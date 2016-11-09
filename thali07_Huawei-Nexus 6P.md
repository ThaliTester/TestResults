#### Test 8962479676fe425_thali07_Huawei-Nexus 6P Logs


```
--------- beginning of main
11-09 10:32:59.979  4045  4214 I Icing   : Indexing 3C763AF371F9E97B4ECFEA01A338ADB468C38476 from com.google.android.googlequicksearchbox
,11-09 10:33:00.054  4045  4214 I Icing   : Indexing done 3C763AF371F9E97B4ECFEA01A338ADB468C38476
11-09 10:33:00.414  5606  5606 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
11-09 10:33:00.420  5606  5606 D AndroidRuntime: CheckJNI is OFF
11-09 10:33:00.448  5606  5606 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
11-09 10:33:00.490  5606  5606 I Radio-JNI: register_android_hardware_Radio DONE
11-09 10:33:00.505  5606  5606 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
11-09 10:33:00.516   931  3814 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
11-09 10:33:00.550  3963  3978 W SearchService: Abort, client detached.
11-09 10:33:00.551  5606  5606 D AndroidRuntime: Shutting down VM
11-09 10:33:00.558  3963  3963 I HotwordDetector: Closing mic
11-09 10:33:00.558  3963  4193 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@819c8cb
11-09 10:33:00.558  3963  4219 E AudioRecord-JNI: Error -4 during AudioRecord native read
11-09 10:33:00.581   931   942 I ActivityManager: Start proc 5615:com.test.thalitest/u0a77 for activity com.test.thalitest/.MainActivity
11-09 10:33:00.627   516  4222 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
11-09 10:33:00.628   516  4222 D audio_hw_primary: disable_snd_device: snd_device(63: voice-rec-mic)
11-09 10:33:00.633   516  4222 I soundtrigger: audio_extn_sound_trigger_update_device_status: device 0x3f of type 1 for Event 0
11-09 10:33:00.633   516  4222 D sound_trigger_platform: platform_stdev_check_and_update_concurrency: concurrency active 0, tx 0, rx 0, concurrency session_allowed 1
11-09 10:33:00.633   516  3007 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
11-09 10:33:00.634  3963  4218 I MicroRecognitionRnrImpl: Detection finished
11-09 10:33:00.635  3963  4198 I MicroRecognitionRnrImpl: Stopping hotword detection.
11-09 10:33:00.678  5615  5615 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011750)
11-09 10:33:00.714  5615  5615 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,11-09 10:33:00.773  5615  5615 I LibraryLoader: Time to load native libraries: 53 ms (timestamps 5654-5707)
11-09 10:33:00.773  5615  5615 I LibraryLoader: Expected native library version number "",actual native library version number ""
,11-09 10:33:00.810  5615  5615 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {995e4ea}
11-09 10:33:00.811  5615  5615 I LibraryLoader: Expected native library version number "",actual native library version number ""
11-09 10:33:00.811  5615  5615 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,11-09 10:33:00.817  5615  5615 I BrowserStartupController: Initializing chromium process, singleProcess=true
,11-09 10:33:00.819  5615  5615 E SysUtils: ApplicationContext is null in ApplicationStatus
,11-09 10:33:00.867  5615  5615 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,11-09 10:33:00.888  5615  5615 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,11-09 10:33:00.888  5615  5615 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
11-09 10:33:00.889  5615  5615 I Adreno  : QUALCOMM build                   : 63c06b2, I8366cd0437
11-09 10:33:00.889  5615  5615 I Adreno  : Build Date                       : 12/06/15
11-09 10:33:00.889  5615  5615 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
11-09 10:33:00.889  5615  5615 I Adreno  : Local Branch                     : mybranch17112971
11-09 10:33:00.889  5615  5615 I Adreno  : Remote Branch                    : quic/LA.BF64.1.2.9_v2
11-09 10:33:00.889  5615  5615 I Adreno  : Remote Branch                    : NONE
11-09 10:33:00.889  5615  5615 I Adreno  : Reconstruct Branch               : NOTHING
,11-09 10:33:00.942   931   948 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@9dd33d2:true
,11-09 10:33:00.971   403   403 W Binder_1: type=1400 audit(0.0:99): avc: denied { ioctl } for path="socket:[32875]" dev="sockfs" ino=32875 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-09 10:33:00.971   403   403 W Binder_1: type=1400 audit(0.0:100): avc: denied { ioctl } for path="socket:[32875]" dev="sockfs" ino=32875 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-09 10:33:00.982  5615  5615 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,11-09 10:33:00.993  5615  5615 D SystemWebViewEngine: CordovaWebView is running on device made by: Huawei
,11-09 10:33:01.017   766   766 W Binder_4: type=1400 audit(0.0:101): avc: denied { ioctl } for path="socket:[29590]" dev="sockfs" ino=29590 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-09 10:33:01.017   766   766 W Binder_4: type=1400 audit(0.0:102): avc: denied { ioctl } for path="socket:[29590]" dev="sockfs" ino=29590 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
11-09 10:33:01.019  5615  5652 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,11-09 10:33:01.021  3429  3429 W Binder_6: type=1400 audit(0.0:103): avc: denied { ioctl } for path="socket:[20299]" dev="sockfs" ino=20299 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-09 10:33:01.021  3429  3429 W Binder_6: type=1400 audit(0.0:104): avc: denied { ioctl } for path="socket:[20299]" dev="sockfs" ino=20299 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
11-09 10:33:01.024  5615  5639 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,11-09 10:33:01.054  5615  5652 I OpenGLRenderer: Initialized EGL, version 1.4
,11-09 10:33:01.123   931   949 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +566ms
,11-09 10:33:01.121  4826  4826 W Binder_A: type=1400 audit(0.0:105): avc: denied { ioctl } for path="socket:[31998]" dev="sockfs" ino=31998 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-09 10:33:01.121  4826  4826 W Binder_A: type=1400 audit(0.0:106): avc: denied { ioctl } for path="socket:[31998]" dev="sockfs" ino=31998 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-09 10:33:01.121  3814  3814 W Binder_8: type=1400 audit(0.0:107): avc: denied { ioctl } for path="socket:[31997]" dev="sockfs" ino=31997 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-09 10:33:01.124  3814  3814 W Binder_8: type=1400 audit(0.0:108): avc: denied { ioctl } for path="socket:[31997]" dev="sockfs" ino=31997 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
11-09 10:33:01.128  3661  3661 I Keyboard.Facilitator: onFinishInput()
,11-09 10:33:01.149  5615  5615 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 5615
,11-09 10:33:01.224  5615  5615 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,11-09 10:33:01.359  5615  5655 D jxcore_app_log: JniHelper::setJavaVM(0xf4e7c000), pthread_self() = -587724496
,11-09 10:33:01.363  5615  5655 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
11-09 10:33:01.363  5615  5655 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
11-09 10:33:01.363  5615  5655 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
11-09 10:33:01.363  5615  5655 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
11-09 10:33:01.363  5615  5655 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,11-09 10:33:01.364  5615  5655 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1aca150 added. We now have 1 listener(s)
,11-09 10:33:01.365  5615  5655 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 60:83:34:25:D7:D4
,11-09 10:33:01.366  5615  5655 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
,11-09 10:33:01.366  5615  5655 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,11-09 10:33:01.367  5615  5655 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,11-09 10:33:01.369  5615  5655 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
11-09 10:33:01.369  5615  5655 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
11-09 10:33:01.369  5615  5655 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
11-09 10:33:01.369  5615  5655 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 60:83:34:25:D7:D4
11-09 10:33:01.369  5615  5655 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
11-09 10:33:01.369  5615  5655 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
11-09 10:33:01.369  5615  5655 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
11-09 10:33:01.369  5615  5655 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
11-09 10:33:01.369  5615  5655 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
11-09 10:33:01.369  5615  5655 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
11-09 10:33:01.369  5615  5655 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
11-09 10:33:01.369  5615  5655 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
11-09 10:33:01.369  5615  5655 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
11-09 10:33:01.369  5615  5655 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
11-09 10:33:01.369  5615  5655 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@98f56f added. We now have 1 listener(s)
,11-09 10:33:01.369  5615  5655 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-09 10:33:01.374   931  2958 D WifiService: New client listening to asynchronous messages
,11-09 10:33:01.374  5615  5655 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,11-09 10:33:01.374  5615  5655 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
11-09 10:33:01.374  5615  5655 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
11-09 10:33:01.374  5615  5655 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
11-09 10:33:01.374  5615  5655 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,11-09 10:33:01.376  5615  5655 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-09 10:33:01.376  5615  5655 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
,11-09 10:33:01.380  5615  5655 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,11-09 10:33:01.380  5615  5655 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-09 10:33:01.380  5615  5655 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-09 10:33:01.380  5615  5655 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-09 10:33:01.380  5615  5655 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-09 10:33:01.380  5615  5655 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-09 10:33:01.380  5615  5655 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-09 10:33:01.380  5615  5655 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-09 10:33:01.380  5615  5655 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,11-09 10:33:01.380  5615  5655 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
,11-09 10:33:01.381  5615  5655 D io.jxcore.node.ConnectivityMonitor: start: OK
11-09 10:33:01.382  5615  5655 I io.jxcore.node.LifeCycleMonitor: start: OK
,11-09 10:33:01.384  5615  5615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-09 10:33:01.387  5615  5615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-09 10:33:01.397  5615  5615 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,11-09 10:33:01.785  5615  5663 W jxcore-log: Initializing JXcore engine
,11-09 10:33:01.785  5615  5663 W jxcore-log: JXcore engine is ready
,11-09 10:33:01.807  5663  5663 W Thread-62: type=1400 audit(0.0:109): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=10195 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,11-09 10:33:01.807  5663  5663 W Thread-62: type=1400 audit(0.0:110): avc: denied { ioctl } for path="socket:[15414]" dev="sockfs" ino=15414 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
11-09 10:33:01.807  5663  5663 W Thread-62: type=1400 audit(0.0:111): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=708 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
11-09 10:33:01.807  5663  5663 W Thread-62: type=1400 audit(0.0:112): avc: denied { ioctl } for path="socket:[31972]" dev="sockfs" ino=31972 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:untrusted_app:s0:c512,c768 tclass=netlink_route_socket permissive=0
,11-09 10:33:01.817  5615  5663 W jxcore-log: Starting JXcore engine
,11-09 10:33:01.869  5615  5663 W jxcore-log: Platform android
11-09 10:33:01.869  5615  5663 W jxcore-log: 
,11-09 10:33:01.869  5615  5663 W jxcore-log: Process ARCH arm
11-09 10:33:01.869  5615  5663 W jxcore-log: 
,11-09 10:33:02.007  5615  5663 I jxcore-log: JXcore Cordova bridge is ready!
11-09 10:33:02.007  5615  5663 I jxcore-log: 
,11-09 10:33:02.007  5615  5663 W jxcore-log: JXcore engine is started
,11-09 10:33:02.015  5615  5655 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,11-09 10:33:02.018  5615  5615 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,11-09 10:33:05.089  4045  4045 I ConfigFetchService: fetch service done; releasing wakelock
,11-09 10:33:05.091  4045  4045 I ConfigFetchService: stopping self
,11-09 10:33:05.423   931  2957 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-09 10:33:05.564   931  3429 I ActivityManager: Killing 5175:com.google.android.youtube/u0a75 (adj 15): empty #17
,11-09 10:33:07.836   540   540 I ServiceManager: Waiting for service AtCmdFwd...
,11-09 10:33:08.837   540   540 I ServiceManager: Waiting for service AtCmdFwd...
,11-09 10:33:09.838   540   540 I ServiceManager: Waiting for service AtCmdFwd...
,11-09 10:33:10.111  3589  3589 I ConfigService: onDestroy
,11-09 10:33:10.839   540   540 I ServiceManager: Waiting for service AtCmdFwd...
,11-09 10:33:11.579  5615  5663 I jxcore-log: 2016-11-09 09:33:11 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
11-09 10:33:11.579  5615  5663 I jxcore-log: 
,11-09 10:33:11.581  5615  5663 I jxcore-log: 2016-11-09 09:33:11 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
11-09 10:33:11.581  5615  5663 I jxcore-log: 
,11-09 10:33:11.586  5615  5663 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-09 10:33:11.586  5615  5663 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-09 10:33:11.586  5615  5663 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-09 10:33:11.586  5615  5663 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-09 10:33:11.586  5615  5663 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-09 10:33:11.586  5615  5663 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-09 10:33:11.586  5615  5663 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-09 10:33:11.586  5615  5663 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,11-09 10:33:11.587  5615  5663 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,11-09 10:33:11.589  5615  5663 I jxcore-log: 2016-11-09 09:33:11 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
11-09 10:33:11.589  5615  5663 I jxcore-log: 
11-09 10:33:11.590  5615  5663 I jxcore-log: 2016-11-09 09:33:11 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
11-09 10:33:11.590  5615  5663 I jxcore-log: 
,11-09 10:33:11.841   540   540 I ServiceManager: Waiting for service AtCmdFwd...
,11-09 10:33:11.844  5615  5663 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,11-09 10:33:11.844  5615  5663 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fcabfc5 added. We now have 2 listener(s)
11-09 10:33:11.845  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
,11-09 10:33:11.845  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,11-09 10:33:11.845  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-09 10:33:11.845  5615  5663 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-09 10:33:11.845  5615  5663 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@71fdd1a added. We now have 2 listener(s)
11-09 10:33:11.845  5615  5663 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-09 10:33:11.846  5615  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
11-09 10:33:11.848  5615  5663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,11-09 10:33:11.851  5615  5663 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-09 10:33:11.851  5615  5663 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-09 10:33:11.851  5615  5663 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-09 10:33:11.851  5615  5663 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-09 10:33:11.851  5615  5663 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-09 10:33:11.851  5615  5663 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-09 10:33:11.851  5615  5663 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-09 10:33:11.851  5615  5663 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
11-09 10:33:11.852  5615  5663 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,11-09 10:33:11.852  5615  5663 D io.jxcore.node.ConnectivityMonitor: start: OK
11-09 10:33:11.853  5615  5663 D ExecuteNativeTests: Running unit tests
11-09 10:33:11.854  5615  5663 D BluetoothAdapter: enable(): BT is already enabled..!
11-09 10:33:11.854   931   942 D WifiService: setWifiEnabled: true pid=5615, uid=10077
11-09 10:33:11.854   931   942 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-09 10:33:11.856  5615  5615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-09 10:33:11.862  5615  5615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-09 10:33:12.841   540   540 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,11-09 10:33:13.777  3963  5667 W CronetSyncConnectionRcs: Upload content type not set.
,11-09 10:33:13.938  4897  4931 D Finsky  : [192] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,11-09 10:33:13.949  4897  4897 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,11-09 10:33:13.951   931  4826 I ActivityManager: Killing 5263:org.codeaurora.ims/1001 (adj 15): empty #17
,11-09 10:33:21.860  5615  5663 I com.test.thalitest.ThaliTestRunner: Running UT
,11-09 10:33:21.927  5615  5663 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,11-09 10:33:21.927  5615  5663 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8df729c added. We now have 3 listener(s)
11-09 10:33:21.928  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-09 10:33:21.928  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,11-09 10:33:21.928  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-09 10:33:21.928  5615  5663 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-09 10:33:21.928  5615  5663 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cb784a5 added. We now have 3 listener(s)
11-09 10:33:21.928  5615  5663 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-09 10:33:21.929  5615  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,11-09 10:33:21.932  5615  5663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,11-09 10:33:21.937  5615  5663 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-09 10:33:21.937  5615  5663 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-09 10:33:21.937  5615  5663 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-09 10:33:21.937  5615  5663 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-09 10:33:21.937  5615  5663 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-09 10:33:21.937  5615  5663 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-09 10:33:21.937  5615  5663 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-09 10:33:21.937  5615  5663 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
11-09 10:33:21.938  5615  5663 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,11-09 10:33:21.938  5615  5663 D io.jxcore.node.ConnectivityMonitor: start: OK
,11-09 10:33:21.943  5615  5663 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnConnectionTimeout
,11-09 10:33:21.944  5615  5663 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,11-09 10:33:21.944  5615  5663 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,11-09 10:33:21.944  5615  5663 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-09 10:33:21.944  5615  5663 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-09 10:33:21.945  5615  5663 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
11-09 10:33:21.945  5615  5663 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
11-09 10:33:21.945  5615  5663 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
11-09 10:33:21.946  5615  5663 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-09 10:33:21.946  5615  5663 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-09 10:33:21.946  5615  5663 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,11-09 10:33:21.946  5615  5663 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnBluetoothMacAddressResolved
11-09 10:33:21.946  5615  5663 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
11-09 10:33:21.946  5615  5615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-09 10:33:21.947  5615  5663 I io.jxcore.node.ConnectionHelperTest: Starting test: testHasMaximumNumberOfConnections
11-09 10:33:21.949  5615  5663 I io.jxcore.node.ConnectionHelperTest: Starting test: testStart
11-09 10:33:21.949  5615  5663 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
11-09 10:33:21.952  5615  5615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-09 10:33:21.953  5615  5663 V io.jxcore.node.ConnectivityMonitor: start: Already started
11-09 10:33:21.953  5615  5663 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 1
11-09 10:33:21.953  5615  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 0 -> 1
11-09 10:33:21.953  5615  5663 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
11-09 10:33:21.953  5615  5663 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
11-09 10:33:21.953  5615  5663 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
,11-09 10:33:21.953  5615  5663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-09 10:33:21.954  5615  5663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,11-09 10:33:21.954  5615  5663 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
11-09 10:33:21.954  5615  5663 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
11-09 10:33:21.954  5615  5663 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
11-09 10:33:21.955  5615  5663 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
11-09 10:33:21.955  5615  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
11-09 10:33:21.955  5615  5663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-09 10:33:21.955  5615  5663 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
11-09 10:33:21.955  5615  5615 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
11-09 10:33:21.955  5615  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
11-09 10:33:21.957  5615  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-09 10:33:21.957  5615  5663 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-09 10:33:21.957  5615  5663 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
11-09 10:33:21.960  5615  5670 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-09 10:33:21.962  5615  5663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-09 10:33:21.957  4688  4688 W Binder_1: type=1400 audit(0.0:113): avc: denied { ioctl } for path="socket:[20305]" dev="sockfs" ino=20305 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-09 10:33:21.957  4688  4688 W Binder_1: type=1400 audit(0.0:114): avc: denied { ioctl } for path="socket:[20305]" dev="sockfs" ino=20305 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-09 10:33:21.963  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,11-09 10:33:21.963  5615  5663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-09 10:33:21.963  5615  5670 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
11-09 10:33:21.964  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Current thread: Thread[Thread-62,5,main], id: 62
11-09 10:33:21.964  5615  5663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
,11-09 10:33:21.964  5615  5663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-09 10:33:21.964  5615  5663 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 01 60 83 34 25 D7 D4
,11-09 10:33:21.965  5615  5663 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-09 10:33:21.965  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: Current thread: Thread[Thread-62,5,main], id: 62
11-09 10:33:21.965  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData finished: Current thread: Thread[Thread-62,5,main], id: 62
,11-09 10:33:21.965  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = NOT_STARTEDCurrent thread: Thread[Thread-62,5,main], id: 62
11-09 10:33:21.965  5615  5663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... adv data = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]Current thread: Thread[Thread-62,5,main], id: 62
11-09 10:33:21.965  5615  5663 D BluetoothAdapter: STATE_ON
11-09 10:33:21.968  4676  4688 D BtGatt.GattService: registerClient() - UUID=17275a58-1893-4303-8f61-2767c28fce90
,11-09 10:33:21.969  4676  4736 D BtGatt.GattService: onClientRegistered() - UUID=17275a58-1893-4303-8f61-2767c28fce90, clientIf=5
,11-09 10:33:21.971  5615  5625 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
,11-09 10:33:21.975  4676  4738 D BtGatt.AdvertiseManager: message : 0
,11-09 10:33:21.979  4676  4738 D BtGatt.AdvertiseManager: starting multi advertising
,11-09 10:33:21.996  4676  4736 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,11-09 10:33:22.004  4676  4736 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,11-09 10:33:22.005  5615  5663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment Current thread: Thread[Thread-62,5,main], id: 62
,11-09 10:33:22.005  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTINGCurrent thread: Thread[Thread-62,5,main], id: 62
11-09 10:33:22.005  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
11-09 10:33:22.006  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged default (no call to listener). Current thread: Thread[Thread-62,5,main], id: 62
11-09 10:33:22.006  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finishedCurrent thread: Thread[Thread-62,5,main], id: 62
11-09 10:33:22.006  5615  5663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[Thread-62,5,main], id: 62
11-09 10:33:22.006  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[Thread-62,5,main], id: 62
11-09 10:33:22.006  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser started = trueCurrent thread: Thread[Thread-62,5,main], id: 62
11-09 10:33:22.006  5615  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-09 10:33:22.006  5615  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,11-09 10:33:22.006  5615  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-09 10:33:22.007  5615  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-09 10:33:22.007  5615  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-09 10:33:22.007  5615  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-09 10:33:22.007  5615  5663 I io.jxcore.node.ConnectionHelper: start: OK
11-09 10:33:22.007  5615  5615 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,11-09 10:33:22.008  5615  5615 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess : Current thread: Thread[main,5,main], id: 1
11-09 10:33:22.008  5615  5615 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNINGCurrent thread: Thread[main,5,main], id: 1
11-09 10:33:22.008  5615  5615 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
11-09 10:33:22.008  5615  5615 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged true. Current thread: Thread[main,5,main], id: 1
11-09 10:33:22.008  5615  5615 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-09 10:33:22.008  5615  5615 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-09 10:33:22.009  5615  5615 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [ADVERTISING]
11-09 10:33:22.009  5615  5615 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-09 10:33:22.009  5615  5615 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-09 10:33:22.009  5615  5615 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]Current thread: Thread[main,5,main], id: 1
11-09 10:33:22.009  5615  5615 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
11-09 10:33:22.009  5615  5615 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
,11-09 10:33:22.012  5615  5615 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-09 10:33:22.012  5615  5615 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
,11-09 10:33:22.013  5615  5615 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-09 10:33:22.013  5615  5615 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-09 10:33:22.013  5615  5615 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-09 10:33:22.013  5615  5615 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finishedCurrent thread: Thread[main,5,main], id: 1
11-09 10:33:22.013  5615  5615 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,11-09 10:33:22.510  5615  5663 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-09 10:33:22.511  5615  5663 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
11-09 10:33:22.511  5615  5663 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
11-09 10:33:22.511  5615  5663 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
11-09 10:33:22.511  5615  5663 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
11-09 10:33:22.511  5615  5663 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
11-09 10:33:22.511  5615  5663 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
11-09 10:33:22.511  5615  5663 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
11-09 10:33:22.511  5615  5663 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
11-09 10:33:22.511  5615  5663 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
11-09 10:33:22.512  5615  5663 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
11-09 10:33:22.512  5615  5663 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
11-09 10:33:22.512  5615  5663 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
,11-09 10:33:22.512  5615  5663 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
11-09 10:33:22.512  5615  5663 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
11-09 10:33:22.512  5615  5663 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
11-09 10:33:22.512  5615  5663 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
11-09 10:33:22.512  5615  5663 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
11-09 10:33:22.512  5615  5663 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
11-09 10:33:22.513  5615  5663 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
11-09 10:33:22.513  5615  5663 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
11-09 10:33:22.513  5615  5663 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
11-09 10:33:22.513  5615  5663 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
11-09 10:33:22.513  5615  5663 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
11-09 10:33:22.513  5615  5663 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
11-09 10:33:22.513  5615  5663 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
11-09 10:33:22.513  5615  5663 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
11-09 10:33:22.513  5615  5663 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
11-09 10:33:22.513  5615  5663 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
11-09 10:33:22.513  5615  5663 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
11-09 10:33:22.514  5615  5663 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
11-09 10:33:22.514  5615  5663 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
11-09 10:33:22.514  5615  5663 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
11-09 10:33:22.514  5615  5663 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
11-09 10:33:22.514  5615  5663 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
11-09 10:33:22.514  5615  5663 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
,11-09 10:33:22.514  5615  5663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
11-09 10:33:22.515  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
11-09 10:33:22.515  5615  5615 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
11-09 10:33:22.515  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
11-09 10:33:22.515  5615  5663 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
11-09 10:33:22.515  5615  5663 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
11-09 10:33:22.516  5615  5663 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
11-09 10:33:22.516  5615  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-09 10:33:22.516  5615  5670 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
11-09 10:33:22.516  5615  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
11-09 10:33:22.516  5615  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
11-09 10:33:22.516  5615  5670 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
11-09 10:33:22.516  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-09 10:33:22.517  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-62,5,main], id: 62
11-09 10:33:22.517  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-62,5,main], id: 62
11-09 10:33:22.518  5615  5663 D BluetoothAdapter: STATE_ON
11-09 10:33:22.519  5615  5663 D BluetoothLeScanner: could not find callback wrapper
11-09 10:33:22.519  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-09 10:33:22.519  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-62,5,main], id: 62
11-09 10:33:22.519  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-62,5,main], id: 62
11-09 10:33:22.519  5615  5663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
11-09 10:33:22.519  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-62,5,main], id: 62
11-09 10:33:22.521  4676  4738 D BtGatt.AdvertiseManager: message : 1
11-09 10:33:22.522  4676  4738 D BtGatt.AdvertiseManager: stop advertise for client 5
,11-09 10:33:22.534  4676  4736 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
,11-09 10:33:22.534  4676  4736 D BtGatt.GattService: Client app is not null!
11-09 10:33:22.535  4676  4688 D BtGatt.GattService: unregisterClient() - clientIf=5
11-09 10:33:22.536  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-09 10:33:22.536  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTEDCurrent thread: Thread[Thread-62,5,main], id: 62
11-09 10:33:22.536  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
11-09 10:33:22.536  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged false. Current thread: Thread[Thread-62,5,main], id: 62
11-09 10:33:22.537  5615  5663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: falseCurrent thread: Thread[Thread-62,5,main], id: 62
11-09 10:33:22.537  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[Thread-62,5,main], id: 62
11-09 10:33:22.537  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-09 10:33:22.537  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [ADVERTISING]
11-09 10:33:22.537  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[Thread-62,5,main], id: 62
,11-09 10:33:22.537  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]Current thread: Thread[Thread-62,5,main], id: 62
11-09 10:33:22.537  5615  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
11-09 10:33:22.537  5615  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-09 10:33:22.539  5615  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-09 10:33:22.539  5615  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-09 10:33:22.539  5615  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-09 10:33:22.539  5615  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-09 10:33:22.539  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[Thread-62,5,main], id: 62
11-09 10:33:22.539  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finishedCurrent thread: Thread[Thread-62,5,main], id: 62
11-09 10:33:22.539  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-62,5,main], id: 62
11-09 10:33:22.539  5615  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-09 10:33:22.540  5615  5663 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-09 10:33:22.540  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
11-09 10:33:22.541  5615  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
,11-09 10:33:22.542  5615  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-09 10:33:22.542  5615  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-09 10:33:22.542  5615  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
,11-09 10:33:22.542  5615  5615 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-09 10:33:22.543  5615  5615 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,11-09 10:33:22.543  5615  5615 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
,11-09 10:33:22.544  5615  5615 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-09 10:33:22.544  5615  5615 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
11-09 10:33:22.544  5615  5615 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-09 10:33:22.544  5615  5615 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-09 10:33:22.544  5615  5615 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-09 10:33:22.544  5615  5663 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
11-09 10:33:22.544  5615  5663 V io.jxcore.node.ConnectivityMonitor: start: Already started
11-09 10:33:22.544  5615  5663 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 2
11-09 10:33:22.544  5615  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 1 -> 2
11-09 10:33:22.544  5615  5663 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
11-09 10:33:22.544  5615  5663 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
11-09 10:33:22.544  5615  5663 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
11-09 10:33:22.544  5615  5663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,11-09 10:33:22.550  5615  5663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
11-09 10:33:22.550  5615  5663 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
11-09 10:33:22.550  5615  5663 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
11-09 10:33:22.550  5615  5663 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
,11-09 10:33:22.551  5615  5663 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
11-09 10:33:22.551  5615  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
,11-09 10:33:22.551  5615  5615 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
11-09 10:33:22.551  5615  5663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-09 10:33:22.551  5615  5663 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
11-09 10:33:22.551  5615  5673 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
11-09 10:33:22.552  5615  5673 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-09 10:33:22.554  5615  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-09 10:33:22.554  5615  5663 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,11-09 10:33:22.554  5615  5663 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
11-09 10:33:22.556  5615  5673 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
11-09 10:33:22.554  4688  4688 W Binder_1: type=1400 audit(0.0:115): avc: denied { ioctl } for path="socket:[29612]" dev="sockfs" ino=29612 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-09 10:33:22.554  4688  4688 W Binder_1: type=1400 audit(0.0:116): avc: denied { ioctl } for path="socket:[29612]" dev="sockfs" ino=29612 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,11-09 10:33:22.558  5615  5663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,11-09 10:33:22.559  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-09 10:33:22.559  5615  5663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-09 10:33:22.561  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Current thread: Thread[Thread-62,5,main], id: 62
11-09 10:33:22.561  5615  5663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
,11-09 10:33:22.561  5615  5663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-09 10:33:22.561  5615  5663 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 02 60 83 34 25 D7 D4
11-09 10:33:22.561  5615  5663 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[2, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-09 10:33:22.561  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: Current thread: Thread[Thread-62,5,main], id: 62
11-09 10:33:22.561  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData finished: Current thread: Thread[Thread-62,5,main], id: 62
11-09 10:33:22.561  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = NOT_STARTEDCurrent thread: Thread[Thread-62,5,main], id: 62
11-09 10:33:22.561  5615  5663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... adv data = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[2, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]Current thread: Thread[Thread-62,5,main], id: 62
11-09 10:33:22.563  5615  5663 D BluetoothAdapter: STATE_ON
,11-09 10:33:22.565  4676  4889 D BtGatt.GattService: registerClient() - UUID=394089b1-43e3-4afc-948d-2bd382e86538
,11-09 10:33:22.566  4676  4736 D BtGatt.GattService: onClientRegistered() - UUID=394089b1-43e3-4afc-948d-2bd382e86538, clientIf=5
11-09 10:33:22.566  5615  5626 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
,11-09 10:33:22.568  4676  4738 D BtGatt.AdvertiseManager: message : 0
,11-09 10:33:22.570  4676  4738 D BtGatt.AdvertiseManager: starting multi advertising
,11-09 10:33:22.581  4676  4736 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,11-09 10:33:22.588  4676  4736 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,11-09 10:33:22.588  5615  5663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment Current thread: Thread[Thread-62,5,main], id: 62
,11-09 10:33:22.588  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTINGCurrent thread: Thread[Thread-62,5,main], id: 62
11-09 10:33:22.588  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
11-09 10:33:22.588  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged default (no call to listener). Current thread: Thread[Thread-62,5,main], id: 62
11-09 10:33:22.589  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finishedCurrent thread: Thread[Thread-62,5,main], id: 62
,11-09 10:33:22.589  5615  5663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[Thread-62,5,main], id: 62
11-09 10:33:22.589  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[Thread-62,5,main], id: 62
11-09 10:33:22.589  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser started = trueCurrent thread: Thread[Thread-62,5,main], id: 62
11-09 10:33:22.589  5615  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-09 10:33:22.590  5615  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-09 10:33:22.590  5615  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-09 10:33:22.591  5615  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-09 10:33:22.591  5615  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
,11-09 10:33:22.592  5615  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-09 10:33:22.592  5615  5663 I io.jxcore.node.ConnectionHelper: start: OK
11-09 10:33:22.592  5615  5615 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,11-09 10:33:22.592  5615  5615 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess : Current thread: Thread[main,5,main], id: 1
11-09 10:33:22.592  5615  5615 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNINGCurrent thread: Thread[main,5,main], id: 1
11-09 10:33:22.592  5615  5615 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
,11-09 10:33:22.592  5615  5615 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged true. Current thread: Thread[main,5,main], id: 1
11-09 10:33:22.592  5615  5615 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-09 10:33:22.593  5615  5615 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-09 10:33:22.593  5615  5615 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [ADVERTISING]
11-09 10:33:22.593  5615  5615 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-09 10:33:22.593  5615  5615 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
,11-09 10:33:22.593  5615  5615 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]Current thread: Thread[main,5,main], id: 1
11-09 10:33:22.593  5615  5615 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
11-09 10:33:22.593  5615  5615 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-09 10:33:22.595  5615  5615 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-09 10:33:22.595  5615  5615 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
11-09 10:33:22.596  5615  5615 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
,11-09 10:33:22.596  5615  5615 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-09 10:33:22.596  5615  5615 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-09 10:33:22.596  5615  5615 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finishedCurrent thread: Thread[main,5,main], id: 1
11-09 10:33:22.596  5615  5615 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,11-09 10:33:23.096  5615  5663 I io.jxcore.node.ConnectionHelperTest: Starting test: testStop
11-09 10:33:23.096  5615  5663 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
11-09 10:33:23.097  5615  5663 V io.jxcore.node.ConnectivityMonitor: start: Already started
11-09 10:33:23.097  5615  5663 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,11-09 10:33:23.097  5615  5663 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 3
11-09 10:33:23.097  5615  5615 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
11-09 10:33:23.097  5615  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 2 -> 3
11-09 10:33:23.098  5615  5663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
11-09 10:33:23.098  5615  5663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Manufacturer ID: 7413
11-09 10:33:23.098  5615  5663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad length and type: 533
11-09 10:33:23.098  5615  5663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad extra information: 3
11-09 10:33:23.098  5615  5663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
11-09 10:33:23.098  5615  5663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 2
11-09 10:33:23.098  5615  5663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 3
11-09 10:33:23.098  5615  5663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 2
11-09 10:33:23.098  5615  5663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
11-09 10:33:23.098  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-62,5,main], id: 62
11-09 10:33:23.101  4676  4738 D BtGatt.AdvertiseManager: message : 1
11-09 10:33:23.102  4676  4738 D BtGatt.AdvertiseManager: stop advertise for client 5
,11-09 10:33:23.115  4676  4736 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
11-09 10:33:23.116  4676  4736 D BtGatt.GattService: Client app is not null!
11-09 10:33:23.117  4676  4689 D BtGatt.GattService: unregisterClient() - clientIf=5
11-09 10:33:23.117  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-09 10:33:23.118  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTEDCurrent thread: Thread[Thread-62,5,main], id: 62
11-09 10:33:23.118  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
11-09 10:33:23.118  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finishedCurrent thread: Thread[Thread-62,5,main], id: 62
11-09 10:33:23.118  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-62,5,main], id: 62
,11-09 10:33:23.118  5615  5663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,11-09 10:33:23.118  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Current thread: Thread[Thread-62,5,main], id: 62
11-09 10:33:23.118  5615  5663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
11-09 10:33:23.119  5615  5663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-09 10:33:23.119  5615  5663 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 03 60 83 34 25 D7 D4
11-09 10:33:23.119  5615  5663 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[3, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-09 10:33:23.119  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: Current thread: Thread[Thread-62,5,main], id: 62
,11-09 10:33:23.119  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData finished: Current thread: Thread[Thread-62,5,main], id: 62
,11-09 10:33:23.119  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = NOT_STARTEDCurrent thread: Thread[Thread-62,5,main], id: 62
11-09 10:33:23.120  5615  5663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... adv data = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[3, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]Current thread: Thread[Thread-62,5,main], id: 62
,11-09 10:33:23.121  5615  5663 D BluetoothAdapter: STATE_ON
11-09 10:33:23.126  4676  4689 D BtGatt.GattService: registerClient() - UUID=b0a9d9ed-63d2-4c1e-a57f-1780e20007f0
11-09 10:33:23.127  4676  4736 D BtGatt.GattService: onClientRegistered() - UUID=b0a9d9ed-63d2-4c1e-a57f-1780e20007f0, clientIf=5
11-09 10:33:23.127  5615  5626 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
11-09 10:33:23.129  4676  4738 D BtGatt.AdvertiseManager: message : 0
,11-09 10:33:23.132  4676  4738 D BtGatt.AdvertiseManager: starting multi advertising
,11-09 10:33:23.147  4676  4736 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,11-09 10:33:23.155  4676  4736 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
11-09 10:33:23.156  5615  5663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment Current thread: Thread[Thread-62,5,main], id: 62
,11-09 10:33:23.156  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTINGCurrent thread: Thread[Thread-62,5,main], id: 62
11-09 10:33:23.156  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
11-09 10:33:23.156  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged default (no call to listener). Current thread: Thread[Thread-62,5,main], id: 62
11-09 10:33:23.156  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finishedCurrent thread: Thread[Thread-62,5,main], id: 62
11-09 10:33:23.156  5615  5663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[Thread-62,5,main], id: 62
11-09 10:33:23.156  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[Thread-62,5,main], id: 62
11-09 10:33:23.156  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser started = trueCurrent thread: Thread[Thread-62,5,main], id: 62
11-09 10:33:23.157  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-09 10:33:23.157  5615  5663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-09 10:33:23.157  5615  5663 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
,11-09 10:33:23.157  5615  5663 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-09 10:33:23.157  5615  5663 I io.jxcore.node.ConnectionHelper: start: OK
11-09 10:33:23.157  5615  5615 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess : Current thread: Thread[main,5,main], id: 1
,11-09 10:33:23.158  5615  5615 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNINGCurrent thread: Thread[main,5,main], id: 1
11-09 10:33:23.158  5615  5615 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
11-09 10:33:23.158  5615  5615 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged true. Current thread: Thread[main,5,main], id: 1
11-09 10:33:23.158  5615  5615 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-09 10:33:23.158  5615  5615 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-09 10:33:23.158  5615  5615 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [ADVERTISING]
,11-09 10:33:23.158  5615  5615 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [ADVERTISING]
11-09 10:33:23.158  5615  5615 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-09 10:33:23.158  5615  5615 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-09 10:33:23.158  5615  5615 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finishedCurrent thread: Thread[main,5,main], id: 1
,11-09 10:33:23.159  5615  5663 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-09 10:33:23.159  5615  5663 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
11-09 10:33:23.159  5615  5663 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
11-09 10:33:23.159  5615  5663 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
11-09 10:33:23.159  5615  5663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
11-09 10:33:23.159  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
,11-09 10:33:23.159  5615  5673 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
11-09 10:33:23.159  5615  5673 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
11-09 10:33:23.159  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
11-09 10:33:23.159  5615  5673 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
11-09 10:33:23.159  5615  5663 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
11-09 10:33:23.160  5615  5663 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
11-09 10:33:23.160  5615  5663 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
11-09 10:33:23.160  5615  5615 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,11-09 10:33:23.160  5615  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-09 10:33:23.160  5615  5615 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-09 10:33:23.160  5615  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
11-09 10:33:23.160  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-09 10:33:23.160  5615  5615 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
11-09 10:33:23.160  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-62,5,main], id: 62
11-09 10:33:23.160  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-62,5,main], id: 62
,11-09 10:33:23.161  5615  5663 D BluetoothAdapter: STATE_ON
11-09 10:33:23.161  5615  5663 D BluetoothLeScanner: could not find callback wrapper
11-09 10:33:23.161  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-09 10:33:23.161  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-62,5,main], id: 62
11-09 10:33:23.161  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-62,5,main], id: 62
11-09 10:33:23.161  5615  5663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
11-09 10:33:23.161  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-62,5,main], id: 62
11-09 10:33:23.162  4676  4738 D BtGatt.AdvertiseManager: message : 1
11-09 10:33:23.163  4676  4738 D BtGatt.AdvertiseManager: stop advertise for client 5
,11-09 10:33:23.170  4676  4736 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
,11-09 10:33:23.170  4676  4736 D BtGatt.GattService: Client app is not null!
,11-09 10:33:23.171  4676  4689 D BtGatt.GattService: unregisterClient() - clientIf=5
11-09 10:33:23.171  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-09 10:33:23.171  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTEDCurrent thread: Thread[Thread-62,5,main], id: 62
,11-09 10:33:23.171  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
11-09 10:33:23.171  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged false. Current thread: Thread[Thread-62,5,main], id: 62
11-09 10:33:23.171  5615  5663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: falseCurrent thread: Thread[Thread-62,5,main], id: 62
11-09 10:33:23.172  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[Thread-62,5,main], id: 62
11-09 10:33:23.172  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-09 10:33:23.172  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [ADVERTISING]
11-09 10:33:23.172  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[Thread-62,5,main], id: 62
11-09 10:33:23.172  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]Current thread: Thread[Thread-62,5,main], id: 62
11-09 10:33:23.172  5615  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
11-09 10:33:23.172  5615  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
,11-09 10:33:23.173  5615  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-09 10:33:23.173  5615  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-09 10:33:23.174  5615  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-09 10:33:23.174  5615  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-09 10:33:23.174  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[Thread-62,5,main], id: 62
11-09 10:33:23.174  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finishedCurrent thread: Thread[Thread-62,5,main], id: 62
11-09 10:33:23.174  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-62,5,main], id: 62
11-09 10:33:23.174  5615  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-09 10:33:23.174  5615  5663 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-09 10:33:23.175  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
11-09 10:33:23.175  5615  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
,11-09 10:33:23.176  5615  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-09 10:33:23.176  5615  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-09 10:33:23.176  5615  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-09 10:33:23.176  5615  5615 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-09 10:33:23.176  5615  5615 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
11-09 10:33:23.176  5615  5615 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-09 10:33:23.176  5615  5615 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-09 10:33:23.176  5615  5615 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,11-09 10:33:23.178  5615  5663 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnPeerReadyToProvideBluetoothMacAddress
11-09 10:33:23.178  5615  5663 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
,11-09 10:33:23.180  5615  5663 I io.jxcore.node.ConnectionHelperTest: Starting test: testKillAllConnections
,11-09 10:33:23.180  5615  5663 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
,11-09 10:33:23.181  5615  5663 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnConnectionManagerStateChanged
11-09 10:33:23.182  5615  5663 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
,11-09 10:33:23.183  5615  5663 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnPermissionCheckRequired
,11-09 10:33:23.183  5615  5663 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
11-09 10:33:23.184  5615  5663 I io.jxcore.node.ConnectionHelperTest: Starting test: testToggleBetweenSystemDecidedAndAlternativeInsecureRfcommPortNumber
11-09 10:33:23.184  5615  5663 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
11-09 10:33:23.184  5615  5663 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-09 10:33:23.184  5615  5663 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-09 10:33:23.184  5615  5663 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-09 10:33:23.184  5615  5663 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
11-09 10:33:23.184  5615  5663 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-09 10:33:23.184  5615  5663 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-09 10:33:23.184  5615  5663 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-09 10:33:23.184  5615  5663 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
11-09 10:33:23.184  5615  5663 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-09 10:33:23.184  5615  5663 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-09 10:33:23.185  5615  5663 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-09 10:33:23.185  5615  5663 I io.jxcore.node.ConnectionHelperTest: Starting test: testConnect
11-09 10:33:23.185  5615  5663 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
11-09 10:33:23.186  5615  5663 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
11-09 10:33:23.190  5615  5663 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnProvideBluetoothMacAddressRequest
11-09 10:33:23.190  5615  5663 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
11-09 10:33:23.191  5615  5663 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnDiscoveryManagerStateChanged
11-09 10:33:23.191  5615  5663 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
11-09 10:33:23.192  5615  5663 I io.jxcore.node.ConnectionHelperTest: Starting test: testDisconnectOutgoingConnection
11-09 10:33:23.192  5615  5663 E io.jxcore.node.ConnectionModel: addConnectionThread: A matching thread for outgoing connection already exists
11-09 10:33:23.192  5615  5663 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
11-09 10:33:23.192  5615  5663 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
11-09 10:33:23.192  5615  5663 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
11-09 10:33:23.192  5615  5663 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
11-09 10:33:23.192  5615  5663 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
11-09 10:33:23.192  5615  5663 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
11-09 10:33:23.192  5615  5663 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
11-09 10:33:23.192  5615  5663 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
11-09 10:33:23.192  5615  5663 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
11-09 10:33:23.193  5615  5663 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
11-09 10:33:23.193  5615  5663 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
11-09 10:33:23.193  5615  5663 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
11-09 10:33:23.194  5615  5663 I io.jxcore.node.ConnectionHelperTest: Starting test: testDispose
11-09 10:33:23.194  5615  5663 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
11-09 10:33:23.194  5615  5663 V io.jxcore.node.ConnectivityMonitor: start: Already started
11-09 10:33:23.194  5615  5663 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 4
11-09 10:33:23.194  5615  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 3 -> 4
11-09 10:33:23.194  5615  5663 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
11-09 10:33:23.194  5615  5663 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
11-09 10:33:23.194  5615  5663 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
11-09 10:33:23.194  5615  5663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-09 10:33:23.196  5615  5663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
11-09 10:33:23.196  5615  5663 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
11-09 10:33:23.196  5615  5663 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
11-09 10:33:23.196  5615  5663 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
11-09 10:33:23.196  5615  5663 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
11-09 10:33:23.196  5615  5677 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
11-09 10:33:23.197  5615  5615 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
11-09 10:33:23.197  5615  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
11-09 10:33:23.197  5615  5663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-09 10:33:23.197  5615  5663 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
11-09 10:33:23.197  5615  5677 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-09 10:33:23.197  4689  4689 W Binder_2: type=1400 audit(0.0:117): avc: denied { ioctl } for path="socket:[32187]" dev="sockfs" ino=32187 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-09 10:33:23.197  4689  4689 W Binder_2: type=1400 audit(0.0:118): avc: denied { ioctl } for path="socket:[32187]" dev="sockfs" ino=32187 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-09 10:33:23.200  5615  5677 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,11-09 10:33:23.203  5615  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-09 10:33:23.203  5615  5663 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-09 10:33:23.203  5615  5663 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
11-09 10:33:23.207  5615  5663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-09 10:33:23.209  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-09 10:33:23.209  5615  5663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-09 10:33:23.210  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Current thread: Thread[Thread-62,5,main], id: 62
11-09 10:33:23.211  5615  5663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
11-09 10:33:23.211  5615  5663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-09 10:33:23.211  5615  5663 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 04 60 83 34 25 D7 D4
11-09 10:33:23.211  5615  5663 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[4, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-09 10:33:23.211  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: Current thread: Thread[Thread-62,5,main], id: 62
11-09 10:33:23.211  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData finished: Current thread: Thread[Thread-62,5,main], id: 62
11-09 10:33:23.211  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = NOT_STARTEDCurrent thread: Thread[Thread-62,5,main], id: 62
11-09 10:33:23.211  5615  5663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... adv data = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[4, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]Current thread: Thread[Thread-62,5,main], id: 62
11-09 10:33:23.212  5615  5663 D BluetoothAdapter: STATE_ON
11-09 10:33:23.214  4676  4689 D BtGatt.GattService: registerClient() - UUID=f0ecf7ea-4e3a-4190-aa5e-ac471151f8dd
11-09 10:33:23.214  4676  4736 D BtGatt.GattService: onClientRegistered() - UUID=f0ecf7ea-4e3a-4190-aa5e-ac471151f8dd, clientIf=5
11-09 10:33:23.215  5615  5625 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
,11-09 10:33:23.216  4676  4738 D BtGatt.AdvertiseManager: message : 0
,11-09 10:33:23.217  4676  4738 D BtGatt.AdvertiseManager: starting multi advertising
,11-09 10:33:23.226  4676  4736 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,11-09 10:33:23.231  4676  4736 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,11-09 10:33:23.233  5615  5663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment Current thread: Thread[Thread-62,5,main], id: 62
11-09 10:33:23.233  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTINGCurrent thread: Thread[Thread-62,5,main], id: 62
,11-09 10:33:23.233  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
11-09 10:33:23.233  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged default (no call to listener). Current thread: Thread[Thread-62,5,main], id: 62
11-09 10:33:23.233  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finishedCurrent thread: Thread[Thread-62,5,main], id: 62
11-09 10:33:23.233  5615  5663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[Thread-62,5,main], id: 62
11-09 10:33:23.233  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[Thread-62,5,main], id: 62
11-09 10:33:23.233  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser started = trueCurrent thread: Thread[Thread-62,5,main], id: 62
11-09 10:33:23.233  5615  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-09 10:33:23.234  5615  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-09 10:33:23.234  5615  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-09 10:33:23.235  5615  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-09 10:33:23.235  5615  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-09 10:33:23.235  5615  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-09 10:33:23.235  5615  5663 I io.jxcore.node.ConnectionHelper: start: OK
11-09 10:33:23.235  5615  5615 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
11-09 10:33:23.236  5615  5615 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess : Current thread: Thread[main,5,main], id: 1
11-09 10:33:23.236  5615  5615 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNINGCurrent thread: Thread[main,5,main], id: 1
11-09 10:33:23.236  5615  5615 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
11-09 10:33:23.236  5615  5615 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged true. Current thread: Thread[main,5,main], id: 1
11-09 10:33:23.236  5615  5615 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
,11-09 10:33:23.236  5615  5615 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-09 10:33:23.236  5615  5615 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [ADVERTISING]
11-09 10:33:23.236  5615  5615 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-09 10:33:23.236  5615  5615 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-09 10:33:23.236  5615  5615 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]Current thread: Thread[main,5,main], id: 1
11-09 10:33:23.236  5615  5615 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
11-09 10:33:23.236  5615  5615 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-09 10:33:23.238  5615  5615 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-09 10:33:23.238  5615  5615 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
11-09 10:33:23.238  5615  5615 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-09 10:33:23.239  5615  5615 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-09 10:33:23.239  5615  5615 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-09 10:33:23.239  5615  5615 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finishedCurrent thread: Thread[main,5,main], id: 1
11-09 10:33:23.239  5615  5615 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,11-09 10:33:23.736  5615  5663 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,11-09 10:33:23.736  5615  5663 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
11-09 10:33:23.737  5615  5663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
11-09 10:33:23.737  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
11-09 10:33:23.737  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
11-09 10:33:23.737  5615  5677 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
11-09 10:33:23.737  5615  5663 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
,11-09 10:33:23.737  5615  5677 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
11-09 10:33:23.738  5615  5663 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
11-09 10:33:23.738  5615  5677 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
11-09 10:33:23.738  5615  5663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-09 10:33:23.738  5615  5615 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
,11-09 10:33:23.739  5615  5663 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8df729c removed from the list
11-09 10:33:23.739  5615  5615 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
11-09 10:33:23.739  5615  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-09 10:33:23.739  5615  5615 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-09 10:33:23.739  5615  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,11-09 10:33:23.739  5615  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
11-09 10:33:23.739  5615  5615 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
11-09 10:33:23.739  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-09 10:33:23.739  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-62,5,main], id: 62
,11-09 10:33:23.740  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-62,5,main], id: 62
11-09 10:33:23.741  5615  5663 D BluetoothAdapter: STATE_ON
11-09 10:33:23.741  5615  5663 D BluetoothLeScanner: could not find callback wrapper
11-09 10:33:23.742  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-09 10:33:23.742  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-62,5,main], id: 62
,11-09 10:33:23.742  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-62,5,main], id: 62
11-09 10:33:23.742  5615  5663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
,11-09 10:33:23.743  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-62,5,main], id: 62
11-09 10:33:23.744  4676  4738 D BtGatt.AdvertiseManager: message : 1
11-09 10:33:23.747  4676  4738 D BtGatt.AdvertiseManager: stop advertise for client 5
,11-09 10:33:23.761  4676  4736 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
11-09 10:33:23.761  4676  4736 D BtGatt.GattService: Client app is not null!
,11-09 10:33:23.763  4676  4908 D BtGatt.GattService: unregisterClient() - clientIf=5
,11-09 10:33:23.764  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-09 10:33:23.764  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTEDCurrent thread: Thread[Thread-62,5,main], id: 62
11-09 10:33:23.765  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
,11-09 10:33:23.765  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged false. Current thread: Thread[Thread-62,5,main], id: 62
11-09 10:33:23.765  5615  5663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: falseCurrent thread: Thread[Thread-62,5,main], id: 62
11-09 10:33:23.765  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[Thread-62,5,main], id: 62
11-09 10:33:23.765  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-09 10:33:23.766  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [ADVERTISING]
11-09 10:33:23.766  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[Thread-62,5,main], id: 62
11-09 10:33:23.766  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]Current thread: Thread[Thread-62,5,main], id: 62
,11-09 10:33:23.767  5615  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
11-09 10:33:23.767  5615  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
,11-09 10:33:23.770  5615  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-09 10:33:23.770  5615  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-09 10:33:23.771  5615  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-09 10:33:23.771  5615  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-09 10:33:23.771  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[Thread-62,5,main], id: 62
11-09 10:33:23.771  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finishedCurrent thread: Thread[Thread-62,5,main], id: 62
11-09 10:33:23.771  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-62,5,main], id: 62
11-09 10:33:23.771  5615  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-09 10:33:23.772  5615  5663 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-09 10:33:23.773  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,11-09 10:33:23.773  5615  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-09 10:33:23.776  5615  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-09 10:33:23.776  5615  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
,11-09 10:33:23.777  5615  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-09 10:33:23.777  5615  5663 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cb784a5 removed from the list
11-09 10:33:23.777  5615  5615 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-09 10:33:23.777  5615  5663 D io.jxcore.node.ConnectivityMonitor: stop
11-09 10:33:23.777  5615  5615 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-09 10:33:23.777  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-09 10:33:23.777  5615  5615 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,11-09 10:33:24.278  5615  5615 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-09 10:33:28.781  5615  5663 I io.jxcore.node.ConnectionHelperTest: Starting test: testIsRunning
,11-09 10:33:28.787  5615  5663 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
,11-09 10:33:28.788  5615  5663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-09 10:33:28.789  5615  5663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,11-09 10:33:28.790  5615  5663 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,11-09 10:33:28.791  5615  5663 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
11-09 10:33:28.791  5615  5663 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
11-09 10:33:28.791  5615  5678 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
11-09 10:33:28.791  5615  5615 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
11-09 10:33:28.792  5615  5663 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
,11-09 10:33:28.792  5615  5663 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
11-09 10:33:28.793  5615  5678 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-09 10:33:28.795  5615  5663 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnConnectionFailed
11-09 10:33:28.796  5615  5663 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
,11-09 10:33:28.797  5615  5663 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
,11-09 10:33:28.797  5615  5663 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
11-09 10:33:28.797  5615  5663 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-09 10:33:28.797  5615  5663 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-09 10:33:28.799  5615  5678 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
11-09 10:33:28.797  4908  4908 W Binder_4: type=1400 audit(0.0:119): avc: denied { ioctl } for path="socket:[31371]" dev="sockfs" ino=31371 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,11-09 10:33:28.797  4908  4908 W Binder_4: type=1400 audit(0.0:120): avc: denied { ioctl } for path="socket:[31371]" dev="sockfs" ino=31371 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,11-09 10:33:28.802  5615  5663 I io.jxcore.node.ConnectionHelperTest: Starting test: testGetConnectivityMonitorGetDiscoveryManagerGetConnectionModelGetBluetoothName
,11-09 10:33:28.811  5615  5663 I io.jxcore.node.ConnectionHelperTest: Starting test: testConstructor
,11-09 10:33:28.812  5615  5663 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,11-09 10:33:28.812  5615  5663 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
11-09 10:33:28.812  5615  5663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
11-09 10:33:28.812  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
,11-09 10:33:28.812  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-09 10:33:28.812  5615  5678 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
11-09 10:33:28.812  5615  5678 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
11-09 10:33:28.812  5615  5663 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
11-09 10:33:28.813  5615  5678 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
11-09 10:33:28.813  5615  5663 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
11-09 10:33:28.813  5615  5615 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,11-09 10:33:28.813  5615  5615 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-09 10:33:28.813  5615  5663 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8df729c not in the list
11-09 10:33:28.813  5615  5615 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
11-09 10:33:28.813  5615  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-09 10:33:28.813  5615  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-09 10:33:28.813  5615  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
11-09 10:33:28.813  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,11-09 10:33:28.813  5615  5663 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-09 10:33:28.813  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-09 10:33:28.813  5615  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
,11-09 10:33:28.816  5615  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-09 10:33:28.816  5615  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-09 10:33:28.816  5615  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-09 10:33:28.816  5615  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-09 10:33:28.816  5615  5615 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,11-09 10:33:28.816  5615  5663 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cb784a5 not in the list
11-09 10:33:28.816  5615  5615 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-09 10:33:28.816  5615  5663 D io.jxcore.node.ConnectivityMonitor: stop
11-09 10:33:28.817  5615  5663 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-09 10:33:28.817  5615  5615 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-09 10:33:28.817  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-09 10:33:28.819  5615  5663 I io.jxcore.node.ConnectionModelTest: Starting test: testGetNumberOfCurrentOutgoingConnections
11-09 10:33:28.819  5615  5663 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
,11-09 10:33:28.819  5615  5663 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
11-09 10:33:28.819  5615  5663 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
11-09 10:33:28.819  5615  5663 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
11-09 10:33:28.819  5615  5663 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
11-09 10:33:28.819  5615  5663 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
11-09 10:33:28.820  5615  5663 I io.jxcore.node.ConnectionModelTest: Starting test: constructorTest
,11-09 10:33:28.821  5615  5663 I io.jxcore.node.ConnectionModelTest: Starting test: testHasIncomingConnection
,11-09 10:33:28.823  5615  5663 I io.jxcore.node.ConnectionModelTest: Starting test: testGetNumberOfCurrentConnections
,11-09 10:33:28.824  5615  5663 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
11-09 10:33:28.824  5615  5663 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
11-09 10:33:28.824  5615  5663 I io.jxcore.node.ConnectionModelTest: Starting test: testGetNumberOfCurrentIncomingConnections
11-09 10:33:28.825  5615  5663 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
11-09 10:33:28.825  5615  5663 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
11-09 10:33:28.825  5615  5663 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
,11-09 10:33:28.826  5615  5663 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
11-09 10:33:28.826  5615  5663 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
11-09 10:33:28.826  5615  5663 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
,11-09 10:33:28.827  5615  5663 I io.jxcore.node.ConnectionModelTest: Starting test: testGetOutgoingConnectionCallbackByBluetoothMacAddress
,11-09 10:33:28.827  5615  5663 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
11-09 10:33:28.827  5615  5663 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
11-09 10:33:28.828  5615  5663 I io.jxcore.node.ConnectionModelTest: Starting test: testHasConnection
11-09 10:33:28.828  5615  5663 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
,11-09 10:33:28.829  5615  5663 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
11-09 10:33:28.829  5615  5663 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
11-09 10:33:28.829  5615  5663 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
,11-09 10:33:28.830  5615  5663 I io.jxcore.node.ConnectionModelTest: Starting test: testHasOutgoingConnection
11-09 10:33:28.830  5615  5663 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-09 10:33:28.830  5615  5663 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6cbe115 added. We now have 3 listener(s)
,11-09 10:33:28.832  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-09 10:33:28.832  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-09 10:33:28.832  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-09 10:33:28.832  5615  5663 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-09 10:33:28.832  5615  5663 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ea16c2a added. We now have 3 listener(s)
11-09 10:33:28.832  5615  5663 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-09 10:33:28.833  5615  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,11-09 10:33:28.836  5615  5663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,11-09 10:33:28.840  5615  5663 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-09 10:33:28.840  5615  5663 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-09 10:33:28.840  5615  5663 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-09 10:33:28.840  5615  5663 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-09 10:33:28.840  5615  5663 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-09 10:33:28.840  5615  5663 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-09 10:33:28.840  5615  5663 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-09 10:33:28.840  5615  5663 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
11-09 10:33:28.841  5615  5663 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
11-09 10:33:28.841  5615  5663 D io.jxcore.node.ConnectivityMonitor: start: OK
,11-09 10:33:28.844  5615  5615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-09 10:33:28.844  5615  5663 D BluetoothAdapter: enable(): BT is already enabled..!
11-09 10:33:28.844   931  3770 D WifiService: setWifiEnabled: true pid=5615, uid=10077
,11-09 10:33:28.844   931  3770 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-09 10:33:28.846  5615  5663 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testIsBleMultipleAdvertisementSupported
,11-09 10:33:28.847  5615  5615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-09 10:33:28.849  5615  5663 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testIsBluetoothSupported
,11-09 10:33:28.849  5615  5663 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testStartStop
,11-09 10:33:28.852   931  3770 D WifiService: setWifiEnabled: false pid=5615, uid=10077
,11-09 10:33:28.852   931  3770 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-09 10:33:28.854   931  2957 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,11-09 10:33:28.854   931  2957 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
11-09 10:33:28.854   931  2957 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
11-09 10:33:28.855   931  2957 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-09 10:33:28.862   931  5392 D DhcpClient: Clearing IP address
11-09 10:33:28.862   511   925 D CommandListener: Clearing all IP addresses on wlan0
,11-09 10:33:28.870   511   925 D CommandListener: Setting iface cfg
,11-09 10:33:28.872  3589  5458 V NativeCrypto: Read error: ssl=0x7f8a6cf600: I/O error during system call, Connection timed out
,11-09 10:33:28.873  3589  5458 V NativeCrypto: SSL shutdown failed: ssl=0x7f8a6cf600: I/O error during system call, Broken pipe
11-09 10:33:28.875   931  3428 D ConnectivityService: reportNetworkConnectivity(100, false) by 10012
11-09 10:33:28.876   931  5390 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Forcing reevaluation for UID 10012
,11-09 10:33:28.878   931  5390 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.gstatic.com": No address associated with hostname
,11-09 10:33:28.879   931  2959 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
11-09 10:33:28.879   931  2959 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] validation failed
11-09 10:33:28.879   931  2959 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,11-09 10:33:28.880   931  2959 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
11-09 10:33:28.883   538   538 E Parcel  : Reading a NULL string not supported here.
11-09 10:33:28.884   931   931 D RttService: SCAN_AVAILABLE : 1
11-09 10:33:28.885   931  3065 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,11-09 10:33:28.886   931  2959 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
,11-09 10:33:28.888   931  4826 I ActivityManager: Killing 5279:com.android.settings/1000 (adj 15): empty #17
,11-09 10:33:28.892   931  5393 D DhcpClient: Receive thread stopped
,11-09 10:33:28.899   931  2957 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,11-09 10:33:28.921   931  2959 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
11-09 10:33:28.922  3732  3848 W QCNEJ   : |CORE| network lost: 100
,11-09 10:33:28.923  3732  3848 W QCNEJ   : |CORE| onLost: unbind the process to WIFI
11-09 10:33:28.924   931  2957 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,11-09 10:33:28.942   511   925 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-09 10:33:28.960   511   925 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-09 10:33:28.961   931  2959 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
11-09 10:33:28.961   511   925 D CommandListener: Clearing all IP addresses on wlan0
11-09 10:33:28.962   931  2959 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,11-09 10:33:28.962   511   925 D TetherController: Setting IP forward enable = 0
,11-09 10:33:28.963   931   948 D Tethering: MasterInitialState.processMessage what=3
11-09 10:33:28.968  3963  3963 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
,11-09 10:33:28.967  5294  5294 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@352b876 and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
11-09 10:33:28.970   931  2957 D DhcpClient: doQuit
11-09 10:33:28.970   931  2957 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
11-09 10:33:28.971  5615  5615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-09 10:33:28.971  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-09 10:33:28.971  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-09 10:33:28.971  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-09 10:33:28.971  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-09 10:33:28.971  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-09 10:33:28.971  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-09 10:33:28.971  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,11-09 10:33:28.971   931  5392 D DhcpClient: onQuitting
11-09 10:33:28.973  3457  3457 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
11-09 10:33:28.973  4045  4045 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
11-09 10:33:28.978  5615  5615 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,11-09 10:33:28.980  4045  4045 D SystemUpdateService: onCreate
,11-09 10:33:28.984  5615  5615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-09 10:33:28.984  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-09 10:33:28.984  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-09 10:33:28.984  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-09 10:33:28.984  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-09 10:33:28.984  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-09 10:33:28.984  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-09 10:33:28.984  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,11-09 10:33:28.986  4045  4045 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,11-09 10:33:28.989  5615  5615 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
11-09 10:33:28.989  4045  5693 I SystemUpdateService: active receiver: enabled
,11-09 10:33:28.994  5615  5615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-09 10:33:28.994  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-09 10:33:28.994  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-09 10:33:28.994  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-09 10:33:28.994  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-09 10:33:28.994  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-09 10:33:28.994  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-09 10:33:28.994  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,11-09 10:33:28.994  4045  4045 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,11-09 10:33:28.997  5615  5615 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,11-09 10:33:28.998  3457  3457 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
,11-09 10:33:29.001  4045  4254 I iu.UploadsManager: num queued entries: 0
11-09 10:33:29.001  3457  3457 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
11-09 10:33:29.001  4045  4254 I iu.UploadsManager: num updated entries: 0
11-09 10:33:29.002  5615  5615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-09 10:33:29.002  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-09 10:33:29.002  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-09 10:33:29.002  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-09 10:33:29.002  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-09 10:33:29.002  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-09 10:33:29.002  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-09 10:33:29.002  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-09 10:33:29.003  4045  5693 I SystemUpdateService: Already downloaded, skipping offpeak checks.
11-09 10:33:29.005  4045  4045 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
11-09 10:33:29.006  5615  5615 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,11-09 10:33:29.006  4045  4045 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
11-09 10:33:29.007  5615  5615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-09 10:33:29.009  5615  5615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-09 10:33:29.009  5418  5418 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
11-09 10:33:29.014  5418  5418 D SprintDMHelper: simOperator: 
11-09 10:33:29.014  5418  5418 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,11-09 10:33:29.026  4045  5693 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,11-09 10:33:29.026  4045  5693 I SystemUpdateService: now status is 0 (complete)
11-09 10:33:29.026  4045  5693 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
11-09 10:33:29.027  4045  4254 I iu.SyncManager: NEXT; no task
11-09 10:33:29.026  4045  5693 I SystemUpdateService: file has been verified
11-09 10:33:29.028  4045  5693 I SystemUpdateService: OTA package size = 21989297
,11-09 10:33:29.034   511   925 E Netd    : netlink response contains error (No such file or directory)
,11-09 10:33:29.035   511   925 D TetherController: Setting IP forward enable = 0
11-09 10:33:29.035   931  2959 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
11-09 10:33:29.035  4045  5693 I SystemUpdateService: showing system update notification
,11-09 10:33:29.040   931  4826 I ActivityManager: Start proc 5702:com.google.android.apps.gcs/u0a11 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,11-09 10:33:29.051  3457  3457 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,11-09 10:33:29.052   931   931 V NotificationService: pkg=com.google.android.gms canInterrupt=false intercept=true
,11-09 10:33:29.054  4045  4045 D SystemUpdateService: onDestroy
,11-09 10:33:29.070  3457  3457 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,11-09 10:33:29.082  5702  5702 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm64
,11-09 10:33:29.089   931  3429 I ActivityManager: Killing 5077:com.google.android.apps.maps/u0a58 (adj 15): empty #17
,11-09 10:33:29.174   931  2957 D wifi    : In wifi stop Hal
,11-09 10:33:29.174   931  2957 D wifi    : halHandle = 0x7f88adbe00, mVM = 0x7fa514d140, mCls = 0x100a02
11-09 10:33:29.174   931  3456 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
11-09 10:33:29.174   931  3456 D WifiHAL : Got a signal to exit!!!
11-09 10:33:29.174   931  3456 I WifiHAL : Exit wifi_event_loop
11-09 10:33:29.174  4527  4527 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
11-09 10:33:29.175  3930  4187 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,11-09 10:33:29.177  5615  5615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-09 10:33:29.177   931  2957 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 0
11-09 10:33:29.177   931  2957 E WifiHAL : Event processing terminated
11-09 10:33:29.177   931  2957 D wifi    : In wifi cleaned up handler
11-09 10:33:29.177   931  2957 I WifiHAL : Internal cleanup completed
,11-09 10:33:29.179  5615  5615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-09 10:33:29.180  5615  5615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-09 10:33:29.206   931  3456 D wifi    : set interface wlan0 flags (DOWN)
11-09 10:33:29.207   931  2957 D WifiNative-HAL: HAL event thread stopped successfully
,11-09 10:33:29.317  5615  5615 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-09 10:33:29.356  5615  5679 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-09 10:33:29.359   931  3156 D WifiService: setWifiEnabled: true pid=5615, uid=10077
,11-09 10:33:29.360   931  3156 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-09 10:33:29.410   511   925 D SoftapController: Softap fwReload - Ok
,11-09 10:33:29.411   931   948 D Tethering: InitialState.processMessage what=4
,11-09 10:33:29.416   511   925 D CommandListener: Setting iface cfg
,11-09 10:33:29.416   511   925 D CommandListener: Trying to bring down wlan0
11-09 10:33:29.418   511   925 D CommandListener: Clearing all IP addresses on wlan0
11-09 10:33:29.418   931   948 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,11-09 10:33:29.423   931  2957 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,11-09 10:33:29.867   931  3814 D WifiService: setWifiEnabled: true pid=5615, uid=10077
,11-09 10:33:29.870   931  3814 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-09 10:33:30.033   931  2957 D wifi    : set interface wlan0 flags (UP)
,11-09 10:33:30.033   931  2957 I WifiHAL : Initializing wifi
11-09 10:33:30.033   931  2957 I WifiHAL : Creating socket
,11-09 10:33:30.039   931   948 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,11-09 10:33:30.044   931  2957 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
,11-09 10:33:30.044   931  2957 D wifi    : Did set static halHandle = 0x7f88adbe00
,11-09 10:33:30.044   931  2957 D wifi    : halHandle = 0x7f88adbe00, mVM = 0x7fa514d140, mCls = 0x101792
11-09 10:33:30.045   931  2957 D wifi    : array field set
11-09 10:33:30.045   931  2957 I WifiNative-HAL: interface[0] = wlan0
,11-09 10:33:30.048   931  5719 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=547753934336
11-09 10:33:30.049   931  5719 D wifi    : waitForHalEvents called, vm = 0x7fa514d140, obj = 0x101792, env = 0x7f88ae8a00
,11-09 10:33:30.111  5720  5720 I wpa_supplicant: Successfully initialized wpa_supplicant
,11-09 10:33:30.153   931  2957 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,11-09 10:33:30.157  5615  5615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-09 10:33:30.159  5615  5615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-09 10:33:30.161  5615  5615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-09 10:33:30.177  5720  5720 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,11-09 10:33:30.200  5720  5720 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,11-09 10:33:30.200  5720  5720 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,11-09 10:33:30.212   931  2957 D WifiConfigStore: Loading config and enabling all networks 
,11-09 10:33:30.219  5615  5615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-09 10:33:30.219  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-09 10:33:30.219  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-09 10:33:30.219  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-09 10:33:30.219  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-09 10:33:30.219  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-09 10:33:30.219  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-09 10:33:30.219  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,11-09 10:33:30.223  5615  5615 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,11-09 10:33:30.225  5615  5615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-09 10:33:30.225  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-09 10:33:30.225  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-09 10:33:30.225  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-09 10:33:30.225  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-09 10:33:30.225  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-09 10:33:30.225  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-09 10:33:30.225  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,11-09 10:33:30.227  5615  5615 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,11-09 10:33:30.228   931  2957 D WifiConfigStore: loaded 0 passpoint configs
11-09 10:33:30.229   931  2957 W WifiConfigStore: Upgrading network 4 to android.uid.system:1000
11-09 10:33:30.229   931  2957 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
11-09 10:33:30.229   931  2957 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,11-09 10:33:30.230   931  2957 W WifiConfigStore: Upgrading network 3 to android.uid.system:1000
11-09 10:33:30.230   931  2957 W WifiConfigStore: Upgrading network 2 to android.uid.system:1000
,11-09 10:33:30.230   931  2957 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
11-09 10:33:30.230   931  2957 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 5
11-09 10:33:30.231   931  2957 E WifiConfigStore: found sortedWifiConfigurations : "AndroidAP"WPA_PSK
11-09 10:33:30.231   931  2957 E WifiConfigStore: found sortedWifiConfigurations : "AndroidHotspot2346"WPA_PSK
11-09 10:33:30.231   931  2957 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
11-09 10:33:30.231   931  2957 E WifiConfigStore: found sortedWifiConfigurations : "Thali_internal"WPA_PSK
11-09 10:33:30.231   931  2957 E WifiConfigStore: found sortedWifiConfigurations : "MC"WPA_PSK
,11-09 10:33:30.231  5615  5615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-09 10:33:30.231  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-09 10:33:30.231  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-09 10:33:30.231  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-09 10:33:30.231  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-09 10:33:30.231  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-09 10:33:30.231  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-09 10:33:30.231  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,11-09 10:33:30.232   931  2957 D WifiNative-HAL: Setting external_sim to 1
11-09 10:33:30.233   931  2957 D wifi    : setting dfs flag to true, 0x7f88af5be0
11-09 10:33:30.233  4527  4527 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
11-09 10:33:30.233   931  2957 D WifiStateMachine: Setting OUI to DA-A1-19
11-09 10:33:30.233   931  2957 D wifi    : setting scan oui 0x7f88af5be0
11-09 10:33:30.233   931  2957 D WifiHAL : Sending mac address OUI
,11-09 10:33:30.233  5615  5615 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,11-09 10:33:30.235   931  2957 E native  : do suspend false
,11-09 10:33:30.242   931  2957 D wifi    : android_net_wifi_setLinkLayerStats: 1
,11-09 10:33:30.242   931   931 D RttService: SCAN_AVAILABLE : 3
11-09 10:33:30.242   931  3065 D RttService: DefaultState got{ when=-1ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,11-09 10:33:30.245   511   925 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,11-09 10:33:30.247   511   925 D CommandListener: Setting iface cfg
,11-09 10:33:30.249   931  2956 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '122 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 122 Failed to set address (No such device)'
11-09 10:33:30.249   931  2956 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,11-09 10:33:30.256   931   946 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=105191 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=11 mControllerEnergyUsed=41 }
,11-09 10:33:30.257   931  2956 D WifiNative-HAL: p2pGetDeviceAddress
11-09 10:33:30.257   931  2956 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:70
,11-09 10:33:30.373  5615  5679 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-09 10:33:30.382  4676  4732 D BluetoothAdapterState: Current state: ON, message: 23
,11-09 10:33:30.382  4676  4732 D BluetoothAdapterProperties: Setting state to 13
,11-09 10:33:30.382  4676  4732 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,11-09 10:33:30.383  4676  4732 D BluetoothAdapterProperties: onBluetoothDisable()
11-09 10:33:30.385  4676  4732 I BluetoothAdapterState: Entering PendingCommandState
11-09 10:33:30.388  4676  4676 D BluetoothMapService: onReceive
11-09 10:33:30.389  4676  4676 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
11-09 10:33:30.389  4676  4676 D BluetoothMapService: STATE_TURNING_OFF
11-09 10:33:30.389  4676  4676 D BluetoothMapService: MAP Service closeService in
11-09 10:33:30.389  4676  4676 D BluetoothMapMasInstance0: MAP Service shutdown
11-09 10:33:30.390  4676  4676 D ObexServerSockets0: shutdown(block = true)
11-09 10:33:30.391  4676  4676 D ObexServerSockets0: shutdown called from another thread - interrupt().
11-09 10:33:30.391  4676  4909 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
11-09 10:33:30.392  4676  4676 D ObexServerSockets0: shutdown called from another thread - interrupt().
,11-09 10:33:30.392  5615  5615 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-09 10:33:30.392  4676  4911 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
11-09 10:33:30.392  5615  5615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-09 10:33:30.392  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-09 10:33:30.392  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-09 10:33:30.392  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-09 10:33:30.392  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-09 10:33:30.392  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-09 10:33:30.392  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-09 10:33:30.392  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-09 10:33:30.392  4676  4887 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
11-09 10:33:30.395  5615  5615 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-09 10:33:30.395  5615  5615 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
11-09 10:33:30.396  4676  4676 I BtOppRfcommListener: stopping Accept Thread
11-09 10:33:30.397  4676  5321 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
11-09 10:33:30.397  4676  5321 I BtOppRfcommListener: BluetoothSocket listen thread finished
11-09 10:33:30.401  5615  5615 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-09 10:33:30.401  5615  5615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-09 10:33:30.401  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-09 10:33:30.401  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-09 10:33:30.401  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-09 10:33:30.401  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-09 10:33:30.401  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-09 10:33:30.401  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-09 10:33:30.401  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-09 10:33:30.403  5615  5615 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,11-09 10:33:30.403  5615  5615 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
11-09 10:33:30.409  5615  5615 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-09 10:33:30.410  5615  5615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-09 10:33:30.410  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-09 10:33:30.410  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-09 10:33:30.410  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-09 10:33:30.410  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-09 10:33:30.410  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-09 10:33:30.410  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-09 10:33:30.410  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-09 10:33:30.412   931   944 I ActivityManager: Start proc 5725:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
11-09 10:33:30.412  5615  5615 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-09 10:33:30.412  5615  5615 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
11-09 10:33:30.413  4676  4736 D BluetoothAdapterProperties: Scan Mode:20
11-09 10:33:30.413  4676  4732 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
11-09 10:33:30.415  4676  4676 D HeadsetService: Received stop request...Stopping profile...
11-09 10:33:30.418  3150  3984 D BluetoothHeadset: Proxy object disconnected
11-09 10:33:30.418   931   931 D BluetoothHeadset: Proxy object disconnected
11-09 10:33:30.419   931   931 D BluetoothHeadset: Proxy object disconnected
11-09 10:33:30.419   931   931 D BluetoothHeadset: Proxy object disconnected
11-09 10:33:30.419  4676  4676 D A2dpService: Received stop request...Stopping profile...
11-09 10:33:30.419  3777  3991 D BluetoothHeadset: Proxy object disconnected
11-09 10:33:30.419  4676  4892 D A2dpStateMachine: Exit Disconnected: -1
11-09 10:33:30.421   931   931 D BluetoothA2dp: Proxy object disconnected
11-09 10:33:30.422  5615  5615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-09 10:33:30.422  4676  4676 V BluetoothAdapterState: isTurningOff()=true
11-09 10:33:30.422  4676  4676 V BluetoothAdapterState: isTurningOn()=false
11-09 10:33:30.422  4676  4676 V BluetoothAdapterState: isBleTurningOn()=false
11-09 10:33:30.422  4676  4676 V BluetoothAdapterState: isBleTurningOff()=false
11-09 10:33:30.423  3150  3150 D HeadsetProfile: Bluetooth service disconnected
11-09 10:33:30.424  3150  3150 D BluetoothA2dp: Proxy object disconnected
11-09 10:33:30.425  5615  5615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-09 10:33:30.425  4676  4676 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
11-09 10:33:30.426  4676  4676 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
11-09 10:33:30.426  4676  4881 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-09 10:33:30.426  4676  4881 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-09 10:33:30.426  4676  4881 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-09 10:33:30.426  5615  5615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-09 10:33:30.427  4676  4736 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
11-09 10:33:30.427  4676  4736 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
11-09 10:33:30.427  4676  4676 D HidService: Received stop request...Stopping profile...
11-09 10:33:30.427  4676  4676 D HidService: Stopping Bluetooth HidService
11-09 10:33:30.429  3150  3150 D BluetoothInputDevice: Proxy object disconnected
11-09 10:33:30.429  3150  3150 D HidProfile: Bluetooth service disconnected
11-09 10:33:30.430  4676  4676 D HealthService: Received stop request...Stopping profile...
11-09 10:33:30.431  4676  4676 V BluetoothAdapterState: isTurningOff()=true
11-09 10:33:30.431  4676  4676 V BluetoothAdapterState: isTurningOn()=false
11-09 10:33:30.431  4676  4676 V BluetoothAdapterState: isBleTurningOn()=false
11-09 10:33:30.431  4676  4676 V BluetoothAdapterState: isBleTurningOff()=false
11-09 10:33:30.438  4676  4881 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-09 10:33:30.438  4676  4881 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-09 10:33:30.438  4676  4676 D PanService: Received stop request...Stopping profile...
11-09 10:33:30.438  4676  4881 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
11-09 10:33:30.438  4676  4881 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
11-09 10:33:30.438  4676  4881 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
11-09 10:33:30.438  4676  4881 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
11-09 10:33:30.438  4676  4736 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
11-09 10:33:30.439  3150  3150 D BluetoothPan: BluetoothPAN Proxy object disconnected
11-09 10:33:30.439  3150  3150 D PanProfile: Bluetooth service disconnected
11-09 10:33:30.439  4676  4676 D BluetoothMapService: Received stop request...Stopping profile...
11-09 10:33:30.440  4676  4676 D BluetoothMapService: stop()
11-09 10:33:30.440  4676  4676 D BluetoothMapAppObserver: deinitObservers()
11-09 10:33:30.440  4676  4676 D BluetoothMapAppObserver: removeReceiver()
11-09 10:33:30.441  3150  3150 D BluetoothMap: Proxy object disconnected
11-09 10:33:30.441  3150  3150 D MapProfile: Bluetooth service disconnected
11-09 10:33:30.442  4676  4676 D SapService: Received stop request...Stopping profile...
11-09 10:33:30.442  4676  4676 V SapService: stop()
11-09 10:33:30.443  4676  4676 V BluetoothAdapterState: isTurningOff()=true
11-09 10:33:30.443  4676  4676 V BluetoothAdapterState: isTurningOn()=false
11-09 10:33:30.443  4676  4676 V BluetoothAdapterState: isBleTurningOn()=false
11-09 10:33:30.443  4676  4676 V BluetoothAdapterState: isBleTurningOff()=false
11-09 10:33:30.444  4676  4676 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
11-09 10:33:30.444  4676  4676 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
11-09 10:33:30.444  4676  4676 V BluetoothAdapterState: isTurningOff()=true
11-09 10:33:30.444  4676  4676 V BluetoothAdapterState: isTurningOn()=false
11-09 10:33:30.444  4676  4676 V BluetoothAdapterState: isBleTurningOn()=false
11-09 10:33:30.445  4676  4676 V BluetoothAdapterState: isBleTurningOff()=false
11-09 10:33:30.445  4676  4676 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
,11-09 10:33:30.446  4676  4676 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
11-09 10:33:30.446  4676  4676 V BluetoothAdapterState: isTurningOff()=true
11-09 10:33:30.446  4676  4676 V BluetoothAdapterState: isTurningOn()=false
11-09 10:33:30.446  4676  4676 V BluetoothAdapterState: isBleTurningOn()=false
11-09 10:33:30.446  4676  4676 V BluetoothAdapterState: isBleTurningOff()=false
11-09 10:33:30.446  4676  4676 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
11-09 10:33:30.446  4676  4676 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
11-09 10:33:30.447  4676  4736 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
11-09 10:33:30.447  4676  4736 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
11-09 10:33:30.451  4676  4676 D BluetoothMapService: MAP Service closeService in
11-09 10:33:30.452  4676  4676 V BluetoothAdapterState: isTurningOff()=true
11-09 10:33:30.452  4676  4676 V BluetoothAdapterState: isTurningOn()=false
11-09 10:33:30.452  4676  4676 V BluetoothAdapterState: isBleTurningOn()=false
11-09 10:33:30.453  4676  4676 V BluetoothAdapterState: isBleTurningOff()=false
11-09 10:33:30.453  4676  4676 D BluetoothMapService: cleanup()
11-09 10:33:30.453  4676  4676 D BluetoothMapService: MAP Service closeService in
11-09 10:33:30.453  4676  4676 V BluetoothAdapterState: isTurningOff()=true
11-09 10:33:30.453  4676  4676 V BluetoothAdapterState: isTurningOn()=false
11-09 10:33:30.453  4676  4676 V BluetoothAdapterState: isBleTurningOn()=false
11-09 10:33:30.453  4676  4676 V BluetoothAdapterState: isBleTurningOff()=false
11-09 10:33:30.453  4676  4732 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
11-09 10:33:30.454  4676  4732 D BluetoothAdapterProperties: Setting state to 15
11-09 10:33:30.454  4676  4732 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
11-09 10:33:30.454  4676  4732 I BluetoothAdapterState: Entering BleOnState
11-09 10:33:30.455  3777  3802 D BluetoothHeadset: onBluetoothStateChange: up=false
11-09 10:33:30.455  3150  3983 D BluetoothPbap: onBluetoothStateChange: up=false
11-09 10:33:30.456  3150  3163 D BluetoothMap: onBluetoothStateChange: up=false
11-09 10:33:30.457  3150  3984 D BluetoothHeadset: onBluetoothStateChange: up=false
11-09 10:33:30.457   931   948 D BluetoothHeadset: onBluetoothStateChange: up=false
11-09 10:33:30.458  3150  3164 D BluetoothPan: onBluetoothStateChange on: false
11-09 10:33:30.458   931   948 D BluetoothHeadset: onBluetoothStateChange: up=false
11-09 10:33:30.459  3150  3983 D BluetoothInputDevice: onBluetoothStateChange: up=false
11-09 10:33:30.459   931   948 D BluetoothA2dp: onBluetoothStateChange: up=false
11-09 10:33:30.459   931   948 D BluetoothHeadset: onBluetoothStateChange: up=false
11-09 10:33:30.460  3150  3163 D BluetoothA2dp: onBluetoothStateChange: up=false
11-09 10:33:30.461  4676  4732 D BluetoothAdapterState: Current state: BLE ON, message: 20
11-09 10:33:30.461  4676  4732 D BluetoothAdapterProperties: Setting state to 16
11-09 10:33:30.461  4676  4732 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
11-09 10:33:30.465  5615  5615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-09 10:33:30.467  4676  4732 D BluetoothAdapterProperties: onBleDisable
11-09 10:33:30.467  4676  4732 I BluetoothAdapterState: Entering PendingCommandState
11-09 10:33:30.467  4676  4733 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
11-09 10:33:30.468  5615  5615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-09 10:33:30.468  4676  4881 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
11-09 10:33:30.468  4676  4881 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-09 10:33:30.469  5615  5615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-09 10:33:30.471  4676  4736 D BluetoothAdapterProperties: Scan Mode:20
11-09 10:33:30.474  5615  5615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-09 10:33:30.475  5615  5615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-09 10:33:30.477  5615  5615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-09 10:33:30.491  5725  5725 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm64
,11-09 10:33:30.504  5725  5725 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,11-09 10:33:30.509   931   948 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@db97378:true
,11-09 10:33:30.510  3589  3589 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,11-09 10:33:30.524   931   941 I ActivityManager: Start proc 5737:com.google.android.apps.maps/u0a58 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,11-09 10:33:30.531  5725  5725 D LocalBluetoothProfileManager: Adding local MAP profile
,11-09 10:33:30.536  5725  5725 D BluetoothMap: Create BluetoothMap proxy object
,11-09 10:33:30.544  5725  5725 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,11-09 10:33:30.559  5737  5737 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm64
,11-09 10:33:30.563  5725  5725 D DockEventReceiver: finishStartingService: stopping service
,11-09 10:33:30.565   931  3158 I ActivityManager: Killing 5294:com.google.android.music:main/u0a59 (adj 15): empty #17
,11-09 10:33:30.675  4676  4736 I bt_hci  : shut_down
,11-09 10:33:30.680  4676  4740 D bt_hwcfg: hw_epilog_process
,11-09 10:33:30.680  4676  4740 I bt_vendor: low_power_mode_cb
,11-09 10:33:30.682  4676  4740 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,11-09 10:33:30.682  4676  4740 I bt_vendor: epilog_cb
11-09 10:33:30.682  4676  4740 I bt_hci  : epilog_finished_callback
,11-09 10:33:30.685  4676  4736 I bt_hci_h4: hal_close
,11-09 10:33:30.686  4676  4736 I bt_userial_vendor: device fd = 54 close
,11-09 10:33:30.773  5737  5737 D StrictMode: StrictMode policy violation; ~duration=124 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-09 10:33:30.773  5737  5737 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-09 10:33:30.773  5737  5737 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
11-09 10:33:30.773  5737  5737 D StrictMode: 	at java.io.File.doAccess(File.java:281)
11-09 10:33:30.773  5737  5737 D StrictMode: 	at java.io.File.exists(File.java:361)
11-09 10:33:30.773  5737  5737 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
11-09 10:33:30.773  5737  5737 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
11-09 10:33:30.773  5737  5737 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
11-09 10:33:30.773  5737  5737 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
11-09 10:33:30.773  5737  5737 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
11-09 10:33:30.773  5737  5737 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
11-09 10:33:30.773  5737  5737 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-09 10:33:30.773  5737  5737 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-09 10:33:30.773  5737  5737 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-09 10:33:30.773  5737  5737 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-09 10:33:30.773  5737  5737 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-09 10:33:30.773  5737  5737 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-09 10:33:30.773  5737  5737 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-09 10:33:30.773  5737  5737 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-09 10:33:30.773  5737  5737 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-09 10:33:30.773  5737  5737 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-09 10:33:30.773  5737  5737 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-09 10:33:30.773  5737  5737 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-09 10:33:30.773  5737  5737 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-09 10:33:30.773  5737  5737 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-09 10:33:30.773  5737  5737 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-09 10:33:30.773  5737  5737 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,11-09 10:33:30.773  5737  5737 D StrictMode: StrictMode policy violation; ~duration=123 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-09 10:33:30.773  5737  5737 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-09 10:33:30.773  5737  5737 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
11-09 10:33:30.773  5737  5737 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
11-09 10:33:30.773  5737  5737 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
11-09 10:33:30.773  5737  5737 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
11-09 10:33:30.773  5737  5737 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
11-09 10:33:30.773  5737  5737 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
11-09 10:33:30.773  5737  5737 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
11-09 10:33:30.773  5737  5737 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-09 10:33:30.773  5737  5737 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-09 10:33:30.773  5737  5737 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-09 10:33:30.773  5737  5737 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-09 10:33:30.773  5737  5737 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-09 10:33:30.773  5737  5737 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-09 10:33:30.773  5737  5737 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-09 10:33:30.773  5737  5737 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-09 10:33:30.773  5737  5737 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-09 10:33:30.773  5737  5737 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-09 10:33:30.773  5737  5737 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-09 10:33:30.773  5737  5737 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-09 10:33:30.773  5737  5737 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-09 10:33:30.773  5737  5737 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-09 10:33:30.773  5737  5737 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-09 10:33:30.773  5737  5737 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-09 10:33:30.774  5737  5737 D StrictMode: StrictMode policy violation; ~duration=123 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-09 10:33:30.774  5737  5737 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-09 10:33:30.774  5737  5737 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
11-09 10:33:30.774  5737  5737 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
11-09 10:33:30.774  5737  5737 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
11-09 10:33:30.774  5737  5737 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
11-09 10:33:30.774  5737  5737 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
11-09 10:33:30.774  5737  5737 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
11-09 10:33:30.774  5737  5737 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
11-09 10:33:30.774  5737  5737 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-09 10:33:30.774  5737  5737 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-09 10:33:30.774  5737  5737 D StrictMode: 	at com.google.android.apps.gmm.base.ap,p.a.a(PG:244)
11-09 10:33:30.774  5737  5737 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-09 10:33:30.774  5737  5737 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-09 10:33:30.774  5737  5737 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-09 10:33:30.774  5737  5737 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-09 10:33:30.774  5737  5737 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-09 10:33:30.774  5737  5737 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-09 10:33:30.774  5737  5737 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-09 10:33:30.774  5737  5737 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-09 10:33:30.774  5737  5737 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-09 10:33:30.774  5737  5737 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-09 10:33:30.774  5737  5737 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-09 10:33:30.774  5737  5737 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-09 10:33:30.774  5737  5737 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-09 10:33:30.774  5737  5737 D StrictMode: StrictMode policy violation; ~duration=122 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-09 10:33:30.774  5737  5737 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-09 10:33:30.774  5737  5737 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
11-09 10:33:30.774  5737  5737 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
11-09 10:33:30.774  5737  5737 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
11-09 10:33:30.774  5737  5737 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
11-09 10:33:30.774  5737  5737 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
11-09 10:33:30.774  5737  5737 D StrictMode: 	at com.google.r.k.d(PG:1187)
11-09 10:33:30.774  5737  5737 D StrictMode: 	at com.google.r.k.a(PG:2107)
11-09 10:33:30.774  5737  5737 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
11-09 10:33:30.774  5737  5737 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
11-09 10:33:30.774  5737  5737 D StrictMode: 	at com.google.r.v.a(PG:1161)
11-09 10:33:30.774  5737  5737 D StrictMode: 	at com.google.r.y.a(PG:2188)
11-09 10:33:30.774  5737  5737 D StrictMode: 	at com.google.r.e.b(PG:170)
11-09 10:33:30.774  5737  5737 D StrictMode: 	at com.google.r.e.b(PG:15188)
11-09 10:33:30.774  5737  5737 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
11-09 10:33:30.774  5737  5737 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
11-09 10:33:30.774  5737  5737 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-09 10:33:30.774  5737  5737 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-09 10:33:30.774  5737  5737 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-09 10:33:30.774  5737  5737 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-09 10:33:30.774  5737  5737 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-09 10:33:30.774  5737  5737 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-09 10:33:30.774  5737  5737 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-09 10:33:30.774  5737  5737 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-09 10:33:30.774  5737  5737 D StrictMode: 	at android.app.ActivityThread.-wrap1(Activit,yThread.java)
11-09 10:33:30.774  5737  5737 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-09 10:33:30.774  5737  5737 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-09 10:33:30.774  5737  5737 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-09 10:33:30.774  5737  5737 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-09 10:33:30.774  5737  5737 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-09 10:33:30.774  5737  5737 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-09 10:33:30.774  5737  5737 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-09 10:33:30.774  5737  5737 D StrictMode: StrictMode policy violation; ~duration=118 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-09 10:33:30.774  5737  5737 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-09 10:33:30.774  5737  5737 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
11-09 10:33:30.774  5737  5737 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
11-09 10:33:30.774  5737  5737 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
11-09 10:33:30.774  5737  5737 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
11-09 10:33:30.774  5737  5737 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
11-09 10:33:30.774  5737  5737 D StrictMode: 	at com.google.r.k.d(PG:1187)
11-09 10:33:30.774  5737  5737 D StrictMode: 	at com.google.r.k.c(PG:18147)
11-09 10:33:30.774  5737  5737 D StrictMode: 	at com.google.r.k.d(PG:583)
11-09 10:33:30.774  5737  5737 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
11-09 10:33:30.774  5737  5737 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
11-09 10:33:30.774  5737  5737 D StrictMode: 	at com.google.r.v.a(PG:1161)
11-09 10:33:30.774  5737  5737 D StrictMode: 	at com.google.r.y.a(PG:2188)
11-09 10:33:30.774  5737  5737 D StrictMode: 	at com.google.r.e.b(PG:170)
11-09 10:33:30.774  5737  5737 D StrictMode: 	at com.google.r.e.b(PG:15188)
11-09 10:33:30.774  5737  5737 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
11-09 10:33:30.774  5737  5737 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
11-09 10:33:30.774  5737  5737 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-09 10:33:30.774  5737  5737 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-09 10:33:30.774  5737  5737 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-09 10:33:30.774  5737  5737 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-09 10:33:30.774  5737  5737 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-09 10:33:30.774  5737  5737 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-09 10:33:30.774  5737  5737 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-09 10:33:30.774  5737  5737 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-09 10:33:30.774  5737  5737 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-09 10:33:30.774  5737  5737 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-09 10:33:30.774  5737  5737 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-09 10:33:30.774  5737  5737 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-09 10:33:30.774  5737  5737 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-09 10:33:30.774  5737  5737 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-09 10:33:30.774  5737  5737 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-09 10:33:30.774  5737  5737 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-09 10:33:30.774  5737  5737 D StrictMode: StrictMode policy violation; ~duration=77 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-09 10:33:30.774  5737  5737 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-09 10:33:30.774  5737  5737 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
11-09 10:33:30.774  5737  5737 D StrictMode: 	at java.io.File.doAccess(File.java:281)
11-09 10:33:30.774  5737  5737 D StrictMode: 	at java.io.File.exists(File.java:361)
11-09 10:33:30.774  5737  5737 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
11-09 10:33:30.774  5737  5737 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
11-09 10:33:30.774  5737  5737 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
11-09 10:33:30.774  5737  5737 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
11-09 10:33:30.774  5737  5737 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
11-09 10:33:30.774  5737  5737 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-09 10:33:30.774  5737  5737 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-09 10:33:30.774  5737  5737 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-09 10:33:30.774  5737  5737 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-09 10:33:30.774  5737  5737 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-09 10:33:30.774  5737  5737 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-09 10:33:30.774  5737  5737 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-09 10:33:30.774  5737  5737 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-09 10:33:30.774  5737  5737 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-09 10:33:30.774  5737  5737 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-09 10:33:30.774  5737  5737 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-09 10:33:30.774  5737  5737 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-09 10:33:30.774  5737  5737 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-09 10:33:30.774  5737  5737 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-09 10:33:30.774  5737  5737 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-09 10:33:30.774  5737  5737 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-09 10:33:30.774  5737  5737 D StrictMode: StrictMode policy violation; ~duration=76 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-09 10:33:30.774  5737  5737 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-09 10:33:30.774  5737  5737 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
11-09 10:33:30.774  5737  5737 D StrictMode: 	at java.io.File.doAccess(File.java:281)
11-09 10:33:30.774  5737  5737 D StrictMode: 	at java.io.File.exists(File.java:361)
11-09 10:33:30.774  5737  5737 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
11-09 10:33:30.774  5737  5737 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-09 10:33:30.774  5737  5737 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-09 10:33:30.774  5737  5737 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-09 10:33:30.774  5737  5737 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-09 10:33:30.774  5737  5737 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-09 10:33:30.774  5737  5737 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-09 10:33:30.774  5737  5737 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-09 10:33:30.774  5737  5737 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-09 10:33:30.774  5737  5737 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-09 10:33:30.774  5737  5737 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-09 10:33:30.774  5737  5737 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-09 10:33:30.774  5737  5737 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-09 10:33:30.774  5737  5737 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-09 10:33:30.774  5737  5737 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-09 10:33:30.774  5737  5737 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-09 10:33:30.774  5737  5737 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-09 10:33:30.774  5737  5737 D StrictMode: StrictMode policy violation; ~duration=76 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-09 10:33:30.774  5737  5737 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-09 10:33:30.774  5737  5737 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
11-09 10:33:30.774  5737  5737 D StrictMode: 	at java.io.File.lastModified(File.java:569)
11-09 10:33:30.774  5737  5737 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
11-09 10:33:30.774  5737  5737 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-09 10:33:30.774  5737  5737 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-09 10:33:30.774  5737  5737 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-09 10:33:30.774  5737  5737 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-09 10:33:30.774  5737  5737 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-09 10:33:30.774  5737  5737 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-09 10:33:30.774  5737  5737 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-09 10:33:30.774  5737  5737 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-09 10:33:30.774  5737  5737 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-09 10:33:30.774  5737  5737 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-09 10:33:30.774  5737  5737 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-09 10:33:30.774  5737  5737 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-09 10:33:30.774  5737  5737 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-09 10:33:30.774  5737  5737 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-09 10:33:30.774  5737  5737 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-09 10:33:30.774  5737  5737 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-09 10:33:30.778  5725  5725 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
11-09 10:33:30.783  3589  3589 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
11-09 10:33:30.790  5725  5725 D DockEventReceiver: finishStartingService: stopping service
11-09 10:33:30.792   931   942 I ActivityManager: Killing 3853:com.android.providers.calendar/u0a1 (adj 15): empty #17
,11-09 10:33:30.834  4676  4733 D bt_stack_manager: event_shut_down_stack finished.
11-09 10:33:30.834  4676  4732 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
11-09 10:33:30.836  4676  4732 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
11-09 10:33:30.836  4676  4676 D BtGatt.DebugUtils: handleDebugAction() action=null
11-09 10:33:30.836  4676  4676 D BtGatt.GattService: Received stop request...Stopping profile...
11-09 10:33:30.836  4676  4676 D BtGatt.GattService: stop()
11-09 10:33:30.836  4676  4676 D BtGatt.AdvertiseManager: advertise clients cleared
11-09 10:33:30.838  4676  4676 V BluetoothAdapterState: isTurningOff()=false
11-09 10:33:30.838  4676  4676 V BluetoothAdapterState: isTurningOn()=false
11-09 10:33:30.838  4676  4676 V BluetoothAdapterState: isBleTurningOn()=false
11-09 10:33:30.838  4676  4676 V BluetoothAdapterState: isBleTurningOff()=true
11-09 10:33:30.838  4676  4732 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
11-09 10:33:30.838  4676  4732 D BluetoothAdapterProperties: Setting state to 10
11-09 10:33:30.838  4676  4732 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
11-09 10:33:30.840   931   948 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
11-09 10:33:30.840  4676  4732 I BluetoothAdapterState: Entering OffState
11-09 10:33:30.846  4676  4676 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
11-09 10:33:30.846  4676  4676 W BluetoothSdpJni: Cleaning up Bluetooth Health object
11-09 10:33:30.846  4676  4676 I BluetoothServiceJni: cleanupNative: return from cleanup
11-09 10:33:30.847  4676  4733 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,11-09 10:33:30.849  4676  4676 I art     : System.exit called, status: 0
,11-09 10:33:30.850  4676  4676 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,11-09 10:33:30.882  5615  5679 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-09 10:33:30.884   380   380 E lowmemorykiller: Error writing /proc/4676/oom_score_adj; errno=22
,11-09 10:33:30.884   931   948 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!  (parcel size = 76)
11-09 10:33:30.885   931   948 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!  (parcel size = 1308)
11-09 10:33:30.885   931   948 W ActivityManager: Application dead when creating service ServiceRecord{fa93043 u0 com.android.bluetooth/.btservice.AdapterService}
,11-09 10:33:30.891   931   948 I ActivityManager: Process com.android.bluetooth (pid 4676) has died
,11-09 10:33:30.891   931   948 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/.btservice.AdapterService in 1000ms
11-09 10:33:30.892   931   948 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/.btservice.AdapterService in 4000ms
11-09 10:33:30.893   931   948 W ActivityManager: Exception when starting service com.android.bluetooth/.btservice.AdapterService
11-09 10:33:30.893   931   948 W ActivityManager: android.os.DeadObjectException: Transaction failed on small parcel; remote process probably died
11-09 10:33:30.893   931   948 W ActivityManager: 	at android.os.BinderProxy.transactNative(Native Method)
11-09 10:33:30.893   931   948 W ActivityManager: 	at android.os.BinderProxy.transact(Binder.java:503)
11-09 10:33:30.893   931   948 W ActivityManager: 	at android.app.ApplicationThreadProxy.scheduleCreateService(ApplicationThreadNative.java:928)
11-09 10:33:30.893   931   948 W ActivityManager: 	at com.android.server.am.ActiveServices.realStartServiceLocked(ActiveServices.java:1531)
11-09 10:33:30.893   931   948 W ActivityManager: 	at com.android.server.am.ActiveServices.bringUpServiceLocked(ActiveServices.java:1435)
11-09 10:33:30.893   931   948 W ActivityManager: 	at com.android.server.am.ActiveServices.bindServiceLocked(ActiveServices.java:817)
11-09 10:33:30.893   931   948 W ActivityManager: 	at com.android.server.am.ActivityManagerService.bindService(ActivityManagerService.java:16010)
11-09 10:33:30.893   931   948 W ActivityManager: 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1317)
11-09 10:33:30.893   931   948 W ActivityManager: 	at android.app.ContextImpl.bindServiceAsUser(ContextImpl.java:1293)
11-09 10:33:30.893   931   948 W ActivityManager: 	at com.android.server.BluetoothManagerService.doBind(BluetoothManagerService.java:1588)
11-09 10:33:30.893   931   948 W ActivityManager: 	at com.android.server.BluetoothManagerService.handleEnable(BluetoothManagerService.java:1544)
11-09 10:33:30.893   931   948 W ActivityManager: 	at com.android.server.BluetoothManagerService.-wrap7(BluetoothManagerService.java)
11-09 10:33:30.893   931   948 W ActivityManager: 	at com.android.server.BluetoothManagerService$BluetoothHandler.handleMessage(BluetoothManagerService.java:1215)
11-09 10:33:30.893   931   948 W ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-09 10:33:30.893   931   948 W ActivityManager: 	at android.os.Looper.loop(Looper.java:148)
11-09 10:33:30.893   931   948 W ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
11-09 10:33:30.893   931   948 W ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
11-09 10:33:30.893   931  3770 W ActivityManager: Spurious death for ProcessRecord{8842d61 0:com.android.bluetooth/1002}, curProc for 4676: null
,11-09 10:33:31.022  5737  5755 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,11-09 10:33:31.031   931   948 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@7af2ff9:true
,11-09 10:33:33.332  5720  5720 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-09 10:33:33.337  5720  5720 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-09 10:33:33.342  5720  5720 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-09 10:33:33.347  5720  5720 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-09 10:33:33.394   931  2957 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
11-09 10:33:33.395   931  2957 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3
11-09 10:33:33.395   931  2957 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-09 10:33:33.406   931  2957 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=0
,11-09 10:33:33.442   931  2957 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=0
,11-09 10:33:33.448  5720  5720 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,11-09 10:33:33.883   931   948 E BluetoothManagerService: MESSAGE_TIMEOUT_BIND
,11-09 10:33:33.884  5720  5720 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,11-09 10:33:33.920  5720  5720 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,11-09 10:33:33.921  5720  5720 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,11-09 10:33:33.921   931   948 I ActivityManager: Start proc 5771:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,11-09 10:33:33.930   931  2957 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
11-09 10:33:33.930   931  2957 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
11-09 10:33:33.931   931  2959 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,11-09 10:33:33.944   931  2957 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-09 10:33:33.958   511   925 D CommandListener: Setting iface cfg
,11-09 10:33:33.962   931  2957 D WifiStateMachine: Start Dhcp Watchdog 2
,11-09 10:33:33.968   931  5786 D DhcpClient: Receive thread started
,11-09 10:33:33.973   931  2959 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-09 10:33:33.973   931  2957 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
11-09 10:33:33.973   931  2959 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
,11-09 10:33:33.998  5771  5771 D AdapterServiceConfig: Adding HeadsetService
11-09 10:33:33.998  5771  5771 D AdapterServiceConfig: Adding A2dpService
,11-09 10:33:33.999  5771  5771 D AdapterServiceConfig: Adding HidService
11-09 10:33:33.999  5771  5771 D AdapterServiceConfig: Adding HealthService
11-09 10:33:33.999  5771  5771 D AdapterServiceConfig: Adding PanService
11-09 10:33:33.999  5771  5771 D AdapterServiceConfig: Adding GattService
11-09 10:33:33.999  5771  5771 D AdapterServiceConfig: Adding BluetoothMapService
11-09 10:33:33.999  5771  5771 D AdapterServiceConfig: Adding SapService
,11-09 10:33:34.012   931   948 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@b13d4e:true
,11-09 10:33:34.012  5771  5771 D BluetoothAdapterState: make() - Creating AdapterState
,11-09 10:33:34.015  5771  5771 I bt_bluedroid: init
,11-09 10:33:34.015  5771  5787 I BluetoothAdapterState: Entering OffState
,11-09 10:33:34.017  5771  5788 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
11-09 10:33:34.017  5771  5788 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
11-09 10:33:34.017  5771  5788 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
11-09 10:33:34.017  5771  5788 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,11-09 10:33:34.017  5771  5771 I bt_bluedroid: get_profile_interface socket
,11-09 10:33:34.019  5771  5791 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:D4
,11-09 10:33:34.019  5771  5771 I bt_bluedroid: get_profile_interface sdp
11-09 10:33:34.020  5771  5791 D BluetoothAdapterProperties: Name is: Nexus 6P
,11-09 10:33:34.023  5771  5783 I bt_bluedroid: config_hci_snoop_log
,11-09 10:33:34.024   931   948 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,11-09 10:33:34.027  5771  5787 D BluetoothAdapterState: Current state: OFF, message: 0
,11-09 10:33:34.027  5771  5787 D BluetoothAdapterProperties: Setting state to 14
11-09 10:33:34.027  5771  5787 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
11-09 10:33:34.029  5771  5787 D BluetoothBondStateMachine: make
,11-09 10:33:34.030  5771  5792 I BluetoothBondStateMachine: StableState(): Entering Off State
,11-09 10:33:34.032  5771  5787 I BluetoothAdapterState: Entering PendingCommandState
,11-09 10:33:34.033  5771  5771 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,11-09 10:33:34.035  5771  5771 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a44b98d
,11-09 10:33:34.036  5771  5771 D BtGatt.DebugUtils: handleDebugAction() action=null
,11-09 10:33:34.036  5771  5771 D BtGatt.GattService: Received start request. Starting profile...
11-09 10:33:34.036  5771  5771 D BtGatt.GattService: start()
11-09 10:33:34.036  5771  5771 I bt_bluedroid: get_profile_interface gatt
,11-09 10:33:34.037  5771  5771 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a44b98d
,11-09 10:33:34.037  5771  5771 D BtGatt.AdvertiseManager: advertise manager created
,11-09 10:33:34.042  5771  5771 V BluetoothAdapterState: isTurningOff()=false
,11-09 10:33:34.042  5771  5771 V BluetoothAdapterState: isTurningOn()=false
11-09 10:33:34.042  5771  5771 V BluetoothAdapterState: isBleTurningOn()=true
11-09 10:33:34.042  5771  5771 V BluetoothAdapterState: isBleTurningOff()=false
11-09 10:33:34.042  5771  5787 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,11-09 10:33:34.043  5771  5787 I bt_bluedroid: bt_bluedroid
11-09 10:33:34.043  5771  5788 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,11-09 10:33:34.043  5771  5788 I bt_hci  : start_up
,11-09 10:33:34.048  5771  5788 I bt_vendor: alloc value 0xf3b37871
,11-09 10:33:34.048  5771  5788 I bt_vendor: init
11-09 10:33:34.048  5771  5788 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
11-09 10:33:34.048  5771  5788 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,11-09 10:33:34.052   931  2957 E native  : do suspend false
,11-09 10:33:34.060   931  5785 D DhcpClient: Broadcasting DHCPDISCOVER
,11-09 10:33:34.131   931  5786 D DhcpClient: Received packet: 60:83:34:25:d7:70 OFFER, ip /192.168.1.105, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172732, domain null
,11-09 10:33:34.131   931  5785 D DhcpClient: Got pending lease: IP address 192.168.1.105/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172732 seconds
11-09 10:33:34.131   931  5785 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.105 serverid=192.168.1.1
,11-09 10:33:34.146   931  5786 D DhcpClient: Received packet: 60:83:34:25:d7:70 ACK: your new IP /192.168.1.105, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,11-09 10:33:34.147   931  5785 D DhcpClient: Confirmed lease: IP address 192.168.1.105/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,11-09 10:33:34.148   511   925 D CommandListener: Setting iface cfg
,11-09 10:33:34.152   931  2957 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,11-09 10:33:34.156  5771  5788 D bt_hci  : start_up starting async portion
,11-09 10:33:34.156  5771  5795 I bt_hci  : event_finish_startup
11-09 10:33:34.156  5771  5795 I bt_hci_h4: hal_open
11-09 10:33:34.156  5771  5795 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,11-09 10:33:34.158   931  5785 D DhcpClient: Scheduling renewal in 86399s
11-09 10:33:34.158  5771  5795 I bt_userial_vendor: device fd = 54 open
11-09 10:33:34.154  5796  5796 W irq/448-msm_hs_: type=1400 audit(0.0:121): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-09 10:33:34.170   931  2957 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,11-09 10:33:34.171   931  2957 D WifiConfigStore: No blacklist allowed without epno enabled
,11-09 10:33:34.171   931  2959 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,11-09 10:33:34.173  5771  5795 I bt_hwcfg: bt vendor lib: set UART baud 3000000
11-09 10:33:34.176   931  2959 D ConnectivityService: Adding iface wlan0 to network 101
11-09 10:33:34.177  5771  5795 D bt_hwcfg: Chipset BCM4358A3
11-09 10:33:34.177  5771  5795 D bt_hwcfg: Target name = [BCM4358A3]
11-09 10:33:34.177  5771  5795 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
11-09 10:33:34.178   931  2957 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,11-09 10:33:34.216   931  2959 E ConnectivityService: Unexpected mtu value: 0, wlan0
,11-09 10:33:34.216   931  2959 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
,11-09 10:33:34.218   931  2959 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,11-09 10:33:34.220   931  2959 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,11-09 10:33:34.221   931  2959 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,11-09 10:33:34.230   931  2959 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
11-09 10:33:34.235   931  2959 D ConnectivityService: scheduleUnvalidatedPrompt 101
,11-09 10:33:34.235   931  2959 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
11-09 10:33:34.235   931  2959 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
11-09 10:33:34.235   931  2959 D ConnectivityService:    accepting network in place of null
,11-09 10:33:34.235   931  2957 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
11-09 10:33:34.236   931  2957 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
11-09 10:33:34.236   931  2959 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d770/64,192.168.1.105/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -47]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,11-09 10:33:34.259   511   925 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-09 10:33:34.282   511   925 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-09 10:33:34.288   931  2959 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,11-09 10:33:34.288   931  2959 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
11-09 10:33:34.288  3732  3848 W QCNEJ   : |CORE| network available: 101
11-09 10:33:34.289   931  2959 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
,11-09 10:33:34.292   931   948 D Tethering: MasterInitialState.processMessage what=3
,11-09 10:33:34.295  3732  3848 W QCNEJ   : |CORE| onAvailable: bind the process to WIFI
11-09 10:33:34.297  3732  3848 W QCNEJ   : |CORE| newLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d770/64,192.168.1.105/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}
11-09 10:33:34.297  3732  3848 W QCNEJ   : |CORE| curLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d770/64,192.168.1.105/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
11-09 10:33:34.299  5615  5615 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-09 10:33:34.299  5615  5615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-09 10:33:34.299  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-09 10:33:34.299  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-09 10:33:34.299  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-09 10:33:34.299  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-09 10:33:34.299  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-09 10:33:34.299  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-09 10:33:34.299  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,11-09 10:33:34.301  5615  5615 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-09 10:33:34.301   931  5784 D NetlinkSocketObserver: NeighborEvent{elapsedMs=109235, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
11-09 10:33:34.301  5615  5615 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,11-09 10:33:34.305  5615  5615 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,11-09 10:33:34.306  5615  5615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-09 10:33:34.306  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-09 10:33:34.306  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-09 10:33:34.306  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-09 10:33:34.306  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-09 10:33:34.306  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-09 10:33:34.306  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-09 10:33:34.306  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
11-09 10:33:34.306  5615  5615 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-09 10:33:34.307  5615  5615 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,11-09 10:33:34.310  5615  5615 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-09 10:33:34.310  5615  5615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-09 10:33:34.310  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-09 10:33:34.310  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-09 10:33:34.310  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-09 10:33:34.310  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-09 10:33:34.310  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-09 10:33:34.310  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-09 10:33:34.310  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
11-09 10:33:34.311  5615  5615 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-09 10:33:34.311  5615  5615 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,11-09 10:33:34.312  3963  3963 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
11-09 10:33:34.315  4045  4045 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
11-09 10:33:34.318  4045  4045 D SystemUpdateService: onCreate
11-09 10:33:34.322  4045  4045 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,11-09 10:33:34.335  4045  4045 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,11-09 10:33:34.340  4045  4254 I iu.UploadsManager: num queued entries: 0
,11-09 10:33:34.340  4045  4254 I iu.UploadsManager: num updated entries: 0
11-09 10:33:34.340  4045  4254 I iu.SyncManager: NEXT; no task
,11-09 10:33:34.342  4045  5807 I SystemUpdateService: active receiver: enabled
,11-09 10:33:34.345  4045  4045 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
11-09 10:33:34.347  4045  4045 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,11-09 10:33:34.349  5418  5418 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,11-09 10:33:34.353  5418  5418 D SprintDMHelper: simOperator: 
,11-09 10:33:34.353  5418  5418 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,11-09 10:33:34.367   931  5777 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.214.238,2a00:1450:400d:803::200e
,11-09 10:33:34.377  4045  5807 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,11-09 10:33:34.382  4045  5807 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,11-09 10:33:34.383  4045  5807 I SystemUpdateService: now status is 0 (complete)
11-09 10:33:34.383  4045  5807 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
11-09 10:33:34.383  4045  5807 I SystemUpdateService: file has been verified
11-09 10:33:34.383  4045  5807 I SystemUpdateService: OTA package size = 21989297
,11-09 10:33:34.388  4045  5807 I SystemUpdateService: showing system update notification
,11-09 10:33:34.396  5771  5787 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 0
,11-09 10:33:34.397   931   931 V NotificationService: pkg=com.google.android.gms canInterrupt=false intercept=true
11-09 10:33:34.398  4045  4045 D SystemUpdateService: onDestroy
,11-09 10:33:34.418   931  5777 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 09 Nov 2016 09:33:34 GMT], X-Android-Received-Millis=[1478684014417], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1478684014393]}
,11-09 10:33:34.419   931  2959 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,11-09 10:33:34.419   931  2959 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation  passed
11-09 10:33:34.419   931  2959 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
11-09 10:33:34.420   931  2959 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,11-09 10:33:34.492  5771  5795 I bt_hwcfg: bt vendor lib: set UART baud 115200
,11-09 10:33:34.492  5771  5795 D bt_hwcfg: Settlement delay -- 100 ms
11-09 10:33:34.492  5771  5795 I bt_hwcfg: Setting fw settlement delay to 100 
,11-09 10:33:34.617  5771  5795 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,11-09 10:33:34.617  5771  5795 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:D4
,11-09 10:33:34.619  5771  5795 I bt_hwcfg: vendor lib fwcfg completed
11-09 10:33:34.619  5771  5795 I bt_vendor: firmware callback
11-09 10:33:34.619  5771  5795 I bt_hci  : firmware_config_callback
,11-09 10:33:34.630  5771  5815 I bt_btu  : btu_task pending for preload complete event
,11-09 10:33:34.631  5771  5815 I bt_btu_task: Bluetooth chip preload is complete
11-09 10:33:34.631  5771  5815 I bt_btu  : btu_task received preload complete event
11-09 10:33:34.634  5771  5815 I         : BTE_InitTraceLevels -- TRC_HCI
11-09 10:33:34.634  5771  5815 I         : BTE_InitTraceLevels -- TRC_L2CAP
,11-09 10:33:34.634  5771  5815 I         : BTE_InitTraceLevels -- TRC_RFCOMM
11-09 10:33:34.634  5771  5815 I         : BTE_InitTraceLevels -- TRC_AVDT
11-09 10:33:34.634  5771  5815 I         : BTE_InitTraceLevels -- TRC_AVRC
11-09 10:33:34.634  5771  5815 I         : BTE_InitTraceLevels -- TRC_A2D
11-09 10:33:34.634  5771  5815 I         : BTE_InitTraceLevels -- TRC_BNEP
,11-09 10:33:34.634  5771  5815 I         : BTE_InitTraceLevels -- TRC_BTM
11-09 10:33:34.634  5771  5815 I         : BTE_InitTraceLevels -- TRC_GAP
11-09 10:33:34.634  5771  5815 I         : BTE_InitTraceLevels -- TRC_PAN
11-09 10:33:34.634  5771  5815 I         : BTE_InitTraceLevels -- TRC_SDP
11-09 10:33:34.634  5771  5815 I         : BTE_InitTraceLevels -- TRC_GATT
11-09 10:33:34.634  5771  5815 I         : BTE_InitTraceLevels -- TRC_SMP
11-09 10:33:34.634  5771  5815 I         : BTE_InitTraceLevels -- TRC_BTAPP
,11-09 10:33:34.635  5771  5815 I         : BTE_InitTraceLevels -- TRC_BTIF
,11-09 10:33:34.714  5771  5815 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf3ab5549
,11-09 10:33:34.714  5771  5815 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf3ab5549 
,11-09 10:33:34.731  5771  5791 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,11-09 10:33:34.732  5771  5791 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,11-09 10:33:34.733  5771  5791 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:D4
,11-09 10:33:34.735  5771  5791 D BluetoothAdapterProperties: Name is: Nexus 6P
,11-09 10:33:34.737  5771  5791 D BluetoothAdapterProperties: Scan Mode:20
,11-09 10:33:34.738  5771  5791 D BluetoothAdapterProperties: Discoverable Timeout:120
11-09 10:33:34.738  5771  5791 D bt_hci  : do_postload posting postload work item
11-09 10:33:34.738  5771  5795 I bt_hci  : event_postload
11-09 10:33:34.738  5771  5795 I bt_vendor: sco_config_cb
11-09 10:33:34.738  5771  5795 I bt_hci  : sco_config_callback postload finished.
11-09 10:33:34.740  5771  5791 D bt_bte_conf: Device ID record 1 : primary
11-09 10:33:34.740  5771  5791 D bt_bte_conf:   vendorId            = 000f
11-09 10:33:34.740  5771  5791 D bt_bte_conf:   vendorIdSource      = 0001
11-09 10:33:34.740  5771  5791 D bt_bte_conf:   product             = 1200
11-09 10:33:34.740  5771  5791 D bt_bte_conf:   version             = 1436
11-09 10:33:34.740  5771  5791 D bt_bte_conf:   clientExecutableURL = 
11-09 10:33:34.740  5771  5791 D bt_bte_conf:   serviceDescription  = 
11-09 10:33:34.740  5771  5791 D bt_bte_conf:   documentationURL    = 
11-09 10:33:34.741  5771  5791 D bt_bte_conf: bte_load_did_conf no section named DID2.
11-09 10:33:34.741  5771  5788 D bt_stack_manager: event_start_up_stack finished
11-09 10:33:34.742  5771  5787 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
,11-09 10:33:34.743  5771  5787 D BluetoothAdapterProperties: Setting state to 15
,11-09 10:33:34.743  5615  5615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-09 10:33:34.743  5771  5787 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
11-09 10:33:34.745  5771  5787 I BluetoothAdapterState: Entering BleOnState
,11-09 10:33:34.747  5771  5795 I bt_vendor: low_power_mode_cb
,11-09 10:33:34.750  5771  5787 D BluetoothAdapterState: Current state: BLE ON, message: 1
11-09 10:33:34.750  5771  5787 D BluetoothAdapterProperties: Setting state to 11
11-09 10:33:34.750  5771  5787 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
11-09 10:33:34.751  5615  5615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-09 10:33:34.758  5615  5615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-09 10:33:34.766  5771  5771 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a44b98d
,11-09 10:33:34.767  5771  5771 D HeadsetService: Received start request. Starting profile...
11-09 10:33:34.768  5615  5615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-09 10:33:34.769  5771  5771 I BluetoothHeadsetServiceJni: classInitNative: succeeds
11-09 10:33:34.769  5771  5771 D HeadsetStateMachine: make
,11-09 10:33:34.772  5615  5615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-09 10:33:34.775  5615  5615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-09 10:33:34.777  5771  5787 I BluetoothAdapterState: Entering PendingCommandState
,11-09 10:33:34.778  5771  5771 D HeadsetStateMachine: max_hf_connections = 1
,11-09 10:33:34.778  5771  5771 I bt_bluedroid: get_profile_interface handsfree
11-09 10:33:34.778  5771  5791 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
11-09 10:33:34.778  5771  5791 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
11-09 10:33:34.781  5771  5771 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a44b98d
11-09 10:33:34.781  5771  5771 D A2dpService: Received start request. Starting profile...
11-09 10:33:34.782  5771  5771 I BluetoothAvrcpServiceJni: classInitNative: succeeds
11-09 10:33:34.782  5771  5771 I bt_bluedroid: get_profile_interface avrcp
,11-09 10:33:34.788  5771  5771 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,11-09 10:33:34.788  5771  5771 I BluetoothA2dpServiceJni: classInitNative: succeeds
11-09 10:33:34.788  5771  5771 D A2dpStateMachine: make
,11-09 10:33:34.789  5771  5771 I bt_bluedroid: get_profile_interface a2dp
,11-09 10:33:34.790  5771  5791 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
11-09 10:33:34.791  5771  5822 D A2dpStateMachine: Enter Disconnected: -2
,11-09 10:33:34.792  5771  5771 I BluetoothHidServiceJni: classInitNative: succeeds
,11-09 10:33:34.792  5771  5771 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a44b98d
,11-09 10:33:34.794  5725  5725 D BluetoothInputDevice: Proxy object connected
,11-09 10:33:34.794  5725  5725 D HidProfile: Bluetooth service connected
11-09 10:33:34.795  5771  5771 D HidService: Received start request. Starting profile...
11-09 10:33:34.795  5771  5771 I bt_bluedroid: get_profile_interface hidhost
11-09 10:33:34.795  5771  5791 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf3a9656d
11-09 10:33:34.795  5771  5771 D HidService: setHidService(): set to: null
11-09 10:33:34.795  5771  5791 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
11-09 10:33:34.798  5771  5771 I BluetoothHealthServiceJni: classInitNative: succeeds
11-09 10:33:34.799  3589  3589 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
11-09 10:33:34.799  5771  5771 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a44b98d
11-09 10:33:34.800  5771  5771 D HealthService: Received start request. Starting profile...
,11-09 10:33:34.801  5771  5771 I bt_bluedroid: get_profile_interface health
,11-09 10:33:34.802  5771  5771 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,11-09 10:33:34.803  5771  5771 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a44b98d
,11-09 10:33:34.804  5725  5725 D BluetoothPan: BluetoothPAN Proxy object connected
11-09 10:33:34.804  5771  5771 D PanService: Received start request. Starting profile...
,11-09 10:33:34.804  5771  5771 D BluetoothPanServiceJni: initializeNative(L110): pan
11-09 10:33:34.804  5725  5725 D PanProfile: Bluetooth service connected
11-09 10:33:34.804  5771  5771 I bt_bluedroid: get_profile_interface pan
11-09 10:33:34.805  5771  5791 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,11-09 10:33:34.807  5771  5771 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a44b98d
,11-09 10:33:34.808  5725  5725 D BluetoothMap: Proxy object connected
,11-09 10:33:34.809  5771  5771 D BluetoothMapService: Received start request. Starting profile...
11-09 10:33:34.809  5771  5771 D BluetoothMapService: start()
11-09 10:33:34.811  5771  5771 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
11-09 10:33:34.811  5771  5771 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
11-09 10:33:34.811  5771  5771 D BluetoothMapAppObserver: createReceiver()
,11-09 10:33:34.812  5771  5771 D BluetoothMapAppObserver: initObservers()
,11-09 10:33:34.813  5771  5771 D BluetoothMapAppObserver: getEnabledAccountItems()
11-09 10:33:34.813  5725  5725 D MapProfile: Bluetooth service connected
11-09 10:33:34.813  5725  5725 D BluetoothMap: getConnectedDevices()
11-09 10:33:34.813  5725  5725 D BluetoothMap: Bluetooth is Not enabled
,11-09 10:33:34.819  5771  5771 V SapService: SapBinder()
,11-09 10:33:34.819  5771  5771 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a44b98d
,11-09 10:33:34.819  5771  5771 D SapService: Received start request. Starting profile...
,11-09 10:33:34.819  5771  5771 V SapService: start()
11-09 10:33:34.821  5771  5771 V BluetoothAdapterState: isTurningOff()=false
11-09 10:33:34.821  5771  5771 V BluetoothAdapterState: isTurningOn()=true
11-09 10:33:34.821  5771  5771 V BluetoothAdapterState: isBleTurningOn()=false
11-09 10:33:34.821  5771  5820 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
11-09 10:33:34.821  5771  5771 V BluetoothAdapterState: isBleTurningOff()=false
11-09 10:33:34.821  5771  5771 V BluetoothAdapterState: isTurningOff()=false
11-09 10:33:34.821  5771  5771 V BluetoothAdapterState: isTurningOn()=true
11-09 10:33:34.821  5771  5771 V BluetoothAdapterState: isBleTurningOn()=false
11-09 10:33:34.821  5771  5771 V BluetoothAdapterState: isBleTurningOff()=false
11-09 10:33:34.821  5771  5771 V BluetoothAdapterState: isTurningOff()=false
11-09 10:33:34.821  5771  5771 V BluetoothAdapterState: isTurningOn()=true
11-09 10:33:34.821  5771  5771 V BluetoothAdapterState: isBleTurningOn()=false
11-09 10:33:34.821  5771  5771 V BluetoothAdapterState: isBleTurningOff()=false
11-09 10:33:34.822  5771  5771 V BluetoothAdapterState: isTurningOff()=false
11-09 10:33:34.822  5771  5771 V BluetoothAdapterState: isTurningOn()=true
11-09 10:33:34.822  5771  5771 V BluetoothAdapterState: isBleTurningOn()=false
11-09 10:33:34.822  5771  5771 V BluetoothAdapterState: isBleTurningOff()=false
11-09 10:33:34.822  5771  5771 V BluetoothAdapterState: isTurningOff()=false
,11-09 10:33:34.822  5771  5771 V BluetoothAdapterState: isTurningOn()=true
11-09 10:33:34.822  5771  5771 V BluetoothAdapterState: isBleTurningOn()=false
11-09 10:33:34.823  5771  5771 V BluetoothAdapterState: isBleTurningOff()=false
,11-09 10:33:34.823  5771  5771 V BluetoothAdapterState: isTurningOff()=false
11-09 10:33:34.823  5771  5771 V BluetoothAdapterState: isTurningOn()=true
11-09 10:33:34.823  5771  5771 V BluetoothAdapterState: isBleTurningOn()=false
11-09 10:33:34.823  5771  5771 V BluetoothAdapterState: isBleTurningOff()=false
11-09 10:33:34.824  5771  5771 V BluetoothAdapterState: isTurningOff()=false
11-09 10:33:34.824  5771  5771 V BluetoothAdapterState: isTurningOn()=true
11-09 10:33:34.824  5771  5771 V BluetoothAdapterState: isBleTurningOn()=false
11-09 10:33:34.824  5771  5771 V BluetoothAdapterState: isBleTurningOff()=false
11-09 10:33:34.824  5771  5787 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
11-09 10:33:34.824  5771  5787 D BluetoothAdapterProperties: ScanMode =  20
11-09 10:33:34.824  5771  5787 D BluetoothAdapterProperties: State =  11
,11-09 10:33:34.825  5771  5787 D BluetoothAdapterProperties: Setting state to 12
11-09 10:33:34.825  5771  5787 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
11-09 10:33:34.825  5771  5787 I BluetoothAdapterState: Entering OnState
11-09 10:33:34.825  3777  3802 D BluetoothHeadset: onBluetoothStateChange: up=true
11-09 10:33:34.826  3150  3984 D BluetoothPbap: onBluetoothStateChange: up=true
11-09 10:33:34.826  5615  5615 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
11-09 10:33:34.826  5771  5791 D BluetoothAdapterProperties: Scan Mode:21
11-09 10:33:34.826  5771  5791 D BluetoothAdapterProperties: Discoverable Timeout:120
11-09 10:33:34.827  5725  5736 D BluetoothPan: onBluetoothStateChange on: true
11-09 10:33:34.828  5725  5735 D BluetoothInputDevice: onBluetoothStateChange: up=true
11-09 10:33:34.828  5615  5615 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
,11-09 10:33:34.828  3150  3163 D BluetoothMap: onBluetoothStateChange: up=true
11-09 10:33:34.830  3150  3150 D BluetoothMap: Proxy object connected
11-09 10:33:34.830  3150  3150 D MapProfile: Bluetooth service connected
11-09 10:33:34.830  3150  3150 D BluetoothMap: getConnectedDevices()
11-09 10:33:34.830  5615  5615 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
11-09 10:33:34.830  3150  3984 D BluetoothHeadset: onBluetoothStateChange: up=true
11-09 10:33:34.831   931   948 D BluetoothHeadset: onBluetoothStateChange: up=true
,11-09 10:33:34.832  5725  5736 D BluetoothPbap: onBluetoothStateChange: up=true
,11-09 10:33:34.835  5725  5735 D BluetoothMap: onBluetoothStateChange: up=true
11-09 10:33:34.835  3150  3983 D BluetoothPan: onBluetoothStateChange on: true
11-09 10:33:34.836  5615  5615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-09 10:33:34.836  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-09 10:33:34.836  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-09 10:33:34.836  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-09 10:33:34.836  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-09 10:33:34.836  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-09 10:33:34.836  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-09 10:33:34.836  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
11-09 10:33:34.837  5771  5771 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
11-09 10:33:34.837  5771  5771 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
11-09 10:33:34.838  5615  5615 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
11-09 10:33:34.838   931   948 D BluetoothHeadset: onBluetoothStateChange: up=true
11-09 10:33:34.838  3150  3984 D BluetoothInputDevice: onBluetoothStateChange: up=true
11-09 10:33:34.838  3150  3150 D BluetoothPan: BluetoothPAN Proxy object connected
11-09 10:33:34.838  3150  3150 D PanProfile: Bluetooth service connected
11-09 10:33:34.838  5771  5771 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-09 10:33:34.840  3150  3150 D BluetoothInputDevice: Proxy object connected
,11-09 10:33:34.840  3150  3150 D HidProfile: Bluetooth service connected
,11-09 10:33:34.840   931   948 D BluetoothA2dp: onBluetoothStateChange: up=true
11-09 10:33:34.841   931   948 D BluetoothHeadset: onBluetoothStateChange: up=true
11-09 10:33:34.841  3150  3164 D BluetoothA2dp: onBluetoothStateChange: up=true
11-09 10:33:34.843  5771  5771 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-09 10:33:34.844  5615  5615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-09 10:33:34.844  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-09 10:33:34.844  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-09 10:33:34.844  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-09 10:33:34.844  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-09 10:33:34.844  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-09 10:33:34.844  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-09 10:33:34.844  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
11-09 10:33:34.845  5771  5771 D ObexServerSockets: Succeed to create listening sockets 
11-09 10:33:34.845  5771  5771 D ObexServerSockets0: startAccept()
11-09 10:33:34.845  5771  5771 D ObexServerSockets0: prepareForNewConnect()
11-09 10:33:34.845   931   931 I Telecom : BluetoothPhoneService: queryPhoneState
,11-09 10:33:34.848  5771  5771 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
,11-09 10:33:34.848  5615  5615 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
11-09 10:33:34.848  5771  5771 D BluetoothSdpJni: SDP Create record success - handle: 0
11-09 10:33:34.848  5771  5829 D ObexServerSockets0: Accepting socket connection...
11-09 10:33:34.849  5771  5830 D ObexServerSockets0: Accepting socket connection...
,11-09 10:33:34.850  5771  5771 D BluetoothMapService: onReceive
11-09 10:33:34.850  3150  3150 D BluetoothA2dp: Proxy object connected
11-09 10:33:34.850  5771  5771 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
11-09 10:33:34.850  5771  5771 D BluetoothMapService: STATE_ON
11-09 10:33:34.850  5725  5725 D LocalBluetoothProfileManager: Adding local A2DP profile
11-09 10:33:34.851   931   931 D BluetoothA2dp: Proxy object connected
11-09 10:33:34.853  5615  5615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-09 10:33:34.853  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-09 10:33:34.853  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-09 10:33:34.853  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-09 10:33:34.853  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-09 10:33:34.853  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-09 10:33:34.853  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-09 10:33:34.853  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,11-09 10:33:34.855  5615  5615 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,11-09 10:33:34.855  5725  5725 D LocalBluetoothProfileManager: Adding local HEADSET profile
11-09 10:33:34.855  5615  5615 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
11-09 10:33:34.855  5771  5831 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-09 10:33:34.857  5771  5831 D BluetoothSdpJni: sdpCreateSapsRecordNative:
11-09 10:33:34.857  5771  5831 D BluetoothSdpJni: SDP Create record success - handle: 1
11-09 10:33:34.858  5615  5615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-09 10:33:34.860  5615  5615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-09 10:33:34.861  5615  5615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-09 10:33:34.864  5725  5725 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,11-09 10:33:34.866  5725  5725 D BluetoothA2dp: Proxy object connected
,11-09 10:33:34.871  3589  3589 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,11-09 10:33:34.872  5725  5725 D DockEventReceiver: finishStartingService: stopping service
,11-09 10:33:34.878  5771  5771 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,11-09 10:33:34.878  3150  3150 D BluetoothPbap: Proxy object connected
11-09 10:33:34.878  5725  5725 D BluetoothPbap: Proxy object connected
11-09 10:33:34.878  5771  5771 D ObexServerSockets0: prepareForNewConnect()
11-09 10:33:34.878  3150  3150 D PbapServerProfile: Bluetooth service connected
11-09 10:33:34.878  5725  5725 D PbapServerProfile: Bluetooth service connected
,11-09 10:33:34.885  5771  5835 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-09 10:33:34.897  5771  5839 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-09 10:33:34.898  5615  5679 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-09 10:33:34.898  5615  5663 D io.jxcore.node.ConnectivityMonitor: stop
,11-09 10:33:34.899  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-09 10:33:34.899  5771  5839 I BtOppRfcommListener: Accept thread started.
11-09 10:33:34.900  5615  5663 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testIsWifiDirectSupported
11-09 10:33:34.901  5615  5663 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testIsBluetoothEnabled
11-09 10:33:34.903  5615  5663 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-09 10:33:34.904  5771  5787 D BluetoothAdapterState: Current state: ON, message: 23
11-09 10:33:34.904  5771  5787 D BluetoothAdapterProperties: Setting state to 13
11-09 10:33:34.904  5771  5787 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
11-09 10:33:34.905  5771  5787 D BluetoothAdapterProperties: onBluetoothDisable()
11-09 10:33:34.905  5771  5787 I BluetoothAdapterState: Entering PendingCommandState
,11-09 10:33:34.906  5771  5771 D BluetoothMapService: onReceive
,11-09 10:33:34.906  5771  5771 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
11-09 10:33:34.907  5771  5771 D BluetoothMapService: STATE_TURNING_OFF
11-09 10:33:34.907  5771  5771 D BluetoothMapService: MAP Service closeService in
11-09 10:33:34.907  5771  5771 D BluetoothMapMasInstance0: MAP Service shutdown
11-09 10:33:34.907  5771  5771 D ObexServerSockets0: shutdown(block = true)
11-09 10:33:34.907  5771  5829 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
11-09 10:33:34.908  5771  5771 D ObexServerSockets0: shutdown called from another thread - interrupt().
11-09 10:33:34.908  5771  5771 D ObexServerSockets0: shutdown called from another thread - interrupt().
11-09 10:33:34.908  5771  5817 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
11-09 10:33:34.908  5771  5830 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
11-09 10:33:34.910  5771  5771 I BtOppRfcommListener: stopping Accept Thread
11-09 10:33:34.910  5771  5839 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
11-09 10:33:34.910  5771  5839 I BtOppRfcommListener: BluetoothSocket listen thread finished
,11-09 10:33:34.910  5615  5615 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,11-09 10:33:34.911  5615  5615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-09 10:33:34.911  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-09 10:33:34.911  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-09 10:33:34.911  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-09 10:33:34.911  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-09 10:33:34.911  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-09 10:33:34.911  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-09 10:33:34.911  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
11-09 10:33:34.911  5615  5615 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-09 10:33:34.911  5615  5615 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
11-09 10:33:34.912  5771  5791 D BluetoothAdapterProperties: Scan Mode:20
11-09 10:33:34.913  5771  5787 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
11-09 10:33:34.915  5725  5725 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
11-09 10:33:34.915  5771  5771 D HeadsetService: Received stop request...Stopping profile...
11-09 10:33:34.916  5615  5615 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-09 10:33:34.916  5615  5615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-09 10:33:34.916  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-09 10:33:34.916  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-09 10:33:34.916  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-09 10:33:34.916  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-09 10:33:34.916  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-09 10:33:34.916  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-09 10:33:34.916  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
11-09 10:33:34.917  5615  5615 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-09 10:33:34.917  5615  5615 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,11-09 10:33:34.919  5771  5771 D A2dpService: Received stop request...Stopping profile...
,11-09 10:33:34.920  5771  5822 D A2dpStateMachine: Exit Disconnected: -1
,11-09 10:33:34.920  5725  5725 D DockEventReceiver: finishStartingService: stopping service
11-09 10:33:34.920   931   931 D BluetoothA2dp: Proxy object disconnected
11-09 10:33:34.921  5615  5615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-09 10:33:34.922  5725  5725 D BluetoothA2dp: Proxy object disconnected
11-09 10:33:34.923  5615  5615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-09 10:33:34.924  5771  5771 V BluetoothAdapterState: isTurningOff()=true
11-09 10:33:34.924  5771  5771 V BluetoothAdapterState: isTurningOn()=false
11-09 10:33:34.924  5771  5771 V BluetoothAdapterState: isBleTurningOn()=false
11-09 10:33:34.924  5771  5771 V BluetoothAdapterState: isBleTurningOff()=false
11-09 10:33:34.925  5771  5771 D HidService: Received stop request...Stopping profile...
11-09 10:33:34.925  5771  5771 D HidService: Stopping Bluetooth HidService
11-09 10:33:34.925  5725  5725 D BluetoothInputDevice: Proxy object disconnected
11-09 10:33:34.925  5725  5725 D HidProfile: Bluetooth service disconnected
11-09 10:33:34.927  3589  3589 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
11-09 10:33:34.928  5771  5771 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
11-09 10:33:34.928  5771  5771 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
11-09 10:33:34.928  5771  5815 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-09 10:33:34.928  5771  5815 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,11-09 10:33:34.928  5771  5815 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-09 10:33:34.929  5771  5791 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
11-09 10:33:34.929  5771  5791 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
11-09 10:33:34.929  5771  5771 D HealthService: Received stop request...Stopping profile...
11-09 10:33:34.929  5771  5771 V BluetoothAdapterState: isTurningOff()=true
11-09 10:33:34.929  5771  5771 V BluetoothAdapterState: isTurningOn()=false
11-09 10:33:34.929  5771  5771 V BluetoothAdapterState: isBleTurningOn()=false
11-09 10:33:34.929  5771  5771 V BluetoothAdapterState: isBleTurningOff()=false
,11-09 10:33:34.931  5771  5771 D PanService: Received stop request...Stopping profile...
11-09 10:33:34.932  5771  5771 D BluetoothMapService: Received stop request...Stopping profile...
11-09 10:33:34.932  5771  5771 D BluetoothMapService: stop()
11-09 10:33:34.933  5771  5771 D BluetoothMapAppObserver: deinitObservers()
11-09 10:33:34.933  5771  5771 D BluetoothMapAppObserver: removeReceiver()
11-09 10:33:34.934  5771  5791 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
,11-09 10:33:34.934  5771  5815 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-09 10:33:34.934  5771  5815 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-09 10:33:34.934  5771  5815 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
11-09 10:33:34.934  5771  5771 D SapService: Received stop request...Stopping profile...
11-09 10:33:34.934  5771  5815 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
11-09 10:33:34.934  5771  5771 V SapService: stop()
11-09 10:33:34.934  5771  5815 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
11-09 10:33:34.934  5771  5815 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
11-09 10:33:34.935  5771  5771 V BluetoothAdapterState: isTurningOff()=true
11-09 10:33:34.935  5771  5771 V BluetoothAdapterState: isTurningOn()=false
11-09 10:33:34.935  5771  5771 V BluetoothAdapterState: isBleTurningOn()=false
11-09 10:33:34.935  5771  5771 V BluetoothAdapterState: isBleTurningOff()=false
11-09 10:33:34.935  5771  5771 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
11-09 10:33:34.936  5771  5771 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
11-09 10:33:34.936  5771  5791 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
11-09 10:33:34.936  5725  5725 D BluetoothPan: BluetoothPAN Proxy object disconnected
11-09 10:33:34.936  5725  5725 D PanProfile: Bluetooth service disconnected
11-09 10:33:34.936  5725  5725 D BluetoothMap: Proxy object disconnected
11-09 10:33:34.936  5725  5725 D MapProfile: Bluetooth service disconnected
11-09 10:33:34.937  5725  5725 D BluetoothPbap: Proxy object disconnected
11-09 10:33:34.937  5725  5725 D PbapServerProfile: Bluetooth service disconnected
11-09 10:33:34.939  3150  3150 D BluetoothA2dp: Proxy object disconnected
11-09 10:33:34.939  3150  3150 D BluetoothInputDevice: Proxy object disconnected
11-09 10:33:34.939  3150  3150 D HidProfile: Bluetooth service disconnected
11-09 10:33:34.940  3150  3150 D BluetoothPan: BluetoothPAN Proxy object disconnected
11-09 10:33:34.940  3150  3150 D PanProfile: Bluetooth service disconnected
11-09 10:33:34.940  3150  3150 D BluetoothMap: Proxy object disconnected
11-09 10:33:34.940  3150  3150 D MapProfile: Bluetooth service disconnected
11-09 10:33:34.940  3150  3150 D BluetoothPbap: Proxy object disconnected
11-09 10:33:34.940  3150  3150 D PbapServerProfile: Bluetooth service disconnected
,11-09 10:33:34.941  5771  5771 V BluetoothAdapterState: isTurningOff()=true
11-09 10:33:34.941  5771  5771 V BluetoothAdapterState: isTurningOn()=false
11-09 10:33:34.941  5771  5771 V BluetoothAdapterState: isBleTurningOn()=false
,11-09 10:33:34.941  5771  5771 V BluetoothAdapterState: isBleTurningOff()=false
11-09 10:33:34.941  5771  5771 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
11-09 10:33:34.941  5771  5791 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
11-09 10:33:34.941  5771  5771 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
,11-09 10:33:34.942  5771  5771 V BluetoothAdapterState: isTurningOff()=true
11-09 10:33:34.942  5771  5771 V BluetoothAdapterState: isTurningOn()=false
11-09 10:33:34.942  5771  5771 V BluetoothAdapterState: isBleTurningOn()=false
11-09 10:33:34.942  5771  5771 V BluetoothAdapterState: isBleTurningOff()=false
11-09 10:33:34.942  5771  5771 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
11-09 10:33:34.942  5771  5771 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
,11-09 10:33:34.943  5771  5771 D BluetoothMapService: MAP Service closeService in
11-09 10:33:34.943  5771  5771 V BluetoothAdapterState: isTurningOff()=true
11-09 10:33:34.943  5771  5771 V BluetoothAdapterState: isTurningOn()=false
11-09 10:33:34.943  5771  5771 V BluetoothAdapterState: isBleTurningOn()=false
11-09 10:33:34.943  5771  5771 V BluetoothAdapterState: isBleTurningOff()=false
11-09 10:33:34.943  5771  5771 D BluetoothMapService: cleanup()
,11-09 10:33:34.943  5771  5771 D BluetoothMapService: MAP Service closeService in
11-09 10:33:34.944  5771  5771 V BluetoothAdapterState: isTurningOff()=true
11-09 10:33:34.944  5771  5771 V BluetoothAdapterState: isTurningOn()=false
11-09 10:33:34.944  5771  5771 V BluetoothAdapterState: isBleTurningOn()=false
,11-09 10:33:34.944  5771  5771 V BluetoothAdapterState: isBleTurningOff()=false
11-09 10:33:34.944  5771  5787 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
11-09 10:33:34.944  5771  5787 D BluetoothAdapterProperties: Setting state to 15
11-09 10:33:34.944  5771  5787 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
11-09 10:33:34.945  5771  5787 I BluetoothAdapterState: Entering BleOnState
11-09 10:33:34.945  5725  5736 D BluetoothHeadset: onBluetoothStateChange: up=false
11-09 10:33:34.945  3777  3805 D BluetoothHeadset: onBluetoothStateChange: up=false
11-09 10:33:34.945  3150  3164 D BluetoothPbap: onBluetoothStateChange: up=false
11-09 10:33:34.946  5725  5735 D BluetoothPan: onBluetoothStateChange on: false
11-09 10:33:34.947  5725  5736 D BluetoothInputDevice: onBluetoothStateChange: up=false
11-09 10:33:34.947  3150  3164 D BluetoothMap: onBluetoothStateChange: up=false
11-09 10:33:34.947  3150  3983 D BluetoothHeadset: onBluetoothStateChange: up=false
11-09 10:33:34.948   931   948 D BluetoothHeadset: onBluetoothStateChange: up=false
11-09 10:33:34.948  5725  5735 D BluetoothPbap: onBluetoothStateChange: up=false
11-09 10:33:34.948  5725  5736 D BluetoothMap: onBluetoothStateChange: up=false
11-09 10:33:34.949  3150  3163 D BluetoothPan: onBluetoothStateChange on: false
11-09 10:33:34.949   931   948 D BluetoothHeadset: onBluetoothStateChange: up=false
11-09 10:33:34.949  3150  3984 D BluetoothInputDevice: onBluetoothStateChange: up=false
11-09 10:33:34.950   931   948 D BluetoothA2dp: onBluetoothStateChange: up=false
,11-09 10:33:34.950   931   948 D BluetoothHeadset: onBluetoothStateChange: up=false
,11-09 10:33:34.950  5725  5735 D BluetoothA2dp: onBluetoothStateChange: up=false
,11-09 10:33:34.950  3150  3164 D BluetoothA2dp: onBluetoothStateChange: up=false
11-09 10:33:34.951  5771  5787 D BluetoothAdapterState: Current state: BLE ON, message: 20
11-09 10:33:34.951  5771  5787 D BluetoothAdapterProperties: Setting state to 16
11-09 10:33:34.951  5771  5787 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
11-09 10:33:34.951  5771  5787 D BluetoothAdapterProperties: onBleDisable
11-09 10:33:34.952  5771  5787 I BluetoothAdapterState: Entering PendingCommandState
11-09 10:33:34.952  5771  5788 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
11-09 10:33:34.953  5771  5815 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
11-09 10:33:34.953  5771  5815 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-09 10:33:34.954  5771  5791 D BluetoothAdapterProperties: Scan Mode:20
11-09 10:33:34.955  5725  5725 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
11-09 10:33:34.958  5615  5615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-09 10:33:34.960  3589  3589 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
11-09 10:33:34.962  5615  5615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-09 10:33:34.963  5725  5725 D DockEventReceiver: finishStartingService: stopping service
11-09 10:33:34.964  5615  5615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-09 10:33:34.966  5615  5615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-09 10:33:35.154  5771  5791 I bt_hci  : shut_down
,11-09 10:33:35.154  5771  5795 D bt_hwcfg: hw_epilog_process
11-09 10:33:35.155  5771  5795 I bt_vendor: low_power_mode_cb
,11-09 10:33:35.157  5771  5795 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,11-09 10:33:35.158  5771  5795 I bt_vendor: epilog_cb
11-09 10:33:35.158  5771  5795 I bt_hci  : epilog_finished_callback
11-09 10:33:35.158  5771  5791 I bt_hci_h4: hal_close
11-09 10:33:35.159  5771  5791 I bt_userial_vendor: device fd = 54 close
,11-09 10:33:35.280  5771  5788 D bt_stack_manager: event_shut_down_stack finished.
,11-09 10:33:35.281  5771  5787 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,11-09 10:33:35.284  5771  5771 D BtGatt.DebugUtils: handleDebugAction() action=null
11-09 10:33:35.284  5771  5787 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,11-09 10:33:35.285  5771  5771 D BtGatt.GattService: Received stop request...Stopping profile...
11-09 10:33:35.285  5771  5771 D BtGatt.GattService: stop()
11-09 10:33:35.285  5771  5771 D BtGatt.AdvertiseManager: advertise clients cleared
11-09 10:33:35.288  5771  5771 V BluetoothAdapterState: isTurningOff()=false
11-09 10:33:35.288  5771  5771 V BluetoothAdapterState: isTurningOn()=false
11-09 10:33:35.288  5771  5771 V BluetoothAdapterState: isBleTurningOn()=false
11-09 10:33:35.288  5771  5771 V BluetoothAdapterState: isBleTurningOff()=true
11-09 10:33:35.289  5771  5787 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
11-09 10:33:35.289   931  2959 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
11-09 10:33:35.289  5771  5787 D BluetoothAdapterProperties: Setting state to 10
,11-09 10:33:35.289  5771  5787 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
11-09 10:33:35.290  5771  5787 I BluetoothAdapterState: Entering OffState
,11-09 10:33:35.292   931   948 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,11-09 10:33:35.306  5771  5771 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,11-09 10:33:35.306  5771  5771 W BluetoothSdpJni: Cleaning up Bluetooth Health object
11-09 10:33:35.306  5771  5771 I BluetoothServiceJni: cleanupNative: return from cleanup
11-09 10:33:35.307  5771  5788 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,11-09 10:33:35.314  5771  5771 I art     : System.exit called, status: 0
,11-09 10:33:35.314  5771  5771 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,11-09 10:33:35.342   931  3158 I ActivityManager: Process com.android.bluetooth (pid 5771) has died
,11-09 10:33:35.410  5615  5679 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-09 10:33:35.410  5615  5679 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-09 10:33:35.410  5615  5679 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-09 10:33:35.410  5615  5679 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-09 10:33:35.410  5615  5679 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-09 10:33:35.410  5615  5679 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-09 10:33:35.410  5615  5679 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-09 10:33:35.410  5615  5679 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-09 10:33:35.410  5615  5679 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
11-09 10:33:35.410  5615  5679 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-09 10:33:35.411  5615  5679 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,11-09 10:33:35.418  5615  5663 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-09 10:33:35.439   931   948 I ActivityManager: Start proc 5844:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,11-09 10:33:35.517  5844  5844 D AdapterServiceConfig: Adding HeadsetService
,11-09 10:33:35.517  5844  5844 D AdapterServiceConfig: Adding A2dpService
11-09 10:33:35.517  5844  5844 D AdapterServiceConfig: Adding HidService
11-09 10:33:35.518  5844  5844 D AdapterServiceConfig: Adding HealthService
,11-09 10:33:35.518  5844  5844 D AdapterServiceConfig: Adding PanService
11-09 10:33:35.518  5844  5844 D AdapterServiceConfig: Adding GattService
11-09 10:33:35.518  5844  5844 D AdapterServiceConfig: Adding BluetoothMapService
,11-09 10:33:35.518  5844  5844 D AdapterServiceConfig: Adding SapService
,11-09 10:33:35.528   931   948 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3d9247d:true
,11-09 10:33:35.528  5844  5844 D BluetoothAdapterState: make() - Creating AdapterState
,11-09 10:33:35.531  5844  5844 I bt_bluedroid: init
11-09 10:33:35.531  5844  5856 I BluetoothAdapterState: Entering OffState
,11-09 10:33:35.533  5844  5857 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,11-09 10:33:35.533  5844  5857 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
11-09 10:33:35.533  5844  5857 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
11-09 10:33:35.533  5844  5857 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
11-09 10:33:35.533  5844  5844 I bt_bluedroid: get_profile_interface socket
,11-09 10:33:35.535  5844  5860 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:D4
,11-09 10:33:35.536  5844  5844 I bt_bluedroid: get_profile_interface sdp
11-09 10:33:35.537  5844  5860 D BluetoothAdapterProperties: Name is: Nexus 6P
,11-09 10:33:35.540  5844  5855 I bt_bluedroid: config_hci_snoop_log
,11-09 10:33:35.541   931   948 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,11-09 10:33:35.545  5844  5856 D BluetoothAdapterState: Current state: OFF, message: 0
11-09 10:33:35.545  5844  5856 D BluetoothAdapterProperties: Setting state to 14
,11-09 10:33:35.545  5844  5856 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,11-09 10:33:35.547  5844  5856 D BluetoothBondStateMachine: make
,11-09 10:33:35.549  5844  5861 I BluetoothBondStateMachine: StableState(): Entering Off State
,11-09 10:33:35.551  5844  5856 I BluetoothAdapterState: Entering PendingCommandState
,11-09 10:33:35.552  5844  5844 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,11-09 10:33:35.555  5844  5844 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a44b98d
11-09 10:33:35.556  5844  5844 D BtGatt.DebugUtils: handleDebugAction() action=null
11-09 10:33:35.556  5844  5844 D BtGatt.GattService: Received start request. Starting profile...
11-09 10:33:35.556  5844  5844 D BtGatt.GattService: start()
11-09 10:33:35.556  5844  5844 I bt_bluedroid: get_profile_interface gatt
,11-09 10:33:35.558  5844  5844 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a44b98d
11-09 10:33:35.558  5844  5844 D BtGatt.AdvertiseManager: advertise manager created
,11-09 10:33:35.563  5844  5844 V BluetoothAdapterState: isTurningOff()=false
,11-09 10:33:35.564  5844  5844 V BluetoothAdapterState: isTurningOn()=false
11-09 10:33:35.564  5844  5844 V BluetoothAdapterState: isBleTurningOn()=true
11-09 10:33:35.564  5844  5844 V BluetoothAdapterState: isBleTurningOff()=false
11-09 10:33:35.564  5844  5856 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,11-09 10:33:35.566  5844  5856 I bt_bluedroid: bt_bluedroid
,11-09 10:33:35.566  5844  5857 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,11-09 10:33:35.566  5844  5857 I bt_hci  : start_up
,11-09 10:33:35.572  5844  5857 I bt_vendor: alloc value 0xf3b37871
11-09 10:33:35.572  5844  5857 I bt_vendor: init
,11-09 10:33:35.572  5844  5857 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
11-09 10:33:35.572  5844  5857 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,11-09 10:33:35.681  5844  5857 D bt_hci  : start_up starting async portion
,11-09 10:33:35.681  5844  5864 I bt_hci  : event_finish_startup
11-09 10:33:35.681  5844  5864 I bt_hci_h4: hal_open
11-09 10:33:35.681  5844  5864 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,11-09 10:33:35.683  5844  5864 I bt_userial_vendor: device fd = 54 open
,11-09 10:33:35.681  5865  5865 W irq/448-msm_hs_: type=1400 audit(0.0:122): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-09 10:33:35.695  5844  5864 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,11-09 10:33:35.697  5844  5864 D bt_hwcfg: Chipset BCM4358A3
,11-09 10:33:35.697  5844  5864 D bt_hwcfg: Target name = [BCM4358A3]
11-09 10:33:35.697  5844  5864 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,11-09 10:33:35.923  5844  5856 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 0
,11-09 10:33:36.092  5844  5864 I bt_hwcfg: bt vendor lib: set UART baud 115200
,11-09 10:33:36.093  5844  5864 D bt_hwcfg: Settlement delay -- 100 ms
11-09 10:33:36.093  5844  5864 I bt_hwcfg: Setting fw settlement delay to 100 
,11-09 10:33:36.217  5844  5864 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,11-09 10:33:36.218  5844  5864 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:D4
,11-09 10:33:36.219  5844  5864 I bt_hwcfg: vendor lib fwcfg completed
11-09 10:33:36.219  5844  5864 I bt_vendor: firmware callback
11-09 10:33:36.219  5844  5864 I bt_hci  : firmware_config_callback
,11-09 10:33:36.226  5844  5867 I bt_btu  : btu_task pending for preload complete event
,11-09 10:33:36.227  5844  5867 I bt_btu_task: Bluetooth chip preload is complete
,11-09 10:33:36.227  5844  5867 I bt_btu  : btu_task received preload complete event
,11-09 10:33:36.233  5844  5867 I         : BTE_InitTraceLevels -- TRC_HCI
,11-09 10:33:36.233  5844  5867 I         : BTE_InitTraceLevels -- TRC_L2CAP
11-09 10:33:36.233  5844  5867 I         : BTE_InitTraceLevels -- TRC_RFCOMM
11-09 10:33:36.233  5844  5867 I         : BTE_InitTraceLevels -- TRC_AVDT
,11-09 10:33:36.233  5844  5867 I         : BTE_InitTraceLevels -- TRC_AVRC
11-09 10:33:36.233  5844  5867 I         : BTE_InitTraceLevels -- TRC_A2D
11-09 10:33:36.234  5844  5867 I         : BTE_InitTraceLevels -- TRC_BNEP
,11-09 10:33:36.234  5844  5867 I         : BTE_InitTraceLevels -- TRC_BTM
11-09 10:33:36.234  5844  5867 I         : BTE_InitTraceLevels -- TRC_GAP
,11-09 10:33:36.234  5844  5867 I         : BTE_InitTraceLevels -- TRC_PAN
11-09 10:33:36.234  5844  5867 I         : BTE_InitTraceLevels -- TRC_SDP
11-09 10:33:36.234  5844  5867 I         : BTE_InitTraceLevels -- TRC_GATT
11-09 10:33:36.234  5844  5867 I         : BTE_InitTraceLevels -- TRC_SMP
11-09 10:33:36.234  5844  5867 I         : BTE_InitTraceLevels -- TRC_BTAPP
,11-09 10:33:36.235  5844  5867 I         : BTE_InitTraceLevels -- TRC_BTIF
,11-09 10:33:36.319  5844  5867 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf3ab5549
,11-09 10:33:36.320  5844  5867 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf3ab5549 
,11-09 10:33:36.336  5844  5860 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,11-09 10:33:36.338  5844  5860 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,11-09 10:33:36.339  5844  5860 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:D4
,11-09 10:33:36.342  5844  5860 D BluetoothAdapterProperties: Name is: Nexus 6P
,11-09 10:33:36.345  5844  5860 D BluetoothAdapterProperties: Scan Mode:20
11-09 10:33:36.346  5844  5860 D BluetoothAdapterProperties: Discoverable Timeout:120
,11-09 10:33:36.346  5844  5860 D bt_hci  : do_postload posting postload work item
11-09 10:33:36.347  5844  5864 I bt_hci  : event_postload
11-09 10:33:36.347  5844  5864 I bt_vendor: sco_config_cb
11-09 10:33:36.347  5844  5864 I bt_hci  : sco_config_callback postload finished.
,11-09 10:33:36.352  5615  5615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-09 10:33:36.353  5844  5860 D bt_bte_conf: Device ID record 1 : primary
11-09 10:33:36.353  5844  5860 D bt_bte_conf:   vendorId            = 000f
11-09 10:33:36.354  5844  5860 D bt_bte_conf:   vendorIdSource      = 0001
11-09 10:33:36.354  5844  5860 D bt_bte_conf:   product             = 1200
11-09 10:33:36.354  5844  5860 D bt_bte_conf:   version             = 1436
11-09 10:33:36.354  5844  5860 D bt_bte_conf:   clientExecutableURL = 
11-09 10:33:36.354  5844  5860 D bt_bte_conf:   serviceDescription  = 
11-09 10:33:36.354  5844  5860 D bt_bte_conf:   documentationURL    = 
11-09 10:33:36.354  5844  5860 D bt_bte_conf: bte_load_did_conf no section named DID2.
11-09 10:33:36.354  5844  5857 D bt_stack_manager: event_start_up_stack finished
,11-09 10:33:36.355  5844  5856 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
11-09 10:33:36.355  5844  5856 D BluetoothAdapterProperties: Setting state to 15
11-09 10:33:36.355  5844  5856 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
11-09 10:33:36.357  5615  5615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-09 10:33:36.357  5844  5856 I BluetoothAdapterState: Entering BleOnState
11-09 10:33:36.360  5844  5864 I bt_vendor: low_power_mode_cb
,11-09 10:33:36.361  5844  5856 D BluetoothAdapterState: Current state: BLE ON, message: 1
,11-09 10:33:36.361  5844  5856 D BluetoothAdapterProperties: Setting state to 11
11-09 10:33:36.361  5844  5856 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,11-09 10:33:36.371  5844  5844 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a44b98d
,11-09 10:33:36.372  5615  5615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-09 10:33:36.376  5615  5615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-09 10:33:36.379  3150  3983 D BluetoothHeadset: Proxy object connected
,11-09 10:33:36.379  5844  5844 D HeadsetService: Received start request. Starting profile...
11-09 10:33:36.379  3150  3150 D HeadsetProfile: Bluetooth service connected
,11-09 10:33:36.379   931   931 D BluetoothHeadset: Proxy object connected
11-09 10:33:36.379   931   931 D BluetoothHeadset: Proxy object connected
11-09 10:33:36.379   931   931 D BluetoothHeadset: Proxy object connected
11-09 10:33:36.380  3777  3802 D BluetoothHeadset: Proxy object connected
11-09 10:33:36.381  5725  5735 D BluetoothHeadset: Proxy object connected
11-09 10:33:36.381  5844  5844 I BluetoothHeadsetServiceJni: classInitNative: succeeds
11-09 10:33:36.382  5844  5844 D HeadsetStateMachine: make
,11-09 10:33:36.387  5725  5725 D HeadsetProfile: Bluetooth service connected
11-09 10:33:36.388  5844  5856 I BluetoothAdapterState: Entering PendingCommandState
,11-09 10:33:36.390  5844  5844 D HeadsetStateMachine: max_hf_connections = 1
11-09 10:33:36.390  5844  5844 I bt_bluedroid: get_profile_interface handsfree
,11-09 10:33:36.392  5844  5860 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
11-09 10:33:36.392  5844  5860 E bt_btif : btif_hf_upstreams_evt: Invalid index 250
,11-09 10:33:36.394  5844  5844 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a44b98d
11-09 10:33:36.395  5844  5844 D A2dpService: Received start request. Starting profile...
11-09 10:33:36.396  5844  5844 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,11-09 10:33:36.396  3589  3589 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
11-09 10:33:36.396  5844  5844 I bt_bluedroid: get_profile_interface avrcp
,11-09 10:33:36.402  5844  5844 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,11-09 10:33:36.402  5844  5844 I BluetoothA2dpServiceJni: classInitNative: succeeds
11-09 10:33:36.402  5844  5844 D A2dpStateMachine: make
11-09 10:33:36.403  5844  5844 I bt_bluedroid: get_profile_interface a2dp
,11-09 10:33:36.404  5844  5860 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,11-09 10:33:36.405  5844  5875 D A2dpStateMachine: Enter Disconnected: -2
,11-09 10:33:36.406  5844  5844 I BluetoothHidServiceJni: classInitNative: succeeds
,11-09 10:33:36.406  5844  5844 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a44b98d
,11-09 10:33:36.407  5844  5844 D HidService: Received start request. Starting profile...
11-09 10:33:36.407  5844  5844 I bt_bluedroid: get_profile_interface hidhost
11-09 10:33:36.407  5844  5844 D HidService: setHidService(): set to: null
11-09 10:33:36.408  5844  5860 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf3a9656d
11-09 10:33:36.408  5844  5844 I BluetoothHealthServiceJni: classInitNative: succeeds
11-09 10:33:36.408  5844  5860 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
11-09 10:33:36.409  5844  5844 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a44b98d
11-09 10:33:36.409  5844  5844 D HealthService: Received start request. Starting profile...
,11-09 10:33:36.411  5844  5844 I bt_bluedroid: get_profile_interface health
,11-09 10:33:36.411  5844  5844 I BluetoothPanServiceJni: classInitNative(L105): succeeds
11-09 10:33:36.412  5844  5844 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a44b98d
,11-09 10:33:36.413  5844  5844 D PanService: Received start request. Starting profile...
,11-09 10:33:36.413  5844  5844 D BluetoothPanServiceJni: initializeNative(L110): pan
11-09 10:33:36.413  5844  5844 I bt_bluedroid: get_profile_interface pan
11-09 10:33:36.413  5844  5860 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
11-09 10:33:36.415  5844  5844 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a44b98d
,11-09 10:33:36.416  5844  5844 D BluetoothMapService: Received start request. Starting profile...
,11-09 10:33:36.416  5844  5844 D BluetoothMapService: start()
,11-09 10:33:36.419  5844  5844 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,11-09 10:33:36.420  5844  5844 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
11-09 10:33:36.420  5844  5844 D BluetoothMapAppObserver: createReceiver()
11-09 10:33:36.421  5844  5844 D BluetoothMapAppObserver: initObservers()
11-09 10:33:36.422  5844  5844 D BluetoothMapAppObserver: getEnabledAccountItems()
,11-09 10:33:36.425  5844  5856 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 0
,11-09 10:33:36.430  5844  5844 V SapService: SapBinder()
,11-09 10:33:36.430  5844  5844 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a44b98d
11-09 10:33:36.431  5844  5844 D SapService: Received start request. Starting profile...
11-09 10:33:36.431  5844  5844 V SapService: start()
,11-09 10:33:36.433  5844  5844 V BluetoothAdapterState: isTurningOff()=false
,11-09 10:33:36.433  5844  5844 V BluetoothAdapterState: isTurningOn()=true
11-09 10:33:36.433  5844  5844 V BluetoothAdapterState: isBleTurningOn()=false
11-09 10:33:36.433  5844  5844 V BluetoothAdapterState: isBleTurningOff()=false
,11-09 10:33:36.434  5844  5873 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
11-09 10:33:36.434  5844  5844 V BluetoothAdapterState: isTurningOff()=false
11-09 10:33:36.434  5844  5844 V BluetoothAdapterState: isTurningOn()=true
11-09 10:33:36.434  5844  5844 V BluetoothAdapterState: isBleTurningOn()=false
11-09 10:33:36.434  5844  5844 V BluetoothAdapterState: isBleTurningOff()=false
11-09 10:33:36.434  5844  5844 V BluetoothAdapterState: isTurningOff()=false
,11-09 10:33:36.434  5844  5844 V BluetoothAdapterState: isTurningOn()=true
11-09 10:33:36.434  5844  5844 V BluetoothAdapterState: isBleTurningOn()=false
11-09 10:33:36.434  5844  5844 V BluetoothAdapterState: isBleTurningOff()=false
11-09 10:33:36.435  5844  5844 V BluetoothAdapterState: isTurningOff()=false
11-09 10:33:36.435  5844  5844 V BluetoothAdapterState: isTurningOn()=true
,11-09 10:33:36.435  5844  5844 V BluetoothAdapterState: isBleTurningOn()=false
11-09 10:33:36.435  5844  5844 V BluetoothAdapterState: isBleTurningOff()=false
11-09 10:33:36.435  5844  5844 V BluetoothAdapterState: isTurningOff()=false
11-09 10:33:36.435  5844  5844 V BluetoothAdapterState: isTurningOn()=true
11-09 10:33:36.435  5844  5844 V BluetoothAdapterState: isBleTurningOn()=false
11-09 10:33:36.435  5844  5844 V BluetoothAdapterState: isBleTurningOff()=false
11-09 10:33:36.435  5844  5844 V BluetoothAdapterState: isTurningOff()=false
11-09 10:33:36.436  5844  5844 V BluetoothAdapterState: isTurningOn()=true
11-09 10:33:36.436  5844  5844 V BluetoothAdapterState: isBleTurningOn()=false
11-09 10:33:36.436  5844  5844 V BluetoothAdapterState: isBleTurningOff()=false
11-09 10:33:36.436  5844  5844 V BluetoothAdapterState: isTurningOff()=false
11-09 10:33:36.437  5844  5844 V BluetoothAdapterState: isTurningOn()=true
11-09 10:33:36.437  5844  5844 V BluetoothAdapterState: isBleTurningOn()=false
,11-09 10:33:36.437  5844  5844 V BluetoothAdapterState: isBleTurningOff()=false
,11-09 10:33:36.437  5844  5856 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
,11-09 10:33:36.437  5844  5856 D BluetoothAdapterProperties: ScanMode =  20
11-09 10:33:36.437  5844  5856 D BluetoothAdapterProperties: State =  11
11-09 10:33:36.438  5844  5860 D BluetoothAdapterProperties: Scan Mode:21
11-09 10:33:36.438  5844  5860 D BluetoothAdapterProperties: Discoverable Timeout:120
11-09 10:33:36.438  5844  5856 D BluetoothAdapterProperties: Setting state to 12
11-09 10:33:36.439  5844  5856 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
11-09 10:33:36.439  5615  5615 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
11-09 10:33:36.439  5844  5856 I BluetoothAdapterState: Entering OnState
,11-09 10:33:36.439  5725  5736 D BluetoothHeadset: onBluetoothStateChange: up=true
11-09 10:33:36.440  3777  3991 D BluetoothHeadset: onBluetoothStateChange: up=true
11-09 10:33:36.440  3150  3164 D BluetoothPbap: onBluetoothStateChange: up=true
,11-09 10:33:36.442  5725  5735 D BluetoothPan: onBluetoothStateChange on: true
,11-09 10:33:36.444  5725  5736 D BluetoothInputDevice: onBluetoothStateChange: up=true
11-09 10:33:36.444  5615  5615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-09 10:33:36.444  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-09 10:33:36.444  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-09 10:33:36.444  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-09 10:33:36.444  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-09 10:33:36.444  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-09 10:33:36.444  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-09 10:33:36.444  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
11-09 10:33:36.446  3150  3163 D BluetoothMap: onBluetoothStateChange: up=true
11-09 10:33:36.446  5615  5615 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
11-09 10:33:36.448  3150  3983 D BluetoothHeadset: onBluetoothStateChange: up=true
11-09 10:33:36.448   931   948 D BluetoothHeadset: onBluetoothStateChange: up=true
,11-09 10:33:36.448  5844  5844 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
11-09 10:33:36.448  5725  5736 D BluetoothPbap: onBluetoothStateChange: up=true
11-09 10:33:36.448  5844  5844 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
11-09 10:33:36.449  5725  5735 D BluetoothMap: onBluetoothStateChange: up=true
11-09 10:33:36.450  5844  5844 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-09 10:33:36.450  5615  5615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-09 10:33:36.450  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-09 10:33:36.450  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-09 10:33:36.450  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-09 10:33:36.450  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-09 10:33:36.450  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-09 10:33:36.450  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-09 10:33:36.450  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
11-09 10:33:36.451  3150  3984 D BluetoothPan: onBluetoothStateChange on: true
11-09 10:33:36.451  5725  5725 D BluetoothPan: BluetoothPAN Proxy object connected
11-09 10:33:36.451  5725  5725 D PanProfile: Bluetooth service connected
11-09 10:33:36.451  5725  5725 D BluetoothInputDevice: Proxy object connected
11-09 10:33:36.451  5844  5844 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-09 10:33:36.452  5725  5725 D HidProfile: Bluetooth service connected
11-09 10:33:36.453  5615  5615 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
11-09 10:33:36.454  3150  3150 D BluetoothPan: BluetoothPAN Proxy object connected
11-09 10:33:36.454  3150  3150 D PanProfile: Bluetooth service connected
,11-09 10:33:36.454  5844  5844 D ObexServerSockets: Succeed to create listening sockets 
11-09 10:33:36.454  5844  5844 D ObexServerSockets0: startAccept()
11-09 10:33:36.454  5844  5844 D ObexServerSockets0: prepareForNewConnect()
11-09 10:33:36.456  5844  5844 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
,11-09 10:33:36.456  5844  5844 D BluetoothSdpJni: SDP Create record success - handle: 0
11-09 10:33:36.456   931   948 D BluetoothHeadset: onBluetoothStateChange: up=true
11-09 10:33:36.456  3150  3163 D BluetoothInputDevice: onBluetoothStateChange: up=true
11-09 10:33:36.457  5844  5882 D ObexServerSockets0: Accepting socket connection...
11-09 10:33:36.457  5844  5883 D ObexServerSockets0: Accepting socket connection...
11-09 10:33:36.457  3150  3150 D BluetoothMap: Proxy object connected
11-09 10:33:36.457  3150  3150 D MapProfile: Bluetooth service connected
,11-09 10:33:36.457  3150  3150 D BluetoothMap: getConnectedDevices()
,11-09 10:33:36.458  5725  5725 D BluetoothMap: Proxy object connected
,11-09 10:33:36.458  5725  5725 D MapProfile: Bluetooth service connected
11-09 10:33:36.458  5725  5725 D BluetoothMap: getConnectedDevices()
11-09 10:33:36.458   931   948 D BluetoothA2dp: onBluetoothStateChange: up=true
11-09 10:33:36.459   931   948 D BluetoothHeadset: onBluetoothStateChange: up=true
11-09 10:33:36.459  5725  5735 D BluetoothA2dp: onBluetoothStateChange: up=true
11-09 10:33:36.459  3150  3150 D BluetoothInputDevice: Proxy object connected
11-09 10:33:36.459  3150  3150 D HidProfile: Bluetooth service connected
11-09 10:33:36.461  3150  3984 D BluetoothA2dp: onBluetoothStateChange: up=true
11-09 10:33:36.461   931   931 D BluetoothA2dp: Proxy object connected
11-09 10:33:36.462  3150  3150 D BluetoothA2dp: Proxy object connected
,11-09 10:33:36.463  5725  5725 D BluetoothA2dp: Proxy object connected
11-09 10:33:36.464  5615  5615 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
,11-09 10:33:36.465  5844  5844 D BluetoothMapService: onReceive
11-09 10:33:36.465  5844  5844 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
11-09 10:33:36.465  5844  5844 D BluetoothMapService: STATE_ON
11-09 10:33:36.466   931   931 I Telecom : BluetoothPhoneService: queryPhoneState
11-09 10:33:36.466   931   931 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
11-09 10:33:36.466  5615  5615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-09 10:33:36.468  5844  5885 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-09 10:33:36.470  5844  5885 D BluetoothSdpJni: sdpCreateSapsRecordNative:
11-09 10:33:36.470  5844  5885 D BluetoothSdpJni: SDP Create record success - handle: 1
,11-09 10:33:36.471  5615  5615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-09 10:33:36.475  5725  5725 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,11-09 10:33:36.480  3589  3589 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
11-09 10:33:36.481  5725  5725 D DockEventReceiver: finishStartingService: stopping service
,11-09 10:33:36.489  5725  5725 D BluetoothPbap: Proxy object connected
,11-09 10:33:36.489  5725  5725 D PbapServerProfile: Bluetooth service connected
,11-09 10:33:36.492  5844  5844 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,11-09 10:33:36.492  5844  5844 D ObexServerSockets0: prepareForNewConnect()
,11-09 10:33:36.494  3150  3150 D BluetoothPbap: Proxy object connected
11-09 10:33:36.494  3150  3150 D PbapServerProfile: Bluetooth service connected
,11-09 10:33:36.496  5844  5890 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-09 10:33:36.512  5844  5894 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-09 10:33:36.513  5844  5894 I BtOppRfcommListener: Accept thread started.
,11-09 10:33:36.938  5615  5679 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-09 10:33:36.938  5615  5679 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-09 10:33:36.938  5615  5679 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-09 10:33:36.938  5615  5679 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-09 10:33:36.938  5615  5679 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-09 10:33:36.938  5615  5679 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-09 10:33:36.938  5615  5679 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-09 10:33:36.938  5615  5679 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,11-09 10:33:36.943  5615  5679 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
11-09 10:33:36.946  5615  5663 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testIsWifiEnabled
,11-09 10:33:36.949   931   942 D WifiService: setWifiEnabled: false pid=5615, uid=10077
11-09 10:33:36.949   931   942 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-09 10:33:36.953  5615  5663 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-09 10:33:36.954   931  2957 D WifiStateMachine: WifiStateMachine: Leaving Connected state
11-09 10:33:36.954   931  2957 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
11-09 10:33:36.955   931  2957 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
11-09 10:33:36.955   931  2957 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-09 10:33:36.971   931  5785 D DhcpClient: Clearing IP address
,11-09 10:33:36.972   511   925 D CommandListener: Clearing all IP addresses on wlan0
,11-09 10:33:36.980   511   925 D CommandListener: Setting iface cfg
,11-09 10:33:36.985  3589  5814 V NativeCrypto: Read error: ssl=0x7f8a6cb000: I/O error during system call, Connection timed out
,11-09 10:33:36.986  3589  5814 V NativeCrypto: SSL shutdown failed: ssl=0x7f8a6cb000: I/O error during system call, Broken pipe
,11-09 10:33:36.989   931  4826 D ConnectivityService: reportNetworkConnectivity(101, false) by 10012
11-09 10:33:36.989   931  5777 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Forcing reevaluation for UID 10012
,11-09 10:33:36.991   931  2959 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
,11-09 10:33:36.991   931  2959 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 3
11-09 10:33:36.991   931  5777 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.gstatic.com": No address associated with hostname
11-09 10:33:36.994   931   931 D RttService: SCAN_AVAILABLE : 1
11-09 10:33:36.996   931  3065 D RttService: EnabledState got{ when=-1ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
11-09 10:33:36.997   538   538 E Parcel  : Reading a NULL string not supported here.
11-09 10:33:36.998   931  2959 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
11-09 10:33:37.001  3732  3848 W QCNEJ   : |CORE| network lost: 101
11-09 10:33:37.001  3732  3848 W QCNEJ   : |CORE| onLost: unbind the process to WIFI
,11-09 10:33:37.005   931  2957 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,11-09 10:33:37.005   931  5786 D DhcpClient: Receive thread stopped
,11-09 10:33:37.022   511   925 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
11-09 10:33:37.022   931  2957 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,11-09 10:33:37.043   511   925 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
11-09 10:33:37.043   511   925 D CommandListener: Clearing all IP addresses on wlan0
,11-09 10:33:37.044   931  2959 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
11-09 10:33:37.044   931  2959 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,11-09 10:33:37.045   931   948 D Tethering: MasterInitialState.processMessage what=3
,11-09 10:33:37.050  3963  3963 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
11-09 10:33:37.050   931  2957 D DhcpClient: doQuit
11-09 10:33:37.050   931  2957 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
11-09 10:33:37.051   931  5785 D DhcpClient: onQuitting
11-09 10:33:37.052  5720  5720 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
11-09 10:33:37.055  5615  5615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-09 10:33:37.055  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-09 10:33:37.055  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-09 10:33:37.055  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-09 10:33:37.055  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-09 10:33:37.055  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-09 10:33:37.055  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-09 10:33:37.055  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-09 10:33:37.055  4045  4045 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,11-09 10:33:37.057  5615  5615 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
11-09 10:33:37.059  4045  4045 D SystemUpdateService: onCreate
11-09 10:33:37.061  5615  5615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-09 10:33:37.061  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-09 10:33:37.061  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-09 10:33:37.061  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-09 10:33:37.061  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-09 10:33:37.061  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-09 10:33:37.061  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-09 10:33:37.061  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-09 10:33:37.062  4045  4045 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
11-09 10:33:37.063  5615  5615 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,11-09 10:33:37.066  5615  5615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-09 10:33:37.066  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-09 10:33:37.066  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-09 10:33:37.066  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-09 10:33:37.066  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-09 10:33:37.066  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-09 10:33:37.066  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-09 10:33:37.066  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,11-09 10:33:37.068  5615  5615 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,11-09 10:33:37.070  5615  5615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-09 10:33:37.071  5720  5720 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
,11-09 10:33:37.071  4045  5903 I SystemUpdateService: active receiver: enabled
,11-09 10:33:37.077  4045  4045 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,11-09 10:33:37.077  5720  5720 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,11-09 10:33:37.083  4045  4254 I iu.UploadsManager: num queued entries: 0
,11-09 10:33:37.083  4045  4254 I iu.UploadsManager: num updated entries: 0
11-09 10:33:37.084  4045  4254 I iu.SyncManager: NEXT; no task
,11-09 10:33:37.085  4045  5903 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,11-09 10:33:37.087  4045  4045 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,11-09 10:33:37.088  4045  4045 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,11-09 10:33:37.090  5418  5418 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,11-09 10:33:37.096  5418  5418 D SprintDMHelper: simOperator: 
,11-09 10:33:37.096  5418  5418 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,11-09 10:33:37.101   511   925 E Netd    : netlink response contains error (No such file or directory)
,11-09 10:33:37.103   931  2959 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,11-09 10:33:37.108  4045  5903 I SystemUpdateService: network: null; metered: false; mobile allowed: true
11-09 10:33:37.110  4045  5903 I SystemUpdateService: now status is 0 (complete)
11-09 10:33:37.110  4045  5903 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
11-09 10:33:37.110  4045  5903 I SystemUpdateService: file has been verified
,11-09 10:33:37.111  4045  5903 I SystemUpdateService: OTA package size = 21989297
11-09 10:33:37.111  5720  5720 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,11-09 10:33:37.126  4045  5903 I SystemUpdateService: showing system update notification
,11-09 10:33:37.131   931   931 V NotificationService: pkg=com.google.android.gms canInterrupt=false intercept=true
,11-09 10:33:37.132  5720  5720 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,11-09 10:33:37.133  4045  4045 D SystemUpdateService: onDestroy
,11-09 10:33:37.237   931  2957 D wifi    : In wifi stop Hal
11-09 10:33:37.237   931  2957 D wifi    : halHandle = 0x7f88adbe00, mVM = 0x7fa514d140, mCls = 0x101792
,11-09 10:33:37.237   931  5719 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
11-09 10:33:37.237   931  5719 D WifiHAL : Got a signal to exit!!!
11-09 10:33:37.237   931  5719 I WifiHAL : Exit wifi_event_loop
11-09 10:33:37.239   931  2957 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 11
11-09 10:33:37.239   931  2957 E WifiHAL : Event processing terminated
11-09 10:33:37.239   931  2957 D wifi    : In wifi cleaned up handler
11-09 10:33:37.239   931  2957 I WifiHAL : Internal cleanup completed
11-09 10:33:37.240  5615  5615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-09 10:33:37.238  4527  4527 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
11-09 10:33:37.247  3930  4187 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,11-09 10:33:37.247  5615  5615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-09 10:33:37.266   931  5719 D wifi    : set interface wlan0 flags (DOWN)
,11-09 10:33:37.267   931  2957 D WifiNative-HAL: HAL event thread stopped successfully
,11-09 10:33:37.460  5615  5679 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-09 10:33:37.460  5615  5679 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-09 10:33:37.460  5615  5679 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-09 10:33:37.460  5615  5679 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-09 10:33:37.460  5615  5679 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-09 10:33:37.460  5615  5679 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-09 10:33:37.460  5615  5679 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-09 10:33:37.460  5615  5679 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,11-09 10:33:37.471   931   948 D Tethering: InitialState.processMessage what=4
,11-09 10:33:37.472  5615  5679 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,11-09 10:33:37.475   931  3156 D WifiService: setWifiEnabled: true pid=5615, uid=10077
11-09 10:33:37.476   931  3156 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-09 10:33:37.477  5615  5663 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-09 10:33:37.479   931   948 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,11-09 10:33:37.483   511   925 D SoftapController: Softap fwReload - Ok
,11-09 10:33:37.487   511   925 D CommandListener: Setting iface cfg
,11-09 10:33:37.487   511   925 D CommandListener: Trying to bring down wlan0
,11-09 10:33:37.489   511   925 D CommandListener: Clearing all IP addresses on wlan0
,11-09 10:33:37.495   931  2957 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,11-09 10:33:37.842   540   540 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,11-09 10:33:37.846   540   540 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,11-09 10:33:37.980   931  3429 D WifiService: setWifiEnabled: true pid=5615, uid=10077
,11-09 10:33:37.981   931  3429 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-09 10:33:38.102   931  2957 D wifi    : set interface wlan0 flags (UP)
,11-09 10:33:38.103   931  2957 I WifiHAL : Initializing wifi
,11-09 10:33:38.103   931  2957 I WifiHAL : Creating socket
11-09 10:33:38.111   931  2957 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
,11-09 10:33:38.111   931   948 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
11-09 10:33:38.111   931  2957 D wifi    : Did set static halHandle = 0x7f88adbe00
11-09 10:33:38.111   931  2957 D wifi    : halHandle = 0x7f88adbe00, mVM = 0x7fa514d140, mCls = 0x1922
11-09 10:33:38.111   931  2957 D wifi    : array field set
11-09 10:33:38.112   931  2957 I WifiNative-HAL: interface[0] = wlan0
,11-09 10:33:38.119   931  5911 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=547753934336
,11-09 10:33:38.119   931  5911 D wifi    : waitForHalEvents called, vm = 0x7fa514d140, obj = 0x1922, env = 0x7f8ac82240
,11-09 10:33:38.173  5912  5912 I wpa_supplicant: Successfully initialized wpa_supplicant
,11-09 10:33:38.216   931  2957 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,11-09 10:33:38.224  5615  5615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-09 10:33:38.226  5615  5615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-09 10:33:38.243  5912  5912 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,11-09 10:33:38.248  5912  5912 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,11-09 10:33:38.248  5912  5912 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,11-09 10:33:38.258   931  2957 D WifiConfigStore: Loading config and enabling all networks 
,11-09 10:33:38.263  5615  5615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-09 10:33:38.263  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-09 10:33:38.263  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-09 10:33:38.263  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-09 10:33:38.263  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-09 10:33:38.263  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-09 10:33:38.263  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-09 10:33:38.263  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,11-09 10:33:38.264  5615  5615 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
11-09 10:33:38.267  5615  5615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-09 10:33:38.267  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-09 10:33:38.267  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-09 10:33:38.267  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-09 10:33:38.267  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-09 10:33:38.267  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-09 10:33:38.267  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-09 10:33:38.267  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,11-09 10:33:38.269  5615  5615 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,11-09 10:33:38.273   931  2957 D WifiConfigStore: loaded 0 passpoint configs
,11-09 10:33:38.274   931  2957 W WifiConfigStore: Upgrading network 4 to android.uid.system:1000
11-09 10:33:38.274   931  2957 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,11-09 10:33:38.274   931  2957 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
11-09 10:33:38.275   931  2957 W WifiConfigStore: Upgrading network 3 to android.uid.system:1000
,11-09 10:33:38.275   931  2957 W WifiConfigStore: Upgrading network 2 to android.uid.system:1000
11-09 10:33:38.275   931  2957 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,11-09 10:33:38.276   931  2957 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 5
11-09 10:33:38.276   931  2957 E WifiConfigStore: found sortedWifiConfigurations : "AndroidAP"WPA_PSK
11-09 10:33:38.276   931  2957 E WifiConfigStore: found sortedWifiConfigurations : "AndroidHotspot2346"WPA_PSK
,11-09 10:33:38.276   931  2957 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
11-09 10:33:38.276   931  2957 E WifiConfigStore: found sortedWifiConfigurations : "Thali_internal"WPA_PSK
11-09 10:33:38.276   931  2957 E WifiConfigStore: found sortedWifiConfigurations : "MC"WPA_PSK
,11-09 10:33:38.277   931  2957 D WifiNative-HAL: Setting external_sim to 1
11-09 10:33:38.278   931  2957 D wifi    : setting dfs flag to true, 0x7f88af5b60
11-09 10:33:38.278   931  2957 D WifiStateMachine: Setting OUI to DA-A1-19
11-09 10:33:38.278   931  2957 D wifi    : setting scan oui 0x7f88af5b60
11-09 10:33:38.278   931  2957 D WifiHAL : Sending mac address OUI
,11-09 10:33:38.278  4527  4527 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,11-09 10:33:38.280   931  2957 E native  : do suspend false
,11-09 10:33:38.287   931  2957 D wifi    : android_net_wifi_setLinkLayerStats: 1
11-09 10:33:38.287   931   931 D RttService: SCAN_AVAILABLE : 3
,11-09 10:33:38.287   931  3065 D RttService: DefaultState got{ when=-1ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,11-09 10:33:38.290   511   925 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,11-09 10:33:38.292   511   925 D CommandListener: Setting iface cfg
,11-09 10:33:38.295   931  2956 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '155 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 155 Failed to set address (No such device)'
,11-09 10:33:38.295   931  2956 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,11-09 10:33:38.299   931  2956 D WifiNative-HAL: p2pGetDeviceAddress
,11-09 10:33:38.303   931  2956 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:70
,11-09 10:33:38.304   931   946 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=113238 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=12 mControllerEnergyUsed=45 }
,11-09 10:33:38.491  5615  5679 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-09 10:33:38.491  5615  5679 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-09 10:33:38.491  5615  5679 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-09 10:33:38.491  5615  5679 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-09 10:33:38.491  5615  5679 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-09 10:33:38.491  5615  5679 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-09 10:33:38.491  5615  5679 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-09 10:33:38.491  5615  5679 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,11-09 10:33:38.497  5615  5679 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,11-09 10:33:38.502  5615  5663 D BluetoothAdapter: enable(): BT is already enabled..!
11-09 10:33:38.503   931  4826 D WifiService: setWifiEnabled: true pid=5615, uid=10077
11-09 10:33:38.504   931  4826 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
11-09 10:33:38.505  5615  5663 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,11-09 10:33:38.505  5615  5663 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-09 10:33:38.505  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-09 10:33:38.505  5615  5663 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,11-09 10:33:38.506  5615  5663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-09 10:33:38.506  5615  5663 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6cbe115 removed from the list
11-09 10:33:38.506  5615  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-09 10:33:38.506  5615  5663 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ea16c2a removed from the list
11-09 10:33:38.506  5615  5663 D io.jxcore.node.ConnectivityMonitor: stop
,11-09 10:33:38.506  5615  5663 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-09 10:33:38.506  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,11-09 10:33:38.513  5615  5663 I io.jxcore.node.IncomingSocketThreadTest: Starting test: testSetTcpPortNumber
,11-09 10:33:38.516  5615  5663 I io.jxcore.node.IncomingSocketThreadTest: Starting test: testGetTcpPortNumber
,11-09 10:33:38.519  5615  5663 I io.jxcore.node.IncomingSocketThreadTest: Starting test: testGetLocalHostPort
,11-09 10:33:38.521  5615  5663 I io.jxcore.node.IncomingSocketThreadTest: Starting test: testConstructor
,11-09 10:33:38.525  5615  5663 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityCreated
,11-09 10:33:38.527  5615  5663 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,11-09 10:33:38.528  5615  5663 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityResumed
,11-09 10:33:38.529  5615  5663 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,11-09 10:33:38.531  5615  5663 I io.jxcore.node.LifeCycleMonitorTest: Starting test: constructor
,11-09 10:33:38.536  5615  5663 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivitySaveInstanceState
,11-09 10:33:38.536  5615  5663 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@bb7e490 Bundle[{}]
11-09 10:33:38.537  5615  5663 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testStartStop
11-09 10:33:38.537  5615  5663 I io.jxcore.node.LifeCycleMonitor: start: OK
,11-09 10:33:38.538  5615  5663 I io.jxcore.node.LifeCycleMonitor: stop: OK
11-09 10:33:38.538  5615  5663 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityStarted
11-09 10:33:38.538  5615  5663 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
11-09 10:33:38.539  5615  5663 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityStopped
,11-09 10:33:38.539  5615  5663 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
11-09 10:33:38.540  5615  5663 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityDestroyed
11-09 10:33:38.540  5615  5663 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
,11-09 10:33:38.542  5615  5663 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityPaused
,11-09 10:33:38.543  5615  5663 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,11-09 10:33:38.546  5615  5663 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testToString
,11-09 10:33:38.547  5615  5663 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testToJsonObject
11-09 10:33:38.548  5615  5663 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testConstructorWithParameters
11-09 10:33:38.549  5615  5663 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testSetListeningOnPortNumber
11-09 10:33:38.549  5615  5663 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testGetListeningOnPortNumber
,11-09 10:33:38.551  5615  5663 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testDefaultConstructor
,11-09 10:33:38.553  5615  5663 I io.jxcore.node.OutgoingSocketThreadTest: Starting test: testClose
,11-09 10:33:38.555  5615  5663 I io.jxcore.node.OutgoingSocketThreadTest: Starting test: testGetListeningOnPortNumber
11-09 10:33:38.555  5615  5663 I io.jxcore.node.OutgoingSocketThreadTest: Starting test: testConstructor
,11-09 10:33:38.558  5615  5663 I io.jxcore.node.SocketThreadBaseTest: Starting test: testGetListener
,11-09 10:33:38.558  5615  5663 I io.jxcore.node.SocketThreadBaseTest: Starting test: testSetPeerProperties
,11-09 10:33:38.560  5615  5663 I io.jxcore.node.SocketThreadBaseTest: Starting test: testClose
,11-09 10:33:38.560  5615  5663 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 142)
11-09 10:33:38.561  5615  5663 I io.jxcore.node.SocketThreadBaseTest: Starting test: testCloseLocalSocketAndStreams
11-09 10:33:38.561  5615  5663 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
11-09 10:33:38.561  5615  5663 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 143)
11-09 10:33:38.561  5615  5663 I io.jxcore.node.SocketThreadBaseTest: Starting test: testGetPeerProperties
,11-09 10:33:38.563  5615  5663 I io.jxcore.node.SocketThreadBaseTest: Starting test: testEquals
,11-09 10:33:38.564  5615  5663 I io.jxcore.node.SocketThreadBaseTest: Starting test: testGetLocalHostAddressAsString
,11-09 10:33:38.565  5615  5663 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,11-09 10:33:38.566  5615  5663 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b167991 added. We now have 3 listener(s)
11-09 10:33:38.567  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-09 10:33:38.567  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-09 10:33:38.567  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-09 10:33:38.567  5615  5663 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-09 10:33:38.567  5615  5663 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8c220f6 added. We now have 3 listener(s)
11-09 10:33:38.567  5615  5663 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-09 10:33:38.569  5615  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,11-09 10:33:38.574  5615  5663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,11-09 10:33:38.576  5615  5663 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-09 10:33:38.576  5615  5663 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-09 10:33:38.576  5615  5663 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-09 10:33:38.576  5615  5663 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-09 10:33:38.576  5615  5663 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-09 10:33:38.576  5615  5663 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-09 10:33:38.576  5615  5663 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-09 10:33:38.576  5615  5663 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,11-09 10:33:38.578  5615  5663 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
11-09 10:33:38.578  5615  5663 D io.jxcore.node.ConnectivityMonitor: start: OK
11-09 10:33:38.579  5615  5615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-09 10:33:38.581  5615  5663 I io.jxcore.node.StartStopOperationHandlerTest: Starting test: testCancelCurrentOperation
,11-09 10:33:38.581  5615  5615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-09 10:33:38.581  5615  5663 I io.jxcore.node.StartStopOperationHandlerTest: Starting test: testExecuteStopOperation
11-09 10:33:38.581  5615  5663 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 5
11-09 10:33:38.582  5615  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 4 -> 5
11-09 10:33:38.582  5615  5663 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
11-09 10:33:38.582  5615  5663 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
11-09 10:33:38.582  5615  5663 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
11-09 10:33:38.582  5615  5663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,11-09 10:33:38.583  5615  5663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
11-09 10:33:38.583  5615  5663 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
11-09 10:33:38.584  5615  5663 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
11-09 10:33:38.584  5615  5663 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
,11-09 10:33:38.584  5615  5663 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
,11-09 10:33:38.584  5615  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
11-09 10:33:38.584  5615  5615 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
,11-09 10:33:38.584  5615  5663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,11-09 10:33:38.584  5615  5663 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
11-09 10:33:38.584  5615  5914 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
11-09 10:33:38.585  5615  5914 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-09 10:33:38.587  5615  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-09 10:33:38.584  5871  5871 W Binder_3: type=1400 audit(0.0:123): avc: denied { ioctl } for path="socket:[33963]" dev="sockfs" ino=33963 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-09 10:33:38.587  5615  5914 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
11-09 10:33:38.587  5615  5663 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,11-09 10:33:38.588  5615  5663 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
11-09 10:33:38.584  5871  5871 W Binder_3: type=1400 audit(0.0:124): avc: denied { ioctl } for path="socket:[33963]" dev="sockfs" ino=33963 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,11-09 10:33:38.592  5615  5663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,11-09 10:33:38.593  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,11-09 10:33:38.593  5615  5663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,11-09 10:33:38.596  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Current thread: Thread[Thread-62,5,main], id: 62
,11-09 10:33:38.596  5615  5663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
11-09 10:33:38.596  5615  5663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-09 10:33:38.596  5615  5663 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 05 60 83 34 25 D7 D4
11-09 10:33:38.597  5615  5663 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[5, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-09 10:33:38.597  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: Current thread: Thread[Thread-62,5,main], id: 62
11-09 10:33:38.597  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData finished: Current thread: Thread[Thread-62,5,main], id: 62
11-09 10:33:38.597  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = NOT_STARTEDCurrent thread: Thread[Thread-62,5,main], id: 62
11-09 10:33:38.597  5615  5663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... adv data = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[5, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]Current thread: Thread[Thread-62,5,main], id: 62
11-09 10:33:38.597  5615  5663 D BluetoothAdapter: STATE_ON
11-09 10:33:38.599  5844  5884 D BtGatt.GattService: registerClient() - UUID=9cb5f80b-7b2c-4fad-9156-91b1ac1126cf
,11-09 10:33:38.600  5844  5860 D BtGatt.GattService: onClientRegistered() - UUID=9cb5f80b-7b2c-4fad-9156-91b1ac1126cf, clientIf=5
11-09 10:33:38.601  5615  5659 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
,11-09 10:33:38.602  5844  5862 D BtGatt.AdvertiseManager: message : 0
,11-09 10:33:38.604  5844  5862 D BtGatt.AdvertiseManager: starting multi advertising
,11-09 10:33:38.613  5844  5860 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,11-09 10:33:38.618  5844  5860 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,11-09 10:33:38.619  5615  5663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment Current thread: Thread[Thread-62,5,main], id: 62
,11-09 10:33:38.619  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTINGCurrent thread: Thread[Thread-62,5,main], id: 62
11-09 10:33:38.619  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
11-09 10:33:38.619  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged default (no call to listener). Current thread: Thread[Thread-62,5,main], id: 62
11-09 10:33:38.619  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finishedCurrent thread: Thread[Thread-62,5,main], id: 62
11-09 10:33:38.620  5615  5663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[Thread-62,5,main], id: 62
11-09 10:33:38.620  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[Thread-62,5,main], id: 62
11-09 10:33:38.620  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser started = trueCurrent thread: Thread[Thread-62,5,main], id: 62
11-09 10:33:38.620  5615  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,11-09 10:33:38.621  5615  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-09 10:33:38.621  5615  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
,11-09 10:33:38.622  5615  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
,11-09 10:33:38.623  5615  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-09 10:33:38.623  5615  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-09 10:33:38.623  5615  5615 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
11-09 10:33:38.623  5615  5615 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess : Current thread: Thread[main,5,main], id: 1
11-09 10:33:38.623  5615  5615 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNINGCurrent thread: Thread[main,5,main], id: 1
11-09 10:33:38.623  5615  5615 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
11-09 10:33:38.623  5615  5615 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged true. Current thread: Thread[main,5,main], id: 1
11-09 10:33:38.623  5615  5615 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-09 10:33:38.623  5615  5615 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-09 10:33:38.623  5615  5615 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [ADVERTISING]
,11-09 10:33:38.623  5615  5615 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-09 10:33:38.623  5615  5615 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-09 10:33:38.623  5615  5615 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]Current thread: Thread[main,5,main], id: 1
11-09 10:33:38.624  5615  5615 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
11-09 10:33:38.624  5615  5615 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
,11-09 10:33:38.626  5615  5615 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-09 10:33:38.626  5615  5615 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
11-09 10:33:38.626  5615  5615 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-09 10:33:38.626  5615  5615 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
,11-09 10:33:38.626  5615  5615 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-09 10:33:38.627  5615  5615 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finishedCurrent thread: Thread[main,5,main], id: 1
11-09 10:33:38.627  5615  5615 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,11-09 10:33:39.128  5615  5615 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
,11-09 10:33:39.128  5615  5615 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
11-09 10:33:39.128  5615  5615 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,11-09 10:33:41.375  5912  5912 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-09 10:33:41.382  5912  5912 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-09 10:33:41.386  5912  5912 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-09 10:33:41.391  5912  5912 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-09 10:33:41.433   931  2957 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,11-09 10:33:41.434   931  2957 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3
11-09 10:33:41.434   931  2957 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-09 10:33:41.446   931  2957 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=0
,11-09 10:33:41.481   931  2957 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=0
,11-09 10:33:41.487  5912  5912 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,11-09 10:33:41.908  5912  5912 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,11-09 10:33:41.940  5912  5912 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,11-09 10:33:41.940  5912  5912 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,11-09 10:33:41.950   931  2957 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,11-09 10:33:41.951   931  2957 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
11-09 10:33:41.951   931  2959 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,11-09 10:33:41.966   931  2957 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-09 10:33:41.977   511   925 D CommandListener: Setting iface cfg
,11-09 10:33:41.982   931  2957 D WifiStateMachine: Start Dhcp Watchdog 3
,11-09 10:33:41.990   931  5919 D DhcpClient: Receive thread started
,11-09 10:33:41.992   931  2959 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-09 10:33:41.992   931  2957 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
11-09 10:33:41.992   931  2959 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 102] to 60
,11-09 10:33:42.072   931  2957 E native  : do suspend false
,11-09 10:33:42.086   931  5918 D DhcpClient: Broadcasting DHCPDISCOVER
,11-09 10:33:42.103   931  5919 D DhcpClient: Received packet: 60:83:34:25:d7:70 OFFER, ip /192.168.1.105, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172792, domain null
,11-09 10:33:42.104   931  5918 D DhcpClient: Got pending lease: IP address 192.168.1.105/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172792 seconds
,11-09 10:33:42.106   931  5918 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.105 serverid=192.168.1.1
,11-09 10:33:42.119   931  5919 D DhcpClient: Received packet: 60:83:34:25:d7:70 ACK: your new IP /192.168.1.105, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,11-09 10:33:42.119   931  5918 D DhcpClient: Confirmed lease: IP address 192.168.1.105/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,11-09 10:33:42.123   511   925 D CommandListener: Setting iface cfg
,11-09 10:33:42.125  5615  5663 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
11-09 10:33:42.125  5615  5663 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,11-09 10:33:42.125  5615  5663 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
11-09 10:33:42.125  5615  5663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
11-09 10:33:42.126  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
,11-09 10:33:42.126  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
11-09 10:33:42.126  5615  5663 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
11-09 10:33:42.127  5615  5663 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
,11-09 10:33:42.127  5615  5914 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
,11-09 10:33:42.127  5615  5914 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
11-09 10:33:42.127  5615  5663 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
11-09 10:33:42.127  5615  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-09 10:33:42.127  5615  5914 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
,11-09 10:33:42.127  5615  5615 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
11-09 10:33:42.127  5615  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
11-09 10:33:42.127  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-09 10:33:42.128  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-62,5,main], id: 62
11-09 10:33:42.128  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-62,5,main], id: 62
11-09 10:33:42.129   931  2957 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
11-09 10:33:42.131  5615  5663 D BluetoothAdapter: STATE_ON
11-09 10:33:42.131  5615  5663 D BluetoothLeScanner: could not find callback wrapper
11-09 10:33:42.131  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-09 10:33:42.132  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-62,5,main], id: 62
11-09 10:33:42.132  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-62,5,main], id: 62
11-09 10:33:42.132  5615  5663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
11-09 10:33:42.132  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-62,5,main], id: 62
11-09 10:33:42.135  5844  5862 D BtGatt.AdvertiseManager: message : 1
11-09 10:33:42.136   931  5918 D DhcpClient: Scheduling renewal in 86399s
11-09 10:33:42.137  5844  5862 D BtGatt.AdvertiseManager: stop advertise for client 5
,11-09 10:33:42.145   931  2957 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,11-09 10:33:42.146   931  2957 D WifiConfigStore: No blacklist allowed without epno enabled
11-09 10:33:42.147   931  2959 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
11-09 10:33:42.148   931  2957 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
11-09 10:33:42.152   931  2959 D ConnectivityService: Adding iface wlan0 to network 102
,11-09 10:33:42.153  5844  5860 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
11-09 10:33:42.154  5844  5860 D BtGatt.GattService: Client app is not null!
11-09 10:33:42.157  5844  5884 D BtGatt.GattService: unregisterClient() - clientIf=5
11-09 10:33:42.158  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-09 10:33:42.158  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTEDCurrent thread: Thread[Thread-62,5,main], id: 62
11-09 10:33:42.158  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
,11-09 10:33:42.158  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged false. Current thread: Thread[Thread-62,5,main], id: 62
11-09 10:33:42.158  5615  5663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: falseCurrent thread: Thread[Thread-62,5,main], id: 62
11-09 10:33:42.159  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[Thread-62,5,main], id: 62
11-09 10:33:42.159  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-09 10:33:42.159  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [ADVERTISING]
,11-09 10:33:42.159  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[Thread-62,5,main], id: 62
11-09 10:33:42.159  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]Current thread: Thread[Thread-62,5,main], id: 62
11-09 10:33:42.159  5615  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
11-09 10:33:42.159  5615  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-09 10:33:42.161  5615  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-09 10:33:42.161  5615  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,11-09 10:33:42.162  5615  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-09 10:33:42.162  5615  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-09 10:33:42.162  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[Thread-62,5,main], id: 62
11-09 10:33:42.162  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finishedCurrent thread: Thread[Thread-62,5,main], id: 62
11-09 10:33:42.162  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-62,5,main], id: 62
,11-09 10:33:42.162  5615  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-09 10:33:42.163  5615  5663 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-09 10:33:42.164  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,11-09 10:33:42.164  5615  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
,11-09 10:33:42.167  5615  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-09 10:33:42.167  5615  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-09 10:33:42.167  5615  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-09 10:33:42.168  5615  5615 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,11-09 10:33:42.168  5615  5615 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
11-09 10:33:42.169  5615  5615 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
11-09 10:33:42.169  5615  5615 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-09 10:33:42.169  5615  5615 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-09 10:33:42.169  5615  5615 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,11-09 10:33:42.170  5615  5615 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-09 10:33:42.172  5615  5663 I io.jxcore.node.StartStopOperationHandlerTest: Starting test: testCheckCurrentOperationStatus
11-09 10:33:42.173  5615  5663 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-09 10:33:42.174  5615  5663 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-09 10:33:42.174  5615  5663 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
11-09 10:33:42.174  5615  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,11-09 10:33:42.174  5615  5663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-09 10:33:42.174  5615  5663 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
11-09 10:33:42.179  5615  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-09 10:33:42.179  5615  5663 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-09 10:33:42.179  5615  5663 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,11-09 10:33:42.183  5615  5663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,11-09 10:33:42.184  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-09 10:33:42.184  5615  5663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-09 10:33:42.188   931  2959 E ConnectivityService: Unexpected mtu value: 0, wlan0
11-09 10:33:42.188   931  2959 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
11-09 10:33:42.189  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-62,5,main], id: 62
11-09 10:33:42.189  5615  5663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
11-09 10:33:42.189  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,11-09 10:33:42.189  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
11-09 10:33:42.189  5615  5663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
11-09 10:33:42.190   931  2959 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
11-09 10:33:42.190  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-62,5,main], id: 62
,11-09 10:33:42.190  5615  5663 D BluetoothAdapter: STATE_ON
11-09 10:33:42.191   931  2959 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
11-09 10:33:42.193   931  2959 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
11-09 10:33:42.193  5844  5871 D BtGatt.GattService: registerClient() - UUID=49221ba0-b368-46f6-95ed-5028ad2af834
11-09 10:33:42.194  5844  5860 D BtGatt.GattService: onClientRegistered() - UUID=49221ba0-b368-46f6-95ed-5028ad2af834, clientIf=5
11-09 10:33:42.194  5615  5625 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,11-09 10:33:42.195  5844  5884 D BtGatt.GattService: start scan with filters
,11-09 10:33:42.199  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
,11-09 10:33:42.199  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-62,5,main], id: 62
11-09 10:33:42.199  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
11-09 10:33:42.199  5844  5863 D BtGatt.ScanManager: handling starting scan
11-09 10:33:42.199  5615  5663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[Thread-62,5,main], id: 62
11-09 10:33:42.200  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[Thread-62,5,main], id: 62
11-09 10:33:42.200  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
,11-09 10:33:42.200  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-09 10:33:42.200  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[Thread-62,5,main], id: 62
11-09 10:33:42.200  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[Thread-62,5,main], id: 62
11-09 10:33:42.200  5615  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
11-09 10:33:42.200  5615  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-09 10:33:42.201  5844  5863 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a44b98d
11-09 10:33:42.201   931  2959 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
11-09 10:33:42.203  5615  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-09 10:33:42.203  5615  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
11-09 10:33:42.203  5615  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-09 10:33:42.203  5615  5615 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,11-09 10:33:42.204  5615  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-09 10:33:42.204  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[Thread-62,5,main], id: 62
11-09 10:33:42.204  5615  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-09 10:33:42.205  5615  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-09 10:33:42.205  5615  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-09 10:33:42.206   931  2959 D ConnectivityService: scheduleUnvalidatedPrompt 102
11-09 10:33:42.206   931  2959 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 102]
11-09 10:33:42.206   931  2959 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 102]
11-09 10:33:42.206   931  2957 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
11-09 10:33:42.206   931  2959 D ConnectivityService:    accepting network in place of null
11-09 10:33:42.206   931  2957 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
11-09 10:33:42.206   931  2959 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d770/64,192.168.1.105/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -47]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
11-09 10:33:42.207  5844  5860 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
11-09 10:33:42.207  5844  5860 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-09 10:33:42.208  5844  5863 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
11-09 10:33:42.208  5615  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-09 10:33:42.209  5615  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-09 10:33:42.209  5615  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
,11-09 10:33:42.213   931  5917 D NetlinkSocketObserver: NeighborEvent{elapsedMs=117147, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,11-09 10:33:42.216  5844  5860 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
,11-09 10:33:42.216  5844  5860 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-09 10:33:42.217  5844  5863 D BtGatt.ScanManager: Starting BLE batch scan
11-09 10:33:42.217  5844  5863 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,11-09 10:33:42.227  5844  5860 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
11-09 10:33:42.227  5844  5860 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-09 10:33:42.228   511   925 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-09 10:33:42.232  5844  5860 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,11-09 10:33:42.232  5844  5860 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-09 10:33:42.247   511   925 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-09 10:33:42.250   931  2959 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
11-09 10:33:42.250   931  2959 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
11-09 10:33:42.250  3732  3848 W QCNEJ   : |CORE| network available: 102
,11-09 10:33:42.251   931  2959 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
11-09 10:33:42.251   931  2959 D ConnectivityService: handlePromptUnvalidated 101
11-09 10:33:42.252   931   948 D Tethering: MasterInitialState.processMessage what=3
11-09 10:33:42.254  3732  3848 W QCNEJ   : |CORE| onAvailable: bind the process to WIFI
,11-09 10:33:42.256  3732  3848 W QCNEJ   : |CORE| newLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d770/64,192.168.1.105/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}
11-09 10:33:42.256  3732  3848 W QCNEJ   : |CORE| curLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d770/64,192.168.1.105/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,11-09 10:33:42.259  5615  5615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-09 10:33:42.259  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-09 10:33:42.259  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-09 10:33:42.259  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-09 10:33:42.259  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-09 10:33:42.259  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-09 10:33:42.259  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-09 10:33:42.259  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,11-09 10:33:42.261  5615  5615 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,11-09 10:33:42.263  3963  3963 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
,11-09 10:33:42.265  4045  4045 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
11-09 10:33:42.266  5615  5615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-09 10:33:42.266  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-09 10:33:42.266  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-09 10:33:42.266  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-09 10:33:42.266  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-09 10:33:42.266  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-09 10:33:42.266  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-09 10:33:42.266  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
11-09 10:33:42.268  4045  4045 D SystemUpdateService: onCreate
11-09 10:33:42.268  5615  5615 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,11-09 10:33:42.271  4045  4045 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,11-09 10:33:42.272  5615  5615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-09 10:33:42.272  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-09 10:33:42.272  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-09 10:33:42.272  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-09 10:33:42.272  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-09 10:33:42.272  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-09 10:33:42.272  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-09 10:33:42.272  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,11-09 10:33:42.275  5615  5615 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,11-09 10:33:42.281  4045  4045 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,11-09 10:33:42.286  4045  4254 I iu.UploadsManager: num queued entries: 0
,11-09 10:33:42.286  4045  4254 I iu.UploadsManager: num updated entries: 0
,11-09 10:33:42.287  4045  4254 I iu.SyncManager: NEXT; no task
,11-09 10:33:42.291  4045  4045 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,11-09 10:33:42.292  4045  4045 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,11-09 10:33:42.294  5418  5418 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,11-09 10:33:42.297  5418  5418 D SprintDMHelper: simOperator: 
11-09 10:33:42.297  5418  5418 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,11-09 10:33:42.305  4045  5929 I SystemUpdateService: active receiver: enabled
,11-09 10:33:42.324  4045  5929 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,11-09 10:33:42.326  4045  5929 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,11-09 10:33:42.326  4045  5929 I SystemUpdateService: now status is 0 (complete)
11-09 10:33:42.326  4045  5929 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
11-09 10:33:42.326  4045  5929 I SystemUpdateService: file has been verified
11-09 10:33:42.326  4045  5929 I SystemUpdateService: OTA package size = 21989297
,11-09 10:33:42.334  4045  5929 I SystemUpdateService: showing system update notification
,11-09 10:33:42.340   931   931 V NotificationService: pkg=com.google.android.gms canInterrupt=false intercept=true
,11-09 10:33:42.341  4045  4045 D SystemUpdateService: onDestroy
,11-09 10:33:42.383   931  5916 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.214.238,2a00:1450:400d:803::200e
,11-09 10:33:42.429   931  5916 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 09 Nov 2016 09:33:42 GMT], X-Android-Received-Millis=[1478684022428], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1478684022408]}
,11-09 10:33:42.430   931  2959 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,11-09 10:33:42.430   931  2959 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] validation  passed
11-09 10:33:42.430   931  2959 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-09 10:33:42.432   931  2959 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,11-09 10:33:42.704  5615  5615 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,11-09 10:33:42.705  5615  5615 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
11-09 10:33:42.705  5615  5615 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,11-09 10:33:42.736  5844  5844 D BtGatt.ScanManager: awakened up at time 117670
,11-09 10:33:42.738  5844  5863 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-09 10:33:42.764  5844  5860 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
11-09 10:33:42.764  5844  5860 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-09 10:33:42.765  5844  5860 D BtGatt.GattService: current time is 117699625675
11-09 10:33:42.765  5844  5860 D BtGatt.GattService: Batch record : [71, -122, -77, 84, 69, -12, 1, -128, -89, 9, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
11-09 10:33:42.767  5844  5860 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
,11-09 10:33:42.771  5615  5615 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: onBatchScanResults: Current thread: Thread[main,5,main], id: 1
11-09 10:33:42.772  5615  5615 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: 
11-09 10:33:42.772  5615  5615 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: ScanResult{mDevice=F4:45:54:B3:86:47, mScanRecord=ScanRecord [mAdvertiseFlags=6, mServiceUuids=null, mManufacturerSpecificData={76=[2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74]}, mServiceData={0000180a-0000-1000-8000-00805f9b34fb=[71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]}, mTxPowerLevel=-2147483648, mDeviceName=estimote], mRssi=-89, mTimestampNanos=117250252914}
,11-09 10:33:42.847   540   540 I ServiceManager: Waiting for service AtCmdFwd...
,11-09 10:33:43.251   931  2959 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 101] cleared because we found a replacement network
,11-09 10:33:43.848   540   540 I ServiceManager: Waiting for service AtCmdFwd...
,11-09 10:33:44.850   540   540 I ServiceManager: Waiting for service AtCmdFwd...
,11-09 10:33:45.007   931  2959 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-09 10:33:45.211  5615  5663 I io.jxcore.node.StartStopOperationHandlerTest: Starting test: testExecuteStartOperation
11-09 10:33:45.211  5615  5663 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 6
11-09 10:33:45.211  5615  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 5 -> 6
,11-09 10:33:45.212  5615  5663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
11-09 10:33:45.212  5615  5663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Manufacturer ID: 7413
11-09 10:33:45.212  5615  5663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad length and type: 533
11-09 10:33:45.212  5615  5663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad extra information: 6
11-09 10:33:45.212  5615  5663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
11-09 10:33:45.212  5615  5663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 2
11-09 10:33:45.212  5615  5663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 3
11-09 10:33:45.212  5615  5663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 2
11-09 10:33:45.212  5615  5663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
11-09 10:33:45.213  5615  5663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-09 10:33:45.213  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-09 10:33:45.216  5615  5663 D BluetoothAdapter: STATE_ON
,11-09 10:33:45.218  5844  5855 D BtGatt.GattService: stopScan() - queue size =1
,11-09 10:33:45.224  5844  5881 D BtGatt.GattService: unregisterClient() - clientIf=5
,11-09 10:33:45.225  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-09 10:33:45.226  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-62,5,main], id: 62
,11-09 10:33:45.226  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
11-09 10:33:45.227  5615  5663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-09 10:33:45.227  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-62,5,main], id: 62
11-09 10:33:45.228  5615  5663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,11-09 10:33:45.228  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
11-09 10:33:45.229  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
11-09 10:33:45.229  5615  5663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
11-09 10:33:45.230  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-62,5,main], id: 62
11-09 10:33:45.230  5844  5844 D BtGatt.ScanManager: awakened up at time 120165
,11-09 10:33:45.231  5615  5663 D BluetoothAdapter: STATE_ON
11-09 10:33:45.234  5844  5860 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
11-09 10:33:45.234  5844  5860 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-09 10:33:45.235  5844  5863 D BtGatt.ScanManager: stopping BLe Batch
11-09 10:33:45.235  5844  5855 D BtGatt.GattService: registerClient() - UUID=9fb4f3a2-0a6f-42cb-9395-f29e62ff12b3
11-09 10:33:45.236  5844  5860 D BtGatt.GattService: onClientRegistered() - UUID=9fb4f3a2-0a6f-42cb-9395-f29e62ff12b3, clientIf=5
,11-09 10:33:45.236  5615  5625 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
11-09 10:33:45.237  5844  5881 D BtGatt.GattService: start scan with filters
,11-09 10:33:45.240  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
11-09 10:33:45.240  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-62,5,main], id: 62
11-09 10:33:45.241  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,11-09 10:33:45.241  5615  5663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[Thread-62,5,main], id: 62
11-09 10:33:45.241  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[Thread-62,5,main], id: 62
11-09 10:33:45.241  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
11-09 10:33:45.241  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
11-09 10:33:45.241  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[Thread-62,5,main], id: 62
11-09 10:33:45.243  5844  5860 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
11-09 10:33:45.243  5844  5860 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-09 10:33:45.243  5844  5863 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
11-09 10:33:45.255  5844  5860 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=3
11-09 10:33:45.255  5844  5860 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-09 10:33:45.241  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[Thread-62,5,main], id: 62
11-09 10:33:45.256  5844  5860 D BtGatt.GattService: current time is 120190948311
11-09 10:33:45.256  5615  5663 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
11-09 10:33:45.256  5615  5663 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
11-09 10:33:45.256  5615  5663 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
11-09 10:33:45.256  5844  5860 D BtGatt.GattService: Batch record : [35, 97, 126, -92, 22, -56, 1, -128, -92, 45, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 0, 37, -47, 14, -113, 116, -46, 1, -128, -87, 44, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, -46, -4, -117, 6, 105, -37, 1, -128, -77, 34, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
11-09 10:33:45.256  5615  5663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-09 10:33:45.256  5844  5860 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74]
11-09 10:33:45.256  5844  5860 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
11-09 10:33:45.257  5844  5860 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
11-09 10:33:45.257  5615  5663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
11-09 10:33:45.2,57  5615  5663 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
11-09 10:33:45.257   931  2957 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 8, 11 -> obsolete
11-09 10:33:45.257  5615  5663 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
11-09 10:33:45.257  5615  5663 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
11-09 10:33:45.257  5615  5663 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
11-09 10:33:45.258  5615  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: true
11-09 10:33:45.258  5844  5863 D BtGatt.ScanManager: handling starting scan
11-09 10:33:45.258  5615  5615 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
11-09 10:33:45.258  5615  5937 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
11-09 10:33:45.259  5615  5937 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-09 10:33:45.259  5615  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-09 10:33:45.260  5615  5663 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,11-09 10:33:45.257  5871  5871 W Binder_3: type=1400 audit(0.0:125): avc: denied { ioctl } for path="socket:[33993]" dev="sockfs" ino=33993 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-09 10:33:45.257  5871  5871 W Binder_3: type=1400 audit(0.0:126): avc: denied { ioctl } for path="socket:[33993]" dev="sockfs" ino=33993 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,11-09 10:33:45.262  5615  5937 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,11-09 10:33:45.264  5844  5860 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
11-09 10:33:45.264  5844  5860 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-09 10:33:45.265  5844  5863 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
11-09 10:33:45.267  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser : Current thread: Thread[Thread-62,5,main], id: 62
11-09 10:33:45.267  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Current thread: Thread[Thread-62,5,main], id: 62
,11-09 10:33:45.267  5615  5663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
11-09 10:33:45.267  5615  5663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-09 10:33:45.267  5615  5663 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 06 60 83 34 25 D7 D4
11-09 10:33:45.267  5615  5663 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[6, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-09 10:33:45.267  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: Current thread: Thread[Thread-62,5,main], id: 62
11-09 10:33:45.267  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData finished: Current thread: Thread[Thread-62,5,main], id: 62
11-09 10:33:45.267  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = NOT_STARTEDCurrent thread: Thread[Thread-62,5,main], id: 62
11-09 10:33:45.268  5615  5663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... adv data = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[6, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]Current thread: Thread[Thread-62,5,main], id: 62
11-09 10:33:45.269  5615  5663 D BluetoothAdapter: STATE_ON
,11-09 10:33:45.270  5844  5860 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
11-09 10:33:45.270  5844  5860 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-09 10:33:45.271  5844  5881 D BtGatt.GattService: registerClient() - UUID=cd0be9bf-d5ee-47c6-a76b-412853460ca1
11-09 10:33:45.271  5844  5860 D BtGatt.GattService: onClientRegistered() - UUID=cd0be9bf-d5ee-47c6-a76b-412853460ca1, clientIf=6
11-09 10:33:45.271  5615  5626 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
11-09 10:33:45.272  5844  5863 D BtGatt.ScanManager: Starting BLE batch scan
11-09 10:33:45.272  5844  5863 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,11-09 10:33:45.272  5844  5862 D BtGatt.AdvertiseManager: message : 0
11-09 10:33:45.274  5844  5862 D BtGatt.AdvertiseManager: starting multi advertising
,11-09 10:33:45.281  5844  5860 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,11-09 10:33:45.281  5844  5860 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-09 10:33:45.288  5844  5860 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0
,11-09 10:33:45.292  5844  5860 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,11-09 10:33:45.292  5844  5860 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-09 10:33:45.296  5844  5860 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0
,11-09 10:33:45.297  5615  5663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment Current thread: Thread[Thread-62,5,main], id: 62
11-09 10:33:45.297  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTINGCurrent thread: Thread[Thread-62,5,main], id: 62
11-09 10:33:45.297  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,11-09 10:33:45.297  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged default (no call to listener). Current thread: Thread[Thread-62,5,main], id: 62
11-09 10:33:45.297  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finishedCurrent thread: Thread[Thread-62,5,main], id: 62
11-09 10:33:45.297  5615  5663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[Thread-62,5,main], id: 62
11-09 10:33:45.297  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[Thread-62,5,main], id: 62
11-09 10:33:45.297  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser started = trueCurrent thread: Thread[Thread-62,5,main], id: 62
11-09 10:33:45.297  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser: advertiser is started. Current thread: Thread[Thread-62,5,main], id: 62
11-09 10:33:45.297  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-62,5,main], id: 62
11-09 10:33:45.297  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-62,5,main], id: 62
11-09 10:33:45.298  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Already running
11-09 10:33:45.298  5615  5663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser: adv = true, disc = true
11-09 10:33:45.298  5615  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,11-09 10:33:45.299  5615  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-09 10:33:45.299  5615  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
,11-09 10:33:45.301  5615  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
,11-09 10:33:45.301  5615  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-09 10:33:45.301  5615  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-09 10:33:45.302  5615  5615 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
,11-09 10:33:45.302  5615  5615 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess : Current thread: Thread[main,5,main], id: 1
11-09 10:33:45.302  5615  5615 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNINGCurrent thread: Thread[main,5,main], id: 1
11-09 10:33:45.302  5615  5615 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
11-09 10:33:45.302  5615  5615 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged true. Current thread: Thread[main,5,main], id: 1
11-09 10:33:45.302  5615  5615 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-09 10:33:45.302  5615  5615 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-09 10:33:45.302  5615  5615 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING, ADVERTISING]
11-09 10:33:45.302  5615  5615 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
11-09 10:33:45.302  5615  5615 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-09 10:33:45.303  5615  5615 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [SCANNING, ADVERTISING]Current thread: Thread[main,5,main], id: 1
,11-09 10:33:45.303  5615  5615 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [SCANNING, ADVERTISING]
11-09 10:33:45.303  5615  5615 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
,11-09 10:33:45.306  5615  5615 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
,11-09 10:33:45.306  5615  5615 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: true
11-09 10:33:45.306  5615  5615 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-09 10:33:45.306  5615  5615 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-09 10:33:45.306  5615  5615 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-09 10:33:45.306  5615  5615 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finishedCurrent thread: Thread[main,5,main], id: 1
11-09 10:33:45.306  5615  5615 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: true
,11-09 10:33:45.426   931  2957 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 7, 11 -> obsolete
,11-09 10:33:45.796  5844  5844 D BtGatt.ScanManager: awakened up at time 120730
,11-09 10:33:45.798  5844  5863 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-09 10:33:45.807  5615  5615 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: true
,11-09 10:33:45.807  5615  5615 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
11-09 10:33:45.808  5615  5615 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,11-09 10:33:45.819  5844  5860 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,11-09 10:33:45.820  5844  5860 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-09 10:33:45.820  5844  5860 D BtGatt.GattService: current time is 120754798682
,11-09 10:33:45.820  5844  5860 D BtGatt.GattService: Batch record : [-46, -4, -117, 6, 105, -37, 1, -128, -76, 5, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
11-09 10:33:45.820  5844  5860 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
,11-09 10:33:45.821  5615  5615 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: onBatchScanResults: Current thread: Thread[main,5,main], id: 1
11-09 10:33:45.821  5615  5615 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: 
,11-09 10:33:45.822  5615  5615 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: ScanResult{mDevice=DB:69:06:8B:FC:D2, mScanRecord=ScanRecord [mAdvertiseFlags=6, mServiceUuids=null, mManufacturerSpecificData={76=[2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74]}, mServiceData={0000180a-0000-1000-8000-00805f9b34fb=[-46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]}, mTxPowerLevel=-2147483648, mDeviceName=estimote], mRssi=-76, mTimestampNanos=120505096651}
,11-09 10:33:45.851   540   540 I ServiceManager: Waiting for service AtCmdFwd...
,11-09 10:33:46.851   540   540 I ServiceManager: Waiting for service AtCmdFwd...
,11-09 10:33:47.852   540   540 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,11-09 10:33:48.034   931  2959 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-09 10:33:48.305  5615  5663 I io.jxcore.node.StartStopOperationHandlerTest: Starting test: testConstructor
,11-09 10:33:48.306  5615  5663 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,11-09 10:33:48.306  5615  5663 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
,11-09 10:33:48.306  5615  5663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
11-09 10:33:48.306  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
,11-09 10:33:48.307  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
11-09 10:33:48.307  5615  5937 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
,11-09 10:33:48.307  5615  5663 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
,11-09 10:33:48.307  5615  5937 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
,11-09 10:33:48.307  5615  5663 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
11-09 10:33:48.307  5615  5937 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
,11-09 10:33:48.308  5615  5663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-09 10:33:48.308  5615  5615 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
11-09 10:33:48.308  5615  5663 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b167991 removed from the list
,11-09 10:33:48.308  5615  5615 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
11-09 10:33:48.308  5615  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-09 10:33:48.308  5615  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-09 10:33:48.308  5615  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
11-09 10:33:48.309  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-09 10:33:48.309  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-62,5,main], id: 62
11-09 10:33:48.309  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-62,5,main], id: 62
11-09 10:33:48.309  5615  5663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
11-09 10:33:48.308  5615  5615 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-09 10:33:48.311  5615  5663 D BluetoothAdapter: STATE_ON
11-09 10:33:48.313  5844  5881 D BtGatt.GattService: stopScan() - queue size =1
11-09 10:33:48.315  5844  5854 D BtGatt.GattService: unregisterClient() - clientIf=5
11-09 10:33:48.315  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-09 10:33:48.316  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-62,5,main], id: 62
11-09 10:33:48.316  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
11-09 10:33:48.316  5615  5663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[Thread-62,5,main], id: 62
,11-09 10:33:48.316  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[Thread-62,5,main], id: 62
11-09 10:33:48.316  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [ADVERTISING]
11-09 10:33:48.317  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING, ADVERTISING]
,11-09 10:33:48.317  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[Thread-62,5,main], id: 62
11-09 10:33:48.317  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING, ADVERTISING] to [ADVERTISING]Current thread: Thread[Thread-62,5,main], id: 62
11-09 10:33:48.317  5615  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING, ADVERTISING] -> [ADVERTISING]
,11-09 10:33:48.317  5615  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-09 10:33:48.320  5844  5844 D BtGatt.ScanManager: awakened up at time 123255
11-09 10:33:48.323  5615  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-09 10:33:48.324  5615  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
11-09 10:33:48.324  5615  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-09 10:33:48.324  5615  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-09 10:33:48.324  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[Thread-62,5,main], id: 62
11-09 10:33:48.324  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-62,5,main], id: 62
11-09 10:33:48.325  5615  5663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
11-09 10:33:48.325  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-62,5,main], id: 62
11-09 10:33:48.326  5844  5862 D BtGatt.AdvertiseManager: message : 1
11-09 10:33:48.327  5844  5862 D BtGatt.AdvertiseManager: stop advertise for client 6
11-09 10:33:48.327  5844  5860 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
11-09 10:33:48.328  5844  5860 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-09 10:33:48.328  5844  5863 D BtGatt.ScanManager: stopping BLe Batch
,11-09 10:33:48.340  5844  5860 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,11-09 10:33:48.341  5844  5860 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-09 10:33:48.341  5844  5863 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-09 10:33:48.345  5844  5860 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
11-09 10:33:48.345  5844  5860 D BtGatt.GattService: Client app is not null!
,11-09 10:33:48.346  5844  5871 D BtGatt.GattService: unregisterClient() - clientIf=6
,11-09 10:33:48.347  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-09 10:33:48.347  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTEDCurrent thread: Thread[Thread-62,5,main], id: 62
11-09 10:33:48.347  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
,11-09 10:33:48.348  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged false. Current thread: Thread[Thread-62,5,main], id: 62
11-09 10:33:48.348  5615  5663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: falseCurrent thread: Thread[Thread-62,5,main], id: 62
11-09 10:33:48.348  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[Thread-62,5,main], id: 62
11-09 10:33:48.348  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-09 10:33:48.348  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [ADVERTISING]
11-09 10:33:48.348  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[Thread-62,5,main], id: 62
,11-09 10:33:48.348  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]Current thread: Thread[Thread-62,5,main], id: 62
11-09 10:33:48.348  5615  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
11-09 10:33:48.348  5615  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-09 10:33:48.350  5615  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-09 10:33:48.350  5615  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-09 10:33:48.350  5615  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-09 10:33:48.350  5615  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-09 10:33:48.350  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[Thread-62,5,main], id: 62
11-09 10:33:48.350  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finishedCurrent thread: Thread[Thread-62,5,main], id: 62
11-09 10:33:48.350  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-62,5,main], id: 62
11-09 10:33:48.350  5615  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-09 10:33:48.350  5615  5663 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,11-09 10:33:48.351  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
11-09 10:33:48.351  5615  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-09 10:33:48.353  5615  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
,11-09 10:33:48.354  5615  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-09 10:33:48.354  5615  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-09 10:33:48.354  5615  5663 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8c220f6 removed from the list
11-09 10:33:48.354  5615  5615 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-09 10:33:48.354  5615  5663 D io.jxcore.node.ConnectivityMonitor: stop
,11-09 10:33:48.354  5615  5615 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-09 10:33:48.354  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-09 10:33:48.354  5615  5615 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
11-09 10:33:48.354  5615  5615 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-09 10:33:48.356  5615  5663 I io.jxcore.node.StartStopOperationTest: Starting test: testIsTargetState
11-09 10:33:48.356  5615  5663 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
11-09 10:33:48.357  5615  5663 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
,11-09 10:33:48.357  5615  5663 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
11-09 10:33:48.357  5615  5663 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-09 10:33:48.357  5615  5663 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
11-09 10:33:48.357  5615  5663 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
11-09 10:33:48.358  5615  5663 I io.jxcore.node.StartStopOperationTest: Starting test: testCreateStartOperation
11-09 10:33:48.359  5615  5663 I io.jxcore.node.StartStopOperationTest: Starting test: testGetShouldStartOrStopListeningToAdvertisementsOnly
,11-09 10:33:48.360  5615  5663 I io.jxcore.node.StartStopOperationTest: Starting test: testIsStartOperation
11-09 10:33:48.361  5615  5663 I io.jxcore.node.StartStopOperationTest: Starting test: testToString
11-09 10:33:48.362  5615  5663 I io.jxcore.node.StartStopOperationTest: Starting test: testCreateStopOperation
11-09 10:33:48.363  5615  5663 I io.jxcore.node.StartStopOperationTest: Starting test: testSetOperationExecutedTime
11-09 10:33:48.364  5615  5663 I io.jxcore.node.StartStopOperationTest: Starting test: testGetOperationExecutedTime
11-09 10:33:48.365  5615  5663 I io.jxcore.node.StartStopOperationTest: Starting test: testGetCallback
,11-09 10:33:48.379  5844  5860 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=5
,11-09 10:33:48.379  5844  5860 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-09 10:33:48.379  5844  5860 D BtGatt.GattService: current time is 123314456026
11-09 10:33:48.380  5844  5860 D BtGatt.GattService: Batch record : [37, -47, 14, -113, 116, -46, 1, -128, -87, 48, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 81, 34, 97, 112, -14, -5, 1, -128, -83, 45, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 71, -122, -77, 84, 69, -12, 1, -128, -83, 42, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 116, -43, -111, -91, -20, -29, 1, -128, -84, 31, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, -46, -4, -117, 6, 105, -37, 1, -128, -75, 18, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
11-09 10:33:48.380  5844  5860 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
11-09 10:33:48.380  5844  5860 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
11-09 10:33:48.380  5844  5860 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
,11-09 10:33:48.381  5844  5860 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
11-09 10:33:48.381  5844  5860 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
,11-09 10:33:48.855  5615  5615 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-09 10:33:50.208   931  2959 D ConnectivityService: handlePromptUnvalidated 102
,11-09 10:33:50.369  5615  5663 I StreamCopyingThreadTest: Starting test: testCopyDataAndCloseConnection
,11-09 10:33:50.516  5615  5939 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 156, name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
11-09 10:33:50.516  5615  5939 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-09 10:33:51.051   931  2959 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-09 10:33:51.312  5615  5939 W !!      : call onHalfStreamCopied
,11-09 10:33:51.312  5615  5939 I testCopyDataAndClose: closing input stream
,11-09 10:33:52.074  5615  5939 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 156, thread name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
11-09 10:33:52.074  5615  5939 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-09 10:33:52.074  5615  5939 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
11-09 10:33:52.074  5615  5939 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-09 10:33:52.074  5615  5939 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
11-09 10:33:52.074  5615  5939 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
11-09 10:33:52.074  5615  5939 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
11-09 10:33:52.074  5615  5939 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
11-09 10:33:52.074  5615  5939 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
11-09 10:33:52.074  5615  5939 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 156, name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
11-09 10:33:52.074  5615  5939 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 20971520 and the total number of bytes written 20971520
,11-09 10:33:52.853   540   540 I ServiceManager: Waiting for service AtCmdFwd...
,11-09 10:33:53.307   931  2957 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 10, 11 -> obsolete
,11-09 10:33:53.854   540   540 I ServiceManager: Waiting for service AtCmdFwd...
,11-09 10:33:54.215   931  2957 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 9, 11 -> obsolete
,11-09 10:33:54.855   540   540 I ServiceManager: Waiting for service AtCmdFwd...
,11-09 10:33:55.856   540   540 I ServiceManager: Waiting for service AtCmdFwd...
,11-09 10:33:56.578  5615  5663 I StreamCopyingThreadTest: Starting test: testRun
,11-09 10:33:56.581  5615  5940 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 159, name: My test thread name). Connection data: Peer properties: [null null].
11-09 10:33:56.581  5615  5940 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-09 10:33:56.858   540   540 I ServiceManager: Waiting for service AtCmdFwd...
,11-09 10:33:57.858   540   540 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,11-09 10:34:01.129  3661  3835 I Keyboard.Facilitator.LanguageModelFlusher: run()
,11-09 10:34:01.130  3661  3835 I Keyboard.Facilitator: flushDynamicLanguageModels()
,11-09 10:34:01.167  3589  3589 I ConfigService: onCreate
,11-09 10:34:01.589  5615  5941 E StreamCopyingThreadTest: StreamCopyingThread didn't close after 5s!
,11-09 10:34:01.592  5615  5663 I StreamCopyingThreadTest: Starting test: testCopyBigData
,11-09 10:34:01.705  5615  5943 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 162, name: testCopyBigData thread). Connection data: Peer properties: [null null].
11-09 10:34:01.705  5615  5943 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-09 10:34:03.375  5615  5943 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 162, thread name: testCopyBigData thread). Connection data: Peer properties: [null null].
11-09 10:34:03.375  5615  5943 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-09 10:34:03.376  5615  5943 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
11-09 10:34:03.376  5615  5943 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
11-09 10:34:03.376  5615  5943 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
11-09 10:34:03.376  5615  5943 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
11-09 10:34:03.376  5615  5943 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
,11-09 10:34:03.376  5615  5943 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
11-09 10:34:03.376  5615  5943 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
11-09 10:34:03.376  5615  5943 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 162, name: testCopyBigData thread). Connection data: Peer properties: [null null].
11-09 10:34:03.376  5615  5943 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 20971520 and the total number of bytes written 20971520
,11-09 10:34:06.206  3589  3589 I ConfigService: onDestroy
,11-09 10:34:07.733  5615  5663 I StreamCopyingThreadTest: Starting test: testRunNotify
,11-09 10:34:07.735  5615  5944 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 164, name: My test thread name). Connection data: Peer properties: [null null].
11-09 10:34:07.735  5615  5944 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-09 10:34:07.736  5615  5944 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 164, thread name: My test thread name). Connection data: Peer properties: [null null].
11-09 10:34:07.736  5615  5944 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
11-09 10:34:07.736  5615  5944 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
11-09 10:34:07.736  5615  5944 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
11-09 10:34:07.736  5615  5944 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
,11-09 10:34:07.736  5615  5944 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
11-09 10:34:07.736  5615  5944 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
11-09 10:34:07.736  5615  5944 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
,11-09 10:34:07.737  5615  5944 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
11-09 10:34:07.737  5615  5944 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 164, name: My test thread name). Connection data: Peer properties: [null null].
11-09 10:34:07.737  5615  5944 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 22
11-09 10:34:07.738  5615  5663 I StreamCopyingThreadTest: Starting test: testSetBufferSize
11-09 10:34:07.739  5615  5663 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,11-09 10:34:07.740  5615  5663 I StreamCopyingThreadTest: Starting test: testRunWithException
11-09 10:34:07.742  5615  5945 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 168, name: My test thread name). Connection data: Peer properties: [null null].
11-09 10:34:07.742  5615  5945 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
11-09 10:34:07.742  5615  5945 E io.jxcore.node.StreamCopyingThread: Failed to write to the output stream (thread ID: 168, thread name: My test thread name): Test exception.
,11-09 10:34:07.743  5615  5945 D io.jxcore.node.StreamCopyingThread: onStreamCopyError (ID: 168, name: My test thread name). Connection data: Peer properties: [null null].
11-09 10:34:07.743  5615  5945 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
,11-09 10:34:07.743  5615  5945 D io.jxcore.node.StreamCopyingThread: number of bytes read = 22
11-09 10:34:07.743  5615  5945 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 168, name: My test thread name). Connection data: Peer properties: [null null].
11-09 10:34:07.743  5615  5945 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
,11-09 10:34:07.746  5615  5663 E com.test.thalitest.ThaliTestRunner: testConnect(io.jxcore.node.ConnectionHelperTest)
,11-09 10:34:07.746  5615  5663 E com.test.thalitest.ThaliTestRunner: 
11-09 10:34:07.746  5615  5663 E com.test.thalitest.ThaliTestRunner: Expected: is "We already have an outgoing connection to peer with ID 00:11:22:33:44:55"
11-09 10:34:07.746  5615  5663 E com.test.thalitest.ThaliTestRunner:      but: was "Already connect(ing/ed)"
,11-09 10:34:07.747  5615  5663 E com.test.thalitest.ThaliTestRunner: java.lang.AssertionError: 
11-09 10:34:07.747  5615  5663 E com.test.thalitest.ThaliTestRunner: Expected: is "We already have an outgoing connection to peer with ID 00:11:22:33:44:55"
11-09 10:34:07.747  5615  5663 E com.test.thalitest.ThaliTestRunner:      but: was "Already connect(ing/ed)"
11-09 10:34:07.747  5615  5663 E com.test.thalitest.ThaliTestRunner: 	at org.hamcrest.MatcherAssert.assertThat(MatcherAssert.java:20)
11-09 10:34:07.747  5615  5663 E com.test.thalitest.ThaliTestRunner: 	at org.hamcrest.MatcherAssert.assertThat(MatcherAssert.java:8)
11-09 10:34:07.747  5615  5663 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.ConnectionHelperTest.testConnect(ConnectionHelperTest.java:551)
11-09 10:34:07.747  5615  5663 E com.test.thalitest.ThaliTestRunner: 	at java.lang.reflect.Method.invoke(Native Method)
11-09 10:34:07.747  5615  5663 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.model.FrameworkMethod$1.runReflectiveCall(FrameworkMethod.java:50)
11-09 10:34:07.747  5615  5663 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.model.ReflectiveCallable.run(ReflectiveCallable.java:12)
11-09 10:34:07.747  5615  5663 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.model.FrameworkMethod.invokeExplosively(FrameworkMethod.java:47)
11-09 10:34:07.747  5615  5663 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.InvokeMethod.evaluate(InvokeMethod.java:17)
11-09 10:34:07.747  5615  5663 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.RunBefores.evaluate(RunBefores.java:26)
11-09 10:34:07.747  5615  5663 E com.test.thalitest.ThaliTestRunner: 	at org.junit.rules.ExpectedException$ExpectedExceptionStatement.evaluate(ExpectedException.java:239)
11-09 10:34:07.747  5615  5663 E com.test.thalitest.ThaliTestRunner: 	at org.junit.rules.TestWatcher$1.evaluate(TestWatcher.java:55)
11-09 10:34:07.747  5615  5663 E com.test.thalitest.ThaliTestRunner: 	at org.junit.rules.RunRules.evaluate(RunRules.java:20)
11-09 10:34:07.747  5615  5663 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runLeaf(ParentRunner.java:325)
11-09 10:34:07.747  5615  5663 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.BlockJUnit4ClassRunner.runChild(BlockJUnit4ClassRunner.java:78)
11-09 10:34:07.747  5615  5663 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.BlockJUnit4ClassRunner.runChild(BlockJUnit4ClassRunner.java:57)
11-09 10:34:07.747  5615  5663 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$3.run(ParentRunner.java:290)
11-09 10:34:07.747  5615  5663 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$1.schedule(ParentRunner.java:71)
11-09 10:34:07.747  5615  5663 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runChildren(ParentRunner.java:288)
11-09 10:34:07.747  5615  5663 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.access$000(ParentRunner.java:58)
11-09 10:34:07.747  5615  5663 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$2.evaluate(ParentRunner.java:268)
11-09 10:34:07.747  5615  5663 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.RunBefores.evaluate(RunBefores.java:26)
11-09 10:34:07.747  5615  5663 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.RunAfters.evaluate(RunAfters.java:27)
11-09 10:34:07.747  5615  5663 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.run(ParentRunner.java:363)
11-09 10:34:07.747  5615  5663 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:128)
11-09 10:34:07.747  5615  5663 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:27)
11-09 10:34:07.747  5615  5663 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$3.run(ParentRunner.java:290)
11-09 10:34:07.747  5615,  5663 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$1.schedule(ParentRunner.java:71)
11-09 10:34:07.747  5615  5663 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runChildren(ParentRunner.java:288)
11-09 10:34:07.747  5615  5663 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.access$000(ParentRunner.java:58)
11-09 10:34:07.747  5615  5663 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$2.evaluate(ParentRunner.java:268)
11-09 10:34:07.747  5615  5663 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.run(ParentRunner.java:363)
11-09 10:34:07.747  5615  5663 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:128)
11-09 10:34:07.747  5615  5663 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:27)
11-09 10:34:07.747  5615  5663 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$3.run(ParentRunner.java:290)
11-09 10:34:07.747  5615  5663 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$1.schedule(ParentRunner.java:71)
11-09 10:34:07.747  5615  5663 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runChildren(ParentRunner.java:288)
11-09 10:34:07.747  5615  5663 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.access$000(ParentRunner.java:58)
11-09 10:34:07.747  5615  5663 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$2.evaluate(ParentRunner.java:268)
11-09 10:34:07.747  5615  5663 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.run(ParentRunner.java:363)
11-09 10:34:07.747  5615  5663 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.run(JUnitCore.java:137)
11-09 10:34:07.747  5615  5663 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.run(JUnitCore.java:115)
11-09 10:34:07.747  5615  5663 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.run(JUnitCore.java:105)
11-09 10:34:07.747  5615  5663 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.runClasses(JUnitCore.java:62)
11-09 10:34:07.747  5615  5663 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.runClasses(JUnitCore.java:49)
11-09 10:34:07.747  5615  5663 E com.test.thalitest.ThaliTestRunner: 	at com.test.thalitest.ThaliTestRunner.runTests(ThaliTestRunner.java:86)
11-09 10:34:07.747  5615  5663 E com.test.thalitest.ThaliTestRunner: 	at com.test.thalitest.RegisterExecuteUT$2.Receiver(RegisterExecuteUT.java:75)
11-09 10:34:07.747  5615  5663 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.jxcore.javaCall(jxcore.java:139)
11-09 10:34:07.747  5615  5663 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.jxcore.evalEngine(Native Method)
11-09 10:34:07.747  5615  5663 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.jxcore$4.run(jxcore.java:226)
11-09 10:34:07.747  5615  5663 E com.test.thalitest.ThaliTestRunner: 	at android.os.Handler.handleCallback(Handler.java:739)
11-09 10:34:07.747  5615  5663 E com.test.thalitest.ThaliTestRunner: 	at android.os.Handler.dispatchMessage(Handler.java:95)
11-09 10:34:07.747  5615  5663 E com.test.thalitest.ThaliTestRunner: 	at android.os.Looper.loop(Looper.java:148)
11-09 10:34:07.747  5615  5663 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.CoreThread.run(CoreRunnable.java:56)
11-09 10:34:07.747  5615  5663 E com.test.thalitest.ThaliTestRunner: testRun(io.jxcore.node.StreamCopyingThreadTest)
11-09 10:34:07.747  5615  5663 E com.test.thalitest.ThaliTestRunner: StreamCopyingThread should be closed
11-09 10:34:07.747  5615  5663 E com.test.thalitest.ThaliTestRunner: Expected: is <true>
11-09 10:34:07.747  5615  5663 E com.test.thalitest.ThaliTestRunner:      but: was <false>
11-09 10:34:07.748  5615  5663 E com.test.thalitest.ThaliTestRunner: java.lang.AssertionError: StreamCopyingThread should be closed
11-09 10:34:07.748  5615  5663 E com.test.t,halitest.ThaliTestRunner: Expected: is <true>
11-09 10:34:07.748  5615  5663 E com.test.thalitest.ThaliTestRunner:      but: was <false>
11-09 10:34:07.748  5615  5663 E com.test.thalitest.ThaliTestRunner: 	at org.hamcrest.MatcherAssert.assertThat(MatcherAssert.java:20)
11-09 10:34:07.748  5615  5663 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.StreamCopyingThreadTest.testRun(StreamCopyingThreadTest.java:152)
11-09 10:34:07.748  5615  5663 E com.test.thalitest.ThaliTestRunner: 	at java.lang.reflect.Method.invoke(Native Method)
11-09 10:34:07.748  5615  5663 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.model.FrameworkMethod$1.runReflectiveCall(FrameworkMethod.java:50)
11-09 10:34:07.748  5615  5663 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.model.ReflectiveCallable.run(ReflectiveCallable.java:12)
11-09 10:34:07.748  5615  5663 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.model.FrameworkMethod.invokeExplosively(FrameworkMethod.java:47)
11-09 10:34:07.748  5615  5663 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.InvokeMethod.evaluate(InvokeMethod.java:17)
11-09 10:34:07.748  5615  5663 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.RunBefores.evaluate(RunBefores.java:26)
11-09 10:34:07.748  5615  5663 E com.test.thalitest.ThaliTestRunner: 	at org.junit.rules.ExpectedException$ExpectedExceptionStatement.evaluate(ExpectedException.java:239)
11-09 10:34:07.748  5615  5663 E com.test.thalitest.ThaliTestRunner: 	at org.junit.rules.TestWatcher$1.evaluate(TestWatcher.java:55)
11-09 10:34:07.748  5615  5663 E com.test.thalitest.ThaliTestRunner: 	at org.junit.rules.RunRules.evaluate(RunRules.java:20)
11-09 10:34:07.748  5615  5663 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runLeaf(ParentRunner.java:325)
11-09 10:34:07.748  5615  5663 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.BlockJUnit4ClassRunner.runChild(BlockJUnit4ClassRunner.java:78)
11-09 10:34:07.748  5615  5663 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.BlockJUnit4ClassRunner.runChild(BlockJUnit4ClassRunner.java:57)
11-09 10:34:07.748  5615  5663 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$3.run(ParentRunner.java:290)
11-09 10:34:07.748  5615  5663 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$1.schedule(ParentRunner.java:71)
11-09 10:34:07.748  5615  5663 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runChildren(ParentRunner.java:288)
11-09 10:34:07.748  5615  5663 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.access$000(ParentRunner.java:58)
11-09 10:34:07.748  5615  5663 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$2.evaluate(ParentRunner.java:268)
11-09 10:34:07.748  5615  5663 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.run(ParentRunner.java:363)
11-09 10:34:07.748  5615  5663 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:128)
11-09 10:34:07.748  5615  5663 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:27)
11-09 10:34:07.748  5615  5663 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$3.run(ParentRunner.java:290)
11-09 10:34:07.748  5615  5663 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$1.schedule(ParentRunner.java:71)
11-09 10:34:07.748  5615  5663 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runChildren(ParentRunner.java:288)
11-09 10:34:07.748  5615  5663 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.access$000(ParentRunner.java:58)
11-09 10:34:07.748  5615  5663 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$2.evaluate(ParentRunner.java:268)
11-09 10:34:07.748  5615  5663 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.run(ParentRunner.java:363,)
11-09 10:34:07.748  5615  5663 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:128)
11-09 10:34:07.748  5615  5663 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:27)
11-09 10:34:07.748  5615  5663 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$3.run(ParentRunner.java:290)
11-09 10:34:07.748  5615  5663 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$1.schedule(ParentRunner.java:71)
11-09 10:34:07.748  5615  5663 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runChildren(ParentRunner.java:288)
11-09 10:34:07.748  5615  5663 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.access$000(ParentRunner.java:58)
11-09 10:34:07.748  5615  5663 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$2.evaluate(ParentRunner.java:268)
11-09 10:34:07.748  5615  5663 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.run(ParentRunner.java:363)
11-09 10:34:07.748  5615  5663 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.run(JUnitCore.java:137)
11-09 10:34:07.748  5615  5663 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.run(JUnitCore.java:115)
11-09 10:34:07.748  5615  5663 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.run(JUnitCore.java:105)
11-09 10:34:07.748  5615  5663 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.runClasses(JUnitCore.java:62)
11-09 10:34:07.748  5615  5663 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.runClasses(JUnitCore.java:49)
11-09 10:34:07.748  5615  5663 E com.test.thalitest.ThaliTestRunner: 	at com.test.thalitest.ThaliTestRunner.runTests(ThaliTestRunner.java:86)
11-09 10:34:07.748  5615  5663 E com.test.thalitest.ThaliTestRunner: 	at com.test.thalitest.RegisterExecuteUT$2.Receiver(RegisterExecuteUT.java:75)
11-09 10:34:07.748  5615  5663 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.jxcore.javaCall(jxcore.java:139)
11-09 10:34:07.748  5615  5663 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.jxcore.evalEngine(Native Method)
11-09 10:34:07.748  5615  5663 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.jxcore$4.run(jxcore.java:226)
11-09 10:34:07.748  5615  5663 E com.test.thalitest.ThaliTestRunner: 	at android.os.Handler.handleCallback(Handler.java:739)
11-09 10:34:07.748  5615  5663 E com.test.thalitest.ThaliTestRunner: 	at android.os.Handler.dispatchMessage(Handler.java:95)
11-09 10:34:07.748  5615  5663 E com.test.thalitest.ThaliTestRunner: 	at android.os.Looper.loop(Looper.java:148)
11-09 10:34:07.748  5615  5663 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.CoreThread.run(CoreRunnable.java:56)
11-09 10:34:07.750  5615  5663 I jxcore-log: 2016-11-09 09:34:07 - DEBUG UnitTest_app: 'Running unit tests'
11-09 10:34:07.750  5615  5663 I jxcore-log: 
11-09 10:34:07.750  5615  5663 I jxcore-log: *Native tests were executed*
11-09 10:34:07.750  5615  5663 I jxcore-log: 
11-09 10:34:07.750  5615  5663 I jxcore-log: Total number of executed tests:  82
11-09 10:34:07.750  5615  5663 I jxcore-log: 
11-09 10:34:07.750  5615  5663 I jxcore-log: Number of passed tests:  80
11-09 10:34:07.750  5615  5663 I jxcore-log: 
11-09 10:34:07.750  5615  5663 I jxcore-log: Number of failed tests:  2
11-09 10:34:07.750  5615  5663 I jxcore-log: 
11-09 10:34:07.750  5615  5663 I jxcore-log: Number of ignored tests:  0
11-09 10:34:07.750  5615  5663 I jxcore-log: 
11-09 10:34:07.750  5615  5663 I jxcore-log: Total duration:  45821
11-09 10:34:07.750  5615  5663 I jxcore-log: 
11-09 10:34:07.750  5615  5663 I jxcore-log: Failed to execute UT.
11-09 10:34:07.750  5615  5663 I jxcore-log: 
11-09 10:34:07.751  5615  5663 I jxcore-log: 2016-11-09 09:34:07 - DEBUG UnitTest_app: 'Failed to execute UT.'
11-09 10:34:07.751  5615  5663 I jxcore-log: 
11-09 10:34:07.752  5615  5663 I jxcore-log: 2016-11-09 09:34:07 - DEBUG UnitTest_ap,p: 'Unit Test app is loaded'
11-09 10:34:07.752  5615  5663 I jxcore-log: 
11-09 10:34:07.755  5615  5663 I jxcore-log: 2016-11-09 09:34:07 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
11-09 10:34:07.755  5615  5663 I jxcore-log: 
11-09 10:34:07.756  5615  5663 I jxcore-log: 2016-11-09 09:34:07 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-09 10:34:07.756  5615  5663 I jxcore-log: 
11-09 10:34:07.756  5615  5663 I jxcore-log: 2016-11-09 09:34:07 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
11-09 10:34:07.756  5615  5663 I jxcore-log: 
11-09 10:34:07.757  5615  5663 I jxcore-log: 2016-11-09 09:34:07 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-09 10:34:07.757  5615  5663 I jxcore-log: 
11-09 10:34:07.758  5615  5663 I jxcore-log: 2016-11-09 09:34:07 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
11-09 10:34:07.758  5615  5663 I jxcore-log: 
11-09 10:34:07.758  5615  5663 I jxcore-log: 2016-11-09 09:34:07 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-09 10:34:07.758  5615  5663 I jxcore-log: 
11-09 10:34:07.758  5615  5663 I jxcore-log: 2016-11-09 09:34:07 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
11-09 10:34:07.758  5615  5663 I jxcore-log: 
11-09 10:34:07.759  5615  5663 I jxcore-log: 2016-11-09 09:34:07 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
11-09 10:34:07.759  5615  5663 I jxcore-log: 
11-09 10:34:07.759  5615  5663 I jxcore-log: 2016-11-09 09:34:07 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
11-09 10:34:07.759  5615  5663 I jxcore-log: 
11-09 10:34:07.759  5615  5663 I jxcore-log: 2016-11-09 09:34:07 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-09 10:34:07.759  5615  5663 I jxcore-log: 
11-09 10:34:07.760  5615  5663 I jxcore-log: 2016-11-09 09:34:07 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
11-09 10:34:07.760  5615  5663 I jxcore-log: 
11-09 10:34:07.760  5615  5663 I jxcore-log: 2016-11-09 09:34:07 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-09 10:34:07.760  5615  5663 I jxcore-log: 
11-09 10:34:07.760  5615  5663 I jxcore-log: 2016-11-09 09:34:07 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
11-09 10:34:07.760  5615  5663 I jxcore-log: 
11-09 10:34:07.760  5615  5663 I jxcore-log: 2016-11-09 09:34:07 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-09 10:34:07.760  5615  5663 I jxcore-log: 
11-09 10:34:07.760  5615  5663 I jxcore-log: 2016-11-09 09:34:07 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
11-09 10:34:07.760  5615  5663 I jxcore-log: 
11-09 10:34:07.760  5615  5663 I jxcore-log: 2016-11-09 09:34:07 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-09 10:34:07.760  5615  5663 I jxcore-log: 
11-09 10:34:07.761  5615  5663 I jxcore-log: 2016-11-09 09:34:07 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
11-09 10:34:07.761  5615  5663 I jxcore-log: 
11-09 10:34:07.761  5615  5663 I jxcore-log: 2016-11-09 09:,34:07 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-09 10:34:07.761  5615  5663 I jxcore-log: 
11-09 10:34:07.761  5615  5663 I jxcore-log: 2016-11-09 09:34:07 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
11-09 10:34:07.761  5615  5663 I jxcore-log: 
11-09 10:34:07.761  5615  5663 I jxcore-log: 2016-11-09 09:34:07 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-09 10:34:07.761  5615  5663 I jxcore-log: 
11-09 10:34:07.762  5615  5663 I jxcore-log: 2016-11-09 09:34:07 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-09 10:34:07.762  5615  5663 I jxcore-log: 
11-09 10:34:07.762  5615  5663 I jxcore-log: 2016-11-09 09:34:07 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
11-09 10:34:07.762  5615  5663 I jxcore-log: 
11-09 10:34:07.762  5615  5663 I jxcore-log: 2016-11-09 09:34:07 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-09 10:34:07.762  5615  5663 I jxcore-log: 
11-09 10:34:07.762  5615  5663 I jxcore-log: 2016-11-09 09:34:07 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
11-09 10:34:07.762  5615  5663 I jxcore-log: 
11-09 10:34:07.762  5615  5663 I jxcore-log: 2016-11-09 09:34:07 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-09 10:34:07.762  5615  5663 I jxcore-log: 
11-09 10:34:07.763  5615  5663 I jxcore-log: 2016-11-09 09:34:07 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
11-09 10:34:07.763  5615  5663 I jxcore-log: 
11-09 10:34:07.763  5615  5663 I jxcore-log: 2016-11-09 09:34:07 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-09 10:34:07.763  5615  5663 I jxcore-log: 
11-09 10:34:07.763  5615  5663 I jxcore-log: 2016-11-09 09:34:07 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
11-09 10:34:07.763  5615  5663 I jxcore-log: 
11-09 10:34:07.763  5615  5663 I jxcore-log: 2016-11-09 09:34:07 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-09 10:34:07.763  5615  5663 I jxcore-log: 
11-09 10:34:07.765  5615  5663 I jxcore-log: 2016-11-09 09:34:07 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
11-09 10:34:07.765  5615  5663 I jxcore-log: 
11-09 10:34:07.765  5615  5663 I jxcore-log: 2016-11-09 09:34:07 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-09 10:34:07.765  5615  5663 I jxcore-log: 
,11-09 10:34:07.765  5615  5663 I jxcore-log: 2016-11-09 09:34:07 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
11-09 10:34:07.765  5615  5663 I jxcore-log: 
11-09 10:34:07.765  5615  5663 I jxcore-log: 2016-11-09 09:34:07 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-09 10:34:07.765  5615  5663 I jxcore-log: 
11-09 10:34:07.766  5615  5663 I jxcore-log: 2016-11-09 09:34:07 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
11-09 10:34:07.766  5615  5663 I jxcore-log: 
,11-09 10:34:07.766  5615  5663 I jxcore-log: 2016-11-09 09:34:07 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-09 10:34:07.766  5615  5663 I jxcore-log: 
11-09 10:34:07.766  5615  5663 I jxcore-log: 2016-11-09 09:34:07 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
11-09 10:34:07.766  5615  5663 I jxcore-log: 
11-09 10:34:07.766  5615  5663 I jxcore-log: 2016-11-09 09:34:07 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-09 10:34:07.766  5615  5663 I jxcore-log: 
,11-09 10:34:07.766  5615  5663 I jxcore-log: 2016-11-09 09:34:07 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
11-09 10:34:07.766  5615  5663 I jxcore-log: 
11-09 10:34:07.767  5615  5663 I jxcore-log: 2016-11-09 09:34:07 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-09 10:34:07.767  5615  5663 I jxcore-log: 
11-09 10:34:07.767  5615  5663 I jxcore-log: 2016-11-09 09:34:07 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
11-09 10:34:07.767  5615  5663 I jxcore-log: 
11-09 10:34:07.767  5615  5663 I jxcore-log: 2016-11-09 09:34:07 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-09 10:34:07.767  5615  5663 I jxcore-log: 
11-09 10:34:07.767  5615  5663 I jxcore-log: 2016-11-09 09:34:07 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
11-09 10:34:07.767  5615  5663 I jxcore-log: 
11-09 10:34:07.767  5615  5663 I jxcore-log: 2016-11-09 09:34:07 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-09 10:34:07.767  5615  5663 I jxcore-log: 
11-09 10:34:07.768  5615  5663 I jxcore-log: 2016-11-09 09:34:07 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
11-09 10:34:07.768  5615  5663 I jxcore-log: 
11-09 10:34:07.768  5615  5663 I jxcore-log: 2016-11-09 09:34:07 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-09 10:34:07.768  5615  5663 I jxcore-log: 
11-09 10:34:07.768  5615  5663 I jxcore-log: 2016-11-09 09:34:07 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
,11-09 10:34:07.768  5615  5663 I jxcore-log: 
11-09 10:34:07.768  5615  5663 I jxcore-log: 2016-11-09 09:34:07 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-09 10:34:07.768  5615  5663 I jxcore-log: 
11-09 10:34:07.768  5615  5663 I jxcore-log: 2016-11-09 09:34:07 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
11-09 10:34:07.768  5615  5663 I jxcore-log: 
11-09 10:34:07.768  5615  5663 I jxcore-log: 2016-11-09 09:34:07 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-09 10:34:07.768  5615  5663 I jxcore-log: 
11-09 10:34:07.769  5615  5663 I jxcore-log: 2016-11-09 09:34:07 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
11-09 10:34:07.769  5615  5663 I jxcore-log: 
11-09 10:34:07.769  5615  5663 I jxcore-log: 2016-11-09 09:34:07 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-09 10:34:07.769  5615  5663 I jxcore-log: 
,11-09 10:34:07.769  5615  5663 I jxcore-log: 2016-11-09 09:34:07 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
11-09 10:34:07.769  5615  5663 I jxcore-log: 
11-09 10:34:07.769  5615  5663 I jxcore-log: 2016-11-09 09:34:07 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-09 10:34:07.769  5615  5663 I jxcore-log: 
11-09 10:34:07.769  5615  5663 I jxcore-log: 2016-11-09 09:34:07 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
11-09 10:34:07.769  5615  5663 I jxcore-log: 
11-09 10:34:07.770  5615  5663 I jxcore-log: 2016-11-09 09:34:07 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,11-09 10:34:07.770  5615  5663 I jxcore-log: 
11-09 10:34:07.770  5615  5663 I jxcore-log: 2016-11-09 09:34:07 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
11-09 10:34:07.770  5615  5663 I jxcore-log: 
11-09 10:34:07.770  5615  5663 I jxcore-log: 2016-11-09 09:34:07 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-09 10:34:07.770  5615  5663 I jxcore-log: 
11-09 10:34:07.770  5615  5663 I jxcore-log: 2016-11-09 09:34:07 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
11-09 10:34:07.770  5615  5663 I jxcore-log: 
,11-09 10:34:07.770  5615  5663 I jxcore-log: 2016-11-09 09:34:07 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-09 10:34:07.770  5615  5663 I jxcore-log: 
11-09 10:34:07.771  5615  5663 I jxcore-log: 2016-11-09 09:34:07 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
11-09 10:34:07.771  5615  5663 I jxcore-log: 
11-09 10:34:07.771  5615  5663 I jxcore-log: 2016-11-09 09:34:07 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-09 10:34:07.771  5615  5663 I jxcore-log: 
,11-09 10:34:07.771  5615  5663 I jxcore-log: 2016-11-09 09:34:07 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
11-09 10:34:07.771  5615  5663 I jxcore-log: 
11-09 10:34:07.771  5615  5663 I jxcore-log: 2016-11-09 09:34:07 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-09 10:34:07.771  5615  5663 I jxcore-log: 
11-09 10:34:07.771  5615  5663 I jxcore-log: 2016-11-09 09:34:07 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
11-09 10:34:07.771  5615  5663 I jxcore-log: 
11-09 10:34:07.771  5615  5663 I jxcore-log: 2016-11-09 09:34:07 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-09 10:34:07.771  5615  5663 I jxcore-log: 
,11-09 10:34:07.772  5615  5663 I jxcore-log: 2016-11-09 09:34:07 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
11-09 10:34:07.772  5615  5663 I jxcore-log: 
11-09 10:34:07.772  5615  5663 I jxcore-log: 2016-11-09 09:34:07 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-09 10:34:07.772  5615  5663 I jxcore-log: 
11-09 10:34:07.772  5615  5663 I jxcore-log: 2016-11-09 09:34:07 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
11-09 10:34:07.772  5615  5663 I jxcore-log: 
,11-09 10:34:07.772  5615  5663 I jxcore-log: 2016-11-09 09:34:07 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-09 10:34:07.772  5615  5663 I jxcore-log: 
11-09 10:34:07.773  5615  5663 I jxcore-log: 2016-11-09 09:34:07 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
11-09 10:34:07.773  5615  5663 I jxcore-log: 
11-09 10:34:07.773  5615  5663 I jxcore-log: 2016-11-09 09:34:07 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-09 10:34:07.773  5615  5663 I jxcore-log: 
11-09 10:34:07.773  5615  5663 I jxcore-log: 2016-11-09 09:34:07 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
11-09 10:34:07.773  5615  5663 I jxcore-log: 
11-09 10:34:07.773  5615  5663 I jxcore-log: 2016-11-09 09:34:07 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,11-09 10:34:07.773  5615  5663 I jxcore-log: 
11-09 10:34:07.773  5615  5663 I jxcore-log: 2016-11-09 09:34:07 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
11-09 10:34:07.773  5615  5663 I jxcore-log: 
11-09 10:34:07.773  5615  5663 I jxcore-log: 2016-11-09 09:34:07 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
11-09 10:34:07.773  5615  5663 I jxcore-log: 
11-09 10:34:07.774  5615  5663 I jxcore-log: 2016-11-09 09:34:07 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-09 10:34:07.774  5615  5663 I jxcore-log: 
11-09 10:34:07.774  5615  5663 I jxcore-log: 2016-11-09 09:34:07 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
,11-09 10:34:07.774  5615  5663 I jxcore-log: 
11-09 10:34:07.774  5615  5663 I jxcore-log: 2016-11-09 09:34:07 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-09 10:34:07.774  5615  5663 I jxcore-log: 
11-09 10:34:07.774  5615  5663 I jxcore-log: 2016-11-09 09:34:07 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
11-09 10:34:07.774  5615  5663 I jxcore-log: 
11-09 10:34:07.774  5615  5663 I jxcore-log: 2016-11-09 09:34:07 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-09 10:34:07.774  5615  5663 I jxcore-log: 
11-09 10:34:07.775  5615  5663 I jxcore-log: 2016-11-09 09:34:07 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
11-09 10:34:07.775  5615  5663 I jxcore-log: 
,11-09 10:34:07.775  5615  5663 I jxcore-log: 2016-11-09 09:34:07 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
11-09 10:34:07.775  5615  5663 I jxcore-log: 
11-09 10:34:07.775  5615  5663 I jxcore-log: 2016-11-09 09:34:07 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-09 10:34:07.775  5615  5663 I jxcore-log: 
11-09 10:34:07.777  5615  5615 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
11-09 10:34:07.780  5615  5663 I jxcore-log: 2016-11-09 09:34:07 - DEBUG UnitTest_app: 'My device name is: Huawei-Nexus 6P'
11-09 10:34:07.780  5615  5663 I jxcore-log: 
,11-09 10:34:07.781  5615  5663 I jxcore-log: 2016-11-09 09:34:07 - WARN testUtils: 'myNameCallback not set!'
11-09 10:34:07.781  5615  5663 I jxcore-log: 
11-09 10:34:07.781  5615  5663 E JX-Cordova: jxcore.CallJSMethod :{"isFulfilled":false,"isRejected":false}
11-09 10:34:07.782  5615  5663 I jxcore-log: 2016-11-09 09:34:07 - DEBUG UnitTest_app: 'Running for NATIVE network type'
11-09 10:34:07.782  5615  5663 I jxcore-log: 
,11-09 10:34:07.859   540   540 I ServiceManager: Waiting for service AtCmdFwd...
,11-09 10:34:08.860   540   540 I ServiceManager: Waiting for service AtCmdFwd...
,11-09 10:34:09.800  5615  5663 I jxcore-log: 2016-11-09 09:34:09 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js'
11-09 10:34:09.800  5615  5663 I jxcore-log: 
,11-09 10:34:09.862   540   540 I ServiceManager: Waiting for service AtCmdFwd...
,11-09 10:34:10.127  5615  5663 I jxcore-log: 2016-11-09 09:34:10 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js'
11-09 10:34:10.127  5615  5663 I jxcore-log: 
,11-09 10:34:10.141  5615  5663 I jxcore-log: 2016-11-09 09:34:10 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManager.js'
11-09 10:34:10.141  5615  5663 I jxcore-log: 
,11-09 10:34:10.863   540   540 I ServiceManager: Waiting for service AtCmdFwd...
,11-09 10:34:11.208  5615  5663 I jxcore-log: 2016-11-09 09:34:11 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js'
11-09 10:34:11.208  5615  5663 I jxcore-log: 
,11-09 10:34:11.374  5615  5663 I jxcore-log: 2016-11-09 09:34:11 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js'
11-09 10:34:11.374  5615  5663 I jxcore-log: 
,11-09 10:34:11.379  5615  5663 I jxcore-log: 2016-11-09 09:34:11 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testNativeMethod.js'
11-09 10:34:11.379  5615  5663 I jxcore-log: 
,11-09 10:34:11.385  5615  5663 I jxcore-log: 2016-11-09 09:34:11 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPouchDBCheckpointPlugin.js'
11-09 10:34:11.385  5615  5663 I jxcore-log: 
,11-09 10:34:11.861  5615  5663 I jxcore-log: 2016-11-09 09:34:11 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPouchDBGenerator.js'
11-09 10:34:11.861  5615  5663 I jxcore-log: 
,11-09 10:34:11.864   540   540 I ServiceManager: Waiting for service AtCmdFwd...
,11-09 10:34:11.902  5615  5663 I jxcore-log: 2016-11-09 09:34:11 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js'
11-09 10:34:11.902  5615  5663 I jxcore-log: 
,11-09 10:34:11.915  5615  5663 I jxcore-log: 2016-11-09 09:34:11 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js'
11-09 10:34:11.915  5615  5663 I jxcore-log: 
,11-09 10:34:11.919  5615  5663 I jxcore-log: 2016-11-09 09:34:11 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliManager.js'
11-09 10:34:11.919  5615  5663 I jxcore-log: 
,11-09 10:34:12.197  5615  5663 I jxcore-log: 2016-11-09 09:34:12 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliManagerCoordinated.js'
11-09 10:34:12.197  5615  5663 I jxcore-log: 
,11-09 10:34:12.334  5615  5663 I jxcore-log: 2016-11-09 09:34:12 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js'
11-09 10:34:12.334  5615  5663 I jxcore-log: 
,11-09 10:34:12.699  5615  5663 I jxcore-log: 2016-11-09 09:34:12 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js'
11-09 10:34:12.699  5615  5663 I jxcore-log: 
,11-09 10:34:12.733  5615  5663 I jxcore-log: 2016-11-09 09:34:12 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeAndroid.js'
11-09 10:34:12.733  5615  5663 I jxcore-log: 
,11-09 10:34:12.740  5615  5663 I jxcore-log: 2016-11-09 09:34:12 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeDiscoveryCoordinated.js'
11-09 10:34:12.740  5615  5663 I jxcore-log: 
,11-09 10:34:12.745  5615  5663 I jxcore-log: 2016-11-09 09:34:12 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js'
11-09 10:34:12.745  5615  5663 I jxcore-log: 
,11-09 10:34:12.752  5615  5663 I jxcore-log: 2016-11-09 09:34:12 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeiOS.js'
11-09 10:34:12.752  5615  5663 I jxcore-log: 
,11-09 10:34:12.765  5615  5663 I jxcore-log: 2016-11-09 09:34:12 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js'
11-09 10:34:12.765  5615  5663 I jxcore-log: 
,11-09 10:34:12.771  5615  5663 I jxcore-log: 2016-11-09 09:34:12 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js'
11-09 10:34:12.771  5615  5663 I jxcore-log: 
,11-09 10:34:12.799  5615  5663 I jxcore-log: 2016-11-09 09:34:12 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js'
11-09 10:34:12.799  5615  5663 I jxcore-log: 
,11-09 10:34:12.836  5615  5663 I jxcore-log: 2016-11-09 09:34:12 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js'
11-09 10:34:12.836  5615  5663 I jxcore-log: 
,11-09 10:34:12.843  5615  5663 I jxcore-log: 2016-11-09 09:34:12 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationLocal.js'
11-09 10:34:12.843  5615  5663 I jxcore-log: 
,11-09 10:34:12.850  5615  5663 I jxcore-log: 2016-11-09 09:34:12 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js'
11-09 10:34:12.850  5615  5663 I jxcore-log: 
,11-09 10:34:12.864   540   540 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,11-09 10:34:12.865  5615  5663 I jxcore-log: 2016-11-09 09:34:12 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js'
11-09 10:34:12.865  5615  5663 I jxcore-log: 
,11-09 10:34:12.869  5615  5663 I jxcore-log: 2016-11-09 09:34:12 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js'
11-09 10:34:12.869  5615  5663 I jxcore-log: 
,11-09 10:34:12.875  5615  5663 I jxcore-log: 2016-11-09 09:34:12 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolDefault.js'
11-09 10:34:12.875  5615  5663 I jxcore-log: 
,11-09 10:34:12.880  5615  5663 I jxcore-log: 2016-11-09 09:34:12 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js'
11-09 10:34:12.880  5615  5663 I jxcore-log: 
,11-09 10:34:12.893  5615  5663 I jxcore-log: 2016-11-09 09:34:12 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolOneAtATime.js'
11-09 10:34:12.893  5615  5663 I jxcore-log: 
,11-09 10:34:12.900  5615  5663 I jxcore-log: 2016-11-09 09:34:12 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js'
11-09 10:34:12.900  5615  5663 I jxcore-log: 
,11-09 10:34:12.922  5615  5663 I jxcore-log: 2016-11-09 09:34:12 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js'
11-09 10:34:12.922  5615  5663 I jxcore-log: 
,11-09 10:34:12.932  5615  5663 I jxcore-log: 2016-11-09 09:34:12 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerAction.js'
11-09 10:34:12.932  5615  5663 I jxcore-log: 
,11-09 10:34:12.944  5615  5663 I jxcore-log: 2016-11-09 09:34:12 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js'
11-09 10:34:12.944  5615  5663 I jxcore-log: 
,11-09 10:34:12.954  5615  5663 I jxcore-log: 2016-11-09 09:34:12 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js'
11-09 10:34:12.954  5615  5663 I jxcore-log: 
,11-09 10:34:12.967  5615  5663 I jxcore-log: 2016-11-09 09:34:12 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js'
11-09 10:34:12.967  5615  5663 I jxcore-log: 
,11-09 10:34:12.976  5615  5663 I jxcore-log: 2016-11-09 09:34:12 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js'
11-09 10:34:12.976  5615  5663 I jxcore-log: 
,11-09 10:34:12.983  5615  5663 I jxcore-log: 2016-11-09 09:34:12 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js'
11-09 10:34:12.983  5615  5663 I jxcore-log: 
,11-09 10:34:12.989  5615  5663 I jxcore-log: 2016-11-09 09:34:12 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testUsn.js'
11-09 10:34:12.989  5615  5663 I jxcore-log: 
,11-09 10:34:12.995  5615  5663 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: SUPPORTED
,11-09 10:34:12.996  5615  5663 I jxcore-log: 2016-11-09 09:34:12 - INFO testUtils: 'BLE multiple advertisement supported'
11-09 10:34:12.996  5615  5663 I jxcore-log: 
,11-09 10:34:13.085  5615  5663 I jxcore-log: 2016-11-09 09:34:13 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-09 10:34:13.085  5615  5663 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-09 10:34:13.085  5615  5663 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-09 10:34:13.085  5615  5663 I jxcore-log: emit@events.js:82:1
11-09 10:34:13.085  5615  5663 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-09 10:34:13.085  5615  5663 I jxcore-log: emit@events.js:82:1'
11-09 10:34:13.085  5615  5663 I jxcore-log: 
,11-09 10:34:13.337  5615  5663 I jxcore-log: 2016-11-09 09:34:13 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-09 10:34:13.337  5615  5663 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-09 10:34:13.337  5615  5663 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-09 10:34:13.337  5615  5663 I jxcore-log: emit@events.js:82:1
11-09 10:34:13.337  5615  5663 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-09 10:34:13.337  5615  5663 I jxcore-log: emit@events.js:82:1'
11-09 10:34:13.337  5615  5663 I jxcore-log: 
11-09 10:34:13.339  5615  5663 I jxcore-log: 2016-11-09 09:34:13 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-09 10:34:13.339  5615  5663 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-09 10:34:13.339  5615  5663 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-09 10:34:13.339  5615  5663 I jxcore-log: emit@events.js:82:1
11-09 10:34:13.339  5615  5663 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-09 10:34:13.339  5615  5663 I jxcore-log: emit@events.js:82:1'
11-09 10:34:13.339  5615  5663 I jxcore-log: 
,11-09 10:34:13.766  5615  5663 I jxcore-log: 2016-11-09 09:34:13 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-09 10:34:13.766  5615  5663 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-09 10:34:13.766  5615  5663 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-09 10:34:13.766  5615  5663 I jxcore-log: emit@events.js:82:1
11-09 10:34:13.766  5615  5663 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-09 10:34:13.766  5615  5663 I jxcore-log: emit@events.js:82:1'
11-09 10:34:13.766  5615  5663 I jxcore-log: 
,11-09 10:34:13.768  5615  5663 I jxcore-log: 2016-11-09 09:34:13 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-09 10:34:13.768  5615  5663 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-09 10:34:13.768  5615  5663 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-09 10:34:13.768  5615  5663 I jxcore-log: emit@events.js:82:1
11-09 10:34:13.768  5615  5663 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-09 10:34:13.768  5615  5663 I jxcore-log: emit@events.js:82:1'
11-09 10:34:13.768  5615  5663 I jxcore-log: 
,11-09 10:34:14.799  5615  5663 I jxcore-log: 2016-11-09 09:34:14 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-09 10:34:14.799  5615  5663 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-09 10:34:14.799  5615  5663 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-09 10:34:14.799  5615  5663 I jxcore-log: emit@events.js:82:1
11-09 10:34:14.799  5615  5663 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-09 10:34:14.799  5615  5663 I jxcore-log: emit@events.js:82:1'
11-09 10:34:14.799  5615  5663 I jxcore-log: 
,11-09 10:34:14.802  5615  5663 I jxcore-log: 2016-11-09 09:34:14 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-09 10:34:14.802  5615  5663 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-09 10:34:14.802  5615  5663 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-09 10:34:14.802  5615  5663 I jxcore-log: emit@events.js:82:1
11-09 10:34:14.802  5615  5663 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-09 10:34:14.802  5615  5663 I jxcore-log: emit@events.js:82:1'
11-09 10:34:14.802  5615  5663 I jxcore-log: 
,11-09 10:34:15.834  5615  5663 I jxcore-log: 2016-11-09 09:34:15 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-09 10:34:15.834  5615  5663 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-09 10:34:15.834  5615  5663 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-09 10:34:15.834  5615  5663 I jxcore-log: emit@events.js:82:1
11-09 10:34:15.834  5615  5663 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-09 10:34:15.834  5615  5663 I jxcore-log: emit@events.js:82:1'
11-09 10:34:15.834  5615  5663 I jxcore-log: 
,11-09 10:34:15.839  5615  5663 I jxcore-log: 2016-11-09 09:34:15 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-09 10:34:15.839  5615  5663 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-09 10:34:15.839  5615  5663 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-09 10:34:15.839  5615  5663 I jxcore-log: emit@events.js:82:1
11-09 10:34:15.839  5615  5663 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-09 10:34:15.839  5615  5663 I jxcore-log: emit@events.js:82:1'
11-09 10:34:15.839  5615  5663 I jxcore-log: 
,11-09 10:34:16.787   931   951 I PowerManagerService: Going to sleep due to screen timeout (uid 1000)...
,11-09 10:34:16.799  3661  3661 I Keyboard.Facilitator: onFinishInput()
,11-09 10:34:16.794  3156  3156 W Binder_3: type=1400 audit(0.0:127): avc: denied { ioctl } for path="socket:[31997]" dev="sockfs" ino=31997 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
11-09 10:34:16.794  3156  3156 W Binder_3: type=1400 audit(0.0:128): avc: denied { ioctl } for path="socket:[31997]" dev="sockfs" ino=31997 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-09 10:34:16.812   931   951 I Adreno  : QUALCOMM build                   : 63c06b2, I8366cd0437,
11-09 10:34:16.812   931   951 I Adreno  : Build Date                       : 12/06/15
11-09 10:34:16.812   931   951 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
11-09 10:34:16.812   931   951 I Adreno  : Local Branch                     : mybranch17112971
11-09 10:34:16.812   931   951 I Adreno  : Remote Branch                    : quic/LA.BF64.1.2.9_v2
11-09 10:34:16.812   931   951 I Adreno  : Remote Branch                    : NONE
11-09 10:34:16.812   931   951 I Adreno  : Reconstruct Branch               : NOTHING
,11-09 10:34:16.842   382   765 D PermissionCache: checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (312 us)
,11-09 10:34:16.863  5615  5663 I jxcore-log: 2016-11-09 09:34:16 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-09 10:34:16.863  5615  5663 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-09 10:34:16.863  5615  5663 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-09 10:34:16.863  5615  5663 I jxcore-log: emit@events.js:82:1
11-09 10:34:16.863  5615  5663 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-09 10:34:16.863  5615  5663 I jxcore-log: emit@events.js:82:1'
11-09 10:34:16.863  5615  5663 I jxcore-log: 
,11-09 10:34:16.865  5615  5663 I jxcore-log: 2016-11-09 09:34:16 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-09 10:34:16.865  5615  5663 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-09 10:34:16.865  5615  5663 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-09 10:34:16.865  5615  5663 I jxcore-log: emit@events.js:82:1
11-09 10:34:16.865  5615  5663 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-09 10:34:16.865  5615  5663 I jxcore-log: emit@events.js:82:1'
11-09 10:34:16.865  5615  5663 I jxcore-log: 
,11-09 10:34:17.550  5615  5615 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,11-09 10:34:17.550  5615  5615 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,11-09 10:34:17.595   931   951 I sensors : batch
11-09 10:34:17.596   931   951 V KeyguardServiceDelegate: onScreenTurnedOff()
,11-09 10:34:17.599  5615  5615 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@bb7e490 Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@e0533da, 16908290=android.view.AbsSavedState$1@e0533da}, android:focusedViewId=100}]}]
11-09 10:34:17.600  5615  5615 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
11-09 10:34:17.600  5615  5615 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
11-09 10:34:17.600  5615  5615 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
11-09 10:34:17.602   931   951 E libEGL  : call to OpenGL ES API with no current context (logged once per thread)
11-09 10:34:17.602   931   951 I sensors : activate
,11-09 10:34:17.603   931   949 I DisplayManagerService: Display device changed state: "Built-in Screen", OFF
11-09 10:34:17.607   382   382 D SurfaceFlinger: Set power mode=0, type=0 flinger=0x7f8ba43c00
11-09 10:34:17.607   382   382 D qdhwcomposer: hwc_setPowerMode: Setting mode 0 on display: 0
11-09 10:34:17.607   931  2734 I hubconnection: sensorhub said: 'batch 31 flags:0, sampling_rate_Hz:15.00, max_report_latency_us:0'
,11-09 10:34:17.609   931  2734 I hubconnection: sensorhub said: 'activate 7 enable:0'
,11-09 10:34:17.827   511   925 D TetherController: Setting IP forward enable = 1
,11-09 10:34:17.879  5615  5663 I jxcore-log: 2016-11-09 09:34:17 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-09 10:34:17.879  5615  5663 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-09 10:34:17.879  5615  5663 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-09 10:34:17.879  5615  5663 I jxcore-log: emit@events.js:82:1
11-09 10:34:17.879  5615  5663 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-09 10:34:17.879  5615  5663 I jxcore-log: emit@events.js:82:1'
11-09 10:34:17.879  5615  5663 I jxcore-log: 
,11-09 10:34:17.882  5615  5663 I jxcore-log: 2016-11-09 09:34:17 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-09 10:34:17.882  5615  5663 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-09 10:34:17.882  5615  5663 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-09 10:34:17.882  5615  5663 I jxcore-log: emit@events.js:82:1
11-09 10:34:17.882  5615  5663 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-09 10:34:17.882  5615  5663 I jxcore-log: emit@events.js:82:1'
11-09 10:34:17.882  5615  5663 I jxcore-log: 
,11-09 10:34:17.899   382   481 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0
,11-09 10:34:17.900   382   382 D qdhwcomposer: hwc_setPowerMode: Done setting mode 0 on display 0
,11-09 10:34:17.902   931  3068 D SurfaceControl: Excessive delay in setPowerMode(): 299ms
,11-09 10:34:17.905   931   951 I DreamManagerService: Entering dreamland.
11-09 10:34:17.906   931   951 I PowerManagerService: Dozing...
,11-09 10:34:17.906   931   946 I DreamController: Starting dream: name=ComponentInfo{com.android.systemui/com.android.systemui.doze.DozeService}, isTest=false, canDoze=true, userId=0
,11-09 10:34:17.921  4826  4826 W Binder_A: type=1400 audit(0.0:129): avc: denied { ioctl } for path="socket:[35111]" dev="sockfs" ino=35111 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-09 10:34:17.921  4826  4826 W Binder_A: type=1400 audit(0.0:130): avc: denied { ioctl } for path="socket:[35111]" dev="sockfs" ino=35111 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-09 10:34:17.926   931  3156 I sensors : batch
11-09 10:34:17.926   931  3156 I sensors : activate
,11-09 10:34:17.929   931  2734 I hubconnection: sensorhub said: 'batch 21 flags:0, sampling_rate_Hz:1000.00, max_report_latency_us:0'
,11-09 10:34:17.930   931  2734 I hubconnection: sensorhub said: 'activate 21 enable:1'
,11-09 10:34:17.935   516   516 D audio_hw_primary: adev_set_parameters: enter: screen_state=on
,11-09 10:34:17.939   931  2959 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
11-09 10:34:17.940   931  2957 E native  : do suspend false
,11-09 10:34:17.945   931  2957 D WifiConfigStore: No blacklist allowed without epno enabled
,11-09 10:34:17.953  3777  4762 D ScreenStateRecorder : ScreenStateRecorderHandler, handleMessage msg.what = 1
,11-09 10:34:17.953  3777  4762 D         : oem_qmi_lib:come into oem_qmi_common_stream_from_modem_len --->modem 
11-09 10:34:17.954  3777  4762 D         : oem_qmi_lib:oem_qmi_cmd: Send to server  passed!!
11-09 10:34:17.954   530  1327 D         : oem-qmi: Connection accepted
11-09 10:34:17.954   530  1327 D         : oem-qmi: Waiting to accept connection
,11-09 10:34:17.956   931   931 I sensors : activate
,11-09 10:34:17.956  3777  4762 D         : oem_qmi_lib:output 0
11-09 10:34:17.956  3777  4762 D         : oem_qmi_lib:rapi_event_type=10057, qmi_ret=0, return_status=1. 
,11-09 10:34:17.956   516  3008 D audio_hw_primary: adev_set_parameters: enter: screen_state=off
,11-09 10:34:17.958   931  2957 E native  : do suspend true
11-09 10:34:17.959   931  2734 I hubconnection: sensorhub said: 'activate 31 enable:0'
,11-09 10:34:17.974  3777  4762 D ScreenStateRecorder : ScreenStateRecorderHandler, handleMessage msg.what = 2
,11-09 10:34:17.974  3777  4762 D         : oem_qmi_lib:come into oem_qmi_common_stream_from_modem_len --->modem 
11-09 10:34:17.975  3777  4762 D         : oem_qmi_lib:oem_qmi_cmd: Send to server  passed!!
11-09 10:34:17.975   530  1327 D         : oem-qmi: Connection accepted
11-09 10:34:17.975   530  1327 D         : oem-qmi: Waiting to accept connection
,11-09 10:34:17.976  3777  4762 D         : oem_qmi_lib:output 0
,11-09 10:34:17.976  3777  4762 D         : oem_qmi_lib:rapi_event_type=10057, qmi_ret=0, return_status=1. 
,11-09 10:34:18.437   931  2957 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 14, 15 -> obsolete
,11-09 10:34:18.918  5615  5663 I jxcore-log: 2016-11-09 09:34:18 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-09 10:34:18.918  5615  5663 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-09 10:34:18.918  5615  5663 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-09 10:34:18.918  5615  5663 I jxcore-log: emit@events.js:82:1
11-09 10:34:18.918  5615  5663 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-09 10:34:18.918  5615  5663 I jxcore-log: emit@events.js:82:1'
11-09 10:34:18.918  5615  5663 I jxcore-log: 
,11-09 10:34:18.924  5615  5663 I jxcore-log: 2016-11-09 09:34:18 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-09 10:34:18.924  5615  5663 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-09 10:34:18.924  5615  5663 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-09 10:34:18.924  5615  5663 I jxcore-log: emit@events.js:82:1
11-09 10:34:18.924  5615  5663 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-09 10:34:18.924  5615  5663 I jxcore-log: emit@events.js:82:1'
11-09 10:34:18.924  5615  5663 I jxcore-log: 
,11-09 10:34:19.958  5615  5663 I jxcore-log: 2016-11-09 09:34:19 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-09 10:34:19.958  5615  5663 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-09 10:34:19.958  5615  5663 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-09 10:34:19.958  5615  5663 I jxcore-log: emit@events.js:82:1
11-09 10:34:19.958  5615  5663 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-09 10:34:19.958  5615  5663 I jxcore-log: emit@events.js:82:1'
11-09 10:34:19.958  5615  5663 I jxcore-log: 
,11-09 10:34:19.963  5615  5663 I jxcore-log: 2016-11-09 09:34:19 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-09 10:34:19.963  5615  5663 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-09 10:34:19.963  5615  5663 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-09 10:34:19.963  5615  5663 I jxcore-log: emit@events.js:82:1
11-09 10:34:19.963  5615  5663 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-09 10:34:19.963  5615  5663 I jxcore-log: emit@events.js:82:1'
11-09 10:34:19.963  5615  5663 I jxcore-log: 
,11-09 10:34:20.995  5615  5663 I jxcore-log: 2016-11-09 09:34:20 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-09 10:34:20.995  5615  5663 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-09 10:34:20.995  5615  5663 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-09 10:34:20.995  5615  5663 I jxcore-log: emit@events.js:82:1
11-09 10:34:20.995  5615  5663 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-09 10:34:20.995  5615  5663 I jxcore-log: emit@events.js:82:1'
11-09 10:34:20.995  5615  5663 I jxcore-log: 
,11-09 10:34:20.999  5615  5663 I jxcore-log: 2016-11-09 09:34:20 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-09 10:34:20.999  5615  5663 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-09 10:34:20.999  5615  5663 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-09 10:34:20.999  5615  5663 I jxcore-log: emit@events.js:82:1
11-09 10:34:20.999  5615  5663 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-09 10:34:20.999  5615  5663 I jxcore-log: emit@events.js:82:1'
11-09 10:34:20.999  5615  5663 I jxcore-log: 
,11-09 10:34:21.436  3930  4449 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,11-09 10:34:22.075  5615  5663 I jxcore-log: 2016-11-09 09:34:22 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-09 10:34:22.075  5615  5663 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-09 10:34:22.075  5615  5663 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-09 10:34:22.075  5615  5663 I jxcore-log: emit@events.js:82:1
11-09 10:34:22.075  5615  5663 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-09 10:34:22.075  5615  5663 I jxcore-log: emit@events.js:82:1'
11-09 10:34:22.075  5615  5663 I jxcore-log: 
,11-09 10:34:22.080  5615  5663 I jxcore-log: 2016-11-09 09:34:22 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-09 10:34:22.080  5615  5663 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-09 10:34:22.080  5615  5663 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-09 10:34:22.080  5615  5663 I jxcore-log: emit@events.js:82:1
11-09 10:34:22.080  5615  5663 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-09 10:34:22.080  5615  5663 I jxcore-log: emit@events.js:82:1'
11-09 10:34:22.080  5615  5663 I jxcore-log: 
,11-09 10:34:22.153   931  2957 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 12, 15 -> obsolete
,11-09 10:34:23.121  5615  5663 I jxcore-log: 2016-11-09 09:34:23 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-09 10:34:23.121  5615  5663 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-09 10:34:23.121  5615  5663 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-09 10:34:23.121  5615  5663 I jxcore-log: emit@events.js:82:1
11-09 10:34:23.121  5615  5663 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-09 10:34:23.121  5615  5663 I jxcore-log: emit@events.js:82:1'
11-09 10:34:23.121  5615  5663 I jxcore-log: 
,11-09 10:34:23.127  5615  5663 I jxcore-log: 2016-11-09 09:34:23 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-09 10:34:23.127  5615  5663 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-09 10:34:23.127  5615  5663 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-09 10:34:23.127  5615  5663 I jxcore-log: emit@events.js:82:1
11-09 10:34:23.127  5615  5663 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-09 10:34:23.127  5615  5663 I jxcore-log: emit@events.js:82:1'
11-09 10:34:23.127  5615  5663 I jxcore-log: 
,11-09 10:34:24.160  5615  5663 I jxcore-log: 2016-11-09 09:34:24 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-09 10:34:24.160  5615  5663 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-09 10:34:24.160  5615  5663 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-09 10:34:24.160  5615  5663 I jxcore-log: emit@events.js:82:1
11-09 10:34:24.160  5615  5663 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-09 10:34:24.160  5615  5663 I jxcore-log: emit@events.js:82:1'
11-09 10:34:24.160  5615  5663 I jxcore-log: 
,11-09 10:34:24.165  5615  5663 I jxcore-log: 2016-11-09 09:34:24 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-09 10:34:24.165  5615  5663 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-09 10:34:24.165  5615  5663 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-09 10:34:24.165  5615  5663 I jxcore-log: emit@events.js:82:1
11-09 10:34:24.165  5615  5663 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-09 10:34:24.165  5615  5663 I jxcore-log: emit@events.js:82:1'
11-09 10:34:24.165  5615  5663 I jxcore-log: 
,11-09 10:34:25.196  5615  5663 I jxcore-log: 2016-11-09 09:34:25 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-09 10:34:25.196  5615  5663 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-09 10:34:25.196  5615  5663 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-09 10:34:25.196  5615  5663 I jxcore-log: emit@events.js:82:1
11-09 10:34:25.196  5615  5663 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-09 10:34:25.196  5615  5663 I jxcore-log: emit@events.js:82:1'
11-09 10:34:25.196  5615  5663 I jxcore-log: 
,11-09 10:34:25.202  5615  5663 I jxcore-log: 2016-11-09 09:34:25 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-09 10:34:25.202  5615  5663 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-09 10:34:25.202  5615  5663 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-09 10:34:25.202  5615  5663 I jxcore-log: emit@events.js:82:1
11-09 10:34:25.202  5615  5663 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-09 10:34:25.202  5615  5663 I jxcore-log: emit@events.js:82:1'
11-09 10:34:25.202  5615  5663 I jxcore-log: 
,11-09 10:34:25.406   931  5917 D NetlinkSocketObserver: NeighborEvent{elapsedMs=160340, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,11-09 10:34:26.237  5615  5663 I jxcore-log: 2016-11-09 09:34:26 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-09 10:34:26.237  5615  5663 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-09 10:34:26.237  5615  5663 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-09 10:34:26.237  5615  5663 I jxcore-log: emit@events.js:82:1
11-09 10:34:26.237  5615  5663 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-09 10:34:26.237  5615  5663 I jxcore-log: emit@events.js:82:1'
11-09 10:34:26.237  5615  5663 I jxcore-log: 
,11-09 10:34:26.243  5615  5663 I jxcore-log: 2016-11-09 09:34:26 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-09 10:34:26.243  5615  5663 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-09 10:34:26.243  5615  5663 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-09 10:34:26.243  5615  5663 I jxcore-log: emit@events.js:82:1
11-09 10:34:26.243  5615  5663 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-09 10:34:26.243  5615  5663 I jxcore-log: emit@events.js:82:1'
11-09 10:34:26.243  5615  5663 I jxcore-log: 
,11-09 10:34:27.272  5615  5663 I jxcore-log: 2016-11-09 09:34:27 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-09 10:34:27.272  5615  5663 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-09 10:34:27.272  5615  5663 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-09 10:34:27.272  5615  5663 I jxcore-log: emit@events.js:82:1
11-09 10:34:27.272  5615  5663 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-09 10:34:27.272  5615  5663 I jxcore-log: emit@events.js:82:1'
11-09 10:34:27.272  5615  5663 I jxcore-log: 
,11-09 10:34:27.284  5615  5663 E jxcore  : Error!: error is undefined
11-09 10:34:27.284  5615  5663 E jxcore  : Stack: [{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/lib/CoordinatedClient.js","_functionName":"CoordinatedClient.prototype._error","_lineNumber":"220","_columnNumber":"1","_msg":"    at CoordinatedClient.prototype._error@/data/data/com.test.thalitest/files/www/jxcore/lib/CoordinatedClient.js:220:1"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/component-emitter/index.js","_functionName":"Emitter.prototype.emit","_lineNumber":"131","_columnNumber":"7","_msg":"    at Emitter.prototype.emit@/data/data/com.test.thalitest/files/www/jxcore/node_modules/component-emitter/index.js:131:7"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/socket.js","_functionName":"Socket.prototype.emit","_lineNumber":"133","_columnNumber":"5","_msg":"    at Socket.prototype.emit@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/socket.js:133:5"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js","_functionName":"Manager.prototype.emitAll","_lineNumber":"81","_columnNumber":"7","_msg":"    at Manager.prototype.emitAll@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:81:7"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js","_functionName":"Manager.prototype.reconnect","_lineNumber":"507","_columnNumber":"5","_msg":"    at Manager.prototype.reconnect@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:507:5"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js","_functionName":"Manager.prototype.reconnect/timer</<","_lineNumber":"528","_columnNumber":"11","_msg":"    at Manager.prototype.reconnect/timer</<@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:528:11"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js","_functionName":"Manager.prototype.connect/errorSub<","_lineNumber":"235","_columnNumber":"7","_msg":"    at Manager.prototype.connect/errorSub<@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:235:7"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/node_modules/component-emitter/index.js","_functionName":"Emitter.prototype.emit","_lineNumber":"134","_columnNumber":"7","_msg":"    at Emitter.prototype.emit@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/node_modules/component-emitter/index.js:134:7"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/socket.js","_functionName":"Socket.prototype.onError","_lineNumber":"670","_columnNumber":"3","_msg":"    at Socket.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/socket.js:670:3"}]
,11-09 10:34:27.288  5615  5663 I jxcore-log: 2016-11-09 09:34:27 - ERROR TestsProcess: 'uncaught exception, error: 'TypeError: error is undefined', stack: 'TypeError: error is undefined
11-09 10:34:27.288  5615  5663 I jxcore-log:     at CoordinatedClient.prototype._error@/data/data/com.test.thalitest/files/www/jxcore/lib/CoordinatedClient.js:220:1
11-09 10:34:27.288  5615  5663 I jxcore-log:     at Emitter.prototype.emit@/data/data/com.test.thalitest/files/www/jxcore/node_modules/component-emitter/index.js:131:7
11-09 10:34:27.288  5615  5663 I jxcore-log:     at Socket.prototype.emit@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/socket.js:133:5
11-09 10:34:27.288  5615  5663 I jxcore-log:     at Manager.prototype.emitAll@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:81:7
11-09 10:34:27.288  5615  5663 I jxcore-log:     at Manager.prototype.reconnect@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:507:5
11-09 10:34:27.288  5615  5663 I jxcore-log:     at Manager.prototype.reconnect/timer</<@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:528:11
11-09 10:34:27.288  5615  5663 I jxcore-log:     at Manager.prototype.connect/errorSub<@/data/data/com.test.thalitest/files/www/jxcore/node_modules/sock
,11-09 10:34:27.290  5615  5663 I jxcore-log: 2016-11-09 09:34:27 - ERROR TestsProcess: '****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****'
11-09 10:34:27.290  5615  5663 I jxcore-log: 
,11-09 10:34:27.292  5615  5663 E jxcore-log: TypeError: 
11-09 10:34:27.292  5615  5663 E jxcore-log: error is undefined
11-09 10:34:27.292  5615  5663 E jxcore-log:  (/data/data/com.test.thalitest/files/www/jxcore/lib/CoordinatedClient.js 220:0)
11-09 10:34:27.292  5615  5663 E jxcore-log: 
,11-09 10:34:27.390   931  3156 D GraphicsStats: Buffer count: 2
11-09 10:34:27.390   931   942 I WindowState: WIN DEATH: Window{69d74c9 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,11-09 10:34:27.391   931  2958 D WifiService: Client connection lost with reason: 4
,11-09 10:34:27.405   532   532 I Zygote  : Process 5615 exited cleanly (139)
,11-09 10:34:27.406   931   941 I ActivityManager: Process com.test.thalitest (pid 5615) has died
,11-09 10:34:27.421   931   941 I ActivityManager: Start proc 5991:com.test.thalitest/u0a77 for activity com.test.thalitest/.MainActivity
,11-09 10:34:27.480  5991  5991 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011750)
,11-09 10:34:27.498  5991  5991 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,11-09 10:34:27.503  5991  5991 I LibraryLoader: Time to load native libraries: 2 ms (timestamps 2435-2437)
,11-09 10:34:27.503  5991  5991 I LibraryLoader: Expected native library version number "",actual native library version number ""
,11-09 10:34:27.511  5991  5991 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {6d7c4d5}
11-09 10:34:27.512  5991  5991 I LibraryLoader: Expected native library version number "",actual native library version number ""
,11-09 10:34:27.512  5991  5991 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,11-09 10:34:27.515  5991  5991 I BrowserStartupController: Initializing chromium process, singleProcess=true
,11-09 10:34:27.516  5991  5991 E SysUtils: ApplicationContext is null in ApplicationStatus
,11-09 10:34:27.525  5991  5991 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,11-09 10:34:27.532  5991  5991 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,11-09 10:34:27.532  5991  5991 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
11-09 10:34:27.533  5991  5991 I Adreno  : QUALCOMM build                   : 63c06b2, I8366cd0437
11-09 10:34:27.533  5991  5991 I Adreno  : Build Date                       : 12/06/15
11-09 10:34:27.533  5991  5991 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
11-09 10:34:27.533  5991  5991 I Adreno  : Local Branch                     : mybranch17112971
11-09 10:34:27.533  5991  5991 I Adreno  : Remote Branch                    : quic/LA.BF64.1.2.9_v2
11-09 10:34:27.533  5991  5991 I Adreno  : Remote Branch                    : NONE
11-09 10:34:27.533  5991  5991 I Adreno  : Reconstruct Branch               : NOTHING
,11-09 10:34:27.563   931   948 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@73d59c6:true
,11-09 10:34:27.574   766   766 W Binder_4: type=1400 audit(0.0:131): avc: denied { ioctl } for path="socket:[14942]" dev="sockfs" ino=14942 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-09 10:34:27.574   766   766 W Binder_4: type=1400 audit(0.0:132): avc: denied { ioctl } for path="socket:[14942]" dev="sockfs" ino=14942 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-09 10:34:27.586  5991  5991 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,11-09 10:34:27.594  5991  5991 D SystemWebViewEngine: CordovaWebView is running on device made by: Huawei
,11-09 10:34:27.621   403   403 W Binder_1: type=1400 audit(0.0:133): avc: denied { ioctl } for path="socket:[31741]" dev="sockfs" ino=31741 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-09 10:34:27.623  5991  6027 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
11-09 10:34:27.621   403   403 W Binder_1: type=1400 audit(0.0:134): avc: denied { ioctl } for path="socket:[31741]" dev="sockfs" ino=31741 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-09 10:34:27.624  3428  3428 W Binder_5: type=1400 audit(0.0:135): avc: denied { ioctl } for path="socket:[20365]" dev="sockfs" ino=20365 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-09 10:34:27.624  3428  3428 W Binder_5: type=1400 audit(0.0:136): avc: denied { ioctl } for path="socket:[20365]" dev="sockfs" ino=20365 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-09 10:34:27.628  5991  6014 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,11-09 10:34:27.667  5991  6027 I OpenGLRenderer: Initialized EGL, version 1.4
,11-09 10:34:27.698   931   949 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +258ms (total +291ms)
,11-09 10:34:27.699   931  3429 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 5615 uid 10077
,11-09 10:34:27.697  3429  3429 W Binder_6: type=1400 audit(0.0:137): avc: denied { ioctl } for path="socket:[35954]" dev="sockfs" ino=35954 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
11-09 10:34:27.697  3429  3429 W Binder_6: type=1400 audit(0.0:138): avc: denied { ioctl } for path="socket:[35954]" dev="sockfs" ino=35954 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-09 10:34:27.697  3428  3428 W Binder_5: type=1400 audit(0.0:139): avc: denied { ioctl } for path="socket:[35953]" dev="sockfs" ino=35953 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-09 10:34:27.697  3428  3428 W Binder_5: type=1400 audit(0.0:140): avc: denied { ioctl } for path="socket:[35953]" dev="sockfs" ino=35953 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-09 10:34:27.704  5991  5991 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 5991
,11-09 10:34:27.705  3661  3661 I Keyboard.Facilitator: onFinishInput()
,11-09 10:34:27.715  5989  5989 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,11-09 10:34:27.719  5989  5989 D AndroidRuntime: CheckJNI is OFF
,11-09 10:34:27.740  5989  5989 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,11-09 10:34:27.764  5989  5989 I Radio-JNI: register_android_hardware_Radio DONE
,11-09 10:34:27.765  5991  5991 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,11-09 10:34:27.780  5989  5989 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,11-09 10:34:27.785   931   944 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=-1: uninstall pkg
11-09 10:34:27.785   931   944 I ActivityManager: Killing 5991:com.test.thalitest/u0a77 (adj 0): stop com.test.thalitest
,11-09 10:34:27.822   931   942 D GraphicsStats: Buffer count: 2
,11-09 10:34:27.822   931   941 I WindowState: WIN DEATH: Window{9b9e34d u0 com.test.thalitest/com.test.thalitest.MainActivity}
,11-09 10:34:27.864   540   540 I ServiceManager: Waiting for service AtCmdFwd...
,11-09 10:34:27.898   931   944 W ActivityManager: Failed trying to unstop package com.test.thalitest: java.lang.IllegalArgumentException: Unknown package: com.test.thalitest
,11-09 10:34:27.899   931   944 W PackageManager: Package com.test.thalitest is missing; assuming frozen
11-09 10:34:27.900   931   944 E ActivityManager: Failure starting process com.test.thalitest
11-09 10:34:27.900   931   944 E ActivityManager: java.lang.RuntimeException: Package com.test.thalitest is frozen!
11-09 10:34:27.900   931   944 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3278)
11-09 10:34:27.900   931   944 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3237)
11-09 10:34:27.900   931   944 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3116)
11-09 10:34:27.900   931   944 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1395)
11-09 10:34:27.900   931   944 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:2007)
11-09 10:34:27.900   931   944 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1554)
11-09 10:34:27.900   931   944 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2735)
11-09 10:34:27.900   931   944 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2724)
11-09 10:34:27.900   931   944 E ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4598)
11-09 10:34:27.900   931   944 E ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:5955)
11-09 10:34:27.900   931   944 E ActivityManager: 	at com.android.server.am.ActivityManagerService.killPackageProcessesLocked(ActivityManagerService.java:5614)
11-09 10:34:27.900   931   944 E ActivityManager: 	at com.android.server.am.ActivityManagerService.forceStopPackageLocked(ActivityManagerService.java:5763)
11-09 10:34:27.900   931   944 E ActivityManager: 	at com.android.server.am.ActivityManagerService.-wrap1(ActivityManagerService.java)
11-09 10:34:27.900   931   944 E ActivityManager: 	at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:1736)
11-09 10:34:27.900   931   944 E ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-09 10:34:27.900   931   944 E ActivityManager: 	at android.os.Looper.loop(Looper.java:148)
11-09 10:34:27.900   931   944 E ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
11-09 10:34:27.900   931   944 E ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
11-09 10:34:27.900   931   944 I ActivityManager:   Force finishing activity ActivityRecord{e068e96 u0 com.test.thalitest/.MainActivity t68}
,11-09 10:34:27.901   931   954 I art     : Starting a blocking GC Explicit
,11-09 10:34:27.910   931  3770 W ActivityManager: Spurious death for ProcessRecord{490a313 0:com.test.thalitest/u0a77}, curProc for 5991: null
,11-09 10:34:27.987   931   954 I art     : Explicit concurrent mark sweep GC freed 17670(1175KB) AllocSpace objects, 6(120KB) LOS objects, 33% free, 29MB/43MB, paused 1.615ms total 85.739ms
,11-09 10:34:28.007   931   954 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,11-09 10:34:28.011  5989  5989 I art     : System.exit called, status: 0
,11-09 10:34:28.011  5989  5989 I AndroidRuntime: VM exiting with result code 0.
,11-09 10:34:28.025   931   954 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=0: pkg removed
,11-09 10:34:28.033   931   944 I ActivityManager: Exiting empty application process com.test.thalitest (null)
,11-09 10:34:28.038  5844  5844 D BluetoothMapAppObserver: onReceive
11-09 10:34:28.039  5844  5844 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
11-09 10:34:28.039  3661  3661 I Keyboard.Facilitator: resetDictionaries() : en_US
11-09 10:34:28.039  3930  4110 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
11-09 10:34:28.042   931  2949 I InputReader: Reconfiguring input devices.  changes=0x00000010
,11-09 10:34:28.078  3412  6044 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,11-09 10:34:28.081  3661  6042 I Keyboard.Facilitator.DecoderInitializer: run()
,11-09 10:34:28.100  3777  3777 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,11-09 10:34:28.112  3589  3589 E NetworkScheduler.SchedulerReceiver: Invalid parameter app
,11-09 10:34:28.112  3589  3589 E NetworkScheduler.SchedulerReceiver: Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,11-09 10:34:28.120  3661  6042 I Decoder : createOrResetDecoder
,11-09 10:34:28.123   931   931 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
11-09 10:34:28.121    13    13 W kworker/1:0: type=1400 audit(0.0:141): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-09 10:34:28.134    13    13 W kworker/1:0: type=1400 audit(0.0:142): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-09 10:34:28.161   931  4826 I ActivityManager: Start proc 6049:com.google.android.googlequicksearchbox:crash_report/u0a29 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
,--------- beginning of crash
11-09 10:34:28.162  3806  3882 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
11-09 10:34:28.162  3806  3882 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 3806
11-09 10:34:28.162  3806  3882 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 778)
11-09 10:34:28.162  3806  3882 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
11-09 10:34:28.162  3806  3882 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
11-09 10:34:28.162  3806  3882 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
11-09 10:34:28.162  3806  3882 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
11-09 10:34:28.162  3806  3882 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
11-09 10:34:28.162  3806  3882 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
11-09 10:34:28.162  3806  3882 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
11-09 10:34:28.162  3806  3882 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
11-09 10:34:28.162  3806  3882 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
11-09 10:34:28.162  3806  3882 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
11-09 10:34:28.162  3806  3882 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,11-09 10:34:28.161    13    13 W kworker/1:0: type=1400 audit(0.0:143): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-09 10:34:28.169   931  3429 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,11-09 10:34:28.181  3806  3882 I Process : Sending signal. PID: 3806 SIG: 9
,11-09 10:34:28.183  3589  3589 I ConfigService: onCreate
,11-09 10:34:28.186  3589  6063 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/config.db'.
11-09 10:34:28.186  3589  6063 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
11-09 10:34:28.186  3589  6063 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
11-09 10:34:28.186  3589  6063 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
11-09 10:34:28.186  3589  6063 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
11-09 10:34:28.186  3589  6063 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
11-09 10:34:28.186  3589  6063 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
11-09 10:34:28.186  3589  6063 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
11-09 10:34:28.186  3589  6063 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
11-09 10:34:28.186  3589  6063 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
11-09 10:34:28.186  3589  6063 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
11-09 10:34:28.186  3589  6063 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
11-09 10:34:28.186  3589  6063 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
11-09 10:34:28.186  3589  6063 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
11-09 10:34:28.186  3589  6063 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
11-09 10:34:28.186  3589  6063 E SQLiteDatabase: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
11-09 10:34:28.186  3589  6063 E SQLiteDatabase: 	at com.google.android.gms.config.j.run(SourceFile:152)
11-09 10:34:28.186  3589  6063 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
11-09 10:34:28.187  3589  6063 E SQLiteOpenHelper: Couldn't open config.db for writing (will try read-only):
11-09 10:34:28.187  3589  6063 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
11-09 10:34:28.187  3589  6063 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
11-09 10:34:28.187  3589  6063 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
11-09 10:34:28.187  3589  6063 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
11-09 10:34:28.187  3589  6063 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
11-09 10:34:28.187  3589  6063 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
11-09 10:34:28.187  3589  6063 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
11-09 10:34:28.187  3589  6063 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
11-09 10:34:28.187  3589  6063 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
11-09 10:34:28.187  3589  6063 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
11-09 10:34:28.187  3589  6063 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
11-09 10:34:28.187  3589  6063 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
11-09 10:34:28.187  3589  6063 E SQLiteOpenHelper:, 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
11-09 10:34:28.187  3589  6063 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
11-09 10:34:28.187  3589  6063 E SQLiteOpenHelper: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
11-09 10:34:28.187  3589  6063 E SQLiteOpenHelper: 	at com.google.android.gms.config.j.run(SourceFile:152)
11-09 10:34:28.187  3589  6063 E SQLiteOpenHelper: 	at java.lang.Thread.run(Thread.java:818)
11-09 10:34:28.189  3589  6063 W SQLiteOpenHelper: Opened config.db in read-only mode
11-09 10:34:28.201  3589  3589 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/ns.db'.
11-09 10:34:28.201  3589  3589 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
11-09 10:34:28.201  3589  3589 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
11-09 10:34:28.201  3589  3589 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
11-09 10:34:28.201  3589  3589 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
11-09 10:34:28.201  3589  3589 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
11-09 10:34:28.201  3589  3589 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
11-09 10:34:28.201  3589  3589 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
11-09 10:34:28.201  3589  3589 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
11-09 10:34:28.201  3589  3589 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
11-09 10:34:28.201  3589  3589 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
11-09 10:34:28.201  3589  3589 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
11-09 10:34:28.201  3589  3589 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
11-09 10:34:28.201  3589  3589 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
11-09 10:34:28.201  3589  3589 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
11-09 10:34:28.201  3589  3589 E SQLiteDatabase: 	at com.google.android.gms.gcm.nts.n.b(SourceFile:262)
11-09 10:34:28.201  3589  3589 E SQLiteDatabase: 	at com.google.android.gms.gcm.nts.k.a(SourceFile:55)
11-09 10:34:28.201  3589  3589 E SQLiteDatabase: 	at com.google.android.gms.gcm.nts.l.handleMessage(SourceFile:176)
11-09 10:34:28.201  3589  3589 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-09 10:34:28.201  3589  3589 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
11-09 10:34:28.201  3589  3589 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-09 10:34:28.201  3589  3589 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
11-09 10:34:28.201  3589  3589 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-09 10:34:28.201  3589  3589 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-09 10:34:28.202  3589  3589 D AndroidRuntime: Shutting down VM
11-09 10:34:28.202  3589  3589 E AndroidRuntime: FATAL EXCEPTION: main
11-09 10:34:28.202  3589  3589 E AndroidRuntime: Process: com.google.process.gapps, PID: 3589
11-09 10:34:28.202  3589  3589 E AndroidRuntime: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
11-09 10:34:28.202  3589  3589 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
11-09 10:34:28.202  3589  3589 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
11-09 10:34:28.202  3589  3589 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
11-09 10:34:28.202  3589  3589 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
11-09 10:34:28.202  3589  3589 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
11-09 10:34:28.202  3589  3589 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
11-09 10:34:28.202  3589  3589 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
11-09 10:34:28.202  3589  3589 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
11-09 10:34:28.202  3589  3589 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
11-09 10:34:28.202  3589  3589 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
11-09 10:34:28.202  3589  3589 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
11-09 10:34:28.202  3589  3589 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
11-09 10:34:28.202  3589  3589 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
11-09 10:34:28.202  3589  3589 E AndroidRuntime: 	at com.google.android.gms.gcm.nts.n.b(SourceFile:262)
11-09 10:34:28.202  3589  3589 E AndroidRuntime: 	at com.google.android.gms.gcm.nts.k.a(SourceFile:55)
11-09 10:34:28.202  3589  3589 E AndroidRuntime: 	at com.google.android.gms.gcm.nts.l.handleMessage(SourceFile:176)
11-09 10:34:28.202  3589  3589 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-09 10:34:28.202  3589  3589 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
11-09 10:34:28.202  3589  3589 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-09 10:34:28.202  3589  3589 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
11-09 10:34:28.202  3589  3589 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-09 10:34:28.202  3589  3589 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-09 10:34:28.205  3412  6044 E SQLiteLog: (3850) statement aborts at 18: [DELETE FROM calls WHERE (((source_package = 'com.test.thalitest'))) AND ((type = 4))] disk I/O error
11-09 10:34:28.206  3589  3589 I Process : Sending signal. PID: 3589 SIG: 9
11-09 10:34:28.209   931  6064 E DropBoxManagerService: Can't write: system_app_crash
11-09 10:34:28.209   931  6064 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop124.tmp: open failed: EROFS (Read-only file system)
11-09 10:34:28.209   931  6064 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
11-09 10:34:28.209   931  6064 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
11-09 10:34:28.209   931  6064 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
11-09 10:34:28.209   931  6064 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
11-09 10:34:28.209   931  6064 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
11-09 10:34:28.209   931  6064 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
11-09 10:34:28.209   931  6064 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
11-09 10:34:28.209   931  6064 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
11-09 10:34:28.209   931  6064 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
11-09 10:34:28.209   931  6064 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
11-09 10:34:28.209   931  6064 E DropBoxManagerService: 	... 5 more
11-09 10:34:28.210  4045  6062 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
11-09 10:34:28.219  3412  6044 E AndroidRuntime: FATAL EXCEPTION: IntentService[VoicemailCleanupService]
11-09 10:34:28.219  3412  6044 E AndroidRuntime: Process: android.process.acore, PID: 3412
11-09 10:34:28.219  3412  6044 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
11-09 10:34:28.219  3412  6044 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
11-09 10:34:28.219  3412  6044 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
11-09 10:34:28.219  3412  6044 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
11-09 10:34:28.219  3412  6044 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
11-09 10:34:28.219  3412  6044 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
11-09 10:34:28.219  3412  6044 E AndroidRuntime: 	at com.android.providers.contacts.DbModifierWithNotification.delete(DbModifierWithNotification.java:197)
11-09 10:34:28.219  3412  6044 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:219)
11-09 10:34:28.219  3412  6044 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
11-09 10:34:28.219  3412  6044 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
11-09 10:34:28.219  3412  6044 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
11-09 10:34:28.219  3412  6044 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
11-09 10:34:28.219  3412  6044 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
11-09 10:34:28.219  3412  6044 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
11-09 10:34:28.219  3412  6044 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-09 10:34:28.219  3412  6044 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
11-09 10:34:28.219  3412  6044 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,11-09 10:34:28.221  4045  6062 D AccountUtils: Clearing selected account for com.test.thalitest
11-09 10:34:28.221   931  6066 E DropBoxManagerService: Can't write: system_app_crash
11-09 10:34:28.221   931  6066 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop125.tmp: open failed: EROFS (Read-only file system)
11-09 10:34:28.221   931  6066 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
11-09 10:34:28.221   931  6066 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
11-09 10:34:28.221   931  6066 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
11-09 10:34:28.221   931  6066 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
11-09 10:34:28.221   931  6066 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
11-09 10:34:28.221   931  6066 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
11-09 10:34:28.221   931  6066 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
11-09 10:34:28.221   931  6066 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
11-09 10:34:28.221   931  6066 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
11-09 10:34:28.221   931  6066 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
11-09 10:34:28.221   931  6066 E DropBoxManagerService: 	... 5 more

```
