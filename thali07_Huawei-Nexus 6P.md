#### Test 89975734180bfa4_thali07_Huawei-Nexus 6P Logs


```
--------- beginning of main
11-25 14:31:07.353  3912  4162 I Icing   : Indexing 3C763AF371F9E97B4ECFEA01A338ADB468C38476 from com.google.android.googlequicksearchbox
,11-25 14:31:07.428  3912  4162 I Icing   : Indexing done 3C763AF371F9E97B4ECFEA01A338ADB468C38476
11-25 14:31:07.838  5528  5528 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
11-25 14:31:07.844  5528  5528 D AndroidRuntime: CheckJNI is OFF
11-25 14:31:07.872  5528  5528 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
11-25 14:31:07.907  5528  5528 I Radio-JNI: register_android_hardware_Radio DONE
11-25 14:31:07.925  5528  5528 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
11-25 14:31:07.930   929  3716 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
11-25 14:31:07.962  3895  3909 W SearchService: Abort, client detached.
11-25 14:31:07.970  3895  3895 I HotwordDetector: Closing mic
11-25 14:31:07.970  3895  4154 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@db7641
11-25 14:31:07.970  3895  4159 E AudioRecord-JNI: Error -4 during AudioRecord native read
11-25 14:31:07.971  5528  5528 D AndroidRuntime: Shutting down VM
11-25 14:31:07.996   929  3737 I ActivityManager: Start proc 5537:com.test.thalitest/u0a77 for activity com.test.thalitest/.MainActivity
11-25 14:31:08.050   511  4161 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
11-25 14:31:08.053   511  4161 D audio_hw_primary: disable_snd_device: snd_device(63: voice-rec-mic)
11-25 14:31:08.059   511  4161 I soundtrigger: audio_extn_sound_trigger_update_device_status: device 0x3f of type 1 for Event 0
11-25 14:31:08.059   511  4161 D sound_trigger_platform: platform_stdev_check_and_update_concurrency: concurrency active 0, tx 0, rx 0, concurrency session_allowed 1
11-25 14:31:08.060   511  2916 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
11-25 14:31:08.062  3895  4155 I MicroRecognitionRnrImpl: Stopping hotword detection.
11-25 14:31:08.063  3895  4158 I MicroRecognitionRnrImpl: Detection finished
11-25 14:31:08.109  5537  5537 I CordovaLog: Changing log level to DEBUG(3)
11-25 14:31:08.109  5537  5537 I CordovaActivity: Apache Cordova native platform version 6.0.0 is starting
11-25 14:31:08.109  5537  5537 D CordovaActivity: CordovaActivity.onCreate()
11-25 14:31:08.113  5537  5537 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011750)
11-25 14:31:08.134  5537  5537 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
11-25 14:31:08.188  5537  5537 I LibraryLoader: Time to load native libraries: 50 ms (timestamps 9680-9730)
11-25 14:31:08.188  5537  5537 I LibraryLoader: Expected native library version number "",actual native library version number ""
,11-25 14:31:08.215  5537  5537 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {45a9240}
11-25 14:31:08.215  5537  5537 I LibraryLoader: Expected native library version number "",actual native library version number ""
,11-25 14:31:08.215  5537  5537 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,11-25 14:31:08.219  5537  5537 I BrowserStartupController: Initializing chromium process, singleProcess=true
,11-25 14:31:08.219  5537  5537 E SysUtils: ApplicationContext is null in ApplicationStatus
,11-25 14:31:08.278  5537  5537 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,11-25 14:31:08.290  5537  5537 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,11-25 14:31:08.290  5537  5537 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
11-25 14:31:08.290  5537  5537 I Adreno  : QUALCOMM build                   : 63c06b2, I8366cd0437
11-25 14:31:08.290  5537  5537 I Adreno  : Build Date                       : 12/06/15
11-25 14:31:08.290  5537  5537 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
11-25 14:31:08.290  5537  5537 I Adreno  : Local Branch                     : mybranch17112971
11-25 14:31:08.290  5537  5537 I Adreno  : Remote Branch                    : quic/LA.BF64.1.2.9_v2
11-25 14:31:08.290  5537  5537 I Adreno  : Remote Branch                    : NONE
11-25 14:31:08.290  5537  5537 I Adreno  : Reconstruct Branch               : NOTHING
,11-25 14:31:08.325   929   946 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@a249a7f:true
,11-25 14:31:08.348   407   407 W Binder_2: type=1400 audit(0.0:99): avc: denied { ioctl } for path="socket:[15945]" dev="sockfs" ino=15945 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-25 14:31:08.348   407   407 W Binder_2: type=1400 audit(0.0:100): avc: denied { ioctl } for path="socket:[15945]" dev="sockfs" ino=15945 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-25 14:31:08.361  5537  5537 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,11-25 14:31:08.369  5537  5537 D SystemWebViewEngine: CordovaWebView is running on device made by: Huawei
,11-25 14:31:08.373  5537  5537 D PluginManager: init()
,11-25 14:31:08.376  5537  5537 D CordovaWebViewImpl: >>> loadUrl(file:///android_asset/www/index.html)
,11-25 14:31:08.390  5537  5537 D CordovaActivity: Started the activity.
,11-25 14:31:08.390  5537  5537 D CordovaActivity: Resumed the activity.
,11-25 14:31:08.395  5537  5574 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,11-25 14:31:08.391   765   765 W Binder_3: type=1400 audit(0.0:101): avc: denied { ioctl } for path="socket:[29335]" dev="sockfs" ino=29335 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
11-25 14:31:08.391   765   765 W Binder_3: type=1400 audit(0.0:102): avc: denied { ioctl } for path="socket:[29335]" dev="sockfs" ino=29335 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-25 14:31:08.395  3716  3716 W Binder_8: type=1400 audit(0.0:103): avc: denied { ioctl } for path="socket:[28195]" dev="sockfs" ino=28195 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-25 14:31:08.395  3716  3716 W Binder_8: type=1400 audit(0.0:104): avc: denied { ioctl } for path="socket:[28195]" dev="sockfs" ino=28195 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-25 14:31:08.399  5537  5561 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,11-25 14:31:08.433  5537  5574 I OpenGLRenderer: Initialized EGL, version 1.4
,11-25 14:31:08.495  3520  3520 W Binder_6: type=1400 audit(0.0:105): avc: denied { ioctl } for path="socket:[33881]" dev="sockfs" ino=33881 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-25 14:31:08.495  3520  3520 W Binder_6: type=1400 audit(0.0:106): avc: denied { ioctl } for path="socket:[33881]" dev="sockfs" ino=33881 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-25 14:31:08.497   929   947 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +526ms
,11-25 14:31:08.495  3337  3337 W Binder_5: type=1400 audit(0.0:107): avc: denied { ioctl } for path="socket:[33880]" dev="sockfs" ino=33880 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-25 14:31:08.495  3337  3337 W Binder_5: type=1400 audit(0.0:108): avc: denied { ioctl } for path="socket:[33880]" dev="sockfs" ino=33880 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
11-25 14:31:08.500  3578  3578 I Keyboard.Facilitator: onFinishInput()
,11-25 14:31:08.509  5537  5537 D CordovaWebViewImpl: onPageDidNavigate(file:///android_asset/www/index.html)
,11-25 14:31:08.522  5537  5537 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 5537
,11-25 14:31:08.586  5537  5537 D JsMessageQueue: Set native->JS mode to EvalBridgeMode
,11-25 14:31:08.719  5537  5578 D jxcore_app_log: JniHelper::setJavaVM(0xf53bc000), pthread_self() = -581170896
,11-25 14:31:08.724  5537  5578 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
11-25 14:31:08.724  5537  5578 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
11-25 14:31:08.724  5537  5578 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
11-25 14:31:08.724  5537  5578 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
11-25 14:31:08.724  5537  5578 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,11-25 14:31:08.724  5537  5578 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c8d5ed7 added. We now have 1 listener(s)
,11-25 14:31:08.726  5537  5578 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 60:83:34:25:D7:D4
,11-25 14:31:08.727  5537  5578 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
,11-25 14:31:08.728  5537  5578 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,11-25 14:31:08.728  5537  5578 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,11-25 14:31:08.730  5537  5578 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
11-25 14:31:08.730  5537  5578 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
11-25 14:31:08.730  5537  5578 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
11-25 14:31:08.730  5537  5578 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 60:83:34:25:D7:D4
11-25 14:31:08.730  5537  5578 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
11-25 14:31:08.730  5537  5578 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
11-25 14:31:08.730  5537  5578 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
11-25 14:31:08.730  5537  5578 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
11-25 14:31:08.730  5537  5578 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
11-25 14:31:08.730  5537  5578 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
11-25 14:31:08.730  5537  5578 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
11-25 14:31:08.730  5537  5578 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
11-25 14:31:08.730  5537  5578 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
11-25 14:31:08.730  5537  5578 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,11-25 14:31:08.733  5537  5578 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@79919e2 added. We now have 1 listener(s)
11-25 14:31:08.733  5537  5578 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-25 14:31:08.738   929  2909 D WifiService: New client listening to asynchronous messages
,11-25 14:31:08.738  5537  5578 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
11-25 14:31:08.738  5537  5578 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
11-25 14:31:08.738  5537  5578 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[JavaBridge,5,main], id: 51
11-25 14:31:08.738  5537  5578 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
11-25 14:31:08.739  5537  5578 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
11-25 14:31:08.739  5537  5578 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,11-25 14:31:08.739  5537  5578 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[JavaBridge,5,main], id: 51
,11-25 14:31:08.740  5537  5578 I io.jxcore.node.LifeCycleMonitor: start: OK
,11-25 14:31:08.834  5537  5537 D CordovaWebViewImpl: onPageFinished(file:///android_asset/www/index.html)
,11-25 14:31:08.836  5537  5537 D SystemWebChromeClient: file:///android_asset/www/js/index.js: Line 36 : Uncaught TypeError: Cannot read property 'querySelector' of null
,11-25 14:31:08.836  5537  5537 I chromium: [INFO:CONSOLE(36)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (36)
,11-25 14:31:09.432  5537  5585 W jxcore-log: Initializing JXcore engine
11-25 14:31:09.432  5537  5585 W jxcore-log: JXcore engine is ready
,11-25 14:31:09.455  5585  5585 W Thread-58: type=1400 audit(0.0:109): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=11989 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
11-25 14:31:09.455  5585  5585 W Thread-58: type=1400 audit(0.0:110): avc: denied { ioctl } for path="socket:[15381]" dev="sockfs" ino=15381 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,11-25 14:31:09.455  5585  5585 W Thread-58: type=1400 audit(0.0:111): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=5964 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
11-25 14:31:09.455  5585  5585 W Thread-58: type=1400 audit(0.0:112): avc: denied { ioctl } for path="socket:[33846]" dev="sockfs" ino=33846 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:untrusted_app:s0:c512,c768 tclass=netlink_route_socket permissive=0
,11-25 14:31:09.465  5537  5585 W jxcore-log: Starting JXcore engine
,11-25 14:31:09.515  5537  5585 W jxcore-log: Platform android
11-25 14:31:09.515  5537  5585 W jxcore-log: 
,11-25 14:31:09.515  5537  5585 W jxcore-log: Process ARCH arm
11-25 14:31:09.515  5537  5585 W jxcore-log: 
,11-25 14:31:09.700  5537  5585 I jxcore-log: JXcore Cordova bridge is ready!
11-25 14:31:09.700  5537  5585 I jxcore-log: 
,11-25 14:31:09.701  5537  5585 W jxcore-log: JXcore engine is started
,11-25 14:31:09.716  5537  5578 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,11-25 14:31:09.723  5537  5537 D SystemWebChromeClient: file:///android_asset/www/js/thali_main.js: Line 41 : Application has the required permission.
,11-25 14:31:09.723  5537  5537 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,11-25 14:31:11.485  3504  3504 I ConfigService: onDestroy
,11-25 14:31:12.979   929  3337 I ActivityManager: Killing 5001:com.google.android.youtube/u0a75 (adj 15): empty #17
,11-25 14:31:17.732   929  2907 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-25 14:31:18.231   929  2909 D WifiService: New client listening to asynchronous messages
,11-25 14:31:18.235  3895  5588 W CronetSyncConnectionRcs: Upload content type not set.
,11-25 14:31:19.407  5537  5585 I jxcore-log: 2016-11-25 13:31:19 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
11-25 14:31:19.407  5537  5585 I jxcore-log: 
,11-25 14:31:19.409  5537  5585 I jxcore-log: 2016-11-25 13:31:19 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
11-25 14:31:19.409  5537  5585 I jxcore-log: 
,11-25 14:31:19.413  5537  5585 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,11-25 14:31:19.414  5537  5585 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-25 14:31:19.414  5537  5585 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-25 14:31:19.414  5537  5585 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-25 14:31:19.414  5537  5585 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-25 14:31:19.414  5537  5585 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-25 14:31:19.414  5537  5585 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-25 14:31:19.414  5537  5585 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-25 14:31:19.414  5537  5585 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-25 14:31:19.414  5537  5585 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,11-25 14:31:19.415  5537  5585 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
,11-25 14:31:19.418  5537  5585 I jxcore-log: 2016-11-25 13:31:19 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
11-25 14:31:19.418  5537  5585 I jxcore-log: 
11-25 14:31:19.419  5537  5585 I jxcore-log: 2016-11-25 13:31:19 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
11-25 14:31:19.419  5537  5585 I jxcore-log: 
,11-25 14:31:19.664  5537  5585 I jxcore-log: 2016-11-25 13:31:19 - DEBUG UnitTest_app: 'Running unit tests'
11-25 14:31:19.664  5537  5585 I jxcore-log: 
,11-25 14:31:19.665  5537  5585 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-25 14:31:19.665  5537  5585 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@bf6345e added. We now have 2 listener(s)
,11-25 14:31:19.666  5537  5585 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-25 14:31:19.666  5537  5585 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-25 14:31:19.666  5537  5585 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-25 14:31:19.666  5537  5585 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,11-25 14:31:19.666  5537  5585 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a7d203f added. We now have 2 listener(s)
11-25 14:31:19.666  5537  5585 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-25 14:31:19.667  5537  5585 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
11-25 14:31:19.668  5537  5585 D executeNativeTests: Running unit tests
,11-25 14:31:19.710  5537  5585 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,11-25 14:31:19.710  5537  5585 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@51ee13c added. We now have 3 listener(s)
11-25 14:31:19.710  5537  5585 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-25 14:31:19.710  5537  5585 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-25 14:31:19.711  5537  5585 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-25 14:31:19.711  5537  5585 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,11-25 14:31:19.711  5537  5585 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@72e5ec5 added. We now have 3 listener(s)
11-25 14:31:19.711  5537  5585 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-25 14:31:19.711  5537  5585 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,11-25 14:31:19.713  5537  5585 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
11-25 14:31:19.714  5537  5585 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,11-25 14:31:19.714  5537  5585 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-25 14:31:19.714  5537  5585 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-25 14:31:19.715  5537  5585 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
,11-25 14:31:19.715  5537  5585 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
11-25 14:31:19.715  5537  5585 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
11-25 14:31:19.715  5537  5585 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-25 14:31:19.715  5537  5585 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,11-25 14:31:19.715  5537  5585 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-25 14:31:19.715  5537  5585 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-25 14:31:19.716  5537  5585 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-25 14:31:19.716  5537  5585 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,11-25 14:31:19.716  5537  5585 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-25 14:31:19.716  5537  5585 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-25 14:31:19.716  5537  5585 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,11-25 14:31:19.716  5537  5585 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@51ee13c removed from the list
11-25 14:31:19.716  5537  5585 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 14:31:19.716  5537  5585 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@72e5ec5 removed from the list
11-25 14:31:19.716  5537  5585 D io.jxcore.node.ConnectivityMonitor: stop
,11-25 14:31:19.716  5537  5585 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-58,5,main], id: 58
11-25 14:31:19.717  5537  5585 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-58,5,main], id: 58
11-25 14:31:19.718  5537  5585 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-58,5,main], id: 58
11-25 14:31:19.718  5537  5585 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-58,5,main], id: 58
,11-25 14:31:19.718  5537  5585 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-58,5,main], id: 58
,11-25 14:31:19.718  5537  5585 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,11-25 14:31:19.718  5537  5585 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-25 14:31:19.718  5537  5585 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 14:31:19.718  5537  5585 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@72e5ec5 not in the list
,11-25 14:31:19.719  5537  5585 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
11-25 14:31:19.719  5537  5585 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-25 14:31:19.719  5537  5585 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-25 14:31:19.719  5537  5585 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-25 14:31:19.719  5537  5585 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-25 14:31:19.720  5537  5585 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-25 14:31:19.720  5537  5585 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@51ee13c not in the list
11-25 14:31:19.720  5537  5585 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 14:31:19.720  5537  5585 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@72e5ec5 not in the list
11-25 14:31:19.720  5537  5585 D io.jxcore.node.ConnectivityMonitor: stop
11-25 14:31:19.720  5537  5585 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-58,5,main], id: 58
11-25 14:31:19.720  5537  5585 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-58,5,main], id: 58
11-25 14:31:19.721  5537  5585 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-58,5,main], id: 58
11-25 14:31:19.721  5537  5585 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-58,5,main], id: 58
11-25 14:31:19.721  5537  5585 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-58,5,main], id: 58
11-25 14:31:19.721  5537  5585 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-25 14:31:19.721  5537  5585 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-25 14:31:19.721  5537  5585 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 14:31:19.721  5537  5585 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@72e5ec5 not in the list
11-25 14:31:19.723  5537  5585 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
11-25 14:31:19.723  5537  5585 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
,11-25 14:31:19.724  5537  5585 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
11-25 14:31:19.724  5537  5585 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
11-25 14:31:19.724  5537  5585 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
11-25 14:31:19.724  5537  5585 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
11-25 14:31:19.724  5537  5585 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
11-25 14:31:19.724  5537  5585 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
,11-25 14:31:19.724  5537  5585 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
11-25 14:31:19.724  5537  5585 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
11-25 14:31:19.724  5537  5585 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
11-25 14:31:19.724  5537  5585 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
,11-25 14:31:19.724  5537  5585 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
11-25 14:31:19.724  5537  5585 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
11-25 14:31:19.724  5537  5585 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
11-25 14:31:19.724  5537  5585 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
11-25 14:31:19.724  5537  5585 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
11-25 14:31:19.724  5537  5585 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
11-25 14:31:19.724  5537  5585 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
11-25 14:31:19.724  5537  5585 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
11-25 14:31:19.724  5537  5585 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
11-25 14:31:19.724  5537  5585 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
11-25 14:31:19.724  5537  5585 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
11-25 14:31:19.724  5537  5585 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
11-25 14:31:19.724  5537  5585 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
11-25 14:31:19.724  5537  5585 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
11-25 14:31:19.724  5537  5585 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
11-25 14:31:19.724  5537  5585 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
,11-25 14:31:19.724  5537  5585 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
11-25 14:31:19.724  5537  5585 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
11-25 14:31:19.725  5537  5585 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
11-25 14:31:19.725  5537  5585 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-25 14:31:19.725  5537  5585 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,11-25 14:31:19.725  5537  5585 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-25 14:31:19.725  5537  5585 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-25 14:31:19.725  5537  5585 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-25 14:31:19.725  5537  5585 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@51ee13c not in the list
11-25 14:31:19.725  5537  5585 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 14:31:19.725  5537  5585 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@72e5ec5 not in the list
11-25 14:31:19.725  5537  5585 D io.jxcore.node.ConnectivityMonitor: stop
11-25 14:31:19.725  5537  5585 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-58,5,main], id: 58
11-25 14:31:19.725  5537  5585 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-58,5,main], id: 58
11-25 14:31:19.726  5537  5585 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-58,5,main], id: 58
11-25 14:31:19.726  5537  5585 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-58,5,main], id: 58
,11-25 14:31:19.726  5537  5585 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-58,5,main], id: 58
11-25 14:31:19.726  5537  5585 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-25 14:31:19.726  5537  5585 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-25 14:31:19.726  5537  5585 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 14:31:19.726  5537  5585 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@72e5ec5 not in the list
,11-25 14:31:19.726  5537  5585 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
11-25 14:31:19.728  5537  5585 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-25 14:31:19.728  5537  5585 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
11-25 14:31:19.738  5537  5585 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-25 14:31:19.738  5537  5585 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-25 14:31:19.738  5537  5585 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-25 14:31:19.738  5537  5585 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-25 14:31:19.738  5537  5585 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-25 14:31:19.738  5537  5585 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-25 14:31:19.738  5537  5585 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-25 14:31:19.738  5537  5585 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-25 14:31:19.738  5537  5585 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,11-25 14:31:19.739  5537  5585 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
11-25 14:31:19.739  5537  5585 D io.jxcore.node.ConnectivityMonitor: start: OK
11-25 14:31:19.739  5537  5585 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-25 14:31:19.739  5537  5585 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
11-25 14:31:19.739  5537  5585 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,11-25 14:31:19.739  5537  5585 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-25 14:31:19.739  5537  5585 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
11-25 14:31:19.742  5537  5585 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-25 14:31:19.742  5537  5585 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,11-25 14:31:19.742  5537  5585 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
11-25 14:31:19.742  5537  5537 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-25 14:31:19.743  5537  5537 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-25 14:31:19.745  5537  5585 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-58,5,main], id: 58
11-25 14:31:19.745  5537  5585 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-25 14:31:19.746  5537  5585 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-25 14:31:19.746  5537  5585 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-25 14:31:19.746  5537  5585 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 0
11-25 14:31:19.747  5537  5585 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
,11-25 14:31:19.749  5537  5585 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
11-25 14:31:19.749  5537  5585 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-58,5,main], id: 58
,11-25 14:31:19.749  5537  5585 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
11-25 14:31:19.749  5537  5585 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
11-25 14:31:19.749  5537  5585 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
11-25 14:31:19.749  5537  5585 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
11-25 14:31:19.749  5537  5585 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-58,5,main], id: 58
11-25 14:31:19.750  5537  5585 D BluetoothAdapter: STATE_ON
11-25 14:31:19.752  4515  4529 D BtGatt.GattService: registerClient() - UUID=0fe2108a-cf74-473e-aed3-89a53ed05550
,11-25 14:31:19.753  4515  4578 D BtGatt.GattService: onClientRegistered() - UUID=0fe2108a-cf74-473e-aed3-89a53ed05550, clientIf=5
,11-25 14:31:19.756  5537  5547 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,11-25 14:31:19.759  4515  4722 D BtGatt.GattService: start scan with filters
,11-25 14:31:19.764  4515  4581 D BtGatt.ScanManager: handling starting scan
,11-25 14:31:19.765  5537  5585 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
11-25 14:31:19.765  5537  5585 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-58,5,main], id: 58
11-25 14:31:19.765  5537  5585 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
11-25 14:31:19.765  5537  5585 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-58,5,main], id: 58
11-25 14:31:19.765  5537  5585 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-25 14:31:19.765  5537  5537 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-25 14:31:19.765  5537  5537 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
,11-25 14:31:19.765  5537  5537 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
11-25 14:31:19.766  5537  5585 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-25 14:31:19.766  5537  5537 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-25 14:31:19.766  5537  5585 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-58,5,main], id: 58
,11-25 14:31:19.766  5537  5537 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-25 14:31:19.766  5537  5537 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
11-25 14:31:19.766  5537  5537 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-25 14:31:19.766  4515  4581 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@91cfe3b
11-25 14:31:19.766  5537  5537 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING] Current thread: Thread[main,5,main], id: 1
11-25 14:31:19.768  5537  5585 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-58,5,main], id: 58
11-25 14:31:19.768  5537  5585 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-58,5,main], id: 58
11-25 14:31:19.768  5537  5585 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-58,5,main], id: 58
11-25 14:31:19.768  5537  5537 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-25 14:31:19.769  5537  5585 I io.jxcore.node.ConnectionHelper: start: OK
,11-25 14:31:19.773  5537  5537 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
,11-25 14:31:19.774  5537  5537 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
11-25 14:31:19.774  5537  5537 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-25 14:31:19.774  5537  5537 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
,11-25 14:31:19.774  5537  5537 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
11-25 14:31:19.776  4515  4578 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
11-25 14:31:19.776  4515  4578 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-25 14:31:19.777  4515  4581 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,11-25 14:31:19.785  4515  4578 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
11-25 14:31:19.785  4515  4578 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-25 14:31:19.786  4515  4581 D BtGatt.ScanManager: Starting BLE batch scan
,11-25 14:31:19.786  4515  4581 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,11-25 14:31:19.799  4515  4578 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,11-25 14:31:19.799  4515  4578 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-25 14:31:19.806  4515  4578 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
11-25 14:31:19.806  4515  4578 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-25 14:31:19.824   929  2910 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,11-25 14:31:20.276  5537  5537 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,11-25 14:31:20.276  5537  5537 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
11-25 14:31:20.276  5537  5537 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,11-25 14:31:21.932   577   577 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 14:31:22.849   929  2910 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,11-25 14:31:22.933   577   577 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 14:31:23.934   577   577 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 14:31:24.774  5537  5585 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-25 14:31:24.774  5537  5585 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
11-25 14:31:24.774  5537  5585 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,11-25 14:31:24.774  5537  5585 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-25 14:31:24.774  5537  5585 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-25 14:31:24.774  5537  5585 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,11-25 14:31:24.775  5537  5585 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,11-25 14:31:24.775  5537  5585 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,11-25 14:31:24.775  5537  5585 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-58,5,main], id: 58
,11-25 14:31:24.775  5537  5585 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
,11-25 14:31:24.775  5537  5585 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,11-25 14:31:24.776  5537  5585 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-58,5,main], id: 58
11-25 14:31:24.776  5537  5585 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-58,5,main], id: 58
11-25 14:31:24.776  5537  5585 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-58,5,main], id: 58
11-25 14:31:24.776  5537  5585 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
11-25 14:31:24.776  5537  5585 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-58,5,main], id: 58
11-25 14:31:24.777  5537  5585 D BluetoothAdapter: STATE_ON
11-25 14:31:24.778  4515  4721 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
,11-25 14:31:24.778  5537  5585 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-25 14:31:24.779  5537  5585 D BluetoothAdapter: STATE_ON
,11-25 14:31:24.779  4515  4581 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
11-25 14:31:24.780  4515  4529 D BtGatt.GattService: stopScan() - queue size =1
11-25 14:31:24.781  4515  4722 D BtGatt.GattService: unregisterClient() - clientIf=5
11-25 14:31:24.781  5537  5585 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-25 14:31:24.781  5537  5585 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-58,5,main], id: 58
11-25 14:31:24.781  5537  5585 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
11-25 14:31:24.782  5537  5585 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-58,5,main], id: 58
11-25 14:31:24.782  5537  5585 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-58,5,main], id: 58
11-25 14:31:24.782  5537  5585 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-58,5,main], id: 58
11-25 14:31:24.782  5537  5585 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-58,5,main], id: 58
11-25 14:31:24.783  5537  5585 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-25 14:31:24.783  5537  5585 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-58,5,main], id: 58
11-25 14:31:24.783  5537  5585 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-58,5,main], id: 58
11-25 14:31:24.783  5537  5585 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-58,5,main], id: 58
11-25 14:31:24.783  5537  5585 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-25 14:31:24.783  5537  5585 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-25 14:31:24.784  5537  5585 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-25 14:31:24.784  5537  5585 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-58,5,main], id: 58
11-25 14:31:24.786  5537  5585 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-58,5,main], id: 58
,11-25 14:31:24.786  5537  5585 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-25 14:31:24.786  5537  5585 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-58,5,main], id: 58
11-25 14:31:24.786  5537  5585 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-58,5,main], id: 58
11-25 14:31:24.786  5537  5585 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-25 14:31:24.786  5537  5585 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-25 14:31:24.787  5537  5585 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-25 14:31:24.787  5537  5585 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-25 14:31:24.787  5537  5537 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-25 14:31:24.787  5537  5585 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@51ee13c not in the list
11-25 14:31:24.787  5537  5585 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 14:31:24.787  5537  5585 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@72e5ec5 not in the list
11-25 14:31:24.787  5537  5585 D io.jxcore.node.ConnectivityMonitor: stop
11-25 14:31:24.787  5537  5537 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-25 14:31:24.787  5537  5585 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
11-25 14:31:24.788  5537  5537 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-25 14:31:24.788  5537  5537 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-25 14:31:24.789  5537  5537 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-25 14:31:24.789  5537  5537 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
11-25 14:31:24.789  5537  5537 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-25 14:31:24.789  5537  5537 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-25 14:31:24.790  5537  5537 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-25 14:31:24.790  5537  5537 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-25 14:31:24.790  5537  5537 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED] Current thread: Thread[main,5,main], id: 1
11-25 14:31:24.790  5537  5537 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-25 14:31:24.793  5537  5537 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
,11-25 14:31:24.794  5537  5537 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-25 14:31:24.794  5537  5537 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-25 14:31:24.798  4515  4515 D BtGatt.ScanManager: awakened up at time 86341
,11-25 14:31:24.834  4515  4578 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=6
,11-25 14:31:24.834  4515  4578 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-25 14:31:24.834  4515  4578 D BtGatt.GattService: current time is 86377438866
,11-25 14:31:24.835  4515  4578 D BtGatt.GattService: Batch record : [81, 34, 97, 112, -14, -5, 1, -128, -87, 18, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 37, -47, 14, -113, 116, -46, 1, -128, -88, 16, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 35, 97, 126, -92, 22, -56, 1, -128, -90, 25, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 71, -122, -77, 84, 69, -12, 1, -128, -83, 86, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 116, -43, -111, -91, -20, -29, 1, -128, -79, 19, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, -46, -4, -117, 6, 105, -37, 1, -128, -80, 23, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
,11-25 14:31:24.836  4515  4578 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
,11-25 14:31:24.837  4515  4578 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,11-25 14:31:24.838  4515  4578 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
11-25 14:31:24.838  4515  4578 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
11-25 14:31:24.838  4515  4578 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
11-25 14:31:24.838  4515  4578 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
11-25 14:31:24.842  4515  4578 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
11-25 14:31:24.842  4515  4578 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-25 14:31:24.843  4515  4581 D BtGatt.ScanManager: stopping BLe Batch
,11-25 14:31:24.848  4515  4578 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,11-25 14:31:24.848  4515  4578 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-25 14:31:24.848  4515  4581 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-25 14:31:24.852  4515  4578 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,11-25 14:31:24.852  4515  4578 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-25 14:31:24.900  4697  4747 D Finsky  : [184] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,11-25 14:31:24.901  4697  4697 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,11-25 14:31:24.904   929   939 I ActivityManager: Killing 5115:org.codeaurora.ims/1001 (adj 15): empty #17
,11-25 14:31:24.935   577   577 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 14:31:25.291  5537  5537 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-25 14:31:25.936   577   577 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 14:31:26.937   577   577 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,11-25 14:31:28.906   929  2910 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,11-25 14:31:29.800  5537  5585 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,11-25 14:31:29.806  5537  5585 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,11-25 14:31:29.807  5537  5585 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
,11-25 14:31:29.821  5537  5585 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-25 14:31:29.821  5537  5585 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-25 14:31:29.821  5537  5585 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-25 14:31:29.821  5537  5585 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-25 14:31:29.821  5537  5585 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-25 14:31:29.821  5537  5585 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-25 14:31:29.821  5537  5585 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-25 14:31:29.821  5537  5585 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-25 14:31:29.821  5537  5585 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,11-25 14:31:29.825  5537  5585 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
11-25 14:31:29.825  5537  5585 D io.jxcore.node.ConnectivityMonitor: start: OK
11-25 14:31:29.826  5537  5585 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-25 14:31:29.826  5537  5585 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
11-25 14:31:29.826  5537  5585 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
11-25 14:31:29.826  5537  5585 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-25 14:31:29.826  5537  5585 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,11-25 14:31:29.830  5537  5537 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-25 14:31:29.831  5537  5585 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
,11-25 14:31:29.832  5537  5585 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-25 14:31:29.832  5537  5585 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
11-25 14:31:29.834  5537  5537 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-25 14:31:29.837  5537  5585 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-58,5,main], id: 58
,11-25 14:31:29.837  5537  5585 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-25 14:31:29.838  5537  5585 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-25 14:31:29.838  5537  5585 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-25 14:31:29.838  5537  5585 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 0
,11-25 14:31:29.841  5537  5585 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-58,5,main], id: 58
11-25 14:31:29.841  5537  5585 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
11-25 14:31:29.842  5537  5585 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
11-25 14:31:29.842  5537  5585 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
11-25 14:31:29.842  5537  5585 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
11-25 14:31:29.842  5537  5585 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-58,5,main], id: 58
,11-25 14:31:29.842  5537  5585 D BluetoothAdapter: STATE_ON
11-25 14:31:29.844  4515  4529 D BtGatt.GattService: registerClient() - UUID=3e4c4ac2-d626-41ea-b323-dcce6f43a27f
11-25 14:31:29.845  4515  4578 D BtGatt.GattService: onClientRegistered() - UUID=3e4c4ac2-d626-41ea-b323-dcce6f43a27f, clientIf=5
11-25 14:31:29.845  5537  5548 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
11-25 14:31:29.845  4515  4722 D BtGatt.GattService: start scan with filters
,11-25 14:31:29.848  4515  4581 D BtGatt.ScanManager: handling starting scan
11-25 14:31:29.849  5537  5585 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
,11-25 14:31:29.849  5537  5585 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-58,5,main], id: 58
,11-25 14:31:29.849  5537  5585 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
11-25 14:31:29.850  5537  5585 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-58,5,main], id: 58
11-25 14:31:29.850  5537  5585 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-25 14:31:29.850  5537  5537 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-25 14:31:29.850  5537  5537 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-25 14:31:29.850  5537  5537 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
11-25 14:31:29.850  5537  5537 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
,11-25 14:31:29.850  5537  5537 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-25 14:31:29.850  5537  5537 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
11-25 14:31:29.850  5537  5537 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-25 14:31:29.851  5537  5537 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING] Current thread: Thread[main,5,main], id: 1
11-25 14:31:29.851  5537  5585 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-25 14:31:29.851  5537  5585 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-58,5,main], id: 58
11-25 14:31:29.855  5537  5585 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-58,5,main], id: 58
,11-25 14:31:29.855  4515  4578 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
11-25 14:31:29.855  4515  4578 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-25 14:31:29.855  5537  5585 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
11-25 14:31:29.855  5537  5585 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-58,5,main], id: 58
11-25 14:31:29.855  4515  4581 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
11-25 14:31:29.856  5537  5585 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-58,5,main], id: 58
11-25 14:31:29.856  5537  5585 I io.jxcore.node.ConnectionHelper: start: OK
11-25 14:31:29.856  5537  5537 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
,11-25 14:31:29.859  5537  5537 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
,11-25 14:31:29.859  5537  5537 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-25 14:31:29.859  5537  5537 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-25 14:31:29.860  5537  5537 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,11-25 14:31:29.861  4515  4578 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
11-25 14:31:29.861  4515  4578 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-25 14:31:29.861  4515  4581 D BtGatt.ScanManager: Starting BLE batch scan
11-25 14:31:29.861  4515  4581 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,11-25 14:31:29.862  5537  5585 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-25 14:31:29.862  5537  5585 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
11-25 14:31:29.863  5537  5585 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
11-25 14:31:29.863  5537  5585 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,11-25 14:31:29.863  5537  5585 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-25 14:31:29.863  5537  5585 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-25 14:31:29.863  5537  5585 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-25 14:31:29.863  5537  5585 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
11-25 14:31:29.863  5537  5585 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-25 14:31:29.863  5537  5585 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-58,5,main], id: 58
11-25 14:31:29.863  5537  5585 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
,11-25 14:31:29.863  5537  5585 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-25 14:31:29.863  5537  5585 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-58,5,main], id: 58
11-25 14:31:29.863  5537  5585 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-58,5,main], id: 58
11-25 14:31:29.863  5537  5585 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-58,5,main], id: 58
,11-25 14:31:29.863  5537  5585 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
11-25 14:31:29.863  5537  5585 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-58,5,main], id: 58
11-25 14:31:29.864  5537  5585 D BluetoothAdapter: STATE_ON
11-25 14:31:29.864  4515  4721 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
11-25 14:31:29.864  5537  5585 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-25 14:31:29.865  5537  5585 D BluetoothAdapter: STATE_ON
11-25 14:31:29.866  4515  4529 D BtGatt.GattService: stopScan() - queue size =1
11-25 14:31:29.866  4515  4722 D BtGatt.GattService: unregisterClient() - clientIf=5
11-25 14:31:29.867  5537  5585 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-25 14:31:29.867  5537  5585 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-58,5,main], id: 58
11-25 14:31:29.867  5537  5585 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
11-25 14:31:29.867  5537  5585 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-58,5,main], id: 58
11-25 14:31:29.867  5537  5585 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-58,5,main], id: 58
11-25 14:31:29.867  5537  5585 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-58,5,main], id: 58
11-25 14:31:29.867  5537  5585 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-58,5,main], id: 58
11-25 14:31:29.867  5537  5585 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-25 14:31:29.867  5537  5585 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-58,5,main], id: 58
11-25 14:31:29.868  5537  5585 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-58,5,main], id: 58
11-25 14:31:29.868  5537  5585 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-58,5,main], id: 58
11-25 14:31:29.868  5537  5585 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-25 14:31:29.868  5537  5585 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,11-25 14:31:29.869  5537  5585 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-25 14:31:29.869  5537  5585 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-58,5,main], id: 58
11-25 14:31:29.870  5537  5585 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-58,5,main], id: 58
11-25 14:31:29.870  5537  5585 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-25 14:31:29.870  5537  5585 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-58,5,main], id: 58
11-25 14:31:29.870  4515  4578 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
11-25 14:31:29.870  4515  4578 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-25 14:31:29.870  5537  5585 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-58,5,main], id: 58
11-25 14:31:29.870  5537  5585 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-25 14:31:29.871  5537  5537 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-25 14:31:29.871  5537  5585 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-25 14:31:29.871  5537  5585 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-25 14:31:29.871  5537  5537 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-25 14:31:29.871  5537  5585 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-25 14:31:29.871  5537  5585 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@51ee13c not in the list
,11-25 14:31:29.871  5537  5537 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-25 14:31:29.871  5537  5585 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 14:31:29.871  5537  5537 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-25 14:31:29.871  5537  5585 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@72e5ec5 not in the list
11-25 14:31:29.871  5537  5585 D io.jxcore.node.ConnectivityMonitor: stop
11-25 14:31:29.871  5537  5537 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-25 14:31:29.871  5537  5585 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
,11-25 14:31:29.871  5537  5537 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
11-25 14:31:29.871  5537  5537 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-25 14:31:29.871  5537  5537 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-25 14:31:29.871  5537  5537 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-25 14:31:29.871  5537  5537 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-25 14:31:29.871  5537  5537 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED] Current thread: Thread[main,5,main], id: 1
11-25 14:31:29.871  5537  5537 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-25 14:31:29.873  5537  5537 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-25 14:31:29.873  5537  5537 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-25 14:31:29.873  5537  5537 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-25 14:31:29.874  5537  5585 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-58,5,main], id: 58
11-25 14:31:29.874  5537  5585 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-58,5,main], id: 58
11-25 14:31:29.875  5537  5585 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-58,5,main], id: 58
11-25 14:31:29.875  5537  5585 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-58,5,main], id: 58
11-25 14:31:29.875  5537  5585 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-58,5,main], id: 58
11-25 14:31:29.875  5537  5585 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-25 14:31:29.875  5537  5585 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-25 14:31:29.875  5537  5585 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 14:31:29.875  5537  5585 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@72e5ec5 not in the list
11-25 14:31:29.876  5537  5585 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
11-25 14:31:29.876  4515  4578 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
11-25 14:31:29.876  4515  4578 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-25 14:31:29.878  5537  5585 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-25 14:31:29.878  5537  5585 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
11-25 14:31:29.879  4515  4581 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
11-25 14:31:29.885  4515  4578 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-25 14:31:29.885  4515  4578 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-25 14:31:29.885  4515  4578 E BtGatt.ContextMap: Context not found for ID 5
11-25 14:31:29.887  5537  5585 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-25 14:31:29.887  5537  5585 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-25 14:31:29.887  5537  5585 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-25 14:31:29.887  5537  5585 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-25 14:31:29.887  5537  5585 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-25 14:31:29.887  5537  5585 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-25 14:31:29.887  5537  5585 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-25 14:31:29.887  5537  5585 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-25 14:31:29.887  5537  5585 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,11-25 14:31:29.889  5537  5585 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
,11-25 14:31:29.890  5537  5585 D io.jxcore.node.ConnectivityMonitor: start: OK
11-25 14:31:29.890  5537  5585 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-25 14:31:29.890  5537  5585 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
11-25 14:31:29.890  5537  5585 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
11-25 14:31:29.890  5537  5585 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-25 14:31:29.890  5537  5585 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
11-25 14:31:29.893  4515  4578 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
11-25 14:31:29.893  4515  4578 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-25 14:31:29.893  4515  4581 D BtGatt.ScanManager: stopping BLe Batch
11-25 14:31:29.893  5537  5585 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-25 14:31:29.893  5537  5585 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-25 14:31:29.893  5537  5585 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
11-25 14:31:29.894  5537  5537 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-25 14:31:29.896  5537  5585 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-58,5,main], id: 58
11-25 14:31:29.896  5537  5537 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-25 14:31:29.897  5537  5585 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-25 14:31:29.897  5537  5585 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,11-25 14:31:29.897  5537  5585 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,11-25 14:31:29.897  5537  5585 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 0
11-25 14:31:29.898  4515  4578 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
11-25 14:31:29.898  4515  4578 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-25 14:31:29.899  4515  4581 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
11-25 14:31:29.900  5537  5585 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-58,5,main], id: 58
11-25 14:31:29.900  5537  5585 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
11-25 14:31:29.900  5537  5585 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
11-25 14:31:29.901  5537  5585 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
11-25 14:31:29.901  5537  5585 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,11-25 14:31:29.901  5537  5585 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-58,5,main], id: 58
11-25 14:31:29.901  5537  5585 D BluetoothAdapter: STATE_ON
11-25 14:31:29.903  4515  4578 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,11-25 14:31:29.903  4515  4578 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-25 14:31:29.903  4515  4714 D BtGatt.GattService: registerClient() - UUID=d8e9274c-358f-4d6d-b787-ababa62ea212
11-25 14:31:29.904  4515  4578 D BtGatt.GattService: onClientRegistered() - UUID=d8e9274c-358f-4d6d-b787-ababa62ea212, clientIf=5
,11-25 14:31:29.904  5537  5548 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
11-25 14:31:29.904  4515  4527 D BtGatt.GattService: start scan with filters
,11-25 14:31:29.906  4515  4581 D BtGatt.ScanManager: handling starting scan
,11-25 14:31:29.907  5537  5585 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
11-25 14:31:29.907  5537  5585 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-58,5,main], id: 58
11-25 14:31:29.907  5537  5585 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
11-25 14:31:29.907  5537  5585 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-58,5,main], id: 58
11-25 14:31:29.907  5537  5585 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-25 14:31:29.907  5537  5537 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-25 14:31:29.907  5537  5537 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
,11-25 14:31:29.907  5537  5537 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
11-25 14:31:29.907  5537  5537 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-25 14:31:29.907  5537  5537 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-25 14:31:29.907  5537  5537 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
11-25 14:31:29.908  5537  5537 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-25 14:31:29.908  5537  5537 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING] Current thread: Thread[main,5,main], id: 1
,11-25 14:31:29.908  5537  5585 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-25 14:31:29.909  5537  5585 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-58,5,main], id: 58
11-25 14:31:29.911  5537  5585 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-58,5,main], id: 58
11-25 14:31:29.911  5537  5585 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
11-25 14:31:29.911  5537  5585 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-58,5,main], id: 58
11-25 14:31:29.911  5537  5585 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-58,5,main], id: 58
11-25 14:31:29.911  5537  5585 I io.jxcore.node.ConnectionHelper: start: OK
11-25 14:31:29.911  5537  5537 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
,11-25 14:31:29.913  4515  4578 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,11-25 14:31:29.913  4515  4578 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-25 14:31:29.914  4515  4581 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
11-25 14:31:29.914  5537  5537 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
,11-25 14:31:29.914  5537  5537 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-25 14:31:29.914  5537  5537 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-25 14:31:29.914  5537  5537 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,11-25 14:31:29.919  4515  4578 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
11-25 14:31:29.919  4515  4578 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-25 14:31:29.919  4515  4581 D BtGatt.ScanManager: Starting BLE batch scan
11-25 14:31:29.919  4515  4581 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,11-25 14:31:29.928  4515  4578 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,11-25 14:31:29.928  4515  4578 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-25 14:31:29.933  4515  4578 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
11-25 14:31:29.933  4515  4578 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-25 14:31:30.416  5537  5537 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
11-25 14:31:30.416  5537  5537 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,11-25 14:31:30.416  5537  5537 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,11-25 14:31:31.926   929  2910 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,11-25 14:31:34.912  5537  5585 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-25 14:31:34.912  5537  5585 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
11-25 14:31:34.912  5537  5585 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
11-25 14:31:34.912  5537  5585 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-25 14:31:34.913  5537  5585 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-25 14:31:34.913  5537  5585 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-25 14:31:34.913  5537  5585 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
11-25 14:31:34.913  5537  5585 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-25 14:31:34.913  5537  5585 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-58,5,main], id: 58
11-25 14:31:34.913  5537  5585 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
,11-25 14:31:34.914  5537  5585 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-25 14:31:34.914  5537  5585 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-58,5,main], id: 58
11-25 14:31:34.915  5537  5585 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-58,5,main], id: 58
11-25 14:31:34.915  5537  5585 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-58,5,main], id: 58
11-25 14:31:34.915  5537  5585 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,11-25 14:31:34.915  5537  5585 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-58,5,main], id: 58
11-25 14:31:34.918  5537  5585 D BluetoothAdapter: STATE_ON
11-25 14:31:34.918  4515  4527 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
11-25 14:31:34.919  5537  5585 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
,11-25 14:31:34.921  5537  5585 D BluetoothAdapter: STATE_ON
,11-25 14:31:34.922  4515  4581 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-25 14:31:34.923  4515  4529 D BtGatt.GattService: stopScan() - queue size =1
,11-25 14:31:34.924  4515  4721 D BtGatt.GattService: unregisterClient() - clientIf=5
11-25 14:31:34.925  5537  5585 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-25 14:31:34.925  5537  5585 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-58,5,main], id: 58
11-25 14:31:34.925  5537  5585 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,11-25 14:31:34.926  5537  5585 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-58,5,main], id: 58
11-25 14:31:34.926  5537  5585 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-58,5,main], id: 58
11-25 14:31:34.926  5537  5585 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-58,5,main], id: 58
11-25 14:31:34.926  5537  5585 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-58,5,main], id: 58
11-25 14:31:34.926  5537  5585 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,11-25 14:31:34.927  5537  5585 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-58,5,main], id: 58
11-25 14:31:34.927  5537  5585 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-58,5,main], id: 58
11-25 14:31:34.927  5537  5585 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-58,5,main], id: 58
11-25 14:31:34.927  5537  5585 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-25 14:31:34.928  5537  5585 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-25 14:31:34.929  4515  4515 D BtGatt.ScanManager: awakened up at time 96471
,11-25 14:31:34.929  5537  5585 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-25 14:31:34.929  5537  5585 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-58,5,main], id: 58
11-25 14:31:34.931   929  3337 I ActivityManager: Killing 5181:com.android.settings/1000 (adj 15): empty #17
11-25 14:31:34.933  5537  5585 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-58,5,main], id: 58
11-25 14:31:34.933  5537  5585 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-25 14:31:34.933  5537  5585 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-58,5,main], id: 58
11-25 14:31:34.933  5537  5585 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-58,5,main], id: 58
,11-25 14:31:34.933  5537  5537 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-25 14:31:34.933  5537  5537 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-25 14:31:34.934  5537  5537 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-25 14:31:34.934  5537  5537 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-25 14:31:34.934  5537  5537 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
,11-25 14:31:34.934  5537  5537 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
11-25 14:31:34.934  5537  5537 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-25 14:31:34.934  5537  5537 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-25 14:31:34.934  5537  5537 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-25 14:31:34.935  5537  5537 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,11-25 14:31:34.935  5537  5537 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED] Current thread: Thread[main,5,main], id: 1
11-25 14:31:34.935  5537  5537 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-25 14:31:34.937  5537  5537 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-25 14:31:34.937  5537  5537 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-25 14:31:34.937  5537  5537 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
,11-25 14:31:34.973  4515  4578 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=6
,11-25 14:31:34.973  4515  4578 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-25 14:31:34.973  4515  4578 D BtGatt.GattService: current time is 96515869347
11-25 14:31:34.973  4515  4578 D BtGatt.GattService: Batch record : [116, -43, -111, -91, -20, -29, 1, -128, -79, 23, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 37, -47, 14, -113, 116, -46, 1, -128, -88, 14, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 71, -122, -77, 84, 69, -12, 1, -128, -89, 15, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 35, 97, 126, -92, 22, -56, 1, -128, -90, 11, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 81, 34, 97, 112, -14, -5, 1, -128, -86, 21, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, -46, -4, -117, 6, 105, -37, 1, -128, -80, 25, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
11-25 14:31:34.973  4515  4578 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,11-25 14:31:34.974  4515  4578 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
11-25 14:31:34.974  4515  4578 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
11-25 14:31:34.974  4515  4578 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
11-25 14:31:34.975  4515  4578 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
11-25 14:31:34.975  4515  4578 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
,11-25 14:31:34.981  4515  4578 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
,11-25 14:31:34.981  4515  4578 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-25 14:31:34.981  4515  4581 D BtGatt.ScanManager: stopping BLe Batch
,11-25 14:31:34.986  4515  4578 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,11-25 14:31:34.986  4515  4578 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-25 14:31:34.987  4515  4581 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-25 14:31:34.992  4515  4578 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-25 14:31:34.993  4515  4578 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-25 14:31:35.435  5537  5537 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-25 14:31:35.436  5537  5537 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-25 14:31:35.436  5537  5537 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,11-25 14:31:35.682   929  5280 D NetlinkSocketObserver: NeighborEvent{elapsedMs=97224, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,11-25 14:31:37.974   929  2910 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,11-25 14:31:39.935  5537  5585 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-25 14:31:39.935  5537  5585 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,11-25 14:31:39.935  5537  5585 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-25 14:31:39.935  5537  5585 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-25 14:31:39.936  5537  5585 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,11-25 14:31:39.936  5537  5585 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-25 14:31:39.936  5537  5585 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,11-25 14:31:39.936  5537  5585 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@51ee13c not in the list
11-25 14:31:39.936  5537  5585 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 14:31:39.936  5537  5585 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@72e5ec5 not in the list
,11-25 14:31:39.936  5537  5585 D io.jxcore.node.ConnectivityMonitor: stop
11-25 14:31:39.937  5537  5585 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
11-25 14:31:39.939  5537  5585 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-58,5,main], id: 58
11-25 14:31:39.939  5537  5585 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-58,5,main], id: 58
,11-25 14:31:39.943  5537  5585 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-58,5,main], id: 58
11-25 14:31:39.943  5537  5585 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-58,5,main], id: 58
11-25 14:31:39.943  5537  5585 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-58,5,main], id: 58
11-25 14:31:39.943  5537  5585 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-25 14:31:39.943  5537  5585 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-25 14:31:39.943  5537  5585 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-25 14:31:39.944  5537  5585 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@72e5ec5 not in the list
11-25 14:31:39.945  5537  5585 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
,11-25 14:31:39.947  5537  5585 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-25 14:31:39.947  5537  5585 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,11-25 14:31:39.947  5537  5585 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-25 14:31:39.948  5537  5585 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-25 14:31:39.948  5537  5585 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-25 14:31:39.948  5537  5585 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@51ee13c not in the list
,11-25 14:31:39.948  5537  5585 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 14:31:39.948  5537  5585 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@72e5ec5 not in the list
11-25 14:31:39.948  5537  5585 D io.jxcore.node.ConnectivityMonitor: stop
11-25 14:31:39.949  5537  5585 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-58,5,main], id: 58
,11-25 14:31:39.949  5537  5585 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-58,5,main], id: 58
11-25 14:31:39.952  5537  5585 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-58,5,main], id: 58
11-25 14:31:39.952  5537  5585 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-58,5,main], id: 58
11-25 14:31:39.953  5537  5585 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-58,5,main], id: 58
,11-25 14:31:39.953  5537  5585 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-25 14:31:39.953  5537  5585 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-25 14:31:39.953  5537  5585 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-25 14:31:39.953  5537  5585 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@72e5ec5 not in the list
11-25 14:31:39.956  5537  5585 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
,11-25 14:31:39.956  5537  5585 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-25 14:31:39.956  5537  5585 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-25 14:31:39.956  5537  5585 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-25 14:31:39.956  5537  5585 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-25 14:31:39.957  5537  5585 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,11-25 14:31:39.957  5537  5585 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@51ee13c not in the list
11-25 14:31:39.957  5537  5585 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 14:31:39.957  5537  5585 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@72e5ec5 not in the list
11-25 14:31:39.957  5537  5585 D io.jxcore.node.ConnectivityMonitor: stop
11-25 14:31:39.957  5537  5585 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-58,5,main], id: 58
,11-25 14:31:39.957  5537  5585 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-58,5,main], id: 58
11-25 14:31:39.958  5537  5585 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-58,5,main], id: 58
11-25 14:31:39.958  5537  5585 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-58,5,main], id: 58
11-25 14:31:39.958  5537  5585 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-58,5,main], id: 58
11-25 14:31:39.959  5537  5585 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-25 14:31:39.959  5537  5585 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,11-25 14:31:39.959  5537  5585 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 14:31:39.959  5537  5585 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@72e5ec5 not in the list
11-25 14:31:39.959  5537  5585 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
11-25 14:31:39.960  5537  5585 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-25 14:31:39.960  5537  5585 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-25 14:31:39.960  5537  5585 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-25 14:31:39.960  5537  5585 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-25 14:31:39.960  5537  5585 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,11-25 14:31:39.960  5537  5585 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@51ee13c not in the list
11-25 14:31:39.960  5537  5585 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 14:31:39.960  5537  5585 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@72e5ec5 not in the list
11-25 14:31:39.960  5537  5585 D io.jxcore.node.ConnectivityMonitor: stop
,11-25 14:31:39.961  5537  5585 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-58,5,main], id: 58
11-25 14:31:39.961  5537  5585 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-58,5,main], id: 58
11-25 14:31:39.962  5537  5585 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-58,5,main], id: 58
11-25 14:31:39.962  5537  5585 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-58,5,main], id: 58
11-25 14:31:39.962  5537  5585 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-58,5,main], id: 58
11-25 14:31:39.962  5537  5585 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,11-25 14:31:39.962  5537  5585 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-25 14:31:39.962  5537  5585 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 14:31:39.962  5537  5585 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@72e5ec5 not in the list
11-25 14:31:39.963  5537  5585 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
11-25 14:31:39.963  5537  5585 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-25 14:31:39.964  5537  5585 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-25 14:31:39.964  5537  5585 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-25 14:31:39.964  5537  5585 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-25 14:31:39.964  5537  5585 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-25 14:31:39.964  5537  5585 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@51ee13c not in the list
11-25 14:31:39.964  5537  5585 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-25 14:31:39.964  5537  5585 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@72e5ec5 not in the list
11-25 14:31:39.964  5537  5585 D io.jxcore.node.ConnectivityMonitor: stop
11-25 14:31:39.964  5537  5585 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-58,5,main], id: 58
11-25 14:31:39.964  5537  5585 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-58,5,main], id: 58
11-25 14:31:39.966  5537  5585 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-58,5,main], id: 58
,11-25 14:31:39.966  5537  5585 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-58,5,main], id: 58
11-25 14:31:39.966  5537  5585 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-58,5,main], id: 58
11-25 14:31:39.966  5537  5585 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-25 14:31:39.966  5537  5585 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-25 14:31:39.966  5537  5585 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 14:31:39.966  5537  5585 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@72e5ec5 not in the list
,11-25 14:31:39.967  5537  5585 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
11-25 14:31:39.967  5537  5585 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-25 14:31:39.967  5537  5585 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-25 14:31:39.967  5537  5585 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
,11-25 14:31:39.968  5537  5585 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-25 14:31:39.968  5537  5585 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-25 14:31:39.968  5537  5585 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
11-25 14:31:39.968  5537  5585 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-25 14:31:39.968  5537  5585 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-25 14:31:39.968  5537  5585 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-25 14:31:39.968  5537  5585 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-25 14:31:39.968  5537  5585 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-25 14:31:39.968  5537  5585 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,11-25 14:31:39.968  5537  5585 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-25 14:31:39.968  5537  5585 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@51ee13c not in the list
11-25 14:31:39.969  5537  5585 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 14:31:39.969  5537  5585 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@72e5ec5 not in the list
11-25 14:31:39.969  5537  5585 D io.jxcore.node.ConnectivityMonitor: stop
11-25 14:31:39.969  5537  5585 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-58,5,main], id: 58
11-25 14:31:39.969  5537  5585 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-58,5,main], id: 58
,11-25 14:31:39.970  5537  5585 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-58,5,main], id: 58
11-25 14:31:39.970  5537  5585 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-58,5,main], id: 58
11-25 14:31:39.971  5537  5585 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-58,5,main], id: 58
11-25 14:31:39.971  5537  5585 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-25 14:31:39.971  5537  5585 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,11-25 14:31:39.971  5537  5585 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 14:31:39.971  5537  5585 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@72e5ec5 not in the list
11-25 14:31:39.972  5537  5585 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
11-25 14:31:39.972  5537  5585 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
11-25 14:31:39.972  5537  5585 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
11-25 14:31:39.975  5537  5585 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
11-25 14:31:39.975  5537  5585 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
11-25 14:31:39.975  5537  5585 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
11-25 14:31:39.976  5537  5585 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
,11-25 14:31:39.976  5537  5585 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
11-25 14:31:39.976  5537  5585 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
11-25 14:31:39.976  5537  5585 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
11-25 14:31:39.976  5537  5585 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
11-25 14:31:39.976  5537  5585 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
11-25 14:31:39.976  5537  5585 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
11-25 14:31:39.976  5537  5585 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
11-25 14:31:39.976  5537  5585 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
11-25 14:31:39.976  5537  5585 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
11-25 14:31:39.976  5537  5585 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
11-25 14:31:39.976  5537  5585 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
,11-25 14:31:39.976  5537  5585 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
11-25 14:31:39.976  5537  5585 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
11-25 14:31:39.976  5537  5585 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
11-25 14:31:39.976  5537  5585 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
11-25 14:31:39.976  5537  5585 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
11-25 14:31:39.976  5537  5585 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
11-25 14:31:39.976  5537  5585 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
11-25 14:31:39.976  5537  5585 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
11-25 14:31:39.976  5537  5585 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
11-25 14:31:39.977  5537  5585 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
11-25 14:31:39.977  5537  5585 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
,11-25 14:31:39.977  5537  5585 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
11-25 14:31:39.977  5537  5585 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
11-25 14:31:39.977  5537  5585 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
11-25 14:31:39.977  5537  5585 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
11-25 14:31:39.977  5537  5585 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
11-25 14:31:39.977  5537  5585 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
11-25 14:31:39.977  5537  5585 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
11-25 14:31:39.977  5537  5585 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
11-25 14:31:39.978  5537  5585 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
11-25 14:31:39.978  5537  5585 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
11-25 14:31:39.978  5537  5585 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
,11-25 14:31:39.978  5537  5585 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
11-25 14:31:39.978  5537  5585 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
11-25 14:31:39.978  5537  5585 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
11-25 14:31:39.978  5537  5585 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
,11-25 14:31:39.982  5537  5585 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
11-25 14:31:39.983  5537  5585 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
11-25 14:31:39.983  5537  5585 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
11-25 14:31:39.984  5537  5585 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
11-25 14:31:39.984  5537  5585 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
,11-25 14:31:39.984  5537  5585 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
11-25 14:31:39.984  5537  5585 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
11-25 14:31:39.984  5537  5585 E io.jxcore.node.ConnectionHelper: connect: Callback is null
11-25 14:31:39.985  5537  5600 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 123)
11-25 14:31:39.985  5537  5600 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: tryToConnect:  socketConnectSucceeded = false, mIsShuttingDown = false
11-25 14:31:39.985  5537  5600 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: socket closed
11-25 14:31:39.985  5537  5600 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: SYSTEM_DECIDED_INSECURE_RFCOMM_SOCKET_PORT
11-25 14:31:39.985  5537  5585 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-25 14:31:39.985  5537  5585 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-25 14:31:39.985  5537  5585 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-25 14:31:39.986  5537  5585 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,11-25 14:31:39.986  5537  5585 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-25 14:31:39.986  5537  5585 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
,11-25 14:31:39.986  5537  5585 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@51ee13c not in the list
11-25 14:31:39.987  5537  5585 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-25 14:31:39.987  5537  5585 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@72e5ec5 not in the list
11-25 14:31:39.987  5537  5585 D io.jxcore.node.ConnectivityMonitor: stop
11-25 14:31:39.987  5537  5585 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-58,5,main], id: 58
11-25 14:31:39.987  5537  5585 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-58,5,main], id: 58
11-25 14:31:39.987  5537  5600 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: connecting
11-25 14:31:39.988  5537  5600 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-25 14:31:39.988  5537  5601 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 123
11-25 14:31:39.988  5537  5601 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close
11-25 14:31:39.988  5537  5601 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Trying to close the Bluetooth socket... (thread ID: 123)
11-25 14:31:39.988  5537  5601 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Bluetooth socket closed (thread ID: 123)
,11-25 14:31:39.985  4527  4527 W Binder_1: type=1400 audit(0.0:113): avc: denied { ioctl } for path="socket:[32129]" dev="sockfs" ino=32129 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-25 14:31:39.985  4527  4527 W Binder_1: type=1400 audit(0.0:114): avc: denied { ioctl } for path="socket:[32129]" dev="sockfs" ino=32129 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-25 14:31:39.989  5537  5585 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-58,5,main], id: 58
,11-25 14:31:39.989  5537  5585 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-58,5,main], id: 58
11-25 14:31:39.989  5537  5585 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-58,5,main], id: 58
11-25 14:31:39.989  5537  5585 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-25 14:31:39.989  5537  5585 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-25 14:31:39.989  5537  5585 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 14:31:39.989  5537  5585 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@72e5ec5 not in the list
11-25 14:31:39.990  5537  5585 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
11-25 14:31:39.990  5537  5600 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: connect, socket closed
11-25 14:31:39.990  5537  5600 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: socketConnectSucceeded false
11-25 14:31:39.990  5537  5600 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 123)
11-25 14:31:39.991  5537  5585 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-25 14:31:39.991  5537  5585 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-25 14:31:39.991  5537  5585 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-25 14:31:39.991  5537  5585 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-25 14:31:39.991  5537  5585 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-25 14:31:39.991  5537  5585 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@51ee13c not in the list
11-25 14:31:39.991  5537  5585 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 14:31:39.991  5537  5585 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@72e5ec5 not in the list
11-25 14:31:39.991  5537  5585 D io.jxcore.node.ConnectivityMonitor: stop
,11-25 14:31:39.991  5537  5585 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-58,5,main], id: 58
11-25 14:31:39.991  5537  5585 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-58,5,main], id: 58
11-25 14:31:39.992  5537  5585 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-58,5,main], id: 58
11-25 14:31:39.992  5537  5585 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-58,5,main], id: 58
11-25 14:31:39.992  5537  5585 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-58,5,main], id: 58
11-25 14:31:39.992  5537  5585 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-25 14:31:39.993  5537  5585 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-25 14:31:39.993  5537  5585 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 14:31:39.993  5537  5585 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@72e5ec5 not in the list
11-25 14:31:39.993  5537  5585 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
11-25 14:31:39.994  5537  5585 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-25 14:31:39.994  5537  5585 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-25 14:31:39.994  5537  5585 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-25 14:31:39.994  5537  5585 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-25 14:31:39.994  5537  5585 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-25 14:31:39.994  5537  5585 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@51ee13c not in the list
11-25 14:31:39.994  5537  5585 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 14:31:39.994  5537  5585 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@72e5ec5 not in the list
11-25 14:31:39.994  5537  5585 D io.jxcore.node.ConnectivityMonitor: stop
11-25 14:31:39.994  5537  5585 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-58,5,main], id: 58
11-25 14:31:39.994  5537  5585 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-58,5,main], id: 58
,11-25 14:31:39.997  5537  5585 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-58,5,main], id: 58
11-25 14:31:39.997  5537  5585 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-58,5,main], id: 58
,11-25 14:31:39.997  5537  5585 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-58,5,main], id: 58
11-25 14:31:39.997  5537  5585 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-25 14:31:39.997  5537  5585 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-25 14:31:39.997  5537  5585 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 14:31:39.997  5537  5585 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@72e5ec5 not in the list
11-25 14:31:39.998  5537  5585 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
11-25 14:31:39.998  5537  5585 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
11-25 14:31:39.998  5537  5585 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
,11-25 14:31:39.998  5537  5585 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
11-25 14:31:39.999  5537  5585 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
11-25 14:31:39.999  5537  5585 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
11-25 14:31:39.999  5537  5585 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
11-25 14:31:39.999  5537  5585 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
11-25 14:31:39.999  5537  5585 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
11-25 14:31:39.999  5537  5585 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
11-25 14:31:39.999  5537  5585 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
11-25 14:31:39.999  5537  5585 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
,11-25 14:31:39.999  5537  5585 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-25 14:31:39.999  5537  5585 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-25 14:31:39.999  5537  5585 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-25 14:31:39.999  5537  5585 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-25 14:31:39.999  5537  5585 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-25 14:31:40.000  5537  5585 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@51ee13c not in the list
11-25 14:31:40.000  5537  5585 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 14:31:40.000  5537  5585 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@72e5ec5 not in the list
11-25 14:31:40.000  5537  5585 D io.jxcore.node.ConnectivityMonitor: stop
11-25 14:31:40.000  5537  5585 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-58,5,main], id: 58
11-25 14:31:40.000  5537  5585 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-58,5,main], id: 58
,11-25 14:31:40.002  5537  5585 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-58,5,main], id: 58
11-25 14:31:40.002  5537  5585 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-58,5,main], id: 58
11-25 14:31:40.002  5537  5585 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-58,5,main], id: 58
11-25 14:31:40.002  5537  5585 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,11-25 14:31:40.002  5537  5585 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-25 14:31:40.002  5537  5585 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 14:31:40.002  5537  5585 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@72e5ec5 not in the list
,11-25 14:31:40.003  5537  5585 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-25 14:31:40.003  5537  5585 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-25 14:31:40.003  5537  5585 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@51ee13c not in the list
11-25 14:31:40.003  5537  5585 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 14:31:40.003  5537  5585 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@72e5ec5 not in the list
,11-25 14:31:40.003  5537  5585 D io.jxcore.node.ConnectivityMonitor: stop
,11-25 14:31:41.006   929  2910 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,11-25 14:31:44.034   929  2910 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,11-25 14:31:45.004  5537  5585 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-25 14:31:45.004  5537  5585 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@72e5ec5 not in the list
11-25 14:31:45.005  5537  5585 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,11-25 14:31:45.005  5537  5585 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,11-25 14:31:45.005  5537  5585 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@51ee13c not in the list
11-25 14:31:45.005  5537  5585 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-25 14:31:45.006  5537  5585 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-25 14:31:45.006  5537  5585 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-25 14:31:45.006  5537  5585 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-25 14:31:45.006  5537  5585 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,11-25 14:31:45.006  5537  5585 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@51ee13c not in the list
11-25 14:31:45.006  5537  5585 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 14:31:45.007  5537  5585 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@72e5ec5 not in the list
11-25 14:31:45.007  5537  5585 D io.jxcore.node.ConnectivityMonitor: stop
,11-25 14:31:45.007  5537  5585 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-58,5,main], id: 58
11-25 14:31:45.007  5537  5585 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-58,5,main], id: 58
,11-25 14:31:45.011  5537  5585 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-58,5,main], id: 58
,11-25 14:31:45.012  5537  5585 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-58,5,main], id: 58
11-25 14:31:45.012  5537  5585 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-58,5,main], id: 58
11-25 14:31:45.012  5537  5585 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-25 14:31:45.012  5537  5585 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,11-25 14:31:45.012  5537  5585 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 14:31:45.012  5537  5585 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@72e5ec5 not in the list
11-25 14:31:45.016  5537  5585 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
11-25 14:31:45.017  5537  5585 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,11-25 14:31:45.017  5537  5585 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
11-25 14:31:45.023  5537  5585 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,11-25 14:31:45.025  5537  5585 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,11-25 14:31:45.025  5537  5585 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
11-25 14:31:45.025  5537  5585 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
11-25 14:31:45.026  5537  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
11-25 14:31:45.026  5537  5585 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
11-25 14:31:45.026  5537  5537 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
,11-25 14:31:45.026  5537  5585 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
11-25 14:31:45.028  5537  5602 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-25 14:31:45.028  5537  5585 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-25 14:31:45.028  5537  5585 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
,11-25 14:31:45.028  5537  5585 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
11-25 14:31:45.028  5537  5585 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
11-25 14:31:45.029  5537  5585 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
,11-25 14:31:45.028  4714  4714 W Binder_3: type=1400 audit(0.0:115): avc: denied { ioctl } for path="socket:[32133]" dev="sockfs" ino=32133 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,11-25 14:31:45.028  4714  4714 W Binder_3: type=1400 audit(0.0:116): avc: denied { ioctl } for path="socket:[32133]" dev="sockfs" ino=32133 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,11-25 14:31:45.030  5537  5585 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
,11-25 14:31:45.031  5537  5585 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
11-25 14:31:45.031  5537  5585 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@51ee13c not in the list
,11-25 14:31:45.031  5537  5585 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 14:31:45.031  5537  5537 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
11-25 14:31:45.031  5537  5585 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-25 14:31:45.031  5537  5585 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-58,5,main], id: 58
,11-25 14:31:45.031  5537  5585 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
11-25 14:31:45.032  5537  5585 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,11-25 14:31:45.032  5537  5585 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-58,5,main], id: 58
11-25 14:31:45.034  5537  5585 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-58,5,main], id: 58
,11-25 14:31:45.034  5537  5585 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-25 14:31:45.035  5537  5585 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-58,5,main], id: 58
,11-25 14:31:45.035  5537  5585 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-58,5,main], id: 58
,11-25 14:31:45.035  5537  5602 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
11-25 14:31:45.035  5537  5585 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@72e5ec5 not in the list
,11-25 14:31:45.035  5537  5537 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,11-25 14:31:45.035  5537  5602 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
,11-25 14:31:45.035  5537  5585 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-25 14:31:45.035  5537  5602 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
11-25 14:31:45.035  5537  5537 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-25 14:31:45.035  5537  5585 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,11-25 14:31:45.035  5537  5537 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-25 14:31:45.036  5537  5585 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,11-25 14:31:45.036  5537  5585 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-25 14:31:45.036  5537  5585 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
11-25 14:31:45.036  5537  5585 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@51ee13c not in the list
,11-25 14:31:45.036  5537  5537 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,11-25 14:31:45.036  5537  5585 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 14:31:45.036  5537  5537 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-25 14:31:45.036  5537  5585 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@72e5ec5 not in the list
11-25 14:31:45.036  5537  5585 D io.jxcore.node.ConnectivityMonitor: stop
,11-25 14:31:45.037  5537  5585 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-58,5,main], id: 58
11-25 14:31:45.037  5537  5585 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-58,5,main], id: 58
11-25 14:31:45.039  5537  5585 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-58,5,main], id: 58
11-25 14:31:45.039  5537  5585 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-58,5,main], id: 58
11-25 14:31:45.040  5537  5585 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-58,5,main], id: 58
,11-25 14:31:45.040  5537  5585 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-25 14:31:45.040  5537  5585 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-25 14:31:45.040  5537  5585 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 14:31:45.040  5537  5585 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@72e5ec5 not in the list
11-25 14:31:45.044  5537  5585 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
,11-25 14:31:45.044  5537  5585 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
11-25 14:31:45.044  5537  5585 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
11-25 14:31:45.044  5537  5585 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-25 14:31:45.045  5537  5585 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-25 14:31:45.045  5537  5585 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-25 14:31:45.045  5537  5585 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-25 14:31:45.045  5537  5585 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-25 14:31:45.045  5537  5585 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-25 14:31:45.045  5537  5585 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,11-25 14:31:45.045  5537  5585 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@51ee13c not in the list
11-25 14:31:45.045  5537  5585 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 14:31:45.046  5537  5585 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@72e5ec5 not in the list
11-25 14:31:45.046  5537  5585 D io.jxcore.node.ConnectivityMonitor: stop
11-25 14:31:45.046  5537  5585 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-58,5,main], id: 58
,11-25 14:31:45.046  5537  5585 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-58,5,main], id: 58
11-25 14:31:45.048  5537  5585 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-58,5,main], id: 58
11-25 14:31:45.048  5537  5585 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-58,5,main], id: 58
11-25 14:31:45.048  5537  5585 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-58,5,main], id: 58
11-25 14:31:45.048  5537  5585 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,11-25 14:31:45.048  5537  5585 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-25 14:31:45.048  5537  5585 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 14:31:45.048  5537  5585 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@72e5ec5 not in the list
11-25 14:31:45.055  5537  5585 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-25 14:31:45.055  5537  5585 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,11-25 14:31:45.055  5537  5585 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-25 14:31:45.056  5537  5585 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,11-25 14:31:45.056  5537  5585 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-25 14:31:45.056  5537  5585 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@51ee13c not in the list
,11-25 14:31:45.056  5537  5585 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 14:31:45.056  5537  5585 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@72e5ec5 not in the list
11-25 14:31:45.056  5537  5585 D io.jxcore.node.ConnectivityMonitor: stop
11-25 14:31:45.056  5537  5585 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-58,5,main], id: 58
11-25 14:31:45.056  5537  5585 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-58,5,main], id: 58
,11-25 14:31:45.059  5537  5585 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-58,5,main], id: 58
,11-25 14:31:45.059  5537  5585 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-58,5,main], id: 58
11-25 14:31:45.060  5537  5585 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-58,5,main], id: 58
11-25 14:31:45.060  5537  5585 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-25 14:31:45.060  5537  5585 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-25 14:31:45.060  5537  5585 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 14:31:45.060  5537  5585 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@72e5ec5 not in the list
,11-25 14:31:45.061  5537  5585 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-25 14:31:45.061  5537  5585 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-25 14:31:45.061  5537  5585 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-25 14:31:45.062  5537  5585 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-25 14:31:45.062  5537  5585 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-25 14:31:45.062  5537  5585 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@51ee13c not in the list
,11-25 14:31:45.062  5537  5585 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 14:31:45.062  5537  5585 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@72e5ec5 not in the list
11-25 14:31:45.062  5537  5585 D io.jxcore.node.ConnectivityMonitor: stop
11-25 14:31:45.062  5537  5585 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-58,5,main], id: 58
11-25 14:31:45.062  5537  5585 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-58,5,main], id: 58
11-25 14:31:45.064  5537  5585 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-58,5,main], id: 58
,11-25 14:31:45.064  5537  5585 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-58,5,main], id: 58
11-25 14:31:45.064  5537  5585 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-58,5,main], id: 58
11-25 14:31:45.064  5537  5585 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-25 14:31:45.065  5537  5585 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-25 14:31:45.065  5537  5585 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 14:31:45.065  5537  5585 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@72e5ec5 not in the list
,11-25 14:31:45.066  5537  5585 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
11-25 14:31:45.066  5537  5585 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
11-25 14:31:45.066  5537  5585 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
11-25 14:31:45.066  5537  5585 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
11-25 14:31:45.066  5537  5585 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
11-25 14:31:45.066  5537  5585 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,11-25 14:31:45.069  5537  5585 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
,11-25 14:31:45.069  5537  5585 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
11-25 14:31:45.070  5537  5585 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
11-25 14:31:45.070  5537  5585 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
,11-25 14:31:45.070  5537  5585 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
11-25 14:31:45.070  5537  5585 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
11-25 14:31:45.070  5537  5585 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
11-25 14:31:45.070  5537  5585 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
,11-25 14:31:45.071  5537  5585 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
11-25 14:31:45.071  5537  5585 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
11-25 14:31:45.072  5537  5585 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
11-25 14:31:45.072  5537  5585 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
,11-25 14:31:45.072  5537  5585 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
11-25 14:31:45.072  5537  5585 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
11-25 14:31:45.073  5537  5585 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-25 14:31:45.073  5537  5585 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@82933ca added. We now have 3 listener(s)
,11-25 14:31:45.073  5537  5585 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-25 14:31:45.075  5537  5585 D BluetoothAdapter: enable(): BT is already enabled..!
11-25 14:31:45.075   929  3520 D WifiService: setWifiEnabled: true pid=5537, uid=10077
,11-25 14:31:45.075   929  3520 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-25 14:31:45.117  4515  4709 W bt_sdp  : SDP - Rcvd conn cnf with error: 0x4  CID 0x40
11-25 14:31:45.118  4515  4711 E bt_btif_sock_rfcomm: find_rfc_slot_by_id unable to find RFCOMM slot id: 5
,11-25 14:31:45.536  5537  5537 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-25 14:31:47.068   929  2910 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,11-25 14:31:50.081  5537  5585 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,11-25 14:31:50.081  5537  5585 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@f8ec93b added. We now have 4 listener(s)
11-25 14:31:50.081  5537  5585 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-25 14:31:50.093  5537  5585 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-25 14:31:50.094  5537  5585 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@f8ec93b removed from the list
11-25 14:31:50.094  5537  5585 D io.jxcore.node.ConnectivityMonitor: stop
11-25 14:31:50.096  5537  5585 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-25 14:31:50.096  5537  5585 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@fbdd858 added. We now have 4 listener(s)
,11-25 14:31:50.096  5537  5585 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-25 14:31:50.099  5537  5585 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 14:31:50.099  5537  5585 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@fbdd858 removed from the list
11-25 14:31:50.100  5537  5585 D io.jxcore.node.ConnectivityMonitor: stop
11-25 14:31:50.100   929  2910 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
11-25 14:31:50.102  5537  5585 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-25 14:31:50.102  5537  5585 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@7d01db1 added. We now have 4 listener(s)
11-25 14:31:50.102  5537  5585 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-25 14:31:50.107   929  3520 D WifiService: setWifiEnabled: false pid=5537, uid=10077
,11-25 14:31:50.107   929  3520 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-25 14:31:50.110   929  2907 D WifiStateMachine: WifiStateMachine: Leaving Connected state
11-25 14:31:50.111   929  2907 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
11-25 14:31:50.111   929  2907 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
11-25 14:31:50.111   929  2907 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-25 14:31:50.120  4515  4574 D BluetoothAdapterState: Current state: ON, message: 23
11-25 14:31:50.120  4515  4574 D BluetoothAdapterProperties: Setting state to 13
11-25 14:31:50.120  4515  4574 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,11-25 14:31:50.121  4515  4574 D BluetoothAdapterProperties: onBluetoothDisable()
11-25 14:31:50.122  4515  4574 I BluetoothAdapterState: Entering PendingCommandState
11-25 14:31:50.122  5537  5585 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-25 14:31:50.123  5537  5585 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
,11-25 14:31:50.125  4515  4515 D BluetoothMapService: onReceive
,11-25 14:31:50.125  4515  4515 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,11-25 14:31:50.125  4515  4515 D BluetoothMapService: STATE_TURNING_OFF
11-25 14:31:50.125  4515  4515 D BluetoothMapService: MAP Service closeService in
11-25 14:31:50.125  4515  4515 D BluetoothMapMasInstance0: MAP Service shutdown
11-25 14:31:50.125  4515  4515 D ObexServerSockets0: shutdown(block = true)
11-25 14:31:50.126  4515  4515 D ObexServerSockets0: shutdown called from another thread - interrupt().
11-25 14:31:50.126  4515  4515 D ObexServerSockets0: shutdown called from another thread - interrupt().
,11-25 14:31:50.127  4515  4724 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 5
,11-25 14:31:50.127  4515  4725 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
11-25 14:31:50.127  4515  4711 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
11-25 14:31:50.128  4515  4515 I BtOppRfcommListener: stopping Accept Thread
11-25 14:31:50.129  4515  5204 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
11-25 14:31:50.130   929  5281 D DhcpClient: Clearing IP address
11-25 14:31:50.130   506   922 D CommandListener: Clearing all IP addresses on wlan0
11-25 14:31:50.132  4515  5204 I BtOppRfcommListener: BluetoothSocket listen thread finished
11-25 14:31:50.138   506   922 D CommandListener: Setting iface cfg
,11-25 14:31:50.145   929  5282 D DhcpClient: Receive thread stopped
,11-25 14:31:50.148  3504  5333 V NativeCrypto: Read error: ssl=0x7fa8143f80: I/O error during system call, Connection timed out
11-25 14:31:50.149  3504  5333 V NativeCrypto: SSL shutdown failed: ssl=0x7fa8143f80: I/O error during system call, Broken pipe
11-25 14:31:50.151   929  3737 D ConnectivityService: reportNetworkConnectivity(100, false) by 10012
11-25 14:31:50.151   929  5279 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Forcing reevaluation for UID 10012
11-25 14:31:50.152   929   942 I ActivityManager: Start proc 5607:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
,11-25 14:31:50.152  4515  4578 D BluetoothAdapterProperties: Scan Mode:20
11-25 14:31:50.153  4515  4574 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
11-25 14:31:50.154   929  2910 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
,11-25 14:31:50.155   929  2910 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
,11-25 14:31:50.156   929  5279 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.gstatic.com": No address associated with hostname
,11-25 14:31:50.158   571   571 E Parcel  : Reading a NULL string not supported here.
11-25 14:31:50.159  4515  4515 D HeadsetService: Received stop request...Stopping profile...
,11-25 14:31:50.159  5537  5585 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,11-25 14:31:50.159  5537  5585 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-25 14:31:50.159  5537  5585 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-25 14:31:50.159  5537  5585 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-25 14:31:50.159  5537  5585 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-25 14:31:50.159  5537  5585 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-25 14:31:50.159  5537  5585 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-25 14:31:50.159  5537  5585 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-25 14:31:50.159  5537  5585 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-25 14:31:50.159  5537  5585 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,11-25 14:31:50.160  5537  5585 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,11-25 14:31:50.160  5537  5585 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
,11-25 14:31:50.160  5537  5585 D io.jxcore.node.ConnectivityMonitor: start: OK
11-25 14:31:50.160   929   929 D RttService: SCAN_AVAILABLE : 1
11-25 14:31:50.161   929  2962 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
11-25 14:31:50.163   929   929 D BluetoothHeadset: Proxy object disconnected
,11-25 14:31:50.163  3064  3946 D BluetoothHeadset: Proxy object disconnected
11-25 14:31:50.163  5537  5537 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-25 14:31:50.163  3721  3738 D BluetoothHeadset: Proxy object disconnected
11-25 14:31:50.164   929   929 D BluetoothHeadset: Proxy object disconnected
11-25 14:31:50.164   929   929 D BluetoothHeadset: Proxy object disconnected
11-25 14:31:50.165  5537  5537 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-25 14:31:50.166  4515  4515 D A2dpService: Received stop request...Stopping profile...
11-25 14:31:50.169   929  2910 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
11-25 14:31:50.170  4515  4716 D A2dpStateMachine: Exit Disconnected: -1
11-25 14:31:50.173  4515  4515 V BluetoothAdapterState: isTurningOff()=true
11-25 14:31:50.172  3677  3779 W QCNEJ   : |CORE| network lost: 100
11-25 14:31:50.173  4515  4515 V BluetoothAdapterState: isTurningOn()=false
11-25 14:31:50.173  4515  4515 V BluetoothAdapterState: isBleTurningOn()=false
11-25 14:31:50.173  4515  4515 V BluetoothAdapterState: isBleTurningOff()=false
11-25 14:31:50.174   929   929 D BluetoothA2dp: Proxy object disconnected
11-25 14:31:50.174  3677  3779 W QCNEJ   : |CORE| onLost: unbind the process to WIFI
11-25 14:31:50.177  4515  4515 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
11-25 14:31:50.177  4515  4515 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
11-25 14:31:50.177  4515  4578 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
11-25 14:31:50.177  4515  4709 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,11-25 14:31:50.178  4515  4709 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-25 14:31:50.178  4515  4709 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-25 14:31:50.178  4515  4515 D HidService: Received stop request...Stopping profile...
11-25 14:31:50.178  4515  4578 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
11-25 14:31:50.178  4515  4515 D HidService: Stopping Bluetooth HidService
11-25 14:31:50.180  4515  4515 D HealthService: Received stop request...Stopping profile...
,11-25 14:31:50.181  4515  4515 D PanService: Received stop request...Stopping profile...
,11-25 14:31:50.183  4515  4515 D BluetoothMapService: Received stop request...Stopping profile...
11-25 14:31:50.184  4515  4515 D BluetoothMapService: stop()
11-25 14:31:50.184  4515  4515 D BluetoothMapAppObserver: deinitObservers()
,11-25 14:31:50.184  4515  4515 D BluetoothMapAppObserver: removeReceiver()
11-25 14:31:50.186  3064  3064 D HeadsetProfile: Bluetooth service disconnected
11-25 14:31:50.186  4515  4515 V BluetoothAdapterState: isTurningOff()=true
11-25 14:31:50.186  4515  4515 V BluetoothAdapterState: isTurningOn()=false
11-25 14:31:50.186  4515  4515 V BluetoothAdapterState: isBleTurningOn()=false
11-25 14:31:50.186  4515  4515 V BluetoothAdapterState: isBleTurningOff()=false
11-25 14:31:50.187  4515  4515 D SapService: Received stop request...Stopping profile...
11-25 14:31:50.187  4515  4515 V SapService: stop()
11-25 14:31:50.189  3064  3064 D BluetoothA2dp: Proxy object disconnected
11-25 14:31:50.189  4515  4578 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
11-25 14:31:50.189  4515  4709 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-25 14:31:50.190  3064  3064 D BluetoothInputDevice: Proxy object disconnected
11-25 14:31:50.190  3064  3064 D HidProfile: Bluetooth service disconnected
11-25 14:31:50.190  4515  4709 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-25 14:31:50.190  3064  3064 D BluetoothPan: BluetoothPAN Proxy object disconnected
11-25 14:31:50.190  4515  4515 V BluetoothAdapterState: isTurningOff()=true
11-25 14:31:50.190  4515  4709 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
11-25 14:31:50.190  3064  3064 D PanProfile: Bluetooth service disconnected
,11-25 14:31:50.190  4515  4515 V BluetoothAdapterState: isTurningOn()=false
11-25 14:31:50.190  4515  4709 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
11-25 14:31:50.190  3064  3064 D BluetoothMap: Proxy object disconnected
11-25 14:31:50.190  4515  4515 V BluetoothAdapterState: isBleTurningOn()=false
11-25 14:31:50.190  3064  3064 D MapProfile: Bluetooth service disconnected
11-25 14:31:50.190  4515  4515 V BluetoothAdapterState: isBleTurningOff()=false
11-25 14:31:50.190  4515  4709 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
11-25 14:31:50.190  4515  4709 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
11-25 14:31:50.191  4515  4515 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
,11-25 14:31:50.191  4515  4515 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
11-25 14:31:50.191  4515  4515 V BluetoothAdapterState: isTurningOff()=true
11-25 14:31:50.192  4515  4515 V BluetoothAdapterState: isTurningOn()=false
11-25 14:31:50.192  4515  4578 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
11-25 14:31:50.192  4515  4515 V BluetoothAdapterState: isBleTurningOn()=false
11-25 14:31:50.192  4515  4515 V BluetoothAdapterState: isBleTurningOff()=false
11-25 14:31:50.192  4515  4515 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
11-25 14:31:50.192   929  2907 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,11-25 14:31:50.193  4515  4515 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
11-25 14:31:50.193  4515  4515 V BluetoothAdapterState: isTurningOff()=true
11-25 14:31:50.193  4515  4515 V BluetoothAdapterState: isTurningOn()=false
11-25 14:31:50.193  4515  4515 V BluetoothAdapterState: isBleTurningOn()=false
11-25 14:31:50.193  4515  4515 V BluetoothAdapterState: isBleTurningOff()=false
11-25 14:31:50.193  4515  4578 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
11-25 14:31:50.193  4515  4515 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
11-25 14:31:50.193  4515  4515 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
11-25 14:31:50.194  4515  4515 D BluetoothMapService: MAP Service closeService in
11-25 14:31:50.194  4515  4515 V BluetoothAdapterState: isTurningOff()=true
,11-25 14:31:50.194  4515  4515 V BluetoothAdapterState: isTurningOn()=false
11-25 14:31:50.194  4515  4515 V BluetoothAdapterState: isBleTurningOn()=false
11-25 14:31:50.194  4515  4515 V BluetoothAdapterState: isBleTurningOff()=false
11-25 14:31:50.195  4515  4515 D BluetoothMapService: cleanup()
11-25 14:31:50.195  4515  4515 D BluetoothMapService: MAP Service closeService in
11-25 14:31:50.195  4515  4515 V BluetoothAdapterState: isTurningOff()=true
11-25 14:31:50.195  4515  4515 V BluetoothAdapterState: isTurningOn()=false
11-25 14:31:50.195  4515  4515 V BluetoothAdapterState: isBleTurningOn()=false
11-25 14:31:50.195  4515  4515 V BluetoothAdapterState: isBleTurningOff()=false
11-25 14:31:50.195  4515  4574 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
11-25 14:31:50.195  4515  4574 D BluetoothAdapterProperties: Setting state to 15
11-25 14:31:50.195  4515  4574 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
11-25 14:31:50.196  4515  4574 I BluetoothAdapterState: Entering BleOnState
11-25 14:31:50.196  3721  3911 D BluetoothHeadset: onBluetoothStateChange: up=false
11-25 14:31:50.196  3064  3076 D BluetoothInputDevice: onBluetoothStateChange: up=false
,11-25 14:31:50.200  3064  3075 D BluetoothHeadset: onBluetoothStateChange: up=false
,11-25 14:31:50.200  3064  3946 D BluetoothPan: onBluetoothStateChange on: false
11-25 14:31:50.201   929   946 D BluetoothA2dp: onBluetoothStateChange: up=false
11-25 14:31:50.202  3064  3076 D BluetoothA2dp: onBluetoothStateChange: up=false
11-25 14:31:50.202   929   946 D BluetoothHeadset: onBluetoothStateChange: up=false
11-25 14:31:50.202  3064  3075 D BluetoothMap: onBluetoothStateChange: up=false
11-25 14:31:50.203   929   946 D BluetoothHeadset: onBluetoothStateChange: up=false
11-25 14:31:50.203  3064  3946 D BluetoothPbap: onBluetoothStateChange: up=false
11-25 14:31:50.204   929   946 D BluetoothHeadset: onBluetoothStateChange: up=false
11-25 14:31:50.204  4515  4574 D BluetoothAdapterState: Current state: BLE ON, message: 20
11-25 14:31:50.204  4515  4574 D BluetoothAdapterProperties: Setting state to 16
11-25 14:31:50.204  4515  4574 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
11-25 14:31:50.205  4515  4574 D BluetoothAdapterProperties: onBleDisable
11-25 14:31:50.205  4515  4574 I BluetoothAdapterState: Entering PendingCommandState
11-25 14:31:50.205  4515  4575 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
11-25 14:31:50.206  4515  4578 D BluetoothAdapterProperties: Scan Mode:20
11-25 14:31:50.207  4515  4709 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
11-25 14:31:50.207  4515  4709 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-25 14:31:50.208  5537  5537 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-25 14:31:50.208  5537  5537 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-25 14:31:50.208  5537  5537 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-25 14:31:50.208  5537  5537 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-25 14:31:50.208  5537  5537 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-25 14:31:50.208  5537  5537 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-25 14:31:50.208  5537  5537 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-25 14:31:50.208  5537  5537 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-25 14:31:50.208  5537  5537 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-25 14:31:50.208  5537  5537 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-25 14:31:50.210  5537  5537 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-25 14:31:50.217   506   922 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-25 14:31:50.217   929  2907 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,11-25 14:31:50.222  5607  5607 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm64
11-25 14:31:50.235  5607  5607 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
11-25 14:31:50.240   929   946 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@d2f9ed3:true
11-25 14:31:50.242  3504  3504 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
11-25 14:31:50.247   506   922 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
11-25 14:31:50.248   929  2910 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
11-25 14:31:50.248   929  2910 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
11-25 14:31:50.247   506   922 D CommandListener: Clearing all IP addresses on wlan0
11-25 14:31:50.250   929  2907 D DhcpClient: doQuit
11-25 14:31:50.250   929  2907 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
11-25 14:31:50.250   929  5281 D DhcpClient: onQuitting
11-25 14:31:50.251  3369  3369 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
11-25 14:31:50.254   929   946 D Tethering: MasterInitialState.processMessage what=3
11-25 14:31:50.254  5131  5131 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@fba8b2c and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
11-25 14:31:50.258  3895  3895 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
11-25 14:31:50.258  5537  5537 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-25 14:31:50.258  5537  5537 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-25 14:31:50.258  5537  5537 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-25 14:31:50.258  5537  5537 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-25 14:31:50.258  5537  5537 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-25 14:31:50.258  5537  5537 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-25 14:31:50.258  5537  5537 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-25 14:31:50.258  5537  5537 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-25 14:31:50.258  5537  5537 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-25 14:31:50.258  5537  5537 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-25 14:31:50.259  5537  5537 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-25 14:31:50.260  5537  5537 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
11-25 14:31:50.261  5537  5537 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-25 14:31:50.261  4854  4868 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
11-25 14:31:50.261  4854  4868 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
11-25 14:31:50.262  4854  4868 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,0,0,0
11-25 14:31:50.262  4854  4868 E SarControlService: no key has been found,reset the power
11-25 14:31:50.262  4854  4893 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
11-25 14:31:50.262  4854  4893 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
11-25 14:31:50.262  4854  4893 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
11-25 14:31:50.262  4881  4881 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
11-25 14:31:50.262  4881  4881 D QcrilMsgTunnelSocket: [1002] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
11-25 14:31:50.263  4854  4893 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
11-25 14:31:50.263  4854  4893 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
11-25 14:31:50.263  4854  4893 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
11-25 14:31:50.264  4881  4881 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
11-25 14:31:50.264  4881  4881 D QcrilMsgTunnelSocket: [1003] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
,11-25 14:31:50.272  3369  3369 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
,11-25 14:31:50.273  4881  4895 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@716d172 HexData = [00000000ea03000000000000ffffffff]
,11-25 14:31:50.273  4881  4895 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-25 14:31:50.273  4881  4895 D QcrilMsgTunnelSocket: [1002] < OEM_HOOK_RAW [null]
11-25 14:31:50.273  4881  4881 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
11-25 14:31:50.274  4854  4864 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
,11-25 14:31:50.275  4881  4895 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@716d172 HexData = [00000000eb03000000000000ffffffff]
,11-25 14:31:50.275  4881  4895 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-25 14:31:50.275  4881  4895 D QcrilMsgTunnelSocket: [1003] < OEM_HOOK_RAW [null]
11-25 14:31:50.276  4881  4881 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
11-25 14:31:50.276  4854  4866 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
11-25 14:31:50.277  3369  3369 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,11-25 14:31:50.285  5607  5607 D LocalBluetoothProfileManager: Adding local MAP profile
,11-25 14:31:50.286  5607  5607 D BluetoothMap: Create BluetoothMap proxy object
,11-25 14:31:50.293  5607  5607 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,11-25 14:31:50.298  3369  3369 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,11-25 14:31:50.301  5607  5607 D DockEventReceiver: finishStartingService: stopping service
,11-25 14:31:50.303   506   922 E Netd    : netlink response contains error (No such file or directory)
,11-25 14:31:50.304   929  2910 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
11-25 14:31:50.304   929  2910 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
11-25 14:31:50.304  5607  5607 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,11-25 14:31:50.309  3504  3504 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
11-25 14:31:50.309  5607  5607 D DockEventReceiver: finishStartingService: stopping service
,11-25 14:31:50.311   929  3736 I ActivityManager: Killing 5131:com.google.android.music:main/u0a59 (adj 15): empty #17
11-25 14:31:50.311  3369  3369 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,11-25 14:31:50.338  3912  3912 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,11-25 14:31:50.341  3912  3912 D SystemUpdateService: onCreate
,11-25 14:31:50.344  3912  3912 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,11-25 14:31:50.351  3912  3912 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,11-25 14:31:50.355  3912  5637 I SystemUpdateService: active receiver: enabled
,11-25 14:31:50.356  3912  5304 I iu.UploadsManager: num queued entries: 0
,11-25 14:31:50.356  3912  5304 I iu.UploadsManager: num updated entries: 0
11-25 14:31:50.357  3912  5304 I iu.SyncManager: NEXT; no task
,11-25 14:31:50.358  3912  3912 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,11-25 14:31:50.359  3912  3912 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,11-25 14:31:50.361  5308  5308 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,11-25 14:31:50.365  5308  5308 D SprintDMHelper: simOperator: 
11-25 14:31:50.365  5308  5308 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,11-25 14:31:50.375  3912  5637 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,11-25 14:31:50.376  4357  5639 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,11-25 14:31:50.378  3912  5637 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,11-25 14:31:50.378  3912  5637 I SystemUpdateService: now status is 0 (complete)
11-25 14:31:50.378  3912  5637 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
,11-25 14:31:50.379  3912  5637 I SystemUpdateService: file has been verified
11-25 14:31:50.379  3912  5637 I SystemUpdateService: OTA package size = 21989297
,11-25 14:31:50.385  3912  5637 I SystemUpdateService: showing system update notification
,11-25 14:31:50.388   929   940 I ActivityManager: Start proc 5640:com.google.android.apps.gcs/u0a11 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,11-25 14:31:50.400   929   929 V NotificationService: pkg=com.google.android.gms canInterrupt=false intercept=true
,11-25 14:31:50.401  3912  3912 D SystemUpdateService: onDestroy
,11-25 14:31:50.416  4357  4357 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,11-25 14:31:50.418  3649  4112 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,11-25 14:31:50.419  4515  4578 I bt_hci  : shut_down
,11-25 14:31:50.420  5537  5537 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-25 14:31:50.420   929  2907 D wifi    : In wifi stop Hal
11-25 14:31:50.420   929  2907 D wifi    : halHandle = 0x7f9669b180, mVM = 0x7fb2c4d140, mCls = 0x100a02
,11-25 14:31:50.421   929  3367 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
11-25 14:31:50.421   929  3367 D WifiHAL : Got a signal to exit!!!
11-25 14:31:50.421   929  3367 I WifiHAL : Exit wifi_event_loop
11-25 14:31:50.421   929  2907 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 11
11-25 14:31:50.421   929  2907 E WifiHAL : Event processing terminated
11-25 14:31:50.421   929  2907 D wifi    : In wifi cleaned up handler
11-25 14:31:50.421   929  2907 I WifiHAL : Internal cleanup completed
,11-25 14:31:50.421  4515  4582 D bt_hwcfg: hw_epilog_process
11-25 14:31:50.422  4515  4582 I bt_vendor: low_power_mode_cb
,11-25 14:31:50.425  4515  4582 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,11-25 14:31:50.425  4515  4582 I bt_vendor: epilog_cb
11-25 14:31:50.425  4515  4582 I bt_hci  : epilog_finished_callback
11-25 14:31:50.427  5640  5640 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm64
11-25 14:31:50.428  4515  4578 I bt_hci_h4: hal_close
11-25 14:31:50.429  4515  4578 I bt_userial_vendor: device fd = 54 close
,11-25 14:31:50.436   929  3060 I ActivityManager: Killing 3787:com.android.providers.calendar/u0a1 (adj 15): empty #17
,11-25 14:31:50.439   929  3367 D wifi    : set interface wlan0 flags (DOWN)
,11-25 14:31:50.439   929  2907 D WifiNative-HAL: HAL event thread stopped successfully
,11-25 14:31:50.500   506   922 E Netd    : netlink response contains error (No such file or directory)
,11-25 14:31:50.539  4515  4575 D bt_stack_manager: event_shut_down_stack finished.
,11-25 14:31:50.539  4515  4574 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,11-25 14:31:50.541  4515  4515 D BtGatt.DebugUtils: handleDebugAction() action=null
,11-25 14:31:50.541  4515  4574 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
11-25 14:31:50.541  4515  4515 D BtGatt.GattService: Received stop request...Stopping profile...
11-25 14:31:50.541  4515  4515 D BtGatt.GattService: stop()
11-25 14:31:50.541  4515  4515 D BtGatt.AdvertiseManager: advertise clients cleared
11-25 14:31:50.542  4515  4515 V BluetoothAdapterState: isTurningOff()=false
11-25 14:31:50.542  4515  4515 V BluetoothAdapterState: isTurningOn()=false
11-25 14:31:50.542  4515  4515 V BluetoothAdapterState: isBleTurningOn()=false
11-25 14:31:50.542  4515  4515 V BluetoothAdapterState: isBleTurningOff()=true
11-25 14:31:50.543  4515  4574 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
11-25 14:31:50.543  4515  4574 D BluetoothAdapterProperties: Setting state to 10
11-25 14:31:50.543  4515  4574 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
11-25 14:31:50.543  4515  4574 I BluetoothAdapterState: Entering OffState
,11-25 14:31:50.544   929   946 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,11-25 14:31:50.549  4515  4515 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,11-25 14:31:50.549  4515  4515 W BluetoothSdpJni: Cleaning up Bluetooth Health object
11-25 14:31:50.549  4515  4515 I BluetoothServiceJni: cleanupNative: return from cleanup
11-25 14:31:50.550  4515  4575 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,11-25 14:31:50.552  4515  4515 I art     : System.exit called, status: 0
,11-25 14:31:50.552  4515  4515 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,11-25 14:31:50.574   929   939 I ActivityManager: Process com.android.bluetooth (pid 4515) has died
,11-25 14:31:50.643   929   946 D Tethering: InitialState.processMessage what=4
,11-25 14:31:50.646   929   946 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,11-25 14:31:51.938   577   577 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,11-25 14:31:51.938   577   577 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,11-25 14:31:55.163   929  3337 D WifiService: setWifiEnabled: true pid=5537, uid=10077
,11-25 14:31:55.163   929  3337 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-25 14:31:55.173   506   922 D SoftapController: Softap fwReload - Ok
,11-25 14:31:55.178   506   922 D CommandListener: Setting iface cfg
,11-25 14:31:55.178   506   922 D CommandListener: Trying to bring down wlan0
,11-25 14:31:55.180   506   922 D CommandListener: Clearing all IP addresses on wlan0
,11-25 14:31:55.187   929  2907 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,11-25 14:31:55.784   929  2907 D wifi    : set interface wlan0 flags (UP)
,11-25 14:31:55.788   929  2907 I WifiHAL : Initializing wifi
,11-25 14:31:55.788   929  2907 I WifiHAL : Creating socket
,11-25 14:31:55.795   929  2907 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
,11-25 14:31:55.795   929  2907 D wifi    : Did set static halHandle = 0x7f9669b180
,11-25 14:31:55.795   929  2907 D wifi    : halHandle = 0x7f9669b180, mVM = 0x7fb2c4d140, mCls = 0x101976
,11-25 14:31:55.796   929  2907 D wifi    : array field set
,11-25 14:31:55.796   929   946 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
11-25 14:31:55.796   929  2907 I WifiNative-HAL: interface[0] = wlan0
,11-25 14:31:55.802   929  5662 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=547984355712
,11-25 14:31:55.802   929  5662 D wifi    : waitForHalEvents called, vm = 0x7fb2c4d140, obj = 0x101976, env = 0x7f98addf00
,11-25 14:31:55.860  5664  5664 I wpa_supplicant: Successfully initialized wpa_supplicant
,11-25 14:31:55.901   929  2907 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,11-25 14:31:55.907  5537  5537 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-25 14:31:55.927  5664  5664 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,11-25 14:31:55.962  5664  5664 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,11-25 14:31:55.962  5664  5664 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,11-25 14:31:55.972   929  2907 D WifiConfigStore: Loading config and enabling all networks 
,11-25 14:31:55.973  5537  5537 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,11-25 14:31:55.973  5537  5537 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-25 14:31:55.973  5537  5537 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-25 14:31:55.973  5537  5537 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-25 14:31:55.973  5537  5537 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-25 14:31:55.973  5537  5537 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-25 14:31:55.973  5537  5537 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-25 14:31:55.973  5537  5537 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-25 14:31:55.973  5537  5537 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-25 14:31:55.973  5537  5537 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-25 14:31:55.973  5537  5537 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,11-25 14:31:55.973  5537  5537 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
,11-25 14:31:55.984   929  2907 D WifiConfigStore: loaded 0 passpoint configs
,11-25 14:31:55.985   929  2907 W WifiConfigStore: Upgrading network 4 to android.uid.system:1000
11-25 14:31:55.985   929  2907 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,11-25 14:31:55.985   929  2907 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
11-25 14:31:55.985   929  2907 W WifiConfigStore: Upgrading network 3 to android.uid.system:1000
,11-25 14:31:55.986   929  2907 W WifiConfigStore: Upgrading network 2 to android.uid.system:1000
11-25 14:31:55.986   929  2907 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,11-25 14:31:55.986   929  2907 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 5
11-25 14:31:55.986   929  2907 E WifiConfigStore: found sortedWifiConfigurations : "AndroidAP"WPA_PSK
11-25 14:31:55.986   929  2907 E WifiConfigStore: found sortedWifiConfigurations : "AndroidHotspot2346"WPA_PSK
11-25 14:31:55.986   929  2907 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
11-25 14:31:55.986   929  2907 E WifiConfigStore: found sortedWifiConfigurations : "Thali_internal"WPA_PSK
,11-25 14:31:55.987   929  2907 E WifiConfigStore: found sortedWifiConfigurations : "MC"WPA_PSK
,11-25 14:31:55.988   929  2907 D WifiNative-HAL: Setting external_sim to 1
,11-25 14:31:55.988   929  2907 D wifi    : setting dfs flag to true, 0x7f9a68cec0
,11-25 14:31:55.989  4357  4357 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
11-25 14:31:55.989   929  2907 D WifiStateMachine: Setting OUI to DA-A1-19
,11-25 14:31:55.989   929  2907 D wifi    : setting scan oui 0x7f9a68cec0
11-25 14:31:55.989   929  2907 D WifiHAL : Sending mac address OUI
,11-25 14:31:55.991   929  2907 E native  : do suspend false
,11-25 14:31:55.997   929  2907 D wifi    : android_net_wifi_setLinkLayerStats: 1
11-25 14:31:55.997   929   929 D RttService: SCAN_AVAILABLE : 3
,11-25 14:31:55.998   929  2962 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,11-25 14:31:56.001   506   922 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,11-25 14:31:56.002   506   922 D CommandListener: Setting iface cfg
,11-25 14:31:56.004   929  2896 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '125 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 125 Failed to set address (No such device)'
,11-25 14:31:56.004   929  2896 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,11-25 14:31:56.009   929  2896 D WifiNative-HAL: p2pGetDeviceAddress
,11-25 14:31:56.009   929  2896 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:70
,11-25 14:31:56.027   929   944 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=117569 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=24 mControllerEnergyUsed=91 }
,11-25 14:31:56.939   577   577 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 14:31:57.737   929  2907 D WifiStateMachine: Disconnected CMD_START_SCAN source -2 7, 8 -> obsolete
,11-25 14:31:57.940   577   577 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 14:31:58.941   577   577 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 14:31:59.065  5664  5664 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-25 14:31:59.073  5664  5664 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-25 14:31:59.098   929  2907 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,11-25 14:31:59.099   929  2907 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3
11-25 14:31:59.100   929  2907 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-25 14:31:59.110   929  2907 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=0
,11-25 14:31:59.141   929  2907 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=0
,11-25 14:31:59.146  5664  5664 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,11-25 14:31:59.567  5664  5664 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,11-25 14:31:59.599  5664  5664 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,11-25 14:31:59.599  5664  5664 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,11-25 14:31:59.608   929  2907 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,11-25 14:31:59.608   929  2907 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-25 14:31:59.608   929  2910 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,11-25 14:31:59.625   929  2907 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-25 14:31:59.637   506   922 D CommandListener: Setting iface cfg
,11-25 14:31:59.642   929  2907 D WifiStateMachine: Start Dhcp Watchdog 2
,11-25 14:31:59.648   929  5679 D DhcpClient: Receive thread started
,11-25 14:31:59.652   929  2910 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-25 14:31:59.652   929  2907 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
11-25 14:31:59.652   929  2910 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
,11-25 14:31:59.733   929  2907 E native  : do suspend false
,11-25 14:31:59.748   929  5678 D DhcpClient: Broadcasting DHCPDISCOVER
,11-25 14:31:59.760   929  5679 D DhcpClient: Received packet: 60:83:34:25:d7:70 OFFER, ip /192.168.1.109, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172718, domain null
,11-25 14:31:59.760   929  5678 D DhcpClient: Got pending lease: IP address 192.168.1.109/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172718 seconds
,11-25 14:31:59.762   929  5678 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.109 serverid=192.168.1.1
,11-25 14:31:59.777   929  5679 D DhcpClient: Received packet: 60:83:34:25:d7:70 ACK: your new IP /192.168.1.109, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,11-25 14:31:59.777   929  5678 D DhcpClient: Confirmed lease: IP address 192.168.1.109/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
11-25 14:31:59.780   506   922 D CommandListener: Setting iface cfg
,11-25 14:31:59.785   929  2907 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,11-25 14:31:59.790   929  5678 D DhcpClient: Scheduling renewal in 86399s
,11-25 14:31:59.802   929  2907 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
11-25 14:31:59.803   929  2907 D WifiConfigStore: No blacklist allowed without epno enabled
11-25 14:31:59.804   929  2910 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,11-25 14:31:59.807   929  2907 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
11-25 14:31:59.811   929  2910 D ConnectivityService: Adding iface wlan0 to network 101
,11-25 14:31:59.861   929  2910 E ConnectivityService: Unexpected mtu value: 0, wlan0
,11-25 14:31:59.861   929  2910 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
,11-25 14:31:59.863   929  2910 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,11-25 14:31:59.866   929  2910 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,11-25 14:31:59.868   929  2910 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,11-25 14:31:59.874   929  2910 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-25 14:31:59.879   929  2910 D ConnectivityService: scheduleUnvalidatedPrompt 101
,11-25 14:31:59.879   929  2910 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
11-25 14:31:59.879   929  2910 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
11-25 14:31:59.879   929  2910 D ConnectivityService:    accepting network in place of null
11-25 14:31:59.879   929  2907 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
11-25 14:31:59.879   929  2907 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
11-25 14:31:59.880   929  2910 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.109/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -52]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,11-25 14:31:59.895   929  5677 D NetlinkSocketObserver: NeighborEvent{elapsedMs=121438, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,11-25 14:31:59.903   506   922 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-25 14:31:59.926   506   922 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-25 14:31:59.929   929  2910 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,11-25 14:31:59.929   929  2910 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
11-25 14:31:59.929  3677  3779 W QCNEJ   : |CORE| network available: 101
,11-25 14:31:59.930   929  2910 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
,11-25 14:31:59.931   929   946 D Tethering: MasterInitialState.processMessage what=3
,11-25 14:31:59.936  3677  3779 W QCNEJ   : |CORE| onAvailable: bind the process to WIFI
11-25 14:31:59.937  3677  3779 W QCNEJ   : |CORE| newLp: {InterfaceName: wlan0 LinkAddresses: [192.168.1.109/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}
11-25 14:31:59.938  3677  3779 W QCNEJ   : |CORE| curLp: {InterfaceName: wlan0 LinkAddresses: [192.168.1.109/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
11-25 14:31:59.938  5537  5537 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-25 14:31:59.938  5537  5537 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-25 14:31:59.938  5537  5537 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-25 14:31:59.938  5537  5537 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-25 14:31:59.938  5537  5537 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-25 14:31:59.938  5537  5537 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-25 14:31:59.938  5537  5537 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-25 14:31:59.938  5537  5537 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-25 14:31:59.938  5537  5537 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-25 14:31:59.938  5537  5537 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
11-25 14:31:59.938  5537  5537 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-25 14:31:59.938  5537  5537 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
,11-25 14:31:59.941   577   577 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 14:31:59.947  4854  4868 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
,11-25 14:31:59.947  4854  4868 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
11-25 14:31:59.947  4854  4868 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,1,0,0
11-25 14:31:59.947  4854  4868 E SarControlService: no key has been found,reset the power
11-25 14:31:59.948  4854  4893 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
11-25 14:31:59.948  4854  4893 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
11-25 14:31:59.948  4854  4893 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
11-25 14:31:59.948  4881  4881 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
11-25 14:31:59.948  4881  4881 D QcrilMsgTunnelSocket: [1004] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
11-25 14:31:59.950  3895  3895 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
11-25 14:31:59.951  4854  4893 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
11-25 14:31:59.951  4854  4893 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
11-25 14:31:59.951  4854  4893 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
11-25 14:31:59.951  4881  4881 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
,11-25 14:31:59.951  4881  4881 D QcrilMsgTunnelSocket: [1005] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
11-25 14:31:59.953  3912  3912 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,11-25 14:31:59.957  4881  4895 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@716d172 HexData = [00000000ec03000000000000ffffffff]
,11-25 14:31:59.957  4881  4895 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-25 14:31:59.957  4881  4895 D QcrilMsgTunnelSocket: [1004] < OEM_HOOK_RAW [null]
11-25 14:31:59.957  4881  4895 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@716d172 HexData = [00000000ed03000000000000ffffffff]
,11-25 14:31:59.957  4881  4895 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
,11-25 14:31:59.957  4881  4895 D QcrilMsgTunnelSocket: [1005] < OEM_HOOK_RAW [null]
11-25 14:31:59.958  4881  4881 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
11-25 14:31:59.958  4854  4864 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
11-25 14:31:59.959  4881  4881 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
11-25 14:31:59.959  4854  4866 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
11-25 14:31:59.959  3912  3912 D SystemUpdateService: onCreate
,11-25 14:31:59.964  3912  3912 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,11-25 14:31:59.973  3912  3912 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,11-25 14:31:59.978  3912  5304 I iu.UploadsManager: num queued entries: 0
11-25 14:31:59.979  3912  5304 I iu.UploadsManager: num updated entries: 0
,11-25 14:31:59.979  3912  5304 I iu.SyncManager: NEXT; no task
11-25 14:31:59.980   929  5676 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=172.217.22.110,2a00:1450:4001:81d::200e
,11-25 14:31:59.983  3912  5691 I SystemUpdateService: active receiver: enabled
,11-25 14:31:59.985  3912  3912 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,11-25 14:31:59.987  3912  3912 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,11-25 14:31:59.989  5308  5308 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,11-25 14:31:59.994  5308  5308 D SprintDMHelper: simOperator: 
,11-25 14:31:59.994  5308  5308 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,11-25 14:32:00.018  3912  5691 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,11-25 14:32:00.032  3912  5691 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,11-25 14:32:00.032  3912  5691 I SystemUpdateService: now status is 0 (complete)
11-25 14:32:00.032  3912  5691 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
11-25 14:32:00.032  3912  5691 I SystemUpdateService: file has been verified
11-25 14:32:00.032  3912  5691 I SystemUpdateService: OTA package size = 21989297
,11-25 14:32:00.042  3912  5691 I SystemUpdateService: showing system update notification
,11-25 14:32:00.048   929   929 V NotificationService: pkg=com.google.android.gms canInterrupt=false intercept=true
,11-25 14:32:00.050  3912  3912 D SystemUpdateService: onDestroy
,11-25 14:32:00.171   929  3736 D WifiService: setWifiEnabled: false pid=5537, uid=10077
11-25 14:32:00.171   929  3736 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-25 14:32:00.175   929  2907 D WifiStateMachine: WifiStateMachine: Leaving Connected state
11-25 14:32:00.175   929  2907 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
,11-25 14:32:00.175   929  2907 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,11-25 14:32:00.175   929  2907 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-25 14:32:00.203   929  5678 D DhcpClient: Clearing IP address
,11-25 14:32:00.204   506   922 D CommandListener: Clearing all IP addresses on wlan0
,11-25 14:32:00.209   506   922 D CommandListener: Setting iface cfg
,11-25 14:32:00.223   929  5676 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Probably not a portal: exception java.net.ConnectException: failed to connect to connectivitycheck.gstatic.com/2a00:1450:4001:81d::200e (port 80) after 10000ms: connect failed: ENETUNREACH (Network is unreachable)
11-25 14:32:00.225   929  2910 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation failed
,11-25 14:32:00.229   929  2910 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
11-25 14:32:00.229   929  2910 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 3
,11-25 14:32:00.239   929   929 D RttService: SCAN_AVAILABLE : 1
,11-25 14:32:00.239   929  2962 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,11-25 14:32:00.242   571   571 E Parcel  : Reading a NULL string not supported here.
11-25 14:32:00.243   929  2910 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
11-25 14:32:00.245  3677  3779 W QCNEJ   : |CORE| network lost: 101
11-25 14:32:00.246   929  5679 D DhcpClient: Receive thread stopped
,11-25 14:32:00.246  3677  3779 W QCNEJ   : |CORE| onLost: unbind the process to WIFI
,11-25 14:32:00.266   929  2907 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,11-25 14:32:00.272   506   922 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-25 14:32:00.278   929  2907 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,11-25 14:32:00.295   506   922 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-25 14:32:00.295   929  2910 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,11-25 14:32:00.295   929  2910 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
11-25 14:32:00.295   506   922 D CommandListener: Clearing all IP addresses on wlan0
,11-25 14:32:00.299   929   946 D Tethering: MasterInitialState.processMessage what=3
,11-25 14:32:00.300  5537  5537 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,11-25 14:32:00.300  5537  5537 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-25 14:32:00.300  5537  5537 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-25 14:32:00.300  5537  5537 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-25 14:32:00.300  5537  5537 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-25 14:32:00.300  5537  5537 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-25 14:32:00.300  5537  5537 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-25 14:32:00.300  5537  5537 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-25 14:32:00.300  5537  5537 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-25 14:32:00.300  5537  5537 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-25 14:32:00.300  5537  5537 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-25 14:32:00.300  5537  5537 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
11-25 14:32:00.301   929  2907 D DhcpClient: doQuit
11-25 14:32:00.301   929  2907 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,11-25 14:32:00.301   929  5678 D DhcpClient: onQuitting
11-25 14:32:00.302  5664  5664 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
11-25 14:32:00.303  3895  3895 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
11-25 14:32:00.305  5537  5537 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-25 14:32:00.305  5537  5537 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-25 14:32:00.305  5537  5537 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-25 14:32:00.305  5537  5537 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-25 14:32:00.305  5537  5537 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-25 14:32:00.305  5537  5537 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-25 14:32:00.305  5537  5537 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-25 14:32:00.305  5537  5537 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-25 14:32:00.305  5537  5537 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-25 14:32:00.305  5537  5537 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-25 14:32:00.305  5537  5537 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-25 14:32:00.305  5537  5537 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
,11-25 14:32:00.307  3912  3912 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
11-25 14:32:00.309  4854  4868 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
11-25 14:32:00.310  4854  4868 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
11-25 14:32:00.310  4854  4868 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,0,0,0
11-25 14:32:00.310  4854  4868 E SarControlService: no key has been found,reset the power
11-25 14:32:00.310  4854  4893 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
11-25 14:32:00.311  4854  4893 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
,11-25 14:32:00.311  4854  4893 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
11-25 14:32:00.311  4881  4881 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
11-25 14:32:00.311  4881  4881 D QcrilMsgTunnelSocket: [1006] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
11-25 14:32:00.312  4854  4893 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
11-25 14:32:00.313  4854  4893 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
11-25 14:32:00.313  4854  4893 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
11-25 14:32:00.313  4881  4881 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
,11-25 14:32:00.313  4881  4881 D QcrilMsgTunnelSocket: [1007] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
11-25 14:32:00.316  3912  3912 D SystemUpdateService: onCreate
11-25 14:32:00.318  4881  4895 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@716d172 HexData = [00000000ee03000000000000ffffffff]
11-25 14:32:00.318  4881  4895 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-25 14:32:00.318  4881  4895 D QcrilMsgTunnelSocket: [1006] < OEM_HOOK_RAW [null]
11-25 14:32:00.318  4881  4881 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
11-25 14:32:00.319  4854  4866 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
,11-25 14:32:00.322  3912  3912 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,11-25 14:32:00.325  4881  4895 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@716d172 HexData = [00000000ef03000000000000ffffffff]
,11-25 14:32:00.326  4881  4895 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-25 14:32:00.326  4881  4895 D QcrilMsgTunnelSocket: [1007] < OEM_HOOK_RAW [null]
11-25 14:32:00.327  4881  4881 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
,11-25 14:32:00.328  4854  4864 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
11-25 14:32:00.328  5664  5664 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
,11-25 14:32:00.329  3912  5711 I SystemUpdateService: active receiver: enabled
11-25 14:32:00.331  3912  3912 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
11-25 14:32:00.334  5664  5664 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
11-25 14:32:00.336  3912  5304 I iu.UploadsManager: num queued entries: 0
11-25 14:32:00.337  3912  5304 I iu.UploadsManager: num updated entries: 0
,11-25 14:32:00.340  3912  5711 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,11-25 14:32:00.341  3912  5711 I SystemUpdateService: network: null; metered: false; mobile allowed: true
11-25 14:32:00.341  3912  5711 I SystemUpdateService: now status is 0 (complete)
11-25 14:32:00.342  3912  5711 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
11-25 14:32:00.342  3912  5711 I SystemUpdateService: file has been verified
,11-25 14:32:00.343  3912  3912 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,11-25 14:32:00.345  3912  3912 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,11-25 14:32:00.346  5308  5308 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,11-25 14:32:00.352  5308  5308 D SprintDMHelper: simOperator: 
11-25 14:32:00.353  5308  5308 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,11-25 14:32:00.353  3912  5711 I SystemUpdateService: OTA package size = 21989297
,11-25 14:32:00.353  3912  5304 I iu.SyncManager: NEXT; no task
,11-25 14:32:00.360   506   922 E Netd    : netlink response contains error (No such file or directory)
,11-25 14:32:00.361   929  2910 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,11-25 14:32:00.361   929  2910 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,11-25 14:32:00.367  3912  5711 I SystemUpdateService: showing system update notification
,11-25 14:32:00.376  5664  5664 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,11-25 14:32:00.384  5664  5664 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,11-25 14:32:00.388   929   929 V NotificationService: pkg=com.google.android.gms canInterrupt=false intercept=true
11-25 14:32:00.389  3912  3912 D SystemUpdateService: onDestroy
,11-25 14:32:00.489   929  2907 D wifi    : In wifi stop Hal
,11-25 14:32:00.489   929  2907 D wifi    : halHandle = 0x7f9669b180, mVM = 0x7fb2c4d140, mCls = 0x101976
,11-25 14:32:00.491  4357  4357 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
11-25 14:32:00.491   929  5662 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
11-25 14:32:00.493  3649  4112 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
11-25 14:32:00.495   929  5662 D WifiHAL : Got a signal to exit!!!
11-25 14:32:00.496   929  5662 I WifiHAL : Exit wifi_event_loop
11-25 14:32:00.493  5537  5537 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-25 14:32:00.497   929  2907 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 0
11-25 14:32:00.497   929  2907 E WifiHAL : Event processing terminated
11-25 14:32:00.498   929  2907 D wifi    : In wifi cleaned up handler
11-25 14:32:00.499   929  2907 I WifiHAL : Internal cleanup completed
,11-25 14:32:00.518   929  5662 D wifi    : set interface wlan0 flags (DOWN)
,11-25 14:32:00.518   929  2907 D WifiNative-HAL: HAL event thread stopped successfully
,11-25 14:32:00.580   506   922 E Netd    : netlink response contains error (No such file or directory)
,11-25 14:32:00.722   929   946 D Tethering: InitialState.processMessage what=4
,11-25 14:32:00.727   929   946 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,11-25 14:32:00.930   929  2910 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,11-25 14:32:00.942   577   577 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 14:32:01.943   577   577 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,11-25 14:32:05.025  4357  5696 W Babel_NetworkConnectionCheckingService: IO exceptions, probably not a captive portal 
,11-25 14:32:05.026  4357  5696 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,11-25 14:32:05.029  4357  5696 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,11-25 14:32:05.215   929   946 I ActivityManager: Start proc 5722:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,11-25 14:32:05.314  5722  5722 D AdapterServiceConfig: Adding HeadsetService
,11-25 14:32:05.314  5722  5722 D AdapterServiceConfig: Adding A2dpService
11-25 14:32:05.314  5722  5722 D AdapterServiceConfig: Adding HidService
11-25 14:32:05.314  5722  5722 D AdapterServiceConfig: Adding HealthService
11-25 14:32:05.315  5722  5722 D AdapterServiceConfig: Adding PanService
11-25 14:32:05.315  5722  5722 D AdapterServiceConfig: Adding GattService
11-25 14:32:05.315  5722  5722 D AdapterServiceConfig: Adding BluetoothMapService
,11-25 14:32:05.315  5722  5722 D AdapterServiceConfig: Adding SapService
,11-25 14:32:05.329   929   946 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@16dd7d7:true
,11-25 14:32:05.329  5722  5722 D BluetoothAdapterState: make() - Creating AdapterState
,11-25 14:32:05.331  5722  5722 I bt_bluedroid: init
,11-25 14:32:05.331  5722  5734 I BluetoothAdapterState: Entering OffState
,11-25 14:32:05.334  5722  5735 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,11-25 14:32:05.334  5722  5735 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
11-25 14:32:05.334  5722  5735 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
11-25 14:32:05.334  5722  5735 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
11-25 14:32:05.335  5722  5722 I bt_bluedroid: get_profile_interface socket
,11-25 14:32:05.336  5722  5722 I bt_bluedroid: get_profile_interface sdp
,11-25 14:32:05.336  5722  5738 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:D4
,11-25 14:32:05.337  5722  5738 D BluetoothAdapterProperties: Name is: Nexus 6P
,11-25 14:32:05.340  5722  5733 I bt_bluedroid: config_hci_snoop_log
,11-25 14:32:05.341   929   946 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,11-25 14:32:05.345  5722  5734 D BluetoothAdapterState: Current state: OFF, message: 0
11-25 14:32:05.345  5722  5734 D BluetoothAdapterProperties: Setting state to 14
11-25 14:32:05.345  5722  5734 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,11-25 14:32:05.347  5722  5734 D BluetoothBondStateMachine: make
,11-25 14:32:05.348  5722  5739 I BluetoothBondStateMachine: StableState(): Entering Off State
,11-25 14:32:05.351  5722  5734 I BluetoothAdapterState: Entering PendingCommandState
,11-25 14:32:05.351  5722  5722 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,11-25 14:32:05.353  5722  5722 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@91cfe3b
11-25 14:32:05.354  5722  5722 D BtGatt.DebugUtils: handleDebugAction() action=null
11-25 14:32:05.354  5722  5722 D BtGatt.GattService: Received start request. Starting profile...
11-25 14:32:05.354  5722  5722 D BtGatt.GattService: start()
,11-25 14:32:05.354  5722  5722 I bt_bluedroid: get_profile_interface gatt
,11-25 14:32:05.355  5722  5722 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@91cfe3b
11-25 14:32:05.355  5722  5722 D BtGatt.AdvertiseManager: advertise manager created
,11-25 14:32:05.359  5722  5722 V BluetoothAdapterState: isTurningOff()=false
,11-25 14:32:05.360  5722  5722 V BluetoothAdapterState: isTurningOn()=false
11-25 14:32:05.360  5722  5722 V BluetoothAdapterState: isBleTurningOn()=true
11-25 14:32:05.360  5722  5722 V BluetoothAdapterState: isBleTurningOff()=false
11-25 14:32:05.360  5722  5734 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,11-25 14:32:05.361  5722  5734 I bt_bluedroid: bt_bluedroid
,11-25 14:32:05.361  5722  5735 D bt_stack_manager: event_start_up_stack is bringing up the stack.
11-25 14:32:05.361  5722  5735 I bt_hci  : start_up
,11-25 14:32:05.366  5722  5735 I bt_vendor: alloc value 0xf4071871
11-25 14:32:05.366  5722  5735 I bt_vendor: init
11-25 14:32:05.366  5722  5735 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
11-25 14:32:05.367  5722  5735 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,11-25 14:32:05.474  5722  5735 D bt_hci  : start_up starting async portion
11-25 14:32:05.474  5722  5742 I bt_hci  : event_finish_startup
11-25 14:32:05.475  5722  5742 I bt_hci_h4: hal_open
11-25 14:32:05.475  5722  5742 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,11-25 14:32:05.471  5743  5743 W irq/448-msm_hs_: type=1400 audit(0.0:117): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-25 14:32:05.480  5722  5742 I bt_userial_vendor: device fd = 54 open
,11-25 14:32:05.493  5722  5742 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,11-25 14:32:05.495  5722  5742 D bt_hwcfg: Chipset BCM4358A3
,11-25 14:32:05.496  5722  5742 D bt_hwcfg: Target name = [BCM4358A3]
11-25 14:32:05.496  5722  5742 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,11-25 14:32:05.881  5722  5742 I bt_hwcfg: bt vendor lib: set UART baud 115200
,11-25 14:32:05.881  5722  5742 D bt_hwcfg: Settlement delay -- 100 ms
,11-25 14:32:05.881  5722  5742 I bt_hwcfg: Setting fw settlement delay to 100 
,11-25 14:32:06.016  5722  5742 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,11-25 14:32:06.016  5722  5742 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:D4
11-25 14:32:06.017  5722  5742 I bt_hwcfg: vendor lib fwcfg completed
11-25 14:32:06.018  5722  5742 I bt_vendor: firmware callback
11-25 14:32:06.018  5722  5742 I bt_hci  : firmware_config_callback
,11-25 14:32:06.026  5722  5745 I bt_btu  : btu_task pending for preload complete event
,11-25 14:32:06.026  5722  5745 I bt_btu_task: Bluetooth chip preload is complete
11-25 14:32:06.026  5722  5745 I bt_btu  : btu_task received preload complete event
11-25 14:32:06.033  5722  5745 I         : BTE_InitTraceLevels -- TRC_HCI
11-25 14:32:06.033  5722  5745 I         : BTE_InitTraceLevels -- TRC_L2CAP
11-25 14:32:06.033  5722  5745 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,11-25 14:32:06.033  5722  5745 I         : BTE_InitTraceLevels -- TRC_AVDT
11-25 14:32:06.033  5722  5745 I         : BTE_InitTraceLevels -- TRC_AVRC
11-25 14:32:06.034  5722  5745 I         : BTE_InitTraceLevels -- TRC_A2D
11-25 14:32:06.034  5722  5745 I         : BTE_InitTraceLevels -- TRC_BNEP
,11-25 14:32:06.034  5722  5745 I         : BTE_InitTraceLevels -- TRC_BTM
11-25 14:32:06.034  5722  5745 I         : BTE_InitTraceLevels -- TRC_GAP
11-25 14:32:06.034  5722  5745 I         : BTE_InitTraceLevels -- TRC_PAN
11-25 14:32:06.034  5722  5745 I         : BTE_InitTraceLevels -- TRC_SDP
11-25 14:32:06.034  5722  5745 I         : BTE_InitTraceLevels -- TRC_GATT
11-25 14:32:06.035  5722  5745 I         : BTE_InitTraceLevels -- TRC_SMP
,11-25 14:32:06.035  5722  5745 I         : BTE_InitTraceLevels -- TRC_BTAPP
11-25 14:32:06.035  5722  5745 I         : BTE_InitTraceLevels -- TRC_BTIF
,11-25 14:32:06.117  5722  5745 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf3fef549
,11-25 14:32:06.118  5722  5745 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf3fef549 
,11-25 14:32:06.135  5722  5738 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,11-25 14:32:06.137  5722  5738 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,11-25 14:32:06.137  5722  5738 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:D4
11-25 14:32:06.139  5722  5738 D BluetoothAdapterProperties: Name is: Nexus 6P
11-25 14:32:06.142  5722  5738 D BluetoothAdapterProperties: Scan Mode:20
,11-25 14:32:06.142  5722  5738 D BluetoothAdapterProperties: Discoverable Timeout:120
,11-25 14:32:06.142  5722  5738 D bt_hci  : do_postload posting postload work item
11-25 14:32:06.142  5722  5742 I bt_hci  : event_postload
,11-25 14:32:06.143  5722  5742 I bt_vendor: sco_config_cb
11-25 14:32:06.143  5722  5742 I bt_hci  : sco_config_callback postload finished.
11-25 14:32:06.146  5722  5738 D bt_bte_conf: Device ID record 1 : primary
11-25 14:32:06.146  5722  5738 D bt_bte_conf:   vendorId            = 000f
11-25 14:32:06.146  5722  5738 D bt_bte_conf:   vendorIdSource      = 0001
11-25 14:32:06.146  5722  5738 D bt_bte_conf:   product             = 1200
,11-25 14:32:06.146  5722  5738 D bt_bte_conf:   version             = 1436
11-25 14:32:06.146  5722  5738 D bt_bte_conf:   clientExecutableURL = 
11-25 14:32:06.146  5722  5738 D bt_bte_conf:   serviceDescription  = 
11-25 14:32:06.146  5722  5738 D bt_bte_conf:   documentationURL    = 
,11-25 14:32:06.147  5722  5738 D bt_bte_conf: bte_load_did_conf no section named DID2.
11-25 14:32:06.147  5537  5537 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-25 14:32:06.147  5722  5735 D bt_stack_manager: event_start_up_stack finished
11-25 14:32:06.148  5722  5734 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
11-25 14:32:06.149  5722  5734 D BluetoothAdapterProperties: Setting state to 15
11-25 14:32:06.149  5722  5734 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
11-25 14:32:06.150  5722  5734 I BluetoothAdapterState: Entering BleOnState
11-25 14:32:06.151  5722  5742 I bt_vendor: low_power_mode_cb
,11-25 14:32:06.156  5722  5734 D BluetoothAdapterState: Current state: BLE ON, message: 1
11-25 14:32:06.156  5722  5734 D BluetoothAdapterProperties: Setting state to 11
,11-25 14:32:06.156  5722  5734 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
11-25 14:32:06.160  5722  5722 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@91cfe3b
11-25 14:32:06.161  5722  5722 D HeadsetService: Received start request. Starting profile...
,11-25 14:32:06.166  5722  5722 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,11-25 14:32:06.166  5722  5722 D HeadsetStateMachine: make
11-25 14:32:06.166  5537  5537 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-25 14:32:06.179  5722  5734 I BluetoothAdapterState: Entering PendingCommandState
,11-25 14:32:06.180  5722  5722 D HeadsetStateMachine: max_hf_connections = 1
11-25 14:32:06.180  5722  5722 I bt_bluedroid: get_profile_interface handsfree
,11-25 14:32:06.180  5722  5738 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
11-25 14:32:06.183  5722  5722 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@91cfe3b
11-25 14:32:06.183  5722  5738 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
,11-25 14:32:06.183  5722  5722 D A2dpService: Received start request. Starting profile...
,11-25 14:32:06.184  5722  5722 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,11-25 14:32:06.185  5722  5722 I bt_bluedroid: get_profile_interface avrcp
,11-25 14:32:06.190  5722  5722 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,11-25 14:32:06.190  5722  5722 I BluetoothA2dpServiceJni: classInitNative: succeeds
11-25 14:32:06.191  5722  5722 D A2dpStateMachine: make
,11-25 14:32:06.192  5722  5722 I bt_bluedroid: get_profile_interface a2dp
,11-25 14:32:06.192  5722  5738 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,11-25 14:32:06.194  5722  5753 D A2dpStateMachine: Enter Disconnected: -2
,11-25 14:32:06.194  5722  5722 I BluetoothHidServiceJni: classInitNative: succeeds
,11-25 14:32:06.195  5722  5722 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@91cfe3b
11-25 14:32:06.197  5722  5722 D HidService: Received start request. Starting profile...
11-25 14:32:06.197  5722  5722 I bt_bluedroid: get_profile_interface hidhost
11-25 14:32:06.197  5722  5722 D HidService: setHidService(): set to: null
,11-25 14:32:06.197  5722  5738 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf3fd056d
11-25 14:32:06.197  5722  5738 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
11-25 14:32:06.199  5722  5722 I BluetoothHealthServiceJni: classInitNative: succeeds
11-25 14:32:06.199  5722  5722 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@91cfe3b
11-25 14:32:06.201  5607  5607 D BluetoothInputDevice: Proxy object connected
,11-25 14:32:06.201  5722  5722 D HealthService: Received start request. Starting profile...
11-25 14:32:06.201  5607  5607 D HidProfile: Bluetooth service connected
11-25 14:32:06.202  3504  3504 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,11-25 14:32:06.202  5722  5722 I bt_bluedroid: get_profile_interface health
,11-25 14:32:06.203  5722  5722 I BluetoothPanServiceJni: classInitNative(L105): succeeds
11-25 14:32:06.204  5722  5722 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@91cfe3b
11-25 14:32:06.205  5607  5607 D BluetoothPan: BluetoothPAN Proxy object connected
11-25 14:32:06.205  5722  5722 D PanService: Received start request. Starting profile...
11-25 14:32:06.205  5722  5722 D BluetoothPanServiceJni: initializeNative(L110): pan
11-25 14:32:06.205  5722  5722 I bt_bluedroid: get_profile_interface pan
11-25 14:32:06.206  5607  5607 D PanProfile: Bluetooth service connected
11-25 14:32:06.206  5722  5738 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,11-25 14:32:06.209  5722  5722 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@91cfe3b
,11-25 14:32:06.210  5607  5607 D BluetoothMap: Proxy object connected
11-25 14:32:06.210  5722  5722 D BluetoothMapService: Received start request. Starting profile...
,11-25 14:32:06.210  5722  5722 D BluetoothMapService: start()
11-25 14:32:06.211  5607  5607 D MapProfile: Bluetooth service connected
11-25 14:32:06.211  5607  5607 D BluetoothMap: getConnectedDevices()
11-25 14:32:06.212  5607  5607 D BluetoothMap: Bluetooth is Not enabled
,11-25 14:32:06.213  5722  5722 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,11-25 14:32:06.214  5722  5722 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
11-25 14:32:06.214  5722  5722 D BluetoothMapAppObserver: createReceiver()
11-25 14:32:06.215  5722  5722 D BluetoothMapAppObserver: initObservers()
11-25 14:32:06.215  5722  5722 D BluetoothMapAppObserver: getEnabledAccountItems()
,11-25 14:32:06.221  5722  5722 V SapService: SapBinder()
,11-25 14:32:06.221  5722  5722 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@91cfe3b
11-25 14:32:06.221  5722  5722 D SapService: Received start request. Starting profile...
11-25 14:32:06.222  5722  5722 V SapService: start()
,11-25 14:32:06.223  5722  5722 V BluetoothAdapterState: isTurningOff()=false
11-25 14:32:06.223  5722  5722 V BluetoothAdapterState: isTurningOn()=true
11-25 14:32:06.223  5722  5722 V BluetoothAdapterState: isBleTurningOn()=false
11-25 14:32:06.223  5722  5722 V BluetoothAdapterState: isBleTurningOff()=false
11-25 14:32:06.223  5722  5722 V BluetoothAdapterState: isTurningOff()=false
11-25 14:32:06.223  5722  5722 V BluetoothAdapterState: isTurningOn()=true
11-25 14:32:06.223  5722  5722 V BluetoothAdapterState: isBleTurningOn()=false
11-25 14:32:06.223  5722  5722 V BluetoothAdapterState: isBleTurningOff()=false
11-25 14:32:06.224  5722  5722 V BluetoothAdapterState: isTurningOff()=false
11-25 14:32:06.224  5722  5751 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
11-25 14:32:06.224  5722  5722 V BluetoothAdapterState: isTurningOn()=true
11-25 14:32:06.224  5722  5722 V BluetoothAdapterState: isBleTurningOn()=false
11-25 14:32:06.224  5722  5722 V BluetoothAdapterState: isBleTurningOff()=false
11-25 14:32:06.224  5722  5722 V BluetoothAdapterState: isTurningOff()=false
11-25 14:32:06.224  5722  5722 V BluetoothAdapterState: isTurningOn()=true
11-25 14:32:06.224  5722  5722 V BluetoothAdapterState: isBleTurningOn()=false
11-25 14:32:06.224  5722  5722 V BluetoothAdapterState: isBleTurningOff()=false
11-25 14:32:06.224  5722  5722 V BluetoothAdapterState: isTurningOff()=false
11-25 14:32:06.224  5722  5722 V BluetoothAdapterState: isTurningOn()=true
11-25 14:32:06.224  5722  5722 V BluetoothAdapterState: isBleTurningOn()=false
11-25 14:32:06.224  5722  5722 V BluetoothAdapterState: isBleTurningOff()=false
11-25 14:32:06.225  5722  5722 V BluetoothAdapterState: isTurningOff()=false
11-25 14:32:06.225  5722  5722 V BluetoothAdapterState: isTurningOn()=true
11-25 14:32:06.225  5722  5722 V BluetoothAdapterState: isBleTurningOn()=false
11-25 14:32:06.225  5722  5722 V BluetoothAdapterState: isBleTurningOff()=false
11-25 14:32:06.225  5722  5722 V BluetoothAdapterState: isTurningOff()=false
11-25 14:32:06.225  5722  5722 V BluetoothAdapterState: isTurningOn()=true
11-25 14:32:06.225  5722  5722 V BluetoothAdapterState: isBleTurningOn()=false
11-25 14:32:06.225  5722  5722 V BluetoothAdapterState: isBleTurningOff()=false
11-25 14:32:06.226  5722  5734 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
11-25 14:32:06.226  5722  5734 D BluetoothAdapterProperties: ScanMode =  20
,11-25 14:32:06.226  5722  5734 D BluetoothAdapterProperties: State =  11
11-25 14:32:06.227  5722  5738 D BluetoothAdapterProperties: Scan Mode:21
11-25 14:32:06.227  5722  5734 D BluetoothAdapterProperties: Setting state to 12
,11-25 14:32:06.227  5722  5734 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,11-25 14:32:06.227  5537  5537 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
11-25 14:32:06.228  5722  5738 D BluetoothAdapterProperties: Discoverable Timeout:120
11-25 14:32:06.228  3721  3738 D BluetoothHeadset: onBluetoothStateChange: up=true
11-25 14:32:06.229  5607  5619 D BluetoothMap: onBluetoothStateChange: up=true
,11-25 14:32:06.229  5722  5734 I BluetoothAdapterState: Entering OnState
11-25 14:32:06.229  3064  3075 D BluetoothInputDevice: onBluetoothStateChange: up=true
11-25 14:32:06.231  3064  3064 D BluetoothInputDevice: Proxy object connected
11-25 14:32:06.231  3064  3064 D HidProfile: Bluetooth service connected
11-25 14:32:06.231  5607  5622 D BluetoothPan: onBluetoothStateChange on: true
11-25 14:32:06.231  5607  5619 D BluetoothPbap: onBluetoothStateChange: up=true
11-25 14:32:06.231  5537  5537 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-25 14:32:06.231  5537  5537 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-25 14:32:06.231  5537  5537 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-25 14:32:06.231  5537  5537 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-25 14:32:06.231  5537  5537 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-25 14:32:06.231  5537  5537 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-25 14:32:06.231  5537  5537 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-25 14:32:06.231  5537  5537 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-25 14:32:06.231  5537  5537 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-25 14:32:06.232  3064  3076 D BluetoothHeadset: onBluetoothStateChange: up=true
11-25 14:32:06.233  3064  3946 D BluetoothPan: onBluetoothStateChange on: true
11-25 14:32:06.233  5537  5537 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
,11-25 14:32:06.234  3064  3064 D BluetoothPan: BluetoothPAN Proxy object connected
11-25 14:32:06.234  5607  5622 D BluetoothInputDevice: onBluetoothStateChange: up=true
11-25 14:32:06.234  3064  3064 D PanProfile: Bluetooth service connected
11-25 14:32:06.234   929   946 D BluetoothA2dp: onBluetoothStateChange: up=true
11-25 14:32:06.235  3064  3075 D BluetoothA2dp: onBluetoothStateChange: up=true
11-25 14:32:06.235   929   929 D BluetoothA2dp: Proxy object connected
11-25 14:32:06.236   929   946 D BluetoothHeadset: onBluetoothStateChange: up=true
11-25 14:32:06.236  3064  3064 D BluetoothA2dp: Proxy object connected
11-25 14:32:06.236  3064  3946 D BluetoothMap: onBluetoothStateChange: up=true
11-25 14:32:06.238   929   946 D BluetoothHeadset: onBluetoothStateChange: up=true
11-25 14:32:06.238  3064  3076 D BluetoothPbap: onBluetoothStateChange: up=true
11-25 14:32:06.238  3064  3064 D BluetoothMap: Proxy object connected
,11-25 14:32:06.238  3064  3064 D MapProfile: Bluetooth service connected
11-25 14:32:06.238  3064  3064 D BluetoothMap: getConnectedDevices()
11-25 14:32:06.240  5722  5722 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
11-25 14:32:06.240   929   946 D BluetoothHeadset: onBluetoothStateChange: up=true
11-25 14:32:06.241  5722  5722 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
11-25 14:32:06.241   929   929 I Telecom : BluetoothPhoneService: queryPhoneState
11-25 14:32:06.242  5537  5537 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
11-25 14:32:06.243  5537  5537 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-25 14:32:06.244  5607  5607 D LocalBluetoothProfileManager: Adding local A2DP profile
,11-25 14:32:06.244  5722  5722 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-25 14:32:06.246  5722  5722 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-25 14:32:06.247  5722  5722 D ObexServerSockets: Succeed to create listening sockets 
11-25 14:32:06.247  5722  5722 D ObexServerSockets0: startAccept()
11-25 14:32:06.247  5722  5722 D ObexServerSockets0: prepareForNewConnect()
,11-25 14:32:06.248  5607  5607 D LocalBluetoothProfileManager: Adding local HEADSET profile
11-25 14:32:06.249  5722  5722 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
11-25 14:32:06.250  5722  5722 D BluetoothSdpJni: SDP Create record success - handle: 0
11-25 14:32:06.251  5722  5722 D BluetoothMapService: onReceive
11-25 14:32:06.252  5722  5760 D ObexServerSockets0: Accepting socket connection...
11-25 14:32:06.252  5722  5722 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
11-25 14:32:06.252  5722  5722 D BluetoothMapService: STATE_ON
11-25 14:32:06.252  5722  5761 D ObexServerSockets0: Accepting socket connection...
,11-25 14:32:06.254  5722  5762 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-25 14:32:06.255  5607  5607 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,11-25 14:32:06.256  5722  5762 D BluetoothSdpJni: sdpCreateSapsRecordNative:
11-25 14:32:06.256  5722  5762 D BluetoothSdpJni: SDP Create record success - handle: 1
11-25 14:32:06.257  5607  5607 D BluetoothA2dp: Proxy object connected
,11-25 14:32:06.261  3504  3504 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,11-25 14:32:06.264  5607  5607 D DockEventReceiver: finishStartingService: stopping service
,11-25 14:32:06.270  3064  3064 D BluetoothPbap: Proxy object connected
,11-25 14:32:06.270  3064  3064 D PbapServerProfile: Bluetooth service connected
,11-25 14:32:06.273  5607  5607 D BluetoothPbap: Proxy object connected
,11-25 14:32:06.274  5607  5607 D PbapServerProfile: Bluetooth service connected
,11-25 14:32:06.275  5722  5722 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,11-25 14:32:06.275  5722  5722 D ObexServerSockets0: prepareForNewConnect()
11-25 14:32:06.277  5722  5766 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-25 14:32:06.290  5722  5770 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-25 14:32:06.291  5722  5770 I BtOppRfcommListener: Accept thread started.
,11-25 14:32:06.330   929   929 D BluetoothHeadset: Proxy object connected
,11-25 14:32:06.330  3064  5702 D BluetoothHeadset: Proxy object connected
,11-25 14:32:06.331  3064  3064 D HeadsetProfile: Bluetooth service connected
,11-25 14:32:06.331  3721  3739 D BluetoothHeadset: Proxy object connected
11-25 14:32:06.331   929   929 D BluetoothHeadset: Proxy object connected
11-25 14:32:06.331   929   929 D BluetoothHeadset: Proxy object connected
11-25 14:32:06.333  3064  3946 D BluetoothHeadset: Proxy object connected
11-25 14:32:06.333  3064  3064 D HeadsetProfile: Bluetooth service connected
,11-25 14:32:06.337   929   946 D BluetoothHeadset: Proxy object connected
,11-25 14:32:06.338   929   946 D BluetoothHeadset: Proxy object connected
,11-25 14:32:06.340   929   946 D BluetoothHeadset: Proxy object connected
,11-25 14:32:06.351  5607  5622 D BluetoothHeadset: Proxy object connected
,11-25 14:32:06.352  5607  5607 D HeadsetProfile: Bluetooth service connected
,11-25 14:32:06.944   577   577 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 14:32:07.885   929  2910 D ConnectivityService: handlePromptUnvalidated 101
,11-25 14:32:07.945   577   577 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 14:32:08.501  3578  3769 I Keyboard.Facilitator.LanguageModelFlusher: run()
,11-25 14:32:08.501  3578  3769 I Keyboard.Facilitator: flushDynamicLanguageModels()
,11-25 14:32:08.531  3504  3504 I ConfigService: onCreate
,11-25 14:32:08.946   577   577 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 14:32:09.947   577   577 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 14:32:10.191  5722  5734 D BluetoothAdapterState: Current state: ON, message: 23
,11-25 14:32:10.191  5722  5734 D BluetoothAdapterProperties: Setting state to 13
11-25 14:32:10.191  5722  5734 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,11-25 14:32:10.193  5722  5734 D BluetoothAdapterProperties: onBluetoothDisable()
11-25 14:32:10.194  5722  5734 I BluetoothAdapterState: Entering PendingCommandState
,11-25 14:32:10.197  5722  5722 D BluetoothMapService: onReceive
11-25 14:32:10.198  5722  5722 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
11-25 14:32:10.198  5722  5722 D BluetoothMapService: STATE_TURNING_OFF
11-25 14:32:10.199  5722  5722 D BluetoothMapService: MAP Service closeService in
11-25 14:32:10.199  5722  5722 D BluetoothMapMasInstance0: MAP Service shutdown
11-25 14:32:10.199  5722  5722 D ObexServerSockets0: shutdown(block = true)
11-25 14:32:10.199  5722  5760 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
11-25 14:32:10.200  5722  5722 D ObexServerSockets0: shutdown called from another thread - interrupt().
,11-25 14:32:10.201  5722  5722 D ObexServerSockets0: shutdown called from another thread - interrupt().
11-25 14:32:10.201  5722  5747 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
11-25 14:32:10.201  5722  5761 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
11-25 14:32:10.201  5537  5537 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,11-25 14:32:10.201  5537  5537 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-25 14:32:10.201  5537  5537 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-25 14:32:10.201  5537  5537 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-25 14:32:10.201  5537  5537 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-25 14:32:10.201  5537  5537 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-25 14:32:10.201  5537  5537 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-25 14:32:10.201  5537  5537 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-25 14:32:10.201  5537  5537 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-25 14:32:10.201  5537  5537 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-25 14:32:10.205  5537  5537 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-25 14:32:10.205  5722  5738 D BluetoothAdapterProperties: Scan Mode:20
11-25 14:32:10.205  5537  5537 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
11-25 14:32:10.206  5722  5722 I BtOppRfcommListener: stopping Accept Thread
11-25 14:32:10.206  5722  5734 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
11-25 14:32:10.208  5722  5770 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,11-25 14:32:10.212  5722  5770 I BtOppRfcommListener: BluetoothSocket listen thread finished
11-25 14:32:10.213  5607  5607 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
11-25 14:32:10.214  5537  5537 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-25 14:32:10.218  5722  5722 D HeadsetService: Received stop request...Stopping profile...
,11-25 14:32:10.220   929   929 D BluetoothHeadset: Proxy object disconnected
,11-25 14:32:10.220  5607  5622 D BluetoothHeadset: Proxy object disconnected
,11-25 14:32:10.221  3064  3946 D BluetoothHeadset: Proxy object disconnected
11-25 14:32:10.221  5722  5722 D A2dpService: Received stop request...Stopping profile...
11-25 14:32:10.221  3721  3945 D BluetoothHeadset: Proxy object disconnected
11-25 14:32:10.222   929   929 D BluetoothHeadset: Proxy object disconnected
11-25 14:32:10.222  5722  5753 D A2dpStateMachine: Exit Disconnected: -1
11-25 14:32:10.222   929   929 D BluetoothHeadset: Proxy object disconnected
11-25 14:32:10.222   929   929 D BluetoothA2dp: Proxy object disconnected
,11-25 14:32:10.225  5722  5722 D HidService: Received stop request...Stopping profile...
,11-25 14:32:10.225  5722  5722 D HidService: Stopping Bluetooth HidService
,11-25 14:32:10.226  5607  5607 D DockEventReceiver: finishStartingService: stopping service
,11-25 14:32:10.227  5607  5607 D HeadsetProfile: Bluetooth service disconnected
11-25 14:32:10.227  5607  5607 D BluetoothA2dp: Proxy object disconnected
11-25 14:32:10.228  5607  5607 D BluetoothInputDevice: Proxy object disconnected
11-25 14:32:10.228  5607  5607 D HidProfile: Bluetooth service disconnected
11-25 14:32:10.228  3064  3064 D HeadsetProfile: Bluetooth service disconnected
11-25 14:32:10.228  3064  3064 D BluetoothA2dp: Proxy object disconnected
11-25 14:32:10.229  3064  3064 D BluetoothInputDevice: Proxy object disconnected
11-25 14:32:10.229  3064  3064 D HidProfile: Bluetooth service disconnected
,11-25 14:32:10.229  5722  5722 D HealthService: Received stop request...Stopping profile...
,11-25 14:32:10.231  5722  5722 V BluetoothAdapterState: isTurningOff()=true
11-25 14:32:10.231  5722  5722 V BluetoothAdapterState: isTurningOn()=false
11-25 14:32:10.231  5722  5722 V BluetoothAdapterState: isBleTurningOn()=false
11-25 14:32:10.231  5722  5722 V BluetoothAdapterState: isBleTurningOff()=false
11-25 14:32:10.232  5722  5722 D PanService: Received stop request...Stopping profile...
11-25 14:32:10.233  3064  3064 D BluetoothPan: BluetoothPAN Proxy object disconnected
11-25 14:32:10.233  3064  3064 D PanProfile: Bluetooth service disconnected
11-25 14:32:10.234  5607  5607 D BluetoothPan: BluetoothPAN Proxy object disconnected
11-25 14:32:10.234  5607  5607 D PanProfile: Bluetooth service disconnected
,11-25 14:32:10.235  5722  5722 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
11-25 14:32:10.235  5722  5722 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
11-25 14:32:10.235  5722  5745 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-25 14:32:10.235  5722  5745 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-25 14:32:10.235  5722  5745 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-25 14:32:10.236  5722  5738 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
11-25 14:32:10.236  5722  5738 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
11-25 14:32:10.236  5722  5722 D BluetoothMapService: Received stop request...Stopping profile...
11-25 14:32:10.236  5722  5722 D BluetoothMapService: stop()
11-25 14:32:10.237  5722  5722 D BluetoothMapAppObserver: deinitObservers()
11-25 14:32:10.237  5722  5722 D BluetoothMapAppObserver: removeReceiver()
,11-25 14:32:10.238  3064  3064 D BluetoothMap: Proxy object disconnected
11-25 14:32:10.238  3064  3064 D MapProfile: Bluetooth service disconnected
,11-25 14:32:10.238  5722  5722 V BluetoothAdapterState: isTurningOff()=true
11-25 14:32:10.238  5722  5722 V BluetoothAdapterState: isTurningOn()=false
11-25 14:32:10.238  5722  5722 V BluetoothAdapterState: isBleTurningOn()=false
11-25 14:32:10.238  5722  5722 V BluetoothAdapterState: isBleTurningOff()=false
11-25 14:32:10.239  5722  5722 D SapService: Received stop request...Stopping profile...
11-25 14:32:10.239  5722  5722 V SapService: stop()
11-25 14:32:10.240  5607  5607 D BluetoothMap: Proxy object disconnected
11-25 14:32:10.240  5607  5607 D MapProfile: Bluetooth service disconnected
,11-25 14:32:10.241  5722  5738 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
11-25 14:32:10.241  5722  5745 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,11-25 14:32:10.241  5722  5745 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-25 14:32:10.241  5722  5745 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
11-25 14:32:10.241  5722  5745 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
11-25 14:32:10.241  5722  5745 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
11-25 14:32:10.241  5722  5745 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,11-25 14:32:10.242  5722  5722 V BluetoothAdapterState: isTurningOff()=true
11-25 14:32:10.242  5722  5722 V BluetoothAdapterState: isTurningOn()=false
11-25 14:32:10.242  5722  5722 V BluetoothAdapterState: isBleTurningOn()=false
11-25 14:32:10.242  5722  5722 V BluetoothAdapterState: isBleTurningOff()=false
11-25 14:32:10.242  5722  5722 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
11-25 14:32:10.242  5722  5722 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
11-25 14:32:10.242  5722  5722 V BluetoothAdapterState: isTurningOff()=true
11-25 14:32:10.242  5722  5722 V BluetoothAdapterState: isTurningOn()=false
,11-25 14:32:10.243  5722  5722 V BluetoothAdapterState: isBleTurningOn()=false
11-25 14:32:10.243  5722  5722 V BluetoothAdapterState: isBleTurningOff()=false
11-25 14:32:10.243  5722  5722 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
,11-25 14:32:10.243  5722  5738 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
11-25 14:32:10.244  5722  5738 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
11-25 14:32:10.244  3504  3504 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
11-25 14:32:10.244  5722  5722 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
,11-25 14:32:10.250  5722  5722 V BluetoothAdapterState: isTurningOff()=true
,11-25 14:32:10.250  5722  5722 V BluetoothAdapterState: isTurningOn()=false
11-25 14:32:10.250  5722  5722 V BluetoothAdapterState: isBleTurningOn()=false
11-25 14:32:10.250  5722  5722 V BluetoothAdapterState: isBleTurningOff()=false
11-25 14:32:10.250  5722  5722 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
11-25 14:32:10.250  5722  5722 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
11-25 14:32:10.251  5722  5722 D BluetoothMapService: MAP Service closeService in
11-25 14:32:10.251  5722  5722 V BluetoothAdapterState: isTurningOff()=true
,11-25 14:32:10.251  5722  5722 V BluetoothAdapterState: isTurningOn()=false
11-25 14:32:10.251  5722  5722 V BluetoothAdapterState: isBleTurningOn()=false
11-25 14:32:10.251  5722  5722 V BluetoothAdapterState: isBleTurningOff()=false
11-25 14:32:10.251  5722  5722 D BluetoothMapService: cleanup()
11-25 14:32:10.251  5722  5722 D BluetoothMapService: MAP Service closeService in
11-25 14:32:10.251  5722  5722 V BluetoothAdapterState: isTurningOff()=true
11-25 14:32:10.252  5722  5722 V BluetoothAdapterState: isTurningOn()=false
11-25 14:32:10.252  5722  5722 V BluetoothAdapterState: isBleTurningOn()=false
11-25 14:32:10.252  5722  5722 V BluetoothAdapterState: isBleTurningOff()=false
11-25 14:32:10.252  5722  5734 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
,11-25 14:32:10.253  3064  3064 D BluetoothPbap: Proxy object disconnected
11-25 14:32:10.253  3064  3064 D PbapServerProfile: Bluetooth service disconnected
11-25 14:32:10.254  5607  5607 D BluetoothPbap: Proxy object disconnected
11-25 14:32:10.254  5607  5607 D PbapServerProfile: Bluetooth service disconnected
11-25 14:32:10.252  5722  5734 D BluetoothAdapterProperties: Setting state to 15
11-25 14:32:10.254  5722  5734 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
11-25 14:32:10.254  5722  5734 I BluetoothAdapterState: Entering BleOnState
11-25 14:32:10.255  3721  3911 D BluetoothHeadset: onBluetoothStateChange: up=false
,11-25 14:32:10.256  5607  5619 D BluetoothMap: onBluetoothStateChange: up=false
,11-25 14:32:10.257  5607  5622 D BluetoothA2dp: onBluetoothStateChange: up=false
,11-25 14:32:10.257  3064  3946 D BluetoothInputDevice: onBluetoothStateChange: up=false
11-25 14:32:10.258  5607  5619 D BluetoothPan: onBluetoothStateChange on: false
11-25 14:32:10.259  5607  5622 D BluetoothHeadset: onBluetoothStateChange: up=false
11-25 14:32:10.259  5607  5619 D BluetoothPbap: onBluetoothStateChange: up=false
11-25 14:32:10.259  3064  3075 D BluetoothHeadset: onBluetoothStateChange: up=false
11-25 14:32:10.260  3064  3076 D BluetoothPan: onBluetoothStateChange on: false
11-25 14:32:10.260  5607  5622 D BluetoothInputDevice: onBluetoothStateChange: up=false
11-25 14:32:10.260   929   946 D BluetoothA2dp: onBluetoothStateChange: up=false
11-25 14:32:10.261  3064  5702 D BluetoothA2dp: onBluetoothStateChange: up=false
11-25 14:32:10.261   929   946 D BluetoothHeadset: onBluetoothStateChange: up=false
11-25 14:32:10.261  3064  3946 D BluetoothMap: onBluetoothStateChange: up=false
11-25 14:32:10.262   929   946 D BluetoothHeadset: onBluetoothStateChange: up=false
11-25 14:32:10.262  3064  3075 D BluetoothPbap: onBluetoothStateChange: up=false
,11-25 14:32:10.262   929   946 D BluetoothHeadset: onBluetoothStateChange: up=false
11-25 14:32:10.262  5722  5734 D BluetoothAdapterState: Current state: BLE ON, message: 20
11-25 14:32:10.262  5722  5734 D BluetoothAdapterProperties: Setting state to 16
11-25 14:32:10.262  5722  5734 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
11-25 14:32:10.263  5722  5734 D BluetoothAdapterProperties: onBleDisable
11-25 14:32:10.263  5722  5734 I BluetoothAdapterState: Entering PendingCommandState
11-25 14:32:10.263  5722  5735 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
11-25 14:32:10.264  5722  5745 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
11-25 14:32:10.264  5722  5745 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-25 14:32:10.265  5537  5537 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-25 14:32:10.266  5722  5738 D BluetoothAdapterProperties: Scan Mode:20
11-25 14:32:10.266  5607  5607 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
11-25 14:32:10.268  5537  5537 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-25 14:32:10.270  3504  3504 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,11-25 14:32:10.272  5607  5607 D DockEventReceiver: finishStartingService: stopping service
,11-25 14:32:10.473  5722  5738 I bt_hci  : shut_down
,11-25 14:32:10.476  5722  5742 D bt_hwcfg: hw_epilog_process
,11-25 14:32:10.477  5722  5742 I bt_vendor: low_power_mode_cb
,11-25 14:32:10.479  5722  5742 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,11-25 14:32:10.479  5722  5742 I bt_vendor: epilog_cb
11-25 14:32:10.479  5722  5742 I bt_hci  : epilog_finished_callback
,11-25 14:32:10.481  5722  5738 I bt_hci_h4: hal_close
,11-25 14:32:10.481  5722  5738 I bt_userial_vendor: device fd = 54 close
,11-25 14:32:10.601  5722  5735 D bt_stack_manager: event_shut_down_stack finished.
,11-25 14:32:10.602  5722  5734 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,11-25 14:32:10.607  5722  5734 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,11-25 14:32:10.607  5722  5722 D BtGatt.DebugUtils: handleDebugAction() action=null
,11-25 14:32:10.608  5722  5722 D BtGatt.GattService: Received stop request...Stopping profile...
11-25 14:32:10.608  5722  5722 D BtGatt.GattService: stop()
11-25 14:32:10.609  5722  5722 D BtGatt.AdvertiseManager: advertise clients cleared
,11-25 14:32:10.613  5722  5722 V BluetoothAdapterState: isTurningOff()=false
,11-25 14:32:10.613  5722  5722 V BluetoothAdapterState: isTurningOn()=false
11-25 14:32:10.613  5722  5722 V BluetoothAdapterState: isBleTurningOn()=false
11-25 14:32:10.613  5722  5722 V BluetoothAdapterState: isBleTurningOff()=true
11-25 14:32:10.613  5722  5734 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
11-25 14:32:10.614  5722  5734 D BluetoothAdapterProperties: Setting state to 10
11-25 14:32:10.614  5722  5734 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
,11-25 14:32:10.616  5722  5734 I BluetoothAdapterState: Entering OffState
,11-25 14:32:10.616   929   946 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,11-25 14:32:10.629  5722  5722 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,11-25 14:32:10.629  5722  5722 W BluetoothSdpJni: Cleaning up Bluetooth Health object
11-25 14:32:10.629  5722  5722 I BluetoothServiceJni: cleanupNative: return from cleanup
,11-25 14:32:10.632  5722  5735 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,11-25 14:32:10.637  5722  5722 I art     : System.exit called, status: 0
,11-25 14:32:10.638  5722  5722 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,11-25 14:32:10.666   929  3520 I ActivityManager: Process com.android.bluetooth (pid 5722) has died
,11-25 14:32:10.948   577   577 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 14:32:11.948   577   577 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,11-25 14:32:13.564  3504  3504 I ConfigService: onDestroy
,11-25 14:32:15.187  5537  5585 D io.jxcore.node.ConnectivityMonitor: stop
,11-25 14:32:15.187  5537  5585 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
,11-25 14:32:15.193  5537  5585 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 14:32:15.193  5537  5585 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@7d01db1 removed from the list
11-25 14:32:15.193  5537  5585 D io.jxcore.node.ConnectivityMonitor: stop
,11-25 14:32:15.199  5537  5585 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,11-25 14:32:15.199  5537  5585 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2642204 added. We now have 4 listener(s)
11-25 14:32:15.200  5537  5585 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-25 14:32:15.201  5537  5585 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-25 14:32:15.202  5537  5585 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2642204 removed from the list
,11-25 14:32:15.203  5537  5585 D io.jxcore.node.ConnectivityMonitor: stop
,11-25 14:32:15.206  5537  5585 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,11-25 14:32:15.206  5537  5585 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@a17e3ed added. We now have 4 listener(s)
,11-25 14:32:15.206  5537  5585 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-25 14:32:20.217  5537  5585 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-25 14:32:20.251   929   946 I ActivityManager: Start proc 5779:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,11-25 14:32:20.336  5779  5779 D AdapterServiceConfig: Adding HeadsetService
,11-25 14:32:20.336  5779  5779 D AdapterServiceConfig: Adding A2dpService
11-25 14:32:20.337  5779  5779 D AdapterServiceConfig: Adding HidService
11-25 14:32:20.337  5779  5779 D AdapterServiceConfig: Adding HealthService
11-25 14:32:20.337  5779  5779 D AdapterServiceConfig: Adding PanService
11-25 14:32:20.337  5779  5779 D AdapterServiceConfig: Adding GattService
11-25 14:32:20.337  5779  5779 D AdapterServiceConfig: Adding BluetoothMapService
11-25 14:32:20.337  5779  5779 D AdapterServiceConfig: Adding SapService
,11-25 14:32:20.350   929   946 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1dcf233:true
,11-25 14:32:20.350  5779  5779 D BluetoothAdapterState: make() - Creating AdapterState
,11-25 14:32:20.353  5779  5779 I bt_bluedroid: init
,11-25 14:32:20.353  5779  5791 I BluetoothAdapterState: Entering OffState
,11-25 14:32:20.355  5779  5792 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,11-25 14:32:20.355  5779  5792 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
11-25 14:32:20.355  5779  5792 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
11-25 14:32:20.355  5779  5792 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
11-25 14:32:20.356  5779  5779 I bt_bluedroid: get_profile_interface socket
,11-25 14:32:20.357  5779  5795 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:D4
,11-25 14:32:20.358  5779  5779 I bt_bluedroid: get_profile_interface sdp
11-25 14:32:20.359  5779  5795 D BluetoothAdapterProperties: Name is: Nexus 6P
,11-25 14:32:20.363  5779  5790 I bt_bluedroid: config_hci_snoop_log
,11-25 14:32:20.364   929   946 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,11-25 14:32:20.368  5779  5791 D BluetoothAdapterState: Current state: OFF, message: 0
,11-25 14:32:20.368  5779  5791 D BluetoothAdapterProperties: Setting state to 14
11-25 14:32:20.368  5779  5791 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
11-25 14:32:20.370  5779  5791 D BluetoothBondStateMachine: make
,11-25 14:32:20.372  5779  5796 I BluetoothBondStateMachine: StableState(): Entering Off State
,11-25 14:32:20.374  5779  5791 I BluetoothAdapterState: Entering PendingCommandState
,11-25 14:32:20.375  5779  5779 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,11-25 14:32:20.377  5779  5779 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@91cfe3b
11-25 14:32:20.378  5779  5779 D BtGatt.DebugUtils: handleDebugAction() action=null
11-25 14:32:20.378  5779  5779 D BtGatt.GattService: Received start request. Starting profile...
11-25 14:32:20.379  5779  5779 D BtGatt.GattService: start()
,11-25 14:32:20.379  5779  5779 I bt_bluedroid: get_profile_interface gatt
,11-25 14:32:20.380  5779  5779 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@91cfe3b
11-25 14:32:20.380  5779  5779 D BtGatt.AdvertiseManager: advertise manager created
,11-25 14:32:20.385  5779  5779 V BluetoothAdapterState: isTurningOff()=false
,11-25 14:32:20.385  5779  5779 V BluetoothAdapterState: isTurningOn()=false
11-25 14:32:20.385  5779  5779 V BluetoothAdapterState: isBleTurningOn()=true
11-25 14:32:20.385  5779  5779 V BluetoothAdapterState: isBleTurningOff()=false
11-25 14:32:20.385  5779  5791 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,11-25 14:32:20.386  5779  5791 I bt_bluedroid: bt_bluedroid
,11-25 14:32:20.387  5779  5792 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,11-25 14:32:20.387  5779  5792 I bt_hci  : start_up
,11-25 14:32:20.393  5779  5792 I bt_vendor: alloc value 0xf4071871
,11-25 14:32:20.393  5779  5792 I bt_vendor: init
11-25 14:32:20.393  5779  5792 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
11-25 14:32:20.393  5779  5792 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,11-25 14:32:20.508  5779  5792 D bt_hci  : start_up starting async portion
,11-25 14:32:20.508  5779  5799 I bt_hci  : event_finish_startup
11-25 14:32:20.509  5779  5799 I bt_hci_h4: hal_open
11-25 14:32:20.509  5779  5799 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,11-25 14:32:20.512  5779  5799 I bt_userial_vendor: device fd = 54 open
,11-25 14:32:20.508  5800  5800 W irq/448-msm_hs_: type=1400 audit(0.0:118): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-25 14:32:20.529  5779  5799 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,11-25 14:32:20.532  5779  5799 D bt_hwcfg: Chipset BCM4358A3
11-25 14:32:20.533  5779  5799 D bt_hwcfg: Target name = [BCM4358A3]
,11-25 14:32:20.533  5779  5799 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,11-25 14:32:21.046  5779  5799 I bt_hwcfg: bt vendor lib: set UART baud 115200
11-25 14:32:21.047  5779  5799 D bt_hwcfg: Settlement delay -- 100 ms
,11-25 14:32:21.047  5779  5799 I bt_hwcfg: Setting fw settlement delay to 100 
,11-25 14:32:21.181  5779  5799 I bt_hwcfg: bt vendor lib: set UART baud 3000000
11-25 14:32:21.182  5779  5799 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:D4
11-25 14:32:21.183  5779  5799 I bt_hwcfg: vendor lib fwcfg completed
,11-25 14:32:21.184  5779  5799 I bt_vendor: firmware callback
11-25 14:32:21.184  5779  5799 I bt_hci  : firmware_config_callback
,11-25 14:32:21.194  5779  5802 I bt_btu  : btu_task pending for preload complete event
,11-25 14:32:21.194  5779  5802 I bt_btu_task: Bluetooth chip preload is complete
,11-25 14:32:21.194  5779  5802 I bt_btu  : btu_task received preload complete event
,11-25 14:32:21.201  5779  5802 I         : BTE_InitTraceLevels -- TRC_HCI
11-25 14:32:21.201  5779  5802 I         : BTE_InitTraceLevels -- TRC_L2CAP
11-25 14:32:21.201  5779  5802 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,11-25 14:32:21.201  5779  5802 I         : BTE_InitTraceLevels -- TRC_AVDT
11-25 14:32:21.202  5779  5802 I         : BTE_InitTraceLevels -- TRC_AVRC
11-25 14:32:21.202  5779  5802 I         : BTE_InitTraceLevels -- TRC_A2D
11-25 14:32:21.202  5779  5802 I         : BTE_InitTraceLevels -- TRC_BNEP
11-25 14:32:21.202  5779  5802 I         : BTE_InitTraceLevels -- TRC_BTM
11-25 14:32:21.202  5779  5802 I         : BTE_InitTraceLevels -- TRC_GAP
,11-25 14:32:21.202  5779  5802 I         : BTE_InitTraceLevels -- TRC_PAN
11-25 14:32:21.202  5779  5802 I         : BTE_InitTraceLevels -- TRC_SDP
11-25 14:32:21.202  5779  5802 I         : BTE_InitTraceLevels -- TRC_GATT
11-25 14:32:21.202  5779  5802 I         : BTE_InitTraceLevels -- TRC_SMP
11-25 14:32:21.203  5779  5802 I         : BTE_InitTraceLevels -- TRC_BTAPP
,11-25 14:32:21.203  5779  5802 I         : BTE_InitTraceLevels -- TRC_BTIF
,11-25 14:32:21.300  5779  5802 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf3fef549
11-25 14:32:21.300  5779  5802 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf3fef549 
,11-25 14:32:21.317  5779  5795 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,11-25 14:32:21.319  5779  5795 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,11-25 14:32:21.320  5779  5795 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:D4
,11-25 14:32:21.322  5779  5795 D BluetoothAdapterProperties: Name is: Nexus 6P
,11-25 14:32:21.325  5779  5795 D BluetoothAdapterProperties: Scan Mode:20
11-25 14:32:21.325  5779  5795 D BluetoothAdapterProperties: Discoverable Timeout:120
,11-25 14:32:21.326  5779  5795 D bt_hci  : do_postload posting postload work item
11-25 14:32:21.326  5779  5799 I bt_hci  : event_postload
,11-25 14:32:21.326  5779  5799 I bt_vendor: sco_config_cb
11-25 14:32:21.326  5779  5799 I bt_hci  : sco_config_callback postload finished.
,11-25 14:32:21.329  5779  5795 D bt_bte_conf: Device ID record 1 : primary
11-25 14:32:21.329  5779  5795 D bt_bte_conf:   vendorId            = 000f
11-25 14:32:21.329  5779  5795 D bt_bte_conf:   vendorIdSource      = 0001
11-25 14:32:21.330  5779  5795 D bt_bte_conf:   product             = 1200
,11-25 14:32:21.330  5779  5795 D bt_bte_conf:   version             = 1436
,11-25 14:32:21.331  5779  5795 D bt_bte_conf:   clientExecutableURL = 
11-25 14:32:21.331  5779  5795 D bt_bte_conf:   serviceDescription  = 
11-25 14:32:21.331  5779  5795 D bt_bte_conf:   documentationURL    = 
11-25 14:32:21.331  5779  5795 D bt_bte_conf: bte_load_did_conf no section named DID2.
11-25 14:32:21.332  5779  5792 D bt_stack_manager: event_start_up_stack finished
,11-25 14:32:21.333  5779  5791 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
11-25 14:32:21.334  5779  5791 D BluetoothAdapterProperties: Setting state to 15
11-25 14:32:21.334  5779  5791 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
,11-25 14:32:21.335  5779  5799 I bt_vendor: low_power_mode_cb
11-25 14:32:21.335  5779  5791 I BluetoothAdapterState: Entering BleOnState
,11-25 14:32:21.339  5779  5791 D BluetoothAdapterState: Current state: BLE ON, message: 1
,11-25 14:32:21.339  5779  5791 D BluetoothAdapterProperties: Setting state to 11
11-25 14:32:21.339  5779  5791 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,11-25 14:32:21.346  5779  5779 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@91cfe3b
,11-25 14:32:21.347  5779  5779 D HeadsetService: Received start request. Starting profile...
11-25 14:32:21.350  5779  5779 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,11-25 14:32:21.352  5779  5779 D HeadsetStateMachine: make
,11-25 14:32:21.365  5779  5791 I BluetoothAdapterState: Entering PendingCommandState
,11-25 14:32:21.366  5779  5779 D HeadsetStateMachine: max_hf_connections = 1
11-25 14:32:21.366  5779  5779 I bt_bluedroid: get_profile_interface handsfree
11-25 14:32:21.367  5779  5795 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
11-25 14:32:21.367  5779  5795 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
,11-25 14:32:21.370  5779  5779 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@91cfe3b
,11-25 14:32:21.370  5779  5779 D A2dpService: Received start request. Starting profile...
11-25 14:32:21.371  5779  5779 I BluetoothAvrcpServiceJni: classInitNative: succeeds
11-25 14:32:21.371  5779  5779 I bt_bluedroid: get_profile_interface avrcp
,11-25 14:32:21.377  5779  5779 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,11-25 14:32:21.377  5779  5779 I BluetoothA2dpServiceJni: classInitNative: succeeds
11-25 14:32:21.377  5779  5779 D A2dpStateMachine: make
11-25 14:32:21.378  5779  5779 I bt_bluedroid: get_profile_interface a2dp
,11-25 14:32:21.380  5779  5795 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
11-25 14:32:21.380  5779  5810 D A2dpStateMachine: Enter Disconnected: -2
,11-25 14:32:21.381  5779  5779 I BluetoothHidServiceJni: classInitNative: succeeds
,11-25 14:32:21.382  5779  5779 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@91cfe3b
11-25 14:32:21.383  5779  5779 D HidService: Received start request. Starting profile...
11-25 14:32:21.383  5779  5779 I bt_bluedroid: get_profile_interface hidhost
11-25 14:32:21.383  5779  5779 D HidService: setHidService(): set to: null
11-25 14:32:21.383  5779  5795 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf3fd056d
11-25 14:32:21.383  5779  5795 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
11-25 14:32:21.383  3504  3504 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,11-25 14:32:21.383  5779  5779 I BluetoothHealthServiceJni: classInitNative: succeeds
11-25 14:32:21.384  5779  5779 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@91cfe3b
11-25 14:32:21.385  5779  5779 D HealthService: Received start request. Starting profile...
,11-25 14:32:21.386  5779  5779 I bt_bluedroid: get_profile_interface health
,11-25 14:32:21.387  5779  5779 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,11-25 14:32:21.388  5779  5779 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@91cfe3b
,11-25 14:32:21.388  5779  5779 D PanService: Received start request. Starting profile...
11-25 14:32:21.388  5779  5779 D BluetoothPanServiceJni: initializeNative(L110): pan
11-25 14:32:21.388  5779  5779 I bt_bluedroid: get_profile_interface pan
11-25 14:32:21.389  5779  5795 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,11-25 14:32:21.392  5779  5779 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@91cfe3b
,11-25 14:32:21.392  5779  5779 D BluetoothMapService: Received start request. Starting profile...
11-25 14:32:21.392  5779  5779 D BluetoothMapService: start()
,11-25 14:32:21.395  5779  5779 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
11-25 14:32:21.396  5779  5779 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
11-25 14:32:21.396  5779  5779 D BluetoothMapAppObserver: createReceiver()
11-25 14:32:21.397  5779  5779 D BluetoothMapAppObserver: initObservers()
11-25 14:32:21.397  5779  5779 D BluetoothMapAppObserver: getEnabledAccountItems()
,11-25 14:32:21.402  5779  5779 V SapService: SapBinder()
,11-25 14:32:21.403  5779  5779 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@91cfe3b
,11-25 14:32:21.403  5779  5779 D SapService: Received start request. Starting profile...
11-25 14:32:21.403  5779  5779 V SapService: start()
,11-25 14:32:21.405  5779  5779 V BluetoothAdapterState: isTurningOff()=false
11-25 14:32:21.405  5779  5779 V BluetoothAdapterState: isTurningOn()=true
11-25 14:32:21.405  5779  5779 V BluetoothAdapterState: isBleTurningOn()=false
11-25 14:32:21.405  5779  5779 V BluetoothAdapterState: isBleTurningOff()=false
11-25 14:32:21.405  5779  5808 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
11-25 14:32:21.405  5779  5779 V BluetoothAdapterState: isTurningOff()=false
11-25 14:32:21.406  5779  5779 V BluetoothAdapterState: isTurningOn()=true
11-25 14:32:21.406  5779  5779 V BluetoothAdapterState: isBleTurningOn()=false
11-25 14:32:21.406  5779  5779 V BluetoothAdapterState: isBleTurningOff()=false
,11-25 14:32:21.406  5779  5779 V BluetoothAdapterState: isTurningOff()=false
11-25 14:32:21.406  5779  5779 V BluetoothAdapterState: isTurningOn()=true
11-25 14:32:21.406  5779  5779 V BluetoothAdapterState: isBleTurningOn()=false
11-25 14:32:21.406  5779  5779 V BluetoothAdapterState: isBleTurningOff()=false
11-25 14:32:21.406  5779  5779 V BluetoothAdapterState: isTurningOff()=false
11-25 14:32:21.406  5779  5779 V BluetoothAdapterState: isTurningOn()=true
11-25 14:32:21.406  5779  5779 V BluetoothAdapterState: isBleTurningOn()=false
11-25 14:32:21.406  5779  5779 V BluetoothAdapterState: isBleTurningOff()=false
11-25 14:32:21.406  5779  5779 V BluetoothAdapterState: isTurningOff()=false
,11-25 14:32:21.406  5779  5779 V BluetoothAdapterState: isTurningOn()=true
11-25 14:32:21.406  5779  5779 V BluetoothAdapterState: isBleTurningOn()=false
11-25 14:32:21.407  5779  5779 V BluetoothAdapterState: isBleTurningOff()=false
11-25 14:32:21.407  5779  5779 V BluetoothAdapterState: isTurningOff()=false
11-25 14:32:21.407  5779  5779 V BluetoothAdapterState: isTurningOn()=true
11-25 14:32:21.407  5779  5779 V BluetoothAdapterState: isBleTurningOn()=false
11-25 14:32:21.407  5779  5779 V BluetoothAdapterState: isBleTurningOff()=false
11-25 14:32:21.407  5779  5779 V BluetoothAdapterState: isTurningOff()=false
11-25 14:32:21.408  5779  5779 V BluetoothAdapterState: isTurningOn()=true
11-25 14:32:21.408  5779  5779 V BluetoothAdapterState: isBleTurningOn()=false
11-25 14:32:21.408  5779  5779 V BluetoothAdapterState: isBleTurningOff()=false
11-25 14:32:21.408  5779  5791 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
11-25 14:32:21.408  5779  5791 D BluetoothAdapterProperties: ScanMode =  20
,11-25 14:32:21.408  5779  5791 D BluetoothAdapterProperties: State =  11
11-25 14:32:21.408  5779  5791 D BluetoothAdapterProperties: Setting state to 12
11-25 14:32:21.408  5779  5791 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
11-25 14:32:21.409  5779  5791 I BluetoothAdapterState: Entering OnState
11-25 14:32:21.409  3721  3945 D BluetoothHeadset: onBluetoothStateChange: up=true
11-25 14:32:21.410  5779  5795 D BluetoothAdapterProperties: Scan Mode:21
11-25 14:32:21.410  5779  5795 D BluetoothAdapterProperties: Discoverable Timeout:120
11-25 14:32:21.410  5607  5619 D BluetoothMap: onBluetoothStateChange: up=true
11-25 14:32:21.412  5607  5622 D BluetoothA2dp: onBluetoothStateChange: up=true
,11-25 14:32:21.414  5607  5607 D BluetoothMap: Proxy object connected
11-25 14:32:21.414  5607  5607 D MapProfile: Bluetooth service connected
,11-25 14:32:21.414  5607  5607 D BluetoothMap: getConnectedDevices()
,11-25 14:32:21.414  3064  3946 D BluetoothInputDevice: onBluetoothStateChange: up=true
11-25 14:32:21.416  5607  5619 D BluetoothPan: onBluetoothStateChange on: true
11-25 14:32:21.418  3064  3064 D BluetoothInputDevice: Proxy object connected
11-25 14:32:21.418  3064  3064 D HidProfile: Bluetooth service connected
11-25 14:32:21.418  5607  5622 D BluetoothHeadset: onBluetoothStateChange: up=true
11-25 14:32:21.419  5607  5815 D BluetoothPbap: onBluetoothStateChange: up=true
11-25 14:32:21.421  3064  3075 D BluetoothHeadset: onBluetoothStateChange: up=true
11-25 14:32:21.421  3064  5702 D BluetoothPan: onBluetoothStateChange on: true
,11-25 14:32:21.422  5779  5779 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,11-25 14:32:21.423  5607  5622 D BluetoothInputDevice: onBluetoothStateChange: up=true
11-25 14:32:21.423  3064  3064 D BluetoothPan: BluetoothPAN Proxy object connected
11-25 14:32:21.423  3064  3064 D PanProfile: Bluetooth service connected
11-25 14:32:21.423  5779  5779 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
11-25 14:32:21.424  5779  5779 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-25 14:32:21.424  5607  5607 D BluetoothA2dp: Proxy object connected
,11-25 14:32:21.425   929   946 D BluetoothA2dp: onBluetoothStateChange: up=true
11-25 14:32:21.426   929   929 D BluetoothA2dp: Proxy object connected
,11-25 14:32:21.426  3064  3076 D BluetoothA2dp: onBluetoothStateChange: up=true
11-25 14:32:21.426  5779  5779 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-25 14:32:21.427  5607  5607 D BluetoothPan: BluetoothPAN Proxy object connected
11-25 14:32:21.427  5607  5607 D PanProfile: Bluetooth service connected
11-25 14:32:21.427  5607  5607 D BluetoothInputDevice: Proxy object connected
11-25 14:32:21.427  5607  5607 D HidProfile: Bluetooth service connected
,11-25 14:32:21.427   929   946 D BluetoothHeadset: onBluetoothStateChange: up=true
11-25 14:32:21.427  3064  3064 D BluetoothA2dp: Proxy object connected
11-25 14:32:21.428  3064  3946 D BluetoothMap: onBluetoothStateChange: up=true
11-25 14:32:21.429  5779  5779 D ObexServerSockets: Succeed to create listening sockets 
11-25 14:32:21.429  5779  5779 D ObexServerSockets0: startAccept()
11-25 14:32:21.430  5779  5779 D ObexServerSockets0: prepareForNewConnect()
,11-25 14:32:21.430  3064  3064 D BluetoothMap: Proxy object connected
,11-25 14:32:21.431  3064  3064 D MapProfile: Bluetooth service connected
11-25 14:32:21.431  3064  3064 D BluetoothMap: getConnectedDevices()
,11-25 14:32:21.432  5779  5779 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
,11-25 14:32:21.432  5779  5779 D BluetoothSdpJni: SDP Create record success - handle: 0
11-25 14:32:21.432  5779  5817 D ObexServerSockets0: Accepting socket connection...
11-25 14:32:21.432  5779  5816 D ObexServerSockets0: Accepting socket connection...
,11-25 14:32:21.432   929   946 D BluetoothHeadset: onBluetoothStateChange: up=true
11-25 14:32:21.433  3064  3075 D BluetoothPbap: onBluetoothStateChange: up=true
,11-25 14:32:21.439   929   946 D BluetoothHeadset: onBluetoothStateChange: up=true
,11-25 14:32:21.440   929   929 I Telecom : BluetoothPhoneService: queryPhoneState
,11-25 14:32:21.440  5779  5779 D BluetoothMapService: onReceive
11-25 14:32:21.440  5779  5779 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
11-25 14:32:21.441  5779  5779 D BluetoothMapService: STATE_ON
,11-25 14:32:21.443  5779  5818 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-25 14:32:21.444  5779  5818 D BluetoothSdpJni: sdpCreateSapsRecordNative:
11-25 14:32:21.444  5779  5818 D BluetoothSdpJni: SDP Create record success - handle: 1
,11-25 14:32:21.449  5607  5607 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,11-25 14:32:21.453  5607  5607 D DockEventReceiver: finishStartingService: stopping service
11-25 14:32:21.456  3504  3504 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,11-25 14:32:21.463  5607  5607 D BluetoothPbap: Proxy object connected
11-25 14:32:21.464  5607  5607 D PbapServerProfile: Bluetooth service connected
,11-25 14:32:21.464  5779  5779 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
11-25 14:32:21.464  3064  3064 D BluetoothPbap: Proxy object connected
11-25 14:32:21.464  5779  5779 D ObexServerSockets0: prepareForNewConnect()
11-25 14:32:21.465  3064  3064 D PbapServerProfile: Bluetooth service connected
11-25 14:32:21.467  5779  5820 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-25 14:32:21.483  5779  5826 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-25 14:32:21.485  5779  5826 I BtOppRfcommListener: Accept thread started.
,11-25 14:32:21.511   929   929 D BluetoothHeadset: Proxy object connected
,11-25 14:32:21.511  5607  5622 D BluetoothHeadset: Proxy object connected
11-25 14:32:21.512  3064  3946 D BluetoothHeadset: Proxy object connected
11-25 14:32:21.512  3064  3064 D HeadsetProfile: Bluetooth service connected
11-25 14:32:21.512  3721  3911 D BluetoothHeadset: Proxy object connected
11-25 14:32:21.512   929   929 D BluetoothHeadset: Proxy object connected
,11-25 14:32:21.512   929   929 D BluetoothHeadset: Proxy object connected
,11-25 14:32:21.514  5607  5607 D HeadsetProfile: Bluetooth service connected
,11-25 14:32:21.519  5607  5815 D BluetoothHeadset: Proxy object connected
,11-25 14:32:21.520  5607  5607 D HeadsetProfile: Bluetooth service connected
,11-25 14:32:21.521  3064  3076 D BluetoothHeadset: Proxy object connected
11-25 14:32:21.521  3064  3064 D HeadsetProfile: Bluetooth service connected
,11-25 14:32:21.528   929   946 D BluetoothHeadset: Proxy object connected
,11-25 14:32:21.533   929   946 D BluetoothHeadset: Proxy object connected
,11-25 14:32:21.539   929   946 D BluetoothHeadset: Proxy object connected
,11-25 14:32:21.950   577   577 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 14:32:22.951   577   577 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 14:32:23.952   577   577 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 14:32:24.954   577   577 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 14:32:25.234  5537  5585 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-25 14:32:25.234  5537  5585 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-25 14:32:25.234  5537  5585 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-25 14:32:25.234  5537  5585 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-25 14:32:25.234  5537  5585 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-25 14:32:25.234  5537  5585 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-25 14:32:25.234  5537  5585 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-25 14:32:25.234  5537  5585 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-25 14:32:25.234  5537  5585 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,11-25 14:32:25.238  5537  5585 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
,11-25 14:32:25.239  5537  5585 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 14:32:25.239  5537  5585 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@a17e3ed removed from the list
11-25 14:32:25.240  5537  5585 D io.jxcore.node.ConnectivityMonitor: stop
,11-25 14:32:25.242  5537  5585 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,11-25 14:32:25.242  5537  5585 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@9ec7222 added. We now have 4 listener(s)
,11-25 14:32:25.243  5537  5585 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-25 14:32:25.246   929  3737 D WifiService: setWifiEnabled: false pid=5537, uid=10077
,11-25 14:32:25.246   929  3737 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-25 14:32:25.955   577   577 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 14:32:26.955   577   577 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,11-25 14:32:30.256  5537  5585 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-25 14:32:30.258   929  3337 D WifiService: setWifiEnabled: true pid=5537, uid=10077
11-25 14:32:30.258   929  3337 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-25 14:32:30.265   506   922 D SoftapController: Softap fwReload - Ok
,11-25 14:32:30.271   506   922 D CommandListener: Setting iface cfg
,11-25 14:32:30.271   506   922 D CommandListener: Trying to bring down wlan0
,11-25 14:32:30.273   506   922 D CommandListener: Clearing all IP addresses on wlan0
,11-25 14:32:30.281   929  2907 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,11-25 14:32:30.949   929  2907 D wifi    : set interface wlan0 flags (UP)
,11-25 14:32:30.955   929  2907 I WifiHAL : Initializing wifi
11-25 14:32:30.955   929  2907 I WifiHAL : Creating socket
11-25 14:32:30.959   929   946 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
11-25 14:32:30.960   929  2907 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
,11-25 14:32:30.960   929  2907 D wifi    : Did set static halHandle = 0x7f9669b180
11-25 14:32:30.960   929  2907 D wifi    : halHandle = 0x7f9669b180, mVM = 0x7fb2c4d140, mCls = 0x18c2
11-25 14:32:30.961   929  2907 D wifi    : array field set
,11-25 14:32:30.962   929  2907 I WifiNative-HAL: interface[0] = wlan0
11-25 14:32:30.965   929  5832 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=547984355712
11-25 14:32:30.966   929  5832 D wifi    : waitForHalEvents called, vm = 0x7fb2c4d140, obj = 0x18c2, env = 0x7f98ade200
,11-25 14:32:31.009  5833  5833 I wpa_supplicant: Successfully initialized wpa_supplicant
,11-25 14:32:31.065   929  2907 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,11-25 14:32:31.072  5833  5833 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,11-25 14:32:31.127  5833  5833 I wpa_supplicant: rfkill: Cannot open RFKILL control device
11-25 14:32:31.127  5833  5833 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,11-25 14:32:31.141   929  2907 D WifiConfigStore: Loading config and enabling all networks 
,11-25 14:32:31.175   929  2907 D WifiConfigStore: loaded 0 passpoint configs
,11-25 14:32:31.176   929  2907 W WifiConfigStore: Upgrading network 4 to android.uid.system:1000
,11-25 14:32:31.176   929  2907 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,11-25 14:32:31.177   929  2907 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
11-25 14:32:31.178   929  2907 W WifiConfigStore: Upgrading network 3 to android.uid.system:1000
,11-25 14:32:31.178   929  2907 W WifiConfigStore: Upgrading network 2 to android.uid.system:1000
,11-25 14:32:31.179   929  2907 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
11-25 14:32:31.180   929  2907 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 5
11-25 14:32:31.180   929  2907 E WifiConfigStore: found sortedWifiConfigurations : "AndroidAP"WPA_PSK
,11-25 14:32:31.180   929  2907 E WifiConfigStore: found sortedWifiConfigurations : "AndroidHotspot2346"WPA_PSK
11-25 14:32:31.180   929  2907 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
11-25 14:32:31.180   929  2907 E WifiConfigStore: found sortedWifiConfigurations : "Thali_internal"WPA_PSK
11-25 14:32:31.180   929  2907 E WifiConfigStore: found sortedWifiConfigurations : "MC"WPA_PSK
,11-25 14:32:31.183   929  2907 D WifiNative-HAL: Setting external_sim to 1
,11-25 14:32:31.183   929  2907 D wifi    : setting dfs flag to true, 0x7f98ead000
11-25 14:32:31.183   929  2907 D WifiStateMachine: Setting OUI to DA-A1-19
11-25 14:32:31.184   929  2907 D wifi    : setting scan oui 0x7f98ead000
,11-25 14:32:31.184  4357  4357 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
11-25 14:32:31.184   929  2907 D WifiHAL : Sending mac address OUI
,11-25 14:32:31.188   929  2907 E native  : do suspend false
,11-25 14:32:31.199   929  2907 D wifi    : android_net_wifi_setLinkLayerStats: 1
11-25 14:32:31.199   929   929 D RttService: SCAN_AVAILABLE : 3
11-25 14:32:31.199   506   922 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
11-25 14:32:31.200   929  2962 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,11-25 14:32:31.202   506   922 D CommandListener: Setting iface cfg
,11-25 14:32:31.207   929  2896 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '158 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 158 Failed to set address (No such device)'
,11-25 14:32:31.207   929  2896 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,11-25 14:32:31.219   929  2896 D WifiNative-HAL: p2pGetDeviceAddress
11-25 14:32:31.220   929  2896 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:70
,11-25 14:32:31.225   929   944 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=152768 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=20 mControllerEnergyUsed=76 }
,11-25 14:32:31.773  3649  4302 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,11-25 14:32:34.261  5833  5833 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-25 14:32:34.266  5833  5833 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-25 14:32:34.344   929  2907 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,11-25 14:32:34.345   929  2907 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3
11-25 14:32:34.345   929  2907 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-25 14:32:34.356   929  2907 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=0
,11-25 14:32:34.388   929  2907 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=0
,11-25 14:32:34.393  5833  5833 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,11-25 14:32:34.817  5833  5833 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,11-25 14:32:34.854  5833  5833 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,11-25 14:32:34.856  5833  5833 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,11-25 14:32:34.866   929  2907 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
11-25 14:32:34.866   929  2907 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-25 14:32:34.866   929  2910 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,11-25 14:32:34.886   929  2907 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-25 14:32:34.902   506   922 D CommandListener: Setting iface cfg
,11-25 14:32:34.908   929  2907 D WifiStateMachine: Start Dhcp Watchdog 3
,11-25 14:32:34.914   929  5847 D DhcpClient: Receive thread started
,11-25 14:32:34.920   929  2910 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-25 14:32:34.920   929  2907 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
11-25 14:32:34.921   929  2910 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 102] to 60
,11-25 14:32:35.001   929  2907 E native  : do suspend false
,11-25 14:32:35.013   929  5846 D DhcpClient: Broadcasting DHCPDISCOVER
,11-25 14:32:35.028   929  5847 D DhcpClient: Received packet: 60:83:34:25:d7:70 OFFER, ip /192.168.1.109, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172765, domain null
,11-25 14:32:35.028   929  5846 D DhcpClient: Got pending lease: IP address 192.168.1.109/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172765 seconds
,11-25 14:32:35.031   929  5846 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.109 serverid=192.168.1.1
,11-25 14:32:35.043   929  5847 D DhcpClient: Received packet: 60:83:34:25:d7:70 ACK: your new IP /192.168.1.109, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,11-25 14:32:35.043   929  5846 D DhcpClient: Confirmed lease: IP address 192.168.1.109/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
11-25 14:32:35.047   506   922 D CommandListener: Setting iface cfg
,11-25 14:32:35.052   929  2907 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,11-25 14:32:35.056   929  5846 D DhcpClient: Scheduling renewal in 86399s
,11-25 14:32:35.065   929  2907 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,11-25 14:32:35.066   929  2907 D WifiConfigStore: No blacklist allowed without epno enabled
11-25 14:32:35.067   929  2910 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
11-25 14:32:35.071   929  2910 D ConnectivityService: Adding iface wlan0 to network 102
11-25 14:32:35.078   929  2907 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,11-25 14:32:35.120   929  2910 E ConnectivityService: Unexpected mtu value: 0, wlan0
,11-25 14:32:35.120   929  2910 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
,11-25 14:32:35.123   929  2910 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
,11-25 14:32:35.128   929  2910 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
,11-25 14:32:35.130   929  2910 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
,11-25 14:32:35.137   929  2910 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-25 14:32:35.142   929  2910 D ConnectivityService: scheduleUnvalidatedPrompt 102
,11-25 14:32:35.142   929  2910 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 102]
11-25 14:32:35.142   929  2910 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 102]
,11-25 14:32:35.142   929  2910 D ConnectivityService:    accepting network in place of null
11-25 14:32:35.142   929  2907 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
,11-25 14:32:35.142   929  2907 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
11-25 14:32:35.143   929  2910 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.109/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -65]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,11-25 14:32:35.159   929  5845 D NetlinkSocketObserver: NeighborEvent{elapsedMs=156702, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,11-25 14:32:35.168   506   922 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-25 14:32:35.200   506   922 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-25 14:32:35.203   929  2910 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
,11-25 14:32:35.204   929  2910 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
11-25 14:32:35.205   929  2910 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
11-25 14:32:35.205  3677  3779 W QCNEJ   : |CORE| network available: 102
11-25 14:32:35.206   929   946 D Tethering: MasterInitialState.processMessage what=3
11-25 14:32:35.210  3677  3779 W QCNEJ   : |CORE| onAvailable: bind the process to WIFI
11-25 14:32:35.212  3677  3779 W QCNEJ   : |CORE| newLp: {InterfaceName: wlan0 LinkAddresses: [192.168.1.109/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}
11-25 14:32:35.212  3677  3779 W QCNEJ   : |CORE| curLp: {InterfaceName: wlan0 LinkAddresses: [192.168.1.109/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,11-25 14:32:35.228  4854  4868 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
,11-25 14:32:35.228  4854  4868 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
11-25 14:32:35.228  4854  4868 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,1,0,0
11-25 14:32:35.229  4854  4868 E SarControlService: no key has been found,reset the power
,11-25 14:32:35.229  4854  4893 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
,11-25 14:32:35.229  4854  4893 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
11-25 14:32:35.229  4854  4893 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
11-25 14:32:35.230  4881  4881 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
11-25 14:32:35.230  4881  4881 D QcrilMsgTunnelSocket: [1008] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
,11-25 14:32:35.231  4854  4893 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
11-25 14:32:35.231  4854  4893 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
11-25 14:32:35.231  4854  4893 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
11-25 14:32:35.232  3895  3895 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
11-25 14:32:35.233  4881  4881 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
11-25 14:32:35.233  4881  4881 D QcrilMsgTunnelSocket: [1009] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
,11-25 14:32:35.235   929  5844 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=172.217.22.110,2a00:1450:400d:803::200e
11-25 14:32:35.238  4881  4895 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@716d172 HexData = [00000000f003000000000000ffffffff]
11-25 14:32:35.238  4881  4895 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-25 14:32:35.238  4881  4895 D QcrilMsgTunnelSocket: [1008] < OEM_HOOK_RAW [null]
,11-25 14:32:35.239  4881  4881 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
11-25 14:32:35.239  4854  4866 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
11-25 14:32:35.239  4881  4895 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@716d172 HexData = [00000000f103000000000000ffffffff]
11-25 14:32:35.239  4881  4895 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-25 14:32:35.239  4881  4895 D QcrilMsgTunnelSocket: [1009] < OEM_HOOK_RAW [null]
11-25 14:32:35.240  4881  4881 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
11-25 14:32:35.240  4854  4864 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
,11-25 14:32:35.243  3912  3912 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,11-25 14:32:35.246  3912  3912 D SystemUpdateService: onCreate
,11-25 14:32:35.249  3912  3912 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,11-25 14:32:35.267  3912  3912 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,11-25 14:32:35.270  5537  5585 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-25 14:32:35.270  5537  5585 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-25 14:32:35.270  5537  5585 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-25 14:32:35.270  5537  5585 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-25 14:32:35.270  5537  5585 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-25 14:32:35.270  5537  5585 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-25 14:32:35.270  5537  5585 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-25 14:32:35.270  5537  5585 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-25 14:32:35.270  5537  5585 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,11-25 14:32:35.272  5537  5585 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
,11-25 14:32:35.272  5537  5585 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 14:32:35.273  5537  5585 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@9ec7222 removed from the list
11-25 14:32:35.273  5537  5585 D io.jxcore.node.ConnectivityMonitor: stop
11-25 14:32:35.273  3912  5304 I iu.UploadsManager: num queued entries: 0
11-25 14:32:35.273  3912  5304 I iu.UploadsManager: num updated entries: 0
,11-25 14:32:35.276  5537  5585 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,11-25 14:32:35.277  5537  5585 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
11-25 14:32:35.279  5537  5585 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@6063b96 Bundle[{}]
11-25 14:32:35.279  5537  5585 I io.jxcore.node.LifeCycleMonitor: start: OK
11-25 14:32:35.279  5537  5585 I io.jxcore.node.LifeCycleMonitor: stop: OK
11-25 14:32:35.280  3912  3912 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
11-25 14:32:35.280  5537  5585 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,11-25 14:32:35.280  5537  5585 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
11-25 14:32:35.281  5537  5585 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
11-25 14:32:35.281  5537  5585 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
11-25 14:32:35.286  5537  5585 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 166)
11-25 14:32:35.287  5537  5585 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
11-25 14:32:35.287  5537  5585 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 167)
,11-25 14:32:35.289   929  5844 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Fri, 25 Nov 2016 13:32:35 GMT], X-Android-Received-Millis=[1480080755288], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1480080755265]}
,11-25 14:32:35.289  5537  5585 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,11-25 14:32:35.289  5537  5585 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@cbf24b3 added. We now have 3 listener(s)
,11-25 14:32:35.289   929  2910 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
11-25 14:32:35.289   929  2910 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] validation  passed
11-25 14:32:35.290   929  2910 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
11-25 14:32:35.290  3912  5860 I SystemUpdateService: active receiver: enabled
11-25 14:32:35.291   929  2910 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
11-25 14:32:35.292  5537  5585 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
,11-25 14:32:35.292  5537  5585 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-25 14:32:35.292  5537  5585 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-25 14:32:35.292  5537  5585 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-25 14:32:35.292  5537  5585 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@35a70 added. We now have 4 listener(s)
11-25 14:32:35.293  5537  5585 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-25 14:32:35.293  5537  5585 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,11-25 14:32:35.295  5537  5585 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-25 14:32:35.295  5537  5585 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@99bd1e9 added. We now have 4 listener(s)
11-25 14:32:35.296  5537  5585 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-25 14:32:35.296  5537  5585 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-25 14:32:35.296  5537  5585 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-25 14:32:35.296  5537  5585 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-25 14:32:35.296  5537  5585 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4838e6e added. We now have 5 listener(s)
11-25 14:32:35.296  5537  5585 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-25 14:32:35.296  5537  5585 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-25 14:32:35.296  5537  5585 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-25 14:32:35.296  5537  5585 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-25 14:32:35.296  5537  5585 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-25 14:32:35.296  5537  5585 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-25 14:32:35.296  5537  5585 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-25 14:32:35.296  5537  5585 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@cbf24b3 removed from the list
11-25 14:32:35.297  5537  5585 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 14:32:35.297  5537  5585 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@35a70 removed from the list
11-25 14:32:35.297  5537  5585 D io.jxcore.node.ConnectivityMonitor: stop
11-25 14:32:35.297  5537  5585 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-58,5,main], id: 58
11-25 14:32:35.297  5537  5585 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-58,5,main], id: 58
11-25 14:32:35.298  5537  5585 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-58,5,main], id: 58
11-25 14:32:35.298  5537  5585 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-58,5,main], id: 58
11-25 14:32:35.298  5537  5585 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-58,5,main], id: 58
11-25 14:32:35.298  5537  5585 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-25 14:32:35.298  5537  5585 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-25 14:32:35.298  5537  5585 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 14:32:35.298  5537  5585 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@35a70 not in the list
11-25 14:32:35.298  5537  5585 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-58,5,main], id: 58
11-25 14:32:35.298  5537  5585 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-58,5,main], id: 58
11-25 14:32:35.299  5537  5585 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-58,5,main], id: 58
11-25 14:32:35.299  5537  5585 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-58,5,main], id: 58
11-25 14:32:35.299  5537  5585 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-58,5,main], id: 58
11-25 14:32:35.299  5537  5585 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-25 14:32:35.299  5537  5585 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-25 14:32:35.299  5537  5585 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 14:32:35.299  5537  5585 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4838e6e removed from the list
11-25 14:32:35.299  5537  5585 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-25 14:32:35.299  5537  5585 D org.thaliproject.,p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-25 14:32:35.299  5537  5585 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-25 14:32:35.299  5537  5585 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@99bd1e9 removed from the list
11-25 14:32:35.300  5537  5585 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-25 14:32:35.300  5537  5585 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@87d590f added. We now have 3 listener(s)
11-25 14:32:35.301  5537  5585 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-25 14:32:35.301  5537  5585 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-25 14:32:35.301  5537  5585 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-25 14:32:35.301  5537  5585 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-25 14:32:35.302  5537  5585 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f1bad9c added. We now have 4 listener(s)
11-25 14:32:35.302  5537  5585 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-25 14:32:35.302  5537  5585 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
11-25 14:32:35.303  3912  3912 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
11-25 14:32:35.303  5537  5585 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-25 14:32:35.304  5537  5585 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@56a3a5 added. We now have 4 listener(s)
11-25 14:32:35.305  5537  5585 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-25 14:32:35.305  5537  5585 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-25 14:32:35.305  5537  5585 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-25 14:32:35.305  5537  5585 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-25 14:32:35.305  5537  5585 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@15e237a added. We now have 5 listener(s)
11-25 14:32:35.305  5537  5585 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-25 14:32:35.305  5537  5585 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-25 14:32:35.305  5537  5585 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
11-25 14:32:35.305  5537  5585 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
11-25 14:32:35.305  5537  5585 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-25 14:32:35.305  5537  5585 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
11-25 14:32:35.305  5308  5308 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
11-25 14:32:35.307  5537  5585 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
11-25 14:32:35.310  5537  5585 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-25 14:32:35.310  5537  5585 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-25 14:32:35.310  5537  5585 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
11-25 14:32:35.313  3912  5304 I iu.SyncManager: NEXT; no task
11-25 14:32:35.314  3912  5860 I SystemUpdateService: Already downloaded, skipping offpeak checks.
11-25 14:32:35.316  5308  5308 D SprintDMHelper: simOperator: 
11-25 14:32:35.316  5308  5308 D SprintDMReceiver: Not Sprint UICC, don't do anything.
11-25 14:32:35.318  5537  5585 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-58,5,main], id: 58
11-25 14:32:35.318  5537  5585 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-25 14:32:35.319  5537  5585 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-25 14:32:35.319  5537  5585 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-25 14:32:35.319  5537  5585 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 0
11-25 14:32:35.319  3912  5860 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
11-25 14:32:35.320  3912  5860 I SystemUpdateService: now status is 0 (complete)
11-25 14:32:35.320  3912  5860 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
11-25 14:32:35.320  3912  5860 I SystemUpdateService: file has been verified
11-25 14:32:35.320  3912  5860 I SystemUpdateService: OTA package size = 21989297
11-25 14:32:35.322  5537  5585 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-58,5,main], id: 58
11-25 14:32:35.323  5537  5585 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
11-25 14:32:35.323  5537  5585 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
11-25 14:32:35.323  5537  5585 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
11-25 14:32:35.323  5537  5585 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
11-25 14:32:35.323  5537  5585 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-58,5,main], id: 58
11-25 14:32:35.324  5537  5585 D BluetoothAdapter: STATE_ON
11-25 14:32:35.328  5779  5790 D BtGatt.GattService: registerClient() - UUID=262c983f-a512-4871-a1b9-b64c2e0a041f
11-25 14:32:35.329  5779  5795 D BtGatt.GattService: onClientRegistered() - UUID=262c983f-a512-4871-a1b9-b64c2e0a041f, clientIf=5
11-25 14:32:35.330  5537  5548 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
11-25 14:32:35.331  5779  5789 D BtGatt.GattService: start scan with filters
,11-25 14:32:35.335  5537  5585 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
11-25 14:32:35.335  5537  5585 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-58,5,main], id: 58
11-25 14:32:35.335  5779  5798 D BtGatt.ScanManager: handling starting scan
11-25 14:32:35.335  5537  5585 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
11-25 14:32:35.335  5537  5585 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-58,5,main], id: 58
11-25 14:32:35.335  5537  5585 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-25 14:32:35.335  5537  5537 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-25 14:32:35.335  5537  5537 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-25 14:32:35.335  5537  5537 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
11-25 14:32:35.336  5537  5537 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-25 14:32:35.336  5537  5537 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-25 14:32:35.336  5537  5537 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
11-25 14:32:35.336  5537  5537 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-25 14:32:35.336  5537  5537 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING] Current thread: Thread[main,5,main], id: 1
11-25 14:32:35.336  5537  5585 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-25 14:32:35.336  5537  5585 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-58,5,main], id: 58
11-25 14:32:35.337  5779  5798 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@91cfe3b
11-25 14:32:35.339  5537  5585 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-58,5,main], id: 58
11-25 14:32:35.339  5537  5585 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
11-25 14:32:35.339  5537  5585 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-58,5,main], id: 58
11-25 14:32:35.339  5537  5585 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-58,5,main], id: 58
11-25 14:32:35.339  5537  5585 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
11-25 14:32:35.339  5537  5585 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
11-25 14:32:35.339  5537  5585 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
11-25 14:32:35.339  5537  5585 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-25 14:32:35.339  5537  5585 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-25 14:32:35.339  5537  5585 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-25 14:32:35.339  5537  5537 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-25 14:32:35.340  5537  5585 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
11-25 14:32:35.342  5537  5537 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-25 14:32:35.342  5537  5537 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-25 14:32:35.342  5537  5537 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-25 14:32:35.342  5537  5585 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-25 14:32:35.342  5537  5537 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
11-25 14:32:35.342  5537  5585 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-58,5,main], id: 58
11-25 14:32:35.342  5537  5585 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
11-25 14:32:35.342  5537  5585 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-25 14:32:35.342  5537  5585 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-58,5,main], id: 58
11-25 14:32:35.342  5537  5585 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-58,5,main], id: 58
11-25 14:32:35.343  5537  5585 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-58,5,main], id: 58
11-25 14:32:35.343  5537  5585 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
11-25 14:32:35.343  5537  5585 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-58,5,main], id: 58
11-25 14:32:35.343  5537  5585 D BluetoothAdapter: STATE_ON
11-25 14:32:35.344  5779  5807 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
11-25 14:32:35.344  5537  5585 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-25 14:32:35.344  5537  5585 D BluetoothAdapter: STATE_ON
11-25 14:32:35.345  5779  5795 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
11-25 14:32:35.345  5779  5789 D BtGatt.GattService: stopScan() - queue size =1
11-25 14:32:35.345  5779  5795 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-25 14:32:35.345  5779  5798 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
11-25 14:32:35.345  5779  5807 D BtGatt.GattService: unregisterClient() - clientIf=5
11-25 14:32:35.346  5537  5585 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-25 14:32:35.346  5537  5585 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-58,5,main], id: 58
11-25 14:32:35.346  5537  5585 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
11-25 14:32:35.346  5537  5585 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-58,5,main], id: 58
11-25 14:32:35.346  5537  5585 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-58,5,main], id: 58
11-25 14:32:35.346  5537  5585 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-58,5,main], id: 58
11-25 14:32:35.346  5537  5585 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-58,5,main], id: 58
11-25 14:32:35.346  5537  5585 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-25 14:32:35.346  5537  5585 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-58,5,main], id: 58
11-25 14:32:35.346  5537  5585 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-58,5,main], id: 58
11-25 14:32:35.346  5537  5585 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-58,5,main], id: 58
11-25 14:32:35.346  5537  5585 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-25 14:32:35.346  5537  5585 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-25 14:32:35.347  5537  5585 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
11-25 14:32:35.348  5537  5585 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-58,5,main], id: 58
11-25 14:32:35.349  5537  5585 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-58,5,main], id: 58
11-25 14:32:35.349  5537  5585 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-25 14:32:35.349  5537  5585 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-58,5,main], id: 58
11-25 14:32:35.349  5537  5585 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-58,5,main], id: 58
11-25 14:32:35.349  5537  5537 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-25 14:32:35.349  5537  5537 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-25 14:32:35.349  5537  5537 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-25 14:32:35.349  5537  5537 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-25 14:32:35.349  5537  5537 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-25 14:32:35.349  5537  5537 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
11-25 14:32:35.349  5537  5537 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-25 14:32:35.349  5537  5537 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-25 14:32:35.349  5537  5537 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-25 14:32:35.349  5537  5537 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-25 14:32:35.350  5537  5537 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED] Current thread: Thread[main,5,main], id: 1
11-25 14:32:35.350  5537  5537 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-25 14:32:35.350  3912  5860 I SystemUpdateService: showing system update notification
11-25 14:32:35.351  5537  5537 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-25 14:32:35.351  5537  5537 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-25 14:32:35.351  5537  5537 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-25 14:32:35.351  5537  5585 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-25 14:32:35.351  5537  5585 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-25 14:32:35.351  5779  5795 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
11-25 14:32:35.351  5537  5585 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-25 14:32:35.351  5779  5795 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-25 14:32:35.351  5537  5585 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-25 14:32:35.352  5537  5585 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-25 14:32:35.352  5537  5585 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-25 14:32:35.352  5537  5585 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@87d590f removed from the list
11-25 14:32:35.352  5537  5585 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 14:32:35.352  5537  5585 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f1bad9c removed from the list
11-25 14:32:35.352  5537  5585 D io.jxcore.node.ConnectivityMonitor: stop
11-25 14:32:35.352  5779  5798 D BtGatt.ScanManager: Starting BLE batch scan
11-25 14:32:35.352  5537  5585 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-58,5,main], id: 58
11-25 14:32:35.352  5779  5798 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
11-25 14:32:35.352  5537  5585 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-58,5,main], id: 58
11-25 14:32:35.353  5537  5585 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-58,5,main], id: 58
11-25 14:32:35.353  5537  5585 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-58,5,main], id: 58
11-25 14:32:35.353  5537  5585 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-58,5,main], id: 58
11-25 14:32:35.353  5537  5585 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-25 14:32:35.353  5537  5585 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-25 14:32:35.353  5537  5585 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 14:32:35.353  5537  5585 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f1bad9c not in the list
11-25 14:32:35.353  5537  5585 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-58,5,main], id: 58
11-25 14:32:35.353  5537  5585 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-58,5,main], id: 58
11-25 14:32:35.354  5537  5585 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-58,5,main], id: 58
11-25 14:32:35.354  5537  5585 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-58,5,main], id: 58
11-25 14:32:35.355  5537  5585 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-58,5,main], id: 58
11-25 14:32:35.355  5537  5585 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-25 14:32:35.355  5537  5585 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-25 14:32:35.355  5537  5585 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 14:32:35.355  5537  5585 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@15e237a removed from the list
11-25 14:32:35.355  5537  5585 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-25 14:32:35.355  5537  5585 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-25 14:32:35.355  5537  5585 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-25 14:32:35.355  5537  5585 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@56a3a5 removed from the list
11-25 14:32:35.355  5537  5585 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-25 14:32:35.355  5537  5585 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8cd5b07 added. We now have 3 listener(s)
11-25 14:32:35.357  5537  5585 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-25 14:32:35.357  5537  5585 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-25 14:32:35.357  5537  5585 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-25 14:32:35.357  5537  5585 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-25 14:32:35.357  5537  5585 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f961434 added. We now have 4 listener(s)
11-25 14:32:35.357  5537  5585 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-25 14:32:35.357  5537  5585 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
11-25 14:32:35.359  3504  5870 I VacuumService: Vacuum at: now=1480080755359 tag=VacuumService
11-25 14:32:35.361  5537  5585 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-25 14:32:35.361  5537  5585 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@146a25d added. We now have 4 listener(s)
11-25 14:32:35.362  5779  5795 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
11-25 14:32:35.362  5779  5795 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-25 14:32:35.362   929   929 V NotificationService: pkg=com.google.android.gms canInterrupt=false intercept=true
11-25 14:32:35.363  5537  5585 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-25 14:32:35.363  5537  5585 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-25 14:32:35.363  5537  5585 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-25 14:32:35.363  5537  5585 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-25 14:32:35.364  5537  5585 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@179a7d2 added. We now have 5 listener(s)
11-25 14:32:35.364  5537  5585 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-25 14:32:35.364  5537  5585 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-25 14:32:35.364  5537  5585 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-25 14:32:35.364  5537  5585 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
11-25 14:32:35.365  5537  5585 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
11-25 14:32:35.365  5537  5585 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-25 14:32:35.365  5537  5585 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
11-25 14:32:35.366  3912  3912 D SystemUpdateService: onDestroy
11-25 14:32:35.366  5537  5585 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
11-25 14:32:35.369  5537  5585 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-25 14:32:35.369  5537  5585 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-25 14:32:35.369  5779  5795 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
11-25 14:32:35.370  5537  5585 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
11-25 14:32:35.370  5779  5795 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-25 14:32:35.376  5779  5798 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
11-25 14:32:35.377  5537  5585 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-58,5,main], id: 58
11-25 14:32:35.377  5537  5585 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-25 14:32:35.379  5537  5585 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-25 14:32:35.379  5537  5585 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-25 14:32:35.379  5537  5585 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 0
11-25 14:32:35.381  5779  5795 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-25 14:32:35.381  5779  5795 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-25 14:32:35.382  5779  5795 E BtGatt.ContextMap: Context not found for ID 5
11-25 14:32:35.383  5537  5585 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-58,5,main], id: 58
11-25 14:32:35.383  5537  5585 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
11-25 14:32:35.383  5537  5585 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
11-25 14:32:35.383  5537  5585 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
11-25 14:32:35.383  5537  5585 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
11-25 14:32:35.383  5537  5585 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-58,5,main], id: 58
11-25 14:32:35.384  5537  5585 D BluetoothAdapter: STATE_ON
11-25 14:32:35.386  5779  5807 D BtGatt.GattService: registerClient() - UUID=50b83c43-ddcf-4aa5-9567-274d6aaf5695
11-25 14:32:35.387  5779  5795 D BtGatt.GattService: onClientRegistered() - UUID=50b83c43-ddcf-4aa5-9567-274d6aaf5695, clientIf=5
11-25 14:32:35.387  5537  5548 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
11-25 14:32:35.388  5779  5790 D BtGatt.GattService: start scan with filters
11-25 14:32:35.388  5779  5795 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
11-25 14:32:35.388  5779  5795 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-25 14:32:35.389  5779  5798 D BtGatt.ScanManager: stopping BLe Batch
11-25 14:32:35.391  5537  5585 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
11-25 14:32:35.391  5537  5585 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-58,5,main], id: 58
11-25 14:32:35.391  5537  5585 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
11-25 14:32:35.391  5537  5585 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-58,5,main], id: 58
11-25 14:32:35.391  5537  5585 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-25 14:32:35.391  5537  5537 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-25 14:32:35.391  5537  5537 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-25 14:32:35.392  5537  5537 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
11-25 14:32:35.392  5537  5537 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-25 14:32:35.392  5537  5537 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-25 14:32:35.392  5537  5537 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
11-25 14:32:35.392  5537  5537 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-25 14:32:35.392  5537  5537 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING] Current thread: Thread[main,5,main], id: 1
11-25 14:32:35.392  5537  5585 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-25 14:32:35.393  5537  5585 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-58,5,main], id: 58
11-25 14:32:35.394  5779  5795 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
11-25 14:32:35.394  5779  5795 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-25 14:32:35.395  5537  5585 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-58,5,main], id: 58
11-25 14:32:35.395  5537  5585 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
11-25 14:32:35.395  5779  5798 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
11-25 14:32:35.395  5537  5585 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-58,5,main], id: 58
11-25 14:32:35.395  5537  5585 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-58,5,main], id: 58
11-25 14:32:35.395  5537  5537 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-25 14:32:35.395  5537  5585 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
11-25 14:32:35.395  5537  5585 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
11-25 14:32:35.395  5537  5585 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-25 14:32:35.395  5537  5585 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-25 14:32:35.395  5537  5585 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-25 14:32:35.396  5537  5585 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-25 14:32:35.396  5537  5585 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-25 14:32:35.396  5537  5585 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-25 14:32:35.396  5537  5585 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-25 14:32:35.396  5537  5585 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-25 14:32:35.396  5537  5585 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8cd5b07 removed from the list
11-25 14:32:35.396  5537  5585 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 14:32:35.396  5537  5585 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f961434 removed from the list
11-25 14:32:35.396  5537  5585 D io.jxcore.node.ConnectivityMonitor: stop
11-25 14:32:35.396  5537  5585 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-25 14:32:35.396  5537  5585 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-25 14:32:35.396  5537  5585 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-58,5,main], id: 58
11-25 14:32:35.396  5537  5585 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
11-25 14:32:35.396  5537  5585 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
11-25 14:32:35.396  5537  5585 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-25 14:32:35.396  5537  5585 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-25 14:32:35.396  5537  5585 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-58,5,main], id: 58
11-25 14:32:35.397  5537  5537 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-25 14:32:35.397  5537  5537 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-25 14:32:35.397  5537  5537 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-25 14:32:35.398  5537  5537 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
11-25 14:32:35.400  5779  5795 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-25 14:32:35.400  5779  5795 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-25 14:32:35.401  5537  5585 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-58,5,main], id: 58
11-25 14:32:35.401  5537  5585 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-58,5,main], id: 58
11-25 14:32:35.401  5537  5585 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-58,5,main], id: 58
11-25 14:32:35.401  5537  5585 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-25 14:32:35.401  5537  5585 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-25 14:32:35.401  5537  5585 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 14:32:35.401  5537  5585 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f961434 not in the list
11-25 14:32:35.401  5537  5585 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-25 14:32:35.401  5537  5585 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-58,5,main], id: 58
11-25 14:32:35.401  5537  5585 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
11-25 14:32:35.401  5537  5585 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-25 14:32:35.401  5537  5585 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-58,5,main], id: 58
11-25 14:32:35.402  5537  5585 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-58,5,main], id: 58
11-25 14:32:35.402  5537  5585 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-58,5,main], id: 58
11-25 14:32:35.402  5537  5585 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
11-25 14:32:35.402  5537  5585 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-58,5,main], id: 58
11-25 14:32:35.403  5779  5798 D BtGatt.ScanManager: handling starting scan
,11-25 14:32:35.404  5537  5585 D BluetoothAdapter: STATE_ON
11-25 14:32:35.404  5779  5789 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
11-25 14:32:35.404  5537  5585 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-25 14:32:35.405  5537  5585 D BluetoothAdapter: STATE_ON
11-25 14:32:35.405  5779  5807 D BtGatt.GattService: stopScan() - queue size =1
11-25 14:32:35.406  5779  5789 D BtGatt.GattService: unregisterClient() - clientIf=5
11-25 14:32:35.406  5537  5585 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-25 14:32:35.406  5537  5585 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-58,5,main], id: 58
11-25 14:32:35.406  5537  5585 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
11-25 14:32:35.406  5537  5585 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-58,5,main], id: 58
11-25 14:32:35.406  5537  5585 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-58,5,main], id: 58
11-25 14:32:35.406  5537  5585 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-58,5,main], id: 58
11-25 14:32:35.406  5537  5585 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-58,5,main], id: 58
11-25 14:32:35.406  5537  5585 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-25 14:32:35.406  5537  5585 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-58,5,main], id: 58
11-25 14:32:35.407  5537  5585 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-58,5,main], id: 58
11-25 14:32:35.407  5537  5585 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-58,5,main], id: 58
11-25 14:32:35.407  5537  5585 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-25 14:32:35.407  5537  5585 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-25 14:32:35.407  3504  5873 D GetConfigurationSnapshotOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
11-25 14:32:35.407  5537  5585 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
11-25 14:32:35.407  5779  5795 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
11-25 14:32:35.408  5779  5795 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-25 14:32:35.408  5779  5798 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
11-25 14:32:35.408  5537  5585 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-58,5,main], id: 58
11-25 14:32:35.409  5537  5585 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-58,5,main], id: 58
11-25 14:32:35.410  5537  5585 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-25 14:32:35.410  5537  5585 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-58,5,main], id: 58
11-25 14:32:35.410  5537  5585 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-58,5,main], id: 58
11-25 14:32:35.410  5537  5585 I org.thaliproject.p2p.btconnectorlib.DiscoveryM,anager: stopDiscovery
11-25 14:32:35.410  5537  5585 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-25 14:32:35.411  5537  5585 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 14:32:35.411  5537  5585 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@179a7d2 removed from the list
11-25 14:32:35.411  5537  5585 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-25 14:32:35.411  5537  5537 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-25 14:32:35.411  5537  5537 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-25 14:32:35.411  5537  5585 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-25 14:32:35.411  5537  5537 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-25 14:32:35.411  5537  5537 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-25 14:32:35.411  5537  5585 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-25 14:32:35.411  5537  5537 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-25 14:32:35.411  5537  5537 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
11-25 14:32:35.411  5537  5585 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@146a25d removed from the list
11-25 14:32:35.411  5537  5537 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-25 14:32:35.411  5537  5537 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-25 14:32:35.411  5537  5537 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-25 14:32:35.412  5537  5537 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-25 14:32:35.412  5537  5537 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED] Current thread: Thread[main,5,main], id: 1
11-25 14:32:35.412  5537  5537 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-25 14:32:35.412  5537  5585 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-25 14:32:35.412  5537  5585 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@feca3ff added. We now have 3 listener(s)
11-25 14:32:35.413  5779  5795 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
11-25 14:32:35.413  5779  5795 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-25 14:32:35.413  5537  5537 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-25 14:32:35.413  5779  5798 D BtGatt.ScanManager: Starting BLE batch scan
11-25 14:32:35.413  5779  5798 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
11-25 14:32:35.413  5537  5537 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11,-25 14:32:35.413  5537  5537 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-25 14:32:35.414  5537  5585 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-25 14:32:35.414  5537  5585 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-25 14:32:35.414  5537  5585 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-25 14:32:35.414  5537  5585 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-25 14:32:35.414  5537  5585 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7f3b5cc added. We now have 4 listener(s)
11-25 14:32:35.414  5537  5585 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-25 14:32:35.415  5537  5585 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
11-25 14:32:35.418  5537  5585 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-25 14:32:35.418  5537  5585 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@bf0c015 added. We now have 4 listener(s)
11-25 14:32:35.420  5537  5585 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-25 14:32:35.420  5537  5585 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-25 14:32:35.421  5537  5585 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-25 14:32:35.421  5537  5585 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-25 14:32:35.421  5537  5585 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5465f2a added. We now have 5 listener(s)
11-25 14:32:35.421  5537  5585 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-25 14:32:35.421  5537  5585 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-25 14:32:35.421  5537  5585 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
11-25 14:32:35.422  5537  5585 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
11-25 14:32:35.422  5537  5585 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-25 14:32:35.422  5537  5585 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
11-25 14:32:35.423  5779  5795 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
11-25 14:32:35.423  5779  5795 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-25 14:32:35.423  5537  5585 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
11-25 14:32:35.427  5537  5585 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-25 14:32:35.427  5537  5585 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-25 14:32:35.427  5537  5585 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
11-25 14:32:35.430  4357  5866 I Babel   : connection state changed from DISCONNECTED to CONNECTED
11-25 14:32:35.430  5537  5585 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-58,5,main], id: 58
11-25 14:32:35.430  5537  5585 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-25 14:32:35.431  5779  5795 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
11-25 14:32:35.431  5779  5795 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-25 14:32:35.431  5537  5585 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-25 14:32:35.432  5537  5585 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-25 14:32:35.432  5537  5585 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 0
11-25 14:32:35.433  5779  5798 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
11-25 14:32:35.434  5537  5585 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-58,5,main], id: 58
11-25 14:32:35.435  5537  5585 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
11-25 14:32:35.435  5537  5585 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
11-25 14:32:35.435  5537  5585 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
11-25 14:32:35.435  5537  5585 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
11-25 14:32:35.435  5537  5585 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-58,5,main], id: 58
11-25 14:32:35.436  5537  5585 D BluetoothAdapter: STATE_ON
11-25 14:32:35.437  5779  5795 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-25 14:32:35.437  5779  5795 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-25 14:32:35.437  5779  5795 E BtGatt.ContextMap: Context not found for ID 5
11-25 14:32:35.438  5779  5790 D BtGatt.GattService: registerClient() - UUID=e1f95583-af6a-4de9-abf0-08e434b28f83
11-25 14:32:35.438  5779  5795 D BtGatt.GattService: onClientRegistered() - UUID=e1f95583-af6a-4de9-abf0-08e434b28f83, clientIf=5
11-25 14:32:35.439  5537  5547 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
11-25 14:32:35.439  5779  5807 D BtGatt.GattService: start scan with filters
11-25 14:32:35.442  5537  5585 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
11-25 14:32:35.442  5537  5585 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-58,5,main], id: 58
11-25 14:32:35.442  5537  5585 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
11-25 14:32:35.442  5537  5585 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-58,5,main], id: 58
11-25 14:32:35.442  5537  5585 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-25 14:32:35.442  5537  5537 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-25 14:32:35.442  5537  5537 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-25 14:32:35.442  5537  5537 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
11-25 14:32:35.442  5537  5537 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-25 14:32:35.443  5537  5537 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-25 14:32:35.443  5537  5537 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
11-25 14:32:35.443  5537  5537 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-25 14:32:35.443  5537  5537 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING] Current thread: Thread[main,5,main], id: 1
11-25 14:32:35.443  5779  5795 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
11-25 14:32:35.443  5779  5795 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-25 14:32:35.443  5779  5798 D BtGatt.ScanManager: stopping BLe Batch
11-25 14:32:35.444  5537  5585 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-25 14:32:35.444  5537  5585 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-58,5,main], id: 58
11-25 14:32:35.446  5537  5585 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-58,5,main], id: 58
11-25 14:32:35.446  5537  5585 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
11-25 14:32:35.446  5537  5585 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-58,5,main], id: 58
11-25 14:32:35.446  5537  5585 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-58,5,main], id: 58
11-25 14:32:35.446  5537  5537 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-25 14:32:35.448  5537  5585 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-25 14:32:35.448  5537  5585 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-25 14:32:35.448  5537  5585 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-25 14:32:35.448  5537  5585 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-25 14:32:35.448  5537  5585 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-25 14:32:35.448  5779  5795 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
11-25 14:32:35.448  5537  5585 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-25 14:32:35.448  5779  5795 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-25 14:32:35.448  5537  5585 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-25 14:32:35.448  5779  5798 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
11-25 14:32:35.448  5537  5585 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-25 14:32:35.448  5537  5585 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@feca3ff removed from the list
11-25 14:32:35.448  5537  5585 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 14:32:35.448  5537  5585 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7f3b5cc removed from the list
11-25 14:32:35.449  5537  5585 D io.jxcore.node.ConnectivityMonitor: stop
11-25 14:32:35.449  5537  5585 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-25 14:32:35.449  5537  5585 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-25 14:32:35.449  5537  5585 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-58,5,main], id: 58
11-25 14:32:35.449  5537  5585 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
11-25 14:32:35.449  5537  5537 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-25 14:32:35.449  5537  5537 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-25 14:32:35.449  5537  5537 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-25 14:32:35.449  5537  5537 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
11-25 14:32:35.449  5537  5585 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
11-25 14:32:35.449  5537  5585 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-25 14:32:35.449  5537  5585 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-25 14:32:35.449  5537  5585 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-58,5,main], id: 58
,11-25 14:32:35.450  5537  5585 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-58,5,main], id: 58
11-25 14:32:35.450  5537  5585 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-58,5,main], id: 58
11-25 14:32:35.450  5537  5585 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-58,5,main], id: 58
11-25 14:32:35.450  5537  5585 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-25 14:32:35.451  5537  5585 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-25 14:32:35.451  5537  5585 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 14:32:35.451  5537  5585 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7f3b5cc not in the list
11-25 14:32:35.451  5537  5585 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-25 14:32:35.451  5537  5585 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-58,5,main], id: 58
11-25 14:32:35.451  5537  5585 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
11-25 14:32:35.451  5537  5585 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-25 14:32:35.451  5537  5585 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-58,5,main], id: 58
11-25 14:32:35.451  5537  5585 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-58,5,main], id: 58
11-25 14:32:35.451  5537  5585 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-58,5,main], id: 58
11-25 14:32:35.451  5537  5585 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
11-25 14:32:35.451  5537  5585 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-58,5,main], id: 58
11-25 14:32:35.452  3504  5871 I PhenotypeFlagCommitter: Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
11-25 14:32:35.452  5537  5585 D BluetoothAdapter: STATE_ON
11-25 14:32:35.453  5779  5790 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
11-25 14:32:35.453  5779  5795 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-25 14:32:35.453  5779  5795 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-25 14:32:35.453  5537  5585 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-25 14:32:35.454  5537  5585 D BluetoothAdapter: STATE_ON
11-25 14:32:35.454  3504  5871 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
11-25 14:32:35.455  5779  5789 D BtGatt.GattService: stopScan() - queue size =0
11-25 14:32:35.455  5779  5790 D BtGatt.GattService: unregisterClient() - clientIf=5
11-25 14:32:35.455  5537  5585 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-25 14:32:35.456  5537  5585 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-58,5,main], id: 58
11-25 14:32:35.456  5537  5585 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
11-25 14:32:35.456  5537  5585 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-58,5,main], id: 58
11-25 14:32:35.456  5537  5585 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-58,5,main], id: 58
11-25 14:32:35.456  5537  5585 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-58,5,main], id: 58
11-25 14:32:35.456  5537  5585 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-58,5,main], id: 58
11-25 14:32:35.456  5537  5585 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-25 14:32:35.456  5537  5585 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-58,5,main], id: 58
11-25 14:32:35.456  5537  5585 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-58,5,main], id: 58
11-25 14:32:35.456  5537  5585 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-58,5,main], id: 58
11-25 14:32:35.456  5537  5585 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-25 14:32:35.456  5537  5585 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-25 14:32:35.457  5779  5798 D BtGatt.ScanManager: handling starting scan
11-25 14:32:35.457  5537  5585 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
11-25 14:32:35.458  5537  5585 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-58,5,main], id: 58
11-25 14:32:35.459  5537  5585 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-58,5,main], id: 58
11-25 14:32:35.459  5537  5585 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-25 14:32:35.459  5537  5585 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-58,5,main], id: 58
11-25 14:32:35.459  5537  5585 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-58,5,main], id: 58
11-25 14:32:35.459  5537  5585 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-25 14:32:35.459  5537  5585 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-25 14:32:35.459  5537  5585 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 14:32:35.459  5537  5585 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5465f2a removed from the list
11-25 14:32:35.459  5537  5585 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-25 14:32:35.459  5537  5585 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-25 14:32:35.459  5537  5537 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-25 14:32:35.459  5537  5585 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-25 14:32:35.459  5537  5537 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-25 14:32:35.459  5537  5585 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@bf0c015 removed from the list
11-25 14:32:35.460  5537  5537 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-25 14:32:35.460  5537  5537 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-25 14:32:35.460  5537  5537 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-25 14:32:35.460  5537  5537 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
11-25 14:32:35.460  5537  5537 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-25 14:32:35.460  5537  5537 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-25 14:32:35.460  5537  5537 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-25 14:32:35.460  5537  5537 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-25 14:32:35.460  5537  5585 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-25 14:32:35.460  5537  5585 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@19d13f7 added. We now have 3 listener(s)
11-25 14:32:35.460  5537  5537 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED] Current thread: Thread[main,5,main], id: 1
11-25 14:32:35.460  5537  5537 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-25 14:32:35.461  5537  5585 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-25 14:32:35.461  5537  5585 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-25 14:32:35.461  5537  5585 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-25 14:32:35.462  5537  5585 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-25 14:32:35.462  5537  5585 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@400f264 added. We now have 4 listener(s)
11-25 14:32:35.462  5537  5585 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-25 14:32:35.462  5537  5585 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
11-25 14:32:35.462  5779  5795 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
11-25 14:32:35.462  5779  5795 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-25 14:32:35.463  5779  5798 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
11-25 14:32:35.463  5537  5537 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-25 14:32:35.463  5537  5537 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-25 14:32:35.463  5537  5537 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-25 14:32:35.464  5537  5585 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-25 14:32:35.464  5537  5585 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b99dccd added. We now have 4 listener(s)
11-25 14:32:35.465  5537  5585 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-25 14:32:35.465  5537  5585 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-25 14:32:35.465  5537  5585 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-25 14:32:35.465  5537  5585 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-25 14:32:35.466  5537  5585 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@557a982 added. We now have 5 listener(s)
11-25 14:32:35.466  5537  5585 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-25 14:32:35.466  5537  5585 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-25 14:32:35.466  5537  5585 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-25 14:32:35.466  5537  5585 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-25 14:32:35.466  5537  5585 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-25 14:32:35.466  5537  5585 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-25 14:32:35.466  5537  5585 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-25 14:32:35.466  5537  5585 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@19d13f7 removed from the list
11-25 14:32:35.466  5537  5585 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 14:32:35.466  5537  5585 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@400f264 removed from the list
11-25 14:32:35.466  5537  5585 D io.jxcore.node.ConnectivityMonitor: stop
11-25 14:32:35.466  5537  5585 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-58,5,main], id: 58
11-25 14:32:35.466  5537  5585 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-58,5,main], id: 58
11-25 14:32:35.467  5779  5795 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
11-25 14:32:35.467  5537  5585 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-58,5,main], id: 58
11-25 14:32:35.467  5537  5585 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-58,5,main], id: 58
11-25 14:32:35.467  5537  5585 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-58,5,main], id: 58
11-25 14:32:35.467  5537  5585 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-25 14:32:35.467  5537  5585 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-25 14:32:35.467  5537  5585 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 14:32:35.467  5537  5585 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@400f264 not in the list
11-25 14:32:35.467  5537  5585 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-58,5,main], id: 58
11-25 14:32:35.467  5537  5585 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-58,5,main], id: 58
11-25 14:32:35.468  5779  5795 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-25 14:32:35.468  5779  5798 D BtGatt.ScanManager: Starting BLE batch scan
11-25 14:32:35.468  5779  5798 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
11-25 14:32:35.468  5537  5585 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-58,5,main], id: 58
11-25 14:32:35.468  5537  5585 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-58,5,main], id: 58
11-25 14:32:35.469  5537  5585 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-58,5,main], id: 58
11-25 14:32:35.469  5537  5585 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-25 14:32:35.469  5537  5585 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-25 14:32:35.469  5537  5585 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 14:32:35.469  5537  5585 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@557a982 removed from the list
11-25 14:32:35.469  5537  5585 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-25 14:32:35.469  5537  5585 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-25 14:32:35.469  5537  5585 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-25 14:32:35.469  5537  5585 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b99dccd removed from the list
11-25 14:32:35.469  5537  5585 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
11-25 14:32:35.470  5537  5585 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
11-25 14:32:35.470  5537  5585 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
11-25 14:32:35.470  5537  5585 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-25 14:32:35.470  5537  5585 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
11-25 14:32:35.470  5537  5585 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
11-25 14:32:35.478  5779  5795 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
11-25 14:32:35.478  5779  5795 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-25 14:32:35.482  5779  5795 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
11-25 14:32:35.482  5779  5795 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-25 14:32:35.483  3504  5871 W Uploader:  no longer exists, so no auth token.
11-25 14:32:35.484  5779  5798 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
11-25 14:32:35.489  3504  5873 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
11-25 14:32:35.490  5779  5795 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-25 14:32:35.490  5779  5795 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-25 14:32:35.490  5779  5795 E BtGatt.ContextMap: Context not found for ID 5
,11-25 14:32:35.497  5779  5795 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
11-25 14:32:35.497  5779  5795 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-25 14:32:35.497  5779  5798 D BtGatt.ScanManager: stopping BLe Batch
11-25 14:32:35.501  5779  5795 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
11-25 14:32:35.501  5779  5795 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-25 14:32:35.501  5779  5798 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
11-25 14:32:35.506  5779  5795 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-25 14:32:35.506  5779  5795 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-25 14:32:35.738  3504  5876 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,11-25 14:32:35.851  5537  5537 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-25 14:32:35.911  5537  5537 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-25 14:32:35.920  3504  5871 W Uploader:  no longer exists, so no auth token.
,11-25 14:32:35.929  3504  5873 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,11-25 14:32:35.961  5537  5537 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-25 14:32:36.004  3504  5876 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,11-25 14:32:36.084  3504  5873 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,11-25 14:32:36.151  3504  5876 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,11-25 14:32:36.331   929  2907 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{4}, ntable=[192.168.1.1/NUD_REACHABLE]
,11-25 14:32:36.343   929  2910 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-25 14:32:36.350  3677  3779 W QCNEJ   : |CORE| newLp: {InterfaceName: wlan0 LinkAddresses: [192.168.1.109/24,fe80::6283:34ff:fe25:d770/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}
,11-25 14:32:36.352  3677  3779 W QCNEJ   : |CORE| curLp: {InterfaceName: wlan0 LinkAddresses: [192.168.1.109/24,fe80::6283:34ff:fe25:d770/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,11-25 14:32:37.604  5537  5882 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 175, name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
11-25 14:32:37.604  5537  5882 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-25 14:32:37.941   929  2910 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-25 14:32:38.412  5537  5882 W !!      : call onHalfStreamCopied
,11-25 14:32:38.412  5537  5882 I testCopyDataAndClose: closing input stream
,11-25 14:32:39.221  5537  5882 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 175, thread name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
11-25 14:32:39.221  5537  5882 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
11-25 14:32:39.221  5537  5882 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
11-25 14:32:39.221  5537  5882 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
11-25 14:32:39.221  5537  5882 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
11-25 14:32:39.221  5537  5882 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
,11-25 14:32:39.221  5537  5882 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
11-25 14:32:39.221  5537  5882 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
11-25 14:32:39.221  5537  5882 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
11-25 14:32:39.221  5537  5882 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 175, name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
11-25 14:32:39.221  5537  5882 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 20971520 and the total number of bytes written 20971520
,11-25 14:32:40.951   929  2910 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-25 14:32:41.957   577   577 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 14:32:42.958   577   577 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 14:32:43.146   929  2910 D ConnectivityService: handlePromptUnvalidated 102
,11-25 14:32:43.741  5537  5883 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 178, name: My test thread name). Connection data: Peer properties: [null null].
11-25 14:32:43.741  5537  5883 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-25 14:32:43.960   577   577 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 14:32:44.961   577   577 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 14:32:45.741  5537  5585 I io.jxcore.node.StreamCopyingThread: close: Thread ID: 178. Connection data: Peer properties: [null null].
11-25 14:32:45.741  5537  5585 I io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-25 14:32:45.741  5537  5585 D io.jxcore.node.StreamCopyingThread: closeStreams: Streams closed (thread ID: 178, name: My test thread name)
,11-25 14:32:45.788  5537  5883 D io.jxcore.node.StreamCopyingThread: number of bytes read = 0
,11-25 14:32:45.788  5537  5883 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 178, name: My test thread name). Connection data: Peer properties: [null null].
11-25 14:32:45.788  5537  5883 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 176 and the total number of bytes written 176
,11-25 14:32:45.879  5537  5884 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 180, name: testCopyBigData thread). Connection data: Peer properties: [null null].
11-25 14:32:45.879  5537  5884 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-25 14:32:45.962   577   577 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 14:32:46.228   929  2907 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 10, 11 -> obsolete
,11-25 14:32:46.963   577   577 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,11-25 14:32:47.517  5537  5884 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 180, thread name: testCopyBigData thread). Connection data: Peer properties: [null null].
11-25 14:32:47.517  5537  5884 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-25 14:32:47.517  5537  5884 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
11-25 14:32:47.517  5537  5884 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
11-25 14:32:47.517  5537  5884 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
11-25 14:32:47.517  5537  5884 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
11-25 14:32:47.517  5537  5884 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
11-25 14:32:47.517  5537  5884 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
11-25 14:32:47.517  5537  5884 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
11-25 14:32:47.517  5537  5884 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 180, name: testCopyBigData thread). Connection data: Peer properties: [null null].
11-25 14:32:47.517  5537  5884 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 20971520 and the total number of bytes written 20971520
,11-25 14:32:50.036   929  2910 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-25 14:32:51.771  5537  5885 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 182, name: My test thread name). Connection data: Peer properties: [null null].
11-25 14:32:51.771  5537  5885 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-25 14:32:51.772  5537  5885 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 182, thread name: My test thread name). Connection data: Peer properties: [null null].
11-25 14:32:51.772  5537  5885 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
11-25 14:32:51.772  5537  5885 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
11-25 14:32:51.772  5537  5885 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
11-25 14:32:51.772  5537  5885 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
11-25 14:32:51.772  5537  5885 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
11-25 14:32:51.772  5537  5885 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
,11-25 14:32:51.772  5537  5885 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
11-25 14:32:51.773  5537  5885 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
11-25 14:32:51.773  5537  5885 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 182, name: My test thread name). Connection data: Peer properties: [null null].
11-25 14:32:51.773  5537  5885 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 22
11-25 14:32:51.774  5537  5585 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,11-25 14:32:51.777  5537  5886 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 186, name: My test thread name). Connection data: Peer properties: [null null].
11-25 14:32:51.777  5537  5886 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-25 14:32:51.778  5537  5886 E io.jxcore.node.StreamCopyingThread: Failed to write to the output stream (thread ID: 186, thread name: My test thread name): Test exception.
11-25 14:32:51.778  5537  5886 D io.jxcore.node.StreamCopyingThread: onStreamCopyError (ID: 186, name: My test thread name). Connection data: Peer properties: [null null].
11-25 14:32:51.778  5537  5886 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
,11-25 14:32:51.779  5537  5886 D io.jxcore.node.StreamCopyingThread: number of bytes read = 22
11-25 14:32:51.779  5537  5886 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 186, name: My test thread name). Connection data: Peer properties: [null null].
11-25 14:32:51.779  5537  5886 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
,11-25 14:32:51.784  5537  5585 I jxcore-log: 2016-11-25 13:32:51 - DEBUG UnitTest_app: 'Total number of executed tests:  82'
11-25 14:32:51.784  5537  5585 I jxcore-log: 
,11-25 14:32:51.784  5537  5585 I jxcore-log: 2016-11-25 13:32:51 - DEBUG UnitTest_app: 'Number of passed tests:  82'
11-25 14:32:51.784  5537  5585 I jxcore-log: 
,11-25 14:32:51.785  5537  5585 I jxcore-log: 2016-11-25 13:32:51 - DEBUG UnitTest_app: 'Number of failed tests:  0'
11-25 14:32:51.785  5537  5585 I jxcore-log: 
11-25 14:32:51.785  5537  5585 I jxcore-log: 2016-11-25 13:32:51 - DEBUG UnitTest_app: 'Number of ignored tests:  0'
11-25 14:32:51.785  5537  5585 I jxcore-log: 
11-25 14:32:51.785  5537  5585 I jxcore-log: 2016-11-25 13:32:51 - DEBUG UnitTest_app: 'Total duration:  92072'
11-25 14:32:51.785  5537  5585 I jxcore-log: 
11-25 14:32:51.787  5537  5585 I jxcore-log: 2016-11-25 13:32:51 - DEBUG UnitTest_app: 'Unit Test app is loaded'
11-25 14:32:51.787  5537  5585 I jxcore-log: 
,11-25 14:32:51.790  5537  5585 I jxcore-log: 2016-11-25 13:32:51 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
11-25 14:32:51.790  5537  5585 I jxcore-log: 
11-25 14:32:51.792  5537  5585 I jxcore-log: 2016-11-25 13:32:51 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
11-25 14:32:51.792  5537  5585 I jxcore-log: 
11-25 14:32:51.792  5537  5585 I jxcore-log: 2016-11-25 13:32:51 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
11-25 14:32:51.792  5537  5585 I jxcore-log: 
11-25 14:32:51.792  5537  5585 I jxcore-log: 2016-11-25 13:32:51 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH"})'
11-25 14:32:51.792  5537  5585 I jxcore-log: 
11-25 14:32:51.793  5537  5585 I jxcore-log: 2016-11-25 13:32:51 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-25 14:32:51.793  5537  5585 I jxcore-log: 
11-25 14:32:51.793  5537  5585 I jxcore-log: 2016-11-25 13:32:51 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-25 14:32:51.793  5537  5585 I jxcore-log: 
11-25 14:32:51.793  5537  5585 I jxcore-log: 2016-11-25 13:32:51 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-25 14:32:51.793  5537  5585 I jxcore-log: 
,11-25 14:32:51.793  5537  5585 I jxcore-log: 2016-11-25 13:32:51 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
11-25 14:32:51.793  5537  5585 I jxcore-log: 
11-25 14:32:51.794  5537  5585 I jxcore-log: 2016-11-25 13:32:51 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
11-25 14:32:51.794  5537  5585 I jxcore-log: 
11-25 14:32:51.794  5537  5585 I jxcore-log: 2016-11-25 13:32:51 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
11-25 14:32:51.794  5537  5585 I jxcore-log: 
11-25 14:32:51.794  5537  5585 I jxcore-log: 2016-11-25 13:32:51 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH"})'
11-25 14:32:51.794  5537  5585 I jxcore-log: 
11-25 14:32:51.794  5537  5585 I jxcore-log: 2016-11-25 13:32:51 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-25 14:32:51.794  5537  5585 I jxcore-log: 
11-25 14:32:51.795  5537  5585 I jxcore-log: 2016-11-25 13:32:51 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-25 14:32:51.795  5537  5585 I jxcore-log: 
11-25 14:32:51.795  5537  5585 I jxcore-log: 2016-11-25 13:32:51 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-25 14:32:51.795  5537  5585 I jxcore-log: 
,11-25 14:32:51.795  5537  5585 I jxcore-log: 2016-11-25 13:32:51 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-25 14:32:51.795  5537  5585 I jxcore-log: 
11-25 14:32:51.795  5537  5585 I jxcore-log: 2016-11-25 13:32:51 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-25 14:32:51.795  5537  5585 I jxcore-log: 
11-25 14:32:51.796  5537  5585 I jxcore-log: 2016-11-25 13:32:51 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
11-25 14:32:51.796  5537  5585 I jxcore-log: 
11-25 14:32:51.796  5537  5585 I jxcore-log: 2016-11-25 13:32:51 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
11-25 14:32:51.796  5537  5585 I jxcore-log: 
11-25 14:32:51.796  5537  5585 I jxcore-log: 2016-11-25 13:32:51 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
11-25 14:32:51.796  5537  5585 I jxcore-log: 
11-25 14:32:51.796  5537  5585 I jxcore-log: 2016-11-25 13:32:51 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
11-25 14:32:51.796  5537  5585 I jxcore-log: 
,11-25 14:32:51.797  5537  5585 I jxcore-log: 2016-11-25 13:32:51 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
11-25 14:32:51.797  5537  5585 I jxcore-log: 
11-25 14:32:51.797  5537  5585 I jxcore-log: 2016-11-25 13:32:51 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
11-25 14:32:51.797  5537  5585 I jxcore-log: 
11-25 14:32:51.797  5537  5585 I jxcore-log: 2016-11-25 13:32:51 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
11-25 14:32:51.797  5537  5585 I jxcore-log: 
11-25 14:32:51.798  5537  5585 I jxcore-log: 2016-11-25 13:32:51 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
11-25 14:32:51.798  5537  5585 I jxcore-log: 
,11-25 14:32:51.799  5537  5585 I jxcore-log: 2016-11-25 13:32:51 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
11-25 14:32:51.799  5537  5585 I jxcore-log: 
,11-25 14:32:51.799  5537  5585 I jxcore-log: 2016-11-25 13:32:51 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
11-25 14:32:51.799  5537  5585 I jxcore-log: 
11-25 14:32:51.800  5537  5585 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-25 14:32:51.800  5537  5585 D io.jxcore.node.StartStopOperationHandler: Operation timeout, state error: null
,11-25 14:32:51.800  5537  5585 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-25 14:32:51.800  5537  5585 D io.jxcore.node.StartStopOperationHandler: Operation timeout, state error: Discovery manager not started
11-25 14:32:51.800  5537  5585 I jxcore-log: 2016-11-25 13:32:51 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-25 14:32:51.800  5537  5585 I jxcore-log: 
11-25 14:32:51.800  5537  5585 I jxcore-log: 2016-11-25 13:32:51 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-25 14:32:51.800  5537  5585 I jxcore-log: 
11-25 14:32:51.801  5537  5585 I jxcore-log: 2016-11-25 13:32:51 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-25 14:32:51.801  5537  5585 I jxcore-log: 
11-25 14:32:51.801  5537  5585 I jxcore-log: 2016-11-25 13:32:51 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-25 14:32:51.801  5537  5585 I jxcore-log: 
,11-25 14:32:51.801  5537  5585 I jxcore-log: 2016-11-25 13:32:51 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-25 14:32:51.801  5537  5585 I jxcore-log: 
11-25 14:32:51.801  5537  5585 I jxcore-log: 2016-11-25 13:32:51 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-25 14:32:51.801  5537  5585 I jxcore-log: 
,11-25 14:32:51.804  5537  5537 D SystemWebChromeClient: file:///android_asset/www/js/thali_main.js: Line 68 : UIApp is all set and ready!
11-25 14:32:51.805  5537  5537 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
,11-25 14:32:51.806  5537  5585 I jxcore-log: 2016-11-25 13:32:51 - DEBUG UnitTest_app: 'My device name is: Huawei-Nexus 6P'
11-25 14:32:51.806  5537  5585 I jxcore-log: 
,11-25 14:32:51.807  5537  5585 I jxcore-log: 2016-11-25 13:32:51 - WARN testUtils: 'myNameCallback not set!'
11-25 14:32:51.807  5537  5585 I jxcore-log: 
,11-25 14:32:53.066   929  2910 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-25 14:32:53.388   929  5845 D NetlinkSocketObserver: NeighborEvent{elapsedMs=174930, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,11-25 14:32:53.814  5537  5585 I jxcore-log: 2016-11-25 13:32:53 - INFO runTests: 'Starting tests. Network type: WIFI. Platform: android'
11-25 14:32:53.814  5537  5585 I jxcore-log: 
,11-25 14:32:53.817  5537  5585 I jxcore-log: 2016-11-25 13:32:53 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js'
11-25 14:32:53.817  5537  5585 I jxcore-log: 
,11-25 14:32:54.171  5537  5585 I jxcore-log: 2016-11-25 13:32:54 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js'
11-25 14:32:54.171  5537  5585 I jxcore-log: 
,11-25 14:32:54.183  5537  5585 I jxcore-log: 2016-11-25 13:32:54 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManager.js'
11-25 14:32:54.183  5537  5585 I jxcore-log: 
,11-25 14:32:55.313  5537  5585 I jxcore-log: 2016-11-25 13:32:55 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js'
11-25 14:32:55.313  5537  5585 I jxcore-log: 
,11-25 14:32:55.506  5537  5585 I jxcore-log: 2016-11-25 13:32:55 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js'
11-25 14:32:55.506  5537  5585 I jxcore-log: 
,11-25 14:32:55.511  5537  5585 I jxcore-log: 2016-11-25 13:32:55 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testNativeMethod.js'
11-25 14:32:55.511  5537  5585 I jxcore-log: 
,11-25 14:32:55.516  5537  5585 I jxcore-log: 2016-11-25 13:32:55 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPouchDBCheckpointPlugin.js'
11-25 14:32:55.516  5537  5585 I jxcore-log: 
,11-25 14:32:56.000  5537  5585 I jxcore-log: 2016-11-25 13:32:55 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPouchDBGenerator.js'
11-25 14:32:56.000  5537  5585 I jxcore-log: 
,11-25 14:32:56.044  5537  5585 I jxcore-log: 2016-11-25 13:32:56 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js'
11-25 14:32:56.044  5537  5585 I jxcore-log: 
,11-25 14:32:56.057  5537  5585 I jxcore-log: 2016-11-25 13:32:56 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js'
11-25 14:32:56.057  5537  5585 I jxcore-log: 
,11-25 14:32:56.061  5537  5585 I jxcore-log: 2016-11-25 13:32:56 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliManager.js'
11-25 14:32:56.061  5537  5585 I jxcore-log: 
,11-25 14:32:56.330  5537  5585 I jxcore-log: 2016-11-25 13:32:56 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliManagerCoordinated.js'
11-25 14:32:56.330  5537  5585 I jxcore-log: 
,11-25 14:32:56.456  5537  5585 I jxcore-log: 2016-11-25 13:32:56 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js'
11-25 14:32:56.456  5537  5585 I jxcore-log: 
,11-25 14:32:56.814  5537  5585 I jxcore-log: 2016-11-25 13:32:56 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js'
11-25 14:32:56.814  5537  5585 I jxcore-log: 
,11-25 14:32:56.822  5537  5585 I jxcore-log: 2016-11-25 13:32:56 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeDiscoveryCoordinated.js'
11-25 14:32:56.822  5537  5585 I jxcore-log: 
,11-25 14:32:56.826  5537  5585 I jxcore-log: 2016-11-25 13:32:56 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js'
11-25 14:32:56.826  5537  5585 I jxcore-log: 
,11-25 14:32:56.832  5537  5585 I jxcore-log: 2016-11-25 13:32:56 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js'
11-25 14:32:56.832  5537  5585 I jxcore-log: 
,11-25 14:32:56.837  5537  5585 I jxcore-log: 2016-11-25 13:32:56 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js'
11-25 14:32:56.837  5537  5585 I jxcore-log: 
,11-25 14:32:56.865  5537  5585 I jxcore-log: 2016-11-25 13:32:56 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js'
11-25 14:32:56.865  5537  5585 I jxcore-log: 
,11-25 14:32:56.900  5537  5585 I jxcore-log: 2016-11-25 13:32:56 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js'
11-25 14:32:56.900  5537  5585 I jxcore-log: 
,11-25 14:32:56.908  5537  5585 I jxcore-log: 2016-11-25 13:32:56 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationLocal.js'
11-25 14:32:56.908  5537  5585 I jxcore-log: 
,11-25 14:32:56.914  5537  5585 I jxcore-log: 2016-11-25 13:32:56 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js'
11-25 14:32:56.914  5537  5585 I jxcore-log: 
,11-25 14:32:56.930  5537  5585 I jxcore-log: 2016-11-25 13:32:56 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js'
11-25 14:32:56.930  5537  5585 I jxcore-log: 
,11-25 14:32:56.945  5537  5585 I jxcore-log: 2016-11-25 13:32:56 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js'
11-25 14:32:56.945  5537  5585 I jxcore-log: 
,11-25 14:32:56.951  5537  5585 I jxcore-log: 2016-11-25 13:32:56 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolDefault.js'
11-25 14:32:56.951  5537  5585 I jxcore-log: 
,11-25 14:32:56.957  5537  5585 I jxcore-log: 2016-11-25 13:32:56 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js'
11-25 14:32:56.957  5537  5585 I jxcore-log: 
,11-25 14:32:56.970  5537  5585 I jxcore-log: 2016-11-25 13:32:56 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolOneAtATime.js'
11-25 14:32:56.970  5537  5585 I jxcore-log: 
,11-25 14:32:56.988  5537  5585 I jxcore-log: 2016-11-25 13:32:56 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js'
11-25 14:32:56.988  5537  5585 I jxcore-log: 
,11-25 14:32:57.002  5537  5585 I jxcore-log: 2016-11-25 13:32:57 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js'
11-25 14:32:57.002  5537  5585 I jxcore-log: 
,11-25 14:32:57.013  5537  5585 I jxcore-log: 2016-11-25 13:32:57 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerAction.js'
11-25 14:32:57.013  5537  5585 I jxcore-log: 
,11-25 14:32:57.026  5537  5585 I jxcore-log: 2016-11-25 13:32:57 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js'
11-25 14:32:57.026  5537  5585 I jxcore-log: 
,11-25 14:32:57.036  5537  5585 I jxcore-log: 2016-11-25 13:32:57 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js'
11-25 14:32:57.036  5537  5585 I jxcore-log: 
,11-25 14:32:57.049  5537  5585 I jxcore-log: 2016-11-25 13:32:57 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js'
11-25 14:32:57.049  5537  5585 I jxcore-log: 
,11-25 14:32:57.069  5537  5585 I jxcore-log: 2016-11-25 13:32:57 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js'
11-25 14:32:57.069  5537  5585 I jxcore-log: 
,11-25 14:32:57.076  5537  5585 I jxcore-log: 2016-11-25 13:32:57 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js'
11-25 14:32:57.076  5537  5585 I jxcore-log: 
,11-25 14:32:57.095  5537  5585 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: SUPPORTED
,11-25 14:32:57.096  5537  5585 I jxcore-log: 2016-11-25 13:32:57 - INFO testUtils: 'BLE multiple advertisement supported'
11-25 14:32:57.096  5537  5585 I jxcore-log: 
,11-25 14:32:57.126  5537  5585 I jxcore-log: 2016-11-25 13:32:57 - INFO CoordinatedClient: 'Connecting to coordination server on http://85.14.110.168:3000/'
11-25 14:32:57.126  5537  5585 I jxcore-log: 
,11-25 14:32:57.405  5537  5585 I jxcore-log: 2016-11-25 13:32:57 - DEBUG CoordinatedClient: 'connected to the test server'
11-25 14:32:57.405  5537  5585 I jxcore-log: 
,11-25 14:33:02.161   929  5845 D NetlinkSocketObserver: NeighborEvent{elapsedMs=183703, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,11-25 14:33:06.964   577   577 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 14:33:07.965   577   577 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 14:33:08.966   577   577 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 14:33:09.968   577   577 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 14:33:10.969   577   577 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 14:33:11.203   929  2910 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-25 14:33:11.970   577   577 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,11-25 14:33:14.230   929  2910 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-25 14:33:14.508   929  5845 D NetlinkSocketObserver: NeighborEvent{elapsedMs=196050, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,11-25 14:33:15.122   929  2907 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-25 14:33:27.415   929  5845 D NetlinkSocketObserver: NeighborEvent{elapsedMs=208957, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,11-25 14:33:36.971   577   577 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,11-25 14:33:36.971   577   577 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,11-25 14:33:39.575   929  5845 D NetlinkSocketObserver: NeighborEvent{elapsedMs=221117, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,11-25 14:33:44.484   929  2910 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-25 14:33:46.972   577   577 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 14:33:47.974   577   577 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 14:33:48.975   577   577 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 14:33:49.977   577   577 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 14:33:50.529   929  2910 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-25 14:33:50.978   577   577 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 14:33:51.978   577   577 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,11-25 14:33:52.442   929  5845 D NetlinkSocketObserver: NeighborEvent{elapsedMs=233984, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,11-25 14:33:55.128   929  2907 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-25 14:33:56.980   577   577 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 14:33:57.981   577   577 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 14:33:58.983   577   577 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 14:33:59.984   577   577 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 14:34:00.985   577   577 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 14:34:01.986   577   577 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,11-25 14:34:02.646   929  2910 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-25 14:34:04.642   929  5845 D NetlinkSocketObserver: NeighborEvent{elapsedMs=246184, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,11-25 14:34:05.676   929  2910 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-25 14:34:11.729   929  2910 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-25 14:34:11.988   577   577 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 14:34:12.989   577   577 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 14:34:13.990   577   577 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 14:34:14.764   929  2910 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-25 14:34:14.991   577   577 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 14:34:15.129   929  2907 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-25 14:34:15.993   577   577 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 14:34:16.993   577   577 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,11-25 14:34:17.495   929  5845 D NetlinkSocketObserver: NeighborEvent{elapsedMs=259037, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,11-25 14:34:29.655   929  5845 D NetlinkSocketObserver: NeighborEvent{elapsedMs=271197, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,11-25 14:34:29.906   929  2910 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-25 14:34:31.995   577   577 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 14:34:32.938   929  2910 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-25 14:34:32.996   577   577 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 14:34:33.997   577   577 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 14:34:34.998   577   577 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 14:34:35.999   577   577 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 14:34:37.000   577   577 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,11-25 14:34:38.973   929  2910 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-25 14:34:42.013   929  2910 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-25 14:34:42.521   929  5845 D NetlinkSocketObserver: NeighborEvent{elapsedMs=284063, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,11-25 14:34:54.722   929  5845 D NetlinkSocketObserver: NeighborEvent{elapsedMs=296264, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,11-25 14:34:55.132   929  2907 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-25 14:34:57.001   577   577 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 14:34:58.002   577   577 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 14:34:59.003   577   577 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 14:35:00.005   577   577 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 14:35:00.170   929  2910 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-25 14:35:01.006   577   577 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 14:35:02.006   577   577 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,11-25 14:35:03.198   929  2910 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-25 14:35:07.575   929  5845 D NetlinkSocketObserver: NeighborEvent{elapsedMs=309117, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,11-25 14:35:09.268   929  2910 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-25 14:35:12.299   929  2910 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-25 14:35:15.136   929  2907 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-25 14:35:15.319   929  2910 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-25 14:35:19.762   929  5845 D NetlinkSocketObserver: NeighborEvent{elapsedMs=321304, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,11-25 14:35:21.389   929  2910 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-25 14:35:27.007   577   577 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,11-25 14:35:27.008   577   577 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,11-25 14:35:27.448   929  2910 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-25 14:35:30.489   929  2910 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-25 14:35:32.615   929  5845 D NetlinkSocketObserver: NeighborEvent{elapsedMs=334157, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,11-25 14:35:35.139   929  2907 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-25 14:35:42.009   577   577 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 14:35:42.606   929  2910 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-25 14:35:43.010   577   577 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 14:35:44.012   577   577 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 14:35:45.013   577   577 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 14:35:46.015   577   577 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 14:35:47.015   577   577 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,11-25 14:35:49.815   929  5845 D NetlinkSocketObserver: NeighborEvent{elapsedMs=351357, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,11-25 14:35:51.700   929  2910 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-25 14:35:52.017   577   577 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 14:35:53.018   577   577 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 14:35:54.019   577   577 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 14:35:55.020   577   577 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 14:35:56.022   577   577 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 14:35:57.023   577   577 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,11-25 14:35:57.641   929  5845 D NetlinkSocketObserver: NeighborEvent{elapsedMs=359183, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,11-25 14:36:00.766   929  2910 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-25 14:36:03.793   929  2910 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-25 14:36:07.024   577   577 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 14:36:08.025   577   577 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 14:36:09.027   577   577 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 14:36:10.028   577   577 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 14:36:10.349   929  5845 D NetlinkSocketObserver: NeighborEvent{elapsedMs=371891, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,11-25 14:36:11.030   577   577 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 14:36:12.030   577   577 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,11-25 14:36:12.875   929  2910 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-25 14:36:15.143   929  2907 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-25 14:36:15.912   929  2910 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-25 14:36:23.188   929  5845 D NetlinkSocketObserver: NeighborEvent{elapsedMs=384730, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,11-25 14:36:25.003   929  2910 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-25 14:36:27.031   577   577 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 14:36:28.032   577   577 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 14:36:28.041   929  2910 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-25 14:36:29.034   577   577 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 14:36:30.035   577   577 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 14:36:31.037   577   577 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 14:36:32.038   577   577 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,11-25 14:36:34.102   929  2910 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-25 14:36:35.145   929  2907 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-25 14:36:35.362   929  5845 D NetlinkSocketObserver: NeighborEvent{elapsedMs=396903, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,11-25 14:36:37.134   929  2910 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-25 14:36:40.153   929  2910 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-25 14:36:40.482   929  5845 D NetlinkSocketObserver: NeighborEvent{elapsedMs=402024, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,11-25 14:36:52.039   577   577 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 14:36:52.274   929  2910 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-25 14:36:53.040   577   577 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 14:36:54.041   577   577 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 14:36:55.042   577   577 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 14:36:55.149   929  2907 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-25 14:36:56.043   577   577 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 14:36:57.044   577   577 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,11-25 14:37:00.375   929  5845 D NetlinkSocketObserver: NeighborEvent{elapsedMs=421917, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,11-25 14:37:04.373   929  2910 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-25 14:37:10.448   929  2910 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-25 14:37:13.282   929  5845 D NetlinkSocketObserver: NeighborEvent{elapsedMs=434824, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,11-25 14:37:15.150   929  2907 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-25 14:37:19.551   929  2910 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-25 14:37:22.045   577   577 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,11-25 14:37:22.045   577   577 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,11-25 14:37:25.442   929  5845 D NetlinkSocketObserver: NeighborEvent{elapsedMs=446984, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,11-25 14:37:25.601   929  2910 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-25 14:37:35.151   929  2907 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-25 14:37:37.702   929  2910 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-25 14:37:38.308   929  5845 D NetlinkSocketObserver: NeighborEvent{elapsedMs=459850, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,11-25 14:37:39.258  5537  5585 I jxcore-log: 2016-11-25 13:37:39 - DEBUG CoordinatedClient: 'device disconnected from the test server'
11-25 14:37:39.258  5537  5585 I jxcore-log: 
,11-25 14:37:39.571  5537  5585 I jxcore-log: 2016-11-25 13:37:39 - ERROR CoordinatedClient: 'connection error: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-25 14:37:39.571  5537  5585 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-25 14:37:39.571  5537  5585 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-25 14:37:39.571  5537  5585 I jxcore-log: emit@events.js:82:1
11-25 14:37:39.571  5537  5585 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-25 14:37:39.571  5537  5585 I jxcore-log: emit@events.js:82:1''
11-25 14:37:39.571  5537  5585 I jxcore-log: 
,11-25 14:37:39.573  5537  5585 I jxcore-log: 2016-11-25 13:37:39 - DEBUG CoordinatedClient: 'test client failed'
11-25 14:37:39.573  5537  5585 I jxcore-log: 
,11-25 14:37:39.584  5537  5585 I jxcore-log: 2016-11-25 13:37:39 - ERROR CoordinatedClient: 'connection error: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-25 14:37:39.584  5537  5585 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-25 14:37:39.584  5537  5585 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-25 14:37:39.584  5537  5585 I jxcore-log: emit@events.js:82:1
,11-25 14:37:39.584  5537  5585 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-25 14:37:39.584  5537  5585 I jxcore-log: emit@events.js:82:1''
11-25 14:37:39.584  5537  5585 I jxcore-log: 
11-25 14:37:39.585  5537  5585 I jxcore-log: 2016-11-25 13:37:39 - DEBUG CoordinatedClient: 'test client failed'
11-25 14:37:39.585  5537  5585 I jxcore-log: 
,11-25 14:37:39.590  5537  5585 I jxcore-log: 2016-11-25 13:37:39 - ERROR CoordinatedThaliTape: 'tests failed, error: 'Error: websocket error', stack: 'Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-25 14:37:39.590  5537  5585 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-25 14:37:39.590  5537  5585 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-25 14:37:39.590  5537  5585 I jxcore-log: emit@events.js:82:1
11-25 14:37:39.590  5537  5585 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-25 14:37:39.590  5537  5585 I jxcore-log: emit@events.js:82:1''
11-25 14:37:39.590  5537  5585 I jxcore-log: 
,11-25 14:37:39.591  5537  5585 I jxcore-log: 2016-11-25 13:37:39 - DEBUG CoordinatedThaliTape: '****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****'
11-25 14:37:39.591  5537  5585 I jxcore-log: 
,11-25 14:37:40.183  5896  5896 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,11-25 14:37:40.213  5896  5896 D AndroidRuntime: CheckJNI is OFF
,11-25 14:37:40.242  5896  5896 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,11-25 14:37:40.277  5896  5896 I Radio-JNI: register_android_hardware_Radio DONE
,11-25 14:37:40.295  5896  5896 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,11-25 14:37:40.309   929   942 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=-1: uninstall pkg
,11-25 14:37:40.310   929   942 I ActivityManager: Killing 5537:com.test.thalitest/u0a77 (adj 0): stop com.test.thalitest
,11-25 14:37:40.419   929  3520 I WindowState: WIN DEATH: Window{15f216f u0 com.test.thalitest/com.test.thalitest.MainActivity}
,11-25 14:37:40.419   929   940 D GraphicsStats: Buffer count: 2
,11-25 14:37:40.422   929  2909 D WifiService: Client connection lost with reason: 4
,11-25 14:37:40.438   929   942 W ActivityManager: Force removing ActivityRecord{2f0e684 u0 com.test.thalitest/.MainActivity t70}: app died, no saved state
,11-25 14:37:40.484   929   952 I art     : Starting a blocking GC Explicit
,11-25 14:37:40.489   929   940 W ActivityManager: Spurious death for ProcessRecord{4653bb8 0:com.test.thalitest/u0a77}, curProc for 5537: null
,11-25 14:37:40.512   929  3061 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 5537 uid 10077
,11-25 14:37:40.513  3578  3578 I Keyboard.Facilitator: onFinishInput()
11-25 14:37:40.508  3061  3061 W Binder_4: type=1400 audit(0.0:119): avc: denied { ioctl } for path="socket:[25350]" dev="sockfs" ino=25350 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
11-25 14:37:40.508  3061  3061 W Binder_4: type=1400 audit(0.0:120): avc: denied { ioctl } for path="socket:[25350]" dev="sockfs" ino=25350 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-25 14:37:40.579  3895  5911 I MicroRecognitionRnrImpl: Starting detection.
,11-25 14:37:40.581  3895  5912 I MicrophoneInputStream: mic_starting com.google.android.apps.gsa.speech.audio.x@ef15ed6
,11-25 14:37:40.583   511  5914 I AudioFlinger: AudioFlinger's thread 0xf1c40000 ready to run
,11-25 14:37:40.588   511  2916 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
,11-25 14:37:40.589  3895  5912 I MicrophoneInputStream: mic_started com.google.android.apps.gsa.speech.audio.x@ef15ed6
,11-25 14:37:40.599   511  5914 D audio_hw_primary: select_devices: out_snd_device(0: none) in_snd_device(63: voice-rec-mic)
,11-25 14:37:40.599   511  5914 D msm8974_platform: platform_send_audio_calibration: sending audio calibration for snd_device(63) acdb_id(62)
11-25 14:37:40.599   511  5914 I ACDB-LOADER: ACDB AFE returned = -19
,11-25 14:37:40.600   511  5914 I soundtrigger: audio_extn_sound_trigger_update_device_status: device 0x3f of type 1 for Event 1
11-25 14:37:40.600   511  5914 D sound_trigger_platform: platform_stdev_check_and_update_concurrency: concurrency active 0, tx 1, rx 0, concurrency session_allowed 0
11-25 14:37:40.600   511  5914 D audio_hw_primary: enable_snd_device: snd_device(63: voice-rec-mic)
11-25 14:37:40.600   929   952 I art     : Explicit concurrent mark sweep GC freed 142321(9MB) AllocSpace objects, 83(2MB) LOS objects, 33% free, 29MB/44MB, paused 1.990ms total 115.324ms
,11-25 14:37:40.609   511  5914 D audio_hw_primary: enable_audio_route: apply and update mixer path: audio-record
,11-25 14:37:40.619   929   952 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,11-25 14:37:40.621  5896  5896 I art     : System.exit called, status: 0
11-25 14:37:40.621  5896  5896 I AndroidRuntime: VM exiting with result code 0.
,11-25 14:37:40.625   929   952 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=0: pkg removed
,11-25 14:37:40.633  5779  5779 D BluetoothMapAppObserver: onReceive
,11-25 14:37:40.633  5779  5779 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
11-25 14:37:40.637  3649  4005 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
11-25 14:37:40.637  3578  3578 I Keyboard.Facilitator: resetDictionaries() : en_US
11-25 14:37:40.640   929  2886 I InputReader: Reconfiguring input devices.  changes=0x00000010
,11-25 14:37:40.658  3578  5921 I Keyboard.Facilitator.DecoderInitializer: run()
,11-25 14:37:40.663  3323  5923 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,11-25 14:37:40.691   929   929 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,11-25 14:37:40.692  3895  3895 I HotwordWorkerImpl: onReady
,11-25 14:37:40.699  3721  3721 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,11-25 14:37:40.702  3578  5921 I Decoder : createOrResetDecoder
,11-25 14:37:40.719  3504  3504 E NetworkScheduler.SchedulerReceiver: Invalid parameter app
11-25 14:37:40.719  3504  3504 E NetworkScheduler.SchedulerReceiver: Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,11-25 14:37:40.731    28    28 W kworker/2:1: type=1400 audit(0.0:121): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-25 14:37:40.739  3912  5927 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
,11-25 14:37:40.739  3912  5927 D AccountUtils: Clearing selected account for com.test.thalitest
,11-25 14:37:40.738    28    28 W kworker/2:1: type=1400 audit(0.0:122): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-25 14:37:40.750  3504  3504 I ConfigService: onCreate
,11-25 14:37:40.754  3912  5927 I LocationSettingsChecker: Removing dialog suppression flag for package com.test.thalitest
,11-25 14:37:40.765    28    28 W kworker/2:1: type=1400 audit(0.0:123): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-25 14:37:40.779  3912  3912 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
,11-25 14:37:40.779  3912  3912 D ChimeraModuleLdr: Module APK com.google.android.play.games already loaded
11-25 14:37:40.779  3578  5921 I Keyboard.Facilitator.MainLanguageModelLoader: run()
,11-25 14:37:40.782  3323  5923 E SQLiteLog: (3850) statement aborts at 18: [DELETE FROM calls WHERE (((source_package = 'com.test.thalitest'))) AND ((type = 4))] disk I/O error
,--------- beginning of crash
11-25 14:37:40.783  3323  5923 E AndroidRuntime: FATAL EXCEPTION: IntentService[VoicemailCleanupService]
11-25 14:37:40.783  3323  5923 E AndroidRuntime: Process: android.process.acore, PID: 3323
11-25 14:37:40.783  3323  5923 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
11-25 14:37:40.783  3323  5923 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
11-25 14:37:40.783  3323  5923 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
11-25 14:37:40.783  3323  5923 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
11-25 14:37:40.783  3323  5923 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
11-25 14:37:40.783  3323  5923 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
11-25 14:37:40.783  3323  5923 E AndroidRuntime: 	at com.android.providers.contacts.DbModifierWithNotification.delete(DbModifierWithNotification.java:197)
11-25 14:37:40.783  3323  5923 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:219)
11-25 14:37:40.783  3323  5923 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
11-25 14:37:40.783  3323  5923 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
11-25 14:37:40.783  3323  5923 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
11-25 14:37:40.783  3323  5923 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
11-25 14:37:40.783  3323  5923 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
11-25 14:37:40.783  3323  5923 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
11-25 14:37:40.783  3323  5923 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-25 14:37:40.783  3323  5923 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
11-25 14:37:40.783  3323  5923 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,11-25 14:37:40.795  3912  3912 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
11-25 14:37:40.795  3912  3912 D ChimeraModuleLdr: Module APK com.google.android.play.games already loaded
11-25 14:37:40.795  3912  5935 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/metrics.db'.
11-25 14:37:40.795  3912  5935 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
11-25 14:37:40.795  3912  5935 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
11-25 14:37:40.795  3912  5935 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
11-25 14:37:40.795  3912  5935 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
11-25 14:37:40.795  3912  5935 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
11-25 14:37:40.795  3912  5935 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
11-25 14:37:40.795  3912  5935 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
11-25 14:37:40.795  3912  5935 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
11-25 14:37:40.795  3912  5935 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
11-25 14:37:40.795  3912  5935 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
11-25 14:37:40.795  3912  5935 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
11-25 14:37:40.795  3912  5935 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
11-25 14:37:40.795  3912  5935 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
11-25 14:37:40.795  3912  5935 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
11-25 14:37:40.795  3912  5935 E SQLiteDatabase: 	at com.google.android.gms.googlehelp.metrics.c.a(SourceFile:102)
11-25 14:37:40.795  3912  5935 E SQLiteDatabase: 	at com.google.android.gms.googlehelp.c.a.b(SourceFile:52)
11-25 14:37:40.795  3912  5935 E SQLiteDatabase: 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:278)
11-25 14:37:40.795  3912  5935 E SQLiteDatabase: 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
11-25 14:37:40.795  3912  5935 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
11-25 14:37:40.795  3912  5935 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-25 14:37:40.795  3912  5935 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
11-25 14:37:40.795  3912  5935 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
11-25 14:37:40.795  3912  5935 E SQLiteOpenHelper: Couldn't open metrics.db for writing (will try read-only):
11-25 14:37:40.795  3912  5935 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
11-25 14:37:40.795  3912  5935 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
11-25 14:37:40.795  3912  5935 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
11-25 14:37:40.795  3912  5935 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
11-25 14:37:40.795  3912  5935 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
11-25 14:37:40.795  3912  5935 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
11-25 14:37:40.795  3912  5935 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
11-25 14:37:40.795  3912  5935 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
11-25 14:37:40.795  3912  5935 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
11-25 14:37:40.795  3912  5935 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
11-25 14:37:40.795  3912  5935 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
11-25 14:37:40.795  3912  5935 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
11-25 14:37:40.795  3912  5935 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
11-25 14:37:40.795  3912  5935 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
11-25 14:37:40.795  3912  5935 E SQLiteOpenHelper: 	at com.google.android.gms.googlehelp.metrics.c.a(SourceFile:102)
11-25 14:37:40.795  3912  5935 E SQLiteOpenHelper: 	at com.google.android.gms.googlehelp.c.a.b(SourceFile:52)
11-25 14:37:40.795  3912  5935 E SQLiteOpenHelper: 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:278)
11-25 14:37:40.795  3912  5935 E SQLiteOpenHelper: 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
11-25 14:37:40.795  3912  5935 E SQLiteOpenHelper: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
11-25 14:37:40.795  3912  5935 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-25 14:37:40.795  3912  5935 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:148)
11-25 14:37:40.795  3912  5935 E SQLiteOpenHelper: 	at android.os.HandlerThread.run(HandlerThread.java:61)
11-25 14:37:40.803   929  5939 E DropBoxManagerService: Can't write: system_app_crash
11-25 14:37:40.803   929  5939 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop121.tmp: open failed: EROFS (Read-only file system)
11-25 14:37:40.803   929  5939 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
11-25 14:37:40.803   929  5939 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
11-25 14:37:40.803   929  5939 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
11-25 14:37:40.803   929  5939 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
11-25 14:37:40.803   929  5939 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
11-25 14:37:40.803   929  5939 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
11-25 14:37:40.803   929  5939 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
11-25 14:37:40.803   929  5939 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
11-25 14:37:40.803   929  5939 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
11-25 14:37:40.803   929  5939 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
11-25 14:37:40.803   929  5939 E DropBoxManagerService: 	... 5 more
11-25 14:37:40.803  3912  5935 W SQLiteOpenHelper: Opened metrics.db in read-only mode
11-25 14:37:40.803  3912  5935 D GOOGLEHELP_CompatibleDatabase: Open SQLiteDatabase: /data/user/0/com.google.android.gms/databases/metrics.db, release reference: 1
11-25 14:37:40.803  3912  5935 D GOOGLEHELP_CompatibleDatabase: Acquire reference of SQLiteDatabase: /data/user/0/com.google.android.gms/databases/metrics.db: 2
11-25 14:37:40.804  3912  5935 E SQLiteLog: (8) statement aborts at 16: [DELETE FROM metrics WHERE app_package_name="com.test.thalitest"] attempt to write a readonly database
11-25 14:37:40.805  3912  5935 D GOOGLEHELP_CompatibleDatabase: Release reference of SQLiteDatabase: /data/user/0/com.google.android.gms/databases/metrics.db: 1
11-25 14:37:40.806  3912  5935 E AndroidRuntime: FATAL EXCEPTION: IntentService[ClearHelpHistoryIntentService]
11-25 14:37:40.806  3912  5935 E AndroidRuntime: Process: com.google.android.gms, PID: 3912
11-25 14:37:40.806  3912  5935 E AndroidRuntime: android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
11-25 14:37:40.806  3912  5935 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
11-25 14:37:40.806  3912  5935 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
11-25 14:37:40.806  3912  5935 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
11-25 14:37:40.806  3912  5935 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
11-25 14:37:40.806  3912  5935 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
11-25 14:37:40.806  3912  5935 E AndroidRuntime: 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:281)
11-25 14:37:40.806  3912  5935 E AndroidRuntime: 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
11-25 14:37:40.806  3912  5935 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
11-25 14:37:40.806  3912  5935 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-25 14:37:40.806  3912  5935 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
11-25 14:37:40.806  3912  5935 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
11-25 14:37:40.807  3912  5938 I GMPM-SVC: App measurement is starting up
11-25 14:37:40.810  3912  5938 E GMPM-SVC: AppMeasurementService not registered/enabled
11-25 14:37:40.810  3912  5938 E GMPM-SVC: Uploading is not possible. App measurement disabled
11-25 14:37:40.808   405   405 W Binder_1: type=1400 audit(0.0:124): avc: denied { ioctl } for path="socket:[28587]" dev="sockfs" ino=28587 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
11-25 14:37:40.808   405   405 W Binder_1: type=1400 audit(0.0:125): avc: denied { ioctl } for path="socket:[28587]" dev="sockfs" ino=28587 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
11-25 14:37:40.811   407   407 W Binder_2: type=1400 audit(0.0:126): avc: denied { ioctl } for path="socket:[34817]" dev="sockfs" ino=34817 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
11-25 14:37:40.815   929  5942 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
11-25 14:37:40.811   407   407 W Binder_2: type=1400 audit(0.0:127): avc: denied { ioctl } for path="socket:[34817]" dev="sockfs" ino=34817 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-25 14:37:40.827  3912  3912 I ConfigFetchService: onStartCommand Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
11-25 14:37:40.829   929  5944 E DropBoxManagerService: Can't write: system_app_crash
11-25 14:37:40.829   929  5944 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop123.tmp: open failed: EROFS (Read-only file system)
11-25 14:37:40.829   929  5944 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
11-25 14:37:40.829   929  5944 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
11-25 14:37:40.829   929  5944 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
11-25 14:37:40.829   929  5944 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
11-25 14:37:40.829   929  5944 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
11-25 14:37:40.829   929  5944 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
11-25 14:37:40.829   929  5944 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
11-25 14:37:40.829   929  5944 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
11-25 14:37:40.829   929  5944 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
11-25 14:37:40.829   929  5944 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
11-25 14:37:40.829   929  5944 E DropBoxManagerService: 	... 5 more
11-25 14:37:40.829  3912  4762 E SharedPreferencesImpl: Couldn't rename file /data/user/0/com.google.android.gms/shared_prefs/config_removals.xml to backup file /data/user/0/com.google.android.gms/shared_prefs/config_removals.xml.bak
11-25 14:37:40.831  3578  5921 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /data/user/0/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
11-25 14:37:40.832  3912  5938 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/google_app_measurement.db'.
11-25 14:37:40.832  3912  5938 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
11-25 14:37:40.832  3912  5938 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
11-25 14:37:40.832  3912  5938 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
11-25 14:37:40.832  3912  5938 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
11-25 14:37:40.832  3912  5938 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
11-25 14:37:40.832  3912  5938 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
11-25 14:37:40.832  3912  5938 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
11-25 14:37:40.832  3912  5938 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
11-25 14:37:40.832  3912  5938 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
11-25 14:37:40.832  3912  5938 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
11-25 14:37:40.832  3912  5938 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
11-25 14:37:40.832  3912  5938 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
11-25 14:37:40.832  3912  5938 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
11-25 14:37:40.832  3912  5938 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
11-25 14:37:40.832  3912  5938 E SQLiteDatabase: 	at com.google.android.gms.measurement.internal.e.getWritableDatabase(SourceFile:1022)
11-25 14:37:40.832  3912  5938 E SQLiteDatabase: 	at com.google.android.gms.measurement.internal.d.j(SourceFile:271)
11-25 14:37:40.832  3912  5938 E SQLiteDatabase: 	at com.google.android.gms.measurement.internal.d.d(SourceFile:877)
11-25 14:37:40.832  3912  5938 E SQLiteDatabase: 	at com.google.android.gms.measurement.internal.ao.run(SourceFile:397)
11-25 14:37:40.832  3912  5938 E SQLiteDatabase: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
11-25 14:37:40.832  3912  5938 E SQLiteDatabase: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
11-25 14:37:40.832  3912  5938 E SQLiteDatabase: 	at com.google.android.gms.measurement.internal.al.run(SourceFile:257)
11-25 14:37:40.832  3912  5938 E GMPM-SVC: Opening the database failed, dropping and recreating it
11-25 14:37:40.834  3912  5938 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/google_app_measurement.db'.
11-25 14:37:40.834  3912  5938 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
11-25 14:37:40.834  3912  5938 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
11-25 14:37:40.834  3912  5938 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
11-25 14:37:40.834  3912  5938 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
11-25 14:37:40.834  3912  5938 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
11-25 14:37:40.834  3912  5938 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
11-25 14:37:40.834  3912  5938 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
11-25 14:37:40.834  3912  5938 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
11-25 14:37:40.834  3912  5938 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
11-25 14:37:40.834  3912  5938 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
11-25 14:37:40.834  3912  5938 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
11-25 14:37:40.834  3912  5938 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
11-25 14:37:40.834  3912  5938 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
11-25 14:37:40.834  3912  5938 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
11-25 14:37:40.834  3912  5938 E SQLiteDatabase: 	at com.google.android.gms.measurement.internal.e.getWritableDatabase(SourceFile:1036)
11-25 14:37:40.834  3912  5938 E SQLiteDatabase: 	at com.google.android.gms.measurement.internal.d.j(SourceFile:271)
11-25 14:37:40.834  3912  5938 E SQLiteDatabase: 	at com.google.android.gms.measurement.internal.d.d(SourceFile:877)
11-25 14:37:40.834  3912  5938 E SQLiteDatabase: 	at com.google.android.gms.measurement.internal.ao.run(SourceFile:397)
11-25 14:37:40.834  3912  5938 E SQLiteDatabase: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
11-25 14:37:40.834  3912  5938 E SQLiteDatabase: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
11-25 14:37:40.834  3912  5938 E SQLiteDatabase: 	at com.google.android.gms.measurement.internal.al.run(SourceFile:257)
11-25 14:37:40.834  3912  3912 I ConfigFetchService: service connected
11-25 14:37:40.837  3578  5921 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
11-25 14:37:40.838  3912  5946 I PeopleContactsSync: CP2 sync disabled
11-25 14:37:40.838  3578  5921 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
,11-25 14:37:40.839  3895  5945 I UpdateIcingCorporaServi: Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
11-25 14:37:40.840  3578  5921 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Contacts.dict
11-25 14:37:40.840  3912  5938 E GMPM-SVC: Failed to open freshly created database: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.: com.google.android.gms.measurement.internal.e.getWritableDatabase(SourceFile:1036)
11-25 14:37:40.840  3578  5921 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = history
11-25 14:37:40.841  3912  5938 W GMPM-SVC: Error opening database: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.: com.google.android.gms.measurement.internal.e.getWritableDatabase(SourceFile:1036)
11-25 14:37:40.842  3578  5921 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loaded File = UserHistory.en_US.dict
11-25 14:37:40.842  3578  5921 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = user
11-25 14:37:40.843  3912  5938 E GMPM-SVC: Error deleting application data. appId, error: com.test.thalitest, android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.: com.google.android.gms.measurement.internal.e.getWritableDatabase(SourceFile:1036)
11-25 14:37:40.845  3912  4762 E SharedPreferencesImpl: Couldn't rename file /data/user/0/com.google.android.gms/shared_prefs/com.google.android.gms.measurement.prefs.xml to backup file /data/user/0/com.google.android.gms/shared_prefs/com.google.android.gms.measurement.prefs.xml.bak
,11-25 14:37:40.846  3912  4762 E SharedPreferencesImpl: Couldn't rename file /data/user/0/com.google.android.gms/shared_prefs/com.google.android.gms.measurement.prefs.xml to backup file /data/user/0/com.google.android.gms/shared_prefs/com.google.android.gms.measurement.prefs.xml.bak
11-25 14:37:40.846  3912  4762 E SharedPreferencesImpl: Couldn't rename file /data/user/0/com.google.android.gms/shared_prefs/com.google.android.gms.measurement.prefs.xml to backup file /data/user/0/com.google.android.gms/shared_prefs/com.google.android.gms.measurement.prefs.xml.bak
11-25 14:37:40.847  3912  4762 E SharedPreferencesImpl: Couldn't rename file /data/user/0/com.google.android.gms/shared_prefs/com.google.android.gms.measurement.prefs.xml to backup file /data/user/0/com.google.android.gms/shared_prefs/com.google.android.gms.measurement.prefs.xml.bak
11-25 14:37:40.847  3578  5921 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Personal.en_US.dict
11-25 14:37:40.847  3912  4762 E SharedPreferencesImpl: Couldn't rename file /data/user/0/com.google.android.gms/shared_prefs/com.google.android.gms.measurement.prefs.xml to backup file /data/user/0/com.google.android.gms/shared_prefs/com.google.android.gms.measurement.prefs.xml.bak
11-25 14:37:40.847  3578  5921 I Keyboard.Facilitator.PersonalDictionaryLoader: run() : Loaded (exit)
11-25 14:37:40.847  3578  5921 I Keyboard.Facilitator.Delight2FileSweeper: run()
11-25 14:37:40.847  3912  4762 E SharedPreferencesImpl: Couldn't rename file /data/user/0/com.google.android.gms/shared_prefs/com.google.android.gms.measurement.prefs.xml to backup file /data/user/0/com.google.android.gms/shared_prefs/com.google.android.gms.measurement.prefs.xml.bak
11-25 14:37:40.847  3578  5921 I Keyboard.Facilitator.RecurringTaskScheduler: run()
11-25 14:37:40.847  3578  5921 I StatsUtilsManager: startPeriodStatsRecorder() : Success
11-25 14:37:40.847  3578  5921 I PeriodicStatsRecorder: shouldRecordStats() = Too Soon
,11-25 14:37:40.867  3912  4162 I Icing   : doRemovePackageData com.test.thalitest
,11-25 14:37:40.880   929  3061 I ActivityManager: Start proc 5949:com.android.keychain/1000 for broadcast com.android.keychain/.KeyChainBroadcastReceiver
,11-25 14:37:40.883  3912  5937 W BaseAppContext: Using Auth Proxy for data requests.
,11-25 14:37:40.888  3912  5937 W BaseAppContext: Using Auth Proxy for data requests.
,11-25 14:37:40.899   929   942 W BroadcastQueue: Skipping deliver [background] BroadcastRecord{4e04538 u-1 android.net.conn.CONNECTIVITY_CHANGE} to ReceiverList{a35ddaa 3912 com.google.android.gms/10012/u0 remote:20d2895}: process crashing
,11-25 14:37:40.906   929   939 D ConnectivityService: listenForNetwork for Listen from uid/pid:10012/3912 for NetworkRequest [ id=5, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,11-25 14:37:40.962  3912  5934 W DriveInitializer: Awaiting to be initialized
,11-25 14:37:40.962  3912  5956 W DriveInitializer: Background init thread started
,11-25 14:37:41.163   383   479 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0

```
