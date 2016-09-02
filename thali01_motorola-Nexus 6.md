#### Test 83268893e6b65d6_thali01_motorola-Nexus 6 Logs


```
--------- beginning of main
09-02 15:25:52.004  1528  1528 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-02 15:25:52.016  1528  1528 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
09-02 15:25:52.020  1528  1528 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
09-02 15:25:52.051  1528  2380 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
09-02 15:25:52.052  1528  2380 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
09-02 15:25:52.052  1528  2380 I GLSUser : [GLSUser] Extracting token using key: Auth
09-02 15:25:52.052  1528  2380 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
09-02 15:25:52.069  3504  3504 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
09-02 15:25:52.069  3504  3504 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
09-02 15:25:52.069  3504  3504 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 3.
09-02 15:25:52.660  3778  3778 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
09-02 15:25:52.665  3778  3778 D AndroidRuntime: CheckJNI is OFF
09-02 15:25:52.709  3778  3778 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
09-02 15:25:52.758  3778  3778 I Radio-JNI: register_android_hardware_Radio DONE
09-02 15:25:52.782  3778  3778 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
09-02 15:25:52.787   872  1994 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
09-02 15:25:52.866  2018  2031 W SearchService: Abort, client detached.
09-02 15:25:52.868  2018  2018 I HotwordDetector: Closing mic
09-02 15:25:52.869  2018  2310 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@3492d33
09-02 15:25:52.871  2018  2328 E AudioRecord-JNI: Error -4 during AudioRecord native read
09-02 15:25:52.889  3778  3778 D AndroidRuntime: Shutting down VM
09-02 15:25:52.901   872  1944 I ActivityManager: Start proc 3788:com.test.thalitest/u0a0 for activity com.test.thalitest/.MainActivity
09-02 15:25:52.919   376  2330 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
09-02 15:25:52.921   376  2330 D audio_hw_primary: disable_snd_device: snd_device(61: voice-rec-mic)
09-02 15:25:52.925   376  1277 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
09-02 15:25:52.926  2018  2327 I MicroRecognitionRnrImpl: Detection finished
09-02 15:25:52.927  2018  2319 I MicroRecognitionRnrImpl: Stopping hotword detection.
09-02 15:25:52.995  3788  3788 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
09-02 15:25:53.024  3788  3788 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
09-02 15:25:53.033  3788  3788 I LibraryLoader: Time to load native libraries: 4 ms (timestamps 470-474)
09-02 15:25:53.033  3788  3788 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-02 15:25:53.065  3788  3788 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {ab2911c}
09-02 15:25:53.065  3788  3788 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-02 15:25:53.065  3788  3788 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
09-02 15:25:53.075  3788  3788 I BrowserStartupController: Initializing chromium process, singleProcess=true
09-02 15:25:53.076  3788  3788 E SysUtils: ApplicationContext is null in ApplicationStatus
09-02 15:25:53.100  3788  3788 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
09-02 15:25:53.110  3788  3788 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-02 15:25:53.110  3788  3788 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-02 15:25:53.111  3788  3788 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
09-02 15:25:53.111  3788  3788 I Adreno  : Build Date                       : 10/20/15
09-02 15:25:53.111  3788  3788 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
09-02 15:25:53.111  3788  3788 I Adreno  : Local Branch                     : M14
09-02 15:25:53.111  3788  3788 I Adreno  : Remote Branch                    : 
09-02 15:25:53.111  3788  3788 I Adreno  : Remote Branch                    : 
09-02 15:25:53.111  3788  3788 I Adreno  : Reconstruct Branch               : 
,09-02 15:25:53.169   872   889 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@f5ab6e4:true
,09-02 15:25:53.234  3788  3788 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,09-02 15:25:53.254  3788  3788 D SystemWebViewEngine: CordovaWebView is running on device made by: motorola
,09-02 15:25:53.341  3788  3827 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,09-02 15:25:53.352  3788  3813 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,09-02 15:25:53.390  3788  3827 I OpenGLRenderer: Initialized EGL, version 1.4
,09-02 15:25:53.500   872   890 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +610ms
,09-02 15:25:53.504  1871  1871 I Keyboard.Facilitator: onFinishInput()
,09-02 15:25:53.569   872  1867 D NetlinkSocketObserver: NeighborEvent{elapsedMs=121010, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-02 15:25:53.618  3788  3788 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 3788
,09-02 15:25:53.734   872  1693 I ActivityManager: Killing 3219:com.google.android.gm/u0a78 (adj 15): empty #17
,09-02 15:25:53.744  3788  3788 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,09-02 15:25:53.773   872  1693 I ActivityManager: Killing 3102:com.google.android.apps.maps/u0a65 (adj 15): empty #18
,09-02 15:25:53.946  3788  3829 D jxcore_app_log: JniHelper::setJavaVM(0xb4cfc000), pthread_self() = -1686243024
,09-02 15:25:53.952  3788  3829 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
09-02 15:25:53.952  3788  3829 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
09-02 15:25:53.952  3788  3829 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
09-02 15:25:53.952  3788  3829 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
09-02 15:25:53.952  3788  3829 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,09-02 15:25:53.952  3788  3829 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@12997e0 added. We now have 1 listener(s)
,09-02 15:25:53.959  3788  3829 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: F8:CF:C5:D9:E5:61
,09-02 15:25:53.965  3788  3829 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-02 15:25:53.967  3788  3829 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-02 15:25:53.968  3788  3829 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-02 15:25:53.976  3788  3829 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
09-02 15:25:53.976  3788  3829 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
09-02 15:25:53.976  3788  3829 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
09-02 15:25:53.976  3788  3829 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: F8:CF:C5:D9:E5:61
09-02 15:25:53.976  3788  3829 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
09-02 15:25:53.976  3788  3829 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
09-02 15:25:53.976  3788  3829 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
09-02 15:25:53.976  3788  3829 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
09-02 15:25:53.976  3788  3829 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
09-02 15:25:53.976  3788  3829 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
09-02 15:25:53.976  3788  3829 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
09-02 15:25:53.976  3788  3829 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
09-02 15:25:53.976  3788  3829 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
09-02 15:25:53.976  3788  3829 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,09-02 15:25:53.976  3788  3829 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d55093f added. We now have 1 listener(s)
09-02 15:25:53.977  3788  3829 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-02 15:25:53.982  3788  3829 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-02 15:25:53.982  3788  3829 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
09-02 15:25:53.982  3788  3829 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
09-02 15:25:53.982  3788  3829 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
,09-02 15:25:53.982  3788  3829 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
09-02 15:25:53.983   872  1307 D WifiService: New client listening to asynchronous messages
,09-02 15:25:53.991  3788  3829 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-02 15:25:53.991  3788  3829 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is F8:CF:C5:D9:E5:61
,09-02 15:25:54.001  3788  3829 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,09-02 15:25:54.002  3788  3829 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-02 15:25:54.002  3788  3829 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 15:25:54.002  3788  3829 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-02 15:25:54.002  3788  3829 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-02 15:25:54.002  3788  3829 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-02 15:25:54.002  3788  3829 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-02 15:25:54.002  3788  3829 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-02 15:25:54.002  3788  3829 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-02 15:25:54.002  3788  3829 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
09-02 15:25:54.002  3788  3829 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-02 15:25:54.003  3788  3829 I io.jxcore.node.LifeCycleMonitor: start: OK
,09-02 15:25:54.084  3788  3788 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-02 15:25:54.089  3788  3788 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-02 15:25:54.098  3788  3788 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,09-02 15:25:55.129   872  1306 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-02 15:25:55.334  3788  3836 W jxcore-log: Initializing JXcore engine
,09-02 15:25:55.335  3788  3836 W jxcore-log: JXcore engine is ready
,09-02 15:25:55.385  3836  3836 W Thread-321: type=1400 audit(0.0:4): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=8945 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,09-02 15:25:55.385  3836  3836 W Thread-321: type=1400 audit(0.0:5): avc: denied { ioctl } for path="socket:[12726]" dev="sockfs" ino=12726 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,09-02 15:25:55.385  3836  3836 W Thread-321: type=1400 audit(0.0:6): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0,
,09-02 15:25:55.385  3836  3836 W Thread-321: type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[25298]" dev="sockfs" ino=25298 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,09-02 15:25:55.397  3788  3836 W jxcore-log: Starting JXcore engine
,09-02 15:25:55.474  3788  3836 W jxcore-log: Platform android
09-02 15:25:55.474  3788  3836 W jxcore-log: 
,09-02 15:25:55.474  3788  3836 W jxcore-log: Process ARCH arm
09-02 15:25:55.474  3788  3836 W jxcore-log: 
,09-02 15:25:55.659  3788  3836 I jxcore-log: JXcore Cordova bridge is ready!
09-02 15:25:55.659  3788  3836 I jxcore-log: 
,09-02 15:25:55.659  3788  3836 W jxcore-log: JXcore engine is started
,09-02 15:25:55.674  3788  3829 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,09-02 15:25:55.681  3788  3788 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,09-02 15:25:58.822   872  1867 D NetlinkSocketObserver: NeighborEvent{elapsedMs=126263, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-02 15:26:05.550  3788  3836 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
09-02 15:26:05.550  3788  3836 I jxcore-log: 
,09-02 15:26:05.553  3788  3836 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
09-02 15:26:05.553  3788  3836 I jxcore-log: 
,09-02 15:26:05.564  3788  3836 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-02 15:26:05.564  3788  3836 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 15:26:05.564  3788  3836 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-02 15:26:05.564  3788  3836 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-02 15:26:05.564  3788  3836 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-02 15:26:05.564  3788  3836 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-02 15:26:05.564  3788  3836 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-02 15:26:05.564  3788  3836 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-02 15:26:05.568  3788  3836 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-02 15:26:05.570  3788  3836 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
09-02 15:26:05.570  3788  3836 I jxcore-log: 
,09-02 15:26:05.572  3788  3836 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
09-02 15:26:05.572  3788  3836 I jxcore-log: 
,09-02 15:26:06.067  3788  3836 D executeNativeTests: Running unit tests
,09-02 15:26:06.126  3788  3836 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-02 15:26:06.126  3788  3836 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4a6b6b0 added. We now have 2 listener(s)
,09-02 15:26:06.127  3788  3836 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-02 15:26:06.127  3788  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-02 15:26:06.127  3788  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-02 15:26:06.127  3788  3836 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-02 15:26:06.127  3788  3836 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c59929 added. We now have 2 listener(s)
09-02 15:26:06.127  3788  3836 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-02 15:26:06.128  3788  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-02 15:26:06.131  3788  3836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-02 15:26:06.148  3788  3836 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-02 15:26:06.148  3788  3836 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 15:26:06.148  3788  3836 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-02 15:26:06.148  3788  3836 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-02 15:26:06.148  3788  3836 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-02 15:26:06.148  3788  3836 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-02 15:26:06.148  3788  3836 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-02 15:26:06.148  3788  3836 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-02 15:26:06.153  3788  3836 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-02 15:26:06.153  3788  3836 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-02 15:26:06.155  3788  3836 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-02 15:26:06.157  3788  3836 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,09-02 15:26:06.158  3788  3836 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-02 15:26:06.159  3788  3836 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
09-02 15:26:06.159  3788  3836 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
,09-02 15:26:06.159  3788  3836 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
,09-02 15:26:06.159  3788  3836 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,09-02 15:26:06.161  3788  3836 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,09-02 15:26:06.161  3788  3836 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-02 15:26:06.162  3788  3836 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-02 15:26:06.162  3788  3836 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-02 15:26:06.162  3788  3836 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-02 15:26:06.162  3788  3836 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 15:26:06.162  3788  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-02 15:26:06.162  3788  3836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-02 15:26:06.162  3788  3836 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4a6b6b0 removed from the list
09-02 15:26:06.162  3788  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose,
09-02 15:26:06.162  3788  3836 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c59929 removed from the list
09-02 15:26:06.158  3788  3788 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-02 15:26:06.163  3788  3836 D io.jxcore.node.ConnectivityMonitor: stop
,09-02 15:26:06.163  3788  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 15:26:06.163  3788  3836 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 15:26:06.163  3788  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-02 15:26:06.169  3788  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-02 15:26:06.170  3788  3788 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-02 15:26:06.170  3788  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-02 15:26:06.171  3788  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 15:26:06.171  3788  3836 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c59929 not in the list
,09-02 15:26:06.176  3788  3836 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
,09-02 15:26:06.179  3788  3836 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-02 15:26:06.179  3788  3836 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-02 15:26:06.179  3788  3836 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-02 15:26:06.180  3788  3836 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 15:26:06.180  3788  3836 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 15:26:06.180  3788  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-02 15:26:06.180  3788  3836 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4a6b6b0 not in the list
09-02 15:26:06.180  3788  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 15:26:06.181  3788  3836 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c59929 not in the list
09-02 15:26:06.181  3788  3836 D io.jxcore.node.ConnectivityMonitor: stop
,09-02 15:26:06.181  3788  3836 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 15:26:06.181  3788  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 15:26:06.182  3788  3836 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-02 15:26:06.182  3788  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-02 15:26:06.183  3788  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-02 15:26:06.184  3788  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-02 15:26:06.184  3788  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-02 15:26:06.184  3788  3836 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c59929 not in the list
,09-02 15:26:06.197  3788  3836 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,09-02 15:26:06.197  3788  3836 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-02 15:26:06.197  3788  3836 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-02 15:26:06.197  3788  3836 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-02 15:26:06.197  3788  3836 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-02 15:26:06.197  3788  3836 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-02 15:26:06.198  3788  3836 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
,09-02 15:26:06.198  3788  3836 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-02 15:26:06.198  3788  3836 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-02 15:26:06.198  3788  3836 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-02 15:26:06.198  3788  3836 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
,09-02 15:26:06.198  3788  3836 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-02 15:26:06.198  3788  3836 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-02 15:26:06.198  3788  3836 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
,09-02 15:26:06.198  3788  3836 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-02 15:26:06.198  3788  3836 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-02 15:26:06.198  3788  3836 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-02 15:26:06.198  3788  3836 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-02 15:26:06.198  3788  3836 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-02 15:26:06.198  3788  3836 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810],
09-02 15:26:06.198  3788  3836 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-02 15:26:06.199  3788  3836 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-02 15:26:06.199  3788  3836 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-02 15:26:06.199  3788  3836 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-02 15:26:06.199  3788  3836 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-02 15:26:06.199  3788  3836 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
,09-02 15:26:06.199  3788  3836 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-02 15:26:06.199  3788  3836 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-02 15:26:06.199  3788  3836 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-02 15:26:06.199  3788  3836 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-02 15:26:06.199  3788  3836 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910],
09-02 15:26:06.199  3788  3836 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-02 15:26:06.199  3788  3836 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-02 15:26:06.199  3788  3836 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-02 15:26:06.199  3788  3836 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-02 15:26:06.200  3788  3836 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 15:26:06.200  3788  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 15:26:06.200  3788  3836 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4a6b6b0 not in the list
09-02 15:26:06.200  3788  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 15:26:06.200  3788  3836 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c59929 not in the list
09-02 15:26:06.200  3788  3836 D io.jxcore.node.ConnectivityMonitor: stop
09-02 15:26:06.200  3788  3836 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 15:26:06.200  3788  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 15:26:06.200  3788  3836 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 15:26:06.200  3788  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-02 15:26:06.201  3788  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-02 15:26:06.201  3788  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-02 15:26:06.201  3788  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 15:26:06.201  3788  3836 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c59929 not in the list
09-02 15:26:06.202  3788  3836 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-02 15:26:06.203  3788  3836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-02 15:26:06.207  3788  3836 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-02 15:26:06.207  3788  3836 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 15:26:06.207  3788  3836 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-02 15:26:06.207  3788  3836 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-02 15:26:06.207  3788  3836 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-02 15:26:06.207  3788  3836 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-02 15:26:06.207  3788  3836 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-02 15:26:06.207  3788  3836 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-02 15:26:06.209  3788  3836 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-02 15:26:06.209  3788  3836 D io.jxcore.node.ConnectivityMonitor: start: OK
09-02 15:26:06.209  3788  3836 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-02 15:26:06.209  3788  3836 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-02 15:26:06.209  3788  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,09-02 15:26:06.209  3788  3836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-02 15:26:06.209  3788  3836 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-02 15:26:06.211  3788  3788 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-02 15:26:06.212  3788  3836 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-02 15:26:06.212  3788  3836 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-02 15:26:06.214  3788  3788 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-02 15:26:06.216  3788  3836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-02 15:26:06.219  3788  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-02 15:26:06.219  3788  3836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-02 15:26:06.221  3788  3836 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
,09-02 15:26:06.225  3788  3836 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
09-02 15:26:06.225  3788  3836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-02 15:26:06.225  3788  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,09-02 15:26:06.226  3788  3836 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-02 15:26:06.227  3788  3836 D BluetoothAdapter: STATE_ON
,09-02 15:26:06.231  2655  2665 D BtGatt.GattService: registerClient() - UUID=32c2bf46-984a-4871-80a1-95e32749a6aa
,09-02 15:26:06.232  2655  2678 D BtGatt.GattService: onClientRegistered() - UUID=32c2bf46-984a-4871-80a1-95e32749a6aa, clientIf=5
,09-02 15:26:06.233  3788  3799 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-02 15:26:06.234  2655  2813 D BtGatt.GattService: start scan with filters
,09-02 15:26:06.237  3788  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-02 15:26:06.237  2655  2688 D BtGatt.ScanManager: handling starting scan
09-02 15:26:06.237  3788  3836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,09-02 15:26:06.237  3788  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,09-02 15:26:06.237  3788  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
09-02 15:26:06.238  2655  2688 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@12ec4c6
09-02 15:26:06.240  3788  3836 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-02 15:26:06.240  3788  3836 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-02 15:26:06.240  3788  3788 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-02 15:26:06.242  3788  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-02 15:26:06.244  3788  3836 I io.jxcore.node.ConnectionHelper: start: OK
,09-02 15:26:06.246  2655  2678 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,09-02 15:26:06.246  2655  2678 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-02 15:26:06.246  2655  2688 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-02 15:26:06.248  3788  3836 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-02 15:26:06.248  3788  3836 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,09-02 15:26:06.248  3788  3836 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-02 15:26:06.248  3788  3836 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,09-02 15:26:06.248  3788  3836 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 15:26:06.248  3788  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-02 15:26:06.248  3788  3836 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,09-02 15:26:06.248  3788  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-02 15:26:06.248  3788  3836 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-02 15:26:06.249  3788  3836 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-02 15:26:06.249  3788  3836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-02 15:26:06.249  3788  3836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-02 15:26:06.250  3788  3836 D BluetoothAdapter: STATE_ON
09-02 15:26:06.250  2655  2665 D BtGatt.GattService: stopScan() - queue size =1
09-02 15:26:06.251  2655  2813 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-02 15:26:06.251  3788  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-02 15:26:06.251  3788  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-02 15:26:06.251  3788  3836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-02 15:26:06.251  3788  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,09-02 15:26:06.251  3788  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-02 15:26:06.252  3788  3836 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-02 15:26:06.252  3788  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-02 15:26:06.252  3788  3836 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-02 15:26:06.253  3788  3836 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-02 15:26:06.253  3788  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-02 15:26:06.253  2655  2678 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
09-02 15:26:06.253  2655  2678 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-02 15:26:06.254  2655  2688 D BtGatt.ScanManager: Starting BLE batch scan
09-02 15:26:06.254  2655  2688 D BtGatt.ScanManager: configuring batch scan storage, appIf 5,
09-02 15:26:06.255  3788  3788 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-02 15:26:06.255  3788  3788 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-02 15:26:06.255  3788  3788 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-02 15:26:06.255  3788  3836 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-02 15:26:06.255  3788  3836 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 15:26:06.255  3788  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-02 15:26:06.255  3788  3836 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4a6b6b0 not in the list
09-02 15:26:06.255  3788  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-02 15:26:06.255  3788  3836 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c59929 not in the list
,09-02 15:26:06.255  3788  3836 D io.jxcore.node.ConnectivityMonitor: stop
,09-02 15:26:06.255  3788  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 15:26:06.256  3788  3836 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-02 15:26:06.257  3788  3836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-02 15:26:06.260  3788  3836 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-02 15:26:06.260  3788  3836 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 15:26:06.260  3788  3836 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-02 15:26:06.260  3788  3836 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-02 15:26:06.260  3788  3836 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-02 15:26:06.260  3788  3836 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-02 15:26:06.260  3788  3836 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-02 15:26:06.260  3788  3836 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-02 15:26:06.262  3788  3836 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-02 15:26:06.262  3788  3836 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-02 15:26:06.263  3788  3836 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-02 15:26:06.263  3788  3836 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-02 15:26:06.263  3788  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,09-02 15:26:06.263  3788  3836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-02 15:26:06.263  3788  3836 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-02 15:26:06.264  3788  3788 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-02 15:26:06.266  3788  3788 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-02 15:26:06.267  2655  2678 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-02 15:26:06.268  2655  2678 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-02 15:26:06.268  3788  3836 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-02 15:26:06.269  3788  3836 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-02 15:26:06.271  3788  3836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-02 15:26:06.272  3788  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-02 15:26:06.272  3788  3836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-02 15:26:06.275  2655  2678 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-02 15:26:06.276  2655  2678 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-02 15:26:06.277  3788  3836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-02 15:26:06.277  3788  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-02 15:26:06.277  3788  3836 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-02 15:26:06.278  3788  3836 D BluetoothAdapter: STATE_ON
,09-02 15:26:06.280  2655  2813 D BtGatt.GattService: registerClient() - UUID=0a9a5e12-dab4-4bbe-8155-ea7dc5d009a4
09-02 15:26:06.280  2655  2678 D BtGatt.GattService: onClientRegistered() - UUID=0a9a5e12-dab4-4bbe-8155-ea7dc5d009a4, clientIf=5
,09-02 15:26:06.280  3788  3800 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-02 15:26:06.280  2655  2665 D BtGatt.GattService: start scan with filters
,09-02 15:26:06.282  3788  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-02 15:26:06.282  3788  3836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-02 15:26:06.282  3788  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-02 15:26:06.283  3788  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-02 15:26:06.284  2655  2678 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
09-02 15:26:06.284  2655  2678 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-02 15:26:06.284  2655  2688 D BtGatt.ScanManager: stopping BLe Batch
,09-02 15:26:06.285  3788  3836 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-02 15:26:06.285  3788  3788 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-02 15:26:06.285  3788  3836 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-02 15:26:06.286  3788  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-02 15:26:06.288  3788  3836 I io.jxcore.node.ConnectionHelper: start: OK
,09-02 15:26:06.290  3788  3836 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-02 15:26:06.290  3788  3836 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,09-02 15:26:06.290  3788  3836 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-02 15:26:06.290  3788  3836 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-02 15:26:06.290  3788  3836 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 15:26:06.290  3788  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-02 15:26:06.290  2655  2678 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,09-02 15:26:06.290  2655  2678 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-02 15:26:06.290  2655  2688 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
09-02 15:26:06.290  3788  3836 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-02 15:26:06.290  3788  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,09-02 15:26:06.291  3788  3836 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-02 15:26:06.291  3788  3836 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-02 15:26:06.291  3788  3836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-02 15:26:06.291  3788  3836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-02 15:26:06.291  3788  3836 D BluetoothAdapter: STATE_ON
09-02 15:26:06.292  2655  2813 D BtGatt.GattService: stopScan() - queue size =0
,09-02 15:26:06.292  2655  2666 D BtGatt.GattService: unregisterClient() - clientIf=5
09-02 15:26:06.293  3788  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-02 15:26:06.293  3788  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-02 15:26:06.293  3788  3836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-02 15:26:06.293  3788  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-02 15:26:06.293  3788  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-02 15:26:06.294  3788  3836 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-02 15:26:06.294  3788  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-02 15:26:06.294  3788  3836 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-02 15:26:06.295  3788  3836 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-02 15:26:06.295  3788  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-02 15:26:06.296  3788  3788 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-02 15:26:06.296  3788  3788 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-02 15:26:06.296  3788  3788 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-02 15:26:06.296  2655  2678 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-02 15:26:06.296  2655  2678 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-02 15:26:06.297  3788  3836 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 15:26:06.297  3788  3836 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 15:26:06.297  3788  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-02 15:26:06.297  3788  3836 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4a6b6b0 not in the list
09-02 15:26:06.297  3788  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 15:26:06.297  3788  3836 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c59929 not in the list
09-02 15:26:06.297  3788  3836 D io.jxcore.node.ConnectivityMonitor: stop
09-02 15:26:06.297  3788  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 15:26:06.297  3788  3836 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 15:26:06.297  3788  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-02 15:26:06.298  2655  2688 D BtGatt.ScanManager: handling starting scan
09-02 15:26:06.298  3788  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-02 15:26:06.298  3788  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-02 15:26:06.298  3788  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 15:26:06.298  3788  3836 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c59929 not in the list
09-02 15:26:06.300  3788  3836 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-02 15:26:06.302  3788  3836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-02 15:26:06.302  2655  2678 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-02 15:26:06.302  2655  2678 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-02 15:26:06.302  2655  2688 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-02 15:26:06.305  3788  3836 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-02 15:26:06.305  3788  3836 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 15:26:06.305  3788  3836 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-02 15:26:06.305  3788  3836 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-02 15:26:06.305  3788  3836 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-02 15:26:06.305  3788  3836 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-02 15:26:06.305  3788  3836 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-02 15:26:06.305  3788  3836 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-02 15:26:06.307  3788  3836 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-02 15:26:06.307  3788  3836 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-02 15:26:06.308  2655  2678 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
09-02 15:26:06.308  2655  2678 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-02 15:26:06.308  2655  2688 D BtGatt.ScanManager: Starting BLE batch scan
09-02 15:26:06.308  2655  2688 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,09-02 15:26:06.308  3788  3836 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-02 15:26:06.308  3788  3836 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-02 15:26:06.309  3788  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-02 15:26:06.309  3788  3836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-02 15:26:06.309  3788  3836 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-02 15:26:06.310  3788  3788 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-02 15:26:06.312  3788  3836 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-02 15:26:06.312  3788  3836 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-02 15:26:06.312  3788  3788 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-02 15:26:06.316  3788  3836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-02 15:26:06.317  3788  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-02 15:26:06.317  3788  3836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-02 15:26:06.317  2655  2678 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,09-02 15:26:06.317  2655  2678 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-02 15:26:06.321  2655  2678 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-02 15:26:06.321  2655  2678 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-02 15:26:06.323  3788  3836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-02 15:26:06.323  3788  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-02 15:26:06.323  3788  3836 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-02 15:26:06.324  3788  3836 D BluetoothAdapter: STATE_ON
,09-02 15:26:06.327  2655  2665 D BtGatt.GattService: registerClient() - UUID=d27fbe09-0b81-4fb3-a3ce-f101e348362e
,09-02 15:26:06.327  2655  2678 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
09-02 15:26:06.327  2655  2678 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-02 15:26:06.327  2655  2678 D BtGatt.GattService: onClientRegistered() - UUID=d27fbe09-0b81-4fb3-a3ce-f101e348362e, clientIf=5
,09-02 15:26:06.328  2655  2688 D BtGatt.ScanManager: stopping BLe Batch
09-02 15:26:06.328  3788  3799 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-02 15:26:06.328  2655  2791 D BtGatt.GattService: start scan with filters
,09-02 15:26:06.331  3788  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-02 15:26:06.331  3788  3836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-02 15:26:06.331  3788  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,09-02 15:26:06.332  3788  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-02 15:26:06.334  2655  2678 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,09-02 15:26:06.334  2655  2678 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-02 15:26:06.334  2655  2688 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-02 15:26:06.335  3788  3836 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-02 15:26:06.336  3788  3836 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-02 15:26:06.336  3788  3788 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-02 15:26:06.337  3788  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-02 15:26:06.340  3788  3836 I io.jxcore.node.ConnectionHelper: start: OK
,09-02 15:26:06.340  3788  3836 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-02 15:26:06.340  3788  3836 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-02 15:26:06.340  3788  3836 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,09-02 15:26:06.340  3788  3836 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-02 15:26:06.341  3788  3836 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-02 15:26:06.341  3788  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-02 15:26:06.341  3788  3836 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-02 15:26:06.341  3788  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-02 15:26:06.341  3788  3836 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,09-02 15:26:06.341  3788  3836 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-02 15:26:06.342  3788  3836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-02 15:26:06.342  3788  3836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-02 15:26:06.342  2655  2678 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-02 15:26:06.342  2655  2678 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-02 15:26:06.343  3788  3836 D BluetoothAdapter: STATE_ON
09-02 15:26:06.343  2655  2791 D BtGatt.GattService: stopScan() - queue size =0
09-02 15:26:06.344  2655  2813 D BtGatt.GattService: unregisterClient() - clientIf=5
09-02 15:26:06.344  2655  2688 D BtGatt.ScanManager: handling starting scan
,09-02 15:26:06.344  3788  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-02 15:26:06.344  3788  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-02 15:26:06.344  3788  3836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-02 15:26:06.345  3788  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-02 15:26:06.345  3788  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-02 15:26:06.347  3788  3836 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-02 15:26:06.347  3788  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-02 15:26:06.347  3788  3836 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-02 15:26:06.347  3788  3836 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-02 15:26:06.348  3788  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-02 15:26:06.349  3788  3788 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-02 15:26:06.349  3788  3788 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-02 15:26:06.349  3788  3788 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-02 15:26:06.350  3788  3836 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-02 15:26:06.350  3788  3836 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-02 15:26:06.350  3788  3836 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-02 15:26:06.350  3788  3836 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-02 15:26:06.351  3788  3836 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 15:26:06.351  3788  3836 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 15:26:06.351  3788  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-02 15:26:06.351  3788  3836 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4a6b6b0 not in the list
09-02 15:26:06.351  2655  2678 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,09-02 15:26:06.352  2655  2678 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-02 15:26:06.351  3788  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 15:26:06.352  3788  3836 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c59929 not in the list
09-02 15:26:06.352  3788  3836 D io.jxcore.node.ConnectivityMonitor: stop
09-02 15:26:06.352  2655  2688 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
09-02 15:26:06.352  3788  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 15:26:06.353  3788  3836 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-02 15:26:06.353  3788  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-02 15:26:06.354  3788  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-02 15:26:06.355  3788  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-02 15:26:06.355  3788  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 15:26:06.355  3788  3836 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c59929 not in the list
,09-02 15:26:06.356  3788  3836 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
,09-02 15:26:06.356  2655  2678 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
09-02 15:26:06.357  2655  2678 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-02 15:26:06.357  3788  3836 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-02 15:26:06.357  3788  3836 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-02 15:26:06.357  2655  2688 D BtGatt.ScanManager: Starting BLE batch scan
,09-02 15:26:06.357  3788  3836 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-02 15:26:06.357  2655  2688 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
09-02 15:26:06.357  3788  3836 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 15:26:06.357  3788  3836 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 15:26:06.357  3788  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 15:26:06.357  3788  3836 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4a6b6b0 not in the list
09-02 15:26:06.357  3788  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-02 15:26:06.358  3788  3836 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c59929 not in the list
09-02 15:26:06.358  3788  3836 D io.jxcore.node.ConnectivityMonitor: stop
09-02 15:26:06.358  3788  3836 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 15:26:06.358  3788  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 15:26:06.358  3788  3836 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 15:26:06.358  3788  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 15:26:06.359  3788  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-02 15:26:06.359  3788  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-02 15:26:06.359  3788  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 15:26:06.359  3788  3836 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c59929 not in the list
09-02 15:26:06.359  3788  3836 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
09-02 15:26:06.360  3788  3836 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-02 15:26:06.360  3788  3836 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-02 15:26:06.360  3788  3836 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-02 15:26:06.360  3788  3836 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 15:26:06.360  3788  3836 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 15:26:06.360  3788  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-02 15:26:06.360  3788  3836 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4a6b6b0 not in the list
09-02 15:26:06.360  3788  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 15:26:06.360  3788  3836 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c59929 not in the list
09-02 15:26:06.360  3788  3836 D io.jxcore.node.ConnectivityMonitor: stop
,09-02 15:26:06.360  3788  3836 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 15:26:06.360  3788  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 15:26:06.360  3788  3836 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 15:26:06.360  3788  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 15:26:06.361  3788  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-02 15:26:06.361  3788  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-02 15:26:06.361  3788  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-02 15:26:06.361  3788  3836 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c59929 not in the list
09-02 15:26:06.361  3788  3836 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
09-02 15:26:06.361  3788  3836 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-02 15:26:06.362  3788  3836 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-02 15:26:06.362  3788  3836 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-02 15:26:06.362  3788  3836 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 15:26:06.362  3788  3836 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-02 15:26:06.362  3788  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 15:26:06.362  3788  3836 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4a6b6b0 not in the list
09-02 15:26:06.362  3788  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 15:26:06.362  3788  3836 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c59929 not in the list
09-02 15:26:06.362  3788  3836 D io.jxcore.node.ConnectivityMonitor: stop
09-02 15:26:06.362  3788  3836 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-02 15:26:06.362  3788  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 15:26:06.362  3788  3836 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 15:26:06.362  3788  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 15:26:06.364  3788  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-02 15:26:06.364  3788  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-02 15:26:06.364  3788  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 15:26:06.365  3788  3836 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c59929 not in the list
09-02 15:26:06.366  3788  3836 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
09-02 15:26:06.366  3788  3836 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-02 15:26:06.366  3788  3836 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-02 15:26:06.366  3788  3836 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-02 15:26:06.366  3788  3836 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 15:26:06.366  3788  3836 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 15:26:06.366  3788  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-02 15:26:06.367  3788  3836 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4a6b6b0 not in the list
09-02 15:26:06.367  3788  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 15:26:06.367  3788  3836 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c59929 not in the list
09-02 15:26:06.367  3788  3836 D io.jxcore.node.ConnectivityMonitor: stop
09-02 15:26:06.367  3788  3836 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 15:26:06.367  3788  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 15:26:06.367  3788  3836 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-02 15:26:06.367  3788  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 15:26:06.368  2655  2678 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-02 15:26:06.368  2655  2678 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-02 15:26:06.370  3788  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-02 15:26:06.370  3788  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-02 15:26:06.370  3788  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-02 15:26:06.370  3788  3836 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c59929 not in the list
,09-02 15:26:06.371  3788  3836 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,09-02 15:26:06.373  2655  2678 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,09-02 15:26:06.373  2655  2678 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-02 15:26:06.373  3788  3836 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-02 15:26:06.373  3788  3836 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-02 15:26:06.374  3788  3836 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,09-02 15:26:06.374  3788  3836 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,09-02 15:26:06.376  3788  3836 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,09-02 15:26:06.376  3788  3836 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-02 15:26:06.376  3788  3836 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-02 15:26:06.376  3788  3836 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-02 15:26:06.377  3788  3836 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 15:26:06.377  3788  3836 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 15:26:06.377  3788  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 15:26:06.377  3788  3836 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4a6b6b0 not in the list
09-02 15:26:06.377  3788  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 15:26:06.377  3788  3836 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c59929 not in the list
,09-02 15:26:06.377  3788  3836 D io.jxcore.node.ConnectivityMonitor: stop
09-02 15:26:06.377  3788  3836 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 15:26:06.377  3788  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 15:26:06.377  3788  3836 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 15:26:06.377  3788  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-02 15:26:06.378  3788  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-02 15:26:06.378  3788  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-02 15:26:06.378  3788  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 15:26:06.378  3788  3836 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c59929 not in the list
,09-02 15:26:06.379  2655  2678 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
09-02 15:26:06.379  2655  2678 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-02 15:26:06.379  3788  3836 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-02 15:26:06.379  2655  2688 D BtGatt.ScanManager: stopping BLe Batch
09-02 15:26:06.380  3788  3836 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
,09-02 15:26:06.380  3788  3836 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,09-02 15:26:06.384  3788  3836 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-02 15:26:06.385  3788  3836 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
09-02 15:26:06.385  3788  3836 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-02 15:26:06.385  3788  3836 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-02 15:26:06.385  3788  3836 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-02 15:26:06.385  3788  3836 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-02 15:26:06.385  3788  3836 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-02 15:26:06.385  3788  3836 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
,09-02 15:26:06.385  3788  3836 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-02 15:26:06.385  3788  3836 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-02 15:26:06.385  3788  3836 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-02 15:26:06.385  3788  3836 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-02 15:26:06.385  3788  3836 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-02 15:26:06.385  3788  3836 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-02 15:26:06.386  3788  3836 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
,09-02 15:26:06.386  3788  3836 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
,09-02 15:26:06.386  3788  3836 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-02 15:26:06.386  3788  3836 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-02 15:26:06.386  3788  3836 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-02 15:26:06.386  3788  3836 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-02 15:26:06.386  3788  3836 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
,09-02 15:26:06.386  3788  3836 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-02 15:26:06.386  3788  3836 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-02 15:26:06.386  3788  3836 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-02 15:26:06.386  2655  2678 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,09-02 15:26:06.386  3788  3836 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-02 15:26:06.386  2655  2678 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-02 15:26:06.386  3788  3836 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-02 15:26:06.386  2655  2688 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
09-02 15:26:06.386  3788  3836 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-02 15:26:06.386  3788  3836 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
,09-02 15:26:06.387  3788  3836 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-02 15:26:06.387  3788  3836 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-02 15:26:06.387  3788  3836 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-02 15:26:06.387  3788  3836 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
,09-02 15:26:06.387  3788  3836 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
09-02 15:26:06.387  3788  3836 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-02 15:26:06.387  3788  3836 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
09-02 15:26:06.388  3788  3836 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-02 15:26:06.388  3788  3836 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
,09-02 15:26:06.388  3788  3836 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
09-02 15:26:06.388  3788  3836 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-02 15:26:06.388  3788  3836 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-02 15:26:06.388  3788  3836 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
09-02 15:26:06.392  3788  3836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
,09-02 15:26:06.392  2655  2678 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-02 15:26:06.392  2655  2678 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-02 15:26:06.393  3788  3836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
09-02 15:26:06.393  3788  3836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
,09-02 15:26:06.393  3788  3836 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
09-02 15:26:06.393  3788  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
09-02 15:26:06.393  3788  3836 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
09-02 15:26:06.394  3788  3836 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,09-02 15:26:06.394  3788  3836 E io.jxcore.node.ConnectionHelper: connect: Callback is null
,09-02 15:26:06.394  3788  3836 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-02 15:26:06.394  3788  3836 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-02 15:26:06.395  3788  3836 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-02 15:26:06.395  3788  3836 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 15:26:06.395  3788  3836 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-02 15:26:06.394  3788  3848 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 385)
09-02 15:26:06.395  3788  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 15:26:06.395  3788  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
09-02 15:26:06.395  3788  3836 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4a6b6b0 not in the list
09-02 15:26:06.395  3788  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-02 15:26:06.396  3788  3836 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c59929 not in the list
09-02 15:26:06.396  3788  3836 D io.jxcore.node.ConnectivityMonitor: stop
,09-02 15:26:06.396  3788  3836 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 15:26:06.396  3788  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 15:26:06.396  3788  3836 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 15:26:06.396  3788  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-02 15:26:06.397  3788  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-02 15:26:06.397  3788  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-02 15:26:06.397  3788  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 15:26:06.397  3788  3836 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c59929 not in the list
,09-02 15:26:06.397  3788  3848 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-02 15:26:06.397  3788  3836 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
,09-02 15:26:06.398  3788  3836 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-02 15:26:06.398  3788  3836 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-02 15:26:06.398  3788  3836 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-02 15:26:06.398  3788  3836 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-02 15:26:06.398  3788  3836 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 15:26:06.398  3788  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-02 15:26:06.398  3788  3836 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4a6b6b0 not in the list
09-02 15:26:06.398  3788  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-02 15:26:06.398  3788  3836 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c59929 not in the list
,09-02 15:26:06.398  3788  3836 D io.jxcore.node.ConnectivityMonitor: stop
09-02 15:26:06.399  3788  3836 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-02 15:26:06.399  3788  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 15:26:06.399  3788  3836 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed,
09-02 15:26:06.399  3788  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 15:26:06.400  3788  3849 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 385
,09-02 15:26:06.400  3788  3849 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Trying to close the Bluetooth socket... (thread ID: 385)
,09-02 15:26:06.400  2655  2788 E bt_btif_sock_rfcomm: btsock_rfc_signaled socket signaled for read while disconnected, slot: 4, channel: -1
09-02 15:26:06.400  3788  3849 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Bluetooth socket closed (thread ID: 385)
,09-02 15:26:06.400  3788  3848 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 385)
09-02 15:26:06.400  3788  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-02 15:26:06.400  3788  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-02 15:26:06.400  3788  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 15:26:06.400  3788  3836 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c59929 not in the list
09-02 15:26:06.401  3788  3836 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
09-02 15:26:06.401  3788  3836 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-02 15:26:06.401  3788  3836 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-02 15:26:06.401  3788  3836 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-02 15:26:06.401  3788  3836 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-02 15:26:06.401  3788  3836 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 15:26:06.401  3788  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 15:26:06.402  3788  3836 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4a6b6b0 not in the list
,09-02 15:26:06.402  3788  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 15:26:06.402  3788  3836 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c59929 not in the list
,09-02 15:26:06.402  3788  3836 D io.jxcore.node.ConnectivityMonitor: stop
,09-02 15:26:06.402  3788  3836 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 15:26:06.402  3788  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-02 15:26:06.402  3788  3836 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 15:26:06.402  3788  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 15:26:06.403  3788  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-02 15:26:06.403  3788  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-02 15:26:06.403  3788  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-02 15:26:06.403  3788  3836 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c59929 not in the list
09-02 15:26:06.404  3788  3836 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
09-02 15:26:06.404  3788  3836 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
09-02 15:26:06.404  3788  3836 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
,09-02 15:26:06.404  3788  3836 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
09-02 15:26:06.404  3788  3836 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
,09-02 15:26:06.404  3788  3836 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
09-02 15:26:06.404  3788  3836 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-02 15:26:06.404  3788  3836 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
09-02 15:26:06.404  3788  3836 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-02 15:26:06.404  3788  3836 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55,
09-02 15:26:06.404  3788  3836 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-02 15:26:06.404  3788  3836 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
,09-02 15:26:06.405  3788  3836 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-02 15:26:06.405  3788  3836 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-02 15:26:06.405  3788  3836 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-02 15:26:06.405  3788  3836 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-02 15:26:06.405  3788  3836 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 15:26:06.405  3788  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 15:26:06.405  3788  3836 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4a6b6b0 not in the list
,09-02 15:26:06.405  3788  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 15:26:06.405  3788  3836 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c59929 not in the list
09-02 15:26:06.405  3788  3836 D io.jxcore.node.ConnectivityMonitor: stop
09-02 15:26:06.405  3788  3836 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 15:26:06.405  3788  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-02 15:26:06.405  3788  3836 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 15:26:06.405  3788  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 15:26:06.406  3788  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-02 15:26:06.406  3788  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-02 15:26:06.406  3788  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 15:26:06.407  3788  3836 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c59929 not in the list
09-02 15:26:06.407  3788  3836 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 15:26:06.407  3788  3836 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 15:26:06.407  3788  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-02 15:26:06.407  3788  3836 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4a6b6b0 not in the list
09-02 15:26:06.407  3788  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-02 15:26:06.407  3788  3836 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c59929 not in the list
09-02 15:26:06.407  3788  3836 D io.jxcore.node.ConnectivityMonitor: stop
,09-02 15:26:06.407  3788  3836 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 15:26:06.407  3788  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 15:26:06.408  3788  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 15:26:06.408  3788  3836 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c59929 not in the list
09-02 15:26:06.408  3788  3836 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 15:26:06.408  3788  3836 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-02 15:26:06.408  3788  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 15:26:06.408  3788  3836 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4a6b6b0 not in the list
09-02 15:26:06.408  3788  3836 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-02 15:26:06.408  3788  3836 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-02 15:26:06.408  3788  3836 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-02 15:26:06.408  3788  3836 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 15:26:06.408  3788  3836 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 15:26:06.408  3788  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-02 15:26:06.408  3788  3836 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4a6b6b0 not in the list
09-02 15:26:06.408  3788  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 15:26:06.408  3788  3836 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c59929 not in the list
09-02 15:26:06.409  3788  3836 D io.jxcore.node.ConnectivityMonitor: stop
09-02 15:26:06.409  3788  3836 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 15:26:06.409  3788  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 15:26:06.409  3788  3836 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-02 15:26:06.409  3788  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 15:26:06.410  3788  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-02 15:26:06.410  3788  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-02 15:26:06.410  3788  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 15:26:06.410  3788  3836 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c59929 not in the list
09-02 15:26:06.411  3788  3836 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-02 15:26:06.411  3788  3836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-02 15:26:06.412  3788  3836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,09-02 15:26:06.412  3788  3836 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-02 15:26:06.412  3788  3836 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-02 15:26:06.413  3788  3836 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-02 15:26:06.413  3788  3788 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
09-02 15:26:06.413  3788  3836 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-02 15:26:06.413  3788  3836 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 15:26:06.413  3788  3836 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
,09-02 15:26:06.413  3788  3836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-02 15:26:06.413  3788  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-02 15:26:06.413  3788  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 15:26:06.413  3788  3836 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-02 15:26:06.413  3788  3836 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4a6b6b0 not in the list
09-02 15:26:06.413  3788  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 15:26:06.413  3788  3788 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
,09-02 15:26:06.413  3788  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-02 15:26:06.413  3788  3836 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-02 15:26:06.414  3788  3850 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-02 15:26:06.414  3788  3836 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-02 15:26:06.414  3788  3836 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 15:26:06.414  3788  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 15:26:06.414  3788  3836 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-02 15:26:06.415  3788  3788 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-02 15:26:06.415  3788  3836 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c59929 not in the list
09-02 15:26:06.415  3788  3788 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-02 15:26:06.415  3788  3836 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-02 15:26:06.415  3788  3788 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-02 15:26:06.415  3788  3836 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-02 15:26:06.415  3788  3836 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-02 15:26:06.415  3788  3836 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 15:26:06.415  3788  3836 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 15:26:06.415  3788  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 15:26:06.415  3788  3836 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4a6b6b0 not in the list
09-02 15:26:06.415  3788  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 15:26:06.415  3788  3836 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c59929 not in the list
09-02 15:26:06.415  3788  3836 D io.jxcore.node.ConnectivityMonitor: stop
,09-02 15:26:06.415  3788  3836 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 15:26:06.415  3788  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 15:26:06.415  3788  3850 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
09-02 15:26:06.415  3788  3836 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 15:26:06.416  3788  3850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-02 15:26:06.416  3788  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 15:26:06.416  3788  3850 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-02 15:26:06.416  3788  3788 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-02 15:26:06.416  3788  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-02 15:26:06.416  3788  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-02 15:26:06.416  3788  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 15:26:06.416  3788  3836 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c59929 not in the list
09-02 15:26:06.417  3788  3836 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
09-02 15:26:06.418  3788  3836 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-02 15:26:06.418  3788  3836 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-02 15:26:06.419  3788  3836 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-02 15:26:06.419  3788  3836 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-02 15:26:06.419  3788  3836 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-02 15:26:06.419  3788  3836 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-02 15:26:06.419  3788  3836 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-02 15:26:06.419  3788  3836 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 15:26:06.419  3788  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 15:26:06.420  3788  3836 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4a6b6b0 not in the list
09-02 15:26:06.420  3788  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 15:26:06.420  3788  3836 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c59929 not in the list
09-02 15:26:06.420  3788  3836 D io.jxcore.node.ConnectivityMonitor: stop
09-02 15:26:06.420  3788  3836 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 15:26:06.420  3788  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 15:26:06.420  3788  3836 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 15:26:06.420  3788  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-02 15:26:06.421  3788  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-02 15:26:06.421  3788  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-02 15:26:06.421  3788  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 15:26:06.421  3788  3836 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c59929 not in the list
09-02 15:26:06.425  3788  3836 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-02 15:26:06.425  3788  3836 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-02 15:26:06.425  3788  3836 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-02 15:26:06.425  3788  3836 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 15:26:06.425  3788  3836 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 15:26:06.425  3788  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 15:26:06.425  3788  3836 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4a6b6b0 not in the list
09-02 15:26:06.425  3788  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-02 15:26:06.425  3788  3836 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c59929 not in the list
09-02 15:26:06.425  3788  3836 D io.jxcore.node.ConnectivityMonitor: stop
09-02 15:26:06.425  3788  3836 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 15:26:06.425  3788  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 15:26:06.425  3788  3836 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 15:26:06.425  3788  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 15:26:06.426  3788  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-02 15:26:06.426  3788  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-02 15:26:06.426  3788  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 15:26:06.426  3788  3836 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c59929 not in the list
09-02 15:26:06.427  3788  3836 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-02 15:26:06.427  3788  3836 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-02 15:26:06.427  3788  3836 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-02 15:26:06.427  3788  3836 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 15:26:06.427  3788  3836 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 15:26:06.428  3788  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 15:26:06.428  3788  3836 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4a6b6b0 not in the list
09-02 15:26:06.428  3788  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 15:26:06.428  3788  3836 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c59929 not in the list
09-02 15:26:06.428  3788  3836 D io.jxcore.node.ConnectivityMonitor: stop
09-02 15:26:06.428  3788  3836 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 15:26:06.428  3788  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 15:26:06.428  3788  3836 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-02 15:26:06.428  3788  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 15:26:06.429  3788  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-02 15:26:06.429  3788  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-02 15:26:06.429  3788  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 15:26:06.429  3788  3836 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c59929 not in the list
09-02 15:26:06.430  3788  3836 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
09-02 15:26:06.430  3788  3836 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-02 15:26:06.430  3788  3836 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
09-02 15:26:06.430  3788  3836 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-02 15:26:06.430  3788  3836 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
09-02 15:26:06.430  3788  3836 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-02 15:26:06.432  3788  3836 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
09-02 15:26:06.432  3788  3836 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
09-02 15:26:06.433  3788  3836 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
09-02 15:26:06.433  3788  3836 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-02 15:26:06.433  3788  3836 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
09-02 15:26:06.433  3788  3836 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-02 15:26:06.433  3788  3836 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
09-02 15:26:06.433  3788  3836 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
09-02 15:26:06.434  3788  3836 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
09-02 15:26:06.434  3788  3836 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
09-02 15:26:06.434  3788  3836 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
09-02 15:26:06.434  3788  3836 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
09-02 15:26:06.434  3788  3836 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
09-02 15:26:06.434  3788  3836 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
09-02 15:26:06.435  3788  3836 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-02 15:26:06.435  3788  3836 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@53095e3 added. We now have 2 listener(s)
09-02 15:26:06.435  3788  3836 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-02 15:26:06.437  3788  3836 D BluetoothAdapter: enable(): BT is already enabled..!
09-02 15:26:06.437   872   882 D WifiService: setWifiEnabled: true pid=3788, uid=10000
09-02 15:26:06.437   872   882 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
09-02 15:26:06.438  3788  3836 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-02 15:26:06.438  3788  3836 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@3ed2be0 added. We now have 3 listener(s)
09-02 15:26:06.438  3788  3836 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-02 15:26:06.442  3788  3836 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-02 15:26:06.442  3788  3836 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@e9a1e99 added. We now have 4 listener(s)
09-02 15:26:06.442  3788  3836 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-02 15:26:06.444  3788  3836 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-02 15:26:06.444  3788  3836 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@47d55e added. We now have 5 listener(s)
09-02 15:26:06.444  3788  3836 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-02 15:26:06.446   872  3116 D WifiService: setWifiEnabled: false pid=3788, uid=10000
09-02 15:26:06.447   872  3116 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
09-02 15:26:06.450  3788  3836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-02 15:26:06.450  2655  2673 D BluetoothAdapterState: Current state: ON, message: 23
09-02 15:26:06.450  2655  2673 D BluetoothAdapterProperties: Setting state to 13
09-02 15:26:06.450  2655  2673 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
09-02 15:26:06.451  2655  2673 D BluetoothAdapterProperties: onBluetoothDisable()
09-02 15:26:06.451  2655  2673 I BluetoothAdapterState: Entering PendingCommandState
09-02 15:26:06.452  2655  2678 D BluetoothAdapterProperties: Scan Mode:20
09-02 15:26:06.452  3788  3836 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-02 15:26:06.452  2655  2673 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
09-02 15:26:06.452  3788  3836 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-02 15:26:06.452  3788  3836 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 15:26:06.452  3788  3836 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-02 15:26:06.452  3788  3836 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-02 15:26:06.452  3788  3836 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-02 15:26:06.452  3788  3836 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-02 15:26:06.452  3788  3836 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-02 15:26:06.452  3788  3836 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-02 15:26:06.453  3788  3836 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-02 15:26:06.453  3788  3836 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-02 15:26:06.453  3788  3836 D io.jxcore.node.ConnectivityMonitor: start: OK
09-02 15:26:06.454  2655  2655 D HeadsetService: Received stop request...Stopping profile...
09-02 15:26:06.456  3788  3788 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-02 15:26:06.459  3788  3788 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-02 15:26:06.462  1465  1465 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
09-02 15:26:06.463  3788  3788 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-02 15:26:06.463  3788  3788 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-02 15:26:06.463  3788  3788 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 15:26:06.463  3788  3788 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-02 15:26:06.463  3788  3788 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-02 15:26:06.463  3788  3788 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-02 15:26:06.463  3788  3788 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-02 15:26:06.463  3788  3788 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-02 15:26:06.463  3788  3788 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-02 15:26:06.464  3788  3788 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-02 15:26:06.464  3788  3788 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-02 15:26:06.464   872  1306 D WifiStateMachine: WifiStateMachine: Leaving Connected state
09-02 15:26:06.464   872  1306 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
09-02 15:26:06.464   872  1306 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-02 15:26:06.464   872  1306 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-02 15:26:06.467  3788  3788 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-02 15:26:06.470  3788  3788 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-02 15:26:06.471   372   870 D CommandListener: Clearing all IP addresses on wlan0
09-02 15:26:06.471   872  1870 D DhcpClient: Clearing IP address
09-02 15:26:06.473  3788  3788 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-02 15:26:06.473   372   870 D CommandListener: Setting iface cfg
09-02 15:26:06.476  1528  2150 V NativeCrypto: Read error: ssl=0xaecd3a00: I/O error during system call, Connection timed out
09-02 15:26:06.476   872   885 I ActivityManager: Start proc 3853:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
09-02 15:26:06.479  1939  1953 D BluetoothHeadset: Proxy object disconnected
09-02 15:26:06.479  1528  2150 V NativeCrypto: SSL shutdown failed: ssl=0xaecd3a00: I/O error during system call, Broken pipe
09-02 15:26:06.479   872   872 D BluetoothHeadset: Proxy object disconnected
09-02 15:26:06.479   872   872 D BluetoothHeadset: Proxy object disconnected
09-02 15:26:06.480  2655  2655 D BluetoothMapService: onReceive
09-02 15:26:06.480  1365  1383 D BluetoothHeadset: Proxy object disconnected
09-02 15:26:06.480  2655  2655 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-02 15:26:06.480  2655  2655 D BluetoothMapService: STATE_TURNING_OFF
09-02 15:26:06.480   872   872 D BluetoothHeadset: Proxy object disconnected
09-02 15:26:06.480  2655  2655 D A2dpService: Received stop request...Stopping profile...
09-02 15:26:06.481  1365  1365 D HeadsetProfile: Bluetooth service disconnected
09-02 15:26:06.481  2655  2794 D A2dpStateMachine: Exit Disconnected: -1
09-02 15:26:06.482   872  1377 D ConnectivityService: reportNetworkConnectivity(100, false) by 10011
09-02 15:26:06.482   872  1862 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Forcing reevaluation for UID 10011
09-02 15:26:06.482   872  1308 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
09-02 15:26:06.482   872  1308 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
09-02 15:26:06.484   872  1306 D WifiStateMachine: Start Disconnecting Watchdog 1
09-02 15:26:06.486   872  1306 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-02 15:26:06.486   395   395 E Parcel  : Reading a NULL string not supported here.
09-02 15:26:06.488   872  1862 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.gstatic.com": No address associated with hostname
09-02 15:26:06.492   872   872 D BluetoothA2dp: Proxy object disconnected
09-02 15:26:06.492  2655  2655 V BluetoothAdapterState: isTurningOff()=true
09-02 15:26:06.492  2655  2655 V BluetoothAdapterState: isTurningOn()=false
09-02 15:26:06.492  2655  2655 V BluetoothAdapterState: isBleTurningOn()=false
09-02 15:26:06.493  2655  2655 V BluetoothAdapterState: isBleTurningOff()=false
09-02 15:26:06.494  1365  1365 D BluetoothA2dp: Proxy object disconnected
,09-02 15:26:06.494  2655  2655 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
09-02 15:26:06.494  2655  2678 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
09-02 15:26:06.494  2655  2755 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-02 15:26:06.494  2655  2655 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
,09-02 15:26:06.494  2655  2755 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,09-02 15:26:06.494  2655  2755 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-02 15:26:06.495  2655  2678 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
09-02 15:26:06.495  2655  2655 D BluetoothMapService: MAP Service closeService in
09-02 15:26:06.495  2655  2655 D BluetoothMapMasInstance0: MAP Service shutdown
,09-02 15:26:06.495  2655  2655 D ObexServerSockets0: shutdown(block = true)
09-02 15:26:06.495  2655  2814 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
09-02 15:26:06.496  2655  2655 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-02 15:26:06.496  2655  2788 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
09-02 15:26:06.496  2655  2815 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
,09-02 15:26:06.496  2655  2655 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-02 15:26:06.496  2655  2655 I BtOppRfcommListener: stopping Accept Thread
09-02 15:26:06.496  2655  3442 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-02 15:26:06.497  2655  3442 I BtOppRfcommListener: BluetoothSocket listen thread finished
,09-02 15:26:06.498  2655  2655 D HidService: Received stop request...Stopping profile...
09-02 15:26:06.498  2655  2655 D HidService: Stopping Bluetooth HidService
09-02 15:26:06.498   872  1308 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
09-02 15:26:06.499  1365  1365 D BluetoothInputDevice: Proxy object disconnected
09-02 15:26:06.499  1365  1365 D HidProfile: Bluetooth service disconnected
,09-02 15:26:06.499  2655  2655 D HealthService: Received stop request...Stopping profile...
09-02 15:26:06.500   372   870 D CommandListener: Clearing all IP addresses on wlan0
09-02 15:26:06.500  2655  2655 D PanService: Received stop request...Stopping profile...
09-02 15:26:06.502  2655  2655 D BluetoothMapService: Received stop request...Stopping profile...
09-02 15:26:06.502  2655  2655 D BluetoothMapService: stop()
,09-02 15:26:06.502  1365  1365 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-02 15:26:06.502  1365  1365 D PanProfile: Bluetooth service disconnected
09-02 15:26:06.503  2655  2655 D BluetoothMapAppObserver: deinitObservers()
09-02 15:26:06.503  2655  2655 D BluetoothMapAppObserver: removeReceiver()
,09-02 15:26:06.504  2655  2655 V BluetoothAdapterState: isTurningOff()=true
,09-02 15:26:06.504  2655  2655 V BluetoothAdapterState: isTurningOn()=false
09-02 15:26:06.504  2655  2655 V BluetoothAdapterState: isBleTurningOn()=false
09-02 15:26:06.505  2655  2655 V BluetoothAdapterState: isBleTurningOff()=false
,09-02 15:26:06.505   872  1882 D DhcpClient: Receive thread stopped
,09-02 15:26:06.507  1365  1365 D BluetoothMap: Proxy object disconnected
09-02 15:26:06.507  1365  1365 D MapProfile: Bluetooth service disconnected
09-02 15:26:06.510  2655  2678 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
09-02 15:26:06.510  2655  2755 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,09-02 15:26:06.511  2655  2755 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,09-02 15:26:06.511  2655  2755 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-02 15:26:06.511  2655  2755 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-02 15:26:06.511  2655  2755 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,09-02 15:26:06.511  2655  2755 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-02 15:26:06.518  2655  2655 V BluetoothAdapterState: isTurningOff()=true
09-02 15:26:06.518  2655  2655 V BluetoothAdapterState: isTurningOn()=false
09-02 15:26:06.518  2655  2655 V BluetoothAdapterState: isBleTurningOn()=false
09-02 15:26:06.518  2655  2655 V BluetoothAdapterState: isBleTurningOff()=false
09-02 15:26:06.518  2655  2655 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
,09-02 15:26:06.520  2655  2678 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
09-02 15:26:06.520  2655  2655 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
09-02 15:26:06.521  2655  2655 V BluetoothAdapterState: isTurningOff()=true
09-02 15:26:06.521  2655  2655 V BluetoothAdapterState: isTurningOn()=false
,09-02 15:26:06.521  2655  2655 V BluetoothAdapterState: isBleTurningOn()=false
09-02 15:26:06.521  2655  2655 V BluetoothAdapterState: isBleTurningOff()=false
09-02 15:26:06.523  2655  2655 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
09-02 15:26:06.523  2655  2678 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
09-02 15:26:06.524  2655  2655 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-02 15:26:06.525  2655  2655 V BluetoothAdapterState: isTurningOff()=true
,09-02 15:26:06.525  2655  2655 V BluetoothAdapterState: isTurningOn()=false
09-02 15:26:06.525  2655  2655 V BluetoothAdapterState: isBleTurningOn()=false
09-02 15:26:06.525  2655  2655 V BluetoothAdapterState: isBleTurningOff()=false
09-02 15:26:06.525  2655  2655 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
09-02 15:26:06.525  2655  2655 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
09-02 15:26:06.527  2655  2655 D BluetoothMapService: MAP Service closeService in
,09-02 15:26:06.527  2655  2655 V BluetoothAdapterState: isTurningOff()=true
09-02 15:26:06.527  2655  2655 V BluetoothAdapterState: isTurningOn()=false
09-02 15:26:06.527  2655  2655 V BluetoothAdapterState: isBleTurningOn()=false
09-02 15:26:06.528  2655  2655 V BluetoothAdapterState: isBleTurningOff()=false
09-02 15:26:06.528  2655  2673 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
09-02 15:26:06.528  2655  2673 D BluetoothAdapterProperties: Setting state to 15
,09-02 15:26:06.528  2655  2673 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
09-02 15:26:06.529  1365  3787 D BluetoothMap: onBluetoothStateChange: up=false
09-02 15:26:06.529  2655  2673 I BluetoothAdapterState: Entering BleOnState
,09-02 15:26:06.529  2655  2655 D BluetoothMapService: cleanup()
,09-02 15:26:06.529  2655  2655 D BluetoothMapService: MAP Service closeService in
09-02 15:26:06.529  1365  1380 D BluetoothPan: onBluetoothStateChange on: false
09-02 15:26:06.529   872   889 D BluetoothA2dp: onBluetoothStateChange: up=false
09-02 15:26:06.529   872   889 D BluetoothHeadset: onBluetoothStateChange: up=false
,09-02 15:26:06.529  1365  2059 D BluetoothPbap: onBluetoothStateChange: up=false
09-02 15:26:06.532  1939  1953 D BluetoothHeadset: onBluetoothStateChange: up=false
,09-02 15:26:06.532  1365  1383 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-02 15:26:06.533   872   889 D BluetoothHeadset: onBluetoothStateChange: up=false
09-02 15:26:06.533  1365  3787 D BluetoothA2dp: onBluetoothStateChange: up=false
09-02 15:26:06.534   872   889 D BluetoothHeadset: onBluetoothStateChange: up=false
,09-02 15:26:06.534  1365  1380 D BluetoothHeadset: onBluetoothStateChange: up=false
,09-02 15:26:06.534  2655  2673 D BluetoothAdapterState: Current state: BLE ON, message: 20
09-02 15:26:06.534  2655  2673 D BluetoothAdapterProperties: Setting state to 16
09-02 15:26:06.534  2655  2673 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
09-02 15:26:06.535  2655  2673 D BluetoothAdapterProperties: onBleDisable
09-02 15:26:06.535  2655  2673 I BluetoothAdapterState: Entering PendingCommandState
,09-02 15:26:06.535  2655  2674 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
,09-02 15:26:06.537  2655  2755 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
,09-02 15:26:06.537  2655  2755 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-02 15:26:06.537  2655  2678 D BluetoothAdapterProperties: Scan Mode:20
09-02 15:26:06.538  3788  3788 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-02 15:26:06.538  3788  3788 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-02 15:26:06.538  3788  3788 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 15:26:06.538  3788  3788 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-02 15:26:06.538  3788  3788 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-02 15:26:06.538  3788  3788 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-02 15:26:06.538  3788  3788 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-02 15:26:06.538  3788  3788 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-02 15:26:06.538  3788  3788 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-02 15:26:06.539  3788  3788 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-02 15:26:06.539  3788  3788 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-02 15:26:06.541  3788  3788 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-02 15:26:06.541  3788  3788 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-02 15:26:06.541  3788  3788 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 15:26:06.541  3788  3788 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-02 15:26:06.541  3788  3788 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-02 15:26:06.541  3788  3788 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-02 15:26:06.541  3788  3788 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-02 15:26:06.541  3788  3788 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-02 15:26:06.541  3788  3788 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-02 15:26:06.541  3788  3788 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-02 15:26:06.541  3788  3788 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-02 15:26:06.543  3788  3788 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-02 15:26:06.543  3788  3788 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-02 15:26:06.544   372   870 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-02 15:26:06.548  3853  3853 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm
09-02 15:26:06.557  3853  3853 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-02 15:26:06.560   372   870 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
09-02 15:26:06.561   872  1308 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
09-02 15:26:06.561   872  1308 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
09-02 15:26:06.562  1528  1528 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-02 15:26:06.563   872   889 D Tethering: MasterInitialState.processMessage what=3
,09-02 15:26:06.566  3788  3788 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-02 15:26:06.567  3788  3788 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-02 15:26:06.567  3407  3407 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@12997e0 and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
,09-02 15:26:06.575   872   889 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@963f0d1:true
,09-02 15:26:06.582   872   883 I ActivityManager: Start proc 3873:com.google.android.apps.maps/u0a65 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,09-02 15:26:06.583   872  1306 D WifiConfigStore: Retrieve network priorities after PNO.
,09-02 15:26:06.586  3788  3788 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-02 15:26:06.586  3788  3788 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-02 15:26:06.586  3788  3788 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 15:26:06.586  3788  3788 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-02 15:26:06.586  3788  3788 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-02 15:26:06.586  3788  3788 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-02 15:26:06.586  3788  3788 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-02 15:26:06.586  3788  3788 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-02 15:26:06.586  3788  3788 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-02 15:26:06.587  3788  3788 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-02 15:26:06.587  3788  3788 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-02 15:26:06.588   872  1306 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
09-02 15:26:06.589  2183  2297 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-02 15:26:06.590  3788  3788 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-02 15:26:06.590  3788  3788 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-02 15:26:06.590  3788  3788 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 15:26:06.590  3788  3788 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-02 15:26:06.590  3788  3788 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-02 15:26:06.590  3788  3788 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-02 15:26:06.590  3788  3788 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-02 15:26:06.590  3788  3788 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-02 15:26:06.590  3788  3788 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-02 15:26:06.590  3788  3788 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-02 15:26:06.590  3788  3788 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-02 15:26:06.613  3853  3853 D LocalBluetoothProfileManager: Adding local MAP profile
,09-02 15:26:06.614  3853  3853 D BluetoothMap: Create BluetoothMap proxy object
,09-02 15:26:06.621  3873  3873 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm
,09-02 15:26:06.629  3853  3853 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,09-02 15:26:06.639   372   870 E Netd    : netlink response contains error (No such file or directory)
,09-02 15:26:06.641   872  1308 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
09-02 15:26:06.641   872  1308 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,09-02 15:26:06.660  3853  3853 D DockEventReceiver: finishStartingService: stopping service
,09-02 15:26:06.662   872  1693 I ActivityManager: Killing 2970:com.google.android.calendar/u0a37 (adj 15): empty #17
,09-02 15:26:06.740  2655  2678 I bt_hci  : shut_down
,09-02 15:26:06.740  2655  2693 D bt_hwcfg: hw_epilog_process
,09-02 15:26:06.741  2655  2693 I bt_vendor: low_power_mode_cb
,09-02 15:26:06.765  2655  2693 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,09-02 15:26:06.765  2655  2693 I bt_vendor: epilog_cb
,09-02 15:26:06.765  2655  2693 I bt_hci  : epilog_finished_callback
,09-02 15:26:06.770  2655  2678 I bt_hci_h4: hal_close
,09-02 15:26:06.770  2655  2678 I bt_userial_vendor: device fd = 51 close
,09-02 15:26:06.780  3873  3873 D StrictMode: StrictMode policy violation; ~duration=83 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-02 15:26:06.780  3873  3873 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-02 15:26:06.780  3873  3873 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-02 15:26:06.780  3873  3873 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-02 15:26:06.780  3873  3873 D StrictMode: 	at java.io.File.exists(File.java:361)
09-02 15:26:06.780  3873  3873 D StrictMode: 	,at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
09-02 15:26:06.780  3873  3873 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
09-02 15:26:06.780  3873  3873 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
09-02 15:26:06.780  3873  3873 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-02 15:26:06.780  3873  3873 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-02 15:26:06.780  3873  3873 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-02 15:26:06.780  3873  3873 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-02 15:26:06.780  3873  3873 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-02 15:26:06.780  3873  3873 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-02 15:26:06.780  3873  3873 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-02 15:26:06.780  3873  3873 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-02 15:26:06.780  3873  3873 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-02 15:26:06.780  3873  3873 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-02 15:26:06.780  3873  3873 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-02 15:26:06.780  3873  3873 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-02 15:26:06.780  3873  3873 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-02 15:26:06.780  3873  3873 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-02 15:26:06.780  3873  3873 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-02 15:26:06.780  3873  3873 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-02 15:26:06.780  3873  3873 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-02 15:26:06.780  3873  3873 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-02 15:26:06.780  3873  3873 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-02 15:26:06.780  3873  3873 D StrictMode: StrictMode policy violation; ~duration=83 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-02 15:26:06.780  3873  3873 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-02 15:26:06.780  3873  3873 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
09-02 15:26:06.780  3873  3873 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-02 15:26:06.780  3873  3873 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-02 15:26:06.780  3873  3873 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
09-02 15:26:06.780  3873  3873 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-02 15:26:06.780  3873  3873 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-02 15:26:06.780  3873  3873 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-02 15:26:06.780  3873  3873 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-02 15:26:06.780  3873  3873 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-02 15:26:06.780  3873  3873 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-02 15:26:06.780  3873  3873 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-02 15:26:06.780  3873  3873 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-02 15:26:06.780  3873  3873 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-02 15:26:06.780  3873  3873 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-02 15:26:06.780  3873  3873 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-02 15:26:06.780  3873  3873 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-02 15:26:06.780  3873  3873 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-02 15:26:06.780  3873  3873 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-02 15:26:06.780  3873  3873 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-02 15:26:06.780  3873  3873 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-02 15:26:06.780  3873  3873 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-02 15:26:06.780  3873  3873 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-02 15:26:06.780  3873  3873 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-02 15:26:06.780  3873  3873 D StrictMode: StrictMode policy violation; ~duration=82 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-02 15:26:06.780  3873  3873 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-02 15:26:06.780  3873  3873 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
09-02 15:26:06.780  3873  3873 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
09-02 15:26:06.780  3873  3873 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-02 15:26:06.780  3873  3873 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
09-02 15:26:06.780  3873  3873 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-02 15:26:06.780  3873  3873 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-02 15:26:06.780  3873  3873 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-02 15:26:06.780  3873  3873 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-02 15:26:06.780  3873  3873 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-02 15:26:06.780  3873  3873 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-02 15:26:06.780  3873  3873 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-02 15:26:06.780  3873  3873 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-02 15:26:06.780  3873  3873 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-02 15:26:06.780  3873  3873 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-02 15:26:06.780  3873  3873 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-02 15:26:06.780  3873  3873 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-02 15:26:06.780  3873  3873 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-02 15:26:06.780  3873  3873 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-02 15:26:06.780  3873  3873 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-02 15:26:06.780  3873  3873 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-02 15:26:06.780  3873  3873 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-02 15:26:06.780  3873  3873 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-02 15:26:06.780  3873  3873 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-02 15:26:06.780  3873  3873 D StrictMode: StrictMode policy violation; ~duration=82 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-02 15:26:06.780  3873  3873 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-02 15:26:06.780  3873  3873 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-02 15:26:06.780  3873  3873 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
09-02 15:26:06.780  3873  3873 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-02 15:26:06.780  3873  3873 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-02 15:26:06.780  3873  3873 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-02 15:26:06.780  3873  3873 D StrictMode: 	at com.google.r.k.d(PG:1187)
09-02 15:26:06.780  3873  3873 D StrictMode: 	at com.google.r.k.a(PG:2107)
09-02 15:26:06.780  3873  3873 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
09-02 15:26:06.780  3873  3873 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
09-02 15:26:06.780  3873  3873 D StrictMode: 	at com.google.r.v.a(PG:1161)
09-02 15:26:06.780  3873  3873 D StrictMode: 	at com.google.r.y.a(PG:2188)
09-02 15:26:06.780  3873  3873 D StrictMode: 	at com.google.r.e.b(PG:170)
09-02 15:26:06.780  3873  3873 D StrictMode: 	at com.google.r.e.b(PG:15188)
09-02 15:26:06.780  3873  3873 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
09-02 15:26:06.780  3873  3873 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-02 15:26:06.780  3873  3873 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-02 15:26:06.780  3873  3873 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-02 15:26:06.780  3873  3873 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-02 15:26:06.780  3873  3873 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-02 15:26:06.780  3873  3873 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-02 15:26:06.780  3873  3873 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-02 15:26:06.780  3873  3873 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-02 15:26:06.780  3873  3873 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-02 15:26:06.780  3873  3873 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-02 15:26:06.780  3873  3873 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-02 15:26:06.780  3873  3873 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-02 15:26:06.780  3873  3873 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-02 15:26:06.780  3873  3873 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-02 15:26:06.780  3873  3873 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-02 15:26:06.780  3873  3873 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-02 15:26:06.780  3873  3873 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-02 15:26:06.780  3873  3873 D StrictMode: StrictMode policy violation; ~duration=74 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-02 15:26:06.780  3873  3873 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-02 15:26:06.780  3873  3873 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-02 15:26:06.780  3873  3873 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
09-02 15:26:06.780  3873  3873 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-02 15:26:06.780  3873  3873 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-02 15:26:06.780  3873  3873 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-02 15:26:06.780  3873  3873 D StrictMode: 	at com.google.r.k.d(PG:1187)
09-02 15:26:06.780  3873  3873 D StrictMode: 	at com.google.r.k.c(PG:18147)
09-02 15:26:06.780  3873  3873 D StrictMode: 	at com.google.r.k.d(PG:583)
09-02 15:26:06.780  3873  3873 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
09-02 15:26:06.780  3873  3873 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
09-02 15:26:06.780  3873  3873 D StrictMode: 	at com.google.r.v.a(PG:1161)
09-02 15:26:06.780  3873  3873 D StrictMode: 	at com.google.r.y.a(PG:2188)
09-02 15:26:06.780  3873  3873 D StrictMode: 	at com.google.r.e.b(PG:170)
09-02 15:26:06.780  3873  3873 D StrictMode: 	at com.google.r.e.b(PG:15188)
09-02 15:26:06.780  3873  3873 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
09-02 15:26:06.780  3873  3873 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-02 15:26:06.780  3873  3873 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-02 15:26:06.780  3873  3873 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-02 15:26:06.780  3873  3873 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-02 15:26:06.780  3873  3873 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-02 15:26:06.780  3873  3873 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-02 15:26:06.780  3873  3873 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-02 15:26:06.780  3873  3873 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-02 15:26:06.780  3873  3873 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-02 15:26:06.780  3873  3873 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-02 15:26:06.780  3873  3873 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-02 15:26:06.780  3873  3873 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-02 15:26:06.780  3873  3873 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-02 15:26:06.780  3873  3873 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-02 15:26:06.780  3873  3873 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-02 15:26:06.780  3873  3873 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-02 15:26:06.780  3873  3873 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-02 15:26:06.780  3873  3873 D StrictMode: StrictMode policy violation; ~duration=57 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-02 15:26:06.780  3873  3873 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-02 15:26:06.780  3873  3873 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-02 15:26:06.780  3873  3873 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-02 15:26:06.780  3873  3873 D StrictMode: 	at java.io.File.exists(File.java:361)
09-02 15:26:06.780  3873  3873 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
09-02 15:26:06.780  3873  3873 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
09-02 15:26:06.780  3873  3873 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
09-02 15:26:06.780  3873  3873 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
09-02 15:26:06.780  3873  3873 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
09-02 15:26:06.780  3873  3873 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-02 15:26:06.780  3873  3873 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-02 15:26:06.780  3873  3873 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-02 15:26:06.780  3873  3873 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-02 15:26:06.780  3873  3873 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-02 15:26:06.780  3873  3873 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-02 15:26:06.780  3873  3873 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-02 15:26:06.780  3873  3873 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-02 15:26:06.780  3873  3873 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-02 15:26:06.780  3873  3873 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-02 15:26:06.780  3873  3873 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-02 15:26:06.780  3873  3873 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-02 15:26:06.780  3873  3873 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-02 15:26:06.780  3873  3873 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-02 15:26:06.780  3873  3873 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-02 15:26:06.780  3873  3873 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-02 15:26:06.781  3873  3873 D StrictMode: StrictMode policy violation; ~duration=57 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-02 15:26:06.781  3873  3873 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-02 15:26:06.781  3873  3873 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-02 15:26:06.781  3873  3873 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-02 15:26:06.781  3873  3873 D StrictMode: 	at java.io.File.exists(File.java:361)
09-02 15:26:06.781  3873  3873 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
09-02 15:26:06.781  3873  3873 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-02 15:26:06.781  3873  3873 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-02 15:26:06.781  3873  3873 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-02 15:26:06.781  3873  3873 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-02 15:26:06.781  3873  3873 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-02 15:26:06.781  3873  3873 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-02 15:26:06.781  3873  3873 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-02 15:26:06.781  3873  3873 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-02 15:26:06.781  3873  3873 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-02 15:26:06.781  3873  3873 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-02 15:26:06.781  3873  3873 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-02 15:26:06.781  3873  3873 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-02 15:26:06.781  3873  3873 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-02 15:26:06.781  3873  3873 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-02 15:26:06.781  3873  3873 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-02 15:26:06.781  3873  3873 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-02 15:26:06.781  3873  3873 D StrictMode: StrictMode policy violation; ~duration=56 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-02 15:26:06.781  3873  3873 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-02 15:26:06.781  3873  3873 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
09-02 15:26:06.781  3873  3873 D StrictMode: 	at java.io.File.lastModified(File.java:569)
09-02 15:26:06.781  3873  3873 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
09-02 15:26:06.781  3873  3873 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-02 15:26:06.781  3873  3873 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-02 15:26:06.781  3873  3873 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-02 15:26:06.781  3873  3873 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-02 15:26:06.781  3873  3873 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-02 15:26:06.781  3873  3873 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-02 15:26:06.781  3873  3873 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-02 15:26:06.781  3873  3873 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-02 15:26:06.781  3873  3873 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-02 15:26:06.781  3873  3873 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-02 15:26:06.781  3873  3873 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-02 15:26:06.781  3873  3873 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-02 15:26:06.781  3873  3873 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-02 15:26:06.781  3873  3873 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-02 15:26:06.781  3873  3873 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-02 15:26:06.781  3873  3873 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-02 15:26:06.789  3853  3853 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-02 15:26:06.801  1528  1528 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-02 15:26:06.821  3853  3853 D DockEventReceiver: finishStartingService: stopping service
,09-02 15:26:06.826  1747  1747 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,09-02 15:26:06.829  1747  1747 D SystemUpdateService: onCreate
,09-02 15:26:06.832  1747  1747 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,09-02 15:26:06.845  1747  1747 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,09-02 15:26:06.848  1747  2421 I iu.UploadsManager: num queued entries: 0
,09-02 15:26:06.849  1747  2421 I iu.UploadsManager: num updated entries: 0
,09-02 15:26:06.850  1747  2421 I iu.SyncManager: NEXT; no task
,09-02 15:26:06.852  1747  1747 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-02 15:26:06.853  1747  1747 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
09-02 15:26:06.846  1747  3906 I SystemUpdateService: active receiver: enabled
,09-02 15:26:06.862  1747  3906 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-02 15:26:06.865  1747  3906 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,09-02 15:26:06.865  1747  3906 I SystemUpdateService: now status is 0 (complete)
09-02 15:26:06.865  1747  3906 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
,09-02 15:26:06.865  1747  3906 I SystemUpdateService: file has been verified
09-02 15:26:06.865  1747  3906 I SystemUpdateService: OTA package size = 12249756
,09-02 15:26:06.889  1747  3906 I SystemUpdateService: showing system update notification
,09-02 15:26:06.900   872  1994 I ActivityManager: Start proc 3909:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,09-02 15:26:06.915  3788  3788 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-02 15:26:06.924  2655  2674 D bt_stack_manager: event_shut_down_stack finished.
,09-02 15:26:06.925  2655  2673 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,09-02 15:26:06.926  2655  2655 D BtGatt.DebugUtils: handleDebugAction() action=null
09-02 15:26:06.927  2655  2673 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
09-02 15:26:06.927  2655  2655 D BtGatt.GattService: Received stop request...Stopping profile...
09-02 15:26:06.927  2655  2655 D BtGatt.GattService: stop()
,09-02 15:26:06.927  2655  2655 D BtGatt.AdvertiseManager: advertise clients cleared
,09-02 15:26:06.929  2655  2655 V BluetoothAdapterState: isTurningOff()=false
09-02 15:26:06.929  2655  2655 V BluetoothAdapterState: isTurningOn()=false
09-02 15:26:06.929  2655  2655 V BluetoothAdapterState: isBleTurningOn()=false
09-02 15:26:06.929  2655  2655 V BluetoothAdapterState: isBleTurningOff()=true
09-02 15:26:06.929  2655  2673 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
09-02 15:26:06.930  2655  2673 D BluetoothAdapterProperties: Setting state to 10
09-02 15:26:06.930  2655  2673 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
,09-02 15:26:06.932  2655  2673 I BluetoothAdapterState: Entering OffState
,09-02 15:26:06.932   872   889 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
,09-02 15:26:06.970  3909  3909 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm
,09-02 15:26:06.973  2655  2655 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,09-02 15:26:06.973  2655  2655 W BluetoothSdpJni: Cleaning up Bluetooth Health object
09-02 15:26:06.973  2655  2655 I BluetoothServiceJni: cleanupNative: return from cleanup
,09-02 15:26:06.974  2655  2674 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
09-02 15:26:06.976  2655  2674 D bt_stack_manager: event_clean_up_stack finished.
,09-02 15:26:06.977  3909  3909 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-02 15:26:06.991  2655  2655 I art     : System.exit called, status: 0
,09-02 15:26:06.991  2655  2655 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,09-02 15:26:07.000  3909  3909 D SprintDMHelper: simOperator: 
,09-02 15:26:07.000  3909  3909 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-02 15:26:07.036   872  1693 I ActivityManager: Start proc 3923:com.android.chrome/u0a40 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
,09-02 15:26:07.040   872  1693 I ActivityManager: Killing 3407:com.google.android.music:main/u0a66 (adj 15): empty #17
,09-02 15:26:07.077   872   882 I ActivityManager: Process com.android.bluetooth (pid 2655) has died
,09-02 15:26:07.081  1747  1747 D SystemUpdateService: onDestroy
,09-02 15:26:07.091   872   882 I ActivityManager: Killing 3033:com.google.android.keep/u0a79 (adj 15): empty #17
,09-02 15:26:07.202   872  1377 I ActivityManager: Start proc 3940:com.google.android.apps.magazines/u0a67 for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider
,09-02 15:26:07.206  3053  3939 I Babel   : connection state changed from UNKNOWN to DISCONNECTED
,09-02 15:26:07.226  3873  3894 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,09-02 15:26:07.247   872   889 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@d440804:true
,09-02 15:26:07.271  3940  3940 W System  : ClassLoader referenced unknown path: /system/app/Newsstand/lib/arm
,09-02 15:26:07.330  3940  3940 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
09-02 15:26:07.330  3940  3940 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
09-02 15:26:07.330  3940  3940 I GAv4    :   adb logcat -s GAv4
,09-02 15:26:07.351  3940  3940 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,09-02 15:26:07.357  3940  3940 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,09-02 15:26:07.395  3940  3957 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,09-02 15:26:07.506  3940  3940 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
,09-02 15:26:07.546  3940  3940 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,09-02 15:26:07.554  3940  3940 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 4993-4996)
,09-02 15:26:07.555  3940  3940 I LibraryLoader: Expected native library version number "",actual native library version number ""
,09-02 15:26:07.567  3940  3940 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {142b910}
,09-02 15:26:07.567  3940  3940 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-02 15:26:07.567  3940  3940 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,09-02 15:26:07.576  3940  3940 I BrowserStartupController: Initializing chromium process, singleProcess=true
,09-02 15:26:07.578  3940  3940 E SysUtils: ApplicationContext is null in ApplicationStatus
,09-02 15:26:07.595  3940  3940 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,09-02 15:26:07.609  3940  3940 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,09-02 15:26:07.609  3940  3940 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-02 15:26:07.609  3940  3940 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
09-02 15:26:07.609  3940  3940 I Adreno  : Build Date                       : 10/20/15
09-02 15:26:07.609  3940  3940 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
09-02 15:26:07.609  3940  3940 I Adreno  : Local Branch                     : M14
09-02 15:26:07.609  3940  3940 I Adreno  : Remote Branch                    : 
09-02 15:26:07.609  3940  3940 I Adreno  : Remote Branch                    : 
09-02 15:26:07.609  3940  3940 I Adreno  : Reconstruct Branch               : 
,09-02 15:26:07.695  3940  3940 I NSApplication: Starting up...
,09-02 15:26:07.694  3940  3986 W AudioManagerAndroid: Requires BLUETOOTH permission
,09-02 15:26:07.736   872  1692 I ActivityManager: Start proc 3991:com.google.android.apps.photos/u0a71 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
,09-02 15:26:07.737   872  1692 I ActivityManager: Killing 3468:com.android.providers.calendar/u0a3 (adj 15): empty #17
,09-02 15:26:07.784  3991  3991 W System  : ClassLoader referenced unknown path: /system/app/Photos/lib/arm
,09-02 15:26:07.999   872  1959 I ActivityManager: Killing 1695:android.process.acore/u0a5 (adj 15): empty #17
,09-02 15:26:08.116   872   882 I ActivityManager: Start proc 4005:com.google.android.apps.gcs/u0a89 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,09-02 15:26:08.165  4005  4005 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm
,09-02 15:26:08.216  4005  4005 W ClientExperimentManager: [1] d.a: com.google.android.apps.gcs does not have permission com.google.android.apps.gcs.WRITE_EXPERIMENTS; disabling overrides
,09-02 15:26:08.239   872   882 I ActivityManager: Start proc 4028:com.google.android.keep/u0a79 for broadcast com.google.android.keep/.notification.AlertReceiver
,09-02 15:26:08.240   872   882 I ActivityManager: Killing 3641:com.google.android.partnersetup/u0a16 (adj 15): empty #17
,09-02 15:26:08.314  4028  4028 W System  : ClassLoader referenced unknown path: /system/app/PrebuiltKeep/lib/arm
,09-02 15:26:08.564   872  1692 I ActivityManager: Killing 3656:com.android.musicfx/u0a18 (adj 15): empty #17
,09-02 15:26:09.456   872  1944 D WifiService: setWifiEnabled: true pid=3788, uid=10000
,09-02 15:26:09.456   872  1944 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-02 15:26:09.472   872  1306 D WifiConfigStore: Loading config and enabling all networks 
,09-02 15:26:09.480  3788  3788 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-02 15:26:09.480  3788  3788 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-02 15:26:09.480  3788  3788 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 15:26:09.480  3788  3788 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-02 15:26:09.480  3788  3788 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-02 15:26:09.480  3788  3788 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-02 15:26:09.480  3788  3788 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-02 15:26:09.480  3788  3788 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-02 15:26:09.480  3788  3788 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-02 15:26:09.480  3788  3788 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-02 15:26:09.481  3788  3788 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-02 15:26:09.483  3788  3788 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-02 15:26:09.484  3788  3788 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-02 15:26:09.484  3788  3788 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 15:26:09.484  3788  3788 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-02 15:26:09.484  3788  3788 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-02 15:26:09.484  3788  3788 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-02 15:26:09.484  3788  3788 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-02 15:26:09.484  3788  3788 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-02 15:26:09.484  3788  3788 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-02 15:26:09.484  3788  3788 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-02 15:26:09.484  3788  3788 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-02 15:26:09.504   872  1306 D WifiConfigStore: loaded 0 passpoint configs
,09-02 15:26:09.505   872  1306 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,09-02 15:26:09.506   872  1306 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,09-02 15:26:09.507   872  1306 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
09-02 15:26:09.508   872  1306 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
,09-02 15:26:09.508   872  1306 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
09-02 15:26:09.508   872  1306 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,09-02 15:26:09.528   872  1306 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=9.50 rxSuccessRate=13.88 delta 1000 -> 994
,09-02 15:26:09.528   372   870 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
09-02 15:26:09.531   372   870 D CommandListener: Setting iface cfg
,09-02 15:26:09.533   872  1305 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '134 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 134 Failed to set address (No such device)'
09-02 15:26:09.533   872  1305 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,09-02 15:26:09.536   872  1306 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
,09-02 15:26:09.536   872  1306 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-02 15:26:09.543   872  1306 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,09-02 15:26:09.588   872  1306 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,09-02 15:26:09.591  1465  1465 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,09-02 15:26:09.607   872  1305 D WifiNative-HAL: p2pGetDeviceAddress
,09-02 15:26:09.609   872  1305 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,09-02 15:26:10.017  1465  1465 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,09-02 15:26:10.064  1465  1465 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,09-02 15:26:10.066  1465  1465 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,09-02 15:26:10.075   872  1306 D WifiConfigStore: Retrieve network priorities after PNO.
,09-02 15:26:10.090   872  1306 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-02 15:26:10.090   872  1306 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-02 15:26:10.091   872  1308 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,09-02 15:26:10.117   872  1306 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-02 15:26:10.134   372   870 D CommandListener: Setting iface cfg
,09-02 15:26:10.135   872  1306 D WifiStateMachine: Start Dhcp Watchdog 2
,09-02 15:26:10.150   872  1308 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
,09-02 15:26:10.152   872  1306 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,09-02 15:26:10.200   872  4058 D DhcpClient: Receive thread started
,09-02 15:26:10.287   872  1306 E native  : do suspend false
,09-02 15:26:10.310   872  1870 D DhcpClient: Broadcasting DHCPDISCOVER
,09-02 15:26:10.324   872  4058 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.101, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172685, domain null
,09-02 15:26:10.325   872  1870 D DhcpClient: Got pending lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172685 seconds
,09-02 15:26:10.328   872  1870 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.101 serverid=192.168.1.1
,09-02 15:26:10.361   872  4058 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.101, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,09-02 15:26:10.362   872  1870 D DhcpClient: Confirmed lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,09-02 15:26:10.367   372   870 D CommandListener: Setting iface cfg
,09-02 15:26:10.378   872  1306 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,09-02 15:26:10.379   872  1870 D DhcpClient: Scheduling renewal in 86399s
,09-02 15:26:10.396   872  1306 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,09-02 15:26:10.397   872  1306 D WifiConfigStore: No blacklist allowed without epno enabled
,09-02 15:26:10.397   872  1308 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
09-02 15:26:10.398   872  1308 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,09-02 15:26:10.404   872  1306 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,09-02 15:26:10.405   872  1308 D ConnectivityService: Adding iface wlan0 to network 101
,09-02 15:26:10.452   872  1308 E ConnectivityService: Unexpected mtu value: 0, wlan0
,09-02 15:26:10.453   872  1308 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
,09-02 15:26:10.456   872  1308 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,09-02 15:26:10.457   872  1308 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,09-02 15:26:10.459   872  1308 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,09-02 15:26:10.475   872  1308 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-02 15:26:10.482   872  1308 D ConnectivityService: scheduleUnvalidatedPrompt 101
,09-02 15:26:10.482   872  1308 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
09-02 15:26:10.482   872  1308 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101],
09-02 15:26:10.482   872  1308 D ConnectivityService:    accepting network in place of null
09-02 15:26:10.482   872  1306 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
,09-02 15:26:10.483   872  1308 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.101/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -44]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
09-02 15:26:10.484   872  1306 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,09-02 15:26:10.533   372   870 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-02 15:26:10.567   372   870 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-02 15:26:10.575   872  1308 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,09-02 15:26:10.575   872  1308 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-02 15:26:10.577   872  1308 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
09-02 15:26:10.582   872   889 D Tethering: MasterInitialState.processMessage what=3
,09-02 15:26:10.605  3788  3788 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-02 15:26:10.605  3788  3788 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-02 15:26:10.605  3788  3788 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 15:26:10.605  3788  3788 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-02 15:26:10.605  3788  3788 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-02 15:26:10.605  3788  3788 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-02 15:26:10.605  3788  3788 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-02 15:26:10.605  3788  3788 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-02 15:26:10.605  3788  3788 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-02 15:26:10.605  3788  3788 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-02 15:26:10.605  3788  3788 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-02 15:26:10.609  3788  3788 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-02 15:26:10.610  3788  3788 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-02 15:26:10.610  3788  3788 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 15:26:10.610  3788  3788 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-02 15:26:10.610  3788  3788 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-02 15:26:10.610  3788  3788 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-02 15:26:10.610  3788  3788 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-02 15:26:10.610  3788  3788 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-02 15:26:10.610  3788  3788 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-02 15:26:10.610  3788  3788 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-02 15:26:10.610  3788  3788 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-02 15:26:10.615  1747  1747 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,09-02 15:26:10.618  1747  1747 D SystemUpdateService: onCreate
,09-02 15:26:10.622  1747  1747 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,09-02 15:26:10.625  1747  4068 I SystemUpdateService: active receiver: enabled
,09-02 15:26:10.628  1747  4068 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-02 15:26:10.630  1747  4068 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,09-02 15:26:10.630  1747  4068 I SystemUpdateService: now status is 0 (complete)
,09-02 15:26:10.631  1747  4068 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
,09-02 15:26:10.631  1747  4068 I SystemUpdateService: file has been verified
09-02 15:26:10.632  1747  4068 I SystemUpdateService: OTA package size = 12249756
,09-02 15:26:10.635  1747  4068 I SystemUpdateService: showing system update notification
,09-02 15:26:10.636   872  4057 D NetlinkSocketObserver: NeighborEvent{elapsedMs=138077, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-02 15:26:10.641  1747  1747 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,09-02 15:26:10.644  1747  2421 I iu.UploadsManager: num queued entries: 0
,09-02 15:26:10.645  1747  2421 I iu.UploadsManager: num updated entries: 0
,09-02 15:26:10.646  1747  1747 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms,
,09-02 15:26:10.647  1747  4072 I MDM     : [177] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
,09-02 15:26:10.647  1747  4072 W BaseAppContext: Using Auth Proxy for data requests.
09-02 15:26:10.647  1747  1747 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,09-02 15:26:10.648  1747  4072 V GoogleAuthProtoRequest: [177] a.<init>: mAccountName set to: thalitester@gmail.com
,09-02 15:26:10.650  3909  3909 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-02 15:26:10.652  1747  1747 D SystemUpdateService: onDestroy
,09-02 15:26:10.656  1528  1528 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-02 15:26:10.658  1528  1528 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-02 15:26:10.659  3909  3909 D SprintDMHelper: simOperator: 
09-02 15:26:10.659  3909  3909 D SprintDMReceiver: Not Sprint UICC, don't do anything.
09-02 15:26:10.659  1747  2421 I iu.SyncManager: NEXT; no task
,09-02 15:26:10.689  1528  1540 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
,09-02 15:26:10.689  1528  1540 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
09-02 15:26:10.690  1528  1540 I GLSUser : [GLSUser] Extracting token using key: Auth
09-02 15:26:10.690  1528  1540 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-02 15:26:10.706  1747  4072 E MDM     : [177] SitrepService.a: Error sending sitrep.
,09-02 15:26:10.739  4028  4078 V KeepSync: Connecting to GoogleApiClient
,09-02 15:26:10.739   872   882 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,09-02 15:26:10.809  1528  2318 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,09-02 15:26:10.809  1528  2318 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
09-02 15:26:10.809  1528  2318 I GLSUser : [GLSUser] Extracting token using key: Auth
09-02 15:26:10.809  1528  2318 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-02 15:26:10.832  1747  4079 V BaseAuthAsyncOperation: access token request failed
,09-02 15:26:10.835  4028  4078 V KeepSync: GoogleApiClient failed to connect with error code: 4
,09-02 15:26:10.938  1528  2380 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,09-02 15:26:10.938  1528  2380 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
09-02 15:26:10.938  1528  2380 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-02 15:26:10.938  1528  2380 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-02 15:26:10.955  4028  4078 E KeepSync: IOException
09-02 15:26:10.955  4028  4078 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
09-02 15:26:10.955  4028  4078 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
09-02 15:26:10.955  4028  4078 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
09-02 15:26:10.955  4028  4078 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
09-02 15:26:10.955  4028  4078 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
09-02 15:26:10.955  4028  4078 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
09-02 15:26:10.955  4028  4078 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
09-02 15:26:10.955  4028  4078 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
09-02 15:26:10.955  4028  4078 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
09-02 15:26:10.955  4028  4078 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
09-02 15:26:10.955  4028  4078 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
09-02 15:26:10.955  4028  4078 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
09-02 15:26:10.955  4028  4078 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
09-02 15:26:10.955  4028  4078 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
09-02 15:26:10.955  4028  4078 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
09-02 15:26:10.955  4028  4078 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
09-02 15:26:10.955  4028  4078 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
09-02 15:26:10.955  4028  4078 E KeepSync: 	... 10 more
,09-02 15:26:10.956  4028  4078 W KeepSync: Sync result 2
,09-02 15:26:10.968   872   884 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 129314, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,09-02 15:26:11.577   872  1308 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,09-02 15:26:12.461   872  3116 D WifiService: setWifiEnabled: false pid=3788, uid=10000
09-02 15:26:12.462   872  3116 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-02 15:26:12.485  1465  1465 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,09-02 15:26:12.494   872  1306 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,09-02 15:26:12.494   872  1306 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
09-02 15:26:12.494   872  1306 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-02 15:26:12.495   872  1306 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-02 15:26:12.512   872  1870 D DhcpClient: Clearing IP address
,09-02 15:26:12.513   372   870 D CommandListener: Clearing all IP addresses on wlan0
,09-02 15:26:12.522  3053  4074 W Babel_NetworkConnectionCheckingService: IO exceptions, probably not a captive portal 
,09-02 15:26:12.523   372   870 D CommandListener: Setting iface cfg
09-02 15:26:12.524  3053  4074 W Babel_NetworkConnectionCheckingService: java.net.SocketTimeoutException: failed to connect to clients3.google.com/172.217.20.142 (port 80) after 5000ms: isConnected failed: ETIMEDOUT (Connection timed out)
09-02 15:26:12.524  3053  4074 W Babel_NetworkConnectionCheckingService: 	at libcore.io.IoBridge.isConnected(IoBridge.java:232)
09-02 15:26:12.524  3053  4074 W Babel_NetworkConnectionCheckingService: 	at libcore.io.IoBridge.connectErrno(IoBridge.java:171)
09-02 15:26:12.524  3053  4074 W Babel_NetworkConnectionCheckingService: 	at libcore.io.IoBridge.connect(IoBridge.java:122)
09-02 15:26:12.524  3053  4074 W Babel_NetworkConnectionCheckingService: 	at java.net.PlainSocketImpl.connect(PlainSocketImpl.java:183)
09-02 15:26:12.524  3053  4074 W Babel_NetworkConnectionCheckingService: 	at java.net.PlainSocketImpl.connect(PlainSocketImpl.java:452)
09-02 15:26:12.524  3053  4074 W Babel_NetworkConnectionCheckingService: 	at java.net.Socket.connect(Socket.java:884)
09-02 15:26:12.524  3053  4074 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.internal.Platform.connectSocket(Platform.java:117)
09-02 15:26:12.524  3053  4074 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.internal.http.SocketConnector.connectRawSocket(SocketConnector.java:160)
09-02 15:26:12.524  3053  4074 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.internal.http.SocketConnector.connectCleartext(SocketConnector.java:67)
09-02 15:26:12.524  3053  4074 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.Connection.connect(Connection.java:152)
09-02 15:26:12.524  3053  4074 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.Connection.connectAndSetOwner(Connection.java:185)
09-02 15:26:12.524  3053  4074 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.OkHttpClient$1.connectAndSetOwner(OkHttpClient.java:128)
09-02 15:26:12.524  3053  4074 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.internal.http.HttpEngine.nextConnection(HttpEngine.java:341)
09-02 15:26:12.524  3053  4074 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.internal.http.HttpEngine.connect(HttpEngine.java:330)
09-02 15:26:12.524  3053  4074 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.internal.http.HttpEngine.sendRequest(HttpEngine.java:248)
09-02 15:26:12.524  3053  4074 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.internal.huc.HttpURLConnectionImpl.execute(HttpURLConnectionImpl.java:437)
09-02 15:26:12.524  3053  4074 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.internal.huc.HttpURLConnectionImpl.getResponse(HttpURLConnectionImpl.java:388)
09-02 15:26:12.524  3053  4074 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.internal.huc.HttpURLConnectionImpl.getInputStream(HttpURLConnectionImpl.java:231)
09-02 15:26:12.524  3053  4074 W Babel_NetworkConnectionCheckingService: 	at com.google.android.apps.hangouts.service.NetworkConnectionCheckingService.a(SourceFile:129)
09-02 15:26:12.524  3053  4074 W Babel_NetworkConnectionCheckingService: 	at com.google.android.apps.hangouts.service.NetworkConnectionCheckingService.onHandleIntent(SourceFile:1100)
09-02 15:26:12.524  3053  4074 W Babel_NetworkConnectionCheckingService: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
09-02 15:26:12.524  3053  4074 W Babel_NetworkConnectionCheckingService: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-02 15:26:12.524  3053  4074 W Babel_NetworkConnectionCheckingService: 	at android.os.Looper.loop(Looper.java:148)
09-02 15:26:12.524  3053  4074 W Babel_NetworkConnectionCheckingService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-02 15:26:12.524  3053  4074 W Babel_NetworkConnectionCheckingService: Caused by: android.system.ErrnoException: isConnected failed: ETIMEDOUT (Connection timed out)
09-02 15:26:12.524  3053  4074 W Ba,bel_NetworkConnectionCheckingService: 	at libcore.io.IoBridge.isConnected(IoBridge.java:223)
09-02 15:26:12.524  3053  4074 W Babel_NetworkConnectionCheckingService: 	... 23 more
09-02 15:26:12.524  3053  4074 I Babel   : connection state changed from DISCONNECTED to CONNECTED
09-02 15:26:12.525   872  4058 D DhcpClient: Receive thread stopped
09-02 15:26:12.530   872  1308 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
09-02 15:26:12.530   872  1308 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 3
09-02 15:26:12.533   872  1306 D WifiStateMachine: Start Disconnecting Watchdog 2
09-02 15:26:12.534   872  1306 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-02 15:26:12.535   395   395 E Parcel  : Reading a NULL string not supported here.
09-02 15:26:12.544   372   870 D CommandListener: Clearing all IP addresses on wlan0
09-02 15:26:12.548   872  1308 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
,09-02 15:26:12.559   872  1944 I ActivityManager: Killing 2266:com.google.android.gms.wearable/u0a11 (adj 15): empty #17
,09-02 15:26:12.582   372   870 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-02 15:26:12.608   872  1306 D WifiConfigStore: Retrieve network priorities after PNO.
,09-02 15:26:12.611  3788  3788 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-02 15:26:12.611  3788  3788 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-02 15:26:12.611  3788  3788 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 15:26:12.611  3788  3788 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-02 15:26:12.611  3788  3788 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-02 15:26:12.611  3788  3788 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-02 15:26:12.611  3788  3788 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-02 15:26:12.611  3788  3788 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-02 15:26:12.611  3788  3788 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-02 15:26:12.611  3788  3788 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-02 15:26:12.612  3788  3788 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-02 15:26:12.613  3788  3788 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-02 15:26:12.613  3788  3788 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-02 15:26:12.613  3788  3788 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 15:26:12.613  3788  3788 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-02 15:26:12.613  3788  3788 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-02 15:26:12.613  3788  3788 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-02 15:26:12.613  3788  3788 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-02 15:26:12.613  3788  3788 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-02 15:26:12.613  3788  3788 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-02 15:26:12.613   372   870 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
09-02 15:26:12.613  3788  3788 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-02 15:26:12.613  3788  3788 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-02 15:26:12.614  2183  2297 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-02 15:26:12.614   872  1308 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
09-02 15:26:12.615   872  1308 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-02 15:26:12.622   872   889 D Tethering: MasterInitialState.processMessage what=3
,09-02 15:26:12.623  3788  3788 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-02 15:26:12.624  3788  3788 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-02 15:26:12.626   872  1306 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,09-02 15:26:12.640  1747  1747 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,09-02 15:26:12.644  1747  1747 D SystemUpdateService: onCreate
,09-02 15:26:12.649  1747  1747 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,09-02 15:26:12.658  1747  1747 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,09-02 15:26:12.663  1747  2421 I iu.UploadsManager: num queued entries: 0
,09-02 15:26:12.663  1747  2421 I iu.UploadsManager: num updated entries: 0
,09-02 15:26:12.665  1747  1747 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-02 15:26:12.666  1747  1747 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,09-02 15:26:12.668  3909  3909 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-02 15:26:12.672  3909  3909 D SprintDMHelper: simOperator: 
,09-02 15:26:12.672  3909  3909 D SprintDMReceiver: Not Sprint UICC, don't do anything.
09-02 15:26:12.673  1747  4092 I SystemUpdateService: active receiver: enabled
09-02 15:26:12.675  1747  2421 I iu.SyncManager: NEXT; no task
,09-02 15:26:12.686  1747  4092 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-02 15:26:12.692   372   870 E Netd    : netlink response contains error (No such file or directory)
,09-02 15:26:12.693   872  1308 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,09-02 15:26:12.700  3053  4096 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,09-02 15:26:12.703  1747  4092 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,09-02 15:26:12.703  1747  4092 I SystemUpdateService: now status is 0 (complete)
09-02 15:26:12.703  1747  4092 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
09-02 15:26:12.703  1747  4092 I SystemUpdateService: file has been verified
,09-02 15:26:12.704  1747  4092 I SystemUpdateService: OTA package size = 12249756
,09-02 15:26:12.714  1747  4092 I SystemUpdateService: showing system update notification
,09-02 15:26:12.722  1747  1747 D SystemUpdateService: onDestroy
,09-02 15:26:13.397  4028  4035 E DataBuffer: Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (com.google.android.gms.reminders.model.RemindersBuffer@71a9c30)
,09-02 15:26:14.344  1747  4099 I EventLogService: Opted in for usage reporting
,09-02 15:26:14.344  1747  4099 I EventLogService: Aggregate from 1472820971694 (log), 1472820971694 (data)
,09-02 15:26:14.398  1747  4099 W EventLogAggregator: Unknown tag: snet_gcore
,09-02 15:26:14.398  1747  4099 W EventLogAggregator: Unknown tag: snet_launch_service
,09-02 15:26:14.457  1747  4099 I ServiceDumpSys: dumping service [account]
,09-02 15:26:14.529  1528  1528 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-02 15:26:14.558  1528  2318 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,09-02 15:26:14.558  1528  2318 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
,09-02 15:26:14.558  1528  2318 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-02 15:26:14.558  1528  2318 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-02 15:26:14.587  3504  3504 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,09-02 15:26:14.587  3504  3504 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
09-02 15:26:14.587  3504  3504 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 4.
,09-02 15:26:15.511   872   889 I ActivityManager: Start proc 4102:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,09-02 15:26:15.623  4102  4102 D AdapterServiceConfig: Adding HeadsetService
,09-02 15:26:15.623  4102  4102 D AdapterServiceConfig: Adding A2dpService
,09-02 15:26:15.623  4102  4102 D AdapterServiceConfig: Adding HidService
,09-02 15:26:15.623  4102  4102 D AdapterServiceConfig: Adding HealthService
,09-02 15:26:15.624  4102  4102 D AdapterServiceConfig: Adding PanService
,09-02 15:26:15.624  4102  4102 D AdapterServiceConfig: Adding GattService
,09-02 15:26:15.624  4102  4102 D AdapterServiceConfig: Adding BluetoothMapService
,09-02 15:26:15.639  4102  4102 D BluetoothAdapterState: make() - Creating AdapterState,
09-02 15:26:15.639   872   889 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@ca673dd:true
,09-02 15:26:15.645  4102  4102 I bt_bluedroid: init
,09-02 15:26:15.645  4102  4114 I BluetoothAdapterState: Entering OffState
,09-02 15:26:15.650  4102  4115 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,09-02 15:26:15.651  4102  4115 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
09-02 15:26:15.651  4102  4115 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
09-02 15:26:15.652  4102  4115 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,09-02 15:26:15.653  4102  4102 I bt_bluedroid: get_profile_interface socket
,09-02 15:26:15.655  4102  4118 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,09-02 15:26:15.656  4102  4102 I bt_bluedroid: get_profile_interface sdp
09-02 15:26:15.657  4102  4118 D BluetoothAdapterProperties: Name is: Nexus 6
,09-02 15:26:15.660  4102  4113 I bt_bluedroid: config_hci_snoop_log
,09-02 15:26:15.661   872   889 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,09-02 15:26:15.667  4102  4114 D BluetoothAdapterState: Current state: OFF, message: 0
,09-02 15:26:15.668  4102  4114 D BluetoothAdapterProperties: Setting state to 14
09-02 15:26:15.668  4102  4114 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,09-02 15:26:15.672  4102  4114 D BluetoothBondStateMachine: make
,09-02 15:26:15.677  4102  4119 I BluetoothBondStateMachine: StableState(): Entering Off State
,09-02 15:26:15.685  4102  4114 I BluetoothAdapterState: Entering PendingCommandState
,09-02 15:26:15.685  4102  4102 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,09-02 15:26:15.693  4102  4102 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@12ec4c6
,09-02 15:26:15.694  4102  4102 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-02 15:26:15.695  4102  4102 D BtGatt.GattService: Received start request. Starting profile...
,09-02 15:26:15.696  4102  4102 D BtGatt.GattService: start()
,09-02 15:26:15.696  4102  4102 I bt_bluedroid: get_profile_interface gatt
,09-02 15:26:15.697  4102  4102 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@12ec4c6
,09-02 15:26:15.698  4102  4102 D BtGatt.AdvertiseManager: advertise manager created
,09-02 15:26:15.705  4102  4102 V BluetoothAdapterState: isTurningOff()=false
09-02 15:26:15.706  4102  4102 V BluetoothAdapterState: isTurningOn()=false
,09-02 15:26:15.706  4102  4102 V BluetoothAdapterState: isBleTurningOn()=true,
09-02 15:26:15.706  4102  4102 V BluetoothAdapterState: isBleTurningOff()=false
,09-02 15:26:15.707  4102  4114 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4,
09-02 15:26:15.707  4102  4114 I bt_bluedroid: enable
,09-02 15:26:15.708  4102  4115 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,09-02 15:26:15.709  4102  4115 I bt_hci  : start_up
,09-02 15:26:15.719  4102  4115 I bt_vendor: alloc value 0xb39b9189
,09-02 15:26:15.719  4102  4115 I bt_vendor: init
09-02 15:26:15.719  4102  4115 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf,
09-02 15:26:15.720  4102  4115 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,09-02 15:26:15.827  4102  4115 D bt_hci  : start_up starting async portion
,09-02 15:26:15.828  4102  4122 I bt_hci  : event_finish_startup
,09-02 15:26:15.828  4102  4122 I bt_hci_h4: hal_open
,09-02 15:26:15.829  4102  4122 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,09-02 15:26:15.846  4102  4122 I bt_userial_vendor: device fd = 51 open
,09-02 15:26:15.869  4102  4122 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-02 15:26:15.900  4102  4122 D bt_hwcfg: Chipset BCM4354A2
,09-02 15:26:15.901  4102  4122 D bt_hwcfg: Target name = [BCM4354A2]
09-02 15:26:15.903  4102  4122 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,09-02 15:26:16.181   872  4056 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on <unknown ssid>, connectivitycheck.gstatic.com=2a00:1450:4001:814::200e
,09-02 15:26:16.187   872  4056 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Probably not a portal: exception java.net.SocketException: Binding socket to network 101 failed: ENONET (Machine is not on the network)
,09-02 15:26:16.188   872  1308 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,09-02 15:26:16.578  4102  4122 I bt_hwcfg: bt vendor lib: set UART baud 115200
,09-02 15:26:16.580  4102  4122 D bt_hwcfg: Settlement delay -- 100 ms,
,09-02 15:26:16.580  4102  4122 I bt_hwcfg: Setting fw settlement delay to 100 
,09-02 15:26:16.697  4102  4122 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-02 15:26:16.699  4102  4122 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,09-02 15:26:16.727  4102  4122 I bt_hwcfg: vendor lib fwcfg completed
,09-02 15:26:16.728  4102  4122 I bt_vendor: firmware callback
09-02 15:26:16.728  4102  4122 I bt_hci  : firmware_config_callback
,09-02 15:26:16.737  4102  4124 I bt_btu  : btu_task pending for preload complete event
,09-02 15:26:16.738  4102  4124 I bt_btu_task: Bluetooth chip preload is complete
,09-02 15:26:16.738  4102  4124 I bt_btu  : btu_task received preload complete event
,09-02 15:26:16.747  4102  4124 I         : BTE_InitTraceLevels -- TRC_HCI
,09-02 15:26:16.747  4102  4124 I         : BTE_InitTraceLevels -- TRC_L2CAP
,09-02 15:26:16.748  4102  4124 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,09-02 15:26:16.748  4102  4124 I         : BTE_InitTraceLevels -- TRC_AVDT
,09-02 15:26:16.748  4102  4124 I         : BTE_InitTraceLevels -- TRC_AVRC
09-02 15:26:16.749  4102  4124 I         : BTE_InitTraceLevels -- TRC_A2D
,09-02 15:26:16.749  4102  4124 I         : BTE_InitTraceLevels -- TRC_BNEP
09-02 15:26:16.749  4102  4124 I         : BTE_InitTraceLevels -- TRC_BTM
09-02 15:26:16.750  4102  4124 I         : BTE_InitTraceLevels -- TRC_GAP
09-02 15:26:16.750  4102  4124 I         : BTE_InitTraceLevels -- TRC_PAN
,09-02 15:26:16.750  4102  4124 I         : BTE_InitTraceLevels -- TRC_SDP
09-02 15:26:16.750  4102  4124 I         : BTE_InitTraceLevels -- TRC_GATT
09-02 15:26:16.751  4102  4124 I         : BTE_InitTraceLevels -- TRC_SMP
09-02 15:26:16.751  4102  4124 I         : BTE_InitTraceLevels -- TRC_BTAPP
,09-02 15:26:16.751  4102  4124 I         : BTE_InitTraceLevels -- TRC_BTIF
,09-02 15:26:16.883  4102  4124 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb3936d9d,
09-02 15:26:16.883  4102  4124 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb3936d9d 
,09-02 15:26:16.894  4102  4118 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,09-02 15:26:16.895  4102  4118 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000,
,09-02 15:26:16.896  4102  4118 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
09-02 15:26:16.899  4102  4118 D BluetoothAdapterProperties: Name is: Nexus 6
09-02 15:26:16.903  4102  4118 D BluetoothAdapterProperties: Scan Mode:20
,09-02 15:26:16.905  4102  4118 D BluetoothAdapterProperties: Discoverable Timeout:120
,09-02 15:26:16.905  4102  4118 D bt_hci  : do_postload posting postload work item
09-02 15:26:16.906  4102  4122 I bt_hci  : event_postload
09-02 15:26:16.906  4102  4122 I bt_vendor: sco_config_cb
,09-02 15:26:16.906  4102  4122 I bt_hci  : sco_config_callback postload finished.,
09-02 15:26:16.909  4102  4118 D bt_bte_conf: Device ID record 1 : primary
09-02 15:26:16.910  4102  4118 D bt_bte_conf:   vendorId            = 000f
09-02 15:26:16.910  4102  4118 D bt_bte_conf:   vendorIdSource      = 0001
09-02 15:26:16.910  3788  3788 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-02 15:26:16.910  4102  4118 D bt_bte_conf:   product             = 1200
09-02 15:26:16.911  4102  4118 D bt_bte_conf:   version             = 1436
,09-02 15:26:16.911  4102  4118 D bt_bte_conf:   clientExecutableURL = 
09-02 15:26:16.911  4102  4118 D bt_bte_conf:   serviceDescription  = 
09-02 15:26:16.911  4102  4118 D bt_bte_conf:   documentationURL    = 
09-02 15:26:16.912  4102  4118 D bt_bte_conf: bte_load_did_conf no section named DID2.
09-02 15:26:16.912  4102  4115 D bt_stack_manager: event_start_up_stack finished
09-02 15:26:16.913  4102  4122 I bt_vendor: low_power_mode_cb
09-02 15:26:16.913  4102  4114 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
09-02 15:26:16.914  4102  4114 D BluetoothAdapterProperties: Setting state to 15
,09-02 15:26:16.914  4102  4114 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
,09-02 15:26:16.916  3788  3788 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-02 15:26:16.917  4102  4114 I BluetoothAdapterState: Entering BleOnState
09-02 15:26:16.921  4102  4114 D BluetoothAdapterState: Current state: BLE ON, message: 1
09-02 15:26:16.921  4102  4114 D BluetoothAdapterProperties: Setting state to 11
09-02 15:26:16.921  4102  4114 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
09-02 15:26:16.930  3788  3788 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-02 15:26:16.934  3788  3788 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-02 15:26:16.936  4102  4102 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@12ec4c6
09-02 15:26:16.938  4102  4102 D HeadsetService: Received start request. Starting profile...
09-02 15:26:16.941  4102  4114 I BluetoothAdapterState: Entering PendingCommandState
,09-02 15:26:16.945  4102  4102 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,09-02 15:26:16.945  4102  4102 D HeadsetStateMachine: make
,09-02 15:26:16.955  4102  4102 D HeadsetStateMachine: max_hf_connections = 1
,09-02 15:26:16.955  4102  4102 I bt_bluedroid: get_profile_interface handsfree
09-02 15:26:16.955  4102  4118 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
09-02 15:26:16.956  4102  4118 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
,09-02 15:26:16.961  4102  4102 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@12ec4c6
,09-02 15:26:16.962  4102  4102 D A2dpService: Received start request. Starting profile...
09-02 15:26:16.962  4102  4102 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,09-02 15:26:16.963  4102  4102 I bt_bluedroid: get_profile_interface avrcp
,09-02 15:26:16.968  4102  4102 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,09-02 15:26:16.969  4102  4102 I BluetoothA2dpServiceJni: classInitNative: succeeds
09-02 15:26:16.969  4102  4102 D A2dpStateMachine: make
,09-02 15:26:16.970  4102  4102 I bt_bluedroid: get_profile_interface a2dp
,09-02 15:26:16.971  4102  4118 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,09-02 15:26:16.972  4102  4133 D A2dpStateMachine: Enter Disconnected: -2
,09-02 15:26:16.973  4102  4102 I BluetoothHidServiceJni: classInitNative: succeeds
,09-02 15:26:16.974  4102  4102 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@12ec4c6
,09-02 15:26:16.975  4102  4102 D HidService: Received start request. Starting profile...
,09-02 15:26:16.975  4102  4102 I bt_bluedroid: get_profile_interface hidhost
09-02 15:26:16.976  4102  4118 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb39183e5
,09-02 15:26:16.975  3853  3853 D BluetoothInputDevice: Proxy object connected
,09-02 15:26:16.976  4102  4118 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
09-02 15:26:16.976  4102  4102 D HidService: setHidService(): set to: null
09-02 15:26:16.977  4102  4102 I BluetoothHealthServiceJni: classInitNative: succeeds
,09-02 15:26:16.977  4102  4102 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@12ec4c6
09-02 15:26:16.977  3853  3853 D HidProfile: Bluetooth service connected
09-02 15:26:16.978  4102  4102 D HealthService: Received start request. Starting profile...
09-02 15:26:16.979  4102  4102 I bt_bluedroid: get_profile_interface health
,09-02 15:26:16.980  4102  4102 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,09-02 15:26:16.981  4102  4102 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@12ec4c6
,09-02 15:26:16.982  4102  4102 D PanService: Received start request. Starting profile...
09-02 15:26:16.982  4102  4102 D BluetoothPanServiceJni: initializeNative(L110): pan
09-02 15:26:16.982  4102  4102 I bt_bluedroid: get_profile_interface pan
09-02 15:26:16.982  3853  3853 D BluetoothPan: BluetoothPAN Proxy object connected
09-02 15:26:16.983  4102  4118 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
09-02 15:26:16.983  3853  3853 D PanProfile: Bluetooth service connected
,09-02 15:26:16.986  4102  4102 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@12ec4c6
,09-02 15:26:16.987  4102  4102 D BluetoothMapService: Received start request. Starting profile...
09-02 15:26:16.987  4102  4102 D BluetoothMapService: start()
,09-02 15:26:16.987  3853  3853 D BluetoothMap: Proxy object connected
,09-02 15:26:16.989  3853  3853 D MapProfile: Bluetooth service connected
09-02 15:26:16.989  4102  4102 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,09-02 15:26:16.989  3853  3853 D BluetoothMap: getConnectedDevices()
09-02 15:26:16.990  4102  4102 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
09-02 15:26:16.990  4102  4102 D BluetoothMapAppObserver: createReceiver()
,09-02 15:26:16.990  3853  3853 D BluetoothMap: Bluetooth is Not enabled
09-02 15:26:16.991  4102  4102 D BluetoothMapAppObserver: initObservers()
,09-02 15:26:16.991  4102  4102 D BluetoothMapAppObserver: getEnabledAccountItems()
,09-02 15:26:17.000  1528  1528 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-02 15:26:17.001  4102  4102 V BluetoothAdapterState: isTurningOff()=false
,09-02 15:26:17.001  4102  4102 V BluetoothAdapterState: isTurningOn()=true
09-02 15:26:17.001  4102  4102 V BluetoothAdapterState: isBleTurningOn()=false
09-02 15:26:17.001  4102  4102 V BluetoothAdapterState: isBleTurningOff()=false
,09-02 15:26:17.001  4102  4131 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
09-02 15:26:17.004  4102  4102 V BluetoothAdapterState: isTurningOff()=false
09-02 15:26:17.004  4102  4102 V BluetoothAdapterState: isTurningOn()=true
,09-02 15:26:17.004  4102  4102 V BluetoothAdapterState: isBleTurningOn()=false
,09-02 15:26:17.004  4102  4102 V BluetoothAdapterState: isBleTurningOff()=false
09-02 15:26:17.004  4102  4102 V BluetoothAdapterState: isTurningOff()=false
09-02 15:26:17.004  4102  4102 V BluetoothAdapterState: isTurningOn()=true
09-02 15:26:17.004  4102  4102 V BluetoothAdapterState: isBleTurningOn()=false
09-02 15:26:17.004  4102  4102 V BluetoothAdapterState: isBleTurningOff()=false
09-02 15:26:17.005  4102  4102 V BluetoothAdapterState: isTurningOff()=false
,09-02 15:26:17.005  4102  4102 V BluetoothAdapterState: isTurningOn()=true
,09-02 15:26:17.005  4102  4102 V BluetoothAdapterState: isBleTurningOn()=false
,09-02 15:26:17.005  4102  4102 V BluetoothAdapterState: isBleTurningOff()=false
09-02 15:26:17.005  4102  4102 V BluetoothAdapterState: isTurningOff()=false
,09-02 15:26:17.006  4102  4102 V BluetoothAdapterState: isTurningOn()=true
,09-02 15:26:17.006  4102  4102 V BluetoothAdapterState: isBleTurningOn()=false
09-02 15:26:17.006  4102  4102 V BluetoothAdapterState: isBleTurningOff()=false
,09-02 15:26:17.006  4102  4102 V BluetoothAdapterState: isTurningOff()=false
,09-02 15:26:17.006  4102  4102 V BluetoothAdapterState: isTurningOn()=true
,09-02 15:26:17.006  4102  4102 V BluetoothAdapterState: isBleTurningOn()=false
,09-02 15:26:17.006  4102  4102 V BluetoothAdapterState: isBleTurningOff()=false
09-02 15:26:17.006  4102  4114 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
09-02 15:26:17.006  4102  4114 D BluetoothAdapterProperties: ScanMode =  20
09-02 15:26:17.007  4102  4114 D BluetoothAdapterProperties: State =  11
,09-02 15:26:17.007  4102  4114 D BluetoothAdapterProperties: Setting state to 12
,09-02 15:26:17.007  4102  4114 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
09-02 15:26:17.009  1365  2059 D BluetoothMap: onBluetoothStateChange: up=true
,09-02 15:26:17.009  4102  4118 D BluetoothAdapterProperties: Scan Mode:21
09-02 15:26:17.009  4102  4118 D BluetoothAdapterProperties: Discoverable Timeout:120
09-02 15:26:17.012  1365  1365 D BluetoothMap: Proxy object connected
09-02 15:26:17.013  1365  1365 D MapProfile: Bluetooth service connected
09-02 15:26:17.013  1365  1365 D BluetoothMap: getConnectedDevices()
09-02 15:26:17.013  4102  4114 I BluetoothAdapterState: Entering OnState
,09-02 15:26:17.013  3788  3788 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-02 15:26:17.013  3788  3788 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 15:26:17.013  3788  3788 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-02 15:26:17.013  3788  3788 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-02 15:26:17.013  3788  3788 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-02 15:26:17.013  3788  3788 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-02 15:26:17.013  3788  3788 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-02 15:26:17.013  3788  3788 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-02 15:26:17.014  3853  3865 D BluetoothMap: onBluetoothStateChange: up=true
09-02 15:26:17.015  1365  1380 D BluetoothPan: onBluetoothStateChange on: true
09-02 15:26:17.015  3788  3788 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-02 15:26:17.017  3853  3867 D BluetoothPan: onBluetoothStateChange on: true
09-02 15:26:17.017  1365  1365 D BluetoothPan: BluetoothPAN Proxy object connected
,09-02 15:26:17.017   872   889 D BluetoothA2dp: onBluetoothStateChange: up=true
09-02 15:26:17.017  1365  1365 D PanProfile: Bluetooth service connected
09-02 15:26:17.017   872   889 D BluetoothHeadset: onBluetoothStateChange: up=true
09-02 15:26:17.017  4102  4102 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
09-02 15:26:17.018  1365  1383 D BluetoothPbap: onBluetoothStateChange: up=true
09-02 15:26:17.018  4102  4102 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
09-02 15:26:17.019  3788  3788 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-02 15:26:17.019  3788  3788 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 15:26:17.019  3788  3788 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-02 15:26:17.019  3788  3788 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-02 15:26:17.019  3788  3788 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-02 15:26:17.019  3788  3788 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-02 15:26:17.019  3788  3788 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-02 15:26:17.019  3788  3788 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-02 15:26:17.019  4102  4102 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-02 15:26:17.021  1939  1953 D BluetoothHeadset: onBluetoothStateChange: up=true
09-02 15:26:17.021  4102  4102 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-02 15:26:17.022  1365  2059 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-02 15:26:17.022  3788  3788 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-02 15:26:17.022  4102  4102 D ObexServerSockets: Succeed to create listening sockets 
09-02 15:26:17.023  4102  4102 D ObexServerSockets0: startAccept()
,09-02 15:26:17.023  4102  4102 D ObexServerSockets0: prepareForNewConnect()
09-02 15:26:17.024  1365  1365 D BluetoothInputDevice: Proxy object connected
09-02 15:26:17.024  1365  1365 D HidProfile: Bluetooth service connected
09-02 15:26:17.024  4102  4102 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
09-02 15:26:17.025  4102  4102 D BluetoothSdpJni: SDP Create record success - handle: 0
09-02 15:26:17.025  3853  3865 D BluetoothPbap: onBluetoothStateChange: up=true
09-02 15:26:17.026   872   872 D BluetoothA2dp: Proxy object connected
,09-02 15:26:17.027  4102  4139 D ObexServerSockets0: Accepting socket connection...
09-02 15:26:17.027  3853  3867 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-02 15:26:17.027   872   889 D BluetoothHeadset: onBluetoothStateChange: up=true
09-02 15:26:17.027  1365  3787 D BluetoothA2dp: onBluetoothStateChange: up=true
09-02 15:26:17.028  4102  4140 D ObexServerSockets0: Accepting socket connection...
,09-02 15:26:17.029  1365  1365 D BluetoothA2dp: Proxy object connected
09-02 15:26:17.029   872   889 D BluetoothHeadset: onBluetoothStateChange: up=true
09-02 15:26:17.030  1365  1380 D BluetoothHeadset: onBluetoothStateChange: up=true
09-02 15:26:17.031   872   872 I Telecom : BluetoothPhoneService: queryPhoneState
09-02 15:26:17.032  4102  4102 D BluetoothMapService: onReceive
09-02 15:26:17.032  4102  4102 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-02 15:26:17.032  4102  4102 D BluetoothMapService: STATE_ON
,09-02 15:26:17.034  3788  3788 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-02 15:26:17.034  3853  3853 D LocalBluetoothProfileManager: Adding local A2DP profile
09-02 15:26:17.035  3788  3788 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-02 15:26:17.039  3853  3853 D LocalBluetoothProfileManager: Adding local HEADSET profile
09-02 15:26:17.046  3853  3853 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-02 15:26:17.053  4102  4102 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,09-02 15:26:17.053  4102  4102 D ObexServerSockets0: prepareForNewConnect()
09-02 15:26:17.053  3853  3853 D BluetoothA2dp: Proxy object connected
09-02 15:26:17.057  1528  1528 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-02 15:26:17.062  3853  3853 D DockEventReceiver: finishStartingService: stopping service
,09-02 15:26:17.069  3853  3853 D BluetoothPbap: Proxy object connected
,09-02 15:26:17.069  1365  1365 D BluetoothPbap: Proxy object connected
09-02 15:26:17.069  1365  1365 D PbapServerProfile: Bluetooth service connected
,09-02 15:26:17.070  3853  3853 D PbapServerProfile: Bluetooth service connected
,09-02 15:26:17.079  4102  4147 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-02 15:26:17.097  4102  4151 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-02 15:26:17.098  4102  4151 I BtOppRfcommListener: Accept thread started.
,09-02 15:26:17.119  1939  2161 D BluetoothHeadset: Proxy object connected
,09-02 15:26:17.120   872   872 D BluetoothHeadset: Proxy object connected
09-02 15:26:17.120   872   872 D BluetoothHeadset: Proxy object connected
09-02 15:26:17.120  1365  1383 D BluetoothHeadset: Proxy object connected
09-02 15:26:17.120  1365  1365 D HeadsetProfile: Bluetooth service connected
,09-02 15:26:17.120   872   872 D BluetoothHeadset: Proxy object connected
,09-02 15:26:17.122  1939  3498 D BluetoothHeadset: Proxy object connected
,09-02 15:26:17.127   872   889 D BluetoothHeadset: Proxy object connected
,09-02 15:26:17.130   872   889 D BluetoothHeadset: Proxy object connected
,09-02 15:26:17.130  1365  3787 D BluetoothHeadset: Proxy object connected
,09-02 15:26:17.131  1365  1365 D HeadsetProfile: Bluetooth service connected
,09-02 15:26:17.142  3853  4141 D BluetoothHeadset: Proxy object connected
,09-02 15:26:17.143  3853  3853 D HeadsetProfile: Bluetooth service connected
,09-02 15:26:18.479  4102  4114 D BluetoothAdapterState: Current state: ON, message: 23
,09-02 15:26:18.480  4102  4114 D BluetoothAdapterProperties: Setting state to 13
09-02 15:26:18.480  4102  4114 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,09-02 15:26:18.482   872  1308 D ConnectivityService: handlePromptUnvalidated 101
09-02 15:26:18.482  4102  4114 D BluetoothAdapterProperties: onBluetoothDisable()
,09-02 15:26:18.489  4102  4114 I BluetoothAdapterState: Entering PendingCommandState
,09-02 15:26:18.495  4102  4102 D BluetoothMapService: onReceive
09-02 15:26:18.496  4102  4102 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-02 15:26:18.496  4102  4102 D BluetoothMapService: STATE_TURNING_OFF
09-02 15:26:18.497  4102  4102 D BluetoothMapService: MAP Service closeService in
,09-02 15:26:18.497  4102  4102 D BluetoothMapMasInstance0: MAP Service shutdown
09-02 15:26:18.499  4102  4102 D ObexServerSockets0: shutdown(block = true)
09-02 15:26:18.499  4102  4118 D BluetoothAdapterProperties: Scan Mode:20
09-02 15:26:18.500  4102  4114 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
09-02 15:26:18.500  4102  4139 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
09-02 15:26:18.501  3788  3788 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-02 15:26:18.501  3788  3788 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-02 15:26:18.501  3788  3788 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 15:26:18.501  3788  3788 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-02 15:26:18.501  3788  3788 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-02 15:26:18.501  3788  3788 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-02 15:26:18.501  3788  3788 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-02 15:26:18.501  3788  3788 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-02 15:26:18.501  3788  3788 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-02 15:26:18.504  3788  3788 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-02 15:26:18.504  3788  3788 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-02 15:26:18.506  4102  4102 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-02 15:26:18.507  4102  4140 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
09-02 15:26:18.507  4102  4126 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
,09-02 15:26:18.508  4102  4102 D ObexServerSockets0: shutdown called from another thread - interrupt().
,09-02 15:26:18.508  4102  4102 I BtOppRfcommListener: stopping Accept Thread
09-02 15:26:18.508  4102  4151 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-02 15:26:18.509  4102  4151 I BtOppRfcommListener: BluetoothSocket listen thread finished
09-02 15:26:18.510  3788  3788 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-02 15:26:18.510  3788  3788 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-02 15:26:18.510  3788  3788 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 15:26:18.510  3788  3788 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-02 15:26:18.510  3788  3788 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-02 15:26:18.510  3788  3788 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-02 15:26:18.510  3788  3788 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-02 15:26:18.510  3788  3788 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-02 15:26:18.510  3788  3788 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-02 15:26:18.510  3788  3788 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-02 15:26:18.510  4102  4102 D HeadsetService: Received stop request...Stopping profile...
09-02 15:26:18.510  3788  3788 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-02 15:26:18.512  3788  3788 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-02 15:26:18.513  3853  3853 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-02 15:26:18.514  3788  3788 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-02 15:26:18.517  1939  2082 D BluetoothHeadset: Proxy object disconnected
09-02 15:26:18.517  3853  4141 D BluetoothHeadset: Proxy object disconnected
09-02 15:26:18.518  4102  4102 D A2dpService: Received stop request...Stopping profile...
09-02 15:26:18.518   872   872 D BluetoothHeadset: Proxy object disconnected
,09-02 15:26:18.518   872   872 D BluetoothHeadset: Proxy object disconnected
09-02 15:26:18.518  4102  4133 D A2dpStateMachine: Exit Disconnected: -1
09-02 15:26:18.519  1365  3787 D BluetoothHeadset: Proxy object disconnected
09-02 15:26:18.519  1365  1365 D HeadsetProfile: Bluetooth service disconnected
09-02 15:26:18.519   872   872 D BluetoothHeadset: Proxy object disconnected
09-02 15:26:18.520   872   872 D BluetoothA2dp: Proxy object disconnected
,09-02 15:26:18.520  1365  1365 D BluetoothA2dp: Proxy object disconnected
09-02 15:26:18.523  4102  4102 D HidService: Received stop request...Stopping profile...
09-02 15:26:18.523  4102  4102 D HidService: Stopping Bluetooth HidService
09-02 15:26:18.524  1365  1365 D BluetoothInputDevice: Proxy object disconnected
09-02 15:26:18.524  1365  1365 D HidProfile: Bluetooth service disconnected
,09-02 15:26:18.525  4102  4102 D HealthService: Received stop request...Stopping profile...
09-02 15:26:18.526  4102  4102 D PanService: Received stop request...Stopping profile...
09-02 15:26:18.526  3853  3853 D DockEventReceiver: finishStartingService: stopping service
09-02 15:26:18.527  1365  1365 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-02 15:26:18.527  1365  1365 D PanProfile: Bluetooth service disconnected
,09-02 15:26:18.528  4102  4102 D BluetoothMapService: Received stop request...Stopping profile...
09-02 15:26:18.528  4102  4102 D BluetoothMapService: stop()
09-02 15:26:18.528  3853  3853 D HeadsetProfile: Bluetooth service disconnected
09-02 15:26:18.528  4102  4102 D BluetoothMapAppObserver: deinitObservers()
,09-02 15:26:18.528  4102  4102 D BluetoothMapAppObserver: removeReceiver()
09-02 15:26:18.529  3853  3853 D BluetoothA2dp: Proxy object disconnected
09-02 15:26:18.530  1365  1365 D BluetoothMap: Proxy object disconnected
09-02 15:26:18.530  1365  1365 D MapProfile: Bluetooth service disconnected
09-02 15:26:18.530  4102  4102 V BluetoothAdapterState: isTurningOff()=true
09-02 15:26:18.530  4102  4102 V BluetoothAdapterState: isTurningOn()=false
09-02 15:26:18.530  4102  4102 V BluetoothAdapterState: isBleTurningOn()=false
,09-02 15:26:18.530  4102  4102 V BluetoothAdapterState: isBleTurningOff()=false
,09-02 15:26:18.530  3853  3853 D BluetoothInputDevice: Proxy object disconnected
09-02 15:26:18.530  3853  3853 D HidProfile: Bluetooth service disconnected
,09-02 15:26:18.532  4102  4102 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
,09-02 15:26:18.532  4102  4124 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,09-02 15:26:18.532  4102  4124 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,09-02 15:26:18.532  4102  4124 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.,
09-02 15:26:18.532  4102  4102 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-02 15:26:18.533  4102  4102 V BluetoothAdapterState: isTurningOff()=true
09-02 15:26:18.533  4102  4102 V BluetoothAdapterState: isTurningOn()=false
09-02 15:26:18.533  4102  4102 V BluetoothAdapterState: isBleTurningOn()=false
09-02 15:26:18.533  3853  3853 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-02 15:26:18.533  4102  4102 V BluetoothAdapterState: isBleTurningOff()=false
09-02 15:26:18.533  3853  3853 D PanProfile: Bluetooth service disconnected
09-02 15:26:18.533  3853  3853 D BluetoothMap: Proxy object disconnected
09-02 15:26:18.533  3853  3853 D MapProfile: Bluetooth service disconnected
09-02 15:26:18.534  4102  4118 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
09-02 15:26:18.534  4102  4118 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
09-02 15:26:18.535  4102  4118 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
09-02 15:26:18.535  4102  4124 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-02 15:26:18.535  4102  4124 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-02 15:26:18.535  4102  4124 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-02 15:26:18.535  4102  4124 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-02 15:26:18.535  4102  4124 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-02 15:26:18.535  4102  4124 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-02 15:26:18.536  4102  4102 V BluetoothAdapterState: isTurningOff()=true
09-02 15:26:18.536  4102  4102 V BluetoothAdapterState: isTurningOn()=false
09-02 15:26:18.536  4102  4102 V BluetoothAdapterState: isBleTurningOn()=false
09-02 15:26:18.536  4102  4102 V BluetoothAdapterState: isBleTurningOff()=false
09-02 15:26:18.536  4102  4102 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
,09-02 15:26:18.538  1528  1528 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-02 15:26:18.538  4102  4118 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
09-02 15:26:18.538  4102  4102 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
09-02 15:26:18.538  4102  4102 V BluetoothAdapterState: isTurningOff()=true
09-02 15:26:18.538  4102  4102 V BluetoothAdapterState: isTurningOn()=false
09-02 15:26:18.539  4102  4102 V BluetoothAdapterState: isBleTurningOn()=false
09-02 15:26:18.539  4102  4102 V BluetoothAdapterState: isBleTurningOff()=false
09-02 15:26:18.541  4102  4102 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
09-02 15:26:18.541  4102  4118 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
09-02 15:26:18.541  4102  4102 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-02 15:26:18.542  4102  4102 V BluetoothAdapterState: isTurningOff()=true
09-02 15:26:18.542  4102  4102 V BluetoothAdapterState: isTurningOn()=false
09-02 15:26:18.542  4102  4102 V BluetoothAdapterState: isBleTurningOn()=false
09-02 15:26:18.542  4102  4102 V BluetoothAdapterState: isBleTurningOff()=false
,09-02 15:26:18.543  4102  4102 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
,09-02 15:26:18.543  4102  4102 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
09-02 15:26:18.544  4102  4102 D BluetoothMapService: MAP Service closeService in
09-02 15:26:18.544  4102  4102 V BluetoothAdapterState: isTurningOff()=true
09-02 15:26:18.544  4102  4102 V BluetoothAdapterState: isTurningOn()=false
09-02 15:26:18.544  4102  4102 V BluetoothAdapterState: isBleTurningOn()=false
09-02 15:26:18.545  4102  4102 V BluetoothAdapterState: isBleTurningOff()=false
09-02 15:26:18.545  4102  4114 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
09-02 15:26:18.545  4102  4114 D BluetoothAdapterProperties: Setting state to 15
09-02 15:26:18.545  4102  4114 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
09-02 15:26:18.546  4102  4114 I BluetoothAdapterState: Entering BleOnState
09-02 15:26:18.546  1365  1383 D BluetoothMap: onBluetoothStateChange: up=false
,09-02 15:26:18.546  4102  4102 D BluetoothMapService: cleanup()
,09-02 15:26:18.546  4102  4102 D BluetoothMapService: MAP Service closeService in
09-02 15:26:18.547  3853  3865 D BluetoothMap: onBluetoothStateChange: up=false
09-02 15:26:18.547  1365  1380 D BluetoothPan: onBluetoothStateChange on: false
09-02 15:26:18.548  1365  1365 D BluetoothPbap: Proxy object disconnected
09-02 15:26:18.548  1365  1365 D PbapServerProfile: Bluetooth service disconnected
09-02 15:26:18.548  3853  3867 D BluetoothA2dp: onBluetoothStateChange: up=false
,09-02 15:26:18.549  3853  3853 D BluetoothPbap: Proxy object disconnected
,09-02 15:26:18.549  3853  3853 D PbapServerProfile: Bluetooth service disconnected
09-02 15:26:18.550  3853  4141 D BluetoothPan: onBluetoothStateChange on: false
09-02 15:26:18.551   872   889 D BluetoothA2dp: onBluetoothStateChange: up=false
09-02 15:26:18.551   872   889 D BluetoothHeadset: onBluetoothStateChange: up=false
,09-02 15:26:18.551  3853  3865 D BluetoothHeadset: onBluetoothStateChange: up=false
09-02 15:26:18.552  1365  3787 D BluetoothPbap: onBluetoothStateChange: up=false
09-02 15:26:18.554  1939  1952 D BluetoothHeadset: onBluetoothStateChange: up=false
09-02 15:26:18.554  1365  1383 D BluetoothInputDevice: onBluetoothStateChange: up=false
,09-02 15:26:18.555  3853  3867 D BluetoothPbap: onBluetoothStateChange: up=false
09-02 15:26:18.555  3853  4141 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-02 15:26:18.556   872   889 D BluetoothHeadset: onBluetoothStateChange: up=false
,09-02 15:26:18.556  1365  2059 D BluetoothA2dp: onBluetoothStateChange: up=false
,09-02 15:26:18.556   872   889 D BluetoothHeadset: onBluetoothStateChange: up=false
09-02 15:26:18.557  1365  1380 D BluetoothHeadset: onBluetoothStateChange: up=false,
09-02 15:26:18.557  4102  4114 D BluetoothAdapterState: Current state: BLE ON, message: 20
,09-02 15:26:18.557  4102  4114 D BluetoothAdapterProperties: Setting state to 16
,09-02 15:26:18.557  4102  4114 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
,09-02 15:26:18.558  4102  4114 D BluetoothAdapterProperties: onBleDisable
09-02 15:26:18.558  4102  4114 I BluetoothAdapterState: Entering PendingCommandState
09-02 15:26:18.558  4102  4115 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
09-02 15:26:18.560  4102  4124 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
09-02 15:26:18.560  4102  4124 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-02 15:26:18.562  3788  3788 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-02 15:26:18.562  4102  4118 D BluetoothAdapterProperties: Scan Mode:20
09-02 15:26:18.563  3788  3788 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-02 15:26:18.564  3853  3853 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-02 15:26:18.564  3788  3788 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-02 15:26:18.565  3788  3788 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-02 15:26:18.568  1528  1528 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-02 15:26:18.575  3853  3853 D DockEventReceiver: finishStartingService: stopping service
,09-02 15:26:18.760  4102  4118 I bt_hci  : shut_down
,09-02 15:26:18.760  4102  4122 D bt_hwcfg: hw_epilog_process
,09-02 15:26:18.774  4102  4122 I bt_vendor: low_power_mode_cb
,09-02 15:26:18.796  4102  4122 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,09-02 15:26:18.796  4102  4122 I bt_vendor: epilog_cb
,09-02 15:26:18.796  4102  4122 I bt_hci  : epilog_finished_callback
,09-02 15:26:18.804  4102  4118 I bt_hci_h4: hal_close
,09-02 15:26:18.805  4102  4118 I bt_userial_vendor: device fd = 51 close
,09-02 15:26:18.928  4102  4115 D bt_stack_manager: event_shut_down_stack finished.
,09-02 15:26:18.929  4102  4114 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,09-02 15:26:18.935  4102  4114 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
09-02 15:26:18.935  4102  4102 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-02 15:26:18.937  4102  4102 D BtGatt.GattService: Received stop request...Stopping profile...
09-02 15:26:18.937  4102  4102 D BtGatt.GattService: stop()
09-02 15:26:18.938  4102  4102 D BtGatt.AdvertiseManager: advertise clients cleared
,09-02 15:26:18.943  4102  4102 V BluetoothAdapterState: isTurningOff()=false
09-02 15:26:18.943  4102  4102 V BluetoothAdapterState: isTurningOn()=false
,09-02 15:26:18.943  4102  4102 V BluetoothAdapterState: isBleTurningOn()=false
,09-02 15:26:18.944  4102  4102 V BluetoothAdapterState: isBleTurningOff()=true
09-02 15:26:18.944  4102  4114 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
,09-02 15:26:18.945  4102  4114 D BluetoothAdapterProperties: Setting state to 10
,09-02 15:26:18.946  4102  4114 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
,09-02 15:26:18.947  4102  4114 I BluetoothAdapterState: Entering OffState
,09-02 15:26:18.950   872   889 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,09-02 15:26:18.980  4102  4102 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,09-02 15:26:18.981  4102  4102 W BluetoothSdpJni: Cleaning up Bluetooth Health object
,09-02 15:26:18.982  4102  4115 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,09-02 15:26:18.990  4102  4115 D bt_stack_manager: event_clean_up_stack finished.
09-02 15:26:18.990  4102  4102 I BluetoothServiceJni: cleanupNative: return from cleanup
,09-02 15:26:18.992  4102  4102 I art     : System.exit called, status: 0
09-02 15:26:18.992  4102  4102 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,09-02 15:26:19.050   872  1944 I ActivityManager: Process com.android.bluetooth (pid 4102) has died
,09-02 15:26:21.477  3788  3836 D io.jxcore.node.ConnectivityMonitor: stop
,09-02 15:26:21.477  3788  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-02 15:26:22.675   872   892 I PowerManagerService: Going to sleep due to screen timeout (uid 1000)...
,09-02 15:26:22.685  1871  1871 I Keyboard.Facilitator: onFinishInput()
,09-02 15:26:22.694   872   892 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
09-02 15:26:22.694   872   892 I Adreno  : Build Date                       : 10/20/15
09-02 15:26:22.694   872   892 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
09-02 15:26:22.694   872   892 I Adreno  : Local Branch                     : M14
09-02 15:26:22.694   872   892 I Adreno  : Remote Branch                    : 
09-02 15:26:22.694   872   892 I Adreno  : Remote Branch                    : 
09-02 15:26:22.694   872   892 I Adreno  : Reconstruct Branch               : 
,09-02 15:26:22.732   282  1298 D PermissionCache: checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (186 us)
,09-02 15:26:23.411  3788  3788 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,09-02 15:26:23.411  3788  3788 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,09-02 15:26:23.458   872   892 V KeyguardServiceDelegate: onScreenTurnedOff()
,09-02 15:26:23.459  3788  3788 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@ec26752 Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@929260c, 16908290=android.view.AbsSavedState$1@929260c}, android:focusedViewId=100}]}]
09-02 15:26:23.459  3788  3788 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
09-02 15:26:23.460  3788  3788 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
09-02 15:26:23.460  3788  3788 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
,09-02 15:26:23.464   872   892 E libEGL  : call to OpenGL ES API with no current context (logged once per thread)
,09-02 15:26:23.467   282   282 D SurfaceFlinger: Set power mode=0, type=0 flinger=0xb6aa4000
,09-02 15:26:23.467   872   890 I DisplayManagerService: Display device changed state: "Built-in Screen", OFF
,09-02 15:26:23.467   282   282 D qdhwcomposer: hwc_setPowerMode: Setting mode 0 on display: 0
,09-02 15:26:23.726   282   337 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0
,09-02 15:26:23.729   282   282 D qdhwcomposer: hwc_setPowerMode: Done setting mode 0 on display 0
09-02 15:26:23.735   872  1334 D SurfaceControl: Excessive delay in setPowerMode(): 268ms
,09-02 15:26:23.738   872   892 I DreamManagerService: Entering dreamland.
09-02 15:26:23.739   872   892 I PowerManagerService: Dozing...
09-02 15:26:23.741   872   887 I DreamController: Starting dream: name=ComponentInfo{com.android.systemui/com.android.systemui.doze.DozeService}, isTest=false, canDoze=true, userId=0
,09-02 15:26:23.793   376   376 D audio_hw_primary: adev_set_parameters: enter: screen_state=on
,09-02 15:26:23.793   376   376 D mot_vr_audio_hw: adev_set_parameters: screen_state=on
,09-02 15:26:23.800   872  1306 D WifiConfigStore: Retrieve network priorities after PNO.
,09-02 15:26:23.812   872  1306 E native  : do suspend false
,09-02 15:26:23.819  1923  4162 D NfcService: Discovery configuration equal, not updating.
,09-02 15:26:23.843   872  1306 D WifiConfigStore: Retrieve network priorities after PNO.
,09-02 15:26:23.847   872  1306 E native  : do suspend true
,09-02 15:26:23.933   376  1315 D audio_hw_primary: adev_set_parameters: enter: screen_state=off
,09-02 15:26:23.934   376  1315 D mot_vr_audio_hw: adev_set_parameters: screen_state=off
,09-02 15:26:24.485  3788  3836 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-02 15:26:24.485  3788  3836 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@9650b55 added. We now have 6 listener(s)
09-02 15:26:24.486  3788  3836 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-02 15:26:24.489  3788  3836 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-02 15:26:24.490  3788  3836 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@237e96a added. We now have 7 listener(s)
09-02 15:26:24.490  3788  3836 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-02 15:26:24.492  3788  3836 I System.out: IsBluetoothEnabled
,09-02 15:26:24.503  3788  3836 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-02 15:26:24.553   872   889 I ActivityManager: Start proc 4168:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,09-02 15:26:24.712  4168  4168 D AdapterServiceConfig: Adding HeadsetService
,09-02 15:26:24.713  4168  4168 D AdapterServiceConfig: Adding A2dpService
,09-02 15:26:24.713  4168  4168 D AdapterServiceConfig: Adding HidService
,09-02 15:26:24.713  4168  4168 D AdapterServiceConfig: Adding HealthService
09-02 15:26:24.713  4168  4168 D AdapterServiceConfig: Adding PanService
09-02 15:26:24.713  4168  4168 D AdapterServiceConfig: Adding GattService
09-02 15:26:24.714  4168  4168 D AdapterServiceConfig: Adding BluetoothMapService
,09-02 15:26:24.729   872   889 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@9650b55:true
,09-02 15:26:24.729  4168  4168 D BluetoothAdapterState: make() - Creating AdapterState
,09-02 15:26:24.734  4168  4168 I bt_bluedroid: init
,09-02 15:26:24.735  4168  4180 I BluetoothAdapterState: Entering OffState
,09-02 15:26:24.742  4168  4181 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,09-02 15:26:24.742  4168  4181 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
,09-02 15:26:24.742  4168  4181 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,09-02 15:26:24.744  4168  4181 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,09-02 15:26:24.746  4168  4168 I bt_bluedroid: get_profile_interface socket
,09-02 15:26:24.748  4168  4168 I bt_bluedroid: get_profile_interface sdp
,09-02 15:26:24.752  4168  4179 I bt_bluedroid: config_hci_snoop_log
,09-02 15:26:24.756  4168  4184 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,09-02 15:26:24.756   872   889 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,09-02 15:26:24.758  4168  4184 D BluetoothAdapterProperties: Name is: Nexus 6
,09-02 15:26:24.764  4168  4180 D BluetoothAdapterState: Current state: OFF, message: 0
,09-02 15:26:24.764  4168  4180 D BluetoothAdapterProperties: Setting state to 14
09-02 15:26:24.765  4168  4180 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,09-02 15:26:24.769  4168  4180 D BluetoothBondStateMachine: make
,09-02 15:26:24.772  4168  4185 I BluetoothBondStateMachine: StableState(): Entering Off State
,09-02 15:26:24.781  4168  4168 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,09-02 15:26:24.781  4168  4180 I BluetoothAdapterState: Entering PendingCommandState
,09-02 15:26:24.786  4168  4168 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@12ec4c6
,09-02 15:26:24.787  4168  4168 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-02 15:26:24.788  4168  4168 D BtGatt.GattService: Received start request. Starting profile...
09-02 15:26:24.788  4168  4168 D BtGatt.GattService: start()
09-02 15:26:24.788  4168  4168 I bt_bluedroid: get_profile_interface gatt
,09-02 15:26:24.789  4168  4168 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@12ec4c6
09-02 15:26:24.790  4168  4168 D BtGatt.AdvertiseManager: advertise manager created
,09-02 15:26:24.801  4168  4168 V BluetoothAdapterState: isTurningOff()=false
,09-02 15:26:24.801  4168  4168 V BluetoothAdapterState: isTurningOn()=false
09-02 15:26:24.801  4168  4168 V BluetoothAdapterState: isBleTurningOn()=true
,09-02 15:26:24.801  4168  4168 V BluetoothAdapterState: isBleTurningOff()=false
09-02 15:26:24.802  4168  4180 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,09-02 15:26:24.803  4168  4180 I bt_bluedroid: enable
,09-02 15:26:24.803  4168  4181 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,09-02 15:26:24.804  4168  4181 I bt_hci  : start_up
,09-02 15:26:24.819  4168  4181 I bt_vendor: alloc value 0xb39b9189
,09-02 15:26:24.820  4168  4181 I bt_vendor: init
09-02 15:26:24.820  4168  4181 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
09-02 15:26:24.820  4168  4181 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,09-02 15:26:24.928  4168  4181 D bt_hci  : start_up starting async portion
,09-02 15:26:24.929  4168  4188 I bt_hci  : event_finish_startup
,09-02 15:26:24.929  4168  4188 I bt_hci_h4: hal_open
09-02 15:26:24.929  4168  4188 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,09-02 15:26:24.938  4168  4188 I bt_userial_vendor: device fd = 51 open
,09-02 15:26:24.970  4168  4188 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-02 15:26:25.001  4168  4188 D bt_hwcfg: Chipset BCM4354A2
,09-02 15:26:25.001  4168  4188 D bt_hwcfg: Target name = [BCM4354A2]
,09-02 15:26:25.002  4168  4188 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,09-02 15:26:25.657  4168  4188 I bt_hwcfg: bt vendor lib: set UART baud 115200
,09-02 15:26:25.658  4168  4188 D bt_hwcfg: Settlement delay -- 100 ms
,09-02 15:26:25.658  4168  4188 I bt_hwcfg: Setting fw settlement delay to 100 
,09-02 15:26:25.775  4168  4188 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-02 15:26:25.776  4168  4188 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,09-02 15:26:25.806  4168  4188 I bt_hwcfg: vendor lib fwcfg completed
,09-02 15:26:25.807  4168  4188 I bt_vendor: firmware callback
,09-02 15:26:25.807  4168  4188 I bt_hci  : firmware_config_callback
,09-02 15:26:25.818  4168  4190 I bt_btu  : btu_task pending for preload complete event
,09-02 15:26:25.818  4168  4190 I bt_btu_task: Bluetooth chip preload is complete
,09-02 15:26:25.818  4168  4190 I bt_btu  : btu_task received preload complete event
,09-02 15:26:25.827  4168  4190 I         : BTE_InitTraceLevels -- TRC_HCI
,09-02 15:26:25.828  4168  4190 I         : BTE_InitTraceLevels -- TRC_L2CAP
09-02 15:26:25.828  4168  4190 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,09-02 15:26:25.828  4168  4190 I         : BTE_InitTraceLevels -- TRC_AVDT
,09-02 15:26:25.829  4168  4190 I         : BTE_InitTraceLevels -- TRC_AVRC
09-02 15:26:25.829  4168  4190 I         : BTE_InitTraceLevels -- TRC_A2D
09-02 15:26:25.829  4168  4190 I         : BTE_InitTraceLevels -- TRC_BNEP
09-02 15:26:25.830  4168  4190 I         : BTE_InitTraceLevels -- TRC_BTM
,09-02 15:26:25.830  4168  4190 I         : BTE_InitTraceLevels -- TRC_GAP
09-02 15:26:25.830  4168  4190 I         : BTE_InitTraceLevels -- TRC_PAN
09-02 15:26:25.830  4168  4190 I         : BTE_InitTraceLevels -- TRC_SDP
09-02 15:26:25.831  4168  4190 I         : BTE_InitTraceLevels -- TRC_GATT
09-02 15:26:25.831  4168  4190 I         : BTE_InitTraceLevels -- TRC_SMP
09-02 15:26:25.831  4168  4190 I         : BTE_InitTraceLevels -- TRC_BTAPP
09-02 15:26:25.831  4168  4190 I         : BTE_InitTraceLevels -- TRC_BTIF
,09-02 15:26:25.975  4168  4190 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb3936d9d
,09-02 15:26:25.976  4168  4190 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb3936d9d 
,09-02 15:26:25.985  4168  4184 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,09-02 15:26:25.987  4168  4184 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
09-02 15:26:25.987  4168  4184 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,09-02 15:26:25.990  4168  4184 D BluetoothAdapterProperties: Name is: Nexus 6
,09-02 15:26:25.994  4168  4184 D BluetoothAdapterProperties: Scan Mode:20
,09-02 15:26:25.994  4168  4184 D BluetoothAdapterProperties: Discoverable Timeout:120
,09-02 15:26:25.995  4168  4184 D bt_hci  : do_postload posting postload work item
,09-02 15:26:25.996  4168  4188 I bt_hci  : event_postload
,09-02 15:26:25.996  4168  4188 I bt_vendor: sco_config_cb
,09-02 15:26:25.996  4168  4188 I bt_hci  : sco_config_callback postload finished.
,09-02 15:26:25.997  3788  3788 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-02 15:26:25.998  4168  4184 D bt_bte_conf: Device ID record 1 : primary
,09-02 15:26:25.998  4168  4184 D bt_bte_conf:   vendorId            = 000f
,09-02 15:26:25.998  4168  4184 D bt_bte_conf:   vendorIdSource      = 0001
,09-02 15:26:25.999  4168  4184 D bt_bte_conf:   product             = 1200
,09-02 15:26:25.999  4168  4184 D bt_bte_conf:   version             = 1436
09-02 15:26:25.999  4168  4184 D bt_bte_conf:   clientExecutableURL = 
09-02 15:26:25.999  4168  4184 D bt_bte_conf:   serviceDescription  = 
09-02 15:26:26.000  4168  4184 D bt_bte_conf:   documentationURL    = 
,09-02 15:26:26.000  4168  4184 D bt_bte_conf: bte_load_did_conf no section named DID2.
09-02 15:26:26.000  4168  4181 D bt_stack_manager: event_start_up_stack finished
09-02 15:26:26.002  4168  4180 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
09-02 15:26:26.002  4168  4180 D BluetoothAdapterProperties: Setting state to 15
09-02 15:26:26.004  4168  4180 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
09-02 15:26:26.008  4168  4180 I BluetoothAdapterState: Entering BleOnState
09-02 15:26:26.008  4168  4188 I bt_vendor: low_power_mode_cb
09-02 15:26:26.012  4168  4180 D BluetoothAdapterState: Current state: BLE ON, message: 1
,09-02 15:26:26.012  4168  4180 D BluetoothAdapterProperties: Setting state to 11
09-02 15:26:26.012  4168  4180 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
09-02 15:26:26.019  4168  4168 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@12ec4c6
09-02 15:26:26.024  4168  4168 D HeadsetService: Received start request. Starting profile...
,09-02 15:26:26.031  4168  4168 I BluetoothHeadsetServiceJni: classInitNative: succeeds
09-02 15:26:26.031  4168  4168 D HeadsetStateMachine: make
,09-02 15:26:26.033  3788  3788 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-02 15:26:26.037  4168  4180 I BluetoothAdapterState: Entering PendingCommandState
,09-02 15:26:26.039  4168  4168 D HeadsetStateMachine: max_hf_connections = 1
,09-02 15:26:26.039  4168  4168 I bt_bluedroid: get_profile_interface handsfree
09-02 15:26:26.039  4168  4184 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
,09-02 15:26:26.039  4168  4184 E bt_btif : btif_hf_upstreams_evt: Invalid index 1027
,09-02 15:26:26.044  4168  4168 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@12ec4c6
,09-02 15:26:26.045  4168  4168 D A2dpService: Received start request. Starting profile...
,09-02 15:26:26.045  4168  4168 I BluetoothAvrcpServiceJni: classInitNative: succeeds
09-02 15:26:26.046  4168  4168 I bt_bluedroid: get_profile_interface avrcp
,09-02 15:26:26.053  4168  4168 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,09-02 15:26:26.053  4168  4168 I BluetoothA2dpServiceJni: classInitNative: succeeds
09-02 15:26:26.053  4168  4168 D A2dpStateMachine: make
,09-02 15:26:26.054  4168  4168 I bt_bluedroid: get_profile_interface a2dp
,09-02 15:26:26.055  4168  4184 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
09-02 15:26:26.056  4168  4198 D A2dpStateMachine: Enter Disconnected: -2
09-02 15:26:26.056  4168  4168 I BluetoothHidServiceJni: classInitNative: succeeds
09-02 15:26:26.057  4168  4168 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@12ec4c6
09-02 15:26:26.057  4168  4168 D HidService: Received start request. Starting profile...
09-02 15:26:26.057  4168  4168 I bt_bluedroid: get_profile_interface hidhost
09-02 15:26:26.058  4168  4168 D HidService: setHidService(): set to: null
09-02 15:26:26.058  4168  4184 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb39183e5
,09-02 15:26:26.058  4168  4184 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
09-02 15:26:26.059  4168  4168 I BluetoothHealthServiceJni: classInitNative: succeeds
,09-02 15:26:26.059  4168  4168 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@12ec4c6
,09-02 15:26:26.060  4168  4168 D HealthService: Received start request. Starting profile...
,09-02 15:26:26.062  4168  4168 I bt_bluedroid: get_profile_interface health
,09-02 15:26:26.062  4168  4168 I BluetoothPanServiceJni: classInitNative(L105): succeeds
09-02 15:26:26.063  4168  4168 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@12ec4c6
09-02 15:26:26.063  4168  4168 D PanService: Received start request. Starting profile...
09-02 15:26:26.063  4168  4168 D BluetoothPanServiceJni: initializeNative(L110): pan
09-02 15:26:26.064  4168  4168 I bt_bluedroid: get_profile_interface pan
09-02 15:26:26.064  4168  4184 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,09-02 15:26:26.067  4168  4168 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@12ec4c6
09-02 15:26:26.067  4168  4168 D BluetoothMapService: Received start request. Starting profile...
09-02 15:26:26.067  4168  4168 D BluetoothMapService: start()
,09-02 15:26:26.069  4168  4168 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
09-02 15:26:26.070  4168  4168 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
09-02 15:26:26.070  4168  4168 D BluetoothMapAppObserver: createReceiver()
,09-02 15:26:26.071  4168  4168 D BluetoothMapAppObserver: initObservers()
09-02 15:26:26.071  4168  4168 D BluetoothMapAppObserver: getEnabledAccountItems()
,09-02 15:26:26.079  1528  1528 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-02 15:26:26.080  4168  4168 V BluetoothAdapterState: isTurningOff()=false
09-02 15:26:26.080  4168  4168 V BluetoothAdapterState: isTurningOn()=true
09-02 15:26:26.080  4168  4168 V BluetoothAdapterState: isBleTurningOn()=false
09-02 15:26:26.080  4168  4168 V BluetoothAdapterState: isBleTurningOff()=false
09-02 15:26:26.080  4168  4196 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,09-02 15:26:26.082  4168  4168 V BluetoothAdapterState: isTurningOff()=false
09-02 15:26:26.082  4168  4168 V BluetoothAdapterState: isTurningOn()=true
09-02 15:26:26.082  4168  4168 V BluetoothAdapterState: isBleTurningOn()=false
09-02 15:26:26.082  4168  4168 V BluetoothAdapterState: isBleTurningOff()=false
,09-02 15:26:26.082  4168  4168 V BluetoothAdapterState: isTurningOff()=false
09-02 15:26:26.082  4168  4168 V BluetoothAdapterState: isTurningOn()=true
09-02 15:26:26.082  4168  4168 V BluetoothAdapterState: isBleTurningOn()=false
09-02 15:26:26.082  4168  4168 V BluetoothAdapterState: isBleTurningOff()=false
09-02 15:26:26.082  4168  4168 V BluetoothAdapterState: isTurningOff()=false
09-02 15:26:26.082  4168  4168 V BluetoothAdapterState: isTurningOn()=true
09-02 15:26:26.082  4168  4168 V BluetoothAdapterState: isBleTurningOn()=false
09-02 15:26:26.082  4168  4168 V BluetoothAdapterState: isBleTurningOff()=false
,09-02 15:26:26.083  4168  4168 V BluetoothAdapterState: isTurningOff()=false
09-02 15:26:26.083  4168  4168 V BluetoothAdapterState: isTurningOn()=true
09-02 15:26:26.083  4168  4168 V BluetoothAdapterState: isBleTurningOn()=false
,09-02 15:26:26.083  4168  4168 V BluetoothAdapterState: isBleTurningOff()=false
09-02 15:26:26.083  4168  4168 V BluetoothAdapterState: isTurningOff()=false
,09-02 15:26:26.083  4168  4168 V BluetoothAdapterState: isTurningOn()=true
,09-02 15:26:26.083  4168  4168 V BluetoothAdapterState: isBleTurningOn()=false
09-02 15:26:26.083  4168  4168 V BluetoothAdapterState: isBleTurningOff()=false
,09-02 15:26:26.083  4168  4180 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
09-02 15:26:26.083  4168  4180 D BluetoothAdapterProperties: ScanMode =  20
09-02 15:26:26.084  4168  4180 D BluetoothAdapterProperties: State =  11
09-02 15:26:26.084  4168  4180 D BluetoothAdapterProperties: Setting state to 12
09-02 15:26:26.084  4168  4180 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
09-02 15:26:26.085  4168  4184 D BluetoothAdapterProperties: Scan Mode:21
09-02 15:26:26.085  4168  4184 D BluetoothAdapterProperties: Discoverable Timeout:120
09-02 15:26:26.085  1365  1380 D BluetoothMap: onBluetoothStateChange: up=true
,09-02 15:26:26.085  4168  4180 I BluetoothAdapterState: Entering OnState
,09-02 15:26:26.088  3853  3865 D BluetoothMap: onBluetoothStateChange: up=true
,09-02 15:26:26.089  3788  3788 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-02 15:26:26.089  3788  3788 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 15:26:26.089  3788  3788 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-02 15:26:26.089  3788  3788 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-02 15:26:26.089  3788  3788 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-02 15:26:26.089  3788  3788 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-02 15:26:26.089  3788  3788 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-02 15:26:26.089  3788  3788 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-02 15:26:26.090  1365  1365 D BluetoothMap: Proxy object connected
09-02 15:26:26.090  1365  1365 D MapProfile: Bluetooth service connected
,09-02 15:26:26.090  1365  1365 D BluetoothMap: getConnectedDevices()
,09-02 15:26:26.091  1365  1383 D BluetoothPan: onBluetoothStateChange on: true
,09-02 15:26:26.091  3788  3788 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-02 15:26:26.092  3853  3867 D BluetoothA2dp: onBluetoothStateChange: up=true
09-02 15:26:26.093  1365  1365 D BluetoothPan: BluetoothPAN Proxy object connected
09-02 15:26:26.093  1365  1365 D PanProfile: Bluetooth service connected
,09-02 15:26:26.094  3853  4141 D BluetoothPan: onBluetoothStateChange on: true
,09-02 15:26:26.095   872   889 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-02 15:26:26.096   872   889 D BluetoothHeadset: onBluetoothStateChange: up=true
09-02 15:26:26.096   872   872 D BluetoothA2dp: Proxy object connected
09-02 15:26:26.096  3853  3867 D BluetoothHeadset: onBluetoothStateChange: up=true
09-02 15:26:26.096  1365  1380 D BluetoothPbap: onBluetoothStateChange: up=true
,09-02 15:26:26.096  3853  3853 D BluetoothMap: Proxy object connected
09-02 15:26:26.097  3853  3853 D MapProfile: Bluetooth service connected
09-02 15:26:26.097  3853  3853 D BluetoothMap: getConnectedDevices()
,09-02 15:26:26.098  4168  4168 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,09-02 15:26:26.099  4168  4168 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
09-02 15:26:26.100  3853  3853 D BluetoothA2dp: Proxy object connected
,09-02 15:26:26.100  1939  2161 D BluetoothHeadset: onBluetoothStateChange: up=true
09-02 15:26:26.100  4168  4168 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-02 15:26:26.101  1365  3787 D BluetoothInputDevice: onBluetoothStateChange: up=true
,09-02 15:26:26.101  3853  3853 D BluetoothPan: BluetoothPAN Proxy object connected
09-02 15:26:26.101  3853  3853 D PanProfile: Bluetooth service connected
,09-02 15:26:26.102  4168  4168 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-02 15:26:26.103  3853  3865 D BluetoothPbap: onBluetoothStateChange: up=true
09-02 15:26:26.103  4168  4168 D ObexServerSockets: Succeed to create listening sockets 
09-02 15:26:26.103  4168  4168 D ObexServerSockets0: startAccept()
,09-02 15:26:26.104  4168  4168 D ObexServerSockets0: prepareForNewConnect()
,09-02 15:26:26.104  3853  4141 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-02 15:26:26.105  4168  4168 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
09-02 15:26:26.106  4168  4168 D BluetoothSdpJni: SDP Create record success - handle: 0
09-02 15:26:26.106   872   889 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-02 15:26:26.107  4168  4205 D ObexServerSockets0: Accepting socket connection...
09-02 15:26:26.107  1365  1383 D BluetoothA2dp: onBluetoothStateChange: up=true
09-02 15:26:26.107  4168  4206 D ObexServerSockets0: Accepting socket connection...
,09-02 15:26:26.107  1365  1365 D BluetoothInputDevice: Proxy object connected
09-02 15:26:26.107  1365  1365 D HidProfile: Bluetooth service connected
,09-02 15:26:26.109   872   889 D BluetoothHeadset: onBluetoothStateChange: up=true
09-02 15:26:26.109  1365  2059 D BluetoothHeadset: onBluetoothStateChange: up=true
09-02 15:26:26.109  3853  3853 D BluetoothInputDevice: Proxy object connected
09-02 15:26:26.109  1365  1365 D BluetoothA2dp: Proxy object connected
,09-02 15:26:26.109  3853  3853 D HidProfile: Bluetooth service connected
09-02 15:26:26.110   872   872 I Telecom : BluetoothPhoneService: queryPhoneState
09-02 15:26:26.113  4168  4168 D BluetoothMapService: onReceive
09-02 15:26:26.113  4168  4168 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-02 15:26:26.113  4168  4168 D BluetoothMapService: STATE_ON
,09-02 15:26:26.113  3788  3788 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-02 15:26:26.119  3853  3853 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-02 15:26:26.123  3853  3853 D DockEventReceiver: finishStartingService: stopping service
,09-02 15:26:26.126  1528  1528 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-02 15:26:26.133  3853  3853 D BluetoothPbap: Proxy object connected
,09-02 15:26:26.133  3853  3853 D PbapServerProfile: Bluetooth service connected
,09-02 15:26:26.138  1365  1365 D BluetoothPbap: Proxy object connected
,09-02 15:26:26.138  4168  4168 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
09-02 15:26:26.138  1365  1365 D PbapServerProfile: Bluetooth service connected
,09-02 15:26:26.138  4168  4168 D ObexServerSockets0: prepareForNewConnect()
09-02 15:26:26.139  4168  4212 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-02 15:26:26.155  4168  4216 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-02 15:26:26.157  4168  4216 I BtOppRfcommListener: Accept thread started.
,09-02 15:26:26.198  1939  3498 D BluetoothHeadset: Proxy object connected
,09-02 15:26:26.199  3853  4141 D BluetoothHeadset: Proxy object connected
,09-02 15:26:26.199   872   872 D BluetoothHeadset: Proxy object connected
09-02 15:26:26.199  3853  3853 D HeadsetProfile: Bluetooth service connected
,09-02 15:26:26.199   872   872 D BluetoothHeadset: Proxy object connected
09-02 15:26:26.200  1365  2059 D BluetoothHeadset: Proxy object connected
,09-02 15:26:26.201   872   872 D BluetoothHeadset: Proxy object connected
,09-02 15:26:26.201  1939  2082 D BluetoothHeadset: Proxy object connected
09-02 15:26:26.201  1365  1365 D HeadsetProfile: Bluetooth service connected
,09-02 15:26:26.207   872   889 D BluetoothHeadset: Proxy object connected
,09-02 15:26:26.209   872   889 D BluetoothHeadset: Proxy object connected
,09-02 15:26:26.210  1365  1380 D BluetoothHeadset: Proxy object connected
,09-02 15:26:26.211  1365  1365 D HeadsetProfile: Bluetooth service connected
,09-02 15:26:26.522  3788  3836 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-02 15:26:26.522  3788  3836 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 15:26:26.522  3788  3836 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-02 15:26:26.522  3788  3836 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-02 15:26:26.522  3788  3836 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-02 15:26:26.522  3788  3836 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-02 15:26:26.522  3788  3836 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-02 15:26:26.522  3788  3836 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-02 15:26:26.528  3788  3836 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-02 15:26:26.531  3788  3836 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-02 15:26:26.531  3788  3836 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@ce8de5b added. We now have 8 listener(s)
09-02 15:26:26.532  3788  3836 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-02 15:26:26.535   872  1692 D WifiService: setWifiEnabled: false pid=3788, uid=10000
,09-02 15:26:26.536   872  1692 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-02 15:26:26.544  3788  3836 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-02 15:26:26.545   872   883 D WifiService: setWifiEnabled: true pid=3788, uid=10000
,09-02 15:26:26.545   872   883 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-02 15:26:26.550   872  1306 D WifiConfigStore: Loading config and enabling all networks 
,09-02 15:26:26.564   872  1306 D WifiConfigStore: loaded 0 passpoint configs
,09-02 15:26:26.566   872  1306 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,09-02 15:26:26.569   872  1306 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
09-02 15:26:26.571   872  1306 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
09-02 15:26:26.572   872  1306 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
09-02 15:26:26.572   872  1306 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
,09-02 15:26:26.573   872  1306 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,09-02 15:26:26.575  3788  3836 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-02 15:26:26.575  3788  3836 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 15:26:26.575  3788  3836 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-02 15:26:26.575  3788  3836 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-02 15:26:26.575  3788  3836 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-02 15:26:26.575  3788  3836 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-02 15:26:26.575  3788  3836 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-02 15:26:26.575  3788  3836 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-02 15:26:26.576  3788  3788 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-02 15:26:26.576  3788  3788 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 15:26:26.576  3788  3788 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-02 15:26:26.576  3788  3788 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-02 15:26:26.576  3788  3788 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-02 15:26:26.576  3788  3788 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-02 15:26:26.576  3788  3788 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-02 15:26:26.576  3788  3788 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-02 15:26:26.577  3788  3836 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-02 15:26:26.581  3788  3788 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-02 15:26:26.581  3788  3836 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
09-02 15:26:26.582  3788  3836 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,09-02 15:26:26.585  3788  3836 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@ec26752 Bundle[{}]
,09-02 15:26:26.586  3788  3836 I io.jxcore.node.LifeCycleMonitor: start: OK
,09-02 15:26:26.586  3788  3836 I io.jxcore.node.LifeCycleMonitor: stop: OK
09-02 15:26:26.587  3788  3836 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,09-02 15:26:26.588  3788  3836 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,09-02 15:26:26.589  3788  3836 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
,09-02 15:26:26.590  3788  3836 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,09-02 15:26:26.591   372   870 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,09-02 15:26:26.591   872  1306 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.05 rxSuccessRate=0.06 delta 1000 -> 1000
09-02 15:26:26.591   872  1306 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
09-02 15:26:26.592   372   870 D CommandListener: Setting iface cfg
09-02 15:26:26.593   872  1305 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '159 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 159 Failed to set address (No such device)'
09-02 15:26:26.593   872  1305 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,09-02 15:26:26.595  3788  3836 I System.out: Running OutgoingSocketThread
,09-02 15:26:26.595  3788  4221 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 415)
09-02 15:26:26.596  3788  4221 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 44532
,09-02 15:26:26.596  3788  4221 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,09-02 15:26:26.601   872  1306 E native  : do suspend true
,09-02 15:26:26.607   872  1305 D WifiNative-HAL: p2pGetDeviceAddress
,09-02 15:26:26.612   872  1306 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
,09-02 15:26:26.612   872  1305 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
09-02 15:26:26.612   872  1306 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-02 15:26:26.620   872  1306 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,09-02 15:26:26.676   872  1306 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,09-02 15:26:26.678  1465  1465 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,09-02 15:26:27.159  1465  1465 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,09-02 15:26:27.240  1465  1465 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,09-02 15:26:27.242  1465  1465 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,09-02 15:26:27.255   872  1306 D WifiConfigStore: Retrieve network priorities after PNO.
,09-02 15:26:27.271   872  1306 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-02 15:26:27.272   872  1306 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-02 15:26:27.272   872  1308 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,09-02 15:26:27.303   872  1306 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-02 15:26:27.324   372   870 D CommandListener: Setting iface cfg
,09-02 15:26:27.326   872  1306 D WifiStateMachine: Start Dhcp Watchdog 3
,09-02 15:26:27.342   872  1306 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,09-02 15:26:27.386   872  4225 D DhcpClient: Receive thread started
,09-02 15:26:27.473   872  1306 E native  : do suspend false
,09-02 15:26:27.495   872  1870 D DhcpClient: Broadcasting DHCPDISCOVER
,09-02 15:26:27.509   872  4225 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.101, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172783, domain null
,09-02 15:26:27.510   872  1870 D DhcpClient: Got pending lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172783 seconds
,09-02 15:26:27.514   872  1870 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.101 serverid=192.168.1.1
,09-02 15:26:27.529   872  4225 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.101, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,09-02 15:26:27.530   872  1870 D DhcpClient: Confirmed lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,09-02 15:26:27.535   372   870 D CommandListener: Setting iface cfg
,09-02 15:26:27.547   872  1306 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,09-02 15:26:27.550   872  1870 D DhcpClient: Scheduling renewal in 86399s
09-02 15:26:27.550   872  1306 E native  : do suspend true
,09-02 15:26:27.573   872  1306 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,09-02 15:26:27.577   872  1306 D WifiConfigStore: No blacklist allowed without epno enabled
,09-02 15:26:27.580   872  1308 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,09-02 15:26:27.585   872  1308 D ConnectivityService: Adding iface wlan0 to network 102
,09-02 15:26:27.598  3788  3836 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 416)
,09-02 15:26:27.598  3788  3836 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 416)
,09-02 15:26:27.602   872  1306 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,09-02 15:26:27.608  3788  3836 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 421)
,09-02 15:26:27.609  3788  3836 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
,09-02 15:26:27.609  3788  3836 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 422)
09-02 15:26:27.612  3788  3836 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-02 15:26:27.612  3788  3836 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@84896f8 added. We now have 2 listener(s)
,09-02 15:26:27.614  3788  3836 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-02 15:26:27.614  3788  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-02 15:26:27.614  3788  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-02 15:26:27.614  3788  3836 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-02 15:26:27.614  3788  3836 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b807d1 added. We now have 9 listener(s)
09-02 15:26:27.614  3788  3836 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-02 15:26:27.615  3788  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-02 15:26:27.618  3788  3836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-02 15:26:27.622  3788  3836 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-02 15:26:27.622  3788  3836 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 15:26:27.622  3788  3836 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-02 15:26:27.622  3788  3836 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-02 15:26:27.622  3788  3836 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-02 15:26:27.622  3788  3836 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-02 15:26:27.622  3788  3836 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-02 15:26:27.622  3788  3836 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-02 15:26:27.624  3788  3836 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-02 15:26:27.624  3788  3836 D io.jxcore.node.ConnectivityMonitor: start: OK
09-02 15:26:27.624  3788  3836 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-02 15:26:27.625  3788  3836 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@84d0537 added. We now have 3 listener(s)
09-02 15:26:27.625  3788  3788 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-02 15:26:27.626  3788  3836 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-02 15:26:27.627  3788  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-02 15:26:27.627  3788  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-02 15:26:27.627  3788  3836 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-02 15:26:27.627  3788  3836 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fec2aa4 added. We now have 10 listener(s)
,09-02 15:26:27.627  3788  3788 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-02 15:26:27.627  3788  3836 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-02 15:26:27.627  3788  3836 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-02 15:26:27.627  3788  3836 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-02 15:26:27.627  3788  3836 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-02 15:26:27.628  3788  3836 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 15:26:27.628  3788  3836 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 15:26:27.628  3788  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-02 15:26:27.628  3788  3836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-02 15:26:27.628  3788  3836 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@84896f8 removed from the list
09-02 15:26:27.628  3788  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 15:26:27.628  3788  3836 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b807d1 removed from the list
09-02 15:26:27.628  3788  3836 D io.jxcore.node.ConnectivityMonitor: stop
,09-02 15:26:27.628  3788  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 15:26:27.629  3788  3836 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 15:26:27.629  3788  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 15:26:27.630  3788  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-02 15:26:27.630  3788  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-02 15:26:27.630  3788  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 15:26:27.630  3788  3836 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b807d1 not in the list
09-02 15:26:27.630  3788  3836 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 15:26:27.630  3788  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 15:26:27.631  3788  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-02 15:26:27.631  3788  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-02 15:26:27.631  3788  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-02 15:26:27.631  3788  3836 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fec2aa4 removed from the list
09-02 15:26:27.631  3788  3836 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 15:26:27.631  3788  3836 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 15:26:27.631  3788  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 15:26:27.631  3788  3836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-02 15:26:27.632  3788  3836 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@84d0537 removed from the list
,09-02 15:26:27.632  3788  3836 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-02 15:26:27.632  3788  3836 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b64500d added. We now have 2 listener(s)
,09-02 15:26:27.634  3788  3836 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-02 15:26:27.634  3788  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-02 15:26:27.634  3788  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-02 15:26:27.634  3788  3836 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-02 15:26:27.634  3788  3836 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1283bc2 added. We now have 9 listener(s)
09-02 15:26:27.634  3788  3836 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-02 15:26:27.635  3788  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-02 15:26:27.637  3788  3836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-02 15:26:27.640  3788  3836 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-02 15:26:27.640  3788  3836 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 15:26:27.640  3788  3836 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-02 15:26:27.640  3788  3836 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-02 15:26:27.640  3788  3836 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-02 15:26:27.640  3788  3836 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-02 15:26:27.640  3788  3836 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-02 15:26:27.640  3788  3836 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-02 15:26:27.642  3788  3836 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-02 15:26:27.642  3788  3836 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-02 15:26:27.642  3788  3836 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-02 15:26:27.642  3788  3836 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6134d10 added. We now have 3 listener(s)
,09-02 15:26:27.644   872  1308 E ConnectivityService: Unexpected mtu value: 0, wlan0
,09-02 15:26:27.644   872  1308 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
,09-02 15:26:27.644  3788  3788 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-02 15:26:27.644  3788  3836 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-02 15:26:27.644  3788  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-02 15:26:27.644  3788  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-02 15:26:27.645  3788  3836 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-02 15:26:27.645  3788  3836 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@212e009 added. We now have 10 listener(s)
,09-02 15:26:27.645  3788  3836 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-02 15:26:27.645  3788  3836 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-02 15:26:27.645  3788  3836 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-02 15:26:27.645   872  1308 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
09-02 15:26:27.645  3788  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,09-02 15:26:27.645  3788  3836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-02 15:26:27.645  3788  3836 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-02 15:26:27.646  3788  3788 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-02 15:26:27.646   872  1308 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
,09-02 15:26:27.647   872  1308 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
09-02 15:26:27.649  3788  3836 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-02 15:26:27.649  3788  3836 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-02 15:26:27.654   872  1308 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
09-02 15:26:27.655  3788  3836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-02 15:26:27.656  3788  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-02 15:26:27.656  3788  3836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-02 15:26:27.658  3788  3836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-02 15:26:27.658   872  1308 D ConnectivityService: scheduleUnvalidatedPrompt 102
09-02 15:26:27.659  3788  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-02 15:26:27.659  3788  3836 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-02 15:26:27.659   872  1308 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 102]
,09-02 15:26:27.659   872  1308 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 102]
09-02 15:26:27.659   872  1306 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
09-02 15:26:27.659   872  1308 D ConnectivityService:    accepting network in place of null
09-02 15:26:27.659  3788  3836 D BluetoothAdapter: STATE_ON
09-02 15:26:27.659   872  1306 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-02 15:26:27.660   872  1308 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.101/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-02 15:26:27.662  4168  4178 D BtGatt.GattService: registerClient() - UUID=4deff6c8-8c80-4eb2-aea8-4c9bf11420b5
09-02 15:26:27.662  4168  4184 D BtGatt.GattService: onClientRegistered() - UUID=4deff6c8-8c80-4eb2-aea8-4c9bf11420b5, clientIf=5
09-02 15:26:27.663  3788  3800 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-02 15:26:27.663  4168  4208 D BtGatt.GattService: start scan with filters
,09-02 15:26:27.666  3788  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-02 15:26:27.666  4168  4187 D BtGatt.ScanManager: handling starting scan
,09-02 15:26:27.666  3788  3836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-02 15:26:27.666  3788  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-02 15:26:27.666  3788  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-02 15:26:27.667  4168  4187 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@12ec4c6
,09-02 15:26:27.669  3788  3836 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-02 15:26:27.669  4168  4184 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-02 15:26:27.669  3788  3788 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-02 15:26:27.669  4168  4184 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-02 15:26:27.669  3788  3836 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-02 15:26:27.669  4168  4187 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-02 15:26:27.671  3788  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
09-02 15:26:27.671  4168  4184 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,09-02 15:26:27.671  4168  4184 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-02 15:26:27.671  4168  4187 D BtGatt.ScanManager: Starting BLE batch scan
09-02 15:26:27.671  4168  4187 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,09-02 15:26:27.673  4168  4184 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,09-02 15:26:27.673  4168  4184 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-02 15:26:27.674  3788  3836 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,09-02 15:26:27.674  3788  3836 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-02 15:26:27.674  3788  3836 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-02 15:26:27.674  3788  3836 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 15:26:27.674  4168  4184 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,09-02 15:26:27.674  3788  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-02 15:26:27.674  4168  4184 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-02 15:26:27.674  3788  3836 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-02 15:26:27.674  3788  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-02 15:26:27.674  3788  3836 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-02 15:26:27.674  3788  3836 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,09-02 15:26:27.675  3788  3836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-02 15:26:27.675  3788  3836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-02 15:26:27.675  3788  3836 D BluetoothAdapter: STATE_ON
09-02 15:26:27.676  4168  4204 D BtGatt.GattService: stopScan() - queue size =1
,09-02 15:26:27.676   872  4224 D NetlinkSocketObserver: NeighborEvent{elapsedMs=155117, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
09-02 15:26:27.676  4168  4178 D BtGatt.GattService: unregisterClient() - clientIf=5
09-02 15:26:27.676  3788  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-02 15:26:27.676  3788  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,09-02 15:26:27.677  3788  3836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-02 15:26:27.677  3788  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-02 15:26:27.677  3788  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-02 15:26:27.677  4168  4184 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,09-02 15:26:27.678  4168  4184 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-02 15:26:27.678  3788  3836 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-02 15:26:27.678  4168  4187 D BtGatt.ScanManager: stopping BLe Batch
09-02 15:26:27.678  3788  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-02 15:26:27.678  3788  3836 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,09-02 15:26:27.678  3788  3836 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-02 15:26:27.678  3788  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-02 15:26:27.679  3788  3788 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-02 15:26:27.679  3788  3788 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-02 15:26:27.679  3788  3788 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-02 15:26:27.680  4168  4184 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-02 15:26:27.680  4168  4184 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-02 15:26:27.680  4168  4187 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
09-02 15:26:27.681  3788  3836 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-02 15:26:27.682  3788  3836 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-02 15:26:27.682  3788  3836 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-02 15:26:27.682  4168  4184 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,09-02 15:26:27.682  4168  4184 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-02 15:26:27.682  3788  3836 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 15:26:27.682  3788  3836 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 15:26:27.682  3788  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-02 15:26:27.682  3788  3836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-02 15:26:27.682  3788  3836 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b64500d removed from the list
09-02 15:26:27.682  3788  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 15:26:27.682  3788  3836 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1283bc2 removed from the list
09-02 15:26:27.682  3788  3836 D io.jxcore.node.ConnectivityMonitor: stop
,09-02 15:26:27.682  3788  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 15:26:27.683  3788  3836 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 15:26:27.683  3788  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 15:26:27.683  3788  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-02 15:26:27.684  3788  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-02 15:26:27.684  3788  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-02 15:26:27.684  3788  3836 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1283bc2 not in the list
09-02 15:26:27.684  3788  3836 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 15:26:27.684  3788  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 15:26:27.684  3788  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-02 15:26:27.685  3788  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-02 15:26:27.685  3788  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 15:26:27.685  3788  3836 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@212e009 removed from the list
,09-02 15:26:27.685  3788  3836 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 15:26:27.685  3788  3836 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 15:26:27.685  3788  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 15:26:27.685  3788  3836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-02 15:26:27.685  3788  3836 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6134d10 removed from the list
09-02 15:26:27.686  3788  3836 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-02 15:26:27.686  3788  3836 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@50073c5 added. We now have 2 listener(s)
09-02 15:26:27.687  3788  3836 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-02 15:26:27.687  3788  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-02 15:26:27.687  3788  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-02 15:26:27.687  3788  3836 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-02 15:26:27.687  3788  3836 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3d5811a added. We now have 9 listener(s)
09-02 15:26:27.688  3788  3836 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-02 15:26:27.688  3788  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-02 15:26:27.691  3788  3836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-02 15:26:27.694  3788  3836 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-02 15:26:27.694  3788  3836 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 15:26:27.694  3788  3836 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-02 15:26:27.694  3788  3836 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-02 15:26:27.694  3788  3836 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-02 15:26:27.694  3788  3836 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-02 15:26:27.694  3788  3836 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-02 15:26:27.694  3788  3836 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-02 15:26:27.695   372   870 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-02 15:26:27.696  3788  3836 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-02 15:26:27.696  3788  3836 D io.jxcore.node.ConnectivityMonitor: start: OK
09-02 15:26:27.696  3788  3836 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-02 15:26:27.696  3788  3836 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c8bae28 added. We now have 3 listener(s)
,09-02 15:26:27.698  3788  3788 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-02 15:26:27.698  3788  3836 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-02 15:26:27.699  3788  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-02 15:26:27.699  3788  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-02 15:26:27.699  3788  3836 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-02 15:26:27.699  3788  3836 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1798741 added. We now have 10 listener(s)
09-02 15:26:27.699  3788  3836 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-02 15:26:27.699  3788  3836 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-02 15:26:27.699  3788  3788 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-02 15:26:27.700  3788  3836 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-02 15:26:27.700  3788  3836 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-02 15:26:27.700  3788  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-02 15:26:27.700  3788  3836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-02 15:26:27.700  3788  3836 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-02 15:26:27.702  3788  3836 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-02 15:26:27.702  3788  3836 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-02 15:26:27.705  3788  3836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-02 15:26:27.705  3788  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-02 15:26:27.705  3788  3836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-02 15:26:27.708  3788  3836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-02 15:26:27.708  3788  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-02 15:26:27.708  3788  3836 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-02 15:26:27.709  3788  3836 D BluetoothAdapter: STATE_ON
,09-02 15:26:27.710  4168  4207 D BtGatt.GattService: registerClient() - UUID=a6791c56-a182-4412-ab37-96ed18023864
09-02 15:26:27.710  4168  4184 D BtGatt.GattService: onClientRegistered() - UUID=a6791c56-a182-4412-ab37-96ed18023864, clientIf=5
09-02 15:26:27.711  3788  3799 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-02 15:26:27.711  4168  4203 D BtGatt.GattService: start scan with filters
09-02 15:26:27.713  3788  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-02 15:26:27.713  3788  3836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-02 15:26:27.713  4168  4187 D BtGatt.ScanManager: handling starting scan
09-02 15:26:27.713  3788  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-02 15:26:27.713  3788  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
09-02 15:26:27.714  4168  4184 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-02 15:26:27.714  4168  4184 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-02 15:26:27.715  4168  4187 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
09-02 15:26:27.715  3788  3836 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-02 15:26:27.715  3788  3836 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-02 15:26:27.716  3788  3788 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-02 15:26:27.716  4168  4184 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
09-02 15:26:27.716  4168  4184 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-02 15:26:27.716  4168  4187 D BtGatt.ScanManager: Starting BLE batch scan
09-02 15:26:27.716  4168  4187 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
09-02 15:26:27.718  4168  4184 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-02 15:26:27.718  4168  4184 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-02 15:26:27.718  3788  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
09-02 15:26:27.719  4168  4184 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-02 15:26:27.719  4168  4184 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-02 15:26:27.720  3788  3836 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
09-02 15:26:27.720  3788  3836 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
09-02 15:26:27.721  3788  3836 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-02 15:26:27.721  3788  3836 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-02 15:26:27.721  3788  3836 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-02 15:26:27.721  3788  3836 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 15:26:27.721  3788  3836 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 15:26:27.721  3788  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-02 15:26:27.721  3788  3836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,09-02 15:26:27.721  3788  3836 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@50073c5 removed from the list
,09-02 15:26:27.721  3788  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 15:26:27.721  3788  3836 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3d5811a removed from the list
09-02 15:26:27.721  3788  3836 D io.jxcore.node.ConnectivityMonitor: stop
09-02 15:26:27.721  3788  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-02 15:26:27.722  3788  3836 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
,09-02 15:26:27.722  3788  3836 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
,09-02 15:26:27.722  3788  3836 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-02 15:26:27.722  3788  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-02 15:26:27.723  3788  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-02 15:26:27.723  3788  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-02 15:26:27.723  3788  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-02 15:26:27.723  3788  3836 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3d5811a not in the list
09-02 15:26:27.723  3788  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-02 15:26:27.723  3788  3836 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,09-02 15:26:27.723  3788  3836 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-02 15:26:27.723  3788  3836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,09-02 15:26:27.723  3788  3836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-02 15:26:27.724  3788  3836 D BluetoothAdapter: STATE_ON
09-02 15:26:27.724  4168  4207 D BtGatt.GattService: stopScan() - queue size =1
09-02 15:26:27.724   372   870 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-02 15:26:27.725  4168  4203 D BtGatt.GattService: unregisterClient() - clientIf=5
09-02 15:26:27.725  3788  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-02 15:26:27.725  3788  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-02 15:26:27.725  3788  3836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,09-02 15:26:27.725  3788  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,09-02 15:26:27.725  3788  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-02 15:26:27.726  4168  4184 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
09-02 15:26:27.726  4168  4184 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-02 15:26:27.726  3788  3836 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-02 15:26:27.726  3788  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-02 15:26:27.726  3788  3836 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-02 15:26:27.726  4168  4187 D BtGatt.ScanManager: stopping BLe Batch
09-02 15:26:27.726  3788  3836 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-02 15:26:27.727  3788  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 15:26:27.727   872  1308 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
,09-02 15:26:27.727   872  1308 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
09-02 15:26:27.729  4168  4184 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,09-02 15:26:27.730  4168  4184 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-02 15:26:27.730  4168  4187 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
09-02 15:26:27.731   872  1308 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
09-02 15:26:27.732  3788  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-02 15:26:27.732  3788  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-02 15:26:27.732  3788  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 15:26:27.733  3788  3788 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-02 15:26:27.733  3788  3788 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-02 15:26:27.733  3788  3788 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-02 15:26:27.734  3788  3836 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1798741 removed from the list
,09-02 15:26:27.734  3788  3836 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 15:26:27.734  3788  3836 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-02 15:26:27.735  3788  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 15:26:27.736  4168  4184 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-02 15:26:27.737  4168  4184 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-02 15:26:27.737   872   889 D Tethering: MasterInitialState.processMessage what=3
09-02 15:26:27.735  3788  3836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,09-02 15:26:27.737  3788  3836 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c8bae28 removed from the list
09-02 15:26:27.740  3788  3836 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-02 15:26:27.740  3788  3836 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@316567d added. We now have 2 listener(s),
09-02 15:26:27.741  3788  3788 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-02 15:26:27.741  3788  3788 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 15:26:27.741  3788  3788 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-02 15:26:27.741  3788  3788 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-02 15:26:27.741  3788  3788 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-02 15:26:27.741  3788  3788 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-02 15:26:27.741  3788  3788 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-02 15:26:27.741  3788  3788 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-02 15:26:27.742  3788  3836 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-02 15:26:27.743  3788  3788 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-02 15:26:27.743  3788  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-02 15:26:27.743  3788  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-02 15:26:27.743  3788  3836 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-02 15:26:27.743  3788  3836 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8b1972 added. We now have 9 listener(s)
09-02 15:26:27.743  3788  3836 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-02 15:26:27.745  3788  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-02 15:26:27.749  3788  3836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-02 15:26:27.752  3788  3836 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-02 15:26:27.752  3788  3836 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 15:26:27.752  3788  3836 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-02 15:26:27.752  3788  3836 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-02 15:26:27.752  3788  3836 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-02 15:26:27.752  3788  3836 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-02 15:26:27.752  3788  3836 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-02 15:26:27.752  3788  3836 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-02 15:26:27.754  3788  3836 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-02 15:26:27.754  3788  3836 D io.jxcore.node.ConnectivityMonitor: start: OK
09-02 15:26:27.754  3788  3836 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-02 15:26:27.754  3788  3836 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@85c1a40 added. We now have 3 listener(s)
,09-02 15:26:27.755  1747  1747 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,09-02 15:26:27.756  3788  3788 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-02 15:26:27.757  3788  3836 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-02 15:26:27.757  3788  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-02 15:26:27.757  3788  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-02 15:26:27.757  3788  3836 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-02 15:26:27.758  3788  3836 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cb6dd79 added. We now have 10 listener(s)
,09-02 15:26:27.758  3788  3788 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-02 15:26:27.758  3788  3836 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-02 15:26:27.758  3788  3836 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,09-02 15:26:27.758  3788  3836 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-02 15:26:27.758  3788  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-02 15:26:27.758  3788  3836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-02 15:26:27.759  3788  3836 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-02 15:26:27.762  1747  1747 D SystemUpdateService: onCreate
,09-02 15:26:27.762  3788  3836 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-02 15:26:27.763  3788  3836 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-02 15:26:27.765  1747  1747 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,09-02 15:26:27.765  3788  3836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-02 15:26:27.766  3788  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-02 15:26:27.766  3788  3836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-02 15:26:27.769   872  4223 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=172.217.16.206,2a00:1450:4001:814::200e
,09-02 15:26:27.771  3788  3836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-02 15:26:27.771  3788  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-02 15:26:27.771  3788  3836 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-02 15:26:27.771  3788  3836 D BluetoothAdapter: STATE_ON
,09-02 15:26:27.773  4168  4208 D BtGatt.GattService: registerClient() - UUID=66ae600a-a181-47b2-89aa-eb4859cbe3c8
09-02 15:26:27.774  4168  4184 D BtGatt.GattService: onClientRegistered() - UUID=66ae600a-a181-47b2-89aa-eb4859cbe3c8, clientIf=5
,09-02 15:26:27.774  3788  3799 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-02 15:26:27.774  4168  4207 D BtGatt.GattService: start scan with filters
,09-02 15:26:27.777  3788  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-02 15:26:27.778  3788  3836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-02 15:26:27.778  4168  4187 D BtGatt.ScanManager: handling starting scan
09-02 15:26:27.778  3788  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-02 15:26:27.778  3788  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-02 15:26:27.779  4168  4184 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,09-02 15:26:27.780  4168  4184 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-02 15:26:27.780  4168  4187 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
09-02 15:26:27.781  3788  3836 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-02 15:26:27.781  3788  3836 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-02 15:26:27.781  4168  4184 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,09-02 15:26:27.781  4168  4184 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-02 15:26:27.781  4168  4187 D BtGatt.ScanManager: Starting BLE batch scan
09-02 15:26:27.781  4168  4187 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
09-02 15:26:27.781  3788  3788 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-02 15:26:27.782  3788  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
09-02 15:26:27.783  4168  4184 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-02 15:26:27.783  4168  4184 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-02 15:26:27.784  4168  4184 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-02 15:26:27.784  4168  4184 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-02 15:26:27.788  3788  3836 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-02 15:26:27.788  3788  3836 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-02 15:26:27.788  1747  1747 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
09-02 15:26:27.788  3788  3836 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-02 15:26:27.788  3788  3836 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 15:26:27.788  3788  3836 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-02 15:26:27.788  3788  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-02 15:26:27.788  3788  3836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-02 15:26:27.788  3788  3836 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@316567d removed from the list
09-02 15:26:27.788  3788  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 15:26:27.788  3788  3836 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8b1972 removed from the list
09-02 15:26:27.789  3788  3836 D io.jxcore.node.ConnectivityMonitor: stop
09-02 15:26:27.789  3788  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-02 15:26:27.789  3788  3836 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
09-02 15:26:27.789  3788  3836 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
,09-02 15:26:27.789  3788  3836 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 15:26:27.789  3788  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-02 15:26:27.790  3788  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-02 15:26:27.790  3788  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-02 15:26:27.790  3788  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 15:26:27.790  3788  3836 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8b1972 not in the list
09-02 15:26:27.790  3788  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-02 15:26:27.790  3788  3836 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-02 15:26:27.790  3788  3836 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,09-02 15:26:27.790  3788  3836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-02 15:26:27.790  3788  3836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-02 15:26:27.791  3788  3836 D BluetoothAdapter: STATE_ON
,09-02 15:26:27.792  4168  4178 D BtGatt.GattService: stopScan() - queue size =1
,09-02 15:26:27.793  4168  4204 D BtGatt.GattService: unregisterClient() - clientIf=5
09-02 15:26:27.793  3788  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-02 15:26:27.793  3788  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,09-02 15:26:27.793  3788  3836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-02 15:26:27.793  3788  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,09-02 15:26:27.794  3788  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-02 15:26:27.794  4168  4184 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
09-02 15:26:27.794  4168  4184 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-02 15:26:27.794  4168  4187 D BtGatt.ScanManager: stopping BLe Batch
09-02 15:26:27.794  3788  3836 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-02 15:26:27.794  3788  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-02 15:26:27.795  3788  3836 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-02 15:26:27.795  3788  3836 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-02 15:26:27.795  3788  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-02 15:26:27.796  3788  3788 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-02 15:26:27.796  4168  4184 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-02 15:26:27.796  4168  4184 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-02 15:26:27.797  3788  3788 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-02 15:26:27.797  4168  4187 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
09-02 15:26:27.797  3788  3788 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-02 15:26:27.797  3788  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-02 15:26:27.797  3788  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-02 15:26:27.797  3788  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 15:26:27.797  3788  3836 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cb6dd79 removed from the list
09-02 15:26:27.798  3788  3836 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 15:26:27.798  3788  3836 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-02 15:26:27.798  3788  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 15:26:27.798  3788  3836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-02 15:26:27.798  3788  3836 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@85c1a40 removed from the list
09-02 15:26:27.799  3788  3836 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-02 15:26:27.799  3788  3836 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@53ed835 added. We now have 2 listener(s)
,09-02 15:26:27.799  4168  4184 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-02 15:26:27.799  4168  4184 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-02 15:26:27.802  3788  3836 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-02 15:26:27.802  3788  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-02 15:26:27.802  1747  2421 I iu.UploadsManager: num queued entries: 0
09-02 15:26:27.802  3788  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-02 15:26:27.803  3788  3836 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-02 15:26:27.803  1747  4234 I SystemUpdateService: active receiver: enabled
09-02 15:26:27.803  3788  3836 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fa064ca added. We now have 9 listener(s)
,09-02 15:26:27.803  3788  3836 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-02 15:26:27.803  3788  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-02 15:26:27.805  1747  1747 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-02 15:26:27.806  3788  3836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-02 15:26:27.807  1747  1747 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,09-02 15:26:27.809  3909  3909 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-02 15:26:27.810  3788  3836 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-02 15:26:27.810  3788  3836 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 15:26:27.810  3788  3836 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-02 15:26:27.810  3788  3836 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-02 15:26:27.810  3788  3836 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-02 15:26:27.810  3788  3836 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-02 15:26:27.810  3788  3836 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-02 15:26:27.810  3788  3836 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-02 15:26:27.812  3788  3836 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-02 15:26:27.812  3788  3836 D io.jxcore.node.ConnectivityMonitor: start: OK
09-02 15:26:27.813  3788  3836 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-02 15:26:27.813  3788  3836 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@51af158 added. We now have 3 listener(s)
,09-02 15:26:27.814  3788  3836 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-02 15:26:27.814  3788  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-02 15:26:27.814  3788  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-02 15:26:27.814  3788  3836 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-02 15:26:27.814  3788  3836 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@411c2b1 added. We now have 10 listener(s)
09-02 15:26:27.814  3788  3836 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-02 15:26:27.815  3788  3836 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-02 15:26:27.815  3788  3788 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-02 15:26:27.815  3788  3836 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-02 15:26:27.815  3788  3836 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-02 15:26:27.815  3788  3836 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 15:26:27.815  1747  4237 I MDM     : [184] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
,09-02 15:26:27.815  3788  3836 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 15:26:27.815  1747  4237 W BaseAppContext: Using Auth Proxy for data requests.
09-02 15:26:27.815  3788  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-02 15:26:27.815  3788  3836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-02 15:26:27.815  3788  3836 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@53ed835 removed from the list
,09-02 15:26:27.815  3788  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 15:26:27.815  3909  3909 D SprintDMHelper: simOperator: 
09-02 15:26:27.815  3909  3909 D SprintDMReceiver: Not Sprint UICC, don't do anything.
09-02 15:26:27.815  3788  3836 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fa064ca removed from the list
09-02 15:26:27.817  3788  3788 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-02 15:26:27.817  3788  3836 D io.jxcore.node.ConnectivityMonitor: stop
,09-02 15:26:27.817  3788  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-02 15:26:27.820  3788  3836 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 15:26:27.821  3788  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-02 15:26:27.821  3788  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-02 15:26:27.822  3788  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-02 15:26:27.822  3788  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 15:26:27.822  3788  3836 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fa064ca not in the list
09-02 15:26:27.822  3788  3836 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 15:26:27.822  3788  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-02 15:26:27.823  3788  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-02 15:26:27.823  3788  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-02 15:26:27.823  3788  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 15:26:27.823  3788  3836 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@411c2b1 removed from the list
09-02 15:26:27.823  3788  3836 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 15:26:27.823  3788  3836 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-02 15:26:27.823  3788  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 15:26:27.823  3788  3836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-02 15:26:27.823  3788  3836 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@51af158 removed from the list
09-02 15:26:27.824  3788  3836 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
,09-02 15:26:27.824  3788  3836 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
09-02 15:26:27.824  3788  3836 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
09-02 15:26:27.824  3788  3836 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-02 15:26:27.824  3788  3836 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
09-02 15:26:27.824  3788  3836 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,09-02 15:26:27.827  1747  4237 V GoogleAuthProtoRequest: [184] a.<init>: mAccountName set to: thalitester@gmail.com
,09-02 15:26:27.830  3788  4240 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 429, name: My test thread name)
,09-02 15:26:27.830  3788  4240 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 429, thread name: My test thread name)
09-02 15:26:27.830  3788  4240 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 429, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,09-02 15:26:27.835  3788  4241 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 431, name: My test thread name)
,09-02 15:26:27.835  3788  4241 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 431, thread name: My test thread name)
09-02 15:26:27.835  3788  4241 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 431, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,09-02 15:26:27.837  3788  3836 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 80
,09-02 15:26:27.837  3788  3836 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 80
09-02 15:26:27.838  3788  3836 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
09-02 15:26:27.838  3788  3836 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
09-02 15:26:27.838  3788  3836 D com.test.thalitest.ThaliTestRunner: Total duration: 21713 ms
,09-02 15:26:27.839  3788  3836 I jxcore-log: *Native tests were executed*
09-02 15:26:27.839  3788  3836 I jxcore-log: 
,09-02 15:26:27.840  3788  3836 I jxcore-log: Total number of executed tests:  80
09-02 15:26:27.840  3788  3836 I jxcore-log: 
09-02 15:26:27.840  3788  3836 I jxcore-log: Number of passed tests:  80
09-02 15:26:27.840  3788  3836 I jxcore-log: 
09-02 15:26:27.840  3788  3836 I jxcore-log: Number of failed tests:  0
09-02 15:26:27.840  3788  3836 I jxcore-log: 
,09-02 15:26:27.840  3788  3836 I jxcore-log: Number of ignored tests:  0
09-02 15:26:27.840  3788  3836 I jxcore-log: 
09-02 15:26:27.841  3788  3836 I jxcore-log: Total duration:  21713
09-02 15:26:27.841  3788  3836 I jxcore-log: 
,09-02 15:26:27.841  3788  3836 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
09-02 15:26:27.841  3788  3836 I jxcore-log: 
,09-02 15:26:27.844  3788  3836 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-02 15:26:27.844  3788  3836 I jxcore-log: 
09-02 15:26:27.847  3788  3836 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-02 15:26:27.847  3788  3836 I jxcore-log: 
09-02 15:26:27.849  3788  3836 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-02 15:26:27.849  3788  3836 I jxcore-log: 
09-02 15:26:27.850  3788  3836 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-02 15:26:27.850  3788  3836 I jxcore-log: 
09-02 15:26:27.852  3788  3836 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-02 15:26:27.852  3788  3836 I jxcore-log: 
09-02 15:26:27.853  3788  3836 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-02 15:26:27.853  3788  3836 I jxcore-log: 
09-02 15:26:27.856  3788  3788 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
,09-02 15:26:27.856  1747  2421 I iu.UploadsManager: num updated entries: 0
09-02 15:26:27.856  3788  3836 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-02 15:26:27.856  3788  3836 I jxcore-log: 
,09-02 15:26:27.858  1528  1528 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
09-02 15:26:27.858  3788  3836 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-02 15:26:27.858  3788  3836 I jxcore-log: 
09-02 15:26:27.859  3788  3836 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-02 15:26:27.859  3788  3836 I jxcore-log: 
09-02 15:26:27.859  1528  1528 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
09-02 15:26:27.860  3788  3836 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-02 15:26:27.860  3788  3836 I jxcore-log: 
09-02 15:26:27.861  3788  3836 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-02 15:26:27.861  3788  3836 I jxcore-log: 
09-02 15:26:27.862  3788  3836 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-02 15:26:27.862  3788  3836 I jxcore-log: 
,09-02 15:26:27.863  3788  3836 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-02 15:26:27.863  3788  3836 I jxcore-log: 
,09-02 15:26:27.864  3788  3836 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-02 15:26:27.864  3788  3836 I jxcore-log: 
,09-02 15:26:27.864  3788  3836 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-02 15:26:27.864  3788  3836 I jxcore-log: 
09-02 15:26:27.865  3788  3836 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-02 15:26:27.865  3788  3836 I jxcore-log: 
,09-02 15:26:27.866  3788  3836 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-02 15:26:27.866  3788  3836 I jxcore-log: 
,09-02 15:26:27.866  3788  3836 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-02 15:26:27.866  3788  3836 I jxcore-log: 
,09-02 15:26:27.867  3788  3836 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-02 15:26:27.867  3788  3836 I jxcore-log: 
,09-02 15:26:27.868  3788  3836 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-02 15:26:27.868  3788  3836 I jxcore-log: 
09-02 15:26:27.869  3788  3836 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-02 15:26:27.869  3788  3836 I jxcore-log: 
,09-02 15:26:27.869  3788  3836 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-02 15:26:27.869  3788  3836 I jxcore-log: 
,09-02 15:26:27.870  1747  4234 I SystemUpdateService: Already downloaded, skipping offpeak checks.
09-02 15:26:27.870  3788  3836 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-02 15:26:27.870  3788  3836 I jxcore-log: 
09-02 15:26:27.871  3788  3836 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-02 15:26:27.871  3788  3836 I jxcore-log: 
,09-02 15:26:27.872  3788  3836 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-02 15:26:27.872  3788  3836 I jxcore-log: 
,09-02 15:26:27.872  3788  3836 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-02 15:26:27.872  3788  3836 I jxcore-log: 
,09-02 15:26:27.873  3788  3836 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-02 15:26:27.873  3788  3836 I jxcore-log: 
,09-02 15:26:27.874  3788  3836 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-02 15:26:27.874  3788  3836 I jxcore-log: 
,09-02 15:26:27.875  3788  3836 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-02 15:26:27.875  3788  3836 I jxcore-log: 
,09-02 15:26:27.876  3788  3836 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-02 15:26:27.876  3788  3836 I jxcore-log: 
,09-02 15:26:27.876  3788  3836 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-02 15:26:27.876  3788  3836 I jxcore-log: 
,09-02 15:26:27.877  3788  3836 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-02 15:26:27.877  3788  3836 I jxcore-log: 
,09-02 15:26:27.879  1747  2421 I iu.SyncManager: NEXT; no task
,09-02 15:26:27.881  1747  4234 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,09-02 15:26:27.881  1747  4234 I SystemUpdateService: now status is 0 (complete)
,09-02 15:26:27.881  1747  4234 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
,09-02 15:26:27.885  1747  4234 I SystemUpdateService: file has been verified
09-02 15:26:27.885  1747  4234 I SystemUpdateService: OTA package size = 12249756
,09-02 15:26:27.889  1528  2318 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
,09-02 15:26:27.889  1528  2318 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
,09-02 15:26:27.890  1528  2318 I GLSUser : [GLSUser] Extracting token using key: Auth
09-02 15:26:27.890  1528  2318 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
09-02 15:26:27.892   872  4223 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Fri, 02 Sep 2016 13:26:27 GMT], X-Android-Received-Millis=[1472822787891], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1472822787833]}
,09-02 15:26:27.892   872  1308 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,09-02 15:26:27.893   872  1308 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] validation  passed
,09-02 15:26:27.893   872  1308 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
09-02 15:26:27.893   872  1308 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,09-02 15:26:27.899  1747  4234 I SystemUpdateService: showing system update notification
,09-02 15:26:27.906  1747  4237 E MDM     : [184] SitrepService.a: Error sending sitrep.
,09-02 15:26:27.922  1747  1747 D SystemUpdateService: onDestroy
,09-02 15:26:27.992  3053  4239 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,09-02 15:26:28.180  3788  3788 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-02 15:26:28.181  3788  3836 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-02 15:26:28.181  3788  3836 I jxcore-log: 
,09-02 15:26:28.232  3788  3788 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
09-02 15:26:28.234  3788  3836 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-02 15:26:28.234  3788  3836 I jxcore-log: 
,09-02 15:26:28.298  3788  3788 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-02 15:26:28.301  3788  3836 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-02 15:26:28.301  3788  3836 I jxcore-log: 
,09-02 15:26:28.520  4247  4247 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,09-02 15:26:28.527  4247  4247 D AndroidRuntime: CheckJNI is OFF
,09-02 15:26:28.573  4247  4247 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,09-02 15:26:28.616  4247  4247 I Radio-JNI: register_android_hardware_Radio DONE
,09-02 15:26:28.638  4247  4247 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,09-02 15:26:28.649   872   885 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=-1: uninstall pkg
,09-02 15:26:28.650   872   885 I ActivityManager: Killing 3788:com.test.thalitest/u0a0 (adj 0): stop com.test.thalitest
,09-02 15:26:28.727   872  1308 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 101] cleared because we found a replacement network
,09-02 15:26:28.743   872   882 I WindowState: WIN DEATH: Window{74ba114 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,09-02 15:26:28.743   872  1307 D WifiService: Client connection lost with reason: 4
,09-02 15:26:28.744   872  1693 D GraphicsStats: Buffer count: 2
,09-02 15:26:28.784   872   895 W PackageSettings: Skipping PackageSetting{16eb53b com.example.hello/10273} due to missing metadata
,09-02 15:26:28.817   872   885 W ActivityManager: Failed trying to unstop package com.test.thalitest: java.lang.IllegalArgumentException: Unknown package: com.test.thalitest
,09-02 15:26:28.818   872   885 W PackageManager: Package com.test.thalitest is missing; assuming frozen
,09-02 15:26:28.820   872   895 I art     : Starting a blocking GC Explicit
,09-02 15:26:28.820   872   885 E ActivityManager: Failure starting process com.test.thalitest
09-02 15:26:28.820   872   885 E ActivityManager: java.lang.RuntimeException: Package com.test.thalitest is frozen!
09-02 15:26:28.820   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3272)
09-02 15:26:28.820   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3231)
09-02 15:26:28.820   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3110)
09-02 15:26:28.820   872   885 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1395)
09-02 15:26:28.820   872   885 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:2007)
09-02 15:26:28.820   872   885 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1554)
09-02 15:26:28.820   872   885 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2735)
09-02 15:26:28.820   872   885 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2724)
09-02 15:26:28.820   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4592)
09-02 15:26:28.820   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:5949)
09-02 15:26:28.820   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.killPackageProcessesLocked(ActivityManagerService.java:5608)
09-02 15:26:28.820   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.forceStopPackageLocked(ActivityManagerService.java:5757)
09-02 15:26:28.820   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.-wrap1(ActivityManagerService.java)
09-02 15:26:28.820   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:1730)
09-02 15:26:28.820   872   885 E ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-02 15:26:28.820   872   885 E ActivityManager: 	at android.os.Looper.loop(Looper.java:148)
09-02 15:26:28.820   872   885 E ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-02 15:26:28.820   872   885 E ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
,09-02 15:26:28.822   872   885 I ActivityManager:   Force finishing activity ActivityRecord{639de25 u0 com.test.thalitest/.MainActivity t2}
,09-02 15:26:28.830   872  1994 W ActivityManager: Spurious death for ProcessRecord{4a6e106 0:com.test.thalitest/u0a0}, curProc for 3788: null
,09-02 15:26:28.882   872   895 I art     : Explicit concurrent mark sweep GC freed 55036(3MB) AllocSpace objects, 9(220KB) LOS objects, 33% free, 29MB/43MB, paused 1.366ms total 58.191ms
,09-02 15:26:28.908   872   895 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,09-02 15:26:28.912  4247  4247 I art     : System.exit called, status: 0
,09-02 15:26:28.912  4247  4247 I AndroidRuntime: VM exiting with result code 0.
09-02 15:26:28.913   872   895 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=0: pkg removed
,09-02 15:26:28.932   872   885 I ActivityManager: Exiting empty application process com.test.thalitest (null)
,09-02 15:26:28.945  4168  4168 D BluetoothMapAppObserver: onReceive
,09-02 15:26:28.945  4168  4168 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
09-02 15:26:28.945   872  1297 I InputReader: Reconfiguring input devices.  changes=0x00000010
,09-02 15:26:28.951  2183  2259 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,09-02 15:26:28.953  3627  3627 D BuaReceiver: ====== got intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.motorola.android.buacontactadapter/.BuaReceiver (has extras) }
,09-02 15:26:28.969  1871  1871 I Keyboard.Facilitator: resetDictionaries() : en_US
,09-02 15:26:28.972  1871  4265 I Keyboard.Facilitator.DecoderInitializer: run()
,09-02 15:26:28.976  1871  4265 I Decoder : createOrResetDecoder
,09-02 15:26:28.997  1939  1939 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,09-02 15:26:28.998   872  1372 I ActivityManager: Start proc 4266:android.process.acore/u0a5 for broadcast com.android.providers.contacts/.PackageIntentReceiver
,09-02 15:26:29.024   872   872 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,09-02 15:26:29.044  1954  2040 E SQLiteLog: (3850) statement aborts at 23: [DELETE FROM icons WHERE componentName LIKE ? AND profileId = ?] disk I/O error
,09-02 15:26:29.046   872   884 W AtomicFile: Couldn't rename file /data/system/users/0/runtime-permissions.xml to backup file /data/system/users/0/runtime-permissions.xml.bak
09-02 15:26:29.047   872   884 E PackageManager: Failed to write settings, restoring backup
09-02 15:26:29.047   872   884 E PackageManager: java.io.IOException: Couldn't create directory /data/system/users/0/runtime-permissions.xml
09-02 15:26:29.047   872   884 E PackageManager: 	at android.util.AtomicFile.startWrite(AtomicFile.java:106)
09-02 15:26:29.047   872   884 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.writePermissionsSync(Settings.java:4615)
09-02 15:26:29.047   872   884 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.-wrap1(Settings.java)
09-02 15:26:29.047   872   884 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence$MyHandler.handleMessage(Settings.java:4830)
09-02 15:26:29.047   872   884 E PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-02 15:26:29.047   872   884 E PackageManager: 	at android.os.Looper.loop(Looper.java:148)
09-02 15:26:29.047   872   884 E PackageManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,09-02 15:26:29.052   872   885 E DropBoxManagerService: Can't write: system_server_wtf
09-02 15:26:29.052   872   885 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop15.tmp: open failed: EROFS (Read-only file system)
09-02 15:26:29.052   872   885 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-02 15:26:29.052   872   885 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-02 15:26:29.052   872   885 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-02 15:26:29.052   872   885 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-02 15:26:29.052   872   885 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-02 15:26:29.052   872   885 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-02 15:26:29.052   872   885 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12543)
09-02 15:26:29.052   872   885 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.handleApplicationWtfInner(ActivityManagerService.java:12356)
09-02 15:26:29.052   872   885 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:12328)
09-02 15:26:29.052   872   885 E DropBoxManagerService: 	at android.os.Handler.handleCallback(Handler.java:739)
09-02 15:26:29.052   872   885 E DropBoxManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-02 15:26:29.052   872   885 E DropBoxManagerService: 	at android.os.Looper.loop(Looper.java:148)
09-02 15:26:29.052   872   885 E DropBoxManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-02 15:26:29.052   872   885 E DropBoxManagerService: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
09-02 15:26:29.052   872   885 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-02 15:26:29.052   872   885 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-02 15:26:29.052   872   885 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-02 15:26:29.052   872   885 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-02 15:26:29.052   872   885 E DropBoxManagerService: 	... 13 more
,09-02 15:26:29.053  4266  4266 W System  : ClassLoader referenced unknown path: /system/priv-app/ContactsProvider/lib/arm
,09-02 15:26:29.058   872  1692 I ActivityManager: Start proc 4278:com.google.android.googlequicksearchbox:crash_report/u0a28 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
--------- beginning of crash
09-02 15:26:29.058  1954  2040 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
09-02 15:26:29.058  1954  2040 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 1954
09-02 15:26:29.058  1954  2040 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-02 15:26:29.058  1954  2040 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
09-02 15:26:29.058  1954  2040 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
09-02 15:26:29.058  1954  2040 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
09-02 15:26:29.058  1954  2040 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
09-02 15:26:29.058  1954  2040 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
09-02 15:26:29.058  1954  2040 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
09-02 15:26:29.058  1954  2040 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
09-02 15:26:29.058  1954  2040 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
09-02 15:26:29.058  1954  2040 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-02 15:26:29.058  1954  2040 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-02 15:26:29.058  1954  2040 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,09-02 15:26:29.060  1528  1528 I ConfigService: onCreate
,09-02 15:26:29.062   872  1959 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,09-02 15:26:29.062   872  4284 E DropBoxManagerService: Can't write: system_app_crash
09-02 15:26:29.062   872  4284 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop122.tmp: open failed: EROFS (Read-only file system)
09-02 15:26:29.062   872  4284 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-02 15:26:29.062   872  4284 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-02 15:26:29.062   872  4284 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-02 15:26:29.062   872  4284 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-02 15:26:29.062   872  4284 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-02 15:26:29.062   872  4284 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-02 15:26:29.062   872  4284 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-02 15:26:29.062   872  4284 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-02 15:26:29.062   872  4284 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-02 15:26:29.062   872  4284 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-02 15:26:29.062   872  4284 E DropBoxManagerService: 	... 5 more
09-02 15:26:29.064  1528  4283 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/config.db'.
09-02 15:26:29.064  1528  4283 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-02 15:26:29.064  1528  4283 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-02 15:26:29.064  1528  4283 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-02 15:26:29.064  1528  4283 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-02 15:26:29.064  1528  4283 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-02 15:26:29.064  1528  4283 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-02 15:26:29.064  1528  4283 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-02 15:26:29.064  1528  4283 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-02 15:26:29.064  1528  4283 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-02 15:26:29.064  1528  4283 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-02 15:26:29.064  1528  4283 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-02 15:26:29.064  1528  4283 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-02 15:26:29.064  1528  4283 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-02 15:26:29.064  1528  4283 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-02 15:26:29.064  1528  4283 E SQLiteDatabase: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
09-02 15:26:29.064  1528  4283 E SQLiteDatabase: 	at com.google.android.gms.config.j.run(SourceFile:152)
09-02 15:26:29.064  1528  4283 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
09-02 15:26:29.064  1528  4283 E SQLiteOpenHelper: Couldn't open config.db for writing (will try read-only):
09-02 15:26:29.064  1528  4283 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the data,base in read/write mode.
09-02 15:26:29.064  1528  4283 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-02 15:26:29.064  1528  4283 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-02 15:26:29.064  1528  4283 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-02 15:26:29.064  1528  4283 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-02 15:26:29.064  1528  4283 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-02 15:26:29.064  1528  4283 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-02 15:26:29.064  1528  4283 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-02 15:26:29.064  1528  4283 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-02 15:26:29.064  1528  4283 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-02 15:26:29.064  1528  4283 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-02 15:26:29.064  1528  4283 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-02 15:26:29.064  1528  4283 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-02 15:26:29.064  1528  4283 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-02 15:26:29.064  1528  4283 E SQLiteOpenHelper: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
09-02 15:26:29.064  1528  4283 E SQLiteOpenHelper: 	at com.google.android.gms.config.j.run(SourceFile:152)
09-02 15:26:29.064  1528  4283 E SQLiteOpenHelper: 	at java.lang.Thread.run(Thread.java:818)
09-02 15:26:29.064   872   882 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 3788 uid 10000
,09-02 15:26:29.066  1528  4283 W SQLiteOpenHelper: Opened config.db in read-only mode
09-02 15:26:29.067  1954  2040 I Process : Sending signal. PID: 1954 SIG: 9
,09-02 15:26:29.070  1871  1871 I Keyboard.Facilitator: onFinishInput()
,09-02 15:26:29.083  1871  4265 I Keyboard.Facilitator.MainLanguageModelLoader: run()
,09-02 15:26:29.134   872   882 I WindowState: WIN DEATH: Window{41a6d9e u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL}
,09-02 15:26:29.134   872  1959 D GraphicsStats: Buffer count: 1
,09-02 15:26:29.171   872  1692 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 1954) has died
,09-02 15:26:29.171   872  1692 W ActivityManager: Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.reflection.ReflectionService in 1000ms
,09-02 15:26:29.172   872  1692 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
,09-02 15:26:29.188   872   885 I ActivityManager: Start proc 4296:com.google.android.googlequicksearchbox/u0a28 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,09-02 15:26:29.244  4296  4296 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.googlequicksearchbox/databases/launcher.db'.
09-02 15:26:29.244  4296  4296 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-02 15:26:29.244  4296  4296 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-02 15:26:29.244  4296  4296 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-02 15:26:29.244  4296  4296 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-02 15:26:29.244  4296  4296 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-02 15:26:29.244  4296  4296 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-02 15:26:29.244  4296  4296 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-02 15:26:29.244  4296  4296 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-02 15:26:29.244  4296  4296 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-02 15:26:29.244  4296  4296 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-02 15:26:29.244  4296  4296 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-02 15:26:29.244  4296  4296 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-02 15:26:29.244  4296  4296 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-02 15:26:29.244  4296  4296 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-02 15:26:29.244  4296  4296 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
09-02 15:26:29.244  4296  4296 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
09-02 15:26:29.244  4296  4296 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
09-02 15:26:29.244  4296  4296 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
09-02 15:26:29.244  4296  4296 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
09-02 15:26:29.244  4296  4296 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
09-02 15:26:29.244  4296  4296 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
09-02 15:26:29.244  4296  4296 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-02 15:26:29.244  4296  4296 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-02 15:26:29.244  4296  4296 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-02 15:26:29.244  4296  4296 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
09-02 15:26:29.244  4296  4296 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-02 15:26:29.244  4296  4296 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
09-02 15:26:29.244  4296  4296 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-02 15:26:29.244  4296  4296 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-02 15:26:29.245  4296  4296 D AndroidRuntime: Shutting down VM
09-02 15:26:29.250  4296  4296 E AndroidRuntime: FATAL EXCEPTION: main
09-02 15:26:29.250  4296  4296 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 4296
09-02 15:26:29.250  4296  4296 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.android.launcher3.LauncherProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-02 15:26:29.250  4296  4296 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5156)
09-02 15:26:29.250  4296  4296 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
09-02 15:26:29.250  4296  4296 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
09-02 15:26:29.250  4296  4296 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-02 15:26:29.250  4296  4296 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-02 15:26:29.250  4296  4296 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-02 15:26:29.250  4296  4296 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-02 15:26:29.250  4296  4296 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-02 15:26:29.250  4296  4296 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
09-02 15:26:29.250  4296  4296 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-02 15:26:29.250  4296  4296 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-02 15:26:29.250  4296  4296 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-02 15:26:29.250  4296  4296 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-02 15:26:29.250  4296  4296 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-02 15:26:29.250  4296  4296 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-02 15:26:29.250  4296  4296 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-02 15:26:29.250  4296  4296 E AndroidRuntime: 	,at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-02 15:26:29.250  4296  4296 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-02 15:26:29.250  4296  4296 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-02 15:26:29.250  4296  4296 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-02 15:26:29.250  4296  4296 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-02 15:26:29.250  4296  4296 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-02 15:26:29.250  4296  4296 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-02 15:26:29.250  4296  4296 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-02 15:26:29.250  4296  4296 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-02 15:26:29.250  4296  4296 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
09-02 15:26:29.250  4296  4296 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
09-02 15:26:29.250  4296  4296 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
09-02 15:26:29.250  4296  4296 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
09-02 15:26:29.250  4296  4296 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
09-02 15:26:29.250  4296  4296 E AndroidRuntime: 	... 10 more
09-02 15:26:29.256   872   882 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
09-02 15:26:29.257  4296  4296 I Process : Sending signal. PID: 4296 SIG: 9
09-02 15:26:29.257   872  4310 E DropBoxManagerService: Can't write: system_app_crash
09-02 15:26:29.257   872  4310 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop123.tmp: open failed: EROFS (Read-only file system)
09-02 15:26:29.257   872  4310 E DropBoxManagerService: 	,at libcore.io.IoBridge.open(IoBridge.java:452)
09-02 15:26:29.257   872  4310 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-02 15:26:29.257   872  4310 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-02 15:26:29.257   872  4310 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-02 15:26:29.257   872  4310 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-02 15:26:29.257   872  4310 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-02 15:26:29.257   872  4310 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-02 15:26:29.257   872  4310 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-02 15:26:29.257   872  4310 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-02 15:26:29.257   872  4310 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-02 15:26:29.257   872  4310 E DropBoxManagerService: 	... 5 more
,09-02 15:26:29.285  1871  4265 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /data/user/0/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
,09-02 15:26:29.286  1871  4265 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
09-02 15:26:29.286  1871  4265 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
09-02 15:26:29.288  1871  4265 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Contacts.dict
,09-02 15:26:29.288  1871  4265 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = history
09-02 15:26:29.288  1871  4265 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loaded File = UserHistory.en_US.dict
09-02 15:26:29.288  1871  4265 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = user
09-02 15:26:29.289  1871  4265 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Personal.en_US.dict
,09-02 15:26:29.289  1871  4265 I Keyboard.Facilitator.PersonalDictionaryLoader: run() : Loaded (exit)
09-02 15:26:29.289  1871  4265 I Keyboard.Facilitator.Delight2FileSweeper: run()
09-02 15:26:29.289  1871  4265 I Keyboard.Facilitator.RecurringTaskScheduler: run()
09-02 15:26:29.289  1871  4265 I StatsUtilsManager: startPeriodStatsRecorder() : Success
09-02 15:26:29.289  1871  4265 I PeriodicStatsRecorder: shouldRecordStats() = Too Soon
,09-02 15:26:29.304  4266  4266 W System  : ClassLoader referenced unknown path: /system/app/UserDictionaryProvider/lib/arm
,09-02 15:26:29.311  1747  4311 D GFEEDBACK_SendErrorReportOperation: Error doing instant send: java.io.IOException: failed to create reports directory
,09-02 15:26:29.312  1747  4311 E GFEEDBACK_SendErrorReportOperation: Error saving report: java.io.IOException: failed to create reports directory
,09-02 15:26:29.320  1747  4311 D GFEEDBACK_SendErrorReportOperation: Error doing instant send: java.io.IOException: failed to create reports directory
,09-02 15:26:29.320  1747  4311 E GFEEDBACK_SendErrorReportOperation: Error saving report: java.io.IOException: failed to create reports directory
,09-02 15:26:29.325  4266  4293 E SQLiteDatabase: Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
09-02 15:26:29.325  4266  4293 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-02 15:26:29.325  4266  4293 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-02 15:26:29.325  4266  4293 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-02 15:26:29.325  4266  4293 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-02 15:26:29.325  4266  4293 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-02 15:26:29.325  4266  4293 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-02 15:26:29.325  4266  4293 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-02 15:26:29.325  4266  4293 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-02 15:26:29.325  4266  4293 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-02 15:26:29.325  4266  4293 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-02 15:26:29.325  4266  4293 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-02 15:26:29.325  4266  4293 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-02 15:26:29.325  4266  4293 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-02 15:26:29.325  4266  4293 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-02 15:26:29.325  4266  4293 E SQLiteDatabase: 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
09-02 15:26:29.325  4266  4293 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1596)
09-02 15:26:29.325  4266  4293 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1687)
09-02 15:26:29.325  4266  4293 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
09-02 15:26:29.325  4266  4293 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-02 15:26:29.325  4266  4293 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
09-02 15:26:29.325  4266  4293 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,09-02 15:26:29.325  4266  4293 E SQLiteOpenHelper: Couldn't open contacts2.db for writing (will try read-only):
09-02 15:26:29.325  4266  4293 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-02 15:26:29.325  4266  4293 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-02 15:26:29.325  4266  4293 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-02 15:26:29.325  4266  4293 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-02 15:26:29.325  4266  4293 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-02 15:26:29.325  4266  4293 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-02 15:26:29.325  4266  4293 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-02 15:26:29.325  4266  4293 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-02 15:26:29.325  4266  4293 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-02 15:26:29.325  4266  4293 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-02 15:26:29.325  4266  4293 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-02 15:26:29.325  4266  4293 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269),
09-02 15:26:29.325  4266  4293 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-02 15:26:29.325  4266  4293 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-02 15:26:29.325  4266  4293 E SQLiteOpenHelper: 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
09-02 15:26:29.325  4266  4293 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1596)
09-02 15:26:29.325  4266  4293 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1687)
09-02 15:26:29.325  4266  4293 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
09-02 15:26:29.325  4266  4293 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-02 15:26:29.325  4266  4293 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:148)
09-02 15:26:29.325  4266  4293 E SQLiteOpenHelper: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,09-02 15:26:29.331  4266  4312 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,09-02 15:26:29.334   872   882 I ActivityManager: Start proc 4313:com.android.musicfx/u0a18 for broadcast com.android.musicfx/.Compatibility$Receiver
,09-02 15:26:29.345   872  1372 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 4296) has died
,09-02 15:26:29.346   872  1372 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
,09-02 15:26:29.368  4266  4293 E SQLiteLog: (8) statement aborts at 43: [CREATE TABLE IF NOT EXISTS presence_db.presence (presence_data_id INTEGER PRIMARY KEY REFERENCES data(_id),protocol INTEGER NOT NULL,custom_protocol TEXT,im_handle TEXT,im_account TEXT
,09-02 15:26:29.370   872   885 I ActivityManager: Start proc 4325:com.google.android.googlequicksearchbox/u0a28 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,09-02 15:26:29.385  2183  2638 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,09-02 15:26:29.386  4313  4313 W System  : ClassLoader referenced unknown path: /system/priv-app/MusicFX/lib/arm
,09-02 15:26:29.402  4266  4312 E SQLiteDatabase: Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
09-02 15:26:29.402  4266  4312 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-02 15:26:29.402  4266  4312 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-02 15:26:29.402  4266  4312 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-02 15:26:29.402  4266  4312 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-02 15:26:29.402  4266  4312 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-02 15:26:29.402  4266  4312 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-02 15:26:29.402  4266  4312 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-02 15:26:29.402  4266  4312 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-02 15:26:29.402  4266  4312 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-02 15:26:29.402  4266  4312 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-02 15:26:29.402  4266  4312 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-02 15:26:29.402  4266  4312 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-02 15:26:29.402  4266  4312 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-02 15:26:29.402  4266  4312 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-02 15:26:29.402  4266  4312 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:191)
09-02 15:26:29.402  4266  4312 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
09-02 15:26:29.402  4266  4312 E SQLiteDatabase: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
09-02 15:26:29.402  4266  4312 E SQLiteDatabase: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
09-02 15:26:29.402  4266  4312 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
09-02 15:26:29.402  4266  4312 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
09-02 15:26:29.402  4266  4312 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
09-02 15:26:29.402  4266  4312 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-02 15:26:29.402  4266  4312 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
09-02 15:26:29.402  4266  4312 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,09-02 15:26:29.402  4266  4312 E AndroidRuntime: FATAL EXCEPTION: IntentService[VoicemailCleanupService]
09-02 15:26:29.402  4266  4312 E AndroidRuntime: Process: android.process.acore, PID: 4266
09-02 15:26:29.402  4266  4312 E AndroidRuntime: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-02 15:26:29.402  4266  4312 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-02 15:26:29.402  4266  4312 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-02 15:26:29.402  4266  4312 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-02 15:26:29.402  4266  4312 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-02 15:26:29.402  4266  4312 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-02 15:26:29.402  4266  4312 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-02 15:26:29.402  4266  4312 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-02 15:26:29.402  4266  4312 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-02 15:26:29.402  4266  4312 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-02 15:26:29.402  4266  4312 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-02 15:26:29.402  4266  4312 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-02 15:26:29.402  4266  4312 E AndroidRuntime: 	,at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-02 15:26:29.402  4266  4312 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-02 15:26:29.402  4266  4312 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:191)
09-02 15:26:29.402  4266  4312 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
09-02 15:26:29.402  4266  4312 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
09-02 15:26:29.402  4266  4312 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
09-02 15:26:29.402  4266  4312 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
09-02 15:26:29.402  4266  4312 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
09-02 15:26:29.402  4266  4312 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
09-02 15:26:29.402  4266  4312 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-02 15:26:29.402  4266  4312 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-02 15:26:29.402  4266  4312 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,09-02 15:26:29.405   872  4339 E DropBoxManagerService: Can't write: system_app_crash
09-02 15:26:29.405   872  4339 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop124.tmp: open failed: EROFS (Read-only file system)
09-02 15:26:29.405   872  4339 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-02 15:26:29.405   872  4339 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-02 15:26:29.405   872  4339 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-02 15:26:29.405   872  4339 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-02 15:26:29.405   872  4339 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-02 15:26:29.405   872  4339 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-02 15:26:29.405   872  4339 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-02 15:26:29.405   872  4339 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-02 15:26:29.405   872  4339 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-02 15:26:29.405   872  4339 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-02 15:26:29.405   872  4339 E DropBoxManagerService: 	... 5 more
,09-02 15:26:29.409  4266  4312 I Process : Sending signal. PID: 4266 SIG: 9
09-02 15:26:29.409  1528  1528 E SQLiteLog: (3850) statement aborts at 26: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
,09-02 15:26:29.409  1528  1528 D AndroidRuntime: Shutting down VM
,09-02 15:26:29.410  1528  1528 E AndroidRuntime: FATAL EXCEPTION: main
,09-02 15:26:29.410  1528  1528 E AndroidRuntime: Process: com.google.process.gapps, PID: 1528
09-02 15:26:29.410  1528  1528 E AndroidRuntime: java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-02 15:26:29.410  1528  1528 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2732)
09-02 15:26:29.410  1528  1528 E AndroidRuntime: 	at android.app.ActivityThread.-wrap14(ActivityThread.java)
09-02 15:26:29.410  1528  1528 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1421)
09-02 15:26:29.410  1528  1528 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-02 15:26:29.410  1528  1528 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-02 15:26:29.410  1528  1528 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-02 15:26:29.410  1528  1528 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
09-02 15:26:29.410  1528  1528 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-02 15:26:29.410  1528  1528 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-02 15:26:29.410  1528  1528 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-02 15:26:29.410  1528  1528 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
09-02 15:26:29.410  1528  1528 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
09-02 15:26:29.410  1528  1528 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
09-02 15:26:29.410  1528  1528 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
09-02 15:26:29.410  1528  1528 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
09-02 15:26:29.410  1528  1528 E AndroidRuntime: 	at com.google.android.gms.gcm.bg.a(SourceFile:310)
09-02 15:26:29.410  1528  1528 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
09-02 15:26:29.410  1528  1528 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
09-02 15:26:29.410  1528  1528 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2725)
09-02 15:26:29.410  1528  1528 E AndroidRuntime: 	... 8 more
,09-02 15:26:29.415  1528  1528 I Process : Sending signal. PID: 1528 SIG: 9
,09-02 15:26:29.417   872  4340 E DropBoxManagerService: Can't write: system_app_crash
09-02 15:26:29.417   872  4340 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop125.tmp: open failed: EROFS (Read-only file system)
09-02 15:26:29.417   872  4340 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-02 15:26:29.417   872  4340 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-02 15:26:29.417   872  4340 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-02 15:26:29.417   872  4340 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-02 15:26:29.417   872  4340 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-02 15:26:29.417   872  4340 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-02 15:26:29.417   872  4340 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-02 15:26:29.417   872  4340 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-02 15:26:29.417   872  4340 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-02 15:26:29.417   872  4340 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-02 15:26:29.417   872  4340 E DropBoxManagerService: 	... 5 more
,09-02 15:26:29.425   872   882 I ActivityManager: Killing 3685:com.google.android.apps.docs/u0a46 (adj 15): empty #17

```
