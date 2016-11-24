#### Test 9501784151844b4_thali07_Huawei-Nexus 6P Logs


```
--------- beginning of main
11-24 16:40:58.679  3688  4208 I Icing   : Indexing 3C763AF371F9E97B4ECFEA01A338ADB468C38476 from com.google.android.googlequicksearchbox
,11-24 16:40:58.755  3688  4208 I Icing   : Indexing done 3C763AF371F9E97B4ECFEA01A338ADB468C38476
11-24 16:40:59.106  5606  5606 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
11-24 16:40:59.110  5606  5606 D AndroidRuntime: CheckJNI is OFF
11-24 16:40:59.138  5606  5606 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
11-24 16:40:59.173  5606  5606 I Radio-JNI: register_android_hardware_Radio DONE
11-24 16:40:59.188  5606  5606 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
11-24 16:40:59.201   927   938 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
11-24 16:40:59.223  5606  5606 D AndroidRuntime: Shutting down VM
11-24 16:40:59.237  3938  3950 W SearchService: Abort, client detached.
11-24 16:40:59.243  3938  3938 I HotwordDetector: Closing mic
11-24 16:40:59.244  3938  4150 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@556ffde
11-24 16:40:59.245  3938  4185 E AudioRecord-JNI: Error -4 during AudioRecord native read
11-24 16:40:59.271   927  3741 I ActivityManager: Start proc 5615:com.test.thalitest/u0a77 for activity com.test.thalitest/.MainActivity
11-24 16:40:59.316   511  4189 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
11-24 16:40:59.318   511  4189 D audio_hw_primary: disable_snd_device: snd_device(63: voice-rec-mic)
11-24 16:40:59.321   511  4189 I soundtrigger: audio_extn_sound_trigger_update_device_status: device 0x3f of type 1 for Event 0
11-24 16:40:59.321   511  4189 D sound_trigger_platform: platform_stdev_check_and_update_concurrency: concurrency active 0, tx 0, rx 0, concurrency session_allowed 1
11-24 16:40:59.323   511  2958 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
11-24 16:40:59.326  3938  4158 I MicroRecognitionRnrImpl: Stopping hotword detection.
11-24 16:40:59.326  3938  4182 I MicroRecognitionRnrImpl: Detection finished
11-24 16:40:59.373  5615  5615 I CordovaLog: Changing log level to DEBUG(3)
11-24 16:40:59.374  5615  5615 I CordovaActivity: Apache Cordova native platform version 6.0.0 is starting
11-24 16:40:59.374  5615  5615 D CordovaActivity: CordovaActivity.onCreate()
11-24 16:40:59.381  5615  5615 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011750)
11-24 16:40:59.404  5615  5615 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,11-24 16:40:59.464  5615  5615 I LibraryLoader: Time to load native libraries: 56 ms (timestamps 9969-25)
11-24 16:40:59.464  5615  5615 I LibraryLoader: Expected native library version number "",actual native library version number ""
,11-24 16:40:59.510  5615  5615 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {43bf53a}
11-24 16:40:59.510  5615  5615 I LibraryLoader: Expected native library version number "",actual native library version number ""
,11-24 16:40:59.510  5615  5615 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,11-24 16:40:59.514  5615  5615 I BrowserStartupController: Initializing chromium process, singleProcess=true
,11-24 16:40:59.516  5615  5615 E SysUtils: ApplicationContext is null in ApplicationStatus
,11-24 16:40:59.568  5615  5615 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,11-24 16:40:59.583  5615  5615 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,11-24 16:40:59.583  5615  5615 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
11-24 16:40:59.583  5615  5615 I Adreno  : QUALCOMM build                   : 63c06b2, I8366cd0437
11-24 16:40:59.583  5615  5615 I Adreno  : Build Date                       : 12/06/15
11-24 16:40:59.583  5615  5615 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
11-24 16:40:59.583  5615  5615 I Adreno  : Local Branch                     : mybranch17112971
11-24 16:40:59.583  5615  5615 I Adreno  : Remote Branch                    : quic/LA.BF64.1.2.9_v2
11-24 16:40:59.583  5615  5615 I Adreno  : Remote Branch                    : NONE
11-24 16:40:59.583  5615  5615 I Adreno  : Reconstruct Branch               : NOTHING
,11-24 16:40:59.645   927   944 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@73befd2:true
,11-24 16:40:59.680   407   407 W Binder_2: type=1400 audit(0.0:101): avc: denied { ioctl } for path="socket:[15273]" dev="sockfs" ino=15273 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-24 16:40:59.680   407   407 W Binder_2: type=1400 audit(0.0:102): avc: denied { ioctl } for path="socket:[15273]" dev="sockfs" ino=15273 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-24 16:40:59.696  5615  5615 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,11-24 16:40:59.707  5615  5615 D SystemWebViewEngine: CordovaWebView is running on device made by: Huawei
,11-24 16:40:59.712  5615  5615 D PluginManager: init()
,11-24 16:40:59.715  5615  5615 D CordovaWebViewImpl: >>> loadUrl(file:///android_asset/www/index.html)
,11-24 16:40:59.734  5615  5615 D CordovaActivity: Started the activity.
11-24 16:40:59.734  5615  5615 D CordovaActivity: Resumed the activity.
,11-24 16:40:59.733   405   405 W Binder_1: type=1400 audit(0.0:103): avc: denied { ioctl } for path="socket:[32113]" dev="sockfs" ino=32113 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-24 16:40:59.733   405   405 W Binder_1: type=1400 audit(0.0:104): avc: denied { ioctl } for path="socket:[32113]" dev="sockfs" ino=32113 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
11-24 16:40:59.738  5615  5652 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,11-24 16:40:59.740  3655  3655 W Binder_7: type=1400 audit(0.0:105): avc: denied { ioctl } for path="socket:[15284]" dev="sockfs" ino=15284 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-24 16:40:59.740  3655  3655 W Binder_7: type=1400 audit(0.0:106): avc: denied { ioctl } for path="socket:[15284]" dev="sockfs" ino=15284 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-24 16:40:59.743  5615  5639 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,11-24 16:40:59.777  5615  5652 I OpenGLRenderer: Initialized EGL, version 1.4
,11-24 16:40:59.856   927   945 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +612ms
,11-24 16:40:59.853  3655  3655 W Binder_7: type=1400 audit(0.0:107): avc: denied { ioctl } for path="socket:[31153]" dev="sockfs" ino=31153 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
11-24 16:40:59.853  3655  3655 W Binder_7: type=1400 audit(0.0:108): avc: denied { ioctl } for path="socket:[31153]" dev="sockfs" ino=31153 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
11-24 16:40:59.856   937   937 W Binder_1: type=1400 audit(0.0:109): avc: denied { ioctl } for path="socket:[31152]" dev="sockfs" ino=31152 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
11-24 16:40:59.856   937   937 W Binder_1: type=1400 audit(0.0:110): avc: denied { ioctl } for path="socket:[31152]" dev="sockfs" ino=31152 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
11-24 16:40:59.861  3621  3621 I Keyboard.Facilitator: onFinishInput()
,11-24 16:40:59.873  5615  5615 D CordovaWebViewImpl: onPageDidNavigate(file:///android_asset/www/index.html)
,11-24 16:40:59.893  5615  5615 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 5615
,11-24 16:41:00.057  5615  5615 D JsMessageQueue: Set native->JS mode to EvalBridgeMode
,11-24 16:41:00.123   927  2910 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-24 16:41:00.181  5615  5654 D jxcore_app_log: JniHelper::setJavaVM(0xf53bc000), pthread_self() = -562038480
,11-24 16:41:00.185  5615  5654 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
11-24 16:41:00.185  5615  5654 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
11-24 16:41:00.185  5615  5654 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
11-24 16:41:00.185  5615  5654 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
11-24 16:41:00.185  5615  5654 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
11-24 16:41:00.185  5615  5654 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@91f19d9 added. We now have 1 listener(s)
,11-24 16:41:00.189  5615  5654 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 60:83:34:25:D7:D4
,11-24 16:41:00.190  5615  5654 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
,11-24 16:41:00.190  5615  5654 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-24 16:41:00.191  5615  5654 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,11-24 16:41:00.193  5615  5654 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
11-24 16:41:00.193  5615  5654 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
11-24 16:41:00.193  5615  5654 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
11-24 16:41:00.193  5615  5654 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 60:83:34:25:D7:D4
11-24 16:41:00.193  5615  5654 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
11-24 16:41:00.193  5615  5654 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
11-24 16:41:00.193  5615  5654 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
11-24 16:41:00.193  5615  5654 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
11-24 16:41:00.193  5615  5654 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
11-24 16:41:00.193  5615  5654 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
11-24 16:41:00.193  5615  5654 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
11-24 16:41:00.193  5615  5654 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
11-24 16:41:00.193  5615  5654 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
11-24 16:41:00.193  5615  5654 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,11-24 16:41:00.193  5615  5654 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ff1ca4c added. We now have 1 listener(s)
,11-24 16:41:00.193  5615  5654 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-24 16:41:00.197   927  2911 D WifiService: New client listening to asynchronous messages
,11-24 16:41:00.198  5615  5654 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
11-24 16:41:00.198  5615  5654 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
11-24 16:41:00.198  5615  5654 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[JavaBridge,5,main], id: 55
11-24 16:41:00.198  5615  5654 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
11-24 16:41:00.198  5615  5654 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
11-24 16:41:00.198  5615  5654 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
11-24 16:41:00.198  5615  5654 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[JavaBridge,5,main], id: 55
,11-24 16:41:00.199  5615  5654 I io.jxcore.node.LifeCycleMonitor: start: OK
,11-24 16:41:00.241  5615  5615 D CordovaWebViewImpl: onPageFinished(file:///android_asset/www/index.html)
,11-24 16:41:00.243  5615  5615 D SystemWebChromeClient: file:///android_asset/www/js/index.js: Line 36 : Uncaught TypeError: Cannot read property 'querySelector' of null
,11-24 16:41:00.243  5615  5615 I chromium: [INFO:CONSOLE(36)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (36)
,11-24 16:41:00.965  5615  5663 W jxcore-log: Initializing JXcore engine
11-24 16:41:00.965  5615  5663 W jxcore-log: JXcore engine is ready
,11-24 16:41:00.986  5663  5663 W Thread-62: type=1400 audit(0.0:111): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=10237 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,11-24 16:41:00.986  5663  5663 W Thread-62: type=1400 audit(0.0:112): avc: denied { ioctl } for path="socket:[16390]" dev="sockfs" ino=16390 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
11-24 16:41:00.986  5663  5663 W Thread-62: type=1400 audit(0.0:113): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=5964 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
11-24 16:41:00.986  5663  5663 W Thread-62: type=1400 audit(0.0:114): avc: denied { ioctl } for path="socket:[29666]" dev="sockfs" ino=29666 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:untrusted_app:s0:c512,c768 tclass=netlink_route_socket permissive=0
,11-24 16:41:00.998  5615  5663 W jxcore-log: Starting JXcore engine
,11-24 16:41:01.047  5615  5663 W jxcore-log: Platform android
11-24 16:41:01.047  5615  5663 W jxcore-log: 
,11-24 16:41:01.047  5615  5663 W jxcore-log: Process ARCH arm
11-24 16:41:01.047  5615  5663 W jxcore-log: 
,11-24 16:41:01.230  5615  5663 I jxcore-log: JXcore Cordova bridge is ready!
11-24 16:41:01.230  5615  5663 I jxcore-log: 
,11-24 16:41:01.231  5615  5663 W jxcore-log: JXcore engine is started
11-24 16:41:01.243  5615  5654 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
11-24 16:41:01.250  5615  5615 D SystemWebChromeClient: file:///android_asset/www/js/thali_main.js: Line 41 : Application has the required permission.
11-24 16:41:01.251  5615  5615 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,11-24 16:41:02.769  3526  3526 I ConfigService: onDestroy
,11-24 16:41:02.951   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 16:41:03.952   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 16:41:04.251   927  3362 I ActivityManager: Killing 5224:com.android.settings/1000 (adj 15): empty #17
,11-24 16:41:04.285   927  3362 I ActivityManager: Killing 5206:org.codeaurora.ims/1001 (adj 15): empty #18
,11-24 16:41:04.953   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 16:41:05.954   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 16:41:06.956   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 16:41:07.957   535   535 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,11-24 16:41:09.338  3938  5665 W CronetSyncConnectionRcs: Upload content type not set.
,11-24 16:41:10.914  5615  5663 I jxcore-log: 2016-11-24 15:41:10 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
11-24 16:41:10.914  5615  5663 I jxcore-log: 
,11-24 16:41:10.916  5615  5663 I jxcore-log: 2016-11-24 15:41:10 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
11-24 16:41:10.916  5615  5663 I jxcore-log: 
,11-24 16:41:10.923  5615  5663 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,11-24 16:41:10.924  5615  5663 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-24 16:41:10.924  5615  5663 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-24 16:41:10.924  5615  5663 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-24 16:41:10.924  5615  5663 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-24 16:41:10.924  5615  5663 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-24 16:41:10.924  5615  5663 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-24 16:41:10.924  5615  5663 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-24 16:41:10.924  5615  5663 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-24 16:41:10.924  5615  5663 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,11-24 16:41:10.926  5615  5663 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
11-24 16:41:10.927  5615  5663 I jxcore-log: 2016-11-24 15:41:10 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
11-24 16:41:10.927  5615  5663 I jxcore-log: 
11-24 16:41:10.929  5615  5663 I jxcore-log: 2016-11-24 15:41:10 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
11-24 16:41:10.929  5615  5663 I jxcore-log: 
,11-24 16:41:11.179  5615  5663 I jxcore-log: 2016-11-24 15:41:11 - DEBUG UnitTest_app: 'Running unit tests'
11-24 16:41:11.179  5615  5663 I jxcore-log: 
,11-24 16:41:11.180  5615  5663 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,11-24 16:41:11.180  5615  5663 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3032be8 added. We now have 2 listener(s)
11-24 16:41:11.181  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-24 16:41:11.181  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-24 16:41:11.181  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-24 16:41:11.181  5615  5663 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,11-24 16:41:11.181  5615  5663 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d2a9201 added. We now have 2 listener(s)
11-24 16:41:11.181  5615  5663 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-24 16:41:11.182  5615  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
11-24 16:41:11.183  5615  5663 D executeNativeTests: Running unit tests
,11-24 16:41:11.223  5615  5663 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,11-24 16:41:11.223  5615  5663 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@dfc8756 added. We now have 3 listener(s)
11-24 16:41:11.223  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
,11-24 16:41:11.223  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-24 16:41:11.223  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,11-24 16:41:11.224  5615  5663 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-24 16:41:11.224  5615  5663 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@84603d7 added. We now have 3 listener(s)
11-24 16:41:11.224  5615  5663 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-24 16:41:11.224  5615  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
11-24 16:41:11.226  5615  5663 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
11-24 16:41:11.226  5615  5663 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-24 16:41:11.226  5615  5663 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-24 16:41:11.226  5615  5663 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-24 16:41:11.227  5615  5663 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
11-24 16:41:11.227  5615  5663 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
11-24 16:41:11.227  5615  5663 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
11-24 16:41:11.227  5615  5663 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-24 16:41:11.227  5615  5663 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-24 16:41:11.227  5615  5663 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-24 16:41:11.227  5615  5663 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-24 16:41:11.227  5615  5663 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-24 16:41:11.227  5615  5663 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-24 16:41:11.228  5615  5663 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-24 16:41:11.228  5615  5663 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 16:41:11.228  5615  5663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-24 16:41:11.228  5615  5663 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@dfc8756 removed from the list
11-24 16:41:11.228  5615  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 16:41:11.228  5615  5663 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@84603d7 removed from the list
11-24 16:41:11.228  5615  5663 D io.jxcore.node.ConnectivityMonitor: stop
11-24 16:41:11.228  5615  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-62,5,main], id: 62
11-24 16:41:11.228  5615  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-24 16:41:11.229  5615  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal ,Current thread: Thread[Thread-62,5,main], id: 62
11-24 16:41:11.229  5615  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-24 16:41:11.229  5615  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-24 16:41:11.229  5615  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-24 16:41:11.229  5615  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-24 16:41:11.229  5615  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 16:41:11.229  5615  5663 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@84603d7 not in the list
11-24 16:41:11.230  5615  5663 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
11-24 16:41:11.230  5615  5663 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-24 16:41:11.230  5615  5663 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-24 16:41:11.230  5615  5663 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-24 16:41:11.230  5615  5663 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-24 16:41:11.230  5615  5663 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 16:41:11.230  5615  5663 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@dfc8756 not in the list
11-24 16:41:11.230  5615  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 16:41:11.231  5615  5663 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@84603d7 not in the list
11-24 16:41:11.231  5615  5663 D io.jxcore.node.ConnectivityMonitor: stop
11-24 16:41:11.231  5615  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-62,5,main], id: 62
11-24 16:41:11.231  5615  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-24 16:41:11.231  5615  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-24 16:41:11.231  5615  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-24 16:41:11.231  5615  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-24 16:41:11.231  5615  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-24 16:41:11.231  5615  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-24 16:41:11.231  5615  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 16:41:11.231  5615  5663 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@84603d7 not in the list
11-24 16:41:11.234  5615  5663 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
11-24 16:41:11.234  5615  5663 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
11-24 16:41:11.234  5615  5663 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:11,0]
11-24 16:41:11.234  5615  5663 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
11-24 16:41:11.234  5615  5663 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
11-24 16:41:11.234  5615  5663 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
11-24 16:41:11.234  5615  5663 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
11-24 16:41:11.234  5615  5663 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
11-24 16:41:11.234  5615  5663 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
11-24 16:41:11.234  5615  5663 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
11-24 16:41:11.234  5615  5663 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
11-24 16:41:11.234  5615  5663 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
11-24 16:41:11.234  5615  5663 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
11-24 16:41:11.234  5615  5663 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
,11-24 16:41:11.234  5615  5663 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
11-24 16:41:11.234  5615  5663 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
11-24 16:41:11.234  5615  5663 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
11-24 16:41:11.234  5615  5663 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
11-24 16:41:11.234  5615  5663 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
11-24 16:41:11.234  5615  5663 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
11-24 16:41:11.234  5615  5663 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
11-24 16:41:11.234  5615  5663 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
11-24 16:41:11.234  5615  5663 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
11-24 16:41:11.234  5615  5663 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
11-24 16:41:11.234  5615  5663 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
11-24 16:41:11.234  5615  5663 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
,11-24 16:41:11.234  5615  5663 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
11-24 16:41:11.235  5615  5663 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
11-24 16:41:11.235  5615  5663 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
11-24 16:41:11.235  5615  5663 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
11-24 16:41:11.235  5615  5663 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
11-24 16:41:11.235  5615  5663 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-24 16:41:11.235  5615  5663 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-24 16:41:11.235  5615  5663 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-24 16:41:11.235  5615  5663 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-24 16:41:11.235  5615  5663 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 16:41:11.235  5615  5663 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@dfc8756 not in the list
11-24 16:41:11.235  5615  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-24 16:41:11.235  5615  5663 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@84603d7 not in the list
11-24 16:41:11.235  5615  5663 D io.jxcore.node.ConnectivityMonitor: stop
11-24 16:41:11.235  5615  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-62,5,main], id: 62
11-24 16:41:11.235  5615  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-24 16:41:11.236  5615  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-24 16:41:11.236  5615  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
,11-24 16:41:11.236  5615  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-24 16:41:11.236  5615  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-24 16:41:11.236  5615  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-24 16:41:11.236  5615  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 16:41:11.236  5615  5663 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@84603d7 not in the list
11-24 16:41:11.236  5615  5663 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,11-24 16:41:11.237  5615  5663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-24 16:41:11.237  5615  5663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
11-24 16:41:11.245  5615  5663 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-24 16:41:11.245  5615  5663 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-24 16:41:11.245  5615  5663 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-24 16:41:11.245  5615  5663 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-24 16:41:11.245  5615  5663 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-24 16:41:11.245  5615  5663 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-24 16:41:11.245  5615  5663 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-24 16:41:11.245  5615  5663 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-24 16:41:11.245  5615  5663 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,11-24 16:41:11.246  5615  5663 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
11-24 16:41:11.246  5615  5663 D io.jxcore.node.ConnectivityMonitor: start: OK
11-24 16:41:11.246  5615  5663 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-24 16:41:11.246  5615  5663 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
11-24 16:41:11.246  5615  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
11-24 16:41:11.246  5615  5663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-24 16:41:11.246  5615  5663 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
11-24 16:41:11.250  5615  5615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-24 16:41:11.251  5615  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-24 16:41:11.251  5615  5663 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-24 16:41:11.251  5615  5663 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
11-24 16:41:11.253  5615  5615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-24 16:41:11.253  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-62,5,main], id: 62
11-24 16:41:11.253  5615  5663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-24 16:41:11.254  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-24 16:41:11.254  5615  5663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-24 16:41:11.255  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 0
11-24 16:41:11.256  5615  5663 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
11-24 16:41:11.257  5615  5663 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
11-24 16:41:11.257  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-62,5,main], id: 62
11-24 16:41:11.257  5615  5663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
11-24 16:41:11.258  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
11-24 16:41:11.258  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
11-24 16:41:11.258  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
11-24 16:41:11.258  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-62,5,main], id: 62
11-24 16:41:11.258  5615  5663 D BluetoothAdapter: STATE_ON
11-24 16:41:11.260  4623  4638 D BtGatt.GattService: registerClient() - UUID=f779cd00-6dd1-4223-b66b-20e7f20541d5
,11-24 16:41:11.262  4623  4685 D BtGatt.GattService: onClientRegistered() - UUID=f779cd00-6dd1-4223-b66b-20e7f20541d5, clientIf=5
,11-24 16:41:11.265  5615  5625 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
11-24 16:41:11.266  4623  4636 D BtGatt.GattService: start scan with filters
,11-24 16:41:11.271  4623  4688 D BtGatt.ScanManager: handling starting scan
,11-24 16:41:11.271  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
11-24 16:41:11.271  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-62,5,main], id: 62
11-24 16:41:11.271  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
11-24 16:41:11.272  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-62,5,main], id: 62
11-24 16:41:11.272  5615  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-24 16:41:11.272  5615  5615 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-24 16:41:11.272  5615  5615 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-24 16:41:11.272  5615  5615 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
11-24 16:41:11.272  5615  5615 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
,11-24 16:41:11.273  5615  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-24 16:41:11.273  5615  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-24 16:41:11.273  5615  5615 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-24 16:41:11.273  5615  5615 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
11-24 16:41:11.273  5615  5615 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-24 16:41:11.273  4623  4688 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@75cfb1d
11-24 16:41:11.274  5615  5615 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING] Current thread: Thread[main,5,main], id: 1
,11-24 16:41:11.275  5615  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-24 16:41:11.275  5615  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-24 16:41:11.275  5615  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-24 16:41:11.275  5615  5615 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-24 16:41:11.276  5615  5663 I io.jxcore.node.ConnectionHelper: start: OK
,11-24 16:41:11.278  5615  5615 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
,11-24 16:41:11.279  5615  5615 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
11-24 16:41:11.279  5615  5615 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-24 16:41:11.279  5615  5615 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-24 16:41:11.280  5615  5615 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,11-24 16:41:11.282  4623  4685 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
11-24 16:41:11.282  4623  4685 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-24 16:41:11.283  4623  4688 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,11-24 16:41:11.290  4623  4685 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
11-24 16:41:11.291  4623  4685 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-24 16:41:11.291  4623  4688 D BtGatt.ScanManager: Starting BLE batch scan
11-24 16:41:11.291  4623  4688 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,11-24 16:41:11.303  4623  4685 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
11-24 16:41:11.303  4623  4685 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-24 16:41:11.310  4623  4685 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,11-24 16:41:11.310  4623  4685 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-24 16:41:11.782  5615  5615 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,11-24 16:41:11.782  5615  5615 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
11-24 16:41:11.782  5615  5615 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,11-24 16:41:14.184   927  2912 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,11-24 16:41:16.280  5615  5663 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-24 16:41:16.281  5615  5663 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
11-24 16:41:16.281  5615  5663 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
11-24 16:41:16.281  5615  5663 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-24 16:41:16.281  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-24 16:41:16.281  5615  5663 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,11-24 16:41:16.281  5615  5663 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
11-24 16:41:16.281  5615  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-24 16:41:16.282  5615  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-62,5,main], id: 62
11-24 16:41:16.282  5615  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
,11-24 16:41:16.282  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-24 16:41:16.283  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-62,5,main], id: 62
,11-24 16:41:16.283  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-62,5,main], id: 62
11-24 16:41:16.283  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-62,5,main], id: 62
11-24 16:41:16.283  5615  5663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,11-24 16:41:16.283  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-62,5,main], id: 62
11-24 16:41:16.285  5615  5663 D BluetoothAdapter: STATE_ON
11-24 16:41:16.285  4623  4636 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
11-24 16:41:16.285  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-24 16:41:16.287  4623  4688 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-24 16:41:16.287  5615  5663 D BluetoothAdapter: STATE_ON
11-24 16:41:16.291  4623  4835 D BtGatt.GattService: stopScan() - queue size =1
,11-24 16:41:16.293  4623  4638 D BtGatt.GattService: unregisterClient() - clientIf=5
11-24 16:41:16.294  4623  4623 D BtGatt.ScanManager: awakened up at time 96855
,11-24 16:41:16.294  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-24 16:41:16.295  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-62,5,main], id: 62
11-24 16:41:16.295  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
11-24 16:41:16.295  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-62,5,main], id: 62
11-24 16:41:16.296  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-62,5,main], id: 62
11-24 16:41:16.296  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-62,5,main], id: 62
11-24 16:41:16.297  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-62,5,main], id: 62
,11-24 16:41:16.297  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-24 16:41:16.298  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-62,5,main], id: 62
11-24 16:41:16.298  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-62,5,main], id: 62
,11-24 16:41:16.298  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-62,5,main], id: 62
11-24 16:41:16.300  5615  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-24 16:41:16.300  5615  5663 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,11-24 16:41:16.304  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-24 16:41:16.304  5615  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
,11-24 16:41:16.333  5615  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-24 16:41:16.333  5615  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-24 16:41:16.333  5615  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-24 16:41:16.333  5615  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-24 16:41:16.334  5615  5663 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-24 16:41:16.334  5615  5615 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-24 16:41:16.334  5615  5663 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,11-24 16:41:16.334  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-24 16:41:16.334  5615  5615 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-24 16:41:16.334  5615  5663 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 16:41:16.334  5615  5615 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-24 16:41:16.334  5615  5663 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@dfc8756 not in the list
11-24 16:41:16.334  5615  5615 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-24 16:41:16.334  5615  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 16:41:16.334  5615  5663 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@84603d7 not in the list
11-24 16:41:16.334  5615  5615 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-24 16:41:16.334  5615  5663 D io.jxcore.node.ConnectivityMonitor: stop
11-24 16:41:16.334  5615  5615 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
11-24 16:41:16.334  5615  5663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
,11-24 16:41:16.334  5615  5615 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-24 16:41:16.334  5615  5615 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-24 16:41:16.334  5615  5615 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-24 16:41:16.335  5615  5615 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-24 16:41:16.335  5615  5615 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED] Current thread: Thread[main,5,main], id: 1
11-24 16:41:16.335  5615  5615 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-24 16:41:16.337  5615  5615 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-24 16:41:16.337  5615  5615 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-24 16:41:16.337  5615  5615 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
,11-24 16:41:16.348  4623  4685 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=5
11-24 16:41:16.348  4623  4685 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 16:41:16.349  4623  4685 D BtGatt.GattService: current time is 96909943257
11-24 16:41:16.349  4623  4685 D BtGatt.GattService: Batch record : [-46, -4, -117, 6, 105, -37, 1, -128, -80, 99, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 81, 34, 97, 112, -14, -5, 1, -128, -94, 79, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 116, -43, -111, -91, -20, -29, 1, -128, -80, 97, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 37, -47, 14, -113, 116, -46, 1, -128, -94, 96, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 71, -122, -77, 84, 69, -12, 1, -128, -98, 87, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 0]
,11-24 16:41:16.350  4623  4685 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
11-24 16:41:16.351  4623  4685 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
11-24 16:41:16.351  4623  4685 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
11-24 16:41:16.351  4623  4685 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
11-24 16:41:16.351  4623  4685 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74]
11-24 16:41:16.352  4623  4685 E BtGatt.ContextMap: Context not found for ID 5
,11-24 16:41:16.360  4623  4685 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
11-24 16:41:16.360  4623  4685 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 16:41:16.360  4623  4688 D BtGatt.ScanManager: stopping BLe Batch
11-24 16:41:16.364  4623  4685 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
11-24 16:41:16.365  4623  4685 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 16:41:16.365  4623  4688 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-24 16:41:16.369  4623  4685 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,11-24 16:41:16.369  4623  4685 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-24 16:41:16.414  4823  4865 D Finsky  : [184] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,11-24 16:41:16.416  4823  4823 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,11-24 16:41:16.836  5615  5615 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-24 16:41:17.219   927  2912 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,11-24 16:41:21.338  5615  5663 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,11-24 16:41:21.343  5615  5663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-24 16:41:21.344  5615  5663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
,11-24 16:41:21.357  5615  5663 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-24 16:41:21.357  5615  5663 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-24 16:41:21.357  5615  5663 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-24 16:41:21.357  5615  5663 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-24 16:41:21.357  5615  5663 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-24 16:41:21.357  5615  5663 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-24 16:41:21.357  5615  5663 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-24 16:41:21.357  5615  5663 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-24 16:41:21.357  5615  5663 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,11-24 16:41:21.359  5615  5663 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
11-24 16:41:21.359  5615  5663 D io.jxcore.node.ConnectivityMonitor: start: OK
,11-24 16:41:21.359  5615  5663 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-24 16:41:21.359  5615  5663 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
11-24 16:41:21.359  5615  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
11-24 16:41:21.359  5615  5663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-24 16:41:21.360  5615  5663 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
11-24 16:41:21.363  5615  5615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-24 16:41:21.364  5615  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-24 16:41:21.365  5615  5663 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-24 16:41:21.365  5615  5663 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,11-24 16:41:21.367  5615  5615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-24 16:41:21.369  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-62,5,main], id: 62
11-24 16:41:21.369  5615  5663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,11-24 16:41:21.370  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-24 16:41:21.370  5615  5663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,11-24 16:41:21.370  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 0
,11-24 16:41:21.374  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-62,5,main], id: 62
,11-24 16:41:21.374  5615  5663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
11-24 16:41:21.374  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
11-24 16:41:21.374  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
11-24 16:41:21.374  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,11-24 16:41:21.374  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-62,5,main], id: 62
11-24 16:41:21.375  5615  5663 D BluetoothAdapter: STATE_ON
,11-24 16:41:21.377  4623  4636 D BtGatt.GattService: registerClient() - UUID=ff8e3263-cea2-4449-b49f-135b915ea42e
,11-24 16:41:21.378  4623  4685 D BtGatt.GattService: onClientRegistered() - UUID=ff8e3263-cea2-4449-b49f-135b915ea42e, clientIf=5
11-24 16:41:21.379  5615  5655 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,11-24 16:41:21.379  4623  4638 D BtGatt.GattService: start scan with filters
,11-24 16:41:21.382  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
,11-24 16:41:21.382  4623  4688 D BtGatt.ScanManager: handling starting scan
11-24 16:41:21.382  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-62,5,main], id: 62
11-24 16:41:21.382  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
11-24 16:41:21.382  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-62,5,main], id: 62
11-24 16:41:21.382  5615  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-24 16:41:21.382  5615  5615 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-24 16:41:21.382  5615  5615 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
,11-24 16:41:21.383  5615  5615 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
11-24 16:41:21.383  5615  5615 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-24 16:41:21.383  5615  5615 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-24 16:41:21.383  5615  5615 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
11-24 16:41:21.383  5615  5615 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-24 16:41:21.383  5615  5615 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING] Current thread: Thread[main,5,main], id: 1
11-24 16:41:21.384  5615  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,11-24 16:41:21.384  5615  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
,11-24 16:41:21.386  5615  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-24 16:41:21.386  5615  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
11-24 16:41:21.386  5615  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
,11-24 16:41:21.386  5615  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-24 16:41:21.387  5615  5663 I io.jxcore.node.ConnectionHelper: start: OK
11-24 16:41:21.387  5615  5615 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-24 16:41:21.389  5615  5615 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-24 16:41:21.389  5615  5615 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-24 16:41:21.389  5615  5615 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-24 16:41:21.389  5615  5615 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
11-24 16:41:21.390  5615  5663 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-24 16:41:21.390  5615  5663 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
11-24 16:41:21.390  5615  5663 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,11-24 16:41:21.390  5615  5663 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
11-24 16:41:21.390  5615  5663 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-24 16:41:21.390  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-24 16:41:21.390  5615  5663 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 16:41:21.390  5615  5663 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
11-24 16:41:21.390  5615  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-24 16:41:21.390  5615  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-62,5,main], id: 62
11-24 16:41:21.390  5615  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
11-24 16:41:21.390  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-24 16:41:21.390  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-62,5,main], id: 62
11-24 16:41:21.390  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-62,5,main], id: 62
11-24 16:41:21.390  4623  4685 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
11-24 16:41:21.391  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-62,5,main], id: 62
11-24 16:41:21.391  4623  4685 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 16:41:21.391  5615  5663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
11-24 16:41:21.391  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-62,5,main], id: 62
11-24 16:41:21.391  4623  4688 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
11-24 16:41:21.391  5615  5663 D BluetoothAdapter: STATE_ON
11-24 16:41:21.392  4623  4638 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
11-24 16:41:21.392  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-24 16:41:21.392  5615  5663 D BluetoothAdapter: STATE_ON
,11-24 16:41:21.393  4623  4843 D BtGatt.GattService: stopScan() - queue size =1
11-24 16:41:21.394  4623  4636 D BtGatt.GattService: unregisterClient() - clientIf=5
11-24 16:41:21.394  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-24 16:41:21.394  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-62,5,main], id: 62
11-24 16:41:21.394  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
11-24 16:41:21.394  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-62,5,main], id: 62
11-24 16:41:21.394  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-62,5,main], id: 62
11-24 16:41:21.394  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-62,5,main], id: 62
11-24 16:41:21.394  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-62,5,main], id: 62
11-24 16:41:21.395  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-24 16:41:21.395  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-62,5,main], id: 62
11-24 16:41:21.395  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-62,5,main], id: 62
11-24 16:41:21.395  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-62,5,main], id: 62
11-24 16:41:21.395  5615  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-24 16:41:21.395  5615  5663 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-24 16:41:21.395  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-24 16:41:21.396  5615  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-24 16:41:21.397  4623  4685 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
11-24 16:41:21.397  4623  4685 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 16:41:21.397  4623  4688 D BtGatt.ScanManager: Starting BLE batch scan
11-24 16:41:21.397  5615  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
,11-24 16:41:21.397  4623  4688 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
11-24 16:41:21.397  5615  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-24 16:41:21.397  5615  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-24 16:41:21.398  5615  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-24 16:41:21.398  5615  5663 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-24 16:41:21.398  5615  5663 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-24 16:41:21.398  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-24 16:41:21.398  5615  5663 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 16:41:21.398  5615  5663 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@dfc8756 not in the list
11-24 16:41:21.398  5615  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 16:41:21.398  5615  5663 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@84603d7 not in the list
11-24 16:41:21.398  5615  5663 D io.jxcore.node.ConnectivityMonitor: stop
11-24 16:41:21.398  5615  5663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
11-24 16:41:21.398  5615  5615 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-24 16:41:21.398  5615  5615 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,11-24 16:41:21.399  5615  5615 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-24 16:41:21.399  5615  5615 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-24 16:41:21.399  5615  5615 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-24 16:41:21.399  5615  5615 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
11-24 16:41:21.399  5615  5615 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-24 16:41:21.399  5615  5615 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-24 16:41:21.399  5615  5615 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-24 16:41:21.399  5615  5615 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-24 16:41:21.399  5615  5615 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED] Current thread: Thread[main,5,main], id: 1
11-24 16:41:21.399  5615  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-62,5,main], id: 62
11-24 16:41:21.399  5615  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
,11-24 16:41:21.401  5615  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
,11-24 16:41:21.401  5615  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-24 16:41:21.401  5615  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-24 16:41:21.401  5615  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-24 16:41:21.401  5615  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-24 16:41:21.401  5615  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-24 16:41:21.401  5615  5615 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-24 16:41:21.401  5615  5663 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@84603d7 not in the list
11-24 16:41:21.402  5615  5663 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
11-24 16:41:21.403  5615  5615 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-24 16:41:21.403  5615  5615 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-24 16:41:21.403  5615  5615 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
,11-24 16:41:21.405  5615  5663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-24 16:41:21.405  5615  5663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
11-24 16:41:21.408  4623  4685 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
11-24 16:41:21.408  4623  4685 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-24 16:41:21.414  4623  4685 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,11-24 16:41:21.414  4623  4685 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 16:41:21.414  5615  5663 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-24 16:41:21.414  5615  5663 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-24 16:41:21.414  5615  5663 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-24 16:41:21.414  5615  5663 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-24 16:41:21.414  5615  5663 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-24 16:41:21.414  5615  5663 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-24 16:41:21.414  5615  5663 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-24 16:41:21.414  5615  5663 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-24 16:41:21.414  5615  5663 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,11-24 16:41:21.415  4623  4688 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-24 16:41:21.416  5615  5663 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
11-24 16:41:21.416  5615  5663 D io.jxcore.node.ConnectivityMonitor: start: OK
11-24 16:41:21.416  5615  5663 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-24 16:41:21.417  5615  5663 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
11-24 16:41:21.417  5615  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
11-24 16:41:21.417  5615  5663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-24 16:41:21.417  5615  5663 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
11-24 16:41:21.420  4623  4685 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-24 16:41:21.420  5615  5615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-24 16:41:21.420  4623  4685 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 16:41:21.420  4623  4685 E BtGatt.ContextMap: Context not found for ID 5
,11-24 16:41:21.422  5615  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
,11-24 16:41:21.422  5615  5663 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-24 16:41:21.422  5615  5663 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
11-24 16:41:21.423  5615  5615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-24 16:41:21.425  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-62,5,main], id: 62
11-24 16:41:21.425  5615  5663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-24 16:41:21.426  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,11-24 16:41:21.426  5615  5663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-24 16:41:21.426  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 0
11-24 16:41:21.427  4623  4685 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
11-24 16:41:21.427  4623  4685 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 16:41:21.427  4623  4688 D BtGatt.ScanManager: stopping BLe Batch
11-24 16:41:21.428  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-62,5,main], id: 62
11-24 16:41:21.428  5615  5663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
11-24 16:41:21.428  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
11-24 16:41:21.428  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
11-24 16:41:21.428  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,11-24 16:41:21.428  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-62,5,main], id: 62
11-24 16:41:21.429  5615  5663 D BluetoothAdapter: STATE_ON
,11-24 16:41:21.431  4623  4835 D BtGatt.GattService: registerClient() - UUID=8dcadd63-d84b-4cd7-9502-8070b1aaadcf
11-24 16:41:21.431  4623  4685 D BtGatt.GattService: onClientRegistered() - UUID=8dcadd63-d84b-4cd7-9502-8070b1aaadcf, clientIf=5
11-24 16:41:21.431  4623  4685 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
11-24 16:41:21.431  5615  5625 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
11-24 16:41:21.431  4623  4685 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 16:41:21.432  4623  4688 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
11-24 16:41:21.432  4623  4636 D BtGatt.GattService: start scan with filters
,11-24 16:41:21.434  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
11-24 16:41:21.434  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-62,5,main], id: 62
11-24 16:41:21.434  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
11-24 16:41:21.434  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-62,5,main], id: 62
11-24 16:41:21.434  5615  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-24 16:41:21.434  5615  5615 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-24 16:41:21.434  5615  5615 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-24 16:41:21.434  5615  5615 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
11-24 16:41:21.434  5615  5615 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-24 16:41:21.435  5615  5615 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-24 16:41:21.435  5615  5615 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
11-24 16:41:21.435  5615  5615 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-24 16:41:21.435  5615  5615 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING] Current thread: Thread[main,5,main], id: 1
11-24 16:41:21.435  5615  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-24 16:41:21.436  5615  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-24 16:41:21.437  5615  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-24 16:41:21.437  5615  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
11-24 16:41:21.437  5615  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-24 16:41:21.438  5615  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-24 16:41:21.438  5615  5663 I io.jxcore.node.ConnectionHelper: start: OK
11-24 16:41:21.438  5615  5615 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-24 16:41:21.440  5615  5615 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
,11-24 16:41:21.440  5615  5615 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-24 16:41:21.440  5615  5615 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-24 16:41:21.440  5615  5615 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
11-24 16:41:21.441  4623  4685 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
11-24 16:41:21.441  4623  4685 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 16:41:21.441  4623  4685 D BtGatt.GattService: current time is 102002435779
11-24 16:41:21.441  4623  4685 D BtGatt.GattService: Batch record : [81, 34, 97, 112, -14, -5, 1, -128, -86, 0, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
11-24 16:41:21.441  4623  4685 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
,11-24 16:41:21.442  4623  4688 D BtGatt.ScanManager: handling starting scan
,11-24 16:41:21.447  4623  4685 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,11-24 16:41:21.447  4623  4685 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 16:41:21.448  4623  4688 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,11-24 16:41:21.452  4623  4685 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
,11-24 16:41:21.453  4623  4685 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 16:41:21.453  4623  4688 D BtGatt.ScanManager: Starting BLE batch scan
11-24 16:41:21.453  4623  4688 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,11-24 16:41:21.461  4623  4685 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,11-24 16:41:21.461  4623  4685 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-24 16:41:21.466  4623  4685 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
11-24 16:41:21.466  4623  4685 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-24 16:41:21.941  5615  5615 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
11-24 16:41:21.942  5615  5615 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,11-24 16:41:21.942  5615  5615 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,11-24 16:41:23.270   927  2912 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,11-24 16:41:23.276   927  2912 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 100] to 56
,11-24 16:41:24.726   927   937 I ActivityManager: Killing 5023:com.google.android.apps.maps/u0a58 (adj 15): empty #17
,11-24 16:41:26.292   927  2912 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,11-24 16:41:26.296   927  2912 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 100] to 60
,11-24 16:41:26.369   927  5338 D NetlinkSocketObserver: NeighborEvent{elapsedMs=106930, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,11-24 16:41:26.438  5615  5663 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-24 16:41:26.438  5615  5663 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,11-24 16:41:26.439  5615  5663 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
11-24 16:41:26.439  5615  5663 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-24 16:41:26.439  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,11-24 16:41:26.439  5615  5663 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,11-24 16:41:26.439  5615  5663 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,11-24 16:41:26.439  5615  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,11-24 16:41:26.440  5615  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-62,5,main], id: 62
,11-24 16:41:26.440  5615  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
11-24 16:41:26.440  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,11-24 16:41:26.440  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-62,5,main], id: 62
,11-24 16:41:26.440  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-62,5,main], id: 62
11-24 16:41:26.440  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-62,5,main], id: 62
11-24 16:41:26.441  5615  5663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
11-24 16:41:26.441  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-62,5,main], id: 62
11-24 16:41:26.443  5615  5663 D BluetoothAdapter: STATE_ON
11-24 16:41:26.443  4623  4638 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
11-24 16:41:26.444  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-24 16:41:26.445  5615  5663 D BluetoothAdapter: STATE_ON
11-24 16:41:26.445  4623  4688 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
11-24 16:41:26.447  4623  4843 D BtGatt.GattService: stopScan() - queue size =1
11-24 16:41:26.450  4623  4636 D BtGatt.GattService: unregisterClient() - clientIf=5
11-24 16:41:26.450  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-24 16:41:26.451  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-62,5,main], id: 62
11-24 16:41:26.451  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
11-24 16:41:26.451  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-62,5,main], id: 62
11-24 16:41:26.452  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-62,5,main], id: 62
11-24 16:41:26.452  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-62,5,main], id: 62
11-24 16:41:26.452  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-62,5,main], id: 62
11-24 16:41:26.456  4623  4623 D BtGatt.ScanManager: awakened up at time 107017
,11-24 16:41:26.455  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-24 16:41:26.457  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-62,5,main], id: 62
11-24 16:41:26.457  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-62,5,main], id: 62
11-24 16:41:26.457  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-62,5,main], id: 62
11-24 16:41:26.457  5615  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-24 16:41:26.457  5615  5663 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-24 16:41:26.458  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-24 16:41:26.458  5615  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-24 16:41:26.460  5615  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-24 16:41:26.460  5615  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,11-24 16:41:26.460  5615  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-24 16:41:26.460  5615  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-24 16:41:26.461  5615  5615 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-24 16:41:26.461  5615  5615 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-24 16:41:26.461  5615  5615 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-24 16:41:26.461  5615  5615 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
,11-24 16:41:26.461  5615  5615 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-24 16:41:26.461  5615  5615 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
11-24 16:41:26.461  5615  5615 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-24 16:41:26.461  5615  5615 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-24 16:41:26.462  5615  5615 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-24 16:41:26.462  5615  5615 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-24 16:41:26.462  5615  5615 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED] Current thread: Thread[main,5,main], id: 1
11-24 16:41:26.462  5615  5615 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-24 16:41:26.463  5615  5615 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-24 16:41:26.464  5615  5615 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-24 16:41:26.464  5615  5615 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
,11-24 16:41:26.473  4623  4685 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=6
,11-24 16:41:26.473  4623  4685 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 16:41:26.473  4623  4685 D BtGatt.GattService: current time is 107034609724
11-24 16:41:26.474  4623  4685 D BtGatt.GattService: Batch record : [37, -47, 14, -113, 116, -46, 1, -128, -91, 58, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 71, -122, -77, 84, 69, -12, 1, -128, -85, 89, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, -46, -4, -117, 6, 105, -37, 1, -128, -85, 61, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 35, 97, 126, -92, 22, -56, 1, -128, -88, 82, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 116, -43, -111, -91, -20, -29, 1, -128, -78, 62, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 81, 34, 97, 112, -14, -5, 1, -128, -93, 61, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
11-24 16:41:26.474  4623  4685 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
11-24 16:41:26.474  4623  4685 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
11-24 16:41:26.474  4623  4685 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
,11-24 16:41:26.474  4623  4685 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
11-24 16:41:26.475  4623  4685 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
11-24 16:41:26.475  4623  4685 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
,11-24 16:41:26.481  4623  4685 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
,11-24 16:41:26.481  4623  4685 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 16:41:26.481  4623  4688 D BtGatt.ScanManager: stopping BLe Batch
,11-24 16:41:26.488  4623  4685 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,11-24 16:41:26.488  4623  4685 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 16:41:26.488  4623  4688 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-24 16:41:26.495  4623  4685 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,11-24 16:41:26.495  4623  4685 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-24 16:41:26.963  5615  5615 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-24 16:41:26.963  5615  5615 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-24 16:41:26.963  5615  5615 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,11-24 16:41:31.462  5615  5663 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-24 16:41:31.462  5615  5663 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,11-24 16:41:31.463  5615  5663 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,11-24 16:41:31.463  5615  5663 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,11-24 16:41:31.463  5615  5663 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,11-24 16:41:31.463  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,11-24 16:41:31.463  5615  5663 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,11-24 16:41:31.463  5615  5663 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@dfc8756 not in the list
11-24 16:41:31.464  5615  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 16:41:31.464  5615  5663 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@84603d7 not in the list
11-24 16:41:31.464  5615  5663 D io.jxcore.node.ConnectivityMonitor: stop
11-24 16:41:31.464  5615  5663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
,11-24 16:41:31.467  5615  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-62,5,main], id: 62
11-24 16:41:31.467  5615  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-24 16:41:31.470  5615  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-24 16:41:31.470  5615  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
,11-24 16:41:31.470  5615  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-24 16:41:31.470  5615  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-24 16:41:31.471  5615  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-24 16:41:31.471  5615  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 16:41:31.471  5615  5663 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@84603d7 not in the list
11-24 16:41:31.472  5615  5663 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
11-24 16:41:31.474  5615  5663 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-24 16:41:31.474  5615  5663 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-24 16:41:31.474  5615  5663 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-24 16:41:31.474  5615  5663 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-24 16:41:31.475  5615  5663 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 16:41:31.475  5615  5663 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@dfc8756 not in the list
11-24 16:41:31.475  5615  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 16:41:31.475  5615  5663 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@84603d7 not in the list
11-24 16:41:31.475  5615  5663 D io.jxcore.node.ConnectivityMonitor: stop
,11-24 16:41:31.476  5615  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-62,5,main], id: 62
11-24 16:41:31.476  5615  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-24 16:41:31.478  5615  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-24 16:41:31.478  5615  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-24 16:41:31.479  5615  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-24 16:41:31.479  5615  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-24 16:41:31.479  5615  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-24 16:41:31.479  5615  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-24 16:41:31.479  5615  5663 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@84603d7 not in the list
11-24 16:41:31.481  5615  5663 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
11-24 16:41:31.481  5615  5663 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-24 16:41:31.481  5615  5663 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-24 16:41:31.481  5615  5663 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-24 16:41:31.481  5615  5663 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-24 16:41:31.481  5615  5663 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 16:41:31.481  5615  5663 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@dfc8756 not in the list
11-24 16:41:31.481  5615  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 16:41:31.482  5615  5663 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@84603d7 not in the list
,11-24 16:41:31.482  5615  5663 D io.jxcore.node.ConnectivityMonitor: stop
11-24 16:41:31.482  5615  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-62,5,main], id: 62
11-24 16:41:31.482  5615  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
,11-24 16:41:31.483  5615  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-24 16:41:31.483  5615  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-24 16:41:31.483  5615  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-24 16:41:31.483  5615  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-24 16:41:31.483  5615  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-24 16:41:31.483  5615  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 16:41:31.484  5615  5663 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@84603d7 not in the list
,11-24 16:41:31.484  5615  5663 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
11-24 16:41:31.485  5615  5663 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-24 16:41:31.485  5615  5663 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-24 16:41:31.485  5615  5663 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-24 16:41:31.485  5615  5663 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-24 16:41:31.485  5615  5663 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 16:41:31.485  5615  5663 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@dfc8756 not in the list
,11-24 16:41:31.485  5615  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 16:41:31.485  5615  5663 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@84603d7 not in the list
11-24 16:41:31.485  5615  5663 D io.jxcore.node.ConnectivityMonitor: stop
11-24 16:41:31.485  5615  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-62,5,main], id: 62
11-24 16:41:31.485  5615  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
,11-24 16:41:31.487  5615  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-24 16:41:31.487  5615  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-24 16:41:31.487  5615  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-24 16:41:31.487  5615  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-24 16:41:31.487  5615  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-24 16:41:31.487  5615  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 16:41:31.487  5615  5663 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@84603d7 not in the list
,11-24 16:41:31.488  5615  5663 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
11-24 16:41:31.488  5615  5663 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-24 16:41:31.488  5615  5663 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-24 16:41:31.488  5615  5663 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-24 16:41:31.488  5615  5663 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-24 16:41:31.488  5615  5663 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 16:41:31.489  5615  5663 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@dfc8756 not in the list
11-24 16:41:31.489  5615  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 16:41:31.489  5615  5663 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@84603d7 not in the list
11-24 16:41:31.489  5615  5663 D io.jxcore.node.ConnectivityMonitor: stop
,11-24 16:41:31.489  5615  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-62,5,main], id: 62
11-24 16:41:31.489  5615  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
,11-24 16:41:31.490  5615  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-24 16:41:31.490  5615  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-24 16:41:31.490  5615  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-24 16:41:31.490  5615  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-24 16:41:31.490  5615  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-24 16:41:31.491  5615  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-24 16:41:31.491  5615  5663 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@84603d7 not in the list
11-24 16:41:31.491  5615  5663 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
11-24 16:41:31.492  5615  5663 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-24 16:41:31.492  5615  5663 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-24 16:41:31.492  5615  5663 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
11-24 16:41:31.492  5615  5663 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-24 16:41:31.492  5615  5663 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-24 16:41:31.492  5615  5663 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
11-24 16:41:31.492  5615  5663 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,11-24 16:41:31.492  5615  5663 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,11-24 16:41:31.493  5615  5663 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-24 16:41:31.493  5615  5663 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,11-24 16:41:31.493  5615  5663 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-24 16:41:31.493  5615  5663 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,11-24 16:41:31.493  5615  5663 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 16:41:31.493  5615  5663 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@dfc8756 not in the list
,11-24 16:41:31.493  5615  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-24 16:41:31.493  5615  5663 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@84603d7 not in the list
11-24 16:41:31.493  5615  5663 D io.jxcore.node.ConnectivityMonitor: stop
11-24 16:41:31.494  5615  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-62,5,main], id: 62
11-24 16:41:31.494  5615  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
,11-24 16:41:31.495  5615  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-24 16:41:31.495  5615  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-24 16:41:31.495  5615  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-24 16:41:31.495  5615  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-24 16:41:31.495  5615  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-24 16:41:31.496  5615  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 16:41:31.496  5615  5663 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@84603d7 not in the list
11-24 16:41:31.496  5615  5663 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
11-24 16:41:31.497  5615  5663 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
11-24 16:41:31.497  5615  5663 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
11-24 16:41:31.500  5615  5663 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
11-24 16:41:31.500  5615  5663 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
11-24 16:41:31.501  5615  5663 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
11-24 16:41:31.501  5615  5663 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
11-24 16:41:31.501  5615  5663 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
11-24 16:41:31.501  5615  5663 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
11-24 16:41:31.501  5615  5663 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
,11-24 16:41:31.501  5615  5663 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
11-24 16:41:31.501  5615  5663 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
11-24 16:41:31.501  5615  5663 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
11-24 16:41:31.501  5615  5663 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
,11-24 16:41:31.501  5615  5663 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
11-24 16:41:31.501  5615  5663 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
11-24 16:41:31.501  5615  5663 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
11-24 16:41:31.501  5615  5663 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
11-24 16:41:31.501  5615  5663 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
11-24 16:41:31.501  5615  5663 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
,11-24 16:41:31.501  5615  5663 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
11-24 16:41:31.501  5615  5663 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
11-24 16:41:31.501  5615  5663 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
11-24 16:41:31.502  5615  5663 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
11-24 16:41:31.502  5615  5663 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
11-24 16:41:31.502  5615  5663 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
11-24 16:41:31.502  5615  5663 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
11-24 16:41:31.502  5615  5663 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
11-24 16:41:31.502  5615  5663 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
,11-24 16:41:31.502  5615  5663 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
11-24 16:41:31.502  5615  5663 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
11-24 16:41:31.502  5615  5663 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
11-24 16:41:31.502  5615  5663 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
11-24 16:41:31.502  5615  5663 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
11-24 16:41:31.502  5615  5663 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
11-24 16:41:31.502  5615  5663 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
11-24 16:41:31.503  5615  5663 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
11-24 16:41:31.503  5615  5663 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
,11-24 16:41:31.503  5615  5663 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
11-24 16:41:31.503  5615  5663 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
11-24 16:41:31.503  5615  5663 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
11-24 16:41:31.503  5615  5663 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
11-24 16:41:31.503  5615  5663 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
,11-24 16:41:31.503  5615  5663 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
,11-24 16:41:31.507  5615  5663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
,11-24 16:41:31.508  5615  5663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
11-24 16:41:31.508  5615  5663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
11-24 16:41:31.508  5615  5663 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
11-24 16:41:31.508  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
11-24 16:41:31.509  5615  5663 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
11-24 16:41:31.509  5615  5663 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,11-24 16:41:31.509  5615  5663 E io.jxcore.node.ConnectionHelper: connect: Callback is null
11-24 16:41:31.510  5615  5663 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-24 16:41:31.510  5615  5663 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-24 16:41:31.510  5615  5663 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-24 16:41:31.510  5615  5663 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-24 16:41:31.510  5615  5663 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 16:41:31.510  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
11-24 16:41:31.511  5615  5669 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 126)
11-24 16:41:31.512  5615  5669 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: tryToConnect:  socketConnectSucceeded = false, mIsShuttingDown = false
,11-24 16:41:31.512  5615  5669 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: socket closed
11-24 16:41:31.512  5615  5663 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@dfc8756 not in the list
11-24 16:41:31.512  5615  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-24 16:41:31.512  5615  5669 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: SYSTEM_DECIDED_INSECURE_RFCOMM_SOCKET_PORT
11-24 16:41:31.512  5615  5663 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@84603d7 not in the list
11-24 16:41:31.512  5615  5663 D io.jxcore.node.ConnectivityMonitor: stop
11-24 16:41:31.512  5615  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-62,5,main], id: 62
11-24 16:41:31.512  5615  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-24 16:41:31.513  5615  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 126
11-24 16:41:31.513  5615  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close
,11-24 16:41:31.514  5615  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
,11-24 16:41:31.514  5615  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-24 16:41:31.514  5615  5669 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: connecting
11-24 16:41:31.514  5615  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-24 16:41:31.514  5615  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-24 16:41:31.514  5615  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-24 16:41:31.515  5615  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 16:41:31.515  5615  5669 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-24 16:41:31.515  5615  5663 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@84603d7 not in the list
11-24 16:41:31.516  5615  5663 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
,11-24 16:41:31.516  5615  5663 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-24 16:41:31.516  5615  5663 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,11-24 16:41:31.516  5615  5663 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,11-24 16:41:31.516  5615  5663 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-24 16:41:31.516  5615  5663 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 16:41:31.517  5615  5663 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@dfc8756 not in the list
11-24 16:41:31.517  5615  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 16:41:31.517  5615  5663 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@84603d7 not in the list
11-24 16:41:31.517  5615  5663 D io.jxcore.node.ConnectivityMonitor: stop
11-24 16:41:31.517  5615  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-62,5,main], id: 62
11-24 16:41:31.517  5615  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-24 16:41:31.513  4638  4638 W Binder_2: type=1400 audit(0.0:115): avc: denied { ioctl } for path="socket:[32849]" dev="sockfs" ino=32849 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-24 16:41:31.516  4638  4638 W Binder_2: type=1400 audit(0.0:116): avc: denied { ioctl } for path="socket:[32849]" dev="sockfs" ino=32849 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,11-24 16:41:31.518  5615  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-24 16:41:31.518  5615  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-24 16:41:31.518  5615  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-24 16:41:31.518  5615  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,11-24 16:41:31.518  5615  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-24 16:41:31.518  5615  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 16:41:31.518  5615  5663 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@84603d7 not in the list
11-24 16:41:31.519  5615  5663 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
11-24 16:41:31.520  5615  5663 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-24 16:41:31.520  5615  5663 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-24 16:41:31.520  5615  5663 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-24 16:41:31.520  5615  5663 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-24 16:41:31.520  5615  5663 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 16:41:31.520  5615  5663 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@dfc8756 not in the list
,11-24 16:41:31.520  5615  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 16:41:31.520  5615  5663 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@84603d7 not in the list
11-24 16:41:31.520  5615  5663 D io.jxcore.node.ConnectivityMonitor: stop
11-24 16:41:31.520  5615  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-62,5,main], id: 62
11-24 16:41:31.520  5615  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-24 16:41:31.521  5615  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-24 16:41:31.521  5615  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-24 16:41:31.521  5615  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-24 16:41:31.521  5615  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-24 16:41:31.521  5615  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-24 16:41:31.521  5615  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 16:41:31.521  5615  5663 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@84603d7 not in the list
11-24 16:41:31.522  5615  5663 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
11-24 16:41:31.522  5615  5663 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
11-24 16:41:31.522  5615  5663 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
,11-24 16:41:31.523  5615  5663 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
11-24 16:41:31.523  5615  5663 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
11-24 16:41:31.523  5615  5663 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
11-24 16:41:31.523  5615  5663 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
11-24 16:41:31.523  5615  5663 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
11-24 16:41:31.523  5615  5663 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
11-24 16:41:31.523  5615  5663 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
11-24 16:41:31.523  5615  5663 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
11-24 16:41:31.523  5615  5663 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
11-24 16:41:31.523  5615  5663 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-24 16:41:31.523  5615  5663 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-24 16:41:31.523  5615  5663 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,11-24 16:41:31.523  5615  5663 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-24 16:41:31.523  5615  5663 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 16:41:31.523  5615  5663 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@dfc8756 not in the list
11-24 16:41:31.523  5615  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 16:41:31.523  5615  5663 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@84603d7 not in the list
11-24 16:41:31.523  5615  5663 D io.jxcore.node.ConnectivityMonitor: stop
11-24 16:41:31.524  5615  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-62,5,main], id: 62
11-24 16:41:31.524  5615  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-24 16:41:31.525  5615  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-24 16:41:31.525  5615  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-24 16:41:31.525  5615  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-24 16:41:31.525  5615  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,11-24 16:41:31.525  5615  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-24 16:41:31.525  5615  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 16:41:31.525  5615  5663 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@84603d7 not in the list
11-24 16:41:31.526  5615  5663 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-24 16:41:31.526  5615  5663 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 16:41:31.526  5615  5663 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@dfc8756 not in the list
11-24 16:41:31.526  5615  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 16:41:31.526  5615  5663 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@84603d7 not in the list
11-24 16:41:31.526  5615  5663 D io.jxcore.node.ConnectivityMonitor: stop
,11-24 16:41:32.957   535   535 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
11-24 16:41:32.958   535   535 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,11-24 16:41:36.527  5615  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 16:41:36.527  5615  5663 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@84603d7 not in the list
11-24 16:41:36.527  5615  5663 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-24 16:41:36.527  5615  5663 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 16:41:36.527  5615  5663 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@dfc8756 not in the list
,11-24 16:41:36.528  5615  5663 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-24 16:41:36.528  5615  5663 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-24 16:41:36.528  5615  5663 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-24 16:41:36.528  5615  5663 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-24 16:41:36.529  5615  5663 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,11-24 16:41:36.529  5615  5663 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@dfc8756 not in the list
11-24 16:41:36.529  5615  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 16:41:36.529  5615  5663 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@84603d7 not in the list
11-24 16:41:36.530  5615  5663 D io.jxcore.node.ConnectivityMonitor: stop
,11-24 16:41:36.530  5615  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-62,5,main], id: 62
11-24 16:41:36.530  5615  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
,11-24 16:41:36.534  5615  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-24 16:41:36.534  5615  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-24 16:41:36.534  5615  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
,11-24 16:41:36.535  5615  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-24 16:41:36.535  5615  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-24 16:41:36.535  5615  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 16:41:36.535  5615  5663 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@84603d7 not in the list
,11-24 16:41:36.538  5615  5663 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
,11-24 16:41:36.539  5615  5663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,11-24 16:41:36.539  5615  5663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
,11-24 16:41:36.544  5615  5663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,11-24 16:41:36.546  5615  5663 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,11-24 16:41:36.547  5615  5663 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
11-24 16:41:36.547  5615  5663 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
11-24 16:41:36.547  5615  5671 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
,11-24 16:41:36.548  5615  5663 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
11-24 16:41:36.548  5615  5663 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
11-24 16:41:36.548  5615  5615 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
,11-24 16:41:36.548  5615  5663 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,11-24 16:41:36.549  5615  5671 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-24 16:41:36.548  5615  5663 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
11-24 16:41:36.550  5615  5663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
11-24 16:41:36.550  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
11-24 16:41:36.550  5615  5663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
11-24 16:41:36.551  5615  5663 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
11-24 16:41:36.551  5615  5663 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
,11-24 16:41:36.551  5615  5663 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@dfc8756 not in the list
11-24 16:41:36.551  5615  5615 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
11-24 16:41:36.551  5615  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-24 16:41:36.551  5615  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-24 16:41:36.551  5615  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-62,5,main], id: 62
11-24 16:41:36.551  5615  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
,11-24 16:41:36.551  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-24 16:41:36.552  5615  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-24 16:41:36.553  5615  5671 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
,11-24 16:41:36.553  5615  5671 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
11-24 16:41:36.553  5615  5671 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
11-24 16:41:36.546  4843  4843 W Binder_4: type=1400 audit(0.0:117): avc: denied { ioctl } for path="socket:[31184]" dev="sockfs" ino=31184 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,11-24 16:41:36.546  4843  4843 W Binder_4: type=1400 audit(0.0:118): avc: denied { ioctl } for path="socket:[31184]" dev="sockfs" ino=31184 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-24 16:41:36.554  5615  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-24 16:41:36.554  5615  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-24 16:41:36.554  5615  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
,11-24 16:41:36.554  5615  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-24 16:41:36.554  5615  5663 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@84603d7 not in the list
11-24 16:41:36.554  5615  5615 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-24 16:41:36.554  5615  5663 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-24 16:41:36.555  5615  5615 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-24 16:41:36.555  5615  5663 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,11-24 16:41:36.555  5615  5615 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
11-24 16:41:36.555  5615  5663 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-24 16:41:36.555  5615  5615 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 16:41:36.555  5615  5663 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,11-24 16:41:36.555  5615  5615 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-24 16:41:36.555  5615  5663 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 16:41:36.555  5615  5663 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@dfc8756 not in the list
11-24 16:41:36.555  5615  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-24 16:41:36.555  5615  5663 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@84603d7 not in the list
11-24 16:41:36.555  5615  5663 D io.jxcore.node.ConnectivityMonitor: stop
,11-24 16:41:36.556  5615  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-62,5,main], id: 62
11-24 16:41:36.556  5615  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-24 16:41:36.557  5615  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
,11-24 16:41:36.558  5615  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-24 16:41:36.558  5615  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-24 16:41:36.558  5615  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-24 16:41:36.558  5615  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-24 16:41:36.558  5615  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-24 16:41:36.558  5615  5663 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@84603d7 not in the list
11-24 16:41:36.560  5615  5663 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
11-24 16:41:36.560  5615  5663 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
11-24 16:41:36.561  5615  5663 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
11-24 16:41:36.561  5615  5663 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-24 16:41:36.561  5615  5663 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-24 16:41:36.561  5615  5663 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-24 16:41:36.561  5615  5663 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-24 16:41:36.561  5615  5663 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-24 16:41:36.561  5615  5663 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-24 16:41:36.562  5615  5663 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 16:41:36.562  5615  5663 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@dfc8756 not in the list
11-24 16:41:36.562  5615  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 16:41:36.563  5615  5663 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@84603d7 not in the list
11-24 16:41:36.564  5615  5663 D io.jxcore.node.ConnectivityMonitor: stop
11-24 16:41:36.564  5615  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-62,5,main], id: 62
,11-24 16:41:36.565  5615  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-24 16:41:36.569  5615  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-24 16:41:36.569  5615  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-24 16:41:36.569  5615  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-24 16:41:36.569  5615  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-24 16:41:36.569  5615  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-24 16:41:36.569  5615  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-24 16:41:36.570  5615  5663 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@84603d7 not in the list
,11-24 16:41:36.575  5615  5663 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-24 16:41:36.575  5615  5663 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-24 16:41:36.576  5615  5663 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,11-24 16:41:36.576  5615  5663 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-24 16:41:36.576  5615  5663 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 16:41:36.576  5615  5663 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@dfc8756 not in the list
11-24 16:41:36.576  5615  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-24 16:41:36.576  5615  5663 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@84603d7 not in the list
11-24 16:41:36.576  5615  5663 D io.jxcore.node.ConnectivityMonitor: stop
11-24 16:41:36.576  5615  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-62,5,main], id: 62
11-24 16:41:36.576  5615  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-24 16:41:36.578  5615  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-24 16:41:36.578  5615  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
,11-24 16:41:36.578  5615  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-24 16:41:36.578  5615  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-24 16:41:36.578  5615  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-24 16:41:36.578  5615  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 16:41:36.578  5615  5663 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@84603d7 not in the list
,11-24 16:41:36.580  5615  5663 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-24 16:41:36.581  5615  5663 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,11-24 16:41:36.581  5615  5663 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-24 16:41:36.581  5615  5663 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-24 16:41:36.581  5615  5663 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 16:41:36.581  5615  5663 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@dfc8756 not in the list
11-24 16:41:36.581  5615  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 16:41:36.581  5615  5663 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@84603d7 not in the list
11-24 16:41:36.581  5615  5663 D io.jxcore.node.ConnectivityMonitor: stop
,11-24 16:41:36.581  5615  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-62,5,main], id: 62
11-24 16:41:36.581  5615  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-24 16:41:36.583  5615  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-24 16:41:36.583  5615  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-24 16:41:36.583  5615  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-24 16:41:36.583  5615  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-24 16:41:36.583  5615  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,11-24 16:41:36.583  5615  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 16:41:36.583  5615  5663 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@84603d7 not in the list
11-24 16:41:36.584  5615  5663 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
11-24 16:41:36.584  5615  5663 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
11-24 16:41:36.585  5615  5663 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
11-24 16:41:36.585  5615  5663 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
11-24 16:41:36.585  5615  5663 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
,11-24 16:41:36.585  5615  5663 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
11-24 16:41:36.587  5615  5663 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
11-24 16:41:36.587  5615  5663 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
11-24 16:41:36.587  5615  5663 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
11-24 16:41:36.588  5615  5663 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
11-24 16:41:36.588  5615  5663 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
11-24 16:41:36.588  5615  5663 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
,11-24 16:41:36.588  5615  5663 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
11-24 16:41:36.588  5615  5663 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
11-24 16:41:36.588  5615  5663 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
11-24 16:41:36.588  5615  5663 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
11-24 16:41:36.589  5615  5663 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
11-24 16:41:36.589  5615  5663 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
11-24 16:41:36.590  5615  5663 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
,11-24 16:41:36.590  5615  5663 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
11-24 16:41:36.592  5615  5663 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-24 16:41:36.592  5615  5663 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@a8976f4 added. We now have 3 listener(s)
11-24 16:41:36.592  5615  5663 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-24 16:41:36.595  5615  5663 D BluetoothAdapter: enable(): BT is already enabled..!
,11-24 16:41:36.595   927  3741 D WifiService: setWifiEnabled: true pid=5615, uid=10077
11-24 16:41:36.595   927  3741 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-24 16:41:36.646  4623  4818 W bt_sdp  : SDP - Rcvd conn cnf with error: 0x4  CID 0x40
,11-24 16:41:36.647  5615  5669 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: connect, read failed, socket might closed or timeout, read ret: -1
,11-24 16:41:36.647  4623  4821 E bt_btif_sock_rfcomm: find_rfc_slot_by_id unable to find RFCOMM slot id: 5
11-24 16:41:36.647  5615  5669 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: socketConnectSucceeded false
11-24 16:41:36.647  5615  5669 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 126)
,11-24 16:41:37.056  5615  5615 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-24 16:41:37.959   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 16:41:38.399   927  2912 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,11-24 16:41:38.960   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 16:41:39.961   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 16:41:40.129   927  2910 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-24 16:41:40.962   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 16:41:41.415   927  2912 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,11-24 16:41:41.601  5615  5663 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,11-24 16:41:41.602  5615  5663 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@37e2e1d added. We now have 4 listener(s)
11-24 16:41:41.602  5615  5663 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-24 16:41:41.614  5615  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-24 16:41:41.614  5615  5663 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@37e2e1d removed from the list
11-24 16:41:41.615  5615  5663 D io.jxcore.node.ConnectivityMonitor: stop
11-24 16:41:41.616  5615  5663 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-24 16:41:41.617  5615  5663 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@634a892 added. We now have 4 listener(s)
11-24 16:41:41.617  5615  5663 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-24 16:41:41.620  5615  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-24 16:41:41.621  5615  5663 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@634a892 removed from the list
11-24 16:41:41.621  5615  5663 D io.jxcore.node.ConnectivityMonitor: stop
,11-24 16:41:41.623  5615  5663 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-24 16:41:41.623  5615  5663 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2b47263 added. We now have 4 listener(s)
11-24 16:41:41.623  5615  5663 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-24 16:41:41.628   927  3655 D WifiService: setWifiEnabled: false pid=5615, uid=10077
11-24 16:41:41.629   927  3655 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-24 16:41:41.634   927  2910 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,11-24 16:41:41.634   927  2910 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
11-24 16:41:41.634   927  2910 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,11-24 16:41:41.635   927  2910 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-24 16:41:41.644  5615  5663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-24 16:41:41.644  5615  5663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
11-24 16:41:41.644  4623  4681 D BluetoothAdapterState: Current state: ON, message: 23
11-24 16:41:41.644  4623  4681 D BluetoothAdapterProperties: Setting state to 13
,11-24 16:41:41.644  4623  4681 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
11-24 16:41:41.646  4623  4681 D BluetoothAdapterProperties: onBluetoothDisable()
,11-24 16:41:41.647  4623  4681 I BluetoothAdapterState: Entering PendingCommandState
11-24 16:41:41.650  4623  4685 D BluetoothAdapterProperties: Scan Mode:20
11-24 16:41:41.650  4623  4681 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
,11-24 16:41:41.653  5615  5663 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,11-24 16:41:41.653  5615  5663 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-24 16:41:41.653  5615  5663 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-24 16:41:41.653  5615  5663 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-24 16:41:41.653  5615  5663 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-24 16:41:41.653  5615  5663 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-24 16:41:41.653  5615  5663 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-24 16:41:41.653  5615  5663 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-24 16:41:41.653  5615  5663 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-24 16:41:41.653  5615  5663 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,11-24 16:41:41.653   927  5339 D DhcpClient: Clearing IP address
11-24 16:41:41.654   506   918 D CommandListener: Clearing all IP addresses on wlan0
11-24 16:41:41.654  4623  4623 D HeadsetService: Received stop request...Stopping profile...
11-24 16:41:41.655  5615  5663 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,11-24 16:41:41.655  5615  5663 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
11-24 16:41:41.655  5615  5663 D io.jxcore.node.ConnectivityMonitor: start: OK
11-24 16:41:41.660  3105  3117 D BluetoothHeadset: Proxy object disconnected
11-24 16:41:41.660   927   927 D BluetoothHeadset: Proxy object disconnected
11-24 16:41:41.660  3105  3105 D HeadsetProfile: Bluetooth service disconnected
11-24 16:41:41.661  3743  3767 D BluetoothHeadset: Proxy object disconnected
11-24 16:41:41.661   927   927 D BluetoothHeadset: Proxy object disconnected
11-24 16:41:41.661  5615  5615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-24 16:41:41.661   927   927 D BluetoothHeadset: Proxy object disconnected
11-24 16:41:41.663  4623  4623 D A2dpService: Received stop request...Stopping profile...
11-24 16:41:41.664  4623  4838 D A2dpStateMachine: Exit Disconnected: -1
11-24 16:41:41.666   506   918 D CommandListener: Setting iface cfg
11-24 16:41:41.667  5615  5615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-24 16:41:41.670  3526  5396 V NativeCrypto: Read error: ssl=0x7f90461000: I/O error during system call, Connection timed out
11-24 16:41:41.670  5615  5615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-24 16:41:41.671  3105  3105 D BluetoothA2dp: Proxy object disconnected
11-24 16:41:41.671  4623  4623 V BluetoothAdapterState: isTurningOff()=true
11-24 16:41:41.671  4623  4623 V BluetoothAdapterState: isTurningOn()=false
11-24 16:41:41.672  4623  4623 V BluetoothAdapterState: isBleTurningOn()=false
11-24 16:41:41.672  4623  4623 V BluetoothAdapterState: isBleTurningOff()=false
11-24 16:41:41.672  3526  5396 V NativeCrypto: SSL shutdown failed: ssl=0x7f90461000: I/O error during system call, Broken pipe
11-24 16:41:41.672   927   927 D BluetoothA2dp: Proxy object disconnected
,11-24 16:41:41.675  4623  4623 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
,11-24 16:41:41.675  4623  4623 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
11-24 16:41:41.675  4623  4818 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,11-24 16:41:41.675  4623  4818 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,11-24 16:41:41.675   927  3747 D ConnectivityService: reportNetworkConnectivity(100, false) by 10012
,11-24 16:41:41.675  4623  4818 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-24 16:41:41.675  4623  4685 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
11-24 16:41:41.675  4623  4685 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
11-24 16:41:41.676   927  5337 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Forcing reevaluation for UID 10012
11-24 16:41:41.676  4623  4623 D HidService: Received stop request...Stopping profile...
11-24 16:41:41.676  4623  4623 D HidService: Stopping Bluetooth HidService
11-24 16:41:41.676  3105  3105 D BluetoothInputDevice: Proxy object disconnected
11-24 16:41:41.677  3105  3105 D HidProfile: Bluetooth service disconnected
11-24 16:41:41.678   927  5337 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.gstatic.com": No address associated with hostname
11-24 16:41:41.678   927  2912 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] validation failed
11-24 16:41:41.679  4623  4623 D HealthService: Received stop request...Stopping profile...
11-24 16:41:41.679   927  2912 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
11-24 16:41:41.680   927  2912 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
11-24 16:41:41.680  4623  4623 D PanService: Received stop request...Stopping profile...
11-24 16:41:41.682  3105  3105 D BluetoothPan: BluetoothPAN Proxy object disconnected
11-24 16:41:41.682  3105  3105 D PanProfile: Bluetooth service disconnected
,11-24 16:41:41.682  4623  4623 D BluetoothMapService: Received stop request...Stopping profile...
11-24 16:41:41.682  4623  4623 D BluetoothMapService: stop()
11-24 16:41:41.683  4623  4623 D BluetoothMapAppObserver: deinitObservers()
11-24 16:41:41.683  4623  4623 D BluetoothMapAppObserver: removeReceiver()
,11-24 16:41:41.684   927  5340 D DhcpClient: Receive thread stopped
11-24 16:41:41.688   927  2912 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
11-24 16:41:41.688   927  2912 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
11-24 16:41:41.688   533   533 E Parcel  : Reading a NULL string not supported here.
11-24 16:41:41.691  4623  4623 D SapService: Received stop request...Stopping profile...
11-24 16:41:41.691  4623  4623 V SapService: stop()
,11-24 16:41:41.693  3105  3105 D BluetoothMap: Proxy object disconnected
11-24 16:41:41.693  3105  3105 D MapProfile: Bluetooth service disconnected
,11-24 16:41:41.693  4623  4623 V BluetoothAdapterState: isTurningOff()=true
11-24 16:41:41.693  4623  4623 V BluetoothAdapterState: isTurningOn()=false
11-24 16:41:41.693  4623  4623 V BluetoothAdapterState: isBleTurningOn()=false
11-24 16:41:41.693  4623  4623 V BluetoothAdapterState: isBleTurningOff()=false
11-24 16:41:41.695  4623  4818 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-24 16:41:41.695  4623  4818 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-24 16:41:41.695  4623  4623 V BluetoothAdapterState: isTurningOff()=true
11-24 16:41:41.695  4623  4623 V BluetoothAdapterState: isTurningOn()=false
11-24 16:41:41.695  4623  4623 V BluetoothAdapterState: isBleTurningOn()=false
,11-24 16:41:41.695  4623  4623 V BluetoothAdapterState: isBleTurningOff()=false
,11-24 16:41:41.695  4623  4818 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,11-24 16:41:41.695  4623  4818 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,11-24 16:41:41.695  4623  4818 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
11-24 16:41:41.695  4623  4818 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
11-24 16:41:41.696  4623  4685 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
,11-24 16:41:41.696  4623  4623 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
,11-24 16:41:41.696  4623  4623 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
,11-24 16:41:41.696  4623  4685 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
11-24 16:41:41.696  4623  4623 V BluetoothAdapterState: isTurningOff()=true
11-24 16:41:41.696  4623  4623 V BluetoothAdapterState: isTurningOn()=false
11-24 16:41:41.696  4623  4623 V BluetoothAdapterState: isBleTurningOn()=false
11-24 16:41:41.696  4623  4623 V BluetoothAdapterState: isBleTurningOff()=false
,11-24 16:41:41.696  4623  4623 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
11-24 16:41:41.696  4623  4685 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
11-24 16:41:41.697  4623  4623 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
11-24 16:41:41.697  4623  4623 V BluetoothAdapterState: isTurningOff()=true
11-24 16:41:41.697  4623  4623 V BluetoothAdapterState: isTurningOn()=false
11-24 16:41:41.697  4623  4623 V BluetoothAdapterState: isBleTurningOn()=false
11-24 16:41:41.697  4623  4623 V BluetoothAdapterState: isBleTurningOff()=false
11-24 16:41:41.697  4623  4623 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
,11-24 16:41:41.698  4623  4623 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
11-24 16:41:41.698   927  2912 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
11-24 16:41:41.699   927   927 D RttService: SCAN_AVAILABLE : 1
11-24 16:41:41.699   927  3020 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
11-24 16:41:41.702  4623  4623 D BluetoothMapService: MAP Service closeService in
11-24 16:41:41.702  4623  4623 D BluetoothMapMasInstance0: MAP Service shutdown
11-24 16:41:41.702  4623  4623 D ObexServerSockets0: shutdown(block = true)
11-24 16:41:41.702  3708  3826 W QCNEJ   : |CORE| network lost: 100
11-24 16:41:41.703  4623  4623 D ObexServerSockets0: shutdown called from another thread - interrupt().
11-24 16:41:41.703  3708  3826 W QCNEJ   : |CORE| onLost: unbind the process to WIFI
,11-24 16:41:41.703  4623  4623 D ObexServerSockets0: shutdown called from another thread - interrupt().
11-24 16:41:41.703  4623  4846 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
11-24 16:41:41.703  4623  4845 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 5
11-24 16:41:41.704  4623  4821 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
11-24 16:41:41.704  4623  4623 V BluetoothAdapterState: isTurningOff()=true
11-24 16:41:41.704  4623  4623 V BluetoothAdapterState: isTurningOn()=false
11-24 16:41:41.704  4623  4623 V BluetoothAdapterState: isBleTurningOn()=false
11-24 16:41:41.704  4623  4623 V BluetoothAdapterState: isBleTurningOff()=false
11-24 16:41:41.704  5615  5615 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-24 16:41:41.704  4623  4623 D BluetoothMapService: cleanup()
11-24 16:41:41.704  5615  5615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-24 16:41:41.704  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-24 16:41:41.704  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-24 16:41:41.704  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-24 16:41:41.704  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-24 16:41:41.704  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-24 16:41:41.704  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-24 16:41:41.704  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-24 16:41:41.704  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-24 16:41:41.704  4623  4623 D BluetoothMapService: MAP Service closeService in
11-24 16:41:41.705  4623  4623 V BluetoothAdapterState: isTurningOff()=true
11-24 16:41:41.706  4623  4623 V BluetoothAdapterState: isTurningOn()=false
11-24 16:41:41.706  4623  4623 V BluetoothAdapterState: isBleTurningOn()=false
11-24 16:41:41.706  4623  4623 V BluetoothAdapterState: isBleTurningOff()=false
11-24 16:41:41.706  4623  4681 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
11-24 16:41:41.705  5615  5615 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-24 16:41:41.706  4623  4681 D BluetoothAdapterProperties: Setting state to 15
11-24 16:41:41.706  4623  4623 I BtOppRfcommListener: stopping Accept Thread
11-24 16:41:41.706  4623  4681 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
11-24 16:41:41.706  4623  5265 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
11-24 16:41:41.706  5615  5615 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
11-24 16:41:41.707  4623  5265 I BtOppRfcommListener: BluetoothSocket listen thread finished
11-24 16:41:41.707  4623  4681 I BluetoothAdapterState: Entering BleOnState
,11-24 16:41:41.716   927  2910 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,11-24 16:41:41.717   927  2910 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,11-24 16:41:41.717   927  3489 I ActivityManager: Start proc 5682:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
11-24 16:41:41.718   927   944 D BluetoothA2dp: onBluetoothStateChange: up=false
11-24 16:41:41.719   927   944 D BluetoothHeadset: onBluetoothStateChange: up=false
11-24 16:41:41.719  3105  3952 D BluetoothPbap: onBluetoothStateChange: up=false
11-24 16:41:41.721  3105  3117 D BluetoothInputDevice: onBluetoothStateChange: up=false
,11-24 16:41:41.722  3105  3293 D BluetoothA2dp: onBluetoothStateChange: up=false
,11-24 16:41:41.723  3105  3118 D BluetoothMap: onBluetoothStateChange: up=false
,11-24 16:41:41.724  3105  3952 D BluetoothPan: onBluetoothStateChange on: false
,11-24 16:41:41.724   927   944 D BluetoothHeadset: onBluetoothStateChange: up=false
11-24 16:41:41.725  3743  3765 D BluetoothHeadset: onBluetoothStateChange: up=false
11-24 16:41:41.725  3105  3118 D BluetoothHeadset: onBluetoothStateChange: up=false
11-24 16:41:41.725   927   944 D BluetoothHeadset: onBluetoothStateChange: up=false
11-24 16:41:41.726  4623  4681 D BluetoothAdapterState: Current state: BLE ON, message: 20
11-24 16:41:41.726  4623  4681 D BluetoothAdapterProperties: Setting state to 16
11-24 16:41:41.726  4623  4681 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
11-24 16:41:41.726   506   918 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
11-24 16:41:41.728  4623  4681 D BluetoothAdapterProperties: onBleDisable
11-24 16:41:41.728  4623  4681 I BluetoothAdapterState: Entering PendingCommandState
11-24 16:41:41.728  4623  4682 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
,11-24 16:41:41.729  4623  4685 D BluetoothAdapterProperties: Scan Mode:20
11-24 16:41:41.729  4623  4818 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
,11-24 16:41:41.729  4623  4818 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-24 16:41:41.730  5615  5615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-24 16:41:41.732  5615  5615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-24 16:41:41.757   506   918 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-24 16:41:41.758   506   918 D CommandListener: Clearing all IP addresses on wlan0
11-24 16:41:41.758   506   918 D TetherController: Setting IP forward enable = 0
11-24 16:41:41.759   927  2912 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
11-24 16:41:41.760   927  2912 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,11-24 16:41:41.761   927  2910 D DhcpClient: doQuit
11-24 16:41:41.761   927  2910 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,11-24 16:41:41.762  3411  3411 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
11-24 16:41:41.763   927  5339 D DhcpClient: onQuitting
11-24 16:41:41.763   927   944 D Tethering: MasterInitialState.processMessage what=3
11-24 16:41:41.765  5237  5237 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@ec17a1 and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
11-24 16:41:41.766  3938  3938 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
11-24 16:41:41.767  5615  5615 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-24 16:41:41.767  5615  5615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-24 16:41:41.767  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-24 16:41:41.767  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-24 16:41:41.767  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-24 16:41:41.767  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-24 16:41:41.767  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-24 16:41:41.767  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-24 16:41:41.767  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-24 16:41:41.767  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,11-24 16:41:41.769  5615  5615 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,11-24 16:41:41.769  5615  5615 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
,11-24 16:41:41.770  5615  5615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-24 16:41:41.770  5011  5035 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
,11-24 16:41:41.771  5011  5035 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
,11-24 16:41:41.771  5011  5035 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,0,0,0
11-24 16:41:41.772  5011  5035 E SarControlService: no key has been found,reset the power
11-24 16:41:41.772  5011  5048 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
11-24 16:41:41.772  5011  5048 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
11-24 16:41:41.772  5011  5048 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
11-24 16:41:41.773  5036  5036 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
11-24 16:41:41.773  5036  5036 D QcrilMsgTunnelSocket: [1002] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
,11-24 16:41:41.774  5011  5048 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
,11-24 16:41:41.774  5011  5048 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
,11-24 16:41:41.774  5011  5048 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
,11-24 16:41:41.775  5036  5036 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
11-24 16:41:41.775  5036  5036 D QcrilMsgTunnelSocket: [1003] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
11-24 16:41:41.777  5036  5050 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@864bbcf HexData = [00000000ea03000000000000ffffffff]
,11-24 16:41:41.777  5036  5050 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
,11-24 16:41:41.777  5036  5050 D QcrilMsgTunnelSocket: [1002] < OEM_HOOK_RAW [null]
11-24 16:41:41.777  5036  5036 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
11-24 16:41:41.777  5011  5021 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
11-24 16:41:41.784  5682  5682 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm64
11-24 16:41:41.784  5036  5050 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@864bbcf HexData = [00000000eb03000000000000ffffffff]
11-24 16:41:41.785  5036  5050 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-24 16:41:41.785  5036  5050 D QcrilMsgTunnelSocket: [1003] < OEM_HOOK_RAW [null]
11-24 16:41:41.785  5036  5036 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
11-24 16:41:41.786  5011  5022 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
11-24 16:41:41.786  3411  3411 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
11-24 16:41:41.793  3411  3411 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,11-24 16:41:41.802  5682  5682 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,11-24 16:41:41.807   927   944 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@272168c:true
11-24 16:41:41.808  3526  3526 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,11-24 16:41:41.819  3411  3411 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,11-24 16:41:41.821   927  3811 I ActivityManager: Start proc 5704:com.google.android.apps.maps/u0a58 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,11-24 16:41:41.836  3411  3411 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
11-24 16:41:41.835  5682  5682 D LocalBluetoothProfileManager: Adding local MAP profile
11-24 16:41:41.843  5682  5682 D BluetoothMap: Create BluetoothMap proxy object
11-24 16:41:41.855  5682  5682 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,11-24 16:41:41.865  5704  5704 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm64
,11-24 16:41:41.870  5682  5682 D DockEventReceiver: finishStartingService: stopping service
,11-24 16:41:41.876   927   938 I ActivityManager: Killing 5368:com.android.sdm.plugins.sprintdm/1001 (adj 15): empty #17
,11-24 16:41:41.933  4623  4685 I bt_hci  : shut_down
,11-24 16:41:41.937  4623  4689 D bt_hwcfg: hw_epilog_process
11-24 16:41:41.937  4623  4689 I bt_vendor: low_power_mode_cb
,11-24 16:41:41.938   927  2910 D wifi    : In wifi stop Hal
11-24 16:41:41.938  4977  4977 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,11-24 16:41:41.939   927  2910 D wifi    : halHandle = 0x7f8e691e00, mVM = 0x7faaccd140, mCls = 0x100a02
11-24 16:41:41.939   927  3410 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
11-24 16:41:41.939   927  3410 D WifiHAL : Got a signal to exit!!!
11-24 16:41:41.939   927  3410 I WifiHAL : Exit wifi_event_loop
11-24 16:41:41.939   927  2910 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 11
11-24 16:41:41.940   927  2910 E WifiHAL : Event processing terminated
11-24 16:41:41.940   927  2910 D wifi    : In wifi cleaned up handler
11-24 16:41:41.940   927  2910 I WifiHAL : Internal cleanup completed
11-24 16:41:41.940  4623  4689 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
11-24 16:41:41.940  4623  4689 I bt_vendor: epilog_cb
11-24 16:41:41.940  4623  4689 I bt_hci  : epilog_finished_callback
11-24 16:41:41.941  3988  4159 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,11-24 16:41:41.943  5615  5615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-24 16:41:41.943  4623  4685 I bt_hci_h4: hal_close
,11-24 16:41:41.944  4623  4685 I bt_userial_vendor: device fd = 54 close
,11-24 16:41:41.961   927  3410 D wifi    : set interface wlan0 flags (DOWN)
,11-24 16:41:41.962   927  2910 D WifiNative-HAL: HAL event thread stopped successfully
11-24 16:41:41.962   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 16:41:42.051  4623  4682 D bt_stack_manager: event_shut_down_stack finished.
,11-24 16:41:42.051  4623  4681 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
11-24 16:41:42.052  4623  4681 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
11-24 16:41:42.053  4623  4623 D BtGatt.DebugUtils: handleDebugAction() action=null
11-24 16:41:42.053  4623  4623 D BtGatt.GattService: Received stop request...Stopping profile...
11-24 16:41:42.053  4623  4623 D BtGatt.GattService: stop()
,11-24 16:41:42.053  4623  4623 D BtGatt.AdvertiseManager: advertise clients cleared
11-24 16:41:42.055  4623  4623 V BluetoothAdapterState: isTurningOff()=false
11-24 16:41:42.055  4623  4623 V BluetoothAdapterState: isTurningOn()=false
11-24 16:41:42.055  4623  4623 V BluetoothAdapterState: isBleTurningOn()=false
11-24 16:41:42.055  4623  4623 V BluetoothAdapterState: isBleTurningOff()=true
11-24 16:41:42.055  4623  4681 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
11-24 16:41:42.055  5704  5704 D StrictMode: StrictMode policy violation; ~duration=111 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-24 16:41:42.055  5704  5704 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-24 16:41:42.055  5704  5704 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
11-24 16:41:42.055  5704  5704 D StrictMode: 	at java.io.File.doAccess(File.java:281)
11-24 16:41:42.055  5704  5704 D StrictMode: 	at java.io.File.exists(File.java:361)
11-24 16:41:42.055  5704  5704 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
11-24 16:41:42.055  5704  5704 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
11-24 16:41:42.055  5704  5704 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
11-24 16:41:42.055  5704  5704 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
11-24 16:41:42.055  5704  5704 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
11-24 16:41:42.055  5704  5704 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
11-24 16:41:42.055  5704  5704 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-24 16:41:42.055  5704  5704 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-24 16:41:42.055  5704  5704 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-24 16:41:42.055  5704  5704 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-24 16:41:42.055  5704  5704 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-24 16:41:42.055  5704  5704 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-24 16:41:42.055  5704  5704 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-24 16:41:42.055  5704  5704 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-24 16:41:42.055  5704  5704 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-24 16:41:42.055  5704  5704 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-24 16:41:42.055  5704  5704 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-24 16:41:42.055  5704  5704 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-24 16:41:42.055  5704  5704 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-24 16:41:42.055  5704  5704 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-24 16:41:42.055  5704  5704 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-24 16:41:42.055  5704  5704 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-24 16:41:42.055  5704  5704 D StrictMode: StrictMode policy violation; ~duration=110 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-24 16:41:42.055  5704  5704 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-24 16:41:42.055  5704  5704 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
11-24 16:41:42.055  5704  5704 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
11-24 16:41:42.055  5704  5704 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
11-24 1,6:41:42.055  5704  5704 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
11-24 16:41:42.055  5704  5704 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
11-24 16:41:42.055  5704  5704 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
11-24 16:41:42.055  5704  5704 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
11-24 16:41:42.055  5704  5704 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-24 16:41:42.055  5704  5704 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-24 16:41:42.055  5704  5704 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-24 16:41:42.055  5704  5704 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-24 16:41:42.055  5704  5704 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-24 16:41:42.055  5704  5704 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-24 16:41:42.055  5704  5704 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-24 16:41:42.055  5704  5704 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-24 16:41:42.055  5704  5704 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-24 16:41:42.055  5704  5704 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-24 16:41:42.055  5704  5704 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-24 16:41:42.055  5704  5704 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-24 16:41:42.055  5704  5704 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-24 16:41:42.055  5704  5704 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-24 16:41:42.055  5704  5704 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-24 16:41:42.055  5704  5704 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-24 16:41:42.055  4623  4681 D BluetoothAdapterProperties: Setting state to 10
11-24 16:41:42.055  4623  4681 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
11-24 16:41:42.057  4623  4681 I BluetoothAdapterState: Entering OffState
11-24 16:41:42.058   927   944 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
11-24 16:41:42.063  4623  4623 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
11-24 16:41:42.063  4623  4623 W BluetoothSdpJni: Cleaning up Bluetooth Health object
11-24 16:41:42.063  4623  4623 I BluetoothServiceJni: cleanupNative: return from cleanup
11-24 16:41:42.064  4623  4682 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
11-24 16:41:42.067  4623  4623 I art     : System.exit called, status: 0
11-24 16:41:42.067  4623  4623 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
11-24 16:41:42.069  5704  5704 D StrictMode: StrictMode policy violation; ~duration=109 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-24 16:41:42.069  5704  5704 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-24 16:41:42.069  5704  5704 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
11-24 16:41:42.069  5704  5704 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
11-24 16:41:42.069  5704  5704 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
11-24 16:41:42.069  5704  5704 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
11-24 16:41:42.069  5704  5704 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
11-24 16:41:42.069  5704  5704 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
11-24 16:41:42.069  5704  5704 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
11-24 16:41:42.069  5704  5704 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-24 16:41:42.069  5704  5704 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-24 16:41:42.069  5704  5704 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-24 16:41:42.069  5704  5704 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-24 16:41:42.069  5704  5704 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-24 16:41:42.069  5704  5704 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-24 16:41:42.069  5704  5704 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-24 16:41:42.069  5704  5704 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-24 16:41:42.069  5704  5704 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-24 16:41:42.069  5704  5704 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-24 16:41:42.069  5704  5704 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-24 16:41:42.069  5704  5704 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-24 16:41:42.069  5704  5704 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-24 16:41:42.069  5704  5704 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-24 16:41:42.069  5704  5704 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-24 16:41:42.069  5704  5704 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-24 16:41:42.069  5704  5704 D StrictMode: StrictMode policy violation; ~duration=108 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-24 16:41:42.069  5704  5704 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-24 16:41:42.069  5704  5704 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
11-24 16:41:42.069  5704  5704 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
11-24 16:41:42.069  5704  5704 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
11-24 16:41:42.069  5704  5704 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
11-24 16:41:42.069  5704  5704 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
11-24 16:41:42.069  5704  5704 D StrictMode: 	at com.google.r.k.d(PG:1187)
11-24 16:41:42.069  5704  5704 D StrictMode: 	at com.google.r.k.a(PG:2107)
11-24 16:41:42.069  5704  5704 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
11-24 16:41:42.069  5704  5704 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
11-24 16:41:42.069  5704  5704 D StrictMode: 	at com.google.r.v.a(PG:1161)
11-24 16:41:42.069  5704  5704 D StrictMode: 	at com.google.r.y.a(PG:2188)
11-24 16:41:42.069  5704  5704 D StrictMode: 	at com.google.r.e.b(PG:170)
11-24 16:41:42.069  5704  5704 D StrictMode: 	at com.google.r.e.b(PG:15188)
11-24 16:41:42.069  5704  5704 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
11-24 16:41:42.069  5704  5704 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
11-24 16:41:42.069  5704  5704 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-24 16:41:42.069  5704  5704 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-24 16:41:42.069  5704  5704 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-24 16:41:42.069  5704  5704 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-24 16:41:42.069  5704  5704 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-24 16:41:42.069  5704  5704 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-24 16:41:42.069  5704  5704 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-24 16:41:42.069  5704  5704 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-24 16:41:42.069  5704  5704 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-24 16:41:42.069  5704  5704 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-24 16:41:42.069  5704  5704 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-24 16:41:42.069  5704  5704 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-24 16:41:42.069  5704  5704 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-24 16:41:42.069  5704  5704 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-24 16:41:42.069  5704  5704 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-24 16:41:42.069  5704  5704 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-24 16:41:42.069  5704  5704 D StrictMode: StrictMode policy violation; ~duration=100 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-24 16:41:42.069  5704  5704 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-24 16:41:42.069  5704  5704 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
11-24 16:41:42.069  5704  5704 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
11-24 16:41:42.069  5704  5704 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
11-24 16:41:42.069  5704  5704 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
11-24 16:41:42.069  5704  5704 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
11-24 16:41:42.069  5704  5704 D StrictMode: 	at com.google.r.k.d(PG:1187)
11-24 16:41:42.069  5704  5704 D StrictMode: 	at com.google.r.k.c(PG:18147)
11-24 16:41:42.069  5704  5704 D StrictMode: 	at com.google.r.k.d(PG:583)
11-24 16:41:42.069  5704  5704 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
11-24 16:41:42.069  5704  5704 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
11-24 16:41:42.069  5704  5704 D StrictMode: 	at com.google.r.v.a(PG:1161)
11-24 16:41:42.069  5704  5704 D StrictMode: 	at com.google.r.y.a(PG:2188)
11-24 16:41:42.069  5704  5704 D StrictMode: 	at com.google.r.e.b(PG:170)
11-24 16:41:42.069  5704  5704 D StrictMode: 	at com.google.r.e.b(PG:15188)
11-24 16:41:42.069  5704  5704 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
11-24 16:41:42.069  5704  5704 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
11-24 16:41:42.069  5704  5704 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-24 16:41:42.069  5704  5704 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-24 16:41:42.069  5704  5704 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-24 16:41:42.069  5704  5704 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-24 16:41:42.069  5704  5704 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-24 16:41:42.069  5704  5704 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-24 16:41:42.069  5704  5704 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-24 16:41:42.069  5704  5704 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-24 16:41:42.069  5704  5704 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-24 16:41:42.069  5704  5704 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-24 16:41:42.069  5704  5704 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-24 16:41:42.069  5704  5704 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-24 16:41:42.069  5704  5704 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-24 16:41:42.069  5704  5704 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-24 16:41:42.069  5704  5704 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-24 16:41:42.069  5704  5704 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-24 16:41:42.069  5704  5704 D StrictMode: StrictMode policy violation; ~duration=78 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-24 16:41:42.069  5704  5704 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-24 16:41:42.069  5704  5704 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
11-24 16:41:42.069  5704  5704 D StrictMode: 	at java.io.File.doAccess(File.java:281)
11-24 16:41:42.069  5704  5704 D StrictMode: 	at java.io.File.exists(File.java:361)
11-24 16:41:42.069  5704  5704 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
11-24 16:41:42.069  5704  5704 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
11-24 16:41:42.069  5704  5704 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
11-24 16:41:42.069  5704  5704 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
11-24 16:41:42.069  5704  5704 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
11-24 16:41:42.069  5704  5704 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-24 16:41:42.069  5704  5704 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-24 16:41:42.069  5704  5704 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-24 16:41:42.069  5704  5704 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-24 16:41:42.069  5704  5704 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-24 16:41:42.069  5704  5704 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-24 16:41:42.069  5704  5704 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-24 16:41:42.069  5704  5704 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-24 16:41:42.069  5704  5704 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-24 16:41:42.069  5704  5704 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-24 16:41:42.069  5704  5704 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-24 16:41:42.069  5704  5704 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-24 16:41:42.069  5704  5704 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-24 16:41:42.069  5704  5704 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-24 16:41:42.069  5704  5704 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-24 16:41:42.069  5704  5704 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-24 16:41:42.070  5704  5704 D StrictMode: StrictMode policy violation; ~duration=77 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-24 16:41:42.070  5704  5704 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-24 16:41:42.070  5704  5704 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
11-24 16:41:42.070  5704  5704 D StrictMode: 	at java.io.File.doAccess(File.java:281)
11-24 16:41:42.070  5704  5704 D StrictMode: 	at java.io.File.exists(File.java:361)
11-24 16:41:42.070  5704  5704 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
11-24 16:41:42.070  5704  5704 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-24 16:41:42.070  5704  5704 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-24 16:41:42.070  5704  5704 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-24 16:41:42.070  5704  5704 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-24 16:41:42.070  5704  5704 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-24 16:41:42.070  5704  5704 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-24 16:41:42.070  5704  5704 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-24 16:41:42.070  5704  5704 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-24 16:41:42.070  5704  5704 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-24 16:41:42.070  5704  5704 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-24 16:41:42.070  5704  5704 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-24 16:41:42.070  5704  5704 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-24 16:41:42.070  5704  5704 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-24 16:41:42.070  5704  5704 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-24 16:41:42.070  5704  5704 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-24 16:41:42.070  5704  5704 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-24 16:41:42.070  5704  5704 D StrictMode: StrictMode policy violation; ~duration=77 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-24 16:41:42.070  5704  5704 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-24 16:41:42.070  5704  5704 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
11-24 16:41:42.070  5704  5704 D StrictMode: 	at java.io.File.lastModified(File.java:569)
11-24 16:41:42.070  5704  5704 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
11-24 16:41:42.070  5704  5704 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-24 16:41:42.070  5704  5704 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-24 16:41:42.070  5704  5704 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-24 16:41:42.070  5704  5704 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-24 16:41:42.070  5704  5704 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-24 16:41:42.070  5704  5704 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-24 16:41:42.070  5704  5704 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-24 16:41:42.070  5704  5704 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-24 16:41:42.070  5704  5704 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-24 16:41:42.070  5704  5704 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-24 16:41:42.070  5704  5704 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-24 16:41:42.070  5704  5704 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-24 16:41:42.070  5704  5704 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-24 16:41:42.070  5704  5704 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-24 16:41:42.070  5704  5704 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-24 16:41:42.070  5704  5704 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-24 16:41:42.074  5682  5682 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
11-24 16:41:42.090  5682  5682 D DockEventReceiver: finishStartingService: stopping service
11-24 16:41:42.092   927  3116 I ActivityManager: Killing 5384:com.android.chrome/u0a39 (adj 15): empty #17
,11-24 16:41:42.114   927   938 I ActivityManager: Process com.android.bluetooth (pid 4623) has died
11-24 16:41:42.117  3526  3526 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
11-24 16:41:42.129   927  3811 I ActivityManager: Start proc 5736:com.android.bluetooth/1002 for broadcast com.android.bluetooth/.opp.BluetoothOppReceiver
,11-24 16:41:42.164   927   944 D Tethering: InitialState.processMessage what=4
,11-24 16:41:42.167   927   944 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,11-24 16:41:42.196  5736  5736 D AdapterServiceConfig: Adding HeadsetService
,11-24 16:41:42.196  5736  5736 D AdapterServiceConfig: Adding A2dpService
,11-24 16:41:42.196  5736  5736 D AdapterServiceConfig: Adding HidService
11-24 16:41:42.197  5736  5736 D AdapterServiceConfig: Adding HealthService
11-24 16:41:42.197  5736  5736 D AdapterServiceConfig: Adding PanService
11-24 16:41:42.197  5736  5736 D AdapterServiceConfig: Adding GattService
11-24 16:41:42.197  5736  5736 D AdapterServiceConfig: Adding BluetoothMapService
11-24 16:41:42.197  5736  5736 D AdapterServiceConfig: Adding SapService
11-24 16:41:42.201   927  3116 I ActivityManager: Killing 5416:com.google.android.apps.photos/u0a62 (adj 15): empty #17
,11-24 16:41:42.235  3688  3688 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,11-24 16:41:42.238  3688  3688 D SystemUpdateService: onCreate
,11-24 16:41:42.242  3688  3688 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,11-24 16:41:42.247  3688  5749 I SystemUpdateService: active receiver: enabled
,11-24 16:41:42.261  3688  3688 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,11-24 16:41:42.278  3688  5364 I iu.UploadsManager: num queued entries: 0
,11-24 16:41:42.278  3688  5364 I iu.UploadsManager: num updated entries: 0
,11-24 16:41:42.279  3688  5749 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,11-24 16:41:42.283  3688  3688 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,11-24 16:41:42.285  3688  3688 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,11-24 16:41:42.287  3688  5749 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,11-24 16:41:42.287  3688  5749 I SystemUpdateService: now status is 0 (complete)
11-24 16:41:42.287  3688  5749 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
11-24 16:41:42.287  3688  5749 I SystemUpdateService: file has been verified
11-24 16:41:42.287  3688  5749 I SystemUpdateService: OTA package size = 21989297
11-24 16:41:42.291  3688  5364 I iu.SyncManager: NEXT; no task
,11-24 16:41:42.296   927  3362 I ActivityManager: Start proc 5752:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,11-24 16:41:42.309  3688  5749 I SystemUpdateService: showing system update notification
,11-24 16:41:42.332  5752  5752 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm64
,11-24 16:41:42.334  5752  5752 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,11-24 16:41:42.340  5752  5752 D SprintDMHelper: simOperator: 
11-24 16:41:42.340  5752  5752 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,11-24 16:41:42.352   927  3811 I ActivityManager: Start proc 5764:com.android.chrome/u0a39 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
,11-24 16:41:42.364   927   927 V NotificationService: pkg=com.google.android.gms canInterrupt=false intercept=true
,11-24 16:41:42.370  3688  3688 D SystemUpdateService: onDestroy
,11-24 16:41:42.371   927   937 I ActivityManager: Killing 5237:com.google.android.music:main/u0a59 (adj 15): empty #17
,11-24 16:41:42.470  4977  5778 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,11-24 16:41:42.479   927  3489 I ActivityManager: Start proc 5779:com.google.android.apps.photos/u0a62 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
,11-24 16:41:42.482   927  3116 I ActivityManager: Killing 5400:com.google.android.gms.unstable/u0a12 (adj 15): empty #17
,11-24 16:41:42.545  5779  5779 W System  : ClassLoader referenced unknown path: /system/app/Photos/lib/arm
,11-24 16:41:42.644  5704  5725 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,11-24 16:41:42.728   927  3747 I ActivityManager: Killing 3832:com.android.providers.calendar/u0a1 (adj 15): empty #17
,11-24 16:41:42.741   927   944 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@7497eb5:true
,11-24 16:41:42.774   927  3782 I ActivityManager: Start proc 5793:com.google.android.apps.gcs/u0a11 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,11-24 16:41:42.806  5793  5793 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm64
,11-24 16:41:42.813   506   918 E Netd    : netlink response contains error (No such file or directory)
,11-24 16:41:42.814   927  3362 I ActivityManager: Killing 5493:com.android.defcontainer/u0a7 (adj 15): empty #17
11-24 16:41:42.815   927  2908 E NetdConnector: NDC Command {115 bandwidth setglobalalert 2097152} took too long (1044ms)
11-24 16:41:42.815   927  2912 E NetdConnector: NDC Command {114 network destroy 100} took too long (1054ms)
11-24 16:41:42.815   927  2912 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
11-24 16:41:42.815   927  2907 E NetdConnector: NDC Command {116 bandwidth gettetherstats} took too long (647ms)
11-24 16:41:42.815   506   918 D TetherController: Setting IP forward enable = 0
,11-24 16:41:42.963   535   535 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,11-24 16:41:46.662   927  3747 D WifiService: setWifiEnabled: true pid=5615, uid=10077
,11-24 16:41:46.662   927  3747 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-24 16:41:46.673   506   918 D SoftapController: Softap fwReload - Ok
,11-24 16:41:46.678   506   918 D CommandListener: Setting iface cfg
,11-24 16:41:46.678   506   918 D CommandListener: Trying to bring down wlan0
,11-24 16:41:46.679   506   918 D CommandListener: Clearing all IP addresses on wlan0
,11-24 16:41:46.686   927  2910 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,11-24 16:41:47.260   927  2910 D wifi    : set interface wlan0 flags (UP)
,11-24 16:41:47.265   927  2910 I WifiHAL : Initializing wifi
11-24 16:41:47.265   927  2910 I WifiHAL : Creating socket
,11-24 16:41:47.270   927   944 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
11-24 16:41:47.272   927  2910 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
11-24 16:41:47.272   927  2910 D wifi    : Did set static halHandle = 0x7f8e691e00
11-24 16:41:47.274   927  2910 D wifi    : halHandle = 0x7f8e691e00, mVM = 0x7faaccd140, mCls = 0x190a
11-24 16:41:47.274   927  2910 D wifi    : array field set
11-24 16:41:47.274   927  2910 I WifiNative-HAL: interface[0] = wlan0
11-24 16:41:47.277   927  5816 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=547850100224
,11-24 16:41:47.277   927  5816 D wifi    : waitForHalEvents called, vm = 0x7faaccd140, obj = 0x190a, env = 0x7f8f1bd5c0
,11-24 16:41:47.353  5817  5817 I wpa_supplicant: Successfully initialized wpa_supplicant
,11-24 16:41:47.379   927  2910 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
11-24 16:41:47.379   927  2910 E WifiHW  : Unable to open connection to supplicant on "@android:wpa_wlan0": No such file or directory
,11-24 16:41:47.381  5615  5615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-24 16:41:47.427  5817  5817 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,11-24 16:41:47.464  5817  5817 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,11-24 16:41:47.465  5817  5817 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,11-24 16:41:47.964   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 16:41:48.396   927  2910 D WifiConfigStore: Loading config and enabling all networks 
,11-24 16:41:48.398  5615  5615 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-24 16:41:48.398  5615  5615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-24 16:41:48.398  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-24 16:41:48.398  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-24 16:41:48.398  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-24 16:41:48.398  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-24 16:41:48.398  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-24 16:41:48.398  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-24 16:41:48.398  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-24 16:41:48.398  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-24 16:41:48.398  5615  5615 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,11-24 16:41:48.398  5615  5615 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
,11-24 16:41:48.430   927  2910 D WifiConfigStore: loaded 0 passpoint configs
11-24 16:41:48.431   927  2910 W WifiConfigStore: Upgrading network 4 to android.uid.system:1000
11-24 16:41:48.431   927  2910 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,11-24 16:41:48.432   927  2910 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
11-24 16:41:48.432   927  2910 W WifiConfigStore: Upgrading network 3 to android.uid.system:1000
11-24 16:41:48.433   927  2910 W WifiConfigStore: Upgrading network 2 to android.uid.system:1000
,11-24 16:41:48.434   927  2910 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,11-24 16:41:48.435   927  2910 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 5
11-24 16:41:48.435   927  2910 E WifiConfigStore: found sortedWifiConfigurations : "AndroidAP"WPA_PSK
11-24 16:41:48.435   927  2910 E WifiConfigStore: found sortedWifiConfigurations : "AndroidHotspot2346"WPA_PSK
11-24 16:41:48.435   927  2910 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
11-24 16:41:48.435   927  2910 E WifiConfigStore: found sortedWifiConfigurations : "Thali_internal"WPA_PSK
11-24 16:41:48.435   927  2910 E WifiConfigStore: found sortedWifiConfigurations : "MC"WPA_PSK
,11-24 16:41:48.439   927  2910 D WifiNative-HAL: Setting external_sim to 1
,11-24 16:41:48.439  4977  4977 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,11-24 16:41:48.439   927  2910 D wifi    : setting dfs flag to true, 0x7f941bf140
11-24 16:41:48.440   927  2910 D WifiStateMachine: Setting OUI to DA-A1-19
11-24 16:41:48.440   927  2910 D wifi    : setting scan oui 0x7f941bf140
11-24 16:41:48.440   927  2910 D WifiHAL : Sending mac address OUI
,11-24 16:41:48.445   927  2910 E native  : do suspend false
,11-24 16:41:48.457   927  2910 D wifi    : android_net_wifi_setLinkLayerStats: 1
,11-24 16:41:48.458   927   927 D RttService: SCAN_AVAILABLE : 3
11-24 16:41:48.458   506   918 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
11-24 16:41:48.458   927  3020 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
11-24 16:41:48.459   506   918 D CommandListener: Setting iface cfg
,11-24 16:41:48.463   927  2909 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '125 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 125 Failed to set address (No such device)'
,11-24 16:41:48.463   927  2909 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,11-24 16:41:48.474   927  2909 D WifiNative-HAL: p2pGetDeviceAddress
,11-24 16:41:48.479   927  2909 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:70
,11-24 16:41:48.479   927   942 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=129040 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=16 mControllerEnergyUsed=60 }
,11-24 16:41:48.965   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 16:41:49.967   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 16:41:50.968   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 16:41:51.532  5817  5817 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-24 16:41:51.536  5817  5817 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-24 16:41:51.540  5817  5817 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-24 16:41:51.596   927  2910 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
11-24 16:41:51.597   927  2910 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3
11-24 16:41:51.597   927  2910 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-24 16:41:51.613   927  2910 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=0
,11-24 16:41:51.650   927  2910 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=0
,11-24 16:41:51.657  5817  5817 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,11-24 16:41:51.672   927  3782 D WifiService: setWifiEnabled: false pid=5615, uid=10077
,11-24 16:41:51.672   927  3782 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-24 16:41:51.679   927   927 D RttService: SCAN_AVAILABLE : 1
,11-24 16:41:51.679   927  3020 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,11-24 16:41:51.691   927  2910 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,11-24 16:41:51.692   506   918 D CommandListener: Clearing all IP addresses on wlan0
,11-24 16:41:51.697   927  2910 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,11-24 16:41:51.698  5817  5817 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
11-24 16:41:51.704  5615  5615 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-24 16:41:51.704  5615  5615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-24 16:41:51.704  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-24 16:41:51.704  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-24 16:41:51.704  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-24 16:41:51.704  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-24 16:41:51.704  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-24 16:41:51.704  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-24 16:41:51.704  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-24 16:41:51.704  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,11-24 16:41:51.704  5615  5615 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-24 16:41:51.704  5615  5615 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
,11-24 16:41:51.711  5817  5817 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
,11-24 16:41:51.715  5817  5817 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=00:00:00:00:00:00 reason=3 locally_generated=1
,11-24 16:41:51.733  5817  5817 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,11-24 16:41:51.737  5817  5817 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,11-24 16:41:51.841   927  2910 D wifi    : In wifi stop Hal
,11-24 16:41:51.841   927  2910 D wifi    : halHandle = 0x7f8e691e00, mVM = 0x7faaccd140, mCls = 0x190a
,11-24 16:41:51.842   927  5816 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
11-24 16:41:51.842   927  5816 D WifiHAL : Got a signal to exit!!!
,11-24 16:41:51.842   927  5816 I WifiHAL : Exit wifi_event_loop
11-24 16:41:51.843   927  2910 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 0
11-24 16:41:51.844   927  2910 E WifiHAL : Event processing terminated
11-24 16:41:51.845   927  2910 D wifi    : In wifi cleaned up handler
,11-24 16:41:51.846   927  2910 I WifiHAL : Internal cleanup completed
11-24 16:41:51.853  5615  5615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-24 16:41:51.857  3988  4159 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,11-24 16:41:51.858  4977  4977 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,11-24 16:41:51.890   927  5816 D wifi    : set interface wlan0 flags (DOWN)
,11-24 16:41:51.891   927  2910 D WifiNative-HAL: HAL event thread stopped successfully
,11-24 16:41:51.970   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 16:41:52.099   927   944 D Tethering: InitialState.processMessage what=4
,11-24 16:41:52.106   927   944 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,11-24 16:41:52.970   535   535 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,11-24 16:41:56.714   927   944 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@fce7eab:true
,11-24 16:41:56.715  5736  5736 D BluetoothAdapterState: make() - Creating AdapterState
,11-24 16:41:56.722  5736  5736 I bt_bluedroid: init
,11-24 16:41:56.722  5736  5821 I BluetoothAdapterState: Entering OffState
,11-24 16:41:56.725  5736  5822 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,11-24 16:41:56.725  5736  5822 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
11-24 16:41:56.725  5736  5822 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
11-24 16:41:56.725  5736  5822 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
11-24 16:41:56.726  5736  5736 I bt_bluedroid: get_profile_interface socket
,11-24 16:41:56.728  5736  5825 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:D4
,11-24 16:41:56.729  5736  5736 I bt_bluedroid: get_profile_interface sdp
,11-24 16:41:56.730  5736  5825 D BluetoothAdapterProperties: Name is: Nexus 6P
,11-24 16:41:56.738  5736  5746 I bt_bluedroid: config_hci_snoop_log
,11-24 16:41:56.740   927   944 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,11-24 16:41:56.744  5736  5821 D BluetoothAdapterState: Current state: OFF, message: 0
,11-24 16:41:56.744  5736  5821 D BluetoothAdapterProperties: Setting state to 14
11-24 16:41:56.744  5736  5821 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,11-24 16:41:56.747  5736  5821 D BluetoothBondStateMachine: make
,11-24 16:41:56.749  5736  5826 I BluetoothBondStateMachine: StableState(): Entering Off State
,11-24 16:41:56.752  5736  5821 I BluetoothAdapterState: Entering PendingCommandState
,11-24 16:41:56.753  5736  5736 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,11-24 16:41:56.756  5736  5736 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@75cfb1d
,11-24 16:41:56.756  5736  5736 D BtGatt.DebugUtils: handleDebugAction() action=null
,11-24 16:41:56.757  5736  5736 D BtGatt.GattService: Received start request. Starting profile...
,11-24 16:41:56.757  5736  5736 D BtGatt.GattService: start()
11-24 16:41:56.757  5736  5736 I bt_bluedroid: get_profile_interface gatt
,11-24 16:41:56.758  5736  5736 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@75cfb1d
11-24 16:41:56.758  5736  5736 D BtGatt.AdvertiseManager: advertise manager created
,11-24 16:41:56.763  5736  5736 V BluetoothAdapterState: isTurningOff()=false
,11-24 16:41:56.763  5736  5736 V BluetoothAdapterState: isTurningOn()=false
11-24 16:41:56.763  5736  5736 V BluetoothAdapterState: isBleTurningOn()=true
11-24 16:41:56.763  5736  5736 V BluetoothAdapterState: isBleTurningOff()=false
11-24 16:41:56.764  5736  5821 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,11-24 16:41:56.765  5736  5821 I bt_bluedroid: bt_bluedroid
,11-24 16:41:56.765  5736  5822 D bt_stack_manager: event_start_up_stack is bringing up the stack.
11-24 16:41:56.765  5736  5822 I bt_hci  : start_up
,11-24 16:41:56.771  5736  5822 I bt_vendor: alloc value 0xf3ff8871
11-24 16:41:56.771  5736  5822 I bt_vendor: init
11-24 16:41:56.771  5736  5822 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
11-24 16:41:56.771  5736  5822 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,11-24 16:41:56.882  5736  5822 D bt_hci  : start_up starting async portion
,11-24 16:41:56.883  5736  5829 I bt_hci  : event_finish_startup
11-24 16:41:56.883  5736  5829 I bt_hci_h4: hal_open
11-24 16:41:56.883  5736  5829 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,11-24 16:41:56.887  5736  5829 I bt_userial_vendor: device fd = 54 open
,11-24 16:41:56.880  5830  5830 W irq/448-msm_hs_: type=1400 audit(0.0:119): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-24 16:41:56.901  5736  5829 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,11-24 16:41:56.904  5736  5829 D bt_hwcfg: Chipset BCM4358A3
,11-24 16:41:56.904  5736  5829 D bt_hwcfg: Target name = [BCM4358A3]
11-24 16:41:56.904  5736  5829 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,11-24 16:41:57.289  5736  5829 I bt_hwcfg: bt vendor lib: set UART baud 115200
11-24 16:41:57.289  5736  5829 D bt_hwcfg: Settlement delay -- 100 ms
11-24 16:41:57.289  5736  5829 I bt_hwcfg: Setting fw settlement delay to 100 
,11-24 16:41:57.425  5736  5829 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,11-24 16:41:57.425  5736  5829 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:D4
11-24 16:41:57.427  5736  5829 I bt_hwcfg: vendor lib fwcfg completed
11-24 16:41:57.427  5736  5829 I bt_vendor: firmware callback
,11-24 16:41:57.427  5736  5829 I bt_hci  : firmware_config_callback
11-24 16:41:57.435  5736  5832 I bt_btu  : btu_task pending for preload complete event
11-24 16:41:57.435  5736  5832 I bt_btu_task: Bluetooth chip preload is complete
11-24 16:41:57.435  5736  5832 I bt_btu  : btu_task received preload complete event
,11-24 16:41:57.443  5736  5832 I         : BTE_InitTraceLevels -- TRC_HCI
,11-24 16:41:57.443  5736  5832 I         : BTE_InitTraceLevels -- TRC_L2CAP
11-24 16:41:57.443  5736  5832 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,11-24 16:41:57.443  5736  5832 I         : BTE_InitTraceLevels -- TRC_AVDT
11-24 16:41:57.443  5736  5832 I         : BTE_InitTraceLevels -- TRC_AVRC
,11-24 16:41:57.443  5736  5832 I         : BTE_InitTraceLevels -- TRC_A2D
11-24 16:41:57.443  5736  5832 I         : BTE_InitTraceLevels -- TRC_BNEP
,11-24 16:41:57.443  5736  5832 I         : BTE_InitTraceLevels -- TRC_BTM
11-24 16:41:57.444  5736  5832 I         : BTE_InitTraceLevels -- TRC_GAP
11-24 16:41:57.444  5736  5832 I         : BTE_InitTraceLevels -- TRC_PAN
11-24 16:41:57.444  5736  5832 I         : BTE_InitTraceLevels -- TRC_SDP
11-24 16:41:57.444  5736  5832 I         : BTE_InitTraceLevels -- TRC_GATT
,11-24 16:41:57.444  5736  5832 I         : BTE_InitTraceLevels -- TRC_SMP
11-24 16:41:57.444  5736  5832 I         : BTE_InitTraceLevels -- TRC_BTAPP
,11-24 16:41:57.444  5736  5832 I         : BTE_InitTraceLevels -- TRC_BTIF
,11-24 16:41:57.528  5736  5832 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf3f76549
11-24 16:41:57.528  5736  5832 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf3f76549 
,11-24 16:41:57.541  5736  5825 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,11-24 16:41:57.543  5736  5825 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,11-24 16:41:57.544  5736  5825 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:D4
11-24 16:41:57.546  5736  5825 D BluetoothAdapterProperties: Name is: Nexus 6P
,11-24 16:41:57.550  5736  5825 D BluetoothAdapterProperties: Scan Mode:20
,11-24 16:41:57.551  5736  5825 D BluetoothAdapterProperties: Discoverable Timeout:120
11-24 16:41:57.551  5736  5825 D bt_hci  : do_postload posting postload work item
11-24 16:41:57.551  5736  5829 I bt_hci  : event_postload
11-24 16:41:57.551  5736  5829 I bt_vendor: sco_config_cb
11-24 16:41:57.551  5736  5829 I bt_hci  : sco_config_callback postload finished.
11-24 16:41:57.555  5615  5615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-24 16:41:57.558  5736  5825 D bt_bte_conf: Device ID record 1 : primary
,11-24 16:41:57.558  5736  5825 D bt_bte_conf:   vendorId            = 000f
11-24 16:41:57.558  5736  5825 D bt_bte_conf:   vendorIdSource      = 0001
11-24 16:41:57.559  5736  5825 D bt_bte_conf:   product             = 1200
11-24 16:41:57.559  5736  5825 D bt_bte_conf:   version             = 1436
11-24 16:41:57.559  5736  5825 D bt_bte_conf:   clientExecutableURL = 
11-24 16:41:57.559  5736  5825 D bt_bte_conf:   serviceDescription  = 
11-24 16:41:57.559  5736  5825 D bt_bte_conf:   documentationURL    = 
11-24 16:41:57.559  5736  5825 D bt_bte_conf: bte_load_did_conf no section named DID2.
11-24 16:41:57.559  5736  5822 D bt_stack_manager: event_start_up_stack finished
,11-24 16:41:57.560  5736  5829 I bt_vendor: low_power_mode_cb
,11-24 16:41:57.560  5736  5821 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
11-24 16:41:57.561  5736  5821 D BluetoothAdapterProperties: Setting state to 15
11-24 16:41:57.561  5736  5821 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
,11-24 16:41:57.563  5736  5821 I BluetoothAdapterState: Entering BleOnState
11-24 16:41:57.567  5736  5821 D BluetoothAdapterState: Current state: BLE ON, message: 1
11-24 16:41:57.567  5736  5821 D BluetoothAdapterProperties: Setting state to 11
11-24 16:41:57.567  5736  5821 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,11-24 16:41:57.573  5615  5615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-24 16:41:57.577  5736  5736 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@75cfb1d
,11-24 16:41:57.578  5736  5736 D HeadsetService: Received start request. Starting profile...
11-24 16:41:57.580  5736  5736 I BluetoothHeadsetServiceJni: classInitNative: succeeds
11-24 16:41:57.581  5736  5736 D HeadsetStateMachine: make
,11-24 16:41:57.589  5736  5821 I BluetoothAdapterState: Entering PendingCommandState
,11-24 16:41:57.591  5736  5736 D HeadsetStateMachine: max_hf_connections = 1
,11-24 16:41:57.591  5736  5736 I bt_bluedroid: get_profile_interface handsfree
11-24 16:41:57.592  5736  5825 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
11-24 16:41:57.592  5736  5825 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
,11-24 16:41:57.595  5736  5736 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@75cfb1d
,11-24 16:41:57.596  5736  5736 D A2dpService: Received start request. Starting profile...
11-24 16:41:57.596  3526  3526 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
11-24 16:41:57.597  5736  5736 I BluetoothAvrcpServiceJni: classInitNative: succeeds
11-24 16:41:57.597  5736  5736 I bt_bluedroid: get_profile_interface avrcp
,11-24 16:41:57.603  5736  5736 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,11-24 16:41:57.603  5736  5736 I BluetoothA2dpServiceJni: classInitNative: succeeds
11-24 16:41:57.603  5736  5736 D A2dpStateMachine: make
11-24 16:41:57.604  5736  5736 I bt_bluedroid: get_profile_interface a2dp
,11-24 16:41:57.604  5736  5825 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,11-24 16:41:57.606  5736  5840 D A2dpStateMachine: Enter Disconnected: -2
,11-24 16:41:57.606  5736  5736 I BluetoothHidServiceJni: classInitNative: succeeds
,11-24 16:41:57.607  5736  5736 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@75cfb1d
,11-24 16:41:57.609  5736  5736 D HidService: Received start request. Starting profile...
,11-24 16:41:57.610  5736  5736 I bt_bluedroid: get_profile_interface hidhost
11-24 16:41:57.610  5736  5736 D HidService: setHidService(): set to: null
11-24 16:41:57.610  5736  5825 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf3f5756d
11-24 16:41:57.610  5736  5825 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
11-24 16:41:57.610  5736  5736 I BluetoothHealthServiceJni: classInitNative: succeeds
11-24 16:41:57.611  5736  5736 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@75cfb1d
11-24 16:41:57.611  5736  5736 D HealthService: Received start request. Starting profile...
11-24 16:41:57.612  5682  5682 D BluetoothInputDevice: Proxy object connected
,11-24 16:41:57.612  5682  5682 D HidProfile: Bluetooth service connected
11-24 16:41:57.613  5736  5736 I bt_bluedroid: get_profile_interface health
11-24 16:41:57.613  5736  5736 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,11-24 16:41:57.614  5736  5736 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@75cfb1d
,11-24 16:41:57.615  5682  5682 D BluetoothPan: BluetoothPAN Proxy object connected
,11-24 16:41:57.615  5736  5736 D PanService: Received start request. Starting profile...
,11-24 16:41:57.615  5736  5736 D BluetoothPanServiceJni: initializeNative(L110): pan
11-24 16:41:57.615  5736  5736 I bt_bluedroid: get_profile_interface pan
11-24 16:41:57.616  5682  5682 D PanProfile: Bluetooth service connected
11-24 16:41:57.616  5736  5825 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
11-24 16:41:57.618  5736  5736 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@75cfb1d
11-24 16:41:57.619  5682  5682 D BluetoothMap: Proxy object connected
11-24 16:41:57.619  5736  5736 D BluetoothMapService: Received start request. Starting profile...
11-24 16:41:57.619  5736  5736 D BluetoothMapService: start()
11-24 16:41:57.619  5682  5682 D MapProfile: Bluetooth service connected
11-24 16:41:57.619  5682  5682 D BluetoothMap: getConnectedDevices()
11-24 16:41:57.620  5682  5682 D BluetoothMap: Bluetooth is Not enabled
,11-24 16:41:57.621  5736  5736 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,11-24 16:41:57.622  5736  5736 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
11-24 16:41:57.622  5736  5736 D BluetoothMapAppObserver: createReceiver()
11-24 16:41:57.623  5736  5736 D BluetoothMapAppObserver: initObservers()
11-24 16:41:57.624  5736  5736 D BluetoothMapAppObserver: getEnabledAccountItems()
,11-24 16:41:57.630  5736  5736 V SapService: SapBinder()
,11-24 16:41:57.630  5736  5736 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@75cfb1d
11-24 16:41:57.631  5736  5736 D SapService: Received start request. Starting profile...
11-24 16:41:57.631  5736  5736 V SapService: start()
,11-24 16:41:57.632  5736  5736 V BluetoothAdapterState: isTurningOff()=false
,11-24 16:41:57.632  5736  5736 V BluetoothAdapterState: isTurningOn()=true
,11-24 16:41:57.632  5736  5736 V BluetoothAdapterState: isBleTurningOn()=false
,11-24 16:41:57.632  5736  5736 V BluetoothAdapterState: isBleTurningOff()=false
11-24 16:41:57.633  5736  5838 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
11-24 16:41:57.633  5736  5736 V BluetoothAdapterState: isTurningOff()=false
11-24 16:41:57.633  5736  5736 V BluetoothAdapterState: isTurningOn()=true
11-24 16:41:57.633  5736  5736 V BluetoothAdapterState: isBleTurningOn()=false
11-24 16:41:57.633  5736  5736 V BluetoothAdapterState: isBleTurningOff()=false
11-24 16:41:57.633  5736  5736 V BluetoothAdapterState: isTurningOff()=false
11-24 16:41:57.633  5736  5736 V BluetoothAdapterState: isTurningOn()=true
11-24 16:41:57.633  5736  5736 V BluetoothAdapterState: isBleTurningOn()=false
11-24 16:41:57.633  5736  5736 V BluetoothAdapterState: isBleTurningOff()=false
11-24 16:41:57.633  5736  5736 V BluetoothAdapterState: isTurningOff()=false
,11-24 16:41:57.633  5736  5736 V BluetoothAdapterState: isTurningOn()=true
11-24 16:41:57.633  5736  5736 V BluetoothAdapterState: isBleTurningOn()=false
11-24 16:41:57.633  5736  5736 V BluetoothAdapterState: isBleTurningOff()=false
11-24 16:41:57.634  5736  5736 V BluetoothAdapterState: isTurningOff()=false
11-24 16:41:57.634  5736  5736 V BluetoothAdapterState: isTurningOn()=true
11-24 16:41:57.634  5736  5736 V BluetoothAdapterState: isBleTurningOn()=false
11-24 16:41:57.634  5736  5736 V BluetoothAdapterState: isBleTurningOff()=false
11-24 16:41:57.634  5736  5736 V BluetoothAdapterState: isTurningOff()=false
11-24 16:41:57.634  5736  5736 V BluetoothAdapterState: isTurningOn()=true
11-24 16:41:57.634  5736  5736 V BluetoothAdapterState: isBleTurningOn()=false
11-24 16:41:57.634  5736  5736 V BluetoothAdapterState: isBleTurningOff()=false
11-24 16:41:57.634  5736  5736 V BluetoothAdapterState: isTurningOff()=false
11-24 16:41:57.634  5736  5736 V BluetoothAdapterState: isTurningOn()=true
11-24 16:41:57.634  5736  5736 V BluetoothAdapterState: isBleTurningOn()=false
11-24 16:41:57.634  5736  5736 V BluetoothAdapterState: isBleTurningOff()=false
,11-24 16:41:57.635  5736  5821 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
11-24 16:41:57.635  5736  5821 D BluetoothAdapterProperties: ScanMode =  20
11-24 16:41:57.635  5736  5821 D BluetoothAdapterProperties: State =  11
,11-24 16:41:57.635  5736  5821 D BluetoothAdapterProperties: Setting state to 12
11-24 16:41:57.635  5736  5821 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
11-24 16:41:57.636   927   944 D BluetoothA2dp: onBluetoothStateChange: up=true
11-24 16:41:57.636  5736  5821 I BluetoothAdapterState: Entering OnState
11-24 16:41:57.637  5615  5615 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
11-24 16:41:57.637  5736  5825 D BluetoothAdapterProperties: Scan Mode:21
11-24 16:41:57.638  5736  5825 D BluetoothAdapterProperties: Discoverable Timeout:120
11-24 16:41:57.639   927   944 D BluetoothHeadset: onBluetoothStateChange: up=true
,11-24 16:41:57.639  3105  3293 D BluetoothPbap: onBluetoothStateChange: up=true
11-24 16:41:57.640   927   927 D BluetoothA2dp: Proxy object connected
11-24 16:41:57.641  3105  3952 D BluetoothInputDevice: onBluetoothStateChange: up=true
11-24 16:41:57.642  5615  5615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-24 16:41:57.642  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-24 16:41:57.642  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-24 16:41:57.642  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-24 16:41:57.642  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-24 16:41:57.642  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-24 16:41:57.642  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-24 16:41:57.642  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-24 16:41:57.642  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-24 16:41:57.643  3105  3105 D BluetoothInputDevice: Proxy object connected
11-24 16:41:57.643  5682  5693 D BluetoothPbap: onBluetoothStateChange: up=true
11-24 16:41:57.643  3105  3105 D HidProfile: Bluetooth service connected
,11-24 16:41:57.644  3105  3293 D BluetoothA2dp: onBluetoothStateChange: up=true
11-24 16:41:57.646  5615  5615 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
11-24 16:41:57.646  3105  3105 D BluetoothA2dp: Proxy object connected
11-24 16:41:57.646  3105  3118 D BluetoothMap: onBluetoothStateChange: up=true
11-24 16:41:57.647  3105  3117 D BluetoothPan: onBluetoothStateChange on: true
,11-24 16:41:57.648  3105  3105 D BluetoothMap: Proxy object connected
,11-24 16:41:57.648  3105  3105 D MapProfile: Bluetooth service connected
,11-24 16:41:57.648  3105  3105 D BluetoothMap: getConnectedDevices()
11-24 16:41:57.649  5736  5736 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
11-24 16:41:57.649  5736  5736 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
,11-24 16:41:57.651  5736  5736 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-24 16:41:57.651  3105  3105 D BluetoothPan: BluetoothPAN Proxy object connected
11-24 16:41:57.651  5682  5694 D BluetoothInputDevice: onBluetoothStateChange: up=true
11-24 16:41:57.651  3105  3105 D PanProfile: Bluetooth service connected
11-24 16:41:57.651   927   944 D BluetoothHeadset: onBluetoothStateChange: up=true
11-24 16:41:57.651  5682  5693 D BluetoothMap: onBluetoothStateChange: up=true
11-24 16:41:57.652  3743  3957 D BluetoothHeadset: onBluetoothStateChange: up=true
11-24 16:41:57.652  5682  5694 D BluetoothPan: onBluetoothStateChange on: true
11-24 16:41:57.652  5736  5736 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-24 16:41:57.653  3105  3118 D BluetoothHeadset: onBluetoothStateChange: up=true
,11-24 16:41:57.653   927   944 D BluetoothHeadset: onBluetoothStateChange: up=true
11-24 16:41:57.653  5736  5736 D ObexServerSockets: Succeed to create listening sockets 
11-24 16:41:57.653  5736  5736 D ObexServerSockets0: startAccept()
11-24 16:41:57.653  5736  5736 D ObexServerSockets0: prepareForNewConnect()
11-24 16:41:57.655   927   927 I Telecom : BluetoothPhoneService: queryPhoneState
,11-24 16:41:57.655  5615  5615 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
,11-24 16:41:57.656  5736  5736 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
11-24 16:41:57.656  5736  5736 D BluetoothSdpJni: SDP Create record success - handle: 0
11-24 16:41:57.656  5736  5736 D BluetoothMapService: onReceive
11-24 16:41:57.656  5615  5615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-24 16:41:57.657  5736  5736 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,11-24 16:41:57.657  5736  5736 D BluetoothMapService: STATE_ON
11-24 16:41:57.658  5736  5849 D ObexServerSockets0: Accepting socket connection...
11-24 16:41:57.658  5682  5682 D LocalBluetoothProfileManager: Adding local A2DP profile
11-24 16:41:57.658  5736  5848 D ObexServerSockets0: Accepting socket connection...
11-24 16:41:57.659  5736  5850 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-24 16:41:57.660  5736  5850 D BluetoothSdpJni: sdpCreateSapsRecordNative:
,11-24 16:41:57.661  5736  5850 D BluetoothSdpJni: SDP Create record success - handle: 1
,11-24 16:41:57.664  5682  5682 D LocalBluetoothProfileManager: Adding local HEADSET profile
,11-24 16:41:57.670  5682  5682 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,11-24 16:41:57.672  5682  5682 D BluetoothA2dp: Proxy object connected
,11-24 16:41:57.677  3526  3526 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,11-24 16:41:57.677  5682  5682 D DockEventReceiver: finishStartingService: stopping service
,11-24 16:41:57.684  5682  5682 D BluetoothPbap: Proxy object connected
11-24 16:41:57.685  5682  5682 D PbapServerProfile: Bluetooth service connected
11-24 16:41:57.685  5736  5736 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
11-24 16:41:57.685  5736  5736 D ObexServerSockets0: prepareForNewConnect()
,11-24 16:41:57.687  3105  3105 D BluetoothPbap: Proxy object connected
11-24 16:41:57.687  3105  3105 D PbapServerProfile: Bluetooth service connected
,11-24 16:41:57.694  5736  5854 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-24 16:41:57.708  5736  5858 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-24 16:41:57.709  5736  5858 I BtOppRfcommListener: Accept thread started.
,11-24 16:41:57.741  3105  3293 D BluetoothHeadset: Proxy object connected
,11-24 16:41:57.741  3105  3105 D HeadsetProfile: Bluetooth service connected
11-24 16:41:57.741   927   927 D BluetoothHeadset: Proxy object connected
11-24 16:41:57.741  3743  3767 D BluetoothHeadset: Proxy object connected
11-24 16:41:57.742   927   927 D BluetoothHeadset: Proxy object connected
11-24 16:41:57.742   927   927 D BluetoothHeadset: Proxy object connected
,11-24 16:41:57.751   927   944 D BluetoothHeadset: Proxy object connected
,11-24 16:41:57.753  3743  3765 D BluetoothHeadset: Proxy object connected
,11-24 16:41:57.753  3105  3117 D BluetoothHeadset: Proxy object connected
11-24 16:41:57.753  3105  3105 D HeadsetProfile: Bluetooth service connected
11-24 16:41:57.753   927   944 D BluetoothHeadset: Proxy object connected
,11-24 16:41:57.767  5682  5693 D BluetoothHeadset: Proxy object connected
,11-24 16:41:57.768  5682  5682 D HeadsetProfile: Bluetooth service connected
,11-24 16:41:59.862  3621  3801 I Keyboard.Facilitator.LanguageModelFlusher: run()
,11-24 16:41:59.863  3621  3801 I Keyboard.Facilitator: flushDynamicLanguageModels()
,11-24 16:41:59.890  3526  3526 I ConfigService: onCreate
,11-24 16:42:01.693  5736  5821 D BluetoothAdapterState: Current state: ON, message: 23
,11-24 16:42:01.693  5736  5821 D BluetoothAdapterProperties: Setting state to 13
,11-24 16:42:01.694  5736  5821 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,11-24 16:42:01.695  5736  5821 D BluetoothAdapterProperties: onBluetoothDisable()
,11-24 16:42:01.697  5736  5821 I BluetoothAdapterState: Entering PendingCommandState
11-24 16:42:01.701  5736  5736 D BluetoothMapService: onReceive
11-24 16:42:01.701  5736  5736 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
11-24 16:42:01.702  5736  5736 D BluetoothMapService: STATE_TURNING_OFF
11-24 16:42:01.703  5736  5736 D BluetoothMapService: MAP Service closeService in
11-24 16:42:01.703  5736  5736 D BluetoothMapMasInstance0: MAP Service shutdown
11-24 16:42:01.703  5736  5736 D ObexServerSockets0: shutdown(block = true)
,11-24 16:42:01.704  5736  5736 D ObexServerSockets0: shutdown called from another thread - interrupt().
11-24 16:42:01.705  5736  5736 D ObexServerSockets0: shutdown called from another thread - interrupt().
,11-24 16:42:01.705  5736  5848 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
11-24 16:42:01.705  5736  5849 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
11-24 16:42:01.706  5736  5834 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
11-24 16:42:01.708  5615  5615 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-24 16:42:01.708  5615  5615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-24 16:42:01.708  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-24 16:42:01.708  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-24 16:42:01.708  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-24 16:42:01.708  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-24 16:42:01.708  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-24 16:42:01.708  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-24 16:42:01.708  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-24 16:42:01.708  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-24 16:42:01.708  5736  5736 I BtOppRfcommListener: stopping Accept Thread
11-24 16:42:01.709  5736  5858 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
11-24 16:42:01.709  5736  5858 I BtOppRfcommListener: BluetoothSocket listen thread finished
11-24 16:42:01.711  5736  5825 D BluetoothAdapterProperties: Scan Mode:20
11-24 16:42:01.711  5736  5821 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
11-24 16:42:01.711  5615  5615 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-24 16:42:01.711  5615  5615 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
11-24 16:42:01.712  5682  5682 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
11-24 16:42:01.716  5615  5615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-24 16:42:01.723  5682  5682 D DockEventReceiver: finishStartingService: stopping service
,11-24 16:42:01.725  5736  5736 D HeadsetService: Received stop request...Stopping profile...
,11-24 16:42:01.729  3105  3117 D BluetoothHeadset: Proxy object disconnected
,11-24 16:42:01.729   927   927 D BluetoothHeadset: Proxy object disconnected
,11-24 16:42:01.729  5736  5736 D A2dpService: Received stop request...Stopping profile...
11-24 16:42:01.729  3743  3957 D BluetoothHeadset: Proxy object disconnected
11-24 16:42:01.730  5736  5840 D A2dpStateMachine: Exit Disconnected: -1
11-24 16:42:01.730   927   927 D BluetoothHeadset: Proxy object disconnected
11-24 16:42:01.730   927   927 D BluetoothHeadset: Proxy object disconnected
11-24 16:42:01.731  3105  3105 D HeadsetProfile: Bluetooth service disconnected
,11-24 16:42:01.730  5682  5694 D BluetoothHeadset: Proxy object disconnected
11-24 16:42:01.732  3105  3105 D BluetoothA2dp: Proxy object disconnected
,11-24 16:42:01.733   927   927 D BluetoothA2dp: Proxy object disconnected
11-24 16:42:01.734  5682  5682 D HeadsetProfile: Bluetooth service disconnected
11-24 16:42:01.734  5682  5682 D BluetoothA2dp: Proxy object disconnected
11-24 16:42:01.736  5736  5736 D HidService: Received stop request...Stopping profile...
11-24 16:42:01.736  5736  5736 D HidService: Stopping Bluetooth HidService
11-24 16:42:01.738  3526  3526 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
11-24 16:42:01.739  3105  3105 D BluetoothInputDevice: Proxy object disconnected
11-24 16:42:01.739  3105  3105 D HidProfile: Bluetooth service disconnected
11-24 16:42:01.740  5736  5736 D HealthService: Received stop request...Stopping profile...
11-24 16:42:01.740  5682  5682 D BluetoothInputDevice: Proxy object disconnected
11-24 16:42:01.740  5682  5682 D HidProfile: Bluetooth service disconnected
11-24 16:42:01.741  5736  5736 D PanService: Received stop request...Stopping profile...
11-24 16:42:01.742  3105  3105 D BluetoothPan: BluetoothPAN Proxy object disconnected
11-24 16:42:01.742  3105  3105 D PanProfile: Bluetooth service disconnected
11-24 16:42:01.742  5682  5682 D BluetoothPan: BluetoothPAN Proxy object disconnected
11-24 16:42:01.742  5682  5682 D PanProfile: Bluetooth service disconnected
,11-24 16:42:01.742  5736  5736 D BluetoothMapService: Received stop request...Stopping profile...
11-24 16:42:01.742  5736  5736 D BluetoothMapService: stop()
,11-24 16:42:01.743  5736  5736 D BluetoothMapAppObserver: deinitObservers()
11-24 16:42:01.743  5736  5736 D BluetoothMapAppObserver: removeReceiver()
11-24 16:42:01.744  3105  3105 D BluetoothMap: Proxy object disconnected
11-24 16:42:01.744  3105  3105 D MapProfile: Bluetooth service disconnected
11-24 16:42:01.744  5682  5682 D BluetoothMap: Proxy object disconnected
11-24 16:42:01.744  5682  5682 D MapProfile: Bluetooth service disconnected
11-24 16:42:01.745  5736  5736 D SapService: Received stop request...Stopping profile...
11-24 16:42:01.745  5736  5736 V SapService: stop()
11-24 16:42:01.746  5736  5736 V BluetoothAdapterState: isTurningOff()=true
11-24 16:42:01.746  5736  5736 V BluetoothAdapterState: isTurningOn()=false
11-24 16:42:01.746  5736  5736 V BluetoothAdapterState: isBleTurningOn()=false
,11-24 16:42:01.746  5736  5736 V BluetoothAdapterState: isBleTurningOff()=false
11-24 16:42:01.747  5736  5736 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
11-24 16:42:01.747  5736  5736 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
11-24 16:42:01.747  5736  5832 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-24 16:42:01.747  5736  5832 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-24 16:42:01.747  5736  5736 V BluetoothAdapterState: isTurningOff()=true
11-24 16:42:01.748  5736  5832 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-24 16:42:01.748  5736  5736 V BluetoothAdapterState: isTurningOn()=false
11-24 16:42:01.748  5736  5736 V BluetoothAdapterState: isBleTurningOn()=false
11-24 16:42:01.748  5736  5736 V BluetoothAdapterState: isBleTurningOff()=false
11-24 16:42:01.749  5736  5825 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
11-24 16:42:01.749  5736  5825 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
11-24 16:42:01.749  5736  5832 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-24 16:42:01.749  5736  5832 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-24 16:42:01.749  5736  5832 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
11-24 16:42:01.749  5736  5832 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
11-24 16:42:01.749  5736  5832 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
11-24 16:42:01.749  5736  5832 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
11-24 16:42:01.750  5736  5825 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
11-24 16:42:01.750  3105  3105 D BluetoothPbap: Proxy object disconnected
11-24 16:42:01.750  3105  3105 D PbapServerProfile: Bluetooth service disconnected
11-24 16:42:01.750  5736  5736 V BluetoothAdapterState: isTurningOff()=true
11-24 16:42:01.750  5736  5736 V BluetoothAdapterState: isTurningOn()=false
11-24 16:42:01.751  5736  5736 V BluetoothAdapterState: isBleTurningOn()=false
11-24 16:42:01.751  5682  5682 D BluetoothPbap: Proxy object disconnected
11-24 16:42:01.751  5736  5736 V BluetoothAdapterState: isBleTurningOff()=false
11-24 16:42:01.751  5682  5682 D PbapServerProfile: Bluetooth service disconnected
11-24 16:42:01.751  5736  5736 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
11-24 16:42:01.751  5736  5736 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
11-24 16:42:01.751  5736  5736 V BluetoothAdapterState: isTurningOff()=true
11-24 16:42:01.751  5736  5736 V BluetoothAdapterState: isTurningOn()=false
11-24 16:42:01.751  5736  5736 V BluetoothAdapterState: isBleTurningOn()=false
11-24 16:42:01.751  5736  5736 V BluetoothAdapterState: isBleTurningOff()=false
11-24 16:42:01.752  5736  5736 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
,11-24 16:42:01.753  5736  5736 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
,11-24 16:42:01.753  5736  5736 V BluetoothAdapterState: isTurningOff()=true
11-24 16:42:01.753  5736  5736 V BluetoothAdapterState: isTurningOn()=false
11-24 16:42:01.753  5736  5736 V BluetoothAdapterState: isBleTurningOn()=false
11-24 16:42:01.753  5736  5736 V BluetoothAdapterState: isBleTurningOff()=false
11-24 16:42:01.753  5736  5736 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
11-24 16:42:01.753  5736  5736 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
11-24 16:42:01.754  5736  5736 D BluetoothMapService: MAP Service closeService in
,11-24 16:42:01.754  5736  5736 V BluetoothAdapterState: isTurningOff()=true
11-24 16:42:01.754  5736  5736 V BluetoothAdapterState: isTurningOn()=false
11-24 16:42:01.754  5736  5736 V BluetoothAdapterState: isBleTurningOn()=false
11-24 16:42:01.754  5736  5736 V BluetoothAdapterState: isBleTurningOff()=false
11-24 16:42:01.755  5736  5736 D BluetoothMapService: cleanup()
11-24 16:42:01.755  5736  5736 D BluetoothMapService: MAP Service closeService in
11-24 16:42:01.755  5736  5736 V BluetoothAdapterState: isTurningOff()=true
11-24 16:42:01.755  5736  5736 V BluetoothAdapterState: isTurningOn()=false
11-24 16:42:01.755  5736  5736 V BluetoothAdapterState: isBleTurningOn()=false
11-24 16:42:01.755  5736  5736 V BluetoothAdapterState: isBleTurningOff()=false
11-24 16:42:01.755  5736  5821 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
,11-24 16:42:01.755  5736  5821 D BluetoothAdapterProperties: Setting state to 15
11-24 16:42:01.755  5736  5821 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
11-24 16:42:01.756  5736  5821 I BluetoothAdapterState: Entering BleOnState
11-24 16:42:01.756  5736  5825 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
11-24 16:42:01.756  5736  5825 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
11-24 16:42:01.757   927   944 D BluetoothA2dp: onBluetoothStateChange: up=false
11-24 16:42:01.757   927   944 D BluetoothHeadset: onBluetoothStateChange: up=false
11-24 16:42:01.758  3105  3117 D BluetoothPbap: onBluetoothStateChange: up=false
11-24 16:42:01.760  3105  3952 D BluetoothInputDevice: onBluetoothStateChange: up=false
11-24 16:42:01.761  5682  5694 D BluetoothA2dp: onBluetoothStateChange: up=false
,11-24 16:42:01.762  5682  5693 D BluetoothPbap: onBluetoothStateChange: up=false
11-24 16:42:01.763  3105  3118 D BluetoothA2dp: onBluetoothStateChange: up=false
11-24 16:42:01.763  3105  3293 D BluetoothMap: onBluetoothStateChange: up=false
11-24 16:42:01.764  3105  3117 D BluetoothPan: onBluetoothStateChange on: false
11-24 16:42:01.765  5682  5864 D BluetoothInputDevice: onBluetoothStateChange: up=false
,11-24 16:42:01.766   927   944 D BluetoothHeadset: onBluetoothStateChange: up=false
,11-24 16:42:01.766  5682  5694 D BluetoothMap: onBluetoothStateChange: up=false
11-24 16:42:01.767  3743  3767 D BluetoothHeadset: onBluetoothStateChange: up=false
11-24 16:42:01.767  5682  5693 D BluetoothPan: onBluetoothStateChange on: false
11-24 16:42:01.767  3105  3952 D BluetoothHeadset: onBluetoothStateChange: up=false
11-24 16:42:01.768  5682  5864 D BluetoothHeadset: onBluetoothStateChange: up=false
11-24 16:42:01.768   927   944 D BluetoothHeadset: onBluetoothStateChange: up=false
11-24 16:42:01.768  5736  5821 D BluetoothAdapterState: Current state: BLE ON, message: 20
11-24 16:42:01.768  5736  5821 D BluetoothAdapterProperties: Setting state to 16
11-24 16:42:01.768  5736  5821 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
,11-24 16:42:01.769  5736  5821 D BluetoothAdapterProperties: onBleDisable
11-24 16:42:01.770  5736  5821 I BluetoothAdapterState: Entering PendingCommandState
11-24 16:42:01.770  5736  5822 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
11-24 16:42:01.771  5736  5832 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
11-24 16:42:01.771  5736  5832 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-24 16:42:01.772  5736  5825 D BluetoothAdapterProperties: Scan Mode:20
11-24 16:42:01.772  5615  5615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-24 16:42:01.773  5682  5682 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,11-24 16:42:01.773  5615  5615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-24 16:42:01.777  3526  3526 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,11-24 16:42:01.777  5682  5682 D DockEventReceiver: finishStartingService: stopping service
,11-24 16:42:01.985  5736  5825 I bt_hci  : shut_down
,11-24 16:42:01.995  5736  5829 D bt_hwcfg: hw_epilog_process
,11-24 16:42:01.996  5736  5829 I bt_vendor: low_power_mode_cb
,11-24 16:42:01.998  5736  5829 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,11-24 16:42:01.999  5736  5829 I bt_vendor: epilog_cb
11-24 16:42:01.999  5736  5829 I bt_hci  : epilog_finished_callback
,11-24 16:42:02.003  5736  5825 I bt_hci_h4: hal_close
,11-24 16:42:02.005  5736  5825 I bt_userial_vendor: device fd = 54 close
,11-24 16:42:02.124  5736  5822 D bt_stack_manager: event_shut_down_stack finished.
,11-24 16:42:02.125  5736  5821 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,11-24 16:42:02.129  5736  5821 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,11-24 16:42:02.129  5736  5736 D BtGatt.DebugUtils: handleDebugAction() action=null
11-24 16:42:02.130  5736  5736 D BtGatt.GattService: Received stop request...Stopping profile...
11-24 16:42:02.130  5736  5736 D BtGatt.GattService: stop()
11-24 16:42:02.130  5736  5736 D BtGatt.AdvertiseManager: advertise clients cleared
,11-24 16:42:02.134  5736  5736 V BluetoothAdapterState: isTurningOff()=false
,11-24 16:42:02.135  5736  5736 V BluetoothAdapterState: isTurningOn()=false
,11-24 16:42:02.135  5736  5736 V BluetoothAdapterState: isBleTurningOn()=false
,11-24 16:42:02.135  5736  5736 V BluetoothAdapterState: isBleTurningOff()=true
11-24 16:42:02.135  5736  5821 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
,11-24 16:42:02.136  5736  5821 D BluetoothAdapterProperties: Setting state to 10
11-24 16:42:02.136  5736  5821 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
11-24 16:42:02.137  5736  5821 I BluetoothAdapterState: Entering OffState
11-24 16:42:02.138   927   944 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,11-24 16:42:02.150  5736  5736 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,11-24 16:42:02.151  5736  5736 W BluetoothSdpJni: Cleaning up Bluetooth Health object
11-24 16:42:02.151  5736  5736 I BluetoothServiceJni: cleanupNative: return from cleanup
,11-24 16:42:02.153  5736  5822 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,11-24 16:42:02.160  5736  5736 I art     : System.exit called, status: 0
,11-24 16:42:02.160  5736  5736 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,11-24 16:42:02.188   927  3116 I ActivityManager: Process com.android.bluetooth (pid 5736) has died
,11-24 16:42:02.972   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 16:42:03.973   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 16:42:04.919  3526  3526 I ConfigService: onDestroy
,11-24 16:42:04.974   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 16:42:05.975   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 16:42:06.691  5615  5663 D io.jxcore.node.ConnectivityMonitor: stop
,11-24 16:42:06.691  5615  5663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
11-24 16:42:06.698  5615  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 16:42:06.698  5615  5663 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2b47263 removed from the list
11-24 16:42:06.698  5615  5663 D io.jxcore.node.ConnectivityMonitor: stop
11-24 16:42:06.701  5615  5663 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-24 16:42:06.701  5615  5663 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@ef0bbde added. We now have 4 listener(s)
11-24 16:42:06.701  5615  5663 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-24 16:42:06.703  5615  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 16:42:06.703  5615  5663 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@ef0bbde removed from the list
11-24 16:42:06.703  5615  5663 D io.jxcore.node.ConnectivityMonitor: stop
11-24 16:42:06.705  5615  5663 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-24 16:42:06.705  5615  5663 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@171d1bf added. We now have 4 listener(s)
11-24 16:42:06.706  5615  5663 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-24 16:42:06.976   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 16:42:07.977   535   535 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,11-24 16:42:11.717  5615  5663 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-24 16:42:11.750   927   944 I ActivityManager: Start proc 5869:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,11-24 16:42:11.853  5869  5869 D AdapterServiceConfig: Adding HeadsetService
,11-24 16:42:11.854  5869  5869 D AdapterServiceConfig: Adding A2dpService
11-24 16:42:11.854  5869  5869 D AdapterServiceConfig: Adding HidService
11-24 16:42:11.854  5869  5869 D AdapterServiceConfig: Adding HealthService
11-24 16:42:11.854  5869  5869 D AdapterServiceConfig: Adding PanService
11-24 16:42:11.855  5869  5869 D AdapterServiceConfig: Adding GattService
11-24 16:42:11.855  5869  5869 D AdapterServiceConfig: Adding BluetoothMapService
,11-24 16:42:11.855  5869  5869 D AdapterServiceConfig: Adding SapService
,11-24 16:42:11.867   927   944 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@24b6647:true
,11-24 16:42:11.867  5869  5869 D BluetoothAdapterState: make() - Creating AdapterState
,11-24 16:42:11.870  5869  5869 I bt_bluedroid: init
11-24 16:42:11.871  5869  5881 I BluetoothAdapterState: Entering OffState
,11-24 16:42:11.873  5869  5882 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,11-24 16:42:11.873  5869  5882 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
11-24 16:42:11.873  5869  5882 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
11-24 16:42:11.874  5869  5882 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
11-24 16:42:11.874  5869  5869 I bt_bluedroid: get_profile_interface socket
,11-24 16:42:11.876  5869  5869 I bt_bluedroid: get_profile_interface sdp
11-24 16:42:11.876  5869  5885 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:D4
,11-24 16:42:11.877  5869  5885 D BluetoothAdapterProperties: Name is: Nexus 6P
,11-24 16:42:11.882  5869  5880 I bt_bluedroid: config_hci_snoop_log
,11-24 16:42:11.883   927   944 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,11-24 16:42:11.887  5869  5881 D BluetoothAdapterState: Current state: OFF, message: 0
11-24 16:42:11.887  5869  5881 D BluetoothAdapterProperties: Setting state to 14
11-24 16:42:11.887  5869  5881 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
11-24 16:42:11.889  5869  5881 D BluetoothBondStateMachine: make
11-24 16:42:11.890  5869  5886 I BluetoothBondStateMachine: StableState(): Entering Off State
,11-24 16:42:11.893  5869  5881 I BluetoothAdapterState: Entering PendingCommandState
11-24 16:42:11.894  5869  5869 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,11-24 16:42:11.896  5869  5869 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@75cfb1d
11-24 16:42:11.898  5869  5869 D BtGatt.DebugUtils: handleDebugAction() action=null
11-24 16:42:11.898  5869  5869 D BtGatt.GattService: Received start request. Starting profile...
11-24 16:42:11.898  5869  5869 D BtGatt.GattService: start()
11-24 16:42:11.898  5869  5869 I bt_bluedroid: get_profile_interface gatt
,11-24 16:42:11.899  5869  5869 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@75cfb1d
11-24 16:42:11.899  5869  5869 D BtGatt.AdvertiseManager: advertise manager created
,11-24 16:42:11.905  5869  5869 V BluetoothAdapterState: isTurningOff()=false
,11-24 16:42:11.905  5869  5869 V BluetoothAdapterState: isTurningOn()=false
11-24 16:42:11.905  5869  5869 V BluetoothAdapterState: isBleTurningOn()=true
11-24 16:42:11.905  5869  5869 V BluetoothAdapterState: isBleTurningOff()=false
11-24 16:42:11.905  5869  5881 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,11-24 16:42:11.906  5869  5881 I bt_bluedroid: bt_bluedroid
11-24 16:42:11.907  5869  5882 D bt_stack_manager: event_start_up_stack is bringing up the stack.
11-24 16:42:11.907  5869  5882 I bt_hci  : start_up
,11-24 16:42:11.912  5869  5882 I bt_vendor: alloc value 0xf4077871
,11-24 16:42:11.912  5869  5882 I bt_vendor: init
11-24 16:42:11.912  5869  5882 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
11-24 16:42:11.912  5869  5882 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,11-24 16:42:12.021  5869  5882 D bt_hci  : start_up starting async portion
,11-24 16:42:12.021  5869  5889 I bt_hci  : event_finish_startup
11-24 16:42:12.021  5869  5889 I bt_hci_h4: hal_open
11-24 16:42:12.022  5869  5889 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,11-24 16:42:12.020  5890  5890 W irq/448-msm_hs_: type=1400 audit(0.0:120): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
11-24 16:42:12.024  5869  5889 I bt_userial_vendor: device fd = 54 open
,11-24 16:42:12.038  5869  5889 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,11-24 16:42:12.041  5869  5889 D bt_hwcfg: Chipset BCM4358A3
11-24 16:42:12.041  5869  5889 D bt_hwcfg: Target name = [BCM4358A3]
11-24 16:42:12.041  5869  5889 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,11-24 16:42:12.506  5869  5889 I bt_hwcfg: bt vendor lib: set UART baud 115200
,11-24 16:42:12.507  5869  5889 D bt_hwcfg: Settlement delay -- 100 ms
11-24 16:42:12.507  5869  5889 I bt_hwcfg: Setting fw settlement delay to 100 
,11-24 16:42:12.640  5869  5889 I bt_hwcfg: bt vendor lib: set UART baud 3000000
11-24 16:42:12.641  5869  5889 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:D4
,11-24 16:42:12.642  5869  5889 I bt_hwcfg: vendor lib fwcfg completed
11-24 16:42:12.642  5869  5889 I bt_vendor: firmware callback
11-24 16:42:12.642  5869  5889 I bt_hci  : firmware_config_callback
,11-24 16:42:12.651  5869  5892 I bt_btu  : btu_task pending for preload complete event
,11-24 16:42:12.651  5869  5892 I bt_btu_task: Bluetooth chip preload is complete
11-24 16:42:12.652  5869  5892 I bt_btu  : btu_task received preload complete event
,11-24 16:42:12.659  5869  5892 I         : BTE_InitTraceLevels -- TRC_HCI
,11-24 16:42:12.659  5869  5892 I         : BTE_InitTraceLevels -- TRC_L2CAP
11-24 16:42:12.659  5869  5892 I         : BTE_InitTraceLevels -- TRC_RFCOMM
11-24 16:42:12.659  5869  5892 I         : BTE_InitTraceLevels -- TRC_AVDT
,11-24 16:42:12.659  5869  5892 I         : BTE_InitTraceLevels -- TRC_AVRC
11-24 16:42:12.659  5869  5892 I         : BTE_InitTraceLevels -- TRC_A2D
,11-24 16:42:12.660  5869  5892 I         : BTE_InitTraceLevels -- TRC_BNEP
11-24 16:42:12.660  5869  5892 I         : BTE_InitTraceLevels -- TRC_BTM
11-24 16:42:12.660  5869  5892 I         : BTE_InitTraceLevels -- TRC_GAP
11-24 16:42:12.660  5869  5892 I         : BTE_InitTraceLevels -- TRC_PAN
,11-24 16:42:12.660  5869  5892 I         : BTE_InitTraceLevels -- TRC_SDP
11-24 16:42:12.660  5869  5892 I         : BTE_InitTraceLevels -- TRC_GATT
11-24 16:42:12.660  5869  5892 I         : BTE_InitTraceLevels -- TRC_SMP
,11-24 16:42:12.660  5869  5892 I         : BTE_InitTraceLevels -- TRC_BTAPP
11-24 16:42:12.660  5869  5892 I         : BTE_InitTraceLevels -- TRC_BTIF
,11-24 16:42:12.740  5869  5892 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf3ff5549
,11-24 16:42:12.740  5869  5892 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf3ff5549 
,11-24 16:42:12.758  5869  5885 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,11-24 16:42:12.760  5869  5885 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,11-24 16:42:12.761  5869  5885 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:D4
,11-24 16:42:12.764  5869  5885 D BluetoothAdapterProperties: Name is: Nexus 6P
,11-24 16:42:12.767  5869  5885 D BluetoothAdapterProperties: Scan Mode:20
,11-24 16:42:12.768  5869  5885 D BluetoothAdapterProperties: Discoverable Timeout:120
11-24 16:42:12.768  5869  5885 D bt_hci  : do_postload posting postload work item
11-24 16:42:12.768  5869  5889 I bt_hci  : event_postload
11-24 16:42:12.768  5869  5889 I bt_vendor: sco_config_cb
11-24 16:42:12.768  5869  5889 I bt_hci  : sco_config_callback postload finished.
,11-24 16:42:12.771  5869  5885 D bt_bte_conf: Device ID record 1 : primary
,11-24 16:42:12.772  5869  5885 D bt_bte_conf:   vendorId            = 000f
11-24 16:42:12.772  5869  5885 D bt_bte_conf:   vendorIdSource      = 0001
11-24 16:42:12.772  5869  5885 D bt_bte_conf:   product             = 1200
11-24 16:42:12.772  5869  5885 D bt_bte_conf:   version             = 1436
11-24 16:42:12.772  5869  5885 D bt_bte_conf:   clientExecutableURL = 
,11-24 16:42:12.772  5869  5885 D bt_bte_conf:   serviceDescription  = 
11-24 16:42:12.772  5869  5885 D bt_bte_conf:   documentationURL    = 
,11-24 16:42:12.772  5869  5885 D bt_bte_conf: bte_load_did_conf no section named DID2.
11-24 16:42:12.773  5869  5882 D bt_stack_manager: event_start_up_stack finished
11-24 16:42:12.774  5869  5881 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
11-24 16:42:12.774  5869  5881 D BluetoothAdapterProperties: Setting state to 15
11-24 16:42:12.774  5869  5881 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
,11-24 16:42:12.776  5869  5889 I bt_vendor: low_power_mode_cb
11-24 16:42:12.778  5869  5881 I BluetoothAdapterState: Entering BleOnState
,11-24 16:42:12.784  5869  5881 D BluetoothAdapterState: Current state: BLE ON, message: 1
,11-24 16:42:12.784  5869  5881 D BluetoothAdapterProperties: Setting state to 11
11-24 16:42:12.784  5869  5881 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,11-24 16:42:12.790  5869  5869 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@75cfb1d
11-24 16:42:12.791  5869  5869 D HeadsetService: Received start request. Starting profile...
11-24 16:42:12.794  5869  5869 I BluetoothHeadsetServiceJni: classInitNative: succeeds
11-24 16:42:12.795  5869  5869 D HeadsetStateMachine: make
,11-24 16:42:12.805  5869  5881 I BluetoothAdapterState: Entering PendingCommandState
,11-24 16:42:12.808  5869  5869 D HeadsetStateMachine: max_hf_connections = 1
,11-24 16:42:12.808  5869  5869 I bt_bluedroid: get_profile_interface handsfree
11-24 16:42:12.808  5869  5885 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
11-24 16:42:12.808  5869  5885 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
,11-24 16:42:12.812  5869  5869 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@75cfb1d
,11-24 16:42:12.812  5869  5869 D A2dpService: Received start request. Starting profile...
,11-24 16:42:12.813  5869  5869 I BluetoothAvrcpServiceJni: classInitNative: succeeds
11-24 16:42:12.814  5869  5869 I bt_bluedroid: get_profile_interface avrcp
,11-24 16:42:12.820  5869  5869 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,11-24 16:42:12.820  5869  5869 I BluetoothA2dpServiceJni: classInitNative: succeeds
11-24 16:42:12.820  5869  5869 D A2dpStateMachine: make
11-24 16:42:12.821  5869  5869 I bt_bluedroid: get_profile_interface a2dp
,11-24 16:42:12.822  5869  5885 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,11-24 16:42:12.827  5869  5900 D A2dpStateMachine: Enter Disconnected: -2
,11-24 16:42:12.827  5869  5869 I BluetoothHidServiceJni: classInitNative: succeeds
,11-24 16:42:12.828  5869  5869 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@75cfb1d
,11-24 16:42:12.828  5869  5869 D HidService: Received start request. Starting profile...
11-24 16:42:12.829  5869  5869 I bt_bluedroid: get_profile_interface hidhost
11-24 16:42:12.829  5869  5869 D HidService: setHidService(): set to: null
11-24 16:42:12.829  5869  5885 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf3fd656d
11-24 16:42:12.829  5869  5885 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
11-24 16:42:12.831  5869  5869 I BluetoothHealthServiceJni: classInitNative: succeeds
11-24 16:42:12.831  5869  5869 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@75cfb1d
,11-24 16:42:12.832  5869  5869 D HealthService: Received start request. Starting profile...
,11-24 16:42:12.834  5869  5869 I bt_bluedroid: get_profile_interface health
,11-24 16:42:12.834  3526  3526 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
11-24 16:42:12.834  5869  5869 I BluetoothPanServiceJni: classInitNative(L105): succeeds
11-24 16:42:12.835  5869  5869 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@75cfb1d
11-24 16:42:12.836  5869  5869 D PanService: Received start request. Starting profile...
11-24 16:42:12.836  5869  5869 D BluetoothPanServiceJni: initializeNative(L110): pan
11-24 16:42:12.836  5869  5869 I bt_bluedroid: get_profile_interface pan
11-24 16:42:12.837  5869  5885 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
11-24 16:42:12.838  5869  5869 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@75cfb1d
11-24 16:42:12.839  5869  5869 D BluetoothMapService: Received start request. Starting profile...
11-24 16:42:12.839  5869  5869 D BluetoothMapService: start()
,11-24 16:42:12.842  5869  5869 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
11-24 16:42:12.843  5869  5869 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
11-24 16:42:12.843  5869  5869 D BluetoothMapAppObserver: createReceiver()
,11-24 16:42:12.844  5869  5869 D BluetoothMapAppObserver: initObservers()
11-24 16:42:12.844  5869  5869 D BluetoothMapAppObserver: getEnabledAccountItems()
,11-24 16:42:12.851  5869  5869 V SapService: SapBinder()
11-24 16:42:12.852  5869  5869 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@75cfb1d
,11-24 16:42:12.852  5869  5869 D SapService: Received start request. Starting profile...
11-24 16:42:12.852  5869  5869 V SapService: start()
,11-24 16:42:12.854  5869  5869 V BluetoothAdapterState: isTurningOff()=false
,11-24 16:42:12.854  5869  5869 V BluetoothAdapterState: isTurningOn()=true
11-24 16:42:12.854  5869  5869 V BluetoothAdapterState: isBleTurningOn()=false
11-24 16:42:12.854  5869  5869 V BluetoothAdapterState: isBleTurningOff()=false
11-24 16:42:12.855  5869  5869 V BluetoothAdapterState: isTurningOff()=false
11-24 16:42:12.855  5869  5869 V BluetoothAdapterState: isTurningOn()=true
11-24 16:42:12.855  5869  5869 V BluetoothAdapterState: isBleTurningOn()=false
11-24 16:42:12.855  5869  5898 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,11-24 16:42:12.855  5869  5869 V BluetoothAdapterState: isBleTurningOff()=false
11-24 16:42:12.855  5869  5869 V BluetoothAdapterState: isTurningOff()=false
11-24 16:42:12.855  5869  5869 V BluetoothAdapterState: isTurningOn()=true
11-24 16:42:12.855  5869  5869 V BluetoothAdapterState: isBleTurningOn()=false
11-24 16:42:12.855  5869  5869 V BluetoothAdapterState: isBleTurningOff()=false
11-24 16:42:12.856  5869  5869 V BluetoothAdapterState: isTurningOff()=false
11-24 16:42:12.856  5869  5869 V BluetoothAdapterState: isTurningOn()=true
11-24 16:42:12.856  5869  5869 V BluetoothAdapterState: isBleTurningOn()=false
,11-24 16:42:12.856  5869  5869 V BluetoothAdapterState: isBleTurningOff()=false
11-24 16:42:12.856  5869  5869 V BluetoothAdapterState: isTurningOff()=false
11-24 16:42:12.856  5869  5869 V BluetoothAdapterState: isTurningOn()=true
11-24 16:42:12.857  5869  5869 V BluetoothAdapterState: isBleTurningOn()=false
11-24 16:42:12.857  5869  5869 V BluetoothAdapterState: isBleTurningOff()=false
11-24 16:42:12.857  5869  5869 V BluetoothAdapterState: isTurningOff()=false
,11-24 16:42:12.857  5869  5869 V BluetoothAdapterState: isTurningOn()=true
11-24 16:42:12.857  5869  5869 V BluetoothAdapterState: isBleTurningOn()=false
11-24 16:42:12.857  5869  5869 V BluetoothAdapterState: isBleTurningOff()=false
11-24 16:42:12.858  5869  5869 V BluetoothAdapterState: isTurningOff()=false
11-24 16:42:12.858  5869  5869 V BluetoothAdapterState: isTurningOn()=true
11-24 16:42:12.858  5869  5869 V BluetoothAdapterState: isBleTurningOn()=false
11-24 16:42:12.858  5869  5869 V BluetoothAdapterState: isBleTurningOff()=false
11-24 16:42:12.858  5869  5881 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
11-24 16:42:12.858  5869  5881 D BluetoothAdapterProperties: ScanMode =  20
11-24 16:42:12.858  5869  5881 D BluetoothAdapterProperties: State =  11
11-24 16:42:12.859  5869  5881 D BluetoothAdapterProperties: Setting state to 12
11-24 16:42:12.859  5869  5881 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
11-24 16:42:12.859  5869  5881 I BluetoothAdapterState: Entering OnState
11-24 16:42:12.859   927   944 D BluetoothA2dp: onBluetoothStateChange: up=true
,11-24 16:42:12.862   927   944 D BluetoothHeadset: onBluetoothStateChange: up=true
,11-24 16:42:12.863  5869  5885 D BluetoothAdapterProperties: Scan Mode:21
11-24 16:42:12.863  3105  3117 D BluetoothPbap: onBluetoothStateChange: up=true
11-24 16:42:12.863  5869  5885 D BluetoothAdapterProperties: Discoverable Timeout:120
11-24 16:42:12.863   927   927 D BluetoothA2dp: Proxy object connected
11-24 16:42:12.864  3105  3293 D BluetoothInputDevice: onBluetoothStateChange: up=true
11-24 16:42:12.867  5682  5864 D BluetoothA2dp: onBluetoothStateChange: up=true
11-24 16:42:12.867  3105  3105 D BluetoothInputDevice: Proxy object connected
11-24 16:42:12.867  3105  3105 D HidProfile: Bluetooth service connected
11-24 16:42:12.868  5869  5869 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
11-24 16:42:12.869  5869  5869 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
,11-24 16:42:12.870  5682  5693 D BluetoothPbap: onBluetoothStateChange: up=true
11-24 16:42:12.871  3105  3952 D BluetoothA2dp: onBluetoothStateChange: up=true
11-24 16:42:12.872  5869  5869 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-24 16:42:12.873  3105  3105 D BluetoothA2dp: Proxy object connected
11-24 16:42:12.873  3105  3293 D BluetoothMap: onBluetoothStateChange: up=true
11-24 16:42:12.874  5869  5869 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-24 16:42:12.875  3105  3118 D BluetoothPan: onBluetoothStateChange on: true
11-24 16:42:12.875  5869  5869 D ObexServerSockets: Succeed to create listening sockets 
11-24 16:42:12.875  5869  5869 D ObexServerSockets0: startAccept()
11-24 16:42:12.875  5869  5869 D ObexServerSockets0: prepareForNewConnect()
11-24 16:42:12.876  5682  5682 D BluetoothA2dp: Proxy object connected
11-24 16:42:12.877  5869  5869 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
,11-24 16:42:12.877  5682  5694 D BluetoothInputDevice: onBluetoothStateChange: up=true
11-24 16:42:12.877  5869  5869 D BluetoothSdpJni: SDP Create record success - handle: 0
11-24 16:42:12.877  5869  5905 D ObexServerSockets0: Accepting socket connection...
11-24 16:42:12.878  5869  5906 D ObexServerSockets0: Accepting socket connection...
11-24 16:42:12.879  3105  3105 D BluetoothMap: Proxy object connected
11-24 16:42:12.879  3105  3105 D MapProfile: Bluetooth service connected
11-24 16:42:12.879  3105  3105 D BluetoothMap: getConnectedDevices()
11-24 16:42:12.880   927   944 D BluetoothHeadset: onBluetoothStateChange: up=true
11-24 16:42:12.880  5682  5693 D BluetoothMap: onBluetoothStateChange: up=true
,11-24 16:42:12.882  3105  3105 D BluetoothPan: BluetoothPAN Proxy object connected
,11-24 16:42:12.882  3105  3105 D PanProfile: Bluetooth service connected
11-24 16:42:12.882  3743  3765 D BluetoothHeadset: onBluetoothStateChange: up=true
,11-24 16:42:12.883  5682  5694 D BluetoothPan: onBluetoothStateChange on: true
11-24 16:42:12.884  3105  3293 D BluetoothHeadset: onBluetoothStateChange: up=true
11-24 16:42:12.885  5682  5693 D BluetoothHeadset: onBluetoothStateChange: up=true
,11-24 16:42:12.885   927   944 D BluetoothHeadset: onBluetoothStateChange: up=true
11-24 16:42:12.885  5682  5682 D BluetoothInputDevice: Proxy object connected
11-24 16:42:12.885  5682  5682 D HidProfile: Bluetooth service connected
11-24 16:42:12.886   927   927 I Telecom : BluetoothPhoneService: queryPhoneState
11-24 16:42:12.887  5869  5869 D BluetoothMapService: onReceive
,11-24 16:42:12.887  5869  5869 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
11-24 16:42:12.887  5869  5869 D BluetoothMapService: STATE_ON
11-24 16:42:12.888  5682  5682 D BluetoothMap: Proxy object connected
11-24 16:42:12.888  5682  5682 D MapProfile: Bluetooth service connected
11-24 16:42:12.888  5682  5682 D BluetoothMap: getConnectedDevices()
,11-24 16:42:12.890  5682  5682 D BluetoothPan: BluetoothPAN Proxy object connected
,11-24 16:42:12.890  5682  5682 D PanProfile: Bluetooth service connected
11-24 16:42:12.891  5869  5907 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-24 16:42:12.893  5869  5907 D BluetoothSdpJni: sdpCreateSapsRecordNative:
,11-24 16:42:12.893  5869  5907 D BluetoothSdpJni: SDP Create record success - handle: 1
11-24 16:42:12.895  5682  5682 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,11-24 16:42:12.902  5682  5682 D DockEventReceiver: finishStartingService: stopping service
11-24 16:42:12.904  3526  3526 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,11-24 16:42:12.910  5682  5682 D BluetoothPbap: Proxy object connected
,11-24 16:42:12.910  5682  5682 D PbapServerProfile: Bluetooth service connected
,11-24 16:42:12.913  5869  5869 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
11-24 16:42:12.913  5869  5869 D ObexServerSockets0: prepareForNewConnect()
,11-24 16:42:12.917  3105  3105 D BluetoothPbap: Proxy object connected
11-24 16:42:12.917  3105  3105 D PbapServerProfile: Bluetooth service connected
,11-24 16:42:12.921  5869  5912 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-24 16:42:12.940  5869  5916 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-24 16:42:12.941  5869  5916 I BtOppRfcommListener: Accept thread started.
,11-24 16:42:12.964  3105  3118 D BluetoothHeadset: Proxy object connected
,11-24 16:42:12.964  3105  3105 D HeadsetProfile: Bluetooth service connected
11-24 16:42:12.964   927   927 D BluetoothHeadset: Proxy object connected
11-24 16:42:12.964  3743  3957 D BluetoothHeadset: Proxy object connected
11-24 16:42:12.964   927   927 D BluetoothHeadset: Proxy object connected
,11-24 16:42:12.964   927   927 D BluetoothHeadset: Proxy object connected
11-24 16:42:12.965  5682  5694 D BluetoothHeadset: Proxy object connected
11-24 16:42:12.966  5682  5682 D HeadsetProfile: Bluetooth service connected
,11-24 16:42:12.980   927   944 D BluetoothHeadset: Proxy object connected
,11-24 16:42:12.982  3743  3767 D BluetoothHeadset: Proxy object connected
,11-24 16:42:12.985  3105  3952 D BluetoothHeadset: Proxy object connected
,11-24 16:42:12.985  3105  3105 D HeadsetProfile: Bluetooth service connected
11-24 16:42:12.985  5682  5694 D BluetoothHeadset: Proxy object connected
11-24 16:42:12.986   927   944 D BluetoothHeadset: Proxy object connected
11-24 16:42:12.986  5682  5682 D HeadsetProfile: Bluetooth service connected
,11-24 16:42:16.553  3988  4415 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,11-24 16:42:16.734  5615  5663 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-24 16:42:16.734  5615  5663 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-24 16:42:16.734  5615  5663 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-24 16:42:16.734  5615  5663 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-24 16:42:16.734  5615  5663 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-24 16:42:16.734  5615  5663 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-24 16:42:16.734  5615  5663 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-24 16:42:16.734  5615  5663 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-24 16:42:16.734  5615  5663 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,11-24 16:42:16.740  5615  5663 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
,11-24 16:42:16.741  5615  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-24 16:42:16.741  5615  5663 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@171d1bf removed from the list
11-24 16:42:16.741  5615  5663 D io.jxcore.node.ConnectivityMonitor: stop
11-24 16:42:16.742  5615  5663 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-24 16:42:16.742  5615  5663 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@418b08c added. We now have 4 listener(s)
11-24 16:42:16.742  5615  5663 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-24 16:42:16.744   927  3655 D WifiService: setWifiEnabled: false pid=5615, uid=10077
11-24 16:42:16.745   927  3655 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-24 16:42:21.754  5615  5663 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-24 16:42:21.755   927  3747 D WifiService: setWifiEnabled: true pid=5615, uid=10077
,11-24 16:42:21.756   927  3747 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-24 16:42:21.766   506   918 D SoftapController: Softap fwReload - Ok
,11-24 16:42:21.771   506   918 D CommandListener: Setting iface cfg
11-24 16:42:21.772   506   918 D CommandListener: Trying to bring down wlan0
,11-24 16:42:21.774   506   918 D CommandListener: Clearing all IP addresses on wlan0
,11-24 16:42:21.779   927  2910 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,11-24 16:42:22.387   927  2910 D wifi    : set interface wlan0 flags (UP)
,11-24 16:42:22.392   927  2910 I WifiHAL : Initializing wifi
11-24 16:42:22.392   927  2910 I WifiHAL : Creating socket
11-24 16:42:22.396   927   944 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,11-24 16:42:22.397   927  2910 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
11-24 16:42:22.398   927  2910 D wifi    : Did set static halHandle = 0x7f8e691e00
11-24 16:42:22.398   927  2910 D wifi    : halHandle = 0x7f8e691e00, mVM = 0x7faaccd140, mCls = 0x1986
11-24 16:42:22.398   927  2910 D wifi    : array field set
11-24 16:42:22.398   927  2910 I WifiNative-HAL: interface[0] = wlan0
,11-24 16:42:22.401   927  5921 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=547850100224
11-24 16:42:22.401   927  5921 D wifi    : waitForHalEvents called, vm = 0x7faaccd140, obj = 0x1986, env = 0x7f8f1bc9c0
,11-24 16:42:22.461  5922  5922 I wpa_supplicant: Successfully initialized wpa_supplicant
,11-24 16:42:22.502   927  2910 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
11-24 16:42:22.503   927  2910 E WifiHW  : Unable to open connection to supplicant on "@android:wpa_wlan0": No such file or directory
,11-24 16:42:22.536  5922  5922 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,11-24 16:42:22.613  5922  5922 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,11-24 16:42:22.613  5922  5922 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,11-24 16:42:22.978   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 16:42:23.518   927  2910 D WifiConfigStore: Loading config and enabling all networks 
,11-24 16:42:23.554   927  2910 D WifiConfigStore: loaded 0 passpoint configs
11-24 16:42:23.555   927  2910 W WifiConfigStore: Upgrading network 4 to android.uid.system:1000
,11-24 16:42:23.556   927  2910 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,11-24 16:42:23.557   927  2910 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
11-24 16:42:23.558   927  2910 W WifiConfigStore: Upgrading network 3 to android.uid.system:1000
11-24 16:42:23.558   927  2910 W WifiConfigStore: Upgrading network 2 to android.uid.system:1000
,11-24 16:42:23.559   927  2910 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
11-24 16:42:23.560   927  2910 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 5
,11-24 16:42:23.560   927  2910 E WifiConfigStore: found sortedWifiConfigurations : "AndroidAP"WPA_PSK
11-24 16:42:23.560   927  2910 E WifiConfigStore: found sortedWifiConfigurations : "AndroidHotspot2346"WPA_PSK
11-24 16:42:23.560   927  2910 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
11-24 16:42:23.560   927  2910 E WifiConfigStore: found sortedWifiConfigurations : "Thali_internal"WPA_PSK
11-24 16:42:23.560   927  2910 E WifiConfigStore: found sortedWifiConfigurations : "MC"WPA_PSK
,11-24 16:42:23.565   927  2910 D WifiNative-HAL: Setting external_sim to 1
,11-24 16:42:23.566  4977  4977 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
11-24 16:42:23.566   927  2910 D wifi    : setting dfs flag to true, 0x7f924aa2c0
11-24 16:42:23.567   927  2910 D WifiStateMachine: Setting OUI to DA-A1-19
11-24 16:42:23.567   927  2910 D wifi    : setting scan oui 0x7f924aa2c0
11-24 16:42:23.567   927  2910 D WifiHAL : Sending mac address OUI
,11-24 16:42:23.573   927  2910 E native  : do suspend false
,11-24 16:42:23.585   927  2910 D wifi    : android_net_wifi_setLinkLayerStats: 1
11-24 16:42:23.585   506   918 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
11-24 16:42:23.586   927   927 D RttService: SCAN_AVAILABLE : 3
11-24 16:42:23.586   927  3020 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,11-24 16:42:23.587   506   918 D CommandListener: Setting iface cfg
,11-24 16:42:23.593   927  2909 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '137 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 137 Failed to set address (No such device)'
11-24 16:42:23.593   927  2909 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,11-24 16:42:23.605   927  2909 D WifiNative-HAL: p2pGetDeviceAddress
,11-24 16:42:23.611   927  2909 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:70
,11-24 16:42:23.611   927   942 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=164172 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=20 mControllerEnergyUsed=76 }
,11-24 16:42:23.979   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 16:42:24.981   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 16:42:25.982   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 16:42:26.720   927  2910 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,11-24 16:42:26.722   927  2910 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3
11-24 16:42:26.722   927  2910 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-24 16:42:26.734   927  2910 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=0
,11-24 16:42:26.770   927  2910 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=0
,11-24 16:42:26.774  5615  5663 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-24 16:42:26.774  5615  5663 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-24 16:42:26.774  5615  5663 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-24 16:42:26.774  5615  5663 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-24 16:42:26.774  5615  5663 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-24 16:42:26.774  5615  5663 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-24 16:42:26.774  5615  5663 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-24 16:42:26.774  5615  5663 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-24 16:42:26.774  5615  5663 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,11-24 16:42:26.776  5615  5663 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
11-24 16:42:26.776  5615  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 16:42:26.776  5615  5663 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@418b08c removed from the list
11-24 16:42:26.776  5615  5663 D io.jxcore.node.ConnectivityMonitor: stop
11-24 16:42:26.777  5922  5922 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,11-24 16:42:26.782  5615  5663 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,11-24 16:42:26.783  5615  5663 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
11-24 16:42:26.785  5615  5663 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@153ff60 Bundle[{}]
11-24 16:42:26.785  5615  5663 I io.jxcore.node.LifeCycleMonitor: start: OK
,11-24 16:42:26.786  5615  5663 I io.jxcore.node.LifeCycleMonitor: stop: OK
11-24 16:42:26.787  5615  5663 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,11-24 16:42:26.787  5615  5663 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,11-24 16:42:26.788  5615  5663 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
11-24 16:42:26.789  5615  5663 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,11-24 16:42:26.795  5615  5663 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 169)
,11-24 16:42:26.795  5615  5663 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
11-24 16:42:26.795  5615  5663 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 170)
,11-24 16:42:26.797  5615  5663 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,11-24 16:42:26.797  5615  5663 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c9603d5 added. We now have 3 listener(s)
,11-24 16:42:26.799  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
,11-24 16:42:26.799  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-24 16:42:26.799  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-24 16:42:26.799  5615  5663 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-24 16:42:26.799  5615  5663 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cc8b7ea added. We now have 4 listener(s)
11-24 16:42:26.799  5615  5663 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-24 16:42:26.800  5615  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,11-24 16:42:26.801  5615  5663 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,11-24 16:42:26.801  5615  5663 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@27bcadb added. We now have 4 listener(s)
,11-24 16:42:26.803  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
,11-24 16:42:26.803  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-24 16:42:26.803  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-24 16:42:26.803  5615  5663 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-24 16:42:26.803  5615  5663 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6e64978 added. We now have 5 listener(s)
11-24 16:42:26.804  5615  5663 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-24 16:42:26.804  5615  5663 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-24 16:42:26.804  5615  5663 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-24 16:42:26.804  5615  5663 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-24 16:42:26.804  5615  5663 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-24 16:42:26.804  5615  5663 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,11-24 16:42:26.804  5615  5663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-24 16:42:26.804  5615  5663 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c9603d5 removed from the list
11-24 16:42:26.804  5615  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 16:42:26.805  5615  5663 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cc8b7ea removed from the list
11-24 16:42:26.805  5615  5663 D io.jxcore.node.ConnectivityMonitor: stop
11-24 16:42:26.805  5615  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-62,5,main], id: 62
11-24 16:42:26.805  5615  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
,11-24 16:42:26.806  5615  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
,11-24 16:42:26.806  5615  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-24 16:42:26.806  5615  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-24 16:42:26.807  5615  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-24 16:42:26.807  5615  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-24 16:42:26.807  5615  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 16:42:26.807  5615  5663 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cc8b7ea not in the list
11-24 16:42:26.807  5615  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-62,5,main], id: 62
,11-24 16:42:26.807  5615  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
,11-24 16:42:26.808  5615  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-24 16:42:26.808  5615  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-24 16:42:26.808  5615  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
,11-24 16:42:26.808  5615  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-24 16:42:26.809  5615  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-24 16:42:26.809  5615  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 16:42:26.809  5615  5663 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6e64978 removed from the list
,11-24 16:42:26.809  5615  5663 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-24 16:42:26.809  5615  5663 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 16:42:26.809  5615  5663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-24 16:42:26.810  5615  5663 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@27bcadb removed from the list
,11-24 16:42:26.810  5615  5663 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-24 16:42:26.810  5615  5663 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5400851 added. We now have 3 listener(s)
,11-24 16:42:26.812  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
,11-24 16:42:26.812  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-24 16:42:26.812  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-24 16:42:26.812  5615  5663 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-24 16:42:26.812  5615  5663 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e7268b6 added. We now have 4 listener(s)
11-24 16:42:26.812  5615  5663 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-24 16:42:26.813  5615  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,11-24 16:42:26.814  5615  5663 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,11-24 16:42:26.814  5615  5663 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@56239b7 added. We now have 4 listener(s)
,11-24 16:42:26.816  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
,11-24 16:42:26.816  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-24 16:42:26.816  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-24 16:42:26.816  5615  5663 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-24 16:42:26.816  5615  5663 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2f28524 added. We now have 5 listener(s)
11-24 16:42:26.816  5615  5663 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-24 16:42:26.816  5615  5663 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-24 16:42:26.817  5615  5663 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
11-24 16:42:26.817  5615  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
11-24 16:42:26.817  5615  5663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-24 16:42:26.817  5615  5663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
,11-24 16:42:26.818  5615  5663 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,11-24 16:42:26.821  5615  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
,11-24 16:42:26.821  5615  5663 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-24 16:42:26.821  5615  5663 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,11-24 16:42:26.825  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-62,5,main], id: 62
,11-24 16:42:26.825  5615  5663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-24 16:42:26.826  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-24 16:42:26.826  5615  5663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-24 16:42:26.826  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 0
,11-24 16:42:26.828  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-62,5,main], id: 62
,11-24 16:42:26.828  5615  5663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
11-24 16:42:26.828  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
11-24 16:42:26.828  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
11-24 16:42:26.828  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
11-24 16:42:26.828  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-62,5,main], id: 62
,11-24 16:42:26.829  5615  5663 D BluetoothAdapter: STATE_ON
,11-24 16:42:26.831  5869  5897 D BtGatt.GattService: registerClient() - UUID=5f597e5e-3010-43aa-9a9e-0ec9a4dafef9
,11-24 16:42:26.831  5869  5885 D BtGatt.GattService: onClientRegistered() - UUID=5f597e5e-3010-43aa-9a9e-0ec9a4dafef9, clientIf=5
,11-24 16:42:26.832  5615  5626 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,11-24 16:42:26.833  5869  5908 D BtGatt.GattService: start scan with filters
,11-24 16:42:26.836  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
,11-24 16:42:26.837  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-62,5,main], id: 62
11-24 16:42:26.837  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
11-24 16:42:26.837  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-62,5,main], id: 62
11-24 16:42:26.837  5869  5888 D BtGatt.ScanManager: handling starting scan
11-24 16:42:26.837  5615  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-24 16:42:26.837  5615  5615 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-24 16:42:26.837  5615  5615 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-24 16:42:26.837  5615  5615 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
11-24 16:42:26.837  5615  5615 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
,11-24 16:42:26.837  5615  5615 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-24 16:42:26.838  5615  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-24 16:42:26.838  5615  5615 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
,11-24 16:42:26.838  5615  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-24 16:42:26.838  5615  5615 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-24 16:42:26.838  5615  5615 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING] Current thread: Thread[main,5,main], id: 1
11-24 16:42:26.838  5869  5888 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@75cfb1d
11-24 16:42:26.839  5615  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
,11-24 16:42:26.839  5615  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
11-24 16:42:26.839  5615  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-24 16:42:26.840  5615  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-24 16:42:26.840  5615  5663 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
11-24 16:42:26.840  5615  5663 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
11-24 16:42:26.840  5615  5663 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
11-24 16:42:26.840  5615  5663 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,11-24 16:42:26.840  5615  5615 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
,11-24 16:42:26.840  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-24 16:42:26.840  5615  5663 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 16:42:26.840  5615  5663 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,11-24 16:42:26.843  5615  5615 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-24 16:42:26.843  5615  5615 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-24 16:42:26.843  5615  5615 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-24 16:42:26.843  5615  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-24 16:42:26.843  5615  5615 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
11-24 16:42:26.843  5615  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-62,5,main], id: 62
11-24 16:42:26.843  5615  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
11-24 16:42:26.843  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-24 16:42:26.843  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-62,5,main], id: 62
11-24 16:42:26.843  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-62,5,main], id: 62
11-24 16:42:26.843  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-62,5,main], id: 62
11-24 16:42:26.843  5615  5663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,11-24 16:42:26.843  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-62,5,main], id: 62
11-24 16:42:26.844  5615  5663 D BluetoothAdapter: STATE_ON
11-24 16:42:26.844  5869  5908 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
11-24 16:42:26.845  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-24 16:42:26.845  5615  5663 D BluetoothAdapter: STATE_ON
11-24 16:42:26.845  5869  5885 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
11-24 16:42:26.846  5869  5885 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 16:42:26.846  5869  5880 D BtGatt.GattService: stopScan() - queue size =1
11-24 16:42:26.846  5869  5888 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
11-24 16:42:26.846  5869  5897 D BtGatt.GattService: unregisterClient() - clientIf=5
11-24 16:42:26.846  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-24 16:42:26.847  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-62,5,main], id: 62
11-24 16:42:26.847  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,11-24 16:42:26.847  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-62,5,main], id: 62
11-24 16:42:26.847  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-62,5,main], id: 62
11-24 16:42:26.847  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-62,5,main], id: 62
11-24 16:42:26.847  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-62,5,main], id: 62
11-24 16:42:26.847  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-24 16:42:26.847  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-62,5,main], id: 62
11-24 16:42:26.847  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-62,5,main], id: 62
11-24 16:42:26.847  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-62,5,main], id: 62
11-24 16:42:26.847  5615  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-24 16:42:26.847  5615  5663 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-24 16:42:26.848  5615  5663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
11-24 16:42:26.848  5615  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-24 16:42:26.849  5615  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-24 16:42:26.849  5615  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-24 16:42:26.850  5615  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-24 16:42:26.850  5615  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-24 16:42:26.850  5615  5615 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-24 16:42:26.850  5615  5615 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-24 16:42:26.850  5615  5615 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-24 16:42:26.850  5615  5615 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-24 16:42:26.850  5615  5615 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-24 16:42:26.851  5615  5663 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-24 16:42:26.852  5615  5663 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-24 16:42:26.852  5869  5885 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
11-24 16:42:26.852  5615  5663 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skip,ping...
11-24 16:42:26.852  5869  5885 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 16:42:26.852  5615  5663 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-24 16:42:26.852  5615  5663 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 16:42:26.852  5615  5663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-24 16:42:26.853  5615  5663 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5400851 removed from the list
11-24 16:42:26.853  5615  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 16:42:26.853  5615  5663 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e7268b6 removed from the list
11-24 16:42:26.853  5869  5888 D BtGatt.ScanManager: Starting BLE batch scan
11-24 16:42:26.853  5615  5663 D io.jxcore.node.ConnectivityMonitor: stop
11-24 16:42:26.853  5869  5888 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
11-24 16:42:26.853  5615  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-62,5,main], id: 62
11-24 16:42:26.853  5615  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-24 16:42:26.855  5615  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-24 16:42:26.862  5615  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-24 16:42:26.850  5615  5615 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
11-24 16:42:26.862  5615  5615 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-24 16:42:26.862  5615  5615 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
,11-24 16:42:26.862  5615  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-24 16:42:26.862  5615  5615 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-24 16:42:26.862  5615  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-24 16:42:26.862  5615  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-24 16:42:26.862  5615  5615 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-24 16:42:26.862  5615  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 16:42:26.862  5615  5663 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e7268b6 not in the list
11-24 16:42:26.862  5615  5615 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED] Current thread: Thread[main,5,main], id: 1
,11-24 16:42:26.862  5615  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-62,5,main], id: 62
11-24 16:42:26.862  5615  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-24 16:42:26.863  5869  5885 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
11-24 16:42:26.863  5869  5885 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-24 16:42:26.863  5615  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-24 16:42:26.863  5615  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-24 16:42:26.863  5615  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-24 16:42:26.863  5615  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-24 16:42:26.863  5615  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-24 16:42:26.863  5615  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 16:42:26.863  5615  5615 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-24 16:42:26.864  5615  5663 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2f28524 removed from the list
11-24 16:42:26.864  5615  5663 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-24 16:42:26.864  5615  5663 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 16:42:26.864  5615  5663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-24 16:42:26.864  5615  5663 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@56239b7 removed from the list
11-24 16:42:26.864  5615  5663 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-24 16:42:26.864  5615  5663 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e8a7089 added. We now have 3 listener(s)
11-24 16:42:26.864  5615  5615 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-24 16:42:26.865  5615  5615 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-24 16:42:26.865  5615  5615 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-24 16:42:26.865  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-24 16:42:26.865  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-24 16:42:26.866  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-24 16:42:26.866  5615  5663 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-24 16:42:26.866  5615  5663 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@231d88e added. We now have 4 listener(s)
11-24 16:42:26.866  5615  5663 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-24 16:42:26.866  5615  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
11-24 16:42:26.867  5615  5663 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-24 16:42:26.867  5615  5663 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b08a8af added. We now have 4 listener(s)
11-24 16:,42:26.868  5869  5885 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
11-24 16:42:26.868  5869  5885 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 16:42:26.868  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-24 16:42:26.868  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-24 16:42:26.868  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-24 16:42:26.868  5615  5663 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-24 16:42:26.868  5615  5663 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c6f54bc added. We now have 5 listener(s)
11-24 16:42:26.868  5615  5663 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-24 16:42:26.868  5615  5663 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-24 16:42:26.869  5869  5888 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
11-24 16:42:26.869  5615  5663 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-24 16:42:26.869  5615  5663 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
11-24 16:42:26.869  5615  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
11-24 16:42:26.869  5615  5663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-24 16:42:26.869  5615  5663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
11-24 16:42:26.870  5615  5663 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,11-24 16:42:26.872  5869  5885 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,11-24 16:42:26.872  5869  5885 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 16:42:26.873  5869  5885 E BtGatt.ContextMap: Context not found for ID 5
,11-24 16:42:26.873  5615  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-24 16:42:26.873  5615  5663 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,11-24 16:42:26.873  5615  5663 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,11-24 16:42:26.876  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-62,5,main], id: 62
,11-24 16:42:26.876  5615  5663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-24 16:42:26.877  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-24 16:42:26.877  5615  5663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-24 16:42:26.877  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 0
11-24 16:42:26.877  5869  5885 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
11-24 16:42:26.878  5869  5885 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 16:42:26.878  5869  5888 D BtGatt.ScanManager: stopping BLe Batch
,11-24 16:42:26.881  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-62,5,main], id: 62
,11-24 16:42:26.881  5615  5663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
11-24 16:42:26.881  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
11-24 16:42:26.881  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
11-24 16:42:26.881  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
11-24 16:42:26.881  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-62,5,main], id: 62
11-24 16:42:26.882  5615  5663 D BluetoothAdapter: STATE_ON
,11-24 16:42:26.882  5869  5885 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
11-24 16:42:26.882  5869  5885 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 16:42:26.883  5869  5888 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-24 16:42:26.883  5869  5879 D BtGatt.GattService: registerClient() - UUID=84b15728-d97e-4b7d-80d6-0c63576aa6de
,11-24 16:42:26.884  5869  5885 D BtGatt.GattService: onClientRegistered() - UUID=84b15728-d97e-4b7d-80d6-0c63576aa6de, clientIf=5
,11-24 16:42:26.884  5615  5655 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
11-24 16:42:26.884  5869  5897 D BtGatt.GattService: start scan with filters
,11-24 16:42:26.886  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
11-24 16:42:26.886  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-62,5,main], id: 62
11-24 16:42:26.886  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
11-24 16:42:26.886  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-62,5,main], id: 62
11-24 16:42:26.886  5615  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,11-24 16:42:26.886  5615  5615 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
,11-24 16:42:26.887  5615  5615 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-24 16:42:26.887  5615  5615 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
11-24 16:42:26.887  5615  5615 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-24 16:42:26.887  5615  5615 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-24 16:42:26.887  5615  5615 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
11-24 16:42:26.887  5615  5615 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-24 16:42:26.887  5615  5615 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING] Current thread: Thread[main,5,main], id: 1
11-24 16:42:26.887  5869  5885 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,11-24 16:42:26.887  5869  5885 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 16:42:26.887  5615  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-24 16:42:26.887  5615  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-24 16:42:26.888  5869  5888 D BtGatt.ScanManager: handling starting scan
11-24 16:42:26.889  5615  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-24 16:42:26.889  5615  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
11-24 16:42:26.889  5615  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-24 16:42:26.889  5615  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-24 16:42:26.889  5615  5663 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
11-24 16:42:26.889  5615  5663 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
11-24 16:42:26.889  5615  5615 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-24 16:42:26.889  5615  5663 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-24 16:42:26.889  5615  5663 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-24 16:42:26.889  5615  5663 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-24 16:42:26.889  5615  5663 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-24 16:42:26.889  5615  5663 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-24 16:42:26.889  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-24 16:42:26.889  5615  5663 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 16:42:26.889  5615  5663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-24 16:42:26.889  5615  5663 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e8a7089 removed from the list
11-24 16:42:26.889  5615  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 16:42:26.890  5615  5663 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@231d88e removed from the list
11-24 16:42:26.890  5615  5663 D io.jxcore.node.ConnectivityMonitor: stop
11-24 16:42:26.890  5615  5663 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-24 16:42:26.890  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-24 16:42:26.890  5615  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-62,5,main], id: 62
11-24 16:42:26.890  5615  5663 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
11-24 16:42:26,.890  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
11-24 16:42:26.890  5615  5663 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-24 16:42:26.890  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-24 16:42:26.890  5615  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-24 16:42:26.891  5615  5615 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-24 16:42:26.891  5615  5615 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-24 16:42:26.891  5615  5615 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-24 16:42:26.891  5615  5615 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
11-24 16:42:26.892  5615  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-24 16:42:26.892  5615  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-24 16:42:26.892  5615  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
,11-24 16:42:26.892  5615  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,11-24 16:42:26.892  5615  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-24 16:42:26.892  5615  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 16:42:26.892  5615  5663 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@231d88e not in the list
11-24 16:42:26.892  5615  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-24 16:42:26.892  5869  5885 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
11-24 16:42:26.892  5615  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-62,5,main], id: 62
11-24 16:42:26.892  5615  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
11-24 16:42:26.892  5869  5885 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 16:42:26.892  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,11-24 16:42:26.893  5869  5888 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
11-24 16:42:26.893  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-62,5,main], id: 62
11-24 16:42:26.893  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-62,5,main], id: 62
11-24 16:42:26.893  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-62,5,main], id: 62
11-24 16:42:26.893  5615  5663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
11-24 16:42:26.893  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-62,5,main], id: 62
,11-24 16:42:26.894  5615  5663 D BluetoothAdapter: STATE_ON
,11-24 16:42:26.894  5869  5880 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
11-24 16:42:26.895  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-24 16:42:26.896  5615  5663 D BluetoothAdapter: STATE_ON
11-24 16:42:26.896  5869  5879 D BtGatt.GattService: stopScan() - queue size =1
11-24 16:42:26.897  5869  5885 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
11-24 16:42:26.898  5869  5885 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 16:42:26.898  5869  5888 D BtGatt.ScanManager: Starting BLE batch scan
11-24 16:42:26.898  5869  5888 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
11-24 16:42:26.898  5869  5897 D BtGatt.GattService: unregisterClient() - clientIf=5
11-24 16:42:26.898  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-24 16:42:26.898  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-62,5,main], id: 62
11-24 16:42:26.898  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
11-24 16:42:26.898  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-62,5,main], id: 62
11-24 16:42:26.898  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-62,5,main], id: 62
11-24 16:42:26.898  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-62,5,main], id: 62
11-24 16:42:26.898  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-62,5,main], id: 62
11-24 16:42:26.899  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-24 16:42:26.899  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-62,5,main], id: 62
11-24 16:42:26.899  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-62,5,main], id: 62
11-24 16:42:26.899  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-62,5,main], id: 62
11-24 16:42:26.899  5615  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-24 16:42:26.899  5615  5663 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-24 16:42:26.899  5615  5663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
11-24 16:42:26.900  5615  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
,11-24 16:42:26.902  5615  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
,11-24 16:42:26.902  5615  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-24 16:42:26.902  5615  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-24 16:42:26.902  5615  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-24 16:42:26.902  5615  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-24 16:42:26.902  5615  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-24 16:42:26.902  5615  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 16:42:26.903  5615  5663 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c6f54bc removed from the list
,11-24 16:42:26.903  5615  5615 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,11-24 16:42:26.903  5615  5663 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-24 16:42:26.903  5615  5663 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 16:42:26.903  5615  5615 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-24 16:42:26.903  5615  5663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-24 16:42:26.903  5615  5663 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b08a8af removed from the list
11-24 16:42:26.903  5615  5615 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
,11-24 16:42:26.903  5615  5615 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-24 16:42:26.903  5615  5615 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-24 16:42:26.903  5615  5615 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
11-24 16:42:26.903  5615  5615 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-24 16:42:26.903  5615  5615 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-24 16:42:26.903  5615  5615 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-24 16:42:26.903  5615  5663 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,11-24 16:42:26.903  5615  5615 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-24 16:42:26.903  5615  5663 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@242a7c1 added. We now have 3 listener(s)
11-24 16:42:26.903  5615  5615 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED] Current thread: Thread[main,5,main], id: 1
11-24 16:42:26.903  5615  5615 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-24 16:42:26.904  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-24 16:42:26.904  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-24 16:42:26.904  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,11-24 16:42:26.904  5615  5615 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-24 16:42:26.904  5615  5615 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-24 16:42:26.904  5615  5663 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-24 16:42:26.904  5869  5885 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
11-24 16:42:26.904  5615  5615 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-24 16:42:26.904  5615  5663 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5c46b66 added. We now have 4 listener(s)
11-24 16:42:26.904  5869  5885 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 16:42:26.904  5615  5663 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-24 16:42:26.905  5615  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
11-24 16:42:26.905  5615  5663 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-24 16:42:26.905  5615  5663 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@43efea7 added. We now have 4 listener(s)
11-24 16:42:26.906  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-24 16:42:26.906  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-24 16:42:26.906  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-24 16:42:26.906  5615  5663 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,11-24 16:42:26.906  5615  5663 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c937f54 added. We now have 5 listener(s)
11-24 16:42:26.906  5615  5663 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-24 16:42:26.906  5615  5663 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-24 16:42:26.907  5615  5663 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
11-24 16:42:26.907  5615  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
11-24 16:42:26.907  5615  5663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-24 16:42:26.907  5615  5663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
,11-24 16:42:26.907  5615  5663 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
11-24 16:42:26.908  5869  5885 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
11-24 16:42:26.909  5869  5885 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 16:42:26.909  5615  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-24 16:42:26.909  5615  5663 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-24 16:42:26.909  5615  5663 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
11-24 16:42:26.909  5869  5888 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-24 16:42:26.912  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-62,5,main], id: 62
,11-24 16:42:26.912  5615  5663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-24 16:42:26.913  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-24 16:42:26.913  5615  5663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-24 16:42:26.913  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 0
,11-24 16:42:26.913  5869  5885 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-24 16:42:26.913  5869  5885 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 16:42:26.913  5869  5885 E BtGatt.ContextMap: Context not found for ID 5
,11-24 16:42:26.915  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-62,5,main], id: 62
11-24 16:42:26.915  5615  5663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
11-24 16:42:26.915  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
11-24 16:42:26.915  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
11-24 16:42:26.915  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
11-24 16:42:26.915  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-62,5,main], id: 62
,11-24 16:42:26.915  5615  5663 D BluetoothAdapter: STATE_ON
,11-24 16:42:26.919  5869  5885 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
11-24 16:42:26.919  5869  5885 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 16:42:26.919  5869  5888 D BtGatt.ScanManager: stopping BLe Batch
,11-24 16:42:26.920  5869  5908 D BtGatt.GattService: registerClient() - UUID=7d2d11ee-25ad-4cb4-a1d8-72eb8af1c804
,11-24 16:42:26.920  5869  5885 D BtGatt.GattService: onClientRegistered() - UUID=7d2d11ee-25ad-4cb4-a1d8-72eb8af1c804, clientIf=5
11-24 16:42:26.921  5615  5655 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,11-24 16:42:26.923  5869  5879 D BtGatt.GattService: start scan with filters
,11-24 16:42:26.924  5869  5885 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
11-24 16:42:26.924  5869  5885 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 16:42:26.924  5869  5888 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
11-24 16:42:26.925  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
11-24 16:42:26.925  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-62,5,main], id: 62
11-24 16:42:26.925  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
11-24 16:42:26.925  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-62,5,main], id: 62
11-24 16:42:26.925  5615  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-24 16:42:26.925  5615  5615 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-24 16:42:26.925  5615  5615 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-24 16:42:26.925  5615  5615 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
11-24 16:42:26.925  5615  5615 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-24 16:42:26.925  5615  5615 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-24 16:42:26.925  5615  5615 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
11-24 16:42:26.925  5615  5615 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
,11-24 16:42:26.926  5615  5615 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING] Current thread: Thread[main,5,main], id: 1
11-24 16:42:26.926  5615  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-24 16:42:26.926  5615  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
,11-24 16:42:26.928  5615  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
,11-24 16:42:26.928  5615  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
11-24 16:42:26.928  5615  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-24 16:42:26.928  5869  5885 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-24 16:42:26.928  5869  5885 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 16:42:26.928  5615  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-24 16:42:26.928  5615  5615 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
,11-24 16:42:26.929  5869  5888 D BtGatt.ScanManager: handling starting scan
,11-24 16:42:26.933  5869  5885 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,11-24 16:42:26.933  5869  5885 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 16:42:26.934  5869  5888 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
11-24 16:42:26.934  5615  5615 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-24 16:42:26.934  5615  5615 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-24 16:42:26.934  5615  5615 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-24 16:42:26.934  5615  5615 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
11-24 16:42:26.934  5615  5663 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-24 16:42:26.934  5615  5663 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-24 16:42:26.935  5615  5663 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,11-24 16:42:26.935  5615  5663 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-24 16:42:26.935  5615  5663 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-24 16:42:26.935  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-24 16:42:26.935  5615  5663 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 16:42:26.935  5615  5663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-24 16:42:26.935  5615  5663 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@242a7c1 removed from the list
11-24 16:42:26.935  5615  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 16:42:26.935  5615  5663 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5c46b66 removed from the list
11-24 16:42:26.935  5615  5663 D io.jxcore.node.ConnectivityMonitor: stop
11-24 16:42:26.935  5615  5663 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,11-24 16:42:26.935  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-24 16:42:26.935  5615  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-62,5,main], id: 62
11-24 16:42:26.935  5615  5663 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
11-24 16:42:26.935  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
11-24 16:42:26.936  5615  5663 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-24 16:42:26.936  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-24 16:42:26.936  5615  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
,11-24 16:42:26.937  5869  5885 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
11-24 16:42:26.938  5869  5885 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 16:42:26.938  5869  5888 D BtGatt.ScanManager: Starting BLE batch scan
11-24 16:42:26.938  5869  5888 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
11-24 16:42:26.938  5615  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-24 16:42:26.938  5615  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-24 16:42:26.938  5615  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-24 16:42:26.938  5615  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-24 16:42:26.938  5615  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-24 16:42:26.938  5615  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 16:42:26.938  5615  5663 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5c46b66 not in the list
11-24 16:42:26.938  5615  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,11-24 16:42:26.938  5615  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-62,5,main], id: 62
11-24 16:42:26.938  5615  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
11-24 16:42:26.938  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-24 16:42:26.938  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-62,5,main], id: 62
11-24 16:42:26.939  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-62,5,main], id: 62
11-24 16:42:26.939  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-62,5,main], id: 62
11-24 16:42:26.939  5615  5663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
11-24 16:42:26.939  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-62,5,main], id: 62
11-24 16:42:26.939  5615  5663 D BluetoothAdapter: STATE_ON
,11-24 16:42:26.940  5869  5897 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
11-24 16:42:26.940  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-24 16:42:26.940  5615  5663 D BluetoothAdapter: STATE_ON
,11-24 16:42:26.941  5869  5880 D BtGatt.GattService: stopScan() - queue size =1
,11-24 16:42:26.941  5869  5897 D BtGatt.GattService: unregisterClient() - clientIf=5
11-24 16:42:26.941  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-24 16:42:26.941  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-62,5,main], id: 62
11-24 16:42:26.942  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
11-24 16:42:26.942  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-62,5,main], id: 62
,11-24 16:42:26.942  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-62,5,main], id: 62
11-24 16:42:26.942  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-62,5,main], id: 62
11-24 16:42:26.942  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-62,5,main], id: 62
,11-24 16:42:26.942  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-24 16:42:26.942  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-62,5,main], id: 62
11-24 16:42:26.942  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-62,5,main], id: 62
11-24 16:42:26.942  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-62,5,main], id: 62
11-24 16:42:26.942  5615  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-24 16:42:26.943  5615  5663 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-24 16:42:26.943  5615  5663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
11-24 16:42:26.943  5615  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
,11-24 16:42:26.944  5615  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-24 16:42:26.944  5615  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-24 16:42:26.944  5615  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-24 16:42:26.944  5615  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-24 16:42:26.944  5615  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,11-24 16:42:26.944  5615  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-24 16:42:26.944  5615  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 16:42:26.944  5615  5663 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c937f54 removed from the list
11-24 16:42:26.944  5615  5615 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,11-24 16:42:26.944  5615  5663 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-24 16:42:26.944  5615  5615 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-24 16:42:26.944  5615  5663 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,11-24 16:42:26.944  5615  5615 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-24 16:42:26.944  5615  5663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-24 16:42:26.944  5615  5615 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-24 16:42:26.944  5615  5663 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@43efea7 removed from the list
11-24 16:42:26.945  5615  5615 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-24 16:42:26.945  5615  5615 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
,11-24 16:42:26.945  5615  5615 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
,11-24 16:42:26.945  5615  5615 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-24 16:42:26.945  5615  5615 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-24 16:42:26.945  5615  5615 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-24 16:42:26.945  5615  5663 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-24 16:42:26.945  5615  5615 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED] Current thread: Thread[main,5,main], id: 1
11-24 16:42:26.945  5615  5663 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8738df9 added. We now have 3 listener(s)
11-24 16:42:26.945  5615  5615 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-24 16:42:26.946  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
,11-24 16:42:26.946  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-24 16:42:26.946  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-24 16:42:26.946  5615  5663 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-24 16:42:26.947  5615  5663 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@60b813e added. We now have 4 listener(s)
11-24 16:42:26.947  5615  5663 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-24 16:42:26.947  5615  5615 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-24 16:42:26.947  5615  5615 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-24 16:42:26.947  5615  5615 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-24 16:42:26.947  5615  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
11-24 16:42:26.947  5615  5663 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,11-24 16:42:26.948  5615  5663 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@83b1b9f added. We now have 4 listener(s)
11-24 16:42:26.948  5869  5885 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
11-24 16:42:26.948  5869  5885 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 16:42:26.948  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-24 16:42:26.948  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-24 16:42:26.948  5615  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-24 16:42:26.949  5615  5663 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-24 16:42:26.949  5615  5663 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f8f64ec added. We now have 5 listener(s)
11-24 16:42:26.949  5615  5663 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-24 16:42:26.949  5615  5663 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-24 16:42:26.949  5615  5663 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-24 16:42:26.949  5615  5663 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-24 16:42:26.949  5615  5663 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-24 16:42:26.949  5615  5663 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 16:42:26.949  5615  5663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-24 16:42:26.949  5615  5663 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8738df9 removed from the list
11-24 16:42:26.949  5615  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 16:42:26.949  5615  5663 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@60b813e removed from the list
11-24 16:42:26.949  5615  5663 D io.jxcore.node.ConnectivityMonitor: stop
11-24 16:42:26.949  5615  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-62,5,main], id: 62
,11-24 16:42:26.949  5615  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-24 16:42:26.952  5869  5885 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,11-24 16:42:26.952  5869  5885 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 16:42:26.952  5615  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-24 16:42:26.952  5615  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-24 16:42:26.952  5615  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-24 16:42:26.952  5615  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-24 16:42:26.952  5615  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-24 16:42:26.952  5615  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-24 16:42:26.952  5615  5663 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@60b813e not in the list
11-24 16:42:26.952  5615  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-62,5,main], id: 62
11-24 16:42:26.952  5615  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-24 16:42:26.953  5869  5888 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-24 16:42:26.953  5615  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-24 16:42:26.953  5615  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-24 16:42:26.954  5615  5663 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-24 16:42:26.954  5615  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-24 16:42:26.954  5615  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-24 16:42:26.954  5615  5663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 16:42:26.954  5615  5663 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f8f64ec removed from the list
11-24 16:42:26.954  5615  5663 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,11-24 16:42:26.954  5615  5663 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 16:42:26.954  5615  5663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-24 16:42:26.954  5615  5663 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@83b1b9f removed from the list
11-24 16:42:26.954  5615  5663 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
11-24 16:42:26.954  5615  5663 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
11-24 16:42:26.955  5615  5663 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
11-24 16:42:26.955  5615  5663 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-24 16:42:26.955  5615  5663 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
11-24 16:42:26.955  5615  5663 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
11-24 16:42:26.956  5869  5885 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,11-24 16:42:26.956  5869  5885 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 16:42:26.957  5869  5885 E BtGatt.ContextMap: Context not found for ID 5
,11-24 16:42:26.961  5869  5885 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
,11-24 16:42:26.961  5869  5885 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 16:42:26.961  5869  5888 D BtGatt.ScanManager: stopping BLe Batch
,11-24 16:42:26.965  5869  5885 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,11-24 16:42:26.965  5869  5885 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 16:42:26.965  5869  5888 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-24 16:42:26.969  5869  5885 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,11-24 16:42:26.969  5869  5885 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-24 16:42:26.983   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 16:42:27.190  5922  5922 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,11-24 16:42:27.213  5922  5922 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,11-24 16:42:27.214  5922  5922 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,11-24 16:42:27.218   927  2910 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
11-24 16:42:27.218   927  2910 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
11-24 16:42:27.219   927  2912 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,11-24 16:42:27.229   927  2910 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-24 16:42:27.237   506   918 D CommandListener: Setting iface cfg
,11-24 16:42:27.240   927  2910 D WifiStateMachine: Start Dhcp Watchdog 2
,11-24 16:42:27.245   927  5927 D DhcpClient: Receive thread started
,11-24 16:42:27.248   927  2912 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-24 16:42:27.248   927  2912 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
11-24 16:42:27.248   927  2910 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,11-24 16:42:27.328   927  2910 E native  : do suspend false
,11-24 16:42:27.338   927  5926 D DhcpClient: Broadcasting DHCPDISCOVER
,11-24 16:42:27.355   927  5927 D DhcpClient: Received packet: 60:83:34:25:d7:70 OFFER, ip /192.168.1.109, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172673, domain null
,11-24 16:42:27.355   927  5926 D DhcpClient: Got pending lease: IP address 192.168.1.109/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172673 seconds
,11-24 16:42:27.358   927  5926 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.109 serverid=192.168.1.1
,11-24 16:42:27.363  5615  5615 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-24 16:42:27.372   927  5927 D DhcpClient: Received packet: 60:83:34:25:d7:70 ACK: your new IP /192.168.1.109, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,11-24 16:42:27.373   927  5926 D DhcpClient: Confirmed lease: IP address 192.168.1.109/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,11-24 16:42:27.377   506   918 D CommandListener: Setting iface cfg
,11-24 16:42:27.381   927  2910 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,11-24 16:42:27.386   927  5926 D DhcpClient: Scheduling renewal in 86399s
,11-24 16:42:27.398   927  2910 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,11-24 16:42:27.399   927  2910 D WifiConfigStore: No blacklist allowed without epno enabled
11-24 16:42:27.400   927  2912 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
11-24 16:42:27.402   927  2912 D ConnectivityService: Adding iface wlan0 to network 101
11-24 16:42:27.404  5615  5615 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
11-24 16:42:27.410   927  2910 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,11-24 16:42:27.445  5615  5615 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-24 16:42:27.447   927  2912 E ConnectivityService: Unexpected mtu value: 0, wlan0
11-24 16:42:27.447   927  2912 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
,11-24 16:42:27.449   927  2912 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,11-24 16:42:27.451   927  2912 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
11-24 16:42:27.455   927  2912 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,11-24 16:42:27.463   927  2912 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-24 16:42:27.468   927  2912 D ConnectivityService: scheduleUnvalidatedPrompt 101
,11-24 16:42:27.468   927  2912 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
11-24 16:42:27.468   927  2912 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
11-24 16:42:27.468   927  2912 D ConnectivityService:    accepting network in place of null
11-24 16:42:27.469   927  2910 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
11-24 16:42:27.469   927  2910 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,11-24 16:42:27.469   927  2912 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d770/64,192.168.1.109/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -50]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,11-24 16:42:27.482   927  5925 D NetlinkSocketObserver: NeighborEvent{elapsedMs=168043, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,11-24 16:42:27.492   506   918 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-24 16:42:27.515   506   918 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-24 16:42:27.519   927  2912 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,11-24 16:42:27.519  3708  3826 W QCNEJ   : |CORE| network available: 101
,11-24 16:42:27.519   927  2912 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
11-24 16:42:27.520   927  2912 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
11-24 16:42:27.521   927   944 D Tethering: MasterInitialState.processMessage what=3
,11-24 16:42:27.521  3708  3826 W QCNEJ   : |CORE| onAvailable: bind the process to WIFI
11-24 16:42:27.522  3708  3826 W QCNEJ   : |CORE| newLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d770/64,192.168.1.109/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}
11-24 16:42:27.522  3708  3826 W QCNEJ   : |CORE| curLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d770/64,192.168.1.109/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,11-24 16:42:27.535  5011  5035 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
,11-24 16:42:27.535  5011  5035 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
11-24 16:42:27.535  5011  5035 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,1,0,0
11-24 16:42:27.536  5011  5035 E SarControlService: no key has been found,reset the power
11-24 16:42:27.536  5011  5048 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
11-24 16:42:27.536  5011  5048 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
11-24 16:42:27.536  5011  5048 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
11-24 16:42:27.536  5036  5036 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
11-24 16:42:27.537  5036  5036 D QcrilMsgTunnelSocket: [1004] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
11-24 16:42:27.537  5011  5048 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
11-24 16:42:27.537  5011  5048 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
11-24 16:42:27.537  5011  5048 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
,11-24 16:42:27.540  3938  3938 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
,11-24 16:42:27.539  5036  5036 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
11-24 16:42:27.541  5036  5036 D QcrilMsgTunnelSocket: [1005] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
,11-24 16:42:27.545  3688  3688 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,11-24 16:42:27.546  5036  5050 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@864bbcf HexData = [00000000ec03000000000000ffffffff]
11-24 16:42:27.546  5036  5050 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-24 16:42:27.546  5036  5050 D QcrilMsgTunnelSocket: [1004] < OEM_HOOK_RAW [null]
,11-24 16:42:27.549  5036  5050 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@864bbcf HexData = [00000000ed03000000000000ffffffff]
,11-24 16:42:27.549  5036  5050 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-24 16:42:27.549  5036  5050 D QcrilMsgTunnelSocket: [1005] < OEM_HOOK_RAW [null]
11-24 16:42:27.550  5036  5036 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
11-24 16:42:27.550  5011  5021 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
11-24 16:42:27.551  3688  3688 D SystemUpdateService: onCreate
11-24 16:42:27.551  5036  5036 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
,11-24 16:42:27.553  5011  5022 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
,11-24 16:42:27.556  3688  3688 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,11-24 16:42:27.564   927  5924 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=172.217.22.110,2a00:1450:4001:81d::200e
,11-24 16:42:27.572  3688  3688 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,11-24 16:42:27.576  3688  5364 I iu.UploadsManager: num queued entries: 0
,11-24 16:42:27.577  3688  5364 I iu.UploadsManager: num updated entries: 0
,11-24 16:42:27.577  3688  5364 I iu.SyncManager: NEXT; no task
,11-24 16:42:27.585  3688  5937 I SystemUpdateService: active receiver: enabled
,11-24 16:42:27.587  3688  3688 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,11-24 16:42:27.588  3688  3688 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,11-24 16:42:27.590  5752  5752 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,11-24 16:42:27.594  5752  5752 D SprintDMHelper: simOperator: 
,11-24 16:42:27.594  5752  5752 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,11-24 16:42:27.621  3688  5937 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,11-24 16:42:27.624   927  5924 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Thu, 24 Nov 2016 15:42:27 GMT], X-Android-Received-Millis=[1480002147623], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1480002147599]}
,11-24 16:42:27.624   927  2912 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,11-24 16:42:27.624   927  2912 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation  passed
,11-24 16:42:27.624   927  2912 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
11-24 16:42:27.626   927  2912 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,11-24 16:42:27.638  3688  5937 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,11-24 16:42:27.638  3688  5937 I SystemUpdateService: now status is 0 (complete)
11-24 16:42:27.638  3688  5937 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
11-24 16:42:27.638  3688  5937 I SystemUpdateService: file has been verified
11-24 16:42:27.638  3688  5937 I SystemUpdateService: OTA package size = 21989297
,11-24 16:42:27.644  3688  5937 I SystemUpdateService: showing system update notification
,11-24 16:42:27.656  3526  5948 I VacuumService: Vacuum at: now=1480002147656 tag=VacuumService
,11-24 16:42:27.661   927   927 V NotificationService: pkg=com.google.android.gms canInterrupt=false intercept=true
,11-24 16:42:27.663  3688  3688 D SystemUpdateService: onDestroy
,11-24 16:42:27.681  3526  5951 D GetConfigurationSnapshotOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,11-24 16:42:27.708  4977  5943 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,11-24 16:42:27.716  3526  5949 I PhenotypeFlagCommitter: Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,11-24 16:42:27.718  3526  5949 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,11-24 16:42:27.740  3526  5949 W Uploader:  no longer exists, so no auth token.
,11-24 16:42:27.746  3526  5951 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,11-24 16:42:27.983   535   535 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,11-24 16:42:28.066  3526  5955 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,11-24 16:42:28.292  3526  5951 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader,
,11-24 16:42:28.520   927  2912 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,11-24 16:42:28.555  3526  5949 W Uploader:  no longer exists, so no auth token.
,11-24 16:42:28.570  3526  5955 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,11-24 16:42:28.666  3526  5951 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,11-24 16:42:28.750  3526  5955 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,11-24 16:42:29.086  5615  5960 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 178, name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
11-24 16:42:29.086  5615  5960 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-24 16:42:29.884  5615  5960 W !!      : call onHalfStreamCopied
,11-24 16:42:29.884  5615  5960 I testCopyDataAndClose: closing input stream
,11-24 16:42:30.272   927  2912 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-24 16:42:30.655  5615  5960 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 178, thread name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
11-24 16:42:30.655  5615  5960 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
11-24 16:42:30.655  5615  5960 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
11-24 16:42:30.655  5615  5960 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-24 16:42:30.655  5615  5960 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
11-24 16:42:30.655  5615  5960 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
11-24 16:42:30.655  5615  5960 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
11-24 16:42:30.655  5615  5960 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
11-24 16:42:30.655  5615  5960 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
,11-24 16:42:30.655  5615  5960 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 178, name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
11-24 16:42:30.655  5615  5960 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 20971520 and the total number of bytes written 20971520
,11-24 16:42:35.217  5615  5962 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 181, name: My test thread name). Connection data: Peer properties: [null null].
11-24 16:42:35.217  5615  5962 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-24 16:42:35.474   927  2912 D ConnectivityService: handlePromptUnvalidated 101
,11-24 16:42:37.217  5615  5663 I io.jxcore.node.StreamCopyingThread: close: Thread ID: 181. Connection data: Peer properties: [null null].
11-24 16:42:37.217  5615  5663 I io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-24 16:42:37.217  5615  5663 D io.jxcore.node.StreamCopyingThread: closeStreams: Streams closed (thread ID: 181, name: My test thread name)
,11-24 16:42:37.243  5615  5962 D io.jxcore.node.StreamCopyingThread: number of bytes read = 0
11-24 16:42:37.243  5615  5962 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 181, name: My test thread name). Connection data: Peer properties: [null null].
11-24 16:42:37.243  5615  5962 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 154 and the total number of bytes written 154
,11-24 16:42:37.353  5615  5963 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 183, name: testCopyBigData thread). Connection data: Peer properties: [null null].
11-24 16:42:37.353  5615  5963 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-24 16:42:38.614   927  2910 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 10, 11 -> obsolete
,11-24 16:42:38.964  5615  5963 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 183, thread name: testCopyBigData thread). Connection data: Peer properties: [null null].
11-24 16:42:38.964  5615  5963 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-24 16:42:38.964  5615  5963 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
11-24 16:42:38.964  5615  5963 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-24 16:42:38.964  5615  5963 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
11-24 16:42:38.964  5615  5963 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
,11-24 16:42:38.964  5615  5963 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
11-24 16:42:38.964  5615  5963 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
11-24 16:42:38.964  5615  5963 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
,11-24 16:42:38.964  5615  5963 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 183, name: testCopyBigData thread). Connection data: Peer properties: [null null].
11-24 16:42:38.964  5615  5963 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 20971520 and the total number of bytes written 20971520
,11-24 16:42:43.370  5615  5964 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 185, name: My test thread name). Connection data: Peer properties: [null null].
11-24 16:42:43.370  5615  5964 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-24 16:42:43.370  5615  5964 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 185, thread name: My test thread name). Connection data: Peer properties: [null null].
11-24 16:42:43.370  5615  5964 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
11-24 16:42:43.370  5615  5964 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
11-24 16:42:43.370  5615  5964 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
11-24 16:42:43.370  5615  5964 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
,11-24 16:42:43.371  5615  5964 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
11-24 16:42:43.371  5615  5964 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
11-24 16:42:43.371  5615  5964 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
11-24 16:42:43.371  5615  5964 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
,11-24 16:42:43.371  5615  5964 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 185, name: My test thread name). Connection data: Peer properties: [null null].
11-24 16:42:43.371  5615  5964 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 22
11-24 16:42:43.373  5615  5663 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,11-24 16:42:43.376  5615  5965 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 189, name: My test thread name). Connection data: Peer properties: [null null].
11-24 16:42:43.376  5615  5965 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-24 16:42:43.376  5615  5965 E io.jxcore.node.StreamCopyingThread: Failed to write to the output stream (thread ID: 189, thread name: My test thread name): Test exception.
11-24 16:42:43.377  5615  5965 D io.jxcore.node.StreamCopyingThread: onStreamCopyError (ID: 189, name: My test thread name). Connection data: Peer properties: [null null].
11-24 16:42:43.377  5615  5965 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
11-24 16:42:43.377  5615  5965 D io.jxcore.node.StreamCopyingThread: number of bytes read = 22
11-24 16:42:43.377  5615  5965 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 189, name: My test thread name). Connection data: Peer properties: [null null].
11-24 16:42:43.377  5615  5965 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
,11-24 16:42:43.381  5615  5663 I jxcore-log: 2016-11-24 15:42:43 - DEBUG UnitTest_app: 'Total number of executed tests:  82'
11-24 16:42:43.381  5615  5663 I jxcore-log: 
,11-24 16:42:43.381  5615  5663 I jxcore-log: 2016-11-24 15:42:43 - DEBUG UnitTest_app: 'Number of passed tests:  82'
11-24 16:42:43.381  5615  5663 I jxcore-log: 
,11-24 16:42:43.381  5615  5663 I jxcore-log: 2016-11-24 15:42:43 - DEBUG UnitTest_app: 'Number of failed tests:  0'
11-24 16:42:43.381  5615  5663 I jxcore-log: 
11-24 16:42:43.382  5615  5663 I jxcore-log: 2016-11-24 15:42:43 - DEBUG UnitTest_app: 'Number of ignored tests:  0'
11-24 16:42:43.382  5615  5663 I jxcore-log: 
,11-24 16:42:43.382  5615  5663 I jxcore-log: 2016-11-24 15:42:43 - DEBUG UnitTest_app: 'Total duration:  92156'
11-24 16:42:43.382  5615  5663 I jxcore-log: 
11-24 16:42:43.384  5615  5663 I jxcore-log: 2016-11-24 15:42:43 - DEBUG UnitTest_app: 'Unit Test app is loaded'
11-24 16:42:43.384  5615  5663 I jxcore-log: 
,11-24 16:42:43.388  5615  5663 I jxcore-log: 2016-11-24 15:42:43 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
11-24 16:42:43.388  5615  5663 I jxcore-log: 
11-24 16:42:43.389  5615  5663 I jxcore-log: 2016-11-24 15:42:43 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
11-24 16:42:43.389  5615  5663 I jxcore-log: 
11-24 16:42:43.390  5615  5663 I jxcore-log: 2016-11-24 15:42:43 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
11-24 16:42:43.390  5615  5663 I jxcore-log: 
11-24 16:42:43.390  5615  5663 I jxcore-log: 2016-11-24 15:42:43 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH"})'
11-24 16:42:43.390  5615  5663 I jxcore-log: 
11-24 16:42:43.391  5615  5663 I jxcore-log: 2016-11-24 15:42:43 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-24 16:42:43.391  5615  5663 I jxcore-log: 
11-24 16:42:43.391  5615  5663 I jxcore-log: 2016-11-24 15:42:43 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-24 16:42:43.391  5615  5663 I jxcore-log: 
11-24 16:42:43.391  5615  5663 I jxcore-log: 2016-11-24 15:42:43 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-24 16:42:43.391  5615  5663 I jxcore-log: 
11-24 16:42:43.391  5615  5663 I jxcore-log: 2016-11-24 15:42:43 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
11-24 16:42:43.391  5615  5663 I jxcore-log: 
11-24 16:42:43.392  5615  5663 I jxcore-log: 2016-11-24 15:42:43 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
11-24 16:42:43.392  5615  5663 I jxcore-log: 
,11-24 16:42:43.392  5615  5663 I jxcore-log: 2016-11-24 15:42:43 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
11-24 16:42:43.392  5615  5663 I jxcore-log: 
11-24 16:42:43.392  5615  5663 I jxcore-log: 2016-11-24 15:42:43 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH"})'
11-24 16:42:43.392  5615  5663 I jxcore-log: 
11-24 16:42:43.393  5615  5663 I jxcore-log: 2016-11-24 15:42:43 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-24 16:42:43.393  5615  5663 I jxcore-log: 
11-24 16:42:43.393  5615  5663 I jxcore-log: 2016-11-24 15:42:43 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-24 16:42:43.393  5615  5663 I jxcore-log: 
,11-24 16:42:43.393  5615  5663 I jxcore-log: 2016-11-24 15:42:43 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-24 16:42:43.393  5615  5663 I jxcore-log: 
11-24 16:42:43.393  5615  5663 I jxcore-log: 2016-11-24 15:42:43 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-24 16:42:43.393  5615  5663 I jxcore-log: 
11-24 16:42:43.393  5615  5663 I jxcore-log: 2016-11-24 15:42:43 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-24 16:42:43.393  5615  5663 I jxcore-log: 
11-24 16:42:43.394  5615  5663 I jxcore-log: 2016-11-24 15:42:43 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
11-24 16:42:43.394  5615  5663 I jxcore-log: 
,11-24 16:42:43.394  5615  5663 I jxcore-log: 2016-11-24 15:42:43 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
11-24 16:42:43.394  5615  5663 I jxcore-log: 
11-24 16:42:43.394  5615  5663 I jxcore-log: 2016-11-24 15:42:43 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
11-24 16:42:43.394  5615  5663 I jxcore-log: 
11-24 16:42:43.395  5615  5663 I jxcore-log: 2016-11-24 15:42:43 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
11-24 16:42:43.395  5615  5663 I jxcore-log: 
11-24 16:42:43.395  5615  5663 I jxcore-log: 2016-11-24 15:42:43 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
11-24 16:42:43.395  5615  5663 I jxcore-log: 
11-24 16:42:43.395  5615  5663 I jxcore-log: 2016-11-24 15:42:43 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
11-24 16:42:43.395  5615  5663 I jxcore-log: 
11-24 16:42:43.396  5615  5663 I jxcore-log: 2016-11-24 15:42:43 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
11-24 16:42:43.396  5615  5663 I jxcore-log: 
11-24 16:42:43.396  5615  5663 I jxcore-log: 2016-11-24 15:42:43 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
11-24 16:42:43.396  5615  5663 I jxcore-log: 
,11-24 16:42:43.398  5615  5663 I jxcore-log: 2016-11-24 15:42:43 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
11-24 16:42:43.398  5615  5663 I jxcore-log: 
11-24 16:42:43.398  5615  5663 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-24 16:42:43.398  5615  5663 D io.jxcore.node.StartStopOperationHandler: Operation timeout, state error: null
,11-24 16:42:43.398  5615  5663 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-24 16:42:43.398  5615  5663 D io.jxcore.node.StartStopOperationHandler: Operation timeout, state error: Discovery manager not started
11-24 16:42:43.399  5615  5663 I jxcore-log: 2016-11-24 15:42:43 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-24 16:42:43.399  5615  5663 I jxcore-log: 
11-24 16:42:43.399  5615  5663 I jxcore-log: 2016-11-24 15:42:43 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-24 16:42:43.399  5615  5663 I jxcore-log: 
,11-24 16:42:43.399  5615  5663 I jxcore-log: 2016-11-24 15:42:43 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-24 16:42:43.399  5615  5663 I jxcore-log: 
11-24 16:42:43.399  5615  5663 I jxcore-log: 2016-11-24 15:42:43 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-24 16:42:43.399  5615  5663 I jxcore-log: 
11-24 16:42:43.400  5615  5663 I jxcore-log: 2016-11-24 15:42:43 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-24 16:42:43.400  5615  5663 I jxcore-log: 
11-24 16:42:43.400  5615  5663 I jxcore-log: 2016-11-24 15:42:43 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-24 16:42:43.400  5615  5663 I jxcore-log: 
,11-24 16:42:43.405  5615  5663 I jxcore-log: 2016-11-24 15:42:43 - DEBUG UnitTest_app: 'My device name is: Huawei-Nexus 6P'
11-24 16:42:43.405  5615  5663 I jxcore-log: 
11-24 16:42:43.405  5615  5663 I jxcore-log: 2016-11-24 15:42:43 - WARN testUtils: 'myNameCallback not set!'
11-24 16:42:43.405  5615  5663 I jxcore-log: 
,11-24 16:42:43.407  5615  5615 D SystemWebChromeClient: file:///android_asset/www/js/thali_main.js: Line 68 : UIApp is all set and ready!
11-24 16:42:43.407  5615  5615 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
,11-24 16:42:45.466  5615  5663 I jxcore-log: 2016-11-24 15:42:45 - INFO runTests: 'Starting tests. Network type: WIFI. Platform: android'
11-24 16:42:45.466  5615  5663 I jxcore-log: 
,11-24 16:42:45.467  5615  5663 I jxcore-log: 2016-11-24 15:42:45 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js'
11-24 16:42:45.467  5615  5663 I jxcore-log: 
,11-24 16:42:45.603   927  5925 D NetlinkSocketObserver: NeighborEvent{elapsedMs=186163, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,11-24 16:42:45.816  5615  5663 I jxcore-log: 2016-11-24 15:42:45 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js'
11-24 16:42:45.816  5615  5663 I jxcore-log: 
,11-24 16:42:45.828  5615  5663 I jxcore-log: 2016-11-24 15:42:45 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManager.js'
11-24 16:42:45.828  5615  5663 I jxcore-log: 
,11-24 16:42:46.941  5615  5663 I jxcore-log: 2016-11-24 15:42:46 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js'
11-24 16:42:46.941  5615  5663 I jxcore-log: 
,11-24 16:42:47.133  5615  5663 I jxcore-log: 2016-11-24 15:42:47 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js'
11-24 16:42:47.133  5615  5663 I jxcore-log: 
,11-24 16:42:47.139  5615  5663 I jxcore-log: 2016-11-24 15:42:47 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testNativeMethod.js'
11-24 16:42:47.139  5615  5663 I jxcore-log: 
,11-24 16:42:47.144  5615  5663 I jxcore-log: 2016-11-24 15:42:47 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPouchDBCheckpointPlugin.js'
11-24 16:42:47.144  5615  5663 I jxcore-log: 
,11-24 16:42:47.626  5615  5663 I jxcore-log: 2016-11-24 15:42:47 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPouchDBGenerator.js'
11-24 16:42:47.626  5615  5663 I jxcore-log: 
,11-24 16:42:47.671  5615  5663 I jxcore-log: 2016-11-24 15:42:47 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js'
11-24 16:42:47.671  5615  5663 I jxcore-log: 
,11-24 16:42:47.684  5615  5663 I jxcore-log: 2016-11-24 15:42:47 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js'
11-24 16:42:47.684  5615  5663 I jxcore-log: 
,11-24 16:42:47.689  5615  5663 I jxcore-log: 2016-11-24 15:42:47 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliManager.js'
11-24 16:42:47.689  5615  5663 I jxcore-log: 
,11-24 16:42:47.958  5615  5663 I jxcore-log: 2016-11-24 15:42:47 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliManagerCoordinated.js'
11-24 16:42:47.958  5615  5663 I jxcore-log: 
,11-24 16:42:47.984   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 16:42:48.086  5615  5663 I jxcore-log: 2016-11-24 15:42:48 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js'
11-24 16:42:48.086  5615  5663 I jxcore-log: 
,11-24 16:42:48.463  5615  5663 I jxcore-log: 2016-11-24 15:42:48 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js'
11-24 16:42:48.463  5615  5663 I jxcore-log: 
,11-24 16:42:48.472  5615  5663 I jxcore-log: 2016-11-24 15:42:48 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeDiscoveryCoordinated.js'
11-24 16:42:48.472  5615  5663 I jxcore-log: 
,11-24 16:42:48.476  5615  5663 I jxcore-log: 2016-11-24 15:42:48 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js'
11-24 16:42:48.476  5615  5663 I jxcore-log: 
,11-24 16:42:48.481  5615  5663 I jxcore-log: 2016-11-24 15:42:48 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js'
11-24 16:42:48.481  5615  5663 I jxcore-log: 
,11-24 16:42:48.487  5615  5663 I jxcore-log: 2016-11-24 15:42:48 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js'
11-24 16:42:48.487  5615  5663 I jxcore-log: 
,11-24 16:42:48.516  5615  5663 I jxcore-log: 2016-11-24 15:42:48 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js'
11-24 16:42:48.516  5615  5663 I jxcore-log: 
,11-24 16:42:48.554  5615  5663 I jxcore-log: 2016-11-24 15:42:48 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js'
11-24 16:42:48.554  5615  5663 I jxcore-log: 
,11-24 16:42:48.562  5615  5663 I jxcore-log: 2016-11-24 15:42:48 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationLocal.js'
11-24 16:42:48.562  5615  5663 I jxcore-log: 
,11-24 16:42:48.568  5615  5663 I jxcore-log: 2016-11-24 15:42:48 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js'
11-24 16:42:48.568  5615  5663 I jxcore-log: 
,11-24 16:42:48.584  5615  5663 I jxcore-log: 2016-11-24 15:42:48 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js'
11-24 16:42:48.584  5615  5663 I jxcore-log: 
,11-24 16:42:48.600  5615  5663 I jxcore-log: 2016-11-24 15:42:48 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js'
11-24 16:42:48.600  5615  5663 I jxcore-log: 
,11-24 16:42:48.605  5615  5663 I jxcore-log: 2016-11-24 15:42:48 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolDefault.js'
11-24 16:42:48.605  5615  5663 I jxcore-log: 
,11-24 16:42:48.611  5615  5663 I jxcore-log: 2016-11-24 15:42:48 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js'
11-24 16:42:48.611  5615  5663 I jxcore-log: 
,11-24 16:42:48.624  5615  5663 I jxcore-log: 2016-11-24 15:42:48 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolOneAtATime.js'
11-24 16:42:48.624  5615  5663 I jxcore-log: 
,11-24 16:42:48.641  5615  5663 I jxcore-log: 2016-11-24 15:42:48 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js'
11-24 16:42:48.641  5615  5663 I jxcore-log: 
,11-24 16:42:48.655  5615  5663 I jxcore-log: 2016-11-24 15:42:48 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js'
11-24 16:42:48.655  5615  5663 I jxcore-log: 
,11-24 16:42:48.666  5615  5663 I jxcore-log: 2016-11-24 15:42:48 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerAction.js'
11-24 16:42:48.666  5615  5663 I jxcore-log: 
,11-24 16:42:48.679  5615  5663 I jxcore-log: 2016-11-24 15:42:48 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js'
11-24 16:42:48.679  5615  5663 I jxcore-log: 
,11-24 16:42:48.689  5615  5663 I jxcore-log: 2016-11-24 15:42:48 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js'
11-24 16:42:48.689  5615  5663 I jxcore-log: 
,11-24 16:42:48.702  5615  5663 I jxcore-log: 2016-11-24 15:42:48 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js'
11-24 16:42:48.702  5615  5663 I jxcore-log: 
,11-24 16:42:48.712  5615  5663 I jxcore-log: 2016-11-24 15:42:48 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js'
11-24 16:42:48.712  5615  5663 I jxcore-log: 
,11-24 16:42:48.719  5615  5663 I jxcore-log: 2016-11-24 15:42:48 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js'
11-24 16:42:48.719  5615  5663 I jxcore-log: 
,11-24 16:42:48.741  5615  5663 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: SUPPORTED
,11-24 16:42:48.742  5615  5663 I jxcore-log: 2016-11-24 15:42:48 - INFO testUtils: 'BLE multiple advertisement supported'
11-24 16:42:48.742  5615  5663 I jxcore-log: 
,11-24 16:42:48.774  5615  5663 I jxcore-log: 2016-11-24 15:42:48 - INFO CoordinatedClient: 'Connecting to coordination server on http://85.14.110.168:3000/'
11-24 16:42:48.774  5615  5663 I jxcore-log: 
,11-24 16:42:48.985   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 16:42:49.040  5615  5663 I jxcore-log: 2016-11-24 15:42:49 - DEBUG CoordinatedClient: 'connected to the test server'
11-24 16:42:49.040  5615  5663 I jxcore-log: 
,11-24 16:42:49.987   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 16:42:50.988   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 16:42:51.989   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 16:42:52.990   535   535 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,11-24 16:42:53.809   927  5925 D NetlinkSocketObserver: NeighborEvent{elapsedMs=194370, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,11-24 16:43:05.758   927  5925 D NetlinkSocketObserver: NeighborEvent{elapsedMs=206318, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,11-24 16:43:07.449   927  2910 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-24 16:43:17.991   535   535 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,11-24 16:43:17.991   535   535 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,11-24 16:43:19.050   927  5925 D NetlinkSocketObserver: NeighborEvent{elapsedMs=219611, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,11-24 16:43:27.993   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 16:43:28.995   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 16:43:29.996   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 16:43:30.850   927  5925 D NetlinkSocketObserver: NeighborEvent{elapsedMs=231410, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,11-24 16:43:30.997   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 16:43:31.999   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 16:43:33.000   535   535 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,11-24 16:43:38.001   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 16:43:39.002   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 16:43:40.003   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 16:43:41.004   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 16:43:42.005   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 16:43:43.006   535   535 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,11-24 16:43:44.076   927  5925 D NetlinkSocketObserver: NeighborEvent{elapsedMs=244637, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,11-24 16:43:45.862   927  2912 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-24 16:43:47.455   927  2910 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-24 16:43:48.904   927  2912 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-24 16:43:53.007   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 16:43:54.009   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 16:43:55.011   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 16:43:55.863   927  5925 D NetlinkSocketObserver: NeighborEvent{elapsedMs=256424, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,11-24 16:43:56.012   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 16:43:57.013   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 16:43:58.014   535   535 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,11-24 16:44:07.456   927  2910 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-24 16:44:09.117   927  5925 D NetlinkSocketObserver: NeighborEvent{elapsedMs=269677, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,11-24 16:44:13.016   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 16:44:14.017   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 16:44:15.019   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 16:44:16.020   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 16:44:17.021   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 16:44:18.022   535   535 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,11-24 16:44:20.877   927  5925 D NetlinkSocketObserver: NeighborEvent{elapsedMs=281437, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,11-24 16:44:26.517   927  5925 D NetlinkSocketObserver: NeighborEvent{elapsedMs=287077, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,11-24 16:44:38.023   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 16:44:39.025   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 16:44:40.026   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 16:44:41.027   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 16:44:42.028   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 16:44:43.029   535   535 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,11-24 16:44:45.923   927  5925 D NetlinkSocketObserver: NeighborEvent{elapsedMs=306483, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,11-24 16:44:47.462   927  2910 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-24 16:44:59.183   927  5925 D NetlinkSocketObserver: NeighborEvent{elapsedMs=319743, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,11-24 16:45:07.466   927  2910 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-24 16:45:08.030   535   535 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,11-24 16:45:08.030   535   535 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,11-24 16:45:11.277   927  5925 D NetlinkSocketObserver: NeighborEvent{elapsedMs=331837, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,11-24 16:45:22.815  3688  5469 V NativeCrypto: SSL shutdown failed: ssl=0x7fa4b79b00: I/O error during system call, Connection timed out
,11-24 16:45:23.032   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 16:45:24.034   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 16:45:24.503   927  5925 D NetlinkSocketObserver: NeighborEvent{elapsedMs=345063, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,11-24 16:45:25.035   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 16:45:26.036   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 16:45:27.038   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 16:45:27.467   927  2910 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-24 16:45:28.038   535   535 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,11-24 16:45:33.040   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 16:45:34.041   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 16:45:35.042   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 16:45:36.044   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 16:45:36.291   927  5925 D NetlinkSocketObserver: NeighborEvent{elapsedMs=356851, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,11-24 16:45:37.045   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 16:45:38.046   535   535 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,11-24 16:45:48.048   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 16:45:49.049   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 16:45:49.543   927  5925 D NetlinkSocketObserver: NeighborEvent{elapsedMs=370103, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,11-24 16:45:50.051   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 16:45:51.052   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 16:45:52.053   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 16:45:53.054   535   535 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,11-24 16:46:01.303   927  5925 D NetlinkSocketObserver: NeighborEvent{elapsedMs=381863, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,11-24 16:46:07.472   927  2910 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-24 16:46:08.056   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 16:46:09.057   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 16:46:10.059   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 16:46:11.060   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 16:46:12.061   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 16:46:13.062   535   535 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,11-24 16:46:14.583   927  5925 D NetlinkSocketObserver: NeighborEvent{elapsedMs=395143, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,11-24 16:46:27.473   927  2910 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-24 16:46:31.383   927  5925 D NetlinkSocketObserver: NeighborEvent{elapsedMs=411943, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,11-24 16:46:33.064   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 16:46:34.065   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 16:46:35.067   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 16:46:36.068   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 16:46:37.069   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 16:46:38.070   535   535 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,11-24 16:46:39.597   927  5925 D NetlinkSocketObserver: NeighborEvent{elapsedMs=420157, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,11-24 16:46:47.474   927  2910 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-24 16:46:51.383   927  5925 D NetlinkSocketObserver: NeighborEvent{elapsedMs=431944, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,11-24 16:47:03.071   535   535 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,11-24 16:47:03.072   535   535 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,11-24 16:47:04.663   927  5925 D NetlinkSocketObserver: NeighborEvent{elapsedMs=445224, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,11-24 16:47:07.476   927  2910 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-24 16:47:16.450   927  5925 D NetlinkSocketObserver: NeighborEvent{elapsedMs=457010, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,11-24 16:47:20.564  5615  5663 I jxcore-log: 2016-11-24 15:47:20 - DEBUG CoordinatedClient: 'device disconnected from the test server'
11-24 16:47:20.564  5615  5663 I jxcore-log: 
,11-24 16:47:20.833  5615  5663 I jxcore-log: 2016-11-24 15:47:20 - ERROR CoordinatedClient: 'connection error: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-24 16:47:20.833  5615  5663 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-24 16:47:20.833  5615  5663 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-24 16:47:20.833  5615  5663 I jxcore-log: emit@events.js:82:1
11-24 16:47:20.833  5615  5663 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-24 16:47:20.833  5615  5663 I jxcore-log: emit@events.js:82:1''
11-24 16:47:20.833  5615  5663 I jxcore-log: 
,11-24 16:47:20.835  5615  5663 I jxcore-log: 2016-11-24 15:47:20 - DEBUG CoordinatedClient: 'test client failed'
11-24 16:47:20.835  5615  5663 I jxcore-log: 
,11-24 16:47:20.850  5615  5663 I jxcore-log: 2016-11-24 15:47:20 - ERROR CoordinatedClient: 'connection error: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-24 16:47:20.850  5615  5663 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-24 16:47:20.850  5615  5663 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-24 16:47:20.850  5615  5663 I jxcore-log: emit@events.js:82:1
11-24 16:47:20.850  5615  5663 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-24 16:47:20.850  5615  5663 I jxcore-log: emit@events.js:82:1''
11-24 16:47:20.850  5615  5663 I jxcore-log: 
,11-24 16:47:20.851  5615  5663 I jxcore-log: 2016-11-24 15:47:20 - DEBUG CoordinatedClient: 'test client failed'
11-24 16:47:20.851  5615  5663 I jxcore-log: 
,11-24 16:47:20.855  5615  5663 I jxcore-log: 2016-11-24 15:47:20 - ERROR CoordinatedThaliTape: 'tests failed, error: 'Error: websocket error', stack: 'Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-24 16:47:20.855  5615  5663 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-24 16:47:20.855  5615  5663 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-24 16:47:20.855  5615  5663 I jxcore-log: emit@events.js:82:1
11-24 16:47:20.855  5615  5663 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-24 16:47:20.855  5615  5663 I jxcore-log: emit@events.js:82:1''
11-24 16:47:20.855  5615  5663 I jxcore-log: 
,11-24 16:47:20.857  5615  5663 I jxcore-log: 2016-11-24 15:47:20 - DEBUG CoordinatedThaliTape: '****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****'
11-24 16:47:20.857  5615  5663 I jxcore-log: 
,11-24 16:47:21.405  5977  5977 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,11-24 16:47:21.410  5977  5977 D AndroidRuntime: CheckJNI is OFF
,11-24 16:47:21.442  5977  5977 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,11-24 16:47:21.479  5977  5977 I Radio-JNI: register_android_hardware_Radio DONE
,11-24 16:47:21.495  5977  5977 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,11-24 16:47:21.505   927   940 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=-1: uninstall pkg
,11-24 16:47:21.506   927   940 I ActivityManager: Killing 5615:com.test.thalitest/u0a77 (adj 0): stop com.test.thalitest
,11-24 16:47:21.611   927  3655 I WindowState: WIN DEATH: Window{da7a093 u0 com.test.thalitest/com.test.thalitest.MainActivity}
11-24 16:47:21.612   927  2911 D WifiService: Client connection lost with reason: 4
,11-24 16:47:21.613   927  3489 D GraphicsStats: Buffer count: 2
,11-24 16:47:21.631   927   940 W ActivityManager: Force removing ActivityRecord{ab0713b u0 com.test.thalitest/.MainActivity t70}: app died, no saved state
,11-24 16:47:21.658   927   950 I art     : Starting a blocking GC Explicit
,11-24 16:47:21.665   927  3551 W ActivityManager: Spurious death for ProcessRecord{529ddbc 0:com.test.thalitest/u0a77}, curProc for 5615: null
,11-24 16:47:21.700   927  3782 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 5615 uid 10077
,11-24 16:47:21.696  3782  3782 W Binder_A: type=1400 audit(0.0:121): avc: denied { ioctl } for path="socket:[27784]" dev="sockfs" ino=27784 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
11-24 16:47:21.696  3782  3782 W Binder_A: type=1400 audit(0.0:122): avc: denied { ioctl } for path="socket:[27784]" dev="sockfs" ino=27784 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-24 16:47:21.702  3621  3621 I Keyboard.Facilitator: onFinishInput()
,11-24 16:47:21.771   927   950 I art     : Explicit concurrent mark sweep GC freed 130492(9MB) AllocSpace objects, 86(2MB) LOS objects, 33% free, 29MB/44MB, paused 4.890ms total 112.502ms
,11-24 16:47:21.779  3938  5991 I MicroRecognitionRnrImpl: Starting detection.
,11-24 16:47:21.780  3938  5992 I MicrophoneInputStream: mic_starting com.google.android.apps.gsa.speech.audio.x@380283d
,11-24 16:47:21.782   511  5994 I AudioFlinger: AudioFlinger's thread 0xf1e80000 ready to run
,11-24 16:47:21.786   511  2958 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
,11-24 16:47:21.787  3938  5992 I MicrophoneInputStream: mic_started com.google.android.apps.gsa.speech.audio.x@380283d
,11-24 16:47:21.797   511  5994 D audio_hw_primary: select_devices: out_snd_device(0: none) in_snd_device(63: voice-rec-mic)
,11-24 16:47:21.797   511  5994 D msm8974_platform: platform_send_audio_calibration: sending audio calibration for snd_device(63) acdb_id(62)
11-24 16:47:21.798   511  5994 I ACDB-LOADER: ACDB AFE returned = -19
11-24 16:47:21.798   511  5994 I soundtrigger: audio_extn_sound_trigger_update_device_status: device 0x3f of type 1 for Event 1
11-24 16:47:21.798   511  5994 D sound_trigger_platform: platform_stdev_check_and_update_concurrency: concurrency active 0, tx 1, rx 0, concurrency session_allowed 0
11-24 16:47:21.798   511  5994 D audio_hw_primary: enable_snd_device: snd_device(63: voice-rec-mic)
11-24 16:47:21.799   927   950 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
11-24 16:47:21.801  5977  5977 I art     : System.exit called, status: 0
11-24 16:47:21.801  5977  5977 I AndroidRuntime: VM exiting with result code 0.
,11-24 16:47:21.805   511  5994 D audio_hw_primary: enable_audio_route: apply and update mixer path: audio-record
,11-24 16:47:21.819   927   950 I ActivityManager: Start proc 5997:com.android.defcontainer/u0a7 for service com.android.defcontainer/.DefaultContainerService
,11-24 16:47:21.821   927   950 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=0: pkg removed
,11-24 16:47:21.834  3621  3621 I Keyboard.Facilitator: resetDictionaries() : en_US
,11-24 16:47:21.837  5869  5869 D BluetoothMapAppObserver: onReceive
11-24 16:47:21.837  5869  5869 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
,11-24 16:47:21.842  3621  6009 I Keyboard.Facilitator.DecoderInitializer: run()
11-24 16:47:21.843  3988  4126 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,11-24 16:47:21.851   927  2901 I InputReader: Reconfiguring input devices.  changes=0x00000010
,11-24 16:47:21.857  3621  6009 I Decoder : createOrResetDecoder
,11-24 16:47:21.883  3363  6014 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,11-24 16:47:21.887  3938  3938 I HotwordWorkerImpl: onReady
,11-24 16:47:21.902   927   927 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,11-24 16:47:21.913  3526  3526 I ConfigService: onCreate
,11-24 16:47:21.916   412   412 W kworker/3:2: type=1400 audit(0.0:123): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-24 16:47:21.925  3743  3743 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,11-24 16:47:21.923   412   412 W kworker/3:2: type=1400 audit(0.0:124): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-24 16:47:21.933  3783  3877 E SQLiteLog: (3850) statement aborts at 23: [DELETE FROM icons WHERE componentName LIKE ? AND profileId = ?] disk I/O error
,11-24 16:47:21.945  3621  6009 I Keyboard.Facilitator.MainLanguageModelLoader: run()
,11-24 16:47:21.947   927  3551 I ActivityManager: Start proc 6018:com.google.android.googlequicksearchbox:crash_report/u0a29 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
,--------- beginning of crash
11-24 16:47:21.947  3783  3877 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
11-24 16:47:21.947  3783  3877 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 3783
11-24 16:47:21.947  3783  3877 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
11-24 16:47:21.947  3783  3877 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
11-24 16:47:21.947  3783  3877 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
11-24 16:47:21.947  3783  3877 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
11-24 16:47:21.947  3783  3877 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
11-24 16:47:21.947  3783  3877 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
11-24 16:47:21.947  3783  3877 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
11-24 16:47:21.947  3783  3877 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
11-24 16:47:21.947  3783  3877 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
11-24 16:47:21.947  3783  3877 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
11-24 16:47:21.947  3783  3877 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
11-24 16:47:21.947  3783  3877 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,11-24 16:47:21.943   412   412 W kworker/3:2: type=1400 audit(0.0:125): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-24 16:47:21.956   927  3782 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,11-24 16:47:21.958   927  6027 E DropBoxManagerService: Can't write: system_app_crash
11-24 16:47:21.958   927  6027 E DropBoxManagerService: java.io.IOException: write failed: EROFS (Read-only file system)
11-24 16:47:21.958   927  6027 E DropBoxManagerService: 	at libcore.io.IoBridge.write(IoBridge.java:498)
11-24 16:47:21.958   927  6027 E DropBoxManagerService: 	at java.io.FileOutputStream.write(FileOutputStream.java:186)
11-24 16:47:21.958   927  6027 E DropBoxManagerService: 	at java.io.BufferedOutputStream.flushInternal(BufferedOutputStream.java:185)
11-24 16:47:21.958   927  6027 E DropBoxManagerService: 	at java.io.BufferedOutputStream.flush(BufferedOutputStream.java:85)
11-24 16:47:21.958   927  6027 E DropBoxManagerService: 	at java.io.FilterOutputStream.close(FilterOutputStream.java:61)
11-24 16:47:21.958   927  6027 E DropBoxManagerService: 	at java.io.BufferedOutputStream.close(BufferedOutputStream.java:152)
11-24 16:47:21.958   927  6027 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:230)
11-24 16:47:21.958   927  6027 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
11-24 16:47:21.958   927  6027 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
11-24 16:47:21.958   927  6027 E DropBoxManagerService: Caused by: android.system.ErrnoException: write failed: EROFS (Read-only file system)
11-24 16:47:21.958   927  6027 E DropBoxManagerService: 	at libcore.io.Posix.writeBytes(Native Method)
11-24 16:47:21.958   927  6027 E DropBoxManagerService: 	at libcore.io.Posix.write(Posix.java:271)
11-24 16:47:21.958   927  6027 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.write(BlockGuardOs.java:313)
11-24 16:47:21.958   927  6027 E DropBoxManagerService: 	at libcore.io.IoBridge.write(IoBridge.java:493)
11-24 16:47:21.958   927  6027 E DropBoxManagerService: 	... 8 more
,11-24 16:47:21.961  3938  3949 W SearchService: Abort, client detached.
,11-24 16:47:21.963  3363  6014 E SQLiteLog: (3850) statement aborts at 18: [DELETE FROM calls WHERE (((source_package = 'com.test.thalitest'))) AND ((type = 4))] disk I/O error
11-24 16:47:21.964  3938  3938 I HotwordDetector: Closing mic
11-24 16:47:21.964  3938  4150 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@380283d
11-24 16:47:21.964  3938  5992 E AudioRecord-JNI: Error -4 during AudioRecord native read
,11-24 16:47:21.979  3363  6014 E AndroidRuntime: FATAL EXCEPTION: IntentService[VoicemailCleanupService]
11-24 16:47:21.979  3363  6014 E AndroidRuntime: Process: android.process.acore, PID: 3363
11-24 16:47:21.979  3363  6014 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
11-24 16:47:21.979  3363  6014 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
11-24 16:47:21.979  3363  6014 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
11-24 16:47:21.979  3363  6014 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
11-24 16:47:21.979  3363  6014 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
11-24 16:47:21.979  3363  6014 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
11-24 16:47:21.979  3363  6014 E AndroidRuntime: 	at com.android.providers.contacts.DbModifierWithNotification.delete(DbModifierWithNotification.java:197)
11-24 16:47:21.979  3363  6014 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:219)
11-24 16:47:21.979  3363  6014 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
11-24 16:47:21.979  3363  6014 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
11-24 16:47:21.979  3363  6014 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
11-24 16:47:21.979  3363  6014 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
11-24 16:47:21.979  3363  6014 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
11-24 16:47:21.979  3363  6014 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
11-24 16:47:21.979  3363  6014 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-24 16:47:21.979  3363  6014 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
11-24 16:47:21.979  3363  6014 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,11-24 16:47:21.980   407   407 W Binder_2: type=1400 audit(0.0:126): avc: denied { ioctl } for path="socket:[34273]" dev="sockfs" ino=34273 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-24 16:47:21.980   407   407 W Binder_2: type=1400 audit(0.0:127): avc: denied { ioctl } for path="socket:[34273]" dev="sockfs" ino=34273 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-24 16:47:21.983   405   405 W Binder_1: type=1400 audit(0.0:128): avc: denied { ioctl } for path="socket:[31520]" dev="sockfs" ino=31520 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-24 16:47:21.983   405   405 W Binder_1: type=1400 audit(0.0:129): avc: denied { ioctl } for path="socket:[31520]" dev="sockfs" ino=31520 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
11-24 16:47:21.986   927  6031 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,11-24 16:47:21.997   927  6032 E DropBoxManagerService: Can't write: system_app_crash
11-24 16:47:21.997   927  6032 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop120.tmp: open failed: EROFS (Read-only file system)
11-24 16:47:21.997   927  6032 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
11-24 16:47:21.997   927  6032 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
11-24 16:47:21.997   927  6032 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
11-24 16:47:21.997   927  6032 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
11-24 16:47:21.997   927  6032 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
11-24 16:47:21.997   927  6032 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
11-24 16:47:21.997   927  6032 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
11-24 16:47:21.997   927  6032 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
11-24 16:47:21.997   927  6032 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
11-24 16:47:21.997   927  6032 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
11-24 16:47:21.997   927  6032 E DropBoxManagerService: 	... 5 more
,11-24 16:47:22.008  3526  3526 E SQLiteLog: (3850) statement aborts at 26: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
,11-24 16:47:22.011  3526  3526 D AndroidRuntime: Shutting down VM
11-24 16:47:22.012  3526  3526 E AndroidRuntime: FATAL EXCEPTION: main
11-24 16:47:22.012  3526  3526 E AndroidRuntime: Process: com.google.process.gapps, PID: 3526
11-24 16:47:22.012  3526  3526 E AndroidRuntime: java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
11-24 16:47:22.012  3526  3526 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2732)
11-24 16:47:22.012  3526  3526 E AndroidRuntime: 	at android.app.ActivityThread.-wrap14(ActivityThread.java)
11-24 16:47:22.012  3526  3526 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1421)
11-24 16:47:22.012  3526  3526 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-24 16:47:22.012  3526  3526 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
11-24 16:47:22.012  3526  3526 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-24 16:47:22.012  3526  3526 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
11-24 16:47:22.012  3526  3526 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-24 16:47:22.012  3526  3526 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-24 16:47:22.012  3526  3526 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
11-24 16:47:22.012  3526  3526 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
11-24 16:47:22.012  3526  3526 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
11-24 16:47:22.012  3526  3526 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
11-24 16:47:22.012  3526  3526 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
11-24 16:47:22.012  3526  3526 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
11-24 16:47:22.012  3526  3526 E AndroidRuntime: 	at com.google.android.gms.gcm.bg.a(SourceFile:310)
11-24 16:47:22.012  3526  3526 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
11-24 16:47:22.012  3526  3526 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
11-24 16:47:22.012  3526  3526 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2725)
11-24 16:47:22.012  3526  3526 E AndroidRuntime: 	... 8 more
,11-24 16:47:22.020  3621  6009 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /data/user/0/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
11-24 16:47:22.022  3621  6009 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
,11-24 16:47:22.022  3621  6009 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
,11-24 16:47:22.025   927  6035 E DropBoxManagerService: Can't write: system_app_crash
11-24 16:47:22.025   927  6035 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop121.tmp: open failed: EROFS (Read-only file system)
11-24 16:47:22.025   927  6035 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
11-24 16:47:22.025   927  6035 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
11-24 16:47:22.025   927  6035 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
11-24 16:47:22.025   927  6035 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
11-24 16:47:22.025   927  6035 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
11-24 16:47:22.025   927  6035 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
11-24 16:47:22.025   927  6035 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
11-24 16:47:22.025   927  6035 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
11-24 16:47:22.025   927  6035 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
11-24 16:47:22.025   927  6035 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
11-24 16:47:22.025   927  6035 E DropBoxManagerService: 	... 5 more
11-24 16:47:22.025  3621  6009 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Contacts.dict
11-24 16:47:22.025  3621  6009 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = history
,11-24 16:47:22.026  3621  6009 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loaded File = UserHistory.en_US.dict
11-24 16:47:22.026  3621  6009 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = user
11-24 16:47:22.027   511  5994 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
11-24 16:47:22.027  3621  6009 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Personal.en_US.dict
11-24 16:47:22.027  3621  6009 I Keyboard.Facilitator.PersonalDictionaryLoader: run() : Loaded (exit)
11-24 16:47:22.027  3621  6009 I Keyboard.Facilitator.Delight2FileSweeper: run()
11-24 16:47:22.028  3621  6009 I Keyboard.Facilitator.RecurringTaskScheduler: run()
11-24 16:47:22.028  3621  6009 I StatsUtilsManager: startPeriodStatsRecorder() : Success
11-24 16:47:22.028  3621  6009 I PeriodicStatsRecorder: shouldRecordStats() = Too Soon
,11-24 16:47:22.029   511  5994 D audio_hw_primary: disable_snd_device: snd_device(63: voice-rec-mic)
,11-24 16:47:22.034   511  5994 I soundtrigger: audio_extn_sound_trigger_update_device_status: device 0x3f of type 1 for Event 0
,11-24 16:47:22.034   511  5994 D sound_trigger_platform: platform_stdev_check_and_update_concurrency: concurrency active 0, tx 0, rx 0, concurrency session_allowed 1
,11-24 16:47:22.035   511  2958 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
,11-24 16:47:22.036  3938  4158 I MicroRecognitionRnrImpl: Stopping hotword detection.
,11-24 16:47:22.037  3938  5991 I MicroRecognitionRnrImpl: Detection finished
,11-24 16:47:22.330   383   480 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0

```
