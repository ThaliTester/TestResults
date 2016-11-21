#### Test 946263757280694_thali07_Huawei-Nexus 6P Logs


```
--------- beginning of main
11-21 16:24:47.376  4160  4540 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,11-21 16:24:47.847  5642  5642 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
11-21 16:24:47.853  5642  5642 D AndroidRuntime: CheckJNI is OFF
11-21 16:24:47.878  5642  5642 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
11-21 16:24:47.909  5642  5642 I Radio-JNI: register_android_hardware_Radio DONE
11-21 16:24:47.925  5642  5642 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
11-21 16:24:47.946   927   938 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
11-21 16:24:47.978  5642  5642 D AndroidRuntime: Shutting down VM
11-21 16:24:47.979  4012  4027 W SearchService: Abort, client detached.
11-21 16:24:47.982  4012  4012 I HotwordDetector: Closing mic
11-21 16:24:47.983  4012  4245 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@1f950bc
11-21 16:24:47.983  4012  4258 E AudioRecord-JNI: Error -4 during AudioRecord native read
11-21 16:24:47.996   927  3192 I ActivityManager: Start proc 5653:com.test.thalitest/u0a77 for activity com.test.thalitest/.MainActivity
11-21 16:24:48.050   514  4265 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
11-21 16:24:48.051   514  4265 D audio_hw_primary: disable_snd_device: snd_device(63: voice-rec-mic)
11-21 16:24:48.056   514  4265 I soundtrigger: audio_extn_sound_trigger_update_device_status: device 0x3f of type 1 for Event 0
11-21 16:24:48.057   514  4265 D sound_trigger_platform: platform_stdev_check_and_update_concurrency: concurrency active 0, tx 0, rx 0, concurrency session_allowed 1
11-21 16:24:48.058   514  3063 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
11-21 16:24:48.060  4012  4249 I MicroRecognitionRnrImpl: Detection finished
11-21 16:24:48.060  4012  4246 I MicroRecognitionRnrImpl: Stopping hotword detection.
11-21 16:24:48.086  5653  5653 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011750)
11-21 16:24:48.105  5653  5653 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
11-21 16:24:48.129  5653  5653 I LibraryLoader: Time to load native libraries: 19 ms (timestamps 7464-7483)
11-21 16:24:48.129  5653  5653 I LibraryLoader: Expected native library version number "",actual native library version number ""
11-21 16:24:48.154  5653  5653 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {c92ad4b}
11-21 16:24:48.155  5653  5653 I LibraryLoader: Expected native library version number "",actual native library version number ""
11-21 16:24:48.155  5653  5653 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
11-21 16:24:48.158  5653  5653 I BrowserStartupController: Initializing chromium process, singleProcess=true
11-21 16:24:48.158  5653  5653 E SysUtils: ApplicationContext is null in ApplicationStatus
11-21 16:24:48.192  5653  5653 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,11-21 16:24:48.201  5653  5653 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,11-21 16:24:48.202  5653  5653 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
11-21 16:24:48.202  5653  5653 I Adreno  : QUALCOMM build                   : 63c06b2, I8366cd0437
11-21 16:24:48.202  5653  5653 I Adreno  : Build Date                       : 12/06/15
11-21 16:24:48.202  5653  5653 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
11-21 16:24:48.202  5653  5653 I Adreno  : Local Branch                     : mybranch17112971
11-21 16:24:48.202  5653  5653 I Adreno  : Remote Branch                    : quic/LA.BF64.1.2.9_v2
11-21 16:24:48.202  5653  5653 I Adreno  : Remote Branch                    : NONE
11-21 16:24:48.202  5653  5653 I Adreno  : Reconstruct Branch               : NOTHING
,11-21 16:24:48.240   927   944 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@79c437a:true
,11-21 16:24:48.274   404   404 W Binder_1: type=1400 audit(0.0:99): avc: denied { ioctl } for path="socket:[33905]" dev="sockfs" ino=33905 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-21 16:24:48.274   404   404 W Binder_1: type=1400 audit(0.0:100): avc: denied { ioctl } for path="socket:[33905]" dev="sockfs" ino=33905 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-21 16:24:48.285  5653  5653 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,11-21 16:24:48.293  5653  5653 D SystemWebViewEngine: CordovaWebView is running on device made by: Huawei
,11-21 16:24:48.317  2644  2644 W Binder_3: type=1400 audit(0.0:101): avc: denied { ioctl } for path="socket:[32764]" dev="sockfs" ino=32764 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-21 16:24:48.317  2644  2644 W Binder_3: type=1400 audit(0.0:102): avc: denied { ioctl } for path="socket:[32764]" dev="sockfs" ino=32764 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
11-21 16:24:48.321  5653  5690 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,11-21 16:24:48.324   938   938 W Binder_2: type=1400 audit(0.0:103): avc: denied { ioctl } for path="socket:[33916]" dev="sockfs" ino=33916 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-21 16:24:48.324   938   938 W Binder_2: type=1400 audit(0.0:104): avc: denied { ioctl } for path="socket:[33916]" dev="sockfs" ino=33916 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-21 16:24:48.326  5653  5677 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,11-21 16:24:48.349  5653  5690 I OpenGLRenderer: Initialized EGL, version 1.4
,11-21 16:24:48.433   927   945 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +452ms
,11-21 16:24:48.427   938   938 W Binder_2: type=1400 audit(0.0:105): avc: denied { ioctl } for path="socket:[30573]" dev="sockfs" ino=30573 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-21 16:24:48.427   938   938 W Binder_2: type=1400 audit(0.0:106): avc: denied { ioctl } for path="socket:[30573]" dev="sockfs" ino=30573 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-21 16:24:48.431  3933  3933 W Binder_8: type=1400 audit(0.0:107): avc: denied { ioctl } for path="socket:[30572]" dev="sockfs" ino=30572 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-21 16:24:48.431  3933  3933 W Binder_8: type=1400 audit(0.0:108): avc: denied { ioctl } for path="socket:[30572]" dev="sockfs" ino=30572 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
11-21 16:24:48.434  3721  3721 I Keyboard.Facilitator: onFinishInput()
,11-21 16:24:48.485  5653  5653 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 5653
,11-21 16:24:48.600  5653  5653 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,11-21 16:24:48.790   927  3933 I ActivityManager: Killing 5326:com.android.settings/1000 (adj 15): empty #17
,11-21 16:24:48.807   927  3933 I ActivityManager: Killing 5286:org.codeaurora.ims/1001 (adj 15): empty #18
,11-21 16:24:48.858  5653  5692 D jxcore_app_log: JniHelper::setJavaVM(0xf517c000), pthread_self() = -580912848
,11-21 16:24:48.869  5653  5692 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
11-21 16:24:48.869  5653  5692 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
11-21 16:24:48.869  5653  5692 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
11-21 16:24:48.869  5653  5692 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
11-21 16:24:48.869  5653  5692 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,11-21 16:24:48.869  5653  5692 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8c27e added. We now have 1 listener(s)
,11-21 16:24:48.874  5653  5692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 60:83:34:25:D7:D4
,11-21 16:24:48.875  5653  5692 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
,11-21 16:24:48.876  5653  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-21 16:24:48.876  5653  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,11-21 16:24:48.881  5653  5692 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
11-21 16:24:48.881  5653  5692 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
11-21 16:24:48.881  5653  5692 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
11-21 16:24:48.881  5653  5692 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 60:83:34:25:D7:D4
11-21 16:24:48.881  5653  5692 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
11-21 16:24:48.881  5653  5692 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
11-21 16:24:48.881  5653  5692 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
11-21 16:24:48.881  5653  5692 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
11-21 16:24:48.881  5653  5692 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
11-21 16:24:48.881  5653  5692 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
11-21 16:24:48.881  5653  5692 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
11-21 16:24:48.881  5653  5692 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
11-21 16:24:48.881  5653  5692 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
11-21 16:24:48.881  5653  5692 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,11-21 16:24:48.881  5653  5692 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@39032f5 added. We now have 1 listener(s)
11-21 16:24:48.881  5653  5692 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-21 16:24:48.886   927  3039 D WifiService: New client listening to asynchronous messages
,11-21 16:24:48.887  5653  5692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,11-21 16:24:48.887  5653  5692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
11-21 16:24:48.888  5653  5692 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[JavaBridge,5,main], id: 55
11-21 16:24:48.888  5653  5692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
,11-21 16:24:48.888  5653  5692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
11-21 16:24:48.888  5653  5692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,11-21 16:24:48.888  5653  5692 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[JavaBridge,5,main], id: 55
,11-21 16:24:48.891  5653  5692 I io.jxcore.node.LifeCycleMonitor: start: OK
,11-21 16:24:49.192  5653  5653 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,11-21 16:24:49.271   927  3043 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,11-21 16:24:49.503  5653  5662 I art     : Background sticky concurrent mark sweep GC freed 77980(7MB) AllocSpace objects, 16(1476KB) LOS objects, 26% free, 24MB/32MB, paused 3.009ms total 208.656ms
,11-21 16:24:49.904  5653  5701 W jxcore-log: Initializing JXcore engine
11-21 16:24:49.904  5653  5701 W jxcore-log: JXcore engine is ready
,11-21 16:24:49.931  5701  5701 W Thread-62: type=1400 audit(0.0:109): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=12966 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
11-21 16:24:49.931  5701  5701 W Thread-62: type=1400 audit(0.0:110): avc: denied { ioctl } for path="socket:[13859]" dev="sockfs" ino=13859 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
11-21 16:24:49.931  5701  5701 W Thread-62: type=1400 audit(0.0:111): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=5964 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
11-21 16:24:49.931  5701  5701 W Thread-62: type=1400 audit(0.0:112): avc: denied { ioctl } for path="socket:[32743]" dev="sockfs" ino=32743 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:untrusted_app:s0:c512,c768 tclass=netlink_route_socket permissive=0
,11-21 16:24:49.943  5653  5701 W jxcore-log: Starting JXcore engine
,11-21 16:24:50.004  5653  5701 W jxcore-log: Platform android
11-21 16:24:50.004  5653  5701 W jxcore-log: 
11-21 16:24:50.004  5653  5701 W jxcore-log: Process ARCH arm
11-21 16:24:50.004  5653  5701 W jxcore-log: 
,11-21 16:24:50.151  5653  5701 I jxcore-log: JXcore Cordova bridge is ready!
11-21 16:24:50.151  5653  5701 I jxcore-log: 
,11-21 16:24:50.151  5653  5701 W jxcore-log: JXcore engine is started
,11-21 16:24:50.159  5653  5692 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,11-21 16:24:50.166  5653  5653 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,11-21 16:24:53.464   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-21 16:24:54.465   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-21 16:24:55.466   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-21 16:24:56.467   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-21 16:24:57.469   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-21 16:24:58.338   927  3043 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,11-21 16:24:58.470   537   537 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,11-21 16:24:59.923  5653  5701 I jxcore-log: 2016-11-21 15:24:59 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
11-21 16:24:59.923  5653  5701 I jxcore-log: 
,11-21 16:24:59.924  5653  5701 I jxcore-log: 2016-11-21 15:24:59 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
11-21 16:24:59.924  5653  5701 I jxcore-log: 
,11-21 16:24:59.925  5653  5701 I jxcore-log: 2016-11-21 15:24:59 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
11-21 16:24:59.925  5653  5701 I jxcore-log: 
,11-21 16:24:59.930  5653  5701 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
11-21 16:24:59.930  5653  5701 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-21 16:24:59.930  5653  5701 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-21 16:24:59.930  5653  5701 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-21 16:24:59.930  5653  5701 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-21 16:24:59.930  5653  5701 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-21 16:24:59.930  5653  5701 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-21 16:24:59.930  5653  5701 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-21 16:24:59.930  5653  5701 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-21 16:24:59.930  5653  5701 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,11-21 16:24:59.932  5653  5701 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
,11-21 16:24:59.935  5653  5701 I jxcore-log: 2016-11-21 15:24:59 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
11-21 16:24:59.935  5653  5701 I jxcore-log: 
,11-21 16:24:59.937  5653  5701 I jxcore-log: 2016-11-21 15:24:59 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
11-21 16:24:59.937  5653  5701 I jxcore-log: 
11-21 16:24:59.938  5653  5701 I jxcore-log: 2016-11-21 15:24:59 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
11-21 16:24:59.938  5653  5701 I jxcore-log: 
,11-21 16:25:00.189  5653  5701 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,11-21 16:25:00.190  5653  5701 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@72dd9df added. We now have 2 listener(s)
11-21 16:25:00.190  5653  5701 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-21 16:25:00.190  5653  5701 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,11-21 16:25:00.191  5653  5701 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-21 16:25:00.191  5653  5701 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-21 16:25:00.191  5653  5701 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@861e62c added. We now have 2 listener(s)
11-21 16:25:00.191  5653  5701 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-21 16:25:00.191  5653  5701 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
11-21 16:25:00.193  5653  5701 D ExecuteNativeTests: Running unit tests
11-21 16:25:00.193  5653  5701 D BluetoothAdapter: enable(): BT is already enabled..!
11-21 16:25:00.194   927  3224 D WifiService: setWifiEnabled: true pid=5653, uid=10077
11-21 16:25:00.194   927  3224 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-21 16:25:04.401   927  3043 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,11-21 16:25:04.598  4028  5705 I EventLogService: Aggregate from 1479740104187 (log), 1479740104187 (data)
,11-21 16:25:04.721   927  3039 D WifiService: New client listening to asynchronous messages
,11-21 16:25:04.726  4012  5703 W CronetSyncConnectionRcs: Upload content type not set.
,11-21 16:25:04.733  3647  5710 I VacuumService: Vacuum at: now=1479741904733 tag=VacuumService
,11-21 16:25:04.757  3647  5718 D GetConfigurationSnapshotOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,11-21 16:25:04.790  3647  5711 I PhenotypeFlagCommitter: Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,11-21 16:25:04.793  3647  5711 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,11-21 16:25:04.823  3647  5711 W Uploader:  no longer exists, so no auth token.
,11-21 16:25:04.829  3647  5718 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,11-21 16:25:05.241  3647  5711 W Uploader:  no longer exists, so no auth token.
,11-21 16:25:05.254  3647  5723 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,11-21 16:25:05.340  3647  5718 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,11-21 16:25:05.458  3647  5723 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,11-21 16:25:05.552  3647  5718 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,11-21 16:25:07.424   927  3043 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,11-21 16:25:09.790   927  5416 D NetlinkSocketObserver: NeighborEvent{elapsedMs=179144, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,11-21 16:25:10.199  5653  5701 I com.test.thalitest.ThaliTestRunner: Running UT
,11-21 16:25:10.266  5653  5701 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,11-21 16:25:10.266  5653  5701 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fd12119 added. We now have 3 listener(s)
,11-21 16:25:10.267  5653  5701 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
,11-21 16:25:10.267  5653  5701 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,11-21 16:25:10.267  5653  5701 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-21 16:25:10.267  5653  5701 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,11-21 16:25:10.267  5653  5701 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@676e5de added. We now have 3 listener(s)
,11-21 16:25:10.268  5653  5701 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-21 16:25:10.269  5653  5701 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,11-21 16:25:10.274  5653  5701 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnConnectionTimeout
11-21 16:25:10.274  5653  5701 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
11-21 16:25:10.274  5653  5701 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-21 16:25:10.274  5653  5701 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-21 16:25:10.274  5653  5701 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-21 16:25:10.276  5653  5701 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
,11-21 16:25:10.276  5653  5701 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
11-21 16:25:10.276  5653  5701 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
11-21 16:25:10.276  5653  5701 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-21 16:25:10.276  5653  5701 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-21 16:25:10.276  5653  5701 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-21 16:25:10.278  5653  5701 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnBluetoothMacAddressResolved
11-21 16:25:10.279  5653  5701 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
11-21 16:25:10.280  5653  5701 I io.jxcore.node.ConnectionHelperTest: Starting test: testHasMaximumNumberOfConnections
11-21 16:25:10.282  5653  5701 I io.jxcore.node.ConnectionHelperTest: Starting test: testStart
11-21 16:25:10.282  5653  5701 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
11-21 16:25:10.284  5653  5701 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-21 16:25:10.285  5653  5701 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
,11-21 16:25:10.291  5653  5701 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-21 16:25:10.291  5653  5701 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-21 16:25:10.291  5653  5701 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-21 16:25:10.291  5653  5701 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-21 16:25:10.291  5653  5701 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-21 16:25:10.291  5653  5701 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-21 16:25:10.291  5653  5701 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-21 16:25:10.291  5653  5701 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-21 16:25:10.291  5653  5701 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
11-21 16:25:10.291  5653  5701 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
11-21 16:25:10.291  5653  5701 D io.jxcore.node.ConnectivityMonitor: start: OK
11-21 16:25:10.292  5653  5701 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 1
11-21 16:25:10.292  5653  5701 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 0 -> 1
11-21 16:25:10.292  5653  5701 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-62,5,main], id: 62
11-21 16:25:10.292  5653  5701 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-62,5,main], id: 62
11-21 16:25:10.292  5653  5701 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-62,5,main], id: 62
11-21 16:25:10.292  5653  5701 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
11-21 16:25:10.292  5653  5701 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
11-21 16:25:10.292  5653  5701 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
11-21 16:25:10.292  5653  5701 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,11-21 16:25:10.293  5653  5701 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
11-21 16:25:10.293  5653  5701 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,11-21 16:25:10.293  5653  5701 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
11-21 16:25:10.293  5653  5701 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
11-21 16:25:10.294  5653  5701 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
11-21 16:25:10.294  5653  5701 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
11-21 16:25:10.294  5653  5701 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-21 16:25:10.294  5653  5728 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
11-21 16:25:10.294  5653  5701 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,11-21 16:25:10.298  5653  5653 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-21 16:25:10.299  5653  5728 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-21 16:25:10.300  5653  5701 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-21 16:25:10.300  5653  5701 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,11-21 16:25:10.300  5653  5701 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,11-21 16:25:10.301  5653  5728 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,11-21 16:25:10.297  4941  4941 W Binder_4: type=1400 audit(0.0:113): avc: denied { ioctl } for path="socket:[32909]" dev="sockfs" ino=32909 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-21 16:25:10.297  4941  4941 W Binder_4: type=1400 audit(0.0:114): avc: denied { ioctl } for path="socket:[32909]" dev="sockfs" ino=32909 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,11-21 16:25:10.305  5653  5653 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-21 16:25:10.306  5653  5653 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
11-21 16:25:10.306  5653  5701 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-62,5,main], id: 62
11-21 16:25:10.306  5653  5701 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-21 16:25:10.307  5653  5701 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-21 16:25:10.308  5653  5701 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-21 16:25:10.308  5653  5701 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 1
,11-21 16:25:10.308  5653  5701 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Current thread: Thread[Thread-62,5,main], id: 62
,11-21 16:25:10.309  5653  5701 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-62,5,main], id: 62
,11-21 16:25:10.309  5653  5701 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
,11-21 16:25:10.309  5653  5701 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: createAdvertiseDataToServiceData 
11-21 16:25:10.309  5653  5701 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-21 16:25:10.309  5653  5701 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 01 60 83 34 25 D7 D4
,11-21 16:25:10.309  5653  5701 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-21 16:25:10.309  5653  5701 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: created AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-21 16:25:10.309  5653  5701 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: Current thread: Thread[Thread-62,5,main], id: 62
,11-21 16:25:10.309  5653  5701 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: was started = false
11-21 16:25:10.309  5653  5701 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: advertiseData = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-21 16:25:10.310  5653  5701 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData finished: Current thread: Thread[Thread-62,5,main], id: 62
11-21 16:25:10.310  5653  5701 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = NOT_STARTEDCurrent thread: Thread[Thread-62,5,main], id: 62
,11-21 16:25:10.310  5653  5701 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... adv data = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]Current thread: Thread[Thread-62,5,main], id: 62
11-21 16:25:10.310  5653  5701 D BluetoothAdapter: STATE_ON
11-21 16:25:10.312  4709  4941 D BtGatt.GattService: registerClient() - UUID=b1ae8543-5c9f-4e43-bb6a-2c127a1b1058
,11-21 16:25:10.313  4709  4781 D BtGatt.GattService: onClientRegistered() - UUID=b1ae8543-5c9f-4e43-bb6a-2c127a1b1058, clientIf=5
,11-21 16:25:10.314  5653  5664 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
,11-21 16:25:10.316  4709  4783 D BtGatt.AdvertiseManager: message : 0
,11-21 16:25:10.318  4709  4783 D BtGatt.AdvertiseManager: starting multi advertising
,11-21 16:25:10.331  4709  4781 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,11-21 16:25:10.337  4709  4781 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,11-21 16:25:10.338  5653  5701 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment Current thread: Thread[Thread-62,5,main], id: 62
,11-21 16:25:10.338  5653  5701 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTINGCurrent thread: Thread[Thread-62,5,main], id: 62
11-21 16:25:10.338  5653  5701 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
11-21 16:25:10.338  5653  5701 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged default (no call to listener). Current thread: Thread[Thread-62,5,main], id: 62
11-21 16:25:10.338  5653  5701 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-62,5,main], id: 62
11-21 16:25:10.338  5653  5701 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[Thread-62,5,main], id: 62
11-21 16:25:10.338  5653  5701 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[Thread-62,5,main], id: 62
11-21 16:25:10.338  5653  5701 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser started = true Current thread: Thread[Thread-62,5,main], id: 62
11-21 16:25:10.338  5653  5701 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-21 16:25:10.339  5653  5701 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-21 16:25:10.339  5653  5701 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-21 16:25:10.340  5653  5701 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
,11-21 16:25:10.340  5653  5701 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-21 16:25:10.340  5653  5701 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-21 16:25:10.340  5653  5701 I io.jxcore.node.ConnectionHelper: start: OK
11-21 16:25:10.340  5653  5653 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
11-21 16:25:10.341  5653  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess : Current thread: Thread[main,5,main], id: 1
11-21 16:25:10.341  5653  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNINGCurrent thread: Thread[main,5,main], id: 1
11-21 16:25:10.341  5653  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
11-21 16:25:10.341  5653  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  true. Current thread: Thread[main,5,main], id: 1
11-21 16:25:10.341  5653  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[main,5,main], id: 1
11-21 16:25:10.341  5653  5653 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-21 16:25:10.341  5653  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-21 16:25:10.341  5653  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [ADVERTISING]
11-21 16:25:10.341  5653  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-21 16:25:10.342  5653  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-21 16:25:10.342  5653  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]Current thread: Thread[main,5,main], id: 1
11-21 16:25:10.342  5653  5653 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
11-21 16:25:10.342  5653  5653 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-21 16:25:10.344  5653  5653 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-21 16:25:10.345  5653  5653 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
11-21 16:25:10.345  5653  5653 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-21 16:25:10.345  5653  5653 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-21 16:25:10.345  5653  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-21 16:25:10.345  5653  5653 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,11-21 16:25:10.464   927  3043 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,11-21 16:25:10.843  5653  5701 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-21 16:25:10.843  5653  5701 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
11-21 16:25:10.843  5653  5701 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
11-21 16:25:10.843  5653  5701 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
11-21 16:25:10.844  5653  5701 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
,11-21 16:25:10.844  5653  5701 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
,11-21 16:25:10.844  5653  5701 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
11-21 16:25:10.844  5653  5701 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
11-21 16:25:10.844  5653  5701 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
,11-21 16:25:10.844  5653  5701 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
11-21 16:25:10.844  5653  5701 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
11-21 16:25:10.844  5653  5701 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
11-21 16:25:10.844  5653  5701 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
11-21 16:25:10.844  5653  5701 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
,11-21 16:25:10.845  5653  5701 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
11-21 16:25:10.845  5653  5701 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
11-21 16:25:10.845  5653  5701 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
11-21 16:25:10.845  5653  5701 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
,11-21 16:25:10.845  5653  5701 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
11-21 16:25:10.845  5653  5701 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
11-21 16:25:10.845  5653  5701 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
11-21 16:25:10.845  5653  5701 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
11-21 16:25:10.845  5653  5701 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
11-21 16:25:10.846  5653  5701 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
11-21 16:25:10.846  5653  5701 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
11-21 16:25:10.846  5653  5701 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
11-21 16:25:10.846  5653  5701 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
11-21 16:25:10.846  5653  5701 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
,11-21 16:25:10.846  5653  5701 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
11-21 16:25:10.846  5653  5701 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
11-21 16:25:10.847  5653  5701 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
11-21 16:25:10.847  5653  5653 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
11-21 16:25:10.847  5653  5701 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
,11-21 16:25:10.847  5653  5701 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
11-21 16:25:10.847  5653  5701 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
11-21 16:25:10.847  5653  5701 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
11-21 16:25:10.847  5653  5701 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
,11-21 16:25:10.848  5653  5701 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
11-21 16:25:10.848  5653  5701 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
11-21 16:25:10.848  5653  5701 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,11-21 16:25:10.848  5653  5701 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
11-21 16:25:10.848  5653  5701 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
11-21 16:25:10.849  5653  5701 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
11-21 16:25:10.849  5653  5701 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,11-21 16:25:10.849  5653  5701 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
11-21 16:25:10.849  5653  5701 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-21 16:25:10.849  5653  5728 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
11-21 16:25:10.849  5653  5728 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
11-21 16:25:10.850  5653  5701 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-62,5,main], id: 62
,11-21 16:25:10.850  5653  5728 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
11-21 16:25:10.850  5653  5701 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-62,5,main], id: 62
11-21 16:25:10.850  5653  5701 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-62,5,main], id: 62
11-21 16:25:10.850  5653  5701 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-62,5,main], id: 62
11-21 16:25:10.852  5653  5701 D BluetoothAdapter: STATE_ON
,11-21 16:25:10.852  5653  5701 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-21 16:25:10.854  5653  5701 D BluetoothAdapter: STATE_ON
11-21 16:25:10.854  5653  5701 D BluetoothLeScanner: could not find callback wrapper
11-21 16:25:10.854  5653  5701 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-21 16:25:10.855  5653  5701 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-62,5,main], id: 62
11-21 16:25:10.855  5653  5701 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-62,5,main], id: 62
,11-21 16:25:10.855  5653  5701 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-62,5,main], id: 62
11-21 16:25:10.856  5653  5701 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
11-21 16:25:10.856  5653  5701 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-62,5,main], id: 62
11-21 16:25:10.858  4709  4783 D BtGatt.AdvertiseManager: message : 1
11-21 16:25:10.859  4709  4783 D BtGatt.AdvertiseManager: stop advertise for client 5
,11-21 16:25:10.874  4709  4781 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
,11-21 16:25:10.874  4709  4781 D BtGatt.GattService: Client app is not null!
11-21 16:25:10.875  4709  4939 D BtGatt.GattService: unregisterClient() - clientIf=5
11-21 16:25:10.876  5653  5701 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,11-21 16:25:10.877  5653  5701 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTEDCurrent thread: Thread[Thread-62,5,main], id: 62
11-21 16:25:10.877  5653  5701 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
11-21 16:25:10.877  5653  5701 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  false. Current thread: Thread[Thread-62,5,main], id: 62
11-21 16:25:10.877  5653  5701 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-62,5,main], id: 62
11-21 16:25:10.877  5653  5701 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-62,5,main], id: 62
11-21 16:25:10.877  5653  5701 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,11-21 16:25:10.878  5653  5701 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,11-21 16:25:10.879  5653  5701 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-21 16:25:10.879  5653  5701 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-21 16:25:10.881  5653  5701 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-21 16:25:10.881  5653  5701 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-21 16:25:10.881  5653  5701 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-21 16:25:10.881  5653  5701 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
,11-21 16:25:10.881  5653  5653 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-21 16:25:10.882  5653  5653 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
11-21 16:25:10.883  5653  5653 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
11-21 16:25:10.883  5653  5653 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-21 16:25:10.883  5653  5653 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-21 16:25:10.883  5653  5653 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
11-21 16:25:10.884  5653  5653 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-21 16:25:10.884  5653  5653 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-21 16:25:10.884  5653  5701 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
11-21 16:25:10.884  5653  5701 V io.jxcore.node.ConnectivityMonitor: start: Already started
11-21 16:25:10.884  5653  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
,11-21 16:25:10.884  5653  5701 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 2
11-21 16:25:10.884  5653  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-21 16:25:10.884  5653  5701 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 1 -> 2
11-21 16:25:10.884  5653  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [ADVERTISING]
11-21 16:25:10.884  5653  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-21 16:25:10.884  5653  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-21 16:25:10.884  5653  5701 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-62,5,main], id: 62
11-21 16:25:10.884  5653  5653 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
11-21 16:25:10.884  5653  5701 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-62,5,main], id: 62
11-21 16:25:10.884  5653  5653 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-21 16:25:10.884  5653  5701 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-62,5,main], id: 62
11-21 16:25:10.885  5653  5701 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
11-21 16:25:10.885  5653  5701 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
11-21 16:25:10.885  5653  5701 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
11-21 16:25:10.885  5653  5701 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-21 16:25:10.886  5653  5653 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-21 16:25:10.886  5653  5653 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-21 16:25:10.887  5653  5653 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-21 16:25:10.887  5653  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-21 16:25:10.887  5653  5653 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-21 16:25:10.892  5653  5701 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
11-21 16:25:10.892  5653  5701 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
11-21 16:25:10.893  5653  5701 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
11-21 16:25:10.893  5653  5701 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
11-21 16:25:10.893  5653  5701 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
11-21 16:25:10.893  5653  5653 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
11-21 16:25:10.893  5653  5701 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start dis,covery: false, start advertiser: true
11-21 16:25:10.893  5653  5731 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
11-21 16:25:10.893  5653  5701 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-21 16:25:10.894  5653  5701 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
11-21 16:25:10.896  5653  5731 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-21 16:25:10.897  4939  4939 W Binder_3: type=1400 audit(0.0:115): avc: denied { ioctl } for path="socket:[30607]" dev="sockfs" ino=30607 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-21 16:25:10.897  4939  4939 W Binder_3: type=1400 audit(0.0:116): avc: denied { ioctl } for path="socket:[30607]" dev="sockfs" ino=30607 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-21 16:25:10.899  5653  5731 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
11-21 16:25:10.901  5653  5701 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-21 16:25:10.901  5653  5701 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-21 16:25:10.901  5653  5701 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
11-21 16:25:10.905  5653  5701 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-62,5,main], id: 62
11-21 16:25:10.905  5653  5701 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-21 16:25:10.906  5653  5701 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-21 16:25:10.906  5653  5701 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-21 16:25:10.906  5653  5701 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 2
11-21 16:25:10.908  5653  5701 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Current thread: Thread[Thread-62,5,main], id: 62
11-21 16:25:10.909  5653  5701 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-62,5,main], id: 62
11-21 16:25:10.909  5653  5701 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
11-21 16:25:10.909  5653  5701 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: createAdvertiseDataToServiceData 
11-21 16:25:10.909  5653  5701 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-21 16:25:10.909  5653  5701 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 02 60 83 34 25 D7 D4
11-21 16:25:10.909  5653  5701 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[2, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-21 16:25:10.909  5653  5701 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: created AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[2, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-21 16:25:10.909  5653  5701 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: Current thread: Thread[Thread-62,5,main], id: 62
11-21 16:25:10.909  5653  5701 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: was started = false
11-21 16:25:10.910  5653  5701 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: advertiseData = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[2, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-21 16:25:10.910  5653  5701 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData finished: Current thread: Thread[Thread-62,5,main], id: 62
11-21 16:25:10.910  5653  5701 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = NOT_STARTEDCurrent thread: Thread[Thread-62,5,main], id: 62
11-21 16:25:10.910  5653  5701 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... adv data = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[2, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]Current thread: Thread[Thread-62,5,main], id: 62
11-21 16:25:10.911  5653  5701 D BluetoothAdapter: STATE_ON
11-21 16:25:10.913  4709  4939 D BtGatt.GattService: registerClient() - UUID=683a1600-b8f9-4c7e-b404-27a2c4cfd15c
11-21 16:25:10.914  4709  4781 D BtGatt.GattService: onClientRegistered() - UUID=683a1600-b8f9-4c7e-b404-27a2c4cfd15c, clientIf=5
11-21 16:25:10.914  5653  5663 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
11-21 16:25:10.916  4709  4783 D BtGatt.AdvertiseManager: message : 0
11-21 16:25:10.918  4709  4783 D BtGatt.AdvertiseManager: starting multi advertising
11-21 16:25:10.931  4709  4781 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,11-21 16:25:10.939  4709  4781 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
11-21 16:25:10.940  5653  5701 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment Current thread: Thread[Thread-62,5,main], id: 62
11-21 16:25:10.940  5653  5701 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTINGCurrent thread: Thread[Thread-62,5,main], id: 62
11-21 16:25:10.940  5653  5701 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
11-21 16:25:10.940  5653  5701 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged default (no call to listener). Current thread: Thread[Thread-62,5,main], id: 62
11-21 16:25:10.940  5653  5701 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-62,5,main], id: 62
11-21 16:25:10.940  5653  5701 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[Thread-62,5,main], id: 62
11-21 16:25:10.940  5653  5701 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[Thread-62,5,main], id: 62
11-21 16:25:10.940  5653  5701 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser started = true Current thread: Thread[Thread-62,5,main], id: 62
11-21 16:25:10.940  5653  5701 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-21 16:25:10.942  5653  5701 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-21 16:25:10.942  5653  5701 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-21 16:25:10.943  5653  5701 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-21 16:25:10.943  5653  5701 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-21 16:25:10.944  5653  5701 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-21 16:25:10.944  5653  5701 I io.jxcore.node.ConnectionHelper: start: OK
11-21 16:25:10.944  5653  5653 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
11-21 16:25:10.944  5653  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess : Current thread: Thread[main,5,main], id: 1
11-21 16:25:10.944  5653  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNINGCurrent thread: Thread[main,5,main], id: 1
11-21 16:25:10.944  5653  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
11-21 16:25:10.944  5653  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  true. Current thread: Thread[main,5,main], id: 1
11-21 16:25:10.944  5653  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[main,5,main], id: 1
11-21 16:25:10.944  5653  5653 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-21 16:25:10.945  5653  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-21 16:25:10.945  5653  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [ADVERTISING]
11-21 16:25:10.945  5653  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-21 16:25:10.945  5653  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-21 16:25:10.945  5653  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]Current thread: Thread[main,5,main], id: 1
11-21 16:25:10.945  5653  5653 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
11-21 16:25:10.945  5653  5653 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-21 16:25:10.948  5653  5653 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-21 16:25:10.948  5653  5653 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
11-21 16:25:10.949  5653  5653 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-21 16:25:10.949  5653  5653 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-21 16:25:10.949  5653  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-21 16:25:10.949  5653  5653 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,11-21 16:25:11.321   927  3029 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-21 16:25:11.448  5653  5701 I io.jxcore.node.ConnectionHelperTest: Starting test: testStop
11-21 16:25:11.449  5653  5701 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
,11-21 16:25:11.449  5653  5701 V io.jxcore.node.ConnectivityMonitor: start: Already started
11-21 16:25:11.449  5653  5701 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
11-21 16:25:11.449  5653  5701 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 3
11-21 16:25:11.449  5653  5701 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 2 -> 3
11-21 16:25:11.450  5653  5701 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-62,5,main], id: 62
11-21 16:25:11.450  5653  5653 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
11-21 16:25:11.450  5653  5701 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-62,5,main], id: 62
,11-21 16:25:11.450  5653  5701 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-62,5,main], id: 62
11-21 16:25:11.452  5653  5701 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
11-21 16:25:11.452  5653  5701 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Manufacturer ID: 7413
11-21 16:25:11.452  5653  5701 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad length and type: 533
11-21 16:25:11.452  5653  5701 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad extra information: 3
11-21 16:25:11.452  5653  5701 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
11-21 16:25:11.452  5653  5701 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 2
11-21 16:25:11.452  5653  5701 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 3
11-21 16:25:11.452  5653  5701 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 2
11-21 16:25:11.452  5653  5701 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
11-21 16:25:11.452  5653  5701 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Current thread: Thread[Thread-62,5,main], id: 62
11-21 16:25:11.453  5653  5701 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 3
,11-21 16:25:11.454  5653  5701 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: advertiserWasStarted true Current thread: Thread[Thread-62,5,main], id: 62
11-21 16:25:11.454  5653  5701 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: stop advertiser Current thread: Thread[Thread-62,5,main], id: 62
11-21 16:25:11.454  5653  5701 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-62,5,main], id: 62
,11-21 16:25:11.457  4709  4783 D BtGatt.AdvertiseManager: message : 1
,11-21 16:25:11.458  4709  4783 D BtGatt.AdvertiseManager: stop advertise for client 5
,11-21 16:25:11.476  4709  4781 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
,11-21 16:25:11.476  4709  4781 D BtGatt.GattService: Client app is not null!
,11-21 16:25:11.479  4709  4728 D BtGatt.GattService: unregisterClient() - clientIf=5
,11-21 16:25:11.480  5653  5701 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,11-21 16:25:11.480  5653  5701 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTEDCurrent thread: Thread[Thread-62,5,main], id: 62
11-21 16:25:11.480  5653  5701 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
11-21 16:25:11.480  5653  5701 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-62,5,main], id: 62
11-21 16:25:11.481  5653  5701 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-62,5,main], id: 62
,11-21 16:25:11.481  5653  5701 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-62,5,main], id: 62
11-21 16:25:11.481  5653  5701 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-21 16:25:11.481  5653  5701 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: start advertiser Current thread: Thread[Thread-62,5,main], id: 62
11-21 16:25:11.481  5653  5701 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Current thread: Thread[Thread-62,5,main], id: 62
11-21 16:25:11.481  5653  5701 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-62,5,main], id: 62
,11-21 16:25:11.481  5653  5701 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
11-21 16:25:11.482  5653  5701 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: createAdvertiseDataToServiceData 
11-21 16:25:11.482  5653  5701 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-21 16:25:11.482  5653  5701 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 03 60 83 34 25 D7 D4
11-21 16:25:11.482  5653  5701 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[3, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,11-21 16:25:11.482  5653  5701 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: created AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[3, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-21 16:25:11.483  5653  5701 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: Current thread: Thread[Thread-62,5,main], id: 62
,11-21 16:25:11.483  5653  5701 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: was started = false
11-21 16:25:11.483  5653  5701 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: advertiseData = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[3, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,11-21 16:25:11.483  5653  5701 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData finished: Current thread: Thread[Thread-62,5,main], id: 62
11-21 16:25:11.483  5653  5701 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = NOT_STARTEDCurrent thread: Thread[Thread-62,5,main], id: 62
11-21 16:25:11.483  5653  5701 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... adv data = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[3, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]Current thread: Thread[Thread-62,5,main], id: 62
11-21 16:25:11.486  5653  5701 D BluetoothAdapter: STATE_ON
,11-21 16:25:11.493  4709  4941 D BtGatt.GattService: registerClient() - UUID=9069ccd9-30b9-407f-833b-74b8c6d7b52e
11-21 16:25:11.494  4709  4781 D BtGatt.GattService: onClientRegistered() - UUID=9069ccd9-30b9-407f-833b-74b8c6d7b52e, clientIf=5
11-21 16:25:11.494  5653  5664 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
,11-21 16:25:11.496  4709  4783 D BtGatt.AdvertiseManager: message : 0
,11-21 16:25:11.500  4709  4783 D BtGatt.AdvertiseManager: starting multi advertising
,11-21 16:25:11.515  4709  4781 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,11-21 16:25:11.524  4709  4781 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,11-21 16:25:11.525  5653  5701 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment Current thread: Thread[Thread-62,5,main], id: 62
11-21 16:25:11.525  5653  5701 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTINGCurrent thread: Thread[Thread-62,5,main], id: 62
11-21 16:25:11.525  5653  5701 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,11-21 16:25:11.526  5653  5701 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged default (no call to listener). Current thread: Thread[Thread-62,5,main], id: 62
11-21 16:25:11.526  5653  5701 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-62,5,main], id: 62
11-21 16:25:11.526  5653  5701 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[Thread-62,5,main], id: 62
11-21 16:25:11.526  5653  5701 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[Thread-62,5,main], id: 62
,11-21 16:25:11.526  5653  5701 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser started = true Current thread: Thread[Thread-62,5,main], id: 62
11-21 16:25:11.526  5653  5701 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: start advertiser started = true Current thread: Thread[Thread-62,5,main], id: 62
,11-21 16:25:11.526  5653  5701 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-21 16:25:11.526  5653  5701 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: scannerWasStarted false Current thread: Thread[Thread-62,5,main], id: 62
11-21 16:25:11.526  5653  5701 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-21 16:25:11.527  5653  5701 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
,11-21 16:25:11.527  5653  5701 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-21 16:25:11.527  5653  5701 I io.jxcore.node.ConnectionHelper: start: OK
11-21 16:25:11.527  5653  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess : Current thread: Thread[main,5,main], id: 1
,11-21 16:25:11.527  5653  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNINGCurrent thread: Thread[main,5,main], id: 1
11-21 16:25:11.527  5653  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
11-21 16:25:11.527  5653  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  true. Current thread: Thread[main,5,main], id: 1
11-21 16:25:11.527  5653  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[main,5,main], id: 1
11-21 16:25:11.528  5653  5653 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
,11-21 16:25:11.528  5653  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-21 16:25:11.528  5653  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [ADVERTISING]
11-21 16:25:11.528  5653  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [ADVERTISING]
11-21 16:25:11.528  5653  5701 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-21 16:25:11.528  5653  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-21 16:25:11.528  5653  5701 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
11-21 16:25:11.528  5653  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-21 16:25:11.528  5653  5701 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
11-21 16:25:11.528  5653  5701 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
11-21 16:25:11.528  5653  5701 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
,11-21 16:25:11.528  5653  5701 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
11-21 16:25:11.528  5653  5701 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-21 16:25:11.529  5653  5701 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
11-21 16:25:11.529  5653  5701 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
11-21 16:25:11.529  5653  5701 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
11-21 16:25:11.529  5653  5731 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
11-21 16:25:11.529  5653  5701 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-21 16:25:11.529  5653  5653 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
11-21 16:25:11.529  5653  5701 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
11-21 16:25:11.529  5653  5731 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
,11-21 16:25:11.529  5653  5701 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-21 16:25:11.529  5653  5731 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
11-21 16:25:11.529  5653  5701 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-62,5,main], id: 62
11-21 16:25:11.529  5653  5701 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-62,5,main], id: 62
11-21 16:25:11.529  5653  5701 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-62,5,main], id: 62
11-21 16:25:11.529  5653  5701 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-62,5,main], id: 62
11-21 16:25:11.530  5653  5701 D BluetoothAdapter: STATE_ON
11-21 16:25:11.530  5653  5701 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-21 16:25:11.531  5653  5701 D BluetoothAdapter: STATE_ON
,11-21 16:25:11.531  5653  5701 D BluetoothLeScanner: could not find callback wrapper
11-21 16:25:11.531  5653  5701 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-21 16:25:11.531  5653  5701 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-62,5,main], id: 62
11-21 16:25:11.531  5653  5701 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-62,5,main], id: 62
11-21 16:25:11.531  5653  5701 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-62,5,main], id: 62
11-21 16:25:11.531  5653  5701 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
11-21 16:25:11.532  5653  5701 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-62,5,main], id: 62
11-21 16:25:11.533  4709  4783 D BtGatt.AdvertiseManager: message : 1
11-21 16:25:11.534  4709  4783 D BtGatt.AdvertiseManager: stop advertise for client 5
,11-21 16:25:11.542  4709  4781 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
,11-21 16:25:11.543  4709  4781 D BtGatt.GattService: Client app is not null!
11-21 16:25:11.543  4709  4728 D BtGatt.GattService: unregisterClient() - clientIf=5
,11-21 16:25:11.544  5653  5701 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-21 16:25:11.544  5653  5701 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTEDCurrent thread: Thread[Thread-62,5,main], id: 62
,11-21 16:25:11.544  5653  5701 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
11-21 16:25:11.544  5653  5701 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  false. Current thread: Thread[Thread-62,5,main], id: 62
11-21 16:25:11.544  5653  5701 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-62,5,main], id: 62
11-21 16:25:11.544  5653  5701 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-62,5,main], id: 62
11-21 16:25:11.544  5653  5701 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-21 16:25:11.544  5653  5701 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-21 16:25:11.545  5653  5701 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-21 16:25:11.545  5653  5701 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-21 16:25:11.546  5653  5701 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-21 16:25:11.547  5653  5701 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-21 16:25:11.547  5653  5701 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-21 16:25:11.547  5653  5701 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-21 16:25:11.547  5653  5653 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-21 16:25:11.547  5653  5653 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
11-21 16:25:11.547  5653  5653 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-21 16:25:11.547  5653  5653 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-21 16:25:11.547  5653  5653 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
11-21 16:25:11.547  5653  5653 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-21 16:25:11.547  5653  5653 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-21 16:25:11.548  5653  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-21 16:25:11.548  5653  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-21 16:25:11.548  5653  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [ADVERTISING]
11-21 16:25:11.548  5653  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-21 16:25:11.548  5653  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-21 16:25:11.548  5653  5653 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
11-21 16:25:11.548  5653  5653 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-21 16:25:11.550  5653  5701 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnPeerReadyToProvideBluetoothMacAddress
11-21 16:25:11.550  5653  5701 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
11-21 16:25:11.551  5653  5701 I io.jxcore.node.ConnectionHelperTest: Starting test: testKillAllConnections
11-21 16:25:11.552  5653  5653 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-21 16:25:11.553  5653  5653 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-21 16:25:11.553  5653  5653 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-21 16:25:11.553  5653  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-21 16:25:11.553  5653  5653 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-21 16:25:11.553  5653  5701 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
11-21 16:25:11.554  5653  5701 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnConnectionManagerStateChanged
11-21 16:25:11.555  5653  5701 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
11-21 16:25:11.556  5653  5701 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnPermissionCheckRequired
11-21 16:25:11.556  5653  5701 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
11-21 16:25:11.556  5653  5701 I io.jxcore.node.ConnectionHelperTest: Starting test: testToggleBetweenSystemDecidedAndAlternativeInsecureRfcommPortNumber
11-21 16:25:11.556  5653  5701 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
11-21 16:25:11.557  5653  5701 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-21 16:25:11.557  5653  5701 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-21 16:25:11.557  5653  5701 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-21 16:25:11.557  5653  5701 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
11-21 16:25:11.557  5653  5701 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-21 16:25:11.557  5653  5701 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-21 16:25:11.557  5653  5701 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-21 16:25:11.557  5653  5701 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
11-21 16:25:11.557  5653  5701 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-21 16:25:11.557  5653  5701 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-21 16:25:11.557  5653  5701 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,11-21 16:25:11.558  5653  5701 I io.jxcore.node.ConnectionHelperTest: Starting test: testConnect
,11-21 16:25:11.559  5653  5701 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
11-21 16:25:11.559  5653  5701 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
11-21 16:25:11.561  5653  5701 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnProvideBluetoothMacAddressRequest
11-21 16:25:11.562  5653  5701 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
11-21 16:25:11.563  5653  5701 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnDiscoveryManagerStateChanged
11-21 16:25:11.563  5653  5701 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
11-21 16:25:11.564  5653  5701 I io.jxcore.node.ConnectionHelperTest: Starting test: testDisconnectOutgoingConnection
11-21 16:25:11.564  5653  5701 E io.jxcore.node.ConnectionModel: addConnectionThread: A matching thread for outgoing connection already exists
11-21 16:25:11.564  5653  5701 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
11-21 16:25:11.564  5653  5701 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
11-21 16:25:11.564  5653  5701 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
11-21 16:25:11.564  5653  5701 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
11-21 16:25:11.564  5653  5701 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
11-21 16:25:11.564  5653  5701 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
,11-21 16:25:11.564  5653  5701 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
11-21 16:25:11.564  5653  5701 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
11-21 16:25:11.565  5653  5701 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
11-21 16:25:11.565  5653  5701 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
11-21 16:25:11.565  5653  5701 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
11-21 16:25:11.565  5653  5701 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
11-21 16:25:11.566  5653  5701 I io.jxcore.node.ConnectionHelperTest: Starting test: testDispose
11-21 16:25:11.566  5653  5701 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
11-21 16:25:11.566  5653  5701 V io.jxcore.node.ConnectivityMonitor: start: Already started
11-21 16:25:11.566  5653  5701 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 4
11-21 16:25:11.566  5653  5701 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 3 -> 4
11-21 16:25:11.566  5653  5701 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-62,5,main], id: 62
11-21 16:25:11.566  5653  5701 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-62,5,main], id: 62
11-21 16:25:11.566  5653  5701 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-62,5,main], id: 62
11-21 16:25:11.566  5653  5701 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
11-21 16:25:11.566  5653  5701 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
11-21 16:25:11.566  5653  5701 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
11-21 16:25:11.566  5653  5701 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-21 16:25:11.567  5653  5701 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
11-21 16:25:11.568  5653  5701 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
11-21 16:25:11.568  5653  5735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
11-21 16:25:11.568  5653  5701 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
11-21 16:25:11.569  5653  5701 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
,11-21 16:25:11.567  4728  4728 W Binder_1: type=1400 audit(0.0:117): avc: denied { ioctl } for path="socket:[30612]" dev="sockfs" ino=30612 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,11-21 16:25:11.569  5653  5735 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-21 16:25:11.569  5653  5701 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
11-21 16:25:11.569  5653  5701 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
11-21 16:25:11.569  5653  5701 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-21 16:25:11.569  5653  5701 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
11-21 16:25:11.570  5653  5653 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
11-21 16:25:11.572  5653  5735 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
11-21 16:25:11.571  4728  4728 W Binder_1: type=1400 audit(0.0:118): avc: denied { ioctl } for path="socket:[30612]" dev="sockfs" ino=30612 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,11-21 16:25:11.577  5653  5701 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
,11-21 16:25:11.577  5653  5701 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-21 16:25:11.577  5653  5701 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,11-21 16:25:11.583  5653  5701 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-62,5,main], id: 62
,11-21 16:25:11.583  5653  5701 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,11-21 16:25:11.584  5653  5701 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-21 16:25:11.584  5653  5701 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,11-21 16:25:11.584  5653  5701 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 4
,11-21 16:25:11.586  5653  5701 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Current thread: Thread[Thread-62,5,main], id: 62
11-21 16:25:11.586  5653  5701 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-62,5,main], id: 62
,11-21 16:25:11.586  5653  5701 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
11-21 16:25:11.586  5653  5701 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: createAdvertiseDataToServiceData 
11-21 16:25:11.586  5653  5701 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-21 16:25:11.587  5653  5701 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 04 60 83 34 25 D7 D4
11-21 16:25:11.587  5653  5701 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[4, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-21 16:25:11.587  5653  5701 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: created AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[4, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-21 16:25:11.587  5653  5701 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: Current thread: Thread[Thread-62,5,main], id: 62
,11-21 16:25:11.587  5653  5701 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: was started = false
11-21 16:25:11.587  5653  5701 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: advertiseData = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[4, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-21 16:25:11.587  5653  5701 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData finished: Current thread: Thread[Thread-62,5,main], id: 62
11-21 16:25:11.587  5653  5701 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = NOT_STARTEDCurrent thread: Thread[Thread-62,5,main], id: 62
11-21 16:25:11.587  5653  5701 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... adv data = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[4, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]Current thread: Thread[Thread-62,5,main], id: 62
11-21 16:25:11.588  5653  5701 D BluetoothAdapter: STATE_ON
11-21 16:25:11.590  4709  4728 D BtGatt.GattService: registerClient() - UUID=546300aa-9f36-4320-8f4e-66e4c6aa9b29
11-21 16:25:11.590  4709  4781 D BtGatt.GattService: onClientRegistered() - UUID=546300aa-9f36-4320-8f4e-66e4c6aa9b29, clientIf=5
11-21 16:25:11.590  5653  5664 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
11-21 16:25:11.591  4709  4783 D BtGatt.AdvertiseManager: message : 0
,11-21 16:25:11.594  4709  4783 D BtGatt.AdvertiseManager: starting multi advertising
,11-21 16:25:11.602  4709  4781 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,11-21 16:25:11.607  4709  4781 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,11-21 16:25:11.608  5653  5701 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment Current thread: Thread[Thread-62,5,main], id: 62
11-21 16:25:11.608  5653  5701 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTINGCurrent thread: Thread[Thread-62,5,main], id: 62
,11-21 16:25:11.608  5653  5701 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
11-21 16:25:11.608  5653  5701 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged default (no call to listener). Current thread: Thread[Thread-62,5,main], id: 62
11-21 16:25:11.608  5653  5701 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-62,5,main], id: 62
11-21 16:25:11.608  5653  5701 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[Thread-62,5,main], id: 62
11-21 16:25:11.608  5653  5701 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[Thread-62,5,main], id: 62
11-21 16:25:11.608  5653  5701 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser started = true Current thread: Thread[Thread-62,5,main], id: 62
11-21 16:25:11.608  5653  5701 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-21 16:25:11.609  5653  5701 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-21 16:25:11.609  5653  5701 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
,11-21 16:25:11.610  5653  5701 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-21 16:25:11.610  5653  5701 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-21 16:25:11.610  5653  5701 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-21 16:25:11.610  5653  5701 I io.jxcore.node.ConnectionHelper: start: OK
11-21 16:25:11.611  5653  5653 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
11-21 16:25:11.611  5653  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess : Current thread: Thread[main,5,main], id: 1
11-21 16:25:11.611  5653  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNINGCurrent thread: Thread[main,5,main], id: 1
11-21 16:25:11.611  5653  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
11-21 16:25:11.611  5653  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  true. Current thread: Thread[main,5,main], id: 1
11-21 16:25:11.611  5653  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[main,5,main], id: 1
11-21 16:25:11.611  5653  5653 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-21 16:25:11.611  5653  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
,11-21 16:25:11.611  5653  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [ADVERTISING]
11-21 16:25:11.611  5653  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-21 16:25:11.611  5653  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-21 16:25:11.611  5653  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]Current thread: Thread[main,5,main], id: 1
11-21 16:25:11.611  5653  5653 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
11-21 16:25:11.611  5653  5653 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
,11-21 16:25:11.614  5653  5653 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-21 16:25:11.614  5653  5653 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
11-21 16:25:11.614  5653  5653 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-21 16:25:11.614  5653  5653 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-21 16:25:11.614  5653  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-21 16:25:11.614  5653  5653 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,11-21 16:25:12.112  5653  5701 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,11-21 16:25:12.112  5653  5701 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
11-21 16:25:12.112  5653  5701 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
11-21 16:25:12.113  5653  5701 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
11-21 16:25:12.113  5653  5701 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-21 16:25:12.113  5653  5701 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
,11-21 16:25:12.113  5653  5701 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
11-21 16:25:12.113  5653  5735 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
11-21 16:25:12.114  5653  5701 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-21 16:25:12.114  5653  5735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
11-21 16:25:12.114  5653  5735 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
11-21 16:25:12.114  5653  5701 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fd12119 removed from the list
,11-21 16:25:12.114  5653  5701 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-21 16:25:12.114  5653  5701 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-21 16:25:12.114  5653  5701 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
11-21 16:25:12.114  5653  5701 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-21 16:25:12.115  5653  5701 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-62,5,main], id: 62
,11-21 16:25:12.115  5653  5653 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
11-21 16:25:12.116  5653  5653 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
11-21 16:25:12.116  5653  5653 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
11-21 16:25:12.116  5653  5653 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,11-21 16:25:12.115  5653  5701 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-62,5,main], id: 62
11-21 16:25:12.117  5653  5701 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-62,5,main], id: 62
11-21 16:25:12.117  5653  5701 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-62,5,main], id: 62
,11-21 16:25:12.119  5653  5701 D BluetoothAdapter: STATE_ON
11-21 16:25:12.119  5653  5701 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-21 16:25:12.121  5653  5701 D BluetoothAdapter: STATE_ON
11-21 16:25:12.121  5653  5701 D BluetoothLeScanner: could not find callback wrapper
11-21 16:25:12.121  5653  5701 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-21 16:25:12.121  5653  5701 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-62,5,main], id: 62
,11-21 16:25:12.122  5653  5701 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-62,5,main], id: 62
11-21 16:25:12.122  5653  5701 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-62,5,main], id: 62
11-21 16:25:12.122  5653  5701 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
11-21 16:25:12.122  5653  5701 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-62,5,main], id: 62
11-21 16:25:12.124  4709  4783 D BtGatt.AdvertiseManager: message : 1
11-21 16:25:12.125  4709  4783 D BtGatt.AdvertiseManager: stop advertise for client 5
,11-21 16:25:12.135  4709  4781 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
11-21 16:25:12.135  4709  4781 D BtGatt.GattService: Client app is not null!
,11-21 16:25:12.136  4709  4941 D BtGatt.GattService: unregisterClient() - clientIf=5
,11-21 16:25:12.137  5653  5701 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,11-21 16:25:12.137  5653  5701 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTEDCurrent thread: Thread[Thread-62,5,main], id: 62
11-21 16:25:12.137  5653  5701 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
11-21 16:25:12.137  5653  5701 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  false. Current thread: Thread[Thread-62,5,main], id: 62
11-21 16:25:12.137  5653  5701 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-62,5,main], id: 62
11-21 16:25:12.137  5653  5701 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-62,5,main], id: 62
11-21 16:25:12.137  5653  5701 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,11-21 16:25:12.138  5653  5701 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-21 16:25:12.138  5653  5701 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-21 16:25:12.138  5653  5701 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-21 16:25:12.140  5653  5701 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-21 16:25:12.140  5653  5701 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,11-21 16:25:12.140  5653  5701 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-21 16:25:12.140  5653  5701 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-21 16:25:12.140  5653  5701 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@676e5de removed from the list
11-21 16:25:12.140  5653  5653 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-21 16:25:12.140  5653  5701 D io.jxcore.node.ConnectivityMonitor: stop
,11-21 16:25:12.140  5653  5701 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
11-21 16:25:12.140  5653  5653 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-21 16:25:12.140  5653  5653 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-21 16:25:12.141  5653  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-21 16:25:12.141  5653  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-21 16:25:12.141  5653  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [ADVERTISING]
11-21 16:25:12.141  5653  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
,11-21 16:25:12.141  5653  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-21 16:25:12.141  5653  5653 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
11-21 16:25:12.141  5653  5653 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
,11-21 16:25:12.146  5653  5653 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
,11-21 16:25:12.146  5653  5653 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-21 16:25:12.146  5653  5653 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-21 16:25:12.146  5653  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-21 16:25:12.146  5653  5653 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,11-21 16:25:12.647  5653  5653 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-21 16:25:13.494   927  3043 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,11-21 16:25:17.144  5653  5701 I io.jxcore.node.ConnectionHelperTest: Starting test: testIsRunning
,11-21 16:25:17.149  5653  5701 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
11-21 16:25:17.149  5653  5701 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-21 16:25:17.150  5653  5701 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
,11-21 16:25:17.156  5653  5701 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,11-21 16:25:17.157  5653  5701 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
11-21 16:25:17.157  5653  5701 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
11-21 16:25:17.157  5653  5701 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
11-21 16:25:17.157  5653  5701 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
,11-21 16:25:17.158  5653  5701 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
11-21 16:25:17.158  5653  5653 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
11-21 16:25:17.158  5653  5736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
11-21 16:25:17.159  5653  5736 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-21 16:25:17.161  4728  4728 W Binder_1: type=1400 audit(0.0:119): avc: denied { ioctl } for path="socket:[32930]" dev="sockfs" ino=32930 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,11-21 16:25:17.161  4728  4728 W Binder_1: type=1400 audit(0.0:120): avc: denied { ioctl } for path="socket:[32930]" dev="sockfs" ino=32930 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-21 16:25:17.162  5653  5701 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnConnectionFailed
11-21 16:25:17.164  5653  5701 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
11-21 16:25:17.164  5653  5736 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
11-21 16:25:17.165  5653  5701 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
11-21 16:25:17.165  5653  5701 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
,11-21 16:25:17.165  5653  5701 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,11-21 16:25:17.166  5653  5701 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-21 16:25:17.167  5653  5701 I io.jxcore.node.ConnectionHelperTest: Starting test: testGetConnectivityMonitorGetDiscoveryManagerGetConnectionModelGetBluetoothName
,11-21 16:25:17.180  5653  5701 I io.jxcore.node.ConnectionHelperTest: Starting test: testConstructor
,11-21 16:25:17.181  5653  5701 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-21 16:25:17.181  5653  5701 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
11-21 16:25:17.181  5653  5701 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
,11-21 16:25:17.181  5653  5701 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
11-21 16:25:17.182  5653  5701 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
,11-21 16:25:17.182  5653  5736 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
11-21 16:25:17.182  5653  5736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
,11-21 16:25:17.182  5653  5736 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
11-21 16:25:17.183  5653  5653 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
11-21 16:25:17.184  5653  5701 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,11-21 16:25:17.184  5653  5701 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
,11-21 16:25:17.185  5653  5701 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fd12119 not in the list
11-21 16:25:17.185  5653  5653 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-21 16:25:17.185  5653  5701 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-21 16:25:17.185  5653  5653 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
,11-21 16:25:17.185  5653  5701 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-21 16:25:17.185  5653  5701 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
11-21 16:25:17.185  5653  5701 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-21 16:25:17.186  5653  5701 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
,11-21 16:25:17.191  5653  5701 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
,11-21 16:25:17.191  5653  5701 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-21 16:25:17.191  5653  5701 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-21 16:25:17.192  5653  5701 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-21 16:25:17.192  5653  5701 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@676e5de not in the list
11-21 16:25:17.192  5653  5701 D io.jxcore.node.ConnectivityMonitor: stop
,11-21 16:25:17.192  5653  5653 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-21 16:25:17.192  5653  5653 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-21 16:25:17.193  5653  5653 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,11-21 16:25:17.194  5653  5701 I io.jxcore.node.ConnectionModelTest: Starting test: testGetNumberOfCurrentOutgoingConnections
,11-21 16:25:17.195  5653  5701 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
11-21 16:25:17.196  5653  5701 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
11-21 16:25:17.197  5653  5701 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
11-21 16:25:17.197  5653  5701 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
11-21 16:25:17.198  5653  5701 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
,11-21 16:25:17.198  5653  5701 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,11-21 16:25:17.199  5653  5701 I io.jxcore.node.ConnectionModelTest: Starting test: constructorTest
,11-21 16:25:17.201  5653  5701 I io.jxcore.node.ConnectionModelTest: Starting test: testHasIncomingConnection
,11-21 16:25:17.204  5653  5701 I io.jxcore.node.ConnectionModelTest: Starting test: testGetNumberOfCurrentConnections
11-21 16:25:17.205  5653  5701 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
11-21 16:25:17.205  5653  5701 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
11-21 16:25:17.205  5653  5701 I io.jxcore.node.ConnectionModelTest: Starting test: testGetNumberOfCurrentIncomingConnections
11-21 16:25:17.206  5653  5701 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
11-21 16:25:17.206  5653  5701 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
11-21 16:25:17.206  5653  5701 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
11-21 16:25:17.206  5653  5701 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
11-21 16:25:17.206  5653  5701 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
11-21 16:25:17.206  5653  5701 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
11-21 16:25:17.207  5653  5701 I io.jxcore.node.ConnectionModelTest: Starting test: testGetOutgoingConnectionCallbackByBluetoothMacAddress
11-21 16:25:17.207  5653  5701 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
11-21 16:25:17.207  5653  5701 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
11-21 16:25:17.207  5653  5701 I io.jxcore.node.ConnectionModelTest: Starting test: testHasConnection
11-21 16:25:17.207  5653  5701 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
11-21 16:25:17.207  5653  5701 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
11-21 16:25:17.207  5653  5701 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
11-21 16:25:17.208  5653  5701 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
11-21 16:25:17.208  5653  5701 I io.jxcore.node.ConnectionModelTest: Starting test: testHasOutgoingConnection
11-21 16:25:17.209  5653  5701 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-21 16:25:17.209  5653  5701 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9fd0ebc added. We now have 3 listener(s)
,11-21 16:25:17.211  5653  5701 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
,11-21 16:25:17.211  5653  5701 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-21 16:25:17.211  5653  5701 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-21 16:25:17.211  5653  5701 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-21 16:25:17.211  5653  5701 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ca4be45 added. We now have 3 listener(s)
11-21 16:25:17.211  5653  5701 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-21 16:25:17.212  5653  5701 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,11-21 16:25:17.215  5653  5701 D BluetoothAdapter: enable(): BT is already enabled..!
,11-21 16:25:17.215   927   938 D WifiService: setWifiEnabled: true pid=5653, uid=10077
11-21 16:25:17.215   927   938 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
11-21 16:25:17.217  5653  5701 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testIsBleMultipleAdvertisementSupported
,11-21 16:25:17.220  5653  5701 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testIsBluetoothSupported
,11-21 16:25:17.221  5653  5701 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testStartStop
,11-21 16:25:17.224  5653  5701 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testIsWifiDirectSupported
,11-21 16:25:17.224  5653  5701 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testIsBluetoothEnabled
,11-21 16:25:17.230  5653  5701 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-21 16:25:17.230  5653  5701 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-21 16:25:17.230  5653  5701 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-21 16:25:17.230  5653  5701 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-21 16:25:17.230  5653  5701 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-21 16:25:17.230  5653  5701 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-21 16:25:17.230  5653  5701 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-21 16:25:17.230  5653  5701 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-21 16:25:17.230  5653  5701 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,11-21 16:25:17.233  4709  4777 D BluetoothAdapterState: Current state: ON, message: 23
11-21 16:25:17.233  4709  4777 D BluetoothAdapterProperties: Setting state to 13
11-21 16:25:17.233  4709  4777 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
11-21 16:25:17.233  5653  5701 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
,11-21 16:25:17.234  4709  4777 D BluetoothAdapterProperties: onBluetoothDisable()
11-21 16:25:17.234  4709  4777 I BluetoothAdapterState: Entering PendingCommandState
,11-21 16:25:17.236  4709  4709 D BluetoothMapService: onReceive
,11-21 16:25:17.236  4709  4709 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
11-21 16:25:17.237  4709  4709 D BluetoothMapService: STATE_TURNING_OFF
11-21 16:25:17.237  4709  4709 D BluetoothMapService: MAP Service closeService in
11-21 16:25:17.237  4709  4709 D BluetoothMapMasInstance0: MAP Service shutdown
11-21 16:25:17.237  4709  4709 D ObexServerSockets0: shutdown(block = true)
11-21 16:25:17.238  4709  4709 D ObexServerSockets0: shutdown called from another thread - interrupt().
,11-21 16:25:17.238  4709  4943 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 5
,11-21 16:25:17.238  4709  4709 D ObexServerSockets0: shutdown called from another thread - interrupt().
11-21 16:25:17.238  4709  4928 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
11-21 16:25:17.238  4709  4944 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
11-21 16:25:17.240  4709  4709 I BtOppRfcommListener: stopping Accept Thread
,11-21 16:25:17.240  4709  5348 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
11-21 16:25:17.240  4709  5348 I BtOppRfcommListener: BluetoothSocket listen thread finished
,11-21 16:25:17.254   927   940 I ActivityManager: Start proc 5739:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
,11-21 16:25:17.255  4709  4781 D BluetoothAdapterProperties: Scan Mode:20
11-21 16:25:17.256  4709  4777 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
,11-21 16:25:17.258  4709  4709 D HeadsetService: Received stop request...Stopping profile...
,11-21 16:25:17.260  4709  4709 V BluetoothAdapterState: isTurningOff()=true
11-21 16:25:17.260  4709  4709 V BluetoothAdapterState: isTurningOn()=false
11-21 16:25:17.260  4709  4709 V BluetoothAdapterState: isBleTurningOn()=false
11-21 16:25:17.260  4709  4709 V BluetoothAdapterState: isBleTurningOff()=false
11-21 16:25:17.260  3209  3983 D BluetoothHeadset: Proxy object disconnected
11-21 16:25:17.261  4709  4709 D A2dpService: Received stop request...Stopping profile...
11-21 16:25:17.261  3209  3209 D HeadsetProfile: Bluetooth service disconnected
11-21 16:25:17.261   927   927 D BluetoothHeadset: Proxy object disconnected
11-21 16:25:17.261   927   927 D BluetoothHeadset: Proxy object disconnected
11-21 16:25:17.261   927   927 D BluetoothHeadset: Proxy object disconnected
11-21 16:25:17.261  4709  4932 D A2dpStateMachine: Exit Disconnected: -1
11-21 16:25:17.261  3848  3861 D BluetoothHeadset: Proxy object disconnected
11-21 16:25:17.262   927   927 D BluetoothA2dp: Proxy object disconnected
11-21 16:25:17.263  3209  3209 D BluetoothA2dp: Proxy object disconnected
,11-21 16:25:17.265  4709  4709 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
,11-21 16:25:17.265  4709  4709 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
11-21 16:25:17.265  4709  4912 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-21 16:25:17.265  4709  4912 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,11-21 16:25:17.265  4709  4912 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,11-21 16:25:17.265  4709  4781 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
11-21 16:25:17.265  4709  4781 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
11-21 16:25:17.266  4709  4709 D HidService: Received stop request...Stopping profile...
11-21 16:25:17.266  4709  4709 D HidService: Stopping Bluetooth HidService
11-21 16:25:17.267  3209  3209 D BluetoothInputDevice: Proxy object disconnected
11-21 16:25:17.267  3209  3209 D HidProfile: Bluetooth service disconnected
11-21 16:25:17.267  4709  4709 V BluetoothAdapterState: isTurningOff()=true
11-21 16:25:17.267  4709  4709 V BluetoothAdapterState: isTurningOn()=false
,11-21 16:25:17.267  4709  4709 V BluetoothAdapterState: isBleTurningOn()=false
11-21 16:25:17.267  4709  4709 V BluetoothAdapterState: isBleTurningOff()=false
11-21 16:25:17.268  4709  4709 D HealthService: Received stop request...Stopping profile...
11-21 16:25:17.270  4709  4781 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
11-21 16:25:17.270  4709  4912 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-21 16:25:17.270  4709  4912 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-21 16:25:17.270  4709  4912 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,11-21 16:25:17.270  4709  4912 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,11-21 16:25:17.270  4709  4912 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
11-21 16:25:17.270  4709  4912 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
11-21 16:25:17.270  4709  4709 D PanService: Received stop request...Stopping profile...
11-21 16:25:17.271  3209  3209 D BluetoothPan: BluetoothPAN Proxy object disconnected
11-21 16:25:17.271  3209  3209 D PanProfile: Bluetooth service disconnected
11-21 16:25:17.271  4709  4709 D BluetoothMapService: Received stop request...Stopping profile...
11-21 16:25:17.272  4709  4709 D BluetoothMapService: stop()
11-21 16:25:17.272  4709  4709 D BluetoothMapAppObserver: deinitObservers()
11-21 16:25:17.273  4709  4709 D BluetoothMapAppObserver: removeReceiver()
11-21 16:25:17.274  3209  3209 D BluetoothMap: Proxy object disconnected
11-21 16:25:17.274  3209  3209 D MapProfile: Bluetooth service disconnected
11-21 16:25:17.274  4709  4709 V BluetoothAdapterState: isTurningOff()=true
11-21 16:25:17.274  4709  4709 V BluetoothAdapterState: isTurningOn()=false
11-21 16:25:17.274  4709  4709 V BluetoothAdapterState: isBleTurningOn()=false
11-21 16:25:17.274  4709  4709 V BluetoothAdapterState: isBleTurningOff()=false
,11-21 16:25:17.274  4709  4709 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
11-21 16:25:17.274  4709  4709 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
11-21 16:25:17.274  4709  4781 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
11-21 16:25:17.275  4709  4709 D SapService: Received stop request...Stopping profile...
11-21 16:25:17.275  4709  4709 V SapService: stop()
11-21 16:25:17.276  4709  4709 V BluetoothAdapterState: isTurningOff()=true
11-21 16:25:17.276  4709  4709 V BluetoothAdapterState: isTurningOn()=false
,11-21 16:25:17.276  4709  4709 V BluetoothAdapterState: isBleTurningOn()=false
11-21 16:25:17.276  4709  4709 V BluetoothAdapterState: isBleTurningOff()=false
11-21 16:25:17.276  4709  4709 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
,11-21 16:25:17.277  4709  4781 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
,11-21 16:25:17.277  4709  4709 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
11-21 16:25:17.277  4709  4709 V BluetoothAdapterState: isTurningOff()=true
11-21 16:25:17.277  4709  4709 V BluetoothAdapterState: isTurningOn()=false
,11-21 16:25:17.277  4709  4709 V BluetoothAdapterState: isBleTurningOn()=false
11-21 16:25:17.278  4709  4709 V BluetoothAdapterState: isBleTurningOff()=false
11-21 16:25:17.278  4709  4709 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
11-21 16:25:17.278  4709  4709 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
,11-21 16:25:17.286  4709  4709 D BluetoothMapService: MAP Service closeService in
,11-21 16:25:17.287  4709  4709 V BluetoothAdapterState: isTurningOff()=true
,11-21 16:25:17.287  4709  4709 V BluetoothAdapterState: isTurningOn()=false
11-21 16:25:17.287  4709  4709 V BluetoothAdapterState: isBleTurningOn()=false
11-21 16:25:17.287  4709  4709 V BluetoothAdapterState: isBleTurningOff()=false
11-21 16:25:17.287  4709  4709 D BluetoothMapService: cleanup()
,11-21 16:25:17.287  4709  4709 D BluetoothMapService: MAP Service closeService in
11-21 16:25:17.287  4709  4709 V BluetoothAdapterState: isTurningOff()=true
11-21 16:25:17.287  4709  4709 V BluetoothAdapterState: isTurningOn()=false
11-21 16:25:17.287  4709  4709 V BluetoothAdapterState: isBleTurningOn()=false
11-21 16:25:17.288  4709  4709 V BluetoothAdapterState: isBleTurningOff()=false
11-21 16:25:17.288  4709  4777 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
11-21 16:25:17.288  4709  4777 D BluetoothAdapterProperties: Setting state to 15
11-21 16:25:17.288  4709  4777 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
11-21 16:25:17.288  4709  4777 I BluetoothAdapterState: Entering BleOnState
11-21 16:25:17.289  3209  3983 D BluetoothHeadset: onBluetoothStateChange: up=false
11-21 16:25:17.289  3209  3220 D BluetoothInputDevice: onBluetoothStateChange: up=false
11-21 16:25:17.290   927   944 D BluetoothHeadset: onBluetoothStateChange: up=false
11-21 16:25:17.290  3209  5652 D BluetoothA2dp: onBluetoothStateChange: up=false
,11-21 16:25:17.291   927   944 D BluetoothA2dp: onBluetoothStateChange: up=false
,11-21 16:25:17.291  3209  3222 D BluetoothPbap: onBluetoothStateChange: up=false
11-21 16:25:17.292  3209  5651 D BluetoothPan: onBluetoothStateChange on: false
11-21 16:25:17.293   927   944 D BluetoothHeadset: onBluetoothStateChange: up=false
11-21 16:25:17.293   927   944 D BluetoothHeadset: onBluetoothStateChange: up=false
11-21 16:25:17.293  3848  3860 D BluetoothHeadset: onBluetoothStateChange: up=false
11-21 16:25:17.293  3209  3983 D BluetoothMap: onBluetoothStateChange: up=false
11-21 16:25:17.297  4709  4777 D BluetoothAdapterState: Current state: BLE ON, message: 20
11-21 16:25:17.297  4709  4777 D BluetoothAdapterProperties: Setting state to 16
,11-21 16:25:17.297  4709  4777 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
11-21 16:25:17.298  4709  4777 D BluetoothAdapterProperties: onBleDisable
11-21 16:25:17.299  4709  4777 I BluetoothAdapterState: Entering PendingCommandState
11-21 16:25:17.299  4709  4778 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
,11-21 16:25:17.300  4709  4912 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
11-21 16:25:17.300  4709  4912 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,11-21 16:25:17.301  4709  4781 D BluetoothAdapterProperties: Scan Mode:20
,11-21 16:25:17.325  5739  5739 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm64
,11-21 16:25:17.336  5739  5739 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,11-21 16:25:17.342   927   944 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@c4b141d:true
,11-21 16:25:17.343  3647  3647 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,11-21 16:25:17.363  5739  5739 D LocalBluetoothProfileManager: Adding local MAP profile
,11-21 16:25:17.364  5739  5739 D BluetoothMap: Create BluetoothMap proxy object
,11-21 16:25:17.371  5739  5739 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,11-21 16:25:17.377  5739  5739 D DockEventReceiver: finishStartingService: stopping service
,11-21 16:25:17.380  5739  5739 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,11-21 16:25:17.385  3647  3647 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
11-21 16:25:17.385  5739  5739 D DockEventReceiver: finishStartingService: stopping service
,11-21 16:25:17.387   927   937 I ActivityManager: Killing 5444:com.android.sdm.plugins.sprintdm/1001 (adj 15): empty #17
,11-21 16:25:17.507  4709  4781 I bt_hci  : shut_down
,11-21 16:25:17.518  4709  4785 D bt_hwcfg: hw_epilog_process
,11-21 16:25:17.518  4709  4785 I bt_vendor: low_power_mode_cb
,11-21 16:25:17.522  4709  4785 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
11-21 16:25:17.522  4709  4785 I bt_vendor: epilog_cb
11-21 16:25:17.522  4709  4785 I bt_hci  : epilog_finished_callback
,11-21 16:25:17.528  4709  4781 I bt_hci_h4: hal_close
,11-21 16:25:17.529  4709  4781 I bt_userial_vendor: device fd = 54 close
,11-21 16:25:17.645  4709  4778 D bt_stack_manager: event_shut_down_stack finished.
,11-21 16:25:17.646  4709  4777 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,11-21 16:25:17.651  4709  4777 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
11-21 16:25:17.651  4709  4709 D BtGatt.DebugUtils: handleDebugAction() action=null
,11-21 16:25:17.652  4709  4709 D BtGatt.GattService: Received stop request...Stopping profile...
,11-21 16:25:17.652  4709  4709 D BtGatt.GattService: stop()
,11-21 16:25:17.652  4709  4709 D BtGatt.AdvertiseManager: advertise clients cleared
,11-21 16:25:17.655  4709  4709 V BluetoothAdapterState: isTurningOff()=false
11-21 16:25:17.656  4709  4709 V BluetoothAdapterState: isTurningOn()=false
11-21 16:25:17.656  4709  4709 V BluetoothAdapterState: isBleTurningOn()=false
11-21 16:25:17.656  4709  4709 V BluetoothAdapterState: isBleTurningOff()=true
11-21 16:25:17.656  4709  4777 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
,11-21 16:25:17.657  4709  4777 D BluetoothAdapterProperties: Setting state to 10
11-21 16:25:17.657  4709  4777 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
11-21 16:25:17.658  4709  4777 I BluetoothAdapterState: Entering OffState
11-21 16:25:17.659   927   944 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,11-21 16:25:17.674  4709  4709 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,11-21 16:25:17.674  4709  4709 W BluetoothSdpJni: Cleaning up Bluetooth Health object
11-21 16:25:17.674  4709  4709 I BluetoothServiceJni: cleanupNative: return from cleanup
,11-21 16:25:17.678  4709  4778 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,11-21 16:25:17.685  4709  4709 I art     : System.exit called, status: 0
,11-21 16:25:17.686  4709  4709 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,11-21 16:25:17.693  5653  5653 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-21 16:25:17.722   927  3192 I ActivityManager: Process com.android.bluetooth (pid 4709) has died
,11-21 16:25:17.733  5653  5737 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,11-21 16:25:17.734  5653  5737 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-21 16:25:17.734  5653  5737 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-21 16:25:17.734  5653  5737 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-21 16:25:17.734  5653  5737 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-21 16:25:17.734  5653  5737 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-21 16:25:17.734  5653  5737 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-21 16:25:17.734  5653  5737 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-21 16:25:17.734  5653  5737 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-21 16:25:17.734  5653  5737 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
11-21 16:25:17.734  5653  5737 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-21 16:25:17.734  5653  5737 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
,11-21 16:25:17.738  5653  5701 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-21 16:25:17.750   927   944 I ActivityManager: Start proc 5756:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,11-21 16:25:17.812  5756  5756 D AdapterServiceConfig: Adding HeadsetService
,11-21 16:25:17.812  5756  5756 D AdapterServiceConfig: Adding A2dpService
,11-21 16:25:17.813  5756  5756 D AdapterServiceConfig: Adding HidService
11-21 16:25:17.813  5756  5756 D AdapterServiceConfig: Adding HealthService
,11-21 16:25:17.813  5756  5756 D AdapterServiceConfig: Adding PanService
11-21 16:25:17.813  5756  5756 D AdapterServiceConfig: Adding GattService
11-21 16:25:17.813  5756  5756 D AdapterServiceConfig: Adding BluetoothMapService
11-21 16:25:17.813  5756  5756 D AdapterServiceConfig: Adding SapService
,11-21 16:25:17.822   927   944 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@57deaf:true
,11-21 16:25:17.822  5756  5756 D BluetoothAdapterState: make() - Creating AdapterState
,11-21 16:25:17.825  5756  5756 I bt_bluedroid: init
,11-21 16:25:17.825  5756  5768 I BluetoothAdapterState: Entering OffState
,11-21 16:25:17.827  5756  5769 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,11-21 16:25:17.827  5756  5769 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
11-21 16:25:17.827  5756  5769 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
11-21 16:25:17.827  5756  5769 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
11-21 16:25:17.827  5756  5756 I bt_bluedroid: get_profile_interface socket
,11-21 16:25:17.829  5756  5756 I bt_bluedroid: get_profile_interface sdp
,11-21 16:25:17.829  5756  5772 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:D4
11-21 16:25:17.830  5756  5772 D BluetoothAdapterProperties: Name is: Nexus 6P
,11-21 16:25:17.834  5756  5767 I bt_bluedroid: config_hci_snoop_log
,11-21 16:25:17.835   927   944 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,11-21 16:25:17.839  5756  5768 D BluetoothAdapterState: Current state: OFF, message: 0
,11-21 16:25:17.839  5756  5768 D BluetoothAdapterProperties: Setting state to 14
11-21 16:25:17.839  5756  5768 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,11-21 16:25:17.841  5756  5768 D BluetoothBondStateMachine: make
,11-21 16:25:17.843  5756  5773 I BluetoothBondStateMachine: StableState(): Entering Off State
,11-21 16:25:17.845  5756  5768 I BluetoothAdapterState: Entering PendingCommandState
,11-21 16:25:17.846  5756  5756 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,11-21 16:25:17.848  5756  5756 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5411672
,11-21 16:25:17.849  5756  5756 D BtGatt.DebugUtils: handleDebugAction() action=null
,11-21 16:25:17.850  5756  5756 D BtGatt.GattService: Received start request. Starting profile...
11-21 16:25:17.850  5756  5756 D BtGatt.GattService: start()
11-21 16:25:17.850  5756  5756 I bt_bluedroid: get_profile_interface gatt
,11-21 16:25:17.851  5756  5756 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5411672
,11-21 16:25:17.851  5756  5756 D BtGatt.AdvertiseManager: advertise manager created
,11-21 16:25:17.856  5756  5756 V BluetoothAdapterState: isTurningOff()=false
,11-21 16:25:17.856  5756  5756 V BluetoothAdapterState: isTurningOn()=false
11-21 16:25:17.856  5756  5756 V BluetoothAdapterState: isBleTurningOn()=true
11-21 16:25:17.856  5756  5756 V BluetoothAdapterState: isBleTurningOff()=false
11-21 16:25:17.856  5756  5768 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,11-21 16:25:17.858  5756  5768 I bt_bluedroid: bt_bluedroid
,11-21 16:25:17.858  5756  5769 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,11-21 16:25:17.858  5756  5769 I bt_hci  : start_up
,11-21 16:25:17.863  5756  5769 I bt_vendor: alloc value 0xf3e49871
,11-21 16:25:17.863  5756  5769 I bt_vendor: init
11-21 16:25:17.863  5756  5769 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
11-21 16:25:17.863  5756  5769 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,11-21 16:25:17.975  5756  5769 D bt_hci  : start_up starting async portion
,11-21 16:25:17.976  5756  5776 I bt_hci  : event_finish_startup
11-21 16:25:17.976  5756  5776 I bt_hci_h4: hal_open
11-21 16:25:17.976  5756  5776 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,11-21 16:25:17.980  5756  5776 I bt_userial_vendor: device fd = 54 open
,11-21 16:25:17.977  5777  5777 W irq/448-msm_hs_: type=1400 audit(0.0:121): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-21 16:25:17.994  5756  5776 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,11-21 16:25:17.997  5756  5776 D bt_hwcfg: Chipset BCM4358A3
,11-21 16:25:17.997  5756  5776 D bt_hwcfg: Target name = [BCM4358A3]
11-21 16:25:17.998  5756  5776 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,11-21 16:25:18.242  5756  5768 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 0
,11-21 16:25:18.391  5756  5776 I bt_hwcfg: bt vendor lib: set UART baud 115200
,11-21 16:25:18.392  5756  5776 D bt_hwcfg: Settlement delay -- 100 ms
11-21 16:25:18.392  5756  5776 I bt_hwcfg: Setting fw settlement delay to 100 
,11-21 16:25:18.471   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-21 16:25:18.516  5756  5776 I bt_hwcfg: bt vendor lib: set UART baud 3000000
11-21 16:25:18.516  5756  5776 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:D4
11-21 16:25:18.517  5756  5776 I bt_hwcfg: vendor lib fwcfg completed
11-21 16:25:18.518  5756  5776 I bt_vendor: firmware callback
11-21 16:25:18.518  5756  5776 I bt_hci  : firmware_config_callback
,11-21 16:25:18.527  5756  5779 I bt_btu  : btu_task pending for preload complete event
,11-21 16:25:18.527  5756  5779 I bt_btu_task: Bluetooth chip preload is complete
11-21 16:25:18.527  5756  5779 I bt_btu  : btu_task received preload complete event
,11-21 16:25:18.534  5756  5779 I         : BTE_InitTraceLevels -- TRC_HCI
,11-21 16:25:18.534  5756  5779 I         : BTE_InitTraceLevels -- TRC_L2CAP
11-21 16:25:18.534  5756  5779 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,11-21 16:25:18.534  5756  5779 I         : BTE_InitTraceLevels -- TRC_AVDT
11-21 16:25:18.534  5756  5779 I         : BTE_InitTraceLevels -- TRC_AVRC
11-21 16:25:18.535  5756  5779 I         : BTE_InitTraceLevels -- TRC_A2D
,11-21 16:25:18.535  5756  5779 I         : BTE_InitTraceLevels -- TRC_BNEP
11-21 16:25:18.535  5756  5779 I         : BTE_InitTraceLevels -- TRC_BTM
11-21 16:25:18.535  5756  5779 I         : BTE_InitTraceLevels -- TRC_GAP
11-21 16:25:18.535  5756  5779 I         : BTE_InitTraceLevels -- TRC_PAN
11-21 16:25:18.535  5756  5779 I         : BTE_InitTraceLevels -- TRC_SDP
11-21 16:25:18.535  5756  5779 I         : BTE_InitTraceLevels -- TRC_GATT
11-21 16:25:18.535  5756  5779 I         : BTE_InitTraceLevels -- TRC_SMP
11-21 16:25:18.536  5756  5779 I         : BTE_InitTraceLevels -- TRC_BTAPP
11-21 16:25:18.536  5756  5779 I         : BTE_InitTraceLevels -- TRC_BTIF
,11-21 16:25:18.620  5756  5779 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf3dc7549
11-21 16:25:18.620  5756  5779 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf3dc7549 
,11-21 16:25:18.632  5756  5772 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,11-21 16:25:18.633  5756  5772 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,11-21 16:25:18.634  5756  5772 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:D4
,11-21 16:25:18.636  5756  5772 D BluetoothAdapterProperties: Name is: Nexus 6P
11-21 16:25:18.640  5756  5772 D BluetoothAdapterProperties: Scan Mode:20
11-21 16:25:18.640  5756  5772 D BluetoothAdapterProperties: Discoverable Timeout:120
11-21 16:25:18.640  5756  5772 D bt_hci  : do_postload posting postload work item
11-21 16:25:18.640  5756  5776 I bt_hci  : event_postload
11-21 16:25:18.640  5756  5776 I bt_vendor: sco_config_cb
11-21 16:25:18.640  5756  5776 I bt_hci  : sco_config_callback postload finished.
11-21 16:25:18.642  5756  5772 D bt_bte_conf: Device ID record 1 : primary
11-21 16:25:18.642  5756  5772 D bt_bte_conf:   vendorId            = 000f
11-21 16:25:18.642  5756  5772 D bt_bte_conf:   vendorIdSource      = 0001
11-21 16:25:18.643  5756  5772 D bt_bte_conf:   product             = 1200
11-21 16:25:18.643  5756  5772 D bt_bte_conf:   version             = 1436
11-21 16:25:18.643  5756  5772 D bt_bte_conf:   clientExecutableURL = 
11-21 16:25:18.643  5756  5772 D bt_bte_conf:   serviceDescription  = 
11-21 16:25:18.643  5756  5772 D bt_bte_conf:   documentationURL    = 
11-21 16:25:18.643  5756  5772 D bt_bte_conf: bte_load_did_conf no section named DID2.
11-21 16:25:18.643  5756  5769 D bt_stack_manager: event_start_up_stack finished
11-21 16:25:18.644  5756  5768 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
11-21 16:25:18.644  5756  5768 D BluetoothAdapterProperties: Setting state to 15
11-21 16:25:18.645  5756  5768 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
11-21 16:25:18.647  5756  5776 I bt_vendor: low_power_mode_cb
11-21 16:25:18.649  5756  5768 I BluetoothAdapterState: Entering BleOnState
11-21 16:25:18.654  5756  5768 D BluetoothAdapterState: Current state: BLE ON, message: 1
11-21 16:25:18.654  5756  5768 D BluetoothAdapterProperties: Setting state to 11
11-21 16:25:18.654  5756  5768 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
11-21 16:25:18.662  5756  5756 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5411672
11-21 16:25:18.663  5756  5756 D HeadsetService: Received start request. Starting profile...
11-21 16:25:18.666  5756  5756 I BluetoothHeadsetServiceJni: classInitNative: succeeds
11-21 16:25:18.666  5756  5756 D HeadsetStateMachine: make
11-21 16:25:18.678  5756  5768 I BluetoothAdapterState: Entering PendingCommandState
,11-21 16:25:18.679  5756  5756 D HeadsetStateMachine: max_hf_connections = 1
,11-21 16:25:18.679  5756  5756 I bt_bluedroid: get_profile_interface handsfree
11-21 16:25:18.679  5756  5772 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
11-21 16:25:18.679  5756  5772 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
11-21 16:25:18.682  5756  5756 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5411672
11-21 16:25:18.683  5756  5756 D A2dpService: Received start request. Starting profile...
11-21 16:25:18.683  5756  5756 I BluetoothAvrcpServiceJni: classInitNative: succeeds
11-21 16:25:18.684  5756  5756 I bt_bluedroid: get_profile_interface avrcp
,11-21 16:25:18.690  5756  5756 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,11-21 16:25:18.690  5756  5756 I BluetoothA2dpServiceJni: classInitNative: succeeds
11-21 16:25:18.690  5756  5756 D A2dpStateMachine: make
11-21 16:25:18.691  5756  5756 I bt_bluedroid: get_profile_interface a2dp
,11-21 16:25:18.692  5756  5772 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,11-21 16:25:18.693  5756  5787 D A2dpStateMachine: Enter Disconnected: -2
,11-21 16:25:18.694  5756  5756 I BluetoothHidServiceJni: classInitNative: succeeds
,11-21 16:25:18.695  5756  5756 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5411672
,11-21 16:25:18.697  5739  5739 D BluetoothInputDevice: Proxy object connected
11-21 16:25:18.697  3647  3647 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,11-21 16:25:18.697  5756  5756 D HidService: Received start request. Starting profile...
11-21 16:25:18.698  5756  5756 I bt_bluedroid: get_profile_interface hidhost
11-21 16:25:18.698  5756  5756 D HidService: setHidService(): set to: null
11-21 16:25:18.698  5739  5739 D HidProfile: Bluetooth service connected
11-21 16:25:18.698  5756  5756 I BluetoothHealthServiceJni: classInitNative: succeeds
11-21 16:25:18.699  5756  5772 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf3da856d
11-21 16:25:18.699  5756  5756 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5411672
11-21 16:25:18.699  5756  5772 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
11-21 16:25:18.700  5756  5756 D HealthService: Received start request. Starting profile...
,11-21 16:25:18.701  5756  5756 I bt_bluedroid: get_profile_interface health
,11-21 16:25:18.702  5756  5756 I BluetoothPanServiceJni: classInitNative(L105): succeeds
11-21 16:25:18.703  5756  5756 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5411672
,11-21 16:25:18.704  5756  5756 D PanService: Received start request. Starting profile...
11-21 16:25:18.704  5739  5739 D BluetoothPan: BluetoothPAN Proxy object connected
11-21 16:25:18.704  5756  5756 D BluetoothPanServiceJni: initializeNative(L110): pan
11-21 16:25:18.704  5756  5756 I bt_bluedroid: get_profile_interface pan
11-21 16:25:18.704  5756  5772 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
11-21 16:25:18.704  5739  5739 D PanProfile: Bluetooth service connected
11-21 16:25:18.706  5756  5756 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5411672
,11-21 16:25:18.707  5756  5756 D BluetoothMapService: Received start request. Starting profile...
,11-21 16:25:18.707  5756  5756 D BluetoothMapService: start()
11-21 16:25:18.707  5739  5739 D BluetoothMap: Proxy object connected
11-21 16:25:18.708  5739  5739 D MapProfile: Bluetooth service connected
11-21 16:25:18.708  5739  5739 D BluetoothMap: getConnectedDevices()
11-21 16:25:18.709  5739  5739 D BluetoothMap: Bluetooth is Not enabled
,11-21 16:25:18.710  5756  5756 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,11-21 16:25:18.711  5756  5756 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
11-21 16:25:18.711  5756  5756 D BluetoothMapAppObserver: createReceiver()
,11-21 16:25:18.712  5756  5756 D BluetoothMapAppObserver: initObservers()
,11-21 16:25:18.712  5756  5756 D BluetoothMapAppObserver: getEnabledAccountItems()
,11-21 16:25:18.719  5756  5756 V SapService: SapBinder()
,11-21 16:25:18.719  5756  5756 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5411672
,11-21 16:25:18.720  5756  5756 D SapService: Received start request. Starting profile...
,11-21 16:25:18.720  5756  5756 V SapService: start()
11-21 16:25:18.721  5756  5756 V BluetoothAdapterState: isTurningOff()=false
11-21 16:25:18.721  5756  5756 V BluetoothAdapterState: isTurningOn()=true
11-21 16:25:18.721  5756  5756 V BluetoothAdapterState: isBleTurningOn()=false
11-21 16:25:18.721  5756  5756 V BluetoothAdapterState: isBleTurningOff()=false
11-21 16:25:18.722  5756  5756 V BluetoothAdapterState: isTurningOff()=false
11-21 16:25:18.722  5756  5756 V BluetoothAdapterState: isTurningOn()=true
,11-21 16:25:18.722  5756  5756 V BluetoothAdapterState: isBleTurningOn()=false
11-21 16:25:18.722  5756  5756 V BluetoothAdapterState: isBleTurningOff()=false
11-21 16:25:18.722  5756  5785 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
11-21 16:25:18.722  5756  5756 V BluetoothAdapterState: isTurningOff()=false
11-21 16:25:18.722  5756  5756 V BluetoothAdapterState: isTurningOn()=true
11-21 16:25:18.722  5756  5756 V BluetoothAdapterState: isBleTurningOn()=false
11-21 16:25:18.722  5756  5756 V BluetoothAdapterState: isBleTurningOff()=false
,11-21 16:25:18.723  5756  5756 V BluetoothAdapterState: isTurningOff()=false
11-21 16:25:18.723  5756  5756 V BluetoothAdapterState: isTurningOn()=true
11-21 16:25:18.723  5756  5756 V BluetoothAdapterState: isBleTurningOn()=false
11-21 16:25:18.723  5756  5756 V BluetoothAdapterState: isBleTurningOff()=false
11-21 16:25:18.723  5756  5756 V BluetoothAdapterState: isTurningOff()=false
11-21 16:25:18.723  5756  5756 V BluetoothAdapterState: isTurningOn()=true
11-21 16:25:18.723  5756  5756 V BluetoothAdapterState: isBleTurningOn()=false
11-21 16:25:18.723  5756  5756 V BluetoothAdapterState: isBleTurningOff()=false
11-21 16:25:18.723  5756  5756 V BluetoothAdapterState: isTurningOff()=false
11-21 16:25:18.723  5756  5756 V BluetoothAdapterState: isTurningOn()=true
11-21 16:25:18.723  5756  5756 V BluetoothAdapterState: isBleTurningOn()=false
,11-21 16:25:18.723  5756  5756 V BluetoothAdapterState: isBleTurningOff()=false
11-21 16:25:18.724  5756  5756 V BluetoothAdapterState: isTurningOff()=false
11-21 16:25:18.724  5756  5756 V BluetoothAdapterState: isTurningOn()=true
11-21 16:25:18.724  5756  5756 V BluetoothAdapterState: isBleTurningOn()=false
11-21 16:25:18.724  5756  5756 V BluetoothAdapterState: isBleTurningOff()=false
11-21 16:25:18.724  5756  5768 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
11-21 16:25:18.724  5756  5768 D BluetoothAdapterProperties: ScanMode =  20
11-21 16:25:18.724  5756  5768 D BluetoothAdapterProperties: State =  11
11-21 16:25:18.725  5756  5768 D BluetoothAdapterProperties: Setting state to 12
,11-21 16:25:18.725  5756  5768 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
11-21 16:25:18.725  3209  5652 D BluetoothHeadset: onBluetoothStateChange: up=true
11-21 16:25:18.726  5756  5772 D BluetoothAdapterProperties: Scan Mode:21
11-21 16:25:18.726  5756  5772 D BluetoothAdapterProperties: Discoverable Timeout:120
11-21 16:25:18.726  5756  5768 I BluetoothAdapterState: Entering OnState
11-21 16:25:18.726  3209  3222 D BluetoothInputDevice: onBluetoothStateChange: up=true
,11-21 16:25:18.728  3209  3209 D BluetoothInputDevice: Proxy object connected
11-21 16:25:18.728   927   944 D BluetoothHeadset: onBluetoothStateChange: up=true
11-21 16:25:18.728  3209  3209 D HidProfile: Bluetooth service connected
11-21 16:25:18.729  3209  3220 D BluetoothA2dp: onBluetoothStateChange: up=true
,11-21 16:25:18.731  5739  5749 D BluetoothInputDevice: onBluetoothStateChange: up=true
,11-21 16:25:18.731  3209  3209 D BluetoothA2dp: Proxy object connected
11-21 16:25:18.731  5739  5750 D BluetoothPbap: onBluetoothStateChange: up=true
11-21 16:25:18.732   927   944 D BluetoothA2dp: onBluetoothStateChange: up=true
11-21 16:25:18.733   927   927 D BluetoothA2dp: Proxy object connected
11-21 16:25:18.733  3209  3983 D BluetoothPbap: onBluetoothStateChange: up=true
11-21 16:25:18.734  3209  3222 D BluetoothPan: onBluetoothStateChange on: true
11-21 16:25:18.735  3209  3209 D BluetoothPan: BluetoothPAN Proxy object connected
11-21 16:25:18.735  5739  5749 D BluetoothMap: onBluetoothStateChange: up=true
11-21 16:25:18.735  3209  3209 D PanProfile: Bluetooth service connected
11-21 16:25:18.736  5739  5750 D BluetoothPan: onBluetoothStateChange on: true
,11-21 16:25:18.736   927   944 D BluetoothHeadset: onBluetoothStateChange: up=true
11-21 16:25:18.736   927   944 D BluetoothHeadset: onBluetoothStateChange: up=true
11-21 16:25:18.736  3848  4052 D BluetoothHeadset: onBluetoothStateChange: up=true
11-21 16:25:18.737  3209  3220 D BluetoothMap: onBluetoothStateChange: up=true
11-21 16:25:18.737  5756  5756 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,11-21 16:25:18.738  5756  5756 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
,11-21 16:25:18.738  3209  3209 D BluetoothMap: Proxy object connected
11-21 16:25:18.738  3209  3209 D MapProfile: Bluetooth service connected
11-21 16:25:18.738  3209  3209 D BluetoothMap: getConnectedDevices()
,11-21 16:25:18.739   927   927 I Telecom : BluetoothPhoneService: queryPhoneState
,11-21 16:25:18.741  5756  5756 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-21 16:25:18.743  5739  5739 D LocalBluetoothProfileManager: Adding local A2DP profile
,11-21 16:25:18.746  5756  5756 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-21 16:25:18.747  5739  5739 D LocalBluetoothProfileManager: Adding local HEADSET profile
11-21 16:25:18.747  5653  5737 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-21 16:25:18.747  5653  5737 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-21 16:25:18.747  5653  5737 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-21 16:25:18.747  5653  5737 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-21 16:25:18.747  5653  5737 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-21 16:25:18.747  5653  5737 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-21 16:25:18.747  5653  5737 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-21 16:25:18.747  5653  5737 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-21 16:25:18.747  5653  5737 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
11-21 16:25:18.748  5756  5756 D ObexServerSockets: Succeed to create listening sockets 
11-21 16:25:18.748  5756  5756 D ObexServerSockets0: startAccept()
11-21 16:25:18.749  5756  5756 D ObexServerSockets0: prepareForNewConnect()
11-21 16:25:18.750  5653  5737 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
11-21 16:25:18.750  5756  5756 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
11-21 16:25:18.751  5756  5756 D BluetoothSdpJni: SDP Create record success - handle: 0
11-21 16:25:18.751  5756  5756 D BluetoothMapService: onReceive
11-21 16:25:18.751  5653  5701 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testIsWifiEnabled
11-21 16:25:18.751  5756  5756 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
11-21 16:25:18.751  5756  5756 D BluetoothMapService: STATE_ON
11-21 16:25:18.752  5756  5795 D ObexServerSockets0: Accepting socket connection...
11-21 16:25:18.752   927  5426 D WifiService: setWifiEnabled: false pid=5653, uid=10077
11-21 16:25:18.752   927  5426 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
11-21 16:25:18.752  5756  5794 D ObexServerSockets0: Accepting socket connection...
11-21 16:25:18.753  5756  5796 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-21 16:25:18.753   927  3029 D WifiStateMachine: WifiStateMachine: Leaving Connected state
11-21 16:25:18.754   927  3029 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
11-21 16:25:18.754   927  3029 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
11-21 16:25:18.754   927  3029 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-21 16:25:18.756  5739  5739 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,11-21 16:25:18.757  5653  5701 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-21 16:25:18.758  5756  5796 D BluetoothSdpJni: sdpCreateSapsRecordNative:
11-21 16:25:18.759  5756  5796 D BluetoothSdpJni: SDP Create record success - handle: 1
,11-21 16:25:18.763  5739  5739 D BluetoothA2dp: Proxy object connected
,11-21 16:25:18.766  3647  3647 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,11-21 16:25:18.766   509   923 D CommandListener: Clearing all IP addresses on wlan0
,11-21 16:25:18.766   927  5417 D DhcpClient: Clearing IP address
11-21 16:25:18.772  5739  5739 D DockEventReceiver: finishStartingService: stopping service
,11-21 16:25:18.773   509   923 D CommandListener: Setting iface cfg
11-21 16:25:18.773  3209  3209 D BluetoothPbap: Proxy object connected
11-21 16:25:18.773  3209  3209 D PbapServerProfile: Bluetooth service connected
,11-21 16:25:18.773  5739  5739 D BluetoothPbap: Proxy object connected
,11-21 16:25:18.774  3647  5471 V NativeCrypto: Read error: ssl=0x7f908d3f00: I/O error during system call, Connection timed out
11-21 16:25:18.775   927  5418 D DhcpClient: Receive thread stopped
11-21 16:25:18.776  3647  5471 V NativeCrypto: SSL shutdown failed: ssl=0x7f908d3f00: I/O error during system call, Broken pipe
11-21 16:25:18.778  5739  5739 D PbapServerProfile: Bluetooth service connected
,11-21 16:25:18.778   927  3478 D ConnectivityService: reportNetworkConnectivity(100, false) by 10012
11-21 16:25:18.779   927  5415 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Forcing reevaluation for UID 10012
11-21 16:25:18.782   927  5415 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.gstatic.com": No address associated with hostname
,11-21 16:25:18.783   927  3043 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] validation failed
11-21 16:25:18.783   927  3043 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
11-21 16:25:18.784   927  3043 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,11-21 16:25:18.786  5756  5756 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,11-21 16:25:18.786  5756  5756 D ObexServerSockets0: prepareForNewConnect()
11-21 16:25:18.786   927  3043 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
11-21 16:25:18.786   927  3043 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
11-21 16:25:18.791  5756  5802 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-21 16:25:18.792   535   535 E Parcel  : Reading a NULL string not supported here.
11-21 16:25:18.792   927   927 D RttService: SCAN_AVAILABLE : 1
,11-21 16:25:18.793   927  3149 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
11-21 16:25:18.793   927  3043 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
11-21 16:25:18.795  3801  3937 W QCNEJ   : |CORE| network lost: 100
11-21 16:25:18.795  3801  3937 W QCNEJ   : |CORE| onLost: unbind the process to WIFI
,11-21 16:25:18.805   927  3029 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,11-21 16:25:18.810  5756  5807 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-21 16:25:18.811  5756  5807 I BtOppRfcommListener: Accept thread started.
,11-21 16:25:18.812   927  3029 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,11-21 16:25:18.823   509   923 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-21 16:25:18.827  3209  3222 D BluetoothHeadset: Proxy object connected
,11-21 16:25:18.827  3209  3209 D HeadsetProfile: Bluetooth service connected
11-21 16:25:18.827   927   927 D BluetoothHeadset: Proxy object connected
11-21 16:25:18.828   927   927 D BluetoothHeadset: Proxy object connected
11-21 16:25:18.828   927   927 D BluetoothHeadset: Proxy object connected
11-21 16:25:18.828  3848  4052 D BluetoothHeadset: Proxy object connected
11-21 16:25:18.829   927   944 D BluetoothHeadset: Proxy object connected
,11-21 16:25:18.836   927   944 D BluetoothHeadset: Proxy object connected
11-21 16:25:18.836   927   944 D BluetoothHeadset: Proxy object connected
,11-21 16:25:18.837  3848  3861 D BluetoothHeadset: Proxy object connected
,11-21 16:25:18.844   509   923 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
11-21 16:25:18.844   509   923 D CommandListener: Clearing all IP addresses on wlan0
11-21 16:25:18.844   509   923 D TetherController: Setting IP forward enable = 0
11-21 16:25:18.845   927  3043 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
11-21 16:25:18.846   927  3043 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,11-21 16:25:18.847   927   944 D Tethering: MasterInitialState.processMessage what=3
,11-21 16:25:18.850   927  3029 D DhcpClient: doQuit
,11-21 16:25:18.850   927  3029 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
11-21 16:25:18.851   927  5417 D DhcpClient: onQuitting
11-21 16:25:18.851  3508  3508 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
,11-21 16:25:18.860  5739  5750 D BluetoothHeadset: Proxy object connected
,11-21 16:25:18.863  5301  5301 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@1d738 and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
11-21 16:25:18.863  5739  5739 D HeadsetProfile: Bluetooth service connected
11-21 16:25:18.866  5091  5115 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
11-21 16:25:18.866  5091  5115 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
11-21 16:25:18.867  5091  5115 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,0,0,0
11-21 16:25:18.867  5091  5115 E SarControlService: no key has been found,reset the power
,11-21 16:25:18.867  5091  5125 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
11-21 16:25:18.867  5091  5125 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
11-21 16:25:18.867  5091  5125 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
11-21 16:25:18.867  5116  5116 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
11-21 16:25:18.867  5116  5116 D QcrilMsgTunnelSocket: [1002] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
11-21 16:25:18.869  5091  5125 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
11-21 16:25:18.869  5091  5125 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
11-21 16:25:18.870  4028  4028 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,11-21 16:25:18.872  4012  4012 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
11-21 16:25:18.873  5116  5130 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@26cecde HexData = [00000000ea03000000000000ffffffff]
11-21 16:25:18.873  5116  5130 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-21 16:25:18.873  5116  5130 D QcrilMsgTunnelSocket: [1002] < OEM_HOOK_RAW [null]
11-21 16:25:18.877  5116  5116 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
11-21 16:25:18.877  5091  5101 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
11-21 16:25:18.877  3508  3508 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
11-21 16:25:18.877  5091  5125 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
,11-21 16:25:18.879  5116  5116 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
11-21 16:25:18.880  5116  5116 D QcrilMsgTunnelSocket: [1003] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
11-21 16:25:18.881  4028  4028 D SystemUpdateService: onCreate
11-21 16:25:18.882  3508  3508 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
11-21 16:25:18.885  4028  4028 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
11-21 16:25:18.889  4028  5823 I SystemUpdateService: active receiver: enabled
,11-21 16:25:18.891  5116  5130 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@26cecde HexData = [00000000eb03000000000000ffffffff]
11-21 16:25:18.891  5116  5130 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
,11-21 16:25:18.892  5116  5130 D QcrilMsgTunnelSocket: [1003] < OEM_HOOK_RAW [null]
11-21 16:25:18.892  5116  5116 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
11-21 16:25:18.893  5091  5102 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
,11-21 16:25:18.896  4028  4028 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,11-21 16:25:18.901   509   923 E Netd    : netlink response contains error (No such file or directory)
11-21 16:25:18.901  4028  5439 I iu.UploadsManager: num queued entries: 0
,11-21 16:25:18.901  4028  5439 I iu.UploadsManager: num updated entries: 0
11-21 16:25:18.901  3508  3508 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
11-21 16:25:18.902   927  3043 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
11-21 16:25:18.902   927  3043 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
11-21 16:25:18.903   509   923 D TetherController: Setting IP forward enable = 0
,11-21 16:25:18.904  4028  5823 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,11-21 16:25:18.907  4028  4028 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,11-21 16:25:18.908  4028  4028 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,11-21 16:25:18.909  3508  3508 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
11-21 16:25:18.910  4028  5439 I iu.SyncManager: NEXT; no task
11-21 16:25:18.911  4028  5823 I SystemUpdateService: network: null; metered: false; mobile allowed: true
11-21 16:25:18.911  4028  5823 I SystemUpdateService: now status is 0 (complete)
11-21 16:25:18.911  4028  5823 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
11-21 16:25:18.911  4028  5823 I SystemUpdateService: file has been verified
11-21 16:25:18.912  4028  5823 I SystemUpdateService: OTA package size = 21989297
11-21 16:25:18.917  4028  5823 I SystemUpdateService: showing system update notification
,11-21 16:25:18.921   927  3933 I ActivityManager: Start proc 5828:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,11-21 16:25:18.934   927   927 V NotificationService: pkg=com.google.android.gms canInterrupt=false intercept=true
,11-21 16:25:18.936  4028  4028 D SystemUpdateService: onDestroy
,11-21 16:25:18.956  5828  5828 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm64
,11-21 16:25:18.959  5828  5828 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,11-21 16:25:18.969  5828  5828 D SprintDMHelper: simOperator: 
,11-21 16:25:18.969  5828  5828 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,11-21 16:25:18.982  5066  5840 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,11-21 16:25:18.995   927  3192 I ActivityManager: Start proc 5841:com.google.android.apps.gcs/u0a11 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,11-21 16:25:18.996   927  3192 I ActivityManager: Killing 5301:com.google.android.music:main/u0a59 (adj 15): empty #17
,11-21 16:25:19.023   927  3029 D wifi    : In wifi stop Hal
,11-21 16:25:19.023   927  3029 D wifi    : halHandle = 0x7f8eb5d400, mVM = 0x7fab14d140, mCls = 0x100a02
11-21 16:25:19.023   927  3507 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
,11-21 16:25:19.023   927  3507 D WifiHAL : Got a signal to exit!!!
,11-21 16:25:19.023   927  3507 I WifiHAL : Exit wifi_event_loop
11-21 16:25:19.024  5066  5066 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,11-21 16:25:19.024   927  3029 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 0
11-21 16:25:19.024   927  3029 E WifiHAL : Event processing terminated
11-21 16:25:19.025   927  3029 D wifi    : In wifi cleaned up handler
11-21 16:25:19.025   927  3029 I WifiHAL : Internal cleanup completed
,11-21 16:25:19.026  4160  4290 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,11-21 16:25:19.038  5841  5841 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm64
,11-21 16:25:19.044   927  3507 D wifi    : set interface wlan0 flags (DOWN)
,11-21 16:25:19.044   927  3029 D WifiNative-HAL: HAL event thread stopped successfully
,11-21 16:25:19.046   927  3933 I ActivityManager: Killing 3944:com.android.providers.calendar/u0a1 (adj 15): empty #17
,11-21 16:25:19.251   927   944 D Tethering: InitialState.processMessage what=4
,11-21 16:25:19.264   927   944 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,11-21 16:25:19.265  5653  5737 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-21 16:25:19.265  5653  5737 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-21 16:25:19.265  5653  5737 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-21 16:25:19.265  5653  5737 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-21 16:25:19.265  5653  5737 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-21 16:25:19.265  5653  5737 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-21 16:25:19.265  5653  5737 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-21 16:25:19.265  5653  5737 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-21 16:25:19.265  5653  5737 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,11-21 16:25:19.271  5653  5737 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
,11-21 16:25:19.275   927  4302 D WifiService: setWifiEnabled: true pid=5653, uid=10077
,11-21 16:25:19.275   927  4302 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
11-21 16:25:19.278  5653  5701 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-21 16:25:19.280   509   923 D SoftapController: Softap fwReload - Ok
,11-21 16:25:19.282   509   923 D CommandListener: Setting iface cfg
11-21 16:25:19.283   509   923 D CommandListener: Trying to bring down wlan0
,11-21 16:25:19.284   509   923 D CommandListener: Clearing all IP addresses on wlan0
,11-21 16:25:19.287   927  3029 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,11-21 16:25:19.472   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-21 16:25:19.781   927  3224 D WifiService: setWifiEnabled: true pid=5653, uid=10077
,11-21 16:25:19.785   927  3224 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-21 16:25:19.881   927  3029 D wifi    : set interface wlan0 flags (UP)
,11-21 16:25:19.881   927  3029 I WifiHAL : Initializing wifi
,11-21 16:25:19.881   927  3029 I WifiHAL : Creating socket
11-21 16:25:19.888   927  3029 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
11-21 16:25:19.888   927  3029 D wifi    : Did set static halHandle = 0x7f8eb5d400
11-21 16:25:19.889   927  3029 D wifi    : halHandle = 0x7f8eb5d400, mVM = 0x7fab14d140, mCls = 0x186e
11-21 16:25:19.889   927  3029 D wifi    : array field set
11-21 16:25:19.889   927  3029 I WifiNative-HAL: interface[0] = wlan0
11-21 16:25:19.891   927  5857 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=547855127552
11-21 16:25:19.891   927  5857 D wifi    : waitForHalEvents called, vm = 0x7fab14d140, obj = 0x186e, env = 0x7f94053140
,11-21 16:25:19.893   927   944 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,11-21 16:25:19.974  5858  5858 I wpa_supplicant: Successfully initialized wpa_supplicant
,11-21 16:25:19.993   927  3029 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,11-21 16:25:20.042  5858  5858 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,11-21 16:25:20.050  5858  5858 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,11-21 16:25:20.050  5858  5858 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,11-21 16:25:20.064   927  3029 D WifiConfigStore: Loading config and enabling all networks 
,11-21 16:25:20.079   927  3029 D WifiConfigStore: loaded 0 passpoint configs
,11-21 16:25:20.079   927  3029 W WifiConfigStore: Upgrading network 4 to android.uid.system:1000
11-21 16:25:20.079   927  3029 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,11-21 16:25:20.080   927  3029 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
11-21 16:25:20.080   927  3029 W WifiConfigStore: Upgrading network 3 to android.uid.system:1000
11-21 16:25:20.080   927  3029 W WifiConfigStore: Upgrading network 2 to android.uid.system:1000
,11-21 16:25:20.081   927  3029 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
11-21 16:25:20.081   927  3029 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 5
11-21 16:25:20.081   927  3029 E WifiConfigStore: found sortedWifiConfigurations : "AndroidAP"WPA_PSK
,11-21 16:25:20.081   927  3029 E WifiConfigStore: found sortedWifiConfigurations : "AndroidHotspot2346"WPA_PSK
,11-21 16:25:20.081   927  3029 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
11-21 16:25:20.081   927  3029 E WifiConfigStore: found sortedWifiConfigurations : "Thali_internal"WPA_PSK
11-21 16:25:20.081   927  3029 E WifiConfigStore: found sortedWifiConfigurations : "MC"WPA_PSK
11-21 16:25:20.083   927  3029 D WifiNative-HAL: Setting external_sim to 1
11-21 16:25:20.083   927  3029 D wifi    : setting dfs flag to true, 0x7f9327e2c0
11-21 16:25:20.083   927  3029 D WifiStateMachine: Setting OUI to DA-A1-19
,11-21 16:25:20.083   927  3029 D wifi    : setting scan oui 0x7f9327e2c0
11-21 16:25:20.083   927  3029 D WifiHAL : Sending mac address OUI
11-21 16:25:20.084  5066  5066 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
11-21 16:25:20.086   927  3029 E native  : do suspend false
,11-21 16:25:20.093   927  3029 D wifi    : android_net_wifi_setLinkLayerStats: 1
,11-21 16:25:20.093   927   927 D RttService: SCAN_AVAILABLE : 3
11-21 16:25:20.093   927  3149 D RttService: DefaultState got{ when=-1ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,11-21 16:25:20.098   509   923 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,11-21 16:25:20.100   509   923 D CommandListener: Setting iface cfg
,11-21 16:25:20.102   927  3014 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '124 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 124 Failed to set address (No such device)'
11-21 16:25:20.103   927  3014 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,11-21 16:25:20.111   927  3014 D WifiNative-HAL: p2pGetDeviceAddress
,11-21 16:25:20.117   927  3014 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:70
11-21 16:25:20.117   927   942 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=189471 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=18 mControllerEnergyUsed=68 }
,11-21 16:25:20.295  5653  5737 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-21 16:25:20.295  5653  5737 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-21 16:25:20.295  5653  5737 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-21 16:25:20.295  5653  5737 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-21 16:25:20.295  5653  5737 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-21 16:25:20.295  5653  5737 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-21 16:25:20.295  5653  5737 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-21 16:25:20.295  5653  5737 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-21 16:25:20.295  5653  5737 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,11-21 16:25:20.301  5653  5737 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
,11-21 16:25:20.305  5653  5701 D BluetoothAdapter: enable(): BT is already enabled..!
,11-21 16:25:20.306   927  3933 D WifiService: setWifiEnabled: true pid=5653, uid=10077
,11-21 16:25:20.306   927  3933 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-21 16:25:20.307  5653  5701 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,11-21 16:25:20.308  5653  5701 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,11-21 16:25:20.308  5653  5701 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,11-21 16:25:20.308  5653  5701 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9fd0ebc removed from the list,
11-21 16:25:20.308  5653  5701 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-21 16:25:20.308  5653  5701 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ca4be45 removed from the list
11-21 16:25:20.309  5653  5701 D io.jxcore.node.ConnectivityMonitor: stop
11-21 16:25:20.312  5653  5701 I io.jxcore.node.IncomingSocketThreadTest: Starting test: testSetTcpPortNumber
11-21 16:25:20.315  5653  5701 I io.jxcore.node.IncomingSocketThreadTest: Starting test: testGetTcpPortNumber
11-21 16:25:20.316  5653  5701 I io.jxcore.node.IncomingSocketThreadTest: Starting test: testGetLocalHostPort
11-21 16:25:20.318  5653  5701 I io.jxcore.node.IncomingSocketThreadTest: Starting test: testConstructor
11-21 16:25:20.322  5653  5701 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityCreated
11-21 16:25:20.324  5653  5701 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
11-21 16:25:20.326  5653  5701 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityResumed
11-21 16:25:20.326  5653  5701 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
11-21 16:25:20.328  5653  5701 I io.jxcore.node.LifeCycleMonitorTest: Starting test: constructor
,11-21 16:25:20.334  5653  5701 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivitySaveInstanceState
,11-21 16:25:20.334  5653  5701 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@2ebe79 Bundle[{}]
,11-21 16:25:20.336  5653  5701 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testStartStop
,11-21 16:25:20.336  5653  5701 I io.jxcore.node.LifeCycleMonitor: start: OK
,11-21 16:25:20.337  5653  5701 I io.jxcore.node.LifeCycleMonitor: stop: OK
11-21 16:25:20.338  5653  5701 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityStarted
11-21 16:25:20.339  5653  5701 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
11-21 16:25:20.340  5653  5701 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityStopped
11-21 16:25:20.341  5653  5701 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,11-21 16:25:20.342  5653  5701 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityDestroyed
,11-21 16:25:20.343  5653  5701 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
11-21 16:25:20.344  5653  5701 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityPaused
,11-21 16:25:20.346  5653  5701 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,11-21 16:25:20.348  5653  5701 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testToString
,11-21 16:25:20.350  5653  5701 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testToJsonObject
,11-21 16:25:20.351  5653  5701 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testConstructorWithParameters
11-21 16:25:20.352  5653  5701 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testSetListeningOnPortNumber
,11-21 16:25:20.353  5653  5701 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testGetListeningOnPortNumber
,11-21 16:25:20.354  5653  5701 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testDefaultConstructor
11-21 16:25:20.356  5653  5701 I io.jxcore.node.OutgoingSocketThreadTest: Starting test: testClose
11-21 16:25:20.357  5653  5701 I io.jxcore.node.OutgoingSocketThreadTest: Starting test: testGetListeningOnPortNumber
11-21 16:25:20.358  5653  5701 I io.jxcore.node.OutgoingSocketThreadTest: Starting test: testConstructor
,11-21 16:25:20.360  5653  5701 I io.jxcore.node.SocketThreadBaseTest: Starting test: testGetListener
,11-21 16:25:20.361  5653  5701 I io.jxcore.node.SocketThreadBaseTest: Starting test: testSetPeerProperties
,11-21 16:25:20.362  5653  5701 I io.jxcore.node.SocketThreadBaseTest: Starting test: testClose
11-21 16:25:20.362  5653  5701 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 142)
,11-21 16:25:20.363  5653  5701 I io.jxcore.node.SocketThreadBaseTest: Starting test: testCloseLocalSocketAndStreams
,11-21 16:25:20.364  5653  5701 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
11-21 16:25:20.364  5653  5701 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 143)
11-21 16:25:20.365  5653  5701 I io.jxcore.node.SocketThreadBaseTest: Starting test: testGetPeerProperties
11-21 16:25:20.365  5653  5701 I io.jxcore.node.SocketThreadBaseTest: Starting test: testEquals
11-21 16:25:20.366  5653  5701 I io.jxcore.node.SocketThreadBaseTest: Starting test: testGetLocalHostAddressAsString
11-21 16:25:20.367  5653  5701 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-21 16:25:20.367  5653  5701 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f8da2cb added. We now have 3 listener(s)
,11-21 16:25:20.369  5653  5701 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
,11-21 16:25:20.369  5653  5701 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-21 16:25:20.369  5653  5701 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-21 16:25:20.369  5653  5701 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-21 16:25:20.369  5653  5701 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@aea5aa8 added. We now have 3 listener(s)
11-21 16:25:20.369  5653  5701 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-21 16:25:20.370  5653  5701 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,11-21 16:25:20.374  5653  5701 I io.jxcore.node.StartStopOperationHandlerTest: Starting test: testCancelCurrentOperation
,11-21 16:25:20.375  5653  5701 I io.jxcore.node.StartStopOperationHandlerTest: Starting test: testExecuteStopOperation
11-21 16:25:20.375  5653  5701 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 5
11-21 16:25:20.375  5653  5701 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 4 -> 5
11-21 16:25:20.375  5653  5701 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-62,5,main], id: 62
11-21 16:25:20.375  5653  5701 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-62,5,main], id: 62
11-21 16:25:20.375  5653  5701 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-62,5,main], id: 62
11-21 16:25:20.375  5653  5701 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
11-21 16:25:20.375  5653  5701 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
,11-21 16:25:20.376  5653  5701 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
11-21 16:25:20.376  5653  5701 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-21 16:25:20.376  5653  5701 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
,11-21 16:25:20.381  5653  5701 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,11-21 16:25:20.382  5653  5861 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
11-21 16:25:20.382  5653  5701 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
11-21 16:25:20.382  5653  5701 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
11-21 16:25:20.382  5653  5701 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
,11-21 16:25:20.382  5653  5701 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
11-21 16:25:20.382  5653  5653 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
11-21 16:25:20.383  5653  5701 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
11-21 16:25:20.383  5653  5861 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-21 16:25:20.384  5653  5701 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,11-21 16:25:20.384  5653  5701 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
11-21 16:25:20.384  5792  5792 W Binder_4: type=1400 audit(0.0:122): avc: denied { ioctl } for path="socket:[35858]" dev="sockfs" ino=35858 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-21 16:25:20.386  5653  5861 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
11-21 16:25:20.384  5792  5792 W Binder_4: type=1400 audit(0.0:123): avc: denied { ioctl } for path="socket:[35858]" dev="sockfs" ino=35858 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,11-21 16:25:20.389  5653  5701 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
,11-21 16:25:20.389  5653  5701 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-21 16:25:20.389  5653  5701 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
11-21 16:25:20.392  5653  5701 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-62,5,main], id: 62
11-21 16:25:20.392  5653  5701 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-21 16:25:20.393  5653  5701 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-21 16:25:20.393  5653  5701 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-21 16:25:20.393  5653  5701 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 5
11-21 16:25:20.394  5653  5701 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Current thread: Thread[Thread-62,5,main], id: 62
,11-21 16:25:20.394  5653  5701 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-62,5,main], id: 62
11-21 16:25:20.395  5653  5701 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
11-21 16:25:20.395  5653  5701 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: createAdvertiseDataToServiceData 
11-21 16:25:20.395  5653  5701 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-21 16:25:20.395  5653  5701 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 05 60 83 34 25 D7 D4
11-21 16:25:20.395  5653  5701 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[5, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-21 16:25:20.395  5653  5701 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: created AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[5, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,11-21 16:25:20.395  5653  5701 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: Current thread: Thread[Thread-62,5,main], id: 62
11-21 16:25:20.395  5653  5701 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: was started = false
11-21 16:25:20.395  5653  5701 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: advertiseData = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[5, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-21 16:25:20.395  5653  5701 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData finished: Current thread: Thread[Thread-62,5,main], id: 62
11-21 16:25:20.395  5653  5701 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = NOT_STARTEDCurrent thread: Thread[Thread-62,5,main], id: 62
11-21 16:25:20.396  5653  5701 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... adv data = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[5, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]Current thread: Thread[Thread-62,5,main], id: 62
,11-21 16:25:20.398  5653  5701 D BluetoothAdapter: STATE_ON
,11-21 16:25:20.402  5756  5793 D BtGatt.GattService: registerClient() - UUID=434e94da-185c-4347-9fbc-0622fd3ea42d
,11-21 16:25:20.403  5756  5772 D BtGatt.GattService: onClientRegistered() - UUID=434e94da-185c-4347-9fbc-0622fd3ea42d, clientIf=5
,11-21 16:25:20.404  5653  5664 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
,11-21 16:25:20.406  5756  5774 D BtGatt.AdvertiseManager: message : 0
,11-21 16:25:20.408  5756  5774 D BtGatt.AdvertiseManager: starting multi advertising
,11-21 16:25:20.411  5756  5772 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,11-21 16:25:20.413  5756  5772 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,11-21 16:25:20.414  5653  5701 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment Current thread: Thread[Thread-62,5,main], id: 62
,11-21 16:25:20.414  5653  5701 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTINGCurrent thread: Thread[Thread-62,5,main], id: 62
11-21 16:25:20.414  5653  5701 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,11-21 16:25:20.414  5653  5701 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged default (no call to listener). Current thread: Thread[Thread-62,5,main], id: 62
11-21 16:25:20.415  5653  5701 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-62,5,main], id: 62
11-21 16:25:20.415  5653  5701 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[Thread-62,5,main], id: 62
11-21 16:25:20.415  5653  5701 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[Thread-62,5,main], id: 62
11-21 16:25:20.415  5653  5701 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser started = true Current thread: Thread[Thread-62,5,main], id: 62
11-21 16:25:20.415  5653  5701 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-21 16:25:20.416  5653  5701 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-21 16:25:20.416  5653  5701 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-21 16:25:20.417  5653  5701 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-21 16:25:20.417  5653  5701 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-21 16:25:20.417  5653  5701 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-21 16:25:20.418  5653  5653 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
11-21 16:25:20.418  5653  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess : Current thread: Thread[main,5,main], id: 1
11-21 16:25:20.418  5653  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNINGCurrent thread: Thread[main,5,main], id: 1
11-21 16:25:20.418  5653  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
11-21 16:25:20.418  5653  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  true. Current thread: Thread[main,5,main], id: 1
11-21 16:25:20.418  5653  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[main,5,main], id: 1
11-21 16:25:20.418  5653  5653 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-21 16:25:20.418  5653  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-21 16:25:20.418  5653  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [ADVERTISING]
11-21 16:25:20.418  5653  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-21 16:25:20.418  5653  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-21 16:25:20.418  5653  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]Current thread: Thread[main,5,main], id: 1
11-21 16:25:20.418  5653  5653 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
11-21 16:25:2,0.418  5653  5653 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-21 16:25:20.421  5653  5653 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-21 16:25:20.421  5653  5653 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
11-21 16:25:20.421  5653  5653 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-21 16:25:20.421  5653  5653 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-21 16:25:20.421  5653  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-21 16:25:20.421  5653  5653 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,11-21 16:25:20.472   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-21 16:25:20.922  5653  5653 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
,11-21 16:25:20.923  5653  5653 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
11-21 16:25:20.923  5653  5653 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,11-21 16:25:21.473   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-21 16:25:22.474   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-21 16:25:23.148  5858  5858 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-21 16:25:23.152  5858  5858 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-21 16:25:23.156  5858  5858 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-21 16:25:23.209   927  3029 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
11-21 16:25:23.211   927  3029 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3
11-21 16:25:23.211   927  3029 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-21 16:25:23.224   927  3029 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=0
,11-21 16:25:23.258   927  3029 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=0
,11-21 16:25:23.263  5858  5858 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,11-21 16:25:23.474   537   537 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,11-21 16:25:23.713  5858  5858 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,11-21 16:25:23.746  5858  5858 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,11-21 16:25:23.747  5858  5858 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,11-21 16:25:23.756   927  3029 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,11-21 16:25:23.756   927  3029 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
11-21 16:25:23.756   927  3043 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,11-21 16:25:23.775   927  3029 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-21 16:25:23.788   509   923 D CommandListener: Setting iface cfg
,11-21 16:25:23.793   927  3029 D WifiStateMachine: Start Dhcp Watchdog 2
,11-21 16:25:23.799   927  5866 D DhcpClient: Receive thread started
,11-21 16:25:23.804   927  3043 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-21 16:25:23.804   927  3029 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
11-21 16:25:23.805   927  3043 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
,11-21 16:25:23.886   927  3029 E native  : do suspend false
,11-21 16:25:23.904   927  5865 D DhcpClient: Broadcasting DHCPDISCOVER
,11-21 16:25:23.919   927  5866 D DhcpClient: Received packet: 60:83:34:25:d7:70 OFFER, ip /192.168.1.109, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172647, domain null
11-21 16:25:23.920  5653  5701 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
,11-21 16:25:23.920  5653  5701 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
11-21 16:25:23.920   927  5865 D DhcpClient: Got pending lease: IP address 192.168.1.109/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172647 seconds
11-21 16:25:23.920  5653  5701 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
11-21 16:25:23.920  5653  5701 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
11-21 16:25:23.920  5653  5701 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
,11-21 16:25:23.921  5653  5701 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-21 16:25:23.921  5653  5861 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
11-21 16:25:23.921  5653  5861 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
11-21 16:25:23.921  5653  5701 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
11-21 16:25:23.922  5653  5861 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
11-21 16:25:23.922  5653  5701 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
11-21 16:25:23.922  5653  5701 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
11-21 16:25:23.922  5653  5701 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-21 16:25:23.922  5653  5701 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
11-21 16:25:23.922  5653  5701 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-21 16:25:23.922  5653  5653 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
11-21 16:25:23.923  5653  5701 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-62,5,main], id: 62
11-21 16:25:23.923  5653  5701 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-62,5,main], id: 62
11-21 16:25:23.923  5653  5701 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-62,5,main], id: 62
11-21 16:25:23.924  5653  5701 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-62,5,main], id: 62
11-21 16:25:23.924   927  5865 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.109 serverid=192.168.1.1
11-21 16:25:23.926  5653  5701 D BluetoothAdapter: STATE_ON
11-21 16:25:23.926  5653  5701 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-21 16:25:23.929  5653  5701 D BluetoothAdapter: STATE_ON
11-21 16:25:23.929  5653  5701 D BluetoothLeScanner: could not find callback wrapper
,11-21 16:25:23.929  5653  5701 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-21 16:25:23.930  5653  5701 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-62,5,main], id: 62
11-21 16:25:23.930  5653  5701 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-62,5,main], id: 62
11-21 16:25:23.930  5653  5701 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-62,5,main], id: 62
11-21 16:25:23.931  5653  5701 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
11-21 16:25:23.931  5653  5701 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-62,5,main], id: 62
11-21 16:25:23.933  5756  5774 D BtGatt.AdvertiseManager: message : 1
11-21 16:25:23.935  5756  5774 D BtGatt.AdvertiseManager: stop advertise for client 5
,11-21 16:25:23.951  5756  5772 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
,11-21 16:25:23.951  5756  5772 D BtGatt.GattService: Client app is not null!
,11-21 16:25:23.953  5756  5784 D BtGatt.GattService: unregisterClient() - clientIf=5
11-21 16:25:23.954  5653  5701 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-21 16:25:23.954  5653  5701 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTEDCurrent thread: Thread[Thread-62,5,main], id: 62
11-21 16:25:23.954  5653  5701 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
11-21 16:25:23.954  5653  5701 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  false. Current thread: Thread[Thread-62,5,main], id: 62
,11-21 16:25:23.955  5653  5701 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-62,5,main], id: 62
,11-21 16:25:23.955  5653  5701 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-62,5,main], id: 62
11-21 16:25:23.955  5653  5701 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,11-21 16:25:23.955  5653  5701 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-21 16:25:23.957  5653  5701 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
11-21 16:25:23.960   927  5866 D DhcpClient: Received packet: 60:83:34:25:d7:70 ACK: your new IP /192.168.1.109, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,11-21 16:25:23.960   927  5865 D DhcpClient: Confirmed lease: IP address 192.168.1.109/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,11-21 16:25:23.960  5653  5701 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-21 16:25:23.961   509   923 D CommandListener: Setting iface cfg
11-21 16:25:23.963  5653  5701 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-21 16:25:23.964  5653  5701 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-21 16:25:23.964  5653  5701 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-21 16:25:23.964  5653  5701 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-21 16:25:23.965  5653  5653 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-21 16:25:23.965  5653  5653 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
11-21 16:25:23.965  5653  5653 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
11-21 16:25:23.965  5653  5653 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-21 16:25:23.966  5653  5653 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-21 16:25:23.966  5653  5653 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-21 16:25:23.966  5653  5653 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-21 16:25:23.966  5653  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-21 16:25:23.966  5653  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
,11-21 16:25:23.966  5653  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [ADVERTISING]
11-21 16:25:23.966  5653  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-21 16:25:23.966   927  3029 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
11-21 16:25:23.966  5653  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-21 16:25:23.967  5653  5653 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
11-21 16:25:23.967  5653  5653 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-21 16:25:23.969  5653  5653 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-21 16:25:23.969  5653  5653 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-21 16:25:23.969  5653  5653 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-21 16:25:23.970  5653  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
,11-21 16:25:23.970  5653  5653 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-21 16:25:23.970  5653  5701 I io.jxcore.node.StartStopOperationHandlerTest: Starting test: testCheckCurrentOperationStatus
11-21 16:25:23.970  5653  5701 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-21 16:25:23.971  5653  5701 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-21 16:25:23.972  5653  5701 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
11-21 16:25:23.972  5653  5701 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
11-21 16:25:23.972  5653  5701 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-21 16:25:23.972  5653  5701 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
11-21 16:25:23.972   927  5865 D DhcpClient: Scheduling renewal in 86399s
,11-21 16:25:23.974  5653  5701 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,11-21 16:25:23.979   927  3029 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
11-21 16:25:23.980   927  3029 D WifiConfigStore: No blacklist allowed without epno enabled
11-21 16:25:23.980  5653  5701 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-21 16:25:23.980  5653  5701 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-21 16:25:23.980  5653  5701 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
11-21 16:25:23.980   927  3043 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
11-21 16:25:23.981   927  3043 D ConnectivityService: Adding iface wlan0 to network 101
11-21 16:25:23.981   927  3029 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,11-21 16:25:23.985  5653  5701 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-62,5,main], id: 62
,11-21 16:25:23.985  5653  5701 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-21 16:25:23.986  5653  5701 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-21 16:25:23.987  5653  5701 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-21 16:25:23.987  5653  5701 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 5
,11-21 16:25:23.990  5653  5701 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
,11-21 16:25:23.994  5653  5701 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
11-21 16:25:23.994  5653  5701 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-62,5,main], id: 62
11-21 16:25:23.994  5653  5701 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
11-21 16:25:23.994  5653  5701 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
11-21 16:25:23.994  5653  5701 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
11-21 16:25:23.995  5653  5701 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
11-21 16:25:23.995  5653  5701 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-62,5,main], id: 62
11-21 16:25:23.996  5653  5701 D BluetoothAdapter: STATE_ON
,11-21 16:25:23.998  5756  5767 D BtGatt.GattService: registerClient() - UUID=4c6e0499-fb1a-41c9-a3c4-d363f1f9a71a
11-21 16:25:23.999  5756  5772 D BtGatt.GattService: onClientRegistered() - UUID=4c6e0499-fb1a-41c9-a3c4-d363f1f9a71a, clientIf=5
,11-21 16:25:23.999  5653  5663 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,11-21 16:25:24.000  5756  5793 D BtGatt.GattService: start scan with filters
,11-21 16:25:24.003  5653  5701 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
11-21 16:25:24.004  5653  5701 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-62,5,main], id: 62
,11-21 16:25:24.004  5653  5701 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,11-21 16:25:24.004  5653  5701 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-62,5,main], id: 62
11-21 16:25:24.004  5653  5701 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-21 16:25:24.004  5653  5653 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-21 16:25:24.005  5653  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-21 16:25:24.005  5653  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
11-21 16:25:24.005  5653  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-21 16:25:24.005  5653  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-21 16:25:24.005  5653  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
11-21 16:25:24.005  5653  5653 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
11-21 16:25:24.006  5756  5775 D BtGatt.ScanManager: handling starting scan
11-21 16:25:24.008  5756  5775 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5411672
11-21 16:25:24.009  5653  5701 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-21 16:25:24.009  5653  5701 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-21 16:25:24.012  5653  5701 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-21 16:25:24.012  5653  5701 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
11-21 16:25:24.012  5653  5701 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-21 16:25:24.012  5653  5701 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-21 16:25:24.012  5653  5653 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-21 16:25:24.015  5756  5772 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
11-21 16:25:24.015  5756  5772 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-21 16:25:24.015  5653  5653 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-21 16:25:24.016  5756  5775 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
11-21 16:25:24.015  5653  5653 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-21 16:25:24.016  5653  5653 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-21 16:25:24.016  5653  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-21 16:25:24.016  5653  5653 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
11-21 16:25:24.019   927  3043 E ConnectivityService: Unexpected mtu value: 0, wlan0
11-21 16:25:24.019   927  3043 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
11-21 16:25:24.020   927  3043 D ConnectivityService:, Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
11-21 16:25:24.021  5756  5772 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
11-21 16:25:24.022  5756  5772 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-21 16:25:24.022   927  3043 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,11-21 16:25:24.023  5756  5775 D BtGatt.ScanManager: Starting BLE batch scan
11-21 16:25:24.023  5756  5775 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
11-21 16:25:24.024   927  3043 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
11-21 16:25:24.032   927  3043 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
11-21 16:25:24.033  5756  5772 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
11-21 16:25:24.033  5756  5772 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-21 16:25:24.037   927  3043 D ConnectivityService: scheduleUnvalidatedPrompt 101
11-21 16:25:24.037   927  3043 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
11-21 16:25:24.037   927  3043 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
11-21 16:25:24.037   927  3043 D ConnectivityService:    accepting network in place of null
11-21 16:25:24.038   927  3029 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
,11-21 16:25:24.038   927  3029 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
11-21 16:25:24.038   927  3043 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d770/64,192.168.1.109/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -56]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
11-21 16:25:24.039  5756  5772 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
11-21 16:25:24.040  5756  5772 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-21 16:25:24.059   509   923 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-21 16:25:24.076   509   923 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-21 16:25:24.079   927  3043 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,11-21 16:25:24.079   927  3043 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
11-21 16:25:24.079  3801  3937 W QCNEJ   : |CORE| network available: 101
11-21 16:25:24.080   927  3043 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
,11-21 16:25:24.080  3801  3937 W QCNEJ   : |CORE| onAvailable: bind the process to WIFI
,11-21 16:25:24.081   927   944 D Tethering: MasterInitialState.processMessage what=3
11-21 16:25:24.081  3801  3937 W QCNEJ   : |CORE| newLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d770/64,192.168.1.109/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}
11-21 16:25:24.082  3801  3937 W QCNEJ   : |CORE| curLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d770/64,192.168.1.109/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,11-21 16:25:24.093  5091  5115 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
,11-21 16:25:24.094  5091  5115 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
11-21 16:25:24.094  5091  5115 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,1,0,0
11-21 16:25:24.094  5091  5115 E SarControlService: no key has been found,reset the power
11-21 16:25:24.094  5091  5125 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
11-21 16:25:24.094  5091  5125 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
11-21 16:25:24.094  5091  5125 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
11-21 16:25:24.094  5116  5116 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
11-21 16:25:24.095  5116  5116 D QcrilMsgTunnelSocket: [1004] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
,11-21 16:25:24.096  5091  5125 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
,11-21 16:25:24.096  5091  5125 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
,11-21 16:25:24.096  5091  5125 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
11-21 16:25:24.096  5116  5116 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
11-21 16:25:24.097  5116  5116 D QcrilMsgTunnelSocket: [1005] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
11-21 16:25:24.099  4028  4028 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
11-21 16:25:24.101  5116  5130 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@26cecde HexData = [00000000ec03000000000000ffffffff]
11-21 16:25:24.101  5116  5130 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
,11-21 16:25:24.101  5116  5130 D QcrilMsgTunnelSocket: [1004] < OEM_HOOK_RAW [null]
11-21 16:25:24.102  4012  4012 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
11-21 16:25:24.103  5116  5130 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@26cecde HexData = [00000000ed03000000000000ffffffff]
11-21 16:25:24.103  5116  5130 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-21 16:25:24.103  5116  5130 D QcrilMsgTunnelSocket: [1005] < OEM_HOOK_RAW [null]
11-21 16:25:24.103  4028  4028 D SystemUpdateService: onCreate
11-21 16:25:24.104  5116  5116 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
11-21 16:25:24.105  5091  5101 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
,11-21 16:25:24.105  5116  5116 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
11-21 16:25:24.105  5091  5102 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
,11-21 16:25:24.109  4028  4028 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,11-21 16:25:24.117   927  5864 D NetlinkSocketObserver: NeighborEvent{elapsedMs=193472, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,11-21 16:25:24.120  4028  4028 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,11-21 16:25:24.124  4028  5439 I iu.UploadsManager: num queued entries: 0
,11-21 16:25:24.125  4028  5439 I iu.UploadsManager: num updated entries: 0
,11-21 16:25:24.127  4028  5877 I SystemUpdateService: active receiver: enabled
,11-21 16:25:24.129  4028  4028 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,11-21 16:25:24.131  4028  4028 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,11-21 16:25:24.133  5828  5828 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,11-21 16:25:24.136  5828  5828 D SprintDMHelper: simOperator: 
11-21 16:25:24.136  5828  5828 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,11-21 16:25:24.160  4028  5439 I iu.SyncManager: NEXT; no task
,11-21 16:25:24.162  4028  5877 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,11-21 16:25:24.180  4028  5877 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,11-21 16:25:24.180  4028  5877 I SystemUpdateService: now status is 0 (complete)
11-21 16:25:24.180  4028  5877 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
11-21 16:25:24.180  4028  5877 I SystemUpdateService: file has been verified
11-21 16:25:24.180  4028  5877 I SystemUpdateService: OTA package size = 21989297
,11-21 16:25:24.186  4028  5877 I SystemUpdateService: showing system update notification
,11-21 16:25:24.194   927  5863 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.214.238,2a00:1450:400d:803::200e
,11-21 16:25:24.195   927   927 V NotificationService: pkg=com.google.android.gms canInterrupt=false intercept=true
,11-21 16:25:24.196  4028  4028 D SystemUpdateService: onDestroy
,11-21 16:25:24.290  5066  5881 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,11-21 16:25:24.290   927  5863 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Mon, 21 Nov 2016 15:25:24 GMT], X-Android-Received-Millis=[1479741924290], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1479741924247]}
11-21 16:25:24.291   927  3043 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
11-21 16:25:24.291   927  3043 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation  passed
11-21 16:25:24.291   927  3043 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
11-21 16:25:24.294   927  3043 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,11-21 16:25:24.517  5653  5653 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,11-21 16:25:24.517  5653  5653 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
11-21 16:25:24.517  5653  5653 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,11-21 16:25:24.544  5756  5756 D BtGatt.ScanManager: awakened up at time 193898
,11-21 16:25:24.545  5756  5775 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-21 16:25:24.558  5756  5772 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,11-21 16:25:24.558  5756  5772 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-21 16:25:24.562  5653  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: onBatchScanResults: results count  = 0. Current thread: Thread[main,5,main], id: 1
,11-21 16:25:25.081   927  3043 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,11-21 16:25:26.825   927  3043 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-21 16:25:27.014  5653  5701 I io.jxcore.node.StartStopOperationHandlerTest: Starting test: testExecuteStartOperation
,11-21 16:25:27.015  5653  5701 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 6
,11-21 16:25:27.015  5653  5701 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 5 -> 6
11-21 16:25:27.016  5653  5701 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-62,5,main], id: 62
11-21 16:25:27.016  5653  5701 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-62,5,main], id: 62
11-21 16:25:27.016  5653  5701 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-62,5,main], id: 62
11-21 16:25:27.017  5653  5701 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
11-21 16:25:27.017  5653  5701 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Manufacturer ID: 7413
11-21 16:25:27.017  5653  5701 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad length and type: 533
11-21 16:25:27.017  5653  5701 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad extra information: 6
11-21 16:25:27.017  5653  5701 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
11-21 16:25:27.017  5653  5701 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 2
11-21 16:25:27.017  5653  5701 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 3
11-21 16:25:27.017  5653  5701 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 2
11-21 16:25:27.017  5653  5701 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
11-21 16:25:27.017  5653  5701 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Current thread: Thread[Thread-62,5,main], id: 62
,11-21 16:25:27.017  5653  5701 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 6
11-21 16:25:27.017  5653  5701 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: advertiserWasStarted false Current thread: Thread[Thread-62,5,main], id: 62
11-21 16:25:27.017  5653  5701 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-62,5,main], id: 62
11-21 16:25:27.018  5653  5701 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-21 16:25:27.018  5653  5701 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-21 16:25:27.018  5653  5701 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: scannerWasStarted true Current thread: Thread[Thread-62,5,main], id: 62
11-21 16:25:27.018  5653  5701 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: stop scanner Current thread: Thread[Thread-62,5,main], id: 62
11-21 16:25:27.019  5653  5701 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-62,5,main], id: 62
11-21 16:25:27.021  5653  5701 D BluetoothAdapter: STATE_ON
11-21 16:25:27.022  5756  5766 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
11-21 16:25:27.023  5653  5701 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-21 16:25:27.024  5756  5775 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-21 16:25:27.026  5653  5701 D BluetoothAdapter: STATE_ON
,11-21 16:25:27.030  5756  5792 D BtGatt.GattService: stopScan() - queue size =1
11-21 16:25:27.032  5756  5767 D BtGatt.GattService: unregisterClient() - clientIf=5
11-21 16:25:27.034  5653  5701 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-21 16:25:27.034  5756  5756 D BtGatt.ScanManager: awakened up at time 196388
11-21 16:25:27.034  5653  5701 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-62,5,main], id: 62
11-21 16:25:27.034  5653  5701 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
11-21 16:25:27.035  5653  5701 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-62,5,main], id: 62
11-21 16:25:27.035  5653  5701 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-21 16:25:27.035  5653  5701 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: start scanner Current thread: Thread[Thread-62,5,main], id: 62
11-21 16:25:27.035  5653  5701 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-62,5,main], id: 62
11-21 16:25:27.035  5653  5701 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
11-21 16:25:27.035  5653  5701 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
11-21 16:25:27.035  5653  5701 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
11-21 16:25:27.036  5653  5701 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,11-21 16:25:27.036  5653  5701 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-62,5,main], id: 62
11-21 16:25:27.038  5653  5701 D BluetoothAdapter: STATE_ON
,11-21 16:25:27.043  5756  5767 D BtGatt.GattService: registerClient() - UUID=8d57d0ac-07c9-4a81-b07f-e95fede4e44c
11-21 16:25:27.044  5756  5772 D BtGatt.GattService: onClientRegistered() - UUID=8d57d0ac-07c9-4a81-b07f-e95fede4e44c, clientIf=5
,11-21 16:25:27.045  5653  5664 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,11-21 16:25:27.046  5756  5766 D BtGatt.GattService: start scan with filters
11-21 16:25:27.050  5756  5772 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=2
,11-21 16:25:27.050  5756  5772 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-21 16:25:27.050  5756  5772 D BtGatt.GattService: current time is 196404974140
11-21 16:25:27.050  5756  5772 D BtGatt.GattService: Batch record : [35, 97, 126, -92, 22, -56, 1, -128, -80, 46, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, -46, -4, -117, 6, 105, -37, 1, -128, -81, 43, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 0]
,11-21 16:25:27.052  5653  5701 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
11-21 16:25:27.052  5756  5772 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,11-21 16:25:27.052  5653  5701 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-62,5,main], id: 62
11-21 16:25:27.052  5653  5701 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
11-21 16:25:27.052  5653  5701 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-62,5,main], id: 62
11-21 16:25:27.052  5653  5701 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: start scanner started = true Current thread: Thread[Thread-62,5,main], id: 62
,11-21 16:25:27.052  5653  5653 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-21 16:25:27.053  5653  5701 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
11-21 16:25:27.053  5653  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-21 16:25:27.053  5653  5701 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
11-21 16:25:27.053  5653  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
11-21 16:25:27.053  5653  5701 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
11-21 16:25:27.053  5653  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
11-21 16:25:27.053  5653  5701 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-21 16:25:27.053  5653  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-21 16:25:27.053  5653  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-21 16:25:27.053  5756  5772 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74]
11-21 16:25:27.054  5653  5701 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
11-21 16:25:27.054  5653  5701 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
11-21 16:25:27.054  5653  5701 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
11-21 16:25:27.054  5653  5701 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
11-21 16:25:27.054  5653  5701 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
11-21 16:25:27.055  5653  5653 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
11-21 16:25:27.055  5653  5701 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: true
11-21 16:25:27.056  5653  5701 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-21 16:25:27.056  5653  5701 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-21 16:25:27.057  5653  5889 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
11-21 16:25:27.058  5653  5889 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-21 16:25:27.059  5756  5772 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
11-21 16:25:27.059  5756  5772 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-21 16:25:27.060  5756  5775 D BtGatt.ScanManager: stopping BLe Batch
11-21 16:25:27.061  5653  5889 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,11-21 16:25:27.057  5784  5784 W Binder_3: type=1400 audit(0.0:124): avc: denied { ioctl } for path="socket:[31435]" dev="sockfs" ino=31435 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-21 16:25:27.057  5784  5784 W Binder_3: type=1400 audit(0.0:125): avc: denied { ioctl } for path="socket:[31435]" dev="sockfs" ino=31435 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,11-21 16:25:27.064  5653  5701 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser : Current thread: Thread[Thread-62,5,main], id: 62
11-21 16:25:27.064  5653  5701 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Current thread: Thread[Thread-62,5,main], id: 62
11-21 16:25:27.064  5653  5701 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-62,5,main], id: 62
11-21 16:25:27.064  5653  5701 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
,11-21 16:25:27.064  5653  5701 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: createAdvertiseDataToServiceData 
11-21 16:25:27.064  5653  5701 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-21 16:25:27.064  5653  5701 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 06 60 83 34 25 D7 D4
,11-21 16:25:27.064  5653  5701 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[6, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,11-21 16:25:27.064  5653  5701 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: created AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[6, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-21 16:25:27.065  5653  5701 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: Current thread: Thread[Thread-62,5,main], id: 62
11-21 16:25:27.065  5653  5701 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: was started = false
11-21 16:25:27.065  5653  5701 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: advertiseData = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[6, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-21 16:25:27.065  5653  5701 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData finished: Current thread: Thread[Thread-62,5,main], id: 62
11-21 16:25:27.065  5653  5701 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = NOT_STARTEDCurrent thread: Thread[Thread-62,5,main], id: 62
,11-21 16:25:27.065  5653  5701 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... adv data = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[6, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]Current thread: Thread[Thread-62,5,main], id: 62
11-21 16:25:27.066  5756  5772 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
11-21 16:25:27.066  5756  5772 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-21 16:25:27.066  5756  5775 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
11-21 16:25:27.066  5653  5701 D BluetoothAdapter: STATE_ON
11-21 16:25:27.069  5756  5767 D BtGatt.GattService: registerClient() - UUID=ba6be604-2ec6-4dd8-9cd5-feff824958ee
11-21 16:25:27.070  5756  5772 D BtGatt.GattService: onClientRegistered() - UUID=ba6be604-2ec6-4dd8-9cd5-feff824958ee, clientIf=6
,11-21 16:25:27.070  5653  5663 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
11-21 16:25:27.071  5756  5774 D BtGatt.AdvertiseManager: message : 0
11-21 16:25:27.071  5756  5772 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-21 16:25:27.071  5756  5772 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-21 16:25:27.073  5756  5775 D BtGatt.ScanManager: handling starting scan
,11-21 16:25:27.075  5756  5774 D BtGatt.AdvertiseManager: starting multi advertising
11-21 16:25:27.077  5756  5772 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
11-21 16:25:27.077  5756  5772 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-21 16:25:27.077  5756  5775 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,11-21 16:25:27.084  5756  5772 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0
,11-21 16:25:27.088  5756  5772 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
,11-21 16:25:27.089  5756  5772 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-21 16:25:27.089  5756  5775 D BtGatt.ScanManager: Starting BLE batch scan
11-21 16:25:27.089  5756  5775 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,11-21 16:25:27.092  5756  5772 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0
,11-21 16:25:27.093  5653  5701 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment Current thread: Thread[Thread-62,5,main], id: 62
,11-21 16:25:27.093  5653  5701 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTINGCurrent thread: Thread[Thread-62,5,main], id: 62
11-21 16:25:27.093  5653  5701 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
11-21 16:25:27.093  5653  5701 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged default (no call to listener). Current thread: Thread[Thread-62,5,main], id: 62
11-21 16:25:27.093  5653  5701 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-62,5,main], id: 62
11-21 16:25:27.093  5653  5701 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[Thread-62,5,main], id: 62
11-21 16:25:27.093  5653  5701 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[Thread-62,5,main], id: 62
11-21 16:25:27.093  5653  5701 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser started = true Current thread: Thread[Thread-62,5,main], id: 62
11-21 16:25:27.093  5653  5701 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser: advertiser is started. Current thread: Thread[Thread-62,5,main], id: 62
11-21 16:25:27.093  5653  5701 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-62,5,main], id: 62
,11-21 16:25:27.093  5653  5701 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-62,5,main], id: 62
11-21 16:25:27.093  5653  5701 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Already running
11-21 16:25:27.093  5653  5701 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser: adv = true, disc = true
11-21 16:25:27.093  5653  5701 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-21 16:25:27.095  5653  5701 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-21 16:25:27.095  5653  5701 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-21 16:25:27.097  5653  5701 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-21 16:25:27.097  5653  5701 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
,11-21 16:25:27.097  5653  5701 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-21 16:25:27.097  5653  5653 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
,11-21 16:25:27.097  5653  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess : Current thread: Thread[main,5,main], id: 1
,11-21 16:25:27.097  5653  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNINGCurrent thread: Thread[main,5,main], id: 1
11-21 16:25:27.097  5653  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
11-21 16:25:27.097  5653  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  true. Current thread: Thread[main,5,main], id: 1
11-21 16:25:27.097  5653  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[main,5,main], id: 1
11-21 16:25:27.097  5653  5653 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-21 16:25:27.097  5653  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-21 16:25:27.098  5653  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING, ADVERTISING]
11-21 16:25:27.098  5653  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
11-21 16:25:27.098  5653  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
,11-21 16:25:27.098  5653  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [SCANNING, ADVERTISING]Current thread: Thread[main,5,main], id: 1
11-21 16:25:27.098  5653  5653 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [SCANNING, ADVERTISING]
11-21 16:25:27.098  5653  5653 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-21 16:25:27.100  5653  5653 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-21 16:25:27.100  5653  5653 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: true
11-21 16:25:27.100  5653  5653 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-21 16:25:27.100  5653  5653 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-21 16:25:27.100  5653  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-21 16:25:27.100  5653  5653 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: true
11-21 16:25:27.101  5756  5772 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
11-21 16:25:27.101  5756  5772 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-21 16:25:27.105  5756  5772 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
11-21 16:25:27.105  5756  5772 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-21 16:25:27.601  5653  5653 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: true
,11-21 16:25:27.602  5653  5653 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
11-21 16:25:27.602  5653  5653 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,11-21 16:25:30.100  5653  5701 I io.jxcore.node.StartStopOperationHandlerTest: Starting test: testConstructor
11-21 16:25:30.101  5653  5701 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-21 16:25:30.101  5653  5701 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
11-21 16:25:30.101  5653  5701 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
11-21 16:25:30.101  5653  5701 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
11-21 16:25:30.102  5653  5701 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-21 16:25:30.102  5653  5889 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
11-21 16:25:30.102  5653  5889 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
11-21 16:25:30.102  5653  5701 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
11-21 16:25:30.102  5653  5889 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
11-21 16:25:30.102  5653  5701 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
,11-21 16:25:30.103  5653  5653 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
11-21 16:25:30.104  5653  5653 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-21 16:25:30.105  5653  5653 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
,11-21 16:25:30.104  5653  5701 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,11-21 16:25:30.106  5653  5701 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f8da2cb removed from the list
11-21 16:25:30.106  5653  5701 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-21 16:25:30.106  5653  5701 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-21 16:25:30.106  5653  5701 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
11-21 16:25:30.106  5653  5701 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-21 16:25:30.107  5653  5701 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-62,5,main], id: 62
11-21 16:25:30.107  5653  5701 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-62,5,main], id: 62
,11-21 16:25:30.107  5653  5701 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-62,5,main], id: 62
11-21 16:25:30.107  5653  5701 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
11-21 16:25:30.108  5653  5701 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-62,5,main], id: 62
,11-21 16:25:30.109  5653  5701 D BluetoothAdapter: STATE_ON
11-21 16:25:30.110  5756  5767 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
11-21 16:25:30.111  5653  5701 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-21 16:25:30.112  5756  5775 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-21 16:25:30.112  5653  5701 D BluetoothAdapter: STATE_ON
,11-21 16:25:30.114  5756  5793 D BtGatt.GattService: stopScan() - queue size =1
,11-21 16:25:30.116  5756  5792 D BtGatt.GattService: unregisterClient() - clientIf=5
11-21 16:25:30.116  5653  5701 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-21 16:25:30.117  5653  5701 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-62,5,main], id: 62
11-21 16:25:30.117  5653  5701 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
11-21 16:25:30.117  5653  5701 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-62,5,main], id: 62
11-21 16:25:30.117  5653  5701 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-62,5,main], id: 62
11-21 16:25:30.117  5653  5701 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-62,5,main], id: 62
11-21 16:25:30.118  5653  5701 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
11-21 16:25:30.118  5653  5701 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-62,5,main], id: 62
11-21 16:25:30.120  5756  5756 D BtGatt.ScanManager: awakened up at time 199474
11-21 16:25:30.120  5756  5774 D BtGatt.AdvertiseManager: message : 1
11-21 16:25:30.122  5756  5774 D BtGatt.AdvertiseManager: stop advertise for client 6
,11-21 16:25:30.132  5756  5772 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
,11-21 16:25:30.132  5756  5772 D BtGatt.GattService: Client app is not null!
,11-21 16:25:30.134  5756  5793 D BtGatt.GattService: unregisterClient() - clientIf=6
11-21 16:25:30.134  5653  5701 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,11-21 16:25:30.135  5653  5701 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTEDCurrent thread: Thread[Thread-62,5,main], id: 62
,11-21 16:25:30.135  5653  5701 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
11-21 16:25:30.135  5653  5701 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  false. Current thread: Thread[Thread-62,5,main], id: 62
11-21 16:25:30.135  5653  5701 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-62,5,main], id: 62
11-21 16:25:30.135  5653  5701 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-62,5,main], id: 62
11-21 16:25:30.135  5653  5701 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-21 16:25:30.136  5653  5701 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-21 16:25:30.137  5653  5701 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
11-21 16:25:30.137  5653  5701 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-21 16:25:30.139  5653  5701 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-21 16:25:30.139  5653  5701 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-21 16:25:30.139  5653  5701 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-21 16:25:30.139  5653  5701 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-21 16:25:30.140  5653  5701 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@aea5aa8 removed from the list
11-21 16:25:30.140  5653  5653 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-21 16:25:30.140  5653  5701 D io.jxcore.node.ConnectivityMonitor: stop
11-21 16:25:30.140  5653  5653 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-21 16:25:30.140  5653  5653 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-21 16:25:30.140  5653  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-21 16:25:30.140  5653  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-21 16:25:30.140  5653  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING, ADVERTISING]
11-21 16:25:30.140  5653  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-21 16:25:30.140  5653  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING, ADVERTISING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-21 16:25:30.140  5653  5653 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING, ADVERTISING] -> [NOT_STARTED]
11-21 16:25:30.141  5653  5653 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-21 16:25:30.141  5653  5701 I io.jxcore.node.StartStopOperationTest: Starting test: testIsTargetState
11-21 16:25:30.141  5653  5701 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_,STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
11-21 16:25:30.142  5653  5701 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
11-21 16:25:30.142  5653  5701 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
11-21 16:25:30.142  5653  5701 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-21 16:25:30.142  5653  5701 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
11-21 16:25:30.142  5653  5653 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-21 16:25:30.142  5653  5701 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
11-21 16:25:30.142  5653  5653 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-21 16:25:30.142  5653  5653 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-21 16:25:30.142  5653  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-21 16:25:30.143  5653  5653 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-21 16:25:30.143  5653  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-21 16:25:30.143  5653  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-21 16:25:30.143  5653  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-21 16:25:30.143  5653  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-21 16:25:30.143  5653  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
,11-21 16:25:30.143  5653  5653 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-21 16:25:30.143  5653  5701 I io.jxcore.node.StartStopOperationTest: Starting test: testCreateStartOperation
11-21 16:25:30.145  5653  5701 I io.jxcore.node.StartStopOperationTest: Starting test: testGetShouldStartOrStopListeningToAdvertisementsOnly
11-21 16:25:30.146  5653  5701 I io.jxcore.node.StartStopOperationTest: Starting test: testIsStartOperation
11-21 16:25:30.147  5653  5701 I io.jxcore.node.StartStopOperationTest: Starting test: testToString
11-21 16:25:30.148  5653  5701 I io.jxcore.node.StartStopOperationTest: Starting test: testCreateStopOperation
11-21 16:25:30.149  5653  5701 I io.jxcore.node.StartStopOperationTest: Starting test: testSetOperationExecutedTime
11-21 16:25:30.150  5653  5701 I io.jxcore.node.StartStopOperationTest: Starting test: testGetOperationExecutedTime
11-21 16:25:30.151  5653  5701 I io.jxcore.node.StartStopOperationTest: Starting test: testGetCallback
11-21 16:25:30.159  5756  5772 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=6
,11-21 16:25:30.159  5756  5772 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-21 16:25:30.159  5756  5772 D BtGatt.GattService: current time is 199513923616
11-21 16:25:30.159  5756  5772 D BtGatt.GattService: Batch record : [37, -47, 14, -113, 116, -46, 1, -128, -88, 36, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 116, -43, -111, -91, -20, -29, 1, -128, -81, 34, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 81, 34, 97, 112, -14, -5, 1, -128, -84, 31, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 71, -122, -77, 84, 69, -12, 1, -128, -95, 29, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 35, 97, 126, -92, 22, -56, 1, -128, -94, 28, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, -46, -4, -117, 6, 105, -37, 1, -128, -93, 25, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
11-21 16:25:30.160  5756  5772 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,11-21 16:25:30.160  5756  5772 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
11-21 16:25:30.160  5756  5772 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
11-21 16:25:30.161  5756  5772 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
11-21 16:25:30.161  5756  5772 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
11-21 16:25:30.161  5756  5772 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
11-21 16:25:30.161  5756  5772 E BtGatt.ContextMap: Context not found for ID 5
,11-21 16:25:30.169  5756  5772 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
,11-21 16:25:30.169  5756  5772 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-21 16:25:30.169  5756  5775 D BtGatt.ScanManager: stopping BLe Batch
,11-21 16:25:30.176  5756  5772 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,11-21 16:25:30.176  5756  5772 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-21 16:25:30.176  5756  5775 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-21 16:25:30.185  5756  5772 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,11-21 16:25:30.185  5756  5772 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-21 16:25:30.644  5653  5653 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-21 16:25:31.323   927  3029 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 11, 13 -> obsolete
,11-21 16:25:32.042   927  3043 D ConnectivityService: handlePromptUnvalidated 101
,11-21 16:25:32.155  5653  5701 I StreamCopyingThreadTest: Starting test: testCopyDataAndCloseConnection
,11-21 16:25:32.289  5653  5891 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 156, name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
11-21 16:25:32.289  5653  5891 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-21 16:25:33.104  5653  5891 W !!      : call onHalfStreamCopied
11-21 16:25:33.104  5653  5891 I testCopyDataAndClose: closing input stream
,11-21 16:25:33.901  5653  5891 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 156, thread name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
11-21 16:25:33.901  5653  5891 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
11-21 16:25:33.901  5653  5891 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
11-21 16:25:33.901  5653  5891 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-21 16:25:33.901  5653  5891 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
11-21 16:25:33.902  5653  5891 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
11-21 16:25:33.902  5653  5891 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
11-21 16:25:33.902  5653  5891 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
11-21 16:25:33.902  5653  5891 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
11-21 16:25:33.902  5653  5891 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 156, name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
11-21 16:25:33.902  5653  5891 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 20971520 and the total number of bytes written 20971520
,11-21 16:25:35.120   927  3029 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 12, 13 -> obsolete
,11-21 16:25:38.033  5653  5701 I StreamCopyingThreadTest: Starting test: testRun
,11-21 16:25:38.038  5653  5892 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 159, name: My test thread name). Connection data: Peer properties: [null null].
11-21 16:25:38.038  5653  5892 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-21 16:25:43.046  5653  5893 E StreamCopyingThreadTest: StreamCopyingThread didn't close after 5s!
,11-21 16:25:43.049  5653  5701 I StreamCopyingThreadTest: Starting test: testCopyBigData
,11-21 16:25:43.160  5653  5894 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 162, name: testCopyBigData thread). Connection data: Peer properties: [null null].
11-21 16:25:43.160  5653  5894 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-21 16:25:43.409   927  5864 D NetlinkSocketObserver: NeighborEvent{elapsedMs=212763, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,11-21 16:25:44.827  5653  5894 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 162, thread name: testCopyBigData thread). Connection data: Peer properties: [null null].
11-21 16:25:44.827  5653  5894 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-21 16:25:44.827  5653  5894 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
11-21 16:25:44.827  5653  5894 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-21 16:25:44.827  5653  5894 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
,11-21 16:25:44.827  5653  5894 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
,11-21 16:25:44.827  5653  5894 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
11-21 16:25:44.827  5653  5894 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
11-21 16:25:44.827  5653  5894 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
11-21 16:25:44.827  5653  5894 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 162, name: testCopyBigData thread). Connection data: Peer properties: [null null].
11-21 16:25:44.827  5653  5894 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 20971520 and the total number of bytes written 20971520
,11-21 16:25:48.435  3721  3922 I Keyboard.Facilitator.LanguageModelFlusher: run()
11-21 16:25:48.436  3721  3922 I Keyboard.Facilitator: flushDynamicLanguageModels()
,11-21 16:25:48.471  3647  3647 I ConfigService: onCreate
,11-21 16:25:48.475   537   537 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,11-21 16:25:48.475   537   537 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,11-21 16:25:48.961  5653  5701 I StreamCopyingThreadTest: Starting test: testRunNotify
,11-21 16:25:48.964  5653  5896 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 164, name: My test thread name). Connection data: Peer properties: [null null].
11-21 16:25:48.964  5653  5896 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-21 16:25:48.964  5653  5896 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 164, thread name: My test thread name). Connection data: Peer properties: [null null].
11-21 16:25:48.964  5653  5896 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
11-21 16:25:48.964  5653  5896 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
11-21 16:25:48.964  5653  5896 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
11-21 16:25:48.964  5653  5896 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
11-21 16:25:48.964  5653  5896 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
,11-21 16:25:48.965  5653  5896 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
11-21 16:25:48.965  5653  5896 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
11-21 16:25:48.965  5653  5896 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
11-21 16:25:48.965  5653  5896 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 164, name: My test thread name). Connection data: Peer properties: [null null].
11-21 16:25:48.965  5653  5896 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 22
11-21 16:25:48.966  5653  5701 I StreamCopyingThreadTest: Starting test: testSetBufferSize
,11-21 16:25:48.967  5653  5701 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
11-21 16:25:48.968  5653  5701 I StreamCopyingThreadTest: Starting test: testRunWithException
,11-21 16:25:48.970  5653  5897 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 168, name: My test thread name). Connection data: Peer properties: [null null].
11-21 16:25:48.970  5653  5897 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
11-21 16:25:48.970  5653  5897 E io.jxcore.node.StreamCopyingThread: Failed to write to the output stream (thread ID: 168, thread name: My test thread name): Test exception.
11-21 16:25:48.971  5653  5897 D io.jxcore.node.StreamCopyingThread: onStreamCopyError (ID: 168, name: My test thread name). Connection data: Peer properties: [null null].
11-21 16:25:48.971  5653  5897 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
11-21 16:25:48.971  5653  5897 D io.jxcore.node.StreamCopyingThread: number of bytes read = 22
,11-21 16:25:48.971  5653  5897 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 168, name: My test thread name). Connection data: Peer properties: [null null].
11-21 16:25:48.971  5653  5897 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
11-21 16:25:48.973  5653  5701 E com.test.thalitest.ThaliTestRunner: testConnect(io.jxcore.node.ConnectionHelperTest)
11-21 16:25:48.973  5653  5701 E com.test.thalitest.ThaliTestRunner: 
11-21 16:25:48.973  5653  5701 E com.test.thalitest.ThaliTestRunner: Expected: is "We already have an outgoing connection to peer with ID 00:11:22:33:44:55"
11-21 16:25:48.973  5653  5701 E com.test.thalitest.ThaliTestRunner:      but: was "Already connect(ing/ed)"
11-21 16:25:48.974  5653  5701 E com.test.thalitest.ThaliTestRunner: java.lang.AssertionError: 
11-21 16:25:48.974  5653  5701 E com.test.thalitest.ThaliTestRunner: Expected: is "We already have an outgoing connection to peer with ID 00:11:22:33:44:55"
11-21 16:25:48.974  5653  5701 E com.test.thalitest.ThaliTestRunner:      but: was "Already connect(ing/ed)"
11-21 16:25:48.974  5653  5701 E com.test.thalitest.ThaliTestRunner: 	at org.hamcrest.MatcherAssert.assertThat(MatcherAssert.java:20)
11-21 16:25:48.974  5653  5701 E com.test.thalitest.ThaliTestRunner: 	at org.hamcrest.MatcherAssert.assertThat(MatcherAssert.java:8)
11-21 16:25:48.974  5653  5701 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.ConnectionHelperTest.testConnect(ConnectionHelperTest.java:551)
11-21 16:25:48.974  5653  5701 E com.test.thalitest.ThaliTestRunner: 	at java.lang.reflect.Method.invoke(Native Method)
11-21 16:25:48.974  5653  5701 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.model.FrameworkMethod$1.runReflectiveCall(FrameworkMethod.java:50)
11-21 16:25:48.974  5653  5701 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.model.ReflectiveCallable.run(ReflectiveCallable.java:12)
11-21 16:25:48.974  5653  5701 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.model.FrameworkMethod.invokeExplosively(FrameworkMethod.java:47)
11-21 16:25:48.974  5653  5701 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.InvokeMethod.evaluate(InvokeMethod.java:17)
11-21 16:25:48.974  5653  5701 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.RunBefores.evaluate(RunBefores.java:26)
11-21 16:25:48.974  5653  5701 E com.test.thalitest.ThaliTestRunner: 	at org.junit.rules.ExpectedException$ExpectedExceptionStatement.evaluate(ExpectedException.java:239)
11-21 16:25:48.974  5653  5701 E com.test.thalitest.ThaliTestRunner: 	at org.junit.rules.TestWatcher$1.evaluate(TestWatcher.java:55)
11-21 16:25:48.974  5653  5701 E com.test.thalitest.ThaliTestRunner: 	at org.junit.rules.RunRules.evaluate(RunRules.java:20)
11-21 16:25:48.974  5653  5701 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runLeaf(ParentRunner.java:325)
11-21 16:25:48.974  5653  5701 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.BlockJUnit4ClassRunner.runChild(BlockJUnit4ClassRunner.java:78)
11-21 16:25:48.974  5653  5701 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.BlockJUnit4ClassRunner.runChild(BlockJUnit4ClassRunner.java:57)
11-21 16:25:48.974  5653  5701 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$3.run(ParentRunner.java:290)
11-21 16:25:48.974  5653  5701 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$1.schedule(ParentRunner.java:71)
11-21 16:25:48.974  5653  5701 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runChildren(ParentRunner.java:288)
11-21 16:25:48.974  5653  5701 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.access$000(ParentRunner.java:58)
11-21 16:25:48.974  5653  5701 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$2.evaluate(ParentRunner.java:,268)
11-21 16:25:48.974  5653  5701 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.RunBefores.evaluate(RunBefores.java:26)
11-21 16:25:48.974  5653  5701 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.RunAfters.evaluate(RunAfters.java:27)
11-21 16:25:48.974  5653  5701 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.run(ParentRunner.java:363)
11-21 16:25:48.974  5653  5701 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:128)
11-21 16:25:48.974  5653  5701 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:27)
11-21 16:25:48.974  5653  5701 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$3.run(ParentRunner.java:290)
11-21 16:25:48.974  5653  5701 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$1.schedule(ParentRunner.java:71)
11-21 16:25:48.974  5653  5701 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runChildren(ParentRunner.java:288)
11-21 16:25:48.974  5653  5701 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.access$000(ParentRunner.java:58)
11-21 16:25:48.974  5653  5701 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$2.evaluate(ParentRunner.java:268)
11-21 16:25:48.974  5653  5701 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.run(ParentRunner.java:363)
11-21 16:25:48.974  5653  5701 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:128)
11-21 16:25:48.974  5653  5701 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:27)
11-21 16:25:48.974  5653  5701 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$3.run(ParentRunner.java:290)
11-21 16:25:48.974  5653  5701 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$1.schedule(ParentRunner.java:71)
11-21 16:25:48.974  5653  5701 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runChildren(ParentRunner.java:288)
11-21 16:25:48.974  5653  5701 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.access$000(ParentRunner.java:58)
11-21 16:25:48.974  5653  5701 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$2.evaluate(ParentRunner.java:268)
11-21 16:25:48.974  5653  5701 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.run(ParentRunner.java:363)
11-21 16:25:48.974  5653  5701 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.run(JUnitCore.java:137)
11-21 16:25:48.974  5653  5701 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.run(JUnitCore.java:115)
11-21 16:25:48.974  5653  5701 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.run(JUnitCore.java:105)
11-21 16:25:48.974  5653  5701 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.runClasses(JUnitCore.java:62)
11-21 16:25:48.974  5653  5701 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.runClasses(JUnitCore.java:49)
11-21 16:25:48.974  5653  5701 E com.test.thalitest.ThaliTestRunner: 	at com.test.thalitest.ThaliTestRunner.runTests(ThaliTestRunner.java:86)
11-21 16:25:48.974  5653  5701 E com.test.thalitest.ThaliTestRunner: 	at com.test.thalitest.RegisterExecuteUT$2.Receiver(RegisterExecuteUT.java:75)
11-21 16:25:48.974  5653  5701 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.jxcore.javaCall(jxcore.java:139)
11-21 16:25:48.974  5653  5701 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.jxcore.evalEngine(Native Method)
11-21 16:25:48.974  5653  5701 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.jxcore$4.run(jxcore.java:226)
11-21 16:25:48.974  5653  5701 E com.test.thalitest.ThaliTestRunner: 	at android.os.Handler.handleCallback(Handler.java:739)
11-21 16:25:48.974  5653  5701 E com.test.thalitest.ThaliTestRunner: 	at android.os.Handler.dispatchMessag,e(Handler.java:95)
11-21 16:25:48.974  5653  5701 E com.test.thalitest.ThaliTestRunner: 	at android.os.Looper.loop(Looper.java:148)
11-21 16:25:48.974  5653  5701 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.CoreThread.run(CoreRunnable.java:56)
11-21 16:25:48.974  5653  5701 E com.test.thalitest.ThaliTestRunner: testStartStop(io.jxcore.node.ConnectivityMonitorTest)
11-21 16:25:48.974  5653  5701 E com.test.thalitest.ThaliTestRunner: The BT listener was bound
11-21 16:25:48.974  5653  5701 E com.test.thalitest.ThaliTestRunner: Expected: is <true>
11-21 16:25:48.974  5653  5701 E com.test.thalitest.ThaliTestRunner:      but: was <false>
11-21 16:25:48.975  5653  5701 E com.test.thalitest.ThaliTestRunner: java.lang.AssertionError: The BT listener was bound
11-21 16:25:48.975  5653  5701 E com.test.thalitest.ThaliTestRunner: Expected: is <true>
11-21 16:25:48.975  5653  5701 E com.test.thalitest.ThaliTestRunner:      but: was <false>
11-21 16:25:48.975  5653  5701 E com.test.thalitest.ThaliTestRunner: 	at org.hamcrest.MatcherAssert.assertThat(MatcherAssert.java:20)
11-21 16:25:48.975  5653  5701 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.ConnectivityMonitorTest.testStartStop(ConnectivityMonitorTest.java:216)
11-21 16:25:48.975  5653  5701 E com.test.thalitest.ThaliTestRunner: 	at java.lang.reflect.Method.invoke(Native Method)
11-21 16:25:48.975  5653  5701 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.model.FrameworkMethod$1.runReflectiveCall(FrameworkMethod.java:50)
11-21 16:25:48.975  5653  5701 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.model.ReflectiveCallable.run(ReflectiveCallable.java:12)
11-21 16:25:48.975  5653  5701 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.model.FrameworkMethod.invokeExplosively(FrameworkMethod.java:47)
11-21 16:25:48.975  5653  5701 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.InvokeMethod.evaluate(InvokeMethod.java:17)
11-21 16:25:48.975  5653  5701 E com.test.thalitest.ThaliTestRunner: 	at org.junit.rules.ExpectedException$ExpectedExceptionStatement.evaluate(ExpectedException.java:239)
11-21 16:25:48.975  5653  5701 E com.test.thalitest.ThaliTestRunner: 	at org.junit.rules.TestWatcher$1.evaluate(TestWatcher.java:55)
11-21 16:25:48.975  5653  5701 E com.test.thalitest.ThaliTestRunner: 	at org.junit.rules.RunRules.evaluate(RunRules.java:20)
11-21 16:25:48.975  5653  5701 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runLeaf(ParentRunner.java:325)
11-21 16:25:48.975  5653  5701 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.BlockJUnit4ClassRunner.runChild(BlockJUnit4ClassRunner.java:78)
11-21 16:25:48.975  5653  5701 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.BlockJUnit4ClassRunner.runChild(BlockJUnit4ClassRunner.java:57)
11-21 16:25:48.975  5653  5701 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$3.run(ParentRunner.java:290)
11-21 16:25:48.975  5653  5701 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$1.schedule(ParentRunner.java:71)
11-21 16:25:48.975  5653  5701 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runChildren(ParentRunner.java:288)
11-21 16:25:48.975  5653  5701 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.access$000(ParentRunner.java:58)
11-21 16:25:48.975  5653  5701 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$2.evaluate(ParentRunner.java:268)
11-21 16:25:48.975  5653  5701 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.RunBefores.evaluate(RunBefores.java:26)
11-21 16:25:48.975  5653  5701 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.RunAfters.evaluate(RunAfters.java:27)
11-21 16:25:48.975  5653  5701 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.run(ParentRunner.java:363)
11-21 16:25:48.975  5653  5701 E com.test.thalitest.ThaliTestRunner: 	at org.jun,it.runners.Suite.runChild(Suite.java:128)
11-21 16:25:48.975  5653  5701 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:27)
11-21 16:25:48.975  5653  5701 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$3.run(ParentRunner.java:290)
11-21 16:25:48.975  5653  5701 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$1.schedule(ParentRunner.java:71)
11-21 16:25:48.975  5653  5701 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runChildren(ParentRunner.java:288)
11-21 16:25:48.975  5653  5701 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.access$000(ParentRunner.java:58)
11-21 16:25:48.975  5653  5701 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$2.evaluate(ParentRunner.java:268)
11-21 16:25:48.975  5653  5701 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.run(ParentRunner.java:363)
11-21 16:25:48.975  5653  5701 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:128)
11-21 16:25:48.975  5653  5701 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:27)
11-21 16:25:48.975  5653  5701 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$3.run(ParentRunner.java:290)
11-21 16:25:48.975  5653  5701 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$1.schedule(ParentRunner.java:71)
11-21 16:25:48.975  5653  5701 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runChildren(ParentRunner.java:288)
11-21 16:25:48.975  5653  5701 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.access$000(ParentRunner.java:58)
11-21 16:25:48.975  5653  5701 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$2.evaluate(ParentRunner.java:268)
11-21 16:25:48.975  5653  5701 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.run(ParentRunner.java:363)
11-21 16:25:48.975  5653  5701 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.run(JUnitCore.java:137)
11-21 16:25:48.975  5653  5701 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.run(JUnitCore.java:115)
11-21 16:25:48.975  5653  5701 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.run(JUnitCore.java:105)
11-21 16:25:48.975  5653  5701 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.runClasses(JUnitCore.java:62)
11-21 16:25:48.975  5653  5701 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.runClasses(JUnitCore.java:49)
11-21 16:25:48.975  5653  5701 E com.test.thalitest.ThaliTestRunner: 	at com.test.thalitest.ThaliTestRunner.runTests(ThaliTestRunner.java:86)
11-21 16:25:48.975  5653  5701 E com.test.thalitest.ThaliTestRunner: 	at com.test.thalitest.RegisterExecuteUT$2.Receiver(RegisterExecuteUT.java:75)
11-21 16:25:48.975  5653  5701 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.jxcore.javaCall(jxcore.java:139)
11-21 16:25:48.975  5653  5701 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.jxcore.evalEngine(Native Method)
11-21 16:25:48.975  5653  5701 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.jxcore$4.run(jxcore.java:226)
11-21 16:25:48.975  5653  5701 E com.test.thalitest.ThaliTestRunner: 	at android.os.Handler.handleCallback(Handler.java:739)
11-21 16:25:48.975  5653  5701 E com.test.thalitest.ThaliTestRunner: 	at android.os.Handler.dispatchMessage(Handler.java:95)
11-21 16:25:48.975  5653  5701 E com.test.thalitest.ThaliTestRunner: 	at android.os.Looper.loop(Looper.java:148)
11-21 16:25:48.975  5653  5701 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.CoreThread.run(CoreRunnable.java:56)
11-21 16:25:48.975  5653  5701 E com.test.thalitest.ThaliTestRunner: testRun(io.jxcore.node.StreamCopyingThreadTest)
11-21 16:25:48.975  5653  5701 E com.test.thalitest.ThaliTestRunner: StreamCopyingThread should be closed
11-21 16:25:48.975  5653  5701 E co,m.test.thalitest.ThaliTestRunner: Expected: is <true>
11-21 16:25:48.975  5653  5701 E com.test.thalitest.ThaliTestRunner:      but: was <false>
11-21 16:25:48.976  5653  5701 E com.test.thalitest.ThaliTestRunner: java.lang.AssertionError: StreamCopyingThread should be closed
11-21 16:25:48.976  5653  5701 E com.test.thalitest.ThaliTestRunner: Expected: is <true>
11-21 16:25:48.976  5653  5701 E com.test.thalitest.ThaliTestRunner:      but: was <false>
11-21 16:25:48.976  5653  5701 E com.test.thalitest.ThaliTestRunner: 	at org.hamcrest.MatcherAssert.assertThat(MatcherAssert.java:20)
11-21 16:25:48.976  5653  5701 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.StreamCopyingThreadTest.testRun(StreamCopyingThreadTest.java:152)
11-21 16:25:48.976  5653  5701 E com.test.thalitest.ThaliTestRunner: 	at java.lang.reflect.Method.invoke(Native Method)
11-21 16:25:48.976  5653  5701 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.model.FrameworkMethod$1.runReflectiveCall(FrameworkMethod.java:50)
11-21 16:25:48.976  5653  5701 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.model.ReflectiveCallable.run(ReflectiveCallable.java:12)
11-21 16:25:48.976  5653  5701 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.model.FrameworkMethod.invokeExplosively(FrameworkMethod.java:47)
11-21 16:25:48.976  5653  5701 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.InvokeMethod.evaluate(InvokeMethod.java:17)
11-21 16:25:48.976  5653  5701 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.RunBefores.evaluate(RunBefores.java:26)
11-21 16:25:48.976  5653  5701 E com.test.thalitest.ThaliTestRunner: 	at org.junit.rules.ExpectedException$ExpectedExceptionStatement.evaluate(ExpectedException.java:239)
11-21 16:25:48.976  5653  5701 E com.test.thalitest.ThaliTestRunner: 	at org.junit.rules.TestWatcher$1.evaluate(TestWatcher.java:55)
11-21 16:25:48.976  5653  5701 E com.test.thalitest.ThaliTestRunner: 	at org.junit.rules.RunRules.evaluate(RunRules.java:20)
11-21 16:25:48.976  5653  5701 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runLeaf(ParentRunner.java:325)
11-21 16:25:48.976  5653  5701 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.BlockJUnit4ClassRunner.runChild(BlockJUnit4ClassRunner.java:78)
11-21 16:25:48.976  5653  5701 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.BlockJUnit4ClassRunner.runChild(BlockJUnit4ClassRunner.java:57)
11-21 16:25:48.976  5653  5701 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$3.run(ParentRunner.java:290)
11-21 16:25:48.976  5653  5701 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$1.schedule(ParentRunner.java:71)
11-21 16:25:48.976  5653  5701 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runChildren(ParentRunner.java:288)
11-21 16:25:48.976  5653  5701 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.access$000(ParentRunner.java:58)
11-21 16:25:48.976  5653  5701 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$2.evaluate(ParentRunner.java:268)
11-21 16:25:48.976  5653  5701 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.run(ParentRunner.java:363)
11-21 16:25:48.976  5653  5701 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:128)
11-21 16:25:48.976  5653  5701 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:27)
11-21 16:25:48.976  5653  5701 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$3.run(ParentRunner.java:290)
11-21 16:25:48.976  5653  5701 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$1.schedule(ParentRunner.java:71)
11-21 16:25:48.976  5653  5701 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runChildren(ParentRunner.java:288)
11-21 16:25:48.976  5653  5701 E com.test.thalitest.ThaliTestRunner: 	at org.junit.,runners.ParentRunner.access$000(ParentRunner.java:58)
11-21 16:25:48.976  5653  5701 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$2.evaluate(ParentRunner.java:268)
11-21 16:25:48.976  5653  5701 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.run(ParentRunner.java:363)
11-21 16:25:48.976  5653  5701 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:128)
11-21 16:25:48.976  5653  5701 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:27)
11-21 16:25:48.976  5653  5701 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$3.run(ParentRunner.java:290)
11-21 16:25:48.976  5653  5701 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$1.schedule(ParentRunner.java:71)
11-21 16:25:48.976  5653  5701 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runChildren(ParentRunner.java:288)
11-21 16:25:48.976  5653  5701 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.access$000(ParentRunner.java:58)
11-21 16:25:48.976  5653  5701 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$2.evaluate(ParentRunner.java:268)
11-21 16:25:48.976  5653  5701 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.run(ParentRunner.java:363)
11-21 16:25:48.976  5653  5701 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.run(JUnitCore.java:137)
11-21 16:25:48.976  5653  5701 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.run(JUnitCore.java:115)
11-21 16:25:48.976  5653  5701 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.run(JUnitCore.java:105)
11-21 16:25:48.976  5653  5701 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.runClasses(JUnitCore.java:62)
11-21 16:25:48.976  5653  5701 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.runClasses(JUnitCore.java:49)
11-21 16:25:48.976  5653  5701 E com.test.thalitest.ThaliTestRunner: 	at com.test.thalitest.ThaliTestRunner.runTests(ThaliTestRunner.java:86)
11-21 16:25:48.976  5653  5701 E com.test.thalitest.ThaliTestRunner: 	at com.test.thalitest.RegisterExecuteUT$2.Receiver(RegisterExecuteUT.java:75)
11-21 16:25:48.976  5653  5701 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.jxcore.javaCall(jxcore.java:139)
11-21 16:25:48.976  5653  5701 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.jxcore.evalEngine(Native Method)
11-21 16:25:48.976  5653  5701 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.jxcore$4.run(jxcore.java:226)
11-21 16:25:48.976  5653  5701 E com.test.thalitest.ThaliTestRunner: 	at android.os.Handler.handleCallback(Handler.java:739)
11-21 16:25:48.976  5653  5701 E com.test.thalitest.ThaliTestRunner: 	at android.os.Handler.dispatchMessage(Handler.java:95)
11-21 16:25:48.976  5653  5701 E com.test.thalitest.ThaliTestRunner: 	at android.os.Looper.loop(Looper.java:148)
11-21 16:25:48.976  5653  5701 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.CoreThread.run(CoreRunnable.java:56)
11-21 16:25:48.979  5653  5701 I jxcore-log: 2016-11-21 15:25:48 - DEBUG UnitTest_app: 'Running unit tests'
11-21 16:25:48.979  5653  5701 I jxcore-log: 
11-21 16:25:48.979  5653  5701 I jxcore-log: *Native tests were executed*
11-21 16:25:48.979  5653  5701 I jxcore-log: 
11-21 16:25:48.979  5653  5701 I jxcore-log: Total number of executed tests:  82
11-21 16:25:48.979  5653  5701 I jxcore-log: 
11-21 16:25:48.979  5653  5701 I jxcore-log: Number of passed tests:  79
11-21 16:25:48.979  5653  5701 I jxcore-log: 
11-21 16:25:48.979  5653  5701 I jxcore-log: Number of failed tests:  3
11-21 16:25:48.979  5653  5701 I jxcore-log: 
11-21 16:25:48.979  5653  5701 I jxcore-log: Number of ignored tests:  0
11-21 16:25:48.979  5653  5701 I jxcore-log: 
11-21 16:25:48.980  5653  5701 I jxcore-log: Total duration:  38709
11-21 16:25:48.980  5653  5701 I jxcore-log: 
11-21 16:25:48.980  5653  5701 I jx,core-log: Failed to execute UT.
11-21 16:25:48.980  5653  5701 I jxcore-log: 
11-21 16:25:48.980  5653  5701 I jxcore-log: 2016-11-21 15:25:48 - DEBUG UnitTest_app: 'Failed to execute UT.'
11-21 16:25:48.980  5653  5701 I jxcore-log: 
11-21 16:25:48.981  5653  5701 I jxcore-log: 2016-11-21 15:25:48 - DEBUG UnitTest_app: 'Unit Test app is loaded'
11-21 16:25:48.981  5653  5701 I jxcore-log: 
11-21 16:25:48.984  5653  5701 I jxcore-log: 2016-11-21 15:25:48 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
11-21 16:25:48.984  5653  5701 I jxcore-log: 
11-21 16:25:48.985  5653  5701 I jxcore-log: 2016-11-21 15:25:48 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-21 16:25:48.985  5653  5701 I jxcore-log: 
11-21 16:25:48.986  5653  5701 I jxcore-log: 2016-11-21 15:25:48 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
11-21 16:25:48.986  5653  5701 I jxcore-log: 
11-21 16:25:48.986  5653  5701 I jxcore-log: 2016-11-21 15:25:48 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-21 16:25:48.986  5653  5701 I jxcore-log: 
11-21 16:25:48.987  5653  5701 I jxcore-log: 2016-11-21 15:25:48 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
11-21 16:25:48.987  5653  5701 I jxcore-log: 
11-21 16:25:48.987  5653  5701 I jxcore-log: 2016-11-21 15:25:48 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH"})'
11-21 16:25:48.987  5653  5701 I jxcore-log: 
11-21 16:25:48.987  5653  5701 I jxcore-log: 2016-11-21 15:25:48 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-21 16:25:48.987  5653  5701 I jxcore-log: 
11-21 16:25:48.988  5653  5701 I jxcore-log: 2016-11-21 15:25:48 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
11-21 16:25:48.988  5653  5701 I jxcore-log: 
11-21 16:25:48.988  5653  5701 I jxcore-log: 2016-11-21 15:25:48 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH"})'
11-21 16:25:48.988  5653  5701 I jxcore-log: 
11-21 16:25:48.988  5653  5701 I jxcore-log: 2016-11-21 15:25:48 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-21 16:25:48.988  5653  5701 I jxcore-log: 
11-21 16:25:48.988  5653  5701 I jxcore-log: 2016-11-21 15:25:48 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
11-21 16:25:48.988  5653  5701 I jxcore-log: 
11-21 16:25:48.989  5653  5701 I jxcore-log: 2016-11-21 15:25:48 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH"})'
11-21 16:25:48.989  5653  5701 I jxcore-log: 
11-21 16:25:48.989  5653  5701 I jxcore-log: 2016-11-21 15:25:48 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-21 16:25:48.989  5653  5701 I jxcore-log: 
11-21 16:25:48.989  5653  5701 I jxcore-log: 2016-11-21 15:25:48 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-21 16:25:48.989  5653  5701 I jxcore-log: 
11-21 16:25:48.989  5653  5701 I jxcore-log: 2016-11-21 15:25:48 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-21 16:25:48.989  5653  5701 I jxcore-log: 
11-21 16:25:4,8.989  5653  5701 I jxcore-log: 2016-11-21 15:25:48 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
11-21 16:25:48.989  5653  5701 I jxcore-log: 
11-21 16:25:48.990  5653  5701 I jxcore-log: 2016-11-21 15:25:48 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-21 16:25:48.990  5653  5701 I jxcore-log: 
11-21 16:25:48.990  5653  5701 I jxcore-log: 2016-11-21 15:25:48 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-21 16:25:48.990  5653  5701 I jxcore-log: 
11-21 16:25:48.990  5653  5701 I jxcore-log: 2016-11-21 15:25:48 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-21 16:25:48.990  5653  5701 I jxcore-log: 
11-21 16:25:48.990  5653  5701 I jxcore-log: 2016-11-21 15:25:48 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
11-21 16:25:48.990  5653  5701 I jxcore-log: 
11-21 16:25:48.990  5653  5701 I jxcore-log: 2016-11-21 15:25:48 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-21 16:25:48.990  5653  5701 I jxcore-log: 
11-21 16:25:48.991  5653  5701 I jxcore-log: 2016-11-21 15:25:48 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
11-21 16:25:48.991  5653  5701 I jxcore-log: 
11-21 16:25:48.991  5653  5701 I jxcore-log: 2016-11-21 15:25:48 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-21 16:25:48.991  5653  5701 I jxcore-log: 
11-21 16:25:48.991  5653  5701 I jxcore-log: 2016-11-21 15:25:48 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
11-21 16:25:48.991  5653  5701 I jxcore-log: 
11-21 16:25:48.991  5653  5701 I jxcore-log: 2016-11-21 15:25:48 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-21 16:25:48.991  5653  5701 I jxcore-log: 
11-21 16:25:48.991  5653  5701 I jxcore-log: 2016-11-21 15:25:48 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
11-21 16:25:48.991  5653  5701 I jxcore-log: 
11-21 16:25:48.993  5653  5701 I jxcore-log: 2016-11-21 15:25:48 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-21 16:25:48.993  5653  5701 I jxcore-log: 
11-21 16:25:48.993  5653  5701 I jxcore-log: 2016-11-21 15:25:48 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
11-21 16:25:48.993  5653  5701 I jxcore-log: 
11-21 16:25:48.993  5653  5701 I jxcore-log: 2016-11-21 15:25:48 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH"})'
11-21 16:25:48.993  5653  5701 I jxcore-log: 
11-21 16:25:48.993  5653  5701 I jxcore-log: 2016-11-21 15:25:48 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-21 16:25:48.993  5653  5701 I jxcore-log: 
11-21 16:25:48.994  5653  5701 I jxcore-log: 2016-11-21 15:25:48 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
11-21 16:25:48.994  5653  5701 I jxcore-log: 
,11-21 16:25:48.994  5653  5701 I jxcore-log: 2016-11-21 15:25:48 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH"})'
11-21 16:25:48.994  5653  5701 I jxcore-log: 
11-21 16:25:48.994  5653  5701 I jxcore-log: 2016-11-21 15:25:48 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-21 16:25:48.994  5653  5701 I jxcore-log: 
11-21 16:25:48.994  5653  5701 I jxcore-log: 2016-11-21 15:25:48 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
11-21 16:25:48.994  5653  5701 I jxcore-log: 
11-21 16:25:48.995  5653  5701 I jxcore-log: 2016-11-21 15:25:48 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH"})'
11-21 16:25:48.995  5653  5701 I jxcore-log: 
11-21 16:25:48.995  5653  5701 I jxcore-log: 2016-11-21 15:25:48 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-21 16:25:48.995  5653  5701 I jxcore-log: 
,11-21 16:25:48.995  5653  5701 I jxcore-log: 2016-11-21 15:25:48 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-21 16:25:48.995  5653  5701 I jxcore-log: 
11-21 16:25:48.995  5653  5701 I jxcore-log: 2016-11-21 15:25:48 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-21 16:25:48.995  5653  5701 I jxcore-log: 
11-21 16:25:49.000  5653  5701 I jxcore-log: 2016-11-21 15:25:49 - DEBUG UnitTest_app: 'My device name is: Huawei-Nexus 6P'
11-21 16:25:49.000  5653  5701 I jxcore-log: 
11-21 16:25:49.000  5653  5701 I jxcore-log: 2016-11-21 15:25:49 - WARN testUtils: 'myNameCallback not set!'
11-21 16:25:49.000  5653  5701 I jxcore-log: 
,11-21 16:25:49.005  5653  5653 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
,11-21 16:25:51.089  5653  5701 I jxcore-log: 2016-11-21 15:25:51 - INFO runTests: 'Starting tests. Network type: WIFI. Platform: android'
11-21 16:25:51.089  5653  5701 I jxcore-log: 
,11-21 16:25:51.091  5653  5701 I jxcore-log: 2016-11-21 15:25:51 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js'
11-21 16:25:51.091  5653  5701 I jxcore-log: 
,11-21 16:25:51.439  5653  5701 I jxcore-log: 2016-11-21 15:25:51 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js'
11-21 16:25:51.439  5653  5701 I jxcore-log: 
,11-21 16:25:51.453  5653  5701 I jxcore-log: 2016-11-21 15:25:51 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManager.js'
11-21 16:25:51.453  5653  5701 I jxcore-log: 
,11-21 16:25:52.555  5653  5701 I jxcore-log: 2016-11-21 15:25:52 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js'
11-21 16:25:52.555  5653  5701 I jxcore-log: 
,11-21 16:25:52.723  5653  5701 I jxcore-log: 2016-11-21 15:25:52 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js'
11-21 16:25:52.723  5653  5701 I jxcore-log: 
,11-21 16:25:52.728  5653  5701 I jxcore-log: 2016-11-21 15:25:52 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testNativeMethod.js'
11-21 16:25:52.728  5653  5701 I jxcore-log: 
,11-21 16:25:52.741  5653  5701 I jxcore-log: 2016-11-21 15:25:52 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPouchDBCheckpointPlugin.js'
11-21 16:25:52.741  5653  5701 I jxcore-log: 
,11-21 16:25:53.239  5653  5701 I jxcore-log: 2016-11-21 15:25:53 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPouchDBGenerator.js'
11-21 16:25:53.239  5653  5701 I jxcore-log: 
,11-21 16:25:53.284  5653  5701 I jxcore-log: 2016-11-21 15:25:53 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js'
11-21 16:25:53.284  5653  5701 I jxcore-log: 
,11-21 16:25:53.297  5653  5701 I jxcore-log: 2016-11-21 15:25:53 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js'
11-21 16:25:53.297  5653  5701 I jxcore-log: 
,11-21 16:25:53.301  5653  5701 I jxcore-log: 2016-11-21 15:25:53 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliManager.js'
11-21 16:25:53.301  5653  5701 I jxcore-log: 
,11-21 16:25:53.502  3647  3647 I ConfigService: onDestroy
,11-21 16:25:53.582  5653  5701 I jxcore-log: 2016-11-21 15:25:53 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliManagerCoordinated.js'
11-21 16:25:53.582  5653  5701 I jxcore-log: 
,11-21 16:25:53.709  5653  5701 I jxcore-log: 2016-11-21 15:25:53 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js'
11-21 16:25:53.709  5653  5701 I jxcore-log: 
,11-21 16:25:54.079  5653  5701 I jxcore-log: 2016-11-21 15:25:54 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js'
11-21 16:25:54.079  5653  5701 I jxcore-log: 
,11-21 16:25:54.086  5653  5701 I jxcore-log: 2016-11-21 15:25:54 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeAndroid.js'
11-21 16:25:54.086  5653  5701 I jxcore-log: 
,11-21 16:25:54.090  5653  5701 I jxcore-log: 2016-11-21 15:25:54 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeDiscoveryCoordinated.js'
11-21 16:25:54.090  5653  5701 I jxcore-log: 
,11-21 16:25:54.093  5653  5701 I jxcore-log: 2016-11-21 15:25:54 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js'
11-21 16:25:54.093  5653  5701 I jxcore-log: 
,11-21 16:25:54.098  5653  5701 I jxcore-log: 2016-11-21 15:25:54 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeiOS.js'
11-21 16:25:54.098  5653  5701 I jxcore-log: 
,11-21 16:25:54.137  5653  5701 I jxcore-log: 2016-11-21 15:25:54 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js'
11-21 16:25:54.137  5653  5701 I jxcore-log: 
,11-21 16:25:54.143  5653  5701 I jxcore-log: 2016-11-21 15:25:54 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js'
11-21 16:25:54.143  5653  5701 I jxcore-log: 
,11-21 16:25:54.173  5653  5701 I jxcore-log: 2016-11-21 15:25:54 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js'
11-21 16:25:54.173  5653  5701 I jxcore-log: 
,11-21 16:25:54.212  5653  5701 I jxcore-log: 2016-11-21 15:25:54 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js'
11-21 16:25:54.212  5653  5701 I jxcore-log: 
,11-21 16:25:54.219  5653  5701 I jxcore-log: 2016-11-21 15:25:54 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationLocal.js'
11-21 16:25:54.219  5653  5701 I jxcore-log: 
,11-21 16:25:54.226  5653  5701 I jxcore-log: 2016-11-21 15:25:54 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js'
11-21 16:25:54.226  5653  5701 I jxcore-log: 
,11-21 16:25:54.241  5653  5701 I jxcore-log: 2016-11-21 15:25:54 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js'
11-21 16:25:54.241  5653  5701 I jxcore-log: 
,11-21 16:25:54.256  5653  5701 I jxcore-log: 2016-11-21 15:25:54 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js'
11-21 16:25:54.256  5653  5701 I jxcore-log: 
,11-21 16:25:54.262  5653  5701 I jxcore-log: 2016-11-21 15:25:54 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolDefault.js'
11-21 16:25:54.262  5653  5701 I jxcore-log: 
,11-21 16:25:54.267  5653  5701 I jxcore-log: 2016-11-21 15:25:54 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js'
11-21 16:25:54.267  5653  5701 I jxcore-log: 
,11-21 16:25:54.281  5653  5701 I jxcore-log: 2016-11-21 15:25:54 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolOneAtATime.js'
11-21 16:25:54.281  5653  5701 I jxcore-log: 
,11-21 16:25:54.298  5653  5701 I jxcore-log: 2016-11-21 15:25:54 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js'
11-21 16:25:54.298  5653  5701 I jxcore-log: 
,11-21 16:25:54.313  5653  5701 I jxcore-log: 2016-11-21 15:25:54 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js'
11-21 16:25:54.313  5653  5701 I jxcore-log: 
,11-21 16:25:54.324  5653  5701 I jxcore-log: 2016-11-21 15:25:54 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerAction.js'
11-21 16:25:54.324  5653  5701 I jxcore-log: 
,11-21 16:25:54.336  5653  5701 I jxcore-log: 2016-11-21 15:25:54 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js'
11-21 16:25:54.336  5653  5701 I jxcore-log: 
,11-21 16:25:54.347  5653  5701 I jxcore-log: 2016-11-21 15:25:54 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js'
11-21 16:25:54.347  5653  5701 I jxcore-log: 
,11-21 16:25:54.360  5653  5701 I jxcore-log: 2016-11-21 15:25:54 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js'
11-21 16:25:54.360  5653  5701 I jxcore-log: 
,11-21 16:25:54.370  5653  5701 I jxcore-log: 2016-11-21 15:25:54 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js'
11-21 16:25:54.370  5653  5701 I jxcore-log: 
,11-21 16:25:54.377  5653  5701 I jxcore-log: 2016-11-21 15:25:54 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js'
11-21 16:25:54.377  5653  5701 I jxcore-log: 
,11-21 16:25:54.398  5653  5701 I jxcore-log: 2016-11-21 15:25:54 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testUsn.js'
11-21 16:25:54.398  5653  5701 I jxcore-log: 
,11-21 16:25:54.404  5653  5701 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: SUPPORTED
,11-21 16:25:54.405  5653  5701 I jxcore-log: 2016-11-21 15:25:54 - INFO testUtils: 'BLE multiple advertisement supported'
11-21 16:25:54.405  5653  5701 I jxcore-log: 
,11-21 16:25:54.515  5653  5701 I jxcore-log: 2016-11-21 15:25:54 - DEBUG CoordinatedClient: 'connected to the test server'
11-21 16:25:54.515  5653  5701 I jxcore-log: 
,11-21 16:25:54.633  5653  5701 I jxcore-log: 2016-11-21 15:25:54 - ERROR CoordinatedClient: 'device disqualified from the test server, reason: 'Native unit tests failed''
11-21 16:25:54.633  5653  5701 I jxcore-log: 
,11-21 16:25:54.636  5653  5701 I jxcore-log: 2016-11-21 15:25:54 - DEBUG CoordinatedClient: 'test client failed'
11-21 16:25:54.636  5653  5701 I jxcore-log: 
,11-21 16:25:54.639  5653  5701 I jxcore-log: 2016-11-21 15:25:54 - DEBUG CoordinatedClient: 'device disconnected from the test server'
11-21 16:25:54.639  5653  5701 I jxcore-log: 
,11-21 16:25:54.643  5653  5701 I jxcore-log: 2016-11-21 15:25:54 - ERROR CoordinatedThaliTape: 'tests failed, error: 'Error: Test client failed: Native unit tests failed', stack: 'CoordinatedClient.prototype._disqualify/<@/data/data/com.test.thalitest/files/www/jxcore/lib/CoordinatedClient.js:187:20
11-21 16:25:54.643  5653  5701 I jxcore-log: tryCatcher@/data/data/com.test.thalitest/files/www/jxcore/node_modules/bluebird/js/release/util.js:16:16
11-21 16:25:54.643  5653  5701 I jxcore-log: module.exports/Promise.prototype._settlePromiseFromHandler@/data/data/com.test.thalitest/files/www/jxcore/node_modules/bluebird/js/release/promise.js:510:13
11-21 16:25:54.643  5653  5701 I jxcore-log: module.exports/Promise.prototype._settlePromise@/data/data/com.test.thalitest/files/www/jxcore/node_modules/bluebird/js/release/promise.js:567:13
11-21 16:25:54.643  5653  5701 I jxcore-log: module.exports/Promise.prototype._settlePromise0@/data/data/com.test.thalitest/files/www/jxcore/node_modules/bluebird/js/release/promise.js:612:5
11-21 16:25:54.643  5653  5701 I jxcore-log: module.exports/Promise.prototype._settlePromises@/data/data/com.test.thalitest/files/www/jxcore/node_modules/bluebird/js/release/promise.js:691:13''
11-21 16:25:54.643  5653  5701 I jxcore-log: 
,11-21 16:25:54.644  5653  5701 I jxcore-log: 2016-11-21 15:25:54 - DEBUG CoordinatedThaliTape: '****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****'
11-21 16:25:54.644  5653  5701 I jxcore-log: 
,11-21 16:25:54.648  5653  5701 I jxcore-log: 2016-11-21 15:25:54 - ERROR runTests: 'Test client failed: Native unit tests failed
11-21 16:25:54.648  5653  5701 I jxcore-log: CoordinatedClient.prototype._disqualify/<@/data/data/com.test.thalitest/files/www/jxcore/lib/CoordinatedClient.js:187:20
11-21 16:25:54.648  5653  5701 I jxcore-log: tryCatcher@/data/data/com.test.thalitest/files/www/jxcore/node_modules/bluebird/js/release/util.js:16:16
11-21 16:25:54.648  5653  5701 I jxcore-log: module.exports/Promise.prototype._settlePromiseFromHandler@/data/data/com.test.thalitest/files/www/jxcore/node_modules/bluebird/js/release/promise.js:510:13
11-21 16:25:54.648  5653  5701 I jxcore-log: module.exports/Promise.prototype._settlePromise@/data/data/com.test.thalitest/files/www/jxcore/node_modules/bluebird/js/release/promise.js:567:13
11-21 16:25:54.648  5653  5701 I jxcore-log: module.exports/Promise.prototype._settlePromise0@/data/data/com.test.thalitest/files/www/jxcore/node_modules/bluebird/js/release/promise.js:612:5
11-21 16:25:54.648  5653  5701 I jxcore-log: module.exports/Promise.prototype._settlePromises@/data/data/com.test.thalitest/files/www/jxcore/node_modules/bluebird/js/release/promise.js:691:13'
11-21 16:25:54.648  5653  5701 I jxcore-log: 
,11-21 16:25:55.133  5906  5906 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,11-21 16:25:55.153  5906  5906 D AndroidRuntime: CheckJNI is OFF
,11-21 16:25:55.181  5906  5906 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,11-21 16:25:55.219  5906  5906 I Radio-JNI: register_android_hardware_Radio DONE
,11-21 16:25:55.237  5906  5906 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,11-21 16:25:55.248   927   940 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=-1: uninstall pkg
,11-21 16:25:55.249   927   940 I ActivityManager: Killing 5653:com.test.thalitest/u0a77 (adj 0): stop com.test.thalitest
,11-21 16:25:55.293   927  3006 W InputDispatcher: channel '74c7f2a com.test.thalitest/com.test.thalitest.MainActivity (server)' ~ Consumer closed input channel or an error occurred.  events=0x9
,11-21 16:25:55.293   927  3006 E InputDispatcher: channel '74c7f2a com.test.thalitest/com.test.thalitest.MainActivity (server)' ~ Channel is unrecoverably broken and will be disposed!
,11-21 16:25:55.300   927  3039 D WifiService: Client connection lost with reason: 4
,11-21 16:25:55.301   927  5426 D GraphicsStats: Buffer count: 2
,11-21 16:25:55.301   927  3933 I WindowState: WIN DEATH: Window{74c7f2a u0 com.test.thalitest/com.test.thalitest.MainActivity}
11-21 16:25:55.301   927  3933 W InputDispatcher: Attempted to unregister already unregistered input channel '74c7f2a com.test.thalitest/com.test.thalitest.MainActivity (server)'
,11-21 16:25:55.318   927   940 W ActivityManager: Force removing ActivityRecord{8bb24c3 u0 com.test.thalitest/.MainActivity t70}: app died, no saved state
,11-21 16:25:55.392   927   950 I art     : Starting a blocking GC Explicit
,11-21 16:25:55.397   927   938 W ActivityManager: Spurious death for ProcessRecord{1b3887d 0:com.test.thalitest/u0a77}, curProc for 5653: null
,11-21 16:25:55.425   927   938 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 5653 uid 10077
,11-21 16:25:55.424   938   938 W Binder_2: type=1400 audit(0.0:126): avc: denied { ioctl } for path="socket:[28119]" dev="sockfs" ino=28119 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
11-21 16:25:55.424   938   938 W Binder_2: type=1400 audit(0.0:127): avc: denied { ioctl } for path="socket:[28119]" dev="sockfs" ino=28119 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
11-21 16:25:55.433  3721  3721 I Keyboard.Facilitator: onFinishInput()
,11-21 16:25:55.483  4012  5918 I MicroRecognitionRnrImpl: Starting detection.
,11-21 16:25:55.485  4012  5919 I MicrophoneInputStream: mic_starting com.google.android.apps.gsa.speech.audio.x@94bc339
,11-21 16:25:55.487   514  5921 I AudioFlinger: AudioFlinger's thread 0xf1f00000 ready to run
11-21 16:25:55.488   927   950 I art     : Explicit concurrent mark sweep GC freed 67878(4MB) AllocSpace objects, 13(340KB) LOS objects, 33% free, 28MB/43MB, paused 2.291ms total 95.788ms
,11-21 16:25:55.492   514  3063 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
,11-21 16:25:55.493  4012  5919 I MicrophoneInputStream: mic_started com.google.android.apps.gsa.speech.audio.x@94bc339
,11-21 16:25:55.503   514  5921 D audio_hw_primary: select_devices: out_snd_device(0: none) in_snd_device(63: voice-rec-mic)
,11-21 16:25:55.504   514  5921 D msm8974_platform: platform_send_audio_calibration: sending audio calibration for snd_device(63) acdb_id(62)
,11-21 16:25:55.504   514  5921 I ACDB-LOADER: ACDB AFE returned = -19
11-21 16:25:55.504   514  5921 I soundtrigger: audio_extn_sound_trigger_update_device_status: device 0x3f of type 1 for Event 1
11-21 16:25:55.504   514  5921 D sound_trigger_platform: platform_stdev_check_and_update_concurrency: concurrency active 0, tx 1, rx 0, concurrency session_allowed 0
11-21 16:25:55.504   514  5921 D audio_hw_primary: enable_snd_device: snd_device(63: voice-rec-mic)
,11-21 16:25:55.511   514  5921 D audio_hw_primary: enable_audio_route: apply and update mixer path: audio-record
,11-21 16:25:55.514   927   950 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
11-21 16:25:55.516  5906  5906 I art     : System.exit called, status: 0
11-21 16:25:55.516  5906  5906 I AndroidRuntime: VM exiting with result code 0.
,11-21 16:25:55.521   927   950 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=0: pkg removed
,11-21 16:25:55.531  3721  3721 I Keyboard.Facilitator: resetDictionaries() : en_US
,11-21 16:25:55.531  5756  5756 D BluetoothMapAppObserver: onReceive
,11-21 16:25:55.532  5756  5756 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
,11-21 16:25:55.536  4160  4244 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,11-21 16:25:55.536   927  3007 I InputReader: Reconfiguring input devices.  changes=0x00000010
,11-21 16:25:55.545  3721  5925 I Keyboard.Facilitator.DecoderInitializer: run()
,11-21 16:25:55.555  3721  5925 I Decoder : createOrResetDecoder
,11-21 16:25:55.576  3464  5928 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,11-21 16:25:55.605  4012  4012 I HotwordWorkerImpl: onReady
,11-21 16:25:55.611  3647  3647 I ConfigService: onCreate
,11-21 16:25:55.615  3848  3848 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,11-21 16:25:55.617    13    13 W kworker/1:0: type=1400 audit(0.0:128): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-21 16:25:55.624    13    13 W kworker/1:0: type=1400 audit(0.0:129): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-21 16:25:55.630   927   927 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,11-21 16:25:55.637    13    13 W kworker/1:0: type=1400 audit(0.0:130): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-21 16:25:55.640  3863  3981 E SQLiteLog: (3850) statement aborts at 23: [DELETE FROM icons WHERE componentName LIKE ? AND profileId = ?] disk I/O error
,11-21 16:25:55.641   927   939 W AtomicFile: Couldn't rename file /data/system/users/0/runtime-permissions.xml to backup file /data/system/users/0/runtime-permissions.xml.bak
11-21 16:25:55.642  3721  5925 I Keyboard.Facilitator.MainLanguageModelLoader: run()
11-21 16:25:55.642   927   939 E PackageManager: Failed to write settings, restoring backup
11-21 16:25:55.642   927   939 E PackageManager: java.io.IOException: Couldn't create directory /data/system/users/0/runtime-permissions.xml
11-21 16:25:55.642   927   939 E PackageManager: 	at android.util.AtomicFile.startWrite(AtomicFile.java:106)
11-21 16:25:55.642   927   939 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.writePermissionsSync(Settings.java:4615)
11-21 16:25:55.642   927   939 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.-wrap1(Settings.java)
11-21 16:25:55.642   927   939 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence$MyHandler.handleMessage(Settings.java:4830)
11-21 16:25:55.642   927   939 E PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-21 16:25:55.642   927   939 E PackageManager: 	at android.os.Looper.loop(Looper.java:148)
11-21 16:25:55.642   927   939 E PackageManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,11-21 16:25:55.645   927   940 E DropBoxManagerService: Can't write: system_server_wtf
11-21 16:25:55.645   927   940 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop15.tmp: open failed: EROFS (Read-only file system)
11-21 16:25:55.645   927   940 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
11-21 16:25:55.645   927   940 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
11-21 16:25:55.645   927   940 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
11-21 16:25:55.645   927   940 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
11-21 16:25:55.645   927   940 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
11-21 16:25:55.645   927   940 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
11-21 16:25:55.645   927   940 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12561)
11-21 16:25:55.645   927   940 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.handleApplicationWtfInner(ActivityManagerService.java:12374)
11-21 16:25:55.645   927   940 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:12346)
11-21 16:25:55.645   927   940 E DropBoxManagerService: 	at android.os.Handler.handleCallback(Handler.java:739)
11-21 16:25:55.645   927   940 E DropBoxManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:95)
11-21 16:25:55.645   927   940 E DropBoxManagerService: 	at android.os.Looper.loop(Looper.java:148)
11-21 16:25:55.645   927   940 E DropBoxManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
11-21 16:25:55.645   927   940 E DropBoxManagerService: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
11-21 16:25:55.645   927   940 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
11-21 16:25:55.645   927   940 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
11-21 16:25:55.645   927   940 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
11-21 16:25:55.645   927   940 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
11-21 16:25:55.645   927   940 E DropBoxManagerService: 	... 13 more
,11-21 16:25:55.646  3647  3647 E SQLiteLog: (3850) statement aborts at 26: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
11-21 16:25:55.647  3647  3647 D AndroidRuntime: Shutting down VM
--------- beginning of crash
11-21 16:25:55.648  3647  3647 E AndroidRuntime: FATAL EXCEPTION: main
11-21 16:25:55.648  3647  3647 E AndroidRuntime: Process: com.google.process.gapps, PID: 3647
11-21 16:25:55.648  3647  3647 E AndroidRuntime: java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
11-21 16:25:55.648  3647  3647 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2732)
11-21 16:25:55.648  3647  3647 E AndroidRuntime: 	at android.app.ActivityThread.-wrap14(ActivityThread.java)
11-21 16:25:55.648  3647  3647 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1421)
11-21 16:25:55.648  3647  3647 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-21 16:25:55.648  3647  3647 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
11-21 16:25:55.648  3647  3647 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-21 16:25:55.648  3647  3647 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
11-21 16:25:55.648  3647  3647 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-21 16:25:55.648  3647  3647 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-21 16:25:55.648  3647  3647 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
11-21 16:25:55.648  3647  3647 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
11-21 16:25:55.648  3647  3647 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
11-21 16:25:55.648  3647  3647 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
11-21 16:25:55.648  3647  3647 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
11-21 16:25:55.648  3647  3647 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
11-21 16:25:55.648  3647  3647 E AndroidRuntime: 	at com.google.android.gms.gcm.bg.a(SourceFile:310)
11-21 16:25:55.648  3647  3647 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
11-21 16:25:55.648  3647  3647 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
11-21 16:25:55.648  3647  3647 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2725)
11-21 16:25:55.648  3647  3647 E AndroidRuntime: 	... 8 more
,11-21 16:25:55.657   927  3224 I ActivityManager: Start proc 5932:com.google.android.googlequicksearchbox:crash_report/u0a29 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
,11-21 16:25:55.658  3863  3981 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
11-21 16:25:55.658  3863  3981 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 3863
11-21 16:25:55.658  3863  3981 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
11-21 16:25:55.658  3863  3981 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
11-21 16:25:55.658  3863  3981 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
11-21 16:25:55.658  3863  3981 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
11-21 16:25:55.658  3863  3981 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
11-21 16:25:55.658  3863  3981 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
11-21 16:25:55.658  3863  3981 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
11-21 16:25:55.658  3863  3981 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
11-21 16:25:55.658  3863  3981 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
11-21 16:25:55.658  3863  3981 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
11-21 16:25:55.658  3863  3981 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
11-21 16:25:55.658  3863  3981 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,11-21 16:25:55.665   927  5938 E DropBoxManagerService: Can't write: system_app_crash
11-21 16:25:55.665   927  5938 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop112.tmp: open failed: EROFS (Read-only file system)
11-21 16:25:55.665   927  5938 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
11-21 16:25:55.665   927  5938 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
11-21 16:25:55.665   927  5938 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
11-21 16:25:55.665   927  5938 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
11-21 16:25:55.665   927  5938 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
11-21 16:25:55.665   927  5938 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
11-21 16:25:55.665   927  5938 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
11-21 16:25:55.665   927  5938 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
11-21 16:25:55.665   927  5938 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
11-21 16:25:55.665   927  5938 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
11-21 16:25:55.665   927  5938 E DropBoxManagerService: 	... 5 more
,11-21 16:25:55.665   927  4302 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,11-21 16:25:55.668   927  5942 E DropBoxManagerService: Can't write: system_app_crash
11-21 16:25:55.668   927  5942 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop113.tmp: open failed: EROFS (Read-only file system)
11-21 16:25:55.668   927  5942 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
11-21 16:25:55.668   927  5942 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
11-21 16:25:55.668   927  5942 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
11-21 16:25:55.668   927  5942 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
11-21 16:25:55.668   927  5942 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
11-21 16:25:55.668   927  5942 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
11-21 16:25:55.668   927  5942 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
11-21 16:25:55.668   927  5942 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
11-21 16:25:55.668   927  5942 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
11-21 16:25:55.668   927  5942 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
11-21 16:25:55.668   927  5942 E DropBoxManagerService: 	... 5 more
11-21 16:25:55.669  4012  4026 W SearchService: Abort, client detached.
,11-21 16:25:55.673  4012  4012 I HotwordDetector: Closing mic
,11-21 16:25:55.673  4012  4245 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@94bc339
11-21 16:25:55.673  4012  5919 E AudioRecord-JNI: Error -4 during AudioRecord native read
,11-21 16:25:55.681  2644  2644 W Binder_3: type=1400 audit(0.0:131): avc: denied { ioctl } for path="socket:[20893]" dev="sockfs" ino=20893 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-21 16:25:55.681  2644  2644 W Binder_3: type=1400 audit(0.0:132): avc: denied { ioctl } for path="socket:[20893]" dev="sockfs" ino=20893 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-21 16:25:55.684  2644  2644 W Binder_3: type=1400 audit(0.0:133): avc: denied { ioctl } for path="socket:[33129]" dev="sockfs" ino=33129 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-21 16:25:55.684  2644  2644 W Binder_3: type=1400 audit(0.0:134): avc: denied { ioctl } for path="socket:[33129]" dev="sockfs" ino=33129 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
11-21 16:25:55.687   927  5946 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,11-21 16:25:55.689  3464  5928 E SQLiteLog: (3850) statement aborts at 18: [DELETE FROM calls WHERE (((source_package = 'com.test.thalitest'))) AND ((type = 4))] disk I/O error
,11-21 16:25:55.695  3464  5928 E AndroidRuntime: FATAL EXCEPTION: IntentService[VoicemailCleanupService]
11-21 16:25:55.695  3464  5928 E AndroidRuntime: Process: android.process.acore, PID: 3464
11-21 16:25:55.695  3464  5928 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
11-21 16:25:55.695  3464  5928 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
11-21 16:25:55.695  3464  5928 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
11-21 16:25:55.695  3464  5928 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
11-21 16:25:55.695  3464  5928 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
11-21 16:25:55.695  3464  5928 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
11-21 16:25:55.695  3464  5928 E AndroidRuntime: 	at com.android.providers.contacts.DbModifierWithNotification.delete(DbModifierWithNotification.java:197)
11-21 16:25:55.695  3464  5928 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:219)
11-21 16:25:55.695  3464  5928 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
11-21 16:25:55.695  3464  5928 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
11-21 16:25:55.695  3464  5928 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
11-21 16:25:55.695  3464  5928 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
11-21 16:25:55.695  3464  5928 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
11-21 16:25:55.695  3464  5928 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
11-21 16:25:55.695  3464  5928 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-21 16:25:55.695  3464  5928 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
11-21 16:25:55.695  3464  5928 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,11-21 16:25:55.714   927  5948 E DropBoxManagerService: Can't write: system_app_crash
11-21 16:25:55.714   927  5948 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop115.tmp: open failed: EROFS (Read-only file system)
11-21 16:25:55.714   927  5948 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
11-21 16:25:55.714   927  5948 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
11-21 16:25:55.714   927  5948 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
11-21 16:25:55.714   927  5948 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
11-21 16:25:55.714   927  5948 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
11-21 16:25:55.714   927  5948 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
11-21 16:25:55.714   927  5948 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
11-21 16:25:55.714   927  5948 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
11-21 16:25:55.714   927  5948 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
11-21 16:25:55.714   927  5948 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
11-21 16:25:55.714   927  5948 E DropBoxManagerService: 	... 5 more
,11-21 16:25:55.714  3721  5925 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /data/user/0/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
,11-21 16:25:55.716  3721  5925 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
,11-21 16:25:55.716  3721  5925 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
11-21 16:25:55.718  3721  5925 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Contacts.dict
11-21 16:25:55.719  3721  5925 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = history
,11-21 16:25:55.721  3721  5925 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loaded File = UserHistory.en_US.dict
11-21 16:25:55.721  3721  5925 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = user
11-21 16:25:55.721  3721  5925 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Personal.en_US.dict
11-21 16:25:55.721  3721  5925 I Keyboard.Facilitator.PersonalDictionaryLoader: run() : Loaded (exit)
,11-21 16:25:55.721  3721  5925 I Keyboard.Facilitator.Delight2FileSweeper: run()
,11-21 16:25:55.723  3721  5925 I Keyboard.Facilitator.RecurringTaskScheduler: run()
,11-21 16:25:55.724  3721  5925 I StatsUtilsManager: startPeriodStatsRecorder() : Success
11-21 16:25:55.724  3721  5925 I PeriodicStatsRecorder: shouldRecordStats() = Too Soon
,11-21 16:25:55.743   514  5921 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
,11-21 16:25:55.744   514  5921 D audio_hw_primary: disable_snd_device: snd_device(63: voice-rec-mic)
,11-21 16:25:55.748   514  5921 I soundtrigger: audio_extn_sound_trigger_update_device_status: device 0x3f of type 1 for Event 0
,11-21 16:25:55.748   514  5921 D sound_trigger_platform: platform_stdev_check_and_update_concurrency: concurrency active 0, tx 0, rx 0, concurrency session_allowed 1
,11-21 16:25:55.748   514  3063 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
,11-21 16:25:55.750  4012  4246 I MicroRecognitionRnrImpl: Stopping hotword detection.
11-21 16:25:55.751  4012  5918 I MicroRecognitionRnrImpl: Detection finished
,11-21 16:25:56.035   383   482 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0

```
