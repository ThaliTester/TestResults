#### Test 909164155576f84_thali07_Huawei-Nexus 6P Logs


```
--------- beginning of main
10-26 02:42:19.916  3717  4216 I Icing   : Indexing 3C763AF371F9E97B4ECFEA01A338ADB468C38476 from com.google.android.googlequicksearchbox
10-26 02:42:19.992  3717  4216 I Icing   : Indexing done 3C763AF371F9E97B4ECFEA01A338ADB468C38476
,10-26 02:42:20.395  5617  5617 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
10-26 02:42:20.401  5617  5617 D AndroidRuntime: CheckJNI is OFF
10-26 02:42:20.428  5617  5617 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
10-26 02:42:20.463  5617  5617 I Radio-JNI: register_android_hardware_Radio DONE
10-26 02:42:20.478  5617  5617 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
10-26 02:42:20.496   926  3106 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
10-26 02:42:20.514  5617  5617 D AndroidRuntime: Shutting down VM
10-26 02:42:20.525  3950  3973 W SearchService: Abort, client detached.
10-26 02:42:20.536  3950  3950 I HotwordDetector: Closing mic
10-26 02:42:20.537  3950  4189 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@3b9d978
10-26 02:42:20.537  3950  4203 E AudioRecord-JNI: Error -4 during AudioRecord native read
10-26 02:42:20.551   926  3766 I ActivityManager: Start proc 5627:com.test.thalitest/u0a77 for activity com.test.thalitest/.MainActivity
10-26 02:42:20.610   511  4209 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
10-26 02:42:20.611   511  4209 D audio_hw_primary: disable_snd_device: snd_device(63: voice-rec-mic)
10-26 02:42:20.615   511  4209 I soundtrigger: audio_extn_sound_trigger_update_device_status: device 0x3f of type 1 for Event 0
10-26 02:42:20.615   511  4209 D sound_trigger_platform: platform_stdev_check_and_update_concurrency: concurrency active 0, tx 0, rx 0, concurrency session_allowed 1
10-26 02:42:20.616   511  3001 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
10-26 02:42:20.618  3950  4195 I MicroRecognitionRnrImpl: Stopping hotword detection.
10-26 02:42:20.618  3950  4202 I MicroRecognitionRnrImpl: Detection finished
10-26 02:42:20.653  5627  5627 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011750)
10-26 02:42:20.673  5627  5627 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
10-26 02:42:20.733  5627  5627 I LibraryLoader: Time to load native libraries: 57 ms (timestamps 9014-9071)
10-26 02:42:20.733  5627  5627 I LibraryLoader: Expected native library version number "",actual native library version number ""
,10-26 02:42:20.765  5627  5627 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {fe0fd92}
,10-26 02:42:20.766  5627  5627 I LibraryLoader: Expected native library version number "",actual native library version number ""
10-26 02:42:20.766  5627  5627 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,10-26 02:42:20.769  5627  5627 I BrowserStartupController: Initializing chromium process, singleProcess=true
,10-26 02:42:20.770  5627  5627 E SysUtils: ApplicationContext is null in ApplicationStatus
,10-26 02:42:20.822  5627  5627 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,10-26 02:42:20.835  5627  5627 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
10-26 02:42:20.835  5627  5627 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
10-26 02:42:20.835  5627  5627 I Adreno  : QUALCOMM build                   : 63c06b2, I8366cd0437
10-26 02:42:20.835  5627  5627 I Adreno  : Build Date                       : 12/06/15
10-26 02:42:20.835  5627  5627 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
10-26 02:42:20.835  5627  5627 I Adreno  : Local Branch                     : mybranch17112971
10-26 02:42:20.835  5627  5627 I Adreno  : Remote Branch                    : quic/LA.BF64.1.2.9_v2
10-26 02:42:20.835  5627  5627 I Adreno  : Remote Branch                    : NONE
10-26 02:42:20.835  5627  5627 I Adreno  : Reconstruct Branch               : NOTHING
,10-26 02:42:20.868   926   943 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@370641:true
,10-26 02:42:20.897  2455  2455 W Binder_3: type=1400 audit(0.0:99): avc: denied { ioctl } for path="socket:[14044]" dev="sockfs" ino=14044 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,10-26 02:42:20.897  2455  2455 W Binder_3: type=1400 audit(0.0:100): avc: denied { ioctl } for path="socket:[14044]" dev="sockfs" ino=14044 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,10-26 02:42:20.911  5627  5627 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,10-26 02:42:20.919  5627  5627 D SystemWebViewEngine: CordovaWebView is running on device made by: Huawei
,10-26 02:42:20.944   407   407 W Binder_2: type=1400 audit(0.0:101): avc: denied { ioctl } for path="socket:[31670]" dev="sockfs" ino=31670 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,10-26 02:42:20.944   407   407 W Binder_2: type=1400 audit(0.0:102): avc: denied { ioctl } for path="socket:[31670]" dev="sockfs" ino=31670 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
10-26 02:42:20.947  5627  5664 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,10-26 02:42:20.947   936   936 W Binder_1: type=1400 audit(0.0:103): avc: denied { ioctl } for path="socket:[14054]" dev="sockfs" ino=14054 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,10-26 02:42:20.947   936   936 W Binder_1: type=1400 audit(0.0:104): avc: denied { ioctl } for path="socket:[14054]" dev="sockfs" ino=14054 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,10-26 02:42:20.952  5627  5651 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,10-26 02:42:20.974  5627  5664 I OpenGLRenderer: Initialized EGL, version 1.4
,10-26 02:42:21.050  3766  3766 W Binder_8: type=1400 audit(0.0:105): avc: denied { ioctl } for path="socket:[31673]" dev="sockfs" ino=31673 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,10-26 02:42:21.050  3766  3766 W Binder_8: type=1400 audit(0.0:106): avc: denied { ioctl } for path="socket:[31673]" dev="sockfs" ino=31673 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,10-26 02:42:21.053   926   944 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +524ms
,10-26 02:42:21.060  3649  3649 I Keyboard.Facilitator: onFinishInput()
10-26 02:42:21.054  3106  3106 W Binder_3: type=1400 audit(0.0:107): avc: denied { ioctl } for path="socket:[31672]" dev="sockfs" ino=31672 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,10-26 02:42:21.057  3106  3106 W Binder_3: type=1400 audit(0.0:108): avc: denied { ioctl } for path="socket:[31672]" dev="sockfs" ino=31672 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,10-26 02:42:21.088  5627  5627 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 5627
,10-26 02:42:21.200  5627  5627 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,10-26 02:42:21.377  5627  5667 D jxcore_app_log: JniHelper::setJavaVM(0xf547c000), pthread_self() = -579860176
,10-26 02:42:21.381  5627  5667 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
10-26 02:42:21.381  5627  5667 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
10-26 02:42:21.381  5627  5667 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
10-26 02:42:21.381  5627  5667 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
10-26 02:42:21.381  5627  5667 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,10-26 02:42:21.381  5627  5667 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2ce2711 added. We now have 1 listener(s)
,10-26 02:42:21.383  5627  5667 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 60:83:34:25:D7:D4
,10-26 02:42:21.384  5627  5667 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
10-26 02:42:21.384  5627  5667 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,10-26 02:42:21.384  5627  5667 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,10-26 02:42:21.386  5627  5667 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
10-26 02:42:21.386  5627  5667 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
10-26 02:42:21.386  5627  5667 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
10-26 02:42:21.386  5627  5667 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 60:83:34:25:D7:D4
10-26 02:42:21.386  5627  5667 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
10-26 02:42:21.386  5627  5667 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
10-26 02:42:21.386  5627  5667 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
10-26 02:42:21.386  5627  5667 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
10-26 02:42:21.386  5627  5667 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
10-26 02:42:21.386  5627  5667 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
10-26 02:42:21.386  5627  5667 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
10-26 02:42:21.386  5627  5667 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
10-26 02:42:21.386  5627  5667 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
10-26 02:42:21.386  5627  5667 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,10-26 02:42:21.386  5627  5667 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ac342e4 added. We now have 1 listener(s)
,10-26 02:42:21.387  5627  5667 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,10-26 02:42:21.390   926  2994 D WifiService: New client listening to asynchronous messages
,10-26 02:42:21.391  5627  5667 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
10-26 02:42:21.391  5627  5667 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
10-26 02:42:21.391  5627  5667 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
10-26 02:42:21.391  5627  5667 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
10-26 02:42:21.391  5627  5667 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,10-26 02:42:21.393  5627  5667 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-26 02:42:21.393  5627  5667 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
,10-26 02:42:21.397  5627  5667 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
10-26 02:42:21.397  5627  5667 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-26 02:42:21.397  5627  5667 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-26 02:42:21.397  5627  5667 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-26 02:42:21.397  5627  5667 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-26 02:42:21.397  5627  5667 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-26 02:42:21.397  5627  5667 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-26 02:42:21.397  5627  5667 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-26 02:42:21.397  5627  5667 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
10-26 02:42:21.397  5627  5667 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
10-26 02:42:21.398  5627  5667 D io.jxcore.node.ConnectivityMonitor: start: OK
,10-26 02:42:21.398  5627  5667 I io.jxcore.node.LifeCycleMonitor: start: OK
,10-26 02:42:21.500  5627  5627 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-26 02:42:21.503  5627  5627 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-26 02:42:21.507  5627  5627 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,10-26 02:42:21.987  5627  5674 W jxcore-log: Initializing JXcore engine
,10-26 02:42:21.987  5627  5674 W jxcore-log: JXcore engine is ready
,10-26 02:42:22.010  5674  5674 W Thread-57: type=1400 audit(0.0:109): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=11661 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
10-26 02:42:22.010  5674  5674 W Thread-57: type=1400 audit(0.0:110): avc: denied { ioctl } for path="socket:[13413]" dev="sockfs" ino=13413 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,10-26 02:42:22.010  5674  5674 W Thread-57: type=1400 audit(0.0:111): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=696 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
10-26 02:42:22.010  5674  5674 W Thread-57: type=1400 audit(0.0:112): avc: denied { ioctl } for path="socket:[31643]" dev="sockfs" ino=31643 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:untrusted_app:s0:c512,c768 tclass=netlink_route_socket permissive=0
,10-26 02:42:22.021  5627  5674 W jxcore-log: Starting JXcore engine
,10-26 02:42:22.071  5627  5674 W jxcore-log: Platform android
10-26 02:42:22.071  5627  5674 W jxcore-log: 
,10-26 02:42:22.071  5627  5674 W jxcore-log: Process ARCH arm
10-26 02:42:22.071  5627  5674 W jxcore-log: 
,10-26 02:42:22.253  5627  5674 I jxcore-log: JXcore Cordova bridge is ready!
10-26 02:42:22.253  5627  5674 I jxcore-log: 
,10-26 02:42:22.253  5627  5674 W jxcore-log: JXcore engine is started
10-26 02:42:22.266  5627  5667 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
10-26 02:42:22.272  5627  5627 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,10-26 02:42:24.023  3545  3545 I ConfigService: onDestroy
,10-26 02:42:25.541   926  3727 I ActivityManager: Killing 5227:org.codeaurora.ims/1001 (adj 15): empty #17
,10-26 02:42:31.925  5627  5674 I jxcore-log: 2016-10-26 00:42:31 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
10-26 02:42:31.925  5627  5674 I jxcore-log: 
,10-26 02:42:31.927  5627  5674 I jxcore-log: 2016-10-26 00:42:31 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
10-26 02:42:31.927  5627  5674 I jxcore-log: 
,10-26 02:42:31.932  5627  5674 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-26 02:42:31.932  5627  5674 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-26 02:42:31.932  5627  5674 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-26 02:42:31.932  5627  5674 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-26 02:42:31.932  5627  5674 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-26 02:42:31.932  5627  5674 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-26 02:42:31.932  5627  5674 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-26 02:42:31.932  5627  5674 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,10-26 02:42:31.933  5627  5674 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,10-26 02:42:31.935  5627  5674 I jxcore-log: 2016-10-26 00:42:31 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
10-26 02:42:31.935  5627  5674 I jxcore-log: 
,10-26 02:42:31.936  5627  5674 I jxcore-log: 2016-10-26 00:42:31 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
10-26 02:42:31.936  5627  5674 I jxcore-log: 
,10-26 02:42:32.037   926  2990 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,10-26 02:42:32.183  5627  5674 I jxcore-log: 2016-10-26 00:42:32 - DEBUG UnitTest_app: 'Running unit tests'
10-26 02:42:32.183  5627  5674 I jxcore-log: 
,10-26 02:42:32.184  5627  5674 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
10-26 02:42:32.184  5627  5674 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d91a278 added. We now have 2 listener(s)
10-26 02:42:32.185  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
,10-26 02:42:32.185  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,10-26 02:42:32.185  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
10-26 02:42:32.185  5627  5674 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-26 02:42:32.185  5627  5674 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@752ed51 added. We now have 2 listener(s)
10-26 02:42:32.185  5627  5674 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,10-26 02:42:32.186  5627  5674 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
10-26 02:42:32.188  5627  5674 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-26 02:42:32.191  5627  5674 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-26 02:42:32.191  5627  5674 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-26 02:42:32.191  5627  5674 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-26 02:42:32.191  5627  5674 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-26 02:42:32.191  5627  5674 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-26 02:42:32.191  5627  5674 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-26 02:42:32.191  5627  5674 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-26 02:42:32.191  5627  5674 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
10-26 02:42:32.192  5627  5674 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,10-26 02:42:32.192  5627  5674 D io.jxcore.node.ConnectivityMonitor: start: OK
10-26 02:42:32.192  5627  5674 D executeNativeTests: Running unit tests
,10-26 02:42:32.198  5627  5627 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-26 02:42:32.203  5627  5627 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-26 02:42:32.228  5627  5674 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,10-26 02:42:32.228  5627  5674 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4962ba7 added. We now have 3 listener(s)
10-26 02:42:32.229  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
10-26 02:42:32.229  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
10-26 02:42:32.229  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
10-26 02:42:32.229  5627  5674 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,10-26 02:42:32.229  5627  5674 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f67a854 added. We now have 3 listener(s)
10-26 02:42:32.229  5627  5674 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
10-26 02:42:32.230  5627  5674 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
10-26 02:42:32.231  5627  5674 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,10-26 02:42:32.233  5627  5674 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-26 02:42:32.233  5627  5674 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-26 02:42:32.233  5627  5674 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-26 02:42:32.233  5627  5674 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-26 02:42:32.233  5627  5674 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-26 02:42:32.233  5627  5674 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-26 02:42:32.233  5627  5674 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-26 02:42:32.233  5627  5674 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,10-26 02:42:32.234  5627  5674 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
10-26 02:42:32.234  5627  5674 D io.jxcore.node.ConnectivityMonitor: start: OK
10-26 02:42:32.235  5627  5674 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
10-26 02:42:32.236  5627  5674 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,10-26 02:42:32.236  5627  5674 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,10-26 02:42:32.236  5627  5674 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
10-26 02:42:32.236  5627  5674 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
,10-26 02:42:32.236  5627  5674 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
,10-26 02:42:32.236  5627  5674 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
10-26 02:42:32.237  5627  5674 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,10-26 02:42:32.237  5627  5674 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
10-26 02:42:32.237  5627  5674 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
10-26 02:42:32.237  5627  5674 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-26 02:42:32.237  5627  5674 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-26 02:42:32.237  5627  5674 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-26 02:42:32.237  5627  5674 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-26 02:42:32.237  5627  5674 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-26 02:42:32.237  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
10-26 02:42:32.238  5627  5674 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,10-26 02:42:32.238  5627  5674 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
10-26 02:42:32.238  5627  5674 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4962ba7 removed from the list
10-26 02:42:32.238  5627  5674 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose,
10-26 02:42:32.238  5627  5674 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f67a854 removed from the list
10-26 02:42:32.239  5627  5627 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-26 02:42:32.244  5627  5627 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-26 02:42:32.244  5627  5674 D io.jxcore.node.ConnectivityMonitor: stop
10-26 02:42:32.245  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-26 02:42:32.245  5627  5674 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-26 02:42:32.245  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-26 02:42:32.245  5627  5674 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
10-26 02:42:32.246  5627  5674 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
10-26 02:42:32.246  5627  5674 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
10-26 02:42:32.246  5627  5674 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
10-26 02:42:32.246  5627  5674 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-26 02:42:32.246  5627  5674 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-26 02:42:32.246  5627  5674 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-26 02:42:32.246  5627  5674 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f67a854 not in the list
10-26 02:42:32.247  5627  5674 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
10-26 02:42:32.247  5627  5674 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-26 02:42:32.247  5627  5674 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-26 02:42:32.247  5627  5674 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-26 02:42:32.247  5627  5674 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-26 02:42:32.247  5627  5674 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-26 02:42:32.247  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-26 02:42:32.247  5627  5674 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-26 02:42:32.247  5627  5674 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4962ba7 not in the list
10-26 02:42:32.247  5627  5674 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-26 02:42:32.247  5627  5674 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f67a854 not in the list
10-26 02:42:32.247  5627  5674 D io.jxcore.node.ConnectivityMonitor: stop
10-26 02:42:32.247  5627  5674 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - ,probably already removed
10-26 02:42:32.247  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-26 02:42:32.247  5627  5674 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-26 02:42:32.248  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-26 02:42:32.248  5627  5674 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
10-26 02:42:32.248  5627  5674 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
10-26 02:42:32.248  5627  5674 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
10-26 02:42:32.248  5627  5674 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
10-26 02:42:32.248  5627  5674 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-26 02:42:32.248  5627  5674 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-26 02:42:32.248  5627  5674 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-26 02:42:32.248  5627  5674 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f67a854 not in the list
10-26 02:42:32.251  5627  5674 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
10-26 02:42:32.251  5627  5674 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
10-26 02:42:32.251  5627  5674 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
10-26 02:42:32.251  5627  5674 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
10-26 02:42:32.251  5627  5674 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
10-26 02:42:32.251  5627  5674 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
10-26 02:42:32.251  5627  5674 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
10-26 02:42:32.251  5627  5674 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
10-26 02:42:32.251  5627  5674 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
10-26 02:42:32.251  5627  5674 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
10-26 02:42:32.251  5627  5674 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
10-26 02:42:32.251  5627  5674 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
10-26 02:42:32.251  5627  5674 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
10-26 02:42:32.251  5627  5674 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
10-26 02:42:32.251  5627  5674 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
10-26 02:42:32.251  5627  5674 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
10-26 02:42:32.251  5627  5674 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
10-26 02:42:32.251  5627  5674 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
10-26 02:42:32.251  5627  5674 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
10-26 02:42:32.251  5627  5674 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
10-26 02:42:32.251  5627  5674 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
10-26 02:42:32.251  5627  5674 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
10-26 02:42:32.251  5627  5674 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
10-26 02:42:32.251  5627  5674 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
10-26 02:42:32.251  5627  5674 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
10-26 02:42:32.251  5627  5674 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
10-26 02:42:32.251  5627  5674 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
10-26 02:42:32.251  5627  5674 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
10-26 02:42:32.251  5627  5674 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
10-26 02:42:32.251  5627  5674 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
10-26 02:42:32.251  5627  5674 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
10-26 02:42:32.252  5627  5674 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-26 02:42:32.252  5627  5674 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-26 02:42:32.252  5627  5674 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-26 02:42:32.252  5627  5674 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-26 02:42:32.252  5627  5674 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-26 02:42:32.252  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-26 02:42:32.252  5627  5674 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-26 02:42:32.252  5627  5674 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4962ba7 not in the list
10-26 02:42:32.252  5627  5674 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-26 02:42:32.252  5627  5674 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f67a854 not in the list
10-26 02:42:32.252  5627  5674 D io.jxcore.node.ConnectivityMonitor: stop
10-26 02:42:32.252  5627  5674 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-26 02:42:32.252  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-26 02:42:32.252  5627  5674 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-26 02:42:32.252  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-26 02:42:32.252  5627  5674 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
10-26 02:42:32.253  5627  5674 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
10-26 02:42:32.253  5627  5674 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
10-26 02:42:32.253  5627  5674 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
10-26 02:42:32.253  5627  5674 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-26 02:42:32.253  5627  5674 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-26 02:42:32.253  5627  5674 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-26 02:42:32.253  5627  5674 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f67a854 not in the list
10-26 02:42:32.253  5627  5674 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
10-26 02:42:32.254  5627  5674 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-26 02:42:32.256  5627  5674 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-26 02:42:32.256  5627  5674 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-26 02:42:32.256  5627  5674 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-26 02:42:32.256  5627  5674 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-26 02:42:32.256  5627  5674 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-26 02:42:32.256  5627  5674 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-26 02:42:32.256  5627  5674 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-26 02:42:32.256  5627  5674 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
10-26 02:42:32.257  5627  5674 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
10-26 02:42:32.257  5627  5674 D io.jxcore.node.ConnectivityMonitor: start: OK
10-26 02:42:32.257  5627  5674 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
10-26 02:42:32.257  5627  5674 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
10-26 02:42:32.257  5627  5674 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
10-26 02:42:32.257  5627  5674 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-26 02:42:32.257  5627  5674 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
10-26 02:42:32.259  5627  5674 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
10-26 02:42:32.259  5627  5674 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
10-26 02:42:32.259  5627  5627 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-26 02:42:32.259  5627  5674 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
10-26 02:42:32.261  5627  5627 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-26 02:42:32.262  5627  5674 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
10-26 02:42:32.263  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
10-26 02:42:32.263  5627  5674 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
10-26 02:42:32.264  5627  5674 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
10-26 02:42:32.265  5627  5674 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
10-26 02:42:32.265  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-57,5,main], id: 57
10-26 02:42:32.265  5627  5674 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
10-26 02:42:32.265  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
10-26 02:42:32.265  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
10-26 02:42:32.265  5627  5674 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
10-26 02:42:32.265  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-57,5,main], id: 57
10-26 02:42:32.266  5627  5674 D BluetoothAdapter: STATE_ON
10-26 02:42:32.268  4606  4814 D BtGatt.GattService: registerClient() - UUID=69de1390-22d8-4f03-8379-c443c7fa57f4
10-26 02:42:32.269  4606  4668 D BtGatt.GattService: onClientRegistered() - UUID=69de1390-22d8-4f03-8379-c443c7fa57f4, clientIf=5
10-26 02:42:32.269  5627  5638 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
10-26 02:42:32.270  4606  4620 D BtGatt.GattService: start scan with filters
10-26 02:42:32.271  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
10-26 02:42:32.271  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-57,5,main], id: 57
10-26 02:42:32.272  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
10-26 02:42:32.272  5627  5674 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[Thread-57,5,main], id: 57
10-26 02:42:32.272  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[Thread-57,5,main], id: 57
10-26 02:42:32.272  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
10-26 02:42:32.273  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
10-26 02:42:32.273  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[Thread-57,5,main], id: 57
10-26 02:42:32.273  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[Thread-57,5,main], id: 57
10-26 02:42:32.273  5627  5674 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
10-26 02:42:32.273  5627  5674 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
10-26 02:42:32.273  4606  4671 D BtGatt.ScanManager: handling starting scan
10-26 02:42:32.274  4606  4671 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@582acd5
10-26 02:42:32.275  5627  5674 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
10-26 02:42:32.275  5627  5674 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
10-26 02:42:32.275  5627  5674 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
10-26 02:42:32.275  5627  5674 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
10-26 02:42:32.275  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[Thread-57,5,main], id: 57
10-26 02:42:32.275  5627  5674 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
10-26 02:42:32.275  5627  5627 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
10-26 02:42:32.275  5627  5674 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
10-26 02:42:32.275  5627  5674 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
10-26 02:42:32.276  5627  5674 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
10-26 02:42:32.276  5627  5674 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
10-26 02:42:32.276  5627  5674 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
10-26 02:42:32.277  5627  5674 I io.jxcore.node.ConnectionHelper: start: OK
10-26 02:42:32.281  4606  4668 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,10-26 02:42:32.281  4606  4668 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-26 02:42:32.282  4606  4671 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
10-26 02:42:32.288  4606  4668 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
10-26 02:42:32.289  4606  4668 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-26 02:42:32.289  4606  4671 D BtGatt.ScanManager: Starting BLE batch scan
10-26 02:42:32.289  4606  4671 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
10-26 02:42:32.302  4606  4668 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
10-26 02:42:32.302  4606  4668 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-26 02:42:32.308  4606  4668 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
10-26 02:42:32.308  4606  4668 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,10-26 02:42:32.778  5627  5627 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
10-26 02:42:32.778  5627  5627 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,10-26 02:42:32.779  5627  5627 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,10-26 02:42:34.123   926  2995 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,10-26 02:42:36.313   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,10-26 02:42:37.147   926  2995 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,10-26 02:42:37.281  5627  5674 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,10-26 02:42:37.281  5627  5674 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
10-26 02:42:37.282  5627  5674 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
10-26 02:42:37.282  5627  5674 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-26 02:42:37.282  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
,10-26 02:42:37.282  5627  5674 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,10-26 02:42:37.282  5627  5674 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
10-26 02:42:37.282  5627  5674 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
10-26 02:42:37.282  5627  5674 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
10-26 02:42:37.283  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
10-26 02:42:37.283  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-57,5,main], id: 57
10-26 02:42:37.284  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-57,5,main], id: 57
10-26 02:42:37.284  5627  5674 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
10-26 02:42:37.285  5627  5674 D BluetoothAdapter: STATE_ON
10-26 02:42:37.285  4606  4814 D BtGatt.GattService: stopScan() - queue size =1
,10-26 02:42:37.287  4606  4620 D BtGatt.GattService: unregisterClient() - clientIf=5
10-26 02:42:37.288  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,10-26 02:42:37.289  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-57,5,main], id: 57
10-26 02:42:37.289  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
10-26 02:42:37.289  5627  5674 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[Thread-57,5,main], id: 57
,10-26 02:42:37.289  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[Thread-57,5,main], id: 57
10-26 02:42:37.289  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
10-26 02:42:37.289  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
,10-26 02:42:37.289  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[Thread-57,5,main], id: 57
10-26 02:42:37.290  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[Thread-57,5,main], id: 57
10-26 02:42:37.290  5627  5674 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
10-26 02:42:37.290  5627  5674 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
10-26 02:42:37.293  5627  5674 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
,10-26 02:42:37.293  5627  5674 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
10-26 02:42:37.293  5627  5674 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
10-26 02:42:37.293  5627  5674 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
10-26 02:42:37.293  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[Thread-57,5,main], id: 57
10-26 02:42:37.293  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-57,5,main], id: 57
10-26 02:42:37.293  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-57,5,main], id: 57
,10-26 02:42:37.294  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
10-26 02:42:37.294  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-57,5,main], id: 57
10-26 02:42:37.294  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finishedCurrent thread: Thread[Thread-57,5,main], id: 57
,10-26 02:42:37.294  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-57,5,main], id: 57
10-26 02:42:37.294  5627  5674 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,10-26 02:42:37.294  4606  4606 D BtGatt.ScanManager: awakened up at time 85632
,10-26 02:42:37.295  5627  5674 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,10-26 02:42:37.314   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,10-26 02:42:37.342  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
10-26 02:42:37.342  5627  5674 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
,10-26 02:42:37.344  5627  5674 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
,10-26 02:42:37.344  5627  5674 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
10-26 02:42:37.344  5627  5674 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
10-26 02:42:37.345  5627  5674 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-26 02:42:37.345  5627  5674 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-26 02:42:37.345  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,10-26 02:42:37.345  5627  5674 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,10-26 02:42:37.345  5627  5674 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4962ba7 not in the list
10-26 02:42:37.345  5627  5674 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-26 02:42:37.345  5627  5674 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f67a854 not in the list
10-26 02:42:37.345  5627  5674 D io.jxcore.node.ConnectivityMonitor: stop
10-26 02:42:37.345  5627  5627 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-26 02:42:37.345  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-26 02:42:37.345  5627  5627 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-26 02:42:37.345  5627  5627 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,10-26 02:42:37.348  4606  4668 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
10-26 02:42:37.349  4606  4668 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-26 02:42:37.349  4606  4671 D BtGatt.ScanManager: stopping BLe Batch
,10-26 02:42:37.358  4606  4668 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
10-26 02:42:37.358  4606  4668 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,10-26 02:42:37.358  4606  4671 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,10-26 02:42:37.377  4606  4668 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=5
,10-26 02:42:37.377  4606  4668 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-26 02:42:37.377  4606  4668 D BtGatt.GattService: current time is 85715754208
10-26 02:42:37.378  4606  4668 D BtGatt.GattService: Batch record : [71, -122, -77, 84, 69, -12, 1, -128, -83, 75, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, -46, -4, -117, 6, 105, -37, 1, -128, -79, 7, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 116, -43, -111, -91, -20, -29, 1, -128, -75, 3, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 81, 34, 97, 112, -14, -5, 1, -128, -87, 79, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 37, -47, 14, -113, 116, -46, 1, -128, -86, 75, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
10-26 02:42:37.379  4606  4668 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
10-26 02:42:37.380  4606  4668 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
10-26 02:42:37.380  4606  4668 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
10-26 02:42:37.380  4606  4668 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
10-26 02:42:37.380  4606  4668 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,10-26 02:42:37.389  3950  5675 W CronetSyncConnectionRcs: Upload content type not set.
,10-26 02:42:37.451  4787  4837 D Finsky  : [184] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,10-26 02:42:37.452  4787  4787 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,10-26 02:42:37.455   926  3196 I ActivityManager: Killing 5292:com.android.settings/1000 (adj 15): empty #17
,10-26 02:42:37.847  5627  5627 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,10-26 02:42:38.315   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,10-26 02:42:39.316   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,10-26 02:42:40.317   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,10-26 02:42:41.318   534   534 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,10-26 02:42:42.349  5627  5674 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,10-26 02:42:42.356  5627  5674 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,10-26 02:42:42.366  5627  5674 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-26 02:42:42.366  5627  5674 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-26 02:42:42.366  5627  5674 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-26 02:42:42.366  5627  5674 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-26 02:42:42.366  5627  5674 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-26 02:42:42.366  5627  5674 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-26 02:42:42.366  5627  5674 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-26 02:42:42.366  5627  5674 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,10-26 02:42:42.372  5627  5674 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,10-26 02:42:42.372  5627  5674 D io.jxcore.node.ConnectivityMonitor: start: OK
10-26 02:42:42.373  5627  5674 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,10-26 02:42:42.373  5627  5674 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,10-26 02:42:42.373  5627  5674 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
10-26 02:42:42.373  5627  5674 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,10-26 02:42:42.373  5627  5674 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
10-26 02:42:42.379  5627  5627 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-26 02:42:42.384  5627  5674 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
,10-26 02:42:42.384  5627  5674 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,10-26 02:42:42.385  5627  5674 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
10-26 02:42:42.385  5627  5627 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-26 02:42:42.392  5627  5674 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,10-26 02:42:42.393  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
10-26 02:42:42.394  5627  5674 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,10-26 02:42:42.400  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-57,5,main], id: 57
,10-26 02:42:42.400  5627  5674 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
10-26 02:42:42.400  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
10-26 02:42:42.400  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
10-26 02:42:42.400  5627  5674 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,10-26 02:42:42.400  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-57,5,main], id: 57
10-26 02:42:42.401  5627  5674 D BluetoothAdapter: STATE_ON
,10-26 02:42:42.405  4606  4620 D BtGatt.GattService: registerClient() - UUID=c7d68f69-c381-4181-a83d-716162914a69
,10-26 02:42:42.406  4606  4668 D BtGatt.GattService: onClientRegistered() - UUID=c7d68f69-c381-4181-a83d-716162914a69, clientIf=5
,10-26 02:42:42.407  5627  5637 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
10-26 02:42:42.407  4606  4617 D BtGatt.GattService: start scan with filters
,10-26 02:42:42.412  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
,10-26 02:42:42.413  4606  4671 D BtGatt.ScanManager: handling starting scan
10-26 02:42:42.413  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-57,5,main], id: 57
10-26 02:42:42.413  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
10-26 02:42:42.413  5627  5674 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[Thread-57,5,main], id: 57
10-26 02:42:42.413  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[Thread-57,5,main], id: 57
10-26 02:42:42.413  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
,10-26 02:42:42.413  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
10-26 02:42:42.413  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[Thread-57,5,main], id: 57
10-26 02:42:42.414  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[Thread-57,5,main], id: 57
10-26 02:42:42.414  5627  5674 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
10-26 02:42:42.414  5627  5674 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
,10-26 02:42:42.420  5627  5674 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
,10-26 02:42:42.420  5627  5674 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
10-26 02:42:42.420  5627  5674 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
10-26 02:42:42.420  5627  5674 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
,10-26 02:42:42.420  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[Thread-57,5,main], id: 57
10-26 02:42:42.421  5627  5627 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
10-26 02:42:42.421  5627  5674 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
10-26 02:42:42.422  4606  4668 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,10-26 02:42:42.423  4606  4668 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-26 02:42:42.423  4606  4671 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
10-26 02:42:42.424  5627  5674 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
10-26 02:42:42.425  5627  5674 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
,10-26 02:42:42.430  5627  5674 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
,10-26 02:42:42.431  5627  5674 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
10-26 02:42:42.431  5627  5674 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
10-26 02:42:42.431  5627  5674 I io.jxcore.node.ConnectionHelper: start: OK
10-26 02:42:42.432  4606  4668 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
10-26 02:42:42.432  4606  4668 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-26 02:42:42.432  4606  4671 D BtGatt.ScanManager: Starting BLE batch scan
10-26 02:42:42.432  4606  4671 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,10-26 02:42:42.435  5627  5674 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,10-26 02:42:42.435  5627  5674 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,10-26 02:42:42.436  5627  5674 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
10-26 02:42:42.436  5627  5674 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
10-26 02:42:42.436  5627  5674 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-26 02:42:42.436  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
10-26 02:42:42.436  5627  5674 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,10-26 02:42:42.436  5627  5674 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
10-26 02:42:42.436  5627  5674 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
10-26 02:42:42.436  5627  5674 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
10-26 02:42:42.436  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,10-26 02:42:42.436  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-57,5,main], id: 57
10-26 02:42:42.437  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-57,5,main], id: 57
10-26 02:42:42.437  5627  5674 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
10-26 02:42:42.437  5627  5674 D BluetoothAdapter: STATE_ON
10-26 02:42:42.438  4606  4617 D BtGatt.GattService: stopScan() - queue size =1
10-26 02:42:42.439  4606  4814 D BtGatt.GattService: unregisterClient() - clientIf=5
,10-26 02:42:42.439  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
10-26 02:42:42.439  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-57,5,main], id: 57
10-26 02:42:42.439  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
10-26 02:42:42.440  5627  5674 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[Thread-57,5,main], id: 57
10-26 02:42:42.440  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[Thread-57,5,main], id: 57
10-26 02:42:42.440  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
10-26 02:42:42.440  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
,10-26 02:42:42.440  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[Thread-57,5,main], id: 57
10-26 02:42:42.440  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[Thread-57,5,main], id: 57
10-26 02:42:42.440  5627  5674 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
10-26 02:42:42.440  5627  5674 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
,10-26 02:42:42.443  5627  5674 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
10-26 02:42:42.443  5627  5674 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
10-26 02:42:42.443  5627  5674 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
10-26 02:42:42.444  5627  5674 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
10-26 02:42:42.444  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[Thread-57,5,main], id: 57
10-26 02:42:42.444  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-57,5,main], id: 57
,10-26 02:42:42.444  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-57,5,main], id: 57
10-26 02:42:42.444  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,10-26 02:42:42.444  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-57,5,main], id: 57
10-26 02:42:42.444  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finishedCurrent thread: Thread[Thread-57,5,main], id: 57
10-26 02:42:42.444  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-57,5,main], id: 57
10-26 02:42:42.444  5627  5674 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
10-26 02:42:42.444  5627  5674 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
10-26 02:42:42.445  4606  4668 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,10-26 02:42:42.445  4606  4668 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-26 02:42:42.445  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
10-26 02:42:42.445  5627  5674 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
,10-26 02:42:42.447  5627  5674 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
10-26 02:42:42.447  5627  5674 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
,10-26 02:42:42.447  5627  5674 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
10-26 02:42:42.447  5627  5674 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-26 02:42:42.447  5627  5627 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-26 02:42:42.447  5627  5674 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-26 02:42:42.447  5627  5627 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-26 02:42:42.447  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
10-26 02:42:42.447  5627  5674 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-26 02:42:42.447  5627  5627 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
10-26 02:42:42.447  5627  5674 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4962ba7 not in the list
10-26 02:42:42.447  5627  5674 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-26 02:42:42.447  5627  5674 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f67a854 not in the list
10-26 02:42:42.447  5627  5674 D io.jxcore.node.ConnectivityMonitor: stop
10-26 02:42:42.448  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-26 02:42:42.448  5627  5674 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-26 02:42:42.448  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-26 02:42:42.448  5627  5674 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
10-26 02:42:42.450  5627  5674 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
10-26 02:42:42.450  5627  5674 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
10-26 02:42:42.450  5627  5674 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
10-26 02:42:42.450  5627  5674 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-26 02:42:42.450  5627  5674 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-26 02:42:42.450  5627  5674 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-26 02:42:42.450  5627  5674 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f67a854 not in the list
10-26 02:42:42.451  5627  5674 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
10-26 02:42:42.451  4606  4668 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
10-26 02:42:42.451  4606  4668 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-26 02:42:42.453  5627  5674 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-26 02:42:42.458  5627  5674 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-26 02:42:42.458  5627  5674 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-26 02:42:42,.458  5627  5674 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-26 02:42:42.458  5627  5674 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-26 02:42:42.458  5627  5674 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-26 02:42:42.458  5627  5674 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-26 02:42:42.458  5627  5674 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-26 02:42:42.458  5627  5674 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
10-26 02:42:42.459  4606  4668 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
10-26 02:42:42.460  4606  4668 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-26 02:42:42.460  4606  4671 D BtGatt.ScanManager: stopping BLe Batch
10-26 02:42:42.460  5627  5674 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
10-26 02:42:42.461  5627  5674 D io.jxcore.node.ConnectivityMonitor: start: OK
,10-26 02:42:42.461  5627  5674 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
10-26 02:42:42.461  5627  5674 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
10-26 02:42:42.461  5627  5674 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
10-26 02:42:42.461  5627  5674 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-26 02:42:42.461  5627  5674 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,10-26 02:42:42.464  5627  5627 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-26 02:42:42.467  4606  4668 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
10-26 02:42:42.467  4606  4668 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-26 02:42:42.467  4606  4671 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
10-26 02:42:42.467  5627  5627 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-26 02:42:42.467  5627  5674 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
10-26 02:42:42.467  5627  5674 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
10-26 02:42:42.467  5627  5674 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,10-26 02:42:42.471  5627  5674 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,10-26 02:42:42.471  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
10-26 02:42:42.471  5627  5674 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
10-26 02:42:42.472  4606  4668 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
10-26 02:42:42.472  4606  4668 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,10-26 02:42:42.475  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-57,5,main], id: 57
10-26 02:42:42.475  5627  5674 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,10-26 02:42:42.475  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
10-26 02:42:42.475  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
10-26 02:42:42.475  5627  5674 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
10-26 02:42:42.475  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-57,5,main], id: 57
10-26 02:42:42.476  5627  5674 D BluetoothAdapter: STATE_ON
10-26 02:42:42.477  4606  4617 D BtGatt.GattService: registerClient() - UUID=637ef813-12e0-4d99-b64f-91330d97ee0a
10-26 02:42:42.477  4606  4668 D BtGatt.GattService: onClientRegistered() - UUID=637ef813-12e0-4d99-b64f-91330d97ee0a, clientIf=5
,10-26 02:42:42.477  5627  5637 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
10-26 02:42:42.478  4606  4814 D BtGatt.GattService: start scan with filters
,10-26 02:42:42.481  4606  4671 D BtGatt.ScanManager: handling starting scan
,10-26 02:42:42.481  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
10-26 02:42:42.481  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-57,5,main], id: 57
10-26 02:42:42.481  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,10-26 02:42:42.482  5627  5674 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[Thread-57,5,main], id: 57
10-26 02:42:42.482  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[Thread-57,5,main], id: 57
10-26 02:42:42.482  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
10-26 02:42:42.482  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
10-26 02:42:42.482  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[Thread-57,5,main], id: 57
10-26 02:42:42.482  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[Thread-57,5,main], id: 57
10-26 02:42:42.482  5627  5674 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
10-26 02:42:42.482  5627  5674 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
10-26 02:42:42.484  5627  5674 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
10-26 02:42:42.484  5627  5674 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
10-26 02:42:42.484  5627  5674 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
10-26 02:42:42.484  5627  5627 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
10-26 02:42:42.484  5627  5674 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
10-26 02:42:42.484  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[Thread-57,5,main], id: 57
10-26 02:42:42.484  5627  5674 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
10-26 02:42:42.485  4606  4668 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
10-26 02:42:42.485  5627  5674 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
10-26 02:42:42.485  4606  4668 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-26 02:42:42.486  5627  5674 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
10-26 02:42:42.486  4606  4671 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
10-26 02:42:42.487  5627  5674 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
,10-26 02:42:42.487  5627  5674 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
10-26 02:42:42.487  5627  5674 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
10-26 02:42:42.488  5627  5674 I io.jxcore.node.ConnectionHelper: start: OK
10-26 02:42:42.490  4606  4668 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
10-26 02:42:42.490  4606  4668 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-26 02:42:42.490  4606  4671 D BtGatt.ScanManager: Starting BLE batch scan
10-26 02:42:42.490  4606  4671 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,10-26 02:42:42.498  4606  4668 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
10-26 02:42:42.498  4606  4668 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,10-26 02:42:42.503  4606  4668 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
10-26 02:42:42.503  4606  4668 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,10-26 02:42:42.986  5627  5627 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
10-26 02:42:42.986  5627  5627 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,10-26 02:42:42.986  5627  5627 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,10-26 02:42:43.195   926  2995 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,10-26 02:42:46.223   926  2995 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,10-26 02:42:47.488  5627  5674 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,10-26 02:42:47.489  5627  5674 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,10-26 02:42:47.489  5627  5674 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
10-26 02:42:47.489  5627  5674 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-26 02:42:47.489  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
10-26 02:42:47.489  5627  5674 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-26 02:42:47.489  5627  5674 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
10-26 02:42:47.490  5627  5674 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
10-26 02:42:47.490  5627  5674 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
10-26 02:42:47.490  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
10-26 02:42:47.490  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-57,5,main], id: 57
10-26 02:42:47.490  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-57,5,main], id: 57
10-26 02:42:47.491  5627  5674 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
10-26 02:42:47.493  5627  5674 D BluetoothAdapter: STATE_ON
,10-26 02:42:47.495  4606  4814 D BtGatt.GattService: stopScan() - queue size =1
10-26 02:42:47.496  4606  4804 D BtGatt.GattService: unregisterClient() - clientIf=5
10-26 02:42:47.497  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
10-26 02:42:47.497  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-57,5,main], id: 57
10-26 02:42:47.498  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
10-26 02:42:47.498  5627  5674 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[Thread-57,5,main], id: 57
10-26 02:42:47.498  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[Thread-57,5,main], id: 57
10-26 02:42:47.498  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
10-26 02:42:47.498  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
,10-26 02:42:47.499  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[Thread-57,5,main], id: 57
10-26 02:42:47.499  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[Thread-57,5,main], id: 57
10-26 02:42:47.499  5627  5674 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
10-26 02:42:47.499  5627  5674 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
10-26 02:42:47.503  4606  4606 D BtGatt.ScanManager: awakened up at time 95841
10-26 02:42:47.503  5627  5674 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
,10-26 02:42:47.503  5627  5674 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
10-26 02:42:47.504  5627  5674 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
10-26 02:42:47.504  5627  5674 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
10-26 02:42:47.504  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[Thread-57,5,main], id: 57
10-26 02:42:47.504   926   936 I ActivityManager: Killing 4978:com.google.android.apps.maps/u0a58 (adj 15): empty #17
10-26 02:42:47.504  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-57,5,main], id: 57
,10-26 02:42:47.504  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-57,5,main], id: 57
10-26 02:42:47.505  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
10-26 02:42:47.505  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-57,5,main], id: 57
10-26 02:42:47.505  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finishedCurrent thread: Thread[Thread-57,5,main], id: 57
10-26 02:42:47.505  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-57,5,main], id: 57
,10-26 02:42:47.506  5627  5674 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
10-26 02:42:47.506  5627  5674 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,10-26 02:42:47.532  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,10-26 02:42:47.532  5627  5674 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
,10-26 02:42:47.533  4606  4668 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
,10-26 02:42:47.533  4606  4668 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-26 02:42:47.533  4606  4671 D BtGatt.ScanManager: stopping BLe Batch
10-26 02:42:47.534  5627  5674 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
10-26 02:42:47.534  5627  5674 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
10-26 02:42:47.534  5627  5674 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
10-26 02:42:47.534  5627  5627 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-26 02:42:47.534  5627  5627 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-26 02:42:47.534  5627  5627 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,10-26 02:42:47.539  4606  4668 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,10-26 02:42:47.539  4606  4668 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-26 02:42:47.539  4606  4671 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,10-26 02:42:47.554  4606  4668 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=6
10-26 02:42:47.554  4606  4668 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-26 02:42:47.554  4606  4668 D BtGatt.GattService: current time is 95892637394
,10-26 02:42:47.555  4606  4668 D BtGatt.GattService: Batch record : [71, -122, -77, 84, 69, -12, 1, -128, -75, 5, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, -46, -4, -117, 6, 105, -37, 1, -128, -79, 11, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 116, -43, -111, -91, -20, -29, 1, -128, -75, 8, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 81, 34, 97, 112, -14, -5, 1, -128, -94, 3, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 37, -47, 14, -113, 116, -46, 1, -128, -86, 78, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 35, 97, 126, -92, 22, -56, 1, -128, -77, 72, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
10-26 02:42:47.555  4606  4668 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
10-26 02:42:47.555  4606  4668 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
,10-26 02:42:47.555  4606  4668 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
10-26 02:42:47.556  4606  4668 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
10-26 02:42:47.556  4606  4668 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,10-26 02:42:47.556  4606  4668 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,10-26 02:42:48.035  5627  5627 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,10-26 02:42:48.036  5627  5627 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-26 02:42:48.036  5627  5627 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,10-26 02:42:52.535  5627  5674 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,10-26 02:42:52.536  5627  5674 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,10-26 02:42:52.536  5627  5674 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,10-26 02:42:52.536  5627  5674 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,10-26 02:42:52.536  5627  5674 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,10-26 02:42:52.537  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,10-26 02:42:52.537  5627  5674 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,10-26 02:42:52.537  5627  5674 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4962ba7 not in the list
,10-26 02:42:52.537  5627  5674 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-26 02:42:52.537  5627  5674 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f67a854 not in the list
10-26 02:42:52.537  5627  5674 D io.jxcore.node.ConnectivityMonitor: stop
,10-26 02:42:52.537  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-26 02:42:52.539  5627  5674 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-26 02:42:52.540  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-26 02:42:52.541  5627  5674 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
10-26 02:42:52.544  5627  5674 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
,10-26 02:42:52.544  5627  5674 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
10-26 02:42:52.544  5627  5674 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
10-26 02:42:52.544  5627  5674 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-26 02:42:52.544  5627  5674 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-26 02:42:52.544  5627  5674 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,10-26 02:42:52.545  5627  5674 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f67a854 not in the list
10-26 02:42:52.546  5627  5674 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
10-26 02:42:52.548  5627  5674 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-26 02:42:52.548  5627  5674 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-26 02:42:52.548  5627  5674 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-26 02:42:52.548  5627  5674 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,10-26 02:42:52.549  5627  5674 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-26 02:42:52.549  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-26 02:42:52.549  5627  5674 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-26 02:42:52.549  5627  5674 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4962ba7 not in the list
10-26 02:42:52.549  5627  5674 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-26 02:42:52.549  5627  5674 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f67a854 not in the list
,10-26 02:42:52.549  5627  5674 D io.jxcore.node.ConnectivityMonitor: stop
10-26 02:42:52.550  5627  5674 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-26 02:42:52.550  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-26 02:42:52.550  5627  5674 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-26 02:42:52.550  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-26 02:42:52.550  5627  5674 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
10-26 02:42:52.553  5627  5674 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
,10-26 02:42:52.553  5627  5674 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
10-26 02:42:52.553  5627  5674 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
10-26 02:42:52.553  5627  5674 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-26 02:42:52.553  5627  5674 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-26 02:42:52.553  5627  5674 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-26 02:42:52.554  5627  5674 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f67a854 not in the list
,10-26 02:42:52.555  5627  5674 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
10-26 02:42:52.556  5627  5674 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-26 02:42:52.556  5627  5674 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-26 02:42:52.556  5627  5674 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-26 02:42:52.556  5627  5674 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,10-26 02:42:52.556  5627  5674 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-26 02:42:52.556  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-26 02:42:52.556  5627  5674 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-26 02:42:52.556  5627  5674 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4962ba7 not in the list
10-26 02:42:52.557  5627  5674 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-26 02:42:52.557  5627  5674 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f67a854 not in the list
10-26 02:42:52.557  5627  5674 D io.jxcore.node.ConnectivityMonitor: stop
,10-26 02:42:52.557  5627  5674 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-26 02:42:52.557  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-26 02:42:52.557  5627  5674 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-26 02:42:52.557  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-26 02:42:52.557  5627  5674 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
10-26 02:42:52.559  5627  5674 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
10-26 02:42:52.560  5627  5674 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
,10-26 02:42:52.560  5627  5674 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
10-26 02:42:52.560  5627  5674 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-26 02:42:52.560  5627  5674 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-26 02:42:52.560  5627  5674 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-26 02:42:52.560  5627  5674 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f67a854 not in the list
10-26 02:42:52.561  5627  5674 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
,10-26 02:42:52.562  5627  5674 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-26 02:42:52.562  5627  5674 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-26 02:42:52.562  5627  5674 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-26 02:42:52.562  5627  5674 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-26 02:42:52.562  5627  5674 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-26 02:42:52.562  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-26 02:42:52.562  5627  5674 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-26 02:42:52.562  5627  5674 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4962ba7 not in the list
10-26 02:42:52.563  5627  5674 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-26 02:42:52.563  5627  5674 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f67a854 not in the list
10-26 02:42:52.563  5627  5674 D io.jxcore.node.ConnectivityMonitor: stop
10-26 02:42:52.563  5627  5674 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,10-26 02:42:52.563  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-26 02:42:52.563  5627  5674 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-26 02:42:52.563  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-26 02:42:52.563  5627  5674 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
,10-26 02:42:52.566  5627  5674 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
10-26 02:42:52.566  5627  5674 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
,10-26 02:42:52.566  5627  5674 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
10-26 02:42:52.566  5627  5674 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-26 02:42:52.566  5627  5674 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-26 02:42:52.567  5627  5674 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,10-26 02:42:52.567  5627  5674 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f67a854 not in the list
10-26 02:42:52.568  5627  5674 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
10-26 02:42:52.568  5627  5674 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-26 02:42:52.568  5627  5674 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-26 02:42:52.568  5627  5674 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-26 02:42:52.569  5627  5674 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-26 02:42:52.569  5627  5674 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,10-26 02:42:52.569  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-26 02:42:52.569  5627  5674 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-26 02:42:52.569  5627  5674 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4962ba7 not in the list
10-26 02:42:52.569  5627  5674 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-26 02:42:52.569  5627  5674 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f67a854 not in the list
10-26 02:42:52.569  5627  5674 D io.jxcore.node.ConnectivityMonitor: stop
10-26 02:42:52.569  5627  5674 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-26 02:42:52.569  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-26 02:42:52.569  5627  5674 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-26 02:42:52.570  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-26 02:42:52.570  5627  5674 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
10-26 02:42:52.572  5627  5674 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
10-26 02:42:52.573  5627  5674 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
10-26 02:42:52.573  5627  5674 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
10-26 02:42:52.573  5627  5674 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,10-26 02:42:52.573  5627  5674 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-26 02:42:52.573  5627  5674 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,10-26 02:42:52.573  5627  5674 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f67a854 not in the list
10-26 02:42:52.574  5627  5674 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
10-26 02:42:52.575  5627  5674 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
10-26 02:42:52.575  5627  5674 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
10-26 02:42:52.575  5627  5674 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
10-26 02:42:52.576  5627  5674 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
10-26 02:42:52.576  5627  5674 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
10-26 02:42:52.576  5627  5674 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,10-26 02:42:52.576  5627  5674 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
10-26 02:42:52.576  5627  5674 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
10-26 02:42:52.576  5627  5674 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-26 02:42:52.576  5627  5674 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-26 02:42:52.577  5627  5674 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-26 02:42:52.577  5627  5674 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,10-26 02:42:52.577  5627  5674 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-26 02:42:52.577  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-26 02:42:52.577  5627  5674 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-26 02:42:52.577  5627  5674 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4962ba7 not in the list
10-26 02:42:52.577  5627  5674 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,10-26 02:42:52.577  5627  5674 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f67a854 not in the list
10-26 02:42:52.577  5627  5674 D io.jxcore.node.ConnectivityMonitor: stop
10-26 02:42:52.578  5627  5674 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-26 02:42:52.578  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-26 02:42:52.579  5627  5674 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,10-26 02:42:52.579  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-26 02:42:52.579  5627  5674 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
10-26 02:42:52.584  5627  5674 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
10-26 02:42:52.584  5627  5674 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
10-26 02:42:52.584  5627  5674 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
,10-26 02:42:52.584  5627  5674 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-26 02:42:52.584  5627  5674 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-26 02:42:52.585  5627  5674 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-26 02:42:52.585  5627  5674 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f67a854 not in the list
10-26 02:42:52.586  5627  5674 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,10-26 02:42:52.587  5627  5674 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
10-26 02:42:52.587  5627  5674 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,10-26 02:42:52.593  5627  5674 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,10-26 02:42:52.594  5627  5674 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
10-26 02:42:52.594  5627  5674 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
10-26 02:42:52.594  5627  5674 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
10-26 02:42:52.594  5627  5674 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
10-26 02:42:52.594  5627  5674 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
10-26 02:42:52.594  5627  5674 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
10-26 02:42:52.594  5627  5674 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
10-26 02:42:52.594  5627  5674 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
10-26 02:42:52.594  5627  5674 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
10-26 02:42:52.594  5627  5674 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
,10-26 02:42:52.594  5627  5674 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
10-26 02:42:52.594  5627  5674 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
10-26 02:42:52.595  5627  5674 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
10-26 02:42:52.595  5627  5674 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
10-26 02:42:52.595  5627  5674 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
10-26 02:42:52.595  5627  5674 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
,10-26 02:42:52.595  5627  5674 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
10-26 02:42:52.595  5627  5674 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
10-26 02:42:52.595  5627  5674 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
10-26 02:42:52.595  5627  5674 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
10-26 02:42:52.595  5627  5674 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
10-26 02:42:52.595  5627  5674 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
10-26 02:42:52.595  5627  5674 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
10-26 02:42:52.595  5627  5674 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
,10-26 02:42:52.595  5627  5674 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
10-26 02:42:52.595  5627  5674 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
10-26 02:42:52.595  5627  5674 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
10-26 02:42:52.596  5627  5674 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
10-26 02:42:52.596  5627  5674 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
10-26 02:42:52.596  5627  5674 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
10-26 02:42:52.596  5627  5674 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
10-26 02:42:52.596  5627  5674 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
,10-26 02:42:52.596  5627  5674 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
,10-26 02:42:52.597  5627  5674 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
10-26 02:42:52.597  5627  5674 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
10-26 02:42:52.597  5627  5674 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
10-26 02:42:52.597  5627  5674 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
10-26 02:42:52.597  5627  5674 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
10-26 02:42:52.597  5627  5674 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
10-26 02:42:52.597  5627  5674 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
,10-26 02:42:52.602  5627  5674 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
,10-26 02:42:52.603  5627  5674 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
10-26 02:42:52.603  5627  5674 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
10-26 02:42:52.604  5627  5674 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
10-26 02:42:52.604  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
10-26 02:42:52.604  5627  5674 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
10-26 02:42:52.604  5627  5674 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
10-26 02:42:52.605  5627  5674 E io.jxcore.node.ConnectionHelper: connect: Callback is null
,10-26 02:42:52.605  5627  5679 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 121)
10-26 02:42:52.605  5627  5679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: tryToConnect:  socketConnectSucceeded = false, mIsShuttingDown = false
10-26 02:42:52.605  5627  5679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: socket closed
10-26 02:42:52.605  5627  5679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: SYSTEM_DECIDED_INSECURE_RFCOMM_SOCKET_PORT
,10-26 02:42:52.606  5627  5674 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-26 02:42:52.606  5627  5674 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-26 02:42:52.606  5627  5674 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-26 02:42:52.606  5627  5674 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-26 02:42:52.606  5627  5674 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-26 02:42:52.606  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-26 02:42:52.606  5627  5674 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,10-26 02:42:52.607  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
10-26 02:42:52.608  5627  5674 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4962ba7 not in the list
10-26 02:42:52.608  5627  5674 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,10-26 02:42:52.608  5627  5674 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f67a854 not in the list
10-26 02:42:52.608  5627  5674 D io.jxcore.node.ConnectivityMonitor: stop
10-26 02:42:52.608  5627  5674 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-26 02:42:52.608  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-26 02:42:52.608  5627  5674 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-26 02:42:52.608  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-26 02:42:52.608  5627  5674 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
10-26 02:42:52.609  5627  5679 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: connecting
10-26 02:42:52.609  5627  5679 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
10-26 02:42:52.609  5627  5680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 121
10-26 02:42:52.609  5627  5680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Trying to close the Bluetooth socket... (thread ID: 121)
10-26 02:42:52.609  5627  5680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Bluetooth socket closed (thread ID: 121)
,10-26 02:42:52.610  5627  5674 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
10-26 02:42:52.610  5627  5674 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
10-26 02:42:52.610  5627  5674 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
10-26 02:42:52.610  5627  5674 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-26 02:42:52.610  5627  5674 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-26 02:42:52.610  5627  5674 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-26 02:42:52.611  5627  5674 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f67a854 not in the list
10-26 02:42:52.611  5627  5674 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
10-26 02:42:52.610  4620  4620 W Binder_2: type=1400 audit(0.0:113): avc: denied { ioctl } for path="socket:[30533]" dev="sockfs" ino=30533 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
10-26 02:42:52.613  5627  5679 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: connect, socket closed
10-26 02:42:52.613  5627  5674 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-26 02:42:52.613  5627  5679 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: socketConnectSucceeded false
10-26 02:42:52.613  5627  5674 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-26 02:42:52.613  5627  5674 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-26 02:42:52.613  5627  5679 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 121)
10-26 02:42:52.613  5627  5674 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-26 02:42:52.613  5627  5674 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-26 02:42:52.613  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-26 02:42:52.613  5627  5674 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,10-26 02:42:52.613  5627  5674 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4962ba7 not in the list
10-26 02:42:52.613  5627  5674 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-26 02:42:52.613  5627  5674 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f67a854 not in the list
10-26 02:42:52.613  5627  5674 D io.jxcore.node.ConnectivityMonitor: stop
10-26 02:42:52.614  5627  5674 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-26 02:42:52.614  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-26 02:42:52.614  5627  5674 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-26 02:42:52.614  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-26 02:42:52.614  5627  5674 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
,10-26 02:42:52.610  4620  4620 W Binder_2: type=1400 audit(0.0:114): avc: denied { ioctl } for path="socket:[30533]" dev="sockfs" ino=30533 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,10-26 02:42:52.617  5627  5674 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
10-26 02:42:52.617  5627  5674 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
10-26 02:42:52.617  5627  5674 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
,10-26 02:42:52.617  5627  5674 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-26 02:42:52.617  5627  5674 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-26 02:42:52.617  5627  5674 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-26 02:42:52.617  5627  5674 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f67a854 not in the list
10-26 02:42:52.618  5627  5674 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
10-26 02:42:52.618  5627  5674 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-26 02:42:52.618  5627  5674 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-26 02:42:52.618  5627  5674 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-26 02:42:52.618  5627  5674 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-26 02:42:52.618  5627  5674 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,10-26 02:42:52.618  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-26 02:42:52.619  5627  5674 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-26 02:42:52.619  5627  5674 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4962ba7 not in the list
10-26 02:42:52.619  5627  5674 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-26 02:42:52.619  5627  5674 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f67a854 not in the list
10-26 02:42:52.619  5627  5674 D io.jxcore.node.ConnectivityMonitor: stop
10-26 02:42:52.619  5627  5674 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-26 02:42:52.619  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-26 02:42:52.619  5627  5674 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-26 02:42:52.619  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-26 02:42:52.619  5627  5674 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
10-26 02:42:52.621  5627  5674 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
,10-26 02:42:52.622  5627  5674 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
10-26 02:42:52.622  5627  5674 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
10-26 02:42:52.622  5627  5674 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-26 02:42:52.622  5627  5674 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-26 02:42:52.622  5627  5674 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-26 02:42:52.622  5627  5674 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f67a854 not in the list
10-26 02:42:52.623  5627  5674 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
10-26 02:42:52.623  5627  5674 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
10-26 02:42:52.623  5627  5674 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
,10-26 02:42:52.623  5627  5674 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
10-26 02:42:52.623  5627  5674 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
10-26 02:42:52.623  5627  5674 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
10-26 02:42:52.623  5627  5674 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
10-26 02:42:52.623  5627  5674 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
10-26 02:42:52.623  5627  5674 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
10-26 02:42:52.623  5627  5674 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
10-26 02:42:52.623  5627  5674 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
10-26 02:42:52.623  5627  5674 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
10-26 02:42:52.623  5627  5674 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-26 02:42:52.624  5627  5674 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,10-26 02:42:52.624  5627  5674 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-26 02:42:52.624  5627  5674 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-26 02:42:52.624  5627  5674 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-26 02:42:52.624  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-26 02:42:52.624  5627  5674 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-26 02:42:52.624  5627  5674 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4962ba7 not in the list
10-26 02:42:52.624  5627  5674 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-26 02:42:52.624  5627  5674 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f67a854 not in the list
10-26 02:42:52.624  5627  5674 D io.jxcore.node.ConnectivityMonitor: stop
10-26 02:42:52.624  5627  5674 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-26 02:42:52.624  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-26 02:42:52.624  5627  5674 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,10-26 02:42:52.624  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-26 02:42:52.624  5627  5674 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
10-26 02:42:52.626  5627  5674 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
10-26 02:42:52.626  5627  5674 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
10-26 02:42:52.626  5627  5674 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
10-26 02:42:52.626  5627  5674 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-26 02:42:52.626  5627  5674 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-26 02:42:52.626  5627  5674 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-26 02:42:52.626  5627  5674 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f67a854 not in the list
10-26 02:42:52.627  5627  5674 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-26 02:42:52.627  5627  5674 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,10-26 02:42:52.627  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-26 02:42:52.627  5627  5674 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-26 02:42:52.627  5627  5674 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4962ba7 not in the list
10-26 02:42:52.627  5627  5674 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-26 02:42:52.627  5627  5674 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f67a854 not in the list
10-26 02:42:52.627  5627  5674 D io.jxcore.node.ConnectivityMonitor: stop
10-26 02:42:52.627  5627  5674 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-26 02:42:52.627  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-26 02:42:57.628  5627  5674 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,10-26 02:42:57.628  5627  5674 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f67a854 not in the list
10-26 02:42:57.629  5627  5674 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-26 02:42:57.629  5627  5674 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-26 02:42:57.629  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-26 02:42:57.629  5627  5674 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-26 02:42:57.629  5627  5674 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4962ba7 not in the list
10-26 02:42:57.630  5627  5674 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-26 02:42:57.630  5627  5674 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,10-26 02:42:57.630  5627  5674 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-26 02:42:57.630  5627  5674 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-26 02:42:57.630  5627  5674 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-26 02:42:57.631  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-26 02:42:57.631  5627  5674 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,10-26 02:42:57.631  5627  5674 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4962ba7 not in the list
10-26 02:42:57.631  5627  5674 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-26 02:42:57.631  5627  5674 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f67a854 not in the list
10-26 02:42:57.631  5627  5674 D io.jxcore.node.ConnectivityMonitor: stop
,10-26 02:42:57.632  5627  5674 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-26 02:42:57.632  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-26 02:42:57.632  5627  5674 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-26 02:42:57.632  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-26 02:42:57.632  5627  5674 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
,10-26 02:42:57.637  5627  5674 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
,10-26 02:42:57.638  5627  5674 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
10-26 02:42:57.638  5627  5674 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
10-26 02:42:57.638  5627  5674 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,10-26 02:42:57.639  5627  5674 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-26 02:42:57.639  5627  5674 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,10-26 02:42:57.639  5627  5674 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f67a854 not in the list
,10-26 02:42:57.645  5627  5674 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
,10-26 02:42:57.645  5627  5674 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-26 02:42:57.648  5627  5674 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,10-26 02:42:57.651  5627  5674 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
10-26 02:42:57.652  5627  5674 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
10-26 02:42:57.652  5627  5674 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
10-26 02:42:57.652  5627  5681 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
10-26 02:42:57.653  5627  5674 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
10-26 02:42:57.653  5627  5674 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,10-26 02:42:57.653  5627  5627 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
10-26 02:42:57.653  5627  5674 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-26 02:42:57.654  5627  5674 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
10-26 02:42:57.654  5627  5674 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
10-26 02:42:57.654  5627  5681 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
10-26 02:42:57.654  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
10-26 02:42:57.654  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-26 02:42:57.654  5627  5674 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
10-26 02:42:57.654  5627  5674 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
10-26 02:42:57.654  5627  5674 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4962ba7 not in the list
10-26 02:42:57.654  5627  5674 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,10-26 02:42:57.654  5627  5674 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
10-26 02:42:57.654  5627  5674 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,10-26 02:42:57.654  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
10-26 02:42:57.655  5627  5674 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-26 02:42:57.655  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-26 02:42:57.655  5627  5627 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
10-26 02:42:57.655  5627  5674 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
10-26 02:42:57.657  5627  5674 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
10-26 02:42:57.657  4814  4814 W Binder_4: type=1400 audit(0.0:115): avc: denied { ioctl } for path="socket:[30538]" dev="sockfs" ino=30538 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
10-26 02:42:57.657  4814  4814 W Binder_4: type=1400 audit(0.0:116): avc: denied { ioctl } for path="socket:[30538]" dev="sockfs" ino=30538 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,10-26 02:42:57.657  5627  5674 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
10-26 02:42:57.657  5627  5674 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
10-26 02:42:57.657  5627  5674 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
10-26 02:42:57.657  5627  5674 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f67a854 not in the list
10-26 02:42:57.658  5627  5627 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-26 02:42:57.658  5627  5674 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-26 02:42:57.658  5627  5627 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,10-26 02:42:57.658  5627  5674 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-26 02:42:57.658  5627  5627 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
10-26 02:42:57.658  5627  5674 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-26 02:42:57.658  5627  5674 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-26 02:42:57.658  5627  5674 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-26 02:42:57.658  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-26 02:42:57.658  5627  5674 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
10-26 02:42:57.658  5627  5674 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4962ba7 not in the list
10-26 02:42:57.658  5627  5674 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-26 02:42:57.658  5627  5674 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f67a854 not in the list
,10-26 02:42:57.658  5627  5674 D io.jxcore.node.ConnectivityMonitor: stop
10-26 02:42:57.658  5627  5674 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-26 02:42:57.658  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-26 02:42:57.659  5627  5674 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-26 02:42:57.659  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-26 02:42:57.659  5627  5674 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
10-26 02:42:57.660  5627  5681 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
10-26 02:42:57.660  5627  5681 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
10-26 02:42:57.660  5627  5681 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
10-26 02:42:57.660  5627  5674 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
10-26 02:42:57.660  5627  5627 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
10-26 02:42:57.660  5627  5674 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
10-26 02:42:57.660  5627  5674 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
10-26 02:42:57.660  5627  5627 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-26 02:42:57.661  5627  5674 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,10-26 02:42:57.661  5627  5674 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-26 02:42:57.661  5627  5674 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-26 02:42:57.661  5627  5674 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f67a854 not in the list
10-26 02:42:57.662  5627  5674 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
10-26 02:42:57.663  5627  5674 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
10-26 02:42:57.663  5627  5674 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
10-26 02:42:57.663  5627  5674 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
10-26 02:42:57.663  5627  5674 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
10-26 02:42:57.663  5627  5674 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-26 02:42:57.663  5627  5674 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-26 02:42:57.663  5627  5674 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,10-26 02:42:57.663  5627  5674 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-26 02:42:57.663  5627  5674 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-26 02:42:57.663  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-26 02:42:57.664  5627  5674 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-26 02:42:57.664  5627  5674 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4962ba7 not in the list
10-26 02:42:57.664  5627  5674 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-26 02:42:57.664  5627  5674 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f67a854 not in the list
10-26 02:42:57.664  5627  5674 D io.jxcore.node.ConnectivityMonitor: stop
10-26 02:42:57.665  5627  5674 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-26 02:42:57.665  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-26 02:42:57.665  5627  5674 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-26 02:42:57.665  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-26 02:42:57.665  5627  5674 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
10-26 02:42:57.667  5627  5674 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
,10-26 02:42:57.667  5627  5674 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
10-26 02:42:57.667  5627  5674 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
10-26 02:42:57.667  5627  5674 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-26 02:42:57.667  5627  5674 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-26 02:42:57.667  5627  5674 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-26 02:42:57.667  5627  5674 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f67a854 not in the list
,10-26 02:42:57.671  5627  5674 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,10-26 02:42:57.672  5627  5674 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-26 02:42:57.672  5627  5674 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,10-26 02:42:57.672  5627  5674 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-26 02:42:57.672  5627  5674 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-26 02:42:57.672  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-26 02:42:57.672  5627  5674 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-26 02:42:57.672  5627  5674 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4962ba7 not in the list
10-26 02:42:57.672  5627  5674 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-26 02:42:57.672  5627  5674 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f67a854 not in the list
10-26 02:42:57.672  5627  5674 D io.jxcore.node.ConnectivityMonitor: stop
,10-26 02:42:57.672  5627  5674 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-26 02:42:57.672  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-26 02:42:57.673  5627  5674 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-26 02:42:57.673  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-26 02:42:57.673  5627  5674 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
,10-26 02:42:57.675  5627  5674 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
,10-26 02:42:57.675  5627  5674 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
10-26 02:42:57.675  5627  5674 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
10-26 02:42:57.675  5627  5674 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-26 02:42:57.675  5627  5674 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,10-26 02:42:57.675  5627  5674 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-26 02:42:57.675  5627  5674 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f67a854 not in the list
10-26 02:42:57.676  5627  5674 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-26 02:42:57.676  5627  5674 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-26 02:42:57.676  5627  5674 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-26 02:42:57.676  5627  5674 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-26 02:42:57.676  5627  5674 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,10-26 02:42:57.676  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-26 02:42:57.677  5627  5674 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-26 02:42:57.677  5627  5674 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4962ba7 not in the list
10-26 02:42:57.677  5627  5674 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-26 02:42:57.677  5627  5674 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f67a854 not in the list
10-26 02:42:57.677  5627  5674 D io.jxcore.node.ConnectivityMonitor: stop
10-26 02:42:57.677  5627  5674 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-26 02:42:57.677  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-26 02:42:57.677  5627  5674 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-26 02:42:57.677  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-26 02:42:57.677  5627  5674 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
10-26 02:42:57.679  5627  5674 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
10-26 02:42:57.679  5627  5674 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
10-26 02:42:57.679  5627  5674 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
10-26 02:42:57.679  5627  5674 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,10-26 02:42:57.679  5627  5674 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,10-26 02:42:57.679  5627  5674 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-26 02:42:57.679  5627  5674 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f67a854 not in the list
10-26 02:42:57.680  5627  5674 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
10-26 02:42:57.680  5627  5674 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
10-26 02:42:57.681  5627  5674 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
10-26 02:42:57.681  5627  5674 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
,10-26 02:42:57.681  5627  5674 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
10-26 02:42:57.681  5627  5674 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
10-26 02:42:57.683  5627  5674 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
10-26 02:42:57.683  5627  5674 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
10-26 02:42:57.683  5627  5674 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
10-26 02:42:57.684  5627  5674 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
10-26 02:42:57.684  5627  5674 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
10-26 02:42:57.684  5627  5674 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
,10-26 02:42:57.684  5627  5674 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
10-26 02:42:57.684  5627  5674 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
10-26 02:42:57.684  5627  5674 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
10-26 02:42:57.684  5627  5674 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
10-26 02:42:57.684  5627  5674 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
10-26 02:42:57.685  5627  5674 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
10-26 02:42:57.685  5627  5674 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
10-26 02:42:57.685  5627  5674 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
,10-26 02:42:57.685  5627  5674 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-26 02:42:57.685  5627  5674 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@55a7b16 added. We now have 3 listener(s)
10-26 02:42:57.686  5627  5674 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
10-26 02:42:57.687  5627  5674 D BluetoothAdapter: enable(): BT is already enabled..!
10-26 02:42:57.687   926   937 D WifiService: setWifiEnabled: true pid=5627, uid=10077
10-26 02:42:57.687   926   937 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,10-26 02:42:57.739  4606  4799 W bt_sdp  : SDP - Rcvd conn cnf with error: 0x4  CID 0x40
,10-26 02:42:57.739  4606  4801 E bt_btif_sock_rfcomm: find_rfc_slot_by_id unable to find RFCOMM slot id: 5
,10-26 02:42:58.159  5627  5627 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,10-26 02:43:02.693  5627  5674 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,10-26 02:43:02.693  5627  5674 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@20b4c97 added. We now have 4 listener(s)
10-26 02:43:02.693  5627  5674 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,10-26 02:43:02.703  5627  5674 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,10-26 02:43:02.703  5627  5674 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@20b4c97 removed from the list
,10-26 02:43:02.703  5627  5674 D io.jxcore.node.ConnectivityMonitor: stop
,10-26 02:43:02.703  5627  5674 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,10-26 02:43:02.703  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-26 02:43:02.705  5627  5674 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,10-26 02:43:02.705  5627  5674 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@3efce84 added. We now have 4 listener(s)
10-26 02:43:02.705  5627  5674 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,10-26 02:43:02.708  5627  5674 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-26 02:43:02.708  5627  5674 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@3efce84 removed from the list
10-26 02:43:02.708  5627  5674 D io.jxcore.node.ConnectivityMonitor: stop
,10-26 02:43:02.708  5627  5674 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-26 02:43:02.708  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-26 02:43:02.710  5627  5674 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,10-26 02:43:02.710  5627  5674 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@c1f566d added. We now have 4 listener(s)
10-26 02:43:02.710  5627  5674 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,10-26 02:43:02.716   926  3795 D WifiService: setWifiEnabled: false pid=5627, uid=10077
10-26 02:43:02.716   926  3795 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,10-26 02:43:02.719   926  2990 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,10-26 02:43:02.720   926  2990 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
10-26 02:43:02.720   926  2990 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
10-26 02:43:02.720   926  2990 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,10-26 02:43:02.726  5627  5674 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,10-26 02:43:02.727  4606  4664 D BluetoothAdapterState: Current state: ON, message: 23
10-26 02:43:02.727  4606  4664 D BluetoothAdapterProperties: Setting state to 13
10-26 02:43:02.727  4606  4664 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,10-26 02:43:02.728  4606  4664 D BluetoothAdapterProperties: onBluetoothDisable()
,10-26 02:43:02.731  4606  4664 I BluetoothAdapterState: Entering PendingCommandState
,10-26 02:43:02.733   926  5367 D DhcpClient: Clearing IP address
,10-26 02:43:02.733   506   920 D CommandListener: Clearing all IP addresses on wlan0
10-26 02:43:02.740  5627  5674 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-26 02:43:02.740  5627  5674 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-26 02:43:02.740  5627  5674 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-26 02:43:02.740  5627  5674 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-26 02:43:02.740  5627  5674 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-26 02:43:02.740  5627  5674 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-26 02:43:02.740  5627  5674 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-26 02:43:02.740  5627  5674 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-26 02:43:02.740  5627  5674 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,10-26 02:43:02.741  4606  4606 D BluetoothMapService: onReceive
10-26 02:43:02.742  4606  4606 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
10-26 02:43:02.742  4606  4606 D BluetoothMapService: STATE_TURNING_OFF
10-26 02:43:02.742  5627  5674 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-26 02:43:02.742  5627  5674 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
10-26 02:43:02.742  4606  4606 D BluetoothMapService: MAP Service closeService in
10-26 02:43:02.742  4606  4606 D BluetoothMapMasInstance0: MAP Service shutdown
10-26 02:43:02.742  5627  5674 D io.jxcore.node.ConnectivityMonitor: start: OK
10-26 02:43:02.742  4606  4606 D ObexServerSockets0: shutdown(block = true)
10-26 02:43:02.744   506   920 D CommandListener: Setting iface cfg
10-26 02:43:02.746  4606  4606 D ObexServerSockets0: shutdown called from another thread - interrupt().
10-26 02:43:02.746  4606  4816 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 5
10-26 02:43:02.746  5627  5627 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-26 02:43:02.746  4606  4606 D ObexServerSockets0: shutdown called from another thread - interrupt().
10-26 02:43:02.746  4606  4817 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
10-26 02:43:02.747  4606  4801 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
10-26 02:43:02.749  5627  5627 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-26 02:43:02.749  4606  4606 I BtOppRfcommListener: stopping Accept Thread
10-26 02:43:02.750  4606  5313 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
10-26 02:43:02.751  4606  5313 I BtOppRfcommListener: BluetoothSocket listen thread finished
10-26 02:43:02.753  5627  5627 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-26 02:43:02.753  5627  5627 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-26 02:43:02.753  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-26 02:43:02.753  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-26 02:43:02.753  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-26 02:43:02.753  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-26 02:43:02.753  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-26 02:43:02.753  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-26 02:43:02.753  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
10-26 02:43:02.754  5627  5627 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-26 02:43:02.754  5627  5627 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
10-26 02:43:02.755  3545  5418 V NativeCrypto: Read error: ssl=0x7f7aaf9000: I/O error during system call, Connection timed out
10-26 02:43:02.757   926   939 I ActivityManager: Start proc 5685:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
10-26 02:43:02.757  3545  5418 V NativeCrypto: SSL shutdown failed: ssl=0x7f7aaf9000: I/O error during system call, Broken pipe
10-26 02:43:02.758  4606  4668 D BluetoothAdapterProperties: Scan Mode:20
10-26 02:43:02.758  4606  4664 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
10-26 02:43:02.760  5627  5627 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-26 02:43:02.760  5627  5627 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-26 02:43:02.760  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-26 02:43:02.760  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-26 02:43:02.760  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-26 02:43:02.760  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-26 02:43:02.760  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-26 02:43:02.760  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-26 02:43:02.760  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
10-26 02:43:02.760   926  5368 D DhcpClient: Receive thread stopped
10-26 02:43:02.761  5627  5627 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-26 02:43:02.762  5627  5627 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
10-26 02:43:02.762   926  3539 D ConnectivityService: reportNetworkConnectivity(100, false) by 10012
10-26 02:43:02.763   926  5365 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Forcing reevaluation for UID 10012
10-26 02:43:02.764   926  2995 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
10-26 02:43:02.764   926  2995 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
10-26 02:43:02.765   532   532 E Parcel  : Reading a NULL string not supported here.
10-26 02:43:02.765  5627  5627 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-26 02:43:02.765  5627  5627 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-26 02:43:02.765  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-26 02:43:02.765  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-26 02:43:02.765  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-26 02:43:02.765  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-26 02:43:02.765  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-26 02:43:02.765  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-26 02:43:02.765  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
10-26 02:43:02.766   926  5365 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.gstatic.com": No address associated with hostname
10-26 02:43:02.766  5627  5627 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-26 02:43:02.766  5627  5627 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
10-26 02:43:02.766  4606  4606 D HeadsetService: Received stop request...Stopping profile...
10-26 02:43:02.768  5627  5627 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-26 02:43:02.769  5627  5627 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-26 02:43:02.769  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-26 02:43:02.769  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-26 02:43:02.769  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-26 02:43:02.769  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-26 02:43:02.769  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-26 02:43:02.769  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-26 02:43:02.769  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
10-26 02:43:02.769  4606  4606 D A2dpService: Received stop request...Stopping profile...
10-26 02:43:02.769  3128  3143 D BluetoothHeadset: Proxy object disconnected
10-26 02:43:02.769  3128  3128 D HeadsetProfile: Bluetooth service disconnected
10-26 02:43:02.769   926   926 D BluetoothHeadset: Proxy object disconnected
10-26 02:43:02.769   926   926 D BluetoothHeadset: Proxy object disconnected
10-26 02:43:02.769  5627  5627 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-26 02:43:02.769  5627  5627 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
10-26 02:43:02.770  3774  3799 D BluetoothHeadset: Proxy object disconnected
10-26 02:43:02.770  4606  4807 D A2dpStateMachine: Exit Disconnected: -1
10-26 02:43:02.770   926   926 D BluetoothHeadset: Proxy object disconnected
10-26 02:43:02.771  5627  5627 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-26 02:43:02.771  5627  5627 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-26 02:43:02.771  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-26 02:43:02.771  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-26 02:43:02.771  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-26 02:43:02.771  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-26 02:43:02.771  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-26 02:43:02.771  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-26 02:43:02.771  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,10-26 02:43:02.772  5627  5627 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-26 02:43:02.772  5627  5627 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
10-26 02:43:02.773   926   926 D RttService: SCAN_AVAILABLE : 1
10-26 02:43:02.774   926   926 D BluetoothA2dp: Proxy object disconnected
10-26 02:43:02.774   926  3047 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
10-26 02:43:02.774  4606  4606 D HidService: Received stop request...Stopping profile...
10-26 02:43:02.774  4606  4606 D HidService: Stopping Bluetooth HidService
10-26 02:43:02.774  3128  3128 D BluetoothA2dp: Proxy object disconnected
10-26 02:43:02.776  5627  5627 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-26 02:43:02.776  5627  5627 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-26 02:43:02.776  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-26 02:43:02.776  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-26 02:43:02.776  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-26 02:43:02.776  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-26 02:43:02.776  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-26 02:43:02.776  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-26 02:43:02.776  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
10-26 02:43:02.775  4606  4606 V BluetoothAdapterState: isTurningOff()=true
10-26 02:43:02.776  4606  4606 V BluetoothAdapterState: isTurningOn()=false
10-26 02:43:02.776   926  2995 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
10-26 02:43:02.776  4606  4606 V BluetoothAdapterState: isBleTurningOn()=false
10-26 02:43:02.776  4606  4606 V BluetoothAdapterState: isBleTurningOff()=false
10-26 02:43:02.777  3743  3865 W QCNEJ   : |CORE| network lost: 100
10-26 02:43:02.778  3743  3865 W QCNEJ   : |CORE| onLost: unbind the process to WIFI
10-26 02:43:02.778  4606  4606 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
10-26 02:43:02.779  4606  4606 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
10-26 02:43:02.779  4606  4606 V BluetoothAdapterState: isTurningOff()=true
10-26 02:43:02.779  4606  4606 V BluetoothAdapterState: isTurningOn()=false
10-26 02:43:02.779  4606  4606 V BluetoothAdapterState: isBleTurningOn()=false
10-26 02:43:02.779  4606  4668 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
10-26 02:43:02.779  4606  4606 V BluetoothAdapterState: isBleTurningOff()=false
10-26 02:43:02.779  4606  4799 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
10-26 02:43:02.779  4606  4799 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
10-26 02:43:02.779  4606  4799 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
10-26 02:43:02.779  4606  4606 D HealthService: Received stop request...Stopping profile...
10-26 02:43:02.779  4606  4668 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
10-26 02:43:02.781  4606  4799 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
10-26 02:43:02.781  4606  4606 V BluetoothAdapterState: isTurningOff()=true
10-26 02:43:02.781  4606  4606 V BluetoothAdapterState: isTurningOn()=false
10-26 02:43:02.781  4606  4606 V BluetoothAdapterState: isBleTurningOn()=false
10-26 02:43:02.781  4606  4799 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
10-26 02:43:02.781  4606  4606 V BluetoothAdapterState: isBleTurningOff()=false
10-26 02:43:02.781  4606  4668 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
10-26 02:43:02.781  4606  4799 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
10-26 02:43:02.781  4606  4799 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
10-26 02:43:02.781  4606  4799 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
10-26 02:43:02.782  4606  4799 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
10-26 02:43:02.782  4606  4606 D PanService: Received stop request...Stopping profile...
10-26 02:43:02.783  4606  4606 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
10-26 02:43:02.783  4606  4606 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
10-26 02:43:02.783  4606  4668 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
10-26 02:43:02.783  4606  4606 D BluetoothMapService: Received stop request...Stopping profile...
10-26 02:43:02.783  4606  4606 D BluetoothMapService: stop()
10-26 02:43:02.785  4606  4606 D BluetoothMapAppObserver: deinitObservers()
10-26 02:43:02.785  4606  4606 D BluetoothMapAppObserver: removeReceiver()
10-26 02:43:02.787  4606  4606 D SapService: Received stop request...Stopping profile...
10-26 02:43:02.787  4606  4606 V SapService: stop()
10-26 02:43:02.788  4606  4606 V BluetoothAdapterState: isTurningOff()=true
10-26 02:43:02.788  4606  4606 V BluetoothAdapterState: isTurningOn()=false
10-26 02:43:02.788  4606  4606 V BluetoothAdapterState: isBleTurningOn()=false
10-26 02:43:02.788  4606  4606 V BluetoothAdapterState: isBleTurningOff()=false
10-26 02:43:02.788  4606  4606 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
10-26 02:43:02.788  4606  4668 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
10-26 02:43:02.789  4606  4606 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
10-26 02:43:02.789  4606  4606 V BluetoothAdapterState: isTurningOff()=true
10-26 02:43:02.789  4606  4606 V BluetoothAdapterState: isTurningOn()=false
10-26 02:43:02.789  4606  4606 V BluetoothAdapterState: isBleTurningOn()=false
10-26 02:43:02.789  4606  4606 V BluetoothAdapterState: isBleTurningOff()=false
10-26 02:43:02.789  4606  4606 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
10-26 02:43:02.789  4606  4606 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
10-26 02:43:02.790  4606  4606 D BluetoothMapService: MAP Service closeService in
10-26 02:43:02.790  4606  4606 V BluetoothAdapterState: isTurningOff()=true
10-26 02:43:02.790  4606  4606 V BluetoothAdapterState: isTurningOn()=false
10-26 02:43:02.790  4606  4606 V BluetoothAdapterState: isBleTurningOn()=false
10-26 02:43:02.790  4606  4606 V BluetoothAdapterState: isBleTurningOff()=false
10-26 02:43:02.790  4606  4606 D BluetoothMapService: cleanup()
10-26 02:43:02.790  4606  4606 D BluetoothMapService: MAP Service closeService in
10-26 02:43:02.790  4606  4606 V BluetoothAdapterState: isTurningOff()=true
10-26 02:43:02.790  4606  4606 V BluetoothAdapterState: isTurningOn()=false
10-26 02:43:02.790  4606  4606 V BluetoothAdapterState: isBleTurningOn()=false
10-26 02:43:02.790  4606  4606 V BluetoothAdapterState: isBleTurningOff()=false
10-26 02:43:02.790  4606  4664 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
10-26 02:43:02.790  4606  4664 D BluetoothAdapterProperties: Setting state to 15
10-26 02:43:02.791  4606  4664 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
10-26 02:43:02.791  4606  4664 I BluetoothAdapterState: Entering BleOnState
10-26 02:43:02.791   926   943 D BluetoothHeadset: onBluetoothStateChange: up=false
10-26 02:43:02.791   926   943 D BluetoothHeadset: onBluetoothStateChange: up=false
10-26 02:43:02.791  3128  3143 D BluetoothMap: onBluetoothStateChange: up=false
10-26 02:43:02.792   926   943 D BluetoothHeadset: onBluetoothStateChange: up=false
10-26 02:43:02.792  3128  3988 D BluetoothHeadset: onBluetoothStateChange: up=false
10-26 02:43:02.792  3128  3146 D BluetoothInputDevice: onBluetoothStateChange: up=false
10-26 02:43:02.792   926   943 D BluetoothA2dp: onBluetoothStateChange: up=false
10-26 02:43:02.792   926  2990 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
10-26 02:43:02.793  3774  3799 D BluetoothHeadset: onBluetoothStateChange: up=false
10-26 02:43:02.793  3128  3986 D BluetoothPbap: onBluetoothStateChange: up=false
10-26 02:43:02.793  3128  3143 D BluetoothPan: onBluetoothStateChange on: false
10-26 02:43:02.794  3128  3988 D BluetoothA2dp: onBluetoothStateChange: up=false
10-26 02:43:02.795  4606  4664 D BluetoothAdapterState: Current state: BLE ON, message: 20
10-26 02:43:02.795  4606  4664 D BluetoothAdapterProperties: Setting state to 16
10-26 02:43:02.795  4606  4664 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
10-26 02:43:02.796  4606  4664 D BluetoothAdapterProperties: onBleDisable
10-26 02:43:02.796  4606  4664 I BluetoothAdapterState: Entering PendingCommandState
10-26 02:43:02.797  4606  4665 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
10-26 02:43:02.799  5627  5627 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-26 02:43:02.800  4606  4799 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
10-26 02:43:02.800  5627  5627 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-26 02:43:02.800  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-26 02:43:02.800  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-26 02:43:02.800  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-26 02:43:02.800  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-26 02:43:02.800  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-26 02:43:02.800  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-26 02:43:02.800  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-26 02:43:02.800  4606  4799 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
10-26 02:43:02.800  4606  4668 D BluetoothAdapterProperties: Scan Mode:20
10-26 02:43:02.801  5627  5627 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-26 02:43:02.801  5627  5627 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-26 02:43:02.801  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-26 02:43:02.801  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-26 02:43:02.801  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-26 02:43:02.801  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-26 02:43:02.801  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-26 02:43:02.801  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-26 02:43:02.801  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-26 02:43:02.804  5627  5627 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-26 02:43:02.804  5627  5627 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-26 02:43:02.804  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-26 02:43:02.804  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-26 02:43:02.804  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-26 02:43:02.804  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-26 02:43:02.804  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-26 02:43:02.804  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-26 02:43:02.804  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-26 02:43:02.806  5627  5627 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-26 02:43:02.807  5627  5627 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-26 02:43:02.808   506   920 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
10-26 02:43:02.808  5627  5627 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-26 02:43:02.817  5685  5685 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm64
10-26 02:43:02.823   926  2990 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
10-26 02:43:02.833  5685  5685 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
10-26 02:43:02.834   506   920 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
10-26 02:43:02.834   506   920 D CommandListener: Clearing all IP addresses on wlan0
10-26 02:43:02.835   926  2995 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
10-26 02:43:02.835   926  2995 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
10-26 02:43:02.836   926   943 D Tethering: MasterInitialState.processMessage what=3
10-26 02:43:02.838   926  2990 D DhcpClient: doQuit
10-26 02:43:02.838   926  2990 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
10-26 02:43:02.839   926  5367 D DhcpClient: onQuitting
10-26 02:43:02.839  3443  3443 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
10-26 02:43:02.839  5627  5627 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-26 02:43:02.843  5627  5627 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-26 02:43:02.843  5627  5627 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-26 02:43:02.843  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-26 02:43:02.843  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-26 02:43:02.843  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-26 02:43:02.843  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-26 02:43:02.843  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-26 02:43:02.843  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-26 02:43:02.843  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-26 02:43:02.843  3545  3545 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
10-26 02:43:02.844  5627  5627 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-26 02:43:02.844  5627  5627 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
10-26 02:43:02.847  5627  5627 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-26 02:43:02.847  5627  5627 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-26 02:43:02.847  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-26 02:43:02.847  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-26 02:43:02.847  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-26 02:43:02.847  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-26 02:43:02.847  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-26 02:43:02.847  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-26 02:43:02.847  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-26 02:43:02.847  5243  5243 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@97e1b9e and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
10-26 02:43:02.848  5627  5627 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-26 02:43:02.848  5627  5627 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,10-26 02:43:02.849  3950  3950 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
,10-26 02:43:02.851  5627  5627 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-26 02:43:02.851  4956  4977 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
10-26 02:43:02.851  5627  5627 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-26 02:43:02.851  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-26 02:43:02.851  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-26 02:43:02.851  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-26 02:43:02.851  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-26 02:43:02.851  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-26 02:43:02.851  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-26 02:43:02.851  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,10-26 02:43:02.851  4956  4977 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
10-26 02:43:02.851  4956  4977 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,0,0,0
10-26 02:43:02.851  4956  4977 E SarControlService: no key has been found,reset the power
10-26 02:43:02.851  4956  5001 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
10-26 02:43:02.851  4956  5001 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
10-26 02:43:02.851  4956  5001 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
10-26 02:43:02.852  5627  5627 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,10-26 02:43:02.852  5627  5627 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
10-26 02:43:02.852  4990  4990 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
10-26 02:43:02.852  4990  4990 D QcrilMsgTunnelSocket: [1002] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
10-26 02:43:02.853  5627  5627 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-26 02:43:02.853  4956  5001 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
10-26 02:43:02.853  4956  5001 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
,10-26 02:43:02.854  4956  5001 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
10-26 02:43:02.855  5627  5627 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-26 02:43:02.855  4990  4990 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
10-26 02:43:02.855  4990  4990 D QcrilMsgTunnelSocket: [1003] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
10-26 02:43:02.863  4990  5004 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@71683f4 HexData = [00000000ea03000000000000ffffffff]
10-26 02:43:02.864  4990  5004 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
10-26 02:43:02.864  4990  5004 D QcrilMsgTunnelSocket: [1002] < OEM_HOOK_RAW [null]
,10-26 02:43:02.864  4990  4990 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
10-26 02:43:02.864   926   936 I ActivityManager: Start proc 5704:com.google.android.apps.maps/u0a58 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
10-26 02:43:02.864  4956  4966 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
10-26 02:43:02.865   926   943 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@f5511df:true
,10-26 02:43:02.866  4990  5004 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@71683f4 HexData = [00000000eb03000000000000ffffffff]
,10-26 02:43:02.867  4990  5004 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
10-26 02:43:02.867  4990  5004 D QcrilMsgTunnelSocket: [1003] < OEM_HOOK_RAW [null]
10-26 02:43:02.867  4990  4990 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
,10-26 02:43:02.868  4956  4967 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
10-26 02:43:02.870  3443  3443 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
,10-26 02:43:02.875  3443  3443 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,10-26 02:43:02.884  5685  5685 D LocalBluetoothProfileManager: Adding local MAP profile
,10-26 02:43:02.888  5685  5685 D BluetoothMap: Create BluetoothMap proxy object
10-26 02:43:02.891   506   920 E Netd    : netlink response contains error (No such file or directory)
,10-26 02:43:02.892   926  2995 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,10-26 02:43:02.892   926  2995 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,10-26 02:43:02.897  5685  5685 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,10-26 02:43:02.907  3443  3443 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,10-26 02:43:02.909  5704  5704 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm64
,10-26 02:43:02.912  5685  5685 D DockEventReceiver: finishStartingService: stopping service
,10-26 02:43:02.919  3443  3443 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,10-26 02:43:02.921   926  3766 I ActivityManager: Killing 5243:com.google.android.music:main/u0a59 (adj 15): empty #17
,10-26 02:43:03.006  4606  4668 I bt_hci  : shut_down
,10-26 02:43:03.009  4606  4673 D bt_hwcfg: hw_epilog_process
,10-26 02:43:03.009  4606  4673 I bt_vendor: low_power_mode_cb
,10-26 02:43:03.012  4606  4673 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,10-26 02:43:03.012  4606  4673 I bt_vendor: epilog_cb
,10-26 02:43:03.012  4606  4673 I bt_hci  : epilog_finished_callback
10-26 02:43:03.014  4606  4668 I bt_hci_h4: hal_close
,10-26 02:43:03.014  4606  4668 I bt_userial_vendor: device fd = 54 close
,10-26 02:43:03.021  4302  4302 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,10-26 02:43:03.021   926  2990 D wifi    : In wifi stop Hal
10-26 02:43:03.021   926  2990 D wifi    : halHandle = 0x7f64651400, mVM = 0x7f80c4d140, mCls = 0x100a02
10-26 02:43:03.021   926  3442 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
10-26 02:43:03.022   926  3442 D WifiHAL : Got a signal to exit!!!
10-26 02:43:03.022   926  3442 I WifiHAL : Exit wifi_event_loop
10-26 02:43:03.022   926  2990 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 11
10-26 02:43:03.022   926  2990 E WifiHAL : Event processing terminated
10-26 02:43:03.022   926  2990 D wifi    : In wifi cleaned up handler
10-26 02:43:03.022   926  2990 I WifiHAL : Internal cleanup completed
10-26 02:43:03.023  4062  4197 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,10-26 02:43:03.023  5627  5627 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-26 02:43:03.025  5627  5627 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-26 02:43:03.026  5627  5627 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-26 02:43:03.045   926  3442 D wifi    : set interface wlan0 flags (DOWN)
,10-26 02:43:03.046   926  2990 D WifiNative-HAL: HAL event thread stopped successfully
,10-26 02:43:03.105   506   920 E Netd    : netlink response contains error (No such file or directory)
,10-26 02:43:03.120  4606  4665 D bt_stack_manager: event_shut_down_stack finished.
,10-26 02:43:03.120  4606  4664 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,10-26 02:43:03.120  5704  5704 D StrictMode: StrictMode policy violation; ~duration=127 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
10-26 02:43:03.120  5704  5704 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
10-26 02:43:03.120  5704  5704 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
10-26 02:43:03.120  5704  5704 D StrictMode: 	at java.io.File.doAccess(File.java:281)
10-26 02:43:03.120  5704  5704 D StrictMode: 	at java.io.File.exists(File.java:361)
10-26 02:43:03.120  5704  5704 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
10-26 02:43:03.120  5704  5704 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
10-26 02:43:03.120  5704  5704 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
10-26 02:43:03.120  5704  5704 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
10-26 02:43:03.120  5704  5704 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
10-26 02:43:03.120  5704  5704 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
10-26 02:43:03.120  5704  5704 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
10-26 02:43:03.120  5704  5704 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
10-26 02:43:03.120  5704  5704 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
10-26 02:43:03.120  5704  5704 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
10-26 02:43:03.120  5704  5704 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
10-26 02:43:03.120  5704  5704 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
10-26 02:43:03.120  5704  5704 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
10-26 02:43:03.120  5704  5704 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
10-26 02:43:03.120  5704  5704 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
10-26 02:43:03.120  5704  5704 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
10-26 02:43:03.120  5704  5704 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-26 02:43:03.120  5704  5704 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
10-26 02:43:03.120  5704  5704 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
10-26 02:43:03.120  5704  5704 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
10-26 02:43:03.120  5704  5704 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
10-26 02:43:03.120  5704  5704 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
10-26 02:43:03.120  5704  5704 D StrictMode: StrictMode policy violation; ~duration=126 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
10-26 02:43:03.120  5704  5704 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
10-26 02:43:03.120  5704  5704 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
10-26 02:43:03.120  5704  5704 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
10-26 02:43:03.120  5704  5704 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
10-26 02:43:03.120  5704  5704 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
10-26 02:43:03.120  5704  5704 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
10-26 02:43:03.120  5704  5704 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
10-26 02:43:03.120  5704  5704 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
10-26 02:43:03.120  5704  5704 D StrictMode: 	at com.google.android.apps.gmm.share,d.f.a.a(PG:48)
10-26 02:43:03.120  5704  5704 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
10-26 02:43:03.120  5704  5704 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
10-26 02:43:03.120  5704  5704 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
10-26 02:43:03.120  5704  5704 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
10-26 02:43:03.120  5704  5704 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
10-26 02:43:03.120  5704  5704 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
10-26 02:43:03.120  5704  5704 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
10-26 02:43:03.120  5704  5704 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
10-26 02:43:03.120  5704  5704 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
10-26 02:43:03.120  5704  5704 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-26 02:43:03.120  5704  5704 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
10-26 02:43:03.120  5704  5704 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
10-26 02:43:03.120  5704  5704 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
10-26 02:43:03.120  5704  5704 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
10-26 02:43:03.120  5704  5704 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
10-26 02:43:03.121  5704  5704 D StrictMode: StrictMode policy violation; ~duration=126 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
10-26 02:43:03.121  5704  5704 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
10-26 02:43:03.121  5704  5704 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
10-26 02:43:03.121  5704  5704 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
10-26 02:43:03.121  5704  5704 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
10-26 02:43:03.121  5704  5704 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
10-26 02:43:03.121  5704  5704 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
10-26 02:43:03.121  5704  5704 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
10-26 02:43:03.121  5704  5704 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
10-26 02:43:03.121  5704  5704 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
10-26 02:43:03.121  5704  5704 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
10-26 02:43:03.121  5704  5704 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
10-26 02:43:03.121  5704  5704 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
10-26 02:43:03.121  5704  5704 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
10-26 02:43:03.121  5704  5704 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
10-26 02:43:03.121  5704  5704 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
10-26 02:43:03.121  5704  5704 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
10-26 02:43:03.121  5704  5704 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
10-26 02:43:03.121  5704  5704 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
10-26 02:43:03.121  5704  5704 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-26 02:43:03.121  5704  5704 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
10-26 02:43:03.121  5704  5704 D StrictMode: 	at android.app.ActivityThread.main(,ActivityThread.java:5422)
10-26 02:43:03.121  5704  5704 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
10-26 02:43:03.121  5704  5704 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
10-26 02:43:03.121  5704  5704 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
10-26 02:43:03.121  5704  5704 D StrictMode: StrictMode policy violation; ~duration=125 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
10-26 02:43:03.121  5704  5704 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
10-26 02:43:03.121  5704  5704 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
10-26 02:43:03.121  5704  5704 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
10-26 02:43:03.121  5704  5704 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
10-26 02:43:03.121  5704  5704 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
10-26 02:43:03.121  5704  5704 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
10-26 02:43:03.121  5704  5704 D StrictMode: 	at com.google.r.k.d(PG:1187)
10-26 02:43:03.121  5704  5704 D StrictMode: 	at com.google.r.k.a(PG:2107)
10-26 02:43:03.121  5704  5704 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
10-26 02:43:03.121  5704  5704 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
10-26 02:43:03.121  5704  5704 D StrictMode: 	at com.google.r.v.a(PG:1161)
10-26 02:43:03.121  5704  5704 D StrictMode: 	at com.google.r.y.a(PG:2188)
10-26 02:43:03.121  5704  5704 D StrictMode: 	at com.google.r.e.b(PG:170)
10-26 02:43:03.121  5704  5704 D StrictMode: 	at com.google.r.e.b(PG:15188)
10-26 02:43:03.121  5704  5704 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
10-26 02:43:03.121  5704  5704 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
10-26 02:43:03.121  5704  5704 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
10-26 02:43:03.121  5704  5704 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
10-26 02:43:03.121  5704  5704 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
10-26 02:43:03.121  5704  5704 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
10-26 02:43:03.121  5704  5704 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
10-26 02:43:03.121  5704  5704 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
10-26 02:43:03.121  5704  5704 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
10-26 02:43:03.121  5704  5704 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
10-26 02:43:03.121  5704  5704 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
10-26 02:43:03.121  5704  5704 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
10-26 02:43:03.121  5704  5704 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-26 02:43:03.121  5704  5704 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
10-26 02:43:03.121  5704  5704 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
10-26 02:43:03.121  5704  5704 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
10-26 02:43:03.121  5704  5704 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
10-26 02:43:03.121  5704  5704 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
10-26 02:43:03.121  5704  5704 D StrictMode: StrictMode policy violation; ~duration=123 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
10-26 02:43:03.121  5704  5704 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
10-26 02:43:03.121  5704  5704 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
10-26 02:43:03.121  5704  5704 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
10-26 02:43:03.121  5704  5704 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
10-26 02:43:03.121  5704  5704 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
10-26 02:43:03.121  5704  5704 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
10-26 02:43:03.121  5704  5704 D StrictMode: 	at com.google.r.k.d(PG:1187)
10-26 02:43:03.121  5704  5704 D StrictMode: 	at com.google.r.k.c(PG:18147)
10-26 02:43:03.121  5704  5704 D StrictMode: 	at com.google.r.k.d(PG:583)
10-26 02:43:03.121  5704  5704 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
10-26 02:43:03.121  5704  5704 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
10-26 02:43:03.121  5704  5704 D StrictMode: 	at com.google.r.v.a(PG:1161)
10-26 02:43:03.121  5704  5704 D StrictMode: 	at com.google.r.y.a(PG:2188)
10-26 02:43:03.121  5704  5704 D StrictMode: 	at com.google.r.e.b(PG:170)
10-26 02:43:03.121  5704  5704 D StrictMode: 	at com.google.r.e.b(PG:15188)
10-26 02:43:03.121  5704  5704 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
10-26 02:43:03.121  5704  5704 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
10-26 02:43:03.121  5704  5704 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
10-26 02:43:03.121  5704  5704 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
10-26 02:43:03.121  5704  5704 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
10-26 02:43:03.121  5704  5704 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
10-26 02:43:03.121  5704  5704 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
10-26 02:43:03.121  5704  5704 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
10-26 02:43:03.121  5704  5704 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
10-26 02:43:03.121  5704  5704 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
10-26 02:43:03.121  5704  5704 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
10-26 02:43:03.121  5704  5704 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
10-26 02:43:03.121  5704  5704 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-26 02:43:03.121  5704  5704 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
10-26 02:43:03.121  5704  5704 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
10-26 02:43:03.121  5704  5704 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
10-26 02:43:03.121  5704  5704 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
10-26 02:43:03.121  5704  5704 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
10-26 02:43:03.121  5704  5704 D StrictMode: StrictMode policy violation; ~duration=87 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
10-26 02:43:03.121  5704  5704 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
10-26 02:43:03.121  5704  5704 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
10-26 02:43:03.121  5704  5704 D StrictMode: 	at java.io.File.doAccess(File.java:281)
10-26 02:43:03.121  5704  5704 D StrictMode: 	at java.io.File.exists(File.java:361)
10-26 02:43:03.121  5704  5704 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
10-26 02:43:03.121  5704  5704 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
10-26 02:43:03.121  5704  5704 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
10-26 02:43:03.121  5704  5704 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
10-26 02:43:03.121  5704  5704 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
10-26 02:43:03.121  5704  5704 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
10-26 02:43:03.121  5704  5704 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
10-26 02:43:03.121  5704  5704 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
10-26 02:43:03.121  5704  5704 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
10-26 02:43:03.121  5704  5704 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
10-26 02:43:03.121  5704  5704 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
10-26 02:43:03.121  5704  5704 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
10-26 02:43:03.121  5704  5704 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
10-26 02:43:03.121  5704  5704 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
10-26 02:43:03.121  5704  5704 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
10-26 02:43:03.121  5704  5704 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-26 02:43:03.121  5704  5704 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
10-26 02:43:03.121  5704  5704 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
10-26 02:43:03.121  5704  5704 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
10-26 02:43:03.121  5704  5704 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
10-26 02:43:03.121  5704  5704 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
10-26 02:43:03.121  5704  5704 D StrictMode: StrictMode policy violation; ~duration=87 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
10-26 02:43:03.121  5704  5704 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
10-26 02:43:03.121  5704  5704 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
10-26 02:43:03.121  5704  5704 D StrictMode: 	at java.io.File.doAccess(File.java:281)
10-26 02:43:03.121  5704  5704 D StrictMode: 	at java.io.File.exists(File.java:361)
10-26 02:43:03.121  5704  5704 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
10-26 02:43:03.121  5704  5704 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
10-26 02:43:03.121  5704  5704 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
10-26 02:43:03.121  5704  5704 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
10-26 02:43:03.121  5704  5704 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
10-26 02:43:03.121  5704  5704 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
10-26 02:43:03.121  5704  5704 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
10-26 02:43:03.121  5704  5704 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
10-26 02:43:03.121  5704  5704 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
10-26 02:43:03.121  5704  5704 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
10-26 02:43:03.121  5704  5704 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
10-26 02:43:03.121  5704  5704 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-26 02:43:03.121  5704  5704 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
10-26 02:43:03.121  5704  5704 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
10-26 02:43:03.121  5704  5704 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
10-26 02:43:03.121  5704  5704 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
10-26 02:43:03.121  5704  5704 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
10-26 02:43:03.121  5704  5704 D StrictMode: StrictMode policy violation; ~duration=86 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
10-26 02:43:03.121  5704  5704 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
10-26 02:43:03.121  5704  5704 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
10-26 02:43:03.121  5704  5704 D StrictMode: 	at java.io.File.lastModified(File.java:569)
10-26 02:43:03.121  5704  5704 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
10-26 02:43:03.121  5704  5704 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
10-26 02:43:03.121  5704  5704 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
10-26 02:43:03.121  5704  5704 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
10-26 02:43:03.121  5704  5704 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
10-26 02:43:03.121  5704  5704 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
10-26 02:43:03.121  5704  5704 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
10-26 02:43:03.121  5704  5704 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
10-26 02:43:03.121  5704  5704 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
10-26 02:43:03.121  5704  5704 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
10-26 02:43:03.121  5704  5704 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
10-26 02:43:03.121  5704  5704 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-26 02:43:03.121  5704  5704 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
10-26 02:43:03.121  5704  5704 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
10-26 02:43:03.121  5704  5704 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
10-26 02:43:03.121  5704  5704 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
10-26 02:43:03.121  5704  5704 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
10-26 02:43:03.122  4606  4606 D BtGatt.DebugUtils: handleDebugAction() action=null
10-26 02:43:03.123  4606  4606 D BtGatt.GattService: Received stop request...Stopping profile...
10-26 02:43:03.123  4606  4606 D BtGatt.GattService: stop()
10-26 02:43:03.123  4606  4606 D BtGatt.AdvertiseManager: advertise clients cleared
10-26 02:43:03.123  4606  4664 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
10-26 02:43:03.126  4606  4606 V BluetoothAdapterState: isTurningOff()=false
10-26 02:43:03.126  4606  4606 V BluetoothAdapterState: isTurningOn()=false
10-26 02:43:03.126  4606  4606 V BluetoothAdapterState: isBleTurningOn()=false
10-26 02:43:03.126  4606  4606 V BluetoothAdapterState: isBleTurningOff()=true
10-26 02:43:03.126  4606  4664 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
10-26 02:43:03.126  5685  5685 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
10-26 02:43:03.126  4606  4664 D BluetoothAdapterProperties: Setting state to 10
10-26 02:43:03.126  4606  4664 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
10-26 02:43:03.127  4606  4664 I BluetoothAdapterState: Entering OffState
10-26 02:43:03.127   926   943 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
10-26 02:43:03.130  3545  3545 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
10-26 02:43:03.136  4606  4606 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
10-26 02:43:03.136  4606  4606 W BluetoothSdpJni: Cleaning up Bluetooth Health object
10-26 02:43:03.136  4606  4606 I BluetoothServiceJni: cleanupNative: return from cleanup
10-26 02:43:03.137  4606  4665 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
10-26 02:43:03.141  4606  4606 I art     : System.exit called, status: 0
10-26 02:43:03.141  4606  4606 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
10-26 02:43:03.155  5685  5685 D DockEventReceiver: finishStartingService: stopping service
,10-26 02:43:03.159   926   936 I ActivityManager: Killing 5393:com.android.sdm.plugins.sprintdm/1001 (adj 15): empty #17
10-26 02:43:03.176   926  3727 I ActivityManager: Process com.android.bluetooth (pid 4606) has died
10-26 02:43:03.180  3717  3717 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
10-26 02:43:03.182  3717  3717 D SystemUpdateService: onCreate
10-26 02:43:03.185  3717  3717 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
10-26 02:43:03.192  3717  3717 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
10-26 02:43:03.197  3717  5390 I iu.UploadsManager: num queued entries: 0
10-26 02:43:03.197  3717  5390 I iu.UploadsManager: num updated entries: 0
10-26 02:43:03.197  3717  5390 I iu.SyncManager: NEXT; no task
,10-26 02:43:03.199  3717  5744 I SystemUpdateService: active receiver: enabled
,10-26 02:43:03.213  3717  3717 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,10-26 02:43:03.214  3717  3717 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,10-26 02:43:03.216  3717  5744 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,10-26 02:43:03.220  3717  5744 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,10-26 02:43:03.220  3717  5744 I SystemUpdateService: now status is 0 (complete)
10-26 02:43:03.220  3717  5744 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
10-26 02:43:03.220  3717  5744 I SystemUpdateService: file has been verified
10-26 02:43:03.220  3717  5744 I SystemUpdateService: OTA package size = 21989297
,10-26 02:43:03.225   926  3106 I ActivityManager: Start proc 5747:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,10-26 02:43:03.233  3717  5744 I SystemUpdateService: showing system update notification
,10-26 02:43:03.249   926   943 D Tethering: InitialState.processMessage what=4
,10-26 02:43:03.251   926   943 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,10-26 02:43:03.263  5747  5747 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm64
,10-26 02:43:03.268   926   926 V NotificationService: pkg=com.google.android.gms canInterrupt=false intercept=true
,10-26 02:43:03.269  5747  5747 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,10-26 02:43:03.277  5747  5747 D SprintDMHelper: simOperator: 
10-26 02:43:03.277  5747  5747 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,10-26 02:43:03.302   926  3106 I ActivityManager: Start proc 5760:com.google.android.apps.gcs/u0a11 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,10-26 02:43:03.304  3717  3717 D SystemUpdateService: onDestroy
,10-26 02:43:03.312  4302  5759 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,10-26 02:43:03.318   926  3766 I ActivityManager: Killing 5123:com.google.android.youtube/u0a75 (adj 15): empty #17
,10-26 02:43:03.428  5760  5760 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm64
,10-26 02:43:03.437   926  3539 I ActivityManager: Killing 5459:com.android.defcontainer/u0a7 (adj 15): empty #17
,10-26 02:43:03.494  5704  5733 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,10-26 02:43:03.507   926   943 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2be0060:true
,10-26 02:43:06.319   534   534 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,10-26 02:43:06.319   534   534 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,10-26 02:43:07.745   926  3196 D WifiService: setWifiEnabled: true pid=5627, uid=10077
,10-26 02:43:07.745   926  3196 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,10-26 02:43:07.756   506   920 D SoftapController: Softap fwReload - Ok
,10-26 02:43:07.762   506   920 D CommandListener: Setting iface cfg
,10-26 02:43:07.762   506   920 D CommandListener: Trying to bring down wlan0
,10-26 02:43:07.764   506   920 D CommandListener: Clearing all IP addresses on wlan0
,10-26 02:43:07.772   926  2990 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,10-26 02:43:08.348   926  2990 D wifi    : set interface wlan0 flags (UP)
,10-26 02:43:08.352   926  2990 I WifiHAL : Initializing wifi
,10-26 02:43:08.353   926  2990 I WifiHAL : Creating socket
10-26 02:43:08.358   926  2990 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
10-26 02:43:08.359   926  2990 D wifi    : Did set static halHandle = 0x7f64651400
10-26 02:43:08.359   926  2990 D wifi    : halHandle = 0x7f64651400, mVM = 0x7f80c4d140, mCls = 0x201972
10-26 02:43:08.359   926  2990 D wifi    : array field set
10-26 02:43:08.360   926  2990 I WifiNative-HAL: interface[0] = wlan0
,10-26 02:43:08.362   926  5778 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=547145192448
10-26 02:43:08.362   926  5778 D wifi    : waitForHalEvents called, vm = 0x7f80c4d140, obj = 0x201972, env = 0x7f68c70ec0
10-26 02:43:08.364   926   943 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,10-26 02:43:08.421  5779  5779 I wpa_supplicant: Successfully initialized wpa_supplicant
,10-26 02:43:08.463   926  2990 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,10-26 02:43:08.466  5627  5627 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-26 02:43:08.468  5627  5627 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-26 02:43:08.469  5627  5627 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-26 02:43:08.483  5779  5779 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,10-26 02:43:08.544  5779  5779 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,10-26 02:43:08.545  5779  5779 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,10-26 02:43:08.566   926  2990 D WifiConfigStore: Loading config and enabling all networks 
,10-26 02:43:08.571  5627  5627 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,10-26 02:43:08.571  5627  5627 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-26 02:43:08.571  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-26 02:43:08.571  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-26 02:43:08.571  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-26 02:43:08.571  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-26 02:43:08.571  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-26 02:43:08.571  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-26 02:43:08.571  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,10-26 02:43:08.571  5627  5627 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,10-26 02:43:08.571  5627  5627 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,10-26 02:43:08.575  5627  5627 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-26 02:43:08.576  5627  5627 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-26 02:43:08.576  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-26 02:43:08.576  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-26 02:43:08.576  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-26 02:43:08.576  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-26 02:43:08.576  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-26 02:43:08.576  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-26 02:43:08.576  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-26 02:43:08.576  5627  5627 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-26 02:43:08.576  5627  5627 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,10-26 02:43:08.577  5627  5627 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-26 02:43:08.578  5627  5627 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-26 02:43:08.578  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-26 02:43:08.578  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-26 02:43:08.578  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-26 02:43:08.578  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-26 02:43:08.578  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-26 02:43:08.578  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-26 02:43:08.578  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-26 02:43:08.578  5627  5627 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-26 02:43:08.578  5627  5627 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,10-26 02:43:08.594   926  2990 D WifiConfigStore: loaded 0 passpoint configs
10-26 02:43:08.595   926  2990 W WifiConfigStore: Upgrading network 4 to android.uid.system:1000
10-26 02:43:08.595   926  2990 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
10-26 02:43:08.596   926  2990 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
10-26 02:43:08.597   926  2990 W WifiConfigStore: Upgrading network 3 to android.uid.system:1000
10-26 02:43:08.597   926  2990 W WifiConfigStore: Upgrading network 2 to android.uid.system:1000
10-26 02:43:08.598   926  2990 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
10-26 02:43:08.598   926  2990 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 5
10-26 02:43:08.598   926  2990 E WifiConfigStore: found sortedWifiConfigurations : "AndroidAP"WPA_PSK
10-26 02:43:08.598   926  2990 E WifiConfigStore: found sortedWifiConfigurations : "AndroidHotspot2346"WPA_PSK
10-26 02:43:08.599   926  2990 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
10-26 02:43:08.599   926  2990 E WifiConfigStore: found sortedWifiConfigurations : "Thali_internal"WPA_PSK
10-26 02:43:08.599   926  2990 E WifiConfigStore: found sortedWifiConfigurations : "MC"WPA_PSK
10-26 02:43:08.602   926  2990 D WifiNative-HAL: Setting external_sim to 1
10-26 02:43:08.602   926  2990 D wifi    : setting dfs flag to true, 0x7f64bb9420
10-26 02:43:08.603   926  2990 D WifiStateMachine: Setting OUI to DA-A1-19
10-26 02:43:08.603   926  2990 D wifi    : setting scan oui 0x7f64bb9420
10-26 02:43:08.603   926  2990 D WifiHAL : Sending mac address OUI
10-26 02:43:08.603  4302  4302 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
10-26 02:43:08.607   926  2990 E native  : do suspend false
10-26 02:43:08.614   926  2990 D wifi    : android_net_wifi_setLinkLayerStats: 1
10-26 02:43:08.614   926   926 D RttService: SCAN_AVAILABLE : 3
10-26 02:43:08.615   926  3047 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
10-26 02:43:08.615   506   920 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
10-26 02:43:08.616   506   920 D CommandListener: Setting iface cfg
,10-26 02:43:08.620   926  2973 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '121 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 121 Failed to set address (No such device)'
10-26 02:43:08.620   926  2973 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
10-26 02:43:08.629   926  2973 D WifiNative-HAL: p2pGetDeviceAddress
10-26 02:43:08.629   926  2973 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:70
10-26 02:43:08.633   926   941 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=116971 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=14 mControllerEnergyUsed=53 }
,10-26 02:43:11.320   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,10-26 02:43:11.701  5779  5779 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,10-26 02:43:11.706  5779  5779 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,10-26 02:43:11.710  5779  5779 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,10-26 02:43:11.714  5779  5779 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,10-26 02:43:12.040   926  2990 D WifiStateMachine: Disconnected CMD_START_SCAN source -2 7, 8 -> obsolete
,10-26 02:43:12.321   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,10-26 02:43:12.754   926  3766 D WifiService: setWifiEnabled: false pid=5627, uid=10077
,10-26 02:43:12.754   926  3766 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,10-26 02:43:12.762   926   926 D RttService: SCAN_AVAILABLE : 1
10-26 02:43:12.762   926  3047 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,10-26 02:43:12.778   926  2990 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
10-26 02:43:12.779   506   920 D CommandListener: Clearing all IP addresses on wlan0
,10-26 02:43:12.783   926  2990 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,10-26 02:43:12.784  5779  5779 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
,10-26 02:43:12.787  5627  5627 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,10-26 02:43:12.788  5627  5627 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-26 02:43:12.788  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-26 02:43:12.788  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-26 02:43:12.788  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-26 02:43:12.788  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-26 02:43:12.788  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-26 02:43:12.788  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-26 02:43:12.788  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-26 02:43:12.788  5627  5627 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-26 02:43:12.788  5627  5627 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
10-26 02:43:12.789  5627  5627 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,10-26 02:43:12.789  5627  5627 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-26 02:43:12.789  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-26 02:43:12.789  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-26 02:43:12.789  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-26 02:43:12.789  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-26 02:43:12.789  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-26 02:43:12.789  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-26 02:43:12.789  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-26 02:43:12.789  5627  5627 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-26 02:43:12.790  5627  5627 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
10-26 02:43:12.791  5627  5627 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-26 02:43:12.791  5627  5627 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-26 02:43:12.791  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-26 02:43:12.791  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-26 02:43:12.791  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-26 02:43:12.791  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-26 02:43:12.791  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-26 02:43:12.791  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-26 02:43:12.791  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,10-26 02:43:12.791  5627  5627 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-26 02:43:12.791  5627  5627 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,10-26 02:43:12.798  5779  5779 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
,10-26 02:43:12.822  5779  5779 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,10-26 02:43:12.826  5779  5779 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,10-26 02:43:12.929  4302  4302 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,10-26 02:43:12.929   926  2990 D wifi    : In wifi stop Hal
,10-26 02:43:12.931   926  2990 D wifi    : halHandle = 0x7f64651400, mVM = 0x7f80c4d140, mCls = 0x201972
,10-26 02:43:12.932   926  5778 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
10-26 02:43:12.933   926  5778 D WifiHAL : Got a signal to exit!!!
10-26 02:43:12.933   926  2990 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 0
,10-26 02:43:12.933   926  2990 E WifiHAL : Event processing terminated
10-26 02:43:12.934   926  2990 D wifi    : In wifi cleaned up handler
10-26 02:43:12.934   926  2990 I WifiHAL : Internal cleanup completed
10-26 02:43:12.933   926  5778 I WifiHAL : Exit wifi_event_loop
10-26 02:43:12.937  5627  5627 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-26 02:43:12.938  4062  4197 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
10-26 02:43:12.940  5627  5627 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-26 02:43:12.943  5627  5627 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-26 02:43:12.956   926  5778 D wifi    : set interface wlan0 flags (DOWN)
,10-26 02:43:12.957   926  2990 D WifiNative-HAL: HAL event thread stopped successfully
,10-26 02:43:13.030   506   920 E Netd    : netlink response contains error (No such file or directory)
,10-26 02:43:13.163   926   943 D Tethering: InitialState.processMessage what=4
,10-26 02:43:13.170   926   943 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,10-26 02:43:13.322   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,10-26 02:43:14.323   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,10-26 02:43:15.325   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,10-26 02:43:16.326   534   534 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,10-26 02:43:17.797   926   943 I ActivityManager: Start proc 5800:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,10-26 02:43:17.883  5800  5800 D AdapterServiceConfig: Adding HeadsetService
,10-26 02:43:17.884  5800  5800 D AdapterServiceConfig: Adding A2dpService
10-26 02:43:17.884  5800  5800 D AdapterServiceConfig: Adding HidService
10-26 02:43:17.884  5800  5800 D AdapterServiceConfig: Adding HealthService
10-26 02:43:17.884  5800  5800 D AdapterServiceConfig: Adding PanService
10-26 02:43:17.884  5800  5800 D AdapterServiceConfig: Adding GattService
,10-26 02:43:17.885  5800  5800 D AdapterServiceConfig: Adding BluetoothMapService
10-26 02:43:17.885  5800  5800 D AdapterServiceConfig: Adding SapService
,10-26 02:43:17.895   926   943 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@94ffa89:true
,10-26 02:43:17.895  5800  5800 D BluetoothAdapterState: make() - Creating AdapterState
,10-26 02:43:17.898  5800  5800 I bt_bluedroid: init
,10-26 02:43:17.900  5800  5812 I BluetoothAdapterState: Entering OffState
,10-26 02:43:17.902  5800  5813 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
10-26 02:43:17.903  5800  5813 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
10-26 02:43:17.903  5800  5813 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,10-26 02:43:17.903  5800  5813 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
10-26 02:43:17.904  5800  5800 I bt_bluedroid: get_profile_interface socket
,10-26 02:43:17.905  5800  5816 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:D4
,10-26 02:43:17.906  5800  5800 I bt_bluedroid: get_profile_interface sdp
10-26 02:43:17.907  5800  5816 D BluetoothAdapterProperties: Name is: Nexus 6P
,10-26 02:43:17.910  5800  5811 I bt_bluedroid: config_hci_snoop_log
10-26 02:43:17.911   926   943 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,10-26 02:43:17.915  5800  5812 D BluetoothAdapterState: Current state: OFF, message: 0
10-26 02:43:17.916  5800  5812 D BluetoothAdapterProperties: Setting state to 14
10-26 02:43:17.916  5800  5812 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,10-26 02:43:17.918  5800  5812 D BluetoothBondStateMachine: make
,10-26 02:43:17.920  5800  5817 I BluetoothBondStateMachine: StableState(): Entering Off State
,10-26 02:43:17.922  5800  5812 I BluetoothAdapterState: Entering PendingCommandState
,10-26 02:43:17.924  5800  5800 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,10-26 02:43:17.926  5800  5800 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@582acd5
,10-26 02:43:17.927  5800  5800 D BtGatt.DebugUtils: handleDebugAction() action=null
10-26 02:43:17.927  5800  5800 D BtGatt.GattService: Received start request. Starting profile...
10-26 02:43:17.927  5800  5800 D BtGatt.GattService: start()
10-26 02:43:17.928  5800  5800 I bt_bluedroid: get_profile_interface gatt
,10-26 02:43:17.929  5800  5800 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@582acd5
,10-26 02:43:17.929  5800  5800 D BtGatt.AdvertiseManager: advertise manager created
,10-26 02:43:17.935  5800  5800 V BluetoothAdapterState: isTurningOff()=false
10-26 02:43:17.935  5800  5800 V BluetoothAdapterState: isTurningOn()=false
10-26 02:43:17.935  5800  5800 V BluetoothAdapterState: isBleTurningOn()=true
,10-26 02:43:17.935  5800  5800 V BluetoothAdapterState: isBleTurningOff()=false
,10-26 02:43:17.936  5800  5812 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
10-26 02:43:17.937  5800  5812 I bt_bluedroid: bt_bluedroid
10-26 02:43:17.937  5800  5813 D bt_stack_manager: event_start_up_stack is bringing up the stack.
10-26 02:43:17.938  5800  5813 I bt_hci  : start_up
,10-26 02:43:17.943  5800  5813 I bt_vendor: alloc value 0xf412d871
,10-26 02:43:17.943  5800  5813 I bt_vendor: init
10-26 02:43:17.943  5800  5813 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
10-26 02:43:17.943  5800  5813 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,10-26 02:43:18.054  5800  5813 D bt_hci  : start_up starting async portion
10-26 02:43:18.055  5800  5820 I bt_hci  : event_finish_startup
,10-26 02:43:18.055  5800  5820 I bt_hci_h4: hal_open
10-26 02:43:18.055  5800  5820 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,10-26 02:43:18.054  5821  5821 W irq/448-msm_hs_: type=1400 audit(0.0:117): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
10-26 02:43:18.059  5800  5820 I bt_userial_vendor: device fd = 54 open
,10-26 02:43:18.075  5800  5820 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,10-26 02:43:18.078  5800  5820 D bt_hwcfg: Chipset BCM4358A3
,10-26 02:43:18.078  5800  5820 D bt_hwcfg: Target name = [BCM4358A3]
,10-26 02:43:18.079  5800  5820 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,10-26 02:43:18.590  5800  5820 I bt_hwcfg: bt vendor lib: set UART baud 115200
,10-26 02:43:18.591  5800  5820 D bt_hwcfg: Settlement delay -- 100 ms
,10-26 02:43:18.591  5800  5820 I bt_hwcfg: Setting fw settlement delay to 100 
,10-26 02:43:18.726  5800  5820 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,10-26 02:43:18.727  5800  5820 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:D4
,10-26 02:43:18.730  5800  5820 I bt_hwcfg: vendor lib fwcfg completed
,10-26 02:43:18.730  5800  5820 I bt_vendor: firmware callback
,10-26 02:43:18.730  5800  5820 I bt_hci  : firmware_config_callback
,10-26 02:43:18.740  5800  5823 I bt_btu  : btu_task pending for preload complete event
,10-26 02:43:18.740  5800  5823 I bt_btu_task: Bluetooth chip preload is complete
10-26 02:43:18.740  5800  5823 I bt_btu  : btu_task received preload complete event
,10-26 02:43:18.746  5800  5823 I         : BTE_InitTraceLevels -- TRC_HCI
,10-26 02:43:18.746  5800  5823 I         : BTE_InitTraceLevels -- TRC_L2CAP
10-26 02:43:18.747  5800  5823 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,10-26 02:43:18.747  5800  5823 I         : BTE_InitTraceLevels -- TRC_AVDT
10-26 02:43:18.747  5800  5823 I         : BTE_InitTraceLevels -- TRC_AVRC
,10-26 02:43:18.747  5800  5823 I         : BTE_InitTraceLevels -- TRC_A2D
10-26 02:43:18.747  5800  5823 I         : BTE_InitTraceLevels -- TRC_BNEP
10-26 02:43:18.747  5800  5823 I         : BTE_InitTraceLevels -- TRC_BTM
10-26 02:43:18.747  5800  5823 I         : BTE_InitTraceLevels -- TRC_GAP
10-26 02:43:18.747  5800  5823 I         : BTE_InitTraceLevels -- TRC_PAN
10-26 02:43:18.747  5800  5823 I         : BTE_InitTraceLevels -- TRC_SDP
,10-26 02:43:18.747  5800  5823 I         : BTE_InitTraceLevels -- TRC_GATT
10-26 02:43:18.748  5800  5823 I         : BTE_InitTraceLevels -- TRC_SMP
10-26 02:43:18.748  5800  5823 I         : BTE_InitTraceLevels -- TRC_BTAPP
10-26 02:43:18.748  5800  5823 I         : BTE_InitTraceLevels -- TRC_BTIF
,10-26 02:43:18.842  5800  5823 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf40ab549
10-26 02:43:18.842  5800  5823 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf40ab549 
,10-26 02:43:18.866  5800  5816 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,10-26 02:43:18.869  5800  5816 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,10-26 02:43:18.869  5800  5816 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:D4
,10-26 02:43:18.872  5800  5816 D BluetoothAdapterProperties: Name is: Nexus 6P
,10-26 02:43:18.875  5800  5816 D BluetoothAdapterProperties: Scan Mode:20
,10-26 02:43:18.876  5800  5816 D BluetoothAdapterProperties: Discoverable Timeout:120
,10-26 02:43:18.876  5800  5816 D bt_hci  : do_postload posting postload work item
10-26 02:43:18.876  5800  5820 I bt_hci  : event_postload
10-26 02:43:18.877  5800  5820 I bt_vendor: sco_config_cb
10-26 02:43:18.877  5800  5820 I bt_hci  : sco_config_callback postload finished.
10-26 02:43:18.881  5800  5816 D bt_bte_conf: Device ID record 1 : primary
10-26 02:43:18.881  5800  5816 D bt_bte_conf:   vendorId            = 000f
10-26 02:43:18.881  5800  5816 D bt_bte_conf:   vendorIdSource      = 0001
10-26 02:43:18.881  5800  5816 D bt_bte_conf:   product             = 1200
10-26 02:43:18.881  5800  5816 D bt_bte_conf:   version             = 1436
10-26 02:43:18.881  5800  5816 D bt_bte_conf:   clientExecutableURL = 
,10-26 02:43:18.881  5800  5816 D bt_bte_conf:   serviceDescription  = 
10-26 02:43:18.881  5800  5816 D bt_bte_conf:   documentationURL    = 
,10-26 02:43:18.881  5800  5816 D bt_bte_conf: bte_load_did_conf no section named DID2.
,10-26 02:43:18.882  5627  5627 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-26 02:43:18.882  5800  5813 D bt_stack_manager: event_start_up_stack finished
,10-26 02:43:18.885  5627  5627 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-26 02:43:18.887  5627  5627 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-26 02:43:18.888  5800  5812 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
10-26 02:43:18.888  5800  5820 I bt_vendor: low_power_mode_cb
10-26 02:43:18.888  5800  5812 D BluetoothAdapterProperties: Setting state to 15
10-26 02:43:18.888  5800  5812 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
10-26 02:43:18.889  5800  5812 I BluetoothAdapterState: Entering BleOnState
10-26 02:43:18.892  5800  5812 D BluetoothAdapterState: Current state: BLE ON, message: 1
,10-26 02:43:18.893  5800  5812 D BluetoothAdapterProperties: Setting state to 11
10-26 02:43:18.893  5800  5812 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,10-26 02:43:18.899  5627  5627 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-26 02:43:18.902  5627  5627 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-26 02:43:18.903  5800  5800 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@582acd5
10-26 02:43:18.904  5800  5800 D HeadsetService: Received start request. Starting profile...
10-26 02:43:18.905  5627  5627 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-26 02:43:18.907  5800  5800 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,10-26 02:43:18.908  5800  5800 D HeadsetStateMachine: make
,10-26 02:43:18.912  5800  5812 I BluetoothAdapterState: Entering PendingCommandState
,10-26 02:43:18.917  5800  5800 D HeadsetStateMachine: max_hf_connections = 1
10-26 02:43:18.918  5800  5800 I bt_bluedroid: get_profile_interface handsfree
10-26 02:43:18.918  5800  5816 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
,10-26 02:43:18.918  5800  5816 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
,10-26 02:43:18.921  5800  5800 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@582acd5
,10-26 02:43:18.925  5800  5800 D A2dpService: Received start request. Starting profile...
10-26 02:43:18.926  5800  5800 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,10-26 02:43:18.926  5800  5800 I bt_bluedroid: get_profile_interface avrcp
,10-26 02:43:18.932  5800  5800 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,10-26 02:43:18.932  5800  5800 I BluetoothA2dpServiceJni: classInitNative: succeeds
10-26 02:43:18.932  5800  5800 D A2dpStateMachine: make
,10-26 02:43:18.934  5800  5800 I bt_bluedroid: get_profile_interface a2dp
10-26 02:43:18.934  5800  5816 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
10-26 02:43:18.936  5800  5831 D A2dpStateMachine: Enter Disconnected: -2
,10-26 02:43:18.937  5800  5800 I BluetoothHidServiceJni: classInitNative: succeeds
,10-26 02:43:18.938  5800  5800 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@582acd5
10-26 02:43:18.939  5800  5800 D HidService: Received start request. Starting profile...
10-26 02:43:18.939  5800  5800 I bt_bluedroid: get_profile_interface hidhost
10-26 02:43:18.940  5800  5800 D HidService: setHidService(): set to: null
10-26 02:43:18.940  5800  5816 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf408c56d
10-26 02:43:18.940  3545  3545 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
10-26 02:43:18.940  5800  5816 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
,10-26 02:43:18.940  5800  5800 I BluetoothHealthServiceJni: classInitNative: succeeds
10-26 02:43:18.941  5800  5800 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@582acd5
10-26 02:43:18.942  5800  5800 D HealthService: Received start request. Starting profile...
10-26 02:43:18.942  5685  5685 D BluetoothInputDevice: Proxy object connected
,10-26 02:43:18.943  5800  5800 I bt_bluedroid: get_profile_interface health
10-26 02:43:18.944  5800  5800 I BluetoothPanServiceJni: classInitNative(L105): succeeds
10-26 02:43:18.945  5800  5800 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@582acd5
10-26 02:43:18.945  5685  5685 D HidProfile: Bluetooth service connected
10-26 02:43:18.946  5800  5800 D PanService: Received start request. Starting profile...
10-26 02:43:18.946  5800  5800 D BluetoothPanServiceJni: initializeNative(L110): pan
10-26 02:43:18.946  5800  5800 I bt_bluedroid: get_profile_interface pan
10-26 02:43:18.947  5685  5685 D BluetoothPan: BluetoothPAN Proxy object connected
,10-26 02:43:18.947  5800  5816 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
10-26 02:43:18.947  5685  5685 D PanProfile: Bluetooth service connected
,10-26 02:43:18.949  5800  5800 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@582acd5
,10-26 02:43:18.950  5685  5685 D BluetoothMap: Proxy object connected
10-26 02:43:18.950  5800  5800 D BluetoothMapService: Received start request. Starting profile...
10-26 02:43:18.951  5800  5800 D BluetoothMapService: start()
10-26 02:43:18.951  5685  5685 D MapProfile: Bluetooth service connected
10-26 02:43:18.951  5685  5685 D BluetoothMap: getConnectedDevices()
10-26 02:43:18.952  5685  5685 D BluetoothMap: Bluetooth is Not enabled
,10-26 02:43:18.953  5800  5800 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,10-26 02:43:18.955  5800  5800 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
,10-26 02:43:18.955  5800  5800 D BluetoothMapAppObserver: createReceiver()
10-26 02:43:18.956  5800  5800 D BluetoothMapAppObserver: initObservers()
10-26 02:43:18.956  5800  5800 D BluetoothMapAppObserver: getEnabledAccountItems()
,10-26 02:43:18.963  5800  5800 V SapService: SapBinder()
,10-26 02:43:18.963  5800  5800 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@582acd5
,10-26 02:43:18.963  5800  5800 D SapService: Received start request. Starting profile...
10-26 02:43:18.963  5800  5800 V SapService: start()
,10-26 02:43:18.966  5800  5800 V BluetoothAdapterState: isTurningOff()=false
10-26 02:43:18.967  5800  5800 V BluetoothAdapterState: isTurningOn()=true
10-26 02:43:18.967  5800  5800 V BluetoothAdapterState: isBleTurningOn()=false
,10-26 02:43:18.967  5800  5800 V BluetoothAdapterState: isBleTurningOff()=false
10-26 02:43:18.967  5800  5800 V BluetoothAdapterState: isTurningOff()=false
10-26 02:43:18.967  5800  5800 V BluetoothAdapterState: isTurningOn()=true
10-26 02:43:18.967  5800  5800 V BluetoothAdapterState: isBleTurningOn()=false
10-26 02:43:18.967  5800  5800 V BluetoothAdapterState: isBleTurningOff()=false
10-26 02:43:18.967  5800  5829 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=3
10-26 02:43:18.967  5800  5800 V BluetoothAdapterState: isTurningOff()=false
10-26 02:43:18.967  5800  5800 V BluetoothAdapterState: isTurningOn()=true
10-26 02:43:18.967  5800  5800 V BluetoothAdapterState: isBleTurningOn()=false
10-26 02:43:18.967  5800  5800 V BluetoothAdapterState: isBleTurningOff()=false
10-26 02:43:18.968  5800  5800 V BluetoothAdapterState: isTurningOff()=false
10-26 02:43:18.968  5800  5800 V BluetoothAdapterState: isTurningOn()=true
10-26 02:43:18.968  5800  5800 V BluetoothAdapterState: isBleTurningOn()=false
10-26 02:43:18.968  5800  5800 V BluetoothAdapterState: isBleTurningOff()=false
10-26 02:43:18.968  5800  5800 V BluetoothAdapterState: isTurningOff()=false
10-26 02:43:18.968  5800  5800 V BluetoothAdapterState: isTurningOn()=true
10-26 02:43:18.968  5800  5800 V BluetoothAdapterState: isBleTurningOn()=false
10-26 02:43:18.968  5800  5800 V BluetoothAdapterState: isBleTurningOff()=false
10-26 02:43:18.968  5800  5800 V BluetoothAdapterState: isTurningOff()=false
10-26 02:43:18.969  5800  5800 V BluetoothAdapterState: isTurningOn()=true
10-26 02:43:18.969  5800  5800 V BluetoothAdapterState: isBleTurningOn()=false
10-26 02:43:18.969  5800  5800 V BluetoothAdapterState: isBleTurningOff()=false
,10-26 02:43:18.970  5800  5800 V BluetoothAdapterState: isTurningOff()=false
10-26 02:43:18.970  5800  5800 V BluetoothAdapterState: isTurningOn()=true
10-26 02:43:18.970  5800  5800 V BluetoothAdapterState: isBleTurningOn()=false
10-26 02:43:18.970  5800  5800 V BluetoothAdapterState: isBleTurningOff()=false
10-26 02:43:18.970  5800  5812 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
10-26 02:43:18.970  5800  5812 D BluetoothAdapterProperties: ScanMode =  20
10-26 02:43:18.970  5800  5812 D BluetoothAdapterProperties: State =  11
10-26 02:43:18.970  5800  5812 D BluetoothAdapterProperties: Setting state to 12
10-26 02:43:18.970  5800  5812 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
10-26 02:43:18.971  5800  5812 I BluetoothAdapterState: Entering OnState
10-26 02:43:18.971  5685  5698 D BluetoothPan: onBluetoothStateChange on: true
,10-26 02:43:18.972   926   943 D BluetoothHeadset: onBluetoothStateChange: up=true
10-26 02:43:18.972   926   943 D BluetoothHeadset: onBluetoothStateChange: up=true
10-26 02:43:18.972  5685  5696 D BluetoothPbap: onBluetoothStateChange: up=true
10-26 02:43:18.975  5800  5816 D BluetoothAdapterProperties: Scan Mode:21
10-26 02:43:18.975  5800  5816 D BluetoothAdapterProperties: Discoverable Timeout:120
10-26 02:43:18.975  5627  5627 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
,10-26 02:43:18.976  3128  3143 D BluetoothMap: onBluetoothStateChange: up=true
,10-26 02:43:18.977   926   943 D BluetoothHeadset: onBluetoothStateChange: up=true
,10-26 02:43:18.977  3128  3988 D BluetoothHeadset: onBluetoothStateChange: up=true
10-26 02:43:18.977  3128  3128 D BluetoothMap: Proxy object connected
,10-26 02:43:18.977  3128  3128 D MapProfile: Bluetooth service connected
10-26 02:43:18.977  3128  3128 D BluetoothMap: getConnectedDevices()
,10-26 02:43:18.978  3128  3986 D BluetoothInputDevice: onBluetoothStateChange: up=true
,10-26 02:43:18.979  5627  5627 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-26 02:43:18.979  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-26 02:43:18.979  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-26 02:43:18.979  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-26 02:43:18.979  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-26 02:43:18.979  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-26 02:43:18.979  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-26 02:43:18.979  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,10-26 02:43:18.980   926   943 D BluetoothA2dp: onBluetoothStateChange: up=true
10-26 02:43:18.980  5685  5698 D BluetoothMap: onBluetoothStateChange: up=true
,10-26 02:43:18.981  3774  3995 D BluetoothHeadset: onBluetoothStateChange: up=true
,10-26 02:43:18.981  5685  5696 D BluetoothInputDevice: onBluetoothStateChange: up=true
10-26 02:43:18.981   926   926 D BluetoothA2dp: Proxy object connected
10-26 02:43:18.981  5627  5627 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,10-26 02:43:18.981  3128  3986 D BluetoothPbap: onBluetoothStateChange: up=true
10-26 02:43:18.982  5800  5800 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
10-26 02:43:18.982  3128  3128 D BluetoothInputDevice: Proxy object connected
10-26 02:43:18.982  3128  3128 D HidProfile: Bluetooth service connected
10-26 02:43:18.982  5800  5800 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
,10-26 02:43:18.983  3128  3988 D BluetoothPan: onBluetoothStateChange on: true
10-26 02:43:18.984  5800  5800 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
10-26 02:43:18.984  3128  3146 D BluetoothA2dp: onBluetoothStateChange: up=true
,10-26 02:43:18.986  5627  5627 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-26 02:43:18.986  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-26 02:43:18.986  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-26 02:43:18.986  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-26 02:43:18.986  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-26 02:43:18.986  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-26 02:43:18.986  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-26 02:43:18.986  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-26 02:43:18.987  3128  3128 D BluetoothPan: BluetoothPAN Proxy object connected
10-26 02:43:18.987  3128  3128 D PanProfile: Bluetooth service connected
,10-26 02:43:18.988  3128  3128 D BluetoothA2dp: Proxy object connected
10-26 02:43:18.989  5800  5800 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
10-26 02:43:18.989  5627  5627 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
10-26 02:43:18.990   926   926 I Telecom : BluetoothPhoneService: queryPhoneState
10-26 02:43:18.992  5685  5685 D LocalBluetoothProfileManager: Adding local A2DP profile
10-26 02:43:18.992  5800  5800 D ObexServerSockets: Succeed to create listening sockets 
10-26 02:43:18.992  5800  5800 D ObexServerSockets0: startAccept()
,10-26 02:43:18.992  5800  5800 D ObexServerSockets0: prepareForNewConnect()
10-26 02:43:18.993  5627  5627 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-26 02:43:18.993  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-26 02:43:18.993  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-26 02:43:18.993  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-26 02:43:18.993  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-26 02:43:18.993  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-26 02:43:18.993  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-26 02:43:18.993  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-26 02:43:18.996  5627  5627 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
10-26 02:43:18.996  5627  5627 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
10-26 02:43:18.996  5685  5685 D LocalBluetoothProfileManager: Adding local HEADSET profile
,10-26 02:43:18.998  5627  5627 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-26 02:43:18.998  5800  5800 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
10-26 02:43:18.998  5800  5800 D BluetoothSdpJni: SDP Create record success - handle: 0
10-26 02:43:19.000  5627  5627 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-26 02:43:19.000  5800  5838 D ObexServerSockets0: Accepting socket connection...
10-26 02:43:19.001  5800  5800 D BluetoothMapService: onReceive
,10-26 02:43:19.001  5800  5800 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
10-26 02:43:19.001  5800  5800 D BluetoothMapService: STATE_ON
,10-26 02:43:19.001  5800  5840 D ObexServerSockets0: Accepting socket connection...
10-26 02:43:19.003  5800  5841 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
10-26 02:43:19.004  5685  5685 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
10-26 02:43:19.004  5627  5627 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-26 02:43:19.005  5800  5841 D BluetoothSdpJni: sdpCreateSapsRecordNative:
,10-26 02:43:19.005  5800  5841 D BluetoothSdpJni: SDP Create record success - handle: 1
,10-26 02:43:19.007  5685  5685 D BluetoothA2dp: Proxy object connected
,10-26 02:43:19.011  3545  3545 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,10-26 02:43:19.018  3128  3128 D BluetoothPbap: Proxy object connected
,10-26 02:43:19.019  3128  3128 D PbapServerProfile: Bluetooth service connected
,10-26 02:43:19.021  5685  5685 D DockEventReceiver: finishStartingService: stopping service
,10-26 02:43:19.022  5685  5685 D BluetoothPbap: Proxy object connected
10-26 02:43:19.023  5685  5685 D PbapServerProfile: Bluetooth service connected
,10-26 02:43:19.027  5800  5845 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,10-26 02:43:19.038  5800  5800 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,10-26 02:43:19.039  5800  5800 D ObexServerSockets0: prepareForNewConnect()
,10-26 02:43:19.042  5800  5849 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,10-26 02:43:19.043  5800  5849 I BtOppRfcommListener: Accept thread started.
,10-26 02:43:19.075  3128  3143 D BluetoothHeadset: Proxy object connected
10-26 02:43:19.075  3128  3128 D HeadsetProfile: Bluetooth service connected
10-26 02:43:19.075   926   926 D BluetoothHeadset: Proxy object connected
,10-26 02:43:19.075   926   926 D BluetoothHeadset: Proxy object connected
10-26 02:43:19.075  3774  3804 D BluetoothHeadset: Proxy object connected
,10-26 02:43:19.076   926   926 D BluetoothHeadset: Proxy object connected
,10-26 02:43:19.078   926   943 D BluetoothHeadset: Proxy object connected
10-26 02:43:19.078  3128  3146 D BluetoothHeadset: Proxy object connected
10-26 02:43:19.078  3128  3128 D HeadsetProfile: Bluetooth service connected
,10-26 02:43:19.081  3774  3799 D BluetoothHeadset: Proxy object connected
,10-26 02:43:19.099  5685  5698 D BluetoothHeadset: Proxy object connected
,10-26 02:43:19.102  5685  5685 D HeadsetProfile: Bluetooth service connected
,10-26 02:43:21.061  3649  3844 I Keyboard.Facilitator.LanguageModelFlusher: run()
,10-26 02:43:21.062  3649  3844 I Keyboard.Facilitator: flushDynamicLanguageModels()
,10-26 02:43:21.088  3545  3545 I ConfigService: onCreate
,10-26 02:43:21.327   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,10-26 02:43:22.328   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,10-26 02:43:22.771  5800  5812 D BluetoothAdapterState: Current state: ON, message: 23
10-26 02:43:22.771  5800  5812 D BluetoothAdapterProperties: Setting state to 13
10-26 02:43:22.771  5800  5812 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
10-26 02:43:22.773  5800  5812 D BluetoothAdapterProperties: onBluetoothDisable()
,10-26 02:43:22.774  5800  5812 I BluetoothAdapterState: Entering PendingCommandState
10-26 02:43:22.777  5800  5800 D BluetoothMapService: onReceive
10-26 02:43:22.777  5800  5800 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,10-26 02:43:22.777  5800  5800 D BluetoothMapService: STATE_TURNING_OFF
10-26 02:43:22.778  5800  5800 D BluetoothMapService: MAP Service closeService in
10-26 02:43:22.778  5800  5800 D BluetoothMapMasInstance0: MAP Service shutdown
10-26 02:43:22.779  5800  5800 D ObexServerSockets0: shutdown(block = true)
,10-26 02:43:22.780  5800  5800 D ObexServerSockets0: shutdown called from another thread - interrupt().
,10-26 02:43:22.780  5800  5838 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
,10-26 02:43:22.780  5800  5825 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
10-26 02:43:22.780  5800  5800 D ObexServerSockets0: shutdown called from another thread - interrupt().
,10-26 02:43:22.780  5800  5840 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
,10-26 02:43:22.782  5800  5816 D BluetoothAdapterProperties: Scan Mode:20
10-26 02:43:22.783  5800  5812 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
,10-26 02:43:22.784  5800  5800 I BtOppRfcommListener: stopping Accept Thread
10-26 02:43:22.784  5685  5685 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
10-26 02:43:22.784  5800  5849 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
10-26 02:43:22.785  5800  5849 I BtOppRfcommListener: BluetoothSocket listen thread finished
10-26 02:43:22.788  5800  5800 D HeadsetService: Received stop request...Stopping profile...
10-26 02:43:22.790  5627  5627 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,10-26 02:43:22.790  5627  5627 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-26 02:43:22.790  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-26 02:43:22.790  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-26 02:43:22.790  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-26 02:43:22.790  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-26 02:43:22.790  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-26 02:43:22.790  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-26 02:43:22.790  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-26 02:43:22.791  3128  3988 D BluetoothHeadset: Proxy object disconnected
10-26 02:43:22.791   926   926 D BluetoothHeadset: Proxy object disconnected
10-26 02:43:22.791   926   926 D BluetoothHeadset: Proxy object disconnected
10-26 02:43:22.792  3128  3128 D HeadsetProfile: Bluetooth service disconnected
10-26 02:43:22.793  5685  5696 D BluetoothHeadset: Proxy object disconnected
,10-26 02:43:22.793  5627  5627 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-26 02:43:22.793  3774  3995 D BluetoothHeadset: Proxy object disconnected
10-26 02:43:22.794  5627  5627 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
10-26 02:43:22.794   926   926 D BluetoothHeadset: Proxy object disconnected
10-26 02:43:22.798  5800  5800 V BluetoothAdapterState: isTurningOff()=true
10-26 02:43:22.798  5800  5800 V BluetoothAdapterState: isTurningOn()=false
10-26 02:43:22.798  5800  5800 V BluetoothAdapterState: isBleTurningOn()=false
10-26 02:43:22.798  5800  5800 V BluetoothAdapterState: isBleTurningOff()=false
,10-26 02:43:22.802  5627  5627 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,10-26 02:43:22.802  5627  5627 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-26 02:43:22.802  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-26 02:43:22.802  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-26 02:43:22.802  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-26 02:43:22.802  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-26 02:43:22.802  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-26 02:43:22.802  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-26 02:43:22.802  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-26 02:43:22.803  5627  5627 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-26 02:43:22.803  5800  5800 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
10-26 02:43:22.803  5627  5627 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
10-26 02:43:22.803  5800  5800 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
10-26 02:43:22.803  5800  5823 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,10-26 02:43:22.803  5800  5823 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
10-26 02:43:22.803  5800  5823 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
10-26 02:43:22.804  5800  5816 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
10-26 02:43:22.804  5800  5816 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
10-26 02:43:22.804  5800  5800 D A2dpService: Received stop request...Stopping profile...
10-26 02:43:22.805  5800  5831 D A2dpStateMachine: Exit Disconnected: -1
10-26 02:43:22.807  5627  5627 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,10-26 02:43:22.807  5627  5627 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-26 02:43:22.807  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-26 02:43:22.807  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-26 02:43:22.807  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-26 02:43:22.807  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-26 02:43:22.807  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-26 02:43:22.807  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-26 02:43:22.807  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-26 02:43:22.807   926   926 D BluetoothA2dp: Proxy object disconnected
10-26 02:43:22.808  5627  5627 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-26 02:43:22.809  5685  5685 D HeadsetProfile: Bluetooth service disconnected
10-26 02:43:22.808  5627  5627 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,10-26 02:43:22.810  5800  5800 D HidService: Received stop request...Stopping profile...
10-26 02:43:22.810  5800  5800 D HidService: Stopping Bluetooth HidService
10-26 02:43:22.813  5627  5627 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-26 02:43:22.815  3128  3128 D BluetoothA2dp: Proxy object disconnected
10-26 02:43:22.815  3128  3128 D BluetoothInputDevice: Proxy object disconnected
10-26 02:43:22.815  3128  3128 D HidProfile: Bluetooth service disconnected
10-26 02:43:22.816  5627  5627 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-26 02:43:22.818  5685  5685 D DockEventReceiver: finishStartingService: stopping service
10-26 02:43:22.818  5627  5627 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-26 02:43:22.818  5800  5800 D HealthService: Received stop request...Stopping profile...
10-26 02:43:22.820  5800  5800 D PanService: Received stop request...Stopping profile...
10-26 02:43:22.822  3128  3128 D BluetoothPan: BluetoothPAN Proxy object disconnected
10-26 02:43:22.822  3128  3128 D PanProfile: Bluetooth service disconnected
10-26 02:43:22.823  5800  5800 D BluetoothMapService: Received stop request...Stopping profile...
10-26 02:43:22.823  5800  5800 D BluetoothMapService: stop()
,10-26 02:43:22.824  5800  5800 D BluetoothMapAppObserver: deinitObservers()
,10-26 02:43:22.824  5800  5800 D BluetoothMapAppObserver: removeReceiver()
10-26 02:43:22.825  3128  3128 D BluetoothMap: Proxy object disconnected
10-26 02:43:22.825  3128  3128 D MapProfile: Bluetooth service disconnected
10-26 02:43:22.825  5800  5800 V BluetoothAdapterState: isTurningOff()=true
10-26 02:43:22.825  5685  5685 D BluetoothA2dp: Proxy object disconnected
10-26 02:43:22.825  5800  5800 V BluetoothAdapterState: isTurningOn()=false
10-26 02:43:22.825  5800  5800 V BluetoothAdapterState: isBleTurningOn()=false
10-26 02:43:22.825  5800  5800 V BluetoothAdapterState: isBleTurningOff()=false
10-26 02:43:22.825  5685  5685 D BluetoothInputDevice: Proxy object disconnected
10-26 02:43:22.826  5685  5685 D HidProfile: Bluetooth service disconnected
10-26 02:43:22.826  5685  5685 D BluetoothPan: BluetoothPAN Proxy object disconnected
10-26 02:43:22.826  5685  5685 D PanProfile: Bluetooth service disconnected
10-26 02:43:22.827  5685  5685 D BluetoothMap: Proxy object disconnected
10-26 02:43:22.827  5685  5685 D MapProfile: Bluetooth service disconnected
10-26 02:43:22.827  5800  5823 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
10-26 02:43:22.827  5800  5823 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
10-26 02:43:22.827  5800  5800 D SapService: Received stop request...Stopping profile...
10-26 02:43:22.827  5800  5800 V SapService: stop()
10-26 02:43:22.828  5800  5816 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
10-26 02:43:22.828  5800  5823 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
10-26 02:43:22.828  5800  5823 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
10-26 02:43:22.828  5800  5823 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
10-26 02:43:22.828  5800  5823 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,10-26 02:43:22.831  5800  5800 V BluetoothAdapterState: isTurningOff()=true
10-26 02:43:22.831  5800  5800 V BluetoothAdapterState: isTurningOn()=false
10-26 02:43:22.831  5800  5800 V BluetoothAdapterState: isBleTurningOn()=false
10-26 02:43:22.831  5800  5800 V BluetoothAdapterState: isBleTurningOff()=false
10-26 02:43:22.831  5800  5800 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
10-26 02:43:22.831  5800  5800 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
10-26 02:43:22.831  5800  5816 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
10-26 02:43:22.832  5800  5800 V BluetoothAdapterState: isTurningOff()=true
10-26 02:43:22.832  5800  5800 V BluetoothAdapterState: isTurningOn()=false
10-26 02:43:22.832  5800  5800 V BluetoothAdapterState: isBleTurningOn()=false
10-26 02:43:22.832  5800  5800 V BluetoothAdapterState: isBleTurningOff()=false
10-26 02:43:22.832  5800  5800 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
10-26 02:43:22.832  5800  5816 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
10-26 02:43:22.833  5800  5800 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
10-26 02:43:22.833  5800  5800 V BluetoothAdapterState: isTurningOff()=true
10-26 02:43:22.833  5800  5800 V BluetoothAdapterState: isTurningOn()=false
10-26 02:43:22.833  5800  5800 V BluetoothAdapterState: isBleTurningOn()=false
10-26 02:43:22.833  5800  5800 V BluetoothAdapterState: isBleTurningOff()=false
,10-26 02:43:22.833  5800  5800 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
10-26 02:43:22.833  5800  5800 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
10-26 02:43:22.834  3545  3545 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
10-26 02:43:22.834  5800  5800 D BluetoothMapService: MAP Service closeService in
10-26 02:43:22.834  5800  5800 V BluetoothAdapterState: isTurningOff()=true
,10-26 02:43:22.834  5800  5800 V BluetoothAdapterState: isTurningOn()=false
10-26 02:43:22.834  5800  5800 V BluetoothAdapterState: isBleTurningOn()=false
10-26 02:43:22.834  5800  5800 V BluetoothAdapterState: isBleTurningOff()=false
10-26 02:43:22.835  5800  5800 D BluetoothMapService: cleanup()
10-26 02:43:22.835  5800  5800 D BluetoothMapService: MAP Service closeService in
10-26 02:43:22.835  5800  5800 V BluetoothAdapterState: isTurningOff()=true
10-26 02:43:22.835  5800  5800 V BluetoothAdapterState: isTurningOn()=false
10-26 02:43:22.835  5800  5800 V BluetoothAdapterState: isBleTurningOn()=false
10-26 02:43:22.835  5800  5800 V BluetoothAdapterState: isBleTurningOff()=false
10-26 02:43:22.835  5800  5812 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
10-26 02:43:22.836  5800  5812 D BluetoothAdapterProperties: Setting state to 15
,10-26 02:43:22.836  5800  5812 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
10-26 02:43:22.836  5800  5812 I BluetoothAdapterState: Entering BleOnState
,10-26 02:43:22.838  5685  5698 D BluetoothPan: onBluetoothStateChange on: false
10-26 02:43:22.839  3128  3128 D BluetoothPbap: Proxy object disconnected
10-26 02:43:22.839  3128  3128 D PbapServerProfile: Bluetooth service disconnected
,10-26 02:43:22.839   926   943 D BluetoothHeadset: onBluetoothStateChange: up=false
10-26 02:43:22.839   926   943 D BluetoothHeadset: onBluetoothStateChange: up=false
10-26 02:43:22.840  5685  5696 D BluetoothPbap: onBluetoothStateChange: up=false
10-26 02:43:22.840  3128  3988 D BluetoothMap: onBluetoothStateChange: up=false
10-26 02:43:22.841   926   943 D BluetoothHeadset: onBluetoothStateChange: up=false
10-26 02:43:22.841  3128  3143 D BluetoothHeadset: onBluetoothStateChange: up=false
10-26 02:43:22.841  5685  5698 D BluetoothA2dp: onBluetoothStateChange: up=false
,10-26 02:43:22.842  3128  3986 D BluetoothInputDevice: onBluetoothStateChange: up=false
10-26 02:43:22.843   926   943 D BluetoothA2dp: onBluetoothStateChange: up=false
10-26 02:43:22.843  5685  5696 D BluetoothMap: onBluetoothStateChange: up=false
10-26 02:43:22.843  3774  3804 D BluetoothHeadset: onBluetoothStateChange: up=false
10-26 02:43:22.843  5685  5698 D BluetoothInputDevice: onBluetoothStateChange: up=false
10-26 02:43:22.844  3128  3146 D BluetoothPbap: onBluetoothStateChange: up=false
10-26 02:43:22.844  5685  5696 D BluetoothHeadset: onBluetoothStateChange: up=false
10-26 02:43:22.844  3128  3988 D BluetoothPan: onBluetoothStateChange on: false
,10-26 02:43:22.845  3128  3143 D BluetoothA2dp: onBluetoothStateChange: up=false
10-26 02:43:22.845  5800  5812 D BluetoothAdapterState: Current state: BLE ON, message: 20
10-26 02:43:22.845  5800  5812 D BluetoothAdapterProperties: Setting state to 16
10-26 02:43:22.845  5800  5812 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
10-26 02:43:22.846  5800  5812 D BluetoothAdapterProperties: onBleDisable
10-26 02:43:22.846  5800  5812 I BluetoothAdapterState: Entering PendingCommandState
,10-26 02:43:22.846  5800  5813 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
10-26 02:43:22.848  5800  5823 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
10-26 02:43:22.848  5800  5823 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
10-26 02:43:22.849  5800  5816 D BluetoothAdapterProperties: Scan Mode:20
,10-26 02:43:22.850  5627  5627 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-26 02:43:22.852  5627  5627 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-26 02:43:22.853  5627  5627 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-26 02:43:22.854  5627  5627 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-26 02:43:22.856  5627  5627 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-26 02:43:22.857  5627  5627 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-26 02:43:22.859  5685  5685 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,10-26 02:43:22.865  3545  3545 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,10-26 02:43:22.869  5685  5685 D DockEventReceiver: finishStartingService: stopping service
,10-26 02:43:23.060  5800  5816 I bt_hci  : shut_down
,10-26 02:43:23.070  5800  5820 D bt_hwcfg: hw_epilog_process
10-26 02:43:23.071  5800  5820 I bt_vendor: low_power_mode_cb
,10-26 02:43:23.074  5800  5820 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,10-26 02:43:23.074  5800  5820 I bt_vendor: epilog_cb
10-26 02:43:23.074  5800  5820 I bt_hci  : epilog_finished_callback
,10-26 02:43:23.078  5800  5816 I bt_hci_h4: hal_close
,10-26 02:43:23.079  5800  5816 I bt_userial_vendor: device fd = 54 close
,10-26 02:43:23.188  5800  5813 D bt_stack_manager: event_shut_down_stack finished.
,10-26 02:43:23.190  5800  5812 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,10-26 02:43:23.195  5800  5812 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,10-26 02:43:23.195  5800  5800 D BtGatt.DebugUtils: handleDebugAction() action=null
10-26 02:43:23.196  5800  5800 D BtGatt.GattService: Received stop request...Stopping profile...
,10-26 02:43:23.196  5800  5800 D BtGatt.GattService: stop()
10-26 02:43:23.196  5800  5800 D BtGatt.AdvertiseManager: advertise clients cleared
,10-26 02:43:23.200  5800  5800 V BluetoothAdapterState: isTurningOff()=false
,10-26 02:43:23.200  5800  5800 V BluetoothAdapterState: isTurningOn()=false
10-26 02:43:23.201  5800  5800 V BluetoothAdapterState: isBleTurningOn()=false
10-26 02:43:23.201  5800  5800 V BluetoothAdapterState: isBleTurningOff()=true
,10-26 02:43:23.201  5800  5812 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
10-26 02:43:23.202  5800  5812 D BluetoothAdapterProperties: Setting state to 10
,10-26 02:43:23.202  5800  5812 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
10-26 02:43:23.203  5800  5812 I BluetoothAdapterState: Entering OffState
,10-26 02:43:23.206   926   943 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,10-26 02:43:23.221  5800  5800 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,10-26 02:43:23.221  5800  5800 W BluetoothSdpJni: Cleaning up Bluetooth Health object
10-26 02:43:23.221  5800  5813 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,10-26 02:43:23.224  5800  5800 I BluetoothServiceJni: cleanupNative: return from cleanup
,10-26 02:43:23.229  5800  5800 I art     : System.exit called, status: 0
,10-26 02:43:23.229  5800  5800 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,10-26 02:43:23.257   926  3831 I ActivityManager: Process com.android.bluetooth (pid 5800) has died
,10-26 02:43:23.329   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,10-26 02:43:24.329   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,10-26 02:43:25.330   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,10-26 02:43:26.116  3545  3545 I ConfigService: onDestroy
,10-26 02:43:26.331   534   534 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,10-26 02:43:27.769  5627  5674 D io.jxcore.node.ConnectivityMonitor: stop
,10-26 02:43:27.769  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-26 02:43:27.773  5627  5674 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,10-26 02:43:27.774  5627  5674 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@c1f566d removed from the list
10-26 02:43:27.774  5627  5674 D io.jxcore.node.ConnectivityMonitor: stop
10-26 02:43:27.774  5627  5674 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-26 02:43:27.774  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-26 02:43:27.777  5627  5674 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-26 02:43:27.777  5627  5674 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1ae1b33 added. We now have 4 listener(s)
10-26 02:43:27.777  5627  5674 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,10-26 02:43:27.779  5627  5674 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-26 02:43:27.779  5627  5674 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1ae1b33 removed from the list
10-26 02:43:27.779  5627  5674 D io.jxcore.node.ConnectivityMonitor: stop
,10-26 02:43:27.780  5627  5674 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-26 02:43:27.780  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-26 02:43:27.784  5627  5674 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,10-26 02:43:27.785  5627  5674 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@fdd4ef0 added. We now have 4 listener(s)
10-26 02:43:27.786  5627  5674 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,10-26 02:43:32.795  5627  5674 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-26 02:43:32.827   926   943 I ActivityManager: Start proc 5858:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,10-26 02:43:32.910  5858  5858 D AdapterServiceConfig: Adding HeadsetService
,10-26 02:43:32.910  5858  5858 D AdapterServiceConfig: Adding A2dpService
10-26 02:43:32.910  5858  5858 D AdapterServiceConfig: Adding HidService
10-26 02:43:32.911  5858  5858 D AdapterServiceConfig: Adding HealthService
10-26 02:43:32.911  5858  5858 D AdapterServiceConfig: Adding PanService
,10-26 02:43:32.911  5858  5858 D AdapterServiceConfig: Adding GattService
10-26 02:43:32.911  5858  5858 D AdapterServiceConfig: Adding BluetoothMapService
10-26 02:43:32.911  5858  5858 D AdapterServiceConfig: Adding SapService
,10-26 02:43:32.922   926   943 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@52cb005:true
,10-26 02:43:32.922  5858  5858 D BluetoothAdapterState: make() - Creating AdapterState
,10-26 02:43:32.925  5858  5858 I bt_bluedroid: init
,10-26 02:43:32.925  5858  5870 I BluetoothAdapterState: Entering OffState
,10-26 02:43:32.927  5858  5871 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,10-26 02:43:32.927  5858  5871 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
,10-26 02:43:32.927  5858  5871 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
10-26 02:43:32.928  5858  5871 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
10-26 02:43:32.928  5858  5858 I bt_bluedroid: get_profile_interface socket
,10-26 02:43:32.930  5858  5874 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:D4
,10-26 02:43:32.931  5858  5858 I bt_bluedroid: get_profile_interface sdp
10-26 02:43:32.932  5858  5874 D BluetoothAdapterProperties: Name is: Nexus 6P
,10-26 02:43:32.936  5858  5869 I bt_bluedroid: config_hci_snoop_log
10-26 02:43:32.936   926   943 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,10-26 02:43:32.941  5858  5870 D BluetoothAdapterState: Current state: OFF, message: 0
,10-26 02:43:32.941  5858  5870 D BluetoothAdapterProperties: Setting state to 14
10-26 02:43:32.941  5858  5870 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
10-26 02:43:32.942  5858  5870 D BluetoothBondStateMachine: make
10-26 02:43:32.944  5858  5875 I BluetoothBondStateMachine: StableState(): Entering Off State
,10-26 02:43:32.947  5858  5870 I BluetoothAdapterState: Entering PendingCommandState
,10-26 02:43:32.948  5858  5858 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,10-26 02:43:32.950  5858  5858 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@582acd5
10-26 02:43:32.951  5858  5858 D BtGatt.DebugUtils: handleDebugAction() action=null
10-26 02:43:32.951  5858  5858 D BtGatt.GattService: Received start request. Starting profile...
10-26 02:43:32.951  5858  5858 D BtGatt.GattService: start()
,10-26 02:43:32.951  5858  5858 I bt_bluedroid: get_profile_interface gatt
,10-26 02:43:32.952  5858  5858 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@582acd5
10-26 02:43:32.952  5858  5858 D BtGatt.AdvertiseManager: advertise manager created
,10-26 02:43:32.957  5858  5858 V BluetoothAdapterState: isTurningOff()=false
10-26 02:43:32.958  5858  5858 V BluetoothAdapterState: isTurningOn()=false
10-26 02:43:32.958  5858  5858 V BluetoothAdapterState: isBleTurningOn()=true
10-26 02:43:32.958  5858  5858 V BluetoothAdapterState: isBleTurningOff()=false
,10-26 02:43:32.958  5858  5870 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
10-26 02:43:32.959  5858  5870 I bt_bluedroid: bt_bluedroid
10-26 02:43:32.959  5858  5871 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,10-26 02:43:32.960  5858  5871 I bt_hci  : start_up
,10-26 02:43:32.965  5858  5871 I bt_vendor: alloc value 0xf412d871
10-26 02:43:32.965  5858  5871 I bt_vendor: init
10-26 02:43:32.965  5858  5871 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
10-26 02:43:32.965  5858  5871 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,10-26 02:43:33.074  5858  5871 D bt_hci  : start_up starting async portion
,10-26 02:43:33.074  5858  5878 I bt_hci  : event_finish_startup
10-26 02:43:33.075  5858  5878 I bt_hci_h4: hal_open
,10-26 02:43:33.076  5858  5878 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,10-26 02:43:33.077  5879  5879 W irq/448-msm_hs_: type=1400 audit(0.0:118): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,10-26 02:43:33.081  5858  5878 I bt_userial_vendor: device fd = 54 open
,10-26 02:43:33.098  5858  5878 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,10-26 02:43:33.103  5858  5878 D bt_hwcfg: Chipset BCM4358A3
,10-26 02:43:33.103  5858  5878 D bt_hwcfg: Target name = [BCM4358A3]
10-26 02:43:33.104  5858  5878 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,10-26 02:43:33.527  5858  5878 I bt_hwcfg: bt vendor lib: set UART baud 115200
,10-26 02:43:33.527  5858  5878 D bt_hwcfg: Settlement delay -- 100 ms
,10-26 02:43:33.527  5858  5878 I bt_hwcfg: Setting fw settlement delay to 100 
,10-26 02:43:33.661  5858  5878 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,10-26 02:43:33.662  5858  5878 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:D4
,10-26 02:43:33.664  5858  5878 I bt_hwcfg: vendor lib fwcfg completed
10-26 02:43:33.664  5858  5878 I bt_vendor: firmware callback
,10-26 02:43:33.664  5858  5878 I bt_hci  : firmware_config_callback
,10-26 02:43:33.672  5858  5881 I bt_btu  : btu_task pending for preload complete event
,10-26 02:43:33.673  5858  5881 I bt_btu_task: Bluetooth chip preload is complete
10-26 02:43:33.673  5858  5881 I bt_btu  : btu_task received preload complete event
,10-26 02:43:33.681  5858  5881 I         : BTE_InitTraceLevels -- TRC_HCI
,10-26 02:43:33.681  5858  5881 I         : BTE_InitTraceLevels -- TRC_L2CAP
,10-26 02:43:33.681  5858  5881 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,10-26 02:43:33.681  5858  5881 I         : BTE_InitTraceLevels -- TRC_AVDT
10-26 02:43:33.681  5858  5881 I         : BTE_InitTraceLevels -- TRC_AVRC
10-26 02:43:33.681  5858  5881 I         : BTE_InitTraceLevels -- TRC_A2D
10-26 02:43:33.681  5858  5881 I         : BTE_InitTraceLevels -- TRC_BNEP
,10-26 02:43:33.681  5858  5881 I         : BTE_InitTraceLevels -- TRC_BTM
10-26 02:43:33.682  5858  5881 I         : BTE_InitTraceLevels -- TRC_GAP
10-26 02:43:33.682  5858  5881 I         : BTE_InitTraceLevels -- TRC_PAN
10-26 02:43:33.682  5858  5881 I         : BTE_InitTraceLevels -- TRC_SDP
,10-26 02:43:33.682  5858  5881 I         : BTE_InitTraceLevels -- TRC_GATT
10-26 02:43:33.682  5858  5881 I         : BTE_InitTraceLevels -- TRC_SMP
10-26 02:43:33.683  5858  5881 I         : BTE_InitTraceLevels -- TRC_BTAPP
,10-26 02:43:33.683  5858  5881 I         : BTE_InitTraceLevels -- TRC_BTIF
,10-26 02:43:33.767  5858  5881 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf40ab549
10-26 02:43:33.767  5858  5881 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf40ab549 
,10-26 02:43:33.789  5858  5874 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,10-26 02:43:33.790  5858  5874 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,10-26 02:43:33.791  5858  5874 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:D4
,10-26 02:43:33.794  5858  5874 D BluetoothAdapterProperties: Name is: Nexus 6P
,10-26 02:43:33.796  5858  5874 D BluetoothAdapterProperties: Scan Mode:20
10-26 02:43:33.796  5858  5874 D BluetoothAdapterProperties: Discoverable Timeout:120
,10-26 02:43:33.797  5858  5874 D bt_hci  : do_postload posting postload work item
10-26 02:43:33.797  5858  5878 I bt_hci  : event_postload
,10-26 02:43:33.797  5858  5878 I bt_vendor: sco_config_cb
10-26 02:43:33.797  5858  5878 I bt_hci  : sco_config_callback postload finished.
10-26 02:43:33.799  5858  5874 D bt_bte_conf: Device ID record 1 : primary
,10-26 02:43:33.800  5858  5874 D bt_bte_conf:   vendorId            = 000f
10-26 02:43:33.800  5858  5874 D bt_bte_conf:   vendorIdSource      = 0001
10-26 02:43:33.800  5858  5874 D bt_bte_conf:   product             = 1200
10-26 02:43:33.800  5627  5627 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-26 02:43:33.800  5858  5874 D bt_bte_conf:   version             = 1436
10-26 02:43:33.800  5858  5874 D bt_bte_conf:   clientExecutableURL = 
10-26 02:43:33.800  5858  5874 D bt_bte_conf:   serviceDescription  = 
10-26 02:43:33.800  5858  5874 D bt_bte_conf:   documentationURL    = 
,10-26 02:43:33.800  5858  5874 D bt_bte_conf: bte_load_did_conf no section named DID2.
10-26 02:43:33.801  5858  5871 D bt_stack_manager: event_start_up_stack finished
10-26 02:43:33.802  5858  5870 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
10-26 02:43:33.803  5858  5870 D BluetoothAdapterProperties: Setting state to 15
,10-26 02:43:33.803  5858  5870 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
10-26 02:43:33.803  5627  5627 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-26 02:43:33.806  5858  5870 I BluetoothAdapterState: Entering BleOnState
10-26 02:43:33.811  5858  5870 D BluetoothAdapterState: Current state: BLE ON, message: 1
10-26 02:43:33.811  5858  5870 D BluetoothAdapterProperties: Setting state to 11
10-26 02:43:33.811  5858  5870 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,10-26 02:43:33.813  5858  5878 I bt_vendor: low_power_mode_cb
10-26 02:43:33.818  5858  5858 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@582acd5
10-26 02:43:33.819  5858  5858 D HeadsetService: Received start request. Starting profile...
10-26 02:43:33.823  5627  5627 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-26 02:43:33.826  5627  5627 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-26 02:43:33.829  5858  5858 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,10-26 02:43:33.829  5858  5858 D HeadsetStateMachine: make
,10-26 02:43:33.839  5858  5870 I BluetoothAdapterState: Entering PendingCommandState
,10-26 02:43:33.839  5858  5858 D HeadsetStateMachine: max_hf_connections = 1
10-26 02:43:33.840  5858  5858 I bt_bluedroid: get_profile_interface handsfree
10-26 02:43:33.840  5858  5874 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
10-26 02:43:33.840  5858  5874 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
,10-26 02:43:33.843  5858  5858 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@582acd5
10-26 02:43:33.843  5858  5858 D A2dpService: Received start request. Starting profile...
10-26 02:43:33.844  5858  5858 I BluetoothAvrcpServiceJni: classInitNative: succeeds
10-26 02:43:33.844  5858  5858 I bt_bluedroid: get_profile_interface avrcp
,10-26 02:43:33.852  5858  5858 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,10-26 02:43:33.852  5858  5858 I BluetoothA2dpServiceJni: classInitNative: succeeds
10-26 02:43:33.852  5858  5858 D A2dpStateMachine: make
,10-26 02:43:33.854  5858  5858 I bt_bluedroid: get_profile_interface a2dp
,10-26 02:43:33.854  5858  5874 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,10-26 02:43:33.856  5858  5858 I BluetoothHidServiceJni: classInitNative: succeeds
10-26 02:43:33.857  5858  5890 D A2dpStateMachine: Enter Disconnected: -2
,10-26 02:43:33.857  5858  5858 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@582acd5
10-26 02:43:33.858  5858  5858 D HidService: Received start request. Starting profile...
10-26 02:43:33.858  5858  5858 I bt_bluedroid: get_profile_interface hidhost
,10-26 02:43:33.858  5858  5874 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf408c56d
10-26 02:43:33.859  5858  5874 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
10-26 02:43:33.858  5858  5858 D HidService: setHidService(): set to: null
10-26 02:43:33.863  3545  3545 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,10-26 02:43:33.863  5858  5858 I BluetoothHealthServiceJni: classInitNative: succeeds
,10-26 02:43:33.864  5858  5858 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@582acd5
10-26 02:43:33.864  5858  5858 D HealthService: Received start request. Starting profile...
,10-26 02:43:33.865  5858  5858 I bt_bluedroid: get_profile_interface health
,10-26 02:43:33.866  5858  5858 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,10-26 02:43:33.867  5858  5858 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@582acd5
,10-26 02:43:33.868  5858  5858 D PanService: Received start request. Starting profile...
,10-26 02:43:33.868  5858  5858 D BluetoothPanServiceJni: initializeNative(L110): pan
10-26 02:43:33.868  5858  5858 I bt_bluedroid: get_profile_interface pan
,10-26 02:43:33.868  5858  5874 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,10-26 02:43:33.870  5858  5858 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@582acd5
,10-26 02:43:33.871  5858  5858 D BluetoothMapService: Received start request. Starting profile...
10-26 02:43:33.871  5858  5858 D BluetoothMapService: start()
,10-26 02:43:33.874  5858  5858 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,10-26 02:43:33.875  5858  5858 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
,10-26 02:43:33.875  5858  5858 D BluetoothMapAppObserver: createReceiver()
,10-26 02:43:33.876  5858  5858 D BluetoothMapAppObserver: initObservers()
10-26 02:43:33.876  5858  5858 D BluetoothMapAppObserver: getEnabledAccountItems()
,10-26 02:43:33.883  5858  5858 V SapService: SapBinder()
,10-26 02:43:33.883  5858  5858 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@582acd5
,10-26 02:43:33.885  5858  5858 D SapService: Received start request. Starting profile...
,10-26 02:43:33.885  5858  5858 V SapService: start()
,10-26 02:43:33.886  5858  5858 V BluetoothAdapterState: isTurningOff()=false
,10-26 02:43:33.886  5858  5858 V BluetoothAdapterState: isTurningOn()=true
10-26 02:43:33.886  5858  5858 V BluetoothAdapterState: isBleTurningOn()=false
10-26 02:43:33.886  5858  5858 V BluetoothAdapterState: isBleTurningOff()=false
10-26 02:43:33.886  5858  5858 V BluetoothAdapterState: isTurningOff()=false
10-26 02:43:33.886  5858  5858 V BluetoothAdapterState: isTurningOn()=true
10-26 02:43:33.887  5858  5858 V BluetoothAdapterState: isBleTurningOn()=false
10-26 02:43:33.887  5858  5858 V BluetoothAdapterState: isBleTurningOff()=false
10-26 02:43:33.887  5858  5888 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=3
,10-26 02:43:33.887  5858  5858 V BluetoothAdapterState: isTurningOff()=false
10-26 02:43:33.887  5858  5858 V BluetoothAdapterState: isTurningOn()=true
10-26 02:43:33.887  5858  5858 V BluetoothAdapterState: isBleTurningOn()=false
10-26 02:43:33.887  5858  5858 V BluetoothAdapterState: isBleTurningOff()=false
10-26 02:43:33.887  5858  5858 V BluetoothAdapterState: isTurningOff()=false
10-26 02:43:33.887  5858  5858 V BluetoothAdapterState: isTurningOn()=true
10-26 02:43:33.887  5858  5858 V BluetoothAdapterState: isBleTurningOn()=false
10-26 02:43:33.888  5858  5858 V BluetoothAdapterState: isBleTurningOff()=false
10-26 02:43:33.888  5858  5858 V BluetoothAdapterState: isTurningOff()=false
10-26 02:43:33.888  5858  5858 V BluetoothAdapterState: isTurningOn()=true
10-26 02:43:33.888  5858  5858 V BluetoothAdapterState: isBleTurningOn()=false
10-26 02:43:33.888  5858  5858 V BluetoothAdapterState: isBleTurningOff()=false
10-26 02:43:33.888  5858  5858 V BluetoothAdapterState: isTurningOff()=false
,10-26 02:43:33.888  5858  5858 V BluetoothAdapterState: isTurningOn()=true
10-26 02:43:33.888  5858  5858 V BluetoothAdapterState: isBleTurningOn()=false
10-26 02:43:33.888  5858  5858 V BluetoothAdapterState: isBleTurningOff()=false
10-26 02:43:33.889  5858  5858 V BluetoothAdapterState: isTurningOff()=false
10-26 02:43:33.889  5858  5858 V BluetoothAdapterState: isTurningOn()=true
10-26 02:43:33.889  5858  5858 V BluetoothAdapterState: isBleTurningOn()=false
10-26 02:43:33.889  5858  5858 V BluetoothAdapterState: isBleTurningOff()=false
,10-26 02:43:33.889  5858  5870 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
10-26 02:43:33.889  5858  5870 D BluetoothAdapterProperties: ScanMode =  20
10-26 02:43:33.889  5858  5870 D BluetoothAdapterProperties: State =  11
10-26 02:43:33.890  5858  5870 D BluetoothAdapterProperties: Setting state to 12
,10-26 02:43:33.890  5858  5870 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
10-26 02:43:33.890  5858  5870 I BluetoothAdapterState: Entering OnState
10-26 02:43:33.890  5858  5874 D BluetoothAdapterProperties: Scan Mode:21
10-26 02:43:33.890  5685  5698 D BluetoothPan: onBluetoothStateChange on: true
10-26 02:43:33.890  5858  5874 D BluetoothAdapterProperties: Discoverable Timeout:120
10-26 02:43:33.891  5627  5627 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
,10-26 02:43:33.892   926   943 D BluetoothHeadset: onBluetoothStateChange: up=true
10-26 02:43:33.892   926   943 D BluetoothHeadset: onBluetoothStateChange: up=true
10-26 02:43:33.893  5685  5696 D BluetoothPbap: onBluetoothStateChange: up=true
10-26 02:43:33.895  5627  5627 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-26 02:43:33.895  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-26 02:43:33.895  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-26 02:43:33.895  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-26 02:43:33.895  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-26 02:43:33.895  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-26 02:43:33.895  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-26 02:43:33.895  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-26 02:43:33.895  3128  3146 D BluetoothMap: onBluetoothStateChange: up=true
10-26 02:43:33.896   926   943 D BluetoothHeadset: onBluetoothStateChange: up=true
,10-26 02:43:33.896  3128  3988 D BluetoothHeadset: onBluetoothStateChange: up=true
10-26 02:43:33.897  3128  3128 D BluetoothMap: Proxy object connected
10-26 02:43:33.897  5685  5698 D BluetoothA2dp: onBluetoothStateChange: up=true
10-26 02:43:33.897  5627  5627 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
10-26 02:43:33.897  3128  3128 D MapProfile: Bluetooth service connected
10-26 02:43:33.897  3128  3128 D BluetoothMap: getConnectedDevices()
,10-26 02:43:33.899  3128  3146 D BluetoothInputDevice: onBluetoothStateChange: up=true
10-26 02:43:33.901  5627  5627 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-26 02:43:33.901  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-26 02:43:33.901  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-26 02:43:33.901  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-26 02:43:33.901  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-26 02:43:33.901  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-26 02:43:33.901  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-26 02:43:33.901  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-26 02:43:33.901   926   943 D BluetoothA2dp: onBluetoothStateChange: up=true
10-26 02:43:33.901   926   926 D BluetoothA2dp: Proxy object connected
10-26 02:43:33.901  5685  5698 D BluetoothMap: onBluetoothStateChange: up=true
10-26 02:43:33.902  5627  5627 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
10-26 02:43:33.902  5685  5685 D BluetoothPan: BluetoothPAN Proxy object connected
10-26 02:43:33.902  5685  5685 D PanProfile: Bluetooth service connected
10-26 02:43:33.902  5858  5858 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
10-26 02:43:33.902  5685  5685 D BluetoothA2dp: Proxy object connected
10-26 02:43:33.903  5858  5858 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
10-26 02:43:33.904  3774  3995 D BluetoothHeadset: onBluetoothStateChange: up=true
10-26 02:43:33.904  5858  5858 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
10-26 02:43:33.904  5685  5696 D BluetoothInputDevice: onBluetoothStateChange: up=true
,10-26 02:43:33.906  5858  5858 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
10-26 02:43:33.906  3128  3988 D BluetoothPbap: onBluetoothStateChange: up=true
10-26 02:43:33.907  5858  5858 D ObexServerSockets: Succeed to create listening sockets 
10-26 02:43:33.907  5858  5858 D ObexServerSockets0: startAccept()
10-26 02:43:33.907  5858  5858 D ObexServerSockets0: prepareForNewConnect()
10-26 02:43:33.907  5685  5698 D BluetoothHeadset: onBluetoothStateChange: up=true
10-26 02:43:33.908  3128  3986 D BluetoothPan: onBluetoothStateChange on: true
10-26 02:43:33.908  5858  5858 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
10-26 02:43:33.909  5858  5858 D BluetoothSdpJni: SDP Create record success - handle: 0
10-26 02:43:33.909  5858  5896 D ObexServerSockets0: Accepting socket connection...
10-26 02:43:33.909  5858  5897 D ObexServerSockets0: Accepting socket connection...
,10-26 02:43:33.910  3128  3128 D BluetoothInputDevice: Proxy object connected
10-26 02:43:33.910  3128  3128 D HidProfile: Bluetooth service connected
10-26 02:43:33.911  3128  3988 D BluetoothA2dp: onBluetoothStateChange: up=true
10-26 02:43:33.911  3128  3128 D BluetoothPan: BluetoothPAN Proxy object connected
10-26 02:43:33.911  3128  3128 D PanProfile: Bluetooth service connected
10-26 02:43:33.913  3128  3128 D BluetoothA2dp: Proxy object connected
10-26 02:43:33.914   926   926 I Telecom : BluetoothPhoneService: queryPhoneState
,10-26 02:43:33.915  5627  5627 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
,10-26 02:43:33.916  5858  5858 D BluetoothMapService: onReceive
10-26 02:43:33.916  5858  5858 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
10-26 02:43:33.916  5858  5858 D BluetoothMapService: STATE_ON
,10-26 02:43:33.916  5627  5627 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-26 02:43:33.918  5858  5899 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
10-26 02:43:33.918  5627  5627 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-26 02:43:33.919  5685  5685 D BluetoothMap: Proxy object connected
,10-26 02:43:33.919  5685  5685 D MapProfile: Bluetooth service connected
10-26 02:43:33.919  5685  5685 D BluetoothMap: getConnectedDevices()
10-26 02:43:33.920  5858  5899 D BluetoothSdpJni: sdpCreateSapsRecordNative:
10-26 02:43:33.920  5858  5899 D BluetoothSdpJni: SDP Create record success - handle: 1
10-26 02:43:33.921  5685  5685 D BluetoothInputDevice: Proxy object connected
10-26 02:43:33.921  5685  5685 D HidProfile: Bluetooth service connected
10-26 02:43:33.926  5685  5685 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,10-26 02:43:33.932  3545  3545 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,10-26 02:43:33.936  5685  5685 D DockEventReceiver: finishStartingService: stopping service
,10-26 02:43:33.939  5858  5858 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,10-26 02:43:33.939  5858  5858 D ObexServerSockets0: prepareForNewConnect()
10-26 02:43:33.941  5858  5901 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
10-26 02:43:33.942  3128  3128 D BluetoothPbap: Proxy object connected
10-26 02:43:33.942  3128  3128 D PbapServerProfile: Bluetooth service connected
10-26 02:43:33.942  5685  5685 D BluetoothPbap: Proxy object connected
10-26 02:43:33.942  5685  5685 D PbapServerProfile: Bluetooth service connected
,10-26 02:43:33.963  5858  5907 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,10-26 02:43:33.965  5858  5907 I BtOppRfcommListener: Accept thread started.
,10-26 02:43:33.994  3128  3986 D BluetoothHeadset: Proxy object connected
,10-26 02:43:33.994  3128  3128 D HeadsetProfile: Bluetooth service connected
10-26 02:43:33.994   926   926 D BluetoothHeadset: Proxy object connected
10-26 02:43:33.994   926   926 D BluetoothHeadset: Proxy object connected
,10-26 02:43:33.994  5685  5698 D BluetoothHeadset: Proxy object connected
,10-26 02:43:33.995  3774  3804 D BluetoothHeadset: Proxy object connected
10-26 02:43:33.995  5685  5685 D HeadsetProfile: Bluetooth service connected
10-26 02:43:33.995   926   926 D BluetoothHeadset: Proxy object connected
10-26 02:43:33.997   926   943 D BluetoothHeadset: Proxy object connected
10-26 02:43:33.997  3128  3143 D BluetoothHeadset: Proxy object connected
10-26 02:43:33.997  3128  3128 D HeadsetProfile: Bluetooth service connected
,10-26 02:43:34.005  3774  3799 D BluetoothHeadset: Proxy object connected
,10-26 02:43:34.008  5685  5696 D BluetoothHeadset: Proxy object connected
,10-26 02:43:34.009  5685  5685 D HeadsetProfile: Bluetooth service connected
,10-26 02:43:36.332   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,10-26 02:43:37.333   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,10-26 02:43:37.813  5627  5674 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-26 02:43:37.813  5627  5674 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-26 02:43:37.813  5627  5674 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-26 02:43:37.813  5627  5674 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-26 02:43:37.813  5627  5674 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-26 02:43:37.813  5627  5674 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-26 02:43:37.813  5627  5674 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-26 02:43:37.813  5627  5674 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,10-26 02:43:37.819  5627  5674 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,10-26 02:43:37.820  5627  5674 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-26 02:43:37.820  5627  5674 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@fdd4ef0 removed from the list
10-26 02:43:37.820  5627  5674 D io.jxcore.node.ConnectivityMonitor: stop
10-26 02:43:37.820  5627  5674 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,10-26 02:43:37.821  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-26 02:43:37.825  5627  5674 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,10-26 02:43:37.826  5627  5674 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@ce7ec69 added. We now have 4 listener(s)
,10-26 02:43:37.826  5627  5674 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,10-26 02:43:37.829   926  3559 D WifiService: setWifiEnabled: false pid=5627, uid=10077
,10-26 02:43:37.829   926  3559 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,10-26 02:43:38.334   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,10-26 02:43:39.337   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,10-26 02:43:40.338   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,10-26 02:43:41.020   926   946 I PowerManagerService: Going to sleep due to screen timeout (uid 1000)...
,10-26 02:43:41.024  3727  3727 W Binder_7: type=1400 audit(0.0:119): avc: denied { ioctl } for path="socket:[31672]" dev="sockfs" ino=31672 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,10-26 02:43:41.027  3727  3727 W Binder_7: type=1400 audit(0.0:120): avc: denied { ioctl } for path="socket:[31672]" dev="sockfs" ino=31672 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,10-26 02:43:41.034  3649  3649 I Keyboard.Facilitator: onFinishInput()
,10-26 02:43:41.046   926   946 I Adreno  : QUALCOMM build                   : 63c06b2, I8366cd0437
10-26 02:43:41.046   926   946 I Adreno  : Build Date                       : 12/06/15
10-26 02:43:41.046   926   946 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
10-26 02:43:41.046   926   946 I Adreno  : Local Branch                     : mybranch17112971
10-26 02:43:41.046   926   946 I Adreno  : Remote Branch                    : quic/LA.BF64.1.2.9_v2
10-26 02:43:41.046   926   946 I Adreno  : Remote Branch                    : NONE
10-26 02:43:41.046   926   946 I Adreno  : Reconstruct Branch               : NOTHING
,10-26 02:43:41.091   382  2457 D PermissionCache: checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (200 us)
,10-26 02:43:41.338   534   534 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,10-26 02:43:41.751  5627  5627 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,10-26 02:43:41.751  5627  5627 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,10-26 02:43:41.799   926   946 I sensors : batch
,10-26 02:43:41.800   926   946 V KeyguardServiceDelegate: onScreenTurnedOff()
,10-26 02:43:41.803  5627  5627 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@755c678 Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@afdd6ee, 16908290=android.view.AbsSavedState$1@afdd6ee}, android:focusedViewId=100}]}]
,10-26 02:43:41.803  5627  5627 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
,10-26 02:43:41.804  5627  5627 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
10-26 02:43:41.804  5627  5627 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
10-26 02:43:41.805   926  2689 I hubconnection: sensorhub said: 'batch 31 flags:0, sampling_rate_Hz:15.00, max_report_latency_us:0'
10-26 02:43:41.809   926   946 E libEGL  : call to OpenGL ES API with no current context (logged once per thread)
,10-26 02:43:41.809   926   946 I sensors : activate
,10-26 02:43:41.810   926   944 I DisplayManagerService: Display device changed state: "Built-in Screen", OFF
,10-26 02:43:41.812   926  2689 I hubconnection: sensorhub said: 'activate 7 enable:0'
,10-26 02:43:41.810   382   382 D SurfaceFlinger: Set power mode=0, type=0 flinger=0x7f8c743c00
10-26 02:43:41.815   382   382 D qdhwcomposer: hwc_setPowerMode: Setting mode 0 on display: 0
,10-26 02:43:42.108   382   479 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0
,10-26 02:43:42.110   382   382 D qdhwcomposer: hwc_setPowerMode: Done setting mode 0 on display 0
,10-26 02:43:42.112   926  3050 D SurfaceControl: Excessive delay in setPowerMode(): 302ms
,10-26 02:43:42.125   926   946 I DreamManagerService: Entering dreamland.
,10-26 02:43:42.126   926   946 I PowerManagerService: Dozing...
,10-26 02:43:42.127   926   941 I DreamController: Starting dream: name=ComponentInfo{com.android.systemui/com.android.systemui.doze.DozeService}, isTest=false, canDoze=true, userId=0
,10-26 02:43:42.157  3766  3766 W Binder_8: type=1400 audit(0.0:121): avc: denied { ioctl } for path="socket:[33071]" dev="sockfs" ino=33071 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,10-26 02:43:42.157  3766  3766 W Binder_8: type=1400 audit(0.0:122): avc: denied { ioctl } for path="socket:[33071]" dev="sockfs" ino=33071 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
10-26 02:43:42.161   926  3559 I sensors : batch
,10-26 02:43:42.162   926  3559 I sensors : activate
,10-26 02:43:42.166   926  2689 I hubconnection: sensorhub said: 'batch 21 flags:0, sampling_rate_Hz:1000.00, max_report_latency_us:0'
,10-26 02:43:42.166   926  2689 I hubconnection: sensorhub said: 'activate 21 enable:1'
,10-26 02:43:42.173   511  3004 D audio_hw_primary: adev_set_parameters: enter: screen_state=on
,10-26 02:43:42.211  3774  4680 D ScreenStateRecorder : ScreenStateRecorderHandler, handleMessage msg.what = 1
,10-26 02:43:42.211  3774  4680 D         : oem_qmi_lib:come into oem_qmi_common_stream_from_modem_len --->modem 
10-26 02:43:42.211  3774  4680 D         : oem_qmi_lib:oem_qmi_cmd: Send to server  passed!!
10-26 02:43:42.212   524  1198 D         : oem-qmi: Connection accepted
10-26 02:43:42.212   524  1198 D         : oem-qmi: Waiting to accept connection
,10-26 02:43:42.219  3774  4680 D         : oem_qmi_lib:output 0
,10-26 02:43:42.219  3774  4680 D         : oem_qmi_lib:rapi_event_type=10057, qmi_ret=0, return_status=1. 
,10-26 02:43:42.222   926   926 I sensors : activate
10-26 02:43:42.223   511  3002 D audio_hw_primary: adev_set_parameters: enter: screen_state=off
,10-26 02:43:42.225   926  2689 I hubconnection: sensorhub said: 'activate 31 enable:0'
,10-26 02:43:42.256  3774  4680 D ScreenStateRecorder : ScreenStateRecorderHandler, handleMessage msg.what = 2
,10-26 02:43:42.256  3774  4680 D         : oem_qmi_lib:come into oem_qmi_common_stream_from_modem_len --->modem 
10-26 02:43:42.256  3774  4680 D         : oem_qmi_lib:oem_qmi_cmd: Send to server  passed!!
10-26 02:43:42.257   524  1198 D         : oem-qmi: Connection accepted
,10-26 02:43:42.257   524  1198 D         : oem-qmi: Waiting to accept connection
,10-26 02:43:42.263  3774  4680 D         : oem_qmi_lib:output 0
,10-26 02:43:42.263  3774  4680 D         : oem_qmi_lib:rapi_event_type=10057, qmi_ret=0, return_status=1. 
,10-26 02:43:42.839  5627  5674 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-26 02:43:42.840   926  3795 D WifiService: setWifiEnabled: true pid=5627, uid=10077
10-26 02:43:42.840   926  3795 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,10-26 02:43:42.849   506   920 D SoftapController: Softap fwReload - Ok
,10-26 02:43:42.854   506   920 D CommandListener: Setting iface cfg
,10-26 02:43:42.854   506   920 D CommandListener: Trying to bring down wlan0
,10-26 02:43:42.857   506   920 D CommandListener: Clearing all IP addresses on wlan0
,10-26 02:43:42.864   926  2990 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,10-26 02:43:43.478   926  2990 D wifi    : set interface wlan0 flags (UP)
,10-26 02:43:43.485   926   943 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,10-26 02:43:43.485   926  2990 I WifiHAL : Initializing wifi
,10-26 02:43:43.485   926  2990 I WifiHAL : Creating socket
,10-26 02:43:43.491   926  2990 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
10-26 02:43:43.491   926  2990 D wifi    : Did set static halHandle = 0x7f64651400
10-26 02:43:43.491   926  2990 D wifi    : halHandle = 0x7f64651400, mVM = 0x7f80c4d140, mCls = 0x201902
,10-26 02:43:43.492   926  2990 D wifi    : array field set
,10-26 02:43:43.493   926  2990 I WifiNative-HAL: interface[0] = wlan0
,10-26 02:43:43.494   926  5918 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=547145192448
,10-26 02:43:43.495   926  5918 D wifi    : waitForHalEvents called, vm = 0x7f80c4d140, obj = 0x201902, env = 0x7f68c0d780
,10-26 02:43:43.547  5919  5919 I wpa_supplicant: Successfully initialized wpa_supplicant
,10-26 02:43:43.596   926  2990 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,10-26 02:43:43.600  5627  5627 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-26 02:43:43.602  5627  5627 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-26 02:43:43.630  5919  5919 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,10-26 02:43:43.636  5919  5919 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,10-26 02:43:43.636  5919  5919 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,10-26 02:43:43.646   926  2990 D WifiConfigStore: Loading config and enabling all networks 
,10-26 02:43:43.650  5627  5627 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-26 02:43:43.650  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-26 02:43:43.650  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-26 02:43:43.650  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-26 02:43:43.650  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-26 02:43:43.650  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-26 02:43:43.650  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-26 02:43:43.650  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,10-26 02:43:43.652  5627  5627 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,10-26 02:43:43.655  5627  5627 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-26 02:43:43.655  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-26 02:43:43.655  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-26 02:43:43.655  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-26 02:43:43.655  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-26 02:43:43.655  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-26 02:43:43.655  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-26 02:43:43.655  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-26 02:43:43.656  5627  5627 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,10-26 02:43:43.661   926  2990 D WifiConfigStore: loaded 0 passpoint configs
,10-26 02:43:43.662   926  2990 W WifiConfigStore: Upgrading network 4 to android.uid.system:1000
,10-26 02:43:43.662   926  2990 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
10-26 02:43:43.662   926  2990 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,10-26 02:43:43.663   926  2990 W WifiConfigStore: Upgrading network 3 to android.uid.system:1000
10-26 02:43:43.663   926  2990 W WifiConfigStore: Upgrading network 2 to android.uid.system:1000
,10-26 02:43:43.663   926  2990 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,10-26 02:43:43.664   926  2990 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 5
10-26 02:43:43.664   926  2990 E WifiConfigStore: found sortedWifiConfigurations : "AndroidAP"WPA_PSK
10-26 02:43:43.664   926  2990 E WifiConfigStore: found sortedWifiConfigurations : "AndroidHotspot2346"WPA_PSK
10-26 02:43:43.664   926  2990 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
10-26 02:43:43.664   926  2990 E WifiConfigStore: found sortedWifiConfigurations : "Thali_internal"WPA_PSK
10-26 02:43:43.664   926  2990 E WifiConfigStore: found sortedWifiConfigurations : "MC"WPA_PSK
,10-26 02:43:43.666   926  2990 D WifiNative-HAL: Setting external_sim to 1
,10-26 02:43:43.666   926  2990 D wifi    : setting dfs flag to true, 0x7f692ff7e0
10-26 02:43:43.666  4302  4302 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
10-26 02:43:43.666   926  2990 D WifiStateMachine: Setting OUI to DA-A1-19
10-26 02:43:43.666   926  2990 D wifi    : setting scan oui 0x7f692ff7e0
10-26 02:43:43.666   926  2990 D WifiHAL : Sending mac address OUI
,10-26 02:43:43.669   926  2990 E native  : do suspend true
,10-26 02:43:43.674   926  2990 D wifi    : android_net_wifi_setLinkLayerStats: 1
10-26 02:43:43.674   926   926 D RttService: SCAN_AVAILABLE : 3
,10-26 02:43:43.674   926  3047 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,10-26 02:43:43.680   506   920 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,10-26 02:43:43.681   506   920 D CommandListener: Setting iface cfg
,10-26 02:43:43.685   926  2973 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '133 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 133 Failed to set address (No such device)'
,10-26 02:43:43.685   926  2973 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,10-26 02:43:43.691   926   941 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=152028 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=5 mControllerEnergyUsed=19 }
,10-26 02:43:43.691   926  2973 D WifiNative-HAL: p2pGetDeviceAddress
,10-26 02:43:43.692   926  2973 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:70
,10-26 02:43:45.792  4062  4452 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,10-26 02:43:46.829  5919  5919 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,10-26 02:43:46.862   926  2990 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,10-26 02:43:46.867   926  2990 D WifiStateMachine: CMD_AUTO_CONNECT sup state DisconnectedState my state DisconnectedState nid=0 roam=3
,10-26 02:43:46.868   926  2990 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,10-26 02:43:46.885   926  2990 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=0
,10-26 02:43:46.922   926  2990 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=0
,10-26 02:43:47.272  5919  5919 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,10-26 02:43:47.305  5919  5919 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,10-26 02:43:47.306  5919  5919 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,10-26 02:43:47.316   926  2990 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,10-26 02:43:47.316   926  2990 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
10-26 02:43:47.316   926  2995 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,10-26 02:43:47.337   926  2990 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,10-26 02:43:47.348   506   920 D CommandListener: Setting iface cfg
,10-26 02:43:47.353   926  2990 D WifiStateMachine: Start Dhcp Watchdog 2
,10-26 02:43:47.356   926  2990 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,10-26 02:43:47.360   926  5933 D DhcpClient: Receive thread started
,10-26 02:43:47.441   926  2990 E native  : do suspend false
,10-26 02:43:47.451   926  5932 D DhcpClient: Broadcasting DHCPDISCOVER
,10-26 02:43:47.464   926  5933 D DhcpClient: Received packet: 60:83:34:25:d7:70 OFFER, ip /192.168.1.111, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172685, domain null
,10-26 02:43:47.465   926  5932 D DhcpClient: Got pending lease: IP address 192.168.1.111/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172685 seconds
,10-26 02:43:47.469   926  5932 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.111 serverid=192.168.1.1
,10-26 02:43:47.482   926  5933 D DhcpClient: Received packet: 60:83:34:25:d7:70 ACK: your new IP /192.168.1.111, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,10-26 02:43:47.483   926  5932 D DhcpClient: Confirmed lease: IP address 192.168.1.111/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,10-26 02:43:47.487   506   920 D CommandListener: Setting iface cfg
,10-26 02:43:47.491   926  2990 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,10-26 02:43:47.495   926  2990 E native  : do suspend true
10-26 02:43:47.496   926  5932 D DhcpClient: Scheduling renewal in 86399s
,10-26 02:43:47.514   926  2990 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,10-26 02:43:47.516   926  2990 D WifiConfigStore: No blacklist allowed without epno enabled
10-26 02:43:47.516   926  2995 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
10-26 02:43:47.518   926  2995 D ConnectivityService: Adding iface wlan0 to network 101
10-26 02:43:47.525   926  2990 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,10-26 02:43:47.563   926  2995 E ConnectivityService: Unexpected mtu value: 0, wlan0
,10-26 02:43:47.564   926  2995 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
,10-26 02:43:47.565   926  2995 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,10-26 02:43:47.567   926  2995 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,10-26 02:43:47.569   926  2995 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,10-26 02:43:47.577   926  2995 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,10-26 02:43:47.582   926  2995 D ConnectivityService: scheduleUnvalidatedPrompt 101
,10-26 02:43:47.582   926  2995 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
10-26 02:43:47.582   926  2995 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
10-26 02:43:47.582   926  2995 D ConnectivityService:    accepting network in place of null
10-26 02:43:47.582   926  2990 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
,10-26 02:43:47.582   926  2990 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
10-26 02:43:47.583   926  2995 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.111/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,10-26 02:43:47.598   926  5931 D NetlinkSocketObserver: NeighborEvent{elapsedMs=155936, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,10-26 02:43:47.608   506   920 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,10-26 02:43:47.628   506   920 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,10-26 02:43:47.631   926  2995 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
10-26 02:43:47.631   926  2995 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,10-26 02:43:47.631  3743  3865 W QCNEJ   : |CORE| network available: 101
,10-26 02:43:47.632   926  2995 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
,10-26 02:43:47.635   926   943 D Tethering: MasterInitialState.processMessage what=3
,10-26 02:43:47.637  3743  3865 W QCNEJ   : |CORE| onAvailable: bind the process to WIFI
,10-26 02:43:47.639  3743  3865 W QCNEJ   : |CORE| newLp: {InterfaceName: wlan0 LinkAddresses: [192.168.1.111/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}
10-26 02:43:47.639  3743  3865 W QCNEJ   : |CORE| curLp: {InterfaceName: wlan0 LinkAddresses: [192.168.1.111/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,10-26 02:43:47.643  5627  5627 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-26 02:43:47.643  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-26 02:43:47.643  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-26 02:43:47.643  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-26 02:43:47.643  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-26 02:43:47.643  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-26 02:43:47.643  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-26 02:43:47.643  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,10-26 02:43:47.645  5627  5627 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,10-26 02:43:47.649  5627  5627 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-26 02:43:47.649  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-26 02:43:47.649  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-26 02:43:47.649  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-26 02:43:47.649  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-26 02:43:47.649  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-26 02:43:47.649  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-26 02:43:47.649  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,10-26 02:43:47.651  5627  5627 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,10-26 02:43:47.656  4956  4977 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
,10-26 02:43:47.656  4956  4977 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
10-26 02:43:47.656  4956  4977 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,1,0,0
10-26 02:43:47.656  4956  4977 E SarControlService: no key has been found,reset the power
10-26 02:43:47.657  4956  5001 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
10-26 02:43:47.657  4956  5001 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
10-26 02:43:47.657  4956  5001 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
10-26 02:43:47.657  4990  4990 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
10-26 02:43:47.657  4990  4990 D QcrilMsgTunnelSocket: [1004] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
10-26 02:43:47.658  3950  3950 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
,10-26 02:43:47.660  4956  5001 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
,10-26 02:43:47.660  4956  5001 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
10-26 02:43:47.660  4956  5001 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
,10-26 02:43:47.660  4990  4990 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
10-26 02:43:47.661  4990  4990 D QcrilMsgTunnelSocket: [1005] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
10-26 02:43:47.662  3717  3717 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
10-26 02:43:47.665  4990  5004 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@71683f4 HexData = [00000000ec03000000000000ffffffff]
10-26 02:43:47.666  4990  5004 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
10-26 02:43:47.666  4990  5004 D QcrilMsgTunnelSocket: [1004] < OEM_HOOK_RAW [null]
10-26 02:43:47.669   926  5930 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.209.78,2a00:1450:400d:803::200e
10-26 02:43:47.669  4990  5004 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@71683f4 HexData = [00000000ed03000000000000ffffffff]
10-26 02:43:47.669  4990  5004 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
10-26 02:43:47.669  4990  5004 D QcrilMsgTunnelSocket: [1005] < OEM_HOOK_RAW [null]
,10-26 02:43:47.670  4990  4990 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
10-26 02:43:47.670  4956  4967 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
10-26 02:43:47.670  3717  3717 D SystemUpdateService: onCreate
10-26 02:43:47.672  4990  4990 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
10-26 02:43:47.672  4956  4966 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
10-26 02:43:47.675  3717  3717 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,10-26 02:43:47.686  3717  3717 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,10-26 02:43:47.691  3717  5390 I iu.UploadsManager: num queued entries: 0
,10-26 02:43:47.691  3717  5390 I iu.UploadsManager: num updated entries: 0
,10-26 02:43:47.694  3717  5943 I SystemUpdateService: active receiver: enabled
,10-26 02:43:47.697  3717  3717 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
10-26 02:43:47.698  3717  3717 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,10-26 02:43:47.701  5747  5747 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,10-26 02:43:47.705  5747  5747 D SprintDMHelper: simOperator: 
,10-26 02:43:47.705  5747  5747 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,10-26 02:43:47.716  3717  5390 I iu.SyncManager: NEXT; no task
,10-26 02:43:47.727   926  5930 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 26 Oct 2016 00:43:47 GMT], X-Android-Received-Millis=[1477442627726], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1477442627696]}
,10-26 02:43:47.727   926  2995 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,10-26 02:43:47.728   926  2995 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation  passed
10-26 02:43:47.728   926  2995 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
10-26 02:43:47.728  3717  5943 I SystemUpdateService: Already downloaded, skipping offpeak checks.
10-26 02:43:47.729   926  2995 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,10-26 02:43:47.741  3717  5943 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,10-26 02:43:47.741  3717  5943 I SystemUpdateService: now status is 0 (complete)
10-26 02:43:47.741  3717  5943 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
10-26 02:43:47.741  3717  5943 I SystemUpdateService: file has been verified
10-26 02:43:47.741  3717  5943 I SystemUpdateService: OTA package size = 21989297
,10-26 02:43:47.748  3717  5943 I SystemUpdateService: showing system update notification
,10-26 02:43:47.758   926   926 V NotificationService: pkg=com.google.android.gms canInterrupt=false intercept=true
,10-26 02:43:47.759  3717  3717 D SystemUpdateService: onDestroy
,10-26 02:43:47.830  4302  5947 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,10-26 02:43:47.854  5627  5674 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-26 02:43:47.854  5627  5674 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-26 02:43:47.854  5627  5674 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-26 02:43:47.854  5627  5674 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-26 02:43:47.854  5627  5674 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-26 02:43:47.854  5627  5674 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-26 02:43:47.854  5627  5674 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-26 02:43:47.854  5627  5674 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,10-26 02:43:47.857  5627  5674 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,10-26 02:43:47.858  5627  5674 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-26 02:43:47.858  5627  5674 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@ce7ec69 removed from the list
10-26 02:43:47.858  5627  5674 D io.jxcore.node.ConnectivityMonitor: stop
10-26 02:43:47.858  5627  5674 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,10-26 02:43:47.858  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-26 02:43:47.862  5627  5674 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
10-26 02:43:47.863  5627  5674 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
10-26 02:43:47.863  3545  5957 D GetConfigurationSnapshotOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
10-26 02:43:47.864  5627  5674 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@755c678 Bundle[{}]
10-26 02:43:47.865  5627  5674 I io.jxcore.node.LifeCycleMonitor: start: OK
,10-26 02:43:47.865  5627  5674 I io.jxcore.node.LifeCycleMonitor: stop: OK
,10-26 02:43:47.866  5627  5674 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
10-26 02:43:47.866  5627  5674 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
10-26 02:43:47.867  5627  5674 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
,10-26 02:43:47.867  5627  5674 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
10-26 02:43:47.873  5627  5674 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 164)
,10-26 02:43:47.874  5627  5674 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
,10-26 02:43:47.874  5627  5674 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 165)
,10-26 02:43:47.876  5627  5674 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,10-26 02:43:47.876  5627  5674 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fa5378f added. We now have 3 listener(s)
,10-26 02:43:47.878  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
,10-26 02:43:47.878  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
10-26 02:43:47.878  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
10-26 02:43:47.878  5627  5674 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-26 02:43:47.878  5627  5674 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7e06a1c added. We now have 4 listener(s)
10-26 02:43:47.878  5627  5674 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,10-26 02:43:47.879  5627  5674 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,10-26 02:43:47.881  5627  5674 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,10-26 02:43:47.888  5627  5674 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-26 02:43:47.888  5627  5674 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-26 02:43:47.888  5627  5674 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-26 02:43:47.888  5627  5674 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-26 02:43:47.888  5627  5674 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-26 02:43:47.888  5627  5674 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-26 02:43:47.888  5627  5674 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-26 02:43:47.888  5627  5674 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,10-26 02:43:47.890  5627  5674 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,10-26 02:43:47.890  5627  5674 D io.jxcore.node.ConnectivityMonitor: start: OK
10-26 02:43:47.890  5627  5674 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
10-26 02:43:47.890  5627  5674 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c7473fa added. We now have 4 listener(s)
10-26 02:43:47.891  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
10-26 02:43:47.891  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,10-26 02:43:47.891  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
10-26 02:43:47.891  5627  5674 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-26 02:43:47.891  5627  5674 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@647bdab added. We now have 5 listener(s)
10-26 02:43:47.891  5627  5674 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
10-26 02:43:47.891  5627  5674 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-26 02:43:47.891  5627  5674 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-26 02:43:47.891  5627  5674 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-26 02:43:47.892  5627  5674 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-26 02:43:47.892  5627  5674 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-26 02:43:47.892  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
10-26 02:43:47.892  5627  5674 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-26 02:43:47.892  5627  5674 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
10-26 02:43:47.892  5627  5627 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-26 02:43:47.892  5627  5674 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fa5378f removed from the list
,10-26 02:43:47.892  5627  5674 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-26 02:43:47.892  5627  5674 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7e06a1c removed from the list
10-26 02:43:47.895  5627  5627 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-26 02:43:47.895  5627  5674 D io.jxcore.node.ConnectivityMonitor: stop
10-26 02:43:47.895  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-26 02:43:47.896  5627  5674 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,10-26 02:43:47.896  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-26 02:43:47.896  5627  5674 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
10-26 02:43:47.897  5627  5674 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
10-26 02:43:47.897  5627  5674 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
10-26 02:43:47.897  5627  5674 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
10-26 02:43:47.897  5627  5674 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-26 02:43:47.897  5627  5674 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-26 02:43:47.897  5627  5674 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-26 02:43:47.897  5627  5674 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7e06a1c not in the list
10-26 02:43:47.897  5627  5674 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-26 02:43:47.897  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-26 02:43:47.897  5627  5674 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
,10-26 02:43:47.898  5627  5674 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
10-26 02:43:47.898  5627  5674 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
10-26 02:43:47.898  5627  5674 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
10-26 02:43:47.898  5627  5674 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-26 02:43:47.898  5627  5674 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-26 02:43:47.898  5627  5674 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-26 02:43:47.898  5627  5674 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@647bdab removed from the list
10-26 02:43:47.898  5627  5674 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,10-26 02:43:47.898  5627  5674 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-26 02:43:47.898  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-26 02:43:47.898  5627  5674 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-26 02:43:47.898  5627  5674 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
10-26 02:43:47.899  5627  5674 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c7473fa removed from the list
10-26 02:43:47.899  5627  5674 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
10-26 02:43:47.899  5627  5674 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5980c08 added. We now have 3 listener(s)
,10-26 02:43:47.900  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
10-26 02:43:47.900  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
10-26 02:43:47.900  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
10-26 02:43:47.900  5627  5674 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,10-26 02:43:47.900  5627  5674 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b97bfa1 added. We now have 4 listener(s)
,10-26 02:43:47.901  5627  5674 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
10-26 02:43:47.901  5627  5674 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
10-26 02:43:47.901  3545  5955 I PhenotypeFlagCommitter: Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
10-26 02:43:47.903  5627  5674 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-26 02:43:47.904  3545  5955 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
10-26 02:43:47.907  5627  5674 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-26 02:43:47.907  5627  5674 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-26 02:43:47.907  5627  5674 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-26 02:43:47.907  5627  5674 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-26 02:43:47.907  5627  5674 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-26 02:43:47.907  5627  5674 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-26 02:43:47.907  5627  5674 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-26 02:43:47.907  5627  5674 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
10-26 02:43:47.910  5627  5674 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
10-26 02:43:47.910  5627  5674 D io.jxcore.node.ConnectivityMonitor: start: OK
10-26 02:43:47.910  5627  5674 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,10-26 02:43:47.910  5627  5674 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4428987 added. We now have 4 listener(s)
10-26 02:43:47.911  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
10-26 02:43:47.911  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
10-26 02:43:47.911  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
10-26 02:43:47.911  5627  5674 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-26 02:43:47.911  5627  5674 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ba5e0b4 added. We now have 5 listener(s)
10-26 02:43:47.911  5627  5674 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
10-26 02:43:47.912  5627  5674 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
10-26 02:43:47.912  5627  5674 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
10-26 02:43:47.912  5627  5674 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,10-26 02:43:47.912  5627  5674 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-26 02:43:47.912  5627  5674 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
10-26 02:43:47.912  5627  5627 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-26 02:43:47.915  5627  5627 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-26 02:43:47.915  5627  5674 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
10-26 02:43:47.915  5627  5674 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
10-26 02:43:47.915  5627  5674 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
10-26 02:43:47.918  5627  5674 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
10-26 02:43:47.919  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
10-26 02:43:47.919  5627  5674 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,10-26 02:43:47.924  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-57,5,main], id: 57
,10-26 02:43:47.924  5627  5674 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
10-26 02:43:47.924  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
10-26 02:43:47.924  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
10-26 02:43:47.924  5627  5674 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
10-26 02:43:47.924  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-57,5,main], id: 57
10-26 02:43:47.925  5627  5674 D BluetoothAdapter: STATE_ON
,10-26 02:43:47.927  5858  5887 D BtGatt.GattService: registerClient() - UUID=ef424e6c-e8aa-425b-9100-daa138de6326
10-26 02:43:47.928  5858  5874 D BtGatt.GattService: onClientRegistered() - UUID=ef424e6c-e8aa-425b-9100-daa138de6326, clientIf=5
10-26 02:43:47.929  5627  5638 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,10-26 02:43:47.930  5858  5868 D BtGatt.GattService: start scan with filters
,10-26 02:43:47.933  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
,10-26 02:43:47.933  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-57,5,main], id: 57
10-26 02:43:47.933  5858  5877 D BtGatt.ScanManager: handling starting scan
10-26 02:43:47.933  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
10-26 02:43:47.933  5627  5674 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[Thread-57,5,main], id: 57
10-26 02:43:47.933  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[Thread-57,5,main], id: 57
10-26 02:43:47.933  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
10-26 02:43:47.933  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
10-26 02:43:47.933  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[Thread-57,5,main], id: 57
10-26 02:43:47.933  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[Thread-57,5,main], id: 57
10-26 02:43:47.933  5627  5674 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,10-26 02:43:47.933  5627  5674 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
10-26 02:43:47.934  5858  5877 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@582acd5
,10-26 02:43:47.936  5627  5674 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
10-26 02:43:47.936  5627  5674 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
10-26 02:43:47.936  5627  5674 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
10-26 02:43:47.936  5627  5674 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
10-26 02:43:47.936  3545  5955 W Uploader:  no longer exists, so no auth token.
10-26 02:43:47.936  5627  5627 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,10-26 02:43:47.936  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[Thread-57,5,main], id: 57
10-26 02:43:47.936  5627  5674 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
10-26 02:43:47.937  5627  5674 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
10-26 02:43:47.938  5627  5674 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
,10-26 02:43:47.940  5627  5674 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
10-26 02:43:47.940  5627  5674 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
10-26 02:43:47.940  5627  5674 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
10-26 02:43:47.940  5627  5674 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
10-26 02:43:47.940  5627  5674 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
10-26 02:43:47.940  5627  5674 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
10-26 02:43:47.940  5627  5674 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-26 02:43:47.940  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
10-26 02:43:47.940  5627  5674 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-26 02:43:47.941  5627  5674 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,10-26 02:43:47.941  5627  5674 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
10-26 02:43:47.941  5627  5674 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,10-26 02:43:47.941  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,10-26 02:43:47.941  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-57,5,main], id: 57
10-26 02:43:47.941  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-57,5,main], id: 57
10-26 02:43:47.941  5627  5674 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
10-26 02:43:47.942  5627  5674 D BluetoothAdapter: STATE_ON
10-26 02:43:47.942  5858  5874 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
10-26 02:43:47.942  5858  5874 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-26 02:43:47.942  5858  5868 D BtGatt.GattService: stopScan() - queue size =1
10-26 02:43:47.942  5858  5877 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
10-26 02:43:47.943  5858  5869 D BtGatt.GattService: unregisterClient() - clientIf=5
10-26 02:43:47.943  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
10-26 02:43:47.944  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-57,5,main], id: 57
10-26 02:43:47.944  3545  5957 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,10-26 02:43:47.944  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
10-26 02:43:47.944  5627  5674 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[Thread-57,5,main], id: 57
10-26 02:43:47.944  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[Thread-57,5,main], id: 57
10-26 02:43:47.944  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
10-26 02:43:47.944  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
10-26 02:43:47.944  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[Thread-57,5,main], id: 57
10-26 02:43:47.944  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[Thread-57,5,main], id: 57
10-26 02:43:47.944  5627  5674 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
10-26 02:43:47.944  5627  5674 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
10-26 02:43:47.945  5627  5674 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
10-26 02:43:47.945  5627  5674 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
10-26 02:43:47.945  5627  5674 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
10-26 02:43:47.945  5627  5674 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
10-26 02:43:47.945  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[Thread-57,5,main], id: 57
10-26 02:43:47.945  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-57,5,main], id: 57
10-26 02:43:47.945  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-57,5,main], id: 57
10-26 02:43:47.945  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
10-26 02:43:47.946  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-57,5,main], id: 57
10-26 02:43:47.946  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finishedCurrent thread: Thread[Thread-57,5,main], id: 57
10-26 02:43:47.946  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-57,5,main], id: 57
10-26 02:43:47.946  5627  5674 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
10-26 02:43:47.946  5627  5674 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
10-26 02:43:47.946  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
10-26 02:43:47.946  5627  5674 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
10-26 02:43:47.947  5858  5874 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
10-26 02:43:47.947  5858  5874 D BtGatt.ScanManager: callback don,e for clientIf - 5 status - 0
10-26 02:43:47.948  5627  5674 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
10-26 02:43:47.948  5858  5877 D BtGatt.ScanManager: Starting BLE batch scan
10-26 02:43:47.948  5627  5674 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
10-26 02:43:47.948  5858  5877 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
10-26 02:43:47.948  5627  5674 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
10-26 02:43:47.948  5627  5627 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-26 02:43:47.948  5627  5627 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-26 02:43:47.948  5627  5627 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
10-26 02:43:47.950  5627  5674 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-26 02:43:47.950  5627  5674 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-26 02:43:47.950  5627  5674 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-26 02:43:47.950  5627  5674 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-26 02:43:47.950  5627  5674 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-26 02:43:47.951  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
10-26 02:43:47.951  5627  5674 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-26 02:43:47.951  5627  5674 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
10-26 02:43:47.951  5627  5674 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5980c08 removed from the list
10-26 02:43:47.951  5627  5674 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-26 02:43:47.951  5627  5674 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b97bfa1 removed from the list
10-26 02:43:47.951  5627  5674 D io.jxcore.node.ConnectivityMonitor: stop
10-26 02:43:47.951  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-26 02:43:47.951  5627  5674 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-26 02:43:47.952  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-26 02:43:47.952  5627  5674 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
10-26 02:43:47.953  5627  5674 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
10-26 02:43:47.953  5627  5674 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
10-26 02:43:47.953  5627  5674 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
10-26 02:43:47.953  5627  5674 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-26 02:43:47.953  5627  5674 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-26 02:43:47.953  5627  5674 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-26 02:43:47.953  5627  5674 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b97bfa1 not in the list
10-26 02:43:47.953  5627  5674 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-26 02:43:47.953  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-26 02:43:47.953  5627  5674 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
10-26 02:43:47.954  5627  5674 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
10-26 02:43:47.955  5627  5674 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
10-26 02:43:47.955  5627  5674 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
10-26 02:43:47.955  5627  5674 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-26 02:43:47.955  5627  5674 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-26 02:43:47.955  5627  5674 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-26 02:43:47.955  5627  5674 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ba5e0b4 removed from the list
10-26 02:43:47.955  5627  5674 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-26 02:43:47.955  5627  5674 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-26 02:43:47.955  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-26 02:43:47.955  5627  5674 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-26 02:43:47.955  5627  5674 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
10-26 02:43:47.955  5627  5674 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4428987 removed from the list
10-26 02:43:47.956  5627  5674 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
10-26 02:43:47.956  5627  5674 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@31a5420 added. We now have 3 listener(s)
10-26 02:43:47.957  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
10-26 02:43:47.957  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
10-26 02:43:47.957  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
10-26 02:43:47.957  5627  5674 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-26 02:43:47.957  5627  5674 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@897c1d9 added. We now have 4 listener(s)
10-26 02:43:47.957  5627  5674 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
10-26 02:43:47.958  5627  5674 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
10-26 02:43:47.959  5858  5874 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
10-26 02:43:47.959  5858  5874 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-26 02:43:47.961  5627  5674 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-26 02:43:47.965  5858  5874 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
10-26 02:43:47.965  5858  5874 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-26 02:43:47.965  5627  5674 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-26 02:43:47.965  5627  5674 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-26 02:43:47.965  5627  5674 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-26 02:43:47.965  5627  5674 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-26 02:43:47.965  5627  5674 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-26 02:43:47.965  5627  5674 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-26 02:43:47.965  5627  5674 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-26 02:43:47.965  5627  5674 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
10-26 02:43:47.968  5627  5674 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
10-26 02:43:47.968  5627  5674 D io.jxcore.node.ConnectivityMonitor: start: OK
10-26 02:43:47.968  5627  5674 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
10-26 02:43:47.968  5627  5674 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@209227f added. We now have 4 listener(s)
10-26 02:43:47.969  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
10-26 02:43:47.969  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
10-26 02:43:47.969  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
10-26 02:43:47.969  5627  5674 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-26 02:43:47.969  5627  5674 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3a0924c added. We now have 5 listener(s)
10-26 02:43:47.969  5627  5674 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
10-26 02:43:47.970  5627  5674 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
10-26 02:43:47.970  5627  5627 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-26 02:43:47.970  5627  5674 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
10-26 02:43:47.970  5627  5674 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
10-26 02:43:47.970  5627  5674 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
10-26 02:43:47.970  5627  5674 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-26 02:43:47.970  5627  5674 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
10-26 02:43:47.971  5858  5874 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
10-26 02:43:47.971  5858  5874 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-26 02:43:47.971  5858  5877 D BtGatt.ScanManager: stopping BLe Batch
10-26 02:43:47.973  5627  5674 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
10-26 02:43:47.973  5627  5674 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
10-26 02:43:47.973  5627  5674 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
10-26 02:43:47.974  5627  5627 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-26 02:43:47.976  5858  5874 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
10-26 02:43:47.976  5627  5674 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
10-26 02:43:47.976  5858  5874 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-26 02:43:47.976  5858  5877 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
10-26 02:43:47.977  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
10-26 02:43:47.977  5627  5674 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
10-26 02:43:47.981  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-57,5,main], id: 57
10-26 02:43:47.981  5627  5674 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
10-26 02:43:47.981  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
10-26 02:43:47.981  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
10-26 02:43:47.981  5627  5674 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
10-26 02:43:47.981  5858  5874 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
10-26 02:43:47.981  5858  5874 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-26 02:43:47.981  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-57,5,main], id: 57
10-26 02:43:47.982  5627  5674 D BluetoothAdapter: STATE_ON
10-26 02:43:47.985  5858  5887 D BtGatt.GattService: registerClient() - UUID=8c2689c3-4e68-41b8-81e8-9eefb65fedef
10-26 02:43:47.985  5858  5874 D BtGatt.GattService: onClientRegistered() - UUID=8c2689c3-4e68-41b8-81e8-9eefb65fedef, clientIf=5
10-26 02:43:47.986  5627  5638 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
10-26 02:43:47.986  5858  5868 D BtGatt.GattService: start scan with filters
10-26 02:43:47.987  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
10-26 02:43:47.988  5858  5877 D BtGatt.ScanManager: handling starting scan
10-26 02:43:47.988  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-57,5,main], id: 57
10-26 02:43:47.988  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
10-26 02:43:47.988  5627  5674 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[Thread-57,5,main], id: 57
10-26 02:43:47.988  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[Thread-57,5,main], id: 57
10-26 02:43:47.988  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
10-26 02:43:47.988  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
10-26 02:43:47.988  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[Thread-57,5,main], id: 57
10-26 02:43:47.988  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[Thread-57,5,main], id: 57
10-26 02:43:47.988  5627  5674 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
10-26 02:43:47.988  5627  5674 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
10-26 02:43:47.991  5627  5674 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
10-26 02:43:47.991  5627  5674 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
10-26 02:43:47.991  5627  5674 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
10-26 02:43:47.991  5627  5627 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
10-26 02:43:47.991  5627  5674 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
10-26 02:43:47.991  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[Thread-57,5,main], id: 57
10-26 02:43:47.991  5627  5674 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
10-26 02:43:47.992  5858  5874 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
10-26 02:43:47.992  5858  5874 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-26 02:43:47.992  5627  5674 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
10-26 02:43:47.993  5627  5674 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
10-26 02:43:47.993  5858  5877 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,10-26 02:43:47.995  5627  5674 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
10-26 02:43:47.995  5627  5674 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
10-26 02:43:47.995  5627  5674 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
10-26 02:43:47.995  5627  5674 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
10-26 02:43:47.995  5627  5674 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
10-26 02:43:47.995  5627  5674 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-26 02:43:47.995  5627  5674 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-26 02:43:47.995  5627  5674 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-26 02:43:47.995  5627  5674 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-26 02:43:47.995  5627  5674 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-26 02:43:47.995  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
10-26 02:43:47.995  5627  5674 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-26 02:43:47.996  5627  5674 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
10-26 02:43:47.996  5627  5674 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@31a5420 removed from the list
10-26 02:43:47.996  5627  5674 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-26 02:43:47.996  5627  5674 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@897c1d9 removed from the list
10-26 02:43:47.996  5627  5674 D io.jxcore.node.ConnectivityMonitor: stop
10-26 02:43:47.996  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
10-26 02:43:47.996  5627  5674 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
10-26 02:43:47.996  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
10-26 02:43:47.996  5627  5674 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-26 02:43:47.996  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
10-26 02:43:47.996  5627  5674 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
10-26 02:43:47.997  5858  5874 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
10-26 02:43:47.997  5858  5874 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-26 02:43:47.997  5858  5877 D BtGatt.ScanManager: Starting BLE batch scan
10-26 02:43:47.997  5858  5877 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
10-26 02:43:47.997  5627  5674 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
10-26 02:43:47.997  5627  5674 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
10-26 02:43:47.997  5627  5674 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
10-26 02:43:47.997  5627  5674 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-26 02:43:47.997  5627  5674 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-26 02:43:47.997  5627  5674 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-26 02:43:47.998  5627  5674 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@897c1d9 not in the list
10-26 02:43:47.998  5627  5674 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
10-26 02:43:47.998  5627  5674 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
10-26 02:43:47.998  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
10-26 02:43:47.998  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-57,5,main], id: 57
10-26 02:43:47.998  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-57,5,main], id: 57
10-26 02:43:47.998  5627  5674 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
10-26 02:43:47.998  5627  5674 D BluetoothAdapter: STATE_ON
10-26 02:43:47.999  5858  5868 D BtGatt.GattService: stopScan() - queue size =1
10-26 02:43:47.999  5858  5869 D BtGatt.GattService: unregisterClient() - clientIf=5
10-26 02:43:48.000  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
10-26 02:43:48.000  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-57,5,main], id: 57
10-26 02:43:48.000  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
10-26 02:43:48.000  5627  5674 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[Thread-57,5,main], id: 57
10-26 02:43:48.000  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[Thread-57,5,main], id: 57
10-26 02:43:48.000  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
10-26 02:43:48.000  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
10-26 02:43:48.000  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[Thread-57,5,main], id: 57
10-26 02:43:48.000  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[Thread-57,5,main], id: 57
10-26 02:43:48.000  5627  5674 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
10-26 02:43:48.000  5627  5674 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
10-26 02:43:48.001  5627  5674 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
10-26 02:43:48.001  5627  5674 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
10-26 02:43:48.001  5627  5674 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
10-26 02:43:48.002  5627  5674 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
10-26 02:43:48.002  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[Thread-57,5,main], id: 57
10-26 02:43:48.002  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-57,5,main], id: 57
10-26 02:43:48.002  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-57,5,main], id: 57
10-26 02:43:48.002  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
10-26 02:43:48.002  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-57,5,main], id: 57
10-26 02:43:48.002  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finishedCurrent thread: Thread[Thread-57,5,main], id: 57
10-26 02:43:48.002  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-57,5,main], id: 57
10-26 02:43:48.002  5627  5674 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
10-26 02:43:48.002  5627  5674 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
10-26 02:43:48.005  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-26 02:43:48.005  5627  5674 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
10-26 02:43:48.006  5858  5874 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
10-26 02:43:48.006  5858  5874 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-26 02:43:48.006  5627  5674 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
10-26 02:43:48.006  5627  5674 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
10-26 02:43:48.006  5627  5674 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
10-26 02:43:48.006  5627  5674 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-26 02:43:48.006  5627  5674 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-26 02:43:48.006  5627  5674 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-26 02:43:48.007  5627  5627 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-26 02:43:48.007  5627  5674 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3a0924c removed from the list
10-26 02:43:48.007  5627  5674 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-26 02:43:48.007  5627  5627 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-26 02:43:48.007  5627  5674 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-26 02:43:48.007  5627  5627 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
10-26 02:43:48.007  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-26 02:43:48.007  5627  5674 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-26 02:43:48.007  5627  5674 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
10-26 02:43:48.007  5627  5674 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@209227f removed from the list
10-26 02:43:48.007  5627  5674 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
10-26 02:43:48.007  5627  5674 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@26a8738 added. We now have 3 listener(s)
10-26 02:43:48.009  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
10-26 02:43:48.009  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
10-26 02:43:48.009  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
10-26 02:43:48.009  5627  5674 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-26 02:43:48.009  5627  5674 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9ded311 added. We now have 4 listener(s)
10-26 02:43:48.009  5627  5674 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
10-26 02:43:48.009  5627  5674 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
10-26 02:43:48.010  5858  5874 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
10-26 02:43:48.010  5858  5874 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-26 02:43:48.011  5627  5674 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-26 02:43:48.016  5627  5674 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-26 02:43:48.016  5627  5674 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-26 02:43:48.016  5627  5674 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-26 02:43:48.016  5627  5674 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-26 02:43:48.016  5627  5674 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-26 02:43:48.016  5627  5674 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-26 02:43:48.016  5627  5674 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-26 02:43:48.016  5627  5674 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
10-26 02:43:48.017  5858  5874 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
10-26 02:43:48.017  5858  5874 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-26 02:43:48.017  5858  5877 D BtGatt.ScanManager: stopping BLe Batch
10-26 02:43:48.019  5627  5674 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
10-26 02:43:48.019  5627  5674 D io.jxcore.node.ConnectivityMonitor: start: OK
10-26 02:43:48.019  5627  5674 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
10-26 02:43:48.019  5627  5674 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@dfae277 added. We now have 4 listener(s)
10-26 02:43:48.020  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
10-26 02:43:48.020  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
10-26 02:43:48.020  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
10-26 02:43:48.020  5627  5674 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-26 02:43:48.020  5627  5674 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3dcdee4 added. We now have 5 listener(s)
10-26 02:43:48.021  5627  5674 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
10-26 02:43:48.021  5627  5674 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
10-26 02:43:48.021  5627  5674 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
10-26 02:43:48.021  5627  5674 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
10-26 02:43:48.021  5627  5674 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-26 02:43:48.021  5627  5674 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
10-26 02:43:48.021  5627  5627 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-26 02:43:48.022  5858  5874 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
10-26 02:43:48.022  5858  5874 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-26 02:43:48.022  5858  5877 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
10-26 02:43:48.024  5627  5674 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
10-26 02:43:48.025  5627  5674 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
10-26 02:43:48.025  5627  5627 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-26 02:43:48.025  5627  5674 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
10-26 02:43:48.027  5858  5874 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
10-26 02:43:48.027  5858  5874 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-26 02:43:48.029  5627  5674 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
10-26 02:43:48.029  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
10-26 02:43:48.029  5627  5674 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
10-26 02:43:48.033  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-57,5,main], id: 57
10-26 02:43:48.033  5627  5674 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
10-26 02:43:48.033  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
10-26 02:43:48.033  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
10-26 02:43:48.034  5627  5674 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
10-26 02:43:48.034  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-57,5,main], id: 57
10-26 02:43:48.034  5627  5674 D BluetoothAdapter: STATE_ON
10-26 02:43:48.037  5858  5886 D BtGatt.GattService: registerClient() - UUID=3ea2b128-4537-4021-bb8b-0cabb7541e85
10-26 02:43:48.037  5858  5874 D BtGatt.GattService: onClientRegistered() - UUID=3ea2b128-4537-4021-bb8b-0cabb7541e85, clientIf=5
,10-26 02:43:48.037  5627  5637 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
10-26 02:43:48.038  5858  5868 D BtGatt.GattService: start scan with filters
10-26 02:43:48.039  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
10-26 02:43:48.039  5858  5877 D BtGatt.ScanManager: handling starting scan
10-26 02:43:48.039  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-57,5,main], id: 57
10-26 02:43:48.039  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
10-26 02:43:48.039  5627  5674 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[Thread-57,5,main], id: 57
10-26 02:43:48.039  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[Thread-57,5,main], id: 57
10-26 02:43:48.040  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
10-26 02:43:48.040  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
10-26 02:43:48.040  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[Thread-57,5,main], id: 57
10-26 02:43:48.040  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[Thread-57,5,main], id: 57
10-26 02:43:48.040  5627  5674 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
10-26 02:43:48.040  5627  5674 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
10-26 02:43:48.042  5627  5674 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
10-26 02:43:48.043  5627  5674 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
10-26 02:43:48.043  5627  5674 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
10-26 02:43:48.043  5627  5627 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
10-26 02:43:48.043  5627  5674 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
10-26 02:43:48.043  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[Thread-57,5,main], id: 57
10-26 02:43:48.043  5627  5674 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
10-26 02:43:48.044  5627  5674 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
10-26 02:43:48.044  5627  5674 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
10-26 02:43:48.044  5858  5874 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
10-26 02:43:48.044  5858  5874 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-26 02:43:48.044  5858  5877 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
10-26 02:43:48.046  5627  5674 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
10-26 02:43:48.047  5627  5674 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
10-26 02:43:48.047  5627  5674 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
10-26 02:43:48.048  5627  5674 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-26 02:43:48.048  5627  5674 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-26 02:43:48.048  5627  5674 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-26 02:43:48.048  5627  5674 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-26 02:43:48.048  5627  5674 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-26 02:43:48.049  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
10-26 02:43:48.049  5627  5674 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-26 02:43:48.049  5627  5674 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
10-26 02:43:48.049  5627  5674 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@26a8738 removed from the list
10-26 02:43:48.049  5627  5674 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-26 02:43:48.049  5627  5674 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9ded311 removed from the list
10-26 02:43:48.049  5627  5674 D io.jxcore.node.ConnectivityMonitor: stop
10-26 02:43:48.049  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
10-26 02:43:48.049  5627  5674 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
10-26 02:43:48.049  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
10-26 02:43:48.049  5627  5674 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-26 02:43:48.049  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
10-26 02:43:48.050  5627  5674 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
10-26 02:43:48.050  5858  5874 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
10-26 02:43:48.050  5858  5874 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-26 02:43:48.050  5858  5877 D BtGatt.ScanManager: Starting BLE batch scan
10-26 02:43:48.050  5858  5877 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
10-26 02:43:48.051  5627  5674 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
10-26 02:43:48.051  5627  5674 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
10-26 02:43:48.051  5627  5674 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
10-26 02:43:48.052  5627  5674 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-26 02:43:48.052  5627  5674 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-26 02:43:48.052  5627  5674 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-26 02:43:48.052  5627  5674 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9ded311 not in the list
10-26 02:43:48.052  5627  5674 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
10-26 02:43:48.052  5627  5674 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
10-26 02:43:48.052  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
10-26 02:43:48.052  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-57,5,main], id: 57
10-26 02:43:48.052  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-57,5,main], id: 57
10-26 02:43:48.052  5627  5674 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
10-26 02:43:48.052  5627  5674 D BluetoothAdapter: STATE_ON
10-26 02:43:48.053  5858  5898 D BtGatt.GattService: stopScan() - queue size =1
10-26 02:43:48.054  5858  5886 D BtGatt.GattService: unregisterClient() - clientIf=5
10-26 02:43:48.054  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
10-26 02:43:48.054  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-57,5,main], id: 57
10-26 02:43:48.054  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
10-26 02:43:48.054  5627  5674 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[Thread-57,5,main], id: 57
10-26 02:43:48.054  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[Thread-57,5,main], id: 57
10-26 02:43:48.054  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
10-26 02:43:48.054  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
10-26 02:43:48.054  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[Thread-57,5,main], id: 57
10-26 02:43:48.054  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[Thread-57,5,main], id: 57
10-26 02:43:48.054  5627  5674 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
10-26 02:43:48.054  5627  5674 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
10-26 02:43:48.055  5627  5674 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
10-26 02:43:48.055  5627  5674 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
10-26 02:43:48.055  5627  5674 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
10-26 02:43:48.056  5627  5674 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
10-26 02:43:48.056  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[Thread-57,5,main], id: 57
10-26 02:43:48.056  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-57,5,main], id: 57
10-26 02:43:48.056  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-57,5,main], id: 57
10-26 02:43:48.056  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
10-26 02:43:48.056  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-57,5,main], id: 57
10-26 02:43:48.056  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finishedCurrent thread: Thread[Thread-57,5,main], id: 57
10-26 02:43:48.056  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-57,5,main], id: 57
10-26 02:43:48.056  5627  5674 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
10-26 02:43:48.056  5627  5674 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
10-26 02:43:48.056  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-26 02:43:48.056  5627  5674 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
10-26 02:43:48.057  5627  5674 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
10-26 02:43:48.057  5627  5674 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
10-26 02:43:48.057  5627  5674 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
10-26 02:43:48.057  5627  5674 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-26 02:43:48.057  5627  5674 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-26 02:43:48.058  5627  5674 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-26 02:43:48.058  5627  5674 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3dcdee4 removed from the list
10-26 02:43:48.058  5627  5627 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-26 02:43:48.058  5627  5674 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-26 02:43:48.058  5627  5627 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-26 02:43:48.058  5627  5674 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-26 02:43:48.058  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-26 02:43:48.058  5627  5627 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
10-26 02:43:48.058  5627  5674 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-26 02:43:48.058  5627  5674 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
10-26 02:43:48.058  5627  5674 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@dfae277 removed from the list
10-26 02:43:48.059  5858  5874 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
10-26 02:43:48.059  5858  5874 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-26 02:43:48.059  5627  5674 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
10-26 02:43:48.059  5627  5674 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@bfb0550 added. We now have 3 listener(s)
10-26 02:43:48.060  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
10-26 02:43:48.061  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
10-26 02:43:48.061  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
10-26 02:43:48.061  5627  5674 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-26 02:43:48.061  5627  5674 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@15fd349 added. We now have 4 listener(s)
10-26 02:43:48.061  5627  5674 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
10-26 02:43:48.061  5627  5674 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
10-26 02:43:48.064  5627  5674 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-26 02:43:48.065  5858  5874 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
10-26 02:43:48.065  5858  5874 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-26 02:43:48.068  5627  5674 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-26 02:43:48.068  5627  5674 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-26 02:43:48.068  5627  5674 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-26 02:43:48.068  5627  5674 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-26 02:43:48.068  5627  5674 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-26 02:43:48.068  5627  5674 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-26 02:43:48.068  5627  5674 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-26 02:43:48.068  5627  5674 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
10-26 02:43:48.070  5627  5674 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
10-26 02:43:48.070  5627  5674 D io.jxcore.node.ConnectivityMonitor: start: OK
10-26 02:43:48.070  5627  5674 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
10-26 02:43:48.070  5627  5674 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f75a96f added. We now have 4 listener(s)
10-26 02:43:48.070  5858  5874 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
10-26 02:43:48.070  5858  5874 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-26 02:43:48.070  5858  5877 D BtGatt.ScanManager: stopping BLe Batch
10-26 02:43:48.071  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
10-26 02:43:48.071  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
10-26 02:43:48.071  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
10-26 02:43:48.071  5627  5674 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-26 02:43:48.071  5627  5674 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@993267c added. We now have 5 listener(s)
10-26 02:43:48.071  5627  5674 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
10-26 02:43:48.071  5627  5674 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-26 02:43:48.072  5627  5674 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-26 02:43:48.072  5627  5674 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-26 02:43:48.072  5627  5674 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-26 02:43:48.072  5627  5674 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-26 02:43:48.072  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
10-26 02:43:48.072  5627  5674 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-26 02:43:48.072  5627  5674 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
10-26 02:43:48.072  5627  5627 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-26 02:43:48.072  5627  5674 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@bfb0550 removed from the list
10-26 02:43:48.072  5627  5674 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-26 02:43:48.072  5627  5674 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@15fd349 removed from the list
10-26 02:43:48.075  5627  5627 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-26 02:43:48.075  5627  5674 D io.jxcore.node.ConnectivityMonitor: stop
,10-26 02:43:48.075  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-26 02:43:48.075  5627  5674 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-26 02:43:48.075  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-26 02:43:48.076  5627  5674 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
10-26 02:43:48.077  5627  5674 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
10-26 02:43:48.077  5858  5874 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
10-26 02:43:48.077  5858  5874 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-26 02:43:48.077  5627  5674 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
10-26 02:43:48.077  5858  5877 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
10-26 02:43:48.077  5627  5674 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
10-26 02:43:48.077  5627  5674 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-26 02:43:48.077  5627  5674 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-26 02:43:48.077  5627  5674 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-26 02:43:48.077  5627  5674 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@15fd349 not in the list
10-26 02:43:48.077  5627  5674 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-26 02:43:48.077  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-26 02:43:48.078  5627  5674 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
10-26 02:43:48.079  5627  5674 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
10-26 02:43:48.079  5627  5674 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
10-26 02:43:48.079  5627  5674 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
10-26 02:43:48.079  5627  5674 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-26 02:43:48.079  5627  5674 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-26 02:43:48.079  5627  5674 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-26 02:43:48.079  5627  5674 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@993267c removed from the list
10-26 02:43:48.079  5627  5674 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-26 02:43:48.080  5627  5674 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-26 02:43:48.080  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-26 02:43:48.080  5627  5674 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-26 02:43:48.080  5627  5674 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
10-26 02:43:48.080  5627  5674 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f75a96f removed from the list
10-26 02:43:48.081  5627  5674 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
10-26 02:43:48.081  5627  5674 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
10-26 02:43:48.081  5627  5674 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
10-26 02:43:48.081  5627  5674 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
10-26 02:43:48.081  5627  5674 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
10-26 02:43:48.081  5627  5674 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
10-26 02:43:48.082  5858  5874 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
10-26 02:43:48.082  5858  5874 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,10-26 02:43:48.246  3545  5959 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,10-26 02:43:48.362  3545  5957 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,10-26 02:43:48.443  3545  5955 W Uploader:  no longer exists, so no auth token.
,10-26 02:43:48.448   926  2990 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{4}, ntable=[192.168.1.1/NUD_REACHABLE]
,10-26 02:43:48.449  5627  5627 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,10-26 02:43:48.457   926  2995 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,10-26 02:43:48.460  3545  5959 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,10-26 02:43:48.462  3743  3865 W QCNEJ   : |CORE| newLp: {InterfaceName: wlan0 LinkAddresses: [192.168.1.111/24,fe80::6283:34ff:fe25:d770/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}
,10-26 02:43:48.464  3743  3865 W QCNEJ   : |CORE| curLp: {InterfaceName: wlan0 LinkAddresses: [192.168.1.111/24,fe80::6283:34ff:fe25:d770/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,10-26 02:43:48.508  5627  5627 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,10-26 02:43:48.543  3545  5957 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,10-26 02:43:48.558  5627  5627 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,10-26 02:43:48.628  3545  5959 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,10-26 02:43:48.631   926  2995 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,10-26 02:43:50.226  5627  5964 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 173, name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
10-26 02:43:50.226  5627  5964 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,10-26 02:43:51.024  5627  5964 W !!      : call onHalfStreamCopied
,10-26 02:43:51.024  5627  5964 I testCopyDataAndClose: closing input stream
,10-26 02:43:51.796  5627  5964 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 173, thread name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
10-26 02:43:51.796  5627  5964 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,10-26 02:43:51.796  5627  5964 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
10-26 02:43:51.796  5627  5964 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
10-26 02:43:51.796  5627  5964 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
10-26 02:43:51.796  5627  5964 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
,10-26 02:43:51.796  5627  5964 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
10-26 02:43:51.796  5627  5964 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
10-26 02:43:51.796  5627  5964 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
,10-26 02:43:51.796  5627  5964 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 173, name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
10-26 02:43:51.796  5627  5964 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 20971520 and the total number of bytes written 20971520
,10-26 02:43:55.590   926  2995 D ConnectivityService: handlePromptUnvalidated 101
,10-26 02:43:55.930  5627  5965 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 176, name: My test thread name). Connection data: Peer properties: [null null].
10-26 02:43:55.930  5627  5965 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,10-26 02:43:56.340   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,10-26 02:43:57.341   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,10-26 02:43:57.930  5627  5674 I io.jxcore.node.StreamCopyingThread: close: Thread ID: 176. Connection data: Peer properties: [null null].
10-26 02:43:57.930  5627  5674 I io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
10-26 02:43:57.930  5627  5674 D io.jxcore.node.StreamCopyingThread: closeStreams: Streams closed (thread ID: 176, name: My test thread name)
,10-26 02:43:57.940  5627  5965 D io.jxcore.node.StreamCopyingThread: number of bytes read = 0
,10-26 02:43:57.941  5627  5965 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 176, name: My test thread name). Connection data: Peer properties: [null null].
10-26 02:43:57.941  5627  5965 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 121 and the total number of bytes written 121
,10-26 02:43:58.073  5627  5966 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 178, name: testCopyBigData thread). Connection data: Peer properties: [null null].
10-26 02:43:58.073  5627  5966 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,10-26 02:43:58.342   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,10-26 02:43:59.344   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,10-26 02:43:59.696  5627  5966 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 178, thread name: testCopyBigData thread). Connection data: Peer properties: [null null].
10-26 02:43:59.696  5627  5966 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,10-26 02:43:59.696  5627  5966 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
10-26 02:43:59.696  5627  5966 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
10-26 02:43:59.696  5627  5966 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
10-26 02:43:59.696  5627  5966 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
10-26 02:43:59.696  5627  5966 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
10-26 02:43:59.696  5627  5966 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
,10-26 02:43:59.696  5627  5966 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
,10-26 02:43:59.696  5627  5966 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 178, name: testCopyBigData thread). Connection data: Peer properties: [null null].
10-26 02:43:59.696  5627  5966 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 20971520 and the total number of bytes written 20971520
,10-26 02:44:00.345   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,10-26 02:44:01.346   534   534 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,10-26 02:44:03.821  5627  5967 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 180, name: My test thread name). Connection data: Peer properties: [null null].
10-26 02:44:03.821  5627  5967 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,10-26 02:44:03.821  5627  5967 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 180, thread name: My test thread name). Connection data: Peer properties: [null null].
10-26 02:44:03.821  5627  5967 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
10-26 02:44:03.821  5627  5967 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
10-26 02:44:03.821  5627  5967 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
10-26 02:44:03.821  5627  5967 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
,10-26 02:44:03.822  5627  5967 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
10-26 02:44:03.822  5627  5967 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
10-26 02:44:03.822  5627  5967 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
10-26 02:44:03.822  5627  5967 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
,10-26 02:44:03.822  5627  5967 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 180, name: My test thread name). Connection data: Peer properties: [null null].
10-26 02:44:03.822  5627  5967 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 22
10-26 02:44:03.824  5627  5674 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,10-26 02:44:03.827  5627  5968 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 184, name: My test thread name). Connection data: Peer properties: [null null].
10-26 02:44:03.827  5627  5968 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
10-26 02:44:03.827  5627  5968 E io.jxcore.node.StreamCopyingThread: Failed to write to the output stream (thread ID: 184, thread name: My test thread name): Test exception.
,10-26 02:44:03.828  5627  5968 D io.jxcore.node.StreamCopyingThread: onStreamCopyError (ID: 184, name: My test thread name). Connection data: Peer properties: [null null].
10-26 02:44:03.828  5627  5968 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
10-26 02:44:03.828  5627  5968 D io.jxcore.node.StreamCopyingThread: number of bytes read = 22
10-26 02:44:03.828  5627  5968 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 184, name: My test thread name). Connection data: Peer properties: [null null].
10-26 02:44:03.828  5627  5968 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
10-26 02:44:03.833  5627  5674 I jxcore-log: 2016-10-26 00:44:03 - DEBUG UnitTest_app: 'Total number of executed tests:  82'
10-26 02:44:03.833  5627  5674 I jxcore-log: 
10-26 02:44:03.834  5627  5674 I jxcore-log: 2016-10-26 00:44:03 - DEBUG UnitTest_app: 'Number of passed tests:  82'
10-26 02:44:03.834  5627  5674 I jxcore-log: 
,10-26 02:44:03.834  5627  5674 I jxcore-log: 2016-10-26 00:44:03 - DEBUG UnitTest_app: 'Number of failed tests:  0'
10-26 02:44:03.834  5627  5674 I jxcore-log: 
10-26 02:44:03.834  5627  5674 I jxcore-log: 2016-10-26 00:44:03 - DEBUG UnitTest_app: 'Number of ignored tests:  0'
10-26 02:44:03.834  5627  5674 I jxcore-log: 
10-26 02:44:03.834  5627  5674 I jxcore-log: 2016-10-26 00:44:03 - DEBUG UnitTest_app: 'Total duration:  91603'
10-26 02:44:03.834  5627  5674 I jxcore-log: 
10-26 02:44:03.836  5627  5674 I jxcore-log: 2016-10-26 00:44:03 - DEBUG UnitTest_app: 'Unit Test app is loaded'
10-26 02:44:03.836  5627  5674 I jxcore-log: 
,10-26 02:44:03.839  5627  5674 I jxcore-log: 2016-10-26 00:44:03 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-26 02:44:03.839  5627  5674 I jxcore-log: 
,10-26 02:44:03.840  5627  5674 I jxcore-log: 2016-10-26 00:44:03 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-26 02:44:03.840  5627  5674 I jxcore-log: 
10-26 02:44:03.841  5627  5674 I jxcore-log: 2016-10-26 00:44:03 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-26 02:44:03.841  5627  5674 I jxcore-log: 
10-26 02:44:03.841  5627  5674 I jxcore-log: 2016-10-26 00:44:03 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-26 02:44:03.841  5627  5674 I jxcore-log: 
,10-26 02:44:03.841  5627  5674 I jxcore-log: 2016-10-26 00:44:03 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
10-26 02:44:03.841  5627  5674 I jxcore-log: 
10-26 02:44:03.842  5627  5674 I jxcore-log: 2016-10-26 00:44:03 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
10-26 02:44:03.842  5627  5674 I jxcore-log: 
10-26 02:44:03.842  5627  5674 I jxcore-log: 2016-10-26 00:44:03 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-26 02:44:03.842  5627  5674 I jxcore-log: 
10-26 02:44:03.842  5627  5674 I jxcore-log: 2016-10-26 00:44:03 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-26 02:44:03.842  5627  5674 I jxcore-log: 
10-26 02:44:03.842  5627  5674 I jxcore-log: 2016-10-26 00:44:03 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
10-26 02:44:03.842  5627  5674 I jxcore-log: 
10-26 02:44:03.843  5627  5674 I jxcore-log: 2016-10-26 00:44:03 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
10-26 02:44:03.843  5627  5674 I jxcore-log: 
,10-26 02:44:03.843  5627  5674 I jxcore-log: 2016-10-26 00:44:03 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
10-26 02:44:03.843  5627  5674 I jxcore-log: 
10-26 02:44:03.843  5627  5674 I jxcore-log: 2016-10-26 00:44:03 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-26 02:44:03.843  5627  5674 I jxcore-log: 
10-26 02:44:03.843  5627  5674 I jxcore-log: 2016-10-26 00:44:03 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-26 02:44:03.843  5627  5674 I jxcore-log: 
10-26 02:44:03.844  5627  5674 I jxcore-log: 2016-10-26 00:44:03 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
10-26 02:44:03.844  5627  5674 I jxcore-log: 
,10-26 02:44:03.844  5627  5674 I jxcore-log: 2016-10-26 00:44:03 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-26 02:44:03.844  5627  5674 I jxcore-log: 
10-26 02:44:03.844  5627  5674 I jxcore-log: 2016-10-26 00:44:03 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
10-26 02:44:03.844  5627  5674 I jxcore-log: 
10-26 02:44:03.845  5627  5674 I jxcore-log: 2016-10-26 00:44:03 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
10-26 02:44:03.845  5627  5674 I jxcore-log: 
10-26 02:44:03.845  5627  5674 I jxcore-log: 2016-10-26 00:44:03 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
10-26 02:44:03.845  5627  5674 I jxcore-log: 
10-26 02:44:03.845  5627  5674 I jxcore-log: 2016-10-26 00:44:03 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
10-26 02:44:03.845  5627  5674 I jxcore-log: 
10-26 02:44:03.845  5627  5674 I jxcore-log: 2016-10-26 00:44:03 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
10-26 02:44:03.845  5627  5674 I jxcore-log: 
,10-26 02:44:03.846  5627  5674 I jxcore-log: 2016-10-26 00:44:03 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
10-26 02:44:03.846  5627  5674 I jxcore-log: 
10-26 02:44:03.846  5627  5674 I jxcore-log: 2016-10-26 00:44:03 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
10-26 02:44:03.846  5627  5674 I jxcore-log: 
,10-26 02:44:03.846  5627  5674 I jxcore-log: 2016-10-26 00:44:03 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
10-26 02:44:03.846  5627  5674 I jxcore-log: 
,10-26 02:44:03.847  5627  5674 I jxcore-log: 2016-10-26 00:44:03 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
10-26 02:44:03.847  5627  5674 I jxcore-log: 
10-26 02:44:03.848  5627  5674 I jxcore-log: 2016-10-26 00:44:03 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
10-26 02:44:03.848  5627  5674 I jxcore-log: 
10-26 02:44:03.848  5627  5674 I jxcore-log: 2016-10-26 00:44:03 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
10-26 02:44:03.848  5627  5674 I jxcore-log: 
10-26 02:44:03.848  5627  5674 I jxcore-log: 2016-10-26 00:44:03 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
10-26 02:44:03.848  5627  5674 I jxcore-log: 
10-26 02:44:03.849  5627  5674 I jxcore-log: 2016-10-26 00:44:03 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
10-26 02:44:03.849  5627  5674 I jxcore-log: 
10-26 02:44:03.849  5627  5674 I jxcore-log: 2016-10-26 00:44:03 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
10-26 02:44:03.849  5627  5674 I jxcore-log: 
,10-26 02:44:03.849  5627  5674 I jxcore-log: 2016-10-26 00:44:03 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
10-26 02:44:03.849  5627  5674 I jxcore-log: 
10-26 02:44:03.849  5627  5674 I jxcore-log: 2016-10-26 00:44:03 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
10-26 02:44:03.849  5627  5674 I jxcore-log: 
10-26 02:44:03.849  5627  5674 I jxcore-log: 2016-10-26 00:44:03 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
10-26 02:44:03.849  5627  5674 I jxcore-log: 
10-26 02:44:03.850  5627  5674 I jxcore-log: 2016-10-26 00:44:03 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
10-26 02:44:03.850  5627  5674 I jxcore-log: 
10-26 02:44:03.850  5627  5674 I jxcore-log: 2016-10-26 00:44:03 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
10-26 02:44:03.850  5627  5674 I jxcore-log: 
10-26 02:44:03.850  5627  5674 I jxcore-log: 2016-10-26 00:44:03 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
10-26 02:44:03.850  5627  5674 I jxcore-log: 
,10-26 02:44:03.850  5627  5674 I jxcore-log: 2016-10-26 00:44:03 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
10-26 02:44:03.850  5627  5674 I jxcore-log: 
10-26 02:44:03.851  5627  5674 I jxcore-log: 2016-10-26 00:44:03 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
10-26 02:44:03.851  5627  5674 I jxcore-log: 
10-26 02:44:03.851  5627  5674 I jxcore-log: 2016-10-26 00:44:03 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-26 02:44:03.851  5627  5674 I jxcore-log: 
10-26 02:44:03.851  5627  5674 I jxcore-log: 2016-10-26 00:44:03 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-26 02:44:03.851  5627  5674 I jxcore-log: 
10-26 02:44:03.851  5627  5674 I jxcore-log: 2016-10-26 00:44:03 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-26 02:44:03.851  5627  5674 I jxcore-log: 
10-26 02:44:03.851  5627  5674 I jxcore-log: 2016-10-26 00:44:03 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-26 02:44:03.851  5627  5674 I jxcore-log: 
10-26 02:44:03.852  5627  5674 I jxcore-log: 2016-10-26 00:44:03 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-26 02:44:03.852  5627  5674 I jxcore-log: 
10-26 02:44:03.852  5627  5674 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-26 02:44:03.852  5627  5674 D io.jxcore.node.StartStopOperationHandler: Operation timeout, state error: null
10-26 02:44:03.852  5627  5674 I jxcore-log: 2016-10-26 00:44:03 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-26 02:44:03.852  5627  5674 I jxcore-log: 
10-26 02:44:03.852  5627  5674 I jxcore-log: 2016-10-26 00:44:03 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-26 02:44:03.852  5627  5674 I jxcore-log: 
10-26 02:44:03.853  5627  5674 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
10-26 02:44:03.853  5627  5674 D io.jxcore.node.StartStopOperationHandler: Operation timeout, state error: Discovery manager not started
10-26 02:44:03.853  5627  5674 I jxcore-log: 2016-10-26 00:44:03 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-26 02:44:03.853  5627  5674 I jxcore-log: 
10-26 02:44:03.853  5627  5674 I jxcore-log: 2016-10-26 00:44:03 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
10-26 02:44:03.853  5627  5674 I jxcore-log: 
10-26 02:44:03.853  5627  5674 I jxcore-log: 2016-10-26 00:44:03 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
10-26 02:44:03.853  5627  5674 I jxcore-log: 
10-26 02:44:03.853  5627  5674 I jxcore-log: 2016-10-26 00:44:03 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
10-26 02:44:03.853  5627  5674 I jxcore-log: 
10-26 02:44:03.854  5627  5627 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
10-26 02:44:03.859  5627  5674 I jxcore-log: 2016-10-26 00:44:03 - DEBUG UnitTest_app: 'My device name is: Huawei-Nexus 6P'
10-26 02:44:03.859  5627  5674 I jxcore-log: 
10-26 02:44:03.860  5627  5674 E JX-Cordova: jxcore.CallJSMethod :{"isFulfilled":false,"isRejected":false}
10-26 02:44:03.861  5627  5674 I jxcore-log: 2016-10-26 00:44:03 - DEBUG UnitTest_app: 'Running for WIFI network type'
10-26 02:44:03.861  5627  5674 I jxcore-log: 
,10-26 02:44:05.869  5627  5674 I jxcore-log: 2016-10-26 00:44:05 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js'
10-26 02:44:05.869  5627  5674 I jxcore-log: 
,10-26 02:44:06.194  5627  5674 I jxcore-log: 2016-10-26 00:44:06 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js'
10-26 02:44:06.194  5627  5674 I jxcore-log: 
,10-26 02:44:06.206  5627  5674 I jxcore-log: 2016-10-26 00:44:06 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManager.js'
10-26 02:44:06.206  5627  5674 I jxcore-log: 
,10-26 02:44:07.291  5627  5674 I jxcore-log: 2016-10-26 00:44:07 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js'
10-26 02:44:07.291  5627  5674 I jxcore-log: 
,10-26 02:44:07.477  5627  5674 I jxcore-log: 2016-10-26 00:44:07 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js'
10-26 02:44:07.477  5627  5674 I jxcore-log: 
,10-26 02:44:07.483  5627  5674 I jxcore-log: 2016-10-26 00:44:07 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testNativeMethod.js'
10-26 02:44:07.483  5627  5674 I jxcore-log: 
,10-26 02:44:07.487  5627  5674 I jxcore-log: 2016-10-26 00:44:07 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPouchDBCheckpointPlugin.js'
10-26 02:44:07.487  5627  5674 I jxcore-log: 
,10-26 02:44:07.959  5627  5674 I jxcore-log: 2016-10-26 00:44:07 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPouchDBGenerator.js'
10-26 02:44:07.959  5627  5674 I jxcore-log: 
,10-26 02:44:08.001  5627  5674 I jxcore-log: 2016-10-26 00:44:08 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js'
10-26 02:44:08.001  5627  5674 I jxcore-log: 
,10-26 02:44:08.014  5627  5674 I jxcore-log: 2016-10-26 00:44:08 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js'
10-26 02:44:08.014  5627  5674 I jxcore-log: 
,10-26 02:44:08.018  5627  5674 I jxcore-log: 2016-10-26 00:44:08 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliManager.js'
10-26 02:44:08.018  5627  5674 I jxcore-log: 
,10-26 02:44:08.297  5627  5674 I jxcore-log: 2016-10-26 00:44:08 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliManagerCoordinated.js'
10-26 02:44:08.297  5627  5674 I jxcore-log: 
,10-26 02:44:08.420  5627  5674 I jxcore-log: 2016-10-26 00:44:08 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js'
10-26 02:44:08.420  5627  5674 I jxcore-log: 
,10-26 02:44:08.807  5627  5674 I jxcore-log: 2016-10-26 00:44:08 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js'
10-26 02:44:08.807  5627  5674 I jxcore-log: 
,10-26 02:44:08.814  5627  5674 I jxcore-log: 2016-10-26 00:44:08 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeDiscoveryCoordinated.js'
10-26 02:44:08.814  5627  5674 I jxcore-log: 
,10-26 02:44:08.817  5627  5674 I jxcore-log: 2016-10-26 00:44:08 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js'
10-26 02:44:08.817  5627  5674 I jxcore-log: 
,10-26 02:44:08.822  5627  5674 I jxcore-log: 2016-10-26 00:44:08 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js'
10-26 02:44:08.822  5627  5674 I jxcore-log: 
,10-26 02:44:08.827  5627  5674 I jxcore-log: 2016-10-26 00:44:08 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js'
10-26 02:44:08.827  5627  5674 I jxcore-log: 
,10-26 02:44:08.853  5627  5674 I jxcore-log: 2016-10-26 00:44:08 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js'
10-26 02:44:08.853  5627  5674 I jxcore-log: 
,10-26 02:44:08.887  5627  5674 I jxcore-log: 2016-10-26 00:44:08 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js'
10-26 02:44:08.887  5627  5674 I jxcore-log: 
,10-26 02:44:08.893  5627  5674 I jxcore-log: 2016-10-26 00:44:08 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationLocal.js'
10-26 02:44:08.893  5627  5674 I jxcore-log: 
,10-26 02:44:08.899  5627  5674 I jxcore-log: 2016-10-26 00:44:08 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js'
10-26 02:44:08.899  5627  5674 I jxcore-log: 
,10-26 02:44:08.912  5627  5674 I jxcore-log: 2016-10-26 00:44:08 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js'
10-26 02:44:08.912  5627  5674 I jxcore-log: 
,10-26 02:44:08.916  5627  5674 I jxcore-log: 2016-10-26 00:44:08 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js'
10-26 02:44:08.916  5627  5674 I jxcore-log: 
,10-26 02:44:08.921  5627  5674 I jxcore-log: 2016-10-26 00:44:08 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolDefault.js'
10-26 02:44:08.921  5627  5674 I jxcore-log: 
,10-26 02:44:08.926  5627  5674 I jxcore-log: 2016-10-26 00:44:08 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js'
10-26 02:44:08.926  5627  5674 I jxcore-log: 
,10-26 02:44:08.937  5627  5674 I jxcore-log: 2016-10-26 00:44:08 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolOneAtATime.js'
10-26 02:44:08.937  5627  5674 I jxcore-log: 
,10-26 02:44:08.942  5627  5674 I jxcore-log: 2016-10-26 00:44:08 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js'
10-26 02:44:08.942  5627  5674 I jxcore-log: 
,10-26 02:44:08.962  5627  5674 I jxcore-log: 2016-10-26 00:44:08 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js'
10-26 02:44:08.962  5627  5674 I jxcore-log: 
,10-26 02:44:08.972  5627  5674 I jxcore-log: 2016-10-26 00:44:08 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerAction.js'
10-26 02:44:08.972  5627  5674 I jxcore-log: 
,10-26 02:44:08.982  5627  5674 I jxcore-log: 2016-10-26 00:44:08 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js'
10-26 02:44:08.982  5627  5674 I jxcore-log: 
,10-26 02:44:08.992  5627  5674 I jxcore-log: 2016-10-26 00:44:08 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js'
10-26 02:44:08.992  5627  5674 I jxcore-log: 
,10-26 02:44:09.004  5627  5674 I jxcore-log: 2016-10-26 00:44:09 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js'
10-26 02:44:09.004  5627  5674 I jxcore-log: 
,10-26 02:44:09.014  5627  5674 I jxcore-log: 2016-10-26 00:44:09 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js'
10-26 02:44:09.014  5627  5674 I jxcore-log: 
,10-26 02:44:09.020  5627  5674 I jxcore-log: 2016-10-26 00:44:09 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js'
10-26 02:44:09.020  5627  5674 I jxcore-log: 
,10-26 02:44:09.042  5627  5674 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: SUPPORTED
,10-26 02:44:09.043  5627  5674 I jxcore-log: 2016-10-26 00:44:09 - INFO testUtils: 'BLE multiple advertisement supported'
10-26 02:44:09.043  5627  5674 I jxcore-log: 
,10-26 02:44:09.116  5627  5674 I jxcore-log: 2016-10-26 00:44:09 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-26 02:44:09.116  5627  5674 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-26 02:44:09.116  5627  5674 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-26 02:44:09.116  5627  5674 I jxcore-log: emit@events.js:82:1
10-26 02:44:09.116  5627  5674 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-26 02:44:09.116  5627  5674 I jxcore-log: emit@events.js:82:1'
10-26 02:44:09.116  5627  5674 I jxcore-log: 
,10-26 02:44:09.464  5627  5674 I jxcore-log: 2016-10-26 00:44:09 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-26 02:44:09.464  5627  5674 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-26 02:44:09.464  5627  5674 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-26 02:44:09.464  5627  5674 I jxcore-log: emit@events.js:82:1
10-26 02:44:09.464  5627  5674 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-26 02:44:09.464  5627  5674 I jxcore-log: emit@events.js:82:1'
10-26 02:44:09.464  5627  5674 I jxcore-log: 
,10-26 02:44:09.468  5627  5674 I jxcore-log: 2016-10-26 00:44:09 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-26 02:44:09.468  5627  5674 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-26 02:44:09.468  5627  5674 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-26 02:44:09.468  5627  5674 I jxcore-log: emit@events.js:82:1
10-26 02:44:09.468  5627  5674 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-26 02:44:09.468  5627  5674 I jxcore-log: emit@events.js:82:1'
10-26 02:44:09.468  5627  5674 I jxcore-log: 
,10-26 02:44:09.869  5627  5674 I jxcore-log: 2016-10-26 00:44:09 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-26 02:44:09.869  5627  5674 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-26 02:44:09.869  5627  5674 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-26 02:44:09.869  5627  5674 I jxcore-log: emit@events.js:82:1
10-26 02:44:09.869  5627  5674 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-26 02:44:09.869  5627  5674 I jxcore-log: emit@events.js:82:1'
10-26 02:44:09.869  5627  5674 I jxcore-log: 
,10-26 02:44:09.872  5627  5674 I jxcore-log: 2016-10-26 00:44:09 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-26 02:44:09.872  5627  5674 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-26 02:44:09.872  5627  5674 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-26 02:44:09.872  5627  5674 I jxcore-log: emit@events.js:82:1
10-26 02:44:09.872  5627  5674 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-26 02:44:09.872  5627  5674 I jxcore-log: emit@events.js:82:1'
10-26 02:44:09.872  5627  5674 I jxcore-log: 
,10-26 02:44:10.382  5627  5674 I jxcore-log: 2016-10-26 00:44:10 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-26 02:44:10.382  5627  5674 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-26 02:44:10.382  5627  5674 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-26 02:44:10.382  5627  5674 I jxcore-log: emit@events.js:82:1
10-26 02:44:10.382  5627  5674 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-26 02:44:10.382  5627  5674 I jxcore-log: emit@events.js:82:1'
10-26 02:44:10.382  5627  5674 I jxcore-log: 
,10-26 02:44:10.386  5627  5674 I jxcore-log: 2016-10-26 00:44:10 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-26 02:44:10.386  5627  5674 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-26 02:44:10.386  5627  5674 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-26 02:44:10.386  5627  5674 I jxcore-log: emit@events.js:82:1
10-26 02:44:10.386  5627  5674 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-26 02:44:10.386  5627  5674 I jxcore-log: emit@events.js:82:1'
10-26 02:44:10.386  5627  5674 I jxcore-log: 
,10-26 02:44:11.326  5627  5674 I jxcore-log: 2016-10-26 00:44:11 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-26 02:44:11.326  5627  5674 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-26 02:44:11.326  5627  5674 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-26 02:44:11.326  5627  5674 I jxcore-log: emit@events.js:82:1
10-26 02:44:11.326  5627  5674 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-26 02:44:11.326  5627  5674 I jxcore-log: emit@events.js:82:1'
10-26 02:44:11.326  5627  5674 I jxcore-log: 
,10-26 02:44:11.330  5627  5674 I jxcore-log: 2016-10-26 00:44:11 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-26 02:44:11.330  5627  5674 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-26 02:44:11.330  5627  5674 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-26 02:44:11.330  5627  5674 I jxcore-log: emit@events.js:82:1
10-26 02:44:11.330  5627  5674 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-26 02:44:11.330  5627  5674 I jxcore-log: emit@events.js:82:1'
10-26 02:44:11.330  5627  5674 I jxcore-log: 
,10-26 02:44:12.372  5627  5674 I jxcore-log: 2016-10-26 00:44:12 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-26 02:44:12.372  5627  5674 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-26 02:44:12.372  5627  5674 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-26 02:44:12.372  5627  5674 I jxcore-log: emit@events.js:82:1
10-26 02:44:12.372  5627  5674 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-26 02:44:12.372  5627  5674 I jxcore-log: emit@events.js:82:1'
10-26 02:44:12.372  5627  5674 I jxcore-log: 
,10-26 02:44:12.376  5627  5674 I jxcore-log: 2016-10-26 00:44:12 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-26 02:44:12.376  5627  5674 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-26 02:44:12.376  5627  5674 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-26 02:44:12.376  5627  5674 I jxcore-log: emit@events.js:82:1
10-26 02:44:12.376  5627  5674 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-26 02:44:12.376  5627  5674 I jxcore-log: emit@events.js:82:1'
10-26 02:44:12.376  5627  5674 I jxcore-log: 
,10-26 02:44:13.621  5627  5674 I jxcore-log: 2016-10-26 00:44:13 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-26 02:44:13.621  5627  5674 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-26 02:44:13.621  5627  5674 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-26 02:44:13.621  5627  5674 I jxcore-log: emit@events.js:82:1
10-26 02:44:13.621  5627  5674 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-26 02:44:13.621  5627  5674 I jxcore-log: emit@events.js:82:1'
10-26 02:44:13.621  5627  5674 I jxcore-log: 
,10-26 02:44:13.625  5627  5674 I jxcore-log: 2016-10-26 00:44:13 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-26 02:44:13.625  5627  5674 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-26 02:44:13.625  5627  5674 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-26 02:44:13.625  5627  5674 I jxcore-log: emit@events.js:82:1
10-26 02:44:13.625  5627  5674 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-26 02:44:13.625  5627  5674 I jxcore-log: emit@events.js:82:1'
10-26 02:44:13.625  5627  5674 I jxcore-log: 
,10-26 02:44:14.683  5627  5674 I jxcore-log: 2016-10-26 00:44:14 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-26 02:44:14.683  5627  5674 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-26 02:44:14.683  5627  5674 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-26 02:44:14.683  5627  5674 I jxcore-log: emit@events.js:82:1
10-26 02:44:14.683  5627  5674 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-26 02:44:14.683  5627  5674 I jxcore-log: emit@events.js:82:1'
10-26 02:44:14.683  5627  5674 I jxcore-log: 
,10-26 02:44:14.688  5627  5674 I jxcore-log: 2016-10-26 00:44:14 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-26 02:44:14.688  5627  5674 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-26 02:44:14.688  5627  5674 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-26 02:44:14.688  5627  5674 I jxcore-log: emit@events.js:82:1
10-26 02:44:14.688  5627  5674 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-26 02:44:14.688  5627  5674 I jxcore-log: emit@events.js:82:1'
10-26 02:44:14.688  5627  5674 I jxcore-log: 
,10-26 02:44:15.718  5627  5674 I jxcore-log: 2016-10-26 00:44:15 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-26 02:44:15.718  5627  5674 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-26 02:44:15.718  5627  5674 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-26 02:44:15.718  5627  5674 I jxcore-log: emit@events.js:82:1
10-26 02:44:15.718  5627  5674 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-26 02:44:15.718  5627  5674 I jxcore-log: emit@events.js:82:1'
10-26 02:44:15.718  5627  5674 I jxcore-log: 
,10-26 02:44:15.723  5627  5674 I jxcore-log: 2016-10-26 00:44:15 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-26 02:44:15.723  5627  5674 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-26 02:44:15.723  5627  5674 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-26 02:44:15.723  5627  5674 I jxcore-log: emit@events.js:82:1
10-26 02:44:15.723  5627  5674 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-26 02:44:15.723  5627  5674 I jxcore-log: emit@events.js:82:1'
10-26 02:44:15.723  5627  5674 I jxcore-log: 
,10-26 02:44:16.753  5627  5674 I jxcore-log: 2016-10-26 00:44:16 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-26 02:44:16.753  5627  5674 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-26 02:44:16.753  5627  5674 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-26 02:44:16.753  5627  5674 I jxcore-log: emit@events.js:82:1
10-26 02:44:16.753  5627  5674 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-26 02:44:16.753  5627  5674 I jxcore-log: emit@events.js:82:1'
10-26 02:44:16.753  5627  5674 I jxcore-log: 
,10-26 02:44:16.757  5627  5674 I jxcore-log: 2016-10-26 00:44:16 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-26 02:44:16.757  5627  5674 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-26 02:44:16.757  5627  5674 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-26 02:44:16.757  5627  5674 I jxcore-log: emit@events.js:82:1
10-26 02:44:16.757  5627  5674 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-26 02:44:16.757  5627  5674 I jxcore-log: emit@events.js:82:1'
10-26 02:44:16.757  5627  5674 I jxcore-log: 
,10-26 02:44:17.858  5627  5674 I jxcore-log: 2016-10-26 00:44:17 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-26 02:44:17.858  5627  5674 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-26 02:44:17.858  5627  5674 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-26 02:44:17.858  5627  5674 I jxcore-log: emit@events.js:82:1
10-26 02:44:17.858  5627  5674 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-26 02:44:17.858  5627  5674 I jxcore-log: emit@events.js:82:1'
10-26 02:44:17.858  5627  5674 I jxcore-log: 
,10-26 02:44:17.866  5627  5674 I jxcore-log: 2016-10-26 00:44:17 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-26 02:44:17.866  5627  5674 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-26 02:44:17.866  5627  5674 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-26 02:44:17.866  5627  5674 I jxcore-log: emit@events.js:82:1
10-26 02:44:17.866  5627  5674 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-26 02:44:17.866  5627  5674 I jxcore-log: emit@events.js:82:1'
10-26 02:44:17.866  5627  5674 I jxcore-log: 
,10-26 02:44:18.903  5627  5674 I jxcore-log: 2016-10-26 00:44:18 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-26 02:44:18.903  5627  5674 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-26 02:44:18.903  5627  5674 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-26 02:44:18.903  5627  5674 I jxcore-log: emit@events.js:82:1
10-26 02:44:18.903  5627  5674 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-26 02:44:18.903  5627  5674 I jxcore-log: emit@events.js:82:1'
10-26 02:44:18.903  5627  5674 I jxcore-log: 
,10-26 02:44:18.908  5627  5674 I jxcore-log: 2016-10-26 00:44:18 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-26 02:44:18.908  5627  5674 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-26 02:44:18.908  5627  5674 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-26 02:44:18.908  5627  5674 I jxcore-log: emit@events.js:82:1
10-26 02:44:18.908  5627  5674 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-26 02:44:18.908  5627  5674 I jxcore-log: emit@events.js:82:1'
10-26 02:44:18.908  5627  5674 I jxcore-log: 
,10-26 02:44:19.947  5627  5674 I jxcore-log: 2016-10-26 00:44:19 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-26 02:44:19.947  5627  5674 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-26 02:44:19.947  5627  5674 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-26 02:44:19.947  5627  5674 I jxcore-log: emit@events.js:82:1
10-26 02:44:19.947  5627  5674 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-26 02:44:19.947  5627  5674 I jxcore-log: emit@events.js:82:1'
10-26 02:44:19.947  5627  5674 I jxcore-log: 
,10-26 02:44:19.950  5627  5674 I jxcore-log: 2016-10-26 00:44:19 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-26 02:44:19.950  5627  5674 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-26 02:44:19.950  5627  5674 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-26 02:44:19.950  5627  5674 I jxcore-log: emit@events.js:82:1
10-26 02:44:19.950  5627  5674 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-26 02:44:19.950  5627  5674 I jxcore-log: emit@events.js:82:1'
10-26 02:44:19.950  5627  5674 I jxcore-log: 
,10-26 02:44:20.982  5627  5674 I jxcore-log: 2016-10-26 00:44:20 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-26 02:44:20.982  5627  5674 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-26 02:44:20.982  5627  5674 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-26 02:44:20.982  5627  5674 I jxcore-log: emit@events.js:82:1
10-26 02:44:20.982  5627  5674 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-26 02:44:20.982  5627  5674 I jxcore-log: emit@events.js:82:1'
10-26 02:44:20.982  5627  5674 I jxcore-log: 
,10-26 02:44:20.986  5627  5674 I jxcore-log: 2016-10-26 00:44:20 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-26 02:44:20.986  5627  5674 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-26 02:44:20.986  5627  5674 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-26 02:44:20.986  5627  5674 I jxcore-log: emit@events.js:82:1
10-26 02:44:20.986  5627  5674 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-26 02:44:20.986  5627  5674 I jxcore-log: emit@events.js:82:1'
10-26 02:44:20.986  5627  5674 I jxcore-log: 
,10-26 02:44:21.347   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,10-26 02:44:22.017  5627  5674 I jxcore-log: 2016-10-26 00:44:22 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-26 02:44:22.017  5627  5674 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-26 02:44:22.017  5627  5674 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-26 02:44:22.017  5627  5674 I jxcore-log: emit@events.js:82:1
10-26 02:44:22.017  5627  5674 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-26 02:44:22.017  5627  5674 I jxcore-log: emit@events.js:82:1'
10-26 02:44:22.017  5627  5674 I jxcore-log: 
,10-26 02:44:22.021  5627  5674 I jxcore-log: 2016-10-26 00:44:22 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-26 02:44:22.021  5627  5674 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-26 02:44:22.021  5627  5674 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-26 02:44:22.021  5627  5674 I jxcore-log: emit@events.js:82:1
10-26 02:44:22.021  5627  5674 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-26 02:44:22.021  5627  5674 I jxcore-log: emit@events.js:82:1'
10-26 02:44:22.021  5627  5674 I jxcore-log: 
,10-26 02:44:22.348   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,10-26 02:44:23.050  5627  5674 I jxcore-log: 2016-10-26 00:44:23 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-26 02:44:23.050  5627  5674 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-26 02:44:23.050  5627  5674 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-26 02:44:23.050  5627  5674 I jxcore-log: emit@events.js:82:1
10-26 02:44:23.050  5627  5674 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-26 02:44:23.050  5627  5674 I jxcore-log: emit@events.js:82:1'
10-26 02:44:23.050  5627  5674 I jxcore-log: 
,10-26 02:44:23.059  5627  5674 E jxcore  : Error!: error is undefined
10-26 02:44:23.059  5627  5674 E jxcore  : Stack: [{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/lib/CoordinatedClient.js","_functionName":"CoordinatedClient.prototype._error","_lineNumber":"220","_columnNumber":"1","_msg":"    at CoordinatedClient.prototype._error@/data/data/com.test.thalitest/files/www/jxcore/lib/CoordinatedClient.js:220:1"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/component-emitter/index.js","_functionName":"Emitter.prototype.emit","_lineNumber":"131","_columnNumber":"7","_msg":"    at Emitter.prototype.emit@/data/data/com.test.thalitest/files/www/jxcore/node_modules/component-emitter/index.js:131:7"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/socket.js","_functionName":"Socket.prototype.emit","_lineNumber":"133","_columnNumber":"5","_msg":"    at Socket.prototype.emit@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/socket.js:133:5"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js","_functionName":"Manager.prototype.emitAll","_lineNumber":"81","_columnNumber":"7","_msg":"    at Manager.prototype.emitAll@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:81:7"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js","_functionName":"Manager.prototype.reconnect","_lineNumber":"507","_columnNumber":"5","_msg":"    at Manager.prototype.reconnect@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:507:5"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js","_functionName":"Manager.prototype.reconnect/timer</<","_lineNumber":"528","_columnNumber":"11","_msg":"    at Manager.prototype.reconnect/timer</<@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:528:11"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js","_functionName":"Manager.prototype.connect/errorSub<","_lineNumber":"235","_columnNumber":"7","_msg":"    at Manager.prototype.connect/errorSub<@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:235:7"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/node_modules/component-emitter/index.js","_functionName":"Emitter.prototype.emit","_lineNumber":"134","_columnNumber":"7","_msg":"    at Emitter.prototype.emit@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/node_modules/component-emitter/index.js:134:7"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/socket.js","_functionName":"Socket.prototype.onError","_lineNumber":"670","_columnNumber":"3","_msg":"    at Socket.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/socket.js:670:3"}]
,10-26 02:44:23.065  5627  5674 I jxcore-log: 2016-10-26 00:44:23 - ERROR TestsProcess: 'uncaught exception, error: 'TypeError: error is undefined', stack: 'TypeError: error is undefined
10-26 02:44:23.065  5627  5674 I jxcore-log:     at CoordinatedClient.prototype._error@/data/data/com.test.thalitest/files/www/jxcore/lib/CoordinatedClient.js:220:1
10-26 02:44:23.065  5627  5674 I jxcore-log:     at Emitter.prototype.emit@/data/data/com.test.thalitest/files/www/jxcore/node_modules/component-emitter/index.js:131:7
10-26 02:44:23.065  5627  5674 I jxcore-log:     at Socket.prototype.emit@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/socket.js:133:5
10-26 02:44:23.065  5627  5674 I jxcore-log:     at Manager.prototype.emitAll@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:81:7
10-26 02:44:23.065  5627  5674 I jxcore-log:     at Manager.prototype.reconnect@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:507:5
10-26 02:44:23.065  5627  5674 I jxcore-log:     at Manager.prototype.reconnect/timer</<@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:528:11
10-26 02:44:23.065  5627  5674 I jxcore-log:     at Manager.prototype.connect/errorSub<@/data/data/com.test.thalitest/files/www/jxcore/node_modules/sock
,10-26 02:44:23.067  5627  5674 I jxcore-log: 2016-10-26 00:44:23 - ERROR TestsProcess: '****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****'
10-26 02:44:23.067  5627  5674 I jxcore-log: 
,10-26 02:44:23.069  5627  5674 E jxcore-log: TypeError: 
10-26 02:44:23.069  5627  5674 E jxcore-log: error is undefined
10-26 02:44:23.069  5627  5674 E jxcore-log:  (/data/data/com.test.thalitest/files/www/jxcore/lib/CoordinatedClient.js 220:0)
10-26 02:44:23.069  5627  5674 E jxcore-log: 
,10-26 02:44:23.168   926  3559 I WindowState: WIN DEATH: Window{a015604 u0 com.test.thalitest/com.test.thalitest.MainActivity}
10-26 02:44:23.168   926  2994 D WifiService: Client connection lost with reason: 4
,10-26 02:44:23.168   926  3727 D GraphicsStats: Buffer count: 2
,10-26 02:44:23.179   526   526 I Zygote  : Process 5627 exited cleanly (139)
,10-26 02:44:23.184   926  3795 I ActivityManager: Process com.test.thalitest (pid 5627) has died
,10-26 02:44:23.201   926  3795 I ActivityManager: Start proc 5975:com.test.thalitest/u0a77 for activity com.test.thalitest/.MainActivity
,10-26 02:44:23.269  5975  5975 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011750)
,10-26 02:44:23.287  5975  5975 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,10-26 02:44:23.293  5975  5975 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 1627-1630)
,10-26 02:44:23.293  5975  5975 I LibraryLoader: Expected native library version number "",actual native library version number ""
,10-26 02:44:23.301  5975  5975 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {382b71d}
,10-26 02:44:23.301  5975  5975 I LibraryLoader: Expected native library version number "",actual native library version number ""
,10-26 02:44:23.301  5975  5975 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,10-26 02:44:23.305  5975  5975 I BrowserStartupController: Initializing chromium process, singleProcess=true
,10-26 02:44:23.305  5975  5975 E SysUtils: ApplicationContext is null in ApplicationStatus
,10-26 02:44:23.315  5975  5975 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,10-26 02:44:23.323  5975  5975 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,10-26 02:44:23.323  5975  5975 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
10-26 02:44:23.323  5975  5975 I Adreno  : QUALCOMM build                   : 63c06b2, I8366cd0437
10-26 02:44:23.323  5975  5975 I Adreno  : Build Date                       : 12/06/15
10-26 02:44:23.323  5975  5975 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
10-26 02:44:23.323  5975  5975 I Adreno  : Local Branch                     : mybranch17112971
10-26 02:44:23.323  5975  5975 I Adreno  : Remote Branch                    : quic/LA.BF64.1.2.9_v2
10-26 02:44:23.323  5975  5975 I Adreno  : Remote Branch                    : NONE
10-26 02:44:23.323  5975  5975 I Adreno  : Reconstruct Branch               : NOTHING
,10-26 02:44:23.349   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,10-26 02:44:23.354   926   943 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2af68de:true
,10-26 02:44:23.367  2455  2455 W Binder_3: type=1400 audit(0.0:123): avc: denied { ioctl } for path="socket:[14745]" dev="sockfs" ino=14745 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,10-26 02:44:23.367  2455  2455 W Binder_3: type=1400 audit(0.0:124): avc: denied { ioctl } for path="socket:[14745]" dev="sockfs" ino=14745 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,10-26 02:44:23.380  5975  5975 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,10-26 02:44:23.387  5975  5975 D SystemWebViewEngine: CordovaWebView is running on device made by: Huawei
,10-26 02:44:23.410   407   407 W Binder_2: type=1400 audit(0.0:125): avc: denied { ioctl } for path="socket:[33158]" dev="sockfs" ino=33158 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,10-26 02:44:23.414  5975  6011 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
10-26 02:44:23.410   407   407 W Binder_2: type=1400 audit(0.0:126): avc: denied { ioctl } for path="socket:[33158]" dev="sockfs" ino=33158 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,10-26 02:44:23.417  3831  3831 W Binder_B: type=1400 audit(0.0:127): avc: denied { ioctl } for path="socket:[14756]" dev="sockfs" ino=14756 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,10-26 02:44:23.417  3831  3831 W Binder_B: type=1400 audit(0.0:128): avc: denied { ioctl } for path="socket:[14756]" dev="sockfs" ino=14756 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
10-26 02:44:23.421  5975  5998 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,10-26 02:44:23.456  5975  6011 I OpenGLRenderer: Initialized EGL, version 1.4
,10-26 02:44:23.474   926  3793 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 5627 uid 10077
,10-26 02:44:23.470  3793  3793 W Binder_9: type=1400 audit(0.0:129): avc: denied { ioctl } for path="socket:[33166]" dev="sockfs" ino=33166 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,10-26 02:44:23.470  3793  3793 W Binder_9: type=1400 audit(0.0:130): avc: denied { ioctl } for path="socket:[33166]" dev="sockfs" ino=33166 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
10-26 02:44:23.474  3559  3559 W Binder_6: type=1400 audit(0.0:131): avc: denied { ioctl } for path="socket:[33165]" dev="sockfs" ino=33165 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
10-26 02:44:23.474  3559  3559 W Binder_6: type=1400 audit(0.0:132): avc: denied { ioctl } for path="socket:[33165]" dev="sockfs" ino=33165 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
10-26 02:44:23.478  3649  3649 I Keyboard.Facilitator: onFinishInput()
,10-26 02:44:23.498  5975  5975 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 5975
,10-26 02:44:23.500  5973  5973 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
10-26 02:44:23.501   926   944 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +279ms (total +313ms)
,10-26 02:44:23.503  5973  5973 D AndroidRuntime: CheckJNI is OFF
,10-26 02:44:23.524  5973  5973 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,10-26 02:44:23.549  5973  5973 I Radio-JNI: register_android_hardware_Radio DONE
,10-26 02:44:23.557  5975  5975 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,10-26 02:44:23.565  5973  5973 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,10-26 02:44:23.570   926   939 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=-1: uninstall pkg
,10-26 02:44:23.571   926   939 I ActivityManager: Killing 5975:com.test.thalitest/u0a77 (adj 0): stop com.test.thalitest
,10-26 02:44:23.600   926  3559 D GraphicsStats: Buffer count: 2
,10-26 02:44:23.600   926  3106 I WindowState: WIN DEATH: Window{eb31d45 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,10-26 02:44:23.671   926   939 W ActivityManager: Failed trying to unstop package com.test.thalitest: java.lang.IllegalArgumentException: Unknown package: com.test.thalitest
,10-26 02:44:23.672   926   939 W PackageManager: Package com.test.thalitest is missing; assuming frozen
,10-26 02:44:23.672   926   949 I art     : Starting a blocking GC Explicit
,10-26 02:44:23.673   926   939 E ActivityManager: Failure starting process com.test.thalitest
10-26 02:44:23.673   926   939 E ActivityManager: java.lang.RuntimeException: Package com.test.thalitest is frozen!
10-26 02:44:23.673   926   939 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3278)
10-26 02:44:23.673   926   939 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3237)
10-26 02:44:23.673   926   939 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3116)
10-26 02:44:23.673   926   939 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1395)
10-26 02:44:23.673   926   939 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:2007)
10-26 02:44:23.673   926   939 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1554)
10-26 02:44:23.673   926   939 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2735)
10-26 02:44:23.673   926   939 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2724)
10-26 02:44:23.673   926   939 E ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4598)
10-26 02:44:23.673   926   939 E ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:5955)
10-26 02:44:23.673   926   939 E ActivityManager: 	at com.android.server.am.ActivityManagerService.killPackageProcessesLocked(ActivityManagerService.java:5614)
10-26 02:44:23.673   926   939 E ActivityManager: 	at com.android.server.am.ActivityManagerService.forceStopPackageLocked(ActivityManagerService.java:5763)
10-26 02:44:23.673   926   939 E ActivityManager: 	at com.android.server.am.ActivityManagerService.-wrap1(ActivityManagerService.java)
10-26 02:44:23.673   926   939 E ActivityManager: 	at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:1736)
10-26 02:44:23.673   926   939 E ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-26 02:44:23.673   926   939 E ActivityManager: 	at android.os.Looper.loop(Looper.java:148)
10-26 02:44:23.673   926   939 E ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
10-26 02:44:23.673   926   939 E ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
10-26 02:44:23.674   926   939 I ActivityManager:   Force finishing activity ActivityRecord{966da55 u0 com.test.thalitest/.MainActivity t66}
,10-26 02:44:23.679   926  3793 W ActivityManager: Spurious death for ProcessRecord{a9899cb 0:com.test.thalitest/u0a77}, curProc for 5975: null
,10-26 02:44:23.761   926   949 I art     : Explicit concurrent mark sweep GC freed 49086(2MB) AllocSpace objects, 12(256KB) LOS objects, 33% free, 28MB/43MB, paused 1.609ms total 88.543ms
,10-26 02:44:23.780   926   949 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,10-26 02:44:23.784  5973  5973 I art     : System.exit called, status: 0
,10-26 02:44:23.784  5973  5973 I AndroidRuntime: VM exiting with result code 0.
,10-26 02:44:23.800   926   949 I ActivityManager: Start proc 6024:com.android.defcontainer/u0a7 for service com.android.defcontainer/.DefaultContainerService
10-26 02:44:23.800   926   949 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=0: pkg removed
,10-26 02:44:23.806   926   939 I ActivityManager: Exiting empty application process com.test.thalitest (null)
10-26 02:44:23.811  5858  5858 D BluetoothMapAppObserver: onReceive
10-26 02:44:23.811  5858  5858 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
,10-26 02:44:23.812  4062  4166 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
10-26 02:44:23.813  3649  3649 I Keyboard.Facilitator: resetDictionaries() : en_US
10-26 02:44:23.819   926  2947 I InputReader: Reconfiguring input devices.  changes=0x00000010
,10-26 02:44:23.841  3380  6037 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,10-26 02:44:23.843  3649  6035 I Keyboard.Facilitator.DecoderInitializer: run()
,10-26 02:44:23.863  3774  3774 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,10-26 02:44:23.872  3649  6035 I Decoder : createOrResetDecoder
,10-26 02:44:23.878  3545  3545 E NetworkScheduler.SchedulerReceiver: Invalid parameter app
,10-26 02:44:23.878  3545  3545 E NetworkScheduler.SchedulerReceiver: Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,10-26 02:44:23.887  4137  4137 W kworker/3:2: type=1400 audit(0.0:133): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,10-26 02:44:23.894  4137  4137 W kworker/3:2: type=1400 audit(0.0:134): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,10-26 02:44:23.897  3766  3766 W Binder_8: type=1400 audit(0.0:135): avc: denied { ioctl } for path="socket:[29741]" dev="sockfs" ino=29741 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,10-26 02:44:23.897  3766  3766 W Binder_8: type=1400 audit(0.0:136): avc: denied { ioctl } for path="socket:[29741]" dev="sockfs" ino=29741 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,10-26 02:44:23.897   926  3766 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 5975 uid 10077
,10-26 02:44:23.901   926   926 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
10-26 02:44:23.903  3807  3914 E SQLiteLog: (3850) statement aborts at 23: [DELETE FROM icons WHERE componentName LIKE ? AND profileId = ?] disk I/O error
10-26 02:44:23.904   926   938 E PackageManager: Failed to write settings, restoring backup
10-26 02:44:23.904   926   938 E PackageManager: java.io.IOException: write failed: EBADF (Bad file descriptor)
10-26 02:44:23.904   926   938 E PackageManager: 	at libcore.io.IoBridge.write(IoBridge.java:498)
10-26 02:44:23.904   926   938 E PackageManager: 	at java.io.FileOutputStream.write(FileOutputStream.java:186)
10-26 02:44:23.904   926   938 E PackageManager: 	at java.io.OutputStreamWriter.flushBytes(OutputStreamWriter.java:170)
10-26 02:44:23.904   926   938 E PackageManager: 	at java.io.OutputStreamWriter.flush(OutputStreamWriter.java:161)
10-26 02:44:23.904   926   938 E PackageManager: 	at java.io.BufferedWriter.flush(BufferedWriter.java:124)
10-26 02:44:23.904   926   938 E PackageManager: 	at org.kxml2.io.KXmlSerializer.flush(KXmlSerializer.java:477)
10-26 02:44:23.904   926   938 E PackageManager: 	at org.kxml2.io.KXmlSerializer.endDocument(KXmlSerializer.java:169)
10-26 02:44:23.904   926   938 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.writePermissionsSync(Settings.java:4650)
10-26 02:44:23.904   926   938 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.-wrap1(Settings.java)
10-26 02:44:23.904   926   938 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence$MyHandler.handleMessage(Settings.java:4830)
10-26 02:44:23.904   926   938 E PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-26 02:44:23.904   926   938 E PackageManager: 	at android.os.Looper.loop(Looper.java:148)
10-26 02:44:23.904   926   938 E PackageManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
10-26 02:44:23.904   926   938 E PackageManager: Caused by: android.system.ErrnoException: write failed: EBADF (Bad file descriptor)
10-26 02:44:23.904   926   938 E PackageManager: 	at libcore.io.Posix.writeBytes(Native Method)
10-26 02:44:23.904   926   938 E PackageManager: 	at libcore.io.Posix.write(Posix.java:271)
10-26 02:44:23.904   926   938 E PackageManager: 	at libcore.io.BlockGuardOs.write(BlockGuardOs.java:313)
10-26 02:44:23.904   926   938 E PackageManager: 	at libcore.io.IoBridge.write(IoBridge.java:493)
10-26 02:44:23.904   926   938 E PackageManager: 	... 12 more
10-26 02:44:23.907  3649  3649 I Keyboard.Facilitator: onFinishInput()
,10-26 02:44:23.916   926  3795 I ActivityManager: Start proc 6043:com.google.android.googlequicksearchbox:crash_report/u0a29 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
,--------- beginning of crash
10-26 02:44:23.917  3807  3914 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
10-26 02:44:23.917  3807  3914 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 3807
10-26 02:44:23.917  3807  3914 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
10-26 02:44:23.917  3807  3914 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
10-26 02:44:23.917  3807  3914 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
10-26 02:44:23.917  3807  3914 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
10-26 02:44:23.917  3807  3914 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
10-26 02:44:23.917  3807  3914 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
10-26 02:44:23.917  3807  3914 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
10-26 02:44:23.917  3807  3914 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
10-26 02:44:23.917  3807  3914 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
10-26 02:44:23.917  3807  3914 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
10-26 02:44:23.917  3807  3914 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
10-26 02:44:23.917  3807  3914 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,10-26 02:44:23.920  4137  4137 W kworker/3:2: type=1400 audit(0.0:137): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,10-26 02:44:23.923  3717  6050 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
,10-26 02:44:23.926  3717  6050 D AccountUtils: Clearing selected account for com.test.thalitest
10-26 02:44:23.926   926   936 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,10-26 02:44:23.936  3807  3914 I Process : Sending signal. PID: 3807 SIG: 9
,10-26 02:44:23.962  3545  3545 I ConfigService: onCreate
,10-26 02:44:23.964  3545  6059 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/config.db'.
10-26 02:44:23.964  3545  6059 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
10-26 02:44:23.964  3545  6059 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
10-26 02:44:23.964  3545  6059 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
10-26 02:44:23.964  3545  6059 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
10-26 02:44:23.964  3545  6059 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
10-26 02:44:23.964  3545  6059 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
10-26 02:44:23.964  3545  6059 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
10-26 02:44:23.964  3545  6059 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
10-26 02:44:23.964  3545  6059 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
10-26 02:44:23.964  3545  6059 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
10-26 02:44:23.964  3545  6059 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
10-26 02:44:23.964  3545  6059 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
10-26 02:44:23.964  3545  6059 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
10-26 02:44:23.964  3545  6059 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
10-26 02:44:23.964  3545  6059 E SQLiteDatabase: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
10-26 02:44:23.964  3545  6059 E SQLiteDatabase: 	at com.google.android.gms.config.j.run(SourceFile:152)
10-26 02:44:23.964  3545  6059 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
,10-26 02:44:23.965  3545  6059 E SQLiteOpenHelper: Couldn't open config.db for writing (will try read-only):
10-26 02:44:23.965  3545  6059 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
10-26 02:44:23.965  3545  6059 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
10-26 02:44:23.965  3545  6059 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
10-26 02:44:23.965  3545  6059 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
10-26 02:44:23.965  3545  6059 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
10-26 02:44:23.965  3545  6059 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
10-26 02:44:23.965  3545  6059 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
10-26 02:44:23.965  3545  6059 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
10-26 02:44:23.965  3545  6059 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
10-26 02:44:23.965  3545  6059 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
10-26 02:44:23.965  3545  6059 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
10-26 02:44:23.965  3545  6059 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
10-26 02:44:23.965  3545  6059 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
10-26 02:44:23.965  3545  6059 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
10-26 02:44:23.965  3545  6059 E SQLiteOpenHelper: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
10-26 02:44:23.965  3545  6059 E SQLiteOpenHelper: 	at com.google.android.gms.config.j.run(SourceFile:152)
10-26 02:44:23.965  3545  6059 E SQLiteOpenHelper: 	at java.lang.Thread.run(Thread.java:818)
10-26 02:44:23.967  3545  6059 W SQLiteOpenHelper: Opened config.db in read-only mode
,10-26 02:44:23.978  3649  6035 I Keyboard.Facilitator.MainLanguageModelLoader: run()
,10-26 02:44:23.991   382   479 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0

```
