#### Test 91818238ff180c4_thali07_Huawei-Nexus 6P Logs


```
--------- beginning of main
11-03 12:11:19.440  4074  4250 I Icing   : Indexing 3C763AF371F9E97B4ECFEA01A338ADB468C38476 from com.google.android.googlequicksearchbox
11-03 12:11:19.513  4074  4250 I Icing   : Indexing done 3C763AF371F9E97B4ECFEA01A338ADB468C38476
,11-03 12:11:19.922  5585  5585 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
11-03 12:11:19.927  5585  5585 D AndroidRuntime: CheckJNI is OFF
11-03 12:11:19.954  5585  5585 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
11-03 12:11:19.990  5585  5585 I Radio-JNI: register_android_hardware_Radio DONE
11-03 12:11:20.005  5585  5585 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
11-03 12:11:20.017   928  3807 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
11-03 12:11:20.035  5585  5585 D AndroidRuntime: Shutting down VM
11-03 12:11:20.054  3979  3989 W SearchService: Abort, client detached.
11-03 12:11:20.062  3979  3979 I HotwordDetector: Closing mic
11-03 12:11:20.063  3979  4236 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@7fa43a6
11-03 12:11:20.063  3979  4251 E AudioRecord-JNI: Error -4 during AudioRecord native read
11-03 12:11:20.085   928  3622 I ActivityManager: Start proc 5594:com.test.thalitest/u0a77 for activity com.test.thalitest/.MainActivity
11-03 12:11:20.136   513  4255 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
11-03 12:11:20.139   513  4255 D audio_hw_primary: disable_snd_device: snd_device(63: voice-rec-mic)
11-03 12:11:20.144   513  4255 I soundtrigger: audio_extn_sound_trigger_update_device_status: device 0x3f of type 1 for Event 0
11-03 12:11:20.145   513  4255 D sound_trigger_platform: platform_stdev_check_and_update_concurrency: concurrency active 0, tx 0, rx 0, concurrency session_allowed 1
11-03 12:11:20.145   513  3025 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
11-03 12:11:20.148  3979  4245 I MicroRecognitionRnrImpl: Stopping hotword detection.
11-03 12:11:20.148  3979  4248 I MicroRecognitionRnrImpl: Detection finished
11-03 12:11:20.177  5594  5594 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011750)
11-03 12:11:20.214  5594  5594 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,11-03 12:11:20.273  5594  5594 I LibraryLoader: Time to load native libraries: 54 ms (timestamps 4991-5045)
,11-03 12:11:20.273  5594  5594 I LibraryLoader: Expected native library version number "",actual native library version number ""
,11-03 12:11:20.306  5594  5594 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {7e2e5f6}
,11-03 12:11:20.306  5594  5594 I LibraryLoader: Expected native library version number "",actual native library version number ""
11-03 12:11:20.307  5594  5594 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,11-03 12:11:20.312  5594  5594 I BrowserStartupController: Initializing chromium process, singleProcess=true
,11-03 12:11:20.314  5594  5594 E SysUtils: ApplicationContext is null in ApplicationStatus
,11-03 12:11:20.365  5594  5594 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,11-03 12:11:20.382  5594  5594 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,11-03 12:11:20.382  5594  5594 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
11-03 12:11:20.382  5594  5594 I Adreno  : QUALCOMM build                   : 63c06b2, I8366cd0437
11-03 12:11:20.382  5594  5594 I Adreno  : Build Date                       : 12/06/15
11-03 12:11:20.382  5594  5594 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
11-03 12:11:20.382  5594  5594 I Adreno  : Local Branch                     : mybranch17112971
11-03 12:11:20.382  5594  5594 I Adreno  : Remote Branch                    : quic/LA.BF64.1.2.9_v2
11-03 12:11:20.382  5594  5594 I Adreno  : Remote Branch                    : NONE
11-03 12:11:20.382  5594  5594 I Adreno  : Reconstruct Branch               : NOTHING
,11-03 12:11:20.438   928   945 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2a699c8:true
,11-03 12:11:20.479  3851  3851 W Binder_4: type=1400 audit(0.0:99): avc: denied { ioctl } for path="socket:[32912]" dev="sockfs" ino=32912 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-03 12:11:20.479  3851  3851 W Binder_4: type=1400 audit(0.0:100): avc: denied { ioctl } for path="socket:[32912]" dev="sockfs" ino=32912 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-03 12:11:20.490  5594  5594 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,11-03 12:11:20.499  5594  5594 D SystemWebViewEngine: CordovaWebView is running on device made by: Huawei
,11-03 12:11:20.522   408   408 W Binder_2: type=1400 audit(0.0:101): avc: denied { ioctl } for path="socket:[31345]" dev="sockfs" ino=31345 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-03 12:11:20.526  5594  5631 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
11-03 12:11:20.522   408   408 W Binder_2: type=1400 audit(0.0:102): avc: denied { ioctl } for path="socket:[31345]" dev="sockfs" ino=31345 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-03 12:11:20.525  3622  3622 W Binder_6: type=1400 audit(0.0:103): avc: denied { ioctl } for path="socket:[19342]" dev="sockfs" ino=19342 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-03 12:11:20.525  3622  3622 W Binder_6: type=1400 audit(0.0:104): avc: denied { ioctl } for path="socket:[19342]" dev="sockfs" ino=19342 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-03 12:11:20.531  5594  5618 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,11-03 12:11:20.558  5594  5631 I OpenGLRenderer: Initialized EGL, version 1.4
,11-03 12:11:20.629  3186  3186 W Binder_4: type=1400 audit(0.0:105): avc: denied { ioctl } for path="socket:[30448]" dev="sockfs" ino=30448 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-03 12:11:20.631   928   946 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +570ms
,11-03 12:11:20.629  3186  3186 W Binder_4: type=1400 audit(0.0:106): avc: denied { ioctl } for path="socket:[30448]" dev="sockfs" ino=30448 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
11-03 12:11:20.629   938   938 W Binder_1: type=1400 audit(0.0:107): avc: denied { ioctl } for path="socket:[30447]" dev="sockfs" ino=30447 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
11-03 12:11:20.629   938   938 W Binder_1: type=1400 audit(0.0:108): avc: denied { ioctl } for path="socket:[30447]" dev="sockfs" ino=30447 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-03 12:11:20.635  3679  3679 I Keyboard.Facilitator: onFinishInput()
,11-03 12:11:20.667  5594  5594 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 5594
,11-03 12:11:20.781  5594  5594 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,11-03 12:11:20.988  5594  5634 D jxcore_app_log: JniHelper::setJavaVM(0xf4e3c000), pthread_self() = -592180944
,11-03 12:11:20.991  5594  5634 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
11-03 12:11:20.991  5594  5634 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
11-03 12:11:20.991  5594  5634 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
11-03 12:11:20.991  5594  5634 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
11-03 12:11:20.991  5594  5634 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,11-03 12:11:20.991  5594  5634 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@cdddc45 added. We now have 1 listener(s)
,11-03 12:11:20.994  5594  5634 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 60:83:34:25:D7:D4
,11-03 12:11:20.994  5594  5634 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
,11-03 12:11:20.995  5594  5634 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-03 12:11:20.995  5594  5634 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,11-03 12:11:20.998  5594  5634 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
11-03 12:11:20.998  5594  5634 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
11-03 12:11:20.998  5594  5634 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
11-03 12:11:20.998  5594  5634 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 60:83:34:25:D7:D4
11-03 12:11:20.998  5594  5634 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
11-03 12:11:20.998  5594  5634 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
11-03 12:11:20.998  5594  5634 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
11-03 12:11:20.998  5594  5634 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
11-03 12:11:20.998  5594  5634 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
11-03 12:11:20.998  5594  5634 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
11-03 12:11:20.998  5594  5634 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
11-03 12:11:20.998  5594  5634 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
11-03 12:11:20.998  5594  5634 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
11-03 12:11:20.998  5594  5634 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
11-03 12:11:20.998  5594  5634 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b5490a8 added. We now have 1 listener(s)
,11-03 12:11:20.998  5594  5634 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-03 12:11:21.004   928  2980 D WifiService: New client listening to asynchronous messages
,11-03 12:11:21.005  5594  5634 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
11-03 12:11:21.005  5594  5634 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
,11-03 12:11:21.005  5594  5634 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
,11-03 12:11:21.005  5594  5634 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
,11-03 12:11:21.005  5594  5634 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
11-03 12:11:21.007  5594  5634 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-03 12:11:21.007  5594  5634 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
,11-03 12:11:21.010  5594  5634 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,11-03 12:11:21.010  5594  5634 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-03 12:11:21.010  5594  5634 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-03 12:11:21.010  5594  5634 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-03 12:11:21.010  5594  5634 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-03 12:11:21.010  5594  5634 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-03 12:11:21.010  5594  5634 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-03 12:11:21.010  5594  5634 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-03 12:11:21.010  5594  5634 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
11-03 12:11:21.010  5594  5634 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
11-03 12:11:21.010  5594  5634 D io.jxcore.node.ConnectivityMonitor: start: OK
11-03 12:11:21.011  5594  5634 I io.jxcore.node.LifeCycleMonitor: start: OK
,11-03 12:11:21.099  5594  5594 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-03 12:11:21.104  5594  5594 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-03 12:11:21.107  5594  5594 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,11-03 12:11:21.389  5594  5641 W jxcore-log: Initializing JXcore engine
,11-03 12:11:21.389  5594  5641 W jxcore-log: JXcore engine is ready
,11-03 12:11:21.412  5641  5641 W Thread-57: type=1400 audit(0.0:109): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=11915 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,11-03 12:11:21.412  5641  5641 W Thread-57: type=1400 audit(0.0:110): avc: denied { ioctl } for path="socket:[15377]" dev="sockfs" ino=15377 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
11-03 12:11:21.412  5641  5641 W Thread-57: type=1400 audit(0.0:111): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=5964 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
11-03 12:11:21.412  5641  5641 W Thread-57: type=1400 audit(0.0:112): avc: denied { ioctl } for path="socket:[31325]" dev="sockfs" ino=31325 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:untrusted_app:s0:c512,c768 tclass=netlink_route_socket permissive=0
,11-03 12:11:21.424  5594  5641 W jxcore-log: Starting JXcore engine
,11-03 12:11:21.480  5594  5641 W jxcore-log: Platform android
11-03 12:11:21.480  5594  5641 W jxcore-log: 
,11-03 12:11:21.480  5594  5641 W jxcore-log: Process ARCH arm
11-03 12:11:21.480  5594  5641 W jxcore-log: 
,11-03 12:11:21.624  5594  5641 I jxcore-log: JXcore Cordova bridge is ready!
11-03 12:11:21.624  5594  5641 I jxcore-log: 
,11-03 12:11:21.624  5594  5641 W jxcore-log: JXcore engine is started
,11-03 12:11:21.629  5594  5634 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,11-03 12:11:21.633  5594  5594 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,11-03 12:11:23.590  3608  3608 I ConfigService: onDestroy
,11-03 12:11:25.070   928  3829 I ActivityManager: Killing 5157:com.google.android.youtube/u0a75 (adj 15): empty #17
,11-03 12:11:25.512   928  2977 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-03 12:11:29.085   545   545 I ServiceManager: Waiting for service AtCmdFwd...
,11-03 12:11:30.086   545   545 I ServiceManager: Waiting for service AtCmdFwd...
,11-03 12:11:31.088   545   545 I ServiceManager: Waiting for service AtCmdFwd...
,11-03 12:11:31.536  5594  5641 I jxcore-log: 2016-11-03 11:11:31 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
11-03 12:11:31.536  5594  5641 I jxcore-log: 
,11-03 12:11:31.538  5594  5641 I jxcore-log: 2016-11-03 11:11:31 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
11-03 12:11:31.538  5594  5641 I jxcore-log: 
,11-03 12:11:31.542  5594  5641 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-03 12:11:31.542  5594  5641 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-03 12:11:31.542  5594  5641 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-03 12:11:31.542  5594  5641 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-03 12:11:31.542  5594  5641 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-03 12:11:31.542  5594  5641 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-03 12:11:31.542  5594  5641 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-03 12:11:31.542  5594  5641 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,11-03 12:11:31.544  5594  5641 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,11-03 12:11:31.545  5594  5641 I jxcore-log: 2016-11-03 11:11:31 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
11-03 12:11:31.545  5594  5641 I jxcore-log: 
,11-03 12:11:31.547  5594  5641 I jxcore-log: 2016-11-03 11:11:31 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
11-03 12:11:31.547  5594  5641 I jxcore-log: 
,11-03 12:11:31.809  5594  5641 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,11-03 12:11:31.809  5594  5641 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@84f3c81 added. We now have 2 listener(s)
11-03 12:11:31.810  5594  5641 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-03 12:11:31.810  5594  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-03 12:11:31.811  5594  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,11-03 12:11:31.811  5594  5641 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-03 12:11:31.811  5594  5641 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@af24126 added. We now have 2 listener(s)
11-03 12:11:31.811  5594  5641 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-03 12:11:31.812  5594  5641 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,11-03 12:11:31.814  5594  5641 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,11-03 12:11:31.819  5594  5641 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-03 12:11:31.819  5594  5641 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-03 12:11:31.819  5594  5641 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-03 12:11:31.819  5594  5641 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-03 12:11:31.819  5594  5641 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-03 12:11:31.819  5594  5641 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-03 12:11:31.819  5594  5641 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-03 12:11:31.819  5594  5641 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,11-03 12:11:31.820  5594  5641 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
11-03 12:11:31.820  5594  5641 D io.jxcore.node.ConnectivityMonitor: start: OK
11-03 12:11:31.821  5594  5641 D ExecuteNativeTests: Running unit tests
11-03 12:11:31.821  5594  5641 D BluetoothAdapter: enable(): BT is already enabled..!
11-03 12:11:31.822   928  3180 D WifiService: setWifiEnabled: true pid=5594, uid=10077
,11-03 12:11:31.822   928  3180 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-03 12:11:31.827  5594  5594 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-03 12:11:31.832  5594  5594 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-03 12:11:32.089   545   545 I ServiceManager: Waiting for service AtCmdFwd...
,11-03 12:11:33.090   545   545 I ServiceManager: Waiting for service AtCmdFwd...
,11-03 12:11:33.239   928  2980 D WifiService: New client listening to asynchronous messages
,11-03 12:11:33.243  3979  5643 W CronetSyncConnectionRcs: Upload content type not set.
,11-03 12:11:33.320  4893  4927 D Finsky  : [188] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,11-03 12:11:33.321  4893  4893 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,11-03 12:11:33.324   928  3622 I ActivityManager: Killing 5233:org.codeaurora.ims/1001 (adj 15): empty #17
,11-03 12:11:34.091   545   545 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,11-03 12:11:41.826  5594  5641 I com.test.thalitest.ThaliTestRunner: Running UT
,11-03 12:11:41.888  5594  5641 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-03 12:11:41.888  5594  5641 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c19c2c8 added. We now have 3 listener(s)
,11-03 12:11:41.889  5594  5641 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-03 12:11:41.889  5594  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-03 12:11:41.889  5594  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-03 12:11:41.889  5594  5641 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,11-03 12:11:41.889  5594  5641 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f010f61 added. We now have 3 listener(s)
11-03 12:11:41.889  5594  5641 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-03 12:11:41.890  5594  5641 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
11-03 12:11:41.893  5594  5641 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,11-03 12:11:41.901  5594  5641 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-03 12:11:41.901  5594  5641 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-03 12:11:41.901  5594  5641 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-03 12:11:41.901  5594  5641 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-03 12:11:41.901  5594  5641 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-03 12:11:41.901  5594  5641 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-03 12:11:41.901  5594  5641 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-03 12:11:41.901  5594  5641 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,11-03 12:11:41.906  5594  5641 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
11-03 12:11:41.907  5594  5641 D io.jxcore.node.ConnectivityMonitor: start: OK
,11-03 12:11:41.911  5594  5594 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-03 12:11:41.912  5594  5594 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-03 12:11:41.914  5594  5641 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnConnectionTimeout
,11-03 12:11:41.914  5594  5641 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,11-03 12:11:41.914  5594  5641 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-03 12:11:41.914  5594  5641 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-03 12:11:41.914  5594  5641 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-03 12:11:41.915  5594  5641 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
11-03 12:11:41.915  5594  5641 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
11-03 12:11:41.915  5594  5641 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
11-03 12:11:41.915  5594  5641 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-03 12:11:41.915  5594  5641 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,11-03 12:11:41.915  5594  5641 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-03 12:11:41.916  5594  5641 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnBluetoothMacAddressResolved
11-03 12:11:41.917  5594  5641 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
11-03 12:11:41.918  5594  5641 I io.jxcore.node.ConnectionHelperTest: Starting test: testHasMaximumNumberOfConnections
11-03 12:11:41.919  5594  5641 I io.jxcore.node.ConnectionHelperTest: Starting test: testStart
11-03 12:11:41.919  5594  5641 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
11-03 12:11:41.920  5594  5641 V io.jxcore.node.ConnectivityMonitor: start: Already started
,11-03 12:11:41.920  5594  5641 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 1
11-03 12:11:41.920  5594  5641 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 0 -> 1
11-03 12:11:41.920  5594  5641 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
11-03 12:11:41.920  5594  5641 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
11-03 12:11:41.920  5594  5641 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
11-03 12:11:41.920  5594  5641 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-03 12:11:41.921  5594  5641 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
11-03 12:11:41.921  5594  5641 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
11-03 12:11:41.922  5594  5641 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
,11-03 12:11:41.922  5594  5641 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
11-03 12:11:41.922  5594  5641 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
11-03 12:11:41.922  5594  5641 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
,11-03 12:11:41.922  5594  5641 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-03 12:11:41.922  5594  5641 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
11-03 12:11:41.922  5594  5594 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
11-03 12:11:41.922  5594  5655 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
11-03 12:11:41.924  5594  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-03 12:11:41.925  5594  5641 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-03 12:11:41.925  5594  5641 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
11-03 12:11:41.927  5594  5655 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-03 12:11:41.928  5594  5641 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,11-03 12:11:41.930  5594  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,11-03 12:11:41.930  5594  5641 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-03 12:11:41.929  4684  4684 W Binder_1: type=1400 audit(0.0:113): avc: denied { ioctl } for path="socket:[33863]" dev="sockfs" ino=33863 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,11-03 12:11:41.932  5594  5655 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
11-03 12:11:41.932  5594  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Current thread: Thread[Thread-57,5,main], id: 57
11-03 12:11:41.932  5594  5641 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
11-03 12:11:41.933  5594  5641 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-03 12:11:41.933  5594  5641 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 01 60 83 34 25 D7 D4
11-03 12:11:41.933  5594  5641 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-03 12:11:41.929  4684  4684 W Binder_1: type=1400 audit(0.0:114): avc: denied { ioctl } for path="socket:[33863]" dev="sockfs" ino=33863 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-03 12:11:41.933  5594  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: Current thread: Thread[Thread-57,5,main], id: 57
11-03 12:11:41.933  5594  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData finished: Current thread: Thread[Thread-57,5,main], id: 57
11-03 12:11:41.933  5594  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = NOT_STARTEDCurrent thread: Thread[Thread-57,5,main], id: 57
11-03 12:11:41.933  5594  5641 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... adv data = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]Current thread: Thread[Thread-57,5,main], id: 57
,11-03 12:11:41.934  5594  5641 D BluetoothAdapter: STATE_ON
,11-03 12:11:41.937  4671  4686 D BtGatt.GattService: registerClient() - UUID=c5b5ee24-1429-4713-85dd-d7588e63023f
11-03 12:11:41.938  4671  4735 D BtGatt.GattService: onClientRegistered() - UUID=c5b5ee24-1429-4713-85dd-d7588e63023f, clientIf=5
,11-03 12:11:41.939  5594  5605 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
,11-03 12:11:41.941  4671  4737 D BtGatt.AdvertiseManager: message : 0
,11-03 12:11:41.945  4671  4737 D BtGatt.AdvertiseManager: starting multi advertising
,11-03 12:11:41.958  4671  4735 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,11-03 12:11:41.966  4671  4735 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,11-03 12:11:41.967  5594  5641 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment Current thread: Thread[Thread-57,5,main], id: 57
,11-03 12:11:41.967  5594  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTINGCurrent thread: Thread[Thread-57,5,main], id: 57
11-03 12:11:41.967  5594  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
11-03 12:11:41.968  5594  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged default (no call to listener). Current thread: Thread[Thread-57,5,main], id: 57
11-03 12:11:41.968  5594  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finishedCurrent thread: Thread[Thread-57,5,main], id: 57
11-03 12:11:41.968  5594  5641 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[Thread-57,5,main], id: 57
11-03 12:11:41.968  5594  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[Thread-57,5,main], id: 57
11-03 12:11:41.968  5594  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser started = trueCurrent thread: Thread[Thread-57,5,main], id: 57
,11-03 12:11:41.968  5594  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,11-03 12:11:41.970  5594  5641 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-03 12:11:41.970  5594  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
,11-03 12:11:41.971  5594  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
,11-03 12:11:41.972  5594  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
11-03 12:11:41.972  5594  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
11-03 12:11:41.972  5594  5641 I io.jxcore.node.ConnectionHelper: start: OK
,11-03 12:11:41.973  5594  5594 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,11-03 12:11:41.973  5594  5594 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess : Current thread: Thread[main,5,main], id: 1
11-03 12:11:41.973  5594  5594 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNINGCurrent thread: Thread[main,5,main], id: 1
,11-03 12:11:41.973  5594  5594 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
11-03 12:11:41.973  5594  5594 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged true. Current thread: Thread[main,5,main], id: 1
11-03 12:11:41.973  5594  5594 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-03 12:11:41.974  5594  5594 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-03 12:11:41.974  5594  5594 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [ADVERTISING]
11-03 12:11:41.974  5594  5594 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-03 12:11:41.974  5594  5594 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-03 12:11:41.974  5594  5594 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]Current thread: Thread[main,5,main], id: 1
11-03 12:11:41.974  5594  5594 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
11-03 12:11:41.974  5594  5594 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
,11-03 12:11:41.977  5594  5594 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-03 12:11:41.977  5594  5594 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
11-03 12:11:41.978  5594  5594 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-03 12:11:41.978  5594  5594 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-03 12:11:41.978  5594  5594 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-03 12:11:41.978  5594  5594 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finishedCurrent thread: Thread[main,5,main], id: 1
11-03 12:11:41.978  5594  5594 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,11-03 12:11:42.476  5594  5641 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-03 12:11:42.477  5594  5641 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
11-03 12:11:42.477  5594  5641 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
11-03 12:11:42.477  5594  5641 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
11-03 12:11:42.477  5594  5641 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
11-03 12:11:42.477  5594  5641 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
11-03 12:11:42.477  5594  5641 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
,11-03 12:11:42.477  5594  5641 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
11-03 12:11:42.477  5594  5641 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
11-03 12:11:42.478  5594  5641 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
11-03 12:11:42.478  5594  5641 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
11-03 12:11:42.478  5594  5641 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
11-03 12:11:42.478  5594  5641 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
11-03 12:11:42.478  5594  5641 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
11-03 12:11:42.478  5594  5641 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
11-03 12:11:42.478  5594  5641 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
11-03 12:11:42.478  5594  5641 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
11-03 12:11:42.478  5594  5641 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
11-03 12:11:42.478  5594  5641 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
11-03 12:11:42.478  5594  5641 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
11-03 12:11:42.479  5594  5641 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
,11-03 12:11:42.479  5594  5641 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
11-03 12:11:42.479  5594  5641 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
11-03 12:11:42.479  5594  5641 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
11-03 12:11:42.479  5594  5641 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
11-03 12:11:42.479  5594  5641 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
11-03 12:11:42.479  5594  5641 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
,11-03 12:11:42.479  5594  5641 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
11-03 12:11:42.479  5594  5641 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
11-03 12:11:42.479  5594  5641 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
11-03 12:11:42.479  5594  5641 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
11-03 12:11:42.480  5594  5641 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
,11-03 12:11:42.480  5594  5641 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
11-03 12:11:42.480  5594  5594 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
11-03 12:11:42.480  5594  5641 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
11-03 12:11:42.480  5594  5641 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,11-03 12:11:42.480  5594  5641 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
11-03 12:11:42.480  5594  5641 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
11-03 12:11:42.481  5594  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
11-03 12:11:42.481  5594  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
11-03 12:11:42.481  5594  5641 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
11-03 12:11:42.481  5594  5641 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
,11-03 12:11:42.481  5594  5641 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
11-03 12:11:42.481  5594  5641 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-03 12:11:42.481  5594  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
11-03 12:11:42.481  5594  5641 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-03 12:11:42.482  5594  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-57,5,main], id: 57
11-03 12:11:42.482  5594  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-57,5,main], id: 57
,11-03 12:11:42.482  5594  5655 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
11-03 12:11:42.483  5594  5655 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
11-03 12:11:42.484  5594  5641 D BluetoothAdapter: STATE_ON
11-03 12:11:42.484  5594  5641 D BluetoothLeScanner: could not find callback wrapper
,11-03 12:11:42.484  5594  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-03 12:11:42.484  5594  5655 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
11-03 12:11:42.484  5594  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-57,5,main], id: 57
11-03 12:11:42.484  5594  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-57,5,main], id: 57
11-03 12:11:42.484  5594  5641 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
11-03 12:11:42.485  5594  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-57,5,main], id: 57
11-03 12:11:42.486  4671  4737 D BtGatt.AdvertiseManager: message : 1
,11-03 12:11:42.487  4671  4737 D BtGatt.AdvertiseManager: stop advertise for client 5
,11-03 12:11:42.501  4671  4735 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
,11-03 12:11:42.501  4671  4735 D BtGatt.GattService: Client app is not null!
,11-03 12:11:42.503  4671  4684 D BtGatt.GattService: unregisterClient() - clientIf=5
,11-03 12:11:42.504  5594  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-03 12:11:42.504  5594  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTEDCurrent thread: Thread[Thread-57,5,main], id: 57
,11-03 12:11:42.504  5594  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
,11-03 12:11:42.505  5594  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged false. Current thread: Thread[Thread-57,5,main], id: 57
11-03 12:11:42.505  5594  5641 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: falseCurrent thread: Thread[Thread-57,5,main], id: 57
11-03 12:11:42.505  5594  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[Thread-57,5,main], id: 57
11-03 12:11:42.505  5594  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
,11-03 12:11:42.505  5594  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [ADVERTISING]
11-03 12:11:42.505  5594  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[Thread-57,5,main], id: 57
11-03 12:11:42.505  5594  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]Current thread: Thread[Thread-57,5,main], id: 57
11-03 12:11:42.505  5594  5641 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
11-03 12:11:42.506  5594  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
11-03 12:11:42.507  5594  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
11-03 12:11:42.508  5594  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-03 12:11:42.508  5594  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
11-03 12:11:42.508  5594  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
11-03 12:11:42.508  5594  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[Thread-57,5,main], id: 57
11-03 12:11:42.508  5594  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finishedCurrent thread: Thread[Thread-57,5,main], id: 57
11-03 12:11:42.508  5594  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-57,5,main], id: 57
11-03 12:11:42.508  5594  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-03 12:11:42.509  5594  5641 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-03 12:11:42.510  5594  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
11-03 12:11:42.510  5594  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
11-03 12:11:42.512  5594  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
11-03 12:11:42.512  5594  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
11-03 12:11:42.512  5594  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
11-03 12:11:42.513  5594  5594 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-03 12:11:42.513  5594  5594 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,11-03 12:11:42.515  5594  5641 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
11-03 12:11:42.515  5594  5641 V io.jxcore.node.ConnectivityMonitor: start: Already started
11-03 12:11:42.515  5594  5641 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 2
11-03 12:11:42.514  5594  5594 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
11-03 12:11:42.515  5594  5641 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 1 -> 2
11-03 12:11:42.516  5594  5641 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
11-03 12:11:42.516  5594  5641 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
11-03 12:11:42.516  5594  5641 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
11-03 12:11:42.517  5594  5641 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-03 12:11:42.518  5594  5641 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
11-03 12:11:42.518  5594  5641 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
11-03 12:11:42.518  5594  5641 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
11-03 12:11:42.518  5594  5641 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
11-03 12:11:42.518  5594  5641 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
11-03 12:11:42.518  5594  5641 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
11-03 12:11:42.518  5594  5641 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-03 12:11:42.519  5594  5641 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
11-03 12:11:42.519  5594  5658 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
11-03 12:11:42.519  5594  5658 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-03 12:11:42.524  5594  5658 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
11-03 12:11:42.519  4686  4686 W Binder_2: type=1400 audit(0.0:115): avc: denied { ioctl } for path="socket:[31833]" dev="sockfs" ino=31833 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-03 12:11:42.519  4686  4686 W Binder_2: type=1400 audit(0.0:116): avc: denied { ioctl } for path="socket:[31833]" dev="sockfs" ino=31833 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-03 12:11:42.524  5594  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-03 12:11:42.525  5594  5641 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-03 12:11:42.525  5594  5641 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
11-03 12:11:42.529  5594  5641 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-03 12:11:42.530  5594  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-03 12:11:42.530  5594  5641 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-03 12:11:42.533  5594  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Current thread: Thread[Thread-57,5,main], id: 57
11-03 12:11:42.533  5594  5641 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
11-03 12:11:42.533  5594  5641 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-03 12:11:42.533  5594  5641 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 02 60 83 34 25 D7 D4
11-03 12:11:42.533  5594  5641 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[2, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-03 12:11:42.533  5594  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: Current thread: Thread[Thread-57,5,main], id: 57
11-03 12:11:42.533  5594  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData finished: Current thread: Thread[Thread-57,5,main], id: 57
11-03 12:11:42.533  5594  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = NOT_STARTEDCurrent thread: Thread[Thread-57,5,main], id: 57
11-03 12:11:42.534  5594  5641 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... adv data = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[2, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]Current thread: Thread[Thread-57,5,main], id: 57
11-03 12:11:42.535  5594  5641 D BluetoothAdapter: STATE_ON
11-03 12:11:42.537  4671  4684 D BtGatt.GattService: registerClient() - UUID=299558f0-95ff-44ec-a9c5-85a799f047ef
11-03 12:11:42.538  4671  4735 D BtGatt.GattService: onClientRegistered() - UUID=299558f0-95ff-44ec-a9c5-85a799f047ef, clientIf=5
11-03 12:11:42.538  5594  5604 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
11-03 12:11:42.539  4671  4737 D BtGatt.AdvertiseManager: message : 0
11-03 12:11:42.541  4671  4737 D BtGatt.AdvertiseManager: starting multi advertising
11-03 12:11:42.552  4671  4735 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,11-03 12:11:42.558  4671  4735 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
11-03 12:11:42.559  5594  5641 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment Current thread: Thread[Thread-57,5,main], id: 57
11-03 12:11:42.559  5594  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTINGCurrent thread: Thread[Thread-57,5,main], id: 57
11-03 12:11:42.559  5594  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
11-03 12:11:42.559  5594  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged default (no call to listener). Current thread: Thread[Thread-57,5,main], id: 57
11-03 12:11:42.559  5594  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finishedCurrent thread: Thread[Thread-57,5,main], id: 57
11-03 12:11:42.559  5594  5641 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[Thread-57,5,main], id: 57
11-03 12:11:42.559  5594  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[Thread-57,5,main], id: 57
11-03 12:11:42.559  5594  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser started = trueCurrent thread: Thread[Thread-57,5,main], id: 57
11-03 12:11:42.559  5594  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-03 12:11:42.561  5594  5641 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-03 12:11:42.561  5594  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
11-03 12:11:42.562  5594  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
11-03 12:11:42.562  5594  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
11-03 12:11:42.562  5594  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
11-03 12:11:42.562  5594  5641 I io.jxcore.node.ConnectionHelper: start: OK
11-03 12:11:42.562  5594  5594 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
11-03 12:11:42.563  5594  5594 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[main,5,main], id: 1
11-03 12:11:42.563  5594  5594 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[main,5,main], id: 1
11-03 12:11:42.564  5594  5594 D BluetoothAdapter: STATE_ON
11-03 12:11:42.564  5594  5594 D BluetoothLeScanner: could not find callback wrapper
11-03 12:11:42.564  5594  5594 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-03 12:11:42.564  5594  5594 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[main,5,main], id: 1
11-03 12:11:42.564  5594  5594 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[main,5,main], id: 1
11-03 12:11:42.564  5594  5594 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
11-03 12:11:42.564  5594  5594 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[main,5,main], id: 1
11-03 12:11:42.565  4671  4737 D BtGatt.AdvertiseManager: message : 1
11-03 12:11:42.565  4671  4737 D BtGatt.AdvertiseManager: stop advertise for client 5
11-03 12:11:42.571  4671  4735 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
11-03 12:11:42.571  4671  4735 D BtGatt.GattService: Client app is not null!
11-03 12:11:42.571  4671  4686 D BtGatt.GattService: unregisterClient() - clientIf=5
11-03 12:11:42.572  5594  5594 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-03 12:11:42.572  5594  5594 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = NOT_STARTEDCurrent thread: Thread[main,5,main], id: 1
11-03 12:11:42.572  5594  5594 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to NOT_STARTED
11-03 12:11:42.572  5594  5594 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged false. Current thread: Thread[main,5,main], id: 1
11-03 12:11:42.572  5594  5594 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-03 12:11:42.572  5594  5594 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-03 12:11:42.572  5594  5594 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-03 12:11:42.572  5594  5594 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-03 12:11:42.572  5594  5594 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-03 12:11:42.572  5594  5594 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-03 12:11:42.572  5594  5594 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finishedCurrent thread: Thread[main,5,main], id: 1
11-03 12:11:42.572  5594  5594 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[main,5,main], id: 1
11-03 12:11:42.573  5594  5594 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-03 12:11:42.573  5594  5594 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
11-03 12:11:42.574  5594  5594 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-03 12:11:42.575  5594  5594 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-03 12:11:42.575  5594  5594 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
11-03 12:11:42.578  5594  5594 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-03 12:11:42.578  5594  5594 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-03 12:11:42.579  5594  5594 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-03 12:11:42.580  5594  5594 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Current thread: Thread[main,5,main], id: 1
11-03 12:11:42.580  5594  5594 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
11-03 12:11:42.581  5594  5594 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-03 12:11:42.581  5594  5594 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 02 60 83 34 25 D7 D4
11-03 12:11:42.581  5594  5594 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[2, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-03 12:11:42.581  5594  5594 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: Current thread: Thread[main,5,main], id: 1
11-03 12:11:42.581  5594  5594 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData finished: Current thread: Thread[main,5,main], id: 1
11-03 12:11:42.581  5594  5594 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = NOT_STARTEDCurrent thread: Thread[main,5,main], id: 1
11-03 12:11:42.581  5594  5594 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... adv data = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[2, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]Current thread: Thread[main,5,main], id: 1
11-03 12:11:42.582  5594  5594 D BluetoothAdapter: STATE_ON
11-03 12:11:42.585  4671  4686 D BtGatt.GattService: registerClient() - UUID=935d24ee-399e-459a-837e-856281821d99
11-03 12:11:42.585  4671  4735 D BtGatt.GattService: onClientRegistered() - UUID=935d24ee-399e-459a-837e-856281821d99, clientIf=5
11-03 12:11:42.585  5594  5605 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
11-03 12:11:42.586  4671  4737 D BtGatt.AdvertiseManager: message : 0
11-03 12:11:42.588  4671  4737 D BtGatt.AdvertiseManager: starting multi advertising
,11-03 12:11:42.598  4671  4735 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
11-03 12:11:42.604  4671  4735 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
11-03 12:11:42.605  5594  5594 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment Current thread: Thread[main,5,main], id: 1
11-03 12:11:42.605  5594  5594 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTINGCurrent thread: Thread[main,5,main], id: 1
11-03 12:11:42.605  5594  5594 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
11-03 12:11:42.605  5594  5594 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged default (no call to listener). Current thread: Thread[main,5,main], id: 1
11-03 12:11:42.605  5594  5594 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finishedCurrent thread: Thread[main,5,main], id: 1
11-03 12:11:42.605  5594  5594 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[main,5,main], id: 1
11-03 12:11:42.605  5594  5594 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[main,5,main], id: 1
11-03 12:11:42.605  5594  5594 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser started = trueCurrent thread: Thread[main,5,main], id: 1
11-03 12:11:42.605  5594  5594 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-03 12:11:42.606  5594  5594 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-03 12:11:42.606  5594  5594 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-03 12:11:42.607  5594  5594 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-03 12:11:42.608  5594  5594 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-03 12:11:42.608  5594  5594 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-03 12:11:42.608  5594  5594 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
11-03 12:11:42.609  5594  5594 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-03 12:11:42.609  5594  5594 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-03 12:11:42.611  5594  5594 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Current thread: Thread[main,5,main], id: 1
11-03 12:11:42.611  5594  5594 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-03 12:11:42.611  5594  5594 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 02 60 83 34 25 D7 D4
11-03 12:11:42.611  5594  5594 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[2, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-03 12:11:42.611  5594  5594 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: Current thread: Thread[main,5,main], id: 1
11-03 12:11:42.611  5594  5594 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[main,5,main], id: 1
11-03 12:11:42.612  4671  4737 D BtGatt.AdvertiseManager: message : 1
11-03 12:11:42.613  4671  4737 D BtGatt.AdvertiseManager: stop advertise for client 5
11-03 12:11:42.618  4671  4735 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
11-03 12:11:42.619  4671  4735 D BtGatt.GattService: Client app is not null!
11-03 12:11:42.619  4671  4686 D BtGatt.GattService: unregisterClient() - clientIf=5
11-03 12:11:42.620  5594  5594 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-03 12:11:42.620  5594  5594 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = NOT_STARTEDCurrent thread: Thread[main,5,main], id: 1
11-03 12:11:42.620  5594  5594 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to NOT_STARTED
11-03 12:11:42.620  5594  5594 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finishedCurrent thread: Thread[main,5,main], id: 1
11-03 12:11:42.620  5594  5594 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[main,5,main], id: 1
11-03 12:11:42.620  5594  5594 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = NOT_STARTEDCurrent thread: Thread[main,5,main], id: 1
11-03 12:11:42.620  5594  5594 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... adv data = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[2, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]Current thread: Thread[main,5,main], id: 1
11-03 12:11:42.621  5594  5594 D BluetoothAdapter: STATE_ON
11-03 12:11:42.623  4671  4905 D BtGatt.GattService: registerClient() - UUID=7948bd43-8f62-426f-9b5c-c67043379051
11-03 12:11:42.624  4671  4735 D BtGatt.GattService: onClientRegistered() - UUID=7948bd43-8f62-426f-9b5c-c67043379051, clientIf=5
11-03 12:11:42.624  5594  5605 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
11-03 12:11:42.625  4671  4737 D BtGatt.AdvertiseManager: message : 0
11-03 12:11:42.628  4671  4737 D BtGatt.AdvertiseManager: starting multi advertising
,11-03 12:11:42.639  4671  4735 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,11-03 12:11:42.644  4671  4735 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,11-03 12:11:42.645  5594  5594 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment Current thread: Thread[main,5,main], id: 1
,11-03 12:11:42.645  5594  5594 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTINGCurrent thread: Thread[main,5,main], id: 1
11-03 12:11:42.645  5594  5594 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
11-03 12:11:42.645  5594  5594 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged default (no call to listener). Current thread: Thread[main,5,main], id: 1
11-03 12:11:42.646  5594  5594 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finishedCurrent thread: Thread[main,5,main], id: 1
11-03 12:11:42.646  5594  5594 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[main,5,main], id: 1
11-03 12:11:42.646  5594  5594 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[main,5,main], id: 1
11-03 12:11:42.646  5594  5594 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData finished: Current thread: Thread[main,5,main], id: 1
,11-03 12:11:42.646  5594  5594 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = STARTINGCurrent thread: Thread[main,5,main], id: 1
11-03 12:11:42.646  5594  5594 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Already running
11-03 12:11:42.646  5594  5594 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[main,5,main], id: 1
11-03 12:11:42.646  5594  5594 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[main,5,main], id: 1
11-03 12:11:42.646  5594  5594 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser started = trueCurrent thread: Thread[main,5,main], id: 1
11-03 12:11:42.646  5594  5594 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-03 12:11:42.647  5594  5594 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-03 12:11:42.647  5594  5594 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
,11-03 12:11:42.649  5594  5594 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
,11-03 12:11:42.649  5594  5594 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-03 12:11:42.649  5594  5594 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-03 12:11:42.649  5594  5594 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
11-03 12:11:42.649  5594  5594 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  false
11-03 12:11:42.650  5594  5594 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
11-03 12:11:42.650  5594  5594 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-03 12:11:42.650  5594  5594 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
11-03 12:11:42.650  5594  5594 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
11-03 12:11:42.650  5594  5594 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess : Current thread: Thread[main,5,main], id: 1
11-03 12:11:42.650  5594  5594 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = RUNNINGCurrent thread: Thread[main,5,main], id: 1
11-03 12:11:42.650  5594  5594 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to RUNNING
,11-03 12:11:42.650  5594  5594 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged true. Current thread: Thread[main,5,main], id: 1
11-03 12:11:42.650  5594  5594 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-03 12:11:42.650  5594  5594 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-03 12:11:42.650  5594  5594 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [ADVERTISING]
11-03 12:11:42.650  5594  5594 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-03 12:11:42.650  5594  5594 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-03 12:11:42.651  5594  5594 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]Current thread: Thread[main,5,main], id: 1
11-03 12:11:42.651  5594  5594 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
11-03 12:11:42.651  5594  5594 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
,11-03 12:11:42.652  5594  5594 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-03 12:11:42.652  5594  5594 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-03 12:11:42.652  5594  5594 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-03 12:11:42.652  5594  5594 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-03 12:11:42.652  5594  5594 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finishedCurrent thread: Thread[main,5,main], id: 1
11-03 12:11:42.652  5594  5594 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess : Current thread: Thread[main,5,main], id: 1
11-03 12:11:42.652  5594  5594 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNINGCurrent thread: Thread[main,5,main], id: 1
11-03 12:11:42.652  5594  5594 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
11-03 12:11:42.652  5594  5594 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged true. Current thread: Thread[main,5,main], id: 1
11-03 12:11:42.652  5594  5594 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
,11-03 12:11:42.652  5594  5594 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-03 12:11:42.653  5594  5594 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [ADVERTISING]
11-03 12:11:42.653  5594  5594 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-03 12:11:42.653  5594  5594 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-03 12:11:42.653  5594  5594 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]Current thread: Thread[main,5,main], id: 1
11-03 12:11:42.653  5594  5594 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-03 12:11:42.653  5594  5594 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finishedCurrent thread: Thread[main,5,main], id: 1
11-03 12:11:42.653  5594  5594 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess : Current thread: Thread[main,5,main], id: 1
11-03 12:11:42.653  5594  5594 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = RUNNINGCurrent thread: Thread[main,5,main], id: 1
11-03 12:11:42.653  5594  5594 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finishedCurrent thread: Thread[main,5,main], id: 1
11-03 12:11:42.653  5594  5594 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
,11-03 12:11:42.653  5594  5594 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: true - Start operation: Should start/stop everything
,11-03 12:11:43.151  5594  5594 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
11-03 12:11:43.151  5594  5594 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: true - Start operation: Should start/stop everything
,11-03 12:11:47.566  5594  5659 E io.jxcore.node.ConnectionHelperTest: Discovery manager didn't start after 5s!
,11-03 12:11:47.575  5594  5641 I io.jxcore.node.ConnectionHelperTest: Starting test: testStop
,11-03 12:11:47.576  5594  5641 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
11-03 12:11:47.576  5594  5641 V io.jxcore.node.ConnectivityMonitor: start: Already started
11-03 12:11:47.576  5594  5641 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
11-03 12:11:47.576  5594  5641 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 3
11-03 12:11:47.576  5594  5641 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 2 -> 3
,11-03 12:11:47.577  5594  5641 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
11-03 12:11:47.577  5594  5641 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Manufacturer ID: 7413
11-03 12:11:47.577  5594  5641 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad length and type: 533
11-03 12:11:47.577  5594  5641 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad extra information: 3
11-03 12:11:47.577  5594  5641 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
11-03 12:11:47.577  5594  5641 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 2
11-03 12:11:47.577  5594  5641 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 3
11-03 12:11:47.577  5594  5641 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 2
11-03 12:11:47.577  5594  5641 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
11-03 12:11:47.577  5594  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-57,5,main], id: 57
11-03 12:11:47.579  4671  4737 D BtGatt.AdvertiseManager: message : 1
11-03 12:11:47.581  4671  4737 D BtGatt.AdvertiseManager: stop advertise for client 5
,11-03 12:11:47.593  4671  4735 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
,11-03 12:11:47.593  4671  4735 D BtGatt.GattService: Client app is not null!
11-03 12:11:47.594  4671  4686 D BtGatt.GattService: unregisterClient() - clientIf=5
,11-03 12:11:47.594  5594  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,11-03 12:11:47.595  5594  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTEDCurrent thread: Thread[Thread-57,5,main], id: 57
11-03 12:11:47.595  5594  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
11-03 12:11:47.595  5594  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finishedCurrent thread: Thread[Thread-57,5,main], id: 57
,11-03 12:11:47.595  5594  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-57,5,main], id: 57
11-03 12:11:47.595  5594  5641 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-03 12:11:47.595  5594  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Current thread: Thread[Thread-57,5,main], id: 57
11-03 12:11:47.595  5594  5641 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
,11-03 12:11:47.595  5594  5641 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-03 12:11:47.596  5594  5641 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 03 60 83 34 25 D7 D4
11-03 12:11:47.596  5594  5641 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[3, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-03 12:11:47.596  5594  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: Current thread: Thread[Thread-57,5,main], id: 57
,11-03 12:11:47.596  5594  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData finished: Current thread: Thread[Thread-57,5,main], id: 57
11-03 12:11:47.596  5594  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = NOT_STARTEDCurrent thread: Thread[Thread-57,5,main], id: 57
11-03 12:11:47.596  5594  5641 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... adv data = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[3, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]Current thread: Thread[Thread-57,5,main], id: 57
11-03 12:11:47.598  5594  5641 D BluetoothAdapter: STATE_ON
,11-03 12:11:47.602  4671  4686 D BtGatt.GattService: registerClient() - UUID=b94704be-0046-427e-990d-eadcf627c276
,11-03 12:11:47.603  4671  4735 D BtGatt.GattService: onClientRegistered() - UUID=b94704be-0046-427e-990d-eadcf627c276, clientIf=5
,11-03 12:11:47.603  5594  5605 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
,11-03 12:11:47.605  4671  4737 D BtGatt.AdvertiseManager: message : 0
,11-03 12:11:47.608  4671  4737 D BtGatt.AdvertiseManager: starting multi advertising
,11-03 12:11:47.618  4671  4735 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,11-03 12:11:47.624  4671  4735 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,11-03 12:11:47.624  5594  5594 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess : Current thread: Thread[main,5,main], id: 1
11-03 12:11:47.624  5594  5641 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment Current thread: Thread[Thread-57,5,main], id: 57
11-03 12:11:47.624  5594  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTINGCurrent thread: Thread[Thread-57,5,main], id: 57
11-03 12:11:47.624  5594  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,11-03 12:11:47.624  5594  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged default (no call to listener). Current thread: Thread[Thread-57,5,main], id: 57
,11-03 12:11:47.624  5594  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finishedCurrent thread: Thread[Thread-57,5,main], id: 57
11-03 12:11:47.625  5594  5641 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[Thread-57,5,main], id: 57
11-03 12:11:47.625  5594  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[Thread-57,5,main], id: 57
11-03 12:11:47.625  5594  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser started = trueCurrent thread: Thread[Thread-57,5,main], id: 57
11-03 12:11:47.625  5594  5594 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNINGCurrent thread: Thread[main,5,main], id: 1
11-03 12:11:47.625  5594  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-03 12:11:47.625  5594  5594 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
,11-03 12:11:47.625  5594  5641 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-03 12:11:47.625  5594  5594 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged true. Current thread: Thread[main,5,main], id: 1
11-03 12:11:47.625  5594  5594 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-03 12:11:47.625  5594  5641 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: true - Start operation: Should start/stop everything
11-03 12:11:47.625  5594  5594 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-03 12:11:47.625  5594  5641 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
11-03 12:11:47.625  5594  5641 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
11-03 12:11:47.625  5594  5594 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [ADVERTISING]
,11-03 12:11:47.625  5594  5594 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [ADVERTISING]
11-03 12:11:47.625  5594  5594 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-03 12:11:47.625  5594  5594 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-03 12:11:47.625  5594  5594 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finishedCurrent thread: Thread[main,5,main], id: 1
11-03 12:11:47.626  5594  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Already started
11-03 12:11:47.626  5594  5641 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
11-03 12:11:47.626  5594  5641 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the connection manager (Bluetooth connection listener)
,11-03 12:11:47.626  5594  5641 I io.jxcore.node.ConnectionHelper: start: OK
,11-03 12:11:52.633  5594  5660 E io.jxcore.node.ConnectionHelperTest: Discovery manager didn't start after 5s!
,11-03 12:11:52.638  5594  5641 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnPeerReadyToProvideBluetoothMacAddress
,11-03 12:11:52.639  5594  5641 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
,11-03 12:11:52.644  5594  5641 I io.jxcore.node.ConnectionHelperTest: Starting test: testKillAllConnections
11-03 12:11:52.645  5594  5641 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
11-03 12:11:52.646  5594  5641 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnConnectionManagerStateChanged
11-03 12:11:52.647  5594  5641 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
,11-03 12:11:52.648  5594  5641 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnPermissionCheckRequired
11-03 12:11:52.649  5594  5641 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
11-03 12:11:52.650  5594  5641 I io.jxcore.node.ConnectionHelperTest: Starting test: testToggleBetweenSystemDecidedAndAlternativeInsecureRfcommPortNumber
11-03 12:11:52.650  5594  5641 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
11-03 12:11:52.651  5594  5641 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-03 12:11:52.651  5594  5641 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-03 12:11:52.651  5594  5641 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-03 12:11:52.651  5594  5641 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
11-03 12:11:52.651  5594  5641 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,11-03 12:11:52.651  5594  5641 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-03 12:11:52.652  5594  5641 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-03 12:11:52.652  5594  5641 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
11-03 12:11:52.652  5594  5641 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-03 12:11:52.652  5594  5641 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-03 12:11:52.652  5594  5641 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-03 12:11:52.654  5594  5641 I io.jxcore.node.ConnectionHelperTest: Starting test: testConnect
11-03 12:11:52.655  5594  5641 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,11-03 12:11:52.655  5594  5641 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
11-03 12:11:52.657  5594  5641 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnProvideBluetoothMacAddressRequest
11-03 12:11:52.657  5594  5641 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
11-03 12:11:52.659  5594  5641 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnDiscoveryManagerStateChanged
11-03 12:11:52.659  5594  5641 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
11-03 12:11:52.660  5594  5641 I io.jxcore.node.ConnectionHelperTest: Starting test: testDisconnectOutgoingConnection
,11-03 12:11:52.660  5594  5641 E io.jxcore.node.ConnectionModel: addConnectionThread: A matching thread for outgoing connection already exists
11-03 12:11:52.660  5594  5641 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
,11-03 12:11:52.660  5594  5641 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
11-03 12:11:52.660  5594  5641 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
11-03 12:11:52.660  5594  5641 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
11-03 12:11:52.660  5594  5641 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
11-03 12:11:52.660  5594  5641 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
11-03 12:11:52.661  5594  5641 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
11-03 12:11:52.661  5594  5641 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
11-03 12:11:52.661  5594  5641 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
,11-03 12:11:52.661  5594  5641 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
11-03 12:11:52.661  5594  5641 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
11-03 12:11:52.661  5594  5641 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
11-03 12:11:52.662  5594  5641 I io.jxcore.node.ConnectionHelperTest: Starting test: testDispose
11-03 12:11:52.662  5594  5641 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
11-03 12:11:52.662  5594  5641 V io.jxcore.node.ConnectivityMonitor: start: Already started
,11-03 12:11:52.662  5594  5641 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 4
11-03 12:11:52.662  5594  5641 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 3 -> 4
11-03 12:11:52.662  5594  5641 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
11-03 12:11:52.662  5594  5641 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Manufacturer ID: 7413
11-03 12:11:52.662  5594  5641 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad length and type: 533
11-03 12:11:52.662  5594  5641 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad extra information: 4
11-03 12:11:52.662  5594  5641 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
11-03 12:11:52.662  5594  5641 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 2
11-03 12:11:52.662  5594  5641 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 3
11-03 12:11:52.662  5594  5641 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 2
11-03 12:11:52.662  5594  5641 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
11-03 12:11:52.663  5594  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-57,5,main], id: 57
,11-03 12:11:52.663  4671  4737 D BtGatt.AdvertiseManager: message : 1
11-03 12:11:52.664  4671  4737 D BtGatt.AdvertiseManager: stop advertise for client 5
,11-03 12:11:52.673  4671  4735 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
,11-03 12:11:52.673  4671  4735 D BtGatt.GattService: Client app is not null!
11-03 12:11:52.674  4671  4684 D BtGatt.GattService: unregisterClient() - clientIf=5
,11-03 12:11:52.675  5594  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-03 12:11:52.675  5594  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTEDCurrent thread: Thread[Thread-57,5,main], id: 57
11-03 12:11:52.675  5594  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
11-03 12:11:52.675  5594  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finishedCurrent thread: Thread[Thread-57,5,main], id: 57
,11-03 12:11:52.675  5594  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-57,5,main], id: 57
11-03 12:11:52.676  5594  5641 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-03 12:11:52.676  5594  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Current thread: Thread[Thread-57,5,main], id: 57
11-03 12:11:52.676  5594  5641 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
11-03 12:11:52.676  5594  5641 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-03 12:11:52.676  5594  5641 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 04 60 83 34 25 D7 D4
,11-03 12:11:52.676  5594  5641 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[4, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-03 12:11:52.676  5594  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: Current thread: Thread[Thread-57,5,main], id: 57
11-03 12:11:52.676  5594  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData finished: Current thread: Thread[Thread-57,5,main], id: 57
11-03 12:11:52.676  5594  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = NOT_STARTEDCurrent thread: Thread[Thread-57,5,main], id: 57
11-03 12:11:52.676  5594  5641 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... adv data = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[4, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]Current thread: Thread[Thread-57,5,main], id: 57
11-03 12:11:52.678  5594  5641 D BluetoothAdapter: STATE_ON
,11-03 12:11:52.683  4671  4686 D BtGatt.GattService: registerClient() - UUID=7d88188f-82ef-4ef4-a30e-452e64691a6f
,11-03 12:11:52.684  4671  4735 D BtGatt.GattService: onClientRegistered() - UUID=7d88188f-82ef-4ef4-a30e-452e64691a6f, clientIf=5
,11-03 12:11:52.684  5594  5604 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
,11-03 12:11:52.686  4671  4737 D BtGatt.AdvertiseManager: message : 0
,11-03 12:11:52.688  4671  4737 D BtGatt.AdvertiseManager: starting multi advertising
,11-03 12:11:52.698  4671  4735 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,11-03 12:11:52.705  4671  4735 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,11-03 12:11:52.706  5594  5594 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess : Current thread: Thread[main,5,main], id: 1
11-03 12:11:52.706  5594  5641 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment Current thread: Thread[Thread-57,5,main], id: 57
,11-03 12:11:52.706  5594  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTINGCurrent thread: Thread[Thread-57,5,main], id: 57
11-03 12:11:52.706  5594  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
11-03 12:11:52.706  5594  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged default (no call to listener). Current thread: Thread[Thread-57,5,main], id: 57
11-03 12:11:52.706  5594  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finishedCurrent thread: Thread[Thread-57,5,main], id: 57
11-03 12:11:52.706  5594  5641 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[Thread-57,5,main], id: 57
11-03 12:11:52.706  5594  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[Thread-57,5,main], id: 57
,11-03 12:11:52.706  5594  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser started = trueCurrent thread: Thread[Thread-57,5,main], id: 57
11-03 12:11:52.706  5594  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-03 12:11:52.706  5594  5594 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNINGCurrent thread: Thread[main,5,main], id: 1
11-03 12:11:52.706  5594  5641 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-03 12:11:52.706  5594  5594 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
11-03 12:11:52.706  5594  5641 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: true - Start operation: Should start/stop everything
11-03 12:11:52.706  5594  5594 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged true. Current thread: Thread[main,5,main], id: 1
11-03 12:11:52.706  5594  5641 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
11-03 12:11:52.706  5594  5594 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
,11-03 12:11:52.707  5594  5641 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
11-03 12:11:52.707  5594  5594 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-03 12:11:52.707  5594  5594 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [ADVERTISING]
11-03 12:11:52.707  5594  5594 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [ADVERTISING]
11-03 12:11:52.707  5594  5594 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-03 12:11:52.707  5594  5594 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-03 12:11:52.707  5594  5594 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finishedCurrent thread: Thread[main,5,main], id: 1
,11-03 12:11:52.707  5594  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Already started
11-03 12:11:52.707  5594  5641 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
11-03 12:11:52.707  5594  5641 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the connection manager (Bluetooth connection listener)
11-03 12:11:52.708  5594  5641 I io.jxcore.node.ConnectionHelper: start: OK
,11-03 12:11:54.035   928  2701 I hubconnection: sensorhub said: 'set_bias 3: -3.8400, 0.0000, 0.0000'
,11-03 12:11:57.714  5594  5661 E io.jxcore.node.ConnectionHelperTest: Discovery manager didn't start after 5s!
,11-03 12:11:57.719  5594  5641 I io.jxcore.node.ConnectionHelperTest: Starting test: testIsRunning
,11-03 12:11:57.721  5594  5641 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
,11-03 12:11:57.725  5594  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Already started
,11-03 12:11:57.725  5594  5641 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
,11-03 12:11:57.725  5594  5641 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,11-03 12:11:57.729  5594  5641 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnConnectionFailed
,11-03 12:11:57.731  5594  5641 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
,11-03 12:11:57.731  5594  5641 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
11-03 12:11:57.732  5594  5641 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
,11-03 12:11:57.732  5594  5641 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,11-03 12:11:57.732  5594  5641 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,11-03 12:11:57.732  5594  5641 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-03 12:11:57.734  5594  5641 I io.jxcore.node.ConnectionHelperTest: Starting test: testGetConnectivityMonitorGetDiscoveryManagerGetConnectionModelGetBluetoothName
,11-03 12:11:57.749  5594  5641 I io.jxcore.node.ConnectionHelperTest: Starting test: testConstructor
,11-03 12:11:57.749  5594  5641 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-03 12:11:57.749  5594  5641 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
11-03 12:11:57.749  5594  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
11-03 12:11:57.750  5594  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
,11-03 12:11:57.750  5594  5658 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
11-03 12:11:57.750  5594  5641 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-03 12:11:57.750  5594  5658 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
11-03 12:11:57.750  5594  5658 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
,11-03 12:11:57.750  5594  5641 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-03 12:11:57.750  5594  5641 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c19c2c8 removed from the list
,11-03 12:11:57.751  5594  5594 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
11-03 12:11:57.751  5594  5641 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-03 12:11:57.751  5594  5594 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-03 12:11:57.751  5594  5641 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f010f61 removed from the list
11-03 12:11:57.751  5594  5641 D io.jxcore.node.ConnectivityMonitor: stop
,11-03 12:11:57.751  5594  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,11-03 12:11:57.757  5594  5641 I io.jxcore.node.ConnectionModelTest: Starting test: testGetNumberOfCurrentOutgoingConnections
,11-03 12:11:57.757  5594  5641 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
,11-03 12:11:57.758  5594  5641 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
11-03 12:11:57.758  5594  5641 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
11-03 12:11:57.758  5594  5641 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
11-03 12:11:57.758  5594  5641 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
,11-03 12:11:57.758  5594  5641 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
11-03 12:11:57.760  5594  5641 I io.jxcore.node.ConnectionModelTest: Starting test: constructorTest
11-03 12:11:57.761  5594  5641 I io.jxcore.node.ConnectionModelTest: Starting test: testHasIncomingConnection
,11-03 12:11:57.763  5594  5641 I io.jxcore.node.ConnectionModelTest: Starting test: testGetNumberOfCurrentConnections
,11-03 12:11:57.765  5594  5641 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
11-03 12:11:57.765  5594  5641 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
,11-03 12:11:57.766  5594  5641 I io.jxcore.node.ConnectionModelTest: Starting test: testGetNumberOfCurrentIncomingConnections
,11-03 12:11:57.766  5594  5641 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
11-03 12:11:57.767  5594  5641 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
11-03 12:11:57.767  5594  5641 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
,11-03 12:11:57.767  5594  5641 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
11-03 12:11:57.767  5594  5641 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
,11-03 12:11:57.767  5594  5641 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
11-03 12:11:57.768  5594  5641 I io.jxcore.node.ConnectionModelTest: Starting test: testGetOutgoingConnectionCallbackByBluetoothMacAddress
11-03 12:11:57.768  5594  5641 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
,11-03 12:11:57.768  5594  5641 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
,11-03 12:11:57.769  5594  5641 I io.jxcore.node.ConnectionModelTest: Starting test: testHasConnection
,11-03 12:11:57.769  5594  5641 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
11-03 12:11:57.769  5594  5641 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
11-03 12:11:57.770  5594  5641 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
11-03 12:11:57.770  5594  5641 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
,11-03 12:11:57.770  5594  5641 I io.jxcore.node.ConnectionModelTest: Starting test: testHasOutgoingConnection
,11-03 12:11:57.771  5594  5641 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,11-03 12:11:57.771  5594  5641 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@930b15b added. We now have 3 listener(s)
11-03 12:11:57.773  5594  5641 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-03 12:11:57.773  5594  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-03 12:11:57.773  5594  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,11-03 12:11:57.773  5594  5641 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-03 12:11:57.773  5594  5641 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7276df8 added. We now have 3 listener(s)
11-03 12:11:57.774  5594  5641 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-03 12:11:57.774  5594  5641 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,11-03 12:11:57.777  5594  5641 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,11-03 12:11:57.782  5594  5641 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-03 12:11:57.782  5594  5641 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-03 12:11:57.782  5594  5641 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-03 12:11:57.782  5594  5641 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-03 12:11:57.782  5594  5641 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-03 12:11:57.782  5594  5641 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-03 12:11:57.782  5594  5641 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-03 12:11:57.782  5594  5641 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,11-03 12:11:57.784  5594  5641 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,11-03 12:11:57.785  5594  5641 D io.jxcore.node.ConnectivityMonitor: start: OK
,11-03 12:11:57.787  5594  5641 D BluetoothAdapter: enable(): BT is already enabled..!
,11-03 12:11:57.788   928   938 D WifiService: setWifiEnabled: true pid=5594, uid=10077
11-03 12:11:57.788   928   938 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
11-03 12:11:57.789  5594  5594 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-03 12:11:57.789  5594  5641 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testIsBleMultipleAdvertisementSupported
11-03 12:11:57.791  5594  5594 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-03 12:11:57.795  5594  5641 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testIsBluetoothSupported
,11-03 12:11:57.796  5594  5641 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testStartStop
,11-03 12:11:57.799   928  3622 D WifiService: setWifiEnabled: false pid=5594, uid=10077
11-03 12:11:57.799   928  3622 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-03 12:11:57.803   928  2977 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,11-03 12:11:57.803   928  2977 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
11-03 12:11:57.803   928  2977 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
11-03 12:11:57.804   928  2977 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-03 12:11:57.812   928  5357 D DhcpClient: Clearing IP address
,11-03 12:11:57.812   508   921 D CommandListener: Clearing all IP addresses on wlan0
,11-03 12:11:57.821   508   921 D CommandListener: Setting iface cfg
,11-03 12:11:57.821  3608  5431 V NativeCrypto: Read error: ssl=0x7f5ca02000: I/O error during system call, Connection timed out
11-03 12:11:57.823  3608  5431 V NativeCrypto: SSL shutdown failed: ssl=0x7f5ca02000: I/O error during system call, Broken pipe
,11-03 12:11:57.825   928  3180 D ConnectivityService: reportNetworkConnectivity(100, false) by 10012
,11-03 12:11:57.825   928  5355 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Forcing reevaluation for UID 10012
,11-03 12:11:57.827   928  5355 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.gstatic.com": No address associated with hostname
,11-03 12:11:57.828   928  2985 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] validation failed
11-03 12:11:57.828   928  2985 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
11-03 12:11:57.829   928  2985 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
11-03 12:11:57.830   928  5358 D DhcpClient: Receive thread stopped
,11-03 12:11:57.833   928  3802 I ActivityManager: Killing 5249:com.android.settings/1000 (adj 15): empty #17
,11-03 12:11:57.861   928  2985 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
11-03 12:11:57.861   928  2985 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
,11-03 12:11:57.864   541   541 E Parcel  : Reading a NULL string not supported here.
,11-03 12:11:57.867   928  2985 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
11-03 12:11:57.868   928   928 D RttService: SCAN_AVAILABLE : 1
,11-03 12:11:57.868   928  3098 D RttService: EnabledState got{ when=-1ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
11-03 12:11:57.870  3735  3867 W QCNEJ   : |CORE| network lost: 100
11-03 12:11:57.870  3735  3867 W QCNEJ   : |CORE| onLost: unbind the process to WIFI
,11-03 12:11:57.877   928  2977 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,11-03 12:11:57.892   928  2977 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,11-03 12:11:57.900   508   921 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-03 12:11:57.918   508   921 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-03 12:11:57.919   508   921 D CommandListener: Clearing all IP addresses on wlan0
11-03 12:11:57.919   508   921 D TetherController: Setting IP forward enable = 0
,11-03 12:11:57.920   928  2985 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
,11-03 12:11:57.920   928  2985 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,11-03 12:11:57.923   928   945 D Tethering: MasterInitialState.processMessage what=3
11-03 12:11:57.923   928  2977 D DhcpClient: doQuit
,11-03 12:11:57.924   928  2977 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
11-03 12:11:57.924   928  5357 D DhcpClient: onQuitting
11-03 12:11:57.925  3478  3478 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
,11-03 12:11:57.929  5264  5264 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@c9d6a42 and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
,11-03 12:11:57.932  5594  5594 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-03 12:11:57.932  5594  5594 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-03 12:11:57.932  5594  5594 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-03 12:11:57.932  5594  5594 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-03 12:11:57.932  5594  5594 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-03 12:11:57.932  5594  5594 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-03 12:11:57.932  5594  5594 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-03 12:11:57.932  5594  5594 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-03 12:11:57.934  5594  5594 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
11-03 12:11:57.937  5594  5594 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-03 12:11:57.937  5594  5594 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-03 12:11:57.937  5594  5594 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-03 12:11:57.937  5594  5594 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-03 12:11:57.937  5594  5594 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-03 12:11:57.937  5594  5594 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-03 12:11:57.937  5594  5594 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-03 12:11:57.937  5594  5594 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-03 12:11:57.939  5594  5594 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
11-03 12:11:57.939  3979  3979 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
11-03 12:11:57.942  4074  4074 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
11-03 12:11:57.943  5594  5594 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-03 12:11:57.943  5594  5594 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-03 12:11:57.943  5594  5594 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-03 12:11:57.943  5594  5594 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-03 12:11:57.943  5594  5594 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-03 12:11:57.943  5594  5594 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-03 12:11:57.943  5594  5594 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-03 12:11:57.943  5594  5594 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-03 12:11:57.944  5038  5051 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
11-03 12:11:57.944  5038  5051 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
11-03 12:11:57.944  5038  5051 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,0,0,0
,11-03 12:11:57.944  5038  5051 E SarControlService: no key has been found,reset the power
11-03 12:11:57.945  5038  5076 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
11-03 12:11:57.945  5038  5076 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
11-03 12:11:57.945  5038  5076 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
11-03 12:11:57.945  5064  5064 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
11-03 12:11:57.945  5064  5064 D QcrilMsgTunnelSocket: [1002] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
11-03 12:11:57.946  5038  5076 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
11-03 12:11:57.946  5038  5076 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
11-03 12:11:57.946  5594  5594 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
11-03 12:11:57.946  5038  5076 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
11-03 12:11:57.948  5064  5064 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
11-03 12:11:57.948  5064  5064 D QcrilMsgTunnelSocket: [1003] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
11-03 12:11:57.948  5594  5594 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-03 12:11:57.949  3478  3478 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
11-03 12:11:57.950  5594  5594 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-03 12:11:57.952  5594  5594 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-03 12:11:57.952  5064  5078 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@726b4b8 HexData = [00000000ea03000000000000ffffffff]
11-03 12:11:57.952  5064  5078 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
,11-03 12:11:57.952  5064  5078 D QcrilMsgTunnelSocket: [1002] < OEM_HOOK_RAW [null]
11-03 12:11:57.953  3478  3478 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
11-03 12:11:57.953  5064  5064 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
11-03 12:11:57.954  5038  5048 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
11-03 12:11:57.955  4074  4074 D SystemUpdateService: onCreate
11-03 12:11:57.955   508   914 W SocketClient: write error (Broken pipe)
11-03 12:11:57.956   508   914 W SocketClient: Unable to send msg '600 Iface linkstate wlan0 up'
11-03 12:11:57.956   508   914 W SocketListener: Error sending broadcast (Broken pipe)
11-03 12:11:57.958  4074  4074 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
11-03 12:11:57.960  5064  5078 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@726b4b8 HexData = [00000000eb03000000000000ffffffff]
11-03 12:11:57.960  5064  5078 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-03 12:11:57.960  5064  5078 D QcrilMsgTunnelSocket: [1003] < OEM_HOOK_RAW [null]
11-03 12:11:57.961  5064  5064 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
,11-03 12:11:57.961  5038  5049 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
,11-03 12:11:57.968  4074  5677 I SystemUpdateService: active receiver: enabled
11-03 12:11:57.970  4074  4074 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,11-03 12:11:57.975  4074  5383 I iu.UploadsManager: num queued entries: 0
,11-03 12:11:57.976  4074  5383 I iu.UploadsManager: num updated entries: 0
11-03 12:11:57.977  4074  5383 I iu.SyncManager: NEXT; no task
,11-03 12:11:57.978  4074  4074 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,11-03 12:11:57.980  4074  4074 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,11-03 12:11:57.982  5386  5386 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,11-03 12:11:57.986  5386  5386 D SprintDMHelper: simOperator: 
11-03 12:11:57.986  5386  5386 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,11-03 12:11:57.992  4074  5677 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,11-03 12:11:57.996  3478  3478 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,11-03 12:11:57.997  4472  5682 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,11-03 12:11:58.001  4074  5677 I SystemUpdateService: network: null; metered: false; mobile allowed: true
11-03 12:11:58.001  4074  5677 I SystemUpdateService: now status is 0 (complete)
11-03 12:11:58.001  4074  5677 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
11-03 12:11:58.001  4074  5677 I SystemUpdateService: file has been verified
11-03 12:11:58.001  4074  5677 I SystemUpdateService: OTA package size = 21989297
,11-03 12:11:58.007  4074  5677 I SystemUpdateService: showing system update notification
,11-03 12:11:58.008  3478  3478 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,11-03 12:11:58.011   508   914 W SocketClient: write error (Broken pipe)
,11-03 12:11:58.011   508   914 W SocketClient: Unable to send msg '600 Iface linkstate wlan0 up'
11-03 12:11:58.011   508   914 W SocketListener: Error sending broadcast (Broken pipe)
11-03 12:11:58.013   928  3807 I ActivityManager: Start proc 5683:com.google.android.apps.gcs/u0a11 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,11-03 12:11:58.024   928   928 V NotificationService: pkg=com.google.android.gms canInterrupt=false intercept=true
,11-03 12:11:58.026  4074  4074 D SystemUpdateService: onDestroy
,11-03 12:11:58.041  5683  5683 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm64
,11-03 12:11:58.048   928  3603 I ActivityManager: Killing 5052:com.google.android.apps.maps/u0a58 (adj 15): empty #17
,11-03 12:11:58.112   928  2977 D wifi    : In wifi stop Hal
,11-03 12:11:58.112   928  2977 D wifi    : halHandle = 0x7f5a788900, mVM = 0x7f76dcd140, mCls = 0x100a02
11-03 12:11:58.112   928  3476 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
11-03 12:11:58.112   928  3476 D WifiHAL : Got a signal to exit!!!
,11-03 12:11:58.112   928  3476 I WifiHAL : Exit wifi_event_loop
11-03 12:11:58.113   928  2977 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 0
,11-03 12:11:58.113   928  2977 E WifiHAL : Event processing terminated
11-03 12:11:58.113   928  2977 D wifi    : In wifi cleaned up handler
11-03 12:11:58.113  4472  4472 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
11-03 12:11:58.113   928  2977 I WifiHAL : Internal cleanup completed
,11-03 12:11:58.114  5594  5594 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-03 12:11:58.115  3961  4224 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
11-03 12:11:58.116  5594  5594 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-03 12:11:58.117  5594  5594 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-03 12:11:58.133   508   914 W SocketClient: write error (Broken pipe)
11-03 12:11:58.133   508   914 W SocketClient: Unable to send msg '600 Iface linkstate wlan0 down'
,11-03 12:11:58.133   508   914 W SocketListener: Error sending broadcast (Broken pipe)
11-03 12:11:58.133   928  3476 D wifi    : set interface wlan0 flags (DOWN)
11-03 12:11:58.134   928  2977 D WifiNative-HAL: HAL event thread stopped successfully
,11-03 12:11:58.310  5594  5662 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-03 12:11:58.314   928  4197 D WifiService: setWifiEnabled: true pid=5594, uid=10077
,11-03 12:11:58.314   928  4197 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-03 12:11:58.339   928   945 D Tethering: InitialState.processMessage what=4
,11-03 12:11:58.348   928   945 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,11-03 12:11:58.819   928  3180 D WifiService: setWifiEnabled: true pid=5594, uid=10077
,11-03 12:11:58.819   928  3180 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-03 12:11:59.023   508   921 E Netd    : netlink response contains error (No such file or directory)
,11-03 12:11:59.025   928  2985 E NetdConnector: NDC Command {109 network destroy 100} took too long (1103ms)
11-03 12:11:59.025   928  2985 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
11-03 12:11:59.026   928  2985 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,11-03 12:11:59.026   928  2975 E NetdConnector: NDC Command {110 bandwidth setglobalalert 2097152} took too long (1098ms)
11-03 12:11:59.026   508   921 D SoftapController: Softap fwReload - Ok
,11-03 12:11:59.027   928  2977 E NetdConnector: NDC Command {111 softap fwreload wlan0 STA} took too long (690ms)
,11-03 12:11:59.028   928  2974 E NetdConnector: NDC Command {112 bandwidth gettetherstats} took too long (677ms)
11-03 12:11:59.028   508   921 D TetherController: Setting IP forward enable = 0
,11-03 12:11:59.033   508   921 D CommandListener: Setting iface cfg
,11-03 12:11:59.033   508   921 D CommandListener: Trying to bring down wlan0
11-03 12:11:59.034   508   921 D CommandListener: Clearing all IP addresses on wlan0
,11-03 12:11:59.038   928  2977 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,11-03 12:11:59.091   545   545 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
11-03 12:11:59.091   545   545 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,11-03 12:11:59.322   928  3186 D WifiService: setWifiEnabled: true pid=5594, uid=10077
,11-03 12:11:59.324   928  3186 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-03 12:11:59.647   928  2977 D wifi    : set interface wlan0 flags (UP)
,11-03 12:11:59.647   928  2977 I WifiHAL : Initializing wifi
,11-03 12:11:59.648   928  2977 I WifiHAL : Creating socket
,11-03 12:11:59.653   928   945 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,11-03 12:11:59.658   928  2977 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
,11-03 12:11:59.658   928  2977 D wifi    : Did set static halHandle = 0x7f5a788900
,11-03 12:11:59.658   928  2977 D wifi    : halHandle = 0x7f5a788900, mVM = 0x7f76dcd140, mCls = 0x2014ae
,11-03 12:11:59.658   928  2977 D wifi    : array field set
,11-03 12:11:59.658   928  2977 I WifiNative-HAL: interface[0] = wlan0
11-03 12:11:59.661   928  5703 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=546978695424
11-03 12:11:59.661   928  5703 D wifi    : waitForHalEvents called, vm = 0x7f76dcd140, obj = 0x2014ae, env = 0x7f5acfd700
,11-03 12:11:59.736  5704  5704 I wpa_supplicant: Successfully initialized wpa_supplicant
,11-03 12:11:59.762   928  2977 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,11-03 12:11:59.767  5594  5594 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-03 12:11:59.769  5594  5594 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-03 12:11:59.771  5594  5594 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-03 12:11:59.807  5704  5704 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,11-03 12:11:59.826   928  3622 D WifiService: setWifiEnabled: true pid=5594, uid=10077
,11-03 12:11:59.826   928  3622 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-03 12:11:59.832  5704  5704 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,11-03 12:11:59.832  5704  5704 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,11-03 12:11:59.845   928  2977 D WifiConfigStore: Loading config and enabling all networks 
,11-03 12:11:59.854  5594  5594 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-03 12:11:59.854  5594  5594 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-03 12:11:59.854  5594  5594 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-03 12:11:59.854  5594  5594 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-03 12:11:59.854  5594  5594 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-03 12:11:59.854  5594  5594 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-03 12:11:59.854  5594  5594 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-03 12:11:59.854  5594  5594 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,11-03 12:11:59.859  5594  5594 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,11-03 12:11:59.863  5594  5594 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-03 12:11:59.863  5594  5594 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-03 12:11:59.863  5594  5594 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-03 12:11:59.863  5594  5594 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-03 12:11:59.863  5594  5594 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-03 12:11:59.863  5594  5594 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-03 12:11:59.863  5594  5594 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-03 12:11:59.863  5594  5594 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,11-03 12:11:59.867   928  2977 D WifiConfigStore: loaded 0 passpoint configs
,11-03 12:11:59.867  5594  5594 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
11-03 12:11:59.868   928  2977 W WifiConfigStore: Upgrading network 4 to android.uid.system:1000
,11-03 12:11:59.868   928  2977 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
11-03 12:11:59.869   928  2977 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,11-03 12:11:59.869   928  2977 W WifiConfigStore: Upgrading network 3 to android.uid.system:1000
11-03 12:11:59.870   928  2977 W WifiConfigStore: Upgrading network 2 to android.uid.system:1000
11-03 12:11:59.870   928  2977 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,11-03 12:11:59.870   928  2977 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 5
11-03 12:11:59.871   928  2977 E WifiConfigStore: found sortedWifiConfigurations : "AndroidAP"WPA_PSK
11-03 12:11:59.871   928  2977 E WifiConfigStore: found sortedWifiConfigurations : "AndroidHotspot2346"WPA_PSK
11-03 12:11:59.871   928  2977 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
11-03 12:11:59.871   928  2977 E WifiConfigStore: found sortedWifiConfigurations : "Thali_internal"WPA_PSK
11-03 12:11:59.871   928  2977 E WifiConfigStore: found sortedWifiConfigurations : "MC"WPA_PSK
,11-03 12:11:59.874   928  2977 D WifiNative-HAL: Setting external_sim to 1
,11-03 12:11:59.874   928  2977 D wifi    : setting dfs flag to true, 0x7f61829520
11-03 12:11:59.874  4472  4472 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
11-03 12:11:59.874   928  2977 D WifiStateMachine: Setting OUI to DA-A1-19
11-03 12:11:59.874   928  2977 D wifi    : setting scan oui 0x7f61829520
11-03 12:11:59.874   928  2977 D WifiHAL : Sending mac address OUI
11-03 12:11:59.875  5594  5594 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-03 12:11:59.875  5594  5594 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-03 12:11:59.875  5594  5594 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-03 12:11:59.875  5594  5594 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-03 12:11:59.875  5594  5594 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-03 12:11:59.875  5594  5594 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-03 12:11:59.875  5594  5594 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-03 12:11:59.875  5594  5594 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-03 12:11:59.877  5594  5594 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
11-03 12:11:59.877   928  2977 E native  : do suspend false
,11-03 12:11:59.884   928  2977 D wifi    : android_net_wifi_setLinkLayerStats: 1
,11-03 12:11:59.884   928   928 D RttService: SCAN_AVAILABLE : 3
11-03 12:11:59.884   928  3098 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,11-03 12:11:59.888   508   921 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,11-03 12:11:59.890   508   921 D CommandListener: Setting iface cfg
,11-03 12:11:59.893   928  2976 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '120 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 120 Failed to set address (No such device)'
11-03 12:11:59.893   928  2976 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,11-03 12:11:59.899   928  2976 D WifiNative-HAL: p2pGetDeviceAddress
,11-03 12:11:59.899   928  2976 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:70
,11-03 12:11:59.905   928   943 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=114677 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=14 mControllerEnergyUsed=53 }
,11-03 12:12:00.332  5594  5662 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-03 12:12:00.345  4671  4731 D BluetoothAdapterState: Current state: ON, message: 23
,11-03 12:12:00.346  4671  4731 D BluetoothAdapterProperties: Setting state to 13
11-03 12:12:00.346  4671  4731 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,11-03 12:12:00.347  4671  4731 D BluetoothAdapterProperties: onBluetoothDisable()
,11-03 12:12:00.349  4671  4731 I BluetoothAdapterState: Entering PendingCommandState
,11-03 12:12:00.351  4671  4671 D BluetoothMapService: onReceive
11-03 12:12:00.351  4671  4671 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
11-03 12:12:00.351  4671  4671 D BluetoothMapService: STATE_TURNING_OFF
11-03 12:12:00.352  4671  4671 D BluetoothMapService: MAP Service closeService in
11-03 12:12:00.352  4671  4671 D BluetoothMapMasInstance0: MAP Service shutdown
,11-03 12:12:00.352  4671  4671 D ObexServerSockets0: shutdown(block = true)
11-03 12:12:00.355  4671  4907 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 5
11-03 12:12:00.354  4671  4671 D ObexServerSockets0: shutdown called from another thread - interrupt().
11-03 12:12:00.359  4671  4671 D ObexServerSockets0: shutdown called from another thread - interrupt().
,11-03 12:12:00.359  4671  4883 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
11-03 12:12:00.359  4671  4908 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
11-03 12:12:00.363  4671  4671 I BtOppRfcommListener: stopping Accept Thread
,11-03 12:12:00.363  4671  5291 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
11-03 12:12:00.364  4671  5291 I BtOppRfcommListener: BluetoothSocket listen thread finished
11-03 12:12:00.367  5594  5594 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-03 12:12:00.367  5594  5594 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-03 12:12:00.367  5594  5594 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-03 12:12:00.367  5594  5594 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-03 12:12:00.367  5594  5594 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-03 12:12:00.367  5594  5594 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-03 12:12:00.367  5594  5594 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-03 12:12:00.367  5594  5594 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-03 12:12:00.367  5594  5594 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,11-03 12:12:00.368  5594  5594 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-03 12:12:00.369  5594  5594 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,11-03 12:12:00.372  5594  5594 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-03 12:12:00.372  5594  5594 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-03 12:12:00.372  5594  5594 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-03 12:12:00.372  5594  5594 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-03 12:12:00.372  5594  5594 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-03 12:12:00.372  5594  5594 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-03 12:12:00.372  5594  5594 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-03 12:12:00.372  5594  5594 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-03 12:12:00.372  5594  5594 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-03 12:12:00.374  5594  5594 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-03 12:12:00.374  5594  5594 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
11-03 12:12:00.374  5594  5594 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBluetoothAdapterStateChanged: State changed to 13
,11-03 12:12:00.379  5594  5594 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,11-03 12:12:00.379  5594  5594 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-03 12:12:00.379  5594  5594 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-03 12:12:00.379  5594  5594 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-03 12:12:00.379  5594  5594 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-03 12:12:00.379  5594  5594 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-03 12:12:00.379  5594  5594 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-03 12:12:00.379  5594  5594 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-03 12:12:00.379  5594  5594 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-03 12:12:00.381  5594  5594 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-03 12:12:00.381  5594  5594 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
11-03 12:12:00.381   928   941 I ActivityManager: Start proc 5710:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
11-03 12:12:00.382  4671  4735 D BluetoothAdapterProperties: Scan Mode:20
11-03 12:12:00.382  4671  4731 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
,11-03 12:12:00.390  5594  5594 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-03 12:12:00.390  4671  4671 D HeadsetService: Received stop request...Stopping profile...
,11-03 12:12:00.393  4671  4671 D A2dpService: Received stop request...Stopping profile...
,11-03 12:12:00.393  3146  3158 D BluetoothHeadset: Proxy object disconnected
11-03 12:12:00.393   928   928 D BluetoothHeadset: Proxy object disconnected
11-03 12:12:00.394   928   928 D BluetoothHeadset: Proxy object disconnected
11-03 12:12:00.394   928   928 D BluetoothHeadset: Proxy object disconnected
11-03 12:12:00.395  4671  4888 D A2dpStateMachine: Exit Disconnected: -1
11-03 12:12:00.395  5594  5594 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-03 12:12:00.395  3765  3779 D BluetoothHeadset: Proxy object disconnected
,11-03 12:12:00.395  5594  5594 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBluetoothAdapterScanModeChanged: Mode changed to 20
11-03 12:12:00.395  5594  5594 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-03 12:12:00.396   928   928 D BluetoothA2dp: Proxy object disconnected
,11-03 12:12:00.397  3146  3146 D HeadsetProfile: Bluetooth service disconnected
11-03 12:12:00.397  3146  3146 D BluetoothA2dp: Proxy object disconnected
11-03 12:12:00.398  4671  4671 D HidService: Received stop request...Stopping profile...
11-03 12:12:00.398  4671  4671 D HidService: Stopping Bluetooth HidService
11-03 12:12:00.399  3146  3146 D BluetoothInputDevice: Proxy object disconnected
11-03 12:12:00.399  3146  3146 D HidProfile: Bluetooth service disconnected
11-03 12:12:00.399  5594  5594 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-03 12:12:00.399  5594  5594 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
11-03 12:12:00.400  4671  4671 D HealthService: Received stop request...Stopping profile...
11-03 12:12:00.400  5594  5594 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-03 12:12:00.400  5594  5594 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-03 12:12:00.401  4671  4671 D PanService: Received stop request...Stopping profile...
,11-03 12:12:00.402  4671  4671 V BluetoothAdapterState: isTurningOff()=true
11-03 12:12:00.402  4671  4671 V BluetoothAdapterState: isTurningOn()=false
11-03 12:12:00.402  4671  4671 V BluetoothAdapterState: isBleTurningOn()=false
11-03 12:12:00.402  3146  3146 D BluetoothPan: BluetoothPAN Proxy object disconnected
11-03 12:12:00.403  4671  4671 V BluetoothAdapterState: isBleTurningOff()=false
11-03 12:12:00.403  3146  3146 D PanProfile: Bluetooth service disconnected
11-03 12:12:00.403  5594  5594 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-03 12:12:00.403  5594  5594 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
11-03 12:12:00.405  4671  4671 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
11-03 12:12:00.405  4671  4671 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
11-03 12:12:00.405  4671  4878 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-03 12:12:00.405  4671  4878 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-03 12:12:00.405  4671  4878 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-03 12:12:00.406  4671  4671 D BluetoothMapService: Received stop request...Stopping profile...
11-03 12:12:00.406  4671  4671 D BluetoothMapService: stop()
11-03 12:12:00.407  4671  4671 D BluetoothMapAppObserver: deinitObservers()
11-03 12:12:00.407  4671  4671 D BluetoothMapAppObserver: removeReceiver()
11-03 12:12:00.408  4671  4735 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
11-03 12:12:00.409  4671  4735 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
11-03 12:12:00.409  4671  4671 V BluetoothAdapterState: isTurningOff()=true
11-03 12:12:00.409  4671  4671 V BluetoothAdapterState: isTurningOn()=false
11-03 12:12:00.410  4671  4671 V BluetoothAdapterState: isBleTurningOn()=false
11-03 12:12:00.410  4671  4671 V BluetoothAdapterState: isBleTurningOff()=false
11-03 12:12:00.411  3146  3146 D BluetoothMap: Proxy object disconnected
11-03 12:12:00.411  3146  3146 D MapProfile: Bluetooth service disconnected
11-03 12:12:00.412  4671  4878 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-03 12:12:00.412  4671  4878 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-03 12:12:00.412  4671  4735 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
11-03 12:12:00.412  4671  4878 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
11-03 12:12:00.412  4671  4671 D SapService: Received stop request...Stopping profile...
11-03 12:12:00.412  4671  4671 V SapService: stop()
11-03 12:12:00.412  4671  4878 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
11-03 12:12:00.412  4671  4878 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
11-03 12:12:00.412  4671  4878 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
11-03 12:12:00.414  4671  4671 V BluetoothAdapterState: isTurningOff()=true
11-03 12:12:00.414  4671  4671 V BluetoothAdapterState: isTurningOn()=false
11-03 12:12:00.414  4671  4671 V BluetoothAdapterState: isBleTurningOn()=false
11-03 12:12:00.414  4671  4671 V BluetoothAdapterState: isBleTurningOff()=false
11-03 12:12:00.415  4671  4671 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
11-03 12:12:00.415  4671  4671 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
11-03 12:12:00.415  4671  4671 V BluetoothAdapterState: isTurningOff()=true
11-03 12:12:00.415  4671  4671 V BluetoothAdapterState: isTurningOn()=false
11-03 12:12:00.415  4671  4671 V BluetoothAdapterState: isBleTurningOn()=false
11-03 12:12:00.415  4671  4671 V BluetoothAdapterState: isBleTurningOff()=false
11-03 12:12:00.416  4671  4671 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
11-03 12:12:00.416  4671  4735 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
11-03 12:12:00.416  4671  4735 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
11-03 12:12:00.416  4671  4671 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
11-03 12:12:00.417  4671  4671 V BluetoothAdapterState: isTurningOff()=true
11-03 12:12:00.417  4671  4671 V BluetoothAdapterState: isTurningOn()=false
11-03 12:12:00.417  4671  4671 V BluetoothAdapterState: isBleTurningOn()=false
11-03 12:12:00.417  4671  4671 V BluetoothAdapterState: isBleTurningOff()=false
11-03 12:12:00.417  4671  4671 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
11-03 12:12:00.418  4671  4671 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
11-03 12:12:00.419  4671  4671 D BluetoothMapService: MAP Service closeService in
11-03 12:12:00.419  4671  4671 V BluetoothAdapterState: isTurningOff()=true
11-03 12:12:00.419  4671  4671 V BluetoothAdapterState: isTurningOn()=false
11-03 12:12:00.419  4671  4671 V BluetoothAdapterState: isBleTurningOn()=false
11-03 12:12:00.420  4671  4671 V BluetoothAdapterState: isBleTurningOff()=false
11-03 12:12:00.420  4671  4671 D BluetoothMapService: cleanup()
11-03 12:12:00.420  4671  4671 D BluetoothMapService: MAP Service closeService in
11-03 12:12:00.420  4671  4671 V BluetoothAdapterState: isTurningOff()=true
11-03 12:12:00.421  4671  4671 V BluetoothAdapterState: isTurningOn()=false
11-03 12:12:00.421  4671  4671 V BluetoothAdapterState: isBleTurningOn()=false
11-03 12:12:00.421  4671  4671 V BluetoothAdapterState: isBleTurningOff()=false
11-03 12:12:00.421  4671  4731 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
11-03 12:12:00.421  4671  4731 D BluetoothAdapterProperties: Setting state to 15
11-03 12:12:00.421  4671  4731 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
11-03 12:12:00.422  4671  4731 I BluetoothAdapterState: Entering BleOnState
11-03 12:12:00.422   928   945 D BluetoothA2dp: onBluetoothStateChange: up=false
11-03 12:12:00.422  3146  4001 D BluetoothPan: onBluetoothStateChange on: false
11-03 12:12:00.423   928   945 D BluetoothHeadset: onBluetoothStateChange: up=false
11-03 12:12:00.423  3765  4013 D BluetoothHeadset: onBluetoothStateChange: up=false
11-03 12:12:00.423   928   945 D BluetoothHeadset: onBluetoothStateChange: up=false
11-03 12:12:00.423  3146  3158 D BluetoothHeadset: onBluetoothStateChange: up=false
11-03 12:12:00.424  3146  3163 D BluetoothA2dp: onBluetoothStateChange: up=false
11-03 12:12:00.424  3146  4001 D BluetoothPbap: onBluetoothStateChange: up=false
11-03 12:12:00.425  3146  3158 D BluetoothInputDevice: onBluetoothStateChange: up=false
11-03 12:12:00.426  3146  3163 D BluetoothMap: onBluetoothStateChange: up=false
11-03 12:12:00.427   928   945 D BluetoothHeadset: onBluetoothStateChange: up=false
11-03 12:12:00.427  4671  4731 D BluetoothAdapterState: Current state: BLE ON, message: 20
11-03 12:12:00.427  4671  4731 D BluetoothAdapterProperties: Setting state to 16
11-03 12:12:00.427  4671  4731 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
11-03 12:12:00.428  4671  4731 D BluetoothAdapterProperties: onBleDisable
11-03 12:12:00.429  4671  4731 I BluetoothAdapterState: Entering PendingCommandState
11-03 12:12:00.429  4671  4732 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
11-03 12:12:00.430  4671  4735 D BluetoothAdapterProperties: Scan Mode:20
11-03 12:12:00.431  4671  4878 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
11-03 12:12:00.431  4671  4878 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-03 12:12:00.432  5594  5594 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-03 12:12:00.433  5594  5594 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-03 12:12:00.433  5594  5594 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBluetoothAdapterStateChanged: State changed to 10
11-03 12:12:00.433  5594  5594 W org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBluetoothAdapterStateChanged: Bluetooth disabled, pausing BLE based peer discovery...
11-03 12:12:00.433  5594  5594 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[main,5,main], id: 1
11-03 12:12:00.433  5594  5594 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[main,5,main], id: 1
11-03 12:12:00.434  5594  5594 D BluetoothAdapter: STATE_OFF
11-03 12:12:00.445  5594  5594 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: BT Adapter is not turned ON
11-03 12:12:00.445  5594  5594 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: java.lang.IllegalStateException: BT Adapter is not turned ON
11-03 12:12:00.445  5594  5594 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: 	at android.bluetooth.le.BluetoothLeUtils.checkAdapterStateOn(BluetoothLeUtils.java:136)
11-03 12:12:00.445  5594  5594 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: 	at android.bluetooth.le.BluetoothLeScanner.stopScan(BluetoothLeScanner.java:169)
11-03 12:12:00.445  5594  5594 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner.stop(BleScanner.java:150)
11-03 12:12:00.445  5594  5594 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer.stopScanner(BlePeerDiscoverer.java:436)
11-03 12:12:00.445  5594  5594 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer.stopScannerAndAdvertiser(BlePeerDiscoverer.java:503)
11-03 12:12:00.445  5594  5594 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.stopBlePeerDiscoverer(DiscoveryManager.java:1217)
11-03 12:12:00.445  5594  5594 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.onBluetoothAdapterStateChanged(DiscoveryManager.java:773)
11-03 12:12:00.445  5594  5594 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager$BluetoothModeBroadcastReceiver.onReceive(BluetoothManager.java:564)
11-03 12:12:00.445  5594  5594 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:881)
11-03 12:12:00.445  5594  5594 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: 	at android.os.Handler.handleCallback(Handler.java:739)
11-03 12:12:00.445  5594  5594 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: 	at android.os.Handler.dispatchMessage(Handler.java:95)
11-03 12:12:00.445  5594  5594 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: 	at android.os.Looper.loop(Looper.java:148)
11-03 12:12:00.445  5594  5594 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-03 12:12:00.445  5594  5594 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: 	at java.lang.reflect.Method.invoke(Native Method)
11-03 12:12:00.445  5594  5594 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-03 12:12:00.445  5594  5594 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-03 12:12:00.445  5594  5594 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[main,5,main], id: 1
11-03 12:12:00.445  5594  5594 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[main,5,main], id: 1
11-03 12:12:00.445  5594  5594 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
11-03 12:12:00.445  5594  5594 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[main,5,main], id: 1
11-03 12:12:00.446  4671  4737 D BtGatt.AdvertiseManager: message : 1
11-03 12:12:00.447  4671  4737 D BtGatt.AdvertiseManager: stop advertise for client 5
,11-03 12:12:00.454  5710  5710 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm64
11-03 12:12:00.455  4671  4735 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
11-03 12:12:00.455  4671  4735 D BtGatt.GattService: Client app is not null!
11-03 12:12:00.456  4671  4684 D BtGatt.GattService: unregisterClient() - clientIf=5
11-03 12:12:00.456  4671  4878 E bt_btif : bta_gattc_deregister Deregister Failedm unknown client cif
11-03 12:12:00.456  5594  5594 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,11-03 12:12:00.456  5594  5594 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTEDCurrent thread: Thread[main,5,main], id: 1
,11-03 12:12:00.456  5594  5594 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
11-03 12:12:00.456  5594  5594 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged false. Current thread: Thread[main,5,main], id: 1
11-03 12:12:00.457  5594  5594 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-03 12:12:00.457  5594  5594 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-03 12:12:00.457  5594  5594 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-03 12:12:00.457  5594  5594 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [ADVERTISING]
11-03 12:12:00.457  5594  5594 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-03 12:12:00.457  5594  5594 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-03 12:12:00.457  5594  5594 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
11-03 12:12:00.457  5594  5594 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-03 12:12:00.459  5594  5594 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
,11-03 12:12:00.459  5594  5594 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: WAITING_FOR_SERVICES_TO_BE_ENABLED, is discovering: false, is advertising: false
11-03 12:12:00.459  5594  5594 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-03 12:12:00.459  5594  5594 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-03 12:12:00.459  5594  5594 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-03 12:12:00.459  5594  5594 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finishedCurrent thread: Thread[main,5,main], id: 1
11-03 12:12:00.459  5594  5594 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[main,5,main], id: 1
11-03 12:12:00.459  5594  5594 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-03 12:12:00.459  5594  5594 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
,11-03 12:12:00.461  5594  5594 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
,11-03 12:12:00.461  5594  5594 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-03 12:12:00.461  5594  5594 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-03 12:12:00.462  5594  5594 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-03 12:12:00.463  5594  5594 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-03 12:12:00.464  5594  5594 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-03 12:12:00.464  5594  5594 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBluetoothAdapterScanModeChanged: Mode changed to 20
11-03 12:12:00.464  5594  5594 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-03 12:12:00.465  5594  5594 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-03 12:12:00.465  5594  5594 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-03 12:12:00.466  5594  5594 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-03 12:12:00.466  5594  5594 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-03 12:12:00.467  5594  5594 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: WAITING_FOR_SERVICES_TO_BE_ENABLED, is discovering: false, is advertising: false
,11-03 12:12:00.473  5710  5710 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,11-03 12:12:00.478   928   945 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@ea16e1e:true
,11-03 12:12:00.479  3608  3608 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,11-03 12:12:00.492   928  3603 I ActivityManager: Start proc 5722:com.google.android.apps.maps/u0a58 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,11-03 12:12:00.504  5710  5710 D LocalBluetoothProfileManager: Adding local MAP profile
,11-03 12:12:00.507  5710  5710 D BluetoothMap: Create BluetoothMap proxy object
,11-03 12:12:00.518  5710  5710 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,11-03 12:12:00.533  5710  5710 D DockEventReceiver: finishStartingService: stopping service
,11-03 12:12:00.535  5722  5722 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm64
,11-03 12:12:00.544   928   938 I ActivityManager: Killing 5264:com.google.android.music:main/u0a59 (adj 15): empty #17
,11-03 12:12:00.638  4671  4735 I bt_hci  : shut_down
,11-03 12:12:00.640  4671  4739 D bt_hwcfg: hw_epilog_process
11-03 12:12:00.641  4671  4739 I bt_vendor: low_power_mode_cb
,11-03 12:12:00.643  4671  4739 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
11-03 12:12:00.643  4671  4739 I bt_vendor: epilog_cb
11-03 12:12:00.643  4671  4739 I bt_hci  : epilog_finished_callback
,11-03 12:12:00.646  4671  4735 I bt_hci_h4: hal_close
,11-03 12:12:00.646  4671  4735 I bt_userial_vendor: device fd = 54 close
,11-03 12:12:00.742  5722  5722 D StrictMode: StrictMode policy violation; ~duration=103 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-03 12:12:00.742  5722  5722 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-03 12:12:00.742  5722  5722 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
11-03 12:12:00.742  5722  5722 D StrictMode: 	at java.io.File.doAccess(File.java:281)
11-03 12:12:00.742  5722  5722 D StrictMode: 	at java.io.File.exists(File.java:361)
11-03 12:12:00.742  5722  5722 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
11-03 12:12:00.742  5722  5722 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
11-03 12:12:00.742  5722  5722 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
11-03 12:12:00.742  5722  5722 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
11-03 12:12:00.742  5722  5722 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
11-03 12:12:00.742  5722  5722 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
11-03 12:12:00.742  5722  5722 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-03 12:12:00.742  5722  5722 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-03 12:12:00.742  5722  5722 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-03 12:12:00.742  5722  5722 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-03 12:12:00.742  5722  5722 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-03 12:12:00.742  5722  5722 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-03 12:12:00.742  5722  5722 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-03 12:12:00.742  5722  5722 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-03 12:12:00.742  5722  5722 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-03 12:12:00.742  5722  5722 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-03 12:12:00.742  5722  5722 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-03 12:12:00.742  5722  5722 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-03 12:12:00.742  5722  5722 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-03 12:12:00.742  5722  5722 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-03 12:12:00.742  5722  5722 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-03 12:12:00.742  5722  5722 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,11-03 12:12:00.742  5722  5722 D StrictMode: StrictMode policy violation; ~duration=102 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-03 12:12:00.742  5722  5722 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-03 12:12:00.742  5722  5722 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
11-03 12:12:00.742  5722  5722 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
11-03 12:12:00.742  5722  5722 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
11-03 12:12:00.742  5722  5722 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
11-03 12:12:00.742  5722  5722 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
11-03 12:12:00.742  5722  5722 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
11-03 12:12:00.742  5722  5722 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
11-03 12:12:00.742  5722  5722 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-03 12:12:00.742  5722  5722 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-03 12:12:00.742  5722  5722 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-03 12:12:00.742  5722  5722 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-03 12:12:00.742  5722  5722 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-03 12:12:00.742  5722  5722 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-03 12:12:00.742  5722  5722 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-03 12:12:00.742  5722  5722 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-03 12:12:00.742  5722  5722 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-03 12:12:00.742  5722  5722 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-03 12:12:00.742  5722  5722 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-03 12:12:00.742  5722  5722 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-03 12:12:00.742  5722  5722 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-03 12:12:00.742  5722  5722 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-03 12:12:00.742  5722  5722 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-03 12:12:00.742  5722  5722 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-03 12:12:00.742  5722  5722 D StrictMode: StrictMode policy violation; ~duration=101 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-03 12:12:00.742  5722  5722 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-03 12:12:00.742  5722  5722 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
11-03 12:12:00.742  5722  5722 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
11-03 12:12:00.742  5722  5722 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
11-03 12:12:00.742  5722  5722 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
11-03 12:12:00.742  5722  5722 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
11-03 12:12:00.742  5722  5722 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
11-03 12:12:00.742  5722  5722 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
11-03 12:12:00.742  5722  5722 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-03 12:12:00.742  5722  5722 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-03 12:12:00.742  5722  5722 D StrictMode: 	at com.google.android.apps.gmm.base.ap,p.a.a(PG:244)
11-03 12:12:00.742  5722  5722 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-03 12:12:00.742  5722  5722 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-03 12:12:00.742  5722  5722 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-03 12:12:00.742  5722  5722 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-03 12:12:00.742  5722  5722 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-03 12:12:00.742  5722  5722 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-03 12:12:00.742  5722  5722 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-03 12:12:00.742  5722  5722 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-03 12:12:00.742  5722  5722 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-03 12:12:00.742  5722  5722 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-03 12:12:00.742  5722  5722 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-03 12:12:00.742  5722  5722 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-03 12:12:00.742  5722  5722 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-03 12:12:00.742  5722  5722 D StrictMode: StrictMode policy violation; ~duration=100 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-03 12:12:00.742  5722  5722 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-03 12:12:00.742  5722  5722 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
11-03 12:12:00.742  5722  5722 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
11-03 12:12:00.742  5722  5722 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
11-03 12:12:00.742  5722  5722 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
11-03 12:12:00.742  5722  5722 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
11-03 12:12:00.742  5722  5722 D StrictMode: 	at com.google.r.k.d(PG:1187)
11-03 12:12:00.742  5722  5722 D StrictMode: 	at com.google.r.k.a(PG:2107)
11-03 12:12:00.742  5722  5722 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
11-03 12:12:00.742  5722  5722 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
11-03 12:12:00.742  5722  5722 D StrictMode: 	at com.google.r.v.a(PG:1161)
11-03 12:12:00.742  5722  5722 D StrictMode: 	at com.google.r.y.a(PG:2188)
11-03 12:12:00.742  5722  5722 D StrictMode: 	at com.google.r.e.b(PG:170)
11-03 12:12:00.742  5722  5722 D StrictMode: 	at com.google.r.e.b(PG:15188)
11-03 12:12:00.742  5722  5722 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
11-03 12:12:00.742  5722  5722 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
11-03 12:12:00.742  5722  5722 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-03 12:12:00.742  5722  5722 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-03 12:12:00.742  5722  5722 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-03 12:12:00.742  5722  5722 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-03 12:12:00.742  5722  5722 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-03 12:12:00.742  5722  5722 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-03 12:12:00.742  5722  5722 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-03 12:12:00.742  5722  5722 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-03 12:12:00.742  5722  5722 D StrictMode: 	at android.app.ActivityThread.-wrap1(Activit,yThread.java)
11-03 12:12:00.742  5722  5722 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-03 12:12:00.742  5722  5722 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-03 12:12:00.742  5722  5722 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-03 12:12:00.742  5722  5722 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-03 12:12:00.742  5722  5722 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-03 12:12:00.742  5722  5722 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-03 12:12:00.742  5722  5722 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-03 12:12:00.742  5722  5722 D StrictMode: StrictMode policy violation; ~duration=93 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-03 12:12:00.742  5722  5722 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-03 12:12:00.742  5722  5722 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
11-03 12:12:00.742  5722  5722 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
11-03 12:12:00.742  5722  5722 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
11-03 12:12:00.742  5722  5722 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
11-03 12:12:00.742  5722  5722 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
11-03 12:12:00.742  5722  5722 D StrictMode: 	at com.google.r.k.d(PG:1187)
11-03 12:12:00.742  5722  5722 D StrictMode: 	at com.google.r.k.c(PG:18147)
11-03 12:12:00.742  5722  5722 D StrictMode: 	at com.google.r.k.d(PG:583)
11-03 12:12:00.742  5722  5722 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
11-03 12:12:00.742  5722  5722 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
11-03 12:12:00.742  5722  5722 D StrictMode: 	at com.google.r.v.a(PG:1161)
11-03 12:12:00.742  5722  5722 D StrictMode: 	at com.google.r.y.a(PG:2188)
11-03 12:12:00.742  5722  5722 D StrictMode: 	at com.google.r.e.b(PG:170)
11-03 12:12:00.742  5722  5722 D StrictMode: 	at com.google.r.e.b(PG:15188)
11-03 12:12:00.742  5722  5722 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
11-03 12:12:00.742  5722  5722 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
11-03 12:12:00.742  5722  5722 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-03 12:12:00.742  5722  5722 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-03 12:12:00.742  5722  5722 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-03 12:12:00.742  5722  5722 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-03 12:12:00.742  5722  5722 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-03 12:12:00.742  5722  5722 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-03 12:12:00.742  5722  5722 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-03 12:12:00.742  5722  5722 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-03 12:12:00.742  5722  5722 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-03 12:12:00.742  5722  5722 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-03 12:12:00.742  5722  5722 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-03 12:12:00.742  5722  5722 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-03 12:12:00.742  5722  5722 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-03 12:12:00.742  5722  5722 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-03 12:12:00.742  5722  5722 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-03 12:12:00.742  5722  5722 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-03 12:12:00.743  5722  5722 D StrictMode: StrictMode policy violation; ~duration=70 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-03 12:12:00.743  5722  5722 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-03 12:12:00.743  5722  5722 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
11-03 12:12:00.743  5722  5722 D StrictMode: 	at java.io.File.doAccess(File.java:281)
11-03 12:12:00.743  5722  5722 D StrictMode: 	at java.io.File.exists(File.java:361)
11-03 12:12:00.743  5722  5722 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
11-03 12:12:00.743  5722  5722 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
11-03 12:12:00.743  5722  5722 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
11-03 12:12:00.743  5722  5722 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
11-03 12:12:00.743  5722  5722 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
11-03 12:12:00.743  5722  5722 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-03 12:12:00.743  5722  5722 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-03 12:12:00.743  5722  5722 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-03 12:12:00.743  5722  5722 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-03 12:12:00.743  5722  5722 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-03 12:12:00.743  5722  5722 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-03 12:12:00.743  5722  5722 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-03 12:12:00.743  5722  5722 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-03 12:12:00.743  5722  5722 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-03 12:12:00.743  5722  5722 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-03 12:12:00.743  5722  5722 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-03 12:12:00.743  5722  5722 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-03 12:12:00.743  5722  5722 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-03 12:12:00.743  5722  5722 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-03 12:12:00.743  5722  5722 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-03 12:12:00.743  5722  5722 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-03 12:12:00.743  5722  5722 D StrictMode: StrictMode policy violation; ~duration=69 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-03 12:12:00.743  5722  5722 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-03 12:12:00.743  5722  5722 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
11-03 12:12:00.743  5722  5722 D StrictMode: 	at java.io.File.doAccess(File.java:281)
11-03 12:12:00.743  5722  5722 D StrictMode: 	at java.io.File.exists(File.java:361)
11-03 12:12:00.743  5722  5722 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
11-03 12:12:00.743  5722  5722 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-03 12:12:00.743  5722  5722 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-03 12:12:00.743  5722  5722 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-03 12:12:00.743  5722  5722 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-03 12:12:00.743  5722  5722 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-03 12:12:00.743  5722  5722 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-03 12:12:00.743  5722  5722 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-03 12:12:00.743  5722  5722 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-03 12:12:00.743  5722  5722 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-03 12:12:00.743  5722  5722 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-03 12:12:00.743  5722  5722 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-03 12:12:00.743  5722  5722 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-03 12:12:00.743  5722  5722 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-03 12:12:00.743  5722  5722 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-03 12:12:00.743  5722  5722 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-03 12:12:00.743  5722  5722 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-03 12:12:00.743  5722  5722 D StrictMode: StrictMode policy violation; ~duration=69 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-03 12:12:00.743  5722  5722 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-03 12:12:00.743  5722  5722 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
11-03 12:12:00.743  5722  5722 D StrictMode: 	at java.io.File.lastModified(File.java:569)
11-03 12:12:00.743  5722  5722 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
11-03 12:12:00.743  5722  5722 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-03 12:12:00.743  5722  5722 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-03 12:12:00.743  5722  5722 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-03 12:12:00.743  5722  5722 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-03 12:12:00.743  5722  5722 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-03 12:12:00.743  5722  5722 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-03 12:12:00.743  5722  5722 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-03 12:12:00.743  5722  5722 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-03 12:12:00.743  5722  5722 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-03 12:12:00.743  5722  5722 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-03 12:12:00.743  5722  5722 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-03 12:12:00.743  5722  5722 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-03 12:12:00.743  5722  5722 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-03 12:12:00.743  5722  5722 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-03 12:12:00.743  5722  5722 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-03 12:12:00.743  5722  5722 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-03 12:12:00.748  5710  5710 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
11-03 12:12:00.754  3608  3608 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
11-03 12:12:00.760  4671  4732 D bt_stack_manager: event_shut_down_stack finished.
11-03 12:12:00.760  4671  4731 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
11-03 12:12:00.762  4671  4671 D BtGatt.DebugUtils: handleDebugAction() action=null
11-03 12:12:00.762  4671  4731 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
11-03 12:12:00.763  4671  4671 D BtGatt.GattService: Received stop request...Stopping profile...
11-03 12:12:00.763  4671  4671 D BtGatt.GattService: stop()
11-03 12:12:00.763  4671  4671 D BtGatt.AdvertiseManager: advertise clients cleared
11-03 12:12:00.764  5710  5710 D DockEventReceiver: finishStartingService: stopping service
11-03 12:12:00.764  4671  4671 V BluetoothAdapterState: isTurningOff()=false
11-03 12:12:00.764  4671  4671 V BluetoothAdapterState: isTurningOn()=false
11-03 12:12:00.764  4671  4671 V BluetoothAdapterState: isBleTurningOn()=false
11-03 12:12:00.764  4671  4671 V BluetoothAdapterState: isBleTurningOff()=true
11-03 12:12:00.765  4671  4731 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
11-03 12:12:00.765  4671  4731 D BluetoothAdapterProperties: Setting state to 10
11-03 12:12:00.765  4671  4731 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
11-03 12:12:00.766   928   945 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
11-03 12:12:00.768  4671  4731 I BluetoothAdapterState: Entering OffState
11-03 12:12:00.773  4671  4671 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
11-03 12:12:00.773  4671  4671 W BluetoothSdpJni: Cleaning up Bluetooth Health object
11-03 12:12:00.773  4671  4671 I BluetoothServiceJni: cleanupNative: return from cleanup
11-03 12:12:00.774  4671  4732 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
11-03 12:12:00.779   928  3622 I ActivityManager: Killing 3879:com.android.providers.calendar/u0a1 (adj 15): empty #17
,11-03 12:12:00.785  4671  4732 D bt_stack_manager: event_clean_up_stack finished.
11-03 12:12:00.791  4671  4671 I art     : System.exit called, status: 0
11-03 12:12:00.791  4671  4671 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,11-03 12:12:00.844   928   939 I ActivityManager: Process com.android.bluetooth (pid 4671) has died
11-03 12:12:00.844  5594  5662 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-03 12:12:00.859   928   945 I ActivityManager: Start proc 5755:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,11-03 12:12:00.918  5755  5755 D AdapterServiceConfig: Adding HeadsetService
,11-03 12:12:00.919  5755  5755 D AdapterServiceConfig: Adding A2dpService
11-03 12:12:00.919  5755  5755 D AdapterServiceConfig: Adding HidService
11-03 12:12:00.919  5755  5755 D AdapterServiceConfig: Adding HealthService
11-03 12:12:00.919  5755  5755 D AdapterServiceConfig: Adding PanService
11-03 12:12:00.919  5755  5755 D AdapterServiceConfig: Adding GattService
11-03 12:12:00.919  5755  5755 D AdapterServiceConfig: Adding BluetoothMapService
11-03 12:12:00.920  5755  5755 D AdapterServiceConfig: Adding SapService
,11-03 12:12:00.930   928   945 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@837f394:true
,11-03 12:12:00.930  5755  5755 D BluetoothAdapterState: make() - Creating AdapterState
,11-03 12:12:00.933  5755  5755 I bt_bluedroid: init
,11-03 12:12:00.933  5755  5767 I BluetoothAdapterState: Entering OffState
,11-03 12:12:00.935  5755  5768 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,11-03 12:12:00.935  5755  5768 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
11-03 12:12:00.935  5755  5768 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
11-03 12:12:00.935  5755  5768 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
11-03 12:12:00.936  5755  5755 I bt_bluedroid: get_profile_interface socket
,11-03 12:12:00.937  5755  5755 I bt_bluedroid: get_profile_interface sdp
,11-03 12:12:00.937  5755  5771 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:D4
,11-03 12:12:00.939  5755  5771 D BluetoothAdapterProperties: Name is: Nexus 6P
,11-03 12:12:00.941  5755  5766 I bt_bluedroid: config_hci_snoop_log
,11-03 12:12:00.942   928   945 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 9 receivers.
,11-03 12:12:00.945  5755  5767 D BluetoothAdapterState: Current state: OFF, message: 0
,11-03 12:12:00.945  5755  5767 D BluetoothAdapterProperties: Setting state to 14
11-03 12:12:00.946  5755  5767 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
11-03 12:12:00.947  5755  5767 D BluetoothBondStateMachine: make
11-03 12:12:00.948  5755  5772 I BluetoothBondStateMachine: StableState(): Entering Off State
,11-03 12:12:00.951  5755  5767 I BluetoothAdapterState: Entering PendingCommandState
,11-03 12:12:00.952  5755  5755 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,11-03 12:12:00.954  5755  5755 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@498a2c9
,11-03 12:12:00.954  5755  5755 D BtGatt.DebugUtils: handleDebugAction() action=null
,11-03 12:12:00.955  5755  5755 D BtGatt.GattService: Received start request. Starting profile...
11-03 12:12:00.955  5755  5755 D BtGatt.GattService: start()
11-03 12:12:00.955  5755  5755 I bt_bluedroid: get_profile_interface gatt
11-03 12:12:00.955  5755  5755 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@498a2c9
11-03 12:12:00.956  5755  5755 D BtGatt.AdvertiseManager: advertise manager created
,11-03 12:12:00.960  5755  5755 V BluetoothAdapterState: isTurningOff()=false
,11-03 12:12:00.960  5755  5755 V BluetoothAdapterState: isTurningOn()=false
,11-03 12:12:00.960  5755  5755 V BluetoothAdapterState: isBleTurningOn()=true
,11-03 12:12:00.960  5755  5755 V BluetoothAdapterState: isBleTurningOff()=false
11-03 12:12:00.960  5755  5767 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
11-03 12:12:00.961  5755  5767 I bt_bluedroid: bt_bluedroid
11-03 12:12:00.962  5755  5768 D bt_stack_manager: event_start_up_stack is bringing up the stack.
11-03 12:12:00.962  5755  5768 I bt_hci  : start_up
11-03 12:12:00.966  5755  5768 I bt_vendor: alloc value 0xf3b09871
11-03 12:12:00.967  5755  5768 I bt_vendor: init
11-03 12:12:00.967  5755  5768 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
,11-03 12:12:00.967  5755  5768 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
11-03 12:12:00.967  5594  5594 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-03 12:12:00.998  5722  5746 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,11-03 12:12:01.009   928   945 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@bffb7f5:true
,11-03 12:12:01.074  5755  5768 D bt_hci  : start_up starting async portion
,11-03 12:12:01.074  5755  5775 I bt_hci  : event_finish_startup
11-03 12:12:01.074  5755  5775 I bt_hci_h4: hal_open
11-03 12:12:01.074  5755  5775 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
11-03 12:12:01.075  5755  5775 I bt_userial_vendor: device fd = 54 open
,11-03 12:12:01.072  5778  5778 W irq/448-msm_hs_: type=1400 audit(0.0:117): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-03 12:12:01.087  5755  5775 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,11-03 12:12:01.089  5755  5775 D bt_hwcfg: Chipset BCM4358A3
,11-03 12:12:01.089  5755  5775 D bt_hwcfg: Target name = [BCM4358A3]
11-03 12:12:01.089  5755  5775 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,11-03 12:12:01.354  5755  5767 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 0
,11-03 12:12:01.490  5755  5775 I bt_hwcfg: bt vendor lib: set UART baud 115200
,11-03 12:12:01.491  5755  5775 D bt_hwcfg: Settlement delay -- 100 ms
,11-03 12:12:01.491  5755  5775 I bt_hwcfg: Setting fw settlement delay to 100 
,11-03 12:12:01.613  5755  5775 I bt_hwcfg: bt vendor lib: set UART baud 3000000
11-03 12:12:01.614  5755  5775 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:D4
,11-03 12:12:01.616  5755  5775 I bt_hwcfg: vendor lib fwcfg completed
11-03 12:12:01.616  5755  5775 I bt_vendor: firmware callback
11-03 12:12:01.616  5755  5775 I bt_hci  : firmware_config_callback
,11-03 12:12:01.625  5755  5780 I bt_btu  : btu_task pending for preload complete event
,11-03 12:12:01.625  5755  5780 I bt_btu_task: Bluetooth chip preload is complete
11-03 12:12:01.626  5755  5780 I bt_btu  : btu_task received preload complete event
,11-03 12:12:01.631  5755  5780 I         : BTE_InitTraceLevels -- TRC_HCI
,11-03 12:12:01.632  5755  5780 I         : BTE_InitTraceLevels -- TRC_L2CAP
11-03 12:12:01.632  5755  5780 I         : BTE_InitTraceLevels -- TRC_RFCOMM
11-03 12:12:01.632  5755  5780 I         : BTE_InitTraceLevels -- TRC_AVDT
11-03 12:12:01.632  5755  5780 I         : BTE_InitTraceLevels -- TRC_AVRC
11-03 12:12:01.632  5755  5780 I         : BTE_InitTraceLevels -- TRC_A2D
,11-03 12:12:01.632  5755  5780 I         : BTE_InitTraceLevels -- TRC_BNEP
11-03 12:12:01.633  5755  5780 I         : BTE_InitTraceLevels -- TRC_BTM
11-03 12:12:01.633  5755  5780 I         : BTE_InitTraceLevels -- TRC_GAP
11-03 12:12:01.633  5755  5780 I         : BTE_InitTraceLevels -- TRC_PAN
11-03 12:12:01.633  5755  5780 I         : BTE_InitTraceLevels -- TRC_SDP
,11-03 12:12:01.633  5755  5780 I         : BTE_InitTraceLevels -- TRC_GATT
,11-03 12:12:01.633  5755  5780 I         : BTE_InitTraceLevels -- TRC_SMP
11-03 12:12:01.633  5755  5780 I         : BTE_InitTraceLevels -- TRC_BTAPP
,11-03 12:12:01.633  5755  5780 I         : BTE_InitTraceLevels -- TRC_BTIF
,11-03 12:12:01.718  5755  5780 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf3a87549
,11-03 12:12:01.718  5755  5780 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf3a87549 
,11-03 12:12:01.735  5755  5771 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,11-03 12:12:01.737  5755  5771 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,11-03 12:12:01.738  5755  5771 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:D4
,11-03 12:12:01.740  5755  5771 D BluetoothAdapterProperties: Name is: Nexus 6P
,11-03 12:12:01.743  5755  5771 D BluetoothAdapterProperties: Scan Mode:20
,11-03 12:12:01.743  5755  5771 D BluetoothAdapterProperties: Discoverable Timeout:120
11-03 12:12:01.744  5755  5771 D bt_hci  : do_postload posting postload work item
11-03 12:12:01.746  5755  5775 I bt_hci  : event_postload
11-03 12:12:01.746  5755  5775 I bt_vendor: sco_config_cb
11-03 12:12:01.746  5755  5775 I bt_hci  : sco_config_callback postload finished.
11-03 12:12:01.748  5594  5594 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-03 12:12:01.748  5755  5771 D bt_bte_conf: Device ID record 1 : primary
,11-03 12:12:01.748  5755  5771 D bt_bte_conf:   vendorId            = 000f
11-03 12:12:01.748  5755  5771 D bt_bte_conf:   vendorIdSource      = 0001
11-03 12:12:01.748  5755  5771 D bt_bte_conf:   product             = 1200
11-03 12:12:01.748  5755  5771 D bt_bte_conf:   version             = 1436
11-03 12:12:01.748  5755  5771 D bt_bte_conf:   clientExecutableURL = 
11-03 12:12:01.748  5755  5771 D bt_bte_conf:   serviceDescription  = 
,11-03 12:12:01.748  5755  5771 D bt_bte_conf:   documentationURL    = 
11-03 12:12:01.748  5755  5771 D bt_bte_conf: bte_load_did_conf no section named DID2.
11-03 12:12:01.749  5755  5768 D bt_stack_manager: event_start_up_stack finished
,11-03 12:12:01.750  5755  5767 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
11-03 12:12:01.750  5755  5767 D BluetoothAdapterProperties: Setting state to 15
11-03 12:12:01.750  5755  5767 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
11-03 12:12:01.751  5594  5594 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-03 12:12:01.752  5755  5767 I BluetoothAdapterState: Entering BleOnState
,11-03 12:12:01.752  5594  5594 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBluetoothAdapterScanModeChanged: Mode changed to 20
11-03 12:12:01.752  5594  5594 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-03 12:12:01.758  5594  5594 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-03 12:12:01.758  5594  5594 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-03 12:12:01.758  5594  5594 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
,11-03 12:12:01.759  5594  5594 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-03 12:12:01.760  5755  5767 D BluetoothAdapterState: Current state: BLE ON, message: 1
11-03 12:12:01.760  5755  5767 D BluetoothAdapterProperties: Setting state to 11
11-03 12:12:01.760  5755  5767 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,11-03 12:12:01.762  5755  5775 I bt_vendor: low_power_mode_cb
,11-03 12:12:01.764  5755  5755 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@498a2c9
11-03 12:12:01.765  5755  5755 D HeadsetService: Received start request. Starting profile...
11-03 12:12:01.767  5755  5755 I BluetoothHeadsetServiceJni: classInitNative: succeeds
11-03 12:12:01.767  5755  5755 D HeadsetStateMachine: make
,11-03 12:12:01.773  5594  5594 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-03 12:12:01.775  5594  5594 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-03 12:12:01.775  5594  5594 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBluetoothAdapterStateChanged: State changed to 11
11-03 12:12:01.777  5594  5594 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-03 12:12:01.777  5755  5755 D HeadsetStateMachine: max_hf_connections = 1
11-03 12:12:01.778  5755  5755 I bt_bluedroid: get_profile_interface handsfree
11-03 12:12:01.778  5755  5771 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
11-03 12:12:01.778  5755  5771 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
11-03 12:12:01.781  5755  5755 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@498a2c9
11-03 12:12:01.781  5755  5767 I BluetoothAdapterState: Entering PendingCommandState
,11-03 12:12:01.781  5755  5755 D A2dpService: Received start request. Starting profile...
11-03 12:12:01.782  5755  5755 I BluetoothAvrcpServiceJni: classInitNative: succeeds
11-03 12:12:01.782  5755  5755 I bt_bluedroid: get_profile_interface avrcp
,11-03 12:12:01.787  5755  5755 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
11-03 12:12:01.788  5755  5755 I BluetoothA2dpServiceJni: classInitNative: succeeds
11-03 12:12:01.788  5755  5755 D A2dpStateMachine: make
,11-03 12:12:01.789  5755  5755 I bt_bluedroid: get_profile_interface a2dp
11-03 12:12:01.789  5755  5771 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
11-03 12:12:01.790  5755  5788 D A2dpStateMachine: Enter Disconnected: -2
11-03 12:12:01.790  5755  5755 I BluetoothHidServiceJni: classInitNative: succeeds
11-03 12:12:01.791  5755  5755 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@498a2c9
11-03 12:12:01.792  5710  5710 D BluetoothInputDevice: Proxy object connected
11-03 12:12:01.792  5755  5755 D HidService: Received start request. Starting profile...
11-03 12:12:01.792  5755  5755 I bt_bluedroid: get_profile_interface hidhost
11-03 12:12:01.792  5755  5755 D HidService: setHidService(): set to: null
,11-03 12:12:01.792  5755  5771 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf3a6856d
11-03 12:12:01.793  5710  5710 D HidProfile: Bluetooth service connected
11-03 12:12:01.793  5755  5771 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
11-03 12:12:01.793  5755  5755 I BluetoothHealthServiceJni: classInitNative: succeeds
11-03 12:12:01.794  5755  5755 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@498a2c9
11-03 12:12:01.794  5755  5755 D HealthService: Received start request. Starting profile...
11-03 12:12:01.795  5755  5755 I bt_bluedroid: get_profile_interface health
,11-03 12:12:01.798  5755  5755 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,11-03 12:12:01.798  5755  5755 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@498a2c9
,11-03 12:12:01.799  5710  5710 D BluetoothPan: BluetoothPAN Proxy object connected
11-03 12:12:01.800  5755  5755 D PanService: Received start request. Starting profile...
11-03 12:12:01.800  5710  5710 D PanProfile: Bluetooth service connected
,11-03 12:12:01.800  5755  5755 D BluetoothPanServiceJni: initializeNative(L110): pan
11-03 12:12:01.800  5755  5755 I bt_bluedroid: get_profile_interface pan
11-03 12:12:01.800  5755  5771 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
11-03 12:12:01.804  5755  5755 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@498a2c9
11-03 12:12:01.804  3608  3608 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
11-03 12:12:01.805  5755  5755 D BluetoothMapService: Received start request. Starting profile...
11-03 12:12:01.805  5755  5755 D BluetoothMapService: start()
,11-03 12:12:01.806  5710  5710 D BluetoothMap: Proxy object connected
,11-03 12:12:01.806  5710  5710 D MapProfile: Bluetooth service connected
11-03 12:12:01.807  5710  5710 D BluetoothMap: getConnectedDevices()
11-03 12:12:01.807  5710  5710 D BluetoothMap: Bluetooth is Not enabled
11-03 12:12:01.808  5755  5755 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,11-03 12:12:01.809  5755  5755 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
11-03 12:12:01.809  5755  5755 D BluetoothMapAppObserver: createReceiver()
,11-03 12:12:01.810  5755  5755 D BluetoothMapAppObserver: initObservers()
,11-03 12:12:01.810  5755  5755 D BluetoothMapAppObserver: getEnabledAccountItems()
,11-03 12:12:01.816  5755  5755 V BluetoothAdapterState: isTurningOff()=false
11-03 12:12:01.816  5755  5755 V BluetoothAdapterState: isTurningOn()=true
,11-03 12:12:01.816  5755  5755 V BluetoothAdapterState: isBleTurningOn()=false
11-03 12:12:01.816  5755  5755 V BluetoothAdapterState: isBleTurningOff()=false
11-03 12:12:01.817  5755  5785 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
11-03 12:12:01.818  5755  5755 V SapService: SapBinder()
11-03 12:12:01.818  5755  5755 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@498a2c9
,11-03 12:12:01.819  5755  5755 D SapService: Received start request. Starting profile...
11-03 12:12:01.819  5755  5755 V SapService: start()
,11-03 12:12:01.820  5755  5755 V BluetoothAdapterState: isTurningOff()=false
,11-03 12:12:01.820  5755  5755 V BluetoothAdapterState: isTurningOn()=true
11-03 12:12:01.820  5755  5755 V BluetoothAdapterState: isBleTurningOn()=false
11-03 12:12:01.820  5755  5755 V BluetoothAdapterState: isBleTurningOff()=false
11-03 12:12:01.820  5755  5755 V BluetoothAdapterState: isTurningOff()=false
11-03 12:12:01.820  5755  5755 V BluetoothAdapterState: isTurningOn()=true
11-03 12:12:01.820  5755  5755 V BluetoothAdapterState: isBleTurningOn()=false
11-03 12:12:01.820  5755  5755 V BluetoothAdapterState: isBleTurningOff()=false
11-03 12:12:01.821  5755  5755 V BluetoothAdapterState: isTurningOff()=false
11-03 12:12:01.821  5755  5755 V BluetoothAdapterState: isTurningOn()=true
11-03 12:12:01.821  5755  5755 V BluetoothAdapterState: isBleTurningOn()=false
,11-03 12:12:01.821  5755  5755 V BluetoothAdapterState: isBleTurningOff()=false
11-03 12:12:01.821  5755  5755 V BluetoothAdapterState: isTurningOff()=false
11-03 12:12:01.821  5755  5755 V BluetoothAdapterState: isTurningOn()=true
11-03 12:12:01.821  5755  5755 V BluetoothAdapterState: isBleTurningOn()=false
11-03 12:12:01.821  5755  5755 V BluetoothAdapterState: isBleTurningOff()=false
11-03 12:12:01.822  5755  5755 V BluetoothAdapterState: isTurningOff()=false
11-03 12:12:01.822  5755  5755 V BluetoothAdapterState: isTurningOn()=true
11-03 12:12:01.822  5755  5755 V BluetoothAdapterState: isBleTurningOn()=false
11-03 12:12:01.822  5755  5755 V BluetoothAdapterState: isBleTurningOff()=false
,11-03 12:12:01.823  5755  5755 V BluetoothAdapterState: isTurningOff()=false
11-03 12:12:01.823  5755  5755 V BluetoothAdapterState: isTurningOn()=true
11-03 12:12:01.823  5755  5755 V BluetoothAdapterState: isBleTurningOn()=false
11-03 12:12:01.823  5755  5755 V BluetoothAdapterState: isBleTurningOff()=false
,11-03 12:12:01.823  5755  5767 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
11-03 12:12:01.823  5755  5767 D BluetoothAdapterProperties: ScanMode =  20
11-03 12:12:01.823  5755  5767 D BluetoothAdapterProperties: State =  11
11-03 12:12:01.824  5755  5771 D BluetoothAdapterProperties: Scan Mode:21
11-03 12:12:01.825  5755  5767 D BluetoothAdapterProperties: Setting state to 12
11-03 12:12:01.825  5755  5767 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
11-03 12:12:01.825  5755  5771 D BluetoothAdapterProperties: Discoverable Timeout:120
,11-03 12:12:01.825  5594  5594 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
11-03 12:12:01.825  5755  5767 I BluetoothAdapterState: Entering OnState
,11-03 12:12:01.826  5710  5720 D BluetoothPan: onBluetoothStateChange on: true
,11-03 12:12:01.826   928   945 D BluetoothA2dp: onBluetoothStateChange: up=true
,11-03 12:12:01.828  5594  5594 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
11-03 12:12:01.829  3146  3163 D BluetoothPan: onBluetoothStateChange on: true
11-03 12:12:01.830  3146  3146 D BluetoothPan: BluetoothPAN Proxy object connected
11-03 12:12:01.830  3146  3146 D PanProfile: Bluetooth service connected
11-03 12:12:01.830   928   945 D BluetoothHeadset: onBluetoothStateChange: up=true
11-03 12:12:01.831  3765  4013 D BluetoothHeadset: onBluetoothStateChange: up=true
11-03 12:12:01.831  5594  5594 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
11-03 12:12:01.831   928   945 D BluetoothHeadset: onBluetoothStateChange: up=true
11-03 12:12:01.831  3146  4001 D BluetoothHeadset: onBluetoothStateChange: up=true
11-03 12:12:01.832  3146  3163 D BluetoothA2dp: onBluetoothStateChange: up=true
,11-03 12:12:01.834  3146  3158 D BluetoothPbap: onBluetoothStateChange: up=true
,11-03 12:12:01.835  5594  5594 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-03 12:12:01.835  5594  5594 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-03 12:12:01.835  5594  5594 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-03 12:12:01.835  5594  5594 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-03 12:12:01.835  5594  5594 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-03 12:12:01.835  5594  5594 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-03 12:12:01.835  5594  5594 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-03 12:12:01.835  5594  5594 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-03 12:12:01.836   928   928 D BluetoothA2dp: Proxy object connected
,11-03 12:12:01.836  5710  5721 D BluetoothInputDevice: onBluetoothStateChange: up=true
,11-03 12:12:01.837  5755  5755 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
11-03 12:12:01.837  3146  3158 D BluetoothInputDevice: onBluetoothStateChange: up=true
11-03 12:12:01.837  3146  3146 D BluetoothA2dp: Proxy object connected
11-03 12:12:01.839  5594  5594 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,11-03 12:12:01.840  5755  5755 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
11-03 12:12:01.842  3146  3146 D BluetoothInputDevice: Proxy object connected
11-03 12:12:01.842  3146  3146 D HidProfile: Bluetooth service connected
,11-03 12:12:01.842  5710  5720 D BluetoothMap: onBluetoothStateChange: up=true
11-03 12:12:01.842  5755  5755 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-03 12:12:01.843  3146  4001 D BluetoothMap: onBluetoothStateChange: up=true
11-03 12:12:01.844  5594  5594 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-03 12:12:01.844  5594  5594 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-03 12:12:01.844  5594  5594 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-03 12:12:01.844  5594  5594 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-03 12:12:01.844  5594  5594 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-03 12:12:01.844  5594  5594 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-03 12:12:01.844  5594  5594 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-03 12:12:01.844  5594  5594 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-03 12:12:01.844  5755  5755 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-03 12:12:01.845  5710  5721 D BluetoothPbap: onBluetoothStateChange: up=true
,11-03 12:12:01.845  3146  3146 D BluetoothMap: Proxy object connected
11-03 12:12:01.845  3146  3146 D MapProfile: Bluetooth service connected
11-03 12:12:01.846  3146  3146 D BluetoothMap: getConnectedDevices()
11-03 12:12:01.846  5594  5594 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
11-03 12:12:01.846  5594  5594 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBluetoothAdapterScanModeChanged: Mode changed to 21
11-03 12:12:01.846   928   945 D BluetoothHeadset: onBluetoothStateChange: up=true
11-03 12:12:01.847  5594  5594 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBluetoothAdapterScanModeChanged: Bluetooth enabled, restarting BLE based peer discovery...
11-03 12:12:01.847  5755  5755 D ObexServerSockets: Succeed to create listening sockets 
11-03 12:12:01.847  5594  5594 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
11-03 12:12:01.847  5755  5755 D ObexServerSockets0: startAccept()
11-03 12:12:01.847  5755  5755 D ObexServerSockets0: prepareForNewConnect()
11-03 12:12:01.847   928   928 I Telecom : BluetoothPhoneService: queryPhoneState
,11-03 12:12:01.848  5594  5594 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-03 12:12:01.848  5594  5594 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-03 12:12:01.848  5594  5594 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
11-03 12:12:01.851  5755  5755 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
11-03 12:12:01.851  5755  5755 D BluetoothSdpJni: SDP Create record success - handle: 0
,11-03 12:12:01.852  5755  5795 D ObexServerSockets0: Accepting socket connection...
,11-03 12:12:01.852  5755  5755 D BluetoothMapService: onReceive
11-03 12:12:01.852  5755  5755 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
11-03 12:12:01.853  5594  5594 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-03 12:12:01.853  5755  5755 D BluetoothMapService: STATE_ON
11-03 12:12:01.853  5710  5710 D LocalBluetoothProfileManager: Adding local A2DP profile
11-03 12:12:01.853  5594  5594 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-03 12:12:01.853  5594  5594 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,11-03 12:12:01.856  5710  5710 D LocalBluetoothProfileManager: Adding local HEADSET profile
11-03 12:12:01.857  5594  5662 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-03 12:12:01.857  5594  5662 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-03 12:12:01.857  5594  5662 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-03 12:12:01.857  5594  5662 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-03 12:12:01.857  5594  5662 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-03 12:12:01.857  5594  5662 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-03 12:12:01.857  5594  5662 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-03 12:12:01.857  5594  5662 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-03 12:12:01.858  5755  5796 D ObexServerSockets0: Accepting socket connection...
11-03 12:12:01.858  5594  5594 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Current thread: Thread[main,5,main], id: 1
,11-03 12:12:01.858  5594  5594 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
11-03 12:12:01.858  5594  5594 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-03 12:12:01.858  5594  5594 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 04 60 83 34 25 D7 D4
11-03 12:12:01.858  5594  5594 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[4, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-03 12:12:01.859  5594  5594 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: Current thread: Thread[main,5,main], id: 1
11-03 12:12:01.859  5594  5594 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData finished: Current thread: Thread[main,5,main], id: 1
11-03 12:12:01.859  5594  5594 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = NOT_STARTEDCurrent thread: Thread[main,5,main], id: 1
11-03 12:12:01.859  5594  5594 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... adv data = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[4, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]Current thread: Thread[main,5,main], id: 1
,11-03 12:12:01.859  5594  5594 D BluetoothAdapter: STATE_ON
11-03 12:12:01.859  5594  5662 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
11-03 12:12:01.860  5755  5798 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-03 12:12:01.860  5594  5641 D io.jxcore.node.ConnectivityMonitor: stop
11-03 12:12:01.860  5594  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
11-03 12:12:01.862  5755  5797 D BtGatt.GattService: registerClient() - UUID=8ecb25fc-a295-429d-a90f-986d7202a656
11-03 12:12:01.862  5594  5641 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testIsWifiDirectSupported
11-03 12:12:01.863  5594  5641 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testIsBluetoothEnabled
11-03 12:12:01.863  5755  5771 D BtGatt.GattService: onClientRegistered() - UUID=8ecb25fc-a295-429d-a90f-986d7202a656, clientIf=5
11-03 12:12:01.863  5594  5604 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
11-03 12:12:01.863  5755  5798 D BluetoothSdpJni: sdpCreateSapsRecordNative:
11-03 12:12:01.863  5755  5798 D BluetoothSdpJni: SDP Create record success - handle: 1
11-03 12:12:01.864  5594  5641 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-03 12:12:01.865  5755  5773 D BtGatt.AdvertiseManager: message : 0
,11-03 12:12:01.867  5710  5710 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,11-03 12:12:01.868  5755  5773 D BtGatt.AdvertiseManager: starting multi advertising
11-03 12:12:01.869  5710  5710 D BluetoothA2dp: Proxy object connected
11-03 12:12:01.871  5755  5767 D BluetoothAdapterState: Current state: ON, message: 23
11-03 12:12:01.871  5755  5767 D BluetoothAdapterProperties: Setting state to 13
11-03 12:12:01.871  5755  5767 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
11-03 12:12:01.871  5755  5767 D BluetoothAdapterProperties: onBluetoothDisable()
,11-03 12:12:01.872  5755  5767 I BluetoothAdapterState: Entering PendingCommandState
,11-03 12:12:01.877  3608  3608 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,11-03 12:12:01.878  5755  5771 D BluetoothAdapterProperties: Scan Mode:20
,11-03 12:12:01.878  5755  5767 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
11-03 12:12:01.878  5755  5771 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,11-03 12:12:01.879  5710  5710 D DockEventReceiver: finishStartingService: stopping service
11-03 12:12:01.881  5755  5771 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,11-03 12:12:01.883  5594  5594 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment Current thread: Thread[main,5,main], id: 1
,11-03 12:12:01.883  5594  5594 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTINGCurrent thread: Thread[main,5,main], id: 1
11-03 12:12:01.883  5594  5594 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
11-03 12:12:01.883  5755  5755 D BluetoothMapService: onReceive
11-03 12:12:01.883  5594  5594 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged default (no call to listener). Current thread: Thread[main,5,main], id: 1
11-03 12:12:01.883  5755  5755 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
11-03 12:12:01.883  5594  5594 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finishedCurrent thread: Thread[main,5,main], id: 1
11-03 12:12:01.883  5755  5755 D BluetoothMapService: STATE_TURNING_OFF
11-03 12:12:01.883  5594  5594 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[main,5,main], id: 1
11-03 12:12:01.883  5594  5594 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[main,5,main], id: 1
11-03 12:12:01.883  5594  5594 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser started = trueCurrent thread: Thread[main,5,main], id: 1
11-03 12:12:01.883  5594  5594 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,11-03 12:12:01.884  5755  5755 D HeadsetService: Received stop request...Stopping profile...
11-03 12:12:01.885  5594  5594 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-03 12:12:01.885  5594  5594 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-03 12:12:01.885  3146  3146 D BluetoothPbap: Proxy object connected
,11-03 12:12:01.885  3146  3146 D PbapServerProfile: Bluetooth service connected
,11-03 12:12:01.886  5710  5710 D BluetoothPbap: Proxy object connected
11-03 12:12:01.886  5594  5594 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-03 12:12:01.886  5594  5594 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-03 12:12:01.887  5594  5594 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-03 12:12:01.887  5710  5710 D PbapServerProfile: Bluetooth service connected
,11-03 12:12:01.888  5755  5755 D A2dpService: Received stop request...Stopping profile...
11-03 12:12:01.889  5755  5788 D A2dpStateMachine: Exit Disconnected: -1
,11-03 12:12:01.889  5594  5594 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-03 12:12:01.889  5594  5594 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-03 12:12:01.889  5594  5594 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-03 12:12:01.889  5594  5594 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-03 12:12:01.889  5594  5594 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-03 12:12:01.889  5594  5594 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-03 12:12:01.889  5594  5594 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-03 12:12:01.889  5594  5594 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-03 12:12:01.889  5594  5594 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-03 12:12:01.890   928   928 D BluetoothA2dp: Proxy object disconnected
,11-03 12:12:01.890  5594  5594 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-03 12:12:01.890  5594  5594 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
11-03 12:12:01.891  5710  5710 D BluetoothA2dp: Proxy object disconnected
11-03 12:12:01.891  5594  5594 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
,11-03 12:12:01.891  3146  3146 D BluetoothA2dp: Proxy object disconnected
,11-03 12:12:01.893  5594  5594 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,11-03 12:12:01.893  5594  5594 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-03 12:12:01.893  5594  5594 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-03 12:12:01.893  5594  5594 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-03 12:12:01.893  5594  5594 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-03 12:12:01.893  5594  5594 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-03 12:12:01.893  5594  5594 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-03 12:12:01.893  5594  5594 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-03 12:12:01.893  5594  5594 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,11-03 12:12:01.893  5594  5594 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-03 12:12:01.893  5594  5594 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
11-03 12:12:01.895  5594  5594 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-03 12:12:01.895  5594  5594 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-03 12:12:01.895  5594  5594 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-03 12:12:01.895  5594  5594 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-03 12:12:01.895  5594  5594 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-03 12:12:01.895  5594  5594 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-03 12:12:01.895  5594  5594 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-03 12:12:01.895  5594  5594 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-03 12:12:01.895  5594  5594 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-03 12:12:01.896  5755  5755 D HidService: Received stop request...Stopping profile...
11-03 12:12:01.896  5594  5594 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-03 12:12:01.896  5755  5755 D HidService: Stopping Bluetooth HidService
11-03 12:12:01.896  5594  5594 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,11-03 12:12:01.896  5594  5594 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBluetoothAdapterStateChanged: State changed to 12
,11-03 12:12:01.899  5594  5594 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-03 12:12:01.899  3146  3146 D BluetoothInputDevice: Proxy object disconnected
,11-03 12:12:01.899  3146  3146 D HidProfile: Bluetooth service disconnected
11-03 12:12:01.899  5755  5755 D BluetoothMapService: MAP Service closeService in
11-03 12:12:01.899  5755  5755 D BluetoothMapMasInstance0: MAP Service shutdown
11-03 12:12:01.899  5755  5755 D ObexServerSockets0: shutdown(block = true)
11-03 12:12:01.900  5755  5755 D ObexServerSockets0: shutdown called from another thread - interrupt().
11-03 12:12:01.900  5710  5710 D BluetoothInputDevice: Proxy object disconnected
11-03 12:12:01.900  5755  5755 D ObexServerSockets0: shutdown called from another thread - interrupt().
11-03 12:12:01.900  5710  5710 D HidProfile: Bluetooth service disconnected
11-03 12:12:01.900  5594  5594 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-03 12:12:01.900  5755  5796 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
11-03 12:12:01.900  5594  5594 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBluetoothAdapterStateChanged: State changed to 13
11-03 12:12:01.900  5755  5782 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
11-03 12:12:01.901  5755  5795 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
,11-03 12:12:01.901  5710  5710 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,11-03 12:12:01.902  5755  5755 D HealthService: Received stop request...Stopping profile...
11-03 12:12:01.903  5594  5594 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-03 12:12:01.903  5755  5755 V BluetoothAdapterState: isTurningOff()=true
11-03 12:12:01.903  5755  5755 V BluetoothAdapterState: isTurningOn()=false
11-03 12:12:01.903  5755  5755 V BluetoothAdapterState: isBleTurningOn()=false
11-03 12:12:01.903  5755  5755 V BluetoothAdapterState: isBleTurningOff()=false
,11-03 12:12:01.904  5755  5755 D PanService: Received stop request...Stopping profile...
11-03 12:12:01.904  5594  5594 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-03 12:12:01.904  5594  5594 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBluetoothAdapterScanModeChanged: Mode changed to 20
11-03 12:12:01.904  5594  5594 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-03 12:12:01.905  3146  3146 D BluetoothPan: BluetoothPAN Proxy object disconnected
11-03 12:12:01.905  3146  3146 D PanProfile: Bluetooth service disconnected
11-03 12:12:01.906  5594  5594 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-03 12:12:01.906  5594  5594 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-03 12:12:01.906  5594  5594 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-03 12:12:01.906  5594  5594 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess : Current thread: Thread[main,5,main], id: 1
11-03 12:12:01.906  5594  5594 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNINGCurrent thread: Thread[main,5,main], id: 1
11-03 12:12:01.906  5594  5594 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
11-03 12:12:01.906  5594  5594 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged true. Current thread: Thread[main,5,main], id: 1
11-03 12:12:01.906  5594  5594 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-03 12:12:01.906  5594  5594 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-03 12:12:01.906  5594  5594 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [ADVERTISING]
11-03 12:12:01.906  5594  5594 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-03 12:12:01.906  5594  5594 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-03 12:12:01.906  5594  5594 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]Current thread: Thread[main,5,main], id: 1
11-03 12:12:01.906  5594  5594 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
11-03 12:12:01.906  5594  5594 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-03 12:12:01.906  5755  5755 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
11-03 12:12:01.907  5755  5755 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
11-03 12:12:01.907  5755  5780 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-03 12:12:01.907  5755  5780 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,11-03 12:12:01.907  5755  5780 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-03 12:12:01.907  5755  5771 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
11-03 12:12:01.907  5755  5771 E bt_btif : btif_hf_upstreams_evt: Invalid index 32766
11-03 12:12:01.907  5755  5755 D BluetoothMapService: Received stop request...Stopping profile...
11-03 12:12:01.907  5755  5755 D BluetoothMapService: stop()
11-03 12:12:01.908  5755  5755 D BluetoothMapAppObserver: deinitObservers()
11-03 12:12:01.908  5755  5755 D BluetoothMapAppObserver: removeReceiver()
11-03 12:12:01.908  5594  5594 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-03 12:12:01.908  5594  5594 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
11-03 12:12:01.908  5594  5594 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-03 12:12:01.909  5594  5594 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
,11-03 12:12:01.909  5594  5594 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-03 12:12:01.909  5594  5594 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finishedCurrent thread: Thread[main,5,main], id: 1
11-03 12:12:01.909  5594  5594 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
11-03 12:12:01.909  3146  3146 D BluetoothMap: Proxy object disconnected
11-03 12:12:01.909  3146  3146 D MapProfile: Bluetooth service disconnected
11-03 12:12:01.909  5755  5755 D SapService: Received stop request...Stopping profile...
11-03 12:12:01.909  5755  5755 V SapService: stop()
11-03 12:12:01.910  5755  5755 V BluetoothAdapterState: isTurningOff()=true
11-03 12:12:01.910  5755  5755 V BluetoothAdapterState: isTurningOn()=false
11-03 12:12:01.910  5755  5755 V BluetoothAdapterState: isBleTurningOn()=false
,11-03 12:12:01.910  5755  5755 V BluetoothAdapterState: isBleTurningOff()=false
11-03 12:12:01.911  5755  5780 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-03 12:12:01.911  5755  5780 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-03 12:12:01.914  5755  5771 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
11-03 12:12:01.914  5755  5780 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
11-03 12:12:01.914  5755  5780 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
11-03 12:12:01.914  5755  5780 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
11-03 12:12:01.914  5755  5780 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
11-03 12:12:01.915  5710  5710 D DockEventReceiver: finishStartingService: stopping service
11-03 12:12:01.916  5710  5710 D BluetoothPan: BluetoothPAN Proxy object disconnected
11-03 12:12:01.916  5710  5710 D PanProfile: Bluetooth service disconnected
11-03 12:12:01.916  5710  5710 D BluetoothMap: Proxy object disconnected
11-03 12:12:01.916  5710  5710 D MapProfile: Bluetooth service disconnected
,11-03 12:12:01.924  5755  5755 V BluetoothAdapterState: isTurningOff()=true
,11-03 12:12:01.924  5755  5755 V BluetoothAdapterState: isTurningOn()=false
11-03 12:12:01.924  5755  5755 V BluetoothAdapterState: isBleTurningOn()=false
11-03 12:12:01.924  5755  5755 V BluetoothAdapterState: isBleTurningOff()=false
,11-03 12:12:01.924  5755  5755 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
,11-03 12:12:01.924  5755  5755 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
11-03 12:12:01.924  5755  5771 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
11-03 12:12:01.925  5755  5755 V BluetoothAdapterState: isTurningOff()=true
11-03 12:12:01.925  5755  5755 V BluetoothAdapterState: isTurningOn()=false
11-03 12:12:01.925  5755  5755 V BluetoothAdapterState: isBleTurningOn()=false
11-03 12:12:01.925  5755  5755 V BluetoothAdapterState: isBleTurningOff()=false
11-03 12:12:01.925  5755  5755 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
11-03 12:12:01.925  5755  5771 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
,11-03 12:12:01.925  5755  5755 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
11-03 12:12:01.926  5755  5755 V BluetoothAdapterState: isTurningOff()=true
11-03 12:12:01.926  5755  5755 V BluetoothAdapterState: isTurningOn()=false
11-03 12:12:01.926  5755  5755 V BluetoothAdapterState: isBleTurningOn()=false
11-03 12:12:01.926  5755  5755 V BluetoothAdapterState: isBleTurningOff()=false
11-03 12:12:01.927  5755  5755 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
11-03 12:12:01.927  5755  5755 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
11-03 12:12:01.928  5755  5755 D BluetoothMapService: MAP Service closeService in
11-03 12:12:01.928  5755  5755 V BluetoothAdapterState: isTurningOff()=true
11-03 12:12:01.928  5755  5755 V BluetoothAdapterState: isTurningOn()=false
11-03 12:12:01.928  5755  5755 V BluetoothAdapterState: isBleTurningOn()=false
11-03 12:12:01.928  5755  5755 V BluetoothAdapterState: isBleTurningOff()=false
11-03 12:12:01.929  5755  5755 D BluetoothMapService: cleanup()
11-03 12:12:01.929  5755  5755 D BluetoothMapService: MAP Service closeService in
11-03 12:12:01.929  5755  5755 V BluetoothAdapterState: isTurningOff()=true
11-03 12:12:01.929  5755  5755 V BluetoothAdapterState: isTurningOn()=false
11-03 12:12:01.929  5755  5755 V BluetoothAdapterState: isBleTurningOn()=false
11-03 12:12:01.929  5755  5755 V BluetoothAdapterState: isBleTurningOff()=false
11-03 12:12:01.930  5755  5767 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
11-03 12:12:01.930  5755  5767 D BluetoothAdapterProperties: Setting state to 15
11-03 12:12:01.930  5755  5767 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
11-03 12:12:01.930  3146  3146 D BluetoothPbap: Proxy object disconnected
11-03 12:12:01.930  3146  3146 D PbapServerProfile: Bluetooth service disconnected
11-03 12:12:01.931  5710  5721 D BluetoothPan: onBluetoothStateChange on: false
11-03 12:12:01.931  5755  5767 I BluetoothAdapterState: Entering BleOnState
,11-03 12:12:01.931   928   945 D BluetoothA2dp: onBluetoothStateChange: up=false
,11-03 12:12:01.932  3146  3163 D BluetoothPan: onBluetoothStateChange on: false
11-03 12:12:01.932   928   945 D BluetoothHeadset: onBluetoothStateChange: up=false
11-03 12:12:01.932  3765  4010 D BluetoothHeadset: onBluetoothStateChange: up=false
11-03 12:12:01.932  5710  5720 D BluetoothA2dp: onBluetoothStateChange: up=false
11-03 12:12:01.933   928   945 D BluetoothHeadset: onBluetoothStateChange: up=false
11-03 12:12:01.933  3146  4001 D BluetoothHeadset: onBluetoothStateChange: up=false
11-03 12:12:01.933  3146  3158 D BluetoothA2dp: onBluetoothStateChange: up=false
11-03 12:12:01.934  3146  3163 D BluetoothPbap: onBluetoothStateChange: up=false
11-03 12:12:01.934  5710  5721 D BluetoothInputDevice: onBluetoothStateChange: up=false
,11-03 12:12:01.935  3608  3608 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
11-03 12:12:01.936  3146  4001 D BluetoothInputDevice: onBluetoothStateChange: up=false
11-03 12:12:01.936  5710  5710 D BluetoothPbap: Proxy object disconnected
11-03 12:12:01.936  5710  5710 D PbapServerProfile: Bluetooth service disconnected
,11-03 12:12:01.937  5710  5721 D BluetoothMap: onBluetoothStateChange: up=false
11-03 12:12:01.939  5710  5720 D BluetoothHeadset: onBluetoothStateChange: up=false
11-03 12:12:01.940  3146  3158 D BluetoothMap: onBluetoothStateChange: up=false
11-03 12:12:01.940  5710  5721 D BluetoothPbap: onBluetoothStateChange: up=false
,11-03 12:12:01.941   928   945 D BluetoothHeadset: onBluetoothStateChange: up=false
11-03 12:12:01.941  5755  5767 D BluetoothAdapterState: Current state: BLE ON, message: 20
11-03 12:12:01.941  5755  5767 D BluetoothAdapterProperties: Setting state to 16
11-03 12:12:01.941  5755  5767 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
11-03 12:12:01.942  5755  5767 D BluetoothAdapterProperties: onBleDisable
11-03 12:12:01.942  5755  5767 I BluetoothAdapterState: Entering PendingCommandState
11-03 12:12:01.942  5755  5768 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
,11-03 12:12:01.945  5755  5780 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
11-03 12:12:01.945  5755  5780 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-03 12:12:01.945  5594  5594 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-03 12:12:01.947  5755  5771 D BluetoothAdapterProperties: Scan Mode:20
11-03 12:12:01.949  5594  5594 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-03 12:12:01.949  5710  5710 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
11-03 12:12:01.949  5594  5594 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBluetoothAdapterStateChanged: State changed to 10
11-03 12:12:01.949  5594  5594 W org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBluetoothAdapterStateChanged: Bluetooth disabled, pausing BLE based peer discovery...
11-03 12:12:01.949  5594  5594 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[main,5,main], id: 1
11-03 12:12:01.949  5594  5594 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[main,5,main], id: 1
11-03 12:12:01.950  5594  5594 D BluetoothAdapter: STATE_OFF
11-03 12:12:01.950  5594  5594 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: BT Adapter is not turned ON
11-03 12:12:01.950  5594  5594 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: java.lang.IllegalStateException: BT Adapter is not turned ON
11-03 12:12:01.950  5594  5594 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: 	at android.bluetooth.le.BluetoothLeUtils.checkAdapterStateOn(BluetoothLeUtils.java:136)
11-03 12:12:01.950  5594  5594 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: 	at android.bluetooth.le.BluetoothLeScanner.stopScan(BluetoothLeScanner.java:169)
11-03 12:12:01.950  5594  5594 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner.stop(BleScanner.java:150)
11-03 12:12:01.950  5594  5594 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer.stopScanner(BlePeerDiscoverer.java:436)
11-03 12:12:01.950  5594  5594 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer.stopScannerAndAdvertiser(BlePeerDiscoverer.java:503)
11-03 12:12:01.950  5594  5594 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.stopBlePeerDiscoverer(DiscoveryManager.java:1217)
11-03 12:12:01.950  5594  5594 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.onBluetoothAdapterStateChanged(DiscoveryManager.java:773)
11-03 12:12:01.950  5594  5594 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager$BluetoothModeBroadcastReceiver.onReceive(BluetoothManager.java:564)
11-03 12:12:01.950  5594  5594 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:881)
11-03 12:12:01.950  5594  5594 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: 	at android.os.Handler.handleCallback(Handler.java:739)
11-03 12:12:01.950  5594  5594 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScann,er: 	at android.os.Handler.dispatchMessage(Handler.java:95)
11-03 12:12:01.950  5594  5594 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: 	at android.os.Looper.loop(Looper.java:148)
11-03 12:12:01.950  5594  5594 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-03 12:12:01.950  5594  5594 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: 	at java.lang.reflect.Method.invoke(Native Method)
11-03 12:12:01.950  5594  5594 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-03 12:12:01.950  5594  5594 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-03 12:12:01.950  5594  5594 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[main,5,main], id: 1
11-03 12:12:01.950  5594  5594 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[main,5,main], id: 1
11-03 12:12:01.951  5594  5594 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
11-03 12:12:01.951  5594  5594 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[main,5,main], id: 1
11-03 12:12:01.952  5755  5773 D BtGatt.AdvertiseManager: message : 1
11-03 12:12:01.952  5755  5773 D BtGatt.AdvertiseManager: stop advertise for client 5
11-03 12:12:01.954  3608  3608 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
11-03 12:12:01.955  5755  5771 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
11-03 12:12:01.955  5755  5771 D BtGatt.GattService: Client app is not null!
11-03 12:12:01.956  5755  5797 D BtGatt.GattService: unregisterClient() - clientIf=5
11-03 12:12:01.956  5594  5594 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-03 12:12:01.956  5755  5780 E bt_btif : bta_gattc_deregister Deregister Failedm unknown client cif
11-03 12:12:01.956  5594  5594 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTEDCurrent thread: Thread[main,5,main], id: 1
11-03 12:12:01.956  5594  5594 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
11-03 12:12:01.956  5594  5594 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged false. Current thread: Thread[main,5,main], id: 1
11-03 12:12:01.956  5594  5594 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-03 12:12:01.956  5594  5594 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-03 12:12:01.957  5594  5594 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-03 12:12:01.957  5594  5594 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [ADVERTISING]
11-03 12:12:01.957  5594  5594 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-03 12:12:01.957  5710  5710 D DockEventReceiver: finishStartingService: stopping service
11-03 12:12:01.957  5594  5594 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED],Current thread: Thread[main,5,main], id: 1
11-03 12:12:01.957  5594  5594 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
11-03 12:12:01.957  5594  5594 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-03 12:12:01.958  5594  5594 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-03 12:12:01.958  5594  5594 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: WAITING_FOR_SERVICES_TO_BE_ENABLED, is discovering: false, is advertising: false
11-03 12:12:01.958  5594  5594 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-03 12:12:01.958  5594  5594 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-03 12:12:01.958  5594  5594 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-03 12:12:01.958  5594  5594 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finishedCurrent thread: Thread[main,5,main], id: 1
11-03 12:12:01.959  5594  5594 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[main,5,main], id: 1
11-03 12:12:01.959  5594  5594 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-03 12:12:01.959  5594  5594 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-03 12:12:01.959  5594  5594 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-03 12:12:01.960  5594  5594 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-03 12:12:01.960  5594  5594 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-03 12:12:01.961  5594  5594 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-03 12:12:01.962  5594  5594 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-03 12:12:01.962  5594  5594 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBluetoothAdapterScanModeChanged: Mode changed to 20
11-03 12:12:01.962  5594  5594 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-03 12:12:01.962  5594  5594 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-03 12:12:01.963  5594  5594 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-03 12:12:01.963  5594  5594 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-03 12:12:01.963  5594  5594 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: WAITING_FOR_SERVICES_TO_BE_ENABLED, is discovering: false, is advertising: false
,11-03 12:12:02.146  5755  5771 I bt_hci  : shut_down
11-03 12:12:02.146  5755  5775 D bt_hwcfg: hw_epilog_process
,11-03 12:12:02.147  5755  5775 I bt_vendor: low_power_mode_cb
,11-03 12:12:02.149  5755  5775 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,11-03 12:12:02.149  5755  5775 I bt_vendor: epilog_cb
11-03 12:12:02.150  5755  5775 I bt_hci  : epilog_finished_callback
11-03 12:12:02.150  5755  5771 I bt_hci_h4: hal_close
11-03 12:12:02.151  5755  5771 I bt_userial_vendor: device fd = 54 close
,11-03 12:12:02.274  5755  5768 D bt_stack_manager: event_shut_down_stack finished.
,11-03 12:12:02.275  5755  5767 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,11-03 12:12:02.279  5755  5767 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,11-03 12:12:02.279  5755  5755 D BtGatt.DebugUtils: handleDebugAction() action=null
11-03 12:12:02.281  5755  5755 D BtGatt.GattService: Received stop request...Stopping profile...
11-03 12:12:02.281  5755  5755 D BtGatt.GattService: stop()
,11-03 12:12:02.281  5755  5755 D BtGatt.AdvertiseManager: advertise clients cleared
,11-03 12:12:02.286  5755  5755 V BluetoothAdapterState: isTurningOff()=false
,11-03 12:12:02.286  5755  5755 V BluetoothAdapterState: isTurningOn()=false
11-03 12:12:02.286  5755  5755 V BluetoothAdapterState: isBleTurningOn()=false
11-03 12:12:02.286  5755  5755 V BluetoothAdapterState: isBleTurningOff()=true
11-03 12:12:02.287  5755  5767 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
,11-03 12:12:02.288  5755  5767 D BluetoothAdapterProperties: Setting state to 10
,11-03 12:12:02.288  5755  5767 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
11-03 12:12:02.290  5755  5767 I BluetoothAdapterState: Entering OffState
,11-03 12:12:02.292   928   945 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,11-03 12:12:02.306  5755  5755 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,11-03 12:12:02.306  5755  5755 W BluetoothSdpJni: Cleaning up Bluetooth Health object
11-03 12:12:02.306  5755  5755 I BluetoothServiceJni: cleanupNative: return from cleanup
,11-03 12:12:02.309  5755  5768 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,11-03 12:12:02.316  5755  5755 I art     : System.exit called, status: 0
,11-03 12:12:02.316  5755  5755 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,11-03 12:12:02.347   928  3622 I ActivityManager: Process com.android.bluetooth (pid 5755) has died
,11-03 12:12:02.372  5594  5662 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-03 12:12:02.373  5594  5641 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-03 12:12:02.389   928   945 I ActivityManager: Start proc 5809:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,11-03 12:12:02.455  5809  5809 D AdapterServiceConfig: Adding HeadsetService
,11-03 12:12:02.455  5809  5809 D AdapterServiceConfig: Adding A2dpService
11-03 12:12:02.456  5809  5809 D AdapterServiceConfig: Adding HidService
11-03 12:12:02.456  5809  5809 D AdapterServiceConfig: Adding HealthService
11-03 12:12:02.456  5809  5809 D AdapterServiceConfig: Adding PanService
,11-03 12:12:02.456  5809  5809 D AdapterServiceConfig: Adding GattService
11-03 12:12:02.457  5809  5809 D AdapterServiceConfig: Adding BluetoothMapService
11-03 12:12:02.457  5809  5809 D AdapterServiceConfig: Adding SapService
,11-03 12:12:02.463  5594  5594 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-03 12:12:02.469   928   945 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@4ab704a:true
,11-03 12:12:02.470  5809  5809 D BluetoothAdapterState: make() - Creating AdapterState
,11-03 12:12:02.473  5809  5809 I bt_bluedroid: init
11-03 12:12:02.473  5809  5821 I BluetoothAdapterState: Entering OffState
,11-03 12:12:02.474  5809  5822 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,11-03 12:12:02.474  5809  5822 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
,11-03 12:12:02.475  5809  5822 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
11-03 12:12:02.475  5809  5822 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
11-03 12:12:02.475  5809  5809 I bt_bluedroid: get_profile_interface socket
,11-03 12:12:02.476  5809  5809 I bt_bluedroid: get_profile_interface sdp
11-03 12:12:02.477  5809  5825 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:D4
,11-03 12:12:02.478  5809  5825 D BluetoothAdapterProperties: Name is: Nexus 6P
,11-03 12:12:02.481  5809  5820 I bt_bluedroid: config_hci_snoop_log
,11-03 12:12:02.481   928   945 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
11-03 12:12:02.485  5809  5821 D BluetoothAdapterState: Current state: OFF, message: 0
11-03 12:12:02.485  5809  5821 D BluetoothAdapterProperties: Setting state to 14
11-03 12:12:02.485  5809  5821 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,11-03 12:12:02.487  5809  5821 D BluetoothBondStateMachine: make
,11-03 12:12:02.488  5809  5827 I BluetoothBondStateMachine: StableState(): Entering Off State
,11-03 12:12:02.491  5809  5821 I BluetoothAdapterState: Entering PendingCommandState
,11-03 12:12:02.492  5809  5809 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,11-03 12:12:02.493  5809  5809 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@498a2c9
,11-03 12:12:02.494  5809  5809 D BtGatt.DebugUtils: handleDebugAction() action=null
,11-03 12:12:02.495  5809  5809 D BtGatt.GattService: Received start request. Starting profile...
11-03 12:12:02.495  5809  5809 D BtGatt.GattService: start()
11-03 12:12:02.495  5809  5809 I bt_bluedroid: get_profile_interface gatt
,11-03 12:12:02.496  5809  5809 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@498a2c9
11-03 12:12:02.496  5809  5809 D BtGatt.AdvertiseManager: advertise manager created
,11-03 12:12:02.500  5809  5809 V BluetoothAdapterState: isTurningOff()=false
,11-03 12:12:02.500  5809  5809 V BluetoothAdapterState: isTurningOn()=false
11-03 12:12:02.500  5809  5809 V BluetoothAdapterState: isBleTurningOn()=true
11-03 12:12:02.500  5809  5809 V BluetoothAdapterState: isBleTurningOff()=false
,11-03 12:12:02.501  5809  5821 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
11-03 12:12:02.502  5809  5821 I bt_bluedroid: bt_bluedroid
11-03 12:12:02.502  5809  5822 D bt_stack_manager: event_start_up_stack is bringing up the stack.
11-03 12:12:02.502  5809  5822 I bt_hci  : start_up
,11-03 12:12:02.507  5809  5822 I bt_vendor: alloc value 0xf3b09871
,11-03 12:12:02.507  5809  5822 I bt_vendor: init
11-03 12:12:02.507  5809  5822 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
11-03 12:12:02.507  5809  5822 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,11-03 12:12:02.618  5809  5822 D bt_hci  : start_up starting async portion
,11-03 12:12:02.618  5809  5830 I bt_hci  : event_finish_startup
11-03 12:12:02.618  5809  5830 I bt_hci_h4: hal_open
11-03 12:12:02.618  5809  5830 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,11-03 12:12:02.619  5831  5831 W irq/448-msm_hs_: type=1400 audit(0.0:118): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-03 12:12:02.622  5809  5830 I bt_userial_vendor: device fd = 54 open
,11-03 12:12:02.636  5809  5830 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,11-03 12:12:02.638  5809  5830 D bt_hwcfg: Chipset BCM4358A3
,11-03 12:12:02.638  5809  5830 D bt_hwcfg: Target name = [BCM4358A3]
11-03 12:12:02.639  5809  5830 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,11-03 12:12:02.881  5809  5821 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 0
,11-03 12:12:02.990  5704  5704 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-03 12:12:02.999  5704  5704 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-03 12:12:03.006  5704  5704 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-03 12:12:03.012  5704  5704 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-03 12:12:03.032  5809  5830 I bt_hwcfg: bt vendor lib: set UART baud 115200
,11-03 12:12:03.032  5809  5830 D bt_hwcfg: Settlement delay -- 100 ms
11-03 12:12:03.032  5809  5830 I bt_hwcfg: Setting fw settlement delay to 100 
,11-03 12:12:03.038   928  2977 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,11-03 12:12:03.039   928  2977 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3
,11-03 12:12:03.040   928  2977 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-03 12:12:03.051   928  2977 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=0
,11-03 12:12:03.086   928  2977 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=0
,11-03 12:12:03.091  5704  5704 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,11-03 12:12:03.154  5809  5830 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,11-03 12:12:03.154  5809  5830 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:D4
11-03 12:12:03.155  5809  5830 I bt_hwcfg: vendor lib fwcfg completed
11-03 12:12:03.155  5809  5830 I bt_vendor: firmware callback
11-03 12:12:03.155  5809  5830 I bt_hci  : firmware_config_callback
,11-03 12:12:03.158  5809  5833 I bt_btu  : btu_task pending for preload complete event
,11-03 12:12:03.158  5809  5833 I bt_btu_task: Bluetooth chip preload is complete
,11-03 12:12:03.158  5809  5833 I bt_btu  : btu_task received preload complete event
,11-03 12:12:03.163  5809  5833 I         : BTE_InitTraceLevels -- TRC_HCI
,11-03 12:12:03.163  5809  5833 I         : BTE_InitTraceLevels -- TRC_L2CAP
11-03 12:12:03.163  5809  5833 I         : BTE_InitTraceLevels -- TRC_RFCOMM
11-03 12:12:03.163  5809  5833 I         : BTE_InitTraceLevels -- TRC_AVDT
11-03 12:12:03.163  5809  5833 I         : BTE_InitTraceLevels -- TRC_AVRC
11-03 12:12:03.163  5809  5833 I         : BTE_InitTraceLevels -- TRC_A2D
11-03 12:12:03.163  5809  5833 I         : BTE_InitTraceLevels -- TRC_BNEP
11-03 12:12:03.164  5809  5833 I         : BTE_InitTraceLevels -- TRC_BTM
,11-03 12:12:03.164  5809  5833 I         : BTE_InitTraceLevels -- TRC_GAP
11-03 12:12:03.164  5809  5833 I         : BTE_InitTraceLevels -- TRC_PAN
11-03 12:12:03.164  5809  5833 I         : BTE_InitTraceLevels -- TRC_SDP
11-03 12:12:03.164  5809  5833 I         : BTE_InitTraceLevels -- TRC_GATT
11-03 12:12:03.164  5809  5833 I         : BTE_InitTraceLevels -- TRC_SMP
11-03 12:12:03.164  5809  5833 I         : BTE_InitTraceLevels -- TRC_BTAPP
11-03 12:12:03.164  5809  5833 I         : BTE_InitTraceLevels -- TRC_BTIF
,11-03 12:12:03.235  5809  5833 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf3a87549
,11-03 12:12:03.235  5809  5833 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf3a87549 
,11-03 12:12:03.254  5809  5825 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = true
,11-03 12:12:03.255  5809  5825 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
11-03 12:12:03.256  5809  5825 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:D4
,11-03 12:12:03.258  5809  5825 D BluetoothAdapterProperties: Name is: Nexus 6P
,11-03 12:12:03.261  5809  5825 D BluetoothAdapterProperties: Scan Mode:20
,11-03 12:12:03.262  5809  5825 D BluetoothAdapterProperties: Discoverable Timeout:120
11-03 12:12:03.263  5809  5825 D bt_hci  : do_postload posting postload work item
11-03 12:12:03.263  5809  5830 I bt_hci  : event_postload
11-03 12:12:03.263  5809  5830 I bt_vendor: sco_config_cb
11-03 12:12:03.263  5809  5830 I bt_hci  : sco_config_callback postload finished.
11-03 12:12:03.266  5594  5594 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-03 12:12:03.268  5594  5594 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-03 12:12:03.268  5594  5594 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBluetoothAdapterScanModeChanged: Mode changed to 20
,11-03 12:12:03.268  5594  5594 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-03 12:12:03.269  5809  5830 I bt_vendor: low_power_mode_cb
11-03 12:12:03.269  5594  5594 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-03 12:12:03.269  5594  5594 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-03 12:12:03.269  5594  5594 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-03 12:12:03.270  5809  5825 D bt_bte_conf: Device ID record 1 : primary
11-03 12:12:03.271  5809  5825 D bt_bte_conf:   vendorId            = 000f
11-03 12:12:03.271  5809  5825 D bt_bte_conf:   vendorIdSource      = 0001
,11-03 12:12:03.271  5809  5825 D bt_bte_conf:   product             = 1200
11-03 12:12:03.271  5809  5825 D bt_bte_conf:   version             = 1436
11-03 12:12:03.271  5809  5825 D bt_bte_conf:   clientExecutableURL = 
11-03 12:12:03.271  5809  5825 D bt_bte_conf:   serviceDescription  = 
11-03 12:12:03.271  5809  5825 D bt_bte_conf:   documentationURL    = 
11-03 12:12:03.271  5809  5825 D bt_bte_conf: bte_load_did_conf no section named DID2.
11-03 12:12:03.271  5809  5822 D bt_stack_manager: event_start_up_stack finished
,11-03 12:12:03.272  5809  5821 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
11-03 12:12:03.272  5809  5821 D BluetoothAdapterProperties: Setting state to 15
11-03 12:12:03.272  5809  5821 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
11-03 12:12:03.272  5809  5821 I BluetoothAdapterState: Entering BleOnState
,11-03 12:12:03.275  5809  5821 D BluetoothAdapterState: Current state: BLE ON, message: 1
11-03 12:12:03.275  5809  5821 D BluetoothAdapterProperties: Setting state to 11
,11-03 12:12:03.275  5809  5821 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,11-03 12:12:03.279  5809  5809 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@498a2c9
,11-03 12:12:03.282  5594  5594 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-03 12:12:03.284  5594  5594 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-03 12:12:03.284  5594  5594 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBluetoothAdapterStateChanged: State changed to 11
,11-03 12:12:03.286  5809  5809 D HeadsetService: Received start request. Starting profile...
,11-03 12:12:03.286  3146  3158 D BluetoothHeadset: Proxy object connected
11-03 12:12:03.287   928   928 D BluetoothHeadset: Proxy object connected
11-03 12:12:03.287   928   928 D BluetoothHeadset: Proxy object connected
11-03 12:12:03.287   928   928 D BluetoothHeadset: Proxy object connected
11-03 12:12:03.287  3765  4010 D BluetoothHeadset: Proxy object connected
11-03 12:12:03.288  5710  5721 D BluetoothHeadset: Proxy object connected
11-03 12:12:03.289  5809  5809 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,11-03 12:12:03.289  5809  5809 D HeadsetStateMachine: make
11-03 12:12:03.292  5710  5710 D HeadsetProfile: Bluetooth service connected
,11-03 12:12:03.297  3146  3146 D HeadsetProfile: Bluetooth service connected
11-03 12:12:03.298  5809  5821 I BluetoothAdapterState: Entering PendingCommandState
,11-03 12:12:03.300  5809  5809 D HeadsetStateMachine: max_hf_connections = 1
11-03 12:12:03.300  5809  5809 I bt_bluedroid: get_profile_interface handsfree
11-03 12:12:03.300  5809  5825 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
,11-03 12:12:03.300  5809  5825 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
,11-03 12:12:03.303  5809  5809 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@498a2c9
11-03 12:12:03.303  5809  5809 D A2dpService: Received start request. Starting profile...
11-03 12:12:03.304  5809  5809 I BluetoothAvrcpServiceJni: classInitNative: succeeds
11-03 12:12:03.304  5809  5809 I bt_bluedroid: get_profile_interface avrcp
,11-03 12:12:03.311  5809  5809 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,11-03 12:12:03.311  5809  5809 I BluetoothA2dpServiceJni: classInitNative: succeeds
11-03 12:12:03.311  5809  5809 D A2dpStateMachine: make
,11-03 12:12:03.312  5809  5809 I bt_bluedroid: get_profile_interface a2dp
,11-03 12:12:03.313  5809  5825 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,11-03 12:12:03.314  5809  5840 D A2dpStateMachine: Enter Disconnected: -2
,11-03 12:12:03.315  5809  5809 I BluetoothHidServiceJni: classInitNative: succeeds
,11-03 12:12:03.316  5809  5809 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@498a2c9
,11-03 12:12:03.317  3608  3608 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
11-03 12:12:03.317  5809  5809 D HidService: Received start request. Starting profile...
11-03 12:12:03.318  5809  5809 I bt_bluedroid: get_profile_interface hidhost
,11-03 12:12:03.318  5809  5825 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf3a6856d
11-03 12:12:03.318  5809  5809 D HidService: setHidService(): set to: null
11-03 12:12:03.318  5809  5825 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
11-03 12:12:03.318  5809  5809 I BluetoothHealthServiceJni: classInitNative: succeeds
,11-03 12:12:03.319  5809  5809 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@498a2c9
,11-03 12:12:03.320  5809  5809 D HealthService: Received start request. Starting profile...
,11-03 12:12:03.322  5809  5809 I bt_bluedroid: get_profile_interface health
11-03 12:12:03.323  5809  5809 I BluetoothPanServiceJni: classInitNative(L105): succeeds
11-03 12:12:03.323  5809  5809 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@498a2c9
11-03 12:12:03.324  5809  5809 D PanService: Received start request. Starting profile...
11-03 12:12:03.324  5809  5809 D BluetoothPanServiceJni: initializeNative(L110): pan
11-03 12:12:03.324  5809  5809 I bt_bluedroid: get_profile_interface pan
,11-03 12:12:03.324  5809  5825 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
11-03 12:12:03.326  5809  5809 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@498a2c9
,11-03 12:12:03.326  5809  5809 D BluetoothMapService: Received start request. Starting profile...
,11-03 12:12:03.326  5809  5809 D BluetoothMapService: start()
11-03 12:12:03.329  5809  5809 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
11-03 12:12:03.330  5809  5809 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
11-03 12:12:03.330  5809  5809 D BluetoothMapAppObserver: createReceiver()
11-03 12:12:03.331  5809  5809 D BluetoothMapAppObserver: initObservers()
11-03 12:12:03.331  5809  5809 D BluetoothMapAppObserver: getEnabledAccountItems()
,11-03 12:12:03.338  5809  5809 V SapService: SapBinder()
,11-03 12:12:03.338  5809  5809 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@498a2c9
,11-03 12:12:03.339  5809  5809 D SapService: Received start request. Starting profile...
,11-03 12:12:03.339  5809  5809 V SapService: start()
11-03 12:12:03.341  5809  5809 V BluetoothAdapterState: isTurningOff()=false
11-03 12:12:03.341  5809  5809 V BluetoothAdapterState: isTurningOn()=true
11-03 12:12:03.341  5809  5809 V BluetoothAdapterState: isBleTurningOn()=false
,11-03 12:12:03.341  5809  5838 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
11-03 12:12:03.341  5809  5809 V BluetoothAdapterState: isBleTurningOff()=false
11-03 12:12:03.342  5809  5809 V BluetoothAdapterState: isTurningOff()=false
11-03 12:12:03.342  5809  5809 V BluetoothAdapterState: isTurningOn()=true
11-03 12:12:03.342  5809  5809 V BluetoothAdapterState: isBleTurningOn()=false
11-03 12:12:03.342  5809  5809 V BluetoothAdapterState: isBleTurningOff()=false
,11-03 12:12:03.342  5809  5809 V BluetoothAdapterState: isTurningOff()=false
11-03 12:12:03.343  5809  5809 V BluetoothAdapterState: isTurningOn()=true
11-03 12:12:03.343  5809  5809 V BluetoothAdapterState: isBleTurningOn()=false
11-03 12:12:03.343  5809  5809 V BluetoothAdapterState: isBleTurningOff()=false
,11-03 12:12:03.343  5809  5809 V BluetoothAdapterState: isTurningOff()=false
,11-03 12:12:03.343  5809  5809 V BluetoothAdapterState: isTurningOn()=true
11-03 12:12:03.343  5809  5809 V BluetoothAdapterState: isBleTurningOn()=false
11-03 12:12:03.343  5809  5809 V BluetoothAdapterState: isBleTurningOff()=false
11-03 12:12:03.343  5809  5809 V BluetoothAdapterState: isTurningOff()=false
11-03 12:12:03.343  5809  5809 V BluetoothAdapterState: isTurningOn()=true
11-03 12:12:03.343  5809  5809 V BluetoothAdapterState: isBleTurningOn()=false
11-03 12:12:03.343  5809  5809 V BluetoothAdapterState: isBleTurningOff()=false
11-03 12:12:03.344  5809  5809 V BluetoothAdapterState: isTurningOff()=false
11-03 12:12:03.344  5809  5809 V BluetoothAdapterState: isTurningOn()=true
11-03 12:12:03.344  5809  5809 V BluetoothAdapterState: isBleTurningOn()=false
11-03 12:12:03.344  5809  5809 V BluetoothAdapterState: isBleTurningOff()=false
11-03 12:12:03.345  5809  5809 V BluetoothAdapterState: isTurningOff()=false
11-03 12:12:03.345  5809  5809 V BluetoothAdapterState: isTurningOn()=true
11-03 12:12:03.345  5809  5809 V BluetoothAdapterState: isBleTurningOn()=false
,11-03 12:12:03.345  5809  5809 V BluetoothAdapterState: isBleTurningOff()=false
,11-03 12:12:03.345  5809  5821 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
11-03 12:12:03.345  5809  5821 D BluetoothAdapterProperties: ScanMode =  20
11-03 12:12:03.345  5809  5821 D BluetoothAdapterProperties: State =  11
11-03 12:12:03.346  5809  5821 D BluetoothAdapterProperties: Setting state to 12
11-03 12:12:03.346  5809  5821 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,11-03 12:12:03.347  5710  5720 D BluetoothPan: onBluetoothStateChange on: true
11-03 12:12:03.347  5809  5825 D BluetoothAdapterProperties: Scan Mode:21
,11-03 12:12:03.347  5809  5825 D BluetoothAdapterProperties: Discoverable Timeout:120
11-03 12:12:03.347  5594  5594 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
11-03 12:12:03.348  5809  5821 I BluetoothAdapterState: Entering OnState
11-03 12:12:03.349   928   945 D BluetoothA2dp: onBluetoothStateChange: up=true
11-03 12:12:03.350  3146  3158 D BluetoothPan: onBluetoothStateChange on: true
11-03 12:12:03.351  5710  5710 D BluetoothPan: BluetoothPAN Proxy object connected
11-03 12:12:03.351  5710  5710 D PanProfile: Bluetooth service connected
11-03 12:12:03.351   928   928 D BluetoothA2dp: Proxy object connected
11-03 12:12:03.351  5594  5594 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-03 12:12:03.351  5594  5594 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-03 12:12:03.351  5594  5594 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-03 12:12:03.351  5594  5594 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-03 12:12:03.351  5594  5594 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-03 12:12:03.351  5594  5594 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-03 12:12:03.351  5594  5594 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-03 12:12:03.351  5594  5594 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-03 12:12:03.354  3146  3146 D BluetoothPan: BluetoothPAN Proxy object connected
11-03 12:12:03.354  3146  3146 D PanProfile: Bluetooth service connected
11-03 12:12:03.354  5594  5594 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
11-03 12:12:03.354   928   945 D BluetoothHeadset: onBluetoothStateChange: up=true
11-03 12:12:03.355  3765  3779 D BluetoothHeadset: onBluetoothStateChange: up=true
,11-03 12:12:03.355  5710  5720 D BluetoothA2dp: onBluetoothStateChange: up=true
,11-03 12:12:03.357   928   945 D BluetoothHeadset: onBluetoothStateChange: up=true
,11-03 12:12:03.357  5809  5809 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
11-03 12:12:03.357  3146  3163 D BluetoothHeadset: onBluetoothStateChange: up=true
11-03 12:12:03.357  3146  4001 D BluetoothA2dp: onBluetoothStateChange: up=true
,11-03 12:12:03.357  5809  5809 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
11-03 12:12:03.358  5594  5594 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-03 12:12:03.358  5594  5594 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-03 12:12:03.358  5594  5594 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-03 12:12:03.358  5594  5594 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-03 12:12:03.358  5594  5594 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-03 12:12:03.358  5594  5594 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-03 12:12:03.358  5594  5594 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-03 12:12:03.358  5594  5594 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,11-03 12:12:03.359  3146  3146 D BluetoothA2dp: Proxy object connected
11-03 12:12:03.359  3146  3163 D BluetoothPbap: onBluetoothStateChange: up=true
11-03 12:12:03.360  5594  5594 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,11-03 12:12:03.360  5594  5594 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBluetoothAdapterScanModeChanged: Mode changed to 21
,11-03 12:12:03.361  5710  5721 D BluetoothInputDevice: onBluetoothStateChange: up=true
11-03 12:12:03.361  5710  5710 D BluetoothA2dp: Proxy object connected
11-03 12:12:03.361  5809  5809 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-03 12:12:03.361  5594  5594 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBluetoothAdapterScanModeChanged: Bluetooth enabled, restarting BLE based peer discovery...
11-03 12:12:03.361  5594  5594 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
11-03 12:12:03.363  3146  4001 D BluetoothInputDevice: onBluetoothStateChange: up=true
11-03 12:12:03.363  5594  5594 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-03 12:12:03.363  5594  5594 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-03 12:12:03.363  5594  5594 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
11-03 12:12:03.363  5809  5809 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-03 12:12:03.364  5809  5809 D ObexServerSockets: Succeed to create listening sockets 
11-03 12:12:03.364  5809  5809 D ObexServerSockets0: startAccept()
11-03 12:12:03.364  5809  5809 D ObexServerSockets0: prepareForNewConnect()
11-03 12:12:03.365  5710  5720 D BluetoothMap: onBluetoothStateChange: up=true
11-03 12:12:03.366  5594  5594 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-03 12:12:03.366  5594  5594 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-03 12:12:03.366  5594  5594 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-03 12:12:03.367  5710  5721 D BluetoothHeadset: onBluetoothStateChange: up=true
11-03 12:12:03.367  3146  3158 D BluetoothMap: onBluetoothStateChange: up=true
11-03 12:12:03.368  5594  5594 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Current thread: Thread[main,5,main], id: 1
11-03 12:12:03.368  5594  5594 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
11-03 12:12:03.368  5594  5594 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-03 12:12:03.368  5594  5594 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 04 60 83 34 25 D7 D4
11-03 12:12:03.368  5710  5846 D BluetoothPbap: onBluetoothStateChange: up=true
11-03 12:12:03.369  5594  5594 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[4, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,11-03 12:12:03.369  5594  5594 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: Current thread: Thread[main,5,main], id: 1
11-03 12:12:03.369  5594  5594 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData finished: Current thread: Thread[main,5,main], id: 1
11-03 12:12:03.369  5594  5594 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = NOT_STARTEDCurrent thread: Thread[main,5,main], id: 1
11-03 12:12:03.369  5594  5594 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... adv data = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[4, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]Current thread: Thread[main,5,main], id: 1
11-03 12:12:03.370  5594  5594 D BluetoothAdapter: STATE_ON
11-03 12:12:03.370   928   945 D BluetoothHeadset: onBluetoothStateChange: up=true
11-03 12:12:03.372  5809  5809 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
11-03 12:12:03.372  5809  5809 D BluetoothSdpJni: SDP Create record success - handle: 0
,11-03 12:12:03.372   928   928 I Telecom : BluetoothPhoneService: queryPhoneState
11-03 12:12:03.373   928   928 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
11-03 12:12:03.375  5809  5826 D BtGatt.GattService: registerClient() - UUID=ced01ad1-2de0-470c-9647-57ca2f4ed1c2
11-03 12:12:03.376  5809  5825 D BtGatt.GattService: onClientRegistered() - UUID=ced01ad1-2de0-470c-9647-57ca2f4ed1c2, clientIf=5
11-03 12:12:03.376  5809  5848 D ObexServerSockets0: Accepting socket connection...
11-03 12:12:03.376  5594  5604 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
,11-03 12:12:03.377  3146  3146 D BluetoothInputDevice: Proxy object connected
11-03 12:12:03.377  3146  3146 D HidProfile: Bluetooth service connected
11-03 12:12:03.378  5809  5809 D BluetoothMapService: onReceive
11-03 12:12:03.378  5809  5809 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,11-03 12:12:03.378  5809  5809 D BluetoothMapService: STATE_ON
11-03 12:12:03.378  5809  5847 D ObexServerSockets0: Accepting socket connection...
11-03 12:12:03.378  5809  5828 D BtGatt.AdvertiseManager: message : 0
11-03 12:12:03.380  5710  5710 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
11-03 12:12:03.380  5809  5850 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-03 12:12:03.383  5809  5828 D BtGatt.AdvertiseManager: starting multi advertising
11-03 12:12:03.384  5710  5710 D BluetoothInputDevice: Proxy object connected
11-03 12:12:03.384  5710  5710 D HidProfile: Bluetooth service connected
11-03 12:12:03.385  5809  5850 D BluetoothSdpJni: sdpCreateSapsRecordNative:
11-03 12:12:03.386  5809  5850 D BluetoothSdpJni: SDP Create record success - handle: 1
11-03 12:12:03.386  5594  5662 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-03 12:12:03.386  5594  5662 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-03 12:12:03.386  5594  5662 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-03 12:12:03.386  5594  5662 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-03 12:12:03.386  5594  5662 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-03 12:12:03.386  5594  5662 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-03 12:12:03.386  5594  5662 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-03 12:12:03.386  5594  5662 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,11-03 12:12:03.388  5710  5710 D BluetoothMap: Proxy object connected
,11-03 12:12:03.388  3608  3608 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
11-03 12:12:03.388  5710  5710 D MapProfile: Bluetooth service connected
11-03 12:12:03.388  5710  5710 D BluetoothMap: getConnectedDevices()
11-03 12:12:03.390  5594  5662 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
11-03 12:12:03.390  5809  5825 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
11-03 12:12:03.391  3146  3146 D BluetoothMap: Proxy object connected
11-03 12:12:03.391  3146  3146 D MapProfile: Bluetooth service connected
11-03 12:12:03.391  3146  3146 D BluetoothMap: getConnectedDevices()
11-03 12:12:03.392  5594  5641 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testIsWifiEnabled
,11-03 12:12:03.393   928   939 D WifiService: setWifiEnabled: false pid=5594, uid=10077
11-03 12:12:03.393   928   939 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-03 12:12:03.394  5594  5641 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-03 12:12:03.395  5809  5825 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,11-03 12:12:03.396   928   928 D RttService: SCAN_AVAILABLE : 1
,11-03 12:12:03.396  5594  5594 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment Current thread: Thread[main,5,main], id: 1
,11-03 12:12:03.396   928  3098 D RttService: EnabledState got{ when=-1ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
11-03 12:12:03.397  5594  5594 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTINGCurrent thread: Thread[main,5,main], id: 1
11-03 12:12:03.397  5594  5594 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
11-03 12:12:03.397  5594  5594 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged default (no call to listener). Current thread: Thread[main,5,main], id: 1
11-03 12:12:03.397  5594  5594 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finishedCurrent thread: Thread[main,5,main], id: 1
11-03 12:12:03.397  5594  5594 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[main,5,main], id: 1
11-03 12:12:03.397  5594  5594 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[main,5,main], id: 1
11-03 12:12:03.397  5594  5594 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser started = trueCurrent thread: Thread[main,5,main], id: 1
11-03 12:12:03.397  5710  5710 D DockEventReceiver: finishStartingService: stopping service
11-03 12:12:03.397  5594  5594 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,11-03 12:12:03.397  3146  3146 D BluetoothPbap: Proxy object connected
11-03 12:12:03.397  3146  3146 D PbapServerProfile: Bluetooth service connected
11-03 12:12:03.398  5710  5710 D BluetoothPbap: Proxy object connected
11-03 12:12:03.398  5710  5710 D PbapServerProfile: Bluetooth service connected
11-03 12:12:03.398  5594  5594 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,11-03 12:12:03.398  5594  5594 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-03 12:12:03.399  5594  5594 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-03 12:12:03.399  5594  5594 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-03 12:12:03.399  5594  5594 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-03 12:12:03.400  5594  5594 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-03 12:12:03.400  5594  5594 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
11-03 12:12:03.401  5594  5594 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-03 12:12:03.403  5594  5594 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-03 12:12:03.403  5594  5594 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBluetoothAdapterStateChanged: State changed to 12
,11-03 12:12:03.404  5594  5594 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBluetoothAdapterStateChanged: Bluetooth enabled, restarting BLE based peer discovery...
,11-03 12:12:03.404  5594  5594 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
11-03 12:12:03.404  5809  5809 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
11-03 12:12:03.404  5809  5809 D ObexServerSockets0: prepareForNewConnect()
11-03 12:12:03.405  5594  5594 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-03 12:12:03.405  5594  5594 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-03 12:12:03.405  5809  5855 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-03 12:12:03.406   928  2977 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
11-03 12:12:03.407   508   921 D CommandListener: Clearing all IP addresses on wlan0
11-03 12:12:03.407  5594  5594 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Current thread: Thread[main,5,main], id: 1
11-03 12:12:03.407  5594  5594 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-03 12:12:03.407  5594  5594 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 04 60 83 34 25 D7 D4
,11-03 12:12:03.407  5594  5594 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[4, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-03 12:12:03.407  5594  5594 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: Current thread: Thread[main,5,main], id: 1
11-03 12:12:03.407  5594  5594 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[main,5,main], id: 1
11-03 12:12:03.408  5809  5828 D BtGatt.AdvertiseManager: message : 1
11-03 12:12:03.408  5809  5828 D BtGatt.AdvertiseManager: stop advertise for client 5
,11-03 12:12:03.410   928  2977 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
11-03 12:12:03.413  5809  5825 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
,11-03 12:12:03.413  5809  5825 D BtGatt.GattService: Client app is not null!
11-03 12:12:03.414  5704  5704 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
11-03 12:12:03.414  5809  5819 D BtGatt.GattService: unregisterClient() - clientIf=5
,11-03 12:12:03.415  5594  5594 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-03 12:12:03.415  5594  5594 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = NOT_STARTEDCurrent thread: Thread[main,5,main], id: 1
11-03 12:12:03.415  5594  5594 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to NOT_STARTED
11-03 12:12:03.415  5594  5594 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finishedCurrent thread: Thread[main,5,main], id: 1
11-03 12:12:03.415  5594  5594 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[main,5,main], id: 1
11-03 12:12:03.415  5594  5594 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = NOT_STARTEDCurrent thread: Thread[main,5,main], id: 1
11-03 12:12:03.415  5594  5594 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... adv data = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[4, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]Current thread: Thread[main,5,main], id: 1
11-03 12:12:03.416  5594  5594 D BluetoothAdapter: STATE_ON
,11-03 12:12:03.419  5809  5819 D BtGatt.GattService: registerClient() - UUID=3d98d7ec-a51f-4071-b134-26088ef8b212
11-03 12:12:03.421  5809  5825 D BtGatt.GattService: onClientRegistered() - UUID=3d98d7ec-a51f-4071-b134-26088ef8b212, clientIf=5
11-03 12:12:03.421  5594  5605 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
,11-03 12:12:03.423  5809  5828 D BtGatt.AdvertiseManager: message : 0
,11-03 12:12:03.424  5809  5859 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-03 12:12:03.425  5809  5828 D BtGatt.AdvertiseManager: starting multi advertising
11-03 12:12:03.425  5809  5859 I BtOppRfcommListener: Accept thread started.
,11-03 12:12:03.435  5809  5825 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,11-03 12:12:03.438  5809  5825 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,11-03 12:12:03.439  5594  5594 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment Current thread: Thread[main,5,main], id: 1
11-03 12:12:03.439  5594  5594 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTINGCurrent thread: Thread[main,5,main], id: 1
11-03 12:12:03.439  5594  5594 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
11-03 12:12:03.439  5594  5594 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged default (no call to listener). Current thread: Thread[main,5,main], id: 1
11-03 12:12:03.439  5594  5594 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finishedCurrent thread: Thread[main,5,main], id: 1
11-03 12:12:03.439  5594  5594 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[main,5,main], id: 1
11-03 12:12:03.439  5594  5594 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[main,5,main], id: 1
11-03 12:12:03.439  5594  5594 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData finished: Current thread: Thread[main,5,main], id: 1
11-03 12:12:03.439  5594  5594 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = STARTINGCurrent thread: Thread[main,5,main], id: 1
,11-03 12:12:03.439  5594  5594 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Already running
11-03 12:12:03.439  5594  5594 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[main,5,main], id: 1
11-03 12:12:03.439  5594  5594 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[main,5,main], id: 1
11-03 12:12:03.439  5594  5594 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser started = trueCurrent thread: Thread[main,5,main], id: 1
11-03 12:12:03.439  5594  5594 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-03 12:12:03.441  5594  5594 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-03 12:12:03.441  5594  5594 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
,11-03 12:12:03.442  5594  5594 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
,11-03 12:12:03.442  5594  5594 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-03 12:12:03.442  5594  5594 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-03 12:12:03.442  5594  5594 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess : Current thread: Thread[main,5,main], id: 1
11-03 12:12:03.442  5594  5594 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNINGCurrent thread: Thread[main,5,main], id: 1
11-03 12:12:03.442  5594  5594 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
11-03 12:12:03.442  5594  5594 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged true. Current thread: Thread[main,5,main], id: 1
11-03 12:12:03.442  5594  5594 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-03 12:12:03.443  5594  5594 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-03 12:12:03.443  5594  5594 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [ADVERTISING]
,11-03 12:12:03.443  5594  5594 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-03 12:12:03.443  5594  5594 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-03 12:12:03.443  5594  5594 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]Current thread: Thread[main,5,main], id: 1
11-03 12:12:03.443  5594  5594 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
11-03 12:12:03.443  5594  5594 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-03 12:12:03.445  5594  5594 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-03 12:12:03.445  5594  5594 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
11-03 12:12:03.445  5594  5594 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-03 12:12:03.445  5594  5594 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
,11-03 12:12:03.445  5594  5594 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-03 12:12:03.445  5594  5594 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finishedCurrent thread: Thread[main,5,main], id: 1
11-03 12:12:03.445  5594  5594 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,11-03 12:12:03.448  5594  5594 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-03 12:12:03.448  5594  5594 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-03 12:12:03.448  5594  5594 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-03 12:12:03.448  5594  5594 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-03 12:12:03.448  5594  5594 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-03 12:12:03.448  5594  5594 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-03 12:12:03.448  5594  5594 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-03 12:12:03.448  5594  5594 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,11-03 12:12:03.449  5594  5594 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,11-03 12:12:03.452  5594  5594 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-03 12:12:03.452  5594  5594 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-03 12:12:03.452  5594  5594 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-03 12:12:03.452  5594  5594 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-03 12:12:03.452  5594  5594 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-03 12:12:03.452  5594  5594 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-03 12:12:03.452  5594  5594 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-03 12:12:03.452  5594  5594 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,11-03 12:12:03.453  5594  5594 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
11-03 12:12:03.455  5594  5594 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess : Current thread: Thread[main,5,main], id: 1
11-03 12:12:03.455  5594  5594 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = RUNNINGCurrent thread: Thread[main,5,main], id: 1
11-03 12:12:03.455  5594  5594 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finishedCurrent thread: Thread[main,5,main], id: 1
11-03 12:12:03.455  5594  5594 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,11-03 12:12:03.490  5704  5704 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
,11-03 12:12:03.492  5704  5704 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=00:00:00:00:00:00 reason=3 locally_generated=1
,11-03 12:12:03.496  5704  5704 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,11-03 12:12:03.504  5704  5704 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,11-03 12:12:03.607   928  2977 D wifi    : In wifi stop Hal
,11-03 12:12:03.607   928  2977 D wifi    : halHandle = 0x7f5a788900, mVM = 0x7f76dcd140, mCls = 0x2014ae
11-03 12:12:03.607   928  5703 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
,11-03 12:12:03.607   928  5703 D WifiHAL : Got a signal to exit!!!
11-03 12:12:03.607   928  5703 I WifiHAL : Exit wifi_event_loop
11-03 12:12:03.608   928  2977 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 0
11-03 12:12:03.608   928  2977 E WifiHAL : Event processing terminated
11-03 12:12:03.609   928  2977 D wifi    : In wifi cleaned up handler
11-03 12:12:03.609   928  2977 I WifiHAL : Internal cleanup completed
11-03 12:12:03.614  3961  4224 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
11-03 12:12:03.615  4472  4472 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
11-03 12:12:03.619  5594  5594 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-03 12:12:03.621  5594  5594 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-03 12:12:03.646   928  5703 D wifi    : set interface wlan0 flags (DOWN)
,11-03 12:12:03.646   928  2977 D WifiNative-HAL: HAL event thread stopped successfully
,11-03 12:12:03.852   928   945 D Tethering: InitialState.processMessage what=4
,11-03 12:12:03.859   928   945 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,11-03 12:12:03.904  5594  5662 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-03 12:12:03.904  5594  5662 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-03 12:12:03.904  5594  5662 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-03 12:12:03.904  5594  5662 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-03 12:12:03.904  5594  5662 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-03 12:12:03.904  5594  5662 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-03 12:12:03.904  5594  5662 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-03 12:12:03.904  5594  5662 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,11-03 12:12:03.908  5594  5662 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,11-03 12:12:03.911   928   938 D WifiService: setWifiEnabled: true pid=5594, uid=10077
11-03 12:12:03.912   928   938 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-03 12:12:03.915  5594  5641 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-03 12:12:03.920   508   921 D SoftapController: Softap fwReload - Ok
,11-03 12:12:03.924   508   921 D CommandListener: Setting iface cfg
,11-03 12:12:03.924   508   921 D CommandListener: Trying to bring down wlan0
11-03 12:12:03.925   508   921 D CommandListener: Clearing all IP addresses on wlan0
,11-03 12:12:03.929   928  2977 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,11-03 12:12:03.955  5594  5594 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
,11-03 12:12:04.092   545   545 I ServiceManager: Waiting for service AtCmdFwd...
,11-03 12:12:04.417   928  3603 D WifiService: setWifiEnabled: true pid=5594, uid=10077
,11-03 12:12:04.422   928  3603 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-03 12:12:04.538   928  2977 D wifi    : set interface wlan0 flags (UP)
,11-03 12:12:04.539   928  2977 I WifiHAL : Initializing wifi
,11-03 12:12:04.539   928  2977 I WifiHAL : Creating socket
,11-03 12:12:04.544   928   945 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
11-03 12:12:04.545   928  2977 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
11-03 12:12:04.545   928  2977 D wifi    : Did set static halHandle = 0x7f5a788900
11-03 12:12:04.546   928  2977 D wifi    : halHandle = 0x7f5a788900, mVM = 0x7f76dcd140, mCls = 0x12c2
11-03 12:12:04.546   928  2977 D wifi    : array field set
,11-03 12:12:04.546   928  2977 I WifiNative-HAL: interface[0] = wlan0
11-03 12:12:04.550   928  5863 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=546978695424
11-03 12:12:04.550   928  5863 D wifi    : waitForHalEvents called, vm = 0x7f76dcd140, obj = 0x12c2, env = 0x7f5acfb780
,11-03 12:12:04.601  5864  5864 I wpa_supplicant: Successfully initialized wpa_supplicant
,11-03 12:12:04.650   928  2977 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,11-03 12:12:04.656  5594  5594 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-03 12:12:04.661  5594  5594 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-03 12:12:04.674  5864  5864 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,11-03 12:12:04.733  5864  5864 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,11-03 12:12:04.733  5864  5864 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,11-03 12:12:04.750   928  2977 D WifiConfigStore: Loading config and enabling all networks 
,11-03 12:12:04.757  5594  5594 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-03 12:12:04.757  5594  5594 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-03 12:12:04.757  5594  5594 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-03 12:12:04.757  5594  5594 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-03 12:12:04.757  5594  5594 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-03 12:12:04.757  5594  5594 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-03 12:12:04.757  5594  5594 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-03 12:12:04.757  5594  5594 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,11-03 12:12:04.761  5594  5594 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,11-03 12:12:04.766  5594  5594 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-03 12:12:04.766  5594  5594 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-03 12:12:04.766  5594  5594 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-03 12:12:04.766  5594  5594 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-03 12:12:04.766  5594  5594 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-03 12:12:04.766  5594  5594 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-03 12:12:04.766  5594  5594 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-03 12:12:04.766  5594  5594 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,11-03 12:12:04.768  5594  5594 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,11-03 12:12:04.782   928  2977 D WifiConfigStore: loaded 0 passpoint configs
,11-03 12:12:04.783   928  2977 W WifiConfigStore: Upgrading network 4 to android.uid.system:1000
,11-03 12:12:04.784   928  2977 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,11-03 12:12:04.785   928  2977 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,11-03 12:12:04.785   928  2977 W WifiConfigStore: Upgrading network 3 to android.uid.system:1000
,11-03 12:12:04.786   928  2977 W WifiConfigStore: Upgrading network 2 to android.uid.system:1000
,11-03 12:12:04.787   928  2977 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,11-03 12:12:04.788   928  2977 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 5
11-03 12:12:04.788   928  2977 E WifiConfigStore: found sortedWifiConfigurations : "AndroidAP"WPA_PSK
11-03 12:12:04.788   928  2977 E WifiConfigStore: found sortedWifiConfigurations : "AndroidHotspot2346"WPA_PSK
11-03 12:12:04.788   928  2977 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
11-03 12:12:04.788   928  2977 E WifiConfigStore: found sortedWifiConfigurations : "Thali_internal"WPA_PSK
11-03 12:12:04.788   928  2977 E WifiConfigStore: found sortedWifiConfigurations : "MC"WPA_PSK
,11-03 12:12:04.792   928  2977 D WifiNative-HAL: Setting external_sim to 1
,11-03 12:12:04.792   928  2977 D wifi    : setting dfs flag to true, 0x7f5e77f840
11-03 12:12:04.792  4472  4472 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
11-03 12:12:04.792   928  2977 D WifiStateMachine: Setting OUI to DA-A1-19
11-03 12:12:04.792   928  2977 D wifi    : setting scan oui 0x7f5e77f840
11-03 12:12:04.792   928  2977 D WifiHAL : Sending mac address OUI
,11-03 12:12:04.796   928  2977 E native  : do suspend false
,11-03 12:12:04.802   928  2977 D wifi    : android_net_wifi_setLinkLayerStats: 1
11-03 12:12:04.802   928   928 D RttService: SCAN_AVAILABLE : 3
11-03 12:12:04.803   928  3098 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
11-03 12:12:04.803   508   921 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,11-03 12:12:04.804   508   921 D CommandListener: Setting iface cfg
,11-03 12:12:04.808   928  2976 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '132 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 132 Failed to set address (No such device)'
,11-03 12:12:04.808   928  2976 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,11-03 12:12:04.813   928   943 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=119585 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=6 mControllerEnergyUsed=22 }
,11-03 12:12:04.814   928  2976 D WifiNative-HAL: p2pGetDeviceAddress
,11-03 12:12:04.814   928  2976 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:70
,11-03 12:12:04.927  5594  5662 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-03 12:12:04.927  5594  5662 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-03 12:12:04.927  5594  5662 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-03 12:12:04.927  5594  5662 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-03 12:12:04.927  5594  5662 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-03 12:12:04.927  5594  5662 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-03 12:12:04.927  5594  5662 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-03 12:12:04.927  5594  5662 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,11-03 12:12:04.929  5594  5662 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,11-03 12:12:04.931  5594  5641 D BluetoothAdapter: enable(): BT is already enabled..!
,11-03 12:12:04.931   928  5737 D WifiService: setWifiEnabled: true pid=5594, uid=10077
11-03 12:12:04.931   928  5737 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
11-03 12:12:04.932  5594  5641 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-03 12:12:04.932  5594  5641 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,11-03 12:12:04.932  5594  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
11-03 12:12:04.932  5594  5641 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-03 12:12:04.932  5594  5641 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-03 12:12:04.932  5594  5641 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@930b15b removed from the list
11-03 12:12:04.932  5594  5641 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-03 12:12:04.933  5594  5641 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7276df8 removed from the list
,11-03 12:12:04.933  5594  5641 D io.jxcore.node.ConnectivityMonitor: stop
11-03 12:12:04.933  5594  5641 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-03 12:12:04.933  5594  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,11-03 12:12:04.935  5594  5641 I io.jxcore.node.IncomingSocketThreadTest: Starting test: testSetTcpPortNumber
11-03 12:12:04.937  5594  5641 I io.jxcore.node.IncomingSocketThreadTest: Starting test: testGetTcpPortNumber
,11-03 12:12:04.937  5594  5641 I io.jxcore.node.IncomingSocketThreadTest: Starting test: testGetLocalHostPort
,11-03 12:12:04.938  5594  5641 I io.jxcore.node.IncomingSocketThreadTest: Starting test: testConstructor
,11-03 12:12:04.940  5594  5641 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityCreated
,11-03 12:12:04.942  5594  5641 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,11-03 12:12:04.943  5594  5641 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityResumed
11-03 12:12:04.943  5594  5641 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
11-03 12:12:04.943  5594  5641 I io.jxcore.node.LifeCycleMonitorTest: Starting test: constructor
,11-03 12:12:04.945  5594  5641 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivitySaveInstanceState
,11-03 12:12:04.946  5594  5641 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@a9fdbfc Bundle[{}]
11-03 12:12:04.946  5594  5641 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testStartStop
11-03 12:12:04.946  5594  5641 I io.jxcore.node.LifeCycleMonitor: start: OK
11-03 12:12:04.947  5594  5641 I io.jxcore.node.LifeCycleMonitor: stop: OK
11-03 12:12:04.947  5594  5641 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityStarted
11-03 12:12:04.947  5594  5641 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
11-03 12:12:04.948  5594  5641 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityStopped
11-03 12:12:04.948  5594  5641 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,11-03 12:12:04.949  5594  5641 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityDestroyed
11-03 12:12:04.949  5594  5641 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
,11-03 12:12:04.950  5594  5641 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityPaused
,11-03 12:12:04.950  5594  5641 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,11-03 12:12:04.951  5594  5641 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testToString
,11-03 12:12:04.952  5594  5641 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testToJsonObject
,11-03 12:12:04.953  5594  5641 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testConstructorWithParameters
,11-03 12:12:04.953  5594  5641 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testSetListeningOnPortNumber
,11-03 12:12:04.954  5594  5641 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testGetListeningOnPortNumber
,11-03 12:12:04.955  5594  5641 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testDefaultConstructor
,11-03 12:12:04.956  5594  5641 I io.jxcore.node.OutgoingSocketThreadTest: Starting test: testClose
,11-03 12:12:04.956  5594  5641 I io.jxcore.node.OutgoingSocketThreadTest: Starting test: testGetListeningOnPortNumber
,11-03 12:12:04.957  5594  5641 I io.jxcore.node.OutgoingSocketThreadTest: Starting test: testConstructor
,11-03 12:12:04.958  5594  5641 I io.jxcore.node.SocketThreadBaseTest: Starting test: testGetListener
,11-03 12:12:04.959  5594  5641 I io.jxcore.node.SocketThreadBaseTest: Starting test: testSetPeerProperties
,11-03 12:12:04.959  5594  5641 I io.jxcore.node.SocketThreadBaseTest: Starting test: testClose
11-03 12:12:04.960  5594  5641 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 135)
,11-03 12:12:04.960  5594  5641 I io.jxcore.node.SocketThreadBaseTest: Starting test: testCloseLocalSocketAndStreams
11-03 12:12:04.960  5594  5641 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
11-03 12:12:04.960  5594  5641 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 136)
,11-03 12:12:04.961  5594  5641 I io.jxcore.node.SocketThreadBaseTest: Starting test: testGetPeerProperties
,11-03 12:12:04.962  5594  5641 I io.jxcore.node.SocketThreadBaseTest: Starting test: testEquals
,11-03 12:12:04.962  5594  5641 I io.jxcore.node.SocketThreadBaseTest: Starting test: testGetLocalHostAddressAsString
,11-03 12:12:04.963  5594  5641 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-03 12:12:04.963  5594  5641 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9f58b0d added. We now have 3 listener(s)
,11-03 12:12:04.965  5594  5641 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
,11-03 12:12:04.965  5594  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-03 12:12:04.965  5594  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-03 12:12:04.965  5594  5641 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-03 12:12:04.965  5594  5641 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6f85ac2 added. We now have 3 listener(s)
11-03 12:12:04.965  5594  5641 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-03 12:12:04.966  5594  5641 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,11-03 12:12:04.969  5594  5641 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,11-03 12:12:04.972  5594  5641 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-03 12:12:04.972  5594  5641 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-03 12:12:04.972  5594  5641 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-03 12:12:04.972  5594  5641 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-03 12:12:04.972  5594  5641 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-03 12:12:04.972  5594  5641 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-03 12:12:04.972  5594  5641 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-03 12:12:04.972  5594  5641 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,11-03 12:12:04.974  5594  5641 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
11-03 12:12:04.974  5594  5641 D io.jxcore.node.ConnectivityMonitor: start: OK
,11-03 12:12:04.975  5594  5594 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-03 12:12:04.976  5594  5641 I io.jxcore.node.StartStopOperationHandlerTest: Starting test: testCancelCurrentOperation
11-03 12:12:04.977  5594  5594 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-03 12:12:04.977  5594  5641 I io.jxcore.node.StartStopOperationHandlerTest: Starting test: testExecuteStopOperation
11-03 12:12:04.977  5594  5641 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 5
11-03 12:12:04.977  5594  5641 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 4 -> 5
11-03 12:12:04.977  5594  5641 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
11-03 12:12:04.977  5594  5641 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
11-03 12:12:04.978  5594  5641 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
11-03 12:12:04.978  5594  5641 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-03 12:12:04.978  5594  5641 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,11-03 12:12:04.978  5594  5641 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
11-03 12:12:04.978  5594  5641 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
11-03 12:12:04.978  5594  5641 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
11-03 12:12:04.979  5594  5641 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
11-03 12:12:04.979  5594  5641 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
,11-03 12:12:04.979  5594  5594 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
,11-03 12:12:04.979  5594  5641 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-03 12:12:04.979  5594  5641 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
11-03 12:12:04.979  5594  5866 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
11-03 12:12:04.979  5594  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-03 12:12:04.979  5594  5641 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-03 12:12:04.979  5594  5641 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
11-03 12:12:04.980  5594  5866 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-03 12:12:04.983  5594  5866 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,11-03 12:12:04.979  5820  5820 W Binder_2: type=1400 audit(0.0:119): avc: denied { ioctl } for path="socket:[31991]" dev="sockfs" ino=31991 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-03 12:12:04.979  5820  5820 W Binder_2: type=1400 audit(0.0:120): avc: denied { ioctl } for path="socket:[31991]" dev="sockfs" ino=31991 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-03 12:12:04.983  5594  5641 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-03 12:12:04.983  5594  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-03 12:12:04.983  5594  5641 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,11-03 12:12:04.985  5594  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Current thread: Thread[Thread-57,5,main], id: 57
,11-03 12:12:04.985  5594  5641 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
11-03 12:12:04.985  5594  5641 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-03 12:12:04.985  5594  5641 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 05 60 83 34 25 D7 D4
11-03 12:12:04.985  5594  5641 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[5, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-03 12:12:04.985  5594  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: Current thread: Thread[Thread-57,5,main], id: 57
11-03 12:12:04.986  5594  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData finished: Current thread: Thread[Thread-57,5,main], id: 57
11-03 12:12:04.986  5594  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = NOT_STARTEDCurrent thread: Thread[Thread-57,5,main], id: 57
11-03 12:12:04.986  5594  5641 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... adv data = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[5, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]Current thread: Thread[Thread-57,5,main], id: 57
11-03 12:12:04.986  5594  5641 D BluetoothAdapter: STATE_ON
11-03 12:12:04.988  5809  5849 D BtGatt.GattService: registerClient() - UUID=0bdd40ee-4c59-415e-8f12-9a73dfa5d2cc
11-03 12:12:04.989  5809  5825 D BtGatt.GattService: onClientRegistered() - UUID=0bdd40ee-4c59-415e-8f12-9a73dfa5d2cc, clientIf=6
,11-03 12:12:04.989  5594  5605 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
11-03 12:12:04.990  5809  5828 D BtGatt.AdvertiseManager: message : 0
,11-03 12:12:04.991  5809  5828 D BtGatt.AdvertiseManager: starting multi advertising
,11-03 12:12:04.993  5809  5825 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0
,11-03 12:12:04.995  5809  5825 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0
,11-03 12:12:04.995  5594  5641 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment Current thread: Thread[Thread-57,5,main], id: 57
,11-03 12:12:04.995  5594  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTINGCurrent thread: Thread[Thread-57,5,main], id: 57
11-03 12:12:04.996  5594  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
11-03 12:12:04.996  5594  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged default (no call to listener). Current thread: Thread[Thread-57,5,main], id: 57
11-03 12:12:04.996  5594  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finishedCurrent thread: Thread[Thread-57,5,main], id: 57
11-03 12:12:04.996  5594  5641 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[Thread-57,5,main], id: 57
11-03 12:12:04.996  5594  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[Thread-57,5,main], id: 57
11-03 12:12:04.996  5594  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser started = trueCurrent thread: Thread[Thread-57,5,main], id: 57
11-03 12:12:04.996  5594  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-03 12:12:04.997  5594  5641 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-03 12:12:04.997  5594  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
,11-03 12:12:04.998  5594  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
,11-03 12:12:04.998  5594  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
11-03 12:12:04.998  5594  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
11-03 12:12:04.998  5594  5594 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
11-03 12:12:04.998  5594  5594 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess : Current thread: Thread[main,5,main], id: 1
11-03 12:12:04.998  5594  5594 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNINGCurrent thread: Thread[main,5,main], id: 1
11-03 12:12:04.998  5594  5594 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
11-03 12:12:04.998  5594  5594 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged true. Current thread: Thread[main,5,main], id: 1
,11-03 12:12:04.998  5594  5594 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-03 12:12:04.999  5594  5594 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-03 12:12:04.999  5594  5594 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [ADVERTISING]
11-03 12:12:04.999  5594  5594 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-03 12:12:04.999  5594  5594 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-03 12:12:04.999  5594  5594 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]Current thread: Thread[main,5,main], id: 1
11-03 12:12:04.999  5594  5594 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
11-03 12:12:04.999  5594  5594 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-03 12:12:05.001  5594  5594 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-03 12:12:05.001  5594  5594 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
,11-03 12:12:05.001  5594  5594 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-03 12:12:05.001  5594  5594 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-03 12:12:05.001  5594  5594 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-03 12:12:05.001  5594  5594 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finishedCurrent thread: Thread[main,5,main], id: 1
11-03 12:12:05.001  5594  5594 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,11-03 12:12:05.093   545   545 I ServiceManager: Waiting for service AtCmdFwd...
,11-03 12:12:05.501  5594  5594 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
,11-03 12:12:05.501  5594  5594 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
11-03 12:12:05.501  5594  5594 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,11-03 12:12:06.093   545   545 I ServiceManager: Waiting for service AtCmdFwd...
,11-03 12:12:07.094   545   545 I ServiceManager: Waiting for service AtCmdFwd...
,11-03 12:12:08.095   545   545 I ServiceManager: Waiting for service AtCmdFwd...
,11-03 12:12:08.500  5594  5641 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
,11-03 12:12:08.500  5594  5641 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
11-03 12:12:08.500  5594  5641 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
11-03 12:12:08.500  5594  5641 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
,11-03 12:12:08.501  5594  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
11-03 12:12:08.501  5594  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 5 listener(s) left
11-03 12:12:08.501  5594  5866 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
11-03 12:12:08.501  5594  5641 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
,11-03 12:12:08.502  5594  5866 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
11-03 12:12:08.502  5594  5641 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
11-03 12:12:08.502  5594  5866 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
11-03 12:12:08.502  5594  5641 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,11-03 12:12:08.502  5594  5641 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-03 12:12:08.502  5594  5594 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
11-03 12:12:08.502  5594  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
11-03 12:12:08.502  5594  5641 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-03 12:12:08.503  5594  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-57,5,main], id: 57
,11-03 12:12:08.503  5594  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-57,5,main], id: 57
11-03 12:12:08.505  5594  5641 D BluetoothAdapter: STATE_ON
11-03 12:12:08.505  5594  5641 D BluetoothLeScanner: could not find callback wrapper
11-03 12:12:08.505  5594  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-03 12:12:08.505  5594  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-57,5,main], id: 57
11-03 12:12:08.506  5594  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-57,5,main], id: 57
11-03 12:12:08.506  5594  5641 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
11-03 12:12:08.506  5594  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-57,5,main], id: 57
11-03 12:12:08.508  5809  5828 D BtGatt.AdvertiseManager: message : 1
,11-03 12:12:08.509  5809  5828 D BtGatt.AdvertiseManager: stop advertise for client 6
,11-03 12:12:08.522  5809  5825 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
,11-03 12:12:08.522  5809  5825 D BtGatt.GattService: Client app is not null!
11-03 12:12:08.523  5809  5845 D BtGatt.GattService: unregisterClient() - clientIf=6
11-03 12:12:08.524  5594  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-03 12:12:08.524  5594  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTEDCurrent thread: Thread[Thread-57,5,main], id: 57
11-03 12:12:08.524  5594  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
11-03 12:12:08.525  5594  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged false. Current thread: Thread[Thread-57,5,main], id: 57
11-03 12:12:08.525  5594  5641 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: falseCurrent thread: Thread[Thread-57,5,main], id: 57
,11-03 12:12:08.525  5594  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[Thread-57,5,main], id: 57
11-03 12:12:08.525  5594  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
,11-03 12:12:08.525  5594  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [ADVERTISING]
11-03 12:12:08.525  5594  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[Thread-57,5,main], id: 57
11-03 12:12:08.526  5594  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]Current thread: Thread[Thread-57,5,main], id: 57
11-03 12:12:08.526  5594  5641 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
,11-03 12:12:08.526  5594  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
,11-03 12:12:08.529  5594  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
,11-03 12:12:08.530  5594  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-03 12:12:08.530  5594  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
,11-03 12:12:08.530  5594  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
11-03 12:12:08.530  5594  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[Thread-57,5,main], id: 57
,11-03 12:12:08.531  5594  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finishedCurrent thread: Thread[Thread-57,5,main], id: 57
11-03 12:12:08.531  5594  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-57,5,main], id: 57
,11-03 12:12:08.531  5594  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-03 12:12:08.532  5594  5641 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
11-03 12:12:08.532  5594  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
,11-03 12:12:08.532  5594  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
11-03 12:12:08.534  5594  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
11-03 12:12:08.535  5594  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
11-03 12:12:08.535  5594  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
11-03 12:12:08.535  5594  5594 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-03 12:12:08.535  5594  5594 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
11-03 12:12:08.535  5594  5594 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
11-03 12:12:08.535  5594  5594 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-03 12:12:08.536  5594  5594 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-03 12:12:08.536  5594  5594 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-03 12:12:08.536  5594  5594 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-03 12:12:08.538  5594  5641 I io.jxcore.node.StartStopOperationHandlerTest: Starting test: testCheckCurrentOperationStatus
,11-03 12:12:08.539  5594  5641 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-03 12:12:08.540  5594  5641 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-03 12:12:08.540  5594  5641 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
11-03 12:12:08.540  5594  5641 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
11-03 12:12:08.540  5594  5641 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-03 12:12:08.540  5594  5641 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,11-03 12:12:08.542  5594  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
,11-03 12:12:08.543  5594  5641 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-03 12:12:08.543  5594  5641 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,11-03 12:12:08.548  5594  5641 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,11-03 12:12:08.549  5594  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,11-03 12:12:08.549  5594  5641 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,11-03 12:12:08.555  5594  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-57,5,main], id: 57
,11-03 12:12:08.555  5594  5641 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
11-03 12:12:08.555  5594  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
11-03 12:12:08.555  5594  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
11-03 12:12:08.556  5594  5641 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
11-03 12:12:08.556  5594  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-57,5,main], id: 57
11-03 12:12:08.557  5594  5641 D BluetoothAdapter: STATE_ON
,11-03 12:12:08.561  5809  5819 D BtGatt.GattService: registerClient() - UUID=2a0eefdb-7c59-4a2b-843d-515c7ccdf0c2
,11-03 12:12:08.561  5809  5825 D BtGatt.GattService: onClientRegistered() - UUID=2a0eefdb-7c59-4a2b-843d-515c7ccdf0c2, clientIf=6
11-03 12:12:08.562  5594  5604 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,11-03 12:12:08.563  5809  5820 D BtGatt.GattService: start scan with filters
11-03 12:12:08.567  5594  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
,11-03 12:12:08.567  5594  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-57,5,main], id: 57
11-03 12:12:08.567  5809  5829 D BtGatt.ScanManager: handling starting scan
11-03 12:12:08.567  5594  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
11-03 12:12:08.568  5594  5641 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[Thread-57,5,main], id: 57
11-03 12:12:08.568  5594  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[Thread-57,5,main], id: 57
11-03 12:12:08.568  5594  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
,11-03 12:12:08.568  5594  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-03 12:12:08.569  5594  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[Thread-57,5,main], id: 57
11-03 12:12:08.569  5594  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[Thread-57,5,main], id: 57
11-03 12:12:08.569  5594  5641 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
11-03 12:12:08.569  5594  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
,11-03 12:12:08.571  5809  5829 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@498a2c9
,11-03 12:12:08.573  5594  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
,11-03 12:12:08.573  5594  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
11-03 12:12:08.573  5594  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
11-03 12:12:08.573  5594  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
11-03 12:12:08.573  5594  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[Thread-57,5,main], id: 57
,11-03 12:12:08.573  5594  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-03 12:12:08.573  5594  5594 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,11-03 12:12:08.575  5594  5641 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-03 12:12:08.575  5594  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
,11-03 12:12:08.579  5594  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
,11-03 12:12:08.579  5594  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
11-03 12:12:08.579  5594  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
11-03 12:12:08.580  5809  5825 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
,11-03 12:12:08.580  5809  5825 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
11-03 12:12:08.581  5809  5829 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,11-03 12:12:08.588  5809  5825 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=31
,11-03 12:12:08.588  5809  5825 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
11-03 12:12:08.588  5809  5829 D BtGatt.ScanManager: Starting BLE batch scan
11-03 12:12:08.589  5809  5829 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,11-03 12:12:08.601  5809  5825 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
,11-03 12:12:08.601  5809  5825 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,11-03 12:12:08.606  5809  5825 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
,11-03 12:12:08.607  5809  5825 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,11-03 12:12:09.074  5594  5594 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,11-03 12:12:09.075  5594  5594 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
11-03 12:12:09.075  5594  5594 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,11-03 12:12:09.096   545   545 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,11-03 12:12:11.582  5594  5641 I io.jxcore.node.StartStopOperationHandlerTest: Starting test: testExecuteStartOperation
,11-03 12:12:11.582  5594  5641 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 6
11-03 12:12:11.582  5594  5641 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 5 -> 6
11-03 12:12:11.583  5594  5641 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
11-03 12:12:11.583  5594  5641 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Manufacturer ID: 7413
11-03 12:12:11.583  5594  5641 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad length and type: 533
11-03 12:12:11.583  5594  5641 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad extra information: 6
11-03 12:12:11.583  5594  5641 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
11-03 12:12:11.583  5594  5641 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 2
11-03 12:12:11.583  5594  5641 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 3
11-03 12:12:11.583  5594  5641 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 2
11-03 12:12:11.583  5594  5641 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
11-03 12:12:11.583  5594  5641 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,11-03 12:12:11.583  5594  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-03 12:12:11.586  5594  5641 D BluetoothAdapter: STATE_ON
11-03 12:12:11.589  5809  5820 D BtGatt.GattService: stopScan() - queue size =1
,11-03 12:12:11.591  5809  5845 D BtGatt.GattService: unregisterClient() - clientIf=6
11-03 12:12:11.592  5594  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-03 12:12:11.593  5594  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-57,5,main], id: 57
11-03 12:12:11.593  5594  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
11-03 12:12:11.593  5594  5641 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-03 12:12:11.594  5594  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-57,5,main], id: 57
,11-03 12:12:11.594  5594  5641 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
11-03 12:12:11.594  5594  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
11-03 12:12:11.594  5594  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
11-03 12:12:11.595  5594  5641 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
11-03 12:12:11.595  5594  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-57,5,main], id: 57
,11-03 12:12:11.597  5594  5641 D BluetoothAdapter: STATE_ON
11-03 12:12:11.602  5809  5809 D BtGatt.ScanManager: awakened up at time 126374
11-03 12:12:11.606  5809  5845 D BtGatt.GattService: registerClient() - UUID=3af1d3b0-9a50-4f8f-9ace-208af3a2fe32
11-03 12:12:11.606  5809  5825 D BtGatt.GattService: onClientRegistered() - UUID=3af1d3b0-9a50-4f8f-9ace-208af3a2fe32, clientIf=6
,11-03 12:12:11.607  5594  5605 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,11-03 12:12:11.608  5809  5826 D BtGatt.GattService: start scan with filters
11-03 12:12:11.610  5809  5825 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=32
11-03 12:12:11.610  5809  5825 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
11-03 12:12:11.611  5809  5829 D BtGatt.ScanManager: stopping BLe Batch
,11-03 12:12:11.616  5594  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
11-03 12:12:11.616  5594  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-57,5,main], id: 57
11-03 12:12:11.616  5594  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
11-03 12:12:11.616  5594  5641 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[Thread-57,5,main], id: 57
11-03 12:12:11.616  5594  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[Thread-57,5,main], id: 57
11-03 12:12:11.617  5594  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
11-03 12:12:11.617  5594  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
11-03 12:12:11.617  5594  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[Thread-57,5,main], id: 57
11-03 12:12:11.617  5594  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[Thread-57,5,main], id: 57
11-03 12:12:11.617  5594  5641 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
,11-03 12:12:11.617  5594  5641 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
11-03 12:12:11.617  5594  5641 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
11-03 12:12:11.617  5594  5641 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-03 12:12:11.618  5594  5641 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
11-03 12:12:11.619  5809  5825 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
11-03 12:12:11.619  5809  5825 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
11-03 12:12:11.619  5809  5829 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
11-03 12:12:11.620  5594  5641 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
11-03 12:12:11.620  5594  5641 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
11-03 12:12:11.620  5594  5641 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
,11-03 12:12:11.620  5594  5641 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
11-03 12:12:11.621  5594  5870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
11-03 12:12:11.621  5594  5594 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
11-03 12:12:11.621  5594  5641 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: true
11-03 12:12:11.622  5594  5870 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-03 12:12:11.623  5594  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-03 12:12:11.623  5594  5641 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-03 12:12:11.626  5594  5870 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,11-03 12:12:11.622  5820  5820 W Binder_2: type=1400 audit(0.0:121): avc: denied { ioctl } for path="socket:[34031]" dev="sockfs" ino=34031 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-03 12:12:11.622  5820  5820 W Binder_2: type=1400 audit(0.0:122): avc: denied { ioctl } for path="socket:[34031]" dev="sockfs" ino=34031 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,11-03 12:12:11.633  5594  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser : Current thread: Thread[Thread-57,5,main], id: 57
11-03 12:12:11.633  5594  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Current thread: Thread[Thread-57,5,main], id: 57
,11-03 12:12:11.634  5594  5641 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
11-03 12:12:11.634  5594  5641 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-03 12:12:11.634  5594  5641 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 06 60 83 34 25 D7 D4
11-03 12:12:11.634  5594  5641 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[6, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-03 12:12:11.634  5594  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: Current thread: Thread[Thread-57,5,main], id: 57
11-03 12:12:11.634  5594  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData finished: Current thread: Thread[Thread-57,5,main], id: 57
11-03 12:12:11.635  5594  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = NOT_STARTEDCurrent thread: Thread[Thread-57,5,main], id: 57
11-03 12:12:11.635  5594  5641 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... adv data = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[6, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]Current thread: Thread[Thread-57,5,main], id: 57
,11-03 12:12:11.636  5594  5641 D BluetoothAdapter: STATE_ON
,11-03 12:12:11.641  5809  5849 D BtGatt.GattService: registerClient() - UUID=de0ec7e2-5422-4810-af56-31ee5602621e
,11-03 12:12:11.641  5809  5825 D BtGatt.GattService: onClientRegistered() - UUID=de0ec7e2-5422-4810-af56-31ee5602621e, clientIf=7
,11-03 12:12:11.642  5594  5604 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=7
11-03 12:12:11.643  5809  5828 D BtGatt.AdvertiseManager: message : 0
,11-03 12:12:11.645  5809  5825 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=6
11-03 12:12:11.645  5809  5825 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
11-03 12:12:11.645  5809  5825 D BtGatt.GattService: current time is 126418244993
11-03 12:12:11.646  5809  5825 D BtGatt.GattService: Batch record : [-52, 11, 57, -70, 107, -17, 1, 0, -100, 30, 0, 28, 2, 1, 6, 2, 10, 0, 3, 2, -25, -2, 17, 7, 28, -37, 54, 78, 111, 108, 127, 14, -112, 127, 124, -7, 58, 38, 64, 82, 20, 6, 9, 78, 97, 98, 117, 88, 12, -1, 1, 2, 1, 1, -106, -17, 107, -70, 57, 11, -52, -46, -4, -117, 6, 105, -37, 1, -128, -75, 55, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 116, -43, -111, -91, -20, -29, 1, -128, -81, 54, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 81, 34, 97, 112, -14, -5, 1, -128, -85, 29, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 71, -122, -77, 84, 69, -12, 1, -128, -85, 32, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 37, -47, 14, -113, 116, -46, 1, -128, -87, 30, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
11-03 12:12:11.648  5809  5829 D BtGatt.ScanManager: handling starting scan
,11-03 12:12:11.649  5809  5825 D BtGatt.GattService: ScanRecord : [2, 1, 6, 2, 10, 0, 3, 2, -25, -2, 17, 7, 28, -37, 54, 78, 111, 108, 127, 14, -112, 127, 124, -7, 58, 38, 64, 82, 6, 9, 78, 97, 98, 117, 88, 12, -1, 1, 2, 1, 1, -106, -17, 107, -70, 57, 11, -52]
11-03 12:12:11.649  5809  5828 D BtGatt.AdvertiseManager: starting multi advertising
11-03 12:12:11.650  5809  5825 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
11-03 12:12:11.650  5809  5825 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
11-03 12:12:11.650  5809  5825 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
,11-03 12:12:11.650  5809  5825 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
11-03 12:12:11.651  5809  5825 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,11-03 12:12:11.658  5809  5825 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
11-03 12:12:11.658  5809  5825 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
11-03 12:12:11.658  5809  5829 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,11-03 12:12:11.669  5809  5825 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=7, status=0
,11-03 12:12:11.674  5809  5825 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=31
,11-03 12:12:11.674  5809  5825 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
11-03 12:12:11.675  5809  5829 D BtGatt.ScanManager: Starting BLE batch scan
11-03 12:12:11.675  5809  5829 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,11-03 12:12:11.680  5809  5825 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=7, status=0
,11-03 12:12:11.681  5594  5641 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment Current thread: Thread[Thread-57,5,main], id: 57
,11-03 12:12:11.681  5594  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTINGCurrent thread: Thread[Thread-57,5,main], id: 57
11-03 12:12:11.681  5594  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
11-03 12:12:11.681  5594  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged default (no call to listener). Current thread: Thread[Thread-57,5,main], id: 57
11-03 12:12:11.681  5594  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finishedCurrent thread: Thread[Thread-57,5,main], id: 57
11-03 12:12:11.681  5594  5641 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[Thread-57,5,main], id: 57
11-03 12:12:11.681  5594  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[Thread-57,5,main], id: 57
11-03 12:12:11.681  5594  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser started = trueCurrent thread: Thread[Thread-57,5,main], id: 57
11-03 12:12:11.681  5594  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser: advertiser is started. Current thread: Thread[Thread-57,5,main], id: 57
11-03 12:12:11.681  5594  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-57,5,main], id: 57
11-03 12:12:11.682  5594  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-57,5,main], id: 57
,11-03 12:12:11.682  5594  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Already running
11-03 12:12:11.682  5594  5641 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser: adv = true, disc = true
11-03 12:12:11.682  5594  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-03 12:12:11.683  5594  5641 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-03 12:12:11.684  5594  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
,11-03 12:12:11.686  5594  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
11-03 12:12:11.687  5594  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
11-03 12:12:11.687  5594  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
11-03 12:12:11.687  5594  5594 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
11-03 12:12:11.687  5594  5594 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: onBatchScanResults: Current thread: Thread[main,5,main], id: 1
11-03 12:12:11.687  5594  5594 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: 
11-03 12:12:11.688  5594  5594 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: ScanResult{mDevice=FB:F2:70:61:22:51, mScanRecord=ScanRecord [mAdvertiseFlags=6, mServiceUuids=null, mManufacturerSpecificData={76=[2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74]}, mServiceData={0000180a-0000-1000-8000-00805f9b34fb=[81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]}, mTxPowerLevel=-2147483648, mDeviceName=estimote], mRssi=-85, mTimestampNanos=124968896501}
,11-03 12:12:11.688  5594  5594 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: 
11-03 12:12:11.689  5594  5594 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: ScanResult{mDevice=F4:45:54:B3:86:47, mScanRecord=ScanRecord [mAdvertiseFlags=6, mServiceUuids=null, mManufacturerSpecificData={76=[2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74]}, mServiceData={0000180a-0000-1000-8000-00805f9b34fb=[71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]}, mTxPowerLevel=-2147483648, mDeviceName=estimote], mRssi=-85, mTimestampNanos=124818896501}
11-03 12:12:11.689  5594  5594 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: 
11-03 12:12:11.689  5594  5594 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: ScanResult{mDevice=E3:EC:A5:91:D5:74, mScanRecord=ScanRecord [mAdvertiseFlags=6, mServiceUuids=null, mManufacturerSpecificData={76=[2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74]}, mServiceData={0000180a-0000-1000-8000-00805f9b34fb=[116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]}, mTxPowerLevel=-2147483648, mDeviceName=estimote], mRssi=-81, mTimestampNanos=123718896501}
11-03 12:12:11.689  5594  5594 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: 
11-03 12:12:11.690  5594  5594 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: ScanResult{mDevice=DB:69:06:8B:FC:D2, mScanRecord=ScanRecord [mAdvertiseFlags=6, mServiceUuids=null, mManufacturerSpecificData={76=[2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74]}, mServiceData={0000180a-0000-1000-8000-00805f9b34fb=[-46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]}, mTxPowerLevel=-2147483648, mDeviceName=estimote], mRssi=-75, mTimestampNanos=123668896501}
11-03 12:12:11.690  5594  5594 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: 
11-03 12:12:11.690  5594  5594 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: ScanResult{mDevice=EF:6B:BA:39:0B:CC, mScanRecord=ScanRecord [mAdvertiseFlags=6, mServiceUuids=[0000fee7-0000-1000-8000-00805f9b34fb, 5240263a-f97c-7f90-0e7f-6c6f4e36db1c], mManufacturerSpecificData={513=[1, 1, -106, -17, 107, -70, 57, 11, -52]}, mServiceData={}, mTxPowerLevel=0, mDeviceName=NabuX], mRssi=-100, mTimestampNanos=124918896501}
11-03 12:12:11.690  5594  5594 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: 
11-03 12:12:11.690  5594  5594 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: ScanResult{mDevice=D2:74:8F:0E:D1:25, mScanRecord=ScanRecord [mAdvertiseFlags=6, mServiceUuids=null, mManufacturerSpecificData={76=[2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74]}, mServiceData={0000180a-0000-1000-8000-00805f9b34fb=[37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]}, mTxPowerLevel=-2147483648, mDeviceName=estimote], mRssi=-87, mTimestampNanos=124918896501}
11-03 12:12:11.691  5594  5594 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess : Current thread: Thread[main,5,main], id: 1
11-03 12:12:11.691  5594  5594 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNINGCurrent thread: Thread[main,5,main], id: 1
,11-03 12:12:11.691  5594  5594 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
11-03 12:12:11.691  5594  5594 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged true. Current thread: Thread[main,5,main], id: 1
11-03 12:12:11.691  5594  5594 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-03 12:12:11.691  5594  5594 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-03 12:12:11.691  5594  5594 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING, ADVERTISING]
11-03 12:12:11.691  5594  5594 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
11-03 12:12:11.691  5594  5594 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-03 12:12:11.691  5594  5594 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [SCANNING, ADVERTISING]Current thread: Thread[main,5,main], id: 1
11-03 12:12:11.691  5594  5594 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [SCANNING, ADVERTISING]
11-03 12:12:11.691  5594  5594 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-03 12:12:11.693  5809  5825 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
11-03 12:12:11.694  5809  5825 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,11-03 12:12:11.695  5594  5594 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-03 12:12:11.695  5594  5594 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: true
11-03 12:12:11.695  5594  5594 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-03 12:12:11.695  5594  5594 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-03 12:12:11.695  5594  5594 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-03 12:12:11.695  5594  5594 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finishedCurrent thread: Thread[main,5,main], id: 1
11-03 12:12:11.695  5594  5594 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: true
,11-03 12:12:11.701  5809  5825 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
,11-03 12:12:11.701  5809  5825 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,11-03 12:12:12.196  5594  5594 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: true
,11-03 12:12:12.197  5594  5594 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
11-03 12:12:12.197  5594  5594 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,11-03 12:12:14.097   545   545 I ServiceManager: Waiting for service AtCmdFwd...
,11-03 12:12:14.107   928  2977 D WifiStateMachine: Disconnected CMD_START_SCAN source -2 7, 9 -> obsolete
,11-03 12:12:14.693  5594  5641 I io.jxcore.node.StartStopOperationHandlerTest: Starting test: testConstructor
,11-03 12:12:14.694  5594  5641 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-03 12:12:14.694  5594  5641 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
11-03 12:12:14.695  5594  5641 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
11-03 12:12:14.695  5594  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
,11-03 12:12:14.695  5594  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 5 listener(s) left
11-03 12:12:14.695  5594  5641 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
11-03 12:12:14.695  5594  5870 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
11-03 12:12:14.696  5594  5641 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
,11-03 12:12:14.696  5594  5870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
11-03 12:12:14.696  5594  5641 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-03 12:12:14.696  5594  5870 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
11-03 12:12:14.696  5594  5641 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9f58b0d removed from the list
,11-03 12:12:14.696  5594  5641 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-03 12:12:14.696  5594  5641 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-03 12:12:14.697  5594  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
11-03 12:12:14.697  5594  5594 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
11-03 12:12:14.697  5594  5641 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-03 12:12:14.697  5594  5594 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
11-03 12:12:14.697  5594  5594 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,11-03 12:12:14.697  5594  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-57,5,main], id: 57
11-03 12:12:14.697  5594  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-57,5,main], id: 57
11-03 12:12:14.698  5594  5641 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
11-03 12:12:14.701  5594  5641 D BluetoothAdapter: STATE_ON
,11-03 12:12:14.703  5809  5849 D BtGatt.GattService: stopScan() - queue size =1
11-03 12:12:14.704  5809  5845 D BtGatt.GattService: unregisterClient() - clientIf=6
11-03 12:12:14.705  5594  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,11-03 12:12:14.706  5594  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-57,5,main], id: 57
,11-03 12:12:14.706  5594  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
11-03 12:12:14.706  5594  5641 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[Thread-57,5,main], id: 57
11-03 12:12:14.706  5594  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[Thread-57,5,main], id: 57
11-03 12:12:14.707  5594  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [ADVERTISING]
11-03 12:12:14.707  5594  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING, ADVERTISING]
,11-03 12:12:14.707  5594  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[Thread-57,5,main], id: 57
11-03 12:12:14.707  5594  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING, ADVERTISING] to [ADVERTISING]Current thread: Thread[Thread-57,5,main], id: 57
11-03 12:12:14.707  5594  5641 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING, ADVERTISING] -> [ADVERTISING]
11-03 12:12:14.708  5594  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
11-03 12:12:14.709  5809  5809 D BtGatt.ScanManager: awakened up at time 129482
,11-03 12:12:14.714  5594  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
11-03 12:12:14.714  5594  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
,11-03 12:12:14.714  5594  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
11-03 12:12:14.714  5594  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
11-03 12:12:14.715  5594  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[Thread-57,5,main], id: 57
11-03 12:12:14.715  5594  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-57,5,main], id: 57
11-03 12:12:14.715  5594  5641 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
,11-03 12:12:14.715  5594  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-57,5,main], id: 57
11-03 12:12:14.716  5809  5828 D BtGatt.AdvertiseManager: message : 1
,11-03 12:12:14.717  5809  5825 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=32
,11-03 12:12:14.717  5809  5825 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
11-03 12:12:14.718  5809  5829 D BtGatt.ScanManager: stopping BLe Batch
11-03 12:12:14.718  5809  5828 D BtGatt.AdvertiseManager: stop advertise for client 7
,11-03 12:12:14.726  5809  5825 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
,11-03 12:12:14.727  5809  5825 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
11-03 12:12:14.727  5809  5829 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,11-03 12:12:14.736  5809  5825 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=7, status=0
11-03 12:12:14.736  5809  5825 D BtGatt.GattService: Client app is not null!
,11-03 12:12:14.737  5809  5826 D BtGatt.GattService: unregisterClient() - clientIf=7
,11-03 12:12:14.738  5594  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,11-03 12:12:14.738  5594  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTEDCurrent thread: Thread[Thread-57,5,main], id: 57
,11-03 12:12:14.738  5594  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
11-03 12:12:14.739  5594  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged false. Current thread: Thread[Thread-57,5,main], id: 57
11-03 12:12:14.739  5594  5641 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: falseCurrent thread: Thread[Thread-57,5,main], id: 57
11-03 12:12:14.739  5594  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[Thread-57,5,main], id: 57
11-03 12:12:14.739  5594  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-03 12:12:14.739  5594  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [ADVERTISING]
11-03 12:12:14.739  5594  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[Thread-57,5,main], id: 57
11-03 12:12:14.739  5594  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]Current thread: Thread[Thread-57,5,main], id: 57
,11-03 12:12:14.739  5594  5641 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
11-03 12:12:14.739  5594  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
11-03 12:12:14.741  5594  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
,11-03 12:12:14.741  5594  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,11-03 12:12:14.759  5594  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
,11-03 12:12:14.759  5594  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
11-03 12:12:14.759  5594  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[Thread-57,5,main], id: 57
11-03 12:12:14.759  5594  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finishedCurrent thread: Thread[Thread-57,5,main], id: 57
11-03 12:12:14.759  5594  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-57,5,main], id: 57
11-03 12:12:14.759  5594  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-03 12:12:14.759  5594  5641 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
11-03 12:12:14.759  5594  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
,11-03 12:12:14.760  5594  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
11-03 12:12:14.762  5594  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
11-03 12:12:14.762  5594  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
11-03 12:12:14.762  5594  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
11-03 12:12:14.762  5594  5641 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6f85ac2 removed from the list
,11-03 12:12:14.762  5594  5594 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-03 12:12:14.762  5594  5641 D io.jxcore.node.ConnectivityMonitor: stop
11-03 12:12:14.762  5594  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,11-03 12:12:14.762  5594  5594 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-03 12:12:14.762  5594  5594 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
11-03 12:12:14.762  5594  5594 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,11-03 12:12:14.764  5594  5641 I io.jxcore.node.StartStopOperationTest: Starting test: testIsTargetState
11-03 12:12:14.765  5594  5641 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
11-03 12:12:14.765  5594  5641 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
,11-03 12:12:14.765  5594  5641 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
11-03 12:12:14.765  5594  5641 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-03 12:12:14.765  5594  5641 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
11-03 12:12:14.765  5594  5641 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,11-03 12:12:14.766  5594  5641 I io.jxcore.node.StartStopOperationTest: Starting test: testCreateStartOperation
11-03 12:12:14.768  5594  5641 I io.jxcore.node.StartStopOperationTest: Starting test: testGetShouldStartOrStopListeningToAdvertisementsOnly
11-03 12:12:14.770  5594  5641 I io.jxcore.node.StartStopOperationTest: Starting test: testIsStartOperation
11-03 12:12:14.770  5594  5641 I io.jxcore.node.StartStopOperationTest: Starting test: testToString
,11-03 12:12:14.771  5594  5641 I io.jxcore.node.StartStopOperationTest: Starting test: testCreateStopOperation
11-03 12:12:14.772  5594  5641 I io.jxcore.node.StartStopOperationTest: Starting test: testSetOperationExecutedTime
11-03 12:12:14.773  5594  5641 I io.jxcore.node.StartStopOperationTest: Starting test: testGetOperationExecutedTime
11-03 12:12:14.774  5594  5641 I io.jxcore.node.StartStopOperationTest: Starting test: testGetCallback
,11-03 12:12:14.775  5809  5825 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=7
11-03 12:12:14.775  5809  5825 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
11-03 12:12:14.775  5809  5825 D BtGatt.GattService: current time is 129547732376
11-03 12:12:14.775  5809  5825 D BtGatt.GattService: Batch record : [71, -122, -77, 84, 69, -12, 1, -128, -83, 15, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 81, 34, 97, 112, -14, -5, 1, -128, -82, 16, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 37, -47, 14, -113, 116, -46, 1, -128, -86, 53, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 35, 97, 126, -92, 22, -56, 1, -128, -78, 48, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, -52, 11, 57, -70, 107, -17, 1, 0, -101, 47, 0, 28, 2, 1, 6, 2, 10, 0, 3, 2, -25, -2, 17, 7, 28, -37, 54, 78, 111, 108, 127, 14, -112, 127, 124, -7, 58, 38, 64, 82, 0, -46, -4, -117, 6, 105, -37, 1, -128, -76, 38, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 116, -43, -111, -91, -20, -29, 1, -128, -81, 37, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
11-03 12:12:14.775  5809  5825 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
11-03 12:12:14.776  5809  5825 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
11-03 12:12:14.776  5809  5825 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,11-03 12:12:14.776  5809  5825 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
11-03 12:12:14.776  5809  5825 D BtGatt.GattService: ScanRecord : [2, 1, 6, 2, 10, 0, 3, 2, -25, -2, 17, 7, 28, -37, 54, 78, 111, 108, 127, 14, -112, 127, 124, -7, 58, 38, 64, 82]
11-03 12:12:14.776  5809  5825 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
11-03 12:12:14.776  5809  5825 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,11-03 12:12:14.905   928  2977 D WifiStateMachine: Disconnected CMD_START_SCAN source -2 8, 9 -> obsolete
,11-03 12:12:15.098   545   545 I ServiceManager: Waiting for service AtCmdFwd...
,11-03 12:12:15.263  5594  5594 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-03 12:12:16.099   545   545 I ServiceManager: Waiting for service AtCmdFwd...
,11-03 12:12:16.779  5594  5641 I StreamCopyingThreadTest: Starting test: testCopyDataAndCloseConnection
,11-03 12:12:16.936  5594  5872 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 149, name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
11-03 12:12:16.936  5594  5872 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-03 12:12:17.100   545   545 I ServiceManager: Waiting for service AtCmdFwd...
,11-03 12:12:17.307   928  2977 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,11-03 12:12:17.308   928  2977 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3
,11-03 12:12:17.308   928  2977 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-03 12:12:17.319   928  2977 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=0
,11-03 12:12:17.351   928  2977 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=0
,11-03 12:12:17.357  5864  5864 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,11-03 12:12:17.736  5594  5872 W !!      : call onHalfStreamCopied
,11-03 12:12:17.736  5594  5872 I testCopyDataAndClose: closing input stream
,11-03 12:12:17.821  5864  5864 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,11-03 12:12:17.868  5864  5864 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,11-03 12:12:17.869  5864  5864 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,11-03 12:12:17.877   928  2977 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
11-03 12:12:17.878   928  2977 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
11-03 12:12:17.878   928  2985 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,11-03 12:12:17.893   928  2977 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-03 12:12:17.906   508   921 D CommandListener: Setting iface cfg
,11-03 12:12:17.910   928  2977 D WifiStateMachine: Start Dhcp Watchdog 2
,11-03 12:12:17.915   928  5876 D DhcpClient: Receive thread started
,11-03 12:12:17.919   928  2977 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,11-03 12:12:17.919   928  2985 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
11-03 12:12:17.920   928  2985 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
,11-03 12:12:17.999   928  2977 E native  : do suspend false
,11-03 12:12:18.008   928  5875 D DhcpClient: Broadcasting DHCPDISCOVER
,11-03 12:12:18.027   928  5876 D DhcpClient: Received packet: 60:83:34:25:d7:70 OFFER, ip /192.168.1.105, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172707, domain null
,11-03 12:12:18.028   928  5875 D DhcpClient: Got pending lease: IP address 192.168.1.105/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172707 seconds
,11-03 12:12:18.031   928  5875 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.105 serverid=192.168.1.1
,11-03 12:12:18.066   928  5876 D DhcpClient: Received packet: 60:83:34:25:d7:70 ACK: your new IP /192.168.1.105, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,11-03 12:12:18.067   928  5875 D DhcpClient: Confirmed lease: IP address 192.168.1.105/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,11-03 12:12:18.070   508   921 D CommandListener: Setting iface cfg
,11-03 12:12:18.076   928  2977 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,11-03 12:12:18.079   928  5875 D DhcpClient: Scheduling renewal in 86399s
,11-03 12:12:18.088   928  2977 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,11-03 12:12:18.089   928  2977 D WifiConfigStore: No blacklist allowed without epno enabled
,11-03 12:12:18.090   928  2985 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,11-03 12:12:18.093   928  2985 D ConnectivityService: Adding iface wlan0 to network 101
,11-03 12:12:18.098   928  2977 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
11-03 12:12:18.101   545   545 I ServiceManager: Waiting for service AtCmdFwd...
,11-03 12:12:18.142   928  2985 E ConnectivityService: Unexpected mtu value: 0, wlan0
,11-03 12:12:18.143   928  2985 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
,11-03 12:12:18.147   928  2985 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,11-03 12:12:18.151   928  2985 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,11-03 12:12:18.152   928  2985 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,11-03 12:12:18.160   928  2985 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-03 12:12:18.166   928  2985 D ConnectivityService: scheduleUnvalidatedPrompt 101
11-03 12:12:18.166   928  2985 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
,11-03 12:12:18.166   928  2985 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
11-03 12:12:18.166   928  2985 D ConnectivityService:    accepting network in place of null
11-03 12:12:18.166   928  2977 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
11-03 12:12:18.167   928  2977 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
11-03 12:12:18.167   928  2985 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d770/64,192.168.1.105/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -46]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,11-03 12:12:18.180   928  5874 D NetlinkSocketObserver: NeighborEvent{elapsedMs=132953, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,11-03 12:12:18.190   508   921 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-03 12:12:18.210   508   921 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-03 12:12:18.214   928  2985 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,11-03 12:12:18.215   928  2985 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
11-03 12:12:18.215  3735  3867 W QCNEJ   : |CORE| network available: 101
11-03 12:12:18.216   928  2985 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
11-03 12:12:18.217   928   945 D Tethering: MasterInitialState.processMessage what=3
11-03 12:12:18.220  3735  3867 W QCNEJ   : |CORE| onAvailable: bind the process to WIFI
11-03 12:12:18.222  3735  3867 W QCNEJ   : |CORE| newLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d770/64,192.168.1.105/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}
11-03 12:12:18.222  3735  3867 W QCNEJ   : |CORE| curLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d770/64,192.168.1.105/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
11-03 12:12:18.229  5594  5594 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-03 12:12:18.229  5594  5594 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-03 12:12:18.229  5594  5594 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-03 12:12:18.229  5594  5594 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-03 12:12:18.229  5594  5594 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-03 12:12:18.229  5594  5594 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-03 12:12:18.229  5594  5594 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-03 12:12:18.229  5594  5594 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,11-03 12:12:18.231  5594  5594 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
11-03 12:12:18.235  5594  5594 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-03 12:12:18.235  5594  5594 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-03 12:12:18.235  5594  5594 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-03 12:12:18.235  5594  5594 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-03 12:12:18.235  5594  5594 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-03 12:12:18.235  5594  5594 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-03 12:12:18.235  5594  5594 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-03 12:12:18.235  5594  5594 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
11-03 12:12:18.235  5038  5051 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
11-03 12:12:18.236  5038  5051 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
11-03 12:12:18.236  5038  5051 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,1,0,0
11-03 12:12:18.236  5038  5051 E SarControlService: no key has been found,reset the power
11-03 12:12:18.236  5038  5076 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
11-03 12:12:18.236  5038  5076 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
11-03 12:12:18.236  5038  5076 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
11-03 12:12:18.237  5064  5064 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
11-03 12:12:18.237  5064  5064 D QcrilMsgTunnelSocket: [1004] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
11-03 12:12:18.238  5594  5594 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,11-03 12:12:18.238  5038  5076 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
11-03 12:12:18.238  5038  5076 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
11-03 12:12:18.239  5038  5076 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
11-03 12:12:18.240  3979  3979 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
11-03 12:12:18.241  5064  5064 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
11-03 12:12:18.241  5064  5064 D QcrilMsgTunnelSocket: [1005] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
11-03 12:12:18.243  4074  4074 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,11-03 12:12:18.247  5064  5078 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@726b4b8 HexData = [00000000ec03000000000000ffffffff]
,11-03 12:12:18.247  5064  5078 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-03 12:12:18.247  5064  5078 D QcrilMsgTunnelSocket: [1004] < OEM_HOOK_RAW [null]
11-03 12:12:18.248  4074  4074 D SystemUpdateService: onCreate
11-03 12:12:18.249  5064  5078 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@726b4b8 HexData = [00000000ed03000000000000ffffffff]
11-03 12:12:18.249  5064  5078 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-03 12:12:18.249  5064  5078 D QcrilMsgTunnelSocket: [1005] < OEM_HOOK_RAW [null]
11-03 12:12:18.250  5064  5064 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
11-03 12:12:18.250  5038  5048 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
,11-03 12:12:18.252  5064  5064 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
11-03 12:12:18.252  5038  5049 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
,11-03 12:12:18.256  4074  4074 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,11-03 12:12:18.270  4074  4074 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,11-03 12:12:18.274  4074  5886 I SystemUpdateService: active receiver: enabled
,11-03 12:12:18.277  4074  5383 I iu.UploadsManager: num queued entries: 0
,11-03 12:12:18.277  4074  5383 I iu.UploadsManager: num updated entries: 0
,11-03 12:12:18.278  4074  5383 I iu.SyncManager: NEXT; no task
,11-03 12:12:18.280  4074  4074 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,11-03 12:12:18.282  4074  4074 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,11-03 12:12:18.286  5386  5386 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,11-03 12:12:18.289  5386  5386 D SprintDMHelper: simOperator: 
,11-03 12:12:18.290  5386  5386 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,11-03 12:12:18.298  4074  5886 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,11-03 12:12:18.301   928  5873 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.214.238,2a00:1450:400d:803::200e
,11-03 12:12:18.310  4074  5886 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,11-03 12:12:18.310  4074  5886 I SystemUpdateService: now status is 0 (complete)
11-03 12:12:18.310  4074  5886 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
11-03 12:12:18.310  4074  5886 I SystemUpdateService: file has been verified
11-03 12:12:18.311  4074  5886 I SystemUpdateService: OTA package size = 21989297
,11-03 12:12:18.327  4074  5886 I SystemUpdateService: showing system update notification
,11-03 12:12:18.333   928   928 V NotificationService: pkg=com.google.android.gms canInterrupt=false intercept=true
,11-03 12:12:18.334  4074  4074 D SystemUpdateService: onDestroy
,11-03 12:12:18.351   928  5873 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Thu, 03 Nov 2016 11:12:18 GMT], X-Android-Received-Millis=[1478171538350], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1478171538326]}
,11-03 12:12:18.351   928  2985 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,11-03 12:12:18.352   928  2985 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation  passed
11-03 12:12:18.352   928  2985 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
11-03 12:12:18.353   928  2985 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,11-03 12:12:18.388  4472  5891 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,11-03 12:12:18.493  5594  5872 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 149, thread name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
11-03 12:12:18.493  5594  5872 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-03 12:12:18.493  5594  5872 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
11-03 12:12:18.493  5594  5872 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
11-03 12:12:18.493  5594  5872 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
11-03 12:12:18.493  5594  5872 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
11-03 12:12:18.493  5594  5872 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
11-03 12:12:18.493  5594  5872 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
11-03 12:12:18.493  5594  5872 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
11-03 12:12:18.493  5594  5872 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 149, name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
11-03 12:12:18.493  5594  5872 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 20971520 and the total number of bytes written 20971520
,11-03 12:12:19.102   545   545 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,11-03 12:12:19.215   928  2985 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,11-03 12:12:19.814   928  2977 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 9, 10 -> obsolete
,11-03 12:12:20.636  3679  3855 I Keyboard.Facilitator.LanguageModelFlusher: run()
,11-03 12:12:20.636  3679  3855 I Keyboard.Facilitator: flushDynamicLanguageModels()
,11-03 12:12:20.672  3608  3608 I ConfigService: onCreate
,11-03 12:12:20.941   928  2985 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-03 12:12:22.853  5594  5641 I StreamCopyingThreadTest: Starting test: testRun
,11-03 12:12:22.857  5594  5899 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 152, name: My test thread name). Connection data: Peer properties: [null null].
11-03 12:12:22.857  5594  5899 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-03 12:12:24.883   928  2701 I hubconnection: sensorhub said: 'set_bias 3: -2.8800, 0.0000, 0.0000'
,11-03 12:12:25.718  3608  3608 I ConfigService: onDestroy
,11-03 12:12:26.173   928  2985 D ConnectivityService: handlePromptUnvalidated 101
,11-03 12:12:27.864  5594  5900 E StreamCopyingThreadTest: StreamCopyingThread didn't close after 5s!
,11-03 12:12:27.866  5594  5641 I StreamCopyingThreadTest: Starting test: testCopyBigData
,11-03 12:12:28.020  5594  5901 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 155, name: testCopyBigData thread). Connection data: Peer properties: [null null].
11-03 12:12:28.020  5594  5901 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-03 12:12:29.104   545   545 I ServiceManager: Waiting for service AtCmdFwd...
,11-03 12:12:29.662  5594  5901 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 155, thread name: testCopyBigData thread). Connection data: Peer properties: [null null].
11-03 12:12:29.662  5594  5901 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-03 12:12:29.662  5594  5901 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
11-03 12:12:29.662  5594  5901 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
11-03 12:12:29.662  5594  5901 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
11-03 12:12:29.662  5594  5901 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
11-03 12:12:29.662  5594  5901 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
11-03 12:12:29.662  5594  5901 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
,11-03 12:12:29.662  5594  5901 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
11-03 12:12:29.662  5594  5901 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 155, name: testCopyBigData thread). Connection data: Peer properties: [null null].
11-03 12:12:29.662  5594  5901 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 20971520 and the total number of bytes written 20971520
,11-03 12:12:30.105   545   545 I ServiceManager: Waiting for service AtCmdFwd...
,11-03 12:12:31.106   545   545 I ServiceManager: Waiting for service AtCmdFwd...
,11-03 12:12:32.108   545   545 I ServiceManager: Waiting for service AtCmdFwd...
,11-03 12:12:33.109   545   545 I ServiceManager: Waiting for service AtCmdFwd...
,11-03 12:12:33.888  5594  5641 I StreamCopyingThreadTest: Starting test: testRunNotify
,11-03 12:12:33.891  5594  5902 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 157, name: My test thread name). Connection data: Peer properties: [null null].
11-03 12:12:33.891  5594  5902 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-03 12:12:33.891  5594  5902 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 157, thread name: My test thread name). Connection data: Peer properties: [null null].
11-03 12:12:33.891  5594  5902 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
11-03 12:12:33.892  5594  5902 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
11-03 12:12:33.892  5594  5902 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
11-03 12:12:33.892  5594  5902 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
11-03 12:12:33.892  5594  5902 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
11-03 12:12:33.892  5594  5902 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
11-03 12:12:33.892  5594  5902 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
,11-03 12:12:33.892  5594  5902 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
11-03 12:12:33.892  5594  5902 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 157, name: My test thread name). Connection data: Peer properties: [null null].
11-03 12:12:33.892  5594  5902 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 22
11-03 12:12:33.894  5594  5641 I StreamCopyingThreadTest: Starting test: testSetBufferSize
11-03 12:12:33.894  5594  5641 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
11-03 12:12:33.895  5594  5641 I StreamCopyingThreadTest: Starting test: testRunWithException
,11-03 12:12:33.897  5594  5903 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 161, name: My test thread name). Connection data: Peer properties: [null null].
11-03 12:12:33.897  5594  5903 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
11-03 12:12:33.898  5594  5903 E io.jxcore.node.StreamCopyingThread: Failed to write to the output stream (thread ID: 161, thread name: My test thread name): Test exception.
11-03 12:12:33.898  5594  5903 D io.jxcore.node.StreamCopyingThread: onStreamCopyError (ID: 161, name: My test thread name). Connection data: Peer properties: [null null].
11-03 12:12:33.898  5594  5903 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
,11-03 12:12:33.898  5594  5903 D io.jxcore.node.StreamCopyingThread: number of bytes read = 22
11-03 12:12:33.899  5594  5903 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 161, name: My test thread name). Connection data: Peer properties: [null null].
11-03 12:12:33.899  5594  5903 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
11-03 12:12:33.900  5594  5641 E com.test.thalitest.ThaliTestRunner: testStart(io.jxcore.node.ConnectionHelperTest)
11-03 12:12:33.900  5594  5641 E com.test.thalitest.ThaliTestRunner: DiscoveryManager should be running
11-03 12:12:33.900  5594  5641 E com.test.thalitest.ThaliTestRunner: Expected: is <true>
11-03 12:12:33.900  5594  5641 E com.test.thalitest.ThaliTestRunner:      but: was <false>
11-03 12:12:33.901  5594  5641 E com.test.thalitest.ThaliTestRunner: java.lang.AssertionError: DiscoveryManager should be running
11-03 12:12:33.901  5594  5641 E com.test.thalitest.ThaliTestRunner: Expected: is <true>
11-03 12:12:33.901  5594  5641 E com.test.thalitest.ThaliTestRunner:      but: was <false>
11-03 12:12:33.901  5594  5641 E com.test.thalitest.ThaliTestRunner: 	at org.hamcrest.MatcherAssert.assertThat(MatcherAssert.java:20)
11-03 12:12:33.901  5594  5641 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.ConnectionHelperTest.testStart(ConnectionHelperTest.java:287)
11-03 12:12:33.901  5594  5641 E com.test.thalitest.ThaliTestRunner: 	at java.lang.reflect.Method.invoke(Native Method)
11-03 12:12:33.901  5594  5641 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.model.FrameworkMethod$1.runReflectiveCall(FrameworkMethod.java:50)
11-03 12:12:33.901  5594  5641 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.model.ReflectiveCallable.run(ReflectiveCallable.java:12)
11-03 12:12:33.901  5594  5641 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.model.FrameworkMethod.invokeExplosively(FrameworkMethod.java:47)
11-03 12:12:33.901  5594  5641 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.InvokeMethod.evaluate(InvokeMethod.java:17)
11-03 12:12:33.901  5594  5641 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.RunBefores.evaluate(RunBefores.java:26)
11-03 12:12:33.901  5594  5641 E com.test.thalitest.ThaliTestRunner: 	at org.junit.rules.ExpectedException$ExpectedExceptionStatement.evaluate(ExpectedException.java:239)
11-03 12:12:33.901  5594  5641 E com.test.thalitest.ThaliTestRunner: 	at org.junit.rules.TestWatcher$1.evaluate(TestWatcher.java:55)
11-03 12:12:33.901  5594  5641 E com.test.thalitest.ThaliTestRunner: 	at org.junit.rules.RunRules.evaluate(RunRules.java:20)
11-03 12:12:33.901  5594  5641 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runLeaf(ParentRunner.java:325)
11-03 12:12:33.901  5594  5641 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.BlockJUnit4ClassRunner.runChild(BlockJUnit4ClassRunner.java:78)
11-03 12:12:33.901  5594  5641 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.BlockJUnit4ClassRunner.runChild(BlockJUnit4ClassRunner.java:57)
11-03 12:12:33.901  5594  5641 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$3.run(ParentRunner.java:290)
11-03 12:12:33.901  5594  5641 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$1.schedule(ParentRunner.java:71)
11-03 12:12:33.901  5594  5641 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runChildren(ParentRunner.java:288)
11-03 12:12:33.901  5594  5641 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.access$000(ParentRunner.java:58)
11-03 12:12:33.901  5594  5641 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$2.evaluate(ParentRunner.java:268)
11-03 12:12:33.901  5594  5641 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.RunBefores.evaluate(RunBefore,s.java:26)
11-03 12:12:33.901  5594  5641 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.RunAfters.evaluate(RunAfters.java:27)
11-03 12:12:33.901  5594  5641 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.run(ParentRunner.java:363)
11-03 12:12:33.901  5594  5641 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:128)
11-03 12:12:33.901  5594  5641 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:27)
11-03 12:12:33.901  5594  5641 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$3.run(ParentRunner.java:290)
11-03 12:12:33.901  5594  5641 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$1.schedule(ParentRunner.java:71)
11-03 12:12:33.901  5594  5641 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runChildren(ParentRunner.java:288)
11-03 12:12:33.901  5594  5641 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.access$000(ParentRunner.java:58)
11-03 12:12:33.901  5594  5641 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$2.evaluate(ParentRunner.java:268)
11-03 12:12:33.901  5594  5641 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.run(ParentRunner.java:363)
11-03 12:12:33.901  5594  5641 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:128)
11-03 12:12:33.901  5594  5641 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:27)
11-03 12:12:33.901  5594  5641 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$3.run(ParentRunner.java:290)
11-03 12:12:33.901  5594  5641 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$1.schedule(ParentRunner.java:71)
11-03 12:12:33.901  5594  5641 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runChildren(ParentRunner.java:288)
11-03 12:12:33.901  5594  5641 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.access$000(ParentRunner.java:58)
11-03 12:12:33.901  5594  5641 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$2.evaluate(ParentRunner.java:268)
11-03 12:12:33.901  5594  5641 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.run(ParentRunner.java:363)
11-03 12:12:33.901  5594  5641 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.run(JUnitCore.java:137)
11-03 12:12:33.901  5594  5641 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.run(JUnitCore.java:115)
11-03 12:12:33.901  5594  5641 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.run(JUnitCore.java:105)
11-03 12:12:33.901  5594  5641 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.runClasses(JUnitCore.java:62)
11-03 12:12:33.901  5594  5641 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.runClasses(JUnitCore.java:49)
11-03 12:12:33.901  5594  5641 E com.test.thalitest.ThaliTestRunner: 	at com.test.thalitest.ThaliTestRunner.runTests(ThaliTestRunner.java:86)
11-03 12:12:33.901  5594  5641 E com.test.thalitest.ThaliTestRunner: 	at com.test.thalitest.RegisterExecuteUT$2.Receiver(RegisterExecuteUT.java:75)
11-03 12:12:33.901  5594  5641 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.jxcore.javaCall(jxcore.java:139)
11-03 12:12:33.901  5594  5641 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.jxcore.evalEngine(Native Method)
11-03 12:12:33.901  5594  5641 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.jxcore$4.run(jxcore.java:226)
11-03 12:12:33.901  5594  5641 E com.test.thalitest.ThaliTestRunner: 	at android.os.Handler.handleCallback(Handler.java:739)
11-03 12:12:33.901  5594  5641 E com.test.thalitest.ThaliTestRunner: 	at android.os.Handler.dispatchMessage(Handler.java:95)
11-03 12:12:33.901  5594  5641 E com.test.thalitest.ThaliTestRunner: 	at android.os.Looper.loop(Looper.java:148)
11-03 12:12:,33.901  5594  5641 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.CoreThread.run(CoreRunnable.java:56)
11-03 12:12:33.902  5594  5641 E com.test.thalitest.ThaliTestRunner: testStop(io.jxcore.node.ConnectionHelperTest)
11-03 12:12:33.902  5594  5641 E com.test.thalitest.ThaliTestRunner: DiscoveryManager should be running
11-03 12:12:33.902  5594  5641 E com.test.thalitest.ThaliTestRunner: Expected: is <true>
11-03 12:12:33.902  5594  5641 E com.test.thalitest.ThaliTestRunner:      but: was <false>
11-03 12:12:33.902  5594  5641 E com.test.thalitest.ThaliTestRunner: java.lang.AssertionError: DiscoveryManager should be running
11-03 12:12:33.902  5594  5641 E com.test.thalitest.ThaliTestRunner: Expected: is <true>
11-03 12:12:33.902  5594  5641 E com.test.thalitest.ThaliTestRunner:      but: was <false>
11-03 12:12:33.902  5594  5641 E com.test.thalitest.ThaliTestRunner: 	at org.hamcrest.MatcherAssert.assertThat(MatcherAssert.java:20)
11-03 12:12:33.902  5594  5641 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.ConnectionHelperTest.testStop(ConnectionHelperTest.java:315)
11-03 12:12:33.902  5594  5641 E com.test.thalitest.ThaliTestRunner: 	at java.lang.reflect.Method.invoke(Native Method)
11-03 12:12:33.902  5594  5641 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.model.FrameworkMethod$1.runReflectiveCall(FrameworkMethod.java:50)
11-03 12:12:33.902  5594  5641 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.model.ReflectiveCallable.run(ReflectiveCallable.java:12)
11-03 12:12:33.902  5594  5641 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.model.FrameworkMethod.invokeExplosively(FrameworkMethod.java:47)
11-03 12:12:33.902  5594  5641 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.InvokeMethod.evaluate(InvokeMethod.java:17)
11-03 12:12:33.902  5594  5641 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.RunBefores.evaluate(RunBefores.java:26)
11-03 12:12:33.902  5594  5641 E com.test.thalitest.ThaliTestRunner: 	at org.junit.rules.ExpectedException$ExpectedExceptionStatement.evaluate(ExpectedException.java:239)
11-03 12:12:33.902  5594  5641 E com.test.thalitest.ThaliTestRunner: 	at org.junit.rules.TestWatcher$1.evaluate(TestWatcher.java:55)
11-03 12:12:33.902  5594  5641 E com.test.thalitest.ThaliTestRunner: 	at org.junit.rules.RunRules.evaluate(RunRules.java:20)
11-03 12:12:33.902  5594  5641 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runLeaf(ParentRunner.java:325)
11-03 12:12:33.902  5594  5641 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.BlockJUnit4ClassRunner.runChild(BlockJUnit4ClassRunner.java:78)
11-03 12:12:33.902  5594  5641 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.BlockJUnit4ClassRunner.runChild(BlockJUnit4ClassRunner.java:57)
11-03 12:12:33.902  5594  5641 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$3.run(ParentRunner.java:290)
11-03 12:12:33.902  5594  5641 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$1.schedule(ParentRunner.java:71)
11-03 12:12:33.902  5594  5641 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runChildren(ParentRunner.java:288)
11-03 12:12:33.902  5594  5641 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.access$000(ParentRunner.java:58)
11-03 12:12:33.902  5594  5641 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$2.evaluate(ParentRunner.java:268)
11-03 12:12:33.902  5594  5641 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.RunBefores.evaluate(RunBefores.java:26)
11-03 12:12:33.902  5594  5641 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.RunAfters.evaluate(RunAfters.java:27)
11-03 12:12:33.902  5594  5641 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.run(ParentRunner.java:363)
11-03 12:12:33.902  5594  5641 E com.test.thalitest.ThaliTestRunner: 	at or,g.junit.runners.Suite.runChild(Suite.java:128)
11-03 12:12:33.902  5594  5641 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:27)
11-03 12:12:33.902  5594  5641 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$3.run(ParentRunner.java:290)
11-03 12:12:33.902  5594  5641 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$1.schedule(ParentRunner.java:71)
11-03 12:12:33.902  5594  5641 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runChildren(ParentRunner.java:288)
11-03 12:12:33.902  5594  5641 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.access$000(ParentRunner.java:58)
11-03 12:12:33.902  5594  5641 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$2.evaluate(ParentRunner.java:268)
11-03 12:12:33.902  5594  5641 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.run(ParentRunner.java:363)
11-03 12:12:33.902  5594  5641 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:128)
11-03 12:12:33.902  5594  5641 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:27)
11-03 12:12:33.902  5594  5641 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$3.run(ParentRunner.java:290)
11-03 12:12:33.902  5594  5641 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$1.schedule(ParentRunner.java:71)
11-03 12:12:33.902  5594  5641 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runChildren(ParentRunner.java:288)
11-03 12:12:33.902  5594  5641 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.access$000(ParentRunner.java:58)
11-03 12:12:33.902  5594  5641 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$2.evaluate(ParentRunner.java:268)
11-03 12:12:33.902  5594  5641 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.run(ParentRunner.java:363)
11-03 12:12:33.902  5594  5641 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.run(JUnitCore.java:137)
11-03 12:12:33.902  5594  5641 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.run(JUnitCore.java:115)
11-03 12:12:33.902  5594  5641 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.run(JUnitCore.java:105)
11-03 12:12:33.902  5594  5641 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.runClasses(JUnitCore.java:62)
11-03 12:12:33.902  5594  5641 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.runClasses(JUnitCore.java:49)
11-03 12:12:33.902  5594  5641 E com.test.thalitest.ThaliTestRunner: 	at com.test.thalitest.ThaliTestRunner.runTests(ThaliTestRunner.java:86)
11-03 12:12:33.902  5594  5641 E com.test.thalitest.ThaliTestRunner: 	at com.test.thalitest.RegisterExecuteUT$2.Receiver(RegisterExecuteUT.java:75)
11-03 12:12:33.902  5594  5641 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.jxcore.javaCall(jxcore.java:139)
11-03 12:12:33.902  5594  5641 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.jxcore.evalEngine(Native Method)
11-03 12:12:33.902  5594  5641 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.jxcore$4.run(jxcore.java:226)
11-03 12:12:33.902  5594  5641 E com.test.thalitest.ThaliTestRunner: 	at android.os.Handler.handleCallback(Handler.java:739)
11-03 12:12:33.902  5594  5641 E com.test.thalitest.ThaliTestRunner: 	at android.os.Handler.dispatchMessage(Handler.java:95)
11-03 12:12:33.902  5594  5641 E com.test.thalitest.ThaliTestRunner: 	at android.os.Looper.loop(Looper.java:148)
11-03 12:12:33.902  5594  5641 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.CoreThread.run(CoreRunnable.java:56)
11-03 12:12:33.902  5594  5641 E com.test.thalitest.ThaliTestRunner: testConnect(io.jxcore.node.ConnectionHelperTest)
11-03 12:12:33.902  5594  5641 E com.test.thalitest.ThaliTestRunner: 
11-03 12:12:33.902  5594  5641 E com.test.thalitest.ThaliTestRunn,er: Expected: is "We already have an outgoing connection to peer with ID 00:11:22:33:44:55"
11-03 12:12:33.902  5594  5641 E com.test.thalitest.ThaliTestRunner:      but: was "Already connect(ing/ed)"
11-03 12:12:33.903  5594  5641 E com.test.thalitest.ThaliTestRunner: java.lang.AssertionError: 
11-03 12:12:33.903  5594  5641 E com.test.thalitest.ThaliTestRunner: Expected: is "We already have an outgoing connection to peer with ID 00:11:22:33:44:55"
11-03 12:12:33.903  5594  5641 E com.test.thalitest.ThaliTestRunner:      but: was "Already connect(ing/ed)"
11-03 12:12:33.903  5594  5641 E com.test.thalitest.ThaliTestRunner: 	at org.hamcrest.MatcherAssert.assertThat(MatcherAssert.java:20)
11-03 12:12:33.903  5594  5641 E com.test.thalitest.ThaliTestRunner: 	at org.hamcrest.MatcherAssert.assertThat(MatcherAssert.java:8)
11-03 12:12:33.903  5594  5641 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.ConnectionHelperTest.testConnect(ConnectionHelperTest.java:551)
11-03 12:12:33.903  5594  5641 E com.test.thalitest.ThaliTestRunner: 	at java.lang.reflect.Method.invoke(Native Method)
11-03 12:12:33.903  5594  5641 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.model.FrameworkMethod$1.runReflectiveCall(FrameworkMethod.java:50)
11-03 12:12:33.903  5594  5641 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.model.ReflectiveCallable.run(ReflectiveCallable.java:12)
11-03 12:12:33.903  5594  5641 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.model.FrameworkMethod.invokeExplosively(FrameworkMethod.java:47)
11-03 12:12:33.903  5594  5641 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.InvokeMethod.evaluate(InvokeMethod.java:17)
11-03 12:12:33.903  5594  5641 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.RunBefores.evaluate(RunBefores.java:26)
11-03 12:12:33.903  5594  5641 E com.test.thalitest.ThaliTestRunner: 	at org.junit.rules.ExpectedException$ExpectedExceptionStatement.evaluate(ExpectedException.java:239)
11-03 12:12:33.903  5594  5641 E com.test.thalitest.ThaliTestRunner: 	at org.junit.rules.TestWatcher$1.evaluate(TestWatcher.java:55)
11-03 12:12:33.903  5594  5641 E com.test.thalitest.ThaliTestRunner: 	at org.junit.rules.RunRules.evaluate(RunRules.java:20)
11-03 12:12:33.903  5594  5641 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runLeaf(ParentRunner.java:325)
11-03 12:12:33.903  5594  5641 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.BlockJUnit4ClassRunner.runChild(BlockJUnit4ClassRunner.java:78)
11-03 12:12:33.903  5594  5641 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.BlockJUnit4ClassRunner.runChild(BlockJUnit4ClassRunner.java:57)
11-03 12:12:33.903  5594  5641 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$3.run(ParentRunner.java:290)
11-03 12:12:33.903  5594  5641 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$1.schedule(ParentRunner.java:71)
11-03 12:12:33.903  5594  5641 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runChildren(ParentRunner.java:288)
11-03 12:12:33.903  5594  5641 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.access$000(ParentRunner.java:58)
11-03 12:12:33.903  5594  5641 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$2.evaluate(ParentRunner.java:268)
11-03 12:12:33.903  5594  5641 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.RunBefores.evaluate(RunBefores.java:26)
11-03 12:12:33.903  5594  5641 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.RunAfters.evaluate(RunAfters.java:27)
11-03 12:12:33.903  5594  5641 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.run(ParentRunner.java:363)
11-03 12:12:33.903  5594  5641 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:128)
11-03 12:12:33.903  5594  5641 E com.test.thalitest.ThaliTestRunner: 	at org.,junit.runners.Suite.runChild(Suite.java:27)
11-03 12:12:33.903  5594  5641 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$3.run(ParentRunner.java:290)
11-03 12:12:33.903  5594  5641 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$1.schedule(ParentRunner.java:71)
11-03 12:12:33.903  5594  5641 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runChildren(ParentRunner.java:288)
11-03 12:12:33.903  5594  5641 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.access$000(ParentRunner.java:58)
11-03 12:12:33.903  5594  5641 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$2.evaluate(ParentRunner.java:268)
11-03 12:12:33.903  5594  5641 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.run(ParentRunner.java:363)
11-03 12:12:33.903  5594  5641 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:128)
11-03 12:12:33.903  5594  5641 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:27)
11-03 12:12:33.903  5594  5641 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$3.run(ParentRunner.java:290)
11-03 12:12:33.903  5594  5641 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$1.schedule(ParentRunner.java:71)
11-03 12:12:33.903  5594  5641 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runChildren(ParentRunner.java:288)
11-03 12:12:33.903  5594  5641 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.access$000(ParentRunner.java:58)
11-03 12:12:33.903  5594  5641 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$2.evaluate(ParentRunner.java:268)
11-03 12:12:33.903  5594  5641 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.run(ParentRunner.java:363)
11-03 12:12:33.903  5594  5641 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.run(JUnitCore.java:137)
11-03 12:12:33.903  5594  5641 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.run(JUnitCore.java:115)
11-03 12:12:33.903  5594  5641 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.run(JUnitCore.java:105)
11-03 12:12:33.903  5594  5641 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.runClasses(JUnitCore.java:62)
11-03 12:12:33.903  5594  5641 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.runClasses(JUnitCore.java:49)
11-03 12:12:33.903  5594  5641 E com.test.thalitest.ThaliTestRunner: 	at com.test.thalitest.ThaliTestRunner.runTests(ThaliTestRunner.java:86)
11-03 12:12:33.903  5594  5641 E com.test.thalitest.ThaliTestRunner: 	at com.test.thalitest.RegisterExecuteUT$2.Receiver(RegisterExecuteUT.java:75)
11-03 12:12:33.903  5594  5641 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.jxcore.javaCall(jxcore.java:139)
11-03 12:12:33.903  5594  5641 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.jxcore.evalEngine(Native Method)
11-03 12:12:33.903  5594  5641 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.jxcore$4.run(jxcore.java:226)
11-03 12:12:33.903  5594  5641 E com.test.thalitest.ThaliTestRunner: 	at android.os.Handler.handleCallback(Handler.java:739)
11-03 12:12:33.903  5594  5641 E com.test.thalitest.ThaliTestRunner: 	at android.os.Handler.dispatchMessage(Handler.java:95)
11-03 12:12:33.903  5594  5641 E com.test.thalitest.ThaliTestRunner: 	at android.os.Looper.loop(Looper.java:148)
11-03 12:12:33.903  5594  5641 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.CoreThread.run(CoreRunnable.java:56)
,11-03 12:12:33.903  5594  5641 E com.test.thalitest.ThaliTestRunner: testDispose(io.jxcore.node.ConnectionHelperTest)
11-03 12:12:33.903  5594  5641 E com.test.thalitest.ThaliTestRunner: DiscoveryManager should be running
11-03 12:12:33.903  5594  5641 E com.test.thalitest.ThaliTestRunner: Expected: is <true>
11-03 12:12:33.903  5594  5641 E com.test.thalitest.ThaliTestRunner:      but: was <false>
,11-03 12:12:33.904  5594  5641 E com.test.thalitest.ThaliTestRunner: java.lang.AssertionError: DiscoveryManager should be running
11-03 12:12:33.904  5594  5641 E com.test.thalitest.ThaliTestRunner: Expected: is <true>
11-03 12:12:33.904  5594  5641 E com.test.thalitest.ThaliTestRunner:      but: was <false>
11-03 12:12:33.904  5594  5641 E com.test.thalitest.ThaliTestRunner: 	,at org.hamcrest.MatcherAssert.assertThat(MatcherAssert.java:20)
11-03 12:12:33.904  5594  5641 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.ConnectionHelperTest.testDispose(ConnectionHelperTest.java:191)
11-03 12:12:33.904  5594  5641 E com.test.thalitest.ThaliTestRunner: 	at java.lang.reflect.Method.invoke(Native Method)
11-03 12:12:33.904  5594  5641 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.model.FrameworkMethod$1.runReflectiveCall(FrameworkMethod.java:50)
11-03 12:12:33.904  5594  5641 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.model.ReflectiveCallable.run(ReflectiveCallable.java:12)
11-03 12:12:33.904  5594  5641 E com.test.thalitest.ThaliTestRunner: 	,at org.junit.runners.model.FrameworkMethod.invokeExplosively(FrameworkMethod.java:47)
11-03 12:12:33.904  5594  5641 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.InvokeMethod.evaluate(InvokeMethod.java:17)
11-03 12:12:33.904  5594  5641 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.RunBefores.evaluate(RunBefores.java:26)
11-03 12:12:33.904  5594  5641 E com.test.thalitest.ThaliTestRunner: 	at org.junit.rules.ExpectedException$ExpectedExceptionStatement.evaluate(ExpectedException.java:239)
11-03 12:12:33.904  5594  5641 E com.test.thalitest.ThaliTestRunner: 	at org.junit.rules.TestWatcher$1.evaluate(TestWatcher.java:55)
11-03 12:12:33.904  5594  5641 E com.test.thalitest.ThaliTestRunner: 	at org.junit.rules.RunRules.evaluate(RunRules.java:20)
11-03 12:12:33.904  5594  5641 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runLeaf(ParentRunner.java:325)
11-03 12:12:33.904  5594  5641 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.BlockJUnit4ClassRunner.runChild(BlockJUnit4ClassRunner.java:78)
11-03 12:12:33.904  5594  5641 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.BlockJUnit4ClassRunner.runChild(BlockJUnit4ClassRunner.java:57)
11-03 12:12:33.904  5594  5641 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$3.run(ParentRunner.java:290)
11-03 12:12:33.904  5594  5641 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$1.schedule(ParentRunner.java:71)
11-03 12:12:33.904  5594  5641 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runChildren(ParentRunner.java:288)
11-03 12:12:33.904  5594  5641 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.access$000(ParentRunner.java:58)
11-03 12:12:33.904  5594  5641 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$2.evaluate(ParentRunner.java:268)
11-03 12:12:33.904  5594  5641 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.RunBefores.evaluate(RunBefores.java:26)
11-03 12:12:33.904  5594  5641 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.RunAfters.evaluate(RunAfters.java:27)
11-03 12:12:33.904  5594  5641 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.run(ParentRunner.java:363)
11-03 12:12:33.904  5594  5641 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:128)
11-03 12:12:33.904  5594  5641 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:27)
11-03 12:12:33.904  5594  5641 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$3.run(ParentRunner.java:290)
11-03 12:12:33.904  5594  5641 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$1.schedule(ParentRunner.java:71)
11-03 12:12:33.904  5594  5641 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runChildren(ParentRunner.java:288)
11-03 12:12:33.904  5594  5641 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.access$000(ParentRunner.java:58)
11-03 12:12:33.904  5594  5641 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$2.evaluate(ParentRunner.java:268)
11-03 12:12:33.904  5594  5641 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.run(ParentRunner.java:363)
11-03 12:12:33.904  5594  5641 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:128)
11-03 12:12:33.904  5594  5641 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:27)
11-03 12:12:33.904  5594  5641 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$3.run(ParentRunner.java:290)
11-03 12:12:33.904  5594  5641 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$1.schedule(ParentRunner.java:71)
11-03 12:12:33.904  5594  5641 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runChildren,(ParentRunner.java:288)
11-03 12:12:33.904  5594  5641 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.access$000(ParentRunner.java:58)
11-03 12:12:33.904  5594  5641 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$2.evaluate(ParentRunner.java:268)
11-03 12:12:33.904  5594  5641 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.run(ParentRunner.java:363)
11-03 12:12:33.904  5594  5641 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.run(JUnitCore.java:137)
11-03 12:12:33.904  5594  5641 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.run(JUnitCore.java:115)
11-03 12:12:33.904  5594  5641 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.run(JUnitCore.java:105)
11-03 12:12:33.904  5594  5641 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.runClasses(JUnitCore.java:62)
11-03 12:12:33.904  5594  5641 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.runClasses(JUnitCore.java:49)
11-03 12:12:33.904  5594  5641 E com.test.thalitest.ThaliTestRunner: 	at com.test.thalitest.ThaliTestRunner.runTests(ThaliTestRunner.java:86)
11-03 12:12:33.904  5594  5641 E com.test.thalitest.ThaliTestRunner: 	at com.test.thalitest.RegisterExecuteUT$2.Receiver(RegisterExecuteUT.java:75)
11-03 12:12:33.904  5594  5641 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.jxcore.javaCall(jxcore.java:139)
11-03 12:12:33.904  5594  5641 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.jxcore.evalEngine(Native Method)
11-03 12:12:33.904  5594  5641 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.jxcore$4.run(jxcore.java:226)
11-03 12:12:33.904  5594  5641 E com.test.thalitest.ThaliTestRunner: 	at android.os.Handler.handleCallback(Handler.java:739)
11-03 12:12:33.904  5594  5641 E com.test.thalitest.ThaliTestRunner: 	at android.os.Handler.dispatchMessage(Handler.java:95)
11-03 12:12:33.904  5594  5641 E com.test.thalitest.ThaliTestRunner: 	at android.os.Looper.loop(Looper.java:148)
11-03 12:12:33.904  5594  5641 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.CoreThread.run(CoreRunnable.java:56)
11-03 12:12:33.904  5594  5641 E com.test.thalitest.ThaliTestRunner: testIsRunning(io.jxcore.node.ConnectionHelperTest)
11-03 12:12:33.904  5594  5641 E com.test.thalitest.ThaliTestRunner: ConnectionManager state is different than NOT_STARTED
11-03 12:12:33.904  5594  5641 E com.test.thalitest.ThaliTestRunner: Expected: is not <NOT_STARTED>
11-03 12:12:33.904  5594  5641 E com.test.thalitest.ThaliTestRunner:      but: was <NOT_STARTED>
11-03 12:12:33.905  5594  5641 E com.test.thalitest.ThaliTestRunner: java.lang.AssertionError: ConnectionManager state is different than NOT_STARTED
11-03 12:12:33.905  5594  5641 E com.test.thalitest.ThaliTestRunner: Expected: is not <NOT_STARTED>
11-03 12:12:33.905  5594  5641 E com.test.thalitest.ThaliTestRunner:      but: was <NOT_STARTED>
11-03 12:12:33.905  5594  5641 E com.test.thalitest.ThaliTestRunner: 	at org.hamcrest.MatcherAssert.assertThat(MatcherAssert.java:20)
11-03 12:12:33.905  5594  5641 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.ConnectionHelperTest.testIsRunning(ConnectionHelperTest.java:413)
11-03 12:12:33.905  5594  5641 E com.test.thalitest.ThaliTestRunner: 	at java.lang.reflect.Method.invoke(Native Method)
11-03 12:12:33.905  5594  5641 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.model.FrameworkMethod$1.runReflectiveCall(FrameworkMethod.java:50)
11-03 12:12:33.905  5594  5641 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.model.ReflectiveCallable.run(ReflectiveCallable.java:12)
11-03 12:12:33.905  5594  5641 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.model.FrameworkMethod.invokeExplosively(FrameworkMethod.java:47)
11-03 12:12:33.905  5594  5641 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.InvokeMethod.evaluate(InvokeMethod.java:17)
11-03 12:12:33.905  5594  5641 E com.test.th,alitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.RunBefores.evaluate(RunBefores.java:26)
11-03 12:12:33.905  5594  5641 E com.test.thalitest.ThaliTestRunner: 	at org.junit.rules.ExpectedException$ExpectedExceptionStatement.evaluate(ExpectedException.java:239)
11-03 12:12:33.905  5594  5641 E com.test.thalitest.ThaliTestRunner: 	at org.junit.rules.TestWatcher$1.evaluate(TestWatcher.java:55)
11-03 12:12:33.905  5594  5641 E com.test.thalitest.ThaliTestRunner: 	at org.junit.rules.RunRules.evaluate(RunRules.java:20)
11-03 12:12:33.905  5594  5641 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runLeaf(ParentRunner.java:325)
11-03 12:12:33.905  5594  5641 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.BlockJUnit4ClassRunner.runChild(BlockJUnit4ClassRunner.java:78)
11-03 12:12:33.905  5594  5641 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.BlockJUnit4ClassRunner.runChild(BlockJUnit4ClassRunner.java:57)
11-03 12:12:33.905  5594  5641 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$3.run(ParentRunner.java:290)
11-03 12:12:33.905  5594  5641 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$1.schedule(ParentRunner.java:71)
11-03 12:12:33.905  5594  5641 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runChildren(ParentRunner.java:288)
11-03 12:12:33.905  5594  5641 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.access$000(ParentRunner.java:58)
11-03 12:12:33.905  5594  5641 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$2.evaluate(ParentRunner.java:268)
11-03 12:12:33.905  5594  5641 E com.test.thalitest.ThaliTestRunner: ,	at org.junit.internal.runners.statements.RunBefores.evaluate(RunBefores.java:26)
11-03 12:12:33.905  5594  5641 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.RunAfters.evaluate(RunAfters.java:27)
11-03 12:12:33.905  5594  5641 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.run(ParentRunner.java:363)
11-03 12:12:33.905  5594  5641 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:128)
11-03 12:12:33.905  5594  5641 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:27)
11-03 12:12:33.905  5594  5641 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$3.run(ParentRunner.java:290)
11-03 12:12:33.905  5594  5641 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$1.schedule(ParentRunner.java:71)
11-03 12:12:33.905  5594  5641 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runChildren(ParentRunner.java:288)
11-03 12:12:33.905  5594  5641 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.access$000(ParentRunner.java:58)
11-03 12:12:33.905  5594  5641 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$2.evaluate(ParentRunner.java:268)
11-03 12:12:33.905  5594  5641 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.run(ParentRunner.java:363)
11-03 12:12:33.905  5594  5641 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:128)
11-03 12:12:33.905  5594  5641 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:27)
11-03 12:12:33.905  5594  5641 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$3.run(ParentRunner.java:290)
11-03 12:12:33.905  5594  5641 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$1.schedule(ParentRunner.java:71)
11-03 12:12:33.905  5594  5641 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runChildren(ParentRunner.java:288)
11-03 12:12:33.905  5594  5641 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.access$000(ParentRunner.java:58)
11-03 12:12:33.905  5594  5641 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$2.evaluate(ParentRunner.java:268)
11-03 12:12:33.905  5594  5641 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.run(ParentRunner.java:363)
11-03 12:12:33.905  5594  5641 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.run(JUnitCore.java:137)
11-03 12:12:33.905  5594  5641 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.run(JUnitCore.java:115)
11-03 12:12:33.905  5594  5641 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.run(JUnitCore.java:105)
11-03 12:12:33.905  5594  5641 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.runClasses(JUnitCore.java:62)
11-03 12:12:33.905  5594  5641 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.runClasses(JUnitCore.java:49)
11-03 12:12:33.905  5594  5641 E com.test.thalitest.ThaliTestRunner: 	at com.test.thalitest.ThaliTestRunner.runTests(ThaliTestRunner.java:86)
11-03 12:12:33.905  5594  5641 E com.test.thalitest.ThaliTestRunner: 	at com.test.thalitest.RegisterExecuteUT$2.Receiver(RegisterExecuteUT.java:75)
11-03 12:12:33.905  5594  5641 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.jxcore.javaCall(jxcore.java:139)
11-03 12:12:33.905  5594  5641 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.jxcore.evalEngine(Native Method)
11-03 12:12:33.905  5594  5641 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.jxcore$4.run(jxcore.java:226)
11-03 12:12:33.905  5594  5641 E com.test.thalitest.ThaliTestRunner: 	at android.os.Handler.handleCallback(Handler.java:739)
11-03 12:12:33.905  5594  5641 E com.test.thalitest.ThaliTestRunner: 	at android.os.Handler.dispatchMessage(Handler.java:95)
11-03 12:12:33.905  5594  5641 E com.test.thalitest.Tha,liTestRunner: 	at android.os.Looper.loop(Looper.java:148)
11-03 12:12:33.905  5594  5641 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.CoreThread.run(CoreRunnable.java:56)
11-03 12:12:33.905  5594  5641 E com.test.thalitest.ThaliTestRunner: testRun(io.jxcore.node.StreamCopyingThreadTest)
11-03 12:12:33.905  5594  5641 E com.test.thalitest.ThaliTestRunner: StreamCopyingThread should be closed
11-03 12:12:33.905  5594  5641 E com.test.thalitest.ThaliTestRunner: Expected: is <true>
11-03 12:12:33.905  5594  5641 E com.test.thalitest.ThaliTestRunner:      but: was <false>
11-03 12:12:33.905  5594  5641 E com.test.thalitest.ThaliTestRunner: java.lang.AssertionError: StreamCopyingThread should be closed
11-03 12:12:33.905  5594  5641 E com.test.thalitest.ThaliTestRunner: Expected: is <true>
11-03 12:12:33.905  5594  5641 E com.test.thalitest.ThaliTestRunner:      but: was <false>
11-03 12:12:33.905  5594  5641 E com.test.thalitest.ThaliTestRunner: 	at org.hamcrest.MatcherAssert.assertThat(MatcherAssert.java:20)
11-03 12:12:33.905  5594  5641 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.StreamCopyingThreadTest.testRun(StreamCopyingThreadTest.java:152)
11-03 12:12:33.905  5594  5641 E com.test.thalitest.ThaliTestRunner: 	at java.lang.reflect.Method.invoke(Native Method)
11-03 12:12:33.905  5594  5641 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.model.FrameworkMethod$1.runReflectiveCall(FrameworkMethod.java:50)
11-03 12:12:33.905  5594  5641 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.model.ReflectiveCallable.run(ReflectiveCallable.java:12)
11-03 12:12:33.905  5594  5641 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.model.FrameworkMethod.invokeExplosively(FrameworkMethod.java:47)
11-03 12:12:33.905  5594  5641 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.InvokeMethod.evaluate(InvokeMethod.java:17)
11-03 12:12:33.905  5594  5641 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.RunBefores.evaluate(RunBefores.java:26)
11-03 12:12:33.905  5594  5641 E com.test.thalitest.ThaliTestRunner: 	at org.junit.rules.ExpectedException$ExpectedExceptionStatement.evaluate(ExpectedException.java:239)
11-03 12:12:33.905  5594  5641 E com.test.thalitest.ThaliTestRunner: 	at org.junit.rules.TestWatcher$1.evaluate(TestWatcher.java:55)
11-03 12:12:33.905  5594  5641 E com.test.thalitest.ThaliTestRunner: 	at org.junit.rules.RunRules.evaluate(RunRules.java:20)
11-03 12:12:33.905  5594  5641 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runLeaf(ParentRunner.java:325)
11-03 12:12:33.905  5594  5641 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.BlockJUnit4ClassRunner.runChild(BlockJUnit4ClassRunner.java:78)
11-03 12:12:33.905  5594  5641 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.BlockJUnit4ClassRunner.runChild(BlockJUnit4ClassRunner.java:57)
11-03 12:12:33.905  5594  5641 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$3.run(ParentRunner.java:290)
11-03 12:12:33.905  5594  5641 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$1.schedule(ParentRunner.java:71)
11-03 12:12:33.905  5594  5641 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runChildren(ParentRunner.java:288)
11-03 12:12:33.905  5594  5641 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.access$000(ParentRunner.java:58)
11-03 12:12:33.905  5594  5641 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$2.evaluate(ParentRunner.java:268)
11-03 12:12:33.905  5594  5641 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.run(ParentRunner.java:363)
11-03 12:12:33.905  5594  5641 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:128)
11-03 12:12:33.905  5594  5641 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:27)
11-03 12:12:33.905  5594  5641 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$3.run(ParentRunner.java:290)
11-03 12:12:33.905  5594  5641 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$1.schedule(ParentRunner.java:71)
11-03 12:12:33.905  5594  5641 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runChildren(ParentRunner.java:288)
11-03 12:12:33.905  5594  5641 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.access$000(ParentRunner.java:58)
11-03 12:12:33.905  5594  5641 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$2.evaluate(ParentRunner.java:268)
11-03 12:12:33.905  5594  5641 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.run(ParentRunner.java:363)
11-03 12:12:33.905  5594  5641 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:128)
11-03 12:12:33.905  5594  5641 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:27)
11-03 12:12:33.905  5594  5641 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$3.run(ParentRunner.java:290)
11-03 12:12:33.905  5594  5641 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$1.schedule(ParentRunner.java:71)
11-03 12:12:33.905  5594  5641 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runChildren(ParentRunner.java:288)
11-03 12:12:33.905  5594  5641 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.access$000(ParentRunner.java:58)
11-03 12:12:33.905  5594  5641 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$2.evaluate(ParentRunner.java:268)
11-03 12:12:33.905  5594  5641 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.run(ParentRunner.java:363)
11-03 12:12:33.905  5594  5641 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.run(JUnitCore.java:137)
11-03 12:12:33.905  5594  5641 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.run(JUnitCore.java:115)
11-03 12:12:33.905  5594  5641 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.run(JUnitCore.java:105)
11-03 12:12:33.905  5594  5641 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.runClasses(JUnitCore.java:62)
11-03 12:12:33.905  5594  5641 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.runClasses(JUnitCore.java:49)
11-03 12:12:33.905  5594  5641 E com.test.thalitest.ThaliTestRunner: 	at com.test.thalitest.ThaliTestRunner.runTests(ThaliTestRunner.java:86)
11-03 12:12:33.905  5594  5641 E com.test.thalitest.ThaliTestRunner: 	at com.test.thalitest.RegisterExecuteUT$2.Receiver(RegisterExecuteUT.java:75)
11-03 12:12:33.905  5594  5641 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.jxcore.javaCall(jxcore.java:139)
11-03 12:12:33.905  5594  5641 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.jxcore.evalEngine(Native Method)
11-03 12:12:33.905  5594  5641 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.jxcore$4.run(jxcore.java:226)
11-03 12:12:33.905  5594  5641 E com.test.thalitest.ThaliTestRunner: 	at android.os.Handler.handleCallback(Handler.java:739)
11-03 12:12:33.905  5594  5641 E com.test.thalitest.ThaliTestRunner: 	at android.os.Handler.dispatchMessage(Handler.java:95)
11-03 12:12:33.905  5594  5641 E com.test.thalitest.ThaliTestRunner: 	at android.os.Looper.loop(Looper.java:148)
11-03 12:12:33.905  5594  5641 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.CoreThread.run(CoreRunnable.java:56)
11-03 12:12:33.909  5594  5641 I jxcore-log: 2016-11-03 11:12:33 - DEBUG UnitTest_app: 'Running unit tests'
11-03 12:12:33.909  5594  5641 I jxcore-log: 
11-03 12:12:33.909  5594  5641 I jxcore-log: *Native tests were executed*
11-03 12:12:33.909  5594  5641 I jxcore-log: 
11-03 12:12:33.909  5594  5641 I jxcore-log: Total number of executed tests:  82
11-03 12:12:33.909  5594  5641 I jxcore-log: 
11-03 12:12:33.909  5594  5641 I jxcore-log: Number of passed tests:  76
11-03 12:12:33.909  5594  5641 I jxcore-log: 
11-03 12:12:33.909  5594  5641 I jxcore-log: Number of failed tests:  6
11-03 12:12:33.909  5594  5641 I jxcore-log: 
11-03 12:12:33.909  5594  5641 I jxcore-log: Number of ignored tests:  0
11-03 12:12:33.909  5594  5641 I jxcore-log: 
11-03 12:12:33.910  5594  5641 I jxcore-log: Total duration:  52013
11-03 12:12:33.910  5594  5641 I jxcore-log: 
11-03 12:12:33.910  5594  5641 I jxcore-log: Failed to execute UT.
11-03 12:12:33.910  5594  5641 I jxcore-log: 
11-03 12:12:33.911  5594  5641 I jxcore-log: 2016-11-03 11:12:33 - DEBUG UnitTest_app: 'Failed to execute UT.'
11-03 12:12:33.911  5594  5641 I jxcore-log: 
11-03 12:12:33.913  5594  5641 I jxcore-log: 2016-11-03 11:12:33 - DEBUG UnitTest_app: 'Unit Test app is loaded'
11-03 12:12:33.913  5594  5641 I jxcore-log: 
11-03 12:12:33.917  5594  5641 I jxcore-log: 2016-11-03 11:12:33 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
11-03 12:12:33.917  5594  5641 I jxcore-log: 
11-03 12:12:33.918  5594  5641 I jxcore-log: 2016-11-03 11:12:33 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-03 12:12:33.918  5594  5641 I jxcore-log: 
11-03 12:12:33.919  5594  5641 I jxcore-log: 2016-11-03 11:12:33 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
11-03 12:12:33.919  5594  5641 I jxcore-log: 
11-03 12:12:33.920  5594  5641 I jxcore-log: 2016-11-03 11:12:33 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-03 12:12:33.920  5594  5641 I jxcore-log: 
11-03 12:12:33.920  5594  5641 I jxcore-log: 2016-11-03 11:12:33 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
11-03 12:12:33.920  5594  5641 I jxcore-log: 
11-03 12:12:33.920  5594  5641 I jxcore-log: 2016-11-03 11:12:33 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-03 12:12:33.920  5594  5641 I jxcore-log: 
11-03 12:12:33.921  5594  5641 I jxcore-log: 2016-11-03 11:12:33 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
11-03 12:12:33.921  5594  5641 I jxcore-log: 
11-03 12:12:33.921  5594  5641 I jxcore-log: 2016-11-03 11:12:33 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-03 12:12:33.921  5594  5641 I jxcore-log: 
11-03 12:12:33.922  5594  5641 I jxcore-log: 2016-11-03 11:12:33 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
11-03 12:12:33.922  5594  5641 I jxcore-log: 
11-03 12:12:33.922  5594  5641 I jxcore-log: 2016-11-03 11:12:33 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-03 12:12:33.922  5594  5641 I jxcore-log: 
11-03 12:12:33.922  5594  5641 I jxcore-log: 2016-11-03 11:12:33 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
11-03 12:12:33.922  5594  5641 I jxcore-log: 
11-03 12:12:33.922  5594  5641 I jxcore-log: 2016-11-03 11:12:33 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-03 12:12:33.922  5594  5641 I jxcore-log: 
11-03 12:12:33.922  5594  5641 I jxcore-log: 2016-11-03 11:12:33 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
11-03 12:12:33.922  5594  5641 I jxcore-log: 
11-03 12:12:33.923  5594  5641 I jxcore-log: 2016-11-03 11:12:33 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-03 12:12:33.923  5594  5641 I jxcore-log: 
11-03 12:12:33.923  5594  5641 I jxcore-log: 2016-11-03 11:12:33 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
11-03 12:12:33.923  5594  5641 I jxcore-log: 
11-03 12:12:33.923  5594  5641 I jxcore-log: 2016-11-03 11:12:33 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-03 12:12:33.923  5594  5641 I jxcore-log: 
11-03 12:12:33.923  5594  5641 I jxcore-log: 2016-11-03 11:12:33 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
11-03 12:12:33.923  5594  5641 I jxcore-log: 
11-03 12:12:33.923  5594  5641 I jxcore-log: 2016-11-03 11:12:33 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-03 12:12:33.923  5594  5641 I jxcore-log: 
11-03 12:12:33.924  5594  5641 I jxcore-log: 2016-11-03 11:12:33 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
11-03 12:12:33.924  5594  5641 I jxcore-log: 
11-03 12:12:33.924  5594  5641 I jxcore-log: 2016-11-03 11:12:33 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-03 12:12:33.924  5594  5641 I jxcore-log: 
11-03 12:12:33.924  5594  5641 I jxcore-log: 2016-11-03 11:12:33 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
11-03 12:12:33.924  5594  5641 I jxcore-log: 
11-03 12:12:33.924  5594  5641 I jxcore-log: 2016-11-03 11:12:33 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-03 12:12:33.924  5594  5641 I jxcore-log: 
11-03 12:12:33.925  5594  5641 I jxcore-log: 2016-11-03 11:12:33 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
11-03 12:12:33.925  5594  5641 I jxcore-log: 
11-03 12:12:33.925  5594  5641 I jxcore-log: 2016-11-03 11:12:33 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-03 12:12:33.925  5594  5641 I jxcore-log: 
11-03 12:12:33.925  5594  5641 I jxcore-log: 2016-11-03 11:12:33 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
11-03 12:12:33.925  5594  5641 I jxcore-log: 
11-03 12:12:33.925  5594  5641 I jxcore-log: 2016-11-03 11:12:33 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-03 12:12:33.925  5594  5641 I jxcore-log: 
11-03 12:12:33.925  5594  5641 I jxcore-log: 2016-11-03 11:12:33 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
11-03 12:12:33.925  5594  5641 I jxcore-log: 
11-03 12:12:33.925  5594  5641 I jxcore-log: 2016-11-03 11:12:33 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-03 12:12:33.925  5594  5641 I jxcore-log: 
11-03 12:12:33.926  5594  5641 I jxcore-log: 2016-11-03 11:12:33 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-03 12:12:33.926  5594  5641 I jxcore-log: 
11-03 12:12:33.927  5594  5641 I jxcore-log: 2016-11-03 11:12:33 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
11-03 12:12:33.927  5594  5641 I jxcore-log: 
11-03 12:12:33.927  5594  5641 I jxcore-log: 2016-11-03 11:12:33 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-03 12:12:33.927  5594  5641 I jxcore-log: 
11-03 12:12:33.928  5594  5641 I jxcore-log: 2016-11-03 11:12:33 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
11-03 12:12:33.928  5594  5641 I jxcore-log: 
11-03 12:12:33.928  5594  5641 I jxcore-log: 2016-11-03 11:12:33 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-03 12:12:33.928  5594  5641 I jxcore-log: 
11-03 12:12:33.928  5594  5641 I jxcore-log: 2016-11-03 11:12:33 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
11-03 12:12:33.928  5594  5641 I jxcore-log: 
11-03 12:12:33.928  5594  5641 I jxcore-log: 2016-11-03 11:12:33 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-03 12:12:33.928  5594  5641 I jxcore-log: 
11-03 12:12:33.928  5594  5641 I jxcore-log: 2016-11-03 11:12:33 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
11-03 12:12:33.928  5594  5641 I jxcore-log: 
11-03 12:12:33.929  5594  5641 I jxcore-log: 2016-11-03 11:12:33 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-03 12:12:33.929  5594  5641 I jxcore-log: 
11-03 12:12:33.929  5594  5641 I jxcore-log: 2016-11-03 11:12:33 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
11-03 12:12:33.929  5594  5641 I jxcore-log: 
11-03 12:12:33.929  5594  5641 I jxcore-log: 2016-11-03 11:12:33 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-03 12:12:33.929  5594  5641 I jxcore-log: 
11-03 12:12:33.929  5594  5641 I jxcore-log: 2016-11-03 11:12:33 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
11-03 12:12:33.929  5594  5641 I jxcore-log: 
11-03 12:12:33.929  5594  5641 I jxcore-log: 2016-11-03 11:12:33 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-03 12:12:33.929  5594  5641 I jxcore-log: 
11-03 12:12:33.930  5594  5641 I jxcore-log: 2016-11-03 11:12:33 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-03 12:12:33.930  5594  5641 I jxcore-log: 
11-03 12:12:33.930  5594  5641 I jxcore-log: 2016-11-03 11:12:33 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
11-03 12:12:33.930  5594  5641 I jxcore-log: 
11-03 12:12:33.930  5594  5641 I jxcore-log: 2016-11-03 11:12:33 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-03 12:12:33.930  5594  5641 I jxcore-log: 
11-03 12:12:33.930  5594  5641 I jxcore-log: 2016-11-03 11:12:33 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
11-03 12:12:33.930  5594  5641 I jxcore-log: 
11-03 12:12:33.930  5594  5641 I jxcore-log: 2016-11-03 11:12:33 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-03 12:12:33.930  5594  5641 I jxcore-log: 
11-03 12:12:33.931  5594  5641 I jxcore-log: 2016-11-03 11:12:33 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
11-03 12:12:33.931  5594  5641 I jxcore-log: 
11-03 12:12:33.931  5594  5641 I jxcore-log: 2016-11-03 11:12:33 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-03 12:12:33.931  5594  5641 I jxcore-log: 
11-03 12:12:33.931  5594  5641 I jxcore-log: 2016-11-03 11:12:33 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
11-03 12:12:33.931  5594  5641 I jxcore-log: 
11-03 12:12:33.931  5594  5641 I jxcore-log: 2016-11-03 11:12:33 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-03 12:12:33.931  5594  5641 I jxcore-log: 
11-03 12:12:33.931  5594  5641 I jxcore-log: 2016-11-03 11:12:33 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
11-03 12:12:33.931  5594  5641 I jxcore-log: 
11-03 12:12:33.931  5594  5641 I jxcore-log: 2016-11-03 11:12:33 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-03 12:12:33.931  5594  5641 I jxcore-log: 
11-03 12:12:33.932  5594  5641 I jxcore-log: 2016-11-03 11:12:33 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
11-03 12:12:33.932  5594  5641 I jxcore-log: 
11-03 12:12:33.932  5594  5641 I jxcore-log: 2016-11-03 11:12:33 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-03 12:12:33.932  5594  5641 I jxcore-log: 
11-03 12:12:33.932  5594  5641 I jxcore-log: 2016-11-03 11:12:33 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
11-03 12:12:33.932  5594  5641 I jxcore-log: 
11-03 12:12:33.932  5594  5641 I jxcore-log: 2016-11-03 11:12:33 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
11-03 12:12:33.932  5594  5641 I jxcore-log: 
11-03 12:12:33.932  5594  5641 I jxcore-log: 2016-11-03 11:12:33 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-03 12:12:33.932  5594  5641 I jxcore-log: 
11-03 12:12:33.933  5594  5641 I jxcore-log: 2016-11-03 11:12:33 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
11-03 12:12:33.933  5594  5641 I jxcore-log: 
11-03 12:12:33.933  5594  5641 I jxcore-log: 2016-11-03 11:12:33 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-03 12:12:33.933  5594  5641 I jxcore-log: 
11-03 12:12:33.933  5594  5641 I jxcore-log: 2016-11-03 11:12:33 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
11-03 12:12:33.933  5594  5641 I jxcore-log: 
11-03 12:12:33.933  5594  5641 I jxcore-log: 2016-11-03 11:12:33 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-03 12:12:33.933  5594  5641 I jxcore-log: 
11-03 12:12:33.933  5594  5641 I jxcore-log: 2016-11-03 11:12:33 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
11-03 12:12:33.933  5594  5641 I jxcore-log: 
11-03 12:12:33.934  5594  5641 I jxcore-log: 2016-11-03 11:12:33 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-03 12:12:33.934  5594  5641 I jxcore-log: 
11-03 12:12:33.934  5594  5641 I jxcore-log: 2016-11-03 11:12:33 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
11-03 12:12:33.934  5594  5641 I jxcore-log: 
11-03 12:12:33.934  5594  5641 I jxcore-log: 2016-11-03 11:12:33 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
11-03 12:12:33.934  5594  5641 I jxcore-log: 
11-03 12:12:33.934  5594  5641 I jxcore-log: 2016-11-03 11:12:33 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
11-03 12:12:33.934  5594  5641 I jxcore-log: 
11-03 12:12:33.934  5594  5641 I jxcore-log: 2016-11-03 11:12:33 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-03 12:12:33.934  5594  5641 I jxcore-log: 
11-03 12:12:33.935  5594  5641 I jxcore-log: 2016-11-03 11:12:33 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
11-03 12:12:33.935  5594  5641 I jxcore-log: 
11-03 12:12:33.935  5594  5641 I jxcore-log: 2016-11-03 11:12:33 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-03 12:12:33.935  5594  5641 I jxcore-log: 
11-03 12:12:33.935  5594  5641 I jxcore-log: 2016-11-03 11:12:33 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
11-03 12:12:33.935  5594  5641 I jxcore-log: 
11-03 12:12:33.935  5594  5641 I jxcore-log: 2016-11-03 11:12:33 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-03 12:12:33.935  5594  5641 I jxcore-log: 
11-03 12:12:33.937  5594  5594 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
11-03 12:12:33.940  5594  5641 I jxcore-log: 2016-11-03 11:12:33 - DEBUG UnitTest_app: 'My device name is: Huawei-Nexus 6P'
11-03 12:12:33.940  5594  5641 I jxcore-log: 
11-03 12:12:33.940  5594  5641 I jxcore-log: 2016-11-03 11:12:33 - WARN testUtils: 'myNameCallback not set!'
11-03 12:12:33.940  5594  5641 I jxcore-log: 
11-03 12:12:33.941  5594  5641 E JX-Cordova: jxcore.CallJSMethod :{"isFulfilled":false,"isRejected":false}
11-03 12:12:33.942  5594  5641 I jxcore-log: 2016-11-03 11:12:33 - DEBUG UnitTest_app: 'Running for NATIVE network type'
11-03 12:12:33.942  5594  5641 I jxcore-log: 
,11-03 12:12:34.110   545   545 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,11-03 12:12:35.943  5594  5641 I jxcore-log: 2016-11-03 11:12:35 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js'
11-03 12:12:35.943  5594  5641 I jxcore-log: 
,11-03 12:12:36.269  5594  5641 I jxcore-log: 2016-11-03 11:12:36 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js'
11-03 12:12:36.269  5594  5641 I jxcore-log: 
,11-03 12:12:36.283  5594  5641 I jxcore-log: 2016-11-03 11:12:36 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManager.js'
11-03 12:12:36.283  5594  5641 I jxcore-log: 
,11-03 12:12:37.365  5594  5641 I jxcore-log: 2016-11-03 11:12:37 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js'
11-03 12:12:37.365  5594  5641 I jxcore-log: 
,11-03 12:12:37.536  5594  5641 I jxcore-log: 2016-11-03 11:12:37 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js'
11-03 12:12:37.536  5594  5641 I jxcore-log: 
,11-03 12:12:37.541  5594  5641 I jxcore-log: 2016-11-03 11:12:37 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testNativeMethod.js'
11-03 12:12:37.541  5594  5641 I jxcore-log: 
,11-03 12:12:37.546  5594  5641 I jxcore-log: 2016-11-03 11:12:37 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPouchDBCheckpointPlugin.js'
11-03 12:12:37.546  5594  5641 I jxcore-log: 
,11-03 12:12:38.025  5594  5641 I jxcore-log: 2016-11-03 11:12:38 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPouchDBGenerator.js'
11-03 12:12:38.025  5594  5641 I jxcore-log: 
,11-03 12:12:38.067  5594  5641 I jxcore-log: 2016-11-03 11:12:38 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js'
11-03 12:12:38.067  5594  5641 I jxcore-log: 
,11-03 12:12:38.081  5594  5641 I jxcore-log: 2016-11-03 11:12:38 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js'
11-03 12:12:38.081  5594  5641 I jxcore-log: 
,11-03 12:12:38.085  5594  5641 I jxcore-log: 2016-11-03 11:12:38 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliManager.js'
11-03 12:12:38.085  5594  5641 I jxcore-log: 
,11-03 12:12:38.365  5594  5641 I jxcore-log: 2016-11-03 11:12:38 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliManagerCoordinated.js'
11-03 12:12:38.365  5594  5641 I jxcore-log: 
,11-03 12:12:38.503  5594  5641 I jxcore-log: 2016-11-03 11:12:38 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js'
11-03 12:12:38.503  5594  5641 I jxcore-log: 
,11-03 12:12:38.870  5594  5641 I jxcore-log: 2016-11-03 11:12:38 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js'
11-03 12:12:38.870  5594  5641 I jxcore-log: 
,11-03 12:12:38.904  5594  5641 I jxcore-log: 2016-11-03 11:12:38 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeAndroid.js'
11-03 12:12:38.904  5594  5641 I jxcore-log: 
,11-03 12:12:38.911  5594  5641 I jxcore-log: 2016-11-03 11:12:38 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeDiscoveryCoordinated.js'
11-03 12:12:38.911  5594  5641 I jxcore-log: 
,11-03 12:12:38.916  5594  5641 I jxcore-log: 2016-11-03 11:12:38 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js'
11-03 12:12:38.916  5594  5641 I jxcore-log: 
,11-03 12:12:38.923  5594  5641 I jxcore-log: 2016-11-03 11:12:38 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeiOS.js'
11-03 12:12:38.923  5594  5641 I jxcore-log: 
,11-03 12:12:38.936  5594  5641 I jxcore-log: 2016-11-03 11:12:38 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js'
11-03 12:12:38.936  5594  5641 I jxcore-log: 
,11-03 12:12:38.942  5594  5641 I jxcore-log: 2016-11-03 11:12:38 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js'
11-03 12:12:38.942  5594  5641 I jxcore-log: 
,11-03 12:12:38.970  5594  5641 I jxcore-log: 2016-11-03 11:12:38 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js'
11-03 12:12:38.970  5594  5641 I jxcore-log: 
,11-03 12:12:39.008  5594  5641 I jxcore-log: 2016-11-03 11:12:39 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js'
11-03 12:12:39.008  5594  5641 I jxcore-log: 
,11-03 12:12:39.015  5594  5641 I jxcore-log: 2016-11-03 11:12:39 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationLocal.js'
11-03 12:12:39.015  5594  5641 I jxcore-log: 
,11-03 12:12:39.021  5594  5641 I jxcore-log: 2016-11-03 11:12:39 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js'
11-03 12:12:39.021  5594  5641 I jxcore-log: 
,11-03 12:12:39.036  5594  5641 I jxcore-log: 2016-11-03 11:12:39 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js'
11-03 12:12:39.036  5594  5641 I jxcore-log: 
,11-03 12:12:39.041  5594  5641 I jxcore-log: 2016-11-03 11:12:39 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js'
11-03 12:12:39.041  5594  5641 I jxcore-log: 
,11-03 12:12:39.046  5594  5641 I jxcore-log: 2016-11-03 11:12:39 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolDefault.js'
11-03 12:12:39.046  5594  5641 I jxcore-log: 
,11-03 12:12:39.052  5594  5641 I jxcore-log: 2016-11-03 11:12:39 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js'
11-03 12:12:39.052  5594  5641 I jxcore-log: 
,11-03 12:12:39.064  5594  5641 I jxcore-log: 2016-11-03 11:12:39 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolOneAtATime.js'
11-03 12:12:39.064  5594  5641 I jxcore-log: 
,11-03 12:12:39.071  5594  5641 I jxcore-log: 2016-11-03 11:12:39 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js'
11-03 12:12:39.071  5594  5641 I jxcore-log: 
,11-03 12:12:39.093  5594  5641 I jxcore-log: 2016-11-03 11:12:39 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js'
11-03 12:12:39.093  5594  5641 I jxcore-log: 
,11-03 12:12:39.104  5594  5641 I jxcore-log: 2016-11-03 11:12:39 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerAction.js'
11-03 12:12:39.104  5594  5641 I jxcore-log: 
,11-03 12:12:39.116  5594  5641 I jxcore-log: 2016-11-03 11:12:39 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js'
11-03 12:12:39.116  5594  5641 I jxcore-log: 
,11-03 12:12:39.126  5594  5641 I jxcore-log: 2016-11-03 11:12:39 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js'
11-03 12:12:39.126  5594  5641 I jxcore-log: 
,11-03 12:12:39.138  5594  5641 I jxcore-log: 2016-11-03 11:12:39 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js'
11-03 12:12:39.138  5594  5641 I jxcore-log: 
,11-03 12:12:39.148  5594  5641 I jxcore-log: 2016-11-03 11:12:39 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js'
11-03 12:12:39.148  5594  5641 I jxcore-log: 
,11-03 12:12:39.155  5594  5641 I jxcore-log: 2016-11-03 11:12:39 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js'
11-03 12:12:39.155  5594  5641 I jxcore-log: 
,11-03 12:12:39.160  5594  5641 I jxcore-log: 2016-11-03 11:12:39 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testUsn.js'
11-03 12:12:39.160  5594  5641 I jxcore-log: 
,11-03 12:12:39.166  5594  5641 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: SUPPORTED
,11-03 12:12:39.167  5594  5641 I jxcore-log: 2016-11-03 11:12:39 - INFO testUtils: 'BLE multiple advertisement supported'
11-03 12:12:39.167  5594  5641 I jxcore-log: 
,11-03 12:12:39.292  5594  5641 I jxcore-log: 2016-11-03 11:12:39 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-03 12:12:39.292  5594  5641 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-03 12:12:39.292  5594  5641 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-03 12:12:39.292  5594  5641 I jxcore-log: emit@events.js:82:1
11-03 12:12:39.292  5594  5641 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-03 12:12:39.292  5594  5641 I jxcore-log: emit@events.js:82:1'
11-03 12:12:39.292  5594  5641 I jxcore-log: 
,11-03 12:12:39.450  5594  5641 I jxcore-log: 2016-11-03 11:12:39 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-03 12:12:39.450  5594  5641 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-03 12:12:39.450  5594  5641 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-03 12:12:39.450  5594  5641 I jxcore-log: emit@events.js:82:1
11-03 12:12:39.450  5594  5641 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-03 12:12:39.450  5594  5641 I jxcore-log: emit@events.js:82:1'
11-03 12:12:39.450  5594  5641 I jxcore-log: 
,11-03 12:12:39.454  5594  5641 I jxcore-log: 2016-11-03 11:12:39 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-03 12:12:39.454  5594  5641 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-03 12:12:39.454  5594  5641 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-03 12:12:39.454  5594  5641 I jxcore-log: emit@events.js:82:1
11-03 12:12:39.454  5594  5641 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-03 12:12:39.454  5594  5641 I jxcore-log: emit@events.js:82:1'
11-03 12:12:39.454  5594  5641 I jxcore-log: 
,11-03 12:12:39.927  5594  5641 I jxcore-log: 2016-11-03 11:12:39 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-03 12:12:39.927  5594  5641 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-03 12:12:39.927  5594  5641 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-03 12:12:39.927  5594  5641 I jxcore-log: emit@events.js:82:1
11-03 12:12:39.927  5594  5641 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-03 12:12:39.927  5594  5641 I jxcore-log: emit@events.js:82:1'
11-03 12:12:39.927  5594  5641 I jxcore-log: 
,11-03 12:12:39.932  5594  5641 I jxcore-log: 2016-11-03 11:12:39 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-03 12:12:39.932  5594  5641 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-03 12:12:39.932  5594  5641 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-03 12:12:39.932  5594  5641 I jxcore-log: emit@events.js:82:1
11-03 12:12:39.932  5594  5641 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-03 12:12:39.932  5594  5641 I jxcore-log: emit@events.js:82:1'
11-03 12:12:39.932  5594  5641 I jxcore-log: 
,11-03 12:12:40.435  5594  5641 I jxcore-log: 2016-11-03 11:12:40 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-03 12:12:40.435  5594  5641 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-03 12:12:40.435  5594  5641 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-03 12:12:40.435  5594  5641 I jxcore-log: emit@events.js:82:1
11-03 12:12:40.435  5594  5641 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-03 12:12:40.435  5594  5641 I jxcore-log: emit@events.js:82:1'
11-03 12:12:40.435  5594  5641 I jxcore-log: 
,11-03 12:12:40.439  5594  5641 I jxcore-log: 2016-11-03 11:12:40 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-03 12:12:40.439  5594  5641 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-03 12:12:40.439  5594  5641 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-03 12:12:40.439  5594  5641 I jxcore-log: emit@events.js:82:1
11-03 12:12:40.439  5594  5641 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-03 12:12:40.439  5594  5641 I jxcore-log: emit@events.js:82:1'
11-03 12:12:40.439  5594  5641 I jxcore-log: 
,11-03 12:12:41.469  5594  5641 I jxcore-log: 2016-11-03 11:12:41 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-03 12:12:41.469  5594  5641 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-03 12:12:41.469  5594  5641 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-03 12:12:41.469  5594  5641 I jxcore-log: emit@events.js:82:1
11-03 12:12:41.469  5594  5641 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-03 12:12:41.469  5594  5641 I jxcore-log: emit@events.js:82:1'
11-03 12:12:41.469  5594  5641 I jxcore-log: 
,11-03 12:12:41.477  5594  5641 I jxcore-log: 2016-11-03 11:12:41 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-03 12:12:41.477  5594  5641 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-03 12:12:41.477  5594  5641 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-03 12:12:41.477  5594  5641 I jxcore-log: emit@events.js:82:1
11-03 12:12:41.477  5594  5641 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-03 12:12:41.477  5594  5641 I jxcore-log: emit@events.js:82:1'
11-03 12:12:41.477  5594  5641 I jxcore-log: 
,11-03 12:12:41.623  3961  4444 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,11-03 12:12:42.521  5594  5641 I jxcore-log: 2016-11-03 11:12:42 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-03 12:12:42.521  5594  5641 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-03 12:12:42.521  5594  5641 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-03 12:12:42.521  5594  5641 I jxcore-log: emit@events.js:82:1
11-03 12:12:42.521  5594  5641 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-03 12:12:42.521  5594  5641 I jxcore-log: emit@events.js:82:1'
11-03 12:12:42.521  5594  5641 I jxcore-log: 
,11-03 12:12:42.525  5594  5641 I jxcore-log: 2016-11-03 11:12:42 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-03 12:12:42.525  5594  5641 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-03 12:12:42.525  5594  5641 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-03 12:12:42.525  5594  5641 I jxcore-log: emit@events.js:82:1
11-03 12:12:42.525  5594  5641 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-03 12:12:42.525  5594  5641 I jxcore-log: emit@events.js:82:1'
11-03 12:12:42.525  5594  5641 I jxcore-log: 
,11-03 12:12:42.694  3608  5905 I VacuumService: Vacuum at: now=1478171562694 tag=VacuumService
,11-03 12:12:42.737  3608  5908 D GetConfigurationSnapshotOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,11-03 12:12:42.768  3608  5906 I PhenotypeFlagCommitter: Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,11-03 12:12:42.770  3608  5906 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,11-03 12:12:42.795  3608  5906 W Uploader:  no longer exists, so no auth token.
,11-03 12:12:42.801  3608  5908 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,11-03 12:12:43.171  3608  5910 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,11-03 12:12:43.352  3608  5908 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,11-03 12:12:43.429  3608  5906 W Uploader:  no longer exists, so no auth token.
,11-03 12:12:43.440  3608  5910 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,11-03 12:12:43.528  3608  5908 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,11-03 12:12:43.550  5594  5641 I jxcore-log: 2016-11-03 11:12:43 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-03 12:12:43.550  5594  5641 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-03 12:12:43.550  5594  5641 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-03 12:12:43.550  5594  5641 I jxcore-log: emit@events.js:82:1
11-03 12:12:43.550  5594  5641 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-03 12:12:43.550  5594  5641 I jxcore-log: emit@events.js:82:1'
11-03 12:12:43.550  5594  5641 I jxcore-log: 
,11-03 12:12:43.552  5594  5641 I jxcore-log: 2016-11-03 11:12:43 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-03 12:12:43.552  5594  5641 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-03 12:12:43.552  5594  5641 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-03 12:12:43.552  5594  5641 I jxcore-log: emit@events.js:82:1
11-03 12:12:43.552  5594  5641 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-03 12:12:43.552  5594  5641 I jxcore-log: emit@events.js:82:1'
11-03 12:12:43.552  5594  5641 I jxcore-log: 
,11-03 12:12:43.612  3608  5910 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,11-03 12:12:44.592  5594  5641 I jxcore-log: 2016-11-03 11:12:44 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-03 12:12:44.592  5594  5641 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-03 12:12:44.592  5594  5641 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-03 12:12:44.592  5594  5641 I jxcore-log: emit@events.js:82:1
11-03 12:12:44.592  5594  5641 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-03 12:12:44.592  5594  5641 I jxcore-log: emit@events.js:82:1'
11-03 12:12:44.592  5594  5641 I jxcore-log: 
,11-03 12:12:44.597  5594  5641 I jxcore-log: 2016-11-03 11:12:44 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-03 12:12:44.597  5594  5641 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-03 12:12:44.597  5594  5641 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-03 12:12:44.597  5594  5641 I jxcore-log: emit@events.js:82:1
11-03 12:12:44.597  5594  5641 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-03 12:12:44.597  5594  5641 I jxcore-log: emit@events.js:82:1'
11-03 12:12:44.597  5594  5641 I jxcore-log: 
,11-03 12:12:45.629  5594  5641 I jxcore-log: 2016-11-03 11:12:45 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-03 12:12:45.629  5594  5641 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-03 12:12:45.629  5594  5641 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-03 12:12:45.629  5594  5641 I jxcore-log: emit@events.js:82:1
11-03 12:12:45.629  5594  5641 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-03 12:12:45.629  5594  5641 I jxcore-log: emit@events.js:82:1'
11-03 12:12:45.629  5594  5641 I jxcore-log: 
,11-03 12:12:45.634  5594  5641 I jxcore-log: 2016-11-03 11:12:45 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-03 12:12:45.634  5594  5641 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-03 12:12:45.634  5594  5641 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-03 12:12:45.634  5594  5641 I jxcore-log: emit@events.js:82:1
11-03 12:12:45.634  5594  5641 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-03 12:12:45.634  5594  5641 I jxcore-log: emit@events.js:82:1'
11-03 12:12:45.634  5594  5641 I jxcore-log: 
,11-03 12:12:46.670  5594  5641 I jxcore-log: 2016-11-03 11:12:46 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-03 12:12:46.670  5594  5641 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-03 12:12:46.670  5594  5641 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-03 12:12:46.670  5594  5641 I jxcore-log: emit@events.js:82:1
11-03 12:12:46.670  5594  5641 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-03 12:12:46.670  5594  5641 I jxcore-log: emit@events.js:82:1'
11-03 12:12:46.670  5594  5641 I jxcore-log: 
,11-03 12:12:46.676  5594  5641 I jxcore-log: 2016-11-03 11:12:46 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-03 12:12:46.676  5594  5641 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-03 12:12:46.676  5594  5641 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-03 12:12:46.676  5594  5641 I jxcore-log: emit@events.js:82:1
11-03 12:12:46.676  5594  5641 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-03 12:12:46.676  5594  5641 I jxcore-log: emit@events.js:82:1'
11-03 12:12:46.676  5594  5641 I jxcore-log: 
,11-03 12:12:47.756  5594  5641 I jxcore-log: 2016-11-03 11:12:47 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-03 12:12:47.756  5594  5641 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-03 12:12:47.756  5594  5641 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-03 12:12:47.756  5594  5641 I jxcore-log: emit@events.js:82:1
11-03 12:12:47.756  5594  5641 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-03 12:12:47.756  5594  5641 I jxcore-log: emit@events.js:82:1'
11-03 12:12:47.756  5594  5641 I jxcore-log: 
,11-03 12:12:47.761  5594  5641 I jxcore-log: 2016-11-03 11:12:47 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-03 12:12:47.761  5594  5641 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-03 12:12:47.761  5594  5641 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-03 12:12:47.761  5594  5641 I jxcore-log: emit@events.js:82:1
11-03 12:12:47.761  5594  5641 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-03 12:12:47.761  5594  5641 I jxcore-log: emit@events.js:82:1'
11-03 12:12:47.761  5594  5641 I jxcore-log: 
,11-03 12:12:48.796  5594  5641 I jxcore-log: 2016-11-03 11:12:48 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-03 12:12:48.796  5594  5641 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-03 12:12:48.796  5594  5641 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-03 12:12:48.796  5594  5641 I jxcore-log: emit@events.js:82:1
11-03 12:12:48.796  5594  5641 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-03 12:12:48.796  5594  5641 I jxcore-log: emit@events.js:82:1'
11-03 12:12:48.796  5594  5641 I jxcore-log: 
,11-03 12:12:48.803  5594  5641 I jxcore-log: 2016-11-03 11:12:48 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-03 12:12:48.803  5594  5641 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-03 12:12:48.803  5594  5641 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-03 12:12:48.803  5594  5641 I jxcore-log: emit@events.js:82:1
11-03 12:12:48.803  5594  5641 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-03 12:12:48.803  5594  5641 I jxcore-log: emit@events.js:82:1'
11-03 12:12:48.803  5594  5641 I jxcore-log: 
,11-03 12:12:49.112   545   545 I ServiceManager: Waiting for service AtCmdFwd...
,11-03 12:12:49.840  5594  5641 I jxcore-log: 2016-11-03 11:12:49 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-03 12:12:49.840  5594  5641 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-03 12:12:49.840  5594  5641 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-03 12:12:49.840  5594  5641 I jxcore-log: emit@events.js:82:1
11-03 12:12:49.840  5594  5641 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-03 12:12:49.840  5594  5641 I jxcore-log: emit@events.js:82:1'
11-03 12:12:49.840  5594  5641 I jxcore-log: 
,11-03 12:12:49.845  5594  5641 I jxcore-log: 2016-11-03 11:12:49 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-03 12:12:49.845  5594  5641 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-03 12:12:49.845  5594  5641 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-03 12:12:49.845  5594  5641 I jxcore-log: emit@events.js:82:1
11-03 12:12:49.845  5594  5641 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-03 12:12:49.845  5594  5641 I jxcore-log: emit@events.js:82:1'
11-03 12:12:49.845  5594  5641 I jxcore-log: 
,11-03 12:12:50.113   545   545 I ServiceManager: Waiting for service AtCmdFwd...
,11-03 12:12:50.876  5594  5641 I jxcore-log: 2016-11-03 11:12:50 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-03 12:12:50.876  5594  5641 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-03 12:12:50.876  5594  5641 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-03 12:12:50.876  5594  5641 I jxcore-log: emit@events.js:82:1
11-03 12:12:50.876  5594  5641 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-03 12:12:50.876  5594  5641 I jxcore-log: emit@events.js:82:1'
11-03 12:12:50.876  5594  5641 I jxcore-log: 
,11-03 12:12:50.880  5594  5641 I jxcore-log: 2016-11-03 11:12:50 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-03 12:12:50.880  5594  5641 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-03 12:12:50.880  5594  5641 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-03 12:12:50.880  5594  5641 I jxcore-log: emit@events.js:82:1
11-03 12:12:50.880  5594  5641 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-03 12:12:50.880  5594  5641 I jxcore-log: emit@events.js:82:1'
11-03 12:12:50.880  5594  5641 I jxcore-log: 
,11-03 12:12:51.114   545   545 I ServiceManager: Waiting for service AtCmdFwd...
,11-03 12:12:51.975  5594  5641 I jxcore-log: 2016-11-03 11:12:51 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-03 12:12:51.975  5594  5641 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-03 12:12:51.975  5594  5641 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-03 12:12:51.975  5594  5641 I jxcore-log: emit@events.js:82:1
11-03 12:12:51.975  5594  5641 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-03 12:12:51.975  5594  5641 I jxcore-log: emit@events.js:82:1'
11-03 12:12:51.975  5594  5641 I jxcore-log: 
,11-03 12:12:51.981  5594  5641 I jxcore-log: 2016-11-03 11:12:51 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-03 12:12:51.981  5594  5641 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-03 12:12:51.981  5594  5641 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-03 12:12:51.981  5594  5641 I jxcore-log: emit@events.js:82:1
11-03 12:12:51.981  5594  5641 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-03 12:12:51.981  5594  5641 I jxcore-log: emit@events.js:82:1'
11-03 12:12:51.981  5594  5641 I jxcore-log: 
,11-03 12:12:52.116   545   545 I ServiceManager: Waiting for service AtCmdFwd...
,11-03 12:12:53.010  5594  5641 I jxcore-log: 2016-11-03 11:12:53 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-03 12:12:53.010  5594  5641 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-03 12:12:53.010  5594  5641 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-03 12:12:53.010  5594  5641 I jxcore-log: emit@events.js:82:1
11-03 12:12:53.010  5594  5641 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-03 12:12:53.010  5594  5641 I jxcore-log: emit@events.js:82:1'
11-03 12:12:53.010  5594  5641 I jxcore-log: 
,11-03 12:12:53.020  5594  5641 E jxcore  : Error!: error is undefined
11-03 12:12:53.020  5594  5641 E jxcore  : Stack: [{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/lib/CoordinatedClient.js","_functionName":"CoordinatedClient.prototype._error","_lineNumber":"220","_columnNumber":"1","_msg":"    at CoordinatedClient.prototype._error@/data/data/com.test.thalitest/files/www/jxcore/lib/CoordinatedClient.js:220:1"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/component-emitter/index.js","_functionName":"Emitter.prototype.emit","_lineNumber":"131","_columnNumber":"7","_msg":"    at Emitter.prototype.emit@/data/data/com.test.thalitest/files/www/jxcore/node_modules/component-emitter/index.js:131:7"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/socket.js","_functionName":"Socket.prototype.emit","_lineNumber":"133","_columnNumber":"5","_msg":"    at Socket.prototype.emit@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/socket.js:133:5"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js","_functionName":"Manager.prototype.emitAll","_lineNumber":"81","_columnNumber":"7","_msg":"    at Manager.prototype.emitAll@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:81:7"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js","_functionName":"Manager.prototype.reconnect","_lineNumber":"507","_columnNumber":"5","_msg":"    at Manager.prototype.reconnect@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:507:5"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js","_functionName":"Manager.prototype.reconnect/timer</<","_lineNumber":"528","_columnNumber":"11","_msg":"    at Manager.prototype.reconnect/timer</<@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:528:11"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js","_functionName":"Manager.prototype.connect/errorSub<","_lineNumber":"235","_columnNumber":"7","_msg":"    at Manager.prototype.connect/errorSub<@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:235:7"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/node_modules/component-emitter/index.js","_functionName":"Emitter.prototype.emit","_lineNumber":"134","_columnNumber":"7","_msg":"    at Emitter.prototype.emit@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/node_modules/component-emitter/index.js:134:7"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/socket.js","_functionName":"Socket.prototype.onError","_lineNumber":"670","_columnNumber":"3","_msg":"    at Socket.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/socket.js:670:3"}]
,11-03 12:12:53.024  5594  5641 I jxcore-log: 2016-11-03 11:12:53 - ERROR TestsProcess: 'uncaught exception, error: 'TypeError: error is undefined', stack: 'TypeError: error is undefined
11-03 12:12:53.024  5594  5641 I jxcore-log:     at CoordinatedClient.prototype._error@/data/data/com.test.thalitest/files/www/jxcore/lib/CoordinatedClient.js:220:1
11-03 12:12:53.024  5594  5641 I jxcore-log:     at Emitter.prototype.emit@/data/data/com.test.thalitest/files/www/jxcore/node_modules/component-emitter/index.js:131:7
11-03 12:12:53.024  5594  5641 I jxcore-log:     at Socket.prototype.emit@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/socket.js:133:5
11-03 12:12:53.024  5594  5641 I jxcore-log:     at Manager.prototype.emitAll@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:81:7
11-03 12:12:53.024  5594  5641 I jxcore-log:     at Manager.prototype.reconnect@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:507:5
11-03 12:12:53.024  5594  5641 I jxcore-log:     at Manager.prototype.reconnect/timer</<@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:528:11
11-03 12:12:53.024  5594  5641 I jxcore-log:     at Manager.prototype.connect/errorSub<@/data/data/com.test.thalitest/files/www/jxcore/node_modules/sock
,11-03 12:12:53.025  5594  5641 I jxcore-log: 2016-11-03 11:12:53 - ERROR TestsProcess: '****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****'
11-03 12:12:53.025  5594  5641 I jxcore-log: 
11-03 12:12:53.027  5594  5641 E jxcore-log: TypeError: 
11-03 12:12:53.028  5594  5641 E jxcore-log: error is undefined
11-03 12:12:53.028  5594  5641 E jxcore-log:  (/data/data/com.test.thalitest/files/www/jxcore/lib/CoordinatedClient.js 220:0)
11-03 12:12:53.028  5594  5641 E jxcore-log: 
,11-03 12:12:53.097   928  2967 W InputDispatcher: channel '58dddd1 com.test.thalitest/com.test.thalitest.MainActivity (server)' ~ Consumer closed input channel or an error occurred.  events=0x9
11-03 12:12:53.098   928  2967 E InputDispatcher: channel '58dddd1 com.test.thalitest/com.test.thalitest.MainActivity (server)' ~ Channel is unrecoverably broken and will be disposed!
,11-03 12:12:53.107  5809  5820 D BtGatt.GattService: Binder is dead - unregistering client (5)!
,11-03 12:12:53.108   928  5737 D GraphicsStats: Buffer count: 2
11-03 12:12:53.108   928  3180 I WindowState: WIN DEATH: Window{58dddd1 u0 com.test.thalitest/com.test.thalitest.MainActivity}
11-03 12:12:53.108   928  3180 W InputDispatcher: Attempted to unregister already unregistered input channel '58dddd1 com.test.thalitest/com.test.thalitest.MainActivity (server)'
,11-03 12:12:53.109  5809  5828 D BtGatt.AdvertiseManager: message : 1
,11-03 12:12:53.110  5809  5828 D BtGatt.AdvertiseManager: stop advertise for client 5
11-03 12:12:53.109   928  2980 D WifiService: Client connection lost with reason: 4
11-03 12:12:53.110  5809  5828 D BtGatt.AdvertiseManager: app died - unregistering client : 5
11-03 12:12:53.112  5809  5828 D BtGatt.GattService: unregisterClient() - clientIf=5
11-03 12:12:53.113   529   529 I Zygote  : Process 5594 exited cleanly (139)
11-03 12:12:53.113   928   939 I ActivityManager: Process com.test.thalitest (pid 5594) has died
11-03 12:12:53.114   928   939 W ActivityManager: Force removing ActivityRecord{99465b9 u0 com.test.thalitest/.MainActivity t68}: app died, no saved state
,11-03 12:12:53.117   545   545 I ServiceManager: Waiting for service AtCmdFwd...
,11-03 12:12:53.129  5809  5825 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=255, status=0
,11-03 12:12:53.129  5809  5825 E BtGatt.ContextMap: Context not found for ID 255
,11-03 12:12:53.159  5737  5737 W Binder_B: type=1400 audit(0.0:123): avc: denied { ioctl } for path="socket:[28922]" dev="sockfs" ino=28922 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-03 12:12:53.159  5737  5737 W Binder_B: type=1400 audit(0.0:124): avc: denied { ioctl } for path="socket:[28922]" dev="sockfs" ino=28922 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-03 12:12:53.163   928  5737 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 5594 uid 10077
,11-03 12:12:53.168  3679  3679 I Keyboard.Facilitator: onFinishInput()
,11-03 12:12:53.211  3979  5921 I MicroRecognitionRnrImpl: Starting detection.
,11-03 12:12:53.213  3979  5922 I MicrophoneInputStream: mic_starting com.google.android.apps.gsa.speech.audio.x@ae31b35
,11-03 12:12:53.215   513  5924 I AudioFlinger: AudioFlinger's thread 0xf1dc0000 ready to run
,11-03 12:12:53.219   513  3025 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
,11-03 12:12:53.220  3979  5922 I MicrophoneInputStream: mic_started com.google.android.apps.gsa.speech.audio.x@ae31b35
,11-03 12:12:53.231   513  5924 D audio_hw_primary: select_devices: out_snd_device(0: none) in_snd_device(63: voice-rec-mic)
11-03 12:12:53.231   513  5924 D msm8974_platform: platform_send_audio_calibration: sending audio calibration for snd_device(63) acdb_id(62)
,11-03 12:12:53.231   513  5924 I ACDB-LOADER: ACDB AFE returned = -19
11-03 12:12:53.231   513  5924 I soundtrigger: audio_extn_sound_trigger_update_device_status: device 0x3f of type 1 for Event 1
11-03 12:12:53.231   513  5924 D sound_trigger_platform: platform_stdev_check_and_update_concurrency: concurrency active 0, tx 1, rx 0, concurrency session_allowed 0
11-03 12:12:53.231   513  5924 D audio_hw_primary: enable_snd_device: snd_device(63: voice-rec-mic)
,11-03 12:12:53.240   513  5924 D audio_hw_primary: enable_audio_route: apply and update mixer path: audio-record
,11-03 12:12:53.314  3979  3979 I HotwordWorkerImpl: onReady
,11-03 12:12:53.425  5915  5915 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,11-03 12:12:53.429  5915  5915 D AndroidRuntime: CheckJNI is OFF
,11-03 12:12:53.453  5915  5915 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,11-03 12:12:53.482  5915  5915 I Radio-JNI: register_android_hardware_Radio DONE
,11-03 12:12:53.497  5915  5915 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,11-03 12:12:53.509   928   941 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=-1: uninstall pkg
,11-03 12:12:53.662   928   951 I art     : Starting a blocking GC Explicit
,11-03 12:12:53.697  3782  4055 W OpenGLRenderer: Incorrectly called buildLayer on View: ShortcutAndWidgetContainer, destroying layer...
,11-03 12:12:53.755   928   951 I art     : Explicit concurrent mark sweep GC freed 34591(2MB) AllocSpace objects, 8(252KB) LOS objects, 33% free, 28MB/43MB, paused 1.830ms total 92.869ms
,11-03 12:12:53.774   928   951 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,11-03 12:12:53.777  5915  5915 I art     : System.exit called, status: 0
11-03 12:12:53.777  5915  5915 I AndroidRuntime: VM exiting with result code 0.
,11-03 12:12:53.781   928   951 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=0: pkg removed
,11-03 12:12:53.803  3679  3679 I Keyboard.Facilitator: resetDictionaries() : en_US
,11-03 12:12:53.804  5809  5809 D BluetoothMapAppObserver: onReceive
,11-03 12:12:53.804  5809  5809 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
11-03 12:12:53.809  3679  5935 I Keyboard.Facilitator.DecoderInitializer: run()
,11-03 12:12:53.812  3961  4154 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,11-03 12:12:53.819   928  2968 I InputReader: Reconfiguring input devices.  changes=0x00000010
,11-03 12:12:53.827  3679  5935 I Decoder : createOrResetDecoder
,11-03 12:12:53.861  3765  3765 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,11-03 12:12:53.877   928   928 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,11-03 12:12:53.878  3608  3608 I ConfigService: onCreate
11-03 12:12:53.881  3433  5938 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,11-03 12:12:53.889  3608  3608 E NetworkScheduler.SchedulerReceiver: Invalid parameter app
,11-03 12:12:53.889  3608  3608 E NetworkScheduler.SchedulerReceiver: Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
11-03 12:12:53.889   314   314 W kworker/1:2: type=1400 audit(0.0:125): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-03 12:12:53.895   314   314 W kworker/1:2: type=1400 audit(0.0:126): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-03 12:12:53.903  3679  5935 I Keyboard.Facilitator.MainLanguageModelLoader: run()
,11-03 12:12:53.909  4074  5942 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
11-03 12:12:53.909  4074  5942 D AccountUtils: Clearing selected account for com.test.thalitest
,11-03 12:12:53.926   928  3802 I ActivityManager: Start proc 5945:com.google.android.googlequicksearchbox:crash_report/u0a29 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
,--------- beginning of crash
11-03 12:12:53.927  3782  3922 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
11-03 12:12:53.927  3782  3922 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 3782
11-03 12:12:53.927  3782  3922 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 778)
11-03 12:12:53.927  3782  3922 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
11-03 12:12:53.927  3782  3922 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
11-03 12:12:53.927  3782  3922 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
11-03 12:12:53.927  3782  3922 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
11-03 12:12:53.927  3782  3922 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
11-03 12:12:53.927  3782  3922 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
11-03 12:12:53.927  3782  3922 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
11-03 12:12:53.927  3782  3922 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
11-03 12:12:53.927  3782  3922 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
11-03 12:12:53.927  3782  3922 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
11-03 12:12:53.927  3782  3922 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,11-03 12:12:53.929   314   314 W kworker/1:2: type=1400 audit(0.0:127): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-03 12:12:53.935  4074  5942 I LocationSettingsChecker: Removing dialog suppression flag for package com.test.thalitest
,11-03 12:12:53.935   928  5955 E DropBoxManagerService: Can't write: system_app_crash
11-03 12:12:53.935   928  5955 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop118.tmp: open failed: EROFS (Read-only file system)
11-03 12:12:53.935   928  5955 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
11-03 12:12:53.935   928  5955 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
11-03 12:12:53.935   928  5955 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
11-03 12:12:53.935   928  5955 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
11-03 12:12:53.935   928  5955 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
11-03 12:12:53.935   928  5955 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
11-03 12:12:53.935   928  5955 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
11-03 12:12:53.935   928  5955 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
11-03 12:12:53.935   928  5955 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
11-03 12:12:53.935   928  5955 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
11-03 12:12:53.935   928  5955 E DropBoxManagerService: 	... 5 more
11-03 12:12:53.936   928  3829 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,11-03 12:12:53.941  3979  3993 W SearchService: Abort, client detached.
,11-03 12:12:53.943  3979  3979 I HotwordDetector: Closing mic
11-03 12:12:53.944  3979  4236 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@ae31b35
11-03 12:12:53.944  3979  5922 E AudioRecord-JNI: Error -4 during AudioRecord native read
,11-03 12:12:53.950  3433  5938 E SQLiteLog: (3850) statement aborts at 18: [DELETE FROM calls WHERE (((source_package = 'com.test.thalitest'))) AND ((type = 4))] disk I/O error
,11-03 12:12:53.952   408   408 W Binder_2: type=1400 audit(0.0:128): avc: denied { ioctl } for path="socket:[19399]" dev="sockfs" ino=19399 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-03 12:12:53.952   408   408 W Binder_2: type=1400 audit(0.0:129): avc: denied { ioctl } for path="socket:[19399]" dev="sockfs" ino=19399 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-03 12:12:53.952   408   408 W Binder_2: type=1400 audit(0.0:130): avc: denied { ioctl } for path="socket:[31724]" dev="sockfs" ino=31724 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-03 12:12:53.952   408   408 W Binder_2: type=1400 audit(0.0:131): avc: denied { ioctl } for path="socket:[31724]" dev="sockfs" ino=31724 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
11-03 12:12:53.957  3433  5938 E AndroidRuntime: FATAL EXCEPTION: IntentService[VoicemailCleanupService]
11-03 12:12:53.957  3433  5938 E AndroidRuntime: Process: android.process.acore, PID: 3433
11-03 12:12:53.957  3433  5938 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
11-03 12:12:53.957  3433  5938 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
11-03 12:12:53.957  3433  5938 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
11-03 12:12:53.957  3433  5938 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
11-03 12:12:53.957  3433  5938 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
11-03 12:12:53.957  3433  5938 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
11-03 12:12:53.957  3433  5938 E AndroidRuntime: 	at com.android.providers.contacts.DbModifierWithNotification.delete(DbModifierWithNotification.java:197)
11-03 12:12:53.957  3433  5938 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:219)
11-03 12:12:53.957  3433  5938 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
11-03 12:12:53.957  3433  5938 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
11-03 12:12:53.957  3433  5938 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
11-03 12:12:53.957  3433  5938 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
11-03 12:12:53.957  3433  5938 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
11-03 12:12:53.957  3433  5938 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
11-03 12:12:53.957  3433  5938 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-03 12:12:53.957  3433  5938 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
11-03 12:12:53.957  3433  5938 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
11-03 12:12:53.957   928  5959 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,11-03 12:12:53.962  3679  5935 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /data/user/0/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
,11-03 12:12:53.964  3679  5935 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
11-03 12:12:53.964  3679  5935 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
,11-03 12:12:53.966  3679  5935 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Contacts.dict
,11-03 12:12:53.966  3679  5935 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = history
,11-03 12:12:53.967  3679  5935 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loaded File = UserHistory.en_US.dict
,11-03 12:12:53.970  3679  5935 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = user
11-03 12:12:53.972  3679  5935 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Personal.en_US.dict
11-03 12:12:53.972  3679  5935 I Keyboard.Facilitator.PersonalDictionaryLoader: run() : Loaded (exit)
11-03 12:12:53.972  3679  5935 I Keyboard.Facilitator.Delight2FileSweeper: run()
11-03 12:12:53.974  3679  5935 I Keyboard.Facilitator.RecurringTaskScheduler: run()
11-03 12:12:53.974  3679  5935 I StatsUtilsManager: startPeriodStatsRecorder() : Success
11-03 12:12:53.974  3679  5935 I PeriodicStatsRecorder: shouldRecordStats() = Too Soon
,11-03 12:12:53.974   928  5963 E DropBoxManagerService: Can't write: system_app_crash
11-03 12:12:53.974   928  5963 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop120.tmp: open failed: EROFS (Read-only file system)
11-03 12:12:53.974   928  5963 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
11-03 12:12:53.974   928  5963 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
11-03 12:12:53.974   928  5963 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
11-03 12:12:53.974   928  5963 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
11-03 12:12:53.974   928  5963 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
11-03 12:12:53.974   928  5963 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
11-03 12:12:53.974   928  5963 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
11-03 12:12:53.974   928  5963 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
11-03 12:12:53.974   928  5963 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
11-03 12:12:53.974   928  5963 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
11-03 12:12:53.974   928  5963 E DropBoxManagerService: 	... 5 more
,11-03 12:12:53.986  4074  5942 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/phenotype.db'.
11-03 12:12:53.986  4074  5942 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
11-03 12:12:53.986  4074  5942 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
11-03 12:12:53.986  4074  5942 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
11-03 12:12:53.986  4074  5942 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
11-03 12:12:53.986  4074  5942 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
11-03 12:12:53.986  4074  5942 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
11-03 12:12:53.986  4074  5942 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
11-03 12:12:53.986  4074  5942 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
11-03 12:12:53.986  4074  5942 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
11-03 12:12:53.986  4074  5942 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
11-03 12:12:53.986  4074  5942 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
11-03 12:12:53.986  4074  5942 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
11-03 12:12:53.986  4074  5942 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
11-03 12:12:53.986  4074  5942 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
11-03 12:12:53.986  4074  5942 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
11-03 12:12:53.986  4074  5942 E SQLiteDatabase: 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
11-03 12:12:53.986  4074  5942 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
11-03 12:12:53.986  4074  5942 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-03 12:12:53.986  4074  5942 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
11-03 12:12:53.986  4074  5942 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,11-03 12:12:53.996  4074  4074 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
11-03 12:12:53.996  4074  4074 D ChimeraModuleLdr: Module APK com.google.android.play.games already loaded
11-03 12:12:53.997  4074  5942 E SQLiteOpenHelper: Couldn't open phenotype.db for writing (will try read-only):
11-03 12:12:53.997  4074  5942 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
11-03 12:12:53.997  4074  5942 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
11-03 12:12:53.997  4074  5942 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
11-03 12:12:53.997  4074  5942 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
11-03 12:12:53.997  4074  5942 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
11-03 12:12:53.997  4074  5942 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
11-03 12:12:53.997  4074  5942 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
11-03 12:12:53.997  4074  5942 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
11-03 12:12:53.997  4074  5942 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
11-03 12:12:53.997  4074  5942 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
11-03 12:12:53.997  4074  5942 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
11-03 12:12:53.997  4074  5942 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
11-03 12:12:53.997  4074  5942 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
11-03 12:12:53.997  4074  5942 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
11-03 12:12:53.997  4074  5942 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
11-03 12:12:53.997  4074  5942 E SQLiteOpenHelper: 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
11-03 12:12:53.997  4074  5942 E SQLiteOpenHelper: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
11-03 12:12:53.997  4074  5942 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-03 12:12:53.997  4074  5942 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:148)
11-03 12:12:53.997  4074  5942 E SQLiteOpenHelper: 	at android.os.HandlerThread.run(HandlerThread.java:61)
11-03 12:12:53.999  4074  5942 W SQLiteOpenHelper: Opened phenotype.db in read-only mode
,11-03 12:12:54.007   928  5959 I Adreno  : QUALCOMM build                   : 63c06b2, I8366cd0437
11-03 12:12:54.007   928  5959 I Adreno  : Build Date                       : 12/06/15
11-03 12:12:54.007   928  5959 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
11-03 12:12:54.007   928  5959 I Adreno  : Local Branch                     : mybranch17112971
11-03 12:12:54.007   928  5959 I Adreno  : Remote Branch                    : quic/LA.BF64.1.2.9_v2
11-03 12:12:54.007   928  5959 I Adreno  : Remote Branch                    : NONE
11-03 12:12:54.007   928  5959 I Adreno  : Reconstruct Branch               : NOTHING
,11-03 12:12:54.017   928  4197 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
,11-03 12:12:54.017   513  5924 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
,11-03 12:12:54.019   513  5924 D audio_hw_primary: disable_snd_device: snd_device(63: voice-rec-mic)
,11-03 12:12:54.026  4074  5962 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/metrics.db'.
11-03 12:12:54.026  4074  5962 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
11-03 12:12:54.026  4074  5962 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
11-03 12:12:54.026  4074  5962 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
11-03 12:12:54.026  4074  5962 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
11-03 12:12:54.026  4074  5962 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
11-03 12:12:54.026  4074  5962 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
11-03 12:12:54.026  4074  5962 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
11-03 12:12:54.026  4074  5962 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
11-03 12:12:54.026  4074  5962 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
11-03 12:12:54.026  4074  5962 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
11-03 12:12:54.026  4074  5962 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
11-03 12:12:54.026  4074  5962 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
11-03 12:12:54.026  4074  5962 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
11-03 12:12:54.026  4074  5962 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
11-03 12:12:54.026  4074  5962 E SQLiteDatabase: 	at com.google.android.gms.googlehelp.metrics.c.a(SourceFile:102)
11-03 12:12:54.026  4074  5962 E SQLiteDatabase: 	at com.google.android.gms.googlehelp.c.a.b(SourceFile:52)
11-03 12:12:54.026  4074  5962 E SQLiteDatabase: 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:278)
11-03 12:12:54.026  4074  5962 E SQLiteDatabase: 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
11-03 12:12:54.026  4074  5962 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
11-03 12:12:54.026  4074  5962 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-03 12:12:54.026  4074  5962 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
11-03 12:12:54.026  4074  5962 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,11-03 12:12:54.027  4074  5962 E SQLiteOpenHelper: Couldn't open metrics.db for writing (will try read-only):
11-03 12:12:54.027  4074  5962 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
11-03 12:12:54.027  4074  5962 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
11-03 12:12:54.027  4074  5962 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
11-03 12:12:54.027  4074  5962 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
11-03 12:12:54.027  4074  5962 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
11-03 12:12:54.027  4074  5962 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
11-03 12:12:54.027  4074  5962 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
11-03 12:12:54.027  4074  5962 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
11-03 12:12:54.027  4074  5962 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
11-03 12:12:54.027  4074  5962 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
11-03 12:12:54.027  4074  5962 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
11-03 12:12:54.027  4074  5962 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
11-03 12:12:54.027  4074  5962 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
11-03 12:12:54.027  4074  5962 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
11-03 12:12:54.027  4074  5962 E SQLiteOpenHelper: 	at com.google.android.gms.googlehelp.metrics.c.a(SourceFile:102)
11-03 12:12:54.027  4074  5962 E SQLiteOpenHelper: 	at com.google.android.gms.googlehelp.c.a.b(SourceFile:52)
11-03 12:12:54.027  4074  5962 E SQLiteOpenHelper: 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:278)
11-03 12:12:54.027  4074  5962 E SQLiteOpenHelper: 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
11-03 12:12:54.027  4074  5962 E SQLiteOpenHelper: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
11-03 12:12:54.027  4074  5962 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-03 12:12:54.027  4074  5962 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:148)
11-03 12:12:54.027  4074  5962 E SQLiteOpenHelper: 	at android.os.HandlerThread.run(HandlerThread.java:61)
11-03 12:12:54.028   513  5924 I soundtrigger: audio_extn_sound_trigger_update_device_status: device 0x3f of type 1 for Event 0
11-03 12:12:54.029   513  5924 D sound_trigger_platform: platform_stdev_check_and_update_concurrency: concurrency active 0, tx 0, rx 0, concurrency session_allowed 1
11-03 12:12:54.029   513  3025 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
11-03 12:12:54.032  3979  5921 I MicroRecognitionRnrImpl: Detection finished
11-03 12:12:54.033  3979  4245 I MicroRecognitionRnrImpl: Stopping hotword detection.
,11-03 12:12:54.117   545   545 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,11-03 12:12:54.305   383   482 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0

```
