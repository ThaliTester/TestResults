#### Test 9215228616bd023_thali07_Huawei-Nexus 6P Logs


```
--------- beginning of main
11-18 13:30:29.253  3866  4251 I Icing   : Indexing 3C763AF371F9E97B4ECFEA01A338ADB468C38476 from com.google.android.googlequicksearchbox
,11-18 13:30:29.339  3866  4251 I Icing   : Indexing done 3C763AF371F9E97B4ECFEA01A338ADB468C38476
11-18 13:30:29.679  5618  5618 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
11-18 13:30:29.684  5618  5618 D AndroidRuntime: CheckJNI is OFF
11-18 13:30:29.712  5618  5618 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
11-18 13:30:29.745  5618  5618 I Radio-JNI: register_android_hardware_Radio DONE
11-18 13:30:29.760  5618  5618 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
11-18 13:30:29.763   930   940 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
11-18 13:30:29.781  5618  5618 D AndroidRuntime: Shutting down VM
11-18 13:30:29.786  3990  4009 W SearchService: Abort, client detached.
11-18 13:30:29.797  3990  4214 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@889aa31
11-18 13:30:29.797  3990  3990 I HotwordDetector: Closing mic
11-18 13:30:29.798  3990  4239 E AudioRecord-JNI: Error -4 during AudioRecord native read
11-18 13:30:29.813   930  3626 I ActivityManager: Start proc 5627:com.test.thalitest/u0a77 for activity com.test.thalitest/.MainActivity
11-18 13:30:29.878   512  4241 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
11-18 13:30:29.879   512  4241 D audio_hw_primary: disable_snd_device: snd_device(63: voice-rec-mic)
11-18 13:30:29.884   512  4241 I soundtrigger: audio_extn_sound_trigger_update_device_status: device 0x3f of type 1 for Event 0
11-18 13:30:29.884   512  4241 D sound_trigger_platform: platform_stdev_check_and_update_concurrency: concurrency active 0, tx 0, rx 0, concurrency session_allowed 1
11-18 13:30:29.885   512  3029 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
11-18 13:30:29.888  3990  4229 I MicroRecognitionRnrImpl: Stopping hotword detection.
11-18 13:30:29.888  3990  4236 I MicroRecognitionRnrImpl: Detection finished
11-18 13:30:29.905  5627  5627 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011750)
11-18 13:30:29.923  5627  5627 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
11-18 13:30:29.987  5627  5627 I LibraryLoader: Time to load native libraries: 61 ms (timestamps 5132-5193)
11-18 13:30:29.987  5627  5627 I LibraryLoader: Expected native library version number "",actual native library version number ""
,11-18 13:30:30.022  5627  5627 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {dca8a84}
11-18 13:30:30.022  5627  5627 I LibraryLoader: Expected native library version number "",actual native library version number ""
,11-18 13:30:30.022  5627  5627 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,11-18 13:30:30.025  5627  5627 I BrowserStartupController: Initializing chromium process, singleProcess=true
,11-18 13:30:30.026  5627  5627 E SysUtils: ApplicationContext is null in ApplicationStatus
,11-18 13:30:30.081  5627  5627 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,11-18 13:30:30.095  5627  5627 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,11-18 13:30:30.095  5627  5627 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
11-18 13:30:30.095  5627  5627 I Adreno  : QUALCOMM build                   : 63c06b2, I8366cd0437
11-18 13:30:30.095  5627  5627 I Adreno  : Build Date                       : 12/06/15
11-18 13:30:30.095  5627  5627 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
11-18 13:30:30.095  5627  5627 I Adreno  : Local Branch                     : mybranch17112971
11-18 13:30:30.095  5627  5627 I Adreno  : Remote Branch                    : quic/LA.BF64.1.2.9_v2
11-18 13:30:30.095  5627  5627 I Adreno  : Remote Branch                    : NONE
11-18 13:30:30.095  5627  5627 I Adreno  : Reconstruct Branch               : NOTHING
,11-18 13:30:30.130   930   947 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@62e5ace:true
,11-18 13:30:30.157   409   409 W Binder_2: type=1400 audit(0.0:99): avc: denied { ioctl } for path="socket:[20122]" dev="sockfs" ino=20122 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
11-18 13:30:30.157   409   409 W Binder_2: type=1400 audit(0.0:100): avc: denied { ioctl } for path="socket:[20122]" dev="sockfs" ino=20122 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-18 13:30:30.172  5627  5627 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,11-18 13:30:30.181  5627  5627 D SystemWebViewEngine: CordovaWebView is running on device made by: Huawei
,11-18 13:30:30.207   404   404 W Binder_1: type=1400 audit(0.0:101): avc: denied { ioctl } for path="socket:[32514]" dev="sockfs" ino=32514 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-18 13:30:30.213  5627  5664 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
11-18 13:30:30.207   404   404 W Binder_1: type=1400 audit(0.0:102): avc: denied { ioctl } for path="socket:[32514]" dev="sockfs" ino=32514 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-18 13:30:30.214  3191  3191 W Binder_3: type=1400 audit(0.0:103): avc: denied { ioctl } for path="socket:[30086]" dev="sockfs" ino=30086 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-18 13:30:30.214  3191  3191 W Binder_3: type=1400 audit(0.0:104): avc: denied { ioctl } for path="socket:[30086]" dev="sockfs" ino=30086 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
11-18 13:30:30.220  5627  5651 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,11-18 13:30:30.249  5627  5664 I OpenGLRenderer: Initialized EGL, version 1.4
,11-18 13:30:30.324   940   940 W Binder_1: type=1400 audit(0.0:105): avc: denied { ioctl } for path="socket:[32517]" dev="sockfs" ino=32517 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-18 13:30:30.324   940   940 W Binder_1: type=1400 audit(0.0:106): avc: denied { ioctl } for path="socket:[32517]" dev="sockfs" ino=32517 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-18 13:30:30.327  3193  3193 W Binder_5: type=1400 audit(0.0:107): avc: denied { ioctl } for path="socket:[32516]" dev="sockfs" ino=32516 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-18 13:30:30.332   930   948 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +540ms
11-18 13:30:30.333  3689  3689 I Keyboard.Facilitator: onFinishInput()
11-18 13:30:30.327  3193  3193 W Binder_5: type=1400 audit(0.0:108): avc: denied { ioctl } for path="socket:[32516]" dev="sockfs" ino=32516 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-18 13:30:30.367  5627  5627 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 5627
,11-18 13:30:30.508  5627  5627 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,11-18 13:30:30.611  5627  5666 D jxcore_app_log: JniHelper::setJavaVM(0xf4fbc000), pthread_self() = -567805648
,11-18 13:30:30.616  5627  5666 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
11-18 13:30:30.616  5627  5666 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
11-18 13:30:30.616  5627  5666 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
11-18 13:30:30.616  5627  5666 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
11-18 13:30:30.616  5627  5666 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,11-18 13:30:30.616  5627  5666 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2bcf96b added. We now have 1 listener(s)
,11-18 13:30:30.618  5627  5666 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 60:83:34:25:D7:D4
,11-18 13:30:30.618  5627  5666 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
,11-18 13:30:30.619  5627  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,11-18 13:30:30.619  5627  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,11-18 13:30:30.621  5627  5666 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
11-18 13:30:30.621  5627  5666 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
11-18 13:30:30.621  5627  5666 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
11-18 13:30:30.621  5627  5666 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 60:83:34:25:D7:D4
11-18 13:30:30.621  5627  5666 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
11-18 13:30:30.621  5627  5666 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
11-18 13:30:30.621  5627  5666 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
11-18 13:30:30.621  5627  5666 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
11-18 13:30:30.621  5627  5666 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
11-18 13:30:30.621  5627  5666 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
11-18 13:30:30.621  5627  5666 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
11-18 13:30:30.621  5627  5666 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
11-18 13:30:30.621  5627  5666 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
11-18 13:30:30.621  5627  5666 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,11-18 13:30:30.621  5627  5666 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@70a1486 added. We now have 1 listener(s)
11-18 13:30:30.621  5627  5666 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-18 13:30:30.628   930  2982 D WifiService: New client listening to asynchronous messages
,11-18 13:30:30.628  5627  5666 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,11-18 13:30:30.629  5627  5666 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
,11-18 13:30:30.629  5627  5666 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[JavaBridge,5,main], id: 55
11-18 13:30:30.629  5627  5666 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
11-18 13:30:30.629  5627  5666 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
11-18 13:30:30.629  5627  5666 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
11-18 13:30:30.629  5627  5666 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[JavaBridge,5,main], id: 55
11-18 13:30:30.630  5627  5666 I io.jxcore.node.LifeCycleMonitor: start: OK
,11-18 13:30:30.698  5627  5627 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,11-18 13:30:31.020  5627  5674 W jxcore-log: Initializing JXcore engine
11-18 13:30:31.020  5627  5674 W jxcore-log: JXcore engine is ready
,11-18 13:30:31.040  5674  5674 W Thread-61: type=1400 audit(0.0:109): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=5519 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,11-18 13:30:31.040  5674  5674 W Thread-61: type=1400 audit(0.0:110): avc: denied { ioctl } for path="socket:[17427]" dev="sockfs" ino=17427 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
11-18 13:30:31.040  5674  5674 W Thread-61: type=1400 audit(0.0:111): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=696 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
11-18 13:30:31.040  5674  5674 W Thread-61: type=1400 audit(0.0:112): avc: denied { ioctl } for path="socket:[31477]" dev="sockfs" ino=31477 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:untrusted_app:s0:c512,c768 tclass=netlink_route_socket permissive=0
,11-18 13:30:31.051  5627  5674 W jxcore-log: Starting JXcore engine
,11-18 13:30:31.102  5627  5674 W jxcore-log: Platform android
11-18 13:30:31.102  5627  5674 W jxcore-log: 
,11-18 13:30:31.102  5627  5674 W jxcore-log: Process ARCH arm
11-18 13:30:31.102  5627  5674 W jxcore-log: 
,11-18 13:30:31.241  5627  5674 I jxcore-log: JXcore Cordova bridge is ready!
11-18 13:30:31.241  5627  5674 I jxcore-log: 
,11-18 13:30:31.241  5627  5674 W jxcore-log: JXcore engine is started
,11-18 13:30:31.251  5627  5666 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,11-18 13:30:31.257  5627  5627 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,11-18 13:30:33.401  3610  3610 I ConfigService: onDestroy
,11-18 13:30:34.801   930   941 I ActivityManager: Killing 5179:com.google.android.youtube/u0a75 (adj 15): empty #17
,11-18 13:30:35.762   930  2981 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-18 13:30:38.356   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-18 13:30:39.357   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-18 13:30:40.358   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-18 13:30:41.243  5627  5674 I jxcore-log: 2016-11-18 12:30:41 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
11-18 13:30:41.243  5627  5674 I jxcore-log: 
,11-18 13:30:41.246  5627  5674 I jxcore-log: 2016-11-18 12:30:41 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
11-18 13:30:41.246  5627  5674 I jxcore-log: 
,11-18 13:30:41.246  5627  5674 I jxcore-log: 2016-11-18 12:30:41 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
11-18 13:30:41.246  5627  5674 I jxcore-log: 
,11-18 13:30:41.252  5627  5674 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,11-18 13:30:41.252  5627  5674 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-18 13:30:41.252  5627  5674 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-18 13:30:41.252  5627  5674 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-18 13:30:41.252  5627  5674 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-18 13:30:41.252  5627  5674 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-18 13:30:41.252  5627  5674 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-18 13:30:41.252  5627  5674 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-18 13:30:41.252  5627  5674 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-18 13:30:41.252  5627  5674 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
11-18 13:30:41.253  5627  5674 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
,11-18 13:30:41.257  5627  5674 I jxcore-log: 2016-11-18 12:30:41 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
11-18 13:30:41.257  5627  5674 I jxcore-log: 
11-18 13:30:41.258  5627  5674 I jxcore-log: 2016-11-18 12:30:41 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
11-18 13:30:41.258  5627  5674 I jxcore-log: 
,11-18 13:30:41.359   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-18 13:30:41.514  5627  5674 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,11-18 13:30:41.514  5627  5674 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3e07859 added. We now have 2 listener(s)
11-18 13:30:41.515  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
,11-18 13:30:41.515  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-18 13:30:41.515  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-18 13:30:41.515  5627  5674 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-18 13:30:41.516  5627  5674 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9148c1e added. We now have 2 listener(s)
11-18 13:30:41.516  5627  5674 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-18 13:30:41.516  5627  5674 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,11-18 13:30:41.527  5627  5674 D ExecuteNativeTests: Running unit tests
,11-18 13:30:41.528  5627  5674 D BluetoothAdapter: enable(): BT is already enabled..!
11-18 13:30:41.528   930   941 D WifiService: setWifiEnabled: true pid=5627, uid=10077
11-18 13:30:41.528   930   941 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-18 13:30:42.361   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-18 13:30:42.988  3990  5676 W CronetSyncConnectionRcs: Upload content type not set.
,11-18 13:30:43.178  4884  4926 D Finsky  : [184] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,11-18 13:30:43.194  4884  4884 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,11-18 13:30:43.197   930  3192 I ActivityManager: Killing 5269:org.codeaurora.ims/1001 (adj 15): empty #17
,11-18 13:30:43.362   535   535 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,11-18 13:30:51.534  5627  5674 I com.test.thalitest.ThaliTestRunner: Running UT
,11-18 13:30:51.601  5627  5674 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,11-18 13:30:51.601  5627  5674 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@97a7583 added. We now have 3 listener(s)
11-18 13:30:51.602  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-18 13:30:51.602  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,11-18 13:30:51.602  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-18 13:30:51.602  5627  5674 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-18 13:30:51.602  5627  5674 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f442300 added. We now have 3 listener(s)
11-18 13:30:51.602  5627  5674 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-18 13:30:51.603  5627  5674 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,11-18 13:30:51.607  5627  5674 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnConnectionTimeout
11-18 13:30:51.608  5627  5674 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
11-18 13:30:51.608  5627  5674 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-18 13:30:51.608  5627  5674 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-18 13:30:51.608  5627  5674 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-18 13:30:51.609  5627  5674 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
11-18 13:30:51.609  5627  5674 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
11-18 13:30:51.609  5627  5674 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
11-18 13:30:51.609  5627  5674 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-18 13:30:51.609  5627  5674 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-18 13:30:51.609  5627  5674 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-18 13:30:51.610  5627  5674 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnBluetoothMacAddressResolved
11-18 13:30:51.611  5627  5674 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
11-18 13:30:51.612  5627  5674 I io.jxcore.node.ConnectionHelperTest: Starting test: testHasMaximumNumberOfConnections
11-18 13:30:51.614  5627  5674 I io.jxcore.node.ConnectionHelperTest: Starting test: testStart
11-18 13:30:51.614  5627  5674 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
11-18 13:30:51.616  5627  5674 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,11-18 13:30:51.616  5627  5674 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
,11-18 13:30:51.628  5627  5674 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-18 13:30:51.628  5627  5674 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-18 13:30:51.628  5627  5674 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-18 13:30:51.628  5627  5674 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-18 13:30:51.628  5627  5674 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-18 13:30:51.628  5627  5674 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-18 13:30:51.628  5627  5674 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-18 13:30:51.628  5627  5674 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-18 13:30:51.628  5627  5674 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,11-18 13:30:51.629  5627  5674 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
,11-18 13:30:51.629  5627  5674 D io.jxcore.node.ConnectivityMonitor: start: OK
11-18 13:30:51.630  5627  5674 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 1
11-18 13:30:51.630  5627  5674 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 0 -> 1
11-18 13:30:51.630  5627  5674 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-61,5,main], id: 61
,11-18 13:30:51.630  5627  5674 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-61,5,main], id: 61
11-18 13:30:51.630  5627  5674 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-61,5,main], id: 61
,11-18 13:30:51.630  5627  5674 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
11-18 13:30:51.630  5627  5674 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
11-18 13:30:51.630  5627  5674 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
11-18 13:30:51.630  5627  5674 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-18 13:30:51.634  5627  5674 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
11-18 13:30:51.635  5627  5674 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
11-18 13:30:51.636  5627  5674 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
11-18 13:30:51.636  5627  5680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
11-18 13:30:51.636  5627  5627 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-18 13:30:51.636  5627  5674 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
11-18 13:30:51.636  5627  5674 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
11-18 13:30:51.636  5627  5674 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
11-18 13:30:51.636  5627  5674 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-18 13:30:51.637  5627  5674 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
11-18 13:30:51.639  5627  5627 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-18 13:30:51.639  5627  5627 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
,11-18 13:30:51.639  5627  5680 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-18 13:30:51.637  4698  4698 W Binder_2: type=1400 audit(0.0:113): avc: denied { ioctl } for path="socket:[31518]" dev="sockfs" ino=31518 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,11-18 13:30:51.641  5627  5674 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-18 13:30:51.641  5627  5674 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-18 13:30:51.641  5627  5674 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
11-18 13:30:51.644  5627  5680 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
11-18 13:30:51.637  4698  4698 W Binder_2: type=1400 audit(0.0:114): avc: denied { ioctl } for path="socket:[31518]" dev="sockfs" ino=31518 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-18 13:30:51.645  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-61,5,main], id: 61
,11-18 13:30:51.645  5627  5674 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-18 13:30:51.646  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,11-18 13:30:51.646  5627  5674 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-18 13:30:51.646  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 1
11-18 13:30:51.647  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
11-18 13:30:51.647  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-61,5,main], id: 61
11-18 13:30:51.647  5627  5674 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
,11-18 13:30:51.647  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: createAdvertiseDataToServiceData 
11-18 13:30:51.647  5627  5674 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-18 13:30:51.648  5627  5674 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 01 60 83 34 25 D7 D4
11-18 13:30:51.648  5627  5674 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-18 13:30:51.648  5627  5674 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: created AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-18 13:30:51.648  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: Current thread: Thread[Thread-61,5,main], id: 61
,11-18 13:30:51.648  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: was started = false
11-18 13:30:51.648  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: advertiseData = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-18 13:30:51.648  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData finished: Current thread: Thread[Thread-61,5,main], id: 61
11-18 13:30:51.648  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
11-18 13:30:51.648  5627  5674 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... adv data = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]Current thread: Thread[Thread-61,5,main], id: 61
11-18 13:30:51.649  5627  5674 D BluetoothAdapter: STATE_ON
,11-18 13:30:51.652  4683  4904 D BtGatt.GattService: registerClient() - UUID=465bc613-3aa8-4769-9c5f-71c78616b97c
,11-18 13:30:51.653  4683  4745 D BtGatt.GattService: onClientRegistered() - UUID=465bc613-3aa8-4769-9c5f-71c78616b97c, clientIf=5
11-18 13:30:51.653  5627  5637 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
,11-18 13:30:51.656  4683  4747 D BtGatt.AdvertiseManager: message : 0
,11-18 13:30:51.658  4683  4747 D BtGatt.AdvertiseManager: starting multi advertising
,11-18 13:30:51.675  4683  4745 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,11-18 13:30:51.682  4683  4745 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,11-18 13:30:51.684  5627  5674 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment Current thread: Thread[Thread-61,5,main], id: 61
,11-18 13:30:51.684  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTINGCurrent thread: Thread[Thread-61,5,main], id: 61
11-18 13:30:51.684  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
11-18 13:30:51.684  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged default (no call to listener). Current thread: Thread[Thread-61,5,main], id: 61
11-18 13:30:51.684  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-61,5,main], id: 61
11-18 13:30:51.684  5627  5674 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[Thread-61,5,main], id: 61
11-18 13:30:51.684  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[Thread-61,5,main], id: 61
11-18 13:30:51.684  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser started = true Current thread: Thread[Thread-61,5,main], id: 61
11-18 13:30:51.684  5627  5674 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-18 13:30:51.685  5627  5674 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,11-18 13:30:51.685  5627  5674 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-18 13:30:51.686  5627  5674 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-18 13:30:51.686  5627  5674 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-18 13:30:51.686  5627  5674 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-18 13:30:51.686  5627  5674 I io.jxcore.node.ConnectionHelper: start: OK
11-18 13:30:51.686  5627  5627 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,11-18 13:30:51.687  5627  5627 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess : Current thread: Thread[main,5,main], id: 1
,11-18 13:30:51.687  5627  5627 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNINGCurrent thread: Thread[main,5,main], id: 1
11-18 13:30:51.687  5627  5627 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
11-18 13:30:51.687  5627  5627 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  true. Current thread: Thread[main,5,main], id: 1
11-18 13:30:51.687  5627  5627 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[main,5,main], id: 1
11-18 13:30:51.688  5627  5627 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-18 13:30:51.688  5627  5627 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-18 13:30:51.688  5627  5627 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [ADVERTISING]
11-18 13:30:51.688  5627  5627 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-18 13:30:51.688  5627  5627 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-18 13:30:51.688  5627  5627 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]Current thread: Thread[main,5,main], id: 1
11-18 13:30:51.688  5627  5627 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
,11-18 13:30:51.688  5627  5627 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-18 13:30:51.691  5627  5627 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-18 13:30:51.691  5627  5627 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
11-18 13:30:51.691  5627  5627 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-18 13:30:51.692  5627  5627 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-18 13:30:51.692  5627  5627 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-18 13:30:51.692  5627  5627 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,11-18 13:30:52.189  5627  5674 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-18 13:30:52.189  5627  5674 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
11-18 13:30:52.190  5627  5674 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
11-18 13:30:52.190  5627  5674 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
,11-18 13:30:52.190  5627  5674 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
11-18 13:30:52.190  5627  5674 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
11-18 13:30:52.190  5627  5674 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
11-18 13:30:52.190  5627  5674 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
,11-18 13:30:52.190  5627  5674 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
11-18 13:30:52.191  5627  5674 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
11-18 13:30:52.191  5627  5674 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
11-18 13:30:52.191  5627  5674 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
,11-18 13:30:52.191  5627  5674 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
11-18 13:30:52.191  5627  5674 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
11-18 13:30:52.191  5627  5674 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
,11-18 13:30:52.191  5627  5674 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
11-18 13:30:52.191  5627  5674 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
,11-18 13:30:52.192  5627  5674 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
,11-18 13:30:52.192  5627  5674 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
11-18 13:30:52.192  5627  5674 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
,11-18 13:30:52.192  5627  5674 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
11-18 13:30:52.192  5627  5674 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
11-18 13:30:52.192  5627  5674 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
11-18 13:30:52.192  5627  5674 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
,11-18 13:30:52.192  5627  5674 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
11-18 13:30:52.193  5627  5674 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
11-18 13:30:52.193  5627  5674 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
,11-18 13:30:52.193  5627  5674 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
11-18 13:30:52.193  5627  5674 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
11-18 13:30:52.193  5627  5674 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
11-18 13:30:52.193  5627  5674 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
,11-18 13:30:52.193  5627  5674 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
11-18 13:30:52.194  5627  5674 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
11-18 13:30:52.193  5627  5627 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
,11-18 13:30:52.194  5627  5674 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
11-18 13:30:52.194  5627  5674 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
11-18 13:30:52.194  5627  5674 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
,11-18 13:30:52.194  5627  5674 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
11-18 13:30:52.194  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
11-18 13:30:52.195  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-18 13:30:52.195  5627  5674 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
11-18 13:30:52.195  5627  5674 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
,11-18 13:30:52.195  5627  5674 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
11-18 13:30:52.195  5627  5674 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-18 13:30:52.195  5627  5674 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
11-18 13:30:52.195  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-18 13:30:52.195  5627  5680 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
11-18 13:30:52.195  5627  5680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
11-18 13:30:52.196  5627  5680 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
11-18 13:30:52.196  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
11-18 13:30:52.196  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-61,5,main], id: 61
11-18 13:30:52.196  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-18 13:30:52.196  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-61,5,main], id: 61
11-18 13:30:52.198  5627  5674 D BluetoothAdapter: STATE_ON
11-18 13:30:52.198  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-18 13:30:52.199  5627  5674 D BluetoothAdapter: STATE_ON
11-18 13:30:52.199  5627  5674 D BluetoothLeScanner: could not find callback wrapper
11-18 13:30:52.199  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-18 13:30:52.199  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-18 13:30:52.199  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-61,5,main], id: 61
11-18 13:30:52.199  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-61,5,main], id: 61
11-18 13:30:52.200  5627  5674 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
11-18 13:30:52.200  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-61,5,main], id: 61
11-18 13:30:52.201  4683  4747 D BtGatt.AdvertiseManager: message : 1
11-18 13:30:52.202  4683  4747 D BtGatt.AdvertiseManager: stop advertise for client 5
11-18 13:30:52.216  4683  4745 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
11-18 13:30:52.216  4683  4745 D BtGatt.GattService: Client app is not null!
11-18 13:30:52.218  4683  4897 D BtGatt.GattService: unregisterClient() - clientIf=5
,11-18 13:30:52.219  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-18 13:30:52.219  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
11-18 13:30:52.220  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
11-18 13:30:52.220  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  false. Current thread: Thread[Thread-61,5,main], id: 61
,11-18 13:30:52.220  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-61,5,main], id: 61
11-18 13:30:52.220  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-61,5,main], id: 61
11-18 13:30:52.220  5627  5674 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-18 13:30:52.221  5627  5674 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,11-18 13:30:52.222  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-18 13:30:52.222  5627  5674 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-18 13:30:52.225  5627  5674 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-18 13:30:52.225  5627  5674 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-18 13:30:52.225  5627  5674 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-18 13:30:52.225  5627  5674 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
,11-18 13:30:52.225  5627  5627 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,11-18 13:30:52.226  5627  5627 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
11-18 13:30:52.228  5627  5627 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
11-18 13:30:52.228  5627  5627 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-18 13:30:52.228  5627  5627 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-18 13:30:52.228  5627  5627 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
11-18 13:30:52.228  5627  5627 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,11-18 13:30:52.228  5627  5674 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
11-18 13:30:52.228  5627  5627 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-18 13:30:52.228  5627  5674 V io.jxcore.node.ConnectivityMonitor: start: Already started
11-18 13:30:52.228  5627  5627 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-18 13:30:52.229  5627  5674 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 2
11-18 13:30:52.229  5627  5674 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 1 -> 2
,11-18 13:30:52.229  5627  5627 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-18 13:30:52.229  5627  5674 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-61,5,main], id: 61
11-18 13:30:52.229  5627  5627 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [ADVERTISING]
11-18 13:30:52.229  5627  5674 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-61,5,main], id: 61
11-18 13:30:52.229  5627  5627 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-18 13:30:52.229  5627  5674 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-61,5,main], id: 61
,11-18 13:30:52.229  5627  5674 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
11-18 13:30:52.229  5627  5674 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
11-18 13:30:52.229  5627  5627 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-18 13:30:52.229  5627  5674 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
11-18 13:30:52.229  5627  5627 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
11-18 13:30:52.229  5627  5674 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-18 13:30:52.230  5627  5627 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
,11-18 13:30:52.231  5627  5674 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
11-18 13:30:52.231  5627  5674 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
11-18 13:30:52.231  5627  5674 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
11-18 13:30:52.231  5627  5674 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
11-18 13:30:52.231  5627  5674 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
11-18 13:30:52.232  5627  5627 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-18 13:30:52.232  5627  5627 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-18 13:30:52.232  5627  5683 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
11-18 13:30:52.233  5627  5627 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-18 13:30:52.234  5627  5627 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-18 13:30:52.234  5627  5627 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-18 13:30:52.234  5627  5627 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
11-18 13:30:52.234  5627  5683 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-18 13:30:52.234  5627  5674 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
11-18 13:30:52.234  5627  5674 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-18 13:30:52.234  5627  5674 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
11-18 13:30:52.234  4897  4897 W Binder_3: type=1400 audit(0.0:115): avc: denied { ioctl } for path="socket:[32557]" dev="sockfs" ino=32557 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-18 13:30:52.234  4897  4897 W Binder_3: type=1400 audit(0.0:116): avc: denied { ioctl } for path="socket:[32557]" dev="sockfs" ino=32557 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-18 13:30:52.240  5627  5683 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
11-18 13:30:52.240  5627  5674 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-18 13:30:52.240  5627  5674 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-18 13:30:52.240  5627  5674 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
11-18 13:30:52.244  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-61,5,main], id: 61
11-18 13:30:52.245  5627  5674 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-18 13:30:52.245  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-18 13:30:52.245  5627  5674 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-18 13:30:52.245  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 2
11-18 13:30:52.248  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
11-18 13:30:52.248  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-61,5,main], id: 61
11-18 13:30:52.248  5627  5674 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
11-18 13:30:52.248  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: createAdvertiseDataToServiceData 
11-18 13:30:52.248  5627  5674 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-18 13:30:52.248  5627  5674 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 02 60 83 34 25 D7 D4
11-18 13:30:52.248  5627  5674 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[2, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-18 13:30:52.248  5627  5674 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: created AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[2, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-18 13:30:52.249  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: Current thread: Thread[Thread-61,5,main], id: 61
11-18 13:30:52.249  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: was started = false
11-18 13:30:52.249  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: advertiseData = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[2, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-18 13:30:52.249  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData finished: Current thread: Thread[Thread-61,5,main], id: 61
11-18 13:30:52.249  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
11-18 13:30:52.249  5627  5674 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... adv data = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[2, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]Current thread: Thread[Thread-61,5,main], id: 61
11-18 13:30:52.251  5627  5674 D BluetoothAdapter: STATE_ON
11-18 13:30:52.253  4683  4904 D BtGatt.GattService: registerClient() - UUID=a897102d-8213-49b2-9ee5-2d60405c1485
11-18 13:30:52.254  4683  4745 D BtGatt.GattService: onClientRegistered() - UUID=a897102d-8213-49b2-9ee5-2d60405c1485, clientIf=5
11-18 13:30:52.254  5627  5637 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
11-18 13:30:52.255  4683  4747 D BtGatt.AdvertiseManager: message : 0
11-18 13:30:52.257  4683  4747 D BtGatt.AdvertiseManager: starting multi advertising
11-18 13:30:52.268  4683  4745 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,11-18 13:30:52.274  4683  4745 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
11-18 13:30:52.274  5627  5674 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment Current thread: Thread[Thread-61,5,main], id: 61
11-18 13:30:52.274  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTINGCurrent thread: Thread[Thread-61,5,main], id: 61
11-18 13:30:52.274  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
11-18 13:30:52.275  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged default (no call to listener). Current thread: Thread[Thread-61,5,main], id: 61
11-18 13:30:52.275  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-61,5,main], id: 61
11-18 13:30:52.275  5627  5674 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[Thread-61,5,main], id: 61
11-18 13:30:52.275  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[Thread-61,5,main], id: 61
11-18 13:30:52.275  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser started = true Current thread: Thread[Thread-61,5,main], id: 61
11-18 13:30:52.275  5627  5674 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-18 13:30:52.276  5627  5674 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-18 13:30:52.276  5627  5674 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-18 13:30:52.277  5627  5674 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-18 13:30:52.278  5627  5674 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-18 13:30:52.278  5627  5674 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-18 13:30:52.278  5627  5674 I io.jxcore.node.ConnectionHelper: start: OK
11-18 13:30:52.278  5627  5627 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
11-18 13:30:52.278  5627  5627 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess : Current thread: Thread[main,5,main], id: 1
11-18 13:30:52.278  5627  5627 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNINGCurrent thread: Thread[main,5,main], id: 1
11-18 13:30:52.278  5627  5627 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
11-18 13:30:52.278  5627  5627 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  true. Current thread: Thread[main,5,main], id: 1
11-18 13:30:52.278  5627  5627 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[main,5,main], id: 1
11-18 13:30:52.279  5627  5627 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-18 13:30:52.279  5627  5627 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-18 13:30:52.279  5627  5627 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [ADVERTISING]
11-18 13:30:52.279  5627  5627 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-18 13:30:52.279  5627  5627 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-18 13:30:52.279  5627  5627 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]Current thread: Thread[main,5,main], id: 1
11-18 13:30:52.279  5627  5627 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
11-18 13:30:52.279  5627  5627 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-18 13:30:52.281  5627  5627 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-18 13:30:52.282  5627  5627 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
11-18 13:30:52.282  5627  5627 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-18 13:30:52.282  5627  5627 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-18 13:30:52.282  5627  5627 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-18 13:30:52.282  5627  5627 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,11-18 13:30:52.782  5627  5674 I io.jxcore.node.ConnectionHelperTest: Starting test: testStop
,11-18 13:30:52.782  5627  5674 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
,11-18 13:30:52.783  5627  5674 V io.jxcore.node.ConnectivityMonitor: start: Already started
,11-18 13:30:52.783  5627  5674 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,11-18 13:30:52.783  5627  5674 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 3
11-18 13:30:52.783  5627  5674 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 2 -> 3
11-18 13:30:52.783  5627  5627 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
,11-18 13:30:52.784  5627  5674 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-61,5,main], id: 61
,11-18 13:30:52.784  5627  5674 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-61,5,main], id: 61
,11-18 13:30:52.784  5627  5674 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-61,5,main], id: 61
,11-18 13:30:52.786  5627  5674 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
11-18 13:30:52.786  5627  5674 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Manufacturer ID: 7413
11-18 13:30:52.786  5627  5674 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad length and type: 533
11-18 13:30:52.786  5627  5674 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad extra information: 3
11-18 13:30:52.786  5627  5674 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
11-18 13:30:52.786  5627  5674 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 2
11-18 13:30:52.786  5627  5674 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 3
11-18 13:30:52.786  5627  5674 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 2
11-18 13:30:52.786  5627  5674 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
11-18 13:30:52.786  5627  5674 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Current thread: Thread[Thread-61,5,main], id: 61
11-18 13:30:52.786  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 3
,11-18 13:30:52.788  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: advertiserWasStarted true Current thread: Thread[Thread-61,5,main], id: 61
11-18 13:30:52.788  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: stop advertiser Current thread: Thread[Thread-61,5,main], id: 61
11-18 13:30:52.788  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-61,5,main], id: 61
11-18 13:30:52.796  4683  4747 D BtGatt.AdvertiseManager: message : 1
11-18 13:30:52.798  4683  4747 D BtGatt.AdvertiseManager: stop advertise for client 5
,11-18 13:30:52.807  4683  4745 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
,11-18 13:30:52.807  4683  4745 D BtGatt.GattService: Client app is not null!
11-18 13:30:52.808  4683  4897 D BtGatt.GattService: unregisterClient() - clientIf=5
11-18 13:30:52.809  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-18 13:30:52.809  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
,11-18 13:30:52.809  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
,11-18 13:30:52.809  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-61,5,main], id: 61
11-18 13:30:52.809  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-61,5,main], id: 61
11-18 13:30:52.809  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-61,5,main], id: 61
11-18 13:30:52.809  5627  5674 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-18 13:30:52.810  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: start advertiser Current thread: Thread[Thread-61,5,main], id: 61
11-18 13:30:52.810  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
11-18 13:30:52.810  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-61,5,main], id: 61
11-18 13:30:52.810  5627  5674 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
11-18 13:30:52.810  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: createAdvertiseDataToServiceData 
11-18 13:30:52.810  5627  5674 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-18 13:30:52.811  5627  5674 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 03 60 83 34 25 D7 D4
,11-18 13:30:52.811  5627  5674 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[3, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-18 13:30:52.811  5627  5674 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: created AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[3, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-18 13:30:52.811  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: Current thread: Thread[Thread-61,5,main], id: 61
,11-18 13:30:52.811  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: was started = false
11-18 13:30:52.811  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: advertiseData = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[3, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-18 13:30:52.811  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData finished: Current thread: Thread[Thread-61,5,main], id: 61
11-18 13:30:52.812  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
11-18 13:30:52.812  5627  5674 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... adv data = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[3, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]Current thread: Thread[Thread-61,5,main], id: 61
11-18 13:30:52.813  5627  5674 D BluetoothAdapter: STATE_ON
,11-18 13:30:52.819  4683  4897 D BtGatt.GattService: registerClient() - UUID=01b41489-ae2c-4d6a-84a8-f1238b0eaea3
,11-18 13:30:52.819  4683  4745 D BtGatt.GattService: onClientRegistered() - UUID=01b41489-ae2c-4d6a-84a8-f1238b0eaea3, clientIf=5
11-18 13:30:52.819  5627  5638 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
11-18 13:30:52.821  4683  4747 D BtGatt.AdvertiseManager: message : 0
,11-18 13:30:52.823  4683  4747 D BtGatt.AdvertiseManager: starting multi advertising
,11-18 13:30:52.832  4683  4745 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,11-18 13:30:52.838  4683  4745 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,11-18 13:30:52.839  5627  5674 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment Current thread: Thread[Thread-61,5,main], id: 61
11-18 13:30:52.839  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTINGCurrent thread: Thread[Thread-61,5,main], id: 61
,11-18 13:30:52.839  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
11-18 13:30:52.839  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged default (no call to listener). Current thread: Thread[Thread-61,5,main], id: 61
11-18 13:30:52.839  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-61,5,main], id: 61
11-18 13:30:52.839  5627  5674 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[Thread-61,5,main], id: 61
11-18 13:30:52.840  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[Thread-61,5,main], id: 61
11-18 13:30:52.840  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser started = true Current thread: Thread[Thread-61,5,main], id: 61
11-18 13:30:52.840  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: start advertiser started = true Current thread: Thread[Thread-61,5,main], id: 61
,11-18 13:30:52.840  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-18 13:30:52.840  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: scannerWasStarted false Current thread: Thread[Thread-61,5,main], id: 61
11-18 13:30:52.840  5627  5674 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-18 13:30:52.840  5627  5674 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
11-18 13:30:52.840  5627  5674 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-18 13:30:52.840  5627  5674 I io.jxcore.node.ConnectionHelper: start: OK
,11-18 13:30:52.841  5627  5627 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess : Current thread: Thread[main,5,main], id: 1
11-18 13:30:52.841  5627  5627 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNINGCurrent thread: Thread[main,5,main], id: 1
11-18 13:30:52.841  5627  5627 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
11-18 13:30:52.841  5627  5627 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  true. Current thread: Thread[main,5,main], id: 1
11-18 13:30:52.841  5627  5627 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[main,5,main], id: 1
11-18 13:30:52.841  5627  5627 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-18 13:30:52.841  5627  5627 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-18 13:30:52.842  5627  5674 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-18 13:30:52.842  5627  5627 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [ADVERTISING]
,11-18 13:30:52.842  5627  5627 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [ADVERTISING]
11-18 13:30:52.842  5627  5674 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
11-18 13:30:52.842  5627  5627 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-18 13:30:52.842  5627  5674 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
11-18 13:30:52.842  5627  5627 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-18 13:30:52.842  5627  5674 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
11-18 13:30:52.842  5627  5674 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
11-18 13:30:52.842  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
11-18 13:30:52.842  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,11-18 13:30:52.842  5627  5683 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
11-18 13:30:52.842  5627  5683 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
11-18 13:30:52.842  5627  5674 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
11-18 13:30:52.842  5627  5674 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
11-18 13:30:52.842  5627  5683 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
11-18 13:30:52.842  5627  5674 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
11-18 13:30:52.842  5627  5674 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,11-18 13:30:52.842  5627  5627 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
11-18 13:30:52.842  5627  5674 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
11-18 13:30:52.842  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-18 13:30:52.843  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
11-18 13:30:52.843  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-61,5,main], id: 61
11-18 13:30:52.843  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-18 13:30:52.843  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-61,5,main], id: 61
,11-18 13:30:52.844  5627  5674 D BluetoothAdapter: STATE_ON
11-18 13:30:52.844  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-18 13:30:52.845  5627  5674 D BluetoothAdapter: STATE_ON
,11-18 13:30:52.845  5627  5674 D BluetoothLeScanner: could not find callback wrapper
11-18 13:30:52.845  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-18 13:30:52.846  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-18 13:30:52.846  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-61,5,main], id: 61
11-18 13:30:52.846  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-61,5,main], id: 61
11-18 13:30:52.846  5627  5674 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
11-18 13:30:52.846  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-61,5,main], id: 61
,11-18 13:30:52.847  4683  4747 D BtGatt.AdvertiseManager: message : 1
,11-18 13:30:52.848  4683  4747 D BtGatt.AdvertiseManager: stop advertise for client 5
,11-18 13:30:52.854  4683  4745 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
11-18 13:30:52.854  4683  4745 D BtGatt.GattService: Client app is not null!
,11-18 13:30:52.855  4683  4698 D BtGatt.GattService: unregisterClient() - clientIf=5
,11-18 13:30:52.856  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-18 13:30:52.856  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
11-18 13:30:52.856  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
11-18 13:30:52.856  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  false. Current thread: Thread[Thread-61,5,main], id: 61
11-18 13:30:52.856  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-61,5,main], id: 61
,11-18 13:30:52.856  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-61,5,main], id: 61
11-18 13:30:52.856  5627  5674 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-18 13:30:52.856  5627  5674 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,11-18 13:30:52.857  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,11-18 13:30:52.857  5627  5674 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-18 13:30:52.859  5627  5674 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-18 13:30:52.859  5627  5674 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-18 13:30:52.859  5627  5674 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-18 13:30:52.859  5627  5674 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
,11-18 13:30:52.861  5627  5627 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,11-18 13:30:52.861  5627  5627 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
11-18 13:30:52.861  5627  5627 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
11-18 13:30:52.861  5627  5627 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-18 13:30:52.861  5627  5627 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-18 13:30:52.861  5627  5627 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-18 13:30:52.861  5627  5627 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-18 13:30:52.861  5627  5627 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
,11-18 13:30:52.861  5627  5627 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-18 13:30:52.861  5627  5627 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [ADVERTISING]
11-18 13:30:52.861  5627  5627 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-18 13:30:52.861  5627  5627 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-18 13:30:52.861  5627  5627 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
11-18 13:30:52.861  5627  5627 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-18 13:30:52.862  5627  5627 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-18 13:30:52.863  5627  5627 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-18 13:30:52.863  5627  5627 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
,11-18 13:30:52.863  5627  5627 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-18 13:30:52.863  5627  5627 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,11-18 13:30:52.865  5627  5674 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnPeerReadyToProvideBluetoothMacAddress
11-18 13:30:52.865  5627  5674 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
11-18 13:30:52.866  5627  5674 I io.jxcore.node.ConnectionHelperTest: Starting test: testKillAllConnections
,11-18 13:30:52.866  5627  5674 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
11-18 13:30:52.867  5627  5674 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnConnectionManagerStateChanged
11-18 13:30:52.867  5627  5674 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
,11-18 13:30:52.868  5627  5674 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnPermissionCheckRequired
11-18 13:30:52.868  5627  5674 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
11-18 13:30:52.869  5627  5674 I io.jxcore.node.ConnectionHelperTest: Starting test: testToggleBetweenSystemDecidedAndAlternativeInsecureRfcommPortNumber
,11-18 13:30:52.869  5627  5674 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
11-18 13:30:52.869  5627  5674 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-18 13:30:52.869  5627  5674 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-18 13:30:52.869  5627  5674 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-18 13:30:52.869  5627  5674 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
11-18 13:30:52.869  5627  5674 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-18 13:30:52.870  5627  5674 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-18 13:30:52.870  5627  5674 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-18 13:30:52.870  5627  5674 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
11-18 13:30:52.870  5627  5674 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-18 13:30:52.870  5627  5674 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,11-18 13:30:52.870  5627  5674 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-18 13:30:52.871  5627  5674 I io.jxcore.node.ConnectionHelperTest: Starting test: testConnect
,11-18 13:30:52.871  5627  5674 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
11-18 13:30:52.872  5627  5674 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
,11-18 13:30:52.875  5627  5674 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnProvideBluetoothMacAddressRequest
11-18 13:30:52.875  5627  5674 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
,11-18 13:30:52.876  5627  5674 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnDiscoveryManagerStateChanged
,11-18 13:30:52.876  5627  5674 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
11-18 13:30:52.877  5627  5674 I io.jxcore.node.ConnectionHelperTest: Starting test: testDisconnectOutgoingConnection
11-18 13:30:52.877  5627  5674 E io.jxcore.node.ConnectionModel: addConnectionThread: A matching thread for outgoing connection already exists
11-18 13:30:52.877  5627  5674 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
11-18 13:30:52.877  5627  5674 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
11-18 13:30:52.877  5627  5674 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
11-18 13:30:52.878  5627  5674 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
11-18 13:30:52.878  5627  5674 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
11-18 13:30:52.878  5627  5674 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
11-18 13:30:52.878  5627  5674 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
11-18 13:30:52.878  5627  5674 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
11-18 13:30:52.878  5627  5674 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
11-18 13:30:52.878  5627  5674 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
11-18 13:30:52.878  5627  5674 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
11-18 13:30:52.878  5627  5674 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
11-18 13:30:52.879  5627  5674 I io.jxcore.node.ConnectionHelperTest: Starting test: testDispose
11-18 13:30:52.879  5627  5674 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
11-18 13:30:52.879  5627  5674 V io.jxcore.node.ConnectivityMonitor: start: Already started
11-18 13:30:52.879  5627  5674 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 4
11-18 13:30:52.879  5627  5674 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 3 -> 4
11-18 13:30:52.879  5627  5674 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-61,5,main], id: 61
11-18 13:30:52.879  5627  5674 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-61,5,main], id: 61
11-18 13:30:52.879  5627  5674 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-61,5,main], id: 61
11-18 13:30:52.879  5627  5674 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
11-18 13:30:52.879  5627  5674 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
11-18 13:30:52.879  5627  5674 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
11-18 13:30:52.879  5627  5674 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-18 13:30:52.880  5627  5674 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
11-18 13:30:52.881  5627  5674 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
11-18 13:30:52.881  5627  5674 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
11-18 13:30:52.881  5627  5674 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
11-18 13:30:52.881  5627  5674 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
11-18 13:30:52.881  5627  5674 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
11-18 13:30:52.881  5627  5674 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-18 13:30:52.881  5627  5627 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
11-18 13:30:52.881  5627  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
11-18 13:30:52.881  5627  5674 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
11-18 13:30:52.882  5627  5687 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-18 13:30:52.880  4897  4897 W Binder_3: type=1400 audit(0.0:117): avc: denied { ioctl } for path="socket:[33111]" dev="sockfs" ino=33111 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-18 13:30:52.880  4897  4897 W Binder_3: type=1400 audit(0.0:118): avc: denied { ioctl } for path="socket:[33111]" dev="sockfs" ino=33111 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-18 13:30:52.885  5627  5687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
11-18 13:30:52.886  5627  5674 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-18 13:30:52.886  5627  5674 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-18 13:30:52.886  5627  5674 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
11-18 13:30:52.890  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-61,5,main], id: 61
11-18 13:30:52.890  5627  5674 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,11-18 13:30:52.891  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-18 13:30:52.891  5627  5674 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-18 13:30:52.891  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 4
11-18 13:30:52.894  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
11-18 13:30:52.894  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-61,5,main], id: 61
11-18 13:30:52.894  5627  5674 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
11-18 13:30:52.894  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: createAdvertiseDataToServiceData 
11-18 13:30:52.894  5627  5674 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-18 13:30:52.894  5627  5674 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 04 60 83 34 25 D7 D4
11-18 13:30:52.894  5627  5674 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[4, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-18 13:30:52.895  5627  5674 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: created AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[4, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-18 13:30:52.895  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: Current thread: Thread[Thread-61,5,main], id: 61
11-18 13:30:52.895  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: was started = false
11-18 13:30:52.895  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: advertiseData = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[4, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-18 13:30:52.895  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData finished: Current thread: Thread[Thread-61,5,main], id: 61
11-18 13:30:52.895  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
11-18 13:30:52.895  5627  5674 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... adv data = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[4, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]Current thread: Thread[Thread-61,5,main], id: 61
,11-18 13:30:52.896  5627  5674 D BluetoothAdapter: STATE_ON
,11-18 13:30:52.899  4683  4897 D BtGatt.GattService: registerClient() - UUID=dcf5494d-41d4-48da-bec3-7231194a8026
,11-18 13:30:52.899  4683  4745 D BtGatt.GattService: onClientRegistered() - UUID=dcf5494d-41d4-48da-bec3-7231194a8026, clientIf=5
,11-18 13:30:52.900  5627  5638 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
,11-18 13:30:52.900  4683  4747 D BtGatt.AdvertiseManager: message : 0
,11-18 13:30:52.903  4683  4747 D BtGatt.AdvertiseManager: starting multi advertising
,11-18 13:30:52.914  4683  4745 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,11-18 13:30:52.919  4683  4745 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,11-18 13:30:52.919  5627  5674 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment Current thread: Thread[Thread-61,5,main], id: 61
11-18 13:30:52.919  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTINGCurrent thread: Thread[Thread-61,5,main], id: 61
11-18 13:30:52.919  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
11-18 13:30:52.920  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged default (no call to listener). Current thread: Thread[Thread-61,5,main], id: 61
,11-18 13:30:52.920  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-61,5,main], id: 61
11-18 13:30:52.920  5627  5674 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[Thread-61,5,main], id: 61
11-18 13:30:52.920  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[Thread-61,5,main], id: 61
11-18 13:30:52.920  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser started = true Current thread: Thread[Thread-61,5,main], id: 61
11-18 13:30:52.920  5627  5674 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,11-18 13:30:52.921  5627  5674 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-18 13:30:52.921  5627  5674 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-18 13:30:52.922  5627  5674 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-18 13:30:52.922  5627  5674 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-18 13:30:52.922  5627  5674 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-18 13:30:52.922  5627  5674 I io.jxcore.node.ConnectionHelper: start: OK
11-18 13:30:52.923  5627  5627 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,11-18 13:30:52.923  5627  5627 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess : Current thread: Thread[main,5,main], id: 1
11-18 13:30:52.923  5627  5627 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNINGCurrent thread: Thread[main,5,main], id: 1
11-18 13:30:52.923  5627  5627 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
11-18 13:30:52.923  5627  5627 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  true. Current thread: Thread[main,5,main], id: 1
11-18 13:30:52.923  5627  5627 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[main,5,main], id: 1
,11-18 13:30:52.923  5627  5627 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-18 13:30:52.923  5627  5627 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-18 13:30:52.923  5627  5627 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [ADVERTISING]
11-18 13:30:52.923  5627  5627 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-18 13:30:52.923  5627  5627 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-18 13:30:52.923  5627  5627 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]Current thread: Thread[main,5,main], id: 1
11-18 13:30:52.923  5627  5627 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
11-18 13:30:52.923  5627  5627 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
,11-18 13:30:52.926  5627  5627 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-18 13:30:52.926  5627  5627 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
11-18 13:30:52.926  5627  5627 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
,11-18 13:30:52.926  5627  5627 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-18 13:30:52.926  5627  5627 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-18 13:30:52.926  5627  5627 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,11-18 13:30:53.424  5627  5674 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-18 13:30:53.424  5627  5674 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
11-18 13:30:53.424  5627  5674 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
,11-18 13:30:53.425  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
11-18 13:30:53.425  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-18 13:30:53.425  5627  5674 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
11-18 13:30:53.425  5627  5674 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
11-18 13:30:53.425  5627  5687 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
11-18 13:30:53.426  5627  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
,11-18 13:30:53.426  5627  5674 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-18 13:30:53.426  5627  5687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
11-18 13:30:53.426  5627  5674 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@97a7583 removed from the list
11-18 13:30:53.426  5627  5674 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-18 13:30:53.426  5627  5674 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,11-18 13:30:53.426  5627  5627 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
11-18 13:30:53.426  5627  5674 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
11-18 13:30:53.427  5627  5627 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
11-18 13:30:53.427  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,11-18 13:30:53.427  5627  5627 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-18 13:30:53.427  5627  5627 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
11-18 13:30:53.427  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
11-18 13:30:53.427  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-61,5,main], id: 61
,11-18 13:30:53.428  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-18 13:30:53.428  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-61,5,main], id: 61
11-18 13:30:53.430  5627  5674 D BluetoothAdapter: STATE_ON
11-18 13:30:53.430  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
,11-18 13:30:53.432  5627  5674 D BluetoothAdapter: STATE_ON
11-18 13:30:53.432  5627  5674 D BluetoothLeScanner: could not find callback wrapper
11-18 13:30:53.433  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-18 13:30:53.433  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-18 13:30:53.433  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-61,5,main], id: 61
,11-18 13:30:53.433  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-61,5,main], id: 61
11-18 13:30:53.434  5627  5674 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
11-18 13:30:53.434  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-61,5,main], id: 61
11-18 13:30:53.436  4683  4747 D BtGatt.AdvertiseManager: message : 1
,11-18 13:30:53.438  4683  4747 D BtGatt.AdvertiseManager: stop advertise for client 5
,11-18 13:30:53.450  4683  4745 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
11-18 13:30:53.451  4683  4745 D BtGatt.GattService: Client app is not null!
,11-18 13:30:53.452  4683  4698 D BtGatt.GattService: unregisterClient() - clientIf=5
,11-18 13:30:53.453  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,11-18 13:30:53.453  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
11-18 13:30:53.453  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
11-18 13:30:53.453  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  false. Current thread: Thread[Thread-61,5,main], id: 61
11-18 13:30:53.454  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-61,5,main], id: 61
11-18 13:30:53.454  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-61,5,main], id: 61
11-18 13:30:53.454  5627  5674 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-18 13:30:53.454  5627  5674 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-18 13:30:53.455  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-18 13:30:53.455  5627  5674 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-18 13:30:53.456  5627  5674 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-18 13:30:53.458  5627  5674 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-18 13:30:53.458  5627  5674 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-18 13:30:53.458  5627  5674 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-18 13:30:53.458  5627  5674 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f442300 removed from the list
11-18 13:30:53.458  5627  5627 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-18 13:30:53.458  5627  5674 D io.jxcore.node.ConnectivityMonitor: stop
11-18 13:30:53.458  5627  5627 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,11-18 13:30:53.458  5627  5674 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
11-18 13:30:53.458  5627  5627 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-18 13:30:53.459  5627  5627 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-18 13:30:53.459  5627  5627 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-18 13:30:53.459  5627  5627 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [ADVERTISING]
11-18 13:30:53.459  5627  5627 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-18 13:30:53.459  5627  5627 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
,11-18 13:30:53.459  5627  5627 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
11-18 13:30:53.459  5627  5627 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-18 13:30:53.461  5627  5627 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-18 13:30:53.461  5627  5627 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-18 13:30:53.461  5627  5627 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-18 13:30:53.462  5627  5627 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
,11-18 13:30:53.462  5627  5627 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,11-18 13:30:53.963  5627  5627 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-18 13:30:58.463  5627  5674 I io.jxcore.node.ConnectionHelperTest: Starting test: testIsRunning
,11-18 13:30:58.467  5627  5674 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
,11-18 13:30:58.467  5627  5674 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,11-18 13:30:58.468  5627  5674 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
,11-18 13:30:58.473  5627  5674 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,11-18 13:30:58.474  5627  5674 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,11-18 13:30:58.474  5627  5674 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
11-18 13:30:58.474  5627  5674 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
11-18 13:30:58.475  5627  5674 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
,11-18 13:30:58.475  5627  5674 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
11-18 13:30:58.475  5627  5627 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
11-18 13:30:58.475  5627  5688 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
11-18 13:30:58.477  5627  5688 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-18 13:30:58.477  5627  5674 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnConnectionFailed
,11-18 13:30:58.477  4698  4698 W Binder_2: type=1400 audit(0.0:119): avc: denied { ioctl } for path="socket:[33118]" dev="sockfs" ino=33118 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,11-18 13:30:58.477  4698  4698 W Binder_2: type=1400 audit(0.0:120): avc: denied { ioctl } for path="socket:[33118]" dev="sockfs" ino=33118 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-18 13:30:58.479  5627  5674 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
11-18 13:30:58.479  5627  5674 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
,11-18 13:30:58.480  5627  5674 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
11-18 13:30:58.480  5627  5674 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-18 13:30:58.480  5627  5674 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-18 13:30:58.482  5627  5674 I io.jxcore.node.ConnectionHelperTest: Starting test: testGetConnectivityMonitorGetDiscoveryManagerGetConnectionModelGetBluetoothName
11-18 13:30:58.485  5627  5688 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,11-18 13:30:58.489  5627  5674 I io.jxcore.node.ConnectionHelperTest: Starting test: testConstructor
11-18 13:30:58.489  5627  5674 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-18 13:30:58.489  5627  5674 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
11-18 13:30:58.489  5627  5674 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
11-18 13:30:58.489  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
11-18 13:30:58.490  5627  5674 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
,11-18 13:30:58.490  5627  5688 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
11-18 13:30:58.490  5627  5688 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
11-18 13:30:58.490  5627  5688 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
11-18 13:30:58.490  5627  5627 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
11-18 13:30:58.491  5627  5674 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-18 13:30:58.491  5627  5674 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
,11-18 13:30:58.492  5627  5627 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-18 13:30:58.492  5627  5674 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@97a7583 not in the list
11-18 13:30:58.492  5627  5627 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
11-18 13:30:58.492  5627  5674 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-18 13:30:58.493  5627  5674 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-18 13:30:58.493  5627  5674 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
11-18 13:30:58.493  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,11-18 13:30:58.493  5627  5674 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-18 13:30:58.495  5627  5674 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-18 13:30:58.495  5627  5674 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-18 13:30:58.496  5627  5674 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-18 13:30:58.496  5627  5674 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-18 13:30:58.496  5627  5674 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f442300 not in the list
11-18 13:30:58.496  5627  5627 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-18 13:30:58.496  5627  5674 D io.jxcore.node.ConnectivityMonitor: stop
11-18 13:30:58.496  5627  5627 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,11-18 13:30:58.496  5627  5627 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-18 13:30:58.497  5627  5674 I io.jxcore.node.ConnectionModelTest: Starting test: testGetNumberOfCurrentOutgoingConnections
11-18 13:30:58.498  5627  5674 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
11-18 13:30:58.498  5627  5674 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
11-18 13:30:58.499  5627  5674 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
11-18 13:30:58.499  5627  5674 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
11-18 13:30:58.499  5627  5674 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
,11-18 13:30:58.499  5627  5674 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
11-18 13:30:58.500  5627  5674 I io.jxcore.node.ConnectionModelTest: Starting test: constructorTest
11-18 13:30:58.500  5627  5674 I io.jxcore.node.ConnectionModelTest: Starting test: testHasIncomingConnection
11-18 13:30:58.502  5627  5674 I io.jxcore.node.ConnectionModelTest: Starting test: testGetNumberOfCurrentConnections
11-18 13:30:58.502  5627  5674 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
11-18 13:30:58.503  5627  5674 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
,11-18 13:30:58.504  5627  5674 I io.jxcore.node.ConnectionModelTest: Starting test: testGetNumberOfCurrentIncomingConnections
,11-18 13:30:58.504  5627  5674 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
11-18 13:30:58.504  5627  5674 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
11-18 13:30:58.504  5627  5674 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
11-18 13:30:58.504  5627  5674 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
11-18 13:30:58.504  5627  5674 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
11-18 13:30:58.504  5627  5674 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
,11-18 13:30:58.505  5627  5674 I io.jxcore.node.ConnectionModelTest: Starting test: testGetOutgoingConnectionCallbackByBluetoothMacAddress
11-18 13:30:58.506  5627  5674 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
11-18 13:30:58.506  5627  5674 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
,11-18 13:30:58.507  5627  5674 I io.jxcore.node.ConnectionModelTest: Starting test: testHasConnection
,11-18 13:30:58.507  5627  5674 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
11-18 13:30:58.507  5627  5674 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
11-18 13:30:58.507  5627  5674 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
11-18 13:30:58.507  5627  5674 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
11-18 13:30:58.508  5627  5674 I io.jxcore.node.ConnectionModelTest: Starting test: testHasOutgoingConnection
11-18 13:30:58.508  5627  5674 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-18 13:30:58.508  5627  5674 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6c6362e added. We now have 3 listener(s)
11-18 13:30:58.510  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-18 13:30:58.510  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,11-18 13:30:58.510  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-18 13:30:58.510  5627  5674 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,11-18 13:30:58.511  5627  5674 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c7b45cf added. We now have 3 listener(s)
11-18 13:30:58.511  5627  5674 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-18 13:30:58.511  5627  5674 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,11-18 13:30:58.514  5627  5674 D BluetoothAdapter: enable(): BT is already enabled..!
11-18 13:30:58.515   930  3191 D WifiService: setWifiEnabled: true pid=5627, uid=10077
11-18 13:30:58.515   930  3191 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-18 13:30:58.516  5627  5674 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testIsBleMultipleAdvertisementSupported
,11-18 13:30:58.519  5627  5674 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testIsBluetoothSupported
11-18 13:30:58.520  5627  5674 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testStartStop
,11-18 13:30:58.523  5627  5674 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testIsWifiDirectSupported
11-18 13:30:58.523  5627  5674 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testIsBluetoothEnabled
,11-18 13:30:58.528  5627  5674 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-18 13:30:58.528  5627  5674 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-18 13:30:58.528  5627  5674 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-18 13:30:58.528  5627  5674 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-18 13:30:58.528  5627  5674 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-18 13:30:58.528  5627  5674 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-18 13:30:58.528  5627  5674 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-18 13:30:58.528  5627  5674 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-18 13:30:58.528  5627  5674 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
11-18 13:30:58.528  4683  4741 D BluetoothAdapterState: Current state: ON, message: 23
,11-18 13:30:58.528  4683  4741 D BluetoothAdapterProperties: Setting state to 13
11-18 13:30:58.528  4683  4741 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
11-18 13:30:58.528  4683  4741 D BluetoothAdapterProperties: onBluetoothDisable()
11-18 13:30:58.528  5627  5674 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-18 13:30:58.529  5627  5674 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
11-18 13:30:58.529  4683  4741 I BluetoothAdapterState: Entering PendingCommandState
,11-18 13:30:58.530  4683  4745 D BluetoothAdapterProperties: Scan Mode:20
11-18 13:30:58.530  4683  4741 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
,11-18 13:30:58.532  4683  4683 D BluetoothMapService: onReceive
11-18 13:30:58.532  4683  4683 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,11-18 13:30:58.533  4683  4683 D BluetoothMapService: STATE_TURNING_OFF
11-18 13:30:58.533  4683  4683 D BluetoothMapService: MAP Service closeService in
11-18 13:30:58.533  4683  4683 D BluetoothMapMasInstance0: MAP Service shutdown
11-18 13:30:58.534  4683  4683 D ObexServerSockets0: shutdown(block = true)
11-18 13:30:58.535  4683  4683 D ObexServerSockets0: shutdown called from another thread - interrupt().
11-18 13:30:58.535  4683  4683 D ObexServerSockets0: shutdown called from another thread - interrupt().
11-18 13:30:58.535  4683  4882 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
,11-18 13:30:58.535  4683  4906 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 5
11-18 13:30:58.536  4683  4907 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
11-18 13:30:58.538  4683  4683 D HeadsetService: Received stop request...Stopping profile...
11-18 13:30:58.539  5310  5310 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
11-18 13:30:58.543   930   930 D BluetoothHeadset: Proxy object disconnected
11-18 13:30:58.543  3791  4016 D BluetoothHeadset: Proxy object disconnected
11-18 13:30:58.543   930   930 D BluetoothHeadset: Proxy object disconnected
11-18 13:30:58.544  4683  4683 D A2dpService: Received stop request...Stopping profile...
11-18 13:30:58.544  4683  4899 D A2dpStateMachine: Exit Disconnected: -1
,11-18 13:30:58.544  5310  5321 D BluetoothHeadset: Proxy object disconnected
,11-18 13:30:58.545  3163  3180 D BluetoothHeadset: Proxy object disconnected
11-18 13:30:58.546   930   930 D BluetoothHeadset: Proxy object disconnected
11-18 13:30:58.546   930   930 D BluetoothA2dp: Proxy object disconnected
,11-18 13:30:58.548  4683  4683 I BtOppRfcommListener: stopping Accept Thread
11-18 13:30:58.548  4683  5330 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
11-18 13:30:58.549  4683  5330 I BtOppRfcommListener: BluetoothSocket listen thread finished
11-18 13:30:58.550  5310  5310 D DockEventReceiver: finishStartingService: stopping service
,11-18 13:30:58.552  5310  5310 D HeadsetProfile: Bluetooth service disconnected
11-18 13:30:58.552  5310  5310 D BluetoothA2dp: Proxy object disconnected
,11-18 13:30:58.552  3163  3163 D HeadsetProfile: Bluetooth service disconnected
11-18 13:30:58.553  3163  3163 D BluetoothA2dp: Proxy object disconnected
11-18 13:30:58.553   930  3727 I ActivityManager: Killing 5084:com.google.android.apps.maps/u0a58 (adj 15): empty #17
,11-18 13:30:58.555  4683  4683 D HidService: Received stop request...Stopping profile...
,11-18 13:30:58.556  4683  4683 D HidService: Stopping Bluetooth HidService
,11-18 13:30:58.577  5310  5310 D BluetoothInputDevice: Proxy object disconnected
11-18 13:30:58.577  5310  5310 D HidProfile: Bluetooth service disconnected
11-18 13:30:58.577  3163  3163 D BluetoothInputDevice: Proxy object disconnected
11-18 13:30:58.577  3163  3163 D HidProfile: Bluetooth service disconnected
,11-18 13:30:58.577  4683  4683 D HealthService: Received stop request...Stopping profile...
,11-18 13:30:58.578  4683  4683 D PanService: Received stop request...Stopping profile...
,11-18 13:30:58.579  4683  4683 D BluetoothMapService: Received stop request...Stopping profile...
11-18 13:30:58.579  3163  3163 D BluetoothPan: BluetoothPAN Proxy object disconnected
11-18 13:30:58.580  3163  3163 D PanProfile: Bluetooth service disconnected
11-18 13:30:58.580  4683  4683 D BluetoothMapService: stop()
11-18 13:30:58.580  4683  4683 D BluetoothMapAppObserver: deinitObservers()
11-18 13:30:58.580  4683  4683 D BluetoothMapAppObserver: removeReceiver()
11-18 13:30:58.581  4683  4683 V BluetoothAdapterState: isTurningOff()=true
11-18 13:30:58.581  4683  4683 V BluetoothAdapterState: isTurningOn()=false
11-18 13:30:58.581  4683  4683 V BluetoothAdapterState: isBleTurningOn()=false
,11-18 13:30:58.581  4683  4683 V BluetoothAdapterState: isBleTurningOff()=false
11-18 13:30:58.582  3163  3163 D BluetoothMap: Proxy object disconnected
11-18 13:30:58.582  3163  3163 D MapProfile: Bluetooth service disconnected
11-18 13:30:58.582  4683  4683 D SapService: Received stop request...Stopping profile...
11-18 13:30:58.582  4683  4683 V SapService: stop()
11-18 13:30:58.583  5310  5310 D BluetoothPan: BluetoothPAN Proxy object disconnected
11-18 13:30:58.583  5310  5310 D PanProfile: Bluetooth service disconnected
11-18 13:30:58.583  5310  5310 D BluetoothMap: Proxy object disconnected
11-18 13:30:58.583  5310  5310 D MapProfile: Bluetooth service disconnected
,11-18 13:30:58.585  4683  4683 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
,11-18 13:30:58.585  4683  4683 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
11-18 13:30:58.585  4683  4872 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-18 13:30:58.585  4683  4872 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-18 13:30:58.585  4683  4872 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-18 13:30:58.586  4683  4745 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
11-18 13:30:58.586  4683  4683 V BluetoothAdapterState: isTurningOff()=true
11-18 13:30:58.586  4683  4683 V BluetoothAdapterState: isTurningOn()=false
11-18 13:30:58.586  4683  4683 V BluetoothAdapterState: isBleTurningOn()=false
11-18 13:30:58.586  4683  4683 V BluetoothAdapterState: isBleTurningOff()=false
11-18 13:30:58.588  4683  4745 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
11-18 13:30:58.588  4683  4745 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
11-18 13:30:58.588  4683  4872 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-18 13:30:58.588  4683  4872 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-18 13:30:58.588  4683  4872 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
11-18 13:30:58.588  4683  4872 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
11-18 13:30:58.588  4683  4872 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
11-18 13:30:58.588  4683  4872 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
11-18 13:30:58.588  3610  3610 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,11-18 13:30:58.591  4683  4683 V BluetoothAdapterState: isTurningOff()=true
,11-18 13:30:58.591  4683  4683 V BluetoothAdapterState: isTurningOn()=false
11-18 13:30:58.591  4683  4683 V BluetoothAdapterState: isBleTurningOn()=false
11-18 13:30:58.591  4683  4683 V BluetoothAdapterState: isBleTurningOff()=false
,11-18 13:30:58.591  4683  4683 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
11-18 13:30:58.591  4683  4683 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
11-18 13:30:58.591  4683  4683 V BluetoothAdapterState: isTurningOff()=true
,11-18 13:30:58.591  4683  4683 V BluetoothAdapterState: isTurningOn()=false
11-18 13:30:58.591  4683  4683 V BluetoothAdapterState: isBleTurningOn()=false
11-18 13:30:58.591  4683  4683 V BluetoothAdapterState: isBleTurningOff()=false
11-18 13:30:58.591  4683  4745 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
11-18 13:30:58.591  4683  4683 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
11-18 13:30:58.592  4683  4745 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
11-18 13:30:58.592  4683  4683 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
11-18 13:30:58.592  4683  4683 V BluetoothAdapterState: isTurningOff()=true
11-18 13:30:58.592  4683  4683 V BluetoothAdapterState: isTurningOn()=false
11-18 13:30:58.592  4683  4683 V BluetoothAdapterState: isBleTurningOn()=false
,11-18 13:30:58.592  4683  4683 V BluetoothAdapterState: isBleTurningOff()=false
11-18 13:30:58.592  4683  4683 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
11-18 13:30:58.592  4683  4683 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
11-18 13:30:58.593  4683  4683 D BluetoothMapService: MAP Service closeService in
11-18 13:30:58.593  4683  4683 V BluetoothAdapterState: isTurningOff()=true
11-18 13:30:58.593  4683  4683 V BluetoothAdapterState: isTurningOn()=false
11-18 13:30:58.593  4683  4683 V BluetoothAdapterState: isBleTurningOn()=false
11-18 13:30:58.593  4683  4683 V BluetoothAdapterState: isBleTurningOff()=false
11-18 13:30:58.594  4683  4683 D BluetoothMapService: cleanup()
11-18 13:30:58.594  4683  4683 D BluetoothMapService: MAP Service closeService in
,11-18 13:30:58.594  4683  4683 V BluetoothAdapterState: isTurningOff()=true
11-18 13:30:58.594  4683  4683 V BluetoothAdapterState: isTurningOn()=false
11-18 13:30:58.594  4683  4683 V BluetoothAdapterState: isBleTurningOn()=false
11-18 13:30:58.594  4683  4683 V BluetoothAdapterState: isBleTurningOff()=false
11-18 13:30:58.594  4683  4741 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
11-18 13:30:58.594  4683  4741 D BluetoothAdapterProperties: Setting state to 15
11-18 13:30:58.594  4683  4741 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
11-18 13:30:58.595  5310  5320 D BluetoothMap: onBluetoothStateChange: up=false
11-18 13:30:58.596  4683  4741 I BluetoothAdapterState: Entering BleOnState
11-18 13:30:58.596  5310  5310 D BluetoothPbap: Proxy object disconnected
11-18 13:30:58.596  5310  5310 D PbapServerProfile: Bluetooth service disconnected
11-18 13:30:58.596  3163  3163 D BluetoothPbap: Proxy object disconnected
11-18 13:30:58.596  3163  3163 D PbapServerProfile: Bluetooth service disconnected
11-18 13:30:58.596  3163  3909 D BluetoothInputDevice: onBluetoothStateChange: up=false
,11-18 13:30:58.599  5310  5321 D BluetoothHeadset: onBluetoothStateChange: up=false
,11-18 13:30:58.600  5310  5320 D BluetoothA2dp: onBluetoothStateChange: up=false
,11-18 13:30:58.609   930  3823 I ActivityManager: Start proc 5694:com.google.android.apps.maps/u0a58 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
11-18 13:30:58.610  3163  3174 D BluetoothMap: onBluetoothStateChange: up=false
11-18 13:30:58.611  5310  5693 D BluetoothPbap: onBluetoothStateChange: up=false
11-18 13:30:58.611  5310  5321 D BluetoothPan: onBluetoothStateChange on: false
11-18 13:30:58.612   930   947 D BluetoothHeadset: onBluetoothStateChange: up=false
11-18 13:30:58.612   930   947 D BluetoothHeadset: onBluetoothStateChange: up=false
11-18 13:30:58.612   930   947 D BluetoothA2dp: onBluetoothStateChange: up=false
11-18 13:30:58.612  3791  3803 D BluetoothHeadset: onBluetoothStateChange: up=false
11-18 13:30:58.612   930   947 D BluetoothHeadset: onBluetoothStateChange: up=false
11-18 13:30:58.613  5310  5320 D BluetoothInputDevice: onBluetoothStateChange: up=false
,11-18 13:30:58.613  3163  3180 D BluetoothHeadset: onBluetoothStateChange: up=false
11-18 13:30:58.613  3163  4017 D BluetoothPbap: onBluetoothStateChange: up=false
11-18 13:30:58.614  3163  3909 D BluetoothA2dp: onBluetoothStateChange: up=false
11-18 13:30:58.614  3163  3174 D BluetoothPan: onBluetoothStateChange on: false
11-18 13:30:58.615  4683  4741 D BluetoothAdapterState: Current state: BLE ON, message: 20
11-18 13:30:58.615  4683  4741 D BluetoothAdapterProperties: Setting state to 16
11-18 13:30:58.615  4683  4741 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
11-18 13:30:58.616  4683  4741 D BluetoothAdapterProperties: onBleDisable
11-18 13:30:58.616  4683  4741 I BluetoothAdapterState: Entering PendingCommandState
,11-18 13:30:58.616  4683  4742 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
11-18 13:30:58.618  4683  4872 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
11-18 13:30:58.618  4683  4872 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-18 13:30:58.618  4683  4745 D BluetoothAdapterProperties: Scan Mode:20
,11-18 13:30:58.667  5694  5694 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm64
,11-18 13:30:58.822  4683  4745 I bt_hci  : shut_down
,11-18 13:30:58.827  4683  4749 I bt_vendor: low_power_mode_cb
,11-18 13:30:58.832  4683  4749 D bt_hwcfg: hw_epilog_process
,11-18 13:30:58.835  4683  4749 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
11-18 13:30:58.835  4683  4749 I bt_vendor: epilog_cb
11-18 13:30:58.835  4683  4749 I bt_hci  : epilog_finished_callback
,11-18 13:30:58.837  4683  4745 I bt_hci_h4: hal_close
,11-18 13:30:58.838  4683  4745 I bt_userial_vendor: device fd = 54 close
,11-18 13:30:58.850  5694  5694 D StrictMode: StrictMode policy violation; ~duration=125 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-18 13:30:58.850  5694  5694 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-18 13:30:58.850  5694  5694 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
11-18 13:30:58.850  5694  5694 D StrictMode: 	at java.io.File.doAccess(File.java:281)
11-18 13:30:58.850  5694  5694 D StrictMode: 	at java.io.File.exists(File.java:361)
11-18 13:30:58.850  5694  5694 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
11-18 13:30:58.850  5694  5694 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
11-18 13:30:58.850  5694  5694 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
11-18 13:30:58.850  5694  5694 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
11-18 13:30:58.850  5694  5694 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
11-18 13:30:58.850  5694  5694 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
11-18 13:30:58.850  5694  5694 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-18 13:30:58.850  5694  5694 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-18 13:30:58.850  5694  5694 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-18 13:30:58.850  5694  5694 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-18 13:30:58.850  5694  5694 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-18 13:30:58.850  5694  5694 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-18 13:30:58.850  5694  5694 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-18 13:30:58.850  5694  5694 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-18 13:30:58.850  5694  5694 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-18 13:30:58.850  5694  5694 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-18 13:30:58.850  5694  5694 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-18 13:30:58.850  5694  5694 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-18 13:30:58.850  5694  5694 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-18 13:30:58.850  5694  5694 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-18 13:30:58.850  5694  5694 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-18 13:30:58.850  5694  5694 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-18 13:30:58.850  5694  5694 D StrictMode: StrictMode policy violation; ~duration=124 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-18 13:30:58.850  5694  5694 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-18 13:30:58.850  5694  5694 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
11-18 13:30:58.850  5694  5694 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
11-18 13:30:58.850  5694  5694 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
11-18 13:30:58.850  5694  5694 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
11-18 13:30:58.850  5694  5694 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
11-18 13:30:58.850  5694  5694 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
11-18 13:30:58.850  5694  5694 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
11-18 13:30:58.850  5694  5694 D StrictMode: 	at com.google.android.apps.gmm.share,d.f.a.a(PG:48)
11-18 13:30:58.850  5694  5694 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-18 13:30:58.850  5694  5694 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-18 13:30:58.850  5694  5694 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-18 13:30:58.850  5694  5694 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-18 13:30:58.850  5694  5694 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-18 13:30:58.850  5694  5694 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-18 13:30:58.850  5694  5694 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-18 13:30:58.850  5694  5694 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-18 13:30:58.850  5694  5694 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-18 13:30:58.850  5694  5694 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-18 13:30:58.850  5694  5694 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-18 13:30:58.850  5694  5694 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-18 13:30:58.850  5694  5694 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-18 13:30:58.850  5694  5694 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-18 13:30:58.850  5694  5694 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-18 13:30:58.850  5694  5694 D StrictMode: StrictMode policy violation; ~duration=124 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-18 13:30:58.850  5694  5694 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-18 13:30:58.850  5694  5694 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
11-18 13:30:58.850  5694  5694 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
11-18 13:30:58.850  5694  5694 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
11-18 13:30:58.850  5694  5694 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
11-18 13:30:58.850  5694  5694 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
11-18 13:30:58.850  5694  5694 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
11-18 13:30:58.850  5694  5694 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
11-18 13:30:58.850  5694  5694 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-18 13:30:58.850  5694  5694 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-18 13:30:58.850  5694  5694 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-18 13:30:58.850  5694  5694 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-18 13:30:58.850  5694  5694 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-18 13:30:58.850  5694  5694 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-18 13:30:58.850  5694  5694 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-18 13:30:58.850  5694  5694 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-18 13:30:58.850  5694  5694 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-18 13:30:58.850  5694  5694 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-18 13:30:58.850  5694  5694 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-18 13:30:58.850  5694  5694 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-18 13:30:58.850  5694  5694 D StrictMode: 	at android.app.ActivityThread.main(,ActivityThread.java:5422)
11-18 13:30:58.850  5694  5694 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-18 13:30:58.850  5694  5694 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-18 13:30:58.850  5694  5694 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-18 13:30:58.851  5694  5694 D StrictMode: StrictMode policy violation; ~duration=122 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-18 13:30:58.851  5694  5694 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-18 13:30:58.851  5694  5694 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
11-18 13:30:58.851  5694  5694 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
11-18 13:30:58.851  5694  5694 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
11-18 13:30:58.851  5694  5694 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
11-18 13:30:58.851  5694  5694 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
11-18 13:30:58.851  5694  5694 D StrictMode: 	at com.google.r.k.d(PG:1187)
11-18 13:30:58.851  5694  5694 D StrictMode: 	at com.google.r.k.a(PG:2107)
11-18 13:30:58.851  5694  5694 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
11-18 13:30:58.851  5694  5694 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
11-18 13:30:58.851  5694  5694 D StrictMode: 	at com.google.r.v.a(PG:1161)
11-18 13:30:58.851  5694  5694 D StrictMode: 	at com.google.r.y.a(PG:2188)
11-18 13:30:58.851  5694  5694 D StrictMode: 	at com.google.r.e.b(PG:170)
11-18 13:30:58.851  5694  5694 D StrictMode: 	at com.google.r.e.b(PG:15188)
11-18 13:30:58.851  5694  5694 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
11-18 13:30:58.851  5694  5694 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
11-18 13:30:58.851  5694  5694 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-18 13:30:58.851  5694  5694 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-18 13:30:58.851  5694  5694 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-18 13:30:58.851  5694  5694 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-18 13:30:58.851  5694  5694 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-18 13:30:58.851  5694  5694 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-18 13:30:58.851  5694  5694 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-18 13:30:58.851  5694  5694 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-18 13:30:58.851  5694  5694 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-18 13:30:58.851  5694  5694 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-18 13:30:58.851  5694  5694 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-18 13:30:58.851  5694  5694 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-18 13:30:58.851  5694  5694 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-18 13:30:58.851  5694  5694 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-18 13:30:58.851  5694  5694 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-18 13:30:58.851  5694  5694 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-18 13:30:58.851  5694  5694 D StrictMode: StrictMode policy violation; ~duration=119 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-18 13:30:58.851  5694  5694 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-18 13:30:58.851  5694  5694 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
11-18 13:30:58.851  5694  5694 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
11-18 13:30:58.851  5694  5694 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
11-18 13:30:58.851  5694  5694 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
11-18 13:30:58.851  5694  5694 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
11-18 13:30:58.851  5694  5694 D StrictMode: 	at com.google.r.k.d(PG:1187)
11-18 13:30:58.851  5694  5694 D StrictMode: 	at com.google.r.k.c(PG:18147)
11-18 13:30:58.851  5694  5694 D StrictMode: 	at com.google.r.k.d(PG:583)
11-18 13:30:58.851  5694  5694 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
11-18 13:30:58.851  5694  5694 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
11-18 13:30:58.851  5694  5694 D StrictMode: 	at com.google.r.v.a(PG:1161)
11-18 13:30:58.851  5694  5694 D StrictMode: 	at com.google.r.y.a(PG:2188)
11-18 13:30:58.851  5694  5694 D StrictMode: 	at com.google.r.e.b(PG:170)
11-18 13:30:58.851  5694  5694 D StrictMode: 	at com.google.r.e.b(PG:15188)
11-18 13:30:58.851  5694  5694 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
11-18 13:30:58.851  5694  5694 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
11-18 13:30:58.851  5694  5694 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-18 13:30:58.851  5694  5694 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-18 13:30:58.851  5694  5694 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-18 13:30:58.851  5694  5694 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-18 13:30:58.851  5694  5694 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-18 13:30:58.851  5694  5694 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-18 13:30:58.851  5694  5694 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-18 13:30:58.851  5694  5694 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-18 13:30:58.851  5694  5694 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-18 13:30:58.851  5694  5694 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-18 13:30:58.851  5694  5694 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-18 13:30:58.851  5694  5694 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-18 13:30:58.851  5694  5694 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-18 13:30:58.851  5694  5694 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-18 13:30:58.851  5694  5694 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-18 13:30:58.851  5694  5694 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-18 13:30:58.851  5694  5694 D StrictMode: StrictMode policy violation; ~duration=93 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-18 13:30:58.851  5694  5694 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-18 13:30:58.851  5694  5694 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
11-18 13:30:58.851  5694  5694 D StrictMode: 	at java.io.File.doAccess(File.java:281)
11-18 13:30:58.851  5694  5694 D StrictMode: 	at java.io.File.exists(File.java:361)
11-18 13:30:58.851  5694  5694 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
11-18 13:30:58.851  5694  5694 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
11-18 13:30:58.851  5694  5694 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
11-18 13:30:58.851  5694  5694 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
11-18 13:30:58.851  5694  5694 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
11-18 13:30:58.851  5694  5694 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-18 13:30:58.851  5694  5694 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-18 13:30:58.851  5694  5694 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-18 13:30:58.851  5694  5694 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-18 13:30:58.851  5694  5694 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-18 13:30:58.851  5694  5694 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-18 13:30:58.851  5694  5694 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-18 13:30:58.851  5694  5694 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-18 13:30:58.851  5694  5694 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-18 13:30:58.851  5694  5694 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-18 13:30:58.851  5694  5694 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-18 13:30:58.851  5694  5694 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-18 13:30:58.851  5694  5694 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-18 13:30:58.851  5694  5694 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-18 13:30:58.851  5694  5694 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-18 13:30:58.851  5694  5694 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-18 13:30:58.851  5694  5694 D StrictMode: StrictMode policy violation; ~duration=93 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-18 13:30:58.851  5694  5694 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-18 13:30:58.851  5694  5694 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
11-18 13:30:58.851  5694  5694 D StrictMode: 	at java.io.File.doAccess(File.java:281)
11-18 13:30:58.851  5694  5694 D StrictMode: 	at java.io.File.exists(File.java:361)
11-18 13:30:58.851  5694  5694 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
11-18 13:30:58.851  5694  5694 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-18 13:30:58.851  5694  5694 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-18 13:30:58.851  5694  5694 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-18 13:30:58.851  5694  5694 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-18 13:30:58.851  5694  5694 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-18 13:30:58.851  5694  5694 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-18 13:30:58.851  5694  5694 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-18 13:30:58.851  5694  5694 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-18 13:30:58.851  5694  5694 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-18 13:30:58.851  5694  5694 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-18 13:30:58.851  5694  5694 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-18 13:30:58.851  5694  5694 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-18 13:30:58.851  5694  5694 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-18 13:30:58.851  5694  5694 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-18 13:30:58.851  5694  5694 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-18 13:30:58.851  5694  5694 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-18 13:30:58.851  5694  5694 D StrictMode: StrictMode policy violation; ~duration=92 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-18 13:30:58.851  5694  5694 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-18 13:30:58.851  5694  5694 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
11-18 13:30:58.851  5694  5694 D StrictMode: 	at java.io.File.lastModified(File.java:569)
11-18 13:30:58.851  5694  5694 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
11-18 13:30:58.851  5694  5694 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-18 13:30:58.851  5694  5694 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-18 13:30:58.851  5694  5694 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-18 13:30:58.851  5694  5694 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-18 13:30:58.851  5694  5694 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-18 13:30:58.851  5694  5694 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-18 13:30:58.851  5694  5694 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-18 13:30:58.851  5694  5694 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-18 13:30:58.851  5694  5694 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-18 13:30:58.851  5694  5694 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-18 13:30:58.851  5694  5694 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-18 13:30:58.851  5694  5694 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-18 13:30:58.851  5694  5694 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-18 13:30:58.851  5694  5694 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-18 13:30:58.851  5694  5694 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-18 13:30:58.851  5694  5694 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-18 13:30:58.861  5310  5310 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
11-18 13:30:58.866  3610  3610 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
11-18 13:30:58.869  5310  5310 D DockEventReceiver: finishStartingService: stopping service
11-18 13:30:58.872   930  3626 I ActivityManager: Killing 5426:com.android.sdm.plugins.sprintdm/1001 (adj 15): empty #17
,11-18 13:30:58.946  4683  4742 D bt_stack_manager: event_shut_down_stack finished.
,11-18 13:30:58.947  4683  4741 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,11-18 13:30:58.948  4683  4741 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,11-18 13:30:58.949  4683  4683 D BtGatt.DebugUtils: handleDebugAction() action=null
,11-18 13:30:58.949  4683  4683 D BtGatt.GattService: Received stop request...Stopping profile...
11-18 13:30:58.949  4683  4683 D BtGatt.GattService: stop()
,11-18 13:30:58.949  4683  4683 D BtGatt.AdvertiseManager: advertise clients cleared
11-18 13:30:58.951  4683  4683 V BluetoothAdapterState: isTurningOff()=false
,11-18 13:30:58.951  4683  4683 V BluetoothAdapterState: isTurningOn()=false
11-18 13:30:58.951  4683  4683 V BluetoothAdapterState: isBleTurningOn()=false
,11-18 13:30:58.951  4683  4683 V BluetoothAdapterState: isBleTurningOff()=true
11-18 13:30:58.951  4683  4741 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
11-18 13:30:58.952  4683  4741 D BluetoothAdapterProperties: Setting state to 10
,11-18 13:30:58.952  4683  4741 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
11-18 13:30:58.952  4683  4741 I BluetoothAdapterState: Entering OffState
11-18 13:30:58.953   930   947 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
,11-18 13:30:58.959  4683  4683 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,11-18 13:30:58.959  4683  4683 W BluetoothSdpJni: Cleaning up Bluetooth Health object
11-18 13:30:58.959  4683  4683 I BluetoothServiceJni: cleanupNative: return from cleanup
11-18 13:30:58.960  4683  4742 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,11-18 13:30:58.965  4683  4683 I art     : System.exit called, status: 0
11-18 13:30:58.965  4683  4683 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,11-18 13:30:58.997  5627  5627 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-18 13:30:59.004   930  3191 I ActivityManager: Process com.android.bluetooth (pid 4683) has died
,11-18 13:30:59.013  5694  5722 W ActivityThread: ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,11-18 13:30:59.030  5627  5689 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,11-18 13:30:59.030  5627  5689 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-18 13:30:59.030  5627  5689 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-18 13:30:59.030  5627  5689 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-18 13:30:59.030  5627  5689 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-18 13:30:59.030  5627  5689 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-18 13:30:59.030  5627  5689 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-18 13:30:59.030  5627  5689 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-18 13:30:59.030  5627  5689 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-18 13:30:59.030  5627  5689 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
11-18 13:30:59.030  5627  5689 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-18 13:30:59.030  5627  5689 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
,11-18 13:30:59.033  5627  5674 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-18 13:30:59.044   930   947 I ActivityManager: Start proc 5725:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,11-18 13:30:59.084  5694  5714 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,11-18 13:30:59.098   930   947 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1b851af:true
,11-18 13:30:59.100  5725  5725 D AdapterServiceConfig: Adding HeadsetService
,11-18 13:30:59.100  5725  5725 D AdapterServiceConfig: Adding A2dpService
11-18 13:30:59.100  5725  5725 D AdapterServiceConfig: Adding HidService
11-18 13:30:59.101  5725  5725 D AdapterServiceConfig: Adding HealthService
,11-18 13:30:59.101  5725  5725 D AdapterServiceConfig: Adding PanService
11-18 13:30:59.101  5725  5725 D AdapterServiceConfig: Adding GattService
11-18 13:30:59.101  5725  5725 D AdapterServiceConfig: Adding BluetoothMapService
11-18 13:30:59.101  5725  5725 D AdapterServiceConfig: Adding SapService
11-18 13:30:59.110   930   947 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@a1ac7a7:true
11-18 13:30:59.110  5725  5725 D BluetoothAdapterState: make() - Creating AdapterState
,11-18 13:30:59.115  5725  5725 I bt_bluedroid: init
,11-18 13:30:59.115  5725  5739 I BluetoothAdapterState: Entering OffState
,11-18 13:30:59.117  5725  5740 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,11-18 13:30:59.117  5725  5740 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
11-18 13:30:59.117  5725  5740 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
11-18 13:30:59.117  5725  5740 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,11-18 13:30:59.119  5725  5725 I bt_bluedroid: get_profile_interface socket
,11-18 13:30:59.120  5725  5743 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:D4
11-18 13:30:59.121  5725  5743 D BluetoothAdapterProperties: Name is: Nexus 6P
11-18 13:30:59.121  5725  5725 I bt_bluedroid: get_profile_interface sdp
,11-18 13:30:59.125  5725  5736 I bt_bluedroid: config_hci_snoop_log
,11-18 13:30:59.126   930   947 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,11-18 13:30:59.129  5725  5739 D BluetoothAdapterState: Current state: OFF, message: 0
,11-18 13:30:59.130  5725  5739 D BluetoothAdapterProperties: Setting state to 14
11-18 13:30:59.130  5725  5739 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,11-18 13:30:59.131  5725  5739 D BluetoothBondStateMachine: make
11-18 13:30:59.133  5725  5744 I BluetoothBondStateMachine: StableState(): Entering Off State
,11-18 13:30:59.135  5725  5739 I BluetoothAdapterState: Entering PendingCommandState
,11-18 13:30:59.136  5725  5725 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,11-18 13:30:59.138  5725  5725 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7dee38f
11-18 13:30:59.139  5725  5725 D BtGatt.DebugUtils: handleDebugAction() action=null
11-18 13:30:59.139  5725  5725 D BtGatt.GattService: Received start request. Starting profile...
11-18 13:30:59.139  5725  5725 D BtGatt.GattService: start()
11-18 13:30:59.139  5725  5725 I bt_bluedroid: get_profile_interface gatt
11-18 13:30:59.140  5725  5725 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7dee38f
11-18 13:30:59.140  5725  5725 D BtGatt.AdvertiseManager: advertise manager created
,11-18 13:30:59.145  5725  5725 V BluetoothAdapterState: isTurningOff()=false
11-18 13:30:59.145  5725  5725 V BluetoothAdapterState: isTurningOn()=false
11-18 13:30:59.145  5725  5725 V BluetoothAdapterState: isBleTurningOn()=true
,11-18 13:30:59.145  5725  5725 V BluetoothAdapterState: isBleTurningOff()=false
11-18 13:30:59.145  5725  5739 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,11-18 13:30:59.146  5725  5739 I bt_bluedroid: bt_bluedroid
11-18 13:30:59.146  5725  5740 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,11-18 13:30:59.147  5725  5740 I bt_hci  : start_up
,11-18 13:30:59.151  5725  5740 I bt_vendor: alloc value 0xf3c75871
,11-18 13:30:59.151  5725  5740 I bt_vendor: init
11-18 13:30:59.151  5725  5740 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
11-18 13:30:59.151  5725  5740 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,11-18 13:30:59.260  5725  5740 D bt_hci  : start_up starting async portion
11-18 13:30:59.261  5725  5747 I bt_hci  : event_finish_startup
11-18 13:30:59.261  5725  5747 I bt_hci_h4: hal_open
11-18 13:30:59.261  5725  5747 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,11-18 13:30:59.257  5749  5749 W irq/448-msm_hs_: type=1400 audit(0.0:121): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
11-18 13:30:59.261  5725  5747 I bt_userial_vendor: device fd = 54 open
,11-18 13:30:59.275  5725  5747 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,11-18 13:30:59.278  5725  5747 D bt_hwcfg: Chipset BCM4358A3
,11-18 13:30:59.278  5725  5747 D bt_hwcfg: Target name = [BCM4358A3]
11-18 13:30:59.278  5725  5747 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,11-18 13:30:59.527  3610  5753 V NQFileLogger: [132] e.a: about to write to file
,11-18 13:30:59.532  3610  5753 V ProcessReports: [132] ProcessReportsService.a: If not already scheduled, schedule for 3600 to 14400 seconds from now (but might be processed inline after 900 seconds instead)
,11-18 13:30:59.536  5725  5739 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 0
,11-18 13:30:59.759  5725  5747 I bt_hwcfg: bt vendor lib: set UART baud 115200
11-18 13:30:59.760  5725  5747 D bt_hwcfg: Settlement delay -- 100 ms
,11-18 13:30:59.760  5725  5747 I bt_hwcfg: Setting fw settlement delay to 100 
,11-18 13:30:59.883  5725  5747 I bt_hwcfg: bt vendor lib: set UART baud 3000000
11-18 13:30:59.884  5725  5747 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:D4
11-18 13:30:59.886  5725  5747 I bt_hwcfg: vendor lib fwcfg completed
11-18 13:30:59.886  5725  5747 I bt_vendor: firmware callback
11-18 13:30:59.886  5725  5747 I bt_hci  : firmware_config_callback
,11-18 13:30:59.895  5725  5755 I bt_btu  : btu_task pending for preload complete event
,11-18 13:30:59.896  5725  5755 I bt_btu_task: Bluetooth chip preload is complete
,11-18 13:30:59.896  5725  5755 I bt_btu  : btu_task received preload complete event
,11-18 13:30:59.903  5725  5755 I         : BTE_InitTraceLevels -- TRC_HCI
,11-18 13:30:59.903  5725  5755 I         : BTE_InitTraceLevels -- TRC_L2CAP
11-18 13:30:59.903  5725  5755 I         : BTE_InitTraceLevels -- TRC_RFCOMM
11-18 13:30:59.903  5725  5755 I         : BTE_InitTraceLevels -- TRC_AVDT
11-18 13:30:59.903  5725  5755 I         : BTE_InitTraceLevels -- TRC_AVRC
11-18 13:30:59.903  5725  5755 I         : BTE_InitTraceLevels -- TRC_A2D
,11-18 13:30:59.904  5725  5755 I         : BTE_InitTraceLevels -- TRC_BNEP
11-18 13:30:59.904  5725  5755 I         : BTE_InitTraceLevels -- TRC_BTM
11-18 13:30:59.904  5725  5755 I         : BTE_InitTraceLevels -- TRC_GAP
11-18 13:30:59.904  5725  5755 I         : BTE_InitTraceLevels -- TRC_PAN
,11-18 13:30:59.904  5725  5755 I         : BTE_InitTraceLevels -- TRC_SDP
11-18 13:30:59.904  5725  5755 I         : BTE_InitTraceLevels -- TRC_GATT
,11-18 13:30:59.904  5725  5755 I         : BTE_InitTraceLevels -- TRC_SMP
11-18 13:30:59.904  5725  5755 I         : BTE_InitTraceLevels -- TRC_BTAPP
,11-18 13:30:59.904  5725  5755 I         : BTE_InitTraceLevels -- TRC_BTIF
,11-18 13:30:59.983  5725  5755 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf3bf3549
11-18 13:30:59.983  5725  5755 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf3bf3549 
,11-18 13:30:59.997  5725  5743 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,11-18 13:30:59.998  5725  5743 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,11-18 13:30:59.999  5725  5743 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:D4
11-18 13:31:00.000  5725  5743 D BluetoothAdapterProperties: Name is: Nexus 6P
11-18 13:31:00.002  5725  5743 D BluetoothAdapterProperties: Scan Mode:20
11-18 13:31:00.002  5725  5743 D BluetoothAdapterProperties: Discoverable Timeout:120
11-18 13:31:00.002  5725  5743 D bt_hci  : do_postload posting postload work item
,11-18 13:31:00.002  5725  5747 I bt_hci  : event_postload
,11-18 13:31:00.003  5725  5747 I bt_vendor: sco_config_cb
11-18 13:31:00.003  5725  5747 I bt_hci  : sco_config_callback postload finished.
,11-18 13:31:00.006  5725  5743 D bt_bte_conf: Device ID record 1 : primary
11-18 13:31:00.006  5725  5743 D bt_bte_conf:   vendorId            = 000f
11-18 13:31:00.006  5725  5743 D bt_bte_conf:   vendorIdSource      = 0001
11-18 13:31:00.006  5725  5743 D bt_bte_conf:   product             = 1200
,11-18 13:31:00.006  5725  5743 D bt_bte_conf:   version             = 1436
11-18 13:31:00.006  5725  5743 D bt_bte_conf:   clientExecutableURL = 
11-18 13:31:00.006  5725  5743 D bt_bte_conf:   serviceDescription  = 
11-18 13:31:00.006  5725  5743 D bt_bte_conf:   documentationURL    = 
11-18 13:31:00.006  5725  5743 D bt_bte_conf: bte_load_did_conf no section named DID2.
11-18 13:31:00.007  5725  5740 D bt_stack_manager: event_start_up_stack finished
11-18 13:31:00.009  5725  5739 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
11-18 13:31:00.009  5725  5739 D BluetoothAdapterProperties: Setting state to 15
11-18 13:31:00.009  5725  5739 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
,11-18 13:31:00.010  5725  5739 I BluetoothAdapterState: Entering BleOnState
,11-18 13:31:00.014  5725  5747 I bt_vendor: low_power_mode_cb
,11-18 13:31:00.018  5725  5739 D BluetoothAdapterState: Current state: BLE ON, message: 1
11-18 13:31:00.018  5725  5739 D BluetoothAdapterProperties: Setting state to 11
,11-18 13:31:00.018  5725  5739 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,11-18 13:31:00.022  5725  5725 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7dee38f
11-18 13:31:00.024  5725  5725 D HeadsetService: Received start request. Starting profile...
11-18 13:31:00.024   930   939 I art     : Background partial concurrent mark sweep GC freed 40269(2MB) AllocSpace objects, 13(376KB) LOS objects, 33% free, 29MB/43MB, paused 1.906ms total 122.868ms
11-18 13:31:00.026  5725  5725 I BluetoothHeadsetServiceJni: classInitNative: succeeds
11-18 13:31:00.026  5725  5725 D HeadsetStateMachine: make
,11-18 13:31:00.038  5725  5739 I BluetoothAdapterState: Entering PendingCommandState
,11-18 13:31:00.040  5725  5725 D HeadsetStateMachine: max_hf_connections = 1
11-18 13:31:00.040  5725  5739 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 0
11-18 13:31:00.040  5725  5725 I bt_bluedroid: get_profile_interface handsfree
11-18 13:31:00.040  5725  5743 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
,11-18 13:31:00.041  5725  5743 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
,11-18 13:31:00.043  5725  5725 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7dee38f
,11-18 13:31:00.044  5725  5725 D A2dpService: Received start request. Starting profile...
11-18 13:31:00.045  5725  5725 I BluetoothAvrcpServiceJni: classInitNative: succeeds
11-18 13:31:00.045  5725  5725 I bt_bluedroid: get_profile_interface avrcp
,11-18 13:31:00.049  5725  5725 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
11-18 13:31:00.050  5725  5725 I BluetoothA2dpServiceJni: classInitNative: succeeds
11-18 13:31:00.050  5725  5725 D A2dpStateMachine: make
11-18 13:31:00.051  5725  5725 I bt_bluedroid: get_profile_interface a2dp
11-18 13:31:00.052  5725  5743 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,11-18 13:31:00.056  5725  5762 D A2dpStateMachine: Enter Disconnected: -2
11-18 13:31:00.057  5725  5725 I BluetoothHidServiceJni: classInitNative: succeeds
11-18 13:31:00.058  5725  5725 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7dee38f
,11-18 13:31:00.058  5725  5725 D HidService: Received start request. Starting profile...
11-18 13:31:00.058  5725  5725 I bt_bluedroid: get_profile_interface hidhost
,11-18 13:31:00.058  5725  5725 D HidService: setHidService(): set to: null
11-18 13:31:00.058  5725  5743 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf3bd456d
11-18 13:31:00.058  3610  3610 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
11-18 13:31:00.058  5725  5743 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
11-18 13:31:00.059  5725  5725 I BluetoothHealthServiceJni: classInitNative: succeeds
11-18 13:31:00.059  5725  5725 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7dee38f
11-18 13:31:00.059  5725  5725 D HealthService: Received start request. Starting profile...
,11-18 13:31:00.061  5725  5725 I bt_bluedroid: get_profile_interface health
,11-18 13:31:00.062  5725  5725 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,11-18 13:31:00.062  5725  5725 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7dee38f
11-18 13:31:00.063  5725  5725 D PanService: Received start request. Starting profile...
,11-18 13:31:00.063  5725  5725 D BluetoothPanServiceJni: initializeNative(L110): pan
11-18 13:31:00.063  5725  5725 I bt_bluedroid: get_profile_interface pan
,11-18 13:31:00.064  5725  5743 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
11-18 13:31:00.064  5725  5725 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7dee38f
,11-18 13:31:00.065  5725  5725 D BluetoothMapService: Received start request. Starting profile...
11-18 13:31:00.065  5725  5725 D BluetoothMapService: start()
,11-18 13:31:00.066  5725  5725 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
11-18 13:31:00.067  5725  5725 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
11-18 13:31:00.067  5725  5725 D BluetoothMapAppObserver: createReceiver()
11-18 13:31:00.067  5725  5725 D BluetoothMapAppObserver: initObservers()
11-18 13:31:00.067  5725  5725 D BluetoothMapAppObserver: getEnabledAccountItems()
,11-18 13:31:00.071  5725  5725 V SapService: SapBinder()
,11-18 13:31:00.071  5725  5725 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7dee38f
11-18 13:31:00.072  5725  5725 D SapService: Received start request. Starting profile...
11-18 13:31:00.072  5725  5725 V SapService: start()
11-18 13:31:00.073  5725  5725 V BluetoothAdapterState: isTurningOff()=false
11-18 13:31:00.073  5725  5725 V BluetoothAdapterState: isTurningOn()=true
11-18 13:31:00.073  5725  5725 V BluetoothAdapterState: isBleTurningOn()=false
11-18 13:31:00.073  5725  5725 V BluetoothAdapterState: isBleTurningOff()=false
11-18 13:31:00.073  5725  5725 V BluetoothAdapterState: isTurningOff()=false
11-18 13:31:00.073  5725  5725 V BluetoothAdapterState: isTurningOn()=true
11-18 13:31:00.073  5725  5725 V BluetoothAdapterState: isBleTurningOn()=false
11-18 13:31:00.073  5725  5725 V BluetoothAdapterState: isBleTurningOff()=false
11-18 13:31:00.073  5725  5725 V BluetoothAdapterState: isTurningOff()=false
11-18 13:31:00.073  5725  5725 V BluetoothAdapterState: isTurningOn()=true
11-18 13:31:00.073  5725  5725 V BluetoothAdapterState: isBleTurningOn()=false
,11-18 13:31:00.073  5725  5725 V BluetoothAdapterState: isBleTurningOff()=false
11-18 13:31:00.074  5725  5725 V BluetoothAdapterState: isTurningOff()=false
,11-18 13:31:00.074  5725  5725 V BluetoothAdapterState: isTurningOn()=true
11-18 13:31:00.074  5725  5725 V BluetoothAdapterState: isBleTurningOn()=false
11-18 13:31:00.074  5725  5725 V BluetoothAdapterState: isBleTurningOff()=false
11-18 13:31:00.074  5725  5725 V BluetoothAdapterState: isTurningOff()=false
11-18 13:31:00.074  5725  5725 V BluetoothAdapterState: isTurningOn()=true
11-18 13:31:00.074  5725  5725 V BluetoothAdapterState: isBleTurningOn()=false
11-18 13:31:00.075  5725  5725 V BluetoothAdapterState: isBleTurningOff()=false
11-18 13:31:00.075  5725  5725 V BluetoothAdapterState: isTurningOff()=false
11-18 13:31:00.075  5725  5725 V BluetoothAdapterState: isTurningOn()=true
11-18 13:31:00.075  5725  5725 V BluetoothAdapterState: isBleTurningOn()=false
11-18 13:31:00.075  5725  5725 V BluetoothAdapterState: isBleTurningOff()=false
11-18 13:31:00.075  5725  5725 V BluetoothAdapterState: isTurningOff()=false
11-18 13:31:00.075  5725  5725 V BluetoothAdapterState: isTurningOn()=true
11-18 13:31:00.075  5725  5725 V BluetoothAdapterState: isBleTurningOn()=false
11-18 13:31:00.075  5725  5725 V BluetoothAdapterState: isBleTurningOff()=false
11-18 13:31:00.076  5725  5739 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
11-18 13:31:00.076  5725  5739 D BluetoothAdapterProperties: ScanMode =  20
11-18 13:31:00.076  5725  5739 D BluetoothAdapterProperties: State =  11
11-18 13:31:00.076  5725  5739 D BluetoothAdapterProperties: Setting state to 12
11-18 13:31:00.076  5725  5739 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
11-18 13:31:00.077  5725  5739 I BluetoothAdapterState: Entering OnState
11-18 13:31:00.077  5725  5743 D BluetoothAdapterProperties: Scan Mode:21
11-18 13:31:00.077  5725  5743 D BluetoothAdapterProperties: Discoverable Timeout:120
11-18 13:31:00.078  5310  5320 D BluetoothMap: onBluetoothStateChange: up=true
,11-18 13:31:00.084  3163  3180 D BluetoothInputDevice: onBluetoothStateChange: up=true
11-18 13:31:00.087  5310  5321 D BluetoothHeadset: onBluetoothStateChange: up=true
11-18 13:31:00.087  5310  5320 D BluetoothA2dp: onBluetoothStateChange: up=true
11-18 13:31:00.088  3163  3163 D BluetoothInputDevice: Proxy object connected
11-18 13:31:00.088  3163  3163 D HidProfile: Bluetooth service connected
11-18 13:31:00.089  5310  5310 D BluetoothMap: Proxy object connected
11-18 13:31:00.090  5310  5310 D MapProfile: Bluetooth service connected
11-18 13:31:00.090  3163  4017 D BluetoothMap: onBluetoothStateChange: up=true
11-18 13:31:00.091  5725  5725 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
11-18 13:31:00.092  5725  5725 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
11-18 13:31:00.092  5310  5321 D BluetoothPbap: onBluetoothStateChange: up=true
11-18 13:31:00.092  3163  3163 D BluetoothMap: Proxy object connected
11-18 13:31:00.092  3163  3163 D MapProfile: Bluetooth service connected
11-18 13:31:00.092  3163  3163 D BluetoothMap: getConnectedDevices()
11-18 13:31:00.093  5310  5320 D BluetoothPan: onBluetoothStateChange on: true
11-18 13:31:00.094  5725  5725 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-18 13:31:00.094   930   947 D BluetoothHeadset: onBluetoothStateChange: up=true
11-18 13:31:00.095   930   947 D BluetoothHeadset: onBluetoothStateChange: up=true
11-18 13:31:00.095   930   947 D BluetoothA2dp: onBluetoothStateChange: up=true
11-18 13:31:00.095   930   930 D BluetoothA2dp: Proxy object connected
11-18 13:31:00.095  3791  3802 D BluetoothHeadset: onBluetoothStateChange: up=true
11-18 13:31:00.096   930   947 D BluetoothHeadset: onBluetoothStateChange: up=true
11-18 13:31:00.096  5310  5693 D BluetoothInputDevice: onBluetoothStateChange: up=true
11-18 13:31:00.096  5725  5725 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-18 13:31:00.097  5310  5310 D BluetoothMap: getConnectedDevices()
11-18 13:31:00.097  5725  5725 D ObexServerSockets: Succeed to create listening sockets 
11-18 13:31:00.097  5725  5725 D ObexServerSockets0: startAccept()
11-18 13:31:00.097  5725  5725 D ObexServerSockets0: prepareForNewConnect()
11-18 13:31:00.098  3163  3180 D BluetoothHeadset: onBluetoothStateChange: up=true
11-18 13:31:00.098  3163  3909 D BluetoothPbap: onBluetoothStateChange: up=true
11-18 13:31:00.099  5725  5725 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
11-18 13:31:00.099  5725  5725 D BluetoothSdpJni: SDP Create record success - handle: 0
11-18 13:31:00.099  5725  5768 D ObexServerSockets0: Accepting socket connection...
11-18 13:31:00.099  5725  5769 D ObexServerSockets0: Accepting socket connection...
11-18 13:31:00.100  5310  5310 D BluetoothA2dp: Proxy object connected
11-18 13:31:00.101  3163  4017 D BluetoothA2dp: onBluetoothStateChange: up=true
11-18 13:31:00.102  3163  3163 D BluetoothA2dp: Proxy object connected
11-18 13:31:00.102  3163  3174 D BluetoothPan: onBluetoothStateChange on: true
11-18 13:31:00.103  5310  5310 D BluetoothInputDevice: Proxy object connected
11-18 13:31:00.103  5310  5310 D HidProfile: Bluetooth service connected
11-18 13:31:00.104  5310  5310 D BluetoothPan: BluetoothPAN Proxy object connected
11-18 13:31:00.104  5310  5310 D PanProfile: Bluetooth service connected
11-18 13:31:00.104  3163  3163 D BluetoothPan: BluetoothPAN Proxy object connected
11-18 13:31:00.104  3163  3163 D PanProfile: Bluetooth service connected
11-18 13:31:00.105  5725  5725 D BluetoothMapService: onReceive
11-18 13:31:00.105  5725  5725 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
11-18 13:31:00.105  5725  5725 D BluetoothMapService: STATE_ON
11-18 13:31:00.106   930   930 I Telecom : BluetoothPhoneService: queryPhoneState
11-18 13:31:00.109  5725  5771 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-18 13:31:00.110  5310  5310 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
11-18 13:31:00.110  5725  5771 D BluetoothSdpJni: sdpCreateSapsRecordNative:
11-18 13:31:00.111  5725  5771 D BluetoothSdpJni: SDP Create record success - handle: 1
,11-18 13:31:00.118  3610  3610 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,11-18 13:31:00.118  5310  5310 D DockEventReceiver: finishStartingService: stopping service
11-18 13:31:00.124  5310  5310 D BluetoothPbap: Proxy object connected
11-18 13:31:00.124  5310  5310 D PbapServerProfile: Bluetooth service connected
11-18 13:31:00.125  3163  3163 D BluetoothPbap: Proxy object connected
11-18 13:31:00.125  3163  3163 D PbapServerProfile: Bluetooth service connected
,11-18 13:31:00.127  5725  5773 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-18 13:31:00.130  5725  5725 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
11-18 13:31:00.130  5725  5725 D ObexServerSockets0: prepareForNewConnect()
,11-18 13:31:00.145  5725  5779 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-18 13:31:00.147  5725  5779 I BtOppRfcommListener: Accept thread started.
,11-18 13:31:00.188   930   930 D BluetoothHeadset: Proxy object connected
,11-18 13:31:00.189  3791  4016 D BluetoothHeadset: Proxy object connected
11-18 13:31:00.189   930   930 D BluetoothHeadset: Proxy object connected
,11-18 13:31:00.189  5310  5693 D BluetoothHeadset: Proxy object connected
11-18 13:31:00.189  3163  3180 D BluetoothHeadset: Proxy object connected
11-18 13:31:00.190  3163  3163 D HeadsetProfile: Bluetooth service connected
11-18 13:31:00.190   930   930 D BluetoothHeadset: Proxy object connected
11-18 13:31:00.191  5310  5310 D HeadsetProfile: Bluetooth service connected
,11-18 13:31:00.195   930   947 D BluetoothHeadset: Proxy object connected
11-18 13:31:00.195   930   947 D BluetoothHeadset: Proxy object connected
11-18 13:31:00.196  3791  3803 D BluetoothHeadset: Proxy object connected
11-18 13:31:00.196   930   947 D BluetoothHeadset: Proxy object connected
,11-18 13:31:00.199  3163  3909 D BluetoothHeadset: Proxy object connected
,11-18 13:31:00.200  3163  3163 D HeadsetProfile: Bluetooth service connected
,11-18 13:31:00.553  5627  5689 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-18 13:31:00.553  5627  5689 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-18 13:31:00.553  5627  5689 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-18 13:31:00.553  5627  5689 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-18 13:31:00.553  5627  5689 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-18 13:31:00.553  5627  5689 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-18 13:31:00.553  5627  5689 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-18 13:31:00.553  5627  5689 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-18 13:31:00.553  5627  5689 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,11-18 13:31:00.559  5627  5689 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
11-18 13:31:00.562  5627  5674 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testIsWifiEnabled
,11-18 13:31:00.564   930   940 D WifiService: setWifiEnabled: false pid=5627, uid=10077
11-18 13:31:00.564   930   940 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
11-18 13:31:00.568  5627  5674 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-18 13:31:00.569   930  2981 D WifiStateMachine: WifiStateMachine: Leaving Connected state
11-18 13:31:00.569   930  2981 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
,11-18 13:31:00.569   930  2981 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
11-18 13:31:00.570   930  2981 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-18 13:31:00.591   930  5402 D DhcpClient: Clearing IP address
,11-18 13:31:00.591   507   928 D CommandListener: Clearing all IP addresses on wlan0
,11-18 13:31:00.600   507   928 D CommandListener: Setting iface cfg
,11-18 13:31:00.608  3610  5453 V NativeCrypto: Read error: ssl=0x7f8f649380: I/O error during system call, Connection timed out
,11-18 13:31:00.610  3610  5453 V NativeCrypto: SSL shutdown failed: ssl=0x7f8f649380: I/O error during system call, Broken pipe
11-18 13:31:00.613   930  4881 D ConnectivityService: reportNetworkConnectivity(100, false) by 10012
11-18 13:31:00.614   930  5400 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Forcing reevaluation for UID 10012
,11-18 13:31:00.616   930  5400 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.gstatic.com": No address associated with hostname
,11-18 13:31:00.617   930  2983 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] validation failed
11-18 13:31:00.618   930  2983 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,11-18 13:31:00.618   930  5403 D DhcpClient: Receive thread stopped
11-18 13:31:00.619   930  2983 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,11-18 13:31:00.625   930  2983 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
11-18 13:31:00.625   930  2983 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
,11-18 13:31:00.630   533   533 E Parcel  : Reading a NULL string not supported here.
,11-18 13:31:00.633   930   930 D RttService: SCAN_AVAILABLE : 1
,11-18 13:31:00.633   930  3090 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
11-18 13:31:00.634   930  2983 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
11-18 13:31:00.638  3750  3908 W QCNEJ   : |CORE| network lost: 100
11-18 13:31:00.639  3750  3908 W QCNEJ   : |CORE| onLost: unbind the process to WIFI
,11-18 13:31:00.647   930  2981 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,11-18 13:31:00.655   930  2981 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,11-18 13:31:00.663   507   928 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-18 13:31:00.684   507   928 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
11-18 13:31:00.685   507   928 D CommandListener: Clearing all IP addresses on wlan0
,11-18 13:31:00.685   930  2983 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
11-18 13:31:00.685   930  2983 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
11-18 13:31:00.685   507   928 D TetherController: Setting IP forward enable = 0
,11-18 13:31:00.686   930  2981 D DhcpClient: doQuit
,11-18 13:31:00.687   930  2981 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,11-18 13:31:00.687   930  5402 D DhcpClient: onQuitting
11-18 13:31:00.687  3474  3474 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
11-18 13:31:00.688   930   947 D Tethering: MasterInitialState.processMessage what=3
,11-18 13:31:00.690  5286  5286 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@dc58f5f and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
11-18 13:31:00.693  3990  3990 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
,11-18 13:31:00.697  5072  5094 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
11-18 13:31:00.698  5072  5094 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
11-18 13:31:00.698  5072  5094 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,0,0,0
,11-18 13:31:00.699  5072  5094 E SarControlService: no key has been found,reset the power
11-18 13:31:00.699  5072  5109 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
11-18 13:31:00.699  5072  5109 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
11-18 13:31:00.699  5072  5109 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
11-18 13:31:00.700  5097  5097 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
11-18 13:31:00.700  5097  5097 D QcrilMsgTunnelSocket: [1002] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
11-18 13:31:00.700  3866  3866 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
11-18 13:31:00.703  3866  3866 D SystemUpdateService: onCreate
11-18 13:31:00.704  5072  5109 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
11-18 13:31:00.705  5072  5109 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
11-18 13:31:00.705  5072  5109 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
,11-18 13:31:00.706  5097  5111 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@fca0efd HexData = [00000000ea03000000000000ffffffff]
11-18 13:31:00.706  5097  5111 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-18 13:31:00.706  5097  5111 D QcrilMsgTunnelSocket: [1002] < OEM_HOOK_RAW [null]
11-18 13:31:00.707  3866  3866 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
11-18 13:31:00.707  5097  5097 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
11-18 13:31:00.707  5097  5097 D QcrilMsgTunnelSocket: [1003] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
11-18 13:31:00.709  5097  5097 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
11-18 13:31:00.709  5072  5082 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
11-18 13:31:00.710  3866  5794 I SystemUpdateService: active receiver: enabled
,11-18 13:31:00.715  3866  3866 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
11-18 13:31:00.716  3866  5794 I SystemUpdateService: OffPeak download feature is not enabled!
11-18 13:31:00.717  5097  5111 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@fca0efd HexData = [00000000eb03000000000000ffffffff]
11-18 13:31:00.717  5097  5111 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-18 13:31:00.717  5097  5111 D QcrilMsgTunnelSocket: [1003] < OEM_HOOK_RAW [null]
,11-18 13:31:00.717  5097  5097 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
11-18 13:31:00.718  5072  5083 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
11-18 13:31:00.718  3866  5794 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,11-18 13:31:00.718  3866  5794 I SystemUpdateService: now status is 0 (complete)
11-18 13:31:00.718  3866  5794 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
11-18 13:31:00.718  3866  5794 I SystemUpdateService: file has been verified
11-18 13:31:00.718  3866  5794 I SystemUpdateService: OTA package size = 21989297
11-18 13:31:00.718  3866  5424 I iu.UploadsManager: num queued entries: 0
11-18 13:31:00.719  3866  5424 I iu.UploadsManager: num updated entries: 0
11-18 13:31:00.719  3474  3474 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
,11-18 13:31:00.721  3866  5424 I iu.SyncManager: NEXT; no task
,11-18 13:31:00.722  3866  5794 I SystemUpdateService: showing system update notification
,11-18 13:31:00.727  3474  3474 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
11-18 13:31:00.730   507   921 W SocketClient: write error (Broken pipe)
,11-18 13:31:00.730   507   921 W SocketClient: Unable to send msg '600 Iface linkstate wlan0 up'
11-18 13:31:00.730   507   921 W SocketListener: Error sending broadcast (Broken pipe)
11-18 13:31:00.732  3866  3866 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
11-18 13:31:00.732   930   930 V NotificationService: pkg=com.google.android.gms canInterrupt=false intercept=true
11-18 13:31:00.733  3866  3866 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,11-18 13:31:00.746   930  3192 I ActivityManager: Start proc 5800:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,11-18 13:31:00.749  3866  3866 D SystemUpdateService: onDestroy
,11-18 13:31:00.758   507   928 E Netd    : netlink response contains error (No such file or directory)
11-18 13:31:00.760   930  2983 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,11-18 13:31:00.762  3474  3474 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
11-18 13:31:00.763   507   928 D TetherController: Setting IP forward enable = 0
,11-18 13:31:00.770  3474  3474 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,11-18 13:31:00.781  5800  5800 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm64
,11-18 13:31:00.784  5800  5800 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,11-18 13:31:00.789  5800  5800 D SprintDMHelper: simOperator: 
11-18 13:31:00.789  5800  5800 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,11-18 13:31:00.801  5039  5815 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,11-18 13:31:00.815   930  3626 I ActivityManager: Start proc 5816:com.google.android.apps.gcs/u0a11 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,11-18 13:31:00.840  5816  5816 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm64
,11-18 13:31:00.848   930  3626 I ActivityManager: Killing 5286:com.google.android.music:main/u0a59 (adj 15): empty #17
,11-18 13:31:00.874   930  2981 D wifi    : In wifi stop Hal
,11-18 13:31:00.874  5039  5039 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
11-18 13:31:00.874   930  2981 D wifi    : halHandle = 0x7f7cf2fe00, mVM = 0x7f994cd140, mCls = 0x100a02
11-18 13:31:00.874   930  3473 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
11-18 13:31:00.874   930  3473 D WifiHAL : Got a signal to exit!!!
11-18 13:31:00.874   930  3473 I WifiHAL : Exit wifi_event_loop
11-18 13:31:00.875   930  2981 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 0
11-18 13:31:00.875   930  2981 E WifiHAL : Event processing terminated
11-18 13:31:00.875   930  2981 D wifi    : In wifi cleaned up handler
11-18 13:31:00.875   930  2981 I WifiHAL : Internal cleanup completed
,11-18 13:31:00.877  4076  4250 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,11-18 13:31:00.900   930  3473 D wifi    : set interface wlan0 flags (DOWN)
,11-18 13:31:00.901   930  2981 D WifiNative-HAL: HAL event thread stopped successfully
,11-18 13:31:01.078  5627  5689 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-18 13:31:01.078  5627  5689 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-18 13:31:01.078  5627  5689 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-18 13:31:01.078  5627  5689 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-18 13:31:01.078  5627  5689 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-18 13:31:01.078  5627  5689 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-18 13:31:01.078  5627  5689 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-18 13:31:01.078  5627  5689 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-18 13:31:01.078  5627  5689 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,11-18 13:31:01.085  5627  5689 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
,11-18 13:31:01.090   930  3727 D WifiService: setWifiEnabled: true pid=5627, uid=10077
11-18 13:31:01.091   930  3727 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
11-18 13:31:01.092  5627  5674 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-18 13:31:01.106   507   928 D SoftapController: Softap fwReload - Ok
,11-18 13:31:01.107   930   947 D Tethering: InitialState.processMessage what=4
,11-18 13:31:01.113   507   928 D CommandListener: Setting iface cfg
,11-18 13:31:01.113   507   928 D CommandListener: Trying to bring down wlan0
11-18 13:31:01.114   507   928 D CommandListener: Clearing all IP addresses on wlan0
11-18 13:31:01.115   930   947 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,11-18 13:31:01.119   930  2981 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,11-18 13:31:01.599   930  3626 D WifiService: setWifiEnabled: true pid=5627, uid=10077
,11-18 13:31:01.602   930  3626 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-18 13:31:01.712   930  2981 D wifi    : set interface wlan0 flags (UP)
,11-18 13:31:01.713   930  2981 I WifiHAL : Initializing wifi
,11-18 13:31:01.713   930  2981 I WifiHAL : Creating socket
,11-18 13:31:01.719   930   947 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,11-18 13:31:01.725   930  2981 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
,11-18 13:31:01.725   930  2981 D wifi    : Did set static halHandle = 0x7f7cf2fe00
11-18 13:31:01.725   930  2981 D wifi    : halHandle = 0x7f7cf2fe00, mVM = 0x7f994cd140, mCls = 0x18be
11-18 13:31:01.725   930  2981 D wifi    : array field set
11-18 13:31:01.725   930  2981 I WifiNative-HAL: interface[0] = wlan0
,11-18 13:31:01.728   930  5833 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=547557146112
11-18 13:31:01.728   930  5833 D wifi    : waitForHalEvents called, vm = 0x7f994cd140, obj = 0x18be, env = 0x7f7dd9ea00
,11-18 13:31:01.803  5834  5834 I wpa_supplicant: Successfully initialized wpa_supplicant
,11-18 13:31:01.829   930  2981 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,11-18 13:31:01.879  5834  5834 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,11-18 13:31:01.884  5834  5834 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,11-18 13:31:01.884  5834  5834 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,11-18 13:31:01.898   930  2981 D WifiConfigStore: Loading config and enabling all networks 
,11-18 13:31:01.915   930  2981 D WifiConfigStore: loaded 0 passpoint configs
,11-18 13:31:01.916   930  2981 W WifiConfigStore: Upgrading network 4 to android.uid.system:1000
11-18 13:31:01.916   930  2981 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
11-18 13:31:01.917   930  2981 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,11-18 13:31:01.917   930  2981 W WifiConfigStore: Upgrading network 3 to android.uid.system:1000
11-18 13:31:01.917   930  2981 W WifiConfigStore: Upgrading network 2 to android.uid.system:1000
11-18 13:31:01.918   930  2981 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,11-18 13:31:01.918   930  2981 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 5
11-18 13:31:01.918   930  2981 E WifiConfigStore: found sortedWifiConfigurations : "AndroidAP"WPA_PSK
11-18 13:31:01.918   930  2981 E WifiConfigStore: found sortedWifiConfigurations : "AndroidHotspot2346"WPA_PSK
11-18 13:31:01.918   930  2981 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
11-18 13:31:01.918   930  2981 E WifiConfigStore: found sortedWifiConfigurations : "Thali_internal"WPA_PSK
11-18 13:31:01.918   930  2981 E WifiConfigStore: found sortedWifiConfigurations : "MC"WPA_PSK
,11-18 13:31:01.920   930  2981 D WifiNative-HAL: Setting external_sim to 1
,11-18 13:31:01.920   930  2981 D wifi    : setting dfs flag to true, 0x7f81f2fe20
11-18 13:31:01.920  5039  5039 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
11-18 13:31:01.921   930  2981 D WifiStateMachine: Setting OUI to DA-A1-19
11-18 13:31:01.921   930  2981 D wifi    : setting scan oui 0x7f81f2fe20
,11-18 13:31:01.921   930  2981 D WifiHAL : Sending mac address OUI
,11-18 13:31:01.923   930  2981 E native  : do suspend false
,11-18 13:31:01.929   930  2981 D wifi    : android_net_wifi_setLinkLayerStats: 1
,11-18 13:31:01.930   930   930 D RttService: SCAN_AVAILABLE : 3
11-18 13:31:01.930   930  3090 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,11-18 13:31:01.934   507   928 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,11-18 13:31:01.935   507   928 D CommandListener: Setting iface cfg
,11-18 13:31:01.937   930  2980 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '124 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 124 Failed to set address (No such device)'
,11-18 13:31:01.937   930  2980 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,11-18 13:31:01.941   930  2980 D WifiNative-HAL: p2pGetDeviceAddress
,11-18 13:31:01.945   930  2980 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:70
11-18 13:31:01.945   930   945 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=107152 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=11 mControllerEnergyUsed=41 }
,11-18 13:31:02.113  5627  5689 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-18 13:31:02.113  5627  5689 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-18 13:31:02.113  5627  5689 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-18 13:31:02.113  5627  5689 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-18 13:31:02.113  5627  5689 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-18 13:31:02.113  5627  5689 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-18 13:31:02.113  5627  5689 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-18 13:31:02.113  5627  5689 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-18 13:31:02.113  5627  5689 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,11-18 13:31:02.118  5627  5689 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
,11-18 13:31:02.122  5627  5674 D BluetoothAdapter: enable(): BT is already enabled..!
,11-18 13:31:02.123   930  3727 D WifiService: setWifiEnabled: true pid=5627, uid=10077
,11-18 13:31:02.124   930  3727 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
11-18 13:31:02.125  5627  5674 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,11-18 13:31:02.125  5627  5674 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-18 13:31:02.126  5627  5674 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-18 13:31:02.126  5627  5674 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6c6362e removed from the list
11-18 13:31:02.126  5627  5674 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-18 13:31:02.127  5627  5674 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c7b45cf removed from the list
,11-18 13:31:02.127  5627  5674 D io.jxcore.node.ConnectivityMonitor: stop
,11-18 13:31:02.132  5627  5674 I io.jxcore.node.IncomingSocketThreadTest: Starting test: testSetTcpPortNumber
,11-18 13:31:02.133  5627  5674 I io.jxcore.node.IncomingSocketThreadTest: Starting test: testGetTcpPortNumber
,11-18 13:31:02.135  5627  5674 I io.jxcore.node.IncomingSocketThreadTest: Starting test: testGetLocalHostPort
,11-18 13:31:02.137  5627  5674 I io.jxcore.node.IncomingSocketThreadTest: Starting test: testConstructor
,11-18 13:31:02.140  5627  5674 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityCreated
11-18 13:31:02.141  5627  5674 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,11-18 13:31:02.143  5627  5674 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityResumed
,11-18 13:31:02.143  5627  5674 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,11-18 13:31:02.144  5627  5674 I io.jxcore.node.LifeCycleMonitorTest: Starting test: constructor
,11-18 13:31:02.147  5627  5674 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivitySaveInstanceState
11-18 13:31:02.147  5627  5674 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@38b0ffa Bundle[{}]
11-18 13:31:02.148  5627  5674 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testStartStop
11-18 13:31:02.148  5627  5674 I io.jxcore.node.LifeCycleMonitor: start: OK
,11-18 13:31:02.148  5627  5674 I io.jxcore.node.LifeCycleMonitor: stop: OK
11-18 13:31:02.148  5627  5674 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityStarted
11-18 13:31:02.148  5627  5674 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
11-18 13:31:02.149  5627  5674 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityStopped
,11-18 13:31:02.149  5627  5674 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,11-18 13:31:02.150  5627  5674 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityDestroyed
11-18 13:31:02.150  5627  5674 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
11-18 13:31:02.151  5627  5674 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityPaused
11-18 13:31:02.152  5627  5674 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
11-18 13:31:02.153  5627  5674 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testToString
11-18 13:31:02.154  5627  5674 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testToJsonObject
,11-18 13:31:02.155  5627  5674 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testConstructorWithParameters
11-18 13:31:02.155  5627  5674 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testSetListeningOnPortNumber
11-18 13:31:02.156  5627  5674 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testGetListeningOnPortNumber
11-18 13:31:02.156  5627  5674 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testDefaultConstructor
11-18 13:31:02.157  5627  5674 I io.jxcore.node.OutgoingSocketThreadTest: Starting test: testClose
,11-18 13:31:02.159  5627  5674 I io.jxcore.node.OutgoingSocketThreadTest: Starting test: testGetListeningOnPortNumber
11-18 13:31:02.160  5627  5674 I io.jxcore.node.OutgoingSocketThreadTest: Starting test: testConstructor
,11-18 13:31:02.161  5627  5674 I io.jxcore.node.SocketThreadBaseTest: Starting test: testGetListener
,11-18 13:31:02.162  5627  5674 I io.jxcore.node.SocketThreadBaseTest: Starting test: testSetPeerProperties
,11-18 13:31:02.163  5627  5674 I io.jxcore.node.SocketThreadBaseTest: Starting test: testClose
,11-18 13:31:02.164  5627  5674 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 141)
11-18 13:31:02.164  5627  5674 I io.jxcore.node.SocketThreadBaseTest: Starting test: testCloseLocalSocketAndStreams
11-18 13:31:02.164  5627  5674 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
11-18 13:31:02.164  5627  5674 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 142)
11-18 13:31:02.165  5627  5674 I io.jxcore.node.SocketThreadBaseTest: Starting test: testGetPeerProperties
11-18 13:31:02.165  5627  5674 I io.jxcore.node.SocketThreadBaseTest: Starting test: testEquals
,11-18 13:31:02.166  5627  5674 I io.jxcore.node.SocketThreadBaseTest: Starting test: testGetLocalHostAddressAsString
11-18 13:31:02.166  5627  5674 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-18 13:31:02.166  5627  5674 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5683e65 added. We now have 3 listener(s)
11-18 13:31:02.167  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-18 13:31:02.168  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-18 13:31:02.168  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-18 13:31:02.168  5627  5674 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-18 13:31:02.168  5627  5674 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@783873a added. We now have 3 listener(s)
,11-18 13:31:02.168  5627  5674 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-18 13:31:02.169  5627  5674 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,11-18 13:31:02.173  5627  5674 I io.jxcore.node.StartStopOperationHandlerTest: Starting test: testCancelCurrentOperation
11-18 13:31:02.173  5627  5674 I io.jxcore.node.StartStopOperationHandlerTest: Starting test: testExecuteStopOperation
11-18 13:31:02.173  5627  5674 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 5
11-18 13:31:02.173  5627  5674 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 4 -> 5
,11-18 13:31:02.173  5627  5674 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-61,5,main], id: 61
,11-18 13:31:02.174  5627  5674 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-61,5,main], id: 61
,11-18 13:31:02.174  5627  5674 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-61,5,main], id: 61
11-18 13:31:02.174  5627  5674 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
11-18 13:31:02.174  5627  5674 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
,11-18 13:31:02.174  5627  5674 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
11-18 13:31:02.174  5627  5674 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-18 13:31:02.174  5627  5674 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
,11-18 13:31:02.178  5627  5674 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
11-18 13:31:02.179  5627  5674 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,11-18 13:31:02.179  5627  5674 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
11-18 13:31:02.179  5627  5674 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
11-18 13:31:02.179  5627  5674 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
11-18 13:31:02.179  5627  5674 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
11-18 13:31:02.179  5627  5674 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-18 13:31:02.179  5627  5837 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
11-18 13:31:02.179  5627  5674 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
11-18 13:31:02.179  5627  5627 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
11-18 13:31:02.180  5627  5837 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-18 13:31:02.182  5627  5674 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
,11-18 13:31:02.182  5627  5674 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-18 13:31:02.183  5627  5674 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,11-18 13:31:02.180  5767  5767 W Binder_3: type=1400 audit(0.0:122): avc: denied { ioctl } for path="socket:[33858]" dev="sockfs" ino=33858 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-18 13:31:02.184  5627  5837 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
11-18 13:31:02.180  5767  5767 W Binder_3: type=1400 audit(0.0:123): avc: denied { ioctl } for path="socket:[33858]" dev="sockfs" ino=33858 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,11-18 13:31:02.187  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-61,5,main], id: 61
,11-18 13:31:02.187  5627  5674 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,11-18 13:31:02.188  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-18 13:31:02.188  5627  5674 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-18 13:31:02.188  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 5
,11-18 13:31:02.190  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
,11-18 13:31:02.191  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-61,5,main], id: 61
11-18 13:31:02.191  5627  5674 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
11-18 13:31:02.191  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: createAdvertiseDataToServiceData 
11-18 13:31:02.191  5627  5674 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-18 13:31:02.191  5627  5674 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 05 60 83 34 25 D7 D4
,11-18 13:31:02.191  5627  5674 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[5, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-18 13:31:02.191  5627  5674 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: created AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[5, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-18 13:31:02.192  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: Current thread: Thread[Thread-61,5,main], id: 61
11-18 13:31:02.192  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: was started = false
11-18 13:31:02.192  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: advertiseData = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[5, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,11-18 13:31:02.192  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData finished: Current thread: Thread[Thread-61,5,main], id: 61
11-18 13:31:02.192  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
11-18 13:31:02.192  5627  5674 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... adv data = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[5, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]Current thread: Thread[Thread-61,5,main], id: 61
,11-18 13:31:02.193  5627  5674 D BluetoothAdapter: STATE_ON
,11-18 13:31:02.197  5725  5736 D BtGatt.GattService: registerClient() - UUID=9706a49e-0921-4add-8d40-f26bbaf82f5e
,11-18 13:31:02.198  5725  5743 D BtGatt.GattService: onClientRegistered() - UUID=9706a49e-0921-4add-8d40-f26bbaf82f5e, clientIf=5
,11-18 13:31:02.198  5627  5638 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
,11-18 13:31:02.200  5725  5745 D BtGatt.AdvertiseManager: message : 0
,11-18 13:31:02.201  5725  5745 D BtGatt.AdvertiseManager: starting multi advertising
,11-18 13:31:02.211  5725  5743 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,11-18 13:31:02.216  5725  5743 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,11-18 13:31:02.217  5627  5674 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment Current thread: Thread[Thread-61,5,main], id: 61
11-18 13:31:02.217  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTINGCurrent thread: Thread[Thread-61,5,main], id: 61
11-18 13:31:02.217  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
11-18 13:31:02.217  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged default (no call to listener). Current thread: Thread[Thread-61,5,main], id: 61
,11-18 13:31:02.217  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-61,5,main], id: 61
11-18 13:31:02.217  5627  5674 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[Thread-61,5,main], id: 61
11-18 13:31:02.217  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[Thread-61,5,main], id: 61
11-18 13:31:02.217  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser started = true Current thread: Thread[Thread-61,5,main], id: 61
11-18 13:31:02.218  5627  5674 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,11-18 13:31:02.219  5627  5674 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-18 13:31:02.219  5627  5674 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-18 13:31:02.220  5627  5674 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
,11-18 13:31:02.220  5627  5674 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-18 13:31:02.221  5627  5674 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-18 13:31:02.221  5627  5627 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
11-18 13:31:02.221  5627  5627 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess : Current thread: Thread[main,5,main], id: 1
11-18 13:31:02.221  5627  5627 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNINGCurrent thread: Thread[main,5,main], id: 1
11-18 13:31:02.221  5627  5627 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
,11-18 13:31:02.221  5627  5627 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  true. Current thread: Thread[main,5,main], id: 1
11-18 13:31:02.221  5627  5627 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[main,5,main], id: 1
11-18 13:31:02.221  5627  5627 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-18 13:31:02.221  5627  5627 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-18 13:31:02.221  5627  5627 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [ADVERTISING]
11-18 13:31:02.221  5627  5627 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-18 13:31:02.221  5627  5627 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
,11-18 13:31:02.221  5627  5627 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]Current thread: Thread[main,5,main], id: 1
11-18 13:31:02.221  5627  5627 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
11-18 13:31:02.222  5627  5627 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-18 13:31:02.223  5627  5627 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-18 13:31:02.224  5627  5627 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
11-18 13:31:02.224  5627  5627 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-18 13:31:02.224  5627  5627 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
,11-18 13:31:02.224  5627  5627 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-18 13:31:02.224  5627  5627 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,11-18 13:31:02.725  5627  5627 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
11-18 13:31:02.725  5627  5627 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
11-18 13:31:02.725  5627  5627 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,11-18 13:31:04.512   930  3823 I ActivityManager: Killing 3922:com.android.providers.calendar/u0a1 (adj 15): empty #17
,11-18 13:31:05.007  5834  5834 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-18 13:31:05.028  5834  5834 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-18 13:31:05.043  5834  5834 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-18 13:31:05.051  5834  5834 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-18 13:31:05.082   930  2981 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,11-18 13:31:05.083   930  2981 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3
,11-18 13:31:05.084   930  2981 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-18 13:31:05.098   930  2981 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=0
,11-18 13:31:05.131   930  2981 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=0
,11-18 13:31:05.136  5834  5834 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,11-18 13:31:05.572  5834  5834 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,11-18 13:31:05.607  5834  5834 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,11-18 13:31:05.608  5834  5834 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,11-18 13:31:05.620   930  2981 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,11-18 13:31:05.621   930  2981 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
11-18 13:31:05.621   930  2983 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,11-18 13:31:05.639   930  2981 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-18 13:31:05.654   507   928 D CommandListener: Setting iface cfg
,11-18 13:31:05.660   930  2981 D WifiStateMachine: Start Dhcp Watchdog 2
,11-18 13:31:05.667   930  5844 D DhcpClient: Receive thread started
,11-18 13:31:05.671   930  2983 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-18 13:31:05.671   930  2981 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
11-18 13:31:05.671   930  2983 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
,11-18 13:31:05.723  5627  5674 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
,11-18 13:31:05.723  5627  5674 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,11-18 13:31:05.723  5627  5674 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
,11-18 13:31:05.723  5627  5674 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
,11-18 13:31:05.723  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
11-18 13:31:05.724  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,11-18 13:31:05.724  5627  5837 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
11-18 13:31:05.724  5627  5837 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
11-18 13:31:05.724  5627  5674 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
,11-18 13:31:05.724  5627  5674 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
11-18 13:31:05.724  5627  5837 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
11-18 13:31:05.725  5627  5674 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
11-18 13:31:05.725  5627  5674 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,11-18 13:31:05.725  5627  5627 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
11-18 13:31:05.725  5627  5674 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
11-18 13:31:05.725  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-18 13:31:05.725  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
11-18 13:31:05.725  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-61,5,main], id: 61
,11-18 13:31:05.726  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-18 13:31:05.726  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-61,5,main], id: 61
,11-18 13:31:05.728  5627  5674 D BluetoothAdapter: STATE_ON
11-18 13:31:05.728  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-18 13:31:05.730  5627  5674 D BluetoothAdapter: STATE_ON
11-18 13:31:05.730  5627  5674 D BluetoothLeScanner: could not find callback wrapper
11-18 13:31:05.730  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-18 13:31:05.730  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-18 13:31:05.730  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-61,5,main], id: 61
11-18 13:31:05.731  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-61,5,main], id: 61
11-18 13:31:05.731  5627  5674 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
11-18 13:31:05.731  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-61,5,main], id: 61
11-18 13:31:05.733  5725  5745 D BtGatt.AdvertiseManager: message : 1
11-18 13:31:05.734  5725  5745 D BtGatt.AdvertiseManager: stop advertise for client 5
,11-18 13:31:05.750  5725  5743 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
11-18 13:31:05.750  5725  5743 D BtGatt.GattService: Client app is not null!
,11-18 13:31:05.752  5725  5770 D BtGatt.GattService: unregisterClient() - clientIf=5
,11-18 13:31:05.753  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-18 13:31:05.753  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
11-18 13:31:05.753  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
11-18 13:31:05.753  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  false. Current thread: Thread[Thread-61,5,main], id: 61
11-18 13:31:05.753  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-61,5,main], id: 61
11-18 13:31:05.754  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-61,5,main], id: 61
11-18 13:31:05.754  5627  5674 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-18 13:31:05.754  5627  5674 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,11-18 13:31:05.755  5627  5674 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
11-18 13:31:05.755  5627  5674 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-18 13:31:05.757  5627  5674 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
,11-18 13:31:05.757  5627  5674 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-18 13:31:05.757   930  2981 E native  : do suspend false
11-18 13:31:05.757  5627  5674 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
,11-18 13:31:05.758  5627  5674 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-18 13:31:05.758  5627  5627 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-18 13:31:05.758  5627  5627 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,11-18 13:31:05.758  5627  5627 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
11-18 13:31:05.758  5627  5627 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-18 13:31:05.758  5627  5627 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-18 13:31:05.759  5627  5627 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-18 13:31:05.759  5627  5627 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
,11-18 13:31:05.759  5627  5627 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-18 13:31:05.759  5627  5627 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-18 13:31:05.759  5627  5627 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [ADVERTISING]
,11-18 13:31:05.759  5627  5627 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-18 13:31:05.759  5627  5627 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-18 13:31:05.759  5627  5627 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
,11-18 13:31:05.760  5627  5627 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-18 13:31:05.762  5627  5627 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-18 13:31:05.763  5627  5674 I io.jxcore.node.StartStopOperationHandlerTest: Starting test: testCheckCurrentOperationStatus
11-18 13:31:05.763  5627  5627 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-18 13:31:05.763  5627  5674 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,11-18 13:31:05.763  5627  5627 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-18 13:31:05.763  5627  5627 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-18 13:31:05.764  5627  5674 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-18 13:31:05.764  5627  5627 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-18 13:31:05.764  5627  5674 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
11-18 13:31:05.764  5627  5674 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
11-18 13:31:05.764  5627  5674 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-18 13:31:05.765  5627  5674 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
11-18 13:31:05.768  5627  5674 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,11-18 13:31:05.774   930  5843 D DhcpClient: Broadcasting DHCPDISCOVER
,11-18 13:31:05.776  5627  5674 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
,11-18 13:31:05.776  5627  5674 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-18 13:31:05.776  5627  5674 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,11-18 13:31:05.781  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-61,5,main], id: 61
,11-18 13:31:05.781  5627  5674 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,11-18 13:31:05.782  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-18 13:31:05.782  5627  5674 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,11-18 13:31:05.782  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 5
,11-18 13:31:05.785  5627  5674 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
,11-18 13:31:05.788   930  5844 D DhcpClient: Received packet: 60:83:34:25:d7:70 OFFER, ip /192.168.1.109, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172730, domain null
,11-18 13:31:05.788   930  5843 D DhcpClient: Got pending lease: IP address 192.168.1.109/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172730 seconds
11-18 13:31:05.789  5627  5674 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
11-18 13:31:05.789  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-61,5,main], id: 61
,11-18 13:31:05.789  5627  5674 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
11-18 13:31:05.789  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
11-18 13:31:05.789  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
11-18 13:31:05.789   930  5843 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.109 serverid=192.168.1.1
,11-18 13:31:05.790  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
11-18 13:31:05.790  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-61,5,main], id: 61
11-18 13:31:05.791  5627  5674 D BluetoothAdapter: STATE_ON
,11-18 13:31:05.797  5725  5736 D BtGatt.GattService: registerClient() - UUID=90a2c222-f325-453e-96dc-c173b1a0b345
,11-18 13:31:05.797  5725  5743 D BtGatt.GattService: onClientRegistered() - UUID=90a2c222-f325-453e-96dc-c173b1a0b345, clientIf=5
11-18 13:31:05.798  5627  5638 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
11-18 13:31:05.799  5725  5767 D BtGatt.GattService: start scan with filters
,11-18 13:31:05.802  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
11-18 13:31:05.803  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
,11-18 13:31:05.803  5725  5746 D BtGatt.ScanManager: handling starting scan
11-18 13:31:05.803  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
11-18 13:31:05.803  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-61,5,main], id: 61
11-18 13:31:05.804  5627  5674 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-18 13:31:05.804  5627  5627 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-18 13:31:05.804  5627  5627 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-18 13:31:05.804  5627  5627 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
11-18 13:31:05.804  5627  5627 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-18 13:31:05.804  5627  5627 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-18 13:31:05.804  5627  5627 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
11-18 13:31:05.804  5627  5627 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
11-18 13:31:05.804  5725  5746 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7dee38f
11-18 13:31:05.805  5627  5674 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-18 13:31:05.805  5627  5674 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-18 13:31:05.808  5627  5674 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-18 13:31:05.808  5627  5674 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
11-18 13:31:05.808  5627  5674 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-18 13:31:05.808   930  5844 D DhcpClient: Received packet: 60:83:34:25:d7:70 ACK: your new IP /192.168.1.109, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
11-18 13:31:05.808  5627  5674 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-18 13:31:05.809  5627  5627 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-18 13:31:05.809   930  5843 D DhcpClient: Confirmed lease: IP address 192.168.1.109/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
11-18 13:31:05.810   507   928 D CommandListener: Setting iface cfg
11-18 13:31:05.811   930  2981 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,11-18 13:31:05.812  5627  5627 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-18 13:31:05.812  5627  5627 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-18 13:31:05.812  5627  5627 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-18 13:31:05.812  5627  5627 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-18 13:31:05.812  5627  5627 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,11-18 13:31:05.813  5725  5743 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
11-18 13:31:05.814  5725  5743 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-18 13:31:05.814  5725  5746 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,11-18 13:31:05.815   930  5843 D DhcpClient: Scheduling renewal in 86399s
,11-18 13:31:05.819  5725  5743 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
,11-18 13:31:05.819  5725  5743 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-18 13:31:05.819  5725  5746 D BtGatt.ScanManager: Starting BLE batch scan
11-18 13:31:05.819  5725  5746 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,11-18 13:31:05.821   930  2981 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
11-18 13:31:05.822   930  2981 D WifiConfigStore: No blacklist allowed without epno enabled
11-18 13:31:05.822   930  2983 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,11-18 13:31:05.823   930  2983 D ConnectivityService: Adding iface wlan0 to network 101
,11-18 13:31:05.824   930  2981 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,11-18 13:31:05.829  5725  5743 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,11-18 13:31:05.829  5725  5743 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-18 13:31:05.834  5725  5743 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,11-18 13:31:05.834  5725  5743 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-18 13:31:05.853   930  2983 E ConnectivityService: Unexpected mtu value: 0, wlan0
,11-18 13:31:05.853   930  2983 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
,11-18 13:31:05.855   930  2983 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,11-18 13:31:05.857   930  2983 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,11-18 13:31:05.859   930  2983 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,11-18 13:31:05.865   930  2983 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-18 13:31:05.869   930  2983 D ConnectivityService: scheduleUnvalidatedPrompt 101
,11-18 13:31:05.869   930  2983 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
11-18 13:31:05.869   930  2983 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
11-18 13:31:05.870   930  2983 D ConnectivityService:    accepting network in place of null
11-18 13:31:05.870   930  2981 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
11-18 13:31:05.870   930  2981 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
11-18 13:31:05.870   930  2983 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d770/64,192.168.1.109/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -51]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,11-18 13:31:05.889   507   928 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-18 13:31:05.908   507   928 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-18 13:31:05.910   930  2983 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,11-18 13:31:05.910   930  2983 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
11-18 13:31:05.910  3750  3908 W QCNEJ   : |CORE| network available: 101
11-18 13:31:05.911   930  2983 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
11-18 13:31:05.912   930   947 D Tethering: MasterInitialState.processMessage what=3
,11-18 13:31:05.914  3750  3908 W QCNEJ   : |CORE| onAvailable: bind the process to WIFI
,11-18 13:31:05.917  3750  3908 W QCNEJ   : |CORE| newLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d770/64,192.168.1.109/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}
,11-18 13:31:05.917  3750  3908 W QCNEJ   : |CORE| curLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d770/64,192.168.1.109/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
11-18 13:31:05.925  5072  5094 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
11-18 13:31:05.925  5072  5094 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
11-18 13:31:05.925  5072  5094 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,1,0,0
11-18 13:31:05.925  5072  5094 E SarControlService: no key has been found,reset the power
11-18 13:31:05.925  5072  5109 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
11-18 13:31:05.925  5072  5109 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
,11-18 13:31:05.925  5072  5109 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
11-18 13:31:05.926  5097  5097 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
11-18 13:31:05.926  5097  5097 D QcrilMsgTunnelSocket: [1004] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
11-18 13:31:05.927  3990  3990 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
11-18 13:31:05.928  5072  5109 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
,11-18 13:31:05.928  5072  5109 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
,11-18 13:31:05.928  5072  5109 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
,11-18 13:31:05.929  5097  5097 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
11-18 13:31:05.929  5097  5097 D QcrilMsgTunnelSocket: [1005] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
11-18 13:31:05.931  3866  3866 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
11-18 13:31:05.932  5097  5111 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@fca0efd HexData = [00000000ec03000000000000ffffffff]
11-18 13:31:05.932  5097  5111 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-18 13:31:05.932  5097  5111 D QcrilMsgTunnelSocket: [1004] < OEM_HOOK_RAW [null]
,11-18 13:31:05.934  5097  5111 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@fca0efd HexData = [00000000ed03000000000000ffffffff]
11-18 13:31:05.934  5097  5111 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-18 13:31:05.934  5097  5111 D QcrilMsgTunnelSocket: [1005] < OEM_HOOK_RAW [null]
11-18 13:31:05.935  5097  5097 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
11-18 13:31:05.935  5072  5082 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
11-18 13:31:05.935  5097  5097 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
11-18 13:31:05.935  5072  5083 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
11-18 13:31:05.936  3866  3866 D SystemUpdateService: onCreate
,11-18 13:31:05.940  3866  3866 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
11-18 13:31:05.941   930  5842 D NetlinkSocketObserver: NeighborEvent{elapsedMs=111147, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,11-18 13:31:05.949  3866  3866 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,11-18 13:31:05.956  3866  5424 I iu.UploadsManager: num queued entries: 0
,11-18 13:31:05.956  3866  5424 I iu.UploadsManager: num updated entries: 0
11-18 13:31:05.956  3866  5424 I iu.SyncManager: NEXT; no task
,11-18 13:31:05.958  3866  5855 I SystemUpdateService: active receiver: enabled
,11-18 13:31:05.959  3866  3866 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,11-18 13:31:05.961  3866  3866 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
11-18 13:31:05.962  5800  5800 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,11-18 13:31:05.966  5800  5800 D SprintDMHelper: simOperator: 
11-18 13:31:05.966  5800  5800 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,11-18 13:31:05.987  3866  5855 I SystemUpdateService: OffPeak download feature is not enabled!
,11-18 13:31:06.002  3866  5855 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,11-18 13:31:06.002  3866  5855 I SystemUpdateService: now status is 0 (complete)
11-18 13:31:06.002  3866  5855 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
11-18 13:31:06.002  3866  5855 I SystemUpdateService: file has been verified
11-18 13:31:06.002  3866  5855 I SystemUpdateService: OTA package size = 21989297
,11-18 13:31:06.007  3866  5855 I SystemUpdateService: showing system update notification
,11-18 13:31:06.009   930  5841 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.214.238,2a00:1450:400d:803::200e
,11-18 13:31:06.016   930   930 V NotificationService: pkg=com.google.android.gms canInterrupt=false intercept=true
,11-18 13:31:06.017  3866  3866 D SystemUpdateService: onDestroy
,11-18 13:31:06.060   930  5841 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Fri, 18 Nov 2016 12:31:06 GMT], X-Android-Received-Millis=[1479472266058], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1479472266034]}
,11-18 13:31:06.060   930  2983 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,11-18 13:31:06.060   930  2983 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation  passed
11-18 13:31:06.060   930  2983 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-18 13:31:06.061   930  2983 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,11-18 13:31:06.081  5039  5860 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,11-18 13:31:06.314  5627  5627 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,11-18 13:31:06.314  5627  5627 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
11-18 13:31:06.314  5627  5627 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,11-18 13:31:06.338  5725  5725 D BtGatt.ScanManager: awakened up at time 111544
,11-18 13:31:06.340  5725  5746 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-18 13:31:06.355  5725  5743 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,11-18 13:31:06.355  5725  5743 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-18 13:31:06.359  5627  5627 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: onBatchScanResults: results count  = 0. Current thread: Thread[main,5,main], id: 1
,11-18 13:31:06.859  5725  5725 D BtGatt.ScanManager: awakened up at time 112065
11-18 13:31:06.861  5725  5746 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-18 13:31:06.889  5725  5743 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,11-18 13:31:06.889  5725  5743 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-18 13:31:06.889  5725  5743 D BtGatt.GattService: current time is 112096108770
,11-18 13:31:06.890  5725  5743 D BtGatt.GattService: Batch record : [-46, -4, -117, 6, 105, -37, 1, -128, -84, 6, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 0]
11-18 13:31:06.894  5725  5743 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74]
11-18 13:31:06.900  5627  5627 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: onBatchScanResults: results count  = 1. Current thread: Thread[main,5,main], id: 1
,11-18 13:31:06.901  5627  5627 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: onBatchScanResults. scan = ScanResult{mDevice=DB:69:06:8B:FC:D2, mScanRecord=ScanRecord [mAdvertiseFlags=6, mServiceUuids=null, mManufacturerSpecificData={76=[2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74]}, mServiceData={}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-84, mTimestampNanos=111797367514}
11-18 13:31:06.901  5627  5627 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: ScanResult{mDevice=DB:69:06:8B:FC:D2, mScanRecord=ScanRecord [mAdvertiseFlags=6, mServiceUuids=null, mManufacturerSpecificData={76=[2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74]}, mServiceData={}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-84, mTimestampNanos=111797367514}
,11-18 13:31:06.911   930  2983 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,11-18 13:31:08.362   535   535 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,11-18 13:31:08.363   535   535 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,11-18 13:31:08.811  5627  5674 I io.jxcore.node.StartStopOperationHandlerTest: Starting test: testExecuteStartOperation
,11-18 13:31:08.812  5627  5674 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 6
11-18 13:31:08.812  5627  5674 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 5 -> 6
11-18 13:31:08.812  5627  5674 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-61,5,main], id: 61
11-18 13:31:08.813  5627  5674 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-61,5,main], id: 61
11-18 13:31:08.813  5627  5674 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-61,5,main], id: 61
11-18 13:31:08.813  5627  5674 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
11-18 13:31:08.813  5627  5674 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Manufacturer ID: 7413
11-18 13:31:08.813  5627  5674 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad length and type: 533
11-18 13:31:08.813  5627  5674 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad extra information: 6
11-18 13:31:08.813  5627  5674 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
11-18 13:31:08.813  5627  5674 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 2
11-18 13:31:08.813  5627  5674 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 3
11-18 13:31:08.813  5627  5674 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 2
11-18 13:31:08.813  5627  5674 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
11-18 13:31:08.813  5627  5674 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Current thread: Thread[Thread-61,5,main], id: 61
11-18 13:31:08.813  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 6
11-18 13:31:08.814  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: advertiserWasStarted false Current thread: Thread[Thread-61,5,main], id: 61
,11-18 13:31:08.814  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-61,5,main], id: 61
11-18 13:31:08.814  5627  5674 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-18 13:31:08.814  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-18 13:31:08.814  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: scannerWasStarted true Current thread: Thread[Thread-61,5,main], id: 61
11-18 13:31:08.815  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: stop scanner Current thread: Thread[Thread-61,5,main], id: 61
11-18 13:31:08.815  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-61,5,main], id: 61
11-18 13:31:08.818  5627  5674 D BluetoothAdapter: STATE_ON
11-18 13:31:08.819  5725  5736 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
11-18 13:31:08.820  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-18 13:31:08.821  5725  5746 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
11-18 13:31:08.824  5627  5674 D BluetoothAdapter: STATE_ON
11-18 13:31:08.825  5725  5735 D BtGatt.GattService: stopScan() - queue size =1
11-18 13:31:08.827  5725  5770 D BtGatt.GattService: unregisterClient() - clientIf=5
11-18 13:31:08.828  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-18 13:31:08.828  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-18 13:31:08.829  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
11-18 13:31:08.829  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-61,5,main], id: 61
11-18 13:31:08.829  5627  5674 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-18 13:31:08.829  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: start scanner Current thread: Thread[Thread-61,5,main], id: 61
11-18 13:31:08.829  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-18 13:31:08.830  5627  5674 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
11-18 13:31:08.830  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,11-18 13:31:08.830  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
11-18 13:31:08.831  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
11-18 13:31:08.831  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-61,5,main], id: 61
11-18 13:31:08.832  5627  5674 D BluetoothAdapter: STATE_ON
,11-18 13:31:08.832  5725  5725 D BtGatt.ScanManager: awakened up at time 114039
11-18 13:31:08.836  5725  5767 D BtGatt.GattService: registerClient() - UUID=8d081b71-738b-4302-a16d-1b387c590d30
11-18 13:31:08.837  5725  5743 D BtGatt.GattService: onClientRegistered() - UUID=8d081b71-738b-4302-a16d-1b387c590d30, clientIf=5
11-18 13:31:08.838  5627  5637 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,11-18 13:31:08.838  5725  5735 D BtGatt.GattService: start scan with filters
,11-18 13:31:08.842  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
11-18 13:31:08.842  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-18 13:31:08.842  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,11-18 13:31:08.842  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-61,5,main], id: 61
11-18 13:31:08.842  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: start scanner started = true Current thread: Thread[Thread-61,5,main], id: 61
11-18 13:31:08.842  5627  5627 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-18 13:31:08.842  5627  5674 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
11-18 13:31:08.842  5627  5627 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-18 13:31:08.842  5627  5674 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
,11-18 13:31:08.842  5627  5674 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
11-18 13:31:08.843  5627  5627 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
11-18 13:31:08.843  5627  5674 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,11-18 13:31:08.843  5627  5627 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
11-18 13:31:08.843  5627  5627 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-18 13:31:08.843  5627  5627 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-18 13:31:08.844  5627  5674 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,11-18 13:31:08.844  5767  5767 W Binder_3: type=1400 audit(0.0:124): avc: denied { ioctl } for path="socket:[33962]" dev="sockfs" ino=33962 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-18 13:31:08.844  5767  5767 W Binder_3: type=1400 audit(0.0:125): avc: denied { ioctl } for path="socket:[33962]" dev="sockfs" ino=33962 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,11-18 13:31:08.845  5627  5674 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
11-18 13:31:08.845  5627  5674 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
11-18 13:31:08.845  5627  5674 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
11-18 13:31:08.845  5627  5674 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
11-18 13:31:08.845  5627  5674 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: true
,11-18 13:31:08.845  5627  5627 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
11-18 13:31:08.845  5627  5867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
,11-18 13:31:08.846  5627  5867 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-18 13:31:08.847  5725  5743 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
11-18 13:31:08.848  5725  5743 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-18 13:31:08.848  5725  5743 D BtGatt.GattService: current time is 114054876872
11-18 13:31:08.848  5725  5743 D BtGatt.GattService: Batch record : [35, 97, 126, -92, 22, -56, 1, -128, -82, 30, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 0]
11-18 13:31:08.848  5627  5867 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
11-18 13:31:08.848  5627  5674 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-18 13:31:08.848  5725  5743 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74]
,11-18 13:31:08.849  5627  5674 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,11-18 13:31:08.855  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser : Current thread: Thread[Thread-61,5,main], id: 61
11-18 13:31:08.855  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
11-18 13:31:08.855  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-61,5,main], id: 61
,11-18 13:31:08.855  5627  5674 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
11-18 13:31:08.856  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: createAdvertiseDataToServiceData 
11-18 13:31:08.856  5627  5674 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-18 13:31:08.856  5627  5674 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 06 60 83 34 25 D7 D4
11-18 13:31:08.856  5627  5674 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[6, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-18 13:31:08.856  5627  5674 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: created AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[6, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-18 13:31:08.856  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: Current thread: Thread[Thread-61,5,main], id: 61
11-18 13:31:08.856  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: was started = false
11-18 13:31:08.856  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: advertiseData = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[6, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-18 13:31:08.856  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData finished: Current thread: Thread[Thread-61,5,main], id: 61
11-18 13:31:08.856  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
11-18 13:31:08.856  5725  5743 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
11-18 13:31:08.856  5725  5743 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-18 13:31:08.856  5627  5674 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... adv data = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[6, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]Current thread: Thread[Thread-61,5,main], id: 61
,11-18 13:31:08.857  5725  5746 D BtGatt.ScanManager: stopping BLe Batch
,11-18 13:31:08.858  5627  5674 D BluetoothAdapter: STATE_ON
11-18 13:31:08.860  5725  5736 D BtGatt.GattService: registerClient() - UUID=a165b317-0306-4730-9d64-79921b13faa1
,11-18 13:31:08.861  5725  5743 D BtGatt.GattService: onClientRegistered() - UUID=a165b317-0306-4730-9d64-79921b13faa1, clientIf=6
11-18 13:31:08.861  5627  5637 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
,11-18 13:31:08.862  5725  5745 D BtGatt.AdvertiseManager: message : 0
,11-18 13:31:08.862  5725  5743 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
11-18 13:31:08.862  5725  5743 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-18 13:31:08.863  5725  5746 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-18 13:31:08.864  5725  5745 D BtGatt.AdvertiseManager: starting multi advertising
,11-18 13:31:08.868  5725  5743 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,11-18 13:31:08.868  5725  5743 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-18 13:31:08.871  5725  5746 D BtGatt.ScanManager: handling starting scan
,11-18 13:31:08.877  5725  5743 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0
,11-18 13:31:08.881  5725  5743 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,11-18 13:31:08.881  5725  5743 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-18 13:31:08.882  5725  5746 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,11-18 13:31:08.886  5725  5743 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0
,11-18 13:31:08.886  5627  5674 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment Current thread: Thread[Thread-61,5,main], id: 61
,11-18 13:31:08.887  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTINGCurrent thread: Thread[Thread-61,5,main], id: 61
11-18 13:31:08.887  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
11-18 13:31:08.887  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged default (no call to listener). Current thread: Thread[Thread-61,5,main], id: 61
11-18 13:31:08.887  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-61,5,main], id: 61
11-18 13:31:08.887  5627  5674 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[Thread-61,5,main], id: 61
11-18 13:31:08.887  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[Thread-61,5,main], id: 61
11-18 13:31:08.887  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser started = true Current thread: Thread[Thread-61,5,main], id: 61
11-18 13:31:08.887  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser: advertiser is started. Current thread: Thread[Thread-61,5,main], id: 61
11-18 13:31:08.887  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-18 13:31:08.887  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-61,5,main], id: 61
11-18 13:31:08.887  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Already running
,11-18 13:31:08.887  5627  5674 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser: adv = true, disc = true
11-18 13:31:08.888  5627  5674 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-18 13:31:08.889  5627  5674 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-18 13:31:08.889  5627  5674 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-18 13:31:08.892  5725  5743 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
11-18 13:31:08.892  5627  5674 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
,11-18 13:31:08.892  5725  5743 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-18 13:31:08.892  5627  5674 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-18 13:31:08.892  5627  5674 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-18 13:31:08.892  5725  5746 D BtGatt.ScanManager: Starting BLE batch scan
11-18 13:31:08.892  5725  5746 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,11-18 13:31:08.892  5627  5627 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
,11-18 13:31:08.893  5627  5627 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: onBatchScanResults: results count  = 1. Current thread: Thread[main,5,main], id: 1
11-18 13:31:08.893  5627  5627 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: onBatchScanResults. scan = ScanResult{mDevice=C8:16:A4:7E:61:23, mScanRecord=ScanRecord [mAdvertiseFlags=6, mServiceUuids=null, mManufacturerSpecificData={76=[2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74]}, mServiceData={}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-82, mTimestampNanos=112555102662}
11-18 13:31:08.893  5627  5627 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: ScanResult{mDevice=C8:16:A4:7E:61:23, mScanRecord=ScanRecord [mAdvertiseFlags=6, mServiceUuids=null, mManufacturerSpecificData={76=[2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74]}, mServiceData={}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-82, mTimestampNanos=112555102662}
11-18 13:31:08.894  5627  5627 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess : Current thread: Thread[main,5,main], id: 1
11-18 13:31:08.894  5627  5627 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNINGCurrent thread: Thread[main,5,main], id: 1
11-18 13:31:08.894  5627  5627 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
11-18 13:31:08.894  5627  5627 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  true. Current thread: Thread[main,5,main], id: 1
11-18 13:31:08.894  5627  5627 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[main,5,main], id: 1
11-18 13:31:08.894  5627  5627 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-18 13:31:08.894  5627  5627 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-18 13:31:08.894  5627  5627 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING, ADVERTISING]
11-18 13:31:08.894  5627  5627 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
11-18 13:31:08.894  5627  5627 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-18 13:31:08.894  5627  5627 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [SCANNING, ADVERTISING]Current thread: Thread[main,5,main], id: 1
11-18 13:31:08.894  5627  5627 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [SCANNING, ADVERTISING]
11-18 13:31:08.894  5627  5627 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
,11-18 13:31:08.897  5627  5627 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-18 13:31:08.897  5627  5627 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: true
11-18 13:31:08.897  5627  5627 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-18 13:31:08.897  5627  5627 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-18 13:31:08.897  5627  5627 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-18 13:31:08.897  5627  5627 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: true
,11-18 13:31:08.901  5725  5743 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,11-18 13:31:08.901  5725  5743 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-18 13:31:08.906  5725  5743 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,11-18 13:31:08.906  5725  5743 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-18 13:31:09.397  5627  5627 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: true
,11-18 13:31:09.397  5627  5627 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
11-18 13:31:09.398  5627  5627 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,11-18 13:31:11.895  5627  5674 I io.jxcore.node.StartStopOperationHandlerTest: Starting test: testConstructor
,11-18 13:31:11.895  5627  5674 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-18 13:31:11.895  5627  5674 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
,11-18 13:31:11.896  5627  5674 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
11-18 13:31:11.896  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
11-18 13:31:11.896  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,11-18 13:31:11.896  5627  5867 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
,11-18 13:31:11.896  5627  5674 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
11-18 13:31:11.896  5627  5867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
11-18 13:31:11.896  5627  5674 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
11-18 13:31:11.897  5627  5867 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
11-18 13:31:11.897  5627  5674 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,11-18 13:31:11.897  5627  5674 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5683e65 removed from the list
11-18 13:31:11.897  5627  5674 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-18 13:31:11.897  5627  5674 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,11-18 13:31:11.898  5627  5627 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
11-18 13:31:11.898  5627  5674 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,11-18 13:31:11.898  5627  5627 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,11-18 13:31:11.898  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,11-18 13:31:11.898  5627  5627 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-18 13:31:11.898  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
11-18 13:31:11.898  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-61,5,main], id: 61
11-18 13:31:11.898  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-18 13:31:11.899  5627  5674 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
11-18 13:31:11.899  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-61,5,main], id: 61
11-18 13:31:11.901  5627  5674 D BluetoothAdapter: STATE_ON
11-18 13:31:11.902  5725  5735 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
11-18 13:31:11.903  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-18 13:31:11.905  5627  5674 D BluetoothAdapter: STATE_ON
11-18 13:31:11.905  5725  5746 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-18 13:31:11.908  5725  5736 D BtGatt.GattService: stopScan() - queue size =1
11-18 13:31:11.911  5725  5735 D BtGatt.GattService: unregisterClient() - clientIf=5
11-18 13:31:11.911  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-18 13:31:11.912  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-18 13:31:11.912  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,11-18 13:31:11.912  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-61,5,main], id: 61
11-18 13:31:11.912  5725  5725 D BtGatt.ScanManager: awakened up at time 117118
11-18 13:31:11.912  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-61,5,main], id: 61
11-18 13:31:11.912  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-61,5,main], id: 61
11-18 13:31:11.912  5627  5674 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
11-18 13:31:11.912  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-61,5,main], id: 61
,11-18 13:31:11.914  5725  5745 D BtGatt.AdvertiseManager: message : 1
11-18 13:31:11.915  5725  5745 D BtGatt.AdvertiseManager: stop advertise for client 6
,11-18 13:31:11.926  5725  5743 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
,11-18 13:31:11.926  5725  5743 D BtGatt.GattService: Client app is not null!
11-18 13:31:11.927  5725  5767 D BtGatt.GattService: unregisterClient() - clientIf=6
11-18 13:31:11.928  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,11-18 13:31:11.928  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
11-18 13:31:11.928  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
11-18 13:31:11.929  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  false. Current thread: Thread[Thread-61,5,main], id: 61
11-18 13:31:11.929  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-61,5,main], id: 61
11-18 13:31:11.929  5627  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-61,5,main], id: 61
,11-18 13:31:11.929  5627  5674 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,11-18 13:31:11.929  5627  5674 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,11-18 13:31:11.930  5627  5674 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
11-18 13:31:11.931  5627  5674 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-18 13:31:11.933  5627  5674 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-18 13:31:11.933  5627  5674 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-18 13:31:11.933  5627  5674 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
,11-18 13:31:11.933  5627  5674 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-18 13:31:11.933  5627  5674 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@783873a removed from the list
11-18 13:31:11.933  5627  5627 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,11-18 13:31:11.933  5627  5674 D io.jxcore.node.ConnectivityMonitor: stop
11-18 13:31:11.933  5627  5627 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,11-18 13:31:11.934  5627  5627 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-18 13:31:11.934  5627  5627 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-18 13:31:11.934  5627  5627 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-18 13:31:11.934  5627  5627 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING, ADVERTISING]
,11-18 13:31:11.934  5627  5627 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-18 13:31:11.934  5627  5627 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING, ADVERTISING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
,11-18 13:31:11.934  5627  5627 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING, ADVERTISING] -> [NOT_STARTED]
11-18 13:31:11.934  5627  5627 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-18 13:31:11.935  5627  5674 I io.jxcore.node.StartStopOperationTest: Starting test: testIsTargetState
11-18 13:31:11.935  5627  5674 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
11-18 13:31:11.935  5627  5674 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
11-18 13:31:11.935  5627  5674 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
11-18 13:31:11.936  5627  5674 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,11-18 13:31:11.936  5627  5674 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
11-18 13:31:11.936  5627  5674 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
11-18 13:31:11.936  5627  5627 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-18 13:31:11.936  5627  5627 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-18 13:31:11.936  5627  5627 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-18 13:31:11.936  5627  5627 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-18 13:31:11.937  5627  5627 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-18 13:31:11.937  5627  5627 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
,11-18 13:31:11.937  5627  5627 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-18 13:31:11.937  5627  5627 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-18 13:31:11.937  5627  5674 I io.jxcore.node.StartStopOperationTest: Starting test: testCreateStartOperation
,11-18 13:31:11.937  5627  5627 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-18 13:31:11.937  5627  5627 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-18 13:31:11.937  5627  5627 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-18 13:31:11.938  5627  5674 I io.jxcore.node.StartStopOperationTest: Starting test: testGetShouldStartOrStopListeningToAdvertisementsOnly
11-18 13:31:11.940  5627  5674 I io.jxcore.node.StartStopOperationTest: Starting test: testIsStartOperation
11-18 13:31:11.943  5627  5674 I io.jxcore.node.StartStopOperationTest: Starting test: testToString
11-18 13:31:11.944  5627  5674 I io.jxcore.node.StartStopOperationTest: Starting test: testCreateStopOperation
11-18 13:31:11.946  5627  5674 I io.jxcore.node.StartStopOperationTest: Starting test: testSetOperationExecutedTime
11-18 13:31:11.948  5627  5674 I io.jxcore.node.StartStopOperationTest: Starting test: testGetOperationExecutedTime
11-18 13:31:11.949  5627  5674 I io.jxcore.node.StartStopOperationTest: Starting test: testGetCallback
,11-18 13:31:11.957  5725  5743 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=5
,11-18 13:31:11.957  5725  5743 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-18 13:31:11.957  5725  5743 D BtGatt.GattService: current time is 117164097918
11-18 13:31:11.958  5725  5743 D BtGatt.GattService: Batch record : [35, 97, 126, -92, 22, -56, 1, -128, -79, 51, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 116, -43, -111, -91, -20, -29, 1, -128, -80, 47, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 71, -122, -77, 84, 69, -12, 1, -128, -79, 44, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 81, 34, 97, 112, -14, -5, 1, -128, -81, 41, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, -46, -4, -117, 6, 105, -37, 1, -128, -93, 27, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
11-18 13:31:11.958  5725  5743 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
11-18 13:31:11.958  5725  5743 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,11-18 13:31:11.958  5725  5743 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
11-18 13:31:11.959  5725  5743 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
11-18 13:31:11.959  5725  5743 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
,11-18 13:31:11.965  5725  5743 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
,11-18 13:31:11.965  5725  5743 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-18 13:31:11.966  5725  5746 D BtGatt.ScanManager: stopping BLe Batch
,11-18 13:31:11.972  5725  5743 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,11-18 13:31:11.972  5725  5743 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-18 13:31:11.972  5725  5746 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-18 13:31:11.979  5725  5743 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-18 13:31:11.979  5725  5743 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-18 13:31:12.438  5627  5627 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-18 13:31:13.364   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-18 13:31:13.876   930  2983 D ConnectivityService: handlePromptUnvalidated 101
,11-18 13:31:13.954  5627  5674 I StreamCopyingThreadTest: Starting test: testCopyDataAndCloseConnection
,11-18 13:31:14.100  5627  5869 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 155, name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
11-18 13:31:14.100  5627  5869 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-18 13:31:14.365   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-18 13:31:14.930  5627  5869 W !!      : call onHalfStreamCopied
,11-18 13:31:14.930  5627  5869 I testCopyDataAndClose: closing input stream
,11-18 13:31:15.366   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-18 13:31:15.714  5627  5869 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 155, thread name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
11-18 13:31:15.714  5627  5869 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-18 13:31:15.714  5627  5869 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
11-18 13:31:15.714  5627  5869 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-18 13:31:15.714  5627  5869 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
11-18 13:31:15.714  5627  5869 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
11-18 13:31:15.714  5627  5869 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
,11-18 13:31:15.714  5627  5869 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
11-18 13:31:15.714  5627  5869 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
,11-18 13:31:15.715  5627  5869 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 155, name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
11-18 13:31:15.715  5627  5869 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 20971520 and the total number of bytes written 20971520
,11-18 13:31:15.767   930  2981 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 7, 9 -> obsolete
,11-18 13:31:16.367   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-18 13:31:16.947   930  2981 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 8, 9 -> obsolete
,11-18 13:31:17.368   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-18 13:31:18.369   535   535 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,11-18 13:31:19.819  5627  5674 I StreamCopyingThreadTest: Starting test: testRun
,11-18 13:31:19.823  5627  5870 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 158, name: My test thread name). Connection data: Peer properties: [null null].
11-18 13:31:19.823  5627  5870 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-18 13:31:23.372   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-18 13:31:24.373   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-18 13:31:24.830  5627  5871 E StreamCopyingThreadTest: StreamCopyingThread didn't close after 5s!
,11-18 13:31:24.832  5627  5674 I StreamCopyingThreadTest: Starting test: testCopyBigData
,11-18 13:31:24.989  5627  5872 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 161, name: testCopyBigData thread). Connection data: Peer properties: [null null].
11-18 13:31:24.989  5627  5872 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-18 13:31:25.375   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-18 13:31:26.376   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-18 13:31:26.623  5627  5872 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 161, thread name: testCopyBigData thread). Connection data: Peer properties: [null null].
11-18 13:31:26.623  5627  5872 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-18 13:31:26.624  5627  5872 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
11-18 13:31:26.624  5627  5872 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
11-18 13:31:26.624  5627  5872 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
11-18 13:31:26.624  5627  5872 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
11-18 13:31:26.624  5627  5872 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
11-18 13:31:26.624  5627  5872 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
11-18 13:31:26.624  5627  5872 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
11-18 13:31:26.624  5627  5872 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 161, name: testCopyBigData thread). Connection data: Peer properties: [null null].
11-18 13:31:26.624  5627  5872 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 20971520 and the total number of bytes written 20971520
,11-18 13:31:26.820   930  2983 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-18 13:31:27.377   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-18 13:31:28.378   535   535 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,11-18 13:31:30.334  3689  3883 I Keyboard.Facilitator.LanguageModelFlusher: run()
,11-18 13:31:30.334  3689  3883 I Keyboard.Facilitator: flushDynamicLanguageModels()
,11-18 13:31:30.364  3610  3610 I ConfigService: onCreate
,11-18 13:31:30.742  5627  5674 I StreamCopyingThreadTest: Starting test: testRunNotify
,11-18 13:31:30.744  5627  5874 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 163, name: My test thread name). Connection data: Peer properties: [null null].
11-18 13:31:30.744  5627  5874 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-18 13:31:30.745  5627  5874 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 163, thread name: My test thread name). Connection data: Peer properties: [null null].
11-18 13:31:30.745  5627  5874 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
11-18 13:31:30.745  5627  5874 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
11-18 13:31:30.745  5627  5874 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
11-18 13:31:30.745  5627  5874 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
,11-18 13:31:30.745  5627  5874 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
11-18 13:31:30.745  5627  5874 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
,11-18 13:31:30.746  5627  5874 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
11-18 13:31:30.746  5627  5874 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
,11-18 13:31:30.746  5627  5874 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 163, name: My test thread name). Connection data: Peer properties: [null null].
11-18 13:31:30.746  5627  5874 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 22
11-18 13:31:30.747  5627  5674 I StreamCopyingThreadTest: Starting test: testSetBufferSize
,11-18 13:31:30.748  5627  5674 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
11-18 13:31:30.748  5627  5674 I StreamCopyingThreadTest: Starting test: testRunWithException
11-18 13:31:30.751  5627  5875 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 167, name: My test thread name). Connection data: Peer properties: [null null].
11-18 13:31:30.751  5627  5875 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-18 13:31:30.752  5627  5875 E io.jxcore.node.StreamCopyingThread: Failed to write to the output stream (thread ID: 167, thread name: My test thread name): Test exception.
11-18 13:31:30.752  5627  5875 D io.jxcore.node.StreamCopyingThread: onStreamCopyError (ID: 167, name: My test thread name). Connection data: Peer properties: [null null].
11-18 13:31:30.752  5627  5875 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
11-18 13:31:30.752  5627  5875 D io.jxcore.node.StreamCopyingThread: number of bytes read = 22
11-18 13:31:30.753  5627  5875 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 167, name: My test thread name). Connection data: Peer properties: [null null].
11-18 13:31:30.753  5627  5875 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
,11-18 13:31:30.754  5627  5674 E com.test.thalitest.ThaliTestRunner: testConnect(io.jxcore.node.ConnectionHelperTest)
11-18 13:31:30.754  5627  5674 E com.test.thalitest.ThaliTestRunner: 
11-18 13:31:30.754  5627  5674 E com.test.thalitest.ThaliTestRunner: Expected: is "We already have an outgoing connection to peer with ID 00:11:22:33:44:55"
11-18 13:31:30.754  5627  5674 E com.test.thalitest.ThaliTestRunner:      but: was "Already connect(ing/ed)"
11-18 13:31:30.755  5627  5674 E com.test.thalitest.ThaliTestRunner: java.lang.AssertionError: 
11-18 13:31:30.755  5627  5674 E com.test.thalitest.ThaliTestRunner: Expected: is "We already have an outgoing connection to peer with ID 00:11:22:33:44:55"
11-18 13:31:30.755  5627  5674 E com.test.thalitest.ThaliTestRunner:      but: was "Already connect(ing/ed)"
11-18 13:31:30.755  5627  5674 E com.test.thalitest.ThaliTestRunner: 	at org.hamcrest.MatcherAssert.assertThat(MatcherAssert.java:20)
11-18 13:31:30.755  5627  5674 E com.test.thalitest.ThaliTestRunner: 	at org.hamcrest.MatcherAssert.assertThat(MatcherAssert.java:8)
11-18 13:31:30.755  5627  5674 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.ConnectionHelperTest.testConnect(ConnectionHelperTest.java:551)
11-18 13:31:30.755  5627  5674 E com.test.thalitest.ThaliTestRunner: 	at java.lang.reflect.Method.invoke(Native Method)
11-18 13:31:30.755  5627  5674 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.model.FrameworkMethod$1.runReflectiveCall(FrameworkMethod.java:50)
11-18 13:31:30.755  5627  5674 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.model.ReflectiveCallable.run(ReflectiveCallable.java:12)
11-18 13:31:30.755  5627  5674 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.model.FrameworkMethod.invokeExplosively(FrameworkMethod.java:47)
11-18 13:31:30.755  5627  5674 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.InvokeMethod.evaluate(InvokeMethod.java:17)
11-18 13:31:30.755  5627  5674 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.RunBefores.evaluate(RunBefores.java:26)
11-18 13:31:30.755  5627  5674 E com.test.thalitest.ThaliTestRunner: 	at org.junit.rules.ExpectedException$ExpectedExceptionStatement.evaluate(ExpectedException.java:239)
11-18 13:31:30.755  5627  5674 E com.test.thalitest.ThaliTestRunner: 	at org.junit.rules.TestWatcher$1.evaluate(TestWatcher.java:55)
11-18 13:31:30.755  5627  5674 E com.test.thalitest.ThaliTestRunner: 	at org.junit.rules.RunRules.evaluate(RunRules.java:20)
11-18 13:31:30.755  5627  5674 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runLeaf(ParentRunner.java:325)
11-18 13:31:30.755  5627  5674 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.BlockJUnit4ClassRunner.runChild(BlockJUnit4ClassRunner.java:78)
11-18 13:31:30.755  5627  5674 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.BlockJUnit4ClassRunner.runChild(BlockJUnit4ClassRunner.java:57)
11-18 13:31:30.755  5627  5674 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$3.run(ParentRunner.java:290)
11-18 13:31:30.755  5627  5674 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$1.schedule(ParentRunner.java:71)
11-18 13:31:30.755  5627  5674 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runChildren(ParentRunner.java:288)
11-18 13:31:30.755  5627  5674 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.access$000(ParentRunner.java:58)
11-18 13:31:30.755  5627  5674 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$2.evaluate(ParentRunner.java:268)
11-18 13:31:30.755  5627  5674 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.RunBefores.evaluate(RunBefores.java:26)
11-18 13:31:30.755  5627  5674 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.RunAfters.evaluate(RunAfters.java:27)
11-18 13:31:30.755  5627  5674 E com.test.thalitest.ThaliTestRunner: 	at org.,junit.runners.ParentRunner.run(ParentRunner.java:363)
11-18 13:31:30.755  5627  5674 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:128)
11-18 13:31:30.755  5627  5674 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:27)
11-18 13:31:30.755  5627  5674 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$3.run(ParentRunner.java:290)
11-18 13:31:30.755  5627  5674 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$1.schedule(ParentRunner.java:71)
11-18 13:31:30.755  5627  5674 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runChildren(ParentRunner.java:288)
11-18 13:31:30.755  5627  5674 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.access$000(ParentRunner.java:58)
11-18 13:31:30.755  5627  5674 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$2.evaluate(ParentRunner.java:268)
11-18 13:31:30.755  5627  5674 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.run(ParentRunner.java:363)
11-18 13:31:30.755  5627  5674 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:128)
11-18 13:31:30.755  5627  5674 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:27)
11-18 13:31:30.755  5627  5674 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$3.run(ParentRunner.java:290)
11-18 13:31:30.755  5627  5674 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$1.schedule(ParentRunner.java:71)
11-18 13:31:30.755  5627  5674 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runChildren(ParentRunner.java:288)
11-18 13:31:30.755  5627  5674 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.access$000(ParentRunner.java:58)
11-18 13:31:30.755  5627  5674 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$2.evaluate(ParentRunner.java:268)
11-18 13:31:30.755  5627  5674 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.run(ParentRunner.java:363)
11-18 13:31:30.755  5627  5674 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.run(JUnitCore.java:137)
11-18 13:31:30.755  5627  5674 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.run(JUnitCore.java:115)
11-18 13:31:30.755  5627  5674 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.run(JUnitCore.java:105)
11-18 13:31:30.755  5627  5674 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.runClasses(JUnitCore.java:62)
11-18 13:31:30.755  5627  5674 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.runClasses(JUnitCore.java:49)
11-18 13:31:30.755  5627  5674 E com.test.thalitest.ThaliTestRunner: 	at com.test.thalitest.ThaliTestRunner.runTests(ThaliTestRunner.java:86)
11-18 13:31:30.755  5627  5674 E com.test.thalitest.ThaliTestRunner: 	at com.test.thalitest.RegisterExecuteUT$2.Receiver(RegisterExecuteUT.java:75)
11-18 13:31:30.755  5627  5674 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.jxcore.javaCall(jxcore.java:139)
11-18 13:31:30.755  5627  5674 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.jxcore.evalEngine(Native Method)
11-18 13:31:30.755  5627  5674 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.jxcore$4.run(jxcore.java:226)
11-18 13:31:30.755  5627  5674 E com.test.thalitest.ThaliTestRunner: 	at android.os.Handler.handleCallback(Handler.java:739)
11-18 13:31:30.755  5627  5674 E com.test.thalitest.ThaliTestRunner: 	at android.os.Handler.dispatchMessage(Handler.java:95)
11-18 13:31:30.755  5627  5674 E com.test.thalitest.ThaliTestRunner: 	at android.os.Looper.loop(Looper.java:148)
11-18 13:31:30.755  5627  5674 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.CoreThread.run(CoreRunnable.java:56)
11-18 13:31:30.755  5627  5674 E com.test.thalitest.ThaliTestRunner: testStartStop(io.jxcore.node.ConnectivityMonitorTest)
1,1-18 13:31:30.755  5627  5674 E com.test.thalitest.ThaliTestRunner: The BT listener was bound
11-18 13:31:30.755  5627  5674 E com.test.thalitest.ThaliTestRunner: Expected: is <true>
11-18 13:31:30.755  5627  5674 E com.test.thalitest.ThaliTestRunner:      but: was <false>
11-18 13:31:30.756  5627  5674 E com.test.thalitest.ThaliTestRunner: java.lang.AssertionError: The BT listener was bound
11-18 13:31:30.756  5627  5674 E com.test.thalitest.ThaliTestRunner: Expected: is <true>
11-18 13:31:30.756  5627  5674 E com.test.thalitest.ThaliTestRunner:      but: was <false>,
11-18 13:31:30.756  5627  5674 E com.test.thalitest.ThaliTestRunner: ,	at org.hamcrest.MatcherAssert.assertThat(MatcherAssert.java:20)
11-18 13:31:30.756  5627  5674 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.ConnectivityMonitorTest.testStartStop(ConnectivityMonitorTest.java:216)
11-18 13:31:30.756  5627  5674 E com.test.thalitest.ThaliTestRunner: 	at java.lang.reflect.Method.invoke(Native Method)
11-18 13:31:30.756  5627  5674 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.model.FrameworkMethod$1.runReflectiveCall(FrameworkMethod.java:50)
11-18 13:31:30.756  5627  5674 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.model.ReflectiveCallable.run(ReflectiveCallable.java:12)
11-18 13:31:30.756  5627  5674 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.model.FrameworkMethod.invokeExplosively(FrameworkMethod.java:47)
11-18 13:31:30.756  5627  5674 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.InvokeMethod.evaluate(InvokeMethod.java:17)
11-18 13:31:30.756  5627  5674 E com.test.thalitest.ThaliTestRunner: 	at org.junit.rules.ExpectedException$ExpectedExceptionStatement.evaluate(ExpectedException.java:239)
11-18 13:31:30.756  5627  5674 E com.test.thalitest.ThaliTestRunner: 	at org.junit.rules.TestWatcher$1.evaluate(TestWatcher.java:55)
11-18 13:31:30.756  5627  5674 E com.test.thalitest.ThaliTestRunner: 	at org.junit.rules.RunRules.evaluate(RunRules.java:20)
11-18 13:31:30.756  5627  5674 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runLeaf(ParentRunner.java:325)
11-18 13:31:30.756  5627  5674 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.BlockJUnit4ClassRunner.runChild(BlockJUnit4ClassRunner.java:78)
11-18 13:31:30.756  5627  5674 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.BlockJUnit4ClassRunner.runChild(BlockJUnit4ClassRunner.java:57)
11-18 13:31:30.756  5627  5674 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$3.run(ParentRunner.java:290)
11-18 13:31:30.756  5627  5674 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$1.schedule(ParentRunner.java:71)
11-18 13:31:30.756  5627  5674 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runChildren(ParentRunner.java:288)
11-18 13:31:30.756  5627  5674 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.access$000(ParentRunner.java:58)
11-18 13:31:30.756  5627  5674 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$2.evaluate(ParentRunner.java:268)
11-18 13:31:30.756  5627  5674 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.RunBefores.evaluate(RunBefores.java:26)
11-18 13:31:30.756  5627  5674 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.RunAfters.evaluate(RunAfters.java:27)
11-18 13:31:30.756  5627  5674 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.run(ParentRunner.java:363)
11-18 13:31:30.756  5627  5674 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:128)
11-18 13:31:30.756  5627  5674 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:27)
11-18 13:31:30.756  5627  5674 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$3.run(ParentRunner.java:290)
11-18 13:31:30.756  5627  5674 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$1.schedule(ParentRunner.java:71)
11-18 13:31:30.756  5627  5674 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runChildren(ParentRunner.java:288)
11-18 13:31:30.756  5627  5674 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.access$000(ParentRunner.java:58)
11-18 13:31:30.756  5627  5674 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$2.evaluate(ParentRunner.java:268)
11-18 13:31:30.756  5627  5674 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.run(ParentRunner.java:363)
11-18 13:31:30.756  5627  5674 E com.test.thalite,st.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:128)
11-18 13:31:30.756  5627  5674 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:27)
11-18 13:31:30.756  5627  5674 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$3.run(ParentRunner.java:290)
11-18 13:31:30.756  5627  5674 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$1.schedule(ParentRunner.java:71)
11-18 13:31:30.756  5627  5674 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runChildren(ParentRunner.java:288)
11-18 13:31:30.756  5627  5674 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.access$000(ParentRunner.java:58)
11-18 13:31:30.756  5627  5674 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$2.evaluate(ParentRunner.java:268)
11-18 13:31:30.756  5627  5674 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.run(ParentRunner.java:363)
11-18 13:31:30.756  5627  5674 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.run(JUnitCore.java:137)
11-18 13:31:30.756  5627  5674 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.run(JUnitCore.java:115)
11-18 13:31:30.756  5627  5674 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.run(JUnitCore.java:105)
11-18 13:31:30.756  5627  5674 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.runClasses(JUnitCore.java:62)
11-18 13:31:30.756  5627  5674 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.runClasses(JUnitCore.java:49)
11-18 13:31:30.756  5627  5674 E com.test.thalitest.ThaliTestRunner: 	at com.test.thalitest.ThaliTestRunner.runTests(ThaliTestRunner.java:86)
11-18 13:31:30.756  5627  5674 E com.test.thalitest.ThaliTestRunner: 	at com.test.thalitest.RegisterExecuteUT$2.Receiver(RegisterExecuteUT.java:75)
11-18 13:31:30.756  5627  5674 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.jxcore.javaCall(jxcore.java:139)
11-18 13:31:30.756  5627  5674 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.jxcore.evalEngine(Native Method)
11-18 13:31:30.756  5627  5674 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.jxcore$4.run(jxcore.java:226)
11-18 13:31:30.756  5627  5674 E com.test.thalitest.ThaliTestRunner: 	at android.os.Handler.handleCallback(Handler.java:739)
11-18 13:31:30.756  5627  5674 E com.test.thalitest.ThaliTestRunner: 	at android.os.Handler.dispatchMessage(Handler.java:95)
11-18 13:31:30.756  5627  5674 E com.test.thalitest.ThaliTestRunner: 	at android.os.Looper.loop(Looper.java:148)
11-18 13:31:30.756  5627  5674 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.CoreThread.run(CoreRunnable.java:56)
11-18 13:31:30.756  5627  5674 E com.test.thalitest.ThaliTestRunner: testRun(io.jxcore.node.StreamCopyingThreadTest)
11-18 13:31:30.756  5627  5674 E com.test.thalitest.ThaliTestRunner: StreamCopyingThread should be closed
11-18 13:31:30.756  5627  5674 E com.test.thalitest.ThaliTestRunner: Expected: is <true>
11-18 13:31:30.756  5627  5674 E com.test.thalitest.ThaliTestRunner:      but: was <false>
11-18 13:31:30.757  5627  5674 E com.test.thalitest.ThaliTestRunner: java.lang.AssertionError: StreamCopyingThread should be closed
11-18 13:31:30.757  5627  5674 E com.test.thalitest.ThaliTestRunner: Expected: is <true>
11-18 13:31:30.757  5627  5674 E com.test.thalitest.ThaliTestRunner:      but: was <false>
11-18 13:31:30.757  5627  5674 E com.test.thalitest.ThaliTestRunner: 	at org.hamcrest.MatcherAssert.assertThat(MatcherAssert.java:20)
11-18 13:31:30.757  5627  5674 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.StreamCopyingThreadTest.testRun(StreamCopyingThreadTest.java:152)
11-18 13:31:30.757  5627  5674 E com.test.thalitest.ThaliTestRunner: 	at java.lang.reflect.Method.invoke(Native Method)
11-18 13:31:30.757  5627  5674 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.model.FrameworkMethod$1.runReflectiveCall(FrameworkMethod.java:50)
11-,18 13:31:30.757  5627  5674 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.model.ReflectiveCallable.run(ReflectiveCallable.java:12)
11-18 13:31:30.757  5627  5674 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.model.FrameworkMethod.invokeExplosively(FrameworkMethod.java:47)
11-18 13:31:30.757  5627  5674 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.InvokeMethod.evaluate(InvokeMethod.java:17)
11-18 13:31:30.757  5627  5674 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.RunBefores.evaluate(RunBefores.java:26)
11-18 13:31:30.757  5627  5674 E com.test.thalitest.ThaliTestRunner: 	at org.junit.rules.ExpectedException$ExpectedExceptionStatement.evaluate(ExpectedException.java:239)
11-18 13:31:30.757  5627  5674 E com.test.thalitest.ThaliTestRunner: 	at org.junit.rules.TestWatcher$1.evaluate(TestWatcher.java:55)
11-18 13:31:30.757  5627  5674 E com.test.thalitest.ThaliTestRunner: 	at org.junit.rules.RunRules.evaluate(RunRules.java:20)
11-18 13:31:30.757  5627  5674 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runLeaf(ParentRunner.java:325)
11-18 13:31:30.757  5627  5674 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.BlockJUnit4ClassRunner.runChild(BlockJUnit4ClassRunner.java:78)
11-18 13:31:30.757  5627  5674 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.BlockJUnit4ClassRunner.runChild(BlockJUnit4ClassRunner.java:57)
11-18 13:31:30.757  5627  5674 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$3.run(ParentRunner.java:290)
11-18 13:31:30.757  5627  5674 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$1.schedule(ParentRunner.java:71)
11-18 13:31:30.757  5627  5674 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runChildren(ParentRunner.java:288)
11-18 13:31:30.757  5627  5674 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.access$000(ParentRunner.java:58)
11-18 13:31:30.757  5627  5674 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$2.evaluate(ParentRunner.java:268)
11-18 13:31:30.757  5627  5674 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.run(ParentRunner.java:363)
11-18 13:31:30.757  5627  5674 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:128)
11-18 13:31:30.757  5627  5674 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:27)
11-18 13:31:30.757  5627  5674 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$3.run(ParentRunner.java:290)
11-18 13:31:30.757  5627  5674 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$1.schedule(ParentRunner.java:71)
11-18 13:31:30.757  5627  5674 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runChildren(ParentRunner.java:288)
11-18 13:31:30.757  5627  5674 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.access$000(ParentRunner.java:58)
11-18 13:31:30.757  5627  5674 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$2.evaluate(ParentRunner.java:268)
11-18 13:31:30.757  5627  5674 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.run(ParentRunner.java:363)
11-18 13:31:30.757  5627  5674 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:128)
11-18 13:31:30.757  5627  5674 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:27)
11-18 13:31:30.757  5627  5674 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$3.run(ParentRunner.java:290)
11-18 13:31:30.757  5627  5674 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$1.schedule(ParentRunner.java:71)
11-18 13:31:30.757  5627  5674 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runChildren(ParentRunner.java:288)
11-18 13:31:30.757  5627  5674 E com.test.thalitest.,ThaliTestRunner: 	at org.junit.runners.ParentRunner.access$000(ParentRunner.java:58)
11-18 13:31:30.757  5627  5674 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$2.evaluate(ParentRunner.java:268)
11-18 13:31:30.757  5627  5674 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.run(ParentRunner.java:363)
11-18 13:31:30.757  5627  5674 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.run(JUnitCore.java:137)
11-18 13:31:30.757  5627  5674 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.run(JUnitCore.java:115)
11-18 13:31:30.757  5627  5674 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.run(JUnitCore.java:105)
11-18 13:31:30.757  5627  5674 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.runClasses(JUnitCore.java:62)
11-18 13:31:30.757  5627  5674 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.runClasses(JUnitCore.java:49)
11-18 13:31:30.757  5627  5674 E com.test.thalitest.ThaliTestRunner: 	at com.test.thalitest.ThaliTestRunner.runTests(ThaliTestRunner.java:86)
11-18 13:31:30.757  5627  5674 E com.test.thalitest.ThaliTestRunner: 	at com.test.thalitest.RegisterExecuteUT$2.Receiver(RegisterExecuteUT.java:75)
11-18 13:31:30.757  5627  5674 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.jxcore.javaCall(jxcore.java:139)
11-18 13:31:30.757  5627  5674 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.jxcore.evalEngine(Native Method)
11-18 13:31:30.757  5627  5674 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.jxcore$4.run(jxcore.java:226)
11-18 13:31:30.757  5627  5674 E com.test.thalitest.ThaliTestRunner: 	at android.os.Handler.handleCallback(Handler.java:739)
11-18 13:31:30.757  5627  5674 E com.test.thalitest.ThaliTestRunner: 	at android.os.Handler.dispatchMessage(Handler.java:95)
11-18 13:31:30.757  5627  5674 E com.test.thalitest.ThaliTestRunner: 	at android.os.Looper.loop(Looper.java:148)
11-18 13:31:30.757  5627  5674 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.CoreThread.run(CoreRunnable.java:56)
11-18 13:31:30.760  5627  5674 I jxcore-log: 2016-11-18 12:31:30 - DEBUG UnitTest_app: 'Running unit tests'
11-18 13:31:30.760  5627  5674 I jxcore-log: 
11-18 13:31:30.760  5627  5674 I jxcore-log: *Native tests were executed*
11-18 13:31:30.760  5627  5674 I jxcore-log: 
11-18 13:31:30.760  5627  5674 I jxcore-log: Total number of executed tests:  82
11-18 13:31:30.760  5627  5674 I jxcore-log: 
11-18 13:31:30.760  5627  5674 I jxcore-log: Number of passed tests:  79
11-18 13:31:30.760  5627  5674 I jxcore-log: 
11-18 13:31:30.760  5627  5674 I jxcore-log: Number of failed tests:  3
11-18 13:31:30.760  5627  5674 I jxcore-log: 
11-18 13:31:30.760  5627  5674 I jxcore-log: Number of ignored tests:  0
11-18 13:31:30.760  5627  5674 I jxcore-log: 
11-18 13:31:30.760  5627  5674 I jxcore-log: Total duration:  39154
11-18 13:31:30.760  5627  5674 I jxcore-log: 
11-18 13:31:30.760  5627  5674 I jxcore-log: Failed to execute UT.
11-18 13:31:30.760  5627  5674 I jxcore-log: 
11-18 13:31:30.761  5627  5674 I jxcore-log: 2016-11-18 12:31:30 - DEBUG UnitTest_app: 'Failed to execute UT.'
11-18 13:31:30.761  5627  5674 I jxcore-log: 
11-18 13:31:30.762  5627  5674 I jxcore-log: 2016-11-18 12:31:30 - DEBUG UnitTest_app: 'Unit Test app is loaded'
11-18 13:31:30.762  5627  5674 I jxcore-log: 
11-18 13:31:30.766  5627  5674 I jxcore-log: 2016-11-18 12:31:30 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
11-18 13:31:30.766  5627  5674 I jxcore-log: 
11-18 13:31:30.766  5627  5674 I jxcore-log: 2016-11-18 12:31:30 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-18 13:31:30.766  5627  5674 I jxcore-log: 
11-18 13:31:30.768  5627  5674 I jxcore-log: 2016-11-18 12:31:30 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
11-18 13:31:30.768  5627  5674 I jxcore-log: 
11-18 13:31:30.769  5627  5674 I jxcore-log: 2016-11-18 12:31:30 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-18 13:31:30.769  5627  5674 I jxcore-log: 
11-18 13:31:30.769  5627  5674 I jxcore-log: 2016-11-18 12:31:30 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
11-18 13:31:30.769  5627  5674 I jxcore-log: 
11-18 13:31:30.769  5627  5674 I jxcore-log: 2016-11-18 12:31:30 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH"})'
11-18 13:31:30.769  5627  5674 I jxcore-log: 
11-18 13:31:30.770  5627  5674 I jxcore-log: 2016-11-18 12:31:30 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-18 13:31:30.770  5627  5674 I jxcore-log: 
11-18 13:31:30.770  5627  5674 I jxcore-log: 2016-11-18 12:31:30 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
11-18 13:31:30.770  5627  5674 I jxcore-log: 
11-18 13:31:30.770  5627  5674 I jxcore-log: 2016-11-18 12:31:30 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH"})'
11-18 13:31:30.770  5627  5674 I jxcore-log: 
11-18 13:31:30.770  5627  5674 I jxcore-log: 2016-11-18 12:31:30 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-18 13:31:30.770  5627  5674 I jxcore-log: 
11-18 13:31:30.771  5627  5674 I jxcore-log: 2016-11-18 12:31:30 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
11-18 13:31:30.771  5627  5674 I jxcore-log: 
11-18 13:31:30.771  5627  5674 I jxcore-log: 2016-11-18 12:31:30 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH"})'
11-18 13:31:30.771  5627  5674 I jxcore-log: 
11-18 13:31:30.771  5627  5674 I jxcore-log: 2016-11-18 12:31:30 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-18 13:31:30.771  5627  5674 I jxcore-log: 
11-18 13:31:30.771  5627  5674 I jxcore-log: 2016-11-18 12:31:30 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-18 13:31:30.771  5627  5674 I jxcore-log: 
11-18 13:31:30.772  5627  5674 I jxcore-log: 2016-11-18 12:31:30 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-18 13:31:30.772  5627  5674 I jxcore-log: 
11-18 13:31:30.772  5627  5674 I jxcore-log: 2016-11-18 12:31:30 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
11-18 13:31:30.772  5627  5674 I jxcore-log: 
11-18 13:31:30.772  5627  5674 I jxcore-log: 2016-11-18 12:31:30 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-18 13:31:30.772  5627  5674 I jxcore-log: 
11-18 13:31:30.772  5627  5674 I jxcore-log: 2016-11-18 12:31:30 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-18 13:31:30.772  5627  5674 I jxcore-log: 
11-18 13:31:30.772  5627  5674 I jxcore-log: 2016-11-18 12:31:30 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-18 13:31:30.772  5627  5674 I jxcore-log: 
11-18 13:31:30.773  5627  5674 I jxcore-log: 2016-11-18 12:31:30 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
11-18 13:31:30.773  5627  5674 I jxcore-log: 
11-18 13:31:30.773  5627  5674 I jxcore-log: 2016-11-18 12:31:30 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-18 13:31:30.773  5627  5674 I jxcore-log: 
11-18 13:31:30.773  5627  5674 I jxcore-log: 2016-11-18 12:31:30 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
11-18 13:31:30.773  5627  5674 I jxcore-log: 
11-18 13:31:30.773  5627  5674 I jxcore-log: 2016-11-18 12:31:30 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-18 13:31:30.773  5627  5674 I jxcore-log: 
11-18 13:31:30.774  5627  5674 I jxcore-log: 2016-11-18 12:31:30 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
11-18 13:31:30.774  5627  5674 I jxcore-log: 
11-18 13:31:30.774  5627  5674 I jxcore-log: 2016-11-18 12:31:30 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-18 13:31:30.774  5627  5674 I jxcore-log: 
11-18 13:31:30.774  5627  5674 I jxcore-log: 2016-11-18 12:31:30 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
11-18 13:31:30.774  5627  5674 I jxcore-log: 
11-18 13:31:30.774  5627  5674 I jxcore-log: 2016-11-18 12:31:30 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-18 13:31:30.774  5627  5674 I jxcore-log: 
11-18 13:31:30.776  5627  5674 I jxcore-log: 2016-11-18 12:31:30 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
11-18 13:31:30.776  5627  5674 I jxcore-log: 
11-18 13:31:30.776  5627  5674 I jxcore-log: 2016-11-18 12:31:30 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH"})'
11-18 13:31:30.776  5627  5674 I jxcore-log: 
11-18 13:31:30.776  5627  5674 I jxcore-log: 2016-11-18 12:31:30 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-18 13:31:30.776  5627  5674 I jxcore-log: 
11-18 13:31:30.776  5627  5674 I jxcore-log: 2016-11-18 12:31:30 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
11-18 13:31:30.776  5627  5674 I jxcore-log: 
11-18 13:31:30.777  5627  5674 I jxcore-log: 2016-11-18 12:31:30 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH"})'
11-18 13:31:30.777  5627  5674 I jxcore-log: 
11-18 13:31:30.777  5627  5674 I jxcore-log: 2016-11-18 12:31:30 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-18 13:31:30.777  5627  5674 I jxcore-log: 
11-18 13:31:30.777  5627  5674 I jxcore-log: 2016-11-18 12:31:30 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
11-18 13:31:30.777  5627  5674 I jxcore-log: 
11-18 13:31:30.777  5627  5674 I jxcore-log: 2016-11-18 12:31:30 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH"})'
11-18 13:31:30.777  5627  5674 I jxcore-log: 
11-18 13:31:30.777  5627  5674 I jxcore-log: 2016-11-18 12:31:30 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-18 13:31:30.777  5627  5674 I jxcore-log: 
11-18 13:31:30.778  5627  5674 I jxcore-log: 2016-11-18 12:31:30 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-18 13:31:30.778  5627  5674 I jxcore-log: 
11-18 13:31:30.778  5627  5674 I jxcore-log: 2016-11-18 12:31:30 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-18 13:31:30.778  5627  5674 I jxcore-log: 
11-18 13:31:30.782  5627  5674 I jxcore-log: 2016-11-18 12:31:30 - DEBUG UnitTest_app: 'My device name is: Huawei-Nexus 6P'
11-18 13:31:30.782  5627  5674 I jxcore-log: 
11-18 13:31:30.783  5627  5674 I jxcore-log: 2016-11-18 12:31:30 - WARN testUtils: 'myNameCallback not set!'
11-18 13:31:30.783  5627  5674 I jxcore-log: 
11-18 13:31:30.786  5627  5627 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
,11-18 13:31:32.873   930  2983 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-18 13:31:32.911  5627  5674 I jxcore-log: 2016-11-18 12:31:32 - INFO runTests: 'Starting tests. Network type: WIFI. Platform: android'
11-18 13:31:32.911  5627  5674 I jxcore-log: 
,11-18 13:31:32.912  5627  5674 I jxcore-log: 2016-11-18 12:31:32 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js'
11-18 13:31:32.912  5627  5674 I jxcore-log: 
,11-18 13:31:33.262  5627  5674 I jxcore-log: 2016-11-18 12:31:33 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js'
11-18 13:31:33.262  5627  5674 I jxcore-log: 
,11-18 13:31:33.277  5627  5674 I jxcore-log: 2016-11-18 12:31:33 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManager.js'
11-18 13:31:33.277  5627  5674 I jxcore-log: 
,11-18 13:31:34.418  5627  5674 I jxcore-log: 2016-11-18 12:31:34 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js'
11-18 13:31:34.418  5627  5674 I jxcore-log: 
,11-18 13:31:34.587  5627  5674 I jxcore-log: 2016-11-18 12:31:34 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js'
11-18 13:31:34.587  5627  5674 I jxcore-log: 
,11-18 13:31:34.593  5627  5674 I jxcore-log: 2016-11-18 12:31:34 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testNativeMethod.js'
11-18 13:31:34.593  5627  5674 I jxcore-log: 
,11-18 13:31:34.605  5627  5674 I jxcore-log: 2016-11-18 12:31:34 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPouchDBCheckpointPlugin.js'
11-18 13:31:34.605  5627  5674 I jxcore-log: 
,11-18 13:31:35.105  5627  5674 I jxcore-log: 2016-11-18 12:31:35 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPouchDBGenerator.js'
11-18 13:31:35.105  5627  5674 I jxcore-log: 
,11-18 13:31:35.152  5627  5674 I jxcore-log: 2016-11-18 12:31:35 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js'
11-18 13:31:35.152  5627  5674 I jxcore-log: 
,11-18 13:31:35.165  5627  5674 I jxcore-log: 2016-11-18 12:31:35 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js'
11-18 13:31:35.165  5627  5674 I jxcore-log: 
,11-18 13:31:35.170  5627  5674 I jxcore-log: 2016-11-18 12:31:35 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliManager.js'
11-18 13:31:35.170  5627  5674 I jxcore-log: 
,11-18 13:31:35.399  3610  3610 I ConfigService: onDestroy
,11-18 13:31:35.453  5627  5674 I jxcore-log: 2016-11-18 12:31:35 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliManagerCoordinated.js'
11-18 13:31:35.453  5627  5674 I jxcore-log: 
,11-18 13:31:35.581  5627  5674 I jxcore-log: 2016-11-18 12:31:35 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js'
11-18 13:31:35.581  5627  5674 I jxcore-log: 
,11-18 13:31:35.967  5627  5674 I jxcore-log: 2016-11-18 12:31:35 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js'
11-18 13:31:35.967  5627  5674 I jxcore-log: 
,11-18 13:31:35.974  5627  5674 I jxcore-log: 2016-11-18 12:31:35 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeAndroid.js'
11-18 13:31:35.974  5627  5674 I jxcore-log: 
,11-18 13:31:35.978  5627  5674 I jxcore-log: 2016-11-18 12:31:35 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeDiscoveryCoordinated.js'
11-18 13:31:35.978  5627  5674 I jxcore-log: 
,11-18 13:31:35.982  5627  5674 I jxcore-log: 2016-11-18 12:31:35 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js'
11-18 13:31:35.982  5627  5674 I jxcore-log: 
,11-18 13:31:35.988  5627  5674 I jxcore-log: 2016-11-18 12:31:35 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeiOS.js'
11-18 13:31:35.988  5627  5674 I jxcore-log: 
,11-18 13:31:36.027  5627  5674 I jxcore-log: 2016-11-18 12:31:36 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js'
11-18 13:31:36.027  5627  5674 I jxcore-log: 
,11-18 13:31:36.033  5627  5674 I jxcore-log: 2016-11-18 12:31:36 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js'
11-18 13:31:36.033  5627  5674 I jxcore-log: 
,11-18 13:31:36.062  5627  5674 I jxcore-log: 2016-11-18 12:31:36 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js'
11-18 13:31:36.062  5627  5674 I jxcore-log: 
,11-18 13:31:36.101  5627  5674 I jxcore-log: 2016-11-18 12:31:36 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js'
11-18 13:31:36.101  5627  5674 I jxcore-log: 
,11-18 13:31:36.109  5627  5674 I jxcore-log: 2016-11-18 12:31:36 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationLocal.js'
11-18 13:31:36.109  5627  5674 I jxcore-log: 
,11-18 13:31:36.115  5627  5674 I jxcore-log: 2016-11-18 12:31:36 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js'
11-18 13:31:36.115  5627  5674 I jxcore-log: 
,11-18 13:31:36.132  5627  5674 I jxcore-log: 2016-11-18 12:31:36 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js'
11-18 13:31:36.132  5627  5674 I jxcore-log: 
,11-18 13:31:36.147  5627  5674 I jxcore-log: 2016-11-18 12:31:36 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js'
11-18 13:31:36.147  5627  5674 I jxcore-log: 
,11-18 13:31:36.153  5627  5674 I jxcore-log: 2016-11-18 12:31:36 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolDefault.js'
11-18 13:31:36.153  5627  5674 I jxcore-log: 
,11-18 13:31:36.158  5627  5674 I jxcore-log: 2016-11-18 12:31:36 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js'
11-18 13:31:36.158  5627  5674 I jxcore-log: 
,11-18 13:31:36.172  5627  5674 I jxcore-log: 2016-11-18 12:31:36 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolOneAtATime.js'
11-18 13:31:36.172  5627  5674 I jxcore-log: 
,11-18 13:31:36.190  5627  5674 I jxcore-log: 2016-11-18 12:31:36 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js'
11-18 13:31:36.190  5627  5674 I jxcore-log: 
,11-18 13:31:36.205  5627  5674 I jxcore-log: 2016-11-18 12:31:36 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js'
11-18 13:31:36.205  5627  5674 I jxcore-log: 
,11-18 13:31:36.216  5627  5674 I jxcore-log: 2016-11-18 12:31:36 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerAction.js'
11-18 13:31:36.216  5627  5674 I jxcore-log: 
,11-18 13:31:36.228  5627  5674 I jxcore-log: 2016-11-18 12:31:36 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js'
11-18 13:31:36.228  5627  5674 I jxcore-log: 
,11-18 13:31:36.239  5627  5674 I jxcore-log: 2016-11-18 12:31:36 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js'
11-18 13:31:36.239  5627  5674 I jxcore-log: 
,11-18 13:31:36.252  5627  5674 I jxcore-log: 2016-11-18 12:31:36 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js'
11-18 13:31:36.252  5627  5674 I jxcore-log: 
,11-18 13:31:36.262  5627  5674 I jxcore-log: 2016-11-18 12:31:36 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js'
11-18 13:31:36.262  5627  5674 I jxcore-log: 
,11-18 13:31:36.269  5627  5674 I jxcore-log: 2016-11-18 12:31:36 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js'
11-18 13:31:36.269  5627  5674 I jxcore-log: 
,11-18 13:31:36.291  5627  5674 I jxcore-log: 2016-11-18 12:31:36 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testUsn.js'
11-18 13:31:36.291  5627  5674 I jxcore-log: 
,11-18 13:31:36.297  5627  5674 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: SUPPORTED
,11-18 13:31:36.298  5627  5674 I jxcore-log: 2016-11-18 12:31:36 - INFO testUtils: 'BLE multiple advertisement supported'
11-18 13:31:36.298  5627  5674 I jxcore-log: 
,11-18 13:31:36.384  5627  5674 I jxcore-log: 2016-11-18 12:31:36 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-18 13:31:36.384  5627  5674 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-18 13:31:36.384  5627  5674 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-18 13:31:36.384  5627  5674 I jxcore-log: emit@events.js:82:1
11-18 13:31:36.384  5627  5674 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-18 13:31:36.384  5627  5674 I jxcore-log: emit@events.js:82:1'
11-18 13:31:36.384  5627  5674 I jxcore-log: 
,11-18 13:31:36.633  5627  5674 I jxcore-log: 2016-11-18 12:31:36 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-18 13:31:36.633  5627  5674 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-18 13:31:36.633  5627  5674 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-18 13:31:36.633  5627  5674 I jxcore-log: emit@events.js:82:1
11-18 13:31:36.633  5627  5674 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-18 13:31:36.633  5627  5674 I jxcore-log: emit@events.js:82:1'
11-18 13:31:36.633  5627  5674 I jxcore-log: 
,11-18 13:31:36.636  5627  5674 I jxcore-log: 2016-11-18 12:31:36 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-18 13:31:36.636  5627  5674 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-18 13:31:36.636  5627  5674 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-18 13:31:36.636  5627  5674 I jxcore-log: emit@events.js:82:1
11-18 13:31:36.636  5627  5674 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-18 13:31:36.636  5627  5674 I jxcore-log: emit@events.js:82:1'
11-18 13:31:36.636  5627  5674 I jxcore-log: 
,11-18 13:31:37.071  5627  5674 I jxcore-log: 2016-11-18 12:31:37 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-18 13:31:37.071  5627  5674 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-18 13:31:37.071  5627  5674 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-18 13:31:37.071  5627  5674 I jxcore-log: emit@events.js:82:1
11-18 13:31:37.071  5627  5674 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-18 13:31:37.071  5627  5674 I jxcore-log: emit@events.js:82:1'
11-18 13:31:37.071  5627  5674 I jxcore-log: 
,11-18 13:31:37.073  5627  5674 I jxcore-log: 2016-11-18 12:31:37 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-18 13:31:37.073  5627  5674 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-18 13:31:37.073  5627  5674 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-18 13:31:37.073  5627  5674 I jxcore-log: emit@events.js:82:1
11-18 13:31:37.073  5627  5674 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-18 13:31:37.073  5627  5674 I jxcore-log: emit@events.js:82:1'
11-18 13:31:37.073  5627  5674 I jxcore-log: 
,11-18 13:31:37.564  5627  5674 I jxcore-log: 2016-11-18 12:31:37 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-18 13:31:37.564  5627  5674 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-18 13:31:37.564  5627  5674 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-18 13:31:37.564  5627  5674 I jxcore-log: emit@events.js:82:1
11-18 13:31:37.564  5627  5674 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-18 13:31:37.564  5627  5674 I jxcore-log: emit@events.js:82:1'
11-18 13:31:37.564  5627  5674 I jxcore-log: 
,11-18 13:31:37.567  5627  5674 I jxcore-log: 2016-11-18 12:31:37 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-18 13:31:37.567  5627  5674 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-18 13:31:37.567  5627  5674 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-18 13:31:37.567  5627  5674 I jxcore-log: emit@events.js:82:1
11-18 13:31:37.567  5627  5674 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-18 13:31:37.567  5627  5674 I jxcore-log: emit@events.js:82:1'
11-18 13:31:37.567  5627  5674 I jxcore-log: 
,11-18 13:31:38.379   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-18 13:31:38.601  5627  5674 I jxcore-log: 2016-11-18 12:31:38 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-18 13:31:38.601  5627  5674 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-18 13:31:38.601  5627  5674 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-18 13:31:38.601  5627  5674 I jxcore-log: emit@events.js:82:1
11-18 13:31:38.601  5627  5674 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-18 13:31:38.601  5627  5674 I jxcore-log: emit@events.js:82:1'
11-18 13:31:38.601  5627  5674 I jxcore-log: 
,11-18 13:31:38.607  5627  5674 I jxcore-log: 2016-11-18 12:31:38 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-18 13:31:38.607  5627  5674 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-18 13:31:38.607  5627  5674 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-18 13:31:38.607  5627  5674 I jxcore-log: emit@events.js:82:1
11-18 13:31:38.607  5627  5674 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-18 13:31:38.607  5627  5674 I jxcore-log: emit@events.js:82:1'
11-18 13:31:38.607  5627  5674 I jxcore-log: 
,11-18 13:31:38.929   930  2983 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-18 13:31:39.381   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-18 13:31:39.668  5627  5674 I jxcore-log: 2016-11-18 12:31:39 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-18 13:31:39.668  5627  5674 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-18 13:31:39.668  5627  5674 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-18 13:31:39.668  5627  5674 I jxcore-log: emit@events.js:82:1
11-18 13:31:39.668  5627  5674 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-18 13:31:39.668  5627  5674 I jxcore-log: emit@events.js:82:1'
11-18 13:31:39.668  5627  5674 I jxcore-log: 
,11-18 13:31:39.671  5627  5674 I jxcore-log: 2016-11-18 12:31:39 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-18 13:31:39.671  5627  5674 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-18 13:31:39.671  5627  5674 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-18 13:31:39.671  5627  5674 I jxcore-log: emit@events.js:82:1
11-18 13:31:39.671  5627  5674 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-18 13:31:39.671  5627  5674 I jxcore-log: emit@events.js:82:1'
11-18 13:31:39.671  5627  5674 I jxcore-log: 
,11-18 13:31:40.382   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-18 13:31:40.714  5627  5674 I jxcore-log: 2016-11-18 12:31:40 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-18 13:31:40.714  5627  5674 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-18 13:31:40.714  5627  5674 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-18 13:31:40.714  5627  5674 I jxcore-log: emit@events.js:82:1
11-18 13:31:40.714  5627  5674 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-18 13:31:40.714  5627  5674 I jxcore-log: emit@events.js:82:1'
11-18 13:31:40.714  5627  5674 I jxcore-log: 
,11-18 13:31:40.717  5627  5674 I jxcore-log: 2016-11-18 12:31:40 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-18 13:31:40.717  5627  5674 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-18 13:31:40.717  5627  5674 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-18 13:31:40.717  5627  5674 I jxcore-log: emit@events.js:82:1
11-18 13:31:40.717  5627  5674 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-18 13:31:40.717  5627  5674 I jxcore-log: emit@events.js:82:1'
11-18 13:31:40.717  5627  5674 I jxcore-log: 
,11-18 13:31:41.383   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-18 13:31:41.752  5627  5674 I jxcore-log: 2016-11-18 12:31:41 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-18 13:31:41.752  5627  5674 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-18 13:31:41.752  5627  5674 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-18 13:31:41.752  5627  5674 I jxcore-log: emit@events.js:82:1
11-18 13:31:41.752  5627  5674 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-18 13:31:41.752  5627  5674 I jxcore-log: emit@events.js:82:1'
11-18 13:31:41.752  5627  5674 I jxcore-log: 
,11-18 13:31:41.758  5627  5674 I jxcore-log: 2016-11-18 12:31:41 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-18 13:31:41.758  5627  5674 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-18 13:31:41.758  5627  5674 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-18 13:31:41.758  5627  5674 I jxcore-log: emit@events.js:82:1
11-18 13:31:41.758  5627  5674 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-18 13:31:41.758  5627  5674 I jxcore-log: emit@events.js:82:1'
11-18 13:31:41.758  5627  5674 I jxcore-log: 
,11-18 13:31:41.951   930  2983 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-18 13:31:42.384   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-18 13:31:42.801  5627  5674 I jxcore-log: 2016-11-18 12:31:42 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-18 13:31:42.801  5627  5674 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-18 13:31:42.801  5627  5674 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-18 13:31:42.801  5627  5674 I jxcore-log: emit@events.js:82:1
11-18 13:31:42.801  5627  5674 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-18 13:31:42.801  5627  5674 I jxcore-log: emit@events.js:82:1'
11-18 13:31:42.801  5627  5674 I jxcore-log: 
,11-18 13:31:42.804  5627  5674 I jxcore-log: 2016-11-18 12:31:42 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-18 13:31:42.804  5627  5674 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-18 13:31:42.804  5627  5674 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-18 13:31:42.804  5627  5674 I jxcore-log: emit@events.js:82:1
11-18 13:31:42.804  5627  5674 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-18 13:31:42.804  5627  5674 I jxcore-log: emit@events.js:82:1'
11-18 13:31:42.804  5627  5674 I jxcore-log: 
,11-18 13:31:43.385   535   535 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,11-18 13:31:43.836  5627  5674 I jxcore-log: 2016-11-18 12:31:43 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-18 13:31:43.836  5627  5674 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-18 13:31:43.836  5627  5674 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-18 13:31:43.836  5627  5674 I jxcore-log: emit@events.js:82:1
11-18 13:31:43.836  5627  5674 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-18 13:31:43.836  5627  5674 I jxcore-log: emit@events.js:82:1'
11-18 13:31:43.836  5627  5674 I jxcore-log: 
,11-18 13:31:43.840  5627  5674 I jxcore-log: 2016-11-18 12:31:43 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-18 13:31:43.840  5627  5674 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-18 13:31:43.840  5627  5674 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-18 13:31:43.840  5627  5674 I jxcore-log: emit@events.js:82:1
11-18 13:31:43.840  5627  5674 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-18 13:31:43.840  5627  5674 I jxcore-log: emit@events.js:82:1'
11-18 13:31:43.840  5627  5674 I jxcore-log: 
,11-18 13:31:44.903  5627  5674 I jxcore-log: 2016-11-18 12:31:44 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-18 13:31:44.903  5627  5674 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-18 13:31:44.903  5627  5674 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-18 13:31:44.903  5627  5674 I jxcore-log: emit@events.js:82:1
11-18 13:31:44.903  5627  5674 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-18 13:31:44.903  5627  5674 I jxcore-log: emit@events.js:82:1'
11-18 13:31:44.903  5627  5674 I jxcore-log: 
,11-18 13:31:44.907  5627  5674 I jxcore-log: 2016-11-18 12:31:44 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-18 13:31:44.907  5627  5674 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-18 13:31:44.907  5627  5674 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-18 13:31:44.907  5627  5674 I jxcore-log: emit@events.js:82:1
11-18 13:31:44.907  5627  5674 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-18 13:31:44.907  5627  5674 I jxcore-log: emit@events.js:82:1'
11-18 13:31:44.907  5627  5674 I jxcore-log: 
,11-18 13:31:45.858   930  2981 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-18 13:31:45.938  5627  5674 I jxcore-log: 2016-11-18 12:31:45 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-18 13:31:45.938  5627  5674 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-18 13:31:45.938  5627  5674 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-18 13:31:45.938  5627  5674 I jxcore-log: emit@events.js:82:1
11-18 13:31:45.938  5627  5674 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-18 13:31:45.938  5627  5674 I jxcore-log: emit@events.js:82:1'
11-18 13:31:45.938  5627  5674 I jxcore-log: 
,11-18 13:31:45.943  5627  5674 I jxcore-log: 2016-11-18 12:31:45 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-18 13:31:45.943  5627  5674 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-18 13:31:45.943  5627  5674 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-18 13:31:45.943  5627  5674 I jxcore-log: emit@events.js:82:1
11-18 13:31:45.943  5627  5674 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-18 13:31:45.943  5627  5674 I jxcore-log: emit@events.js:82:1'
11-18 13:31:45.943  5627  5674 I jxcore-log: 
,11-18 13:31:46.975  5627  5674 I jxcore-log: 2016-11-18 12:31:46 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-18 13:31:46.975  5627  5674 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-18 13:31:46.975  5627  5674 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-18 13:31:46.975  5627  5674 I jxcore-log: emit@events.js:82:1
11-18 13:31:46.975  5627  5674 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-18 13:31:46.975  5627  5674 I jxcore-log: emit@events.js:82:1'
11-18 13:31:46.975  5627  5674 I jxcore-log: 
,11-18 13:31:46.981  5627  5674 I jxcore-log: 2016-11-18 12:31:46 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-18 13:31:46.981  5627  5674 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-18 13:31:46.981  5627  5674 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-18 13:31:46.981  5627  5674 I jxcore-log: emit@events.js:82:1
11-18 13:31:46.981  5627  5674 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-18 13:31:46.981  5627  5674 I jxcore-log: emit@events.js:82:1'
11-18 13:31:46.981  5627  5674 I jxcore-log: 
,11-18 13:31:48.015  5627  5674 I jxcore-log: 2016-11-18 12:31:48 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-18 13:31:48.015  5627  5674 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-18 13:31:48.015  5627  5674 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-18 13:31:48.015  5627  5674 I jxcore-log: emit@events.js:82:1
11-18 13:31:48.015  5627  5674 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-18 13:31:48.015  5627  5674 I jxcore-log: emit@events.js:82:1'
11-18 13:31:48.015  5627  5674 I jxcore-log: 
,11-18 13:31:48.017  5627  5674 I jxcore-log: 2016-11-18 12:31:48 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-18 13:31:48.017  5627  5674 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-18 13:31:48.017  5627  5674 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-18 13:31:48.017  5627  5674 I jxcore-log: emit@events.js:82:1
11-18 13:31:48.017  5627  5674 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-18 13:31:48.017  5627  5674 I jxcore-log: emit@events.js:82:1'
11-18 13:31:48.017  5627  5674 I jxcore-log: 
,11-18 13:31:49.069  5627  5674 I jxcore-log: 2016-11-18 12:31:49 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-18 13:31:49.069  5627  5674 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-18 13:31:49.069  5627  5674 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-18 13:31:49.069  5627  5674 I jxcore-log: emit@events.js:82:1
11-18 13:31:49.069  5627  5674 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-18 13:31:49.069  5627  5674 I jxcore-log: emit@events.js:82:1'
11-18 13:31:49.069  5627  5674 I jxcore-log: 
,11-18 13:31:49.074  5627  5674 I jxcore-log: 2016-11-18 12:31:49 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-18 13:31:49.074  5627  5674 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-18 13:31:49.074  5627  5674 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-18 13:31:49.074  5627  5674 I jxcore-log: emit@events.js:82:1
11-18 13:31:49.074  5627  5674 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-18 13:31:49.074  5627  5674 I jxcore-log: emit@events.js:82:1'
11-18 13:31:49.074  5627  5674 I jxcore-log: 
,11-18 13:31:50.110  5627  5674 I jxcore-log: 2016-11-18 12:31:50 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-18 13:31:50.110  5627  5674 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-18 13:31:50.110  5627  5674 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-18 13:31:50.110  5627  5674 I jxcore-log: emit@events.js:82:1
11-18 13:31:50.110  5627  5674 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-18 13:31:50.110  5627  5674 I jxcore-log: emit@events.js:82:1'
11-18 13:31:50.110  5627  5674 I jxcore-log: 
,11-18 13:31:50.119  5627  5674 E jxcore  : Error!: error is undefined
11-18 13:31:50.119  5627  5674 E jxcore  : Stack: [{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/lib/CoordinatedClient.js","_functionName":"CoordinatedClient.prototype._error","_lineNumber":"223","_columnNumber":"1","_msg":"    at CoordinatedClient.prototype._error@/data/data/com.test.thalitest/files/www/jxcore/lib/CoordinatedClient.js:223:1"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/component-emitter/index.js","_functionName":"Emitter.prototype.emit","_lineNumber":"131","_columnNumber":"7","_msg":"    at Emitter.prototype.emit@/data/data/com.test.thalitest/files/www/jxcore/node_modules/component-emitter/index.js:131:7"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/socket.js","_functionName":"Socket.prototype.emit","_lineNumber":"133","_columnNumber":"5","_msg":"    at Socket.prototype.emit@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/socket.js:133:5"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js","_functionName":"Manager.prototype.emitAll","_lineNumber":"81","_columnNumber":"7","_msg":"    at Manager.prototype.emitAll@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:81:7"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js","_functionName":"Manager.prototype.reconnect","_lineNumber":"507","_columnNumber":"5","_msg":"    at Manager.prototype.reconnect@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:507:5"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js","_functionName":"Manager.prototype.reconnect/timer</<","_lineNumber":"528","_columnNumber":"11","_msg":"    at Manager.prototype.reconnect/timer</<@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:528:11"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js","_functionName":"Manager.prototype.connect/errorSub<","_lineNumber":"235","_columnNumber":"7","_msg":"    at Manager.prototype.connect/errorSub<@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:235:7"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/node_modules/component-emitter/index.js","_functionName":"Emitter.prototype.emit","_lineNumber":"134","_columnNumber":"7","_msg":"    at Emitter.prototype.emit@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/node_modules/component-emitter/index.js:134:7"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/socket.js","_functionName":"Socket.prototype.onError","_lineNumber":"670","_columnNumber":"3","_msg":"    at Socket.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/socket.js:670:3"}]
,11-18 13:31:50.123  5627  5674 I jxcore-log: 2016-11-18 12:31:50 - ERROR TestsProcess: 'uncaught exception, error: 'TypeError: error is undefined', stack: 'TypeError: error is undefined
11-18 13:31:50.123  5627  5674 I jxcore-log:     at CoordinatedClient.prototype._error@/data/data/com.test.thalitest/files/www/jxcore/lib/CoordinatedClient.js:223:1
11-18 13:31:50.123  5627  5674 I jxcore-log:     at Emitter.prototype.emit@/data/data/com.test.thalitest/files/www/jxcore/node_modules/component-emitter/index.js:131:7
11-18 13:31:50.123  5627  5674 I jxcore-log:     at Socket.prototype.emit@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/socket.js:133:5
11-18 13:31:50.123  5627  5674 I jxcore-log:     at Manager.prototype.emitAll@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:81:7
11-18 13:31:50.123  5627  5674 I jxcore-log:     at Manager.prototype.reconnect@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:507:5
11-18 13:31:50.123  5627  5674 I jxcore-log:     at Manager.prototype.reconnect/timer</<@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:528:11
11-18 13:31:50.123  5627  5674 I jxcore-log:     at Manager.prototype.connect/errorSub<@/data/data/com.test.thalitest/files/www/jxcore/node_modules/sock
,11-18 13:31:50.125  5627  5674 I jxcore-log: 2016-11-18 12:31:50 - ERROR TestsProcess: '****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****'
11-18 13:31:50.125  5627  5674 I jxcore-log: 
11-18 13:31:50.126  5627  5674 E jxcore-log: TypeError: 
,11-18 13:31:50.127  5627  5674 E jxcore-log: error is undefined
11-18 13:31:50.127  5627  5674 E jxcore-log:  (/data/data/com.test.thalitest/files/www/jxcore/lib/CoordinatedClient.js 223:0)
11-18 13:31:50.127  5627  5674 E jxcore-log: 
,11-18 13:31:50.220   930  3727 D GraphicsStats: Buffer count: 2
11-18 13:31:50.221   930  2982 D WifiService: Client connection lost with reason: 4
,11-18 13:31:50.221   930   940 I WindowState: WIN DEATH: Window{45977f5 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,11-18 13:31:50.235   527   527 I Zygote  : Process 5627 exited cleanly (139)
,11-18 13:31:50.246   930  3823 I ActivityManager: Process com.test.thalitest (pid 5627) has died
,11-18 13:31:50.247   930  3823 W ActivityManager: Force removing ActivityRecord{6b176d2 u0 com.test.thalitest/.MainActivity t70}: app died, no saved state
,11-18 13:31:50.290  4881  4881 W Binder_A: type=1400 audit(0.0:126): avc: denied { ioctl } for path="socket:[27912]" dev="sockfs" ino=27912 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
11-18 13:31:50.290  4881  4881 W Binder_A: type=1400 audit(0.0:127): avc: denied { ioctl } for path="socket:[27912]" dev="sockfs" ino=27912 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-18 13:31:50.296   930  4881 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 5627 uid 10077
11-18 13:31:50.297  3689  3689 I Keyboard.Facilitator: onFinishInput()
,11-18 13:31:50.349  3990  5881 I MicroRecognitionRnrImpl: Starting detection.
,11-18 13:31:50.351  3990  5882 I MicrophoneInputStream: mic_starting com.google.android.apps.gsa.speech.audio.x@3d261d5
,11-18 13:31:50.352   512  5884 I AudioFlinger: AudioFlinger's thread 0xf1b40000 ready to run
,11-18 13:31:50.356   512  3029 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
,11-18 13:31:50.358  3990  5882 I MicrophoneInputStream: mic_started com.google.android.apps.gsa.speech.audio.x@3d261d5
,11-18 13:31:50.368   512  5884 D audio_hw_primary: select_devices: out_snd_device(0: none) in_snd_device(63: voice-rec-mic)
,11-18 13:31:50.368   512  5884 D msm8974_platform: platform_send_audio_calibration: sending audio calibration for snd_device(63) acdb_id(62)
,11-18 13:31:50.368   512  5884 I ACDB-LOADER: ACDB AFE returned = -19
11-18 13:31:50.369   512  5884 I soundtrigger: audio_extn_sound_trigger_update_device_status: device 0x3f of type 1 for Event 1
11-18 13:31:50.369   512  5884 D sound_trigger_platform: platform_stdev_check_and_update_concurrency: concurrency active 0, tx 1, rx 0, concurrency session_allowed 0
11-18 13:31:50.369   512  5884 D audio_hw_primary: enable_snd_device: snd_device(63: voice-rec-mic)
,11-18 13:31:50.377   512  5884 D audio_hw_primary: enable_audio_route: apply and update mixer path: audio-record
,11-18 13:31:50.456  3990  3990 I HotwordWorkerImpl: onReady
,11-18 13:31:50.532  5876  5876 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,11-18 13:31:50.535  5876  5876 D AndroidRuntime: CheckJNI is OFF
,11-18 13:31:50.559  5876  5876 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,11-18 13:31:50.585  5876  5876 I Radio-JNI: register_android_hardware_Radio DONE
,11-18 13:31:50.600  5876  5876 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,11-18 13:31:50.609   930   943 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=-1: uninstall pkg
,11-18 13:31:50.722   930   953 I art     : Starting a blocking GC Explicit
,11-18 13:31:50.830  3812  4068 W OpenGLRenderer: Incorrectly called buildLayer on View: ShortcutAndWidgetContainer, destroying layer...
,11-18 13:31:50.843   930   953 I art     : Explicit concurrent mark sweep GC freed 78367(4MB) AllocSpace objects, 21(672KB) LOS objects, 33% free, 29MB/43MB, paused 2.253ms total 120.278ms
,11-18 13:31:50.863   930   953 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,11-18 13:31:50.866  5876  5876 I art     : System.exit called, status: 0
,11-18 13:31:50.866  5876  5876 I AndroidRuntime: VM exiting with result code 0.
,11-18 13:31:50.872   930   953 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=0: pkg removed
,11-18 13:31:50.883  3689  3689 I Keyboard.Facilitator: resetDictionaries() : en_US
,11-18 13:31:50.885  5725  5725 D BluetoothMapAppObserver: onReceive
,11-18 13:31:50.885  5725  5725 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
,11-18 13:31:50.894  4076  4185 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,11-18 13:31:50.906   930  2973 I InputReader: Reconfiguring input devices.  changes=0x00000010
,11-18 13:31:50.910  3689  5895 I Keyboard.Facilitator.DecoderInitializer: run()
,11-18 13:31:50.919  3433  5896 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,11-18 13:31:50.918  3689  5895 I Decoder : createOrResetDecoder
,11-18 13:31:50.951  3791  3791 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,11-18 13:31:50.950   929   929 W kworker/1:3: type=1400 audit(0.0:128): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-18 13:31:50.954   929   929 W kworker/1:3: type=1400 audit(0.0:129): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-18 13:31:50.957   929   929 W kworker/1:3: type=1400 audit(0.0:130): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-18 13:31:50.967   930   930 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,11-18 13:31:50.968  3610  3610 I ConfigService: onCreate
,11-18 13:31:50.969  3433  3459 E SQLiteLog: (2570) os_unix.c:31406: (30) unlink(/data/user/0/com.android.providers.contacts/databases/contacts2.db-mjB6F8C5961) - 
,11-18 13:31:50.972  3610  5900 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/config.db'.
11-18 13:31:50.972  3610  5900 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
11-18 13:31:50.972  3610  5900 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
11-18 13:31:50.972  3610  5900 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
11-18 13:31:50.972  3610  5900 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
11-18 13:31:50.972  3610  5900 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
11-18 13:31:50.972  3610  5900 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
11-18 13:31:50.972  3610  5900 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
11-18 13:31:50.972  3610  5900 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
11-18 13:31:50.972  3610  5900 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
11-18 13:31:50.972  3610  5900 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
11-18 13:31:50.972  3610  5900 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
11-18 13:31:50.972  3610  5900 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
11-18 13:31:50.972  3610  5900 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
11-18 13:31:50.972  3610  5900 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
11-18 13:31:50.972  3610  5900 E SQLiteDatabase: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
11-18 13:31:50.972  3610  5900 E SQLiteDatabase: 	at com.google.android.gms.config.j.run(SourceFile:152)
11-18 13:31:50.972  3610  5900 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
,11-18 13:31:50.972  3610  5900 E SQLiteOpenHelper: Couldn't open config.db for writing (will try read-only):
11-18 13:31:50.972  3610  5900 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
11-18 13:31:50.972  3610  5900 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
11-18 13:31:50.972  3610  5900 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
11-18 13:31:50.972  3610  5900 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
11-18 13:31:50.972  3610  5900 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
11-18 13:31:50.972  3610  5900 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
11-18 13:31:50.972  3610  5900 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
11-18 13:31:50.972  3610  5900 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
11-18 13:31:50.972  3610  5900 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
11-18 13:31:50.972  3610  5900 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
11-18 13:31:50.972  3610  5900 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
11-18 13:31:50.972  3610  5900 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
11-18 13:31:50.972  3610  5900 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
11-18 13:31:50.972  3610  5900 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
11-18 13:31:50.972  3610  5900 E SQLiteOpenHelper: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
11-18 13:31:50.972  3610  5900 E SQLiteOpenHelper: 	at com.google.android.gms.config.j.run(SourceFile:152)
11-18 13:31:50.972  3610  5900 E SQLiteOpenHelper: 	at java.lang.Thread.run(Thread.java:818)
11-18 13:31:50.974  3610  5900 W SQLiteOpenHelper: Opened config.db in read-only mode
,11-18 13:31:50.982  3610  3610 E SQLiteLog: (3850) statement aborts at 26: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
,11-18 13:31:50.982  3610  3610 D AndroidRuntime: Shutting down VM
--------- beginning of crash
11-18 13:31:50.983  3610  3610 E AndroidRuntime: FATAL EXCEPTION: main
11-18 13:31:50.983  3610  3610 E AndroidRuntime: Process: com.google.process.gapps, PID: 3610
11-18 13:31:50.983  3610  3610 E AndroidRuntime: java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
11-18 13:31:50.983  3610  3610 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2732)
11-18 13:31:50.983  3610  3610 E AndroidRuntime: 	at android.app.ActivityThread.-wrap14(ActivityThread.java)
11-18 13:31:50.983  3610  3610 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1421)
11-18 13:31:50.983  3610  3610 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-18 13:31:50.983  3610  3610 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
11-18 13:31:50.983  3610  3610 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-18 13:31:50.983  3610  3610 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
11-18 13:31:50.983  3610  3610 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-18 13:31:50.983  3610  3610 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-18 13:31:50.983  3610  3610 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
11-18 13:31:50.983  3610  3610 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
11-18 13:31:50.983  3610  3610 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
11-18 13:31:50.983  3610  3610 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
11-18 13:31:50.983  3610  3610 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
11-18 13:31:50.983  3610  3610 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
11-18 13:31:50.983  3610  3610 E AndroidRuntime: 	at com.google.android.gms.gcm.bg.a(SourceFile:310)
11-18 13:31:50.983  3610  3610 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
11-18 13:31:50.983  3610  3610 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
11-18 13:31:50.983  3610  3610 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2725)
11-18 13:31:50.983  3610  3610 E AndroidRuntime: 	... 8 more
11-18 13:31:50.983   930   942 W AtomicFile: Couldn't rename file /data/system/users/0/runtime-permissions.xml to backup file /data/system/users/0/runtime-permissions.xml.bak
11-18 13:31:50.984  3812  3969 E SQLiteLog: (3850) statement aborts at 23: [DELETE FROM icons WHERE componentName LIKE ? AND profileId = ?] disk I/O error
11-18 13:31:50.984   930   942 E PackageManager: Failed to write settings, restoring backup
11-18 13:31:50.984   930   942 E PackageManager: java.io.IOException: Couldn't create directory /data/system/users/0/runtime-permissions.xml
11-18 13:31:50.984   930   942 E PackageManager: 	at android.util.AtomicFile.startWrite(AtomicFile.java:106)
11-18 13:31:50.984   930   942 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.writePermissionsSync(Settings.java:4615)
11-18 13:31:50.984   930   942 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.-wrap1(Settings.java)
11-18 13:31:50.984   930   942 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence$MyHandler.handleMessage(Settings.java:4830)
11-18 13:31:50.984   930   942 E PackageManager: 	at an,droid.os.Handler.dispatchMessage(Handler.java:102)
11-18 13:31:50.984   930   942 E PackageManager: 	at android.os.Looper.loop(Looper.java:148)
11-18 13:31:50.984   930   942 E PackageManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
11-18 13:31:50.988  3689  5895 I Keyboard.Facilitator.MainLanguageModelLoader: run()
11-18 13:31:50.988   930  5902 E DropBoxManagerService: Can't write: system_app_crash
11-18 13:31:50.988   930  5902 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop112.tmp: open failed: EROFS (Read-only file system)
11-18 13:31:50.988   930  5902 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
11-18 13:31:50.988   930  5902 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
11-18 13:31:50.988   930  5902 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
11-18 13:31:50.988   930  5902 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
11-18 13:31:50.988   930  5902 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
11-18 13:31:50.988   930  5902 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
11-18 13:31:50.988   930  5902 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
11-18 13:31:50.988   930  5902 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
11-18 13:31:50.988   930  5902 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
11-18 13:31:50.988   930  5902 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
11-18 13:31:50.988   930  5902 E DropBoxManagerService: 	... 5 more
11-18 13:31:50.989   930   943 E DropBoxManagerService: Can't write: system_server_wtf
11-18 13:31:50.989   930   943 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop15.tmp: open failed: EROFS (Read-only file system)
11-18 13:31:50.989   930   943 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
11-18 13:31:50.989   930   943 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
11-18 13:31:50.989   930   943 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
11-18 13:31:50.989   930   943 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
11-18 13:31:50.989   930   943 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
11-18 13:31:50.989   930   943 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
11-18 13:31:50.989   930   943 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12561)
11-18 13:31:50.989   930   943 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.handleApplicationWtfInner(ActivityManagerService.java:12374)
11-18 13:31:50.989   930   943 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:12346)
11-18 13:31:50.989   930   943 E DropBoxManagerService: 	at android.os.Handler.handleCallback(Handler.java:739)
11-18 13:31:50.989   930   943 E DropBoxManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:95)
11-18 13:31:50.989   930   943 E DropBoxManagerService: 	at android.os.Looper.loop(Looper.java:148)
11-18 13:31:50.989   930   943 E DropBoxManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
11-18 13:31:50.989   930   943 E DropBoxManagerService: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
11-18 13:31:50.989   930   943 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
11-18 13:31:50.989   930   943 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
11-18 13:31:50.989   930   943 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
11-18 13:31:50.989   930   943 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
11-18 13:31:50.989   930   943 E DropBoxManagerService: 	... 13 more
11-18 13:31:51.005   930  3823 I ActivityManager: Start proc 5903:com.google.android.googlequicksearchbox:crash_report/u0a29 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
11-18 13:31:51.006  3812  3969 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
11-18 13:31:51.006  3812  3969 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 3812
11-18 13:31:51.006  3812  3969 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
11-18 13:31:51.006  3812  3969 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
11-18 13:31:51.006  3812  3969 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
11-18 13:31:51.006  3812  3969 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
11-18 13:31:51.006  3812  3969 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
11-18 13:31:51.006  3812  3969 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
11-18 13:31:51.006  3812  3969 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
11-18 13:31:51.006  3812  3969 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
11-18 13:31:51.006  3812  3969 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
11-18 13:31:51.006  3812  3969 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
11-18 13:31:51.006  3812  3969 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
11-18 13:31:51.006  3812  3969 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,11-18 13:31:51.018  3433  5896 E SQLiteLog: (3850) statement aborts at 18: [DELETE FROM calls WHERE (((source_package = 'com.test.thalitest'))) AND ((type = 4))] disk I/O error
11-18 13:31:51.019  3433  5896 E AndroidRuntime: FATAL EXCEPTION: IntentService[VoicemailCleanupService]
11-18 13:31:51.019  3433  5896 E AndroidRuntime: Process: android.process.acore, PID: 3433
11-18 13:31:51.019  3433  5896 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
11-18 13:31:51.019  3433  5896 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
11-18 13:31:51.019  3433  5896 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
11-18 13:31:51.019  3433  5896 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
11-18 13:31:51.019  3433  5896 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
11-18 13:31:51.019  3433  5896 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
11-18 13:31:51.019  3433  5896 E AndroidRuntime: 	at com.android.providers.contacts.DbModifierWithNotification.delete(DbModifierWithNotification.java:197)
11-18 13:31:51.019  3433  5896 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:219)
11-18 13:31:51.019  3433  5896 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
11-18 13:31:51.019  3433  5896 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
11-18 13:31:51.019  3433  5896 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
11-18 13:31:51.019  3433  5896 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
11-18 13:31:51.019  3433  5896 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
11-18 13:31:51.019  3433  5896 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
11-18 13:31:51.019  3433  5896 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-18 13:31:51.019  3433  5896 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
11-18 13:31:51.019  3433  5896 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
11-18 13:31:51.022  3433  3459 I Process : Sending signal. PID: 3433 SIG: 9
11-18 13:31:51.020   708   708 W Binder_4: type=1400 audit(0.0:131): avc: denied { ioctl } for path="socket:[30199]" dev="sockfs" ino=30199 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
11-18 13:31:51.020   708   708 W Binder_4: type=1400 audit(0.0:132): avc: denied { ioctl } for path="socket:[30199]" dev="sockfs" ino=30199 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
11-18 13:31:51.024   409   409 W Binder_2: type=1400 audit(0.0:133): avc: denied { ioctl } for path="socket:[33302]" dev="sockfs" ino=33302 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
11-18 13:31:51.024   409   409 W Binder_2: type=1400 audit(0.0:134): avc: denied { ioctl } for path="socket:[33302]" dev="sockfs" ino=33302 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
11-18 13:31:51.028   930  5915 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
11-18 13:31:51.034  3689  5895 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /data/user/0/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
11-18 13:31:51.034   930  3626 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
11-18 13:31:51.034   930  5917 E DropBoxManagerService: Can't write: system_app_crash
11-18 13:31:51.034   930  5917 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop114.tmp: open failed: EROFS (Read-only file system)
11-18 13:31:51.034   930  5917 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
11-18 13:31:51.034   930  5917 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
11-18 13:31:51.034   930  5917 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
11-18 13:31:51.034   930  5917 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
11-18 13:31:51.034   930  5917 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
11-18 13:31:51.034   930  5917 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
11-18 13:31:51.034   930  5917 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
11-18 13:31:51.034   930  5917 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
11-18 13:31:51.034   930  5917 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
11-18 13:31:51.034   930  5917 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
11-18 13:31:51.034   930  5917 E DropBoxManagerService: 	... 5 more
11-18 13:31:51.036  3689  5895 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
11-18 13:31:51.036  3689  5895 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
11-18 13:31:51.037   930  5918 E DropBoxManagerService: Can't write: system_app_crash
11-18 13:31:51.037   930  5918 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop115.tmp: open failed: EROFS (Read-only file system)
11-18 13:31:51.037   930  5918 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
11-18 13:31:51.037   930  5918 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
11-18 13:31:51.037   930  5918 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
11-18 13:31:51.037   930  5918 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
11-18 13:31:51.037   930  5918 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
11-18 13:31:51.037   930  5918 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
11-18 13:31:51.037   930  5918 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
11-18 13:31:51.037   930  5918 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
11-18 13:31:51.037   930  5918 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
11-18 13:31:51.037   930  5918 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
11-18 13:31:51.037   930  5918 E DropBoxManagerService: 	... 5 more
11-18 13:31:51.038  3990  4009 W SearchService: Abort, client detached.
11-18 13:31:51.038  3689  5895 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Contacts.dict
11-18 13:31:51.038  3689  5895 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = history
11-18 13:31:51.039  3689  5895 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loaded File = UserHistory.en_US.dict
11-18 13:31:51.039  3689  5895 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = user
11-18 13:31:51.040  3990  3990 I HotwordDetector: Closing mic
11-18 13:31:51.040  3689  5895 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Personal.en_US.dict
11-18 13:31:51.040  3689  5895 I Keyboard.Facilitator.PersonalDictionaryLoader: run() : Loaded (exit)
11-18 13:31:51.040  3689  5895 I Keyboard.Facilitator.Delight2FileSweeper: run()
11-18 13:31:51.040  3990  4214 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@3d261d5
11-18 13:31:51.040  3689  5895 I Keyboard.Facilitator.RecurringTaskScheduler: run()
11-18 13:31:51.040  3689  5895 I StatsUtilsManager: startPeriodStatsRecorder() : Success
11-18 13:31:51.040  3990  5882 E AudioRecord-JNI: Error -4 during AudioRecord native read
11-18 13:31:51.040  3689  5895 I PeriodicStatsRecorder: shouldRecordStats() = Too Soon
,11-18 13:31:51.057   930  3193 I ActivityManager: Process android.process.acore (pid 3433) has died
11-18 13:31:51.058   930  3193 W ActivityManager: Scheduling restart of crashed service com.android.providers.contacts/.VoicemailCleanupService in 1000ms
,11-18 13:31:51.114   512  5884 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
,11-18 13:31:51.116   512  5884 D audio_hw_primary: disable_snd_device: snd_device(63: voice-rec-mic)
,11-18 13:31:51.118   930  3191 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
,11-18 13:31:51.124   512  5884 I soundtrigger: audio_extn_sound_trigger_update_device_status: device 0x3f of type 1 for Event 0
,11-18 13:31:51.124   512  5884 D sound_trigger_platform: platform_stdev_check_and_update_concurrency: concurrency active 0, tx 0, rx 0, concurrency session_allowed 1
,11-18 13:31:51.125   512  3029 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
11-18 13:31:51.128  3990  5881 I MicroRecognitionRnrImpl: Detection finished
,11-18 13:31:51.129  3990  4229 I MicroRecognitionRnrImpl: Stopping hotword detection.
,11-18 13:31:51.358   382   480 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0

```
