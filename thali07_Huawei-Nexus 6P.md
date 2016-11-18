#### Test 93765317141d42a_thali07_Huawei-Nexus 6P Logs


```
--------- beginning of main
11-18 16:47:46.043  3937  4193 I Icing   : Indexing 3C763AF371F9E97B4ECFEA01A338ADB468C38476 from com.google.android.googlequicksearchbox
,11-18 16:47:46.124  3937  4193 I Icing   : Indexing done 3C763AF371F9E97B4ECFEA01A338ADB468C38476
11-18 16:47:46.498  5582  5582 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
11-18 16:47:46.503  5582  5582 D AndroidRuntime: CheckJNI is OFF
11-18 16:47:46.526  5582  5582 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
11-18 16:47:46.568  5582  5582 I Radio-JNI: register_android_hardware_Radio DONE
11-18 16:47:46.582  5582  5582 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
11-18 16:47:46.595   929  3585 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
11-18 16:47:46.613  5582  5582 D AndroidRuntime: Shutting down VM
11-18 16:47:46.619  3955  3968 W SearchService: Abort, client detached.
11-18 16:47:46.621  3955  3955 I HotwordDetector: Closing mic
11-18 16:47:46.621  3955  4146 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@92b0b7e
11-18 16:47:46.626  3955  4157 E AudioRecord-JNI: Error -4 during AudioRecord native read
11-18 16:47:46.648   929  3763 I ActivityManager: Start proc 5591:com.test.thalitest/u0a77 for activity com.test.thalitest/.MainActivity
11-18 16:47:46.691   514  4160 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
11-18 16:47:46.692   514  4160 D audio_hw_primary: disable_snd_device: snd_device(63: voice-rec-mic)
11-18 16:47:46.696   514  4160 I soundtrigger: audio_extn_sound_trigger_update_device_status: device 0x3f of type 1 for Event 0
11-18 16:47:46.696   514  4160 D sound_trigger_platform: platform_stdev_check_and_update_concurrency: concurrency active 0, tx 0, rx 0, concurrency session_allowed 1
11-18 16:47:46.697   514  2987 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
11-18 16:47:46.700  3955  4147 I MicroRecognitionRnrImpl: Stopping hotword detection.
11-18 16:47:46.700  3955  4154 I MicroRecognitionRnrImpl: Detection finished
11-18 16:47:46.737  5591  5591 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011750)
11-18 16:47:46.769  5591  5591 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
11-18 16:47:46.829  5591  5591 I LibraryLoader: Time to load native libraries: 57 ms (timestamps 4713-4770)
11-18 16:47:46.829  5591  5591 I LibraryLoader: Expected native library version number "",actual native library version number ""
,11-18 16:47:46.860  5591  5591 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {814f401}
,11-18 16:47:46.860  5591  5591 I LibraryLoader: Expected native library version number "",actual native library version number ""
11-18 16:47:46.860  5591  5591 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,11-18 16:47:46.863  5591  5591 I BrowserStartupController: Initializing chromium process, singleProcess=true
,11-18 16:47:46.864  5591  5591 E SysUtils: ApplicationContext is null in ApplicationStatus
,11-18 16:47:46.918  5591  5591 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,11-18 16:47:46.927  5591  5591 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,11-18 16:47:46.927  5591  5591 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
11-18 16:47:46.927  5591  5591 I Adreno  : QUALCOMM build                   : 63c06b2, I8366cd0437
11-18 16:47:46.927  5591  5591 I Adreno  : Build Date                       : 12/06/15
11-18 16:47:46.927  5591  5591 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
11-18 16:47:46.927  5591  5591 I Adreno  : Local Branch                     : mybranch17112971
11-18 16:47:46.927  5591  5591 I Adreno  : Remote Branch                    : quic/LA.BF64.1.2.9_v2
11-18 16:47:46.927  5591  5591 I Adreno  : Remote Branch                    : NONE
11-18 16:47:46.927  5591  5591 I Adreno  : Reconstruct Branch               : NOTHING
,11-18 16:47:46.968   929   946 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@aec0c2f:true
,11-18 16:47:47.003   402   402 W Binder_2: type=1400 audit(0.0:99): avc: denied { ioctl } for path="socket:[28234]" dev="sockfs" ino=28234 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-18 16:47:47.003   402   402 W Binder_2: type=1400 audit(0.0:100): avc: denied { ioctl } for path="socket:[28234]" dev="sockfs" ino=28234 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-18 16:47:47.016  5591  5591 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,11-18 16:47:47.024  5591  5591 D SystemWebViewEngine: CordovaWebView is running on device made by: Huawei
,11-18 16:47:47.046  2382  2382 W Binder_3: type=1400 audit(0.0:101): avc: denied { ioctl } for path="socket:[32921]" dev="sockfs" ino=32921 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-18 16:47:47.046  2382  2382 W Binder_3: type=1400 audit(0.0:102): avc: denied { ioctl } for path="socket:[32921]" dev="sockfs" ino=32921 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
11-18 16:47:47.051  5591  5628 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,11-18 16:47:47.053  3585  3585 W Binder_6: type=1400 audit(0.0:103): avc: denied { ioctl } for path="socket:[32142]" dev="sockfs" ino=32142 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-18 16:47:47.053  3585  3585 W Binder_6: type=1400 audit(0.0:104): avc: denied { ioctl } for path="socket:[32142]" dev="sockfs" ino=32142 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-18 16:47:47.058  5591  5615 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,11-18 16:47:47.092  5591  5628 I OpenGLRenderer: Initialized EGL, version 1.4
,11-18 16:47:47.175   929   947 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +553ms
11-18 16:47:47.170  3190  3190 W Binder_4: type=1400 audit(0.0:105): avc: denied { ioctl } for path="socket:[33892]" dev="sockfs" ino=33892 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-18 16:47:47.170  3190  3190 W Binder_4: type=1400 audit(0.0:106): avc: denied { ioctl } for path="socket:[33892]" dev="sockfs" ino=33892 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
11-18 16:47:47.173  3652  3652 W Binder_8: type=1400 audit(0.0:107): avc: denied { ioctl } for path="socket:[33891]" dev="sockfs" ino=33891 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
11-18 16:47:47.176  3645  3645 I Keyboard.Facilitator: onFinishInput()
11-18 16:47:47.173  3652  3652 W Binder_8: type=1400 audit(0.0:108): avc: denied { ioctl } for path="socket:[33891]" dev="sockfs" ino=33891 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-18 16:47:47.207  5591  5591 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 5591
,11-18 16:47:47.367  5591  5591 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,11-18 16:47:47.519  5591  5631 D jxcore_app_log: JniHelper::setJavaVM(0xf547c000), pthread_self() = -561772240
,11-18 16:47:47.524  5591  5631 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
11-18 16:47:47.524  5591  5631 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
11-18 16:47:47.524  5591  5631 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
11-18 16:47:47.524  5591  5631 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
11-18 16:47:47.524  5591  5631 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,11-18 16:47:47.524  5591  5631 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@624d2b5 added. We now have 1 listener(s)
,11-18 16:47:47.527  5591  5631 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 60:83:34:25:D7:D4
,11-18 16:47:47.527  5591  5631 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-18 16:47:47.527  5591  5631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,11-18 16:47:47.528  5591  5631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,11-18 16:47:47.530  5591  5631 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
11-18 16:47:47.530  5591  5631 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
11-18 16:47:47.530  5591  5631 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
11-18 16:47:47.530  5591  5631 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 60:83:34:25:D7:D4
11-18 16:47:47.530  5591  5631 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
11-18 16:47:47.530  5591  5631 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
11-18 16:47:47.530  5591  5631 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
11-18 16:47:47.530  5591  5631 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
11-18 16:47:47.530  5591  5631 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
11-18 16:47:47.530  5591  5631 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
11-18 16:47:47.530  5591  5631 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
11-18 16:47:47.530  5591  5631 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
11-18 16:47:47.530  5591  5631 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
11-18 16:47:47.530  5591  5631 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
11-18 16:47:47.530  5591  5631 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c2b0dd8 added. We now have 1 listener(s)
11-18 16:47:47.531  5591  5631 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-18 16:47:47.535   929  2940 D WifiService: New client listening to asynchronous messages
,11-18 16:47:47.536  5591  5631 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
11-18 16:47:47.536  5591  5631 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
,11-18 16:47:47.536  5591  5631 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[JavaBridge,5,main], id: 55
11-18 16:47:47.537  5591  5631 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
,11-18 16:47:47.537  5591  5631 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
11-18 16:47:47.537  5591  5631 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
11-18 16:47:47.538  5591  5631 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[JavaBridge,5,main], id: 55
,11-18 16:47:47.540  5591  5631 I io.jxcore.node.LifeCycleMonitor: start: OK
,11-18 16:47:47.655  5591  5591 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,11-18 16:47:48.035  5591  5600 I art     : Background sticky concurrent mark sweep GC freed 79789(7MB) AllocSpace objects, 16(1476KB) LOS objects, 26% free, 24MB/32MB, paused 1.381ms total 269.519ms
,11-18 16:47:48.420  5591  5638 W jxcore-log: Initializing JXcore engine
,11-18 16:47:48.420  5591  5638 W jxcore-log: JXcore engine is ready
,11-18 16:47:48.440  5638  5638 W Thread-61: type=1400 audit(0.0:109): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=12040 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,11-18 16:47:48.443  5638  5638 W Thread-61: type=1400 audit(0.0:110): avc: denied { ioctl } for path="socket:[14388]" dev="sockfs" ino=14388 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
11-18 16:47:48.443  5638  5638 W Thread-61: type=1400 audit(0.0:111): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=5964 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
11-18 16:47:48.443  5638  5638 W Thread-61: type=1400 audit(0.0:112): avc: denied { ioctl } for path="socket:[33865]" dev="sockfs" ino=33865 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:untrusted_app:s0:c512,c768 tclass=netlink_route_socket permissive=0
,11-18 16:47:48.460  5591  5638 W jxcore-log: Starting JXcore engine
,11-18 16:47:48.510  5591  5638 W jxcore-log: Platform android
11-18 16:47:48.510  5591  5638 W jxcore-log: 
,11-18 16:47:48.510  5591  5638 W jxcore-log: Process ARCH arm
11-18 16:47:48.510  5591  5638 W jxcore-log: 
,11-18 16:47:48.650  5591  5638 I jxcore-log: JXcore Cordova bridge is ready!
11-18 16:47:48.650  5591  5638 I jxcore-log: 
,11-18 16:47:48.650  5591  5638 W jxcore-log: JXcore engine is started
,11-18 16:47:48.657  5591  5631 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,11-18 16:47:48.663  5591  5591 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,11-18 16:47:50.137  3569  3569 I ConfigService: onDestroy
,11-18 16:47:51.634   929  3147 I ActivityManager: Killing 5142:com.google.android.youtube/u0a75 (adj 15): empty #17
,11-18 16:47:52.527   929  2941 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,11-18 16:47:52.638  3955  3955 I art     : Waiting for a blocking GC DisableMovingGc
,11-18 16:47:52.645  3955  3955 I art     : WaitForGcToComplete blocked for 7.189ms for cause DisableMovingGc
,11-18 16:47:52.645  3955  3955 I art     : Starting a blocking GC DisableMovingGc
,11-18 16:47:53.459   929  2939 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-18 16:47:55.550   929  2941 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,11-18 16:47:55.607   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-18 16:47:56.609   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-18 16:47:57.610   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-18 16:47:58.388  5591  5638 I jxcore-log: 2016-11-18 15:47:58 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
11-18 16:47:58.388  5591  5638 I jxcore-log: 
,11-18 16:47:58.390  5591  5638 I jxcore-log: 2016-11-18 15:47:58 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
11-18 16:47:58.390  5591  5638 I jxcore-log: 
,11-18 16:47:58.395  5591  5638 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
11-18 16:47:58.396  5591  5638 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-18 16:47:58.396  5591  5638 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-18 16:47:58.396  5591  5638 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-18 16:47:58.396  5591  5638 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-18 16:47:58.396  5591  5638 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-18 16:47:58.396  5591  5638 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-18 16:47:58.396  5591  5638 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-18 16:47:58.396  5591  5638 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-18 16:47:58.396  5591  5638 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,11-18 16:47:58.397  5591  5638 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
,11-18 16:47:58.400  5591  5638 I jxcore-log: 2016-11-18 15:47:58 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
11-18 16:47:58.400  5591  5638 I jxcore-log: 
11-18 16:47:58.402  5591  5638 I jxcore-log: 2016-11-18 15:47:58 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
11-18 16:47:58.402  5591  5638 I jxcore-log: 
,11-18 16:47:58.611   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-18 16:47:58.650  5591  5638 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,11-18 16:47:58.650  5591  5638 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d8ad629 added. We now have 2 listener(s)
11-18 16:47:58.651  5591  5638 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-18 16:47:58.651  5591  5638 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,11-18 16:47:58.651  5591  5638 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-18 16:47:58.651  5591  5638 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-18 16:47:58.651  5591  5638 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e13ddae added. We now have 2 listener(s)
11-18 16:47:58.651  5591  5638 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-18 16:47:58.652  5591  5638 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
11-18 16:47:58.653  5591  5638 D ExecuteNativeTests: Running unit tests
,11-18 16:47:58.654  5591  5638 D BluetoothAdapter: enable(): BT is already enabled..!
,11-18 16:47:58.654   929   940 D WifiService: setWifiEnabled: true pid=5591, uid=10077
11-18 16:47:58.654   929   940 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-18 16:47:59.612   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-18 16:47:59.680   929   942 I ActivityManager: Killing 5231:org.codeaurora.ims/1001 (adj 15): empty #17
,11-18 16:47:59.794  3955  5641 W CronetSyncConnectionRcs: Upload content type not set.
,11-18 16:47:59.800   929  3805 I ActivityManager: Start proc 5644:com.google.android.youtube/u0a75 for service com.google.android.youtube/com.google.android.libraries.youtube.common.gcore.gcoreclient.gcm.impl.GcmTaskServiceDelegator
,11-18 16:47:59.828  3937  5643 I EventLogService: Aggregate from 1479482268531 (log), 1479482268531 (data)
,11-18 16:47:59.833  5644  5644 W System  : ClassLoader referenced unknown path: /system/app/YouTube/lib/arm64
,11-18 16:47:59.904  5644  5658 W System  : ClassLoader referenced unknown path: /system/priv-app/PrebuiltGmsCore/lib/arm64
,11-18 16:47:59.976  5644  5658 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 241 native methods...
,11-18 16:48:00.014  5644  5658 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,11-18 16:48:00.040  4809  4884 D Finsky  : [184] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,11-18 16:48:00.041  4809  4809 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,11-18 16:48:00.046  5644  5644 W System.err: YouTube MDX: Bogus value in shared preferences for key MdxServerSelection value , returning default value.
,11-18 16:48:00.064  5673  5673 I dex2oat : /system/bin/dex2oat -j2 --dex-file=/data/user/0/com.google.android.youtube/cache/ads-602166154.jar --oat-file=/data/user/0/com.google.android.youtube/cache/ads-602166154.dex
,11-18 16:48:00.101  5673  5673 I dex2oat : dex2oat took 38.168ms (threads: 2) arena alloc=189KB java alloc=37KB native alloc=1258KB free=1045KB
,11-18 16:48:00.178  5644  5644 W InstanceID/Rpc: Found 10012
,11-18 16:48:00.242   929  3763 I ActivityManager: Killing 5272:com.android.settings/1000 (adj 15): empty #17
,11-18 16:48:00.282  3569  5729 I VacuumService: Vacuum at: now=1479484080282 tag=VacuumService
,11-18 16:48:00.613   537   537 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,11-18 16:48:08.660  5591  5638 I com.test.thalitest.ThaliTestRunner: Running UT
,11-18 16:48:08.723  5591  5638 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-18 16:48:08.723  5591  5638 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@512f2d3 added. We now have 3 listener(s)
,11-18 16:48:08.724  5591  5638 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-18 16:48:08.724  5591  5638 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-18 16:48:08.724  5591  5638 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-18 16:48:08.724  5591  5638 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,11-18 16:48:08.724  5591  5638 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@13fde10 added. We now have 3 listener(s)
11-18 16:48:08.725  5591  5638 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-18 16:48:08.725  5591  5638 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,11-18 16:48:08.732  5591  5638 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnConnectionTimeout
11-18 16:48:08.733  5591  5638 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
11-18 16:48:08.733  5591  5638 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,11-18 16:48:08.733  5591  5638 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-18 16:48:08.733  5591  5638 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-18 16:48:08.734  5591  5638 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
,11-18 16:48:08.734  5591  5638 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
11-18 16:48:08.734  5591  5638 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
11-18 16:48:08.734  5591  5638 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-18 16:48:08.734  5591  5638 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,11-18 16:48:08.734  5591  5638 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-18 16:48:08.735  5591  5638 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnBluetoothMacAddressResolved
11-18 16:48:08.735  5591  5638 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
11-18 16:48:08.737  5591  5638 I io.jxcore.node.ConnectionHelperTest: Starting test: testHasMaximumNumberOfConnections
,11-18 16:48:08.738  5591  5638 I io.jxcore.node.ConnectionHelperTest: Starting test: testStart
,11-18 16:48:08.739  5591  5638 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
11-18 16:48:08.740  5591  5638 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-18 16:48:08.741  5591  5638 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
,11-18 16:48:08.757  5591  5638 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-18 16:48:08.757  5591  5638 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-18 16:48:08.757  5591  5638 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-18 16:48:08.757  5591  5638 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-18 16:48:08.757  5591  5638 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-18 16:48:08.757  5591  5638 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-18 16:48:08.757  5591  5638 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-18 16:48:08.757  5591  5638 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-18 16:48:08.757  5591  5638 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,11-18 16:48:08.765  5591  5638 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
,11-18 16:48:08.766  5591  5638 D io.jxcore.node.ConnectivityMonitor: start: OK
11-18 16:48:08.766  5591  5638 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 1
11-18 16:48:08.766  5591  5638 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 0 -> 1
,11-18 16:48:08.767  5591  5638 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-61,5,main], id: 61
11-18 16:48:08.767  5591  5638 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-61,5,main], id: 61
11-18 16:48:08.767  5591  5638 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-61,5,main], id: 61
11-18 16:48:08.767  5591  5638 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,11-18 16:48:08.767  5591  5638 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
11-18 16:48:08.767  5591  5638 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
11-18 16:48:08.767  5591  5638 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-18 16:48:08.768  5591  5638 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
11-18 16:48:08.768  5591  5638 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,11-18 16:48:08.768  5591  5638 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
11-18 16:48:08.768  5591  5638 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
11-18 16:48:08.769  5591  5638 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
11-18 16:48:08.769  5591  5638 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
11-18 16:48:08.769  5591  5638 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,11-18 16:48:08.769  5591  5638 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,11-18 16:48:08.770  5591  5591 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-18 16:48:08.775  5591  5591 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-18 16:48:08.775  5591  5591 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
,11-18 16:48:08.776  5591  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
,11-18 16:48:08.777  5591  5638 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-18 16:48:08.777  5591  5638 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,11-18 16:48:08.777  5591  5638 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,11-18 16:48:08.780  5591  5730 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-18 16:48:08.780  4853  4853 W Binder_3: type=1400 audit(0.0:113): avc: denied { ioctl } for path="socket:[29418]" dev="sockfs" ino=29418 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-18 16:48:08.783  5591  5638 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-61,5,main], id: 61
11-18 16:48:08.780  4853  4853 W Binder_3: type=1400 audit(0.0:114): avc: denied { ioctl } for path="socket:[29418]" dev="sockfs" ino=29418 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-18 16:48:08.784  5591  5638 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-18 16:48:08.784  5591  5730 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,11-18 16:48:08.788  5591  5638 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,11-18 16:48:08.788  5591  5638 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-18 16:48:08.788  5591  5638 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 1
,11-18 16:48:08.791  5591  5638 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
11-18 16:48:08.791  5591  5638 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-61,5,main], id: 61
,11-18 16:48:08.791  5591  5638 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
11-18 16:48:08.791  5591  5638 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: createAdvertiseDataToServiceData 
11-18 16:48:08.792  5591  5638 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-18 16:48:08.792  5591  5638 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 01 60 83 34 25 D7 D4
11-18 16:48:08.793  5591  5638 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-18 16:48:08.793  5591  5638 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: created AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-18 16:48:08.793  5591  5638 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: Current thread: Thread[Thread-61,5,main], id: 61
11-18 16:48:08.793  5591  5638 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: was started = false
,11-18 16:48:08.793  5591  5638 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: advertiseData = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-18 16:48:08.794  5591  5638 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData finished: Current thread: Thread[Thread-61,5,main], id: 61
11-18 16:48:08.794  5591  5638 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
11-18 16:48:08.794  5591  5638 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... adv data = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]Current thread: Thread[Thread-61,5,main], id: 61
11-18 16:48:08.795  5591  5638 D BluetoothAdapter: STATE_ON
,11-18 16:48:08.803  4615  4861 D BtGatt.GattService: registerClient() - UUID=b36e892a-c9c9-4d0f-b056-3922aee66129
11-18 16:48:08.804  4615  4703 D BtGatt.GattService: onClientRegistered() - UUID=b36e892a-c9c9-4d0f-b056-3922aee66129, clientIf=5
11-18 16:48:08.804  5591  5601 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
,11-18 16:48:08.807  4615  4707 D BtGatt.AdvertiseManager: message : 0
11-18 16:48:08.810  4615  4707 D BtGatt.AdvertiseManager: starting multi advertising
,11-18 16:48:08.825  4615  4703 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,11-18 16:48:08.833  4615  4703 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,11-18 16:48:08.834  5591  5638 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment Current thread: Thread[Thread-61,5,main], id: 61
,11-18 16:48:08.834  5591  5638 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTINGCurrent thread: Thread[Thread-61,5,main], id: 61
11-18 16:48:08.834  5591  5638 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
11-18 16:48:08.835  5591  5638 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged default (no call to listener). Current thread: Thread[Thread-61,5,main], id: 61
11-18 16:48:08.835  5591  5638 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-61,5,main], id: 61
11-18 16:48:08.835  5591  5638 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[Thread-61,5,main], id: 61
11-18 16:48:08.835  5591  5638 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[Thread-61,5,main], id: 61
11-18 16:48:08.835  5591  5638 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser started = true Current thread: Thread[Thread-61,5,main], id: 61
11-18 16:48:08.835  5591  5638 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-18 16:48:08.837  5591  5638 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-18 16:48:08.837  5591  5638 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-18 16:48:08.838  5591  5638 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-18 16:48:08.838  5591  5638 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-18 16:48:08.838  5591  5638 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-18 16:48:08.839  5591  5638 I io.jxcore.node.ConnectionHelper: start: OK
11-18 16:48:08.839  5591  5591 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
11-18 16:48:08.840  5591  5591 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess : Current thread: Thread[main,5,main], id: 1
11-18 16:48:08.840  5591  5591 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNINGCurrent thread: Thread[main,5,main], id: 1
11-18 16:48:08.840  5591  5591 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
11-18 16:48:08.840  5591  5591 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  true. Current thread: Thread[main,5,main], id: 1
11-18 16:48:08.841  5591  5591 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[main,5,main], id: 1
11-18 16:48:08.841  5591  5591 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-18 16:48:08.841  5591  5591 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-18 16:48:08.841  5591  5591 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [ADVERTISING]
11-18 16:48:08.841  5591  5591 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-18 16:48:08.841  5591  5591 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.Ble,PeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-18 16:48:08.841  5591  5591 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]Current thread: Thread[main,5,main], id: 1
11-18 16:48:08.841  5591  5591 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
11-18 16:48:08.842  5591  5591 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-18 16:48:08.845  5591  5591 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-18 16:48:08.845  5591  5591 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
11-18 16:48:08.846  5591  5591 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-18 16:48:08.846  5591  5591 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-18 16:48:08.846  5591  5591 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-18 16:48:08.846  5591  5591 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,11-18 16:48:09.344  5591  5638 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-18 16:48:09.344  5591  5638 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,11-18 16:48:09.344  5591  5638 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
,11-18 16:48:09.344  5591  5638 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
11-18 16:48:09.344  5591  5638 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
,11-18 16:48:09.345  5591  5638 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
,11-18 16:48:09.345  5591  5638 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
,11-18 16:48:09.345  5591  5638 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
,11-18 16:48:09.345  5591  5638 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
11-18 16:48:09.345  5591  5638 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
,11-18 16:48:09.346  5591  5638 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
11-18 16:48:09.346  5591  5638 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
11-18 16:48:09.346  5591  5638 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
11-18 16:48:09.346  5591  5638 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
,11-18 16:48:09.346  5591  5638 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
11-18 16:48:09.346  5591  5638 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
11-18 16:48:09.347  5591  5638 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
11-18 16:48:09.347  5591  5638 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
11-18 16:48:09.347  5591  5638 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
11-18 16:48:09.347  5591  5638 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
11-18 16:48:09.347  5591  5638 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
11-18 16:48:09.347  5591  5638 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
,11-18 16:48:09.348  5591  5591 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
11-18 16:48:09.348  5591  5638 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
11-18 16:48:09.348  5591  5591 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
11-18 16:48:09.348  5591  5638 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
11-18 16:48:09.348  5591  5591 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
11-18 16:48:09.348  5591  5638 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
11-18 16:48:09.349  5591  5638 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
,11-18 16:48:09.349  5591  5638 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
11-18 16:48:09.349  5591  5638 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
11-18 16:48:09.350  5591  5638 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
11-18 16:48:09.350  5591  5638 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
11-18 16:48:09.350  5591  5638 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
11-18 16:48:09.350  5591  5638 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
11-18 16:48:09.351  5591  5638 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
11-18 16:48:09.351  5591  5638 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,11-18 16:48:09.352  5591  5638 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
11-18 16:48:09.352  5591  5638 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
11-18 16:48:09.352  5591  5638 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
11-18 16:48:09.353  5591  5730 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
11-18 16:48:09.353  5591  5638 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-18 16:48:09.353  5591  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
11-18 16:48:09.353  5591  5638 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
11-18 16:48:09.354  5591  5638 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
,11-18 16:48:09.354  5591  5730 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
11-18 16:48:09.354  5591  5591 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
11-18 16:48:09.354  5591  5638 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
11-18 16:48:09.354  5591  5638 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-18 16:48:09.355  5591  5638 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
11-18 16:48:09.355  5591  5638 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-18 16:48:09.357  5591  5638 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
11-18 16:48:09.357  5591  5638 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-61,5,main], id: 61
11-18 16:48:09.357  5591  5638 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-18 16:48:09.358  5591  5638 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-61,5,main], id: 61
,11-18 16:48:09.360  5591  5638 D BluetoothAdapter: STATE_ON
,11-18 16:48:09.361  5591  5638 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-18 16:48:09.362  5591  5638 D BluetoothAdapter: STATE_ON
11-18 16:48:09.362  5591  5638 D BluetoothLeScanner: could not find callback wrapper
11-18 16:48:09.363  5591  5638 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-18 16:48:09.363  5591  5638 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-18 16:48:09.363  5591  5638 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-61,5,main], id: 61
11-18 16:48:09.363  5591  5638 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-61,5,main], id: 61
11-18 16:48:09.363  5591  5638 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
11-18 16:48:09.363  5591  5638 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-61,5,main], id: 61
11-18 16:48:09.364  4615  4707 D BtGatt.AdvertiseManager: message : 1
11-18 16:48:09.365  4615  4707 D BtGatt.AdvertiseManager: stop advertise for client 5
,11-18 16:48:09.380  4615  4703 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
,11-18 16:48:09.380  4615  4703 D BtGatt.GattService: Client app is not null!
11-18 16:48:09.381  4615  4853 D BtGatt.GattService: unregisterClient() - clientIf=5
,11-18 16:48:09.382  5591  5638 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,11-18 16:48:09.382  5591  5638 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
11-18 16:48:09.382  5591  5638 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
11-18 16:48:09.382  5591  5638 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  false. Current thread: Thread[Thread-61,5,main], id: 61
11-18 16:48:09.382  5591  5638 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-61,5,main], id: 61
11-18 16:48:09.382  5591  5638 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-61,5,main], id: 61
11-18 16:48:09.382  5591  5638 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,11-18 16:48:09.383  5591  5638 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,11-18 16:48:09.384  5591  5638 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-18 16:48:09.384  5591  5638 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-18 16:48:09.385  5591  5638 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-18 16:48:09.385  5591  5638 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-18 16:48:09.385  5591  5638 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-18 16:48:09.385  5591  5638 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-18 16:48:09.386  5591  5591 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-18 16:48:09.386  5591  5591 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
11-18 16:48:09.386  5591  5591 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
11-18 16:48:09.386  5591  5591 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-18 16:48:09.386  5591  5591 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-18 16:48:09.386  5591  5591 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-18 16:48:09.386  5591  5591 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-18 16:48:09.386  5591  5591 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-18 16:48:09.386  5591  5591 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-18 16:48:09.386  5591  5591 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [ADVERTISING]
11-18 16:48:09.386  5591  5591 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-18 16:48:09.386  5591  5591 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-18 16:48:09.387  5591  5591 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
,11-18 16:48:09.387  5591  5591 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
,11-18 16:48:09.388  5591  5638 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
11-18 16:48:09.389  4632  4632 W Binder_1: type=1400 audit(0.0:115): avc: denied { ioctl } for path="socket:[32990]" dev="sockfs" ino=32990 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-18 16:48:09.388  5591  5638 V io.jxcore.node.ConnectivityMonitor: start: Already started
11-18 16:48:09.388  5591  5638 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 2
11-18 16:48:09.388  5591  5638 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 1 -> 2
,11-18 16:48:09.388  5591  5638 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-61,5,main], id: 61
11-18 16:48:09.388  5591  5591 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-18 16:48:09.388  5591  5638 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-61,5,main], id: 61
11-18 16:48:09.388  5591  5591 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-18 16:48:09.388  5591  5638 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-61,5,main], id: 61
11-18 16:48:09.388  5591  5591 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-18 16:48:09.388  5591  5638 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,11-18 16:48:09.389  4632  4632 W Binder_1: type=1400 audit(0.0:116): avc: denied { ioctl } for path="socket:[32990]" dev="sockfs" ino=32990 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-18 16:48:09.388  5591  5591 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-18 16:48:09.389  5591  5638 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
11-18 16:48:09.389  5591  5638 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
11-18 16:48:09.389  5591  5591 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,11-18 16:48:09.389  5591  5638 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-18 16:48:09.389  5591  5638 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
11-18 16:48:09.390  5591  5638 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
11-18 16:48:09.390  5591  5638 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
11-18 16:48:09.390  5591  5638 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
11-18 16:48:09.390  5591  5638 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
11-18 16:48:09.390  5591  5638 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
11-18 16:48:09.390  5591  5638 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-18 16:48:09.390  5591  5638 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,11-18 16:48:09.390  5591  5591 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
11-18 16:48:09.391  5591  5733 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
11-18 16:48:09.393  5591  5733 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-18 16:48:09.393  5591  5638 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-18 16:48:09.393  5591  5638 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-18 16:48:09.394  5591  5638 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
11-18 16:48:09.395  5591  5733 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,11-18 16:48:09.398  5591  5638 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-61,5,main], id: 61
11-18 16:48:09.398  5591  5638 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-18 16:48:09.399  5591  5638 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-18 16:48:09.399  5591  5638 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,11-18 16:48:09.399  5591  5638 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 2
,11-18 16:48:09.401  5591  5638 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
11-18 16:48:09.401  5591  5638 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-61,5,main], id: 61
11-18 16:48:09.401  5591  5638 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
11-18 16:48:09.401  5591  5638 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: createAdvertiseDataToServiceData 
11-18 16:48:09.401  5591  5638 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:D4"
,11-18 16:48:09.401  5591  5638 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 02 60 83 34 25 D7 D4
11-18 16:48:09.402  5591  5638 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[2, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-18 16:48:09.402  5591  5638 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: created AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[2, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-18 16:48:09.402  5591  5638 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: Current thread: Thread[Thread-61,5,main], id: 61
11-18 16:48:09.402  5591  5638 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: was started = false
,11-18 16:48:09.402  5591  5638 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: advertiseData = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[2, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-18 16:48:09.402  5591  5638 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData finished: Current thread: Thread[Thread-61,5,main], id: 61
11-18 16:48:09.402  5591  5638 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
11-18 16:48:09.402  5591  5638 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... adv data = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[2, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]Current thread: Thread[Thread-61,5,main], id: 61
,11-18 16:48:09.403  5591  5638 D BluetoothAdapter: STATE_ON
11-18 16:48:09.406  4615  4636 D BtGatt.GattService: registerClient() - UUID=a66ac2a1-7131-4d40-b693-74699cd29d3e
11-18 16:48:09.407  4615  4703 D BtGatt.GattService: onClientRegistered() - UUID=a66ac2a1-7131-4d40-b693-74699cd29d3e, clientIf=5
,11-18 16:48:09.407  5591  5602 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
11-18 16:48:09.408  4615  4707 D BtGatt.AdvertiseManager: message : 0
,11-18 16:48:09.410  4615  4707 D BtGatt.AdvertiseManager: starting multi advertising
,11-18 16:48:09.420  4615  4703 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,11-18 16:48:09.426  4615  4703 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,11-18 16:48:09.427  5591  5638 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment Current thread: Thread[Thread-61,5,main], id: 61
,11-18 16:48:09.427  5591  5638 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTINGCurrent thread: Thread[Thread-61,5,main], id: 61
11-18 16:48:09.427  5591  5638 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
11-18 16:48:09.427  5591  5638 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged default (no call to listener). Current thread: Thread[Thread-61,5,main], id: 61
11-18 16:48:09.427  5591  5638 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-61,5,main], id: 61
11-18 16:48:09.427  5591  5638 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[Thread-61,5,main], id: 61
11-18 16:48:09.427  5591  5638 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[Thread-61,5,main], id: 61
,11-18 16:48:09.427  5591  5638 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser started = true Current thread: Thread[Thread-61,5,main], id: 61
11-18 16:48:09.427  5591  5638 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-18 16:48:09.428  5591  5638 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-18 16:48:09.428  5591  5638 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-18 16:48:09.429  5591  5638 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-18 16:48:09.429  5591  5638 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-18 16:48:09.429  5591  5638 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-18 16:48:09.430  5591  5638 I io.jxcore.node.ConnectionHelper: start: OK
,11-18 16:48:09.430  5591  5591 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
11-18 16:48:09.430  5591  5591 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess : Current thread: Thread[main,5,main], id: 1
11-18 16:48:09.430  5591  5591 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNINGCurrent thread: Thread[main,5,main], id: 1
11-18 16:48:09.430  5591  5591 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
11-18 16:48:09.430  5591  5591 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  true. Current thread: Thread[main,5,main], id: 1
11-18 16:48:09.430  5591  5591 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[main,5,main], id: 1
11-18 16:48:09.430  5591  5591 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-18 16:48:09.430  5591  5591 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-18 16:48:09.430  5591  5591 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [ADVERTISING]
11-18 16:48:09.430  5591  5591 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-18 16:48:09.431  5591  5591 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-18 16:48:09.431  5591  5591 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]Current thread: Thread[main,5,main], id: 1
11-18 16:48:09.431  5591  5591 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
11-18 16:48:09.431  5591  5591 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
,11-18 16:48:09.433  5591  5591 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-18 16:48:09.433  5591  5591 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
11-18 16:48:09.434  5591  5591 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-18 16:48:09.434  5591  5591 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-18 16:48:09.434  5591  5591 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-18 16:48:09.434  5591  5591 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,11-18 16:48:09.934  5591  5638 I io.jxcore.node.ConnectionHelperTest: Starting test: testStop
,11-18 16:48:09.934  5591  5638 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
11-18 16:48:09.934  5591  5638 V io.jxcore.node.ConnectivityMonitor: start: Already started
11-18 16:48:09.935  5591  5638 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
11-18 16:48:09.935  5591  5591 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
11-18 16:48:09.935  5591  5638 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 3
,11-18 16:48:09.935  5591  5638 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 2 -> 3
11-18 16:48:09.936  5591  5638 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-61,5,main], id: 61
11-18 16:48:09.936  5591  5638 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-61,5,main], id: 61
11-18 16:48:09.936  5591  5638 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-61,5,main], id: 61
,11-18 16:48:09.937  5591  5638 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
11-18 16:48:09.937  5591  5638 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Manufacturer ID: 7413
11-18 16:48:09.937  5591  5638 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad length and type: 533
11-18 16:48:09.937  5591  5638 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad extra information: 3
11-18 16:48:09.937  5591  5638 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
11-18 16:48:09.937  5591  5638 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 2
11-18 16:48:09.937  5591  5638 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 3
11-18 16:48:09.937  5591  5638 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 2
11-18 16:48:09.937  5591  5638 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
11-18 16:48:09.937  5591  5638 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Current thread: Thread[Thread-61,5,main], id: 61
11-18 16:48:09.938  5591  5638 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 3
11-18 16:48:09.938  5591  5638 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: advertiserWasStarted true Current thread: Thread[Thread-61,5,main], id: 61
11-18 16:48:09.939  5591  5638 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: stop advertiser Current thread: Thread[Thread-61,5,main], id: 61
11-18 16:48:09.940  5591  5638 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-61,5,main], id: 61
11-18 16:48:09.942  4615  4707 D BtGatt.AdvertiseManager: message : 1
11-18 16:48:09.943  4615  4707 D BtGatt.AdvertiseManager: stop advertise for client 5
,11-18 16:48:09.960  4615  4703 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
,11-18 16:48:09.960  4615  4703 D BtGatt.GattService: Client app is not null!
,11-18 16:48:09.963  4615  4636 D BtGatt.GattService: unregisterClient() - clientIf=5
,11-18 16:48:09.964  5591  5638 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-18 16:48:09.964  5591  5638 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
11-18 16:48:09.965  5591  5638 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
11-18 16:48:09.965  5591  5638 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-61,5,main], id: 61
11-18 16:48:09.965  5591  5638 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-61,5,main], id: 61
11-18 16:48:09.965  5591  5638 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-61,5,main], id: 61
11-18 16:48:09.965  5591  5638 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-18 16:48:09.965  5591  5638 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: start advertiser Current thread: Thread[Thread-61,5,main], id: 61
,11-18 16:48:09.965  5591  5638 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
11-18 16:48:09.966  5591  5638 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-61,5,main], id: 61
11-18 16:48:09.966  5591  5638 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
11-18 16:48:09.966  5591  5638 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: createAdvertiseDataToServiceData 
,11-18 16:48:09.966  5591  5638 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-18 16:48:09.966  5591  5638 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 03 60 83 34 25 D7 D4
,11-18 16:48:09.966  5591  5638 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[3, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,11-18 16:48:09.967  5591  5638 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: created AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[3, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-18 16:48:09.967  5591  5638 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: Current thread: Thread[Thread-61,5,main], id: 61
11-18 16:48:09.967  5591  5638 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: was started = false
11-18 16:48:09.967  5591  5638 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: advertiseData = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[3, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-18 16:48:09.967  5591  5638 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData finished: Current thread: Thread[Thread-61,5,main], id: 61
11-18 16:48:09.967  5591  5638 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
11-18 16:48:09.968  5591  5638 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... adv data = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[3, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]Current thread: Thread[Thread-61,5,main], id: 61
11-18 16:48:09.969  5591  5638 D BluetoothAdapter: STATE_ON
11-18 16:48:09.974  4615  4632 D BtGatt.GattService: registerClient() - UUID=237332ce-567b-4608-a69c-8064056ad71c
11-18 16:48:09.974  4615  4703 D BtGatt.GattService: onClientRegistered() - UUID=237332ce-567b-4608-a69c-8064056ad71c, clientIf=5
11-18 16:48:09.975  5591  5601 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
11-18 16:48:09.977  4615  4707 D BtGatt.AdvertiseManager: message : 0
11-18 16:48:09.982  4615  4707 D BtGatt.AdvertiseManager: starting multi advertising
,11-18 16:48:09.999  4615  4703 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,11-18 16:48:10.008  4615  4703 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
11-18 16:48:10.010  5591  5638 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment Current thread: Thread[Thread-61,5,main], id: 61
,11-18 16:48:10.010  5591  5638 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTINGCurrent thread: Thread[Thread-61,5,main], id: 61
11-18 16:48:10.010  5591  5638 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
11-18 16:48:10.010  5591  5638 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged default (no call to listener). Current thread: Thread[Thread-61,5,main], id: 61
11-18 16:48:10.010  5591  5638 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-61,5,main], id: 61
11-18 16:48:10.010  5591  5638 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[Thread-61,5,main], id: 61
,11-18 16:48:10.010  5591  5638 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[Thread-61,5,main], id: 61
11-18 16:48:10.011  5591  5638 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser started = true Current thread: Thread[Thread-61,5,main], id: 61
11-18 16:48:10.011  5591  5638 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: start advertiser started = true Current thread: Thread[Thread-61,5,main], id: 61
11-18 16:48:10.011  5591  5638 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-18 16:48:10.011  5591  5638 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: scannerWasStarted false Current thread: Thread[Thread-61,5,main], id: 61
11-18 16:48:10.011  5591  5638 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,11-18 16:48:10.012  5591  5638 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
11-18 16:48:10.012  5591  5638 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-18 16:48:10.012  5591  5638 I io.jxcore.node.ConnectionHelper: start: OK
,11-18 16:48:10.012  5591  5591 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess : Current thread: Thread[main,5,main], id: 1
11-18 16:48:10.013  5591  5591 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNINGCurrent thread: Thread[main,5,main], id: 1
11-18 16:48:10.013  5591  5591 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
11-18 16:48:10.013  5591  5591 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  true. Current thread: Thread[main,5,main], id: 1
11-18 16:48:10.013  5591  5591 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[main,5,main], id: 1
11-18 16:48:10.013  5591  5591 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-18 16:48:10.013  5591  5591 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-18 16:48:10.013  5591  5591 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [ADVERTISING]
,11-18 16:48:10.013  5591  5591 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [ADVERTISING]
11-18 16:48:10.013  5591  5591 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-18 16:48:10.013  5591  5638 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-18 16:48:10.013  5591  5591 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-18 16:48:10.013  5591  5638 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
11-18 16:48:10.014  5591  5638 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
11-18 16:48:10.014  5591  5638 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
11-18 16:48:10.014  5591  5638 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
11-18 16:48:10.014  5591  5638 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
,11-18 16:48:10.014  5591  5638 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-18 16:48:10.014  5591  5638 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
11-18 16:48:10.014  5591  5638 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
11-18 16:48:10.014  5591  5733 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
11-18 16:48:10.014  5591  5733 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
11-18 16:48:10.015  5591  5638 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,11-18 16:48:10.015  5591  5733 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
11-18 16:48:10.015  5591  5591 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
11-18 16:48:10.015  5591  5638 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-18 16:48:10.015  5591  5638 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
11-18 16:48:10.015  5591  5638 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-18 16:48:10.015  5591  5638 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
,11-18 16:48:10.015  5591  5638 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-61,5,main], id: 61
11-18 16:48:10.015  5591  5638 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-18 16:48:10.015  5591  5638 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-61,5,main], id: 61
11-18 16:48:10.016  5591  5638 D BluetoothAdapter: STATE_ON
11-18 16:48:10.017  5591  5638 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-18 16:48:10.017  5591  5638 D BluetoothAdapter: STATE_ON
11-18 16:48:10.018  5591  5638 D BluetoothLeScanner: could not find callback wrapper
11-18 16:48:10.018  5591  5638 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-18 16:48:10.018  5591  5638 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-18 16:48:10.018  5591  5638 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-61,5,main], id: 61
11-18 16:48:10.018  5591  5638 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-61,5,main], id: 61
11-18 16:48:10.018  5591  5638 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
11-18 16:48:10.018  5591  5638 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-61,5,main], id: 61
11-18 16:48:10.019  4615  4707 D BtGatt.AdvertiseManager: message : 1
11-18 16:48:10.020  4615  4707 D BtGatt.AdvertiseManager: stop advertise for client 5
,11-18 16:48:10.027  4615  4703 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
11-18 16:48:10.027  4615  4703 D BtGatt.GattService: Client app is not null!
,11-18 16:48:10.028  4615  4632 D BtGatt.GattService: unregisterClient() - clientIf=5
11-18 16:48:10.029  5591  5638 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,11-18 16:48:10.029  5591  5638 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
,11-18 16:48:10.029  5591  5638 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
,11-18 16:48:10.029  5591  5638 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  false. Current thread: Thread[Thread-61,5,main], id: 61
11-18 16:48:10.029  5591  5638 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-61,5,main], id: 61
11-18 16:48:10.030  5591  5638 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-61,5,main], id: 61
11-18 16:48:10.030  5591  5638 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,11-18 16:48:10.030  5591  5638 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-18 16:48:10.031  5591  5638 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,11-18 16:48:10.031  5591  5638 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-18 16:48:10.032  5591  5638 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-18 16:48:10.032  5591  5638 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-18 16:48:10.032  5591  5638 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-18 16:48:10.032  5591  5638 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-18 16:48:10.033  5591  5591 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-18 16:48:10.033  5591  5591 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
11-18 16:48:10.033  5591  5591 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
11-18 16:48:10.033  5591  5591 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-18 16:48:10.033  5591  5591 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-18 16:48:10.034  5591  5591 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-18 16:48:10.034  5591  5591 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-18 16:48:10.034  5591  5591 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-18 16:48:10.034  5591  5591 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-18 16:48:10.034  5591  5591 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [ADVERTISING]
11-18 16:48:10.034  5591  5591 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-18 16:48:10.034  5591  5591 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-18 16:48:10.034  5591  5591 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
11-18 16:48:10.034  5591  5591 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-18 16:48:10.035  5591  5638 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnPeerReadyToProvideBluetoothMacAddress
11-18 16:48:10.035  5591  5638 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
11-18 16:48:10.036  5591  5591 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-18 16:48:10.036  5591  5591 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
,11-18 16:48:10.036  5591  5591 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-18 16:48:10.036  5591  5591 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-18 16:48:10.036  5591  5591 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-18 16:48:10.037  5591  5638 I io.jxcore.node.ConnectionHelperTest: Starting test: testKillAllConnections
11-18 16:48:10.037  5591  5638 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
,11-18 16:48:10.038  5591  5638 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnConnectionManagerStateChanged
,11-18 16:48:10.038  5591  5638 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
,11-18 16:48:10.039  5591  5638 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnPermissionCheckRequired
,11-18 16:48:10.039  5591  5638 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
,11-18 16:48:10.040  5591  5638 I io.jxcore.node.ConnectionHelperTest: Starting test: testToggleBetweenSystemDecidedAndAlternativeInsecureRfcommPortNumber
11-18 16:48:10.040  5591  5638 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
11-18 16:48:10.041  5591  5638 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-18 16:48:10.041  5591  5638 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-18 16:48:10.041  5591  5638 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-18 16:48:10.041  5591  5638 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
11-18 16:48:10.041  5591  5638 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-18 16:48:10.041  5591  5638 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-18 16:48:10.041  5591  5638 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-18 16:48:10.041  5591  5638 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
11-18 16:48:10.041  5591  5638 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-18 16:48:10.041  5591  5638 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-18 16:48:10.041  5591  5638 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,11-18 16:48:10.042  5591  5638 I io.jxcore.node.ConnectionHelperTest: Starting test: testConnect
11-18 16:48:10.042  5591  5638 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
11-18 16:48:10.042  5591  5638 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
11-18 16:48:10.045  5591  5638 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnProvideBluetoothMacAddressRequest
11-18 16:48:10.045  5591  5638 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
,11-18 16:48:10.046  5591  5638 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnDiscoveryManagerStateChanged
11-18 16:48:10.046  5591  5638 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
11-18 16:48:10.047  5591  5638 I io.jxcore.node.ConnectionHelperTest: Starting test: testDisconnectOutgoingConnection
,11-18 16:48:10.047  5591  5638 E io.jxcore.node.ConnectionModel: addConnectionThread: A matching thread for outgoing connection already exists
11-18 16:48:10.047  5591  5638 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
11-18 16:48:10.047  5591  5638 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
11-18 16:48:10.047  5591  5638 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
11-18 16:48:10.048  5591  5638 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
11-18 16:48:10.048  5591  5638 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
11-18 16:48:10.048  5591  5638 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
11-18 16:48:10.048  5591  5638 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,11-18 16:48:10.048  5591  5638 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
11-18 16:48:10.048  5591  5638 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
11-18 16:48:10.048  5591  5638 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
11-18 16:48:10.048  5591  5638 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
11-18 16:48:10.048  5591  5638 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
11-18 16:48:10.049  5591  5638 I io.jxcore.node.ConnectionHelperTest: Starting test: testDispose
11-18 16:48:10.049  5591  5638 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
11-18 16:48:10.049  5591  5638 V io.jxcore.node.ConnectivityMonitor: start: Already started
,11-18 16:48:10.049  5591  5638 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 4
11-18 16:48:10.049  5591  5638 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 3 -> 4
11-18 16:48:10.049  5591  5638 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-61,5,main], id: 61
11-18 16:48:10.049  5591  5638 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-61,5,main], id: 61
11-18 16:48:10.049  5591  5638 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-61,5,main], id: 61
11-18 16:48:10.049  5591  5638 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
11-18 16:48:10.050  5591  5638 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
11-18 16:48:10.050  5591  5638 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
11-18 16:48:10.050  5591  5638 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,11-18 16:48:10.050  5591  5638 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
11-18 16:48:10.051  5591  5638 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
11-18 16:48:10.051  5591  5638 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
11-18 16:48:10.051  5591  5638 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
11-18 16:48:10.051  5591  5638 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
11-18 16:48:10.051  5591  5638 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
11-18 16:48:10.051  5591  5737 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
11-18 16:48:10.051  5591  5591 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
11-18 16:48:10.051  5591  5638 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,11-18 16:48:10.051  5591  5638 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
11-18 16:48:10.053  5591  5737 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-18 16:48:10.055  5591  5638 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-18 16:48:10.055  5591  5638 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-18 16:48:10.055  5591  5638 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
11-18 16:48:10.050  4863  4863 W Binder_5: type=1400 audit(0.0:117): avc: denied { ioctl } for path="socket:[28273]" dev="sockfs" ino=28273 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-18 16:48:10.053  4863  4863 W Binder_5: type=1400 audit(0.0:118): avc: denied { ioctl } for path="socket:[28273]" dev="sockfs" ino=28273 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-18 16:48:10.056  5591  5737 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,11-18 16:48:10.061  5591  5638 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-61,5,main], id: 61
11-18 16:48:10.061  5591  5638 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,11-18 16:48:10.061  5591  5638 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-18 16:48:10.061  5591  5638 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-18 16:48:10.061  5591  5638 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 4
,11-18 16:48:10.064  5591  5638 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
,11-18 16:48:10.065  5591  5638 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-61,5,main], id: 61
,11-18 16:48:10.065  5591  5638 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
11-18 16:48:10.065  5591  5638 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: createAdvertiseDataToServiceData 
11-18 16:48:10.065  5591  5638 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-18 16:48:10.065  5591  5638 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 04 60 83 34 25 D7 D4
11-18 16:48:10.065  5591  5638 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[4, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-18 16:48:10.065  5591  5638 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: created AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[4, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-18 16:48:10.065  5591  5638 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: Current thread: Thread[Thread-61,5,main], id: 61
,11-18 16:48:10.065  5591  5638 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: was started = false
11-18 16:48:10.065  5591  5638 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: advertiseData = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[4, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-18 16:48:10.065  5591  5638 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData finished: Current thread: Thread[Thread-61,5,main], id: 61
11-18 16:48:10.065  5591  5638 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
11-18 16:48:10.065  5591  5638 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... adv data = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[4, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]Current thread: Thread[Thread-61,5,main], id: 61
11-18 16:48:10.066  5591  5638 D BluetoothAdapter: STATE_ON
,11-18 16:48:10.070  4615  4636 D BtGatt.GattService: registerClient() - UUID=806a4d4e-a678-4f95-9123-0022516b0f0e
11-18 16:48:10.070  4615  4703 D BtGatt.GattService: onClientRegistered() - UUID=806a4d4e-a678-4f95-9123-0022516b0f0e, clientIf=5
,11-18 16:48:10.070  5591  5601 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
,11-18 16:48:10.071  4615  4707 D BtGatt.AdvertiseManager: message : 0
,11-18 16:48:10.074  4615  4707 D BtGatt.AdvertiseManager: starting multi advertising
,11-18 16:48:10.084  4615  4703 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,11-18 16:48:10.089  4615  4703 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,11-18 16:48:10.090  5591  5638 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment Current thread: Thread[Thread-61,5,main], id: 61
,11-18 16:48:10.090  5591  5638 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTINGCurrent thread: Thread[Thread-61,5,main], id: 61
11-18 16:48:10.090  5591  5638 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
11-18 16:48:10.091  5591  5638 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged default (no call to listener). Current thread: Thread[Thread-61,5,main], id: 61
11-18 16:48:10.091  5591  5638 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-61,5,main], id: 61
11-18 16:48:10.091  5591  5638 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[Thread-61,5,main], id: 61
11-18 16:48:10.091  5591  5638 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[Thread-61,5,main], id: 61
11-18 16:48:10.091  5591  5638 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser started = true Current thread: Thread[Thread-61,5,main], id: 61
11-18 16:48:10.091  5591  5638 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-18 16:48:10.092  5591  5638 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-18 16:48:10.092  5591  5638 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-18 16:48:10.094  5591  5638 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-18 16:48:10.094  5591  5638 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-18 16:48:10.094  5591  5638 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-18 16:48:10.094  5591  5638 I io.jxcore.node.ConnectionHelper: start: OK
11-18 16:48:10.094  5591  5591 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
11-18 16:48:10.094  5591  5591 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess : Current thread: Thread[main,5,main], id: 1
,11-18 16:48:10.094  5591  5591 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNINGCurrent thread: Thread[main,5,main], id: 1
11-18 16:48:10.094  5591  5591 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
11-18 16:48:10.094  5591  5591 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  true. Current thread: Thread[main,5,main], id: 1
11-18 16:48:10.094  5591  5591 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[main,5,main], id: 1
11-18 16:48:10.095  5591  5591 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-18 16:48:10.095  5591  5591 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-18 16:48:10.095  5591  5591 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [ADVERTISING]
11-18 16:48:10.095  5591  5591 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-18 16:48:10.095  5591  5591 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-18 16:48:10.095  5591  5591 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]Current thread: Thread[main,5,main], id: 1
11-18 16:48:10.095  5591  5591 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
11-18 16:48:10.095  5591  5591 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
,11-18 16:48:10.097  5591  5591 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
,11-18 16:48:10.098  5591  5591 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
11-18 16:48:10.098  5591  5591 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-18 16:48:10.098  5591  5591 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-18 16:48:10.098  5591  5591 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-18 16:48:10.098  5591  5591 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,11-18 16:48:10.596  5591  5638 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,11-18 16:48:10.596  5591  5638 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
,11-18 16:48:10.596  5591  5638 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
11-18 16:48:10.596  5591  5638 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
11-18 16:48:10.597  5591  5638 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-18 16:48:10.597  5591  5638 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
11-18 16:48:10.597  5591  5638 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
,11-18 16:48:10.597  5591  5737 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
11-18 16:48:10.597  5591  5737 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
11-18 16:48:10.597  5591  5638 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-18 16:48:10.597  5591  5737 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
11-18 16:48:10.598  5591  5638 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@512f2d3 removed from the list
,11-18 16:48:10.598  5591  5591 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
11-18 16:48:10.598  5591  5638 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-18 16:48:10.598  5591  5638 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-18 16:48:10.598  5591  5591 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
11-18 16:48:10.598  5591  5638 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,11-18 16:48:10.598  5591  5591 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-18 16:48:10.598  5591  5638 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-18 16:48:10.598  5591  5591 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
11-18 16:48:10.599  5591  5638 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
11-18 16:48:10.599  5591  5638 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-61,5,main], id: 61
11-18 16:48:10.599  5591  5638 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-18 16:48:10.599  5591  5638 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-61,5,main], id: 61
11-18 16:48:10.601  5591  5638 D BluetoothAdapter: STATE_ON
11-18 16:48:10.601  5591  5638 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-18 16:48:10.603  5591  5638 D BluetoothAdapter: STATE_ON
11-18 16:48:10.603  5591  5638 D BluetoothLeScanner: could not find callback wrapper
11-18 16:48:10.603  5591  5638 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-18 16:48:10.604  5591  5638 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
,11-18 16:48:10.604  5591  5638 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-61,5,main], id: 61
11-18 16:48:10.604  5591  5638 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-61,5,main], id: 61
11-18 16:48:10.604  5591  5638 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
,11-18 16:48:10.604  5591  5638 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-61,5,main], id: 61
11-18 16:48:10.606  4615  4707 D BtGatt.AdvertiseManager: message : 1
11-18 16:48:10.607  4615  4707 D BtGatt.AdvertiseManager: stop advertise for client 5
,11-18 16:48:10.619  4615  4703 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
11-18 16:48:10.620  4615  4703 D BtGatt.GattService: Client app is not null!
,11-18 16:48:10.622  4615  4861 D BtGatt.GattService: unregisterClient() - clientIf=5
,11-18 16:48:10.623  5591  5638 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-18 16:48:10.624  5591  5638 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
11-18 16:48:10.624  5591  5638 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
,11-18 16:48:10.624  5591  5638 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  false. Current thread: Thread[Thread-61,5,main], id: 61
11-18 16:48:10.624  5591  5638 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-61,5,main], id: 61
11-18 16:48:10.624  5591  5638 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-61,5,main], id: 61
11-18 16:48:10.624  5591  5638 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-18 16:48:10.624  5591  5638 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-18 16:48:10.625  5591  5638 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-18 16:48:10.626  5591  5638 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-18 16:48:10.628  5591  5638 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-18 16:48:10.628  5591  5638 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-18 16:48:10.628  5591  5638 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
,11-18 16:48:10.629  5591  5638 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-18 16:48:10.629  5591  5638 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@13fde10 removed from the list
11-18 16:48:10.629  5591  5591 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-18 16:48:10.629  5591  5638 D io.jxcore.node.ConnectivityMonitor: stop
11-18 16:48:10.629  5591  5638 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
11-18 16:48:10.629  5591  5591 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,11-18 16:48:10.629  5591  5591 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-18 16:48:10.629  5591  5591 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-18 16:48:10.629  5591  5591 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-18 16:48:10.630  5591  5591 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [ADVERTISING]
11-18 16:48:10.630  5591  5591 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-18 16:48:10.630  5591  5591 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-18 16:48:10.630  5591  5591 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
11-18 16:48:10.630  5591  5591 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-18 16:48:10.632  5591  5591 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-18 16:48:10.632  5591  5591 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-18 16:48:10.633  5591  5591 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
,11-18 16:48:10.633  5591  5591 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-18 16:48:10.633  5591  5591 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,11-18 16:48:11.134  5591  5591 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-18 16:48:15.634  5591  5638 I io.jxcore.node.ConnectionHelperTest: Starting test: testIsRunning
,11-18 16:48:15.636  5591  5638 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
,11-18 16:48:15.636  5591  5638 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,11-18 16:48:15.637  5591  5638 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
,11-18 16:48:15.643  5591  5638 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,11-18 16:48:15.644  5591  5638 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,11-18 16:48:15.644  5591  5638 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
,11-18 16:48:15.644  5591  5638 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
11-18 16:48:15.645  5591  5638 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
11-18 16:48:15.645  5591  5638 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
11-18 16:48:15.645  5591  5738 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
11-18 16:48:15.646  5591  5591 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
11-18 16:48:15.647  5591  5738 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-18 16:48:15.648  5591  5638 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnConnectionFailed
11-18 16:48:15.646  4853  4853 W Binder_3: type=1400 audit(0.0:119): avc: denied { ioctl } for path="socket:[34021]" dev="sockfs" ino=34021 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-18 16:48:15.650  5591  5638 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
11-18 16:48:15.646  4853  4853 W Binder_3: type=1400 audit(0.0:120): avc: denied { ioctl } for path="socket:[34021]" dev="sockfs" ino=34021 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-18 16:48:15.651  5591  5638 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
,11-18 16:48:15.651  5591  5638 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
11-18 16:48:15.651  5591  5638 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-18 16:48:15.651  5591  5638 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-18 16:48:15.653  5591  5738 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
11-18 16:48:15.653  5591  5638 I io.jxcore.node.ConnectionHelperTest: Starting test: testGetConnectivityMonitorGetDiscoveryManagerGetConnectionModelGetBluetoothName
,11-18 16:48:15.659  5591  5638 I io.jxcore.node.ConnectionHelperTest: Starting test: testConstructor
,11-18 16:48:15.660  5591  5638 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-18 16:48:15.660  5591  5638 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
11-18 16:48:15.660  5591  5638 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
11-18 16:48:15.660  5591  5638 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
11-18 16:48:15.660  5591  5638 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
11-18 16:48:15.660  5591  5738 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
11-18 16:48:15.660  5591  5738 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
,11-18 16:48:15.660  5591  5738 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
11-18 16:48:15.661  5591  5591 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
11-18 16:48:15.661  5591  5638 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-18 16:48:15.661  5591  5638 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
11-18 16:48:15.662  5591  5591 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-18 16:48:15.662  5591  5638 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@512f2d3 not in the list
,11-18 16:48:15.662  5591  5591 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
11-18 16:48:15.662  5591  5638 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-18 16:48:15.662  5591  5638 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-18 16:48:15.662  5591  5638 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
11-18 16:48:15.662  5591  5638 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-18 16:48:15.662  5591  5638 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-18 16:48:15.664  5591  5638 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-18 16:48:15.665  5591  5638 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-18 16:48:15.665  5591  5638 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-18 16:48:15.665  5591  5638 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
,11-18 16:48:15.665  5591  5591 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-18 16:48:15.665  5591  5638 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@13fde10 not in the list
11-18 16:48:15.665  5591  5591 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-18 16:48:15.666  5591  5591 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-18 16:48:15.665  5591  5638 D io.jxcore.node.ConnectivityMonitor: stop
,11-18 16:48:15.668  5591  5638 I io.jxcore.node.ConnectionModelTest: Starting test: testGetNumberOfCurrentOutgoingConnections
,11-18 16:48:15.669  5591  5638 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
,11-18 16:48:15.669  5591  5638 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
,11-18 16:48:15.671  5591  5638 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
11-18 16:48:15.671  5591  5638 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
11-18 16:48:15.672  5591  5638 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
,11-18 16:48:15.672  5591  5638 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,11-18 16:48:15.673  5591  5638 I io.jxcore.node.ConnectionModelTest: Starting test: constructorTest
,11-18 16:48:15.674  5591  5638 I io.jxcore.node.ConnectionModelTest: Starting test: testHasIncomingConnection
11-18 16:48:15.675  5591  5638 I io.jxcore.node.ConnectionModelTest: Starting test: testGetNumberOfCurrentConnections
11-18 16:48:15.675  5591  5638 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
11-18 16:48:15.675  5591  5638 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
11-18 16:48:15.675  5591  5638 I io.jxcore.node.ConnectionModelTest: Starting test: testGetNumberOfCurrentIncomingConnections
11-18 16:48:15.676  5591  5638 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
11-18 16:48:15.676  5591  5638 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
11-18 16:48:15.676  5591  5638 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
11-18 16:48:15.676  5591  5638 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
,11-18 16:48:15.676  5591  5638 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
11-18 16:48:15.676  5591  5638 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
11-18 16:48:15.676  5591  5638 I io.jxcore.node.ConnectionModelTest: Starting test: testGetOutgoingConnectionCallbackByBluetoothMacAddress
11-18 16:48:15.677  5591  5638 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
11-18 16:48:15.677  5591  5638 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
11-18 16:48:15.677  5591  5638 I io.jxcore.node.ConnectionModelTest: Starting test: testHasConnection
11-18 16:48:15.677  5591  5638 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
11-18 16:48:15.677  5591  5638 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
,11-18 16:48:15.677  5591  5638 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
11-18 16:48:15.677  5591  5638 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
11-18 16:48:15.678  5591  5638 I io.jxcore.node.ConnectionModelTest: Starting test: testHasOutgoingConnection
11-18 16:48:15.678  5591  5638 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-18 16:48:15.678  5591  5638 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3f13be added. We now have 3 listener(s)
11-18 16:48:15.679  5591  5638 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-18 16:48:15.680  5591  5638 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-18 16:48:15.680  5591  5638 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,11-18 16:48:15.680  5591  5638 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-18 16:48:15.680  5591  5638 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5d37c1f added. We now have 3 listener(s)
11-18 16:48:15.680  5591  5638 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-18 16:48:15.680  5591  5638 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,11-18 16:48:15.683  5591  5638 D BluetoothAdapter: enable(): BT is already enabled..!
,11-18 16:48:15.683   929  3190 D WifiService: setWifiEnabled: true pid=5591, uid=10077
11-18 16:48:15.683   929  3190 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-18 16:48:15.685  5591  5638 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testIsBleMultipleAdvertisementSupported
,11-18 16:48:15.687  5591  5638 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testIsBluetoothSupported
,11-18 16:48:15.688  5591  5638 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testStartStop
,11-18 16:48:15.690  5591  5638 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testIsWifiDirectSupported
11-18 16:48:15.691  5591  5638 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testIsBluetoothEnabled
,11-18 16:48:15.695  4615  4699 D BluetoothAdapterState: Current state: ON, message: 23
11-18 16:48:15.695  4615  4699 D BluetoothAdapterProperties: Setting state to 13
11-18 16:48:15.695  4615  4699 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
11-18 16:48:15.695  5591  5638 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-18 16:48:15.695  5591  5638 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-18 16:48:15.695  5591  5638 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-18 16:48:15.695  5591  5638 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-18 16:48:15.695  5591  5638 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-18 16:48:15.695  5591  5638 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-18 16:48:15.695  5591  5638 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-18 16:48:15.695  5591  5638 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-18 16:48:15.695  5591  5638 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
11-18 16:48:15.696  4615  4699 D BluetoothAdapterProperties: onBluetoothDisable()
11-18 16:48:15.696  4615  4699 I BluetoothAdapterState: Entering PendingCommandState
11-18 16:48:15.697  5591  5638 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-18 16:48:15.697  5591  5638 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
,11-18 16:48:15.699  4615  4615 D BluetoothMapService: onReceive
,11-18 16:48:15.699  4615  4615 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
11-18 16:48:15.699  4615  4615 D BluetoothMapService: STATE_TURNING_OFF
11-18 16:48:15.699  4615  4615 D BluetoothMapService: MAP Service closeService in
11-18 16:48:15.699  4615  4615 D BluetoothMapMasInstance0: MAP Service shutdown
11-18 16:48:15.699  4615  4615 D ObexServerSockets0: shutdown(block = true)
,11-18 16:48:15.700  4615  4615 D ObexServerSockets0: shutdown called from another thread - interrupt().
11-18 16:48:15.700  4615  4615 D ObexServerSockets0: shutdown called from another thread - interrupt().
11-18 16:48:15.700  4615  4866 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
11-18 16:48:15.700  4615  4837 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
11-18 16:48:15.700  4615  4865 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 5
11-18 16:48:15.702  4615  4615 I BtOppRfcommListener: stopping Accept Thread
,11-18 16:48:15.703  4615  5293 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
11-18 16:48:15.703  4615  5293 I BtOppRfcommListener: BluetoothSocket listen thread finished
,11-18 16:48:15.712   929   942 I ActivityManager: Start proc 5741:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
,11-18 16:48:15.713  4615  4703 D BluetoothAdapterProperties: Scan Mode:20
11-18 16:48:15.714  4615  4699 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
,11-18 16:48:15.716  4615  4615 D HeadsetService: Received stop request...Stopping profile...
11-18 16:48:15.717   929   929 D BluetoothHeadset: Proxy object disconnected
11-18 16:48:15.717   929   929 D BluetoothHeadset: Proxy object disconnected
11-18 16:48:15.718  3105  3973 D BluetoothHeadset: Proxy object disconnected
11-18 16:48:15.718  4615  4615 V BluetoothAdapterState: isTurningOff()=true
11-18 16:48:15.718  4615  4615 V BluetoothAdapterState: isTurningOn()=false
11-18 16:48:15.718  4615  4615 V BluetoothAdapterState: isBleTurningOn()=false
11-18 16:48:15.718  4615  4615 V BluetoothAdapterState: isBleTurningOff()=false
11-18 16:48:15.718  3747  3777 D BluetoothHeadset: Proxy object disconnected
11-18 16:48:15.718  4615  4615 D A2dpService: Received stop request...Stopping profile...
11-18 16:48:15.718   929   929 D BluetoothHeadset: Proxy object disconnected
11-18 16:48:15.719  4615  4856 D A2dpStateMachine: Exit Disconnected: -1
,11-18 16:48:15.721   929   929 D BluetoothA2dp: Proxy object disconnected
,11-18 16:48:15.724  4615  4615 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
,11-18 16:48:15.726  4615  4615 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
,11-18 16:48:15.726  4615  4821 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-18 16:48:15.726  4615  4821 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-18 16:48:15.726  4615  4821 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,11-18 16:48:15.727  4615  4615 D HidService: Received stop request...Stopping profile...
,11-18 16:48:15.728  4615  4615 D HidService: Stopping Bluetooth HidService
11-18 16:48:15.728  4615  4703 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
11-18 16:48:15.728  4615  4703 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
11-18 16:48:15.729  4615  4615 D HealthService: Received stop request...Stopping profile...
11-18 16:48:15.732  3105  3105 D HeadsetProfile: Bluetooth service disconnected
11-18 16:48:15.732  3105  3105 D BluetoothA2dp: Proxy object disconnected
11-18 16:48:15.732  3105  3105 D BluetoothInputDevice: Proxy object disconnected
11-18 16:48:15.732  3105  3105 D HidProfile: Bluetooth service disconnected
11-18 16:48:15.733  4615  4615 V BluetoothAdapterState: isTurningOff()=true
11-18 16:48:15.733  4615  4615 V BluetoothAdapterState: isTurningOn()=false
11-18 16:48:15.733  4615  4615 V BluetoothAdapterState: isBleTurningOn()=false
11-18 16:48:15.733  4615  4615 V BluetoothAdapterState: isBleTurningOff()=false
11-18 16:48:15.734  4615  4615 D PanService: Received stop request...Stopping profile...
11-18 16:48:15.735  3105  3105 D BluetoothPan: BluetoothPAN Proxy object disconnected
,11-18 16:48:15.735  3105  3105 D PanProfile: Bluetooth service disconnected
11-18 16:48:15.736  4615  4821 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-18 16:48:15.736  4615  4821 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-18 16:48:15.737  4615  4821 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
11-18 16:48:15.737  4615  4821 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
11-18 16:48:15.737  4615  4821 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
11-18 16:48:15.737  4615  4615 D BluetoothMapService: Received stop request...Stopping profile...
,11-18 16:48:15.737  4615  4821 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
11-18 16:48:15.737  4615  4615 D BluetoothMapService: stop()
11-18 16:48:15.737  4615  4703 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
,11-18 16:48:15.738  4615  4615 D BluetoothMapAppObserver: deinitObservers()
11-18 16:48:15.739  4615  4615 D BluetoothMapAppObserver: removeReceiver()
11-18 16:48:15.740  3105  3105 D BluetoothMap: Proxy object disconnected
11-18 16:48:15.740  3105  3105 D MapProfile: Bluetooth service disconnected
,11-18 16:48:15.741  4615  4615 D SapService: Received stop request...Stopping profile...
11-18 16:48:15.741  4615  4615 V SapService: stop()
,11-18 16:48:15.743   929   940 I ActivityManager: Killing 5048:com.google.android.apps.maps/u0a58 (adj 15): empty #17
,11-18 16:48:15.762  4615  4615 V BluetoothAdapterState: isTurningOff()=true
11-18 16:48:15.762  4615  4615 V BluetoothAdapterState: isTurningOn()=false
,11-18 16:48:15.762  4615  4615 V BluetoothAdapterState: isBleTurningOn()=false
,11-18 16:48:15.762  4615  4615 V BluetoothAdapterState: isBleTurningOff()=false
,11-18 16:48:15.762  4615  4615 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
11-18 16:48:15.762  4615  4615 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
,11-18 16:48:15.762  4615  4703 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
11-18 16:48:15.762  4615  4615 V BluetoothAdapterState: isTurningOff()=true
11-18 16:48:15.762  4615  4615 V BluetoothAdapterState: isTurningOn()=false
11-18 16:48:15.762  4615  4615 V BluetoothAdapterState: isBleTurningOn()=false
11-18 16:48:15.763  4615  4615 V BluetoothAdapterState: isBleTurningOff()=false
,11-18 16:48:15.763  4615  4615 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
,11-18 16:48:15.763  4615  4703 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
,11-18 16:48:15.763  4615  4615 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
11-18 16:48:15.764  4615  4615 V BluetoothAdapterState: isTurningOff()=true
11-18 16:48:15.764  4615  4615 V BluetoothAdapterState: isTurningOn()=false
11-18 16:48:15.764  4615  4615 V BluetoothAdapterState: isBleTurningOn()=false
,11-18 16:48:15.764  4615  4615 V BluetoothAdapterState: isBleTurningOff()=false
11-18 16:48:15.764  4615  4615 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
11-18 16:48:15.764  4615  4615 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
11-18 16:48:15.766  4615  4615 D BluetoothMapService: MAP Service closeService in
11-18 16:48:15.766  4615  4615 V BluetoothAdapterState: isTurningOff()=true
11-18 16:48:15.766  4615  4615 V BluetoothAdapterState: isTurningOn()=false
11-18 16:48:15.766  4615  4615 V BluetoothAdapterState: isBleTurningOn()=false
11-18 16:48:15.766  4615  4615 V BluetoothAdapterState: isBleTurningOff()=false
11-18 16:48:15.766  4615  4615 D BluetoothMapService: cleanup()
,11-18 16:48:15.766  4615  4615 D BluetoothMapService: MAP Service closeService in
,11-18 16:48:15.767  4615  4615 V BluetoothAdapterState: isTurningOff()=true
11-18 16:48:15.767  4615  4615 V BluetoothAdapterState: isTurningOn()=false
11-18 16:48:15.767  4615  4615 V BluetoothAdapterState: isBleTurningOn()=false
,11-18 16:48:15.767  4615  4615 V BluetoothAdapterState: isBleTurningOff()=false
,11-18 16:48:15.767  4615  4699 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
,11-18 16:48:15.767  4615  4699 D BluetoothAdapterProperties: Setting state to 15
,11-18 16:48:15.767  4615  4699 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
11-18 16:48:15.768  3747  3786 D BluetoothHeadset: onBluetoothStateChange: up=false
11-18 16:48:15.768  3105  3120 D BluetoothA2dp: onBluetoothStateChange: up=false
,11-18 16:48:15.768  4615  4699 I BluetoothAdapterState: Entering BleOnState
11-18 16:48:15.769   929   946 D BluetoothHeadset: onBluetoothStateChange: up=false
11-18 16:48:15.769  3105  3973 D BluetoothInputDevice: onBluetoothStateChange: up=false
11-18 16:48:15.769  3105  3126 D BluetoothHeadset: onBluetoothStateChange: up=false
11-18 16:48:15.770   929   946 D BluetoothHeadset: onBluetoothStateChange: up=false
11-18 16:48:15.770  3105  3120 D BluetoothMap: onBluetoothStateChange: up=false
11-18 16:48:15.770  3105  3973 D BluetoothPbap: onBluetoothStateChange: up=false
11-18 16:48:15.771  3105  3126 D BluetoothPan: onBluetoothStateChange on: false
11-18 16:48:15.771   929   946 D BluetoothA2dp: onBluetoothStateChange: up=false
11-18 16:48:15.771   929   946 D BluetoothHeadset: onBluetoothStateChange: up=false
,11-18 16:48:15.772  4615  4699 D BluetoothAdapterState: Current state: BLE ON, message: 20
11-18 16:48:15.772  4615  4699 D BluetoothAdapterProperties: Setting state to 16
11-18 16:48:15.772  4615  4699 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
11-18 16:48:15.772  4615  4699 D BluetoothAdapterProperties: onBleDisable
11-18 16:48:15.773  4615  4699 I BluetoothAdapterState: Entering PendingCommandState
11-18 16:48:15.773  4615  4700 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
11-18 16:48:15.773  4615  4821 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
11-18 16:48:15.774  4615  4821 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-18 16:48:15.776  4615  4703 D BluetoothAdapterProperties: Scan Mode:20
,11-18 16:48:15.778  5741  5741 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm64
,11-18 16:48:15.799  5741  5741 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,11-18 16:48:15.803   929   946 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@984bca9:true
,11-18 16:48:15.804  3569  3569 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,11-18 16:48:15.818   929  3652 I ActivityManager: Start proc 5753:com.google.android.apps.maps/u0a58 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,11-18 16:48:15.831  5741  5741 D LocalBluetoothProfileManager: Adding local MAP profile
,11-18 16:48:15.834  5741  5741 D BluetoothMap: Create BluetoothMap proxy object
,11-18 16:48:15.852  5741  5741 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,11-18 16:48:15.859  5753  5753 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm64
,11-18 16:48:15.870  5741  5741 D DockEventReceiver: finishStartingService: stopping service
,11-18 16:48:15.873   929   940 I ActivityManager: Killing 5392:com.android.sdm.plugins.sprintdm/1001 (adj 15): empty #17
,11-18 16:48:15.981  4615  4703 I bt_hci  : shut_down
,11-18 16:48:15.985  4615  4709 D bt_hwcfg: hw_epilog_process
,11-18 16:48:15.986  4615  4709 I bt_vendor: low_power_mode_cb
,11-18 16:48:15.988  4615  4709 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,11-18 16:48:15.988  4615  4709 I bt_vendor: epilog_cb
11-18 16:48:15.988  4615  4709 I bt_hci  : epilog_finished_callback
,11-18 16:48:15.991  4615  4703 I bt_hci_h4: hal_close
,11-18 16:48:15.992  4615  4703 I bt_userial_vendor: device fd = 54 close
,11-18 16:48:16.067  5753  5753 D StrictMode: StrictMode policy violation; ~duration=114 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-18 16:48:16.067  5753  5753 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-18 16:48:16.067  5753  5753 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
11-18 16:48:16.067  5753  5753 D StrictMode: 	at java.io.File.doAccess(File.java:281)
11-18 16:48:16.067  5753  5753 D StrictMode: 	at java.io.File.exists(File.java:361)
11-18 16:48:16.067  5753  5753 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
11-18 16:48:16.067  5753  5753 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
11-18 16:48:16.067  5753  5753 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
11-18 16:48:16.067  5753  5753 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
11-18 16:48:16.067  5753  5753 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
11-18 16:48:16.067  5753  5753 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
11-18 16:48:16.067  5753  5753 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-18 16:48:16.067  5753  5753 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-18 16:48:16.067  5753  5753 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-18 16:48:16.067  5753  5753 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-18 16:48:16.067  5753  5753 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-18 16:48:16.067  5753  5753 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-18 16:48:16.067  5753  5753 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-18 16:48:16.067  5753  5753 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-18 16:48:16.067  5753  5753 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-18 16:48:16.067  5753  5753 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-18 16:48:16.067  5753  5753 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-18 16:48:16.067  5753  5753 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-18 16:48:16.067  5753  5753 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-18 16:48:16.067  5753  5753 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-18 16:48:16.067  5753  5753 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-18 16:48:16.067  5753  5753 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,11-18 16:48:16.068  5753  5753 D StrictMode: StrictMode policy violation; ~duration=113 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-18 16:48:16.068  5753  5753 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-18 16:48:16.068  5753  5753 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
11-18 16:48:16.068  5753  5753 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
11-18 16:48:16.068  5753  5753 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
11-18 16:48:16.068  5753  5753 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
11-18 16:48:16.068  5753  5753 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
11-18 16:48:16.068  5753  5753 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
11-18 16:48:16.068  5753  5753 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
11-18 16:48:16.068  5753  5753 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-18 16:48:16.068  5753  5753 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-18 16:48:16.068  5753  5753 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-18 16:48:16.068  5753  5753 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-18 16:48:16.068  5753  5753 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-18 16:48:16.068  5753  5753 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-18 16:48:16.068  5753  5753 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-18 16:48:16.068  5753  5753 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-18 16:48:16.068  5753  5753 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-18 16:48:16.068  5753  5753 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-18 16:48:16.068  5753  5753 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-18 16:48:16.068  5753  5753 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-18 16:48:16.068  5753  5753 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-18 16:48:16.068  5753  5753 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-18 16:48:16.068  5753  5753 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-18 16:48:16.068  5753  5753 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-18 16:48:16.068  5753  5753 D StrictMode: StrictMode policy violation; ~duration=113 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-18 16:48:16.068  5753  5753 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-18 16:48:16.068  5753  5753 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
11-18 16:48:16.068  5753  5753 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
11-18 16:48:16.068  5753  5753 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
11-18 16:48:16.068  5753  5753 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
11-18 16:48:16.068  5753  5753 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
11-18 16:48:16.068  5753  5753 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
11-18 16:48:16.068  5753  5753 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
11-18 16:48:16.068  5753  5753 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-18 16:48:16.068  5753  5753 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-18 16:48:16.068  5753  5753 D StrictMode: 	at com.google.android.apps.gmm.base.ap,p.a.a(PG:244)
11-18 16:48:16.068  5753  5753 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-18 16:48:16.068  5753  5753 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-18 16:48:16.068  5753  5753 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-18 16:48:16.068  5753  5753 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-18 16:48:16.068  5753  5753 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-18 16:48:16.068  5753  5753 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-18 16:48:16.068  5753  5753 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-18 16:48:16.068  5753  5753 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-18 16:48:16.068  5753  5753 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-18 16:48:16.068  5753  5753 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-18 16:48:16.068  5753  5753 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-18 16:48:16.068  5753  5753 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-18 16:48:16.068  5753  5753 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-18 16:48:16.068  5753  5753 D StrictMode: StrictMode policy violation; ~duration=111 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-18 16:48:16.068  5753  5753 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-18 16:48:16.068  5753  5753 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
11-18 16:48:16.068  5753  5753 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
11-18 16:48:16.068  5753  5753 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
11-18 16:48:16.068  5753  5753 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
11-18 16:48:16.068  5753  5753 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
11-18 16:48:16.068  5753  5753 D StrictMode: 	at com.google.r.k.d(PG:1187)
11-18 16:48:16.068  5753  5753 D StrictMode: 	at com.google.r.k.a(PG:2107)
11-18 16:48:16.068  5753  5753 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
11-18 16:48:16.068  5753  5753 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
11-18 16:48:16.068  5753  5753 D StrictMode: 	at com.google.r.v.a(PG:1161)
11-18 16:48:16.068  5753  5753 D StrictMode: 	at com.google.r.y.a(PG:2188)
11-18 16:48:16.068  5753  5753 D StrictMode: 	at com.google.r.e.b(PG:170)
11-18 16:48:16.068  5753  5753 D StrictMode: 	at com.google.r.e.b(PG:15188)
11-18 16:48:16.068  5753  5753 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
11-18 16:48:16.068  5753  5753 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
11-18 16:48:16.068  5753  5753 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-18 16:48:16.068  5753  5753 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-18 16:48:16.068  5753  5753 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-18 16:48:16.068  5753  5753 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-18 16:48:16.068  5753  5753 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-18 16:48:16.068  5753  5753 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-18 16:48:16.068  5753  5753 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-18 16:48:16.068  5753  5753 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-18 16:48:16.068  5753  5753 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-18 16:48:16.068  5753  5753 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-18 16:48:16.068  5753  5753 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-18 16:48:16.068  5753  5753 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-18 16:48:16.068  5753  5753 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-18 16:48:16.068  5753  5753 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-18 16:48:16.068  5753  5753 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-18 16:48:16.068  5753  5753 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-18 16:48:16.068  5753  5753 D StrictMode: StrictMode policy violation; ~duration=104 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-18 16:48:16.068  5753  5753 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-18 16:48:16.068  5753  5753 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
11-18 16:48:16.068  5753  5753 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
11-18 16:48:16.068  5753  5753 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
11-18 16:48:16.068  5753  5753 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
11-18 16:48:16.068  5753  5753 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
11-18 16:48:16.068  5753  5753 D StrictMode: 	at com.google.r.k.d(PG:1187)
11-18 16:48:16.068  5753  5753 D StrictMode: 	at com.google.r.k.c(PG:18147)
11-18 16:48:16.068  5753  5753 D StrictMode: 	at com.google.r.k.d(PG:583)
11-18 16:48:16.068  5753  5753 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
11-18 16:48:16.068  5753  5753 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
11-18 16:48:16.068  5753  5753 D StrictMode: 	at com.google.r.v.a(PG:1161)
11-18 16:48:16.068  5753  5753 D StrictMode: 	at com.google.r.y.a(PG:2188)
11-18 16:48:16.068  5753  5753 D StrictMode: 	at com.google.r.e.b(PG:170)
11-18 16:48:16.068  5753  5753 D StrictMode: 	at com.google.r.e.b(PG:15188)
11-18 16:48:16.068  5753  5753 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
11-18 16:48:16.068  5753  5753 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
11-18 16:48:16.068  5753  5753 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-18 16:48:16.068  5753  5753 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-18 16:48:16.068  5753  5753 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-18 16:48:16.068  5753  5753 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-18 16:48:16.068  5753  5753 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-18 16:48:16.068  5753  5753 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-18 16:48:16.068  5753  5753 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-18 16:48:16.068  5753  5753 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-18 16:48:16.068  5753  5753 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-18 16:48:16.068  5753  5753 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-18 16:48:16.068  5753  5753 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-18 16:48:16.068  5753  5753 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-18 16:48:16.068  5753  5753 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-18 16:48:16.068  5753  5753 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-18 16:48:16.068  5753  5753 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-18 16:48:16.068  5753  5753 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-18 16:48:16.068  5753  5753 D StrictMode: StrictMode policy violation; ~duration=77 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-18 16:48:16.068  5753  5753 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-18 16:48:16.068  5753  5753 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
11-18 16:48:16.068  5753  5753 D StrictMode: 	at java.io.File.doAccess(File.java:281)
11-18 16:48:16.068  5753  5753 D StrictMode: 	at java.io.File.exists(File.java:361)
11-18 16:48:16.068  5753  5753 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
11-18 16:48:16.068  5753  5753 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
11-18 16:48:16.068  5753  5753 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
11-18 16:48:16.068  5753  5753 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
11-18 16:48:16.068  5753  5753 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
11-18 16:48:16.068  5753  5753 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-18 16:48:16.068  5753  5753 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-18 16:48:16.068  5753  5753 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-18 16:48:16.068  5753  5753 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-18 16:48:16.068  5753  5753 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-18 16:48:16.068  5753  5753 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-18 16:48:16.068  5753  5753 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-18 16:48:16.068  5753  5753 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-18 16:48:16.068  5753  5753 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-18 16:48:16.068  5753  5753 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-18 16:48:16.068  5753  5753 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-18 16:48:16.068  5753  5753 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-18 16:48:16.068  5753  5753 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-18 16:48:16.068  5753  5753 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-18 16:48:16.068  5753  5753 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-18 16:48:16.068  5753  5753 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-18 16:48:16.068  5753  5753 D StrictMode: StrictMode policy violation; ~duration=75 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-18 16:48:16.068  5753  5753 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-18 16:48:16.068  5753  5753 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
11-18 16:48:16.068  5753  5753 D StrictMode: 	at java.io.File.doAccess(File.java:281)
11-18 16:48:16.068  5753  5753 D StrictMode: 	at java.io.File.exists(File.java:361)
11-18 16:48:16.068  5753  5753 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
11-18 16:48:16.068  5753  5753 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-18 16:48:16.068  5753  5753 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-18 16:48:16.068  5753  5753 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-18 16:48:16.068  5753  5753 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-18 16:48:16.068  5753  5753 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-18 16:48:16.068  5753  5753 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-18 16:48:16.068  5753  5753 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-18 16:48:16.068  5753  5753 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-18 16:48:16.068  5753  5753 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-18 16:48:16.068  5753  5753 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-18 16:48:16.068  5753  5753 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-18 16:48:16.068  5753  5753 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-18 16:48:16.068  5753  5753 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-18 16:48:16.068  5753  5753 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-18 16:48:16.068  5753  5753 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-18 16:48:16.068  5753  5753 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-18 16:48:16.068  5753  5753 D StrictMode: StrictMode policy violation; ~duration=73 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-18 16:48:16.068  5753  5753 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-18 16:48:16.068  5753  5753 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
11-18 16:48:16.068  5753  5753 D StrictMode: 	at java.io.File.lastModified(File.java:569)
11-18 16:48:16.068  5753  5753 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
11-18 16:48:16.068  5753  5753 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-18 16:48:16.068  5753  5753 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-18 16:48:16.068  5753  5753 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-18 16:48:16.068  5753  5753 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-18 16:48:16.068  5753  5753 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-18 16:48:16.068  5753  5753 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-18 16:48:16.068  5753  5753 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-18 16:48:16.068  5753  5753 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-18 16:48:16.068  5753  5753 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-18 16:48:16.068  5753  5753 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-18 16:48:16.068  5753  5753 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-18 16:48:16.068  5753  5753 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-18 16:48:16.068  5753  5753 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-18 16:48:16.068  5753  5753 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-18 16:48:16.068  5753  5753 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-18 16:48:16.068  5753  5753 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-18 16:48:16.072  5741  5741 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
11-18 16:48:16.077  3569  3569 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
11-18 16:48:16.081  5741  5741 D DockEventReceiver: finishStartingService: stopping service
11-18 16:48:16.084   929  3763 I ActivityManager: Killing 5404:com.android.chrome/u0a39 (adj 15): empty #17
,11-18 16:48:16.115  4615  4700 D bt_stack_manager: event_shut_down_stack finished.
11-18 16:48:16.116  4615  4699 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
11-18 16:48:16.118  4615  4699 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
11-18 16:48:16.118  4615  4615 D BtGatt.DebugUtils: handleDebugAction() action=null
11-18 16:48:16.118  4615  4615 D BtGatt.GattService: Received stop request...Stopping profile...
11-18 16:48:16.118  4615  4615 D BtGatt.GattService: stop()
11-18 16:48:16.118  4615  4615 D BtGatt.AdvertiseManager: advertise clients cleared
11-18 16:48:16.120  4615  4615 V BluetoothAdapterState: isTurningOff()=false
11-18 16:48:16.120  4615  4615 V BluetoothAdapterState: isTurningOn()=false
11-18 16:48:16.120  4615  4615 V BluetoothAdapterState: isBleTurningOn()=false
11-18 16:48:16.120  4615  4615 V BluetoothAdapterState: isBleTurningOff()=true
11-18 16:48:16.121  4615  4699 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
11-18 16:48:16.121  4615  4699 D BluetoothAdapterProperties: Setting state to 10
11-18 16:48:16.121  4615  4699 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
11-18 16:48:16.122  4615  4699 I BluetoothAdapterState: Entering OffState
11-18 16:48:16.122   929   946 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
11-18 16:48:16.129  4615  4615 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
11-18 16:48:16.129  4615  4615 W BluetoothSdpJni: Cleaning up Bluetooth Health object
11-18 16:48:16.129  4615  4615 I BluetoothServiceJni: cleanupNative: return from cleanup
11-18 16:48:16.130  4615  4700 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
11-18 16:48:16.133  4615  4615 I art     : System.exit called, status: 0
11-18 16:48:16.133  4615  4615 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,11-18 16:48:16.167  5591  5591 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
11-18 16:48:16.167   929  3147 I ActivityManager: Process com.android.bluetooth (pid 4615) has died
,11-18 16:48:16.198  5591  5739 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,11-18 16:48:16.198  5591  5739 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-18 16:48:16.198  5591  5739 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-18 16:48:16.198  5591  5739 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-18 16:48:16.198  5591  5739 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-18 16:48:16.198  5591  5739 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-18 16:48:16.198  5591  5739 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-18 16:48:16.198  5591  5739 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-18 16:48:16.198  5591  5739 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-18 16:48:16.198  5591  5739 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
11-18 16:48:16.198  5591  5739 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-18 16:48:16.198  5591  5739 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
,11-18 16:48:16.201  5591  5638 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-18 16:48:16.213   929   946 I ActivityManager: Start proc 5785:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,11-18 16:48:16.260  5753  5797 W ActivityThread: ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,11-18 16:48:16.274  5785  5785 D AdapterServiceConfig: Adding HeadsetService
,11-18 16:48:16.274  5785  5785 D AdapterServiceConfig: Adding A2dpService
11-18 16:48:16.274  5785  5785 D AdapterServiceConfig: Adding HidService
11-18 16:48:16.275  5785  5785 D AdapterServiceConfig: Adding HealthService
11-18 16:48:16.275  5785  5785 D AdapterServiceConfig: Adding PanService
11-18 16:48:16.275  5785  5785 D AdapterServiceConfig: Adding GattService
11-18 16:48:16.275  5785  5785 D AdapterServiceConfig: Adding BluetoothMapService
,11-18 16:48:16.275  5785  5785 D AdapterServiceConfig: Adding SapService
,11-18 16:48:16.286   929   946 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@5ebfb8d:true
,11-18 16:48:16.286  5785  5785 D BluetoothAdapterState: make() - Creating AdapterState
,11-18 16:48:16.289  5785  5785 I bt_bluedroid: init
,11-18 16:48:16.289  5785  5799 I BluetoothAdapterState: Entering OffState
,11-18 16:48:16.291  5785  5800 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,11-18 16:48:16.291  5785  5800 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
11-18 16:48:16.291  5785  5800 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
11-18 16:48:16.292  5785  5800 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
11-18 16:48:16.292  5785  5785 I bt_bluedroid: get_profile_interface socket
,11-18 16:48:16.294  5785  5803 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:D4
,11-18 16:48:16.294  5785  5785 I bt_bluedroid: get_profile_interface sdp
,11-18 16:48:16.295  5785  5803 D BluetoothAdapterProperties: Name is: Nexus 6P
,11-18 16:48:16.298  5785  5796 I bt_bluedroid: config_hci_snoop_log
,11-18 16:48:16.299   929   946 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 9 receivers.
,11-18 16:48:16.302  5785  5799 D BluetoothAdapterState: Current state: OFF, message: 0
11-18 16:48:16.302  5785  5799 D BluetoothAdapterProperties: Setting state to 14
11-18 16:48:16.302  5785  5799 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,11-18 16:48:16.304  5785  5799 D BluetoothBondStateMachine: make
,11-18 16:48:16.305  5785  5804 I BluetoothBondStateMachine: StableState(): Entering Off State
,11-18 16:48:16.307  5785  5799 I BluetoothAdapterState: Entering PendingCommandState
,11-18 16:48:16.308  5785  5785 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,11-18 16:48:16.310  5785  5785 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1677a00
,11-18 16:48:16.310  5785  5785 D BtGatt.DebugUtils: handleDebugAction() action=null
11-18 16:48:16.311  5785  5785 D BtGatt.GattService: Received start request. Starting profile...
11-18 16:48:16.311  5785  5785 D BtGatt.GattService: start()
11-18 16:48:16.311  5785  5785 I bt_bluedroid: get_profile_interface gatt
11-18 16:48:16.312  5785  5785 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1677a00
,11-18 16:48:16.312  5785  5785 D BtGatt.AdvertiseManager: advertise manager created
,11-18 16:48:16.316  5785  5785 V BluetoothAdapterState: isTurningOff()=false
,11-18 16:48:16.316  5785  5785 V BluetoothAdapterState: isTurningOn()=false
11-18 16:48:16.316  5785  5785 V BluetoothAdapterState: isBleTurningOn()=true
11-18 16:48:16.316  5785  5785 V BluetoothAdapterState: isBleTurningOff()=false
11-18 16:48:16.316  5785  5799 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,11-18 16:48:16.317  5785  5799 I bt_bluedroid: bt_bluedroid
11-18 16:48:16.317  5785  5800 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,11-18 16:48:16.317  5785  5800 I bt_hci  : start_up
,11-18 16:48:16.321  5753  5777 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,11-18 16:48:16.322  5785  5800 I bt_vendor: alloc value 0xf413f871
11-18 16:48:16.322  5785  5800 I bt_vendor: init
11-18 16:48:16.322  5785  5800 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
11-18 16:48:16.322  5785  5800 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,11-18 16:48:16.336   929   946 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@ac5b69a:true
,11-18 16:48:16.429  5785  5800 D bt_hci  : start_up starting async portion
,11-18 16:48:16.429  5785  5807 I bt_hci  : event_finish_startup
11-18 16:48:16.429  5785  5807 I bt_hci_h4: hal_open
11-18 16:48:16.429  5785  5807 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,11-18 16:48:16.430  5785  5807 I bt_userial_vendor: device fd = 54 open
11-18 16:48:16.426  5810  5810 W irq/448-msm_hs_: type=1400 audit(0.0:121): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-18 16:48:16.442  5785  5807 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,11-18 16:48:16.444  5785  5807 D bt_hwcfg: Chipset BCM4358A3
,11-18 16:48:16.444  5785  5807 D bt_hwcfg: Target name = [BCM4358A3]
11-18 16:48:16.445  5785  5807 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,11-18 16:48:16.699   929  2941 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,11-18 16:48:16.707  5785  5799 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 0
,11-18 16:48:16.761  3569  5815 V NQFileLogger: [132] e.a: about to write to file
,11-18 16:48:16.765  3569  5815 V ProcessReports: [132] ProcessReportsService.a: If not already scheduled, schedule for 3600 to 14400 seconds from now (but might be processed inline after 900 seconds instead)
,11-18 16:48:16.801  5785  5807 I bt_hwcfg: bt vendor lib: set UART baud 115200
11-18 16:48:16.801  5785  5807 D bt_hwcfg: Settlement delay -- 100 ms
11-18 16:48:16.802  5785  5807 I bt_hwcfg: Setting fw settlement delay to 100 
,11-18 16:48:16.924  5785  5807 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,11-18 16:48:16.924  5785  5807 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:D4
,11-18 16:48:16.924  5785  5807 I bt_hwcfg: vendor lib fwcfg completed
,11-18 16:48:16.924  5785  5807 I bt_vendor: firmware callback
11-18 16:48:16.924  5785  5807 I bt_hci  : firmware_config_callback
,11-18 16:48:16.927  5785  5817 I bt_btu  : btu_task pending for preload complete event
11-18 16:48:16.927  5785  5817 I bt_btu_task: Bluetooth chip preload is complete
11-18 16:48:16.927  5785  5817 I bt_btu  : btu_task received preload complete event
,11-18 16:48:16.933  5785  5817 I         : BTE_InitTraceLevels -- TRC_HCI
,11-18 16:48:16.933  5785  5817 I         : BTE_InitTraceLevels -- TRC_L2CAP
11-18 16:48:16.933  5785  5817 I         : BTE_InitTraceLevels -- TRC_RFCOMM
11-18 16:48:16.933  5785  5817 I         : BTE_InitTraceLevels -- TRC_AVDT
11-18 16:48:16.934  5785  5817 I         : BTE_InitTraceLevels -- TRC_AVRC
11-18 16:48:16.934  5785  5817 I         : BTE_InitTraceLevels -- TRC_A2D
11-18 16:48:16.934  5785  5817 I         : BTE_InitTraceLevels -- TRC_BNEP
11-18 16:48:16.934  5785  5817 I         : BTE_InitTraceLevels -- TRC_BTM
,11-18 16:48:16.934  5785  5817 I         : BTE_InitTraceLevels -- TRC_GAP
11-18 16:48:16.934  5785  5817 I         : BTE_InitTraceLevels -- TRC_PAN
11-18 16:48:16.934  5785  5817 I         : BTE_InitTraceLevels -- TRC_SDP
11-18 16:48:16.935  5785  5817 I         : BTE_InitTraceLevels -- TRC_GATT
11-18 16:48:16.935  5785  5817 I         : BTE_InitTraceLevels -- TRC_SMP
11-18 16:48:16.935  5785  5817 I         : BTE_InitTraceLevels -- TRC_BTAPP
,11-18 16:48:16.935  5785  5817 I         : BTE_InitTraceLevels -- TRC_BTIF
,11-18 16:48:17.014  5785  5817 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf40bd549
11-18 16:48:17.015  5785  5817 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf40bd549 
,11-18 16:48:17.031  5785  5803 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,11-18 16:48:17.033  5785  5803 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,11-18 16:48:17.034  5785  5803 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:D4
,11-18 16:48:17.036  5785  5803 D BluetoothAdapterProperties: Name is: Nexus 6P
,11-18 16:48:17.038  5785  5803 D BluetoothAdapterProperties: Scan Mode:20
11-18 16:48:17.038  5785  5803 D BluetoothAdapterProperties: Discoverable Timeout:120
11-18 16:48:17.038  5785  5803 D bt_hci  : do_postload posting postload work item
,11-18 16:48:17.039  5785  5807 I bt_hci  : event_postload
,11-18 16:48:17.039  5785  5807 I bt_vendor: sco_config_cb
11-18 16:48:17.039  5785  5807 I bt_hci  : sco_config_callback postload finished.
,11-18 16:48:17.042  5785  5803 D bt_bte_conf: Device ID record 1 : primary
11-18 16:48:17.042  5785  5803 D bt_bte_conf:   vendorId            = 000f
11-18 16:48:17.042  5785  5803 D bt_bte_conf:   vendorIdSource      = 0001
11-18 16:48:17.042  5785  5803 D bt_bte_conf:   product             = 1200
11-18 16:48:17.042  5785  5803 D bt_bte_conf:   version             = 1436
11-18 16:48:17.042  5785  5803 D bt_bte_conf:   clientExecutableURL = 
11-18 16:48:17.042  5785  5803 D bt_bte_conf:   serviceDescription  = 
,11-18 16:48:17.042  5785  5803 D bt_bte_conf:   documentationURL    = 
11-18 16:48:17.043  5785  5803 D bt_bte_conf: bte_load_did_conf no section named DID2.
11-18 16:48:17.043  5785  5800 D bt_stack_manager: event_start_up_stack finished
11-18 16:48:17.043  5785  5799 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
11-18 16:48:17.044  5785  5799 D BluetoothAdapterProperties: Setting state to 15
,11-18 16:48:17.044  5785  5799 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
11-18 16:48:17.045  5785  5799 I BluetoothAdapterState: Entering BleOnState
11-18 16:48:17.046  5785  5807 I bt_vendor: low_power_mode_cb
11-18 16:48:17.050  5785  5799 D BluetoothAdapterState: Current state: BLE ON, message: 1
11-18 16:48:17.051  5785  5799 D BluetoothAdapterProperties: Setting state to 11
11-18 16:48:17.051  5785  5799 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,11-18 16:48:17.061  5785  5785 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1677a00
11-18 16:48:17.062  5785  5785 D HeadsetService: Received start request. Starting profile...
11-18 16:48:17.065  5785  5785 I BluetoothHeadsetServiceJni: classInitNative: succeeds
11-18 16:48:17.065  5785  5785 D HeadsetStateMachine: make
,11-18 16:48:17.075  5785  5799 I BluetoothAdapterState: Entering PendingCommandState
,11-18 16:48:17.078  5785  5785 D HeadsetStateMachine: max_hf_connections = 1
,11-18 16:48:17.078  5785  5785 I bt_bluedroid: get_profile_interface handsfree
11-18 16:48:17.078  5785  5803 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
11-18 16:48:17.078  5785  5803 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
11-18 16:48:17.082  5785  5785 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1677a00
11-18 16:48:17.083  5785  5785 D A2dpService: Received start request. Starting profile...
11-18 16:48:17.083  3569  3569 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,11-18 16:48:17.083  5785  5785 I BluetoothAvrcpServiceJni: classInitNative: succeeds
11-18 16:48:17.084  5785  5785 I bt_bluedroid: get_profile_interface avrcp
,11-18 16:48:17.090  5785  5785 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,11-18 16:48:17.090  5785  5785 I BluetoothA2dpServiceJni: classInitNative: succeeds
11-18 16:48:17.090  5785  5785 D A2dpStateMachine: make
,11-18 16:48:17.091  5785  5785 I bt_bluedroid: get_profile_interface a2dp
11-18 16:48:17.091  5785  5803 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
11-18 16:48:17.093  5785  5825 D A2dpStateMachine: Enter Disconnected: -2
,11-18 16:48:17.093  5785  5785 I BluetoothHidServiceJni: classInitNative: succeeds
,11-18 16:48:17.094  5785  5785 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1677a00
11-18 16:48:17.095  5741  5741 D BluetoothInputDevice: Proxy object connected
11-18 16:48:17.095  5785  5785 D HidService: Received start request. Starting profile...
,11-18 16:48:17.096  5785  5785 I bt_bluedroid: get_profile_interface hidhost
11-18 16:48:17.096  5785  5803 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf409e56d
11-18 16:48:17.096  5785  5785 D HidService: setHidService(): set to: null
11-18 16:48:17.096  5785  5803 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
11-18 16:48:17.096  5741  5741 D HidProfile: Bluetooth service connected
11-18 16:48:17.096  5785  5785 I BluetoothHealthServiceJni: classInitNative: succeeds
11-18 16:48:17.097  5785  5785 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1677a00
11-18 16:48:17.098  5785  5785 D HealthService: Received start request. Starting profile...
,11-18 16:48:17.099  5785  5785 I bt_bluedroid: get_profile_interface health
,11-18 16:48:17.100  5785  5785 I BluetoothPanServiceJni: classInitNative(L105): succeeds
11-18 16:48:17.100  5785  5785 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1677a00
,11-18 16:48:17.101  5741  5741 D BluetoothPan: BluetoothPAN Proxy object connected
,11-18 16:48:17.102  5785  5785 D PanService: Received start request. Starting profile...
11-18 16:48:17.102  5785  5785 D BluetoothPanServiceJni: initializeNative(L110): pan
11-18 16:48:17.102  5785  5785 I bt_bluedroid: get_profile_interface pan
11-18 16:48:17.102  5741  5741 D PanProfile: Bluetooth service connected
11-18 16:48:17.104  5785  5803 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,11-18 16:48:17.106  5785  5785 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1677a00
,11-18 16:48:17.107  5785  5785 D BluetoothMapService: Received start request. Starting profile...
,11-18 16:48:17.107  5785  5785 D BluetoothMapService: start()
11-18 16:48:17.110  5785  5785 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
11-18 16:48:17.111  5785  5785 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
11-18 16:48:17.111  5785  5785 D BluetoothMapAppObserver: createReceiver()
11-18 16:48:17.112  5785  5785 D BluetoothMapAppObserver: initObservers()
11-18 16:48:17.112  5785  5785 D BluetoothMapAppObserver: getEnabledAccountItems()
,11-18 16:48:17.116  5741  5741 D BluetoothMap: Proxy object connected
,11-18 16:48:17.117  5741  5741 D MapProfile: Bluetooth service connected
11-18 16:48:17.117  5741  5741 D BluetoothMap: getConnectedDevices()
11-18 16:48:17.118  5741  5741 D BluetoothMap: Bluetooth is Not enabled
,11-18 16:48:17.118  5785  5785 V SapService: SapBinder()
11-18 16:48:17.119  5785  5785 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1677a00
,11-18 16:48:17.119  5785  5785 D SapService: Received start request. Starting profile...
11-18 16:48:17.119  5785  5785 V SapService: start()
,11-18 16:48:17.121  5785  5785 V BluetoothAdapterState: isTurningOff()=false
11-18 16:48:17.121  5785  5785 V BluetoothAdapterState: isTurningOn()=true
11-18 16:48:17.121  5785  5785 V BluetoothAdapterState: isBleTurningOn()=false
11-18 16:48:17.121  5785  5785 V BluetoothAdapterState: isBleTurningOff()=false
11-18 16:48:17.122  5785  5822 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=2
11-18 16:48:17.122  5785  5785 V BluetoothAdapterState: isTurningOff()=false
11-18 16:48:17.122  5785  5785 V BluetoothAdapterState: isTurningOn()=true
11-18 16:48:17.122  5785  5785 V BluetoothAdapterState: isBleTurningOn()=false
11-18 16:48:17.122  5785  5785 V BluetoothAdapterState: isBleTurningOff()=false
,11-18 16:48:17.122  5785  5785 V BluetoothAdapterState: isTurningOff()=false
11-18 16:48:17.122  5785  5785 V BluetoothAdapterState: isTurningOn()=true
11-18 16:48:17.122  5785  5785 V BluetoothAdapterState: isBleTurningOn()=false
11-18 16:48:17.122  5785  5785 V BluetoothAdapterState: isBleTurningOff()=false
11-18 16:48:17.122  5785  5785 V BluetoothAdapterState: isTurningOff()=false
11-18 16:48:17.122  5785  5785 V BluetoothAdapterState: isTurningOn()=true
11-18 16:48:17.122  5785  5785 V BluetoothAdapterState: isBleTurningOn()=false
11-18 16:48:17.122  5785  5785 V BluetoothAdapterState: isBleTurningOff()=false
11-18 16:48:17.123  5785  5785 V BluetoothAdapterState: isTurningOff()=false
11-18 16:48:17.123  5785  5785 V BluetoothAdapterState: isTurningOn()=true
11-18 16:48:17.123  5785  5785 V BluetoothAdapterState: isBleTurningOn()=false
11-18 16:48:17.123  5785  5785 V BluetoothAdapterState: isBleTurningOff()=false
11-18 16:48:17.123  5785  5785 V BluetoothAdapterState: isTurningOff()=false
11-18 16:48:17.123  5785  5785 V BluetoothAdapterState: isTurningOn()=true
11-18 16:48:17.123  5785  5785 V BluetoothAdapterState: isBleTurningOn()=false
11-18 16:48:17.123  5785  5785 V BluetoothAdapterState: isBleTurningOff()=false
11-18 16:48:17.124  5785  5785 V BluetoothAdapterState: isTurningOff()=false
11-18 16:48:17.124  5785  5785 V BluetoothAdapterState: isTurningOn()=true
11-18 16:48:17.124  5785  5785 V BluetoothAdapterState: isBleTurningOn()=false
11-18 16:48:17.124  5785  5785 V BluetoothAdapterState: isBleTurningOff()=false
11-18 16:48:17.124  5785  5799 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
11-18 16:48:17.124  5785  5799 D BluetoothAdapterProperties: ScanMode =  20
11-18 16:48:17.124  5785  5799 D BluetoothAdapterProperties: State =  11
,11-18 16:48:17.125  5785  5799 D BluetoothAdapterProperties: Setting state to 12
11-18 16:48:17.125  5785  5799 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
11-18 16:48:17.125  5785  5799 I BluetoothAdapterState: Entering OnState
11-18 16:48:17.125  5785  5803 D BluetoothAdapterProperties: Scan Mode:21
11-18 16:48:17.125  3747  3777 D BluetoothHeadset: onBluetoothStateChange: up=true
11-18 16:48:17.126  5785  5803 D BluetoothAdapterProperties: Discoverable Timeout:120
,11-18 16:48:17.126  5741  5752 D BluetoothPbap: onBluetoothStateChange: up=true
,11-18 16:48:17.129  3105  3120 D BluetoothA2dp: onBluetoothStateChange: up=true
11-18 16:48:17.130   929   946 D BluetoothHeadset: onBluetoothStateChange: up=true
11-18 16:48:17.131  3105  3126 D BluetoothInputDevice: onBluetoothStateChange: up=true
11-18 16:48:17.131  3105  3105 D BluetoothA2dp: Proxy object connected
,11-18 16:48:17.132  3105  3973 D BluetoothHeadset: onBluetoothStateChange: up=true
,11-18 16:48:17.133  5741  5751 D BluetoothMap: onBluetoothStateChange: up=true
11-18 16:48:17.133   929   946 D BluetoothHeadset: onBluetoothStateChange: up=true
11-18 16:48:17.133  3105  3105 D BluetoothInputDevice: Proxy object connected
11-18 16:48:17.133  3105  3126 D BluetoothMap: onBluetoothStateChange: up=true
11-18 16:48:17.133  3105  3105 D HidProfile: Bluetooth service connected
,11-18 16:48:17.135  3105  3105 D BluetoothMap: Proxy object connected
11-18 16:48:17.135  3105  3105 D MapProfile: Bluetooth service connected
11-18 16:48:17.135  3105  3105 D BluetoothMap: getConnectedDevices()
11-18 16:48:17.135  5741  5752 D BluetoothInputDevice: onBluetoothStateChange: up=true
11-18 16:48:17.135  3105  3973 D BluetoothPbap: onBluetoothStateChange: up=true
11-18 16:48:17.137  3105  3120 D BluetoothPan: onBluetoothStateChange on: true
,11-18 16:48:17.138  5785  5785 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
11-18 16:48:17.138  5785  5785 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
11-18 16:48:17.138  3105  3105 D BluetoothPan: BluetoothPAN Proxy object connected
11-18 16:48:17.138  5741  5751 D BluetoothPan: onBluetoothStateChange on: true
,11-18 16:48:17.138  3105  3105 D PanProfile: Bluetooth service connected
11-18 16:48:17.139   929   946 D BluetoothA2dp: onBluetoothStateChange: up=true
11-18 16:48:17.139   929   946 D BluetoothHeadset: onBluetoothStateChange: up=true
11-18 16:48:17.140   929   929 D BluetoothA2dp: Proxy object connected
11-18 16:48:17.140  5785  5785 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-18 16:48:17.143  5785  5785 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-18 16:48:17.143   929   929 I Telecom : BluetoothPhoneService: queryPhoneState
11-18 16:48:17.143  5741  5741 D LocalBluetoothProfileManager: Adding local A2DP profile
11-18 16:48:17.145  5785  5785 D ObexServerSockets: Succeed to create listening sockets 
11-18 16:48:17.145  5785  5785 D ObexServerSockets0: startAccept()
11-18 16:48:17.145  5785  5785 D ObexServerSockets0: prepareForNewConnect()
,11-18 16:48:17.147  5785  5785 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
11-18 16:48:17.147  5741  5741 D LocalBluetoothProfileManager: Adding local HEADSET profile
11-18 16:48:17.147  5785  5785 D BluetoothSdpJni: SDP Create record success - handle: 0
11-18 16:48:17.148  5785  5785 D BluetoothMapService: onReceive
,11-18 16:48:17.148  5785  5832 D ObexServerSockets0: Accepting socket connection...
,11-18 16:48:17.148  5785  5833 D ObexServerSockets0: Accepting socket connection...
,11-18 16:48:17.148  5785  5785 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
11-18 16:48:17.149  5785  5785 D BluetoothMapService: STATE_ON
,11-18 16:48:17.151  5785  5834 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-18 16:48:17.153  5785  5834 D BluetoothSdpJni: sdpCreateSapsRecordNative:
,11-18 16:48:17.153  5785  5834 D BluetoothSdpJni: SDP Create record success - handle: 1
,11-18 16:48:17.156  5741  5741 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,11-18 16:48:17.159  5741  5741 D BluetoothA2dp: Proxy object connected
11-18 16:48:17.164  3569  3569 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
11-18 16:48:17.164  5741  5741 D DockEventReceiver: finishStartingService: stopping service
,11-18 16:48:17.170  3105  3105 D BluetoothPbap: Proxy object connected
11-18 16:48:17.170  5741  5741 D BluetoothPbap: Proxy object connected
11-18 16:48:17.170  3105  3105 D PbapServerProfile: Bluetooth service connected
11-18 16:48:17.171  5741  5741 D PbapServerProfile: Bluetooth service connected
,11-18 16:48:17.176  5785  5785 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,11-18 16:48:17.176  5785  5785 D ObexServerSockets0: prepareForNewConnect()
,11-18 16:48:17.179  5785  5838 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-18 16:48:17.193  5785  5842 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-18 16:48:17.196  5785  5842 I BtOppRfcommListener: Accept thread started.
,11-18 16:48:17.209  5591  5739 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-18 16:48:17.209  5591  5739 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-18 16:48:17.209  5591  5739 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-18 16:48:17.209  5591  5739 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-18 16:48:17.209  5591  5739 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-18 16:48:17.209  5591  5739 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-18 16:48:17.209  5591  5739 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-18 16:48:17.209  5591  5739 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-18 16:48:17.209  5591  5739 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,11-18 16:48:17.210  5591  5739 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
11-18 16:48:17.211  5591  5638 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testIsWifiEnabled
,11-18 16:48:17.212   929  3147 D WifiService: setWifiEnabled: false pid=5591, uid=10077
,11-18 16:48:17.213   929  3147 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
11-18 16:48:17.214  5591  5638 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-18 16:48:17.214   929  2939 D WifiStateMachine: WifiStateMachine: Leaving Connected state
11-18 16:48:17.214   929  2939 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
11-18 16:48:17.214   929  2939 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
11-18 16:48:17.214   929  2939 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-18 16:48:17.223   929  5366 D DhcpClient: Clearing IP address
11-18 16:48:17.223   509   928 D CommandListener: Clearing all IP addresses on wlan0
,11-18 16:48:17.227   929   929 D BluetoothHeadset: Proxy object connected
11-18 16:48:17.227   929   929 D BluetoothHeadset: Proxy object connected
11-18 16:48:17.227  3105  3120 D BluetoothHeadset: Proxy object connected
11-18 16:48:17.227  3105  3105 D HeadsetProfile: Bluetooth service connected
11-18 16:48:17.228  3747  3786 D BluetoothHeadset: Proxy object connected
,11-18 16:48:17.228   929   929 D BluetoothHeadset: Proxy object connected
,11-18 16:48:17.230   929   946 D BluetoothHeadset: Proxy object connected
,11-18 16:48:17.231   509   928 D CommandListener: Setting iface cfg
11-18 16:48:17.231  3569  5417 V NativeCrypto: Read error: ssl=0x7fac7c7000: I/O error during system call, Connection timed out
,11-18 16:48:17.233  3569  5417 V NativeCrypto: SSL shutdown failed: ssl=0x7fac7c7000: I/O error during system call, Broken pipe
,11-18 16:48:17.233  3105  3126 D BluetoothHeadset: Proxy object connected
11-18 16:48:17.233  3105  3105 D HeadsetProfile: Bluetooth service connected
11-18 16:48:17.233   929   946 D BluetoothHeadset: Proxy object connected
11-18 16:48:17.236   929  3807 D ConnectivityService: reportNetworkConnectivity(100, false) by 10012
11-18 16:48:17.236   929  5364 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Forcing reevaluation for UID 10012
11-18 16:48:17.238   929  5364 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.gstatic.com": No address associated with hostname
11-18 16:48:17.239   929  2941 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] validation failed
11-18 16:48:17.239   929   946 D BluetoothHeadset: Proxy object connected
11-18 16:48:17.239   929  2941 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
11-18 16:48:17.240   929  2941 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
11-18 16:48:17.246   929  2941 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
11-18 16:48:17.246   929  2941 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
11-18 16:48:17.247   535   535 E Parcel  : Reading a NULL string not supported here.
,11-18 16:48:17.250  5741  5752 D BluetoothHeadset: Proxy object connected
11-18 16:48:17.251   929   929 D RttService: SCAN_AVAILABLE : 1
,11-18 16:48:17.251   929  3047 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
11-18 16:48:17.251   929  2941 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
11-18 16:48:17.252  3718  3837 W QCNEJ   : |CORE| network lost: 100
11-18 16:48:17.253  3718  3837 W QCNEJ   : |CORE| onLost: unbind the process to WIFI
,11-18 16:48:17.257  5741  5741 D HeadsetProfile: Bluetooth service connected
,11-18 16:48:17.259   929  5367 D DhcpClient: Receive thread stopped
,11-18 16:48:17.263   929  2939 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,11-18 16:48:17.274   509   928 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-18 16:48:17.283   929  2939 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,11-18 16:48:17.306   509   928 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-18 16:48:17.306   509   928 D CommandListener: Clearing all IP addresses on wlan0
,11-18 16:48:17.307   929  2941 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
11-18 16:48:17.307   509   928 D TetherController: Setting IP forward enable = 0
,11-18 16:48:17.307   929  2941 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,11-18 16:48:17.310   929   946 D Tethering: MasterInitialState.processMessage what=3
,11-18 16:48:17.318   929  2939 D DhcpClient: doQuit
,11-18 16:48:17.318   929  2939 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,11-18 16:48:17.319   929  5366 D DhcpClient: onQuitting
,11-18 16:48:17.319  3438  3438 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
11-18 16:48:17.319  5248  5248 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@a1180fd and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
11-18 16:48:17.323  3569  5855 D GetConfigurationSnapshotOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,11-18 16:48:17.323  3955  3955 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
11-18 16:48:17.325  5036  5059 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
,11-18 16:48:17.325  5036  5059 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
11-18 16:48:17.325  5036  5059 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,0,0,0
11-18 16:48:17.325  5036  5059 E SarControlService: no key has been found,reset the power
11-18 16:48:17.326  5036  5073 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
11-18 16:48:17.326  5036  5073 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
11-18 16:48:17.326  5036  5073 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
11-18 16:48:17.326  5061  5061 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
11-18 16:48:17.326  5061  5061 D QcrilMsgTunnelSocket: [1002] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
11-18 16:48:17.328  5036  5073 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
,11-18 16:48:17.328  5036  5073 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
11-18 16:48:17.329  3937  3937 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
11-18 16:48:17.331  5061  5075 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@465030b HexData = [00000000ea03000000000000ffffffff]
,11-18 16:48:17.331  5061  5075 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-18 16:48:17.331  5061  5075 D QcrilMsgTunnelSocket: [1002] < OEM_HOOK_RAW [null]
11-18 16:48:17.332  5061  5061 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
11-18 16:48:17.332  3937  3937 D SystemUpdateService: onCreate
11-18 16:48:17.333  5036  5046 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
11-18 16:48:17.333  5036  5073 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
11-18 16:48:17.334  5061  5061 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
11-18 16:48:17.334  5061  5061 D QcrilMsgTunnelSocket: [1003] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
11-18 16:48:17.336  3937  3937 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,11-18 16:48:17.341  3937  5860 I SystemUpdateService: active receiver: enabled
11-18 16:48:17.343  5061  5075 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@465030b HexData = [00000000eb03000000000000ffffffff]
11-18 16:48:17.343  5061  5075 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-18 16:48:17.343  5061  5075 D QcrilMsgTunnelSocket: [1003] < OEM_HOOK_RAW [null]
11-18 16:48:17.343  5061  5061 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
11-18 16:48:17.343  5036  5047 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
,11-18 16:48:17.348  3937  5860 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,11-18 16:48:17.349  3438  3438 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
,11-18 16:48:17.350  3937  3937 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,11-18 16:48:17.351  3937  5860 I SystemUpdateService: network: null; metered: false; mobile allowed: true
11-18 16:48:17.351  3937  5860 I SystemUpdateService: now status is 0 (complete)
11-18 16:48:17.351  3937  5860 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
11-18 16:48:17.351  3937  5860 I SystemUpdateService: file has been verified
11-18 16:48:17.351  3937  5860 I SystemUpdateService: OTA package size = 21989297
11-18 16:48:17.354  3937  5860 I SystemUpdateService: showing system update notification
11-18 16:48:17.356  3937  5390 I iu.UploadsManager: num queued entries: 0
11-18 16:48:17.356  3937  5390 I iu.UploadsManager: num updated entries: 0
11-18 16:48:17.357  3937  5390 I iu.SyncManager: NEXT; no task
,11-18 16:48:17.359  3438  3438 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,11-18 16:48:17.365   929   929 V NotificationService: pkg=com.google.android.gms canInterrupt=false intercept=true
,11-18 16:48:17.365  3937  3937 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
11-18 16:48:17.367  3937  3937 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,11-18 16:48:17.368  3569  5852 I PhenotypeFlagCommitter: Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
11-18 16:48:17.371  3569  5852 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,11-18 16:48:17.380   929  3647 I ActivityManager: Start proc 5865:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,11-18 16:48:17.382  3937  3937 D SystemUpdateService: onDestroy
,11-18 16:48:17.403   509   928 E Netd    : netlink response contains error (No such file or directory)
,11-18 16:48:17.404   929  2941 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,11-18 16:48:17.404   929  2941 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,11-18 16:48:17.407  3438  3438 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
11-18 16:48:17.408  3569  5852 W Uploader:  no longer exists, so no auth token.
,11-18 16:48:17.414  3569  5855 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,11-18 16:48:17.423  3438  3438 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
11-18 16:48:17.422  5865  5865 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm64
11-18 16:48:17.425  3569  5852 D Uploader: Network request failed class java.net.UnknownHostException(Unable to resolve host "play.googleapis.com": No address associated with hostname)
,11-18 16:48:17.427  5865  5865 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,11-18 16:48:17.432  5865  5865 D SprintDMHelper: simOperator: 
11-18 16:48:17.432  5865  5865 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,11-18 16:48:17.445   929  3807 I ActivityManager: Start proc 5880:com.android.chrome/u0a39 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
,11-18 16:48:17.519  4972  5894 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,11-18 16:48:17.532   929   940 I ActivityManager: Start proc 5895:com.google.android.apps.gcs/u0a11 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,11-18 16:48:17.533   929  2939 D wifi    : In wifi stop Hal
,11-18 16:48:17.534   929  2939 D wifi    : halHandle = 0x7f962f0c80, mVM = 0x7fb28cd140, mCls = 0x100a02
,11-18 16:48:17.534   929   940 I ActivityManager: Killing 5248:com.google.android.music:main/u0a59 (adj 15): empty #17
11-18 16:48:17.534   929  3437 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
11-18 16:48:17.534   929  3437 D WifiHAL : Got a signal to exit!!!
11-18 16:48:17.534   929  3437 I WifiHAL : Exit wifi_event_loop
11-18 16:48:17.535   929  2939 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 11
11-18 16:48:17.535   929  2939 E WifiHAL : Event processing terminated
11-18 16:48:17.535   929  2939 D wifi    : In wifi cleaned up handler
11-18 16:48:17.535   929  2939 I WifiHAL : Internal cleanup completed
,11-18 16:48:17.559   929  3437 D wifi    : set interface wlan0 flags (DOWN)
,11-18 16:48:17.561   929  2939 D WifiNative-HAL: HAL event thread stopped successfully
11-18 16:48:17.561  4972  4972 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,11-18 16:48:17.563  4087  4213 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,11-18 16:48:17.575  5895  5895 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm64
,11-18 16:48:17.582   929  3147 I ActivityManager: Killing 3844:com.android.providers.calendar/u0a1 (adj 15): empty #17
,11-18 16:48:17.718  5591  5739 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-18 16:48:17.718  5591  5739 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-18 16:48:17.718  5591  5739 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-18 16:48:17.718  5591  5739 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-18 16:48:17.718  5591  5739 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-18 16:48:17.718  5591  5739 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-18 16:48:17.718  5591  5739 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-18 16:48:17.718  5591  5739 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-18 16:48:17.718  5591  5739 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,11-18 16:48:17.720  5591  5739 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
,11-18 16:48:17.723   929  3805 D WifiService: setWifiEnabled: true pid=5591, uid=10077
,11-18 16:48:17.723   929  3805 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-18 16:48:17.724  5591  5638 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-18 16:48:17.763   929   946 D Tethering: InitialState.processMessage what=4
11-18 16:48:17.764   509   928 D SoftapController: Softap fwReload - Ok
,11-18 16:48:17.766   929   946 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,11-18 16:48:17.768   509   928 D CommandListener: Setting iface cfg
,11-18 16:48:17.768   509   928 D CommandListener: Trying to bring down wlan0
,11-18 16:48:17.769   509   928 D CommandListener: Clearing all IP addresses on wlan0
,11-18 16:48:17.771   929  2939 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,11-18 16:48:17.929  3569  5861 I SQLiteConnectionPool: The connection pool for /data/user/0/com.google.android.gms/databases/phenotype.db has been closed but there are still 1 connections in use.  They will be closed as they are released back to the pool.
,11-18 16:48:17.931  3569  5861 E ClearcutLoggerIntentService: attempt to re-open an already-closed object: SQLiteDatabase: /data/user/0/com.google.android.gms/databases/phenotype.db
11-18 16:48:17.931  3569  5861 E ClearcutLoggerIntentService: java.lang.IllegalStateException: attempt to re-open an already-closed object: SQLiteDatabase: /data/user/0/com.google.android.gms/databases/phenotype.db
11-18 16:48:17.931  3569  5861 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteClosable.acquireReference(SQLiteClosable.java:55)
11-18 16:48:17.931  3569  5861 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteDatabase.endTransaction(SQLiteDatabase.java:520)
11-18 16:48:17.931  3569  5861 E ClearcutLoggerIntentService: 	at com.google.android.gms.phenotype.service.a.g.a(SourceFile:143)
11-18 16:48:17.931  3569  5861 E ClearcutLoggerIntentService: 	at com.google.android.gms.clearcut.service.a.a(SourceFile:532)
11-18 16:48:17.931  3569  5861 E ClearcutLoggerIntentService: 	at com.google.android.gms.clearcut.service.a.a(SourceFile:149)
11-18 16:48:17.931  3569  5861 E ClearcutLoggerIntentService: 	at com.google.android.gms.common.service.g.run(SourceFile:178)
11-18 16:48:17.931  3569  5861 E ClearcutLoggerIntentService: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
11-18 16:48:17.931  3569  5861 E ClearcutLoggerIntentService: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
11-18 16:48:17.931  3569  5861 E ClearcutLoggerIntentService: 	at java.lang.Thread.run(Thread.java:818)
,11-18 16:48:18.228   929  3763 D WifiService: setWifiEnabled: true pid=5591, uid=10077
,11-18 16:48:18.228   929  3763 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-18 16:48:18.374   929  2939 D wifi    : set interface wlan0 flags (UP)
,11-18 16:48:18.375   929  2939 I WifiHAL : Initializing wifi
11-18 16:48:18.375   929  2939 I WifiHAL : Creating socket
,11-18 16:48:18.378   929   946 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,11-18 16:48:18.384   929  2939 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
,11-18 16:48:18.384   929  2939 D wifi    : Did set static halHandle = 0x7f962f0c80
,11-18 16:48:18.384   929  2939 D wifi    : halHandle = 0x7f962f0c80, mVM = 0x7fb28cd140, mCls = 0x1892
11-18 16:48:18.384   929  2939 D wifi    : array field set
,11-18 16:48:18.384   929  2939 I WifiNative-HAL: interface[0] = wlan0
11-18 16:48:18.385   509   928 D TetherController: Setting IP forward enable = 0
,11-18 16:48:18.386   929  5914 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=547980512384
11-18 16:48:18.386   929  5914 D wifi    : waitForHalEvents called, vm = 0x7fb28cd140, obj = 0x1892, env = 0x7f97c542c0
,11-18 16:48:18.445  5916  5916 I wpa_supplicant: Successfully initialized wpa_supplicant
,11-18 16:48:18.489   929  2939 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,11-18 16:48:18.513  5916  5916 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,11-18 16:48:18.551  5916  5916 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,11-18 16:48:18.551  5916  5916 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,11-18 16:48:18.566   929  2939 D WifiConfigStore: Loading config and enabling all networks 
,11-18 16:48:18.588   929  2939 D WifiConfigStore: loaded 0 passpoint configs
,11-18 16:48:18.589   929  2939 W WifiConfigStore: Upgrading network 4 to android.uid.system:1000
11-18 16:48:18.589   929  2939 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
11-18 16:48:18.590   929  2939 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,11-18 16:48:18.590   929  2939 W WifiConfigStore: Upgrading network 3 to android.uid.system:1000
11-18 16:48:18.590   929  2939 W WifiConfigStore: Upgrading network 2 to android.uid.system:1000
,11-18 16:48:18.591   929  2939 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
11-18 16:48:18.591   929  2939 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 5
,11-18 16:48:18.591   929  2939 E WifiConfigStore: found sortedWifiConfigurations : "AndroidAP"WPA_PSK
,11-18 16:48:18.591   929  2939 E WifiConfigStore: found sortedWifiConfigurations : "AndroidHotspot2346"WPA_PSK
,11-18 16:48:18.591   929  2939 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,11-18 16:48:18.591   929  2939 E WifiConfigStore: found sortedWifiConfigurations : "Thali_internal"WPA_PSK
11-18 16:48:18.591   929  2939 E WifiConfigStore: found sortedWifiConfigurations : "MC"WPA_PSK
11-18 16:48:18.593   929  2939 D WifiNative-HAL: Setting external_sim to 1
,11-18 16:48:18.594   929  2939 D wifi    : setting dfs flag to true, 0x7f98844920
11-18 16:48:18.594   929  2939 D WifiStateMachine: Setting OUI to DA-A1-19
,11-18 16:48:18.594   929  2939 D wifi    : setting scan oui 0x7f98844920
11-18 16:48:18.594   929  2939 D WifiHAL : Sending mac address OUI
,11-18 16:48:18.594  4972  4972 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
11-18 16:48:18.597   929  2939 E native  : do suspend false
,11-18 16:48:18.608   929  2939 D wifi    : android_net_wifi_setLinkLayerStats: 1
11-18 16:48:18.608   929   929 D RttService: SCAN_AVAILABLE : 3
,11-18 16:48:18.608   509   928 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
11-18 16:48:18.608   929  3047 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
11-18 16:48:18.610   509   928 D CommandListener: Setting iface cfg
,11-18 16:48:18.615   929  2938 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '124 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 124 Failed to set address (No such device)'
,11-18 16:48:18.615   929  2938 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,11-18 16:48:18.626   929  2938 D WifiNative-HAL: p2pGetDeviceAddress
,11-18 16:48:18.632   929   944 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=106573 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=18 mControllerEnergyUsed=68 }
,11-18 16:48:18.633   929  2938 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:70
,11-18 16:48:18.735  5591  5739 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-18 16:48:18.735  5591  5739 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-18 16:48:18.735  5591  5739 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-18 16:48:18.735  5591  5739 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-18 16:48:18.735  5591  5739 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-18 16:48:18.735  5591  5739 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-18 16:48:18.735  5591  5739 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-18 16:48:18.735  5591  5739 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-18 16:48:18.735  5591  5739 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,11-18 16:48:18.739  5591  5739 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
,11-18 16:48:18.742  5591  5638 D BluetoothAdapter: enable(): BT is already enabled..!
,11-18 16:48:18.743   929  3763 D WifiService: setWifiEnabled: true pid=5591, uid=10077
,11-18 16:48:18.743   929  3763 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
11-18 16:48:18.745  5591  5638 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-18 16:48:18.745  5591  5638 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-18 16:48:18.745  5591  5638 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,11-18 16:48:18.745  5591  5638 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3f13be removed from the list
,11-18 16:48:18.746  5591  5638 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-18 16:48:18.747  5591  5638 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5d37c1f removed from the list
11-18 16:48:18.747  5591  5638 D io.jxcore.node.ConnectivityMonitor: stop
,11-18 16:48:18.751  5591  5638 I io.jxcore.node.IncomingSocketThreadTest: Starting test: testSetTcpPortNumber
,11-18 16:48:18.753  5591  5638 I io.jxcore.node.IncomingSocketThreadTest: Starting test: testGetTcpPortNumber
,11-18 16:48:18.755  5591  5638 I io.jxcore.node.IncomingSocketThreadTest: Starting test: testGetLocalHostPort
11-18 16:48:18.756  5591  5638 I io.jxcore.node.IncomingSocketThreadTest: Starting test: testConstructor
,11-18 16:48:18.760  5591  5638 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityCreated
,11-18 16:48:18.760  5591  5638 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,11-18 16:48:18.761  5591  5638 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityResumed
,11-18 16:48:18.761  5591  5638 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
11-18 16:48:18.762  5591  5638 I io.jxcore.node.LifeCycleMonitorTest: Starting test: constructor
11-18 16:48:18.764  5591  5638 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivitySaveInstanceState
,11-18 16:48:18.764  5591  5638 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@fca362c Bundle[{}]
11-18 16:48:18.765  5591  5638 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testStartStop
11-18 16:48:18.765  5591  5638 I io.jxcore.node.LifeCycleMonitor: start: OK
11-18 16:48:18.765  5591  5638 I io.jxcore.node.LifeCycleMonitor: stop: OK
,11-18 16:48:18.765  5591  5638 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityStarted
11-18 16:48:18.765  5591  5638 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
11-18 16:48:18.766  5591  5638 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityStopped
,11-18 16:48:18.766  5591  5638 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
11-18 16:48:18.767  5591  5638 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityDestroyed
11-18 16:48:18.767  5591  5638 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
,11-18 16:48:18.768  5591  5638 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityPaused
11-18 16:48:18.768  5591  5638 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
11-18 16:48:18.770  5591  5638 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testToString
,11-18 16:48:18.772  5591  5638 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testToJsonObject
,11-18 16:48:18.773  5591  5638 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testConstructorWithParameters
,11-18 16:48:18.773  5591  5638 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testSetListeningOnPortNumber
11-18 16:48:18.774  5591  5638 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testGetListeningOnPortNumber
11-18 16:48:18.774  5591  5638 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testDefaultConstructor
,11-18 16:48:18.776  5591  5638 I io.jxcore.node.OutgoingSocketThreadTest: Starting test: testClose
,11-18 16:48:18.777  5591  5638 I io.jxcore.node.OutgoingSocketThreadTest: Starting test: testGetListeningOnPortNumber
11-18 16:48:18.778  5591  5638 I io.jxcore.node.OutgoingSocketThreadTest: Starting test: testConstructor
,11-18 16:48:18.780  5591  5638 I io.jxcore.node.SocketThreadBaseTest: Starting test: testGetListener
,11-18 16:48:18.781  5591  5638 I io.jxcore.node.SocketThreadBaseTest: Starting test: testSetPeerProperties
11-18 16:48:18.782  5591  5638 I io.jxcore.node.SocketThreadBaseTest: Starting test: testClose
11-18 16:48:18.782  5591  5638 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 141)
11-18 16:48:18.782  5591  5638 I io.jxcore.node.SocketThreadBaseTest: Starting test: testCloseLocalSocketAndStreams
11-18 16:48:18.782  5591  5638 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
11-18 16:48:18.782  5591  5638 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 142)
11-18 16:48:18.783  5591  5638 I io.jxcore.node.SocketThreadBaseTest: Starting test: testGetPeerProperties
11-18 16:48:18.783  5591  5638 I io.jxcore.node.SocketThreadBaseTest: Starting test: testEquals
11-18 16:48:18.784  5591  5638 I io.jxcore.node.SocketThreadBaseTest: Starting test: testGetLocalHostAddressAsString
,11-18 16:48:18.784  5591  5638 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-18 16:48:18.784  5591  5638 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9e2a535 added. We now have 3 listener(s)
11-18 16:48:18.785  5591  5638 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-18 16:48:18.786  5591  5638 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-18 16:48:18.786  5591  5638 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-18 16:48:18.786  5591  5638 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-18 16:48:18.786  5591  5638 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fd4adca added. We now have 3 listener(s)
11-18 16:48:18.786  5591  5638 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-18 16:48:18.787  5591  5638 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,11-18 16:48:18.791  5591  5638 I io.jxcore.node.StartStopOperationHandlerTest: Starting test: testCancelCurrentOperation
,11-18 16:48:18.791  5591  5638 I io.jxcore.node.StartStopOperationHandlerTest: Starting test: testExecuteStopOperation
11-18 16:48:18.791  5591  5638 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 5
11-18 16:48:18.791  5591  5638 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 4 -> 5
11-18 16:48:18.792  5591  5638 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-61,5,main], id: 61
11-18 16:48:18.792  5591  5638 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-61,5,main], id: 61
11-18 16:48:18.792  5591  5638 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-61,5,main], id: 61
11-18 16:48:18.792  5591  5638 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
11-18 16:48:18.792  5591  5638 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
11-18 16:48:18.792  5591  5638 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
,11-18 16:48:18.792  5591  5638 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-18 16:48:18.792  5591  5638 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
,11-18 16:48:18.795  5591  5638 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,11-18 16:48:18.795  5591  5638 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
11-18 16:48:18.795  5591  5638 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
11-18 16:48:18.795  5591  5638 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
11-18 16:48:18.795  5591  5638 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
11-18 16:48:18.796  5591  5591 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
11-18 16:48:18.796  5591  5638 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
11-18 16:48:18.796  5591  5638 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-18 16:48:18.796  5591  5638 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
11-18 16:48:18.796  5591  5920 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
,11-18 16:48:18.797  5591  5920 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-18 16:48:18.796  5795  5795 W Binder_1: type=1400 audit(0.0:122): avc: denied { ioctl } for path="socket:[34251]" dev="sockfs" ino=34251 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,11-18 16:48:18.796  5795  5795 W Binder_1: type=1400 audit(0.0:123): avc: denied { ioctl } for path="socket:[34251]" dev="sockfs" ino=34251 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-18 16:48:18.799  5591  5638 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-18 16:48:18.799  5591  5638 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-18 16:48:18.799  5591  5638 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
11-18 16:48:18.801  5591  5920 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
11-18 16:48:18.803  5591  5638 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-61,5,main], id: 61
11-18 16:48:18.803  5591  5638 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-18 16:48:18.803  5591  5638 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-18 16:48:18.803  5591  5638 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-18 16:48:18.803  5591  5638 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 5
11-18 16:48:18.805  5591  5638 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
11-18 16:48:18.805  5591  5638 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-61,5,main], id: 61
11-18 16:48:18.805  5591  5638 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
11-18 16:48:18.805  5591  5638 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: createAdvertiseDataToServiceData 
11-18 16:48:18.805  5591  5638 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-18 16:48:18.805  5591  5638 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 05 60 83 34 25 D7 D4
11-18 16:48:18.806  5591  5638 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[5, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-18 16:48:18.806  5591  5638 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: created AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[5, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-18 16:48:18.806  5591  5638 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: Current thread: Thread[Thread-61,5,main], id: 61
11-18 16:48:18.806  5591  5638 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: was started = false
,11-18 16:48:18.806  5591  5638 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: advertiseData = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[5, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-18 16:48:18.806  5591  5638 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData finished: Current thread: Thread[Thread-61,5,main], id: 61
11-18 16:48:18.806  5591  5638 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
,11-18 16:48:18.806  5591  5638 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... adv data = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[5, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]Current thread: Thread[Thread-61,5,main], id: 61
11-18 16:48:18.807  5591  5638 D BluetoothAdapter: STATE_ON
11-18 16:48:18.810  5785  5823 D BtGatt.GattService: registerClient() - UUID=e00cda1c-eed0-449a-8d14-76c3fdce064e
11-18 16:48:18.811  5785  5803 D BtGatt.GattService: onClientRegistered() - UUID=e00cda1c-eed0-449a-8d14-76c3fdce064e, clientIf=5
11-18 16:48:18.811  5591  5601 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
,11-18 16:48:18.814  5785  5805 D BtGatt.AdvertiseManager: message : 0
11-18 16:48:18.816  5785  5805 D BtGatt.AdvertiseManager: starting multi advertising
,11-18 16:48:18.819  5785  5803 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,11-18 16:48:18.822  5785  5803 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,11-18 16:48:18.823  5591  5638 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment Current thread: Thread[Thread-61,5,main], id: 61
11-18 16:48:18.823  5591  5638 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTINGCurrent thread: Thread[Thread-61,5,main], id: 61
11-18 16:48:18.823  5591  5638 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
11-18 16:48:18.823  5591  5638 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged default (no call to listener). Current thread: Thread[Thread-61,5,main], id: 61
,11-18 16:48:18.823  5591  5638 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-61,5,main], id: 61
11-18 16:48:18.823  5591  5638 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[Thread-61,5,main], id: 61
11-18 16:48:18.823  5591  5638 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[Thread-61,5,main], id: 61
11-18 16:48:18.823  5591  5638 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser started = true Current thread: Thread[Thread-61,5,main], id: 61
11-18 16:48:18.823  5591  5638 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-18 16:48:18.825  5591  5638 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-18 16:48:18.825  5591  5638 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-18 16:48:18.826  5591  5638 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-18 16:48:18.826  5591  5638 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-18 16:48:18.826  5591  5638 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-18 16:48:18.826  5591  5591 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,11-18 16:48:18.827  5591  5591 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess : Current thread: Thread[main,5,main], id: 1
11-18 16:48:18.827  5591  5591 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNINGCurrent thread: Thread[main,5,main], id: 1
11-18 16:48:18.827  5591  5591 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
11-18 16:48:18.827  5591  5591 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  true. Current thread: Thread[main,5,main], id: 1
11-18 16:48:18.827  5591  5591 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[main,5,main], id: 1
11-18 16:48:18.827  5591  5591 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-18 16:48:18.827  5591  5591 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-18 16:48:18.827  5591  5591 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [ADVERTISING]
11-18 16:48:18.827  5591  5591 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-18 16:48:18.827  5591  5591 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-18 16:48:18.827  5591  5591 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]Current thread: Thread[main,5,main], id: 1
11-18 16:48:18.827  5591  5591 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
11-18 16:48:18.827  5591  5591 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-18 16:48:18.830  5591  5591 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-18 16:48:18.830  5591  5591 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
11-18 16:48:18.831  5591  5591 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-18 16:48:18.831  5591  5591 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-18 16:48:18.831  5591  5591 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-18 16:48:18.831  5591  5591 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,11-18 16:48:19.332  5591  5591 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
,11-18 16:48:19.332  5591  5591 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
11-18 16:48:19.332  5591  5591 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,11-18 16:48:21.697  5916  5916 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-18 16:48:21.718  5916  5916 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-18 16:48:21.729  5916  5916 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-18 16:48:21.741   929  3147 I ActivityManager: Killing 5466:com.android.defcontainer/u0a7 (adj 15): empty #17
,11-18 16:48:21.764   929  2939 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,11-18 16:48:21.775   929  2939 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3
11-18 16:48:21.776   929  2939 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-18 16:48:21.787   929  2939 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=0
,11-18 16:48:21.838   929  2939 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=0
,11-18 16:48:21.846  5916  5916 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,11-18 16:48:22.310  5916  5916 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,11-18 16:48:22.329  5591  5638 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
,11-18 16:48:22.329  5591  5638 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,11-18 16:48:22.329  5591  5638 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
,11-18 16:48:22.329  5591  5638 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
11-18 16:48:22.329  5591  5638 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
11-18 16:48:22.330  5591  5638 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-18 16:48:22.330  5591  5920 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
11-18 16:48:22.330  5591  5638 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
11-18 16:48:22.330  5591  5920 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
11-18 16:48:22.330  5591  5638 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
11-18 16:48:22.330  5591  5920 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
11-18 16:48:22.330  5591  5638 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
11-18 16:48:22.331  5591  5638 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-18 16:48:22.331  5591  5591 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
11-18 16:48:22.331  5591  5638 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,11-18 16:48:22.331  5591  5638 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-18 16:48:22.331  5591  5638 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
11-18 16:48:22.331  5591  5638 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-61,5,main], id: 61
11-18 16:48:22.331  5591  5638 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-18 16:48:22.332  5591  5638 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-61,5,main], id: 61
11-18 16:48:22.334  5591  5638 D BluetoothAdapter: STATE_ON
11-18 16:48:22.334  5591  5638 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-18 16:48:22.337  5591  5638 D BluetoothAdapter: STATE_ON
,11-18 16:48:22.337  5591  5638 D BluetoothLeScanner: could not find callback wrapper
11-18 16:48:22.337  5591  5638 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-18 16:48:22.337  5591  5638 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-18 16:48:22.338  5591  5638 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-61,5,main], id: 61
11-18 16:48:22.338  5591  5638 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-61,5,main], id: 61
11-18 16:48:22.338  5591  5638 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
,11-18 16:48:22.338  5591  5638 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-61,5,main], id: 61
11-18 16:48:22.340  5785  5805 D BtGatt.AdvertiseManager: message : 1
11-18 16:48:22.341  5785  5805 D BtGatt.AdvertiseManager: stop advertise for client 5
,11-18 16:48:22.351  5785  5803 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
,11-18 16:48:22.351  5785  5803 D BtGatt.GattService: Client app is not null!
,11-18 16:48:22.354  5785  5796 D BtGatt.GattService: unregisterClient() - clientIf=5
,11-18 16:48:22.355  5591  5638 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-18 16:48:22.355  5591  5638 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
11-18 16:48:22.355  5591  5638 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
,11-18 16:48:22.355  5591  5638 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  false. Current thread: Thread[Thread-61,5,main], id: 61
11-18 16:48:22.355  5591  5638 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-61,5,main], id: 61
11-18 16:48:22.355  5591  5638 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-61,5,main], id: 61
11-18 16:48:22.355  5591  5638 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-18 16:48:22.356  5591  5638 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-18 16:48:22.356  5916  5916 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
11-18 16:48:22.356  5916  5916 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
11-18 16:48:22.357  5591  5638 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
11-18 16:48:22.358  5591  5638 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-18 16:48:22.359  5591  5638 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-18 16:48:22.359  5591  5638 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-18 16:48:22.360  5591  5638 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-18 16:48:22.360  5591  5638 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-18 16:48:22.361  5591  5591 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-18 16:48:22.361  5591  5591 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,11-18 16:48:22.361  5591  5591 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
11-18 16:48:22.361  5591  5591 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-18 16:48:22.361  5591  5591 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,11-18 16:48:22.361  5591  5591 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-18 16:48:22.361  5591  5591 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-18 16:48:22.361  5591  5591 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-18 16:48:22.362  5591  5591 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
,11-18 16:48:22.362  5591  5591 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [ADVERTISING]
11-18 16:48:22.362  5591  5591 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-18 16:48:22.362  5591  5591 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-18 16:48:22.362  5591  5591 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
11-18 16:48:22.362  5591  5591 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
,11-18 16:48:22.365  5591  5591 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-18 16:48:22.365   929  2939 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
11-18 16:48:22.365  5591  5591 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
,11-18 16:48:22.365  5591  5591 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-18 16:48:22.365   929  2939 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
11-18 16:48:22.366  5591  5591 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-18 16:48:22.366   929  2941 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
11-18 16:48:22.366  5591  5591 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,11-18 16:48:22.372  5591  5638 I io.jxcore.node.StartStopOperationHandlerTest: Starting test: testCheckCurrentOperationStatus
,11-18 16:48:22.373  5591  5638 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-18 16:48:22.374  5591  5638 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-18 16:48:22.374  5591  5638 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
11-18 16:48:22.374  5591  5638 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
11-18 16:48:22.374  5591  5638 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-18 16:48:22.374  5591  5638 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
,11-18 16:48:22.376  5591  5638 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,11-18 16:48:22.380  5591  5638 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
,11-18 16:48:22.380  5591  5638 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-18 16:48:22.380  5591  5638 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
11-18 16:48:22.381   929  2939 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-18 16:48:22.385  5591  5638 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-61,5,main], id: 61
,11-18 16:48:22.385  5591  5638 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,11-18 16:48:22.386  5591  5638 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,11-18 16:48:22.386  5591  5638 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-18 16:48:22.386  5591  5638 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 5
,11-18 16:48:22.389  5591  5638 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
11-18 16:48:22.392   509   928 D CommandListener: Setting iface cfg
11-18 16:48:22.393  5591  5638 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
11-18 16:48:22.393  5591  5638 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-18 16:48:22.393  5591  5638 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
11-18 16:48:22.393  5591  5638 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
11-18 16:48:22.393  5591  5638 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
11-18 16:48:22.394  5591  5638 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
11-18 16:48:22.394  5591  5638 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-61,5,main], id: 61
,11-18 16:48:22.395  5591  5638 D BluetoothAdapter: STATE_ON
11-18 16:48:22.397  5785  5795 D BtGatt.GattService: registerClient() - UUID=e86d56ff-fafe-434b-8585-03d76bcb3d8e
11-18 16:48:22.398   929  2939 D WifiStateMachine: Start Dhcp Watchdog 2
11-18 16:48:22.398  5785  5803 D BtGatt.GattService: onClientRegistered() - UUID=e86d56ff-fafe-434b-8585-03d76bcb3d8e, clientIf=5
11-18 16:48:22.398  5591  5601 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
11-18 16:48:22.399  5785  5823 D BtGatt.GattService: start scan with filters
,11-18 16:48:22.403  5591  5638 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
,11-18 16:48:22.403  5591  5638 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-18 16:48:22.404  5591  5638 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
11-18 16:48:22.404  5785  5806 D BtGatt.ScanManager: handling starting scan
11-18 16:48:22.404  5591  5638 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-61,5,main], id: 61
11-18 16:48:22.404  5591  5638 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-18 16:48:22.404  5591  5591 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
,11-18 16:48:22.404  5591  5591 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-18 16:48:22.404  5591  5591 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
11-18 16:48:22.405  5591  5591 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-18 16:48:22.405  5591  5591 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-18 16:48:22.405  5591  5591 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
11-18 16:48:22.405  5591  5591 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
11-18 16:48:22.405  5785  5806 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1677a00
11-18 16:48:22.406  5591  5638 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-18 16:48:22.406  5591  5638 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-18 16:48:22.408  5591  5638 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-18 16:48:22.408  5591  5638 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
11-18 16:48:22.408  5591  5638 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-18 16:48:22.408  5591  5638 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-18 16:48:22.409  5591  5591 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
,11-18 16:48:22.409   929  5928 D DhcpClient: Receive thread started
11-18 16:48:22.411  5785  5803 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
11-18 16:48:22.412  5785  5803 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-18 16:48:22.412  5591  5591 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-18 16:48:22.412  5591  5591 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-18 16:48:22.412  5591  5591 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-18 16:48:22.412  5591  5591 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-18 16:48:22.412  5591  5591 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
11-18 16:48:22.412  5785  5806 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,11-18 16:48:22.414   929  2939 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
11-18 16:48:22.414   929  2941 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
11-18 16:48:22.414   929  2941 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
11-18 16:48:22.419  5785  5803 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
,11-18 16:48:22.419  5785  5803 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-18 16:48:22.419  5785  5806 D BtGatt.ScanManager: Starting BLE batch scan
11-18 16:48:22.419  5785  5806 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,11-18 16:48:22.430  5785  5803 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,11-18 16:48:22.430  5785  5803 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-18 16:48:22.434  5785  5803 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,11-18 16:48:22.434  5785  5803 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-18 16:48:22.494   929  2939 E native  : do suspend false
,11-18 16:48:22.501   929  5927 D DhcpClient: Broadcasting DHCPDISCOVER
,11-18 16:48:22.513   929  5928 D DhcpClient: Received packet: 60:83:34:25:d7:70 OFFER, ip /192.168.1.109, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172731, domain null
,11-18 16:48:22.514   929  5927 D DhcpClient: Got pending lease: IP address 192.168.1.109/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172731 seconds
,11-18 16:48:22.514   929  5927 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.109 serverid=192.168.1.1
,11-18 16:48:22.535   929  5928 D DhcpClient: Received packet: 60:83:34:25:d7:70 ACK: your new IP /192.168.1.109, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,11-18 16:48:22.535   929  5927 D DhcpClient: Confirmed lease: IP address 192.168.1.109/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
11-18 16:48:22.537   509   928 D CommandListener: Setting iface cfg
,11-18 16:48:22.539   929  2939 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,11-18 16:48:22.541   929  5927 D DhcpClient: Scheduling renewal in 86399s
,11-18 16:48:22.547   929  2939 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,11-18 16:48:22.548   929  2939 D WifiConfigStore: No blacklist allowed without epno enabled
11-18 16:48:22.548   929  2941 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,11-18 16:48:22.550   929  2941 D ConnectivityService: Adding iface wlan0 to network 101
11-18 16:48:22.554   929  2939 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,11-18 16:48:22.581   929  2941 E ConnectivityService: Unexpected mtu value: 0, wlan0
,11-18 16:48:22.581   929  2941 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
,11-18 16:48:22.585   929  2941 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,11-18 16:48:22.586   929  2941 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,11-18 16:48:22.588   929  2941 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,11-18 16:48:22.593   929  2941 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-18 16:48:22.597   929  2941 D ConnectivityService: scheduleUnvalidatedPrompt 101
,11-18 16:48:22.598   929  2941 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
11-18 16:48:22.598   929  2941 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
11-18 16:48:22.598   929  2939 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
11-18 16:48:22.598   929  2941 D ConnectivityService:    accepting network in place of null
11-18 16:48:22.598   929  2939 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
11-18 16:48:22.598   929  2941 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d770/64,192.168.1.109/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -57]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,11-18 16:48:22.607   929  5926 D NetlinkSocketObserver: NeighborEvent{elapsedMs=110547, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,11-18 16:48:22.617   509   928 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-18 16:48:22.636   509   928 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-18 16:48:22.638   929  2941 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
11-18 16:48:22.638   929  2941 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
11-18 16:48:22.638  3718  3837 W QCNEJ   : |CORE| network available: 101
,11-18 16:48:22.639   929  2941 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
11-18 16:48:22.640   929   946 D Tethering: MasterInitialState.processMessage what=3
,11-18 16:48:22.644  3718  3837 W QCNEJ   : |CORE| onAvailable: bind the process to WIFI
,11-18 16:48:22.645  3718  3837 W QCNEJ   : |CORE| newLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d770/64,192.168.1.109/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}
11-18 16:48:22.645  3718  3837 W QCNEJ   : |CORE| curLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d770/64,192.168.1.109/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,11-18 16:48:22.655  5036  5059 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
,11-18 16:48:22.655  5036  5059 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
11-18 16:48:22.655  5036  5059 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,1,0,0
11-18 16:48:22.655  5036  5059 E SarControlService: no key has been found,reset the power
11-18 16:48:22.655  5036  5073 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
11-18 16:48:22.655  5036  5073 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
11-18 16:48:22.655  5036  5073 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
11-18 16:48:22.656  5061  5061 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
,11-18 16:48:22.656  5061  5061 D QcrilMsgTunnelSocket: [1004] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
,11-18 16:48:22.657  5036  5073 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
11-18 16:48:22.657  5036  5073 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
11-18 16:48:22.657  5036  5073 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
11-18 16:48:22.658  5061  5061 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
11-18 16:48:22.658  5061  5061 D QcrilMsgTunnelSocket: [1005] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
11-18 16:48:22.658  3955  3955 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
11-18 16:48:22.661  3937  3937 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
11-18 16:48:22.664  5061  5075 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@465030b HexData = [00000000ec03000000000000ffffffff]
11-18 16:48:22.664  5061  5075 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-18 16:48:22.664  5061  5075 D QcrilMsgTunnelSocket: [1004] < OEM_HOOK_RAW [null]
11-18 16:48:22.664  5061  5075 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@465030b HexData = [00000000ed03000000000000ffffffff]
,11-18 16:48:22.664  5061  5075 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-18 16:48:22.664  5061  5075 D QcrilMsgTunnelSocket: [1005] < OEM_HOOK_RAW [null]
11-18 16:48:22.665  5061  5061 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
11-18 16:48:22.665  5036  5046 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
11-18 16:48:22.666  5061  5061 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
11-18 16:48:22.667  5036  5047 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
11-18 16:48:22.667  3937  3937 D SystemUpdateService: onCreate
,11-18 16:48:22.670  3937  3937 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,11-18 16:48:22.680  3937  3937 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,11-18 16:48:22.685  3937  5939 I SystemUpdateService: active receiver: enabled
,11-18 16:48:22.687  3937  5390 I iu.UploadsManager: num queued entries: 0
,11-18 16:48:22.687  3937  5390 I iu.UploadsManager: num updated entries: 0
11-18 16:48:22.687  3937  5390 I iu.SyncManager: NEXT; no task
,11-18 16:48:22.689   929  5924 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.214.238,2a00:1450:400d:803::200e
,11-18 16:48:22.691  3937  3937 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,11-18 16:48:22.692  3937  3937 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,11-18 16:48:22.694  5865  5865 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,11-18 16:48:22.698  5865  5865 D SprintDMHelper: simOperator: 
,11-18 16:48:22.698  5865  5865 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,11-18 16:48:22.719  3937  5939 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,11-18 16:48:22.734  3937  5939 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,11-18 16:48:22.734  3937  5939 I SystemUpdateService: now status is 0 (complete)
11-18 16:48:22.734  3937  5939 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
11-18 16:48:22.734  3937  5939 I SystemUpdateService: file has been verified
11-18 16:48:22.735  3937  5939 I SystemUpdateService: OTA package size = 21989297
,11-18 16:48:22.740  3937  5939 I SystemUpdateService: showing system update notification
,11-18 16:48:22.745   929  5924 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Fri, 18 Nov 2016 15:48:22 GMT], X-Android-Received-Millis=[1479484102744], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1479484102712]}
,11-18 16:48:22.745   929  2941 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,11-18 16:48:22.745   929  2941 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation  passed
,11-18 16:48:22.746   929  2941 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
11-18 16:48:22.747   929  2941 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,11-18 16:48:22.749   929   929 V NotificationService: pkg=com.google.android.gms canInterrupt=false intercept=true
,11-18 16:48:22.750  3937  3937 D SystemUpdateService: onDestroy
,11-18 16:48:22.830  4972  5944 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,11-18 16:48:22.913  5591  5591 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,11-18 16:48:22.913  5591  5591 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
11-18 16:48:22.913  5591  5591 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,11-18 16:48:22.938  5785  5785 D BtGatt.ScanManager: awakened up at time 110879
,11-18 16:48:22.943  5785  5806 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-18 16:48:22.959  5785  5803 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,11-18 16:48:22.960  5785  5803 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-18 16:48:22.962  5591  5591 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: onBatchScanResults: results count  = 0. Current thread: Thread[main,5,main], id: 1
,11-18 16:48:23.466  5785  5785 D BtGatt.ScanManager: awakened up at time 111406
,11-18 16:48:23.468  5785  5806 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-18 16:48:23.496  5785  5803 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=2
,11-18 16:48:23.496  5785  5803 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-18 16:48:23.497  5785  5803 D BtGatt.GattService: current time is 111437978988
11-18 16:48:23.497  5785  5803 D BtGatt.GattService: Batch record : [116, -43, -111, -91, -20, -29, 1, -128, -80, 1, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 71, -122, -77, 84, 69, -12, 1, -128, -83, 0, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 0]
,11-18 16:48:23.503  5785  5803 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,11-18 16:48:23.505  5785  5803 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74]
,11-18 16:48:23.510  5591  5591 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: onBatchScanResults: results count  = 2. Current thread: Thread[main,5,main], id: 1
,11-18 16:48:23.510  5591  5591 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: onBatchScanResults. scan = ScanResult{mDevice=E3:EC:A5:91:D5:74, mScanRecord=ScanRecord [mAdvertiseFlags=6, mServiceUuids=null, mManufacturerSpecificData={76=[2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74]}, mServiceData={0000180a-0000-1000-8000-00805f9b34fb=[116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]}, mTxPowerLevel=-2147483648, mDeviceName=estimote], mRssi=-80, mTimestampNanos=111388872285}
,11-18 16:48:23.511  5591  5591 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: ScanResult{mDevice=E3:EC:A5:91:D5:74, mScanRecord=ScanRecord [mAdvertiseFlags=6, mServiceUuids=null, mManufacturerSpecificData={76=[2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74]}, mServiceData={0000180a-0000-1000-8000-00805f9b34fb=[116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]}, mTxPowerLevel=-2147483648, mDeviceName=estimote], mRssi=-80, mTimestampNanos=111388872285}
11-18 16:48:23.512  5591  5591 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: parsedAdvertisement: [UUID = null, bluetoothMacAddress = D5:91:A5:EC:E3:B6, provideBluetoothMacAddressRequestId = nullextra info = 116]
,11-18 16:48:23.512  5591  5591 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: parsedAdvertisement uuid mismatch
,11-18 16:48:23.513  5591  5591 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: onBatchScanResults. scan = ScanResult{mDevice=F4:45:54:B3:86:47, mScanRecord=ScanRecord [mAdvertiseFlags=6, mServiceUuids=null, mManufacturerSpecificData={76=[2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74]}, mServiceData={}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-83, mTimestampNanos=111438872285}
11-18 16:48:23.513  5591  5591 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: ScanResult{mDevice=F4:45:54:B3:86:47, mScanRecord=ScanRecord [mAdvertiseFlags=6, mServiceUuids=null, mManufacturerSpecificData={76=[2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74]}, mServiceData={}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-83, mTimestampNanos=111438872285}
,11-18 16:48:23.639   929  2941 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,11-18 16:48:25.411  5591  5638 I io.jxcore.node.StartStopOperationHandlerTest: Starting test: testExecuteStartOperation
,11-18 16:48:25.412  5591  5638 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 6
,11-18 16:48:25.412  5591  5638 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 5 -> 6
11-18 16:48:25.413  5591  5638 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-61,5,main], id: 61
11-18 16:48:25.413  5591  5638 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-61,5,main], id: 61
11-18 16:48:25.413  5591  5638 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-61,5,main], id: 61
11-18 16:48:25.414  5591  5638 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
11-18 16:48:25.414  5591  5638 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Manufacturer ID: 7413
11-18 16:48:25.414  5591  5638 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad length and type: 533
11-18 16:48:25.414  5591  5638 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad extra information: 6
11-18 16:48:25.414  5591  5638 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
11-18 16:48:25.414  5591  5638 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 2
11-18 16:48:25.414  5591  5638 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 3
11-18 16:48:25.414  5591  5638 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 2
11-18 16:48:25.414  5591  5638 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
11-18 16:48:25.414  5591  5638 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Current thread: Thread[Thread-61,5,main], id: 61
11-18 16:48:25.414  5591  5638 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 6
11-18 16:48:25.414  5591  5638 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: advertiserWasStarted false Current thread: Thread[Thread-61,5,main], id: 61
11-18 16:48:25.414  5591  5638 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-61,5,main], id: 61
11-18 16:48:25.414  5591  5638 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-18 16:48:25.415  5591  5638 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-18 16:48:25.415  5591  5638 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: scannerWasStarted true Current thread: Thread[Thread-61,5,main], id: 61
,11-18 16:48:25.415  5591  5638 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: stop scanner Current thread: Thread[Thread-61,5,main], id: 61
,11-18 16:48:25.415  5591  5638 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-61,5,main], id: 61
11-18 16:48:25.419  5591  5638 D BluetoothAdapter: STATE_ON
11-18 16:48:25.420  5785  5830 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
11-18 16:48:25.420  5591  5638 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-18 16:48:25.422  5591  5638 D BluetoothAdapter: STATE_ON
11-18 16:48:25.423  5785  5831 D BtGatt.GattService: stopScan() - queue size =1
11-18 16:48:25.425  5785  5795 D BtGatt.GattService: unregisterClient() - clientIf=5
11-18 16:48:25.425  5785  5806 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
11-18 16:48:25.426  5591  5638 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-18 16:48:25.426  5591  5638 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-18 16:48:25.426  5591  5638 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
11-18 16:48:25.427  5591  5638 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-61,5,main], id: 61
11-18 16:48:25.427  5591  5638 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-18 16:48:25.427  5591  5638 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: start scanner Current thread: Thread[Thread-61,5,main], id: 61
11-18 16:48:25.427  5591  5638 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-18 16:48:25.427  5591  5638 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
11-18 16:48:25.427  5591  5638 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
11-18 16:48:25.427  5591  5638 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
11-18 16:48:25.427  5591  5638 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
11-18 16:48:25.427  5591  5638 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-61,5,main], id: 61
11-18 16:48:25.428  5591  5638 D BluetoothAdapter: STATE_ON
11-18 16:48:25.430  5785  5785 D BtGatt.ScanManager: awakened up at time 113371
,11-18 16:48:25.433  5785  5796 D BtGatt.GattService: registerClient() - UUID=0ee9478e-3b5f-49af-ad01-965d33c71212
11-18 16:48:25.434  5785  5803 D BtGatt.GattService: onClientRegistered() - UUID=0ee9478e-3b5f-49af-ad01-965d33c71212, clientIf=5
11-18 16:48:25.434  5591  5601 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,11-18 16:48:25.435  5785  5830 D BtGatt.GattService: start scan with filters
,11-18 16:48:25.441  5591  5638 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
11-18 16:48:25.441  5591  5638 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-18 16:48:25.441   929  2941 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
11-18 16:48:25.441  5591  5638 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,11-18 16:48:25.441  5591  5638 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-61,5,main], id: 61
11-18 16:48:25.441  5591  5638 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: start scanner started = true Current thread: Thread[Thread-61,5,main], id: 61
11-18 16:48:25.441  5591  5591 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-18 16:48:25.441  5591  5638 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
11-18 16:48:25.441  5591  5591 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-18 16:48:25.442  5591  5591 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
11-18 16:48:25.442  5591  5638 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
11-18 16:48:25.442  5591  5638 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
11-18 16:48:25.442  5591  5591 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
,11-18 16:48:25.442  5591  5591 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-18 16:48:25.442  5591  5638 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-18 16:48:25.442  5591  5591 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-18 16:48:25.444  5785  5803 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
11-18 16:48:25.445  5785  5803 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-18 16:48:25.445  5785  5803 D BtGatt.GattService: current time is 113385925187
11-18 16:48:25.445  5785  5803 D BtGatt.GattService: Batch record : [37, -47, 14, -113, 116, -46, 1, -128, -88, 33, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 0]
11-18 16:48:25.445  5785  5803 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74]
11-18 16:48:25.446  5591  5591 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: onBatchScanResults: results count  = 1. Current thread: Thread[main,5,main], id: 1
11-18 16:48:25.446  5591  5638 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
11-18 16:48:25.446  5591  5591 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: onBatchScanResults. scan = ScanResult{mDevice=D2:74:8F:0E:D1:25, mScanRecord=ScanRecord [mAdvertiseFlags=6, mServiceUuids=null, mManufacturerSpecificData={76=[2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74]}, mServiceData={}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-88, mTimestampNanos=111736131386}
11-18 16:48:25.446  5591  5591 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: ScanResult{mDevice=D2:74:8F:0E:D1:25, mScanRecord=ScanRecord [mAdvertiseFlags=6, mServiceUuids=null, mManufacturerSpecificData={76=[2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74]}, mServiceData={}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-88, mTimestampNanos=111736131386}
,11-18 16:48:25.447  5591  5638 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,11-18 16:48:25.447  5591  5638 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
11-18 16:48:25.447  5591  5638 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
11-18 16:48:25.447  5591  5638 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
11-18 16:48:25.447  5591  5591 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
11-18 16:48:25.447  5591  5638 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: true
11-18 16:48:25.448  5591  5951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
11-18 16:48:25.448  5591  5638 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-18 16:48:25.448  5591  5638 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-18 16:48:25.449  5591  5951 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-18 16:48:25.446  5830  5830 W Binder_4: type=1400 audit(0.0:124): avc: denied { ioctl } for path="socket:[29616]" dev="sockfs" ino=29616 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-18 16:48:25.446  5830  5830 W Binder_4: type=1400 audit(0.0:125): avc: denied { ioctl } for path="socket:[29616]" dev="sockfs" ino=29616 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-18 16:48:25.451  5591  5951 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,11-18 16:48:25.453  5785  5803 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
11-18 16:48:25.453  5785  5803 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-18 16:48:25.454  5785  5806 D BtGatt.ScanManager: stopping BLe Batch
,11-18 16:48:25.454  5591  5638 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser : Current thread: Thread[Thread-61,5,main], id: 61
11-18 16:48:25.454  5591  5638 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
,11-18 16:48:25.454  5591  5638 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-61,5,main], id: 61
11-18 16:48:25.454  5591  5638 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
11-18 16:48:25.454  5591  5638 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: createAdvertiseDataToServiceData 
11-18 16:48:25.454  5591  5638 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-18 16:48:25.455  5591  5638 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 06 60 83 34 25 D7 D4
11-18 16:48:25.455  5591  5638 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[6, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-18 16:48:25.455  5591  5638 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: created AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[6, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-18 16:48:25.455  5591  5638 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: Current thread: Thread[Thread-61,5,main], id: 61
11-18 16:48:25.455  5591  5638 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: was started = false
11-18 16:48:25.455  5591  5638 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: advertiseData = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[6, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-18 16:48:25.455  5591  5638 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData finished: Current thread: Thread[Thread-61,5,main], id: 61
11-18 16:48:25.455  5591  5638 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
11-18 16:48:25.455  5591  5638 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... adv data = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[6, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]Current thread: Thread[Thread-61,5,main], id: 61
11-18 16:48:25.456  5591  5638 D BluetoothAdapter: STATE_ON
,11-18 16:48:25.459  5785  5830 D BtGatt.GattService: registerClient() - UUID=f301c931-0af8-4016-bfc4-2c84716a9638
11-18 16:48:25.459  5785  5803 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
11-18 16:48:25.459  5785  5803 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-18 16:48:25.459  5785  5806 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
11-18 16:48:25.460  5785  5803 D BtGatt.GattService: onClientRegistered() - UUID=f301c931-0af8-4016-bfc4-2c84716a9638, clientIf=6
11-18 16:48:25.460  5591  5601 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
11-18 16:48:25.461  5785  5805 D BtGatt.AdvertiseManager: message : 0
,11-18 16:48:25.464  5785  5805 D BtGatt.AdvertiseManager: starting multi advertising
11-18 16:48:25.465  5785  5803 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-18 16:48:25.465  5785  5803 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-18 16:48:25.467  5785  5806 D BtGatt.ScanManager: handling starting scan
,11-18 16:48:25.473  5785  5803 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0
,11-18 16:48:25.477  5785  5803 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,11-18 16:48:25.477  5785  5803 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-18 16:48:25.477  5785  5806 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,11-18 16:48:25.481  5785  5803 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0
,11-18 16:48:25.481  5591  5638 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment Current thread: Thread[Thread-61,5,main], id: 61
11-18 16:48:25.481  5591  5638 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTINGCurrent thread: Thread[Thread-61,5,main], id: 61
11-18 16:48:25.481  5591  5638 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
11-18 16:48:25.482  5591  5638 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged default (no call to listener). Current thread: Thread[Thread-61,5,main], id: 61
11-18 16:48:25.482  5591  5638 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-61,5,main], id: 61
11-18 16:48:25.482  5591  5638 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[Thread-61,5,main], id: 61
11-18 16:48:25.482  5591  5638 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[Thread-61,5,main], id: 61
11-18 16:48:25.482  5591  5638 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser started = true Current thread: Thread[Thread-61,5,main], id: 61
11-18 16:48:25.482  5591  5638 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser: advertiser is started. Current thread: Thread[Thread-61,5,main], id: 61
11-18 16:48:25.482  5591  5638 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-18 16:48:25.482  5591  5638 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-61,5,main], id: 61
11-18 16:48:25.482  5591  5638 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Already running
11-18 16:48:25.482  5591  5638 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser: adv = true, disc = true
11-18 16:48:25.482  5591  5638 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,11-18 16:48:25.483  5591  5638 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-18 16:48:25.484  5591  5638 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-18 16:48:25.485  5785  5803 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
11-18 16:48:25.485  5785  5803 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-18 16:48:25.486  5785  5806 D BtGatt.ScanManager: Starting BLE batch scan
,11-18 16:48:25.486  5785  5806 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
11-18 16:48:25.486  5591  5638 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-18 16:48:25.486  5591  5638 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-18 16:48:25.486  5591  5638 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-18 16:48:25.487  5591  5591 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
,11-18 16:48:25.487  5591  5591 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess : Current thread: Thread[main,5,main], id: 1
,11-18 16:48:25.487  5591  5591 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNINGCurrent thread: Thread[main,5,main], id: 1
11-18 16:48:25.487  5591  5591 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
11-18 16:48:25.487  5591  5591 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  true. Current thread: Thread[main,5,main], id: 1
11-18 16:48:25.487  5591  5591 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[main,5,main], id: 1
11-18 16:48:25.487  5591  5591 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-18 16:48:25.487  5591  5591 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-18 16:48:25.488  5591  5591 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING, ADVERTISING]
11-18 16:48:25.488  5591  5591 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
11-18 16:48:25.488  5591  5591 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
,11-18 16:48:25.488  5591  5591 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [SCANNING, ADVERTISING]Current thread: Thread[main,5,main], id: 1
11-18 16:48:25.488  5591  5591 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [SCANNING, ADVERTISING]
11-18 16:48:25.488  5591  5591 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-18 16:48:25.491  5591  5591 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-18 16:48:25.491  5591  5591 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: true
11-18 16:48:25.491  5591  5591 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-18 16:48:25.491  5591  5591 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
,11-18 16:48:25.491  5591  5591 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-18 16:48:25.491  5591  5591 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: true
,11-18 16:48:25.496  5785  5803 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,11-18 16:48:25.496  5785  5803 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-18 16:48:25.500  5785  5803 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,11-18 16:48:25.500  5785  5803 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-18 16:48:25.613   537   537 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,11-18 16:48:25.614   537   537 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,11-18 16:48:25.992  5591  5591 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: true
,11-18 16:48:25.992  5591  5591 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
11-18 16:48:25.993  5591  5591 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,11-18 16:48:28.490  5591  5638 I io.jxcore.node.StartStopOperationHandlerTest: Starting test: testConstructor
,11-18 16:48:28.491  5591  5638 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,11-18 16:48:28.491  5591  5638 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
,11-18 16:48:28.491  5591  5638 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
,11-18 16:48:28.491  5591  5638 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
,11-18 16:48:28.492  5591  5638 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-18 16:48:28.492  5591  5951 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
11-18 16:48:28.492  5591  5638 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
11-18 16:48:28.492  5591  5951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
11-18 16:48:28.492  5591  5638 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
11-18 16:48:28.492  5591  5951 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
11-18 16:48:28.493  5591  5638 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-18 16:48:28.493  5591  5591 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
11-18 16:48:28.493  5591  5638 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9e2a535 removed from the list
11-18 16:48:28.493  5591  5591 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
11-18 16:48:28.493  5591  5638 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-18 16:48:28.493  5591  5638 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-18 16:48:28.493  5591  5591 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-18 16:48:28.493  5591  5638 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
11-18 16:48:28.493  5591  5638 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-18 16:48:28.494  5591  5638 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
11-18 16:48:28.494  5591  5638 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-61,5,main], id: 61
11-18 16:48:28.494  5591  5638 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-18 16:48:28.494  5591  5638 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
11-18 16:48:28.495  5591  5638 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-61,5,main], id: 61
11-18 16:48:28.500  5591  5638 D BluetoothAdapter: STATE_ON
11-18 16:48:28.500  5785  5830 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
11-18 16:48:28.501  5591  5638 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-18 16:48:28.503  5591  5638 D BluetoothAdapter: STATE_ON
11-18 16:48:28.503  5785  5806 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
11-18 16:48:28.504  5785  5831 D BtGatt.GattService: stopScan() - queue size =1
,11-18 16:48:28.507  5785  5795 D BtGatt.GattService: unregisterClient() - clientIf=5
,11-18 16:48:28.508  5591  5638 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-18 16:48:28.508  5591  5638 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-18 16:48:28.508  5591  5638 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
11-18 16:48:28.508  5591  5638 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-61,5,main], id: 61
11-18 16:48:28.508  5591  5638 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-61,5,main], id: 61
11-18 16:48:28.508  5591  5638 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-61,5,main], id: 61
11-18 16:48:28.509  5591  5638 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
,11-18 16:48:28.509  5591  5638 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-61,5,main], id: 61
11-18 16:48:28.510  5785  5805 D BtGatt.AdvertiseManager: message : 1
11-18 16:48:28.511  5785  5785 D BtGatt.ScanManager: awakened up at time 116451
11-18 16:48:28.511  5785  5805 D BtGatt.AdvertiseManager: stop advertise for client 6
,11-18 16:48:28.524  5785  5803 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
,11-18 16:48:28.524  5785  5803 D BtGatt.GattService: Client app is not null!
11-18 16:48:28.526  5785  5823 D BtGatt.GattService: unregisterClient() - clientIf=6
11-18 16:48:28.526  5591  5638 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,11-18 16:48:28.526  5591  5638 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
,11-18 16:48:28.527  5591  5638 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
11-18 16:48:28.527  5591  5638 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  false. Current thread: Thread[Thread-61,5,main], id: 61
11-18 16:48:28.527  5591  5638 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-61,5,main], id: 61
,11-18 16:48:28.527  5591  5638 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-61,5,main], id: 61
11-18 16:48:28.527  5591  5638 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-18 16:48:28.527  5591  5638 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-18 16:48:28.528  5591  5638 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
,11-18 16:48:28.529  5591  5638 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-18 16:48:28.530  5591  5638 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-18 16:48:28.530  5591  5638 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-18 16:48:28.530  5591  5638 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-18 16:48:28.530  5591  5638 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
,11-18 16:48:28.531  5591  5638 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fd4adca removed from the list
11-18 16:48:28.531  5591  5591 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-18 16:48:28.531  5591  5638 D io.jxcore.node.ConnectivityMonitor: stop
11-18 16:48:28.531  5591  5591 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,11-18 16:48:28.531  5591  5591 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-18 16:48:28.531  5591  5591 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-18 16:48:28.531  5591  5591 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-18 16:48:28.531  5591  5591 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING, ADVERTISING]
11-18 16:48:28.531  5591  5591 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
,11-18 16:48:28.531  5591  5591 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING, ADVERTISING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-18 16:48:28.531  5591  5591 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING, ADVERTISING] -> [NOT_STARTED]
11-18 16:48:28.531  5591  5591 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-18 16:48:28.532  5591  5638 I io.jxcore.node.StartStopOperationTest: Starting test: testIsTargetState
11-18 16:48:28.532  5591  5638 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
,11-18 16:48:28.532  5591  5638 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
11-18 16:48:28.533  5591  5638 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
,11-18 16:48:28.533  5591  5638 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-18 16:48:28.533  5591  5638 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
11-18 16:48:28.533  5591  5638 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
11-18 16:48:28.533  5591  5591 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
,11-18 16:48:28.533  5591  5591 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-18 16:48:28.533  5591  5591 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-18 16:48:28.533  5591  5591 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-18 16:48:28.533  5591  5591 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-18 16:48:28.533  5591  5591 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-18 16:48:28.534  5591  5591 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-18 16:48:28.534  5591  5638 I io.jxcore.node.StartStopOperationTest: Starting test: testCreateStartOperation
11-18 16:48:28.534  5591  5591 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
,11-18 16:48:28.534  5591  5591 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-18 16:48:28.534  5591  5591 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-18 16:48:28.534  5591  5591 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-18 16:48:28.535  5591  5638 I io.jxcore.node.StartStopOperationTest: Starting test: testGetShouldStartOrStopListeningToAdvertisementsOnly
11-18 16:48:28.536  5591  5638 I io.jxcore.node.StartStopOperationTest: Starting test: testIsStartOperation
11-18 16:48:28.537  5591  5638 I io.jxcore.node.StartStopOperationTest: Starting test: testToString
11-18 16:48:28.537  5591  5638 I io.jxcore.node.StartStopOperationTest: Starting test: testCreateStopOperation
11-18 16:48:28.538  5591  5638 I io.jxcore.node.StartStopOperationTest: Starting test: testSetOperationExecutedTime
11-18 16:48:28.539  5591  5638 I io.jxcore.node.StartStopOperationTest: Starting test: testGetOperationExecutedTime
,11-18 16:48:28.540  5591  5638 I io.jxcore.node.StartStopOperationTest: Starting test: testGetCallback
,11-18 16:48:28.552  5785  5803 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=5
,11-18 16:48:28.552  5785  5803 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-18 16:48:28.552  5785  5803 D BtGatt.GattService: current time is 116493463465
11-18 16:48:28.553  5785  5803 D BtGatt.GattService: Batch record : [-46, -4, -117, 6, 105, -37, 1, -128, -95, 4, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 116, -43, -111, -91, -20, -29, 1, -128, -83, 5, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 35, 97, 126, -92, 22, -56, 1, -128, -93, 26, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 81, 34, 97, 112, -14, -5, 1, -128, -82, 16, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 37, -47, 14, -113, 116, -46, 1, -128, -89, 15, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
11-18 16:48:28.553  5785  5803 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
11-18 16:48:28.553  5785  5803 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
11-18 16:48:28.553  5785  5803 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
11-18 16:48:28.553  5785  5803 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
,11-18 16:48:28.553  5785  5803 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
11-18 16:48:28.553  5785  5803 E BtGatt.ContextMap: Context not found for ID 5
,11-18 16:48:28.559  5785  5803 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
11-18 16:48:28.559  5785  5803 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-18 16:48:28.559  5785  5806 D BtGatt.ScanManager: stopping BLe Batch
,11-18 16:48:28.564  5785  5803 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,11-18 16:48:28.564  5785  5803 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-18 16:48:28.565  5785  5806 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-18 16:48:28.570  5785  5803 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-18 16:48:28.570  5785  5803 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-18 16:48:29.035  5591  5591 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-18 16:48:30.544  5591  5638 I StreamCopyingThreadTest: Starting test: testCopyDataAndCloseConnection
,11-18 16:48:30.602   929  2941 D ConnectivityService: handlePromptUnvalidated 101
,11-18 16:48:30.614   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-18 16:48:30.703  5591  5954 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 155, name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
11-18 16:48:30.703  5591  5954 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-18 16:48:31.508  5591  5954 W !!      : call onHalfStreamCopied
,11-18 16:48:31.508  5591  5954 I testCopyDataAndClose: closing input stream
,11-18 16:48:31.615   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-18 16:48:32.289  5591  5954 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 155, thread name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
11-18 16:48:32.289  5591  5954 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-18 16:48:32.289  5591  5954 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
11-18 16:48:32.289  5591  5954 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-18 16:48:32.290  5591  5954 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
,11-18 16:48:32.290  5591  5954 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
,11-18 16:48:32.290  5591  5954 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
,11-18 16:48:32.290  5591  5954 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
,11-18 16:48:32.290  5591  5954 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
11-18 16:48:32.290  5591  5954 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 155, name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
11-18 16:48:32.290  5591  5954 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 20971520 and the total number of bytes written 20971520
,11-18 16:48:32.616   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-18 16:48:33.464   929  2939 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 7, 9 -> obsolete
,11-18 16:48:33.616   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-18 16:48:33.634   929  2939 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 8, 9 -> obsolete
,11-18 16:48:34.617   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-18 16:48:35.618   537   537 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,11-18 16:48:36.471  5591  5638 I StreamCopyingThreadTest: Starting test: testRun
,11-18 16:48:36.477  5591  5955 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 158, name: My test thread name). Connection data: Peer properties: [null null].
11-18 16:48:36.477  5591  5955 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-18 16:48:40.620   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-18 16:48:41.485  5591  5956 E StreamCopyingThreadTest: StreamCopyingThread didn't close after 5s!
,11-18 16:48:41.487  5591  5638 I StreamCopyingThreadTest: Starting test: testCopyBigData
,11-18 16:48:41.620   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-18 16:48:41.637  5591  5957 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 161, name: testCopyBigData thread). Connection data: Peer properties: [null null].
11-18 16:48:41.637  5591  5957 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-18 16:48:42.622   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-18 16:48:43.267  5591  5957 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 161, thread name: testCopyBigData thread). Connection data: Peer properties: [null null].
11-18 16:48:43.267  5591  5957 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
11-18 16:48:43.267  5591  5957 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
11-18 16:48:43.267  5591  5957 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-18 16:48:43.267  5591  5957 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
11-18 16:48:43.267  5591  5957 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
11-18 16:48:43.267  5591  5957 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
11-18 16:48:43.267  5591  5957 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
11-18 16:48:43.267  5591  5957 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
11-18 16:48:43.267  5591  5957 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 161, name: testCopyBigData thread). Connection data: Peer properties: [null null].
11-18 16:48:43.267  5591  5957 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 20971520 and the total number of bytes written 20971520
,11-18 16:48:43.623   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-18 16:48:44.624   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-18 16:48:45.625   537   537 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,11-18 16:48:47.177  3645  3822 I Keyboard.Facilitator.LanguageModelFlusher: run()
,11-18 16:48:47.177  3645  3822 I Keyboard.Facilitator: flushDynamicLanguageModels()
,11-18 16:48:47.209  3569  3569 I ConfigService: onCreate
,11-18 16:48:47.442  5591  5638 I StreamCopyingThreadTest: Starting test: testRunNotify
,11-18 16:48:47.444  5591  5959 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 163, name: My test thread name). Connection data: Peer properties: [null null].
11-18 16:48:47.444  5591  5959 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-18 16:48:47.445  5591  5959 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 163, thread name: My test thread name). Connection data: Peer properties: [null null].
11-18 16:48:47.445  5591  5959 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
11-18 16:48:47.445  5591  5959 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
11-18 16:48:47.445  5591  5959 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
11-18 16:48:47.445  5591  5959 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
11-18 16:48:47.445  5591  5959 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
11-18 16:48:47.446  5591  5959 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
,11-18 16:48:47.446  5591  5959 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
11-18 16:48:47.446  5591  5959 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
11-18 16:48:47.446  5591  5959 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 163, name: My test thread name). Connection data: Peer properties: [null null].
11-18 16:48:47.446  5591  5959 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 22
,11-18 16:48:47.448  5591  5638 I StreamCopyingThreadTest: Starting test: testSetBufferSize
11-18 16:48:47.448  5591  5638 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,11-18 16:48:47.449  5591  5638 I StreamCopyingThreadTest: Starting test: testRunWithException
,11-18 16:48:47.451  5591  5960 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 167, name: My test thread name). Connection data: Peer properties: [null null].
11-18 16:48:47.451  5591  5960 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-18 16:48:47.452  5591  5960 E io.jxcore.node.StreamCopyingThread: Failed to write to the output stream (thread ID: 167, thread name: My test thread name): Test exception.
11-18 16:48:47.452  5591  5960 D io.jxcore.node.StreamCopyingThread: onStreamCopyError (ID: 167, name: My test thread name). Connection data: Peer properties: [null null].
11-18 16:48:47.452  5591  5960 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
11-18 16:48:47.452  5591  5960 D io.jxcore.node.StreamCopyingThread: number of bytes read = 22
11-18 16:48:47.453  5591  5960 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 167, name: My test thread name). Connection data: Peer properties: [null null].
11-18 16:48:47.453  5591  5960 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
11-18 16:48:47.455  5591  5638 E com.test.thalitest.ThaliTestRunner: testConnect(io.jxcore.node.ConnectionHelperTest)
,11-18 16:48:47.455  5591  5638 E com.test.thalitest.ThaliTestRunner: 
11-18 16:48:47.455  5591  5638 E com.test.thalitest.ThaliTestRunner: Expected: is "We already have an outgoing connection to peer with ID 00:11:22:33:44:55"
11-18 16:48:47.455  5591  5638 E com.test.thalitest.ThaliTestRunner:      but: was "Already connect(ing/ed)"
11-18 16:48:47.456  5591  5638 E com.test.thalitest.ThaliTestRunner: java.lang.AssertionError: 
11-18 16:48:47.456  5591  5638 E com.test.thalitest.ThaliTestRunner: Expected: is "We already have an outgoing connection to peer with ID 00:11:22:33:44:55"
11-18 16:48:47.456  5591  5638 E com.test.thalitest.ThaliTestRunner:      but: was "Already connect(ing/ed)"
11-18 16:48:47.456  5591  5638 E com.test.thalitest.ThaliTestRunner: 	at org.hamcrest.MatcherAssert.assertThat(MatcherAssert.java:20)
11-18 16:48:47.456  5591  5638 E com.test.thalitest.ThaliTestRunner: 	at org.hamcrest.MatcherAssert.assertThat(MatcherAssert.java:8)
11-18 16:48:47.456  5591  5638 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.ConnectionHelperTest.testConnect(ConnectionHelperTest.java:551)
11-18 16:48:47.456  5591  5638 E com.test.thalitest.ThaliTestRunner: 	at java.lang.reflect.Method.invoke(Native Method)
11-18 16:48:47.456  5591  5638 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.model.FrameworkMethod$1.runReflectiveCall(FrameworkMethod.java:50)
11-18 16:48:47.456  5591  5638 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.model.ReflectiveCallable.run(ReflectiveCallable.java:12)
11-18 16:48:47.456  5591  5638 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.model.FrameworkMethod.invokeExplosively(FrameworkMethod.java:47)
11-18 16:48:47.456  5591  5638 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.InvokeMethod.evaluate(InvokeMethod.java:17)
11-18 16:48:47.456  5591  5638 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.RunBefores.evaluate(RunBefores.java:26)
11-18 16:48:47.456  5591  5638 E com.test.thalitest.ThaliTestRunner: 	at org.junit.rules.ExpectedException$ExpectedExceptionStatement.evaluate(ExpectedException.java:239)
11-18 16:48:47.456  5591  5638 E com.test.thalitest.ThaliTestRunner: 	at org.junit.rules.TestWatcher$1.evaluate(TestWatcher.java:55)
11-18 16:48:47.456  5591  5638 E com.test.thalitest.ThaliTestRunner: 	at org.junit.rules.RunRules.evaluate(RunRules.java:20)
11-18 16:48:47.456  5591  5638 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runLeaf(ParentRunner.java:325)
11-18 16:48:47.456  5591  5638 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.BlockJUnit4ClassRunner.runChild(BlockJUnit4ClassRunner.java:78)
11-18 16:48:47.456  5591  5638 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.BlockJUnit4ClassRunner.runChild(BlockJUnit4ClassRunner.java:57)
11-18 16:48:47.456  5591  5638 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$3.run(ParentRunner.java:290)
11-18 16:48:47.456  5591  5638 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$1.schedule(ParentRunner.java:71)
11-18 16:48:47.456  5591  5638 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runChildren(ParentRunner.java:288)
11-18 16:48:47.456  5591  5638 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.access$000(ParentRunner.java:58)
11-18 16:48:47.456  5591  5638 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$2.evaluate(ParentRunner.java:268)
11-18 16:48:47.456  5591  5638 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.RunBefores.evaluate(RunBefores.java:26)
11-18 16:48:47.456  5591  5638 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.RunAfters.evaluate(RunAfters.java:27)
11-18 16:48:47.456  5591  5638 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.run(ParentRunner.java:363)
11-18 16:48:47.456  5591  5638 E com.test.thalitest.ThaliTestRun,ner: 	at org.junit.runners.Suite.runChild(Suite.java:128)
11-18 16:48:47.456  5591  5638 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:27)
11-18 16:48:47.456  5591  5638 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$3.run(ParentRunner.java:290)
11-18 16:48:47.456  5591  5638 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$1.schedule(ParentRunner.java:71)
11-18 16:48:47.456  5591  5638 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runChildren(ParentRunner.java:288)
11-18 16:48:47.456  5591  5638 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.access$000(ParentRunner.java:58)
11-18 16:48:47.456  5591  5638 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$2.evaluate(ParentRunner.java:268)
11-18 16:48:47.456  5591  5638 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.run(ParentRunner.java:363)
11-18 16:48:47.456  5591  5638 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:128)
11-18 16:48:47.456  5591  5638 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:27)
11-18 16:48:47.456  5591  5638 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$3.run(ParentRunner.java:290)
11-18 16:48:47.456  5591  5638 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$1.schedule(ParentRunner.java:71)
11-18 16:48:47.456  5591  5638 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runChildren(ParentRunner.java:288)
11-18 16:48:47.456  5591  5638 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.access$000(ParentRunner.java:58)
11-18 16:48:47.456  5591  5638 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$2.evaluate(ParentRunner.java:268)
11-18 16:48:47.456  5591  5638 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.run(ParentRunner.java:363)
11-18 16:48:47.456  5591  5638 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.run(JUnitCore.java:137)
11-18 16:48:47.456  5591  5638 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.run(JUnitCore.java:115)
11-18 16:48:47.456  5591  5638 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.run(JUnitCore.java:105)
11-18 16:48:47.456  5591  5638 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.runClasses(JUnitCore.java:62)
11-18 16:48:47.456  5591  5638 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.runClasses(JUnitCore.java:49)
11-18 16:48:47.456  5591  5638 E com.test.thalitest.ThaliTestRunner: 	at com.test.thalitest.ThaliTestRunner.runTests(ThaliTestRunner.java:86)
11-18 16:48:47.456  5591  5638 E com.test.thalitest.ThaliTestRunner: 	at com.test.thalitest.RegisterExecuteUT$2.Receiver(RegisterExecuteUT.java:75)
11-18 16:48:47.456  5591  5638 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.jxcore.javaCall(jxcore.java:139)
11-18 16:48:47.456  5591  5638 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.jxcore.evalEngine(Native Method)
11-18 16:48:47.456  5591  5638 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.jxcore$4.run(jxcore.java:226)
11-18 16:48:47.456  5591  5638 E com.test.thalitest.ThaliTestRunner: 	at android.os.Handler.handleCallback(Handler.java:739)
11-18 16:48:47.456  5591  5638 E com.test.thalitest.ThaliTestRunner: 	at android.os.Handler.dispatchMessage(Handler.java:95)
11-18 16:48:47.456  5591  5638 E com.test.thalitest.ThaliTestRunner: 	at android.os.Looper.loop(Looper.java:148)
11-18 16:48:47.456  5591  5638 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.CoreThread.run(CoreRunnable.java:56)
11-18 16:48:47.456  5591  5638 E com.test.thalitest.ThaliTestRunner: testStartStop(io.jxcore.node.ConnectivityMonitorTest)
11-18 16:48:47.456  5591  5638 E com.test.thalitest.ThaliTestRunner: The BT listener was bound
11-18 16:48:47.456  5591,  5638 E com.test.thalitest.ThaliTestRunner: Expected: is <true>
11-18 16:48:47.456  5591  5638 E com.test.thalitest.ThaliTestRunner:      but: was <false>
11-18 16:48:47.457  5591  5638 E com.test.thalitest.ThaliTestRunner: java.lang.AssertionError: The BT listener was bound
11-18 16:48:47.457  5591  5638 E com.test.thalitest.ThaliTestRunner: Expected: is <true>
11-18 16:48:47.457  5591  5638 E com.test.thalitest.ThaliTestRunner:      but: was <false>
11-18 16:48:47.457  5591  5638 E com.test.thalitest.ThaliTestRunner: 	at org.hamcrest.MatcherAssert.assertThat(MatcherAssert.java:20)
11-18 16:48:47.457  5591  5638 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.ConnectivityMonitorTest.testStartStop(ConnectivityMonitorTest.java:216)
11-18 16:48:47.457  5591  5638 E com.test.thalitest.ThaliTestRunner: 	at java.lang.reflect.Method.invoke(Native Method)
11-18 16:48:47.457  5591  5638 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.model.FrameworkMethod$1.runReflectiveCall(FrameworkMethod.java:50)
11-18 16:48:47.457  5591  5638 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.model.ReflectiveCallable.run(ReflectiveCallable.java:12)
11-18 16:48:47.457  5591  5638 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.model.FrameworkMethod.invokeExplosively(FrameworkMethod.java:47)
11-18 16:48:47.457  5591  5638 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.InvokeMethod.evaluate(InvokeMethod.java:17)
11-18 16:48:47.457  5591  5638 E com.test.thalitest.ThaliTestRunner: 	at org.junit.rules.ExpectedException$ExpectedExceptionStatement.evaluate(ExpectedException.java:239)
11-18 16:48:47.457  5591  5638 E com.test.thalitest.ThaliTestRunner: 	at org.junit.rules.TestWatcher$1.evaluate(TestWatcher.java:55)
11-18 16:48:47.457  5591  5638 E com.test.thalitest.ThaliTestRunner: 	at org.junit.rules.RunRules.evaluate(RunRules.java:20)
11-18 16:48:47.457  5591  5638 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runLeaf(ParentRunner.java:325)
11-18 16:48:47.457  5591  5638 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.BlockJUnit4ClassRunner.runChild(BlockJUnit4ClassRunner.java:78)
11-18 16:48:47.457  5591  5638 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.BlockJUnit4ClassRunner.runChild(BlockJUnit4ClassRunner.java:57)
11-18 16:48:47.457  5591  5638 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$3.run(ParentRunner.java:290)
11-18 16:48:47.457  5591  5638 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$1.schedule(ParentRunner.java:71)
11-18 16:48:47.457  5591  5638 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runChildren(ParentRunner.java:288)
11-18 16:48:47.457  5591  5638 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.access$000(ParentRunner.java:58)
11-18 16:48:47.457  5591  5638 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$2.evaluate(ParentRunner.java:268)
11-18 16:48:47.457  5591  5638 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.RunBefores.evaluate(RunBefores.java:26)
11-18 16:48:47.457  5591  5638 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.RunAfters.evaluate(RunAfters.java:27)
11-18 16:48:47.457  5591  5638 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.run(ParentRunner.java:363)
11-18 16:48:47.457  5591  5638 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:128)
11-18 16:48:47.457  5591  5638 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:27)
11-18 16:48:47.457  5591  5638 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$3.run(ParentRunner.java:290)
11-18 16:48:47.457  5591  5638 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$1.schedule(ParentRunner.java:71)
11-18 16:48:47.457  5591  5638 E com.test.thalitest.ThaliTestRunner,: 	at org.junit.runners.ParentRunner.runChildren(ParentRunner.java:288)
11-18 16:48:47.457  5591  5638 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.access$000(ParentRunner.java:58)
11-18 16:48:47.457  5591  5638 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$2.evaluate(ParentRunner.java:268)
11-18 16:48:47.457  5591  5638 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.run(ParentRunner.java:363)
11-18 16:48:47.457  5591  5638 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:128)
11-18 16:48:47.457  5591  5638 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:27)
11-18 16:48:47.457  5591  5638 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$3.run(ParentRunner.java:290)
11-18 16:48:47.457  5591  5638 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$1.schedule(ParentRunner.java:71)
11-18 16:48:47.457  5591  5638 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runChildren(ParentRunner.java:288)
11-18 16:48:47.457  5591  5638 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.access$000(ParentRunner.java:58)
11-18 16:48:47.457  5591  5638 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$2.evaluate(ParentRunner.java:268)
11-18 16:48:47.457  5591  5638 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.run(ParentRunner.java:363)
11-18 16:48:47.457  5591  5638 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.run(JUnitCore.java:137)
11-18 16:48:47.457  5591  5638 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.run(JUnitCore.java:115)
11-18 16:48:47.457  5591  5638 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.run(JUnitCore.java:105)
11-18 16:48:47.457  5591  5638 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.runClasses(JUnitCore.java:62)
11-18 16:48:47.457  5591  5638 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.runClasses(JUnitCore.java:49)
11-18 16:48:47.457  5591  5638 E com.test.thalitest.ThaliTestRunner: 	at com.test.thalitest.ThaliTestRunner.runTests(ThaliTestRunner.java:86)
11-18 16:48:47.457  5591  5638 E com.test.thalitest.ThaliTestRunner: 	at com.test.thalitest.RegisterExecuteUT$2.Receiver(RegisterExecuteUT.java:75)
11-18 16:48:47.457  5591  5638 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.jxcore.javaCall(jxcore.java:139)
11-18 16:48:47.457  5591  5638 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.jxcore.evalEngine(Native Method)
11-18 16:48:47.457  5591  5638 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.jxcore$4.run(jxcore.java:226)
11-18 16:48:47.457  5591  5638 E com.test.thalitest.ThaliTestRunner: 	at android.os.Handler.handleCallback(Handler.java:739)
11-18 16:48:47.457  5591  5638 E com.test.thalitest.ThaliTestRunner: 	at android.os.Handler.dispatchMessage(Handler.java:95)
11-18 16:48:47.457  5591  5638 E com.test.thalitest.ThaliTestRunner: 	at android.os.Looper.loop(Looper.java:148)
11-18 16:48:47.457  5591  5638 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.CoreThread.run(CoreRunnable.java:56)
11-18 16:48:47.457  5591  5638 E com.test.thalitest.ThaliTestRunner: testRun(io.jxcore.node.StreamCopyingThreadTest)
11-18 16:48:47.457  5591  5638 E com.test.thalitest.ThaliTestRunner: StreamCopyingThread should be closed
11-18 16:48:47.457  5591  5638 E com.test.thalitest.ThaliTestRunner: Expected: is <true>
11-18 16:48:47.457  5591  5638 E com.test.thalitest.ThaliTestRunner:      but: was <false>
11-18 16:48:47.458  5591  5638 E com.test.thalitest.ThaliTestRunner: java.lang.AssertionError: StreamCopyingThread should be closed
11-18 16:48:47.458  5591  5638 E com.test.thalitest.ThaliTestRunner: Expected: is <true>
11-18 16:48:47.458  5591  5638 E com.test.thalitest.ThaliTestRunner:      but: was <false>
11-18 16:48:47.458  5591  5638 E com.test.,thalitest.ThaliTestRunner: 	at org.hamcrest.MatcherAssert.assertThat(MatcherAssert.java:20)
11-18 16:48:47.458  5591  5638 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.StreamCopyingThreadTest.testRun(StreamCopyingThreadTest.java:152)
11-18 16:48:47.458  5591  5638 E com.test.thalitest.ThaliTestRunner: 	at java.lang.reflect.Method.invoke(Native Method)
11-18 16:48:47.458  5591  5638 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.model.FrameworkMethod$1.runReflectiveCall(FrameworkMethod.java:50)
11-18 16:48:47.458  5591  5638 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.model.ReflectiveCallable.run(ReflectiveCallable.java:12)
11-18 16:48:47.458  5591  5638 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.model.FrameworkMethod.invokeExplosively(FrameworkMethod.java:47)
11-18 16:48:47.458  5591  5638 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.InvokeMethod.evaluate(InvokeMethod.java:17)
11-18 16:48:47.458  5591  5638 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.RunBefores.evaluate(RunBefores.java:26)
11-18 16:48:47.458  5591  5638 E com.test.thalitest.ThaliTestRunner: 	at org.junit.rules.ExpectedException$ExpectedExceptionStatement.evaluate(ExpectedException.java:239)
11-18 16:48:47.458  5591  5638 E com.test.thalitest.ThaliTestRunner: 	at org.junit.rules.TestWatcher$1.evaluate(TestWatcher.java:55)
11-18 16:48:47.458  5591  5638 E com.test.thalitest.ThaliTestRunner: 	at org.junit.rules.RunRules.evaluate(RunRules.java:20)
11-18 16:48:47.458  5591  5638 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runLeaf(ParentRunner.java:325)
11-18 16:48:47.458  5591  5638 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.BlockJUnit4ClassRunner.runChild(BlockJUnit4ClassRunner.java:78)
11-18 16:48:47.458  5591  5638 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.BlockJUnit4ClassRunner.runChild(BlockJUnit4ClassRunner.java:57)
11-18 16:48:47.458  5591  5638 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$3.run(ParentRunner.java:290)
11-18 16:48:47.458  5591  5638 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$1.schedule(ParentRunner.java:71)
11-18 16:48:47.458  5591  5638 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runChildren(ParentRunner.java:288)
11-18 16:48:47.458  5591  5638 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.access$000(ParentRunner.java:58)
11-18 16:48:47.458  5591  5638 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$2.evaluate(ParentRunner.java:268)
11-18 16:48:47.458  5591  5638 E com.test.thalitest.ThaliTestRunner: 	,at org.junit.runners.ParentRunner.run(ParentRunner.java:363)
11-18 16:48:47.458  5591  5638 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:128)
11-18 16:48:47.458  5591  5638 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:27)
11-18 16:48:47.458  5591  5638 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$3.run(ParentRunner.java:290)
11-18 16:48:47.458  5591  5638 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$1.schedule(ParentRunner.java:71)
11-18 16:48:47.458  5591  5638 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runChildren(ParentRunner.java:288)
11-18 16:48:47.458  5591  5638 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.access$000(ParentRunner.java:58)
11-18 16:48:47.458  5591  5638 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$2.evaluate(ParentRunner.java:268)
11-18 16:48:47.458  5591  5638 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.run(ParentRunner.java:363)
11-18 16:48:47.458  5591  5638 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:128)
11-18 16:48:47.458  5591  5638 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:27)
11-18 16:48:47.458  5591  5638 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$3.run(ParentRunner.java:290)
11-18 16:48:47.458  5591  5638 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$1.schedule(ParentRunner.java:71)
11-18 16:48:47.458  5591  5638 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runChildren(ParentRunner.java:288)
11-18 16:48:47.458  5591  5638 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.access$000(ParentRunner.java:58)
11-18 16:48:47.458  5591  5638 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$2.evaluate(ParentRunner.java:268)
11-18 16:48:47.458  5591  5638 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.run(ParentRunner.java:363)
11-18 16:48:47.458  5591  5638 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.run(JUnitCore.java:137)
11-18 16:48:47.458  5591  5638 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.run(JUnitCore.java:115)
11-18 16:48:47.458  5591  5638 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.run(JUnitCore.java:105)
11-18 16:48:47.458  5591  5638 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.runClasses(JUnitCore.java:62)
11-18 16:48:47.458  5591  5638 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.runClasses(JUnitCore.java:49)
11-18 16:48:47.458  5591  5638 E com.test.thalitest.ThaliTestRunner: 	at com.test.thalitest.ThaliTestRunner.runTests(ThaliTestRunner.java:86)
11-18 16:48:47.458  5591  5638 E com.test.thalitest.ThaliTestRunner: 	at com.test.thalitest.RegisterExecuteUT$2.Receiver(RegisterExecuteUT.java:75)
11-18 16:48:47.458  5591  5638 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.jxcore.javaCall(jxcore.java:139)
11-18 16:48:47.458  5591  5638 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.jxcore.evalEngine(Native Method)
11-18 16:48:47.458  5591  5638 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.jxcore$4.run(jxcore.java:226)
11-18 16:48:47.458  5591  5638 E com.test.thalitest.ThaliTestRunner: 	at android.os.Handler.handleCallback(Handler.java:739)
11-18 16:48:47.458  5591  5638 E com.test.thalitest.ThaliTestRunner: 	at android.os.Handler.dispatchMessage(Handler.java:95)
11-18 16:48:47.458  5591  5638 E com.test.thalitest.ThaliTestRunner: 	at android.os.Looper.loop(Looper.java:148)
11-18 16:48:47.458  5591  5638 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.CoreThread.run(CoreRunnable.java:56)
11-18 16:48:47.468  5591  5638 I jxcore-log: 2016-11-18 15:48:47 - DEBUG UnitTest_app: 'Running unit tests'
11-18 16:,48:47.468  5591  5638 I jxcore-log: 
11-18 16:48:47.468  5591  5638 I jxcore-log: *Native tests were executed*
11-18 16:48:47.468  5591  5638 I jxcore-log: 
11-18 16:48:47.469  5591  5638 I jxcore-log: Total number of executed tests:  82
11-18 16:48:47.469  5591  5638 I jxcore-log: 
11-18 16:48:47.469  5591  5638 I jxcore-log: Number of passed tests:  79
11-18 16:48:47.469  5591  5638 I jxcore-log: 
11-18 16:48:47.469  5591  5638 I jxcore-log: Number of failed tests:  3
11-18 16:48:47.469  5591  5638 I jxcore-log: 
11-18 16:48:47.469  5591  5638 I jxcore-log: Number of ignored tests:  0
11-18 16:48:47.469  5591  5638 I jxcore-log: 
11-18 16:48:47.470  5591  5638 I jxcore-log: Total duration:  38732
11-18 16:48:47.470  5591  5638 I jxcore-log: 
11-18 16:48:47.471  5591  5638 I jxcore-log: Failed to execute UT.
11-18 16:48:47.471  5591  5638 I jxcore-log: 
11-18 16:48:47.473  5591  5638 I jxcore-log: 2016-11-18 15:48:47 - DEBUG UnitTest_app: 'Failed to execute UT.'
11-18 16:48:47.473  5591  5638 I jxcore-log: 
11-18 16:48:47.475  5591  5638 I jxcore-log: 2016-11-18 15:48:47 - DEBUG UnitTest_app: 'Unit Test app is loaded'
11-18 16:48:47.475  5591  5638 I jxcore-log: 
11-18 16:48:47.479  5591  5638 I jxcore-log: 2016-11-18 15:48:47 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
11-18 16:48:47.479  5591  5638 I jxcore-log: 
11-18 16:48:47.479  5591  5638 I jxcore-log: 2016-11-18 15:48:47 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-18 16:48:47.479  5591  5638 I jxcore-log: 
11-18 16:48:47.480  5591  5638 I jxcore-log: 2016-11-18 15:48:47 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
11-18 16:48:47.480  5591  5638 I jxcore-log: 
11-18 16:48:47.481  5591  5638 I jxcore-log: 2016-11-18 15:48:47 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-18 16:48:47.481  5591  5638 I jxcore-log: 
11-18 16:48:47.482  5591  5638 I jxcore-log: 2016-11-18 15:48:47 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
11-18 16:48:47.482  5591  5638 I jxcore-log: 
11-18 16:48:47.482  5591  5638 I jxcore-log: 2016-11-18 15:48:47 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH"})'
11-18 16:48:47.482  5591  5638 I jxcore-log: 
11-18 16:48:47.482  5591  5638 I jxcore-log: 2016-11-18 15:48:47 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-18 16:48:47.482  5591  5638 I jxcore-log: 
11-18 16:48:47.483  5591  5638 I jxcore-log: 2016-11-18 15:48:47 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
11-18 16:48:47.483  5591  5638 I jxcore-log: 
11-18 16:48:47.483  5591  5638 I jxcore-log: 2016-11-18 15:48:47 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH"})'
11-18 16:48:47.483  5591  5638 I jxcore-log: 
11-18 16:48:47.483  5591  5638 I jxcore-log: 2016-11-18 15:48:47 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-18 16:48:47.483  5591  5638 I jxcore-log: 
11-18 16:48:47.483  5591  5638 I jxcore-log: 2016-11-18 15:48:47 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
11-18 16:48:47.483  5591  5638 I jxcore-log: 
11-18 16:48:47.483  5591  5638 I jxcore-log: 2016-11-18 15:48:47 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH"})'
11-18 16:48:47.483  5591  5638 I jxcore-log: 
11-18 16:48:47.484  5591  5638 I jxcore-log: 2016-11-18 15:48:47 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-18 16:48:47.484  5591  5638 I jxcore-log: 
11-18 16:48:47.484  5591  5638 I jxcore-log: 2016-11-18 15:48:47 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-18 16:48:47.484  5591  5638 I jxcore-log: 
11-18 16:48:47.484  5591  5638 I jxcore-log: 2016-11-18 15:48:47 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-18 16:48:47.484  5591  5638 I jxcore-log: 
11-18 16:48:47.484  5591  5638 I jxcore-log: 2016-11-18 15:48:47 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
11-18 16:48:47.484  5591  5638 I jxcore-log: 
11-18 16:48:47.485  5591  5638 I jxcore-log: 2016-11-18 15:48:47 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-18 16:48:47.485  5591  5638 I jxcore-log: 
11-18 16:48:47.485  5591  5638 I jxcore-log: 2016-11-18 15:48:47 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-18 16:48:47.485  5591  5638 I jxcore-log: 
11-18 16:48:47.485  5591  5638 I jxcore-log: 2016-11-18 15:48:47 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-18 16:48:47.485  5591  5638 I jxcore-log: 
11-18 16:48:47.485  5591  5638 I jxcore-log: 2016-11-18 15:48:47 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
11-18 16:48:47.485  5591  5638 I jxcore-log: 
11-18 16:48:47.485  5591  5638 I jxcore-log: 2016-11-18 15:48:47 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-18 16:48:47.485  5591  5638 I jxcore-log: 
11-18 16:48:47.486  5591  5638 I jxcore-log: 2016-11-18 15:48:47 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
11-18 16:48:47.486  5591  5638 I jxcore-log: 
11-18 16:48:47.486  5591  5638 I jxcore-log: 2016-11-18 15:48:47 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-18 16:48:47.486  5591  5638 I jxcore-log: 
11-18 16:48:47.486  5591  5638 I jxcore-log: 2016-11-18 15:48:47 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
11-18 16:48:47.486  5591  5638 I jxcore-log: 
11-18 16:48:47.486  5591  5638 I jxcore-log: 2016-11-18 15:48:47 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-18 16:48:47.486  5591  5638 I jxcore-log: 
11-18 16:48:47.487  5591  5638 I jxcore-log: 2016-11-18 15:48:47 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
11-18 16:48:47.487  5591  5638 I jxcore-log: 
11-18 16:48:47.487  5591  5638 I jxcore-log: 2016-11-18 15:48:47 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-18 16:48:47.487  5591  5638 I jxcore-log: 
11-18 16:48:47.487  5591  5638 I jxcore-log: 2016-11-18 15:48:47 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
11-18 16:48:47.487  5591  5638 I jxcore-log: 
11-18 16:48:47.488  5591  5638 I jxcore-log: 2016-11-18 15:48:47 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH"})'
11-18 16:48:47.488  5591  5638 I jxcore-log: 
11-18 16:48:47.489  5591  5638 I jxcore-log: 2016-11-18 15:48:47 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-18 16:48:47.489  5591  5638 I jxcore-log: 
11-18 16:48:47.489  5591  5638 I jxcore-log: 2016-11-18 15:48:47 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
11-18 16:48:47.489  5591  5638 I jxcore-log: 
11-18 16:48:47.489  5591  5638 I jxcore-log: 2016-11-18 15:48:47 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH"})'
11-18 16:48:47.489  5591  5638 I jxcore-log: 
11-18 16:48:47.489  5591  5638 I jxcore-log: 2016-11-18 15:48:47 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-18 16:48:47.489  5591  5638 I jxcore-log: 
11-18 16:48:47.490  5591  5638 I jxcore-log: 2016-11-18 15:48:47 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
11-18 16:48:47.490  5591  5638 I jxcore-log: 
11-18 16:48:47.490  5591  5638 I jxcore-log: 2016-11-18 15:48:47 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH"})'
11-18 16:48:47.490  5591  5638 I jxcore-log: 
11-18 16:48:47.490  5591  5638 I jxcore-log: 2016-11-18 15:48:47 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-18 16:48:47.490  5591  5638 I jxcore-log: 
11-18 16:48:47.490  5591  5638 I jxcore-log: 2016-11-18 15:48:47 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-18 16:48:47.490  5591  5638 I jxcore-log: 
11-18 16:48:47.491  5591  5638 I jxcore-log: 2016-11-18 15:48:47 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-18 16:48:47.491  5591  5638 I jxcore-log: 
11-18 16:48:47.496  5591  5638 I jxcore-log: 2016-11-18 15:48:47 - DEBUG UnitTest_app: 'My device name is: Huawei-Nexus 6P'
11-18 16:48:47.496  5591  5638 I jxcore-log: 
11-18 16:48:47.496  5591  5638 I jxcore-log: 2016-11-18 15:48:47 - WARN testUtils: 'myNameCallback not set!'
11-18 16:48:47.496  5591  5638 I jxcore-log: 
11-18 16:48:47.496  5591  5591 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
,11-18 16:48:49.523  5591  5638 I jxcore-log: 2016-11-18 15:48:49 - INFO runTests: 'Starting tests. Network type: WIFI. Platform: android'
11-18 16:48:49.523  5591  5638 I jxcore-log: 
,11-18 16:48:49.525  5591  5638 I jxcore-log: 2016-11-18 15:48:49 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js'
11-18 16:48:49.525  5591  5638 I jxcore-log: 
,11-18 16:48:49.862  5591  5638 I jxcore-log: 2016-11-18 15:48:49 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js'
11-18 16:48:49.862  5591  5638 I jxcore-log: 
,11-18 16:48:49.875  5591  5638 I jxcore-log: 2016-11-18 15:48:49 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManager.js'
11-18 16:48:49.875  5591  5638 I jxcore-log: 
,11-18 16:48:50.977  5591  5638 I jxcore-log: 2016-11-18 15:48:50 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js'
11-18 16:48:50.977  5591  5638 I jxcore-log: 
,11-18 16:48:51.142  5591  5638 I jxcore-log: 2016-11-18 15:48:51 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js'
11-18 16:48:51.142  5591  5638 I jxcore-log: 
,11-18 16:48:51.148  5591  5638 I jxcore-log: 2016-11-18 15:48:51 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testNativeMethod.js'
11-18 16:48:51.148  5591  5638 I jxcore-log: 
,11-18 16:48:51.160  5591  5638 I jxcore-log: 2016-11-18 15:48:51 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPouchDBCheckpointPlugin.js'
11-18 16:48:51.160  5591  5638 I jxcore-log: 
,11-18 16:48:51.648  5591  5638 I jxcore-log: 2016-11-18 15:48:51 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPouchDBGenerator.js'
11-18 16:48:51.648  5591  5638 I jxcore-log: 
,11-18 16:48:51.692  5591  5638 I jxcore-log: 2016-11-18 15:48:51 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js'
11-18 16:48:51.692  5591  5638 I jxcore-log: 
,11-18 16:48:51.705  5591  5638 I jxcore-log: 2016-11-18 15:48:51 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js'
11-18 16:48:51.705  5591  5638 I jxcore-log: 
,11-18 16:48:51.709  5591  5638 I jxcore-log: 2016-11-18 15:48:51 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliManager.js'
11-18 16:48:51.709  5591  5638 I jxcore-log: 
,11-18 16:48:51.981  5591  5638 I jxcore-log: 2016-11-18 15:48:51 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliManagerCoordinated.js'
11-18 16:48:51.981  5591  5638 I jxcore-log: 
,11-18 16:48:52.106  5591  5638 I jxcore-log: 2016-11-18 15:48:52 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js'
11-18 16:48:52.106  5591  5638 I jxcore-log: 
,11-18 16:48:52.243  3569  3569 I ConfigService: onDestroy
,11-18 16:48:52.488  5591  5638 I jxcore-log: 2016-11-18 15:48:52 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js'
11-18 16:48:52.488  5591  5638 I jxcore-log: 
,11-18 16:48:52.495  5591  5638 I jxcore-log: 2016-11-18 15:48:52 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeAndroid.js'
11-18 16:48:52.495  5591  5638 I jxcore-log: 
,11-18 16:48:52.499  5591  5638 I jxcore-log: 2016-11-18 15:48:52 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeDiscoveryCoordinated.js'
11-18 16:48:52.499  5591  5638 I jxcore-log: 
,11-18 16:48:52.503  5591  5638 I jxcore-log: 2016-11-18 15:48:52 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js'
11-18 16:48:52.503  5591  5638 I jxcore-log: 
,11-18 16:48:52.509  5591  5638 I jxcore-log: 2016-11-18 15:48:52 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeiOS.js'
11-18 16:48:52.509  5591  5638 I jxcore-log: 
,11-18 16:48:52.549  5591  5638 I jxcore-log: 2016-11-18 15:48:52 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js'
11-18 16:48:52.549  5591  5638 I jxcore-log: 
,11-18 16:48:52.556  5591  5638 I jxcore-log: 2016-11-18 15:48:52 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js'
11-18 16:48:52.556  5591  5638 I jxcore-log: 
,11-18 16:48:52.586  5591  5638 I jxcore-log: 2016-11-18 15:48:52 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js'
11-18 16:48:52.586  5591  5638 I jxcore-log: 
,11-18 16:48:52.624  5591  5638 I jxcore-log: 2016-11-18 15:48:52 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js'
11-18 16:48:52.624  5591  5638 I jxcore-log: 
,11-18 16:48:52.631  5591  5638 I jxcore-log: 2016-11-18 15:48:52 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationLocal.js'
11-18 16:48:52.631  5591  5638 I jxcore-log: 
,11-18 16:48:52.638  5591  5638 I jxcore-log: 2016-11-18 15:48:52 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js'
11-18 16:48:52.638  5591  5638 I jxcore-log: 
,11-18 16:48:52.654  5591  5638 I jxcore-log: 2016-11-18 15:48:52 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js'
11-18 16:48:52.654  5591  5638 I jxcore-log: 
,11-18 16:48:52.669  5591  5638 I jxcore-log: 2016-11-18 15:48:52 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js'
11-18 16:48:52.669  5591  5638 I jxcore-log: 
,11-18 16:48:52.675  5591  5638 I jxcore-log: 2016-11-18 15:48:52 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolDefault.js'
11-18 16:48:52.675  5591  5638 I jxcore-log: 
,11-18 16:48:52.680  5591  5638 I jxcore-log: 2016-11-18 15:48:52 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js'
11-18 16:48:52.680  5591  5638 I jxcore-log: 
,11-18 16:48:52.694  5591  5638 I jxcore-log: 2016-11-18 15:48:52 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolOneAtATime.js'
11-18 16:48:52.694  5591  5638 I jxcore-log: 
,11-18 16:48:52.711  5591  5638 I jxcore-log: 2016-11-18 15:48:52 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js'
11-18 16:48:52.711  5591  5638 I jxcore-log: 
,11-18 16:48:52.726  5591  5638 I jxcore-log: 2016-11-18 15:48:52 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js'
11-18 16:48:52.726  5591  5638 I jxcore-log: 
,11-18 16:48:52.737  5591  5638 I jxcore-log: 2016-11-18 15:48:52 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerAction.js'
11-18 16:48:52.737  5591  5638 I jxcore-log: 
,11-18 16:48:52.750  5591  5638 I jxcore-log: 2016-11-18 15:48:52 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js'
11-18 16:48:52.750  5591  5638 I jxcore-log: 
,11-18 16:48:52.760  5591  5638 I jxcore-log: 2016-11-18 15:48:52 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js'
11-18 16:48:52.760  5591  5638 I jxcore-log: 
,11-18 16:48:52.773  5591  5638 I jxcore-log: 2016-11-18 15:48:52 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js'
11-18 16:48:52.773  5591  5638 I jxcore-log: 
,11-18 16:48:52.783  5591  5638 I jxcore-log: 2016-11-18 15:48:52 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js'
11-18 16:48:52.783  5591  5638 I jxcore-log: 
,11-18 16:48:52.790  5591  5638 I jxcore-log: 2016-11-18 15:48:52 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js'
11-18 16:48:52.790  5591  5638 I jxcore-log: 
,11-18 16:48:52.811  5591  5638 I jxcore-log: 2016-11-18 15:48:52 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testUsn.js'
11-18 16:48:52.811  5591  5638 I jxcore-log: 
,11-18 16:48:52.817  5591  5638 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: SUPPORTED
,11-18 16:48:52.818  5591  5638 I jxcore-log: 2016-11-18 15:48:52 - INFO testUtils: 'BLE multiple advertisement supported'
11-18 16:48:52.818  5591  5638 I jxcore-log: 
,11-18 16:48:52.893  5591  5638 I jxcore-log: 2016-11-18 15:48:52 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-18 16:48:52.893  5591  5638 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-18 16:48:52.893  5591  5638 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-18 16:48:52.893  5591  5638 I jxcore-log: emit@events.js:82:1
11-18 16:48:52.893  5591  5638 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-18 16:48:52.893  5591  5638 I jxcore-log: emit@events.js:82:1'
11-18 16:48:52.893  5591  5638 I jxcore-log: 
,11-18 16:48:53.175  5591  5638 I jxcore-log: 2016-11-18 15:48:53 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-18 16:48:53.175  5591  5638 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-18 16:48:53.175  5591  5638 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-18 16:48:53.175  5591  5638 I jxcore-log: emit@events.js:82:1
11-18 16:48:53.175  5591  5638 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-18 16:48:53.175  5591  5638 I jxcore-log: emit@events.js:82:1'
11-18 16:48:53.175  5591  5638 I jxcore-log: 
,11-18 16:48:53.178  5591  5638 I jxcore-log: 2016-11-18 15:48:53 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-18 16:48:53.178  5591  5638 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-18 16:48:53.178  5591  5638 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-18 16:48:53.178  5591  5638 I jxcore-log: emit@events.js:82:1
11-18 16:48:53.178  5591  5638 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-18 16:48:53.178  5591  5638 I jxcore-log: emit@events.js:82:1'
11-18 16:48:53.178  5591  5638 I jxcore-log: 
,11-18 16:48:53.606  5591  5638 I jxcore-log: 2016-11-18 15:48:53 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-18 16:48:53.606  5591  5638 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-18 16:48:53.606  5591  5638 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-18 16:48:53.606  5591  5638 I jxcore-log: emit@events.js:82:1
11-18 16:48:53.606  5591  5638 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-18 16:48:53.606  5591  5638 I jxcore-log: emit@events.js:82:1'
11-18 16:48:53.606  5591  5638 I jxcore-log: 
,11-18 16:48:53.610  5591  5638 I jxcore-log: 2016-11-18 15:48:53 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-18 16:48:53.610  5591  5638 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-18 16:48:53.610  5591  5638 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-18 16:48:53.610  5591  5638 I jxcore-log: emit@events.js:82:1
11-18 16:48:53.610  5591  5638 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-18 16:48:53.610  5591  5638 I jxcore-log: emit@events.js:82:1'
11-18 16:48:53.610  5591  5638 I jxcore-log: 
,11-18 16:48:54.095  5591  5638 I jxcore-log: 2016-11-18 15:48:54 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-18 16:48:54.095  5591  5638 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-18 16:48:54.095  5591  5638 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-18 16:48:54.095  5591  5638 I jxcore-log: emit@events.js:82:1
11-18 16:48:54.095  5591  5638 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-18 16:48:54.095  5591  5638 I jxcore-log: emit@events.js:82:1'
11-18 16:48:54.095  5591  5638 I jxcore-log: 
,11-18 16:48:54.097  5591  5638 I jxcore-log: 2016-11-18 15:48:54 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-18 16:48:54.097  5591  5638 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-18 16:48:54.097  5591  5638 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-18 16:48:54.097  5591  5638 I jxcore-log: emit@events.js:82:1
11-18 16:48:54.097  5591  5638 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-18 16:48:54.097  5591  5638 I jxcore-log: emit@events.js:82:1'
11-18 16:48:54.097  5591  5638 I jxcore-log: 
,11-18 16:48:55.133  5591  5638 I jxcore-log: 2016-11-18 15:48:55 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-18 16:48:55.133  5591  5638 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-18 16:48:55.133  5591  5638 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-18 16:48:55.133  5591  5638 I jxcore-log: emit@events.js:82:1
11-18 16:48:55.133  5591  5638 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-18 16:48:55.133  5591  5638 I jxcore-log: emit@events.js:82:1'
11-18 16:48:55.133  5591  5638 I jxcore-log: 
,11-18 16:48:55.139  5591  5638 I jxcore-log: 2016-11-18 15:48:55 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-18 16:48:55.139  5591  5638 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-18 16:48:55.139  5591  5638 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-18 16:48:55.139  5591  5638 I jxcore-log: emit@events.js:82:1
11-18 16:48:55.139  5591  5638 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-18 16:48:55.139  5591  5638 I jxcore-log: emit@events.js:82:1'
11-18 16:48:55.139  5591  5638 I jxcore-log: 
,11-18 16:48:55.626   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-18 16:48:56.179  5591  5638 I jxcore-log: 2016-11-18 15:48:56 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-18 16:48:56.179  5591  5638 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-18 16:48:56.179  5591  5638 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-18 16:48:56.179  5591  5638 I jxcore-log: emit@events.js:82:1
11-18 16:48:56.179  5591  5638 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-18 16:48:56.179  5591  5638 I jxcore-log: emit@events.js:82:1'
11-18 16:48:56.179  5591  5638 I jxcore-log: 
,11-18 16:48:56.183  5591  5638 I jxcore-log: 2016-11-18 15:48:56 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-18 16:48:56.183  5591  5638 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-18 16:48:56.183  5591  5638 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-18 16:48:56.183  5591  5638 I jxcore-log: emit@events.js:82:1
11-18 16:48:56.183  5591  5638 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-18 16:48:56.183  5591  5638 I jxcore-log: emit@events.js:82:1'
11-18 16:48:56.183  5591  5638 I jxcore-log: 
,11-18 16:48:56.627   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-18 16:48:57.212  5591  5638 I jxcore-log: 2016-11-18 15:48:57 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-18 16:48:57.212  5591  5638 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-18 16:48:57.212  5591  5638 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-18 16:48:57.212  5591  5638 I jxcore-log: emit@events.js:82:1
11-18 16:48:57.212  5591  5638 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-18 16:48:57.212  5591  5638 I jxcore-log: emit@events.js:82:1'
11-18 16:48:57.212  5591  5638 I jxcore-log: 
,11-18 16:48:57.218  5591  5638 I jxcore-log: 2016-11-18 15:48:57 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-18 16:48:57.218  5591  5638 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-18 16:48:57.218  5591  5638 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-18 16:48:57.218  5591  5638 I jxcore-log: emit@events.js:82:1
11-18 16:48:57.218  5591  5638 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-18 16:48:57.218  5591  5638 I jxcore-log: emit@events.js:82:1'
11-18 16:48:57.218  5591  5638 I jxcore-log: 
,11-18 16:48:57.628   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-18 16:48:58.253  5591  5638 I jxcore-log: 2016-11-18 15:48:58 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-18 16:48:58.253  5591  5638 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-18 16:48:58.253  5591  5638 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-18 16:48:58.253  5591  5638 I jxcore-log: emit@events.js:82:1
11-18 16:48:58.253  5591  5638 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-18 16:48:58.253  5591  5638 I jxcore-log: emit@events.js:82:1'
11-18 16:48:58.253  5591  5638 I jxcore-log: 
11-18 16:48:58.257  5591  5638 I jxcore-log: 2016-11-18 15:48:58 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-18 16:48:58.257  5591  5638 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-18 16:48:58.257  5591  5638 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-18 16:48:58.257  5591  5638 I jxcore-log: emit@events.js:82:1
11-18 16:48:58.257  5591  5638 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-18 16:48:58.257  5591  5638 I jxcore-log: emit@events.js:82:1'
11-18 16:48:58.257  5591  5638 I jxcore-log: 
,11-18 16:48:58.630   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-18 16:48:58.695   929  2941 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-18 16:48:59.298  5591  5638 I jxcore-log: 2016-11-18 15:48:59 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-18 16:48:59.298  5591  5638 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-18 16:48:59.298  5591  5638 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-18 16:48:59.298  5591  5638 I jxcore-log: emit@events.js:82:1
11-18 16:48:59.298  5591  5638 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-18 16:48:59.298  5591  5638 I jxcore-log: emit@events.js:82:1'
11-18 16:48:59.298  5591  5638 I jxcore-log: 
,11-18 16:48:59.301  5591  5638 I jxcore-log: 2016-11-18 15:48:59 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-18 16:48:59.301  5591  5638 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-18 16:48:59.301  5591  5638 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-18 16:48:59.301  5591  5638 I jxcore-log: emit@events.js:82:1
11-18 16:48:59.301  5591  5638 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-18 16:48:59.301  5591  5638 I jxcore-log: emit@events.js:82:1'
11-18 16:48:59.301  5591  5638 I jxcore-log: 
,11-18 16:48:59.631   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-18 16:49:00.328  5591  5638 I jxcore-log: 2016-11-18 15:49:00 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-18 16:49:00.328  5591  5638 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-18 16:49:00.328  5591  5638 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-18 16:49:00.328  5591  5638 I jxcore-log: emit@events.js:82:1
11-18 16:49:00.328  5591  5638 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-18 16:49:00.328  5591  5638 I jxcore-log: emit@events.js:82:1'
11-18 16:49:00.328  5591  5638 I jxcore-log: 
,11-18 16:49:00.331  5591  5638 I jxcore-log: 2016-11-18 15:49:00 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-18 16:49:00.331  5591  5638 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-18 16:49:00.331  5591  5638 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-18 16:49:00.331  5591  5638 I jxcore-log: emit@events.js:82:1
11-18 16:49:00.331  5591  5638 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-18 16:49:00.331  5591  5638 I jxcore-log: emit@events.js:82:1'
11-18 16:49:00.331  5591  5638 I jxcore-log: 
,11-18 16:49:00.557   929  5926 D NetlinkSocketObserver: NeighborEvent{elapsedMs=148497, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,11-18 16:49:00.632   537   537 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,11-18 16:49:01.405  5591  5638 I jxcore-log: 2016-11-18 15:49:01 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-18 16:49:01.405  5591  5638 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-18 16:49:01.405  5591  5638 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-18 16:49:01.405  5591  5638 I jxcore-log: emit@events.js:82:1
11-18 16:49:01.405  5591  5638 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-18 16:49:01.405  5591  5638 I jxcore-log: emit@events.js:82:1'
11-18 16:49:01.405  5591  5638 I jxcore-log: 
,11-18 16:49:01.410  5591  5638 I jxcore-log: 2016-11-18 15:49:01 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-18 16:49:01.410  5591  5638 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-18 16:49:01.410  5591  5638 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-18 16:49:01.410  5591  5638 I jxcore-log: emit@events.js:82:1
11-18 16:49:01.410  5591  5638 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-18 16:49:01.410  5591  5638 I jxcore-log: emit@events.js:82:1'
11-18 16:49:01.410  5591  5638 I jxcore-log: 
,11-18 16:49:01.729   929  2941 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-18 16:49:02.446  5591  5638 I jxcore-log: 2016-11-18 15:49:02 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-18 16:49:02.446  5591  5638 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-18 16:49:02.446  5591  5638 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-18 16:49:02.446  5591  5638 I jxcore-log: emit@events.js:82:1
11-18 16:49:02.446  5591  5638 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-18 16:49:02.446  5591  5638 I jxcore-log: emit@events.js:82:1'
11-18 16:49:02.446  5591  5638 I jxcore-log: 
,11-18 16:49:02.451  5591  5638 I jxcore-log: 2016-11-18 15:49:02 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-18 16:49:02.451  5591  5638 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-18 16:49:02.451  5591  5638 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-18 16:49:02.451  5591  5638 I jxcore-log: emit@events.js:82:1
11-18 16:49:02.451  5591  5638 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-18 16:49:02.451  5591  5638 I jxcore-log: emit@events.js:82:1'
11-18 16:49:02.451  5591  5638 I jxcore-log: 
,11-18 16:49:02.586   929  2939 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-18 16:49:03.480  5591  5638 I jxcore-log: 2016-11-18 15:49:03 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-18 16:49:03.480  5591  5638 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-18 16:49:03.480  5591  5638 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-18 16:49:03.480  5591  5638 I jxcore-log: emit@events.js:82:1
11-18 16:49:03.480  5591  5638 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-18 16:49:03.480  5591  5638 I jxcore-log: emit@events.js:82:1'
11-18 16:49:03.480  5591  5638 I jxcore-log: 
,11-18 16:49:03.484  5591  5638 I jxcore-log: 2016-11-18 15:49:03 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-18 16:49:03.484  5591  5638 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-18 16:49:03.484  5591  5638 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-18 16:49:03.484  5591  5638 I jxcore-log: emit@events.js:82:1
11-18 16:49:03.484  5591  5638 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-18 16:49:03.484  5591  5638 I jxcore-log: emit@events.js:82:1'
11-18 16:49:03.484  5591  5638 I jxcore-log: 
,11-18 16:49:04.515  5591  5638 I jxcore-log: 2016-11-18 15:49:04 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-18 16:49:04.515  5591  5638 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-18 16:49:04.515  5591  5638 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-18 16:49:04.515  5591  5638 I jxcore-log: emit@events.js:82:1
11-18 16:49:04.515  5591  5638 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-18 16:49:04.515  5591  5638 I jxcore-log: emit@events.js:82:1'
11-18 16:49:04.515  5591  5638 I jxcore-log: 
,11-18 16:49:04.522  5591  5638 I jxcore-log: 2016-11-18 15:49:04 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-18 16:49:04.522  5591  5638 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-18 16:49:04.522  5591  5638 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-18 16:49:04.522  5591  5638 I jxcore-log: emit@events.js:82:1
11-18 16:49:04.522  5591  5638 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-18 16:49:04.522  5591  5638 I jxcore-log: emit@events.js:82:1'
11-18 16:49:04.522  5591  5638 I jxcore-log: 
,11-18 16:49:05.553  5591  5638 I jxcore-log: 2016-11-18 15:49:05 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-18 16:49:05.553  5591  5638 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-18 16:49:05.553  5591  5638 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-18 16:49:05.553  5591  5638 I jxcore-log: emit@events.js:82:1
11-18 16:49:05.553  5591  5638 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-18 16:49:05.553  5591  5638 I jxcore-log: emit@events.js:82:1'
11-18 16:49:05.553  5591  5638 I jxcore-log: 
,11-18 16:49:05.559  5591  5638 I jxcore-log: 2016-11-18 15:49:05 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-18 16:49:05.559  5591  5638 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-18 16:49:05.559  5591  5638 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-18 16:49:05.559  5591  5638 I jxcore-log: emit@events.js:82:1
11-18 16:49:05.559  5591  5638 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-18 16:49:05.559  5591  5638 I jxcore-log: emit@events.js:82:1'
11-18 16:49:05.559  5591  5638 I jxcore-log: 
,11-18 16:49:06.390   929  5926 D NetlinkSocketObserver: NeighborEvent{elapsedMs=154330, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,11-18 16:49:06.593  5591  5638 I jxcore-log: 2016-11-18 15:49:06 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-18 16:49:06.593  5591  5638 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-18 16:49:06.593  5591  5638 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-18 16:49:06.593  5591  5638 I jxcore-log: emit@events.js:82:1
11-18 16:49:06.593  5591  5638 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-18 16:49:06.593  5591  5638 I jxcore-log: emit@events.js:82:1'
11-18 16:49:06.593  5591  5638 I jxcore-log: 
,11-18 16:49:06.607  5591  5638 E jxcore  : Error!: error is undefined
11-18 16:49:06.607  5591  5638 E jxcore  : Stack: [{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/lib/CoordinatedClient.js","_functionName":"CoordinatedClient.prototype._error","_lineNumber":"223","_columnNumber":"1","_msg":"    at CoordinatedClient.prototype._error@/data/data/com.test.thalitest/files/www/jxcore/lib/CoordinatedClient.js:223:1"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/component-emitter/index.js","_functionName":"Emitter.prototype.emit","_lineNumber":"131","_columnNumber":"7","_msg":"    at Emitter.prototype.emit@/data/data/com.test.thalitest/files/www/jxcore/node_modules/component-emitter/index.js:131:7"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/socket.js","_functionName":"Socket.prototype.emit","_lineNumber":"133","_columnNumber":"5","_msg":"    at Socket.prototype.emit@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/socket.js:133:5"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js","_functionName":"Manager.prototype.emitAll","_lineNumber":"81","_columnNumber":"7","_msg":"    at Manager.prototype.emitAll@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:81:7"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js","_functionName":"Manager.prototype.reconnect","_lineNumber":"507","_columnNumber":"5","_msg":"    at Manager.prototype.reconnect@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:507:5"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js","_functionName":"Manager.prototype.reconnect/timer</<","_lineNumber":"528","_columnNumber":"11","_msg":"    at Manager.prototype.reconnect/timer</<@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:528:11"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js","_functionName":"Manager.prototype.connect/errorSub<","_lineNumber":"235","_columnNumber":"7","_msg":"    at Manager.prototype.connect/errorSub<@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:235:7"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/node_modules/component-emitter/index.js","_functionName":"Emitter.prototype.emit","_lineNumber":"134","_columnNumber":"7","_msg":"    at Emitter.prototype.emit@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/node_modules/component-emitter/index.js:134:7"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/socket.js","_functionName":"Socket.prototype.onError","_lineNumber":"670","_columnNumber":"3","_msg":"    at Socket.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/socket.js:670:3"}]
,11-18 16:49:06.610  5591  5638 I jxcore-log: 2016-11-18 15:49:06 - ERROR TestsProcess: 'uncaught exception, error: 'TypeError: error is undefined', stack: 'TypeError: error is undefined
11-18 16:49:06.610  5591  5638 I jxcore-log:     at CoordinatedClient.prototype._error@/data/data/com.test.thalitest/files/www/jxcore/lib/CoordinatedClient.js:223:1
11-18 16:49:06.610  5591  5638 I jxcore-log:     at Emitter.prototype.emit@/data/data/com.test.thalitest/files/www/jxcore/node_modules/component-emitter/index.js:131:7
11-18 16:49:06.610  5591  5638 I jxcore-log:     at Socket.prototype.emit@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/socket.js:133:5
11-18 16:49:06.610  5591  5638 I jxcore-log:     at Manager.prototype.emitAll@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:81:7
11-18 16:49:06.610  5591  5638 I jxcore-log:     at Manager.prototype.reconnect@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:507:5
11-18 16:49:06.610  5591  5638 I jxcore-log:     at Manager.prototype.reconnect/timer</<@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:528:11
11-18 16:49:06.610  5591  5638 I jxcore-log:     at Manager.prototype.connect/errorSub<@/data/data/com.test.thalitest/files/www/jxcore/node_modules/sock
,11-18 16:49:06.611  5591  5638 I jxcore-log: 2016-11-18 15:49:06 - ERROR TestsProcess: '****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****'
11-18 16:49:06.611  5591  5638 I jxcore-log: 
,11-18 16:49:06.613  5591  5638 E jxcore-log: TypeError: 
11-18 16:49:06.613  5591  5638 E jxcore-log: error is undefined
11-18 16:49:06.613  5591  5638 E jxcore-log:  (/data/data/com.test.thalitest/files/www/jxcore/lib/CoordinatedClient.js 223:0)
11-18 16:49:06.613  5591  5638 E jxcore-log: 
,11-18 16:49:07.128  5962  5962 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,11-18 16:49:07.150  5962  5962 D AndroidRuntime: CheckJNI is OFF
,11-18 16:49:07.175  5962  5962 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,11-18 16:49:07.206  5962  5962 I Radio-JNI: register_android_hardware_Radio DONE
,11-18 16:49:07.222  5962  5962 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,11-18 16:49:07.231   929   942 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=-1: uninstall pkg
,11-18 16:49:07.231   929   942 I ActivityManager: Killing 5591:com.test.thalitest/u0a77 (adj 0): stop com.test.thalitest
,11-18 16:49:07.351   929  2940 D WifiService: Client connection lost with reason: 4
,11-18 16:49:07.351   929  3585 D GraphicsStats: Buffer count: 2
11-18 16:49:07.351   929   939 I WindowState: WIN DEATH: Window{b5b2cca u0 com.test.thalitest/com.test.thalitest.MainActivity}
,11-18 16:49:07.379   929   942 W ActivityManager: Force removing ActivityRecord{256bde3 u0 com.test.thalitest/.MainActivity t70}: app died, no saved state
,11-18 16:49:07.382   929   952 I art     : Starting a blocking GC Explicit
,11-18 16:49:07.391   929  3763 W ActivityManager: Spurious death for ProcessRecord{e7fe26e 0:com.test.thalitest/u0a77}, curProc for 5591: null
,11-18 16:49:07.428   929  3803 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 5591 uid 10077
,11-18 16:49:07.429  3645  3645 I Keyboard.Facilitator: onFinishInput()
,11-18 16:49:07.423  3803  3803 W Binder_A: type=1400 audit(0.0:126): avc: denied { ioctl } for path="socket:[28793]" dev="sockfs" ino=28793 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
11-18 16:49:07.423  3803  3803 W Binder_A: type=1400 audit(0.0:127): avc: denied { ioctl } for path="socket:[28793]" dev="sockfs" ino=28793 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-18 16:49:07.447  3955  3955 W ThreadPoolDumper: Queue length for executor AudioRouter with 1 threads is now 8. Perhaps some tasks are too long, or the pool is too small.
,11-18 16:49:07.471   929   952 I art     : Explicit concurrent mark sweep GC freed 30985(2MB) AllocSpace objects, 13(380KB) LOS objects, 33% free, 29MB/43MB, paused 1.737ms total 88.462ms
,11-18 16:49:07.491   929   952 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,11-18 16:49:07.495  5962  5962 I art     : System.exit called, status: 0
11-18 16:49:07.495  5962  5962 I AndroidRuntime: VM exiting with result code 0.
,11-18 16:49:07.505  3955  5975 I MicroRecognitionRnrImpl: Starting detection.
,11-18 16:49:07.505  3955  5976 I MicrophoneInputStream: mic_starting com.google.android.apps.gsa.speech.audio.x@3325293
,11-18 16:49:07.507   514  5978 I AudioFlinger: AudioFlinger's thread 0xf2080000 ready to run
,11-18 16:49:07.512   514  2987 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
,11-18 16:49:07.513  3955  5976 I MicrophoneInputStream: mic_started com.google.android.apps.gsa.speech.audio.x@3325293
,11-18 16:49:07.520   929   952 I ActivityManager: Start proc 5979:com.android.defcontainer/u0a7 for service com.android.defcontainer/.DefaultContainerService
,11-18 16:49:07.521   929   952 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=0: pkg removed
,11-18 16:49:07.523   514  5978 D audio_hw_primary: select_devices: out_snd_device(0: none) in_snd_device(63: voice-rec-mic)
,11-18 16:49:07.523   514  5978 D msm8974_platform: platform_send_audio_calibration: sending audio calibration for snd_device(63) acdb_id(62)
11-18 16:49:07.523   514  5978 I ACDB-LOADER: ACDB AFE returned = -19
11-18 16:49:07.524   514  5978 I soundtrigger: audio_extn_sound_trigger_update_device_status: device 0x3f of type 1 for Event 1
11-18 16:49:07.524   514  5978 D sound_trigger_platform: platform_stdev_check_and_update_concurrency: concurrency active 0, tx 1, rx 0, concurrency session_allowed 0
11-18 16:49:07.524   514  5978 D audio_hw_primary: enable_snd_device: snd_device(63: voice-rec-mic)
,11-18 16:49:07.527  5785  5785 D BluetoothMapAppObserver: onReceive
11-18 16:49:07.527  5785  5785 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
,11-18 16:49:07.534   514  5978 D audio_hw_primary: enable_audio_route: apply and update mixer path: audio-record
,11-18 16:49:07.540   929  2931 I InputReader: Reconfiguring input devices.  changes=0x00000010
,11-18 16:49:07.540  4087  4145 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,11-18 16:49:07.543  3645  3645 I Keyboard.Facilitator: resetDictionaries() : en_US
,11-18 16:49:07.552  3645  5991 I Keyboard.Facilitator.DecoderInitializer: run()
,11-18 16:49:07.557  3645  5991 I Decoder : createOrResetDecoder
,11-18 16:49:07.597  3394  5994 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,11-18 16:49:07.598  3569  3569 I ConfigService: onCreate
,11-18 16:49:07.601  3747  3747 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,11-18 16:49:07.616    29    29 W kworker/3:1: type=1400 audit(0.0:128): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-18 16:49:07.618  3955  3955 I HotwordWorkerImpl: onReady
11-18 16:49:07.619   929   929 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,11-18 16:49:07.623    29    29 W kworker/3:1: type=1400 audit(0.0:129): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-18 16:49:07.634   929   941 E PackageManager: Failed to write settings, restoring backup
11-18 16:49:07.634   929   941 E PackageManager: java.io.IOException: write failed: EBADF (Bad file descriptor)
11-18 16:49:07.634   929   941 E PackageManager: 	at libcore.io.IoBridge.write(IoBridge.java:498)
11-18 16:49:07.634   929   941 E PackageManager: 	at java.io.FileOutputStream.write(FileOutputStream.java:186)
11-18 16:49:07.634   929   941 E PackageManager: 	at java.io.OutputStreamWriter.flushBytes(OutputStreamWriter.java:170)
11-18 16:49:07.634   929   941 E PackageManager: 	at java.io.OutputStreamWriter.convert(OutputStreamWriter.java:184)
11-18 16:49:07.634   929   941 E PackageManager: 	at java.io.OutputStreamWriter.write(OutputStreamWriter.java:269)
11-18 16:49:07.634   929   941 E PackageManager: 	at java.io.BufferedWriter.write(BufferedWriter.java:236)
11-18 16:49:07.634   929   941 E PackageManager: 	at org.kxml2.io.KXmlSerializer.attribute(KXmlSerializer.java:468)
11-18 16:49:07.634   929   941 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.writePermissionsSync(Settings.java:4644)
11-18 16:49:07.634   929   941 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.-wrap1(Settings.java)
11-18 16:49:07.634   929   941 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence$MyHandler.handleMessage(Settings.java:4830)
11-18 16:49:07.634   929   941 E PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-18 16:49:07.634   929   941 E PackageManager: 	at android.os.Looper.loop(Looper.java:148)
11-18 16:49:07.634   929   941 E PackageManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
11-18 16:49:07.634   929   941 E PackageManager: Caused by: android.system.ErrnoException: write failed: EBADF (Bad file descriptor)
11-18 16:49:07.634   929   941 E PackageManager: 	at libcore.io.Posix.writeBytes(Native Method)
11-18 16:49:07.634   929   941 E PackageManager: 	at libcore.io.Posix.write(Posix.java:271)
11-18 16:49:07.634   929   941 E PackageManager: 	at libcore.io.BlockGuardOs.write(BlockGuardOs.java:313)
11-18 16:49:07.634   929   941 E PackageManager: 	at libcore.io.IoBridge.write(IoBridge.java:493)
11-18 16:49:07.634   929   941 E PackageManager: 	... 12 more
,11-18 16:49:07.634  3645  5991 I Keyboard.Facilitator.MainLanguageModelLoader: run()
,11-18 16:49:07.643  3569  3569 E SQLiteLog: (3850) statement aborts at 26: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
,11-18 16:49:07.644  3569  3569 D AndroidRuntime: Shutting down VM
--------- beginning of crash
11-18 16:49:07.644  3569  3569 E AndroidRuntime: FATAL EXCEPTION: main
11-18 16:49:07.644  3569  3569 E AndroidRuntime: Process: com.google.process.gapps, PID: 3569
11-18 16:49:07.644  3569  3569 E AndroidRuntime: java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
11-18 16:49:07.644  3569  3569 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2732)
11-18 16:49:07.644  3569  3569 E AndroidRuntime: 	at android.app.ActivityThread.-wrap14(ActivityThread.java)
11-18 16:49:07.644  3569  3569 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1421)
11-18 16:49:07.644  3569  3569 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-18 16:49:07.644  3569  3569 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
11-18 16:49:07.644  3569  3569 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-18 16:49:07.644  3569  3569 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
11-18 16:49:07.644  3569  3569 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-18 16:49:07.644  3569  3569 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-18 16:49:07.644  3569  3569 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
11-18 16:49:07.644  3569  3569 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
11-18 16:49:07.644  3569  3569 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
11-18 16:49:07.644  3569  3569 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
11-18 16:49:07.644  3569  3569 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
11-18 16:49:07.644  3569  3569 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
11-18 16:49:07.644  3569  3569 E AndroidRuntime: 	at com.google.android.gms.gcm.bg.a(SourceFile:310)
11-18 16:49:07.644  3569  3569 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
11-18 16:49:07.644  3569  3569 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
11-18 16:49:07.644  3569  3569 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2725)
11-18 16:49:07.644  3569  3569 E AndroidRuntime: 	... 8 more
,11-18 16:49:07.653    29    29 W kworker/3:1: type=1400 audit(0.0:130): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-18 16:49:07.660   398   398 W Binder_1: type=1400 audit(0.0:131): avc: denied { ioctl } for path="socket:[28401]" dev="sockfs" ino=28401 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-18 16:49:07.660   398   398 W Binder_1: type=1400 audit(0.0:132): avc: denied { ioctl } for path="socket:[28401]" dev="sockfs" ino=28401 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-18 16:49:07.663   402   402 W Binder_2: type=1400 audit(0.0:133): avc: denied { ioctl } for path="socket:[32690]" dev="sockfs" ino=32690 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-18 16:49:07.667   929  6001 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
11-18 16:49:07.663   402   402 W Binder_2: type=1400 audit(0.0:134): avc: denied { ioctl } for path="socket:[32690]" dev="sockfs" ino=32690 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-18 16:49:07.686   929  3805 I ActivityManager: Start proc 6004:com.google.android.googlequicksearchbox:crash_report/u0a29 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
,11-18 16:49:07.687  3781  3910 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
11-18 16:49:07.687  3781  3910 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 3781
11-18 16:49:07.687  3781  3910 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 778)
11-18 16:49:07.687  3781  3910 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
11-18 16:49:07.687  3781  3910 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
11-18 16:49:07.687  3781  3910 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
11-18 16:49:07.687  3781  3910 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
11-18 16:49:07.687  3781  3910 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
11-18 16:49:07.687  3781  3910 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
11-18 16:49:07.687  3781  3910 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
11-18 16:49:07.687  3781  3910 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
11-18 16:49:07.687  3781  3910 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
11-18 16:49:07.687  3781  3910 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
11-18 16:49:07.687  3781  3910 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,11-18 16:49:07.689   929   940 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,11-18 16:49:07.693   929  6012 E DropBoxManagerService: Can't write: system_app_crash
11-18 16:49:07.693   929  6012 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop116.tmp: open failed: EROFS (Read-only file system)
11-18 16:49:07.693   929  6012 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
11-18 16:49:07.693   929  6012 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
11-18 16:49:07.693   929  6012 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
11-18 16:49:07.693   929  6012 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
11-18 16:49:07.693   929  6012 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
11-18 16:49:07.693   929  6012 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
11-18 16:49:07.693   929  6012 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
11-18 16:49:07.693   929  6012 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
11-18 16:49:07.693   929  6012 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
11-18 16:49:07.693   929  6012 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
11-18 16:49:07.693   929  6012 E DropBoxManagerService: 	... 5 more
,11-18 16:49:07.695  3955  4211 W SearchService: Abort, client detached.
,11-18 16:49:07.696  3394  5994 E SQLiteLog: (3850) statement aborts at 18: [DELETE FROM calls WHERE (((source_package = 'com.test.thalitest'))) AND ((type = 4))] disk I/O error
11-18 16:49:07.697  3394  5994 E AndroidRuntime: FATAL EXCEPTION: IntentService[VoicemailCleanupService]
11-18 16:49:07.697  3394  5994 E AndroidRuntime: Process: android.process.acore, PID: 3394
11-18 16:49:07.697  3394  5994 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
11-18 16:49:07.697  3394  5994 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
11-18 16:49:07.697  3394  5994 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
11-18 16:49:07.697  3394  5994 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
11-18 16:49:07.697  3394  5994 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
11-18 16:49:07.697  3394  5994 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
11-18 16:49:07.697  3394  5994 E AndroidRuntime: 	at com.android.providers.contacts.DbModifierWithNotification.delete(DbModifierWithNotification.java:197)
11-18 16:49:07.697  3394  5994 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:219)
11-18 16:49:07.697  3394  5994 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
11-18 16:49:07.697  3394  5994 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
11-18 16:49:07.697  3394  5994 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
11-18 16:49:07.697  3394  5994 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
11-18 16:49:07.697  3394  5994 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
11-18 16:49:07.697  3394  5994 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
11-18 16:49:07.697  3394  5994 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-18 16:49:07.697  3394  5994 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
11-18 16:49:07.697  3394  5994 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,11-18 16:49:07.698  3955  3955 I HotwordDetector: Closing mic
11-18 16:49:07.699  3955  4146 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@3325293
11-18 16:49:07.700  3955  5976 E AudioRecord-JNI: Error -4 during AudioRecord native read
,11-18 16:49:07.703   929  6017 E DropBoxManagerService: Can't write: system_app_crash
11-18 16:49:07.703   929  6017 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop117.tmp: open failed: EROFS (Read-only file system)
11-18 16:49:07.703   929  6017 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
11-18 16:49:07.703   929  6017 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
11-18 16:49:07.703   929  6017 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
11-18 16:49:07.703   929  6017 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
11-18 16:49:07.703   929  6017 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
11-18 16:49:07.703   929  6017 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
11-18 16:49:07.703   929  6017 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
11-18 16:49:07.703   929  6017 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
11-18 16:49:07.703   929  6017 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
11-18 16:49:07.703   929  6017 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
11-18 16:49:07.703   929  6017 E DropBoxManagerService: 	... 5 more
,11-18 16:49:07.704  3645  5991 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /data/user/0/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
,11-18 16:49:07.707  3645  5991 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
,11-18 16:49:07.707  3645  5991 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
,11-18 16:49:07.721  3645  5991 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Contacts.dict
,11-18 16:49:07.721  3645  5991 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = history
11-18 16:49:07.721  3645  5991 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loaded File = UserHistory.en_US.dict
11-18 16:49:07.721  3645  5991 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = user
11-18 16:49:07.722  3645  5991 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Personal.en_US.dict
11-18 16:49:07.722  3645  5991 I Keyboard.Facilitator.PersonalDictionaryLoader: run() : Loaded (exit)
11-18 16:49:07.722  3645  5991 I Keyboard.Facilitator.Delight2FileSweeper: run()
11-18 16:49:07.722  3645  5991 I Keyboard.Facilitator.RecurringTaskScheduler: run()
11-18 16:49:07.722  3645  5991 I StatsUtilsManager: startPeriodStatsRecorder() : Success
,11-18 16:49:07.722  3645  5991 I PeriodicStatsRecorder: shouldRecordStats() = Too Soon
,11-18 16:49:07.778   514  5978 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
,11-18 16:49:07.779   514  5978 D audio_hw_primary: disable_snd_device: snd_device(63: voice-rec-mic)
,11-18 16:49:07.782   514  5978 I soundtrigger: audio_extn_sound_trigger_update_device_status: device 0x3f of type 1 for Event 0
11-18 16:49:07.782   514  5978 D sound_trigger_platform: platform_stdev_check_and_update_concurrency: concurrency active 0, tx 0, rx 0, concurrency session_allowed 1
11-18 16:49:07.783   514  2987 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
11-18 16:49:07.786  3955  4147 I MicroRecognitionRnrImpl: Stopping hotword detection.
11-18 16:49:07.786  3955  5975 I MicroRecognitionRnrImpl: Detection finished
,11-18 16:49:08.050   382   482 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0

```
