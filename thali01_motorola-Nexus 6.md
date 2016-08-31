#### Test 82894682929afb6_thali01_motorola-Nexus 6 Logs


```
--------- beginning of main
08-31 08:51:43.076  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-31 08:51:43.090  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
08-31 08:51:43.101  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
08-31 08:51:43.130  1511  1522 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
08-31 08:51:43.130  1511  1522 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
08-31 08:51:43.130  1511  1522 I GLSUser : [GLSUser] Extracting token using key: Auth
08-31 08:51:43.130  1511  1522 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
08-31 08:51:43.151  3574  3574 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
08-31 08:51:43.151  3574  3574 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
08-31 08:51:43.152  3574  3574 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 3.
08-31 08:51:43.704  3859  3859 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
08-31 08:51:43.709  3859  3859 D AndroidRuntime: CheckJNI is OFF
08-31 08:51:43.745  3859  3859 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
08-31 08:51:43.789  3859  3859 I Radio-JNI: register_android_hardware_Radio DONE
08-31 08:51:43.813  3859  3859 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
08-31 08:51:43.817   872  1392 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-31 08:51:43.883  2060  2073 W SearchService: Abort, client detached.
08-31 08:51:43.890  3859  3859 D AndroidRuntime: Shutting down VM
08-31 08:51:43.893  2060  2060 I HotwordDetector: Closing mic
08-31 08:51:43.893  2060  2353 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@7e585de
08-31 08:51:43.893  2060  2366 E AudioRecord-JNI: Error -4 during AudioRecord native read
08-31 08:51:43.908   872  1881 I ActivityManager: Start proc 3868:com.test.thalitest/u0a0 for activity com.test.thalitest/.MainActivity
08-31 08:51:43.952   375  2368 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
08-31 08:51:43.955   375  2368 D audio_hw_primary: disable_snd_device: snd_device(61: voice-rec-mic)
08-31 08:51:43.964   375  1282 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
08-31 08:51:43.966  2060  2365 I MicroRecognitionRnrImpl: Detection finished
08-31 08:51:43.967  2060  2357 I MicroRecognitionRnrImpl: Stopping hotword detection.
08-31 08:51:44.011  3868  3868 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
08-31 08:51:44.038  3868  3868 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
08-31 08:51:44.058  3868  3868 I LibraryLoader: Time to load native libraries: 13 ms (timestamps 1004-1017)
08-31 08:51:44.058  3868  3868 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-31 08:51:44.078  3868  3868 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {1571e2}
08-31 08:51:44.079  3868  3868 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-31 08:51:44.079  3868  3868 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
08-31 08:51:44.084  3868  3868 I BrowserStartupController: Initializing chromium process, singleProcess=true
08-31 08:51:44.086  3868  3868 E SysUtils: ApplicationContext is null in ApplicationStatus
08-31 08:51:44.107  3868  3868 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
08-31 08:51:44.119  3868  3868 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-31 08:51:44.119  3868  3868 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-31 08:51:44.119  3868  3868 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-31 08:51:44.119  3868  3868 I Adreno  : Build Date                       : 10/20/15
08-31 08:51:44.119  3868  3868 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-31 08:51:44.119  3868  3868 I Adreno  : Local Branch                     : M14
08-31 08:51:44.119  3868  3868 I Adreno  : Remote Branch                    : 
08-31 08:51:44.119  3868  3868 I Adreno  : Remote Branch                    : 
08-31 08:51:44.119  3868  3868 I Adreno  : Reconstruct Branch               : 
,08-31 08:51:44.208   872   889 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@f85051:true
,08-31 08:51:44.242  3868  3868 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,08-31 08:51:44.255  3868  3868 D SystemWebViewEngine: CordovaWebView is running on device made by: motorola
,08-31 08:51:44.315  3868  3906 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,08-31 08:51:44.330  3868  3893 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,08-31 08:51:44.365  3868  3906 I OpenGLRenderer: Initialized EGL, version 1.4
,08-31 08:51:44.481   872   890 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +590ms
,08-31 08:51:44.486  1884  1884 I Keyboard.Facilitator: onFinishInput()
,08-31 08:51:44.591  3868  3868 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 3868
,08-31 08:51:44.756   872   883 I ActivityManager: Killing 3269:com.google.android.gm/u0a78 (adj 15): empty #17
,08-31 08:51:44.782  3868  3868 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-31 08:51:44.795   872   883 I ActivityManager: Killing 2990:com.google.android.calendar/u0a37 (adj 15): empty #18
,08-31 08:51:44.972  3868  3909 D jxcore_app_log: JniHelper::setJavaVM(0xb4d3c000), pthread_self() = -1696728784
,08-31 08:51:44.981  3868  3909 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-31 08:51:44.981  3868  3909 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-31 08:51:44.981  3868  3909 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-31 08:51:44.981  3868  3909 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-31 08:51:44.981  3868  3909 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,08-31 08:51:44.981  3868  3909 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3935a1 added. We now have 1 listener(s)
,08-31 08:51:44.986  3868  3909 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: F8:CF:C5:D9:E5:61
,08-31 08:51:44.987  3868  3909 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-31 08:51:44.988  3868  3909 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-31 08:51:44.988  3868  3909 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: ,
,08-31 08:51:44.992  3868  3909 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-31 08:51:44.992  3868  3909 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-31 08:51:44.992  3868  3909 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-31 08:51:44.992  3868  3909 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: F8:CF:C5:D9:E5:61
08-31 08:51:44.992  3868  3909 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-31 08:51:44.992  3868  3909 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-31 08:51:44.992  3868  3909 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-31 08:51:44.992  3868  3909 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-31 08:51:44.992  3868  3909 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-31 08:51:44.992  3868  3909 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-31 08:51:44.992  3868  3909 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-31 08:51:44.992  3868  3909 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-31 08:51:44.992  3868  3909 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-31 08:51:44.992  3868  3909 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,08-31 08:51:44.992  3868  3909 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2764eb4 added. We now have 1 listener(s)
08-31 08:51:44.992  3868  3909 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-31 08:51:45.001   872  1311 D WifiService: New client listening to asynchronous messages
,08-31 08:51:45.002  3868  3909 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-31 08:51:45.002  3868  3909 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
08-31 08:51:45.002  3868  3909 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-31 08:51:45.002  3868  3909 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
,08-31 08:51:45.002  3868  3909 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,08-31 08:51:45.005  3868  3909 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-31 08:51:45.005  3868  3909 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is F8:CF:C5:D9:E5:61
,08-31 08:51:45.010  3868  3909 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,08-31 08:51:45.010  3868  3909 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-31 08:51:45.010  3868  3909 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 08:51:45.010  3868  3909 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 08:51:45.010  3868  3909 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 08:51:45.010  3868  3909 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 08:51:45.010  3868  3909 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-31 08:51:45.010  3868  3909 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-31 08:51:45.010  3868  3909 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-31 08:51:45.010  3868  3909 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-31 08:51:45.011  3868  3909 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-31 08:51:45.011  3868  3909 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-31 08:51:45.012  3868  3868 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 08:51:45.014  3868  3868 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 08:51:45.228  3868  3868 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-31 08:51:45.587  3868  3877 I art     : Background sticky concurrent mark sweep GC freed 68417(6MB) AllocSpace objects, 18(1604KB) LOS objects, 30% free, 22MB/32MB, paused 719us total 107.882ms
,08-31 08:51:45.687   872  1310 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,08-31 08:51:46.352  3868  3918 W jxcore-log: Initializing JXcore engine
,08-31 08:51:46.352  3868  3918 W jxcore-log: JXcore engine is ready
,08-31 08:51:46.385  3918  3918 W Thread-333: type=1400 audit(0.0:4): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=8936 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,08-31 08:51:46.385  3918  3918 W Thread-333: type=1400 audit(0.0:5): avc: denied { ioctl } for path="socket:[11658]" dev="sockfs" ino=11658 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
08-31 08:51:46.385  3918  3918 W Thread-333: type=1400 audit(0.0:6): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
08-31 08:51:46.385  3918  3918 W Thread-333: type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[26904]" dev="sockfs" ino=26904 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,08-31 08:51:46.399  3868  3918 W jxcore-log: Starting JXcore engine
,08-31 08:51:46.476  3868  3918 W jxcore-log: Platform android
08-31 08:51:46.476  3868  3918 W jxcore-log: 
,08-31 08:51:46.476  3868  3918 W jxcore-log: Process ARCH arm
08-31 08:51:46.476  3868  3918 W jxcore-log: 
,08-31 08:51:46.664  3868  3918 I jxcore-log: JXcore Cordova bridge is ready!
08-31 08:51:46.664  3868  3918 I jxcore-log: 
,08-31 08:51:46.664  3868  3918 W jxcore-log: JXcore engine is started
,08-31 08:51:46.677  3868  3909 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,08-31 08:51:46.682  3868  3868 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-31 08:51:51.731   872  1859 D NetlinkSocketObserver: NeighborEvent{elapsedMs=128690, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-31 08:51:56.279  3868  3918 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-31 08:51:56.279  3868  3918 I jxcore-log: 
,08-31 08:51:56.281  3868  3918 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-31 08:51:56.281  3868  3918 I jxcore-log: 
,08-31 08:51:56.294  3868  3918 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-31 08:51:56.294  3868  3918 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 08:51:56.294  3868  3918 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 08:51:56.294  3868  3918 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 08:51:56.294  3868  3918 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 08:51:56.294  3868  3918 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-31 08:51:56.294  3868  3918 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-31 08:51:56.294  3868  3918 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-31 08:51:56.300  3868  3918 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-31 08:51:56.302  3868  3918 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-31 08:51:56.302  3868  3918 I jxcore-log: 
,08-31 08:51:56.304  3868  3918 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-31 08:51:56.304  3868  3918 I jxcore-log: 
,08-31 08:51:56.798  3868  3918 D executeNativeTests: Running unit tests
,08-31 08:51:56.860  3868  3918 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-31 08:51:56.861  3868  3918 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6366d16 added. We now have 2 listener(s)
08-31 08:51:56.862  3868  3918 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-31 08:51:56.862  3868  3918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-31 08:51:56.862  3868  3918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-31 08:51:56.862  3868  3918 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-31 08:51:56.862  3868  3918 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f6d5697 added. We now have 2 listener(s)
08-31 08:51:56.862  3868  3918 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-31 08:51:56.863  3868  3918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-31 08:51:56.870  3868  3918 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-31 08:51:56.884  3868  3918 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-31 08:51:56.884  3868  3918 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 08:51:56.884  3868  3918 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 08:51:56.884  3868  3918 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 08:51:56.884  3868  3918 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 08:51:56.884  3868  3918 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-31 08:51:56.884  3868  3918 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-31 08:51:56.884  3868  3918 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-31 08:51:56.886  3868  3918 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-31 08:51:56.886  3868  3918 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-31 08:51:56.888  3868  3918 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-31 08:51:56.889  3868  3918 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-31 08:51:56.889  3868  3918 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-31 08:51:56.891  3868  3918 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
,08-31 08:51:56.891  3868  3868 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 08:51:56.892  3868  3918 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-31 08:51:56.892  3868  3918 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-31 08:51:56.892  3868  3918 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-31 08:51:56.892  3868  3918 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-31 08:51:56.893  3868  3918 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 08:51:56.894  3868  3918 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 08:51:56.894  3868  3918 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 08:51:56.894  3868  3918 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 08:51:56.894  3868  3918 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 08:51:56.894  3868  3918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-31 08:51:56.894  3868  3918 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-31 08:51:56.894  3868  3918 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6366d16 removed from the list
08-31 08:51:56.894  3868  3918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 08:51:56.894  3868  3918 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f6d5697 removed from the list
08-31 08:51:56.896  3868  3868 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 08:51:56.896  3868  3918 D io.jxcore.node.ConnectivityMonitor: stop
08-31 08:51:56.896  3868  3918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 08:51:56.897  3868  3918 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 08:51:56.897  3868  3918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-31 08:51:56.898  3868  3918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-31 08:51:56.898  3868  3918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 08:51:56.898  3868  3918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 08:51:56.898  3868  3918 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f6d5697 not in the list
,08-31 08:51:56.900  3868  3918 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
,08-31 08:51:56.901  3868  3918 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 08:51:56.901  3868  3918 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 08:51:56.901  3868  3918 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 08:51:56.901  3868  3918 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 08:51:56.901  3868  3918 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-31 08:51:56.901  3868  3918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 08:51:56.901  3868  3918 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6366d16 not in the list
08-31 08:51:56.901  3868  3918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 08:51:56.901  3868  3918 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f6d5697 not in the list
08-31 08:51:56.902  3868  3918 D io.jxcore.node.ConnectivityMonitor: stop
08-31 08:51:56.902  3868  3918 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 08:51:56.902  3868  3918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 08:51:56.902  3868  3918 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 08:51:56.902  3868  3918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-31 08:51:56.903  3868  3918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-31 08:51:56.903  3868  3918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 08:51:56.903  3868  3918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 08:51:56.903  3868  3918 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f6d5697 not in the list
,08-31 08:51:56.909  3868  3918 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-31 08:51:56.909  3868  3918 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-31 08:51:56.909  3868  3918 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
,08-31 08:51:56.909  3868  3918 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-31 08:51:56.909  3868  3918 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-31 08:51:56.909  3868  3918 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-31 08:51:56.909  3868  3918 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-31 08:51:56.909  3868  3918 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-31 08:51:56.909  3868  3918 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-31 08:51:56.909  3868  3918 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-31 08:51:56.910  3868  3918 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-31 08:51:56.910  3868  3918 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-31 08:51:56.910  3868  3918 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-31 08:51:56.910  3868  3918 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
,08-31 08:51:56.910  3868  3918 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-31 08:51:56.910  3868  3918 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-31 08:51:56.910  3868  3918 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-31 08:51:56.910  3868  3918 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-31 08:51:56.910  3868  3918 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-31 08:51:56.910  3868  3918 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
,08-31 08:51:56.910  3868  3918 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-31 08:51:56.910  3868  3918 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-31 08:51:56.910  3868  3918 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-31 08:51:56.910  3868  3918 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-31 08:51:56.911  3868  3918 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-31 08:51:56.911  3868  3918 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-31 08:51:56.911  3868  3918 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-31 08:51:56.911  3868  3918 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-31 08:51:56.911  3868  3918 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-31 08:51:56.911  3868  3918 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-31 08:51:56.911  3868  3918 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-31 08:51:56.911  3868  3918 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-31 08:51:56.911  3868  3918 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 08:51:56.911  3868  3918 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 08:51:56.911  3868  3918 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 08:51:56.911  3868  3918 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 08:51:56.911  3868  3918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 08:51:56.912  3868  3918 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6366d16 not in the list
08-31 08:51:56.912  3868  3918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 08:51:56.912  3868  3918 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f6d5697 not in the list
08-31 08:51:56.912  3868  3918 D io.jxcore.node.ConnectivityMonitor: stop
08-31 08:51:56.912  3868  3918 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 08:51:56.912  3868  3918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 08:51:56.912  3868  3918 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-31 08:51:56.912  3868  3918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 08:51:56.913  3868  3918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 08:51:56.913  3868  3918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 08:51:56.913  3868  3918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 08:51:56.913  3868  3918 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f6d5697 not in the list
,08-31 08:51:56.914  3868  3918 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,08-31 08:51:56.916  3868  3918 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-31 08:51:56.920  3868  3918 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-31 08:51:56.920  3868  3918 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 08:51:56.920  3868  3918 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 08:51:56.920  3868  3918 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 08:51:56.920  3868  3918 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 08:51:56.920  3868  3918 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-31 08:51:56.920  3868  3918 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-31 08:51:56.920  3868  3918 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-31 08:51:56.922  3868  3918 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-31 08:51:56.922  3868  3918 D io.jxcore.node.ConnectivityMonitor: start: OK
08-31 08:51:56.922  3868  3918 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-31 08:51:56.924  3868  3918 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,08-31 08:51:56.924  3868  3918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-31 08:51:56.924  3868  3918 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-31 08:51:56.924  3868  3868 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 08:51:56.924  3868  3918 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-31 08:51:56.927  3868  3868 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 08:51:56.928  3868  3918 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,08-31 08:51:56.929  3868  3918 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-31 08:51:56.934  3868  3918 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-31 08:51:56.936  3868  3918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,08-31 08:51:56.936  3868  3918 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-31 08:51:56.938  3868  3918 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
,08-31 08:51:56.941  3868  3918 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
08-31 08:51:56.941  3868  3918 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-31 08:51:56.941  3868  3918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-31 08:51:56.942  3868  3918 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-31 08:51:56.942  3868  3918 D BluetoothAdapter: STATE_ON
,08-31 08:51:56.947  2714  2734 D BtGatt.GattService: registerClient() - UUID=f40f62ec-ecaf-48d3-8718-63fdd9a8992a
,08-31 08:51:56.948  2714  2765 D BtGatt.GattService: onClientRegistered() - UUID=f40f62ec-ecaf-48d3-8718-63fdd9a8992a, clientIf=5
,08-31 08:51:56.949  3868  3880 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,08-31 08:51:56.950  2714  2727 D BtGatt.GattService: start scan with filters
,08-31 08:51:56.954  3868  3918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-31 08:51:56.954  2714  2770 D BtGatt.ScanManager: handling starting scan
08-31 08:51:56.954  3868  3918 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-31 08:51:56.955  3868  3918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-31 08:51:56.955  3868  3918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
08-31 08:51:56.956  2714  2770 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4e6af5c
,08-31 08:51:56.958  3868  3918 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-31 08:51:56.958  3868  3868 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-31 08:51:56.959  3868  3918 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-31 08:51:56.962  3868  3918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-31 08:51:56.963  2714  2765 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,08-31 08:51:56.963  2714  2765 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-31 08:51:56.964  2714  2770 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-31 08:51:56.964  3868  3918 I io.jxcore.node.ConnectionHelper: start: OK
,08-31 08:51:56.967  3868  3918 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-31 08:51:56.967  3868  3918 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-31 08:51:56.967  3868  3918 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-31 08:51:56.967  3868  3918 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-31 08:51:56.967  3868  3918 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 08:51:56.967  3868  3918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-31 08:51:56.967  3868  3918 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-31 08:51:56.968  3868  3918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-31 08:51:56.968  3868  3918 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,08-31 08:51:56.968  3868  3918 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-31 08:51:56.968  3868  3918 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-31 08:51:56.968  3868  3918 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-31 08:51:56.969  3868  3918 D BluetoothAdapter: STATE_ON
08-31 08:51:56.969  2714  2765 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-31 08:51:56.969  2714  2765 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-31 08:51:56.969  2714  2734 D BtGatt.GattService: stopScan() - queue size =1
08-31 08:51:56.970  2714  2770 D BtGatt.ScanManager: Starting BLE batch scan
08-31 08:51:56.970  2714  2770 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-31 08:51:56.970  2714  2727 D BtGatt.GattService: unregisterClient() - clientIf=5
08-31 08:51:56.970  3868  3918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-31 08:51:56.970  3868  3918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-31 08:51:56.970  3868  3918 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-31 08:51:56.970  3868  3918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-31 08:51:56.970  3868  3918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-31 08:51:56.971  3868  3918 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-31 08:51:56.972  3868  3918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,08-31 08:51:56.972  3868  3918 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-31 08:51:56.972  3868  3918 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-31 08:51:56.972  3868  3918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-31 08:51:56.973  3868  3868 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-31 08:51:56.973  3868  3868 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-31 08:51:56.974  3868  3868 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-31 08:51:56.974  3868  3918 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 08:51:56.974  3868  3918 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 08:51:56.974  3868  3918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-31 08:51:56.974  3868  3918 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6366d16 not in the list
08-31 08:51:56.974  3868  3918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 08:51:56.974  3868  3918 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f6d5697 not in the list
08-31 08:51:56.974  3868  3918 D io.jxcore.node.ConnectivityMonitor: stop
,08-31 08:51:56.974  3868  3918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 08:51:56.975  3868  3918 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,08-31 08:51:56.976  3868  3918 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-31 08:51:56.979  2714  2765 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,08-31 08:51:56.979  2714  2765 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-31 08:51:56.981  3868  3918 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-31 08:51:56.981  3868  3918 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 08:51:56.981  3868  3918 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 08:51:56.981  3868  3918 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 08:51:56.981  3868  3918 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 08:51:56.981  3868  3918 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-31 08:51:56.981  3868  3918 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-31 08:51:56.981  3868  3918 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-31 08:51:56.982  3868  3918 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-31 08:51:56.982  3868  3918 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-31 08:51:56.982  3868  3918 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-31 08:51:56.982  3868  3918 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-31 08:51:56.982  3868  3918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-31 08:51:56.983  3868  3918 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-31 08:51:56.983  3868  3918 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-31 08:51:56.984  3868  3868 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 08:51:56.984  2714  2765 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-31 08:51:56.984  2714  2765 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-31 08:51:56.986  3868  3918 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-31 08:51:56.986  3868  3918 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-31 08:51:56.986  3868  3868 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 08:51:56.989  3868  3918 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-31 08:51:56.989  3868  3918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-31 08:51:56.989  3868  3918 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-31 08:51:56.991  2714  2765 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-31 08:51:56.991  2714  2765 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-31 08:51:56.991  2714  2770 D BtGatt.ScanManager: stopping BLe Batch
,08-31 08:51:56.993  3868  3918 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-31 08:51:56.993  3868  3918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-31 08:51:56.993  3868  3918 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-31 08:51:56.994  3868  3918 D BluetoothAdapter: STATE_ON
,08-31 08:51:56.996  2714  2900 D BtGatt.GattService: registerClient() - UUID=923f587e-1512-4aaa-bbf4-afb15cacf6d6
,08-31 08:51:56.996  2714  2765 D BtGatt.GattService: onClientRegistered() - UUID=923f587e-1512-4aaa-bbf4-afb15cacf6d6, clientIf=5
,08-31 08:51:56.999  3868  3879 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-31 08:51:56.999  2714  2765 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-31 08:51:56.999  2714  2765 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-31 08:51:56.999  2714  2920 D BtGatt.GattService: start scan with filters
08-31 08:51:56.999  2714  2770 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-31 08:51:57.001  3868  3918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-31 08:51:57.001  3868  3918 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-31 08:51:57.001  3868  3918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-31 08:51:57.001  3868  3918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-31 08:51:57.004  3868  3918 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-31 08:51:57.004  2714  2765 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-31 08:51:57.004  2714  2765 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-31 08:51:57.005  3868  3868 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-31 08:51:57.005  3868  3918 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-31 08:51:57.006  3868  3918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-31 08:51:57.007  2714  2770 D BtGatt.ScanManager: handling starting scan
,08-31 08:51:57.009  3868  3918 I io.jxcore.node.ConnectionHelper: start: OK
,08-31 08:51:57.011  3868  3918 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-31 08:51:57.011  3868  3918 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-31 08:51:57.011  3868  3918 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-31 08:51:57.011  3868  3918 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,08-31 08:51:57.011  3868  3918 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 08:51:57.012  3868  3918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-31 08:51:57.012  3868  3918 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-31 08:51:57.012  3868  3918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-31 08:51:57.012  3868  3918 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,08-31 08:51:57.012  3868  3918 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-31 08:51:57.012  3868  3918 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-31 08:51:57.012  3868  3918 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-31 08:51:57.013  3868  3918 D BluetoothAdapter: STATE_ON
08-31 08:51:57.013  2714  2765 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-31 08:51:57.013  2714  2765 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-31 08:51:57.013  2714  2920 D BtGatt.GattService: stopScan() - queue size =1
,08-31 08:51:57.013  2714  2770 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
08-31 08:51:57.014  2714  2727 D BtGatt.GattService: unregisterClient() - clientIf=5
08-31 08:51:57.014  3868  3918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-31 08:51:57.014  3868  3918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-31 08:51:57.014  3868  3918 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-31 08:51:57.014  3868  3918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-31 08:51:57.014  3868  3918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-31 08:51:57.015  3868  3918 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-31 08:51:57.015  3868  3918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-31 08:51:57.015  3868  3918 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-31 08:51:57.015  3868  3918 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-31 08:51:57.016  3868  3918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-31 08:51:57.017  3868  3868 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-31 08:51:57.017  3868  3868 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-31 08:51:57.017  3868  3868 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-31 08:51:57.017  3868  3918 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 08:51:57.017  3868  3918 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 08:51:57.017  3868  3918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-31 08:51:57.018  3868  3918 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6366d16 not in the list
08-31 08:51:57.018  3868  3918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 08:51:57.018  3868  3918 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f6d5697 not in the list
,08-31 08:51:57.018  3868  3918 D io.jxcore.node.ConnectivityMonitor: stop
08-31 08:51:57.018  3868  3918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 08:51:57.018  3868  3918 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 08:51:57.018  3868  3918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 08:51:57.018  2714  2765 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,08-31 08:51:57.019  2714  2765 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-31 08:51:57.019  2714  2770 D BtGatt.ScanManager: Starting BLE batch scan
08-31 08:51:57.019  2714  2770 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-31 08:51:57.019  3868  3918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 08:51:57.019  3868  3918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 08:51:57.019  3868  3918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 08:51:57.020  3868  3918 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f6d5697 not in the list
08-31 08:51:57.020  3868  3918 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,08-31 08:51:57.022  3868  3918 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-31 08:51:57.028  3868  3918 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-31 08:51:57.028  3868  3918 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 08:51:57.028  3868  3918 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 08:51:57.028  3868  3918 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 08:51:57.028  3868  3918 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 08:51:57.028  3868  3918 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-31 08:51:57.028  3868  3918 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-31 08:51:57.028  3868  3918 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-31 08:51:57.028  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-31 08:51:57.030  2714  2765 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-31 08:51:57.030  2714  2765 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-31 08:51:57.031  3868  3918 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-31 08:51:57.032  3868  3918 D io.jxcore.node.ConnectivityMonitor: start: OK
08-31 08:51:57.032  3868  3918 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-31 08:51:57.032  3868  3918 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-31 08:51:57.032  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
08-31 08:51:57.032  3868  3918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,08-31 08:51:57.032  3868  3918 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-31 08:51:57.032  3868  3918 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-31 08:51:57.036  2714  2765 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,08-31 08:51:57.036  2714  2765 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-31 08:51:57.037  3868  3918 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-31 08:51:57.037  3868  3918 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-31 08:51:57.037  3868  3868 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 08:51:57.040  3868  3868 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 08:51:57.043  2714  2765 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,08-31 08:51:57.043  2714  2765 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-31 08:51:57.044  2714  2770 D BtGatt.ScanManager: stopping BLe Batch
08-31 08:51:57.044  3868  3918 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-31 08:51:57.045  3868  3918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-31 08:51:57.046  3868  3918 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-31 08:51:57.049  2714  2765 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,08-31 08:51:57.049  2714  2765 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-31 08:51:57.049  2714  2770 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-31 08:51:57.051  3868  3918 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-31 08:51:57.051  3868  3918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-31 08:51:57.051  3868  3918 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-31 08:51:57.052  3868  3918 D BluetoothAdapter: STATE_ON
,08-31 08:51:57.054  2714  2765 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-31 08:51:57.055  2714  2765 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-31 08:51:57.055  2714  2727 D BtGatt.GattService: registerClient() - UUID=694f3c53-7b1e-4db1-abb7-db660cdfde1c
08-31 08:51:57.055  2714  2765 D BtGatt.GattService: onClientRegistered() - UUID=694f3c53-7b1e-4db1-abb7-db660cdfde1c, clientIf=5
,08-31 08:51:57.055  3868  3880 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-31 08:51:57.056  2714  2734 D BtGatt.GattService: start scan with filters
,08-31 08:51:57.059  3868  3918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-31 08:51:57.059  2714  2770 D BtGatt.ScanManager: handling starting scan
08-31 08:51:57.059  3868  3918 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,08-31 08:51:57.060  3868  3918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-31 08:51:57.060  3868  3918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
08-31 08:51:57.062  3868  3918 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-31 08:51:57.062  3868  3868 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-31 08:51:57.063  3868  3918 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-31 08:51:57.064  1511  1523 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
08-31 08:51:57.064  1511  1523 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
,08-31 08:51:57.064  1511  1523 I GLSUser : [GLSUser] Extracting token using key: Auth
08-31 08:51:57.064  1511  1523 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-31 08:51:57.065  2714  2765 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,08-31 08:51:57.065  2714  2765 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-31 08:51:57.065  2714  2770 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
08-31 08:51:57.065  3868  3918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-31 08:51:57.068  3868  3918 I io.jxcore.node.ConnectionHelper: start: OK
,08-31 08:51:57.068  3868  3918 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 08:51:57.068  3868  3918 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-31 08:51:57.068  3868  3918 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-31 08:51:57.069  3868  3918 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,08-31 08:51:57.069  3868  3918 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 08:51:57.069  3868  3918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-31 08:51:57.069  3868  3918 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-31 08:51:57.069  3868  3918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-31 08:51:57.069  3868  3918 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,08-31 08:51:57.069  3868  3918 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-31 08:51:57.069  3868  3918 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,08-31 08:51:57.069  3868  3918 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-31 08:51:57.070  3868  3918 D BluetoothAdapter: STATE_ON
,08-31 08:51:57.073  2714  2734 D BtGatt.GattService: stopScan() - queue size =1
08-31 08:51:57.074  2714  2765 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-31 08:51:57.074  2714  2765 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-31 08:51:57.074  2714  2770 D BtGatt.ScanManager: Starting BLE batch scan
08-31 08:51:57.074  2714  2770 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-31 08:51:57.074  2714  2900 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-31 08:51:57.075  3868  3918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-31 08:51:57.075  3868  3918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-31 08:51:57.075  3868  3918 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-31 08:51:57.075  3868  3918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-31 08:51:57.075  3868  3918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-31 08:51:57.076  3868  3918 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-31 08:51:57.076  3868  3918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-31 08:51:57.076  3868  3918 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,08-31 08:51:57.076  3868  3918 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-31 08:51:57.076  3868  3918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-31 08:51:57.077  3868  3868 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-31 08:51:57.077  3868  3918 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-31 08:51:57.077  3868  3918 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-31 08:51:57.077  3868  3868 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-31 08:51:57.077  3868  3918 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 08:51:57.077  3868  3918 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 08:51:57.077  3868  3868 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-31 08:51:57.077  3868  3918 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-31 08:51:57.077  3868  3918 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 08:51:57.078  3868  3918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-31 08:51:57.078  3868  3918 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6366d16 not in the list
08-31 08:51:57.078  3868  3918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-31 08:51:57.078  3868  3918 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f6d5697 not in the list
08-31 08:51:57.078  3868  3918 D io.jxcore.node.ConnectivityMonitor: stop
08-31 08:51:57.078  3868  3918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 08:51:57.078  3868  3918 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-31 08:51:57.078  3868  3918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 08:51:57.081  3868  3918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 08:51:57.081  3868  3918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 08:51:57.082  3868  3918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-31 08:51:57.082  3868  3918 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f6d5697 not in the list
,08-31 08:51:57.085  3868  3918 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
,08-31 08:51:57.086  3868  3918 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections,
,08-31 08:51:57.086  3868  3918 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-31 08:51:57.086  3868  3918 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-31 08:51:57.086  3868  3918 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 08:51:57.086  3868  3918 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 08:51:57.086  3868  3918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 08:51:57.086  3868  3918 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6366d16 not in the list
08-31 08:51:57.086  3868  3918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 08:51:57.086  3868  3918 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f6d5697 not in the list
08-31 08:51:57.086  2714  2765 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-31 08:51:57.086  2714  2765 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-31 08:51:57.087  3868  3918 D io.jxcore.node.ConnectivityMonitor: stop
08-31 08:51:57.087  3868  3918 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 08:51:57.087  3868  3918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 08:51:57.087  3868  3918 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 08:51:57.087  3868  3918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 08:51:57.087  3868  3918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 08:51:57.087  3868  3918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 08:51:57.088  3868  3918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 08:51:57.088  3868  3918 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f6d5697 not in the list
,08-31 08:51:57.088  3868  3918 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-31 08:51:57.088  3868  3918 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 08:51:57.088  3015  3929 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
08-31 08:51:57.088  3015  3929 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-31 08:51:57.088  3015  3929 E HttpOperation: 	at jdm.a(PG:82)
08-31 08:51:57.088  3015  3929 E HttpOperation: 	at jcs.o(PG:406)
08-31 08:51:57.088  3015  3929 E HttpOperation: 	at jcn.a(PG:1379)
08-31 08:51:57.088  3015  3929 E HttpOperation: 	at jcs.i(PG:143)
08-31 08:51:57.088  3015  3929 E HttpOperation: 	at blb.a(PG:3937)
08-31 08:51:57.088  3015  3929 E HttpOperation: 	at czp.a(PG:18188)
08-31 08:51:57.088  3015  3929 E HttpOperation: 	at czp.a(PG:9081)
08-31 08:51:57.088  3015  3929 E HttpOperation: 	at czq.run(PG:1686)
08-31 08:51:57.088  3015  3929 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-31 08:51:57.088  3015  3929 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-31 08:51:57.088  3015  3929 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-31 08:51:57.088  3015  3929 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-31 08:51:57.088  3015  3929 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-31 08:51:57.088  3015  3929 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-31 08:51:57.088  3015  3929 E HttpOperation: 	at jdj.a(PG:4091)
08-31 08:51:57.088  3015  3929 E HttpOperation: 	at jdj.a(PG:1125)
08-31 08:51:57.088  3015  3929 E HttpOperation: 	at jdm.a(PG:77)
08-31 08:51:57.088  3015  3929 E HttpOperation: 	... 12 more
08-31 08:51:57.088  3015  3929 E HttpOperation: Caused by: faj: BadAuthentication
08-31 08:51:57.088  3015  3929 E HttpOperation: 	at fal.a(PG:38)
08-31 08:51:57.088  3015  3929 E HttpOperation: 	at jdj.a(PG:4089)
08-31 08:51:57.088  3015  3929 E HttpOperation: 	... 14 more
08-31 08:51:57.088  3868  3918 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 08:51:57.089  3868  3918 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 08:51:57.089  3868  3918 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 08:51:57.089  3868  3918 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-31 08:51:57.089  3868  3918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 08:51:57.089  3868  3918 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6366d16 not in the list
08-31 08:51:57.089  3868  3918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 08:51:57.089  3868  3918 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f6d5697 not in the list
08-31 08:51:57.089  3868  3918 D io.jxcore.node.ConnectivityMonitor: stop
08-31 08:51:57.089  3868  3918 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-31 08:51:57.089  3868  3918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 08:51:57.089  3868  3918 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 08:51:57.089  3868  3918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 08:51:57.090  3868  3918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 08:51:57.090  3868  3918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 08:51:57.090  3868  3918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 08:51:57.090  3868  3918 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f6d5697 not in the list
,08-31 08:51:57.091  3868  3918 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
08-31 08:51:57.091  3868  3918 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-31 08:51:57.091  3868  3918 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 08:51:57.091  3868  3918 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 08:51:57.092  3868  3918 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-31 08:51:57.092  3868  3918 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 08:51:57.092  3868  3918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 08:51:57.092  2714  2765 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-31 08:51:57.092  2714  2765 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-31 08:51:57.092  3868  3918 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6366d16 not in the list
08-31 08:51:57.093  3868  3918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 08:51:57.093  3868  3918 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f6d5697 not in the list
08-31 08:51:57.093  3868  3918 D io.jxcore.node.ConnectivityMonitor: stop
,08-31 08:51:57.093  3868  3918 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 08:51:57.093  3868  3918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 08:51:57.094  3868  3918 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 08:51:57.094  3868  3918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 08:51:57.095  3868  3918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 08:51:57.095  3868  3918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 08:51:57.095  3868  3918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-31 08:51:57.095  3868  3918 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f6d5697 not in the list
08-31 08:51:57.095  3868  3918 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
08-31 08:51:57.095  3868  3918 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 08:51:57.096  3868  3918 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 08:51:57.096  3868  3918 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-31 08:51:57.096  3868  3918 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 08:51:57.096  3868  3918 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 08:51:57.096  3868  3918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 08:51:57.097  3868  3918 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6366d16 not in the list
,08-31 08:51:57.097  3868  3918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 08:51:57.097  3868  3918 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f6d5697 not in the list
08-31 08:51:57.097  3868  3918 D io.jxcore.node.ConnectivityMonitor: stop
08-31 08:51:57.097  3868  3918 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 08:51:57.097  3868  3918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-31 08:51:57.097  3868  3918 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 08:51:57.097  3868  3918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 08:51:57.098  3868  3918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 08:51:57.098  3868  3918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 08:51:57.098  3868  3918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 08:51:57.098  3868  3918 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f6d5697 not in the list
08-31 08:51:57.098  3868  3918 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,08-31 08:51:57.099  2714  2765 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-31 08:51:57.099  2714  2765 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-31 08:51:57.099  2714  2770 D BtGatt.ScanManager: stopping BLe Batch
08-31 08:51:57.100  3868  3918 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-31 08:51:57.100  3868  3918 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-31 08:51:57.100  3868  3918 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-31 08:51:57.101  3868  3918 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-31 08:51:57.102  3868  3918 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-31 08:51:57.102  3868  3918 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 08:51:57.102  3868  3918 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 08:51:57.103  3868  3918 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 08:51:57.103  3868  3918 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 08:51:57.104  3868  3918 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 08:51:57.104  3868  3918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 08:51:57.105  3868  3918 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6366d16 not in the list
,08-31 08:51:57.105  3868  3918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 08:51:57.106  3868  3918 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f6d5697 not in the list
08-31 08:51:57.106  3868  3918 D io.jxcore.node.ConnectivityMonitor: stop
08-31 08:51:57.106  3868  3918 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 08:51:57.106  3868  3918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 08:51:57.106  3868  3918 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-31 08:51:57.106  3868  3918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 08:51:57.106  2714  2765 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-31 08:51:57.107  2714  2765 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-31 08:51:57.107  2714  2770 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-31 08:51:57.110  3868  3918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 08:51:57.110  3868  3918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 08:51:57.110  3868  3918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 08:51:57.110  3868  3918 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f6d5697 not in the list
08-31 08:51:57.113  2714  2765 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-31 08:51:57.113  2714  2765 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-31 08:51:57.113  3868  3918 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-31 08:51:57.114  3868  3918 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
08-31 08:51:57.114  3868  3918 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-31 08:51:57.116  3868  3918 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,08-31 08:51:57.116  3868  3918 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
08-31 08:51:57.116  3868  3918 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-31 08:51:57.116  3868  3918 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-31 08:51:57.116  3868  3918 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-31 08:51:57.116  3868  3918 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
,08-31 08:51:57.116  3868  3918 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-31 08:51:57.116  3868  3918 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-31 08:51:57.117  3868  3918 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-31 08:51:57.117  3868  3918 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
,08-31 08:51:57.117  3868  3918 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-31 08:51:57.117  3868  3918 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-31 08:51:57.117  3868  3918 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-31 08:51:57.117  3868  3918 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-31 08:51:57.117  3868  3918 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-31 08:51:57.117  3868  3918 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-31 08:51:57.117  3868  3918 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-31 08:51:57.117  3868  3918 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-31 08:51:57.117  3868  3918 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-31 08:51:57.117  3868  3918 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-31 08:51:57.117  3868  3918 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-31 08:51:57.117  3868  3918 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-31 08:51:57.117  3868  3918 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-31 08:51:57.117  3868  3918 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-31 08:51:57.117  3868  3918 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-31 08:51:57.117  3868  3918 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-31 08:51:57.117  3868  3918 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-31 08:51:57.117  3868  3918 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-31 08:51:57.117  3868  3918 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-31 08:51:57.118  3868  3918 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
,08-31 08:51:57.118  3868  3918 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-31 08:51:57.118  3868  3918 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-31 08:51:57.118  3868  3918 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
08-31 08:51:57.118  3868  3918 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-31 08:51:57.118  3868  3918 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
08-31 08:51:57.118  3868  3918 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-31 08:51:57.118  3868  3918 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-31 08:51:57.118  3868  3918 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
08-31 08:51:57.118  3868  3918 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-31 08:51:57.118  3868  3918 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-31 08:51:57.118  3868  3918 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
08-31 08:51:57.121  3868  3918 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
08-31 08:51:57.122  3868  3918 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
08-31 08:51:57.122  3868  3918 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
08-31 08:51:57.123  3868  3918 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
08-31 08:51:57.123  3868  3918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
08-31 08:51:57.123  3868  3918 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
08-31 08:51:57.123  3868  3918 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-31 08:51:57.123  3868  3918 E io.jxcore.node.ConnectionHelper: connect: Callback is null
08-31 08:51:57.123  3868  3930 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 397)
08-31 08:51:57.123  1511  2005 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
08-31 08:51:57.123  1511  2005 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-31 08:51:57.123  1511  2005 I GLSUser : [GLSUser] Extracting token using key: Auth
08-31 08:51:57.124  1511  2005 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
08-31 08:51:57.124  3868  3918 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 08:51:57.124  3868  3918 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 08:51:57.124  3868  3918 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 08:51:57.124  3868  3918 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 08:51:57.124  3868  3918 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 08:51:57.124  3868  3918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 08:51:57.124  3868  3918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
08-31 08:51:57.125  3868  3918 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6366d16 not in the list
08-31 08:51:57.125  3868  3918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 08:51:57.125  3868  3918 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f6d5697 not in the list
08-31 08:51:57.125  3868  3918 D io.jxcore.node.ConnectivityMonitor: stop
08-31 08:51:57.125  3868  3918 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 08:51:57.125  3868  3918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 08:51:57.125  3868  3918 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 08:51:57.125  3868  3918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 08:51:57.126  3868  3930 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-31 08:51:57.126  3868  3918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 08:51:57.126  3868  3918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 08:51:57.126  3868  3918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 08:51:57.126  3868  3918 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f6d5697 not in the list
08-31 08:51:57.127  3868  3918 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
08-31 08:51:57.127  3868  3918 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 08:51:57.127  3868  3918 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 08:51:57.127  3868  3918 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 08:51:57.127  3868  3918 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 08:51:57.129  3868  3918 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 08:51:57.129  3868  3918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 08:51:57.129  3868  3918 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6366d16 not in the list
08-31 08:51:57.129  3868  3931 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 397
08-31 08:51:57.129  3868  3918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 08:51:57.129  3868  3931 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Trying to close the Bluetooth socket... (thread ID: 397)
08-31 08:51:57.129  3868  3918 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f6d5697 not in the list
08-31 08:51:57.129  3868  3918 D io.jxcore.node.ConnectivityMonitor: stop
08-31 08:51:57.129  3868  3931 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Bluetooth socket closed (thread ID: 397)
08-31 08:51:57.130  3868  3930 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 397)
08-31 08:51:57.129  3868  3918 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 08:51:57.130  3868  3918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 08:51:57.130  3868  3918 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 08:51:57.130  3868  3918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 08:51:57.130  2714  2897 E bt_btif_sock_rfcomm: btsock_rfc_signaled socket signaled for read while disconnected, slot: 4, channel: -1
08-31 08:51:57.133  3868  3918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 08:51:57.133  3868  3918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 08:51:57.134  3868  3918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 08:51:57.134  3868  3918 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f6d5697 not in the list
08-31 08:51:57.134  3868  3918 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
08-31 08:51:57.134  3868  3918 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 08:51:57.134  3868  3918 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 08:51:57.135  3868  3918 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 08:51:57.135  3868  3918 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 08:51:57.135  3868  3918 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 08:51:57.135  3868  3918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 08:51:57.135  3868  3918 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6366d16 not in the list
08-31 08:51:57.135  3868  3918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 08:51:57.135  3868  3918 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f6d5697 not in the list
08-31 08:51:57.135  3868  3918 D io.jxcore.node.ConnectivityMonitor: stop
08-31 08:51:57.135  3868  3918 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 08:51:57.135  3868  3918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 08:51:57.135  3868  3918 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 08:51:57.135  3868  3918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 08:51:57.136  3868  3918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 08:51:57.136  3868  3918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 08:51:57.136  3868  3918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 08:51:57.136  3868  3918 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f6d5697 not in the list
08-31 08:51:57.137  3868  3918 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
08-31 08:51:57.137  3868  3918 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
08-31 08:51:57.137  3868  3918 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-31 08:51:57.137  3868  3918 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
08-31 08:51:57.137  3868  3918 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-31 08:51:57.137  3868  3918 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
08-31 08:51:57.137  3868  3918 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-31 08:51:57.137  3868  3918 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
08-31 08:51:57.137  3868  3918 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-31 08:51:57.138  3868  3918 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
08-31 08:51:57.138  3868  3918 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-31 08:51:57.138  3868  3918 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
08-31 08:51:57.138  3868  3918 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 08:51:57.138  3868  3918 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 08:51:57.138  3868  3918 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 08:51:57.138  3868  3918 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 08:51:57.138  3868  3918 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 08:51:57.138  3868  3918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 08:51:57.138  3868  3918 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6366d16 not in the list
08-31 08:51:57.138  3868  3918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 08:51:57.138  3868  3918 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f6d5697 not in the list
08-31 08:51:57.138  3868  3918 D io.jxcore.node.ConnectivityMonitor: stop
08-31 08:51:57.138  3868  3918 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 08:51:57.138  3868  3918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 08:51:57.142  3868  3918 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 08:51:57.142  3868  3918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 08:51:57.143  3868  3918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 08:51:57.143  3868  3918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 08:51:57.143  3868  3918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 08:51:57.143  3868  3918 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f6d5697 not in the list
08-31 08:51:57.143  3868  3918 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 08:51:57.143  3868  3918 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 08:51:57.144  3868  3918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 08:51:57.144  3868  3918 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6366d16 not in the list
08-31 08:51:57.144  3868  3918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 08:51:57.144  3868  3918 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f6d5697 not in the list
08-31 08:51:57.144  3868  3918 D io.jxcore.node.ConnectivityMonitor: stop
08-31 08:51:57.144  3868  3918 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 08:51:57.144  3868  3918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 08:51:57.144  3868  3918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 08:51:57.144  3868  3918 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f6d5697 not in the list
08-31 08:51:57.144  3868  3918 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 08:51:57.144  3868  3918 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 08:51:57.144  3868  3918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-31 08:51:57.144  3868  3918 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6366d16 not in the list
08-31 08:51:57.144  3868  3918 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 08:51:57.145  3868  3918 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 08:51:57.145  3868  3918 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 08:51:57.145  3868  3918 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 08:51:57.145  3868  3918 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 08:51:57.145  3868  3918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 08:51:57.145  3868  3918 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6366d16 not in the list
08-31 08:51:57.145  3868  3918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 08:51:57.145  3868  3918 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f6d5697 not in the list
08-31 08:51:57.145  3868  3918 D io.jxcore.node.ConnectivityMonitor: stop
08-31 08:51:57.145  3868  3918 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 08:51:57.145  3868  3918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 08:51:57.145  3868  3918 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 08:51:57.145  3868  3918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 08:51:57.146  3868  3918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 08:51:57.146  3868  3918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 08:51:57.146  3868  3918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 08:51:57.146  3015  3929 E HttpOperation: [getmobileexperiments] Unexpected exception
08-31 08:51:57.146  3015  3929 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-31 08:51:57.146  3015  3929 E HttpOperation: 	at jdm.a(PG:82)
08-31 08:51:57.146  3015  3929 E HttpOperation: 	at jcs.o(PG:406)
08-31 08:51:57.146  3015  3929 E HttpOperation: 	at jcn.a(PG:1379)
08-31 08:51:57.146  3015  3929 E HttpOperation: 	at jcs.i(PG:143)
08-31 08:51:57.146  3015  3929 E HttpOperation: 	at hec.a(PG:42)
08-31 08:51:57.146  3015  3929 E HttpOperation: 	at hee.a(PG:102)
08-31 08:51:57.146  3015  3929 E HttpOperation: 	at czr.a(PG:65)
08-31 08:51:57.146  3015  3929 E HttpOperation: 	at kka.a(PG:108)
08-31 08:51:57.146  3015  3929 E HttpOperation: 	at czp.a(PG:19176)
08-31 08:51:57.146  3015  3929 E HttpOperation: 	at czp.a(PG:9081)
08-31 08:51:57.146  3015  3929 E HttpOperation: 	at czq.run(PG:1686)
08-31 08:51:57.146  3015  3929 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-31 08:51:57.146  3015  3929 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-31 08:51:57.146  3015  3929 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-31 08:51:57.146  3015  3929 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-31 08:51:57.146  3015  3929 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-31 08:51:57.146  3015  3929 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-31 08:51:57.146  3015  3929 E HttpOperation: 	at jdj.a(PG:4091)
08-31 08:51:57.146  3015  3929 E HttpOperation: 	at jdj.a(PG:1125)
08-31 08:51:57.146  3015  3929 E HttpOperation: 	at jdm.a(PG:77)
08-31 08:51:57.146  3015  3929 E HttpOperation: 	... 15 more
08-31 08:51:57.146  3015  3929 E HttpOperation: Caused by: faj: BadAuthentication
08-31 08:51:57.146  3015  3929 E HttpOperation: 	at fal.a(PG:38)
08-31 08:51:57.146  3015  3929 E HttpOperation: 	at jdj.a(PG:4089)
08-31 08:51:57.146  3015  3929 E HttpOperation: 	... 17 more
08-31 08:51:57.146  3868  3918 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f6d5697 not in the list
08-31 08:51:57.147  3015  3929 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
08-31 08:51:57.147  3015  3929 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
08-31 08:51:57.147  3015  3929 E ExperimentLoader: 	at jdm.a(PG:82)
08-31 08:51:57.147  3015  3929 E ExperimentLoader: 	at jcs.o(PG:406)
08-31 08:51:57.147  3015  3929 E ExperimentLoader: 	at jcn.a(PG:1379)
08-31 08:51:57.147  3015  3929 E ExperimentLoader: 	at jcs.i(PG:143)
08-31 08:51:57.147  3015  3929 E ExperimentLoader: 	at hec.a(PG:42)
08-31 08:51:57.147  3015  3929 E ExperimentLoader: 	at hee.a(PG:102)
08-31 08:51:57.147  3015  3929 E ExperimentLoader: 	at czr.a(PG:65)
08-31 08:51:57.147  3015  3929 E ExperimentLoader: 	at kka.a(PG:108)
08-31 08:51:57.147  3015  3929 E ExperimentLoader: 	at czp.a(PG:19176)
08-31 08:51:57.147  3015  3929 E ExperimentLoader: 	at czp.a(PG:9081)
08-31 08:51:57.147  3015  3929 E ExperimentLoader: 	at czq.run(PG:1686)
08-31 08:51:57.147  3015  3929 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-31 08:51:57.147  3015  3929 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-31 08:51:57.147  3015  3929 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-31 08:51:57.147  3015  3929 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-31 08:51:57.147  3015  3929 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
08-31 08:51:57.147  3015  3929 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-31 08:51:57.147  3015  3929 E ExperimentLoader: 	at jdj.a(PG:4091)
08-31 08:51:57.147  3015  3929 E ExperimentLoader: 	at jdj.a(PG:1125)
08-31 08:51:57.147  3015  3929 E ExperimentLoader: 	at jdm.a(PG:77)
08-31 08:51:57.147  3015  3929 E ExperimentLoader: 	... 15 more
08-31 08:51:57.147  3015  3929 E ExperimentLoader: Caused by: faj: BadAuthentication
08-31 08:51:57.147  3015  3929 E ExperimentLoader: 	at fal.a(PG:38)
08-31 08:51:57.147  3015  3929 E ExperimentLoader: 	at jdj.a(PG:4089)
08-31 08:51:57.147  3015  3929 E ExperimentLoader: 	... 17 more
08-31 08:51:57.147  3868  3918 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
08-31 08:51:57.147  3868  3918 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-31 08:51:57.148  3868  3918 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
08-31 08:51:57.149  3868  3918 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
08-31 08:51:57.149  3868  3918 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
08-31 08:51:57.149  3868  3918 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
08-31 08:51:57.149  3868  3868 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
08-31 08:51:57.149  3868  3918 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-31 08:51:57.149  3868  3918 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 08:51:57.149  3868  3918 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
08-31 08:51:57.150  3868  3918 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
08-31 08:51:57.150  3868  3918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
08-31 08:51:57.150  3868  3918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 08:51:57.150  3868  3918 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
08-31 08:51:57.150  3868  3868 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
08-31 08:51:57.150  3868  3918 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6366d16 not in the list
08-31 08:51:57.150  3868  3918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 08:51:57.150  3868  3918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-31 08:51:57.150  3868  3918 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-31 08:51:57.150  3868  3918 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-31 08:51:57.150  3868  3918 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 08:51:57.150  3868  3918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 08:51:57.151  3868  3918 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-31 08:51:57.151  3868  3918 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f6d5697 not in the list
08-31 08:51:57.151  3868  3868 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-31 08:51:57.151  3868  3868 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-31 08:51:57.151  3868  3918 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 08:51:57.151  3868  3868 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-31 08:51:57.151  3868  3918 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 08:51:57.151  3868  3918 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 08:51:57.152  3868  3918 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 08:51:57.152  3868  3918 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 08:51:57.152  3868  3918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 08:51:57.152  3868  3918 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6366d16 not in the l,ist
08-31 08:51:57.152  3868  3918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 08:51:57.152  3868  3918 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f6d5697 not in the list
08-31 08:51:57.152  3868  3918 D io.jxcore.node.ConnectivityMonitor: stop
08-31 08:51:57.152  3868  3918 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 08:51:57.152  3868  3918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 08:51:57.152  3868  3918 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 08:51:57.152  3868  3918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 08:51:57.153  3868  3918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 08:51:57.153  3868  3918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 08:51:57.153  3868  3918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 08:51:57.153  3868  3918 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f6d5697 not in the list
08-31 08:51:57.154  3868  3918 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
08-31 08:51:57.155  3868  3918 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-31 08:51:57.155  3868  3918 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-31 08:51:57.155  3868  3918 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-31 08:51:57.155  3868  3918 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 08:51:57.155  3868  3918 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 08:51:57.155  3868  3918 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 08:51:57.155  3868  3918 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 08:51:57.155  3868  3918 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 08:51:57.155  3868  3918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 08:51:57.155  3868  3918 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6366d16 not in the list
08-31 08:51:57.155  3868  3918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 08:51:57.156  3868  3918 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f6d5697 not in the list
08-31 08:51:57.156  3868  3918 D io.jxcore.node.ConnectivityMonitor: stop
,08-31 08:51:57.156  3868  3918 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-31 08:51:57.156  3868  3918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 08:51:57.156  3868  3918 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 08:51:57.156  3868  3918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 08:51:57.156  3868  3933 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
08-31 08:51:57.157  3868  3933 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
08-31 08:51:57.157  3868  3868 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,08-31 08:51:57.158  3868  3918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 08:51:57.158  3868  3918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-31 08:51:57.158  3868  3918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 08:51:57.158  3868  3918 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f6d5697 not in the list
08-31 08:51:57.162  3868  3918 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 08:51:57.162  3868  3918 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 08:51:57.162  3868  3918 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 08:51:57.162  3868  3918 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-31 08:51:57.162  3868  3918 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 08:51:57.162  3868  3918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 08:51:57.163  3868  3918 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6366d16 not in the list
08-31 08:51:57.163  3868  3918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 08:51:57.163  3868  3918 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f6d5697 not in the list
,08-31 08:51:57.163  3868  3918 D io.jxcore.node.ConnectivityMonitor: stop
08-31 08:51:57.163  3868  3918 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 08:51:57.163  3868  3918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-31 08:51:57.163  3868  3918 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 08:51:57.163  3868  3918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 08:51:57.164  3868  3918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 08:51:57.164  3868  3918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 08:51:57.164  3868  3918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-31 08:51:57.164  3868  3918 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f6d5697 not in the list
08-31 08:51:57.165  3868  3918 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 08:51:57.165  3868  3918 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 08:51:57.165  3868  3918 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 08:51:57.165  3868  3918 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 08:51:57.166  3868  3918 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 08:51:57.166  3868  3918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 08:51:57.166  3868  3918 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6366d16 not in the list
,08-31 08:51:57.166  3868  3918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 08:51:57.166  3868  3918 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f6d5697 not in the list
08-31 08:51:57.166  3868  3918 D io.jxcore.node.ConnectivityMonitor: stop
08-31 08:51:57.166  3868  3918 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-31 08:51:57.166  3868  3918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 08:51:57.166  3868  3918 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 08:51:57.166  3868  3918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 08:51:57.167  3868  3918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 08:51:57.167  3868  3918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 08:51:57.167  3868  3918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 08:51:57.167  3868  3918 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f6d5697 not in the list
,08-31 08:51:57.168  3868  3918 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
08-31 08:51:57.168  3868  3918 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-31 08:51:57.168  3868  3918 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
08-31 08:51:57.168  3868  3918 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-31 08:51:57.168  3868  3918 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
08-31 08:51:57.168  3868  3918 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-31 08:51:57.170  3868  3918 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-31 08:51:57.170  3868  3918 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
08-31 08:51:57.171  3868  3918 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
08-31 08:51:57.171  3868  3918 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-31 08:51:57.171  3868  3918 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
08-31 08:51:57.171  3868  3918 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
,08-31 08:51:57.171  3868  3918 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
,08-31 08:51:57.171  3868  3918 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
08-31 08:51:57.172  3868  3918 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
,08-31 08:51:57.172  3868  3918 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
,08-31 08:51:57.172  3868  3918 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
08-31 08:51:57.172  3868  3918 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
08-31 08:51:57.172  3868  3918 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
08-31 08:51:57.173  3868  3918 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
08-31 08:51:57.174  3868  3918 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-31 08:51:57.174  3868  3918 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@496b9a1 added. We now have 2 listener(s)
08-31 08:51:57.174  3868  3918 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-31 08:51:57.175  3868  3918 D BluetoothAdapter: enable(): BT is already enabled..!
08-31 08:51:57.176   872  1393 D WifiService: setWifiEnabled: true pid=3868, uid=10000
08-31 08:51:57.176   872  1393 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-31 08:51:57.177  3868  3918 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-31 08:51:57.177  3868  3918 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@44247c6 added. We now have 3 listener(s)
08-31 08:51:57.177  3868  3918 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-31 08:51:57.181  3868  3918 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-31 08:51:57.181  3868  3918 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@b3b1387 added. We now have 4 listener(s)
08-31 08:51:57.181  3868  3918 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-31 08:51:57.182  3868  3918 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-31 08:51:57.182  3868  3918 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@984a2b4 added. We now have 5 listener(s)
08-31 08:51:57.182  3868  3918 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-31 08:51:57.183   872  1994 D WifiService: setWifiEnabled: false pid=3868, uid=10000
08-31 08:51:57.183   872  1994 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-31 08:51:57.189  3868  3918 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-31 08:51:57.189  2714  2761 D BluetoothAdapterState: Current state: ON, message: 23
08-31 08:51:57.189  2714  2761 D BluetoothAdapterProperties: Setting state to 13
,08-31 08:51:57.189  2714  2761 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-31 08:51:57.190  2714  2761 D BluetoothAdapterProperties: onBluetoothDisable()
08-31 08:51:57.191  2714  2714 D BluetoothMapService: onReceive
08-31 08:51:57.191  2714  2714 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-31 08:51:57.192  2714  2714 D BluetoothMapService: STATE_TURNING_OFF
08-31 08:51:57.192  2714  2714 D BluetoothMapService: MAP Service closeService in
,08-31 08:51:57.192  2714  2714 D BluetoothMapMasInstance0: MAP Service shutdown
08-31 08:51:57.192  2714  2714 D ObexServerSockets0: shutdown(block = true)
08-31 08:51:57.192  2714  2714 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-31 08:51:57.192  2714  2921 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
,08-31 08:51:57.192  2714  2714 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-31 08:51:57.192  2714  2897 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
08-31 08:51:57.193  2714  2922 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
08-31 08:51:57.196  3868  3918 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 08:51:57.196  3868  3918 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-31 08:51:57.196  3868  3918 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 08:51:57.196  3868  3918 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 08:51:57.196  3868  3918 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 08:51:57.196  3868  3918 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-31 08:51:57.196  3868  3918 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-31 08:51:57.196  3868  3918 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-31 08:51:57.196  3868  3918 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-31 08:51:57.197  2714  2761 I BluetoothAdapterState: Entering PendingCommandState
08-31 08:51:57.197  2714  2714 I BtOppRfcommListener: stopping Accept Thread
,08-31 08:51:57.198  2714  3490 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-31 08:51:57.198  2714  3490 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-31 08:51:57.198  3868  3918 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 08:51:57.198  3868  3918 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-31 08:51:57.198  3868  3918 D io.jxcore.node.ConnectivityMonitor: start: OK
08-31 08:51:57.200  3868  3868 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 08:51:57.203  3868  3868 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 08:51:57.204  1460  1460 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-31 08:51:57.205  3868  3868 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 08:51:57.205  3868  3868 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 08:51:57.205  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 08:51:57.205  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 08:51:57.205  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 08:51:57.205  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-31 08:51:57.205  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-31 08:51:57.205  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-31 08:51:57.205  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-31 08:51:57.206   872  1310 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,08-31 08:51:57.206   872  1310 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
08-31 08:51:57.206   872  1310 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-31 08:51:57.206   872  1310 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-31 08:51:57.206  3868  3868 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 08:51:57.206  3868  3868 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-31 08:51:57.208  3868  3868 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 08:51:57.213   371   870 D CommandListener: Clearing all IP addresses on wlan0
08-31 08:51:57.213   872  1861 D DhcpClient: Clearing IP address
08-31 08:51:57.216  1511  2442 V NativeCrypto: Read error: ssl=0xab4bf200: I/O error during system call, Connection timed out
08-31 08:51:57.218  1511  2442 V NativeCrypto: SSL shutdown failed: ssl=0xab4bf200: I/O error during system call, Broken pipe
08-31 08:51:57.218   371   870 D CommandListener: Setting iface cfg
,08-31 08:51:57.220   872  1881 D ConnectivityService: reportNetworkConnectivity(100, false) by 10011
08-31 08:51:57.221   872  1857 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Forcing reevaluation for UID 10011
08-31 08:51:57.222   872   885 I ActivityManager: Start proc 3936:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
08-31 08:51:57.222  2714  2765 D BluetoothAdapterProperties: Scan Mode:20
08-31 08:51:57.222  2714  2761 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
,08-31 08:51:57.223   872  1310 D WifiStateMachine: Start Disconnecting Watchdog 1
08-31 08:51:57.224   872  1310 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-31 08:51:57.224   872  1312 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
,08-31 08:51:57.225  2714  2714 D HeadsetService: Received stop request...Stopping profile...
08-31 08:51:57.227   371   870 D CommandListener: Clearing all IP addresses on wlan0
08-31 08:51:57.230   872  1312 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
08-31 08:51:57.231   446   446 E Parcel  : Reading a NULL string not supported here.
08-31 08:51:57.231  3868  3868 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 08:51:57.231  3868  3868 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 08:51:57.231  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 08:51:57.231  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 08:51:57.231  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 08:51:57.231  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-31 08:51:57.231  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 08:51:57.231  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 08:51:57.231  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-31 08:51:57.231  3868  3868 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 08:51:57.233  3868  3868 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-31 08:51:57.234   872  1312 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
08-31 08:51:57.236  1355  1377 D BluetoothHeadset: Proxy object disconnected
08-31 08:51:57.237  3868  3868 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-31 08:51:57.237  3868  3868 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 08:51:57.237  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 08:51:57.237  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 08:51:57.237  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 08:51:57.237  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-31 08:51:57.237  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 08:51:57.237  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 08:51:57.237  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-31 08:51:57.237  2714  2714 D A2dpService: Received stop request...Stopping profile...
08-31 08:51:57.237  2714  2903 D A2dpStateMachine: Exit Disconnected: -1
08-31 08:51:57.237   872   872 D BluetoothHeadset: Proxy object disconnected
,08-31 08:51:57.237   872   872 D BluetoothHeadset: Proxy object disconnected
08-31 08:51:57.237   872   872 D BluetoothHeadset: Proxy object disconnected
08-31 08:51:57.237  1971  1986 D BluetoothHeadset: Proxy object disconnected
08-31 08:51:57.238  3868  3868 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 08:51:57.238  3868  3868 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-31 08:51:57.238  1355  1355 D HeadsetProfile: Bluetooth service disconnected
08-31 08:51:57.241  2714  2714 V BluetoothAdapterState: isTurningOff()=true
,08-31 08:51:57.241  2714  2714 V BluetoothAdapterState: isTurningOn()=false
08-31 08:51:57.241  2714  2714 V BluetoothAdapterState: isBleTurningOn()=false
08-31 08:51:57.241  2714  2714 V BluetoothAdapterState: isBleTurningOff()=false
08-31 08:51:57.241  1355  1355 D BluetoothA2dp: Proxy object disconnected
08-31 08:51:57.241   872   872 D BluetoothA2dp: Proxy object disconnected
,08-31 08:51:57.242  2714  2714 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-31 08:51:57.242  2714  2765 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
08-31 08:51:57.242  2714  2714 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-31 08:51:57.242  2714  2893 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-31 08:51:57.242  2714  2893 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-31 08:51:57.242  2714  2893 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-31 08:51:57.243  2714  2765 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
08-31 08:51:57.243  2714  2714 D HidService: Received stop request...Stopping profile...
08-31 08:51:57.243  2714  2714 D HidService: Stopping Bluetooth HidService
08-31 08:51:57.243  1355  1355 D BluetoothInputDevice: Proxy object disconnected
08-31 08:51:57.243  1355  1355 D HidProfile: Bluetooth service disconnected
,08-31 08:51:57.244  2714  2714 D HealthService: Received stop request...Stopping profile...
08-31 08:51:57.245  2714  2714 D PanService: Received stop request...Stopping profile...
08-31 08:51:57.247  1355  1355 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-31 08:51:57.247  1355  1355 D PanProfile: Bluetooth service disconnected
08-31 08:51:57.248  2714  2714 V BluetoothAdapterState: isTurningOff()=true
08-31 08:51:57.248  2714  2714 V BluetoothAdapterState: isTurningOn()=false
08-31 08:51:57.248  2714  2714 V BluetoothAdapterState: isBleTurningOn()=false
08-31 08:51:57.248  2714  2714 V BluetoothAdapterState: isBleTurningOff()=false
,08-31 08:51:57.249  2714  2893 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-31 08:51:57.249  2714  2893 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-31 08:51:57.249  2714  2893 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-31 08:51:57.249  2714  2893 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-31 08:51:57.249  2714  2893 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-31 08:51:57.249  2714  2893 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,08-31 08:51:57.249  2714  2765 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
08-31 08:51:57.250  2714  2714 D BluetoothMapService: Received stop request...Stopping profile...
08-31 08:51:57.250  2714  2714 D BluetoothMapService: stop()
08-31 08:51:57.251   872  1310 D WifiConfigStore: Retrieve network priorities after PNO.
08-31 08:51:57.254  2714  2714 D BluetoothMapAppObserver: deinitObservers()
08-31 08:51:57.254  3868  3868 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 08:51:57.254  2714  2714 D BluetoothMapAppObserver: removeReceiver()
,08-31 08:51:57.254  3868  3868 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 08:51:57.254  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 08:51:57.254  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 08:51:57.254  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-31 08:51:57.254  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-31 08:51:57.254  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 08:51:57.254  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 08:51:57.254  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-31 08:51:57.255  3868  3868 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 08:51:57.255  3868  3868 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-31 08:51:57.256  1355  1355 D BluetoothMap: Proxy object disconnected
08-31 08:51:57.256  1355  1355 D MapProfile: Bluetooth service disconnected
08-31 08:51:57.256  2714  2714 V BluetoothAdapterState: isTurningOff()=true
08-31 08:51:57.256  2714  2714 V BluetoothAdapterState: isTurningOn()=false
08-31 08:51:57.256  2714  2714 V BluetoothAdapterState: isBleTurningOn()=false
,08-31 08:51:57.256  2714  2714 V BluetoothAdapterState: isBleTurningOff()=false
08-31 08:51:57.256  2714  2714 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-31 08:51:57.256  2714  2714 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-31 08:51:57.257  2714  2714 V BluetoothAdapterState: isTurningOff()=true
08-31 08:51:57.257  2714  2714 V BluetoothAdapterState: isTurningOn()=false
08-31 08:51:57.257  2714  2714 V BluetoothAdapterState: isBleTurningOn()=false
08-31 08:51:57.257  2714  2714 V BluetoothAdapterState: isBleTurningOff()=false
08-31 08:51:57.257  3868  3868 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 08:51:57.257  3868  3868 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 08:51:57.257  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 08:51:57.257  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 08:51:57.257  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-31 08:51:57.257  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-31 08:51:57.257  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 08:51:57.257  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 08:51:57.257  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-31 08:51:57.257  2714  2714 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-31 08:51:57.257  2714  2765 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
08-31 08:51:57.257  2714  2765 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
08-31 08:51:57.257  3868  3868 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 08:51:57.257  3868  3868 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-31 08:51:57.257  2714  2714 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-31 08:51:57.258  2714  2714 V BluetoothAdapterState: isTurningOff()=true
,08-31 08:51:57.258  2714  2714 V BluetoothAdapterState: isTurningOn()=false
08-31 08:51:57.258  2714  2714 V BluetoothAdapterState: isBleTurningOn()=false
08-31 08:51:57.258  2714  2714 V BluetoothAdapterState: isBleTurningOff()=false
08-31 08:51:57.258  2714  2714 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
,08-31 08:51:57.258  2714  2714 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-31 08:51:57.259  2714  2714 D BluetoothMapService: MAP Service closeService in
08-31 08:51:57.259  2714  2714 V BluetoothAdapterState: isTurningOff()=true
08-31 08:51:57.259  2714  2714 V BluetoothAdapterState: isTurningOn()=false
08-31 08:51:57.259  2714  2714 V BluetoothAdapterState: isBleTurningOn()=false
08-31 08:51:57.259  2714  2714 V BluetoothAdapterState: isBleTurningOff()=false
,08-31 08:51:57.260  2714  2761 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
08-31 08:51:57.260  2714  2761 D BluetoothAdapterProperties: Setting state to 15
08-31 08:51:57.260  2714  2761 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
08-31 08:51:57.260   872  1310 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-31 08:51:57.260  1355  1377 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-31 08:51:57.261  1355  2035 D BluetoothHeadset: onBluetoothStateChange: up=false
08-31 08:51:57.261  2714  2761 I BluetoothAdapterState: Entering BleOnState
08-31 08:51:57.261   872   889 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-31 08:51:57.261   872   889 D BluetoothHeadset: onBluetoothStateChange: up=false
08-31 08:51:57.261  1355  1385 D BluetoothMap: onBluetoothStateChange: up=false
08-31 08:51:57.262  1355  1377 D BluetoothPbap: onBluetoothStateChange: up=false
08-31 08:51:57.262   872  1857 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.gstatic.com": No address associated with hostname
08-31 08:51:57.262  1355  2035 D BluetoothA2dp: onBluetoothStateChange: up=false
08-31 08:51:57.263  1355  1385 D BluetoothPan: onBluetoothStateChange on: false
08-31 08:51:57.263  1971  1986 D BluetoothHeadset: onBluetoothStateChange: up=false
08-31 08:51:57.263  2714  2714 D BluetoothMapService: cleanup()
08-31 08:51:57.263  2714  2714 D BluetoothMapService: MAP Service closeService in
08-31 08:51:57.264   872   889 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-31 08:51:57.264   872   889 D BluetoothHeadset: onBluetoothStateChange: up=false
08-31 08:51:57.264  2714  2761 D BluetoothAdapterState: Current state: BLE ON, message: 20
08-31 08:51:57.264  2714  2761 D BluetoothAdapterProperties: Setting state to 16
08-31 08:51:57.265  2714  2761 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
08-31 08:51:57.265  2714  2761 D BluetoothAdapterProperties: onBleDisable
08-31 08:51:57.265  2714  2761 I BluetoothAdapterState: Entering PendingCommandState
08-31 08:51:57.265  2714  2762 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
,08-31 08:51:57.266  2714  2765 D BluetoothAdapterProperties: Scan Mode:20
08-31 08:51:57.267  2714  2893 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
08-31 08:51:57.267  2714  2893 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-31 08:51:57.267  3868  3868 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 08:51:57.268  3868  3868 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 08:51:57.269  3868  3868 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 08:51:57.270  3868  3868 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 08:51:57.280   872  1863 D DhcpClient: Receive thread stopped
,08-31 08:51:57.276  1897  2314 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 08:51:57.294   371   870 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
08-31 08:51:57.295   872   884 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 133762, reason: 10074, SyncResult: stats [ numIoExceptions: 1]
,08-31 08:51:57.314   371   870 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-31 08:51:57.314   872  1312 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
,08-31 08:51:57.315   872  1312 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
08-31 08:51:57.316  3936  3936 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm
08-31 08:51:57.318   872   889 D Tethering: MasterInitialState.processMessage what=3
08-31 08:51:57.320  3868  3868 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 08:51:57.321  3868  3868 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 08:51:57.321  3458  3458 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@409181c and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
08-31 08:51:57.322  2060  2060 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
,08-31 08:51:57.332  3936  3936 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-31 08:51:57.338  1511  1511 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-31 08:51:57.341   872   889 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@adf8814:true
,08-31 08:51:57.351   872  1993 I ActivityManager: Start proc 3956:com.google.android.apps.maps/u0a65 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,08-31 08:51:57.358  3936  3936 D LocalBluetoothProfileManager: Adding local MAP profile
,08-31 08:51:57.362  3936  3936 D BluetoothMap: Create BluetoothMap proxy object
,08-31 08:51:57.366  3936  3936 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,08-31 08:51:57.367   371   870 E Netd    : netlink response contains error (No such file or directory)
,08-31 08:51:57.368   872  1312 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,08-31 08:51:57.380  3956  3956 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm
,08-31 08:51:57.383  3936  3936 D DockEventReceiver: finishStartingService: stopping service
,08-31 08:51:57.391   872   882 I ActivityManager: Killing 3110:com.google.android.talk/u0a61 (adj 15): empty #17
,08-31 08:51:57.470  2714  2765 I bt_hci  : shut_down
08-31 08:51:57.471  2714  2771 D bt_hwcfg: hw_epilog_process
,08-31 08:51:57.487  2714  2771 I bt_vendor: low_power_mode_cb
,08-31 08:51:57.507  2714  2771 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,08-31 08:51:57.507  2714  2771 I bt_vendor: epilog_cb
,08-31 08:51:57.507  2714  2771 I bt_hci  : epilog_finished_callback
,08-31 08:51:57.511  2714  2765 I bt_hci_h4: hal_close
,08-31 08:51:57.511  2714  2765 I bt_userial_vendor: device fd = 51 close
,08-31 08:51:57.593  3956  3956 D StrictMode: StrictMode policy violation; ~duration=92 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-31 08:51:57.593  3956  3956 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-31 08:51:57.593  3956  3956 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-31 08:51:57.593  3956  3956 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-31 08:51:57.593  3956  3956 D StrictMode: 	at java.io.File.exists(File.java:361)
08-31 08:51:57.593  3956  3956 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
08-31 08:51:57.593  3956  3956 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
08-31 08:51:57.593  3956  3956 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
08-31 08:51:57.593  3956  3956 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-31 08:51:57.593  3956  3956 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-31 08:51:57.593  3956  3956 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-31 08:51:57.593  3956  3956 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-31 08:51:57.593  3956  3956 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-31 08:51:57.593  3956  3956 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-31 08:51:57.593  3956  3956 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-31 08:51:57.593  3956  3956 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-31 08:51:57.593  3956  3956 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-31 08:51:57.593  3956  3956 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-31 08:51:57.593  3956  3956 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-31 08:51:57.593  3956  3956 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-31 08:51:57.593  3956  3956 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-31 08:51:57.593  3956  3956 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 08:51:57.593  3956  3956 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-31 08:51:57.593  3956  3956 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-31 08:51:57.593  3956  3956 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-31 08:51:57.593  3956  3956 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-31 08:51:57.593  3956  3956 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-31 08:51:57.593  3956  3956 D StrictMode: StrictMode policy violation; ~duration=92 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-31 08:51:57.593  3956  3956 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-31 08:51:57.593  3956  3956 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
08-31 08:51:57.593  3956  3956 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-31 08:51:57.593  3956  3956 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-31 08:51:57.593  3956  3956 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
08-31 08:51:57.593  3956  3956 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-31 08:51:57.593  3956  3956 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-31 08:51:57.593  3956  3956 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-31 08:51:57.593  3956  3956 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-31 08:51:57.593  3956  3956 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-31 08:51:57.593  3956  3956 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-31 08:51:57.593  3956  3956 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-31 08:51:57.593  3956  3956 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-31 08:51:57.593  3956  3956 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-31 08:51:57.593  3956  3956 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-31 08:51:57.593  3956  3956 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-31 08:51:57.593  3956  3956 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-31 08:51:57.593  3956  3956 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-31 08:51:57.593  3956  3956 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 08:51:57.593  3956  3956 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-31 08:51:57.593  3956  3956 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-31 08:51:57.593  3956  3956 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-31 08:51:57.593  3956  3956 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-31 08:51:57.593  3956  3956 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-31 08:51:57.594  3956  3956 D StrictMode: StrictMode policy violation; ~duration=92 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-31 08:51:57.594  3956  3956 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-31 08:51:57.594  3956  3956 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
08-31 08:51:57.594  3956  3956 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
08-31 08:51:57.594  3956  3956 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-31 08:51:57.594  3956  3956 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
08-31 08:51:57.594  3956  3956 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-31 08:51:57.594  3956  3956 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-31 08:51:57.594  3956  3956 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-31 08:51:57.594  3956  3956 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-31 08:51:57.594  3956  3956 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-31 08:51:57.594  3956  3956 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-31 08:51:57.594  3956  3956 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-31 08:51:57.594  3956  3956 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-31 08:51:57.594  3956  3956 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-31 08:51:57.594  3956  3956 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-31 08:51:57.594  3956  3956 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-31 08:51:57.594  3956  3956 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-31 08:51:57.594  3956  3956 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-31 08:51:57.594  3956  3956 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 08:51:57.594  3956  3956 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-31 08:51:57.594  3956  3956 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-31 08:51:57.594  3956  3956 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-31 08:51:57.594  3956  3956 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-31 08:51:57.594  3956  3956 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-31 08:51:57.594  3956  3956 D StrictMode: StrictMode policy violation; ~duration=91 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-31 08:51:57.594  3956  3956 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-31 08:51:57.594  3956  3956 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-31 08:51:57.594  3956  3956 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
08-31 08:51:57.594  3956  3956 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-31 08:51:57.594  3956  3956 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-31 08:51:57.594  3956  3956 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-31 08:51:57.594  3956  3956 D StrictMode: 	at com.google.r.k.d(PG:1187)
08-31 08:51:57.594  3956  3956 D StrictMode: 	at com.google.r.k.a(PG:2107)
08-31 08:51:57.594  3956  3956 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
08-31 08:51:57.594  3956  3956 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
08-31 08:51:57.594  3956  3956 D StrictMode: 	at com.google.r.v.a(PG:1161)
08-31 08:51:57.594  3956  3956 D StrictMode: 	at com.google.r.y.a(PG:2188)
08-31 08:51:57.594  3956  3956 D StrictMode: 	at com.google.r.e.b(PG:170)
08-31 08:51:57.594  3956  3956 D StrictMode: 	at com.google.r.e.b(PG:15188)
08-31 08:51:57.594  3956  3956 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
08-31 08:51:57.594  3956  3956 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-31 08:51:57.594  3956  3956 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-31 08:51:57.594  3956  3956 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-31 08:51:57.594  3956  3956 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-31 08:51:57.594  3956  3956 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-31 08:51:57.594  3956  3956 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-31 08:51:57.594  3956  3956 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-31 08:51:57.594  3956  3956 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-31 08:51:57.594  3956  3956 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-31 08:51:57.594  3956  3956 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-31 08:51:57.594  3956  3956 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-31 08:51:57.594  3956  3956 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 08:51:57.594  3956  3956 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-31 08:51:57.594  3956  3956 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-31 08:51:57.594  3956  3956 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-31 08:51:57.594  3956  3956 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-31 08:51:57.594  3956  3956 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-31 08:51:57.594  3956  3956 D StrictMode: StrictMode policy violation; ~duration=89 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-31 08:51:57.594  3956  3956 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-31 08:51:57.594  3956  3956 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-31 08:51:57.594  3956  3956 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
08-31 08:51:57.594  3956  3956 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-31 08:51:57.594  3956  3956 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-31 08:51:57.594  3956  3956 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-31 08:51:57.594  3956  3956 D StrictMode: 	at com.google.r.k.d(PG:1187)
08-31 08:51:57.594  3956  3956 D StrictMode: 	at com.google.r.k.c(PG:18147)
08-31 08:51:57.594  3956  3956 D StrictMode: 	at com.google.r.k.d(PG:583)
08-31 08:51:57.594  3956  3956 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
08-31 08:51:57.594  3956  3956 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
08-31 08:51:57.594  3956  3956 D StrictMode: 	at com.google.r.v.a(PG:1161)
08-31 08:51:57.594  3956  3956 D StrictMode: 	at com.google.r.y.a(PG:2188)
08-31 08:51:57.594  3956  3956 D StrictMode: 	at com.google.r.e.b(PG:170)
08-31 08:51:57.594  3956  3956 D StrictMode: 	at com.google.r.e.b(PG:15188)
08-31 08:51:57.594  3956  3956 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
08-31 08:51:57.594  3956  3956 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-31 08:51:57.594  3956  3956 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-31 08:51:57.594  3956  3956 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-31 08:51:57.594  3956  3956 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-31 08:51:57.594  3956  3956 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-31 08:51:57.594  3956  3956 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-31 08:51:57.594  3956  3956 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-31 08:51:57.594  3956  3956 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-31 08:51:57.594  3956  3956 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-31 08:51:57.594  3956  3956 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-31 08:51:57.594  3956  3956 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-31 08:51:57.594  3956  3956 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 08:51:57.594  3956  3956 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-31 08:51:57.594  3956  3956 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-31 08:51:57.594  3956  3956 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-31 08:51:57.594  3956  3956 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-31 08:51:57.594  3956  3956 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-31 08:51:57.594  3956  3956 D StrictMode: StrictMode policy violation; ~duration=69 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-31 08:51:57.594  3956  3956 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-31 08:51:57.594  3956  3956 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-31 08:51:57.594  3956  3956 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-31 08:51:57.594  3956  3956 D StrictMode: 	at java.io.File.exists(File.java:361)
08-31 08:51:57.594  3956  3956 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
08-31 08:51:57.594  3956  3956 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
08-31 08:51:57.594  3956  3956 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
08-31 08:51:57.594  3956  3956 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
08-31 08:51:57.594  3956  3956 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
08-31 08:51:57.594  3956  3956 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-31 08:51:57.594  3956  3956 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-31 08:51:57.594  3956  3956 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-31 08:51:57.594  3956  3956 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-31 08:51:57.594  3956  3956 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-31 08:51:57.594  3956  3956 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-31 08:51:57.594  3956  3956 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-31 08:51:57.594  3956  3956 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-31 08:51:57.594  3956  3956 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-31 08:51:57.594  3956  3956 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-31 08:51:57.594  3956  3956 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 08:51:57.594  3956  3956 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-31 08:51:57.594  3956  3956 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-31 08:51:57.594  3956  3956 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-31 08:51:57.594  3956  3956 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-31 08:51:57.594  3956  3956 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-31 08:51:57.594  3956  3956 D StrictMode: StrictMode policy violation; ~duration=68 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-31 08:51:57.594  3956  3956 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-31 08:51:57.594  3956  3956 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-31 08:51:57.594  3956  3956 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-31 08:51:57.594  3956  3956 D StrictMode: 	at java.io.File.exists(File.java:361)
08-31 08:51:57.594  3956  3956 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
08-31 08:51:57.594  3956  3956 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-31 08:51:57.594  3956  3956 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-31 08:51:57.594  3956  3956 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-31 08:51:57.594  3956  3956 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-31 08:51:57.594  3956  3956 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-31 08:51:57.594  3956  3956 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-31 08:51:57.594  3956  3956 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-31 08:51:57.594  3956  3956 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-31 08:51:57.594  3956  3956 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-31 08:51:57.594  3956  3956 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-31 08:51:57.594  3956  3956 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 08:51:57.594  3956  3956 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-31 08:51:57.594  3956  3956 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-31 08:51:57.594  3956  3956 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-31 08:51:57.594  3956  3956 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-31 08:51:57.594  3956  3956 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-31 08:51:57.594  3956  3956 D StrictMode: StrictMode policy violation; ~duration=68 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-31 08:51:57.594  3956  3956 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-31 08:51:57.594  3956  3956 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
08-31 08:51:57.594  3956  3956 D StrictMode: 	at java.io.File.lastModified(File.java:569)
08-31 08:51:57.594  3956  3956 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
08-31 08:51:57.594  3956  3956 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-31 08:51:57.594  3956  3956 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-31 08:51:57.594  3956  3956 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-31 08:51:57.594  3956  3956 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-31 08:51:57.594  3956  3956 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-31 08:51:57.594  3956  3956 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-31 08:51:57.594  3956  3956 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-31 08:51:57.594  3956  3956 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-31 08:51:57.594  3956  3956 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-31 08:51:57.594  3956  3956 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-31 08:51:57.594  3956  3956 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 08:51:57.594  3956  3956 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-31 08:51:57.594  3956  3956 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-31 08:51:57.594  3956  3956 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-31 08:51:57.594  3956  3956 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-31 08:51:57.594  3956  3956 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-31 08:51:57.619   872  1393 I ActivityManager: Start proc 3986:com.google.android.talk/u0a61 for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver
08-31 08:51:57.620   872  1393 I ActivityManager: Killing 3458:com.google.android.music:main/u0a66 (adj 15): empty #17
,08-31 08:51:57.651  3868  3868 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-31 08:51:57.811  2714  2762 D bt_stack_manager: event_shut_down_stack finished.
,08-31 08:51:57.811  2714  2761 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,08-31 08:51:57.813  2714  2714 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-31 08:51:57.813  2714  2761 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
08-31 08:51:57.813  2714  2714 D BtGatt.GattService: Received stop request...Stopping profile...
08-31 08:51:57.813  2714  2714 D BtGatt.GattService: stop()
08-31 08:51:57.814  2714  2714 D BtGatt.AdvertiseManager: advertise clients cleared
,08-31 08:51:57.815  2714  2714 V BluetoothAdapterState: isTurningOff()=false
08-31 08:51:57.815  2714  2714 V BluetoothAdapterState: isTurningOn()=false
08-31 08:51:57.815  2714  2714 V BluetoothAdapterState: isBleTurningOn()=false
,08-31 08:51:57.815  2714  2714 V BluetoothAdapterState: isBleTurningOff()=true
08-31 08:51:57.815  2714  2761 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
08-31 08:51:57.816  2714  2761 D BluetoothAdapterProperties: Setting state to 10
08-31 08:51:57.816  2714  2761 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
,08-31 08:51:57.817  2714  2761 I BluetoothAdapterState: Entering OffState
08-31 08:51:57.817   872   889 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
,08-31 08:51:57.824  2714  2714 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,08-31 08:51:57.824  2714  2714 W BluetoothSdpJni: Cleaning up Bluetooth Health object
08-31 08:51:57.824  2714  2714 I BluetoothServiceJni: cleanupNative: return from cleanup
08-31 08:51:57.825  2714  2762 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,08-31 08:51:57.828  2714  2762 D bt_stack_manager: event_clean_up_stack finished.
,08-31 08:51:57.830  3986  3986 W System  : ClassLoader referenced unknown path: /system/app/Hangouts/lib/arm
,08-31 08:51:57.841  2714  2714 I art     : System.exit called, status: 0
,08-31 08:51:57.841  2714  2714 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-31 08:51:57.897   872  2078 I ActivityManager: Process com.android.bluetooth (pid 2714) has died
,08-31 08:51:57.988  3956  3974 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,08-31 08:51:58.056  3986  4007 I Babel_SMS: MmsConfig: mnc/mcc: 0/0
08-31 08:51:58.056  3986  4007 I Babel_SMS: MmsConfig.loadMmsSettings
08-31 08:51:58.058  3986  4007 I Babel_SMS: MmsConfig.loadDeviceMmsSettings from API: mUserAgent=nexus6, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/nexus6/Profile/nexus6.rdf
08-31 08:51:58.058  3986  4007 I Babel_SMS: MmsConfig.loadFromDatabase
,08-31 08:51:58.099  3986  4007 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc 
08-31 08:51:58.100  3986  4007 I Babel_SMS: MmsConfig.loadFromResources
08-31 08:51:58.101  3986  4007 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc nullnull
08-31 08:51:58.102  3986  4007 I Babel_SMS: MmsConfig.loadMmsSettings: mUserAgent=nexus6, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/nexus6/Profile/nexus6.rdf
,08-31 08:51:58.155  3986  3986 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-31 08:51:58.159  3986  3986 I Babel_Crash: startup - clean
,08-31 08:51:58.171   872   889 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@7238a0c:true
,08-31 08:51:58.187  3986  3986 I Babel_telephony: TeleModule.launchCompleted
,08-31 08:51:58.202   872  1993 I Telecom : PhoneAccountRegistrar: SimCallManager queried, returning: null
,08-31 08:51:58.213  3986  3986 I Babel_telephony: TeleModule.updateConnectionManagerRegistration, registration preference changed from false to false
,08-31 08:51:58.221  3986  3986 W Babel   : BAM#gBA: invalid account id: -1
,08-31 08:51:58.221  3986  3986 W Babel   : BAM#gBA: invalid account id: -1
08-31 08:51:58.222  3986  3986 I Babel_telephony: TeleModule.updateIncomingCallRegistration, preferred account for incoming calls changed from: null to null
,08-31 08:51:58.226   872   883 I Telecom : PhoneAccountRegistrar: SimCallManager queried, returning: null
,08-31 08:51:58.234  3986  4012 I Babel   : deleted: false for 0
,08-31 08:51:58.281   872   882 I ActivityManager: Start proc 4014:com.google.android.apps.gcs/u0a89 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,08-31 08:51:58.290  3986  3986 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-31 08:51:58.353  4014  4014 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm
,08-31 08:51:58.356  3986  3986 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,08-31 08:51:58.367  3986  3986 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-31 08:51:58.381  3986  3986 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-31 08:51:58.388  3986  3986 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-31 08:51:58.401  3986  3986 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-31 08:51:58.413  3986  3986 I vclib   : onServiceConnected
,08-31 08:51:58.456  4014  4014 W ClientExperimentManager: [1] d.a: com.google.android.apps.gcs does not have permission com.google.android.apps.gcs.WRITE_EXPERIMENTS; disabling overrides
,08-31 08:51:58.483  3936  3936 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-31 08:51:58.526   872  2078 I ActivityManager: Start proc 4039:com.android.bluetooth/1002 for broadcast com.android.bluetooth/.pbap.BluetoothPbapReceiver
,08-31 08:51:58.527  3936  3936 D DockEventReceiver: finishStartingService: stopping service
,08-31 08:51:58.528   872  2076 I ActivityManager: Killing 3622:com.google.process.gapps/u0a99 (adj 15): empty #17
,08-31 08:51:58.623  4039  4039 D AdapterServiceConfig: Adding HeadsetService
,08-31 08:51:58.624  4039  4039 D AdapterServiceConfig: Adding A2dpService
08-31 08:51:58.624  4039  4039 D AdapterServiceConfig: Adding HidService
08-31 08:51:58.624  4039  4039 D AdapterServiceConfig: Adding HealthService
08-31 08:51:58.624  4039  4039 D AdapterServiceConfig: Adding PanService
08-31 08:51:58.624  4039  4039 D AdapterServiceConfig: Adding GattService
08-31 08:51:58.625  4039  4039 D AdapterServiceConfig: Adding BluetoothMapService
,08-31 08:51:58.628   872  2255 I ActivityManager: Killing 2788:com.android.providers.calendar/u0a3 (adj 15): empty #17
,08-31 08:51:58.685  1511  1511 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-31 08:51:58.709  1716  1716 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-31 08:51:58.713  1716  1716 D SystemUpdateService: onCreate
,08-31 08:51:58.719  1716  1716 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-31 08:51:58.727  1716  4051 I SystemUpdateService: active receiver: enabled
,08-31 08:51:58.730  1716  4051 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-31 08:51:58.732  1716  4051 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,08-31 08:51:58.732  1716  4051 I SystemUpdateService: now status is 0 (complete)
08-31 08:51:58.732  1716  4051 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
,08-31 08:51:58.732  1716  4051 I SystemUpdateService: file has been verified
08-31 08:51:58.733  1716  4051 I SystemUpdateService: OTA package size = 12249756
,08-31 08:51:58.739  1716  4051 I SystemUpdateService: showing system update notification
,08-31 08:51:58.752  1716  1716 D SystemUpdateService: onDestroy
,08-31 08:51:58.761  1716  1716 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,08-31 08:51:58.763  1716  2405 I iu.UploadsManager: num queued entries: 0
,08-31 08:51:58.764  1716  2405 I iu.UploadsManager: num updated entries: 0
08-31 08:51:58.764  1716  2405 I iu.SyncManager: NEXT; no task
,08-31 08:51:58.767  1716  1716 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-31 08:51:58.769  1716  1716 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-31 08:51:58.787   872  2255 I ActivityManager: Start proc 4053:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,08-31 08:51:58.840  4053  4053 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm
,08-31 08:51:58.843  4053  4053 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-31 08:51:58.850  4053  4053 D SprintDMHelper: simOperator: 
,08-31 08:51:58.850  4053  4053 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-31 08:51:58.880   872  2001 I ActivityManager: Start proc 4065:com.android.chrome/u0a40 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
,08-31 08:51:58.881   872  2001 I ActivityManager: Killing 3557:android.process.acore/u0a5 (adj 15): empty #17
,08-31 08:51:59.034   872  2078 I ActivityManager: Start proc 4080:com.google.android.apps.magazines/u0a67 for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider
,08-31 08:51:59.042  3986  4079 I Babel   : connection state changed from UNKNOWN to DISCONNECTED
,08-31 08:51:59.046   872  2255 I ActivityManager: Killing 3696:com.google.android.partnersetup/u0a16 (adj 15): empty #17
,08-31 08:51:59.131  4080  4080 W System  : ClassLoader referenced unknown path: /system/app/Newsstand/lib/arm
,08-31 08:51:59.194  4080  4080 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
08-31 08:51:59.194  4080  4080 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
08-31 08:51:59.194  4080  4080 I GAv4    :   adb logcat -s GAv4
,08-31 08:51:59.210  4080  4080 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,08-31 08:51:59.217  4080  4080 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,08-31 08:51:59.250  4080  4097 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,08-31 08:51:59.366  4080  4080 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
,08-31 08:51:59.404  4080  4080 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,08-31 08:51:59.417  4080  4080 I LibraryLoader: Time to load native libraries: 7 ms (timestamps 6370-6377)
,08-31 08:51:59.418  4080  4080 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-31 08:51:59.431  4080  4080 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {153fa76}
,08-31 08:51:59.432  4080  4080 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-31 08:51:59.432  4080  4080 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,08-31 08:51:59.442  4080  4080 I BrowserStartupController: Initializing chromium process, singleProcess=true
,08-31 08:51:59.444  4080  4080 E SysUtils: ApplicationContext is null in ApplicationStatus
,08-31 08:51:59.463  4080  4080 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,08-31 08:51:59.478  4080  4080 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,08-31 08:51:59.478  4080  4080 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,08-31 08:51:59.478  4080  4080 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-31 08:51:59.478  4080  4080 I Adreno  : Build Date                       : 10/20/15
08-31 08:51:59.478  4080  4080 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-31 08:51:59.478  4080  4080 I Adreno  : Local Branch                     : M14
08-31 08:51:59.478  4080  4080 I Adreno  : Remote Branch                    : 
08-31 08:51:59.478  4080  4080 I Adreno  : Remote Branch                    : 
08-31 08:51:59.478  4080  4080 I Adreno  : Reconstruct Branch               : 
,08-31 08:51:59.541  4080  4080 I NSApplication: Starting up...
,08-31 08:51:59.554  4080  4126 W AudioManagerAndroid: Requires BLUETOOTH permission
,08-31 08:51:59.579   872  1998 I ActivityManager: Start proc 4131:com.google.android.apps.photos/u0a71 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
,08-31 08:51:59.580   872  1998 I ActivityManager: Killing 3711:com.android.musicfx/u0a18 (adj 15): empty #17
,08-31 08:51:59.644  4131  4131 W System  : ClassLoader referenced unknown path: /system/app/Photos/lib/arm
,08-31 08:51:59.849   872   882 I ActivityManager: Killing 3507:com.google.android.gms.wearable/u0a11 (adj 15): empty #17
,08-31 08:52:00.204   872  2078 D WifiService: setWifiEnabled: true pid=3868, uid=10000
08-31 08:52:00.204   872  2078 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-31 08:52:00.216   872  1310 D WifiConfigStore: Loading config and enabling all networks 
,08-31 08:52:00.224  3868  3868 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-31 08:52:00.225  3868  3868 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 08:52:00.225  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 08:52:00.225  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 08:52:00.225  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 08:52:00.225  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-31 08:52:00.225  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 08:52:00.225  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 08:52:00.225  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-31 08:52:00.225  3868  3868 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 08:52:00.225  3868  3868 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-31 08:52:00.228  3868  3868 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-31 08:52:00.229  3868  3868 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 08:52:00.229  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 08:52:00.229  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 08:52:00.229  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 08:52:00.229  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-31 08:52:00.229  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 08:52:00.229  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 08:52:00.229  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-31 08:52:00.229  3868  3868 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-31 08:52:00.229  3868  3868 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-31 08:52:00.251   872  1310 D WifiConfigStore: loaded 0 passpoint configs
,08-31 08:52:00.252   872  1310 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,08-31 08:52:00.253   872  1310 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,08-31 08:52:00.253   872  1310 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,08-31 08:52:00.254   872  1310 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
,08-31 08:52:00.254   872  1310 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
,08-31 08:52:00.254   872  1310 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,08-31 08:52:00.276   872  1310 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=10.88 rxSuccessRate=17.12 delta 1000 -> 994
,08-31 08:52:00.276   371   870 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,08-31 08:52:00.279   371   870 D CommandListener: Setting iface cfg
,08-31 08:52:00.283   872  1309 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '133 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 133 Failed to set address (No such device)'
,08-31 08:52:00.283   872  1309 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,08-31 08:52:00.283   872  1310 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
,08-31 08:52:00.283   872  1310 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-31 08:52:00.291   872  1310 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,08-31 08:52:00.321   872  1309 D WifiNative-HAL: p2pGetDeviceAddress
,08-31 08:52:00.321   872  1309 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,08-31 08:52:00.372   872  1310 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,08-31 08:52:00.374  1460  1460 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,08-31 08:52:00.796  1460  1460 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-31 08:52:00.843  1460  1460 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,08-31 08:52:00.844  1460  1460 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,08-31 08:52:00.853   872  1310 D WifiConfigStore: Retrieve network priorities after PNO.
,08-31 08:52:00.864   872  1310 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
08-31 08:52:00.864   872  1310 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-31 08:52:00.864   872  1312 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,08-31 08:52:00.888   872  1310 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-31 08:52:00.902   371   870 D CommandListener: Setting iface cfg
,08-31 08:52:00.903   872  1310 D WifiStateMachine: Start Dhcp Watchdog 2
,08-31 08:52:00.919   872  1312 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
,08-31 08:52:00.920   872  1310 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,08-31 08:52:00.961   872  4156 D DhcpClient: Receive thread started
,08-31 08:52:01.044   872  1310 E native  : do suspend false
,08-31 08:52:01.064   872  1861 D DhcpClient: Broadcasting DHCPDISCOVER
,08-31 08:52:01.081   872  4156 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.101, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172685, domain null
,08-31 08:52:01.082   872  1861 D DhcpClient: Got pending lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172685 seconds
,08-31 08:52:01.087   872  1861 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.101 serverid=192.168.1.1
,08-31 08:52:01.100   872  4156 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.101, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,08-31 08:52:01.101   872  1861 D DhcpClient: Confirmed lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,08-31 08:52:01.106   371   870 D CommandListener: Setting iface cfg
,08-31 08:52:01.117   872  1861 D DhcpClient: Scheduling renewal in 86399s
,08-31 08:52:01.117   872  1310 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,08-31 08:52:01.138   872  1310 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,08-31 08:52:01.141   872  1310 D WifiConfigStore: No blacklist allowed without epno enabled
,08-31 08:52:01.141   872  1312 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,08-31 08:52:01.142   872  1312 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,08-31 08:52:01.148   872  1312 D ConnectivityService: Adding iface wlan0 to network 101
,08-31 08:52:01.157   872  1310 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,08-31 08:52:01.202   872  1312 E ConnectivityService: Unexpected mtu value: 0, wlan0
,08-31 08:52:01.202   872  1312 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
,08-31 08:52:01.203   872  1312 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,08-31 08:52:01.204   872  1312 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,08-31 08:52:01.206   872  1312 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,08-31 08:52:01.226   872  1312 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,08-31 08:52:01.231   872  1312 D ConnectivityService: scheduleUnvalidatedPrompt 101
,08-31 08:52:01.231   872  1312 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
,08-31 08:52:01.231   872  1310 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: [],
,08-31 08:52:01.232   872  1310 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-31 08:52:01.232   872  1312 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
,08-31 08:52:01.232   872  1312 D ConnectivityService:    accepting network in place of null,
,08-31 08:52:01.234   872  1312 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.101/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -50]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-31 08:52:01.284   371   870 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-31 08:52:01.285   872  4155 D NetlinkSocketObserver: NeighborEvent{elapsedMs=138245, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-31 08:52:01.322   371   870 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-31 08:52:01.331   872  1312 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,08-31 08:52:01.333   872  1312 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-31 08:52:01.344   872   889 D Tethering: MasterInitialState.processMessage what=3
08-31 08:52:01.350   872  1312 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
08-31 08:52:01.350  3868  3868 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-31 08:52:01.351  3868  3868 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 08:52:01.351  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 08:52:01.351  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 08:52:01.351  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 08:52:01.351  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-31 08:52:01.351  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-31 08:52:01.351  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-31 08:52:01.351  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-31 08:52:01.355  3868  3868 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 08:52:01.355  3868  3868 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-31 08:52:01.359  3868  3868 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 08:52:01.359  3868  3868 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 08:52:01.359  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 08:52:01.359  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 08:52:01.359  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 08:52:01.359  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-31 08:52:01.359  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-31 08:52:01.359  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-31 08:52:01.359  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-31 08:52:01.359  3868  3868 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 08:52:01.359  3868  3868 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-31 08:52:01.364  2060  2060 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
,08-31 08:52:01.370  1716  1716 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-31 08:52:01.374  1716  1716 D SystemUpdateService: onCreate
,08-31 08:52:01.376  1716  1716 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-31 08:52:01.378  1716  4167 I SystemUpdateService: active receiver: enabled
,08-31 08:52:01.381  1716  4167 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-31 08:52:01.388  1716  4167 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,08-31 08:52:01.388  1716  4167 I SystemUpdateService: now status is 0 (complete)
08-31 08:52:01.388  1716  4167 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
08-31 08:52:01.388  1716  4167 I SystemUpdateService: file has been verified
,08-31 08:52:01.388  1716  4167 I SystemUpdateService: OTA package size = 12249756
,08-31 08:52:01.391  1716  4167 I SystemUpdateService: showing system update notification
,08-31 08:52:01.400  1716  1716 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,08-31 08:52:01.403  1716  2405 I iu.UploadsManager: num queued entries: 0
,08-31 08:52:01.403  1716  2405 I iu.UploadsManager: num updated entries: 0
08-31 08:52:01.404  1716  2405 I iu.SyncManager: NEXT; no task
,08-31 08:52:01.406  1716  1716 D SystemUpdateService: onDestroy
,08-31 08:52:01.406  1716  4171 I MDM     : [180] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
08-31 08:52:01.406  1716  4171 W BaseAppContext: Using Auth Proxy for data requests.
,08-31 08:52:01.407  1716  4171 V GoogleAuthProtoRequest: [180] a.<init>: mAccountName set to: thalitester@gmail.com
08-31 08:52:01.409  1716  1716 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
08-31 08:52:01.410  1716  1716 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
08-31 08:52:01.412  4053  4053 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
08-31 08:52:01.416  4053  4053 D SprintDMHelper: simOperator: 
08-31 08:52:01.416  4053  4053 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-31 08:52:01.442  1511  1522 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
,08-31 08:52:01.442  1511  1522 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
08-31 08:52:01.442  1511  1522 I GLSUser : [GLSUser] Extracting token using key: Auth
08-31 08:52:01.443  1511  1522 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-31 08:52:01.467  1716  4171 E MDM     : [180] SitrepService.a: Error sending sitrep.
,08-31 08:52:02.330   872  1312 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,08-31 08:52:02.581   872  4154 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.209.78,2a00:1450:401b:801::200e
,08-31 08:52:03.211   872  1994 D WifiService: setWifiEnabled: false pid=3868, uid=10000
,08-31 08:52:03.211   872  1994 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-31 08:52:03.253  1460  1460 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,08-31 08:52:03.261   872  1310 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,08-31 08:52:03.262   872  1310 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
,08-31 08:52:03.262   872  1310 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-31 08:52:03.263   872  1310 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-31 08:52:03.283   371   870 D CommandListener: Clearing all IP addresses on wlan0
,08-31 08:52:03.283   872  1861 D DhcpClient: Clearing IP address
08-31 08:52:03.286   371   870 D CommandListener: Setting iface cfg
,08-31 08:52:03.290   872  4156 D DhcpClient: Receive thread stopped
,08-31 08:52:03.291  1511  4168 V NativeCrypto: SSL handshake aborted: ssl=0x9b536400: I/O error during system call, Connection timed out
,08-31 08:52:03.299   872  1310 D WifiStateMachine: Start Disconnecting Watchdog 2
,08-31 08:52:03.299   872  1312 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
,08-31 08:52:03.300   872  1310 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-31 08:52:03.300   872  1312 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 3
08-31 08:52:03.303   371   870 D CommandListener: Clearing all IP addresses on wlan0
,08-31 08:52:03.308   446   446 E Parcel  : Reading a NULL string not supported here.
,08-31 08:52:03.318   872  1312 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
,08-31 08:52:03.317   872  4154 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Probably not a portal: exception java.net.ConnectException: failed to connect to connectivitycheck.gstatic.com/2a00:1450:401b:801::200e (port 80) after 10000ms: connect failed: ENETUNREACH (Network is unreachable)
08-31 08:52:03.325   872  1310 D WifiConfigStore: Retrieve network priorities after PNO.
08-31 08:52:03.329   872  1310 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,08-31 08:52:03.329  3868  3868 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 08:52:03.329  3868  3868 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 08:52:03.329  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 08:52:03.329  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 08:52:03.329  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-31 08:52:03.329  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-31 08:52:03.329  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 08:52:03.329  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 08:52:03.329  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-31 08:52:03.329  3868  3868 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 08:52:03.329  3868  3868 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-31 08:52:03.330  3868  3868 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 08:52:03.330  3868  3868 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 08:52:03.330  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 08:52:03.330  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 08:52:03.330  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-31 08:52:03.330  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-31 08:52:03.330  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 08:52:03.330  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 08:52:03.330  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-31 08:52:03.330  3868  3868 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 08:52:03.330  3868  3868 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-31 08:52:03.332  1897  2314 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 08:52:03.334  3986  4173 W Babel_NetworkConnectionCheckingService: IO exceptions, probably not a captive portal 
08-31 08:52:03.339  3986  4173 W Babel_NetworkConnectionCheckingService: java.net.SocketException: recvfrom failed: ETIMEDOUT (Connection timed out)
08-31 08:52:03.339  3986  4173 W Babel_NetworkConnectionCheckingService: 	at libcore.io.IoBridge.maybeThrowAfterRecvfrom(IoBridge.java:588)
08-31 08:52:03.339  3986  4173 W Babel_NetworkConnectionCheckingService: 	at libcore.io.IoBridge.recvfrom(IoBridge.java:552)
08-31 08:52:03.339  3986  4173 W Babel_NetworkConnectionCheckingService: 	at java.net.PlainSocketImpl.read(PlainSocketImpl.java:481)
08-31 08:52:03.339  3986  4173 W Babel_NetworkConnectionCheckingService: 	at java.net.PlainSocketImpl.-wrap0(PlainSocketImpl.java)
08-31 08:52:03.339  3986  4173 W Babel_NetworkConnectionCheckingService: 	at java.net.PlainSocketImpl$PlainSocketInputStream.read(PlainSocketImpl.java:237)
08-31 08:52:03.339  3986  4173 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.okio.Okio$2.read(Okio.java:135)
08-31 08:52:03.339  3986  4173 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.okio.AsyncTimeout$2.read(AsyncTimeout.java:211)
08-31 08:52:03.339  3986  4173 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.okio.RealBufferedSource.indexOf(RealBufferedSource.java:306)
08-31 08:52:03.339  3986  4173 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.okio.RealBufferedSource.indexOf(RealBufferedSource.java:300)
08-31 08:52:03.339  3986  4173 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.okio.RealBufferedSource.readUtf8LineStrict(RealBufferedSource.java:196)
08-31 08:52:03.339  3986  4173 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.internal.http.HttpConnection.readResponse(HttpConnection.java:191)
08-31 08:52:03.339  3986  4173 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.internal.http.HttpTransport.readResponseHeaders(HttpTransport.java:80)
08-31 08:52:03.339  3986  4173 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.internal.http.HttpEngine.readNetworkResponse(HttpEngine.java:904)
08-31 08:52:03.339  3986  4173 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.internal.http.HttpEngine.readResponse(HttpEngine.java:788)
08-31 08:52:03.339  3986  4173 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.internal.huc.HttpURLConnectionImpl.execute(HttpURLConnectionImpl.java:443)
08-31 08:52:03.339  3986  4173 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.internal.huc.HttpURLConnectionImpl.getResponse(HttpURLConnectionImpl.java:388)
08-31 08:52:03.339  3986  4173 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.internal.huc.HttpURLConnectionImpl.getInputStream(HttpURLConnectionImpl.java:231)
08-31 08:52:03.339  3986  4173 W Babel_NetworkConnectionCheckingService: 	at com.google.android.apps.hangouts.service.NetworkConnectionCheckingService.a(SourceFile:129)
08-31 08:52:03.339  3986  4173 W Babel_NetworkConnectionCheckingService: 	at com.google.android.apps.hangouts.service.NetworkConnectionCheckingService.onHandleIntent(SourceFile:1100)
08-31 08:52:03.339  3986  4173 W Babel_NetworkConnectionCheckingService: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-31 08:52:03.339  3986  4173 W Babel_NetworkConnectionCheckingService: 	at android.os.Handler.dispatchMessage(,Handler.java:102)
08-31 08:52:03.339  3986  4173 W Babel_NetworkConnectionCheckingService: 	at android.os.Looper.loop(Looper.java:148)
08-31 08:52:03.339  3986  4173 W Babel_NetworkConnectionCheckingService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-31 08:52:03.339  3986  4173 W Babel_NetworkConnectionCheckingService: Caused by: android.system.ErrnoException: recvfrom failed: ETIMEDOUT (Connection timed out)
08-31 08:52:03.339  3986  4173 W Babel_NetworkConnectionCheckingService: 	at libcore.io.Posix.recvfromBytes(Native Method)
08-31 08:52:03.339  3986  4173 W Babel_NetworkConnectionCheckingService: 	at libcore.io.Posix.recvfrom(Posix.java:189)
08-31 08:52:03.339  3986  4173 W Babel_NetworkConnectionCheckingService: 	at libcore.io.BlockGuardOs.recvfrom(BlockGuardOs.java:250)
08-31 08:52:03.339  3986  4173 W Babel_NetworkConnectionCheckingService: 	at libcore.io.IoBridge.recvfrom(IoBridge.java:549)
08-31 08:52:03.339  3986  4173 W Babel_NetworkConnectionCheckingService: 	... 21 more
08-31 08:52:03.344  3986  4173 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,08-31 08:52:03.355   872  2166 I ActivityManager: Killing 3734:com.google.android.apps.docs/u0a46 (adj 15): empty #17
,08-31 08:52:03.362   371   870 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-31 08:52:03.407   371   870 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
08-31 08:52:03.408   872  1312 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
08-31 08:52:03.408   872  1312 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-31 08:52:03.411   872   889 D Tethering: MasterInitialState.processMessage what=3
,08-31 08:52:03.417  3868  3868 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 08:52:03.421  3868  3868 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 08:52:03.423  2060  2060 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
,08-31 08:52:03.426  1716  1716 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-31 08:52:03.429  1716  1716 D SystemUpdateService: onCreate
,08-31 08:52:03.432  1716  1716 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-31 08:52:03.436  1716  4188 I SystemUpdateService: active receiver: enabled
,08-31 08:52:03.445  1716  1716 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,08-31 08:52:03.447  1716  2405 I iu.UploadsManager: num queued entries: 0
,08-31 08:52:03.447  1716  2405 I iu.UploadsManager: num updated entries: 0
,08-31 08:52:03.453  1716  4188 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-31 08:52:03.454  1716  1716 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-31 08:52:03.456  1716  1716 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-31 08:52:03.458  4053  4053 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-31 08:52:03.461  4053  4053 D SprintDMHelper: simOperator: 
,08-31 08:52:03.462  4053  4053 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-31 08:52:03.494  1716  2405 I iu.SyncManager: NEXT; no task
,08-31 08:52:03.495   371   870 E Netd    : netlink response contains error (No such file or directory)
,08-31 08:52:03.496  1716  4188 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,08-31 08:52:03.498   872  1312 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,08-31 08:52:03.498  3986  4192 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,08-31 08:52:03.496  1716  4188 I SystemUpdateService: now status is 0 (complete)
,08-31 08:52:03.504  1716  4188 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
08-31 08:52:03.504  1716  4188 I SystemUpdateService: file has been verified
,08-31 08:52:03.504  1716  4188 I SystemUpdateService: OTA package size = 12249756
,08-31 08:52:03.509  1716  4188 I SystemUpdateService: showing system update notification
,08-31 08:52:03.518  1716  1716 D SystemUpdateService: onDestroy
,08-31 08:52:06.254   872   889 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@bee8edf:true
,08-31 08:52:06.255  4039  4039 D BluetoothAdapterState: make() - Creating AdapterState
,08-31 08:52:06.260  4039  4039 I bt_bluedroid: init
,08-31 08:52:06.261  4039  4195 I BluetoothAdapterState: Entering OffState
,08-31 08:52:06.265  4039  4196 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,08-31 08:52:06.265  4039  4196 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-31 08:52:06.265  4039  4196 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-31 08:52:06.265  4039  4196 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,08-31 08:52:06.266  4039  4039 I bt_bluedroid: get_profile_interface socket
,08-31 08:52:06.268  4039  4039 I bt_bluedroid: get_profile_interface sdp
,08-31 08:52:06.271  4039  4049 I bt_bluedroid: config_hci_snoop_log
08-31 08:52:06.271  4039  4199 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-31 08:52:06.274  4039  4199 D BluetoothAdapterProperties: Name is: Nexus 6
,08-31 08:52:06.277   872   889 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,08-31 08:52:06.290  4039  4195 D BluetoothAdapterState: Current state: OFF, message: 0
,08-31 08:52:06.290  4039  4195 D BluetoothAdapterProperties: Setting state to 14
08-31 08:52:06.291  4039  4195 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
08-31 08:52:06.295  4039  4195 D BluetoothBondStateMachine: make
,08-31 08:52:06.297  4039  4202 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-31 08:52:06.316  4039  4195 I BluetoothAdapterState: Entering PendingCommandState
,08-31 08:52:06.317  4039  4039 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
08-31 08:52:06.321  4039  4039 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4e6af5c
,08-31 08:52:06.322  4039  4039 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-31 08:52:06.324  4039  4039 D BtGatt.GattService: Received start request. Starting profile...
,08-31 08:52:06.324  4039  4039 D BtGatt.GattService: start()
,08-31 08:52:06.325  4039  4039 I bt_bluedroid: get_profile_interface gatt
,08-31 08:52:06.327  4039  4039 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4e6af5c
,08-31 08:52:06.327  4039  4039 D BtGatt.AdvertiseManager: advertise manager created
,08-31 08:52:06.340  4039  4039 V BluetoothAdapterState: isTurningOff()=false
,08-31 08:52:06.341  4039  4039 V BluetoothAdapterState: isTurningOn()=false
08-31 08:52:06.341  4039  4039 V BluetoothAdapterState: isBleTurningOn()=true
08-31 08:52:06.341  4039  4039 V BluetoothAdapterState: isBleTurningOff()=false
,08-31 08:52:06.343  4039  4195 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,08-31 08:52:06.344  4039  4195 I bt_bluedroid: enable
08-31 08:52:06.344  4039  4196 D bt_stack_manager: event_start_up_stack is bringing up the stack.
08-31 08:52:06.344  4039  4196 I bt_hci  : start_up
,08-31 08:52:06.350  4039  4196 I bt_vendor: alloc value 0xb39a9189
,08-31 08:52:06.350  4039  4196 I bt_vendor: init
08-31 08:52:06.350  4039  4196 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
08-31 08:52:06.350  4039  4196 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,08-31 08:52:06.410  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-31 08:52:06.438  1511  1522 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,08-31 08:52:06.438  1511  1522 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
,08-31 08:52:06.438  1511  1522 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-31 08:52:06.438  1511  1522 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-31 08:52:06.457  4039  4196 D bt_hci  : start_up starting async portion
,08-31 08:52:06.460  4039  4205 I bt_hci  : event_finish_startup
,08-31 08:52:06.460  4039  4205 I bt_hci_h4: hal_open
08-31 08:52:06.460  4039  4205 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,08-31 08:52:06.465  4039  4205 I bt_userial_vendor: device fd = 51 open
,08-31 08:52:06.478  3574  3574 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
08-31 08:52:06.478  3574  3574 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
,08-31 08:52:06.478  3574  3574 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 4.
,08-31 08:52:06.500  4039  4205 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-31 08:52:06.532  4039  4205 D bt_hwcfg: Chipset BCM4354A2
,08-31 08:52:06.532  4039  4205 D bt_hwcfg: Target name = [BCM4354A2]
08-31 08:52:06.532  4039  4205 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,08-31 08:52:07.197  4039  4205 I bt_hwcfg: bt vendor lib: set UART baud 115200
,08-31 08:52:07.197  4039  4205 D bt_hwcfg: Settlement delay -- 100 ms
,08-31 08:52:07.197  4039  4205 I bt_hwcfg: Setting fw settlement delay to 100 
,08-31 08:52:07.314  4039  4205 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-31 08:52:07.315  4039  4205 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,08-31 08:52:07.346  4039  4205 I bt_hwcfg: vendor lib fwcfg completed
,08-31 08:52:07.346  4039  4205 I bt_vendor: firmware callback
08-31 08:52:07.347  4039  4205 I bt_hci  : firmware_config_callback
,08-31 08:52:07.358  4039  4207 I bt_btu  : btu_task pending for preload complete event
,08-31 08:52:07.358  4039  4207 I bt_btu_task: Bluetooth chip preload is complete
,08-31 08:52:07.358  4039  4207 I bt_btu  : btu_task received preload complete event
,08-31 08:52:07.372  4039  4207 I         : BTE_InitTraceLevels -- TRC_HCI
,08-31 08:52:07.372  4039  4207 I         : BTE_InitTraceLevels -- TRC_L2CAP
,08-31 08:52:07.372  4039  4207 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-31 08:52:07.373  4039  4207 I         : BTE_InitTraceLevels -- TRC_AVDT
08-31 08:52:07.373  4039  4207 I         : BTE_InitTraceLevels -- TRC_AVRC
,08-31 08:52:07.373  4039  4207 I         : BTE_InitTraceLevels -- TRC_A2D
08-31 08:52:07.374  4039  4207 I         : BTE_InitTraceLevels -- TRC_BNEP
08-31 08:52:07.374  4039  4207 I         : BTE_InitTraceLevels -- TRC_BTM
,08-31 08:52:07.374  4039  4207 I         : BTE_InitTraceLevels -- TRC_GAP
08-31 08:52:07.374  4039  4207 I         : BTE_InitTraceLevels -- TRC_PAN
08-31 08:52:07.375  4039  4207 I         : BTE_InitTraceLevels -- TRC_SDP
08-31 08:52:07.375  4039  4207 I         : BTE_InitTraceLevels -- TRC_GATT
,08-31 08:52:07.375  4039  4207 I         : BTE_InitTraceLevels -- TRC_SMP
08-31 08:52:07.376  4039  4207 I         : BTE_InitTraceLevels -- TRC_BTAPP
,08-31 08:52:07.376  4039  4207 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-31 08:52:07.510  4039  4207 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb3926d9d
,08-31 08:52:07.510  4039  4207 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb3926d9d 
,08-31 08:52:07.522  4039  4199 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,08-31 08:52:07.524  4039  4199 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,08-31 08:52:07.525  4039  4199 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-31 08:52:07.528  4039  4199 D BluetoothAdapterProperties: Name is: Nexus 6
,08-31 08:52:07.534  4039  4199 D BluetoothAdapterProperties: Scan Mode:20
,08-31 08:52:07.538  3868  3868 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 08:52:07.541  4039  4199 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-31 08:52:07.542  4039  4199 D bt_hci  : do_postload posting postload work item
,08-31 08:52:07.543  4039  4205 I bt_hci  : event_postload
,08-31 08:52:07.543  4039  4205 I bt_vendor: sco_config_cb
,08-31 08:52:07.544  4039  4205 I bt_hci  : sco_config_callback postload finished.
,08-31 08:52:07.544  3868  3868 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 08:52:07.546  4039  4199 D bt_bte_conf: Device ID record 1 : primary
,08-31 08:52:07.546  4039  4199 D bt_bte_conf:   vendorId            = 000f
08-31 08:52:07.547  4039  4199 D bt_bte_conf:   vendorIdSource      = 0001
08-31 08:52:07.547  4039  4199 D bt_bte_conf:   product             = 1200
08-31 08:52:07.547  4039  4199 D bt_bte_conf:   version             = 1436
,08-31 08:52:07.547  4039  4199 D bt_bte_conf:   clientExecutableURL = 
08-31 08:52:07.547  4039  4199 D bt_bte_conf:   serviceDescription  = 
08-31 08:52:07.548  4039  4199 D bt_bte_conf:   documentationURL    = 
08-31 08:52:07.548  4039  4199 D bt_bte_conf: bte_load_did_conf no section named DID2.
08-31 08:52:07.549  4039  4205 I bt_vendor: low_power_mode_cb
08-31 08:52:07.548  4039  4196 D bt_stack_manager: event_start_up_stack finished
08-31 08:52:07.549  4039  4195 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
08-31 08:52:07.549  4039  4195 D BluetoothAdapterProperties: Setting state to 15
,08-31 08:52:07.549  4039  4195 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
08-31 08:52:07.551  4039  4195 I BluetoothAdapterState: Entering BleOnState
08-31 08:52:07.552  4039  4195 D BluetoothAdapterState: Current state: BLE ON, message: 1
08-31 08:52:07.552  4039  4195 D BluetoothAdapterProperties: Setting state to 11
08-31 08:52:07.553  4039  4195 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
08-31 08:52:07.558  4039  4039 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4e6af5c
,08-31 08:52:07.562  3868  3868 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 08:52:07.563  3868  3868 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 08:52:07.564  4039  4039 D HeadsetService: Received start request. Starting profile...
,08-31 08:52:07.568  4039  4039 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-31 08:52:07.569  4039  4039 D HeadsetStateMachine: make
,08-31 08:52:07.577  4039  4195 I BluetoothAdapterState: Entering PendingCommandState
08-31 08:52:07.578  4039  4039 D HeadsetStateMachine: max_hf_connections = 1
08-31 08:52:07.578  4039  4039 I bt_bluedroid: get_profile_interface handsfree
,08-31 08:52:07.579  4039  4199 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
,08-31 08:52:07.579  4039  4199 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
,08-31 08:52:07.584  4039  4039 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4e6af5c
,08-31 08:52:07.585  4039  4039 D A2dpService: Received start request. Starting profile...
,08-31 08:52:07.586  4039  4039 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,08-31 08:52:07.586  4039  4039 I bt_bluedroid: get_profile_interface avrcp
,08-31 08:52:07.592  4039  4039 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-31 08:52:07.592  4039  4039 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-31 08:52:07.592  4039  4039 D A2dpStateMachine: make
,08-31 08:52:07.594  4039  4039 I bt_bluedroid: get_profile_interface a2dp
,08-31 08:52:07.594  4039  4199 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,08-31 08:52:07.596  4039  4217 D A2dpStateMachine: Enter Disconnected: -2
,08-31 08:52:07.597  4039  4039 I BluetoothHidServiceJni: classInitNative: succeeds
,08-31 08:52:07.598  4039  4039 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4e6af5c
,08-31 08:52:07.599  4039  4039 D HidService: Received start request. Starting profile...
08-31 08:52:07.599  4039  4039 I bt_bluedroid: get_profile_interface hidhost
,08-31 08:52:07.599  4039  4039 D HidService: setHidService(): set to: null
08-31 08:52:07.599  4039  4199 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb39083e5
08-31 08:52:07.599  4039  4199 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
08-31 08:52:07.600  4039  4039 I BluetoothHealthServiceJni: classInitNative: succeeds
08-31 08:52:07.600  3936  3936 D BluetoothInputDevice: Proxy object connected
,08-31 08:52:07.601  4039  4039 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4e6af5c
,08-31 08:52:07.601  3936  3936 D HidProfile: Bluetooth service connected
08-31 08:52:07.601  4039  4039 D HealthService: Received start request. Starting profile...
,08-31 08:52:07.602  4039  4039 I bt_bluedroid: get_profile_interface health
,08-31 08:52:07.605  1511  1511 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-31 08:52:07.605  4039  4039 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,08-31 08:52:07.606  4039  4039 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4e6af5c
,08-31 08:52:07.607  4039  4039 D PanService: Received start request. Starting profile...
08-31 08:52:07.608  4039  4039 D BluetoothPanServiceJni: initializeNative(L110): pan
,08-31 08:52:07.608  3936  3936 D BluetoothPan: BluetoothPAN Proxy object connected
,08-31 08:52:07.608  4039  4039 I bt_bluedroid: get_profile_interface pan
,08-31 08:52:07.608  4039  4199 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,08-31 08:52:07.610  3936  3936 D PanProfile: Bluetooth service connected
,08-31 08:52:07.611  4039  4039 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4e6af5c
,08-31 08:52:07.612  4039  4039 D BluetoothMapService: Received start request. Starting profile...
,08-31 08:52:07.612  4039  4039 D BluetoothMapService: start()
08-31 08:52:07.612  3936  3936 D BluetoothMap: Proxy object connected
,08-31 08:52:07.613  3936  3936 D MapProfile: Bluetooth service connected
08-31 08:52:07.613  3936  3936 D BluetoothMap: getConnectedDevices()
,08-31 08:52:07.614  3936  3936 D BluetoothMap: Bluetooth is Not enabled
,08-31 08:52:07.614  4039  4039 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
08-31 08:52:07.615  4039  4039 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
,08-31 08:52:07.615  4039  4039 D BluetoothMapAppObserver: createReceiver()
08-31 08:52:07.616  4039  4039 D BluetoothMapAppObserver: initObservers()
,08-31 08:52:07.616  4039  4039 D BluetoothMapAppObserver: getEnabledAccountItems()
,08-31 08:52:07.624  4039  4039 V BluetoothAdapterState: isTurningOff()=false
,08-31 08:52:07.624  4039  4039 V BluetoothAdapterState: isTurningOn()=true
08-31 08:52:07.624  4039  4039 V BluetoothAdapterState: isBleTurningOn()=false
,08-31 08:52:07.624  4039  4039 V BluetoothAdapterState: isBleTurningOff()=false
,08-31 08:52:07.626  4039  4039 V BluetoothAdapterState: isTurningOff()=false
08-31 08:52:07.626  4039  4039 V BluetoothAdapterState: isTurningOn()=true
08-31 08:52:07.626  4039  4039 V BluetoothAdapterState: isBleTurningOn()=false
08-31 08:52:07.626  4039  4039 V BluetoothAdapterState: isBleTurningOff()=false
08-31 08:52:07.626  4039  4039 V BluetoothAdapterState: isTurningOff()=false
,08-31 08:52:07.626  4039  4039 V BluetoothAdapterState: isTurningOn()=true
08-31 08:52:07.626  4039  4039 V BluetoothAdapterState: isBleTurningOn()=false
08-31 08:52:07.626  4039  4213 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-31 08:52:07.626  4039  4039 V BluetoothAdapterState: isBleTurningOff()=false
08-31 08:52:07.627  4039  4039 V BluetoothAdapterState: isTurningOff()=false
,08-31 08:52:07.627  4039  4039 V BluetoothAdapterState: isTurningOn()=true
08-31 08:52:07.627  4039  4039 V BluetoothAdapterState: isBleTurningOn()=false
08-31 08:52:07.627  4039  4039 V BluetoothAdapterState: isBleTurningOff()=false
,08-31 08:52:07.627  4039  4039 V BluetoothAdapterState: isTurningOff()=false
08-31 08:52:07.627  4039  4039 V BluetoothAdapterState: isTurningOn()=true
08-31 08:52:07.627  4039  4039 V BluetoothAdapterState: isBleTurningOn()=false
08-31 08:52:07.627  4039  4039 V BluetoothAdapterState: isBleTurningOff()=false
08-31 08:52:07.628  4039  4039 V BluetoothAdapterState: isTurningOff()=false
08-31 08:52:07.628  4039  4039 V BluetoothAdapterState: isTurningOn()=true
08-31 08:52:07.628  4039  4039 V BluetoothAdapterState: isBleTurningOn()=false
,08-31 08:52:07.628  4039  4039 V BluetoothAdapterState: isBleTurningOff()=false
,08-31 08:52:07.628  4039  4195 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
,08-31 08:52:07.629  4039  4195 D BluetoothAdapterProperties: ScanMode =  20
,08-31 08:52:07.629  4039  4195 D BluetoothAdapterProperties: State =  11
,08-31 08:52:07.631  4039  4199 D BluetoothAdapterProperties: Scan Mode:21
,08-31 08:52:07.631  4039  4199 D BluetoothAdapterProperties: Discoverable Timeout:120
08-31 08:52:07.633  4039  4195 D BluetoothAdapterProperties: Setting state to 12
,08-31 08:52:07.633  4039  4195 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-31 08:52:07.634  3936  3950 D BluetoothPan: onBluetoothStateChange on: true
08-31 08:52:07.634  4039  4195 I BluetoothAdapterState: Entering OnState
08-31 08:52:07.635  1355  2035 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-31 08:52:07.638  3868  3868 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 08:52:07.638  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 08:52:07.638  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 08:52:07.638  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-31 08:52:07.638  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 08:52:07.638  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 08:52:07.638  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 08:52:07.638  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-31 08:52:07.640  3868  3868 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-31 08:52:07.640  1355  1355 D BluetoothInputDevice: Proxy object connected
08-31 08:52:07.640  1355  1355 D HidProfile: Bluetooth service connected
,08-31 08:52:07.641  1355  1385 D BluetoothHeadset: onBluetoothStateChange: up=true
08-31 08:52:07.643   872   889 D BluetoothHeadset: onBluetoothStateChange: up=true
08-31 08:52:07.643   872   889 D BluetoothHeadset: onBluetoothStateChange: up=true
08-31 08:52:07.643  3936  3948 D BluetoothMap: onBluetoothStateChange: up=true
08-31 08:52:07.644  1355  2035 D BluetoothMap: onBluetoothStateChange: up=true
,08-31 08:52:07.644  3868  3868 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 08:52:07.644  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 08:52:07.644  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 08:52:07.644  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-31 08:52:07.644  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 08:52:07.644  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 08:52:07.644  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 08:52:07.644  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-31 08:52:07.645  4039  4039 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,08-31 08:52:07.646  1355  1355 D BluetoothMap: Proxy object connected
08-31 08:52:07.646  1355  1355 D MapProfile: Bluetooth service connected
08-31 08:52:07.646  1355  1355 D BluetoothMap: getConnectedDevices()
08-31 08:52:07.646  4039  4039 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
08-31 08:52:07.646  3868  3868 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-31 08:52:07.647  1355  1385 D BluetoothPbap: onBluetoothStateChange: up=true
,08-31 08:52:07.648  4039  4039 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-31 08:52:07.648  1355  1377 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-31 08:52:07.650  1355  2035 D BluetoothPan: onBluetoothStateChange on: true
,08-31 08:52:07.652  1355  1355 D BluetoothPan: BluetoothPAN Proxy object connected
,08-31 08:52:07.652  1355  1355 D PanProfile: Bluetooth service connected
08-31 08:52:07.652  3936  3950 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-31 08:52:07.652  4039  4039 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-31 08:52:07.652  1971  2189 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-31 08:52:07.653  3936  3948 D BluetoothPbap: onBluetoothStateChange: up=true
08-31 08:52:07.654  4039  4039 D ObexServerSockets: Succeed to create listening sockets 
08-31 08:52:07.654  4039  4039 D ObexServerSockets0: startAccept()
,08-31 08:52:07.654  4039  4039 D ObexServerSockets0: prepareForNewConnect()
08-31 08:52:07.655   872   889 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-31 08:52:07.655   872   889 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-31 08:52:07.656   872   872 I Telecom : BluetoothPhoneService: queryPhoneState
,08-31 08:52:07.658  3868  3868 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 08:52:07.659  4039  4039 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
08-31 08:52:07.660  3868  3868 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 08:52:07.660  4039  4039 D BluetoothSdpJni: SDP Create record success - handle: 0
,08-31 08:52:07.662  3936  3936 D LocalBluetoothProfileManager: Adding local A2DP profile
,08-31 08:52:07.662   872   872 D BluetoothA2dp: Proxy object connected
,08-31 08:52:07.663  4039  4224 D ObexServerSockets0: Accepting socket connection...
,08-31 08:52:07.663  4039  4039 D BluetoothMapService: onReceive
08-31 08:52:07.663  4039  4039 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-31 08:52:07.663  4039  4039 D BluetoothMapService: STATE_ON
08-31 08:52:07.663  1355  1355 D BluetoothA2dp: Proxy object connected
08-31 08:52:07.665  4039  4223 D ObexServerSockets0: Accepting socket connection...
,08-31 08:52:07.674  3936  3936 D LocalBluetoothProfileManager: Adding local HEADSET profile
,08-31 08:52:07.679  3936  3936 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-31 08:52:07.681  3936  3936 D BluetoothA2dp: Proxy object connected
,08-31 08:52:07.683  4039  4039 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,08-31 08:52:07.683  4039  4039 D ObexServerSockets0: prepareForNewConnect()
08-31 08:52:07.685  1511  1511 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-31 08:52:07.695  1355  1355 D BluetoothPbap: Proxy object connected
,08-31 08:52:07.695  1355  1355 D PbapServerProfile: Bluetooth service connected
08-31 08:52:07.696  3936  3936 D DockEventReceiver: finishStartingService: stopping service
08-31 08:52:07.697  3936  3936 D BluetoothPbap: Proxy object connected
,08-31 08:52:07.699  3936  3936 D PbapServerProfile: Bluetooth service connected
,08-31 08:52:07.703  4039  4228 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-31 08:52:07.716  4039  4232 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-31 08:52:07.717  4039  4232 I BtOppRfcommListener: Accept thread started.
,08-31 08:52:07.743  1355  1377 D BluetoothHeadset: Proxy object connected
08-31 08:52:07.743  1355  1355 D HeadsetProfile: Bluetooth service connected
08-31 08:52:07.743   872   872 D BluetoothHeadset: Proxy object connected
08-31 08:52:07.744   872   872 D BluetoothHeadset: Proxy object connected
08-31 08:52:07.744   872   872 D BluetoothHeadset: Proxy object connected
08-31 08:52:07.744   872   889 D BluetoothHeadset: Proxy object connected
08-31 08:52:07.744   872   889 D BluetoothHeadset: Proxy object connected
08-31 08:52:07.744  1971  1983 D BluetoothHeadset: Proxy object connected
,08-31 08:52:07.752  1971  1986 D BluetoothHeadset: Proxy object connected
,08-31 08:52:07.755   872   889 D BluetoothHeadset: Proxy object connected
,08-31 08:52:07.778  3936  3950 D BluetoothHeadset: Proxy object connected
,08-31 08:52:07.779  3936  3936 D HeadsetProfile: Bluetooth service connected
,08-31 08:52:09.233  4039  4195 D BluetoothAdapterState: Current state: ON, message: 23
08-31 08:52:09.234  4039  4195 D BluetoothAdapterProperties: Setting state to 13
,08-31 08:52:09.234  4039  4195 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-31 08:52:09.237   872  1312 D ConnectivityService: handlePromptUnvalidated 101
,08-31 08:52:09.239  4039  4195 D BluetoothAdapterProperties: onBluetoothDisable()
,08-31 08:52:09.241  4039  4195 I BluetoothAdapterState: Entering PendingCommandState
,08-31 08:52:09.244  4039  4199 D BluetoothAdapterProperties: Scan Mode:20
08-31 08:52:09.244  4039  4195 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
,08-31 08:52:09.251  3868  3868 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-31 08:52:09.252  3868  3868 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 08:52:09.252  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 08:52:09.252  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 08:52:09.252  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-31 08:52:09.252  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-31 08:52:09.252  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 08:52:09.252  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 08:52:09.252  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-31 08:52:09.254  3868  3868 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 08:52:09.254  3868  3868 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-31 08:52:09.251  4039  4039 D BluetoothMapService: onReceive
08-31 08:52:09.255  4039  4039 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,08-31 08:52:09.255  4039  4039 D BluetoothMapService: STATE_TURNING_OFF
08-31 08:52:09.256  4039  4039 D BluetoothMapService: MAP Service closeService in
08-31 08:52:09.256  4039  4039 D BluetoothMapMasInstance0: MAP Service shutdown
,08-31 08:52:09.256  4039  4039 D ObexServerSockets0: shutdown(block = true)
08-31 08:52:09.256  4039  4223 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
08-31 08:52:09.256  3868  3868 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 08:52:09.256  3868  3868 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 08:52:09.256  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 08:52:09.256  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 08:52:09.256  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-31 08:52:09.256  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-31 08:52:09.256  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 08:52:09.256  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 08:52:09.256  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-31 08:52:09.257  3868  3868 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-31 08:52:09.258  3868  3868 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-31 08:52:09.258  4039  4039 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-31 08:52:09.258  4039  4224 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
08-31 08:52:09.259  4039  4209 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
,08-31 08:52:09.260  4039  4039 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-31 08:52:09.261  4039  4039 I BtOppRfcommListener: stopping Accept Thread
08-31 08:52:09.261  3868  3868 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 08:52:09.261  4039  4232 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-31 08:52:09.262  4039  4232 I BtOppRfcommListener: BluetoothSocket listen thread finished
,08-31 08:52:09.262  3868  3868 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 08:52:09.262  3936  3936 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-31 08:52:09.263  4039  4039 D HeadsetService: Received stop request...Stopping profile...
,08-31 08:52:09.269  1355  1385 D BluetoothHeadset: Proxy object disconnected
,08-31 08:52:09.269   872   872 D BluetoothHeadset: Proxy object disconnected
08-31 08:52:09.269  3936  3948 D BluetoothHeadset: Proxy object disconnected
08-31 08:52:09.269   872   872 D BluetoothHeadset: Proxy object disconnected
,08-31 08:52:09.269   872   872 D BluetoothHeadset: Proxy object disconnected
,08-31 08:52:09.270  1971  2189 D BluetoothHeadset: Proxy object disconnected
,08-31 08:52:09.270  4039  4039 D A2dpService: Received stop request...Stopping profile...
08-31 08:52:09.271  4039  4217 D A2dpStateMachine: Exit Disconnected: -1
08-31 08:52:09.271   872   872 D BluetoothA2dp: Proxy object disconnected
08-31 08:52:09.272  4039  4039 D HidService: Received stop request...Stopping profile...
08-31 08:52:09.273  4039  4039 D HidService: Stopping Bluetooth HidService
,08-31 08:52:09.274  4039  4039 D HealthService: Received stop request...Stopping profile...
08-31 08:52:09.276  1355  1355 D HeadsetProfile: Bluetooth service disconnected
,08-31 08:52:09.276  1355  1355 D BluetoothA2dp: Proxy object disconnected
08-31 08:52:09.276  1355  1355 D BluetoothInputDevice: Proxy object disconnected
08-31 08:52:09.276  1355  1355 D HidProfile: Bluetooth service disconnected
,08-31 08:52:09.276  3936  3936 D DockEventReceiver: finishStartingService: stopping service
08-31 08:52:09.278  3936  3936 D HeadsetProfile: Bluetooth service disconnected
08-31 08:52:09.278  4039  4039 D PanService: Received stop request...Stopping profile...
08-31 08:52:09.279  3936  3936 D BluetoothA2dp: Proxy object disconnected
,08-31 08:52:09.279  1355  1355 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-31 08:52:09.279  1355  1355 D PanProfile: Bluetooth service disconnected
08-31 08:52:09.279  4039  4039 V BluetoothAdapterState: isTurningOff()=true
,08-31 08:52:09.279  4039  4039 V BluetoothAdapterState: isTurningOn()=false
,08-31 08:52:09.279  4039  4039 V BluetoothAdapterState: isBleTurningOn()=false
08-31 08:52:09.279  4039  4039 V BluetoothAdapterState: isBleTurningOff()=false
,08-31 08:52:09.283  3936  3936 D BluetoothInputDevice: Proxy object disconnected
,08-31 08:52:09.283  3936  3936 D HidProfile: Bluetooth service disconnected
,08-31 08:52:09.284  1511  1511 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-31 08:52:09.284  3936  3936 D BluetoothPan: BluetoothPAN Proxy object disconnected
,08-31 08:52:09.284  3936  3936 D PanProfile: Bluetooth service disconnected
08-31 08:52:09.285  4039  4039 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...,
08-31 08:52:09.286  4039  4199 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
08-31 08:52:09.286  4039  4207 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-31 08:52:09.286  4039  4039 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-31 08:52:09.286  4039  4207 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-31 08:52:09.286  4039  4207 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-31 08:52:09.286  4039  4199 E bt_btif : btif_hf_upstreams_evt: Invalid index 11885
08-31 08:52:09.287  4039  4039 D BluetoothMapService: Received stop request...Stopping profile...
08-31 08:52:09.287  4039  4039 D BluetoothMapService: stop()
08-31 08:52:09.287  4039  4039 D BluetoothMapAppObserver: deinitObservers()
08-31 08:52:09.287  4039  4039 D BluetoothMapAppObserver: removeReceiver()
,08-31 08:52:09.289  4039  4039 V BluetoothAdapterState: isTurningOff()=true
08-31 08:52:09.289  1355  1355 D BluetoothMap: Proxy object disconnected
,08-31 08:52:09.289  1355  1355 D MapProfile: Bluetooth service disconnected
08-31 08:52:09.289  4039  4039 V BluetoothAdapterState: isTurningOn()=false
08-31 08:52:09.289  4039  4039 V BluetoothAdapterState: isBleTurningOn()=false
08-31 08:52:09.289  4039  4039 V BluetoothAdapterState: isBleTurningOff()=false
08-31 08:52:09.289  3936  3936 D BluetoothMap: Proxy object disconnected
,08-31 08:52:09.289  3936  3936 D MapProfile: Bluetooth service disconnected
08-31 08:52:09.291  4039  4199 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
08-31 08:52:09.291  4039  4207 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-31 08:52:09.291  4039  4207 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-31 08:52:09.291  4039  4207 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-31 08:52:09.291  4039  4207 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,08-31 08:52:09.291  4039  4207 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-31 08:52:09.291  4039  4207 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-31 08:52:09.291  4039  4039 V BluetoothAdapterState: isTurningOff()=true
08-31 08:52:09.291  4039  4039 V BluetoothAdapterState: isTurningOn()=false
08-31 08:52:09.292  4039  4039 V BluetoothAdapterState: isBleTurningOn()=false
08-31 08:52:09.292  4039  4039 V BluetoothAdapterState: isBleTurningOff()=false
,08-31 08:52:09.292  4039  4039 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-31 08:52:09.292  4039  4199 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
08-31 08:52:09.292  4039  4039 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
,08-31 08:52:09.292  4039  4039 V BluetoothAdapterState: isTurningOff()=true
08-31 08:52:09.293  4039  4039 V BluetoothAdapterState: isTurningOn()=false
08-31 08:52:09.293  4039  4039 V BluetoothAdapterState: isBleTurningOn()=false
08-31 08:52:09.293  4039  4039 V BluetoothAdapterState: isBleTurningOff()=false
08-31 08:52:09.293  4039  4039 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
,08-31 08:52:09.293  4039  4199 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
08-31 08:52:09.293  4039  4039 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-31 08:52:09.294  4039  4039 V BluetoothAdapterState: isTurningOff()=true
08-31 08:52:09.294  4039  4039 V BluetoothAdapterState: isTurningOn()=false
08-31 08:52:09.294  4039  4039 V BluetoothAdapterState: isBleTurningOn()=false
08-31 08:52:09.294  4039  4039 V BluetoothAdapterState: isBleTurningOff()=false
08-31 08:52:09.294  4039  4039 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
,08-31 08:52:09.294  4039  4039 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
,08-31 08:52:09.296  1355  1355 D BluetoothPbap: Proxy object disconnected
,08-31 08:52:09.297  1355  1355 D PbapServerProfile: Bluetooth service disconnected
08-31 08:52:09.297  3936  3936 D BluetoothPbap: Proxy object disconnected
,08-31 08:52:09.297  3936  3936 D PbapServerProfile: Bluetooth service disconnected
,08-31 08:52:09.299  4039  4039 D BluetoothMapService: MAP Service closeService in
,08-31 08:52:09.299  4039  4039 V BluetoothAdapterState: isTurningOff()=true
08-31 08:52:09.299  4039  4039 V BluetoothAdapterState: isTurningOn()=false
08-31 08:52:09.299  4039  4039 V BluetoothAdapterState: isBleTurningOn()=false
08-31 08:52:09.299  4039  4039 V BluetoothAdapterState: isBleTurningOff()=false
08-31 08:52:09.299  4039  4195 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
08-31 08:52:09.300  4039  4195 D BluetoothAdapterProperties: Setting state to 15
,08-31 08:52:09.300  4039  4195 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
08-31 08:52:09.300  4039  4195 I BluetoothAdapterState: Entering BleOnState
,08-31 08:52:09.300  3936  3950 D BluetoothPan: onBluetoothStateChange on: false
08-31 08:52:09.301  4039  4039 D BluetoothMapService: cleanup()
,08-31 08:52:09.301  4039  4039 D BluetoothMapService: MAP Service closeService in
08-31 08:52:09.301  1355  2035 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-31 08:52:09.303  1355  1385 D BluetoothHeadset: onBluetoothStateChange: up=false
08-31 08:52:09.303   872   889 D BluetoothHeadset: onBluetoothStateChange: up=false
08-31 08:52:09.303   872   889 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-31 08:52:09.304  3936  3948 D BluetoothA2dp: onBluetoothStateChange: up=false
08-31 08:52:09.304  3936  3950 D BluetoothMap: onBluetoothStateChange: up=false
08-31 08:52:09.305  1355  1377 D BluetoothMap: onBluetoothStateChange: up=false
08-31 08:52:09.305  1355  2035 D BluetoothPbap: onBluetoothStateChange: up=false
,08-31 08:52:09.306  3936  3948 D BluetoothHeadset: onBluetoothStateChange: up=false
08-31 08:52:09.306  1355  1385 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-31 08:52:09.307  1355  1377 D BluetoothPan: onBluetoothStateChange on: false
,08-31 08:52:09.307  3936  3950 D BluetoothInputDevice: onBluetoothStateChange: up=false
,08-31 08:52:09.308  1971  1983 D BluetoothHeadset: onBluetoothStateChange: up=false
08-31 08:52:09.308  3936  3948 D BluetoothPbap: onBluetoothStateChange: up=false
,08-31 08:52:09.309   872   889 D BluetoothA2dp: onBluetoothStateChange: up=false
08-31 08:52:09.309   872   889 D BluetoothHeadset: onBluetoothStateChange: up=false
08-31 08:52:09.309  4039  4195 D BluetoothAdapterState: Current state: BLE ON, message: 20
08-31 08:52:09.309  4039  4195 D BluetoothAdapterProperties: Setting state to 16
08-31 08:52:09.309  4039  4195 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
,08-31 08:52:09.310  4039  4195 D BluetoothAdapterProperties: onBleDisable
,08-31 08:52:09.310  4039  4195 I BluetoothAdapterState: Entering PendingCommandState
08-31 08:52:09.310  4039  4196 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
08-31 08:52:09.311  4039  4207 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
08-31 08:52:09.311  4039  4207 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-31 08:52:09.314  3868  3868 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 08:52:09.315  3868  3868 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 08:52:09.316  4039  4199 D BluetoothAdapterProperties: Scan Mode:20
,08-31 08:52:09.317  3868  3868 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 08:52:09.317  3936  3936 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-31 08:52:09.319  3868  3868 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 08:52:09.322  1511  1511 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-31 08:52:09.326  3936  3936 D DockEventReceiver: finishStartingService: stopping service
,08-31 08:52:09.512  4039  4199 I bt_hci  : shut_down
,08-31 08:52:09.522  4039  4205 D bt_hwcfg: hw_epilog_process
,08-31 08:52:09.522  4039  4205 I bt_vendor: low_power_mode_cb
,08-31 08:52:09.539  4039  4205 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
08-31 08:52:09.539  4039  4205 I bt_vendor: epilog_cb
08-31 08:52:09.539  4039  4205 I bt_hci  : epilog_finished_callback
,08-31 08:52:09.547  4039  4199 I bt_hci_h4: hal_close
,08-31 08:52:09.549  4039  4199 I bt_userial_vendor: device fd = 51 close
,08-31 08:52:09.674  4039  4196 D bt_stack_manager: event_shut_down_stack finished.
,08-31 08:52:09.675  4039  4195 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,08-31 08:52:09.681  4039  4039 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-31 08:52:09.682  4039  4195 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,08-31 08:52:09.683  4039  4039 D BtGatt.GattService: Received stop request...Stopping profile...
,08-31 08:52:09.683  4039  4039 D BtGatt.GattService: stop()
,08-31 08:52:09.685  4039  4039 D BtGatt.AdvertiseManager: advertise clients cleared
,08-31 08:52:09.696  4039  4039 V BluetoothAdapterState: isTurningOff()=false
08-31 08:52:09.696  4039  4039 V BluetoothAdapterState: isTurningOn()=false
08-31 08:52:09.696  4039  4039 V BluetoothAdapterState: isBleTurningOn()=false
08-31 08:52:09.697  4039  4039 V BluetoothAdapterState: isBleTurningOff()=true
08-31 08:52:09.698  4039  4195 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
08-31 08:52:09.698  4039  4195 D BluetoothAdapterProperties: Setting state to 10
08-31 08:52:09.699  4039  4195 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
08-31 08:52:09.700  4039  4195 I BluetoothAdapterState: Entering OffState
08-31 08:52:09.702   872   889 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,08-31 08:52:09.741  4039  4039 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,08-31 08:52:09.741  4039  4039 W BluetoothSdpJni: Cleaning up Bluetooth Health object
08-31 08:52:09.741  4039  4196 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,08-31 08:52:09.743  4039  4196 D bt_stack_manager: event_clean_up_stack finished.
08-31 08:52:09.744  4039  4039 I BluetoothServiceJni: cleanupNative: return from cleanup
08-31 08:52:09.747  4039  4039 I art     : System.exit called, status: 0
,08-31 08:52:09.747  4039  4039 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-31 08:52:09.795   872  2076 I ActivityManager: Process com.android.bluetooth (pid 4039) has died
,08-31 08:52:12.228  3868  3918 D io.jxcore.node.ConnectivityMonitor: stop
,08-31 08:52:12.228  3868  3918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-31 08:52:15.236  3868  3918 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-31 08:52:15.237  3868  3918 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@30b1a52 added. We now have 6 listener(s)
08-31 08:52:15.237  3868  3918 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-31 08:52:15.242  3868  3918 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-31 08:52:15.243  3868  3918 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@b2b6123 added. We now have 7 listener(s)
08-31 08:52:15.243  3868  3918 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-31 08:52:15.245  3868  3918 I System.out: IsBluetoothEnabled
,08-31 08:52:15.257  3868  3918 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 08:52:15.310   872   889 I ActivityManager: Start proc 4243:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,08-31 08:52:15.436  4243  4243 D AdapterServiceConfig: Adding HeadsetService
08-31 08:52:15.436  4243  4243 D AdapterServiceConfig: Adding A2dpService
08-31 08:52:15.436  4243  4243 D AdapterServiceConfig: Adding HidService
,08-31 08:52:15.437  4243  4243 D AdapterServiceConfig: Adding HealthService
08-31 08:52:15.437  4243  4243 D AdapterServiceConfig: Adding PanService
08-31 08:52:15.437  4243  4243 D AdapterServiceConfig: Adding GattService
08-31 08:52:15.437  4243  4243 D AdapterServiceConfig: Adding BluetoothMapService
,08-31 08:52:15.457   872   889 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@759706d:true
,08-31 08:52:15.457  4243  4243 D BluetoothAdapterState: make() - Creating AdapterState
,08-31 08:52:15.463  4243  4243 I bt_bluedroid: init
,08-31 08:52:15.463  4243  4255 I BluetoothAdapterState: Entering OffState
,08-31 08:52:15.466  4243  4256 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
08-31 08:52:15.466  4243  4256 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
,08-31 08:52:15.466  4243  4256 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-31 08:52:15.466  4243  4256 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
08-31 08:52:15.467  4243  4243 I bt_bluedroid: get_profile_interface socket
08-31 08:52:15.469  4243  4243 I bt_bluedroid: get_profile_interface sdp
,08-31 08:52:15.475  4243  4254 I bt_bluedroid: config_hci_snoop_log
,08-31 08:52:15.475  4243  4259 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-31 08:52:15.478   872   889 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
08-31 08:52:15.478  4243  4259 D BluetoothAdapterProperties: Name is: Nexus 6
,08-31 08:52:15.490  4243  4255 D BluetoothAdapterState: Current state: OFF, message: 0
,08-31 08:52:15.490  4243  4255 D BluetoothAdapterProperties: Setting state to 14
08-31 08:52:15.491  4243  4255 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,08-31 08:52:15.496  4243  4255 D BluetoothBondStateMachine: make
,08-31 08:52:15.500  4243  4260 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-31 08:52:15.507  4243  4255 I BluetoothAdapterState: Entering PendingCommandState
,08-31 08:52:15.508  4243  4243 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,08-31 08:52:15.512  4243  4243 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4e6af5c
,08-31 08:52:15.512  4243  4243 D BtGatt.DebugUtils: handleDebugAction() action=null
08-31 08:52:15.513  4243  4243 D BtGatt.GattService: Received start request. Starting profile...
,08-31 08:52:15.513  4243  4243 D BtGatt.GattService: start()
08-31 08:52:15.513  4243  4243 I bt_bluedroid: get_profile_interface gatt
,08-31 08:52:15.514  4243  4243 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4e6af5c
08-31 08:52:15.514  4243  4243 D BtGatt.AdvertiseManager: advertise manager created
,08-31 08:52:15.526  4243  4243 V BluetoothAdapterState: isTurningOff()=false
08-31 08:52:15.526  4243  4243 V BluetoothAdapterState: isTurningOn()=false
,08-31 08:52:15.526  4243  4243 V BluetoothAdapterState: isBleTurningOn()=true
08-31 08:52:15.526  4243  4243 V BluetoothAdapterState: isBleTurningOff()=false
,08-31 08:52:15.527  4243  4255 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,08-31 08:52:15.528  4243  4255 I bt_bluedroid: enable
08-31 08:52:15.528  4243  4256 D bt_stack_manager: event_start_up_stack is bringing up the stack.
08-31 08:52:15.529  4243  4256 I bt_hci  : start_up
,08-31 08:52:15.546  4243  4256 I bt_vendor: alloc value 0xb3a02189
,08-31 08:52:15.546  4243  4256 I bt_vendor: init
08-31 08:52:15.546  4243  4256 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
08-31 08:52:15.546  4243  4256 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,08-31 08:52:15.656  4243  4256 D bt_hci  : start_up starting async portion
,08-31 08:52:15.657  4243  4263 I bt_hci  : event_finish_startup
08-31 08:52:15.657  4243  4263 I bt_hci_h4: hal_open
,08-31 08:52:15.658  4243  4263 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,08-31 08:52:15.670  4243  4263 I bt_userial_vendor: device fd = 51 open
,08-31 08:52:15.698  4243  4263 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-31 08:52:15.730  4243  4263 D bt_hwcfg: Chipset BCM4354A2
,08-31 08:52:15.730  4243  4263 D bt_hwcfg: Target name = [BCM4354A2]
,08-31 08:52:15.731  4243  4263 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,08-31 08:52:15.985   872   892 I PowerManagerService: Going to sleep due to screen timeout (uid 1000)...
,08-31 08:52:15.994  1884  1884 I Keyboard.Facilitator: onFinishInput()
,08-31 08:52:16.002   872   892 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-31 08:52:16.002   872   892 I Adreno  : Build Date                       : 10/20/15
08-31 08:52:16.002   872   892 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-31 08:52:16.002   872   892 I Adreno  : Local Branch                     : M14
08-31 08:52:16.002   872   892 I Adreno  : Remote Branch                    : 
08-31 08:52:16.002   872   892 I Adreno  : Remote Branch                    : 
08-31 08:52:16.002   872   892 I Adreno  : Reconstruct Branch               : 
,08-31 08:52:16.064   281   682 D PermissionCache: checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (211 us)
,08-31 08:52:16.307  4243  4263 I bt_hwcfg: bt vendor lib: set UART baud 115200
,08-31 08:52:16.308  4243  4263 D bt_hwcfg: Settlement delay -- 100 ms
,08-31 08:52:16.309  4243  4263 I bt_hwcfg: Setting fw settlement delay to 100 
,08-31 08:52:16.426  4243  4263 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-31 08:52:16.427  4243  4263 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,08-31 08:52:16.458  4243  4263 I bt_hwcfg: vendor lib fwcfg completed
08-31 08:52:16.458  4243  4263 I bt_vendor: firmware callback
,08-31 08:52:16.458  4243  4263 I bt_hci  : firmware_config_callback
,08-31 08:52:16.469  4243  4267 I bt_btu  : btu_task pending for preload complete event
,08-31 08:52:16.470  4243  4267 I bt_btu_task: Bluetooth chip preload is complete
,08-31 08:52:16.470  4243  4267 I bt_btu  : btu_task received preload complete event
,08-31 08:52:16.479  4243  4267 I         : BTE_InitTraceLevels -- TRC_HCI
,08-31 08:52:16.480  4243  4267 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-31 08:52:16.480  4243  4267 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,08-31 08:52:16.480  4243  4267 I         : BTE_InitTraceLevels -- TRC_AVDT
,08-31 08:52:16.481  4243  4267 I         : BTE_InitTraceLevels -- TRC_AVRC
08-31 08:52:16.481  4243  4267 I         : BTE_InitTraceLevels -- TRC_A2D
,08-31 08:52:16.481  4243  4267 I         : BTE_InitTraceLevels -- TRC_BNEP
08-31 08:52:16.482  4243  4267 I         : BTE_InitTraceLevels -- TRC_BTM
08-31 08:52:16.482  4243  4267 I         : BTE_InitTraceLevels -- TRC_GAP
08-31 08:52:16.482  4243  4267 I         : BTE_InitTraceLevels -- TRC_PAN
08-31 08:52:16.482  4243  4267 I         : BTE_InitTraceLevels -- TRC_SDP
08-31 08:52:16.482  4243  4267 I         : BTE_InitTraceLevels -- TRC_GATT
,08-31 08:52:16.483  4243  4267 I         : BTE_InitTraceLevels -- TRC_SMP
08-31 08:52:16.483  4243  4267 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-31 08:52:16.483  4243  4267 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-31 08:52:16.627  4243  4267 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb397fd9d
,08-31 08:52:16.627  4243  4267 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb397fd9d 
,08-31 08:52:16.647  4243  4259 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
08-31 08:52:16.648  4243  4259 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,08-31 08:52:16.649  4243  4259 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-31 08:52:16.687  3868  3868 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,08-31 08:52:16.688  3868  3868 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,08-31 08:52:16.729   872   892 V KeyguardServiceDelegate: onScreenTurnedOff()
,08-31 08:52:16.730  4243  4259 D BluetoothAdapterProperties: Name is: Nexus 6
,08-31 08:52:16.734  3868  3868 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@edd6548 Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@d233620, 16908290=android.view.AbsSavedState$1@d233620}, android:focusedViewId=100}]}]
,08-31 08:52:16.734  3868  3868 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
,08-31 08:52:16.734  3868  3868 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
08-31 08:52:16.735  3868  3868 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
08-31 08:52:16.739  4243  4259 D BluetoothAdapterProperties: Scan Mode:20
08-31 08:52:16.739  4243  4259 D BluetoothAdapterProperties: Discoverable Timeout:120
08-31 08:52:16.739  4243  4259 D bt_hci  : do_postload posting postload work item
08-31 08:52:16.739  4243  4263 I bt_hci  : event_postload
,08-31 08:52:16.739  4243  4263 I bt_vendor: sco_config_cb
08-31 08:52:16.739  4243  4263 I bt_hci  : sco_config_callback postload finished.
08-31 08:52:16.741  3868  3868 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 08:52:16.741  4243  4263 I bt_vendor: low_power_mode_cb
,08-31 08:52:16.741  4243  4259 D bt_bte_conf: Device ID record 1 : primary
08-31 08:52:16.741  4243  4259 D bt_bte_conf:   vendorId            = 000f
08-31 08:52:16.742  4243  4259 D bt_bte_conf:   vendorIdSource      = 0001
08-31 08:52:16.742  4243  4259 D bt_bte_conf:   product             = 1200
08-31 08:52:16.742  4243  4259 D bt_bte_conf:   version             = 1436
08-31 08:52:16.742  4243  4259 D bt_bte_conf:   clientExecutableURL = 
08-31 08:52:16.742  4243  4259 D bt_bte_conf:   serviceDescription  = 
08-31 08:52:16.742  4243  4259 D bt_bte_conf:   documentationURL    = 
08-31 08:52:16.742  4243  4259 D bt_bte_conf: bte_load_did_conf no section named DID2.
08-31 08:52:16.742  4243  4256 D bt_stack_manager: event_start_up_stack finished
08-31 08:52:16.742  4243  4255 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
08-31 08:52:16.742   872   892 E libEGL  : call to OpenGL ES API with no current context (logged once per thread)
08-31 08:52:16.743  4243  4255 D BluetoothAdapterProperties: Setting state to 15
08-31 08:52:16.743  4243  4255 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
08-31 08:52:16.746  4243  4255 I BluetoothAdapterState: Entering BleOnState
08-31 08:52:16.749   281   281 D SurfaceFlinger: Set power mode=0, type=0 flinger=0xb6b24000
08-31 08:52:16.749   281   281 D qdhwcomposer: hwc_setPowerMode: Setting mode 0 on display: 0
08-31 08:52:16.749  4243  4255 D BluetoothAdapterState: Current state: BLE ON, message: 1
08-31 08:52:16.749  4243  4255 D BluetoothAdapterProperties: Setting state to 11
08-31 08:52:16.749  4243  4255 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
08-31 08:52:16.749   872   890 I DisplayManagerService: Display device changed state: "Built-in Screen", OFF
,08-31 08:52:16.753  3868  3868 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 08:52:16.756  4243  4243 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4e6af5c
,08-31 08:52:16.756  4243  4243 D HeadsetService: Received start request. Starting profile...
,08-31 08:52:16.759  4243  4243 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-31 08:52:16.759  4243  4243 D HeadsetStateMachine: make
,08-31 08:52:16.766  4243  4255 I BluetoothAdapterState: Entering PendingCommandState
,08-31 08:52:16.767  4243  4243 D HeadsetStateMachine: max_hf_connections = 1
,08-31 08:52:16.767  4243  4243 I bt_bluedroid: get_profile_interface handsfree
,08-31 08:52:16.767  4243  4259 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
08-31 08:52:16.767  4243  4259 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
08-31 08:52:16.771  1511  1511 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-31 08:52:16.771  4243  4243 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4e6af5c
08-31 08:52:16.771  4243  4243 D A2dpService: Received start request. Starting profile...
,08-31 08:52:16.772  4243  4243 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-31 08:52:16.772  4243  4243 I bt_bluedroid: get_profile_interface avrcp
,08-31 08:52:16.778  4243  4243 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-31 08:52:16.778  4243  4243 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-31 08:52:16.778  4243  4243 D A2dpStateMachine: make
,08-31 08:52:16.779  4243  4243 I bt_bluedroid: get_profile_interface a2dp
08-31 08:52:16.779  4243  4259 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,08-31 08:52:16.783  4243  4278 D A2dpStateMachine: Enter Disconnected: -2
,08-31 08:52:16.784  4243  4243 I BluetoothHidServiceJni: classInitNative: succeeds
,08-31 08:52:16.784  4243  4243 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4e6af5c
,08-31 08:52:16.785  4243  4243 D HidService: Received start request. Starting profile...
08-31 08:52:16.785  4243  4243 I bt_bluedroid: get_profile_interface hidhost
08-31 08:52:16.785  4243  4243 D HidService: setHidService(): set to: null
08-31 08:52:16.785  4243  4259 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb39613e5
,08-31 08:52:16.785  4243  4259 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
08-31 08:52:16.786  4243  4243 I BluetoothHealthServiceJni: classInitNative: succeeds
,08-31 08:52:16.786  4243  4243 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4e6af5c
08-31 08:52:16.787  4243  4243 D HealthService: Received start request. Starting profile...
,08-31 08:52:16.788  4243  4243 I bt_bluedroid: get_profile_interface health
,08-31 08:52:16.788  4243  4243 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,08-31 08:52:16.789  4243  4243 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4e6af5c
,08-31 08:52:16.789  4243  4243 D PanService: Received start request. Starting profile...
08-31 08:52:16.789  4243  4243 D BluetoothPanServiceJni: initializeNative(L110): pan
08-31 08:52:16.789  4243  4243 I bt_bluedroid: get_profile_interface pan
,08-31 08:52:16.790  4243  4259 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,08-31 08:52:16.796  4243  4243 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4e6af5c
,08-31 08:52:16.796  4243  4243 D BluetoothMapService: Received start request. Starting profile...
,08-31 08:52:16.796  4243  4243 D BluetoothMapService: start()
,08-31 08:52:16.798  4243  4243 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
08-31 08:52:16.798  4243  4243 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
,08-31 08:52:16.798  4243  4243 D BluetoothMapAppObserver: createReceiver()
08-31 08:52:16.799  4243  4243 D BluetoothMapAppObserver: initObservers()
,08-31 08:52:16.799  4243  4243 D BluetoothMapAppObserver: getEnabledAccountItems()
,08-31 08:52:16.803  4243  4243 V BluetoothAdapterState: isTurningOff()=false
,08-31 08:52:16.803  4243  4243 V BluetoothAdapterState: isTurningOn()=true
08-31 08:52:16.803  4243  4243 V BluetoothAdapterState: isBleTurningOn()=false
,08-31 08:52:16.803  4243  4243 V BluetoothAdapterState: isBleTurningOff()=false
08-31 08:52:16.803  4243  4275 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,08-31 08:52:16.806  4243  4243 V BluetoothAdapterState: isTurningOff()=false
,08-31 08:52:16.806  4243  4243 V BluetoothAdapterState: isTurningOn()=true
,08-31 08:52:16.806  4243  4243 V BluetoothAdapterState: isBleTurningOn()=false
,08-31 08:52:16.806  4243  4243 V BluetoothAdapterState: isBleTurningOff()=false,
08-31 08:52:16.807  4243  4243 V BluetoothAdapterState: isTurningOff()=false
,08-31 08:52:16.807  4243  4243 V BluetoothAdapterState: isTurningOn()=true
08-31 08:52:16.807  4243  4243 V BluetoothAdapterState: isBleTurningOn()=false
08-31 08:52:16.807  4243  4243 V BluetoothAdapterState: isBleTurningOff()=false
08-31 08:52:16.807  4243  4243 V BluetoothAdapterState: isTurningOff()=false
08-31 08:52:16.807  4243  4243 V BluetoothAdapterState: isTurningOn()=true
08-31 08:52:16.807  4243  4243 V BluetoothAdapterState: isBleTurningOn()=false
08-31 08:52:16.807  4243  4243 V BluetoothAdapterState: isBleTurningOff()=false
08-31 08:52:16.807  4243  4243 V BluetoothAdapterState: isTurningOff()=false
08-31 08:52:16.807  4243  4243 V BluetoothAdapterState: isTurningOn()=true
08-31 08:52:16.807  4243  4243 V BluetoothAdapterState: isBleTurningOn()=false
08-31 08:52:16.807  4243  4243 V BluetoothAdapterState: isBleTurningOff()=false
08-31 08:52:16.808  4243  4243 V BluetoothAdapterState: isTurningOff()=false
,08-31 08:52:16.808  4243  4243 V BluetoothAdapterState: isTurningOn()=true
08-31 08:52:16.808  4243  4243 V BluetoothAdapterState: isBleTurningOn()=false
08-31 08:52:16.808  4243  4243 V BluetoothAdapterState: isBleTurningOff()=false
08-31 08:52:16.808  4243  4255 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
08-31 08:52:16.808  4243  4255 D BluetoothAdapterProperties: ScanMode =  20
,08-31 08:52:16.808  4243  4255 D BluetoothAdapterProperties: State =  11
08-31 08:52:16.809  4243  4259 D BluetoothAdapterProperties: Scan Mode:21
08-31 08:52:16.810  4243  4259 D BluetoothAdapterProperties: Discoverable Timeout:120
08-31 08:52:16.811  4243  4255 D BluetoothAdapterProperties: Setting state to 12
08-31 08:52:16.811  4243  4255 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-31 08:52:16.811  3868  3868 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 08:52:16.812  4243  4255 I BluetoothAdapterState: Entering OnState
08-31 08:52:16.812  3936  3950 D BluetoothPan: onBluetoothStateChange on: true
08-31 08:52:16.815  1355  1377 D BluetoothInputDevice: onBluetoothStateChange: up=true
,08-31 08:52:16.818  1355  2035 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-31 08:52:16.818  3936  3936 D BluetoothPan: BluetoothPAN Proxy object connected
08-31 08:52:16.818  3936  3936 D PanProfile: Bluetooth service connected
08-31 08:52:16.818  1355  1355 D BluetoothInputDevice: Proxy object connected
08-31 08:52:16.818   872   889 D BluetoothHeadset: onBluetoothStateChange: up=true
08-31 08:52:16.818  1355  1355 D HidProfile: Bluetooth service connected
08-31 08:52:16.819   872   889 D BluetoothHeadset: onBluetoothStateChange: up=true
08-31 08:52:16.819  3936  3950 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-31 08:52:16.821  3936  3948 D BluetoothMap: onBluetoothStateChange: up=true
,08-31 08:52:16.823  4243  4243 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,08-31 08:52:16.824  1355  1377 D BluetoothMap: onBluetoothStateChange: up=true
08-31 08:52:16.824  4243  4243 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
,08-31 08:52:16.825  3936  3936 D BluetoothA2dp: Proxy object connected
,08-31 08:52:16.825  1355  4273 D BluetoothPbap: onBluetoothStateChange: up=true
08-31 08:52:16.827  3936  3950 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-31 08:52:16.827  1355  1385 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-31 08:52:16.827  4243  4243 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-31 08:52:16.829  1355  1355 D BluetoothA2dp: Proxy object connected
08-31 08:52:16.829  1355  1377 D BluetoothPan: onBluetoothStateChange on: true
08-31 08:52:16.830  1355  1355 D BluetoothPan: BluetoothPAN Proxy object connected
08-31 08:52:16.830  1355  1355 D PanProfile: Bluetooth service connected
08-31 08:52:16.830  3936  3948 D BluetoothInputDevice: onBluetoothStateChange: up=true
,08-31 08:52:16.830  4243  4243 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-31 08:52:16.832  1971  2189 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-31 08:52:16.832  4243  4243 D ObexServerSockets: Succeed to create listening sockets 
08-31 08:52:16.833  3936  3950 D BluetoothPbap: onBluetoothStateChange: up=true
08-31 08:52:16.833  4243  4243 D ObexServerSockets0: startAccept()
08-31 08:52:16.833  4243  4243 D ObexServerSockets0: prepareForNewConnect()
,08-31 08:52:16.834   872   889 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-31 08:52:16.835   872   889 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-31 08:52:16.835   872   872 D BluetoothA2dp: Proxy object connected
08-31 08:52:16.838   872   872 I Telecom : BluetoothPhoneService: queryPhoneState
08-31 08:52:16.839  4243  4243 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
08-31 08:52:16.839  4243  4243 D BluetoothSdpJni: SDP Create record success - handle: 0
,08-31 08:52:16.840  3868  3868 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 08:52:16.840  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 08:52:16.840  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 08:52:16.840  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-31 08:52:16.840  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 08:52:16.840  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 08:52:16.840  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 08:52:16.840  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-31 08:52:16.840  4243  4286 D ObexServerSockets0: Accepting socket connection...
08-31 08:52:16.841  3936  3936 D BluetoothInputDevice: Proxy object connected
08-31 08:52:16.841  3936  3936 D HidProfile: Bluetooth service connected
,08-31 08:52:16.841  1355  1355 D BluetoothMap: Proxy object connected
08-31 08:52:16.841  1355  1355 D MapProfile: Bluetooth service connected
08-31 08:52:16.841  1355  1355 D BluetoothMap: getConnectedDevices()
08-31 08:52:16.841  4243  4243 D BluetoothMapService: onReceive
08-31 08:52:16.841  4243  4243 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,08-31 08:52:16.841  4243  4243 D BluetoothMapService: STATE_ON
08-31 08:52:16.842  3868  3868 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-31 08:52:16.844  4243  4285 D ObexServerSockets0: Accepting socket connection...
,08-31 08:52:16.849  3936  3936 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-31 08:52:16.851  3936  3936 D BluetoothMap: Proxy object connected
,08-31 08:52:16.851  3936  3936 D MapProfile: Bluetooth service connected
,08-31 08:52:16.852  3936  3936 D BluetoothMap: getConnectedDevices()
,08-31 08:52:16.858  1511  1511 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-31 08:52:16.860  3936  3936 D DockEventReceiver: finishStartingService: stopping service
,08-31 08:52:16.870  3936  3936 D BluetoothPbap: Proxy object connected
,08-31 08:52:16.870  3936  3936 D PbapServerProfile: Bluetooth service connected
08-31 08:52:16.870  1355  1355 D BluetoothPbap: Proxy object connected
08-31 08:52:16.870  1355  1355 D PbapServerProfile: Bluetooth service connected
,08-31 08:52:16.875  4243  4243 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,08-31 08:52:16.876  4243  4243 D ObexServerSockets0: prepareForNewConnect()
,08-31 08:52:16.878  4243  4291 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-31 08:52:16.892  4243  4295 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-31 08:52:16.894  4243  4295 I BtOppRfcommListener: Accept thread started.
,08-31 08:52:16.920  1355  2035 D BluetoothHeadset: Proxy object connected
,08-31 08:52:16.920  1355  1355 D HeadsetProfile: Bluetooth service connected
08-31 08:52:16.920   872   872 D BluetoothHeadset: Proxy object connected
,08-31 08:52:16.921  3936  4283 D BluetoothHeadset: Proxy object connected
,08-31 08:52:16.922  3936  3936 D HeadsetProfile: Bluetooth service connected
08-31 08:52:16.922   872   872 D BluetoothHeadset: Proxy object connected
08-31 08:52:16.922   872   872 D BluetoothHeadset: Proxy object connected
,08-31 08:52:16.923  1971  1983 D BluetoothHeadset: Proxy object connected
,08-31 08:52:16.928  3936  3950 D BluetoothHeadset: Proxy object connected
,08-31 08:52:16.928  3936  3936 D HeadsetProfile: Bluetooth service connected
,08-31 08:52:16.933  1971  1986 D BluetoothHeadset: Proxy object connected
,08-31 08:52:16.936   872   889 D BluetoothHeadset: Proxy object connected
,08-31 08:52:16.973   281   337 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0
,08-31 08:52:16.975   281   281 D qdhwcomposer: hwc_setPowerMode: Done setting mode 0 on display 0
,08-31 08:52:16.983   872  1336 D SurfaceControl: Excessive delay in setPowerMode(): 235ms
,08-31 08:52:16.986   872   892 I DreamManagerService: Entering dreamland.
,08-31 08:52:16.987   872   892 I PowerManagerService: Dozing...
,08-31 08:52:16.988   872   887 I DreamController: Starting dream: name=ComponentInfo{com.android.systemui/com.android.systemui.doze.DozeService}, isTest=false, canDoze=true, userId=0
,08-31 08:52:17.019   375  1318 D audio_hw_primary: adev_set_parameters: enter: screen_state=on
08-31 08:52:17.019   375  1318 D mot_vr_audio_hw: adev_set_parameters: screen_state=on
,08-31 08:52:17.026   872  1310 D WifiConfigStore: Retrieve network priorities after PNO.
,08-31 08:52:17.028   872  1310 E native  : do suspend false
,08-31 08:52:17.031  1958  4297 D NfcService: Discovery configuration equal, not updating.
,08-31 08:52:17.052   872  1310 D WifiConfigStore: Retrieve network priorities after PNO.
,08-31 08:52:17.055   872  1310 E native  : do suspend true
,08-31 08:52:17.163   375  1462 D audio_hw_primary: adev_set_parameters: enter: screen_state=off
,08-31 08:52:17.163   375  1462 D mot_vr_audio_hw: adev_set_parameters: screen_state=off
,08-31 08:52:17.280  3868  3918 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 08:52:17.280  3868  3918 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 08:52:17.280  3868  3918 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 08:52:17.280  3868  3918 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-31 08:52:17.280  3868  3918 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 08:52:17.280  3868  3918 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 08:52:17.280  3868  3918 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 08:52:17.280  3868  3918 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-31 08:52:17.288  3868  3918 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-31 08:52:17.291  3868  3918 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-31 08:52:17.291  3868  3918 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@f3bfbd9 added. We now have 8 listener(s)
,08-31 08:52:17.292  3868  3918 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-31 08:52:17.298   872  1881 D WifiService: setWifiEnabled: false pid=3868, uid=10000
,08-31 08:52:17.298   872  1881 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-31 08:52:17.311  3868  3918 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 08:52:17.312   872  2255 D WifiService: setWifiEnabled: true pid=3868, uid=10000
,08-31 08:52:17.312   872  2255 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-31 08:52:17.330   872  1310 D WifiConfigStore: Loading config and enabling all networks 
,08-31 08:52:17.347  3868  3868 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 08:52:17.347  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 08:52:17.347  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 08:52:17.347  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 08:52:17.347  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 08:52:17.347  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 08:52:17.347  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 08:52:17.347  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-31 08:52:17.350  3868  3868 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-31 08:52:17.373   872  1310 D WifiConfigStore: loaded 0 passpoint configs
,08-31 08:52:17.374   872  1310 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,08-31 08:52:17.375   872  1310 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,08-31 08:52:17.376   872  1310 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory),
,08-31 08:52:17.376   872  1310 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
08-31 08:52:17.376   872  1310 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
,08-31 08:52:17.376   872  1310 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,08-31 08:52:17.391   371   870 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,08-31 08:52:17.391   872  1310 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.05 rxSuccessRate=0.07 delta 1000 -> 1000
08-31 08:52:17.391   872  1310 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,08-31 08:52:17.393   371   870 D CommandListener: Setting iface cfg
,08-31 08:52:17.401   872  1309 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '158 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 158 Failed to set address (No such device)'
,08-31 08:52:17.401   872  1309 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
08-31 08:52:17.402   872  1310 E native  : do suspend true
,08-31 08:52:17.418   872  1310 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
,08-31 08:52:17.419   872  1310 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-31 08:52:17.430   872  1310 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,08-31 08:52:17.466   872  1309 D WifiNative-HAL: p2pGetDeviceAddress
,08-31 08:52:17.467   872  1309 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,08-31 08:52:17.488   872  1310 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,08-31 08:52:17.491  1460  1460 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,08-31 08:52:17.928  1460  1460 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-31 08:52:17.978  1460  1460 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,08-31 08:52:17.981  1460  1460 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,08-31 08:52:17.988   872  1310 D WifiConfigStore: Retrieve network priorities after PNO.
,08-31 08:52:18.004   872  1310 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-31 08:52:18.004   872  1312 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
08-31 08:52:18.004   872  1310 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-31 08:52:18.023   872  1310 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-31 08:52:18.039   371   870 D CommandListener: Setting iface cfg
,08-31 08:52:18.040   872  1310 D WifiStateMachine: Start Dhcp Watchdog 3
,08-31 08:52:18.047   872  1310 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,08-31 08:52:18.059  1511  2119 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,08-31 08:52:18.074   872  4310 D DhcpClient: Receive thread started
,08-31 08:52:18.158   872  1310 E native  : do suspend false
,08-31 08:52:18.178   872  1861 D DhcpClient: Broadcasting DHCPDISCOVER
,08-31 08:52:18.198   872  4310 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.101, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172783, domain null
,08-31 08:52:18.199   872  1861 D DhcpClient: Got pending lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172783 seconds
,08-31 08:52:18.202   872  1861 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.101 serverid=192.168.1.1
,08-31 08:52:18.225   872  4310 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.101, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,08-31 08:52:18.226   872  1861 D DhcpClient: Confirmed lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,08-31 08:52:18.231   371   870 D CommandListener: Setting iface cfg
,08-31 08:52:18.244   872  1310 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,08-31 08:52:18.244   872  1861 D DhcpClient: Scheduling renewal in 86399s
,08-31 08:52:18.247   872  1310 E native  : do suspend true
,08-31 08:52:18.265   872  1310 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,08-31 08:52:18.266   872  1310 D WifiConfigStore: No blacklist allowed without epno enabled
,08-31 08:52:18.266   872  1312 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,08-31 08:52:18.268   872  1310 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,08-31 08:52:18.273   872  1312 D ConnectivityService: Adding iface wlan0 to network 102
,08-31 08:52:18.319   872  1312 E ConnectivityService: Unexpected mtu value: 0, wlan0
,08-31 08:52:18.319   872  1312 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
,08-31 08:52:18.320   872  1312 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
,08-31 08:52:18.321   872  1312 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
,08-31 08:52:18.322   872  1312 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
,08-31 08:52:18.330  3868  3918 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 08:52:18.330  3868  3918 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 08:52:18.330  3868  3918 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 08:52:18.330  3868  3918 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 08:52:18.330  3868  3918 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 08:52:18.330  3868  3918 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 08:52:18.330  3868  3918 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 08:52:18.330  3868  3918 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-31 08:52:18.331   872  1312 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,08-31 08:52:18.333  3868  3918 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-31 08:52:18.335   872  1312 D ConnectivityService: scheduleUnvalidatedPrompt 102
,08-31 08:52:18.335   872  1312 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 102]
08-31 08:52:18.335   872  1312 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 102]
08-31 08:52:18.335   872  1312 D ConnectivityService:    accepting network in place of null
08-31 08:52:18.335   872  1310 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
08-31 08:52:18.336   872  1310 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-31 08:52:18.336   872  1312 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.101/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-31 08:52:18.339  3868  3918 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,08-31 08:52:18.340  3868  3918 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,08-31 08:52:18.344  3868  3918 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@edd6548 Bundle[{}]
,08-31 08:52:18.344  3868  3918 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-31 08:52:18.345  3868  3918 I io.jxcore.node.LifeCycleMonitor: stop: OK
,08-31 08:52:18.346  3868  3918 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,08-31 08:52:18.346  3868  3918 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,08-31 08:52:18.347   872  4309 D NetlinkSocketObserver: NeighborEvent{elapsedMs=155306, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
08-31 08:52:18.347  3868  3918 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
,08-31 08:52:18.348  3868  3918 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,08-31 08:52:18.354  3868  3918 I System.out: Running OutgoingSocketThread
,08-31 08:52:18.355  3868  4315 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 427)
,08-31 08:52:18.356  3868  4315 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 37670
08-31 08:52:18.356  3868  4315 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,08-31 08:52:18.371   371   870 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-31 08:52:18.401   371   870 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-31 08:52:18.406   872  1312 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
08-31 08:52:18.406   872  1312 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-31 08:52:18.409   872  1312 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
08-31 08:52:18.413   872   889 D Tethering: MasterInitialState.processMessage what=3
08-31 08:52:18.426  3868  3868 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 08:52:18.426  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 08:52:18.426  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 08:52:18.426  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 08:52:18.426  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 08:52:18.426  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-31 08:52:18.426  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-31 08:52:18.426  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-31 08:52:18.428  3868  3868 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-31 08:52:18.429   872  4308 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.209.78,2a00:1450:401b:801::200e
,08-31 08:52:18.436  1716  1716 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-31 08:52:18.441  2060  2060 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
,08-31 08:52:18.446  1716  1716 D SystemUpdateService: onCreate
,08-31 08:52:18.450  1716  1716 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-31 08:52:18.462  1716  4320 I SystemUpdateService: active receiver: enabled
,08-31 08:52:18.469  1716  4320 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-31 08:52:18.472  1716  1716 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,08-31 08:52:18.480  1716  2405 I iu.UploadsManager: num queued entries: 0
,08-31 08:52:18.480  1716  2405 I iu.UploadsManager: num updated entries: 0
,08-31 08:52:18.482  1716  1716 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-31 08:52:18.484  1716  1716 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-31 08:52:18.486  1716  4320 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
08-31 08:52:18.486  1716  4320 I SystemUpdateService: now status is 0 (complete)
08-31 08:52:18.486  1716  4320 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
08-31 08:52:18.486  1716  4320 I SystemUpdateService: file has been verified
,08-31 08:52:18.487  4053  4053 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-31 08:52:18.489  1716  4323 I MDM     : [185] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
,08-31 08:52:18.489  1716  4323 W BaseAppContext: Using Auth Proxy for data requests.
,08-31 08:52:18.491  1716  4323 V GoogleAuthProtoRequest: [185] a.<init>: mAccountName set to: thalitester@gmail.com
,08-31 08:52:18.494  4053  4053 D SprintDMHelper: simOperator: 
,08-31 08:52:18.494  4053  4053 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-31 08:52:18.495  1716  4320 I SystemUpdateService: OTA package size = 12249756
,08-31 08:52:18.497  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-31 08:52:18.500  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-31 08:52:18.502   872  4308 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 31 Aug 2016 06:52:18 GMT], X-Android-Received-Millis=[1472626338501], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1472626338476]}
,08-31 08:52:18.504   872  1312 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,08-31 08:52:18.504   872  1312 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] validation  passed
,08-31 08:52:18.504   872  1312 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,08-31 08:52:18.507   872  1312 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,08-31 08:52:18.515  1716  2405 I iu.SyncManager: NEXT; no task
,08-31 08:52:18.520  1716  4320 I SystemUpdateService: showing system update notification
,08-31 08:52:18.550  1511  2050 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
,08-31 08:52:18.550  1511  2050 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
,08-31 08:52:18.550  1511  2050 I GLSUser : [GLSUser] Extracting token using key: Auth
08-31 08:52:18.550  1511  2050 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-31 08:52:18.553  1716  1716 D SystemUpdateService: onDestroy
,08-31 08:52:18.574  1716  4323 E MDM     : [185] SitrepService.a: Error sending sitrep.
,08-31 08:52:18.620  3986  4326 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,08-31 08:52:19.357  3868  3918 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 428)
08-31 08:52:19.358  3868  3918 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 428)
,08-31 08:52:19.367  3868  3918 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 433)
,08-31 08:52:19.369  3868  3918 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
,08-31 08:52:19.370  3868  3918 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 434)
,08-31 08:52:19.375  3868  3918 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-31 08:52:19.376  3868  3918 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@61c899e added. We now have 2 listener(s)
,08-31 08:52:19.377  3868  3918 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-31 08:52:19.378  3868  3918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-31 08:52:19.378  3868  3918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: ,
08-31 08:52:19.378  3868  3918 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-31 08:52:19.378  3868  3918 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a48ec7f added. We now have 9 listener(s)
08-31 08:52:19.378  3868  3918 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-31 08:52:19.379  3868  3918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-31 08:52:19.382  3868  3918 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-31 08:52:19.391  3868  3918 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-31 08:52:19.391  3868  3918 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 08:52:19.391  3868  3918 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 08:52:19.391  3868  3918 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 08:52:19.391  3868  3918 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 08:52:19.391  3868  3918 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-31 08:52:19.391  3868  3918 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-31 08:52:19.391  3868  3918 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-31 08:52:19.394  3868  3918 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-31 08:52:19.394  3868  3918 D io.jxcore.node.ConnectivityMonitor: start: OK
08-31 08:52:19.394  3868  3918 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-31 08:52:19.394  3868  3918 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@677c95 added. We now have 3 listener(s)
,08-31 08:52:19.396  3868  3918 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-31 08:52:19.396  3868  3918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-31 08:52:19.396  3868  3918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-31 08:52:19.396  3868  3918 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-31 08:52:19.397  3868  3918 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@443a1aa added. We now have 10 listener(s)
08-31 08:52:19.397  3868  3918 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-31 08:52:19.397  3868  3918 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-31 08:52:19.397  3868  3918 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 08:52:19.397  3868  3918 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 08:52:19.397  3868  3918 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 08:52:19.397  3868  3918 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-31 08:52:19.397  3868  3918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-31 08:52:19.397  3868  3918 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-31 08:52:19.397  3868  3918 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@61c899e removed from the list
08-31 08:52:19.397  3868  3918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-31 08:52:19.398  3868  3918 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a48ec7f removed from the list
08-31 08:52:19.400  3868  3868 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 08:52:19.405  3868  3868 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 08:52:19.406  3868  3918 D io.jxcore.node.ConnectivityMonitor: stop
08-31 08:52:19.406  3868  3918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-31 08:52:19.406  3868  3918 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 08:52:19.406  3868  3918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 08:52:19.407   872  1312 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 101] cleared because we found a replacement network
,08-31 08:52:19.409  3868  3918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-31 08:52:19.409  3868  3918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 08:52:19.409  3868  3918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 08:52:19.409  3868  3918 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a48ec7f not in the list
08-31 08:52:19.409  3868  3918 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-31 08:52:19.409  3868  3918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-31 08:52:19.410  3868  3918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 08:52:19.410  3868  3918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 08:52:19.410  3868  3918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-31 08:52:19.410  3868  3918 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@443a1aa removed from the list
08-31 08:52:19.410  3868  3918 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 08:52:19.411  3868  3918 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 08:52:19.411  3868  3918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-31 08:52:19.411  3868  3918 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-31 08:52:19.411  3868  3918 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@677c95 removed from the list
,08-31 08:52:19.412  3868  3918 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-31 08:52:19.412  3868  3918 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f89d19b added. We now have 2 listener(s)
08-31 08:52:19.413  3868  3918 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-31 08:52:19.414  3868  3918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-31 08:52:19.414  3868  3918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-31 08:52:19.414  3868  3918 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-31 08:52:19.414  3868  3918 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@46da938 added. We now have 9 listener(s)
08-31 08:52:19.414  3868  3918 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-31 08:52:19.415  3868  3918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-31 08:52:19.418  3868  3918 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-31 08:52:19.424  3868  3918 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-31 08:52:19.424  3868  3918 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 08:52:19.424  3868  3918 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 08:52:19.424  3868  3918 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 08:52:19.424  3868  3918 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 08:52:19.424  3868  3918 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-31 08:52:19.424  3868  3918 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-31 08:52:19.424  3868  3918 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-31 08:52:19.427  3868  3918 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-31 08:52:19.427  3868  3918 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-31 08:52:19.428  3868  3918 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-31 08:52:19.428  3868  3918 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2122e76 added. We now have 3 listener(s)
,08-31 08:52:19.431  3868  3918 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-31 08:52:19.431  3868  3918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-31 08:52:19.431  3868  3918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-31 08:52:19.431  3868  3918 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-31 08:52:19.431  3868  3918 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@129ec77 added. We now have 10 listener(s)
08-31 08:52:19.431  3868  3918 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-31 08:52:19.431  3868  3918 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-31 08:52:19.431  3868  3918 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-31 08:52:19.432  3868  3918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-31 08:52:19.432  3868  3918 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-31 08:52:19.432  3868  3918 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-31 08:52:19.432  3868  3868 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 08:52:19.436  3868  3868 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 08:52:19.436  3868  3918 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-31 08:52:19.437  3868  3918 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-31 08:52:19.446  3868  3918 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-31 08:52:19.447  3868  3918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,08-31 08:52:19.447  3868  3918 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-31 08:52:19.451  3868  3918 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-31 08:52:19.451  3868  3918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-31 08:52:19.451  3868  3918 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-31 08:52:19.452  3868  3918 D BluetoothAdapter: STATE_ON
,08-31 08:52:19.456  4243  4287 D BtGatt.GattService: registerClient() - UUID=a13188c9-d870-4afd-97fd-caec56644d92
,08-31 08:52:19.457  4243  4259 D BtGatt.GattService: onClientRegistered() - UUID=a13188c9-d870-4afd-97fd-caec56644d92, clientIf=5
,08-31 08:52:19.458  3868  3879 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,08-31 08:52:19.459  4243  4254 D BtGatt.GattService: start scan with filters
,08-31 08:52:19.463  3868  3918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-31 08:52:19.464  4243  4262 D BtGatt.ScanManager: handling starting scan
08-31 08:52:19.464  3868  3918 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-31 08:52:19.464  3868  3918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-31 08:52:19.464  3868  3918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-31 08:52:19.465  4243  4262 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4e6af5c
,08-31 08:52:19.468  3868  3918 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-31 08:52:19.468  3868  3868 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-31 08:52:19.469  3868  3918 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-31 08:52:19.470  3868  3918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-31 08:52:19.473  4243  4259 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,08-31 08:52:19.473  4243  4259 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-31 08:52:19.473  3868  3918 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-31 08:52:19.474  4243  4262 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
08-31 08:52:19.474  3868  3918 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-31 08:52:19.474  3868  3918 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,08-31 08:52:19.474  3868  3918 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-31 08:52:19.474  3868  3918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left,
,08-31 08:52:19.474  3868  3918 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts,
08-31 08:52:19.474  3868  3918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,08-31 08:52:19.474  3868  3918 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,08-31 08:52:19.474  3868  3918 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-31 08:52:19.475  3868  3918 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,08-31 08:52:19.475  3868  3918 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-31 08:52:19.476  3868  3918 D BluetoothAdapter: STATE_ON
,08-31 08:52:19.476  4243  4254 D BtGatt.GattService: stopScan() - queue size =1
08-31 08:52:19.477  4243  4284 D BtGatt.GattService: unregisterClient() - clientIf=5
08-31 08:52:19.478  3868  3918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-31 08:52:19.478  3868  3918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-31 08:52:19.478  3868  3918 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,08-31 08:52:19.478  3868  3918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-31 08:52:19.478  3868  3918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-31 08:52:19.479  3868  3918 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-31 08:52:19.480  3868  3918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-31 08:52:19.480  3868  3918 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,08-31 08:52:19.480  3868  3918 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-31 08:52:19.480  3868  3918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-31 08:52:19.482  3868  3868 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-31 08:52:19.482  3868  3868 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-31 08:52:19.482  3868  3868 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-31 08:52:19.484  3868  3918 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-31 08:52:19.485  3868  3918 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-31 08:52:19.485  3868  3918 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...,
08-31 08:52:19.485  3868  3918 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 08:52:19.486  3868  3918 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 08:52:19.486  3868  3918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-31 08:52:19.486  4243  4259 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,08-31 08:52:19.487  4243  4259 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-31 08:52:19.486  3868  3918 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-31 08:52:19.487  3868  3918 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f89d19b removed from the list
08-31 08:52:19.487  3868  3918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 08:52:19.487  3868  3918 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@46da938 removed from the list
,08-31 08:52:19.487  3868  3918 D io.jxcore.node.ConnectivityMonitor: stop
08-31 08:52:19.487  3868  3918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 08:52:19.487  4243  4262 D BtGatt.ScanManager: Starting BLE batch scan
08-31 08:52:19.487  4243  4262 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-31 08:52:19.488  3868  3918 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-31 08:52:19.488  3868  3918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 08:52:19.489  3868  3918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 08:52:19.489  3868  3918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 08:52:19.489  3868  3918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 08:52:19.490  3868  3918 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@46da938 not in the list
,08-31 08:52:19.490  3868  3918 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 08:52:19.490  3868  3918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 08:52:19.491  3868  3918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 08:52:19.491  3868  3918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 08:52:19.491  3868  3918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 08:52:19.491  3868  3918 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@129ec77 removed from the list
08-31 08:52:19.491  3868  3918 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 08:52:19.491  3868  3918 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-31 08:52:19.491  3868  3918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-31 08:52:19.492  3868  3918 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-31 08:52:19.492  3868  3918 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2122e76 removed from the list
08-31 08:52:19.492  3868  3918 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-31 08:52:19.493  3868  3918 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@346d913 added. We now have 2 listener(s)
08-31 08:52:19.495  3868  3918 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-31 08:52:19.495  3868  3918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-31 08:52:19.495  3868  3918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-31 08:52:19.495  3868  3918 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-31 08:52:19.495  3868  3918 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3006750 added. We now have 9 listener(s)
,08-31 08:52:19.495  3868  3918 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-31 08:52:19.496  3868  3918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-31 08:52:19.498  3868  3918 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-31 08:52:19.503  3868  3918 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-31 08:52:19.503  3868  3918 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 08:52:19.503  3868  3918 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 08:52:19.503  3868  3918 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 08:52:19.503  3868  3918 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 08:52:19.503  3868  3918 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-31 08:52:19.503  3868  3918 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-31 08:52:19.503  3868  3918 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-31 08:52:19.505  3868  3918 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-31 08:52:19.505  3868  3918 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-31 08:52:19.508  3868  3868 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 08:52:19.510  3868  3918 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-31 08:52:19.510  3868  3868 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 08:52:19.511  3868  3918 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@dcc964e added. We now have 3 listener(s)
,08-31 08:52:19.512  3868  3918 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-31 08:52:19.512  3868  3918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-31 08:52:19.512  3868  3918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-31 08:52:19.513  3868  3918 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-31 08:52:19.513  3868  3918 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@43bf36f added. We now have 10 listener(s)
,08-31 08:52:19.513  3868  3918 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-31 08:52:19.513  3868  3918 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-31 08:52:19.514  4243  4259 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,08-31 08:52:19.514  4243  4259 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-31 08:52:19.514  3868  3918 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-31 08:52:19.515  3868  3918 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,08-31 08:52:19.515  3868  3918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,08-31 08:52:19.515  3868  3918 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-31 08:52:19.515  3868  3918 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-31 08:52:19.520  3868  3918 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-31 08:52:19.520  3868  3918 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-31 08:52:19.522  4243  4259 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,08-31 08:52:19.522  4243  4259 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-31 08:52:19.525  3868  3918 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-31 08:52:19.526  3868  3918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,08-31 08:52:19.526  3868  3918 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-31 08:52:19.531  4243  4259 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,08-31 08:52:19.531  4243  4259 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-31 08:52:19.531  4243  4262 D BtGatt.ScanManager: stopping BLe Batch
08-31 08:52:19.532  3868  3918 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-31 08:52:19.532  3868  3918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-31 08:52:19.532  3868  3918 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-31 08:52:19.534  3868  3918 D BluetoothAdapter: STATE_ON
,08-31 08:52:19.535  4243  4254 D BtGatt.GattService: registerClient() - UUID=ff4a45a9-88a0-4b04-8eb3-887f79bb4d1f
08-31 08:52:19.536  4243  4259 D BtGatt.GattService: onClientRegistered() - UUID=ff4a45a9-88a0-4b04-8eb3-887f79bb4d1f, clientIf=5
,08-31 08:52:19.536  3868  3879 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,08-31 08:52:19.536  4243  4287 D BtGatt.GattService: start scan with filters
,08-31 08:52:19.540  3868  3918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-31 08:52:19.540  3868  3918 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,08-31 08:52:19.540  3868  3918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-31 08:52:19.540  3868  3918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-31 08:52:19.540  4243  4259 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,08-31 08:52:19.540  4243  4259 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-31 08:52:19.540  4243  4262 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5,
08-31 08:52:19.542  3868  3918 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-31 08:52:19.543  3868  3918 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-31 08:52:19.543  3868  3868 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-31 08:52:19.544  3868  3918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK,
08-31 08:52:19.547  3868  3918 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,08-31 08:52:19.547  3868  3918 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-31 08:52:19.547  3868  3918 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 08:52:19.547  3868  3918 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-31 08:52:19.547  3868  3918 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 08:52:19.548  3868  3918 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-31 08:52:19.548  3868  3918 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-31 08:52:19.548  3868  3918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-31 08:52:19.548  3868  3918 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-31 08:52:19.548  3868  3918 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@346d913 removed from the list,
08-31 08:52:19.548  3868  3918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-31 08:52:19.548  3868  3918 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3006750 removed from the list
08-31 08:52:19.548  3868  3918 D io.jxcore.node.ConnectivityMonitor: stop
,08-31 08:52:19.548  3868  3918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-31 08:52:19.549  3868  3918 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
08-31 08:52:19.549  3868  3918 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
,08-31 08:52:19.549  3868  3918 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-31 08:52:19.549  3868  3918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-31 08:52:19.550  3868  3918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-31 08:52:19.550  3868  3918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 08:52:19.550  3868  3918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose,
,08-31 08:52:19.550  3868  3918 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3006750 not in the list
08-31 08:52:19.550  3868  3918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,08-31 08:52:19.550  3868  3918 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,08-31 08:52:19.550  3868  3918 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-31 08:52:19.550  3868  3918 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-31 08:52:19.550  3868  3918 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-31 08:52:19.551  3868  3918 D BluetoothAdapter: STATE_ON
08-31 08:52:19.551  4243  4287 D BtGatt.GattService: stopScan() - queue size =0
08-31 08:52:19.552  4243  4259 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-31 08:52:19.552  4243  4259 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-31 08:52:19.552  4243  4284 D BtGatt.GattService: unregisterClient() - clientIf=5
08-31 08:52:19.552  3868  3918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-31 08:52:19.552  3868  3918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-31 08:52:19.552  3868  3918 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-31 08:52:19.553  3868  3918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-31 08:52:19.553  3868  3918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-31 08:52:19.554  3868  3918 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-31 08:52:19.554  3868  3918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-31 08:52:19.554  3868  3918 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-31 08:52:19.554  3868  3918 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-31 08:52:19.554  4243  4262 D BtGatt.ScanManager: handling starting scan
08-31 08:52:19.554  3868  3918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 08:52:19.555  3868  3868 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-31 08:52:19.555  3868  3868 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-31 08:52:19.556  3868  3868 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-31 08:52:19.556  3868  3918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 08:52:19.556  3868  3918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 08:52:19.556  3868  3918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 08:52:19.556  3868  3918 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@43bf36f removed from the list
08-31 08:52:19.556  3868  3918 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 08:52:19.556  3868  3918 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 08:52:19.556  3868  3918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 08:52:19.556  3868  3918 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-31 08:52:19.556  3868  3918 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@dcc964e removed from the list
08-31 08:52:19.557  3868  3918 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Alrea,dy loaded
08-31 08:52:19.558  3868  3918 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2be578b added. We now have 2 listener(s)
08-31 08:52:19.559  3868  3918 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-31 08:52:19.559  3868  3918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-31 08:52:19.559  3868  3918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-31 08:52:19.560  3868  3918 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-31 08:52:19.560  3868  3918 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a39d068 added. We now have 9 listener(s)
08-31 08:52:19.560  3868  3918 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-31 08:52:19.560  3868  3918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-31 08:52:19.562  3868  3918 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-31 08:52:19.563  4243  4259 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-31 08:52:19.563  4243  4259 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-31 08:52:19.564  4243  4262 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-31 08:52:19.568  3868  3918 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-31 08:52:19.568  3868  3918 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 08:52:19.568  3868  3918 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 08:52:19.568  3868  3918 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 08:52:19.568  3868  3918 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 08:52:19.568  3868  3918 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-31 08:52:19.568  3868  3918 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-31 08:52:19.568  3868  3918 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-31 08:52:19.570  4243  4259 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-31 08:52:19.570  4243  4259 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-31 08:52:19.570  4243  4262 D BtGatt.ScanManager: Starting BLE batch scan
,08-31 08:52:19.570  4243  4262 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-31 08:52:19.571  3868  3918 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-31 08:52:19.571  3868  3918 D io.jxcore.node.ConnectivityMonitor: start: OK
08-31 08:52:19.571  3868  3918 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-31 08:52:19.571  3868  3918 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ec12126 added. We now have 3 listener(s)
,08-31 08:52:19.573  3868  3868 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 08:52:19.576  3868  3868 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 08:52:19.577  3868  3918 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-31 08:52:19.577  3868  3918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-31 08:52:19.577  3868  3918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-31 08:52:19.577  3868  3918 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-31 08:52:19.577  3868  3918 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9b8e167 added. We now have 10 listener(s)
08-31 08:52:19.577  3868  3918 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-31 08:52:19.578  3868  3918 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-31 08:52:19.578  3868  3918 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-31 08:52:19.578  3868  3918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-31 08:52:19.578  3868  3918 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-31 08:52:19.578  3868  3918 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-31 08:52:19.581  3868  3918 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,08-31 08:52:19.581  3868  3918 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-31 08:52:19.585  4243  4259 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,08-31 08:52:19.585  4243  4259 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-31 08:52:19.586  3868  3918 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-31 08:52:19.588  3868  3918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,08-31 08:52:19.588  3868  3918 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-31 08:52:19.591  3868  3918 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-31 08:52:19.591  3868  3918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-31 08:52:19.591  3868  3918 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-31 08:52:19.592  3868  3918 D BluetoothAdapter: STATE_ON
,08-31 08:52:19.593  4243  4259 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,08-31 08:52:19.593  4243  4259 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-31 08:52:19.594  4243  4254 D BtGatt.GattService: registerClient() - UUID=09f9689a-2dee-47c8-81e2-59415f3ecada
,08-31 08:52:19.595  4243  4259 D BtGatt.GattService: onClientRegistered() - UUID=09f9689a-2dee-47c8-81e2-59415f3ecada, clientIf=5
,08-31 08:52:19.595  3868  3879 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,08-31 08:52:19.596  4243  4287 D BtGatt.GattService: start scan with filters
,08-31 08:52:19.598  3868  3918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-31 08:52:19.598  3868  3918 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,08-31 08:52:19.598  3868  3918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,08-31 08:52:19.599  3868  3918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING],
,08-31 08:52:19.601  3868  3918 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-31 08:52:19.601  4243  4259 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-31 08:52:19.601  3868  3918 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-31 08:52:19.601  4243  4259 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-31 08:52:19.602  4243  4262 D BtGatt.ScanManager: stopping BLe Batch
08-31 08:52:19.602  3868  3868 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-31 08:52:19.603  3868  3918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-31 08:52:19.608  4243  4259 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,08-31 08:52:19.608  4243  4259 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-31 08:52:19.608  4243  4262 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-31 08:52:19.609  3868  3918 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-31 08:52:19.610  3868  3918 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-31 08:52:19.610  3868  3918 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-31 08:52:19.610  3868  3918 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-31 08:52:19.610  3868  3918 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-31 08:52:19.610  3868  3918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-31 08:52:19.610  3868  3918 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-31 08:52:19.610  3868  3918 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2be578b removed from the list
,08-31 08:52:19.610  3868  3918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 08:52:19.610  3868  3918 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a39d068 removed from the list
,08-31 08:52:19.610  3868  3918 D io.jxcore.node.ConnectivityMonitor: stop
08-31 08:52:19.610  3868  3918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-31 08:52:19.611  3868  3918 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
08-31 08:52:19.611  3868  3918 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
,08-31 08:52:19.611  3868  3918 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-31 08:52:19.611  3868  3918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-31 08:52:19.612  3868  3918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 08:52:19.612  3868  3918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 08:52:19.612  3868  3918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 08:52:19.612  3868  3918 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a39d068 not in the list
08-31 08:52:19.612  3868  3918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-31 08:52:19.612  3868  3918 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-31 08:52:19.612  3868  3918 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-31 08:52:19.612  3868  3918 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-31 08:52:19.613  3868  3918 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-31 08:52:19.613  3868  3918 D BluetoothAdapter: STATE_ON
08-31 08:52:19.614  4243  4253 D BtGatt.GattService: stopScan() - queue size =0
,08-31 08:52:19.615  4243  4254 D BtGatt.GattService: unregisterClient() - clientIf=5
08-31 08:52:19.615  3868  3918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped,
08-31 08:52:19.615  3868  3918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,08-31 08:52:19.615  3868  3918 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,08-31 08:52:19.615  3868  3918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-31 08:52:19.615  3868  3918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-31 08:52:19.616  4243  4259 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-31 08:52:19.616  4243  4259 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-31 08:52:19.617  3868  3918 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-31 08:52:19.617  4243  4262 D BtGatt.ScanManager: handling starting scan
08-31 08:52:19.617  3868  3918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,08-31 08:52:19.618  3868  3918 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,08-31 08:52:19.618  3868  3918 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-31 08:52:19.618  3868  3918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left,
08-31 08:52:19.619  3868  3918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery,
,08-31 08:52:19.619  3868  3918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 08:52:19.620  3868  3918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-31 08:52:19.620  3868  3868 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-31 08:52:19.620  3868  3918 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9b8e167 removed from the list
,08-31 08:52:19.620  3868  3918 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 08:52:19.620  3868  3868 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-31 08:52:19.620  3868  3918 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-31 08:52:19.620  3868  3918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 08:52:19.620  3868  3868 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-31 08:52:19.620  3868  3918 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-31 08:52:19.620  3868  3918 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ec12126 removed from the list
08-31 08:52:19.621  3868  3918 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-31 08:52:19.621  3868  3918 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@de82d03 added. We now have 2 listener(s)
,08-31 08:52:19.623  3868  3918 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-31 08:52:19.623  3868  3918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-31 08:52:19.623  3868  3918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-31 08:52:19.624  3868  3918 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-31 08:52:19.624  3868  3918 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ce44480 added. We now have 9 listener(s)
08-31 08:52:19.624  3868  3918 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-31 08:52:19.624  4243  4259 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,08-31 08:52:19.624  4243  4259 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-31 08:52:19.624  4243  4262 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-31 08:52:19.624  3868  3918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-31 08:52:19.627  3868  3918 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-31 08:52:19.630  4243  4259 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-31 08:52:19.630  4243  4259 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-31 08:52:19.630  4243  4262 D BtGatt.ScanManager: Starting BLE batch scan
08-31 08:52:19.630  4243  4262 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-31 08:52:19.632  3868  3918 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-31 08:52:19.632  3868  3918 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 08:52:19.632  3868  3918 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 08:52:19.632  3868  3918 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 08:52:19.632  3868  3918 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 08:52:19.632  3868  3918 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-31 08:52:19.632  3868  3918 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-31 08:52:19.632  3868  3918 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-31 08:52:19.635  3868  3918 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-31 08:52:19.636  3868  3918 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-31 08:52:19.636  3868  3918 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-31 08:52:19.636  3868  3918 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7b12efe added. We now have 3 listener(s)
08-31 08:52:19.638  3868  3868 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 08:52:19.639  3868  3918 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-31 08:52:19.640  3868  3918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-31 08:52:19.640  3868  3918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-31 08:52:19.640  3868  3918 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-31 08:52:19.640  3868  3918 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@936965f added. We now have 10 listener(s)
08-31 08:52:19.640  3868  3918 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-31 08:52:19.640  3868  3918 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-31 08:52:19.641  3868  3868 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 08:52:19.641  3868  3918 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 08:52:19.641  3868  3918 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 08:52:19.641  3868  3918 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-31 08:52:19.641  3868  3918 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 08:52:19.641  3868  3918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-31 08:52:19.641  3868  3918 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-31 08:52:19.641  3868  3918 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@de82d03 removed from the list
08-31 08:52:19.642  3868  3918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-31 08:52:19.642  3868  3918 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ce44480 removed from the list
08-31 08:52:19.642  3868  3918 D io.jxcore.node.ConnectivityMonitor: stop
08-31 08:52:19.642  3868  3918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 08:52:19.643  3868  3918 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 08:52:19.643  3868  3918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 08:52:19.644  4243  4259 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-31 08:52:19.644  4243  4259 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-31 08:52:19.645  3868  3918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-31 08:52:19.645  3868  3918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 08:52:19.645  3868  3918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 08:52:19.645  3868  3918 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ce44480 not in the list
08-31 08:52:19.645  3868  3918 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 08:52:19.645  3868  3918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-31 08:52:19.647  3868  3918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 08:52:19.647  3868  3918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-31 08:52:19.647  3868  3918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 08:52:19.647  3868  3918 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@936965f removed from the list
08-31 08:52:19.647  3868  3918 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 08:52:19.647  3868  3918 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 08:52:19.647  3868  3918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 08:52:19.647  3868  3918 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-31 08:52:19.647  3868  3918 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7b12efe removed from the list
08-31 08:52:19.649  3868  3918 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
08-31 08:52:19.649  3868  3918 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
08-31 08:52:19.649  3868  3918 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
08-31 08:52:19.649  3868  3918 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-31 08:52:19.650  3868  3918 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
08-31 08:52:19.650  3868  3918 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-31 08:52:19.650  4243  4259 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-31 08:52:19.651  4243  4259 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-31 08:52:19.658  4243  4259 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,08-31 08:52:19.658  4243  4259 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-31 08:52:19.658  4243  4262 D BtGatt.ScanManager: stopping BLe Batch
,08-31 08:52:19.660  3868  4334 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 441, name: My test thread name)
,08-31 08:52:19.660  3868  4334 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 441, thread name: My test thread name)
08-31 08:52:19.660  3868  4334 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 441, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,08-31 08:52:19.662  3868  4335 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 443, name: My test thread name)
08-31 08:52:19.662  3868  4335 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 443, thread name: My test thread name)
08-31 08:52:19.662  3868  4335 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 443, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,08-31 08:52:19.664  3868  3918 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 80
,08-31 08:52:19.664  3868  3918 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 80
,08-31 08:52:19.665  3868  3918 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
08-31 08:52:19.665  3868  3918 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
08-31 08:52:19.665  3868  3918 D com.test.thalitest.ThaliTestRunner: Total duration: 22806 ms
,08-31 08:52:19.665  4243  4259 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-31 08:52:19.665  4243  4259 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-31 08:52:19.665  4243  4262 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
08-31 08:52:19.667  3868  3918 I jxcore-log: *Native tests were executed*
08-31 08:52:19.667  3868  3918 I jxcore-log: 
,08-31 08:52:19.667  3868  3918 I jxcore-log: Total number of executed tests:  80
08-31 08:52:19.667  3868  3918 I jxcore-log: 
08-31 08:52:19.667  3868  3918 I jxcore-log: Number of passed tests:  80
08-31 08:52:19.667  3868  3918 I jxcore-log: 
08-31 08:52:19.667  3868  3918 I jxcore-log: Number of failed tests:  0
08-31 08:52:19.667  3868  3918 I jxcore-log: 
08-31 08:52:19.667  3868  3918 I jxcore-log: Number of ignored tests:  0
08-31 08:52:19.667  3868  3918 I jxcore-log: 
,08-31 08:52:19.668  3868  3918 I jxcore-log: Total duration:  22806
08-31 08:52:19.668  3868  3918 I jxcore-log: 
,08-31 08:52:19.668  3868  3918 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
08-31 08:52:19.668  3868  3918 I jxcore-log: 
,08-31 08:52:19.672  3868  3918 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-31 08:52:19.672  3868  3918 I jxcore-log: 
08-31 08:52:19.672  4243  4259 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-31 08:52:19.672  4243  4259 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-31 08:52:19.676  3868  3918 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-31 08:52:19.676  3868  3918 I jxcore-log: 
08-31 08:52:19.677  3868  3918 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-31 08:52:19.677  3868  3918 I jxcore-log: 
08-31 08:52:19.678  3868  3868 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
08-31 08:52:19.679  3868  3918 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-31 08:52:19.679  3868  3918 I jxcore-log: 
08-31 08:52:19.680  3868  3918 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-31 08:52:19.680  3868  3918 I jxcore-log: 
08-31 08:52:19.681  3868  3918 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-31 08:52:19.681  3868  3918 I jxcore-log: 
08-31 08:52:19.684  3868  3918 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-31 08:52:19.684  3868  3918 I jxcore-log: 
08-31 08:52:19.685  3868  3918 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-31 08:52:19.685  3868  3918 I jxcore-log: 
08-31 08:52:19.686  3868  3918 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-31 08:52:19.686  3868  3918 I jxcore-log: 
08-31 08:52:19.687  3868  3918 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-31 08:52:19.687  3868  3918 I jxcore-log: 
08-31 08:52:19.688  3868  3918 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-31 08:52:19.688  3868  3918 I jxcore-log: 
08-31 08:52:19.689  3868  3918 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-31 08:52:19.689  3868  3918 I jxcore-log: 
08-31 08:52:19.690  3868  3918 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-31 08:52:19.690  3868  3918 I jxcore-log: 
,08-31 08:52:19.691  3868  3918 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-31 08:52:19.691  3868  3918 I jxcore-log: 
08-31 08:52:19.692  3868  3918 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-31 08:52:19.692  3868  3918 I jxcore-log: 
,08-31 08:52:19.692  3868  3918 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-31 08:52:19.692  3868  3918 I jxcore-log: 
,08-31 08:52:19.693  3868  3918 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-31 08:52:19.693  3868  3918 I jxcore-log: 
,08-31 08:52:19.694  3868  3918 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-31 08:52:19.694  3868  3918 I jxcore-log: 
,08-31 08:52:19.695  3868  3918 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-31 08:52:19.695  3868  3918 I jxcore-log: 
,08-31 08:52:19.695  3868  3918 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-31 08:52:19.695  3868  3918 I jxcore-log: 
08-31 08:52:19.696  3868  3918 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-31 08:52:19.696  3868  3918 I jxcore-log: 
,08-31 08:52:19.697  3868  3918 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-31 08:52:19.697  3868  3918 I jxcore-log: 
,08-31 08:52:19.698  3868  3918 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-31 08:52:19.698  3868  3918 I jxcore-log: 
,08-31 08:52:19.699  3868  3918 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-31 08:52:19.699  3868  3918 I jxcore-log: 
08-31 08:52:19.699  3868  3918 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-31 08:52:19.699  3868  3918 I jxcore-log: 
,08-31 08:52:19.700  3868  3918 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-31 08:52:19.700  3868  3918 I jxcore-log: 
,08-31 08:52:19.700  3868  3918 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-31 08:52:19.700  3868  3918 I jxcore-log: 
08-31 08:52:19.701  3868  3918 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-31 08:52:19.701  3868  3918 I jxcore-log: 
,08-31 08:52:19.701  3868  3918 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-31 08:52:19.701  3868  3918 I jxcore-log: 
08-31 08:52:19.702  3868  3918 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-31 08:52:19.702  3868  3918 I jxcore-log: 
,08-31 08:52:19.702  3868  3918 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-31 08:52:19.702  3868  3918 I jxcore-log: 
08-31 08:52:19.703  3868  3918 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-31 08:52:19.703  3868  3918 I jxcore-log: 
,08-31 08:52:19.983  3868  3868 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-31 08:52:19.986  3868  3918 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-31 08:52:19.986  3868  3918 I jxcore-log: 
,08-31 08:52:20.056  3868  3868 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-31 08:52:20.060  3868  3918 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-31 08:52:20.060  3868  3918 I jxcore-log: 
,08-31 08:52:20.121  3868  3868 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-31 08:52:20.125  3868  3918 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-31 08:52:20.125  3868  3918 I jxcore-log: 
,08-31 08:52:20.320  4336  4336 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,08-31 08:52:20.325  4336  4336 D AndroidRuntime: CheckJNI is OFF
,08-31 08:52:20.368  4336  4336 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,08-31 08:52:20.416  4336  4336 I Radio-JNI: register_android_hardware_Radio DONE
,08-31 08:52:20.438  4336  4336 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,08-31 08:52:20.449   872   885 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=-1: uninstall pkg
,08-31 08:52:20.450   872   885 I ActivityManager: Killing 3868:com.test.thalitest/u0a0 (adj 0): stop com.test.thalitest
,08-31 08:52:20.545   872  1998 I WindowState: WIN DEATH: Window{9cefc1 u0 com.test.thalitest/com.test.thalitest.MainActivity}
08-31 08:52:20.546   872  1311 D WifiService: Client connection lost with reason: 4
,08-31 08:52:20.546   872  1994 D GraphicsStats: Buffer count: 2
,08-31 08:52:20.587   872   895 W PackageSettings: Skipping PackageSetting{69a1b9 com.example.hello/10273} due to missing metadata
,08-31 08:52:20.608   872   885 W ActivityManager: Failed trying to unstop package com.test.thalitest: java.lang.IllegalArgumentException: Unknown package: com.test.thalitest
,08-31 08:52:20.609   872   885 W PackageManager: Package com.test.thalitest is missing; assuming frozen
,08-31 08:52:20.609   872   885 E ActivityManager: Failure starting process com.test.thalitest
08-31 08:52:20.609   872   885 E ActivityManager: java.lang.RuntimeException: Package com.test.thalitest is frozen!
08-31 08:52:20.609   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3272)
08-31 08:52:20.609   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3231)
08-31 08:52:20.609   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3110)
08-31 08:52:20.609   872   885 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1395)
08-31 08:52:20.609   872   885 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:2007)
08-31 08:52:20.609   872   885 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1554)
08-31 08:52:20.609   872   885 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2735)
08-31 08:52:20.609   872   885 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2724)
08-31 08:52:20.609   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4592)
08-31 08:52:20.609   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:5949)
08-31 08:52:20.609   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.killPackageProcessesLocked(ActivityManagerService.java:5608)
08-31 08:52:20.609   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.forceStopPackageLocked(ActivityManagerService.java:5757)
08-31 08:52:20.609   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.-wrap1(ActivityManagerService.java)
08-31 08:52:20.609   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:1730)
08-31 08:52:20.609   872   885 E ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
,08-31 08:52:20.609   872   885 E ActivityManager: 	at android.os.Looper.loop(Looper.java:148)
08-31 08:52:20.609   872   885 E ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-31 08:52:20.609   872   885 E ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
08-31 08:52:20.610   872   885 I ActivityManager:   Force finishing activity ActivityRecord{f6cd32e u0 com.test.thalitest/.MainActivity t2}
08-31 08:52:20.612   872   895 I art     : Starting a blocking GC Explicit
,08-31 08:52:20.617   872  2076 W ActivityManager: Spurious death for ProcessRecord{e15f3ed 0:com.test.thalitest/u0a0}, curProc for 3868: null
,08-31 08:52:20.656   872   895 I art     : Explicit concurrent mark sweep GC freed 56696(3MB) AllocSpace objects, 9(228KB) LOS objects, 33% free, 29MB/43MB, paused 761us total 43.329ms
,08-31 08:52:20.685   872   895 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,08-31 08:52:20.687  4336  4336 I art     : System.exit called, status: 0
,08-31 08:52:20.688  4336  4336 I AndroidRuntime: VM exiting with result code 0.
,08-31 08:52:20.697   872   895 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=0: pkg removed
,08-31 08:52:20.722   872   885 I ActivityManager: Exiting empty application process com.test.thalitest (null)
,08-31 08:52:20.726  4243  4243 D BluetoothMapAppObserver: onReceive
,08-31 08:52:20.726  4243  4243 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
08-31 08:52:20.731  1897  2278 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
08-31 08:52:20.733   872  1302 I InputReader: Reconfiguring input devices.  changes=0x00000010
08-31 08:52:20.742  3682  3682 D BuaReceiver: ====== got intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.motorola.android.buacontactadapter/.BuaReceiver (has extras) }
,08-31 08:52:20.750  1884  1884 I Keyboard.Facilitator: resetDictionaries() : en_US
,08-31 08:52:20.759  1884  4349 I Keyboard.Facilitator.DecoderInitializer: run()
,08-31 08:52:20.768  1971  1971 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,08-31 08:52:20.785   872  1993 I ActivityManager: Start proc 4350:android.process.acore/u0a5 for broadcast com.android.providers.contacts/.PackageIntentReceiver
,08-31 08:52:20.800  1884  4349 I Decoder : createOrResetDecoder
,08-31 08:52:20.820   872   872 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,08-31 08:52:20.834  4350  4350 W System  : ClassLoader referenced unknown path: /system/priv-app/ContactsProvider/lib/arm
,08-31 08:52:20.836  1511  1511 I ConfigService: onCreate
,08-31 08:52:20.838  1511  4362 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/config.db'.
08-31 08:52:20.838  1511  4362 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-31 08:52:20.838  1511  4362 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-31 08:52:20.838  1511  4362 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-31 08:52:20.838  1511  4362 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-31 08:52:20.838  1511  4362 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-31 08:52:20.838  1511  4362 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-31 08:52:20.838  1511  4362 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-31 08:52:20.838  1511  4362 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-31 08:52:20.838  1511  4362 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-31 08:52:20.838  1511  4362 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-31 08:52:20.838  1511  4362 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-31 08:52:20.838  1511  4362 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-31 08:52:20.838  1511  4362 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-31 08:52:20.838  1511  4362 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-31 08:52:20.838  1511  4362 E SQLiteDatabase: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
08-31 08:52:20.838  1511  4362 E SQLiteDatabase: 	at com.google.android.gms.config.j.run(SourceFile:152)
08-31 08:52:20.838  1511  4362 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
08-31 08:52:20.838  1511  4362 E SQLiteOpenHelper: Couldn't open config.db for writing (will try read-only):
08-31 08:52:20.838  1511  4362 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-31 08:52:20.838  1511  4362 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-31 08:52:20.838  1511  4362 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-31 08:52:20.838  1511  4362 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-31 08:52:20.838  1511  4362 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-31 08:52:20.838  1511  4362 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-31 08:52:20.838  1511  4362 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-31 08:52:20.838  1511  4362 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-31 08:52:20.838  1511  4362 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-31 08:52:20.838  1511  4362 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-31 08:52:20.838  1511  4362 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-31 08:52:20.838  1511  4362 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-31 08:52:20.838  1511  4362 E SQLiteOpenHelper:, 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-31 08:52:20.838  1511  4362 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-31 08:52:20.838  1511  4362 E SQLiteOpenHelper: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
08-31 08:52:20.838  1511  4362 E SQLiteOpenHelper: 	at com.google.android.gms.config.j.run(SourceFile:152)
08-31 08:52:20.838  1511  4362 E SQLiteOpenHelper: 	at java.lang.Thread.run(Thread.java:818)
08-31 08:52:20.841  1511  4362 W SQLiteOpenHelper: Opened config.db in read-only mode
,08-31 08:52:20.846   872  1994 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 3868 uid 10000
,08-31 08:52:20.848  1884  1884 I Keyboard.Facilitator: onFinishInput()
,08-31 08:52:20.853  1884  4349 I Keyboard.Facilitator.MainLanguageModelLoader: run()
,08-31 08:52:20.867   872   884 W AtomicFile: Couldn't rename file /data/system/users/0/runtime-permissions.xml to backup file /data/system/users/0/runtime-permissions.xml.bak
,08-31 08:52:20.867  1987  2084 E SQLiteLog: (3850) statement aborts at 23: [DELETE FROM icons WHERE componentName LIKE ? AND profileId = ?] disk I/O error
08-31 08:52:20.867   872   884 E PackageManager: Failed to write settings, restoring backup
08-31 08:52:20.867   872   884 E PackageManager: java.io.IOException: Couldn't create directory /data/system/users/0/runtime-permissions.xml
08-31 08:52:20.867   872   884 E PackageManager: 	at android.util.AtomicFile.startWrite(AtomicFile.java:106)
08-31 08:52:20.867   872   884 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.writePermissionsSync(Settings.java:4615)
08-31 08:52:20.867   872   884 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.-wrap1(Settings.java)
08-31 08:52:20.867   872   884 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence$MyHandler.handleMessage(Settings.java:4830)
08-31 08:52:20.867   872   884 E PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 08:52:20.867   872   884 E PackageManager: 	at android.os.Looper.loop(Looper.java:148)
08-31 08:52:20.867   872   884 E PackageManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-31 08:52:20.872   872   885 E DropBoxManagerService: Can't write: system_server_wtf
08-31 08:52:20.872   872   885 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop15.tmp: open failed: EROFS (Read-only file system)
08-31 08:52:20.872   872   885 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-31 08:52:20.872   872   885 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-31 08:52:20.872   872   885 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-31 08:52:20.872   872   885 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-31 08:52:20.872   872   885 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-31 08:52:20.872   872   885 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-31 08:52:20.872   872   885 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12543)
08-31 08:52:20.872   872   885 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.handleApplicationWtfInner(ActivityManagerService.java:12356)
08-31 08:52:20.872   872   885 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:12328)
08-31 08:52:20.872   872   885 E DropBoxManagerService: 	at android.os.Handler.handleCallback(Handler.java:739)
08-31 08:52:20.872   872   885 E DropBoxManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-31 08:52:20.872   872   885 E DropBoxManagerService: 	at android.os.Looper.loop(Looper.java:148)
08-31 08:52:20.872   872   885 E DropBoxManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-31 08:52:20.872   872   885 E DropBoxManagerService: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
08-31 08:52:20.872   872   885 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-31 08:52:20.872   872   885 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-31 08:52:20.872   872   885 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-31 08:52:20.872   872   885 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-31 08:52:20.872   872   885 E DropBoxManagerService: 	... 13 more
,08-31 08:52:20.880   872  1881 I ActivityManager: Start proc 4366:com.google.android.googlequicksearchbox:crash_report/u0a28 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
--------- beginning of crash
08-31 08:52:20.881  1987  2084 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
08-31 08:52:20.881  1987  2084 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 1987
08-31 08:52:20.881  1987  2084 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-31 08:52:20.881  1987  2084 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-31 08:52:20.881  1987  2084 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-31 08:52:20.881  1987  2084 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-31 08:52:20.881  1987  2084 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-31 08:52:20.881  1987  2084 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
08-31 08:52:20.881  1987  2084 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
08-31 08:52:20.881  1987  2084 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
08-31 08:52:20.881  1987  2084 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
08-31 08:52:20.881  1987  2084 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-31 08:52:20.881  1987  2084 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-31 08:52:20.881  1987  2084 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-31 08:52:20.884   872  2255 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
08-31 08:52:20.886   872  4373 E DropBoxManagerService: Can't write: system_app_crash
08-31 08:52:20.886   872  4373 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop125.tmp: open failed: EROFS (Read-only file system)
08-31 08:52:20.886   872  4373 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-31 08:52:20.886   872  4373 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-31 08:52:20.886   872  4373 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-31 08:52:20.886   872  4373 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-31 08:52:20.886   872  4373 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-31 08:52:20.886   872  4373 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-31 08:52:20.886   872  4373 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-31 08:52:20.886   872  4373 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-31 08:52:20.886   872  4373 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-31 08:52:20.886   872  4373 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-31 08:52:20.886   872  4373 E DropBoxManagerService: 	... 5 more
,08-31 08:52:20.933  1987  2084 I Process : Sending signal. PID: 1987 SIG: 9
,08-31 08:52:20.983  1884  4349 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /data/user/0/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
,08-31 08:52:20.985  1884  4349 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
,08-31 08:52:20.985  1884  4349 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
,08-31 08:52:20.988  1884  4349 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Contacts.dict
,08-31 08:52:20.988  1884  4349 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = history
,08-31 08:52:20.989  1884  4349 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loaded File = UserHistory.en_US.dict
,08-31 08:52:20.989  1884  4349 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = user
,08-31 08:52:20.991  1884  4349 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Personal.en_US.dict
,08-31 08:52:20.993  1884  4349 I Keyboard.Facilitator.PersonalDictionaryLoader: run() : Loaded (exit)
,08-31 08:52:20.994  1884  4349 I Keyboard.Facilitator.Delight2FileSweeper: run()
,08-31 08:52:21.007  1884  4349 I Keyboard.Facilitator.RecurringTaskScheduler: run()
,08-31 08:52:21.007  1884  4349 I StatsUtilsManager: startPeriodStatsRecorder() : Success
08-31 08:52:21.007  1884  4349 I PeriodicStatsRecorder: shouldRecordStats() = Too Soon
,08-31 08:52:21.031  1716  4383 D GFEEDBACK_SendErrorReportOperation: Error doing instant send: java.io.IOException: failed to create reports directory
,08-31 08:52:21.031  1716  4383 E GFEEDBACK_SendErrorReportOperation: Error saving report: java.io.IOException: failed to create reports directory
,08-31 08:52:21.034  4350  4350 W System  : ClassLoader referenced unknown path: /system/app/UserDictionaryProvider/lib/arm
,08-31 08:52:21.055   872  1994 I ActivityManager: Start proc 4385:com.android.musicfx/u0a18 for broadcast com.android.musicfx/.Compatibility$Receiver
,08-31 08:52:21.057   872  1881 D GraphicsStats: Buffer count: 1
08-31 08:52:21.058   872  2078 I WindowState: WIN DEATH: Window{e8c2c43 u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL}
,08-31 08:52:21.071  4350  4384 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,08-31 08:52:21.074   872  1881 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 1987) has died
,08-31 08:52:21.074   872  1881 W ActivityManager: Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.reflection.ReflectionService in 1000ms
08-31 08:52:21.078   872  1881 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
,08-31 08:52:21.091  4350  4364 E SQLiteDatabase: Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
08-31 08:52:21.091  4350  4364 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-31 08:52:21.091  4350  4364 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-31 08:52:21.091  4350  4364 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-31 08:52:21.091  4350  4364 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-31 08:52:21.091  4350  4364 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-31 08:52:21.091  4350  4364 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-31 08:52:21.091  4350  4364 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-31 08:52:21.091  4350  4364 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-31 08:52:21.091  4350  4364 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-31 08:52:21.091  4350  4364 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-31 08:52:21.091  4350  4364 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-31 08:52:21.091  4350  4364 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-31 08:52:21.091  4350  4364 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-31 08:52:21.091  4350  4364 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-31 08:52:21.091  4350  4364 E SQLiteDatabase: 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
08-31 08:52:21.091  4350  4364 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1596)
08-31 08:52:21.091  4350  4364 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1687)
08-31 08:52:21.091  4350  4364 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
08-31 08:52:21.091  4350  4364 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 08:52:21.091  4350  4364 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-31 08:52:21.091  4350  4364 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-31 08:52:21.092  4350  4364 E SQLiteOpenHelper: Couldn't open contacts2.db for writing (will try read-only):
08-31 08:52:21.092  4350  4364 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-31 08:52:21.092  4350  4364 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-31 08:52:21.092  4350  4364 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-31 08:52:21.092  4350  4364 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-31 08:52:21.092  4350  4364 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-31 08:52:21.092  4350  4364 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-31 08:52:21.092  4350  4364 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-31 08:52:21.092  4350  4364 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-31 08:52:21.092  4350  4364 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-31 08:52:21.092  4350  4364 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-31 08:52:21.092  4350  4364 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-31 08:52:21.092  4350  4364 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-31 08:52:21.092  4350  4364 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-31 08:52:21.092  4350  4364 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-31 08:52:21.092  4350  4364 E SQLiteOpenHelper: 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
08-31 08:52:21.092  4350  4364 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1596)
08-31 08:52:21.092  4350  4364 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1687)
08-31 08:52:21.092  4350  4364 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
08-31 08:52:21.092  4350  4364 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 08:52:21.092  4350  4364 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:148)
08-31 08:52:21.092  4350  4364 E SQLiteOpenHelper: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-31 08:52:21.095   872   885 I ActivityManager: Start proc 4397:com.google.android.googlequicksearchbox/u0a28 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,08-31 08:52:21.114  4385  4385 W System  : ClassLoader referenced unknown path: /system/priv-app/MusicFX/lib/arm
,08-31 08:52:21.152  1511  1511 E SQLiteLog: (3850) statement aborts at 26: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
,08-31 08:52:21.153  1511  1511 D AndroidRuntime: Shutting down VM
08-31 08:52:21.153  1511  1511 E AndroidRuntime: FATAL EXCEPTION: main
08-31 08:52:21.153  1511  1511 E AndroidRuntime: Process: com.google.process.gapps, PID: 1511
08-31 08:52:21.153  1511  1511 E AndroidRuntime: java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-31 08:52:21.153  1511  1511 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2732)
08-31 08:52:21.153  1511  1511 E AndroidRuntime: 	at android.app.ActivityThread.-wrap14(ActivityThread.java)
08-31 08:52:21.153  1511  1511 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1421)
08-31 08:52:21.153  1511  1511 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 08:52:21.153  1511  1511 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-31 08:52:21.153  1511  1511 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-31 08:52:21.153  1511  1511 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-31 08:52:21.153  1511  1511 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-31 08:52:21.153  1511  1511 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-31 08:52:21.153  1511  1511 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-31 08:52:21.153  1511  1511 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-31 08:52:21.153  1511  1511 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-31 08:52:21.153  1511  1511 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-31 08:52:21.153  1511  1511 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-31 08:52:21.153  1511  1511 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
08-31 08:52:21.153  1511  1511 E AndroidRuntime: 	at com.google.android.gms.gcm.bg.a(SourceFile:310)
,08-31 08:52:21.153  1511  1511 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
08-31 08:52:21.153  1511  1511 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
08-31 08:52:21.153  1511  1511 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2725)
08-31 08:52:21.153  1511  1511 E AndroidRuntime: 	... 8 more
08-31 08:52:21.156   872  4412 E DropBoxManagerService: Can't write: system_app_crash
08-31 08:52:21.156   872  4412 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop126.tmp: open failed: EROFS (Read-only file system)
08-31 08:52:21.156   872  4412 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-31 08:52:21.156   872  4412 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-31 08:52:21.156   872  4412 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-31 08:52:21.156   872  4412 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-31 08:52:21.156   872  4412 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-31 08:52:21.156   872  4412 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-31 08:52:21.156   872  4412 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-31 08:52:21.156   872  4412 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-31 08:52:21.156   872  4412 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-31 08:52:21.156   872  4412 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-31 08:52:21.156   872  4412 E DropBoxManagerService: 	... 5 more
,08-31 08:52:21.156  1511  1511 I Process : Sending signal. PID: 1511 SIG: 9
08-31 08:52:21.159  4397  4397 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.googlequicksearchbox/databases/launcher.db'.
08-31 08:52:21.159  4397  4397 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-31 08:52:21.159  4397  4397 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-31 08:52:21.159  4397  4397 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-31 08:52:21.159  4397  4397 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-31 08:52:21.159  4397  4397 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-31 08:52:21.159  4397  4397 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-31 08:52:21.159  4397  4397 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-31 08:52:21.159  4397  4397 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-31 08:52:21.159  4397  4397 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-31 08:52:21.159  4397  4397 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-31 08:52:21.159  4397  4397 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-31 08:52:21.159  4397  4397 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-31 08:52:21.159  4397  4397 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-31 08:52:21.159  4397  4397 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-31 08:52:21.159  4397  4397 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
08-31 08:52:21.159  4397  4397 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
08-31 08:52:21.159  4397  4397 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-31 08:52:21.159  4397  4397 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
08-31 08:52:21.159  4397  4397 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-31 08:52:21.159  4397  4397 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-31 08:52:21.159  4397  4397 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-31 08:52:21.159  4397  4397 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java),
08-31 08:52:21.159  4397  4397 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-31 08:52:21.159  4397  4397 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 08:52:21.159  4397  4397 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-31 08:52:21.159  4397  4397 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-31 08:52:21.159  4397  4397 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-31 08:52:21.159  4397  4397 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-31 08:52:21.159  4397  4397 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-31 08:52:21.160  4397  4397 D AndroidRuntime: Shutting down VM
08-31 08:52:21.167  4397  4397 E AndroidRuntime: FATAL EXCEPTION: main
08-31 08:52:21.167  4397  4397 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 4397
08-31 08:52:21.167  4397  4397 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.android.launcher3.LauncherProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-31 08:52:21.167  4397  4397 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5156)
08-31 08:52:21.167  4397  4397 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-31 08:52:21.167  4397  4397 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-31 08:52:21.167  4397  4397 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-31 08:52:21.167  4397  4397 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-31 08:52:21.167  4397  4397 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 08:52:21.167  4397  4397 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-31 08:52:21.167  4397  4397 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-31 08:52:21.167  4397  4397 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-31 08:52:21.167  4397  4397 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-31 08:52:21.167  4397  4397 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-31 08:52:21.167  4397  4397 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-31 08:52:21.167  4397  4397 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-31 08:52:21.167  4397  4397 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207),
08-31 08:52:21.167  4397  4397 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-31 08:52:21.167  4397  4397 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-31 08:52:21.167  4397  4397 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-31 08:52:21.167  4397  4397 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-31 08:52:21.167  4397  4397 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-31 08:52:21.167  4397  4397 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-31 08:52:21.167  4397  4397 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-31 08:52:21.167  4397  4397 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-31 08:52:21.167  4397  4397 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-31 08:52:21.167  4397  4397 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-31 08:52:21.167  4397  4397 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-31 08:52:21.167  4397  4397 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
08-31 08:52:21.167  4397  4397 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
08-31 08:52:21.167  4397  4397 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-31 08:52:21.167  4397  4397 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
08-31 08:52:21.167  4397  4397 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-31 08:52:21.167  4397  4397 E AndroidRuntime: 	... 10 more
08-31 08:52:21.169   872  1994 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
08-31 08:52:21.170  4397  4397 I Process : Sending signal. PID: 4397 SIG: 9
,08-31 08:52:21.170   872  4413 E DropBoxManagerService: Can't write: system_app_crash
08-31 08:52:21.170   872  4413 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop127.tmp: open failed: EROFS (Read-only file system)
08-31 08:52:21.170   872  4413 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-31 08:52:21.170   872  4413 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-31 08:52:21.170   872  4413 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-31 08:52:21.170   872  4413 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-31 08:52:21.170   872  4413 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-31 08:52:21.170   872  4413 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-31 08:52:21.170   872  4413 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-31 08:52:21.170   872  4413 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-31 08:52:21.170   872  4413 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-31 08:52:21.170   872  4413 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-31 08:52:21.170   872  4413 E DropBoxManagerService: 	... 5 more
08-31 08:52:21.179  1716  4383 D GFEEDBACK_SendErrorReportOperation: Error doing instant send: java.io.IOException: failed to create reports directory
08-31 08:52:21.180  1716  4383 E GFEEDBACK_SendErrorReportOperation: Error saving report: java.io.IOException: failed to create reports directory
08-31 08:52:21.187  4350  4364 E SQLiteLog: (8) statement aborts at 43: [CREATE TABLE IF NOT EXISTS presence_db.presence (presence_data_id INTEGER PRIMARY KEY REFERENCES data(_id),protocol INTEGER NOT NULL,custom_protocol TEXT,im_handle TEXT,im_account TEXT
,08-31 08:52:21.196  4350  4384 E SQLiteDatabase: Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
08-31 08:52:21.196  4350  4384 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-31 08:52:21.196  4350  4384 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-31 08:52:21.196  4350  4384 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-31 08:52:21.196  4350  4384 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-31 08:52:21.196  4350  4384 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-31 08:52:21.196  4350  4384 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-31 08:52:21.196  4350  4384 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-31 08:52:21.196  4350  4384 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-31 08:52:21.196  4350  4384 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-31 08:52:21.196  4350  4384 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-31 08:52:21.196  4350  4384 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-31 08:52:21.196  4350  4384 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-31 08:52:21.196  4350  4384 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-31 08:52:21.196  4350  4384 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-31 08:52:21.196  4350  4384 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:191)
08-31 08:52:21.196  4350  4384 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
08-31 08:52:21.196  4350  4384 E SQLiteDatabase: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
08-31 08:52:21.196  4350  4384 E SQLiteDatabase: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
08-31 08:52:21.196  4350  4384 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
08-31 08:52:21.196  4350  4384 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
08-31 08:52:21.196  4350  4384 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-31 08:52:21.196  4350  4384 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 08:52:21.196  4350  4384 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-31 08:52:21.196  4350  4384 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-31 08:52:21.196  4350  4384 E AndroidRuntime: FATAL EXCEPTION: IntentService[VoicemailCleanupService]
08-31 08:52:21.196  4350  4384 E AndroidRuntime: Process: android.process.acore, PID: 4350
08-31 08:52:21.196  4350  4384 E AndroidRuntime: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-31 08:52:21.196  4350  4384 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-31 08:52:21.196  4350  4384 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-31 08:52:21.196  4350  4384 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-31 08:52:21.196  4350  4384 E Andr,oidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-31 08:52:21.196  4350  4384 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-31 08:52:21.196  4350  4384 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-31 08:52:21.196  4350  4384 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-31 08:52:21.196  4350  4384 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-31 08:52:21.196  4350  4384 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-31 08:52:21.196  4350  4384 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-31 08:52:21.196  4350  4384 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-31 08:52:21.196  4350  4384 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-31 08:52:21.196  4350  4384 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-31 08:52:21.196  4350  4384 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:191)
08-31 08:52:21.196  4350  4384 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
08-31 08:52:21.196  4350  4384 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
08-31 08:52:21.196  4350  4384 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
08-31 08:52:21.196  4350  4384 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
08-31 08:52:21.196  4350  4384 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
08-31 08:52:21.196  4350  4384 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-31 08:52:21.196  4350  4384 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 08:52:21.196  4350  4384 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-31 08:52:21.196  4350  4384 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-31 08:52:21.199   872  1311 D WifiService: Client connection lost with reason: 4
08-31 08:52:21.199   281   337 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0

```
