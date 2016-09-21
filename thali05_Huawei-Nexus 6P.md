#### Test 850469111b8590e_thali05_Huawei-Nexus 6P Logs


```
--------- beginning of main
09-21 05:58:46.007   927  5217 D NetlinkSocketObserver: NeighborEvent{elapsedMs=177890, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-21 05:58:46.468  5588  5588 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
09-21 05:58:46.474  5588  5588 D AndroidRuntime: CheckJNI is OFF
09-21 05:58:46.507  5588  5588 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
09-21 05:58:46.544  5588  5588 I Radio-JNI: register_android_hardware_Radio DONE
09-21 05:58:46.558  5588  5588 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
09-21 05:58:46.562   927  3781 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
09-21 05:58:46.585  4817  4827 W SearchService: Abort, client detached.
09-21 05:58:46.592  4817  4817 I HotwordDetector: Closing mic
09-21 05:58:46.592  4817  5540 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@403631c
09-21 05:58:46.593  4817  5579 E AudioRecord-JNI: Error -4 during AudioRecord native read
09-21 05:58:46.594  5588  5588 D AndroidRuntime: Shutting down VM
09-21 05:58:46.616   927  3141 I ActivityManager: Start proc 5597:com.test.thalitest/u0a77 for activity com.test.thalitest/.MainActivity
09-21 05:58:46.664   511  5582 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
09-21 05:58:46.666   511  5582 D audio_hw_primary: disable_snd_device: snd_device(63: voice-rec-mic)
09-21 05:58:46.671   511  5582 I soundtrigger: audio_extn_sound_trigger_update_device_status: device 0x3f of type 1 for Event 0
09-21 05:58:46.671   511  5582 D sound_trigger_platform: platform_stdev_check_and_update_concurrency: concurrency active 0, tx 0, rx 0, concurrency session_allowed 1
09-21 05:58:46.672   511  3010 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
09-21 05:58:46.675  4817  5577 I MicroRecognitionRnrImpl: Detection finished
09-21 05:58:46.675  4817  5541 I MicroRecognitionRnrImpl: Stopping hotword detection.
09-21 05:58:46.731  5597  5597 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011750)
09-21 05:58:46.753  5597  5597 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,09-21 05:58:46.819  5597  5597 I LibraryLoader: Time to load native libraries: 62 ms (timestamps 8640-8702)
,09-21 05:58:46.819  5597  5597 I LibraryLoader: Expected native library version number "",actual native library version number ""
,09-21 05:58:46.850  5597  5597 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {ac44a0e}
09-21 05:58:46.851  5597  5597 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-21 05:58:46.851  5597  5597 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,09-21 05:58:46.856  5597  5597 I BrowserStartupController: Initializing chromium process, singleProcess=true
,09-21 05:58:46.857  5597  5597 E SysUtils: ApplicationContext is null in ApplicationStatus
,09-21 05:58:46.900  5597  5597 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,09-21 05:58:46.911  5597  5597 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,09-21 05:58:46.911  5597  5597 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-21 05:58:46.911  5597  5597 I Adreno  : QUALCOMM build                   : 63c06b2, I8366cd0437
09-21 05:58:46.911  5597  5597 I Adreno  : Build Date                       : 12/06/15
09-21 05:58:46.911  5597  5597 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
09-21 05:58:46.911  5597  5597 I Adreno  : Local Branch                     : mybranch17112971
09-21 05:58:46.911  5597  5597 I Adreno  : Remote Branch                    : quic/LA.BF64.1.2.9_v2
09-21 05:58:46.911  5597  5597 I Adreno  : Remote Branch                    : NONE
09-21 05:58:46.911  5597  5597 I Adreno  : Reconstruct Branch               : NOTHING
,09-21 05:58:46.942   927   944 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@6c5a61a:true
,09-21 05:58:46.963   732   732 W Binder_3: type=1400 audit(0.0:106): avc: denied { ioctl } for path="socket:[16209]" dev="sockfs" ino=16209 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,09-21 05:58:46.963   732   732 W Binder_3: type=1400 audit(0.0:107): avc: denied { ioctl } for path="socket:[16209]" dev="sockfs" ino=16209 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,09-21 05:58:46.978  5597  5597 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,09-21 05:58:46.986  5597  5597 D SystemWebViewEngine: CordovaWebView is running on device made by: Huawei
,09-21 05:58:47.006   732   732 W Binder_3: type=1400 audit(0.0:108): avc: denied { ioctl } for path="socket:[31931]" dev="sockfs" ino=31931 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,09-21 05:58:47.006   732   732 W Binder_3: type=1400 audit(0.0:109): avc: denied { ioctl } for path="socket:[31931]" dev="sockfs" ino=31931 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
09-21 05:58:47.011  5597  5635 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,09-21 05:58:47.010  3782  3782 W Binder_D: type=1400 audit(0.0:110): avc: denied { ioctl } for path="socket:[13927]" dev="sockfs" ino=13927 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
09-21 05:58:47.010  3782  3782 W Binder_D: type=1400 audit(0.0:111): avc: denied { ioctl } for path="socket:[13927]" dev="sockfs" ino=13927 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,09-21 05:58:47.014  5597  5622 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,09-21 05:58:47.040  5597  5635 I OpenGLRenderer: Initialized EGL, version 1.4
,09-21 05:58:47.103  3142  3142 W Binder_4: type=1400 audit(0.0:112): avc: denied { ioctl } for path="socket:[31935]" dev="sockfs" ino=31935 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
09-21 05:58:47.103  3142  3142 W Binder_4: type=1400 audit(0.0:113): avc: denied { ioctl } for path="socket:[31935]" dev="sockfs" ino=31935 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,09-21 05:58:47.108   927   945 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +515ms
,09-21 05:58:47.110  3407  3407 I Keyboard.Facilitator: onFinishInput()
,09-21 05:58:47.103  3141  3141 W Binder_3: type=1400 audit(0.0:114): avc: denied { ioctl } for path="socket:[31934]" dev="sockfs" ino=31934 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,09-21 05:58:47.103  3141  3141 W Binder_3: type=1400 audit(0.0:115): avc: denied { ioctl } for path="socket:[31934]" dev="sockfs" ino=31934 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,09-21 05:58:47.147  5597  5597 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 5597
,09-21 05:58:47.242  5597  5597 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,09-21 05:58:47.386  5597  5637 D jxcore_app_log: JniHelper::setJavaVM(0xf51bc000), pthread_self() = -583010000
,09-21 05:58:47.389  5597  5637 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
09-21 05:58:47.389  5597  5637 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
09-21 05:58:47.389  5597  5637 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
09-21 05:58:47.389  5597  5637 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
09-21 05:58:47.389  5597  5637 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,09-21 05:58:47.390  5597  5637 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3c7dd94 added. We now have 1 listener(s)
,09-21 05:58:47.392  5597  5637 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 60:83:34:25:D7:C6
,09-21 05:58:47.393  5597  5637 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
,09-21 05:58:47.394  5597  5637 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-21 05:58:47.394  5597  5637 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-21 05:58:47.397  5597  5637 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
09-21 05:58:47.397  5597  5637 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
09-21 05:58:47.397  5597  5637 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
09-21 05:58:47.397  5597  5637 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 60:83:34:25:D7:C6
09-21 05:58:47.397  5597  5637 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
09-21 05:58:47.397  5597  5637 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
09-21 05:58:47.397  5597  5637 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
09-21 05:58:47.397  5597  5637 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
09-21 05:58:47.397  5597  5637 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
09-21 05:58:47.397  5597  5637 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
09-21 05:58:47.397  5597  5637 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
09-21 05:58:47.397  5597  5637 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
09-21 05:58:47.397  5597  5637 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
09-21 05:58:47.397  5597  5637 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
09-21 05:58:47.397  5597  5637 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b508183 added. We now have 1 listener(s)
09-21 05:58:47.397  5597  5637 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-21 05:58:47.400   927  2962 D WifiService: New client listening to asynchronous messages
09-21 05:58:47.401  5597  5637 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-21 05:58:47.401  5597  5637 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
09-21 05:58:47.401  5597  5637 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
09-21 05:58:47.401  5597  5637 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
09-21 05:58:47.401  5597  5637 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
09-21 05:58:47.403  5597  5637 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-21 05:58:47.403  5597  5637 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:C6
,09-21 05:58:47.408  5597  5637 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,09-21 05:58:47.409  5597  5637 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-21 05:58:47.409  5597  5637 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-21 05:58:47.409  5597  5637 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-21 05:58:47.409  5597  5637 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-21 05:58:47.409  5597  5637 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-21 05:58:47.409  5597  5637 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-21 05:58:47.409  5597  5637 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-21 05:58:47.409  5597  5637 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-21 05:58:47.409  5597  5637 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
09-21 05:58:47.409  5597  5637 D io.jxcore.node.ConnectivityMonitor: start: OK
09-21 05:58:47.410  5597  5637 I io.jxcore.node.LifeCycleMonitor: start: OK
,09-21 05:58:47.413  5597  5597 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-21 05:58:47.416  5597  5597 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-21 05:58:47.437  5597  5597 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,09-21 05:58:47.703  5597  5645 W jxcore-log: Initializing JXcore engine
09-21 05:58:47.703  5597  5645 W jxcore-log: JXcore engine is ready
,09-21 05:58:47.723  5645  5645 W Thread-58: type=1400 audit(0.0:116): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=12566 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,09-21 05:58:47.726  5645  5645 W Thread-58: type=1400 audit(0.0:117): avc: denied { ioctl } for path="socket:[16424]" dev="sockfs" ino=16424 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
09-21 05:58:47.726  5645  5645 W Thread-58: type=1400 audit(0.0:118): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2901 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
09-21 05:58:47.726  5645  5645 W Thread-58: type=1400 audit(0.0:119): avc: denied { ioctl } for path="socket:[32996]" dev="sockfs" ino=32996 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:untrusted_app:s0:c512,c768 tclass=netlink_route_socket permissive=0
,09-21 05:58:47.736  5597  5645 W jxcore-log: Starting JXcore engine
,09-21 05:58:47.785  5597  5645 W jxcore-log: Platform android
09-21 05:58:47.785  5597  5645 W jxcore-log: 
09-21 05:58:47.785  5597  5645 W jxcore-log: Process ARCH arm
09-21 05:58:47.785  5597  5645 W jxcore-log: 
,09-21 05:58:47.879  5597  5645 I jxcore-log: JXcore Cordova bridge is ready!
09-21 05:58:47.879  5597  5645 I jxcore-log: 
,09-21 05:58:47.879  5597  5645 W jxcore-log: JXcore engine is started
,09-21 05:58:47.890  5597  5637 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,09-21 05:58:47.898  5597  5597 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,09-21 05:58:49.806   927  2961 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-21 05:58:54.508  5597  5645 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
09-21 05:58:54.508  5597  5645 I jxcore-log: 
,09-21 05:58:54.510  5597  5645 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
09-21 05:58:54.510  5597  5645 I jxcore-log: 
,09-21 05:58:54.514  5597  5645 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-21 05:58:54.514  5597  5645 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-21 05:58:54.514  5597  5645 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-21 05:58:54.514  5597  5645 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-21 05:58:54.514  5597  5645 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-21 05:58:54.514  5597  5645 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-21 05:58:54.514  5597  5645 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-21 05:58:54.514  5597  5645 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-21 05:58:54.515  5597  5645 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-21 05:58:54.517  5597  5645 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
09-21 05:58:54.517  5597  5645 I jxcore-log: 
,09-21 05:58:54.518  5597  5645 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
09-21 05:58:54.518  5597  5645 I jxcore-log: 
,09-21 05:58:54.878  5597  5645 D executeNativeTests: Running unit tests
,09-21 05:58:54.892  5597  5645 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 1
,09-21 05:58:54.892  5597  5645 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 1
09-21 05:58:54.892  5597  5645 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
,09-21 05:58:54.892  5597  5645 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
09-21 05:58:54.892  5597  5645 D com.test.thalitest.ThaliTestRunner: Total duration: 2 ms
,09-21 05:58:54.894  5597  5645 I jxcore-log: *Native tests were executed*
09-21 05:58:54.894  5597  5645 I jxcore-log: 
,09-21 05:58:54.894  5597  5645 I jxcore-log: Total number of executed tests:  1
09-21 05:58:54.894  5597  5645 I jxcore-log: 
,09-21 05:58:54.894  5597  5645 I jxcore-log: Number of passed tests:  1
09-21 05:58:54.894  5597  5645 I jxcore-log: 
,09-21 05:58:54.894  5597  5645 I jxcore-log: Number of failed tests:  0
09-21 05:58:54.894  5597  5645 I jxcore-log: 
,09-21 05:58:54.894  5597  5645 I jxcore-log: Number of ignored tests:  0
09-21 05:58:54.894  5597  5645 I jxcore-log: 
,09-21 05:58:54.895  5597  5645 I jxcore-log: Total duration:  2
09-21 05:58:54.895  5597  5645 I jxcore-log: 
09-21 05:58:54.895  5597  5645 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
09-21 05:58:54.895  5597  5645 I jxcore-log: 
09-21 05:58:54.897  5597  5645 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-21 05:58:54.897  5597  5645 I jxcore-log: 
,09-21 05:58:54.918  5597  5597 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
,09-21 05:58:55.397  5647  5647 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,09-21 05:58:55.402  5647  5647 D AndroidRuntime: CheckJNI is OFF
,09-21 05:58:55.430  5647  5647 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,09-21 05:58:55.460  5647  5647 I Radio-JNI: register_android_hardware_Radio DONE
,09-21 05:58:55.476  5647  5647 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,09-21 05:58:55.489   927   940 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=-1: uninstall pkg
,09-21 05:58:55.490   927   940 I ActivityManager: Killing 5597:com.test.thalitest/u0a77 (adj 0): stop com.test.thalitest
,09-21 05:58:55.557   927   937 D GraphicsStats: Buffer count: 2
09-21 05:58:55.558   927  2962 D WifiService: Client connection lost with reason: 4
,09-21 05:58:55.558   927  3422 I WindowState: WIN DEATH: Window{563c9ca u0 com.test.thalitest/com.test.thalitest.MainActivity}
,09-21 05:58:55.578   927   940 W ActivityManager: Force removing ActivityRecord{dc8f6e3 u0 com.test.thalitest/.MainActivity t2}: app died, no saved state
,09-21 05:58:55.610   927   950 I art     : Starting a blocking GC Explicit
,09-21 05:58:55.616   927  3588 W ActivityManager: Spurious death for ProcessRecord{e28539c 0:com.test.thalitest/u0a77}, curProc for 5597: null
,09-21 05:58:55.645   927  3588 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 5597 uid 10077
,09-21 05:58:55.648  3407  3407 I Keyboard.Facilitator: onFinishInput()
,09-21 05:58:55.640  3588  3588 W Binder_B: type=1400 audit(0.0:120): avc: denied { ioctl } for path="socket:[27294]" dev="sockfs" ino=27294 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
09-21 05:58:55.640  3588  3588 W Binder_B: type=1400 audit(0.0:121): avc: denied { ioctl } for path="socket:[27294]" dev="sockfs" ino=27294 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,09-21 05:58:55.692  4817  4817 W LocationOracleImpl: Best location was null
,09-21 05:58:55.692   927   950 I art     : Explicit concurrent mark sweep GC freed 27763(1937KB) AllocSpace objects, 13(340KB) LOS objects, 33% free, 29MB/43MB, paused 1.723ms total 81.568ms
,09-21 05:58:55.712   927   950 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,09-21 05:58:55.716  5647  5647 I art     : System.exit called, status: 0
09-21 05:58:55.716  5647  5647 I AndroidRuntime: VM exiting with result code 0.
,09-21 05:58:55.718  4817  5662 I MicroRecognitionRnrImpl: Starting detection.
,09-21 05:58:55.720  4817  5663 I MicrophoneInputStream: mic_starting com.google.android.apps.gsa.speech.audio.x@454f4f8
,09-21 05:58:55.721   511  5665 I AudioFlinger: AudioFlinger's thread 0xf1b40000 ready to run
,09-21 05:58:55.724   927   950 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=0: pkg removed
09-21 05:58:55.727   511  3010 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
,09-21 05:58:55.730  4817  5663 I MicrophoneInputStream: mic_started com.google.android.apps.gsa.speech.audio.x@454f4f8
,09-21 05:58:55.739   511  5665 D audio_hw_primary: select_devices: out_snd_device(0: none) in_snd_device(63: voice-rec-mic)
09-21 05:58:55.739   511  5665 D msm8974_platform: platform_send_audio_calibration: sending audio calibration for snd_device(63) acdb_id(62)
09-21 05:58:55.739   511  5665 I ACDB-LOADER: ACDB AFE returned = -19
09-21 05:58:55.739   511  5665 I soundtrigger: audio_extn_sound_trigger_update_device_status: device 0x3f of type 1 for Event 1
09-21 05:58:55.740   511  5665 D sound_trigger_platform: platform_stdev_check_and_update_concurrency: concurrency active 0, tx 1, rx 0, concurrency session_allowed 0
09-21 05:58:55.740   511  5665 D audio_hw_primary: enable_snd_device: snd_device(63: voice-rec-mic)
,09-21 05:58:55.740  4465  4465 D BluetoothMapAppObserver: onReceive
,09-21 05:58:55.740  4465  4465 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
,09-21 05:58:55.742  3407  3407 I Keyboard.Facilitator: resetDictionaries() : en_US
,09-21 05:58:55.746  3648  3965 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
09-21 05:58:55.747   511  5665 D audio_hw_primary: enable_audio_route: apply and update mixer path: audio-record
09-21 05:58:55.754   927  2927 I InputReader: Reconfiguring input devices.  changes=0x00000010
,09-21 05:58:55.765  3407  5667 I Keyboard.Facilitator.DecoderInitializer: run()
,09-21 05:58:55.771  3407  5667 I Decoder : createOrResetDecoder
,09-21 05:58:55.800   437   437 W kworker/5:1: type=1400 audit(0.0:122): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,09-21 05:58:55.811  3648  3929 W GCoreFlp: No location to return for getLastLocation()
,09-21 05:58:55.803   437   437 W kworker/5:1: type=1400 audit(0.0:123): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,09-21 05:58:55.813   437   437 W kworker/5:1: type=1400 audit(0.0:124): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,09-21 05:58:55.823  3495  3495 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,09-21 05:58:55.830  4817  4817 I HotwordWorkerImpl: onReady
,09-21 05:58:55.830  3390  3420 E SQLiteLog: (14) cannot open file at line 31278 of [2ef4f3a5b1]
09-21 05:58:55.830  3390  3420 E SQLiteLog: (14) os_unix.c:31278: (30) open(/data/user/0/com.android.providers.contacts/databases/contacts2.db-mjFEC1F592E) - 
,--------- beginning of crash
09-21 05:58:55.831  3390  3420 E AndroidRuntime: FATAL EXCEPTION: ContactsProviderWorker
09-21 05:58:55.831  3390  3420 E AndroidRuntime: Process: android.process.acore, PID: 3390
09-21 05:58:55.831  3390  3420 E AndroidRuntime: android.database.sqlite.SQLiteCantOpenDatabaseException: unable to open database file (code 14)
09-21 05:58:55.831  3390  3420 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
09-21 05:58:55.831  3390  3420 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:553)
09-21 05:58:55.831  3390  3420 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.endTransactionUnchecked(SQLiteSession.java:437)
09-21 05:58:55.831  3390  3420 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.endTransaction(SQLiteSession.java:401)
09-21 05:58:55.831  3390  3420 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.endTransaction(SQLiteDatabase.java:522)
09-21 05:58:55.831  3390  3420 E AndroidRuntime: 	at com.android.providers.contacts.ContactDirectoryManager.updateDirectoriesForPackage(ContactDirectoryManager.java:411)
09-21 05:58:55.831  3390  3420 E AndroidRuntime: 	at com.android.providers.contacts.ContactDirectoryManager.onPackageChanged(ContactDirectoryManager.java:360)
09-21 05:58:55.831  3390  3420 E AndroidRuntime: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1753)
09-21 05:58:55.831  3390  3420 E AndroidRuntime: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
09-21 05:58:55.831  3390  3420 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-21 05:58:55.831  3390  3420 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-21 05:58:55.831  3390  3420 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,09-21 05:58:55.834  3580  3580 I ConfigService: onCreate
,09-21 05:58:55.838  3580  5672 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/config.db'.
09-21 05:58:55.838  3580  5672 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-21 05:58:55.838  3580  5672 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-21 05:58:55.838  3580  5672 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-21 05:58:55.838  3580  5672 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-21 05:58:55.838  3580  5672 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-21 05:58:55.838  3580  5672 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-21 05:58:55.838  3580  5672 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-21 05:58:55.838  3580  5672 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-21 05:58:55.838  3580  5672 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-21 05:58:55.838  3580  5672 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-21 05:58:55.838  3580  5672 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-21 05:58:55.838  3580  5672 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-21 05:58:55.838  3580  5672 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-21 05:58:55.838  3580  5672 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-21 05:58:55.838  3580  5672 E SQLiteDatabase: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
09-21 05:58:55.838  3580  5672 E SQLiteDatabase: 	at com.google.android.gms.config.j.run(SourceFile:152)
09-21 05:58:55.838  3580  5672 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
,09-21 05:58:55.838  3580  5672 E SQLiteOpenHelper: Couldn't open config.db for writing (will try read-only):
09-21 05:58:55.838  3580  5672 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-21 05:58:55.838  3580  5672 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-21 05:58:55.838  3580  5672 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-21 05:58:55.838  3580  5672 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-21 05:58:55.838  3580  5672 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-21 05:58:55.838  3580  5672 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-21 05:58:55.838  3580  5672 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-21 05:58:55.838  3580  5672 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-21 05:58:55.838  3580  5672 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-21 05:58:55.838  3580  5672 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-21 05:58:55.838  3580  5672 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-21 05:58:55.838  3580  5672 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-21 05:58:55.838  3580  5672 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-21 05:58:55.838  3580  5672 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-21 05:58:55.838  3580  5672 E SQLiteOpenHelper: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
09-21 05:58:55.838  3580  5672 E SQLiteOpenHelper: 	at com.google.android.gms.config.j.run(SourceFile:152)
09-21 05:58:55.838  3580  5672 E SQLiteOpenHelper: 	at java.lang.Thread.run(Thread.java:818)
,09-21 05:58:55.840  3390  5671 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
09-21 05:58:55.842  3580  5672 W SQLiteOpenHelper: Opened config.db in read-only mode
09-21 05:58:55.843  3648  3929 W GCoreFlp: No location to return for getLastLocation()
,09-21 05:58:55.856  3530  3696 E SQLiteLog: (3850) statement aborts at 23: [DELETE FROM icons WHERE componentName LIKE ? AND profileId = ?] disk I/O error
,09-21 05:58:55.856   927  5674 E DropBoxManagerService: Can't write: system_app_crash
09-21 05:58:55.856   927  5674 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop108.tmp: open failed: EROFS (Read-only file system)
09-21 05:58:55.856   927  5674 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-21 05:58:55.856   927  5674 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-21 05:58:55.856   927  5674 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-21 05:58:55.856   927  5674 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-21 05:58:55.856   927  5674 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-21 05:58:55.856   927  5674 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
09-21 05:58:55.856   927  5674 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-21 05:58:55.856   927  5674 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-21 05:58:55.856   927  5674 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-21 05:58:55.856   927  5674 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-21 05:58:55.856   927  5674 E DropBoxManagerService: 	... 5 more
09-21 05:58:55.857   927   939 W AtomicFile: Couldn't rename file /data/system/users/0/runtime-permissions.xml to backup file /data/system/users/0/runtime-permissions.xml.bak
,09-21 05:58:55.859   927   939 E PackageManager: Failed to write settings, restoring backup
09-21 05:58:55.859   927   939 E PackageManager: java.io.IOException: Couldn't create directory /data/system/users/0/runtime-permissions.xml
09-21 05:58:55.859   927   939 E PackageManager: 	at android.util.AtomicFile.startWrite(AtomicFile.java:106)
09-21 05:58:55.859   927   939 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.writePermissionsSync(Settings.java:4615)
09-21 05:58:55.859   927   939 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.-wrap1(Settings.java)
09-21 05:58:55.859   927   939 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence$MyHandler.handleMessage(Settings.java:4830)
09-21 05:58:55.859   927   939 E PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-21 05:58:55.859   927   939 E PackageManager: 	at android.os.Looper.loop(Looper.java:148)
09-21 05:58:55.859   927   939 E PackageManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,09-21 05:58:55.860   927   927 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,09-21 05:58:55.861   927   940 E DropBoxManagerService: Can't write: system_server_wtf
09-21 05:58:55.861   927   940 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop15.tmp: open failed: EROFS (Read-only file system)
09-21 05:58:55.861   927   940 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-21 05:58:55.861   927   940 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-21 05:58:55.861   927   940 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-21 05:58:55.861   927   940 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-21 05:58:55.861   927   940 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-21 05:58:55.861   927   940 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
09-21 05:58:55.861   927   940 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12561)
09-21 05:58:55.861   927   940 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.handleApplicationWtfInner(ActivityManagerService.java:12374)
09-21 05:58:55.861   927   940 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:12346)
09-21 05:58:55.861   927   940 E DropBoxManagerService: 	at android.os.Handler.handleCallback(Handler.java:739)
09-21 05:58:55.861   927   940 E DropBoxManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-21 05:58:55.861   927   940 E DropBoxManagerService: 	at android.os.Looper.loop(Looper.java:148)
09-21 05:58:55.861   927   940 E DropBoxManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-21 05:58:55.861   927   940 E DropBoxManagerService: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
09-21 05:58:55.861   927   940 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-21 05:58:55.861   927   940 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-21 05:58:55.861   927   940 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-21 05:58:55.861   927   940 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-21 05:58:55.861   927   940 E DropBoxManagerService: 	... 13 more
09-21 05:58:55.864  3407  5667 I Keyboard.Facilitator.MainLanguageModelLoader: run()
,09-21 05:58:55.870  4014  4014 W Binder_5: type=1400 audit(0.0:125): avc: denied { ioctl } for path="socket:[33847]" dev="sockfs" ino=33847 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
09-21 05:58:55.870  4014  4014 W Binder_5: type=1400 audit(0.0:126): avc: denied { ioctl } for path="socket:[33847]" dev="sockfs" ino=33847 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,09-21 05:58:55.873  4014  4014 W Binder_5: type=1400 audit(0.0:127): avc: denied { ioctl } for path="socket:[33046]" dev="sockfs" ino=33046 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,09-21 05:58:55.873  4014  4014 W Binder_5: type=1400 audit(0.0:128): avc: denied { ioctl } for path="socket:[33046]" dev="sockfs" ino=33046 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
09-21 05:58:55.878   927  5676 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,09-21 05:58:55.895   927  3523 I ActivityManager: Start proc 5677:com.google.android.googlequicksearchbox:crash_report/u0a29 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
,09-21 05:58:55.896  3530  3696 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
09-21 05:58:55.896  3530  3696 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 3530
09-21 05:58:55.896  3530  3696 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-21 05:58:55.896  3530  3696 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
09-21 05:58:55.896  3530  3696 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
09-21 05:58:55.896  3530  3696 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
09-21 05:58:55.896  3530  3696 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
09-21 05:58:55.896  3530  3696 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
09-21 05:58:55.896  3530  3696 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
09-21 05:58:55.896  3530  3696 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
09-21 05:58:55.896  3530  3696 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
09-21 05:58:55.896  3530  3696 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-21 05:58:55.896  3530  3696 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-21 05:58:55.896  3530  3696 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,09-21 05:58:55.903   927  3422 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,09-21 05:58:55.904   927  5688 E DropBoxManagerService: Can't write: system_app_crash
09-21 05:58:55.904   927  5688 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop111.tmp: open failed: EROFS (Read-only file system)
09-21 05:58:55.904   927  5688 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-21 05:58:55.904   927  5688 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-21 05:58:55.904   927  5688 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-21 05:58:55.904   927  5688 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-21 05:58:55.904   927  5688 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-21 05:58:55.904   927  5688 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
09-21 05:58:55.904   927  5688 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-21 05:58:55.904   927  5688 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-21 05:58:55.904   927  5688 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-21 05:58:55.904   927  5688 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-21 05:58:55.904   927  5688 E DropBoxManagerService: 	... 5 more
09-21 05:58:55.905  3390  5671 E SQLiteLog: (3850) statement aborts at 18: [DELETE FROM calls WHERE (((source_package = 'com.test.thalitest'))) AND ((type = 4))] disk I/O error
,09-21 05:58:55.907  3390  5671 I Process : Sending signal. PID: 3390 SIG: 9
,09-21 05:58:55.909  4817  4827 W SearchService: Abort, client detached.
,09-21 05:58:55.912  4817  5540 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@454f4f8
,09-21 05:58:55.913  4817  4817 I HotwordDetector: Closing mic
09-21 05:58:55.913  4817  5663 E AudioRecord-JNI: Error -4 during AudioRecord native read
09-21 05:58:55.914  3580  3580 E SQLiteLog: (3850) statement aborts at 26: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
09-21 05:58:55.915  3580  3580 D AndroidRuntime: Shutting down VM
09-21 05:58:55.916  3580  3580 E AndroidRuntime: FATAL EXCEPTION: main
09-21 05:58:55.916  3580  3580 E AndroidRuntime: Process: com.google.process.gapps, PID: 3580
09-21 05:58:55.916  3580  3580 E AndroidRuntime: java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-21 05:58:55.916  3580  3580 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2732)
09-21 05:58:55.916  3580  3580 E AndroidRuntime: 	at android.app.ActivityThread.-wrap14(ActivityThread.java)
09-21 05:58:55.916  3580  3580 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1421)
09-21 05:58:55.916  3580  3580 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-21 05:58:55.916  3580  3580 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-21 05:58:55.916  3580  3580 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-21 05:58:55.916  3580  3580 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
09-21 05:58:55.916  3580  3580 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-21 05:58:55.916  3580  3580 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-21 05:58:55.916  3580  3580 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-21 05:58:55.916  3580  3580 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
09-21 05:58:55.916  3580  3580 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
09-21 05:58:55.916  3580  3580 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
09-21 05:58:55.916  3580  3580 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
09-21 05:58:55.916  3580  3580 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
09-21 05:58:55.916  3580  3580 E AndroidRuntime: 	at com.google.android.gms.gcm.bg.a(SourceFile:310)
09-21 05:58:55.916  3580  3580 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
09-21 05:58:55.916  3580  3580 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
09-21 05:58:55.916  3580  3580 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2725)
09-21 05:58:55.916  3580  3580 E AndroidRuntime: 	... 8 more
,09-21 05:58:55.923   927  5690 E DropBoxManagerService: Can't write: system_app_crash
09-21 05:58:55.923   927  5690 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop112.tmp: open failed: EROFS (Read-only file system)
09-21 05:58:55.923   927  5690 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-21 05:58:55.923   927  5690 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-21 05:58:55.923   927  5690 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-21 05:58:55.923   927  5690 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-21 05:58:55.923   927  5690 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-21 05:58:55.923   927  5690 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
09-21 05:58:55.923   927  5690 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-21 05:58:55.923   927  5690 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-21 05:58:55.923   927  5690 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-21 05:58:55.923   927  5690 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-21 05:58:55.923   927  5690 E DropBoxManagerService: 	... 5 more
,09-21 05:58:55.926  3648  3929 W GCoreFlp: No location to return for getLastLocation()
,09-21 05:58:55.955   927  3142 I ActivityManager: Process android.process.acore (pid 3390) has died
,09-21 05:58:55.956   927  3142 W ActivityManager: Scheduling restart of crashed service com.android.providers.contacts/.VoicemailCleanupService in 1000ms
,09-21 05:58:55.997   511  5665 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
,09-21 05:58:55.998   511  5665 D audio_hw_primary: disable_snd_device: snd_device(63: voice-rec-mic)
,09-21 05:58:56.003   511  5665 I soundtrigger: audio_extn_sound_trigger_update_device_status: device 0x3f of type 1 for Event 0
09-21 05:58:56.003   511  5665 D sound_trigger_platform: platform_stdev_check_and_update_concurrency: concurrency active 0, tx 0, rx 0, concurrency session_allowed 1
09-21 05:58:56.003   511  3010 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
,09-21 05:58:56.005  4817  5662 I MicroRecognitionRnrImpl: Detection finished
,09-21 05:58:56.006  4817  5541 I MicroRecognitionRnrImpl: Stopping hotword detection.

```
