#### Test 9518113543259f0_thali07_Huawei-Nexus 6P Logs


```
--------- beginning of main
11-24 15:40:12.040  4073  4228 I Icing   : Indexing 3C763AF371F9E97B4ECFEA01A338ADB468C38476 from com.google.android.googlequicksearchbox
11-24 15:40:12.121  4073  4228 I Icing   : Indexing done 3C763AF371F9E97B4ECFEA01A338ADB468C38476
,11-24 15:40:12.586  5510  5510 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
11-24 15:40:12.592  5510  5510 D AndroidRuntime: CheckJNI is OFF
11-24 15:40:12.620  5510  5510 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
11-24 15:40:12.656  5510  5510 I Radio-JNI: register_android_hardware_Radio DONE
11-24 15:40:12.673  5510  5510 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
11-24 15:40:12.678   926  3791 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
11-24 15:40:12.699  5510  5510 D AndroidRuntime: Shutting down VM
11-24 15:40:12.705  3947  3962 W SearchService: Abort, client detached.
11-24 15:40:12.712  3947  4217 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@debfc61
11-24 15:40:12.712  3947  3947 I HotwordDetector: Closing mic
11-24 15:40:12.713  3947  4225 E AudioRecord-JNI: Error -4 during AudioRecord native read
11-24 15:40:12.734   926  3423 I ActivityManager: Start proc 5519:com.test.thalitest/u0a77 for activity com.test.thalitest/.MainActivity
11-24 15:40:12.789   512  4227 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
11-24 15:40:12.789   512  4227 D audio_hw_primary: disable_snd_device: snd_device(63: voice-rec-mic)
11-24 15:40:12.794   512  4227 I soundtrigger: audio_extn_sound_trigger_update_device_status: device 0x3f of type 1 for Event 0
11-24 15:40:12.794   512  4227 D sound_trigger_platform: platform_stdev_check_and_update_concurrency: concurrency active 0, tx 0, rx 0, concurrency session_allowed 1
11-24 15:40:12.796   512  3021 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
11-24 15:40:12.797  3947  4218 I MicroRecognitionRnrImpl: Stopping hotword detection.
11-24 15:40:12.798  3947  4224 I MicroRecognitionRnrImpl: Detection finished
11-24 15:40:12.842  5519  5519 I CordovaLog: Changing log level to DEBUG(3)
11-24 15:40:12.843  5519  5519 I CordovaActivity: Apache Cordova native platform version 6.0.0 is starting
11-24 15:40:12.843  5519  5519 D CordovaActivity: CordovaActivity.onCreate()
11-24 15:40:12.847  5519  5519 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011750)
11-24 15:40:12.867  5519  5519 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,11-24 15:40:12.922  5519  5519 I LibraryLoader: Time to load native libraries: 51 ms (timestamps 2179-2230)
,11-24 15:40:12.922  5519  5519 I LibraryLoader: Expected native library version number "",actual native library version number ""
,11-24 15:40:12.946  5519  5519 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {c04046e}
,11-24 15:40:12.946  5519  5519 I LibraryLoader: Expected native library version number "",actual native library version number ""
11-24 15:40:12.946  5519  5519 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,11-24 15:40:12.950  5519  5519 I BrowserStartupController: Initializing chromium process, singleProcess=true
,11-24 15:40:12.951  5519  5519 E SysUtils: ApplicationContext is null in ApplicationStatus
,11-24 15:40:13.010  5519  5519 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,11-24 15:40:13.019  5519  5519 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,11-24 15:40:13.019  5519  5519 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
11-24 15:40:13.019  5519  5519 I Adreno  : QUALCOMM build                   : 63c06b2, I8366cd0437
11-24 15:40:13.019  5519  5519 I Adreno  : Build Date                       : 12/06/15
11-24 15:40:13.019  5519  5519 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
11-24 15:40:13.019  5519  5519 I Adreno  : Local Branch                     : mybranch17112971
11-24 15:40:13.019  5519  5519 I Adreno  : Remote Branch                    : quic/LA.BF64.1.2.9_v2
11-24 15:40:13.019  5519  5519 I Adreno  : Remote Branch                    : NONE
11-24 15:40:13.019  5519  5519 I Adreno  : Reconstruct Branch               : NOTHING
,11-24 15:40:13.053   926   943 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@f27c0a1:true
,11-24 15:40:13.074   405   405 W Binder_2: type=1400 audit(0.0:101): avc: denied { ioctl } for path="socket:[28117]" dev="sockfs" ino=28117 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
11-24 15:40:13.074   405   405 W Binder_2: type=1400 audit(0.0:102): avc: denied { ioctl } for path="socket:[28117]" dev="sockfs" ino=28117 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-24 15:40:13.087  5519  5519 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,11-24 15:40:13.095  5519  5519 D SystemWebViewEngine: CordovaWebView is running on device made by: Huawei
,11-24 15:40:13.099  5519  5519 D PluginManager: init()
,11-24 15:40:13.101  5519  5519 D CordovaWebViewImpl: >>> loadUrl(file:///android_asset/www/index.html)
,11-24 15:40:13.115  5519  5519 D CordovaActivity: Started the activity.
,11-24 15:40:13.115  5519  5519 D CordovaActivity: Resumed the activity.
,11-24 15:40:13.118  2964  2964 W Binder_4: type=1400 audit(0.0:103): avc: denied { ioctl } for path="socket:[33876]" dev="sockfs" ino=33876 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-24 15:40:13.118  2964  2964 W Binder_4: type=1400 audit(0.0:104): avc: denied { ioctl } for path="socket:[33876]" dev="sockfs" ino=33876 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
11-24 15:40:13.120  5519  5556 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,11-24 15:40:13.121  3801  3801 W Binder_8: type=1400 audit(0.0:105): avc: denied { ioctl } for path="socket:[29807]" dev="sockfs" ino=29807 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-24 15:40:13.121  3801  3801 W Binder_8: type=1400 audit(0.0:106): avc: denied { ioctl } for path="socket:[29807]" dev="sockfs" ino=29807 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
11-24 15:40:13.123  5519  5543 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,11-24 15:40:13.144  5519  5556 I OpenGLRenderer: Initialized EGL, version 1.4
,11-24 15:40:13.211  4813  4813 W Binder_B: type=1400 audit(0.0:107): avc: denied { ioctl } for path="socket:[32500]" dev="sockfs" ino=32500 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-24 15:40:13.212   926   944 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +498ms
,11-24 15:40:13.211  4813  4813 W Binder_B: type=1400 audit(0.0:108): avc: denied { ioctl } for path="socket:[32500]" dev="sockfs" ino=32500 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
11-24 15:40:13.211   937   937 W Binder_2: type=1400 audit(0.0:109): avc: denied { ioctl } for path="socket:[32499]" dev="sockfs" ino=32499 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-24 15:40:13.211   937   937 W Binder_2: type=1400 audit(0.0:110): avc: denied { ioctl } for path="socket:[32499]" dev="sockfs" ino=32499 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
11-24 15:40:13.216  3689  3689 I Keyboard.Facilitator: onFinishInput()
,11-24 15:40:13.233  5519  5519 D CordovaWebViewImpl: onPageDidNavigate(file:///android_asset/www/index.html)
,11-24 15:40:13.262  5519  5519 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 5519
,11-24 15:40:13.327  5519  5519 D JsMessageQueue: Set native->JS mode to EvalBridgeMode
,11-24 15:40:13.470  5519  5558 D jxcore_app_log: JniHelper::setJavaVM(0xf513c000), pthread_self() = -567281360
,11-24 15:40:13.475  5519  5558 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
11-24 15:40:13.475  5519  5558 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
11-24 15:40:13.475  5519  5558 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
11-24 15:40:13.475  5519  5558 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
11-24 15:40:13.475  5519  5558 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
11-24 15:40:13.475  5519  5558 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@be3af4 added. We now have 1 listener(s)
,11-24 15:40:13.477  5519  5558 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 60:83:34:25:D7:D4
,11-24 15:40:13.478  5519  5558 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
,11-24 15:40:13.478  5519  5558 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-24 15:40:13.478  5519  5558 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,11-24 15:40:13.480  5519  5558 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
11-24 15:40:13.480  5519  5558 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
11-24 15:40:13.480  5519  5558 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
11-24 15:40:13.480  5519  5558 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 60:83:34:25:D7:D4
11-24 15:40:13.480  5519  5558 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
11-24 15:40:13.480  5519  5558 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
11-24 15:40:13.480  5519  5558 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
11-24 15:40:13.480  5519  5558 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
11-24 15:40:13.480  5519  5558 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
11-24 15:40:13.480  5519  5558 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
11-24 15:40:13.480  5519  5558 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
11-24 15:40:13.480  5519  5558 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
11-24 15:40:13.480  5519  5558 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
11-24 15:40:13.480  5519  5558 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,11-24 15:40:13.480  5519  5558 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9f30663 added. We now have 1 listener(s)
11-24 15:40:13.481  5519  5558 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-24 15:40:13.484   926  2974 D WifiService: New client listening to asynchronous messages
,11-24 15:40:13.485  5519  5558 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
11-24 15:40:13.485  5519  5558 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
11-24 15:40:13.485  5519  5558 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[JavaBridge,5,main], id: 51
11-24 15:40:13.485  5519  5558 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
11-24 15:40:13.485  5519  5558 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
11-24 15:40:13.485  5519  5558 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
11-24 15:40:13.485  5519  5558 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[JavaBridge,5,main], id: 51
11-24 15:40:13.486  5519  5558 I io.jxcore.node.LifeCycleMonitor: start: OK
,11-24 15:40:13.496  5519  5519 D CordovaWebViewImpl: onPageFinished(file:///android_asset/www/index.html)
,11-24 15:40:13.502  5519  5519 D SystemWebChromeClient: file:///android_asset/www/js/index.js: Line 36 : Uncaught TypeError: Cannot read property 'querySelector' of null
11-24 15:40:13.502  5519  5519 I chromium: [INFO:CONSOLE(36)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (36)
,11-24 15:40:14.225  5519  5565 W jxcore-log: Initializing JXcore engine
11-24 15:40:14.225  5519  5565 W jxcore-log: JXcore engine is ready
,11-24 15:40:14.248  5565  5565 W Thread-57: type=1400 audit(0.0:111): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=11618 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,11-24 15:40:14.248  5565  5565 W Thread-57: type=1400 audit(0.0:112): avc: denied { ioctl } for path="socket:[16402]" dev="sockfs" ino=16402 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
11-24 15:40:14.248  5565  5565 W Thread-57: type=1400 audit(0.0:113): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=5964 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
11-24 15:40:14.248  5565  5565 W Thread-57: type=1400 audit(0.0:114): avc: denied { ioctl } for path="socket:[33857]" dev="sockfs" ino=33857 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:untrusted_app:s0:c512,c768 tclass=netlink_route_socket permissive=0
,11-24 15:40:14.256  5519  5565 W jxcore-log: Starting JXcore engine
,11-24 15:40:14.306  5519  5565 W jxcore-log: Platform android
11-24 15:40:14.306  5519  5565 W jxcore-log: 
,11-24 15:40:14.306  5519  5565 W jxcore-log: Process ARCH arm
11-24 15:40:14.306  5519  5565 W jxcore-log: 
,11-24 15:40:14.488  5519  5565 I jxcore-log: JXcore Cordova bridge is ready!
11-24 15:40:14.488  5519  5565 I jxcore-log: 
,11-24 15:40:14.489  5519  5565 W jxcore-log: JXcore engine is started
,11-24 15:40:14.498  5519  5558 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,11-24 15:40:14.504  5519  5519 D SystemWebChromeClient: file:///android_asset/www/js/thali_main.js: Line 41 : Application has the required permission.
,11-24 15:40:14.505  5519  5519 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,11-24 15:40:16.185  3592  3592 I ConfigService: onDestroy
,11-24 15:40:17.721   926  3155 I ActivityManager: Killing 4489:com.google.android.calendar/u0a36 (adj 15): empty #17
,11-24 15:40:20.585   926  2973 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-24 15:40:22.780   926  2956 I ActivityManager: Killing 5165:com.android.settings/1000 (adj 15): empty #17
,11-24 15:40:22.857  3947  5567 W CronetSyncConnectionRcs: Upload content type not set.
,11-24 15:40:23.793   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 15:40:24.098  5519  5565 I jxcore-log: 2016-11-24 14:40:24 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
11-24 15:40:24.098  5519  5565 I jxcore-log: 
,11-24 15:40:24.100  5519  5565 I jxcore-log: 2016-11-24 14:40:24 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
11-24 15:40:24.100  5519  5565 I jxcore-log: 
,11-24 15:40:24.107  5519  5565 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,11-24 15:40:24.107  5519  5565 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-24 15:40:24.107  5519  5565 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-24 15:40:24.107  5519  5565 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-24 15:40:24.107  5519  5565 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-24 15:40:24.107  5519  5565 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-24 15:40:24.107  5519  5565 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-24 15:40:24.107  5519  5565 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-24 15:40:24.107  5519  5565 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-24 15:40:24.107  5519  5565 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
11-24 15:40:24.109  5519  5565 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
11-24 15:40:24.110  5519  5565 I jxcore-log: 2016-11-24 14:40:24 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
11-24 15:40:24.110  5519  5565 I jxcore-log: 
,11-24 15:40:24.112  5519  5565 I jxcore-log: 2016-11-24 14:40:24 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
11-24 15:40:24.112  5519  5565 I jxcore-log: 
,11-24 15:40:24.354  5519  5565 I jxcore-log: 2016-11-24 14:40:24 - DEBUG UnitTest_app: 'Running unit tests'
11-24 15:40:24.354  5519  5565 I jxcore-log: 
11-24 15:40:24.355  5519  5565 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,11-24 15:40:24.355  5519  5565 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@abb063c added. We now have 2 listener(s)
11-24 15:40:24.356  5519  5565 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-24 15:40:24.356  5519  5565 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-24 15:40:24.356  5519  5565 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-24 15:40:24.356  5519  5565 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,11-24 15:40:24.356  5519  5565 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bf01fc5 added. We now have 2 listener(s)
11-24 15:40:24.356  5519  5565 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-24 15:40:24.357  5519  5565 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
11-24 15:40:24.358  5519  5565 D executeNativeTests: Running unit tests
,11-24 15:40:24.399  5519  5565 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,11-24 15:40:24.399  5519  5565 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@59ba0ca added. We now have 3 listener(s)
11-24 15:40:24.400  5519  5565 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
,11-24 15:40:24.400  5519  5565 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-24 15:40:24.400  5519  5565 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-24 15:40:24.400  5519  5565 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-24 15:40:24.400  5519  5565 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@47d323b added. We now have 3 listener(s)
,11-24 15:40:24.400  5519  5565 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-24 15:40:24.401  5519  5565 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
11-24 15:40:24.404  5519  5565 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
11-24 15:40:24.404  5519  5565 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,11-24 15:40:24.404  5519  5565 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-24 15:40:24.404  5519  5565 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-24 15:40:24.405  5519  5565 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
11-24 15:40:24.405  5519  5565 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
,11-24 15:40:24.405  5519  5565 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
11-24 15:40:24.405  5519  5565 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-24 15:40:24.405  5519  5565 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-24 15:40:24.405  5519  5565 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-24 15:40:24.405  5519  5565 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-24 15:40:24.406  5519  5565 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-24 15:40:24.406  5519  5565 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-24 15:40:24.406  5519  5565 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-24 15:40:24.406  5519  5565 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 15:40:24.406  5519  5565 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-24 15:40:24.406  5519  5565 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@59ba0ca removed from the list
11-24 15:40:24.406  5519  5565 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 15:40:24.407  5519  5565 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@47d323b removed from the list
11-24 15:40:24.407  5519  5565 D io.jxcore.node.ConnectivityMonitor: stop
11-24 15:40:24.407  5519  5565 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-57,5,main], id: 57
11-24 15:40:24.407  5519  5565 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
11-24 15:40:24.408  5519  5565 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
11-24 15:40:24.408  5519  5565 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
11-24 15:40:24.408  5519  5565 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
11-24 15:40:24.408  5519  5565 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-24 15:40:24.408  5519  5565 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-24 15:40:24.408  5519  5565 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-24 15:40:24.408  5519  5565 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@47d323b not in the list
11-24 15:40:24.409  5519  5565 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
11-24 15:40:24.409  5519  5565 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-24 15:40:24.409  5519  5565 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-24 15:40:24.409  5519  5565 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-24 15:40:24.410  5519  5565 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-24 15:40:24.410  5519  5565 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 15:40:24.410  5519  5565 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@59ba0ca not in the list
11-24 15:40:24.410  5519  5565 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 15:40:24.410  5519  5565 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@47d323b not in the list
,11-24 15:40:24.410  5519  5565 D io.jxcore.node.ConnectivityMonitor: stop
11-24 15:40:24.410  5519  5565 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-57,5,main], id: 57
11-24 15:40:24.410  5519  5565 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
11-24 15:40:24.410  5519  5565 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
11-24 15:40:24.411  5519  5565 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
11-24 15:40:24.411  5519  5565 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
11-24 15:40:24.411  5519  5565 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-24 15:40:24.411  5519  5565 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-24 15:40:24.411  5519  5565 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 15:40:24.411  5519  5565 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@47d323b not in the list
11-24 15:40:24.413  5519  5565 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
11-24 15:40:24.413  5519  5565 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
,11-24 15:40:24.413  5519  5565 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
11-24 15:40:24.413  5519  5565 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
11-24 15:40:24.413  5519  5565 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
11-24 15:40:24.414  5519  5565 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
11-24 15:40:24.414  5519  5565 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
11-24 15:40:24.414  5519  5565 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
11-24 15:40:24.414  5519  5565 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
,11-24 15:40:24.414  5519  5565 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
11-24 15:40:24.414  5519  5565 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
11-24 15:40:24.414  5519  5565 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
11-24 15:40:24.414  5519  5565 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
11-24 15:40:24.414  5519  5565 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
11-24 15:40:24.414  5519  5565 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
11-24 15:40:24.414  5519  5565 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
11-24 15:40:24.414  5519  5565 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
,11-24 15:40:24.414  5519  5565 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
11-24 15:40:24.414  5519  5565 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
11-24 15:40:24.414  5519  5565 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
11-24 15:40:24.414  5519  5565 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
11-24 15:40:24.414  5519  5565 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
,11-24 15:40:24.414  5519  5565 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
11-24 15:40:24.414  5519  5565 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
11-24 15:40:24.414  5519  5565 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
11-24 15:40:24.414  5519  5565 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
11-24 15:40:24.414  5519  5565 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
,11-24 15:40:24.414  5519  5565 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
11-24 15:40:24.414  5519  5565 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
,11-24 15:40:24.414  5519  5565 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
11-24 15:40:24.414  5519  5565 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
,11-24 15:40:24.414  5519  5565 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-24 15:40:24.415  5519  5565 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,11-24 15:40:24.415  5519  5565 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-24 15:40:24.415  5519  5565 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-24 15:40:24.415  5519  5565 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 15:40:24.415  5519  5565 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@59ba0ca not in the list
11-24 15:40:24.415  5519  5565 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 15:40:24.415  5519  5565 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@47d323b not in the list
11-24 15:40:24.415  5519  5565 D io.jxcore.node.ConnectivityMonitor: stop
11-24 15:40:24.415  5519  5565 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-57,5,main], id: 57
11-24 15:40:24.415  5519  5565 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
11-24 15:40:24.416  5519  5565 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
11-24 15:40:24.416  5519  5565 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
11-24 15:40:24.416  5519  5565 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
11-24 15:40:24.416  5519  5565 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-24 15:40:24.416  5519  5565 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-24 15:40:24.416  5519  5565 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 15:40:24.416  5519  5565 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@47d323b not in the list
11-24 15:40:24.416  5519  5565 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
11-24 15:40:24.418  5519  5565 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-24 15:40:24.418  5519  5565 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
11-24 15:40:24.426  5519  5565 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-24 15:40:24.426  5519  5565 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-24 15:40:24.426  5519  5565 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-24 15:40:24.426  5519  5565 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-24 15:40:24.426  5519  5565 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-24 15:40:24.426  5519  5565 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-24 15:40:24.426  5519  5565 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-24 15:40:24.426  5519  5565 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-24 15:40:24.426  5519  5565 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
11-24 15:40:24.429  5519  5565 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
11-24 15:40:24.430  5519  5565 D io.jxcore.node.ConnectivityMonitor: start: OK
11-24 15:40:24.430  5519  5565 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discov,ery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-24 15:40:24.430  5519  5565 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
11-24 15:40:24.430  5519  5565 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
11-24 15:40:24.430  5519  5565 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-24 15:40:24.430  5519  5565 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
11-24 15:40:24.433  5519  5519 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-24 15:40:24.434  5519  5565 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-24 15:40:24.434  5519  5565 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-24 15:40:24.434  5519  5565 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
11-24 15:40:24.436  5519  5519 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-24 15:40:24.440  5519  5565 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-57,5,main], id: 57
11-24 15:40:24.440  5519  5565 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-24 15:40:24.442  5519  5565 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-24 15:40:24.442  5519  5565 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-24 15:40:24.443  5519  5565 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 0
11-24 15:40:24.445  5519  5565 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
11-24 15:40:24.449  5519  5565 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
11-24 15:40:24.449  5519  5565 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-57,5,main], id: 57
11-24 15:40:24.449  5519  5565 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
11-24 15:40:24.449  5519  5565 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
11-24 15:40:24.449  5519  5565 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
11-24 15:40:24.449  5519  5565 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
11-24 15:40:24.449  5519  5565 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-57,5,main], id: 57
11-24 15:40:24.450  5519  5565 D BluetoothAdapter: STATE_ON
11-24 15:40:24.452  4261  4275 D BtGatt.GattService: registerClient() - UUID=dab7133a-1851-4ab0-acde-946adec80690
11-24 15:40:24.453  4261  4300 D BtGatt.GattService: onClientRegistered() - UUID=dab7133a-1851-4ab0-acde-946adec80690, clientIf=5
11-24 15:40:24.454  5519  5529 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
11-24 15:40:24.455  4261  4443 D BtGatt.GattService: start scan with filters
11-24 15:40:24.459  4261  4303 D BtGatt.ScanManager: handling starting scan
11-24 15:40:24.459  5519  5565 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
11-24 15:40:24.460  5519  5565 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-57,5,main], id: 57
11-24 15:40:24.460  5519  5565 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
11-24 15:40:24.460  5519  5565 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-57,5,main], id: 57
11-24 15:40:24.460  5519  5565 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-24 15:40:24.460  5519  5519 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-24 15:40:24.460  5519  5519 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-24 15:40:24.460  5519  5565 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-24 15:40:24.461  5519  5565 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
11-24 15:40:24.461  4261  4303 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@cf72321
11-24 15:40:24.461  5519  5519 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
11-24 15:40:24.461  5519  5519 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-24 15:40:24.461  5519  5519 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-24 15:40:24.461  5519  5519 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
11-24 15:40:24.461  5519  5565 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
11-24 15:40:24.461  5519  5565 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
11-24 15:40:24.461  5519  5565 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
11-24 15:40:24.462  5519  5565 I io.jxcore.node.ConnectionHelper: start: OK
11-24 15:40:24.462  5519  5519 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-24 15:40:24.462  5519  5519 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING] Current thread: Thread[main,5,main], id: 1
11-24 15:40:24.462  5519  5519 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-24 15:40:24.465  5519  5519 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-24 15:40:24.465  5519  5519 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
11-24 15:40:24.465  5519  5519 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-24 15:40:24.465  5519  5519 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-24 15:40:24.465  5519  5519 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
11-24 15:40:24.468  4261  4300 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,11-24 15:40:24.468  4261  4300 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 15:40:24.469  4261  4303 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
11-24 15:40:24.474  4261  4300 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
11-24 15:40:24.474  4261  4300 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 15:40:24.474  4261  4303 D BtGatt.ScanManager: Starting BLE batch scan
11-24 15:40:24.474  4261  4303 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
11-24 15:40:24.484  4261  4300 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
11-24 15:40:24.485  4261  4300 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 15:40:24.490  4261  4300 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
11-24 15:40:24.490  4261  4300 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-24 15:40:24.795   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 15:40:24.967  5519  5519 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
11-24 15:40:24.967  5519  5519 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
11-24 15:40:24.967  5519  5519 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,11-24 15:40:25.724   926  2975 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,11-24 15:40:25.795   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 15:40:26.796   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 15:40:27.797   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 15:40:28.798   535   535 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,11-24 15:40:29.466  5519  5565 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-24 15:40:29.466  5519  5565 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
11-24 15:40:29.466  5519  5565 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
11-24 15:40:29.467  5519  5565 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-24 15:40:29.467  5519  5565 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-24 15:40:29.467  5519  5565 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 15:40:29.467  5519  5565 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,11-24 15:40:29.467  5519  5565 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-24 15:40:29.467  5519  5565 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-57,5,main], id: 57
11-24 15:40:29.467  5519  5565 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
11-24 15:40:29.467  5519  5565 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,11-24 15:40:29.468  5519  5565 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-57,5,main], id: 57
11-24 15:40:29.469  5519  5565 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-57,5,main], id: 57
11-24 15:40:29.469  5519  5565 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-57,5,main], id: 57
11-24 15:40:29.469  5519  5565 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
11-24 15:40:29.469  5519  5565 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-57,5,main], id: 57
,11-24 15:40:29.470  5519  5565 D BluetoothAdapter: STATE_ON
11-24 15:40:29.470  4261  4275 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
11-24 15:40:29.471  5519  5565 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-24 15:40:29.472  5519  5565 D BluetoothAdapter: STATE_ON
,11-24 15:40:29.472  4261  4303 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
11-24 15:40:29.472  4261  4470 D BtGatt.GattService: stopScan() - queue size =1
11-24 15:40:29.473  4261  4446 D BtGatt.GattService: unregisterClient() - clientIf=5
11-24 15:40:29.474  5519  5565 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,11-24 15:40:29.474  5519  5565 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-57,5,main], id: 57
11-24 15:40:29.474  5519  5565 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
11-24 15:40:29.474  5519  5565 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-57,5,main], id: 57
,11-24 15:40:29.474  5519  5565 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-57,5,main], id: 57
11-24 15:40:29.474  5519  5565 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-57,5,main], id: 57
11-24 15:40:29.474  5519  5565 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-57,5,main], id: 57
,11-24 15:40:29.475  5519  5565 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,11-24 15:40:29.475  5519  5565 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-57,5,main], id: 57
11-24 15:40:29.475  5519  5565 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-57,5,main], id: 57
11-24 15:40:29.475  5519  5565 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-57,5,main], id: 57
11-24 15:40:29.475  5519  5565 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-24 15:40:29.476  5519  5565 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,11-24 15:40:29.476  5519  5565 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-24 15:40:29.476  5519  5565 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
11-24 15:40:29.479  5519  5565 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
11-24 15:40:29.479  4261  4261 D BtGatt.ScanManager: awakened up at time 88788
11-24 15:40:29.479  5519  5565 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-24 15:40:29.479  5519  5565 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
11-24 15:40:29.480  5519  5565 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
11-24 15:40:29.480  5519  5565 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-24 15:40:29.480  5519  5519 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-24 15:40:29.480  5519  5565 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-24 15:40:29.480  5519  5519 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-24 15:40:29.480  5519  5565 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-24 15:40:29.480  5519  5565 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 15:40:29.481  5519  5519 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-24 15:40:29.481  5519  5565 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@59ba0ca not in the list
11-24 15:40:29.481  5519  5519 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-24 15:40:29.481  5519  5565 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 15:40:29.481  5519  5565 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@47d323b not in the list
11-24 15:40:29.481  5519  5519 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-24 15:40:29.481  5519  5565 D io.jxcore.node.ConnectivityMonitor: stop
11-24 15:40:29.481  5519  5519 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
11-24 15:40:29.481  5519  5565 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
11-24 15:40:29.482  5519  5519 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-24 15:40:29.482  5519  5519 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-24 15:40:29.482  5519  5519 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-24 15:40:29.482  5519  5519 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-24 15:40:29.483  5519  5519 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeer,DiscovererStateChanged: [SCANNING] -> [NOT_STARTED] Current thread: Thread[main,5,main], id: 1
11-24 15:40:29.483  5519  5519 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-24 15:40:29.487  5519  5519 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-24 15:40:29.487  5519  5519 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-24 15:40:29.487  5519  5519 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
,11-24 15:40:29.505  4261  4300 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=5
11-24 15:40:29.505  4261  4300 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-24 15:40:29.506  4261  4300 D BtGatt.GattService: current time is 88814670280
11-24 15:40:29.506  4261  4300 D BtGatt.GattService: Batch record : [71, -122, -77, 84, 69, -12, 1, -128, -87, 53, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, -46, -4, -117, 6, 105, -37, 1, -128, -85, 41, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 116, -43, -111, -91, -20, -29, 1, -128, -78, 42, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 81, 34, 97, 112, -14, -5, 1, -128, -85, 81, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 37, -47, 14, -113, 116, -46, 1, -128, -93, 77, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
11-24 15:40:29.507  4261  4300 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
11-24 15:40:29.508  4261  4300 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
11-24 15:40:29.509  4261  4300 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
11-24 15:40:29.509  4261  4300 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
,11-24 15:40:29.509  4261  4300 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,11-24 15:40:29.516  4261  4300 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
11-24 15:40:29.516  4261  4300 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 15:40:29.516  4261  4303 D BtGatt.ScanManager: stopping BLe Batch
,11-24 15:40:29.522  4261  4300 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,11-24 15:40:29.523  4261  4300 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 15:40:29.523  4261  4303 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-24 15:40:29.528  4261  4300 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-24 15:40:29.528  4261  4300 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-24 15:40:29.983  5519  5519 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-24 15:40:31.783   926  2975 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,11-24 15:40:34.485  5519  5565 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,11-24 15:40:34.490  5519  5565 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-24 15:40:34.490  5519  5565 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
,11-24 15:40:34.505  5519  5565 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-24 15:40:34.505  5519  5565 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-24 15:40:34.505  5519  5565 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-24 15:40:34.505  5519  5565 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-24 15:40:34.505  5519  5565 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-24 15:40:34.505  5519  5565 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-24 15:40:34.505  5519  5565 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-24 15:40:34.505  5519  5565 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-24 15:40:34.505  5519  5565 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,11-24 15:40:34.509  5519  5565 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
,11-24 15:40:34.509  5519  5565 D io.jxcore.node.ConnectivityMonitor: start: OK
11-24 15:40:34.510  5519  5565 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-24 15:40:34.510  5519  5565 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
11-24 15:40:34.510  5519  5565 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,11-24 15:40:34.510  5519  5565 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-24 15:40:34.510  5519  5565 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,11-24 15:40:34.515  5519  5519 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-24 15:40:34.517  5519  5565 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-24 15:40:34.517  5519  5565 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-24 15:40:34.518  5519  5565 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
11-24 15:40:34.521  5519  5519 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-24 15:40:34.526  5519  5565 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-57,5,main], id: 57
11-24 15:40:34.526  5519  5565 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-24 15:40:34.527  5519  5565 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-24 15:40:34.527  5519  5565 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-24 15:40:34.528  5519  5565 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 0
,11-24 15:40:34.533  5519  5565 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-57,5,main], id: 57
,11-24 15:40:34.533  5519  5565 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
11-24 15:40:34.533  5519  5565 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,11-24 15:40:34.534  5519  5565 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
11-24 15:40:34.534  5519  5565 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
11-24 15:40:34.534  5519  5565 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-57,5,main], id: 57
11-24 15:40:34.535  5519  5565 D BluetoothAdapter: STATE_ON
11-24 15:40:34.538  4261  4275 D BtGatt.GattService: registerClient() - UUID=118baae3-7806-48c4-ad46-dc11ce2c7e26
11-24 15:40:34.539  4261  4300 D BtGatt.GattService: onClientRegistered() - UUID=118baae3-7806-48c4-ad46-dc11ce2c7e26, clientIf=5
,11-24 15:40:34.540  5519  5530 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,11-24 15:40:34.540  4261  4443 D BtGatt.GattService: start scan with filters
11-24 15:40:34.545  4261  4303 D BtGatt.ScanManager: handling starting scan
,11-24 15:40:34.546  5519  5565 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
,11-24 15:40:34.546  5519  5565 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-57,5,main], id: 57
11-24 15:40:34.546  5519  5565 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
11-24 15:40:34.546  5519  5565 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-57,5,main], id: 57
11-24 15:40:34.546  5519  5519 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-24 15:40:34.546  5519  5565 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,11-24 15:40:34.547  5519  5519 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-24 15:40:34.547  5519  5519 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
11-24 15:40:34.547  5519  5519 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
,11-24 15:40:34.547  5519  5519 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-24 15:40:34.547  5519  5519 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
11-24 15:40:34.547  5519  5519 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
,11-24 15:40:34.547  5519  5519 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING] Current thread: Thread[main,5,main], id: 1
,11-24 15:40:34.551  5519  5565 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,11-24 15:40:34.551  5519  5565 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
11-24 15:40:34.554  4261  4300 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
11-24 15:40:34.555  4261  4300 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 15:40:34.555  4261  4303 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
11-24 15:40:34.555  5519  5565 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
,11-24 15:40:34.555  5519  5565 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
11-24 15:40:34.556  5519  5565 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
11-24 15:40:34.556  5519  5565 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
11-24 15:40:34.556  5519  5565 I io.jxcore.node.ConnectionHelper: start: OK
,11-24 15:40:34.556  5519  5519 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-24 15:40:34.560  5519  5519 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-24 15:40:34.560  5519  5519 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-24 15:40:34.560  5519  5519 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-24 15:40:34.560  5519  5519 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
11-24 15:40:34.561  5519  5565 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-24 15:40:34.562  5519  5565 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,11-24 15:40:34.562  5519  5565 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
11-24 15:40:34.562  5519  5565 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
11-24 15:40:34.562  5519  5565 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-24 15:40:34.562  5519  5565 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-24 15:40:34.562  5519  5565 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 15:40:34.562  5519  5565 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
11-24 15:40:34.562  5519  5565 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,11-24 15:40:34.562  5519  5565 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-57,5,main], id: 57
11-24 15:40:34.562  5519  5565 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
11-24 15:40:34.562  5519  5565 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-24 15:40:34.562  4261  4300 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
11-24 15:40:34.563  5519  5565 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-57,5,main], id: 57
11-24 15:40:34.563  4261  4300 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 15:40:34.563  5519  5565 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-57,5,main], id: 57
11-24 15:40:34.563  5519  5565 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-57,5,main], id: 57
11-24 15:40:34.563  5519  5565 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
11-24 15:40:34.563  5519  5565 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-57,5,main], id: 57
11-24 15:40:34.563  4261  4303 D BtGatt.ScanManager: Starting BLE batch scan
11-24 15:40:34.563  4261  4303 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,11-24 15:40:34.564  5519  5565 D BluetoothAdapter: STATE_ON
11-24 15:40:34.564  4261  4275 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
11-24 15:40:34.565  5519  5565 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
,11-24 15:40:34.566  5519  5565 D BluetoothAdapter: STATE_ON
,11-24 15:40:34.566  4261  4446 D BtGatt.GattService: stopScan() - queue size =1
11-24 15:40:34.567  4261  4276 D BtGatt.GattService: unregisterClient() - clientIf=5
11-24 15:40:34.567  5519  5565 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-24 15:40:34.568  5519  5565 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-57,5,main], id: 57
11-24 15:40:34.568  5519  5565 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
11-24 15:40:34.568  5519  5565 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-57,5,main], id: 57
11-24 15:40:34.568  5519  5565 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-57,5,main], id: 57
11-24 15:40:34.568  5519  5565 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-57,5,main], id: 57
11-24 15:40:34.568  5519  5565 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-57,5,main], id: 57
,11-24 15:40:34.568  5519  5565 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-24 15:40:34.568  5519  5565 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-57,5,main], id: 57
11-24 15:40:34.568  5519  5565 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-57,5,main], id: 57
11-24 15:40:34.568  5519  5565 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-57,5,main], id: 57
11-24 15:40:34.568  5519  5565 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-24 15:40:34.568  5519  5565 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,11-24 15:40:34.569  5519  5565 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-24 15:40:34.569  5519  5565 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
11-24 15:40:34.571  5519  5565 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
,11-24 15:40:34.571  5519  5565 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-24 15:40:34.572  5519  5565 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
11-24 15:40:34.572  5519  5565 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
11-24 15:40:34.572  5519  5565 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-24 15:40:34.572  5519  5565 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-24 15:40:34.572  5519  5565 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-24 15:40:34.572  5519  5565 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 15:40:34.572  5519  5565 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@59ba0ca not in the list
,11-24 15:40:34.572  5519  5565 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 15:40:34.572  5519  5565 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@47d323b not in the list
11-24 15:40:34.572  5519  5565 D io.jxcore.node.ConnectivityMonitor: stop
11-24 15:40:34.572  5519  5565 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
11-24 15:40:34.572  5519  5519 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-24 15:40:34.572  5519  5519 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-24 15:40:34.572  5519  5519 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-24 15:40:34.572  5519  5519 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-24 15:40:34.572  5519  5519 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
,11-24 15:40:34.572  5519  5519 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
11-24 15:40:34.573  5519  5519 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-24 15:40:34.573  5519  5519 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-24 15:40:34.573  5519  5519 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-24 15:40:34.573  5519  5519 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-24 15:40:34.573  5519  5519 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED] Current thread: Thread[main,5,main], id: 1
11-24 15:40:34.573  5519  5565 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-57,5,main], id: 57
11-24 15:40:34.573  5519  5565 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
11-24 15:40:34.574  5519  5565 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
11-24 15:40:34.574  5519  5565 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
11-24 15:40:34.574  5519  5565 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
11-24 15:40:34.574  5519  5565 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,11-24 15:40:34.574  5519  5565 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-24 15:40:34.574  5519  5565 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 15:40:34.574  5519  5519 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-24 15:40:34.575  5519  5565 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@47d323b not in the list
11-24 15:40:34.575  5519  5565 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
11-24 15:40:34.576  5519  5519 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-24 15:40:34.576  5519  5519 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-24 15:40:34.576  5519  5519 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-24 15:40:34.577  5519  5565 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-24 15:40:34.577  5519  5565 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
,11-24 15:40:34.577  4261  4300 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
11-24 15:40:34.577  4261  4300 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-24 15:40:34.583  5519  5565 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-24 15:40:34.583  5519  5565 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-24 15:40:34.583  5519  5565 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-24 15:40:34.583  5519  5565 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-24 15:40:34.583  5519  5565 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-24 15:40:34.583  5519  5565 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-24 15:40:34.583  5519  5565 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-24 15:40:34.583  5519  5565 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-24 15:40:34.583  5519  5565 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
11-24 15:40:34.584  4261  4300 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
11-24 15:40:34.584  4261  4300 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-24 15:40:34.585  5519  5565 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
,11-24 15:40:34.585  4261  4303 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
11-24 15:40:34.585  5519  5565 D io.jxcore.node.ConnectivityMonitor: start: OK
11-24 15:40:34.585  5519  5565 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-24 15:40:34.585  5519  5565 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
11-24 15:40:34.585  5519  5565 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
11-24 15:40:34.585  5519  5565 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-24 15:40:34.585  5519  5565 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
11-24 15:40:34.588  5519  5519 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-24 15:40:34.589  4261  4300 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,11-24 15:40:34.590  4261  4300 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 15:40:34.590  4261  4300 E BtGatt.ContextMap: Context not found for ID 5
11-24 15:40:34.590  5519  5519 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-24 15:40:34.591  5519  5565 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-24 15:40:34.591  5519  5565 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,11-24 15:40:34.591  5519  5565 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
11-24 15:40:34.595  5519  5565 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-57,5,main], id: 57
11-24 15:40:34.595  5519  5565 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-24 15:40:34.595  5519  5565 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-24 15:40:34.595  5519  5565 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-24 15:40:34.595  5519  5565 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 0
11-24 15:40:34.596  4261  4300 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
11-24 15:40:34.596  4261  4300 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-24 15:40:34.596  4261  4303 D BtGatt.ScanManager: stopping BLe Batch
,11-24 15:40:34.598  5519  5565 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-57,5,main], id: 57
11-24 15:40:34.598  5519  5565 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
11-24 15:40:34.598  5519  5565 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,11-24 15:40:34.598  5519  5565 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
11-24 15:40:34.599  5519  5565 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
11-24 15:40:34.599  5519  5565 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-57,5,main], id: 57
,11-24 15:40:34.599  5519  5565 D BluetoothAdapter: STATE_ON
11-24 15:40:34.601  4261  4276 D BtGatt.GattService: registerClient() - UUID=4ead165c-2f4d-4601-8eb5-5ee980fa7289
,11-24 15:40:34.602  4261  4300 D BtGatt.GattService: onClientRegistered() - UUID=4ead165c-2f4d-4601-8eb5-5ee980fa7289, clientIf=5
,11-24 15:40:34.602  5519  5530 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
11-24 15:40:34.602  4261  4300 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
11-24 15:40:34.602  4261  4443 D BtGatt.GattService: start scan with filters
11-24 15:40:34.602  4261  4300 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 15:40:34.602  4261  4303 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
11-24 15:40:34.604  5519  5565 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
11-24 15:40:34.604  5519  5565 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-57,5,main], id: 57
11-24 15:40:34.604  5519  5565 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
11-24 15:40:34.604  5519  5565 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-57,5,main], id: 57
11-24 15:40:34.604  5519  5565 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-24 15:40:34.604  5519  5519 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-24 15:40:34.604  5519  5519 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-24 15:40:34.604  5519  5519 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
11-24 15:40:34.604  5519  5519 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
,11-24 15:40:34.604  5519  5519 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-24 15:40:34.605  5519  5519 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
11-24 15:40:34.605  5519  5519 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-24 15:40:34.605  5519  5519 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING] Current thread: Thread[main,5,main], id: 1
,11-24 15:40:34.606  5519  5565 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-24 15:40:34.606  5519  5565 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
11-24 15:40:34.607  4261  4300 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,11-24 15:40:34.607  4261  4300 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-24 15:40:34.609  5519  5565 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
,11-24 15:40:34.609  5519  5565 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
11-24 15:40:34.609  4261  4303 D BtGatt.ScanManager: handling starting scan
11-24 15:40:34.609  5519  5565 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
11-24 15:40:34.609  5519  5565 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
11-24 15:40:34.609  5519  5565 I io.jxcore.node.ConnectionHelper: start: OK
11-24 15:40:34.609  5519  5519 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
,11-24 15:40:34.612  5519  5519 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-24 15:40:34.612  5519  5519 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-24 15:40:34.613  5519  5519 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-24 15:40:34.613  5519  5519 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,11-24 15:40:34.616  4261  4300 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
11-24 15:40:34.616  4261  4300 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 15:40:34.616  4261  4303 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,11-24 15:40:34.620  4261  4300 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
,11-24 15:40:34.620  4261  4300 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 15:40:34.620  4261  4303 D BtGatt.ScanManager: Starting BLE batch scan
11-24 15:40:34.620  4261  4303 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,11-24 15:40:34.628  4261  4300 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
11-24 15:40:34.628  4261  4300 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-24 15:40:34.632  4261  4300 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
11-24 15:40:34.632  4261  4300 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-24 15:40:34.813   926  2975 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,11-24 15:40:35.114  5519  5519 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
11-24 15:40:35.115  5519  5519 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,11-24 15:40:35.115  5519  5519 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,11-24 15:40:36.819  4261  4261 D BtGatt.ScanManager: awakened up at time 96128
,11-24 15:40:36.820  4261  4303 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-24 15:40:36.834  4261  4300 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=5
,11-24 15:40:36.834  4261  4300 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 15:40:36.834  4261  4300 D BtGatt.GattService: current time is 96142771705
11-24 15:40:36.834  4261  4300 D BtGatt.GattService: Batch record : [71, -122, -77, 84, 69, -12, 1, -128, -88, 1, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, -46, -4, -117, 6, 105, -37, 1, -128, -91, 14, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 81, 34, 97, 112, -14, -5, 1, -128, -86, 13, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 116, -43, -111, -91, -20, -29, 1, -128, -92, 29, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 0, 37, -47, 14, -113, 116, -46, 1, -128, -94, 28, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,11-24 15:40:36.834  4261  4300 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
11-24 15:40:36.834  4261  4300 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
11-24 15:40:36.835  4261  4300 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
,11-24 15:40:36.835  4261  4300 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74]
11-24 15:40:36.835  4261  4300 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,11-24 15:40:36.838  5519  5519 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: onBatchScanResults: results count  = 5. Current thread: Thread[main,5,main], id: 1
,11-24 15:40:36.839  5519  5519 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: onBatchScanResults. scan = ScanResult{mDevice=FB:F2:70:61:22:51, mScanRecord=ScanRecord [mAdvertiseFlags=6, mServiceUuids=null, mManufacturerSpecificData={76=[2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74]}, mServiceData={0000180a-0000-1000-8000-00805f9b34fb=[81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]}, mTxPowerLevel=-2147483648, mDeviceName=estimote], mRssi=-86, mTimestampNanos=95493010924}
11-24 15:40:36.839  5519  5519 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: ScanResult{mDevice=FB:F2:70:61:22:51, mScanRecord=ScanRecord [mAdvertiseFlags=6, mServiceUuids=null, mManufacturerSpecificData={76=[2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74]}, mServiceData={0000180a-0000-1000-8000-00805f9b34fb=[81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]}, mTxPowerLevel=-2147483648, mDeviceName=estimote], mRssi=-86, mTimestampNanos=95493010924}
11-24 15:40:36.839  5519  5519 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: parsedAdvertisement: [UUID = null, bluetoothMacAddress = 22:61:70:F2:FB:B6, provideBluetoothMacAddressRequestId = nullextra info = 81]
11-24 15:40:36.840  5519  5519 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: parsedAdvertisement uuid mismatch
11-24 15:40:36.840  5519  5519 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: onBatchScanResults. scan = ScanResult{mDevice=F4:45:54:B3:86:47, mScanRecord=ScanRecord [mAdvertiseFlags=6, mServiceUuids=null, mManufacturerSpecificData={76=[2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74]}, mServiceData={0000180a-0000-1000-8000-00805f9b34fb=[71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]}, mTxPowerLevel=-2147483648, mDeviceName=estimote], mRssi=-88, mTimestampNanos=96093010924}
,11-24 15:40:36.840  5519  5519 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: ScanResult{mDevice=F4:45:54:B3:86:47, mScanRecord=ScanRecord [mAdvertiseFlags=6, mServiceUuids=null, mManufacturerSpecificData={76=[2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74]}, mServiceData={0000180a-0000-1000-8000-00805f9b34fb=[71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]}, mTxPowerLevel=-2147483648, mDeviceName=estimote], mRssi=-88, mTimestampNanos=96093010924}
11-24 15:40:36.840  5519  5519 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: parsedAdvertisement: [UUID = null, bluetoothMacAddress = 86:B3:54:45:F4:B6, provideBluetoothMacAddressRequestId = nullextra info = 71]
11-24 15:40:36.840  5519  5519 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: parsedAdvertisement uuid mismatch
11-24 15:40:36.840  5519  5519 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: onBatchScanResults. scan = ScanResult{mDevice=D2:74:8F:0E:D1:25, mScanRecord=ScanRecord [mAdvertiseFlags=6, mServiceUuids=null, mManufacturerSpecificData={76=[2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74]}, mServiceData={0000180a-0000-1000-8000-00805f9b34fb=[37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]}, mTxPowerLevel=-2147483648, mDeviceName=estimote], mRssi=-94, mTimestampNanos=94743010924}
11-24 15:40:36.840  5519  5519 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: ScanResult{mDevice=D2:74:8F:0E:D1:25, mScanRecord=ScanRecord [mAdvertiseFlags=6, mServiceUuids=null, mManufacturerSpecificData={76=[2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74]}, mServiceData={0000180a-0000-1000-8000-00805f9b34fb=[37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]}, mTxPowerLevel=-2147483648, mDeviceName=estimote], mRssi=-94, mTimestampNanos=94743010924}
11-24 15:40:36.841  5519  5519 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: parsedAdvertisement: [UUID = null, bluetoothMacAddress = D1:0E:8F:74:D2:B6, provideBluetoothMacAddressRequestId = nullextra info = 37]
11-24 15:40:36.841  5519  5519 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: parsedAdvertisement uuid mismatch
11-24 15:40:36.841  5519  5519 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: onBatchScanResults. scan = ScanResult{mDevice=DB:69:06:8B:FC:D2, mScanRecord=ScanRecord [mAdvertiseFlags=6, mServiceUuids=null, mManufacturerSpecificData={76=[2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74]}, mServiceData={0000180a-0000-1000-8000-00805f9b34fb=[-46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]}, mTxPowerLevel=-2147483648, mDeviceName=estimote], mRssi=-91, mTimestampNanos=95443010924}
11-24 15:40:36.841  5519  5519 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: ScanResult{mDevice=DB:69:06:8B:FC:D2, mScanRecord=ScanRecord [mAdvertiseFlags=6, mServiceUuids=null, mManufacturerSpecificData={76=[2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74]}, mServiceData={0000180a-0000-1000-8000-00805f9b34fb=[-46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]}, mTxPowerLevel=-2147483648, mDeviceName=estimote], mRssi=-91, mTimestampNanos=95443010924}
11-24 15:40:36.841  5519  5519 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: parsedAdvertisement: [UUID = null, bluetoothMacAddress = FC:8B:06:69:DB:B6, provideBluetoothMacAddressRequestId = nullextra info = 210]
11-24 15:40:36.841  5519  5519 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: parsedAdvertisement uuid mismatch
11-24 15:40:36.841  5519  5519 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: onBatchScanResults. scan = ScanResult{mDevice=E3:EC:A5:91:D5:74, mScanRecord=ScanRecord [mAdvertiseFlags=6, mServiceUuids=null, mManufacturerSpecificData={76=[2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74]}, mServiceData={}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-92, mTimestampNanos=94693010924}
11-24 15:40:36.841  5519  5519 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: ScanResult{mDevice=E3:EC:A5:91:D5:74, mScanRecord=ScanRecord [mAdvertiseFlags=6, mServiceUuids=null, mManufacturerSpecificData={76=[2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74]}, mServiceData={}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-92, mTimestampNanos=94693010924}
,11-24 15:40:36.887  3592  5575 D GetConfigurationSnapshotOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,11-24 15:40:36.915  3592  5573 I PhenotypeFlagCommitter: Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,11-24 15:40:36.918  3592  5573 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,11-24 15:40:36.919  4675  4705 D Finsky  : [180] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
11-24 15:40:36.921  4675  4675 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,11-24 15:40:36.923   926  4746 I ActivityManager: Killing 4188:com.google.android.apps.maps/u0a58 (adj 15): empty #17
,11-24 15:40:36.952  3592  5573 W Uploader:  no longer exists, so no auth token.
,11-24 15:40:36.958  3592  5575 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,11-24 15:40:37.338  4261  4261 D BtGatt.ScanManager: awakened up at time 96646
,11-24 15:40:37.343  4261  4303 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-24 15:40:37.364  4261  4300 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=2
,11-24 15:40:37.364  4261  4300 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 15:40:37.365  4261  4300 D BtGatt.GattService: current time is 96673704050
,11-24 15:40:37.365  4261  4300 D BtGatt.GattService: Batch record : [116, -43, -111, -91, -20, -29, 1, -128, -78, 2, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 37, -47, 14, -113, 116, -46, 1, -128, -90, 1, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,11-24 15:40:37.365  4261  4300 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
11-24 15:40:37.366  4261  4300 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,11-24 15:40:37.367  5519  5519 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: onBatchScanResults: results count  = 2. Current thread: Thread[main,5,main], id: 1
11-24 15:40:37.367  5519  5519 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: onBatchScanResults. scan = ScanResult{mDevice=D2:74:8F:0E:D1:25, mScanRecord=ScanRecord [mAdvertiseFlags=6, mServiceUuids=null, mManufacturerSpecificData={76=[2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74]}, mServiceData={0000180a-0000-1000-8000-00805f9b34fb=[37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]}, mTxPowerLevel=-2147483648, mDeviceName=estimote], mRssi=-90, mTimestampNanos=96624083060}
11-24 15:40:37.368  5519  5519 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: ScanResult{mDevice=D2:74:8F:0E:D1:25, mScanRecord=ScanRecord [mAdvertiseFlags=6, mServiceUuids=null, mManufacturerSpecificData={76=[2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74]}, mServiceData={0000180a-0000-1000-8000-00805f9b34fb=[37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]}, mTxPowerLevel=-2147483648, mDeviceName=estimote], mRssi=-90, mTimestampNanos=96624083060}
,11-24 15:40:37.368  5519  5519 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: parsedAdvertisement: [UUID = null, bluetoothMacAddress = D1:0E:8F:74:D2:B6, provideBluetoothMacAddressRequestId = nullextra info = 37]
11-24 15:40:37.368  5519  5519 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: parsedAdvertisement uuid mismatch
,11-24 15:40:37.368  5519  5519 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: onBatchScanResults. scan = ScanResult{mDevice=E3:EC:A5:91:D5:74, mScanRecord=ScanRecord [mAdvertiseFlags=6, mServiceUuids=null, mManufacturerSpecificData={76=[2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74]}, mServiceData={0000180a-0000-1000-8000-00805f9b34fb=[116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]}, mTxPowerLevel=-2147483648, mDeviceName=estimote], mRssi=-78, mTimestampNanos=96574083060}
11-24 15:40:37.369  5519  5519 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: ScanResult{mDevice=E3:EC:A5:91:D5:74, mScanRecord=ScanRecord [mAdvertiseFlags=6, mServiceUuids=null, mManufacturerSpecificData={76=[2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74]}, mServiceData={0000180a-0000-1000-8000-00805f9b34fb=[116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]}, mTxPowerLevel=-2147483648, mDeviceName=estimote], mRssi=-78, mTimestampNanos=96574083060}
,11-24 15:40:37.369  5519  5519 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: parsedAdvertisement: [UUID = null, bluetoothMacAddress = D5:91:A5:EC:E3:B6, provideBluetoothMacAddressRequestId = nullextra info = 116]
,11-24 15:40:37.369  5519  5519 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: parsedAdvertisement uuid mismatch
,11-24 15:40:37.531  3592  5582 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,11-24 15:40:37.729  3592  5583 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,11-24 15:40:37.790  3592  5573 W Uploader:  no longer exists, so no auth token.
,11-24 15:40:37.802  3592  5582 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,11-24 15:40:37.823   926  2975 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,11-24 15:40:37.901  3592  5583 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,11-24 15:40:37.984  3592  5582 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,11-24 15:40:38.066  4261  4261 D BtGatt.ScanManager: awakened up at time 97374
11-24 15:40:38.067  4261  4303 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-24 15:40:38.078  4261  4300 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,11-24 15:40:38.078  4261  4300 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 15:40:38.079  5519  5519 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: onBatchScanResults: results count  = 0. Current thread: Thread[main,5,main], id: 1
,11-24 15:40:38.502  3592  3592 I SQLiteConnectionPool: The connection pool for /data/user/0/com.google.android.gms/databases/phenotype.db has been closed but there are still 1 connections in use.  They will be closed as they are released back to the pool.
,11-24 15:40:38.506  3592  5580 E ClearcutLoggerIntentService: attempt to re-open an already-closed object: SQLiteDatabase: /data/user/0/com.google.android.gms/databases/phenotype.db
11-24 15:40:38.506  3592  5580 E ClearcutLoggerIntentService: java.lang.IllegalStateException: attempt to re-open an already-closed object: SQLiteDatabase: /data/user/0/com.google.android.gms/databases/phenotype.db
11-24 15:40:38.506  3592  5580 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteClosable.acquireReference(SQLiteClosable.java:55)
11-24 15:40:38.506  3592  5580 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteDatabase.endTransaction(SQLiteDatabase.java:520)
11-24 15:40:38.506  3592  5580 E ClearcutLoggerIntentService: 	at com.google.android.gms.phenotype.service.a.g.a(SourceFile:143)
11-24 15:40:38.506  3592  5580 E ClearcutLoggerIntentService: 	at com.google.android.gms.clearcut.service.a.a(SourceFile:532)
11-24 15:40:38.506  3592  5580 E ClearcutLoggerIntentService: 	at com.google.android.gms.clearcut.service.a.a(SourceFile:149)
11-24 15:40:38.506  3592  5580 E ClearcutLoggerIntentService: 	at com.google.android.gms.common.service.g.run(SourceFile:178)
11-24 15:40:38.506  3592  5580 E ClearcutLoggerIntentService: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
11-24 15:40:38.506  3592  5580 E ClearcutLoggerIntentService: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
11-24 15:40:38.506  3592  5580 E ClearcutLoggerIntentService: 	at java.lang.Thread.run(Thread.java:818)
,11-24 15:40:39.610  5519  5565 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-24 15:40:39.610  5519  5565 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,11-24 15:40:39.610  5519  5565 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,11-24 15:40:39.610  5519  5565 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,11-24 15:40:39.611  5519  5565 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,11-24 15:40:39.611  5519  5565 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 15:40:39.611  5519  5565 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,11-24 15:40:39.611  5519  5565 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,11-24 15:40:39.611  5519  5565 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-57,5,main], id: 57
11-24 15:40:39.612  5519  5565 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
11-24 15:40:39.612  5519  5565 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,11-24 15:40:39.612  5519  5565 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-57,5,main], id: 57
11-24 15:40:39.612  5519  5565 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-57,5,main], id: 57
11-24 15:40:39.612  5519  5565 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-57,5,main], id: 57
11-24 15:40:39.613  5519  5565 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
11-24 15:40:39.613  5519  5565 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-57,5,main], id: 57
11-24 15:40:39.615  5519  5565 D BluetoothAdapter: STATE_ON
11-24 15:40:39.616  4261  4470 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
,11-24 15:40:39.617  5519  5565 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-24 15:40:39.618  4261  4303 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
11-24 15:40:39.619  5519  5565 D BluetoothAdapter: STATE_ON
11-24 15:40:39.620  4261  4276 D BtGatt.GattService: stopScan() - queue size =1
11-24 15:40:39.622  4261  4443 D BtGatt.GattService: unregisterClient() - clientIf=5
11-24 15:40:39.623  5519  5565 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-24 15:40:39.624  5519  5565 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-57,5,main], id: 57
11-24 15:40:39.624  5519  5565 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
11-24 15:40:39.624  5519  5565 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-57,5,main], id: 57
11-24 15:40:39.625  5519  5565 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-57,5,main], id: 57
11-24 15:40:39.625  5519  5565 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-57,5,main], id: 57
11-24 15:40:39.625  5519  5565 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-57,5,main], id: 57
11-24 15:40:39.625  5519  5565 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-24 15:40:39.625  5519  5565 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-57,5,main], id: 57
11-24 15:40:39.626  5519  5565 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-57,5,main], id: 57
11-24 15:40:39.626  5519  5565 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-57,5,main], id: 57
11-24 15:40:39.626  5519  5565 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-24 15:40:39.626  5519  5565 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-24 15:40:39.627  4261  4261 D BtGatt.ScanManager: awakened up at time 98935
,11-24 15:40:39.628  5519  5565 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-24 15:40:39.630  5519  5565 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
11-24 15:40:39.632  5519  5565 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
11-24 15:40:39.633  5519  5565 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-24 15:40:39.633  5519  5565 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
11-24 15:40:39.633  5519  5565 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
11-24 15:40:39.633  5519  5519 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-24 15:40:39.633  5519  5519 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-24 15:40:39.634  4261  4300 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-24 15:40:39.634  4261  4300 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 15:40:39.634  4261  4300 E BtGatt.ContextMap: Context not found for ID 5
11-24 15:40:39.634  5519  5519 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-24 15:40:39.634  5519  5519 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-24 15:40:39.635  5519  5519 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
,11-24 15:40:39.635  5519  5519 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
11-24 15:40:39.635  5519  5519 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-24 15:40:39.635  5519  5519 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
,11-24 15:40:39.635  5519  5519 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-24 15:40:39.635  5519  5519 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-24 15:40:39.635  5519  5519 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED] Current thread: Thread[main,5,main], id: 1
11-24 15:40:39.635  5519  5519 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-24 15:40:39.638  5519  5519 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-24 15:40:39.638  5519  5519 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-24 15:40:39.638  5519  5519 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
,11-24 15:40:39.646  4261  4300 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
,11-24 15:40:39.646  4261  4300 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 15:40:39.646  4261  4303 D BtGatt.ScanManager: stopping BLe Batch
,11-24 15:40:39.652  4261  4300 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,11-24 15:40:39.652  4261  4300 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 15:40:39.653  4261  4303 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-24 15:40:39.658  4261  4300 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-24 15:40:39.658  4261  4300 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-24 15:40:40.136  5519  5519 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-24 15:40:40.137  5519  5519 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-24 15:40:40.137  5519  5519 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,11-24 15:40:40.588   926  2973 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-24 15:40:44.634  5519  5565 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-24 15:40:44.635  5519  5565 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,11-24 15:40:44.635  5519  5565 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-24 15:40:44.635  5519  5565 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-24 15:40:44.636  5519  5565 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,11-24 15:40:44.636  5519  5565 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-24 15:40:44.636  5519  5565 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,11-24 15:40:44.636  5519  5565 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@59ba0ca not in the list
11-24 15:40:44.636  5519  5565 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 15:40:44.636  5519  5565 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@47d323b not in the list
,11-24 15:40:44.637  5519  5565 D io.jxcore.node.ConnectivityMonitor: stop
,11-24 15:40:44.637  5519  5565 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
,11-24 15:40:44.641  5519  5565 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-57,5,main], id: 57
,11-24 15:40:44.642  5519  5565 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
,11-24 15:40:44.644  5519  5565 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
11-24 15:40:44.644  5519  5565 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
,11-24 15:40:44.645  5519  5565 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
11-24 15:40:44.645  5519  5565 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,11-24 15:40:44.645  5519  5565 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-24 15:40:44.645  5519  5565 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 15:40:44.645  5519  5565 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@47d323b not in the list
11-24 15:40:44.647  5519  5565 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
,11-24 15:40:44.648  5519  5565 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-24 15:40:44.649  5519  5565 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-24 15:40:44.649  5519  5565 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-24 15:40:44.649  5519  5565 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,11-24 15:40:44.649  5519  5565 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 15:40:44.650  5519  5565 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@59ba0ca not in the list
11-24 15:40:44.650  5519  5565 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 15:40:44.650  5519  5565 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@47d323b not in the list
,11-24 15:40:44.650  5519  5565 D io.jxcore.node.ConnectivityMonitor: stop
11-24 15:40:44.650  5519  5565 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-57,5,main], id: 57
11-24 15:40:44.650  5519  5565 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
11-24 15:40:44.653  5519  5565 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
,11-24 15:40:44.653  5519  5565 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
11-24 15:40:44.653  5519  5565 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
11-24 15:40:44.653  5519  5565 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-24 15:40:44.653  5519  5565 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,11-24 15:40:44.653  5519  5565 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 15:40:44.653  5519  5565 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@47d323b not in the list
,11-24 15:40:44.655  5519  5565 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
11-24 15:40:44.655  5519  5565 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-24 15:40:44.655  5519  5565 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-24 15:40:44.655  5519  5565 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-24 15:40:44.655  5519  5565 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-24 15:40:44.656  5519  5565 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 15:40:44.656  5519  5565 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@59ba0ca not in the list
,11-24 15:40:44.656  5519  5565 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 15:40:44.656  5519  5565 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@47d323b not in the list
11-24 15:40:44.656  5519  5565 D io.jxcore.node.ConnectivityMonitor: stop
11-24 15:40:44.656  5519  5565 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-57,5,main], id: 57
11-24 15:40:44.656  5519  5565 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
,11-24 15:40:44.658  5519  5565 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
,11-24 15:40:44.658  5519  5565 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
11-24 15:40:44.658  5519  5565 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
11-24 15:40:44.658  5519  5565 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-24 15:40:44.658  5519  5565 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-24 15:40:44.659  5519  5565 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 15:40:44.659  5519  5565 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@47d323b not in the list
,11-24 15:40:44.660  5519  5565 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
11-24 15:40:44.660  5519  5565 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-24 15:40:44.660  5519  5565 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-24 15:40:44.660  5519  5565 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-24 15:40:44.660  5519  5565 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-24 15:40:44.660  5519  5565 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,11-24 15:40:44.660  5519  5565 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@59ba0ca not in the list
11-24 15:40:44.660  5519  5565 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 15:40:44.661  5519  5565 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@47d323b not in the list
11-24 15:40:44.661  5519  5565 D io.jxcore.node.ConnectivityMonitor: stop
11-24 15:40:44.661  5519  5565 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-57,5,main], id: 57
11-24 15:40:44.661  5519  5565 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
,11-24 15:40:44.663  5519  5565 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
11-24 15:40:44.663  5519  5565 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
11-24 15:40:44.663  5519  5565 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
11-24 15:40:44.663  5519  5565 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,11-24 15:40:44.663  5519  5565 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-24 15:40:44.663  5519  5565 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 15:40:44.664  5519  5565 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@47d323b not in the list
,11-24 15:40:44.665  5519  5565 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
,11-24 15:40:44.665  5519  5565 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-24 15:40:44.666  5519  5565 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-24 15:40:44.666  5519  5565 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-24 15:40:44.666  5519  5565 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-24 15:40:44.666  5519  5565 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 15:40:44.666  5519  5565 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@59ba0ca not in the list
11-24 15:40:44.666  5519  5565 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-24 15:40:44.666  5519  5565 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@47d323b not in the list
11-24 15:40:44.666  5519  5565 D io.jxcore.node.ConnectivityMonitor: stop
11-24 15:40:44.666  5519  5565 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-57,5,main], id: 57
11-24 15:40:44.666  5519  5565 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
,11-24 15:40:44.669  5519  5565 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
,11-24 15:40:44.669  5519  5565 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
11-24 15:40:44.670  5519  5565 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
11-24 15:40:44.670  5519  5565 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-24 15:40:44.670  5519  5565 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-24 15:40:44.670  5519  5565 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-24 15:40:44.670  5519  5565 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@47d323b not in the list
,11-24 15:40:44.671  5519  5565 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
11-24 15:40:44.672  5519  5565 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-24 15:40:44.672  5519  5565 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-24 15:40:44.672  5519  5565 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
11-24 15:40:44.672  5519  5565 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-24 15:40:44.672  5519  5565 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,11-24 15:40:44.672  5519  5565 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
11-24 15:40:44.672  5519  5565 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-24 15:40:44.673  5519  5565 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-24 15:40:44.673  5519  5565 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-24 15:40:44.673  5519  5565 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,11-24 15:40:44.673  5519  5565 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-24 15:40:44.673  5519  5565 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-24 15:40:44.673  5519  5565 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 15:40:44.673  5519  5565 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@59ba0ca not in the list
11-24 15:40:44.673  5519  5565 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 15:40:44.673  5519  5565 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@47d323b not in the list
11-24 15:40:44.674  5519  5565 D io.jxcore.node.ConnectivityMonitor: stop
,11-24 15:40:44.675  5519  5565 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-57,5,main], id: 57
11-24 15:40:44.675  5519  5565 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
,11-24 15:40:44.679  5519  5565 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
11-24 15:40:44.679  5519  5565 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
11-24 15:40:44.679  5519  5565 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
,11-24 15:40:44.680  5519  5565 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-24 15:40:44.680  5519  5565 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-24 15:40:44.680  5519  5565 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 15:40:44.680  5519  5565 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@47d323b not in the list
,11-24 15:40:44.681  5519  5565 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
11-24 15:40:44.681  5519  5565 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
11-24 15:40:44.681  5519  5565 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,11-24 15:40:44.685  5519  5565 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,11-24 15:40:44.685  5519  5565 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
11-24 15:40:44.685  5519  5565 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
11-24 15:40:44.685  5519  5565 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
11-24 15:40:44.685  5519  5565 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
11-24 15:40:44.685  5519  5565 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
11-24 15:40:44.685  5519  5565 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
11-24 15:40:44.685  5519  5565 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
11-24 15:40:44.686  5519  5565 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
11-24 15:40:44.686  5519  5565 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
11-24 15:40:44.686  5519  5565 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
,11-24 15:40:44.686  5519  5565 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
11-24 15:40:44.686  5519  5565 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
11-24 15:40:44.686  5519  5565 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
11-24 15:40:44.686  5519  5565 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
,11-24 15:40:44.686  5519  5565 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
11-24 15:40:44.686  5519  5565 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
11-24 15:40:44.686  5519  5565 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
11-24 15:40:44.686  5519  5565 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
,11-24 15:40:44.686  5519  5565 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
11-24 15:40:44.686  5519  5565 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
11-24 15:40:44.686  5519  5565 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
,11-24 15:40:44.686  5519  5565 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
11-24 15:40:44.686  5519  5565 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
11-24 15:40:44.686  5519  5565 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
11-24 15:40:44.686  5519  5565 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
11-24 15:40:44.686  5519  5565 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
11-24 15:40:44.686  5519  5565 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
11-24 15:40:44.687  5519  5565 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
,11-24 15:40:44.687  5519  5565 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
11-24 15:40:44.687  5519  5565 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
11-24 15:40:44.687  5519  5565 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
11-24 15:40:44.687  5519  5565 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
,11-24 15:40:44.687  5519  5565 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
,11-24 15:40:44.687  5519  5565 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
11-24 15:40:44.687  5519  5565 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
11-24 15:40:44.687  5519  5565 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
11-24 15:40:44.687  5519  5565 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
11-24 15:40:44.688  5519  5565 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
11-24 15:40:44.688  5519  5565 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
11-24 15:40:44.688  5519  5565 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
,11-24 15:40:44.692  5519  5565 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
11-24 15:40:44.693  5519  5565 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
11-24 15:40:44.693  5519  5565 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
11-24 15:40:44.694  5519  5565 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
11-24 15:40:44.694  5519  5565 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
11-24 15:40:44.694  5519  5565 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
11-24 15:40:44.694  5519  5565 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,11-24 15:40:44.694  5519  5584 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 121)
,11-24 15:40:44.694  5519  5565 E io.jxcore.node.ConnectionHelper: connect: Callback is null
,11-24 15:40:44.695  5519  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: tryToConnect:  socketConnectSucceeded = false, mIsShuttingDown = false
11-24 15:40:44.695  5519  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: socket closed
11-24 15:40:44.695  5519  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: SYSTEM_DECIDED_INSECURE_RFCOMM_SOCKET_PORT
,11-24 15:40:44.696  5519  5565 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-24 15:40:44.696  5519  5565 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,11-24 15:40:44.696  5519  5565 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-24 15:40:44.696  5519  5565 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-24 15:40:44.696  5519  5565 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 15:40:44.696  5519  5565 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
11-24 15:40:44.698  5519  5565 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@59ba0ca not in the list
,11-24 15:40:44.698  5519  5584 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: connecting
,11-24 15:40:44.698  5519  5565 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 15:40:44.697  4470  4470 W Binder_5: type=1400 audit(0.0:115): avc: denied { ioctl } for path="socket:[34167]" dev="sockfs" ino=34167 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-24 15:40:44.698  5519  5584 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-24 15:40:44.698  5519  5565 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@47d323b not in the list
11-24 15:40:44.697  4470  4470 W Binder_5: type=1400 audit(0.0:116): avc: denied { ioctl } for path="socket:[34167]" dev="sockfs" ino=34167 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-24 15:40:44.698  5519  5565 D io.jxcore.node.ConnectivityMonitor: stop
11-24 15:40:44.699  5519  5585 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 121
11-24 15:40:44.699  5519  5585 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close
11-24 15:40:44.699  5519  5565 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-57,5,main], id: 57
11-24 15:40:44.699  5519  5585 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Trying to close the Bluetooth socket... (thread ID: 121)
11-24 15:40:44.699  5519  5585 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Bluetooth socket closed (thread ID: 121)
11-24 15:40:44.699  5519  5565 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
11-24 15:40:44.702  5519  5565 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
11-24 15:40:44.702  5519  5565 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
11-24 15:40:44.702  5519  5565 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
11-24 15:40:44.702  5519  5565 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-24 15:40:44.702  5519  5584 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: connect, socket closed
11-24 15:40:44.702  5519  5565 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-24 15:40:44.702  5519  5565 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-24 15:40:44.702  5519  5584 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: socketConnectSucceeded false
11-24 15:40:44.702  5519  5565 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@47d323b not in the list
11-24 15:40:44.702  5519  5584 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 121)
11-24 15:40:44.703  5519  5565 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
11-24 15:40:44.703  5519  5565 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-24 15:40:44.703  5519  5565 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-24 15:40:44.703  5519  5565 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-24 15:40:44.704  5519  5565 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-24 15:40:44.704  5519  5565 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 15:40:44.704  5519  5565 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@59ba0ca not in the list
11-24 15:40:44.704  5519  5565 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-24 15:40:44.704  5519  5565 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@47d323b not in the list
11-24 15:40:44.704  5519  5565 D io.jxcore.node.ConnectivityMonitor: stop
11-24 15:40:44.704  5519  5565 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-57,5,main], id: 57
11-24 15:40:44.704  5519  5565 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
,11-24 15:40:44.706  5519  5565 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
11-24 15:40:44.706  5519  5565 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
11-24 15:40:44.706  5519  5565 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
11-24 15:40:44.706  5519  5565 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-24 15:40:44.706  5519  5565 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-24 15:40:44.706  5519  5565 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 15:40:44.707  5519  5565 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@47d323b not in the list
,11-24 15:40:44.707  5519  5565 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
11-24 15:40:44.708  5519  5565 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-24 15:40:44.708  5519  5565 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-24 15:40:44.708  5519  5565 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-24 15:40:44.708  5519  5565 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-24 15:40:44.708  5519  5565 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,11-24 15:40:44.708  5519  5565 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@59ba0ca not in the list
,11-24 15:40:44.708  5519  5565 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 15:40:44.708  5519  5565 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@47d323b not in the list
11-24 15:40:44.708  5519  5565 D io.jxcore.node.ConnectivityMonitor: stop
11-24 15:40:44.709  5519  5565 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-57,5,main], id: 57
11-24 15:40:44.709  5519  5565 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
11-24 15:40:44.710  5519  5565 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
11-24 15:40:44.710  5519  5565 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
11-24 15:40:44.710  5519  5565 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
11-24 15:40:44.710  5519  5565 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,11-24 15:40:44.710  5519  5565 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-24 15:40:44.710  5519  5565 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 15:40:44.710  5519  5565 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@47d323b not in the list
11-24 15:40:44.711  5519  5565 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
11-24 15:40:44.711  5519  5565 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
11-24 15:40:44.711  5519  5565 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
11-24 15:40:44.711  5519  5565 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
11-24 15:40:44.711  5519  5565 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
11-24 15:40:44.711  5519  5565 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
,11-24 15:40:44.711  5519  5565 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
11-24 15:40:44.711  5519  5565 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
11-24 15:40:44.711  5519  5565 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
11-24 15:40:44.712  5519  5565 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
11-24 15:40:44.712  5519  5565 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
11-24 15:40:44.712  5519  5565 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
11-24 15:40:44.712  5519  5565 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-24 15:40:44.712  5519  5565 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-24 15:40:44.712  5519  5565 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,11-24 15:40:44.712  5519  5565 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-24 15:40:44.712  5519  5565 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 15:40:44.713  5519  5565 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@59ba0ca not in the list
11-24 15:40:44.713  5519  5565 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 15:40:44.713  5519  5565 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@47d323b not in the list
11-24 15:40:44.713  5519  5565 D io.jxcore.node.ConnectivityMonitor: stop
11-24 15:40:44.713  5519  5565 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-57,5,main], id: 57
11-24 15:40:44.713  5519  5565 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
,11-24 15:40:44.714  5519  5565 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
11-24 15:40:44.715  5519  5565 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
,11-24 15:40:44.715  5519  5565 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
11-24 15:40:44.715  5519  5565 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-24 15:40:44.715  5519  5565 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-24 15:40:44.715  5519  5565 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 15:40:44.715  5519  5565 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@47d323b not in the list
,11-24 15:40:44.716  5519  5565 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-24 15:40:44.716  5519  5565 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,11-24 15:40:44.716  5519  5565 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@59ba0ca not in the list
11-24 15:40:44.716  5519  5565 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 15:40:44.716  5519  5565 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@47d323b not in the list
11-24 15:40:44.716  5519  5565 D io.jxcore.node.ConnectivityMonitor: stop
,11-24 15:40:49.717  5519  5565 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-24 15:40:49.717  5519  5565 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@47d323b not in the list
11-24 15:40:49.717  5519  5565 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-24 15:40:49.718  5519  5565 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 15:40:49.718  5519  5565 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@59ba0ca not in the list
11-24 15:40:49.718  5519  5565 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-24 15:40:49.718  5519  5565 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,11-24 15:40:49.719  5519  5565 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-24 15:40:49.719  5519  5565 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-24 15:40:49.719  5519  5565 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 15:40:49.719  5519  5565 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@59ba0ca not in the list
11-24 15:40:49.719  5519  5565 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 15:40:49.719  5519  5565 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@47d323b not in the list
11-24 15:40:49.720  5519  5565 D io.jxcore.node.ConnectivityMonitor: stop
11-24 15:40:49.720  5519  5565 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-57,5,main], id: 57
11-24 15:40:49.720  5519  5565 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
,11-24 15:40:49.724  5519  5565 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
11-24 15:40:49.724  5519  5565 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
,11-24 15:40:49.725  5519  5565 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
11-24 15:40:49.725  5519  5565 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,11-24 15:40:49.725  5519  5565 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-24 15:40:49.725  5519  5565 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 15:40:49.726  5519  5565 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@47d323b not in the list
,11-24 15:40:49.731  5519  5565 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
,11-24 15:40:49.732  5519  5565 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-24 15:40:49.732  5519  5565 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
,11-24 15:40:49.738  5519  5565 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,11-24 15:40:49.740  5519  5565 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
11-24 15:40:49.740  5519  5565 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
11-24 15:40:49.740  5519  5565 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
11-24 15:40:49.740  5519  5586 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
,11-24 15:40:49.740  5519  5565 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
11-24 15:40:49.740  5519  5565 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
11-24 15:40:49.740  5519  5519 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
11-24 15:40:49.741  5519  5565 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,11-24 15:40:49.741  5519  5565 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
,11-24 15:40:49.741  5519  5565 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
11-24 15:40:49.741  5519  5565 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
11-24 15:40:49.741  5519  5565 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
11-24 15:40:49.741  5519  5586 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-24 15:40:49.742  5519  5565 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
11-24 15:40:49.742  5519  5565 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
11-24 15:40:49.742  5519  5565 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@59ba0ca not in the list
11-24 15:40:49.742  5519  5519 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
11-24 15:40:49.742  5519  5565 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-24 15:40:49.742  5519  5565 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-24 15:40:49.742  5519  5565 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-57,5,main], id: 57
11-24 15:40:49.742  5519  5565 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
11-24 15:40:49.742  5519  5565 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-24 15:40:49.742  5519  5565 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
,11-24 15:40:49.744  5519  5565 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
11-24 15:40:49.744  5519  5586 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
11-24 15:40:49.745  5519  5565 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-24 15:40:49.745  5519  5586 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
11-24 15:40:49.745  5519  5565 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
11-24 15:40:49.745  5519  5586 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
,11-24 15:40:49.745  5519  5565 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
11-24 15:40:49.745  5519  5565 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@47d323b not in the list
11-24 15:40:49.745  5519  5519 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-24 15:40:49.745  5519  5565 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-24 15:40:49.745  5519  5519 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-24 15:40:49.745  5519  5565 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,11-24 15:40:49.745  5519  5565 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-24 15:40:49.745  5519  5519 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-24 15:40:49.745  5519  5565 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-24 15:40:49.745  5519  5565 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
11-24 15:40:49.745  5519  5519 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
11-24 15:40:49.745  5519  5519 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,11-24 15:40:49.745  5519  5565 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@59ba0ca not in the list
11-24 15:40:49.746  5519  5565 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 15:40:49.746  5519  5565 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@47d323b not in the list
11-24 15:40:49.746  5519  5565 D io.jxcore.node.ConnectivityMonitor: stop
11-24 15:40:49.746  5519  5565 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-57,5,main], id: 57
11-24 15:40:49.746  5519  5565 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
,11-24 15:40:49.741  4276  4276 W Binder_2: type=1400 audit(0.0:117): avc: denied { ioctl } for path="socket:[32980]" dev="sockfs" ino=32980 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-24 15:40:49.741  4276  4276 W Binder_2: type=1400 audit(0.0:118): avc: denied { ioctl } for path="socket:[32980]" dev="sockfs" ino=32980 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,11-24 15:40:49.747  5519  5565 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
11-24 15:40:49.747  5519  5565 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
,11-24 15:40:49.747  5519  5565 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
11-24 15:40:49.747  5519  5565 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-24 15:40:49.747  5519  5565 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-24 15:40:49.748  5519  5565 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 15:40:49.748  5519  5565 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@47d323b not in the list
11-24 15:40:49.749  5519  5565 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
,11-24 15:40:49.749  5519  5565 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
11-24 15:40:49.749  5519  5565 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
11-24 15:40:49.749  5519  5565 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-24 15:40:49.750  5519  5565 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-24 15:40:49.750  5519  5565 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-24 15:40:49.750  5519  5565 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,11-24 15:40:49.750  5519  5565 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-24 15:40:49.750  5519  5565 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-24 15:40:49.750  5519  5565 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 15:40:49.750  5519  5565 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@59ba0ca not in the list
11-24 15:40:49.750  5519  5565 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 15:40:49.750  5519  5565 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@47d323b not in the list
11-24 15:40:49.750  5519  5565 D io.jxcore.node.ConnectivityMonitor: stop
,11-24 15:40:49.750  5519  5565 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-57,5,main], id: 57
11-24 15:40:49.750  5519  5565 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
,11-24 15:40:49.753  5519  5565 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
,11-24 15:40:49.753  5519  5565 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
11-24 15:40:49.754  5519  5565 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
11-24 15:40:49.754  5519  5565 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-24 15:40:49.754  5519  5565 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,11-24 15:40:49.755  5519  5565 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 15:40:49.755  5519  5565 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@47d323b not in the list
,11-24 15:40:49.761  5519  5565 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-24 15:40:49.761  5519  5565 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-24 15:40:49.761  5519  5565 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-24 15:40:49.761  5519  5565 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-24 15:40:49.761  5519  5565 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,11-24 15:40:49.761  5519  5565 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@59ba0ca not in the list
11-24 15:40:49.762  5519  5565 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 15:40:49.762  5519  5565 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@47d323b not in the list
11-24 15:40:49.762  5519  5565 D io.jxcore.node.ConnectivityMonitor: stop
,11-24 15:40:49.762  5519  5565 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-57,5,main], id: 57
11-24 15:40:49.762  5519  5565 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
11-24 15:40:49.763  5519  5565 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
,11-24 15:40:49.763  5519  5565 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
11-24 15:40:49.763  5519  5565 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
11-24 15:40:49.763  5519  5565 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-24 15:40:49.763  5519  5565 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,11-24 15:40:49.763  5519  5565 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 15:40:49.763  5519  5565 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@47d323b not in the list
11-24 15:40:49.764  5519  5565 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-24 15:40:49.764  5519  5565 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,11-24 15:40:49.764  5519  5565 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-24 15:40:49.764  5519  5565 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-24 15:40:49.764  5519  5565 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 15:40:49.765  5519  5565 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@59ba0ca not in the list
,11-24 15:40:49.765  5519  5565 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 15:40:49.765  5519  5565 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@47d323b not in the list
11-24 15:40:49.765  5519  5565 D io.jxcore.node.ConnectivityMonitor: stop
11-24 15:40:49.765  5519  5565 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-57,5,main], id: 57
11-24 15:40:49.765  5519  5565 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
11-24 15:40:49.767  5519  5565 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
11-24 15:40:49.767  5519  5565 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
,11-24 15:40:49.767  5519  5565 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
11-24 15:40:49.767  5519  5565 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-24 15:40:49.767  5519  5565 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-24 15:40:49.767  5519  5565 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-24 15:40:49.767  5519  5565 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@47d323b not in the list
,11-24 15:40:49.769  5519  5565 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
,11-24 15:40:49.769  5519  5565 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
11-24 15:40:49.769  5519  5565 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
11-24 15:40:49.769  5519  5565 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
11-24 15:40:49.769  5519  5565 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
11-24 15:40:49.769  5519  5565 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
11-24 15:40:49.771  5519  5565 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
,11-24 15:40:49.771  5519  5565 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
11-24 15:40:49.772  5519  5565 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
11-24 15:40:49.772  5519  5565 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
11-24 15:40:49.772  5519  5565 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
11-24 15:40:49.772  5519  5565 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
11-24 15:40:49.772  5519  5565 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
,11-24 15:40:49.772  5519  5565 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
11-24 15:40:49.773  5519  5565 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
11-24 15:40:49.773  5519  5565 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
11-24 15:40:49.774  5519  5565 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
11-24 15:40:49.774  5519  5565 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
11-24 15:40:49.774  5519  5565 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
,11-24 15:40:49.774  5519  5565 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
11-24 15:40:49.776  5519  5565 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-24 15:40:49.776  5519  5565 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@f9bfc88 added. We now have 3 listener(s)
11-24 15:40:49.776  5519  5565 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-24 15:40:49.778  5519  5565 D BluetoothAdapter: enable(): BT is already enabled..!
,11-24 15:40:49.778   926  3791 D WifiService: setWifiEnabled: true pid=5519, uid=10077
11-24 15:40:49.778   926  3791 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-24 15:40:49.827  4261  4424 W bt_sdp  : SDP - Rcvd conn cnf with error: 0x4  CID 0x40
,11-24 15:40:49.827  4261  4440 E bt_btif_sock_rfcomm: find_rfc_slot_by_id unable to find RFCOMM slot id: 5
,11-24 15:40:50.246  5519  5519 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-24 15:40:53.798   535   535 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,11-24 15:40:53.799   535   535 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,11-24 15:40:54.784  5519  5565 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,11-24 15:40:54.785  5519  5565 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@58c2621 added. We now have 4 listener(s)
,11-24 15:40:54.785  5519  5565 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-24 15:40:54.798  5519  5565 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-24 15:40:54.799  5519  5565 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@58c2621 removed from the list
,11-24 15:40:54.799  5519  5565 D io.jxcore.node.ConnectivityMonitor: stop
,11-24 15:40:54.800  5519  5565 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,11-24 15:40:54.800  5519  5565 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@ed07a46 added. We now have 4 listener(s)
,11-24 15:40:54.800  5519  5565 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-24 15:40:54.802  5519  5565 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-24 15:40:54.803  5519  5565 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@ed07a46 removed from the list
11-24 15:40:54.803  5519  5565 D io.jxcore.node.ConnectivityMonitor: stop
,11-24 15:40:54.804  5519  5565 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-24 15:40:54.804  5519  5565 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@c299407 added. We now have 4 listener(s)
11-24 15:40:54.804  5519  5565 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-24 15:40:54.808   926  4746 D WifiService: setWifiEnabled: false pid=5519, uid=10077
11-24 15:40:54.808   926  4746 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-24 15:40:54.815   926  2973 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,11-24 15:40:54.815   926  2973 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
,11-24 15:40:54.815   926  2973 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
11-24 15:40:54.816   926  2973 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
11-24 15:40:54.819  5519  5565 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-24 15:40:54.819  5519  5565 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
11-24 15:40:54.821  4261  4296 D BluetoothAdapterState: Current state: ON, message: 23
11-24 15:40:54.821  4261  4296 D BluetoothAdapterProperties: Setting state to 13
,11-24 15:40:54.822  4261  4296 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
11-24 15:40:54.824  4261  4296 D BluetoothAdapterProperties: onBluetoothDisable()
,11-24 15:40:54.826  4261  4296 I BluetoothAdapterState: Entering PendingCommandState
,11-24 15:40:54.827  4261  4300 D BluetoothAdapterProperties: Scan Mode:20
11-24 15:40:54.828  4261  4296 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
,11-24 15:40:54.828  5519  5565 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,11-24 15:40:54.829  5519  5565 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-24 15:40:54.829  5519  5565 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-24 15:40:54.829  5519  5565 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-24 15:40:54.829  5519  5565 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-24 15:40:54.829  5519  5565 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-24 15:40:54.829  5519  5565 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-24 15:40:54.829  5519  5565 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-24 15:40:54.829  5519  5565 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-24 15:40:54.829  5519  5565 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
11-24 15:40:54.830  5519  5565 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-24 15:40:54.830  5519  5565 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
11-24 15:40:54.830  5519  5565 D io.jxcore.node.ConnectivityMonitor: start: OK
11-24 15:40:54.833   926  5295 D DhcpClient: Clearing IP address
11-24 15:40:54.834   507   920 D CommandListener: Clearing all IP addresses on wlan0
11-24 15:40:54.835  4261  4261 D HeadsetService: Received stop request...Stopping profile...
,11-24 15:40:54.839   926   926 D BluetoothHeadset: Proxy object disconnected
11-24 15:40:54.840  5519  5519 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-24 15:40:54.840  3141  4171 D BluetoothHeadset: Proxy object disconnected
11-24 15:40:54.841  3141  3141 D HeadsetProfile: Bluetooth service disconnected
11-24 15:40:54.841  3774  4026 D BluetoothHeadset: Proxy object disconnected
11-24 15:40:54.841   926   926 D BluetoothHeadset: Proxy object disconnected
11-24 15:40:54.842   926   926 D BluetoothHeadset: Proxy object disconnected
11-24 15:40:54.843  4261  4261 D A2dpService: Received stop request...Stopping profile...
11-24 15:40:54.843  4261  4453 D A2dpStateMachine: Exit Disconnected: -1
11-24 15:40:54.845  5519  5519 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-24 15:40:54.846   507   920 D CommandListener: Setting iface cfg
,11-24 15:40:54.849  5519  5519 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-24 15:40:54.849  3592  5348 V NativeCrypto: Read error: ssl=0x7f84283180: I/O error during system call, Connection timed out
11-24 15:40:54.851  3592  5348 V NativeCrypto: SSL shutdown failed: ssl=0x7f84283180: I/O error during system call, Broken pipe
,11-24 15:40:54.853  5519  5519 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-24 15:40:54.861   926   939 I ActivityManager: Start proc 5590:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
,11-24 15:40:54.864   926   926 D BluetoothA2dp: Proxy object disconnected
11-24 15:40:54.864   926  2975 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
,11-24 15:40:54.864   926  2975 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
11-24 15:40:54.865  4261  4261 V BluetoothAdapterState: isTurningOff()=true
,11-24 15:40:54.865  4261  4261 V BluetoothAdapterState: isTurningOn()=false
11-24 15:40:54.865  4261  4261 V BluetoothAdapterState: isBleTurningOn()=false
11-24 15:40:54.865  4261  4261 V BluetoothAdapterState: isBleTurningOff()=false
11-24 15:40:54.865  4261  4261 D HidService: Received stop request...Stopping profile...
11-24 15:40:54.865  4261  4261 D HidService: Stopping Bluetooth HidService
11-24 15:40:54.869  4261  4261 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
11-24 15:40:54.869  4261  4261 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
11-24 15:40:54.869  4261  4261 D BluetoothMapService: onReceive
11-24 15:40:54.870  4261  4261 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
11-24 15:40:54.870  4261  4261 D BluetoothMapService: STATE_TURNING_OFF
11-24 15:40:54.870  4261  4424 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-24 15:40:54.870  4261  4261 V BluetoothAdapterState: isTurningOff()=true
,11-24 15:40:54.870  4261  4424 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-24 15:40:54.870  4261  4261 V BluetoothAdapterState: isTurningOn()=false
11-24 15:40:54.870  4261  4424 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-24 15:40:54.870  4261  4300 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
11-24 15:40:54.870  4261  4300 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
11-24 15:40:54.872   926  5296 D DhcpClient: Receive thread stopped
11-24 15:40:54.872   926   926 D RttService: SCAN_AVAILABLE : 1
11-24 15:40:54.872   926  2975 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
11-24 15:40:54.873   533   533 E Parcel  : Reading a NULL string not supported here.
11-24 15:40:54.874  4261  4261 V BluetoothAdapterState: isBleTurningOn()=false
11-24 15:40:54.874  4261  4261 V BluetoothAdapterState: isBleTurningOff()=false
11-24 15:40:54.874   926  3083 D RttService: EnabledState got{ when=-1ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
11-24 15:40:54.874  4261  4261 V BluetoothAdapterState: isTurningOff()=true
11-24 15:40:54.874  4261  4261 V BluetoothAdapterState: isTurningOn()=false
11-24 15:40:54.874  4261  4261 V BluetoothAdapterState: isBleTurningOn()=false
11-24 15:40:54.874  4261  4261 V BluetoothAdapterState: isBleTurningOff()=false
,11-24 15:40:54.875  3740  3887 W QCNEJ   : |CORE| network lost: 100
,11-24 15:40:54.876  4261  4261 D HealthService: Received stop request...Stopping profile...
11-24 15:40:54.876  3740  3887 W QCNEJ   : |CORE| onLost: unbind the process to WIFI
11-24 15:40:54.877  4261  4261 D PanService: Received stop request...Stopping profile...
11-24 15:40:54.880   926  2973 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
11-24 15:40:54.881  4261  4424 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-24 15:40:54.881  4261  4424 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-24 15:40:54.881  4261  4300 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
11-24 15:40:54.881  4261  4424 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
11-24 15:40:54.881  4261  4424 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
11-24 15:40:54.881  4261  4424 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
11-24 15:40:54.881  4261  4424 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
11-24 15:40:54.881  4261  4261 D BluetoothMapService: Received stop request...Stopping profile...
11-24 15:40:54.881  4261  4261 D BluetoothMapService: stop()
11-24 15:40:54.881  3141  3141 D BluetoothA2dp: Proxy object disconnected
11-24 15:40:54.882  3141  3141 D BluetoothInputDevice: Proxy object disconnected
11-24 15:40:54.882  3141  3141 D HidProfile: Bluetooth service disconnected
11-24 15:40:54.884  3141  3141 D BluetoothPan: BluetoothPAN Proxy object disconnected
11-24 15:40:54.885  3141  3141 D PanProfile: Bluetooth service disconnected
11-24 15:40:54.885  4261  4261 D BluetoothMapAppObserver: deinitObservers()
11-24 15:40:54.885  4261  4261 D BluetoothMapAppObserver: removeReceiver()
,11-24 15:40:54.886  4261  4261 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
11-24 15:40:54.888  4261  4261 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
11-24 15:40:54.888  4261  4300 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
11-24 15:40:54.888  4261  4261 D SapService: Received stop request...Stopping profile...
11-24 15:40:54.888  4261  4261 V SapService: stop()
11-24 15:40:54.890  4261  4261 I BtOppRfcommListener: stopping Accept Thread
11-24 15:40:54.890   926  2973 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
11-24 15:40:54.890  4261  5199 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
11-24 15:40:54.891  4261  5199 I BtOppRfcommListener: BluetoothSocket listen thread finished
11-24 15:40:54.894  4261  4261 V BluetoothAdapterState: isTurningOff()=true
11-24 15:40:54.894  4261  4261 V BluetoothAdapterState: isTurningOn()=false
11-24 15:40:54.894  4261  4261 V BluetoothAdapterState: isBleTurningOn()=false
11-24 15:40:54.894  4261  4261 V BluetoothAdapterState: isBleTurningOff()=false
11-24 15:40:54.894  4261  4261 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
11-24 15:40:54.894  4261  4300 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
11-24 15:40:54.895  4261  4261 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
11-24 15:40:54.895  4261  4261 V BluetoothAdapterState: isTurningOff()=true
11-24 15:40:54.895  4261  4261 V BluetoothAdapterState: isTurningOn()=false
11-24 15:40:54.895  4261  4261 V BluetoothAdapterState: isBleTurningOn()=false
11-24 15:40:54.895  4261  4261 V BluetoothAdapterState: isBleTurningOff()=false
11-24 15:40:54.896  4261  4261 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
11-24 15:40:54.896  4261  4261 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
11-24 15:40:54.897  4261  4261 D BluetoothMapService: MAP Service closeService in
11-24 15:40:54.897  4261  4261 D BluetoothMapMasInstance0: MAP Service shutdown
11-24 15:40:54.897  4261  4261 D ObexServerSockets0: shutdown(block = true)
11-24 15:40:54.897  4261  4261 D ObexServerSockets0: shutdown called from another thread - interrupt().
11-24 15:40:54.897  4261  4479 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 5
11-24 15:40:54.897  4261  4440 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
11-24 15:40:54.897  4261  4480 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
11-24 15:40:54.898  4261  4261 D ObexServerSockets0: shutdown called from another thread - interrupt().
11-24 15:40:54.898  4261  4261 V BluetoothAdapterState: isTurningOff()=true
11-24 15:40:54.898  4261  4261 V BluetoothAdapterState: isTurningOn()=false
11-24 15:40:54.898  4261  4261 V BluetoothAdapterState: isBleTurningOn()=false
11-24 15:40:54.898  4261  4261 V BluetoothAdapterState: isBleTurningOff()=false
11-24 15:40:54.899  4261  4261 D BluetoothMapService: cleanup()
11-24 15:40:54.899  4261  4261 D BluetoothMapService: MAP Service closeService in
11-24 15:40:54.899  4261  4261 V BluetoothAdapterState: isTurningOff()=true
11-24 15:40:54.899  4261  4261 V BluetoothAdapterState: isTurningOn()=false
11-24 15:40:54.899  4261  4261 V BluetoothAdapterState: isBleTurningOn()=false
11-24 15:40:54.899  4261  4261 V BluetoothAdapterState: isBleTurningOff()=false
11-24 15:40:54.899  4261  4296 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
11-24 15:40:54.900  4261  4296 D BluetoothAdapterProperties: Setting state to 15
11-24 15:40:54.900  4261  4296 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
11-24 15:40:54.900  4261  4296 I BluetoothAdapterState: Entering BleOnState
11-24 15:40:54.900  3141  4171 D BluetoothPan: onBluetoothStateChange on: false
11-24 15:40:54.901   926   943 D BluetoothA2dp: onBluetoothStateChange: up=false
11-24 15:40:54.901   926   943 D BluetoothHeadset: onBluetoothStateChange: up=false
11-24 15:40:54.901  3141  3156 D BluetoothMap: onBluetoothStateChange: up=false
11-24 15:40:54.901  3774  4026 D BluetoothHeadset: onBluetoothStateChange: up=false
11-24 15:40:54.902  3141  3153 D BluetoothPbap: onBluetoothStateChange: up=false
11-24 15:40:54.902  3141  4171 D BluetoothA2dp: onBluetoothStateChange: up=false
11-24 15:40:54.903   926   943 D BluetoothHeadset: onBluetoothStateChange: up=false
11-24 15:40:54.904  3141  3156 D BluetoothInputDevice: onBluetoothStateChange: up=false
11-24 15:40:54.908   926   943 D BluetoothHeadset: onBluetoothStateChange: up=false
11-24 15:40:54.908  3141  3153 D BluetoothHeadset: onBluetoothStateChange: up=false
11-24 15:40:54.909  4261  4296 D BluetoothAdapterState: Current state: BLE ON, message: 20
11-24 15:40:54.909  4261  4296 D BluetoothAdapterProperties: Setting state to 16
11-24 15:40:54.909  4261  4296 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
11-24 15:40:54.911  4261  4296 D BluetoothAdapterProperties: onBleDisable
11-24 15:40:54.911  4261  4296 I BluetoothAdapterState: Entering PendingCommandState
11-24 15:40:54.912  4261  4297 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
11-24 15:40:54.912  5519  5519 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-24 15:40:54.912  4261  4300 D BluetoothAdapterProperties: Scan Mode:20
11-24 15:40:54.912  5519  5519 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-24 15:40:54.912  5519  5519 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-24 15:40:54.912  5519  5519 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-24 15:40:54.912  5519  5519 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-24 15:40:54.912  5519  5519 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-24 15:40:54.912  5519  5519 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-24 15:40:54.912  5519  5519 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-24 15:40:54.912  5519  5519 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-24 15:40:54.912  5519  5519 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-24 15:40:54.913  5519  5519 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-24 15:40:54.913  5519  5519 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
11-24 15:40:54.914  4261  4424 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
11-24 15:40:54.914  4261  4424 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-24 15:40:54.914  5519  5519 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-24 15:40:54.915   507   920 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-24 15:40:54.936   507   920 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-24 15:40:54.937   507   920 D CommandListener: Clearing all IP addresses on wlan0
11-24 15:40:54.937   507   920 D TetherController: Setting IP forward enable = 0
11-24 15:40:54.938   926  2975 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
11-24 15:40:54.938  5590  5590 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm64
11-24 15:40:54.938   926  2975 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,11-24 15:40:54.941   926   943 D Tethering: MasterInitialState.processMessage what=3
,11-24 15:40:54.943  5519  5519 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-24 15:40:54.945  3947  3947 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
,11-24 15:40:54.947  5119  5119 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@1a457e9 and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
11-24 15:40:54.950  4859  4896 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
11-24 15:40:54.950  4859  4896 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
11-24 15:40:54.950  4859  4896 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,0,0,0
11-24 15:40:54.950  4859  4896 E SarControlService: no key has been found,reset the power
11-24 15:40:54.950  4859  4922 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
,11-24 15:40:54.950  4859  4922 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
11-24 15:40:54.950  4859  4922 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
11-24 15:40:54.951  4909  4909 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
11-24 15:40:54.951  4909  4909 D QcrilMsgTunnelSocket: [1002] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
11-24 15:40:54.952  4859  4922 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
11-24 15:40:54.952  4859  4922 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
11-24 15:40:54.952  4859  4922 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
11-24 15:40:54.953  4909  4909 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
11-24 15:40:54.953  4909  4909 D QcrilMsgTunnelSocket: [1003] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
11-24 15:40:54.956  4909  4926 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@92f9857 HexData = [00000000ea03000000000000ffffffff]
11-24 15:40:54.956  4909  4926 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-24 15:40:54.956  4909  4926 D QcrilMsgTunnelSocket: [1002] < OEM_HOOK_RAW [null]
11-24 15:40:54.957  4909  4909 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
11-24 15:40:54.957  4859  4869 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
,11-24 15:40:54.965  4909  4926 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@92f9857 HexData = [00000000eb03000000000000ffffffff]
,11-24 15:40:54.965  4909  4926 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-24 15:40:54.965  4909  4926 D QcrilMsgTunnelSocket: [1003] < OEM_HOOK_RAW [null]
11-24 15:40:54.966  4909  4909 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
11-24 15:40:54.966  4859  4870 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
,11-24 15:40:54.972  5590  5590 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,11-24 15:40:54.977   926   943 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@6dffc36:true
,11-24 15:40:54.978  3592  3592 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,11-24 15:40:54.987   507   920 E Netd    : netlink response contains error (No such file or directory)
11-24 15:40:54.987   507   920 D TetherController: Setting IP forward enable = 0
,11-24 15:40:54.988   926  2975 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,11-24 15:40:54.991   926  3803 I ActivityManager: Start proc 5621:com.google.android.apps.maps/u0a58 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,11-24 15:40:54.992   926  2973 D DhcpClient: doQuit
,11-24 15:40:54.993   926  2973 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
11-24 15:40:54.993   926  5295 D DhcpClient: onQuitting
,11-24 15:40:54.995  3477  3477 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
,11-24 15:40:54.999  5519  5519 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-24 15:40:54.999  5519  5519 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-24 15:40:54.999  5519  5519 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-24 15:40:54.999  5519  5519 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-24 15:40:54.999  5519  5519 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-24 15:40:54.999  5519  5519 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-24 15:40:54.999  5519  5519 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-24 15:40:54.999  5519  5519 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-24 15:40:54.999  5519  5519 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-24 15:40:54.999  5519  5519 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-24 15:40:55.000  5519  5519 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-24 15:40:55.000  5519  5519 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
,11-24 15:40:55.003  5590  5590 D LocalBluetoothProfileManager: Adding local MAP profile
11-24 15:40:55.007  5590  5590 D BluetoothMap: Create BluetoothMap proxy object
,11-24 15:40:55.016  5590  5590 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,11-24 15:40:55.022  3477  3477 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
,11-24 15:40:55.026  3477  3477 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,11-24 15:40:55.032  5590  5590 D DockEventReceiver: finishStartingService: stopping service
,11-24 15:40:55.039   926  3424 I ActivityManager: Killing 5119:com.google.android.music:main/u0a59 (adj 15): empty #17
,11-24 15:40:55.048  5621  5621 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm64
,11-24 15:40:55.060  3477  3477 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,11-24 15:40:55.081  3477  3477 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,11-24 15:40:55.120  4261  4300 I bt_hci  : shut_down
,11-24 15:40:55.124  4261  4304 D bt_hwcfg: hw_epilog_process
,11-24 15:40:55.124  4261  4304 I bt_vendor: low_power_mode_cb
,11-24 15:40:55.126  4261  4304 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,11-24 15:40:55.126  4261  4304 I bt_vendor: epilog_cb
11-24 15:40:55.126  4261  4304 I bt_hci  : epilog_finished_callback
,11-24 15:40:55.128  4261  4300 I bt_hci_h4: hal_close
,11-24 15:40:55.129  4261  4300 I bt_userial_vendor: device fd = 54 close
,11-24 15:40:55.186   926  2973 D wifi    : In wifi stop Hal
11-24 15:40:55.187   926  2973 D wifi    : halHandle = 0x7f6f9fbf80, mVM = 0x7f8a50d140, mCls = 0x100a12
11-24 15:40:55.187   926  3476 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
,11-24 15:40:55.187   926  3476 D WifiHAL : Got a signal to exit!!!
11-24 15:40:55.187   926  3476 I WifiHAL : Exit wifi_event_loop
,11-24 15:40:55.187   926  2973 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 0
11-24 15:40:55.187   926  2973 E WifiHAL : Event processing terminated
11-24 15:40:55.187   926  2973 D wifi    : In wifi cleaned up handler
,11-24 15:40:55.188   926  2973 I WifiHAL : Internal cleanup completed
11-24 15:40:55.188  4817  4817 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
11-24 15:40:55.189  3934  4209 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
11-24 15:40:55.190  5519  5519 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-24 15:40:55.210   926  3476 D wifi    : set interface wlan0 flags (DOWN)
,11-24 15:40:55.211   926  2973 D WifiNative-HAL: HAL event thread stopped successfully
,11-24 15:40:55.235  4261  4297 D bt_stack_manager: event_shut_down_stack finished.
,11-24 15:40:55.235  4261  4296 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,11-24 15:40:55.237  4261  4296 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
11-24 15:40:55.237  4261  4261 D BtGatt.DebugUtils: handleDebugAction() action=null
,11-24 15:40:55.237  4261  4261 D BtGatt.GattService: Received stop request...Stopping profile...
,11-24 15:40:55.237  4261  4261 D BtGatt.GattService: stop()
11-24 15:40:55.237  4261  4261 D BtGatt.AdvertiseManager: advertise clients cleared
11-24 15:40:55.239  4261  4261 V BluetoothAdapterState: isTurningOff()=false
11-24 15:40:55.239  4261  4261 V BluetoothAdapterState: isTurningOn()=false
11-24 15:40:55.239  4261  4261 V BluetoothAdapterState: isBleTurningOn()=false
11-24 15:40:55.239  4261  4261 V BluetoothAdapterState: isBleTurningOff()=true
,11-24 15:40:55.240  4261  4296 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
11-24 15:40:55.240  4261  4296 D BluetoothAdapterProperties: Setting state to 10
11-24 15:40:55.240  4261  4296 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
11-24 15:40:55.241   926   943 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
11-24 15:40:55.241  4261  4296 I BluetoothAdapterState: Entering OffState
,11-24 15:40:55.247  4261  4261 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,11-24 15:40:55.247  4261  4261 W BluetoothSdpJni: Cleaning up Bluetooth Health object
11-24 15:40:55.247  4261  4261 I BluetoothServiceJni: cleanupNative: return from cleanup
11-24 15:40:55.248  4261  4297 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,11-24 15:40:55.256  4261  4261 I art     : System.exit called, status: 0
,11-24 15:40:55.256  4261  4261 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,11-24 15:40:55.300   926  3791 I ActivityManager: Process com.android.bluetooth (pid 4261) has died
,11-24 15:40:55.306  5621  5621 D StrictMode: StrictMode policy violation; ~duration=167 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-24 15:40:55.306  5621  5621 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-24 15:40:55.306  5621  5621 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
11-24 15:40:55.306  5621  5621 D StrictMode: 	at java.io.File.doAccess(File.java:281)
11-24 15:40:55.306  5621  5621 D StrictMode: 	at java.io.File.exists(File.java:361)
11-24 15:40:55.306  5621  5621 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
11-24 15:40:55.306  5621  5621 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
11-24 15:40:55.306  5621  5621 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
11-24 15:40:55.306  5621  5621 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
11-24 15:40:55.306  5621  5621 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
11-24 15:40:55.306  5621  5621 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
11-24 15:40:55.306  5621  5621 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-24 15:40:55.306  5621  5621 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-24 15:40:55.306  5621  5621 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-24 15:40:55.306  5621  5621 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-24 15:40:55.306  5621  5621 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-24 15:40:55.306  5621  5621 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-24 15:40:55.306  5621  5621 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-24 15:40:55.306  5621  5621 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-24 15:40:55.306  5621  5621 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-24 15:40:55.306  5621  5621 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-24 15:40:55.306  5621  5621 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-24 15:40:55.306  5621  5621 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-24 15:40:55.306  5621  5621 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-24 15:40:55.306  5621  5621 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-24 15:40:55.306  5621  5621 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-24 15:40:55.306  5621  5621 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,11-24 15:40:55.306  5621  5621 D StrictMode: StrictMode policy violation; ~duration=167 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-24 15:40:55.306  5621  5621 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-24 15:40:55.306  5621  5621 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
11-24 15:40:55.306  5621  5621 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
11-24 15:40:55.306  5621  5621 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
11-24 15:40:55.306  5621  5621 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
11-24 15:40:55.306  5621  5621 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
11-24 15:40:55.306  5621  5621 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
11-24 15:40:55.306  5621  5621 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
11-24 15:40:55.306  5621  5621 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-24 15:40:55.306  5621  5621 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-24 15:40:55.306  5621  5621 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-24 15:40:55.306  5621  5621 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-24 15:40:55.306  5621  5621 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-24 15:40:55.306  5621  5621 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-24 15:40:55.306  5621  5621 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-24 15:40:55.306  5621  5621 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-24 15:40:55.306  5621  5621 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-24 15:40:55.306  5621  5621 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-24 15:40:55.306  5621  5621 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-24 15:40:55.306  5621  5621 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-24 15:40:55.306  5621  5621 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-24 15:40:55.306  5621  5621 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-24 15:40:55.306  5621  5621 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-24 15:40:55.306  5621  5621 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-24 15:40:55.307  5621  5621 D StrictMode: StrictMode policy violation; ~duration=166 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-24 15:40:55.307  5621  5621 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-24 15:40:55.307  5621  5621 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
11-24 15:40:55.307  5621  5621 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
11-24 15:40:55.307  5621  5621 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
11-24 15:40:55.307  5621  5621 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
11-24 15:40:55.307  5621  5621 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
11-24 15:40:55.307  5621  5621 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
11-24 15:40:55.307  5621  5621 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
11-24 15:40:55.307  5621  5621 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-24 15:40:55.307  5621  5621 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-24 15:40:55.307  5621  5621 D StrictMode: 	at com.google.android.apps.gmm.base.ap,p.a.a(PG:244)
11-24 15:40:55.307  5621  5621 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-24 15:40:55.307  5621  5621 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-24 15:40:55.307  5621  5621 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-24 15:40:55.307  5621  5621 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-24 15:40:55.307  5621  5621 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-24 15:40:55.307  5621  5621 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-24 15:40:55.307  5621  5621 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-24 15:40:55.307  5621  5621 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-24 15:40:55.307  5621  5621 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-24 15:40:55.307  5621  5621 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-24 15:40:55.307  5621  5621 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-24 15:40:55.307  5621  5621 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-24 15:40:55.307  5621  5621 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-24 15:40:55.307  5621  5621 D StrictMode: StrictMode policy violation; ~duration=166 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-24 15:40:55.307  5621  5621 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-24 15:40:55.307  5621  5621 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
11-24 15:40:55.307  5621  5621 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
11-24 15:40:55.307  5621  5621 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
11-24 15:40:55.307  5621  5621 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
11-24 15:40:55.307  5621  5621 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
11-24 15:40:55.307  5621  5621 D StrictMode: 	at com.google.r.k.d(PG:1187)
11-24 15:40:55.307  5621  5621 D StrictMode: 	at com.google.r.k.a(PG:2107)
11-24 15:40:55.307  5621  5621 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
11-24 15:40:55.307  5621  5621 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
11-24 15:40:55.307  5621  5621 D StrictMode: 	at com.google.r.v.a(PG:1161)
11-24 15:40:55.307  5621  5621 D StrictMode: 	at com.google.r.y.a(PG:2188)
11-24 15:40:55.307  5621  5621 D StrictMode: 	at com.google.r.e.b(PG:170)
11-24 15:40:55.307  5621  5621 D StrictMode: 	at com.google.r.e.b(PG:15188)
11-24 15:40:55.307  5621  5621 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
11-24 15:40:55.307  5621  5621 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
11-24 15:40:55.307  5621  5621 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-24 15:40:55.307  5621  5621 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-24 15:40:55.307  5621  5621 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-24 15:40:55.307  5621  5621 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-24 15:40:55.307  5621  5621 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-24 15:40:55.307  5621  5621 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-24 15:40:55.307  5621  5621 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-24 15:40:55.307  5621  5621 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-24 15:40:55.307  5621  5621 D StrictMode: 	at android.app.ActivityThread.-wrap1(Activit,yThread.java)
11-24 15:40:55.307  5621  5621 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-24 15:40:55.307  5621  5621 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-24 15:40:55.307  5621  5621 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-24 15:40:55.307  5621  5621 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-24 15:40:55.307  5621  5621 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-24 15:40:55.307  5621  5621 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-24 15:40:55.307  5621  5621 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-24 15:40:55.307  5621  5621 D StrictMode: StrictMode policy violation; ~duration=163 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-24 15:40:55.307  5621  5621 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-24 15:40:55.307  5621  5621 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
11-24 15:40:55.307  5621  5621 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
11-24 15:40:55.307  5621  5621 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
11-24 15:40:55.307  5621  5621 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
11-24 15:40:55.307  5621  5621 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
11-24 15:40:55.307  5621  5621 D StrictMode: 	at com.google.r.k.d(PG:1187)
11-24 15:40:55.307  5621  5621 D StrictMode: 	at com.google.r.k.c(PG:18147)
11-24 15:40:55.307  5621  5621 D StrictMode: 	at com.google.r.k.d(PG:583)
11-24 15:40:55.307  5621  5621 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
11-24 15:40:55.307  5621  5621 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
11-24 15:40:55.307  5621  5621 D StrictMode: 	at com.google.r.v.a(PG:1161)
11-24 15:40:55.307  5621  5621 D StrictMode: 	at com.google.r.y.a(PG:2188)
11-24 15:40:55.307  5621  5621 D StrictMode: 	at com.google.r.e.b(PG:170)
11-24 15:40:55.307  5621  5621 D StrictMode: 	at com.google.r.e.b(PG:15188)
11-24 15:40:55.307  5621  5621 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
11-24 15:40:55.307  5621  5621 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
11-24 15:40:55.307  5621  5621 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-24 15:40:55.307  5621  5621 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-24 15:40:55.307  5621  5621 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-24 15:40:55.307  5621  5621 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-24 15:40:55.307  5621  5621 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-24 15:40:55.307  5621  5621 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-24 15:40:55.307  5621  5621 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-24 15:40:55.307  5621  5621 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-24 15:40:55.307  5621  5621 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-24 15:40:55.307  5621  5621 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-24 15:40:55.307  5621  5621 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-24 15:40:55.307  5621  5621 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-24 15:40:55.307  5621  5621 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-24 15:40:55.307  5621  5621 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-24 15:40:55.307  5621  5621 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-24 15:40:55.307  5621  5621 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-24 15:40:55.307  5621  5621 D StrictMode: StrictMode policy violation; ~duration=134 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-24 15:40:55.307  5621  5621 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-24 15:40:55.307  5621  5621 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
11-24 15:40:55.307  5621  5621 D StrictMode: 	at java.io.File.doAccess(File.java:281)
11-24 15:40:55.307  5621  5621 D StrictMode: 	at java.io.File.exists(File.java:361)
11-24 15:40:55.307  5621  5621 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
11-24 15:40:55.307  5621  5621 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
11-24 15:40:55.307  5621  5621 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
11-24 15:40:55.307  5621  5621 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
11-24 15:40:55.307  5621  5621 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
11-24 15:40:55.307  5621  5621 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-24 15:40:55.307  5621  5621 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-24 15:40:55.307  5621  5621 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-24 15:40:55.307  5621  5621 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-24 15:40:55.307  5621  5621 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-24 15:40:55.307  5621  5621 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-24 15:40:55.307  5621  5621 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-24 15:40:55.307  5621  5621 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-24 15:40:55.307  5621  5621 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-24 15:40:55.307  5621  5621 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-24 15:40:55.307  5621  5621 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-24 15:40:55.307  5621  5621 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-24 15:40:55.307  5621  5621 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-24 15:40:55.307  5621  5621 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-24 15:40:55.307  5621  5621 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-24 15:40:55.307  5621  5621 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-24 15:40:55.307  5621  5621 D StrictMode: StrictMode policy violation; ~duration=133 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-24 15:40:55.307  5621  5621 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-24 15:40:55.307  5621  5621 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
11-24 15:40:55.307  5621  5621 D StrictMode: 	at java.io.File.doAccess(File.java:281)
11-24 15:40:55.307  5621  5621 D StrictMode: 	at java.io.File.exists(File.java:361)
11-24 15:40:55.307  5621  5621 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
11-24 15:40:55.307  5621  5621 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-24 15:40:55.307  5621  5621 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-24 15:40:55.307  5621  5621 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-24 15:40:55.307  5621  5621 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-24 15:40:55.307  5621  5621 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-24 15:40:55.307  5621  5621 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-24 15:40:55.307  5621  5621 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-24 15:40:55.307  5621  5621 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-24 15:40:55.307  5621  5621 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-24 15:40:55.307  5621  5621 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-24 15:40:55.307  5621  5621 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-24 15:40:55.307  5621  5621 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-24 15:40:55.307  5621  5621 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-24 15:40:55.307  5621  5621 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-24 15:40:55.307  5621  5621 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-24 15:40:55.307  5621  5621 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-24 15:40:55.307  5621  5621 D StrictMode: StrictMode policy violation; ~duration=133 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-24 15:40:55.307  5621  5621 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-24 15:40:55.307  5621  5621 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
11-24 15:40:55.307  5621  5621 D StrictMode: 	at java.io.File.lastModified(File.java:569)
11-24 15:40:55.307  5621  5621 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
11-24 15:40:55.307  5621  5621 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-24 15:40:55.307  5621  5621 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-24 15:40:55.307  5621  5621 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-24 15:40:55.307  5621  5621 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-24 15:40:55.307  5621  5621 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-24 15:40:55.307  5621  5621 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-24 15:40:55.307  5621  5621 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-24 15:40:55.307  5621  5621 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-24 15:40:55.307  5621  5621 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-24 15:40:55.307  5621  5621 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-24 15:40:55.307  5621  5621 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-24 15:40:55.307  5621  5621 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-24 15:40:55.307  5621  5621 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-24 15:40:55.307  5621  5621 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-24 15:40:55.307  5621  5621 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-24 15:40:55.307  5621  5621 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-24 15:40:55.319  5590  5590 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
11-24 15:40:55.332   926   936 I ActivityManager: Start proc 5655:com.android.bluetooth/1002 for broadcast com.android.bluetooth/.pbap.BluetoothPbapReceiver
11-24 15:40:55.333  5590  5590 D DockEventReceiver: finishStartingService: stopping service
11-24 15:40:55.335   926   937 I ActivityManager: Killing 5322:com.android.sdm.plugins.sprintdm/1001 (adj 15): empty #17
,11-24 15:40:55.413   926   943 D Tethering: InitialState.processMessage what=4
,11-24 15:40:55.416   926   943 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,11-24 15:40:55.428  5655  5655 D AdapterServiceConfig: Adding HeadsetService
,11-24 15:40:55.428  5655  5655 D AdapterServiceConfig: Adding A2dpService
11-24 15:40:55.428  5655  5655 D AdapterServiceConfig: Adding HidService
11-24 15:40:55.428  5655  5655 D AdapterServiceConfig: Adding HealthService
,11-24 15:40:55.428  5655  5655 D AdapterServiceConfig: Adding PanService
11-24 15:40:55.429  5655  5655 D AdapterServiceConfig: Adding GattService
11-24 15:40:55.429  5655  5655 D AdapterServiceConfig: Adding BluetoothMapService
11-24 15:40:55.429  5655  5655 D AdapterServiceConfig: Adding SapService
,11-24 15:40:55.431   926  4746 I ActivityManager: Killing 5335:com.android.chrome/u0a39 (adj 15): empty #17
,11-24 15:40:55.459  3592  3592 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,11-24 15:40:55.468  4073  4073 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,11-24 15:40:55.471  4073  4073 D SystemUpdateService: onCreate
,11-24 15:40:55.476  4073  4073 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,11-24 15:40:55.489  4073  4073 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,11-24 15:40:55.493  4073  5319 I iu.UploadsManager: num queued entries: 0
,11-24 15:40:55.493  4073  5319 I iu.UploadsManager: num updated entries: 0
11-24 15:40:55.493  4073  5319 I iu.SyncManager: NEXT; no task
,11-24 15:40:55.496  4073  4073 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,11-24 15:40:55.498  4073  4073 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,11-24 15:40:55.499  4073  5667 I SystemUpdateService: active receiver: enabled
,11-24 15:40:55.510   926  3803 I ActivityManager: Start proc 5669:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,11-24 15:40:55.513  4073  5667 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,11-24 15:40:55.515  4073  5667 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,11-24 15:40:55.515  4073  5667 I SystemUpdateService: now status is 0 (complete)
11-24 15:40:55.515  4073  5667 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
11-24 15:40:55.515  4073  5667 I SystemUpdateService: file has been verified
,11-24 15:40:55.515  4073  5667 I SystemUpdateService: OTA package size = 21989297
,11-24 15:40:55.528  4073  5667 I SystemUpdateService: showing system update notification
,11-24 15:40:55.546  5669  5669 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm64
,11-24 15:40:55.549  5669  5669 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,11-24 15:40:55.557  5669  5669 D SprintDMHelper: simOperator: 
,11-24 15:40:55.558  5669  5669 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,11-24 15:40:55.565   926   926 V NotificationService: pkg=com.google.android.gms canInterrupt=false intercept=true
,11-24 15:40:55.570   926   937 I ActivityManager: Start proc 5681:com.android.chrome/u0a39 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
,11-24 15:40:55.580  4073  4073 D SystemUpdateService: onDestroy
,11-24 15:40:55.582   926  3155 I ActivityManager: Killing 5352:com.google.android.apps.photos/u0a62 (adj 15): empty #17
,11-24 15:40:55.677  4817  5695 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,11-24 15:40:55.683   926  3791 I ActivityManager: Start proc 5696:com.google.android.apps.photos/u0a62 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
,11-24 15:40:55.686   926   936 I ActivityManager: Killing 3873:com.android.providers.calendar/u0a1 (adj 15): empty #17
,11-24 15:40:55.734  5696  5696 W System  : ClassLoader referenced unknown path: /system/app/Photos/lib/arm
,11-24 15:40:55.796  5621  5645 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,11-24 15:40:55.885   926   943 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@b21a504:true
,11-24 15:40:55.929   926  3155 I ActivityManager: Killing 5381:com.android.defcontainer/u0a7 (adj 15): empty #17
,11-24 15:40:55.969   926   937 I ActivityManager: Start proc 5710:com.google.android.apps.gcs/u0a11 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,11-24 15:40:55.996  5710  5710 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm64
,11-24 15:40:56.003   926  3791 I ActivityManager: Killing 3408:android.process.acore/u0a2 (adj 15): empty #17
,11-24 15:40:58.800   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 15:40:59.801   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 15:40:59.832   926  4813 D WifiService: setWifiEnabled: true pid=5519, uid=10077
,11-24 15:40:59.833   926  4813 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-24 15:40:59.844   507   920 D SoftapController: Softap fwReload - Ok
,11-24 15:40:59.849   507   920 D CommandListener: Setting iface cfg
11-24 15:40:59.849   507   920 D CommandListener: Trying to bring down wlan0
,11-24 15:40:59.851   507   920 D CommandListener: Clearing all IP addresses on wlan0
,11-24 15:40:59.856   926  2973 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,11-24 15:41:00.426   926  2973 D wifi    : set interface wlan0 flags (UP)
,11-24 15:41:00.429   926  2973 I WifiHAL : Initializing wifi
11-24 15:41:00.429   926  2973 I WifiHAL : Creating socket
,11-24 15:41:00.430   926   943 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,11-24 15:41:00.434   926  2973 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
,11-24 15:41:00.435   926  2973 D wifi    : Did set static halHandle = 0x7f6f9fbf80
,11-24 15:41:00.435   926  2973 D wifi    : halHandle = 0x7f6f9fbf80, mVM = 0x7f8a50d140, mCls = 0x2018ea
11-24 15:41:00.435   926  2973 D wifi    : array field set
11-24 15:41:00.435   926  2973 I WifiNative-HAL: interface[0] = wlan0
11-24 15:41:00.436   926  5728 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=547333586816
11-24 15:41:00.437   926  5728 D wifi    : waitForHalEvents called, vm = 0x7f8a50d140, obj = 0x2018ea, env = 0x7f72cdf500
,11-24 15:41:00.493  5729  5729 I wpa_supplicant: Successfully initialized wpa_supplicant
,11-24 15:41:00.537   926  2973 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,11-24 15:41:00.543  5519  5519 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-24 15:41:00.551  5729  5729 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,11-24 15:41:00.583  5729  5729 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,11-24 15:41:00.583  5729  5729 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,11-24 15:41:00.600   926  2973 D WifiConfigStore: Loading config and enabling all networks 
,11-24 15:41:00.601  5519  5519 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,11-24 15:41:00.601  5519  5519 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-24 15:41:00.601  5519  5519 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-24 15:41:00.601  5519  5519 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-24 15:41:00.601  5519  5519 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-24 15:41:00.601  5519  5519 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-24 15:41:00.601  5519  5519 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-24 15:41:00.601  5519  5519 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-24 15:41:00.601  5519  5519 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-24 15:41:00.601  5519  5519 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-24 15:41:00.601  5519  5519 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-24 15:41:00.602  5519  5519 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
,11-24 15:41:00.630   926  2973 D WifiConfigStore: loaded 0 passpoint configs
,11-24 15:41:00.631   926  2973 W WifiConfigStore: Upgrading network 4 to android.uid.system:1000
,11-24 15:41:00.632   926  2973 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,11-24 15:41:00.632   926  2973 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,11-24 15:41:00.633   926  2973 W WifiConfigStore: Upgrading network 3 to android.uid.system:1000
,11-24 15:41:00.633   926  2973 W WifiConfigStore: Upgrading network 2 to android.uid.system:1000
,11-24 15:41:00.634   926  2973 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,11-24 15:41:00.635   926  2973 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 5
11-24 15:41:00.635   926  2973 E WifiConfigStore: found sortedWifiConfigurations : "AndroidAP"WPA_PSK
11-24 15:41:00.635   926  2973 E WifiConfigStore: found sortedWifiConfigurations : "AndroidHotspot2346"WPA_PSK
11-24 15:41:00.635   926  2973 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
11-24 15:41:00.635   926  2973 E WifiConfigStore: found sortedWifiConfigurations : "Thali_internal"WPA_PSK
,11-24 15:41:00.635   926  2973 E WifiConfigStore: found sortedWifiConfigurations : "MC"WPA_PSK
,11-24 15:41:00.638   926  2973 D WifiNative-HAL: Setting external_sim to 1
,11-24 15:41:00.639  4817  4817 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
11-24 15:41:00.639   926  2973 D wifi    : setting dfs flag to true, 0x7f727a05c0
,11-24 15:41:00.639   926  2973 D WifiStateMachine: Setting OUI to DA-A1-19
11-24 15:41:00.639   926  2973 D wifi    : setting scan oui 0x7f727a05c0
11-24 15:41:00.639   926  2973 D WifiHAL : Sending mac address OUI
,11-24 15:41:00.643   926  2973 E native  : do suspend false
,11-24 15:41:00.650   926  2973 D wifi    : android_net_wifi_setLinkLayerStats: 1
11-24 15:41:00.650   926   926 D RttService: SCAN_AVAILABLE : 3
11-24 15:41:00.650   926  3083 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
11-24 15:41:00.650   507   920 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,11-24 15:41:00.651   507   920 D CommandListener: Setting iface cfg
,11-24 15:41:00.655   926  2972 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '125 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 125 Failed to set address (No such device)'
,11-24 15:41:00.655   926  2972 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,11-24 15:41:00.665   926  2972 D WifiNative-HAL: p2pGetDeviceAddress
,11-24 15:41:00.670   926   941 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=119978 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=15 mControllerEnergyUsed=57 }
,11-24 15:41:00.670   926  2972 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:70
,11-24 15:41:00.801   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 15:41:01.802   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 15:41:02.803   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 15:41:03.734  5729  5729 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-24 15:41:03.742  5729  5729 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-24 15:41:03.748  5729  5729 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-24 15:41:03.773   926  2973 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
11-24 15:41:03.774   926  2973 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3
11-24 15:41:03.775   926  2973 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-24 15:41:03.785   926  2973 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=0
,11-24 15:41:03.804   535   535 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,11-24 15:41:03.819   926  2973 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=0
,11-24 15:41:03.825  5729  5729 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,11-24 15:41:04.284  5729  5729 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,11-24 15:41:04.319  5729  5729 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,11-24 15:41:04.320  5729  5729 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
11-24 15:41:04.329   926  2973 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,11-24 15:41:04.330   926  2973 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
11-24 15:41:04.330   926  2975 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,11-24 15:41:04.346   926  2973 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-24 15:41:04.358   507   920 D CommandListener: Setting iface cfg
,11-24 15:41:04.363   926  2973 D WifiStateMachine: Start Dhcp Watchdog 2
,11-24 15:41:04.368   926  5735 D DhcpClient: Receive thread started
,11-24 15:41:04.373   926  2975 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-24 15:41:04.373   926  2973 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
11-24 15:41:04.373   926  2975 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
,11-24 15:41:04.453   926  2973 E native  : do suspend false
,11-24 15:41:04.464   926  5734 D DhcpClient: Broadcasting DHCPDISCOVER
,11-24 15:41:04.476   926  5735 D DhcpClient: Received packet: 60:83:34:25:d7:70 OFFER, ip /192.168.1.109, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172716, domain null
,11-24 15:41:04.476   926  5734 D DhcpClient: Got pending lease: IP address 192.168.1.109/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172716 seconds
,11-24 15:41:04.478   926  5734 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.109 serverid=192.168.1.1
,11-24 15:41:04.491   926  5735 D DhcpClient: Received packet: 60:83:34:25:d7:70 ACK: your new IP /192.168.1.109, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,11-24 15:41:04.492   926  5734 D DhcpClient: Confirmed lease: IP address 192.168.1.109/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,11-24 15:41:04.494   507   920 D CommandListener: Setting iface cfg
,11-24 15:41:04.498   926  2973 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,11-24 15:41:04.501   926  5734 D DhcpClient: Scheduling renewal in 86399s
,11-24 15:41:04.509   926  2973 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
11-24 15:41:04.509   926  2973 D WifiConfigStore: No blacklist allowed without epno enabled
11-24 15:41:04.510   926  2975 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
11-24 15:41:04.516   926  2975 D ConnectivityService: Adding iface wlan0 to network 101
11-24 15:41:04.516   926  2973 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,11-24 15:41:04.555   926  2975 E ConnectivityService: Unexpected mtu value: 0, wlan0
,11-24 15:41:04.555   926  2975 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
11-24 15:41:04.557   926  2975 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
11-24 15:41:04.558   926  2975 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
11-24 15:41:04.560   926  2975 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,11-24 15:41:04.567   926  2975 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-24 15:41:04.571   926  2975 D ConnectivityService: scheduleUnvalidatedPrompt 101
,11-24 15:41:04.571   926  2975 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
11-24 15:41:04.571   926  2975 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
11-24 15:41:04.572   926  2973 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
11-24 15:41:04.572   926  2975 D ConnectivityService:    accepting network in place of null
11-24 15:41:04.572   926  2973 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
11-24 15:41:04.572   926  2975 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d770/64,192.168.1.109/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -49]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,11-24 15:41:04.583   926  5733 D NetlinkSocketObserver: NeighborEvent{elapsedMs=123892, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,11-24 15:41:04.596   507   920 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-24 15:41:04.617   507   920 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-24 15:41:04.620   926  2975 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,11-24 15:41:04.621  3740  3887 W QCNEJ   : |CORE| network available: 101
,11-24 15:41:04.621   926  2975 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
11-24 15:41:04.622   926  2975 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
11-24 15:41:04.624   926   943 D Tethering: MasterInitialState.processMessage what=3
11-24 15:41:04.625  3740  3887 W QCNEJ   : |CORE| onAvailable: bind the process to WIFI
,11-24 15:41:04.628  3740  3887 W QCNEJ   : |CORE| newLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d770/64,192.168.1.109/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}
,11-24 15:41:04.628  3740  3887 W QCNEJ   : |CORE| curLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d770/64,192.168.1.109/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,11-24 15:41:04.630  5519  5519 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-24 15:41:04.630  5519  5519 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-24 15:41:04.630  5519  5519 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-24 15:41:04.630  5519  5519 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-24 15:41:04.630  5519  5519 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-24 15:41:04.630  5519  5519 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-24 15:41:04.630  5519  5519 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-24 15:41:04.630  5519  5519 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-24 15:41:04.630  5519  5519 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-24 15:41:04.630  5519  5519 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
11-24 15:41:04.630  5519  5519 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-24 15:41:04.630  5519  5519 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
11-24 15:41:04.638  4859  4896 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
,11-24 15:41:04.639  4859  4896 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
11-24 15:41:04.639  4859  4896 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,1,0,0
,11-24 15:41:04.639  4859  4896 E SarControlService: no key has been found,reset the power
,11-24 15:41:04.639  4859  4922 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
11-24 15:41:04.639  4859  4922 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
11-24 15:41:04.639  4859  4922 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
11-24 15:41:04.640  4909  4909 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
11-24 15:41:04.640  4909  4909 D QcrilMsgTunnelSocket: [1004] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
11-24 15:41:04.641  3947  3947 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
,11-24 15:41:04.642  4859  4922 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
,11-24 15:41:04.643  4859  4922 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
11-24 15:41:04.643  4859  4922 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
11-24 15:41:04.646  4909  4909 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
11-24 15:41:04.646  4909  4909 D QcrilMsgTunnelSocket: [1005] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
11-24 15:41:04.648  4073  4073 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
11-24 15:41:04.649  4909  4926 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@92f9857 HexData = [00000000ec03000000000000ffffffff]
11-24 15:41:04.649  4909  4926 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-24 15:41:04.649  4909  4926 D QcrilMsgTunnelSocket: [1004] < OEM_HOOK_RAW [null]
11-24 15:41:04.652  4909  4909 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
11-24 15:41:04.652  4859  4869 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
,11-24 15:41:04.653  4073  4073 D SystemUpdateService: onCreate
,11-24 15:41:04.658  4909  4926 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@92f9857 HexData = [00000000ed03000000000000ffffffff]
,11-24 15:41:04.658  4909  4926 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-24 15:41:04.658  4909  4926 D QcrilMsgTunnelSocket: [1005] < OEM_HOOK_RAW [null]
,11-24 15:41:04.658  4909  4909 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
11-24 15:41:04.659  4859  4870 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
11-24 15:41:04.659  4073  4073 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,11-24 15:41:04.671   926  5732 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=172.217.22.110,2a00:1450:4001:81d::200e
,11-24 15:41:04.675  4073  4073 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,11-24 15:41:04.677  4073  5319 I iu.UploadsManager: num queued entries: 0
11-24 15:41:04.677  4073  5319 I iu.UploadsManager: num updated entries: 0
,11-24 15:41:04.687  4073  5747 I SystemUpdateService: active receiver: enabled
,11-24 15:41:04.689  4073  5319 I iu.SyncManager: NEXT; no task
,11-24 15:41:04.692  4073  4073 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,11-24 15:41:04.694  4073  4073 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,11-24 15:41:04.696  5669  5669 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,11-24 15:41:04.702  5669  5669 D SprintDMHelper: simOperator: 
11-24 15:41:04.702  5669  5669 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,11-24 15:41:04.714  4073  5747 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,11-24 15:41:04.734  4073  5747 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,11-24 15:41:04.735  4073  5747 I SystemUpdateService: now status is 0 (complete)
11-24 15:41:04.735  4073  5747 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
11-24 15:41:04.735  4073  5747 I SystemUpdateService: file has been verified
11-24 15:41:04.735  4073  5747 I SystemUpdateService: OTA package size = 21989297
,11-24 15:41:04.738   926  5732 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Thu, 24 Nov 2016 14:41:04 GMT], X-Android-Received-Millis=[1479998464737], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1479998464706]}
,11-24 15:41:04.739   926  2975 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
11-24 15:41:04.739   926  2975 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation  passed
11-24 15:41:04.739   926  2975 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
11-24 15:41:04.740   926  2975 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,11-24 15:41:04.748  4073  5747 I SystemUpdateService: showing system update notification
,11-24 15:41:04.754   926   926 V NotificationService: pkg=com.google.android.gms canInterrupt=false intercept=true
,11-24 15:41:04.757  4073  4073 D SystemUpdateService: onDestroy
,11-24 15:41:04.837  4817  5752 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,11-24 15:41:04.841   926  4746 D WifiService: setWifiEnabled: false pid=5519, uid=10077
,11-24 15:41:04.841   926  4746 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-24 15:41:04.843   926  2973 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,11-24 15:41:04.843   926  2973 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
,11-24 15:41:04.843   926  2973 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
11-24 15:41:04.843   926  2973 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-24 15:41:04.854   926  5734 D DhcpClient: Clearing IP address
,11-24 15:41:04.854   507   920 D CommandListener: Clearing all IP addresses on wlan0
,11-24 15:41:04.857   507   920 D CommandListener: Setting iface cfg
,11-24 15:41:04.859  3592  5757 V NativeCrypto: Read error: ssl=0x7f7fa2ea80: I/O error during system call, Connection timed out
11-24 15:41:04.859  3592  5757 V NativeCrypto: SSL shutdown failed: ssl=0x7f7fa2ea80: I/O error during system call, Broken pipe
,11-24 15:41:04.865   926  4746 D ConnectivityService: reportNetworkConnectivity(101, false) by 10012
11-24 15:41:04.865   926  5732 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Forcing reevaluation for UID 10012
11-24 15:41:04.866   926  5732 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=172.217.22.110,2a00:1450:4001:81d::200e
,11-24 15:41:04.867   926  2975 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
,11-24 15:41:04.867   926  2975 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 3
11-24 15:41:04.873   533   533 E Parcel  : Reading a NULL string not supported here.
11-24 15:41:04.875   926   926 D RttService: SCAN_AVAILABLE : 1
11-24 15:41:04.876   926  3083 D RttService: EnabledState got{ when=-1ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
11-24 15:41:04.876   926  5732 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Probably not a portal: exception java.net.ConnectException: failed to connect to connectivitycheck.gstatic.com/2a00:1450:4001:81d::200e (port 80) after 10000ms: connect failed: ENETUNREACH (Network is unreachable)
11-24 15:41:04.877   926  2973 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,11-24 15:41:04.879   926  5735 D DhcpClient: Receive thread stopped
,11-24 15:41:04.880   926  2975 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
11-24 15:41:04.880   926  2973 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
11-24 15:41:04.882  3740  3887 W QCNEJ   : |CORE| network lost: 101
11-24 15:41:04.882  3740  3887 W QCNEJ   : |CORE| onLost: unbind the process to WIFI
,11-24 15:41:04.900   507   920 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-24 15:41:04.918   507   920 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
11-24 15:41:04.919   507   920 D CommandListener: Clearing all IP addresses on wlan0
,11-24 15:41:04.919   926  2975 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,11-24 15:41:04.920   926  2975 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,11-24 15:41:04.921   926   943 D Tethering: MasterInitialState.processMessage what=3
,11-24 15:41:04.924  5519  5519 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-24 15:41:04.924  5519  5519 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-24 15:41:04.924  5519  5519 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-24 15:41:04.924  5519  5519 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-24 15:41:04.924  5519  5519 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-24 15:41:04.924  5519  5519 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-24 15:41:04.924  5519  5519 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-24 15:41:04.924  5519  5519 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-24 15:41:04.924  5519  5519 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-24 15:41:04.924  5519  5519 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-24 15:41:04.924  5519  5519 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-24 15:41:04.924  5519  5519 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
11-24 15:41:04.924   926  2973 D DhcpClient: doQuit
,11-24 15:41:04.925   926  2973 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
11-24 15:41:04.925   926  5734 D DhcpClient: onQuitting
11-24 15:41:04.926  5729  5729 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
11-24 15:41:04.926  3947  3947 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
,11-24 15:41:04.931  5519  5519 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-24 15:41:04.931  5519  5519 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-24 15:41:04.931  5519  5519 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-24 15:41:04.931  5519  5519 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-24 15:41:04.931  5519  5519 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-24 15:41:04.931  5519  5519 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-24 15:41:04.931  5519  5519 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-24 15:41:04.931  5519  5519 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-24 15:41:04.931  5519  5519 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-24 15:41:04.931  5519  5519 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-24 15:41:04.931  5519  5519 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-24 15:41:04.931  5519  5519 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
11-24 15:41:04.934  4073  4073 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
11-24 15:41:04.936  5729  5729 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
11-24 15:41:04.937  4859  4896 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
,11-24 15:41:04.937  4859  4896 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
11-24 15:41:04.937  4859  4896 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,0,0,0
11-24 15:41:04.938  4859  4896 E SarControlService: no key has been found,reset the power
11-24 15:41:04.938  4859  4922 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
11-24 15:41:04.938  4859  4922 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
11-24 15:41:04.938  4859  4922 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
11-24 15:41:04.939  5729  5729 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
11-24 15:41:04.939  4909  4909 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
11-24 15:41:04.939  4909  4909 D QcrilMsgTunnelSocket: [1006] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
,11-24 15:41:04.940  4859  4922 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
11-24 15:41:04.941  4859  4922 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
11-24 15:41:04.941  4859  4922 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
,11-24 15:41:04.941  4909  4909 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
11-24 15:41:04.942  4909  4909 D QcrilMsgTunnelSocket: [1007] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
11-24 15:41:04.942  4073  4073 D SystemUpdateService: onCreate
11-24 15:41:04.946  4909  4926 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@92f9857 HexData = [00000000ee03000000000000ffffffff]
11-24 15:41:04.946  4909  4926 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-24 15:41:04.946  4909  4926 D QcrilMsgTunnelSocket: [1006] < OEM_HOOK_RAW [null]
11-24 15:41:04.946  4909  4909 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
11-24 15:41:04.946  4859  4870 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
11-24 15:41:04.947  4073  4073 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
11-24 15:41:04.949  4909  4926 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@92f9857 HexData = [00000000ef03000000000000ffffffff]
11-24 15:41:04.949  4909  4926 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-24 15:41:04.949  4909  4926 D QcrilMsgTunnelSocket: [1007] < OEM_HOOK_RAW [null]
11-24 15:41:04.950  4909  4909 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
11-24 15:41:04.950  4859  4869 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
,11-24 15:41:04.955  4073  4073 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
11-24 15:41:04.960  4073  5319 I iu.UploadsManager: num queued entries: 0
11-24 15:41:04.961  4073  5319 I iu.UploadsManager: num updated entries: 0
,11-24 15:41:04.963  4073  4073 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
11-24 15:41:04.964  5729  5729 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
11-24 15:41:04.965  4073  4073 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,11-24 15:41:04.967  5669  5669 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,11-24 15:41:04.971  5669  5669 D SprintDMHelper: simOperator: 
,11-24 15:41:04.971  5669  5669 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,11-24 15:41:04.973  4073  5770 I SystemUpdateService: active receiver: enabled
11-24 15:41:04.974   507   920 E Netd    : netlink response contains error (No such file or directory)
11-24 15:41:04.975  5729  5729 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,11-24 15:41:04.982   926  2975 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
11-24 15:41:04.982   926  2975 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,11-24 15:41:04.983  4817  5774 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,11-24 15:41:04.985  4073  5319 I iu.SyncManager: NEXT; no task
,11-24 15:41:04.992  4073  5770 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,11-24 15:41:04.997  4073  5770 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,11-24 15:41:04.997  4073  5770 I SystemUpdateService: now status is 0 (complete)
11-24 15:41:04.997  4073  5770 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
11-24 15:41:04.997  4073  5770 I SystemUpdateService: file has been verified
11-24 15:41:04.997  4073  5770 I SystemUpdateService: OTA package size = 21989297
,11-24 15:41:05.003  4073  5770 I SystemUpdateService: showing system update notification
,11-24 15:41:05.010   926   926 V NotificationService: pkg=com.google.android.gms canInterrupt=false intercept=true
,11-24 15:41:05.011  4073  4073 D SystemUpdateService: onDestroy
,11-24 15:41:05.080   926  2973 D wifi    : In wifi stop Hal
11-24 15:41:05.080   926  2973 D wifi    : halHandle = 0x7f6f9fbf80, mVM = 0x7f8a50d140, mCls = 0x2018ea
,11-24 15:41:05.081   926  5728 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
,11-24 15:41:05.081   926  5728 D WifiHAL : Got a signal to exit!!!
11-24 15:41:05.081   926  5728 I WifiHAL : Exit wifi_event_loop
11-24 15:41:05.082  3934  4209 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
11-24 15:41:05.083  4817  4817 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
11-24 15:41:05.083   926  2973 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 0
11-24 15:41:05.083   926  2973 E WifiHAL : Event processing terminated
11-24 15:41:05.083   926  2973 D wifi    : In wifi cleaned up handler
11-24 15:41:05.084   926  2973 I WifiHAL : Internal cleanup completed
11-24 15:41:05.084  5519  5519 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-24 15:41:05.114   926  5728 D wifi    : set interface wlan0 flags (DOWN)
,11-24 15:41:05.115   926  2973 D WifiNative-HAL: HAL event thread stopped successfully
,11-24 15:41:05.319   926   943 D Tethering: InitialState.processMessage what=4
,11-24 15:41:05.325   926   943 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,11-24 15:41:05.621   926  2975 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,11-24 15:41:08.805   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 15:41:09.805   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 15:41:09.873   926   943 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@b76a465:true
,11-24 15:41:09.874  5655  5655 D BluetoothAdapterState: make() - Creating AdapterState
,11-24 15:41:09.879  5655  5655 I bt_bluedroid: init
,11-24 15:41:09.879  5655  5776 I BluetoothAdapterState: Entering OffState
,11-24 15:41:09.883  5655  5777 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,11-24 15:41:09.883  5655  5777 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
,11-24 15:41:09.883  5655  5777 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
11-24 15:41:09.883  5655  5777 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
11-24 15:41:09.884  5655  5655 I bt_bluedroid: get_profile_interface socket
,11-24 15:41:09.886  5655  5655 I bt_bluedroid: get_profile_interface sdp
,11-24 15:41:09.886  5655  5780 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:D4
,11-24 15:41:09.888  5655  5780 D BluetoothAdapterProperties: Name is: Nexus 6P
,11-24 15:41:09.892  5655  5665 I bt_bluedroid: config_hci_snoop_log
,11-24 15:41:09.894   926   943 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,11-24 15:41:09.899  5655  5776 D BluetoothAdapterState: Current state: OFF, message: 0
,11-24 15:41:09.899  5655  5776 D BluetoothAdapterProperties: Setting state to 14
11-24 15:41:09.899  5655  5776 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,11-24 15:41:09.901  5655  5776 D BluetoothBondStateMachine: make
,11-24 15:41:09.903  5655  5781 I BluetoothBondStateMachine: StableState(): Entering Off State
,11-24 15:41:09.906  5655  5776 I BluetoothAdapterState: Entering PendingCommandState
,11-24 15:41:09.907  5655  5655 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,11-24 15:41:09.910  5655  5655 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@cf72321
,11-24 15:41:09.911  5655  5655 D BtGatt.DebugUtils: handleDebugAction() action=null
,11-24 15:41:09.911  5655  5655 D BtGatt.GattService: Received start request. Starting profile...
,11-24 15:41:09.911  5655  5655 D BtGatt.GattService: start()
11-24 15:41:09.911  5655  5655 I bt_bluedroid: get_profile_interface gatt
11-24 15:41:09.912  5655  5655 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@cf72321
,11-24 15:41:09.912  5655  5655 D BtGatt.AdvertiseManager: advertise manager created
,11-24 15:41:09.917  5655  5655 V BluetoothAdapterState: isTurningOff()=false
,11-24 15:41:09.917  5655  5655 V BluetoothAdapterState: isTurningOn()=false
11-24 15:41:09.917  5655  5655 V BluetoothAdapterState: isBleTurningOn()=true
11-24 15:41:09.917  5655  5655 V BluetoothAdapterState: isBleTurningOff()=false
11-24 15:41:09.918  5655  5776 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,11-24 15:41:09.919  5655  5776 I bt_bluedroid: bt_bluedroid
,11-24 15:41:09.919  5655  5777 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,11-24 15:41:09.920  5655  5777 I bt_hci  : start_up
,11-24 15:41:09.925  5655  5777 I bt_vendor: alloc value 0xf3d78871
,11-24 15:41:09.925  5655  5777 I bt_vendor: init
11-24 15:41:09.925  5655  5777 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
11-24 15:41:09.925  5655  5777 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,11-24 15:41:10.035  5655  5777 D bt_hci  : start_up starting async portion
11-24 15:41:10.035  5655  5784 I bt_hci  : event_finish_startup
,11-24 15:41:10.035  5655  5784 I bt_hci_h4: hal_open
11-24 15:41:10.036  5655  5784 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,11-24 15:41:10.038  5655  5784 I bt_userial_vendor: device fd = 54 open
,11-24 15:41:10.034  5785  5785 W irq/448-msm_hs_: type=1400 audit(0.0:119): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-24 15:41:10.052  5655  5784 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,11-24 15:41:10.055  5655  5784 D bt_hwcfg: Chipset BCM4358A3
,11-24 15:41:10.055  5655  5784 D bt_hwcfg: Target name = [BCM4358A3]
11-24 15:41:10.056  5655  5784 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,11-24 15:41:10.454  5655  5784 I bt_hwcfg: bt vendor lib: set UART baud 115200
,11-24 15:41:10.454  5655  5784 D bt_hwcfg: Settlement delay -- 100 ms
11-24 15:41:10.454  5655  5784 I bt_hwcfg: Setting fw settlement delay to 100 
,11-24 15:41:10.588  5655  5784 I bt_hwcfg: bt vendor lib: set UART baud 3000000
11-24 15:41:10.589  5655  5784 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:D4
11-24 15:41:10.590  5655  5784 I bt_hwcfg: vendor lib fwcfg completed
11-24 15:41:10.590  5655  5784 I bt_vendor: firmware callback
11-24 15:41:10.590  5655  5784 I bt_hci  : firmware_config_callback
,11-24 15:41:10.600  5655  5789 I bt_btu  : btu_task pending for preload complete event
,11-24 15:41:10.600  5655  5789 I bt_btu_task: Bluetooth chip preload is complete
11-24 15:41:10.600  5655  5789 I bt_btu  : btu_task received preload complete event
,11-24 15:41:10.608  5655  5789 I         : BTE_InitTraceLevels -- TRC_HCI
,11-24 15:41:10.608  5655  5789 I         : BTE_InitTraceLevels -- TRC_L2CAP
11-24 15:41:10.608  5655  5789 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,11-24 15:41:10.608  5655  5789 I         : BTE_InitTraceLevels -- TRC_AVDT
11-24 15:41:10.608  5655  5789 I         : BTE_InitTraceLevels -- TRC_AVRC
11-24 15:41:10.608  5655  5789 I         : BTE_InitTraceLevels -- TRC_A2D
11-24 15:41:10.609  5655  5789 I         : BTE_InitTraceLevels -- TRC_BNEP
,11-24 15:41:10.609  5655  5789 I         : BTE_InitTraceLevels -- TRC_BTM
11-24 15:41:10.609  5655  5789 I         : BTE_InitTraceLevels -- TRC_GAP
,11-24 15:41:10.609  5655  5789 I         : BTE_InitTraceLevels -- TRC_PAN
,11-24 15:41:10.609  5655  5789 I         : BTE_InitTraceLevels -- TRC_SDP
11-24 15:41:10.609  5655  5789 I         : BTE_InitTraceLevels -- TRC_GATT
,11-24 15:41:10.609  5655  5789 I         : BTE_InitTraceLevels -- TRC_SMP
,11-24 15:41:10.609  5655  5789 I         : BTE_InitTraceLevels -- TRC_BTAPP
11-24 15:41:10.610  5655  5789 I         : BTE_InitTraceLevels -- TRC_BTIF
,11-24 15:41:10.694  5655  5789 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf3cf6549
11-24 15:41:10.695  5655  5789 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf3cf6549 
,11-24 15:41:10.705  5655  5780 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,11-24 15:41:10.706  5655  5780 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,11-24 15:41:10.707  5655  5780 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:D4
,11-24 15:41:10.710  5655  5780 D BluetoothAdapterProperties: Name is: Nexus 6P
,11-24 15:41:10.714  5655  5780 D BluetoothAdapterProperties: Scan Mode:20
11-24 15:41:10.714  5655  5780 D BluetoothAdapterProperties: Discoverable Timeout:120
11-24 15:41:10.715  5655  5780 D bt_hci  : do_postload posting postload work item
11-24 15:41:10.715  5655  5784 I bt_hci  : event_postload
11-24 15:41:10.715  5655  5784 I bt_vendor: sco_config_cb
11-24 15:41:10.715  5655  5784 I bt_hci  : sco_config_callback postload finished.
11-24 15:41:10.718  5655  5780 D bt_bte_conf: Device ID record 1 : primary
11-24 15:41:10.718  5655  5780 D bt_bte_conf:   vendorId            = 000f
11-24 15:41:10.719  5655  5780 D bt_bte_conf:   vendorIdSource      = 0001
,11-24 15:41:10.719  5655  5780 D bt_bte_conf:   product             = 1200
11-24 15:41:10.719  5655  5780 D bt_bte_conf:   version             = 1436
,11-24 15:41:10.719  5655  5780 D bt_bte_conf:   clientExecutableURL = 
11-24 15:41:10.719  5655  5780 D bt_bte_conf:   serviceDescription  = 
11-24 15:41:10.719  5655  5780 D bt_bte_conf:   documentationURL    = 
11-24 15:41:10.719  5655  5780 D bt_bte_conf: bte_load_did_conf no section named DID2.
11-24 15:41:10.719  5519  5519 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-24 15:41:10.719  5655  5777 D bt_stack_manager: event_start_up_stack finished
,11-24 15:41:10.720  5655  5776 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
11-24 15:41:10.721  5655  5776 D BluetoothAdapterProperties: Setting state to 15
11-24 15:41:10.721  5655  5776 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
11-24 15:41:10.723  5655  5776 I BluetoothAdapterState: Entering BleOnState
11-24 15:41:10.724  5655  5784 I bt_vendor: low_power_mode_cb
,11-24 15:41:10.727  5655  5776 D BluetoothAdapterState: Current state: BLE ON, message: 1
11-24 15:41:10.727  5655  5776 D BluetoothAdapterProperties: Setting state to 11
11-24 15:41:10.727  5655  5776 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,11-24 15:41:10.732  5655  5655 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@cf72321
,11-24 15:41:10.733  5655  5655 D HeadsetService: Received start request. Starting profile...
11-24 15:41:10.736  5519  5519 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-24 15:41:10.737  5655  5655 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,11-24 15:41:10.737  5655  5655 D HeadsetStateMachine: make
,11-24 15:41:10.746  5655  5776 I BluetoothAdapterState: Entering PendingCommandState
,11-24 15:41:10.749  5655  5655 D HeadsetStateMachine: max_hf_connections = 1
,11-24 15:41:10.749  5655  5655 I bt_bluedroid: get_profile_interface handsfree
11-24 15:41:10.750  5655  5780 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
11-24 15:41:10.750  5655  5780 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
11-24 15:41:10.753  5655  5655 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@cf72321
,11-24 15:41:10.754  5655  5655 D A2dpService: Received start request. Starting profile...
11-24 15:41:10.755  5655  5655 I BluetoothAvrcpServiceJni: classInitNative: succeeds
11-24 15:41:10.755  5655  5655 I bt_bluedroid: get_profile_interface avrcp
,11-24 15:41:10.761  5655  5655 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,11-24 15:41:10.761  5655  5655 I BluetoothA2dpServiceJni: classInitNative: succeeds
11-24 15:41:10.761  5655  5655 D A2dpStateMachine: make
,11-24 15:41:10.762  5655  5655 I bt_bluedroid: get_profile_interface a2dp
,11-24 15:41:10.763  5655  5780 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,11-24 15:41:10.765  5655  5797 D A2dpStateMachine: Enter Disconnected: -2
,11-24 15:41:10.765  5655  5655 I BluetoothHidServiceJni: classInitNative: succeeds
,11-24 15:41:10.766  5655  5655 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@cf72321
11-24 15:41:10.767  5590  5590 D BluetoothInputDevice: Proxy object connected
11-24 15:41:10.769  5655  5655 D HidService: Received start request. Starting profile...
11-24 15:41:10.769  5655  5655 I bt_bluedroid: get_profile_interface hidhost
11-24 15:41:10.769  5655  5655 D HidService: setHidService(): set to: null
11-24 15:41:10.769  5655  5780 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf3cd756d
11-24 15:41:10.770  5655  5780 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
11-24 15:41:10.770  5655  5655 I BluetoothHealthServiceJni: classInitNative: succeeds
,11-24 15:41:10.771  5655  5655 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@cf72321
,11-24 15:41:10.772  3592  3592 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
11-24 15:41:10.772  5655  5655 D HealthService: Received start request. Starting profile...
11-24 15:41:10.773  5590  5590 D HidProfile: Bluetooth service connected
11-24 15:41:10.774  5655  5655 I bt_bluedroid: get_profile_interface health
11-24 15:41:10.774  5655  5655 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,11-24 15:41:10.775  5655  5655 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@cf72321
11-24 15:41:10.776  5590  5590 D BluetoothPan: BluetoothPAN Proxy object connected
11-24 15:41:10.777  5655  5655 D PanService: Received start request. Starting profile...
11-24 15:41:10.777  5655  5655 D BluetoothPanServiceJni: initializeNative(L110): pan
11-24 15:41:10.777  5655  5655 I bt_bluedroid: get_profile_interface pan
,11-24 15:41:10.777  5590  5590 D PanProfile: Bluetooth service connected
11-24 15:41:10.778  5655  5780 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,11-24 15:41:10.780  5655  5655 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@cf72321
,11-24 15:41:10.781  5590  5590 D BluetoothMap: Proxy object connected
11-24 15:41:10.782  5655  5655 D BluetoothMapService: Received start request. Starting profile...
11-24 15:41:10.782  5655  5655 D BluetoothMapService: start()
11-24 15:41:10.782  5590  5590 D MapProfile: Bluetooth service connected
11-24 15:41:10.782  5590  5590 D BluetoothMap: getConnectedDevices()
11-24 15:41:10.783  5590  5590 D BluetoothMap: Bluetooth is Not enabled
,11-24 15:41:10.785  5655  5655 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,11-24 15:41:10.786  5655  5655 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
,11-24 15:41:10.786  5655  5655 D BluetoothMapAppObserver: createReceiver()
11-24 15:41:10.787  5655  5655 D BluetoothMapAppObserver: initObservers()
11-24 15:41:10.787  5655  5655 D BluetoothMapAppObserver: getEnabledAccountItems()
,11-24 15:41:10.793  5655  5655 V SapService: SapBinder()
,11-24 15:41:10.794  5655  5655 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@cf72321
,11-24 15:41:10.794  5655  5655 D SapService: Received start request. Starting profile...
11-24 15:41:10.794  5655  5655 V SapService: start()
,11-24 15:41:10.797  5655  5655 V BluetoothAdapterState: isTurningOff()=false
,11-24 15:41:10.797  5655  5655 V BluetoothAdapterState: isTurningOn()=true
11-24 15:41:10.797  5655  5655 V BluetoothAdapterState: isBleTurningOn()=false
11-24 15:41:10.797  5655  5795 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
11-24 15:41:10.797  5655  5655 V BluetoothAdapterState: isBleTurningOff()=false
11-24 15:41:10.797  5655  5655 V BluetoothAdapterState: isTurningOff()=false
11-24 15:41:10.797  5655  5655 V BluetoothAdapterState: isTurningOn()=true
,11-24 15:41:10.797  5655  5655 V BluetoothAdapterState: isBleTurningOn()=false
11-24 15:41:10.797  5655  5655 V BluetoothAdapterState: isBleTurningOff()=false
11-24 15:41:10.798  5655  5655 V BluetoothAdapterState: isTurningOff()=false
11-24 15:41:10.798  5655  5655 V BluetoothAdapterState: isTurningOn()=true
11-24 15:41:10.798  5655  5655 V BluetoothAdapterState: isBleTurningOn()=false
11-24 15:41:10.798  5655  5655 V BluetoothAdapterState: isBleTurningOff()=false
11-24 15:41:10.798  5655  5655 V BluetoothAdapterState: isTurningOff()=false
11-24 15:41:10.798  5655  5655 V BluetoothAdapterState: isTurningOn()=true
11-24 15:41:10.798  5655  5655 V BluetoothAdapterState: isBleTurningOn()=false
11-24 15:41:10.798  5655  5655 V BluetoothAdapterState: isBleTurningOff()=false
,11-24 15:41:10.798  5655  5655 V BluetoothAdapterState: isTurningOff()=false
11-24 15:41:10.798  5655  5655 V BluetoothAdapterState: isTurningOn()=true
11-24 15:41:10.798  5655  5655 V BluetoothAdapterState: isBleTurningOn()=false
11-24 15:41:10.798  5655  5655 V BluetoothAdapterState: isBleTurningOff()=false
11-24 15:41:10.798  5655  5655 V BluetoothAdapterState: isTurningOff()=false
11-24 15:41:10.799  5655  5655 V BluetoothAdapterState: isTurningOn()=true
11-24 15:41:10.799  5655  5655 V BluetoothAdapterState: isBleTurningOn()=false
11-24 15:41:10.799  5655  5655 V BluetoothAdapterState: isBleTurningOff()=false
11-24 15:41:10.799  5655  5655 V BluetoothAdapterState: isTurningOff()=false
11-24 15:41:10.799  5655  5655 V BluetoothAdapterState: isTurningOn()=true
11-24 15:41:10.799  5655  5655 V BluetoothAdapterState: isBleTurningOn()=false
11-24 15:41:10.799  5655  5655 V BluetoothAdapterState: isBleTurningOff()=false
11-24 15:41:10.799  5655  5776 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
,11-24 15:41:10.800  5655  5776 D BluetoothAdapterProperties: ScanMode =  20
11-24 15:41:10.800  5655  5776 D BluetoothAdapterProperties: State =  11
11-24 15:41:10.802  5655  5780 D BluetoothAdapterProperties: Scan Mode:21
,11-24 15:41:10.802  5655  5780 D BluetoothAdapterProperties: Discoverable Timeout:120
11-24 15:41:10.803  5519  5519 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
11-24 15:41:10.803  5655  5776 D BluetoothAdapterProperties: Setting state to 12
11-24 15:41:10.803  5655  5776 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,11-24 15:41:10.804  5655  5776 I BluetoothAdapterState: Entering OnState
11-24 15:41:10.804  3141  3156 D BluetoothPan: onBluetoothStateChange on: true
,11-24 15:41:10.806   535   535 I ServiceManager: Waiting for service AtCmdFwd...
11-24 15:41:10.806   926   943 D BluetoothA2dp: onBluetoothStateChange: up=true
11-24 15:41:10.806  3141  3141 D BluetoothPan: BluetoothPAN Proxy object connected
11-24 15:41:10.806  3141  3141 D PanProfile: Bluetooth service connected
11-24 15:41:10.807  5519  5519 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-24 15:41:10.807  5519  5519 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-24 15:41:10.807  5519  5519 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-24 15:41:10.807  5519  5519 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-24 15:41:10.807  5519  5519 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-24 15:41:10.807  5519  5519 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-24 15:41:10.807  5519  5519 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-24 15:41:10.807  5519  5519 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-24 15:41:10.807  5519  5519 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-24 15:41:10.807  5590  5606 D BluetoothPan: onBluetoothStateChange on: true
11-24 15:41:10.808  5590  5603 D BluetoothMap: onBluetoothStateChange: up=true
11-24 15:41:10.808   926   926 D BluetoothA2dp: Proxy object connected
11-24 15:41:10.808   926   943 D BluetoothHeadset: onBluetoothStateChange: up=true
,11-24 15:41:10.808  3141  3153 D BluetoothMap: onBluetoothStateChange: up=true
11-24 15:41:10.810  5519  5519 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
11-24 15:41:10.810  3141  3141 D BluetoothMap: Proxy object connected
11-24 15:41:10.810  3774  4026 D BluetoothHeadset: onBluetoothStateChange: up=true
11-24 15:41:10.810  3141  3141 D MapProfile: Bluetooth service connected
11-24 15:41:10.810  3141  3141 D BluetoothMap: getConnectedDevices()
11-24 15:41:10.810  5590  5606 D BluetoothInputDevice: onBluetoothStateChange: up=true
11-24 15:41:10.811  3141  3156 D BluetoothPbap: onBluetoothStateChange: up=true
11-24 15:41:10.812  3141  4171 D BluetoothA2dp: onBluetoothStateChange: up=true
11-24 15:41:10.813  5655  5655 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
11-24 15:41:10.814   926   943 D BluetoothHeadset: onBluetoothStateChange: up=true
,11-24 15:41:10.814  3141  3141 D BluetoothA2dp: Proxy object connected
11-24 15:41:10.814  3141  3156 D BluetoothInputDevice: onBluetoothStateChange: up=true
11-24 15:41:10.814  5655  5655 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
11-24 15:41:10.815  5655  5655 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-24 15:41:10.816  3141  3141 D BluetoothInputDevice: Proxy object connected
11-24 15:41:10.816  3141  3141 D HidProfile: Bluetooth service connected
11-24 15:41:10.816   926   943 D BluetoothHeadset: onBluetoothStateChange: up=true
11-24 15:41:10.817  5590  5603 D BluetoothPbap: onBluetoothStateChange: up=true
11-24 15:41:10.817  5655  5655 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-24 15:41:10.818  3141  3153 D BluetoothHeadset: onBluetoothStateChange: up=true
11-24 15:41:10.819  5655  5655 D ObexServerSockets: Succeed to create listening sockets 
11-24 15:41:10.819  5655  5655 D ObexServerSockets0: startAccept()
11-24 15:41:10.819  5655  5655 D ObexServerSockets0: prepareForNewConnect()
11-24 15:41:10.819   926   926 I Telecom : BluetoothPhoneService: queryPhoneState
11-24 15:41:10.820  5519  5519 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
,11-24 15:41:10.822  5655  5655 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
11-24 15:41:10.822  5590  5590 D LocalBluetoothProfileManager: Adding local A2DP profile
11-24 15:41:10.822  5655  5655 D BluetoothSdpJni: SDP Create record success - handle: 0
11-24 15:41:10.822  5519  5519 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-24 15:41:10.824  5655  5803 D ObexServerSockets0: Accepting socket connection...
11-24 15:41:10.824  5655  5655 D BluetoothMapService: onReceive
11-24 15:41:10.824  5655  5804 D ObexServerSockets0: Accepting socket connection...
11-24 15:41:10.824  5655  5655 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
11-24 15:41:10.824  5655  5655 D BluetoothMapService: STATE_ON
,11-24 15:41:10.826  5655  5805 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-24 15:41:10.826  5590  5590 D LocalBluetoothProfileManager: Adding local HEADSET profile
,11-24 15:41:10.828  5655  5805 D BluetoothSdpJni: sdpCreateSapsRecordNative:
,11-24 15:41:10.828  5655  5805 D BluetoothSdpJni: SDP Create record success - handle: 1
,11-24 15:41:10.832  5590  5590 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
11-24 15:41:10.835  5590  5590 D BluetoothA2dp: Proxy object connected
,11-24 15:41:10.839  3592  3592 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,11-24 15:41:10.844  5590  5590 D DockEventReceiver: finishStartingService: stopping service
,11-24 15:41:10.846  5590  5590 D BluetoothPbap: Proxy object connected
11-24 15:41:10.846  3141  3141 D BluetoothPbap: Proxy object connected
,11-24 15:41:10.846  3141  3141 D PbapServerProfile: Bluetooth service connected
11-24 15:41:10.847  5590  5590 D PbapServerProfile: Bluetooth service connected
,11-24 15:41:10.851  5655  5655 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
11-24 15:41:10.851  5655  5655 D ObexServerSockets0: prepareForNewConnect()
,11-24 15:41:10.853  5655  5809 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-24 15:41:10.867  5655  5813 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-24 15:41:10.868  5655  5813 I BtOppRfcommListener: Accept thread started.
,11-24 15:41:10.910   926   926 D BluetoothHeadset: Proxy object connected
,11-24 15:41:10.911  3141  4171 D BluetoothHeadset: Proxy object connected
11-24 15:41:10.911  3774  3788 D BluetoothHeadset: Proxy object connected
11-24 15:41:10.911  3141  3141 D HeadsetProfile: Bluetooth service connected
11-24 15:41:10.911  3774  3795 D BluetoothHeadset: Proxy object connected
11-24 15:41:10.911   926   926 D BluetoothHeadset: Proxy object connected
11-24 15:41:10.911   926   926 D BluetoothHeadset: Proxy object connected
,11-24 15:41:10.914   926   943 D BluetoothHeadset: Proxy object connected
,11-24 15:41:10.916   926   943 D BluetoothHeadset: Proxy object connected
,11-24 15:41:10.919  3141  3153 D BluetoothHeadset: Proxy object connected
,11-24 15:41:10.919  3141  3141 D HeadsetProfile: Bluetooth service connected
,11-24 15:41:10.929  5590  5606 D BluetoothHeadset: Proxy object connected
,11-24 15:41:10.930  5590  5590 D HeadsetProfile: Bluetooth service connected
,11-24 15:41:11.807   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 15:41:12.579   926  2975 D ConnectivityService: handlePromptUnvalidated 101
,11-24 15:41:12.808   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 15:41:13.217  3689  3856 I Keyboard.Facilitator.LanguageModelFlusher: run()
,11-24 15:41:13.217  3689  3856 I Keyboard.Facilitator: flushDynamicLanguageModels()
,11-24 15:41:13.245  3592  3592 I ConfigService: onCreate
,11-24 15:41:13.809   535   535 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,11-24 15:41:14.857  5655  5776 D BluetoothAdapterState: Current state: ON, message: 23
,11-24 15:41:14.857  5655  5776 D BluetoothAdapterProperties: Setting state to 13
,11-24 15:41:14.858  5655  5776 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,11-24 15:41:14.859  5655  5776 D BluetoothAdapterProperties: onBluetoothDisable()
11-24 15:41:14.862  5655  5776 I BluetoothAdapterState: Entering PendingCommandState
11-24 15:41:14.867  5655  5655 D BluetoothMapService: onReceive
11-24 15:41:14.867  5655  5655 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
11-24 15:41:14.867  5655  5655 D BluetoothMapService: STATE_TURNING_OFF
,11-24 15:41:14.868  5655  5655 D BluetoothMapService: MAP Service closeService in
11-24 15:41:14.868  5655  5655 D BluetoothMapMasInstance0: MAP Service shutdown
11-24 15:41:14.868  5655  5655 D ObexServerSockets0: shutdown(block = true)
11-24 15:41:14.869  5655  5780 D BluetoothAdapterProperties: Scan Mode:20
,11-24 15:41:14.870  5655  5776 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
11-24 15:41:14.873  5655  5803 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
11-24 15:41:14.873  5519  5519 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-24 15:41:14.873  5519  5519 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-24 15:41:14.873  5519  5519 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-24 15:41:14.873  5519  5519 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-24 15:41:14.873  5519  5519 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-24 15:41:14.873  5519  5519 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-24 15:41:14.873  5519  5519 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-24 15:41:14.873  5519  5519 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-24 15:41:14.873  5519  5519 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-24 15:41:14.873  5519  5519 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-24 15:41:14.874  5519  5519 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,11-24 15:41:14.875  5519  5519 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
11-24 15:41:14.876  5519  5519 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-24 15:41:14.877  5590  5590 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
11-24 15:41:14.879  5655  5655 D ObexServerSockets0: shutdown called from another thread - interrupt().
11-24 15:41:14.879  5655  5655 D ObexServerSockets0: shutdown called from another thread - interrupt().
,11-24 15:41:14.879  5655  5804 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
11-24 15:41:14.880  5655  5791 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
11-24 15:41:14.882  5655  5655 I BtOppRfcommListener: stopping Accept Thread
11-24 15:41:14.882  5655  5813 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
11-24 15:41:14.882  5655  5813 I BtOppRfcommListener: BluetoothSocket listen thread finished
,11-24 15:41:14.884  5655  5655 D HeadsetService: Received stop request...Stopping profile...
,11-24 15:41:14.885   926   926 D BluetoothHeadset: Proxy object disconnected
,11-24 15:41:14.886  5590  5603 D BluetoothHeadset: Proxy object disconnected
11-24 15:41:14.886  5655  5655 D A2dpService: Received stop request...Stopping profile...
,11-24 15:41:14.887  5655  5797 D A2dpStateMachine: Exit Disconnected: -1
11-24 15:41:14.887  3141  3153 D BluetoothHeadset: Proxy object disconnected
11-24 15:41:14.889  3774  4026 D BluetoothHeadset: Proxy object disconnected
11-24 15:41:14.889  5655  5655 D HidService: Received stop request...Stopping profile...
,11-24 15:41:14.889  5655  5655 D HidService: Stopping Bluetooth HidService
11-24 15:41:14.889   926   926 D BluetoothHeadset: Proxy object disconnected
11-24 15:41:14.889   926   926 D BluetoothHeadset: Proxy object disconnected
11-24 15:41:14.889   926   926 D BluetoothA2dp: Proxy object disconnected
11-24 15:41:14.891  5655  5655 D HealthService: Received stop request...Stopping profile...
11-24 15:41:14.892  5655  5655 D PanService: Received stop request...Stopping profile...
,11-24 15:41:14.893  3141  3141 D HeadsetProfile: Bluetooth service disconnected
11-24 15:41:14.893  3141  3141 D BluetoothA2dp: Proxy object disconnected
11-24 15:41:14.893  3141  3141 D BluetoothInputDevice: Proxy object disconnected
11-24 15:41:14.893  3141  3141 D HidProfile: Bluetooth service disconnected
11-24 15:41:14.894  5590  5590 D DockEventReceiver: finishStartingService: stopping service
11-24 15:41:14.894  3141  3141 D BluetoothPan: BluetoothPAN Proxy object disconnected
11-24 15:41:14.894  3141  3141 D PanProfile: Bluetooth service disconnected
11-24 15:41:14.898  3592  3592 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
11-24 15:41:14.898  5590  5590 D HeadsetProfile: Bluetooth service disconnected
11-24 15:41:14.898  5655  5655 V BluetoothAdapterState: isTurningOff()=true
11-24 15:41:14.898  5655  5655 V BluetoothAdapterState: isTurningOn()=false
11-24 15:41:14.898  5655  5655 V BluetoothAdapterState: isBleTurningOn()=false
11-24 15:41:14.898  5655  5655 V BluetoothAdapterState: isBleTurningOff()=false
11-24 15:41:14.898  5590  5590 D BluetoothA2dp: Proxy object disconnected
11-24 15:41:14.898  5590  5590 D BluetoothInputDevice: Proxy object disconnected
11-24 15:41:14.898  5590  5590 D HidProfile: Bluetooth service disconnected
11-24 15:41:14.898  5590  5590 D BluetoothPan: BluetoothPAN Proxy object disconnected
11-24 15:41:14.899  5590  5590 D PanProfile: Bluetooth service disconnected
,11-24 15:41:14.901  5655  5655 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
11-24 15:41:14.901  5655  5655 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
11-24 15:41:14.901  5655  5780 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
11-24 15:41:14.901  5655  5789 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-24 15:41:14.901  5655  5789 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-24 15:41:14.901  5655  5789 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-24 15:41:14.901  5655  5780 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
11-24 15:41:14.906  5655  5655 V BluetoothAdapterState: isTurningOff()=true
11-24 15:41:14.906  5655  5655 V BluetoothAdapterState: isTurningOn()=false
11-24 15:41:14.906  5655  5655 V BluetoothAdapterState: isBleTurningOn()=false
11-24 15:41:14.906  5655  5655 V BluetoothAdapterState: isBleTurningOff()=false
,11-24 15:41:14.907  5655  5655 V BluetoothAdapterState: isTurningOff()=true
,11-24 15:41:14.907  5655  5780 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
11-24 15:41:14.907  5655  5655 V BluetoothAdapterState: isTurningOn()=false
11-24 15:41:14.907  5655  5789 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-24 15:41:14.907  5655  5655 V BluetoothAdapterState: isBleTurningOn()=false
11-24 15:41:14.907  5655  5655 V BluetoothAdapterState: isBleTurningOff()=false
11-24 15:41:14.908  5655  5789 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-24 15:41:14.908  5655  5789 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
11-24 15:41:14.908  5655  5789 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
11-24 15:41:14.908  5655  5789 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,11-24 15:41:14.908  5655  5789 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
11-24 15:41:14.908  5655  5655 D BluetoothMapService: Received stop request...Stopping profile...
11-24 15:41:14.908  5655  5655 D BluetoothMapService: stop()
11-24 15:41:14.909  5655  5655 D BluetoothMapAppObserver: deinitObservers()
11-24 15:41:14.909  5655  5655 D BluetoothMapAppObserver: removeReceiver()
11-24 15:41:14.910  3141  3141 D BluetoothMap: Proxy object disconnected
11-24 15:41:14.910  3141  3141 D MapProfile: Bluetooth service disconnected
11-24 15:41:14.910  5590  5590 D BluetoothMap: Proxy object disconnected
11-24 15:41:14.910  5655  5655 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
11-24 15:41:14.910  5590  5590 D MapProfile: Bluetooth service disconnected
11-24 15:41:14.910  5655  5655 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
11-24 15:41:14.910  5655  5780 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
11-24 15:41:14.910  5655  5655 V BluetoothAdapterState: isTurningOff()=true
11-24 15:41:14.910  5655  5655 V BluetoothAdapterState: isTurningOn()=false
,11-24 15:41:14.910  5655  5655 V BluetoothAdapterState: isBleTurningOn()=false
11-24 15:41:14.910  5655  5655 V BluetoothAdapterState: isBleTurningOff()=false
11-24 15:41:14.911  5655  5655 D SapService: Received stop request...Stopping profile...
11-24 15:41:14.911  5655  5655 V SapService: stop()
11-24 15:41:14.913  5655  5655 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
11-24 15:41:14.913  5655  5780 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
,11-24 15:41:14.915  5655  5655 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
11-24 15:41:14.915  5655  5655 V BluetoothAdapterState: isTurningOff()=true
11-24 15:41:14.915  5655  5655 V BluetoothAdapterState: isTurningOn()=false
11-24 15:41:14.915  5655  5655 V BluetoothAdapterState: isBleTurningOn()=false
11-24 15:41:14.915  5655  5655 V BluetoothAdapterState: isBleTurningOff()=false
11-24 15:41:14.915  5655  5655 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
,11-24 15:41:14.915  5655  5655 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
,11-24 15:41:14.917  5590  5590 D BluetoothPbap: Proxy object disconnected
11-24 15:41:14.917  5590  5590 D PbapServerProfile: Bluetooth service disconnected
11-24 15:41:14.917  3141  3141 D BluetoothPbap: Proxy object disconnected
,11-24 15:41:14.917  3141  3141 D PbapServerProfile: Bluetooth service disconnected
11-24 15:41:14.918  5655  5655 D BluetoothMapService: MAP Service closeService in
11-24 15:41:14.918  5655  5655 V BluetoothAdapterState: isTurningOff()=true
11-24 15:41:14.918  5655  5655 V BluetoothAdapterState: isTurningOn()=false
11-24 15:41:14.918  5655  5655 V BluetoothAdapterState: isBleTurningOn()=false
11-24 15:41:14.918  5655  5655 V BluetoothAdapterState: isBleTurningOff()=false
11-24 15:41:14.918  5655  5655 D BluetoothMapService: cleanup()
11-24 15:41:14.918  5655  5655 D BluetoothMapService: MAP Service closeService in
11-24 15:41:14.919  5655  5655 V BluetoothAdapterState: isTurningOff()=true
,11-24 15:41:14.919  5655  5655 V BluetoothAdapterState: isTurningOn()=false
11-24 15:41:14.919  5655  5655 V BluetoothAdapterState: isBleTurningOn()=false
11-24 15:41:14.919  5655  5655 V BluetoothAdapterState: isBleTurningOff()=false
11-24 15:41:14.919  5655  5776 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
11-24 15:41:14.919  5655  5776 D BluetoothAdapterProperties: Setting state to 15
11-24 15:41:14.919  5655  5776 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
11-24 15:41:14.920  5655  5776 I BluetoothAdapterState: Entering BleOnState
11-24 15:41:14.920  3141  3156 D BluetoothPan: onBluetoothStateChange on: false
11-24 15:41:14.921   926   943 D BluetoothA2dp: onBluetoothStateChange: up=false
11-24 15:41:14.921  5590  5606 D BluetoothPan: onBluetoothStateChange on: false
,11-24 15:41:14.922  5590  5603 D BluetoothMap: onBluetoothStateChange: up=false
,11-24 15:41:14.923  5590  5606 D BluetoothA2dp: onBluetoothStateChange: up=false
11-24 15:41:14.923   926   943 D BluetoothHeadset: onBluetoothStateChange: up=false
11-24 15:41:14.923  3141  3153 D BluetoothMap: onBluetoothStateChange: up=false
11-24 15:41:14.924  3774  3788 D BluetoothHeadset: onBluetoothStateChange: up=false
11-24 15:41:14.924  5590  5603 D BluetoothHeadset: onBluetoothStateChange: up=false
11-24 15:41:14.924  5590  5606 D BluetoothInputDevice: onBluetoothStateChange: up=false
11-24 15:41:14.925  3141  4171 D BluetoothPbap: onBluetoothStateChange: up=false
,11-24 15:41:14.925  3141  3156 D BluetoothA2dp: onBluetoothStateChange: up=false
11-24 15:41:14.926   926   943 D BluetoothHeadset: onBluetoothStateChange: up=false
11-24 15:41:14.926  3141  3153 D BluetoothInputDevice: onBluetoothStateChange: up=false
11-24 15:41:14.926   926   943 D BluetoothHeadset: onBluetoothStateChange: up=false
11-24 15:41:14.926  5590  5603 D BluetoothPbap: onBluetoothStateChange: up=false
11-24 15:41:14.927  3141  4171 D BluetoothHeadset: onBluetoothStateChange: up=false
11-24 15:41:14.927  5655  5776 D BluetoothAdapterState: Current state: BLE ON, message: 20
11-24 15:41:14.927  5655  5776 D BluetoothAdapterProperties: Setting state to 16
11-24 15:41:14.927  5655  5776 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
,11-24 15:41:14.928  5655  5776 D BluetoothAdapterProperties: onBleDisable
11-24 15:41:14.928  5655  5776 I BluetoothAdapterState: Entering PendingCommandState
11-24 15:41:14.929  5655  5777 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
11-24 15:41:14.930  5655  5789 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
11-24 15:41:14.930  5655  5789 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-24 15:41:14.930  5519  5519 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-24 15:41:14.930  5655  5780 D BluetoothAdapterProperties: Scan Mode:20
11-24 15:41:14.930  5590  5590 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
11-24 15:41:14.933  5519  5519 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-24 15:41:14.935  3592  3592 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,11-24 15:41:14.937  5590  5590 D DockEventReceiver: finishStartingService: stopping service
,11-24 15:41:15.136  5655  5780 I bt_hci  : shut_down
,11-24 15:41:15.145  5655  5784 D bt_hwcfg: hw_epilog_process
11-24 15:41:15.145  5655  5784 I bt_vendor: low_power_mode_cb
,11-24 15:41:15.148  5655  5784 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,11-24 15:41:15.149  5655  5784 I bt_vendor: epilog_cb
11-24 15:41:15.149  5655  5784 I bt_hci  : epilog_finished_callback
,11-24 15:41:15.152  5655  5780 I bt_hci_h4: hal_close
,11-24 15:41:15.153  5655  5780 I bt_userial_vendor: device fd = 54 close
,11-24 15:41:15.273  5655  5777 D bt_stack_manager: event_shut_down_stack finished.
,11-24 15:41:15.274  5655  5776 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,11-24 15:41:15.278  5655  5776 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
11-24 15:41:15.278  5655  5655 D BtGatt.DebugUtils: handleDebugAction() action=null
11-24 15:41:15.279  5655  5655 D BtGatt.GattService: Received stop request...Stopping profile...
,11-24 15:41:15.279  5655  5655 D BtGatt.GattService: stop()
11-24 15:41:15.280  5655  5655 D BtGatt.AdvertiseManager: advertise clients cleared
,11-24 15:41:15.283  5655  5655 V BluetoothAdapterState: isTurningOff()=false
,11-24 15:41:15.284  5655  5655 V BluetoothAdapterState: isTurningOn()=false
11-24 15:41:15.284  5655  5655 V BluetoothAdapterState: isBleTurningOn()=false
11-24 15:41:15.284  5655  5655 V BluetoothAdapterState: isBleTurningOff()=true
11-24 15:41:15.284  5655  5776 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
11-24 15:41:15.285  5655  5776 D BluetoothAdapterProperties: Setting state to 10
11-24 15:41:15.285  5655  5776 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
11-24 15:41:15.286  5655  5776 I BluetoothAdapterState: Entering OffState
,11-24 15:41:15.287   926   943 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,11-24 15:41:15.301  5655  5655 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,11-24 15:41:15.301  5655  5655 W BluetoothSdpJni: Cleaning up Bluetooth Health object
,11-24 15:41:15.301  5655  5655 I BluetoothServiceJni: cleanupNative: return from cleanup
,11-24 15:41:15.303  5655  5777 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,11-24 15:41:15.310  5655  5655 I art     : System.exit called, status: 0
,11-24 15:41:15.310  5655  5655 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,11-24 15:41:15.348   926  3801 I ActivityManager: Process com.android.bluetooth (pid 5655) has died
,11-24 15:41:18.273  3592  3592 I ConfigService: onDestroy
,11-24 15:41:19.855  5519  5565 D io.jxcore.node.ConnectivityMonitor: stop
11-24 15:41:19.855  5519  5565 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
11-24 15:41:19.860  5519  5565 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-24 15:41:19.861  5519  5565 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@c299407 removed from the list
11-24 15:41:19.861  5519  5565 D io.jxcore.node.ConnectivityMonitor: stop
11-24 15:41:19.863  5519  5565 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,11-24 15:41:19.863  5519  5565 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@89f4d2 added. We now have 4 listener(s)
11-24 15:41:19.864  5519  5565 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-24 15:41:19.865  5519  5565 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-24 15:41:19.868  5519  5565 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@89f4d2 removed from the list
,11-24 15:41:19.868  5519  5565 D io.jxcore.node.ConnectivityMonitor: stop
,11-24 15:41:19.870  5519  5565 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,11-24 15:41:19.870  5519  5565 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@fc169a3 added. We now have 4 listener(s)
,11-24 15:41:19.871  5519  5565 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-24 15:41:23.810   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 15:41:24.812   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 15:41:24.882  5519  5565 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-24 15:41:24.918   926   943 I ActivityManager: Start proc 5823:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,11-24 15:41:24.997  5823  5823 D AdapterServiceConfig: Adding HeadsetService
,11-24 15:41:24.997  5823  5823 D AdapterServiceConfig: Adding A2dpService
11-24 15:41:24.997  5823  5823 D AdapterServiceConfig: Adding HidService
11-24 15:41:24.997  5823  5823 D AdapterServiceConfig: Adding HealthService
11-24 15:41:24.997  5823  5823 D AdapterServiceConfig: Adding PanService
11-24 15:41:24.998  5823  5823 D AdapterServiceConfig: Adding GattService
11-24 15:41:24.998  5823  5823 D AdapterServiceConfig: Adding BluetoothMapService
11-24 15:41:24.998  5823  5823 D AdapterServiceConfig: Adding SapService
,11-24 15:41:25.008   926   943 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@44d17a1:true
,11-24 15:41:25.008  5823  5823 D BluetoothAdapterState: make() - Creating AdapterState
,11-24 15:41:25.011  5823  5823 I bt_bluedroid: init
,11-24 15:41:25.012  5823  5835 I BluetoothAdapterState: Entering OffState
,11-24 15:41:25.014  5823  5836 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
11-24 15:41:25.014  5823  5836 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
11-24 15:41:25.014  5823  5836 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,11-24 15:41:25.014  5823  5836 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
11-24 15:41:25.015  5823  5823 I bt_bluedroid: get_profile_interface socket
,11-24 15:41:25.017  5823  5839 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:D4
11-24 15:41:25.018  5823  5823 I bt_bluedroid: get_profile_interface sdp
11-24 15:41:25.018  5823  5839 D BluetoothAdapterProperties: Name is: Nexus 6P
,11-24 15:41:25.026  5823  5834 I bt_bluedroid: config_hci_snoop_log
,11-24 15:41:25.027   926   943 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
11-24 15:41:25.031  5823  5835 D BluetoothAdapterState: Current state: OFF, message: 0
11-24 15:41:25.031  5823  5835 D BluetoothAdapterProperties: Setting state to 14
11-24 15:41:25.031  5823  5835 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,11-24 15:41:25.033  5823  5835 D BluetoothBondStateMachine: make
,11-24 15:41:25.035  5823  5840 I BluetoothBondStateMachine: StableState(): Entering Off State
,11-24 15:41:25.038  5823  5835 I BluetoothAdapterState: Entering PendingCommandState
,11-24 15:41:25.039  5823  5823 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
11-24 15:41:25.042  5823  5823 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@cf72321
11-24 15:41:25.042  5823  5823 D BtGatt.DebugUtils: handleDebugAction() action=null
,11-24 15:41:25.043  5823  5823 D BtGatt.GattService: Received start request. Starting profile...
11-24 15:41:25.043  5823  5823 D BtGatt.GattService: start()
11-24 15:41:25.043  5823  5823 I bt_bluedroid: get_profile_interface gatt
11-24 15:41:25.044  5823  5823 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@cf72321
11-24 15:41:25.044  5823  5823 D BtGatt.AdvertiseManager: advertise manager created
,11-24 15:41:25.049  5823  5823 V BluetoothAdapterState: isTurningOff()=false
,11-24 15:41:25.049  5823  5823 V BluetoothAdapterState: isTurningOn()=false
11-24 15:41:25.049  5823  5823 V BluetoothAdapterState: isBleTurningOn()=true
11-24 15:41:25.049  5823  5823 V BluetoothAdapterState: isBleTurningOff()=false
,11-24 15:41:25.050  5823  5835 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,11-24 15:41:25.051  5823  5835 I bt_bluedroid: bt_bluedroid
11-24 15:41:25.051  5823  5836 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,11-24 15:41:25.051  5823  5836 I bt_hci  : start_up
,11-24 15:41:25.056  5823  5836 I bt_vendor: alloc value 0xf3de6871
11-24 15:41:25.057  5823  5836 I bt_vendor: init
11-24 15:41:25.057  5823  5836 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
11-24 15:41:25.057  5823  5836 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,11-24 15:41:25.165  5823  5836 D bt_hci  : start_up starting async portion
,11-24 15:41:25.166  5823  5843 I bt_hci  : event_finish_startup
11-24 15:41:25.166  5823  5843 I bt_hci_h4: hal_open
11-24 15:41:25.166  5823  5843 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,11-24 15:41:25.164  5844  5844 W irq/448-msm_hs_: type=1400 audit(0.0:120): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
11-24 15:41:25.168  5823  5843 I bt_userial_vendor: device fd = 54 open
,11-24 15:41:25.182  5823  5843 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,11-24 15:41:25.184  5823  5843 D bt_hwcfg: Chipset BCM4358A3
11-24 15:41:25.184  5823  5843 D bt_hwcfg: Target name = [BCM4358A3]
,11-24 15:41:25.184  5823  5843 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,11-24 15:41:25.697  5823  5843 I bt_hwcfg: bt vendor lib: set UART baud 115200
,11-24 15:41:25.698  5823  5843 D bt_hwcfg: Settlement delay -- 100 ms
11-24 15:41:25.698  5823  5843 I bt_hwcfg: Setting fw settlement delay to 100 
,11-24 15:41:25.814   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 15:41:25.832  5823  5843 I bt_hwcfg: bt vendor lib: set UART baud 3000000
11-24 15:41:25.832  5823  5843 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:D4
11-24 15:41:25.834  5823  5843 I bt_hwcfg: vendor lib fwcfg completed
,11-24 15:41:25.834  5823  5843 I bt_vendor: firmware callback
11-24 15:41:25.834  5823  5843 I bt_hci  : firmware_config_callback
,11-24 15:41:25.844  5823  5846 I bt_btu  : btu_task pending for preload complete event
11-24 15:41:25.845  5823  5846 I bt_btu_task: Bluetooth chip preload is complete
,11-24 15:41:25.845  5823  5846 I bt_btu  : btu_task received preload complete event
,11-24 15:41:25.852  5823  5846 I         : BTE_InitTraceLevels -- TRC_HCI
,11-24 15:41:25.852  5823  5846 I         : BTE_InitTraceLevels -- TRC_L2CAP
11-24 15:41:25.853  5823  5846 I         : BTE_InitTraceLevels -- TRC_RFCOMM
11-24 15:41:25.853  5823  5846 I         : BTE_InitTraceLevels -- TRC_AVDT
11-24 15:41:25.853  5823  5846 I         : BTE_InitTraceLevels -- TRC_AVRC
,11-24 15:41:25.853  5823  5846 I         : BTE_InitTraceLevels -- TRC_A2D
11-24 15:41:25.853  5823  5846 I         : BTE_InitTraceLevels -- TRC_BNEP
11-24 15:41:25.853  5823  5846 I         : BTE_InitTraceLevels -- TRC_BTM
,11-24 15:41:25.853  5823  5846 I         : BTE_InitTraceLevels -- TRC_GAP
,11-24 15:41:25.854  5823  5846 I         : BTE_InitTraceLevels -- TRC_PAN
11-24 15:41:25.854  5823  5846 I         : BTE_InitTraceLevels -- TRC_SDP
,11-24 15:41:25.854  5823  5846 I         : BTE_InitTraceLevels -- TRC_GATT
11-24 15:41:25.854  5823  5846 I         : BTE_InitTraceLevels -- TRC_SMP
11-24 15:41:25.854  5823  5846 I         : BTE_InitTraceLevels -- TRC_BTAPP
,11-24 15:41:25.854  5823  5846 I         : BTE_InitTraceLevels -- TRC_BTIF
,11-24 15:41:25.948  5823  5846 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf3d64549
,11-24 15:41:25.948  5823  5846 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf3d64549 
,11-24 15:41:25.977  5823  5839 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,11-24 15:41:25.980  5823  5839 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
11-24 15:41:25.981  5823  5839 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:D4
11-24 15:41:25.985  5823  5839 D BluetoothAdapterProperties: Name is: Nexus 6P
,11-24 15:41:25.988  5823  5839 D BluetoothAdapterProperties: Scan Mode:20
11-24 15:41:25.988  5823  5839 D BluetoothAdapterProperties: Discoverable Timeout:120
11-24 15:41:25.989  5823  5839 D bt_hci  : do_postload posting postload work item
,11-24 15:41:25.989  5823  5843 I bt_hci  : event_postload
11-24 15:41:25.989  5823  5843 I bt_vendor: sco_config_cb
11-24 15:41:25.989  5823  5843 I bt_hci  : sco_config_callback postload finished.
11-24 15:41:25.992  5823  5839 D bt_bte_conf: Device ID record 1 : primary
11-24 15:41:25.992  5823  5839 D bt_bte_conf:   vendorId            = 000f
,11-24 15:41:25.992  5823  5839 D bt_bte_conf:   vendorIdSource      = 0001
11-24 15:41:25.992  5823  5839 D bt_bte_conf:   product             = 1200
11-24 15:41:25.992  5823  5839 D bt_bte_conf:   version             = 1436
11-24 15:41:25.992  5823  5839 D bt_bte_conf:   clientExecutableURL = 
,11-24 15:41:25.992  5823  5839 D bt_bte_conf:   serviceDescription  = 
,11-24 15:41:25.992  5823  5839 D bt_bte_conf:   documentationURL    = 
11-24 15:41:25.992  5823  5839 D bt_bte_conf: bte_load_did_conf no section named DID2.
11-24 15:41:25.993  5823  5836 D bt_stack_manager: event_start_up_stack finished
11-24 15:41:25.993  5823  5835 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
,11-24 15:41:25.994  5823  5835 D BluetoothAdapterProperties: Setting state to 15
11-24 15:41:25.994  5823  5835 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
11-24 15:41:25.995  5823  5835 I BluetoothAdapterState: Entering BleOnState
11-24 15:41:25.997  5823  5843 I bt_vendor: low_power_mode_cb
,11-24 15:41:26.001  5823  5835 D BluetoothAdapterState: Current state: BLE ON, message: 1
11-24 15:41:26.001  5823  5835 D BluetoothAdapterProperties: Setting state to 11
,11-24 15:41:26.001  5823  5835 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,11-24 15:41:26.011  5823  5823 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@cf72321
,11-24 15:41:26.012  5823  5823 D HeadsetService: Received start request. Starting profile...
,11-24 15:41:26.014  5823  5823 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,11-24 15:41:26.015  5823  5823 D HeadsetStateMachine: make
,11-24 15:41:26.027  5823  5835 I BluetoothAdapterState: Entering PendingCommandState
11-24 15:41:26.028  5823  5823 D HeadsetStateMachine: max_hf_connections = 1
,11-24 15:41:26.028  5823  5823 I bt_bluedroid: get_profile_interface handsfree
11-24 15:41:26.028  5823  5839 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
11-24 15:41:26.029  5823  5839 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
11-24 15:41:26.032  5823  5823 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@cf72321
,11-24 15:41:26.034  3592  3592 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
11-24 15:41:26.035  5823  5823 D A2dpService: Received start request. Starting profile...
,11-24 15:41:26.035  5823  5823 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,11-24 15:41:26.036  5823  5823 I bt_bluedroid: get_profile_interface avrcp
,11-24 15:41:26.042  5823  5823 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
11-24 15:41:26.043  5823  5823 I BluetoothA2dpServiceJni: classInitNative: succeeds
,11-24 15:41:26.043  5823  5823 D A2dpStateMachine: make
,11-24 15:41:26.044  5823  5823 I bt_bluedroid: get_profile_interface a2dp
,11-24 15:41:26.045  5823  5839 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,11-24 15:41:26.046  5823  5854 D A2dpStateMachine: Enter Disconnected: -2
,11-24 15:41:26.047  5823  5823 I BluetoothHidServiceJni: classInitNative: succeeds,
,11-24 15:41:26.048  5823  5823 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@cf72321
11-24 15:41:26.049  5823  5823 D HidService: Received start request. Starting profile...
11-24 15:41:26.049  5823  5823 I bt_bluedroid: get_profile_interface hidhost
11-24 15:41:26.049  5823  5823 D HidService: setHidService(): set to: null
,11-24 15:41:26.049  5823  5839 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf3d4556d
11-24 15:41:26.049  5823  5839 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
11-24 15:41:26.050  5823  5823 I BluetoothHealthServiceJni: classInitNative: succeeds
11-24 15:41:26.051  5823  5823 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@cf72321
11-24 15:41:26.052  5823  5823 D HealthService: Received start request. Starting profile...
,11-24 15:41:26.054  5823  5823 I bt_bluedroid: get_profile_interface health
11-24 15:41:26.055  5823  5823 I BluetoothPanServiceJni: classInitNative(L105): succeeds
11-24 15:41:26.055  5823  5823 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@cf72321
,11-24 15:41:26.056  5823  5823 D PanService: Received start request. Starting profile...
,11-24 15:41:26.056  5823  5823 D BluetoothPanServiceJni: initializeNative(L110): pan
11-24 15:41:26.056  5823  5823 I bt_bluedroid: get_profile_interface pan
11-24 15:41:26.057  5823  5839 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,11-24 15:41:26.058  5823  5823 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@cf72321
11-24 15:41:26.059  5823  5823 D BluetoothMapService: Received start request. Starting profile...
11-24 15:41:26.059  5823  5823 D BluetoothMapService: start()
11-24 15:41:26.061  5823  5823 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
11-24 15:41:26.062  5823  5823 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
11-24 15:41:26.062  5823  5823 D BluetoothMapAppObserver: createReceiver()
,11-24 15:41:26.064  5823  5823 D BluetoothMapAppObserver: initObservers()
11-24 15:41:26.064  5823  5823 D BluetoothMapAppObserver: getEnabledAccountItems()
,11-24 15:41:26.071  5823  5823 V SapService: SapBinder()
,11-24 15:41:26.071  5823  5823 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@cf72321
11-24 15:41:26.071  5823  5823 D SapService: Received start request. Starting profile...
11-24 15:41:26.071  5823  5823 V SapService: start()
11-24 15:41:26.073  5823  5823 V BluetoothAdapterState: isTurningOff()=false
11-24 15:41:26.073  5823  5823 V BluetoothAdapterState: isTurningOn()=true
11-24 15:41:26.073  5823  5823 V BluetoothAdapterState: isBleTurningOn()=false
11-24 15:41:26.073  5823  5852 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
11-24 15:41:26.073  5823  5823 V BluetoothAdapterState: isBleTurningOff()=false
11-24 15:41:26.073  5823  5823 V BluetoothAdapterState: isTurningOff()=false
11-24 15:41:26.073  5823  5823 V BluetoothAdapterState: isTurningOn()=true
11-24 15:41:26.073  5823  5823 V BluetoothAdapterState: isBleTurningOn()=false
11-24 15:41:26.073  5823  5823 V BluetoothAdapterState: isBleTurningOff()=false
11-24 15:41:26.074  5823  5823 V BluetoothAdapterState: isTurningOff()=false
11-24 15:41:26.074  5823  5823 V BluetoothAdapterState: isTurningOn()=true
11-24 15:41:26.074  5823  5823 V BluetoothAdapterState: isBleTurningOn()=false
11-24 15:41:26.074  5823  5823 V BluetoothAdapterState: isBleTurningOff()=false
11-24 15:41:26.074  5823  5823 V BluetoothAdapterState: isTurningOff()=false
11-24 15:41:26.074  5823  5823 V BluetoothAdapterState: isTurningOn()=true
11-24 15:41:26.074  5823  5823 V BluetoothAdapterState: isBleTurningOn()=false
11-24 15:41:26.074  5823  5823 V BluetoothAdapterState: isBleTurningOff()=false
11-24 15:41:26.075  5823  5823 V BluetoothAdapterState: isTurningOff()=false
11-24 15:41:26.075  5823  5823 V BluetoothAdapterState: isTurningOn()=true
11-24 15:41:26.075  5823  5823 V BluetoothAdapterState: isBleTurningOn()=false
11-24 15:41:26.075  5823  5823 V BluetoothAdapterState: isBleTurningOff()=false
11-24 15:41:26.075  5823  5823 V BluetoothAdapterState: isTurningOff()=false
11-24 15:41:26.075  5823  5823 V BluetoothAdapterState: isTurningOn()=true
,11-24 15:41:26.076  5823  5823 V BluetoothAdapterState: isBleTurningOn()=false
11-24 15:41:26.076  5823  5823 V BluetoothAdapterState: isBleTurningOff()=false
11-24 15:41:26.076  5823  5823 V BluetoothAdapterState: isTurningOff()=false
11-24 15:41:26.076  5823  5823 V BluetoothAdapterState: isTurningOn()=true
11-24 15:41:26.076  5823  5823 V BluetoothAdapterState: isBleTurningOn()=false
11-24 15:41:26.077  5823  5823 V BluetoothAdapterState: isBleTurningOff()=false
11-24 15:41:26.077  5823  5835 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
11-24 15:41:26.077  5823  5835 D BluetoothAdapterProperties: ScanMode =  20
,11-24 15:41:26.077  5823  5835 D BluetoothAdapterProperties: State =  11
11-24 15:41:26.077  5823  5835 D BluetoothAdapterProperties: Setting state to 12
11-24 15:41:26.077  5823  5835 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
11-24 15:41:26.078  3141  3153 D BluetoothPan: onBluetoothStateChange on: true
11-24 15:41:26.078  5823  5839 D BluetoothAdapterProperties: Scan Mode:21
11-24 15:41:26.078  5823  5839 D BluetoothAdapterProperties: Discoverable Timeout:120
11-24 15:41:26.078  5823  5835 I BluetoothAdapterState: Entering OnState
11-24 15:41:26.079   926   943 D BluetoothA2dp: onBluetoothStateChange: up=true
11-24 15:41:26.080  5590  5603 D BluetoothPan: onBluetoothStateChange on: true
11-24 15:41:26.081  3141  3141 D BluetoothPan: BluetoothPAN Proxy object connected
11-24 15:41:26.081  3141  3141 D PanProfile: Bluetooth service connected
11-24 15:41:26.082   926   926 D BluetoothA2dp: Proxy object connected
11-24 15:41:26.082  5590  5606 D BluetoothMap: onBluetoothStateChange: up=true
11-24 15:41:26.084  5590  5603 D BluetoothA2dp: onBluetoothStateChange: up=true
,11-24 15:41:26.086   926   943 D BluetoothHeadset: onBluetoothStateChange: up=true
11-24 15:41:26.086  3141  4171 D BluetoothMap: onBluetoothStateChange: up=true
,11-24 15:41:26.087  3141  3141 D BluetoothMap: Proxy object connected
11-24 15:41:26.087  3774  4026 D BluetoothHeadset: onBluetoothStateChange: up=true
11-24 15:41:26.087  3141  3141 D MapProfile: Bluetooth service connected
11-24 15:41:26.087  3141  3141 D BluetoothMap: getConnectedDevices()
11-24 15:41:26.088  5590  5606 D BluetoothHeadset: onBluetoothStateChange: up=true
11-24 15:41:26.088  5590  5603 D BluetoothInputDevice: onBluetoothStateChange: up=true
11-24 15:41:26.089  5823  5823 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
11-24 15:41:26.090  5823  5823 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
11-24 15:41:26.090  3141  3156 D BluetoothPbap: onBluetoothStateChange: up=true
11-24 15:41:26.091  5823  5823 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-24 15:41:26.091  3141  4171 D BluetoothA2dp: onBluetoothStateChange: up=true
11-24 15:41:26.092  5590  5590 D BluetoothPan: BluetoothPAN Proxy object connected
11-24 15:41:26.092  5590  5590 D PanProfile: Bluetooth service connected
11-24 15:41:26.092  5590  5590 D BluetoothMap: Proxy object connected
11-24 15:41:26.092  5590  5590 D MapProfile: Bluetooth service connected
11-24 15:41:26.092  5590  5590 D BluetoothMap: getConnectedDevices()
11-24 15:41:26.092  5823  5823 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-24 15:41:26.093  5823  5823 D ObexServerSockets: Succeed to create listening sockets 
,11-24 15:41:26.093   926   943 D BluetoothHeadset: onBluetoothStateChange: up=true
11-24 15:41:26.093  5823  5823 D ObexServerSockets0: startAccept()
11-24 15:41:26.093  5823  5823 D ObexServerSockets0: prepareForNewConnect()
11-24 15:41:26.094  3141  3156 D BluetoothInputDevice: onBluetoothStateChange: up=true
11-24 15:41:26.094  3141  3141 D BluetoothA2dp: Proxy object connected
11-24 15:41:26.095   926   943 D BluetoothHeadset: onBluetoothStateChange: up=true
11-24 15:41:26.095  5590  5606 D BluetoothPbap: onBluetoothStateChange: up=true
11-24 15:41:26.095  5823  5823 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
11-24 15:41:26.095  5823  5823 D BluetoothSdpJni: SDP Create record success - handle: 0
11-24 15:41:26.096  5823  5860 D ObexServerSockets0: Accepting socket connection...
11-24 15:41:26.096  5823  5861 D ObexServerSockets0: Accepting socket connection...
11-24 15:41:26.097  3141  3141 D BluetoothInputDevice: Proxy object connected
,11-24 15:41:26.097  3141  3141 D HidProfile: Bluetooth service connected
11-24 15:41:26.097  3141  3153 D BluetoothHeadset: onBluetoothStateChange: up=true
,11-24 15:41:26.099  5590  5590 D BluetoothA2dp: Proxy object connected
11-24 15:41:26.100   926   926 I Telecom : BluetoothPhoneService: queryPhoneState
11-24 15:41:26.100  5823  5823 D BluetoothMapService: onReceive
11-24 15:41:26.101  5823  5823 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
11-24 15:41:26.101  5823  5823 D BluetoothMapService: STATE_ON
,11-24 15:41:26.102  5590  5590 D BluetoothInputDevice: Proxy object connected
11-24 15:41:26.102  5590  5590 D HidProfile: Bluetooth service connected
,11-24 15:41:26.104  5823  5862 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-24 15:41:26.106  5823  5862 D BluetoothSdpJni: sdpCreateSapsRecordNative:
,11-24 15:41:26.106  5823  5862 D BluetoothSdpJni: SDP Create record success - handle: 1
,11-24 15:41:26.109  5590  5590 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,11-24 15:41:26.115  5590  5590 D DockEventReceiver: finishStartingService: stopping service
,11-24 15:41:26.115  3592  3592 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,11-24 15:41:26.127  5590  5590 D BluetoothPbap: Proxy object connected
11-24 15:41:26.127  5590  5590 D PbapServerProfile: Bluetooth service connected
,11-24 15:41:26.128  3141  3141 D BluetoothPbap: Proxy object connected
11-24 15:41:26.129  3141  3141 D PbapServerProfile: Bluetooth service connected
,11-24 15:41:26.131  5823  5823 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
11-24 15:41:26.131  5823  5823 D ObexServerSockets0: prepareForNewConnect()
,11-24 15:41:26.133  5823  5868 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-24 15:41:26.147  5823  5872 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-24 15:41:26.149  5823  5872 I BtOppRfcommListener: Accept thread started.
,11-24 15:41:26.187   926   926 D BluetoothHeadset: Proxy object connected
,11-24 15:41:26.187  5590  5606 D BluetoothHeadset: Proxy object connected
11-24 15:41:26.187  3774  3788 D BluetoothHeadset: Proxy object connected
11-24 15:41:26.188  3141  4171 D BluetoothHeadset: Proxy object connected
11-24 15:41:26.188  3141  3141 D HeadsetProfile: Bluetooth service connected
11-24 15:41:26.188  3774  3795 D BluetoothHeadset: Proxy object connected
11-24 15:41:26.188   926   926 D BluetoothHeadset: Proxy object connected
11-24 15:41:26.188   926   926 D BluetoothHeadset: Proxy object connected
,11-24 15:41:26.189  5590  5603 D BluetoothHeadset: Proxy object connected
,11-24 15:41:26.190  5590  5590 D HeadsetProfile: Bluetooth service connected
11-24 15:41:26.191  5590  5590 D HeadsetProfile: Bluetooth service connected
,11-24 15:41:26.194   926   943 D BluetoothHeadset: Proxy object connected
,11-24 15:41:26.196   926   943 D BluetoothHeadset: Proxy object connected
,11-24 15:41:26.197  3141  3156 D BluetoothHeadset: Proxy object connected
,11-24 15:41:26.198  3141  3141 D HeadsetProfile: Bluetooth service connected
,11-24 15:41:26.815   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 15:41:27.816   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 15:41:28.817   535   535 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,11-24 15:41:29.898  5519  5565 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-24 15:41:29.898  5519  5565 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-24 15:41:29.898  5519  5565 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-24 15:41:29.898  5519  5565 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-24 15:41:29.898  5519  5565 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-24 15:41:29.898  5519  5565 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-24 15:41:29.898  5519  5565 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-24 15:41:29.898  5519  5565 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-24 15:41:29.898  5519  5565 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,11-24 15:41:29.904  5519  5565 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
,11-24 15:41:29.905  5519  5565 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-24 15:41:29.905  5519  5565 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@fc169a3 removed from the list
11-24 15:41:29.905  5519  5565 D io.jxcore.node.ConnectivityMonitor: stop
11-24 15:41:29.907  5519  5565 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,11-24 15:41:29.907  5519  5565 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@a9bd4a0 added. We now have 4 listener(s)
11-24 15:41:29.908  5519  5565 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-24 15:41:29.911   926  3803 D WifiService: setWifiEnabled: false pid=5519, uid=10077
11-24 15:41:29.911   926  3803 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-24 15:41:33.290  3934  4473 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,11-24 15:41:34.923  5519  5565 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-24 15:41:34.923   926  4813 D WifiService: setWifiEnabled: true pid=5519, uid=10077
,11-24 15:41:34.924   926  4813 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-24 15:41:34.932   507   920 D SoftapController: Softap fwReload - Ok
,11-24 15:41:34.937   507   920 D CommandListener: Setting iface cfg
11-24 15:41:34.937   507   920 D CommandListener: Trying to bring down wlan0
11-24 15:41:34.939   507   920 D CommandListener: Clearing all IP addresses on wlan0
,11-24 15:41:34.947   926  2973 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,11-24 15:41:35.623   926  2973 D wifi    : set interface wlan0 flags (UP)
,11-24 15:41:35.625   926  2973 I WifiHAL : Initializing wifi
11-24 15:41:35.625   926  2973 I WifiHAL : Creating socket
,11-24 15:41:35.630   926   943 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,11-24 15:41:35.632   926  2973 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
,11-24 15:41:35.633   926  2973 D wifi    : Did set static halHandle = 0x7f6f9fbf80
,11-24 15:41:35.633   926  2973 D wifi    : halHandle = 0x7f6f9fbf80, mVM = 0x7f8a50d140, mCls = 0x154a
,11-24 15:41:35.633   926  2973 D wifi    : array field set
11-24 15:41:35.633   926  2973 I WifiNative-HAL: interface[0] = wlan0
,11-24 15:41:35.636   926  5877 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=547333586816
11-24 15:41:35.636   926  5877 D wifi    : waitForHalEvents called, vm = 0x7f8a50d140, obj = 0x154a, env = 0x7f72ce0d00
,11-24 15:41:35.692  5878  5878 I wpa_supplicant: Successfully initialized wpa_supplicant
,11-24 15:41:35.737   926  2973 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,11-24 15:41:35.765  5878  5878 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,11-24 15:41:35.853  5878  5878 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,11-24 15:41:35.853  5878  5878 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,11-24 15:41:35.880   926  2973 D WifiConfigStore: Loading config and enabling all networks 
,11-24 15:41:35.911   926  2973 D WifiConfigStore: loaded 0 passpoint configs
,11-24 15:41:35.912   926  2973 W WifiConfigStore: Upgrading network 4 to android.uid.system:1000
,11-24 15:41:35.913   926  2973 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,11-24 15:41:35.913   926  2973 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,11-24 15:41:35.914   926  2973 W WifiConfigStore: Upgrading network 3 to android.uid.system:1000
,11-24 15:41:35.915   926  2973 W WifiConfigStore: Upgrading network 2 to android.uid.system:1000
,11-24 15:41:35.916   926  2973 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
11-24 15:41:35.916   926  2973 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 5
11-24 15:41:35.916   926  2973 E WifiConfigStore: found sortedWifiConfigurations : "AndroidAP"WPA_PSK
11-24 15:41:35.916   926  2973 E WifiConfigStore: found sortedWifiConfigurations : "AndroidHotspot2346"WPA_PSK
11-24 15:41:35.916   926  2973 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
11-24 15:41:35.916   926  2973 E WifiConfigStore: found sortedWifiConfigurations : "Thali_internal"WPA_PSK
,11-24 15:41:35.916   926  2973 E WifiConfigStore: found sortedWifiConfigurations : "MC"WPA_PSK
,11-24 15:41:35.918   926  2973 D WifiNative-HAL: Setting external_sim to 1
,11-24 15:41:35.919   926  2973 D wifi    : setting dfs flag to true, 0x7f727a0140
11-24 15:41:35.919   926  2973 D WifiStateMachine: Setting OUI to DA-A1-19
11-24 15:41:35.919   926  2973 D wifi    : setting scan oui 0x7f727a0140
11-24 15:41:35.919   926  2973 D WifiHAL : Sending mac address OUI
11-24 15:41:35.919  4817  4817 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,11-24 15:41:35.923   926  2973 E native  : do suspend false
,11-24 15:41:35.934   926  2973 D wifi    : android_net_wifi_setLinkLayerStats: 1
,11-24 15:41:35.934   926   926 D RttService: SCAN_AVAILABLE : 3
11-24 15:41:35.935   507   920 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
11-24 15:41:35.935   926  3083 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
11-24 15:41:35.936   507   920 D CommandListener: Setting iface cfg
,11-24 15:41:35.940   926  2972 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '158 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 158 Failed to set address (No such device)'
,11-24 15:41:35.941   926  2972 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,11-24 15:41:35.950   926  2972 D WifiNative-HAL: p2pGetDeviceAddress
,11-24 15:41:35.951   926  2972 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:70
,11-24 15:41:35.957   926   941 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=155265 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=16 mControllerEnergyUsed=60 }
,11-24 15:41:39.015  5878  5878 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-24 15:41:39.023  5878  5878 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-24 15:41:39.029  5878  5878 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-24 15:41:39.050   926  2973 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,11-24 15:41:39.051   926  2973 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3
11-24 15:41:39.051   926  2973 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-24 15:41:39.062   926  2973 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=0
,11-24 15:41:39.094   926  2973 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=0
,11-24 15:41:39.099  5878  5878 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,11-24 15:41:39.520  5878  5878 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,11-24 15:41:39.553  5878  5878 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,11-24 15:41:39.554  5878  5878 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,11-24 15:41:39.562   926  2973 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,11-24 15:41:39.563   926  2973 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-24 15:41:39.563   926  2975 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,11-24 15:41:39.583   926  2973 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-24 15:41:39.596   507   920 D CommandListener: Setting iface cfg
,11-24 15:41:39.601   926  2973 D WifiStateMachine: Start Dhcp Watchdog 3
,11-24 15:41:39.607   926  5883 D DhcpClient: Receive thread started
,11-24 15:41:39.613   926  2973 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,11-24 15:41:39.613   926  2975 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-24 15:41:39.613   926  2975 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 102] to 60
,11-24 15:41:39.693   926  2973 E native  : do suspend false
,11-24 15:41:39.704   926  5882 D DhcpClient: Broadcasting DHCPDISCOVER
,11-24 15:41:39.717   926  5883 D DhcpClient: Received packet: 60:83:34:25:d7:70 OFFER, ip /192.168.1.109, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172765, domain null
,11-24 15:41:39.719   926  5882 D DhcpClient: Got pending lease: IP address 192.168.1.109/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172765 seconds
,11-24 15:41:39.723   926  5882 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.109 serverid=192.168.1.1
,11-24 15:41:39.735   926  5883 D DhcpClient: Received packet: 60:83:34:25:d7:70 ACK: your new IP /192.168.1.109, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,11-24 15:41:39.736   926  5882 D DhcpClient: Confirmed lease: IP address 192.168.1.109/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,11-24 15:41:39.740   507   920 D CommandListener: Setting iface cfg
,11-24 15:41:39.745   926  2973 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,11-24 15:41:39.749   926  5882 D DhcpClient: Scheduling renewal in 86399s
,11-24 15:41:39.757   926  2973 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,11-24 15:41:39.758   926  2973 D WifiConfigStore: No blacklist allowed without epno enabled
,11-24 15:41:39.759   926  2975 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
11-24 15:41:39.762   926  2973 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
11-24 15:41:39.762   926  2975 D ConnectivityService: Adding iface wlan0 to network 102
,11-24 15:41:39.815   926  2975 E ConnectivityService: Unexpected mtu value: 0, wlan0
11-24 15:41:39.815   926  2975 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
,11-24 15:41:39.818   926  2975 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
,11-24 15:41:39.822   926  2975 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
,11-24 15:41:39.824   926  2975 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
,11-24 15:41:39.832   926  2975 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-24 15:41:39.837   926  2975 D ConnectivityService: scheduleUnvalidatedPrompt 102
,11-24 15:41:39.837   926  2975 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 102]
,11-24 15:41:39.837   926  2975 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 102]
11-24 15:41:39.838   926  2973 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
11-24 15:41:39.838   926  2975 D ConnectivityService:    accepting network in place of null
,11-24 15:41:39.838   926  2973 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
11-24 15:41:39.839   926  2975 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d770/64,192.168.1.109/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -49]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,11-24 15:41:39.866   507   920 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-24 15:41:39.885   926  5881 D NetlinkSocketObserver: NeighborEvent{elapsedMs=159193, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,11-24 15:41:39.892   507   920 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-24 15:41:39.895   926  2975 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
,11-24 15:41:39.895   926  2975 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,11-24 15:41:39.895  3740  3887 W QCNEJ   : |CORE| network available: 102
,11-24 15:41:39.896   926  2975 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
11-24 15:41:39.898   926   943 D Tethering: MasterInitialState.processMessage what=3
,11-24 15:41:39.899  3740  3887 W QCNEJ   : |CORE| onAvailable: bind the process to WIFI
,11-24 15:41:39.900  3740  3887 W QCNEJ   : |CORE| newLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d770/64,192.168.1.109/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}
11-24 15:41:39.901  3740  3887 W QCNEJ   : |CORE| curLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d770/64,192.168.1.109/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,11-24 15:41:39.916  3947  3947 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
,11-24 15:41:39.919  4859  4896 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
,11-24 15:41:39.920  4073  4073 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
11-24 15:41:39.921  4859  4896 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
11-24 15:41:39.921  4859  4896 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,1,0,0
11-24 15:41:39.921  4859  4896 E SarControlService: no key has been found,reset the power
11-24 15:41:39.921  4859  4922 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
11-24 15:41:39.921  4859  4922 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
,11-24 15:41:39.922  4859  4922 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
11-24 15:41:39.922  4909  4909 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
11-24 15:41:39.922  4909  4909 D QcrilMsgTunnelSocket: [1008] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
11-24 15:41:39.923  4859  4922 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
11-24 15:41:39.923  4859  4922 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
11-24 15:41:39.923  4859  4922 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
11-24 15:41:39.923  4909  4909 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
11-24 15:41:39.923  4909  4909 D QcrilMsgTunnelSocket: [1009] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
,11-24 15:41:39.927  4073  4073 D SystemUpdateService: onCreate
,11-24 15:41:39.930  4909  4926 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@92f9857 HexData = [00000000f003000000000000ffffffff]
11-24 15:41:39.931  4909  4926 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-24 15:41:39.931  4909  4926 D QcrilMsgTunnelSocket: [1008] < OEM_HOOK_RAW [null]
11-24 15:41:39.931  4909  4909 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
11-24 15:41:39.931  4859  4870 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
,11-24 15:41:39.932  4073  4073 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
11-24 15:41:39.933  4909  4926 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@92f9857 HexData = [00000000f103000000000000ffffffff]
11-24 15:41:39.933  4909  4926 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-24 15:41:39.933  4909  4926 D QcrilMsgTunnelSocket: [1009] < OEM_HOOK_RAW [null]
11-24 15:41:39.933  4909  4909 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
11-24 15:41:39.934  4859  4869 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
,11-24 15:41:39.936  5519  5565 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-24 15:41:39.936  5519  5565 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-24 15:41:39.936  5519  5565 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-24 15:41:39.936  5519  5565 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-24 15:41:39.936  5519  5565 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-24 15:41:39.936  5519  5565 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-24 15:41:39.936  5519  5565 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-24 15:41:39.936  5519  5565 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-24 15:41:39.936  5519  5565 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,11-24 15:41:39.939  5519  5565 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
,11-24 15:41:39.940  5519  5565 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 15:41:39.940  5519  5565 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@a9bd4a0 removed from the list
11-24 15:41:39.940  5519  5565 D io.jxcore.node.ConnectivityMonitor: stop
11-24 15:41:39.943  5519  5565 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
11-24 15:41:39.944  5519  5565 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,11-24 15:41:39.945  4073  4073 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,11-24 15:41:39.947  5519  5565 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@6a93a34 Bundle[{}]
11-24 15:41:39.947  5519  5565 I io.jxcore.node.LifeCycleMonitor: start: OK
11-24 15:41:39.947  5519  5565 I io.jxcore.node.LifeCycleMonitor: stop: OK
11-24 15:41:39.948  5519  5565 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,11-24 15:41:39.950  5519  5565 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,11-24 15:41:39.951  4073  5319 I iu.UploadsManager: num queued entries: 0
11-24 15:41:39.951  5519  5565 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
11-24 15:41:39.951  4073  5319 I iu.UploadsManager: num updated entries: 0
11-24 15:41:39.951  5519  5565 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,11-24 15:41:39.953   926  5880 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=172.217.22.110,2a00:1450:4001:81d::200e
,11-24 15:41:39.953  4073  5895 I SystemUpdateService: active receiver: enabled
,11-24 15:41:39.957  5519  5565 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 164)
,11-24 15:41:39.957  5519  5565 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
11-24 15:41:39.957  5519  5565 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 165)
,11-24 15:41:39.959  5519  5565 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,11-24 15:41:39.959  5519  5565 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2e27859 added. We now have 3 listener(s)
,11-24 15:41:39.961  4073  4073 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,11-24 15:41:39.961  5519  5565 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-24 15:41:39.961  5519  5565 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-24 15:41:39.961  5519  5565 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-24 15:41:39.961  5519  5565 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-24 15:41:39.961  5519  5565 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8ee8c1e added. We now have 4 listener(s)
,11-24 15:41:39.961  5519  5565 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-24 15:41:39.962  5519  5565 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
11-24 15:41:39.962  4073  4073 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
11-24 15:41:39.963  5519  5565 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-24 15:41:39.963  5519  5565 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@976fcff added. We now have 4 listener(s)
11-24 15:41:39.963  5669  5669 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
11-24 15:41:39.965  5519  5565 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-24 15:41:39.965  5519  5565 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,11-24 15:41:39.965  5519  5565 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-24 15:41:39.965  5519  5565 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-24 15:41:39.965  5519  5565 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4f99acc added. We now have 5 listener(s)
11-24 15:41:39.965  5519  5565 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-24 15:41:39.965  5519  5565 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-24 15:41:39.965  5519  5565 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,11-24 15:41:39.966  5519  5565 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-24 15:41:39.966  5519  5565 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-24 15:41:39.966  5519  5565 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 15:41:39.966  5519  5565 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-24 15:41:39.966  5519  5565 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2e27859 removed from the list
11-24 15:41:39.966  5519  5565 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 15:41:39.966  5519  5565 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8ee8c1e removed from the list
,11-24 15:41:39.966  5519  5565 D io.jxcore.node.ConnectivityMonitor: stop
11-24 15:41:39.966  5519  5565 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-57,5,main], id: 57
11-24 15:41:39.966  5519  5565 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
11-24 15:41:39.967  5519  5565 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
11-24 15:41:39.968  5519  5565 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
11-24 15:41:39.968  5519  5565 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
11-24 15:41:39.968  5519  5565 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,11-24 15:41:39.968  5519  5565 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-24 15:41:39.968  5519  5565 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 15:41:39.968  5669  5669 D SprintDMHelper: simOperator: 
11-24 15:41:39.968  5669  5669 D SprintDMReceiver: Not Sprint UICC, don't do anything.
11-24 15:41:39.968  5519  5565 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8ee8c1e not in the list
11-24 15:41:39.968  5519  5565 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-57,5,main], id: 57
11-24 15:41:39.968  5519  5565 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
,11-24 15:41:39.969  5519  5565 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
11-24 15:41:39.969  5519  5565 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
11-24 15:41:39.970  5519  5565 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
11-24 15:41:39.970  5519  5565 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-24 15:41:39.970  5519  5565 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-24 15:41:39.970  5519  5565 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 15:41:39.970  5519  5565 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4f99acc removed from the list
11-24 15:41:39.970  5519  5565 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-24 15:41:39.970  5519  5565 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 15:41:39.970  5519  5565 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,11-24 15:41:39.970  5519  5565 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@976fcff removed from the list
11-24 15:41:39.971  5519  5565 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-24 15:41:39.971  5519  5565 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1394115 added. We now have 3 listener(s)
11-24 15:41:39.972  5519  5565 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-24 15:41:39.972  5519  5565 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-24 15:41:39.972  5519  5565 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-24 15:41:39.972  5519  5565 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-24 15:41:39.972  5519  5565 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2734c2a added. We now have 4 listener(s)
11-24 15:41:39.972  5519  5565 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-24 15:41:39.973  5519  5565 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
11-24 15:41:39.973  5519  5565 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-24 15:41:39.973  5519  5565 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ec86a1b added. We now have 4 listener(s)
11-24 15:41:39.974  5519  5565 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-24 15:41:39.974  5519  5565 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-24 15:41:39.974  5519  5565 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-24 15:41:39.974  5519  5565 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-24 15:41:39.974  5519  5565 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@78b97b8 added. We now have 5 listener(s)
11-24 15:41:39.974  5519  5565 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-24 15:41:39.975  5519  5565 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-24 15:41:39.975  5519  5565 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
11-24 15:41:39.975  5519  5565 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
11-24 15:41:39.975  5519  5565 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-24 15:41:39.975  5519  5565 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
,11-24 15:41:39.977  5519  5565 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,11-24 15:41:39.978  4073  5895 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,11-24 15:41:39.981  5519  5565 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-24 15:41:39.981  5519  5565 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-24 15:41:39.981  5519  5565 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,11-24 15:41:39.983  5519  5565 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-57,5,main], id: 57
,11-24 15:41:39.983  5519  5565 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-24 15:41:39.984  5519  5565 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-24 15:41:39.984  5519  5565 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-24 15:41:39.984  5519  5565 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 0
,11-24 15:41:39.986  5519  5565 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-57,5,main], id: 57
,11-24 15:41:39.986  5519  5565 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
11-24 15:41:39.986  5519  5565 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
11-24 15:41:39.986  5519  5565 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
11-24 15:41:39.986  5519  5565 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
11-24 15:41:39.986  5519  5565 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-57,5,main], id: 57
,11-24 15:41:39.987  5519  5565 D BluetoothAdapter: STATE_ON
,11-24 15:41:39.989  5823  5864 D BtGatt.GattService: registerClient() - UUID=ae90562b-8201-45f5-8d89-65299fff7128
,11-24 15:41:39.989  5823  5839 D BtGatt.GattService: onClientRegistered() - UUID=ae90562b-8201-45f5-8d89-65299fff7128, clientIf=5
11-24 15:41:39.990  5519  5529 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,11-24 15:41:39.991  5823  5851 D BtGatt.GattService: start scan with filters
,11-24 15:41:39.977  4073  5319 I iu.SyncManager: NEXT; no task
11-24 15:41:39.992  4073  5895 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
11-24 15:41:39.992  4073  5895 I SystemUpdateService: now status is 0 (complete)
11-24 15:41:39.992  4073  5895 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
11-24 15:41:39.992  4073  5895 I SystemUpdateService: file has been verified
11-24 15:41:39.992  4073  5895 I SystemUpdateService: OTA package size = 21989297
,11-24 15:41:39.995  5519  5565 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
,11-24 15:41:39.995  5519  5565 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-57,5,main], id: 57
11-24 15:41:39.995  5519  5565 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
11-24 15:41:39.995  5519  5565 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-57,5,main], id: 57
11-24 15:41:39.995  5519  5565 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,11-24 15:41:39.995  5823  5842 D BtGatt.ScanManager: handling starting scan
11-24 15:41:39.996  5519  5519 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-24 15:41:39.996  5519  5519 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-24 15:41:39.996  5519  5519 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
11-24 15:41:39.996  5519  5519 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
,11-24 15:41:39.996  5519  5519 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-24 15:41:39.996  5519  5519 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
11-24 15:41:39.997  5519  5565 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-24 15:41:39.997  5519  5565 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
11-24 15:41:39.997  5519  5519 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-24 15:41:39.997  5519  5519 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING] Current thread: Thread[main,5,main], id: 1
11-24 15:41:39.998  5823  5842 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@cf72321
11-24 15:41:39.998  5519  5565 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
11-24 15:41:39.998  5519  5565 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
11-24 15:41:39.999  5519  5565 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
,11-24 15:41:39.999  5519  5565 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
11-24 15:41:39.999  5519  5565 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
11-24 15:41:39.999  5519  5565 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
11-24 15:41:39.999  5519  5519 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-24 15:41:39.999  5519  5565 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,11-24 15:41:39.999  5519  5565 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-24 15:41:39.999  5519  5565 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-24 15:41:39.999  5519  5565 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 15:41:39.999  5519  5565 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
11-24 15:41:40.001  5519  5519 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-24 15:41:40.001  5519  5519 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-24 15:41:40.001  5519  5519 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-24 15:41:40.001  5519  5565 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-24 15:41:40.001  5519  5519 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
11-24 15:41:40.001  5519  5565 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-57,5,main], id: 57
,11-24 15:41:40.001  5519  5565 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
11-24 15:41:40.001  5519  5565 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-24 15:41:40.001  5519  5565 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-57,5,main], id: 57
11-24 15:41:40.001  5519  5565 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-57,5,main], id: 57
11-24 15:41:40.001  5519  5565 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-57,5,main], id: 57
11-24 15:41:40.001  5519  5565 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
11-24 15:41:40.001  5519  5565 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-57,5,main], id: 57
11-24 15:41:40.003  5519  5565 D BluetoothAdapter: STATE_ON
11-24 15:41:40.004  5823  5864 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
11-24 15:41:40.004  5519  5565 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-24 15:41:40.004  5519  5565 D BluetoothAdapter: STATE_ON
11-24 15:41:40.005  5823  5834 D BtGatt.GattService: stopScan() - queue size =1
11-24 15:41:40.005  5823  5863 D BtGatt.GattService: unregisterClient() - clientIf=5
11-24 15:41:40.005  5823  5839 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
11-24 15:41:40.005  5823  5839 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-24 15:41:40.005  5519  5565 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-24 15:41:40.005  5519  5565 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-57,5,main], id: 57
11-24 15:41:40.005  5519  5565 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
11-24 15:41:40.005  5519  5565 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-57,5,main], id: 57
11-24 15:41:40.005  5519  5565 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-57,5,main], id: 57
11-24 15:41:40.005  5519  5565 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-57,5,main], id: 57
11-24 15:41:40.005  5823  5842 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
11-24 15:41:40.006  5519  5565 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-57,5,main], id: 57
11-24 15:41:40.006  5519  5565 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,11-24 15:41:40.006  5519  5565 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-57,5,main], id: 57
11-24 15:41:40.006  5519  5565 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-57,5,main], id: 57
11-24 15:41:40.006  5519  5565 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-57,5,main], id: 57
11-24 15:41:40.006  5519  5565 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-24 15:41:40.006  5519  5565 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-24 15:41:40.006  5519  5565 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
,11-24 15:41:40.008  5519  5565 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
,11-24 15:41:40.009  5519  5565 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
11-24 15:41:40.009  5519  5565 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-24 15:41:40.009  5519  5565 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
,11-24 15:41:40.009  5519  5565 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
11-24 15:41:40.009  4073  5895 I SystemUpdateService: showing system update notification
11-24 15:41:40.009  5519  5519 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-24 15:41:40.009  5823  5839 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
11-24 15:41:40.009  5519  5519 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-24 15:41:40.009  5823  5839 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 15:41:40.009  5519  5519 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
,11-24 15:41:40.009  5519  5519 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-24 15:41:40.009  5519  5519 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-24 15:41:40.009  5519  5519 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
11-24 15:41:40.009  5519  5519 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-24 15:41:40.010  5519  5519 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-24 15:41:40.010  5519  5519 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-24 15:41:40.010  5519  5519 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-24 15:41:40.010  5519  5519 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED] Current thread: Thread[main,5,main], id: 1
11-24 15:41:40.010  5823  5842 D BtGatt.ScanManager: Starting BLE batch scan
11-24 15:41:40.010  5519  5519 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-24 15:41:40.010  5823  5842 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
11-24 15:41:40.010  5519  5565 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-24 15:41:40.010  5519  5565 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-24 15:41:40.010  5519  5565 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-24 15:41:40.010  5519  5565 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-24 15:41:40.010  5519  5565 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 15:41:40.010  5519  5565 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-24 15:41:40.010  5519  5565 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1394115 removed from the list
11-24 15:41:40.011  5519  5565 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 15:41:40.011  5519  5565 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2734c2a removed from the list
11-24 15:41:40.011  5519  5565 D io.jxcore.node.ConnectivityMonitor: stop
11-24 15:41:40.011  5519  5565 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-57,5,main], id: 57
11-24 15:41:40.011  5519  5565 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
11-24 15:41:40.011  5519  5519 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-24 15:41:40.011  5519  5519 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-24 15:41:40.012  5519  5519 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-24 15:41:40.012  5519  5565 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,mai,n], id: 57
11-24 15:41:40.012  5519  5565 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
11-24 15:41:40.012  5519  5565 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
11-24 15:41:40.012  5519  5565 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-24 15:41:40.012  5519  5565 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-24 15:41:40.012  5519  5565 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 15:41:40.012  5519  5565 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2734c2a not in the list
11-24 15:41:40.012  5519  5565 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-57,5,main], id: 57
11-24 15:41:40.012  5519  5565 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
11-24 15:41:40.013  5519  5565 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
11-24 15:41:40.013  5519  5565 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
11-24 15:41:40.013  5519  5565 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
11-24 15:41:40.013  5519  5565 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-24 15:41:40.013  5519  5565 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-24 15:41:40.013  5519  5565 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 15:41:40.013  5519  5565 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@78b97b8 removed from the list
11-24 15:41:40.013  5519  5565 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-24 15:41:40.013  5519  5565 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 15:41:40.013  5519  5565 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-24 15:41:40.013  5519  5565 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ec86a1b removed from the list
11-24 15:41:40.013   926  5880 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Thu, 24 Nov 2016 14:41:39 GMT], X-Android-Received-Millis=[1479998500013], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1479998499989]}
11-24 15:41:40.014  5519  5565 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-24 15:41:40.014  5519  5565 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f517dcd added. We now have 3 listener(s)
11-24 15:41:40.014   926  2975 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
11-24 15:41:40.014   926  2975 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] validation  passed
11-24 15:41:40.014   926  2975 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
11-24 15:41:40.015  5519  5565 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-24 15:41:40.015  5519  5565 D org,.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-24 15:41:40.015  5519  5565 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-24 15:41:40.015  5519  5565 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-24 15:41:40.015  5519  5565 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3953682 added. We now have 4 listener(s)
11-24 15:41:40.015  5519  5565 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-24 15:41:40.015   926  2975 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
11-24 15:41:40.015  5519  5565 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
11-24 15:41:40.018  5519  5565 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-24 15:41:40.018  5519  5565 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7b00193 added. We now have 4 listener(s)
11-24 15:41:40.018  5823  5839 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
11-24 15:41:40.018  5823  5839 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 15:41:40.019  5519  5565 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-24 15:41:40.019  5519  5565 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-24 15:41:40.019  5519  5565 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-24 15:41:40.019  5519  5565 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-24 15:41:40.019  5519  5565 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@11da5d0 added. We now have 5 listener(s)
11-24 15:41:40.019  5519  5565 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-24 15:41:40.019  5519  5565 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-24 15:41:40.020   926   926 V NotificationService: pkg=com.google.android.gms canInterrupt=false intercept=true
11-24 15:41:40.020  5519  5565 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-24 15:41:40.020  5519  5565 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
11-24 15:41:40.020  5519  5565 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
11-24 15:41:40.020  5519  5565 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-24 15:41:40.020  5519  5565 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
11-24 15:41:40.021  5519  5565 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
11-24 15:41:40.021  4073  4073 D SystemUpdateService: onDestroy
11-24 15:41:40.024  5823  5839 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
11-24 15:41:40.024  5823  5839 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 15:41:40.024  5519  5565 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-24 15:41:40.024  5519  5565 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-24 15:41:40.024  5519  5565 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
11-24 15:41:40.025  5823  5842 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
11-24 15:41:40.027  5519  5565 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-57,5,main], id: 57
11-24 15:41:40.027  5519  5565 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-24 15:41:40.027  5519  5565 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-24 15:41:40.027  5519  5565 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-24 15:41:40.027  5519  5565 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 0
11-24 15:41:40.029  5823  5839 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-24 15:41:40.030  5823  5839 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 15:41:40.030  5823  5839 E BtGatt.ContextMap: Context not found for ID 5
11-24 15:41:40.030  5519  5565 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-57,5,main], id: 57
11-24 15:41:40.030  5519  5565 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
11-24 15:41:40.030  5519  5565 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
11-24 15:41:40.030  5519  5565 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
11-24 15:41:40.030  5519  5565 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
11-24 15:41:40.030  5519  5565 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-57,5,main], id: 57
11-24 15:41:40.030  5519  5565 D BluetoothAdapter: STATE_ON
11-24 15:41:40.032  5823  5834 D BtGatt.GattService: registerClient() - UUID=65e681a0-4f88-4f43-bf0b-d4ca466038ce
11-24 15:41:40.033  5823  5839 D BtGatt.GattService: onClientRegistered() - UUID=65e681a0-4f88-4f43-bf0b-d4ca466038ce, clientIf=5
11-24 15:41:40.033  5519  5530 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
11-24 15:41:40.033  5823  5833 D BtGatt.GattService: start scan with filters
11-24 15:41:40.036  5823  5839 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
11-24 15:41:40.036  5823  5839 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 15:41:40.036  5823  5842 D BtGatt.ScanManager: stopping BLe Batch
11-24 15:41:40.037  5519  5565 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
11-24 15:41:40.037  5519  5565 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-57,5,main], id: 57
11-24 15:41:40.037  5519  5565 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
11-24 15:41:40.037  5519  5565 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-57,5,main], id: 57
11-24 15:41:40.037  5519  5565 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-24 15:41:40.038  5519  5519 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-24 15:41:40.038  5519  5519 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-24 15:41:40.038  5519  5519 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
11-24 15:41:40.038  5519  5519 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-24 15:41:40.038  5519  5519 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-24 15:41:40.038  5519  5519 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
11-24 15:41:40.038  5519  5519 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-24 15:41:40.038  5519  5519 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING] Current thread: Thread[main,5,main], id: 1
11-24 15:41:40.038  5519  5565 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-24 15:41:40.038  5519  5565 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
11-24 15:41:40.040  5519  5565 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
11-24 15:41:40.040  5519  5565 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
11-24 15:41:40.040  5519  5565 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
11-24 15:41:40.040  5519  5565 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
11-24 15:41:40.040  5519  5565 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
11-24 15:41:40.040  5519  5519 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-24 15:41:40.040  5519  5565 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
11-24 15:41:40.040  5519  5565 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-24 15:41:40.040  5519  5565 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-24 15:41:40.040  5519  5565 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-24 15:41:40.040  5519  5565 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-24 15:41:40.040  5519  5565 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-24 15:41:40.040  5519  5565 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-24 15:41:40.040  5519  5565 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 15:41:40.040  5519  5565 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-24 15:41:40.040  5519  5565 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f517dcd removed from the list
11-24 15:41:40.040  5519  5565 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 15:41:40.041  5519  5565 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3953682 removed from the list
11-24 15:41:40.041  5519  5565 D io.jxcore.node.ConnectivityMonitor: stop
11-24 15:41:40.041  5519  5565 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-24 15:41:40.041  5519  5565 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-24 15:41:40.041  5519  5565 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-57,5,main], id: 57
11-24 15:41:40.041  5519  5565 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
11-24 15:41:40.041  5519  5565 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
,11-24 15:41:40.041  5519  5565 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-24 15:41:40.041  5519  5565 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-24 15:41:40.042  5519  5565 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
11-24 15:41:40.042  5823  5839 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
11-24 15:41:40.042  5823  5839 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 15:41:40.042  5823  5842 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
11-24 15:41:40.042  5519  5519 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-24 15:41:40.042  5519  5565 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
11-24 15:41:40.042  5519  5519 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-24 15:41:40.042  5519  5565 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
11-24 15:41:40.042  5519  5519 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-24 15:41:40.042  5519  5565 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
11-24 15:41:40.042  5519  5565 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-24 15:41:40.042  5519  5519 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
11-24 15:41:40.042  5519  5565 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-24 15:41:40.042  5519  5565 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 15:41:40.042  5519  5565 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3953682 not in the list
11-24 15:41:40.043  5519  5565 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-24 15:41:40.043  5519  5565 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-57,5,main], id: 57
11-24 15:41:40.043  5519  5565 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
11-24 15:41:40.043  5519  5565 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-24 15:41:40.043  5519  5565 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-57,5,main], id: 57
11-24 15:41:40.043  5519  5565 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-57,5,main], id: 57
11-24 15:41:40.043  5519  5565 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-57,5,main], id: 57
11-24 15:41:40.043  5519  5565 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
11-24 15:41:40.043  5519  5565 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-57,5,main], id: 57
11-24 15:41:40.043  5519  5565 D BluetoothAdapter: STATE_ON
11-24 15:41:40.043  5823  5833 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
11-24 15:41:40.044  5519  5565 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-24 15:41:40.044  5519  5565 D BluetoothAdapter: STATE_ON
11-24 15:41:40.044  5823  5864 D BtGatt.GattService: stopScan() - queue size =0
11-24 15:41:40.045  5823  5851 D BtGatt.GattService: unregisterClient() - clientIf=5
11-24 15:41:40.045  5519  5565 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-24 15:41:40.045  5519  5565 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-57,5,main], id: 57
11-24 15:41:40.045  5519  5565 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
11-24 15:41:40.045  5519  5565 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-57,5,main], id: 57
11-24 15:41:40.045  5519  5565 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-57,5,main], id: 57
11-24 15:41:40.045  5519  5565 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-57,5,main], id: 57
11-24 15:41:40.045  5519  5565 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-57,5,main], id: 57
11-24 15:41:40.045  5519  5565 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-24 15:41:40.045  5519  5565 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-57,5,main], id: 57
11-24 15:41:40.045  5519  5565 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-57,5,main], id: 57
11-24 15:41:40.045  5519  5565 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-57,5,main], id: 57
11-24 15:41:40.045  5519  5565 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-24 15:41:40.045  5519  5565 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-24 15:41:40.046  5519  5565 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
11-24 15:41:40.046  5519  5565 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
11-24 15:41:40.047  5519  5565 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
11-24 15:41:40.047  5519  5565 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-24 15:41:40.047  5519  5565 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
11-24 15:41:40.047  5519  5565 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
11-24 15:41:40.047  5519  5565 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-24 15:41:40.047  5519  5565 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-24 15:41:40.047  5519  5565 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 15:41:40.047  5519  5565 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@11da5d0 removed from the list
11-24 15:41:40.047  5519  5519 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-24 15:41:40.047  5519  5565 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-24 15:41:40.047  5519  5519 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-24 15:41:40.047  5519  5565 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 15:41:40.047  5519  5565 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-24 15:41:40.047  5519  5519 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-24 15:41:40.047  5519  5565 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7b00193 removed from the list
11-24 15:41:40.047  5519  5519 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-24 15:41:40.047  5823  5839 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-24 15:41:40.047  5823  5839 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 15:41:40.047  5519  5519 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-24 15:41:40.047  5519  5519 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
11-24 15:41:40.048  5519  5519 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-24 15:41:40.048  5519  5565 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-24 15:41:40.048  5519  5565 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2d9985 added. We now have 3 listener(s)
11-24 15:41:40.048  5519  5519 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-24 15:41:40.048  5519  5519 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-24 15:41:40.048  5519  5519 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-24 15:41:40.048  5519  5519 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED] Current thread: Thread[main,5,main], id: 1
11-24 15:41:40.048  5519  5519 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-24 15:41:40.049  5519  5565 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-24 15:41:40.049  5519  5565 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-24 15:41:40.049  5519  5565 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-24 15:41:40.049  5823  5842 D BtGatt.ScanManager: handling starting scan
11-24 15:41:40.049  5519  5565 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-24 15:41:40.049  5519  5565 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a0f13da added. We now have 4 listener(s)
11-24 15:41:40.049  5519  5565 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-24 15:41:40.049  5519  5519 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-24 15:41:40.049  5519  5519 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-24 15:41:40.049  5519  5519 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-24 15:41:40.049  5519  5565 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
11-24 15:41:40.050  5519  5565 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-24 15:41:40.050  5519  5565 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@514100b added. We now have 4 listener(s)
11-24 15:41:40.051  5519  5565 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-24 15:41:40.051  5519  5565 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-24 15:41:40.051  5519  5565 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-24 15:41:40.051  5519  5565 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-24 15:41:40.051  5519  5565 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9f05ee8 added. We now have 5 listener(s)
11-24 15:41:40.051  5519  5565 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-24 15:41:40.051  5519  5565 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-24 15:41:40.051  5519  5565 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
11-24 15:41:40.051  5519  5565 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
11-24 15:41:40.052  5519  5565 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-24 15:41:40.052  5519  5565 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
11-24 15:41:40.052  5519  5565 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
11-24 15:41:40.054  5519  5565 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-24 15:41:40.054  5519  5565 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-24 15:41:40.054  5519  5565 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
11-24 15:41:40.055  5823  5839 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
11-24 15:41:40.055  5823  5839 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 15:41:40.056  5823  5842 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
11-24 15:41:40.058  5519  5565 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-57,5,main], id: 57
11-24 15:41:40.058  5519  5565 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-24 15:41:40.058  5519  5565 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-24 15:41:40.059  5519  5565 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-24 15:41:40.059  5519  5565 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 0
11-24 15:41:40.059  5823  5839 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
11-24 15:41:40.059  5823  5839 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 15:41:40.059  5823  5842 D BtGatt.ScanManager: Starting BLE batch scan
11-24 15:41:40.059  5823  5842 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
11-24 15:41:40.061  5519  5565 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-57,5,main], id: 57
11-24 15:41:40.061  5519  5565 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
11-24 15:41:40.061  5519  5565 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
11-24 15:41:40.061  5519  5565 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
11-24 15:41:40.061  5519  5565 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
11-24 15:41:40.061  5519  5565 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-57,5,main], id: 57
11-24 15:41:40.062  5519  5565 D BluetoothAdapter: STATE_ON
11-24 15:41:40.063  5823  5851 D BtGatt.GattService: registerClient() - UUID=94545dbb-32dd-448f-8a79-014bc463e3ef
11-24 15:41:40.063  5823  5839 D BtGatt.GattService: onClientRegistered() - UUID=94545dbb-32dd-448f-8a79-014bc463e3ef, clientIf=5
11-24 15:41:40.063  5519  5530 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
11-24 15:41:40.064  5823  5833 D BtGatt.GattService: start scan with filters
11-24 15:41:40.065  5823  5839 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
11-24 15:41:40.066  5823  5839 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 15:41:40.066  5519  5565 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
11-24 15:41:40.066  5519  5565 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-57,5,main], id: 57
11-24 15:41:40.066  5519  5565 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
11-24 15:41:40.066  5519  5565 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-57,5,main], id: 57
11-24 15:41:40.066  5519  5565 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-24 15:41:40.066  5519  5519 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-24 15:41:40.066  5519  5519 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-24 15:41:40.066  5519  5519 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
11-24 15:41:40.066  5519  5519 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-24 15:41:40.066  5519  5519 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-24 15:41:40.066  5519  5519 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
11-24 15:41:40.067  5519  5519 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-24 15:41:40.067  5519  5565 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-24 15:41:40.067  5519  5565 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
11-24 15:41:40.067  5519  5519 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING] Current thread: Thread[main,5,main], id: 1
11-24 15:41:40.068  5519  5565 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
11-24 15:41:40.068  5519  5565 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
11-24 15:41:40.068  5519  5565 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
11-24 15:41:40.068  5519  5565 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
11-24 15:41:40.068  5519  5519 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-24 15:41:40.070  5519  5565 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-24 15:41:40.070  5519  5565 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-24 15:41:40.070  5519  5565 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-24 15:41:40.070  5519  5565 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-24 15:41:40.070  5519  5565 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-24 15:41:40.070  5519  5565 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-24 15:41:40.070  5519  5565 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 15:41:40.070  5519  5565 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-24 15:41:40.070  5519  5565 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2d9985 removed from the list
11-24 15:41:40.070  5519  5565 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 15:41:40.070  5519  5565 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a0f13da removed from the list
11-24 15:41:40.070  5519  5565 D io.jxcore.node.ConnectivityMonitor: stop
11-24 15:41:40.070  5519  5565 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-24 15:41:40.070  5519  5565 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-24 15:41:40.070  5519  5565 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-57,5,main], id: 57
11-24 15:41:40.070  5519  5565 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
11-24 15:41:40.071  5519  5565 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
11-24 15:41:40.071  5519  5565 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-24 15:41:40.071  5519  5565 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-24 15:41:40.071  5519  5565 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
11-24 15:41:40.071  5823  5839 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
11-24 15:41:40.071  5823  5839 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 15:41:40.072  5823  5842 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
11-24 15:41:40.072  5519  5519 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-24 15:41:40.072  5519  5519 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-24 15:41:40.072  5519  5519 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-24 15:41:40.072  5519  5519 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
11-24 15:41:40.072  5519  5565 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
11-24 15:41:40.072  5519  5565 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
11-24 15:41:40.072  5519  5565 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
11-24 15:41:40.072  5519  5565 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-24 15:41:40.072  5519  5565 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-24 15:41:40.072  5519  5565 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 15:41:40.072  5519  5565 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a0f13da not in the list
11-24 15:41:40.072  5519  5565 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-24 15:41:40.072  5519  5565 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-57,5,main], id: 57
11-24 15:41:40.072  5519  5565 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
11-24 15:41:40.072  5519  5565 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-24 15:41:40.073  5519  5565 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-57,5,main], id: 57
11-24 15:41:40.073  5519  5565 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-57,5,main], id: 57
11-24 15:41:40.073  5519  5565 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-57,5,main], id: 57
11-24 15:41:40.073  5519  5565 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
11-24 15:41:40.073  5519  5565 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-57,5,main], id: 57
11-24 15:41:40.073  5519  5565 D BluetoothAdapter: STATE_ON
11-24 15:41:40.073  5823  5863 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
11-24 15:41:40.074  5519  5565 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-24 15:41:40.074  5519  5565 D BluetoothAdapter: STATE_ON
11-24 15:41:40.074  5823  5833 D BtGatt.GattService: stopScan() - queue size =1
11-24 15:41:40.075  5823  5834 D BtGatt.GattService: unregisterClient() - clientIf=5
11-24 15:41:40.075  5519  5565 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-24 15:41:40.075  5519  5565 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-57,5,main], id: 57
11-24 15:41:40.075  5519  5565 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
11-24 15:41:40.075  5519  5565 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-57,5,main], id: 57
11-24 15:41:40.075  5519  5565 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-57,5,main], id: 57
11-24 15:41:40.075  5519  5565 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-57,5,main], id: 57
11-24 15:41:40.075  5519  5565 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-57,5,main], id: 57
11-24 15:41:40.076  5519  5565 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-24 15:41:40.076  5519  5565 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-57,5,main], id: 57
11-24 15:41:40.076  5519  5565 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-57,5,main], id: 57
11-24 15:41:40.076  5519  5565 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-57,5,main], id: 57
11-24 15:41:40.076  5519  5565 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-24 15:41:40.076  5519  5565 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-24 15:41:40.076  5823  5839 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-24 15:41:40.076  5519  5565 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
11-24 15:41:40.076  5823  5839 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 15:41:40.076  5823  5839 E BtGatt.ContextMap: Context not found for ID 5
11-24 15:41:40.077  5519  5565 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
11-24 15:41:40.078  5519  5565 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
11-24 15:41:40.078  5519  5565 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-24 15:41:40.078  5519  5565 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
11-24 15:41:40.078  5519  5565 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
11-24 15:41:40.078  5519  5565 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-24 15:41:40.078  5519  5565 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-24 15:41:40.078  5519  5565 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 15:41:40.078  5519  5565 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9f05ee8 removed from the list
11-24 15:41:40.078  5519  5519 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-24 15:41:40.078  5519  5565 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-24 15:41:40.078  5519  5565 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 15:41:40.078  5519  5519 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-24 15:41:40.078  5519  5565 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-24 15:41:40.078  5519  5565 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@514100b removed from the list
11-24 15:41:40.078  5519  5519 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-24 15:41:40.078  5519  5519 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-24 15:41:40.079  5519  5519 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-24 15:41:40.079  5519  5519 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
11-24 15:41:40.079  5519  5519 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-24 15:41:40.079  5519  5519 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-24 15:41:40.079  5519  5519 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-24 15:41:40.079  5519  5565 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-24 15:41:40.079  5519  5519 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-24 15:41:40.079  5519  5565 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e8a743d added. We now have 3 listener(s)
11-24 15:41:40.079  5519  5519 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED] Current thread: Thread[main,5,main], id: 1
11-24 15:41:40.079  5519  5519 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-24 15:41:40.080  5519  5565 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-24 15:41:40.080  5519  5565 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-24 15:41:40.080  5519  5565 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-24 15:41:40.080  5519  5565 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-24 15:41:40.080  5519  5565 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@48c4432 added. We now have 4 listener(s)
11-24 15:41:40.080  5519  5565 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-24 15:41:40.080  5519  5519 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-24 15:41:40.080  5519  5519 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-24 15:41:40.080  5519  5565 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
11-24 15:41:40.080  5519  5519 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-24 15:41:40.081  5519  5565 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-24 15:41:40.081  5519  5565 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d2c7583 added. We now have 4 listener(s)
11-24 15:41:40.082  5823  5839 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
11-24 15:41:40.082  5823  5839 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 15:41:40.082  5519  5565 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-24 15:41:40.082  5519  5565 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-24 15:41:40.082  5823  5842 D BtGatt.ScanManager: stopping BLe Batch
11-24 15:41:40.082  5519  5565 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-24 15:41:40.082  5519  5565 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-24 15:41:40.082  5519  5565 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e0e2300 added. We now have 5 listener(s)
11-24 15:41:40.082  5519  5565 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-24 15:41:40.082  5519  5565 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-24 15:41:40.082  5519  5565 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-24 15:41:40.082  5519  5565 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-24 15:41:40.082  5519  5565 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-24 15:41:40.082  5519  5565 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 15:41:40.082  5519  5565 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-24 15:41:40.082  5519  5565 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e8a743d removed from the list
11-24 15:41:40.082  5519  5565 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 15:41:40.083  5519  5565 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@48c4432 removed from the list
11-24 15:41:40.083  5519  5565 D io.jxcore.node.ConnectivityMonitor: stop
11-24 15:41:40.083  5519  5565 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-57,5,main], id: 57
11-24 15:41:40.083  5519  5565 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
11-24 15:41:40.083  5519  5565 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
11-24 15:41:40.083  5519  5565 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
11-24 15:41:40.083  5519  5565 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
11-24 15:41:40.084  5519  5565 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-24 15:41:40.084  5519  5565 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-24 15:41:40.084  5519  5565 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 15:41:40.084  5519  5565 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@48c4432 not in the list
11-24 15:41:40.084  5519  5565 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-57,5,main], id: 57
11-24 15:41:40.084  5519  5565 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
11-24 15:41:40.084  5519  5565 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
11-24 15:41:40.084  5519  5565 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
11-24 15:41:40.085  5519  5565 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
11-24 15:41:40.085  5519  5565 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-24 15:41:40.085  5519  5565 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-24 15:41:40.085  5519  5565 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 15:41:40.085  5519  5565 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e0e2300 removed from the list
11-24 15:41:40.085  5519  5565 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-24 15:41:40.085  5519  5565 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 15:41:40.085  5519  5565 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-24 15:41:40.085  5519  5565 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d2c7583 removed from the list
11-24 15:41:40.085  5519  5565 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
11-24 15:41:40.085  5519  5565 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
11-24 15:41:40.085  5519  5565 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
11-24 15:41:40.085  5519  5565 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-24 15:41:40.086  5519  5565 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
11-24 15:41:40.086  5519  5565 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
11-24 15:41:40.087  5823  5839 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,11-24 15:41:40.087  5823  5839 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 15:41:40.087  5823  5842 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
11-24 15:41:40.091  5823  5839 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-24 15:41:40.091  5823  5839 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 15:41:40.095  5823  5842 D BtGatt.ScanManager: handling starting scan
11-24 15:41:40.096  4817  5900 I Babel   : connection state changed from DISCONNECTED to CONNECTED
11-24 15:41:40.100  5823  5839 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
11-24 15:41:40.100  5823  5839 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 15:41:40.100  5823  5842 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
11-24 15:41:40.104  5823  5839 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
11-24 15:41:40.104  5823  5839 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 15:41:40.104  5823  5842 D BtGatt.ScanManager: Starting BLE batch scan
11-24 15:41:40.104  5823  5842 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
11-24 15:41:40.112  5823  5839 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
11-24 15:41:40.112  5823  5839 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 15:41:40.117  5823  5839 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
11-24 15:41:40.117  5823  5839 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 15:41:40.118  5823  5842 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
11-24 15:41:40.124  5823  5839 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-24 15:41:40.124  5823  5839 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 15:41:40.124  5823  5839 E BtGatt.ContextMap: Context not found for ID 5
,11-24 15:41:40.131  5823  5839 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
,11-24 15:41:40.131  5823  5839 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 15:41:40.131  5823  5842 D BtGatt.ScanManager: stopping BLe Batch
,11-24 15:41:40.136  5823  5839 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,11-24 15:41:40.136  5823  5839 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 15:41:40.136  5823  5842 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-24 15:41:40.141  5823  5839 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,11-24 15:41:40.141  5823  5839 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-24 15:41:40.510  5519  5519 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-24 15:41:40.549  5519  5519 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-24 15:41:40.579  5519  5519 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-24 15:41:42.178  5519  5908 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 173, name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
11-24 15:41:42.178  5519  5908 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-24 15:41:42.632   926  2975 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-24 15:41:43.012  5519  5908 W !!      : call onHalfStreamCopied
,11-24 15:41:43.012  5519  5908 I testCopyDataAndClose: closing input stream
,11-24 15:41:43.791  5519  5908 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 173, thread name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
11-24 15:41:43.791  5519  5908 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
11-24 15:41:43.791  5519  5908 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
11-24 15:41:43.791  5519  5908 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-24 15:41:43.792  5519  5908 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
,11-24 15:41:43.792  5519  5908 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
11-24 15:41:43.792  5519  5908 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
,11-24 15:41:43.792  5519  5908 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
11-24 15:41:43.792  5519  5908 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
11-24 15:41:43.792  5519  5908 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 173, name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
11-24 15:41:43.792  5519  5908 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 20971520 and the total number of bytes written 20971520
,11-24 15:41:43.819   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 15:41:44.820   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 15:41:45.821   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 15:41:46.822   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 15:41:47.823   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 15:41:47.843   926  2975 D ConnectivityService: handlePromptUnvalidated 102
,11-24 15:41:48.171  5519  5909 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 176, name: My test thread name). Connection data: Peer properties: [null null].
11-24 15:41:48.171  5519  5909 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-24 15:41:48.824   535   535 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,11-24 15:41:50.171  5519  5565 I io.jxcore.node.StreamCopyingThread: close: Thread ID: 176. Connection data: Peer properties: [null null].
11-24 15:41:50.171  5519  5565 I io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-24 15:41:50.171  5519  5565 D io.jxcore.node.StreamCopyingThread: closeStreams: Streams closed (thread ID: 176, name: My test thread name)
,11-24 15:41:50.193  5519  5909 D io.jxcore.node.StreamCopyingThread: number of bytes read = 0
,11-24 15:41:50.193  5519  5909 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 176, name: My test thread name). Connection data: Peer properties: [null null].
11-24 15:41:50.193  5519  5909 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 165 and the total number of bytes written 165
,11-24 15:41:50.312  5519  5910 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 178, name: testCopyBigData thread). Connection data: Peer properties: [null null].
11-24 15:41:50.312  5519  5910 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-24 15:41:50.961   926  2973 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 10, 11 -> obsolete
,11-24 15:41:51.921  5519  5910 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 178, thread name: testCopyBigData thread). Connection data: Peer properties: [null null].
11-24 15:41:51.921  5519  5910 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-24 15:41:51.921  5519  5910 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
11-24 15:41:51.921  5519  5910 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-24 15:41:51.921  5519  5910 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
11-24 15:41:51.921  5519  5910 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
11-24 15:41:51.921  5519  5910 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
11-24 15:41:51.921  5519  5910 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
11-24 15:41:51.921  5519  5910 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
11-24 15:41:51.921  5519  5910 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 178, name: testCopyBigData thread). Connection data: Peer properties: [null null].
11-24 15:41:51.921  5519  5910 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 20971520 and the total number of bytes written 20971520
,11-24 15:41:54.722   926  2975 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-24 15:41:56.040  5519  5911 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 180, name: My test thread name). Connection data: Peer properties: [null null].
11-24 15:41:56.040  5519  5911 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-24 15:41:56.040  5519  5911 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 180, thread name: My test thread name). Connection data: Peer properties: [null null].
11-24 15:41:56.040  5519  5911 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
11-24 15:41:56.040  5519  5911 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
11-24 15:41:56.040  5519  5911 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
11-24 15:41:56.040  5519  5911 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
11-24 15:41:56.040  5519  5911 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
,11-24 15:41:56.041  5519  5911 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
11-24 15:41:56.041  5519  5911 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
11-24 15:41:56.041  5519  5911 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
,11-24 15:41:56.041  5519  5911 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 180, name: My test thread name). Connection data: Peer properties: [null null].
11-24 15:41:56.041  5519  5911 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 22
,11-24 15:41:56.043  5519  5565 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,11-24 15:41:56.047  5519  5912 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 184, name: My test thread name). Connection data: Peer properties: [null null].
11-24 15:41:56.047  5519  5912 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-24 15:41:56.048  5519  5912 E io.jxcore.node.StreamCopyingThread: Failed to write to the output stream (thread ID: 184, thread name: My test thread name): Test exception.
,11-24 15:41:56.049  5519  5912 D io.jxcore.node.StreamCopyingThread: onStreamCopyError (ID: 184, name: My test thread name). Connection data: Peer properties: [null null].
11-24 15:41:56.049  5519  5912 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
11-24 15:41:56.049  5519  5912 D io.jxcore.node.StreamCopyingThread: number of bytes read = 22
11-24 15:41:56.050  5519  5912 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 184, name: My test thread name). Connection data: Peer properties: [null null].
11-24 15:41:56.050  5519  5912 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
,11-24 15:41:56.055  5519  5565 I jxcore-log: 2016-11-24 14:41:56 - DEBUG UnitTest_app: 'Total number of executed tests:  82'
11-24 15:41:56.055  5519  5565 I jxcore-log: 
11-24 15:41:56.056  5519  5565 I jxcore-log: 2016-11-24 14:41:56 - DEBUG UnitTest_app: 'Number of passed tests:  82'
11-24 15:41:56.056  5519  5565 I jxcore-log: 
11-24 15:41:56.056  5519  5565 I jxcore-log: 2016-11-24 14:41:56 - DEBUG UnitTest_app: 'Number of failed tests:  0'
11-24 15:41:56.056  5519  5565 I jxcore-log: 
11-24 15:41:56.056  5519  5565 I jxcore-log: 2016-11-24 14:41:56 - DEBUG UnitTest_app: 'Number of ignored tests:  0'
11-24 15:41:56.056  5519  5565 I jxcore-log: 
,11-24 15:41:56.056  5519  5565 I jxcore-log: 2016-11-24 14:41:56 - DEBUG UnitTest_app: 'Total duration:  91653'
11-24 15:41:56.056  5519  5565 I jxcore-log: 
,11-24 15:41:56.059  5519  5565 I jxcore-log: 2016-11-24 14:41:56 - DEBUG UnitTest_app: 'Unit Test app is loaded'
11-24 15:41:56.059  5519  5565 I jxcore-log: 
,11-24 15:41:56.063  5519  5565 I jxcore-log: 2016-11-24 14:41:56 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
11-24 15:41:56.063  5519  5565 I jxcore-log: 
,11-24 15:41:56.064  5519  5565 I jxcore-log: 2016-11-24 14:41:56 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
11-24 15:41:56.064  5519  5565 I jxcore-log: 
11-24 15:41:56.065  5519  5565 I jxcore-log: 2016-11-24 14:41:56 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
11-24 15:41:56.065  5519  5565 I jxcore-log: 
11-24 15:41:56.065  5519  5565 I jxcore-log: 2016-11-24 14:41:56 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH"})'
11-24 15:41:56.065  5519  5565 I jxcore-log: 
,11-24 15:41:56.065  5519  5565 I jxcore-log: 2016-11-24 14:41:56 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-24 15:41:56.065  5519  5565 I jxcore-log: 
11-24 15:41:56.066  5519  5565 I jxcore-log: 2016-11-24 14:41:56 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-24 15:41:56.066  5519  5565 I jxcore-log: 
11-24 15:41:56.066  5519  5565 I jxcore-log: 2016-11-24 14:41:56 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-24 15:41:56.066  5519  5565 I jxcore-log: 
11-24 15:41:56.066  5519  5565 I jxcore-log: 2016-11-24 14:41:56 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
11-24 15:41:56.066  5519  5565 I jxcore-log: 
11-24 15:41:56.066  5519  5565 I jxcore-log: 2016-11-24 14:41:56 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
11-24 15:41:56.066  5519  5565 I jxcore-log: 
,11-24 15:41:56.067  5519  5565 I jxcore-log: 2016-11-24 14:41:56 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
11-24 15:41:56.067  5519  5565 I jxcore-log: 
11-24 15:41:56.067  5519  5565 I jxcore-log: 2016-11-24 14:41:56 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH"})'
11-24 15:41:56.067  5519  5565 I jxcore-log: 
11-24 15:41:56.067  5519  5565 I jxcore-log: 2016-11-24 14:41:56 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-24 15:41:56.067  5519  5565 I jxcore-log: 
11-24 15:41:56.067  5519  5565 I jxcore-log: 2016-11-24 14:41:56 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-24 15:41:56.067  5519  5565 I jxcore-log: 
11-24 15:41:56.068  5519  5565 I jxcore-log: 2016-11-24 14:41:56 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-24 15:41:56.068  5519  5565 I jxcore-log: 
,11-24 15:41:56.068  5519  5565 I jxcore-log: 2016-11-24 14:41:56 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-24 15:41:56.068  5519  5565 I jxcore-log: 
11-24 15:41:56.068  5519  5565 I jxcore-log: 2016-11-24 14:41:56 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-24 15:41:56.068  5519  5565 I jxcore-log: 
11-24 15:41:56.068  5519  5565 I jxcore-log: 2016-11-24 14:41:56 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
11-24 15:41:56.068  5519  5565 I jxcore-log: 
11-24 15:41:56.068  5519  5565 I jxcore-log: 2016-11-24 14:41:56 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
11-24 15:41:56.068  5519  5565 I jxcore-log: 
,11-24 15:41:56.069  5519  5565 I jxcore-log: 2016-11-24 14:41:56 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
11-24 15:41:56.069  5519  5565 I jxcore-log: 
11-24 15:41:56.069  5519  5565 I jxcore-log: 2016-11-24 14:41:56 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
11-24 15:41:56.069  5519  5565 I jxcore-log: 
11-24 15:41:56.069  5519  5565 I jxcore-log: 2016-11-24 14:41:56 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
11-24 15:41:56.069  5519  5565 I jxcore-log: 
11-24 15:41:56.070  5519  5565 I jxcore-log: 2016-11-24 14:41:56 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
11-24 15:41:56.070  5519  5565 I jxcore-log: 
11-24 15:41:56.070  5519  5565 I jxcore-log: 2016-11-24 14:41:56 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
11-24 15:41:56.070  5519  5565 I jxcore-log: 
11-24 15:41:56.070  5519  5565 I jxcore-log: 2016-11-24 14:41:56 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
11-24 15:41:56.070  5519  5565 I jxcore-log: 
,11-24 15:41:56.072  5519  5565 I jxcore-log: 2016-11-24 14:41:56 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
11-24 15:41:56.072  5519  5565 I jxcore-log: 
11-24 15:41:56.072  5519  5565 I jxcore-log: 2016-11-24 14:41:56 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
11-24 15:41:56.072  5519  5565 I jxcore-log: 
11-24 15:41:56.072  5519  5565 I jxcore-log: 2016-11-24 14:41:56 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
11-24 15:41:56.072  5519  5565 I jxcore-log: 
,11-24 15:41:56.072  5519  5565 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-24 15:41:56.072  5519  5565 D io.jxcore.node.StartStopOperationHandler: Operation timeout, state error: null
11-24 15:41:56.073  5519  5565 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-24 15:41:56.073  5519  5565 D io.jxcore.node.StartStopOperationHandler: Operation timeout, state error: Discovery manager not started
11-24 15:41:56.073  5519  5565 I jxcore-log: 2016-11-24 14:41:56 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-24 15:41:56.073  5519  5565 I jxcore-log: 
11-24 15:41:56.073  5519  5565 I jxcore-log: 2016-11-24 14:41:56 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-24 15:41:56.073  5519  5565 I jxcore-log: 
11-24 15:41:56.073  5519  5565 I jxcore-log: 2016-11-24 14:41:56 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-24 15:41:56.073  5519  5565 I jxcore-log: 
11-24 15:41:56.073  5519  5565 I jxcore-log: 2016-11-24 14:41:56 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-24 15:41:56.073  5519  5565 I jxcore-log: 
,11-24 15:41:56.074  5519  5565 I jxcore-log: 2016-11-24 14:41:56 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-24 15:41:56.074  5519  5565 I jxcore-log: 
11-24 15:41:56.074  5519  5565 I jxcore-log: 2016-11-24 14:41:56 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-24 15:41:56.074  5519  5565 I jxcore-log: 
,11-24 15:41:56.078  5519  5519 D SystemWebChromeClient: file:///android_asset/www/js/thali_main.js: Line 68 : UIApp is all set and ready!
,11-24 15:41:56.079  5519  5519 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
11-24 15:41:56.079  5519  5565 I jxcore-log: 2016-11-24 14:41:56 - DEBUG UnitTest_app: 'My device name is: Huawei-Nexus 6P'
11-24 15:41:56.079  5519  5565 I jxcore-log: 
11-24 15:41:56.079  5519  5565 I jxcore-log: 2016-11-24 14:41:56 - WARN testUtils: 'myNameCallback not set!'
11-24 15:41:56.079  5519  5565 I jxcore-log: 
,11-24 15:41:57.750   926  2975 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-24 15:41:58.145  5519  5565 I jxcore-log: 2016-11-24 14:41:58 - INFO runTests: 'Starting tests. Network type: WIFI. Platform: android'
11-24 15:41:58.145  5519  5565 I jxcore-log: 
,11-24 15:41:58.146  5519  5565 I jxcore-log: 2016-11-24 14:41:58 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js'
11-24 15:41:58.146  5519  5565 I jxcore-log: 
,11-24 15:41:58.502  5519  5565 I jxcore-log: 2016-11-24 14:41:58 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js'
11-24 15:41:58.502  5519  5565 I jxcore-log: 
,11-24 15:41:58.513  5519  5565 I jxcore-log: 2016-11-24 14:41:58 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManager.js'
11-24 15:41:58.513  5519  5565 I jxcore-log: 
,11-24 15:41:59.628  5519  5565 I jxcore-log: 2016-11-24 14:41:59 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js'
11-24 15:41:59.628  5519  5565 I jxcore-log: 
,11-24 15:41:59.823  5519  5565 I jxcore-log: 2016-11-24 14:41:59 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js'
11-24 15:41:59.823  5519  5565 I jxcore-log: 
,11-24 15:41:59.829  5519  5565 I jxcore-log: 2016-11-24 14:41:59 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testNativeMethod.js'
11-24 15:41:59.829  5519  5565 I jxcore-log: 
,11-24 15:41:59.834  5519  5565 I jxcore-log: 2016-11-24 14:41:59 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPouchDBCheckpointPlugin.js'
11-24 15:41:59.834  5519  5565 I jxcore-log: 
,11-24 15:42:00.307  5519  5565 I jxcore-log: 2016-11-24 14:42:00 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPouchDBGenerator.js'
11-24 15:42:00.307  5519  5565 I jxcore-log: 
,11-24 15:42:00.353  5519  5565 I jxcore-log: 2016-11-24 14:42:00 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js'
11-24 15:42:00.353  5519  5565 I jxcore-log: 
,11-24 15:42:00.366  5519  5565 I jxcore-log: 2016-11-24 14:42:00 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js'
11-24 15:42:00.366  5519  5565 I jxcore-log: 
,11-24 15:42:00.370  5519  5565 I jxcore-log: 2016-11-24 14:42:00 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliManager.js'
11-24 15:42:00.370  5519  5565 I jxcore-log: 
,11-24 15:42:00.641  5519  5565 I jxcore-log: 2016-11-24 14:42:00 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliManagerCoordinated.js'
11-24 15:42:00.641  5519  5565 I jxcore-log: 
,11-24 15:42:00.771  5519  5565 I jxcore-log: 2016-11-24 14:42:00 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js'
11-24 15:42:00.771  5519  5565 I jxcore-log: 
,11-24 15:42:01.143  5519  5565 I jxcore-log: 2016-11-24 14:42:01 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js'
11-24 15:42:01.143  5519  5565 I jxcore-log: 
,11-24 15:42:01.151  5519  5565 I jxcore-log: 2016-11-24 14:42:01 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeDiscoveryCoordinated.js'
11-24 15:42:01.151  5519  5565 I jxcore-log: 
,11-24 15:42:01.155  5519  5565 I jxcore-log: 2016-11-24 14:42:01 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js'
11-24 15:42:01.155  5519  5565 I jxcore-log: 
,11-24 15:42:01.160  5519  5565 I jxcore-log: 2016-11-24 14:42:01 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js'
11-24 15:42:01.160  5519  5565 I jxcore-log: 
,11-24 15:42:01.166  5519  5565 I jxcore-log: 2016-11-24 14:42:01 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js'
11-24 15:42:01.166  5519  5565 I jxcore-log: 
,11-24 15:42:01.194  5519  5565 I jxcore-log: 2016-11-24 14:42:01 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js'
11-24 15:42:01.194  5519  5565 I jxcore-log: 
,11-24 15:42:01.229  5519  5565 I jxcore-log: 2016-11-24 14:42:01 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js'
11-24 15:42:01.229  5519  5565 I jxcore-log: 
,11-24 15:42:01.236  5519  5565 I jxcore-log: 2016-11-24 14:42:01 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationLocal.js'
11-24 15:42:01.236  5519  5565 I jxcore-log: 
,11-24 15:42:01.243  5519  5565 I jxcore-log: 2016-11-24 14:42:01 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js'
11-24 15:42:01.243  5519  5565 I jxcore-log: 
,11-24 15:42:01.258  5519  5565 I jxcore-log: 2016-11-24 14:42:01 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js'
11-24 15:42:01.258  5519  5565 I jxcore-log: 
,11-24 15:42:01.274  5519  5565 I jxcore-log: 2016-11-24 14:42:01 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js'
11-24 15:42:01.274  5519  5565 I jxcore-log: 
,11-24 15:42:01.280  5519  5565 I jxcore-log: 2016-11-24 14:42:01 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolDefault.js'
11-24 15:42:01.280  5519  5565 I jxcore-log: 
,11-24 15:42:01.285  5519  5565 I jxcore-log: 2016-11-24 14:42:01 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js'
11-24 15:42:01.285  5519  5565 I jxcore-log: 
,11-24 15:42:01.298  5519  5565 I jxcore-log: 2016-11-24 14:42:01 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolOneAtATime.js'
11-24 15:42:01.298  5519  5565 I jxcore-log: 
,11-24 15:42:01.315  5519  5565 I jxcore-log: 2016-11-24 14:42:01 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js'
11-24 15:42:01.315  5519  5565 I jxcore-log: 
,11-24 15:42:01.330  5519  5565 I jxcore-log: 2016-11-24 14:42:01 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js'
11-24 15:42:01.330  5519  5565 I jxcore-log: 
,11-24 15:42:01.340  5519  5565 I jxcore-log: 2016-11-24 14:42:01 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerAction.js'
11-24 15:42:01.340  5519  5565 I jxcore-log: 
,11-24 15:42:01.352  5519  5565 I jxcore-log: 2016-11-24 14:42:01 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js'
11-24 15:42:01.352  5519  5565 I jxcore-log: 
,11-24 15:42:01.363  5519  5565 I jxcore-log: 2016-11-24 14:42:01 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js'
11-24 15:42:01.363  5519  5565 I jxcore-log: 
,11-24 15:42:01.376  5519  5565 I jxcore-log: 2016-11-24 14:42:01 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js'
11-24 15:42:01.376  5519  5565 I jxcore-log: 
,11-24 15:42:01.386  5519  5565 I jxcore-log: 2016-11-24 14:42:01 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js'
11-24 15:42:01.386  5519  5565 I jxcore-log: 
,11-24 15:42:01.392  5519  5565 I jxcore-log: 2016-11-24 14:42:01 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js'
11-24 15:42:01.392  5519  5565 I jxcore-log: 
,11-24 15:42:01.414  5519  5565 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: SUPPORTED
,11-24 15:42:01.415  5519  5565 I jxcore-log: 2016-11-24 14:42:01 - INFO testUtils: 'BLE multiple advertisement supported'
11-24 15:42:01.415  5519  5565 I jxcore-log: 
,11-24 15:42:01.445  5519  5565 I jxcore-log: 2016-11-24 14:42:01 - INFO CoordinatedClient: 'Connecting to coordination server on http://85.14.110.168:3000/'
11-24 15:42:01.445  5519  5565 I jxcore-log: 
,11-24 15:42:01.818  5519  5565 I jxcore-log: 2016-11-24 14:42:01 - DEBUG CoordinatedClient: 'connected to the test server'
11-24 15:42:01.818  5519  5565 I jxcore-log: 
,11-24 15:42:08.825   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 15:42:09.826   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 15:42:10.828   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 15:42:11.829   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 15:42:12.831   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 15:42:13.831   535   535 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,11-24 15:42:19.815   926  2973 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-24 15:42:38.832   535   535 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,11-24 15:42:38.833   535   535 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,11-24 15:42:48.834   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 15:42:49.835   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 15:42:50.837   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 15:42:51.838   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 15:42:52.839   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 15:42:53.840   535   535 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,11-24 15:42:58.842   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 15:42:59.820   926  2973 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-24 15:42:59.844   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 15:43:00.845   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 15:43:01.846   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 15:43:02.848   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 15:43:03.849   535   535 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,11-24 15:43:13.850   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 15:43:14.852   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 15:43:15.853   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 15:43:16.854   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 15:43:17.856   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 15:43:18.856   535   535 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,11-24 15:43:19.820   926  2973 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-24 15:43:33.858   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 15:43:34.859   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 15:43:35.860   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 15:43:36.861   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 15:43:37.862   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 15:43:38.863   535   535 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,11-24 15:43:40.204  4073  5921 I EventLogService: Aggregate from 1479996724951 (log), 1479996724951 (data)
,11-24 15:43:58.865   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 15:43:59.823   926  2973 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-24 15:43:59.867   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 15:44:00.868   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 15:44:01.870   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 15:44:02.871   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 15:44:03.872   535   535 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,11-24 15:44:19.827   926  2973 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-24 15:44:28.872   535   535 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,11-24 15:44:28.873   535   535 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,11-24 15:44:39.829   926  2973 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-24 15:44:43.874   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 15:44:44.875   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 15:44:45.876   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 15:44:46.877   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 15:44:47.878   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 15:44:48.879   535   535 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,11-24 15:44:53.880   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 15:44:54.882   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 15:44:55.883   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 15:44:56.223   926  2975 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-24 15:44:56.885   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 15:44:57.886   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 15:44:58.886   535   535 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,11-24 15:44:59.253   926  2975 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-24 15:45:08.888   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 15:45:09.889   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 15:45:10.890   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 15:45:11.891   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 15:45:12.893   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 15:45:13.893   535   535 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,11-24 15:45:19.834   926  2973 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-24 15:45:28.894   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 15:45:29.522   926  2975 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-24 15:45:29.896   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 15:45:30.897   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 15:45:31.899   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 15:45:32.554   926  2975 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-24 15:45:32.900   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 15:45:33.900   535   535 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,11-24 15:45:39.837   926  2973 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-24 15:45:53.902   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 15:45:54.903   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 15:45:55.905   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 15:45:56.906   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 15:45:57.908   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 15:45:58.908   535   535 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,11-24 15:45:59.836   926  2973 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-24 15:46:17.918   926  2975 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-24 15:46:19.838   926  2973 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-24 15:46:20.936   926  2975 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-24 15:46:23.909   535   535 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,11-24 15:46:23.909   535   535 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,11-24 15:46:39.839   926  2973 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-24 15:46:43.910   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 15:46:44.913   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 15:46:45.914   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 15:46:46.916   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 15:46:47.917   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 15:46:48.917   535   535 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,11-24 15:46:53.918   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 15:46:53.919  5519  5565 I jxcore-log: 2016-11-24 14:46:53 - DEBUG CoordinatedClient: 'device disconnected from the test server'
11-24 15:46:53.919  5519  5565 I jxcore-log: 
,11-24 15:46:54.134  5519  5565 I jxcore-log: 2016-11-24 14:46:54 - ERROR CoordinatedClient: 'connection error: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-24 15:46:54.134  5519  5565 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-24 15:46:54.134  5519  5565 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-24 15:46:54.134  5519  5565 I jxcore-log: emit@events.js:82:1
11-24 15:46:54.134  5519  5565 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-24 15:46:54.134  5519  5565 I jxcore-log: emit@events.js:82:1''
11-24 15:46:54.134  5519  5565 I jxcore-log: 
,11-24 15:46:54.136  5519  5565 I jxcore-log: 2016-11-24 14:46:54 - DEBUG CoordinatedClient: 'test client failed'
11-24 15:46:54.136  5519  5565 I jxcore-log: 
,11-24 15:46:54.148  5519  5565 I jxcore-log: 2016-11-24 14:46:54 - ERROR CoordinatedClient: 'connection error: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-24 15:46:54.148  5519  5565 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-24 15:46:54.148  5519  5565 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-24 15:46:54.148  5519  5565 I jxcore-log: emit@events.js:82:1
11-24 15:46:54.148  5519  5565 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-24 15:46:54.148  5519  5565 I jxcore-log: emit@events.js:82:1''
11-24 15:46:54.148  5519  5565 I jxcore-log: 
,11-24 15:46:54.149  5519  5565 I jxcore-log: 2016-11-24 14:46:54 - DEBUG CoordinatedClient: 'test client failed'
11-24 15:46:54.149  5519  5565 I jxcore-log: 
,11-24 15:46:54.155  5519  5565 I jxcore-log: 2016-11-24 14:46:54 - ERROR CoordinatedThaliTape: 'tests failed, error: 'Error: websocket error', stack: 'Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-24 15:46:54.155  5519  5565 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-24 15:46:54.155  5519  5565 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-24 15:46:54.155  5519  5565 I jxcore-log: emit@events.js:82:1
11-24 15:46:54.155  5519  5565 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-24 15:46:54.155  5519  5565 I jxcore-log: emit@events.js:82:1''
11-24 15:46:54.155  5519  5565 I jxcore-log: 
,11-24 15:46:54.156  5519  5565 I jxcore-log: 2016-11-24 14:46:54 - DEBUG CoordinatedThaliTape: '****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****'
11-24 15:46:54.156  5519  5565 I jxcore-log: 
,11-24 15:46:54.800  5933  5933 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,11-24 15:46:54.823  5933  5933 D AndroidRuntime: CheckJNI is OFF
,11-24 15:46:54.852  5933  5933 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,11-24 15:46:54.888  5933  5933 I Radio-JNI: register_android_hardware_Radio DONE
,11-24 15:46:54.906  5933  5933 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,11-24 15:46:54.916   926   939 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=-1: uninstall pkg
,11-24 15:46:54.917   926   939 I ActivityManager: Killing 5519:com.test.thalitest/u0a77 (adj 0): stop com.test.thalitest
11-24 15:46:54.920   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 15:46:55.019   926  2974 D WifiService: Client connection lost with reason: 4
,11-24 15:46:55.020   926  4813 I WindowState: WIN DEATH: Window{5f11411 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,11-24 15:46:55.019   926  3154 D GraphicsStats: Buffer count: 2
,11-24 15:46:55.040   926   939 W ActivityManager: Force removing ActivityRecord{96aef3e u0 com.test.thalitest/.MainActivity t70}: app died, no saved state
,11-24 15:46:55.075   926   949 I art     : Starting a blocking GC Explicit
,11-24 15:46:55.083   926   936 W ActivityManager: Spurious death for ProcessRecord{e85aacd 0:com.test.thalitest/u0a77}, curProc for 5519: null
,11-24 15:46:55.111   937   937 W Binder_2: type=1400 audit(0.0:121): avc: denied { ioctl } for path="socket:[27188]" dev="sockfs" ino=27188 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-24 15:46:55.111   937   937 W Binder_2: type=1400 audit(0.0:122): avc: denied { ioctl } for path="socket:[27188]" dev="sockfs" ino=27188 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-24 15:46:55.111   926   937 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 5519 uid 10077
11-24 15:46:55.112  3689  3689 I Keyboard.Facilitator: onFinishInput()
,11-24 15:46:55.176  3947  5947 I MicroRecognitionRnrImpl: Starting detection.
,11-24 15:46:55.177  3947  5948 I MicrophoneInputStream: mic_starting com.google.android.apps.gsa.speech.audio.x@b67a3bd
,11-24 15:46:55.180   512  5950 I AudioFlinger: AudioFlinger's thread 0xf1ec0000 ready to run
,11-24 15:46:55.187   512  3021 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
11-24 15:46:55.190  3947  5948 I MicrophoneInputStream: mic_started com.google.android.apps.gsa.speech.audio.x@b67a3bd
,11-24 15:46:55.195   926   949 I art     : Explicit concurrent mark sweep GC freed 131557(9MB) AllocSpace objects, 88(2MB) LOS objects, 33% free, 29MB/44MB, paused 1.995ms total 119.304ms
,11-24 15:46:55.199   512  5950 D audio_hw_primary: select_devices: out_snd_device(0: none) in_snd_device(63: voice-rec-mic)
,11-24 15:46:55.199   512  5950 D msm8974_platform: platform_send_audio_calibration: sending audio calibration for snd_device(63) acdb_id(62)
,11-24 15:46:55.200   512  5950 I ACDB-LOADER: ACDB AFE returned = -19
,11-24 15:46:55.200   512  5950 I soundtrigger: audio_extn_sound_trigger_update_device_status: device 0x3f of type 1 for Event 1
,11-24 15:46:55.200   512  5950 D sound_trigger_platform: platform_stdev_check_and_update_concurrency: concurrency active 0, tx 1, rx 0, concurrency session_allowed 0
,11-24 15:46:55.200   512  5950 D audio_hw_primary: enable_snd_device: snd_device(63: voice-rec-mic)
,11-24 15:46:55.208   512  5950 D audio_hw_primary: enable_audio_route: apply and update mixer path: audio-record
,11-24 15:46:55.219   926   949 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,11-24 15:46:55.222  5933  5933 I art     : System.exit called, status: 0
,11-24 15:46:55.222  5933  5933 I AndroidRuntime: VM exiting with result code 0.
,11-24 15:46:55.235   926   949 I ActivityManager: Start proc 5953:com.android.defcontainer/u0a7 for service com.android.defcontainer/.DefaultContainerService
11-24 15:46:55.235   926   949 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=0: pkg removed
,11-24 15:46:55.244  5823  5823 D BluetoothMapAppObserver: onReceive
,11-24 15:46:55.244  5823  5823 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
,11-24 15:46:55.246   926  2958 I InputReader: Reconfiguring input devices.  changes=0x00000010
,11-24 15:46:55.253  3934  4151 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,11-24 15:46:55.255  3689  3689 I Keyboard.Facilitator: resetDictionaries() : en_US
,11-24 15:46:55.262  3689  5964 I Keyboard.Facilitator.DecoderInitializer: run()
,11-24 15:46:55.273  3774  3774 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,11-24 15:46:55.274  3689  5964 I Decoder : createOrResetDecoder
11-24 15:46:55.274   926   939 I ActivityManager: Start proc 5966:android.process.acore/u0a2 for broadcast com.android.providers.contacts/.PackageIntentReceiver
,11-24 15:46:55.291  3947  3947 I HotwordWorkerImpl: onReady
,11-24 15:46:55.318    27    27 W kworker/1:1: type=1400 audit(0.0:123): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-24 15:46:55.321    27    27 W kworker/1:1: type=1400 audit(0.0:124): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-24 15:46:55.331    27    27 W kworker/1:1: type=1400 audit(0.0:125): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-24 15:46:55.331   926   926 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,11-24 15:46:55.341  3592  3592 I ConfigService: onCreate
,11-24 15:46:55.345  3592  5981 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/config.db'.
11-24 15:46:55.345  3592  5981 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
11-24 15:46:55.345  3592  5981 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
11-24 15:46:55.345  3592  5981 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
11-24 15:46:55.345  3592  5981 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
11-24 15:46:55.345  3592  5981 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
11-24 15:46:55.345  3592  5981 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
11-24 15:46:55.345  3592  5981 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
11-24 15:46:55.345  3592  5981 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
11-24 15:46:55.345  3592  5981 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
11-24 15:46:55.345  3592  5981 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
11-24 15:46:55.345  3592  5981 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
11-24 15:46:55.345  3592  5981 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
11-24 15:46:55.345  3592  5981 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
11-24 15:46:55.345  3592  5981 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
11-24 15:46:55.345  3592  5981 E SQLiteDatabase: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
11-24 15:46:55.345  3592  5981 E SQLiteDatabase: 	at com.google.android.gms.config.j.run(SourceFile:152)
11-24 15:46:55.345  3592  5981 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
11-24 15:46:55.346  3592  5981 E SQLiteOpenHelper: Couldn't open config.db for writing (will try read-only):
11-24 15:46:55.346  3592  5981 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
11-24 15:46:55.346  3592  5981 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
11-24 15:46:55.346  3592  5981 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
11-24 15:46:55.346  3592  5981 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
11-24 15:46:55.346  3592  5981 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
11-24 15:46:55.346  3592  5981 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
11-24 15:46:55.346  3592  5981 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
11-24 15:46:55.346  3592  5981 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
11-24 15:46:55.346  3592  5981 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
11-24 15:46:55.346  3592  5981 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
11-24 15:46:55.346  3592  5981 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
11-24 15:46:55.346  3592  5981 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
11-24 15:46:55.346  3592  5981 E SQLiteOpenHelper:, 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
11-24 15:46:55.346  3592  5981 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
11-24 15:46:55.346  3592  5981 E SQLiteOpenHelper: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
11-24 15:46:55.346  3592  5981 E SQLiteOpenHelper: 	at com.google.android.gms.config.j.run(SourceFile:152)
11-24 15:46:55.346  3592  5981 E SQLiteOpenHelper: 	at java.lang.Thread.run(Thread.java:818)
11-24 15:46:55.348  3592  5981 W SQLiteOpenHelper: Opened config.db in read-only mode
11-24 15:46:55.350  3798  3924 E SQLiteLog: (3850) statement aborts at 23: [DELETE FROM icons WHERE componentName LIKE ? AND profileId = ?] disk I/O error
11-24 15:46:55.351   926   938 W AtomicFile: Couldn't rename file /data/system/users/0/runtime-permissions.xml to backup file /data/system/users/0/runtime-permissions.xml.bak
11-24 15:46:55.351   926   938 E PackageManager: Failed to write settings, restoring backup
11-24 15:46:55.351   926   938 E PackageManager: java.io.IOException: Couldn't create directory /data/system/users/0/runtime-permissions.xml
11-24 15:46:55.351   926   938 E PackageManager: 	at android.util.AtomicFile.startWrite(AtomicFile.java:106)
11-24 15:46:55.351   926   938 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.writePermissionsSync(Settings.java:4615)
11-24 15:46:55.351   926   938 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.-wrap1(Settings.java)
11-24 15:46:55.351   926   938 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence$MyHandler.handleMessage(Settings.java:4830)
11-24 15:46:55.351   926   938 E PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-24 15:46:55.351   926   938 E PackageManager: 	at android.os.Looper.loop(Looper.java:148)
11-24 15:46:55.351   926   938 E PackageManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,11-24 15:46:55.356   926   939 E DropBoxManagerService: Can't write: system_server_wtf
11-24 15:46:55.356   926   939 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop15.tmp: open failed: EROFS (Read-only file system)
11-24 15:46:55.356   926   939 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
11-24 15:46:55.356   926   939 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
11-24 15:46:55.356   926   939 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
11-24 15:46:55.356   926   939 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
11-24 15:46:55.356   926   939 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
11-24 15:46:55.356   926   939 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
11-24 15:46:55.356   926   939 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12561)
11-24 15:46:55.356   926   939 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.handleApplicationWtfInner(ActivityManagerService.java:12374)
11-24 15:46:55.356   926   939 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:12346)
11-24 15:46:55.356   926   939 E DropBoxManagerService: 	at android.os.Handler.handleCallback(Handler.java:739)
11-24 15:46:55.356   926   939 E DropBoxManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:95)
11-24 15:46:55.356   926   939 E DropBoxManagerService: 	at android.os.Looper.loop(Looper.java:148)
11-24 15:46:55.356   926   939 E DropBoxManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
11-24 15:46:55.356   926   939 E DropBoxManagerService: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
11-24 15:46:55.356   926   939 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
11-24 15:46:55.356   926   939 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
11-24 15:46:55.356   926   939 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
11-24 15:46:55.356   926   939 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
11-24 15:46:55.356   926   939 E DropBoxManagerService: 	... 13 more
,11-24 15:46:55.360  3689  5964 I Keyboard.Facilitator.MainLanguageModelLoader: run()
,11-24 15:46:55.365   926  3791 I ActivityManager: Start proc 5982:com.google.android.googlequicksearchbox:crash_report/u0a29 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
,--------- beginning of crash
11-24 15:46:55.366  3798  3924 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
11-24 15:46:55.366  3798  3924 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 3798
11-24 15:46:55.366  3798  3924 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
11-24 15:46:55.366  3798  3924 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
11-24 15:46:55.366  3798  3924 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
11-24 15:46:55.366  3798  3924 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
11-24 15:46:55.366  3798  3924 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
11-24 15:46:55.366  3798  3924 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
11-24 15:46:55.366  3798  3924 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
11-24 15:46:55.366  3798  3924 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
11-24 15:46:55.366  3798  3924 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
11-24 15:46:55.366  3798  3924 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
11-24 15:46:55.366  3798  3924 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
11-24 15:46:55.366  3798  3924 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,11-24 15:46:55.369   926  5989 E DropBoxManagerService: Can't write: system_app_crash
11-24 15:46:55.369   926  5989 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop127.tmp: open failed: EROFS (Read-only file system)
11-24 15:46:55.369   926  5989 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
11-24 15:46:55.369   926  5989 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
11-24 15:46:55.369   926  5989 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
11-24 15:46:55.369   926  5989 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
11-24 15:46:55.369   926  5989 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
11-24 15:46:55.369   926  5989 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
11-24 15:46:55.369   926  5989 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
11-24 15:46:55.369   926  5989 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
11-24 15:46:55.369   926  5989 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
11-24 15:46:55.369   926  5989 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
11-24 15:46:55.369   926  5989 E DropBoxManagerService: 	... 5 more
,11-24 15:46:55.369   926  3155 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,11-24 15:46:55.373  3947  3962 W SearchService: Abort, client detached.
,11-24 15:46:55.375  3947  3947 I HotwordDetector: Closing mic
,11-24 15:46:55.379  3947  4217 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@b67a3bd
,11-24 15:46:55.379  3947  5948 E AudioRecord-JNI: Error -4 during AudioRecord native read
11-24 15:46:55.382  5966  5966 W System  : ClassLoader referenced unknown path: /system/priv-app/ContactsProvider/lib/arm64
,11-24 15:46:55.446   512  5950 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
,11-24 15:46:55.447   512  5950 D audio_hw_primary: disable_snd_device: snd_device(63: voice-rec-mic)
,11-24 15:46:55.451   512  5950 I soundtrigger: audio_extn_sound_trigger_update_device_status: device 0x3f of type 1 for Event 0
11-24 15:46:55.451   512  5950 D sound_trigger_platform: platform_stdev_check_and_update_concurrency: concurrency active 0, tx 0, rx 0, concurrency session_allowed 1
11-24 15:46:55.452   512  3021 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
,11-24 15:46:55.454  3947  5947 I MicroRecognitionRnrImpl: Detection finished
,11-24 15:46:55.455  3947  4218 I MicroRecognitionRnrImpl: Stopping hotword detection.
,11-24 15:46:55.523  5966  5966 W System  : ClassLoader referenced unknown path: /system/app/UserDictionaryProvider/lib/arm64
,11-24 15:46:55.542  5966  6001 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,11-24 15:46:55.754   382   481 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0

```
