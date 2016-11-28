#### Test 95507328adf6a6a_thali07_Huawei-Nexus 6P Logs


```
--------- beginning of main
11-28 17:46:43.787  4056  4240 I Icing   : Indexing 3C763AF371F9E97B4ECFEA01A338ADB468C38476 from com.google.android.googlequicksearchbox
,11-28 17:46:43.879  4056  4240 I Icing   : Indexing done 3C763AF371F9E97B4ECFEA01A338ADB468C38476
11-28 17:46:44.242  5597  5597 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
11-28 17:46:44.247  5597  5597 D AndroidRuntime: CheckJNI is OFF
11-28 17:46:44.275  5597  5597 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
11-28 17:46:44.309  5597  5597 I Radio-JNI: register_android_hardware_Radio DONE
11-28 17:46:44.324  5597  5597 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
11-28 17:46:44.339   928  3598 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
11-28 17:46:44.355  5597  5597 D AndroidRuntime: Shutting down VM
11-28 17:46:44.366  3966  4362 W SearchService: Abort, client detached.
11-28 17:46:44.368  3966  3966 I HotwordDetector: Closing mic
11-28 17:46:44.369  3966  4231 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@3c8ef10
11-28 17:46:44.369  3966  4242 E AudioRecord-JNI: Error -4 during AudioRecord native read
11-28 17:46:44.391   928  3212 I ActivityManager: Start proc 5606:com.test.thalitest/u0a77 for activity com.test.thalitest/.MainActivity
11-28 17:46:44.429   513  4246 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
11-28 17:46:44.431   513  4246 D audio_hw_primary: disable_snd_device: snd_device(63: voice-rec-mic)
11-28 17:46:44.436   513  4246 I soundtrigger: audio_extn_sound_trigger_update_device_status: device 0x3f of type 1 for Event 0
11-28 17:46:44.437   513  4246 D sound_trigger_platform: platform_stdev_check_and_update_concurrency: concurrency active 0, tx 0, rx 0, concurrency session_allowed 1
11-28 17:46:44.439   513  2995 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
11-28 17:46:44.444  3966  4234 I MicroRecognitionRnrImpl: Stopping hotword detection.
11-28 17:46:44.445  3966  4241 I MicroRecognitionRnrImpl: Detection finished
11-28 17:46:44.479  5606  5606 I CordovaLog: Changing log level to DEBUG(3)
11-28 17:46:44.479  5606  5606 I CordovaActivity: Apache Cordova native platform version 6.0.0 is starting
11-28 17:46:44.479  5606  5606 D CordovaActivity: CordovaActivity.onCreate()
11-28 17:46:44.484  5606  5606 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011750)
11-28 17:46:44.509  5606  5606 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
11-28 17:46:44.575  5606  5606 I LibraryLoader: Time to load native libraries: 62 ms (timestamps 5512-5574)
11-28 17:46:44.575  5606  5606 I LibraryLoader: Expected native library version number "",actual native library version number ""
,11-28 17:46:44.613  5606  5606 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {af85d53}
11-28 17:46:44.613  5606  5606 I LibraryLoader: Expected native library version number "",actual native library version number ""
,11-28 17:46:44.613  5606  5606 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,11-28 17:46:44.617  5606  5606 I BrowserStartupController: Initializing chromium process, singleProcess=true
,11-28 17:46:44.617  5606  5606 E SysUtils: ApplicationContext is null in ApplicationStatus
,11-28 17:46:44.664  5606  5606 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,11-28 17:46:44.672  5606  5606 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,11-28 17:46:44.672  5606  5606 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
11-28 17:46:44.672  5606  5606 I Adreno  : QUALCOMM build                   : 63c06b2, I8366cd0437
11-28 17:46:44.672  5606  5606 I Adreno  : Build Date                       : 12/06/15
11-28 17:46:44.672  5606  5606 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
11-28 17:46:44.672  5606  5606 I Adreno  : Local Branch                     : mybranch17112971
11-28 17:46:44.672  5606  5606 I Adreno  : Remote Branch                    : quic/LA.BF64.1.2.9_v2
11-28 17:46:44.672  5606  5606 I Adreno  : Remote Branch                    : NONE
11-28 17:46:44.672  5606  5606 I Adreno  : Reconstruct Branch               : NOTHING
,11-28 17:46:44.712   928   945 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@6ccad84:true
,11-28 17:46:44.735   766   766 W Binder_3: type=1400 audit(0.0:99): avc: denied { ioctl } for path="socket:[15202]" dev="sockfs" ino=15202 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-28 17:46:44.735   766   766 W Binder_3: type=1400 audit(0.0:100): avc: denied { ioctl } for path="socket:[15202]" dev="sockfs" ino=15202 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-28 17:46:44.750  5606  5606 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,11-28 17:46:44.758  5606  5606 D SystemWebViewEngine: CordovaWebView is running on device made by: Huawei
,11-28 17:46:44.761  5606  5606 D PluginManager: init()
,11-28 17:46:44.764  5606  5606 D CordovaWebViewImpl: >>> loadUrl(file:///android_asset/www/index.html)
,11-28 17:46:44.780  5606  5606 D CordovaActivity: Started the activity.
,11-28 17:46:44.780  5606  5606 D CordovaActivity: Resumed the activity.
,11-28 17:46:44.782   766   766 W Binder_3: type=1400 audit(0.0:101): avc: denied { ioctl } for path="socket:[32360]" dev="sockfs" ino=32360 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-28 17:46:44.782   766   766 W Binder_3: type=1400 audit(0.0:102): avc: denied { ioctl } for path="socket:[32360]" dev="sockfs" ino=32360 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
11-28 17:46:44.784  5606  5643 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,11-28 17:46:44.785  4209  4209 W Binder_C: type=1400 audit(0.0:103): avc: denied { ioctl } for path="socket:[26119]" dev="sockfs" ino=26119 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-28 17:46:44.785  4209  4209 W Binder_C: type=1400 audit(0.0:104): avc: denied { ioctl } for path="socket:[26119]" dev="sockfs" ino=26119 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
11-28 17:46:44.789  5606  5630 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,11-28 17:46:44.813  5606  5643 I OpenGLRenderer: Initialized EGL, version 1.4
,11-28 17:46:44.888  3147  3147 W Binder_3: type=1400 audit(0.0:105): avc: denied { ioctl } for path="socket:[28522]" dev="sockfs" ino=28522 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-28 17:46:44.888  3147  3147 W Binder_3: type=1400 audit(0.0:106): avc: denied { ioctl } for path="socket:[28522]" dev="sockfs" ino=28522 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-28 17:46:44.888   939   939 W Binder_2: type=1400 audit(0.0:107): avc: denied { ioctl } for path="socket:[28521]" dev="sockfs" ino=28521 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
11-28 17:46:44.888   939   939 W Binder_2: type=1400 audit(0.0:108): avc: denied { ioctl } for path="socket:[28521]" dev="sockfs" ino=28521 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-28 17:46:44.892   928   946 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +518ms
,11-28 17:46:44.899  3684  3684 I Keyboard.Facilitator: onFinishInput()
,11-28 17:46:44.908  5606  5606 D CordovaWebViewImpl: onPageDidNavigate(file:///android_asset/www/index.html)
,11-28 17:46:44.928  5606  5606 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 5606
,11-28 17:46:45.023  5606  5606 D JsMessageQueue: Set native->JS mode to EvalBridgeMode
,11-28 17:46:45.156  5606  5645 D jxcore_app_log: JniHelper::setJavaVM(0xf503c000), pthread_self() = -584845008
,11-28 17:46:45.161  5606  5645 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
11-28 17:46:45.161  5606  5645 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
11-28 17:46:45.161  5606  5645 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
11-28 17:46:45.161  5606  5645 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
11-28 17:46:45.161  5606  5645 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,11-28 17:46:45.161  5606  5645 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6a30d26 added. We now have 1 listener(s)
,11-28 17:46:45.163  5606  5645 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 60:83:34:25:D7:D4
,11-28 17:46:45.164  5606  5645 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
,11-28 17:46:45.165  5606  5645 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-28 17:46:45.165  5606  5645 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,11-28 17:46:45.168  5606  5645 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
11-28 17:46:45.168  5606  5645 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
11-28 17:46:45.168  5606  5645 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
11-28 17:46:45.168  5606  5645 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 60:83:34:25:D7:D4
11-28 17:46:45.168  5606  5645 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
11-28 17:46:45.168  5606  5645 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
11-28 17:46:45.168  5606  5645 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
11-28 17:46:45.168  5606  5645 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
11-28 17:46:45.168  5606  5645 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
11-28 17:46:45.168  5606  5645 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
11-28 17:46:45.168  5606  5645 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
11-28 17:46:45.168  5606  5645 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
11-28 17:46:45.168  5606  5645 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
11-28 17:46:45.168  5606  5645 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,11-28 17:46:45.168  5606  5645 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1825bbd added. We now have 1 listener(s)
11-28 17:46:45.168  5606  5645 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-28 17:46:45.172   928  2977 D WifiService: New client listening to asynchronous messages
,11-28 17:46:45.172  5606  5645 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
11-28 17:46:45.172  5606  5645 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
11-28 17:46:45.172  5606  5645 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[JavaBridge,5,main], id: 51
11-28 17:46:45.173  5606  5645 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
11-28 17:46:45.173  5606  5645 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
11-28 17:46:45.173  5606  5645 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
11-28 17:46:45.173  5606  5645 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[JavaBridge,5,main], id: 51
,11-28 17:46:45.174  5606  5645 I io.jxcore.node.LifeCycleMonitor: start: OK
,11-28 17:46:45.184  5606  5606 D CordovaWebViewImpl: onPageFinished(file:///android_asset/www/index.html)
,11-28 17:46:45.194  5606  5606 D SystemWebChromeClient: file:///android_asset/www/js/index.js: Line 36 : Uncaught TypeError: Cannot read property 'querySelector' of null
11-28 17:46:45.195  5606  5606 I chromium: [INFO:CONSOLE(36)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (36)
,11-28 17:46:45.275   928  2978 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,11-28 17:46:45.481  5606  5615 I art     : Background sticky concurrent mark sweep GC freed 86359(8MB) AllocSpace objects, 16(1476KB) LOS objects, 20% free, 26MB/32MB, paused 2.023ms total 107.867ms
,11-28 17:46:45.654  5606  5652 W jxcore-log: Initializing JXcore engine
11-28 17:46:45.654  5606  5652 W jxcore-log: JXcore engine is ready
,11-28 17:46:45.675  5652  5652 W Thread-57: type=1400 audit(0.0:109): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=12892 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,11-28 17:46:45.678  5652  5652 W Thread-57: type=1400 audit(0.0:110): avc: denied { ioctl } for path="socket:[16402]" dev="sockfs" ino=16402 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
11-28 17:46:45.678  5652  5652 W Thread-57: type=1400 audit(0.0:111): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=5964 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,11-28 17:46:45.678  5652  5652 W Thread-57: type=1400 audit(0.0:112): avc: denied { ioctl } for path="socket:[32331]" dev="sockfs" ino=32331 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:untrusted_app:s0:c512,c768 tclass=netlink_route_socket permissive=0
,11-28 17:46:45.691  5606  5652 W jxcore-log: Starting JXcore engine
,11-28 17:46:45.741  5606  5652 W jxcore-log: Platform android
11-28 17:46:45.741  5606  5652 W jxcore-log: 
,11-28 17:46:45.741  5606  5652 W jxcore-log: Process ARCH arm
11-28 17:46:45.741  5606  5652 W jxcore-log: 
,11-28 17:46:45.885  5606  5652 I jxcore-log: JXcore Cordova bridge is ready!
11-28 17:46:45.885  5606  5652 I jxcore-log: 
,11-28 17:46:45.885  5606  5652 W jxcore-log: JXcore engine is started
,11-28 17:46:45.893  5606  5645 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,11-28 17:46:45.897  5606  5606 D SystemWebChromeClient: file:///android_asset/www/js/thali_main.js: Line 41 : Application has the required permission.
,11-28 17:46:45.897  5606  5606 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,11-28 17:46:48.084  3584  3584 I ConfigService: onDestroy
,11-28 17:46:48.298   928  2978 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,11-28 17:46:49.239   928  2976 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-28 17:46:49.381   928   939 I ActivityManager: Killing 5157:com.google.android.youtube/u0a75 (adj 15): empty #17
,11-28 17:46:51.334   928  2978 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,11-28 17:46:52.779   544   544 I ServiceManager: Waiting for service AtCmdFwd...
,11-28 17:46:53.781   544   544 I ServiceManager: Waiting for service AtCmdFwd...
,11-28 17:46:54.364   928  2978 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,11-28 17:46:54.782   544   544 I ServiceManager: Waiting for service AtCmdFwd...
,11-28 17:46:55.576  5606  5652 I jxcore-log: 2016-11-28 16:46:55 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
11-28 17:46:55.576  5606  5652 I jxcore-log: 
,11-28 17:46:55.578  5606  5652 I jxcore-log: 2016-11-28 16:46:55 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
11-28 17:46:55.578  5606  5652 I jxcore-log: 
,11-28 17:46:55.583  5606  5652 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,11-28 17:46:55.583  5606  5652 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-28 17:46:55.583  5606  5652 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-28 17:46:55.583  5606  5652 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-28 17:46:55.583  5606  5652 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-28 17:46:55.583  5606  5652 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-28 17:46:55.583  5606  5652 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-28 17:46:55.583  5606  5652 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-28 17:46:55.583  5606  5652 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-28 17:46:55.583  5606  5652 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,11-28 17:46:55.585  5606  5652 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
,11-28 17:46:55.587  5606  5652 I jxcore-log: 2016-11-28 16:46:55 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
11-28 17:46:55.587  5606  5652 I jxcore-log: 
,11-28 17:46:55.588  5606  5652 I jxcore-log: 2016-11-28 16:46:55 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
11-28 17:46:55.588  5606  5652 I jxcore-log: 
,11-28 17:46:55.783   544   544 I ServiceManager: Waiting for service AtCmdFwd...
,11-28 17:46:55.839  5606  5652 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,11-28 17:46:55.839  5606  5652 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@364085f added. We now have 2 listener(s)
11-28 17:46:55.840  5606  5652 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-28 17:46:55.840  5606  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-28 17:46:55.840  5606  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-28 17:46:55.840  5606  5652 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,11-28 17:46:55.840  5606  5652 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@49eb2ac added. We now have 2 listener(s)
11-28 17:46:55.840  5606  5652 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-28 17:46:55.841  5606  5652 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
11-28 17:46:55.842  5606  5652 D ExecuteNativeTests: Running unit tests
11-28 17:46:55.842  5606  5652 D BluetoothAdapter: enable(): BT is already enabled..!
,11-28 17:46:55.843   928  3808 D WifiService: setWifiEnabled: true pid=5606, uid=10077
11-28 17:46:55.843   928  3808 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-28 17:46:56.785   544   544 I ServiceManager: Waiting for service AtCmdFwd...
,11-28 17:46:57.387   928  2978 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,11-28 17:46:57.523   928  2977 D WifiService: New client listening to asynchronous messages
,11-28 17:46:57.526  3966  5655 W CronetSyncConnectionRcs: Upload content type not set.
,11-28 17:46:57.600  4880  4944 D Finsky  : [188] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,11-28 17:46:57.601  4880  4880 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,11-28 17:46:57.604   928  3212 I ActivityManager: Killing 5246:org.codeaurora.ims/1001 (adj 15): empty #17
,11-28 17:46:57.785   544   544 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,11-28 17:47:03.476   928  2978 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,11-28 17:47:04.628   928  3833 I ActivityManager: Killing 5285:com.android.settings/1000 (adj 15): empty #17
,11-28 17:47:05.848  5606  5652 I com.test.thalitest.ThaliTestRunner: Running UT
,11-28 17:47:05.918  5606  5652 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-28 17:47:05.919  5606  5652 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@adcfe5e added. We now have 3 listener(s)
11-28 17:47:05.920  5606  5652 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
,11-28 17:47:05.920  5606  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-28 17:47:05.920  5606  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,11-28 17:47:05.920  5606  5652 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,11-28 17:47:05.920  5606  5652 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4d223f added. We now have 3 listener(s)
,11-28 17:47:05.920  5606  5652 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-28 17:47:05.921  5606  5652 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
11-28 17:47:05.926  5606  5652 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnConnectionTimeout
11-28 17:47:05.927  5606  5652 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
11-28 17:47:05.927  5606  5652 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-28 17:47:05.927  5606  5652 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-28 17:47:05.927  5606  5652 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,11-28 17:47:05.928  5606  5652 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
11-28 17:47:05.929  5606  5652 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
11-28 17:47:05.929  5606  5652 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
,11-28 17:47:05.929  5606  5652 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-28 17:47:05.929  5606  5652 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-28 17:47:05.929  5606  5652 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,11-28 17:47:05.930  5606  5652 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnBluetoothMacAddressResolved
11-28 17:47:05.931  5606  5652 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
11-28 17:47:05.933  5606  5652 I io.jxcore.node.ConnectionHelperTest: Starting test: testHasMaximumNumberOfConnections
,11-28 17:47:05.935  5606  5652 I io.jxcore.node.ConnectionHelperTest: Starting test: testStart
11-28 17:47:05.935  5606  5652 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
11-28 17:47:05.936  5606  5652 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,11-28 17:47:05.936  5606  5652 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
,11-28 17:47:05.953  5606  5652 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-28 17:47:05.953  5606  5652 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-28 17:47:05.953  5606  5652 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-28 17:47:05.953  5606  5652 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-28 17:47:05.953  5606  5652 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-28 17:47:05.953  5606  5652 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-28 17:47:05.953  5606  5652 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-28 17:47:05.953  5606  5652 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-28 17:47:05.953  5606  5652 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,11-28 17:47:05.955  5606  5652 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
,11-28 17:47:05.955  5606  5652 D io.jxcore.node.ConnectivityMonitor: start: OK
11-28 17:47:05.955  5606  5652 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 1
11-28 17:47:05.955  5606  5652 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 0 -> 1
,11-28 17:47:05.956  5606  5652 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-57,5,main], id: 57
11-28 17:47:05.956  5606  5652 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-57,5,main], id: 57
,11-28 17:47:05.956  5606  5652 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-57,5,main], id: 57
11-28 17:47:05.956  5606  5652 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,11-28 17:47:05.956  5606  5652 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
11-28 17:47:05.956  5606  5652 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
11-28 17:47:05.957  5606  5652 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,11-28 17:47:05.958  5606  5652 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
11-28 17:47:05.960  5606  5606 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-28 17:47:05.961  5606  5652 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
11-28 17:47:05.961  5606  5652 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
,11-28 17:47:05.961  5606  5652 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
11-28 17:47:05.962  5606  5652 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
11-28 17:47:05.962  5606  5652 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
,11-28 17:47:05.962  5606  5652 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-28 17:47:05.962  5606  5652 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
11-28 17:47:05.962  5606  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
,11-28 17:47:05.964  5606  5606 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-28 17:47:05.964  5606  5606 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
11-28 17:47:05.965  5606  5668 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-28 17:47:05.965  5606  5652 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
,11-28 17:47:05.966  5606  5652 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,11-28 17:47:05.966  5606  5652 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
11-28 17:47:05.969  5606  5668 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
11-28 17:47:05.965  4922  4922 W Binder_4: type=1400 audit(0.0:113): avc: denied { ioctl } for path="socket:[15229]" dev="sockfs" ino=15229 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-28 17:47:05.965  4922  4922 W Binder_4: type=1400 audit(0.0:114): avc: denied { ioctl } for path="socket:[15229]" dev="sockfs" ino=15229 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-28 17:47:05.969  5606  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-57,5,main], id: 57
11-28 17:47:05.969  5606  5652 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,11-28 17:47:05.970  5606  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-28 17:47:05.970  5606  5652 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-28 17:47:05.970  5606  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 1
,11-28 17:47:05.971  5606  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Current thread: Thread[Thread-57,5,main], id: 57
,11-28 17:47:05.971  5606  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-57,5,main], id: 57
11-28 17:47:05.971  5606  5652 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
11-28 17:47:05.971  5606  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: createAdvertiseDataToServiceData 
11-28 17:47:05.972  5606  5652 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-28 17:47:05.972  5606  5652 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 01 60 83 34 25 D7 D4
11-28 17:47:05.972  5606  5652 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-28 17:47:05.972  5606  5652 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: created AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-28 17:47:05.972  5606  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: Current thread: Thread[Thread-57,5,main], id: 57
11-28 17:47:05.972  5606  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: was started = false
,11-28 17:47:05.972  5606  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: advertiseData = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-28 17:47:05.972  5606  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData finished: Current thread: Thread[Thread-57,5,main], id: 57
11-28 17:47:05.972  5606  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = NOT_STARTEDCurrent thread: Thread[Thread-57,5,main], id: 57
11-28 17:47:05.973  5606  5652 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... adv data = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]Current thread: Thread[Thread-57,5,main], id: 57
11-28 17:47:05.973  5606  5652 D BluetoothAdapter: STATE_ON
,11-28 17:47:05.976  4664  4904 D BtGatt.GattService: registerClient() - UUID=e03d4210-826a-477b-a56d-16b6fe5e1ee7
,11-28 17:47:05.976  4664  4752 D BtGatt.GattService: onClientRegistered() - UUID=e03d4210-826a-477b-a56d-16b6fe5e1ee7, clientIf=5
11-28 17:47:05.977  5606  5617 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
11-28 17:47:05.979  4664  4754 D BtGatt.AdvertiseManager: message : 0
11-28 17:47:05.981  4664  4754 D BtGatt.AdvertiseManager: starting multi advertising
,11-28 17:47:05.995  4664  4752 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,11-28 17:47:06.002  4664  4752 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,11-28 17:47:06.003  5606  5652 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment Current thread: Thread[Thread-57,5,main], id: 57
11-28 17:47:06.003  5606  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTINGCurrent thread: Thread[Thread-57,5,main], id: 57
11-28 17:47:06.003  5606  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
11-28 17:47:06.003  5606  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged default (no call to listener). Current thread: Thread[Thread-57,5,main], id: 57
11-28 17:47:06.003  5606  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-57,5,main], id: 57
11-28 17:47:06.004  5606  5652 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[Thread-57,5,main], id: 57
11-28 17:47:06.004  5606  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[Thread-57,5,main], id: 57
11-28 17:47:06.004  5606  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser started = true Current thread: Thread[Thread-57,5,main], id: 57
11-28 17:47:06.004  5606  5652 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-28 17:47:06.004  5606  5652 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-28 17:47:06.004  5606  5652 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
11-28 17:47:06.005  5606  5652 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
11-28 17:47:06.005  5606  5652 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
11-28 17:47:06.005  5606  5652 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
11-28 17:47:06.005  5606  5652 I io.jxcore.node.ConnectionHelper: start: OK
11-28 17:47:06.006  5606  5606 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,11-28 17:47:06.006  5606  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess : Current thread: Thread[main,5,main], id: 1
,11-28 17:47:06.006  5606  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNINGCurrent thread: Thread[main,5,main], id: 1
11-28 17:47:06.006  5606  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
11-28 17:47:06.006  5606  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  true. Current thread: Thread[main,5,main], id: 1
11-28 17:47:06.007  5606  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[main,5,main], id: 1
11-28 17:47:06.007  5606  5606 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-28 17:47:06.007  5606  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-28 17:47:06.007  5606  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [ADVERTISING]
11-28 17:47:06.007  5606  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-28 17:47:06.007  5606  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-28 17:47:06.007  5606  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]Current thread: Thread[main,5,main], id: 1
11-28 17:47:06.008  5606  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-28 17:47:06.008  5606  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING] Current thread: Thread[main,5,main], id: 1
11-28 17:47:06.008  5606  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-28 17:47:06.010  5606  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-28 17:47:06.010  5606  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
,11-28 17:47:06.010  5606  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-28 17:47:06.011  5606  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-28 17:47:06.011  5606  5606 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,11-28 17:47:06.507  5606  5669 D io.jxcore.node.ConnectionHelperTest: Discovery manager is running
,11-28 17:47:06.509  5606  5652 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-28 17:47:06.509  5606  5652 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,11-28 17:47:06.510  5606  5652 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
,11-28 17:47:06.510  5606  5652 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
11-28 17:47:06.510  5606  5652 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
,11-28 17:47:06.510  5606  5652 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
11-28 17:47:06.510  5606  5652 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
,11-28 17:47:06.510  5606  5652 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
11-28 17:47:06.510  5606  5652 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
,11-28 17:47:06.510  5606  5652 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
11-28 17:47:06.510  5606  5652 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
,11-28 17:47:06.510  5606  5652 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
,11-28 17:47:06.510  5606  5652 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
11-28 17:47:06.511  5606  5652 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
11-28 17:47:06.511  5606  5652 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
11-28 17:47:06.511  5606  5652 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
,11-28 17:47:06.511  5606  5652 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
11-28 17:47:06.511  5606  5652 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
11-28 17:47:06.511  5606  5652 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
11-28 17:47:06.511  5606  5652 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
11-28 17:47:06.511  5606  5652 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
11-28 17:47:06.511  5606  5652 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
11-28 17:47:06.511  5606  5652 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
,11-28 17:47:06.511  5606  5652 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
11-28 17:47:06.512  5606  5652 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
11-28 17:47:06.512  5606  5652 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
11-28 17:47:06.512  5606  5652 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
11-28 17:47:06.512  5606  5652 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
11-28 17:47:06.512  5606  5652 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
11-28 17:47:06.512  5606  5652 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
,11-28 17:47:06.512  5606  5652 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
,11-28 17:47:06.512  5606  5606 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
11-28 17:47:06.512  5606  5652 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
11-28 17:47:06.512  5606  5652 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,11-28 17:47:06.513  5606  5652 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
11-28 17:47:06.513  5606  5652 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
11-28 17:47:06.513  5606  5652 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
11-28 17:47:06.513  5606  5652 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
11-28 17:47:06.513  5606  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
,11-28 17:47:06.513  5606  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-28 17:47:06.514  5606  5652 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
11-28 17:47:06.514  5606  5652 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
11-28 17:47:06.514  5606  5652 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,11-28 17:47:06.514  5606  5652 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-28 17:47:06.514  5606  5652 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-57,5,main], id: 57
11-28 17:47:06.514  5606  5652 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
11-28 17:47:06.514  5606  5668 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
11-28 17:47:06.514  5606  5652 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-28 17:47:06.515  5606  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
,11-28 17:47:06.515  5606  5668 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
11-28 17:47:06.515  5606  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-57,5,main], id: 57
11-28 17:47:06.515  5606  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-57,5,main], id: 57
11-28 17:47:06.515  5606  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-57,5,main], id: 57
11-28 17:47:06.516  5606  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-57,5,main], id: 57
11-28 17:47:06.517  5606  5652 D BluetoothAdapter: STATE_ON
11-28 17:47:06.517  5606  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-28 17:47:06.518  5606  5652 D BluetoothAdapter: STATE_ON
11-28 17:47:06.518  5606  5652 D BluetoothLeScanner: could not find callback wrapper
11-28 17:47:06.518  5606  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,11-28 17:47:06.519  5606  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-57,5,main], id: 57
11-28 17:47:06.519  5606  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-57,5,main], id: 57
11-28 17:47:06.519  5606  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-57,5,main], id: 57
11-28 17:47:06.519  5606  5652 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
11-28 17:47:06.519  5606  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-57,5,main], id: 57
11-28 17:47:06.520  4664  4754 D BtGatt.AdvertiseManager: message : 1
11-28 17:47:06.521  4664  4754 D BtGatt.AdvertiseManager: stop advertise for client 5
11-28 17:47:06.537  4664  4752 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
11-28 17:47:06.538  4664  4752 D BtGatt.GattService: Client app is not null!
11-28 17:47:06.539  4664  4681 D BtGatt.GattService: unregisterClient() - clientIf=5
11-28 17:47:06.542  5606  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-28 17:47:06.542  5606  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTEDCurrent thread: Thread[Thread-57,5,main], id: 57
11-28 17:47:06.542  5606  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
11-28 17:47:06.542  5606  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  false. Current thread: Thread[Thread-57,5,main], id: 57
11-28 17:47:06.542  5606  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-57,5,main], id: 57
11-28 17:47:06.543  5606  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-57,5,main], id: 57
11-28 17:47:06.543  5606  5652 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-28 17:47:06.543  5606  5652 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-28 17:47:06.544  5606  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-28 17:47:06.545  5606  5652 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
11-28 17:47:06.547  5606  5652 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
11-28 17:47:06.548  5606  5652 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-28 17:47:06.548  5606  5652 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
11-28 17:47:06.548  5606  5652 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
11-28 17:47:06.548  5606  5606 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-28 17:47:06.549  5606  5606 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
11-28 17:47:06.550  5606  5606 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
11-28 17:47:06.550  5606  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-28 17:47:06.550  5606  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-28 17:47:06.551  5606  5606 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
11-28 17:47:06.551  5606  5606 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-28 17:47:06.551  5606  5606 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-28 17:47:06.551  5606  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-28 17:47:06.551  5606  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-28 17:47:06.552  5606  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [ADVERTISING]
11-28 17:47:06.552  5606  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-28 17:47:06.552  5606  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-28 17:47:06.552  5606  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-28 17:47:06.552  5606  5606 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-28 17:47:06.552  5606  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED] Current thread: Thread[main,5,main], id: 1
11-28 17:47:06.552  5606  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-28 17:47:06.554  5606  5670 D io.jxcore.node.ConnectionHelperTest: Discovery manager is NOT running
11-28 17:47:06.554  5606  5652 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
11-28 17:47:06.554  5606  5652 V io.jxcore.node.ConnectivityMonitor: start: Already started
11-28 17:47:06.554  5606  5652 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 2
11-28 17:47:06.554  5606  5652 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 1 -> 2
11-28 17:47:06.555  5606  5652 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-57,5,main], id: 57
11-28 17:47:06.555  5606  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-28 17:47:06.555  5606  5652 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-57,5,main], id: 57
11-28 17:47:06.555  5606  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-28 17:47:06.555  5606  5652 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-57,5,main], id: 57
11-28 17:47:06.555  5606  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-28 17:47:06.555  5606  5652 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
11-28 17:47:06.555  5606  5652 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
11-28 17:47:06.555  5606  5652 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
11-28 17:47:06.555  5606  5652 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-28 17:47:06.558  4684  4684 W Binder_2: type=1400 audit(0.0:115): avc: denied { ioctl } for path="socket:[31349]" dev="sockfs" ino=31349 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-28 17:47:06.558  4684  4684 W Binder_2: type=1400 audit(0.0:116): avc: denied { ioctl } for path="socket:[31349]" dev="sockfs" ino=31349 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-28 17:47:06.556  5606  5652 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
11-28 17:47:06.557  5606  5652 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
11-28 17:47:06.557  5606  5652 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
11-28 17:47:06.557  5606  5652 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
11-28 17:47:06.557  5606  5652 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
11-28 17:47:06.558  5606  5606 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
11-28 17:47:06.558  5606  5652 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
11-28 17:47:06.558  5606  5671 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
11-28 17:47:06.558  5606  5652 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-28 17:47:06.558  5606  5652 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
11-28 17:47:06.558  5606  5671 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-28 17:47:06.564  5606  5671 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
11-28 17:47:06.566  5606  5652 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-28 17:47:06.566  5606  5652 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-28 17:47:06.566  5606  5652 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
11-28 17:47:06.570  5606  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-57,5,main], id: 57
11-28 17:47:06.570  5606  5652 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-28 17:47:06.571  5606  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-28 17:47:06.571  5606  5652 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-28 17:47:06.572  5606  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 2
11-28 17:47:06.574  5606  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Current thread: Thread[Thread-57,5,main], id: 57
11-28 17:47:06.574  5606  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-57,5,main], id: 57
11-28 17:47:06.574  5606  5652 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
11-28 17:47:06.574  5606  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: createAdvertiseDataToServiceData 
11-28 17:47:06.574  5606  5652 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-28 17:47:06.574  5606  5652 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 02 60 83 34 25 D7 D4
11-28 17:47:06.574  5606  5652 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[2, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-28 17:47:06.575  5606  5652 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: created AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[2, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-28 17:47:06.575  5606  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: Current thread: Thread[Thread-57,5,main], id: 57
11-28 17:47:06.575  5606  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: was started = false
11-28 17:47:06.575  5606  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: advertiseData = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[2, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-28 17:47:06.575  5606  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData finished: Current thread: Thread[Thread-57,5,main], id: 57
11-28 17:47:06.575  5606  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = NOT_STARTEDCurrent thread: Thread[Thread-57,5,main], id: 57
11-28 17:47:06.575  5606  5652 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... adv data = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[2, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]Current thread: Thread[Thread-57,5,main], id: 57
11-28 17:47:06.576  5606  5652 D BluetoothAdapter: STATE_ON
,11-28 17:47:06.579  4664  4684 D BtGatt.GattService: registerClient() - UUID=d3f6d462-3598-44dd-bc43-79a82557c56a
11-28 17:47:06.580  4664  4752 D BtGatt.GattService: onClientRegistered() - UUID=d3f6d462-3598-44dd-bc43-79a82557c56a, clientIf=5
11-28 17:47:06.580  5606  5616 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
11-28 17:47:06.581  4664  4754 D BtGatt.AdvertiseManager: message : 0
11-28 17:47:06.584  4664  4754 D BtGatt.AdvertiseManager: starting multi advertising
11-28 17:47:06.598  4664  4752 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
11-28 17:47:06.606  4664  4752 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
11-28 17:47:06.606  5606  5652 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment Current thread: Thread[Thread-57,5,main], id: 57
11-28 17:47:06.606  5606  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTINGCurrent thread: Thread[Thread-57,5,main], id: 57
11-28 17:47:06.607  5606  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
11-28 17:47:06.607  5606  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged default (no call to listener). Current thread: Thread[Thread-57,5,main], id: 57
11-28 17:47:06.607  5606  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-57,5,main], id: 57
11-28 17:47:06.607  5606  5652 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[Thread-57,5,main], id: 57
11-28 17:47:06.607  5606  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[Thread-57,5,main], id: 57
11-28 17:47:06.607  5606  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser started = true Current thread: Thread[Thread-57,5,main], id: 57
11-28 17:47:06.607  5606  5652 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-28 17:47:06.609  5606  5652 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-28 17:47:06.609  5606  5652 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
11-28 17:47:06.610  5606  5652 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
11-28 17:47:06.610  5606  5652 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
11-28 17:47:06.610  5606  5652 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
11-28 17:47:06.611  5606  5652 I io.jxcore.node.ConnectionHelper: start: OK
11-28 17:47:06.611  5606  5606 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
11-28 17:47:06.611  5606  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess : Current thread: Thread[main,5,main], id: 1
11-28 17:47:06.611  5606  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNINGCurrent thread: Thread[main,5,main], id: 1
11-28 17:47:06.611  5606  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
11-28 17:47:06.611  5606  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  true. Current thread: Thread[main,5,main], id: 1
11-28 17:47:06.611  5606  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[main,5,main], id: 1
11-28 17:47:06.611  5606  5606 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-28 17:47:06.612  5606  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-28 17:47:06.612  5606  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [ADVERTISING]
11-28 17:47:06.612  5606  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-28 17:47:06.612  5606  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-28 17:47:06.612  5606  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]Current thread: Thread[main,5,main], id: 1
11-28 17:47:06.612  5606  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-28 17:47:06.612  5606  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING] Current thread: Thread[main,5,main], id: 1
11-28 17:47:06.613  5606  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-28 17:47:06.617  5606  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-28 17:47:06.617  5606  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
11-28 17:47:06.617  5606  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-28 17:47:06.617  5606  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-28 17:47:06.617  5606  5606 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,11-28 17:47:07.112  5606  5672 D io.jxcore.node.ConnectionHelperTest: Discovery manager is running
,11-28 17:47:07.116  5606  5652 I io.jxcore.node.ConnectionHelperTest: Starting test: testStop
,11-28 17:47:07.116  5606  5652 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
11-28 17:47:07.116  5606  5652 V io.jxcore.node.ConnectivityMonitor: start: Already started
,11-28 17:47:07.116  5606  5652 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
11-28 17:47:07.116  5606  5652 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 3
11-28 17:47:07.116  5606  5652 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 2 -> 3
11-28 17:47:07.117  5606  5652 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-57,5,main], id: 57
11-28 17:47:07.117  5606  5652 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-57,5,main], id: 57
11-28 17:47:07.118  5606  5652 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-57,5,main], id: 57
,11-28 17:47:07.118  5606  5606 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
11-28 17:47:07.119  5606  5652 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
11-28 17:47:07.119  5606  5652 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Manufacturer ID: 7413
11-28 17:47:07.119  5606  5652 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad length and type: 533
11-28 17:47:07.119  5606  5652 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad extra information: 3
11-28 17:47:07.119  5606  5652 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
11-28 17:47:07.119  5606  5652 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 2
11-28 17:47:07.119  5606  5652 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 3
11-28 17:47:07.119  5606  5652 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 2
11-28 17:47:07.119  5606  5652 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
11-28 17:47:07.119  5606  5652 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Current thread: Thread[Thread-57,5,main], id: 57
,11-28 17:47:07.119  5606  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 3
,11-28 17:47:07.120  5606  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: advertiserWasStarted true Current thread: Thread[Thread-57,5,main], id: 57
11-28 17:47:07.121  5606  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: stop advertiser Current thread: Thread[Thread-57,5,main], id: 57
11-28 17:47:07.121  5606  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-57,5,main], id: 57
11-28 17:47:07.124  4664  4754 D BtGatt.AdvertiseManager: message : 1
11-28 17:47:07.127  4664  4754 D BtGatt.AdvertiseManager: stop advertise for client 5
,11-28 17:47:07.137  4664  4752 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
11-28 17:47:07.137  4664  4752 D BtGatt.GattService: Client app is not null!
,11-28 17:47:07.138  4664  4904 D BtGatt.GattService: unregisterClient() - clientIf=5
11-28 17:47:07.138  5606  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,11-28 17:47:07.139  5606  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTEDCurrent thread: Thread[Thread-57,5,main], id: 57
11-28 17:47:07.139  5606  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
11-28 17:47:07.139  5606  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-57,5,main], id: 57
,11-28 17:47:07.139  5606  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-57,5,main], id: 57
11-28 17:47:07.139  5606  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-57,5,main], id: 57
11-28 17:47:07.139  5606  5652 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,11-28 17:47:07.139  5606  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: start advertiser Current thread: Thread[Thread-57,5,main], id: 57
11-28 17:47:07.140  5606  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Current thread: Thread[Thread-57,5,main], id: 57
11-28 17:47:07.140  5606  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-57,5,main], id: 57
11-28 17:47:07.140  5606  5652 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
11-28 17:47:07.140  5606  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: createAdvertiseDataToServiceData 
11-28 17:47:07.140  5606  5652 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-28 17:47:07.140  5606  5652 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 03 60 83 34 25 D7 D4
11-28 17:47:07.141  5606  5652 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[3, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-28 17:47:07.141  5606  5652 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: created AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[3, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-28 17:47:07.141  5606  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: Current thread: Thread[Thread-57,5,main], id: 57
11-28 17:47:07.141  5606  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: was started = false
,11-28 17:47:07.141  5606  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: advertiseData = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[3, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-28 17:47:07.141  5606  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData finished: Current thread: Thread[Thread-57,5,main], id: 57
11-28 17:47:07.141  5606  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = NOT_STARTEDCurrent thread: Thread[Thread-57,5,main], id: 57
11-28 17:47:07.142  5606  5652 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... adv data = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[3, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]Current thread: Thread[Thread-57,5,main], id: 57
,11-28 17:47:07.143  5606  5652 D BluetoothAdapter: STATE_ON
,11-28 17:47:07.146  4664  4681 D BtGatt.GattService: registerClient() - UUID=33938cdf-7e81-412f-bab3-1b38cfd5a915
11-28 17:47:07.147  4664  4752 D BtGatt.GattService: onClientRegistered() - UUID=33938cdf-7e81-412f-bab3-1b38cfd5a915, clientIf=5
,11-28 17:47:07.147  5606  5617 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
11-28 17:47:07.148  4664  4754 D BtGatt.AdvertiseManager: message : 0
,11-28 17:47:07.152  4664  4754 D BtGatt.AdvertiseManager: starting multi advertising
,11-28 17:47:07.162  4664  4752 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,11-28 17:47:07.169  4664  4752 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,11-28 17:47:07.169  5606  5652 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment Current thread: Thread[Thread-57,5,main], id: 57
11-28 17:47:07.170  5606  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTINGCurrent thread: Thread[Thread-57,5,main], id: 57
11-28 17:47:07.170  5606  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
11-28 17:47:07.170  5606  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged default (no call to listener). Current thread: Thread[Thread-57,5,main], id: 57
11-28 17:47:07.170  5606  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-57,5,main], id: 57
11-28 17:47:07.170  5606  5652 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[Thread-57,5,main], id: 57
11-28 17:47:07.170  5606  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[Thread-57,5,main], id: 57
11-28 17:47:07.170  5606  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser started = true Current thread: Thread[Thread-57,5,main], id: 57
,11-28 17:47:07.170  5606  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: start advertiser started = true Current thread: Thread[Thread-57,5,main], id: 57
11-28 17:47:07.170  5606  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-28 17:47:07.170  5606  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: scannerWasStarted false Current thread: Thread[Thread-57,5,main], id: 57
11-28 17:47:07.170  5606  5652 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-28 17:47:07.170  5606  5652 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
11-28 17:47:07.171  5606  5652 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-28 17:47:07.171  5606  5652 I io.jxcore.node.ConnectionHelper: start: OK
11-28 17:47:07.171  5606  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess : Current thread: Thread[main,5,main], id: 1
,11-28 17:47:07.171  5606  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNINGCurrent thread: Thread[main,5,main], id: 1
11-28 17:47:07.171  5606  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
11-28 17:47:07.171  5606  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  true. Current thread: Thread[main,5,main], id: 1
11-28 17:47:07.171  5606  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[main,5,main], id: 1
11-28 17:47:07.171  5606  5606 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
,11-28 17:47:07.171  5606  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-28 17:47:07.171  5606  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [ADVERTISING]
11-28 17:47:07.171  5606  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [ADVERTISING]
11-28 17:47:07.172  5606  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
,11-28 17:47:07.172  5606  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-28 17:47:07.172  5606  5673 D io.jxcore.node.ConnectionHelperTest: Discovery manager is running
11-28 17:47:07.172  5606  5652 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-28 17:47:07.172  5606  5652 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
11-28 17:47:07.172  5606  5652 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,11-28 17:47:07.172  5606  5652 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
11-28 17:47:07.172  5606  5652 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
,11-28 17:47:07.172  5606  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
,11-28 17:47:07.172  5606  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-28 17:47:07.172  5606  5671 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
11-28 17:47:07.172  5606  5652 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
11-28 17:47:07.172  5606  5671 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
11-28 17:47:07.172  5606  5652 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
11-28 17:47:07.172  5606  5671 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
11-28 17:47:07.172  5606  5652 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
11-28 17:47:07.173  5606  5606 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
11-28 17:47:07.173  5606  5652 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-28 17:47:07.173  5606  5652 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-57,5,main], id: 57
11-28 17:47:07.173  5606  5652 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
11-28 17:47:07.173  5606  5652 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-28 17:47:07.173  5606  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-57,5,main], id: 57
11-28 17:47:07.173  5606  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-57,5,main], id: 57
11-28 17:47:07.173  5606  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-57,5,main], id: 57
11-28 17:47:07.173  5606  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-57,5,main], id: 57
11-28 17:47:07.174  5606  5652 D BluetoothAdapter: STATE_ON
11-28 17:47:07.174  5606  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-28 17:47:07.175  5606  5652 D BluetoothAdapter: STATE_ON
11-28 17:47:07.175  5606  5652 D BluetoothLeScanner: could not find callback wrapper
11-28 17:47:07.175  5606  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-28 17:47:07.175  5606  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-57,5,main], id: 57
11-28 17:47:07.175  5606  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-57,5,main], id: 57
11-28 17:47:07.175  5606  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-57,5,main], id: 57
11-28 17:47:07.175  5606  5652 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
11-28 17:47:07.175  5606  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-57,5,main], id: 57
11-28 17:47:07.176  4664  4754 D BtGatt.AdvertiseManager: message : 1
11-28 17:47:07.176  4664  4754 D BtGatt.AdvertiseManager: stop advertise for client 5
11-28 17:47:07.182  4664  4752 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
11-28 17:47:07.182  4664  4752 D BtGatt.GattService: Client app is not null!
11-28 17:47:07.183  4664  4922 D BtGatt.GattService: unregisterClient() - clientIf=5
11-28 17:47:07.184  5606  5652 D org.thaliproject.p2p.b,tconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,11-28 17:47:07.184  5606  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTEDCurrent thread: Thread[Thread-57,5,main], id: 57
11-28 17:47:07.184  5606  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
11-28 17:47:07.184  5606  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  false. Current thread: Thread[Thread-57,5,main], id: 57
11-28 17:47:07.184  5606  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-57,5,main], id: 57
11-28 17:47:07.184  5606  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-57,5,main], id: 57
11-28 17:47:07.184  5606  5652 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-28 17:47:07.184  5606  5652 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-28 17:47:07.185  5606  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,11-28 17:47:07.185  5606  5652 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
11-28 17:47:07.187  5606  5652 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
11-28 17:47:07.187  5606  5652 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-28 17:47:07.187  5606  5652 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
11-28 17:47:07.187  5606  5652 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
11-28 17:47:07.187  5606  5606 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-28 17:47:07.187  5606  5606 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
11-28 17:47:07.187  5606  5606 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
11-28 17:47:07.187  5606  5606 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-28 17:47:07.187  5606  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-28 17:47:07.188  5606  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-28 17:47:07.188  5606  5606 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-28 17:47:07.188  5606  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-28 17:47:07.188  5606  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-28 17:47:07.188  5606  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [ADVERTISING]
11-28 17:47:07.188  5606  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-28 17:47:07.188  5606  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-28 17:47:07.188  5606  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
,11-28 17:47:07.188  5606  5606 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-28 17:47:07.188  5606  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED] Current thread: Thread[main,5,main], id: 1
,11-28 17:47:07.188  5606  5674 D io.jxcore.node.ConnectionHelperTest: Discovery manager is NOT running
11-28 17:47:07.188  5606  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-28 17:47:07.190  5606  5652 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnPeerReadyToProvideBluetoothMacAddress
11-28 17:47:07.190  5606  5652 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
,11-28 17:47:07.191  5606  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
,11-28 17:47:07.192  5606  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-28 17:47:07.192  5606  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-28 17:47:07.193  5606  5652 I io.jxcore.node.ConnectionHelperTest: Starting test: testKillAllConnections
11-28 17:47:07.194  5606  5652 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
11-28 17:47:07.195  5606  5652 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnConnectionManagerStateChanged
11-28 17:47:07.195  5606  5652 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
11-28 17:47:07.195  5606  5652 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnPermissionCheckRequired
11-28 17:47:07.196  5606  5652 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
11-28 17:47:07.196  5606  5652 I io.jxcore.node.ConnectionHelperTest: Starting test: testToggleBetweenSystemDecidedAndAlternativeInsecureRfcommPortNumber
,11-28 17:47:07.196  5606  5652 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
11-28 17:47:07.196  5606  5652 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-28 17:47:07.196  5606  5652 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-28 17:47:07.196  5606  5652 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-28 17:47:07.196  5606  5652 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
11-28 17:47:07.196  5606  5652 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-28 17:47:07.196  5606  5652 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-28 17:47:07.197  5606  5652 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-28 17:47:07.197  5606  5652 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
11-28 17:47:07.197  5606  5652 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-28 17:47:07.197  5606  5652 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-28 17:47:07.197  5606  5652 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-28 17:47:07.197  5606  5652 I io.jxcore.node.ConnectionHelperTest: Starting test: testConnect
11-28 17:47:07.199  5606  5652 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
11-28 17:47:07.199  5606  5652 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
11-28 17:47:07.200  5606  5652 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
11-28 17:47:07.203  5606  5652 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
11-28 17:47:07.204  5606  5652 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
11-28 17:47:07.205  5606  5652 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
11-28 17:47:07.205  5606  5652 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
11-28 17:47:07.205  5606  5652 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
11-28 17:47:07.205  5606  5652 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
11-28 17:47:07.205  5606  5652 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
11-28 17:47:07.205  5606  5652 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
11-28 17:47:07.205  5606  5652 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
11-28 17:47:07.205  5606  5652 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
11-28 17:47:07.205  5606  5652 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
11-28 17:47:07.205  5606  5652 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
11-28 17:47:07.205  5606  5652 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
11-28 17:47:07.205  5606  5652 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
11-28 17:47:07.205  5606  5652 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
11-28 17:47:07.205  5606  5652 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
11-28 17:47:07.205  5606  5652 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
11-28 17:47:07.205  5606  5652 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
11-28 17:47:07.205  5606  5652 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
11-28 17:47:07.206  5606  5652 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
11-28 17:47:07.206  5606  5652 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
11-28 17:47:07.206  5606  5652 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
11-28 17:47:07.206  5606  5652 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
11-28 17:47:07.206  5606  5652 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
11-28 17:47:07.206  5606  5652 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
11-28 17:47:07.206  5606  5652 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
11-28 17:47:07.206  5606  5652 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
11-28 17:47:07.206  5606  5652 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
11-28 17:47:07.206  5606  5652 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
11-28 17:47:07.206  5606  5652 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
11-28 17:47:07.206  5606  5652 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
11-28 17:47:07.206  5606  5652 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
11-28 17:47:07.207  5606  5652 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
11-28 17:47:07.207  5606  5652 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
11-28 17:47:07.207  5606  5652 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
11-28 17:47:07.207  5606  5652 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
11-28 17:47:07.208  5606  5652 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
11-28 17:47:07.208  5606  5652 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
11-28 17:47:07.208  5606  5652 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
11-28 17:47:07.208  5606  5652 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
11-28 17:47:07.208  5606  5652 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
,11-28 17:47:07.213  5606  5652 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
,11-28 17:47:07.215  4922  4922 W Binder_4: type=1400 audit(0.0:117): avc: denied { ioctl } for path="socket:[32981]" dev="sockfs" ino=32981 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,11-28 17:47:07.215  4922  4922 W Binder_4: type=1400 audit(0.0:118): avc: denied { ioctl } for path="socket:[32981]" dev="sockfs" ino=32981 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,11-28 17:47:07.214  5606  5652 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port 1
11-28 17:47:07.215  5606  5652 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
11-28 17:47:07.215  5606  5652 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
11-28 17:47:07.215  5606  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
11-28 17:47:07.215  5606  5652 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
11-28 17:47:07.215  5606  5652 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
11-28 17:47:07.216  5606  5652 E io.jxcore.node.ConnectionHelper: connect: Callback is null
11-28 17:47:07.216  5606  5675 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 129)
11-28 17:47:07.216  5606  5675 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: tryToConnect:  socketConnectSucceeded = false, mIsShuttingDown = false
11-28 17:47:07.216  5606  5675 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: socket closed
11-28 17:47:07.216  5606  5675 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: given port
11-28 17:47:07.216  5606  5675 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils: createBluetoothSocketToServiceRecord: Socket created with channel/port 1
11-28 17:47:07.216  5606  5675 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: connecting
11-28 17:47:07.216  5606  5675 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-28 17:47:07.217  5606  5652 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnProvideBluetoothMacAddressRequest
11-28 17:47:07.217  5606  5652 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
11-28 17:47:07.218  5606  5652 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnDiscoveryManagerStateChanged
11-28 17:47:07.218  5606  5652 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
11-28 17:47:07.219  5606  5652 I io.jxcore.node.ConnectionHelperTest: Starting test: testDisconnectOutgoingConnection
11-28 17:47:07.219  5606  5652 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
11-28 17:47:07.219  5606  5652 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
11-28 17:47:07.219  5606  5652 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
11-28 17:47:07.219  5606  5652 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
11-28 17:47:07.219  5606  5652 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
,11-28 17:47:07.219  5606  5652 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
11-28 17:47:07.219  5606  5652 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
11-28 17:47:07.219  5606  5652 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
11-28 17:47:07.219  5606  5652 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
11-28 17:47:07.219  5606  5652 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
11-28 17:47:07.219  5606  5652 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
11-28 17:47:07.220  5606  5652 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
11-28 17:47:07.220  5606  5652 I io.jxcore.node.ConnectionHelperTest: Starting test: testDispose
11-28 17:47:07.220  5606  5652 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
11-28 17:47:07.220  5606  5652 V io.jxcore.node.ConnectivityMonitor: start: Already started
11-28 17:47:07.220  5606  5652 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 4
11-28 17:47:07.220  5606  5652 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 3 -> 4
11-28 17:47:07.221  5606  5652 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-57,5,main], id: 57
,11-28 17:47:07.221  5606  5652 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-57,5,main], id: 57
11-28 17:47:07.221  5606  5652 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-57,5,main], id: 57
11-28 17:47:07.222  5606  5652 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
11-28 17:47:07.222  5606  5652 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
11-28 17:47:07.222  5606  5652 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
11-28 17:47:07.222  5606  5652 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-28 17:47:07.223  5606  5652 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
11-28 17:47:07.223  5606  5652 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
11-28 17:47:07.223  5606  5652 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
11-28 17:47:07.223  5606  5652 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
11-28 17:47:07.223  5606  5652 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
11-28 17:47:07.224  5606  5606 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
11-28 17:47:07.224  5606  5652 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
,11-28 17:47:07.224  5606  5652 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-28 17:47:07.224  5606  5652 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
11-28 17:47:07.224  5606  5676 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
11-28 17:47:07.225  5606  5676 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-28 17:47:07.225  4681  4681 W Binder_1: type=1400 audit(0.0:119): avc: denied { ioctl } for path="socket:[32561]" dev="sockfs" ino=32561 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,11-28 17:47:07.225  4681  4681 W Binder_1: type=1400 audit(0.0:120): avc: denied { ioctl } for path="socket:[32561]" dev="sockfs" ino=32561 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-28 17:47:07.228  5606  5676 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,11-28 17:47:07.229  5606  5652 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
,11-28 17:47:07.229  5606  5652 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-28 17:47:07.229  5606  5652 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,11-28 17:47:07.233  5606  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-57,5,main], id: 57
,11-28 17:47:07.233  5606  5652 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-28 17:47:07.234  5606  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-28 17:47:07.234  5606  5652 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-28 17:47:07.234  5606  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 4
,11-28 17:47:07.236  5606  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Current thread: Thread[Thread-57,5,main], id: 57
,11-28 17:47:07.236  5606  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-57,5,main], id: 57
11-28 17:47:07.236  5606  5652 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
11-28 17:47:07.236  5606  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: createAdvertiseDataToServiceData 
11-28 17:47:07.236  5606  5652 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-28 17:47:07.236  5606  5652 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 04 60 83 34 25 D7 D4
11-28 17:47:07.236  5606  5652 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[4, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-28 17:47:07.236  5606  5652 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: created AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[4, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-28 17:47:07.236  5606  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: Current thread: Thread[Thread-57,5,main], id: 57
11-28 17:47:07.236  5606  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: was started = false
11-28 17:47:07.236  5606  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: advertiseData = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[4, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-28 17:47:07.236  5606  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData finished: Current thread: Thread[Thread-57,5,main], id: 57
,11-28 17:47:07.236  5606  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = NOT_STARTEDCurrent thread: Thread[Thread-57,5,main], id: 57
11-28 17:47:07.237  5606  5652 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... adv data = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[4, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]Current thread: Thread[Thread-57,5,main], id: 57
11-28 17:47:07.237  5606  5652 D BluetoothAdapter: STATE_ON
11-28 17:47:07.239  4664  4684 D BtGatt.GattService: registerClient() - UUID=74ad0e06-6dbf-4608-a686-827768d557eb
11-28 17:47:07.239  4664  4752 D BtGatt.GattService: onClientRegistered() - UUID=74ad0e06-6dbf-4608-a686-827768d557eb, clientIf=5
11-28 17:47:07.240  5606  5617 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
11-28 17:47:07.240  4664  4754 D BtGatt.AdvertiseManager: message : 0
,11-28 17:47:07.242  4664  4754 D BtGatt.AdvertiseManager: starting multi advertising
,11-28 17:47:07.252  4664  4752 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,11-28 17:47:07.257  4664  4752 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,11-28 17:47:07.257  5606  5652 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment Current thread: Thread[Thread-57,5,main], id: 57
11-28 17:47:07.257  5606  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTINGCurrent thread: Thread[Thread-57,5,main], id: 57
11-28 17:47:07.257  5606  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
11-28 17:47:07.257  5606  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged default (no call to listener). Current thread: Thread[Thread-57,5,main], id: 57
,11-28 17:47:07.257  5606  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-57,5,main], id: 57
11-28 17:47:07.258  5606  5652 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[Thread-57,5,main], id: 57
11-28 17:47:07.258  5606  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[Thread-57,5,main], id: 57
11-28 17:47:07.258  5606  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser started = true Current thread: Thread[Thread-57,5,main], id: 57
11-28 17:47:07.258  5606  5652 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-28 17:47:07.259  5606  5652 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-28 17:47:07.259  5606  5652 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
,11-28 17:47:07.260  5606  5652 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
11-28 17:47:07.260  5606  5652 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
11-28 17:47:07.260  5606  5652 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
11-28 17:47:07.260  5606  5652 I io.jxcore.node.ConnectionHelper: start: OK
11-28 17:47:07.260  5606  5606 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
11-28 17:47:07.260  5606  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess : Current thread: Thread[main,5,main], id: 1
,11-28 17:47:07.260  5606  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNINGCurrent thread: Thread[main,5,main], id: 1
11-28 17:47:07.261  5606  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
11-28 17:47:07.261  5606  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  true. Current thread: Thread[main,5,main], id: 1
11-28 17:47:07.261  5606  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[main,5,main], id: 1
11-28 17:47:07.261  5606  5606 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-28 17:47:07.261  5606  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
,11-28 17:47:07.261  5606  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [ADVERTISING]
11-28 17:47:07.261  5606  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-28 17:47:07.261  5606  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-28 17:47:07.261  5606  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]Current thread: Thread[main,5,main], id: 1
11-28 17:47:07.261  5606  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-28 17:47:07.261  5606  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING] Current thread: Thread[main,5,main], id: 1
,11-28 17:47:07.261  5606  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-28 17:47:07.263  5606  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-28 17:47:07.263  5606  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
11-28 17:47:07.263  5606  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-28 17:47:07.263  5606  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-28 17:47:07.263  5606  5606 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,11-28 17:47:07.761  5606  5669 D io.jxcore.node.ConnectionHelperTest: Discovery manager is running
,11-28 17:47:07.762  5606  5652 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,11-28 17:47:07.762  5606  5652 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
,11-28 17:47:07.762  5606  5652 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
11-28 17:47:07.762  5606  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
,11-28 17:47:07.763  5606  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-28 17:47:07.763  5606  5652 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
,11-28 17:47:07.763  5606  5652 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
11-28 17:47:07.763  5606  5676 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
,11-28 17:47:07.763  5606  5676 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
11-28 17:47:07.764  5606  5652 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-28 17:47:07.764  5606  5676 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
11-28 17:47:07.764  5606  5606 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
11-28 17:47:07.764  5606  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
11-28 17:47:07.764  5606  5606 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
11-28 17:47:07.765  5606  5606 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
11-28 17:47:07.765  5606  5606 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-28 17:47:07.767  5606  5652 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@adcfe5e removed from the list
,11-28 17:47:07.768  5606  5652 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-28 17:47:07.768  5606  5652 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,11-28 17:47:07.768  5606  5652 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-57,5,main], id: 57
11-28 17:47:07.768  5606  5652 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
,11-28 17:47:07.768  5606  5677 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 129
11-28 17:47:07.768  5606  5652 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,11-28 17:47:07.769  5606  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-57,5,main], id: 57
11-28 17:47:07.769  5606  5677 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close
,11-28 17:47:07.769  5606  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-57,5,main], id: 57
11-28 17:47:07.769  5606  5677 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Trying to close the Bluetooth socket... (thread ID: 129)
11-28 17:47:07.769  5606  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-57,5,main], id: 57
,11-28 17:47:07.769  5606  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-57,5,main], id: 57
11-28 17:47:07.770  5606  5675 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: connect, read failed, socket might closed or timeout, read ret: -1
11-28 17:47:07.770  5606  5675 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: socketConnectSucceeded false
,11-28 17:47:07.770  4664  4899 E bt_btif_sock_rfcomm: btsock_rfc_signaled socket signaled for read while disconnected, slot: 7, channel: 1
11-28 17:47:07.770  5606  5675 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 129)
11-28 17:47:07.770  5606  5677 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Bluetooth socket closed (thread ID: 129)
,11-28 17:47:07.773  5606  5652 D BluetoothAdapter: STATE_ON
11-28 17:47:07.773  5606  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-28 17:47:07.775  5606  5652 D BluetoothAdapter: STATE_ON
11-28 17:47:07.775  5606  5652 D BluetoothLeScanner: could not find callback wrapper
,11-28 17:47:07.775  5606  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-28 17:47:07.775  5606  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-57,5,main], id: 57
11-28 17:47:07.776  5606  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-57,5,main], id: 57
,11-28 17:47:07.776  5606  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-57,5,main], id: 57
11-28 17:47:07.776  5606  5652 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
11-28 17:47:07.776  5606  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-57,5,main], id: 57
11-28 17:47:07.778  4664  4754 D BtGatt.AdvertiseManager: message : 1
,11-28 17:47:07.779  4664  4754 D BtGatt.AdvertiseManager: stop advertise for client 5
,11-28 17:47:07.791  4664  4752 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
,11-28 17:47:07.791  4664  4752 D BtGatt.GattService: Client app is not null!
,11-28 17:47:07.792  4664  4904 D BtGatt.GattService: unregisterClient() - clientIf=5
,11-28 17:47:07.793  5606  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-28 17:47:07.793  5606  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTEDCurrent thread: Thread[Thread-57,5,main], id: 57
11-28 17:47:07.793  5606  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
11-28 17:47:07.793  5606  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  false. Current thread: Thread[Thread-57,5,main], id: 57
11-28 17:47:07.793  5606  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-57,5,main], id: 57
11-28 17:47:07.793  5606  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-57,5,main], id: 57
11-28 17:47:07.793  5606  5652 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-28 17:47:07.794  5606  5652 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-28 17:47:07.795  5606  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-28 17:47:07.795  5606  5652 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
11-28 17:47:07.798  5606  5652 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
11-28 17:47:07.798  5606  5652 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-28 17:47:07.798  5606  5652 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
11-28 17:47:07.798  5606  5652 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
11-28 17:47:07.798  5606  5652 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4d223f removed from the list
11-28 17:47:07.798  5606  5652 D io.jxcore.node.ConnectivityMonitor: stop
11-28 17:47:07.798  5606  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-28 17:47:07.798  5606  5652 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
11-28 17:47:07.799  5606  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-28 17:47:07.799  5606  5606 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-28 17:47:07.799  5606  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-28 17:47:07.799  5606  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-28 17:47:07.799  5606  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [ADVERTISING]
11-28 17:47:07.799  5606  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-28 17:47:07.799  5606  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
,11-28 17:47:07.800  5606  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-28 17:47:07.800  5606  5606 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-28 17:47:07.800  5606  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED] Current thread: Thread[main,5,main], id: 1
11-28 17:47:07.800  5606  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-28 17:47:07.802  5606  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-28 17:47:07.802  5606  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-28 17:47:07.802  5606  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
,11-28 17:47:08.300  5606  5606 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-28 17:47:12.345  4664  4872 W bt_sdp  : SDP - Rcvd conn cnf with error: 0x4  CID 0x40
11-28 17:47:12.345  4664  4872 E bt_btif_sock_rfcomm: find_rfc_slot_by_id unable to find RFCOMM slot id: 7
,11-28 17:47:12.801  5606  5670 D io.jxcore.node.ConnectionHelperTest: Discovery manager is NOT running
,11-28 17:47:12.804  5606  5652 I io.jxcore.node.ConnectionHelperTest: Starting test: testIsRunning
,11-28 17:47:12.806  5606  5652 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
,11-28 17:47:12.807  5606  5652 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-28 17:47:12.807  5606  5652 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
,11-28 17:47:12.814  5606  5652 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,11-28 17:47:12.815  5606  5652 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,11-28 17:47:12.815  5606  5652 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
,11-28 17:47:12.815  5606  5652 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
,11-28 17:47:12.816  5606  5652 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
,11-28 17:47:12.816  5606  5652 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,11-28 17:47:12.816  5606  5606 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
11-28 17:47:12.816  5606  5678 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
11-28 17:47:12.817  5606  5678 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-28 17:47:12.818  5606  5652 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnConnectionFailed
11-28 17:47:12.819  5606  5652 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
11-28 17:47:12.820  5606  5652 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
11-28 17:47:12.820  5606  5652 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
11-28 17:47:12.818  4904  4904 W Binder_3: type=1400 audit(0.0:121): avc: denied { ioctl } for path="socket:[31362]" dev="sockfs" ino=31362 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-28 17:47:12.818  4904  4904 W Binder_3: type=1400 audit(0.0:122): avc: denied { ioctl } for path="socket:[31362]" dev="sockfs" ino=31362 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-28 17:47:12.822  5606  5652 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-28 17:47:12.822  5606  5652 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-28 17:47:12.823  5606  5678 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
11-28 17:47:12.823  5606  5652 I io.jxcore.node.ConnectionHelperTest: Starting test: testGetConnectivityMonitorGetDiscoveryManagerGetConnectionModelGetBluetoothName
,11-28 17:47:12.835  5606  5652 I io.jxcore.node.ConnectionHelperTest: Starting test: testConstructor
,11-28 17:47:12.836  5606  5652 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-28 17:47:12.836  5606  5652 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
11-28 17:47:12.836  5606  5652 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
11-28 17:47:12.836  5606  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
,11-28 17:47:12.836  5606  5652 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
11-28 17:47:12.836  5606  5678 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
,11-28 17:47:12.836  5606  5678 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
11-28 17:47:12.836  5606  5678 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
11-28 17:47:12.837  5606  5606 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
11-28 17:47:12.837  5606  5652 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,11-28 17:47:12.837  5606  5652 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
11-28 17:47:12.838  5606  5652 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@adcfe5e not in the list
,11-28 17:47:12.838  5606  5606 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-28 17:47:12.838  5606  5652 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-28 17:47:12.838  5606  5652 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,11-28 17:47:12.838  5606  5606 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
,11-28 17:47:12.838  5606  5652 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-57,5,main], id: 57
11-28 17:47:12.838  5606  5652 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
,11-28 17:47:12.838  5606  5652 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-28 17:47:12.838  5606  5652 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
,11-28 17:47:12.840  5606  5652 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
,11-28 17:47:12.840  5606  5652 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,11-28 17:47:12.840  5606  5652 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
,11-28 17:47:12.841  5606  5652 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
11-28 17:47:12.841  5606  5652 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4d223f not in the list
,11-28 17:47:12.841  5606  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-28 17:47:12.841  5606  5652 D io.jxcore.node.ConnectivityMonitor: stop
11-28 17:47:12.841  5606  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-28 17:47:12.841  5606  5606 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-28 17:47:12.843  5606  5652 I io.jxcore.node.ConnectionModelTest: Starting test: testGetNumberOfCurrentOutgoingConnections
11-28 17:47:12.843  5606  5652 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
11-28 17:47:12.843  5606  5652 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
,11-28 17:47:12.843  5606  5652 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
11-28 17:47:12.843  5606  5652 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
11-28 17:47:12.844  5606  5652 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
11-28 17:47:12.844  5606  5652 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
11-28 17:47:12.845  5606  5652 I io.jxcore.node.ConnectionModelTest: Starting test: constructorTest
11-28 17:47:12.846  5606  5652 I io.jxcore.node.ConnectionModelTest: Starting test: testHasIncomingConnection
11-28 17:47:12.848  5606  5652 I io.jxcore.node.ConnectionModelTest: Starting test: testGetNumberOfCurrentConnections
,11-28 17:47:12.848  5606  5652 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
11-28 17:47:12.848  5606  5652 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
11-28 17:47:12.849  5606  5652 I io.jxcore.node.ConnectionModelTest: Starting test: testGetNumberOfCurrentIncomingConnections
11-28 17:47:12.849  5606  5652 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
11-28 17:47:12.849  5606  5652 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
11-28 17:47:12.850  5606  5652 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
,11-28 17:47:12.850  5606  5652 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
11-28 17:47:12.850  5606  5652 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
11-28 17:47:12.850  5606  5652 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
11-28 17:47:12.852  5606  5652 I io.jxcore.node.ConnectionModelTest: Starting test: testGetOutgoingConnectionCallbackByBluetoothMacAddress
11-28 17:47:12.852  5606  5652 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
11-28 17:47:12.852  5606  5652 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
,11-28 17:47:12.853  5606  5652 I io.jxcore.node.ConnectionModelTest: Starting test: testHasConnection
11-28 17:47:12.853  5606  5652 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
11-28 17:47:12.853  5606  5652 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
11-28 17:47:12.853  5606  5652 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
11-28 17:47:12.853  5606  5652 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
,11-28 17:47:12.854  5606  5652 I io.jxcore.node.ConnectionModelTest: Starting test: testHasOutgoingConnection
,11-28 17:47:12.855  5606  5652 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-28 17:47:12.855  5606  5652 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a8bb0c5 added. We now have 3 listener(s)
11-28 17:47:12.857  5606  5652 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
,11-28 17:47:12.857  5606  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-28 17:47:12.857  5606  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-28 17:47:12.857  5606  5652 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-28 17:47:12.858  5606  5652 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ab47a1a added. We now have 3 listener(s)
,11-28 17:47:12.858  5606  5652 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-28 17:47:12.858  5606  5652 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
11-28 17:47:12.860  5606  5652 D BluetoothAdapter: enable(): BT is already enabled..!
,11-28 17:47:12.861   928  4209 D WifiService: setWifiEnabled: true pid=5606, uid=10077
11-28 17:47:12.861   928  4209 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
11-28 17:47:12.863  5606  5652 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testIsBleMultipleAdvertisementSupported
,11-28 17:47:12.866  5606  5652 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testIsBluetoothSupported
,11-28 17:47:12.867  5606  5652 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testIsWifiDirectSupported
11-28 17:47:12.868  5606  5652 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testIsBluetoothEnabled
,11-28 17:47:12.874  4664  4747 D BluetoothAdapterState: Current state: ON, message: 23
11-28 17:47:12.874  4664  4747 D BluetoothAdapterProperties: Setting state to 13
11-28 17:47:12.874  4664  4747 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
11-28 17:47:12.875  4664  4747 D BluetoothAdapterProperties: onBluetoothDisable()
11-28 17:47:12.875  5606  5652 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-28 17:47:12.875  5606  5652 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-28 17:47:12.875  5606  5652 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-28 17:47:12.875  5606  5652 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-28 17:47:12.875  5606  5652 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-28 17:47:12.875  5606  5652 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-28 17:47:12.875  5606  5652 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-28 17:47:12.875  5606  5652 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-28 17:47:12.875  5606  5652 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-28 17:47:12.875  5606  5652 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
11-28 17:47:12.876  4664  4747 I BluetoothAdapterState: Entering PendingCommandState
11-28 17:47:12.876  5606  5652 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-28 17:47:12.876  5606  5652 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
,11-28 17:47:12.879  4664  4664 D BluetoothMapService: onReceive
,11-28 17:47:12.879  4664  4664 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
11-28 17:47:12.879  4664  4664 D BluetoothMapService: STATE_TURNING_OFF
11-28 17:47:12.879  4664  4664 D BluetoothMapService: MAP Service closeService in
,11-28 17:47:12.879  4664  4664 D BluetoothMapMasInstance0: MAP Service shutdown
,11-28 17:47:12.879  4664  4664 D ObexServerSockets0: shutdown(block = true)
11-28 17:47:12.880  4664  4664 D ObexServerSockets0: shutdown called from another thread - interrupt().
11-28 17:47:12.880  4664  4664 D ObexServerSockets0: shutdown called from another thread - interrupt().
11-28 17:47:12.880  4664  4924 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 5
11-28 17:47:12.880  4664  4899 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
11-28 17:47:12.880  4664  4925 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
11-28 17:47:12.883  4664  4664 I BtOppRfcommListener: stopping Accept Thread
11-28 17:47:12.883  4664  5307 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
11-28 17:47:12.883  4664  5307 I BtOppRfcommListener: BluetoothSocket listen thread finished
,11-28 17:47:12.895   928   941 I ActivityManager: Start proc 5681:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
,11-28 17:47:12.896  4664  4752 D BluetoothAdapterProperties: Scan Mode:20
,11-28 17:47:12.898  4664  4747 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
11-28 17:47:12.900  4664  4664 D HeadsetService: Received stop request...Stopping profile...
11-28 17:47:12.902   928   928 D BluetoothHeadset: Proxy object disconnected
11-28 17:47:12.902   928   928 D BluetoothHeadset: Proxy object disconnected
11-28 17:47:12.902   928   928 D BluetoothHeadset: Proxy object disconnected
11-28 17:47:12.902  3127  3352 D BluetoothHeadset: Proxy object disconnected
11-28 17:47:12.903  3127  3127 D HeadsetProfile: Bluetooth service disconnected
11-28 17:47:12.903  3801  4012 D BluetoothHeadset: Proxy object disconnected
11-28 17:47:12.904  4664  4664 V BluetoothAdapterState: isTurningOff()=true
11-28 17:47:12.904  4664  4664 V BluetoothAdapterState: isTurningOn()=false
11-28 17:47:12.904  4664  4664 V BluetoothAdapterState: isBleTurningOn()=false
11-28 17:47:12.905  4664  4664 V BluetoothAdapterState: isBleTurningOff()=false
,11-28 17:47:12.907  4664  4664 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
11-28 17:47:12.907  4664  4664 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
11-28 17:47:12.907  4664  4752 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
11-28 17:47:12.907  4664  4872 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-28 17:47:12.907  4664  4872 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-28 17:47:12.908  4664  4872 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,11-28 17:47:12.908  4664  4752 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
,11-28 17:47:12.911  4664  4664 D A2dpService: Received stop request...Stopping profile...
,11-28 17:47:12.911  4664  4916 D A2dpStateMachine: Exit Disconnected: -1
,11-28 17:47:12.913  3127  3127 D BluetoothA2dp: Proxy object disconnected
,11-28 17:47:12.913   928   928 D BluetoothA2dp: Proxy object disconnected
11-28 17:47:12.914  4664  4664 D HidService: Received stop request...Stopping profile...
11-28 17:47:12.914  4664  4664 D HidService: Stopping Bluetooth HidService
11-28 17:47:12.915  3127  3127 D BluetoothInputDevice: Proxy object disconnected
11-28 17:47:12.916  3127  3127 D HidProfile: Bluetooth service disconnected
11-28 17:47:12.916  4664  4664 D HealthService: Received stop request...Stopping profile...
,11-28 17:47:12.918  4664  4664 D PanService: Received stop request...Stopping profile...
,11-28 17:47:12.919  3127  3127 D BluetoothPan: BluetoothPAN Proxy object disconnected
,11-28 17:47:12.919  3127  3127 D PanProfile: Bluetooth service disconnected
11-28 17:47:12.919  4664  4664 V BluetoothAdapterState: isTurningOff()=true
11-28 17:47:12.919  4664  4664 V BluetoothAdapterState: isTurningOn()=false
11-28 17:47:12.919  4664  4664 V BluetoothAdapterState: isBleTurningOn()=false
11-28 17:47:12.919  4664  4664 V BluetoothAdapterState: isBleTurningOff()=false
,11-28 17:47:12.921  4664  4872 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,11-28 17:47:12.921  4664  4872 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-28 17:47:12.921  4664  4664 D BluetoothMapService: Received stop request...Stopping profile...
11-28 17:47:12.921  4664  4664 D BluetoothMapService: stop()
11-28 17:47:12.921  4664  4872 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
11-28 17:47:12.922  4664  4872 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
11-28 17:47:12.922  4664  4872 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
11-28 17:47:12.922  4664  4872 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,11-28 17:47:12.922  4664  4752 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
11-28 17:47:12.922  4664  4664 D BluetoothMapAppObserver: deinitObservers()
,11-28 17:47:12.922  4664  4664 D BluetoothMapAppObserver: removeReceiver()
,11-28 17:47:12.925  4664  4664 V BluetoothAdapterState: isTurningOff()=true
11-28 17:47:12.925  3127  3127 D BluetoothMap: Proxy object disconnected
11-28 17:47:12.925  3127  3127 D MapProfile: Bluetooth service disconnected
11-28 17:47:12.925  4664  4664 V BluetoothAdapterState: isTurningOn()=false
,11-28 17:47:12.926  4664  4664 V BluetoothAdapterState: isBleTurningOn()=false
,11-28 17:47:12.926  4664  4664 V BluetoothAdapterState: isBleTurningOff()=false
11-28 17:47:12.926  4664  4664 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
,11-28 17:47:12.926  4664  4664 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
11-28 17:47:12.927  4664  4664 D SapService: Received stop request...Stopping profile...
11-28 17:47:12.927  4664  4664 V SapService: stop()
11-28 17:47:12.927  4664  4752 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
11-28 17:47:12.928  4664  4664 V BluetoothAdapterState: isTurningOff()=true
,11-28 17:47:12.928  4664  4664 V BluetoothAdapterState: isTurningOn()=false
11-28 17:47:12.928  4664  4664 V BluetoothAdapterState: isBleTurningOn()=false
11-28 17:47:12.928  4664  4664 V BluetoothAdapterState: isBleTurningOff()=false
11-28 17:47:12.928  4664  4664 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
11-28 17:47:12.928  4664  4752 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
11-28 17:47:12.928  4664  4664 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
11-28 17:47:12.929  4664  4664 V BluetoothAdapterState: isTurningOff()=true
11-28 17:47:12.929  4664  4664 V BluetoothAdapterState: isTurningOn()=false
11-28 17:47:12.929  4664  4664 V BluetoothAdapterState: isBleTurningOn()=false
11-28 17:47:12.929  4664  4664 V BluetoothAdapterState: isBleTurningOff()=false
,11-28 17:47:12.929  4664  4664 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
,11-28 17:47:12.929  4664  4664 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
11-28 17:47:12.931  4664  4664 D BluetoothMapService: MAP Service closeService in
11-28 17:47:12.931  4664  4664 V BluetoothAdapterState: isTurningOff()=true
11-28 17:47:12.931  4664  4664 V BluetoothAdapterState: isTurningOn()=false
11-28 17:47:12.931  4664  4664 V BluetoothAdapterState: isBleTurningOn()=false
11-28 17:47:12.931  4664  4664 V BluetoothAdapterState: isBleTurningOff()=false
11-28 17:47:12.932  4664  4664 D BluetoothMapService: cleanup()
11-28 17:47:12.932  4664  4664 D BluetoothMapService: MAP Service closeService in
11-28 17:47:12.932  4664  4664 V BluetoothAdapterState: isTurningOff()=true
11-28 17:47:12.932  4664  4664 V BluetoothAdapterState: isTurningOn()=false
11-28 17:47:12.932  4664  4664 V BluetoothAdapterState: isBleTurningOn()=false
11-28 17:47:12.932  4664  4664 V BluetoothAdapterState: isBleTurningOff()=false
11-28 17:47:12.933  4664  4747 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
11-28 17:47:12.933  4664  4747 D BluetoothAdapterProperties: Setting state to 15
11-28 17:47:12.933  4664  4747 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
11-28 17:47:12.933   928   945 D BluetoothHeadset: onBluetoothStateChange: up=false
,11-28 17:47:12.934  3801  3985 D BluetoothHeadset: onBluetoothStateChange: up=false
11-28 17:47:12.934  4664  4747 I BluetoothAdapterState: Entering BleOnState
11-28 17:47:12.934   928   945 D BluetoothHeadset: onBluetoothStateChange: up=false
,11-28 17:47:12.934  3127  3143 D BluetoothPan: onBluetoothStateChange on: false
,11-28 17:47:12.935   928   945 D BluetoothHeadset: onBluetoothStateChange: up=false
11-28 17:47:12.935  3127  3138 D BluetoothPbap: onBluetoothStateChange: up=false
11-28 17:47:12.936   928   945 D BluetoothA2dp: onBluetoothStateChange: up=false
11-28 17:47:12.936  3127  3352 D BluetoothMap: onBluetoothStateChange: up=false
11-28 17:47:12.937  3127  3143 D BluetoothHeadset: onBluetoothStateChange: up=false
11-28 17:47:12.937  3127  3138 D BluetoothInputDevice: onBluetoothStateChange: up=false
11-28 17:47:12.938  3127  3352 D BluetoothA2dp: onBluetoothStateChange: up=false
11-28 17:47:12.939  4664  4747 D BluetoothAdapterState: Current state: BLE ON, message: 20
11-28 17:47:12.939  4664  4747 D BluetoothAdapterProperties: Setting state to 16
,11-28 17:47:12.939  4664  4747 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
11-28 17:47:12.940  4664  4747 D BluetoothAdapterProperties: onBleDisable
11-28 17:47:12.940  4664  4747 I BluetoothAdapterState: Entering PendingCommandState
11-28 17:47:12.940  4664  4749 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
,11-28 17:47:12.942  4664  4752 D BluetoothAdapterProperties: Scan Mode:20
,11-28 17:47:12.942  4664  4872 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
,11-28 17:47:12.942  4664  4872 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-28 17:47:12.946  5681  5681 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm64
,11-28 17:47:12.960  5681  5681 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,11-28 17:47:12.965   928   945 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@69b020a:true
,11-28 17:47:12.966  3584  3584 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,11-28 17:47:12.983  5681  5681 D LocalBluetoothProfileManager: Adding local MAP profile
,11-28 17:47:12.985  5681  5681 D BluetoothMap: Create BluetoothMap proxy object
,11-28 17:47:12.991  5681  5681 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,11-28 17:47:12.998  5681  5681 D DockEventReceiver: finishStartingService: stopping service
,11-28 17:47:13.001  5681  5681 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,11-28 17:47:13.006  3584  3584 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,11-28 17:47:13.006  5681  5681 D DockEventReceiver: finishStartingService: stopping service
11-28 17:47:13.008   928  4207 I ActivityManager: Killing 5405:com.android.sdm.plugins.sprintdm/1001 (adj 15): empty #17
,11-28 17:47:13.154  4664  4752 I bt_hci  : shut_down
,11-28 17:47:13.160  4664  4756 D bt_hwcfg: hw_epilog_process
,11-28 17:47:13.160  4664  4756 I bt_vendor: low_power_mode_cb
,11-28 17:47:13.163  4664  4756 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
11-28 17:47:13.163  4664  4756 I bt_vendor: epilog_cb
11-28 17:47:13.163  4664  4756 I bt_hci  : epilog_finished_callback
,11-28 17:47:13.166  4664  4752 I bt_hci_h4: hal_close
,11-28 17:47:13.167  4664  4752 I bt_userial_vendor: device fd = 54 close
,11-28 17:47:13.279  4664  4749 D bt_stack_manager: event_shut_down_stack finished.
,11-28 17:47:13.279  4664  4747 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,11-28 17:47:13.282  4664  4747 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
11-28 17:47:13.282  4664  4664 D BtGatt.DebugUtils: handleDebugAction() action=null
,11-28 17:47:13.283  4664  4664 D BtGatt.GattService: Received stop request...Stopping profile...
,11-28 17:47:13.283  4664  4664 D BtGatt.GattService: stop()
11-28 17:47:13.283  4664  4664 D BtGatt.AdvertiseManager: advertise clients cleared
,11-28 17:47:13.285  4664  4664 V BluetoothAdapterState: isTurningOff()=false
,11-28 17:47:13.285  4664  4664 V BluetoothAdapterState: isTurningOn()=false
11-28 17:47:13.285  4664  4664 V BluetoothAdapterState: isBleTurningOn()=false
11-28 17:47:13.286  4664  4664 V BluetoothAdapterState: isBleTurningOff()=true
11-28 17:47:13.286  4664  4747 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
11-28 17:47:13.286  4664  4747 D BluetoothAdapterProperties: Setting state to 10
11-28 17:47:13.286  4664  4747 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
,11-28 17:47:13.287  4664  4747 I BluetoothAdapterState: Entering OffState
,11-28 17:47:13.288   928   945 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,11-28 17:47:13.296  4664  4664 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,11-28 17:47:13.296  4664  4664 W BluetoothSdpJni: Cleaning up Bluetooth Health object
11-28 17:47:13.296  4664  4664 I BluetoothServiceJni: cleanupNative: return from cleanup
,11-28 17:47:13.297  4664  4749 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,11-28 17:47:13.301  4664  4664 I art     : System.exit called, status: 0
,11-28 17:47:13.302  4664  4664 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,11-28 17:47:13.325   928  3823 I ActivityManager: Process com.android.bluetooth (pid 4664) has died
,11-28 17:47:13.342  5606  5606 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-28 17:47:13.378  5606  5679 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,11-28 17:47:13.378  5606  5679 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-28 17:47:13.378  5606  5679 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-28 17:47:13.378  5606  5679 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-28 17:47:13.378  5606  5679 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-28 17:47:13.378  5606  5679 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-28 17:47:13.378  5606  5679 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-28 17:47:13.378  5606  5679 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-28 17:47:13.378  5606  5679 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-28 17:47:13.378  5606  5679 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
11-28 17:47:13.378  5606  5679 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-28 17:47:13.378  5606  5679 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
,11-28 17:47:13.382  5606  5652 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-28 17:47:13.397   928   945 I ActivityManager: Start proc 5698:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,11-28 17:47:13.456  5698  5698 D AdapterServiceConfig: Adding HeadsetService
,11-28 17:47:13.457  5698  5698 D AdapterServiceConfig: Adding A2dpService
11-28 17:47:13.457  5698  5698 D AdapterServiceConfig: Adding HidService
11-28 17:47:13.457  5698  5698 D AdapterServiceConfig: Adding HealthService
11-28 17:47:13.457  5698  5698 D AdapterServiceConfig: Adding PanService
,11-28 17:47:13.457  5698  5698 D AdapterServiceConfig: Adding GattService
11-28 17:47:13.457  5698  5698 D AdapterServiceConfig: Adding BluetoothMapService
11-28 17:47:13.457  5698  5698 D AdapterServiceConfig: Adding SapService
,11-28 17:47:13.469   928   945 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@88f0074:true
,11-28 17:47:13.470  5698  5698 D BluetoothAdapterState: make() - Creating AdapterState
,11-28 17:47:13.473  5698  5698 I bt_bluedroid: init
,11-28 17:47:13.473  5698  5710 I BluetoothAdapterState: Entering OffState
,11-28 17:47:13.475  5698  5711 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
11-28 17:47:13.475  5698  5711 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
11-28 17:47:13.475  5698  5711 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
11-28 17:47:13.475  5698  5711 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
11-28 17:47:13.475  5698  5698 I bt_bluedroid: get_profile_interface socket
,11-28 17:47:13.477  5698  5714 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:D4
,11-28 17:47:13.477  5698  5698 I bt_bluedroid: get_profile_interface sdp
11-28 17:47:13.478  5698  5714 D BluetoothAdapterProperties: Name is: Nexus 6P
,11-28 17:47:13.482  5698  5709 I bt_bluedroid: config_hci_snoop_log
11-28 17:47:13.483   928   945 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,11-28 17:47:13.487  5698  5710 D BluetoothAdapterState: Current state: OFF, message: 0
11-28 17:47:13.487  5698  5710 D BluetoothAdapterProperties: Setting state to 14
11-28 17:47:13.487  5698  5710 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,11-28 17:47:13.488  5698  5710 D BluetoothBondStateMachine: make
,11-28 17:47:13.490  5698  5715 I BluetoothBondStateMachine: StableState(): Entering Off State
,11-28 17:47:13.492  5698  5710 I BluetoothAdapterState: Entering PendingCommandState
,11-28 17:47:13.493  5698  5698 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,11-28 17:47:13.495  5698  5698 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ef81e9a
11-28 17:47:13.495  5698  5698 D BtGatt.DebugUtils: handleDebugAction() action=null
11-28 17:47:13.496  5698  5698 D BtGatt.GattService: Received start request. Starting profile...
11-28 17:47:13.496  5698  5698 D BtGatt.GattService: start()
11-28 17:47:13.496  5698  5698 I bt_bluedroid: get_profile_interface gatt
,11-28 17:47:13.497  5698  5698 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ef81e9a
11-28 17:47:13.497  5698  5698 D BtGatt.AdvertiseManager: advertise manager created
,11-28 17:47:13.501  5698  5698 V BluetoothAdapterState: isTurningOff()=false
11-28 17:47:13.501  5698  5698 V BluetoothAdapterState: isTurningOn()=false
11-28 17:47:13.501  5698  5698 V BluetoothAdapterState: isBleTurningOn()=true
11-28 17:47:13.501  5698  5698 V BluetoothAdapterState: isBleTurningOff()=false
11-28 17:47:13.502  5698  5710 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,11-28 17:47:13.502  5698  5710 I bt_bluedroid: bt_bluedroid
,11-28 17:47:13.503  5698  5711 D bt_stack_manager: event_start_up_stack is bringing up the stack.
11-28 17:47:13.503  5698  5711 I bt_hci  : start_up
,11-28 17:47:13.508  5698  5711 I bt_vendor: alloc value 0xf3cf7871
,11-28 17:47:13.508  5698  5711 I bt_vendor: init
11-28 17:47:13.508  5698  5711 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
11-28 17:47:13.508  5698  5711 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,11-28 17:47:13.618  5698  5711 D bt_hci  : start_up starting async portion
,11-28 17:47:13.618  5698  5718 I bt_hci  : event_finish_startup
,11-28 17:47:13.619  5698  5718 I bt_hci_h4: hal_open
,11-28 17:47:13.619  5698  5718 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
11-28 17:47:13.615  5719  5719 W irq/448-msm_hs_: type=1400 audit(0.0:123): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-28 17:47:13.622  5698  5718 I bt_userial_vendor: device fd = 54 open
,11-28 17:47:13.637  5698  5718 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,11-28 17:47:13.640  5698  5718 D bt_hwcfg: Chipset BCM4358A3
,11-28 17:47:13.640  5698  5718 D bt_hwcfg: Target name = [BCM4358A3]
11-28 17:47:13.640  5698  5718 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,11-28 17:47:13.887  5698  5710 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 0
,11-28 17:47:14.023  5698  5718 I bt_hwcfg: bt vendor lib: set UART baud 115200
,11-28 17:47:14.024  5698  5718 D bt_hwcfg: Settlement delay -- 100 ms
11-28 17:47:14.024  5698  5718 I bt_hwcfg: Setting fw settlement delay to 100 
,11-28 17:47:14.149  5698  5718 I bt_hwcfg: bt vendor lib: set UART baud 3000000
11-28 17:47:14.149  5698  5718 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:D4
11-28 17:47:14.151  5698  5718 I bt_hwcfg: vendor lib fwcfg completed
11-28 17:47:14.151  5698  5718 I bt_vendor: firmware callback
11-28 17:47:14.151  5698  5718 I bt_hci  : firmware_config_callback
,11-28 17:47:14.160  5698  5721 I bt_btu  : btu_task pending for preload complete event
,11-28 17:47:14.160  5698  5721 I bt_btu_task: Bluetooth chip preload is complete
11-28 17:47:14.160  5698  5721 I bt_btu  : btu_task received preload complete event
,11-28 17:47:14.169  5698  5721 I         : BTE_InitTraceLevels -- TRC_HCI
,11-28 17:47:14.169  5698  5721 I         : BTE_InitTraceLevels -- TRC_L2CAP
11-28 17:47:14.169  5698  5721 I         : BTE_InitTraceLevels -- TRC_RFCOMM
11-28 17:47:14.170  5698  5721 I         : BTE_InitTraceLevels -- TRC_AVDT
11-28 17:47:14.170  5698  5721 I         : BTE_InitTraceLevels -- TRC_AVRC
11-28 17:47:14.170  5698  5721 I         : BTE_InitTraceLevels -- TRC_A2D
,11-28 17:47:14.170  5698  5721 I         : BTE_InitTraceLevels -- TRC_BNEP
11-28 17:47:14.170  5698  5721 I         : BTE_InitTraceLevels -- TRC_BTM
11-28 17:47:14.170  5698  5721 I         : BTE_InitTraceLevels -- TRC_GAP
,11-28 17:47:14.170  5698  5721 I         : BTE_InitTraceLevels -- TRC_PAN
11-28 17:47:14.171  5698  5721 I         : BTE_InitTraceLevels -- TRC_SDP
11-28 17:47:14.171  5698  5721 I         : BTE_InitTraceLevels -- TRC_GATT
11-28 17:47:14.171  5698  5721 I         : BTE_InitTraceLevels -- TRC_SMP
11-28 17:47:14.171  5698  5721 I         : BTE_InitTraceLevels -- TRC_BTAPP
11-28 17:47:14.171  5698  5721 I         : BTE_InitTraceLevels -- TRC_BTIF
,11-28 17:47:14.247  5698  5721 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf3c75549
11-28 17:47:14.247  5698  5721 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf3c75549 
,11-28 17:47:14.253  5698  5714 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,11-28 17:47:14.255  5698  5714 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,11-28 17:47:14.255  5698  5714 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:D4
,11-28 17:47:14.257  5698  5714 D BluetoothAdapterProperties: Name is: Nexus 6P
,11-28 17:47:14.258  5698  5714 D BluetoothAdapterProperties: Scan Mode:20
,11-28 17:47:14.258  5698  5714 D BluetoothAdapterProperties: Discoverable Timeout:120
11-28 17:47:14.259  5698  5714 D bt_hci  : do_postload posting postload work item
11-28 17:47:14.259  5698  5718 I bt_hci  : event_postload
11-28 17:47:14.259  5698  5718 I bt_vendor: sco_config_cb
11-28 17:47:14.259  5698  5718 I bt_hci  : sco_config_callback postload finished.
11-28 17:47:14.260  5698  5714 D bt_bte_conf: Device ID record 1 : primary
11-28 17:47:14.260  5698  5714 D bt_bte_conf:   vendorId            = 000f
11-28 17:47:14.260  5698  5714 D bt_bte_conf:   vendorIdSource      = 0001
11-28 17:47:14.260  5698  5714 D bt_bte_conf:   product             = 1200
11-28 17:47:14.260  5698  5714 D bt_bte_conf:   version             = 1436
11-28 17:47:14.261  5698  5714 D bt_bte_conf:   clientExecutableURL = 
11-28 17:47:14.261  5698  5714 D bt_bte_conf:   serviceDescription  = 
11-28 17:47:14.261  5698  5714 D bt_bte_conf:   documentationURL    = 
11-28 17:47:14.261  5698  5714 D bt_bte_conf: bte_load_did_conf no section named DID2.
11-28 17:47:14.261  5698  5711 D bt_stack_manager: event_start_up_stack finished
11-28 17:47:14.261  5698  5710 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
11-28 17:47:14.261  5698  5710 D BluetoothAdapterProperties: Setting state to 15
11-28 17:47:14.262  5698  5710 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
11-28 17:47:14.262  5698  5710 I BluetoothAdapterState: Entering BleOnState
11-28 17:47:14.266  5698  5710 D BluetoothAdapterState: Current state: BLE ON, message: 1
11-28 17:47:14.266  5698  5710 D BluetoothAdapterProperties: Setting state to 11
,11-28 17:47:14.266  5698  5710 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
11-28 17:47:14.266  5698  5718 I bt_vendor: low_power_mode_cb
,11-28 17:47:14.275  5698  5698 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ef81e9a
11-28 17:47:14.279  5698  5698 D HeadsetService: Received start request. Starting profile...
,11-28 17:47:14.282  5698  5698 I BluetoothHeadsetServiceJni: classInitNative: succeeds
11-28 17:47:14.282  5698  5698 D HeadsetStateMachine: make
,11-28 17:47:14.293  5698  5710 I BluetoothAdapterState: Entering PendingCommandState
,11-28 17:47:14.295  5698  5698 D HeadsetStateMachine: max_hf_connections = 1
,11-28 17:47:14.296  5698  5698 I bt_bluedroid: get_profile_interface handsfree
11-28 17:47:14.296  5698  5714 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
11-28 17:47:14.296  5698  5714 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
,11-28 17:47:14.299  5698  5698 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ef81e9a
11-28 17:47:14.300  5698  5698 D A2dpService: Received start request. Starting profile...
11-28 17:47:14.301  5698  5698 I BluetoothAvrcpServiceJni: classInitNative: succeeds
11-28 17:47:14.301  5698  5698 I bt_bluedroid: get_profile_interface avrcp
11-28 17:47:14.302   928   937 I art     : Background partial concurrent mark sweep GC freed 40082(2MB) AllocSpace objects, 11(276KB) LOS objects, 33% free, 28MB/43MB, paused 1.921ms total 135.373ms
,11-28 17:47:14.308  5698  5698 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,11-28 17:47:14.308  5698  5698 I BluetoothA2dpServiceJni: classInitNative: succeeds
11-28 17:47:14.308  5698  5698 D A2dpStateMachine: make
,11-28 17:47:14.309  5698  5698 I bt_bluedroid: get_profile_interface a2dp
11-28 17:47:14.311  5698  5714 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
11-28 17:47:14.312  5698  5729 D A2dpStateMachine: Enter Disconnected: -2
11-28 17:47:14.313  5698  5698 I BluetoothHidServiceJni: classInitNative: succeeds
11-28 17:47:14.314  5698  5698 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ef81e9a
11-28 17:47:14.314  3584  3584 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,11-28 17:47:14.316  5681  5681 D BluetoothInputDevice: Proxy object connected
,11-28 17:47:14.317  5681  5681 D HidProfile: Bluetooth service connected
11-28 17:47:14.318  5698  5698 D HidService: Received start request. Starting profile...
11-28 17:47:14.318  5698  5698 I bt_bluedroid: get_profile_interface hidhost
,11-28 17:47:14.318  5698  5698 D HidService: setHidService(): set to: null
,11-28 17:47:14.318  5698  5714 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf3c5656d
11-28 17:47:14.318  5698  5714 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
11-28 17:47:14.319  5698  5698 I BluetoothHealthServiceJni: classInitNative: succeeds
11-28 17:47:14.319  5698  5698 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ef81e9a
,11-28 17:47:14.320  5698  5698 D HealthService: Received start request. Starting profile...
,11-28 17:47:14.322  5698  5698 I bt_bluedroid: get_profile_interface health
,11-28 17:47:14.324  5698  5698 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,11-28 17:47:14.324  5698  5698 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ef81e9a
,11-28 17:47:14.326  5698  5698 D PanService: Received start request. Starting profile...
11-28 17:47:14.326  5698  5698 D BluetoothPanServiceJni: initializeNative(L110): pan
,11-28 17:47:14.326  5698  5698 I bt_bluedroid: get_profile_interface pan
11-28 17:47:14.326  5698  5714 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
11-28 17:47:14.329  5698  5698 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ef81e9a
11-28 17:47:14.330  5681  5681 D BluetoothPan: BluetoothPAN Proxy object connected
11-28 17:47:14.331  5698  5698 D BluetoothMapService: Received start request. Starting profile...
11-28 17:47:14.331  5698  5698 D BluetoothMapService: start()
11-28 17:47:14.331  5681  5681 D PanProfile: Bluetooth service connected
11-28 17:47:14.331  5681  5681 D BluetoothMap: Proxy object connected
11-28 17:47:14.331  5681  5681 D MapProfile: Bluetooth service connected
11-28 17:47:14.331  5681  5681 D BluetoothMap: getConnectedDevices()
,11-28 17:47:14.333  5698  5698 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
11-28 17:47:14.333  5698  5698 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
11-28 17:47:14.334  5698  5698 D BluetoothMapAppObserver: createReceiver()
11-28 17:47:14.336  5698  5698 D BluetoothMapAppObserver: initObservers()
11-28 17:47:14.336  5698  5698 D BluetoothMapAppObserver: getEnabledAccountItems()
11-28 17:47:14.341  5681  5681 D BluetoothMap: Bluetooth is Not enabled
11-28 17:47:14.342  5698  5698 V SapService: SapBinder()
11-28 17:47:14.342  5698  5698 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ef81e9a
,11-28 17:47:14.342  5698  5698 D SapService: Received start request. Starting profile...
11-28 17:47:14.342  5698  5698 V SapService: start()
,11-28 17:47:14.344  5698  5698 V BluetoothAdapterState: isTurningOff()=false
,11-28 17:47:14.344  5698  5698 V BluetoothAdapterState: isTurningOn()=true
11-28 17:47:14.344  5698  5698 V BluetoothAdapterState: isBleTurningOn()=false
11-28 17:47:14.344  5698  5698 V BluetoothAdapterState: isBleTurningOff()=false
11-28 17:47:14.344  5698  5698 V BluetoothAdapterState: isTurningOff()=false
11-28 17:47:14.344  5698  5698 V BluetoothAdapterState: isTurningOn()=true
11-28 17:47:14.344  5698  5698 V BluetoothAdapterState: isBleTurningOn()=false
11-28 17:47:14.345  5698  5698 V BluetoothAdapterState: isBleTurningOff()=false
11-28 17:47:14.345  5698  5727 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,11-28 17:47:14.345  5698  5698 V BluetoothAdapterState: isTurningOff()=false
11-28 17:47:14.345  5698  5698 V BluetoothAdapterState: isTurningOn()=true
11-28 17:47:14.345  5698  5698 V BluetoothAdapterState: isBleTurningOn()=false
11-28 17:47:14.345  5698  5698 V BluetoothAdapterState: isBleTurningOff()=false
11-28 17:47:14.345  5698  5698 V BluetoothAdapterState: isTurningOff()=false
,11-28 17:47:14.345  5698  5698 V BluetoothAdapterState: isTurningOn()=true
11-28 17:47:14.345  5698  5698 V BluetoothAdapterState: isBleTurningOn()=false
11-28 17:47:14.346  5698  5698 V BluetoothAdapterState: isBleTurningOff()=false
11-28 17:47:14.346  5698  5698 V BluetoothAdapterState: isTurningOff()=false
11-28 17:47:14.346  5698  5698 V BluetoothAdapterState: isTurningOn()=true
11-28 17:47:14.346  5698  5698 V BluetoothAdapterState: isBleTurningOn()=false
,11-28 17:47:14.346  5698  5698 V BluetoothAdapterState: isBleTurningOff()=false
11-28 17:47:14.346  5698  5698 V BluetoothAdapterState: isTurningOff()=false
11-28 17:47:14.346  5698  5698 V BluetoothAdapterState: isTurningOn()=true
11-28 17:47:14.346  5698  5698 V BluetoothAdapterState: isBleTurningOn()=false
11-28 17:47:14.346  5698  5698 V BluetoothAdapterState: isBleTurningOff()=false
11-28 17:47:14.347  5698  5698 V BluetoothAdapterState: isTurningOff()=false
11-28 17:47:14.347  5698  5698 V BluetoothAdapterState: isTurningOn()=true
,11-28 17:47:14.347  5698  5698 V BluetoothAdapterState: isBleTurningOn()=false
11-28 17:47:14.347  5698  5698 V BluetoothAdapterState: isBleTurningOff()=false
,11-28 17:47:14.347  5698  5710 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
11-28 17:47:14.347  5698  5710 D BluetoothAdapterProperties: ScanMode =  20
11-28 17:47:14.347  5698  5710 D BluetoothAdapterProperties: State =  11
11-28 17:47:14.348  5698  5714 D BluetoothAdapterProperties: Scan Mode:21
,11-28 17:47:14.348  5698  5710 D BluetoothAdapterProperties: Setting state to 12
11-28 17:47:14.348  5698  5710 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,11-28 17:47:14.349   928   945 D BluetoothHeadset: onBluetoothStateChange: up=true
11-28 17:47:14.349  5698  5710 I BluetoothAdapterState: Entering OnState
11-28 17:47:14.349  3801  3985 D BluetoothHeadset: onBluetoothStateChange: up=true
11-28 17:47:14.349  5698  5714 D BluetoothAdapterProperties: Discoverable Timeout:120
11-28 17:47:14.349   928   945 D BluetoothHeadset: onBluetoothStateChange: up=true
11-28 17:47:14.350  3127  3143 D BluetoothPan: onBluetoothStateChange on: true
,11-28 17:47:14.351   928   945 D BluetoothHeadset: onBluetoothStateChange: up=true
,11-28 17:47:14.351  3127  3138 D BluetoothPbap: onBluetoothStateChange: up=true
11-28 17:47:14.352  3127  3127 D BluetoothPan: BluetoothPAN Proxy object connected
11-28 17:47:14.352  3127  3127 D PanProfile: Bluetooth service connected
,11-28 17:47:14.353  5681  5692 D BluetoothInputDevice: onBluetoothStateChange: up=true
,11-28 17:47:14.353  5681  5691 D BluetoothPan: onBluetoothStateChange on: true
11-28 17:47:14.353  5681  5692 D BluetoothMap: onBluetoothStateChange: up=true
,11-28 17:47:14.353   928   945 D BluetoothA2dp: onBluetoothStateChange: up=true
11-28 17:47:14.354  3127  3143 D BluetoothMap: onBluetoothStateChange: up=true
11-28 17:47:14.355   928   928 D BluetoothA2dp: Proxy object connected
11-28 17:47:14.356  3127  3127 D BluetoothMap: Proxy object connected
,11-28 17:47:14.356  3127  3127 D MapProfile: Bluetooth service connected
11-28 17:47:14.356  5681  5691 D BluetoothPbap: onBluetoothStateChange: up=true
11-28 17:47:14.356  3127  3127 D BluetoothMap: getConnectedDevices()
11-28 17:47:14.357  3127  3138 D BluetoothHeadset: onBluetoothStateChange: up=true
11-28 17:47:14.358  3127  3143 D BluetoothInputDevice: onBluetoothStateChange: up=true
,11-28 17:47:14.359  3127  3127 D BluetoothInputDevice: Proxy object connected
,11-28 17:47:14.359  3127  3127 D HidProfile: Bluetooth service connected
11-28 17:47:14.359  3127  3138 D BluetoothA2dp: onBluetoothStateChange: up=true
11-28 17:47:14.361  3127  3127 D BluetoothA2dp: Proxy object connected
,11-28 17:47:14.362  5698  5698 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,11-28 17:47:14.362   928   928 I Telecom : BluetoothPhoneService: queryPhoneState
11-28 17:47:14.363  5698  5698 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
,11-28 17:47:14.365  5698  5698 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-28 17:47:14.366  5681  5681 D LocalBluetoothProfileManager: Adding local A2DP profile
,11-28 17:47:14.367  5698  5698 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-28 17:47:14.368  5698  5698 D ObexServerSockets: Succeed to create listening sockets 
11-28 17:47:14.369  5698  5698 D ObexServerSockets0: startAccept()
11-28 17:47:14.369  5698  5698 D ObexServerSockets0: prepareForNewConnect()
11-28 17:47:14.369  5681  5681 D LocalBluetoothProfileManager: Adding local HEADSET profile
11-28 17:47:14.371  5698  5698 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
,11-28 17:47:14.371  5698  5698 D BluetoothSdpJni: SDP Create record success - handle: 0
11-28 17:47:14.371  5698  5698 D BluetoothMapService: onReceive
11-28 17:47:14.371  5698  5735 D ObexServerSockets0: Accepting socket connection...
11-28 17:47:14.371  5698  5736 D ObexServerSockets0: Accepting socket connection...
11-28 17:47:14.371  5698  5698 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
11-28 17:47:14.372  5698  5698 D BluetoothMapService: STATE_ON
11-28 17:47:14.373  5698  5737 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-28 17:47:14.374  5698  5737 D BluetoothSdpJni: sdpCreateSapsRecordNative:
,11-28 17:47:14.374  5698  5737 D BluetoothSdpJni: SDP Create record success - handle: 1
,11-28 17:47:14.376  5681  5681 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,11-28 17:47:14.378  5681  5681 D BluetoothA2dp: Proxy object connected
,11-28 17:47:14.382  3584  3584 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,11-28 17:47:14.387  5681  5681 D DockEventReceiver: finishStartingService: stopping service
,11-28 17:47:14.388  3127  3127 D BluetoothPbap: Proxy object connected
11-28 17:47:14.388  3127  3127 D PbapServerProfile: Bluetooth service connected
,11-28 17:47:14.390  5606  5679 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-28 17:47:14.390  5606  5679 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-28 17:47:14.390  5606  5679 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-28 17:47:14.390  5606  5679 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-28 17:47:14.390  5606  5679 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-28 17:47:14.390  5606  5679 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-28 17:47:14.390  5606  5679 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-28 17:47:14.390  5606  5679 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-28 17:47:14.390  5606  5679 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,11-28 17:47:14.392  5606  5679 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
,11-28 17:47:14.393  5681  5681 D BluetoothPbap: Proxy object connected
11-28 17:47:14.393  5606  5652 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testIsWifiEnabled
11-28 17:47:14.394   928  4209 D WifiService: setWifiEnabled: false pid=5606, uid=10077
11-28 17:47:14.394   928  4209 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
11-28 17:47:14.394  5681  5681 D PbapServerProfile: Bluetooth service connected
11-28 17:47:14.395  5698  5741 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-28 17:47:14.397   928  2976 D WifiStateMachine: WifiStateMachine: Leaving Connected state
11-28 17:47:14.397   928  2976 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
11-28 17:47:14.397   928  2976 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,11-28 17:47:14.397   928  2976 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
11-28 17:47:14.399  5606  5652 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-28 17:47:14.407   928  5378 D DhcpClient: Clearing IP address
,11-28 17:47:14.407  5698  5698 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
11-28 17:47:14.407   508   924 D CommandListener: Clearing all IP addresses on wlan0
11-28 17:47:14.407  5698  5698 D ObexServerSockets0: prepareForNewConnect()
,11-28 17:47:14.411  5698  5746 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-28 17:47:14.413  5698  5746 I BtOppRfcommListener: Accept thread started.
11-28 17:47:14.414   508   924 D CommandListener: Setting iface cfg
,11-28 17:47:14.415  3584  5455 V NativeCrypto: Read error: ssl=0x7f8798b980: I/O error during system call, Connection timed out
,11-28 17:47:14.417  3584  5455 V NativeCrypto: SSL shutdown failed: ssl=0x7f8798b980: I/O error during system call, Broken pipe
11-28 17:47:14.418   928  4209 D ConnectivityService: reportNetworkConnectivity(100, false) by 10012
11-28 17:47:14.419   928  5374 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Forcing reevaluation for UID 10012
11-28 17:47:14.421   928  5374 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.gstatic.com": No address associated with hostname
11-28 17:47:14.421   928  2978 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] validation failed
11-28 17:47:14.421   928  2978 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
11-28 17:47:14.422   928  2978 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
11-28 17:47:14.426   928  2978 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
,11-28 17:47:14.426   928  2978 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
11-28 17:47:14.429   541   541 E Parcel  : Reading a NULL string not supported here.
11-28 17:47:14.430   928   928 D RttService: SCAN_AVAILABLE : 1
11-28 17:47:14.431   928  3080 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,11-28 17:47:14.431   928  2978 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
,11-28 17:47:14.433  3752  3869 W QCNEJ   : |CORE| network lost: 100
11-28 17:47:14.434  3752  3869 W QCNEJ   : |CORE| onLost: unbind the process to WIFI
,11-28 17:47:14.443   928  5379 D DhcpClient: Receive thread stopped
,11-28 17:47:14.446   928  2976 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,11-28 17:47:14.451   928   928 D BluetoothHeadset: Proxy object connected
11-28 17:47:14.451   928   928 D BluetoothHeadset: Proxy object connected
11-28 17:47:14.451   928   928 D BluetoothHeadset: Proxy object connected
,11-28 17:47:14.451   928   945 D BluetoothHeadset: Proxy object connected
11-28 17:47:14.451  3127  3138 D BluetoothHeadset: Proxy object connected
11-28 17:47:14.452  3801  3822 D BluetoothHeadset: Proxy object connected
11-28 17:47:14.453   508   924 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-28 17:47:14.457   928  2976 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,11-28 17:47:14.459  3127  3143 D BluetoothHeadset: Proxy object connected
,11-28 17:47:14.465  3127  3127 D HeadsetProfile: Bluetooth service connected
,11-28 17:47:14.467  3127  3127 D HeadsetProfile: Bluetooth service connected
,11-28 17:47:14.472   508   924 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
11-28 17:47:14.472   508   924 D CommandListener: Clearing all IP addresses on wlan0
11-28 17:47:14.472   508   924 D TetherController: Setting IP forward enable = 0
,11-28 17:47:14.473  5681  5691 D BluetoothHeadset: Proxy object connected
,11-28 17:47:14.474   928  2978 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
,11-28 17:47:14.474   928  2978 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,11-28 17:47:14.474  5681  5681 D HeadsetProfile: Bluetooth service connected
11-28 17:47:14.475   928  2976 D DhcpClient: doQuit
11-28 17:47:14.475   928  2976 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,11-28 17:47:14.476   928  5378 D DhcpClient: onQuitting
11-28 17:47:14.477   928   945 D Tethering: MasterInitialState.processMessage what=3
11-28 17:47:14.478  3457  3457 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
11-28 17:47:14.483  3966  3966 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
,11-28 17:47:14.484  5262  5262 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@fbd971e and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
11-28 17:47:14.488  4056  4056 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
11-28 17:47:14.489  5024  5037 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
11-28 17:47:14.490  5024  5037 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
11-28 17:47:14.490  5024  5037 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,0,0,0
11-28 17:47:14.490  5024  5037 E SarControlService: no key has been found,reset the power
11-28 17:47:14.490  5024  5062 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
11-28 17:47:14.490  5024  5062 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
11-28 17:47:14.490  5024  5062 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
11-28 17:47:14.491  5050  5050 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
11-28 17:47:14.491  5050  5050 D QcrilMsgTunnelSocket: [1002] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
11-28 17:47:14.492  5024  5062 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
11-28 17:47:14.492  5024  5062 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
11-28 17:47:14.492  5024  5062 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
11-28 17:47:14.493  5050  5050 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
,11-28 17:47:14.493  5050  5050 D QcrilMsgTunnelSocket: [1003] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
11-28 17:47:14.494  3457  3457 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
11-28 17:47:14.494  5050  5065 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@aa83b74 HexData = [00000000ea03000000000000ffffffff]
11-28 17:47:14.494  5050  5065 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-28 17:47:14.494  5050  5065 D QcrilMsgTunnelSocket: [1002] < OEM_HOOK_RAW [null]
11-28 17:47:14.498  3457  3457 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
11-28 17:47:14.498  5050  5050 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
,11-28 17:47:14.498  5024  5035 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
11-28 17:47:14.500   508   917 W SocketClient: write error (Broken pipe)
11-28 17:47:14.500   508   917 W SocketClient: Unable to send msg '600 Iface linkstate wlan0 up'
11-28 17:47:14.500  4056  4056 D SystemUpdateService: onCreate
11-28 17:47:14.500   508   917 W SocketListener: Error sending broadcast (Broken pipe)
11-28 17:47:14.503  4056  4056 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
11-28 17:47:14.505  5050  5065 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@aa83b74 HexData = [00000000eb03000000000000ffffffff]
11-28 17:47:14.505  5050  5065 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-28 17:47:14.505  5050  5065 D QcrilMsgTunnelSocket: [1003] < OEM_HOOK_RAW [null]
11-28 17:47:14.506  5050  5050 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
11-28 17:47:14.506  5024  5034 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
,11-28 17:47:14.512  4056  5761 I SystemUpdateService: active receiver: enabled
,11-28 17:47:14.514  4056  4056 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,11-28 17:47:14.520  4056  5403 I iu.UploadsManager: num queued entries: 0
,11-28 17:47:14.520  4056  5403 I iu.UploadsManager: num updated entries: 0
11-28 17:47:14.522  4056  4056 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
11-28 17:47:14.523  4056  4056 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
11-28 17:47:14.525  4056  5403 I iu.SyncManager: NEXT; no task
11-28 17:47:14.525  4056  5761 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,11-28 17:47:14.527  4056  5761 I SystemUpdateService: network: null; metered: false; mobile allowed: true
11-28 17:47:14.527  4056  5761 I SystemUpdateService: now status is 0 (complete)
11-28 17:47:14.527  4056  5761 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
11-28 17:47:14.527  4056  5761 I SystemUpdateService: file has been verified
11-28 17:47:14.527   508   924 E Netd    : netlink response contains error (No such file or directory)
11-28 17:47:14.529   928  2978 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
11-28 17:47:14.527  4056  5761 I SystemUpdateService: OTA package size = 21989297
11-28 17:47:14.529   928  2978 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,11-28 17:47:14.530  3457  3457 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,11-28 17:47:14.531   508   924 D TetherController: Setting IP forward enable = 0
,11-28 17:47:14.533  4056  5761 I SystemUpdateService: showing system update notification
,11-28 17:47:14.535   928  3147 I ActivityManager: Start proc 5767:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,11-28 17:47:14.541  3457  3457 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,11-28 17:47:14.549   928   928 V NotificationService: pkg=com.google.android.gms canInterrupt=false intercept=true
,11-28 17:47:14.551  4056  4056 D SystemUpdateService: onDestroy
,11-28 17:47:14.570  5767  5767 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm64
,11-28 17:47:14.573  5767  5767 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,11-28 17:47:14.579  5767  5767 D SprintDMHelper: simOperator: 
,11-28 17:47:14.580  5767  5767 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,11-28 17:47:14.590  4487  5781 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,11-28 17:47:14.592   928  3598 I ActivityManager: Killing 5262:com.google.android.music:main/u0a59 (adj 15): empty #17
,11-28 17:47:14.624   928  3598 I ActivityManager: Start proc 5782:com.google.android.apps.gcs/u0a11 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,11-28 17:47:14.645   928  2976 D wifi    : In wifi stop Hal
11-28 17:47:14.645  4487  4487 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,11-28 17:47:14.646   928  2976 D wifi    : halHandle = 0x7f85dc7f00, mVM = 0x7fa240d140, mCls = 0x100a02
11-28 17:47:14.646   928  3456 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
11-28 17:47:14.646   928  3456 D WifiHAL : Got a signal to exit!!!
11-28 17:47:14.646   928  3456 I WifiHAL : Exit wifi_event_loop
11-28 17:47:14.646   928  2976 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 11
11-28 17:47:14.646   928  2976 E WifiHAL : Event processing terminated
,11-28 17:47:14.647   928  2976 D wifi    : In wifi cleaned up handler
11-28 17:47:14.647   928  2976 I WifiHAL : Internal cleanup completed
11-28 17:47:14.647  3950  4223 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,11-28 17:47:14.658  5782  5782 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm64
,11-28 17:47:14.665   928  4207 I ActivityManager: Killing 3875:com.android.providers.calendar/u0a1 (adj 15): empty #17
,11-28 17:47:14.669   928  3456 D wifi    : set interface wlan0 flags (DOWN)
,11-28 17:47:14.670   928  2976 D WifiNative-HAL: HAL event thread stopped successfully
,11-28 17:47:14.877   928   945 D Tethering: InitialState.processMessage what=4
,11-28 17:47:14.885   928   945 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,11-28 17:47:14.901  5606  5679 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-28 17:47:14.901  5606  5679 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-28 17:47:14.901  5606  5679 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-28 17:47:14.901  5606  5679 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-28 17:47:14.901  5606  5679 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-28 17:47:14.901  5606  5679 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-28 17:47:14.901  5606  5679 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-28 17:47:14.901  5606  5679 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-28 17:47:14.901  5606  5679 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,11-28 17:47:14.903  5606  5679 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
11-28 17:47:14.906   928  3212 D WifiService: setWifiEnabled: true pid=5606, uid=10077
,11-28 17:47:14.906   928  3212 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-28 17:47:14.909  5606  5652 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-28 17:47:14.910   508   924 D SoftapController: Softap fwReload - Ok
,11-28 17:47:14.914   508   924 D CommandListener: Setting iface cfg
11-28 17:47:14.914   508   924 D CommandListener: Trying to bring down wlan0
,11-28 17:47:14.916   508   924 D CommandListener: Clearing all IP addresses on wlan0
,11-28 17:47:14.918   928  2976 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,11-28 17:47:15.410   928  4207 D WifiService: setWifiEnabled: true pid=5606, uid=10077
,11-28 17:47:15.416   928  4207 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-28 17:47:15.525   928  2976 D wifi    : set interface wlan0 flags (UP)
,11-28 17:47:15.525   928  2976 I WifiHAL : Initializing wifi
11-28 17:47:15.526   928  2976 I WifiHAL : Creating socket
11-28 17:47:15.531   928  2976 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
11-28 17:47:15.532   928  2976 D wifi    : Did set static halHandle = 0x7f85dc7f00
11-28 17:47:15.532   928  2976 D wifi    : halHandle = 0x7f85dc7f00, mVM = 0x7fa240d140, mCls = 0x188e
11-28 17:47:15.532   928  2976 D wifi    : array field set
,11-28 17:47:15.532   928  2976 I WifiNative-HAL: interface[0] = wlan0
11-28 17:47:15.535   928  5798 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=547706666752
11-28 17:47:15.536   928  5798 D wifi    : waitForHalEvents called, vm = 0x7fa240d140, obj = 0x188e, env = 0x7f832c4080
,11-28 17:47:15.546   928   945 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,11-28 17:47:15.601  5799  5799 I wpa_supplicant: Successfully initialized wpa_supplicant
,11-28 17:47:15.637   928  2976 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,11-28 17:47:15.673  5799  5799 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,11-28 17:47:15.720  5799  5799 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,11-28 17:47:15.720  5799  5799 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,11-28 17:47:15.743   928  2976 D WifiConfigStore: Loading config and enabling all networks 
,11-28 17:47:15.768   928  2976 D WifiConfigStore: loaded 0 passpoint configs
,11-28 17:47:15.769   928  2976 W WifiConfigStore: Upgrading network 4 to android.uid.system:1000
,11-28 17:47:15.769   928  2976 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
11-28 17:47:15.770   928  2976 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
11-28 17:47:15.770   928  2976 W WifiConfigStore: Upgrading network 3 to android.uid.system:1000
11-28 17:47:15.770   928  2976 W WifiConfigStore: Upgrading network 2 to android.uid.system:1000
,11-28 17:47:15.771   928  2976 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,11-28 17:47:15.771   928  2976 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 5
11-28 17:47:15.771   928  2976 E WifiConfigStore: found sortedWifiConfigurations : "AndroidAP"WPA_PSK
11-28 17:47:15.772   928  2976 E WifiConfigStore: found sortedWifiConfigurations : "AndroidHotspot2346"WPA_PSK
11-28 17:47:15.772   928  2976 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,11-28 17:47:15.772   928  2976 E WifiConfigStore: found sortedWifiConfigurations : "Thali_internal"WPA_PSK
11-28 17:47:15.772   928  2976 E WifiConfigStore: found sortedWifiConfigurations : "MC"WPA_PSK
,11-28 17:47:15.774   928  2976 D WifiNative-HAL: Setting external_sim to 1
,11-28 17:47:15.775   928  2976 D wifi    : setting dfs flag to true, 0x7f86c9c600
,11-28 17:47:15.775   928  2976 D WifiStateMachine: Setting OUI to DA-A1-19
11-28 17:47:15.775   928  2976 D wifi    : setting scan oui 0x7f86c9c600
11-28 17:47:15.775   928  2976 D WifiHAL : Sending mac address OUI
,11-28 17:47:15.776  4487  4487 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,11-28 17:47:15.778   928  2976 E native  : do suspend false
,11-28 17:47:15.785   928  2976 D wifi    : android_net_wifi_setLinkLayerStats: 1
,11-28 17:47:15.785   928   928 D RttService: SCAN_AVAILABLE : 3
11-28 17:47:15.785   928  3080 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,11-28 17:47:15.789   508   924 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,11-28 17:47:15.790   508   924 D CommandListener: Setting iface cfg
,11-28 17:47:15.793   928  2975 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '125 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 125 Failed to set address (No such device)'
11-28 17:47:15.793   928  2975 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,11-28 17:47:15.801   928  2975 D WifiNative-HAL: p2pGetDeviceAddress
,11-28 17:47:15.802   928  2975 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:70
,11-28 17:47:15.808   928   943 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=106807 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=18 mControllerEnergyUsed=68 }
,11-28 17:47:15.927  5606  5679 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-28 17:47:15.927  5606  5679 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-28 17:47:15.927  5606  5679 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-28 17:47:15.927  5606  5679 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-28 17:47:15.927  5606  5679 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-28 17:47:15.927  5606  5679 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-28 17:47:15.927  5606  5679 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-28 17:47:15.927  5606  5679 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-28 17:47:15.927  5606  5679 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,11-28 17:47:15.933  5606  5679 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
,11-28 17:47:15.936  5606  5652 D BluetoothAdapter: enable(): BT is already enabled..!
,11-28 17:47:15.937   928  3212 D WifiService: setWifiEnabled: true pid=5606, uid=10077
,11-28 17:47:15.937   928  3212 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-28 17:47:15.939  5606  5652 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,11-28 17:47:15.939  5606  5652 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-28 17:47:15.939  5606  5652 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,11-28 17:47:15.940  5606  5652 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a8bb0c5 removed from the list
11-28 17:47:15.940  5606  5652 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-28 17:47:15.940  5606  5652 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ab47a1a removed from the list
,11-28 17:47:15.940  5606  5652 D io.jxcore.node.ConnectivityMonitor: stop
11-28 17:47:15.943  5606  5652 I io.jxcore.node.IncomingSocketThreadTest: Starting test: testSetTcpPortNumber
,11-28 17:47:15.945  5606  5652 I io.jxcore.node.IncomingSocketThreadTest: Starting test: testGetTcpPortNumber
,11-28 17:47:15.946  5606  5652 I io.jxcore.node.IncomingSocketThreadTest: Starting test: testGetLocalHostPort
11-28 17:47:15.947  5606  5652 I io.jxcore.node.IncomingSocketThreadTest: Starting test: testConstructor
,11-28 17:47:15.950  5606  5652 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityCreated
,11-28 17:47:15.950  5606  5652 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,11-28 17:47:15.951  5606  5652 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityResumed
11-28 17:47:15.952  5606  5652 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,11-28 17:47:15.953  5606  5652 I io.jxcore.node.LifeCycleMonitorTest: Starting test: constructor
,11-28 17:47:15.955  5606  5652 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivitySaveInstanceState
11-28 17:47:15.955  5606  5652 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@fa98a66 Bundle[{}]
11-28 17:47:15.956  5606  5652 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testStartStop
11-28 17:47:15.956  5606  5652 I io.jxcore.node.LifeCycleMonitor: start: OK
11-28 17:47:15.956  5606  5652 I io.jxcore.node.LifeCycleMonitor: stop: OK
11-28 17:47:15.957  5606  5652 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityStarted
,11-28 17:47:15.957  5606  5652 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
11-28 17:47:15.958  5606  5652 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityStopped
11-28 17:47:15.958  5606  5652 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
11-28 17:47:15.958  5606  5652 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityDestroyed
11-28 17:47:15.958  5606  5652 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
11-28 17:47:15.959  5606  5652 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityPaused
,11-28 17:47:15.959  5606  5652 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,11-28 17:47:15.961  5606  5652 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testToString
,11-28 17:47:15.963  5606  5652 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testToJsonObject
,11-28 17:47:15.965  5606  5652 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testConstructorWithParameters
,11-28 17:47:15.966  5606  5652 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testSetListeningOnPortNumber
,11-28 17:47:15.967  5606  5652 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testGetListeningOnPortNumber
,11-28 17:47:15.968  5606  5652 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testDefaultConstructor
,11-28 17:47:15.970  5606  5652 I io.jxcore.node.OutgoingSocketThreadTest: Starting test: testClose
,11-28 17:47:15.972  5606  5652 I io.jxcore.node.OutgoingSocketThreadTest: Starting test: testNoAvailablePorts
,11-28 17:47:16.976  5606  5652 I io.jxcore.node.OutgoingSocketThreadTest: Starting test: testGetListeningOnPortNumber
,11-28 17:47:16.979  5606  5652 I io.jxcore.node.OutgoingSocketThreadTest: Starting test: testConstructor
,11-28 17:47:16.983  5606  5652 I io.jxcore.node.SocketThreadBaseTest: Starting test: testGetListener
11-28 17:47:16.985  5606  5652 I io.jxcore.node.SocketThreadBaseTest: Starting test: testSetPeerProperties
,11-28 17:47:16.987  5606  5652 I io.jxcore.node.SocketThreadBaseTest: Starting test: testClose
,11-28 17:47:16.987  5606  5652 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 172)
11-28 17:47:16.989  5606  5652 I io.jxcore.node.SocketThreadBaseTest: Starting test: testCloseLocalSocketAndStreams
,11-28 17:47:16.990  5606  5652 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
11-28 17:47:16.990  5606  5652 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 173)
11-28 17:47:16.991  5606  5652 I io.jxcore.node.SocketThreadBaseTest: Starting test: testGetPeerProperties
11-28 17:47:16.993  5606  5652 I io.jxcore.node.SocketThreadBaseTest: Starting test: testEquals
,11-28 17:47:16.995  5606  5652 I io.jxcore.node.SocketThreadBaseTest: Starting test: testGetLocalHostAddressAsString
,11-28 17:47:16.996  5606  5652 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-28 17:47:16.996  5606  5652 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1c9cf28 added. We now have 3 listener(s)
,11-28 17:47:16.999  5606  5652 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
,11-28 17:47:16.999  5606  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-28 17:47:17.000  5606  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-28 17:47:17.000  5606  5652 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,11-28 17:47:17.000  5606  5652 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fb9441 added. We now have 3 listener(s)
11-28 17:47:17.000  5606  5652 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-28 17:47:17.001  5606  5652 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,11-28 17:47:17.009  5606  5652 I io.jxcore.node.StartStopOperationHandlerTest: Starting test: testCancelCurrentOperation
,11-28 17:47:17.010  5606  5652 I io.jxcore.node.StartStopOperationHandlerTest: Starting test: testExecuteStopOperation
11-28 17:47:17.011  5606  5652 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 5
11-28 17:47:17.011  5606  5652 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 4 -> 5
,11-28 17:47:17.011  5606  5652 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-57,5,main], id: 57
,11-28 17:47:17.011  5606  5652 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-57,5,main], id: 57
,11-28 17:47:17.011  5606  5652 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-57,5,main], id: 57
11-28 17:47:17.012  5606  5652 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
11-28 17:47:17.012  5606  5652 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
11-28 17:47:17.012  5606  5652 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
11-28 17:47:17.012  5606  5652 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,11-28 17:47:17.012  5606  5652 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
11-28 17:47:17.016  5606  5652 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,11-28 17:47:17.017  5606  5652 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,11-28 17:47:17.018  5606  5652 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
,11-28 17:47:17.018  5606  5652 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
11-28 17:47:17.018  5606  5652 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
11-28 17:47:17.018  5606  5652 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
,11-28 17:47:17.018  5606  5652 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,11-28 17:47:17.018  5606  5606 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
11-28 17:47:17.018  5606  5803 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
11-28 17:47:17.018  5606  5652 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
11-28 17:47:17.021  5606  5803 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-28 17:47:17.025  5606  5803 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
11-28 17:47:17.022  5734  5734 W Binder_4: type=1400 audit(0.0:124): avc: denied { ioctl } for path="socket:[33115]" dev="sockfs" ino=33115 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-28 17:47:17.026  5606  5652 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-28 17:47:17.026  5606  5652 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,11-28 17:47:17.026  5606  5652 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
11-28 17:47:17.022  5734  5734 W Binder_4: type=1400 audit(0.0:125): avc: denied { ioctl } for path="socket:[33115]" dev="sockfs" ino=33115 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,11-28 17:47:17.035  5606  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-57,5,main], id: 57
,11-28 17:47:17.035  5606  5652 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,11-28 17:47:17.037  5606  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,11-28 17:47:17.037  5606  5652 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-28 17:47:17.037  5606  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 5
,11-28 17:47:17.041  5606  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Current thread: Thread[Thread-57,5,main], id: 57
,11-28 17:47:17.041  5606  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-57,5,main], id: 57
11-28 17:47:17.041  5606  5652 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
11-28 17:47:17.041  5606  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: createAdvertiseDataToServiceData 
11-28 17:47:17.042  5606  5652 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-28 17:47:17.042  5606  5652 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 05 60 83 34 25 D7 D4
11-28 17:47:17.042  5606  5652 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[5, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,11-28 17:47:17.042  5606  5652 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: created AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[5, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-28 17:47:17.042  5606  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: Current thread: Thread[Thread-57,5,main], id: 57
11-28 17:47:17.042  5606  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: was started = false
11-28 17:47:17.042  5606  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: advertiseData = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[5, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-28 17:47:17.042  5606  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData finished: Current thread: Thread[Thread-57,5,main], id: 57
11-28 17:47:17.042  5606  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = NOT_STARTEDCurrent thread: Thread[Thread-57,5,main], id: 57
,11-28 17:47:17.043  5606  5652 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... adv data = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[5, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]Current thread: Thread[Thread-57,5,main], id: 57
11-28 17:47:17.044  5606  5652 D BluetoothAdapter: STATE_ON
,11-28 17:47:17.048  5698  5708 D BtGatt.GattService: registerClient() - UUID=cbdcaad1-d8ef-474f-93b4-a73bb7d41c52
,11-28 17:47:17.049  5698  5714 D BtGatt.GattService: onClientRegistered() - UUID=cbdcaad1-d8ef-474f-93b4-a73bb7d41c52, clientIf=5
,11-28 17:47:17.050  5606  5617 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
,11-28 17:47:17.052  5698  5716 D BtGatt.AdvertiseManager: message : 0
,11-28 17:47:17.055  5698  5716 D BtGatt.AdvertiseManager: starting multi advertising
,11-28 17:47:17.070  5698  5714 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,11-28 17:47:17.078  5698  5714 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,11-28 17:47:17.079  5606  5652 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment Current thread: Thread[Thread-57,5,main], id: 57
,11-28 17:47:17.079  5606  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTINGCurrent thread: Thread[Thread-57,5,main], id: 57
11-28 17:47:17.079  5606  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,11-28 17:47:17.079  5606  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged default (no call to listener). Current thread: Thread[Thread-57,5,main], id: 57
11-28 17:47:17.079  5606  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-57,5,main], id: 57
,11-28 17:47:17.079  5606  5652 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[Thread-57,5,main], id: 57
11-28 17:47:17.079  5606  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[Thread-57,5,main], id: 57
,11-28 17:47:17.079  5606  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser started = true Current thread: Thread[Thread-57,5,main], id: 57
11-28 17:47:17.079  5606  5652 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,11-28 17:47:17.081  5606  5652 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-28 17:47:17.081  5606  5652 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
11-28 17:47:17.083  5606  5652 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
11-28 17:47:17.083  5606  5652 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
11-28 17:47:17.083  5606  5652 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
11-28 17:47:17.083  5606  5606 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
11-28 17:47:17.084  5606  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess : Current thread: Thread[main,5,main], id: 1
11-28 17:47:17.084  5606  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNINGCurrent thread: Thread[main,5,main], id: 1
11-28 17:47:17.084  5606  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
11-28 17:47:17.084  5606  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  true. Current thread: Thread[main,5,main], id: 1
11-28 17:47:17.084  5606  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[main,5,main], id: 1
11-28 17:47:17.084  5606  5606 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-28 17:47:17.085  5606  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-28 17:47:17.085  5606  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [ADVERTISING]
11-28 17:47:17.085  5606  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-28 17:47:17.085  5606  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-28 17:47:17.085  5606  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]Current thread: Thread[main,5,main], id: 1
11-28 17:47:17.085  5606  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-28 17:47:17.085  5606  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING] Current thread: Thread[main,5,main], id: 1
11-28 17:47:17.086  5606  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-28 17:47:17.089  5606  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-28 17:47:17.090  5606  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
11-28 17:47:17.090  5606  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-28 17:47:17.090  5606  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-28 17:47:17.090  5606  5606 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,11-28 17:47:17.591  5606  5606 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
,11-28 17:47:17.591  5606  5606 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
11-28 17:47:17.591  5606  5606 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,11-28 17:47:18.927  5799  5799 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-28 17:47:18.932  5799  5799 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-28 17:47:18.986   928  2976 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,11-28 17:47:18.988   928  2976 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3
,11-28 17:47:18.988   928  2976 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-28 17:47:19.002   928  2976 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=0
,11-28 17:47:19.036   928  2976 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=0
,11-28 17:47:19.042  5799  5799 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,11-28 17:47:19.466  5799  5799 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,11-28 17:47:19.499  5799  5799 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,11-28 17:47:19.500  5799  5799 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,11-28 17:47:19.511   928  2976 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,11-28 17:47:19.511   928  2976 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
11-28 17:47:19.511   928  2978 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,11-28 17:47:19.530   928  2976 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-28 17:47:19.541   508   924 D CommandListener: Setting iface cfg
,11-28 17:47:19.548   928  2976 D WifiStateMachine: Start Dhcp Watchdog 2
,11-28 17:47:19.555   928  5808 D DhcpClient: Receive thread started
,11-28 17:47:19.559   928  2978 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-28 17:47:19.559   928  2976 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
11-28 17:47:19.559   928  2978 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
,11-28 17:47:19.640   928  2976 E native  : do suspend false
,11-28 17:47:19.653   928  5807 D DhcpClient: Broadcasting DHCPDISCOVER
,11-28 17:47:19.665   928  5808 D DhcpClient: Received packet: 60:83:34:25:d7:70 OFFER, ip /192.168.1.109, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172729, domain null
,11-28 17:47:19.666   928  5807 D DhcpClient: Got pending lease: IP address 192.168.1.109/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172729 seconds
,11-28 17:47:19.669   928  5807 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.109 serverid=192.168.1.1
,11-28 17:47:19.692   928  5808 D DhcpClient: Received packet: 60:83:34:25:d7:70 ACK: your new IP /192.168.1.109, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,11-28 17:47:19.693   928  5807 D DhcpClient: Confirmed lease: IP address 192.168.1.109/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,11-28 17:47:19.695   508   924 D CommandListener: Setting iface cfg
,11-28 17:47:19.697   928  2976 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,11-28 17:47:19.700   928  5807 D DhcpClient: Scheduling renewal in 86399s
,11-28 17:47:19.705   928  2976 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
11-28 17:47:19.705   928  2976 D WifiConfigStore: No blacklist allowed without epno enabled
11-28 17:47:19.706   928  2978 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
11-28 17:47:19.707   928  2976 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
11-28 17:47:19.707   928  2978 D ConnectivityService: Adding iface wlan0 to network 101
,11-28 17:47:19.736   928  2978 E ConnectivityService: Unexpected mtu value: 0, wlan0
,11-28 17:47:19.736   928  2978 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
,11-28 17:47:19.739   928  2978 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,11-28 17:47:19.740   928  2978 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,11-28 17:47:19.741   928  2978 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,11-28 17:47:19.747   928  2978 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-28 17:47:19.751   928  2978 D ConnectivityService: scheduleUnvalidatedPrompt 101
,11-28 17:47:19.751   928  2978 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
11-28 17:47:19.751   928  2978 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
11-28 17:47:19.751   928  2978 D ConnectivityService:    accepting network in place of null
11-28 17:47:19.751   928  2976 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
11-28 17:47:19.751   928  2976 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
11-28 17:47:19.751   928  2978 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d770/64,192.168.1.109/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -51]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,11-28 17:47:19.763   928  5806 D NetlinkSocketObserver: NeighborEvent{elapsedMs=110762, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,11-28 17:47:19.770   508   924 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-28 17:47:19.789   508   924 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-28 17:47:19.792   928  2978 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,11-28 17:47:19.792   928  2978 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
11-28 17:47:19.792  3752  3869 W QCNEJ   : |CORE| network available: 101
11-28 17:47:19.793   928  2978 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
11-28 17:47:19.796  3752  3869 W QCNEJ   : |CORE| onAvailable: bind the process to WIFI
11-28 17:47:19.796   928   945 D Tethering: MasterInitialState.processMessage what=3
11-28 17:47:19.797  3752  3869 W QCNEJ   : |CORE| newLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d770/64,192.168.1.109/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}
11-28 17:47:19.797  3752  3869 W QCNEJ   : |CORE| curLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d770/64,192.168.1.109/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,11-28 17:47:19.806  5024  5037 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
,11-28 17:47:19.806  5024  5037 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
11-28 17:47:19.806  5024  5037 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,1,0,0
11-28 17:47:19.806  5024  5037 E SarControlService: no key has been found,reset the power
11-28 17:47:19.806  5024  5062 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
,11-28 17:47:19.806  5024  5062 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
11-28 17:47:19.806  5024  5062 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
11-28 17:47:19.807  5050  5050 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
11-28 17:47:19.807  5050  5050 D QcrilMsgTunnelSocket: [1004] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
11-28 17:47:19.808  5024  5062 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
11-28 17:47:19.808  5024  5062 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
11-28 17:47:19.808  5024  5062 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
,11-28 17:47:19.809  5050  5050 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
11-28 17:47:19.809  5050  5050 D QcrilMsgTunnelSocket: [1005] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
11-28 17:47:19.809  3966  3966 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
11-28 17:47:19.813  4056  4056 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
11-28 17:47:19.814  5050  5065 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@aa83b74 HexData = [00000000ec03000000000000ffffffff]
11-28 17:47:19.814  5050  5065 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-28 17:47:19.814  5050  5065 D QcrilMsgTunnelSocket: [1004] < OEM_HOOK_RAW [null]
,11-28 17:47:19.817  5050  5065 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@aa83b74 HexData = [00000000ed03000000000000ffffffff]
,11-28 17:47:19.817  5050  5065 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-28 17:47:19.817  5050  5065 D QcrilMsgTunnelSocket: [1005] < OEM_HOOK_RAW [null]
11-28 17:47:19.817  5050  5050 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
11-28 17:47:19.818  5024  5035 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
11-28 17:47:19.818  5050  5050 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
11-28 17:47:19.818  5024  5034 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
11-28 17:47:19.818  4056  4056 D SystemUpdateService: onCreate
,11-28 17:47:19.823  4056  4056 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,11-28 17:47:19.831   928  5805 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=172.217.22.110,2a00:1450:4001:81d::200e
11-28 17:47:19.834  4056  4056 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,11-28 17:47:19.838  4056  5403 I iu.UploadsManager: num queued entries: 0
,11-28 17:47:19.838  4056  5403 I iu.UploadsManager: num updated entries: 0
11-28 17:47:19.839  4056  5403 I iu.SyncManager: NEXT; no task
,11-28 17:47:19.842  4056  5818 I SystemUpdateService: active receiver: enabled
,11-28 17:47:19.844  4056  4056 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,11-28 17:47:19.846  4056  4056 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,11-28 17:47:19.848  5767  5767 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,11-28 17:47:19.851  5767  5767 D SprintDMHelper: simOperator: 
,11-28 17:47:19.851  5767  5767 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,11-28 17:47:19.872  4056  5818 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,11-28 17:47:19.882   928  5805 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Mon, 28 Nov 2016 16:47:19 GMT], X-Android-Received-Millis=[1480351639881], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1480351639856]}
,11-28 17:47:19.882   928  2978 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
11-28 17:47:19.882   928  2978 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation  passed
11-28 17:47:19.882   928  2978 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-28 17:47:19.884   928  2978 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,11-28 17:47:19.886  4056  5818 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,11-28 17:47:19.886  4056  5818 I SystemUpdateService: now status is 0 (complete)
11-28 17:47:19.886  4056  5818 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
11-28 17:47:19.886  4056  5818 I SystemUpdateService: file has been verified
11-28 17:47:19.886  4056  5818 I SystemUpdateService: OTA package size = 21989297
,11-28 17:47:19.892  4056  5818 I SystemUpdateService: showing system update notification
,11-28 17:47:19.899   928   928 V NotificationService: pkg=com.google.android.gms canInterrupt=false intercept=true
,11-28 17:47:19.902  4056  4056 D SystemUpdateService: onDestroy
,11-28 17:47:20.022  4487  5822 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,11-28 17:47:20.586  5606  5652 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
,11-28 17:47:20.586  5606  5652 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
11-28 17:47:20.587  5606  5652 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
11-28 17:47:20.587  5606  5652 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
11-28 17:47:20.587  5606  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
,11-28 17:47:20.588  5606  5803 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
11-28 17:47:20.588  5606  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-28 17:47:20.588  5606  5803 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
,11-28 17:47:20.588  5606  5652 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
,11-28 17:47:20.588  5606  5803 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
11-28 17:47:20.588  5606  5652 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
,11-28 17:47:20.588  5606  5652 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,11-28 17:47:20.588  5606  5606 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,11-28 17:47:20.589  5606  5652 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-28 17:47:20.589  5606  5606 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-28 17:47:20.589  5606  5606 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
,11-28 17:47:20.589  5606  5652 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-57,5,main], id: 57
11-28 17:47:20.589  5606  5652 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
,11-28 17:47:20.589  5606  5652 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-28 17:47:20.590  5606  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-57,5,main], id: 57
11-28 17:47:20.590  5606  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-57,5,main], id: 57
,11-28 17:47:20.590  5606  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-57,5,main], id: 57
11-28 17:47:20.590  5606  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-57,5,main], id: 57
11-28 17:47:20.595  5606  5652 D BluetoothAdapter: STATE_ON
11-28 17:47:20.595  5606  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
,11-28 17:47:20.598  5606  5652 D BluetoothAdapter: STATE_ON
11-28 17:47:20.598  5606  5652 D BluetoothLeScanner: could not find callback wrapper
11-28 17:47:20.598  5606  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,11-28 17:47:20.599  5606  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-57,5,main], id: 57
11-28 17:47:20.599  5606  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-57,5,main], id: 57
11-28 17:47:20.599  5606  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-57,5,main], id: 57
11-28 17:47:20.600  5606  5652 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
11-28 17:47:20.600  5606  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-57,5,main], id: 57
,11-28 17:47:20.604  5698  5716 D BtGatt.AdvertiseManager: message : 1
,11-28 17:47:20.605  5698  5716 D BtGatt.AdvertiseManager: stop advertise for client 5
,11-28 17:47:20.616  5698  5714 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
,11-28 17:47:20.616  5698  5714 D BtGatt.GattService: Client app is not null!
11-28 17:47:20.617  5698  5708 D BtGatt.GattService: unregisterClient() - clientIf=5
11-28 17:47:20.618  5606  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-28 17:47:20.618  5606  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTEDCurrent thread: Thread[Thread-57,5,main], id: 57
,11-28 17:47:20.618  5606  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
11-28 17:47:20.619  5606  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  false. Current thread: Thread[Thread-57,5,main], id: 57
11-28 17:47:20.619  5606  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-57,5,main], id: 57
,11-28 17:47:20.619  5606  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-57,5,main], id: 57
11-28 17:47:20.619  5606  5652 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-28 17:47:20.620  5606  5652 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-28 17:47:20.621  5606  5652 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
,11-28 17:47:20.622  5606  5652 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
11-28 17:47:20.624  5606  5652 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
11-28 17:47:20.624  5606  5652 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-28 17:47:20.624  5606  5652 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
11-28 17:47:20.624  5606  5652 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
11-28 17:47:20.624  5606  5606 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-28 17:47:20.625  5606  5606 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
11-28 17:47:20.625  5606  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-28 17:47:20.625  5606  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-28 17:47:20.625  5606  5606 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
,11-28 17:47:20.625  5606  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-28 17:47:20.625  5606  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-28 17:47:20.625  5606  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [ADVERTISING]
11-28 17:47:20.625  5606  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-28 17:47:20.626  5606  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-28 17:47:20.626  5606  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-28 17:47:20.626  5606  5606 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-28 17:47:20.626  5606  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED] Current thread: Thread[main,5,main], id: 1
11-28 17:47:20.626  5606  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-28 17:47:20.629  5606  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-28 17:47:20.629  5606  5652 I io.jxcore.node.StartStopOperationHandlerTest: Starting test: testCheckCurrentOperationStatus
11-28 17:47:20.629  5606  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-28 17:47:20.629  5606  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-28 17:47:20.629  5606  5652 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-28 17:47:20.630  5606  5652 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-28 17:47:20.631  5606  5652 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
11-28 17:47:20.631  5606  5652 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
11-28 17:47:20.631  5606  5652 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-28 17:47:20.631  5606  5652 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
11-28 17:47:20.633  5606  5652 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
11-28 17:47:20.638  5606  5652 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-28 17:47:20.638  5606  5652 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-28 17:47:20.639  5606  5652 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
11-28 17:47:20.645  5606  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-57,5,main], id: 57
11-28 17:47:20.646  5606  5652 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-28 17:47:20.646  5606  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-28 17:47:20.646  5606  5652 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-28 17:47:20.647  5606  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 5
11-28 17:47:20.650  5606  5652 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
11-28 17:47:20.655  5606  5652 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
11-28 17:47:20.656  5606  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-57,5,main], id: 57
11-28 17:47:20.657  5606  5652 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
11-28 17:47:20.657  5606  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
11-28 17:47:20.657  5606  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
11-28 17:47:20.659  5606  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
11-28 17:47:20.659  5606  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-57,5,main], id: 57
11-28 17:47:20.661  5606  5652 D BluetoothAdapter: STATE_ON
11-28 17:47:20.666  5698  5709 D BtGatt.GattService: registerClient() - UUID=542b851a-01c5-41ad-9022-c827af250bd3
11-28 17:47:20.667  5698  5714 D BtGatt.GattService: onClientRegistered() - UUID=542b851a-01c5-41ad-9022-c827af250bd3, clientIf=5
11-28 17:47:20.667  5606  5616 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
11-28 17:47:20.668  5698  5734 D BtGatt.GattService: start scan with filters
,11-28 17:47:20.671  5606  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
11-28 17:47:20.671  5698  5717 D BtGatt.ScanManager: handling starting scan
11-28 17:47:20.671  5606  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-57,5,main], id: 57
11-28 17:47:20.671  5606  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
11-28 17:47:20.672  5606  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-57,5,main], id: 57
11-28 17:47:20.673  5606  5652 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-28 17:47:20.673  5606  5606 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-28 17:47:20.673  5606  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-28 17:47:20.673  5606  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
11-28 17:47:20.673  5606  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-28 17:47:20.673  5606  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-28 17:47:20.673  5606  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
11-28 17:47:20.673  5606  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-28 17:47:20.673  5606  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING] Current thread: Thread[main,5,main], id: 1
11-28 17:47:20.673  5698  5717 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ef81e9a
11-28 17:47:20.674  5606  5652 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-28 17:47:20.674  5606  5652 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
11-28 17:47:20.679  5606  5652 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
11-28 17:47:20.679  5606  5652 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
11-28 17:47:20.679  5606  5652 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
11-28 17:47:20.679  5606  5652 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
11-28 17:47:20.679  5606  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-28 17:47:20.680  5698  5714 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
11-28 17:47:20.680  5698  5714 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-28 17:47:20.681  5698  5717 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
11-28 17:47:20.682  5606  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-28 17:47:20.682  5606  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-28 17:47:20.682  5606  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-28 17:47:20.682  5606  5606 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
11-28 17:47:20.687  5698  5714 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
11-28 17:47:20.687  5698  5714 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-28 17:47:20.688  5698  5717 D BtGatt.ScanManager: Starting BLE batch scan
11-28 17:47:20.688  5698  5717 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
11-28 17:47:20.697  5698  5714 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
11-28 17:47:20.698  5698  5714 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-28 17:47:20.703  5698  5714 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
11-28 17:47:20.703  5698  5714 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-28 17:47:20.792   928  2978 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,11-28 17:47:21.183  5606  5606 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,11-28 17:47:21.183  5606  5606 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
11-28 17:47:21.184  5606  5606 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,11-28 17:47:22.576   928  2978 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-28 17:47:22.786   544   544 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
11-28 17:47:22.786   544   544 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,11-28 17:47:23.681  5606  5652 I io.jxcore.node.StartStopOperationHandlerTest: Starting test: testExecuteStartOperation
,11-28 17:47:23.682  5606  5652 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 6
11-28 17:47:23.682  5606  5652 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 5 -> 6
,11-28 17:47:23.683  5606  5652 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-57,5,main], id: 57
11-28 17:47:23.683  5606  5652 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-57,5,main], id: 57
11-28 17:47:23.683  5606  5652 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-57,5,main], id: 57
,11-28 17:47:23.683  5606  5652 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
11-28 17:47:23.683  5606  5652 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Manufacturer ID: 7413
11-28 17:47:23.683  5606  5652 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad length and type: 533
11-28 17:47:23.683  5606  5652 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad extra information: 6
11-28 17:47:23.683  5606  5652 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
11-28 17:47:23.683  5606  5652 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 2
11-28 17:47:23.683  5606  5652 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 3
11-28 17:47:23.683  5606  5652 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 2
11-28 17:47:23.683  5606  5652 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
11-28 17:47:23.683  5606  5652 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Current thread: Thread[Thread-57,5,main], id: 57
11-28 17:47:23.684  5606  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 6
11-28 17:47:23.684  5606  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: advertiserWasStarted false Current thread: Thread[Thread-57,5,main], id: 57
,11-28 17:47:23.684  5606  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-57,5,main], id: 57
11-28 17:47:23.684  5606  5652 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-28 17:47:23.684  5606  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-28 17:47:23.685  5606  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: scannerWasStarted true Current thread: Thread[Thread-57,5,main], id: 57
,11-28 17:47:23.686  5606  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: stop scanner Current thread: Thread[Thread-57,5,main], id: 57
11-28 17:47:23.688  5606  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-57,5,main], id: 57
,11-28 17:47:23.690  5606  5652 D BluetoothAdapter: STATE_ON
11-28 17:47:23.691  5698  5734 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
11-28 17:47:23.691  5606  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
,11-28 17:47:23.696  5698  5717 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-28 17:47:23.696  5606  5652 D BluetoothAdapter: STATE_ON
11-28 17:47:23.698  5698  5726 D BtGatt.GattService: stopScan() - queue size =1
11-28 17:47:23.699  5698  5709 D BtGatt.GattService: unregisterClient() - clientIf=5
11-28 17:47:23.700  5606  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-28 17:47:23.700  5606  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-57,5,main], id: 57
,11-28 17:47:23.700  5606  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,11-28 17:47:23.700  5606  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-57,5,main], id: 57
11-28 17:47:23.701  5606  5652 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,11-28 17:47:23.701  5606  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: start scanner Current thread: Thread[Thread-57,5,main], id: 57
11-28 17:47:23.701  5606  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-57,5,main], id: 57
11-28 17:47:23.701  5606  5652 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
11-28 17:47:23.701  5606  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
11-28 17:47:23.701  5606  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
11-28 17:47:23.702  5606  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
11-28 17:47:23.702  5606  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-57,5,main], id: 57
11-28 17:47:23.703  5698  5698 D BtGatt.ScanManager: awakened up at time 114702
11-28 17:47:23.704  5606  5652 D BluetoothAdapter: STATE_ON
11-28 17:47:23.709  5698  5708 D BtGatt.GattService: registerClient() - UUID=bf780f57-f860-4baf-9b8e-7a97c141f686
,11-28 17:47:23.711  5698  5714 D BtGatt.GattService: onClientRegistered() - UUID=bf780f57-f860-4baf-9b8e-7a97c141f686, clientIf=5
,11-28 17:47:23.712  5606  5616 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
11-28 17:47:23.712  5698  5726 D BtGatt.GattService: start scan with filters
,11-28 17:47:23.717  5606  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
,11-28 17:47:23.717  5606  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-57,5,main], id: 57
11-28 17:47:23.717  5606  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
11-28 17:47:23.717  5606  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-57,5,main], id: 57
11-28 17:47:23.717  5606  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: start scanner started = true Current thread: Thread[Thread-57,5,main], id: 57
11-28 17:47:23.717  5606  5606 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-28 17:47:23.718  5606  5652 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
11-28 17:47:23.718  5606  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-28 17:47:23.718  5606  5652 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
11-28 17:47:23.718  5606  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
,11-28 17:47:23.718  5606  5652 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
11-28 17:47:23.718  5606  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
11-28 17:47:23.718  5606  5652 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-28 17:47:23.718  5606  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-28 17:47:23.718  5606  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-28 17:47:23.719  5606  5652 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
11-28 17:47:23.719  5606  5652 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
11-28 17:47:23.719  5606  5652 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
,11-28 17:47:23.719  5606  5652 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
11-28 17:47:23.720  5606  5652 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
11-28 17:47:23.720  5606  5832 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
11-28 17:47:23.720  5606  5652 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: true
11-28 17:47:23.720  5606  5606 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
11-28 17:47:23.720  5606  5832 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-28 17:47:23.721  5606  5652 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-28 17:47:23.721  5606  5652 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,11-28 17:47:23.722  5606  5832 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
11-28 17:47:23.722  5698  5714 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=5
11-28 17:47:23.722  5698  5714 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-28 17:47:23.718  5726  5726 W Binder_3: type=1400 audit(0.0:126): avc: denied { ioctl } for path="socket:[31533]" dev="sockfs" ino=31533 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-28 17:47:23.718  5726  5726 W Binder_3: type=1400 audit(0.0:127): avc: denied { ioctl } for path="socket:[31533]" dev="sockfs" ino=31533 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,11-28 17:47:23.722  5698  5714 D BtGatt.GattService: current time is 114721994012
,11-28 17:47:23.723  5698  5714 D BtGatt.GattService: Batch record : [116, -43, -111, -91, -20, -29, 1, -128, -80, 40, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 35, 97, 126, -92, 22, -56, 1, -128, -82, 34, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 37, -47, 14, -113, 116, -46, 1, -128, -82, 32, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 71, -122, -77, 84, 69, -12, 1, -128, -83, 43, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, -46, -4, -117, 6, 105, -37, 1, -128, -84, 38, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
11-28 17:47:23.724  5698  5714 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
11-28 17:47:23.725  5698  5714 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
11-28 17:47:23.725  5698  5714 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
11-28 17:47:23.725  5698  5714 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
11-28 17:47:23.725  5698  5714 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
,11-28 17:47:23.729  5606  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser : Current thread: Thread[Thread-57,5,main], id: 57
11-28 17:47:23.730  5606  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Current thread: Thread[Thread-57,5,main], id: 57
11-28 17:47:23.730  5606  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-57,5,main], id: 57
11-28 17:47:23.730  5606  5652 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
11-28 17:47:23.730  5606  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: createAdvertiseDataToServiceData 
11-28 17:47:23.730  5606  5652 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-28 17:47:23.730  5606  5652 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 06 60 83 34 25 D7 D4
11-28 17:47:23.730  5698  5714 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
,11-28 17:47:23.730  5698  5714 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-28 17:47:23.730  5606  5652 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[6, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-28 17:47:23.730  5698  5717 D BtGatt.ScanManager: stopping BLe Batch
11-28 17:47:23.730  5606  5652 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: created AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[6, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-28 17:47:23.730  5606  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: Current thread: Thread[Thread-57,5,main], id: 57
11-28 17:47:23.730  5606  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: was started = false
11-28 17:47:23.731  5606  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: advertiseData = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[6, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-28 17:47:23.731  5606  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData finished: Current thread: Thread[Thread-57,5,main], id: 57
,11-28 17:47:23.731  5606  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = NOT_STARTEDCurrent thread: Thread[Thread-57,5,main], id: 57
,11-28 17:47:23.731  5606  5652 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... adv data = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[6, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]Current thread: Thread[Thread-57,5,main], id: 57
11-28 17:47:23.732  5606  5652 D BluetoothAdapter: STATE_ON
11-28 17:47:23.734  5698  5708 D BtGatt.GattService: registerClient() - UUID=0416eb29-9785-4dad-b861-2f28532b6892
11-28 17:47:23.735  5698  5714 D BtGatt.GattService: onClientRegistered() - UUID=0416eb29-9785-4dad-b861-2f28532b6892, clientIf=6
11-28 17:47:23.735  5606  5616 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
,11-28 17:47:23.736  5698  5716 D BtGatt.AdvertiseManager: message : 0
,11-28 17:47:23.736  5698  5714 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
11-28 17:47:23.736  5698  5714 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-28 17:47:23.736  5698  5717 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-28 17:47:23.740  5698  5716 D BtGatt.AdvertiseManager: starting multi advertising
,11-28 17:47:23.741  5698  5714 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-28 17:47:23.741  5698  5714 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-28 17:47:23.744  5698  5717 D BtGatt.ScanManager: handling starting scan
,11-28 17:47:23.751  5698  5714 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0
,11-28 17:47:23.755  5698  5714 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
11-28 17:47:23.755  5698  5714 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-28 17:47:23.755  5698  5717 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,11-28 17:47:23.759  5698  5714 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0
,11-28 17:47:23.760  5606  5652 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment Current thread: Thread[Thread-57,5,main], id: 57
,11-28 17:47:23.760  5606  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTINGCurrent thread: Thread[Thread-57,5,main], id: 57
11-28 17:47:23.760  5606  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
11-28 17:47:23.760  5606  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged default (no call to listener). Current thread: Thread[Thread-57,5,main], id: 57
11-28 17:47:23.760  5606  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-57,5,main], id: 57
11-28 17:47:23.760  5606  5652 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[Thread-57,5,main], id: 57
11-28 17:47:23.760  5606  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[Thread-57,5,main], id: 57
,11-28 17:47:23.760  5606  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser started = true Current thread: Thread[Thread-57,5,main], id: 57
11-28 17:47:23.760  5606  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser: advertiser is started. Current thread: Thread[Thread-57,5,main], id: 57
11-28 17:47:23.760  5606  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-57,5,main], id: 57
11-28 17:47:23.761  5606  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-57,5,main], id: 57
11-28 17:47:23.761  5606  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Already running
11-28 17:47:23.761  5606  5652 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser: adv = true, disc = true
11-28 17:47:23.761  5606  5652 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-28 17:47:23.762  5606  5652 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-28 17:47:23.762  5606  5652 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
11-28 17:47:23.763  5698  5714 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
11-28 17:47:23.763  5698  5714 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-28 17:47:23.764  5698  5717 D BtGatt.ScanManager: Starting BLE batch scan
11-28 17:47:23.764  5698  5717 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,11-28 17:47:23.764  5606  5652 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
11-28 17:47:23.765  5606  5652 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
11-28 17:47:23.765  5606  5652 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
,11-28 17:47:23.771  5606  5606 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
,11-28 17:47:23.771  5606  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess : Current thread: Thread[main,5,main], id: 1
11-28 17:47:23.771  5606  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNINGCurrent thread: Thread[main,5,main], id: 1
11-28 17:47:23.771  5606  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
11-28 17:47:23.771  5606  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  true. Current thread: Thread[main,5,main], id: 1
11-28 17:47:23.771  5606  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[main,5,main], id: 1
11-28 17:47:23.771  5606  5606 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
,11-28 17:47:23.771  5606  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-28 17:47:23.771  5606  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING, ADVERTISING]
11-28 17:47:23.771  5606  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
11-28 17:47:23.771  5606  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-28 17:47:23.772  5606  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [SCANNING, ADVERTISING]Current thread: Thread[main,5,main], id: 1
11-28 17:47:23.772  5606  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-28 17:47:23.772  5606  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [SCANNING, ADVERTISING] Current thread: Thread[main,5,main], id: 1
11-28 17:47:23.772  5606  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-28 17:47:23.772  5698  5714 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,11-28 17:47:23.772  5698  5714 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-28 17:47:23.774  5606  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
,11-28 17:47:23.774  5606  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: true
11-28 17:47:23.775  5606  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-28 17:47:23.775  5606  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-28 17:47:23.775  5606  5606 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: true
,11-28 17:47:23.776  5698  5714 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
11-28 17:47:23.776  5698  5714 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-28 17:47:24.276  5606  5606 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: true
,11-28 17:47:24.276  5606  5606 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
11-28 17:47:24.276  5606  5606 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,11-28 17:47:25.605   928  2978 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-28 17:47:26.769  5606  5652 I io.jxcore.node.StartStopOperationHandlerTest: Starting test: testConstructor
,11-28 17:47:26.769  5606  5652 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,11-28 17:47:26.769  5606  5652 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
11-28 17:47:26.769  5606  5652 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
11-28 17:47:26.770  5606  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
11-28 17:47:26.770  5606  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,11-28 17:47:26.770  5606  5832 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
11-28 17:47:26.770  5606  5832 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
11-28 17:47:26.770  5606  5652 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
11-28 17:47:26.771  5606  5832 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
,11-28 17:47:26.771  5606  5652 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
11-28 17:47:26.771  5606  5652 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,11-28 17:47:26.771  5606  5606 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
11-28 17:47:26.771  5606  5652 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1c9cf28 removed from the list
11-28 17:47:26.771  5606  5606 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
11-28 17:47:26.771  5606  5652 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-28 17:47:26.771  5606  5652 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-28 17:47:26.771  5606  5606 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-28 17:47:26.772  5606  5652 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-57,5,main], id: 57
11-28 17:47:26.772  5606  5652 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
11-28 17:47:26.772  5606  5652 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-28 17:47:26.772  5606  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-57,5,main], id: 57
11-28 17:47:26.773  5606  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-57,5,main], id: 57
11-28 17:47:26.773  5606  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-57,5,main], id: 57
,11-28 17:47:26.773  5606  5652 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
11-28 17:47:26.773  5606  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-57,5,main], id: 57
,11-28 17:47:26.777  5606  5652 D BluetoothAdapter: STATE_ON
11-28 17:47:26.778  5698  5709 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
,11-28 17:47:26.778  5606  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-28 17:47:26.780  5698  5717 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
11-28 17:47:26.781  5606  5652 D BluetoothAdapter: STATE_ON
11-28 17:47:26.782  5698  5734 D BtGatt.GattService: stopScan() - queue size =1
11-28 17:47:26.784  5698  5708 D BtGatt.GattService: unregisterClient() - clientIf=5
11-28 17:47:26.785  5606  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,11-28 17:47:26.785  5606  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-57,5,main], id: 57
11-28 17:47:26.785  5606  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
11-28 17:47:26.786  5606  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-57,5,main], id: 57
,11-28 17:47:26.786  5606  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-57,5,main], id: 57
11-28 17:47:26.786  5606  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-57,5,main], id: 57
11-28 17:47:26.786  5606  5652 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
11-28 17:47:26.786  5606  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-57,5,main], id: 57
11-28 17:47:26.787  5698  5698 D BtGatt.ScanManager: awakened up at time 117786
11-28 17:47:26.789  5698  5716 D BtGatt.AdvertiseManager: message : 1
11-28 17:47:26.790  5698  5716 D BtGatt.AdvertiseManager: stop advertise for client 6
,11-28 17:47:26.803  5698  5714 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
,11-28 17:47:26.803  5698  5714 D BtGatt.GattService: Client app is not null!
,11-28 17:47:26.805  5698  5708 D BtGatt.GattService: unregisterClient() - clientIf=6
,11-28 17:47:26.806  5606  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,11-28 17:47:26.806  5606  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTEDCurrent thread: Thread[Thread-57,5,main], id: 57
11-28 17:47:26.806  5606  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
11-28 17:47:26.807  5606  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  false. Current thread: Thread[Thread-57,5,main], id: 57
,11-28 17:47:26.807  5606  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-57,5,main], id: 57
11-28 17:47:26.807  5606  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-57,5,main], id: 57
11-28 17:47:26.807  5606  5652 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-28 17:47:26.807  5606  5652 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-28 17:47:26.808  5606  5652 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
11-28 17:47:26.809  5606  5652 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
11-28 17:47:26.811  5606  5652 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
11-28 17:47:26.811  5606  5652 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-28 17:47:26.811  5606  5652 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
11-28 17:47:26.811  5606  5652 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
11-28 17:47:26.811  5606  5652 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fb9441 removed from the list
11-28 17:47:26.811  5606  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-28 17:47:26.811  5606  5652 D io.jxcore.node.ConnectivityMonitor: stop
11-28 17:47:26.811  5606  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-28 17:47:26.812  5606  5606 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-28 17:47:26.812  5606  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-28 17:47:26.812  5606  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
,11-28 17:47:26.812  5606  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING, ADVERTISING]
11-28 17:47:26.812  5606  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
,11-28 17:47:26.812  5606  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING, ADVERTISING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-28 17:47:26.812  5606  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-28 17:47:26.813  5606  5606 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-28 17:47:26.813  5606  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
,11-28 17:47:26.813  5606  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-28 17:47:26.813  5606  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-28 17:47:26.813  5606  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-28 17:47:26.813  5606  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-28 17:47:26.813  5606  5606 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,11-28 17:47:26.813  5606  5652 I io.jxcore.node.StartStopOperationTest: Starting test: testIsTargetState
11-28 17:47:26.813  5606  5652 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
11-28 17:47:26.813  5606  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING, ADVERTISING] -> [NOT_STARTED] Current thread: Thread[main,5,main], id: 1
11-28 17:47:26.813  5606  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-28 17:47:26.813  5606  5652 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
11-28 17:47:26.814  5606  5652 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
11-28 17:47:26.814  5606  5652 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-28 17:47:26.814  5606  5652 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
11-28 17:47:26.814  5606  5652 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
11-28 17:47:26.815  5606  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-28 17:47:26.815  5606  5652 I io.jxcore.node.StartStopOperationTest: Starting test: testCreateStartOperation
11-28 17:47:26.815  5606  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-28 17:47:26.815  5606  5606 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
,11-28 17:47:26.817  5606  5652 I io.jxcore.node.StartStopOperationTest: Starting test: testGetShouldStartOrStopListeningToAdvertisementsOnly
11-28 17:47:26.819  5606  5652 I io.jxcore.node.StartStopOperationTest: Starting test: testIsStartOperation
,11-28 17:47:26.820  5606  5652 I io.jxcore.node.StartStopOperationTest: Starting test: testToString
11-28 17:47:26.821  5606  5652 I io.jxcore.node.StartStopOperationTest: Starting test: testCreateStopOperation
11-28 17:47:26.823  5606  5652 I io.jxcore.node.StartStopOperationTest: Starting test: testSetOperationExecutedTime
11-28 17:47:26.824  5606  5652 I io.jxcore.node.StartStopOperationTest: Starting test: testGetOperationExecutedTime
11-28 17:47:26.825  5606  5652 I io.jxcore.node.StartStopOperationTest: Starting test: testGetCallback
,11-28 17:47:26.832  5698  5714 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=5
,11-28 17:47:26.832  5698  5714 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-28 17:47:26.832  5698  5714 D BtGatt.GattService: current time is 117832002440
11-28 17:47:26.833  5698  5714 D BtGatt.GattService: Batch record : [35, 97, 126, -92, 22, -56, 1, -128, -82, 58, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 81, 34, 97, 112, -14, -5, 1, -128, -87, 45, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 116, -43, -111, -91, -20, -29, 1, -128, -78, 25, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 71, -122, -77, 84, 69, -12, 1, -128, -88, 24, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, -46, -4, -117, 6, 105, -37, 1, -128, -80, 23, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
11-28 17:47:26.833  5698  5714 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
11-28 17:47:26.833  5698  5714 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
,11-28 17:47:26.833  5698  5714 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
11-28 17:47:26.834  5698  5714 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
11-28 17:47:26.834  5698  5714 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
,11-28 17:47:26.841  5698  5714 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
,11-28 17:47:26.841  5698  5714 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-28 17:47:26.841  5698  5717 D BtGatt.ScanManager: stopping BLe Batch
,11-28 17:47:26.847  5698  5714 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,11-28 17:47:26.847  5698  5714 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-28 17:47:26.848  5698  5717 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-28 17:47:26.855  5698  5714 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-28 17:47:26.855  5698  5714 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-28 17:47:27.313  5606  5606 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-28 17:47:27.753   928  2978 D ConnectivityService: handlePromptUnvalidated 101
,11-28 17:47:27.787   544   544 I ServiceManager: Waiting for service AtCmdFwd...
,11-28 17:47:28.788   544   544 I ServiceManager: Waiting for service AtCmdFwd...
,11-28 17:47:28.829  5606  5652 I StreamCopyingThreadTest: Starting test: testCopyDataAndCloseConnection
,11-28 17:47:28.977  5606  5834 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 186, name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
11-28 17:47:28.977  5606  5834 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-28 17:47:29.242   928  2976 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 7, 9 -> obsolete
,11-28 17:47:29.768  5606  5834 W !!      : call onHalfStreamCopied
,11-28 17:47:29.769  5606  5834 I testCopyDataAndClose: closing input stream
,11-28 17:47:29.789   544   544 I ServiceManager: Waiting for service AtCmdFwd...
,11-28 17:47:30.542  5606  5834 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 186, thread name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
11-28 17:47:30.542  5606  5834 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-28 17:47:30.542  5606  5834 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
11-28 17:47:30.542  5606  5834 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
11-28 17:47:30.542  5606  5834 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
,11-28 17:47:30.542  5606  5834 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
,11-28 17:47:30.542  5606  5834 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
11-28 17:47:30.542  5606  5834 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
,11-28 17:47:30.542  5606  5834 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
11-28 17:47:30.542  5606  5834 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 186, name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
11-28 17:47:30.542  5606  5834 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 20971520 and the total number of bytes written 20971520
,11-28 17:47:30.790   544   544 I ServiceManager: Waiting for service AtCmdFwd...
,11-28 17:47:30.810   928  2976 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 8, 9 -> obsolete
,11-28 17:47:31.791   544   544 I ServiceManager: Waiting for service AtCmdFwd...
,11-28 17:47:32.791   544   544 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,11-28 17:47:34.856  5606  5652 I StreamCopyingThreadTest: Starting test: testCopyBigData
,11-28 17:47:34.947  5606  5835 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 189, name: testCopyBigData thread). Connection data: Peer properties: [null null].
11-28 17:47:34.947  5606  5835 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-28 17:47:36.567  5606  5835 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 189, thread name: testCopyBigData thread). Connection data: Peer properties: [null null].
11-28 17:47:36.567  5606  5835 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-28 17:47:36.567  5606  5835 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
11-28 17:47:36.567  5606  5835 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
11-28 17:47:36.567  5606  5835 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
11-28 17:47:36.567  5606  5835 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
11-28 17:47:36.567  5606  5835 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
11-28 17:47:36.567  5606  5835 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
11-28 17:47:36.567  5606  5835 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
,11-28 17:47:36.567  5606  5835 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 189, name: testCopyBigData thread). Connection data: Peer properties: [null null].
11-28 17:47:36.567  5606  5835 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 20971520 and the total number of bytes written 20971520
,11-28 17:47:37.793   544   544 I ServiceManager: Waiting for service AtCmdFwd...
,11-28 17:47:38.794   544   544 I ServiceManager: Waiting for service AtCmdFwd...
,11-28 17:47:39.796   544   544 I ServiceManager: Waiting for service AtCmdFwd...
,11-28 17:47:40.713  5606  5652 I StreamCopyingThreadTest: Starting test: testRunNotify
,11-28 17:47:40.715  5606  5836 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 191, name: My test thread name). Connection data: Peer properties: [null null].
11-28 17:47:40.715  5606  5836 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-28 17:47:40.716  5606  5836 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 191, thread name: My test thread name). Connection data: Peer properties: [null null].
11-28 17:47:40.716  5606  5836 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
11-28 17:47:40.717  5606  5836 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
11-28 17:47:40.717  5606  5836 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-28 17:47:40.717  5606  5836 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
,11-28 17:47:40.717  5606  5836 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
11-28 17:47:40.717  5606  5836 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
,11-28 17:47:40.718  5606  5836 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
11-28 17:47:40.718  5606  5836 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
,11-28 17:47:40.719  5606  5836 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 191, name: My test thread name). Connection data: Peer properties: [null null].
11-28 17:47:40.719  5606  5836 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 22
,11-28 17:47:40.720  5606  5652 I StreamCopyingThreadTest: Starting test: testSetBufferSize
11-28 17:47:40.721  5606  5652 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
11-28 17:47:40.722  5606  5652 I StreamCopyingThreadTest: Starting test: testRunWithException
11-28 17:47:40.724  5606  5837 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 195, name: My test thread name). Connection data: Peer properties: [null null].
11-28 17:47:40.724  5606  5837 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-28 17:47:40.724  5606  5837 E io.jxcore.node.StreamCopyingThread: Failed to write to the output stream (thread ID: 195, thread name: My test thread name): Test exception.
11-28 17:47:40.725  5606  5837 D io.jxcore.node.StreamCopyingThread: onStreamCopyError (ID: 195, name: My test thread name). Connection data: Peer properties: [null null].
11-28 17:47:40.725  5606  5837 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
11-28 17:47:40.725  5606  5837 D io.jxcore.node.StreamCopyingThread: number of bytes read = 22
11-28 17:47:40.725  5606  5837 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 195, name: My test thread name). Connection data: Peer properties: [null null].
11-28 17:47:40.725  5606  5837 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
,11-28 17:47:40.729  5606  5652 I jxcore-log: 2016-11-28 16:47:40 - DEBUG UnitTest_app: 'Running unit tests'
11-28 17:47:40.729  5606  5652 I jxcore-log: 
,11-28 17:47:40.730  5606  5652 I jxcore-log: *Native tests were executed*
11-28 17:47:40.730  5606  5652 I jxcore-log: 
11-28 17:47:40.730  5606  5652 I jxcore-log: Total number of executed tests:  81
11-28 17:47:40.730  5606  5652 I jxcore-log: 
,11-28 17:47:40.730  5606  5652 I jxcore-log: Number of passed tests:  79
11-28 17:47:40.730  5606  5652 I jxcore-log: 
11-28 17:47:40.730  5606  5652 I jxcore-log: Number of failed tests:  0
11-28 17:47:40.730  5606  5652 I jxcore-log: 
11-28 17:47:40.730  5606  5652 I jxcore-log: Number of ignored tests:  2
11-28 17:47:40.730  5606  5652 I jxcore-log: 
,11-28 17:47:40.730  5606  5652 I jxcore-log: Total duration:  34809
11-28 17:47:40.730  5606  5652 I jxcore-log: 
11-28 17:47:40.733  5606  5652 I jxcore-log: 2016-11-28 16:47:40 - DEBUG UnitTest_app: 'Unit Test app is loaded'
11-28 17:47:40.733  5606  5652 I jxcore-log: 
,11-28 17:47:40.738  5606  5652 I jxcore-log: 2016-11-28 16:47:40 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
11-28 17:47:40.738  5606  5652 I jxcore-log: 
11-28 17:47:40.738  5606  5652 I jxcore-log: 2016-11-28 16:47:40 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-28 17:47:40.738  5606  5652 I jxcore-log: 
11-28 17:47:40.739  5606  5652 I jxcore-log: 2016-11-28 16:47:40 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
11-28 17:47:40.739  5606  5652 I jxcore-log: 
11-28 17:47:40.739  5606  5652 I jxcore-log: 2016-11-28 16:47:40 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-28 17:47:40.739  5606  5652 I jxcore-log: 
11-28 17:47:40.740  5606  5652 I jxcore-log: 2016-11-28 16:47:40 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
11-28 17:47:40.740  5606  5652 I jxcore-log: 
11-28 17:47:40.741  5606  5652 I jxcore-log: 2016-11-28 16:47:40 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH"})'
11-28 17:47:40.741  5606  5652 I jxcore-log: 
11-28 17:47:40.741  5606  5652 I jxcore-log: 2016-11-28 16:47:40 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-28 17:47:40.741  5606  5652 I jxcore-log: 
11-28 17:47:40.741  5606  5652 I jxcore-log: 2016-11-28 16:47:40 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
11-28 17:47:40.741  5606  5652 I jxcore-log: 
11-28 17:47:40.742  5606  5652 I jxcore-log: 2016-11-28 16:47:40 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH"})'
11-28 17:47:40.742  5606  5652 I jxcore-log: 
11-28 17:47:40.742  5606  5652 I jxcore-log: 2016-11-28 16:47:40 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-28 17:47:40.742  5606  5652 I jxcore-log: 
11-28 17:47:40.742  5606  5652 I jxcore-log: 2016-11-28 16:47:40 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
11-28 17:47:40.742  5606  5652 I jxcore-log: 
11-28 17:47:40.742  5606  5652 I jxcore-log: 2016-11-28 16:47:40 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH"})'
11-28 17:47:40.742  5606  5652 I jxcore-log: 
,11-28 17:47:40.742  5606  5652 I jxcore-log: 2016-11-28 16:47:40 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-28 17:47:40.742  5606  5652 I jxcore-log: 
11-28 17:47:40.743  5606  5652 I jxcore-log: 2016-11-28 16:47:40 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-28 17:47:40.743  5606  5652 I jxcore-log: 
,11-28 17:47:40.743  5606  5652 I jxcore-log: 2016-11-28 16:47:40 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-28 17:47:40.743  5606  5652 I jxcore-log: 
,11-28 17:47:40.743  5606  5652 I jxcore-log: 2016-11-28 16:47:40 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
11-28 17:47:40.743  5606  5652 I jxcore-log: 
11-28 17:47:40.744  5606  5652 I jxcore-log: 2016-11-28 16:47:40 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-28 17:47:40.744  5606  5652 I jxcore-log: 
11-28 17:47:40.744  5606  5652 I jxcore-log: 2016-11-28 16:47:40 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-28 17:47:40.744  5606  5652 I jxcore-log: 
,11-28 17:47:40.744  5606  5652 I jxcore-log: 2016-11-28 16:47:40 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-28 17:47:40.744  5606  5652 I jxcore-log: 
11-28 17:47:40.744  5606  5652 I jxcore-log: 2016-11-28 16:47:40 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
11-28 17:47:40.744  5606  5652 I jxcore-log: 
,11-28 17:47:40.744  5606  5652 I jxcore-log: 2016-11-28 16:47:40 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-28 17:47:40.744  5606  5652 I jxcore-log: 
11-28 17:47:40.745  5606  5652 I jxcore-log: 2016-11-28 16:47:40 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
11-28 17:47:40.745  5606  5652 I jxcore-log: 
11-28 17:47:40.745  5606  5652 I jxcore-log: 2016-11-28 16:47:40 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-28 17:47:40.745  5606  5652 I jxcore-log: 
11-28 17:47:40.745  5606  5652 I jxcore-log: 2016-11-28 16:47:40 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
11-28 17:47:40.745  5606  5652 I jxcore-log: 
,11-28 17:47:40.745  5606  5652 I jxcore-log: 2016-11-28 16:47:40 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-28 17:47:40.745  5606  5652 I jxcore-log: 
11-28 17:47:40.746  5606  5652 I jxcore-log: 2016-11-28 16:47:40 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
11-28 17:47:40.746  5606  5652 I jxcore-log: 
11-28 17:47:40.746  5606  5652 I jxcore-log: 2016-11-28 16:47:40 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-28 17:47:40.746  5606  5652 I jxcore-log: 
11-28 17:47:40.746  5606  5652 I jxcore-log: 2016-11-28 16:47:40 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
11-28 17:47:40.746  5606  5652 I jxcore-log: 
11-28 17:47:40.746  5606  5652 I jxcore-log: 2016-11-28 16:47:40 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH"})'
11-28 17:47:40.746  5606  5652 I jxcore-log: 
,11-28 17:47:40.747  5606  5652 I jxcore-log: 2016-11-28 16:47:40 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-28 17:47:40.747  5606  5652 I jxcore-log: 
11-28 17:47:40.748  5606  5652 I jxcore-log: 2016-11-28 16:47:40 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
11-28 17:47:40.748  5606  5652 I jxcore-log: 
11-28 17:47:40.748  5606  5652 I jxcore-log: 2016-11-28 16:47:40 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH"})'
11-28 17:47:40.748  5606  5652 I jxcore-log: 
11-28 17:47:40.748  5606  5652 I jxcore-log: 2016-11-28 16:47:40 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-28 17:47:40.748  5606  5652 I jxcore-log: 
,11-28 17:47:40.749  5606  5652 I jxcore-log: 2016-11-28 16:47:40 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
11-28 17:47:40.749  5606  5652 I jxcore-log: 
11-28 17:47:40.749  5606  5652 I jxcore-log: 2016-11-28 16:47:40 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH"})'
11-28 17:47:40.749  5606  5652 I jxcore-log: 
11-28 17:47:40.749  5606  5652 I jxcore-log: 2016-11-28 16:47:40 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-28 17:47:40.749  5606  5652 I jxcore-log: 
11-28 17:47:40.749  5606  5652 I jxcore-log: 2016-11-28 16:47:40 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-28 17:47:40.749  5606  5652 I jxcore-log: 
,11-28 17:47:40.749  5606  5652 I jxcore-log: 2016-11-28 16:47:40 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-28 17:47:40.749  5606  5652 I jxcore-log: 
11-28 17:47:40.751  5606  5606 D SystemWebChromeClient: file:///android_asset/www/js/thali_main.js: Line 68 : UIApp is all set and ready!
11-28 17:47:40.751  5606  5606 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
,11-28 17:47:40.754  5606  5652 I jxcore-log: 2016-11-28 16:47:40 - DEBUG UnitTest_app: 'My device name is: Huawei-Nexus 6P'
11-28 17:47:40.754  5606  5652 I jxcore-log: 
11-28 17:47:40.755  5606  5652 I jxcore-log: 2016-11-28 16:47:40 - WARN testUtils: 'myNameCallback not set!'
11-28 17:47:40.755  5606  5652 I jxcore-log: 
,11-28 17:47:40.797   544   544 I ServiceManager: Waiting for service AtCmdFwd...
,11-28 17:47:41.798   544   544 I ServiceManager: Waiting for service AtCmdFwd...
,11-28 17:47:42.798   544   544 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,11-28 17:47:42.813  5606  5652 I jxcore-log: 2016-11-28 16:47:42 - INFO runTests: 'Starting tests. Network type: WIFI. Platform: android'
11-28 17:47:42.813  5606  5652 I jxcore-log: 
,11-28 17:47:42.815  5606  5652 I jxcore-log: 2016-11-28 16:47:42 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js'
11-28 17:47:42.815  5606  5652 I jxcore-log: 
,11-28 17:47:43.157  5606  5652 I jxcore-log: 2016-11-28 16:47:43 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js'
11-28 17:47:43.157  5606  5652 I jxcore-log: 
,11-28 17:47:43.169  5606  5652 I jxcore-log: 2016-11-28 16:47:43 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManager.js'
11-28 17:47:43.169  5606  5652 I jxcore-log: 
,11-28 17:47:43.524   928  5806 D NetlinkSocketObserver: NeighborEvent{elapsedMs=134523, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,11-28 17:47:43.728   928  2978 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-28 17:47:44.272  5606  5652 I jxcore-log: 2016-11-28 16:47:44 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js'
11-28 17:47:44.272  5606  5652 I jxcore-log: 
,11-28 17:47:44.437  5606  5652 I jxcore-log: 2016-11-28 16:47:44 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js'
11-28 17:47:44.437  5606  5652 I jxcore-log: 
,11-28 17:47:44.443  5606  5652 I jxcore-log: 2016-11-28 16:47:44 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testNativeMethod.js'
11-28 17:47:44.443  5606  5652 I jxcore-log: 
,11-28 17:47:44.455  5606  5652 I jxcore-log: 2016-11-28 16:47:44 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPouchDBCheckpointPlugin.js'
11-28 17:47:44.455  5606  5652 I jxcore-log: 
,11-28 17:47:44.901  3684  3859 I Keyboard.Facilitator.LanguageModelFlusher: run()
,11-28 17:47:44.901  3684  3859 I Keyboard.Facilitator: flushDynamicLanguageModels()
,11-28 17:47:44.933  3584  3584 I ConfigService: onCreate
,11-28 17:47:44.940  5606  5652 I jxcore-log: 2016-11-28 16:47:44 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPouchDBGenerator.js'
11-28 17:47:44.940  5606  5652 I jxcore-log: 
,11-28 17:47:44.981  5606  5652 I jxcore-log: 2016-11-28 16:47:44 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js'
11-28 17:47:44.981  5606  5652 I jxcore-log: 
,11-28 17:47:44.993  5606  5652 I jxcore-log: 2016-11-28 16:47:44 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js'
11-28 17:47:44.993  5606  5652 I jxcore-log: 
,11-28 17:47:44.997  5606  5652 I jxcore-log: 2016-11-28 16:47:44 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliManager.js'
11-28 17:47:44.997  5606  5652 I jxcore-log: 
,11-28 17:47:45.264  5606  5652 I jxcore-log: 2016-11-28 16:47:45 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliManagerCoordinated.js'
11-28 17:47:45.264  5606  5652 I jxcore-log: 
,11-28 17:47:45.390  5606  5652 I jxcore-log: 2016-11-28 16:47:45 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js'
11-28 17:47:45.390  5606  5652 I jxcore-log: 
,11-28 17:47:45.777  5606  5652 I jxcore-log: 2016-11-28 16:47:45 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js'
11-28 17:47:45.777  5606  5652 I jxcore-log: 
,11-28 17:47:45.784  5606  5652 I jxcore-log: 2016-11-28 16:47:45 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeAndroid.js'
11-28 17:47:45.784  5606  5652 I jxcore-log: 
,11-28 17:47:45.788  5606  5652 I jxcore-log: 2016-11-28 16:47:45 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeDiscoveryCoordinated.js'
11-28 17:47:45.788  5606  5652 I jxcore-log: 
,11-28 17:47:45.792  5606  5652 I jxcore-log: 2016-11-28 16:47:45 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js'
11-28 17:47:45.792  5606  5652 I jxcore-log: 
,11-28 17:47:45.797  5606  5652 I jxcore-log: 2016-11-28 16:47:45 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeiOS.js'
11-28 17:47:45.797  5606  5652 I jxcore-log: 
,11-28 17:47:45.835  5606  5652 I jxcore-log: 2016-11-28 16:47:45 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js'
11-28 17:47:45.835  5606  5652 I jxcore-log: 
,11-28 17:47:45.842  5606  5652 I jxcore-log: 2016-11-28 16:47:45 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js'
11-28 17:47:45.842  5606  5652 I jxcore-log: 
,11-28 17:47:45.870  5606  5652 I jxcore-log: 2016-11-28 16:47:45 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js'
11-28 17:47:45.870  5606  5652 I jxcore-log: 
,11-28 17:47:45.909  5606  5652 I jxcore-log: 2016-11-28 16:47:45 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js'
11-28 17:47:45.909  5606  5652 I jxcore-log: 
,11-28 17:47:45.916  5606  5652 I jxcore-log: 2016-11-28 16:47:45 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationLocal.js'
11-28 17:47:45.916  5606  5652 I jxcore-log: 
,11-28 17:47:45.923  5606  5652 I jxcore-log: 2016-11-28 16:47:45 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js'
11-28 17:47:45.923  5606  5652 I jxcore-log: 
,11-28 17:47:45.938  5606  5652 I jxcore-log: 2016-11-28 16:47:45 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js'
11-28 17:47:45.938  5606  5652 I jxcore-log: 
,11-28 17:47:45.953  5606  5652 I jxcore-log: 2016-11-28 16:47:45 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js'
11-28 17:47:45.953  5606  5652 I jxcore-log: 
,11-28 17:47:45.959  5606  5652 I jxcore-log: 2016-11-28 16:47:45 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolDefault.js'
11-28 17:47:45.959  5606  5652 I jxcore-log: 
,11-28 17:47:45.964  5606  5652 I jxcore-log: 2016-11-28 16:47:45 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js'
11-28 17:47:45.964  5606  5652 I jxcore-log: 
,11-28 17:47:45.978  5606  5652 I jxcore-log: 2016-11-28 16:47:45 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolOneAtATime.js'
11-28 17:47:45.978  5606  5652 I jxcore-log: 
,11-28 17:47:45.996  5606  5652 I jxcore-log: 2016-11-28 16:47:45 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js'
11-28 17:47:45.996  5606  5652 I jxcore-log: 
,11-28 17:47:46.010  5606  5652 I jxcore-log: 2016-11-28 16:47:46 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js'
11-28 17:47:46.010  5606  5652 I jxcore-log: 
,11-28 17:47:46.021  5606  5652 I jxcore-log: 2016-11-28 16:47:46 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerAction.js'
11-28 17:47:46.021  5606  5652 I jxcore-log: 
,11-28 17:47:46.034  5606  5652 I jxcore-log: 2016-11-28 16:47:46 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js'
11-28 17:47:46.034  5606  5652 I jxcore-log: 
,11-28 17:47:46.044  5606  5652 I jxcore-log: 2016-11-28 16:47:46 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js'
11-28 17:47:46.044  5606  5652 I jxcore-log: 
,11-28 17:47:46.057  5606  5652 I jxcore-log: 2016-11-28 16:47:46 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js'
11-28 17:47:46.057  5606  5652 I jxcore-log: 
,11-28 17:47:46.067  5606  5652 I jxcore-log: 2016-11-28 16:47:46 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js'
11-28 17:47:46.067  5606  5652 I jxcore-log: 
,11-28 17:47:46.074  5606  5652 I jxcore-log: 2016-11-28 16:47:46 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js'
11-28 17:47:46.074  5606  5652 I jxcore-log: 
,11-28 17:47:46.095  5606  5652 I jxcore-log: 2016-11-28 16:47:46 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testUsn.js'
11-28 17:47:46.095  5606  5652 I jxcore-log: 
,11-28 17:47:46.102  5606  5652 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: SUPPORTED
,11-28 17:47:46.103  5606  5652 I jxcore-log: 2016-11-28 16:47:46 - INFO testUtils: 'BLE multiple advertisement supported'
11-28 17:47:46.103  5606  5652 I jxcore-log: 
,11-28 17:47:46.140  5606  5652 I jxcore-log: 2016-11-28 16:47:46 - INFO CoordinatedClient: 'Connecting to coordination server on http://85.14.110.168:3000/'
11-28 17:47:46.140  5606  5652 I jxcore-log: 
,11-28 17:47:46.201  5606  5652 I jxcore-log: 2016-11-28 16:47:46 - ERROR CoordinatedClient: 'connection error: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-28 17:47:46.201  5606  5652 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-28 17:47:46.201  5606  5652 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-28 17:47:46.201  5606  5652 I jxcore-log: emit@events.js:82:1
11-28 17:47:46.201  5606  5652 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-28 17:47:46.201  5606  5652 I jxcore-log: emit@events.js:82:1''
11-28 17:47:46.201  5606  5652 I jxcore-log: 
,11-28 17:47:46.201  5606  5652 I jxcore-log: 2016-11-28 16:47:46 - DEBUG CoordinatedClient: 'test client failed'
11-28 17:47:46.201  5606  5652 I jxcore-log: 
,11-28 17:47:46.204  5606  5652 I jxcore-log: 2016-11-28 16:47:46 - ERROR CoordinatedThaliTape: 'tests failed, error: 'Error: websocket error', stack: 'Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-28 17:47:46.204  5606  5652 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-28 17:47:46.204  5606  5652 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-28 17:47:46.204  5606  5652 I jxcore-log: emit@events.js:82:1
11-28 17:47:46.204  5606  5652 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-28 17:47:46.204  5606  5652 I jxcore-log: emit@events.js:82:1''
11-28 17:47:46.204  5606  5652 I jxcore-log: 
,11-28 17:47:46.205  5606  5652 I jxcore-log: 2016-11-28 16:47:46 - DEBUG CoordinatedThaliTape: '****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****'
11-28 17:47:46.205  5606  5652 I jxcore-log: 
11-28 17:47:46.205  5606  5652 I jxcore-log: 2016-11-28 16:47:46 - ERROR runTests: 'websocket error
11-28 17:47:46.205  5606  5652 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-28 17:47:46.205  5606  5652 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-28 17:47:46.205  5606  5652 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-28 17:47:46.205  5606  5652 I jxcore-log: emit@events.js:82:1
11-28 17:47:46.205  5606  5652 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-28 17:47:46.205  5606  5652 I jxcore-log: emit@events.js:82:1'
11-28 17:47:46.205  5606  5652 I jxcore-log: 
,11-28 17:47:46.654  5839  5839 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,11-28 17:47:46.660  5839  5839 D AndroidRuntime: CheckJNI is OFF
,11-28 17:47:46.686  5839  5839 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,11-28 17:47:46.711  5839  5839 I Radio-JNI: register_android_hardware_Radio DONE
,11-28 17:47:46.727  5839  5839 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,11-28 17:47:46.735   928   941 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=-1: uninstall pkg
11-28 17:47:46.735   928   941 I ActivityManager: Killing 5606:com.test.thalitest/u0a77 (adj 0): stop com.test.thalitest
,11-28 17:47:46.757   928  2978 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-28 17:47:46.852   928  3833 D GraphicsStats: Buffer count: 2
11-28 17:47:46.852   928   939 I WindowState: WIN DEATH: Window{af87fb4 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,11-28 17:47:46.853   928  2977 D WifiService: Client connection lost with reason: 4
,11-28 17:47:46.864   928   941 W ActivityManager: Force removing ActivityRecord{4913445 u0 com.test.thalitest/.MainActivity t70}: app died, no saved state
,11-28 17:47:46.891   928   951 I art     : Starting a blocking GC Explicit
,11-28 17:47:46.899   928  4209 W ActivityManager: Spurious death for ProcessRecord{80d5aea 0:com.test.thalitest/u0a77}, curProc for 5606: null
,11-28 17:47:46.934   928  3808 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 5606 uid 10077
,11-28 17:47:46.932  3808  3808 W Binder_7: type=1400 audit(0.0:128): avc: denied { ioctl } for path="socket:[27901]" dev="sockfs" ino=27901 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
11-28 17:47:46.932  3808  3808 W Binder_7: type=1400 audit(0.0:129): avc: denied { ioctl } for path="socket:[27901]" dev="sockfs" ino=27901 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-28 17:47:46.945  3684  3684 I Keyboard.Facilitator: onFinishInput()
,11-28 17:47:46.979   928   951 I art     : Explicit concurrent mark sweep GC freed 69066(4MB) AllocSpace objects, 15(492KB) LOS objects, 33% free, 29MB/43MB, paused 2.231ms total 87.622ms
,11-28 17:47:46.999   928   951 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,11-28 17:47:47.001  5839  5839 I art     : System.exit called, status: 0
11-28 17:47:47.001  5839  5839 I AndroidRuntime: VM exiting with result code 0.
,11-28 17:47:47.004  3966  5852 I MicroRecognitionRnrImpl: Starting detection.
,11-28 17:47:47.005  3966  5853 I MicrophoneInputStream: mic_starting com.google.android.apps.gsa.speech.audio.x@88945bd
,11-28 17:47:47.007   513  5855 I AudioFlinger: AudioFlinger's thread 0xf1d80000 ready to run
,11-28 17:47:47.009   928   951 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=0: pkg removed
,11-28 17:47:47.014   513  2995 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
11-28 17:47:47.015  3966  5853 I MicrophoneInputStream: mic_started com.google.android.apps.gsa.speech.audio.x@88945bd
,11-28 17:47:47.022  5698  5698 D BluetoothMapAppObserver: onReceive
,11-28 17:47:47.022  5698  5698 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
,11-28 17:47:47.025   513  5855 D audio_hw_primary: select_devices: out_snd_device(0: none) in_snd_device(63: voice-rec-mic)
,11-28 17:47:47.025   513  5855 D msm8974_platform: platform_send_audio_calibration: sending audio calibration for snd_device(63) acdb_id(62)
11-28 17:47:47.025   513  5855 I ACDB-LOADER: ACDB AFE returned = -19
11-28 17:47:47.025   513  5855 I soundtrigger: audio_extn_sound_trigger_update_device_status: device 0x3f of type 1 for Event 1
11-28 17:47:47.025   513  5855 D sound_trigger_platform: platform_stdev_check_and_update_concurrency: concurrency active 0, tx 1, rx 0, concurrency session_allowed 0
11-28 17:47:47.026   513  5855 D audio_hw_primary: enable_snd_device: snd_device(63: voice-rec-mic)
11-28 17:47:47.026   928  2948 I InputReader: Reconfiguring input devices.  changes=0x00000010
,11-28 17:47:47.028  3950  4154 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,11-28 17:47:47.029  3684  3684 I Keyboard.Facilitator: resetDictionaries() : en_US
,11-28 17:47:47.034   513  5855 D audio_hw_primary: enable_audio_route: apply and update mixer path: audio-record
,11-28 17:47:47.036  3684  5857 I Keyboard.Facilitator.DecoderInitializer: run()
,11-28 17:47:47.044  3684  5857 I Decoder : createOrResetDecoder
,11-28 17:47:47.084  3401  5860 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,11-28 17:47:47.085    28    28 W kworker/3:1: type=1400 audit(0.0:130): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-28 17:47:47.088    28    28 W kworker/3:1: type=1400 audit(0.0:131): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-28 17:47:47.092    28    28 W kworker/3:1: type=1400 audit(0.0:132): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-28 17:47:47.098  3801  3801 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,11-28 17:47:47.101   928   928 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,11-28 17:47:47.108  3684  5857 I Keyboard.Facilitator.MainLanguageModelLoader: run()
,11-28 17:47:47.114  3827  3924 E SQLiteLog: (3850) statement aborts at 23: [DELETE FROM icons WHERE componentName LIKE ? AND profileId = ?] disk I/O error
,11-28 17:47:47.116   928   940 W AtomicFile: Couldn't rename file /data/system/users/0/runtime-permissions.xml to backup file /data/system/users/0/runtime-permissions.xml.bak
,11-28 17:47:47.117   928   940 E PackageManager: Failed to write settings, restoring backup
11-28 17:47:47.117   928   940 E PackageManager: java.io.IOException: Couldn't create directory /data/system/users/0/runtime-permissions.xml
11-28 17:47:47.117   928   940 E PackageManager: 	at android.util.AtomicFile.startWrite(AtomicFile.java:106)
11-28 17:47:47.117   928   940 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.writePermissionsSync(Settings.java:4615)
11-28 17:47:47.117   928   940 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.-wrap1(Settings.java)
11-28 17:47:47.117   928   940 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence$MyHandler.handleMessage(Settings.java:4830)
11-28 17:47:47.117   928   940 E PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-28 17:47:47.117   928   940 E PackageManager: 	at android.os.Looper.loop(Looper.java:148)
11-28 17:47:47.117   928   940 E PackageManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,11-28 17:47:47.122   928   941 E DropBoxManagerService: Can't write: system_server_wtf
11-28 17:47:47.122   928   941 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop15.tmp: open failed: EROFS (Read-only file system)
11-28 17:47:47.122   928   941 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
11-28 17:47:47.122   928   941 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
11-28 17:47:47.122   928   941 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
11-28 17:47:47.122   928   941 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
11-28 17:47:47.122   928   941 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
11-28 17:47:47.122   928   941 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
11-28 17:47:47.122   928   941 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12561)
11-28 17:47:47.122   928   941 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.handleApplicationWtfInner(ActivityManagerService.java:12374)
11-28 17:47:47.122   928   941 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:12346)
11-28 17:47:47.122   928   941 E DropBoxManagerService: 	at android.os.Handler.handleCallback(Handler.java:739)
11-28 17:47:47.122   928   941 E DropBoxManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:95)
11-28 17:47:47.122   928   941 E DropBoxManagerService: 	at android.os.Looper.loop(Looper.java:148)
11-28 17:47:47.122   928   941 E DropBoxManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
11-28 17:47:47.122   928   941 E DropBoxManagerService: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
11-28 17:47:47.122   928   941 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
11-28 17:47:47.122   928   941 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
11-28 17:47:47.122   928   941 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
11-28 17:47:47.122   928   941 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
11-28 17:47:47.122   928   941 E DropBoxManagerService: 	... 13 more
,11-28 17:47:47.122  3584  3584 E SQLiteLog: (3850) statement aborts at 26: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
11-28 17:47:47.123  3584  3584 D AndroidRuntime: Shutting down VM
,--------- beginning of crash
11-28 17:47:47.124  3584  3584 E AndroidRuntime: FATAL EXCEPTION: main
11-28 17:47:47.124  3584  3584 E AndroidRuntime: Process: com.google.process.gapps, PID: 3584
11-28 17:47:47.124  3584  3584 E AndroidRuntime: java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
11-28 17:47:47.124  3584  3584 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2732)
11-28 17:47:47.124  3584  3584 E AndroidRuntime: 	at android.app.ActivityThread.-wrap14(ActivityThread.java)
11-28 17:47:47.124  3584  3584 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1421)
11-28 17:47:47.124  3584  3584 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-28 17:47:47.124  3584  3584 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
11-28 17:47:47.124  3584  3584 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-28 17:47:47.124  3584  3584 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
11-28 17:47:47.124  3584  3584 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-28 17:47:47.124  3584  3584 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-28 17:47:47.124  3584  3584 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
11-28 17:47:47.124  3584  3584 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
11-28 17:47:47.124  3584  3584 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
11-28 17:47:47.124  3584  3584 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
11-28 17:47:47.124  3584  3584 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
11-28 17:47:47.124  3584  3584 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
11-28 17:47:47.124  3584  3584 E AndroidRuntime: 	at com.google.android.gms.gcm.bg.a(SourceFile:310)
11-28 17:47:47.124  3584  3584 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
11-28 17:47:47.124  3584  3584 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
11-28 17:47:47.124  3584  3584 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2725)
11-28 17:47:47.124  3584  3584 E AndroidRuntime: 	... 8 more
,11-28 17:47:47.124  3966  3966 I HotwordWorkerImpl: onReady
,11-28 17:47:47.133   928  3212 I ActivityManager: Start proc 5863:com.google.android.googlequicksearchbox:crash_report/u0a29 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
,11-28 17:47:47.133  3401  3427 E SQLiteLog: (2570) os_unix.c:31406: (30) unlink(/data/user/0/com.android.providers.contacts/databases/contacts2.db-mj1D8E3199D) - 
11-28 17:47:47.134  3827  3924 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
11-28 17:47:47.134  3827  3924 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 3827
11-28 17:47:47.134  3827  3924 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
11-28 17:47:47.134  3827  3924 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
11-28 17:47:47.134  3827  3924 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
11-28 17:47:47.134  3827  3924 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
11-28 17:47:47.134  3827  3924 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
11-28 17:47:47.134  3827  3924 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
11-28 17:47:47.134  3827  3924 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
11-28 17:47:47.134  3827  3924 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
11-28 17:47:47.134  3827  3924 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
11-28 17:47:47.134  3827  3924 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
11-28 17:47:47.134  3827  3924 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
11-28 17:47:47.134  3827  3924 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,11-28 17:47:47.138   928  5874 E DropBoxManagerService: Can't write: system_app_crash
11-28 17:47:47.138   928  5874 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop114.tmp: open failed: EROFS (Read-only file system)
11-28 17:47:47.138   928  5874 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
11-28 17:47:47.138   928  5874 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
11-28 17:47:47.138   928  5874 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
11-28 17:47:47.138   928  5874 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
11-28 17:47:47.138   928  5874 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
11-28 17:47:47.138   928  5874 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
11-28 17:47:47.138   928  5874 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
11-28 17:47:47.138   928  5874 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
11-28 17:47:47.138   928  5874 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
11-28 17:47:47.138   928  5874 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
11-28 17:47:47.138   928  5874 E DropBoxManagerService: 	... 5 more
,11-28 17:47:47.142   928  4209 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,11-28 17:47:47.142   928  5876 E DropBoxManagerService: Can't write: system_app_crash
11-28 17:47:47.142   928  5876 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop115.tmp: open failed: EROFS (Read-only file system)
11-28 17:47:47.142   928  5876 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
11-28 17:47:47.142   928  5876 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
11-28 17:47:47.142   928  5876 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
11-28 17:47:47.142   928  5876 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
11-28 17:47:47.142   928  5876 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
11-28 17:47:47.142   928  5876 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
11-28 17:47:47.142   928  5876 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
11-28 17:47:47.142   928  5876 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
11-28 17:47:47.142   928  5876 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
11-28 17:47:47.142   928  5876 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
11-28 17:47:47.142   928  5876 E DropBoxManagerService: 	... 5 more
,11-28 17:47:47.144  3966  4362 W SearchService: Abort, client detached.
,11-28 17:47:47.147  3966  3966 I HotwordDetector: Closing mic
11-28 17:47:47.147  3966  4231 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@88945bd
,11-28 17:47:47.151  3966  5853 E AudioRecord-JNI: Error -4 during AudioRecord native read
,11-28 17:47:47.161  3401  5860 E SQLiteLog: (3850) statement aborts at 18: [DELETE FROM calls WHERE (((source_package = 'com.test.thalitest'))) AND ((type = 4))] disk I/O error
,11-28 17:47:47.162  3401  5860 E AndroidRuntime: FATAL EXCEPTION: IntentService[VoicemailCleanupService]
11-28 17:47:47.162  3401  5860 E AndroidRuntime: Process: android.process.acore, PID: 3401
11-28 17:47:47.162  3401  5860 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
11-28 17:47:47.162  3401  5860 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
11-28 17:47:47.162  3401  5860 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
11-28 17:47:47.162  3401  5860 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
11-28 17:47:47.162  3401  5860 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
11-28 17:47:47.162  3401  5860 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
11-28 17:47:47.162  3401  5860 E AndroidRuntime: 	at com.android.providers.contacts.DbModifierWithNotification.delete(DbModifierWithNotification.java:197)
11-28 17:47:47.162  3401  5860 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:219)
11-28 17:47:47.162  3401  5860 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
11-28 17:47:47.162  3401  5860 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
11-28 17:47:47.162  3401  5860 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
11-28 17:47:47.162  3401  5860 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
11-28 17:47:47.162  3401  5860 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
11-28 17:47:47.162  3401  5860 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
11-28 17:47:47.162  3401  5860 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-28 17:47:47.162  3401  5860 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
11-28 17:47:47.162  3401  5860 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
11-28 17:47:47.158   766   766 W Binder_3: type=1400 audit(0.0:133): avc: denied { ioctl } for path="socket:[26242]" dev="sockfs" ino=26242 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
11-28 17:47:47.158   766   766 W Binder_3: type=1400 audit(0.0:134): avc: denied { ioctl } for path="socket:[26242]" dev="sockfs" ino=26242 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-28 17:47:47.163  3401  3427 I Process : Sending signal. PID: 3401 SIG: 9
,11-28 17:47:47.162   766   766 W Binder_3: type=1400 audit(0.0:135): avc: denied { ioctl } for path="socket:[33235]" dev="sockfs" ino=33235 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
11-28 17:47:47.165   928  5878 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
11-28 17:47:47.162   766   766 W Binder_3: type=1400 audit(0.0:136): avc: denied { ioctl } for path="socket:[33235]" dev="sockfs" ino=33235 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-28 17:47:47.174  3684  5857 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /data/user/0/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
,11-28 17:47:47.176  3684  5857 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
11-28 17:47:47.177  3684  5857 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
11-28 17:47:47.178   928  5880 E DropBoxManagerService: Can't write: system_app_crash
11-28 17:47:47.178   928  5880 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop117.tmp: open failed: EROFS (Read-only file system)
11-28 17:47:47.178   928  5880 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
11-28 17:47:47.178   928  5880 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
11-28 17:47:47.178   928  5880 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
11-28 17:47:47.178   928  5880 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
11-28 17:47:47.178   928  5880 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
11-28 17:47:47.178   928  5880 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
11-28 17:47:47.178   928  5880 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
11-28 17:47:47.178   928  5880 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
11-28 17:47:47.178   928  5880 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
11-28 17:47:47.178   928  5880 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
11-28 17:47:47.178   928  5880 E DropBoxManagerService: 	... 5 more
11-28 17:47:47.178  3684  5857 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Contacts.dict
11-28 17:47:47.179  3684  5857 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = history
11-28 17:47:47.179  3684  5857 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loaded File = UserHistory.en_US.dict
,11-28 17:47:47.179  3684  5857 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = user
11-28 17:47:47.180  3684  5857 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Personal.en_US.dict
11-28 17:47:47.180  3684  5857 I Keyboard.Facilitator.PersonalDictionaryLoader: run() : Loaded (exit)
11-28 17:47:47.180  3684  5857 I Keyboard.Facilitator.Delight2FileSweeper: run()
11-28 17:47:47.180  3684  5857 I Keyboard.Facilitator.RecurringTaskScheduler: run()
11-28 17:47:47.180  3684  5857 I StatsUtilsManager: startPeriodStatsRecorder() : Success
11-28 17:47:47.180  3684  5857 I PeriodicStatsRecorder: shouldRecordStats() = Too Soon
,11-28 17:47:47.217   513  5855 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
,11-28 17:47:47.218   513  5855 D audio_hw_primary: disable_snd_device: snd_device(63: voice-rec-mic)
,11-28 17:47:47.222   513  5855 I soundtrigger: audio_extn_sound_trigger_update_device_status: device 0x3f of type 1 for Event 0
11-28 17:47:47.222   513  5855 D sound_trigger_platform: platform_stdev_check_and_update_concurrency: concurrency active 0, tx 0, rx 0, concurrency session_allowed 1
,11-28 17:47:47.223   513  2995 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
11-28 17:47:47.223   928  3833 I ActivityManager: Process android.process.acore (pid 3401) has died
11-28 17:47:47.224   928  3833 W ActivityManager: Scheduling restart of crashed service com.android.providers.contacts/.VoicemailCleanupService in 1000ms
11-28 17:47:47.226  3966  4234 I MicroRecognitionRnrImpl: Stopping hotword detection.
,11-28 17:47:47.228  3966  5852 I MicroRecognitionRnrImpl: Detection finished
,11-28 17:47:47.489   383   479 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0

```
