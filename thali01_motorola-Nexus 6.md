#### Test 82914073a71b108_thali01_motorola-Nexus 6 Logs


```
--------- beginning of main
08-30 14:40:29.690   875  1309 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 8, 9 -> obsolete
,08-30 14:40:30.360  3944  3944 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
08-30 14:40:30.365  3944  3944 D AndroidRuntime: CheckJNI is OFF
08-30 14:40:30.414  3944  3944 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
08-30 14:40:30.492  3944  3944 I Radio-JNI: register_android_hardware_Radio DONE
08-30 14:40:30.518  3944  3944 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
08-30 14:40:30.523   875  3108 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-30 14:40:30.549  1999  2393 W SearchService: Abort, client detached.
08-30 14:40:30.556  3944  3944 D AndroidRuntime: Shutting down VM
08-30 14:40:30.558  1999  2336 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@d58920c
08-30 14:40:30.558  1999  2354 E AudioRecord-JNI: Error -4 during AudioRecord native read
08-30 14:40:30.558  1999  1999 I HotwordDetector: Closing mic
08-30 14:40:30.571   875  1952 I ActivityManager: Start proc 3953:com.test.thalitest/u0a0 for activity com.test.thalitest/.MainActivity
08-30 14:40:30.634   379  2357 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
08-30 14:40:30.641   379  2357 D audio_hw_primary: disable_snd_device: snd_device(61: voice-rec-mic)
08-30 14:40:30.643  3953  3953 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
08-30 14:40:30.652   379  1281 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
08-30 14:40:30.654  1999  2349 I MicroRecognitionRnrImpl: Stopping hotword detection.
08-30 14:40:30.658  1999  2353 I MicroRecognitionRnrImpl: Detection finished
08-30 14:40:30.665  3953  3953 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
08-30 14:40:30.672  3953  3953 I LibraryLoader: Time to load native libraries: 2 ms (timestamps 6681-6683)
08-30 14:40:30.672  3953  3953 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-30 14:40:30.684  3953  3953 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {4375e29}
08-30 14:40:30.684  3953  3953 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-30 14:40:30.684  3953  3953 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
08-30 14:40:30.692  3953  3953 I BrowserStartupController: Initializing chromium process, singleProcess=true
08-30 14:40:30.693  3953  3953 E SysUtils: ApplicationContext is null in ApplicationStatus
08-30 14:40:30.704  3953  3953 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
08-30 14:40:30.714  3953  3953 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-30 14:40:30.714  3953  3953 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-30 14:40:30.714  3953  3953 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-30 14:40:30.714  3953  3953 I Adreno  : Build Date                       : 10/20/15
08-30 14:40:30.714  3953  3953 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-30 14:40:30.714  3953  3953 I Adreno  : Local Branch                     : M14
08-30 14:40:30.714  3953  3953 I Adreno  : Remote Branch                    : 
08-30 14:40:30.714  3953  3953 I Adreno  : Remote Branch                    : 
08-30 14:40:30.714  3953  3953 I Adreno  : Reconstruct Branch               : 
08-30 14:40:30.755   875   892 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1915e59:true
,08-30 14:40:30.789  3953  3953 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,08-30 14:40:30.801  3953  3953 D SystemWebViewEngine: CordovaWebView is running on device made by: motorola
,08-30 14:40:30.859  3953  3990 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,08-30 14:40:30.868  3953  3977 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,08-30 14:40:30.896  3953  3990 I OpenGLRenderer: Initialized EGL, version 1.4
,08-30 14:40:30.962   875   893 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +402ms
,08-30 14:40:30.970  1864  1864 I Keyboard.Facilitator: onFinishInput()
,08-30 14:40:31.036  3953  3953 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 3953
,08-30 14:40:31.145  3953  3953 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-30 14:40:31.335  3953  3992 D jxcore_app_log: JniHelper::setJavaVM(0xb4dbc000), pthread_self() = -1716061904
,08-30 14:40:31.348  3953  3992 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-30 14:40:31.348  3953  3992 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-30 14:40:31.348  3953  3992 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-30 14:40:31.348  3953  3992 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-30 14:40:31.348  3953  3992 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,08-30 14:40:31.348  3953  3992 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fb56634 added. We now have 1 listener(s)
08-30 14:40:31.352  3953  3992 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: F8:CF:C5:D9:E5:61
08-30 14:40:31.354   875  1952 I ActivityManager: Killing 3587:com.google.android.apps.books/u0a34 (adj 15): empty #17
08-30 14:40:31.354  3953  3992 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-30 14:40:31.355  3953  3992 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-30 14:40:31.356  3953  3992 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-30 14:40:31.360  3953  3992 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-30 14:40:31.360  3953  3992 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-30 14:40:31.360  3953  3992 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-30 14:40:31.360  3953  3992 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: F8:CF:C5:D9:E5:61
08-30 14:40:31.360  3953  3992 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-30 14:40:31.360  3953  3992 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-30 14:40:31.360  3953  3992 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-30 14:40:31.360  3953  3992 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-30 14:40:31.360  3953  3992 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-30 14:40:31.360  3953  3992 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-30 14:40:31.360  3953  3992 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-30 14:40:31.360  3953  3992 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-30 14:40:31.360  3953  3992 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-30 14:40:31.360  3953  3992 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,08-30 14:40:31.360  3953  3992 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b79aa3 added. We now have 1 listener(s)
08-30 14:40:31.360  3953  3992 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-30 14:40:31.365   875  1310 D WifiService: New client listening to asynchronous messages
,08-30 14:40:31.366  3953  3992 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-30 14:40:31.366  3953  3992 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
,08-30 14:40:31.368  3953  3992 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
,08-30 14:40:31.368  3953  3992 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
,08-30 14:40:31.368  3953  3992 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,08-30 14:40:31.407   875  1952 I ActivityManager: Killing 3017:com.google.android.keep/u0a79 (adj 15): empty #18
,08-30 14:40:31.460  3953  3992 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-30 14:40:31.461  3953  3992 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is F8:CF:C5:D9:E5:61
,08-30 14:40:31.468  3953  3992 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,08-30 14:40:31.468  3953  3992 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 14:40:31.468  3953  3992 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 14:40:31.468  3953  3992 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 14:40:31.468  3953  3992 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 14:40:31.468  3953  3992 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 14:40:31.468  3953  3992 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 14:40:31.468  3953  3992 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 14:40:31.468  3953  3992 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-30 14:40:31.468  3953  3992 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
,08-30 14:40:31.468  3953  3992 D io.jxcore.node.ConnectivityMonitor: start: OK
08-30 14:40:31.468  3953  3992 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-30 14:40:31.544  3953  3953 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 14:40:31.547  3953  3953 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 14:40:31.549  3953  3953 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-30 14:40:32.307  3953  4001 W jxcore-log: Initializing JXcore engine
08-30 14:40:32.307  3953  4001 W jxcore-log: JXcore engine is ready
,08-30 14:40:32.347  4001  4001 W Thread-337: type=1400 audit(0.0:4): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=8984 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,08-30 14:40:32.347  4001  4001 W Thread-337: type=1400 audit(0.0:5): avc: denied { ioctl } for path="socket:[10883]" dev="sockfs" ino=10883 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
08-30 14:40:32.347  4001  4001 W Thread-337: type=1400 audit(0.0:6): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,08-30 14:40:32.347  4001  4001 W Thread-337: type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[26757]" dev="sockfs" ino=26757 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,08-30 14:40:32.361  3953  4001 W jxcore-log: Starting JXcore engine
,08-30 14:40:32.496  3953  4001 W jxcore-log: Platform android
08-30 14:40:32.496  3953  4001 W jxcore-log: 
,08-30 14:40:32.496  3953  4001 W jxcore-log: Process ARCH arm
08-30 14:40:32.496  3953  4001 W jxcore-log: 
,08-30 14:40:32.798  3953  4001 I jxcore-log: JXcore Cordova bridge is ready!
08-30 14:40:32.798  3953  4001 I jxcore-log: 
,08-30 14:40:32.799  3953  4001 W jxcore-log: JXcore engine is started
,08-30 14:40:32.804  3953  3992 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,08-30 14:40:32.807  3953  3953 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-30 14:40:33.519   875  3910 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: Probably not a portal: exception java.net.SocketTimeoutException
,08-30 14:40:33.521   875  1311 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] validation failed
,08-30 14:40:33.526   875  1309 E WifiConfigStore:  rewrite network history for "NG700"WPA_PSK
,08-30 14:40:34.527   875  3910 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.214.206
,08-30 14:40:36.106   875  3910 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 30 Aug 2016 12:40:35 GMT], X-Android-Received-Millis=[1472560836104], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1472560835315]}
,08-30 14:40:36.109   875  1311 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
08-30 14:40:36.110   875  1311 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] validation  passed
08-30 14:40:36.111   875  1311 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
08-30 14:40:36.115   875  1311 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
08-30 14:40:36.119   875  1309 E WifiConfigStore:  rewrite network history for "NG700"WPA_PSK
,08-30 14:40:40.889  1540  1540 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-30 14:40:40.902  1540  1540 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-30 14:40:40.909  1540  1540 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-30 14:40:40.962  1540  1559 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,08-30 14:40:40.963  1540  1559 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
08-30 14:40:40.963  1540  1559 I GLSUser : [GLSUser] Extracting token using key: Auth
08-30 14:40:40.963  1540  1559 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-30 14:40:40.999  3498  3498 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
08-30 14:40:40.999  3498  3498 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
08-30 14:40:41.000  3498  3498 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 3.
,08-30 14:40:42.704  3953  4001 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-30 14:40:42.704  3953  4001 I jxcore-log: 
,08-30 14:40:42.706  3953  4001 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-30 14:40:42.706  3953  4001 I jxcore-log: 
,08-30 14:40:42.719  3953  4001 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 14:40:42.719  3953  4001 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 14:40:42.719  3953  4001 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 14:40:42.719  3953  4001 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 14:40:42.719  3953  4001 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 14:40:42.719  3953  4001 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 14:40:42.719  3953  4001 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 14:40:42.719  3953  4001 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-30 14:40:42.726  3953  4001 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-30 14:40:42.732  3953  4001 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-30 14:40:42.732  3953  4001 I jxcore-log: 
,08-30 14:40:42.739  3953  4001 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-30 14:40:42.739  3953  4001 I jxcore-log: 
,08-30 14:40:43.279  3953  4001 D executeNativeTests: Running unit tests
,08-30 14:40:43.338  3953  4001 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-30 14:40:43.338  3953  4001 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d9c11ed added. We now have 2 listener(s)
08-30 14:40:43.339  3953  4001 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-30 14:40:43.339  3953  4001 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-30 14:40:43.339  3953  4001 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-30 14:40:43.340  3953  4001 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 14:40:43.340  3953  4001 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3380822 added. We now have 2 listener(s)
08-30 14:40:43.340  3953  4001 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-30 14:40:43.342  3953  4001 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-30 14:40:43.346  3953  4001 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-30 14:40:43.353  3953  4001 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 14:40:43.353  3953  4001 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 14:40:43.353  3953  4001 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 14:40:43.353  3953  4001 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 14:40:43.353  3953  4001 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 14:40:43.353  3953  4001 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 14:40:43.353  3953  4001 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 14:40:43.353  3953  4001 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-30 14:40:43.360  3953  4001 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-30 14:40:43.360  3953  4001 D io.jxcore.node.ConnectivityMonitor: start: OK
08-30 14:40:43.362  3953  4001 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,08-30 14:40:43.364  3953  4001 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-30 14:40:43.364  3953  4001 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-30 14:40:43.366  3953  4001 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
,08-30 14:40:43.366  3953  4001 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-30 14:40:43.366  3953  4001 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-30 14:40:43.366  3953  4001 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,08-30 14:40:43.366  3953  4001 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-30 14:40:43.367  3953  4001 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-30 14:40:43.367  3953  4001 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-30 14:40:43.367  3953  4001 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 14:40:43.368  3953  4001 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 14:40:43.368  3953  4001 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 14:40:43.368  3953  4001 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-30 14:40:43.368  3953  4001 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-30 14:40:43.368  3953  4001 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d9c11ed removed from the list
08-30 14:40:43.368  3953  4001 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-30 14:40:43.368  3953  4001 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3380822 removed from the list
08-30 14:40:43.369  3953  3953 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 14:40:43.369  3953  4001 D io.jxcore.node.ConnectivityMonitor: stop
08-30 14:40:43.369  3953  4001 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 14:40:43.370  3953  4001 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 14:40:43.370  3953  4001 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 14:40:43.374  3953  4001 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-30 14:40:43.374  3953  4001 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 14:40:43.374  3953  4001 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 14:40:43.374  3953  4001 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3380822 not in the list
,08-30 14:40:43.381  3953  3953 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 14:40:43.382  3953  4001 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
08-30 14:40:43.382  3953  4001 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-30 14:40:43.382  3953  4001 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 14:40:43.383  3953  4001 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 14:40:43.383  3953  4001 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 14:40:43.383  3953  4001 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 14:40:43.383  3953  4001 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 14:40:43.383  3953  4001 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d9c11ed not in the list
08-30 14:40:43.383  3953  4001 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 14:40:43.383  3953  4001 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3380822 not in the list
08-30 14:40:43.383  3953  4001 D io.jxcore.node.ConnectivityMonitor: stop
08-30 14:40:43.383  3953  4001 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 14:40:43.383  3953  4001 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 14:40:43.383  3953  4001 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-30 14:40:43.383  3953  4001 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-30 14:40:43.384  3953  4001 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 14:40:43.384  3953  4001 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 14:40:43.384  3953  4001 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-30 14:40:43.384  3953  4001 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3380822 not in the list
08-30 14:40:43.389  3953  4001 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-30 14:40:43.389  3953  4001 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-30 14:40:43.389  3953  4001 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-30 14:40:43.389  3953  4001 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-30 14:40:43.389  3953  4001 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-30 14:40:43.389  3953  4001 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-30 14:40:43.389  3953  4001 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-30 14:40:43.389  3953  4001 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-30 14:40:43.389  3953  4001 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-30 14:40:43.389  3953  4001 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-30 14:40:43.389  3953  4001 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-30 14:40:43.389  3953  4001 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-30 14:40:43.389  3953  4001 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-30 14:40:43.390  3953  4001 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-30 14:40:43.390  3953  4001 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
,08-30 14:40:43.390  3953  4001 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-30 14:40:43.390  3953  4001 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-30 14:40:43.390  3953  4001 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-30 14:40:43.390  3953  4001 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-30 14:40:43.390  3953  4001 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-30 14:40:43.390  3953  4001 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-30 14:40:43.390  3953  4001 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-30 14:40:43.390  3953  4001 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-30 14:40:43.390  3953  4001 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-30 14:40:43.390  3953  4001 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-30 14:40:43.390  3953  4001 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-30 14:40:43.390  3953  4001 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-30 14:40:43.390  3953  4001 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-30 14:40:43.390  3953  4001 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-30 14:40:43.390  3953  4001 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-30 14:40:43.390  3953  4001 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-30 14:40:43.390  3953  4001 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 14:40:43.390  3953  4001 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 14:40:43.391  3953  4001 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-30 14:40:43.391  3953  4001 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 14:40:43.391  3953  4001 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 14:40:43.391  3953  4001 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 14:40:43.392  3953  4001 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d9c11ed not in the list
08-30 14:40:43.392  3953  4001 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 14:40:43.392  3953  4001 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3380822 not in the list
08-30 14:40:43.392  3953  4001 D io.jxcore.node.ConnectivityMonitor: stop
08-30 14:40:43.392  3953  4001 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 14:40:43.392  3953  4001 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 14:40:43.392  3953  4001 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 14:40:43.392  3953  4001 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 14:40:43.394  3953  4001 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 14:40:43.394  3953  4001 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 14:40:43.394  3953  4001 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 14:40:43.394  3953  4001 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3380822 not in the list
08-30 14:40:43.395  3953  4001 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,08-30 14:40:43.396  3953  4001 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-30 14:40:43.401  3953  4001 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 14:40:43.401  3953  4001 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 14:40:43.401  3953  4001 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 14:40:43.401  3953  4001 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 14:40:43.401  3953  4001 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 14:40:43.401  3953  4001 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 14:40:43.401  3953  4001 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 14:40:43.401  3953  4001 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-30 14:40:43.402  3953  4001 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-30 14:40:43.402  3953  4001 D io.jxcore.node.ConnectivityMonitor: start: OK
08-30 14:40:43.403  3953  4001 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-30 14:40:43.403  3953  4001 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-30 14:40:43.404  3953  4001 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-30 14:40:43.404  3953  3953 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 14:40:43.405  3953  4001 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 14:40:43.405  3953  4001 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-30 14:40:43.408  3953  3953 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 14:40:43.409  3953  4001 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-30 14:40:43.409  3953  4001 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-30 14:40:43.413  3953  4001 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-30 14:40:43.418  3953  4001 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,08-30 14:40:43.419  3953  4001 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-30 14:40:43.420  3953  4001 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
,08-30 14:40:43.425  3953  4001 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
,08-30 14:40:43.425  3953  4001 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-30 14:40:43.425  3953  4001 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-30 14:40:43.426  3953  4001 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-30 14:40:43.426  3953  4001 D BluetoothAdapter: STATE_ON
,08-30 14:40:43.431  2678  2692 D BtGatt.GattService: registerClient() - UUID=1d6aa176-1dd6-4775-8735-494db388ff07
,08-30 14:40:43.433  2678  2702 D BtGatt.GattService: onClientRegistered() - UUID=1d6aa176-1dd6-4775-8735-494db388ff07, clientIf=5
,08-30 14:40:43.435  3953  3963 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,08-30 14:40:43.436  2678  2689 D BtGatt.GattService: start scan with filters
,08-30 14:40:43.439  3953  4001 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-30 14:40:43.439  3953  4001 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-30 14:40:43.439  3953  4001 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-30 14:40:43.439  3953  4001 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
08-30 14:40:43.439  2678  2705 D BtGatt.ScanManager: handling starting scan
,08-30 14:40:43.441  3953  4001 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-30 14:40:43.441  3953  3953 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-30 14:40:43.442  3953  4001 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-30 14:40:43.443  3953  4001 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
08-30 14:40:43.443  2678  2705 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@335a16b
,08-30 14:40:43.445  3953  4001 I io.jxcore.node.ConnectionHelper: start: OK
,08-30 14:40:43.448  3953  4001 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-30 14:40:43.448  3953  4001 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-30 14:40:43.448  3953  4001 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-30 14:40:43.448  3953  4001 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-30 14:40:43.448  3953  4001 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 14:40:43.448  3953  4001 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-30 14:40:43.448  3953  4001 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-30 14:40:43.448  3953  4001 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-30 14:40:43.448  3953  4001 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,08-30 14:40:43.448  3953  4001 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-30 14:40:43.449  3953  4001 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-30 14:40:43.449  3953  4001 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-30 14:40:43.450  3953  4001 D BluetoothAdapter: STATE_ON
08-30 14:40:43.450  2678  2692 D BtGatt.GattService: stopScan() - queue size =1
08-30 14:40:43.452  2678  2702 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-30 14:40:43.452  2678  2702 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-30 14:40:43.453  2678  2689 D BtGatt.GattService: unregisterClient() - clientIf=5
08-30 14:40:43.453  2678  2705 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
08-30 14:40:43.454  3953  4001 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-30 14:40:43.454  3953  4001 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-30 14:40:43.455  3953  4001 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,08-30 14:40:43.455  3953  4001 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-30 14:40:43.455  3953  4001 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-30 14:40:43.456  3953  4001 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-30 14:40:43.456  3953  4001 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-30 14:40:43.456  3953  4001 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-30 14:40:43.457  3953  4001 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-30 14:40:43.457  3953  4001 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 14:40:43.459  3953  3953 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-30 14:40:43.459  3953  3953 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-30 14:40:43.459  3953  3953 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-30 14:40:43.459  2678  2702 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-30 14:40:43.459  2678  2702 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-30 14:40:43.460  2678  2705 D BtGatt.ScanManager: Starting BLE batch scan
08-30 14:40:43.460  2678  2705 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-30 14:40:43.460  3953  4001 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 14:40:43.460  3953  4001 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 14:40:43.460  3953  4001 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 14:40:43.460  3953  4001 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d9c11ed not in the list
08-30 14:40:43.460  3953  4001 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-30 14:40:43.460  3953  4001 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3380822 not in the list
08-30 14:40:43.460  3953  4001 D io.jxcore.node.ConnectivityMonitor: stop
08-30 14:40:43.460  3953  4001 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 14:40:43.461  3953  4001 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-30 14:40:43.463  3953  4001 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-30 14:40:43.468  3953  4001 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 14:40:43.468  3953  4001 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 14:40:43.468  3953  4001 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 14:40:43.468  3953  4001 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 14:40:43.468  3953  4001 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 14:40:43.468  3953  4001 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 14:40:43.468  3953  4001 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 14:40:43.468  3953  4001 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-30 14:40:43.469  2678  2702 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-30 14:40:43.469  2678  2702 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-30 14:40:43.470  3953  4001 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-30 14:40:43.471  3953  4001 D io.jxcore.node.ConnectivityMonitor: start: OK
08-30 14:40:43.471  3953  4001 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-30 14:40:43.471  3953  4001 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,08-30 14:40:43.471  3953  4001 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-30 14:40:43.472  3953  4001 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 14:40:43.472  3953  4001 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-30 14:40:43.474  3953  3953 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 14:40:43.475  2678  2702 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-30 14:40:43.475  2678  2702 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-30 14:40:43.477  3953  3953 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 14:40:43.478  3953  4001 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,08-30 14:40:43.478  3953  4001 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-30 14:40:43.482  2678  2702 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-30 14:40:43.482  2678  2702 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-30 14:40:43.482  2678  2705 D BtGatt.ScanManager: stopping BLe Batch
,08-30 14:40:43.487  3953  4001 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-30 14:40:43.488  3953  4001 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-30 14:40:43.488  3953  4001 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-30 14:40:43.489  2678  2702 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-30 14:40:43.489  2678  2702 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-30 14:40:43.489  2678  2705 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-30 14:40:43.492  3953  4001 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-30 14:40:43.492  3953  4001 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-30 14:40:43.493  3953  4001 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-30 14:40:43.494  3953  4001 D BluetoothAdapter: STATE_ON
08-30 14:40:43.494  2678  2702 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-30 14:40:43.494  2678  2702 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-30 14:40:43.497  2678  2692 D BtGatt.GattService: registerClient() - UUID=6a27ccd6-a2c8-44e4-9222-4d38af40bcec
08-30 14:40:43.497  2678  2702 D BtGatt.GattService: onClientRegistered() - UUID=6a27ccd6-a2c8-44e4-9222-4d38af40bcec, clientIf=5
08-30 14:40:43.498  3953  3963 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-30 14:40:43.498  2678  2831 D BtGatt.GattService: start scan with filters
,08-30 14:40:43.503  3953  4001 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-30 14:40:43.503  2678  2705 D BtGatt.ScanManager: handling starting scan
08-30 14:40:43.503  3953  4001 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-30 14:40:43.503  3953  4001 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,08-30 14:40:43.503  3953  4001 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-30 14:40:43.505  3953  4001 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-30 14:40:43.506  3953  4001 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-30 14:40:43.506  3953  3953 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-30 14:40:43.507  3953  4001 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-30 14:40:43.508  3953  4001 I io.jxcore.node.ConnectionHelper: start: OK
08-30 14:40:43.510  3953  4001 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 14:40:43.511  3953  4001 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,08-30 14:40:43.511  3953  4001 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-30 14:40:43.511  2678  2702 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-30 14:40:43.511  2678  2702 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-30 14:40:43.511  3953  4001 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-30 14:40:43.511  3953  4001 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 14:40:43.511  3953  4001 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-30 14:40:43.511  2678  2705 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
08-30 14:40:43.511  3953  4001 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-30 14:40:43.511  3953  4001 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-30 14:40:43.511  3953  4001 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-30 14:40:43.511  3953  4001 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-30 14:40:43.511  3953  4001 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-30 14:40:43.511  3953  4001 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-30 14:40:43.512  3953  4001 D BluetoothAdapter: STATE_ON
,08-30 14:40:43.512  2678  2692 D BtGatt.GattService: stopScan() - queue size =1
08-30 14:40:43.513  2678  2689 D BtGatt.GattService: unregisterClient() - clientIf=5
08-30 14:40:43.513  3953  4001 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-30 14:40:43.513  3953  4001 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-30 14:40:43.513  3953  4001 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-30 14:40:43.513  3953  4001 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-30 14:40:43.513  3953  4001 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-30 14:40:43.514  3953  4001 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-30 14:40:43.515  3953  4001 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-30 14:40:43.515  3953  4001 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-30 14:40:43.515  3953  4001 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-30 14:40:43.515  3953  4001 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 14:40:43.516  3953  3953 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-30 14:40:43.516  3953  3953 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-30 14:40:43.516  3953  3953 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-30 14:40:43.516  3953  4001 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 14:40:43.516  3953  4001 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 14:40:43.516  3953  4001 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 14:40:43.517  3953  4001 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d9c11ed not in the list
08-30 14:40:43.517  3953  4001 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 14:40:43.517  3953  4001 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3380822 not in the list
08-30 14:40:43.517  3953  4001 D io.jxcore.node.ConnectivityMonitor: stop
08-30 14:40:43.517  3953  4001 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 14:40:43.517  3953  4001 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 14:40:43.517  3953  4001 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-30 14:40:43.518  3953  4001 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 14:40:43.518  3953  4001 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 14:40:43.518  3953  4001 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 14:40:43.518  3953  4001 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3380822 not in the list
08-30 14:40:43.518  2678  2702 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-30 14:40:43.518  2678  2702 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-30 14:40:43.519  2678  2705 D BtGatt.ScanManager: Starting BLE batch scan
08-30 14:40:43.519  2678  2705 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-30 14:40:43.519  3953  4001 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,08-30 14:40:43.520  3953  4001 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-30 14:40:43.523  3953  4001 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 14:40:43.523  3953  4001 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 14:40:43.523  3953  4001 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 14:40:43.523  3953  4001 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 14:40:43.523  3953  4001 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 14:40:43.523  3953  4001 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 14:40:43.523  3953  4001 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 14:40:43.523  3953  4001 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-30 14:40:43.525  3953  4001 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-30 14:40:43.525  3953  4001 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-30 14:40:43.526  3953  4001 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-30 14:40:43.526  3953  4001 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-30 14:40:43.526  3953  4001 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-30 14:40:43.526  3953  4001 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 14:40:43.527  3953  4001 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-30 14:40:43.527  3953  3953 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 14:40:43.529  3953  4001 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-30 14:40:43.529  3953  4001 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-30 14:40:43.530  3953  3953 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 14:40:43.532  3953  4001 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-30 14:40:43.533  3953  4001 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-30 14:40:43.533  3953  4001 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-30 14:40:43.533  2678  2702 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,08-30 14:40:43.533  2678  2702 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-30 14:40:43.537  3953  4001 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-30 14:40:43.537  3953  4001 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-30 14:40:43.537  3953  4001 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-30 14:40:43.537  3953  4001 D BluetoothAdapter: STATE_ON
,08-30 14:40:43.540  2678  2702 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-30 14:40:43.540  2678  2702 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-30 14:40:43.540  2678  2689 D BtGatt.GattService: registerClient() - UUID=b50a21c5-18db-46e0-875c-de21a7fbd751
08-30 14:40:43.540  2678  2702 D BtGatt.GattService: onClientRegistered() - UUID=b50a21c5-18db-46e0-875c-de21a7fbd751, clientIf=5
,08-30 14:40:43.541  3953  3964 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-30 14:40:43.541  2678  2812 D BtGatt.GattService: start scan with filters
,08-30 14:40:43.544  3953  4001 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-30 14:40:43.544  3953  4001 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-30 14:40:43.544  3953  4001 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-30 14:40:43.545  3953  4001 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-30 14:40:43.545  2678  2702 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-30 14:40:43.546  2678  2702 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-30 14:40:43.546  2678  2705 D BtGatt.ScanManager: stopping BLe Batch
,08-30 14:40:43.548  3953  4001 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-30 14:40:43.548  3953  3953 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-30 14:40:43.549  3953  4001 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-30 14:40:43.550  3953  4001 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-30 14:40:43.551  2678  2702 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-30 14:40:43.551  2678  2702 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-30 14:40:43.551  2678  2705 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
08-30 14:40:43.553  3953  4001 I io.jxcore.node.ConnectionHelper: start: OK
08-30 14:40:43.553  3953  4001 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-30 14:40:43.553  3953  4001 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-30 14:40:43.554  3953  4001 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-30 14:40:43.554  3953  4001 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-30 14:40:43.554  3953  4001 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 14:40:43.554  3953  4001 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-30 14:40:43.554  3953  4001 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-30 14:40:43.554  3953  4001 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-30 14:40:43.554  3953  4001 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-30 14:40:43.554  3953  4001 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-30 14:40:43.554  3953  4001 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-30 14:40:43.554  3953  4001 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-30 14:40:43.555  3953  4001 D BluetoothAdapter: STATE_ON
,08-30 14:40:43.555  2678  2812 D BtGatt.GattService: stopScan() - queue size =0
08-30 14:40:43.556  2678  2831 D BtGatt.GattService: unregisterClient() - clientIf=5
08-30 14:40:43.556  3953  4001 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-30 14:40:43.556  2678  2702 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-30 14:40:43.556  3953  4001 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,08-30 14:40:43.556  2678  2702 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-30 14:40:43.556  3953  4001 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-30 14:40:43.556  3953  4001 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-30 14:40:43.556  3953  4001 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-30 14:40:43.557  3953  4001 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-30 14:40:43.557  3953  4001 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-30 14:40:43.557  3953  4001 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-30 14:40:43.558  3953  4001 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-30 14:40:43.558  2678  2705 D BtGatt.ScanManager: handling starting scan
08-30 14:40:43.558  3953  4001 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-30 14:40:43.560  3953  3953 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-30 14:40:43.560  3953  3953 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-30 14:40:43.560  3953  3953 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-30 14:40:43.561  3953  4001 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 14:40:43.561  3953  4001 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-30 14:40:43.561  3953  4001 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 14:40:43.561  3953  4001 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-30 14:40:43.561  3953  4001 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 14:40:43.561  3953  4001 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 14:40:43.561  3953  4001 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 14:40:43.561  3953  4001 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d9c11ed not in the list
08-30 14:40:43.561  3953  4001 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 14:40:43.562  3953  4001 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3380822 not in the list
,08-30 14:40:43.562  3953  4001 D io.jxcore.node.ConnectivityMonitor: stop
08-30 14:40:43.562  3953  4001 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 14:40:43.562  3953  4001 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 14:40:43.562  3953  4001 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 14:40:43.563  3953  4001 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 14:40:43.563  3953  4001 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 14:40:43.563  3953  4001 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 14:40:43.563  3953  4001 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3380822 not in the list
08-30 14:40:43.564  2678  2702 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-30 14:40:43.564  2678  2702 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-30 14:40:43.564  3953  4001 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
08-30 14:40:43.564  2678  2705 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
08-30 14:40:43.564  3953  4001 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 14:40:43.564  3953  4001 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 14:40:43.564  3953  4001 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 14:40:43.565  3953  4001 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 14:40:43.565  3953  4001 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 14:40:43.565  3953  4001 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 14:40:43.565  3953  4001 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d9c11ed not in the list
08-30 14:40:43.565  3953  4001 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 14:40:43.565  3953  4001 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3380822 not in the list
08-30 14:40:43.565  3953  4001 D io.jxcore.node.ConnectivityMonitor: stop
,08-30 14:40:43.565  3953  4001 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 14:40:43.565  3953  4001 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 14:40:43.565  3953  4001 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 14:40:43.565  3953  4001 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 14:40:43.567  3953  4001 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 14:40:43.567  3953  4001 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 14:40:43.568  3953  4001 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 14:40:43.568  3953  4001 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3380822 not in the list
,08-30 14:40:43.569  3953  4001 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-30 14:40:43.569  3953  4001 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 14:40:43.569  3953  4001 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 14:40:43.569  3953  4001 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 14:40:43.569  3953  4001 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 14:40:43.569  3953  4001 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-30 14:40:43.569  3953  4001 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 14:40:43.569  3953  4001 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d9c11ed not in the list
08-30 14:40:43.570  3953  4001 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 14:40:43.570  3953  4001 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3380822 not in the list
08-30 14:40:43.570  3953  4001 D io.jxcore.node.ConnectivityMonitor: stop
08-30 14:40:43.570  3953  4001 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 14:40:43.570  3953  4001 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 14:40:43.570  3953  4001 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 14:40:43.570  3953  4001 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 14:40:43.570  2678  2702 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-30 14:40:43.570  2678  2702 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-30 14:40:43.570  2678  2705 D BtGatt.ScanManager: Starting BLE batch scan
,08-30 14:40:43.570  2678  2705 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-30 14:40:43.571  3953  4001 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 14:40:43.571  3953  4001 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 14:40:43.571  3953  4001 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 14:40:43.571  3953  4001 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3380822 not in the list
08-30 14:40:43.572  3953  4001 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
08-30 14:40:43.572  3953  4001 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 14:40:43.572  3953  4001 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 14:40:43.572  3953  4001 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 14:40:43.572  3953  4001 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 14:40:43.572  3953  4001 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 14:40:43.572  3953  4001 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 14:40:43.575  3953  4001 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d9c11ed not in the list
08-30 14:40:43.575  3953  4001 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-30 14:40:43.575  3953  4001 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3380822 not in the list
08-30 14:40:43.575  3953  4001 D io.jxcore.node.ConnectivityMonitor: stop
08-30 14:40:43.575  3953  4001 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 14:40:43.575  3953  4001 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 14:40:43.575  3953  4001 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 14:40:43.575  3953  4001 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-30 14:40:43.576  3953  4001 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 14:40:43.576  3953  4001 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-30 14:40:43.576  3953  4001 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 14:40:43.576  3953  4001 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3380822 not in the list
08-30 14:40:43.577  3953  4001 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
08-30 14:40:43.577  3953  4001 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 14:40:43.577  3953  4001 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 14:40:43.577  3953  4001 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 14:40:43.577  3953  4001 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 14:40:43.577  3953  4001 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 14:40:43.577  3953  4001 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 14:40:43.577  3953  4001 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d9c11ed not in the list
08-30 14:40:43.577  3953  4001 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 14:40:43.577  3953  4001 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3380822 not in the list
08-30 14:40:43.577  3953  4001 D io.jxcore.node.ConnectivityMonitor: stop
08-30 14:40:43.578  3953  4001 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 14:40:43.578  3953  4001 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 14:40:43.578  3953  4001 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 14:40:43.578  3953  4001 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 14:40:43.579  3953  4001 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 14:40:43.579  3953  4001 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 14:40:43.579  3953  4001 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 14:40:43.579  3953  4001 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3380822 not in the list
,08-30 14:40:43.579  3953  4001 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-30 14:40:43.581  3953  4001 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-30 14:40:43.581  3953  4001 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-30 14:40:43.581  3953  4001 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-30 14:40:43.581  3953  4001 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-30 14:40:43.581  3953  4001 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-30 14:40:43.581  3953  4001 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 14:40:43.581  3953  4001 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 14:40:43.581  3953  4001 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 14:40:43.582  2678  2702 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-30 14:40:43.582  3953  4001 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 14:40:43.582  2678  2702 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-30 14:40:43.582  3953  4001 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 14:40:43.582  3953  4001 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 14:40:43.582  3953  4001 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d9c11ed not in the list
08-30 14:40:43.584  3953  4001 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 14:40:43.584  3953  4001 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3380822 not in the list
08-30 14:40:43.584  3953  4001 D io.jxcore.node.ConnectivityMonitor: stop
08-30 14:40:43.584  3953  4001 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 14:40:43.584  3953  4001 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 14:40:43.584  3953  4001 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 14:40:43.584  3953  4001 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 14:40:43.587  3953  4001 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 14:40:43.588  3953  4001 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 14:40:43.588  3953  4001 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 14:40:43.588  3953  4001 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3380822 not in the list
08-30 14:40:43.589  3953  4001 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-30 14:40:43.589  3953  4001 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
08-30 14:40:43.589  3953  4001 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-30 14:40:43.589  2678  2702 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-30 14:40:43.590  2678  2702 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-30 14:40:43.592  3953  4001 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-30 14:40:43.593  3953  4001 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
08-30 14:40:43.593  3953  4001 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-30 14:40:43.593  3953  4001 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-30 14:40:43.593  3953  4001 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-30 14:40:43.593  3953  4001 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-30 14:40:43.593  3953  4001 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-30 14:40:43.593  3953  4001 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-30 14:40:43.593  3953  4001 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-30 14:40:43.593  3953  4001 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-30 14:40:43.593  3953  4001 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-30 14:40:43.593  3953  4001 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-30 14:40:43.593  3953  4001 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-30 14:40:43.593  3953  4001 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-30 14:40:43.593  3953  4001 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-30 14:40:43.594  3953  4001 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-30 14:40:43.594  3953  4001 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-30 14:40:43.594  3953  4001 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-30 14:40:43.594  3953  4001 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-30 14:40:43.594  3953  4001 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-30 14:40:43.594  3953  4001 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-30 14:40:43.594  3953  4001 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-30 14:40:43.594  3953  4001 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-30 14:40:43.594  3953  4001 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-30 14:40:43.594  3953  4001 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-30 14:40:43.595  3953  4001 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-30 14:40:43.595  3953  4001 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-30 14:40:43.595  3953  4001 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-30 14:40:43.595  3953  4001 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-30 14:40:43.596  3953  4001 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-30 14:40:43.596  3953  4001 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-30 14:40:43.596  3953  4001 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-30 14:40:43.596  3953  4001 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
08-30 14:40:43.597  2678  2702 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-30 14:40:43.597  2678  2702 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-30 14:40:43.597  2678  2705 D BtGatt.ScanManager: stopping BLe Batch
08-30 14:40:43.598  3953  4001 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-30 14:40:43.598  3953  4001 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
08-30 14:40:43.598  3953  4001 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-30 14:40:43.598  3953  4001 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-30 14:40:43.598  3953  4001 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
08-30 14:40:43.598  3953  4001 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-30 14:40:43.598  3953  4001 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-30 14:40:43.599  3953  4001 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
08-30 14:40:43.602  2678  2702 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-30 14:40:43.602  2678  2702 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-30 14:40:43.602  3953  4001 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
08-30 14:40:43.602  2678  2705 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
08-30 14:40:43.603  3953  4001 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
08-30 14:40:43.603  3953  4001 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
08-30 14:40:43.604  3953  4001 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
08-30 14:40:43.604  3953  4001 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
08-30 14:40:43.604  3953  4001 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
08-30 14:40:43.604  3953  4001 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-30 14:40:43.604  3953  4001 E io.jxcore.node.ConnectionHelper: connect: Callback is null
08-30 14:40:43.605  3953  4001 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 14:40:43.605  3953  4001 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 14:40:43.605  3953  4001 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 14:40:43.605  3953  4001 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 14:40:43.605  3953  4001 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 14:40:43.605  3953  4001 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 14:40:43.606  3953  4001 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
,08-30 14:40:43.609  3953  4001 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d9c11ed not in the list
08-30 14:40:43.609  3953  4001 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 14:40:43.609  3953  4001 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3380822 not in the list
08-30 14:40:43.609  3953  4001 D io.jxcore.node.ConnectivityMonitor: stop
08-30 14:40:43.609  3953  4001 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 14:40:43.609  3953  4001 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 14:40:43.609  3953  4001 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 14:40:43.609  3953  4001 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 14:40:43.608  3953  4012 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 401)
08-30 14:40:43.610  3953  4013 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 401
08-30 14:40:43.611  3953  4012 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-30 14:40:43.611  3953  4001 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 14:40:43.612  3953  4001 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 14:40:43.612  3953  4001 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 14:40:43.612  3953  4001 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3380822 not in the list
08-30 14:40:43.612  3953  4001 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
08-30 14:40:43.613  3953  4001 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 14:40:43.613  3953  4001 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 14:40:43.613  3953  4001 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 14:40:43.613  2678  2702 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-30 14:40:43.615  2678  2702 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-30 14:40:43.615  3953  4001 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 14:40:43.615  3953  4001 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 14:40:43.615  3953  4001 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 14:40:43.615  3953  4001 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d9c11ed not in the list
08-30 14:40:43.615  3953  4001 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 14:40:43.615  3953  4001 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3380822 not in the list
08-30 14:40:43.615  3953  4001 D io.jxcore.node.ConnectivityMonitor: stop
08-30 14:40:43.615  3953  4001 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 14:40:43.615  3953  4001 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 14:40:43.616  3953  4001 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 14:40:43.616  3953  4001 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 14:40:43.617  3953  4001 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 14:40:43.617  3953  4001 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 14:40:43.617  3953  4001 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 14:40:43.617  3953  4001 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3380822 not in the list
08-30 14:40:43.618  3953  4001 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
08-30 14:40:43.619  3953  4001 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 14:40:43.619  3953  4001 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 14:40:43.619  3953  4001 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 14:40:43.619  3953  4001 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 14:40:43.619  3953  4001 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 14:40:43.619  3953  4001 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 14:40:43.619  3953  4001 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d9c11ed not in the list
08-30 14:40:43.619  3953  4001 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 14:40:43.619  3953  4001 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3380822 not in the list
08-30 14:40:43.619  3953  4001 D io.jxcore.node.ConnectivityMonitor: stop
08-30 14:40:43.619  3953  4001 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 14:40:43.619  3953  4001 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 14:40:43.620  3953  4001 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 14:40:43.620  3953  4001 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 14:40:43.621  3953  4001 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 14:40:43.621  3953  4001 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 14:40:43.621  3953  4001 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 14:40:43.621  3953  4001 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3380822 not in the list
08-30 14:40:43.622  3953  4001 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
08-30 14:40:43.622  3953  4001 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
08-30 14:40:43.622  3953  4001 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-30 14:40:43.622  3953  4001 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
08-30 14:40:43.622  3953  4001 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-30 14:40:43.622  3953  4001 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
08-30 14:40:43.622  3953  4001 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-30 14:40:43.622  3953  4001 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
08-30 14:40:43.622  3953  4001 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-30 14:40:43.622  3953  4001 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
08-30 14:40:43.622  3953  4001 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-30 14:40:43.623  3953  4001 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
08-30 14:40:43.623  3953  4001 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 14:40:43.623  3953  4001 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 14:40:43.623  3953  4001 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 14:40:43.623  3953  4001 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 14:40:43.623  3953  4001 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 14:40:43.623  3953  4001 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 14:40:43.623  3953  4001 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d9c11ed not in the list
08-30 14:40:43.623  3953  4001 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 14:40:43.623  3953  4001 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3380822 not in the list
08-30 14:40:43.623  3953  4001 D io.jxcore.node.ConnectivityMonitor: stop
08-30 14:40:43.624  3953  4001 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 14:40:43.624  3953  4001 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 14:40:43.624  3953  4001 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 14:40:43.624  3953  4001 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 14:40:43.625  3953  4001 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 14:40:43.625  3953  4001 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 14:40:43.625  3953  4001 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 14:40:43.626  3953  4001 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3380822 not in the list
08-30 14:40:43.626  3953  4001 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 14:40:43.626  3953  4001 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 14:40:43.626  3953  4001 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 14:40:43.626  3953  4001 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d9c11ed not in the list
08-30 14:40:43.626  3953  4001 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 14:40:43.626  3953  4001 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3380822 not in the list
08-30 14:40:43.626  3953  4001 D io.jxcore.node.ConnectivityMonitor: stop
08-30 14:40:43.627  3953  4001 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 14:40:43.627  3953  4001 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 14:40:43.627  3953  4001 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 14:40:43.627  3953  4001 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3380822 not in the list
08-30 14:40:43.627  3953  4001 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 14:40:43.627  3953  4001 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 14:40:43.627  3953  4001 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 14:40:43.627  3953  4001 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d9c11ed not in the list
08-30 14:40:43.627  3953  4001 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 14:40:43.627  3953  4001 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 14:40:43.627  3953  4001 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 14:40:43.628  3953  4001 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 14:40:43.628  3953  4001 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 14:40:43.628  3953  4001 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 14:40:43.628  3953  4001 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d9c11ed not in the list
08-30 14:40:43.628  3953  4001 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 14:40:43.628  3953  4001 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3380822 not in the list
08-30 14:40:43.628  3953  4001 D io.jxcore.node.ConnectivityMonitor: stop
08-30 14:40:43.628  3953  4001 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 14:40:43.628  3953  4001 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 14:40:43.628  3953  4001 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 14:40:43.628  3953  4001 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 14:40:43.629  3953  4001 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 14:40:43.629  3953  4001 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 14:40:43.629  3953  4001 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 14:40:43.630  3953  4001 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3380822 not in the list
08-30 14:40:43.631  3953  4001 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
08-30 14:40:43.631  3953  4001 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 14:40:43.632  3953  4001 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
08-30 14:40:43.632  3953  4001 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
08-30 14:40:43.632  3953  4001 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
08-30 14:40:43.633  3953  3953 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
08-30 14:40:43.633  3953  4001 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
08-30 14:40:43.633  3953  4001 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-30 14:40:43.633  3953  4001 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 14:40:43.633  3953  4001 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
08-30 14:40:43.633  3953  4001 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
08-30 14:40:43.633  3953  4001 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
08-30 14:40:43.633  3953  4001 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 14:40:43.633  3953  4001 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
08-30 14:40:43.634  3953  3953 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
08-30 14:40:43.634  3953  4001 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d9c11ed not in the list
08-30 14:40:43.634  3953  4001 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 14:40:43.634  3953  4001 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-30 14:40:43.634  3953  4001 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-30 14:40:43.634  3953  4001 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-30 14:40:43.634  3953  4001 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 14:40:43.634  3953  4001 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 14:40:43.635  3953  4014 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
08-30 14:40:43.635  3953  4001 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-30 14:40:43.635  3953  4001 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3380822 not in the list
08-30 14:40:43.635  3953  3953 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-30 14:40:43.635  3953  4001 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 14:40:43.635  3953  3953 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-30 14:40:43.636  3953  3953 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-30 14:40:43.636  3953  4001 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 14:40:43.636  3953  4001 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 14:40:43.636  3953  4001 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 14:40:43.635  3953  4014 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
08-30 14:40:43.636  3953  4001 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 14:40:43.636  3953  4001 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 14:40:43.636  3953  4001 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d9c11ed not in the list
08-30 14:40:43.636  3953  4001 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 14:40:43.636  3953  4001 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3380822 not in the list
08-30 14:40:43.636  3953  4001 D io.jxcore.node.ConnectivityMonitor: stop
08-30 14:40:43.636  3953  4001 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 14:40:43.636  3953  4001 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 14:40:43.636  3953  4001 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 14:40:43.636  3953  3953 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
08-30 14:40:43.636  3953  4001 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 14:40:43.637  3953  4001 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 14:40:43.637  3953  4001 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 14:40:43.637  3953  4001 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 14:40:43.637  3953  4001 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3380822 not in the list
08-30 14:40:43.638  3953  4001 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
,08-30 14:40:43.638  3953  4001 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-30 14:40:43.638  3953  4001 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-30 14:40:43.639  3953  4001 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-30 14:40:43.640  3953  4001 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 14:40:43.640  3953  4001 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 14:40:43.640  3953  4001 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 14:40:43.640  3953  4001 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 14:40:43.640  3953  4001 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 14:40:43.640  3953  4001 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 14:40:43.640  3953  4001 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d9c11ed not in the list
08-30 14:40:43.640  3953  4001 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 14:40:43.640  3953  4001 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3380822 not in the list
08-30 14:40:43.640  3953  4001 D io.jxcore.node.ConnectivityMonitor: stop
08-30 14:40:43.640  3953  4001 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 14:40:43.640  3953  4001 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 14:40:43.640  3953  4001 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 14:40:43.640  3953  4001 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 14:40:43.643  3953  4001 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 14:40:43.643  3953  4001 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 14:40:43.643  3953  4001 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 14:40:43.644  3953  4001 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3380822 not in the list
08-30 14:40:43.646  3953  4001 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 14:40:43.647  3953  4001 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 14:40:43.647  3953  4001 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 14:40:43.647  3953  4001 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 14:40:43.647  3953  4001 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 14:40:43.647  3953  4001 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 14:40:43.647  3953  4001 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d9c11ed not in the list
08-30 14:40:43.647  3953  4001 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 14:40:43.647  3953  4001 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3380822 not in the list
08-30 14:40:43.647  3953  4001 D io.jxcore.node.ConnectivityMonitor: stop
08-30 14:40:43.647  3953  4001 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 14:40:43.647  3953  4001 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 14:40:43.647  3953  4001 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 14:40:43.647  3953  4001 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 14:40:43.648  3953  4001 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 14:40:43.648  3953  4001 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 14:40:43.648  3953  4001 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 14:40:43.648  3953  4001 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3380822 not in the list
08-30 14:40:43.649  3953  4001 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 14:40:43.649  3953  4001 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 14:40:43.649  3953  4001 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 14:40:43.650  3953  4001 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 14:40:43.650  3953  4001 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 14:40:43.650  3953  4001 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 14:40:43.650  3953  4001 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d9c11ed not in the list
08-30 14:40:43.650  3953  4001 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 14:40:43.650  3953  4001 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3380822 not in the list
08-30 14:40:43.650  3953  4001 D io.jxcore.node.ConnectivityMonitor: stop
08-30 14:40:43.650  3953  4001 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 14:40:43.650  3953  4001 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 14:40:43.650  3953  4001 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 14:40:43.650  3953  4001 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 14:40:43.651  3953  4001 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 14:40:43.651  3953  4001 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 14:40:43.651  3953  4001 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 14:40:43.651  3953  4001 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3380822 not in the list
08-30 14:40:43.655  3953  4001 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
08-30 14:40:43.655  3953  4001 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-30 14:40:43.655  3953  4001 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
08-30 14:40:43.655  3953  4001 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-30 14:40:43.655  3953  4001 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
08-30 14:40:43.655  3953  4001 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-30 14:40:43.656  3953  4001 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-30 14:40:43.656  3953  4001 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
08-30 14:40:43.657  3953  4001 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
08-30 14:40:43.657  3953  4001 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-30 14:40:43.657  3953  4001 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
08-30 14:40:43.657  3953  4001 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-30 14:40:43.657  3953  4001 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
08-30 14:40:43.657  3953  4001 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
08-30 14:40:43.657  3953  4001 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
08-30 14:40:43.658  3953  4001 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
08-30 14:40:43.658  3953  4001 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
08-30 14:40:43.658  3953  4001 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
08-30 14:40:43.658  3953  4001 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
08-30 14:40:43.658  3953  4001 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
08-30 14:40:43.659  3953  4001 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 14:40:43.659  3953  4001 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@a4bba34 added. We now have 2 listener(s)
08-30 14:40:43.659  3953  4001 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 14:40:43.660  3953  4001 D BluetoothAdapter: enable(): BT is already enabled..!
08-30 14:40:43.661   875  1944 D WifiService: setWifiEnabled: true pid=3953, uid=10000
08-30 14:40:43.661   875  1944 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-30 14:40:43.661  3953  4001 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 14:40:43.661  3953  4001 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@d32505d added. We now have 3 listener(s)
08-30 14:40:43.661  3953  4001 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 14:40:43.665  3953  4001 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 14:40:43.666  3953  4001 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@7d6bdd2 added. We now have 4 listener(s)
08-30 14:40:43.666  3953  4001 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 14:40:43.667  3953  4001 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 14:40:43.667  3953  4001 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@6b0fea3 added. We now have 5 listener(s)
08-30 14:40:43.667  3953  4001 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 14:40:43.669   875  1943 D WifiService: setWifiEnabled: false pid=3953, uid=10000
08-30 14:40:43.669   875  1943 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-30 14:40:43.676  2678  2698 D BluetoothAdapterState: Current state: ON, message: 23
08-30 14:40:43.676  2678  2698 D BluetoothAdapterProperties: Setting state to 13
08-30 14:40:43.676  2678  2698 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-30 14:40:43.677  2678  2698 D BluetoothAdapterProperties: onBluetoothDisable()
08-30 14:40:43.678  2678  2698 I BluetoothAdapterState: Entering PendingCommandState
08-30 14:40:43.679  2678  2678 D BluetoothMapService: onReceive
08-30 14:40:43.680  2678  2678 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-30 14:40:43.680  2678  2678 D BluetoothMapService: STATE_TURNING_OFF
08-30 14:40:43.680  2678  2678 D BluetoothMapService: MAP Service closeService in
08-30 14:40:43.680  2678  2678 D BluetoothMapMasInstance0: MAP Service shutdown
08-30 14:40:43.680  2678  2678 D ObexServerSockets0: shutdown(block = true)
08-30 14:40:43.680  2678  2678 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-30 14:40:43.680  2678  2678 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-30 14:40:43.681  2678  2806 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
08-30 14:40:43.681  2678  2844 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
08-30 14:40:43.681  2678  2845 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
08-30 14:40:43.681  3953  3953 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 14:40:43.681  3953  3953 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 14:40:43.681  3953  3953 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 14:40:43.681  3953  3953 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 14:40:43.681  3953  3953 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 14:40:43.681  3953  3953 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 14:40:43.681  3953  3953 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 14:40:43.681  3953  3953 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 14:40:43.681  3953  3953 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-30 14:40:43.682  2678  2678 I BtOppRfcommListener: stopping Accept Thread
08-30 14:40:43.682  2678  3434 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-30 14:40:43.682  2678  3434 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-30 14:40:43.683  3953  3953 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 14:40:43.683  3953  3953 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-30 14:40:43.685  1466  1466 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-30 14:40:43.687   875  1309 D WifiStateMachine: WifiStateMachine: Leaving Connected state
08-30 14:40:43.687   875  1309 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
08-30 14:40:43.687   875  1309 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-30 14:40:43.687   875  1309 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-30 14:40:43.693   875   888 I ActivityManager: Start proc 4017:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
,08-30 14:40:43.693  2678  2702 D BluetoothAdapterProperties: Scan Mode:20
,08-30 14:40:43.694  2678  2698 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
,08-30 14:40:43.696  2678  2678 D HeadsetService: Received stop request...Stopping profile...
,08-30 14:40:43.696  3953  4001 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-30 14:40:43.698   875   875 D BluetoothHeadset: Proxy object disconnected
08-30 14:40:43.698   875   875 D BluetoothHeadset: Proxy object disconnected
08-30 14:40:43.699  1928  2198 D BluetoothHeadset: Proxy object disconnected
,08-30 14:40:43.699  2678  2678 D A2dpService: Received stop request...Stopping profile...
08-30 14:40:43.699   875   875 D BluetoothHeadset: Proxy object disconnected
08-30 14:40:43.700  2678  2818 D A2dpStateMachine: Exit Disconnected: -1
,08-30 14:40:43.700  1354  1365 D BluetoothHeadset: Proxy object disconnected
08-30 14:40:43.701   875  1883 D DhcpClient: Clearing IP address
08-30 14:40:43.702  1354  1354 D HeadsetProfile: Bluetooth service disconnected
08-30 14:40:43.702   375   873 D CommandListener: Clearing all IP addresses on wlan0
08-30 14:40:43.702   875   875 D BluetoothA2dp: Proxy object disconnected
08-30 14:40:43.703  3953  3953 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 14:40:43.703  2678  2678 V BluetoothAdapterState: isTurningOff()=true
08-30 14:40:43.703  2678  2678 V BluetoothAdapterState: isTurningOn()=false
08-30 14:40:43.703  2678  2678 V BluetoothAdapterState: isBleTurningOn()=false
08-30 14:40:43.703  2678  2678 V BluetoothAdapterState: isBleTurningOff()=false
08-30 14:40:43.704  2678  2678 D HidService: Received stop request...Stopping profile...
08-30 14:40:43.704  2678  2678 D HidService: Stopping Bluetooth HidService
08-30 14:40:43.705  3953  4001 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 14:40:43.705   375   873 D CommandListener: Setting iface cfg
08-30 14:40:43.705  3953  4001 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 14:40:43.705  3953  4001 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 14:40:43.705  3953  4001 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 14:40:43.705  3953  4001 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 14:40:43.705  3953  4001 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 14:40:43.705  3953  4001 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 14:40:43.705  3953  4001 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 14:40:43.705  3953  4001 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-30 14:40:43.706  2678  2678 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-30 14:40:43.706  2678  2678 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-30 14:40:43.706  3953  4001 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-30 14:40:43.706  3953  4001 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-30 14:40:43.707  3953  4001 D io.jxcore.node.ConnectivityMonitor: start: OK
08-30 14:40:43.707  2678  2803 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-30 14:40:43.707  2678  2803 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-30 14:40:43.707  2678  2803 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-30 14:40:43.707  2678  2702 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
08-30 14:40:43.707  2678  2702 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
08-30 14:40:43.707  2678  2678 D HealthService: Received stop request...Stopping profile...
08-30 14:40:43.708  1540  3938 V NativeCrypto: Read error: ssl=0x9ae7dc00: I/O error during system call, Connection timed out
08-30 14:40:43.710   875  1309 D WifiStateMachine: Start Disconnecting Watchdog 3
08-30 14:40:43.710  1540  3938 V NativeCrypto: SSL shutdown failed: ssl=0x9ae7dc00: I/O error during system call, Broken pipe
08-30 14:40:43.710   875  1311 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
08-30 14:40:43.711   875  1309 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-30 14:40:43.711   875  1311 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] got DISCONNECTED, was satisfying 3
08-30 14:40:43.712  3953  3953 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 14:40:43.712  3953  3953 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 14:40:43.712  3953  3953 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 14:40:43.712  3953  3953 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 14:40:43.712  3953  3953 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 14:40:43.712  3953  3953 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 14:40:43.712  3953  3953 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 14:40:43.712  3953  3953 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 14:40:43.712  3953  3953 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-30 14:40:43.713   398   398 E Parcel  : Reading a NULL string not supported here.
,08-30 14:40:43.713  3953  3953 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 14:40:43.713  3953  3953 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-30 14:40:43.717  2678  2678 D PanService: Received stop request...Stopping profile...
08-30 14:40:43.717   875  1311 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 102]
08-30 14:40:43.718  2678  2678 V BluetoothAdapterState: isTurningOff()=true
08-30 14:40:43.718  2678  2678 V BluetoothAdapterState: isTurningOn()=false
08-30 14:40:43.719  2678  2678 V BluetoothAdapterState: isBleTurningOn()=false
08-30 14:40:43.719  2678  2678 V BluetoothAdapterState: isBleTurningOff()=false
08-30 14:40:43.719  2678  2678 V BluetoothAdapterState: isTurningOff()=true
08-30 14:40:43.720  2678  2678 V BluetoothAdapterState: isTurningOn()=false
08-30 14:40:43.720  2678  2678 V BluetoothAdapterState: isBleTurningOn()=false
08-30 14:40:43.720  2678  2678 V BluetoothAdapterState: isBleTurningOff()=false
08-30 14:40:43.720  2678  2702 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
08-30 14:40:43.720  2678  2803 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-30 14:40:43.720  2678  2803 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-30 14:40:43.720  2678  2803 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-30 14:40:43.720  2678  2803 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-30 14:40:43.720  2678  2803 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-30 14:40:43.720  2678  2803 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-30 14:40:43.721   375   873 D CommandListener: Clearing all IP addresses on wlan0
08-30 14:40:43.721  2678  2678 D BluetoothMapService: Received stop request...Stopping profile...
08-30 14:40:43.721  2678  2678 D BluetoothMapService: stop()
08-30 14:40:43.721  2678  2678 D BluetoothMapAppObserver: deinitObservers()
08-30 14:40:43.721  2678  2678 D BluetoothMapAppObserver: removeReceiver()
08-30 14:40:43.722  3953  3953 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 14:40:43.722  3953  3953 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 14:40:43.722  3953  3953 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 14:40:43.722  3953  3953 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 14:40:43.722  3953  3953 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 14:40:43.722  3953  3953 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 14:40:43.722  3953  3953 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 14:40:43.722  3953  3953 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 14:40:43.722  3953  3953 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-30 14:40:43.726  2678  2678 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-30 14:40:43.726  2678  2702 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
08-30 14:40:43.726  2678  2678 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-30 14:40:43.726  2678  2678 V BluetoothAdapterState: isTurningOff()=true
08-30 14:40:43.726  2678  2678 V BluetoothAdapterState: isTurningOn()=false
08-30 14:40:43.726  2678  2678 V BluetoothAdapterState: isBleTurningOn()=false
08-30 14:40:43.726  2678  2678 V BluetoothAdapterState: isBleTurningOff()=false
08-30 14:40:43.727  2678,  2678 V BluetoothAdapterState: isTurningOff()=true
08-30 14:40:43.727  2678  2678 V BluetoothAdapterState: isTurningOn()=false
08-30 14:40:43.727  2678  2678 V BluetoothAdapterState: isBleTurningOn()=false
08-30 14:40:43.727  2678  2678 V BluetoothAdapterState: isBleTurningOff()=false
08-30 14:40:43.727  2678  2678 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-30 14:40:43.728  2678  2702 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
08-30 14:40:43.728  2678  2678 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-30 14:40:43.728  1354  1354 D BluetoothA2dp: Proxy object disconnected
08-30 14:40:43.729  1354  1354 D BluetoothInputDevice: Proxy object disconnected
08-30 14:40:43.729  1354  1354 D HidProfile: Bluetooth service disconnected
08-30 14:40:43.729  2678  2678 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-30 14:40:43.729  1354  1354 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-30 14:40:43.729  2678  2678 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-30 14:40:43.729  1354  1354 D PanProfile: Bluetooth service disconnected
08-30 14:40:43.732  2678  2678 D BluetoothMapService: MAP Service closeService in
08-30 14:40:43.732  2678  2678 V BluetoothAdapterState: isTurningOff()=true
08-30 14:40:43.733  2678  2678 V BluetoothAdapterState: isTurningOn()=false
08-30 14:40:43.733  2678  2678 V BluetoothAdapterState: isBleTurningOn()=false
08-30 14:40:43.733  2678  2678 V BluetoothAdapterState: isBleTurningOff()=false
08-30 14:40:43.733  2678  2678 D BluetoothMapService: cleanup()
08-30 14:40:43.733  2678  2678 D BluetoothMapService: MAP Service closeService in
08-30 14:40:43.735   875  3912 D DhcpClient: Receive thread stopped
08-30 14:40:43.735  2678  2698 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
08-30 14:40:43.735  2678  2698 D BluetoothAdapterProperties: Setting state to 15
08-30 14:40:43.735  2678  2698 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
08-30 14:40:43.735  3953  3953 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 14:40:43.735  3953  3953 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 14:40:43.735  3953  3953 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 14:40:43.735  3953  3953 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 14:40:43.735  3953  3953 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 14:40:43.735  3953  3953 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 14:40:43.735  3953  3953 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 14:40:43.735  3953  3953 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 14:40:43.735  3953  3953 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-30 14:40:43.736   875  1309 D WifiConfigStore: Retrieve network priorities after PNO.
08-30 14:40:43.737  2678  2698 I BluetoothAdapterState: Entering BleOnState
08-30 14:40:43.737  1354  2040 D BluetoothPan: onBluetoothStateChange on: false
08-30 14:40:43.738  3953  3953 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 14:40:43.738  3953  3953 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-30 14:40:43.738  1354  1354 D BluetoothMap: Proxy object disconnected
08-30 14:40:43.738  1354  1365 D BluetoothPbap: onBluetoothStateChange: up=false
08-30 14:40:43.739  1354  2040 D BluetoothA2dp: onBluetoothStateChange: up=false
08-30 14:40:43.740  3953  3953 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 14:40:43.740  3953  3953 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 14:40:43.740  3953  3953 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 14:40:43.740  3953  3953 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 14:40:43.740  3953  3953 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 14:40:43.740  3953  3953 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 14:40:43.740  3953  3953 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 14:40:43.740  3953  3953 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 14:40:43.740  3953  3953 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-30 14:40:43.740  1928  1945 D BluetoothHeadset: onBluetoothStateChange: up=false
08-30 14:40:43.740   875   892 D BluetoothA2dp: onBluetoothStateChange: up=false
08-30 14:40:43.740  3953  3953 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 14:40:43.740  1354  1365 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-30 14:40:43.740  3953  3953 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-30 14:40:43.740  2134  2310 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 14:40:43.740   875   892 D BluetoothHeadset: onBluetoothStateChange: up=false
08-30 14:40:43.741   875   892 D BluetoothHeadset: onBluetoothStateChange: up=false
08-30 14:40:43.741  1354  2040 D BluetoothMap: onBluetoothStateChange: up=false
08-30 14:40:43.742   875   892 D BluetoothHeadset: onBluetoothStateChange: up=false
08-30 14:40:43.742  1354  1365 D BluetoothHeadset: onBluetoothStateChange: up=false
08-30 14:40:43.742  2678  2698 D BluetoothAdapterState: Current state: BLE ON, message: 20
08-30 14:40:43.742  2678  2698 D BluetoothAdapterProperties: Setting state to 16
08-30 14:40:43.743  2678  2698 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
08-30 14:40:43.743  2678  2698 D BluetoothAdapterProperties: onBleDisable
08-30 14:40:43.743  2678  2698 I BluetoothAdapterState: Entering PendingCommandState
08-30 14:40:43.744  2678  2699 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
08-30 14:40:43.744  2678  2702 D BluetoothAdapterProperties: Scan Mode:20
08-30 14:40:43.744  1354  1354 D MapProfile: Bluetooth service disconnected
08-30 14:40:43.745   875  1309 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-30 14:40:43.745  3953  3953 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 14:40:43.746  2678  2803 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
08-30 14:40:43.746  2678  2803 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-30 14:40:43.747  3953  4012 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 401)
08-30 14:40:43.747  3953  3953 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 14:40:43.749  3953  3953 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 14:40:43.750  3953  3953 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 14:40:43.777   375   873 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-30 14:40:43.781  4017  4017 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm
,08-30 14:40:43.793  4017  4017 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-30 14:40:43.795   375   873 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-30 14:40:43.796   875  1311 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
08-30 14:40:43.796   875  1311 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-30 14:40:43.798   875   892 D Tethering: MasterInitialState.processMessage what=3
,08-30 14:40:43.803  3953  3953 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 14:40:43.803  1540  1540 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-30 14:40:43.804  3953  3953 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 14:40:43.815   875  1997 I ActivityManager: Start proc 4034:com.google.android.apps.maps/u0a65 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,08-30 14:40:43.817   875   892 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@d139eb7:true
,08-30 14:40:43.843  4017  4017 D LocalBluetoothProfileManager: Adding local MAP profile
,08-30 14:40:43.844  4017  4017 D BluetoothMap: Create BluetoothMap proxy object
,08-30 14:40:43.851  4034  4034 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm
,08-30 14:40:43.853  4017  4017 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,08-30 14:40:43.853   375   873 E Netd    : netlink response contains error (No such file or directory)
,08-30 14:40:43.868  4017  4017 D DockEventReceiver: finishStartingService: stopping service
,08-30 14:40:43.870   875  1943 I ActivityManager: Killing 3460:com.android.providers.calendar/u0a3 (adj 15): empty #17
,08-30 14:40:43.953  2678  2702 I bt_hci  : shut_down
,08-30 14:40:43.961  2678  2706 I bt_vendor: low_power_mode_cb
,08-30 14:40:43.965  2678  2706 D bt_hwcfg: hw_epilog_process
,08-30 14:40:43.980  2678  2706 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,08-30 14:40:43.980  2678  2706 I bt_vendor: epilog_cb
08-30 14:40:43.980  2678  2706 I bt_hci  : epilog_finished_callback
,08-30 14:40:43.983  2678  2702 I bt_hci_h4: hal_close
08-30 14:40:43.984  2678  2702 I bt_userial_vendor: device fd = 51 close
,08-30 14:40:44.068  4034  4034 D StrictMode: StrictMode policy violation; ~duration=137 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-30 14:40:44.068  4034  4034 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-30 14:40:44.068  4034  4034 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-30 14:40:44.068  4034  4034 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-30 14:40:44.068  4034  4034 D StrictMode: 	at java.io.File.exists(File.java:361)
08-30 14:40:44.068  4034  4034 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
08-30 14:40:44.068  4034  4034 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
08-30 14:40:44.068  4034  4034 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
08-30 14:40:44.068  4034  4034 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-30 14:40:44.068  4034  4034 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-30 14:40:44.068  4034  4034 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-30 14:40:44.068  4034  4034 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-30 14:40:44.068  4034  4034 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-30 14:40:44.068  4034  4034 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-30 14:40:44.068  4034  4034 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-30 14:40:44.068  4034  4034 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-30 14:40:44.068  4034  4034 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-30 14:40:44.068  4034  4034 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-30 14:40:44.068  4034  4034 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-30 14:40:44.068  4034  4034 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-30 14:40:44.068  4034  4034 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-30 14:40:44.068  4034  4034 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 14:40:44.068  4034  4034 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-30 14:40:44.068  4034  4034 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-30 14:40:44.068  4034  4034 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 14:40:44.068  4034  4034 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-30 14:40:44.068  4034  4034 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-30 14:40:44.069  4034  4034 D StrictMode: StrictMode policy violation; ~duration=136 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-30 14:40:44.069  4034  4034 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-30 14:40:44.069  4034  4034 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
08-30 14:40:44.069  4034  4034 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-30 14:40:44.069  4034  4034 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-30 14:40:44.069  4034  4034 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
08-30 14:40:44.069  4034  4034 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-30 14:40:44.069  4034  4034 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-30 14:40:44.069  4034  4034 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-30 14:40:44.069  4034  4034 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-30 14:40:44.069  4034  4034 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-30 14:40:44.069  4034  4034 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-30 14:40:44.069  4034  4034 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-30 14:40:44.069  4034  4034 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-30 14:40:44.069  4034  4034 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-30 14:40:44.069  4034  4034 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-30 14:40:44.069  4034  4034 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-30 14:40:44.069  4034  4034 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-30 14:40:44.069  4034  4034 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-30 14:40:44.069  4034  4034 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 14:40:44.069  4034  4034 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-30 14:40:44.069  4034  4034 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-30 14:40:44.069  4034  4034 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 14:40:44.069  4034  4034 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-30 14:40:44.069  4034  4034 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-30 14:40:44.069  4034  4034 D StrictMode: StrictMode policy violation; ~duration=135 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-30 14:40:44.069  4034  4034 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-30 14:40:44.069  4034  4034 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
08-30 14:40:44.069  4034  4034 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
08-30 14:40:44.069  4034  4034 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-30 14:40:44.069  4034  4034 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
08-30 14:40:44.069  4034  4034 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-30 14:40:44.069  4034  4034 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-30 14:40:44.069  4034  4034 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-30 14:40:44.069  4034  4034 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-30 14:40:44.069  4034  4034 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-30 14:40:44.069  4034  4034 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-30 14:40:44.069  4034  4034 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-30 14:40:44.069  4034  4034 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-30 14:40:44.069  4034  4034 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-30 14:40:44.069  4034  4034 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-30 14:40:44.069  4034  4034 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-30 14:40:44.069  4034  4034 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-30 14:40:44.069  4034  4034 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-30 14:40:44.069  4034  4034 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 14:40:44.069  4034  4034 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-30 14:40:44.069  4034  4034 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-30 14:40:44.069  4034  4034 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 14:40:44.069  4034  4034 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-30 14:40:44.069  4034  4034 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-30 14:40:44.069  4034  4034 D StrictMode: StrictMode policy violation; ~duration=135 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-30 14:40:44.069  4034  4034 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-30 14:40:44.069  4034  4034 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-30 14:40:44.069  4034  4034 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
08-30 14:40:44.069  4034  4034 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-30 14:40:44.069  4034  4034 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-30 14:40:44.069  4034  4034 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-30 14:40:44.069  4034  4034 D StrictMode: 	at com.google.r.k.d(PG:1187)
08-30 14:40:44.069  4034  4034 D StrictMode: 	at com.google.r.k.a(PG:2107)
08-30 14:40:44.069  4034  4034 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
08-30 14:40:44.069  4034  4034 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
08-30 14:40:44.069  4034  4034 D StrictMode: 	at com.google.r.v.a(PG:1161)
08-30 14:40:44.069  4034  4034 D StrictMode: 	at com.google.r.y.a(PG:2188)
08-30 14:40:44.069  4,034  4034 D StrictMode: 	at com.google.r.e.b(PG:170)
08-30 14:40:44.069  4034  4034 D StrictMode: 	at com.google.r.e.b(PG:15188)
08-30 14:40:44.069  4034  4034 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
08-30 14:40:44.069  4034  4034 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-30 14:40:44.069  4034  4034 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-30 14:40:44.069  4034  4034 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-30 14:40:44.069  4034  4034 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-30 14:40:44.069  4034  4034 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-30 14:40:44.069  4034  4034 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-30 14:40:44.069  4034  4034 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-30 14:40:44.069  4034  4034 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-30 14:40:44.069  4034  4034 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-30 14:40:44.069  4034  4034 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-30 14:40:44.069  4034  4034 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-30 14:40:44.069  4034  4034 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 14:40:44.069  4034  4034 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-30 14:40:44.069  4034  4034 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-30 14:40:44.069  4034  4034 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 14:40:44.069  4034  4034 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-30 14:40:44.069  4034  4034 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-30 14:40:44.069  4034  4034 D StrictMode: StrictMode policy violation; ~duration=119 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-30 14:40:44.069  4034  4034 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-30 14:40:44.069  4034  4034 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-30 14:40:44.069  4034  4034 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
08-30 14:40:44.069  4034  4034 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-30 14:40:44.069  4034  4034 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-30 14:40:44.069  4034  4034 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-30 14:40:44.069  4034  4034 D StrictMode: 	at com.google.r.k.d(PG:1187)
08-30 14:40:44.069  4034  4034 D StrictMode: 	at com.google.r.k.c(PG:18147)
08-30 14:40:44.069  4034  4034 D StrictMode: 	at com.google.r.k.d(PG:583)
08-30 14:40:44.069  4034  4034 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
08-30 14:40:44.069  4034  4034 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
08-30 14:40:44.069  4034  4034 D StrictMode: 	at com.google.r.v.a(PG:1161)
08-30 14:40:44.069  4034  4034 D StrictMode: 	at com.google.r.y.a(PG:2188)
08-30 14:40:44.069  4034  4034 D StrictMode: 	at com.google.r.e.b(PG:170)
08-30 14:40:44.069  4034  4034 D StrictMode: 	at com.google.r.e.b(PG:15188)
08-30 14:40:44.069  4034  4034 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
08-30 14:40:44.069  4034  4034 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-30 14:40:44.069  4034  4034 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-30 14:40:44.069  4034  4034 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-30 14:40:44.069  4034  4034 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-30 1,4:40:44.069  4034  4034 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-30 14:40:44.069  4034  4034 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-30 14:40:44.069  4034  4034 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-30 14:40:44.069  4034  4034 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-30 14:40:44.069  4034  4034 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-30 14:40:44.069  4034  4034 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-30 14:40:44.069  4034  4034 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-30 14:40:44.069  4034  4034 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 14:40:44.069  4034  4034 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-30 14:40:44.069  4034  4034 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-30 14:40:44.069  4034  4034 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 14:40:44.069  4034  4034 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-30 14:40:44.069  4034  4034 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-30 14:40:44.070  4034  4034 D StrictMode: StrictMode policy violation; ~duration=100 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-30 14:40:44.070  4034  4034 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-30 14:40:44.070  4034  4034 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-30 14:40:44.070  4034  4034 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-30 14:40:44.070  4034  4034 D StrictMode: 	at java.io.File.exists(File.java:361)
08-30 14:40:44.070  4034  4034 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
08-30 14:40:44.070  4034  4034 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
08-30 14:40:44.070  4034  4034 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
08-30 14:40:44.070  4034  4034 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
08-30 14:40:44.070  4034  4034 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
08-30 14:40:44.070  4034  4034 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-30 14:40:44.070  4034  4034 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-30 14:40:44.070  4034  4034 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-30 14:40:44.070  4034  4034 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-30 14:40:44.070  4034  4034 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-30 14:40:44.070  4034  4034 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-30 14:40:44.070  4034  4034 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-30 14:40:44.070  4034  4034 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-30 14:40:44.070  4034  4034 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-30 14:40:44.070  4034  4034 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-30 14:40:44.070  4034  4034 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 14:40:44.070  4034  4034 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-30 14:40:44.070  4034  4034 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-30 14:40:44.070  4034  4034 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 14:40:44.070  4034  4034 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-30 14:40:44.070  4034  4034 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-30 14:40:44.070  4034  4034 D StrictMode: StrictMode policy violation; ~duration=98 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-30 14:40:44.070  4034  4034 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-30 14:40:44.070  4034  4034 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-30 14:40:44.070  4034  4034 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-30 14:40:44.070  4034  4034 D StrictMode: 	at java.io.File.exists(File.java:361)
08-30 14:40:44.070  4034  4034 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
08-30 14:40:44.070  4034  4034 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-30 14:40:44.070  4034  4034 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-30 14:40:44.070  4034  4034 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-30 14:40:44.070  4034  4034 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-30 14:40:44.070  4034  4034 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-30 14:40:44.070  4034  4034 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-30 14:40:44.070  4034  4034 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-30 14:40:44.070  4034  4034 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-30 14:40:44.070  4034  4034 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-30 14:40:44.070  4034  4034 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-30 14:40:44.070  4034  4034 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 14:40:44.070  4034  4034 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-30 14:40:44.070  4034  4034 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-30 14:40:44.070  4034  4034 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 14:40:44.070  4034  4034 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-30 14:40:44.070  4034  4034 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-30 14:40:44.070  4034  4034 D StrictMode: StrictMode policy violation; ~duration=98 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-30 14:40:44.070  4034  4034 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-30 14:40:44.070  4034  4034 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
08-30 14:40:44.070  4034  4034 D StrictMode: 	at java.io.File.lastModified(File.java:569)
08-30 14:40:44.070  4034  4034 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
08-30 14:40:44.070  4034  4034 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-30 14:40:44.070  4034  4034 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-30 14:40:44.070  4034  4034 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-30 14:40:44.070  4034  4034 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-30 14:40:44.070  4034  4034 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-30 14:40:44.070  4034  4034 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-30 14:40:44.070  4034  4034 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-30 14:40:44.070  4034  4034 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-30 14:40:44.070  4034  4034 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-30 14:40:44.070  4034  4034 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-30 14:40:44.070  4034  4034 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 14:40:44.070  4034  4034 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-30 14:40:44.070  4034  4034 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-30 14:40:44.070  4034  4034 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 14:40:44.070  4034  4034 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-30 14:40:44.070  4034  4034 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-30 14:40:44.107   875  1378 I ActivityManager: Start proc 4067:com.google.android.apps.gcs/u0a89 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
08-30 14:40:44.109   875  1378 I ActivityManager: Killing 1680:android.process.acore/u0a5 (adj 15): empty #17
08-30 14:40:44.135  3953  3953 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-30 14:40:44.175  4034  4054 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,08-30 14:40:44.191   875   892 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@7e367bb:true
,08-30 14:40:44.199  2678  2699 D bt_stack_manager: event_shut_down_stack finished.
,08-30 14:40:44.200  2678  2698 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,08-30 14:40:44.201  2678  2698 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,08-30 14:40:44.201  2678  2678 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-30 14:40:44.202  2678  2678 D BtGatt.GattService: Received stop request...Stopping profile...
08-30 14:40:44.202  2678  2678 D BtGatt.GattService: stop()
,08-30 14:40:44.202  2678  2678 D BtGatt.AdvertiseManager: advertise clients cleared
08-30 14:40:44.203  2678  2678 V BluetoothAdapterState: isTurningOff()=false
08-30 14:40:44.203  2678  2678 V BluetoothAdapterState: isTurningOn()=false
,08-30 14:40:44.203  2678  2678 V BluetoothAdapterState: isBleTurningOn()=false
08-30 14:40:44.203  2678  2678 V BluetoothAdapterState: isBleTurningOff()=true
,08-30 14:40:44.204  2678  2698 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
08-30 14:40:44.204  2678  2698 D BluetoothAdapterProperties: Setting state to 10
,08-30 14:40:44.204  2678  2698 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
08-30 14:40:44.206  2678  2698 I BluetoothAdapterState: Entering OffState
08-30 14:40:44.206   875   892 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,08-30 14:40:44.221  2678  2678 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,08-30 14:40:44.221  2678  2678 W BluetoothSdpJni: Cleaning up Bluetooth Health object
08-30 14:40:44.221  2678  2699 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
08-30 14:40:44.223  2678  2699 D bt_stack_manager: event_clean_up_stack finished.
,08-30 14:40:44.223  2678  2678 I BluetoothServiceJni: cleanupNative: return from cleanup
,08-30 14:40:44.229  4067  4067 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm
08-30 14:40:44.234  2678  2678 I art     : System.exit called, status: 0
,08-30 14:40:44.234  2678  2678 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-30 14:40:44.299   875  2086 I ActivityManager: Process com.android.bluetooth (pid 2678) has died
,08-30 14:40:44.320  4067  4067 W ClientExperimentManager: [1] d.a: com.google.android.apps.gcs does not have permission com.google.android.apps.gcs.WRITE_EXPERIMENTS; disabling overrides
,08-30 14:40:44.340   875  1952 I ActivityManager: Start proc 4093:com.google.android.keep/u0a79 for broadcast com.google.android.keep/.notification.AlertReceiver
,08-30 14:40:44.372  4093  4093 W System  : ClassLoader referenced unknown path: /system/app/PrebuiltKeep/lib/arm
,08-30 14:40:44.440  4017  4017 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-30 14:40:44.475   875  3108 I ActivityManager: Start proc 4111:com.android.bluetooth/1002 for broadcast com.android.bluetooth/.pbap.BluetoothPbapReceiver
,08-30 14:40:44.476  4017  4017 D DockEventReceiver: finishStartingService: stopping service
,08-30 14:40:44.564   875  1943 I ActivityManager: Killing 3665:com.google.android.partnersetup/u0a16 (adj 15): empty #17
,08-30 14:40:44.604  4111  4111 D AdapterServiceConfig: Adding HeadsetService
08-30 14:40:44.604  4111  4111 D AdapterServiceConfig: Adding A2dpService
08-30 14:40:44.604  4111  4111 D AdapterServiceConfig: Adding HidService
08-30 14:40:44.604  4111  4111 D AdapterServiceConfig: Adding HealthService
08-30 14:40:44.604  4111  4111 D AdapterServiceConfig: Adding PanService
,08-30 14:40:44.605  4111  4111 D AdapterServiceConfig: Adding GattService
08-30 14:40:44.605  4111  4111 D AdapterServiceConfig: Adding BluetoothMapService
,08-30 14:40:44.608   875  1997 I ActivityManager: Killing 3680:com.android.musicfx/u0a18 (adj 15): empty #17
,08-30 14:40:44.642  1540  1540 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-30 14:40:44.661  1744  1744 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-30 14:40:44.668  1744  1744 D SystemUpdateService: onCreate
,08-30 14:40:44.675  1744  1744 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-30 14:40:44.695  1744  4127 I SystemUpdateService: active receiver: enabled
,08-30 14:40:44.703  1744  4127 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-30 14:40:44.708  1744  1744 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
08-30 14:40:44.709  1744  4127 I SystemUpdateService: network: null; metered: false; mobile allowed: true
08-30 14:40:44.709  1744  4127 I SystemUpdateService: now status is 0 (complete)
08-30 14:40:44.709  1744  4127 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
08-30 14:40:44.710  1744  4127 I SystemUpdateService: file has been verified
08-30 14:40:44.710  1744  4127 I SystemUpdateService: OTA package size = 12249756
,08-30 14:40:44.713  1744  2424 I iu.UploadsManager: num queued entries: 0
,08-30 14:40:44.715  1744  2424 I iu.UploadsManager: num updated entries: 0
08-30 14:40:44.716  1744  2424 I iu.SyncManager: NEXT; no task
08-30 14:40:44.716  1744  4127 I SystemUpdateService: showing system update notification
,08-30 14:40:44.728  1744  1744 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
08-30 14:40:44.729  1744  1744 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-30 14:40:44.732  3768  3768 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-30 14:40:44.737  1744  1744 D SystemUpdateService: onDestroy
,08-30 14:40:44.743  3768  3768 D SprintDMHelper: simOperator: 
,08-30 14:40:44.743  3768  3768 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-30 14:40:44.775  3058  4129 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,08-30 14:40:46.712   875  1394 D WifiService: setWifiEnabled: true pid=3953, uid=10000
,08-30 14:40:46.712   875  1394 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-30 14:40:46.725   875  1309 D WifiConfigStore: Loading config and enabling all networks 
,08-30 14:40:46.734  3953  3953 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 14:40:46.734  3953  3953 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 14:40:46.734  3953  3953 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 14:40:46.734  3953  3953 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 14:40:46.734  3953  3953 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 14:40:46.734  3953  3953 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 14:40:46.734  3953  3953 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 14:40:46.734  3953  3953 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 14:40:46.734  3953  3953 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-30 14:40:46.734  3953  3953 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 14:40:46.734  3953  3953 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-30 14:40:46.736  3953  3953 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-30 14:40:46.737  3953  3953 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 14:40:46.737  3953  3953 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 14:40:46.737  3953  3953 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 14:40:46.737  3953  3953 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 14:40:46.737  3953  3953 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 14:40:46.737  3953  3953 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 14:40:46.737  3953  3953 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 14:40:46.737  3953  3953 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-30 14:40:46.737  3953  3953 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-30 14:40:46.737  3953  3953 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-30 14:40:46.774   875  1309 D WifiConfigStore: loaded 0 passpoint configs
,08-30 14:40:46.776   875  1309 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,08-30 14:40:46.776   875  1309 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,08-30 14:40:46.777   875  1309 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,08-30 14:40:46.777   875  1309 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
08-30 14:40:46.777   875  1309 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
08-30 14:40:46.777   875  1309 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,08-30 14:40:46.790   375   873 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
08-30 14:40:46.790   875  1309 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=15.62 rxSuccessRate=18.12 delta 1000 -> 994
,08-30 14:40:46.791   375   873 D CommandListener: Setting iface cfg
,08-30 14:40:46.793   875  1308 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '178 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 178 Failed to set address (No such device)'
08-30 14:40:46.794   875  1308 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,08-30 14:40:46.799   875  1309 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
,08-30 14:40:46.799   875  1309 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-30 14:40:46.807   875  1309 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,08-30 14:40:46.855   875  1308 D WifiNative-HAL: p2pGetDeviceAddress
,08-30 14:40:46.856   875  1308 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,08-30 14:40:46.903   875  1309 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,08-30 14:40:46.905  1466  1466 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,08-30 14:40:47.345  1466  1466 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-30 14:40:47.388  1466  1466 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,08-30 14:40:47.389  1466  1466 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,08-30 14:40:47.392   875  1309 D WifiConfigStore: Retrieve network priorities after PNO.
,08-30 14:40:47.404   875  1309 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{103}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-30 14:40:47.405   875  1309 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-30 14:40:47.405   875  1311 D ConnectivityService: NetworkAgentInfo [WIFI () - 103] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,08-30 14:40:47.438   875  1309 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-30 14:40:47.454   375   873 D CommandListener: Setting iface cfg
,08-30 14:40:47.457   875  1309 D WifiStateMachine: Start Dhcp Watchdog 4
,08-30 14:40:47.472   875  1311 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 103] to 60
,08-30 14:40:47.474   875  1309 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,08-30 14:40:47.483   875  4136 D DhcpClient: Receive thread started
,08-30 14:40:47.567   875  1309 E native  : do suspend false
,08-30 14:40:47.586   875  1883 D DhcpClient: Broadcasting DHCPDISCOVER
,08-30 14:40:47.599   875  4136 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.101, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172768, domain null
,08-30 14:40:47.600   875  1883 D DhcpClient: Got pending lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172768 seconds
,08-30 14:40:47.605   875  1883 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.101 serverid=192.168.1.1
,08-30 14:40:47.619   875  4136 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.101, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,08-30 14:40:47.620   875  1883 D DhcpClient: Confirmed lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,08-30 14:40:47.626   375   873 D CommandListener: Setting iface cfg
,08-30 14:40:47.636   875  1883 D DhcpClient: Scheduling renewal in 86399s
08-30 14:40:47.636   875  1309 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,08-30 14:40:47.650   875  1309 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,08-30 14:40:47.654   875  1311 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 103]
,08-30 14:40:47.655   875  1309 D WifiConfigStore: No blacklist allowed without epno enabled
,08-30 14:40:47.655   875  1311 D ConnectivityService: NetworkAgentInfo [WIFI () - 103] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,08-30 14:40:47.657   875  1309 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,08-30 14:40:47.665   875  1311 D ConnectivityService: Adding iface wlan0 to network 103
,08-30 14:40:47.721   875  1311 E ConnectivityService: Unexpected mtu value: 0, wlan0
,08-30 14:40:47.722   875  1311 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 103
,08-30 14:40:47.723   875  1311 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 103
,08-30 14:40:47.725   875  1311 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 103
,08-30 14:40:47.727   875  1311 D ConnectivityService: Setting Dns servers for network 103 to [/192.168.1.1]
,08-30 14:40:47.742   875  1311 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 103]
,08-30 14:40:47.750   875  1311 D ConnectivityService: scheduleUnvalidatedPrompt 103
,08-30 14:40:47.750   875  1311 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 103]
08-30 14:40:47.750   875  1311 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 103]
,08-30 14:40:47.751   875  1311 D ConnectivityService:    accepting network in place of null
08-30 14:40:47.751   875  1309 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
,08-30 14:40:47.752   875  1309 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-30 14:40:47.752   875  1311 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{103}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.101/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -47]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-30 14:40:47.770   875  4135 D NetlinkSocketObserver: NeighborEvent{elapsedMs=133782, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-30 14:40:47.825   375   873 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-30 14:40:47.837   875  4134 D NetworkMonitor/NetworkAgentInfo [WIFI () - 103]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.214.206,2a00:1450:400d:802::200e
,08-30 14:40:47.864   375   873 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-30 14:40:47.873   875  1311 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 103] isDefaultNetwork=true
,08-30 14:40:47.873   875  1311 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-30 14:40:47.882   875  1311 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 103]
08-30 14:40:47.883   875   892 D Tethering: MasterInitialState.processMessage what=3
08-30 14:40:47.900  3953  3953 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 14:40:47.900  3953  3953 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 14:40:47.900  3953  3953 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 14:40:47.900  3953  3953 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 14:40:47.900  3953  3953 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 14:40:47.900  3953  3953 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 14:40:47.900  3953  3953 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 14:40:47.900  3953  3953 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 14:40:47.900  3953  3953 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-30 14:40:47.900  3953  3953 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 14:40:47.900  3953  3953 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-30 14:40:47.903  3953  3953 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 14:40:47.903  3953  3953 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 14:40:47.903  3953  3953 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 14:40:47.903  3953  3953 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 14:40:47.903  3953  3953 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 14:40:47.903  3953  3953 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 14:40:47.903  3953  3953 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 14:40:47.903  3953  3953 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 14:40:47.903  3953  3953 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-30 14:40:47.903  3953  3953 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 14:40:47.903  3953  3953 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-30 14:40:47.910  1744  1744 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-30 14:40:47.914  1744  1744 D SystemUpdateService: onCreate
,08-30 14:40:47.918   875  4134 D NetworkMonitor/NetworkAgentInfo [WIFI () - 103]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 30 Aug 2016 12:40:47 GMT], X-Android-Received-Millis=[1472560847918], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1472560847895]}
,08-30 14:40:47.919  1744  1744 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
08-30 14:40:47.919   875  1311 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
08-30 14:40:47.920   875  1311 D ConnectivityService: NetworkAgentInfo [WIFI () - 103] validation  passed
,08-30 14:40:47.920   875  1311 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 103]
08-30 14:40:47.922   875  1311 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,08-30 14:40:47.928  1744  4146 I SystemUpdateService: active receiver: enabled
,08-30 14:40:47.931  1744  4146 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-30 14:40:47.937  1744  1744 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,08-30 14:40:47.936  1744  4146 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true,
08-30 14:40:47.939  1744  4146 I SystemUpdateService: now status is 0 (complete)
08-30 14:40:47.939  1744  4146 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
08-30 14:40:47.939  1744  4146 I SystemUpdateService: file has been verified
08-30 14:40:47.940  1744  4146 I SystemUpdateService: OTA package size = 12249756
08-30 14:40:47.940  1744  2424 I iu.UploadsManager: num queued entries: 0
08-30 14:40:47.943  1744  2424 I iu.UploadsManager: num updated entries: 0
,08-30 14:40:47.945  1744  2424 I iu.SyncManager: NEXT; no task
,08-30 14:40:47.948  1744  4146 I SystemUpdateService: showing system update notification
,08-30 14:40:47.951  1744  1744 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-30 14:40:47.952  1744  1744 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-30 14:40:47.955  1744  4149 I MDM     : [185] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
08-30 14:40:47.955  1744  4149 W BaseAppContext: Using Auth Proxy for data requests.
,08-30 14:40:47.955  3768  3768 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-30 14:40:47.956  1744  4149 V GoogleAuthProtoRequest: [185] a.<init>: mAccountName set to: thalitester@gmail.com
,08-30 14:40:47.961  3768  3768 D SprintDMHelper: simOperator: 
08-30 14:40:47.961  3768  3768 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-30 14:40:47.966   875   887 I ActivityManager: Start proc 4151:com.google.android.apps.books/u0a34 for service com.google.android.apps.books/.service.SyncService
,08-30 14:40:47.970  1744  1744 D SystemUpdateService: onDestroy
,08-30 14:40:47.975  1540  1540 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-30 14:40:47.976  1540  1540 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-30 14:40:48.005  4151  4151 W System  : ClassLoader referenced unknown path: /system/app/Books/lib/arm
,08-30 14:40:48.008  1540  2094 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
08-30 14:40:48.008  1540  2094 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
08-30 14:40:48.008  1540  2094 I GLSUser : [GLSUser] Extracting token using key: Auth
08-30 14:40:48.008  1540  2094 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-30 14:40:48.034  1744  4149 E MDM     : [185] SitrepService.a: Error sending sitrep.
,08-30 14:40:48.072  4093  4165 V KeepSync: Connecting to GoogleApiClient
,08-30 14:40:48.072   875  1997 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,08-30 14:40:48.077  4151  4151 W GAV2    : Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,08-30 14:40:48.086  4151  4151 I BooksApp: Created application version: 3.6.9 (30609)
,08-30 14:40:48.122  1540  2094 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,08-30 14:40:48.123  1540  2094 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
08-30 14:40:48.123  1540  2094 I GLSUser : [GLSUser] Extracting token using key: Auth
08-30 14:40:48.123  1540  2094 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-30 14:40:48.136  3058  4162 I Babel   : connection state changed from DISCONNECTED to CONNECTED,
08-30 14:40:48.136  1744  4173 V BaseAuthAsyncOperation: access token request failed
,08-30 14:40:48.138  4093  4165 V KeepSync: GoogleApiClient failed to connect with error code: 4
,08-30 14:40:48.185  4151  4174 I BooksSync: Starting books sync for 61035162, extras: ade
,08-30 14:40:48.254  1540  1559 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,08-30 14:40:48.254  1540  1559 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
,08-30 14:40:48.254  1540  1559 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-30 14:40:48.256  1540  1559 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-30 14:40:48.304  4093  4165 E KeepSync: IOException
08-30 14:40:48.304  4093  4165 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
08-30 14:40:48.304  4093  4165 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
08-30 14:40:48.304  4093  4165 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
08-30 14:40:48.304  4093  4165 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
08-30 14:40:48.304  4093  4165 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
08-30 14:40:48.304  4093  4165 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
08-30 14:40:48.304  4093  4165 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
08-30 14:40:48.304  4093  4165 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
08-30 14:40:48.304  4093  4165 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
08-30 14:40:48.304  4093  4165 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
08-30 14:40:48.304  4093  4165 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
08-30 14:40:48.304  4093  4165 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
08-30 14:40:48.304  4093  4165 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
08-30 14:40:48.304  4093  4165 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
08-30 14:40:48.304  4093  4165 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-30 14:40:48.304  4093  4165 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-30 14:40:48.304  4093  4165 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
08-30 14:40:48.304  4093  4165 E KeepSync: 	... 10 more
,08-30 14:40:48.304  4093  4165 W KeepSync: Sync result 2
,08-30 14:40:48.306  4151  4182 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,08-30 14:40:48.316   875   887 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 129261, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-30 14:40:48.361  1540  2092 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-30 14:40:48.362  1540  2092 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
08-30 14:40:48.362  1540  2092 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-30 14:40:48.362  1540  2092 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-30 14:40:48.395  1540  2092 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-30 14:40:48.396  1540  2092 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
08-30 14:40:48.396  1540  2092 I GLSUser : [GLSUser] Extracting token using key: Auth
08-30 14:40:48.396  1540  2092 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-30 14:40:48.407  4151  4182 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-30 14:40:48.408  4151  4174 E BooksSync: Soft error
08-30 14:40:48.408  4151  4174 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-30 14:40:48.408  4151  4174 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,08-30 14:40:48.408  4151  4174 E BooksSync: Sync error
08-30 14:40:48.408  4151  4174 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-30 14:40:48.408  4151  4174 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
08-30 14:40:48.408  4151  4174 I BooksSync: Finished books sync
,08-30 14:40:48.413   875   887 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 127787, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-30 14:40:48.464  1540  2094 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-30 14:40:48.464  1540  2094 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-30 14:40:48.464  1540  2094 I GLSUser : [GLSUser] Extracting token using key: Auth
08-30 14:40:48.464  1540  2094 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-30 14:40:48.477  3540  4185 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
08-30 14:40:48.477  3540  4185 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-30 14:40:48.477  3540  4185 E HttpOperation: 	at jdm.a(PG:82)
08-30 14:40:48.477  3540  4185 E HttpOperation: 	at jcs.o(PG:406)
08-30 14:40:48.477  3540  4185 E HttpOperation: 	at jcn.a(PG:1379)
08-30 14:40:48.477  3540  4185 E HttpOperation: 	at jcs.i(PG:143)
08-30 14:40:48.477  3540  4185 E HttpOperation: 	at blb.a(PG:3937)
08-30 14:40:48.477  3540  4185 E HttpOperation: 	at czp.a(PG:18188)
08-30 14:40:48.477  3540  4185 E HttpOperation: 	at czp.a(PG:9081)
08-30 14:40:48.477  3540  4185 E HttpOperation: 	at czq.run(PG:1686)
08-30 14:40:48.477  3540  4185 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-30 14:40:48.477  3540  4185 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-30 14:40:48.477  3540  4185 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-30 14:40:48.477  3540  4185 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-30 14:40:48.477  3540  4185 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-30 14:40:48.477  3540  4185 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-30 14:40:48.477  3540  4185 E HttpOperation: 	at jdj.a(PG:4091)
08-30 14:40:48.477  3540  4185 E HttpOperation: 	at jdj.a(PG:1125)
08-30 14:40:48.477  3540  4185 E HttpOperation: 	at jdm.a(PG:77)
08-30 14:40:48.477  3540  4185 E HttpOperation: 	... 12 more
08-30 14:40:48.477  3540  4185 E HttpOperation: Caused by: faj: BadAuthentication
08-30 14:40:48.477  3540  4185 E HttpOperation: 	at fal.a(PG:38)
08-30 14:40:48.477  3540  4185 E HttpOperation: 	at jdj.a(PG:4089)
08-30 14:40:48.477  3540  4185 E HttpOperation: 	... 14 more
,08-30 14:40:48.549  1540  1555 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-30 14:40:48.550  1540  1555 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
,08-30 14:40:48.550  1540  1555 I GLSUser : [GLSUser] Extracting token using key: Auth
08-30 14:40:48.550  1540  1555 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-30 14:40:48.579  3540  4185 E HttpOperation: [getmobileexperiments] Unexpected exception
08-30 14:40:48.579  3540  4185 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-30 14:40:48.579  3540  4185 E HttpOperation: 	at jdm.a(PG:82)
08-30 14:40:48.579  3540  4185 E HttpOperation: 	at jcs.o(PG:406)
08-30 14:40:48.579  3540  4185 E HttpOperation: 	at jcn.a(PG:1379)
08-30 14:40:48.579  3540  4185 E HttpOperation: 	at jcs.i(PG:143)
08-30 14:40:48.579  3540  4185 E HttpOperation: 	at hec.a(PG:42)
08-30 14:40:48.579  3540  4185 E HttpOperation: 	at hee.a(PG:102)
08-30 14:40:48.579  3540  4185 E HttpOperation: 	at czr.a(PG:65)
08-30 14:40:48.579  3540  4185 E HttpOperation: 	at kka.a(PG:108)
08-30 14:40:48.579  3540  4185 E HttpOperation: 	at czp.a(PG:19176)
08-30 14:40:48.579  3540  4185 E HttpOperation: 	at czp.a(PG:9081)
08-30 14:40:48.579  3540  4185 E HttpOperation: 	at czq.run(PG:1686)
08-30 14:40:48.579  3540  4185 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-30 14:40:48.579  3540  4185 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-30 14:40:48.579  3540  4185 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-30 14:40:48.579  3540  4185 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-30 14:40:48.579  3540  4185 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-30 14:40:48.579  3540  4185 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-30 14:40:48.579  3540  4185 E HttpOperation: 	at jdj.a(PG:4091)
08-30 14:40:48.579  3540  4185 E HttpOperation: 	at jdj.a(PG:1125)
08-30 14:40:48.579  3540  4185 E HttpOperation: 	at jdm.a(PG:77)
08-30 14:40:48.579  3540  4185 E HttpOperation: 	... 15 more
08-30 14:40:48.579  3540  4185 E HttpOperation: Caused by: faj: BadAuthentication
08-30 14:40:48.579  3540  4185 E HttpOperation: 	at fal.a(PG:38)
08-30 14:40:48.579  3540  4185 E HttpOperation: 	at jdj.a(PG:4089)
08-30 14:40:48.579  3540  4185 E HttpOperation: 	... 17 more
,08-30 14:40:48.580  3540  4185 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
08-30 14:40:48.580  3540  4185 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
08-30 14:40:48.580  3540  4185 E ExperimentLoader: 	at jdm.a(PG:82)
08-30 14:40:48.580  3540  4185 E ExperimentLoader: 	at jcs.o(PG:406)
08-30 14:40:48.580  3540  4185 E ExperimentLoader: 	at jcn.a(PG:1379)
08-30 14:40:48.580  3540  4185 E ExperimentLoader: 	at jcs.i(PG:143)
08-30 14:40:48.580  3540  4185 E ExperimentLoader: 	at hec.a(PG:42)
08-30 14:40:48.580  3540  4185 E ExperimentLoader: 	at hee.a(PG:102)
08-30 14:40:48.580  3540  4185 E ExperimentLoader: 	at czr.a(PG:65)
08-30 14:40:48.580  3540  4185 E ExperimentLoader: 	at kka.a(PG:108)
08-30 14:40:48.580  3540  4185 E ExperimentLoader: 	at czp.a(PG:19176)
08-30 14:40:48.580  3540  4185 E ExperimentLoader: 	at czp.a(PG:9081)
08-30 14:40:48.580  3540  4185 E ExperimentLoader: 	at czq.run(PG:1686)
08-30 14:40:48.580  3540  4185 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-30 14:40:48.580  3540  4185 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-30 14:40:48.580  3540  4185 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-30 14:40:48.580  3540  4185 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-30 14:40:48.580  3540  4185 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
08-30 14:40:48.580  3540  4185 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-30 14:40:48.580  3540  4185 E ExperimentLoader: 	at jdj.a(PG:4091)
08-30 14:40:48.580  3540  4185 E ExperimentLoader: 	at jdj.a(PG:1125)
08-30 14:40:48.580  3540  4185 E ExperimentLoader: 	at jdm.a(PG:77)
08-30 14:40:48.580  3540  4185 E ExperimentLoader: 	... 15 more
08-30 14:40:48.580  3540  4185 E ExperimentLoader: Caused by: faj: BadAuthentication
08-30 14:40:48.580  3540  4185 E ExperimentLoader: 	at fal.a(PG:38)
08-30 14:40:48.580  3540  4185 E ExperimentLoader: 	at jdj.a(PG:4089)
08-30 14:40:48.580  3540  4185 E ExperimentLoader: 	... 17 more
,08-30 14:40:48.687   875   886 I ActivityManager: Killing 2231:com.google.android.gms.wearable/u0a11 (adj 15): empty #17
,08-30 14:40:48.687   875   887 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 130453, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,08-30 14:40:48.869   875  1311 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 102] cleared because we found a replacement network
,08-30 14:40:49.344   875   885 I ActivityManager: Killing 3703:com.google.android.apps.docs/u0a46 (adj 15): empty #17
,08-30 14:40:49.453  4093  4100 E DataBuffer: Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (com.google.android.gms.reminders.model.RemindersBuffer@bdd8f97)
,08-30 14:40:49.720   875  1394 D WifiService: setWifiEnabled: false pid=3953, uid=10000
,08-30 14:40:49.721   875  1394 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-30 14:40:49.754  1466  1466 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,08-30 14:40:49.759   875  1309 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,08-30 14:40:49.759   875  1309 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
08-30 14:40:49.760   875  1309 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-30 14:40:49.760   875  1309 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-30 14:40:49.776   375   873 D CommandListener: Clearing all IP addresses on wlan0
08-30 14:40:49.776   875  1883 D DhcpClient: Clearing IP address
,08-30 14:40:49.779   375   873 D CommandListener: Setting iface cfg
,08-30 14:40:49.789  1540  4175 V NativeCrypto: Read error: ssl=0xaee55000: I/O error during system call, Connection timed out
,08-30 14:40:49.795   875  4136 D DhcpClient: Receive thread stopped
,08-30 14:40:49.797  1540  4175 V NativeCrypto: SSL shutdown failed: ssl=0xaee55000: I/O error during system call, Broken pipe
,08-30 14:40:49.798   875  1311 D ConnectivityService: NetworkAgentInfo [WIFI () - 103] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
,08-30 14:40:49.799   875  1311 D ConnectivityService: NetworkAgentInfo [WIFI () - 103] got DISCONNECTED, was satisfying 3
08-30 14:40:49.802   875  1309 D WifiStateMachine: Start Disconnecting Watchdog 4
08-30 14:40:49.803   875  1309 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-30 14:40:49.804   398   398 E Parcel  : Reading a NULL string not supported here.
08-30 14:40:49.806   375   873 D CommandListener: Clearing all IP addresses on wlan0
,08-30 14:40:49.822   875  1311 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 103]
,08-30 14:40:49.828  3953  3953 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-30 14:40:49.828  3953  3953 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 14:40:49.828  3953  3953 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 14:40:49.828  3953  3953 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 14:40:49.828  3953  3953 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 14:40:49.828  3953  3953 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 14:40:49.828  3953  3953 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 14:40:49.828  3953  3953 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 14:40:49.828  3953  3953 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 14:40:49.828  3953  3953 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 14:40:49.828  3953  3953 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-30 14:40:49.829   875  1309 D WifiConfigStore: Retrieve network priorities after PNO.
08-30 14:40:49.829  3953  3953 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 14:40:49.830  3953  3953 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 14:40:49.830  3953  3953 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 14:40:49.830  3953  3953 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 14:40:49.830  3953  3953 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 14:40:49.830  3953  3953 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 14:40:49.830  3953  3953 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 14:40:49.830  3953  3953 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 14:40:49.830  3953  3953 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 14:40:49.830  3953  3953 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 14:40:49.830  3953  3953 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-30 14:40:49.836   875  1309 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-30 14:40:49.837  2134  2310 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-30 14:40:49.856   375   873 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-30 14:40:49.878   375   873 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-30 14:40:49.879   875  1311 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 103] isDefaultNetwork=true
,08-30 14:40:49.879   875  1311 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-30 14:40:49.883   875   892 D Tethering: MasterInitialState.processMessage what=3
,08-30 14:40:49.887  3953  3953 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 14:40:49.889  3953  3953 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 14:40:49.894  1744  1744 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-30 14:40:49.897  1744  1744 D SystemUpdateService: onCreate
,08-30 14:40:49.902  1744  1744 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-30 14:40:49.914  1744  4197 I SystemUpdateService: active receiver: enabled
,08-30 14:40:49.916  1744  1744 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,08-30 14:40:49.920  1744  2424 I iu.UploadsManager: num queued entries: 0
,08-30 14:40:49.924  1744  1744 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-30 14:40:49.924  1744  4197 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-30 14:40:49.925  1744  2424 I iu.UploadsManager: num updated entries: 0
,08-30 14:40:49.927  1744  1744 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-30 14:40:49.929  3768  3768 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
08-30 14:40:49.930   375   873 E Netd    : netlink response contains error (No such file or directory)
,08-30 14:40:49.925  1744  2424 I iu.SyncManager: NEXT; no task
,08-30 14:40:49.931   875  1311 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
08-30 14:40:49.931  1744  4197 I SystemUpdateService: network: null; metered: false; mobile allowed: true
08-30 14:40:49.931  1744  4197 I SystemUpdateService: now status is 0 (complete)
08-30 14:40:49.931  1744  4197 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
,08-30 14:40:49.932  1744  4197 I SystemUpdateService: file has been verified
,08-30 14:40:49.933  3768  3768 D SprintDMHelper: simOperator: 
08-30 14:40:49.933  3768  3768 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-30 14:40:49.940  1744  4197 I SystemUpdateService: OTA package size = 12249756
,08-30 14:40:49.946  3058  4200 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,08-30 14:40:49.949  1744  4197 I SystemUpdateService: showing system update notification
,08-30 14:40:49.972  1744  1744 D SystemUpdateService: onDestroy
,08-30 14:40:52.775   875   892 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@6b0fea3:true
,08-30 14:40:52.775  4111  4111 D BluetoothAdapterState: make() - Creating AdapterState
,08-30 14:40:52.780  4111  4111 I bt_bluedroid: init
,08-30 14:40:52.781  4111  4203 I BluetoothAdapterState: Entering OffState
,08-30 14:40:52.783  4111  4204 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,08-30 14:40:52.784  4111  4204 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-30 14:40:52.784  4111  4204 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,08-30 14:40:52.784  4111  4204 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,08-30 14:40:52.785  4111  4111 I bt_bluedroid: get_profile_interface socket
,08-30 14:40:52.787  4111  4111 I bt_bluedroid: get_profile_interface sdp
,08-30 14:40:52.791  4111  4207 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-30 14:40:52.792  4111  4124 I bt_bluedroid: config_hci_snoop_log
,08-30 14:40:52.793  4111  4207 D BluetoothAdapterProperties: Name is: Nexus 6
,08-30 14:40:52.796   875   892 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,08-30 14:40:52.804  4111  4203 D BluetoothAdapterState: Current state: OFF, message: 0
,08-30 14:40:52.804  4111  4203 D BluetoothAdapterProperties: Setting state to 14
08-30 14:40:52.805  4111  4203 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,08-30 14:40:52.809  4111  4203 D BluetoothBondStateMachine: make
,08-30 14:40:52.815  4111  4208 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-30 14:40:52.823  4111  4111 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,08-30 14:40:52.824  4111  4203 I BluetoothAdapterState: Entering PendingCommandState
08-30 14:40:52.825  4111  4111 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@335a16b
08-30 14:40:52.826  4111  4111 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-30 14:40:52.826  4111  4111 D BtGatt.GattService: Received start request. Starting profile...
08-30 14:40:52.826  4111  4111 D BtGatt.GattService: start()
08-30 14:40:52.826  4111  4111 I bt_bluedroid: get_profile_interface gatt
,08-30 14:40:52.827  4111  4111 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@335a16b
,08-30 14:40:52.827  4111  4111 D BtGatt.AdvertiseManager: advertise manager created
,08-30 14:40:52.836  4111  4111 V BluetoothAdapterState: isTurningOff()=false
,08-30 14:40:52.837  4111  4111 V BluetoothAdapterState: isTurningOn()=false
08-30 14:40:52.837  4111  4111 V BluetoothAdapterState: isBleTurningOn()=true
,08-30 14:40:52.837  4111  4111 V BluetoothAdapterState: isBleTurningOff()=false
,08-30 14:40:52.837  4111  4203 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
08-30 14:40:52.838  4111  4203 I bt_bluedroid: enable
,08-30 14:40:52.838  4111  4204 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,08-30 14:40:52.839  4111  4204 I bt_hci  : start_up
,08-30 14:40:52.849  4111  4204 I bt_vendor: alloc value 0xb39f9189
,08-30 14:40:52.849  4111  4204 I bt_vendor: init
08-30 14:40:52.849  4111  4204 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
08-30 14:40:52.849  4111  4204 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,08-30 14:40:52.955  4111  4204 D bt_hci  : start_up starting async portion
,08-30 14:40:52.956  4111  4211 I bt_hci  : event_finish_startup
,08-30 14:40:52.957  4111  4211 I bt_hci_h4: hal_open
,08-30 14:40:52.958  4111  4211 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,08-30 14:40:52.967  4111  4211 I bt_userial_vendor: device fd = 51 open
,08-30 14:40:52.998  4111  4211 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-30 14:40:53.030  4111  4211 D bt_hwcfg: Chipset BCM4354A2
,08-30 14:40:53.031  4111  4211 D bt_hwcfg: Target name = [BCM4354A2]
08-30 14:40:53.031  4111  4211 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,08-30 14:40:53.079  4151  4171 I GAV2    : Thread[GAThread,5,main]: No campaign data found.
,08-30 14:40:53.680  4111  4211 I bt_hwcfg: bt vendor lib: set UART baud 115200
08-30 14:40:53.682  4111  4211 D bt_hwcfg: Settlement delay -- 100 ms
,08-30 14:40:53.682  4111  4211 I bt_hwcfg: Setting fw settlement delay to 100 
,08-30 14:40:53.799  4111  4211 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-30 14:40:53.800  4111  4211 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,08-30 14:40:53.829  4111  4211 I bt_hwcfg: vendor lib fwcfg completed
,08-30 14:40:53.830  4111  4211 I bt_vendor: firmware callback
08-30 14:40:53.830  4111  4211 I bt_hci  : firmware_config_callback
,08-30 14:40:53.842  4111  4215 I bt_btu  : btu_task pending for preload complete event
,08-30 14:40:53.842  4111  4215 I bt_btu_task: Bluetooth chip preload is complete
08-30 14:40:53.842  4111  4215 I bt_btu  : btu_task received preload complete event
,08-30 14:40:53.855  4111  4215 I         : BTE_InitTraceLevels -- TRC_HCI
,08-30 14:40:53.855  4111  4215 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-30 14:40:53.855  4111  4215 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-30 14:40:53.856  4111  4215 I         : BTE_InitTraceLevels -- TRC_AVDT
,08-30 14:40:53.856  4111  4215 I         : BTE_InitTraceLevels -- TRC_AVRC
08-30 14:40:53.856  4111  4215 I         : BTE_InitTraceLevels -- TRC_A2D
,08-30 14:40:53.857  4111  4215 I         : BTE_InitTraceLevels -- TRC_BNEP
08-30 14:40:53.858  4111  4215 I         : BTE_InitTraceLevels -- TRC_BTM
08-30 14:40:53.858  4111  4215 I         : BTE_InitTraceLevels -- TRC_GAP
,08-30 14:40:53.860  4111  4215 I         : BTE_InitTraceLevels -- TRC_PAN
08-30 14:40:53.860  4111  4215 I         : BTE_InitTraceLevels -- TRC_SDP
,08-30 14:40:53.861  4111  4215 I         : BTE_InitTraceLevels -- TRC_GATT
08-30 14:40:53.861  4111  4215 I         : BTE_InitTraceLevels -- TRC_SMP
08-30 14:40:53.863  4111  4215 I         : BTE_InitTraceLevels -- TRC_BTAPP
,08-30 14:40:53.863  4111  4215 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-30 14:40:53.995  4111  4215 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb3976d9d
,08-30 14:40:53.996  4111  4215 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb3976d9d 
,08-30 14:40:54.019  4111  4207 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,08-30 14:40:54.020  4111  4207 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,08-30 14:40:54.021  4111  4207 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-30 14:40:54.023  4111  4207 D BluetoothAdapterProperties: Name is: Nexus 6
,08-30 14:40:54.028  4111  4207 D BluetoothAdapterProperties: Scan Mode:20
08-30 14:40:54.028  4111  4207 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-30 14:40:54.028  4111  4207 D bt_hci  : do_postload posting postload work item
,08-30 14:40:54.029  4111  4211 I bt_hci  : event_postload
,08-30 14:40:54.029  4111  4211 I bt_vendor: sco_config_cb
08-30 14:40:54.029  4111  4211 I bt_hci  : sco_config_callback postload finished.
08-30 14:40:54.030  3953  3953 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 14:40:54.033  3953  3953 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 14:40:54.035  4111  4211 I bt_vendor: low_power_mode_cb
,08-30 14:40:54.035  4111  4207 D bt_bte_conf: Device ID record 1 : primary
,08-30 14:40:54.036  4111  4207 D bt_bte_conf:   vendorId            = 000f
,08-30 14:40:54.037  4111  4207 D bt_bte_conf:   vendorIdSource      = 0001
,08-30 14:40:54.037  4111  4207 D bt_bte_conf:   product             = 1200
,08-30 14:40:54.039  4111  4207 D bt_bte_conf:   version             = 1436
,08-30 14:40:54.040  4111  4207 D bt_bte_conf:   clientExecutableURL = 
,08-30 14:40:54.041  4111  4207 D bt_bte_conf:   serviceDescription  = 
,08-30 14:40:54.042  4111  4207 D bt_bte_conf:   documentationURL    = 
08-30 14:40:54.043  4111  4207 D bt_bte_conf: bte_load_did_conf no section named DID2.
,08-30 14:40:54.044  4111  4204 D bt_stack_manager: event_start_up_stack finished
,08-30 14:40:54.047  4111  4203 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
,08-30 14:40:54.047  4111  4203 D BluetoothAdapterProperties: Setting state to 15
,08-30 14:40:54.048  4111  4203 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
,08-30 14:40:54.052  4111  4203 I BluetoothAdapterState: Entering BleOnState
,08-30 14:40:54.054  4111  4203 D BluetoothAdapterState: Current state: BLE ON, message: 1
,08-30 14:40:54.055  4111  4203 D BluetoothAdapterProperties: Setting state to 11
,08-30 14:40:54.056  4111  4203 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,08-30 14:40:54.064  4111  4111 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@335a16b
,08-30 14:40:54.065  4111  4111 D HeadsetService: Received start request. Starting profile...
08-30 14:40:54.067  3953  3953 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 14:40:54.069  3953  3953 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 14:40:54.077  4111  4203 I BluetoothAdapterState: Entering PendingCommandState
,08-30 14:40:54.078  4111  4111 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,08-30 14:40:54.079  4111  4111 D HeadsetStateMachine: make
,08-30 14:40:54.094  4111  4111 D HeadsetStateMachine: max_hf_connections = 1
,08-30 14:40:54.095  4111  4111 I bt_bluedroid: get_profile_interface handsfree
,08-30 14:40:54.095  4111  4207 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
08-30 14:40:54.095  4111  4207 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
,08-30 14:40:54.102  4111  4111 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@335a16b
,08-30 14:40:54.103  4111  4111 D A2dpService: Received start request. Starting profile...
,08-30 14:40:54.103  4111  4111 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-30 14:40:54.104  4111  4111 I bt_bluedroid: get_profile_interface avrcp
,08-30 14:40:54.110  4111  4111 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-30 14:40:54.111  4111  4111 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-30 14:40:54.111  4111  4111 D A2dpStateMachine: make
,08-30 14:40:54.113  4111  4111 I bt_bluedroid: get_profile_interface a2dp
,08-30 14:40:54.113  4111  4207 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,08-30 14:40:54.117  4111  4224 D A2dpStateMachine: Enter Disconnected: -2
,08-30 14:40:54.119  4111  4111 I BluetoothHidServiceJni: classInitNative: succeeds
,08-30 14:40:54.120  1540  1540 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-30 14:40:54.122  4111  4111 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@335a16b
,08-30 14:40:54.123  4111  4111 D HidService: Received start request. Starting profile...
,08-30 14:40:54.124  4017  4017 D BluetoothInputDevice: Proxy object connected
08-30 14:40:54.124  4111  4111 I bt_bluedroid: get_profile_interface hidhost
08-30 14:40:54.124  4111  4207 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb39583e5
08-30 14:40:54.124  4111  4207 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
,08-30 14:40:54.124  4111  4111 D HidService: setHidService(): set to: null
08-30 14:40:54.125  4017  4017 D HidProfile: Bluetooth service connected
08-30 14:40:54.125  4111  4111 I BluetoothHealthServiceJni: classInitNative: succeeds
,08-30 14:40:54.126  4111  4111 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@335a16b
08-30 14:40:54.126  4111  4111 D HealthService: Received start request. Starting profile...
,08-30 14:40:54.128  4111  4111 I bt_bluedroid: get_profile_interface health
,08-30 14:40:54.129  4111  4111 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,08-30 14:40:54.129  4111  4111 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@335a16b
,08-30 14:40:54.131  4111  4111 D PanService: Received start request. Starting profile...
,08-30 14:40:54.131  4017  4017 D BluetoothPan: BluetoothPAN Proxy object connected
08-30 14:40:54.131  4111  4111 D BluetoothPanServiceJni: initializeNative(L110): pan
,08-30 14:40:54.131  4111  4111 I bt_bluedroid: get_profile_interface pan
,08-30 14:40:54.131  4111  4207 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,08-30 14:40:54.132  4017  4017 D PanProfile: Bluetooth service connected
,08-30 14:40:54.134  4111  4111 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@335a16b
,08-30 14:40:54.136  4111  4111 D BluetoothMapService: Received start request. Starting profile...
,08-30 14:40:54.136  4111  4111 D BluetoothMapService: start()
08-30 14:40:54.136  4017  4017 D BluetoothMap: Proxy object connected
08-30 14:40:54.137  4017  4017 D MapProfile: Bluetooth service connected
,08-30 14:40:54.138  4017  4017 D BluetoothMap: getConnectedDevices()
08-30 14:40:54.138  4111  4111 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,08-30 14:40:54.139  4111  4111 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
08-30 14:40:54.139  4017  4017 D BluetoothMap: Bluetooth is Not enabled
08-30 14:40:54.139  4111  4111 D BluetoothMapAppObserver: createReceiver()
,08-30 14:40:54.140  4111  4111 D BluetoothMapAppObserver: initObservers()
08-30 14:40:54.140  4111  4111 D BluetoothMapAppObserver: getEnabledAccountItems()
,08-30 14:40:54.149  4111  4111 V BluetoothAdapterState: isTurningOff()=false
,08-30 14:40:54.149  4111  4111 V BluetoothAdapterState: isTurningOn()=true
08-30 14:40:54.149  4111  4111 V BluetoothAdapterState: isBleTurningOn()=false
08-30 14:40:54.149  4111  4111 V BluetoothAdapterState: isBleTurningOff()=false
,08-30 14:40:54.151  4111  4222 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,08-30 14:40:54.151  4111  4111 V BluetoothAdapterState: isTurningOff()=false
08-30 14:40:54.152  4111  4111 V BluetoothAdapterState: isTurningOn()=true
08-30 14:40:54.152  4111  4111 V BluetoothAdapterState: isBleTurningOn()=false
08-30 14:40:54.152  4111  4111 V BluetoothAdapterState: isBleTurningOff()=false
,08-30 14:40:54.152  4111  4111 V BluetoothAdapterState: isTurningOff()=false
,08-30 14:40:54.152  4111  4111 V BluetoothAdapterState: isTurningOn()=true
08-30 14:40:54.152  4111  4111 V BluetoothAdapterState: isBleTurningOn()=false
08-30 14:40:54.152  4111  4111 V BluetoothAdapterState: isBleTurningOff()=false
08-30 14:40:54.152  4111  4111 V BluetoothAdapterState: isTurningOff()=false
08-30 14:40:54.153  4111  4111 V BluetoothAdapterState: isTurningOn()=true
08-30 14:40:54.153  4111  4111 V BluetoothAdapterState: isBleTurningOn()=false
,08-30 14:40:54.153  4111  4111 V BluetoothAdapterState: isBleTurningOff()=false
,08-30 14:40:54.153  4111  4111 V BluetoothAdapterState: isTurningOff()=false
08-30 14:40:54.153  4111  4111 V BluetoothAdapterState: isTurningOn()=true
08-30 14:40:54.153  4111  4111 V BluetoothAdapterState: isBleTurningOn()=false
08-30 14:40:54.153  4111  4111 V BluetoothAdapterState: isBleTurningOff()=false
08-30 14:40:54.153  4111  4111 V BluetoothAdapterState: isTurningOff()=false
08-30 14:40:54.153  4111  4111 V BluetoothAdapterState: isTurningOn()=true
08-30 14:40:54.153  4111  4111 V BluetoothAdapterState: isBleTurningOn()=false
,08-30 14:40:54.154  4111  4111 V BluetoothAdapterState: isBleTurningOff()=false
08-30 14:40:54.154  4111  4203 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
08-30 14:40:54.154  4111  4203 D BluetoothAdapterProperties: ScanMode =  20
08-30 14:40:54.154  4111  4203 D BluetoothAdapterProperties: State =  11
08-30 14:40:54.155  4111  4203 D BluetoothAdapterProperties: Setting state to 12
08-30 14:40:54.155  4111  4203 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-30 14:40:54.156  4111  4207 D BluetoothAdapterProperties: Scan Mode:21
08-30 14:40:54.156  4111  4207 D BluetoothAdapterProperties: Discoverable Timeout:120
08-30 14:40:54.156  4017  4029 D BluetoothMap: onBluetoothStateChange: up=true
08-30 14:40:54.157  4111  4203 I BluetoothAdapterState: Entering OnState
08-30 14:40:54.157  4017  4028 D BluetoothPan: onBluetoothStateChange on: true
08-30 14:40:54.158  1354  1367 D BluetoothPan: onBluetoothStateChange on: true
08-30 14:40:54.160  3953  3953 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 14:40:54.160  3953  3953 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 14:40:54.160  3953  3953 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 14:40:54.160  3953  3953 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 14:40:54.160  3953  3953 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 14:40:54.160  3953  3953 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 14:40:54.160  3953  3953 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 14:40:54.160  3953  3953 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 14:40:54.161  1354  1354 D BluetoothPan: BluetoothPAN Proxy object connected
08-30 14:40:54.161  1354  1354 D PanProfile: Bluetooth service connected
08-30 14:40:54.161  1354  1365 D BluetoothPbap: onBluetoothStateChange: up=true
08-30 14:40:54.163  3953  3953 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-30 14:40:54.167  3953  3953 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 14:40:54.167  3953  3953 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 14:40:54.167  3953  3953 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 14:40:54.167  3953  3953 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 14:40:54.167  3953  3953 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 14:40:54.167  3953  3953 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 14:40:54.167  3953  3953 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 14:40:54.167  3953  3953 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 14:40:54.169  3953  3953 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-30 14:40:54.169  4111  4111 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
08-30 14:40:54.170  1354  2040 D BluetoothA2dp: onBluetoothStateChange: up=true
08-30 14:40:54.170  4111  4111 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
08-30 14:40:54.172  4111  4111 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-30 14:40:54.173  1928  2126 D BluetoothHeadset: onBluetoothStateChange: up=true
08-30 14:40:54.174   875   892 D BluetoothA2dp: onBluetoothStateChange: up=true
08-30 14:40:54.174  1354  1367 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-30 14:40:54.175  4111  4111 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-30 14:40:54.176  4111  4111 D ObexServerSockets: Succeed to create listening sockets 
08-30 14:40:54.176  4111  4111 D ObexServerSockets0: startAccept()
,08-30 14:40:54.176  4111  4111 D ObexServerSockets0: prepareForNewConnect()
08-30 14:40:54.176   875   892 D BluetoothHeadset: onBluetoothStateChange: up=true
08-30 14:40:54.176   875   892 D BluetoothHeadset: onBluetoothStateChange: up=true
08-30 14:40:54.176  1354  1354 D BluetoothInputDevice: Proxy object connected
08-30 14:40:54.176  1354  1354 D HidProfile: Bluetooth service connected
,08-30 14:40:54.176  1354  2040 D BluetoothMap: onBluetoothStateChange: up=true
08-30 14:40:54.178  1354  1354 D BluetoothMap: Proxy object connected
,08-30 14:40:54.178  1354  1354 D MapProfile: Bluetooth service connected
,08-30 14:40:54.178  1354  1354 D BluetoothMap: getConnectedDevices()
,08-30 14:40:54.178  4017  4029 D BluetoothInputDevice: onBluetoothStateChange: up=true
,08-30 14:40:54.178   875   892 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-30 14:40:54.179  4017  4028 D BluetoothPbap: onBluetoothStateChange: up=true
,08-30 14:40:54.180  4111  4111 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
,08-30 14:40:54.180  4111  4111 D BluetoothSdpJni: SDP Create record success - handle: 0
08-30 14:40:54.180  1354  1365 D BluetoothHeadset: onBluetoothStateChange: up=true
08-30 14:40:54.181  1354  1354 D BluetoothA2dp: Proxy object connected
08-30 14:40:54.181   875   875 D BluetoothA2dp: Proxy object connected
08-30 14:40:54.182  4111  4229 D ObexServerSockets0: Accepting socket connection...
,08-30 14:40:54.183  4111  4230 D ObexServerSockets0: Accepting socket connection...
08-30 14:40:54.184  4111  4111 D BluetoothMapService: onReceive
08-30 14:40:54.184  4111  4111 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-30 14:40:54.184  4111  4111 D BluetoothMapService: STATE_ON
,08-30 14:40:54.184  3953  3953 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 14:40:54.186  3953  3953 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 14:40:54.188   875   875 I Telecom : BluetoothPhoneService: queryPhoneState
08-30 14:40:54.190  4017  4017 D LocalBluetoothProfileManager: Adding local A2DP profile
,08-30 14:40:54.193  4017  4017 D LocalBluetoothProfileManager: Adding local HEADSET profile
,08-30 14:40:54.199  4017  4017 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-30 14:40:54.201  4017  4017 D BluetoothA2dp: Proxy object connected
,08-30 14:40:54.206  1540  1540 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-30 14:40:54.212  4017  4017 D DockEventReceiver: finishStartingService: stopping service
,08-30 14:40:54.215  4017  4017 D BluetoothPbap: Proxy object connected
,08-30 14:40:54.215  4017  4017 D PbapServerProfile: Bluetooth service connected
08-30 14:40:54.216  1354  1354 D BluetoothPbap: Proxy object connected
,08-30 14:40:54.216  1354  1354 D PbapServerProfile: Bluetooth service connected
,08-30 14:40:54.218  4111  4111 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
08-30 14:40:54.218  4111  4111 D ObexServerSockets0: prepareForNewConnect()
,08-30 14:40:54.228  4111  4235 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-30 14:40:54.252  4111  4239 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-30 14:40:54.253  4111  4239 I BtOppRfcommListener: Accept thread started.
,08-30 14:40:54.276   875   875 D BluetoothHeadset: Proxy object connected
,08-30 14:40:54.276   875   875 D BluetoothHeadset: Proxy object connected
08-30 14:40:54.277  1928  2198 D BluetoothHeadset: Proxy object connected
08-30 14:40:54.277   875   875 D BluetoothHeadset: Proxy object connected
,08-30 14:40:54.277   875   892 D BluetoothHeadset: Proxy object connected
08-30 14:40:54.278   875   892 D BluetoothHeadset: Proxy object connected
08-30 14:40:54.278  1354  2040 D BluetoothHeadset: Proxy object connected
08-30 14:40:54.278  1354  1354 D HeadsetProfile: Bluetooth service connected
,08-30 14:40:54.279   875   892 D BluetoothHeadset: Proxy object connected
08-30 14:40:54.281  1354  1367 D BluetoothHeadset: Proxy object connected
08-30 14:40:54.282  1354  1354 D HeadsetProfile: Bluetooth service connected
,08-30 14:40:54.296  4017  4029 D BluetoothHeadset: Proxy object connected
,08-30 14:40:54.299  4017  4017 D HeadsetProfile: Bluetooth service connected
,08-30 14:40:55.741  4111  4203 D BluetoothAdapterState: Current state: ON, message: 23
,08-30 14:40:55.742  4111  4203 D BluetoothAdapterProperties: Setting state to 13
08-30 14:40:55.742  4111  4203 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,08-30 14:40:55.744  4111  4203 D BluetoothAdapterProperties: onBluetoothDisable()
,08-30 14:40:55.751  4111  4203 I BluetoothAdapterState: Entering PendingCommandState
,08-30 14:40:55.755   875  1311 D ConnectivityService: handlePromptUnvalidated 103
,08-30 14:40:55.760  4111  4111 D BluetoothMapService: onReceive
,08-30 14:40:55.761  4111  4111 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,08-30 14:40:55.763  4111  4111 D BluetoothMapService: STATE_TURNING_OFF
08-30 14:40:55.763  3953  3953 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 14:40:55.763  3953  3953 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 14:40:55.763  3953  3953 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 14:40:55.763  3953  3953 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 14:40:55.763  3953  3953 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 14:40:55.763  3953  3953 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 14:40:55.763  3953  3953 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 14:40:55.763  3953  3953 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 14:40:55.763  3953  3953 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-30 14:40:55.765  4111  4111 D BluetoothMapService: MAP Service closeService in
08-30 14:40:55.766  4111  4111 D BluetoothMapMasInstance0: MAP Service shutdown
08-30 14:40:55.766  3953  3953 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-30 14:40:55.766  4111  4207 D BluetoothAdapterProperties: Scan Mode:20
,08-30 14:40:55.766  4111  4111 D ObexServerSockets0: shutdown(block = true)
08-30 14:40:55.766  3953  3953 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-30 14:40:55.767  4111  4203 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
08-30 14:40:55.767  4111  4229 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
,08-30 14:40:55.769  4111  4111 D ObexServerSockets0: shutdown called from another thread - interrupt().
,08-30 14:40:55.769  4111  4217 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
08-30 14:40:55.769  4111  4111 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-30 14:40:55.769  4111  4230 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
08-30 14:40:55.770  4111  4111 I BtOppRfcommListener: stopping Accept Thread
,08-30 14:40:55.770  4111  4239 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-30 14:40:55.771  3953  3953 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 14:40:55.771  3953  3953 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 14:40:55.771  3953  3953 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 14:40:55.771  3953  3953 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 14:40:55.771  3953  3953 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 14:40:55.771  3953  3953 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 14:40:55.771  3953  3953 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 14:40:55.771  3953  3953 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 14:40:55.771  3953  3953 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 14:40:55.771  4111  4239 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-30 14:40:55.772  3953  3953 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-30 14:40:55.772  3953  3953 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-30 14:40:55.773  4111  4111 D HeadsetService: Received stop request...Stopping profile...
08-30 14:40:55.774  3953  3953 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 14:40:55.774   875   875 D BluetoothHeadset: Proxy object disconnected
08-30 14:40:55.774   875   875 D BluetoothHeadset: Proxy object disconnected
,08-30 14:40:55.776  4111  4111 D A2dpService: Received stop request...Stopping profile...
08-30 14:40:55.776  3953  3953 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 14:40:55.776  1928  1942 D BluetoothHeadset: Proxy object disconnected
08-30 14:40:55.777  4017  4028 D BluetoothHeadset: Proxy object disconnected
08-30 14:40:55.777   875   875 D BluetoothHeadset: Proxy object disconnected
,08-30 14:40:55.777  1354  1365 D BluetoothHeadset: Proxy object disconnected
08-30 14:40:55.778  1354  1354 D HeadsetProfile: Bluetooth service disconnected
08-30 14:40:55.778  4111  4224 D A2dpStateMachine: Exit Disconnected: -1
,08-30 14:40:55.779   875   875 D BluetoothA2dp: Proxy object disconnected
08-30 14:40:55.779  1354  1354 D BluetoothA2dp: Proxy object disconnected
08-30 14:40:55.780  4111  4111 D HidService: Received stop request...Stopping profile...
08-30 14:40:55.780  4111  4111 D HidService: Stopping Bluetooth HidService
08-30 14:40:55.781  1354  1354 D BluetoothInputDevice: Proxy object disconnected
,08-30 14:40:55.781  1354  1354 D HidProfile: Bluetooth service disconnected
,08-30 14:40:55.782  4111  4111 D HealthService: Received stop request...Stopping profile...
08-30 14:40:55.784  4111  4111 D PanService: Received stop request...Stopping profile...
08-30 14:40:55.784  1354  1354 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-30 14:40:55.784  1354  1354 D PanProfile: Bluetooth service disconnected
08-30 14:40:55.785  4111  4111 V BluetoothAdapterState: isTurningOff()=true
,08-30 14:40:55.785  4111  4111 V BluetoothAdapterState: isTurningOn()=false
08-30 14:40:55.785  4111  4111 V BluetoothAdapterState: isBleTurningOn()=false
08-30 14:40:55.785  4111  4111 V BluetoothAdapterState: isBleTurningOff()=false
08-30 14:40:55.786  4111  4111 D BluetoothMapService: Received stop request...Stopping profile...
08-30 14:40:55.786  4111  4111 D BluetoothMapService: stop()
08-30 14:40:55.786  4017  4017 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-30 14:40:55.786  4111  4111 D BluetoothMapAppObserver: deinitObservers()
08-30 14:40:55.786  4111  4111 D BluetoothMapAppObserver: removeReceiver()
08-30 14:40:55.787  1354  1354 D BluetoothMap: Proxy object disconnected
08-30 14:40:55.787  1354  1354 D MapProfile: Bluetooth service disconnected
,08-30 14:40:55.792  4017  4017 D HeadsetProfile: Bluetooth service disconnected
,08-30 14:40:55.793  4017  4017 D BluetoothA2dp: Proxy object disconnected
,08-30 14:40:55.793  4017  4017 D BluetoothInputDevice: Proxy object disconnected
,08-30 14:40:55.793  4017  4017 D HidProfile: Bluetooth service disconnected,
08-30 14:40:55.793  4111  4111 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
,08-30 14:40:55.794  4017  4017 D BluetoothPan: BluetoothPAN Proxy object disconnected
,08-30 14:40:55.794  4111  4111 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-30 14:40:55.794  4017  4017 D PanProfile: Bluetooth service disconnected
,08-30 14:40:55.794  4111  4207 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
,08-30 14:40:55.794  4111  4215 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-30 14:40:55.794  4111  4215 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-30 14:40:55.794  4017  4017 D BluetoothMap: Proxy object disconnected
,08-30 14:40:55.794  4111  4215 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-30 14:40:55.794  4017  4017 D MapProfile: Bluetooth service disconnected
08-30 14:40:55.794  4111  4111 V BluetoothAdapterState: isTurningOff()=true
08-30 14:40:55.794  4111  4111 V BluetoothAdapterState: isTurningOn()=false
08-30 14:40:55.794  4111  4111 V BluetoothAdapterState: isBleTurningOn()=false
,08-30 14:40:55.794  4111  4111 V BluetoothAdapterState: isBleTurningOff()=false
08-30 14:40:55.795  4111  4207 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
08-30 14:40:55.796  4111  4215 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-30 14:40:55.796  4111  4215 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-30 14:40:55.796  4111  4215 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-30 14:40:55.796  4111  4111 V BluetoothAdapterState: isTurningOff()=true
08-30 14:40:55.796  4111  4215 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-30 14:40:55.796  4111  4111 V BluetoothAdapterState: isTurningOn()=false
08-30 14:40:55.796  4111  4215 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-30 14:40:55.796  4111  4111 V BluetoothAdapterState: isBleTurningOn()=false
08-30 14:40:55.796  4111  4215 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,08-30 14:40:55.796  4111  4111 V BluetoothAdapterState: isBleTurningOff()=false
08-30 14:40:55.796  4111  4207 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
,08-30 14:40:55.796  4111  4111 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
,08-30 14:40:55.797  4111  4111 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-30 14:40:55.797  4111  4207 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,08-30 14:40:55.797  4111  4111 V BluetoothAdapterState: isTurningOff()=true
08-30 14:40:55.797  4111  4111 V BluetoothAdapterState: isTurningOn()=false
08-30 14:40:55.797  4111  4111 V BluetoothAdapterState: isBleTurningOn()=false
08-30 14:40:55.797  4111  4111 V BluetoothAdapterState: isBleTurningOff()=false
08-30 14:40:55.797  4111  4111 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-30 14:40:55.797  4111  4207 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
,08-30 14:40:55.798  4111  4111 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
,08-30 14:40:55.798  4111  4111 V BluetoothAdapterState: isTurningOff()=true
,08-30 14:40:55.798  4111  4111 V BluetoothAdapterState: isTurningOn()=false
08-30 14:40:55.798  4111  4111 V BluetoothAdapterState: isBleTurningOn()=false
08-30 14:40:55.798  4111  4111 V BluetoothAdapterState: isBleTurningOff()=false
08-30 14:40:55.799  4111  4111 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-30 14:40:55.799  4111  4111 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-30 14:40:55.800  4111  4111 D BluetoothMapService: MAP Service closeService in
,08-30 14:40:55.800  4111  4111 V BluetoothAdapterState: isTurningOff()=true
08-30 14:40:55.800  4111  4111 V BluetoothAdapterState: isTurningOn()=false
08-30 14:40:55.800  4111  4111 V BluetoothAdapterState: isBleTurningOn()=false
08-30 14:40:55.800  4111  4111 V BluetoothAdapterState: isBleTurningOff()=false
08-30 14:40:55.800  4111  4203 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
08-30 14:40:55.800  4111  4203 D BluetoothAdapterProperties: Setting state to 15
08-30 14:40:55.800  4111  4203 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
,08-30 14:40:55.800  4111  4111 D BluetoothMapService: cleanup()
08-30 14:40:55.801  4111  4111 D BluetoothMapService: MAP Service closeService in
08-30 14:40:55.801  4111  4203 I BluetoothAdapterState: Entering BleOnState
08-30 14:40:55.801  4017  4028 D BluetoothMap: onBluetoothStateChange: up=false
08-30 14:40:55.803  1540  1540 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-30 14:40:55.806  1354  1354 D BluetoothPbap: Proxy object disconnected
,08-30 14:40:55.806  1354  1354 D PbapServerProfile: Bluetooth service disconnected
08-30 14:40:55.809  4017  4029 D BluetoothPan: onBluetoothStateChange on: false
08-30 14:40:55.809  1354  2040 D BluetoothPan: onBluetoothStateChange on: false
08-30 14:40:55.810  1354  1365 D BluetoothPbap: onBluetoothStateChange: up=false
08-30 14:40:55.810  1354  1367 D BluetoothA2dp: onBluetoothStateChange: up=false
08-30 14:40:55.811  4017  4028 D BluetoothA2dp: onBluetoothStateChange: up=false
08-30 14:40:55.812  1928  1945 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-30 14:40:55.812   875   892 D BluetoothA2dp: onBluetoothStateChange: up=false
08-30 14:40:55.813  1354  2040 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-30 14:40:55.814   875   892 D BluetoothHeadset: onBluetoothStateChange: up=false
08-30 14:40:55.814   875   892 D BluetoothHeadset: onBluetoothStateChange: up=false
08-30 14:40:55.814  1354  1365 D BluetoothMap: onBluetoothStateChange: up=false
08-30 14:40:55.815  4017  4029 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-30 14:40:55.815  4017  4243 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-30 14:40:55.815   875   892 D BluetoothHeadset: onBluetoothStateChange: up=false
08-30 14:40:55.816  4017  4028 D BluetoothPbap: onBluetoothStateChange: up=false
08-30 14:40:55.816  1354  1367 D BluetoothHeadset: onBluetoothStateChange: up=false
08-30 14:40:55.817  4111  4203 D BluetoothAdapterState: Current state: BLE ON, message: 20
08-30 14:40:55.817  4111  4203 D BluetoothAdapterProperties: Setting state to 16
08-30 14:40:55.817  4111  4203 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
,08-30 14:40:55.817  4111  4203 D BluetoothAdapterProperties: onBleDisable
08-30 14:40:55.818  4111  4203 I BluetoothAdapterState: Entering PendingCommandState
08-30 14:40:55.818  4111  4204 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
,08-30 14:40:55.819  4111  4215 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
08-30 14:40:55.819  4111  4215 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-30 14:40:55.820  4111  4207 D BluetoothAdapterProperties: Scan Mode:20
08-30 14:40:55.820  3953  3953 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 14:40:55.822  3953  3953 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 14:40:55.823  4017  4017 D DockEventReceiver: finishStartingService: stopping service
08-30 14:40:55.824  3953  3953 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 14:40:55.825  3953  3953 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 14:40:55.826  4017  4017 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-30 14:40:55.830  1540  1540 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-30 14:40:55.831  4017  4017 D DockEventReceiver: finishStartingService: stopping service
,08-30 14:40:56.019  4111  4207 I bt_hci  : shut_down
,08-30 14:40:56.020  4111  4211 D bt_hwcfg: hw_epilog_process
08-30 14:40:56.022  4111  4211 I bt_vendor: low_power_mode_cb
,08-30 14:40:56.048  4111  4211 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,08-30 14:40:56.048  4111  4211 I bt_vendor: epilog_cb
08-30 14:40:56.048  4111  4211 I bt_hci  : epilog_finished_callback
,08-30 14:40:56.059  4111  4207 I bt_hci_h4: hal_close
08-30 14:40:56.061  4111  4207 I bt_userial_vendor: device fd = 51 close
,08-30 14:40:56.179  4111  4204 D bt_stack_manager: event_shut_down_stack finished.
,08-30 14:40:56.180  4111  4203 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,08-30 14:40:56.186  4111  4203 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,08-30 14:40:56.186  4111  4111 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-30 14:40:56.188  4111  4111 D BtGatt.GattService: Received stop request...Stopping profile...
,08-30 14:40:56.188  4111  4111 D BtGatt.GattService: stop()
,08-30 14:40:56.189  4111  4111 D BtGatt.AdvertiseManager: advertise clients cleared
08-30 14:40:56.193  4111  4111 V BluetoothAdapterState: isTurningOff()=false
,08-30 14:40:56.193  4111  4111 V BluetoothAdapterState: isTurningOn()=false
08-30 14:40:56.194  4111  4111 V BluetoothAdapterState: isBleTurningOn()=false
08-30 14:40:56.194  4111  4111 V BluetoothAdapterState: isBleTurningOff()=true
,08-30 14:40:56.195  4111  4203 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
08-30 14:40:56.195  4111  4203 D BluetoothAdapterProperties: Setting state to 10
08-30 14:40:56.196  4111  4203 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
,08-30 14:40:56.197  4111  4203 I BluetoothAdapterState: Entering OffState
08-30 14:40:56.199   875   892 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,08-30 14:40:56.231  4111  4111 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,08-30 14:40:56.231  4111  4111 W BluetoothSdpJni: Cleaning up Bluetooth Health object
,08-30 14:40:56.233  4111  4204 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,08-30 14:40:56.237  4111  4204 D bt_stack_manager: event_clean_up_stack finished.
,08-30 14:40:56.237  4111  4111 I BluetoothServiceJni: cleanupNative: return from cleanup
,08-30 14:40:56.240  4111  4111 I art     : System.exit called, status: 0
,08-30 14:40:56.240  4111  4111 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-30 14:40:56.295   875  1943 I ActivityManager: Process com.android.bluetooth (pid 4111) has died
,08-30 14:40:58.121  3498  3509 D Finsky  : [264] ContentFiltersService$1.getContentFiltersAndIntent: Received content filters request from com.google.android.apps.books
,08-30 14:40:58.136  1540  1540 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-30 14:40:58.163  1540  1540 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-30 14:40:58.167  1540  1540 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-30 14:40:58.219  1540  1559 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
,08-30 14:40:58.219  1540  1559 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
,08-30 14:40:58.219  1540  1559 I GLSUser : [GLSUser] Extracting token using key: Auth
08-30 14:40:58.220  1540  1559 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-30 14:40:58.255  3498  3509 D Finsky  : [264] DfeContentFilters.logException: Unable to retrieve ContentFilterSettingsResponse: AuthFailureError
,08-30 14:40:58.738  3953  4001 D io.jxcore.node.ConnectivityMonitor: stop
,08-30 14:40:58.739  3953  4001 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-30 14:41:01.746  3953  4001 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-30 14:41:01.747  3953  4001 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@4c89559 added. We now have 6 listener(s)
08-30 14:41:01.747  3953  4001 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-30 14:41:01.751  3953  4001 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-30 14:41:01.751  3953  4001 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2bee51e added. We now have 7 listener(s)
08-30 14:41:01.752  3953  4001 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-30 14:41:01.753  3953  4001 I System.out: IsBluetoothEnabled
,08-30 14:41:01.765  3953  4001 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 14:41:01.820   875   892 I ActivityManager: Start proc 4251:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,08-30 14:41:01.945  4251  4251 D AdapterServiceConfig: Adding HeadsetService
,08-30 14:41:01.945  4251  4251 D AdapterServiceConfig: Adding A2dpService
08-30 14:41:01.945  4251  4251 D AdapterServiceConfig: Adding HidService
08-30 14:41:01.945  4251  4251 D AdapterServiceConfig: Adding HealthService
08-30 14:41:01.946  4251  4251 D AdapterServiceConfig: Adding PanService
08-30 14:41:01.946  4251  4251 D AdapterServiceConfig: Adding GattService
08-30 14:41:01.946  4251  4251 D AdapterServiceConfig: Adding BluetoothMapService
,08-30 14:41:01.963  4251  4251 D BluetoothAdapterState: make() - Creating AdapterState
08-30 14:41:01.963   875   892 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@abffc8e:true
,08-30 14:41:01.968  4251  4251 I bt_bluedroid: init
,08-30 14:41:01.969  4251  4263 I BluetoothAdapterState: Entering OffState
,08-30 14:41:01.972  4251  4264 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,08-30 14:41:01.972  4251  4264 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-30 14:41:01.972  4251  4264 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-30 14:41:01.972  4251  4264 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,08-30 14:41:01.973  4251  4251 I bt_bluedroid: get_profile_interface socket
08-30 14:41:01.975  4251  4251 I bt_bluedroid: get_profile_interface sdp
,08-30 14:41:01.979  4251  4267 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-30 14:41:01.982  4251  4267 D BluetoothAdapterProperties: Name is: Nexus 6
,08-30 14:41:01.982  4251  4262 I bt_bluedroid: config_hci_snoop_log
,08-30 14:41:01.988   875   892 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,08-30 14:41:01.998  4251  4263 D BluetoothAdapterState: Current state: OFF, message: 0
,08-30 14:41:01.999  4251  4263 D BluetoothAdapterProperties: Setting state to 14
08-30 14:41:01.999  4251  4263 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,08-30 14:41:02.003  4251  4263 D BluetoothBondStateMachine: make
,08-30 14:41:02.009  4251  4269 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-30 14:41:02.014  4251  4263 I BluetoothAdapterState: Entering PendingCommandState
,08-30 14:41:02.016  4251  4251 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,08-30 14:41:02.019  4251  4251 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@335a16b
,08-30 14:41:02.020  4251  4251 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-30 14:41:02.021  4251  4251 D BtGatt.GattService: Received start request. Starting profile...
08-30 14:41:02.021  4251  4251 D BtGatt.GattService: start()
08-30 14:41:02.021  4251  4251 I bt_bluedroid: get_profile_interface gatt
,08-30 14:41:02.022  4251  4251 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@335a16b
08-30 14:41:02.022  4251  4251 D BtGatt.AdvertiseManager: advertise manager created
,08-30 14:41:02.034  4251  4251 V BluetoothAdapterState: isTurningOff()=false
08-30 14:41:02.035  4251  4251 V BluetoothAdapterState: isTurningOn()=false
08-30 14:41:02.035  4251  4251 V BluetoothAdapterState: isBleTurningOn()=true
,08-30 14:41:02.035  4251  4251 V BluetoothAdapterState: isBleTurningOff()=false
08-30 14:41:02.035  4251  4263 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
08-30 14:41:02.036  4251  4263 I bt_bluedroid: enable
,08-30 14:41:02.036  4251  4264 D bt_stack_manager: event_start_up_stack is bringing up the stack.
08-30 14:41:02.037  4251  4264 I bt_hci  : start_up
,08-30 14:41:02.048  4251  4264 I bt_vendor: alloc value 0xb3a5e189
,08-30 14:41:02.048  4251  4264 I bt_vendor: init
08-30 14:41:02.048  4251  4264 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
08-30 14:41:02.049  4251  4264 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,08-30 14:41:02.157  4251  4264 D bt_hci  : start_up starting async portion
,08-30 14:41:02.158  4251  4272 I bt_hci  : event_finish_startup
,08-30 14:41:02.158  4251  4272 I bt_hci_h4: hal_open
,08-30 14:41:02.158  4251  4272 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,08-30 14:41:02.172  4251  4272 I bt_userial_vendor: device fd = 51 open
,08-30 14:41:02.199  4251  4272 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-30 14:41:02.231  4251  4272 D bt_hwcfg: Chipset BCM4354A2
,08-30 14:41:02.231  4251  4272 D bt_hwcfg: Target name = [BCM4354A2]
,08-30 14:41:02.232  4251  4272 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,08-30 14:41:02.900  4251  4272 I bt_hwcfg: bt vendor lib: set UART baud 115200
,08-30 14:41:02.901  4251  4272 D bt_hwcfg: Settlement delay -- 100 ms
08-30 14:41:02.901  4251  4272 I bt_hwcfg: Setting fw settlement delay to 100 
,08-30 14:41:03.018  4251  4272 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-30 14:41:03.019  4251  4272 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,08-30 14:41:03.049  4251  4272 I bt_hwcfg: vendor lib fwcfg completed
,08-30 14:41:03.050  4251  4272 I bt_vendor: firmware callback
08-30 14:41:03.050  4251  4272 I bt_hci  : firmware_config_callback
,08-30 14:41:03.061  4251  4275 I bt_btu  : btu_task pending for preload complete event
,08-30 14:41:03.061  4251  4275 I bt_btu_task: Bluetooth chip preload is complete
08-30 14:41:03.061  4251  4275 I bt_btu  : btu_task received preload complete event
,08-30 14:41:03.071  4251  4275 I         : BTE_InitTraceLevels -- TRC_HCI
,08-30 14:41:03.071  4251  4275 I         : BTE_InitTraceLevels -- TRC_L2CAP
,08-30 14:41:03.072  4251  4275 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-30 14:41:03.072  4251  4275 I         : BTE_InitTraceLevels -- TRC_AVDT
08-30 14:41:03.072  4251  4275 I         : BTE_InitTraceLevels -- TRC_AVRC
,08-30 14:41:03.072  4251  4275 I         : BTE_InitTraceLevels -- TRC_A2D
08-30 14:41:03.073  4251  4275 I         : BTE_InitTraceLevels -- TRC_BNEP
08-30 14:41:03.073  4251  4275 I         : BTE_InitTraceLevels -- TRC_BTM
,08-30 14:41:03.073  4251  4275 I         : BTE_InitTraceLevels -- TRC_GAP
08-30 14:41:03.073  4251  4275 I         : BTE_InitTraceLevels -- TRC_PAN
,08-30 14:41:03.074  4251  4275 I         : BTE_InitTraceLevels -- TRC_SDP
,08-30 14:41:03.074  4251  4275 I         : BTE_InitTraceLevels -- TRC_GATT
08-30 14:41:03.074  4251  4275 I         : BTE_InitTraceLevels -- TRC_SMP
08-30 14:41:03.074  4251  4275 I         : BTE_InitTraceLevels -- TRC_BTAPP
,08-30 14:41:03.075  4251  4275 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-30 14:41:03.209  4251  4275 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb39dbd9d
,08-30 14:41:03.209  4251  4275 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb39dbd9d 
,08-30 14:41:03.217  4251  4267 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,08-30 14:41:03.219  4251  4267 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,08-30 14:41:03.220  4251  4267 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
08-30 14:41:03.225  4251  4267 D BluetoothAdapterProperties: Name is: Nexus 6
,08-30 14:41:03.228  4251  4267 D BluetoothAdapterProperties: Scan Mode:20
08-30 14:41:03.229  4251  4267 D BluetoothAdapterProperties: Discoverable Timeout:120
08-30 14:41:03.229  4251  4267 D bt_hci  : do_postload posting postload work item
,08-30 14:41:03.229  4251  4272 I bt_hci  : event_postload
08-30 14:41:03.230  4251  4272 I bt_vendor: sco_config_cb
,08-30 14:41:03.230  4251  4272 I bt_hci  : sco_config_callback postload finished.
,08-30 14:41:03.233  3953  3953 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 14:41:03.235  4251  4267 D bt_bte_conf: Device ID record 1 : primary
08-30 14:41:03.235  4251  4267 D bt_bte_conf:   vendorId            = 000f
,08-30 14:41:03.236  4251  4267 D bt_bte_conf:   vendorIdSource      = 0001
08-30 14:41:03.236  4251  4267 D bt_bte_conf:   product             = 1200
,08-30 14:41:03.236  4251  4267 D bt_bte_conf:   version             = 1436
08-30 14:41:03.236  4251  4267 D bt_bte_conf:   clientExecutableURL = 
,08-30 14:41:03.236  4251  4267 D bt_bte_conf:   serviceDescription  = 
08-30 14:41:03.236  4251  4267 D bt_bte_conf:   documentationURL    = 
,08-30 14:41:03.237  4251  4272 I bt_vendor: low_power_mode_cb
08-30 14:41:03.237  4251  4267 D bt_bte_conf: bte_load_did_conf no section named DID2.
,08-30 14:41:03.237  4251  4264 D bt_stack_manager: event_start_up_stack finished
08-30 14:41:03.239  4251  4263 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
,08-30 14:41:03.240  4251  4263 D BluetoothAdapterProperties: Setting state to 15
08-30 14:41:03.240  4251  4263 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
,08-30 14:41:03.241  4251  4263 I BluetoothAdapterState: Entering BleOnState
,08-30 14:41:03.246  4251  4263 D BluetoothAdapterState: Current state: BLE ON, message: 1
,08-30 14:41:03.247  4251  4263 D BluetoothAdapterProperties: Setting state to 11
,08-30 14:41:03.247  4251  4263 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
08-30 14:41:03.254  3953  3953 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 14:41:03.257  4251  4251 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@335a16b
,08-30 14:41:03.259  4251  4251 D HeadsetService: Received start request. Starting profile...
,08-30 14:41:03.265  4251  4251 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,08-30 14:41:03.265  4251  4251 D HeadsetStateMachine: make
,08-30 14:41:03.276  4251  4263 I BluetoothAdapterState: Entering PendingCommandState
,08-30 14:41:03.280  4251  4251 D HeadsetStateMachine: max_hf_connections = 1
,08-30 14:41:03.280  4251  4251 I bt_bluedroid: get_profile_interface handsfree
,08-30 14:41:03.280  4251  4267 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
,08-30 14:41:03.280  4251  4267 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
,08-30 14:41:03.286  4251  4251 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@335a16b
,08-30 14:41:03.287  1540  1540 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-30 14:41:03.287  4251  4251 D A2dpService: Received start request. Starting profile...
,08-30 14:41:03.289  4251  4251 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,08-30 14:41:03.289  4251  4251 I bt_bluedroid: get_profile_interface avrcp
,08-30 14:41:03.295  4251  4251 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-30 14:41:03.295  4251  4251 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-30 14:41:03.296  4251  4251 D A2dpStateMachine: make
,08-30 14:41:03.297  4251  4251 I bt_bluedroid: get_profile_interface a2dp
,08-30 14:41:03.298  4251  4267 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,08-30 14:41:03.302  4251  4283 D A2dpStateMachine: Enter Disconnected: -2
,08-30 14:41:03.302  4251  4251 I BluetoothHidServiceJni: classInitNative: succeeds
,08-30 14:41:03.303  4251  4251 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@335a16b
08-30 14:41:03.303  4251  4251 D HidService: Received start request. Starting profile...
08-30 14:41:03.303  4251  4251 I bt_bluedroid: get_profile_interface hidhost
,08-30 14:41:03.304  4251  4251 D HidService: setHidService(): set to: null
08-30 14:41:03.304  4251  4267 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb39bd3e5
08-30 14:41:03.304  4251  4267 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
08-30 14:41:03.304  4251  4251 I BluetoothHealthServiceJni: classInitNative: succeeds
,08-30 14:41:03.305  4251  4251 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@335a16b
,08-30 14:41:03.305  4251  4251 D HealthService: Received start request. Starting profile...
,08-30 14:41:03.306  4251  4251 I bt_bluedroid: get_profile_interface health
,08-30 14:41:03.307  4251  4251 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,08-30 14:41:03.308  4251  4251 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@335a16b
08-30 14:41:03.308  4251  4251 D PanService: Received start request. Starting profile...
,08-30 14:41:03.308  4251  4251 D BluetoothPanServiceJni: initializeNative(L110): pan
08-30 14:41:03.308  4251  4251 I bt_bluedroid: get_profile_interface pan
08-30 14:41:03.309  4251  4267 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,08-30 14:41:03.313  4251  4251 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@335a16b
,08-30 14:41:03.314  4251  4251 D BluetoothMapService: Received start request. Starting profile...
,08-30 14:41:03.314  4251  4251 D BluetoothMapService: start()
,08-30 14:41:03.317  4251  4251 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,08-30 14:41:03.318  4251  4251 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
,08-30 14:41:03.318  4251  4251 D BluetoothMapAppObserver: createReceiver()
,08-30 14:41:03.320  4251  4251 D BluetoothMapAppObserver: initObservers()
,08-30 14:41:03.320  4251  4251 D BluetoothMapAppObserver: getEnabledAccountItems()
,08-30 14:41:03.329  4251  4251 V BluetoothAdapterState: isTurningOff()=false
,08-30 14:41:03.329  4251  4251 V BluetoothAdapterState: isTurningOn()=true
08-30 14:41:03.329  4251  4251 V BluetoothAdapterState: isBleTurningOn()=false
,08-30 14:41:03.329  4251  4281 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-30 14:41:03.329  4251  4251 V BluetoothAdapterState: isBleTurningOff()=false
,08-30 14:41:03.332  4251  4251 V BluetoothAdapterState: isTurningOff()=false
,08-30 14:41:03.332  4251  4251 V BluetoothAdapterState: isTurningOn()=true
08-30 14:41:03.333  4251  4251 V BluetoothAdapterState: isBleTurningOn()=false
08-30 14:41:03.333  4251  4251 V BluetoothAdapterState: isBleTurningOff()=false
08-30 14:41:03.333  4251  4251 V BluetoothAdapterState: isTurningOff()=false
08-30 14:41:03.333  4251  4251 V BluetoothAdapterState: isTurningOn()=true
,08-30 14:41:03.333  4251  4251 V BluetoothAdapterState: isBleTurningOn()=false
08-30 14:41:03.333  4251  4251 V BluetoothAdapterState: isBleTurningOff()=false
08-30 14:41:03.334  4251  4251 V BluetoothAdapterState: isTurningOff()=false
,08-30 14:41:03.335  4251  4251 V BluetoothAdapterState: isTurningOn()=true
08-30 14:41:03.335  4251  4251 V BluetoothAdapterState: isBleTurningOn()=false
08-30 14:41:03.335  4251  4251 V BluetoothAdapterState: isBleTurningOff()=false
08-30 14:41:03.336  4251  4251 V BluetoothAdapterState: isTurningOff()=false
08-30 14:41:03.336  4251  4251 V BluetoothAdapterState: isTurningOn()=true
,08-30 14:41:03.336  4251  4251 V BluetoothAdapterState: isBleTurningOn()=false
08-30 14:41:03.336  4251  4251 V BluetoothAdapterState: isBleTurningOff()=false
08-30 14:41:03.337  4251  4251 V BluetoothAdapterState: isTurningOff()=false
,08-30 14:41:03.337  4251  4251 V BluetoothAdapterState: isTurningOn()=true
08-30 14:41:03.337  4251  4251 V BluetoothAdapterState: isBleTurningOn()=false
08-30 14:41:03.337  4251  4251 V BluetoothAdapterState: isBleTurningOff()=false
,08-30 14:41:03.338  4251  4263 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
08-30 14:41:03.338  4251  4263 D BluetoothAdapterProperties: ScanMode =  20
08-30 14:41:03.338  4251  4263 D BluetoothAdapterProperties: State =  11
,08-30 14:41:03.340  4251  4263 D BluetoothAdapterProperties: Setting state to 12
,08-30 14:41:03.341  4251  4263 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,08-30 14:41:03.342  4017  4243 D BluetoothMap: onBluetoothStateChange: up=true
08-30 14:41:03.342  4251  4263 I BluetoothAdapterState: Entering OnState
,08-30 14:41:03.346  4251  4267 D BluetoothAdapterProperties: Scan Mode:21
08-30 14:41:03.346  4251  4267 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-30 14:41:03.347  4017  4028 D BluetoothPan: onBluetoothStateChange on: true
,08-30 14:41:03.348  4251  4251 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,08-30 14:41:03.349  4251  4251 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
,08-30 14:41:03.351  3953  3953 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 14:41:03.351  3953  3953 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 14:41:03.351  3953  3953 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 14:41:03.351  3953  3953 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 14:41:03.351  3953  3953 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 14:41:03.351  3953  3953 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 14:41:03.351  3953  3953 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 14:41:03.351  3953  3953 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-30 14:41:03.351  1354  1367 D BluetoothPan: onBluetoothStateChange on: true
08-30 14:41:03.353  4251  4251 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-30 14:41:03.353  3953  3953 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-30 14:41:03.354  1354  2040 D BluetoothPbap: onBluetoothStateChange: up=true
,08-30 14:41:03.356  1354  1365 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-30 14:41:03.356  4251  4251 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-30 14:41:03.358  4251  4251 D ObexServerSockets: Succeed to create listening sockets 
08-30 14:41:03.358  4251  4251 D ObexServerSockets0: startAccept()
,08-30 14:41:03.358  4251  4251 D ObexServerSockets0: prepareForNewConnect()
08-30 14:41:03.359  4017  4029 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-30 14:41:03.361  4251  4251 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
08-30 14:41:03.361  4251  4251 D BluetoothSdpJni: SDP Create record success - handle: 0
,08-30 14:41:03.363  1928  1945 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-30 14:41:03.363  4251  4288 D ObexServerSockets0: Accepting socket connection...
,08-30 14:41:03.364  1354  1354 D BluetoothPan: BluetoothPAN Proxy object connected
,08-30 14:41:03.364  1354  1354 D PanProfile: Bluetooth service connected
08-30 14:41:03.365  1354  1354 D BluetoothA2dp: Proxy object connected
08-30 14:41:03.365  4251  4289 D ObexServerSockets0: Accepting socket connection...
,08-30 14:41:03.366   875   892 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-30 14:41:03.367  1354  1365 D BluetoothInputDevice: onBluetoothStateChange: up=true
,08-30 14:41:03.367   875   875 D BluetoothA2dp: Proxy object connected
,08-30 14:41:03.370   875   892 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-30 14:41:03.370   875   892 D BluetoothHeadset: onBluetoothStateChange: up=true
08-30 14:41:03.371  1354  1365 D BluetoothMap: onBluetoothStateChange: up=true
08-30 14:41:03.371  1354  1354 D BluetoothInputDevice: Proxy object connected
08-30 14:41:03.372  1354  1354 D HidProfile: Bluetooth service connected
,08-30 14:41:03.371  4017  4017 D BluetoothMap: Proxy object connected
,08-30 14:41:03.372  4017  4017 D MapProfile: Bluetooth service connected
,08-30 14:41:03.372  4017  4017 D BluetoothMap: getConnectedDevices()
08-30 14:41:03.374  4017  4243 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-30 14:41:03.375  4017  4017 D BluetoothPan: BluetoothPAN Proxy object connected
08-30 14:41:03.375  4017  4017 D PanProfile: Bluetooth service connected
08-30 14:41:03.376  4017  4017 D BluetoothA2dp: Proxy object connected
08-30 14:41:03.376  1354  1354 D BluetoothMap: Proxy object connected
08-30 14:41:03.376  1354  1354 D MapProfile: Bluetooth service connected
08-30 14:41:03.376  1354  1354 D BluetoothMap: getConnectedDevices()
08-30 14:41:03.376  4017  4029 D BluetoothHeadset: onBluetoothStateChange: up=true
08-30 14:41:03.377   875   892 D BluetoothHeadset: onBluetoothStateChange: up=true
08-30 14:41:03.377  4017  4028 D BluetoothPbap: onBluetoothStateChange: up=true
08-30 14:41:03.378  4017  4017 D BluetoothInputDevice: Proxy object connected
08-30 14:41:03.378  4017  4017 D HidProfile: Bluetooth service connected
,08-30 14:41:03.379  1354  1367 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-30 14:41:03.382  4251  4251 D BluetoothMapService: onReceive
08-30 14:41:03.382  4251  4251 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,08-30 14:41:03.382   875   875 I Telecom : BluetoothPhoneService: queryPhoneState
08-30 14:41:03.382  4251  4251 D BluetoothMapService: STATE_ON
08-30 14:41:03.383  3953  3953 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 14:41:03.390  4017  4017 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-30 14:41:03.396  4017  4017 D DockEventReceiver: finishStartingService: stopping service
,08-30 14:41:03.399  1540  1540 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-30 14:41:03.410  1354  1354 D BluetoothPbap: Proxy object connected
,08-30 14:41:03.410  1354  1354 D PbapServerProfile: Bluetooth service connected
,08-30 14:41:03.411  4251  4251 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
08-30 14:41:03.411  4251  4251 D ObexServerSockets0: prepareForNewConnect()
,08-30 14:41:03.416  4017  4017 D BluetoothPbap: Proxy object connected
,08-30 14:41:03.416  4017  4017 D PbapServerProfile: Bluetooth service connected
,08-30 14:41:03.424  4251  4295 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-30 14:41:03.438  4251  4299 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-30 14:41:03.439  4251  4299 I BtOppRfcommListener: Accept thread started.
,08-30 14:41:03.467   875   875 D BluetoothHeadset: Proxy object connected
08-30 14:41:03.467   875   875 D BluetoothHeadset: Proxy object connected
,08-30 14:41:03.467  1928  2126 D BluetoothHeadset: Proxy object connected
,08-30 14:41:03.468  4017  4028 D BluetoothHeadset: Proxy object connected
,08-30 14:41:03.468   875   875 D BluetoothHeadset: Proxy object connected
,08-30 14:41:03.468  4017  4017 D HeadsetProfile: Bluetooth service connected
,08-30 14:41:03.469  1354  1365 D BluetoothHeadset: Proxy object connected
,08-30 14:41:03.469  1354  1354 D HeadsetProfile: Bluetooth service connected
,08-30 14:41:03.470   875   892 D BluetoothHeadset: Proxy object connected
08-30 14:41:03.470   875   892 D BluetoothHeadset: Proxy object connected
,08-30 14:41:03.477  4017  4243 D BluetoothHeadset: Proxy object connected
,08-30 14:41:03.477  4017  4017 D HeadsetProfile: Bluetooth service connected
08-30 14:41:03.477   875   892 D BluetoothHeadset: Proxy object connected
,08-30 14:41:03.480  1354  1367 D BluetoothHeadset: Proxy object connected
,08-30 14:41:03.480  1354  1354 D HeadsetProfile: Bluetooth service connected
,08-30 14:41:03.787  3953  4001 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 14:41:03.787  3953  4001 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 14:41:03.787  3953  4001 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 14:41:03.787  3953  4001 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 14:41:03.787  3953  4001 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 14:41:03.787  3953  4001 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 14:41:03.787  3953  4001 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 14:41:03.787  3953  4001 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-30 14:41:03.795  3953  4001 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-30 14:41:03.800  3953  4001 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-30 14:41:03.800  3953  4001 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@84ae1ff added. We now have 8 listener(s)
,08-30 14:41:03.801  3953  4001 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-30 14:41:03.808   875  1952 D WifiService: setWifiEnabled: false pid=3953, uid=10000
,08-30 14:41:03.809   875  1952 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-30 14:41:03.819  3953  4001 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 14:41:03.820   875  1378 D WifiService: setWifiEnabled: true pid=3953, uid=10000
08-30 14:41:03.820   875  1378 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-30 14:41:03.830   875  1309 D WifiConfigStore: Loading config and enabling all networks 
,08-30 14:41:03.837  3953  3953 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 14:41:03.837  3953  3953 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 14:41:03.837  3953  3953 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 14:41:03.837  3953  3953 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 14:41:03.837  3953  3953 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 14:41:03.837  3953  3953 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 14:41:03.837  3953  3953 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 14:41:03.837  3953  3953 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-30 14:41:03.844  3953  4001 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 14:41:03.844  3953  4001 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 14:41:03.844  3953  4001 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 14:41:03.844  3953  4001 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 14:41:03.844  3953  4001 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 14:41:03.844  3953  4001 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 14:41:03.844  3953  4001 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 14:41:03.844  3953  4001 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-30 14:41:03.845  3953  3953 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-30 14:41:03.848  3953  4001 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-30 14:41:03.850   875  1309 D WifiConfigStore: loaded 0 passpoint configs
08-30 14:41:03.851   875  1309 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
08-30 14:41:03.852  3953  4001 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,08-30 14:41:03.852   875  1309 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,08-30 14:41:03.853  3953  4001 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,08-30 14:41:03.853   875  1309 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
08-30 14:41:03.853   875  1309 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
08-30 14:41:03.853   875  1309 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
08-30 14:41:03.853   875  1309 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
08-30 14:41:03.855  3953  4001 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@a8ae947 Bundle[{}]
08-30 14:41:03.857  3953  4001 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-30 14:41:03.857  3953  4001 I io.jxcore.node.LifeCycleMonitor: stop: OK
08-30 14:41:03.859  3953  4001 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,08-30 14:41:03.860  3953  4001 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,08-30 14:41:03.862  3953  4001 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
,08-30 14:41:03.865  3953  4001 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,08-30 14:41:03.875   875  1309 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.30 rxSuccessRate=0.33 delta 1000 -> 1000
,08-30 14:41:03.875   375   873 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
08-30 14:41:03.876   375   873 D CommandListener: Setting iface cfg
,08-30 14:41:03.876  3953  4001 I System.out: Running OutgoingSocketThread
08-30 14:41:03.877   875  1308 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '203 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 203 Failed to set address (No such device)'
08-30 14:41:03.877   875  1308 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,08-30 14:41:03.879  3953  4304 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 431)
08-30 14:41:03.879   875  1308 D WifiNative-HAL: p2pGetDeviceAddress
,08-30 14:41:03.879   875  1308 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,08-30 14:41:03.881  3953  4304 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 44126
,08-30 14:41:03.881  3953  4304 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,08-30 14:41:03.884   875  1309 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
,08-30 14:41:03.885   875  1309 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-30 14:41:03.899   875  1309 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,08-30 14:41:03.950   875  1309 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,08-30 14:41:03.954  1466  1466 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,08-30 14:41:04.101   875   895 I PowerManagerService: Going to sleep due to screen timeout (uid 1000)...
,08-30 14:41:04.109   875   895 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-30 14:41:04.109   875   895 I Adreno  : Build Date                       : 10/20/15
08-30 14:41:04.109   875   895 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-30 14:41:04.109   875   895 I Adreno  : Local Branch                     : M14
08-30 14:41:04.109   875   895 I Adreno  : Remote Branch                    : 
08-30 14:41:04.109   875   895 I Adreno  : Remote Branch                    : 
08-30 14:41:04.109   875   895 I Adreno  : Reconstruct Branch               : 
,08-30 14:41:04.116  1864  1864 I Keyboard.Facilitator: onFinishInput()
,08-30 14:41:04.135   280   302 D PermissionCache: checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (184 us)
,08-30 14:41:04.508  1466  1466 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-30 14:41:04.556  1466  1466 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,08-30 14:41:04.557  1466  1466 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,08-30 14:41:04.562   875  1309 D WifiConfigStore: Retrieve network priorities after PNO.
,08-30 14:41:04.575   875  1309 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{104}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-30 14:41:04.575   875  1309 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-30 14:41:04.575   875  1311 D ConnectivityService: NetworkAgentInfo [WIFI () - 104] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,08-30 14:41:04.599   875  1309 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-30 14:41:04.618   375   873 D CommandListener: Setting iface cfg
,08-30 14:41:04.620   875  1309 D WifiStateMachine: Start Dhcp Watchdog 5
,08-30 14:41:04.637   875  1311 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 104]
,08-30 14:41:04.637   875  1311 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 104] to 60
,08-30 14:41:04.641   875  1309 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,08-30 14:41:04.664   875  4309 D DhcpClient: Receive thread started
,08-30 14:41:04.747   875  1309 E native  : do suspend false
,08-30 14:41:04.766   875  1883 D DhcpClient: Broadcasting DHCPDISCOVER
,08-30 14:41:04.792   875  4309 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.101, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172783, domain null
,08-30 14:41:04.804  3953  3953 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,08-30 14:41:04.804  3953  3953 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,08-30 14:41:04.843   875   895 V KeyguardServiceDelegate: onScreenTurnedOff()
,08-30 14:41:04.844   875  1883 D DhcpClient: Got pending lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172783 seconds
,08-30 14:41:04.844  3953  3953 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@a8ae947 Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@2f81bcc, 16908290=android.view.AbsSavedState$1@2f81bcc}, android:focusedViewId=100}]}]
08-30 14:41:04.845  3953  3953 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
08-30 14:41:04.845  3953  3953 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
08-30 14:41:04.845  3953  3953 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
,08-30 14:41:04.850   875  1883 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.101 serverid=192.168.1.1
,08-30 14:41:04.853   875   895 E libEGL  : call to OpenGL ES API with no current context (logged once per thread)
,08-30 14:41:04.856   875   893 I DisplayManagerService: Display device changed state: "Built-in Screen", OFF
,08-30 14:41:04.856   280   280 D SurfaceFlinger: Set power mode=0, type=0 flinger=0xb6aa4000
08-30 14:41:04.856   280   280 D qdhwcomposer: hwc_setPowerMode: Setting mode 0 on display: 0
,08-30 14:41:04.875   875  4309 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.101, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,08-30 14:41:04.876   875  1883 D DhcpClient: Confirmed lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,08-30 14:41:04.878  3953  4001 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 432)
,08-30 14:41:04.878  3953  4001 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 432)
,08-30 14:41:04.879   375   873 D CommandListener: Setting iface cfg
,08-30 14:41:04.881   875  1309 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,08-30 14:41:04.882  3953  4001 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 437)
,08-30 14:41:04.883  3953  4001 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
,08-30 14:41:04.884   875  1883 D DhcpClient: Scheduling renewal in 86399s
08-30 14:41:04.883  3953  4001 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 438)
,08-30 14:41:04.887  3953  4001 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-30 14:41:04.887  3953  4001 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7e42e15 added. We now have 2 listener(s)
,08-30 14:41:04.888   875  1309 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,08-30 14:41:04.889  3953  4001 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-30 14:41:04.889  3953  4001 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-30 14:41:04.889   875  1309 D WifiConfigStore: No blacklist allowed without epno enabled
08-30 14:41:04.889  3953  4001 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-30 14:41:04.890  3953  4001 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 14:41:04.890  3953  4001 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b70352a added. We now have 9 listener(s)
08-30 14:41:04.890  3953  4001 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 14:41:04.890   875  1311 D ConnectivityService: NetworkAgentInfo [WIFI () - 104] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,08-30 14:41:04.890  3953  4001 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-30 14:41:04.890   875  1311 D ConnectivityService: Adding iface wlan0 to network 104
,08-30 14:41:04.893   875  1309 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,08-30 14:41:04.894  3953  4001 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-30 14:41:04.898  3953  4001 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 14:41:04.898  3953  4001 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 14:41:04.898  3953  4001 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 14:41:04.898  3953  4001 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 14:41:04.898  3953  4001 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 14:41:04.898  3953  4001 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 14:41:04.898  3953  4001 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 14:41:04.898  3953  4001 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-30 14:41:04.899  3953  4001 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-30 14:41:04.899  3953  4001 D io.jxcore.node.ConnectivityMonitor: start: OK
08-30 14:41:04.900  3953  4001 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-30 14:41:04.900  3953  4001 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d7128b8 added. We now have 3 listener(s)
08-30 14:41:04.900  3953  3953 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 14:41:04.901  3953  4001 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-30 14:41:04.901  3953  4001 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-30 14:41:04.901  3953  4001 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-30 14:41:04.901  3953  4001 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 14:41:04.901  3953  4001 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9e69691 added. We now have 10 listener(s)
08-30 14:41:04.901  3953  4001 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 14:41:04.901  3953  4001 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 14:41:04.901  3953  4001 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 14:41:04.901  3953  4001 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 14:41:04.901  3953  4001 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 14:41:04.901  3953  4001 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 14:41:04.901  3953  4001 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 14:41:04.901  3953  3953 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 14:41:04.901  3953  4001 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-30 14:41:04.901  3953  4001 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7e42e15 removed from the list
08-30 14:41:04.901  3953  4001 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 14:41:04.901  3953  4001 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b70352a removed from the list
08-30 14:41:04.901  3953  4001 D io.jxcore.node.ConnectivityMonitor: stop
08-30 14:41:04.901  3953  4001 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 14:41:04.902  3953  4001 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 14:41:04.902  3953  4001 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 14:41:04.902  3953  4001 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 14:41:04.902  3953  4001 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 14:41:04.902  3953  4001 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 14:41:04.902  3953  4001 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b70352a not in the list
08-30 14:41:04.902  3953  4001 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 14:41:04.903  3953  4001 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 14:41:04.903  3953  4001 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 14:41:04.903  3953  4001 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 14:41:04.903  3953  4001 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 14:41:04.903  3953  4001 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9e69691 removed from the list
08-30 14:41:04.903  3953  4001 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 14:41:04.903  3953  4001 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 14:41:04.903  3953  4001 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 14:41:04.903  3953  4001 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-30 14:41:04.903  3953  4001 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d7128b8 removed from the list
08-30 14:41:04.904  3953  4001 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-30 14:41:04.904  3953  4001 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e3479f6 added. We now have 2 listener(s)
08-30 14:41:04.905  3953  4001 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-30 14:41:04.905  3953  4001 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-30 14:41:04.905  3953  4001 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-30 14:41:04.905  3953  4001 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 14:41:04.905  3953  4001 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c511f7 added. We now have 9 listener(s)
08-30 14:41:04.905  3953  4001 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 14:41:04.905  3953  4001 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-30 14:41:04.907  3953  4001 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 14:41:04.912  3953  4001 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 14:41:04.912  3953  4001 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 14:41:04.912  3953  4001 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 14:41:04.912  3953  4001 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 14:41:04.912  3953  4001 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 14:41:04.912  3953  4001 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 14:41:04.912  3953  4001 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 14:41:04.912  3953  4001 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 14:41:04.913  3953  4001 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-30 14:41:04.913  3953  4001 D io.jxcore.node.ConnectivityMonitor: start: OK
08-30 14:41:04.913  3953  4001 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-30 14:41:04.913  3953  4001 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8cd0acd added. We now have 3 listener(s)
08-30 14:41:04.914  3953  3953 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 14:41:04.914  3953  4001 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-30 14:41:04.914  3953  4001 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-30 14:41:04.914  3953  4001 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-30 14:41:04.915  3953  4001 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 14:41:04.915  3953  4001 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@263f82 added. We now have 10 listener(s)
08-30 14:41:04.915  3953  4001 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 14:41:04.915  3953  4001 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-30 14:41:04.915  3953  4001 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-30 14:41:04.915  3953  4001 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-30 14:41:04.915  3953  4001 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 14:41:04.915  3953  4001 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-30 14:41:04.915  3953  3953 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 14:41:04.917  3953  4001 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-30 14:41:04.917  3953  4001 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-30 14:41:04.919  3953  4001 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-30 14:41:04.919  3953  4001 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-30 14:41:04.919  3953  4001 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-30 14:41:04.921  3953  4001 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-30 14:41:04.921  3953  4001 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-30 14:41:04.921  3953  4001 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-30 14:41:04.922  3953  4001 D BluetoothAdapter: STATE_ON
08-30 14:41:04.924  4251  4268 D BtGatt.GattService: registerClient() - UUID=cf875981-ebb4-4e44-9c1f-5b2b15c684fa
08-30 14:41:04.924  4251  4267 D BtGatt.GattService: onClientRegistered() - UUID=cf875981-ebb4-4e44-9c1f-5b2b15c684fa, clientIf=5
08-30 14:41:04.924   875  1311 E ConnectivityService: Unexpected mtu value: 0, wlan0
08-30 14:41:04.925   875  1311 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 104
08-30 14:41:04.925  3953  3963 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-30 14:41:04.925   875  1311 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 104
08-30 14:41:04.925  4251  4261 D BtGatt.GattService: start scan with filters
08-30 14:41:04.926   875  1311 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 104
,08-30 14:41:04.926   875  1311 D ConnectivityService: Setting Dns servers for network 104 to [/192.168.1.1]
08-30 14:41:04.929  4251  4271 D BtGatt.ScanManager: handling starting scan
08-30 14:41:04.929  3953  4001 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-30 14:41:04.929  3953  4001 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-30 14:41:04.929  3953  4001 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-30 14:41:04.929  3953  4001 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
08-30 14:41:04.930  4251  4271 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@335a16b
08-30 14:41:04.932   875  1311 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 104]
08-30 14:41:04.932  4251  4267 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-30 14:41:04.932  4251  4267 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-30 14:41:04.932  4251  4271 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
08-30 14:41:04.934  4251  4267 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-30 14:41:04.934  4251  4267 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-30 14:41:04.934  4251  4271 D BtGatt.ScanManager: Starting BLE batch scan
08-30 14:41:04.934  4251  4271 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-30 14:41:04.935   875  1311 D ConnectivityService: scheduleUnvalidatedPrompt 104
08-30 14:41:04.935   875  1311 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 104]
08-30 14:41:04.935   875  1311 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 104]
08-30 14:41:04.935   875  1309 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
08-30 14:41:04.935   875  1311 D ConnectivityService:    accepting network in place of null
08-30 14:41:04.936  4251  4267 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-30 14:41:04.936  4251  4267 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-30 14:41:04.936   875  1309 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-30 14:41:04.936   875  1311 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{104}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.101/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -47]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
08-30 14:41:04.937  4251  4267 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-30 14:41:04.937  4251  4267 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-30 14:41:04.938  3953  4001 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-30 14:41:04.938  3953  3953 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-30 14:41:04.939  3953  4001 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-30 14:41:04.940  3953  4001 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
08-30 14:41:04.943  3953  4001 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-30 14:41:04.943  3953  4001 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-30 14:41:04.943  3953  4001 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-30 14:41:04.943  3953  4001 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 14:41:04.943  3953  4001 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-30 14:41:04.943  3953  4001 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-30 14:41:04.943  3953  4001 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-30 14:41:04.943  3953  4001 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-30 14:41:04.943  3953  4001 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-30 14:41:04.943  3953  4001 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-30 14:41:04.943  3953  4001 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-30 14:41:04.944  3953  4001 D BluetoothAdapter: STATE_ON
08-30 14:41:04.944  4251  4291 D BtGatt.GattService: stopScan() - queue size =1
08-30 14:41:04.945  4251  4261 D BtGatt.GattService: unregisterClient() - clientIf=5
08-30 14:41:04.946  4251  4267 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-30 14:41:04.946  4251  4267 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-30 14:41:04.946  4251  4271 D BtGatt.ScanManager: stopping BLe Batch
08-30 14:41:04.946  3953  4001 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-30 14:41:04.946  3953  4001 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-30 14:41:04.947  3953  4001 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-30 14:41:04.947  3953  4001 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-30 14:41:04.947  3953  4001 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-30 14:41:04.948  4251  4267 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-30 14:41:04.948  4251  4267 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-30 14:41:04.948  4251  4271 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
08-30 14:41:04.948  3953  4001 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-30 14:41:04.949  3953  4001 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-30 14:41:04.949  3953  4001 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-30 14:41:04.949  3953  4001 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-30 14:41:04.949  4251  4267 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-30 14:41:04.949  4251  4267 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-30 14:41:04.950  3953  4001 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 14:41:04.951  3953  3953 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-30 14:41:04.951  3953  3953 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-30 14:41:04.951  3953  3953 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-30 14:41:04.953  3953  4001 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 14:41:04.953  3953  4001 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 14:41:04.953  3953  4001 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 14:41:04.953  3953  4001 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 14:41:04.953  3953  4001 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 14:41:04.953  3953  4001 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 14:41:04.953  3953  4001 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-30 14:41:04.953  3953  4001 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e3479f6 removed from the list
08-30 14:41:04.953  3953  4001 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 14:41:04.953  3953  4001 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c511f7 removed from the list
08-30 14:41:04.954   375   873 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
08-30 14:41:04.954  3953  4001 D io.jxcore.node.ConnectivityMonitor: stop
08-30 14:41:04.954  3953  4001 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 14:41:04.955  3953  4001 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 14:41:04.955  3953  4001 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 14:41:04.955  3953  4001 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 14:41:04.955  3953  4001 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 14:41:04.956  3953  4001 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 14:41:04.956  3953  4001 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c511f7 not in the list
08-30 14:41:04.956  3953  4001 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 14:41:04.956  3953  4001 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 14:41:04.956  3953  4001 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 14:41:04.956  3953  4001 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 14:41:04.956  3953  4001 I org.thaliproject.p2p.btconnector,lib.DiscoveryManager: dispose
08-30 14:41:04.956  3953  4001 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@263f82 removed from the list
08-30 14:41:04.956  3953  4001 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 14:41:04.957  3953  4001 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 14:41:04.957  3953  4001 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 14:41:04.957  3953  4001 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-30 14:41:04.957  3953  4001 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8cd0acd removed from the list
,08-30 14:41:04.957  3953  4001 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-30 14:41:04.957  3953  4001 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b7cd1ce added. We now have 2 listener(s)
08-30 14:41:04.958  3953  4001 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-30 14:41:04.958  3953  4001 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-30 14:41:04.958  3953  4001 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-30 14:41:04.958  3953  4001 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 14:41:04.958  3953  4001 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f6648ef added. We now have 9 listener(s)
08-30 14:41:04.959  3953  4001 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-30 14:41:04.959  3953  4001 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-30 14:41:04.960  3953  4001 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 14:41:04.964  3953  4001 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 14:41:04.964  3953  4001 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 14:41:04.964  3953  4001 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 14:41:04.964  3953  4001 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 14:41:04.964  3953  4001 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 14:41:04.964  3953  4001 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 14:41:04.964  3953  4001 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 14:41:04.964  3953  4001 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-30 14:41:04.965  3953  4001 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-30 14:41:04.965  3953  4001 D io.jxcore.node.ConnectivityMonitor: start: OK
08-30 14:41:04.966   875  4308 D NetlinkSocketObserver: NeighborEvent{elapsedMs=150978, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
08-30 14:41:04.967  3953  3953 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 14:41:04.966  3953  4001 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-30 14:41:04.969  3953  3953 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 14:41:04.969  3953  4001 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1edc685 added. We now have 3 listener(s)
08-30 14:41:04.970  3953  4001 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-30 14:41:04.970  3953  4001 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-30 14:41:04.970  3953  4001 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-30 14:41:04.971  3953  4001 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 14:41:04.971  3953  4001 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4983cda added. We now have 10 listener(s)
,08-30 14:41:04.971  3953  4001 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 14:41:04.971  3953  4001 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-30 14:41:04.971  3953  4001 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-30 14:41:04.972  3953  4001 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,08-30 14:41:04.972  3953  4001 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-30 14:41:04.972  3953  4001 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 14:41:04.972  3953  4001 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-30 14:41:04.973   375   873 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
08-30 14:41:04.974  3953  4001 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-30 14:41:04.975  3953  4001 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-30 14:41:04.976   875  1311 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 104] isDefaultNetwork=true
,08-30 14:41:04.976   875  1311 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
08-30 14:41:04.978   875  1311 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 104]
,08-30 14:41:04.980   875   892 D Tethering: MasterInitialState.processMessage what=3
08-30 14:41:04.982  3953  4001 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-30 14:41:04.982  3953  4001 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-30 14:41:04.983  3953  4001 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-30 14:41:04.987  3953  3953 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 14:41:04.987  3953  3953 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 14:41:04.987  3953  3953 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 14:41:04.987  3953  3953 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 14:41:04.987  3953  3953 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 14:41:04.987  3953  3953 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 14:41:04.987  3953  3953 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 14:41:04.987  3953  3953 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-30 14:41:04.990  3953  3953 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-30 14:41:04.991  3953  4001 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-30 14:41:04.991  3953  4001 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-30 14:41:04.991  3953  4001 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-30 14:41:04.992  3953  4001 D BluetoothAdapter: STATE_ON
08-30 14:41:04.992  3953  3953 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 14:41:04.993  4251  4290 D BtGatt.GattService: registerClient() - UUID=b2fb2de2-42ec-4a3b-9949-583cd915c776
08-30 14:41:04.993  1744  1744 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
08-30 14:41:04.994  4251  4267 D BtGatt.GattService: onClientRegistered() - UUID=b2fb2de2-42ec-4a3b-9949-583cd915c776, clientIf=5
,08-30 14:41:04.994  3953  3963 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-30 14:41:04.994  4251  4262 D BtGatt.GattService: start scan with filters
,08-30 14:41:04.996  4251  4271 D BtGatt.ScanManager: handling starting scan
,08-30 14:41:04.996  3953  4001 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-30 14:41:04.996  3953  4001 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,08-30 14:41:04.997  3953  4001 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,08-30 14:41:04.997  3953  4001 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
08-30 14:41:04.998  3953  4001 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-30 14:41:04.998  4251  4267 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,08-30 14:41:04.998  3953  3953 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-30 14:41:04.998  4251  4267 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-30 14:41:04.998  3953  4001 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-30 14:41:04.999  4251  4271 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
08-30 14:41:04.999  1744  1744 D SystemUpdateService: onCreate
,08-30 14:41:04.999  3953  4001 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
08-30 14:41:05.000  4251  4267 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-30 14:41:05.000  4251  4267 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-30 14:41:05.000  4251  4271 D BtGatt.ScanManager: Starting BLE batch scan
,08-30 14:41:05.000  4251  4271 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-30 14:41:05.001  3953  4001 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,08-30 14:41:05.001  3953  4001 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
08-30 14:41:05.001  3953  4001 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-30 14:41:05.001  3953  4001 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 14:41:05.001  3953  4001 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-30 14:41:05.002  3953  4001 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 14:41:05.002  3953  4001 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 14:41:05.002  3953  4001 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-30 14:41:05.002  3953  4001 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-30 14:41:05.002  3953  4001 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b7cd1ce removed from the list
,08-30 14:41:05.002  3953  4001 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 14:41:05.002  3953  4001 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f6648ef removed from the list
,08-30 14:41:05.002  4251  4267 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-30 14:41:05.002  3953  4001 D io.jxcore.node.ConnectivityMonitor: stop
08-30 14:41:05.002  4251  4267 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-30 14:41:05.002  3953  4001 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-30 14:41:05.002  3953  4001 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
,08-30 14:41:05.002  3953  4001 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
08-30 14:41:05.002  3953  4001 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 14:41:05.002  1744  1744 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
08-30 14:41:05.002  3953  4001 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-30 14:41:05.003  3953  4001 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 14:41:05.003  3953  4001 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 14:41:05.003  3953  4001 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 14:41:05.003  3953  4001 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f6648ef not in the list
08-30 14:41:05.003  3953  4001 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,08-30 14:41:05.003  3953  4001 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-30 14:41:05.003  4251  4267 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,08-30 14:41:05.003  3953  4001 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-30 14:41:05.003  4251  4267 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-30 14:41:05.003  3953  4001 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-30 14:41:05.003  3953  4001 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-30 14:41:05.004  3953  4001 D BluetoothAdapter: STATE_ON
08-30 14:41:05.004  4251  4262 D BtGatt.GattService: stopScan() - queue size =1
08-30 14:41:05.005  4251  4261 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-30 14:41:05.005  3953  4001 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-30 14:41:05.005  3953  4001 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-30 14:41:05.005  3953  4001 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false,
08-30 14:41:05.005  3953  4001 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-30 14:41:05.005  3953  4001 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-30 14:41:05.006  3953  4001 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-30 14:41:05.007  3953  4001 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-30 14:41:05.007  3953  4001 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-30 14:41:05.007  3953  4001 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...,
08-30 14:41:05.007  3953  4001 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 14:41:05.007  4251  4267 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-30 14:41:05.007  4251  4267 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-30 14:41:05.007  4251  4271 D BtGatt.ScanManager: stopping BLe Batch
08-30 14:41:05.008  3953  3953 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-30 14:41:05.008  3953  3953 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-30 14:41:05.008  3953  3953 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-30 14:41:05.008  3953  4001 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 14:41:05.008  3953  4001 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 14:41:05.008  3953  4001 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-30 14:41:05.009  3953  4001 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4983cda removed from the list
08-30 14:41:05.009  3953  4001 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 14:41:05.009  3953  4001 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-30 14:41:05.009  3953  4001 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 14:41:05.009  3953  4001 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-30 14:41:05.009  3953  4001 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1edc685 removed from the list
08-30 14:41:05.009  4251  4267 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-30 14:41:05.009  4251  4267 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-30 14:41:05.009  3953  4001 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-30 14:41:05.009  3953  4001 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3cd4ca6 added. We now have 2 listener(s)
08-30 14:41:05.009  4251  4271 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
08-30 14:41:05.010  3953  4001 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-30 14:41:05.010  3953  4001 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-30 14:41:05.011  3953  4001 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-30 14:41:05.011  3953  4001 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 14:41:05.011  4251  4267 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-30 14:41:05.011  3953  4001 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a2866e7 added. We now have 9 listener(s)
,08-30 14:41:05.011  4251  4267 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-30 14:41:05.011  3953  4001 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 14:41:05.011  3953  4001 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-30 14:41:05.012  3953  4001 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-30 14:41:05.015  3953  4001 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 14:41:05.015  3953  4001 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 14:41:05.015  3953  4001 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 14:41:05.015  3953  4001 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 14:41:05.015  3953  4001 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 14:41:05.015  3953  4001 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 14:41:05.015  3953  4001 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 14:41:05.015  3953  4001 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-30 14:41:05.017  3953  4001 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-30 14:41:05.017  3953  4001 D io.jxcore.node.ConnectivityMonitor: start: OK
08-30 14:41:05.017  3953  4001 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-30 14:41:05.017  3953  4001 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@883413d added. We now have 3 listener(s)
08-30 14:41:05.018  3953  4001 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-30 14:41:05.018  3953  4001 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66,
08-30 14:41:05.018  3953  3953 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 14:41:05.018  3953  4001 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-30 14:41:05.019  3953  4001 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 14:41:05.019  3953  4001 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ff18d32 added. We now have 10 listener(s)
08-30 14:41:05.019  3953  4001 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 14:41:05.019  3953  4001 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-30 14:41:05.019  3953  4001 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,08-30 14:41:05.019  3953  4001 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,08-30 14:41:05.019  3953  4001 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 14:41:05.019  3953  4001 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-30 14:41:05.020  3953  3953 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 14:41:05.021  3953  4001 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-30 14:41:05.021  3953  4001 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-30 14:41:05.021  1744  1744 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,08-30 14:41:05.023  3953  4001 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-30 14:41:05.023  1744  2424 I iu.UploadsManager: num queued entries: 0
08-30 14:41:05.024  3953  4001 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-30 14:41:05.024  3953  4001 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0,
08-30 14:41:05.026  3953  4001 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-30 14:41:05.026  3953  4001 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-30 14:41:05.026  3953  4001 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-30 14:41:05.026  3953  4001 D BluetoothAdapter: STATE_ON
08-30 14:41:05.028  4251  4268 D BtGatt.GattService: registerClient() - UUID=b5460da7-81df-44a1-a66a-5a408a77b755
,08-30 14:41:05.028  4251  4267 D BtGatt.GattService: onClientRegistered() - UUID=b5460da7-81df-44a1-a66a-5a408a77b755, clientIf=5
08-30 14:41:05.028  3953  3963 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-30 14:41:05.028  4251  4290 D BtGatt.GattService: start scan with filters
,08-30 14:41:05.031  3953  4001 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-30 14:41:05.031  3953  4001 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-30 14:41:05.031  4251  4271 D BtGatt.ScanManager: handling starting scan
,08-30 14:41:05.031  3953  4001 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-30 14:41:05.031  3953  4001 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
08-30 14:41:05.032  1744  4319 I SystemUpdateService: active receiver: enabled
08-30 14:41:05.033  4251  4267 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,08-30 14:41:05.033  4251  4267 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-30 14:41:05.032  3953  4001 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-30 14:41:05.033  3953  4001 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-30 14:41:05.033  4251  4271 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
08-30 14:41:05.033  3953  3953 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-30 14:41:05.034  1744  1744 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
08-30 14:41:05.034  4251  4267 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-30 14:41:05.034  4251  4267 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-30 14:41:05.034  4251  4271 D BtGatt.ScanManager: Starting BLE batch scan
,08-30 14:41:05.034  3953  4001 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
08-30 14:41:05.034  4251  4271 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-30 14:41:05.035  1744  1744 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-30 14:41:05.036  4251  4267 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-30 14:41:05.036  4251  4267 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-30 14:41:05.037  4251  4267 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-30 14:41:05.037  3953  4001 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 14:41:05.037  4251  4267 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-30 14:41:05.037  3953  4001 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 14:41:05.037  3953  4001 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 14:41:05.037  3953  4001 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-30 14:41:05.038  3953  4001 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 14:41:05.038  3953  4001 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-30 14:41:05.038  3768  3768 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
08-30 14:41:05.038  3953  4001 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-30 14:41:05.038  3953  4001 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3cd4ca6 removed from the list
08-30 14:41:05.038  3953  4001 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 14:41:05.038  3953  4001 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a2866e7 removed from the list
08-30 14:41:05.038  3953  4001 D io.jxcore.node.ConnectivityMonitor: stop
,08-30 14:41:05.038  3953  4001 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 14:41:05.038  3953  4001 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
08-30 14:41:05.038  3953  4001 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
08-30 14:41:05.038  3953  4001 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 14:41:05.038  3953  4001 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-30 14:41:05.039  3953  4001 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 14:41:05.039  3953  4001 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-30 14:41:05.039  3953  4001 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 14:41:05.039  3953  4001 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a2866e7 not in the list
08-30 14:41:05.039  3953  4001 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-30 14:41:05.039  3953  4001 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,08-30 14:41:05.039  3953  4001 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-30 14:41:05.039  3953  4001 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-30 14:41:05.039  3953  4001 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-30 14:41:05.040  3953  4001 D BluetoothAdapter: STATE_ON
08-30 14:41:05.040  4251  4291 D BtGatt.GattService: stopScan() - queue size =1
08-30 14:41:05.041  4251  4268 D BtGatt.GattService: unregisterClient() - clientIf=5
08-30 14:41:05.041  3953  4001 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-30 14:41:05.041  3953  4001 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-30 14:41:05.041  3953  4001 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,08-30 14:41:05.041  3953  4001 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-30 14:41:05.041  3953  4001 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-30 14:41:05.041  4251  4267 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-30 14:41:05.041  4251  4267 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-30 14:41:05.042  4251  4271 D BtGatt.ScanManager: stopping BLe Batch
08-30 14:41:05.042  3953  4001 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-30 14:41:05.042  3953  4001 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-30 14:41:05.042  3953  4001 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-30 14:41:05.042  3953  4001 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-30 14:41:05.042  3953  4001 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 14:41:05.043  3953  4001 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-30 14:41:05.043  3953  4001 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 14:41:05.043  3953  4001 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 14:41:05.043  3953  4001 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ff18d32 removed from the list
08-30 14:41:05.043  3953  3953 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-30 14:41:05.043  3953  4001 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 14:41:05.043  3953  4001 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 14:41:05.043  3953  4001 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 14:41:05.043  3953  3953 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-30 14:41:05.043  3953  4001 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-30 14:41:05.043  3953  4001 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@883413d removed from the list
08-30 14:41:05.043  3953  3953 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-30 14:41:05.044  3768  3768 D SprintDMHelper: simOperator: 
08-30 14:41:05.044  3953  4001 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-30 14:41:05.044  3768  3768 D SprintDMReceiver: Not Sprint UICC, don't do anything.
08-30 14:41:05.044  3953  4001 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5a74a7e added. We now have 2 listener(s)
08-30 14:41:05.044  4251  4267 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-30 14:41:05.044  4251  4267 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-30 14:41:05.045  4251  4271 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
08-30 14:41:05.045  3953  4001 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-30 14:41:05.045  3953  4001 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-30 14:41:05.045  3953  4001 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-30 14:41:05.045  3953  4001 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 14:41:05.045  3953  4001 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c614bdf added. We now have 9 listener(s)
08-30 14:41:05.045  3953  4001 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 14:41:05.046  3953  4001 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-30 14:41:05.047  4251  4267 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-30 14:41:05.047  4251  4267 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-30 14:41:05.047  3953  4001 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-30 14:41:05.050  3953  4001 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 14:41:05.050  3953  4001 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 14:41:05.050  3953  4001 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 14:41:05.050  3953  4001 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 14:41:05.050  3953  4001 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 14:41:05.050  3953  4001 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 14:41:05.050  3953  4001 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 14:41:05.050  3953  4001 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-30 14:41:05.051   875  4307 D NetworkMonitor/NetworkAgentInfo [WIFI () - 104]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.214.206,2a00:1450:400d:802::200e
,08-30 14:41:05.052  3953  4001 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-30 14:41:05.052  3953  4001 D io.jxcore.node.ConnectivityMonitor: start: OK
08-30 14:41:05.052  3953  4001 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-30 14:41:05.052  3953  4001 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@865af5 added. We now have 3 listener(s)
,08-30 14:41:05.053  3953  4001 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-30 14:41:05.053  3953  4001 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-30 14:41:05.053  3953  4001 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-30 14:41:05.053  3953  4001 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 14:41:05.053  3953  4001 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@769908a added. We now have 10 listener(s)
08-30 14:41:05.053  3953  4001 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 14:41:05.054  3953  4001 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 14:41:05.054  3953  4001 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 14:41:05.054  3953  4001 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 14:41:05.054  3953  4001 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 14:41:05.054  3953  4001 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-30 14:41:05.054  3953  4001 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 14:41:05.054  3953  4001 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-30 14:41:05.054  3953  4001 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5a74a7e removed from the list
08-30 14:41:05.054  3953  4001 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 14:41:05.054  3953  4001 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c614bdf removed from the list
08-30 14:41:05.054  3953  3953 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 14:41:05.054  3953  4001 D io.jxcore.node.ConnectivityMonitor: stop
08-30 14:41:05.054  3953  4001 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 14:41:05.055  3953  4001 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 14:41:05.055  3953  4001 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 14:41:05.055  3953  4001 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 14:41:05.055  3953  4001 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 14:41:05.055  3953  4001 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 14:41:05.055  3953  4001 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c614bdf not in the list
08-30 14:41:05.055  3953  4001 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 14:41:05.056  3953  4001 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 14:41:05.056  3953  3953 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 14:41:05.057  3953  4001 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 14:41:05.057  3953  4001 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 14:41:05.057  3953  4001 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 14:41:05.057  3953  4001 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@769908a removed from the list
08-30 14:41:05.057  3953  4001 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 14:41:05.057  3953  4001 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-30 14:41:05.057  3953  4001 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 14:41:05.057  3953  4001 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-30 14:41:05.057  3953  4001 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@865af5 removed from the list
,08-30 14:41:05.058  3953  4001 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
08-30 14:41:05.058  3953  4001 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
08-30 14:41:05.058  3953  4001 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
08-30 14:41:05.058  3953  4001 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-30 14:41:05.058  3953  4001 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
08-30 14:41:05.058  3953  4001 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-30 14:41:05.062  3953  4325 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 445, name: My test thread name)
08-30 14:41:05.062  3953  4325 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 445, thread name: My test thread name)
08-30 14:41:05.063  3953  4325 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 445, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,08-30 14:41:05.064  3953  4326 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 447, name: My test thread name)
,08-30 14:41:05.064  3953  4326 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 447, thread name: My test thread name)
08-30 14:41:05.064  3953  4326 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 447, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,08-30 14:41:05.066  3953  4001 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 80
,08-30 14:41:05.066  3953  4001 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 80
08-30 14:41:05.067  3953  4001 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
08-30 14:41:05.067  1744  4322 I MDM     : [191] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
08-30 14:41:05.067  3953  4001 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
08-30 14:41:05.067  1744  4322 W BaseAppContext: Using Auth Proxy for data requests.
08-30 14:41:05.067  3953  4001 D com.test.thalitest.ThaliTestRunner: Total duration: 21730 ms
,08-30 14:41:05.069  3953  4001 I jxcore-log: *Native tests were executed*
08-30 14:41:05.069  3953  4001 I jxcore-log: 
08-30 14:41:05.069  3953  4001 I jxcore-log: Total number of executed tests:  80
08-30 14:41:05.069  3953  4001 I jxcore-log: 
,08-30 14:41:05.069  3953  4001 I jxcore-log: Number of passed tests:  80
08-30 14:41:05.069  3953  4001 I jxcore-log: 
08-30 14:41:05.070  3953  4001 I jxcore-log: Number of failed tests:  0
08-30 14:41:05.070  3953  4001 I jxcore-log: 
,08-30 14:41:05.070  3953  4001 I jxcore-log: Number of ignored tests:  0
08-30 14:41:05.070  3953  4001 I jxcore-log: 
,08-30 14:41:05.071  3953  4001 I jxcore-log: Total duration:  21730
08-30 14:41:05.071  3953  4001 I jxcore-log: 
08-30 14:41:05.071  3953  4001 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
08-30 14:41:05.071  3953  4001 I jxcore-log: 
,08-30 14:41:05.075  3953  4001 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 14:41:05.075  3953  4001 I jxcore-log: 
,08-30 14:41:05.077  1744  4322 V GoogleAuthProtoRequest: [191] a.<init>: mAccountName set to: thalitester@gmail.com
,08-30 14:41:05.078  3953  4001 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 14:41:05.078  3953  4001 I jxcore-log: 
08-30 14:41:05.079   280   344 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0
08-30 14:41:05.079  3953  3953 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
08-30 14:41:05.079  3953  4001 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 14:41:05.079  3953  4001 I jxcore-log: 
08-30 14:41:05.080   280   280 D qdhwcomposer: hwc_setPowerMode: Done setting mode 0 on display 0
08-30 14:41:05.080   875  1334 D SurfaceControl: Excessive delay in setPowerMode(): 224ms
08-30 14:41:05.080  3953  4001 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 14:41:05.080  3953  4001 I jxcore-log: 
08-30 14:41:05.081  3953  4001 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 14:41:05.081  3953  4001 I jxcore-log: 
,08-30 14:41:05.081   875   895 I DreamManagerService: Entering dreamland.
,08-30 14:41:05.081   875   895 I PowerManagerService: Dozing...
08-30 14:41:05.082   875   890 I DreamController: Starting dream: name=ComponentInfo{com.android.systemui/com.android.systemui.doze.DozeService}, isTest=false, canDoze=true, userId=0
08-30 14:41:05.082  3953  4001 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 14:41:05.082  3953  4001 I jxcore-log: 
08-30 14:41:05.084  3953  4001 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-30 14:41:05.084  3953  4001 I jxcore-log: 
08-30 14:41:05.088  3953  4001 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 14:41:05.088  3953  4001 I jxcore-log: 
08-30 14:41:05.089  3953  4001 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-30 14:41:05.089  3953  4001 I jxcore-log: 
08-30 14:41:05.090  3953  4001 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-30 14:41:05.090  3953  4001 I jxcore-log: 
08-30 14:41:05.090  1540  1540 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
08-30 14:41:05.090  3953  4001 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-30 14:41:05.090  3953  4001 I jxcore-log: 
08-30 14:41:05.092  3953  4001 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-30 14:41:05.092  3953  4001 I jxcore-log: 
08-30 14:41:05.092  3953  4001 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-30 14:41:05.092  3953  4001 I jxcore-log: 
,08-30 14:41:05.093  3953  4001 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 14:41:05.093  3953  4001 I jxcore-log: 
,08-30 14:41:05.093  1540  1540 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-30 14:41:05.094  3953  4001 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 14:41:05.094  3953  4001 I jxcore-log: 
,08-30 14:41:05.094  3953  4001 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-30 14:41:05.094  3953  4001 I jxcore-log: 
,08-30 14:41:05.095  3953  4001 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-30 14:41:05.095  3953  4001 I jxcore-log: 
,08-30 14:41:05.095  1744  2424 I iu.UploadsManager: num updated entries: 0
,08-30 14:41:05.096  3953  4001 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-30 14:41:05.096  3953  4001 I jxcore-log: 
08-30 14:41:05.096  3953  4001 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-30 14:41:05.096  3953  4001 I jxcore-log: 
,08-30 14:41:05.097  3953  4001 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-30 14:41:05.097  3953  4001 I jxcore-log: 
08-30 14:41:05.097  3953  4001 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-30 14:41:05.097  3953  4001 I jxcore-log: 
08-30 14:41:05.098  3953  4001 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-30 14:41:05.098  3953  4001 I jxcore-log: 
08-30 14:41:05.098  3953  4001 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-30 14:41:05.098  3953  4001 I jxcore-log: 
08-30 14:41:05.099  3953  4001 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-30 14:41:05.099  3953  4001 I jxcore-log: 
08-30 14:41:05.100  3953  4001 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-30 14:41:05.100  3953  4001 I jxcore-log: 
,08-30 14:41:05.100  3953  4001 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-30 14:41:05.100  3953  4001 I jxcore-log: 
,08-30 14:41:05.101  3953  4001 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-30 14:41:05.101  3953  4001 I jxcore-log: 
08-30 14:41:05.102  3953  4001 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 14:41:05.102  3953  4001 I jxcore-log: 
08-30 14:41:05.102  3953  4001 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 14:41:05.102  3953  4001 I jxcore-log: 
08-30 14:41:05.103  3953  4001 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 14:41:05.103  3953  4001 I jxcore-log: 
08-30 14:41:05.103  3953  4001 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 14:41:05.103  3953  4001 I jxcore-log: 
08-30 14:41:05.110  1744  4319 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-30 14:41:05.111  1744  2424 I iu.SyncManager: NEXT; no task
,08-30 14:41:05.118  1744  4319 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,08-30 14:41:05.119  1744  4319 I SystemUpdateService: now status is 0 (complete)
08-30 14:41:05.119  1744  4319 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
,08-30 14:41:05.119  1744  4319 I SystemUpdateService: file has been verified
08-30 14:41:05.120  1744  4319 I SystemUpdateService: OTA package size = 12249756
,08-30 14:41:05.123  1744  4319 I SystemUpdateService: showing system update notification
,08-30 14:41:05.124   875  1309 D WifiConfigStore: Retrieve network priorities after PNO.
,08-30 14:41:05.125   379  1282 D audio_hw_primary: adev_set_parameters: enter: screen_state=on
,08-30 14:41:05.125   379  1282 D mot_vr_audio_hw: adev_set_parameters: screen_state=on
,08-30 14:41:05.129   875  1309 E native  : do suspend false
,08-30 14:41:05.130   875  4307 D NetworkMonitor/NetworkAgentInfo [WIFI () - 104]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 30 Aug 2016 12:41:05 GMT], X-Android-Received-Millis=[1472560865130], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1472560865105]}
,08-30 14:41:05.133   875  1311 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,08-30 14:41:05.133   875  1311 D ConnectivityService: NetworkAgentInfo [WIFI () - 104] validation  passed
,08-30 14:41:05.133   875  1311 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 104]
08-30 14:41:05.135   875  1311 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,08-30 14:41:05.137   875  1309 D WifiConfigStore: No blacklist allowed without epno enabled
,08-30 14:41:05.140  1915  4332 D NfcService: Discovery configuration equal, not updating.
,08-30 14:41:05.149  1540  2978 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
,08-30 14:41:05.149  1540  2978 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
,08-30 14:41:05.149  1540  2978 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-30 14:41:05.149  1540  2978 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
08-30 14:41:05.150   875  1309 D WifiConfigStore: Retrieve network priorities after PNO.
08-30 14:41:05.152   875  1309 E native  : do suspend true
,08-30 14:41:05.155  1744  1744 D SystemUpdateService: onDestroy
,08-30 14:41:05.164  1744  4322 E MDM     : [191] SitrepService.a: Error sending sitrep.
,08-30 14:41:05.227  3058  4324 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,08-30 14:41:05.258   379  1318 D audio_hw_primary: adev_set_parameters: enter: screen_state=off
,08-30 14:41:05.258   379  1318 D mot_vr_audio_hw: adev_set_parameters: screen_state=off
,08-30 14:41:05.452  3953  3953 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-30 14:41:05.455  3953  4001 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-30 14:41:05.455  3953  4001 I jxcore-log: 
,08-30 14:41:05.509  3953  3953 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-30 14:41:05.512  3953  4001 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-30 14:41:05.512  3953  4001 I jxcore-log: 
,08-30 14:41:05.544  3953  3953 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-30 14:41:05.547  3953  4001 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-30 14:41:05.547  3953  4001 I jxcore-log: 
,08-30 14:41:05.626   875  1309 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 16, 17 -> obsolete
,08-30 14:41:05.690  4334  4334 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,08-30 14:41:05.696  4334  4334 D AndroidRuntime: CheckJNI is OFF
,08-30 14:41:05.739  4334  4334 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,08-30 14:41:05.787  4334  4334 I Radio-JNI: register_android_hardware_Radio DONE
,08-30 14:41:05.810  4334  4334 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,08-30 14:41:05.820   875   888 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=-1: uninstall pkg
,08-30 14:41:05.822   875   888 I ActivityManager: Killing 3953:com.test.thalitest/u0a0 (adj 0): stop com.test.thalitest
,08-30 14:41:05.907   875  1997 D GraphicsStats: Buffer count: 2
08-30 14:41:05.907   875  1394 I WindowState: WIN DEATH: Window{4398fc9 u0 com.test.thalitest/com.test.thalitest.MainActivity}
08-30 14:41:05.907   875  1310 D WifiService: Client connection lost with reason: 4
,08-30 14:41:05.960   875   898 W PackageSettings: Skipping PackageSetting{6b6a32c com.example.hello/10273} due to missing metadata
,08-30 14:41:05.977   875  1311 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 103] cleared because we found a replacement network
,08-30 14:41:05.981   875   888 W ActivityManager: Failed trying to unstop package com.test.thalitest: java.lang.IllegalArgumentException: Unknown package: com.test.thalitest
,08-30 14:41:05.982   875   888 W PackageManager: Package com.test.thalitest is missing; assuming frozen
08-30 14:41:05.983   875   898 I art     : Starting a blocking GC Explicit
,08-30 14:41:05.989   875   888 E ActivityManager: Failure starting process com.test.thalitest
08-30 14:41:05.989   875   888 E ActivityManager: java.lang.RuntimeException: Package com.test.thalitest is frozen!
08-30 14:41:05.989   875   888 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3272)
08-30 14:41:05.989   875   888 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3231)
08-30 14:41:05.989   875   888 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3110)
08-30 14:41:05.989   875   888 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1395)
08-30 14:41:05.989   875   888 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:2007)
08-30 14:41:05.989   875   888 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1554)
08-30 14:41:05.989   875   888 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2735)
08-30 14:41:05.989   875   888 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2724)
08-30 14:41:05.989   875   888 E ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4592)
08-30 14:41:05.989   875   888 E ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:5949)
08-30 14:41:05.989   875   888 E ActivityManager: 	at com.android.server.am.ActivityManagerService.killPackageProcessesLocked(ActivityManagerService.java:5608)
08-30 14:41:05.989   875   888 E ActivityManager: 	at com.android.server.am.ActivityManagerService.forceStopPackageLocked(ActivityManagerService.java:5757)
08-30 14:41:05.989   875   888 E ActivityManager: 	at com.android.server.am.ActivityManagerService.-wrap1(ActivityManagerService.java)
08-30 14:41:05.989   875   888 E ActivityManager: 	at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:1730)
08-30 14:41:05.989   875   888 E ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 14:41:05.989   875   888 E ActivityManager: 	at android.os.Looper.loop(Looper.java:148)
08-30 14:41:05.989   875   888 E ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-30 14:41:05.989   875   888 E ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
08-30 14:41:05.990   875   888 I ActivityManager:   Force finishing activity ActivityRecord{da7ad96 u0 com.test.thalitest/.MainActivity t2}
,08-30 14:41:05.994   875  1997 W ActivityManager: Spurious death for ProcessRecord{5a0920e 0:com.test.thalitest/u0a0}, curProc for 3953: null
,08-30 14:41:06.010  1354  1354 W RecentsTaskLoader: Missing ActivityInfo for ComponentInfo{com.test.thalitest/com.test.thalitest.MainActivity} u=0
,08-30 14:41:06.048   875   898 I art     : Explicit concurrent mark sweep GC freed 32852(1985KB) AllocSpace objects, 3(60KB) LOS objects, 33% free, 29MB/43MB, paused 816us total 64.628ms
,08-30 14:41:06.073   875   898 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
08-30 14:41:06.075  4334  4334 I art     : System.exit called, status: 0
08-30 14:41:06.075  4334  4334 I AndroidRuntime: VM exiting with result code 0.
08-30 14:41:06.079   875   898 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=0: pkg removed
08-30 14:41:06.092   875   888 I ActivityManager: Exiting empty application process com.test.thalitest (null)
08-30 14:41:06.094  4251  4251 D BluetoothMapAppObserver: onReceive
08-30 14:41:06.094  4251  4251 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
08-30 14:41:06.098  3651  3651 D BuaReceiver: ====== got intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.motorola.android.buacontactadapter/.BuaReceiver (has extras) }
08-30 14:41:06.099   875  1299 I InputReader: Reconfiguring input devices.  changes=0x00000010
08-30 14:41:06.101  2134  2279 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
08-30 14:41:06.099  1864  1864 I Keyboard.Facilitator: resetDictionaries() : en_US
08-30 14:41:06.117   875  1944 I ActivityManager: Start proc 4350:android.process.acore/u0a5 for broadcast com.android.providers.contacts/.PackageIntentReceiver
08-30 14:41:06.119  1864  4349 I Keyboard.Facilitator.DecoderInitializer: run()
08-30 14:41:06.127  1864  4349 I Decoder : createOrResetDecoder
,08-30 14:41:06.155  1928  1928 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,08-30 14:41:06.162  1540  1540 I ConfigService: onCreate
,08-30 14:41:06.173  4350  4350 W System  : ClassLoader referenced unknown path: /system/priv-app/ContactsProvider/lib/arm
,08-30 14:41:06.182  1864  4349 I Keyboard.Facilitator.MainLanguageModelLoader: run()
,08-30 14:41:06.198   875  1997 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 3953 uid 10000
,08-30 14:41:06.200  1864  1864 I Keyboard.Facilitator: onFinishInput()
,08-30 14:41:06.216  1864  4349 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /data/user/0/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
,08-30 14:41:06.217   875   875 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
08-30 14:41:06.217  1864  4349 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
08-30 14:41:06.217  1864  4349 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
,08-30 14:41:06.222  1864  4349 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Contacts.dict
,08-30 14:41:06.223  1864  4349 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = history
,08-30 14:41:06.224  1864  4349 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loaded File = UserHistory.en_US.dict
,08-30 14:41:06.224  1864  4349 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = user
08-30 14:41:06.225  1864  4349 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Personal.en_US.dict
08-30 14:41:06.225  1864  4349 I Keyboard.Facilitator.PersonalDictionaryLoader: run() : Loaded (exit)
08-30 14:41:06.225  1864  4349 I Keyboard.Facilitator.Delight2FileSweeper: run()
08-30 14:41:06.225  1864  4349 I Keyboard.Facilitator.RecurringTaskScheduler: run()
,08-30 14:41:06.225  1864  4349 I StatsUtilsManager: startPeriodStatsRecorder() : Success
08-30 14:41:06.225  1864  4349 I PeriodicStatsRecorder: shouldRecordStats() = Too Soon
,08-30 14:41:06.245  1946  2039 E SQLiteLog: (3850) statement aborts at 23: [DELETE FROM icons WHERE componentName LIKE ? AND profileId = ?] disk I/O error
,08-30 14:41:06.247  4350  4350 W System  : ClassLoader referenced unknown path: /system/app/UserDictionaryProvider/lib/arm
,08-30 14:41:06.248   875   887 W AtomicFile: Couldn't rename file /data/system/users/0/runtime-permissions.xml to backup file /data/system/users/0/runtime-permissions.xml.bak
,08-30 14:41:06.249   875   887 E PackageManager: Failed to write settings, restoring backup
08-30 14:41:06.249   875   887 E PackageManager: java.io.IOException: Couldn't create directory /data/system/users/0/runtime-permissions.xml
08-30 14:41:06.249   875   887 E PackageManager: 	at android.util.AtomicFile.startWrite(AtomicFile.java:106)
08-30 14:41:06.249   875   887 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.writePermissionsSync(Settings.java:4615)
08-30 14:41:06.249   875   887 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.-wrap1(Settings.java)
08-30 14:41:06.249   875   887 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence$MyHandler.handleMessage(Settings.java:4830)
08-30 14:41:06.249   875   887 E PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 14:41:06.249   875   887 E PackageManager: 	at android.os.Looper.loop(Looper.java:148)
08-30 14:41:06.249   875   887 E PackageManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-30 14:41:06.255   875   888 E DropBoxManagerService: Can't write: system_server_wtf
08-30 14:41:06.255   875   888 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop15.tmp: open failed: EROFS (Read-only file system)
08-30 14:41:06.255   875   888 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-30 14:41:06.255   875   888 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-30 14:41:06.255   875   888 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-30 14:41:06.255   875   888 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-30 14:41:06.255   875   888 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-30 14:41:06.255   875   888 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-30 14:41:06.255   875   888 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12543)
08-30 14:41:06.255   875   888 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.handleApplicationWtfInner(ActivityManagerService.java:12356)
08-30 14:41:06.255   875   888 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:12328)
08-30 14:41:06.255   875   888 E DropBoxManagerService: 	at android.os.Handler.handleCallback(Handler.java:739)
08-30 14:41:06.255   875   888 E DropBoxManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-30 14:41:06.255   875   888 E DropBoxManagerService: 	at android.os.Looper.loop(Looper.java:148)
08-30 14:41:06.255   875   888 E DropBoxManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-30 14:41:06.255   875   888 E DropBoxManagerService: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
08-30 14:41:06.255   875   888 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-30 14:41:06.255   875   888 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-30 14:41:06.255   875   888 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-30 14:41:06.255   875   888 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-30 14:41:06.255   875   888 E DropBoxManagerService: 	... 13 more
,08-30 14:41:06.256  4350  4367 E SQLiteDatabase: Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
08-30 14:41:06.256  4350  4367 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 14:41:06.256  4350  4367 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-30 14:41:06.256  4350  4367 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-30 14:41:06.256  4350  4367 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-30 14:41:06.256  4350  4367 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-30 14:41:06.256  4350  4367 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-30 14:41:06.256  4350  4367 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-30 14:41:06.256  4350  4367 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-30 14:41:06.256  4350  4367 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-30 14:41:06.256  4350  4367 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-30 14:41:06.256  4350  4367 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-30 14:41:06.256  4350  4367 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-30 14:41:06.256  4350  4367 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-30 14:41:06.256  4350  4367 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-30 14:41:06.256  4350  4367 E SQLiteDatabase: 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
08-30 14:41:06.256  4350  4367 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1596)
08-30 14:41:06.256  4350  4367 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1687)
08-30 14:41:06.256  4350  4367 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
08-30 14:41:06.256  4350  4367 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 14:41:06.256  4350  4367 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-30 14:41:06.256  4350  4367 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-30 14:41:06.256  4350  4367 E SQLiteOpenHelper: Couldn't open contacts2.db for writing (will try read-only):
08-30 14:41:06.256  4350  4367 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 14:41:06.256  4350  4367 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-30 14:41:06.256  4350  4367 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-30 14:41:06.256  4350  4367 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-30 14:41:06.256  4350  4367 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-30 14:41:06.256  4350  4367 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-30 14:41:06.256  4350  4367 E SQLiteOpenHelper: ,	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-30 14:41:06.256  4350  4367 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-30 14:41:06.256  4350  4367 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-30 14:41:06.256  4350  4367 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-30 14:41:06.256  4350  4367 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-30 14:41:06.256  4350  4367 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-30 14:41:06.256  4350  4367 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-30 14:41:06.256  4350  4367 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-30 14:41:06.256  4350  4367 E SQLiteOpenHelper: 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
08-30 14:41:06.256  4350  4367 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1596)
08-30 14:41:06.256  4350  4367 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1687)
08-30 14:41:06.256  4350  4367 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
08-30 14:41:06.256  4350  4367 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 14:41:06.256  4350  4367 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:148)
08-30 14:41:06.256  4350  4367 E SQLiteOpenHelper: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-30 14:41:06.263   875   885 I ActivityManager: Start proc 4369:com.google.android.googlequicksearchbox:crash_report/u0a28 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
,--------- beginning of crash
08-30 14:41:06.264  1946  2039 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
08-30 14:41:06.264  1946  2039 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 1946
08-30 14:41:06.264  1946  2039 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-30 14:41:06.264  1946  2039 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-30 14:41:06.264  1946  2039 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-30 14:41:06.264  1946  2039 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-30 14:41:06.264  1946  2039 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-30 14:41:06.264  1946  2039 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
08-30 14:41:06.264  1946  2039 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
08-30 14:41:06.264  1946  2039 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
08-30 14:41:06.264  1946  2039 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
08-30 14:41:06.264  1946  2039 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-30 14:41:06.264  1946  2039 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-30 14:41:06.264  1946  2039 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-30 14:41:06.266   875  4379 E DropBoxManagerService: Can't write: system_app_crash
08-30 14:41:06.266   875  4379 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop134.tmp: open failed: EROFS (Read-only file system)
08-30 14:41:06.266   875  4379 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-30 14:41:06.266   875  4379 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-30 14:41:06.266   875  4379 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-30 14:41:06.266   875  4379 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-30 14:41:06.266   875  4379 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-30 14:41:06.266   875  4379 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-30 14:41:06.266   875  4379 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-30 14:41:06.266   875  4379 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-30 14:41:06.266   875  4379 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-30 14:41:06.266   875  4379 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-30 14:41:06.266   875  4379 E DropBoxManagerService: 	... 5 more
,08-30 14:41:06.267   875  1997 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,08-30 14:41:06.269  4350  4381 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,08-30 14:41:06.281   875  1378 I ActivityManager: Start proc 4384:com.android.musicfx/u0a18 for broadcast com.android.musicfx/.Compatibility$Receiver
,08-30 14:41:06.292   875  1335 W System.err: java.io.IOException: write failed: EBADF (Bad file descriptor)
,08-30 14:41:06.284  1946  2039 I Process : Sending signal. PID: 1946 SIG: 9
08-30 14:41:06.292   875  1335 W System.err: 	at libcore.io.IoBridge.write(IoBridge.java:498)
08-30 14:41:06.292   875  1335 W System.err: 	at java.io.FileOutputStream.write(FileOutputStream.java:186)
,08-30 14:41:06.292   875  1335 W System.err: 	at android.graphics.Bitmap.nativeCompress(Native Method)
08-30 14:41:06.292   875  1335 W System.err: 	at android.graphics.Bitmap.compress(Bitmap.java:1027)
08-30 14:41:06.292   875  1335 W System.err: 	at com.android.server.am.TaskPersister$LazyTaskWriterThread.run(TaskPersister.java:557)
,08-30 14:41:06.292   875  1335 W System.err: Caused by: android.system.ErrnoException: write failed: EBADF (Bad file descriptor)
08-30 14:41:06.293   875  1335 W System.err: 	at libcore.io.Posix.writeBytes(Native Method)
08-30 14:41:06.293   875  1335 W System.err: 	at libcore.io.Posix.write(Posix.java:271)
,08-30 14:41:06.293   875  1335 W System.err: 	at libcore.io.BlockGuardOs.write(BlockGuardOs.java:313)
08-30 14:41:06.293   875  1335 W System.err: 	at libcore.io.IoBridge.write(IoBridge.java:493)
08-30 14:41:06.293   875  1335 W System.err: 	... 4 more
,08-30 14:41:06.293   875  1335 D skia    : ------- write threw an exception
,08-30 14:41:06.356  4384  4384 W System  : ClassLoader referenced unknown path: /system/priv-app/MusicFX/lib/arm
,08-30 14:41:06.393   875  1298 W InputDispatcher: channel 'd66a3c2 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL (server)' ~ Consumer closed input channel or an error occurred.  events=0x9
,08-30 14:41:06.393   875  1298 E InputDispatcher: channel 'd66a3c2 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL (server)' ~ Channel is unrecoverably broken and will be disposed!
,08-30 14:41:06.395   875  1943 I WindowState: WIN DEATH: Window{d66a3c2 u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL}
08-30 14:41:06.395   875  1943 W InputDispatcher: Attempted to unregister already unregistered input channel 'd66a3c2 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL (server)'
,08-30 14:41:06.395   875   886 D GraphicsStats: Buffer count: 1
,08-30 14:41:06.408   875  1952 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 1946) has died
,08-30 14:41:06.409   875  1952 W ActivityManager: Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.reflection.ReflectionService in 1000ms
08-30 14:41:06.410   875  1952 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
,08-30 14:41:06.429  1540  1540 E SQLiteLog: (3850) statement aborts at 26: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
,08-30 14:41:06.430  1540  1540 D AndroidRuntime: Shutting down VM
,08-30 14:41:06.431  1540  1540 E AndroidRuntime: FATAL EXCEPTION: main
08-30 14:41:06.431  1540  1540 E AndroidRuntime: Process: com.google.process.gapps, PID: 1540
08-30 14:41:06.431  1540  1540 E AndroidRuntime: java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-30 14:41:06.431  1540  1540 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2732)
08-30 14:41:06.431  1540  1540 E AndroidRuntime: 	at android.app.ActivityThread.-wrap14(ActivityThread.java)
08-30 14:41:06.431  1540  1540 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1421)
08-30 14:41:06.431  1540  1540 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 14:41:06.431  1540  1540 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-30 14:41:06.431  1540  1540 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-30 14:41:06.431  1540  1540 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 14:41:06.431  1540  1540 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-30 14:41:06.431  1540  1540 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-30 14:41:06.431  1540  1540 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-30 14:41:06.431  1540  1540 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-30 14:41:06.431  1540  1540 E AndroidRuntime: ,	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-30 14:41:06.431  1540  1540 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-30 14:41:06.431  1540  1540 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-30 14:41:06.431  1540  1540 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
08-30 14:41:06.431  1540  1540 E AndroidRuntime: 	at com.google.android.gms.gcm.bg.a(SourceFile:310)
08-30 14:41:06.431  1540  1540 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
08-30 14:41:06.431  1540  1540 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
08-30 14:41:06.431  1540  1540 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2725)
08-30 14:41:06.431  1540  1540 E AndroidRuntime: 	... 8 more
,08-30 14:41:06.434  4350  4367 E SQLiteLog: (8) statement aborts at 43: [CREATE TABLE IF NOT EXISTS presence_db.presence (presence_data_id INTEGER PRIMARY KEY REFERENCES data(_id),protocol INTEGER NOT NULL,custom_protocol TEXT,im_handle TEXT,im_account TEXT
,08-30 14:41:06.438   875   888 I ActivityManager: Start proc 4402:com.google.android.googlequicksearchbox/u0a28 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,08-30 14:41:06.447   875  4411 E DropBoxManagerService: Can't write: system_app_crash
08-30 14:41:06.447   875  4411 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop135.tmp: open failed: EROFS (Read-only file system)
08-30 14:41:06.447   875  4411 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-30 14:41:06.447   875  4411 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-30 14:41:06.447   875  4411 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-30 14:41:06.447   875  4411 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-30 14:41:06.447   875  4411 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-30 14:41:06.447   875  4411 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-30 14:41:06.447   875  4411 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-30 14:41:06.447   875  4411 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-30 14:41:06.447   875  4411 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-30 14:41:06.447   875  4411 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-30 14:41:06.447   875  4411 E DropBoxManagerService: 	... 5 more
,08-30 14:41:06.449  1540  1540 I Process : Sending signal. PID: 1540 SIG: 9
,08-30 14:41:06.469  4350  4381 E SQLiteDatabase: Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
08-30 14:41:06.469  4350  4381 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 14:41:06.469  4350  4381 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-30 14:41:06.469  4350  4381 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-30 14:41:06.469  4350  4381 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-30 14:41:06.469  4350  4381 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-30 14:41:06.469  4350  4381 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-30 14:41:06.469  4350  4381 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-30 14:41:06.469  4350  4381 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-30 14:41:06.469  4350  4381 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-30 14:41:06.469  4350  4381 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-30 14:41:06.469  4350  4381 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-30 14:41:06.469  4350  4381 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-30 14:41:06.469  4350  4381 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-30 14:41:06.469  4350  4381 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-30 14:41:06.469  4350  4381 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:191)
08-30 14:41:06.469  4350  4381 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
08-30 14:41:06.469  4350  4381 E SQLiteDatabase: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
08-30 14:41:06.469  4350  4381 E SQLiteDatabase: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
08-30 14:41:06.469  4350  4381 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
08-30 14:41:06.469  4350  4381 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
08-30 14:41:06.469  4350  4381 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-30 14:41:06.469  4350  4381 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 14:41:06.469  4350  4381 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-30 14:41:06.469  4350  4381 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-30 14:41:06.469  4350  4381 E AndroidRuntime: FATAL EXCEPTION: IntentService[VoicemailCleanupService]
08-30 14:41:06.469  4350  4381 E AndroidRuntime: Process: android.process.acore, PID: 4350
08-30 14:41:06.469  4350  4381 E AndroidRuntime: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 14:41:06.469  4350  4381 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-30 14:41:06.469  4350  4381 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-30 14:41:06.469  4350  4381 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-30 14:41:06.469  4350  4381 E Andr,oidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-30 14:41:06.469  4350  4381 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-30 14:41:06.469  4350  4381 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-30 14:41:06.469  4350  4381 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-30 14:41:06.469  4350  4381 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-30 14:41:06.469  4350  4381 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-30 14:41:06.469  4350  4381 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-30 14:41:06.469  4350  4381 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-30 14:41:06.469  4350  4381 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-30 14:41:06.469  4350  4381 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-30 14:41:06.469  4350  4381 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:191)
08-30 14:41:06.469  4350  4381 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
08-30 14:41:06.469  4350  4381 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
08-30 14:41:06.469  4350  4381 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
08-30 14:41:06.469  4350  4381 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
08-30 14:41:06.469  4350  4381 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
08-30 14:41:06.469  4350  4381 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-30 14:41:06.469  4350  4381 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 14:41:06.469  4350  4381 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-30 14:41:06.469  4350  4381 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-30 14:41:06.471  4350  4367 I Process : Sending signal. PID: 4350 SIG: 9
08-30 14:41:06.472   875  4415 E DropBoxManagerService: Can't write: system_app_crash
08-30 14:41:06.472   875  4415 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop136.tmp: open failed: EROFS (Read-only file system)
08-30 14:41:06.472   875  4415 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-30 14:41:06.472   875  4415 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-30 14:41:06.472   875  4415 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-30 14:41:06.472   875  4415 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-30 14:41:06.472   875  4415 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-30 14:41:06.472   875  4415 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-30 14:41:06.472   875  4415 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-30 14:41:06.472   875  4415 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-30 14:41:06.472   875  4415 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-30 14:41:06.472   875  4415 E DropBoxManagerService: 	at, libcore.io.IoBridge.open(IoBridge.java:438)
08-30 14:41:06.472   875  4415 E DropBoxManagerService: 	... 5 more
08-30 14:41:06.500   875  1943 I ActivityManager: Process android.process.acore (pid 4350) has died
08-30 14:41:06.501   875  1943 W ActivityManager: Scheduling restart of crashed service com.android.providers.contacts/.VoicemailCleanupService in 1000ms
08-30 14:41:06.503  4402  4402 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.googlequicksearchbox/databases/launcher.db'.
08-30 14:41:06.503  4402  4402 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 14:41:06.503  4402  4402 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-30 14:41:06.503  4402  4402 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-30 14:41:06.503  4402  4402 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-30 14:41:06.503  4402  4402 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-30 14:41:06.503  4402  4402 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-30 14:41:06.503  4402  4402 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-30 14:41:06.503  4402  4402 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-30 14:41:06.503  4402  4402 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-30 14:41:06.503  4402  4402 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-30 14:41:06.503  4402  4402 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-30 14:41:06.503  4402  4402 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-30 14:41:06.503  4402  4402 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-30 14:41:06.503  4402  4402 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-30 14:41:06.503  4402  4402 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
08-30 14:41:06.503  4402  4402 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
08-30 14:41:06.503  4402  4402 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-30 14:41:06.503  4402  4402 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
08-30 14:41:06.503  4402  4402 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-30 14:41:06.503  4402  4402 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-30 14:41:06.503  4402  4402 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-30 14:41:06.503  4402  4402 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-30 14:41:06.503  4402  4402 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-30 14:41:06.503  4402  4402 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 14:41:06.503  4402  4402 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-30 14:41:06.503  4402  4402 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-30 14:41:06.503  4402  4402 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 14:41:06.503  4402  4402 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-30 14:41:06.503  4402  4402 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-30 14:41:06.503  4402  4402 D AndroidRuntime: Shutting down VM
,08-30 14:41:06.512  4402  4402 E AndroidRuntime: FATAL EXCEPTION: main
08-30 14:41:06.512  4402  4402 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 4402
08-30 14:41:06.512  4402  4402 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.android.launcher3.LauncherProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 14:41:06.512  4402  4402 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5156)
08-30 14:41:06.512  4402  4402 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-30 14:41:06.512  4402  4402 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-30 14:41:06.512  4402  4402 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-30 14:41:06.512  4402  4402 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-30 14:41:06.512  4402  4402 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 14:41:06.512  4402  4402 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-30 14:41:06.512  4402  4402 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-30 14:41:06.512  4402  4402 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 14:41:06.512  4402  4402 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-30 14:41:06.512  4402  4402 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-30 14:41:06.512  4402  4402 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 14:41:06.512  4402  4402 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-30 14:41:06.512  4402  4402 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-30 14:41:06.512  4402  4402 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-30 14:41:06.512  4402  4402 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-30 14:41:06.512  4402  4402 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-30 14:41:06.512  4402  4402 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-30 14:41:06.512  4402  4402 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-30 14:41:06.512  4402  4402 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-30 14:41:06.512  4402  4402 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-30 14:41:06.512  4402  4402 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-30 14:41:06.512  4402  4402 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-30 14:41:06.512  4402  4402 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-30 14:41:06.512  4402  4402 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-30 14:41:06.512  4402  4402 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
08-30 14:41:06.512  4402  4402 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
08-30 14:41:06.512  4402  4402 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-30 14:41:06.512  4402  4402 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
08-30 14:41:06.512  4402  4402 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-30 14:41:06.512  4402  4402 E AndroidRuntime: 	... 10 more
08-30 14:41:06.513   875  2086 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
08-30 14:41:06.514  4402  4402 I Process : Sending signal. PID: 4402 SIG: 9
08-30 14:41:06.514   875  4416 E DropBoxManagerService: Can't write: system_app_crash
08-30 14:41:06.514   875  4416 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop137.tmp: open failed: EROFS (Read-only file system)
08-30 14:41:06.514   875  4416 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-30 14:41:06.514   875  4416 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-30 14:41:06.514   875  4416 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-30 14:41:06.514   875  4416 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-30 14:41:06.514   875  4416 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-30 14:41:06.514   875  4416 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-30 14:41:06.514   875  4416 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-30 14:41:06.514   875  4416 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-30 14:41:06.514   875  4416 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-30 14:41:06.514   875  4416 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-30 14:41:06.514   875  4416 E DropBoxManagerService: 	... 5 more
08-30 14:41:06.523   875  1310 D WifiService: Client connection lost with reason: 4
08-30 14:41:06.525  1744  4400 E BulkCursor: Unable to get window because the remote process is dead
08-30 14:41:06.525  1744  4400 W BulkCursor: Remote process exception when closing
08-30 14:41:06.528   875  2086 I ActivityManager: Process com.google.process.gapps (pid 1540) has died
08-30 14:41:06.529   875  2086 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.config.ConfigService in 1000ms
08-30 14:41:06.529   875  2086 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.auth.GetToken in 10999ms
08-30 14:41:06.529   875  2086 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.gcm.GcmService in 20999ms
08-30 14:41:06.530   875  2086 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.clearcut.service.ClearcutLoggerService in 30999ms
08-30 14:41:06.530   875  2086 I ActivityManager: Killing 1744:com.google.android.gms/u0a11 (adj 5): depends on provider com.google.android.gsf/.gservices.GservicesProvider in dying proc com.google.process.gapps
,08-30 14:41:06.576   875   885 D ConnectivityService: ConnectivityService NetworkRequestInfo binderDied(NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], android.os.BinderProxy@9fd7030)
08-30 14:41:06.577   875  1311 D ConnectivityService: releasing NetworkRequest NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 14:41:06.578   875  1311 E ConnectivityService: RemoteException caught trying to send a callback msg for NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 14:41:06.587   875   888 W BroadcastQueue: Exception when sending broadcast to ComponentInfo{com.google.android.gms/com.google.android.gms.photos.autobackup.PhotosAppUninstalledReceiver}
08-30 14:41:06.587   875   888 W BroadcastQueue: android.os.DeadObjectException
08-30 14:41:06.587   875   888 W BroadcastQueue: 	at android.os.BinderProxy.transactNative(Native Method)
08-30 14:41:06.587   875   888 W BroadcastQueue: 	at android.os.BinderProxy.transact(Binder.java:503)
08-30 14:41:06.587   875   888 W BroadcastQueue: 	at android.app.ApplicationThreadProxy.scheduleReceiver(ApplicationThreadNative.java:891)
08-30 14:41:06.587   875   888 W BroadcastQueue: 	at com.android.server.am.BroadcastQueue.processCurBroadcastLocked(BroadcastQueue.java:273)
08-30 14:41:06.587   875   888 W BroadcastQueue: 	at com.android.server.am.BroadcastQueue.processNextBroadcast(BroadcastQueue.java:1039)
08-30 14:41:06.587   875   888 W BroadcastQueue: 	at com.android.server.am.BroadcastQueue$BroadcastHandler.handleMessage(BroadcastQueue.java:168)
08-30 14:41:06.587   875   888 W BroadcastQueue: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 14:41:06.587   875   888 W BroadcastQueue: 	at android.os.Looper.loop(Looper.java:148)
08-30 14:41:06.587   875   888 W BroadcastQueue: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-30 14:41:06.587   875   888 W BroadcastQueue: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
,08-30 14:41:06.587   875   888 W libprocessgroup: failed to open /acct/uid_10011/pid_1744/cgroup.procs: No such file or directory
,08-30 14:41:06.587   875   888 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.feedback.FeedbackService in 40941ms
08-30 14:41:06.587   875   888 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.analytics.service.AnalyticsService in 50941ms
08-30 14:41:06.587   875   888 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.feedback.FeedbackAsyncService in 60941ms
,08-30 14:41:06.602   875   888 I ActivityManager: Start proc 4418:com.google.android.gms/u0a11 for broadcast com.google.android.gms/.photos.autobackup.PhotosAppUninstalledReceiver
,08-30 14:41:06.605   875  1997 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 4402) has died
,08-30 14:41:06.606   875  1997 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
,08-30 14:41:06.615   280   344 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0

```
