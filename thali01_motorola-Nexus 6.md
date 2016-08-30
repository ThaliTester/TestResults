#### Test 8326112021d0a60_thali01_motorola-Nexus 6 Logs


```
--------- beginning of main
,08-30 14:56:16.353   872  2119 D NetlinkSocketObserver: NeighborEvent{elapsedMs=113757, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
08-30 14:56:17.025  3815  3815 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
08-30 14:56:17.030  3815  3815 D AndroidRuntime: CheckJNI is OFF
08-30 14:56:17.066  3815  3815 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
08-30 14:56:17.147  3815  3815 I Radio-JNI: register_android_hardware_Radio DONE
08-30 14:56:17.172  3815  3815 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
08-30 14:56:17.179   872  1390 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-30 14:56:17.232  3815  3815 D AndroidRuntime: Shutting down VM
08-30 14:56:17.232  2065  2079 W SearchService: Abort, client detached.
08-30 14:56:17.242  2065  2065 I HotwordDetector: Closing mic
08-30 14:56:17.243  2065  2354 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@82d6fa0
08-30 14:56:17.244  2065  2363 E AudioRecord-JNI: Error -4 during AudioRecord native read
08-30 14:56:17.264   872  2023 I ActivityManager: Start proc 3824:com.test.thalitest/u0a0 for activity com.test.thalitest/.MainActivity
08-30 14:56:17.315   374  2365 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
08-30 14:56:17.317   374  2365 D audio_hw_primary: disable_snd_device: snd_device(61: voice-rec-mic)
08-30 14:56:17.326   374  1274 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
08-30 14:56:17.331  2065  2361 I MicroRecognitionRnrImpl: Detection finished
08-30 14:56:17.332  2065  2357 I MicroRecognitionRnrImpl: Stopping hotword detection.
08-30 14:56:17.367  3824  3824 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
08-30 14:56:17.389  3824  3824 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
08-30 14:56:17.396  3824  3824 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 4798-4801)
08-30 14:56:17.396  3824  3824 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-30 14:56:17.413  3824  3824 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {d0787a}
08-30 14:56:17.414  3824  3824 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-30 14:56:17.415  3824  3824 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
08-30 14:56:17.426  3824  3824 I BrowserStartupController: Initializing chromium process, singleProcess=true
08-30 14:56:17.430  3824  3824 E SysUtils: ApplicationContext is null in ApplicationStatus
08-30 14:56:17.456  3824  3824 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
08-30 14:56:17.472  3824  3824 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,08-30 14:56:17.472  3824  3824 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-30 14:56:17.472  3824  3824 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-30 14:56:17.472  3824  3824 I Adreno  : Build Date                       : 10/20/15
08-30 14:56:17.472  3824  3824 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-30 14:56:17.472  3824  3824 I Adreno  : Local Branch                     : M14
08-30 14:56:17.472  3824  3824 I Adreno  : Remote Branch                    : 
08-30 14:56:17.472  3824  3824 I Adreno  : Remote Branch                    : 
08-30 14:56:17.472  3824  3824 I Adreno  : Reconstruct Branch               : 
08-30 14:56:17.552   872   889 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@f4b0d59:true
08-30 14:56:17.595  3824  3824 W AwContents: onDetachedFromWindow called when already detached. Ignoring
08-30 14:56:17.614  3824  3824 D SystemWebViewEngine: CordovaWebView is running on device made by: motorola
08-30 14:56:17.676  3824  3862 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
08-30 14:56:17.690  3824  3849 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
08-30 14:56:17.730  3824  3862 I OpenGLRenderer: Initialized EGL, version 1.4
08-30 14:56:17.760  1889  1889 I Keyboard.Facilitator: onFinishInput()
08-30 14:56:17.795   872   890 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +554ms
08-30 14:56:17.836  3824  3824 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 3824
08-30 14:56:17.933  3824  3824 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
08-30 14:56:18.076   872  1982 I ActivityManager: Killing 3261:com.google.android.gm/u0a78 (adj 15): empty #17
08-30 14:56:18.114   872  1982 I ActivityManager: Killing 3160:com.google.android.apps.maps/u0a65 (adj 15): empty #18
08-30 14:56:18.238  3824  3866 D jxcore_app_log: JniHelper::setJavaVM(0xb4d7c000), pthread_self() = -1699542736
08-30 14:56:18.246  3824  3866 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-30 14:56:18.246  3824  3866 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-30 14:56:18.246  3824  3866 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-30 14:56:18.246  3824  3866 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-30 14:56:18.246  3824  3866 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
08-30 14:56:18.246  3824  3866 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@78eaede added. We now have 1 listener(s)
08-30 14:56:18.249  3824  3866 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: F8:CF:C5:D9:E5:61
08-30 14:56:18.253  3824  3866 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-30 14:56:18.253  3824  3866 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-30 14:56:18.253  3824  3866 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-30 14:56:18.268  3824  3866 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-30 14:56:18.268  3824  3866 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-30 14:56:18.268  3824  3866 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-30 14:56:18.268  3824  3866 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: F8:CF:C5:D9:E5:61
08-30 14:56:18.268  3824  3866 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-30 14:56:18.268  3824  3866 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-30 14:56:18.268  3824  3866 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-30 14:56:18.268  3824  3866 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-30 14:56:18.268  3824  3866 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-30 14:56:18.268  3824  3866 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-30 14:56:18.268  3824  3866 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-30 14:56:18.268  3824  3866 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-30 14:56:18.268  3824  3866 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-30 14:56:18.268  3824  3866 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
08-30 14:56:18.268  3824  3866 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9b6d2d5 added. We now have 1 listener(s)
08-30 14:56:18.269  3824  3866 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 14:56:18.273   872  1305 D WifiService: New client listening to asynchronous messages
08-30 14:56:18.273  3824  3866 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-30 14:56:18.273  3824  3866 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
08-30 14:56:18.273  3824  3866 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-30 14:56:18.274  3824  3866 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-30 14:56:18.275  3824  3866 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
08-30 14:56:18.280  3824  3866 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 14:56:18.280  3824  3866 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is F8:CF:C5:D9:E5:61
08-30 14:56:18.287  3824  3866 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
08-30 14:56:18.287  3824  3866 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 14:56:18.287  3824  3866 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 14:56:18.287  3824  3866 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 14:56:18.287  3824  3866 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 14:56:18.287  3824  3866 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 14:56:18.287  3824  3866 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 14:56:18.287  3824  3866 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 14:56:18.287  3824  3866 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-30 14:56:18.287  3824  3866 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-30 14:56:18.287  3824  3866 D io.jxcore.node.ConnectivityMonitor: start: OK
08-30 14:56:18.288  3824  3866 I io.jxcore.node.LifeCycleMonitor: start: OK
08-30 14:56:18.462  3824  3824 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 14:56:18.466  3824  3824 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 14:56:18.471  3824  3824 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-30 14:56:19.196  3824  3873 W jxcore-log: Initializing JXcore engine
,08-30 14:56:19.197  3824  3873 W jxcore-log: JXcore engine is ready
,08-30 14:56:19.233  3873  3873 W Thread-330: type=1400 audit(0.0:5): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=8932 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,08-30 14:56:19.233  3873  3873 W Thread-330: type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[11738]" dev="sockfs" ino=11738 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,08-30 14:56:19.233  3873  3873 W Thread-330: type=1400 audit(0.0:7): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,08-30 14:56:19.233  3873  3873 W Thread-330: type=1400 audit(0.0:8): avc: denied { ioctl } for path="socket:[26778]" dev="sockfs" ino=26778 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,08-30 14:56:19.248  3824  3873 W jxcore-log: Starting JXcore engine
,08-30 14:56:19.329  3824  3873 W jxcore-log: Platform android
08-30 14:56:19.329  3824  3873 W jxcore-log: 
,08-30 14:56:19.329  3824  3873 W jxcore-log: Process ARCH arm
08-30 14:56:19.329  3824  3873 W jxcore-log: 
,08-30 14:56:19.604  3824  3873 I jxcore-log: JXcore Cordova bridge is ready!
08-30 14:56:19.604  3824  3873 I jxcore-log: 
,08-30 14:56:19.604  3824  3873 W jxcore-log: JXcore engine is started
,08-30 14:56:19.613  3824  3866 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,08-30 14:56:19.615  3824  3824 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-30 14:56:26.701   872  1302 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,08-30 14:56:27.517  1494  1494 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-30 14:56:27.520  1494  1494 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-30 14:56:27.522  1494  1494 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-30 14:56:27.535  1494  2307 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,08-30 14:56:27.535  1494  2307 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
08-30 14:56:27.535  1494  2307 I GLSUser : [GLSUser] Extracting token using key: Auth
08-30 14:56:27.536  1494  2307 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-30 14:56:27.545  3569  3569 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,08-30 14:56:27.546  3569  3569 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
08-30 14:56:27.546  3569  3569 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 3.
,08-30 14:56:29.358  3824  3873 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-30 14:56:29.358  3824  3873 I jxcore-log: 
,08-30 14:56:29.360  3824  3873 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-30 14:56:29.360  3824  3873 I jxcore-log: 
,08-30 14:56:29.370  3824  3873 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 14:56:29.370  3824  3873 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 14:56:29.370  3824  3873 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 14:56:29.370  3824  3873 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 14:56:29.370  3824  3873 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 14:56:29.370  3824  3873 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 14:56:29.370  3824  3873 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 14:56:29.370  3824  3873 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-30 14:56:29.377  3824  3873 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-30 14:56:29.379  3824  3873 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-30 14:56:29.379  3824  3873 I jxcore-log: 
,08-30 14:56:29.381  3824  3873 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-30 14:56:29.381  3824  3873 I jxcore-log: 
,08-30 14:56:29.875  3824  3873 D executeNativeTests: Running unit tests
,08-30 14:56:29.934  3824  3873 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-30 14:56:29.934  3824  3873 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@30b122e added. We now have 2 listener(s)
,08-30 14:56:29.935  3824  3873 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-30 14:56:29.935  3824  3873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-30 14:56:29.935  3824  3873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-30 14:56:29.935  3824  3873 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-30 14:56:29.936  3824  3873 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8d4f1cf added. We now have 2 listener(s)
08-30 14:56:29.936  3824  3873 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 14:56:29.936  3824  3873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-30 14:56:29.940  3824  3873 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-30 14:56:29.958  3824  3873 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 14:56:29.958  3824  3873 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 14:56:29.958  3824  3873 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 14:56:29.958  3824  3873 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 14:56:29.958  3824  3873 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 14:56:29.958  3824  3873 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 14:56:29.958  3824  3873 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 14:56:29.958  3824  3873 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-30 14:56:29.961  3824  3873 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-30 14:56:29.961  3824  3873 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-30 14:56:29.963  3824  3873 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,08-30 14:56:29.965  3824  3873 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-30 14:56:29.965  3824  3873 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-30 14:56:29.967  3824  3873 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
,08-30 14:56:29.968  3824  3873 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
,08-30 14:56:29.968  3824  3873 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-30 14:56:29.968  3824  3873 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-30 14:56:29.968  3824  3873 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-30 14:56:29.968  3824  3873 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 14:56:29.968  3824  3824 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 14:56:29.969  3824  3873 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-30 14:56:29.969  3824  3873 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 14:56:29.969  3824  3873 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 14:56:29.970  3824  3873 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-30 14:56:29.970  3824  3873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 14:56:29.970  3824  3873 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-30 14:56:29.970  3824  3873 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@30b122e removed from the list
08-30 14:56:29.970  3824  3873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-30 14:56:29.970  3824  3873 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8d4f1cf removed from the list
08-30 14:56:29.974  3824  3824 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 14:56:29.975  3824  3873 D io.jxcore.node.ConnectivityMonitor: stop
08-30 14:56:29.975  3824  3873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-30 14:56:29.975  3824  3873 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 14:56:29.975  3824  3873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 14:56:29.977  3824  3873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising,
08-30 14:56:29.977  3824  3873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 14:56:29.978  3824  3873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-30 14:56:29.978  3824  3873 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8d4f1cf not in the list
,08-30 14:56:29.984  3824  3873 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
,08-30 14:56:29.985  3824  3873 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-30 14:56:29.986  3824  3873 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 14:56:29.986  3824  3873 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-30 14:56:29.987  3824  3873 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 14:56:29.987  3824  3873 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 14:56:29.987  3824  3873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 14:56:29.987  3824  3873 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@30b122e not in the list
08-30 14:56:29.987  3824  3873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose,
08-30 14:56:29.987  3824  3873 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8d4f1cf not in the list
08-30 14:56:29.988  3824  3873 D io.jxcore.node.ConnectivityMonitor: stop
,08-30 14:56:29.988  3824  3873 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 14:56:29.988  3824  3873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 14:56:29.988  3824  3873 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 14:56:29.988  3824  3873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-30 14:56:29.990  3824  3873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 14:56:29.990  3824  3873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-30 14:56:29.990  3824  3873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 14:56:29.990  3824  3873 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8d4f1cf not in the list
,08-30 14:56:30.003  3824  3873 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,08-30 14:56:30.003  3824  3873 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-30 14:56:30.003  3824  3873 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-30 14:56:30.003  3824  3873 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
,08-30 14:56:30.003  3824  3873 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-30 14:56:30.003  3824  3873 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-30 14:56:30.003  3824  3873 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-30 14:56:30.003  3824  3873 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
,08-30 14:56:30.004  3824  3873 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-30 14:56:30.004  3824  3873 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-30 14:56:30.004  3824  3873 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
,08-30 14:56:30.004  3824  3873 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-30 14:56:30.004  3824  3873 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-30 14:56:30.004  3824  3873 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
,08-30 14:56:30.004  3824  3873 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-30 14:56:30.004  3824  3873 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-30 14:56:30.004  3824  3873 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-30 14:56:30.004  3824  3873 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
,08-30 14:56:30.004  3824  3873 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-30 14:56:30.004  3824  3873 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-30 14:56:30.004  3824  3873 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
,08-30 14:56:30.004  3824  3873 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-30 14:56:30.005  3824  3873 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-30 14:56:30.005  3824  3873 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-30 14:56:30.005  3824  3873 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
,08-30 14:56:30.005  3824  3873 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-30 14:56:30.005  3824  3873 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-30 14:56:30.005  3824  3873 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-30 14:56:30.005  3824  3873 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
,08-30 14:56:30.005  3824  3873 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-30 14:56:30.005  3824  3873 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
,08-30 14:56:30.005  3824  3873 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 14:56:30.005  3824  3873 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 14:56:30.005  3824  3873 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 14:56:30.006  3824  3873 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 14:56:30.006  3824  3873 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 14:56:30.006  3824  3873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-30 14:56:30.006  3824  3873 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@30b122e not in the list
08-30 14:56:30.006  3824  3873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 14:56:30.006  3824  3873 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8d4f1cf not in the list
08-30 14:56:30.006  3824  3873 D io.jxcore.node.ConnectivityMonitor: stop
08-30 14:56:30.006  3824  3873 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 14:56:30.006  3824  3873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-30 14:56:30.006  3824  3873 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 14:56:30.006  3824  3873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 14:56:30.008  3824  3873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 14:56:30.008  3824  3873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 14:56:30.008  3824  3873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 14:56:30.008  3824  3873 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8d4f1cf not in the list
08-30 14:56:30.009  3824  3873 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,08-30 14:56:30.011  3824  3873 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 14:56:30.015  3824  3873 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 14:56:30.015  3824  3873 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 14:56:30.015  3824  3873 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 14:56:30.015  3824  3873 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 14:56:30.015  3824  3873 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 14:56:30.015  3824  3873 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 14:56:30.015  3824  3873 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 14:56:30.015  3824  3873 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-30 14:56:30.017  3824  3873 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-30 14:56:30.017  3824  3873 D io.jxcore.node.ConnectivityMonitor: start: OK
08-30 14:56:30.018  3824  3873 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-30 14:56:30.018  3824  3873 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,08-30 14:56:30.018  3824  3873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-30 14:56:30.018  3824  3873 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 14:56:30.018  3824  3873 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-30 14:56:30.020  3824  3824 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 14:56:30.022  3824  3873 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-30 14:56:30.022  3824  3873 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-30 14:56:30.026  3824  3824 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 14:56:30.027  3824  3873 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-30 14:56:30.029  3824  3873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,08-30 14:56:30.030  3824  3873 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-30 14:56:30.033  3824  3873 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
,08-30 14:56:30.036  3824  3873 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
,08-30 14:56:30.036  3824  3873 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-30 14:56:30.036  3824  3873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-30 14:56:30.037  3824  3873 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-30 14:56:30.038  3824  3873 D BluetoothAdapter: STATE_ON
,08-30 14:56:30.044  2712  2725 D BtGatt.GattService: registerClient() - UUID=9244e48e-63b7-4e42-acb0-1d054477ed99
,08-30 14:56:30.045  2712  2763 D BtGatt.GattService: onClientRegistered() - UUID=9244e48e-63b7-4e42-acb0-1d054477ed99, clientIf=5
,08-30 14:56:30.045  3824  3835 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,08-30 14:56:30.046  2712  2930 D BtGatt.GattService: start scan with filters
,08-30 14:56:30.049  3824  3873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-30 14:56:30.049  2712  2768 D BtGatt.ScanManager: handling starting scan
,08-30 14:56:30.049  3824  3873 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-30 14:56:30.049  3824  3873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,08-30 14:56:30.049  3824  3873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-30 14:56:30.050  2712  2768 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@cadc134
,08-30 14:56:30.053  3824  3873 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-30 14:56:30.054  3824  3873 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-30 14:56:30.054  3824  3824 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-30 14:56:30.057  3824  3873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-30 14:56:30.057  2712  2763 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,08-30 14:56:30.058  2712  2763 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-30 14:56:30.058  2712  2768 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
08-30 14:56:30.060  3824  3873 I io.jxcore.node.ConnectionHelper: start: OK
,08-30 14:56:30.062  3824  3873 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 14:56:30.062  3824  3873 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-30 14:56:30.062  3824  3873 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-30 14:56:30.062  3824  3873 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-30 14:56:30.062  3824  3873 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 14:56:30.062  3824  3873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-30 14:56:30.062  3824  3873 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,08-30 14:56:30.062  3824  3873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-30 14:56:30.063  3824  3873 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-30 14:56:30.063  3824  3873 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-30 14:56:30.063  2712  2763 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,08-30 14:56:30.063  2712  2763 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-30 14:56:30.063  3824  3873 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-30 14:56:30.063  3824  3873 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-30 14:56:30.063  2712  2768 D BtGatt.ScanManager: Starting BLE batch scan
08-30 14:56:30.063  2712  2768 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-30 14:56:30.064  3824  3873 D BluetoothAdapter: STATE_ON
08-30 14:56:30.064  2712  2725 D BtGatt.GattService: stopScan() - queue size =1
,08-30 14:56:30.065  2712  2930 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-30 14:56:30.065  3824  3873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-30 14:56:30.066  3824  3873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,08-30 14:56:30.066  3824  3873 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-30 14:56:30.066  3824  3873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-30 14:56:30.066  3824  3873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-30 14:56:30.067  3824  3873 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-30 14:56:30.068  3824  3873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-30 14:56:30.068  3824  3873 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-30 14:56:30.068  3824  3873 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-30 14:56:30.068  3824  3873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 14:56:30.069  3824  3873 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-30 14:56:30.069  3824  3824 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-30 14:56:30.069  3824  3873 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 14:56:30.069  3824  3873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 14:56:30.069  3824  3824 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-30 14:56:30.069  3824  3873 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@30b122e not in the list
08-30 14:56:30.070  3824  3873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 14:56:30.070  3824  3873 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8d4f1cf not in the list
08-30 14:56:30.070  3824  3873 D io.jxcore.node.ConnectivityMonitor: stop
08-30 14:56:30.070  3824  3873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-30 14:56:30.070  3824  3824 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-30 14:56:30.070  3824  3873 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-30 14:56:30.071  3824  3873 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 14:56:30.072  2712  2763 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-30 14:56:30.072  2712  2763 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-30 14:56:30.076  3824  3873 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 14:56:30.076  3824  3873 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 14:56:30.076  3824  3873 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 14:56:30.076  3824  3873 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 14:56:30.076  3824  3873 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 14:56:30.076  3824  3873 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 14:56:30.076  3824  3873 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 14:56:30.076  3824  3873 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-30 14:56:30.077  3824  3873 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-30 14:56:30.077  2712  2763 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,08-30 14:56:30.077  3824  3873 D io.jxcore.node.ConnectivityMonitor: start: OK
08-30 14:56:30.077  2712  2763 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-30 14:56:30.077  3824  3873 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-30 14:56:30.077  3824  3873 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,08-30 14:56:30.077  3824  3873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-30 14:56:30.077  3824  3873 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-30 14:56:30.077  3824  3873 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-30 14:56:30.079  3824  3824 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 14:56:30.081  3824  3873 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-30 14:56:30.081  3824  3873 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-30 14:56:30.083  3824  3873 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-30 14:56:30.083  3824  3824 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 14:56:30.084  3824  3873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-30 14:56:30.084  3824  3873 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-30 14:56:30.087  2712  2763 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-30 14:56:30.087  2712  2763 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-30 14:56:30.087  2712  2768 D BtGatt.ScanManager: stopping BLe Batch
,08-30 14:56:30.087  3824  3873 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-30 14:56:30.087  3824  3873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-30 14:56:30.087  3824  3873 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-30 14:56:30.088  3824  3873 D BluetoothAdapter: STATE_ON
,08-30 14:56:30.090  2712  2726 D BtGatt.GattService: registerClient() - UUID=80f06467-aafd-41c3-ba48-a16083e636c6
,08-30 14:56:30.091  2712  2763 D BtGatt.GattService: onClientRegistered() - UUID=80f06467-aafd-41c3-ba48-a16083e636c6, clientIf=5
08-30 14:56:30.091  3824  3836 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,08-30 14:56:30.091  2712  2931 D BtGatt.GattService: start scan with filters
,08-30 14:56:30.092  2712  2763 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-30 14:56:30.092  2712  2763 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-30 14:56:30.093  2712  2768 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-30 14:56:30.095  3824  3873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-30 14:56:30.095  3824  3873 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-30 14:56:30.095  3824  3873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,08-30 14:56:30.095  3824  3873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-30 14:56:30.097  3824  3873 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-30 14:56:30.097  3824  3873 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-30 14:56:30.097  3824  3824 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-30 14:56:30.097  2712  2763 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-30 14:56:30.098  2712  2763 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-30 14:56:30.098  3824  3873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
08-30 14:56:30.099  3824  3873 I io.jxcore.node.ConnectionHelper: start: OK
08-30 14:56:30.100  2712  2768 D BtGatt.ScanManager: handling starting scan
,08-30 14:56:30.101  3824  3873 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-30 14:56:30.101  3824  3873 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-30 14:56:30.102  3824  3873 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-30 14:56:30.102  3824  3873 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,08-30 14:56:30.102  3824  3873 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 14:56:30.102  3824  3873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-30 14:56:30.102  3824  3873 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-30 14:56:30.102  3824  3873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-30 14:56:30.102  3824  3873 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-30 14:56:30.102  3824  3873 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode,
08-30 14:56:30.102  3824  3873 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-30 14:56:30.102  3824  3873 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-30 14:56:30.103  3824  3873 D BluetoothAdapter: STATE_ON
08-30 14:56:30.103  2712  2725 D BtGatt.GattService: stopScan() - queue size =1
,08-30 14:56:30.105  2712  2930 D BtGatt.GattService: unregisterClient() - clientIf=5
08-30 14:56:30.105  3824  3873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-30 14:56:30.105  3824  3873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-30 14:56:30.105  3824  3873 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-30 14:56:30.105  3824  3873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED],
08-30 14:56:30.106  3824  3873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-30 14:56:30.106  3824  3873 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-30 14:56:30.106  3824  3873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-30 14:56:30.106  3824  3873 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-30 14:56:30.106  3824  3873 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-30 14:56:30.107  3824  3873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-30 14:56:30.108  3824  3873 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 14:56:30.108  3824  3873 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 14:56:30.108  3824  3824 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false,
08-30 14:56:30.108  3824  3873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 14:56:30.108  2712  2763 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,08-30 14:56:30.108  3824  3824 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-30 14:56:30.108  3824  3873 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@30b122e not in the list
08-30 14:56:30.108  3824  3824 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-30 14:56:30.108  2712  2763 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-30 14:56:30.108  3824  3873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 14:56:30.108  3824  3873 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8d4f1cf not in the list
,08-30 14:56:30.108  3824  3873 D io.jxcore.node.ConnectivityMonitor: stop
08-30 14:56:30.108  3824  3873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 14:56:30.109  2712  2768 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
08-30 14:56:30.109  3824  3873 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-30 14:56:30.109  3824  3873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 14:56:30.110  3824  3873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 14:56:30.110  3824  3873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 14:56:30.110  3824  3873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-30 14:56:30.110  3824  3873 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8d4f1cf not in the list
08-30 14:56:30.111  3824  3873 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-30 14:56:30.113  3824  3873 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-30 14:56:30.117  3824  3873 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 14:56:30.117  3824  3873 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 14:56:30.117  3824  3873 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 14:56:30.117  3824  3873 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 14:56:30.117  3824  3873 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 14:56:30.117  3824  3873 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 14:56:30.117  3824  3873 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 14:56:30.117  3824  3873 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-30 14:56:30.117  2712  2763 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-30 14:56:30.118  2712  2763 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-30 14:56:30.118  2712  2768 D BtGatt.ScanManager: Starting BLE batch scan
08-30 14:56:30.118  2712  2768 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-30 14:56:30.119  3824  3873 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-30 14:56:30.119  3824  3873 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-30 14:56:30.120  3824  3873 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-30 14:56:30.120  3824  3873 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-30 14:56:30.120  3824  3873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-30 14:56:30.120  3824  3873 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 14:56:30.120  3824  3873 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-30 14:56:30.121  3824  3824 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 14:56:30.123  3824  3824 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 14:56:30.125  3824  3873 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-30 14:56:30.125  3824  3873 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-30 14:56:30.129  3824  3873 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-30 14:56:30.129  3824  3873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-30 14:56:30.130  3824  3873 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-30 14:56:30.132  3824  3873 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-30 14:56:30.132  3824  3873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-30 14:56:30.132  3824  3873 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-30 14:56:30.132  2712  2763 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-30 14:56:30.132  2712  2763 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-30 14:56:30.133  3824  3873 D BluetoothAdapter: STATE_ON
,08-30 14:56:30.135  2712  2931 D BtGatt.GattService: registerClient() - UUID=d4c9c8a8-9ad0-41e7-9192-e49d7307bc76
,08-30 14:56:30.135  2712  2763 D BtGatt.GattService: onClientRegistered() - UUID=d4c9c8a8-9ad0-41e7-9192-e49d7307bc76, clientIf=5
08-30 14:56:30.135  3824  3863 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,08-30 14:56:30.135  2712  2928 D BtGatt.GattService: start scan with filters
,08-30 14:56:30.138  3824  3873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING,
08-30 14:56:30.138  3824  3873 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-30 14:56:30.138  3824  3873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,08-30 14:56:30.138  3824  3873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-30 14:56:30.140  2712  2763 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-30 14:56:30.140  2712  2763 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-30 14:56:30.141  3824  3873 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-30 14:56:30.141  3824  3824 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-30 14:56:30.141  3824  3873 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-30 14:56:30.143  3824  3873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-30 14:56:30.145  3824  3873 I io.jxcore.node.ConnectionHelper: start: OK
,08-30 14:56:30.145  3824  3873 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 14:56:30.145  3824  3873 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,08-30 14:56:30.145  3824  3873 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-30 14:56:30.146  3824  3873 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-30 14:56:30.146  3824  3873 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-30 14:56:30.146  3824  3873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-30 14:56:30.146  3824  3873 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-30 14:56:30.146  3824  3873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,08-30 14:56:30.146  3824  3873 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-30 14:56:30.146  3824  3873 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-30 14:56:30.146  3824  3873 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,08-30 14:56:30.146  3824  3873 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-30 14:56:30.147  3824  3873 D BluetoothAdapter: STATE_ON
08-30 14:56:30.148  2712  2763 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-30 14:56:30.148  2712  2763 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-30 14:56:30.148  2712  2931 D BtGatt.GattService: stopScan() - queue size =0
08-30 14:56:30.148  2712  2768 D BtGatt.ScanManager: stopping BLe Batch
08-30 14:56:30.149  2712  2928 D BtGatt.GattService: unregisterClient() - clientIf=5
08-30 14:56:30.149  3824  3873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-30 14:56:30.149  3824  3873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-30 14:56:30.151  3824  3873 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-30 14:56:30.151  3824  3873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-30 14:56:30.151  3824  3873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED],
,08-30 14:56:30.152  3824  3873 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-30 14:56:30.152  3824  3873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-30 14:56:30.152  3824  3873 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-30 14:56:30.152  3824  3873 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-30 14:56:30.152  3824  3873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 14:56:30.154  3824  3824 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-30 14:56:30.154  3824  3824 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-30 14:56:30.154  3824  3824 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false,
08-30 14:56:30.154  3824  3873 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 14:56:30.154  3824  3873 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-30 14:56:30.154  3824  3873 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-30 14:56:30.154  3824  3873 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 14:56:30.155  3824  3873 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 14:56:30.155  3824  3873 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-30 14:56:30.155  3824  3873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 14:56:30.155  3824  3873 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@30b122e not in the list
08-30 14:56:30.155  3824  3873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 14:56:30.155  3824  3873 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8d4f1cf not in the list
,08-30 14:56:30.155  3824  3873 D io.jxcore.node.ConnectivityMonitor: stop
08-30 14:56:30.155  3824  3873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 14:56:30.155  2712  2763 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-30 14:56:30.155  2712  2763 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0,
08-30 14:56:30.156  2712  2768 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
08-30 14:56:30.156  3824  3873 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-30 14:56:30.156  3824  3873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 14:56:30.156  3824  3873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-30 14:56:30.156  3824  3873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 14:56:30.156  3824  3873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 14:56:30.156  3824  3873 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8d4f1cf not in the list,
08-30 14:56:30.157  3824  3873 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
08-30 14:56:30.157  3824  3873 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 14:56:30.157  3824  3873 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-30 14:56:30.157  3824  3873 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 14:56:30.157  3824  3873 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 14:56:30.158  3824  3873 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 14:56:30.158  3824  3873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-30 14:56:30.158  3824  3873 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@30b122e not in the list
08-30 14:56:30.158  3824  3873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 14:56:30.158  3824  3873 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8d4f1cf not in the list
08-30 14:56:30.158  3824  3873 D io.jxcore.node.ConnectivityMonitor: stop,
08-30 14:56:30.158  3824  3873 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 14:56:30.158  3824  3873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 14:56:30.158  3824  3873 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-30 14:56:30.158  3824  3873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 14:56:30.160  3824  3873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 14:56:30.160  3824  3873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-30 14:56:30.160  3824  3873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 14:56:30.160  3824  3873 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8d4f1cf not in the list
08-30 14:56:30.161  3824  3873 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-30 14:56:30.161  3824  3873 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections,
08-30 14:56:30.161  3824  3873 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 14:56:30.161  3824  3873 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 14:56:30.161  3824  3873 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 14:56:30.161  3824  3873 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-30 14:56:30.161  3824  3873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 14:56:30.161  3824  3873 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@30b122e not in the list
08-30 14:56:30.161  3824  3873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 14:56:30.161  3824  3873 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8d4f1cf not in the list
08-30 14:56:30.161  3824  3873 D io.jxcore.node.ConnectivityMonitor: stop
,08-30 14:56:30.161  3824  3873 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 14:56:30.161  3824  3873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 14:56:30.162  3824  3873 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 14:56:30.162  3824  3873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-30 14:56:30.162  2712  2763 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-30 14:56:30.162  2712  2763 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-30 14:56:30.163  3824  3873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 14:56:30.163  3824  3873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 14:56:30.163  3824  3873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 14:56:30.163  2712  2768 D BtGatt.ScanManager: handling starting scan
08-30 14:56:30.163  3824  3873 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8d4f1cf not in the list
,08-30 14:56:30.164  3824  3873 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
08-30 14:56:30.164  3824  3873 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 14:56:30.164  3824  3873 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 14:56:30.164  3824  3873 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 14:56:30.164  3824  3873 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 14:56:30.164  3824  3873 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 14:56:30.164  3824  3873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 14:56:30.164  3824  3873 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@30b122e not in the list
08-30 14:56:30.164  3824  3873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 14:56:30.164  3824  3873 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8d4f1cf not in the list
08-30 14:56:30.164  3824  3873 D io.jxcore.node.ConnectivityMonitor: stop
08-30 14:56:30.164  3824  3873 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 14:56:30.165  3824  3873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 14:56:30.165  3824  3873 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 14:56:30.165  3824  3873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 14:56:30.166  3824  3873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 14:56:30.166  3824  3873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 14:56:30.166  3824  3873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 14:56:30.166  3824  3873 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8d4f1cf not in the list
08-30 14:56:30.166  3824  3873 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
,08-30 14:56:30.166  3824  3873 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 14:56:30.166  3824  3873 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 14:56:30.166  3824  3873 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 14:56:30.166  3824  3873 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 14:56:30.167  3824  3873 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 14:56:30.167  3824  3873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 14:56:30.167  3824  3873 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@30b122e not in the list
08-30 14:56:30.167  3824  3873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 14:56:30.167  3824  3873 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8d4f1cf not in the list
08-30 14:56:30.167  3824  3873 D io.jxcore.node.ConnectivityMonitor: stop
08-30 14:56:30.167  3824  3873 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 14:56:30.167  3824  3873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 14:56:30.167  3824  3873 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 14:56:30.167  3824  3873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 14:56:30.168  3824  3873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 14:56:30.168  3824  3873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 14:56:30.168  3824  3873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 14:56:30.168  3824  3873 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8d4f1cf not in the list
08-30 14:56:30.168  3824  3873 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-30 14:56:30.170  2712  2763 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-30 14:56:30.170  2712  2763 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-30 14:56:30.170  3824  3873 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-30 14:56:30.170  3824  3873 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-30 14:56:30.170  2712  2768 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
08-30 14:56:30.170  3824  3873 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-30 14:56:30.170  3824  3873 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-30 14:56:30.171  3824  3873 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-30 14:56:30.172  3824  3873 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 14:56:30.172  3824  3873 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 14:56:30.172  3824  3873 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 14:56:30.172  3824  3873 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 14:56:30.172  3824  3873 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 14:56:30.172  3824  3873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 14:56:30.172  3824  3873 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@30b122e not in the list
08-30 14:56:30.172  3824  3873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 14:56:30.172  3824  3873 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8d4f1cf not in the list
08-30 14:56:30.172  3824  3873 D io.jxcore.node.ConnectivityMonitor: stop
08-30 14:56:30.173  3824  3873 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 14:56:30.173  3824  3873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 14:56:30.173  3824  3873 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 14:56:30.173  3824  3873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 14:56:30.173  3824  3873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 14:56:30.173  3824  3873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 14:56:30.173  3824  3873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 14:56:30.173  3824  3873 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8d4f1cf not in the list
08-30 14:56:30.174  3824  3873 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-30 14:56:30.174  3824  3873 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
08-30 14:56:30.174  3824  3873 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-30 14:56:30.175  2712  2763 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-30 14:56:30.175  2712  2763 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-30 14:56:30.176  2712  2768 D BtGatt.ScanManager: Starting BLE batch scan
08-30 14:56:30.176  2712  2768 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-30 14:56:30.179  3824  3873 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-30 14:56:30.180  3824  3873 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
08-30 14:56:30.180  3824  3873 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-30 14:56:30.180  3824  3873 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-30 14:56:30.180  3824  3873 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-30 14:56:30.180  3824  3873 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-30 14:56:30.180  3824  3873 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-30 14:56:30.180  3824  3873 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-30 14:56:30.180  3824  3873 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-30 14:56:30.180  3824  3873 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-30 14:56:30.181  3824  3873 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-30 14:56:30.181  3824  3873 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-30 14:56:30.181  3824  3873 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-30 14:56:30.181  3824  3873 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-30 14:56:30.181  3824  3873 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-30 14:56:30.181  3824  3873 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-30 14:56:30.181  3824  3873 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-30 14:56:30.181  3824  3873 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-30 14:56:30.181  3824  3873 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-30 14:56:30.181  3824  3873 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-30 14:56:30.182  3824  3873 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-30 14:56:30.182  3824  3873 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-30 14:56:30.182  3824  3873 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-30 14:56:30.182  3824  3873 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-30 14:56:30.182  3824  3873 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-30 14:56:30.182  3824  3873 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-30 14:56:30.182  3824  3873 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-30 14:56:30.183  3824  3873 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-30 14:56:30.183  3824  3873 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-30 14:56:30.183  3824  3873 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-30 14:56:30.183  3824  3873 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-30 14:56:30.183  3824  3873 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-30 14:56:30.184  3824  3873 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
08-30 14:56:30.184  3824  3873 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-30 14:56:30.184  3824  3873 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
08-30 14:56:30.184  3824  3873 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-30 14:56:30.184  3824  3873 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-30 14:56:30.185  3824  3873 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
08-30 14:56:30.185  3824  3873 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-30 14:56:30.185  3824  3873 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-30 14:56:30.185  3824  3873 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
08-30 14:56:30.185  2712  2763 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-30 14:56:30.185  2712  2763 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-30 14:56:30.188  3824  3873 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
08-30 14:56:30.189  3824  3873 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
08-30 14:56:30.189  3824  3873 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
08-30 14:56:30.189  3824  3873 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
08-30 14:56:30.189  3824  3873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
08-30 14:56:30.189  3824  3873 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
08-30 14:56:30.189  3824  3873 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-30 14:56:30.189  3824  3885 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 394)
08-30 14:56:30.190  3824  3873 E io.jxcore.node.ConnectionHelper: connect: Callback is null
08-30 14:56:30.190  3824  3873 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-30 14:56:30.190  3824  3873 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 14:56:30.191  3824  3873 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 14:56:30.191  2712  2763 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-30 14:56:30.191  3824  3873 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 14:56:30.191  2712  2763 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-30 14:56:30.191  3824  3873 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 14:56:30.191  3824  3885 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-30 14:56:30.191  3824  3873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 14:56:30.191  3824  3873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
08-30 14:56:30.192  3824  3873 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@30b122e not in the list
08-30 14:56:30.192  3824  3873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 14:56:30.192  3824  3873 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8d4f1cf not in the list
08-30 14:56:30.192  3824  3873 D io.jxcore.node.ConnectivityMonitor: stop
08-30 14:56:30.192  3824  3873 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 14:56:30.192  3824  3873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 14:56:30.192  3824  3873 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 14:56:30.192  3824  3873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 14:56:30.193  3824  3873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 14:56:30.193  3824  3886 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 394
08-30 14:56:30.193  3824  3873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 14:56:30.193  3824  3886 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Trying to close the Bluetooth socket... (thread ID: 394)
08-30 14:56:30.193  3824  3873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 14:56:30.193  3824  3873 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8d4f1cf not in the list
08-30 14:56:30.193  3824  3885 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 394)
08-30 14:56:30.194  3824  3873 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
08-30 14:56:30.194  2712  2908 E bt_btif_sock_rfcomm: btsock_rfc_signaled socket signaled for read while disconnected, slot: 4, channel: -1
08-30 14:56:30.194  3824  3886 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Bluetooth socket closed (thread ID: 394)
08-30 14:56:30.195  3824  3873 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 14:56:30.196  3824  3873 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 14:56:30.196  3824  3873 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 14:56:30.196  3824  3873 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 14:56:30.197  3824  3873 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 14:56:30.197  3824  3873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 14:56:30.197  3824  3873 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@30b122e not in the list
08-30 14:56:30.197  3824  3873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 14:56:30.197  2712  2763 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-30 14:56:30.197  3824  3873 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8d4f1cf not in the list
08-30 14:56:30.197  2712  2763 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-30 14:56:30.197  3824  3873 D io.jxcore.node.ConnectivityMonitor: stop
08-30 14:56:30.197  3824  3873 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 14:56:30.197  2712  2768 D BtGatt.ScanManager: stopping BLe Batch
08-30 14:56:30.197  3824  3873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 14:56:30.197  3824  3873 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 14:56:30.197  3824  3873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 14:56:30.198  3824  3873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 14:56:30.198  3824  3873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 14:56:30.198  3824  3873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 14:56:30.198  3824  3873 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8d4f1cf not in the list
08-30 14:56:30.199  3824  3873 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
08-30 14:56:30.199  3824  3873 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 14:56:30.199  3824  3873 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 14:56:30.199  3824  3873 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 14:56:30.199  3824  3873 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 14:56:30.199  3824  3873 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 14:56:30.200  3824  3873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 14:56:30.200  3824  3873 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@30b122e not in the list
08-30 14:56:30.200  3824  3873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 14:56:30.200  3824  3873 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8d4f1cf not in the list
08-30 14:56:30.200  3824  3873 D io.jxcore.node.ConnectivityMonitor: stop
08-30 14:56:30.200  3824  3873 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 14:56:30.200  3824  3873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 14:56:30.200  3824  3873 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 14:56:30.200  3824  3873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 14:56:30.201  3824  3873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 14:56:30.201  3824  3873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 14:56:30.201  3824  3873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 14:56:30.201  3824  3873 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8d4f1cf not in the list
08-30 14:56:30.202  3824  3873 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
08-30 14:56:30.202  3824  3873 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
08-30 14:56:30.202  3824  3873 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-30 14:56:30.202  3824  3873 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
08-30 14:56:30.202  3824  3873 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-30 14:56:30.202  3824  3873 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
08-30 14:56:30.202  3824  3873 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-30 14:56:30.202  3824  3873 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
08-30 14:56:30.202  3824  3873 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-30 14:56:30.202  3824  3873 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
08-30 14:56:30.202  3824  3873 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-30 14:56:30.202  3824  3873 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
08-30 14:56:30.202  3824  3873 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 14:56:30.203  3824  3873 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 14:56:30.203  3824  3873 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 14:56:30.203  3824  3873 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 14:56:30.203  3824  3873 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 14:56:30.203  3824  3873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 14:56:30.203  3824  3873 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@30b122e not in the list
08-30 14:56:30.203  3824  3873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 14:56:30.203  3824  3873 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8d4f1cf not in the list
08-30 14:56:30.203  3824  3873 D io.jxcore.node.ConnectivityMonitor: stop
08-30 14:56:30.203  3824  3873 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 14:56:30.203  3824  3873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 14:56:30.203  3824  3873 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 14:56:30.203  3824  3873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 14:56:30.204  3824  3873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 14:56:30.204  3824  3873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 14:56:30.204  3824  3873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 14:56:30.204  3824  3873 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8d4f1cf not in the list
08-30 14:56:30.204  3824  3873 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 14:56:30.204  3824  3873 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 14:56:30.204  3824  3873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 14:56:30.204  3824  3873 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@30b122e not in the list
08-30 14:56:30.204  3824  3873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 14:56:30.204  3824  3873 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8d4f1cf not in the list
08-30 14:56:30.204  3824  3873 D io.jxcore.node.ConnectivityMonitor: stop
08-30 14:56:30.205  3824  3873 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 14:56:30.205  3824  3873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 14:56:30.205  3824  3873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 14:56:30.205  3824  3873 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8d4f1cf not in the list
08-30 14:56:30.205  3824  3873 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 14:56:30.205  3824  3873 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 14:56:30.205  3824  3873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 14:56:30.205  3824  3873 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@30b122e not in the list
08-30 14:56:30.205  3824  3873 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 14:56:30.205  3824  3873 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 14:56:30.205  3824  3873 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 14:56:30.205  3824  3873 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 14:56:30.205  3824  3873 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 14:56:30.205  3824  3873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 14:56:30.205  3824  3873 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@30b122e not in the list
08-30 14:56:30.205  3824  3873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 14:56:30.206  3824  3873 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8d4f1cf not in the list
08-30 14:56:30.206  3824  3873 D io.jxcore.node.ConnectivityMonitor: stop
08-30 14:56:30.206  3824  3873 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 14:56:30.206  3824  3873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 14:56:30.206  3824  3873 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 14:56:30.206  3824  3873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 14:56:30.207  3824  3873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 14:56:30.207  3824  3873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 14:56:30.207  3824  3873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 14:56:30.207  3824  3873 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8d4f1cf not in the list
08-30 14:56:30.208  2712  2763 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-30 14:56:30.208  2712  2763 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-30 14:56:30.208  2712  2768 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
08-30 14:56:30.209  3824  3873 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
08-30 14:56:30.209  3824  3873 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 14:56:30.209  3824  3873 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
08-30 14:56:30.210  3824  3873 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
08-30 14:56:30.210  3824  3873 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
08-30 14:56:30.210  3824  3824 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
08-30 14:56:30.210  3824  3873 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
08-30 14:56:30.210  3824  3873 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-30 14:56:30.210  3824  3873 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 14:56:30.210  3824  3873 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
08-30 14:56:30.210  3824  3873 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
08-30 14:56:30.211  3824  3873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
08-30 14:56:30.211  3824  3873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 14:56:30.211  3824  3873 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
08-30 14:56:30.211  3824  3824 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
08-30 14:56:30.211  3824  3873 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@30b122e not in the list
08-30 14:56:30.211  3824  3873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 14:56:30.211  3824  3873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-30 14:56:30.211  3824  3873 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-30 14:56:30.211  3824  3873 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-30 14:56:30.211  3824  3873 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 14:56:30.211  3824  3873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 14:56:30.211  3824  3887 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-30 14:56:30.212  3824  3873 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-30 14:56:30.212  3824  3824 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-30 14:56:30.212  3824  3824 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-30 14:56:30.212  3824  3824 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-30 14:56:30.212  3824  3873 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8d4f1cf not in the list
08-30 14:56:30.213  3824  3873 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 14:56:30.213  3824  3873 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 14:56:30.213  3824  3873 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 14:56:30.213  3824  3873 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 14:56:30.213  3824  3873 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 14:56:30.213  3824  3887 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
08-30 14:56:30.213  3824  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
08-30 14:56:30.213  2712  2763 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-30 14:56:30.213  2712  2763 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-30 14:56:30.213  3824  3887 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
08-30 14:56:30.214  3824  3824 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
08-30 14:56:30.213  3824  3873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 14:56:30.214  3824  3873 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@30b122e not in the list
08-30 14:56:30.214  3824  3873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 14:56:30.214  3824  3873 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8d4f1cf not in the list
08-30 14:56:30.214  3824  3873 D io.jxcore.node.ConnectivityMonitor: stop
08-30 14:56:30.214  3824  3873 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 14:56:30.214  3824  3873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 14:56:30.215  3824  3873 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 14:56:30.215  3824  3873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 14:56:30.216  3824  3873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 14:56:30.216  3824  3873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 14:56:30.216  3824  3873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 14:56:30.216  3824  3873 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8d4f1cf not in the list
08-30 14:56:30.217  3824  3873 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
08-30 14:56:30.217  3824  3873 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-30 14:56:30.217  3824  3873 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-30 14:56:30.218  3824  3873 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-30 14:56:30.218  3824  3873 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 14:56:30.218  3824  3873 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 14:56:30.218  3824  3873 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 14:56:30.218  3824  3873 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 14:56:30.218  3824  3873 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 14:56:30.218  3824  3873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 14:56:30.218  3824  3873 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliprojec,t.p2p.btconnectorlib.ConnectionManager@30b122e not in the list
08-30 14:56:30.218  3824  3873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 14:56:30.218  3824  3873 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8d4f1cf not in the list
08-30 14:56:30.218  3824  3873 D io.jxcore.node.ConnectivityMonitor: stop
08-30 14:56:30.218  3824  3873 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 14:56:30.218  3824  3873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 14:56:30.219  3824  3873 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 14:56:30.219  3824  3873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 14:56:30.220  3824  3873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 14:56:30.220  3824  3873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 14:56:30.220  3824  3873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 14:56:30.220  3824  3873 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8d4f1cf not in the list
08-30 14:56:30.223  3824  3873 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 14:56:30.223  3824  3873 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 14:56:30.223  3824  3873 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 14:56:30.223  3824  3873 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 14:56:30.223  3824  3873 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 14:56:30.223  3824  3873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 14:56:30.223  3824  3873 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@30b122e not in the list
08-30 14:56:30.223  3824  3873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 14:56:30.224  3824  3873 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8d4f1cf not in the list
08-30 14:56:30.224  3824  3873 D io.jxcore.node.ConnectivityMonitor: stop
08-30 14:56:30.224  3824  3873 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 14:56:30.224  3824  3873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 14:56:30.224  3824  3873 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 14:56:30.224  3824  3873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 14:56:30.225  3824  3873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 14:56:30.225  3824  3873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 14:56:30.225  3824  3873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 14:56:30.225  3824  3873 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8d4f1cf not in the list
08-30 14:56:30.225  3824  3873 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 14:56:30.226  3824  3873 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 14:56:30.226  3824  3873 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 14:56:30.226  3824  3873 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 14:56:30.226  3824  3873 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 14:56:30.226  3824  3873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 14:56:30.226  3824  3873 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@30b122e not in the list
08-30 14:56:30.226  3824  3873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 14:56:30.226  3824  3873 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8d4f1cf not in the list
08-30 14:56:30.226  3824  3873 D io.jxcore.node.ConnectivityMonitor: stop
08-30 14:56:30.226  3824  3873 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 14:56:30.226  3824  3873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 14:56:30.226  3824  3873 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 14:56:30.226  3824  3873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 14:56:30.227  3824  3873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 14:56:30.227  3824  3873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 14:56:30.227  3824  3873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 14:56:30.227  3824  3873 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8d4f1cf not in the list
08-30 14:56:30.228  3824  3873 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
08-30 14:56:30.228  3824  3873 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-30 14:56:30.228  3824  3873 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
08-30 14:56:30.228  3824  3873 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-30 14:56:30.228  3824  3873 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
08-30 14:56:30.229  3824  3873 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-30 14:56:30.230  3824  3873 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-30 14:56:30.230  3824  3873 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
08-30 14:56:30.231  3824  3873 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
,08-30 14:56:30.231  3824  3873 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-30 14:56:30.231  3824  3873 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
08-30 14:56:30.231  3824  3873 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-30 14:56:30.231  3824  3873 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
08-30 14:56:30.231  3824  3873 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
08-30 14:56:30.232  3824  3873 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
08-30 14:56:30.232  3824  3873 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
08-30 14:56:30.232  3824  3873 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
08-30 14:56:30.232  3824  3873 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
08-30 14:56:30.232  3824  3873 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
08-30 14:56:30.233  3824  3873 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
08-30 14:56:30.233  3824  3873 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 14:56:30.233  3824  3873 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@8dc7219 added. We now have 2 listener(s)
08-30 14:56:30.234  3824  3873 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 14:56:30.235  3824  3873 D BluetoothAdapter: enable(): BT is already enabled..!
08-30 14:56:30.235   872  2023 D WifiService: setWifiEnabled: true pid=3824, uid=10000
08-30 14:56:30.235   872  2023 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-30 14:56:30.236  3824  3873 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 14:56:30.236  3824  3873 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@8f662de added. We now have 3 listener(s)
08-30 14:56:30.236  3824  3873 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 14:56:30.241  3824  3873 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 14:56:30.241  3824  3873 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@8bbecbf added. We now have 4 listener(s)
08-30 14:56:30.241  3824  3873 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 14:56:30.243  3824  3873 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 14:56:30.243  3824  3873 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@4e02f8c added. We now have 5 listener(s)
08-30 14:56:30.243  3824  3873 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 14:56:30.245   872  1674 D WifiService: setWifiEnabled: false pid=3824, uid=10000
08-30 14:56:30.245   872  1674 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-30 14:56:30.248  2712  2759 D BluetoothAdapterState: Current state: ON, message: 23
08-30 14:56:30.248  2712  2759 D BluetoothAdapterProperties: Setting state to 13
08-30 14:56:30.248  2712  2759 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-30 14:56:30.248  2712  2759 D BluetoothAdapterProperties: onBluetoothDisable()
08-30 14:56:30.249  2712  2759 I BluetoothAdapterState: Entering PendingCommandState
08-30 14:56:30.249  3824  3873 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 14:56:30.251  2712  2712 D BluetoothMapService: onReceive
08-30 14:56:30.251  2712  2712 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-30 14:56:30.251  2712  2712 D BluetoothMapService: STATE_TURNING_OFF
08-30 14:56:30.251  2712  2712 D BluetoothMapService: MAP Service closeService in
08-30 14:56:30.251  2712  2712 D BluetoothMapMasInstance0: MAP Service shutdown
08-30 14:56:30.251  2712  2712 D ObexServerSockets0: shutdown(block = true)
08-30 14:56:30.252  2712  2712 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-30 14:56:30.252  2712  2712 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-30 14:56:30.252  2712  2933 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
08-30 14:56:30.253  2712  2908 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
08-30 14:56:30.253  2712  2934 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
08-30 14:56:30.254  2712  2712 I BtOppRfcommListener: stopping Accept Thread
08-30 14:56:30.254  2712  3482 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-30 14:56:30.254  2712  3482 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-30 14:56:30.256  3824  3873 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 14:56:30.256  3824  3873 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 14:56:30.256  3824  3873 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 14:56:30.256  3824  3873 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 14:56:30.256  3824  3873 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 14:56:30.256  3824  3873 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 14:56:30.256  3824  3873 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 14:56:30.256  3824  3873 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 14:56:30.256  3824  3873 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-30 14:56:30.256  3824  3873 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 14:56:30.256  3824  3873 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-30 14:56:30.256  3824  3873 D io.jxcore.node.ConnectivityMonitor: start: OK
08-30 14:56:30.259  3824  3824 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 14:56:30.261  3824  3824 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 14:56:30.262  1458  1458 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-30 14:56:30.264   872  1302 D WifiStateMachine: WifiStateMachine: Leaving Connected state
08-30 14:56:30.264   872  1302 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
08-30 14:56:30.264   872  1302 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-30 14:56:30.264  3824  3824 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 14:56:30.264   872  1302 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-30 14:56:30.264  3824  3824 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 14:56:30.264  3824  3824 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 14:56:30.264  3824  3824 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 14:56:30.264  3824  3824 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 14:56:30.264  3824  3824 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 14:56:30.264  3824  3824 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 14:56:30.264  3824  3824 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 14:56:30.264  3824  3824 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-30 14:56:30.265  3824  3824 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 14:56:30.265  3824  3824 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-30 14:56:30.267  3824  3824 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 14:56:30.272   872  2121 D DhcpClient: Clearing IP address
08-30 14:56:30.272   370   870 D CommandListener: Clearing all IP addresses on wlan0
08-30 14:56:30.272   872   885 I ActivityManager: Start proc 3890:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
08-30 14:56:30.273  2712  2763 D BluetoothAdapterProperties: Scan Mode:20
08-30 14:56:30.273  2712  2759 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
08-30 14:56:30.276  3824  3824 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 14:56:30.276  2712  2712 D HeadsetService: Received stop request...Stopping profile...
08-30 14:56:30.278   872   872 D BluetoothHeadset: Proxy object disconnected
08-30 14:56:30.279  1344  1360 D BluetoothHeadset: Proxy object disconnected
08-30 14:56:30.279  1344  1344 D HeadsetProfile: Bluetooth service disconnected
08-30 14:56:30.279   872   872 D BluetoothHeadset: Proxy object disconnected
08-30 14:56:30.279   872   872 D BluetoothHeadset: Proxy object disconnected
08-30 14:56:30.279  1975  2061 D BluetoothHeadset: Proxy object disconnected
08-30 14:56:30.280  3824  3824 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 14:56:30.280  2712  2712 D A2dpService: Received stop request...Stopping profile...
08-30 14:56:30.281  2712  2913 D A2dpStateMachine: Exit Disconnected: -1
08-30 14:56:30.283  1494  2549 V NativeCrypto: Read error: ssl=0x9b6c9000: I/O error during system call, Connection timed out
08-30 14:56:30.284   370   870 D CommandListener: Setting iface cfg
08-30 14:56:30.285   872   872 D BluetoothA2dp: Proxy object disconnected
08-30 14:56:30.285  1344  1344 D BluetoothA2dp: Proxy object disconnected
08-30 14:56:30.285  2712  2712 V BluetoothAdapterState: isTurningOff()=true
08-30 14:56:30.285  2712  2712 V BluetoothAdapterState: isTurningOn()=false
,08-30 14:56:30.286  2712  2712 V BluetoothAdapterState: isBleTurningOn()=false
,08-30 14:56:30.286  2712  2712 V BluetoothAdapterState: isBleTurningOff()=false
08-30 14:56:30.286  1494  2549 V NativeCrypto: SSL shutdown failed: ssl=0x9b6c9000: I/O error during system call, Broken pipe
08-30 14:56:30.287  2712  2712 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
,08-30 14:56:30.287  2712  2712 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
,08-30 14:56:30.288  2712  2763 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
,08-30 14:56:30.288  2712  2901 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-30 14:56:30.288  2712  2901 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-30 14:56:30.288  2712  2901 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-30 14:56:30.288  2712  2712 D HidService: Received stop request...Stopping profile...
08-30 14:56:30.288  2712  2712 D HidService: Stopping Bluetooth HidService
08-30 14:56:30.289  2712  2763 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
08-30 14:56:30.289  1344  1344 D BluetoothInputDevice: Proxy object disconnected
,08-30 14:56:30.289  1344  1344 D HidProfile: Bluetooth service disconnected
,08-30 14:56:30.290   872  1306 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
,08-30 14:56:30.290   872  1306 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
,08-30 14:56:30.295   872  1302 D WifiStateMachine: Start Disconnecting Watchdog 1
08-30 14:56:30.295   872  1306 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
08-30 14:56:30.296   872  1302 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-30 14:56:30.296   396   396 E Parcel  : Reading a NULL string not supported here.
08-30 14:56:30.296  2712  2712 D HealthService: Received stop request...Stopping profile...
,08-30 14:56:30.298  2712  2712 V BluetoothAdapterState: isTurningOff()=true
08-30 14:56:30.298  2712  2712 V BluetoothAdapterState: isTurningOn()=false
08-30 14:56:30.298  2712  2712 V BluetoothAdapterState: isBleTurningOn()=false
08-30 14:56:30.298  2712  2712 V BluetoothAdapterState: isBleTurningOff()=false
08-30 14:56:30.301  2712  2901 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-30 14:56:30.302  2712  2901 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-30 14:56:30.302  2712  2901 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-30 14:56:30.302  2712  2901 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-30 14:56:30.302  2712  2901 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-30 14:56:30.302  2712  2901 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-30 14:56:30.302  2712  2763 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
08-30 14:56:30.303  2712  2712 D PanService: Received stop request...Stopping profile...
08-30 14:56:30.304  2712  2712 D BluetoothMapService: Received stop request...Stopping profile...
08-30 14:56:30.304  2712  2712 D BluetoothMapService: stop()
08-30 14:56:30.304  2712  2712 D BluetoothMapAppObserver: deinitObservers()
08-30 14:56:30.304  2712  2712 D BluetoothMapAppObserver: removeReceiver()
08-30 14:56:30.305   370   870 D CommandListener: Clearing all IP addresses on wlan0
,08-30 14:56:30.305  1344  1344 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-30 14:56:30.305  1344  1344 D PanProfile: Bluetooth service disconnected
08-30 14:56:30.306  1344  1344 D BluetoothMap: Proxy object disconnected
,08-30 14:56:30.306  1344  1344 D MapProfile: Bluetooth service disconnected
08-30 14:56:30.306  2712  2712 V BluetoothAdapterState: isTurningOff()=true
08-30 14:56:30.306  2712  2712 V BluetoothAdapterState: isTurningOn()=false
08-30 14:56:30.306  2712  2712 V BluetoothAdapterState: isBleTurningOn()=false
,08-30 14:56:30.306  2712  2712 V BluetoothAdapterState: isBleTurningOff()=false
08-30 14:56:30.306  2712  2712 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-30 14:56:30.306  2712  2712 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-30 14:56:30.306  2712  2712 V BluetoothAdapterState: isTurningOff()=true
08-30 14:56:30.306  2712  2712 V BluetoothAdapterState: isTurningOn()=false
08-30 14:56:30.306  2712  2712 V BluetoothAdapterState: isBleTurningOn()=false
08-30 14:56:30.306  2712  2712 V BluetoothAdapterState: isBleTurningOff()=false
08-30 14:56:30.307  2712  2712 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-30 14:56:30.307  2712  2763 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
08-30 14:56:30.307  2712  2763 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
08-30 14:56:30.307  2712  2712 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-30 14:56:30.308  2712  2712 V BluetoothAdapterState: isTurningOff()=true
08-30 14:56:30.308  2712  2712 V BluetoothAdapterState: isTurningOn()=false
,08-30 14:56:30.308  2712  2712 V BluetoothAdapterState: isBleTurningOn()=false
08-30 14:56:30.308  2712  2712 V BluetoothAdapterState: isBleTurningOff()=false
08-30 14:56:30.308  2712  2712 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-30 14:56:30.308  2712  2712 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-30 14:56:30.310  2712  2712 D BluetoothMapService: MAP Service closeService in
08-30 14:56:30.310  2712  2712 V BluetoothAdapterState: isTurningOff()=true
08-30 14:56:30.310  2712  2712 V BluetoothAdapterState: isTurningOn()=false
08-30 14:56:30.310  2712  2712 V BluetoothAdapterState: isBleTurningOn()=false
,08-30 14:56:30.310  2712  2712 V BluetoothAdapterState: isBleTurningOff()=false
08-30 14:56:30.310  2712  2759 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
,08-30 14:56:30.310  2712  2759 D BluetoothAdapterProperties: Setting state to 15
08-30 14:56:30.310  2712  2759 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
08-30 14:56:30.310  2712  2712 D BluetoothMapService: cleanup()
08-30 14:56:30.310  2712  2712 D BluetoothMapService: MAP Service closeService in
08-30 14:56:30.311  2712  2759 I BluetoothAdapterState: Entering BleOnState
08-30 14:56:30.311   872   889 D BluetoothHeadset: onBluetoothStateChange: up=false
08-30 14:56:30.311   872   889 D BluetoothA2dp: onBluetoothStateChange: up=false
08-30 14:56:30.311  1344  2056 D BluetoothPan: onBluetoothStateChange on: false
08-30 14:56:30.312  1344  1360 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-30 14:56:30.313  1344  1361 D BluetoothA2dp: onBluetoothStateChange: up=false
08-30 14:56:30.313  1344  2056 D BluetoothMap: onBluetoothStateChange: up=false
08-30 14:56:30.314  1344  1360 D BluetoothPbap: onBluetoothStateChange: up=false
08-30 14:56:30.315   872   889 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-30 14:56:30.315   872   889 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-30 14:56:30.315  1344  2056 D BluetoothHeadset: onBluetoothStateChange: up=false
08-30 14:56:30.315  1975  2141 D BluetoothHeadset: onBluetoothStateChange: up=false
08-30 14:56:30.316  2712  2759 D BluetoothAdapterState: Current state: BLE ON, message: 20
08-30 14:56:30.316  2712  2759 D BluetoothAdapterProperties: Setting state to 16
08-30 14:56:30.316  2712  2759 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
08-30 14:56:30.317  2712  2759 D BluetoothAdapterProperties: onBleDisable
08-30 14:56:30.317  2712  2759 I BluetoothAdapterState: Entering PendingCommandState
08-30 14:56:30.317  2712  2760 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
,08-30 14:56:30.318  2712  2901 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
08-30 14:56:30.318  2712  2901 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-30 14:56:30.318   872  2127 D DhcpClient: Receive thread stopped
08-30 14:56:30.319  2712  2763 D BluetoothAdapterProperties: Scan Mode:20
08-30 14:56:30.322  3824  3824 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 14:56:30.322  3824  3824 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 14:56:30.322  3824  3824 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 14:56:30.322  3824  3824 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 14:56:30.322  3824  3824 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 14:56:30.322  3824  3824 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 14:56:30.322  3824  3824 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 14:56:30.322  3824  3824 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 14:56:30.322  3824  3824 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 14:56:30.323  3824  3824 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 14:56:30.323  3824  3824 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-30 14:56:30.325  3824  3824 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-30 14:56:30.325  3824  3824 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 14:56:30.325  3824  3824 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 14:56:30.325  3824  3824 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 14:56:30.325  3824  3824 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 14:56:30.325  3824  3824 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 14:56:30.325  3824  3824 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 14:56:30.325  3824  3824 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 14:56:30.325  3824  3824 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 14:56:30.325  3824  3824 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 14:56:30.325  3824  3824 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-30 14:56:30.326  3824  3824 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 14:56:30.327  3824  3824 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 14:56:30.342   370   870 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-30 14:56:30.347  3890  3890 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm
,08-30 14:56:30.357  3890  3890 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-30 14:56:30.359   370   870 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-30 14:56:30.360   872  1306 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
08-30 14:56:30.360   872  1306 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-30 14:56:30.363   872   889 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@39ca124:true
08-30 14:56:30.364  1494  1494 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-30 14:56:30.365   872  1302 D WifiConfigStore: Retrieve network priorities after PNO.
08-30 14:56:30.366   872   889 D Tethering: MasterInitialState.processMessage what=3
08-30 14:56:30.370  3824  3824 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 14:56:30.370  3824  3824 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 14:56:30.370  3824  3824 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 14:56:30.370  3824  3824 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 14:56:30.370  3824  3824 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 14:56:30.370  3824  3824 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 14:56:30.370  3824  3824 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 14:56:30.370  3824  3824 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 14:56:30.370  3824  3824 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 14:56:30.370  1855  2294 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 14:56:30.371  3824  3824 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 14:56:30.371  3824  3824 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-30 14:56:30.371   872  1302 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-30 14:56:30.372  3824  3824 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 14:56:30.372  3824  3824 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 14:56:30.372  3824  3824 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 14:56:30.372  3824  3824 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 14:56:30.372  3824  3824 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 14:56:30.372  3824  3824 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 14:56:30.372  3824  3824 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 14:56:30.372  3824  3824 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 14:56:30.372  3824  3824 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 14:56:30.373  3824  3824 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 14:56:30.373  3824  3824 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-30 14:56:30.374  3824  3824 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 14:56:30.374  3450  3450 D MusicLifecycle: com.go,ogle.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@221c1f4 and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
08-30 14:56:30.375  3824  3824 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 14:56:30.375  2065  2065 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
,08-30 14:56:30.387   872  1389 I ActivityManager: Start proc 3907:com.google.android.apps.maps/u0a65 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,08-30 14:56:30.396  3890  3890 D LocalBluetoothProfileManager: Adding local MAP profile
,08-30 14:56:30.409  3890  3890 D BluetoothMap: Create BluetoothMap proxy object
,08-30 14:56:30.417   370   870 E Netd    : netlink response contains error (No such file or directory)
,08-30 14:56:30.417   872  1306 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,08-30 14:56:30.419  3890  3890 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,08-30 14:56:30.426  3907  3907 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm
,08-30 14:56:30.433  3890  3890 D DockEventReceiver: finishStartingService: stopping service
,08-30 14:56:30.443   872  2017 I ActivityManager: Killing 2999:com.google.android.calendar/u0a37 (adj 15): empty #17
,08-30 14:56:30.519  2712  2763 I bt_hci  : shut_down
,08-30 14:56:30.519  2712  2769 D bt_hwcfg: hw_epilog_process
,08-30 14:56:30.525  2712  2769 I bt_vendor: low_power_mode_cb
,08-30 14:56:30.545  2712  2769 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,08-30 14:56:30.545  2712  2769 I bt_vendor: epilog_cb
08-30 14:56:30.545  2712  2769 I bt_hci  : epilog_finished_callback
,08-30 14:56:30.549  2712  2763 I bt_hci_h4: hal_close
,08-30 14:56:30.550  2712  2763 I bt_userial_vendor: device fd = 51 close
,08-30 14:56:30.558  3907  3907 D StrictMode: StrictMode policy violation; ~duration=68 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-30 14:56:30.558  3907  3907 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-30 14:56:30.558  3907  3907 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-30 14:56:30.558  3907  3907 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-30 14:56:30.558  3907  3907 D StrictMode: 	at java.io.File.exists(File.java:361)
08-30 14:56:30.558  3907  3907 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
08-30 14:56:30.558  3907  3907 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
08-30 14:56:30.558  3907  3907 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
08-30 14:56:30.558  3907  3907 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-30 14:56:30.558  3907  3907 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-30 14:56:30.558  3907  3907 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-30 14:56:30.558  3907  3907 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-30 14:56:30.558  3907  3907 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-30 14:56:30.558  3907  3907 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-30 14:56:30.558  3907  3907 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-30 14:56:30.558  3907  3907 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-30 14:56:30.558  3907  3907 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-30 14:56:30.558  3907  3907 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-30 14:56:30.558  3907  3907 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-30 14:56:30.558  3907  3907 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-30 14:56:30.558  3907  3907 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-30 14:56:30.558  3907  3907 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 14:56:30.558  3907  3907 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-30 14:56:30.558  3907  3907 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-30 14:56:30.558  3907  3907 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 14:56:30.558  3907  3907 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-30 14:56:30.558  3907  3907 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-30 14:56:30.558  3907  3907 D StrictMode: StrictMode policy violation; ~duration=67 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-30 14:56:30.558  3907  3907 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-30 14:56:30.558  3907  3907 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
08-30 14:56:30.558  3907  3907 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-30 14:56:30.558  3907  3907 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-30 14:56:30.558  3907  3907 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
08-30 14:56:30.558  3907  3907 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-30 14:56:30.558  3907  3907 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-30 14:56:30.558  3907  3907 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-30 14:56:30.558  3907  3907 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-30 14:56:30.558  3907  3907 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-30 14:56:30.558  3907  3907 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-30 14:56:30.558  3907  3907 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-30 14:56:30.558  3907  3907 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-30 14:56:30.558  3907  3907 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-30 14:56:30.558  3907  3907 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-30 14:56:30.558  3907  3907 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-30 14:56:30.558  3907  3907 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-30 14:56:30.558  3907  3907 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-30 14:56:30.558  3907  3907 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 14:56:30.558  3907  3907 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-30 14:56:30.558  3907  3907 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-30 14:56:30.558  3907  3907 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 14:56:30.558  3907  3907 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-30 14:56:30.558  3907  3907 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-30 14:56:30.558  3907  3907 D StrictMode: StrictMode policy violation; ~duration=66 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-30 14:56:30.558  3907  3907 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-30 14:56:30.558  3907  3907 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
08-30 14:56:30.558  3907  3907 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
08-30 14:56:30.558  3907  3907 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-30 14:56:30.558  3907  3907 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
08-30 14:56:30.558  3907  3907 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-30 14:56:30.558  3907  3907 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-30 14:56:30.558  3907  3907 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-30 14:56:30.558  3907  3907 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-30 14:56:30.558  3907  3907 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-30 14:56:30.558  3907  3907 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-30 14:56:30.558  3907  3907 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-30 14:56:30.558  3907  3907 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-30 14:56:30.558  3907  3907 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-30 14:56:30.558  3907  3907 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-30 14:56:30.558  3907  3907 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-30 14:56:30.558  3907  3907 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-30 14:56:30.558  3907  3907 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-30 14:56:30.558  3907  3907 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 14:56:30.558  3907  3907 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-30 14:56:30.558  3907  3907 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-30 14:56:30.558  3907  3907 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 14:56:30.558  3907  3907 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-30 14:56:30.558  3907  3907 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-30 14:56:30.558  3907  3907 D StrictMode: StrictMode policy violation; ~duration=65 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-30 14:56:30.558  3907  3907 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-30 14:56:30.558  3907  3907 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-30 14:56:30.558  3907  3907 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
08-30 14:56:30.558  3907  3907 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-30 14:56:30.558  3907  3907 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-30 14:56:30.558  3907  3907 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-30 14:56:30.558  3907  3907 D StrictMode: 	at com.google.r.k.d(PG:1187)
08-30 14:56:30.558  3907  3907 D StrictMode: 	at com.google.r.k.a(PG:2107)
08-30 14:56:30.558  3907  3907 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
08-30 14:56:30.558  3907  3907 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
08-30 14:56:30.558  3907  3907 D StrictMode: 	at com.google.r.v.a(PG:1161)
08-30 14:56:30.558  3907  3907 D StrictMode: 	at com.google.r.y.a(PG:2188)
08-30 14:56:30.558  390,7  3907 D StrictMode: 	at com.google.r.e.b(PG:170)
08-30 14:56:30.558  3907  3907 D StrictMode: 	at com.google.r.e.b(PG:15188)
08-30 14:56:30.558  3907  3907 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
08-30 14:56:30.558  3907  3907 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-30 14:56:30.558  3907  3907 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-30 14:56:30.558  3907  3907 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-30 14:56:30.558  3907  3907 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-30 14:56:30.558  3907  3907 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-30 14:56:30.558  3907  3907 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-30 14:56:30.558  3907  3907 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-30 14:56:30.558  3907  3907 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-30 14:56:30.558  3907  3907 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-30 14:56:30.558  3907  3907 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-30 14:56:30.558  3907  3907 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-30 14:56:30.558  3907  3907 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 14:56:30.558  3907  3907 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-30 14:56:30.558  3907  3907 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-30 14:56:30.558  3907  3907 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 14:56:30.558  3907  3907 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-30 14:56:30.558  3907  3907 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-30 14:56:30.558  3907  3907 D StrictMode: StrictMode policy violation; ~duration=63 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-30 14:56:30.558  3907  3907 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-30 14:56:30.558  3907  3907 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-30 14:56:30.558  3907  3907 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
08-30 14:56:30.558  3907  3907 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-30 14:56:30.558  3907  3907 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-30 14:56:30.558  3907  3907 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-30 14:56:30.558  3907  3907 D StrictMode: 	at com.google.r.k.d(PG:1187)
08-30 14:56:30.558  3907  3907 D StrictMode: 	at com.google.r.k.c(PG:18147)
08-30 14:56:30.558  3907  3907 D StrictMode: 	at com.google.r.k.d(PG:583)
08-30 14:56:30.558  3907  3907 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
08-30 14:56:30.558  3907  3907 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
08-30 14:56:30.558  3907  3907 D StrictMode: 	at com.google.r.v.a(PG:1161)
08-30 14:56:30.558  3907  3907 D StrictMode: 	at com.google.r.y.a(PG:2188)
08-30 14:56:30.558  3907  3907 D StrictMode: 	at com.google.r.e.b(PG:170)
08-30 14:56:30.558  3907  3907 D StrictMode: 	at com.google.r.e.b(PG:15188)
08-30 14:56:30.558  3907  3907 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
08-30 14:56:30.558  3907  3907 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-30 14:56:30.558  3907  3907 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-30 14:56:30.558  3907  3907 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-30 14:56:30.558  3907  3907 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-30 14:5,6:30.558  3907  3907 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-30 14:56:30.558  3907  3907 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-30 14:56:30.558  3907  3907 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-30 14:56:30.558  3907  3907 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-30 14:56:30.558  3907  3907 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-30 14:56:30.558  3907  3907 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-30 14:56:30.558  3907  3907 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-30 14:56:30.558  3907  3907 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 14:56:30.558  3907  3907 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-30 14:56:30.558  3907  3907 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-30 14:56:30.558  3907  3907 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 14:56:30.558  3907  3907 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-30 14:56:30.558  3907  3907 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-30 14:56:30.559  3907  3907 D StrictMode: StrictMode policy violation; ~duration=51 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-30 14:56:30.559  3907  3907 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-30 14:56:30.559  3907  3907 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-30 14:56:30.559  3907  3907 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-30 14:56:30.559  3907  3907 D StrictMode: 	at java.io.File.exists(File.java:361)
08-30 14:56:30.559  3907  3907 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
08-30 14:56:30.559  3907  3907 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
08-30 14:56:30.559  3907  3907 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
08-30 14:56:30.559  3907  3907 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
08-30 14:56:30.559  3907  3907 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
08-30 14:56:30.559  3907  3907 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-30 14:56:30.559  3907  3907 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-30 14:56:30.559  3907  3907 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-30 14:56:30.559  3907  3907 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-30 14:56:30.559  3907  3907 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-30 14:56:30.559  3907  3907 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-30 14:56:30.559  3907  3907 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-30 14:56:30.559  3907  3907 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-30 14:56:30.559  3907  3907 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-30 14:56:30.559  3907  3907 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-30 14:56:30.559  3907  3907 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 14:56:30.559  3907  3907 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-30 14:56:30.559  3907  3907 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-30 14:56:30.559  3907  3907 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 14:56:30.559  3907  3907 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-30 14:56:30.559  3907  3907 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-30 14:56:30.559  3907  3907 D StrictMode: StrictMode policy violation; ~duration=50 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-30 14:56:30.559  3907  3907 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-30 14:56:30.559  3907  3907 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-30 14:56:30.559  3907  3907 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-30 14:56:30.559  3907  3907 D StrictMode: 	at java.io.File.exists(File.java:361)
08-30 14:56:30.559  3907  3907 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
08-30 14:56:30.559  3907  3907 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-30 14:56:30.559  3907  3907 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-30 14:56:30.559  3907  3907 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-30 14:56:30.559  3907  3907 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-30 14:56:30.559  3907  3907 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-30 14:56:30.559  3907  3907 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-30 14:56:30.559  3907  3907 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-30 14:56:30.559  3907  3907 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-30 14:56:30.559  3907  3907 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-30 14:56:30.559  3907  3907 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-30 14:56:30.559  3907  3907 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 14:56:30.559  3907  3907 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-30 14:56:30.559  3907  3907 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-30 14:56:30.559  3907  3907 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 14:56:30.559  3907  3907 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-30 14:56:30.559  3907  3907 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-30 14:56:30.559  3907  3907 D StrictMode: StrictMode policy violation; ~duration=49 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-30 14:56:30.559  3907  3907 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-30 14:56:30.559  3907  3907 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
08-30 14:56:30.559  3907  3907 D StrictMode: 	at java.io.File.lastModified(File.java:569)
08-30 14:56:30.559  3907  3907 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
08-30 14:56:30.559  3907  3907 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-30 14:56:30.559  3907  3907 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-30 14:56:30.559  3907  3907 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-30 14:56:30.559  3907  3907 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-30 14:56:30.559  3907  3907 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-30 14:56:30.559  3907  3907 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-30 14:56:30.559  3907  3907 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-30 14:56:30.559  3907  3907 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-30 14:56:30.559  3907  3907 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-30 14:56:30.559  3907  3907 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-30 14:56:30.559  3907  3907 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 14:56:30.559  3907  3907 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-30 14:56:30.559  3907  3907 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-30 14:56:30.559  3907  3907 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 14:56:30.559  3907  3907 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-30 14:56:30.559  3907  3907 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-30 14:56:30.571  3890  3890 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-30 14:56:30.578  1494  1494 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-30 14:56:30.616  3890  3890 D DockEventReceiver: finishStartingService: stopping service
08-30 14:56:30.622  1709  1709 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
08-30 14:56:30.642  1709  1709 D SystemUpdateService: onCreate
,08-30 14:56:30.655  1709  1709 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-30 14:56:30.661  1709  3940 I SystemUpdateService: active receiver: enabled
,08-30 14:56:30.713  3824  3824 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-30 14:56:30.721  1709  1709 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,08-30 14:56:30.725  2712  2760 D bt_stack_manager: event_shut_down_stack finished.
,08-30 14:56:30.725  2712  2759 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
08-30 14:56:30.725  1709  3940 I SystemUpdateService: Already downloaded, skipping offpeak checks.
08-30 14:56:30.726  1709  2527 I iu.UploadsManager: num queued entries: 0
08-30 14:56:30.726  1709  2527 I iu.UploadsManager: num updated entries: 0
,08-30 14:56:30.727  1709  2527 I iu.SyncManager: NEXT; no task
08-30 14:56:30.728  1709  3940 I SystemUpdateService: network: null; metered: false; mobile allowed: true
08-30 14:56:30.728  1709  3940 I SystemUpdateService: now status is 0 (complete)
08-30 14:56:30.728  1709  3940 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
,08-30 14:56:30.728  1709  3940 I SystemUpdateService: file has been verified
08-30 14:56:30.729  2712  2759 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
08-30 14:56:30.729  2712  2712 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-30 14:56:30.730  2712  2712 D BtGatt.GattService: Received stop request...Stopping profile...
,08-30 14:56:30.730  2712  2712 D BtGatt.GattService: stop()
08-30 14:56:30.730  2712  2712 D BtGatt.AdvertiseManager: advertise clients cleared
08-30 14:56:30.732  2712  2712 V BluetoothAdapterState: isTurningOff()=false
08-30 14:56:30.732  2712  2712 V BluetoothAdapterState: isTurningOn()=false
08-30 14:56:30.732  2712  2712 V BluetoothAdapterState: isBleTurningOn()=false
08-30 14:56:30.732  2712  2712 V BluetoothAdapterState: isBleTurningOff()=true
08-30 14:56:30.732  2712  2759 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
,08-30 14:56:30.733  1709  3940 I SystemUpdateService: OTA package size = 12249756
08-30 14:56:30.733  2712  2759 D BluetoothAdapterProperties: Setting state to 10
08-30 14:56:30.733  2712  2759 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
08-30 14:56:30.734  2712  2759 I BluetoothAdapterState: Entering OffState
,08-30 14:56:30.737   872   889 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
,08-30 14:56:30.739  1709  3940 I SystemUpdateService: showing system update notification
,08-30 14:56:30.749  1709  1709 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
08-30 14:56:30.750  1709  1709 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-30 14:56:30.753  2712  2712 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,08-30 14:56:30.753  2712  2712 W BluetoothSdpJni: Cleaning up Bluetooth Health object
,08-30 14:56:30.762  2712  2712 I BluetoothServiceJni: cleanupNative: return from cleanup
,08-30 14:56:30.763  2712  2760 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,08-30 14:56:30.766   872  1390 I ActivityManager: Start proc 3944:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,08-30 14:56:30.768  2712  2760 D bt_stack_manager: event_clean_up_stack finished.
08-30 14:56:30.769  2712  2712 I art     : System.exit called, status: 0
08-30 14:56:30.769  2712  2712 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-30 14:56:30.791  1709  1709 D SystemUpdateService: onDestroy
,08-30 14:56:30.797   872  1984 I ActivityManager: Killing 3450:com.google.android.music:main/u0a66 (adj 15): empty #17
,08-30 14:56:30.856   872  2017 I ActivityManager: Process com.android.bluetooth (pid 2712) has died
,08-30 14:56:30.880  3944  3944 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm
,08-30 14:56:30.883  3944  3944 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-30 14:56:30.904  3944  3944 D SprintDMHelper: simOperator: 
,08-30 14:56:30.904  3944  3944 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-30 14:56:30.923   872  2023 I ActivityManager: Start proc 3957:com.android.chrome/u0a40 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
,08-30 14:56:30.923   872  2023 I ActivityManager: Killing 3069:com.google.android.keep/u0a79 (adj 15): empty #17
,08-30 14:56:30.965  3907  3936 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,08-30 14:56:31.055   872   889 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@65d31f0:true
,08-30 14:56:31.121   872  2021 I ActivityManager: Start proc 3974:com.google.android.apps.magazines/u0a67 for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider
,08-30 14:56:31.123  3109  3973 I Babel   : connection state changed from UNKNOWN to DISCONNECTED
,08-30 14:56:31.221  3974  3974 W System  : ClassLoader referenced unknown path: /system/app/Newsstand/lib/arm
,08-30 14:56:31.280  3974  3974 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
08-30 14:56:31.280  3974  3974 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
08-30 14:56:31.280  3974  3974 I GAv4    :   adb logcat -s GAv4
,08-30 14:56:31.298  3974  3974 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,08-30 14:56:31.306  3974  3974 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,08-30 14:56:31.332  3974  3992 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,08-30 14:56:31.442  3974  3974 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
,08-30 14:56:31.482  3974  3974 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,08-30 14:56:31.491  3974  3974 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 8892-8895)
,08-30 14:56:31.491  3974  3974 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-30 14:56:31.503  3974  3974 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {3b28b8e}
,08-30 14:56:31.504  3974  3974 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-30 14:56:31.504  3974  3974 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,08-30 14:56:31.514  3974  3974 I BrowserStartupController: Initializing chromium process, singleProcess=true
,08-30 14:56:31.515  3974  3974 E SysUtils: ApplicationContext is null in ApplicationStatus
,08-30 14:56:31.531  3974  3974 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,08-30 14:56:31.548  3974  3974 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,08-30 14:56:31.548  3974  3974 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-30 14:56:31.548  3974  3974 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-30 14:56:31.548  3974  3974 I Adreno  : Build Date                       : 10/20/15
08-30 14:56:31.548  3974  3974 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-30 14:56:31.548  3974  3974 I Adreno  : Local Branch                     : M14
08-30 14:56:31.548  3974  3974 I Adreno  : Remote Branch                    : 
08-30 14:56:31.548  3974  3974 I Adreno  : Remote Branch                    : 
08-30 14:56:31.548  3974  3974 I Adreno  : Reconstruct Branch               : 
,08-30 14:56:31.612  3974  3974 I NSApplication: Starting up...
,08-30 14:56:31.629  3974  4020 W AudioManagerAndroid: Requires BLUETOOTH permission
,08-30 14:56:31.658   872  1390 I ActivityManager: Start proc 4025:com.google.android.apps.photos/u0a71 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
,08-30 14:56:31.659   872  1390 I ActivityManager: Killing 3514:com.android.providers.calendar/u0a3 (adj 15): empty #17
,08-30 14:56:31.741  4025  4025 W System  : ClassLoader referenced unknown path: /system/app/Photos/lib/arm
,08-30 14:56:31.939   872  2027 I ActivityManager: Killing 1688:android.process.acore/u0a5 (adj 15): empty #17
,08-30 14:56:32.004   872  2017 I ActivityManager: Start proc 4040:com.google.android.apps.gcs/u0a89 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,08-30 14:56:32.072  4040  4040 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm
,08-30 14:56:32.121  4040  4040 W ClientExperimentManager: [1] d.a: com.google.android.apps.gcs does not have permission com.google.android.apps.gcs.WRITE_EXPERIMENTS; disabling overrides
,08-30 14:56:32.144   872   882 I ActivityManager: Start proc 4063:com.google.android.keep/u0a79 for broadcast com.google.android.keep/.notification.AlertReceiver
,08-30 14:56:32.147   872   882 I ActivityManager: Killing 3681:com.google.android.partnersetup/u0a16 (adj 15): empty #17
,08-30 14:56:32.218  4063  4063 W System  : ClassLoader referenced unknown path: /system/app/PrebuiltKeep/lib/arm
,08-30 14:56:32.421   872  1385 I ActivityManager: Killing 3698:com.android.musicfx/u0a18 (adj 15): empty #17
,08-30 14:56:33.259   872  1674 D WifiService: setWifiEnabled: true pid=3824, uid=10000
,08-30 14:56:33.259   872  1674 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-30 14:56:33.276   872  1302 D WifiConfigStore: Loading config and enabling all networks 
,08-30 14:56:33.287  3824  3824 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-30 14:56:33.287  3824  3824 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 14:56:33.287  3824  3824 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 14:56:33.287  3824  3824 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 14:56:33.287  3824  3824 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 14:56:33.287  3824  3824 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 14:56:33.287  3824  3824 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 14:56:33.287  3824  3824 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 14:56:33.287  3824  3824 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 14:56:33.288  3824  3824 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 14:56:33.288  3824  3824 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-30 14:56:33.292  3824  3824 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-30 14:56:33.292  3824  3824 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 14:56:33.292  3824  3824 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 14:56:33.292  3824  3824 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 14:56:33.292  3824  3824 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 14:56:33.292  3824  3824 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 14:56:33.292  3824  3824 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 14:56:33.292  3824  3824 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 14:56:33.292  3824  3824 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 14:56:33.293  3824  3824 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 14:56:33.293  3824  3824 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-30 14:56:33.306   872  1302 D WifiConfigStore: loaded 0 passpoint configs
,08-30 14:56:33.307   872  1302 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,08-30 14:56:33.307   872  1302 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,08-30 14:56:33.308   872  1302 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
08-30 14:56:33.308   872  1302 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
08-30 14:56:33.309   872  1302 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
,08-30 14:56:33.309   872  1302 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,08-30 14:56:33.322   370   870 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,08-30 14:56:33.322   872  1302 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=8.75 rxSuccessRate=20.62 delta 1000 -> 994
08-30 14:56:33.323   370   870 D CommandListener: Setting iface cfg
,08-30 14:56:33.324   872  1301 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '132 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 132 Failed to set address (No such device)'
,08-30 14:56:33.324   872  1301 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,08-30 14:56:33.327   872  1301 D WifiNative-HAL: p2pGetDeviceAddress
,08-30 14:56:33.332   872  1301 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,08-30 14:56:33.333   872  1302 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
08-30 14:56:33.333   872  1302 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-30 14:56:33.340   872  1302 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,08-30 14:56:33.401   872  1302 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,08-30 14:56:33.405  1458  1458 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,08-30 14:56:33.831  1458  1458 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-30 14:56:33.881  1458  1458 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,08-30 14:56:33.881  1458  1458 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
08-30 14:56:33.885   872  1302 D WifiConfigStore: Retrieve network priorities after PNO.
,08-30 14:56:33.896   872  1302 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-30 14:56:33.897   872  1302 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-30 14:56:33.897   872  1306 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,08-30 14:56:33.923   872  1302 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-30 14:56:33.937   370   870 D CommandListener: Setting iface cfg
,08-30 14:56:33.938   872  1302 D WifiStateMachine: Start Dhcp Watchdog 2
,08-30 14:56:33.953   872  1306 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
,08-30 14:56:33.957   872  1302 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,08-30 14:56:34.009   872  4094 D DhcpClient: Receive thread started
,08-30 14:56:34.093   872  1302 E native  : do suspend false
,08-30 14:56:34.112   872  2121 D DhcpClient: Broadcasting DHCPDISCOVER
,08-30 14:56:34.132   872  4094 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.101, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172692, domain null
,08-30 14:56:34.135   872  2121 D DhcpClient: Got pending lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172692 seconds
,08-30 14:56:34.139   872  2121 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.101 serverid=192.168.1.1
,08-30 14:56:34.153   872  4094 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.101, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,08-30 14:56:34.154   872  2121 D DhcpClient: Confirmed lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,08-30 14:56:34.159   370   870 D CommandListener: Setting iface cfg
,08-30 14:56:34.170   872  1302 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,08-30 14:56:34.172   872  2121 D DhcpClient: Scheduling renewal in 86399s
,08-30 14:56:34.183   872  1302 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,08-30 14:56:34.187   872  1302 D WifiConfigStore: No blacklist allowed without epno enabled
08-30 14:56:34.187   872  1306 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,08-30 14:56:34.188   872  1306 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,08-30 14:56:34.192   872  1306 D ConnectivityService: Adding iface wlan0 to network 101
,08-30 14:56:34.198   872  1302 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,08-30 14:56:34.242   872  1306 E ConnectivityService: Unexpected mtu value: 0, wlan0
,08-30 14:56:34.243   872  1306 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
,08-30 14:56:34.245   872  1306 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,08-30 14:56:34.247   872  1306 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,08-30 14:56:34.249   872  1306 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,08-30 14:56:34.262   872  1306 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,08-30 14:56:34.269   872  1306 D ConnectivityService: scheduleUnvalidatedPrompt 101
,08-30 14:56:34.270   872  1306 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
08-30 14:56:34.270   872  1302 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
,08-30 14:56:34.270   872  1306 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
08-30 14:56:34.270   872  1306 D ConnectivityService:    accepting network in place of null
08-30 14:56:34.271   872  1306 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.101/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -55]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-30 14:56:34.271   872  1302 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-30 14:56:34.305   370   870 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-30 14:56:34.345   370   870 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-30 14:56:34.353   872  1306 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,08-30 14:56:34.355   872  1306 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-30 14:56:34.363   872  1306 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
,08-30 14:56:34.364   872   889 D Tethering: MasterInitialState.processMessage what=3
,08-30 14:56:34.382  3824  3824 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 14:56:34.382  3824  3824 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 14:56:34.382  3824  3824 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 14:56:34.382  3824  3824 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 14:56:34.382  3824  3824 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 14:56:34.382  3824  3824 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 14:56:34.382  3824  3824 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 14:56:34.382  3824  3824 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 14:56:34.382  3824  3824 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-30 14:56:34.382  3824  3824 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 14:56:34.383  3824  3824 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-30 14:56:34.384  3824  3824 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 14:56:34.384  3824  3824 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 14:56:34.384  3824  3824 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 14:56:34.384  3824  3824 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 14:56:34.384  3824  3824 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 14:56:34.384  3824  3824 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 14:56:34.384  3824  3824 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 14:56:34.384  3824  3824 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 14:56:34.384  3824  3824 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-30 14:56:34.385  3824  3824 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 14:56:34.385  3824  3824 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-30 14:56:34.405  2065  2065 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
,08-30 14:56:34.408  1709  1709 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-30 14:56:34.411  1709  1709 D SystemUpdateService: onCreate
,08-30 14:56:34.415  1709  1709 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-30 14:56:34.420  1709  4106 I SystemUpdateService: active receiver: enabled
,08-30 14:56:34.422  1709  4106 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-30 14:56:34.424  1709  4106 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
08-30 14:56:34.424  1709  4106 I SystemUpdateService: now status is 0 (complete)
08-30 14:56:34.425  1709  4106 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
08-30 14:56:34.425  1709  4106 I SystemUpdateService: file has been verified
,08-30 14:56:34.425  1709  4106 I SystemUpdateService: OTA package size = 12249756
,08-30 14:56:34.432  1709  4106 I SystemUpdateService: showing system update notification
,08-30 14:56:34.448  1709  1709 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,08-30 14:56:34.448  1709  1709 D SystemUpdateService: onDestroy
,08-30 14:56:34.454  1709  2527 I iu.UploadsManager: num queued entries: 0
,08-30 14:56:34.456  1709  1709 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-30 14:56:34.457  1709  2527 I iu.UploadsManager: num updated entries: 0
08-30 14:56:34.457  1709  1709 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
08-30 14:56:34.457  1709  2527 I iu.SyncManager: NEXT; no task
,08-30 14:56:34.462  1709  4110 I MDM     : [179] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
,08-30 14:56:34.462  1709  4110 W BaseAppContext: Using Auth Proxy for data requests.
,08-30 14:56:34.463  3944  3944 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-30 14:56:34.463  1709  4110 V GoogleAuthProtoRequest: [179] a.<init>: mAccountName set to: thalitester@gmail.com
,08-30 14:56:34.468  3944  3944 D SprintDMHelper: simOperator: 
,08-30 14:56:34.468  3944  3944 D SprintDMReceiver: Not Sprint UICC, don't do anything.
08-30 14:56:34.468  1494  1494 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-30 14:56:34.470  1494  1494 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-30 14:56:34.496  1494  1505 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
,08-30 14:56:34.496  1494  1505 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
08-30 14:56:34.496  1494  1505 I GLSUser : [GLSUser] Extracting token using key: Auth
08-30 14:56:34.496  1494  1505 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-30 14:56:34.520  1709  4110 E MDM     : [179] SitrepService.a: Error sending sitrep.
,08-30 14:56:34.542  4063  4109 V KeepSync: Connecting to GoogleApiClient
,08-30 14:56:34.543   872  1385 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,08-30 14:56:34.594  1494  1504 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-30 14:56:34.594  1494  1504 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-30 14:56:34.594  1494  1504 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-30 14:56:34.594  1494  1504 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-30 14:56:34.597  1494  2307 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,08-30 14:56:34.597  1494  2307 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
08-30 14:56:34.597  1494  2307 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-30 14:56:34.597  1494  2307 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-30 14:56:34.607  3022  4113 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
08-30 14:56:34.607  3022  4113 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-30 14:56:34.607  3022  4113 E HttpOperation: 	at jdm.a(PG:82)
08-30 14:56:34.607  3022  4113 E HttpOperation: 	at jcs.o(PG:406)
08-30 14:56:34.607  3022  4113 E HttpOperation: 	at jcn.a(PG:1379)
08-30 14:56:34.607  3022  4113 E HttpOperation: 	at jcs.i(PG:143)
08-30 14:56:34.607  3022  4113 E HttpOperation: 	at blb.a(PG:3937)
08-30 14:56:34.607  3022  4113 E HttpOperation: 	at czp.a(PG:18188)
08-30 14:56:34.607  3022  4113 E HttpOperation: 	at czp.a(PG:9081)
08-30 14:56:34.607  3022  4113 E HttpOperation: 	at czq.run(PG:1686)
08-30 14:56:34.607  3022  4113 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-30 14:56:34.607  3022  4113 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-30 14:56:34.607  3022  4113 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-30 14:56:34.607  3022  4113 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-30 14:56:34.607  3022  4113 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-30 14:56:34.607  3022  4113 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-30 14:56:34.607  3022  4113 E HttpOperation: 	at jdj.a(PG:4091)
08-30 14:56:34.607  3022  4113 E HttpOperation: 	at jdj.a(PG:1125)
08-30 14:56:34.607  3022  4113 E HttpOperation: 	at jdm.a(PG:77)
08-30 14:56:34.607  3022  4113 E HttpOperation: 	... 12 more
08-30 14:56:34.607  3022  4113 E HttpOperation: Caused by: faj: BadAuthentication
08-30 14:56:34.607  3022  4113 E HttpOperation: 	at fal.a(PG:38)
08-30 14:56:34.607  3022  4113 E HttpOperation: 	at jdj.a(PG:4089)
08-30 14:56:34.607  3022  4113 E HttpOperation: 	... 14 more
,08-30 14:56:34.615  1709  4118 V BaseAuthAsyncOperation: access token request failed
,08-30 14:56:34.618  4063  4109 V KeepSync: GoogleApiClient failed to connect with error code: 4
,08-30 14:56:34.646  1494  1505 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-30 14:56:34.647  1494  1505 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-30 14:56:34.647  1494  1505 I GLSUser : [GLSUser] Extracting token using key: Auth
08-30 14:56:34.647  1494  1505 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-30 14:56:34.661  3022  4113 E HttpOperation: [getmobileexperiments] Unexpected exception
08-30 14:56:34.661  3022  4113 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-30 14:56:34.661  3022  4113 E HttpOperation: 	at jdm.a(PG:82)
08-30 14:56:34.661  3022  4113 E HttpOperation: 	at jcs.o(PG:406)
08-30 14:56:34.661  3022  4113 E HttpOperation: 	at jcn.a(PG:1379)
08-30 14:56:34.661  3022  4113 E HttpOperation: 	at jcs.i(PG:143)
08-30 14:56:34.661  3022  4113 E HttpOperation: 	at hec.a(PG:42)
08-30 14:56:34.661  3022  4113 E HttpOperation: 	at hee.a(PG:102)
08-30 14:56:34.661  3022  4113 E HttpOperation: 	at czr.a(PG:65)
08-30 14:56:34.661  3022  4113 E HttpOperation: 	at kka.a(PG:108)
08-30 14:56:34.661  3022  4113 E HttpOperation: 	at czp.a(PG:19176)
08-30 14:56:34.661  3022  4113 E HttpOperation: 	at czp.a(PG:9081)
08-30 14:56:34.661  3022  4113 E HttpOperation: 	at czq.run(PG:1686)
08-30 14:56:34.661  3022  4113 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-30 14:56:34.661  3022  4113 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-30 14:56:34.661  3022  4113 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-30 14:56:34.661  3022  4113 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-30 14:56:34.661  3022  4113 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-30 14:56:34.661  3022  4113 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-30 14:56:34.661  3022  4113 E HttpOperation: 	at jdj.a(PG:4091)
08-30 14:56:34.661  3022  4113 E HttpOperation: 	at jdj.a(PG:1125)
08-30 14:56:34.661  3022  4113 E HttpOperation: 	at jdm.a(PG:77)
08-30 14:56:34.661  3022  4113 E HttpOperation: 	... 15 more
08-30 14:56:34.661  3022  4113 E HttpOperation: Caused by: faj: BadAuthentication
08-30 14:56:34.661  3022  4113 E HttpOperation: 	at fal.a(PG:38)
08-30 14:56:34.661  3022  4113 E HttpOperation: 	at jdj.a(PG:4089)
08-30 14:56:34.661  3022  4113 E HttpOperation: 	... 17 more
,08-30 14:56:34.661  3022  4113 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
08-30 14:56:34.661  3022  4113 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
08-30 14:56:34.661  3022  4113 E ExperimentLoader: 	at jdm.a(PG:82)
08-30 14:56:34.661  3022  4113 E ExperimentLoader: 	at jcs.o(PG:406)
08-30 14:56:34.661  3022  4113 E ExperimentLoader: 	at jcn.a(PG:1379)
08-30 14:56:34.661  3022  4113 E ExperimentLoader: 	at jcs.i(PG:143)
08-30 14:56:34.661  3022  4113 E ExperimentLoader: 	at hec.a(PG:42)
08-30 14:56:34.661  3022  4113 E ExperimentLoader: 	at hee.a(PG:102)
08-30 14:56:34.661  3022  4113 E ExperimentLoader: 	at czr.a(PG:65)
08-30 14:56:34.661  3022  4113 E ExperimentLoader: 	at kka.a(PG:108)
08-30 14:56:34.661  3022  4113 E ExperimentLoader: 	at czp.a(PG:19176)
08-30 14:56:34.661  3022  4113 E ExperimentLoader: 	at czp.a(PG:9081)
08-30 14:56:34.661  3022  4113 E ExperimentLoader: 	at czq.run(PG:1686)
08-30 14:56:34.661  3022  4113 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-30 14:56:34.661  3022  4113 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-30 14:56:34.661  3022  4113 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-30 14:56:34.661  3022  4113 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-30 14:56:34.661  3022  4113 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
08-30 14:56:34.661  3022  4113 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-30 14:56:34.661  3022  4113 E ExperimentLoader: 	at jdj.a(PG:4091)
08-30 14:56:34.661  3022  4113 E ExperimentLoader: 	at jdj.a(PG:1125)
08-30 14:56:34.661  3022  4113 E ExperimentLoader: 	at jdm.a(PG:77)
08-30 14:56:34.661  3022  4113 E ExperimentLoader: 	... 15 more
08-30 14:56:34.661  3022  4113 E ExperimentLoader: Caused by: faj: BadAuthentication
08-30 14:56:34.661  3022  4113 E ExperimentLoader: 	at fal.a(PG:38)
08-30 14:56:34.661  3022  4113 E ExperimentLoader: 	at jdj.a(PG:4089)
08-30 14:56:34.661  3022  4113 E ExperimentLoader: 	... 17 more
,08-30 14:56:34.783   872   884 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 129218, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,08-30 14:56:34.825  1494  1505 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,08-30 14:56:34.826  1494  1505 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
,08-30 14:56:34.826  1494  1505 I GLSUser : [GLSUser] Extracting token using key: Auth
08-30 14:56:34.826  1494  1505 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-30 14:56:34.873  4063  4109 E KeepSync: IOException
08-30 14:56:34.873  4063  4109 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
08-30 14:56:34.873  4063  4109 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
08-30 14:56:34.873  4063  4109 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
08-30 14:56:34.873  4063  4109 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
08-30 14:56:34.873  4063  4109 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
08-30 14:56:34.873  4063  4109 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
08-30 14:56:34.873  4063  4109 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
08-30 14:56:34.873  4063  4109 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
08-30 14:56:34.873  4063  4109 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
08-30 14:56:34.873  4063  4109 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
08-30 14:56:34.873  4063  4109 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
08-30 14:56:34.873  4063  4109 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
08-30 14:56:34.873  4063  4109 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
08-30 14:56:34.873  4063  4109 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
08-30 14:56:34.873  4063  4109 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-30 14:56:34.873  4063  4109 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-30 14:56:34.873  4063  4109 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
08-30 14:56:34.873  4063  4109 E KeepSync: 	... 10 more
,08-30 14:56:34.873  4063  4109 W KeepSync: Sync result 2
,08-30 14:56:34.881   872   884 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 128578, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-30 14:56:34.951   872  4093 D NetlinkSocketObserver: NeighborEvent{elapsedMs=132356, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-30 14:56:35.353   872  1306 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,08-30 14:56:36.081   872  4092 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.214.206,2a00:1450:400d:802::200e
,08-30 14:56:36.270   872  1982 D WifiService: setWifiEnabled: false pid=3824, uid=10000
08-30 14:56:36.271   872  1982 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-30 14:56:36.296  1458  1458 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,08-30 14:56:36.303   872  1302 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,08-30 14:56:36.304   872  1302 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
,08-30 14:56:36.304   872  1302 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-30 14:56:36.305   872  1302 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-30 14:56:36.323   872  2121 D DhcpClient: Clearing IP address
,08-30 14:56:36.323   370   870 D CommandListener: Clearing all IP addresses on wlan0
,08-30 14:56:36.326   370   870 D CommandListener: Setting iface cfg
,08-30 14:56:36.331   872  4092 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Probably not a portal: exception java.net.ConnectException: failed to connect to connectivitycheck.gstatic.com/2a00:1450:400d:802::200e (port 80) after 10000ms: connect failed: ENETUNREACH (Network is unreachable)
,08-30 14:56:36.333  3109  4114 W Babel_NetworkConnectionCheckingService: IO exceptions, probably not a captive portal 
08-30 14:56:36.333   872  1306 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation failed
08-30 14:56:36.334  3109  4114 W Babel_NetworkConnectionCheckingService: java.net.SocketException: recvfrom failed: ETIMEDOUT (Connection timed out)
08-30 14:56:36.334  3109  4114 W Babel_NetworkConnectionCheckingService: 	at libcore.io.IoBridge.maybeThrowAfterRecvfrom(IoBridge.java:588)
08-30 14:56:36.334  3109  4114 W Babel_NetworkConnectionCheckingService: 	at libcore.io.IoBridge.recvfrom(IoBridge.java:552)
08-30 14:56:36.334  3109  4114 W Babel_NetworkConnectionCheckingService: 	at java.net.PlainSocketImpl.read(PlainSocketImpl.java:481)
08-30 14:56:36.334  3109  4114 W Babel_NetworkConnectionCheckingService: 	at java.net.PlainSocketImpl.-wrap0(PlainSocketImpl.java)
08-30 14:56:36.334  3109  4114 W Babel_NetworkConnectionCheckingService: 	at java.net.PlainSocketImpl$PlainSocketInputStream.read(PlainSocketImpl.java:237)
08-30 14:56:36.334  3109  4114 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.okio.Okio$2.read(Okio.java:135)
08-30 14:56:36.334  3109  4114 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.okio.AsyncTimeout$2.read(AsyncTimeout.java:211)
08-30 14:56:36.334  3109  4114 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.okio.RealBufferedSource.indexOf(RealBufferedSource.java:306)
08-30 14:56:36.334  3109  4114 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.okio.RealBufferedSource.indexOf(RealBufferedSource.java:300)
08-30 14:56:36.334  3109  4114 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.okio.RealBufferedSource.readUtf8LineStrict(RealBufferedSource.java:196)
08-30 14:56:36.334  3109  4114 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.internal.http.HttpConnection.readResponse(HttpConnection.java:191)
08-30 14:56:36.334  3109  4114 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.internal.http.HttpTransport.readResponseHeaders(HttpTransport.java:80)
08-30 14:56:36.334  3109  4114 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.internal.http.HttpEngine.readNetworkResponse(HttpEngine.java:904)
08-30 14:56:36.334  3109  4114 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.internal.http.HttpEngine.readResponse(HttpEngine.java:788)
08-30 14:56:36.334  3109  4114 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.internal.huc.HttpURLConnectionImpl.execute(HttpURLConnectionImpl.java:443)
08-30 14:56:36.334  3109  4114 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.internal.huc.HttpURLConnectionImpl.getResponse(HttpURLConnectionImpl.java:388)
08-30 14:56:36.334  3109  4114 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.internal.huc.HttpURLConnectionImpl.getInputStream(HttpURLConnectionImpl.java:231)
08-30 14:56:36.334  3109  4114 W Babel_NetworkConnectionCheckingService: 	at com.google.android.apps.hangouts.service.NetworkConnectionCheckingService.a(SourceFile:129)
08-30 14:56:36.334  3109  4114 W Babel_NetworkConnectionCheckingService: 	at com.google.android.apps.hangouts.service.NetworkConnectionCheckingService.onHandleIntent(SourceFile:1100)
08-30 14:56:36.334  3109  4114 W Babel_NetworkConnectionCheckingService: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-30 14:56:36.334  3109  4114 W Babel_NetworkConnectionCheckingService: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 14:56:36.334  3109  4114 W Babel_NetworkConnectionCheckingService: 	at android.os.Looper.loop(Looper.java:148)
08-30 14:56:36.334  3109  4114 W Babel_NetworkConnectionCheckingService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-30 14:56:36.334  3109  4114 W Babel_NetworkConnectionCheckingService: Caused by: android.system.ErrnoException: recvfrom failed: ETIMEDOUT (Connection timed out)
08-30 14:56:36.334  3109  4114 W Babel,_NetworkConnectionCheckingService: 	at libcore.io.Posix.recvfromBytes(Native Method)
08-30 14:56:36.334  3109  4114 W Babel_NetworkConnectionCheckingService: 	at libcore.io.Posix.recvfrom(Posix.java:189)
08-30 14:56:36.334  3109  4114 W Babel_NetworkConnectionCheckingService: 	at libcore.io.BlockGuardOs.recvfrom(BlockGuardOs.java:250)
08-30 14:56:36.334  3109  4114 W Babel_NetworkConnectionCheckingService: 	at libcore.io.IoBridge.recvfrom(IoBridge.java:549)
08-30 14:56:36.334  3109  4114 W Babel_NetworkConnectionCheckingService: 	... 21 more
08-30 14:56:36.334  3109  4114 I Babel   : connection state changed from DISCONNECTED to CONNECTED
08-30 14:56:36.334  1494  4107 V NativeCrypto: SSL handshake aborted: ssl=0x9a6bde00: I/O error during system call, Connection timed out
08-30 14:56:36.336   872  1302 D WifiStateMachine: Start Disconnecting Watchdog 2
08-30 14:56:36.336   872  1302 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-30 14:56:36.343   872  1306 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
08-30 14:56:36.343   370   870 D CommandListener: Clearing all IP addresses on wlan0
,08-30 14:56:36.343   872  1306 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 3
,08-30 14:56:36.352  3824  3824 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-30 14:56:36.352  3824  3824 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 14:56:36.352  3824  3824 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 14:56:36.352  3824  3824 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 14:56:36.352  3824  3824 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 14:56:36.352  3824  3824 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 14:56:36.352  3824  3824 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 14:56:36.352  3824  3824 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 14:56:36.352  3824  3824 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-30 14:56:36.352  3824  3824 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-30 14:56:36.352  3824  3824 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-30 14:56:36.354   396   396 E Parcel  : Reading a NULL string not supported here.
08-30 14:56:36.355   872  4094 D DhcpClient: Receive thread stopped
08-30 14:56:36.355   872  1302 D WifiConfigStore: Retrieve network priorities after PNO.
08-30 14:56:36.357   872  1302 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-30 14:56:36.357  3824  3824 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 14:56:36.357  3824  3824 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 14:56:36.357  3824  3824 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 14:56:36.357  3824  3824 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 14:56:36.357  3824  3824 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 14:56:36.357  3824  3824 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 14:56:36.357  3824  3824 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 14:56:36.357  3824  3824 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 14:56:36.357  3824  3824 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-30 14:56:36.357  3824  3824 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 14:56:36.357  3824  3824 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-30 14:56:36.360   872  1306 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
08-30 14:56:36.364  1855  2294 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-30 14:56:36.385   872  2024 I ActivityManager: Killing 3498:com.google.android.gms.wearable/u0a11 (adj 15): empty #17
,08-30 14:56:36.395   370   870 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-30 14:56:36.428   370   870 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-30 14:56:36.429   872  1306 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,08-30 14:56:36.430   872  1306 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-30 14:56:36.433   872   889 D Tethering: MasterInitialState.processMessage what=3
,08-30 14:56:36.437  2065  2065 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
,08-30 14:56:36.437  3824  3824 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 14:56:36.437  3824  3824 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 14:56:36.437  3824  3824 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 14:56:36.437  3824  3824 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 14:56:36.437  3824  3824 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 14:56:36.437  3824  3824 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 14:56:36.437  3824  3824 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 14:56:36.437  3824  3824 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 14:56:36.437  3824  3824 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 14:56:36.439  3824  3824 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-30 14:56:36.439  3824  3824 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 14:56:36.439  3824  3824 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 14:56:36.439  3824  3824 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 14:56:36.439  3824  3824 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 14:56:36.439  3824  3824 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 14:56:36.439  3824  3824 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 14:56:36.439  3824  3824 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 14:56:36.439  3824  3824 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-30 14:56:36.448  1709  1709 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-30 14:56:36.452  1709  1709 D SystemUpdateService: onCreate
,08-30 14:56:36.454  1709  1709 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-30 14:56:36.462  1709  1709 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,08-30 14:56:36.468  1709  2527 I iu.UploadsManager: num queued entries: 0
,08-30 14:56:36.468  1709  2527 I iu.UploadsManager: num updated entries: 0
,08-30 14:56:36.470  1709  1709 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
08-30 14:56:36.471  1709  4133 I SystemUpdateService: active receiver: enabled
,08-30 14:56:36.475  1709  1709 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-30 14:56:36.477  3944  3944 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-30 14:56:36.479  1709  4133 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-30 14:56:36.479  1709  2527 I iu.SyncManager: NEXT; no task
,08-30 14:56:36.482  3944  3944 D SprintDMHelper: simOperator: 
,08-30 14:56:36.482  3944  3944 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-30 14:56:36.486  1709  4133 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,08-30 14:56:36.486  1709  4133 I SystemUpdateService: now status is 0 (complete)
08-30 14:56:36.486  1709  4133 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
08-30 14:56:36.486  1709  4133 I SystemUpdateService: file has been verified
08-30 14:56:36.486  1709  4133 I SystemUpdateService: OTA package size = 12249756
,08-30 14:56:36.493  1709  4133 I SystemUpdateService: showing system update notification
,08-30 14:56:36.513  3109  4137 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,08-30 14:56:36.531   370   870 E Netd    : netlink response contains error (No such file or directory)
,08-30 14:56:36.533   872  1306 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,08-30 14:56:36.536  1709  1709 D SystemUpdateService: onDestroy
,08-30 14:56:37.275  4063  4070 E DataBuffer: Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (com.google.android.gms.reminders.model.RemindersBuffer@c4e33ae)
,08-30 14:56:39.330   872   889 I ActivityManager: Start proc 4142:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,08-30 14:56:39.457  4142  4142 D AdapterServiceConfig: Adding HeadsetService
08-30 14:56:39.457  4142  4142 D AdapterServiceConfig: Adding A2dpService
,08-30 14:56:39.458  4142  4142 D AdapterServiceConfig: Adding HidService
08-30 14:56:39.458  4142  4142 D AdapterServiceConfig: Adding HealthService
08-30 14:56:39.458  4142  4142 D AdapterServiceConfig: Adding PanService
08-30 14:56:39.458  4142  4142 D AdapterServiceConfig: Adding GattService
08-30 14:56:39.459  4142  4142 D AdapterServiceConfig: Adding BluetoothMapService
,08-30 14:56:39.472  4142  4142 D BluetoothAdapterState: make() - Creating AdapterState
08-30 14:56:39.472   872   889 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@335a8ff:true
,08-30 14:56:39.477  4142  4142 I bt_bluedroid: init
,08-30 14:56:39.478  4142  4154 I BluetoothAdapterState: Entering OffState
,08-30 14:56:39.480  4142  4155 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
08-30 14:56:39.480  4142  4155 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-30 14:56:39.480  4142  4155 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-30 14:56:39.480  4142  4155 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,08-30 14:56:39.481  4142  4142 I bt_bluedroid: get_profile_interface socket
,08-30 14:56:39.483  4142  4142 I bt_bluedroid: get_profile_interface sdp
,08-30 14:56:39.486  4142  4153 I bt_bluedroid: config_hci_snoop_log
,08-30 14:56:39.487  4142  4158 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
08-30 14:56:39.489   872   889 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
08-30 14:56:39.495  4142  4158 D BluetoothAdapterProperties: Name is: Nexus 6
,08-30 14:56:39.501  4142  4154 D BluetoothAdapterState: Current state: OFF, message: 0
,08-30 14:56:39.502  4142  4154 D BluetoothAdapterProperties: Setting state to 14
08-30 14:56:39.502  4142  4154 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,08-30 14:56:39.506  4142  4154 D BluetoothBondStateMachine: make
,08-30 14:56:39.509  4142  4159 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-30 14:56:39.515  4142  4154 I BluetoothAdapterState: Entering PendingCommandState
,08-30 14:56:39.515  4142  4142 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,08-30 14:56:39.518  4142  4142 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@cadc134
,08-30 14:56:39.519  4142  4142 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-30 14:56:39.520  4142  4142 D BtGatt.GattService: Received start request. Starting profile...
08-30 14:56:39.520  4142  4142 D BtGatt.GattService: start()
,08-30 14:56:39.520  4142  4142 I bt_bluedroid: get_profile_interface gatt
08-30 14:56:39.521  4142  4142 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@cadc134
,08-30 14:56:39.521  4142  4142 D BtGatt.AdvertiseManager: advertise manager created
,08-30 14:56:39.529  4142  4142 V BluetoothAdapterState: isTurningOff()=false
,08-30 14:56:39.529  4142  4142 V BluetoothAdapterState: isTurningOn()=false
08-30 14:56:39.530  4142  4142 V BluetoothAdapterState: isBleTurningOn()=true
08-30 14:56:39.530  4142  4142 V BluetoothAdapterState: isBleTurningOff()=false
,08-30 14:56:39.530  4142  4154 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
08-30 14:56:39.531  4142  4154 I bt_bluedroid: enable
08-30 14:56:39.531  4142  4155 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,08-30 14:56:39.531  4142  4155 I bt_hci  : start_up
,08-30 14:56:39.538  4142  4155 I bt_vendor: alloc value 0xb3a1d189
,08-30 14:56:39.538  4142  4155 I bt_vendor: init
08-30 14:56:39.538  4142  4155 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
08-30 14:56:39.538  4142  4155 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,08-30 14:56:39.647  4142  4155 D bt_hci  : start_up starting async portion
,08-30 14:56:39.648  4142  4162 I bt_hci  : event_finish_startup
08-30 14:56:39.648  4142  4162 I bt_hci_h4: hal_open
08-30 14:56:39.649  4142  4162 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,08-30 14:56:39.661  4142  4162 I bt_userial_vendor: device fd = 51 open
,08-30 14:56:39.689  4142  4162 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-30 14:56:39.721  4142  4162 D bt_hwcfg: Chipset BCM4354A2
,08-30 14:56:39.721  4142  4162 D bt_hwcfg: Target name = [BCM4354A2]
,08-30 14:56:39.722  4142  4162 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,08-30 14:56:40.392  4142  4162 I bt_hwcfg: bt vendor lib: set UART baud 115200
08-30 14:56:40.394  4142  4162 D bt_hwcfg: Settlement delay -- 100 ms
,08-30 14:56:40.394  4142  4162 I bt_hwcfg: Setting fw settlement delay to 100 ,
,08-30 14:56:40.511  4142  4162 I bt_hwcfg: bt vendor lib: set UART baud 3000000
08-30 14:56:40.512  4142  4162 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,08-30 14:56:40.542  4142  4162 I bt_hwcfg: vendor lib fwcfg completed
,08-30 14:56:40.542  4142  4162 I bt_vendor: firmware callback
08-30 14:56:40.542  4142  4162 I bt_hci  : firmware_config_callback
,08-30 14:56:40.553  4142  4164 I bt_btu  : btu_task pending for preload complete event
,08-30 14:56:40.554  4142  4164 I bt_btu_task: Bluetooth chip preload is complete
08-30 14:56:40.554  4142  4164 I bt_btu  : btu_task received preload complete event
,08-30 14:56:40.566  4142  4164 I         : BTE_InitTraceLevels -- TRC_HCI
,08-30 14:56:40.566  4142  4164 I         : BTE_InitTraceLevels -- TRC_L2CAP
,08-30 14:56:40.566  4142  4164 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-30 14:56:40.567  4142  4164 I         : BTE_InitTraceLevels -- TRC_AVDT
08-30 14:56:40.567  4142  4164 I         : BTE_InitTraceLevels -- TRC_AVRC
,08-30 14:56:40.567  4142  4164 I         : BTE_InitTraceLevels -- TRC_A2D
08-30 14:56:40.567  4142  4164 I         : BTE_InitTraceLevels -- TRC_BNEP
08-30 14:56:40.568  4142  4164 I         : BTE_InitTraceLevels -- TRC_BTM
,08-30 14:56:40.568  4142  4164 I         : BTE_InitTraceLevels -- TRC_GAP
08-30 14:56:40.568  4142  4164 I         : BTE_InitTraceLevels -- TRC_PAN
08-30 14:56:40.569  4142  4164 I         : BTE_InitTraceLevels -- TRC_SDP
08-30 14:56:40.569  4142  4164 I         : BTE_InitTraceLevels -- TRC_GATT
,08-30 14:56:40.569  4142  4164 I         : BTE_InitTraceLevels -- TRC_SMP
08-30 14:56:40.569  4142  4164 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-30 14:56:40.570  4142  4164 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-30 14:56:40.709  4142  4164 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb399ad9d
08-30 14:56:40.709  4142  4164 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb399ad9d 
,08-30 14:56:40.717  4142  4158 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,08-30 14:56:40.718  4142  4158 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,08-30 14:56:40.720  4142  4158 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-30 14:56:40.723  4142  4158 D BluetoothAdapterProperties: Name is: Nexus 6
,08-30 14:56:40.727  4142  4158 D BluetoothAdapterProperties: Scan Mode:20
,08-30 14:56:40.727  4142  4158 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-30 14:56:40.728  4142  4158 D bt_hci  : do_postload posting postload work item
08-30 14:56:40.728  4142  4162 I bt_hci  : event_postload
,08-30 14:56:40.728  4142  4162 I bt_vendor: sco_config_cb
08-30 14:56:40.728  4142  4162 I bt_hci  : sco_config_callback postload finished.
08-30 14:56:40.731  4142  4158 D bt_bte_conf: Device ID record 1 : primary
,08-30 14:56:40.732  4142  4158 D bt_bte_conf:   vendorId            = 000f
08-30 14:56:40.732  3824  3824 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 14:56:40.732  4142  4158 D bt_bte_conf:   vendorIdSource      = 0001
08-30 14:56:40.732  4142  4158 D bt_bte_conf:   product             = 1200
08-30 14:56:40.732  4142  4158 D bt_bte_conf:   version             = 1436
,08-30 14:56:40.732  4142  4158 D bt_bte_conf:   clientExecutableURL = 
08-30 14:56:40.733  4142  4158 D bt_bte_conf:   serviceDescription  = 
,08-30 14:56:40.733  4142  4158 D bt_bte_conf:   documentationURL    = 
08-30 14:56:40.733  4142  4158 D bt_bte_conf: bte_load_did_conf no section named DID2.
,08-30 14:56:40.733  4142  4155 D bt_stack_manager: event_start_up_stack finished
08-30 14:56:40.734  4142  4154 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
08-30 14:56:40.736  3824  3824 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 14:56:40.736  4142  4154 D BluetoothAdapterProperties: Setting state to 15
08-30 14:56:40.736  4142  4162 I bt_vendor: low_power_mode_cb
08-30 14:56:40.736  4142  4154 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
,08-30 14:56:40.737  4142  4154 I BluetoothAdapterState: Entering BleOnState
,08-30 14:56:40.743  4142  4154 D BluetoothAdapterState: Current state: BLE ON, message: 1
08-30 14:56:40.743  4142  4154 D BluetoothAdapterProperties: Setting state to 11
,08-30 14:56:40.743  4142  4154 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,08-30 14:56:40.751  4142  4142 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@cadc134
,08-30 14:56:40.753  4142  4142 D HeadsetService: Received start request. Starting profile...
,08-30 14:56:40.759  4142  4142 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,08-30 14:56:40.760  4142  4142 D HeadsetStateMachine: make
,08-30 14:56:40.763  3824  3824 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 14:56:40.765  3824  3824 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 14:56:40.770  4142  4154 I BluetoothAdapterState: Entering PendingCommandState
,08-30 14:56:40.771  4142  4142 D HeadsetStateMachine: max_hf_connections = 1
,08-30 14:56:40.771  4142  4142 I bt_bluedroid: get_profile_interface handsfree
08-30 14:56:40.771  4142  4158 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
08-30 14:56:40.771  4142  4158 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
,08-30 14:56:40.777  4142  4142 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@cadc134
,08-30 14:56:40.778  4142  4142 D A2dpService: Received start request. Starting profile...
08-30 14:56:40.778  4142  4142 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-30 14:56:40.779  4142  4142 I bt_bluedroid: get_profile_interface avrcp
,08-30 14:56:40.785  4142  4142 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-30 14:56:40.785  4142  4142 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-30 14:56:40.785  4142  4142 D A2dpStateMachine: make
,08-30 14:56:40.787  4142  4142 I bt_bluedroid: get_profile_interface a2dp
,08-30 14:56:40.788  4142  4158 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,08-30 14:56:40.795  4142  4173 D A2dpStateMachine: Enter Disconnected: -2
,08-30 14:56:40.795  4142  4142 I BluetoothHidServiceJni: classInitNative: succeeds
,08-30 14:56:40.798  4142  4142 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@cadc134
,08-30 14:56:40.799  3890  3890 D BluetoothInputDevice: Proxy object connected
,08-30 14:56:40.800  4142  4142 D HidService: Received start request. Starting profile...
,08-30 14:56:40.800  3890  3890 D HidProfile: Bluetooth service connected
,08-30 14:56:40.800  4142  4142 I bt_bluedroid: get_profile_interface hidhost
08-30 14:56:40.800  4142  4158 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb397c3e5
08-30 14:56:40.800  4142  4158 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
08-30 14:56:40.800  4142  4142 D HidService: setHidService(): set to: null
,08-30 14:56:40.801  4142  4142 I BluetoothHealthServiceJni: classInitNative: succeeds
,08-30 14:56:40.803  4142  4142 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@cadc134
,08-30 14:56:40.804  4142  4142 D HealthService: Received start request. Starting profile...
,08-30 14:56:40.806  4142  4142 I bt_bluedroid: get_profile_interface health
,08-30 14:56:40.808  4142  4142 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,08-30 14:56:40.809  4142  4142 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@cadc134
,08-30 14:56:40.811  3890  3890 D BluetoothPan: BluetoothPAN Proxy object connected
,08-30 14:56:40.812  3890  3890 D PanProfile: Bluetooth service connected
08-30 14:56:40.812  4142  4142 D PanService: Received start request. Starting profile...
08-30 14:56:40.812  4142  4142 D BluetoothPanServiceJni: initializeNative(L110): pan
,08-30 14:56:40.812  4142  4142 I bt_bluedroid: get_profile_interface pan
,08-30 14:56:40.813  4142  4158 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,08-30 14:56:40.820  1494  1494 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-30 14:56:40.822  4142  4142 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@cadc134
,08-30 14:56:40.824  4142  4142 D BluetoothMapService: Received start request. Starting profile...
,08-30 14:56:40.824  4142  4142 D BluetoothMapService: start()
,08-30 14:56:40.825  3890  3890 D BluetoothMap: Proxy object connected
,08-30 14:56:40.827  4142  4142 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
08-30 14:56:40.827  3890  3890 D MapProfile: Bluetooth service connected
08-30 14:56:40.827  3890  3890 D BluetoothMap: getConnectedDevices()
08-30 14:56:40.827  4142  4142 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
,08-30 14:56:40.828  4142  4142 D BluetoothMapAppObserver: createReceiver()
08-30 14:56:40.828  3890  3890 D BluetoothMap: Bluetooth is Not enabled
08-30 14:56:40.829  4142  4142 D BluetoothMapAppObserver: initObservers()
08-30 14:56:40.829  4142  4142 D BluetoothMapAppObserver: getEnabledAccountItems()
,08-30 14:56:40.835  4142  4142 V BluetoothAdapterState: isTurningOff()=false
,08-30 14:56:40.835  4142  4142 V BluetoothAdapterState: isTurningOn()=true
08-30 14:56:40.835  4142  4142 V BluetoothAdapterState: isBleTurningOn()=false
08-30 14:56:40.835  4142  4142 V BluetoothAdapterState: isBleTurningOff()=false
,08-30 14:56:40.837  4142  4142 V BluetoothAdapterState: isTurningOff()=false
,08-30 14:56:40.837  4142  4142 V BluetoothAdapterState: isTurningOn()=true
08-30 14:56:40.837  4142  4142 V BluetoothAdapterState: isBleTurningOn()=false
,08-30 14:56:40.837  4142  4142 V BluetoothAdapterState: isBleTurningOff()=false
08-30 14:56:40.837  4142  4170 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,08-30 14:56:40.837  4142  4142 V BluetoothAdapterState: isTurningOff()=false
08-30 14:56:40.837  4142  4142 V BluetoothAdapterState: isTurningOn()=true
,08-30 14:56:40.838  4142  4142 V BluetoothAdapterState: isBleTurningOn()=false
,08-30 14:56:40.838  4142  4142 V BluetoothAdapterState: isBleTurningOff()=false
08-30 14:56:40.838  4142  4142 V BluetoothAdapterState: isTurningOff()=false
08-30 14:56:40.838  4142  4142 V BluetoothAdapterState: isTurningOn()=true
,08-30 14:56:40.838  4142  4142 V BluetoothAdapterState: isBleTurningOn()=false
08-30 14:56:40.838  4142  4142 V BluetoothAdapterState: isBleTurningOff()=false
08-30 14:56:40.838  4142  4142 V BluetoothAdapterState: isTurningOff()=false
,08-30 14:56:40.838  4142  4142 V BluetoothAdapterState: isTurningOn()=true
08-30 14:56:40.838  4142  4142 V BluetoothAdapterState: isBleTurningOn()=false
08-30 14:56:40.838  4142  4142 V BluetoothAdapterState: isBleTurningOff()=false
08-30 14:56:40.839  4142  4142 V BluetoothAdapterState: isTurningOff()=false
,08-30 14:56:40.839  4142  4142 V BluetoothAdapterState: isTurningOn()=true
08-30 14:56:40.839  4142  4142 V BluetoothAdapterState: isBleTurningOn()=false
08-30 14:56:40.839  4142  4142 V BluetoothAdapterState: isBleTurningOff()=false
08-30 14:56:40.840  4142  4154 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
,08-30 14:56:40.840  4142  4154 D BluetoothAdapterProperties: ScanMode =  20
08-30 14:56:40.840  4142  4154 D BluetoothAdapterProperties: State =  11
08-30 14:56:40.842  4142  4154 D BluetoothAdapterProperties: Setting state to 12
08-30 14:56:40.842  4142  4154 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-30 14:56:40.842  4142  4154 I BluetoothAdapterState: Entering OnState
08-30 14:56:40.842  3890  3900 D BluetoothPbap: onBluetoothStateChange: up=true
,08-30 14:56:40.844  4142  4158 D BluetoothAdapterProperties: Scan Mode:21
,08-30 14:56:40.845  4142  4158 D BluetoothAdapterProperties: Discoverable Timeout:120
08-30 14:56:40.846   872   889 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-30 14:56:40.846   872   889 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-30 14:56:40.847  3824  3824 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 14:56:40.847  3824  3824 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 14:56:40.847  3824  3824 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 14:56:40.847  3824  3824 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 14:56:40.847  3824  3824 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 14:56:40.847  3824  3824 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 14:56:40.847  3824  3824 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 14:56:40.847  3824  3824 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 14:56:40.848  1344  4124 D BluetoothPan: onBluetoothStateChange on: true
08-30 14:56:40.849   872   872 D BluetoothA2dp: Proxy object connected
,08-30 14:56:40.850  3824  3824 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-30 14:56:40.853  1344  1344 D BluetoothPan: BluetoothPAN Proxy object connected
08-30 14:56:40.853  1344  1344 D PanProfile: Bluetooth service connected
08-30 14:56:40.854  3824  3824 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 14:56:40.854  3824  3824 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 14:56:40.854  3824  3824 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 14:56:40.854  3824  3824 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 14:56:40.854  3824  3824 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 14:56:40.854  3824  3824 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 14:56:40.854  3824  3824 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 14:56:40.854  3824  3824 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 14:56:40.854  1344  2056 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-30 14:56:40.855  4142  4142 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
08-30 14:56:40.856  4142  4142 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
08-30 14:56:40.856  3824  3824 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-30 14:56:40.857  1344  1344 D BluetoothInputDevice: Proxy object connected
,08-30 14:56:40.857  1344  1344 D HidProfile: Bluetooth service connected
08-30 14:56:40.857  4142  4142 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-30 14:56:40.857  3890  3902 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-30 14:56:40.858  1344  1360 D BluetoothA2dp: onBluetoothStateChange: up=true
08-30 14:56:40.860  4142  4142 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-30 14:56:40.861  1344  1344 D BluetoothA2dp: Proxy object connected
,08-30 14:56:40.861  1344  4125 D BluetoothMap: onBluetoothStateChange: up=true
08-30 14:56:40.863  1344  1344 D BluetoothMap: Proxy object connected
08-30 14:56:40.863  1344  1344 D MapProfile: Bluetooth service connected
08-30 14:56:40.863  1344  1344 D BluetoothMap: getConnectedDevices()
08-30 14:56:40.863  1344  1361 D BluetoothPbap: onBluetoothStateChange: up=true
08-30 14:56:40.863  4142  4142 D ObexServerSockets: Succeed to create listening sockets 
08-30 14:56:40.864  4142  4142 D ObexServerSockets0: startAccept()
,08-30 14:56:40.864  4142  4142 D ObexServerSockets0: prepareForNewConnect()
08-30 14:56:40.865  3890  3900 D BluetoothMap: onBluetoothStateChange: up=true
08-30 14:56:40.865   872   889 D BluetoothHeadset: onBluetoothStateChange: up=true
08-30 14:56:40.866   872   889 D BluetoothHeadset: onBluetoothStateChange: up=true
08-30 14:56:40.866  1344  4124 D BluetoothHeadset: onBluetoothStateChange: up=true
08-30 14:56:40.866  4142  4142 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
,08-30 14:56:40.866  4142  4142 D BluetoothSdpJni: SDP Create record success - handle: 0
,08-30 14:56:40.866  3890  3902 D BluetoothPan: onBluetoothStateChange on: true
08-30 14:56:40.867  1975  2061 D BluetoothHeadset: onBluetoothStateChange: up=true
08-30 14:56:40.868  4142  4179 D ObexServerSockets0: Accepting socket connection...
08-30 14:56:40.869  4142  4180 D ObexServerSockets0: Accepting socket connection...
08-30 14:56:40.870   872   872 I Telecom : BluetoothPhoneService: queryPhoneState
,08-30 14:56:40.871  3824  3824 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 14:56:40.871  4142  4142 D BluetoothMapService: onReceive
08-30 14:56:40.871  4142  4142 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-30 14:56:40.871  4142  4142 D BluetoothMapService: STATE_ON
,08-30 14:56:40.872  3824  3824 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 14:56:40.874  3890  3890 D LocalBluetoothProfileManager: Adding local A2DP profile
,08-30 14:56:40.879  3890  3890 D LocalBluetoothProfileManager: Adding local HEADSET profile
,08-30 14:56:40.885  3890  3890 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-30 14:56:40.887  3890  3890 D BluetoothA2dp: Proxy object connected
,08-30 14:56:40.892  1494  1494 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-30 14:56:40.895  3890  3890 D DockEventReceiver: finishStartingService: stopping service
,08-30 14:56:40.903  4142  4142 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,08-30 14:56:40.903  3890  3890 D BluetoothPbap: Proxy object connected
08-30 14:56:40.903  4142  4142 D ObexServerSockets0: prepareForNewConnect()
08-30 14:56:40.903  1344  1344 D BluetoothPbap: Proxy object connected
08-30 14:56:40.903  1344  1344 D PbapServerProfile: Bluetooth service connected
08-30 14:56:40.903  3890  3890 D PbapServerProfile: Bluetooth service connected
,08-30 14:56:40.912  4142  4185 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-30 14:56:40.933  4142  4189 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-30 14:56:40.935  4142  4189 I BtOppRfcommListener: Accept thread started.
,08-30 14:56:40.947   872   872 D BluetoothHeadset: Proxy object connected
,08-30 14:56:40.948  1344  4124 D BluetoothHeadset: Proxy object connected
08-30 14:56:40.948  1344  1344 D HeadsetProfile: Bluetooth service connected
08-30 14:56:40.948   872   872 D BluetoothHeadset: Proxy object connected
08-30 14:56:40.948   872   872 D BluetoothHeadset: Proxy object connected
,08-30 14:56:40.949  1975  1989 D BluetoothHeadset: Proxy object connected
,08-30 14:56:40.966   872   889 D BluetoothHeadset: Proxy object connected
,08-30 14:56:40.966   872   889 D BluetoothHeadset: Proxy object connected
08-30 14:56:40.967  1344  1360 D BluetoothHeadset: Proxy object connected
08-30 14:56:40.967  1344  1344 D HeadsetProfile: Bluetooth service connected
08-30 14:56:40.967  1975  1990 D BluetoothHeadset: Proxy object connected
,08-30 14:56:40.982  3890  3900 D BluetoothHeadset: Proxy object connected
,08-30 14:56:40.983  3890  3890 D HeadsetProfile: Bluetooth service connected
,08-30 14:56:42.275   872  1306 D ConnectivityService: handlePromptUnvalidated 101
,08-30 14:56:42.289  4142  4154 D BluetoothAdapterState: Current state: ON, message: 23
,08-30 14:56:42.290  4142  4154 D BluetoothAdapterProperties: Setting state to 13
,08-30 14:56:42.290  4142  4154 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-30 14:56:42.293  4142  4154 D BluetoothAdapterProperties: onBluetoothDisable()
,08-30 14:56:42.295  4142  4154 I BluetoothAdapterState: Entering PendingCommandState
,08-30 14:56:42.303  4142  4142 D BluetoothMapService: onReceive
,08-30 14:56:42.304  4142  4142 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-30 14:56:42.304  4142  4142 D BluetoothMapService: STATE_TURNING_OFF
08-30 14:56:42.305  4142  4142 D BluetoothMapService: MAP Service closeService in
08-30 14:56:42.305  4142  4142 D BluetoothMapMasInstance0: MAP Service shutdown
08-30 14:56:42.307  4142  4142 D ObexServerSockets0: shutdown(block = true)
,08-30 14:56:42.308  3824  3824 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 14:56:42.308  3824  3824 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 14:56:42.308  3824  3824 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 14:56:42.308  3824  3824 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 14:56:42.308  3824  3824 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 14:56:42.308  3824  3824 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 14:56:42.308  3824  3824 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 14:56:42.308  3824  3824 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 14:56:42.308  3824  3824 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 14:56:42.308  4142  4179 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
,08-30 14:56:42.310  3824  3824 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-30 14:56:42.310  3824  3824 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-30 14:56:42.311  4142  4142 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-30 14:56:42.313  4142  4158 D BluetoothAdapterProperties: Scan Mode:20
,08-30 14:56:42.313  4142  4142 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-30 14:56:42.313  4142  4180 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
08-30 14:56:42.313  4142  4154 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
08-30 14:56:42.314  4142  4142 I BtOppRfcommListener: stopping Accept Thread
08-30 14:56:42.315  4142  4189 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-30 14:56:42.315  4142  4167 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
08-30 14:56:42.316  4142  4189 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-30 14:56:42.316  3824  3824 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 14:56:42.316  3824  3824 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 14:56:42.316  3824  3824 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 14:56:42.316  3824  3824 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 14:56:42.316  3824  3824 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 14:56:42.316  3824  3824 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 14:56:42.316  3824  3824 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 14:56:42.316  3824  3824 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 14:56:42.316  3824  3824 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-30 14:56:42.319  3824  3824 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 14:56:42.319  3824  3824 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-30 14:56:42.319  4142  4142 D HeadsetService: Received stop request...Stopping profile...
08-30 14:56:42.321  3824  3824 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 14:56:42.322  3890  3902 D BluetoothHeadset: Proxy object disconnected
08-30 14:56:42.322   872   872 D BluetoothHeadset: Proxy object disconnected
08-30 14:56:42.322  1344  4124 D BluetoothHeadset: Proxy object disconnected
08-30 14:56:42.322   872   872 D BluetoothHeadset: Proxy object disconnected
,08-30 14:56:42.323   872   872 D BluetoothHeadset: Proxy object disconnected
08-30 14:56:42.323  1975  2141 D BluetoothHeadset: Proxy object disconnected
08-30 14:56:42.324  3824  3824 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 14:56:42.324  4142  4142 D A2dpService: Received stop request...Stopping profile...
08-30 14:56:42.325  4142  4173 D A2dpStateMachine: Exit Disconnected: -1
,08-30 14:56:42.326   872   872 D BluetoothA2dp: Proxy object disconnected
08-30 14:56:42.327  3890  3890 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-30 14:56:42.327  4142  4142 V BluetoothAdapterState: isTurningOff()=true
08-30 14:56:42.327  4142  4142 V BluetoothAdapterState: isTurningOn()=false
,08-30 14:56:42.327  4142  4142 V BluetoothAdapterState: isBleTurningOn()=false
08-30 14:56:42.327  4142  4142 V BluetoothAdapterState: isBleTurningOff()=false
08-30 14:56:42.328  4142  4142 D HidService: Received stop request...Stopping profile...
08-30 14:56:42.328  4142  4142 D HidService: Stopping Bluetooth HidService
08-30 14:56:42.329  3890  3890 D HeadsetProfile: Bluetooth service disconnected
08-30 14:56:42.330  4142  4142 D HealthService: Received stop request...Stopping profile...
08-30 14:56:42.334  3890  3890 D BluetoothA2dp: Proxy object disconnected
,08-30 14:56:42.335  4142  4142 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
,08-30 14:56:42.335  4142  4142 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
,08-30 14:56:42.335  1344  1344 D HeadsetProfile: Bluetooth service disconnected
08-30 14:56:42.335  4142  4158 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
08-30 14:56:42.335  1344  1344 D BluetoothA2dp: Proxy object disconnected
08-30 14:56:42.335  4142  4164 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-30 14:56:42.335  4142  4164 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-30 14:56:42.336  4142  4164 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-30 14:56:42.336  4142  4142 D PanService: Received stop request...Stopping profile...
08-30 14:56:42.336  4142  4158 E bt_btif : btif_hf_upstreams_evt: Invalid index 17
08-30 14:56:42.336  1344  1344 D BluetoothInputDevice: Proxy object disconnected
,08-30 14:56:42.336  1344  1344 D HidProfile: Bluetooth service disconnected
,08-30 14:56:42.337  1344  1344 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-30 14:56:42.337  1344  1344 D PanProfile: Bluetooth service disconnected
08-30 14:56:42.338  4142  4142 D BluetoothMapService: Received stop request...Stopping profile...
08-30 14:56:42.338  4142  4142 D BluetoothMapService: stop()
08-30 14:56:42.339  4142  4142 D BluetoothMapAppObserver: deinitObservers()
08-30 14:56:42.339  4142  4142 D BluetoothMapAppObserver: removeReceiver()
08-30 14:56:42.340  1344  1344 D BluetoothMap: Proxy object disconnected
08-30 14:56:42.340  1344  1344 D MapProfile: Bluetooth service disconnected
08-30 14:56:42.341  4142  4142 V BluetoothAdapterState: isTurningOff()=true
08-30 14:56:42.341  4142  4142 V BluetoothAdapterState: isTurningOn()=false
,08-30 14:56:42.341  4142  4142 V BluetoothAdapterState: isBleTurningOn()=false
08-30 14:56:42.341  4142  4142 V BluetoothAdapterState: isBleTurningOff()=false
08-30 14:56:42.342  4142  4158 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
08-30 14:56:42.342  4142  4164 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-30 14:56:42.342  4142  4142 V BluetoothAdapterState: isTurningOff()=true
08-30 14:56:42.342  4142  4142 V BluetoothAdapterState: isTurningOn()=false
08-30 14:56:42.342  4142  4142 V BluetoothAdapterState: isBleTurningOn()=false
08-30 14:56:42.342  4142  4164 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-30 14:56:42.342  4142  4142 V BluetoothAdapterState: isBleTurningOff()=false
08-30 14:56:42.343  4142  4164 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-30 14:56:42.343  4142  4164 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,08-30 14:56:42.343  4142  4142 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-30 14:56:42.343  4142  4164 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-30 14:56:42.343  4142  4142 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-30 14:56:42.343  4142  4164 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,08-30 14:56:42.343  4142  4158 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
08-30 14:56:42.343  4142  4142 V BluetoothAdapterState: isTurningOff()=true
08-30 14:56:42.343  4142  4142 V BluetoothAdapterState: isTurningOn()=false
08-30 14:56:42.343  4142  4142 V BluetoothAdapterState: isBleTurningOn()=false
08-30 14:56:42.343  4142  4142 V BluetoothAdapterState: isBleTurningOff()=false
08-30 14:56:42.345  4142  4142 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
,08-30 14:56:42.346  4142  4158 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
08-30 14:56:42.346  1494  1494 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-30 14:56:42.347  4142  4142 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-30 14:56:42.347  4142  4142 V BluetoothAdapterState: isTurningOff()=true
08-30 14:56:42.348  4142  4142 V BluetoothAdapterState: isTurningOn()=false
08-30 14:56:42.348  4142  4142 V BluetoothAdapterState: isBleTurningOn()=false
08-30 14:56:42.348  4142  4142 V BluetoothAdapterState: isBleTurningOff()=false
08-30 14:56:42.348  4142  4142 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-30 14:56:42.348  4142  4142 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-30 14:56:42.349  4142  4142 D BluetoothMapService: MAP Service closeService in
08-30 14:56:42.349  4142  4142 V BluetoothAdapterState: isTurningOff()=true
,08-30 14:56:42.350  4142  4142 V BluetoothAdapterState: isTurningOn()=false
08-30 14:56:42.350  4142  4142 V BluetoothAdapterState: isBleTurningOn()=false
08-30 14:56:42.350  4142  4142 V BluetoothAdapterState: isBleTurningOff()=false
08-30 14:56:42.350  3890  3890 D DockEventReceiver: finishStartingService: stopping service
08-30 14:56:42.350  4142  4154 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
08-30 14:56:42.350  4142  4154 D BluetoothAdapterProperties: Setting state to 15
,08-30 14:56:42.350  4142  4154 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
08-30 14:56:42.350  4142  4142 D BluetoothMapService: cleanup()
08-30 14:56:42.350  4142  4142 D BluetoothMapService: MAP Service closeService in
08-30 14:56:42.351  4142  4154 I BluetoothAdapterState: Entering BleOnState
08-30 14:56:42.351  3890  3900 D BluetoothPbap: onBluetoothStateChange: up=false
08-30 14:56:42.353  1344  1344 D BluetoothPbap: Proxy object disconnected
08-30 14:56:42.353  1344  1344 D PbapServerProfile: Bluetooth service disconnected
,08-30 14:56:42.363   872   889 D BluetoothHeadset: onBluetoothStateChange: up=false
08-30 14:56:42.363   872   889 D BluetoothA2dp: onBluetoothStateChange: up=false
08-30 14:56:42.364  1344  2056 D BluetoothPan: onBluetoothStateChange on: false
08-30 14:56:42.365  3890  3890 D BluetoothInputDevice: Proxy object disconnected
08-30 14:56:42.365  3890  3890 D HidProfile: Bluetooth service disconnected
08-30 14:56:42.365  3890  3890 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-30 14:56:42.365  3890  3890 D PanProfile: Bluetooth service disconnected
08-30 14:56:42.365  3890  3890 D BluetoothMap: Proxy object disconnected
08-30 14:56:42.366  3890  3900 D BluetoothHeadset: onBluetoothStateChange: up=false
08-30 14:56:42.366  3890  3890 D MapProfile: Bluetooth service disconnected
,08-30 14:56:42.366  1344  1361 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-30 14:56:42.368  3890  3900 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-30 14:56:42.368  1344  4125 D BluetoothA2dp: onBluetoothStateChange: up=false
08-30 14:56:42.369  1344  4124 D BluetoothMap: onBluetoothStateChange: up=false
08-30 14:56:42.369  1344  1360 D BluetoothPbap: onBluetoothStateChange: up=false
08-30 14:56:42.370  3890  3902 D BluetoothMap: onBluetoothStateChange: up=false
08-30 14:56:42.370  3890  3900 D BluetoothA2dp: onBluetoothStateChange: up=false
08-30 14:56:42.370   872   889 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-30 14:56:42.370   872   889 D BluetoothHeadset: onBluetoothStateChange: up=false
08-30 14:56:42.371  1344  2056 D BluetoothHeadset: onBluetoothStateChange: up=false
08-30 14:56:42.371  3890  3902 D BluetoothPan: onBluetoothStateChange on: false
08-30 14:56:42.372  1975  2061 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-30 14:56:42.372  4142  4154 D BluetoothAdapterState: Current state: BLE ON, message: 20
,08-30 14:56:42.372  4142  4154 D BluetoothAdapterProperties: Setting state to 16
08-30 14:56:42.372  4142  4154 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
08-30 14:56:42.373  4142  4154 D BluetoothAdapterProperties: onBleDisable
08-30 14:56:42.373  4142  4154 I BluetoothAdapterState: Entering PendingCommandState
08-30 14:56:42.374  4142  4155 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
08-30 14:56:42.374  3824  3824 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 14:56:42.375  4142  4164 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
08-30 14:56:42.375  4142  4164 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-30 14:56:42.375  3824  3824 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 14:56:42.377  4142  4158 D BluetoothAdapterProperties: Scan Mode:20
08-30 14:56:42.378  3824  3824 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 14:56:42.379  3824  3824 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 14:56:42.381  3890  3890 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-30 14:56:42.384  1494  1494 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-30 14:56:42.386  3890  3890 D DockEventReceiver: finishStartingService: stopping service
,08-30 14:56:42.576  4142  4158 I bt_hci  : shut_down
08-30 14:56:42.576  4142  4162 D bt_hwcfg: hw_epilog_process
,08-30 14:56:42.589  4142  4162 I bt_vendor: low_power_mode_cb
,08-30 14:56:42.610  4142  4162 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,08-30 14:56:42.610  4142  4162 I bt_vendor: epilog_cb
08-30 14:56:42.610  4142  4162 I bt_hci  : epilog_finished_callback
,08-30 14:56:42.616  4142  4158 I bt_hci_h4: hal_close
,08-30 14:56:42.617  4142  4158 I bt_userial_vendor: device fd = 51 close
,08-30 14:56:42.752  4142  4155 D bt_stack_manager: event_shut_down_stack finished.
,08-30 14:56:42.753  4142  4154 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,08-30 14:56:42.758  4142  4154 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,08-30 14:56:42.759  4142  4142 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-30 14:56:42.760  4142  4142 D BtGatt.GattService: Received stop request...Stopping profile...
,08-30 14:56:42.761  4142  4142 D BtGatt.GattService: stop()
08-30 14:56:42.761  4142  4142 D BtGatt.AdvertiseManager: advertise clients cleared
,08-30 14:56:42.767  4142  4142 V BluetoothAdapterState: isTurningOff()=false
,08-30 14:56:42.767  4142  4142 V BluetoothAdapterState: isTurningOn()=false
08-30 14:56:42.767  4142  4142 V BluetoothAdapterState: isBleTurningOn()=false
08-30 14:56:42.768  4142  4142 V BluetoothAdapterState: isBleTurningOff()=true
08-30 14:56:42.768  4142  4154 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
,08-30 14:56:42.769  4142  4154 D BluetoothAdapterProperties: Setting state to 10
08-30 14:56:42.770  4142  4154 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
08-30 14:56:42.771  4142  4154 I BluetoothAdapterState: Entering OffState
08-30 14:56:42.773   872   889 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,08-30 14:56:42.799  4142  4142 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,08-30 14:56:42.799  4142  4142 W BluetoothSdpJni: Cleaning up Bluetooth Health object
08-30 14:56:42.800  4142  4155 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,08-30 14:56:42.810  4142  4142 I BluetoothServiceJni: cleanupNative: return from cleanup
,08-30 14:56:42.814  4142  4155 D bt_stack_manager: event_clean_up_stack finished.
,08-30 14:56:42.815  4142  4142 I art     : System.exit called, status: 0
,08-30 14:56:42.816  4142  4142 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-30 14:56:42.868   872   882 I ActivityManager: Process com.android.bluetooth (pid 4142) has died
,08-30 14:56:45.285  3824  3873 D io.jxcore.node.ConnectivityMonitor: stop
08-30 14:56:45.285  3824  3873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-30 14:56:48.292  3824  3873 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-30 14:56:48.293  3824  3873 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@f01ceea added. We now have 6 listener(s)
,08-30 14:56:48.293  3824  3873 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-30 14:56:48.296  3824  3873 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-30 14:56:48.296  3824  3873 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@3cc95db added. We now have 7 listener(s)
08-30 14:56:48.296  3824  3873 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 14:56:48.298  3824  3873 I System.out: IsBluetoothEnabled
,08-30 14:56:48.309  3824  3873 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 14:56:48.341   872   889 I ActivityManager: Start proc 4200:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,08-30 14:56:48.497  4200  4200 D AdapterServiceConfig: Adding HeadsetService
,08-30 14:56:48.497  4200  4200 D AdapterServiceConfig: Adding A2dpService
08-30 14:56:48.497  4200  4200 D AdapterServiceConfig: Adding HidService
08-30 14:56:48.498  4200  4200 D AdapterServiceConfig: Adding HealthService
08-30 14:56:48.498  4200  4200 D AdapterServiceConfig: Adding PanService
08-30 14:56:48.498  4200  4200 D AdapterServiceConfig: Adding GattService
08-30 14:56:48.498  4200  4200 D AdapterServiceConfig: Adding BluetoothMapService
,08-30 14:56:48.511   872   889 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@a3e9d60:true
,08-30 14:56:48.511  4200  4200 D BluetoothAdapterState: make() - Creating AdapterState
,08-30 14:56:48.514  4200  4200 I bt_bluedroid: init
08-30 14:56:48.514  4200  4212 I BluetoothAdapterState: Entering OffState
,08-30 14:56:48.517  4200  4213 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,08-30 14:56:48.517  4200  4213 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-30 14:56:48.517  4200  4213 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-30 14:56:48.517  4200  4213 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,08-30 14:56:48.518  4200  4200 I bt_bluedroid: get_profile_interface socket
,08-30 14:56:48.520  4200  4200 I bt_bluedroid: get_profile_interface sdp
,08-30 14:56:48.522  4200  4216 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-30 14:56:48.523  4200  4211 I bt_bluedroid: config_hci_snoop_log
,08-30 14:56:48.524  4200  4216 D BluetoothAdapterProperties: Name is: Nexus 6
08-30 14:56:48.524   872   889 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,08-30 14:56:48.529  4200  4212 D BluetoothAdapterState: Current state: OFF, message: 0
,08-30 14:56:48.529  4200  4212 D BluetoothAdapterProperties: Setting state to 14
08-30 14:56:48.529  4200  4212 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,08-30 14:56:48.531  4200  4212 D BluetoothBondStateMachine: make
,08-30 14:56:48.533  4200  4217 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-30 14:56:48.536  4200  4212 I BluetoothAdapterState: Entering PendingCommandState
,08-30 14:56:48.537  4200  4200 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,08-30 14:56:48.539  4200  4200 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@cadc134
,08-30 14:56:48.540  4200  4200 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-30 14:56:48.541  4200  4200 D BtGatt.GattService: Received start request. Starting profile...
08-30 14:56:48.541  4200  4200 D BtGatt.GattService: start()
08-30 14:56:48.541  4200  4200 I bt_bluedroid: get_profile_interface gatt
08-30 14:56:48.542  4200  4200 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@cadc134
,08-30 14:56:48.542  4200  4200 D BtGatt.AdvertiseManager: advertise manager created
,08-30 14:56:48.548  4200  4200 V BluetoothAdapterState: isTurningOff()=false
,08-30 14:56:48.549  4200  4200 V BluetoothAdapterState: isTurningOn()=false
08-30 14:56:48.549  4200  4200 V BluetoothAdapterState: isBleTurningOn()=true
08-30 14:56:48.549  4200  4200 V BluetoothAdapterState: isBleTurningOff()=false
08-30 14:56:48.549  4200  4212 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
08-30 14:56:48.549  4200  4212 I bt_bluedroid: enable
,08-30 14:56:48.550  4200  4213 D bt_stack_manager: event_start_up_stack is bringing up the stack.
08-30 14:56:48.550  4200  4213 I bt_hci  : start_up
,08-30 14:56:48.559  4200  4213 I bt_vendor: alloc value 0xb3a1d189
,08-30 14:56:48.559  4200  4213 I bt_vendor: init
08-30 14:56:48.559  4200  4213 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
08-30 14:56:48.559  4200  4213 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,08-30 14:56:48.666  4200  4213 D bt_hci  : start_up starting async portion
08-30 14:56:48.667  4200  4220 I bt_hci  : event_finish_startup
,08-30 14:56:48.667  4200  4220 I bt_hci_h4: hal_open
08-30 14:56:48.667  4200  4220 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,08-30 14:56:48.673  4200  4220 I bt_userial_vendor: device fd = 51 open
,08-30 14:56:48.709  4200  4220 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-30 14:56:48.741  4200  4220 D bt_hwcfg: Chipset BCM4354A2
08-30 14:56:48.741  4200  4220 D bt_hwcfg: Target name = [BCM4354A2]
,08-30 14:56:48.742  4200  4220 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,08-30 14:56:49.423  4200  4220 I bt_hwcfg: bt vendor lib: set UART baud 115200
,08-30 14:56:49.425  4200  4220 D bt_hwcfg: Settlement delay -- 100 ms
08-30 14:56:49.425  4200  4220 I bt_hwcfg: Setting fw settlement delay to 100 
,08-30 14:56:49.542  4200  4220 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-30 14:56:49.544  4200  4220 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,08-30 14:56:49.573  4200  4220 I bt_hwcfg: vendor lib fwcfg completed
,08-30 14:56:49.573  4200  4220 I bt_vendor: firmware callback
08-30 14:56:49.573  4200  4220 I bt_hci  : firmware_config_callback
,08-30 14:56:49.586  4200  4222 I bt_btu  : btu_task pending for preload complete event
,08-30 14:56:49.586  4200  4222 I bt_btu_task: Bluetooth chip preload is complete
,08-30 14:56:49.587  4200  4222 I bt_btu  : btu_task received preload complete event
,08-30 14:56:49.597  4200  4222 I         : BTE_InitTraceLevels -- TRC_HCI
,08-30 14:56:49.597  4200  4222 I         : BTE_InitTraceLevels -- TRC_L2CAP
,08-30 14:56:49.598  4200  4222 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,08-30 14:56:49.598  4200  4222 I         : BTE_InitTraceLevels -- TRC_AVDT
08-30 14:56:49.598  4200  4222 I         : BTE_InitTraceLevels -- TRC_AVRC
08-30 14:56:49.598  4200  4222 I         : BTE_InitTraceLevels -- TRC_A2D
,08-30 14:56:49.599  4200  4222 I         : BTE_InitTraceLevels -- TRC_BNEP
08-30 14:56:49.599  4200  4222 I         : BTE_InitTraceLevels -- TRC_BTM
08-30 14:56:49.599  4200  4222 I         : BTE_InitTraceLevels -- TRC_GAP
,08-30 14:56:49.599  4200  4222 I         : BTE_InitTraceLevels -- TRC_PAN
08-30 14:56:49.600  4200  4222 I         : BTE_InitTraceLevels -- TRC_SDP
08-30 14:56:49.600  4200  4222 I         : BTE_InitTraceLevels -- TRC_GATT
,08-30 14:56:49.600  4200  4222 I         : BTE_InitTraceLevels -- TRC_SMP
08-30 14:56:49.601  4200  4222 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-30 14:56:49.601  4200  4222 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-30 14:56:49.738  4200  4222 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb399ad9d
,08-30 14:56:49.739  4200  4222 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb399ad9d 
,08-30 14:56:49.762  4200  4216 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,08-30 14:56:49.765  4200  4216 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,08-30 14:56:49.766  4200  4216 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-30 14:56:49.773  4200  4216 D BluetoothAdapterProperties: Name is: Nexus 6
,08-30 14:56:49.779  4200  4216 D BluetoothAdapterProperties: Scan Mode:20
,08-30 14:56:49.779  4200  4216 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-30 14:56:49.780  4200  4216 D bt_hci  : do_postload posting postload work item
,08-30 14:56:49.781  4200  4220 I bt_hci  : event_postload
08-30 14:56:49.781  4200  4220 I bt_vendor: sco_config_cb
,08-30 14:56:49.781  4200  4220 I bt_hci  : sco_config_callback postload finished.
,08-30 14:56:49.783  3824  3824 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 14:56:49.783  4200  4216 D bt_bte_conf: Device ID record 1 : primary
,08-30 14:56:49.783  4200  4216 D bt_bte_conf:   vendorId            = 000f
,08-30 14:56:49.784  4200  4216 D bt_bte_conf:   vendorIdSource      = 0001
,08-30 14:56:49.784  4200  4216 D bt_bte_conf:   product             = 1200
,08-30 14:56:49.784  4200  4216 D bt_bte_conf:   version             = 1436
08-30 14:56:49.784  4200  4216 D bt_bte_conf:   clientExecutableURL = 
,08-30 14:56:49.784  4200  4216 D bt_bte_conf:   serviceDescription  = 
08-30 14:56:49.785  4200  4216 D bt_bte_conf:   documentationURL    = 
,08-30 14:56:49.785  4200  4216 D bt_bte_conf: bte_load_did_conf no section named DID2.
,08-30 14:56:49.785  4200  4213 D bt_stack_manager: event_start_up_stack finished
08-30 14:56:49.786  4200  4220 I bt_vendor: low_power_mode_cb
,08-30 14:56:49.787  4200  4212 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
08-30 14:56:49.787  4200  4212 D BluetoothAdapterProperties: Setting state to 15
08-30 14:56:49.788  4200  4212 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
08-30 14:56:49.788  4200  4212 I BluetoothAdapterState: Entering BleOnState
,08-30 14:56:49.793  4200  4212 D BluetoothAdapterState: Current state: BLE ON, message: 1
,08-30 14:56:49.794  4200  4212 D BluetoothAdapterProperties: Setting state to 11
,08-30 14:56:49.794  4200  4212 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,08-30 14:56:49.802  3824  3824 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 14:56:49.813  4200  4200 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@cadc134
,08-30 14:56:49.814  4200  4200 D HeadsetService: Received start request. Starting profile...
,08-30 14:56:49.817  4200  4200 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,08-30 14:56:49.817  4200  4200 D HeadsetStateMachine: make
,08-30 14:56:49.825  4200  4200 D HeadsetStateMachine: max_hf_connections = 1
,08-30 14:56:49.825  4200  4200 I bt_bluedroid: get_profile_interface handsfree,
,08-30 14:56:49.825  4200  4216 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
,08-30 14:56:49.828  4200  4216 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
,08-30 14:56:49.830  4200  4212 I BluetoothAdapterState: Entering PendingCommandState
,08-30 14:56:49.833  4200  4200 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@cadc134
,08-30 14:56:49.833  4200  4200 D A2dpService: Received start request. Starting profile...
,08-30 14:56:49.834  4200  4200 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-30 14:56:49.834  1494  1494 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-30 14:56:49.834  4200  4200 I bt_bluedroid: get_profile_interface avrcp
,08-30 14:56:49.843  4200  4200 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-30 14:56:49.843  4200  4200 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-30 14:56:49.843  4200  4200 D A2dpStateMachine: make
,08-30 14:56:49.844  4200  4200 I bt_bluedroid: get_profile_interface a2dp
,08-30 14:56:49.846  4200  4216 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,08-30 14:56:49.847  4200  4200 I BluetoothHidServiceJni: classInitNative: succeeds
,08-30 14:56:49.848  4200  4200 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@cadc134
,08-30 14:56:49.849  4200  4231 D A2dpStateMachine: Enter Disconnected: -2
,08-30 14:56:49.849  4200  4200 D HidService: Received start request. Starting profile...
08-30 14:56:49.849  4200  4200 I bt_bluedroid: get_profile_interface hidhost
08-30 14:56:49.850  4200  4216 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb397c3e5
08-30 14:56:49.850  4200  4216 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
,08-30 14:56:49.850  4200  4200 D HidService: setHidService(): set to: null
,08-30 14:56:49.853  4200  4200 I BluetoothHealthServiceJni: classInitNative: succeeds
,08-30 14:56:49.854  4200  4200 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@cadc134
,08-30 14:56:49.855  4200  4200 D HealthService: Received start request. Starting profile...
,08-30 14:56:49.857  4200  4200 I bt_bluedroid: get_profile_interface health
,08-30 14:56:49.858  4200  4200 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,08-30 14:56:49.860  4200  4200 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@cadc134
,08-30 14:56:49.861  4200  4200 D PanService: Received start request. Starting profile...
,08-30 14:56:49.861  4200  4200 D BluetoothPanServiceJni: initializeNative(L110): pan
,08-30 14:56:49.861  4200  4200 I bt_bluedroid: get_profile_interface pan
,08-30 14:56:49.862  4200  4216 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,08-30 14:56:49.867  4200  4200 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@cadc134
,08-30 14:56:49.868  4200  4200 D BluetoothMapService: Received start request. Starting profile...
,08-30 14:56:49.868  4200  4200 D BluetoothMapService: start()
,08-30 14:56:49.873  4200  4200 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,08-30 14:56:49.874  4200  4200 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
,08-30 14:56:49.874  4200  4200 D BluetoothMapAppObserver: createReceiver()
,08-30 14:56:49.875  4200  4200 D BluetoothMapAppObserver: initObservers()
,08-30 14:56:49.875  4200  4200 D BluetoothMapAppObserver: getEnabledAccountItems(),
,08-30 14:56:49.883  4200  4200 V BluetoothAdapterState: isTurningOff()=false
,08-30 14:56:49.883  4200  4200 V BluetoothAdapterState: isTurningOn()=true
08-30 14:56:49.883  4200  4200 V BluetoothAdapterState: isBleTurningOn()=false
08-30 14:56:49.883  4200  4200 V BluetoothAdapterState: isBleTurningOff()=false,
,08-30 14:56:49.886  4200  4229 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,08-30 14:56:49.886  4200  4200 V BluetoothAdapterState: isTurningOff()=false
,08-30 14:56:49.886  4200  4200 V BluetoothAdapterState: isTurningOn()=true
08-30 14:56:49.887  4200  4200 V BluetoothAdapterState: isBleTurningOn()=false
,08-30 14:56:49.887  4200  4200 V BluetoothAdapterState: isBleTurningOff()=false
08-30 14:56:49.887  4200  4200 V BluetoothAdapterState: isTurningOff()=false
,08-30 14:56:49.887  4200  4200 V BluetoothAdapterState: isTurningOn()=true
08-30 14:56:49.887  4200  4200 V BluetoothAdapterState: isBleTurningOn()=false,
,08-30 14:56:49.888  4200  4200 V BluetoothAdapterState: isBleTurningOff()=false
08-30 14:56:49.888  4200  4200 V BluetoothAdapterState: isTurningOff()=false
,08-30 14:56:49.888  4200  4200 V BluetoothAdapterState: isTurningOn()=true
08-30 14:56:49.888  4200  4200 V BluetoothAdapterState: isBleTurningOn()=false
08-30 14:56:49.888  4200  4200 V BluetoothAdapterState: isBleTurningOff()=false
08-30 14:56:49.889  4200  4200 V BluetoothAdapterState: isTurningOff()=false
,08-30 14:56:49.889  4200  4200 V BluetoothAdapterState: isTurningOn()=true
08-30 14:56:49.889  4200  4200 V BluetoothAdapterState: isBleTurningOn()=false
08-30 14:56:49.889  4200  4200 V BluetoothAdapterState: isBleTurningOff()=false
08-30 14:56:49.890  4200  4200 V BluetoothAdapterState: isTurningOff()=false
08-30 14:56:49.890  4200  4200 V BluetoothAdapterState: isTurningOn()=true
,08-30 14:56:49.890  4200  4200 V BluetoothAdapterState: isBleTurningOn()=false
08-30 14:56:49.890  4200  4200 V BluetoothAdapterState: isBleTurningOff()=false
,08-30 14:56:49.890  4200  4212 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
,08-30 14:56:49.890  4200  4212 D BluetoothAdapterProperties: ScanMode =  20
,08-30 14:56:49.891  4200  4212 D BluetoothAdapterProperties: State =  11
,08-30 14:56:49.892  4200  4212 D BluetoothAdapterProperties: Setting state to 12
,08-30 14:56:49.892  4200  4212 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-30 14:56:49.894  3890  3902 D BluetoothPbap: onBluetoothStateChange: up=true
,08-30 14:56:49.894  4200  4216 D BluetoothAdapterProperties: Scan Mode:21
,08-30 14:56:49.894  4200  4216 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-30 14:56:49.895   872   889 D BluetoothHeadset: onBluetoothStateChange: up=true
08-30 14:56:49.896   872   889 D BluetoothA2dp: onBluetoothStateChange: up=true
08-30 14:56:49.896  1344  1361 D BluetoothPan: onBluetoothStateChange on: true
08-30 14:56:49.898   872   872 D BluetoothA2dp: Proxy object connected
08-30 14:56:49.898  3824  3824 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 14:56:49.898  3824  3824 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 14:56:49.898  3824  3824 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 14:56:49.898  3824  3824 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 14:56:49.898  3824  3824 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 14:56:49.898  3824  3824 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 14:56:49.898  3824  3824 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 14:56:49.898  3824  3824 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-30 14:56:49.900  4200  4212 I BluetoothAdapterState: Entering OnState
08-30 14:56:49.901  1344  1344 D BluetoothPan: BluetoothPAN Proxy object connected
08-30 14:56:49.901  1344  1344 D PanProfile: Bluetooth service connected
08-30 14:56:49.901  3824  3824 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-30 14:56:49.901  3890  3900 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-30 14:56:49.903  1344  2056 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-30 14:56:49.903  4200  4200 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
08-30 14:56:49.904  4200  4200 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
08-30 14:56:49.906  4200  4200 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-30 14:56:49.910  4200  4200 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-30 14:56:49.911  3890  3902 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-30 14:56:49.912  4200  4200 D ObexServerSockets: Succeed to create listening sockets 
08-30 14:56:49.912  4200  4200 D ObexServerSockets0: startAccept()
08-30 14:56:49.912  4200  4200 D ObexServerSockets0: prepareForNewConnect()
08-30 14:56:49.915  1344  4124 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-30 14:56:49.915  4200  4200 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
08-30 14:56:49.915  4200  4200 D BluetoothSdpJni: SDP Create record success - handle: 0
08-30 14:56:49.917  1344  1344 D BluetoothInputDevice: Proxy object connected
08-30 14:56:49.917  1344  1344 D HidProfile: Bluetooth service connected
08-30 14:56:49.919  1344  1361 D BluetoothMap: onBluetoothStateChange: up=true
08-30 14:56:49.918  4200  4237 D ObexServerSockets0: Accepting socket connection...
,08-30 14:56:49.920  1344  1344 D BluetoothA2dp: Proxy object connected
08-30 14:56:49.921  1344  4125 D BluetoothPbap: onBluetoothStateChange: up=true
08-30 14:56:49.921  4200  4238 D ObexServerSockets0: Accepting socket connection...
08-30 14:56:49.922  1344  1344 D BluetoothMap: Proxy object connected
08-30 14:56:49.923  1344  1344 D MapProfile: Bluetooth service connected
08-30 14:56:49.923  1344  1344 D BluetoothMap: getConnectedDevices()
,08-30 14:56:49.924  3890  3902 D BluetoothMap: onBluetoothStateChange: up=true
,08-30 14:56:49.928  3890  3900 D BluetoothA2dp: onBluetoothStateChange: up=true
08-30 14:56:49.928  3890  3890 D BluetoothInputDevice: Proxy object connected
08-30 14:56:49.928  3890  3890 D HidProfile: Bluetooth service connected
,08-30 14:56:49.929   872   889 D BluetoothHeadset: onBluetoothStateChange: up=true
08-30 14:56:49.929   872   889 D BluetoothHeadset: onBluetoothStateChange: up=true
08-30 14:56:49.930  1344  4124 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-30 14:56:49.930  3890  3902 D BluetoothPan: onBluetoothStateChange on: true
,08-30 14:56:49.932  1975  2141 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-30 14:56:49.933  3890  3890 D BluetoothMap: Proxy object connected
08-30 14:56:49.933  3890  3890 D MapProfile: Bluetooth service connected
08-30 14:56:49.933  3890  3890 D BluetoothMap: getConnectedDevices()
,08-30 14:56:49.934   872   872 I Telecom : BluetoothPhoneService: queryPhoneState
08-30 14:56:49.935  4200  4200 D BluetoothMapService: onReceive
,08-30 14:56:49.935  4200  4200 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-30 14:56:49.936  4200  4200 D BluetoothMapService: STATE_ON
08-30 14:56:49.937  3824  3824 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 14:56:49.938  3890  3890 D BluetoothA2dp: Proxy object connected
,08-30 14:56:49.940  3890  3890 D BluetoothPan: BluetoothPAN Proxy object connected
,08-30 14:56:49.941  3890  3890 D PanProfile: Bluetooth service connected
,08-30 14:56:49.945  3890  3890 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-30 14:56:49.951  1494  1494 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-30 14:56:49.958  3890  3890 D DockEventReceiver: finishStartingService: stopping service
,08-30 14:56:49.960  1344  1344 D BluetoothPbap: Proxy object connected
08-30 14:56:49.960  1344  1344 D PbapServerProfile: Bluetooth service connected
,08-30 14:56:49.962  3890  3890 D BluetoothPbap: Proxy object connected
08-30 14:56:49.962  3890  3890 D PbapServerProfile: Bluetooth service connected
,08-30 14:56:49.964  4200  4200 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,08-30 14:56:49.964  4200  4200 D ObexServerSockets0: prepareForNewConnect()
,08-30 14:56:49.966  4200  4243 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-30 14:56:49.983  4200  4247 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-30 14:56:49.984  4200  4247 I BtOppRfcommListener: Accept thread started.
,08-30 14:56:49.997  3890  3900 D BluetoothHeadset: Proxy object connected
,08-30 14:56:49.997  3890  3890 D HeadsetProfile: Bluetooth service connected
,08-30 14:56:49.997   872   872 D BluetoothHeadset: Proxy object connected
,08-30 14:56:49.997  1344  1361 D BluetoothHeadset: Proxy object connected
,08-30 14:56:49.998   872   872 D BluetoothHeadset: Proxy object connected
08-30 14:56:49.998   872   872 D BluetoothHeadset: Proxy object connected
08-30 14:56:49.998  1344  1344 D HeadsetProfile: Bluetooth service connected
08-30 14:56:49.998  1975  2061 D BluetoothHeadset: Proxy object connected
,08-30 14:56:50.002  3890  3902 D BluetoothHeadset: Proxy object connected
,08-30 14:56:50.002  3890  3890 D HeadsetProfile: Bluetooth service connected
,08-30 14:56:50.029   872   889 D BluetoothHeadset: Proxy object connected
,08-30 14:56:50.030   872   889 D BluetoothHeadset: Proxy object connected
,08-30 14:56:50.031  1344  1360 D BluetoothHeadset: Proxy object connected
,08-30 14:56:50.031  1344  1344 D HeadsetProfile: Bluetooth service connected
,08-30 14:56:50.033  1975  1989 D BluetoothHeadset: Proxy object connected
,08-30 14:56:50.328  3824  3873 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 14:56:50.328  3824  3873 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 14:56:50.328  3824  3873 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 14:56:50.328  3824  3873 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 14:56:50.328  3824  3873 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 14:56:50.328  3824  3873 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 14:56:50.328  3824  3873 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 14:56:50.328  3824  3873 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-30 14:56:50.335  3824  3873 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-30 14:56:50.338  3824  3873 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-30 14:56:50.338  3824  3873 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@626b878 added. We now have 8 listener(s)
08-30 14:56:50.339  3824  3873 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-30 14:56:50.344   872  1982 D WifiService: setWifiEnabled: false pid=3824, uid=10000
08-30 14:56:50.344   872  1982 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-30 14:56:50.356  3824  3873 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 14:56:50.357   872  2026 D WifiService: setWifiEnabled: true pid=3824, uid=10000
,08-30 14:56:50.357   872  2026 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-30 14:56:50.370   872  1302 D WifiConfigStore: Loading config and enabling all networks 
,08-30 14:56:50.384  3824  3824 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 14:56:50.384  3824  3824 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 14:56:50.384  3824  3824 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 14:56:50.384  3824  3824 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 14:56:50.384  3824  3824 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 14:56:50.384  3824  3824 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 14:56:50.384  3824  3824 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 14:56:50.384  3824  3824 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 14:56:50.391  3824  3824 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-30 14:56:50.400   872  1302 D WifiConfigStore: loaded 0 passpoint configs
,08-30 14:56:50.401   872  1302 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,08-30 14:56:50.402   872  1302 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,08-30 14:56:50.402   872  1302 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,08-30 14:56:50.403   872  1302 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
,08-30 14:56:50.403   872  1302 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
08-30 14:56:50.403   872  1302 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,08-30 14:56:50.414   370   870 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,08-30 14:56:50.415   872  1302 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.18 rxSuccessRate=0.35 delta 1000 -> 1000
,08-30 14:56:50.415   370   870 D CommandListener: Setting iface cfg
08-30 14:56:50.416   872  1301 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '157 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 157 Failed to set address (No such device)'
08-30 14:56:50.416   872  1301 D WifiMonitor: startMonitoring(p2p0) with mConnected = true,
,08-30 14:56:50.423   872  1302 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
,08-30 14:56:50.423   872  1301 D WifiNative-HAL: p2pGetDeviceAddress
08-30 14:56:50.423   872  1302 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-30 14:56:50.424   872  1301 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,08-30 14:56:50.434   872  1302 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,08-30 14:56:50.481   872  1302 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,08-30 14:56:50.482  1458  1458 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,08-30 14:56:50.952  1458  1458 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-30 14:56:50.985  1458  1458 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,08-30 14:56:50.986  1458  1458 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,08-30 14:56:50.993   872  1302 D WifiConfigStore: Retrieve network priorities after PNO.
,08-30 14:56:51.003   872  1302 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
08-30 14:56:51.003   872  1302 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-30 14:56:51.004   872  1306 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,08-30 14:56:51.018   872  1302 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-30 14:56:51.032   370   870 D CommandListener: Setting iface cfg
,08-30 14:56:51.033   872  1302 D WifiStateMachine: Start Dhcp Watchdog 3
,08-30 14:56:51.044   872  1306 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,08-30 14:56:51.045   872  1306 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 102] to 60
,08-30 14:56:51.048   872  1302 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,08-30 14:56:51.062   872  4255 D DhcpClient: Receive thread started
,08-30 14:56:51.145   872  1302 E native  : do suspend false
,08-30 14:56:51.165   872  2121 D DhcpClient: Broadcasting DHCPDISCOVER
,08-30 14:56:51.182   872  4255 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.101, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172783, domain null
,08-30 14:56:51.183   872  2121 D DhcpClient: Got pending lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172783 seconds
,08-30 14:56:51.187   872  2121 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.101 serverid=192.168.1.1
,08-30 14:56:51.202   872  4255 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.101, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,08-30 14:56:51.203   872  2121 D DhcpClient: Confirmed lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,08-30 14:56:51.209   370   870 D CommandListener: Setting iface cfg
,08-30 14:56:51.220   872  2121 D DhcpClient: Scheduling renewal in 86399s
,08-30 14:56:51.221   872  1302 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,08-30 14:56:51.238   872  1302 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,08-30 14:56:51.241   872  1302 D WifiConfigStore: No blacklist allowed without epno enabled
,08-30 14:56:51.242   872  1306 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,08-30 14:56:51.243   872  1306 D ConnectivityService: Adding iface wlan0 to network 102
,08-30 14:56:51.255   872  1302 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,08-30 14:56:51.310   872  1306 E ConnectivityService: Unexpected mtu value: 0, wlan0
,08-30 14:56:51.310   872  1306 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
,08-30 14:56:51.311   872  1306 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
,08-30 14:56:51.315   872  1306 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102,
,08-30 14:56:51.317   872  1306 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
,08-30 14:56:51.331   872  1306 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,08-30 14:56:51.342   872  1306 D ConnectivityService: scheduleUnvalidatedPrompt 102
,08-30 14:56:51.343   872  1306 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 102]
,08-30 14:56:51.343   872  1302 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
,08-30 14:56:51.343   872  1306 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 102]
08-30 14:56:51.343   872  1306 D ConnectivityService:    accepting network in place of null
,08-30 14:56:51.344   872  1302 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-30 14:56:51.345   872  1306 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.101/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -46]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-30 14:56:51.357   872  4254 D NetlinkSocketObserver: NeighborEvent{elapsedMs=148762, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-30 14:56:51.377  3824  3873 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 14:56:51.377  3824  3873 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 14:56:51.377  3824  3873 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 14:56:51.377  3824  3873 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 14:56:51.377  3824  3873 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 14:56:51.377  3824  3873 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 14:56:51.377  3824  3873 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 14:56:51.377  3824  3873 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-30 14:56:51.381  3824  3873 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-30 14:56:51.385   370   870 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-30 14:56:51.391  3824  3873 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,08-30 14:56:51.393  3824  3873 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,08-30 14:56:51.398  3824  3873 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@fffbca0 Bundle[{}]
,08-30 14:56:51.399  3824  3873 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-30 14:56:51.399  3824  3873 I io.jxcore.node.LifeCycleMonitor: stop: OK
,08-30 14:56:51.400  3824  3873 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,08-30 14:56:51.400  3824  3873 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,08-30 14:56:51.401  3824  3873 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
,08-30 14:56:51.402  3824  3873 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,08-30 14:56:51.406  3824  3873 I System.out: Running OutgoingSocketThread
,08-30 14:56:51.407  3824  4262 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 425)
,08-30 14:56:51.408  3824  4262 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 49245
,08-30 14:56:51.408  3824  4262 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,08-30 14:56:51.434   370   870 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-30 14:56:51.438   872  1306 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
,08-30 14:56:51.439   872  1306 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-30 14:56:51.443   872   889 D Tethering: MasterInitialState.processMessage what=3
08-30 14:56:51.448   872  1306 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
08-30 14:56:51.458  3824  3824 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 14:56:51.458  3824  3824 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 14:56:51.458  3824  3824 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 14:56:51.458  3824  3824 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 14:56:51.458  3824  3824 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 14:56:51.458  3824  3824 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 14:56:51.458  3824  3824 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 14:56:51.458  3824  3824 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-30 14:56:51.460  3824  3824 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-30 14:56:51.467  2065  2065 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
,08-30 14:56:51.472  1709  1709 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-30 14:56:51.476  1709  1709 D SystemUpdateService: onCreate
,08-30 14:56:51.480  1709  1709 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-30 14:56:51.490  1709  4265 I SystemUpdateService: active receiver: enabled
,08-30 14:56:51.503  1709  4265 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-30 14:56:51.504  1709  1709 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,08-30 14:56:51.508  1709  2527 I iu.UploadsManager: num queued entries: 0
,08-30 14:56:51.509  1709  2527 I iu.UploadsManager: num updated entries: 0
,08-30 14:56:51.514  1709  1709 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-30 14:56:51.517  1709  1709 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-30 14:56:51.518  1709  4265 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
08-30 14:56:51.519  1709  4265 I SystemUpdateService: now status is 0 (complete)
08-30 14:56:51.519  1709  4265 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
,08-30 14:56:51.519  1709  4265 I SystemUpdateService: file has been verified
08-30 14:56:51.520  3944  3944 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-30 14:56:51.521  1709  2527 I iu.SyncManager: NEXT; no task
,08-30 14:56:51.526  1709  4268 I MDM     : [185] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
,08-30 14:56:51.526  1709  4268 W BaseAppContext: Using Auth Proxy for data requests.
,08-30 14:56:51.528  3944  3944 D SprintDMHelper: simOperator: 
,08-30 14:56:51.528  3944  3944 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-30 14:56:51.537  1709  4265 I SystemUpdateService: OTA package size = 12249756
,08-30 14:56:51.539  1709  4268 V GoogleAuthProtoRequest: [185] a.<init>: mAccountName set to: thalitester@gmail.com
,08-30 14:56:51.549  1709  4265 I SystemUpdateService: showing system update notification
,08-30 14:56:51.557  1494  1494 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-30 14:56:51.561  1494  1494 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-30 14:56:51.592  1709  1709 D SystemUpdateService: onDestroy
,08-30 14:56:51.617  1494  2028 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
,08-30 14:56:51.617  1494  2028 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
08-30 14:56:51.617  1494  2028 I GLSUser : [GLSUser] Extracting token using key: Auth
08-30 14:56:51.617  1494  2028 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-30 14:56:51.636  1709  4268 E MDM     : [185] SitrepService.a: Error sending sitrep.
,08-30 14:56:52.048   872  4253 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.214.206,2a00:1450:400d:802::200e
,08-30 14:56:52.259   872  4253 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 30 Aug 2016 12:56:52 GMT], X-Android-Received-Millis=[1472561812257], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1472561812208]}
,08-30 14:56:52.265   872  1306 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,08-30 14:56:52.269   872  1306 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] validation  passed
,08-30 14:56:52.270   872  1306 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
08-30 14:56:52.279   872  1306 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,08-30 14:56:52.290  3109  4270 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,08-30 14:56:52.409  3824  3873 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 426)
08-30 14:56:52.409  3824  3873 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 426)
,08-30 14:56:52.419  3824  3873 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 431)
,08-30 14:56:52.421  3824  3873 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
,08-30 14:56:52.421  3824  3873 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 432)
,08-30 14:56:52.430  3824  3873 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-30 14:56:52.431  3824  3873 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f814b51 added. We now have 2 listener(s)
,08-30 14:56:52.439   872  1306 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 101] cleared because we found a replacement network
,08-30 14:56:52.441  3824  3873 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-30 14:56:52.442  3824  3873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-30 14:56:52.443  3824  3873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-30 14:56:52.443  3824  3873 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-30 14:56:52.444  3824  3873 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a5efb6 added. We now have 9 listener(s)
,08-30 14:56:52.445  3824  3873 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-30 14:56:52.447  3824  3873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-30 14:56:52.479  3824  3873 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-30 14:56:52.484  3824  3873 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 14:56:52.484  3824  3873 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 14:56:52.484  3824  3873 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 14:56:52.484  3824  3873 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 14:56:52.484  3824  3873 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 14:56:52.484  3824  3873 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 14:56:52.484  3824  3873 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 14:56:52.484  3824  3873 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-30 14:56:52.486  3824  3873 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-30 14:56:52.487  3824  3873 D io.jxcore.node.ConnectivityMonitor: start: OK
08-30 14:56:52.487  3824  3873 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-30 14:56:52.487  3824  3873 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@74ae424 added. We now have 3 listener(s)
08-30 14:56:52.489  3824  3873 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-30 14:56:52.489  3824  3873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-30 14:56:52.489  3824  3873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-30 14:56:52.489  3824  3873 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-30 14:56:52.489  3824  3873 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@43e4b8d added. We now have 10 listener(s)
08-30 14:56:52.489  3824  3873 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 14:56:52.489  3824  3873 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 14:56:52.489  3824  3873 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 14:56:52.489  3824  3873 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-30 14:56:52.490  3824  3873 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 14:56:52.490  3824  3873 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 14:56:52.490  3824  3873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-30 14:56:52.490  3824  3873 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-30 14:56:52.490  3824  3873 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f814b51 removed from the list
,08-30 14:56:52.490  3824  3873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 14:56:52.490  3824  3873 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a5efb6 removed from the list
,08-30 14:56:52.494  3824  3824 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 14:56:52.497  3824  3824 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 14:56:52.497  3824  3873 D io.jxcore.node.ConnectivityMonitor: stop
08-30 14:56:52.497  3824  3873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 14:56:52.497  3824  3873 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 14:56:52.497  3824  3873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-30 14:56:52.498  3824  3873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 14:56:52.498  3824  3873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 14:56:52.499  3824  3873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-30 14:56:52.499  3824  3873 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a5efb6 not in the list
08-30 14:56:52.499  3824  3873 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 14:56:52.499  3824  3873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-30 14:56:52.500  3824  3873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 14:56:52.500  3824  3873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 14:56:52.500  3824  3873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 14:56:52.500  3824  3873 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@43e4b8d removed from the list
,08-30 14:56:52.500  3824  3873 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 14:56:52.501  3824  3873 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 14:56:52.501  3824  3873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 14:56:52.501  3824  3873 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-30 14:56:52.501  3824  3873 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@74ae424 removed from the list
,08-30 14:56:52.502  3824  3873 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-30 14:56:52.502  3824  3873 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5995142 added. We now have 2 listener(s)
,08-30 14:56:52.504  3824  3873 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-30 14:56:52.504  3824  3873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-30 14:56:52.504  3824  3873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-30 14:56:52.514  3824  3873 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 14:56:52.515  3824  3873 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@415e553 added. We now have 9 listener(s)
,08-30 14:56:52.515  3824  3873 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 14:56:52.515  3824  3873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-30 14:56:52.519  3824  3873 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-30 14:56:52.528  3824  3873 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 14:56:52.528  3824  3873 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 14:56:52.528  3824  3873 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 14:56:52.528  3824  3873 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 14:56:52.528  3824  3873 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 14:56:52.528  3824  3873 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 14:56:52.528  3824  3873 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 14:56:52.528  3824  3873 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-30 14:56:52.531  3824  3873 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-30 14:56:52.531  3824  3873 D io.jxcore.node.ConnectivityMonitor: start: OK,
,08-30 14:56:52.532  3824  3873 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-30 14:56:52.532  3824  3873 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1511389 added. We now have 3 listener(s)
,08-30 14:56:52.533  3824  3824 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 14:56:52.535  3824  3824 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 14:56:52.538  3824  3873 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-30 14:56:52.538  3824  3873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-30 14:56:52.538  3824  3873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-30 14:56:52.539  3824  3873 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded,
08-30 14:56:52.539  3824  3873 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@86f3f8e added. We now have 10 listener(s)
,08-30 14:56:52.539  3824  3873 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-30 14:56:52.540  3824  3873 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-30 14:56:52.540  3824  3873 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,08-30 14:56:52.540  3824  3873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-30 14:56:52.541  3824  3873 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-30 14:56:52.541  3824  3873 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-30 14:56:52.547  3824  3873 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,08-30 14:56:52.547  3824  3873 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-30 14:56:52.553  3824  3873 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-30 14:56:52.554  3824  3873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,08-30 14:56:52.554  3824  3873 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-30 14:56:52.556  3824  3873 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-30 14:56:52.556  3824  3873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,08-30 14:56:52.557  3824  3873 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-30 14:56:52.557  3824  3873 D BluetoothAdapter: STATE_ON
,08-30 14:56:52.560  4200  4236 D BtGatt.GattService: registerClient() - UUID=7de4c72d-93ac-47ed-9ce8-75ec4bfcc3f4
,08-30 14:56:52.561  4200  4216 D BtGatt.GattService: onClientRegistered() - UUID=7de4c72d-93ac-47ed-9ce8-75ec4bfcc3f4, clientIf=5
,08-30 14:56:52.562  3824  3836 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,08-30 14:56:52.563  4200  4210 D BtGatt.GattService: start scan with filters
,08-30 14:56:52.567  4200  4219 D BtGatt.ScanManager: handling starting scan
,08-30 14:56:52.568  3824  3873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-30 14:56:52.568  3824  3873 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,08-30 14:56:52.568  3824  3873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-30 14:56:52.568  3824  3873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
08-30 14:56:52.569  4200  4219 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@cadc134
08-30 14:56:52.572  3824  3873 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-30 14:56:52.573  3824  3824 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-30 14:56:52.573  3824  3873 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-30 14:56:52.573  4200  4216 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,08-30 14:56:52.574  4200  4216 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-30 14:56:52.574  4200  4219 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
08-30 14:56:52.575  3824  3873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-30 14:56:52.578  3824  3873 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,08-30 14:56:52.578  3824  3873 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-30 14:56:52.578  3824  3873 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-30 14:56:52.578  3824  3873 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 14:56:52.578  3824  3873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-30 14:56:52.578  3824  3873 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-30 14:56:52.578  3824  3873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-30 14:56:52.578  3824  3873 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-30 14:56:52.578  3824  3873 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-30 14:56:52.579  3824  3873 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-30 14:56:52.579  3824  3873 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-30 14:56:52.579  3824  3873 D BluetoothAdapter: STATE_ON
,08-30 14:56:52.580  4200  4228 D BtGatt.GattService: stopScan() - queue size =1
08-30 14:56:52.581  4200  4211 D BtGatt.GattService: unregisterClient() - clientIf=5
08-30 14:56:52.582  3824  3873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-30 14:56:52.582  3824  3873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,08-30 14:56:52.582  3824  3873 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,08-30 14:56:52.582  3824  3873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,08-30 14:56:52.583  4200  4216 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,08-30 14:56:52.583  3824  3873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-30 14:56:52.583  4200  4216 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-30 14:56:52.583  4200  4219 D BtGatt.ScanManager: Starting BLE batch scan
,08-30 14:56:52.583  4200  4219 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-30 14:56:52.585  3824  3873 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-30 14:56:52.585  3824  3873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,08-30 14:56:52.585  3824  3873 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-30 14:56:52.585  3824  3873 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...,
08-30 14:56:52.586  3824  3873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-30 14:56:52.587  3824  3824 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-30 14:56:52.587  3824  3824 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-30 14:56:52.587  3824  3824 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-30 14:56:52.593  3824  3873 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-30 14:56:52.593  3824  3873 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 14:56:52.594  3824  3873 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-30 14:56:52.594  3824  3873 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-30 14:56:52.594  3824  3873 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-30 14:56:52.594  3824  3873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-30 14:56:52.594  3824  3873 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-30 14:56:52.595  3824  3873 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5995142 removed from the list
08-30 14:56:52.595  3824  3873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-30 14:56:52.596  3824  3873 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@415e553 removed from the list
,08-30 14:56:52.596  3824  3873 D io.jxcore.node.ConnectivityMonitor: stop
08-30 14:56:52.596  3824  3873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 14:56:52.597  3824  3873 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 14:56:52.598  3824  3873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-30 14:56:52.598  4200  4216 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-30 14:56:52.598  4200  4216 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-30 14:56:52.600  3824  3873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 14:56:52.600  3824  3873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 14:56:52.600  3824  3873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 14:56:52.601  3824  3873 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@415e553 not in the list
,08-30 14:56:52.601  3824  3873 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 14:56:52.601  3824  3873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 14:56:52.602  3824  3873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 14:56:52.602  3824  3873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 14:56:52.602  3824  3873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-30 14:56:52.603  3824  3873 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@86f3f8e removed from the list
08-30 14:56:52.603  3824  3873 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 14:56:52.603  3824  3873 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 14:56:52.603  3824  3873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 14:56:52.603  3824  3873 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-30 14:56:52.603  3824  3873 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1511389 removed from the list
08-30 14:56:52.604  3824  3873 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-30 14:56:52.604  3824  3873 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7a3c69a added. We now have 2 listener(s)
08-30 14:56:52.606  4200  4216 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-30 14:56:52.606  4200  4216 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-30 14:56:52.608  3824  3873 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-30 14:56:52.608  3824  3873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-30 14:56:52.608  3824  3873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-30 14:56:52.608  3824  3873 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 14:56:52.608  3824  3873 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c5aabcb added. We now have 9 listener(s)
,08-30 14:56:52.608  3824  3873 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 14:56:52.609  3824  3873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-30 14:56:52.612  3824  3873 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 14:56:52.613  4200  4216 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-30 14:56:52.613  4200  4216 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-30 14:56:52.614  4200  4219 D BtGatt.ScanManager: stopping BLe Batch
,08-30 14:56:52.620  3824  3873 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 14:56:52.620  3824  3873 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 14:56:52.620  3824  3873 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 14:56:52.620  3824  3873 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 14:56:52.620  3824  3873 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 14:56:52.620  3824  3873 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 14:56:52.620  3824  3873 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 14:56:52.620  3824  3873 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-30 14:56:52.620  4200  4216 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-30 14:56:52.621  4200  4216 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-30 14:56:52.621  4200  4219 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-30 14:56:52.624  3824  3873 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-30 14:56:52.624  3824  3873 D io.jxcore.node.ConnectivityMonitor: start: OK
08-30 14:56:52.624  3824  3873 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-30 14:56:52.624  3824  3873 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@cdaaac1 added. We now have 3 listener(s)
08-30 14:56:52.626  3824  3873 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-30 14:56:52.626  3824  3873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-30 14:56:52.626  3824  3873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-30 14:56:52.626  3824  3873 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 14:56:52.626  3824  3873 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b67b266 added. We now have 10 listener(s)
,08-30 14:56:52.626  3824  3873 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 14:56:52.626  3824  3873 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-30 14:56:52.627  3824  3873 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-30 14:56:52.627  3824  3873 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,08-30 14:56:52.627  3824  3824 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 14:56:52.627  3824  3873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-30 14:56:52.627  3824  3873 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 14:56:52.627  3824  3873 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-30 14:56:52.629  1494  1494 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
08-30 14:56:52.630  3824  3824 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 14:56:52.631  4200  4216 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-30 14:56:52.631  4200  4216 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-30 14:56:52.633  3824  3873 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-30 14:56:52.633  3824  3873 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-30 14:56:52.637  3824  3873 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-30 14:56:52.637  3824  3873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-30 14:56:52.637  3824  3873 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-30 14:56:52.643  3824  3873 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-30 14:56:52.643  3824  3873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-30 14:56:52.643  3824  3873 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-30 14:56:52.644  3824  3873 D BluetoothAdapter: STATE_ON
,08-30 14:56:52.647  4200  4236 D BtGatt.GattService: registerClient() - UUID=4279aadd-1c16-47e2-8795-5f6b149a30a3
,08-30 14:56:52.648  4200  4216 D BtGatt.GattService: onClientRegistered() - UUID=4279aadd-1c16-47e2-8795-5f6b149a30a3, clientIf=5
08-30 14:56:52.648  3824  3863 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,08-30 14:56:52.648  4200  4210 D BtGatt.GattService: start scan with filters
,08-30 14:56:52.653  3824  3873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-30 14:56:52.653  3824  3873 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-30 14:56:52.653  4200  4219 D BtGatt.ScanManager: handling starting scan
08-30 14:56:52.653  3824  3873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-30 14:56:52.653  3824  3873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-30 14:56:52.656  3824  3873 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-30 14:56:52.656  3824  3873 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-30 14:56:52.656  3824  3824 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-30 14:56:52.657  3824  3873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-30 14:56:52.659  3824  3873 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
08-30 14:56:52.660  3824  3873 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
08-30 14:56:52.660  3824  3873 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 14:56:52.660  3824  3873 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 14:56:52.660  3824  3873 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-30 14:56:52.660  3824  3873 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 14:56:52.660  3824  3873 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 14:56:52.660  3824  3873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-30 14:56:52.660  3824  3873 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-30 14:56:52.661  3824  3873 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7a3c69a removed from the list
08-30 14:56:52.661  3824  3873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 14:56:52.661  3824  3873 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c5aabcb removed from the list
,08-30 14:56:52.661  3824  3873 D io.jxcore.node.ConnectivityMonitor: stop
08-30 14:56:52.661  3824  3873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 14:56:52.662  3824  3873 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
08-30 14:56:52.662  3824  3873 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
08-30 14:56:52.662  3824  3873 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-30 14:56:52.662  3824  3873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 14:56:52.663  3824  3873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 14:56:52.663  3824  3873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-30 14:56:52.663  3824  3873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 14:56:52.663  3824  3873 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c5aabcb not in the list
08-30 14:56:52.664  3824  3873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,08-30 14:56:52.664  3824  3873 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-30 14:56:52.664  3824  3873 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-30 14:56:52.664  3824  3873 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-30 14:56:52.664  3824  3873 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-30 14:56:52.665  4200  4216 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-30 14:56:52.665  4200  4216 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-30 14:56:52.665  1494  3015 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,08-30 14:56:52.666  1494  3015 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
08-30 14:56:52.666  3824  3873 D BluetoothAdapter: STATE_ON
08-30 14:56:52.666  1494  3015 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-30 14:56:52.666  1494  3015 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-30 14:56:52.666  4200  4219 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-30 14:56:52.666  4200  4228 D BtGatt.GattService: stopScan() - queue size =1
,08-30 14:56:52.668  4200  4211 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-30 14:56:52.669  3824  3873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-30 14:56:52.669  3824  3873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-30 14:56:52.669  3824  3873 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,08-30 14:56:52.670  3824  3873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,08-30 14:56:52.670  3824  3873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-30 14:56:52.673  4200  4216 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-30 14:56:52.673  4200  4216 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-30 14:56:52.673  4200  4219 D BtGatt.ScanManager: Starting BLE batch scan
08-30 14:56:52.674  4200  4219 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-30 14:56:52.675  3824  3873 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-30 14:56:52.675  3824  3873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,08-30 14:56:52.675  3824  3873 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-30 14:56:52.676  3824  3873 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-30 14:56:52.677  3824  3873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-30 14:56:52.679  3824  3873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-30 14:56:52.679  3824  3824 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-30 14:56:52.679  3824  3824 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-30 14:56:52.679  3824  3824 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-30 14:56:52.681  3824  3873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-30 14:56:52.682  3824  3873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-30 14:56:52.682  3824  3873 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b67b266 removed from the list
,08-30 14:56:52.683  3824  3873 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 14:56:52.683  3824  3873 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 14:56:52.683  3824  3873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-30 14:56:52.683  3824  3873 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-30 14:56:52.684  3824  3873 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@cdaaac1 removed from the list
,08-30 14:56:52.684  3569  3569 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
08-30 14:56:52.684  3569  3569 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
08-30 14:56:52.685  3569  3569 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 4.
08-30 14:56:52.685  3824  3873 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-30 14:56:52.685  3824  3873 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c2c8ef2 added. We now have 2 listener(s)
08-30 14:56:52.686  4200  4216 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-30 14:56:52.686  4200  4216 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-30 14:56:52.687  3824  3873 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-30 14:56:52.687  3824  3873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-30 14:56:52.687  3824  3873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-30 14:56:52.688  3824  3873 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 14:56:52.688  3824  3873 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3b2c943 added. We now have 9 listener(s)
,08-30 14:56:52.688  3824  3873 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-30 14:56:52.689  3824  3873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-30 14:56:52.691  3824  3873 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 14:56:52.693  4200  4216 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,08-30 14:56:52.693  4200  4216 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-30 14:56:52.697  3824  3873 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 14:56:52.697  3824  3873 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 14:56:52.697  3824  3873 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 14:56:52.697  3824  3873 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 14:56:52.697  3824  3873 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 14:56:52.697  3824  3873 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 14:56:52.697  3824  3873 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 14:56:52.697  3824  3873 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-30 14:56:52.699  3824  3873 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-30 14:56:52.699  3824  3873 D io.jxcore.node.ConnectivityMonitor: start: OK
08-30 14:56:52.699  3824  3873 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-30 14:56:52.700  3824  3873 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7a8f0f9 added. We now have 3 listener(s)
,08-30 14:56:52.701  3824  3873 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-30 14:56:52.702  3824  3873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-30 14:56:52.702  3824  3873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-30 14:56:52.702  3824  3873 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 14:56:52.702  3824  3873 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5f0a83e added. We now have 10 listener(s)
08-30 14:56:52.702  3824  3873 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-30 14:56:52.702  3824  3873 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-30 14:56:52.702  3824  3873 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-30 14:56:52.702  3824  3873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-30 14:56:52.702  3824  3873 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 14:56:52.702  3824  3873 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-30 14:56:52.703  4200  4216 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-30 14:56:52.703  4200  4216 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-30 14:56:52.704  3824  3824 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 14:56:52.704  4200  4219 D BtGatt.ScanManager: stopping BLe Batch
,08-30 14:56:52.705  3824  3873 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,08-30 14:56:52.705  3824  3873 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-30 14:56:52.706  3824  3824 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 14:56:52.708  3824  3873 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-30 14:56:52.709  3824  3873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-30 14:56:52.709  3824  3873 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-30 14:56:52.709  4200  4216 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-30 14:56:52.709  4200  4216 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-30 14:56:52.709  4200  4219 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-30 14:56:52.712  3824  3873 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-30 14:56:52.712  3824  3873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-30 14:56:52.712  3824  3873 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-30 14:56:52.712  3824  3873 D BluetoothAdapter: STATE_ON
,08-30 14:56:52.714  4200  4228 D BtGatt.GattService: registerClient() - UUID=3e787378-9e3e-4cef-a18e-1f11e4c3ead9
,08-30 14:56:52.715  4200  4216 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-30 14:56:52.715  4200  4216 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-30 14:56:52.715  4200  4216 D BtGatt.GattService: onClientRegistered() - UUID=3e787378-9e3e-4cef-a18e-1f11e4c3ead9, clientIf=5
08-30 14:56:52.716  3824  3836 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-30 14:56:52.716  4200  4211 D BtGatt.GattService: start scan with filters
,08-30 14:56:52.718  3824  3873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-30 14:56:52.718  3824  3873 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-30 14:56:52.718  4200  4219 D BtGatt.ScanManager: handling starting scan
08-30 14:56:52.718  3824  3873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-30 14:56:52.718  3824  3873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-30 14:56:52.720  3824  3873 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-30 14:56:52.720  3824  3824 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-30 14:56:52.720  3824  3873 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-30 14:56:52.722  3824  3873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-30 14:56:52.724  4200  4216 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,08-30 14:56:52.724  4200  4216 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-30 14:56:52.724  4200  4219 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-30 14:56:52.726  3824  3873 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-30 14:56:52.726  3824  3873 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 14:56:52.726  3824  3873 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 14:56:52.726  3824  3873 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 14:56:52.726  3824  3873 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-30 14:56:52.726  3824  3873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-30 14:56:52.726  3824  3873 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-30 14:56:52.726  3824  3873 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c2c8ef2 removed from the list
08-30 14:56:52.727  3824  3873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 14:56:52.727  3824  3873 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3b2c943 removed from the list
,08-30 14:56:52.727  3824  3873 D io.jxcore.node.ConnectivityMonitor: stop
08-30 14:56:52.727  3824  3873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 14:56:52.727  3824  3873 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
08-30 14:56:52.727  3824  3873 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
08-30 14:56:52.727  3824  3873 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 14:56:52.727  3824  3873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-30 14:56:52.728  3824  3873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-30 14:56:52.728  3824  3873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 14:56:52.728  3824  3873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 14:56:52.728  3824  3873 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3b2c943 not in the list
08-30 14:56:52.729  3824  3873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-30 14:56:52.729  3824  3873 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-30 14:56:52.729  3824  3873 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-30 14:56:52.729  3824  3873 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-30 14:56:52.729  3824  3873 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-30 14:56:52.730  3824  3873 D BluetoothAdapter: STATE_ON
08-30 14:56:52.730  4200  4211 D BtGatt.GattService: stopScan() - queue size =1
,08-30 14:56:52.730  4200  4216 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,08-30 14:56:52.730  4200  4216 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-30 14:56:52.730  4200  4236 D BtGatt.GattService: unregisterClient() - clientIf=5
08-30 14:56:52.730  4200  4219 D BtGatt.ScanManager: Starting BLE batch scan
08-30 14:56:52.731  4200  4219 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-30 14:56:52.731  3824  3873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-30 14:56:52.731  3824  3873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-30 14:56:52.731  3824  3873 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-30 14:56:52.731  3824  3873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-30 14:56:52.731  3824  3873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED],
08-30 14:56:52.732  3824  3873 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-30 14:56:52.732  3824  3873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,08-30 14:56:52.733  3824  3873 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-30 14:56:52.733  3824  3873 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-30 14:56:52.733  3824  3873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-30 14:56:52.734  3824  3824 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-30 14:56:52.734  3824  3824 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-30 14:56:52.734  3824  3824 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-30 14:56:52.735  3824  3873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-30 14:56:52.735  3824  3873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 14:56:52.735  3824  3873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 14:56:52.735  3824  3873 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5f0a83e removed from the list
08-30 14:56:52.735  3824  3873 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-30 14:56:52.735  3824  3873 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 14:56:52.735  3824  3873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 14:56:52.735  3824  3873 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-30 14:56:52.735  3824  3873 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7a8f0f9 removed from the list
08-30 14:56:52.736  3824  3873 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-30 14:56:52.736  3824  3873 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@44b0a4a added. We now have 2 listener(s)
,08-30 14:56:52.738  3824  3873 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-30 14:56:52.738  3824  3873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-30 14:56:52.738  3824  3873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-30 14:56:52.738  3824  3873 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 14:56:52.739  3824  3873 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@521dbb added. We now have 9 listener(s)
,08-30 14:56:52.739  3824  3873 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 14:56:52.739  3824  3873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-30 14:56:52.740  4200  4216 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,08-30 14:56:52.740  4200  4216 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-30 14:56:52.741  3824  3873 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-30 14:56:52.745  4200  4216 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,08-30 14:56:52.745  4200  4216 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-30 14:56:52.746  3824  3873 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 14:56:52.746  3824  3873 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 14:56:52.746  3824  3873 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 14:56:52.746  3824  3873 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 14:56:52.746  3824  3873 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 14:56:52.746  3824  3873 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 14:56:52.746  3824  3873 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 14:56:52.746  3824  3873 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-30 14:56:52.748  3824  3873 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-30 14:56:52.748  3824  3873 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-30 14:56:52.748  3824  3873 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-30 14:56:52.749  3824  3873 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1c2c631 added. We now have 3 listener(s)
,08-30 14:56:52.750  3824  3824 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 14:56:52.751  4200  4216 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-30 14:56:52.751  4200  4216 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-30 14:56:52.751  4200  4219 D BtGatt.ScanManager: stopping BLe Batch
08-30 14:56:52.752  3824  3873 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-30 14:56:52.752  3824  3873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-30 14:56:52.752  3824  3873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-30 14:56:52.752  3824  3873 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 14:56:52.752  3824  3873 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3378116 added. We now have 10 listener(s)
08-30 14:56:52.752  3824  3873 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 14:56:52.752  3824  3824 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 14:56:52.753  3824  3873 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 14:56:52.753  3824  3873 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 14:56:52.753  3824  3873 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 14:56:52.753  3824  3873 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-30 14:56:52.753  3824  3873 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 14:56:52.753  3824  3873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 14:56:52.753  3824  3873 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-30 14:56:52.753  3824  3873 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@44b0a4a removed from the list
,08-30 14:56:52.753  3824  3873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 14:56:52.753  3824  3873 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@521dbb removed from the list
,08-30 14:56:52.754  3824  3873 D io.jxcore.node.ConnectivityMonitor: stop
08-30 14:56:52.754  3824  3873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 14:56:52.754  3824  3873 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 14:56:52.754  3824  3873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-30 14:56:52.755  3824  3873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising,
08-30 14:56:52.755  3824  3873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 14:56:52.755  3824  3873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 14:56:52.756  3824  3873 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@521dbb not in the list
08-30 14:56:52.756  3824  3873 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-30 14:56:52.756  3824  3873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 14:56:52.757  4200  4216 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-30 14:56:52.757  4200  4216 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-30 14:56:52.757  4200  4219 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
08-30 14:56:52.757  3824  3873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 14:56:52.757  3824  3873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 14:56:52.757  3824  3873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 14:56:52.757  3824  3873 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3378116 removed from the list
,08-30 14:56:52.757  3824  3873 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 14:56:52.757  3824  3873 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 14:56:52.757  3824  3873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 14:56:52.757  3824  3873 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-30 14:56:52.758  3824  3873 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1c2c631 removed from the list
08-30 14:56:52.758  3824  3873 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
08-30 14:56:52.758  3824  3873 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
08-30 14:56:52.759  3824  3873 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything,
08-30 14:56:52.759  3824  3873 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-30 14:56:52.759  3824  3873 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
08-30 14:56:52.759  3824  3873 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything,
,08-30 14:56:52.762  4200  4216 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-30 14:56:52.762  4200  4216 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-30 14:56:52.765  3824  4278 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 439, name: My test thread name)
,08-30 14:56:52.765  3824  4278 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 439, thread name: My test thread name)
08-30 14:56:52.765  3824  4278 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 439, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,08-30 14:56:52.767  3824  4279 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 441, name: My test thread name)
,08-30 14:56:52.767  3824  4279 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 441, thread name: My test thread name)
08-30 14:56:52.767  3824  4279 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 441, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,08-30 14:56:52.768  3824  3873 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 80
,08-30 14:56:52.768  3824  3873 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 80
08-30 14:56:52.768  3824  3873 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
08-30 14:56:52.768  3824  3873 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
08-30 14:56:52.768  3824  3873 D com.test.thalitest.ThaliTestRunner: Total duration: 22836 ms
,08-30 14:56:52.770  3824  3873 I jxcore-log: *Native tests were executed*
08-30 14:56:52.770  3824  3873 I jxcore-log: 
,08-30 14:56:52.770  3824  3873 I jxcore-log: Total number of executed tests:  80
08-30 14:56:52.770  3824  3873 I jxcore-log: 
08-30 14:56:52.770  3824  3873 I jxcore-log: Number of passed tests:  80
08-30 14:56:52.770  3824  3873 I jxcore-log: 
08-30 14:56:52.770  3824  3873 I jxcore-log: Number of failed tests:  0
08-30 14:56:52.770  3824  3873 I jxcore-log: 
,08-30 14:56:52.771  3824  3873 I jxcore-log: Number of ignored tests:  0
08-30 14:56:52.771  3824  3873 I jxcore-log: 
08-30 14:56:52.771  3824  3873 I jxcore-log: Total duration:  22836
08-30 14:56:52.771  3824  3873 I jxcore-log: 
08-30 14:56:52.771  3824  3873 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
08-30 14:56:52.771  3824  3873 I jxcore-log: 
,08-30 14:56:52.774  3824  3873 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 14:56:52.774  3824  3873 I jxcore-log: 
08-30 14:56:52.777  3824  3873 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 14:56:52.777  3824  3873 I jxcore-log: 
08-30 14:56:52.778  3824  3873 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 14:56:52.778  3824  3873 I jxcore-log: 
08-30 14:56:52.778  3824  3873 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 14:56:52.778  3824  3873 I jxcore-log: 
08-30 14:56:52.779  3824  3873 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 14:56:52.779  3824  3873 I jxcore-log: 
08-30 14:56:52.781  3824  3873 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 14:56:52.781  3824  3873 I jxcore-log: 
08-30 14:56:52.781  3824  3824 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
08-30 14:56:52.783  3824  3873 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 14:56:52.783  3824  3873 I jxcore-log: 
08-30 14:56:52.785  3824  3873 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-30 14:56:52.785  3824  3873 I jxcore-log: 
08-30 14:56:52.785  3824  3873 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-30 14:56:52.785  3824  3873 I jxcore-log: 
08-30 14:56:52.786  3824  3873 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-30 14:56:52.786  3824  3873 I jxcore-log: 
08-30 14:56:52.787  3824  3873 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-30 14:56:52.787  3824  3873 I jxcore-log: 
,08-30 14:56:52.788  3824  3873 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-30 14:56:52.788  3824  3873 I jxcore-log: 
,08-30 14:56:52.788  3824  3873 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-30 14:56:52.788  3824  3873 I jxcore-log: 
,08-30 14:56:52.789  3824  3873 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-30 14:56:52.789  3824  3873 I jxcore-log: 
,08-30 14:56:52.790  3824  3873 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 14:56:52.790  3824  3873 I jxcore-log: 
,08-30 14:56:52.790  3824  3873 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 14:56:52.790  3824  3873 I jxcore-log: 
08-30 14:56:52.791  3824  3873 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-30 14:56:52.791  3824  3873 I jxcore-log: 
,08-30 14:56:52.792  3824  3873 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-30 14:56:52.792  3824  3873 I jxcore-log: 
,08-30 14:56:52.792  3824  3873 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-30 14:56:52.792  3824  3873 I jxcore-log: 
08-30 14:56:52.793  3824  3873 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-30 14:56:52.793  3824  3873 I jxcore-log: 
,08-30 14:56:52.793  3824  3873 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-30 14:56:52.793  3824  3873 I jxcore-log: 
08-30 14:56:52.794  3824  3873 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-30 14:56:52.794  3824  3873 I jxcore-log: 
,08-30 14:56:52.795  3824  3873 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-30 14:56:52.795  3824  3873 I jxcore-log: 
,08-30 14:56:52.795  3824  3873 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-30 14:56:52.795  3824  3873 I jxcore-log: 
,08-30 14:56:52.796  3824  3873 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-30 14:56:52.796  3824  3873 I jxcore-log: 
08-30 14:56:52.796  3824  3873 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 14:56:52.796  3824  3873 I jxcore-log: 
,08-30 14:56:52.797  3824  3873 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 14:56:52.797  3824  3873 I jxcore-log: 
,08-30 14:56:52.798  3824  3873 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 14:56:52.798  3824  3873 I jxcore-log: 
,08-30 14:56:52.798  3824  3873 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 14:56:52.798  3824  3873 I jxcore-log: 
,08-30 14:56:52.799  3824  3873 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 14:56:52.799  3824  3873 I jxcore-log: 
08-30 14:56:52.799  3824  3873 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 14:56:52.799  3824  3873 I jxcore-log: 
,08-30 14:56:52.800  3824  3873 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 14:56:52.800  3824  3873 I jxcore-log: 
,08-30 14:56:53.088  3824  3824 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-30 14:56:53.094  3824  3873 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-30 14:56:53.094  3824  3873 I jxcore-log: 
,08-30 14:56:53.179  3824  3824 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false,
08-30 14:56:53.181  3824  3873 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-30 14:56:53.181  3824  3873 I jxcore-log: 
,08-30 14:56:53.235  3824  3824 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-30 14:56:53.236  3824  3873 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-30 14:56:53.236  3824  3873 I jxcore-log: 
,08-30 14:56:53.555  4280  4280 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,08-30 14:56:53.559  4280  4280 D AndroidRuntime: CheckJNI is OFF
,08-30 14:56:53.601  4280  4280 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,08-30 14:56:53.648  4280  4280 I Radio-JNI: register_android_hardware_Radio DONE
,08-30 14:56:53.670  4280  4280 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,08-30 14:56:53.682   872   885 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=-1: uninstall pkg
,08-30 14:56:53.682   872   885 I ActivityManager: Killing 3824:com.test.thalitest/u0a0 (adj 0): stop com.test.thalitest
,08-30 14:56:53.799   872   895 W PackageSettings: Skipping PackageSetting{92eed31 com.example.hello/10273} due to missing metadata
,08-30 14:56:53.821   872  1675 D GraphicsStats: Buffer count: 2
,08-30 14:56:53.821   872  1675 I WindowState: WIN DEATH: Window{73cfec9 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-30 14:56:53.825   872  1305 D WifiService: Client connection lost with reason: 4
,08-30 14:56:53.852   872   885 W ActivityManager: Force removing ActivityRecord{e91096 u0 com.test.thalitest/.MainActivity t2}: app died, no saved state
,08-30 14:56:53.858   872   895 I art     : Starting a blocking GC Explicit
,08-30 14:56:53.875   872  1982 W ActivityManager: Spurious death for ProcessRecord{f14985e 0:com.test.thalitest/u0a0}, curProc for 3824: null
,08-30 14:56:53.911   872  1984 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 3824 uid 10000
,08-30 14:56:53.913  1889  1889 I Keyboard.Facilitator: onFinishInput()
,08-30 14:56:53.927   872   895 I art     : Explicit concurrent mark sweep GC freed 44957(2MB) AllocSpace objects, 3(60KB) LOS objects, 33% free, 29MB/43MB, paused 2.164ms total 68.587ms
,08-30 14:56:53.957   872   895 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,08-30 14:56:53.963  4280  4280 I art     : System.exit called, status: 0
,08-30 14:56:53.963  4280  4280 I AndroidRuntime: VM exiting with result code 0.
,08-30 14:56:53.979  2065  4295 I MicroRecognitionRnrImpl: Starting detection.
,08-30 14:56:53.980  2065  4296 I MicrophoneInputStream: mic_starting com.google.android.apps.gsa.speech.audio.x@de1bf01
,08-30 14:56:53.981   374  4298 I AudioFlinger: AudioFlinger's thread 0xb1c80000 ready to run
,08-30 14:56:53.984   872   895 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=0: pkg removed
08-30 14:56:53.984   374  1274 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
,08-30 14:56:53.986  2065  4296 I MicrophoneInputStream: mic_started com.google.android.apps.gsa.speech.audio.x@de1bf01
,08-30 14:56:53.995   374  4298 D audio_hw_primary: select_devices: out_snd_device(0: none) in_snd_device(61: voice-rec-mic)
08-30 14:56:53.995   374  4298 D msm8974_platform: platform_send_audio_calibration: sending audio calibration for snd_device(61) acdb_id(62)
08-30 14:56:53.995   374  4298 D audio_hw_primary: enable_snd_device: snd_device(61: voice-rec-mic)
,08-30 14:56:54.002   374  4298 D audio_hw_primary: enable_audio_route: apply and update mixer path: audio-record
,08-30 14:56:54.013  4200  4200 D BluetoothMapAppObserver: onReceive
,08-30 14:56:54.013  4200  4200 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
,08-30 14:56:54.014  1855  2198 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,08-30 14:56:54.019   872  1294 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-30 14:56:54.027  1889  1889 I Keyboard.Facilitator: resetDictionaries() : en_US
,08-30 14:56:54.029  1889  4302 I Keyboard.Facilitator.DecoderInitializer: run()
,08-30 14:56:54.046  1975  1975 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,08-30 14:56:54.060  3667  3667 D BuaReceiver: ====== got intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.motorola.android.buacontactadapter/.BuaReceiver (has extras) }
,08-30 14:56:54.064  1889  4302 I Decoder : createOrResetDecoder
,08-30 14:56:54.065   872  1306 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,08-30 14:56:54.081  2065  2065 I HotwordWorkerImpl: onReady
,08-30 14:56:54.099   872   885 I ActivityManager: Start proc 4304:android.process.acore/u0a5 for broadcast com.android.providers.contacts/.PackageIntentReceiver
,08-30 14:56:54.116  1494  1494 I ConfigService: onCreate
,08-30 14:56:54.118   872   872 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
08-30 14:56:54.119  1494  4317 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/config.db'.
08-30 14:56:54.119  1494  4317 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 14:56:54.119  1494  4317 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-30 14:56:54.119  1494  4317 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-30 14:56:54.119  1494  4317 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-30 14:56:54.119  1494  4317 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-30 14:56:54.119  1494  4317 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-30 14:56:54.119  1494  4317 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-30 14:56:54.119  1494  4317 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-30 14:56:54.119  1494  4317 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-30 14:56:54.119  1494  4317 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-30 14:56:54.119  1494  4317 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-30 14:56:54.119  1494  4317 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-30 14:56:54.119  1494  4317 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-30 14:56:54.119  1494  4317 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-30 14:56:54.119  1494  4317 E SQLiteDatabase: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
08-30 14:56:54.119  1494  4317 E SQLiteDatabase: 	at com.google.android.gms.config.j.run(SourceFile:152)
08-30 14:56:54.119  1494  4317 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
08-30 14:56:54.119  1494  4317 E SQLiteOpenHelper: Couldn't open config.db for writing (will try read-only):
08-30 14:56:54.119  1494  4317 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 14:56:54.119  1494  4317 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-30 14:56:54.119  1494  4317 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-30 14:56:54.119  1494  4317 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-30 14:56:54.119  1494  4317 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-30 14:56:54.119  1494  4317 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-30 14:56:54.119  1494  4317 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-30 14:56:54.119  1494  4317 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-30 14:56:54.119  1494  4317 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-30 14:56:54.119  1494  4317 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-30 14:56:54.119  1494  4317 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-30 14:56:54.119  1494  4317 E SQLiteOpenHelper: 	at android.content.ContextW,rapper.openOrCreateDatabase(ContextWrapper.java:269)
08-30 14:56:54.119  1494  4317 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-30 14:56:54.119  1494  4317 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-30 14:56:54.119  1494  4317 E SQLiteOpenHelper: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
08-30 14:56:54.119  1494  4317 E SQLiteOpenHelper: 	at com.google.android.gms.config.j.run(SourceFile:152)
08-30 14:56:54.119  1494  4317 E SQLiteOpenHelper: 	at java.lang.Thread.run(Thread.java:818)
08-30 14:56:54.120  1494  4317 W SQLiteOpenHelper: Opened config.db in read-only mode
,08-30 14:56:54.132  1889  4302 I Keyboard.Facilitator.MainLanguageModelLoader: run()
,08-30 14:56:54.148  4304  4304 W System  : ClassLoader referenced unknown path: /system/priv-app/ContactsProvider/lib/arm
,08-30 14:56:54.154  1996  2082 E SQLiteLog: (3850) statement aborts at 23: [DELETE FROM icons WHERE componentName LIKE ? AND profileId = ?] disk I/O error
,08-30 14:56:54.155   872   884 W AtomicFile: Couldn't rename file /data/system/users/0/runtime-permissions.xml to backup file /data/system/users/0/runtime-permissions.xml.bak
,08-30 14:56:54.155   872   884 E PackageManager: Failed to write settings, restoring backup
08-30 14:56:54.155   872   884 E PackageManager: java.io.IOException: Couldn't create directory /data/system/users/0/runtime-permissions.xml
08-30 14:56:54.155   872   884 E PackageManager: 	at android.util.AtomicFile.startWrite(AtomicFile.java:106)
08-30 14:56:54.155   872   884 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.writePermissionsSync(Settings.java:4615)
08-30 14:56:54.155   872   884 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.-wrap1(Settings.java)
08-30 14:56:54.155   872   884 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence$MyHandler.handleMessage(Settings.java:4830)
08-30 14:56:54.155   872   884 E PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 14:56:54.155   872   884 E PackageManager: 	at android.os.Looper.loop(Looper.java:148)
08-30 14:56:54.155   872   884 E PackageManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-30 14:56:54.159   872   885 E DropBoxManagerService: Can't write: system_server_wtf
08-30 14:56:54.159   872   885 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop15.tmp: open failed: EROFS (Read-only file system)
08-30 14:56:54.159   872   885 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-30 14:56:54.159   872   885 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-30 14:56:54.159   872   885 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-30 14:56:54.159   872   885 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-30 14:56:54.159   872   885 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-30 14:56:54.159   872   885 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-30 14:56:54.159   872   885 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12543)
08-30 14:56:54.159   872   885 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.handleApplicationWtfInner(ActivityManagerService.java:12356)
08-30 14:56:54.159   872   885 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:12328)
08-30 14:56:54.159   872   885 E DropBoxManagerService: 	at android.os.Handler.handleCallback(Handler.java:739)
08-30 14:56:54.159   872   885 E DropBoxManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-30 14:56:54.159   872   885 E DropBoxManagerService: 	at android.os.Looper.loop(Looper.java:148)
08-30 14:56:54.159   872   885 E DropBoxManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-30 14:56:54.159   872   885 E DropBoxManagerService: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
08-30 14:56:54.159   872   885 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-30 14:56:54.159   872   885 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-30 14:56:54.159   872   885 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-30 14:56:54.159   872   885 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-30 14:56:54.159   872   885 E DropBoxManagerService: 	... 13 more
,08-30 14:56:54.162  1889  4302 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /data/user/0/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
,08-30 14:56:54.163  1889  4302 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
,08-30 14:56:54.163  1889  4302 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
,08-30 14:56:54.165  1889  4302 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Contacts.dict
,08-30 14:56:54.166  1889  4302 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = history
08-30 14:56:54.166  1889  4302 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loaded File = UserHistory.en_US.dict
08-30 14:56:54.166  1889  4302 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = user
08-30 14:56:54.167  1889  4302 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Personal.en_US.dict
08-30 14:56:54.167  1889  4302 I Keyboard.Facilitator.PersonalDictionaryLoader: run() : Loaded (exit)
08-30 14:56:54.167   872  2026 I ActivityManager: Start proc 4319:com.google.android.googlequicksearchbox:crash_report/u0a28 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
08-30 14:56:54.167  1889  4302 I Keyboard.Facilitator.Delight2FileSweeper: run()
--------- beginning of crash
08-30 14:56:54.167  1996  2082 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
08-30 14:56:54.167  1996  2082 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 1996
08-30 14:56:54.167  1996  2082 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-30 14:56:54.167  1996  2082 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-30 14:56:54.167  1996  2082 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-30 14:56:54.167  1996  2082 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-30 14:56:54.167  1996  2082 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-30 14:56:54.167  1996  2082 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
08-30 14:56:54.167  1996  2082 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
08-30 14:56:54.167  1996  2082 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
08-30 14:56:54.167  1996  2082 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
08-30 14:56:54.167  1996  2082 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-30 14:56:54.167  1996  2082 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-30 14:56:54.167  1996  2082 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-30 14:56:54.169   872  1984 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,08-30 14:56:54.170   872  4325 E DropBoxManagerService: Can't write: system_app_crash
08-30 14:56:54.170   872  4325 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop127.tmp: open failed: EROFS (Read-only file system)
08-30 14:56:54.170   872  4325 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-30 14:56:54.170   872  4325 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-30 14:56:54.170   872  4325 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-30 14:56:54.170   872  4325 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-30 14:56:54.170   872  4325 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-30 14:56:54.170   872  4325 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-30 14:56:54.170   872  4325 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-30 14:56:54.170   872  4325 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-30 14:56:54.170   872  4325 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-30 14:56:54.170   872  4325 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-30 14:56:54.170   872  4325 E DropBoxManagerService: 	... 5 more
,08-30 14:56:54.170  1889  4302 I Keyboard.Facilitator.RecurringTaskScheduler: run()
08-30 14:56:54.171  1889  4302 I StatsUtilsManager: startPeriodStatsRecorder() : Success
08-30 14:56:54.171  1889  4302 I PeriodicStatsRecorder: shouldRecordStats() = Too Soon
08-30 14:56:54.172  2065  2079 W SearchService: Abort, client detached.
08-30 14:56:54.175  2065  2065 I HotwordDetector: Closing mic
08-30 14:56:54.175  2065  2354 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@de1bf01
08-30 14:56:54.175  2065  4296 E AudioRecord-JNI: Error -4 during AudioRecord native read
,08-30 14:56:54.184   872  4332 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,08-30 14:56:54.196  2065  4333 E Search.SharedPreferencesProto: Failed to rename to backup file /data/user/0/com.google.android.googlequicksearchbox/app_shared_prefs/SearchSettings.bin.bak
,08-30 14:56:54.209   872  4332 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-30 14:56:54.209   872  4332 I Adreno  : Build Date                       : 10/20/15
08-30 14:56:54.209   872  4332 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-30 14:56:54.209   872  4332 I Adreno  : Local Branch                     : M14
08-30 14:56:54.209   872  4332 I Adreno  : Remote Branch                    : 
08-30 14:56:54.209   872  4332 I Adreno  : Remote Branch                    : 
08-30 14:56:54.209   872  4332 I Adreno  : Reconstruct Branch               : 
,08-30 14:56:54.214   872  4332 I OpenGLRenderer: Initialized EGL, version 1.4
,08-30 14:56:54.220  4304  4304 W System  : ClassLoader referenced unknown path: /system/app/UserDictionaryProvider/lib/arm
,08-30 14:56:54.227   374  4298 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
,08-30 14:56:54.229   374  4298 D audio_hw_primary: disable_snd_device: snd_device(61: voice-rec-mic)
,08-30 14:56:54.232   374  1274 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
08-30 14:56:54.234  2065  2357 I MicroRecognitionRnrImpl: Stopping hotword detection.
,08-30 14:56:54.234  2065  4295 I MicroRecognitionRnrImpl: Detection finished
,08-30 14:56:54.243   872  1302 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 11, 13 -> obsolete
,08-30 14:56:54.252   872  1389 I ActivityManager: Start proc 4341:com.android.musicfx/u0a18 for broadcast com.android.musicfx/.Compatibility$Receiver
,08-30 14:56:54.258  4304  4345 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,08-30 14:56:54.294  4304  4345 E SQLiteDatabase: Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
08-30 14:56:54.294  4304  4345 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 14:56:54.294  4304  4345 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-30 14:56:54.294  4304  4345 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-30 14:56:54.294  4304  4345 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-30 14:56:54.294  4304  4345 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-30 14:56:54.294  4304  4345 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-30 14:56:54.294  4304  4345 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-30 14:56:54.294  4304  4345 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-30 14:56:54.294  4304  4345 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-30 14:56:54.294  4304  4345 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-30 14:56:54.294  4304  4345 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-30 14:56:54.294  4304  4345 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-30 14:56:54.294  4304  4345 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-30 14:56:54.294  4304  4345 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-30 14:56:54.294  4304  4345 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:191)
08-30 14:56:54.294  4304  4345 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
08-30 14:56:54.294  4304  4345 E SQLiteDatabase: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
08-30 14:56:54.294  4304  4345 E SQLiteDatabase: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
08-30 14:56:54.294  4304  4345 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
08-30 14:56:54.294  4304  4345 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
08-30 14:56:54.294  4304  4345 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-30 14:56:54.294  4304  4345 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 14:56:54.294  4304  4345 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-30 14:56:54.294  4304  4345 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-30 14:56:54.299  4341  4341 W System  : ClassLoader referenced unknown path: /system/priv-app/MusicFX/lib/arm
,08-30 14:56:54.295  4304  4345 E AndroidRuntime: FATAL EXCEPTION: IntentService[VoicemailCleanupService]
08-30 14:56:54.295  4304  4345 E AndroidRuntime: Process: android.process.acore, PID: 4304
08-30 14:56:54.295  4304  4345 E AndroidRuntime: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 14:56:54.295  4304  4345 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-30 14:56:54.295  4304  4345 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-30 14:56:54.295  4304  4345 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-30 14:56:54.295  4304  4345 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-30 14:56:54.295  4304  4345 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-30 14:56:54.295  4304  4345 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-30 14:56:54.295  4304  4345 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-30 14:56:54.295  4304  4345 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-30 14:56:54.295  4304  4345 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-30 14:56:54.295  4304  4345 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-30 14:56:54.295  4304  4345 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-30 14:56:54.295  4304  4345 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-30 14:56:54.295  4304  4345 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-30 14:56:54.295  4304  4345 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:191)
08-30 14:56:54.295  4304  4345 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
08-30 14:56:54.295  4304  4345 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
08-30 14:56:54.295  4304  4345 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
08-30 14:56:54.295  4304  4345 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
08-30 14:56:54.295  4304  4345 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
08-30 14:56:54.295  4304  4345 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-30 14:56:54.295  4304  4345 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 14:56:54.295  4304  4345 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-30 14:56:54.295  4304  4345 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-30 14:56:54.321   872  4356 E DropBoxManagerService: Can't write: system_app_crash
08-30 14:56:54.321   872  4356 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop131.tmp: open failed: EROFS (Read-only file system)
08-30 14:56:54.321   872  4356 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-30 14:56:54.321   872  4356 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-30 14:56:54.321   872  4356 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-30 14:56:54.321   872  4356 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-30 14:56:54.321   872  4356 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-30 14:56:54.321   872  4356 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-30 14:56:54.321   872  4356 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-30 14:56:54.321   872  4356 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-30 14:56:54.321   872  4356 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-30 14:56:54.321   872  4356 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-30 14:56:54.321   872  4356 E DropBoxManagerService: 	... 5 more
,08-30 14:56:54.329  1709  4355 D GFEEDBACK_SendErrorReportOperation: Error doing instant send: java.io.IOException: failed to create reports directory
,08-30 14:56:54.329  1709  4355 E GFEEDBACK_SendErrorReportOperation: Error saving report: java.io.IOException: failed to create reports directory
,08-30 14:56:54.342  4304  4335 E SQLiteDatabase: Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
08-30 14:56:54.342  4304  4335 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 14:56:54.342  4304  4335 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-30 14:56:54.342  4304  4335 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-30 14:56:54.342  4304  4335 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-30 14:56:54.342  4304  4335 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-30 14:56:54.342  4304  4335 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-30 14:56:54.342  4304  4335 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-30 14:56:54.342  4304  4335 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-30 14:56:54.342  4304  4335 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-30 14:56:54.342  4304  4335 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-30 14:56:54.342  4304  4335 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-30 14:56:54.342  4304  4335 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-30 14:56:54.342  4304  4335 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-30 14:56:54.342  4304  4335 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-30 14:56:54.342  4304  4335 E SQLiteDatabase: 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
08-30 14:56:54.342  4304  4335 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1596)
08-30 14:56:54.342  4304  4335 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1687)
08-30 14:56:54.342  4304  4335 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
08-30 14:56:54.342  4304  4335 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 14:56:54.342  4304  4335 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-30 14:56:54.342  4304  4335 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-30 14:56:54.342  4304  4335 E SQLiteOpenHelper: Couldn't open contacts2.db for writing (will try read-only):
08-30 14:56:54.342  4304  4335 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 14:56:54.342  4304  4335 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-30 14:56:54.342  4304  4335 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-30 14:56:54.342  4304  4335 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-30 14:56:54.342  4304  4335 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-30 14:56:54.342  4304  4335 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-30 14:56:54.342  4304  4335 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-30 14:56:54.342  4304  4335 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-30 14:56:54.342  4304  4335 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-30 14:56:54.342  4304  4335 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-30 14:56:54.342  4304  4335 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-30 14:56:54.342  4304  4335 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-30 14:56:54.342  4304  4335 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-30 14:56:54.342  4304  4335 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-30 14:56:54.342  4304  4335 E SQLiteOpenHelper: 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
08-30 14:56:54.342  4304  4335 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1596)
08-30 14:56:54.342  4304  4335 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1687)
08-30 14:56:54.342  4304  4335 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
08-30 14:56:54.342  4304  4335 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 14:56:54.342  4304  4335 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:148)
08-30 14:56:54.342  4304  4335 E SQLiteOpenHelper: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-30 14:56:54.342  1494  1494 E SQLiteLog: (3850) statement aborts at 26: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
08-30 14:56:54.344  1494  1494 D AndroidRuntime: Shutting down VM
08-30 14:56:54.345  1494  1494 E AndroidRuntime: FATAL EXCEPTION: main
08-30 14:56:54.345  1494  1494 E AndroidRuntime: Process: com.google.process.gapps, PID: 1494,
08-30 14:56:54.345  1494  1494 E AndroidRuntime: java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-30 14:56:54.345  1494  1494 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2732)
08-30 14:56:54.345  1494  1494 E AndroidRuntime: 	at android.app.ActivityThread.-wrap14(ActivityThread.java)
08-30 14:56:54.345  1494  1494 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1421)
08-30 14:56:54.345  1494  1494 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 14:56:54.345  1494  1494 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-30 14:56:54.345  1494  1494 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-30 14:56:54.345  1494  1494 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 14:56:54.345  1494  1494 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-30 14:56:54.345  1494  1494 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-30 14:56:54.345  1494  1494 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-30 14:56:54.345  1494  1494 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-30 14:56:54.345  1494  1494 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-30 14:56:54.345  1494  1494 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-30 14:56:54.345  1494  1494 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-30 14:56:54.345  1494  1494 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
08-30 14:56:54.345  1494  1494 E AndroidRuntime: 	at com.google.android.gms.gcm.bg.a(SourceFile:310)
08-30 14:56:54.345  1494  1494 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
08-30 14:56:54.345  1494  1494 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
08-30 14:56:54.345  1494  1494 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2725)
08-30 14:56:54.345  1494  1494 E AndroidRuntime: 	... 8 more
,08-30 14:56:54.349   872  4360 E DropBoxManagerService: Can't write: system_app_crash
08-30 14:56:54.349   872  4360 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop132.tmp: open failed: EROFS (Read-only file system)
08-30 14:56:54.349   872  4360 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-30 14:56:54.349   872  4360 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-30 14:56:54.349   872  4360 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-30 14:56:54.349   872  4360 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-30 14:56:54.349   872  4360 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-30 14:56:54.349   872  4360 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-30 14:56:54.349   872  4360 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-30 14:56:54.349   872  4360 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-30 14:56:54.349   872  4360 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-30 14:56:54.349   872  4360 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-30 14:56:54.349   872  4360 E DropBoxManagerService: 	... 5 more
08-30 14:56:54.371  4304  4335 E SQLiteLog: (8) statement aborts at 43: [CREATE TABLE IF NOT EXISTS presence_db.presence (presence_data_id INTEGER PRIMARY KEY REFERENCES data(_id),protocol INTEGER NOT NULL,custom_protocol TEXT,im_handle TEXT,im_account TEXT
,08-30 14:56:54.378  4304  4335 I Process : Sending signal. PID: 4304 SIG: 9
,08-30 14:56:54.403   872   882 I ActivityManager: Process android.process.acore (pid 4304) has died
,08-30 14:56:54.404   872   882 W ActivityManager: Scheduling restart of crashed service com.android.providers.contacts/.VoicemailCleanupService in 1000ms
,08-30 14:56:54.624   872   890 W AppOps  : Finishing op nesting under-run: uid 1000 pkg android code 24 time=1465474415550 duration=35 nesting=0
,08-30 14:56:55.223  1889  4302 E native  : dynamic-lm.cc:266 Cannot open fd for /data/user/0/com.google.android.inputmethod.latin/files/Contacts.dict.tmp
08-30 14:56:55.223  1889  4302 E native  : dynamic-lm.cc:257 Cannot write DynamicLm to /data/user/0/com.google.android.inputmethod.latin/files/Contacts.dict.tmp
,08-30 14:56:55.268   872   883 I ActivityManager: Start proc 4362:android.process.acore/u0a5 for content provider com.android.providers.contacts/.ContactsProvider2
,08-30 14:56:55.326  4362  4362 W System  : ClassLoader referenced unknown path: /system/priv-app/ContactsProvider/lib/arm
,08-30 14:56:55.379  4362  4362 W System  : ClassLoader referenced unknown path: /system/app/UserDictionaryProvider/lib/arm
,08-30 14:56:55.409  4362  4375 E SQLiteDatabase: Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
08-30 14:56:55.409  4362  4375 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 14:56:55.409  4362  4375 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-30 14:56:55.409  4362  4375 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-30 14:56:55.409  4362  4375 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-30 14:56:55.409  4362  4375 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-30 14:56:55.409  4362  4375 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-30 14:56:55.409  4362  4375 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-30 14:56:55.409  4362  4375 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-30 14:56:55.409  4362  4375 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-30 14:56:55.409  4362  4375 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-30 14:56:55.409  4362  4375 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-30 14:56:55.409  4362  4375 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-30 14:56:55.409  4362  4375 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-30 14:56:55.409  4362  4375 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-30 14:56:55.409  4362  4375 E SQLiteDatabase: 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
08-30 14:56:55.409  4362  4375 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1596)
08-30 14:56:55.409  4362  4375 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1687)
08-30 14:56:55.409  4362  4375 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
08-30 14:56:55.409  4362  4375 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 14:56:55.409  4362  4375 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-30 14:56:55.409  4362  4375 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-30 14:56:55.411  4362  4375 E SQLiteOpenHelper: Couldn't open contacts2.db for writing (will try read-only):
08-30 14:56:55.411  4362  4375 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 14:56:55.411  4362  4375 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-30 14:56:55.411  4362  4375 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-30 14:56:55.411  4362  4375 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-30 14:56:55.411  4362  4375 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-30 14:56:55.411  4362  4375 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-30 14:56:55.411  4362  4375 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-30 14:56:55.411  4362  4375 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-30 14:56:55.411  4362  4375 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-30 14:56:55.411  4362  4375 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-30 14:56:55.411  4362  4375 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-30 14:56:55.411  4362  4375 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-30 14:56:55.411  4362  4375 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-30 14:56:55.411  4362  4375 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-30 14:56:55.411  4362  4375 E SQLiteOpenHelper: 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
08-30 14:56:55.411  4362  4375 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1596)
08-30 14:56:55.411  4362  4375 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1687)
08-30 14:56:55.411  4362  4375 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
08-30 14:56:55.411  4362  4375 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 14:56:55.411  4362  4375 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:148)
08-30 14:56:55.411  4362  4375 E SQLiteOpenHelper: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-30 14:56:55.436  4362  4375 E SQLiteLog: (8) statement aborts at 43: [CREATE TABLE IF NOT EXISTS presence_db.presence (presence_data_id INTEGER PRIMARY KEY REFERENCES data(_id),protocol INTEGER NOT NULL,custom_protocol TEXT,im_handle TEXT,im_account TEXT
,08-30 14:56:55.441  4362  4375 E AndroidRuntime: FATAL EXCEPTION: ContactsProviderWorker
08-30 14:56:55.441  4362  4375 E AndroidRuntime: Process: android.process.acore, PID: 4362
08-30 14:56:55.441  4362  4375 E AndroidRuntime: android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
08-30 14:56:55.441  4362  4375 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-30 14:56:55.441  4362  4375 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-30 14:56:55.441  4362  4375 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-30 14:56:55.441  4362  4375 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-30 14:56:55.441  4362  4375 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.executeSql(SQLiteDatabase.java:1676)
08-30 14:56:55.441  4362  4375 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.execSQL(SQLiteDatabase.java:1605)
08-30 14:56:55.441  4362  4375 E AndroidRuntime: 	at com.android.providers.contacts.ContactsDatabaseHelper.onOpen(ContactsDatabaseHelper.java:1084)
08-30 14:56:55.441  4362  4375 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:266)
08-30 14:56:55.441  4362  4375 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-30 14:56:55.441  4362  4375 E AndroidRuntime: 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
08-30 14:56:55.441  4362  4375 E AndroidRuntime: 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1596)
08-30 14:56:55.441  4362  4375 E AndroidRuntime: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1687)
08-30 14:56:55.441  4362  4375 E AndroidRuntime: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
08-30 14:56:55.441  4362  4375 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 14:56:55.441  4362  4375 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-30 14:56:55.441  4362  4375 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-30 14:56:55.452   872  4377 E DropBoxManagerService: Can't write: system_app_crash
08-30 14:56:55.452   872  4377 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop133.tmp: open failed: EROFS (Read-only file system)
08-30 14:56:55.452   872  4377 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-30 14:56:55.452   872  4377 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-30 14:56:55.452   872  4377 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-30 14:56:55.452   872  4377 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-30 14:56:55.452   872  4377 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-30 14:56:55.452   872  4377 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-30 14:56:55.452   872  4377 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-30 14:56:55.452   872  4377 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-30 14:56:55.452   872  4377 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-30 14:56:55.452   872  4377 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-30 14:56:55.452   872  4377 E DropBoxManagerService: 	... 5 more
,08-30 14:56:55.988   872   892 I PowerManagerService: Going to sleep due to screen timeout (uid 1000)...
,08-30 14:56:56.032   280   304 D PermissionCache: checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (1805 us)
,08-30 14:56:56.687   872   892 V KeyguardServiceDelegate: onScreenTurnedOff()
,08-30 14:56:56.713   872   892 E libEGL  : call to OpenGL ES API with no current context (logged once per thread)
,08-30 14:56:56.717   280   280 D SurfaceFlinger: Set power mode=0, type=0 flinger=0xb6aa4000
,08-30 14:56:56.717   280   280 D qdhwcomposer: hwc_setPowerMode: Setting mode 0 on display: 0
,08-30 14:56:56.721   872   890 I DisplayManagerService: Display device changed state: "Built-in Screen", OFF
,08-30 14:56:56.726   872   872 W AtomicFile: Couldn't rename file /data/system/usagestats/0/screen_on_time to backup file /data/system/usagestats/0/screen_on_time.bak
,08-30 14:56:56.967   280   342 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0
,08-30 14:56:56.972   280   280 D qdhwcomposer: hwc_setPowerMode: Done setting mode 0 on display 0
,08-30 14:56:56.974   872  1329 D SurfaceControl: Excessive delay in setPowerMode(): 257ms
,08-30 14:56:56.977   872   892 I DreamManagerService: Entering dreamland.
,08-30 14:56:56.978   872   892 I PowerManagerService: Dozing...
,08-30 14:56:56.980   872   887 I DreamController: Starting dream: name=ComponentInfo{com.android.systemui/com.android.systemui.doze.DozeService}, isTest=false, canDoze=true, userId=0
08-30 14:56:56.981   872   885 W BroadcastQueue: Skipping deliver [background] BroadcastRecord{4bacc16 u-1 android.intent.action.CLOSE_SYSTEM_DIALOGS} to ReceiverList{220e07e 1996 com.google.android.googlequicksearchbox/10028/u0 remote:91e239}: process crashing
,08-30 14:56:57.034   872   885 W BroadcastQueue: Skipping deliver [background] BroadcastRecord{c1317f0 u-1 android.intent.action.DREAMING_STARTED} to ReceiverList{ffec0c2 1494 com.google.process.gapps/10011/u0 remote:f1dc90d}: process crashing
,08-30 14:56:57.071   374  1312 D audio_hw_primary: adev_set_parameters: enter: screen_state=on
,08-30 14:56:57.072   374  1312 D mot_vr_audio_hw: adev_set_parameters: screen_state=on
,08-30 14:56:57.084   872  1302 D WifiConfigStore: Retrieve network priorities after PNO.
,08-30 14:56:57.085   872   883 W BroadcastQueue: Skipping deliver [foreground] BroadcastRecord{c29c31c u-1 android.intent.action.SCREEN_ON} to ReceiverList{ffec0c2 1494 com.google.process.gapps/10011/u0 remote:f1dc90d}: process crashing
,08-30 14:56:57.106  1960  4382 D NfcService: Discovery configuration equal, not updating.
,08-30 14:56:57.106   872  1302 E native  : do suspend false
,08-30 14:56:57.137   872  1302 D WifiConfigStore: No blacklist allowed without epno enabled
,08-30 14:56:57.155   872  1302 D WifiConfigStore: Retrieve network priorities after PNO.
,08-30 14:56:57.164   872  1302 E native  : do suspend true
,08-30 14:56:57.196   374  1313 D audio_hw_primary: adev_set_parameters: enter: screen_state=off
,08-30 14:56:57.196   374  1313 D mot_vr_audio_hw: adev_set_parameters: screen_state=off
,08-30 14:56:57.209   872  1389 W BroadcastQueue: Skipping deliver [foreground] BroadcastRecord{ae2cb25 u-1 android.intent.action.SCREEN_OFF} to ReceiverList{ffec0c2 1494 com.google.process.gapps/10011/u0 remote:f1dc90d}: process crashing
,08-30 14:56:57.214   872   872 W BroadcastQueue: Skipping deliver [foreground] BroadcastRecord{ae2cb25 u-1 android.intent.action.SCREEN_OFF} to ReceiverList{74805a0 1494 com.google.process.gapps/10011/u0 remote:9abbea3}: process crashing
,08-30 14:56:57.234   872  1675 W BroadcastQueue: Skipping deliver [foreground] BroadcastRecord{ae2cb25 u-1 android.intent.action.SCREEN_OFF} to ReceiverList{3e30f24 1996 com.google.android.googlequicksearchbox/10028/u0 remote:cf6abb7}: process crashing
,08-30 14:56:57.592   872  1302 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 15, 16 -> obsolete
,08-30 14:56:59.200  1996  2259 W OpenGLRenderer: Incorrectly called buildLayer on View: ShortcutAndWidgetContainer, destroying layer...
,08-30 14:56:59.207   872  1389 I ActivityManager: Killing 3719:com.google.android.apps.docs/u0a46 (adj 15): empty #17
,08-30 14:56:59.217  2065  4390 E Search.SharedPreferencesProto: Failed to rename to backup file /data/user/0/com.google.android.googlequicksearchbox/app_shared_prefs/SearchSettings.bin.bak,
,08-30 14:56:59.345   872  1306 D ConnectivityService: handlePromptUnvalidated 102
,08-30 14:56:59.387   280   342 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0
,08-30 14:56:59.393   975   975 E kickstart: ERROR: function: rx_data:288 Read/Write File descriptor returned error: No such device, error code -1
,08-30 14:56:59.393   975   975 E kickstart: ERROR: function: sahara_main:1143 Sahara protocol error
08-30 14:56:59.395   975   975 E kickstart: ERROR: function: main:268 Uploading  Image using Sahara protocol failed
08-30 14:56:59.396   975   975 I kickstart: STATUS: Wrote to /sys/power/wake_unlock

```
