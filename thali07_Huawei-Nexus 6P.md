#### Test 950476158569fbe_thali07_Huawei-Nexus 6P Logs


```
--------- beginning of system
11-23 19:14:27.200   929  2972 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,--------- beginning of main
11-23 19:14:27.650  5579  5579 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
11-23 19:14:27.655  5579  5579 D AndroidRuntime: CheckJNI is OFF
11-23 19:14:27.679  5579  5579 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
11-23 19:14:27.710  5579  5579 I Radio-JNI: register_android_hardware_Radio DONE
11-23 19:14:27.725  5579  5579 D AndroidRuntime: Calling main entry com.android.commands.am.Am
11-23 19:14:27.728   929  3833 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
11-23 19:14:27.747  5579  5579 D AndroidRuntime: Shutting down VM
11-23 19:14:27.758  3954  5561 W SearchService: Abort, client detached.
11-23 19:14:27.763  3954  4194 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@f1490d0
11-23 19:14:27.763  3954  3954 I HotwordDetector: Closing mic
11-23 19:14:27.764  3954  4212 E AudioRecord-JNI: Error -4 during AudioRecord native read
11-23 19:14:27.783   929  3158 I ActivityManager: Start proc 5588:com.test.thalitest/u0a77 for activity com.test.thalitest/.MainActivity
11-23 19:14:27.834   513  4214 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
11-23 19:14:27.834   513  4214 D audio_hw_primary: disable_snd_device: snd_device(63: voice-rec-mic)
11-23 19:14:27.838   513  4214 I soundtrigger: audio_extn_sound_trigger_update_device_status: device 0x3f of type 1 for Event 0
11-23 19:14:27.838   513  4214 D sound_trigger_platform: platform_stdev_check_and_update_concurrency: concurrency active 0, tx 0, rx 0, concurrency session_allowed 1
11-23 19:14:27.840   513  3006 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
11-23 19:14:27.841  3954  4210 I MicroRecognitionRnrImpl: Detection finished
11-23 19:14:27.841  3954  4199 I MicroRecognitionRnrImpl: Stopping hotword detection.
11-23 19:14:27.861  5588  5588 I CordovaLog: Changing log level to DEBUG(3)
11-23 19:14:27.862  5588  5588 I CordovaActivity: Apache Cordova native platform version 6.0.0 is starting
11-23 19:14:27.862  5588  5588 D CordovaActivity: CordovaActivity.onCreate()
11-23 19:14:27.866  5588  5588 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011750)
11-23 19:14:27.884  5588  5588 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
11-23 19:14:27.955  5588  5588 I LibraryLoader: Time to load native libraries: 68 ms (timestamps 5391-5459)
11-23 19:14:27.955  5588  5588 I LibraryLoader: Expected native library version number "",actual native library version number ""
,11-23 19:14:27.995  5588  5588 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {433d4ff}
,11-23 19:14:27.995  5588  5588 I LibraryLoader: Expected native library version number "",actual native library version number ""
11-23 19:14:27.995  5588  5588 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,11-23 19:14:27.998  5588  5588 I BrowserStartupController: Initializing chromium process, singleProcess=true
,11-23 19:14:27.999  5588  5588 E SysUtils: ApplicationContext is null in ApplicationStatus
,11-23 19:14:28.036  5588  5588 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,11-23 19:14:28.044  5588  5588 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
11-23 19:14:28.044  5588  5588 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,11-23 19:14:28.044  5588  5588 I Adreno  : QUALCOMM build                   : 63c06b2, I8366cd0437
11-23 19:14:28.044  5588  5588 I Adreno  : Build Date                       : 12/06/15
11-23 19:14:28.044  5588  5588 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
11-23 19:14:28.044  5588  5588 I Adreno  : Local Branch                     : mybranch17112971
11-23 19:14:28.044  5588  5588 I Adreno  : Remote Branch                    : quic/LA.BF64.1.2.9_v2
11-23 19:14:28.044  5588  5588 I Adreno  : Remote Branch                    : NONE
11-23 19:14:28.044  5588  5588 I Adreno  : Reconstruct Branch               : NOTHING
,11-23 19:14:28.083   929   946 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@a282a3f:true
,11-23 19:14:28.117   736   736 W Binder_3: type=1400 audit(0.0:99): avc: denied { ioctl } for path="socket:[13795]" dev="sockfs" ino=13795 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-23 19:14:28.117   736   736 W Binder_3: type=1400 audit(0.0:100): avc: denied { ioctl } for path="socket:[13795]" dev="sockfs" ino=13795 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-23 19:14:28.128  5588  5588 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,11-23 19:14:28.136  5588  5588 D SystemWebViewEngine: CordovaWebView is running on device made by: Huawei
,11-23 19:14:28.140  5588  5588 D PluginManager: init()
,11-23 19:14:28.142  5588  5588 D CordovaWebViewImpl: >>> loadUrl(file:///android_asset/www/index.html)
,11-23 19:14:28.159  5588  5588 D CordovaActivity: Started the activity.
,11-23 19:14:28.159  5588  5588 D CordovaActivity: Resumed the activity.
,11-23 19:14:28.160   737   737 W Binder_4: type=1400 audit(0.0:101): avc: denied { ioctl } for path="socket:[31524]" dev="sockfs" ino=31524 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-23 19:14:28.160   737   737 W Binder_4: type=1400 audit(0.0:102): avc: denied { ioctl } for path="socket:[31524]" dev="sockfs" ino=31524 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
11-23 19:14:28.165  5588  5625 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,11-23 19:14:28.167  3158  3158 W Binder_4: type=1400 audit(0.0:103): avc: denied { ioctl } for path="socket:[22442]" dev="sockfs" ino=22442 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-23 19:14:28.167  3158  3158 W Binder_4: type=1400 audit(0.0:104): avc: denied { ioctl } for path="socket:[22442]" dev="sockfs" ino=22442 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-23 19:14:28.171  5588  5612 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,11-23 19:14:28.198  5588  5625 I OpenGLRenderer: Initialized EGL, version 1.4
,11-23 19:14:28.270  3150  3150 W Binder_3: type=1400 audit(0.0:105): avc: denied { ioctl } for path="socket:[31528]" dev="sockfs" ino=31528 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-23 19:14:28.270  3150  3150 W Binder_3: type=1400 audit(0.0:106): avc: denied { ioctl } for path="socket:[31528]" dev="sockfs" ino=31528 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-23 19:14:28.274   929   947 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +512ms
,11-23 19:14:28.273  3158  3158 W Binder_4: type=1400 audit(0.0:107): avc: denied { ioctl } for path="socket:[31527]" dev="sockfs" ino=31527 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-23 19:14:28.278  3666  3666 I Keyboard.Facilitator: onFinishInput()
,11-23 19:14:28.273  3158  3158 W Binder_4: type=1400 audit(0.0:108): avc: denied { ioctl } for path="socket:[31527]" dev="sockfs" ino=31527 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-23 19:14:28.286  5588  5588 D CordovaWebViewImpl: onPageDidNavigate(file:///android_asset/www/index.html)
,11-23 19:14:28.301  5588  5588 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 5588
,11-23 19:14:28.392  5588  5588 D JsMessageQueue: Set native->JS mode to EvalBridgeMode
,11-23 19:14:28.556  5588  5628 D jxcore_app_log: JniHelper::setJavaVM(0xf52bc000), pthread_self() = -582743760
,11-23 19:14:28.560  5588  5628 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
11-23 19:14:28.560  5588  5628 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
11-23 19:14:28.560  5588  5628 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
11-23 19:14:28.560  5588  5628 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
11-23 19:14:28.560  5588  5628 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
11-23 19:14:28.561  5588  5628 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9a1ed42 added. We now have 1 listener(s)
,11-23 19:14:28.563  5588  5628 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 60:83:34:25:D7:D4
,11-23 19:14:28.563  5588  5628 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-23 19:14:28.564  5588  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-23 19:14:28.564  5588  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,11-23 19:14:28.566  5588  5628 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
11-23 19:14:28.566  5588  5628 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
11-23 19:14:28.566  5588  5628 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
11-23 19:14:28.566  5588  5628 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 60:83:34:25:D7:D4
11-23 19:14:28.566  5588  5628 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
11-23 19:14:28.566  5588  5628 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
11-23 19:14:28.566  5588  5628 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
11-23 19:14:28.566  5588  5628 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
11-23 19:14:28.566  5588  5628 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
11-23 19:14:28.566  5588  5628 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
11-23 19:14:28.566  5588  5628 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
11-23 19:14:28.566  5588  5628 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
11-23 19:14:28.566  5588  5628 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
11-23 19:14:28.566  5588  5628 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,11-23 19:14:28.566  5588  5628 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9f75f89 added. We now have 1 listener(s)
11-23 19:14:28.566  5588  5628 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-23 19:14:28.570   929  2971 D WifiService: New client listening to asynchronous messages
11-23 19:14:28.570  5588  5628 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
11-23 19:14:28.571  5588  5628 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
11-23 19:14:28.571  5588  5628 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[JavaBridge,5,main], id: 55
11-23 19:14:28.571  5588  5628 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
11-23 19:14:28.571  5588  5628 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
,11-23 19:14:28.571  5588  5628 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
11-23 19:14:28.571  5588  5628 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[JavaBridge,5,main], id: 55
,11-23 19:14:28.572  5588  5628 I io.jxcore.node.LifeCycleMonitor: start: OK
11-23 19:14:28.591   929   939 I ActivityManager: Killing 5257:com.android.settings/1000 (adj 15): empty #17
,11-23 19:14:28.623   929   939 I ActivityManager: Killing 5216:org.codeaurora.ims/1001 (adj 15): empty #18
,11-23 19:14:28.667  5588  5588 D CordovaWebViewImpl: onPageFinished(file:///android_asset/www/index.html)
,11-23 19:14:28.669  5588  5588 D SystemWebChromeClient: file:///android_asset/www/js/index.js: Line 36 : Uncaught TypeError: Cannot read property 'querySelector' of null
,11-23 19:14:28.669  5588  5588 I chromium: [INFO:CONSOLE(36)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (36)
,11-23 19:14:28.843  5588  5597 I art     : Background sticky concurrent mark sweep GC freed 84648(8MB) AllocSpace objects, 16(1076KB) LOS objects, 19% free, 26MB/32MB, paused 1.831ms total 110.761ms
,11-23 19:14:29.160  5588  5634 W jxcore-log: Initializing JXcore engine
,11-23 19:14:29.160  5588  5634 W jxcore-log: JXcore engine is ready
,11-23 19:14:29.180  5634  5634 W Thread-61: type=1400 audit(0.0:109): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=12077 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,11-23 19:14:29.180  5634  5634 W Thread-61: type=1400 audit(0.0:110): avc: denied { ioctl } for path="socket:[12468]" dev="sockfs" ino=12468 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
11-23 19:14:29.180  5634  5634 W Thread-61: type=1400 audit(0.0:111): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=5964 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
11-23 19:14:29.183  5634  5634 W Thread-61: type=1400 audit(0.0:112): avc: denied { ioctl } for path="socket:[32985]" dev="sockfs" ino=32985 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:untrusted_app:s0:c512,c768 tclass=netlink_route_socket permissive=0
,11-23 19:14:29.192  5588  5634 W jxcore-log: Starting JXcore engine
,11-23 19:14:29.242  5588  5634 W jxcore-log: Platform android
11-23 19:14:29.242  5588  5634 W jxcore-log: 
,11-23 19:14:29.242  5588  5634 W jxcore-log: Process ARCH arm
11-23 19:14:29.242  5588  5634 W jxcore-log: 
,11-23 19:14:29.427  5588  5634 I jxcore-log: JXcore Cordova bridge is ready!
11-23 19:14:29.427  5588  5634 I jxcore-log: 
,11-23 19:14:29.428  5588  5634 W jxcore-log: JXcore engine is started
,11-23 19:14:29.441  5588  5628 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,11-23 19:14:29.448  5588  5588 D SystemWebChromeClient: file:///android_asset/www/js/thali_main.js: Line 41 : Application has the required permission.
,11-23 19:14:29.448  5588  5588 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,11-23 19:14:37.925   929  2971 D WifiService: New client listening to asynchronous messages
,11-23 19:14:37.928  3954  5636 W CronetSyncConnectionRcs: Upload content type not set.
,11-23 19:14:39.170  5588  5634 I jxcore-log: 2016-11-23 18:14:39 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
11-23 19:14:39.170  5588  5634 I jxcore-log: 
,11-23 19:14:39.171  5588  5634 I jxcore-log: 2016-11-23 18:14:39 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
11-23 19:14:39.171  5588  5634 I jxcore-log: 
,11-23 19:14:39.177  5588  5634 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
11-23 19:14:39.177  5588  5634 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-23 19:14:39.177  5588  5634 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-23 19:14:39.177  5588  5634 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-23 19:14:39.177  5588  5634 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-23 19:14:39.177  5588  5634 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-23 19:14:39.177  5588  5634 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-23 19:14:39.177  5588  5634 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-23 19:14:39.177  5588  5634 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-23 19:14:39.177  5588  5634 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,11-23 19:14:39.178  5588  5634 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
,11-23 19:14:39.181  5588  5634 I jxcore-log: 2016-11-23 18:14:39 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
11-23 19:14:39.181  5588  5634 I jxcore-log: 
11-23 19:14:39.182  5588  5634 I jxcore-log: 2016-11-23 18:14:39 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
11-23 19:14:39.182  5588  5634 I jxcore-log: 
,11-23 19:14:39.429  5588  5634 I jxcore-log: 2016-11-23 18:14:39 - DEBUG UnitTest_app: 'Running unit tests'
11-23 19:14:39.429  5588  5634 I jxcore-log: 
,11-23 19:14:39.430  5588  5634 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,11-23 19:14:39.430  5588  5634 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@362f35 added. We now have 2 listener(s)
,11-23 19:14:39.433  5588  5634 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
,11-23 19:14:39.433  5588  5634 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,11-23 19:14:39.433  5588  5634 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,11-23 19:14:39.433  5588  5634 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,11-23 19:14:39.433  5588  5634 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1726fca added. We now have 2 listener(s)
,11-23 19:14:39.433  5588  5634 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-23 19:14:39.434  5588  5634 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
11-23 19:14:39.435  5588  5634 D executeNativeTests: Running unit tests
,11-23 19:14:39.478  5588  5634 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,11-23 19:14:39.478  5588  5634 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b72032b added. We now have 3 listener(s)
11-23 19:14:39.479  5588  5634 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-23 19:14:39.479  5588  5634 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-23 19:14:39.479  5588  5634 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,11-23 19:14:39.479  5588  5634 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-23 19:14:39.479  5588  5634 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ac4a388 added. We now have 3 listener(s)
11-23 19:14:39.479  5588  5634 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-23 19:14:39.479  5588  5634 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
11-23 19:14:39.481  5588  5634 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
11-23 19:14:39.481  5588  5634 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,11-23 19:14:39.481  5588  5634 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-23 19:14:39.481  5588  5634 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-23 19:14:39.482  5588  5634 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
11-23 19:14:39.482  5588  5634 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
11-23 19:14:39.482  5588  5634 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
11-23 19:14:39.482  5588  5634 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-23 19:14:39.482  5588  5634 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-23 19:14:39.482  5588  5634 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-23 19:14:39.483  5588  5634 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-23 19:14:39.483  5588  5634 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-23 19:14:39.483  5588  5634 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-23 19:14:39.483  5588  5634 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,11-23 19:14:39.483  5588  5634 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-23 19:14:39.483  5588  5634 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-23 19:14:39.483  5588  5634 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b72032b removed from the list
11-23 19:14:39.484  5588  5634 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 19:14:39.484  5588  5634 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ac4a388 removed from the list
,11-23 19:14:39.484  5588  5634 D io.jxcore.node.ConnectivityMonitor: stop
11-23 19:14:39.484  5588  5634 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-23 19:14:39.484  5588  5634 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-23 19:14:39.484  5588  5634 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-23 19:14:39.484  5588  5634 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 19:14:39.484  5588  5634 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 19:14:39.485  5588  5634 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,11-23 19:14:39.485  5588  5634 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-23 19:14:39.485  5588  5634 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 19:14:39.485  5588  5634 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ac4a388 not in the list
11-23 19:14:39.486  5588  5634 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
11-23 19:14:39.486  5588  5634 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-23 19:14:39.486  5588  5634 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-23 19:14:39.486  5588  5634 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,11-23 19:14:39.487  5588  5634 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-23 19:14:39.487  5588  5634 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-23 19:14:39.487  5588  5634 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b72032b not in the list
11-23 19:14:39.487  5588  5634 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-23 19:14:39.487  5588  5634 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ac4a388 not in the list
11-23 19:14:39.487  5588  5634 D io.jxcore.node.ConnectivityMonitor: stop
,11-23 19:14:39.487  5588  5634 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-23 19:14:39.487  5588  5634 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-23 19:14:39.487  5588  5634 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
,11-23 19:14:39.487  5588  5634 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 19:14:39.488  5588  5634 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 19:14:39.488  5588  5634 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,11-23 19:14:39.488  5588  5634 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-23 19:14:39.488  5588  5634 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 19:14:39.488  5588  5634 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ac4a388 not in the list
11-23 19:14:39.490  5588  5634 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
11-23 19:14:39.490  5588  5634 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
11-23 19:14:39.490  5588  5634 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
11-23 19:14:39.490  5588  5634 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
11-23 19:14:39.490  5588  5634 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
,11-23 19:14:39.490  5588  5634 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
11-23 19:14:39.490  5588  5634 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
11-23 19:14:39.490  5588  5634 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
11-23 19:14:39.490  5588  5634 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
,11-23 19:14:39.490  5588  5634 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
11-23 19:14:39.490  5588  5634 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
11-23 19:14:39.490  5588  5634 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
11-23 19:14:39.490  5588  5634 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
11-23 19:14:39.490  5588  5634 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
11-23 19:14:39.490  5588  5634 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
11-23 19:14:39.490  5588  5634 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
11-23 19:14:39.490  5588  5634 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
11-23 19:14:39.491  5588  5634 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
,11-23 19:14:39.491  5588  5634 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
11-23 19:14:39.491  5588  5634 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
11-23 19:14:39.491  5588  5634 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
11-23 19:14:39.491  5588  5634 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
,11-23 19:14:39.491  5588  5634 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
11-23 19:14:39.491  5588  5634 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
11-23 19:14:39.491  5588  5634 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
11-23 19:14:39.491  5588  5634 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
11-23 19:14:39.491  5588  5634 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
11-23 19:14:39.491  5588  5634 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
11-23 19:14:39.491  5588  5634 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
,11-23 19:14:39.491  5588  5634 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
11-23 19:14:39.491  5588  5634 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
11-23 19:14:39.491  5588  5634 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-23 19:14:39.491  5588  5634 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-23 19:14:39.491  5588  5634 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-23 19:14:39.491  5588  5634 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-23 19:14:39.491  5588  5634 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-23 19:14:39.491  5588  5634 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b72032b not in the list
11-23 19:14:39.491  5588  5634 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 19:14:39.491  5588  5634 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ac4a388 not in the list
11-23 19:14:39.491  5588  5634 D io.jxcore.node.ConnectivityMonitor: stop
11-23 19:14:39.491  5588  5634 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-23 19:14:39.491  5588  5634 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-23 19:14:39.492  5588  5634 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-23 19:14:39.492  5588  5634 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 19:14:39.492  5588  5634 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 19:14:39.492  5588  5634 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-23 19:14:39.492  5588  5634 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-23 19:14:39.492  5588  5634 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-23 19:14:39.492  5588  5634 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ac4a388 not in the list
11-23 19:14:39.492  5588  5634 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
11-23 19:14:39.494  5588  5634 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-23 19:14:39.494  5588  5634 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
11-23 19:14:39.508  5588  5634 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-23 19:14:39.508  5588  5634 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-23 19:14:39.508  5588  5634 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-23 19:14:39.508  5588  5634 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-23 19:14:39.508  5588  5634 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-23 19:14:39.508  5588  5634 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-23 19:14:39.508  5588  5634 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-23 19:14:39.508  5588  5634 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-23 19:14:39.508  5588  5634 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
11-23 19:14:39.509  5588  5634 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
11-23 19:14:39.509  5588  5634 D io.jxcore.node.ConnectivityMonitor: start: OK
11-23 19:14:39.509  5588  5634 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-23 19:14:39.509  5588  5634 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
11-23 19:14:39.509  5588  5634 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
11-23 19:14:39.509  5588  5634 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-23 19:14:39.509  5588  5634 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
11-23 19:14:39.511  5588  5634 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-23 19:14:39.511  5588  5634 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-23 19:14:39.511  5588  5634 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
11-23 19:14:39.512  5588  5588 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-23 19:14:39.514  5588  5634 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-61,5,main], id: 61
11-23 19:14:39.514  5588  5634 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-23 19:14:39.515  5588  5634 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-23 19:14:39.516  5588  5634 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-23 19:14:39.516  5588  5634 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 0
11-23 19:14:39.516  5588  5588 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-23 19:14:39.517  5588  5634 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
11-23 19:14:39.518  5588  5634 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
11-23 19:14:39.518  5588  5634 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-23 19:14:39.518  5588  5634 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
11-23 19:14:39.518  5588  5634 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
11-23 19:14:39.518  5588  5634 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
11-23 19:14:39.518  5588  5634 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
11-23 19:14:39.518  5588  5634 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-61,5,main], id: 61
11-23 19:14:39.519  5588  5634 D BluetoothAdapter: STATE_ON
11-23 19:14:39.521  4645  4656 D BtGatt.GattService: registerClient() - UUID=009e4a71-544e-4a91-9548-5e3301bf8e17
11-23 19:14:39.521  4645  4721 D BtGatt.GattService: onClientRegistered() - UUID=009e4a71-544e-4a91-9548-5e3301bf8e17, clientIf=5
11-23 19:14:39.523  5588  5598 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
11-23 19:14:39.524  4645  4865 D BtGatt.GattService: start scan with filters
11-23 19:14:39.529  4645  4724 D BtGatt.ScanManager: handling starting scan
11-23 19:14:39.530  5588  5634 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
11-23 19:14:39.530  5588  5634 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-23 19:14:39.530  5588  5634 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
11-23 19:14:39.530  5588  5634 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-61,5,main], id: 61
11-23 19:14:39.530  5588  5634 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-23 19:14:39.530  5588  5588 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-23 19:14:39.530  5588  5588 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-23 19:14:39.530  5588  5588 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
11-23 19:14:39.531  5588  5588 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-23 19:14:39.531  5588  5588 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-23 19:14:39.531  5588  5634 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-23 19:14:39.531  5588  5588 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
11-23 19:14:39.531  4645  4724 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f8a38f6
11-23 19:14:39.531  5588  5634 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-23 19:14:39.531  5588  5588 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-23 19:14:39.531  5588  5588 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING] Current thread: Thread[main,5,main], id: 1
11-23 19:14:39.532  5588  5634 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-23 19:14:39.532  5588  5634 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
11-23 19:14:39.532  5588  5634 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 19:14:39.532  5588  5634 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 19:14:39.532  5588  5588 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-23 19:14:39.532  5588  5634 I io.jxcore.node.ConnectionHelper: start: OK
11-23 19:14:39.535  5588  5588 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-23 19:14:39.535  5588  5588 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-23 19:14:39.535  5588  5588 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-23 19:14:39.535  5588  5588 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
11-23 19:14:39.538  4645  4721 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
11-23 19:14:39.538  4645  4721 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-23 19:14:39.539  4645  4724 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
11-23 19:14:39.544  4645  4721 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
11-23 19:14:39.544  4645  4721 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-23 19:14:39.545  4645  4724 D BtGatt.ScanManager: Starting BLE batch scan
11-23 19:14:39.545  4645  4724 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,11-23 19:14:39.555  4645  4721 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
11-23 19:14:39.555  4645  4721 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-23 19:14:39.561  4645  4721 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
11-23 19:14:39.561  4645  4721 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-23 19:14:40.036  5588  5588 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
11-23 19:14:40.036  5588  5588 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
11-23 19:14:40.036  5588  5588 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,11-23 19:14:41.786   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 19:14:42.314   929  2972 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,11-23 19:14:42.787   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 19:14:43.788   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 19:14:44.537  5588  5634 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-23 19:14:44.537  5588  5634 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
11-23 19:14:44.537  5588  5634 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,11-23 19:14:44.537  5588  5634 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,11-23 19:14:44.537  5588  5634 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-23 19:14:44.538  5588  5634 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-23 19:14:44.538  5588  5634 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,11-23 19:14:44.538  5588  5634 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-23 19:14:44.538  5588  5634 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-23 19:14:44.538  5588  5634 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
,11-23 19:14:44.538  5588  5634 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,11-23 19:14:44.539  5588  5634 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
11-23 19:14:44.539  5588  5634 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-61,5,main], id: 61
,11-23 19:14:44.539  5588  5634 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-23 19:14:44.540  5588  5634 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
11-23 19:14:44.540  5588  5634 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-61,5,main], id: 61
,11-23 19:14:44.542  5588  5634 D BluetoothAdapter: STATE_ON
11-23 19:14:44.543  4645  4856 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
11-23 19:14:44.544  5588  5634 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-23 19:14:44.545  4645  4724 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
11-23 19:14:44.545  5588  5634 D BluetoothAdapter: STATE_ON
,11-23 19:14:44.546  4645  4656 D BtGatt.GattService: stopScan() - queue size =1
11-23 19:14:44.547  4645  4865 D BtGatt.GattService: unregisterClient() - clientIf=5
11-23 19:14:44.549  5588  5634 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-23 19:14:44.549  5588  5634 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-23 19:14:44.549  5588  5634 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,11-23 19:14:44.549  5588  5634 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-61,5,main], id: 61
11-23 19:14:44.549  5588  5634 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-61,5,main], id: 61
11-23 19:14:44.549  5588  5634 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-61,5,main], id: 61
11-23 19:14:44.549  5588  5634 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-61,5,main], id: 61
11-23 19:14:44.550  5588  5634 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-23 19:14:44.550  5588  5634 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
11-23 19:14:44.550  5588  5634 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 19:14:44.550  5588  5634 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-61,5,main], id: 61
11-23 19:14:44.550  5588  5634 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-23 19:14:44.550  5588  5634 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-23 19:14:44.551  4645  4645 D BtGatt.ScanManager: awakened up at time 192055
11-23 19:14:44.552  5588  5634 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-23 19:14:44.552  5588  5634 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-23 19:14:44.554  5588  5634 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-23 19:14:44.554  5588  5634 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-23 19:14:44.554  5588  5634 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 19:14:44.554  5588  5634 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 19:14:44.554  5588  5634 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-23 19:14:44.554  5588  5634 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-23 19:14:44.554  5588  5634 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-23 19:14:44.554  5588  5588 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-23 19:14:44.554  5588  5634 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,11-23 19:14:44.554  5588  5634 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b72032b not in the list
11-23 19:14:44.554  5588  5634 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 19:14:44.554  5588  5588 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-23 19:14:44.555  5588  5634 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ac4a388 not in the list
11-23 19:14:44.555  5588  5634 D io.jxcore.node.ConnectivityMonitor: stop
11-23 19:14:44.555  5588  5634 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
11-23 19:14:44.555  5588  5588 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-23 19:14:44.555  5588  5588 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
,11-23 19:14:44.555  5588  5588 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-23 19:14:44.556  5588  5588 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
11-23 19:14:44.557  5588  5588 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-23 19:14:44.557  5588  5588 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-23 19:14:44.557  5588  5588 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-23 19:14:44.557  5588  5588 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-23 19:14:44.557  5588  5588 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED] Current thread: Thread[main,5,main], id: 1
,11-23 19:14:44.558  5588  5588 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-23 19:14:44.559  5588  5588 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-23 19:14:44.559  5588  5588 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-23 19:14:44.559  5588  5588 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
,11-23 19:14:44.571  4645  4721 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=5
,11-23 19:14:44.571  4645  4721 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-23 19:14:44.571  4645  4721 D BtGatt.GattService: current time is 192075958936
,11-23 19:14:44.572  4645  4721 D BtGatt.GattService: Batch record : [37, -47, 14, -113, 116, -46, 1, -128, -87, 56, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 81, 34, 97, 112, -14, -5, 1, -128, -91, 71, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 116, -43, -111, -91, -20, -29, 1, -128, -78, 71, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, -46, -4, -117, 6, 105, -37, 1, -128, -84, 71, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 35, 97, 126, -92, 22, -56, 1, -128, -96, 52, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
11-23 19:14:44.573  4645  4721 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
11-23 19:14:44.574  4645  4721 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
11-23 19:14:44.574  4645  4721 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,11-23 19:14:44.574  4645  4721 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
11-23 19:14:44.575  4645  4721 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
11-23 19:14:44.575  4645  4721 E BtGatt.ContextMap: Context not found for ID 5
,11-23 19:14:44.583  4645  4721 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
,11-23 19:14:44.583  4645  4721 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-23 19:14:44.583  4645  4724 D BtGatt.ScanManager: stopping BLe Batch
11-23 19:14:44.589  4645  4721 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
11-23 19:14:44.589  4645  4721 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-23 19:14:44.590  4645  4724 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-23 19:14:44.595  4645  4721 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-23 19:14:44.595  4645  4721 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-23 19:14:44.789   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 19:14:45.059  5588  5588 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-23 19:14:45.790   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 19:14:46.791   536   536 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,11-23 19:14:48.368   929  2972 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,11-23 19:14:49.557  5588  5634 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,11-23 19:14:49.562  5588  5634 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,11-23 19:14:49.563  5588  5634 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
,11-23 19:14:49.577  5588  5634 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-23 19:14:49.577  5588  5634 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-23 19:14:49.577  5588  5634 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-23 19:14:49.577  5588  5634 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-23 19:14:49.577  5588  5634 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-23 19:14:49.577  5588  5634 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-23 19:14:49.577  5588  5634 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-23 19:14:49.577  5588  5634 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-23 19:14:49.577  5588  5634 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,11-23 19:14:49.580  5588  5634 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
11-23 19:14:49.580  5588  5634 D io.jxcore.node.ConnectivityMonitor: start: OK
11-23 19:14:49.580  5588  5634 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-23 19:14:49.580  5588  5634 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
11-23 19:14:49.580  5588  5634 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
11-23 19:14:49.580  5588  5634 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,11-23 19:14:49.580  5588  5634 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
11-23 19:14:49.583  5588  5588 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-23 19:14:49.584  5588  5634 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-23 19:14:49.584  5588  5634 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-23 19:14:49.584  5588  5634 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,11-23 19:14:49.588  5588  5588 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-23 19:14:49.588  5588  5634 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-61,5,main], id: 61
11-23 19:14:49.588  5588  5634 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-23 19:14:49.589  5588  5634 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,11-23 19:14:49.589  5588  5634 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-23 19:14:49.589  5588  5634 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 0
,11-23 19:14:49.593  5588  5634 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-23 19:14:49.593  5588  5634 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
11-23 19:14:49.593  5588  5634 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
11-23 19:14:49.593  5588  5634 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
,11-23 19:14:49.593  5588  5634 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
11-23 19:14:49.594  5588  5634 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-61,5,main], id: 61
11-23 19:14:49.595  5588  5634 D BluetoothAdapter: STATE_ON
,11-23 19:14:49.597  4645  4658 D BtGatt.GattService: registerClient() - UUID=e932ba26-3851-404b-ae28-96c27b123d05
,11-23 19:14:49.598  4645  4721 D BtGatt.GattService: onClientRegistered() - UUID=e932ba26-3851-404b-ae28-96c27b123d05, clientIf=5
11-23 19:14:49.598  5588  5599 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
11-23 19:14:49.598  4645  4656 D BtGatt.GattService: start scan with filters
,11-23 19:14:49.601  5588  5634 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
,11-23 19:14:49.602  5588  5634 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-23 19:14:49.602  5588  5634 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
11-23 19:14:49.602  5588  5634 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-61,5,main], id: 61
11-23 19:14:49.602  4645  4724 D BtGatt.ScanManager: handling starting scan
11-23 19:14:49.602  5588  5634 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-23 19:14:49.602  5588  5588 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-23 19:14:49.602  5588  5588 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-23 19:14:49.602  5588  5588 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
11-23 19:14:49.602  5588  5588 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-23 19:14:49.602  5588  5588 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-23 19:14:49.603  5588  5588 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
11-23 19:14:49.603  5588  5588 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-23 19:14:49.603  5588  5588 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING] Current thread: Thread[main,5,main], id: 1
,11-23 19:14:49.604  5588  5634 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,11-23 19:14:49.604  5588  5634 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-23 19:14:49.607  5588  5634 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-23 19:14:49.607  5588  5634 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
11-23 19:14:49.607  5588  5634 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 19:14:49.607  5588  5634 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 19:14:49.607  5588  5634 I io.jxcore.node.ConnectionHelper: start: OK
11-23 19:14:49.607  5588  5588 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
,11-23 19:14:49.608  4645  4721 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
11-23 19:14:49.608  4645  4721 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-23 19:14:49.608  4645  4724 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
11-23 19:14:49.609  5588  5634 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-23 19:14:49.609  5588  5634 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,11-23 19:14:49.609  5588  5634 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
11-23 19:14:49.610  5588  5634 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
11-23 19:14:49.610  5588  5634 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-23 19:14:49.610  5588  5634 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-23 19:14:49.610  5588  5634 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-23 19:14:49.610  5588  5634 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
11-23 19:14:49.611  5588  5588 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-23 19:14:49.611  5588  5588 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-23 19:14:49.611  5588  5588 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-23 19:14:49.611  5588  5634 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-23 19:14:49.611  5588  5588 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
11-23 19:14:49.611  5588  5634 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-23 19:14:49.611  5588  5634 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
11-23 19:14:49.611  5588  5634 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-23 19:14:49.611  5588  5634 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
11-23 19:14:49.611  5588  5634 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-61,5,main], id: 61
11-23 19:14:49.611  5588  5634 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-23 19:14:49.611  5588  5634 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
11-23 19:14:49.611  5588  5634 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-61,5,main], id: 61
,11-23 19:14:49.612  5588  5634 D BluetoothAdapter: STATE_ON
11-23 19:14:49.613  4645  4865 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
11-23 19:14:49.613  5588  5634 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-23 19:14:49.613  5588  5634 D BluetoothAdapter: STATE_ON
11-23 19:14:49.614  4645  4656 D BtGatt.GattService: stopScan() - queue size =1
11-23 19:14:49.615  4645  4658 D BtGatt.GattService: unregisterClient() - clientIf=5
11-23 19:14:49.615  5588  5634 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-23 19:14:49.615  5588  5634 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-23 19:14:49.615  4645  4721 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
11-23 19:14:49.615  5588  5634 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
11-23 19:14:49.615  4645  4721 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-23 19:14:49.615  5588  5634 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-61,5,main], id: 61
11-23 19:14:49.615  5588  5634 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-61,5,main], id: 61
11-23 19:14:49.615  4645  4724 D BtGatt.ScanManager: Starting BLE batch scan
11-23 19:14:49.615  4645  4724 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
11-23 19:14:49.615  5588  5634 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-61,5,main], id: 61
11-23 19:14:49.616  5588  5634 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-61,5,main], id: 61
11-23 19:14:49.616  5588  5634 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-23 19:14:49.616  5588  5634 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
11-23 19:14:49.616  5588  5634 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 19:14:49.616  5588  5634 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-61,5,main], id: 61
11-23 19:14:49.616  5588  5634 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-23 19:14:49.616  5588  5634 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-23 19:14:49.616  5588  5634 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-23 19:14:49.617  5588  5634 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-23 19:14:49.617  5588  5634 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-23 19:14:49.617  5588  5634 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-23 19:14:49.618  5588  5634 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 19:14:49.618  5588  5634 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 19:14:49.618  5588  5634 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-23 19:14:49.618  5588  5588 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-23 19:14:49.618  5588  5634 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-23 19:14:49.618  5588  5634 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-23 19:14:49.618  5588  5588 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-23 19:14:49.618  5588  5634 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-23 19:14:49.618  5588  5588 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-23 19:14:49.618  5588  5634 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b72032b not in the list
11-23 19:14:49.618  5588  5634 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 19:14:49.618  5588  5588 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-23 19:14:49.618  5588  5634 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ac4a388 not in the list
11-23 19:14:49.618  5588  5588 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-23 19:14:49.618  5588  5634 D io.jxcore.node.ConnectivityMonitor: stop
11-23 19:14:49.618  5588  5588 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
11-23 19:14:49.618  5588  5634 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
11-23 19:14:49.618  5588  5588 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-23 19:14:49.618  5588  5588 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-23 19:14:49.618  5588  5588 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-23 19:14:49.618  5588  5588 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-23 19:14:49.619  5588  5588 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED] Current thread: Thread[main,5,main], id: 1
11-23 19:14:49.619  5588  5588 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-23 19:14:49.620  5588  5588 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-23 19:14:49.620  5588  5588 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-23 19:14:49.620  5588  5588 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-23 19:14:49.621  5588  5634 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-23 19:14:49.621  5588  5634 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-23 19:14:49.622  5588  5634 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-23 19:14:49.622  5588  5634 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 19:14:49.622  5588  5634 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 19:14:49.622  5588  5634 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-23 19:14:49.623  5588  5634 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-23 19:14:49.623  5588  5634 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 19:14:49.623  5588  5634 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ac4a388 not in the list
11-23 19:14:49.623  5588  5634 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
11-23 19:14:49.625  5588  5634 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-23 19:14:49.625  5588  5634 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
11-23 19:14:49.627  4645  4721 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
11-23 19:14:49.627  4645  4721 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-23 19:14:49.635  5588  5634 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-23 19:14:49.635  5588  5634 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-23 19:14:49.635  5588  5634 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-23 19:14:49.635  5588  5634 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-23 19:14:49.635  5588  5634 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-23 19:14:49.635  5588  5634 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-23 19:14:49.635  5588  5634 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-23 19:14:49.635  5588  5634 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-23 19:14:49.635  5588  5634 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
11-23 19:14:49.635  4645  4721 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
11-23 19:14:49.635  4645  4721 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-23 19:14:49.636  4645  4724 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
11-23 19:14:49.637  5588  5634 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
11-23 19:14:49.637  5588  5634 D io.jxcore.node.ConnectivityMonitor: start: OK
11-23 19:14:49.637  5588  5634 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-23 19:14:49.638  5588  5634 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
11-23 19:14:49.638  5588  5634 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
11-23 19:14:49.638  5588  5634 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-23 19:14:49.638  5588  5634 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
11-23 19:14:49.640  5588  5588 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-23 19:14:49.641  4645  4721 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-23 19:14:49.641  4645  4721 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-23 19:14:49.641  4645  4721 E BtGatt.ContextMap: Context not found for ID 5
11-23 19:14:49.642  5588  5588 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-23 19:14:49.644  5588  5634 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-23 19:14:49.644  5588  5634 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-23 19:14:49.644  5588  5634 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,11-23 19:14:49.648  4645  4721 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
11-23 19:14:49.648  4645  4721 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-23 19:14:49.648  4645  4724 D BtGatt.ScanManager: stopping BLe Batch
11-23 19:14:49.649  5588  5634 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-61,5,main], id: 61
11-23 19:14:49.649  5588  5634 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-23 19:14:49.649  5588  5634 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-23 19:14:49.649  5588  5634 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-23 19:14:49.649  5588  5634 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 0
11-23 19:14:49.652  5588  5634 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-23 19:14:49.652  5588  5634 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
11-23 19:14:49.652  5588  5634 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
11-23 19:14:49.652  5588  5634 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
11-23 19:14:49.652  5588  5634 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
11-23 19:14:49.652  5588  5634 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-61,5,main], id: 61
11-23 19:14:49.653  5588  5634 D BluetoothAdapter: STATE_ON
11-23 19:14:49.653  4645  4721 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
11-23 19:14:49.653  4645  4721 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-23 19:14:49.653  4645  4724 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
11-23 19:14:49.654  4645  4865 D BtGatt.GattService: registerClient() - UUID=08706a75-f6b4-4486-be7a-a028de6a02b5
11-23 19:14:49.656  4645  4721 D BtGatt.GattService: onClientRegistered() - UUID=08706a75-f6b4-4486-be7a-a028de6a02b5, clientIf=5
11-23 19:14:49.656  5588  5598 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
11-23 19:14:49.656  4645  4656 D BtGatt.GattService: start scan with filters
11-23 19:14:49.658  4645  4721 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-23 19:14:49.658  4645  4721 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-23 19:14:49.661  5588  5634 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
11-23 19:14:49.661  4645  4724 D BtGatt.ScanManager: handling starting scan
11-23 19:14:49.661  5588  5634 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-23 19:14:49.661  5588  5634 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
11-23 19:14:49.661  5588  5634 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-61,5,main], id: 61
11-23 19:14:49.661  5588  5634 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-23 19:14:49.662  5588  5588 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-23 19:14:49.662  5588  5588 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-23 19:14:49.662  5588  5588 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
11-23 19:14:49.662  5588  5588 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-23 19:14:49.662  5588  5588 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-23 19:14:49.662  5588  5588 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
11-23 19:14:49.662  5588  5588 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-23 19:14:49.662  5588  5588 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING] Current thread: Thread[main,5,main], id: 1
11-23 19:14:49.663  5588  5634 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-23 19:14:49.663  5588  5634 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-23 19:14:49.665  5588  5634 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-23 19:14:49.665  5588  5634 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
11-23 19:14:49.666  5588  5634 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 19:14:49.666  5588  5634 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 19:14:49.666  5588  5634 I io.jxcore.node.ConnectionHelper: start: OK
11-23 19:14:49.666  5588  5588 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-23 19:14:49.666  4645  4721 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
11-23 19:14:49.666  4645  4721 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-23 19:14:49.666  4645  4724 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
11-23 19:14:49.668  5588  5588 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-23 19:14:49.668  5588  5588 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-23 19:14:49.668  5588  5588 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-23 19:14:49.668  5588  5588 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
11-23 19:14:49.671  4645  4721 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
11-23 19:14:49.671  4645  4721 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-23 19:14:49.671  4645  4724 D BtGatt.ScanManager: Starting BLE batch scan
11-23 19:14:49.671  4645  4724 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
11-23 19:14:49.680  4645  4721 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
11-23 19:14:49.680  4645  4721 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-23 19:14:49.684  4645  4721 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
11-23 19:14:49.684  4645  4721 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-23 19:14:50.169  5588  5588 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
11-23 19:14:50.170  5588  5588 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,11-23 19:14:50.170  5588  5588 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,11-23 19:14:53.987   929  2970 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-23 19:14:54.666  5588  5634 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-23 19:14:54.667  5588  5634 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
11-23 19:14:54.667  5588  5634 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
11-23 19:14:54.667  5588  5634 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,11-23 19:14:54.667  5588  5634 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-23 19:14:54.667  5588  5634 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-23 19:14:54.667  5588  5634 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
11-23 19:14:54.667  5588  5634 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-23 19:14:54.668  5588  5634 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-23 19:14:54.668  5588  5634 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
11-23 19:14:54.668  5588  5634 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-23 19:14:54.668  5588  5634 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
,11-23 19:14:54.669  5588  5634 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-61,5,main], id: 61
11-23 19:14:54.669  5588  5634 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-23 19:14:54.669  5588  5634 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
11-23 19:14:54.669  5588  5634 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-61,5,main], id: 61
11-23 19:14:54.672  5588  5634 D BluetoothAdapter: STATE_ON
11-23 19:14:54.673  4645  4865 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
11-23 19:14:54.676  4645  4724 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-23 19:14:54.676  5588  5634 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
,11-23 19:14:54.678  5588  5634 D BluetoothAdapter: STATE_ON
11-23 19:14:54.680  4645  4856 D BtGatt.GattService: stopScan() - queue size =1
11-23 19:14:54.681  4645  4658 D BtGatt.GattService: unregisterClient() - clientIf=5
11-23 19:14:54.682  5588  5634 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-23 19:14:54.683  5588  5634 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
,11-23 19:14:54.683  5588  5634 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
11-23 19:14:54.683  5588  5634 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-61,5,main], id: 61
11-23 19:14:54.683  4645  4645 D BtGatt.ScanManager: awakened up at time 202187
11-23 19:14:54.683  5588  5634 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-61,5,main], id: 61
11-23 19:14:54.684  5588  5634 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-61,5,main], id: 61
,11-23 19:14:54.684  5588  5634 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-61,5,main], id: 61
11-23 19:14:54.684  5588  5634 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-23 19:14:54.684  5588  5634 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
11-23 19:14:54.684  5588  5634 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 19:14:54.684  5588  5634 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-61,5,main], id: 61
11-23 19:14:54.684  5588  5634 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,11-23 19:14:54.685  5588  5634 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-23 19:14:54.686  5588  5634 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-23 19:14:54.687  5588  5634 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-23 19:14:54.688  5588  5634 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-23 19:14:54.689  5588  5634 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-23 19:14:54.689  5588  5634 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
,11-23 19:14:54.689  5588  5634 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 19:14:54.689  5588  5588 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-23 19:14:54.690  5588  5588 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-23 19:14:54.690  5588  5588 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-23 19:14:54.690  5588  5588 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-23 19:14:54.690  5588  5588 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
,11-23 19:14:54.690  5588  5588 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
11-23 19:14:54.690  5588  5588 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-23 19:14:54.690  5588  5588 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-23 19:14:54.691  5588  5588 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-23 19:14:54.691  5588  5588 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-23 19:14:54.691  5588  5588 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED] Current thread: Thread[main,5,main], id: 1
11-23 19:14:54.691  5588  5588 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
,11-23 19:14:54.693  5588  5588 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-23 19:14:54.693  5588  5588 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-23 19:14:54.693  5588  5588 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
,11-23 19:14:54.706  4645  4721 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=5
,11-23 19:14:54.707  4645  4721 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-23 19:14:54.707  4645  4721 D BtGatt.GattService: current time is 202211358572
11-23 19:14:54.707  4645  4721 D BtGatt.GattService: Batch record : [-46, -4, -117, 6, 105, -37, 1, -128, -84, 60, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 37, -47, 14, -113, 116, -46, 1, -128, -87, 65, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 116, -43, -111, -91, -20, -29, 1, -128, -78, 61, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 81, 34, 97, 112, -14, -5, 1, -128, -90, 74, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 35, 97, 126, -92, 22, -56, 1, -128, -98, 73, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
11-23 19:14:54.707  4645  4721 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
11-23 19:14:54.708  4645  4721 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
11-23 19:14:54.708  4645  4721 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
11-23 19:14:54.708  4645  4721 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
11-23 19:14:54.708  4645  4721 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,11-23 19:14:54.716  4645  4721 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
,11-23 19:14:54.716  4645  4721 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-23 19:14:54.716  4645  4724 D BtGatt.ScanManager: stopping BLe Batch
,11-23 19:14:54.722  4645  4721 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,11-23 19:14:54.722  4645  4721 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-23 19:14:54.722  4645  4724 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-23 19:14:54.728  4645  4721 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,11-23 19:14:54.729  4645  4721 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-23 19:14:55.191  5588  5588 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-23 19:14:55.192  5588  5588 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-23 19:14:55.192  5588  5588 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,11-23 19:14:57.438   929  2972 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,11-23 19:14:59.691  5588  5634 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-23 19:14:59.691  5588  5634 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-23 19:14:59.691  5588  5634 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-23 19:14:59.691  5588  5634 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,11-23 19:14:59.692  5588  5634 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-23 19:14:59.692  5588  5634 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,11-23 19:14:59.692  5588  5634 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-23 19:14:59.692  5588  5634 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b72032b not in the list
11-23 19:14:59.693  5588  5634 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 19:14:59.693  5588  5634 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ac4a388 not in the list
11-23 19:14:59.693  5588  5634 D io.jxcore.node.ConnectivityMonitor: stop
,11-23 19:14:59.693  5588  5634 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
,11-23 19:14:59.698  5588  5634 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
,11-23 19:14:59.698  5588  5634 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-23 19:14:59.701  5588  5634 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-23 19:14:59.702  5588  5634 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 19:14:59.702  5588  5634 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 19:14:59.702  5588  5634 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-23 19:14:59.702  5588  5634 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-23 19:14:59.702  5588  5634 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 19:14:59.703  5588  5634 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ac4a388 not in the list
11-23 19:14:59.704  5588  5634 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
11-23 19:14:59.705  5588  5634 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-23 19:14:59.706  5588  5634 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-23 19:14:59.706  5588  5634 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-23 19:14:59.706  5588  5634 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-23 19:14:59.706  5588  5634 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-23 19:14:59.706  5588  5634 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b72032b not in the list
11-23 19:14:59.707  5588  5634 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 19:14:59.707  5588  5634 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ac4a388 not in the list
11-23 19:14:59.707  5588  5634 D io.jxcore.node.ConnectivityMonitor: stop
11-23 19:14:59.707  5588  5634 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-23 19:14:59.707  5588  5634 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-23 19:14:59.710  5588  5634 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-23 19:14:59.711  5588  5634 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
,11-23 19:14:59.711  5588  5634 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 19:14:59.711  5588  5634 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-23 19:14:59.711  5588  5634 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-23 19:14:59.711  5588  5634 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 19:14:59.711  5588  5634 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ac4a388 not in the list
11-23 19:14:59.714  5588  5634 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
11-23 19:14:59.714  5588  5634 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-23 19:14:59.714  5588  5634 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-23 19:14:59.715  5588  5634 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-23 19:14:59.715  5588  5634 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-23 19:14:59.715  5588  5634 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-23 19:14:59.715  5588  5634 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b72032b not in the list
11-23 19:14:59.717  5588  5634 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 19:14:59.717  5588  5634 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ac4a388 not in the list
,11-23 19:14:59.717  5588  5634 D io.jxcore.node.ConnectivityMonitor: stop
11-23 19:14:59.717  5588  5634 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-23 19:14:59.718  5588  5634 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-23 19:14:59.720  5588  5634 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-23 19:14:59.720  5588  5634 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 19:14:59.720  5588  5634 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 19:14:59.720  5588  5634 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-23 19:14:59.720  5588  5634 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,11-23 19:14:59.720  5588  5634 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 19:14:59.721  5588  5634 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ac4a388 not in the list
11-23 19:14:59.721  5588  5634 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
11-23 19:14:59.722  5588  5634 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-23 19:14:59.722  5588  5634 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-23 19:14:59.722  5588  5634 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-23 19:14:59.722  5588  5634 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-23 19:14:59.722  5588  5634 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-23 19:14:59.723  5588  5634 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b72032b not in the list
11-23 19:14:59.723  5588  5634 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 19:14:59.723  5588  5634 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ac4a388 not in the list
11-23 19:14:59.723  5588  5634 D io.jxcore.node.ConnectivityMonitor: stop
11-23 19:14:59.723  5588  5634 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-23 19:14:59.723  5588  5634 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-23 19:14:59.725  5588  5634 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-23 19:14:59.725  5588  5634 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 19:14:59.725  5588  5634 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 19:14:59.725  5588  5634 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-23 19:14:59.725  5588  5634 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-23 19:14:59.726  5588  5634 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 19:14:59.726  5588  5634 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ac4a388 not in the list
11-23 19:14:59.727  5588  5634 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
,11-23 19:14:59.727  5588  5634 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-23 19:14:59.727  5588  5634 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-23 19:14:59.727  5588  5634 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-23 19:14:59.727  5588  5634 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-23 19:14:59.727  5588  5634 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-23 19:14:59.728  5588  5634 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b72032b not in the list
11-23 19:14:59.728  5588  5634 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-23 19:14:59.728  5588  5634 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ac4a388 not in the list
11-23 19:14:59.728  5588  5634 D io.jxcore.node.ConnectivityMonitor: stop
11-23 19:14:59.728  5588  5634 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-23 19:14:59.728  5588  5634 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-23 19:14:59.730  5588  5634 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-23 19:14:59.730  5588  5634 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 19:14:59.730  5588  5634 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
,11-23 19:14:59.730  5588  5634 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-23 19:14:59.730  5588  5634 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-23 19:14:59.730  5588  5634 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 19:14:59.730  5588  5634 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ac4a388 not in the list
11-23 19:14:59.731  5588  5634 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
11-23 19:14:59.732  5588  5634 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-23 19:14:59.732  5588  5634 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-23 19:14:59.732  5588  5634 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
11-23 19:14:59.732  5588  5634 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-23 19:14:59.732  5588  5634 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-23 19:14:59.732  5588  5634 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
11-23 19:14:59.732  5588  5634 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-23 19:14:59.732  5588  5634 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-23 19:14:59.732  5588  5634 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-23 19:14:59.733  5588  5634 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-23 19:14:59.733  5588  5634 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-23 19:14:59.733  5588  5634 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-23 19:14:59.733  5588  5634 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-23 19:14:59.733  5588  5634 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b72032b not in the list
11-23 19:14:59.733  5588  5634 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-23 19:14:59.733  5588  5634 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ac4a388 not in the list
11-23 19:14:59.733  5588  5634 D io.jxcore.node.ConnectivityMonitor: stop
11-23 19:14:59.733  5588  5634 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-23 19:14:59.733  5588  5634 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-23 19:14:59.735  5588  5634 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-23 19:14:59.735  5588  5634 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 19:14:59.735  5588  5634 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 19:14:59.735  5588  5634 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-23 19:14:59.735  5588  5634 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-23 19:14:59.736  5588  5634 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 19:14:59.736  5588  5634 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ac4a388 not in the list
11-23 19:14:59.737  5588  5634 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
11-23 19:14:59.737  5588  5634 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
11-23 19:14:59.737  5588  5634 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,11-23 19:14:59.742  5588  5634 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
11-23 19:14:59.742  5588  5634 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
11-23 19:14:59.742  5588  5634 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
11-23 19:14:59.743  5588  5634 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
11-23 19:14:59.743  5588  5634 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
11-23 19:14:59.743  5588  5634 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
11-23 19:14:59.743  5588  5634 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
11-23 19:14:59.743  5588  5634 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
11-23 19:14:59.743  5588  5634 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
11-23 19:14:59.743  5588  5634 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
,11-23 19:14:59.743  5588  5634 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
,11-23 19:14:59.743  5588  5634 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
11-23 19:14:59.743  5588  5634 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
11-23 19:14:59.743  5588  5634 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
11-23 19:14:59.743  5588  5634 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
,11-23 19:14:59.744  5588  5634 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
11-23 19:14:59.744  5588  5634 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
11-23 19:14:59.744  5588  5634 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
11-23 19:14:59.744  5588  5634 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
11-23 19:14:59.744  5588  5634 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
,11-23 19:14:59.744  5588  5634 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
11-23 19:14:59.744  5588  5634 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
11-23 19:14:59.744  5588  5634 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
,11-23 19:14:59.744  5588  5634 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
11-23 19:14:59.744  5588  5634 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
11-23 19:14:59.744  5588  5634 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
,11-23 19:14:59.744  5588  5634 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
11-23 19:14:59.744  5588  5634 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
11-23 19:14:59.745  5588  5634 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
,11-23 19:14:59.745  5588  5634 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
11-23 19:14:59.745  5588  5634 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
11-23 19:14:59.745  5588  5634 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
11-23 19:14:59.745  5588  5634 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
11-23 19:14:59.746  5588  5634 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
11-23 19:14:59.746  5588  5634 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
,11-23 19:14:59.746  5588  5634 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
11-23 19:14:59.746  5588  5634 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
11-23 19:14:59.746  5588  5634 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
11-23 19:14:59.746  5588  5634 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
11-23 19:14:59.746  5588  5634 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
11-23 19:14:59.746  5588  5634 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
11-23 19:14:59.751  5588  5634 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
11-23 19:14:59.752  5588  5634 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
11-23 19:14:59.752  5588  5634 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
,11-23 19:14:59.753  5588  5634 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
11-23 19:14:59.753  5588  5634 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
11-23 19:14:59.753  5588  5634 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
11-23 19:14:59.753  5588  5634 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,11-23 19:14:59.753  5588  5634 E io.jxcore.node.ConnectionHelper: connect: Callback is null
11-23 19:14:59.754  5588  5648 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 125)
11-23 19:14:59.755  5588  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: tryToConnect:  socketConnectSucceeded = false, mIsShuttingDown = false
11-23 19:14:59.755  5588  5634 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-23 19:14:59.755  5588  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: socket closed
11-23 19:14:59.755  5588  5634 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-23 19:14:59.755  5588  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: SYSTEM_DECIDED_INSECURE_RFCOMM_SOCKET_PORT
11-23 19:14:59.755  5588  5634 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-23 19:14:59.755  5588  5634 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-23 19:14:59.755  5588  5634 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-23 19:14:59.755  5588  5634 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
11-23 19:14:59.756  5588  5634 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b72032b not in the list
11-23 19:14:59.756  5588  5634 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 19:14:59.756  5588  5634 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ac4a388 not in the list
11-23 19:14:59.756  5588  5634 D io.jxcore.node.ConnectivityMonitor: stop
11-23 19:14:59.756  5588  5634 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-23 19:14:59.757  5588  5634 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-23 19:14:59.757  5588  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 125
11-23 19:14:59.760  4656  4656 W Binder_1: type=1400 audit(0.0:113): avc: denied { ioctl } for path="socket:[31592]" dev="sockfs" ino=31592 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,11-23 19:14:59.760  4656  4656 W Binder_1: type=1400 audit(0.0:114): avc: denied { ioctl } for path="socket:[31592]" dev="sockfs" ino=31592 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,11-23 19:14:59.758  5588  5634 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-23 19:14:59.758  5588  5634 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
,11-23 19:14:59.758  5588  5634 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 19:14:59.759  5588  5634 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-23 19:14:59.759  5588  5634 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-23 19:14:59.759  5588  5634 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 19:14:59.759  5588  5634 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ac4a388 not in the list
11-23 19:14:59.760  5588  5634 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
11-23 19:14:59.760  5588  5648 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: connecting
,11-23 19:14:59.760  5588  5648 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-23 19:14:59.760  5588  5634 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-23 19:14:59.761  5588  5634 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-23 19:14:59.761  5588  5634 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-23 19:14:59.761  5588  5634 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-23 19:14:59.761  5588  5634 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-23 19:14:59.761  5588  5634 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b72032b not in the list
11-23 19:14:59.761  5588  5634 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 19:14:59.761  5588  5634 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ac4a388 not in the list
11-23 19:14:59.761  5588  5634 D io.jxcore.node.ConnectivityMonitor: stop
11-23 19:14:59.761  5588  5634 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-23 19:14:59.761  5588  5634 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-23 19:14:59.762  5588  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close
11-23 19:14:59.762  5588  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Trying to close the Bluetooth socket... (thread ID: 125)
11-23 19:14:59.763  5588  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Bluetooth socket closed (thread ID: 125)
11-23 19:14:59.763  5588  5648 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: connect, socket closed
11-23 19:14:59.763  5588  5648 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: socketConnectSucceeded false
11-23 19:14:59.763  5588  5648 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 125)
11-23 19:14:59.764  5588  5634 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-23 19:14:59.764  5588  5634 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 19:14:59.764  5588  5634 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 19:14:59.764  5588  5634 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-23 19:14:59.764  5588  5634 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-23 19:14:59.764  5588  5634 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 19:14:59.764  5588  5634 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ac4a388 not in the list
11-23 19:14:59.765  5588  5634 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
11-23 19:14:59.765  5588  5634 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-23 19:14:59.765  5588  5634 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is adv,ertising: false - Stop operation: Should start/stop everything
11-23 19:14:59.766  5588  5634 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-23 19:14:59.766  5588  5634 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-23 19:14:59.766  5588  5634 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-23 19:14:59.766  5588  5634 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b72032b not in the list
11-23 19:14:59.766  5588  5634 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 19:14:59.766  5588  5634 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ac4a388 not in the list
11-23 19:14:59.766  5588  5634 D io.jxcore.node.ConnectivityMonitor: stop
11-23 19:14:59.766  5588  5634 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-23 19:14:59.766  5588  5634 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-23 19:14:59.768  5588  5634 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-23 19:14:59.768  5588  5634 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 19:14:59.768  5588  5634 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 19:14:59.768  5588  5634 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-23 19:14:59.768  5588  5634 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-23 19:14:59.768  5588  5634 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 19:14:59.768  5588  5634 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ac4a388 not in the list
11-23 19:14:59.769  5588  5634 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
11-23 19:14:59.769  5588  5634 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
11-23 19:14:59.769  5588  5634 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
11-23 19:14:59.769  5588  5634 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
11-23 19:14:59.769  5588  5634 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
11-23 19:14:59.769  5588  5634 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
11-23 19:14:59.770  5588  5634 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
11-23 19:14:59.770  5588  5634 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
11-23 19:14:59.770  5588  5634 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
,11-23 19:14:59.770  5588  5634 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
11-23 19:14:59.770  5588  5634 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
11-23 19:14:59.770  5588  5634 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
11-23 19:14:59.770  5588  5634 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-23 19:14:59.770  5588  5634 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-23 19:14:59.770  5588  5634 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-23 19:14:59.770  5588  5634 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-23 19:14:59.770  5588  5634 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-23 19:14:59.770  5588  5634 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b72032b not in the list
11-23 19:14:59.770  5588  5634 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 19:14:59.770  5588  5634 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ac4a388 not in the list
,11-23 19:14:59.770  5588  5634 D io.jxcore.node.ConnectivityMonitor: stop
11-23 19:14:59.771  5588  5634 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-23 19:14:59.771  5588  5634 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-23 19:14:59.772  5588  5634 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-23 19:14:59.772  5588  5634 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 19:14:59.773  5588  5634 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 19:14:59.773  5588  5634 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-23 19:14:59.773  5588  5634 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,11-23 19:14:59.773  5588  5634 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 19:14:59.773  5588  5634 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ac4a388 not in the list
11-23 19:14:59.773  5588  5634 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-23 19:14:59.773  5588  5634 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-23 19:14:59.774  5588  5634 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b72032b not in the list
11-23 19:14:59.774  5588  5634 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 19:14:59.774  5588  5634 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ac4a388 not in the list
11-23 19:14:59.774  5588  5634 D io.jxcore.node.ConnectivityMonitor: stop
,11-23 19:15:00.468   929  2972 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,11-23 19:15:03.502   929  2972 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,11-23 19:15:04.774  5588  5634 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 19:15:04.775  5588  5634 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ac4a388 not in the list
,11-23 19:15:04.775  5588  5634 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-23 19:15:04.775  5588  5634 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,11-23 19:15:04.775  5588  5634 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b72032b not in the list
11-23 19:15:04.776  5588  5634 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-23 19:15:04.776  5588  5634 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,11-23 19:15:04.776  5588  5634 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,11-23 19:15:04.776  5588  5634 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,11-23 19:15:04.776  5588  5634 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,11-23 19:15:04.777  5588  5634 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b72032b not in the list
11-23 19:15:04.777  5588  5634 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-23 19:15:04.777  5588  5634 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ac4a388 not in the list
11-23 19:15:04.777  5588  5634 D io.jxcore.node.ConnectivityMonitor: stop
,11-23 19:15:04.777  5588  5634 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-23 19:15:04.778  5588  5634 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-23 19:15:04.781  5588  5634 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-23 19:15:04.781  5588  5634 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 19:15:04.781  5588  5634 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 19:15:04.782  5588  5634 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-23 19:15:04.782  5588  5634 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-23 19:15:04.782  5588  5634 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-23 19:15:04.782  5588  5634 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ac4a388 not in the list
11-23 19:15:04.786  5588  5634 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
11-23 19:15:04.787  5588  5634 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-23 19:15:04.787  5588  5634 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
,11-23 19:15:04.793  5588  5634 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,11-23 19:15:04.794  5588  5634 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
11-23 19:15:04.794  5588  5634 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
11-23 19:15:04.794  5588  5634 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
11-23 19:15:04.794  5588  5650 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
11-23 19:15:04.795  5588  5634 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
11-23 19:15:04.795  5588  5634 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
11-23 19:15:04.795  5588  5588 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
,11-23 19:15:04.795  5588  5634 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-23 19:15:04.795  5588  5634 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
11-23 19:15:04.795  5588  5634 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
11-23 19:15:04.795  5588  5650 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-23 19:15:04.795  5588  5634 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
11-23 19:15:04.795  5588  5634 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
,11-23 19:15:04.793  4656  4656 W Binder_1: type=1400 audit(0.0:115): avc: denied { ioctl } for path="socket:[29606]" dev="sockfs" ino=29606 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-23 19:15:04.793  4656  4656 W Binder_1: type=1400 audit(0.0:116): avc: denied { ioctl } for path="socket:[29606]" dev="sockfs" ino=29606 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,11-23 19:15:04.796  5588  5634 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
,11-23 19:15:04.796  5588  5634 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
11-23 19:15:04.796  5588  5634 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b72032b not in the list
11-23 19:15:04.796  5588  5634 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-23 19:15:04.796  5588  5634 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-23 19:15:04.796  5588  5588 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
,11-23 19:15:04.797  5588  5634 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-23 19:15:04.797  5588  5634 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
11-23 19:15:04.797  5588  5634 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-23 19:15:04.797  5588  5634 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-23 19:15:04.798  5588  5650 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
11-23 19:15:04.798  5588  5650 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
11-23 19:15:04.798  5588  5650 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
11-23 19:15:04.798  5588  5634 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
,11-23 19:15:04.798  5588  5634 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-23 19:15:04.798  5588  5634 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 19:15:04.798  5588  5634 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 19:15:04.799  5588  5634 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ac4a388 not in the list
11-23 19:15:04.799  5588  5634 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-23 19:15:04.799  5588  5588 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-23 19:15:04.799  5588  5634 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-23 19:15:04.799  5588  5588 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-23 19:15:04.799  5588  5634 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,11-23 19:15:04.799  5588  5588 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-23 19:15:04.799  5588  5634 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-23 19:15:04.799  5588  5634 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
11-23 19:15:04.799  5588  5588 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
11-23 19:15:04.799  5588  5634 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b72032b not in the list
11-23 19:15:04.799  5588  5588 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-23 19:15:04.799  5588  5634 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-23 19:15:04.799  5588  5634 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ac4a388 not in the list
11-23 19:15:04.799  5588  5634 D io.jxcore.node.ConnectivityMonitor: stop
11-23 19:15:04.800  5588  5634 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-23 19:15:04.800  5588  5634 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-23 19:15:04.801  5588  5634 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-23 19:15:04.801  5588  5634 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 19:15:04.801  5588  5634 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 19:15:04.801  5588  5634 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,11-23 19:15:04.801  5588  5634 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-23 19:15:04.801  5588  5634 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 19:15:04.801  5588  5634 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ac4a388 not in the list
11-23 19:15:04.803  5588  5634 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
11-23 19:15:04.803  5588  5634 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
,11-23 19:15:04.803  5588  5634 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
11-23 19:15:04.803  5588  5634 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-23 19:15:04.803  5588  5634 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-23 19:15:04.804  5588  5634 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-23 19:15:04.804  5588  5634 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-23 19:15:04.804  5588  5634 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,11-23 19:15:04.804  5588  5634 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-23 19:15:04.804  5588  5634 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-23 19:15:04.804  5588  5634 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b72032b not in the list
11-23 19:15:04.804  5588  5634 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 19:15:04.804  5588  5634 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ac4a388 not in the list
11-23 19:15:04.804  5588  5634 D io.jxcore.node.ConnectivityMonitor: stop
,11-23 19:15:04.804  5588  5634 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-23 19:15:04.804  5588  5634 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-23 19:15:04.806  5588  5634 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-23 19:15:04.806  5588  5634 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 19:15:04.806  5588  5634 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 19:15:04.806  5588  5634 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,11-23 19:15:04.806  5588  5634 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,11-23 19:15:04.806  5588  5634 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-23 19:15:04.806  5588  5634 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ac4a388 not in the list
11-23 19:15:04.813  5588  5634 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-23 19:15:04.813  5588  5634 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-23 19:15:04.813  5588  5634 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-23 19:15:04.813  5588  5634 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,11-23 19:15:04.814  5588  5634 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-23 19:15:04.814  5588  5634 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b72032b not in the list
11-23 19:15:04.814  5588  5634 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 19:15:04.814  5588  5634 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ac4a388 not in the list
11-23 19:15:04.814  5588  5634 D io.jxcore.node.ConnectivityMonitor: stop
,11-23 19:15:04.814  5588  5634 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-23 19:15:04.814  5588  5634 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-23 19:15:04.815  5588  5634 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-23 19:15:04.815  5588  5634 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 19:15:04.815  5588  5634 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 19:15:04.815  5588  5634 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,11-23 19:15:04.815  5588  5634 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-23 19:15:04.815  5588  5634 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 19:15:04.816  5588  5634 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ac4a388 not in the list
11-23 19:15:04.816  5588  5634 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-23 19:15:04.816  5588  5634 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,11-23 19:15:04.816  5588  5634 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-23 19:15:04.816  5588  5634 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-23 19:15:04.817  5588  5634 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-23 19:15:04.817  5588  5634 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b72032b not in the list
11-23 19:15:04.817  5588  5634 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-23 19:15:04.817  5588  5634 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ac4a388 not in the list
11-23 19:15:04.817  5588  5634 D io.jxcore.node.ConnectivityMonitor: stop
11-23 19:15:04.817  5588  5634 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-23 19:15:04.817  5588  5634 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-23 19:15:04.818  5588  5634 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
,11-23 19:15:04.818  5588  5634 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 19:15:04.818  5588  5634 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 19:15:04.818  5588  5634 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-23 19:15:04.818  5588  5634 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-23 19:15:04.818  5588  5634 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 19:15:04.818  5588  5634 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ac4a388 not in the list
,11-23 19:15:04.819  5588  5634 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
11-23 19:15:04.820  5588  5634 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
11-23 19:15:04.820  5588  5634 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
11-23 19:15:04.820  5588  5634 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
11-23 19:15:04.820  5588  5634 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
,11-23 19:15:04.820  5588  5634 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
11-23 19:15:04.822  5588  5634 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
11-23 19:15:04.822  5588  5634 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
,11-23 19:15:04.822  5588  5634 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
11-23 19:15:04.822  5588  5634 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
,11-23 19:15:04.823  5588  5634 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
11-23 19:15:04.823  5588  5634 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
11-23 19:15:04.823  5588  5634 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
11-23 19:15:04.823  5588  5634 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
,11-23 19:15:04.823  5588  5634 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
,11-23 19:15:04.823  5588  5634 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
11-23 19:15:04.824  5588  5634 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
11-23 19:15:04.824  5588  5634 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
11-23 19:15:04.824  5588  5634 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
11-23 19:15:04.824  5588  5634 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
,11-23 19:15:04.825  5588  5634 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-23 19:15:04.825  5588  5634 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@427b491 added. We now have 3 listener(s)
11-23 19:15:04.825  5588  5634 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-23 19:15:04.827  5588  5634 D BluetoothAdapter: enable(): BT is already enabled..!
11-23 19:15:04.827   929  3873 D WifiService: setWifiEnabled: true pid=5588, uid=10077
,11-23 19:15:04.827   929  3873 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-23 19:15:04.890  4645  4839 W bt_sdp  : SDP - Rcvd conn cnf with error: 0x4  CID 0x40
,11-23 19:15:04.890  4645  4842 E bt_btif_sock_rfcomm: find_rfc_slot_by_id unable to find RFCOMM slot id: 5
,11-23 19:15:05.299  5588  5588 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-23 19:15:06.527   929  2972 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,11-23 19:15:09.186   929  5344 D NetlinkSocketObserver: NeighborEvent{elapsedMs=216690, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,11-23 19:15:09.833  5588  5634 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,11-23 19:15:09.833  5588  5634 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@7123ff6 added. We now have 4 listener(s)
,11-23 19:15:09.833  5588  5634 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-23 19:15:09.848  5588  5634 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-23 19:15:09.849  5588  5634 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@7123ff6 removed from the list
,11-23 19:15:09.849  5588  5634 D io.jxcore.node.ConnectivityMonitor: stop
,11-23 19:15:09.850  5588  5634 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,11-23 19:15:09.851  5588  5634 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@865ff7 added. We now have 4 listener(s)
,11-23 19:15:09.851  5588  5634 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-23 19:15:09.854  5588  5634 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-23 19:15:09.854  5588  5634 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@865ff7 removed from the list
11-23 19:15:09.854  5588  5634 D io.jxcore.node.ConnectivityMonitor: stop
,11-23 19:15:09.857  5588  5634 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-23 19:15:09.857  5588  5634 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@a7e4e64 added. We now have 4 listener(s)
11-23 19:15:09.857  5588  5634 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-23 19:15:09.861   929   940 D WifiService: setWifiEnabled: false pid=5588, uid=10077
,11-23 19:15:09.861   929   940 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-23 19:15:09.864   929  2970 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,11-23 19:15:09.864   929  2970 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
,11-23 19:15:09.865   929  2970 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
11-23 19:15:09.865   929  2970 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-23 19:15:09.868  5588  5634 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-23 19:15:09.868  4645  4717 D BluetoothAdapterState: Current state: ON, message: 23
,11-23 19:15:09.868  4645  4717 D BluetoothAdapterProperties: Setting state to 13
11-23 19:15:09.868  5588  5634 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
11-23 19:15:09.868  4645  4717 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
11-23 19:15:09.868  4645  4717 D BluetoothAdapterProperties: onBluetoothDisable()
11-23 19:15:09.870  4645  4717 I BluetoothAdapterState: Entering PendingCommandState
11-23 19:15:09.871  4645  4645 D BluetoothMapService: onReceive
11-23 19:15:09.871  4645  4645 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
11-23 19:15:09.872  4645  4645 D BluetoothMapService: STATE_TURNING_OFF
11-23 19:15:09.872  4645  4645 D BluetoothMapService: MAP Service closeService in
11-23 19:15:09.872  4645  4645 D BluetoothMapMasInstance0: MAP Service shutdown
11-23 19:15:09.872  4645  4645 D ObexServerSockets0: shutdown(block = true)
11-23 19:15:09.873  4645  4645 D ObexServerSockets0: shutdown called from another thread - interrupt().
11-23 19:15:09.873  4645  4867 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 5
11-23 19:15:09.873  4645  4645 D ObexServerSockets0: shutdown called from another thread - interrupt().
11-23 19:15:09.873  4645  4842 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
11-23 19:15:09.874  4645  4868 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
11-23 19:15:09.878  4645  4645 I BtOppRfcommListener: stopping Accept Thread
11-23 19:15:09.878  4645  5279 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
11-23 19:15:09.878  4645  5279 I BtOppRfcommListener: BluetoothSocket listen thread finished
11-23 19:15:09.879   929  5345 D DhcpClient: Clearing IP address
11-23 19:15:09.879   508   913 D CommandListener: Clearing all IP addresses on wlan0
11-23 19:15:09.881  5588  5634 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-23 19:15:09.881  5588  5634 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-23 19:15:09.881  5588  5634 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-23 19:15:09.881  5588  5634 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-23 19:15:09.881  5588  5634 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-23 19:15:09.881  5588  5634 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-23 19:15:09.881  5588  5634 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-23 19:15:09.881  5588  5634 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-23 19:15:09.881  5588  5634 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-23 19:15:09.881  5588  5634 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,11-23 19:15:09.881  5588  5634 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-23 19:15:09.882  5588  5634 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
11-23 19:15:09.882  5588  5634 D io.jxcore.node.ConnectivityMonitor: start: OK
11-23 19:15:09.885  5588  5588 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-23 19:15:09.886   508   913 D CommandListener: Setting iface cfg
,11-23 19:15:09.889  5588  5588 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-23 19:15:09.893   929   942 I ActivityManager: Start proc 5654:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
,11-23 19:15:09.894  3580  5401 V NativeCrypto: Read error: ssl=0x7f802d1700: I/O error during system call, Connection timed out
11-23 19:15:09.894  4645  4721 D BluetoothAdapterProperties: Scan Mode:20
11-23 19:15:09.895  4645  4717 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
11-23 19:15:09.896   929  2972 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
11-23 19:15:09.896   929  2972 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
11-23 19:15:09.899  3580  5401 V NativeCrypto: SSL shutdown failed: ssl=0x7f802d1700: I/O error during system call, Broken pipe
11-23 19:15:09.899   929  5346 D DhcpClient: Receive thread stopped
11-23 19:15:09.900  5588  5588 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,11-23 19:15:09.900  5588  5588 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-23 19:15:09.900  5588  5588 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-23 19:15:09.900  5588  5588 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-23 19:15:09.900  5588  5588 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-23 19:15:09.900  5588  5588 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-23 19:15:09.900  5588  5588 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-23 19:15:09.900  5588  5588 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-23 19:15:09.900  5588  5588 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-23 19:15:09.900  5588  5588 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
11-23 19:15:09.901  5588  5588 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-23 19:15:09.901  5588  5588 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
11-23 19:15:09.904   929   929 D RttService: SCAN_AVAILABLE : 1
11-23 19:15:09.904   534   534 E Parcel  : Reading a NULL string not supported here.
11-23 19:15:09.905   929  3079 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,11-23 19:15:09.906   929  2972 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
,11-23 19:15:09.907  4645  4645 D HeadsetService: Received stop request...Stopping profile...
11-23 19:15:09.908  3112  3129 D BluetoothHeadset: Proxy object disconnected
11-23 19:15:09.909  3800  3980 D BluetoothHeadset: Proxy object disconnected
11-23 19:15:09.909  4645  4645 D A2dpService: Received stop request...Stopping profile...
11-23 19:15:09.909   929   929 D BluetoothHeadset: Proxy object disconnected
11-23 19:15:09.909   929   929 D BluetoothHeadset: Proxy object disconnected
11-23 19:15:09.909   929   929 D BluetoothHeadset: Proxy object disconnected
11-23 19:15:09.909  4645  4859 D A2dpStateMachine: Exit Disconnected: -1
11-23 19:15:09.910  3769  3887 W QCNEJ   : |CORE| network lost: 100
11-23 19:15:09.910  3769  3887 W QCNEJ   : |CORE| onLost: unbind the process to WIFI
,11-23 19:15:09.913   929   929 D BluetoothA2dp: Proxy object disconnected
,11-23 19:15:09.914   929  2970 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,11-23 19:15:09.914  4645  4645 D HidService: Received stop request...Stopping profile...
11-23 19:15:09.914  4645  4645 D HidService: Stopping Bluetooth HidService
11-23 19:15:09.915  4645  4645 V BluetoothAdapterState: isTurningOff()=true
11-23 19:15:09.915  4645  4645 V BluetoothAdapterState: isTurningOn()=false
11-23 19:15:09.915  4645  4645 V BluetoothAdapterState: isBleTurningOn()=false
11-23 19:15:09.915  4645  4645 V BluetoothAdapterState: isBleTurningOff()=false
,11-23 19:15:09.917  4645  4645 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
11-23 19:15:09.917  4645  4645 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
11-23 19:15:09.917  4645  4839 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-23 19:15:09.917  4645  4839 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-23 19:15:09.917  4645  4839 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-23 19:15:09.917  4645  4645 V BluetoothAdapterState: isTurningOff()=true
11-23 19:15:09.917  4645  4645 V BluetoothAdapterState: isTurningOn()=false
11-23 19:15:09.917  4645  4645 V BluetoothAdapterState: isBleTurningOn()=false
11-23 19:15:09.917  4645  4645 V BluetoothAdapterState: isBleTurningOff()=false
11-23 19:15:09.918  4645  4645 D HealthService: Received stop request...Stopping profile...
11-23 19:15:09.918  4645  4721 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
11-23 19:15:09.918  4645  4721 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
11-23 19:15:09.918  3112  3112 D HeadsetProfile: Bluetooth service disconnected
11-23 19:15:09.921  4645  4839 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-23 19:15:09.921  4645  4839 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-23 19:15:09.921  4645  4721 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
11-23 19:15:09.921  4645  4839 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
11-23 19:15:09.921  4645  4839 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
11-23 19:15:09.922  4645  4839 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
11-23 19:15:09.922  4645  4839 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
11-23 19:15:09.922  4645  4645 V BluetoothAdapterState: isTurningOff()=true
11-23 19:15:09.923  3112  3112 D BluetoothA2dp: Proxy object disconnected
11-23 19:15:09.924  3112  3112 D BluetoothInputDevice: Proxy object disconnected
11-23 19:15:09.924  3112  3112 D HidProfile: Bluetooth service disconnected
11-23 19:15:09.924  4645  4645 V BluetoothAdapterState: isTurningOn()=false
11-23 19:15:09.924  4645  4645 V BluetoothAdapterState: isBleTurningOn()=false
11-23 19:15:09.924  4645  4645 V BluetoothAdapterState: isBleTurningOff()=false
,11-23 19:15:09.925  4645  4645 D PanService: Received stop request...Stopping profile...
11-23 19:15:09.926  4645  4645 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
11-23 19:15:09.926  4645  4645 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
11-23 19:15:09.926   929  2970 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,11-23 19:15:09.926  4645  4721 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
11-23 19:15:09.926  4645  4645 D BluetoothMapService: Received stop request...Stopping profile...
11-23 19:15:09.926  4645  4645 D BluetoothMapService: stop()
11-23 19:15:09.927  3112  3112 D BluetoothPan: BluetoothPAN Proxy object disconnected
11-23 19:15:09.927  3112  3112 D PanProfile: Bluetooth service disconnected
11-23 19:15:09.927  4645  4645 D BluetoothMapAppObserver: deinitObservers()
,11-23 19:15:09.927  4645  4645 D BluetoothMapAppObserver: removeReceiver()
11-23 19:15:09.928  3112  3112 D BluetoothMap: Proxy object disconnected
11-23 19:15:09.928  3112  3112 D MapProfile: Bluetooth service disconnected
11-23 19:15:09.928  4645  4645 D SapService: Received stop request...Stopping profile...
11-23 19:15:09.928  4645  4645 V SapService: stop()
11-23 19:15:09.929  4645  4645 V BluetoothAdapterState: isTurningOff()=true
11-23 19:15:09.930  4645  4645 V BluetoothAdapterState: isTurningOn()=false
11-23 19:15:09.930  4645  4645 V BluetoothAdapterState: isBleTurningOn()=false
11-23 19:15:09.930  4645  4645 V BluetoothAdapterState: isBleTurningOff()=false
11-23 19:15:09.930  4645  4645 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
11-23 19:15:09.930  4645  4721 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
11-23 19:15:09.930  4645  4645 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
11-23 19:15:09.930  4645  4645 V BluetoothAdapterState: isTurningOff()=true
11-23 19:15:09.930  4645  4645 V BluetoothAdapterState: isTurningOn()=false
11-23 19:15:09.930  4645  4645 V BluetoothAdapterState: isBleTurningOn()=false
11-23 19:15:09.930  4645  4645 V BluetoothAdapterState: isBleTurningOff()=false
,11-23 19:15:09.930  4645  4645 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
11-23 19:15:09.931  4645  4645 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
11-23 19:15:09.935  4645  4645 D BluetoothMapService: MAP Service closeService in
11-23 19:15:09.935   508   913 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
11-23 19:15:09.936  4645  4645 V BluetoothAdapterState: isTurningOff()=true
11-23 19:15:09.936  4645  4645 V BluetoothAdapterState: isTurningOn()=false
,11-23 19:15:09.936  4645  4645 V BluetoothAdapterState: isBleTurningOn()=false
11-23 19:15:09.936  4645  4645 V BluetoothAdapterState: isBleTurningOff()=false
11-23 19:15:09.936  4645  4645 D BluetoothMapService: cleanup()
11-23 19:15:09.936  4645  4645 D BluetoothMapService: MAP Service closeService in
11-23 19:15:09.936  4645  4645 V BluetoothAdapterState: isTurningOff()=true
11-23 19:15:09.936  4645  4645 V BluetoothAdapterState: isTurningOn()=false
11-23 19:15:09.936  4645  4645 V BluetoothAdapterState: isBleTurningOn()=false
11-23 19:15:09.936  4645  4645 V BluetoothAdapterState: isBleTurningOff()=false
11-23 19:15:09.937  4645  4717 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
11-23 19:15:09.937  4645  4717 D BluetoothAdapterProperties: Setting state to 15
11-23 19:15:09.937  4645  4717 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
,11-23 19:15:09.937  4645  4717 I BluetoothAdapterState: Entering BleOnState
11-23 19:15:09.938  3112  3129 D BluetoothInputDevice: onBluetoothStateChange: up=false
11-23 19:15:09.938   929   946 D BluetoothHeadset: onBluetoothStateChange: up=false
11-23 19:15:09.938   929   946 D BluetoothHeadset: onBluetoothStateChange: up=false
11-23 19:15:09.938  3112  3126 D BluetoothPbap: onBluetoothStateChange: up=false
,11-23 19:15:09.939  3112  3947 D BluetoothMap: onBluetoothStateChange: up=false
,11-23 19:15:09.939  3112  3129 D BluetoothPan: onBluetoothStateChange on: false
,11-23 19:15:09.941   929   946 D BluetoothHeadset: onBluetoothStateChange: up=false
11-23 19:15:09.941  3800  3830 D BluetoothHeadset: onBluetoothStateChange: up=false
11-23 19:15:09.941   929   946 D BluetoothA2dp: onBluetoothStateChange: up=false
11-23 19:15:09.942  3112  3947 D BluetoothHeadset: onBluetoothStateChange: up=false
11-23 19:15:09.943  3112  3126 D BluetoothA2dp: onBluetoothStateChange: up=false
,11-23 19:15:09.948  4645  4717 D BluetoothAdapterState: Current state: BLE ON, message: 20
11-23 19:15:09.948  4645  4717 D BluetoothAdapterProperties: Setting state to 16
11-23 19:15:09.948  4645  4717 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
11-23 19:15:09.948  4645  4717 D BluetoothAdapterProperties: onBleDisable
11-23 19:15:09.949  4645  4717 I BluetoothAdapterState: Entering PendingCommandState
11-23 19:15:09.949  4645  4718 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
11-23 19:15:09.950  4645  4721 D BluetoothAdapterProperties: Scan Mode:20
,11-23 19:15:09.950  4645  4839 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
,11-23 19:15:09.950  4645  4839 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-23 19:15:09.951  5588  5588 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-23 19:15:09.951  5588  5588 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-23 19:15:09.951  5588  5588 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-23 19:15:09.951  5588  5588 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-23 19:15:09.951  5588  5588 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-23 19:15:09.951  5588  5588 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-23 19:15:09.951  5588  5588 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-23 19:15:09.951  5588  5588 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-23 19:15:09.951  5588  5588 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-23 19:15:09.951  5588  5588 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,11-23 19:15:09.953  5588  5588 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-23 19:15:09.961  5654  5654 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm64
,11-23 19:15:09.962   508   913 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-23 19:15:09.962   508   913 D CommandListener: Clearing all IP addresses on wlan0
,11-23 19:15:09.963   508   913 D TetherController: Setting IP forward enable = 0
,11-23 19:15:09.964   929  2972 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
11-23 19:15:09.964   929  2972 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
11-23 19:15:09.965   929   946 D Tethering: MasterInitialState.processMessage what=3
11-23 19:15:09.967   929  2970 D DhcpClient: doQuit
11-23 19:15:09.967   929  2970 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
11-23 19:15:09.967   929  5345 D DhcpClient: onQuitting
11-23 19:15:09.969  3457  3457 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
11-23 19:15:09.969  5588  5588 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-23 19:15:09.970  3954  3954 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
,11-23 19:15:09.973  5588  5588 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-23 19:15:09.973  5588  5588 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-23 19:15:09.973  5588  5588 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-23 19:15:09.973  5588  5588 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-23 19:15:09.973  5588  5588 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-23 19:15:09.973  5588  5588 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-23 19:15:09.973  5588  5588 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-23 19:15:09.973  5588  5588 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-23 19:15:09.973  5588  5588 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-23 19:15:09.973  5588  5588 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-23 19:15:09.974  5588  5588 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-23 19:15:09.975  5588  5588 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
11-23 19:15:09.975  5235  5235 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@94d81db and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
11-23 19:15:09.981  5021  5045 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
,11-23 19:15:09.981  5021  5045 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
11-23 19:15:09.981  5021  5045 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,0,0,0
11-23 19:15:09.981  5021  5045 E SarControlService: no key has been found,reset the power
11-23 19:15:09.982  5021  5058 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
11-23 19:15:09.982  5021  5058 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
11-23 19:15:09.982  5021  5058 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
11-23 19:15:09.982  5046  5046 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
,11-23 19:15:09.982  5046  5046 D QcrilMsgTunnelSocket: [1002] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
11-23 19:15:09.983  5021  5058 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
11-23 19:15:09.983  5021  5058 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
11-23 19:15:09.983  5021  5058 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
11-23 19:15:09.984  5046  5046 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
11-23 19:15:09.984  5046  5046 D QcrilMsgTunnelSocket: [1003] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
,11-23 19:15:09.987  5046  5060 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@6ad9059 HexData = [00000000ea03000000000000ffffffff]
,11-23 19:15:09.987  5046  5060 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-23 19:15:09.987  5046  5060 D QcrilMsgTunnelSocket: [1002] < OEM_HOOK_RAW [null]
11-23 19:15:09.987  5046  5046 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
11-23 19:15:09.987  5021  5031 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
11-23 19:15:09.993  5046  5060 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@6ad9059 HexData = [00000000eb03000000000000ffffffff]
11-23 19:15:09.993  5046  5060 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-23 19:15:09.993  5046  5060 D QcrilMsgTunnelSocket: [1003] < OEM_HOOK_RAW [null]
,11-23 19:15:09.994  5046  5046 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
11-23 19:15:09.994  5021  5032 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
11-23 19:15:09.997  3457  3457 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
,11-23 19:15:10.001  3457  3457 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,11-23 19:15:10.010  5654  5654 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,11-23 19:15:10.016   508   913 E Netd    : netlink response contains error (No such file or directory)
11-23 19:15:10.016  3580  3580 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
11-23 19:15:10.017   929   946 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@aaffb82:true
11-23 19:15:10.017   508   913 D TetherController: Setting IP forward enable = 0
,11-23 19:15:10.045  3457  3457 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,11-23 19:15:10.056  3457  3457 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,11-23 19:15:10.063  5654  5654 D LocalBluetoothProfileManager: Adding local MAP profile
,11-23 19:15:10.071  5654  5654 D BluetoothMap: Create BluetoothMap proxy object
,11-23 19:15:10.085  5654  5654 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,11-23 19:15:10.098  5654  5654 D DockEventReceiver: finishStartingService: stopping service
,11-23 19:15:10.103  5654  5654 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,11-23 19:15:10.107  5654  5654 D DockEventReceiver: finishStartingService: stopping service
,11-23 19:15:10.109   929  3596 I ActivityManager: Killing 5372:com.android.sdm.plugins.sprintdm/1001 (adj 15): empty #17
,11-23 19:15:10.125  3580  3580 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,11-23 19:15:10.134  3743  3743 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,11-23 19:15:10.137  3743  3743 D SystemUpdateService: onCreate
,11-23 19:15:10.140  3743  3743 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,11-23 19:15:10.147  3743  5691 I SystemUpdateService: active receiver: enabled
,11-23 19:15:10.149  3743  3743 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,11-23 19:15:10.156  4645  4721 I bt_hci  : shut_down
,11-23 19:15:10.157  3743  5369 I iu.UploadsManager: num queued entries: 0
,11-23 19:15:10.158  4996  4996 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
11-23 19:15:10.158   929  2970 D wifi    : In wifi stop Hal
,11-23 19:15:10.158   929  2970 D wifi    : halHandle = 0x7f7e088180, mVM = 0x7f9a68d140, mCls = 0x100a02
11-23 19:15:10.159   929  3455 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
11-23 19:15:10.159   929  3455 D WifiHAL : Got a signal to exit!!!
11-23 19:15:10.159   929  3455 I WifiHAL : Exit wifi_event_loop
11-23 19:15:10.161  3743  3743 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
11-23 19:15:10.161   929  2970 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 0
,11-23 19:15:10.161   929  2970 E WifiHAL : Event processing terminated
11-23 19:15:10.161  5588  5588 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-23 19:15:10.161   929  2970 D wifi    : In wifi cleaned up handler
11-23 19:15:10.161  4038  4211 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
11-23 19:15:10.161   929  2970 I WifiHAL : Internal cleanup completed
11-23 19:15:10.162  3743  3743 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
11-23 19:15:10.163  4645  4726 I bt_vendor: low_power_mode_cb
,11-23 19:15:10.164  3743  5691 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,11-23 19:15:10.165  3743  5369 I iu.UploadsManager: num updated entries: 0
,11-23 19:15:10.166  3743  5369 I iu.SyncManager: NEXT; no task
,11-23 19:15:10.168  3743  5691 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,11-23 19:15:10.168  3743  5691 I SystemUpdateService: now status is 0 (complete)
11-23 19:15:10.168  3743  5691 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
11-23 19:15:10.168  3743  5691 I SystemUpdateService: file has been verified
11-23 19:15:10.168  3743  5691 I SystemUpdateService: OTA package size = 21989297
,11-23 19:15:10.174   929  3158 I ActivityManager: Start proc 5693:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,11-23 19:15:10.175  3743  5691 I SystemUpdateService: showing system update notification
,11-23 19:15:10.176  4645  4726 D bt_hwcfg: hw_epilog_process
,11-23 19:15:10.179  4645  4726 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,11-23 19:15:10.179  4645  4726 I bt_vendor: epilog_cb
11-23 19:15:10.179  4645  4726 I bt_hci  : epilog_finished_callback
,11-23 19:15:10.181  4645  4721 I bt_hci_h4: hal_close
,11-23 19:15:10.181   929  3455 D wifi    : set interface wlan0 flags (DOWN)
,11-23 19:15:10.181  4645  4721 I bt_userial_vendor: device fd = 54 close
11-23 19:15:10.181   929  2970 D WifiNative-HAL: HAL event thread stopped successfully
,11-23 19:15:10.191   929   929 V NotificationService: pkg=com.google.android.gms canInterrupt=false intercept=true
,11-23 19:15:10.192  3743  3743 D SystemUpdateService: onDestroy
,11-23 19:15:10.213  5693  5693 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm64
,11-23 19:15:10.216  5693  5693 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,11-23 19:15:10.222  5693  5693 D SprintDMHelper: simOperator: 
11-23 19:15:10.223  5693  5693 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,11-23 19:15:10.236  4996  5705 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,11-23 19:15:10.248   929  3158 I ActivityManager: Start proc 5706:com.google.android.apps.gcs/u0a11 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,11-23 19:15:10.250   929   940 I ActivityManager: Killing 5235:com.google.android.music:main/u0a59 (adj 15): empty #17
,11-23 19:15:10.285  5706  5706 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm64
,11-23 19:15:10.290  4645  4718 D bt_stack_manager: event_shut_down_stack finished.
,11-23 19:15:10.290  4645  4717 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,11-23 19:15:10.292   929  3158 I ActivityManager: Killing 3890:com.android.providers.calendar/u0a1 (adj 15): empty #17
,11-23 19:15:10.304  4645  4717 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,11-23 19:15:10.305  4645  4645 D BtGatt.DebugUtils: handleDebugAction() action=null
,11-23 19:15:10.305  4645  4645 D BtGatt.GattService: Received stop request...Stopping profile...
11-23 19:15:10.305  4645  4645 D BtGatt.GattService: stop()
11-23 19:15:10.305  4645  4645 D BtGatt.AdvertiseManager: advertise clients cleared
,11-23 19:15:10.308  4645  4645 V BluetoothAdapterState: isTurningOff()=false
11-23 19:15:10.308  4645  4645 V BluetoothAdapterState: isTurningOn()=false
11-23 19:15:10.308  4645  4645 V BluetoothAdapterState: isBleTurningOn()=false
11-23 19:15:10.308  4645  4645 V BluetoothAdapterState: isBleTurningOff()=true
11-23 19:15:10.308  4645  4717 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
11-23 19:15:10.308  4645  4717 D BluetoothAdapterProperties: Setting state to 10
11-23 19:15:10.308  4645  4717 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
,11-23 19:15:10.309  4645  4717 I BluetoothAdapterState: Entering OffState
11-23 19:15:10.309   929   946 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,11-23 19:15:10.317  4645  4645 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,11-23 19:15:10.317  4645  4645 W BluetoothSdpJni: Cleaning up Bluetooth Health object
11-23 19:15:10.317  4645  4645 I BluetoothServiceJni: cleanupNative: return from cleanup
11-23 19:15:10.318  4645  4718 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,11-23 19:15:10.322  4645  4645 I art     : System.exit called, status: 0
,11-23 19:15:10.322  4645  4645 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,11-23 19:15:10.345   929  3158 I ActivityManager: Process com.android.bluetooth (pid 4645) has died
,11-23 19:15:10.384   929   946 D Tethering: InitialState.processMessage what=4
,11-23 19:15:10.387   929   946 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,11-23 19:15:11.791   536   536 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
11-23 19:15:11.792   536   536 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,11-23 19:15:14.884   929  3841 D WifiService: setWifiEnabled: true pid=5588, uid=10077
,11-23 19:15:14.884   929  3841 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
11-23 19:15:14.895   508   913 D SoftapController: Softap fwReload - Ok
11-23 19:15:14.901   508   913 D CommandListener: Setting iface cfg
11-23 19:15:14.902   508   913 D CommandListener: Trying to bring down wlan0
11-23 19:15:14.904   508   913 D CommandListener: Clearing all IP addresses on wlan0
11-23 19:15:14.909   929  2970 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,11-23 19:15:15.552   929  2970 D wifi    : set interface wlan0 flags (UP)
,11-23 19:15:15.556   929  2970 I WifiHAL : Initializing wifi
11-23 19:15:15.556   929  2970 I WifiHAL : Creating socket
11-23 19:15:15.561   929  2970 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
,11-23 19:15:15.561   929  2970 D wifi    : Did set static halHandle = 0x7f7e088180
11-23 19:15:15.562   929  2970 D wifi    : halHandle = 0x7f7e088180, mVM = 0x7f9a68d140, mCls = 0x196a
11-23 19:15:15.562   929   946 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
11-23 19:15:15.562   929  2970 D wifi    : array field set
,11-23 19:15:15.563   929  2970 I WifiNative-HAL: interface[0] = wlan0
11-23 19:15:15.567   929  5722 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=547575333248
,11-23 19:15:15.567   929  5722 D wifi    : waitForHalEvents called, vm = 0x7f9a68d140, obj = 0x196a, env = 0x7f7e0d8b40
,11-23 19:15:15.650  5723  5723 I wpa_supplicant: Successfully initialized wpa_supplicant
,11-23 19:15:15.668   929  2970 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,11-23 19:15:15.676  5588  5588 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-23 19:15:15.733  5723  5723 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,11-23 19:15:15.817  5723  5723 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,11-23 19:15:15.817  5723  5723 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,11-23 19:15:15.864   929  2970 D WifiConfigStore: Loading config and enabling all networks 
,11-23 19:15:15.866  5588  5588 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-23 19:15:15.866  5588  5588 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-23 19:15:15.866  5588  5588 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-23 19:15:15.866  5588  5588 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-23 19:15:15.866  5588  5588 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-23 19:15:15.866  5588  5588 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-23 19:15:15.866  5588  5588 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-23 19:15:15.866  5588  5588 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-23 19:15:15.866  5588  5588 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-23 19:15:15.866  5588  5588 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-23 19:15:15.866  5588  5588 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-23 19:15:15.867  5588  5588 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
,11-23 19:15:15.895   929  2970 D WifiConfigStore: loaded 0 passpoint configs
,11-23 19:15:15.896   929  2970 W WifiConfigStore: Upgrading network 4 to android.uid.system:1000
11-23 19:15:15.897   929  2970 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
11-23 19:15:15.898   929  2970 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
11-23 19:15:15.898   929  2970 W WifiConfigStore: Upgrading network 3 to android.uid.system:1000
11-23 19:15:15.899   929  2970 W WifiConfigStore: Upgrading network 2 to android.uid.system:1000
11-23 19:15:15.900   929  2970 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
11-23 19:15:15.900   929  2970 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 5
11-23 19:15:15.900   929  2970 E WifiConfigStore: found sortedWifiConfigurations : "AndroidAP"WPA_PSK
,11-23 19:15:15.900   929  2970 E WifiConfigStore: found sortedWifiConfigurations : "AndroidHotspot2346"WPA_PSK
11-23 19:15:15.900   929  2970 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
11-23 19:15:15.900   929  2970 E WifiConfigStore: found sortedWifiConfigurations : "Thali_internal"WPA_PSK
11-23 19:15:15.900   929  2970 E WifiConfigStore: found sortedWifiConfigurations : "MC"WPA_PSK
,11-23 19:15:15.905   929  2970 D WifiNative-HAL: Setting external_sim to 1
11-23 19:15:15.906  4996  4996 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,11-23 19:15:15.906   929  2970 D wifi    : setting dfs flag to true, 0x7f7ef55f60
,11-23 19:15:15.907   929  2970 D WifiStateMachine: Setting OUI to DA-A1-19
11-23 19:15:15.907   929  2970 D wifi    : setting scan oui 0x7f7ef55f60
11-23 19:15:15.907   929  2970 D WifiHAL : Sending mac address OUI
,11-23 19:15:15.911   929  2970 E native  : do suspend false
,11-23 19:15:15.924   929  2970 D wifi    : android_net_wifi_setLinkLayerStats: 1
,11-23 19:15:15.924   929   929 D RttService: SCAN_AVAILABLE : 3
11-23 19:15:15.924   508   913 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
11-23 19:15:15.924   929  3079 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
11-23 19:15:15.925   508   913 D CommandListener: Setting iface cfg
,11-23 19:15:15.930   929  2969 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '125 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 125 Failed to set address (No such device)'
,11-23 19:15:15.930   929  2969 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,11-23 19:15:15.941   929  2969 D WifiNative-HAL: p2pGetDeviceAddress
,11-23 19:15:15.946   929  2969 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:70
,11-23 19:15:15.947   929   944 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=223451 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=17 mControllerEnergyUsed=64 }
,11-23 19:15:18.995  5723  5723 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-23 19:15:19.003  5723  5723 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-23 19:15:19.009  5723  5723 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-23 19:15:19.058   929  2970 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,11-23 19:15:19.060   929  2970 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3
,11-23 19:15:19.060   929  2970 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-23 19:15:19.071   929  2970 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=0
,11-23 19:15:19.107   929  2970 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=0
,11-23 19:15:19.114  5723  5723 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,11-23 19:15:19.534  5723  5723 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,11-23 19:15:19.570  5723  5723 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,11-23 19:15:19.571  5723  5723 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,11-23 19:15:19.579   929  2970 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,11-23 19:15:19.579   929  2970 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
11-23 19:15:19.579   929  2972 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,11-23 19:15:19.597   929  2970 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-23 19:15:19.609   508   913 D CommandListener: Setting iface cfg
,11-23 19:15:19.615   929  2970 D WifiStateMachine: Start Dhcp Watchdog 2
,11-23 19:15:19.620   929  5729 D DhcpClient: Receive thread started
,11-23 19:15:19.625   929  2972 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-23 19:15:19.625   929  2970 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
11-23 19:15:19.625   929  2972 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
,11-23 19:15:19.706   929  2970 E native  : do suspend false
,11-23 19:15:19.722   929  5728 D DhcpClient: Broadcasting DHCPDISCOVER
,11-23 19:15:19.734   929  5729 D DhcpClient: Received packet: 60:83:34:25:d7:70 OFFER, ip /192.168.1.109, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172614, domain null
,11-23 19:15:19.735   929  5728 D DhcpClient: Got pending lease: IP address 192.168.1.109/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172614 seconds
,11-23 19:15:19.737   929  5728 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.109 serverid=192.168.1.1
,11-23 19:15:19.757   929  5729 D DhcpClient: Received packet: 60:83:34:25:d7:70 ACK: your new IP /192.168.1.109, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,11-23 19:15:19.757   929  5728 D DhcpClient: Confirmed lease: IP address 192.168.1.109/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,11-23 19:15:19.760   508   913 D CommandListener: Setting iface cfg
,11-23 19:15:19.765   929  2970 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,11-23 19:15:19.772   929  5728 D DhcpClient: Scheduling renewal in 86399s
,11-23 19:15:19.780   929  2970 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,11-23 19:15:19.781   929  2970 D WifiConfigStore: No blacklist allowed without epno enabled
11-23 19:15:19.782   929  2972 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
11-23 19:15:19.785   929  2972 D ConnectivityService: Adding iface wlan0 to network 101
,11-23 19:15:19.793   929  2970 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,11-23 19:15:19.837   929  2972 E ConnectivityService: Unexpected mtu value: 0, wlan0
,11-23 19:15:19.837   929  2972 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
11-23 19:15:19.839   929  2972 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
11-23 19:15:19.840   929  2972 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,11-23 19:15:19.842   929  2972 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,11-23 19:15:19.849   929  2972 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-23 19:15:19.854   929  2972 D ConnectivityService: scheduleUnvalidatedPrompt 101
,11-23 19:15:19.854   929  2972 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
11-23 19:15:19.854   929  2972 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
11-23 19:15:19.854   929  2972 D ConnectivityService:    accepting network in place of null
11-23 19:15:19.854   929  2970 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
11-23 19:15:19.854   929  2970 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,11-23 19:15:19.855   929  2972 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d770/64,192.168.1.109/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -50]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,11-23 19:15:19.862   929  5727 D NetlinkSocketObserver: NeighborEvent{elapsedMs=227366, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,11-23 19:15:19.878   508   913 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-23 19:15:19.892   929   940 D WifiService: setWifiEnabled: false pid=5588, uid=10077
,11-23 19:15:19.892   929   940 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-23 19:15:19.893   929  2970 D WifiStateMachine: WifiStateMachine: Leaving Connected state
11-23 19:15:19.893   929  2970 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
11-23 19:15:19.893   929  2970 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
11-23 19:15:19.894   929  2970 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-23 19:15:19.900   929  5728 D DhcpClient: Clearing IP address
,11-23 19:15:19.901   508   913 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-23 19:15:19.902   508   913 D CommandListener: Clearing all IP addresses on wlan0
,11-23 19:15:19.903   508   913 D CommandListener: Setting iface cfg
,11-23 19:15:19.906   929  2972 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
11-23 19:15:19.906   929  2972 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
11-23 19:15:19.906  3769  3887 W QCNEJ   : |CORE| network available: 101
,11-23 19:15:19.907   929  2972 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
11-23 19:15:19.908   929  2972 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
11-23 19:15:19.908   929  2972 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 3
11-23 19:15:19.909   929   946 D Tethering: MasterInitialState.processMessage what=3
11-23 19:15:19.911   534   534 E Parcel  : Reading a NULL string not supported here.
,11-23 19:15:19.912  3769  3887 W QCNEJ   : |CORE| onAvailable: bind the process to WIFI
,11-23 19:15:19.913  3769  3887 W QCNEJ   : |CORE| newLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d770/64,192.168.1.109/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}
,11-23 19:15:19.914  3769  3887 W QCNEJ   : |CORE| curLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d770/64,192.168.1.109/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,11-23 19:15:19.914  5588  5588 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,11-23 19:15:19.914  5588  5588 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-23 19:15:19.914  5588  5588 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-23 19:15:19.914  5588  5588 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-23 19:15:19.914  5588  5588 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-23 19:15:19.914  5588  5588 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-23 19:15:19.914  5588  5588 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-23 19:15:19.914  5588  5588 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-23 19:15:19.914  5588  5588 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-23 19:15:19.914  5588  5588 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
11-23 19:15:19.916   929   929 D RttService: SCAN_AVAILABLE : 1
11-23 19:15:19.916   929  3079 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
11-23 19:15:19.919   929  2972 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
11-23 19:15:19.919   929  5729 D DhcpClient: Receive thread stopped
11-23 19:15:19.920  3769  3887 W QCNEJ   : |CORE| network lost: 101
11-23 19:15:19.921  3743  3743 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,11-23 19:15:19.921  3769  3887 W QCNEJ   : |CORE| onLost: unbind the process to WIFI
11-23 19:15:19.923   929  2970 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
11-23 19:15:19.924  3743  3743 D SystemUpdateService: onCreate
11-23 19:15:19.926   929  2970 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,11-23 19:15:19.937  3743  3743 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,11-23 19:15:19.944  3743  5740 I SystemUpdateService: active receiver: enabled
,11-23 19:15:19.946   508   913 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-23 19:15:19.950  3743  3743 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
11-23 19:15:19.952  3743  3743 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,11-23 19:15:19.953  5693  5693 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,11-23 19:15:19.958  5693  5693 D SprintDMHelper: simOperator: 
11-23 19:15:19.958  5693  5693 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,11-23 19:15:19.965  3743  5740 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,11-23 19:15:19.967   508   913 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-23 19:15:19.967   508   913 D CommandListener: Clearing all IP addresses on wlan0
,11-23 19:15:19.968   929  2972 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,11-23 19:15:19.968   929  2972 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
11-23 19:15:19.972   929   946 D Tethering: MasterInitialState.processMessage what=3
11-23 19:15:19.973  5588  5588 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-23 19:15:19.973  5588  5588 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-23 19:15:19.973  5588  5588 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-23 19:15:19.973  5588  5588 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-23 19:15:19.973  5588  5588 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-23 19:15:19.973  5588  5588 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-23 19:15:19.973  5588  5588 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-23 19:15:19.973  5588  5588 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-23 19:15:19.973  5588  5588 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-23 19:15:19.973  5588  5588 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-23 19:15:19.973   929  2970 D DhcpClient: doQuit
11-23 19:15:19.973   929  2970 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
11-23 19:15:19.973   929  5728 D DhcpClient: onQuitting
11-23 19:15:19.974  5723  5723 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
11-23 19:15:19.976  3743  5740 I SystemUpdateService: network: null; metered: false; mobile allowed: true
11-23 19:15:19.976  3743  5740 I SystemUpdateService: now status is 0 (complete)
,11-23 19:15:19.976  3743  5740 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
11-23 19:15:19.976  3743  5740 I SystemUpdateService: file has been verified
11-23 19:15:19.977  3743  5740 I SystemUpdateService: OTA package size = 21989297
11-23 19:15:19.978  5588  5588 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,11-23 19:15:19.978  5588  5588 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-23 19:15:19.978  5588  5588 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-23 19:15:19.978  5588  5588 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-23 19:15:19.978  5588  5588 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-23 19:15:19.978  5588  5588 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-23 19:15:19.978  5588  5588 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-23 19:15:19.978  5588  5588 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-23 19:15:19.978  5588  5588 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-23 19:15:19.978  5588  5588 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-23 19:15:19.978  5588  5588 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-23 19:15:19.978  5588  5588 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
,11-23 19:15:19.983  3743  3743 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,11-23 19:15:19.984  3743  3743 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,11-23 19:15:19.996  3743  5740 I SystemUpdateService: showing system update notification
,11-23 19:15:20.000  5723  5723 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
,11-23 19:15:20.003  5723  5723 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,11-23 19:15:20.007  3743  3743 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
11-23 19:15:20.008  3743  3743 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,11-23 19:15:20.010  5693  5693 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,11-23 19:15:20.013  5693  5693 D SprintDMHelper: simOperator: 
11-23 19:15:20.013  5693  5693 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,11-23 19:15:20.017   508   913 E Netd    : netlink response contains error (No such file or directory)
,11-23 19:15:20.018   929  2972 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,11-23 19:15:20.031   929   929 V NotificationService: pkg=com.google.android.gms canInterrupt=false intercept=true
,11-23 19:15:20.033  5723  5723 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,11-23 19:15:20.042  3743  5752 I SystemUpdateService: active receiver: enabled
,11-23 19:15:20.045  3743  5752 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,11-23 19:15:20.047  3743  5752 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,11-23 19:15:20.047  3743  5752 I SystemUpdateService: now status is 0 (complete)
11-23 19:15:20.047  3743  5752 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
11-23 19:15:20.047  3743  5752 I SystemUpdateService: file has been verified
11-23 19:15:20.047  3743  5752 I SystemUpdateService: OTA package size = 21989297
,11-23 19:15:20.051  5723  5723 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,11-23 19:15:20.053  3743  5752 I SystemUpdateService: showing system update notification
,11-23 19:15:20.063   929   929 V NotificationService: pkg=com.google.android.gms canInterrupt=false intercept=true
,11-23 19:15:20.064  3743  3743 D SystemUpdateService: onDestroy
,11-23 19:15:20.155   929  2970 D wifi    : In wifi stop Hal
,11-23 19:15:20.155   929  2970 D wifi    : halHandle = 0x7f7e088180, mVM = 0x7f9a68d140, mCls = 0x196a
,11-23 19:15:20.155   929  5722 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
,11-23 19:15:20.155   929  5722 D WifiHAL : Got a signal to exit!!!
11-23 19:15:20.155   929  5722 I WifiHAL : Exit wifi_event_loop
,11-23 19:15:20.156   929  2970 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 11
,11-23 19:15:20.156   929  2970 E WifiHAL : Event processing terminated
11-23 19:15:20.156   929  2970 D wifi    : In wifi cleaned up handler
,11-23 19:15:20.156   929  2970 I WifiHAL : Internal cleanup completed
11-23 19:15:20.158  4038  4211 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
11-23 19:15:20.160  5588  5588 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-23 19:15:20.160  4996  4996 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,11-23 19:15:20.182   929  5722 D wifi    : set interface wlan0 flags (DOWN)
,11-23 19:15:20.182   929  2970 D WifiNative-HAL: HAL event thread stopped successfully
,11-23 19:15:20.388   929   946 D Tethering: InitialState.processMessage what=4
,11-23 19:15:20.395   929   946 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,11-23 19:15:20.908   929  2972 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,11-23 19:15:21.793   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 19:15:22.794   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 19:15:23.795   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 19:15:24.796   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 19:15:24.904   929  5726 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on <unknown ssid>, connectivitycheck.gstatic.com=2a00:1450:4001:802::200e
,11-23 19:15:24.910   929  5726 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Probably not a portal: exception java.net.SocketException: Binding socket to network 101 failed: ENONET (Machine is not on the network)
,11-23 19:15:24.912   929  2972 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,11-23 19:15:24.930   929   946 I ActivityManager: Start proc 5754:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,11-23 19:15:25.015  5754  5754 D AdapterServiceConfig: Adding HeadsetService
,11-23 19:15:25.015  5754  5754 D AdapterServiceConfig: Adding A2dpService
11-23 19:15:25.015  5754  5754 D AdapterServiceConfig: Adding HidService
11-23 19:15:25.015  5754  5754 D AdapterServiceConfig: Adding HealthService
,11-23 19:15:25.016  5754  5754 D AdapterServiceConfig: Adding PanService
11-23 19:15:25.016  5754  5754 D AdapterServiceConfig: Adding GattService
11-23 19:15:25.016  5754  5754 D AdapterServiceConfig: Adding BluetoothMapService
11-23 19:15:25.016  5754  5754 D AdapterServiceConfig: Adding SapService
,11-23 19:15:25.026   929   946 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@40404ec:true
,11-23 19:15:25.027  5754  5754 D BluetoothAdapterState: make() - Creating AdapterState
,11-23 19:15:25.029  5754  5754 I bt_bluedroid: init
,11-23 19:15:25.029  5754  5766 I BluetoothAdapterState: Entering OffState
,11-23 19:15:25.031  5754  5767 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,11-23 19:15:25.032  5754  5767 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
11-23 19:15:25.032  5754  5767 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
11-23 19:15:25.032  5754  5767 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
11-23 19:15:25.032  5754  5754 I bt_bluedroid: get_profile_interface socket
,11-23 19:15:25.034  5754  5754 I bt_bluedroid: get_profile_interface sdp
11-23 19:15:25.034  5754  5770 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:D4
,11-23 19:15:25.036  5754  5770 D BluetoothAdapterProperties: Name is: Nexus 6P
,11-23 19:15:25.040  5754  5765 I bt_bluedroid: config_hci_snoop_log
,11-23 19:15:25.041   929   946 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,11-23 19:15:25.045  5754  5766 D BluetoothAdapterState: Current state: OFF, message: 0
,11-23 19:15:25.045  5754  5766 D BluetoothAdapterProperties: Setting state to 14
11-23 19:15:25.045  5754  5766 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,11-23 19:15:25.047  5754  5766 D BluetoothBondStateMachine: make
,11-23 19:15:25.048  5754  5771 I BluetoothBondStateMachine: StableState(): Entering Off State
,11-23 19:15:25.051  5754  5766 I BluetoothAdapterState: Entering PendingCommandState
,11-23 19:15:25.052  5754  5754 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,11-23 19:15:25.054  5754  5754 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f8a38f6
11-23 19:15:25.055  5754  5754 D BtGatt.DebugUtils: handleDebugAction() action=null
,11-23 19:15:25.056  5754  5754 D BtGatt.GattService: Received start request. Starting profile...
,11-23 19:15:25.056  5754  5754 D BtGatt.GattService: start()
11-23 19:15:25.056  5754  5754 I bt_bluedroid: get_profile_interface gatt
,11-23 19:15:25.058  5754  5754 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f8a38f6
11-23 19:15:25.058  5754  5754 D BtGatt.AdvertiseManager: advertise manager created
,11-23 19:15:25.063  5754  5754 V BluetoothAdapterState: isTurningOff()=false
11-23 19:15:25.063  5754  5754 V BluetoothAdapterState: isTurningOn()=false
11-23 19:15:25.063  5754  5754 V BluetoothAdapterState: isBleTurningOn()=true
11-23 19:15:25.063  5754  5754 V BluetoothAdapterState: isBleTurningOff()=false
11-23 19:15:25.064  5754  5766 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,11-23 19:15:25.065  5754  5766 I bt_bluedroid: bt_bluedroid
,11-23 19:15:25.065  5754  5767 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,11-23 19:15:25.066  5754  5767 I bt_hci  : start_up
,11-23 19:15:25.071  5754  5767 I bt_vendor: alloc value 0xf3f63871
,11-23 19:15:25.071  5754  5767 I bt_vendor: init
11-23 19:15:25.071  5754  5767 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
11-23 19:15:25.071  5754  5767 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,11-23 19:15:25.182  5754  5767 D bt_hci  : start_up starting async portion
11-23 19:15:25.183  5754  5774 I bt_hci  : event_finish_startup
,11-23 19:15:25.183  5754  5774 I bt_hci_h4: hal_open
,11-23 19:15:25.183  5754  5774 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,11-23 19:15:25.186  5754  5774 I bt_userial_vendor: device fd = 54 open
11-23 19:15:25.180  5775  5775 W irq/448-msm_hs_: type=1400 audit(0.0:117): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-23 19:15:25.200  5754  5774 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,11-23 19:15:25.203  5754  5774 D bt_hwcfg: Chipset BCM4358A3
,11-23 19:15:25.203  5754  5774 D bt_hwcfg: Target name = [BCM4358A3]
11-23 19:15:25.203  5754  5774 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,11-23 19:15:25.592  5754  5774 I bt_hwcfg: bt vendor lib: set UART baud 115200
,11-23 19:15:25.593  5754  5774 D bt_hwcfg: Settlement delay -- 100 ms
11-23 19:15:25.593  5754  5774 I bt_hwcfg: Setting fw settlement delay to 100 
,11-23 19:15:25.726  5754  5774 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,11-23 19:15:25.727  5754  5774 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:D4
11-23 19:15:25.728  5754  5774 I bt_hwcfg: vendor lib fwcfg completed
11-23 19:15:25.728  5754  5774 I bt_vendor: firmware callback
,11-23 19:15:25.728  5754  5774 I bt_hci  : firmware_config_callback
,11-23 19:15:25.738  5754  5777 I bt_btu  : btu_task pending for preload complete event
,11-23 19:15:25.738  5754  5777 I bt_btu_task: Bluetooth chip preload is complete
11-23 19:15:25.738  5754  5777 I bt_btu  : btu_task received preload complete event
,11-23 19:15:25.745  5754  5777 I         : BTE_InitTraceLevels -- TRC_HCI
,11-23 19:15:25.745  5754  5777 I         : BTE_InitTraceLevels -- TRC_L2CAP
11-23 19:15:25.745  5754  5777 I         : BTE_InitTraceLevels -- TRC_RFCOMM
11-23 19:15:25.745  5754  5777 I         : BTE_InitTraceLevels -- TRC_AVDT
11-23 19:15:25.746  5754  5777 I         : BTE_InitTraceLevels -- TRC_AVRC
11-23 19:15:25.746  5754  5777 I         : BTE_InitTraceLevels -- TRC_A2D
11-23 19:15:25.746  5754  5777 I         : BTE_InitTraceLevels -- TRC_BNEP
11-23 19:15:25.746  5754  5777 I         : BTE_InitTraceLevels -- TRC_BTM
11-23 19:15:25.746  5754  5777 I         : BTE_InitTraceLevels -- TRC_GAP
11-23 19:15:25.746  5754  5777 I         : BTE_InitTraceLevels -- TRC_PAN
11-23 19:15:25.746  5754  5777 I         : BTE_InitTraceLevels -- TRC_SDP
11-23 19:15:25.746  5754  5777 I         : BTE_InitTraceLevels -- TRC_GATT
11-23 19:15:25.746  5754  5777 I         : BTE_InitTraceLevels -- TRC_SMP
11-23 19:15:25.746  5754  5777 I         : BTE_InitTraceLevels -- TRC_BTAPP
11-23 19:15:25.746  5754  5777 I         : BTE_InitTraceLevels -- TRC_BTIF
,11-23 19:15:25.797   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 19:15:25.828  5754  5777 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf3ee1549
,11-23 19:15:25.829  5754  5777 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf3ee1549 
,11-23 19:15:25.852  5754  5770 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,11-23 19:15:25.854  5754  5770 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
11-23 19:15:25.854  5754  5770 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:D4
,11-23 19:15:25.858  5754  5770 D BluetoothAdapterProperties: Name is: Nexus 6P
,11-23 19:15:25.861  5754  5770 D BluetoothAdapterProperties: Scan Mode:20
11-23 19:15:25.861  5754  5770 D BluetoothAdapterProperties: Discoverable Timeout:120
11-23 19:15:25.862  5754  5770 D bt_hci  : do_postload posting postload work item
11-23 19:15:25.862  5754  5774 I bt_hci  : event_postload
11-23 19:15:25.862  5754  5774 I bt_vendor: sco_config_cb
11-23 19:15:25.862  5754  5774 I bt_hci  : sco_config_callback postload finished.
,11-23 19:15:25.866  5754  5770 D bt_bte_conf: Device ID record 1 : primary
,11-23 19:15:25.866  5754  5770 D bt_bte_conf:   vendorId            = 000f
11-23 19:15:25.866  5754  5770 D bt_bte_conf:   vendorIdSource      = 0001
11-23 19:15:25.866  5754  5770 D bt_bte_conf:   product             = 1200
,11-23 19:15:25.866  5754  5770 D bt_bte_conf:   version             = 1436
11-23 19:15:25.866  5754  5770 D bt_bte_conf:   clientExecutableURL = 
,11-23 19:15:25.866  5754  5770 D bt_bte_conf:   serviceDescription  = 
11-23 19:15:25.867  5754  5770 D bt_bte_conf:   documentationURL    = 
11-23 19:15:25.867  5754  5770 D bt_bte_conf: bte_load_did_conf no section named DID2.
11-23 19:15:25.867  5754  5767 D bt_stack_manager: event_start_up_stack finished
,11-23 19:15:25.868  5754  5766 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
,11-23 19:15:25.869  5754  5766 D BluetoothAdapterProperties: Setting state to 15
11-23 19:15:25.869  5754  5766 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
11-23 19:15:25.871  5588  5588 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-23 19:15:25.872  5754  5766 I BluetoothAdapterState: Entering BleOnState
,11-23 19:15:25.877  5754  5774 I bt_vendor: low_power_mode_cb
,11-23 19:15:25.877  5754  5766 D BluetoothAdapterState: Current state: BLE ON, message: 1
11-23 19:15:25.877  5754  5766 D BluetoothAdapterProperties: Setting state to 11
11-23 19:15:25.877  5754  5766 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,11-23 19:15:25.882  5754  5754 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f8a38f6
,11-23 19:15:25.884  5754  5754 D HeadsetService: Received start request. Starting profile...
11-23 19:15:25.886  5754  5754 I BluetoothHeadsetServiceJni: classInitNative: succeeds
11-23 19:15:25.887  5588  5588 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-23 19:15:25.887  5754  5754 D HeadsetStateMachine: make
,11-23 19:15:25.898  5754  5766 I BluetoothAdapterState: Entering PendingCommandState
,11-23 19:15:25.900  5754  5754 D HeadsetStateMachine: max_hf_connections = 1
,11-23 19:15:25.900  5754  5754 I bt_bluedroid: get_profile_interface handsfree
,11-23 19:15:25.901  5754  5770 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
11-23 19:15:25.901  5754  5770 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
,11-23 19:15:25.904  5754  5754 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f8a38f6
,11-23 19:15:25.905  5754  5754 D A2dpService: Received start request. Starting profile...
11-23 19:15:25.905  5754  5754 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,11-23 19:15:25.906  5754  5754 I bt_bluedroid: get_profile_interface avrcp
,11-23 19:15:25.911  5754  5754 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
11-23 19:15:25.911  5754  5754 I BluetoothA2dpServiceJni: classInitNative: succeeds
11-23 19:15:25.911  5754  5754 D A2dpStateMachine: make
,11-23 19:15:25.913  5754  5754 I bt_bluedroid: get_profile_interface a2dp
11-23 19:15:25.913  5754  5770 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
11-23 19:15:25.915  5754  5785 D A2dpStateMachine: Enter Disconnected: -2
11-23 19:15:25.916  5754  5754 I BluetoothHidServiceJni: classInitNative: succeeds
,11-23 19:15:25.917  5754  5754 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f8a38f6
11-23 19:15:25.917  3580  3580 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,11-23 19:15:25.918  5654  5654 D BluetoothInputDevice: Proxy object connected
,11-23 19:15:25.918  5754  5754 D HidService: Received start request. Starting profile...
11-23 19:15:25.918  5754  5754 I bt_bluedroid: get_profile_interface hidhost
11-23 19:15:25.918  5754  5754 D HidService: setHidService(): set to: null
11-23 19:15:25.919  5754  5770 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf3ec256d
11-23 19:15:25.919  5754  5770 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
11-23 19:15:25.919  5754  5754 I BluetoothHealthServiceJni: classInitNative: succeeds
11-23 19:15:25.920  5654  5654 D HidProfile: Bluetooth service connected
11-23 19:15:25.920  5754  5754 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f8a38f6
11-23 19:15:25.920  5754  5754 D HealthService: Received start request. Starting profile...
11-23 19:15:25.922  5754  5754 I bt_bluedroid: get_profile_interface health
,11-23 19:15:25.922  5754  5754 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,11-23 19:15:25.923  5754  5754 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f8a38f6
,11-23 19:15:25.924  5654  5654 D BluetoothPan: BluetoothPAN Proxy object connected
11-23 19:15:25.924  5754  5754 D PanService: Received start request. Starting profile...
11-23 19:15:25.924  5754  5754 D BluetoothPanServiceJni: initializeNative(L110): pan
,11-23 19:15:25.924  5754  5754 I bt_bluedroid: get_profile_interface pan
11-23 19:15:25.925  5654  5654 D PanProfile: Bluetooth service connected
11-23 19:15:25.925  5754  5770 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,11-23 19:15:25.927  5754  5754 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f8a38f6
,11-23 19:15:25.928  5654  5654 D BluetoothMap: Proxy object connected
,11-23 19:15:25.929  5654  5654 D MapProfile: Bluetooth service connected
11-23 19:15:25.929  5654  5654 D BluetoothMap: getConnectedDevices()
11-23 19:15:25.930  5754  5754 D BluetoothMapService: Received start request. Starting profile...
11-23 19:15:25.930  5754  5754 D BluetoothMapService: start()
11-23 19:15:25.932  5754  5754 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
11-23 19:15:25.933  5754  5754 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
11-23 19:15:25.933  5754  5754 D BluetoothMapAppObserver: createReceiver()
11-23 19:15:25.934  5754  5754 D BluetoothMapAppObserver: initObservers()
11-23 19:15:25.934  5754  5754 D BluetoothMapAppObserver: getEnabledAccountItems()
,11-23 19:15:25.942  5754  5754 V SapService: SapBinder()
,11-23 19:15:25.942  5754  5754 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f8a38f6
,11-23 19:15:25.942  5754  5754 D SapService: Received start request. Starting profile...
11-23 19:15:25.942  5754  5754 V SapService: start()
11-23 19:15:25.944  5754  5754 V BluetoothAdapterState: isTurningOff()=false
11-23 19:15:25.944  5754  5754 V BluetoothAdapterState: isTurningOn()=true
11-23 19:15:25.944  5754  5754 V BluetoothAdapterState: isBleTurningOn()=false
11-23 19:15:25.944  5754  5754 V BluetoothAdapterState: isBleTurningOff()=false
11-23 19:15:25.944  5754  5783 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
11-23 19:15:25.944  5754  5754 V BluetoothAdapterState: isTurningOff()=false
11-23 19:15:25.944  5754  5754 V BluetoothAdapterState: isTurningOn()=true
11-23 19:15:25.944  5754  5754 V BluetoothAdapterState: isBleTurningOn()=false
11-23 19:15:25.944  5754  5754 V BluetoothAdapterState: isBleTurningOff()=false
11-23 19:15:25.944  5754  5754 V BluetoothAdapterState: isTurningOff()=false
11-23 19:15:25.944  5754  5754 V BluetoothAdapterState: isTurningOn()=true
11-23 19:15:25.945  5754  5754 V BluetoothAdapterState: isBleTurningOn()=false
11-23 19:15:25.945  5754  5754 V BluetoothAdapterState: isBleTurningOff()=false
11-23 19:15:25.945  5754  5754 V BluetoothAdapterState: isTurningOff()=false
11-23 19:15:25.945  5754  5754 V BluetoothAdapterState: isTurningOn()=true
11-23 19:15:25.945  5754  5754 V BluetoothAdapterState: isBleTurningOn()=false
11-23 19:15:25.945  5754  5754 V BluetoothAdapterState: isBleTurningOff()=false
11-23 19:15:25.945  5754  5754 V BluetoothAdapterState: isTurningOff()=false
11-23 19:15:25.945  5754  5754 V BluetoothAdapterState: isTurningOn()=true
11-23 19:15:25.945  5754  5754 V BluetoothAdapterState: isBleTurningOn()=false
11-23 19:15:25.945  5754  5754 V BluetoothAdapterState: isBleTurningOff()=false
11-23 19:15:25.946  5754  5754 V BluetoothAdapterState: isTurningOff()=false
11-23 19:15:25.946  5754  5754 V BluetoothAdapterState: isTurningOn()=true
11-23 19:15:25.946  5754  5754 V BluetoothAdapterState: isBleTurningOn()=false
11-23 19:15:25.946  5754  5754 V BluetoothAdapterState: isBleTurningOff()=false
11-23 19:15:25.947  5754  5754 V BluetoothAdapterState: isTurningOff()=false
11-23 19:15:25.947  5754  5754 V BluetoothAdapterState: isTurningOn()=true
11-23 19:15:25.947  5754  5754 V BluetoothAdapterState: isBleTurningOn()=false
11-23 19:15:25.947  5754  5754 V BluetoothAdapterState: isBleTurningOff()=false
11-23 19:15:25.947  5754  5766 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
11-23 19:15:25.947  5754  5766 D BluetoothAdapterProperties: ScanMode =  20
11-23 19:15:25.947  5754  5766 D BluetoothAdapterProperties: State =  11
,11-23 19:15:25.947  5754  5766 D BluetoothAdapterProperties: Setting state to 12
11-23 19:15:25.947  5754  5766 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
11-23 19:15:25.948  3112  3126 D BluetoothInputDevice: onBluetoothStateChange: up=true
11-23 19:15:25.948  5754  5766 I BluetoothAdapterState: Entering OnState
11-23 19:15:25.948  5654  5654 D BluetoothMap: Bluetooth is Not enabled
11-23 19:15:25.950   929   946 D BluetoothHeadset: onBluetoothStateChange: up=true
11-23 19:15:25.950   929   946 D BluetoothHeadset: onBluetoothStateChange: up=true
11-23 19:15:25.950  3112  3112 D BluetoothInputDevice: Proxy object connected
11-23 19:15:25.950  3112  3112 D HidProfile: Bluetooth service connected
,11-23 19:15:25.950  3112  3947 D BluetoothPbap: onBluetoothStateChange: up=true
11-23 19:15:25.951  5754  5770 D BluetoothAdapterProperties: Scan Mode:21
11-23 19:15:25.952  5754  5770 D BluetoothAdapterProperties: Discoverable Timeout:120
11-23 19:15:25.952  5654  5665 D BluetoothMap: onBluetoothStateChange: up=true
11-23 19:15:25.952  5588  5588 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
11-23 19:15:25.952  3112  3126 D BluetoothMap: onBluetoothStateChange: up=true
11-23 19:15:25.954  3112  3112 D BluetoothMap: Proxy object connected
11-23 19:15:25.954  5654  5671 D BluetoothPan: onBluetoothStateChange on: true
11-23 19:15:25.954  3112  3112 D MapProfile: Bluetooth service connected
,11-23 19:15:25.954  3112  3112 D BluetoothMap: getConnectedDevices()
11-23 19:15:25.954  3112  3129 D BluetoothPan: onBluetoothStateChange on: true
11-23 19:15:25.956   929   946 D BluetoothHeadset: onBluetoothStateChange: up=true
11-23 19:15:25.956  5588  5588 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-23 19:15:25.956  5588  5588 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-23 19:15:25.956  5588  5588 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-23 19:15:25.956  5588  5588 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-23 19:15:25.956  5588  5588 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-23 19:15:25.956  5588  5588 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-23 19:15:25.956  5588  5588 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-23 19:15:25.956  5588  5588 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-23 19:15:25.956  5588  5588 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-23 19:15:25.956  3800  3827 D BluetoothHeadset: onBluetoothStateChange: up=true
11-23 19:15:25.956  3112  3112 D BluetoothPan: BluetoothPAN Proxy object connected
11-23 19:15:25.956  3112  3112 D PanProfile: Bluetooth service connected
11-23 19:15:25.956  5654  5665 D BluetoothInputDevice: onBluetoothStateChange: up=true
,11-23 19:15:25.957  5654  5671 D BluetoothPbap: onBluetoothStateChange: up=true
11-23 19:15:25.957  5588  5588 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
11-23 19:15:25.957   929   946 D BluetoothA2dp: onBluetoothStateChange: up=true
11-23 19:15:25.958  3112  3947 D BluetoothHeadset: onBluetoothStateChange: up=true
11-23 19:15:25.959  3112  3129 D BluetoothA2dp: onBluetoothStateChange: up=true
11-23 19:15:25.959   929   929 D BluetoothA2dp: Proxy object connected
11-23 19:15:25.960  3112  3112 D BluetoothA2dp: Proxy object connected
11-23 19:15:25.960  5754  5754 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,11-23 19:15:25.961  5754  5754 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
11-23 19:15:25.962   929   929 I Telecom : BluetoothPhoneService: queryPhoneState
11-23 19:15:25.964  5588  5588 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
11-23 19:15:25.965  5754  5754 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-23 19:15:25.965  5654  5654 D LocalBluetoothProfileManager: Adding local A2DP profile
11-23 19:15:25.967  5588  5588 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-23 19:15:25.968  5754  5754 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-23 19:15:25.968  5654  5654 D LocalBluetoothProfileManager: Adding local HEADSET profile
11-23 19:15:25.969  5754  5754 D ObexServerSockets: Succeed to create listening sockets 
11-23 19:15:25.969  5754  5754 D ObexServerSockets0: startAccept()
11-23 19:15:25.969  5754  5754 D ObexServerSockets0: prepareForNewConnect()
,11-23 19:15:25.972  5754  5754 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
,11-23 19:15:25.972  5754  5754 D BluetoothSdpJni: SDP Create record success - handle: 0
11-23 19:15:25.972  5754  5754 D BluetoothMapService: onReceive
11-23 19:15:25.972  5754  5791 D ObexServerSockets0: Accepting socket connection...
,11-23 19:15:25.973  5754  5754 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
11-23 19:15:25.973  5754  5754 D BluetoothMapService: STATE_ON
11-23 19:15:25.973  5754  5792 D ObexServerSockets0: Accepting socket connection...
,11-23 19:15:25.975  5754  5793 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-23 19:15:25.976  5654  5654 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
11-23 19:15:25.978  5754  5793 D BluetoothSdpJni: sdpCreateSapsRecordNative:
11-23 19:15:25.978  5754  5793 D BluetoothSdpJni: SDP Create record success - handle: 1
,11-23 19:15:25.978  5654  5654 D BluetoothA2dp: Proxy object connected
,11-23 19:15:25.982  3580  3580 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,11-23 19:15:25.988  5654  5654 D DockEventReceiver: finishStartingService: stopping service
,11-23 19:15:25.992  3112  3112 D BluetoothPbap: Proxy object connected
11-23 19:15:25.992  3112  3112 D PbapServerProfile: Bluetooth service connected
11-23 19:15:25.992  5654  5654 D BluetoothPbap: Proxy object connected
11-23 19:15:25.993  5654  5654 D PbapServerProfile: Bluetooth service connected
,11-23 19:15:25.997  5754  5754 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,11-23 19:15:25.997  5754  5754 D ObexServerSockets0: prepareForNewConnect()
11-23 19:15:26.000  5754  5797 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-23 19:15:26.012  5754  5801 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-23 19:15:26.013  5754  5801 I BtOppRfcommListener: Accept thread started.
,11-23 19:15:26.051  3112  3129 D BluetoothHeadset: Proxy object connected
,11-23 19:15:26.052  3112  3112 D HeadsetProfile: Bluetooth service connected
11-23 19:15:26.052  3800  3980 D BluetoothHeadset: Proxy object connected
11-23 19:15:26.052   929   929 D BluetoothHeadset: Proxy object connected
11-23 19:15:26.052   929   929 D BluetoothHeadset: Proxy object connected
11-23 19:15:26.052   929   929 D BluetoothHeadset: Proxy object connected
,11-23 19:15:26.056   929   946 D BluetoothHeadset: Proxy object connected
11-23 19:15:26.057  3800  3830 D BluetoothHeadset: Proxy object connected
,11-23 19:15:26.059  3112  3126 D BluetoothHeadset: Proxy object connected
11-23 19:15:26.060  3112  3112 D HeadsetProfile: Bluetooth service connected
,11-23 19:15:26.071  5654  5671 D BluetoothHeadset: Proxy object connected
,11-23 19:15:26.072  5654  5654 D HeadsetProfile: Bluetooth service connected
,11-23 19:15:26.797   536   536 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,11-23 19:15:27.857   929  2972 D ConnectivityService: handlePromptUnvalidated 101
,11-23 19:15:28.279  3666  3857 I Keyboard.Facilitator.LanguageModelFlusher: run()
,11-23 19:15:28.279  3666  3857 I Keyboard.Facilitator: flushDynamicLanguageModels()
,11-23 19:15:28.308  3580  3580 I ConfigService: onCreate
,11-23 19:15:29.909  5754  5766 D BluetoothAdapterState: Current state: ON, message: 23
,11-23 19:15:29.910  5754  5766 D BluetoothAdapterProperties: Setting state to 13
,11-23 19:15:29.911  5754  5766 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,11-23 19:15:29.913  5754  5766 D BluetoothAdapterProperties: onBluetoothDisable()
,11-23 19:15:29.916  5754  5766 I BluetoothAdapterState: Entering PendingCommandState
,11-23 19:15:29.917  5754  5770 D BluetoothAdapterProperties: Scan Mode:20
,11-23 19:15:29.917  5754  5766 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
,11-23 19:15:29.922  5754  5754 D HeadsetService: Received stop request...Stopping profile...
11-23 19:15:29.923  5588  5588 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,11-23 19:15:29.923  5588  5588 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-23 19:15:29.923  5588  5588 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-23 19:15:29.923  5588  5588 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-23 19:15:29.923  5588  5588 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-23 19:15:29.923  5588  5588 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-23 19:15:29.923  5588  5588 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-23 19:15:29.923  5588  5588 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-23 19:15:29.923  5588  5588 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-23 19:15:29.923  5588  5588 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-23 19:15:29.926  3112  3947 D BluetoothHeadset: Proxy object disconnected
11-23 19:15:29.927  3112  3112 D HeadsetProfile: Bluetooth service disconnected
11-23 19:15:29.927  3800  3827 D BluetoothHeadset: Proxy object disconnected
11-23 19:15:29.927  5588  5588 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,11-23 19:15:29.927  5588  5588 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
11-23 19:15:29.927  5754  5754 V BluetoothAdapterState: isTurningOff()=true
11-23 19:15:29.927  5754  5754 V BluetoothAdapterState: isTurningOn()=false
11-23 19:15:29.928  5754  5754 V BluetoothAdapterState: isBleTurningOn()=false
11-23 19:15:29.928  5754  5754 V BluetoothAdapterState: isBleTurningOff()=false
11-23 19:15:29.928  5654  5665 D BluetoothHeadset: Proxy object disconnected
11-23 19:15:29.929   929   929 D BluetoothHeadset: Proxy object disconnected
11-23 19:15:29.929   929   929 D BluetoothHeadset: Proxy object disconnected
11-23 19:15:29.929   929   929 D BluetoothHeadset: Proxy object disconnected
11-23 19:15:29.929  5754  5754 D A2dpService: Received stop request...Stopping profile...
11-23 19:15:29.930  5754  5785 D A2dpStateMachine: Exit Disconnected: -1
11-23 19:15:29.932   929   929 D BluetoothA2dp: Proxy object disconnected
11-23 19:15:29.933  3112  3112 D BluetoothA2dp: Proxy object disconnected
,11-23 19:15:29.934  5654  5654 D HeadsetProfile: Bluetooth service disconnected
11-23 19:15:29.935  5654  5654 D BluetoothA2dp: Proxy object disconnected
11-23 19:15:29.942  5754  5754 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
11-23 19:15:29.942  5754  5754 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
11-23 19:15:29.942  5754  5777 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-23 19:15:29.943  5754  5777 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-23 19:15:29.943  5754  5777 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-23 19:15:29.943  5754  5770 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
,11-23 19:15:29.943  5754  5754 D HidService: Received stop request...Stopping profile...
11-23 19:15:29.943  5754  5754 D HidService: Stopping Bluetooth HidService
11-23 19:15:29.943  5754  5770 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
11-23 19:15:29.945  5654  5654 D BluetoothInputDevice: Proxy object disconnected
11-23 19:15:29.945  5654  5654 D HidProfile: Bluetooth service disconnected
11-23 19:15:29.946  3112  3112 D BluetoothInputDevice: Proxy object disconnected
,11-23 19:15:29.946  5754  5754 V BluetoothAdapterState: isTurningOff()=true
11-23 19:15:29.946  3112  3112 D HidProfile: Bluetooth service disconnected
11-23 19:15:29.946  5754  5754 V BluetoothAdapterState: isTurningOn()=false
11-23 19:15:29.946  5754  5754 V BluetoothAdapterState: isBleTurningOn()=false
11-23 19:15:29.946  5754  5754 V BluetoothAdapterState: isBleTurningOff()=false
,11-23 19:15:29.947  5754  5754 D HealthService: Received stop request...Stopping profile...
,11-23 19:15:29.951  5754  5770 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
11-23 19:15:29.951  5754  5777 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-23 19:15:29.951  5754  5777 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,11-23 19:15:29.951  5754  5777 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
11-23 19:15:29.952  5754  5777 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
11-23 19:15:29.952  5754  5777 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
11-23 19:15:29.952  5754  5777 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
11-23 19:15:29.953  5754  5754 D PanService: Received stop request...Stopping profile...
11-23 19:15:29.954  3112  3112 D BluetoothPan: BluetoothPAN Proxy object disconnected
11-23 19:15:29.955  3112  3112 D PanProfile: Bluetooth service disconnected
11-23 19:15:29.955  5654  5654 D BluetoothPan: BluetoothPAN Proxy object disconnected
11-23 19:15:29.955  5654  5654 D PanProfile: Bluetooth service disconnected
11-23 19:15:29.955  5754  5754 D BluetoothMapService: Received stop request...Stopping profile...
11-23 19:15:29.955  5754  5754 D BluetoothMapService: stop()
11-23 19:15:29.956  5754  5754 D BluetoothMapAppObserver: deinitObservers()
11-23 19:15:29.956  5754  5754 D BluetoothMapAppObserver: removeReceiver()
11-23 19:15:29.960  3112  3112 D BluetoothMap: Proxy object disconnected
11-23 19:15:29.960  3112  3112 D MapProfile: Bluetooth service disconnected
11-23 19:15:29.961  5754  5754 D SapService: Received stop request...Stopping profile...
11-23 19:15:29.961  5754  5754 V SapService: stop()
,11-23 19:15:29.963  5754  5754 V BluetoothAdapterState: isTurningOff()=true
11-23 19:15:29.963  5754  5754 V BluetoothAdapterState: isTurningOn()=false
11-23 19:15:29.963  5754  5754 V BluetoothAdapterState: isBleTurningOn()=false
,11-23 19:15:29.963  5754  5754 V BluetoothAdapterState: isBleTurningOff()=false
11-23 19:15:29.963  5754  5754 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
11-23 19:15:29.963  5754  5754 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
11-23 19:15:29.963  5754  5770 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
11-23 19:15:29.964  5754  5754 V BluetoothAdapterState: isTurningOff()=true
11-23 19:15:29.964  5754  5754 V BluetoothAdapterState: isTurningOn()=false
,11-23 19:15:29.964  5754  5754 V BluetoothAdapterState: isBleTurningOn()=false
11-23 19:15:29.964  5754  5754 V BluetoothAdapterState: isBleTurningOff()=false
11-23 19:15:29.964  5754  5754 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
11-23 19:15:29.964  5754  5754 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
11-23 19:15:29.965  5754  5770 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
,11-23 19:15:29.965  5754  5754 V BluetoothAdapterState: isTurningOff()=true
11-23 19:15:29.965  5754  5754 V BluetoothAdapterState: isTurningOn()=false
11-23 19:15:29.965  5754  5754 V BluetoothAdapterState: isBleTurningOn()=false
11-23 19:15:29.965  5754  5754 V BluetoothAdapterState: isBleTurningOff()=false
11-23 19:15:29.966  5754  5754 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
11-23 19:15:29.966  5754  5754 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
11-23 19:15:29.967  5588  5588 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-23 19:15:29.961  5654  5654 D BluetoothMap: Proxy object disconnected
11-23 19:15:29.968  5654  5654 D MapProfile: Bluetooth service disconnected
11-23 19:15:29.969  5754  5754 D BluetoothMapService: MAP Service closeService in
11-23 19:15:29.969  5754  5754 D BluetoothMapMasInstance0: MAP Service shutdown
11-23 19:15:29.969  5754  5754 D ObexServerSockets0: shutdown(block = true)
11-23 19:15:29.970  5754  5791 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
11-23 19:15:29.970  5754  5754 D ObexServerSockets0: shutdown called from another thread - interrupt().
11-23 19:15:29.971  5754  5754 D ObexServerSockets0: shutdown called from another thread - interrupt().
,11-23 19:15:29.971  5754  5779 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
11-23 19:15:29.971  5754  5792 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
11-23 19:15:29.972  5654  5654 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,11-23 19:15:29.975  5754  5754 V BluetoothAdapterState: isTurningOff()=true
,11-23 19:15:29.975  5754  5754 V BluetoothAdapterState: isTurningOn()=false
11-23 19:15:29.975  5754  5754 V BluetoothAdapterState: isBleTurningOn()=false
11-23 19:15:29.975  5754  5754 V BluetoothAdapterState: isBleTurningOff()=false
,11-23 19:15:29.976  5754  5754 D BluetoothMapService: cleanup()
11-23 19:15:29.977  5754  5754 D BluetoothMapService: MAP Service closeService in
11-23 19:15:29.977  5754  5754 V BluetoothAdapterState: isTurningOff()=true
,11-23 19:15:29.977  5754  5754 V BluetoothAdapterState: isTurningOn()=false
11-23 19:15:29.977  5754  5754 V BluetoothAdapterState: isBleTurningOn()=false
,11-23 19:15:29.978  5754  5754 V BluetoothAdapterState: isBleTurningOff()=false
11-23 19:15:29.980  5754  5754 I BtOppRfcommListener: stopping Accept Thread
11-23 19:15:29.980  5754  5801 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
11-23 19:15:29.980  5754  5801 I BtOppRfcommListener: BluetoothSocket listen thread finished
,11-23 19:15:29.982  5754  5766 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
11-23 19:15:29.982  5754  5766 D BluetoothAdapterProperties: Setting state to 15
11-23 19:15:29.982  5654  5654 D DockEventReceiver: finishStartingService: stopping service
11-23 19:15:29.982  3580  3580 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
11-23 19:15:29.982  5754  5766 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
11-23 19:15:29.983  5754  5766 I BluetoothAdapterState: Entering BleOnState
11-23 19:15:29.985  3112  3126 D BluetoothInputDevice: onBluetoothStateChange: up=false
,11-23 19:15:29.986   929   946 D BluetoothHeadset: onBluetoothStateChange: up=false
,11-23 19:15:29.986   929   946 D BluetoothHeadset: onBluetoothStateChange: up=false
11-23 19:15:29.986  3112  3947 D BluetoothPbap: onBluetoothStateChange: up=false
11-23 19:15:29.987  5654  5665 D BluetoothMap: onBluetoothStateChange: up=false
11-23 19:15:29.988  3112  3129 D BluetoothMap: onBluetoothStateChange: up=false
11-23 19:15:29.989  5654  5665 D BluetoothHeadset: onBluetoothStateChange: up=false
11-23 19:15:29.990  5654  5671 D BluetoothPan: onBluetoothStateChange on: false
11-23 19:15:29.990  5654  5654 D BluetoothPbap: Proxy object disconnected
,11-23 19:15:29.990  5654  5654 D PbapServerProfile: Bluetooth service disconnected
,11-23 19:15:29.993  3112  3126 D BluetoothPan: onBluetoothStateChange on: false
,11-23 19:15:29.994  5654  5665 D BluetoothA2dp: onBluetoothStateChange: up=false
11-23 19:15:29.995   929   946 D BluetoothHeadset: onBluetoothStateChange: up=false
11-23 19:15:29.996  3800  3980 D BluetoothHeadset: onBluetoothStateChange: up=false
,11-23 19:15:30.008  5654  5807 D BluetoothInputDevice: onBluetoothStateChange: up=false
,11-23 19:15:30.008  5654  5671 D BluetoothPbap: onBluetoothStateChange: up=false
11-23 19:15:30.009   929   946 D BluetoothA2dp: onBluetoothStateChange: up=false
11-23 19:15:30.009  3112  3947 D BluetoothHeadset: onBluetoothStateChange: up=false
11-23 19:15:30.010  3112  3129 D BluetoothA2dp: onBluetoothStateChange: up=false
11-23 19:15:30.010  5754  5766 D BluetoothAdapterState: Current state: BLE ON, message: 20
11-23 19:15:30.010  5754  5766 D BluetoothAdapterProperties: Setting state to 16
11-23 19:15:30.010  5754  5766 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
11-23 19:15:30.011  5754  5766 D BluetoothAdapterProperties: onBleDisable
11-23 19:15:30.011  5754  5766 I BluetoothAdapterState: Entering PendingCommandState
11-23 19:15:30.011  5754  5767 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
11-23 19:15:30.014  5588  5588 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-23 19:15:30.015  5754  5777 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
11-23 19:15:30.015  5754  5777 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-23 19:15:30.015  5754  5770 D BluetoothAdapterProperties: Scan Mode:20
11-23 19:15:30.016  5654  5654 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
11-23 19:15:30.017  5588  5588 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-23 19:15:30.020  3580  3580 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,11-23 19:15:30.024  5654  5654 D DockEventReceiver: finishStartingService: stopping service
,11-23 19:15:30.231  5754  5770 I bt_hci  : shut_down
,11-23 19:15:30.244  5754  5774 D bt_hwcfg: hw_epilog_process
,11-23 19:15:30.245  5754  5774 I bt_vendor: low_power_mode_cb
,11-23 19:15:30.247  5754  5774 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,11-23 19:15:30.247  5754  5774 I bt_vendor: epilog_cb
11-23 19:15:30.247  5754  5774 I bt_hci  : epilog_finished_callback
,11-23 19:15:30.251  5754  5770 I bt_hci_h4: hal_close
,11-23 19:15:30.251  5754  5770 I bt_userial_vendor: device fd = 54 close
,11-23 19:15:30.367  5754  5767 D bt_stack_manager: event_shut_down_stack finished.
,11-23 19:15:30.369  5754  5766 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,11-23 19:15:30.373  5754  5766 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,11-23 19:15:30.374  5754  5754 D BtGatt.DebugUtils: handleDebugAction() action=null
,11-23 19:15:30.375  5754  5754 D BtGatt.GattService: Received stop request...Stopping profile...
,11-23 19:15:30.375  5754  5754 D BtGatt.GattService: stop()
,11-23 19:15:30.375  5754  5754 D BtGatt.AdvertiseManager: advertise clients cleared
11-23 19:15:30.378  5754  5754 V BluetoothAdapterState: isTurningOff()=false
,11-23 19:15:30.379  5754  5754 V BluetoothAdapterState: isTurningOn()=false
11-23 19:15:30.379  5754  5754 V BluetoothAdapterState: isBleTurningOn()=false
11-23 19:15:30.379  5754  5754 V BluetoothAdapterState: isBleTurningOff()=true
,11-23 19:15:30.380  5754  5766 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
11-23 19:15:30.380  5754  5766 D BluetoothAdapterProperties: Setting state to 10
11-23 19:15:30.380  5754  5766 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
11-23 19:15:30.381  5754  5766 I BluetoothAdapterState: Entering OffState
,11-23 19:15:30.383   929   946 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,11-23 19:15:30.396  5754  5754 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,11-23 19:15:30.396  5754  5754 W BluetoothSdpJni: Cleaning up Bluetooth Health object
11-23 19:15:30.396  5754  5754 I BluetoothServiceJni: cleanupNative: return from cleanup
11-23 19:15:30.398  5754  5767 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,11-23 19:15:30.406  5754  5754 I art     : System.exit called, status: 0
,11-23 19:15:30.406  5754  5754 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,11-23 19:15:30.443   929  3833 I ActivityManager: Process com.android.bluetooth (pid 5754) has died
,11-23 19:15:31.798   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 19:15:32.799   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 19:15:33.340  3580  3580 I ConfigService: onDestroy
,11-23 19:15:33.800   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 19:15:34.801   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 19:15:34.907  5588  5634 D io.jxcore.node.ConnectivityMonitor: stop
,11-23 19:15:34.907  5588  5634 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
,11-23 19:15:34.913  5588  5634 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-23 19:15:34.913  5588  5634 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@a7e4e64 removed from the list
,11-23 19:15:34.913  5588  5634 D io.jxcore.node.ConnectivityMonitor: stop
11-23 19:15:34.915  5588  5634 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,11-23 19:15:34.915  5588  5634 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@ab70493 added. We now have 4 listener(s)
,11-23 19:15:34.915  5588  5634 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-23 19:15:34.917  5588  5634 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-23 19:15:34.917  5588  5634 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@ab70493 removed from the list
11-23 19:15:34.918  5588  5634 D io.jxcore.node.ConnectivityMonitor: stop
,11-23 19:15:34.919  5588  5634 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-23 19:15:34.919  5588  5634 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@3ecd0 added. We now have 4 listener(s)
11-23 19:15:34.919  5588  5634 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-23 19:15:35.802   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 19:15:36.803   536   536 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,11-23 19:15:39.932  5588  5634 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-23 19:15:39.965   929   946 I ActivityManager: Start proc 5812:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,11-23 19:15:40.043  5812  5812 D AdapterServiceConfig: Adding HeadsetService
,11-23 19:15:40.043  5812  5812 D AdapterServiceConfig: Adding A2dpService
11-23 19:15:40.043  5812  5812 D AdapterServiceConfig: Adding HidService
11-23 19:15:40.043  5812  5812 D AdapterServiceConfig: Adding HealthService
11-23 19:15:40.043  5812  5812 D AdapterServiceConfig: Adding PanService
11-23 19:15:40.044  5812  5812 D AdapterServiceConfig: Adding GattService
11-23 19:15:40.044  5812  5812 D AdapterServiceConfig: Adding BluetoothMapService
11-23 19:15:40.044  5812  5812 D AdapterServiceConfig: Adding SapService
,11-23 19:15:40.055   929   946 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@c12e8f1:true
11-23 19:15:40.055  5812  5812 D BluetoothAdapterState: make() - Creating AdapterState
,11-23 19:15:40.058  5812  5812 I bt_bluedroid: init
11-23 19:15:40.058  5812  5824 I BluetoothAdapterState: Entering OffState
,11-23 19:15:40.060  5812  5825 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
11-23 19:15:40.060  5812  5825 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
11-23 19:15:40.060  5812  5825 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
11-23 19:15:40.060  5812  5825 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,11-23 19:15:40.061  5812  5812 I bt_bluedroid: get_profile_interface socket
,11-23 19:15:40.063  5812  5828 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:D4
,11-23 19:15:40.063  5812  5812 I bt_bluedroid: get_profile_interface sdp
11-23 19:15:40.064  5812  5828 D BluetoothAdapterProperties: Name is: Nexus 6P
,11-23 19:15:40.069  5812  5823 I bt_bluedroid: config_hci_snoop_log
,11-23 19:15:40.071   929   946 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,11-23 19:15:40.074  5812  5824 D BluetoothAdapterState: Current state: OFF, message: 0
11-23 19:15:40.074  5812  5824 D BluetoothAdapterProperties: Setting state to 14
11-23 19:15:40.074  5812  5824 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,11-23 19:15:40.076  5812  5824 D BluetoothBondStateMachine: make
,11-23 19:15:40.078  5812  5830 I BluetoothBondStateMachine: StableState(): Entering Off State
,11-23 19:15:40.081  5812  5824 I BluetoothAdapterState: Entering PendingCommandState
,11-23 19:15:40.082  5812  5812 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,11-23 19:15:40.084  5812  5812 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f8a38f6
11-23 19:15:40.085  5812  5812 D BtGatt.DebugUtils: handleDebugAction() action=null
11-23 19:15:40.085  5812  5812 D BtGatt.GattService: Received start request. Starting profile...
11-23 19:15:40.085  5812  5812 D BtGatt.GattService: start()
11-23 19:15:40.086  5812  5812 I bt_bluedroid: get_profile_interface gatt
,11-23 19:15:40.086  5812  5812 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f8a38f6
11-23 19:15:40.087  5812  5812 D BtGatt.AdvertiseManager: advertise manager created
,11-23 19:15:40.092  5812  5812 V BluetoothAdapterState: isTurningOff()=false
11-23 19:15:40.092  5812  5812 V BluetoothAdapterState: isTurningOn()=false
11-23 19:15:40.092  5812  5812 V BluetoothAdapterState: isBleTurningOn()=true
,11-23 19:15:40.092  5812  5812 V BluetoothAdapterState: isBleTurningOff()=false
11-23 19:15:40.093  5812  5824 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,11-23 19:15:40.094  5812  5824 I bt_bluedroid: bt_bluedroid
,11-23 19:15:40.095  5812  5825 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,11-23 19:15:40.095  5812  5825 I bt_hci  : start_up
,11-23 19:15:40.100  5812  5825 I bt_vendor: alloc value 0xf3f63871
,11-23 19:15:40.100  5812  5825 I bt_vendor: init
11-23 19:15:40.100  5812  5825 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
11-23 19:15:40.100  5812  5825 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,11-23 19:15:40.213  5812  5825 D bt_hci  : start_up starting async portion
11-23 19:15:40.213  5812  5833 I bt_hci  : event_finish_startup
,11-23 19:15:40.214  5812  5833 I bt_hci_h4: hal_open
11-23 19:15:40.214  5812  5833 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
11-23 19:15:40.213  5834  5834 W irq/448-msm_hs_: type=1400 audit(0.0:118): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
11-23 19:15:40.217  5812  5833 I bt_userial_vendor: device fd = 54 open
,11-23 19:15:40.233  5812  5833 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,11-23 19:15:40.237  5812  5833 D bt_hwcfg: Chipset BCM4358A3
,11-23 19:15:40.238  5812  5833 D bt_hwcfg: Target name = [BCM4358A3]
11-23 19:15:40.238  5812  5833 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,11-23 19:15:40.748  5812  5833 I bt_hwcfg: bt vendor lib: set UART baud 115200
,11-23 19:15:40.750  5812  5833 D bt_hwcfg: Settlement delay -- 100 ms
11-23 19:15:40.750  5812  5833 I bt_hwcfg: Setting fw settlement delay to 100 
,11-23 19:15:40.884  5812  5833 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,11-23 19:15:40.884  5812  5833 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:D4
,11-23 19:15:40.886  5812  5833 I bt_hwcfg: vendor lib fwcfg completed
,11-23 19:15:40.886  5812  5833 I bt_vendor: firmware callback
11-23 19:15:40.886  5812  5833 I bt_hci  : firmware_config_callback
,11-23 19:15:40.895  5812  5836 I bt_btu  : btu_task pending for preload complete event
,11-23 19:15:40.896  5812  5836 I bt_btu_task: Bluetooth chip preload is complete
,11-23 19:15:40.896  5812  5836 I bt_btu  : btu_task received preload complete event
,11-23 19:15:40.902  5812  5836 I         : BTE_InitTraceLevels -- TRC_HCI
,11-23 19:15:40.902  5812  5836 I         : BTE_InitTraceLevels -- TRC_L2CAP
11-23 19:15:40.902  5812  5836 I         : BTE_InitTraceLevels -- TRC_RFCOMM
11-23 19:15:40.902  5812  5836 I         : BTE_InitTraceLevels -- TRC_AVDT
11-23 19:15:40.902  5812  5836 I         : BTE_InitTraceLevels -- TRC_AVRC
11-23 19:15:40.902  5812  5836 I         : BTE_InitTraceLevels -- TRC_A2D
11-23 19:15:40.902  5812  5836 I         : BTE_InitTraceLevels -- TRC_BNEP
,11-23 19:15:40.903  5812  5836 I         : BTE_InitTraceLevels -- TRC_BTM
11-23 19:15:40.903  5812  5836 I         : BTE_InitTraceLevels -- TRC_GAP
11-23 19:15:40.903  5812  5836 I         : BTE_InitTraceLevels -- TRC_PAN
11-23 19:15:40.903  5812  5836 I         : BTE_InitTraceLevels -- TRC_SDP
11-23 19:15:40.903  5812  5836 I         : BTE_InitTraceLevels -- TRC_GATT
11-23 19:15:40.903  5812  5836 I         : BTE_InitTraceLevels -- TRC_SMP
,11-23 19:15:40.903  5812  5836 I         : BTE_InitTraceLevels -- TRC_BTAPP
11-23 19:15:40.903  5812  5836 I         : BTE_InitTraceLevels -- TRC_BTIF
,11-23 19:15:41.000  5812  5836 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf3ee1549
,11-23 19:15:41.000  5812  5836 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf3ee1549 
,11-23 19:15:41.023  5812  5828 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = true
,11-23 19:15:41.026  5812  5828 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,11-23 19:15:41.027  5812  5828 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:D4
,11-23 19:15:41.030  5812  5828 D BluetoothAdapterProperties: Name is: Nexus 6P
,11-23 19:15:41.033  5812  5828 D BluetoothAdapterProperties: Scan Mode:20
,11-23 19:15:41.034  5812  5828 D BluetoothAdapterProperties: Discoverable Timeout:120
,11-23 19:15:41.034  5812  5828 D bt_hci  : do_postload posting postload work item
,11-23 19:15:41.034  5812  5833 I bt_hci  : event_postload
11-23 19:15:41.034  5812  5833 I bt_vendor: sco_config_cb
11-23 19:15:41.034  5812  5833 I bt_hci  : sco_config_callback postload finished.
11-23 19:15:41.037  5812  5828 D bt_bte_conf: Device ID record 1 : primary
11-23 19:15:41.037  5812  5828 D bt_bte_conf:   vendorId            = 000f
11-23 19:15:41.037  5812  5828 D bt_bte_conf:   vendorIdSource      = 0001
11-23 19:15:41.037  5812  5828 D bt_bte_conf:   product             = 1200
,11-23 19:15:41.037  5812  5828 D bt_bte_conf:   version             = 1436
11-23 19:15:41.037  5812  5828 D bt_bte_conf:   clientExecutableURL = 
11-23 19:15:41.037  5812  5828 D bt_bte_conf:   serviceDescription  = 
11-23 19:15:41.037  5812  5828 D bt_bte_conf:   documentationURL    = 
,11-23 19:15:41.038  5812  5828 D bt_bte_conf: bte_load_did_conf no section named DID2.
11-23 19:15:41.038  5812  5825 D bt_stack_manager: event_start_up_stack finished
11-23 19:15:41.040  5812  5824 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
11-23 19:15:41.040  5812  5824 D BluetoothAdapterProperties: Setting state to 15
11-23 19:15:41.040  5812  5824 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
11-23 19:15:41.042  5812  5833 I bt_vendor: low_power_mode_cb
11-23 19:15:41.043  5812  5824 I BluetoothAdapterState: Entering BleOnState
,11-23 19:15:41.046  5812  5824 D BluetoothAdapterState: Current state: BLE ON, message: 1
11-23 19:15:41.046  5812  5824 D BluetoothAdapterProperties: Setting state to 11
11-23 19:15:41.046  5812  5824 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,11-23 19:15:41.051  5812  5812 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f8a38f6
,11-23 19:15:41.053  5812  5812 D HeadsetService: Received start request. Starting profile...
11-23 19:15:41.056  5812  5812 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,11-23 19:15:41.056  5812  5812 D HeadsetStateMachine: make
,11-23 19:15:41.061  5812  5824 I BluetoothAdapterState: Entering PendingCommandState
,11-23 19:15:41.067  5812  5812 D HeadsetStateMachine: max_hf_connections = 1
,11-23 19:15:41.067  5812  5812 I bt_bluedroid: get_profile_interface handsfree
,11-23 19:15:41.067  5812  5828 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
11-23 19:15:41.069  5812  5828 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
11-23 19:15:41.074  5812  5812 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f8a38f6
11-23 19:15:41.075  5812  5812 D A2dpService: Received start request. Starting profile...
11-23 19:15:41.075  5812  5812 I BluetoothAvrcpServiceJni: classInitNative: succeeds
11-23 19:15:41.076  5812  5812 I bt_bluedroid: get_profile_interface avrcp
,11-23 19:15:41.083  5812  5812 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
11-23 19:15:41.083  5812  5812 I BluetoothA2dpServiceJni: classInitNative: succeeds
,11-23 19:15:41.083  5812  5812 D A2dpStateMachine: make
11-23 19:15:41.084  5812  5812 I bt_bluedroid: get_profile_interface a2dp
,11-23 19:15:41.085  5812  5828 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,11-23 19:15:41.086  5812  5843 D A2dpStateMachine: Enter Disconnected: -2
11-23 19:15:41.086  5812  5812 I BluetoothHidServiceJni: classInitNative: succeeds
11-23 19:15:41.087  5812  5812 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f8a38f6
11-23 19:15:41.087  5812  5812 D HidService: Received start request. Starting profile...
11-23 19:15:41.088  5812  5812 I bt_bluedroid: get_profile_interface hidhost
11-23 19:15:41.088  5812  5812 D HidService: setHidService(): set to: null
11-23 19:15:41.088  5812  5812 I BluetoothHealthServiceJni: classInitNative: succeeds
11-23 19:15:41.089  5812  5828 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf3ec256d
11-23 19:15:41.089  5812  5812 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f8a38f6
11-23 19:15:41.089  5812  5828 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
11-23 19:15:41.089  5812  5812 D HealthService: Received start request. Starting profile...
,11-23 19:15:41.091  5812  5812 I bt_bluedroid: get_profile_interface health
,11-23 19:15:41.092  5812  5812 I BluetoothPanServiceJni: classInitNative(L105): succeeds
11-23 19:15:41.093  5812  5812 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f8a38f6
,11-23 19:15:41.093  5812  5812 D PanService: Received start request. Starting profile...
11-23 19:15:41.094  5812  5812 D BluetoothPanServiceJni: initializeNative(L110): pan
11-23 19:15:41.094  5812  5812 I bt_bluedroid: get_profile_interface pan
11-23 19:15:41.094  5812  5828 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,11-23 19:15:41.096  5812  5812 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f8a38f6
,11-23 19:15:41.097  5812  5812 D BluetoothMapService: Received start request. Starting profile...
11-23 19:15:41.097  5812  5812 D BluetoothMapService: start()
,11-23 19:15:41.100  5812  5812 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,11-23 19:15:41.101  5812  5812 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
11-23 19:15:41.101  5812  5812 D BluetoothMapAppObserver: createReceiver()
,11-23 19:15:41.102  5812  5812 D BluetoothMapAppObserver: initObservers()
11-23 19:15:41.102  5812  5812 D BluetoothMapAppObserver: getEnabledAccountItems()
,11-23 19:15:41.110  5812  5812 V SapService: SapBinder()
11-23 19:15:41.110  5812  5812 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f8a38f6
,11-23 19:15:41.110  5812  5812 D SapService: Received start request. Starting profile...
11-23 19:15:41.110  5812  5812 V SapService: start()
,11-23 19:15:41.114  5812  5812 V BluetoothAdapterState: isTurningOff()=false
11-23 19:15:41.114  5812  5812 V BluetoothAdapterState: isTurningOn()=true
,11-23 19:15:41.114  5812  5812 V BluetoothAdapterState: isBleTurningOn()=false
11-23 19:15:41.115  5812  5812 V BluetoothAdapterState: isBleTurningOff()=false
11-23 19:15:41.115  5812  5841 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
11-23 19:15:41.115  5812  5812 V BluetoothAdapterState: isTurningOff()=false
11-23 19:15:41.115  5812  5812 V BluetoothAdapterState: isTurningOn()=true
11-23 19:15:41.115  5812  5812 V BluetoothAdapterState: isBleTurningOn()=false
11-23 19:15:41.115  5812  5812 V BluetoothAdapterState: isBleTurningOff()=false
11-23 19:15:41.115  5812  5812 V BluetoothAdapterState: isTurningOff()=false
11-23 19:15:41.115  5812  5812 V BluetoothAdapterState: isTurningOn()=true
11-23 19:15:41.115  5812  5812 V BluetoothAdapterState: isBleTurningOn()=false
11-23 19:15:41.115  5812  5812 V BluetoothAdapterState: isBleTurningOff()=false
11-23 19:15:41.115  5812  5812 V BluetoothAdapterState: isTurningOff()=false
11-23 19:15:41.115  5812  5812 V BluetoothAdapterState: isTurningOn()=true
11-23 19:15:41.115  5812  5812 V BluetoothAdapterState: isBleTurningOn()=false
11-23 19:15:41.115  5812  5812 V BluetoothAdapterState: isBleTurningOff()=false
11-23 19:15:41.115  5812  5812 V BluetoothAdapterState: isTurningOff()=false
,11-23 19:15:41.115  5812  5812 V BluetoothAdapterState: isTurningOn()=true
11-23 19:15:41.115  5812  5812 V BluetoothAdapterState: isBleTurningOn()=false
11-23 19:15:41.115  5812  5812 V BluetoothAdapterState: isBleTurningOff()=false
11-23 19:15:41.115  5812  5812 V BluetoothAdapterState: isTurningOff()=false
11-23 19:15:41.115  5812  5812 V BluetoothAdapterState: isTurningOn()=true
11-23 19:15:41.116  5812  5812 V BluetoothAdapterState: isBleTurningOn()=false
11-23 19:15:41.116  5812  5812 V BluetoothAdapterState: isBleTurningOff()=false
11-23 19:15:41.116  3580  3580 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
11-23 19:15:41.117  5812  5812 V BluetoothAdapterState: isTurningOff()=false
11-23 19:15:41.117  5812  5812 V BluetoothAdapterState: isTurningOn()=true
,11-23 19:15:41.117  5812  5812 V BluetoothAdapterState: isBleTurningOn()=false
11-23 19:15:41.117  5812  5812 V BluetoothAdapterState: isBleTurningOff()=false
11-23 19:15:41.117  5812  5824 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
11-23 19:15:41.118  5812  5824 D BluetoothAdapterProperties: ScanMode =  20
11-23 19:15:41.118  5812  5824 D BluetoothAdapterProperties: State =  11
11-23 19:15:41.118  5812  5824 D BluetoothAdapterProperties: Setting state to 12
11-23 19:15:41.118  5812  5824 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
11-23 19:15:41.118  5812  5824 I BluetoothAdapterState: Entering OnState
,11-23 19:15:41.119  3112  3126 D BluetoothInputDevice: onBluetoothStateChange: up=true
,11-23 19:15:41.122  5812  5828 D BluetoothAdapterProperties: Scan Mode:21
,11-23 19:15:41.122  5812  5828 D BluetoothAdapterProperties: Discoverable Timeout:120
11-23 19:15:41.123   929   946 D BluetoothHeadset: onBluetoothStateChange: up=true
11-23 19:15:41.123   929   946 D BluetoothHeadset: onBluetoothStateChange: up=true
11-23 19:15:41.123  3112  3129 D BluetoothPbap: onBluetoothStateChange: up=true
11-23 19:15:41.125  3112  3112 D BluetoothInputDevice: Proxy object connected
11-23 19:15:41.125  3112  3112 D HidProfile: Bluetooth service connected
11-23 19:15:41.125  5654  5665 D BluetoothMap: onBluetoothStateChange: up=true
11-23 19:15:41.127  3112  3126 D BluetoothMap: onBluetoothStateChange: up=true
,11-23 19:15:41.135  5654  5654 D BluetoothMap: Proxy object connected
11-23 19:15:41.135  5654  5654 D MapProfile: Bluetooth service connected
11-23 19:15:41.135  5654  5654 D BluetoothMap: getConnectedDevices()
,11-23 19:15:41.136  5812  5812 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
11-23 19:15:41.136  5654  5807 D BluetoothHeadset: onBluetoothStateChange: up=true
11-23 19:15:41.136  3112  3112 D BluetoothMap: Proxy object connected
11-23 19:15:41.136  3112  3112 D MapProfile: Bluetooth service connected
11-23 19:15:41.136  3112  3112 D BluetoothMap: getConnectedDevices()
11-23 19:15:41.136  5654  5665 D BluetoothPan: onBluetoothStateChange on: true
11-23 19:15:41.136  5812  5812 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
,11-23 19:15:41.137  5812  5812 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-23 19:15:41.138  3112  3129 D BluetoothPan: onBluetoothStateChange on: true
11-23 19:15:41.139  5812  5812 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-23 19:15:41.140  5654  5671 D BluetoothA2dp: onBluetoothStateChange: up=true
11-23 19:15:41.140  5812  5812 D ObexServerSockets: Succeed to create listening sockets 
11-23 19:15:41.140  5812  5812 D ObexServerSockets0: startAccept()
11-23 19:15:41.140  5812  5812 D ObexServerSockets0: prepareForNewConnect()
11-23 19:15:41.141   929   946 D BluetoothHeadset: onBluetoothStateChange: up=true
11-23 19:15:41.142  3800  3830 D BluetoothHeadset: onBluetoothStateChange: up=true
11-23 19:15:41.142  5654  5807 D BluetoothInputDevice: onBluetoothStateChange: up=true
11-23 19:15:41.143  5812  5812 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
11-23 19:15:41.143  5812  5812 D BluetoothSdpJni: SDP Create record success - handle: 0
11-23 19:15:41.143  5812  5848 D ObexServerSockets0: Accepting socket connection...
,11-23 19:15:41.144  5812  5849 D ObexServerSockets0: Accepting socket connection...
,11-23 19:15:41.145  5654  5671 D BluetoothPbap: onBluetoothStateChange: up=true
11-23 19:15:41.145  3112  3112 D BluetoothPan: BluetoothPAN Proxy object connected
,11-23 19:15:41.145  3112  3112 D PanProfile: Bluetooth service connected
11-23 19:15:41.147  5654  5654 D BluetoothInputDevice: Proxy object connected
11-23 19:15:41.147  5654  5654 D HidProfile: Bluetooth service connected
,11-23 19:15:41.148   929   946 D BluetoothA2dp: onBluetoothStateChange: up=true
11-23 19:15:41.148   929   929 D BluetoothA2dp: Proxy object connected
11-23 19:15:41.148  3112  3947 D BluetoothHeadset: onBluetoothStateChange: up=true
11-23 19:15:41.149  3112  3129 D BluetoothA2dp: onBluetoothStateChange: up=true
11-23 19:15:41.151  3112  3112 D BluetoothA2dp: Proxy object connected
11-23 19:15:41.152   929   929 I Telecom : BluetoothPhoneService: queryPhoneState
11-23 19:15:41.153  5812  5812 D BluetoothMapService: onReceive
11-23 19:15:41.153  5812  5812 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
11-23 19:15:41.153  5812  5812 D BluetoothMapService: STATE_ON
11-23 19:15:41.153  5654  5654 D BluetoothPan: BluetoothPAN Proxy object connected
11-23 19:15:41.154  5654  5654 D PanProfile: Bluetooth service connected
11-23 19:15:41.154  5654  5654 D BluetoothA2dp: Proxy object connected
,11-23 19:15:41.157  5812  5852 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-23 19:15:41.159  5812  5852 D BluetoothSdpJni: sdpCreateSapsRecordNative:
11-23 19:15:41.159  5812  5852 D BluetoothSdpJni: SDP Create record success - handle: 1
,11-23 19:15:41.162  5654  5654 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,11-23 19:15:41.169  3580  3580 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,11-23 19:15:41.175  5654  5654 D DockEventReceiver: finishStartingService: stopping service
11-23 19:15:41.176  3112  3112 D BluetoothPbap: Proxy object connected
11-23 19:15:41.176  3112  3112 D PbapServerProfile: Bluetooth service connected
11-23 19:15:41.176  5654  5654 D BluetoothPbap: Proxy object connected
11-23 19:15:41.177  5654  5654 D PbapServerProfile: Bluetooth service connected
,11-23 19:15:41.184  5812  5812 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,11-23 19:15:41.184  5812  5812 D ObexServerSockets0: prepareForNewConnect()
11-23 19:15:41.186  5812  5856 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-23 19:15:41.201  5812  5860 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-23 19:15:41.203  5812  5860 I BtOppRfcommListener: Accept thread started.
,11-23 19:15:41.225  3112  3947 D BluetoothHeadset: Proxy object connected
,11-23 19:15:41.225  3112  3112 D HeadsetProfile: Bluetooth service connected
11-23 19:15:41.225  3800  3827 D BluetoothHeadset: Proxy object connected
,11-23 19:15:41.226  5654  5671 D BluetoothHeadset: Proxy object connected
11-23 19:15:41.226   929   929 D BluetoothHeadset: Proxy object connected
11-23 19:15:41.226   929   929 D BluetoothHeadset: Proxy object connected
11-23 19:15:41.226   929   929 D BluetoothHeadset: Proxy object connected
,11-23 19:15:41.227  5654  5654 D HeadsetProfile: Bluetooth service connected
,11-23 19:15:41.236  5654  5807 D BluetoothHeadset: Proxy object connected
,11-23 19:15:41.237  5654  5654 D HeadsetProfile: Bluetooth service connected
,11-23 19:15:41.242   929   946 D BluetoothHeadset: Proxy object connected
,11-23 19:15:41.242  3800  3980 D BluetoothHeadset: Proxy object connected
,11-23 19:15:41.249  3112  3129 D BluetoothHeadset: Proxy object connected
,11-23 19:15:41.249  3112  3112 D HeadsetProfile: Bluetooth service connected
,11-23 19:15:44.947  5588  5634 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-23 19:15:44.947  5588  5634 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-23 19:15:44.947  5588  5634 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-23 19:15:44.947  5588  5634 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-23 19:15:44.947  5588  5634 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-23 19:15:44.947  5588  5634 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-23 19:15:44.947  5588  5634 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-23 19:15:44.947  5588  5634 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-23 19:15:44.947  5588  5634 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,11-23 19:15:44.952  5588  5634 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
,11-23 19:15:44.953  5588  5634 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 19:15:44.953  5588  5634 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@3ecd0 removed from the list
11-23 19:15:44.953  5588  5634 D io.jxcore.node.ConnectivityMonitor: stop
11-23 19:15:44.956  5588  5634 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-23 19:15:44.956  5588  5634 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@cb364c9 added. We now have 4 listener(s)
11-23 19:15:44.956  5588  5634 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-23 19:15:44.959   929  3555 D WifiService: setWifiEnabled: false pid=5588, uid=10077
11-23 19:15:44.959   929  3555 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-23 19:15:46.804   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 19:15:47.807   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 19:15:48.808   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 19:15:49.810   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 19:15:49.970  5588  5634 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-23 19:15:49.971   929  3158 D WifiService: setWifiEnabled: true pid=5588, uid=10077
11-23 19:15:49.972   929  3158 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-23 19:15:49.984   508   913 D SoftapController: Softap fwReload - Ok
,11-23 19:15:49.990   508   913 D CommandListener: Setting iface cfg
,11-23 19:15:49.990   508   913 D CommandListener: Trying to bring down wlan0
11-23 19:15:49.993   508   913 D CommandListener: Clearing all IP addresses on wlan0
,11-23 19:15:49.998   929  2970 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,11-23 19:15:50.667   929  2970 D wifi    : set interface wlan0 flags (UP)
,11-23 19:15:50.672   929  2970 I WifiHAL : Initializing wifi
11-23 19:15:50.672   929  2970 I WifiHAL : Creating socket
,11-23 19:15:50.677   929   946 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,11-23 19:15:50.681   929  2970 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
11-23 19:15:50.681   929  2970 D wifi    : Did set static halHandle = 0x7f7e088180
,11-23 19:15:50.681   929  2970 D wifi    : halHandle = 0x7f7e088180, mVM = 0x7f9a68d140, mCls = 0x201886
11-23 19:15:50.682   929  2970 D wifi    : array field set
11-23 19:15:50.682   929  2970 I WifiNative-HAL: interface[0] = wlan0
11-23 19:15:50.685   929  5865 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=547575333248
11-23 19:15:50.685   929  5865 D wifi    : waitForHalEvents called, vm = 0x7f9a68d140, obj = 0x201886, env = 0x7f830f2440
,11-23 19:15:50.740  5866  5866 I wpa_supplicant: Successfully initialized wpa_supplicant
,11-23 19:15:50.786   929  2970 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,11-23 19:15:50.787   929  2970 E WifiHW  : Unable to open connection to supplicant on "@android:wpa_wlan0": No such file or directory
,11-23 19:15:50.810   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 19:15:50.816  5866  5866 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,11-23 19:15:50.869  5866  5866 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,11-23 19:15:50.869  5866  5866 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,11-23 19:15:51.801   929  2970 D WifiConfigStore: Loading config and enabling all networks 
,11-23 19:15:51.811   536   536 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,11-23 19:15:51.847   929  2970 D WifiConfigStore: loaded 0 passpoint configs
,11-23 19:15:51.848   929  2970 W WifiConfigStore: Upgrading network 4 to android.uid.system:1000
11-23 19:15:51.849   929  2970 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
11-23 19:15:51.850   929  2970 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,11-23 19:15:51.851   929  2970 W WifiConfigStore: Upgrading network 3 to android.uid.system:1000
,11-23 19:15:51.852   929  2970 W WifiConfigStore: Upgrading network 2 to android.uid.system:1000
11-23 19:15:51.854   929  2970 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
11-23 19:15:51.854   929  2970 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 5
11-23 19:15:51.854   929  2970 E WifiConfigStore: found sortedWifiConfigurations : "AndroidAP"WPA_PSK
11-23 19:15:51.854   929  2970 E WifiConfigStore: found sortedWifiConfigurations : "AndroidHotspot2346"WPA_PSK
11-23 19:15:51.854   929  2970 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
11-23 19:15:51.854   929  2970 E WifiConfigStore: found sortedWifiConfigurations : "Thali_internal"WPA_PSK
11-23 19:15:51.855   929  2970 E WifiConfigStore: found sortedWifiConfigurations : "MC"WPA_PSK
,11-23 19:15:51.859   929  2970 D WifiNative-HAL: Setting external_sim to 1
,11-23 19:15:51.859  4996  4996 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,11-23 19:15:51.860   929  2970 D wifi    : setting dfs flag to true, 0x7f7ef55ae0
11-23 19:15:51.861   929  2970 D WifiStateMachine: Setting OUI to DA-A1-19
,11-23 19:15:51.862   929  2970 D wifi    : setting scan oui 0x7f7ef55ae0
11-23 19:15:51.862   929  2970 D WifiHAL : Sending mac address OUI
,11-23 19:15:51.868   929  2970 E native  : do suspend false
,11-23 19:15:51.880   929  2970 D wifi    : android_net_wifi_setLinkLayerStats: 1
,11-23 19:15:51.880   508   913 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
11-23 19:15:51.880   929   929 D RttService: SCAN_AVAILABLE : 3
11-23 19:15:51.880   929  3079 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
11-23 19:15:51.881   508   913 D CommandListener: Setting iface cfg
,11-23 19:15:51.887   929  2969 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '158 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 158 Failed to set address (No such device)'
11-23 19:15:51.887   929  2969 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,11-23 19:15:51.899   929  2969 D WifiNative-HAL: p2pGetDeviceAddress
,11-23 19:15:51.900   929  2969 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:70
,11-23 19:15:51.908   929   944 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=259412 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=21 mControllerEnergyUsed=79 }
,11-23 19:15:54.978  5866  5866 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-23 19:15:54.982  5866  5866 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-23 19:15:54.987  5866  5866 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-23 19:15:54.992  5866  5866 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-23 19:15:54.994  5588  5634 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-23 19:15:54.994  5588  5634 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-23 19:15:54.994  5588  5634 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-23 19:15:54.994  5588  5634 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-23 19:15:54.994  5588  5634 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-23 19:15:54.994  5588  5634 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-23 19:15:54.994  5588  5634 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-23 19:15:54.994  5588  5634 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-23 19:15:54.994  5588  5634 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,11-23 19:15:54.997  5588  5634 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
,11-23 19:15:54.998  5588  5634 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 19:15:54.998  5588  5634 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@cb364c9 removed from the list
11-23 19:15:54.998  5588  5634 D io.jxcore.node.ConnectivityMonitor: stop
11-23 19:15:55.002  5588  5634 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
11-23 19:15:55.003  5588  5634 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
11-23 19:15:55.005  5588  5634 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@5b115cd Bundle[{}]
,11-23 19:15:55.006  5588  5634 I io.jxcore.node.LifeCycleMonitor: start: OK
,11-23 19:15:55.006  5588  5634 I io.jxcore.node.LifeCycleMonitor: stop: OK
11-23 19:15:55.007  5588  5634 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
11-23 19:15:55.008  5588  5634 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
11-23 19:15:55.008  5588  5634 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
11-23 19:15:55.009  5588  5634 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,11-23 19:15:55.025  5588  5634 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 168)
,11-23 19:15:55.026  5588  5634 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
11-23 19:15:55.026  5588  5634 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 169)
,11-23 19:15:55.029  5588  5634 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,11-23 19:15:55.029  5588  5634 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d8d57ce added. We now have 3 listener(s)
11-23 19:15:55.030  5588  5634 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-23 19:15:55.030  5588  5634 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-23 19:15:55.030  5588  5634 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-23 19:15:55.030  5588  5634 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-23 19:15:55.031  5588  5634 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d4356ef added. We now have 4 listener(s)
,11-23 19:15:55.031  5588  5634 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-23 19:15:55.031  5588  5634 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,11-23 19:15:55.033  5588  5634 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-23 19:15:55.034  5588  5634 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@60305fc added. We now have 4 listener(s)
11-23 19:15:55.035  5588  5634 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-23 19:15:55.035  5588  5634 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-23 19:15:55.035  5588  5634 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-23 19:15:55.035  5588  5634 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-23 19:15:55.036  5588  5634 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8048485 added. We now have 5 listener(s)
11-23 19:15:55.036  5588  5634 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-23 19:15:55.036  5588  5634 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-23 19:15:55.036  5588  5634 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-23 19:15:55.036  5588  5634 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-23 19:15:55.036  5588  5634 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-23 19:15:55.036  5588  5634 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-23 19:15:55.036  5588  5634 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-23 19:15:55.036  5588  5634 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d8d57ce removed from the list
11-23 19:15:55.036  5588  5634 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 19:15:55.036  5588  5634 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d4356ef removed from the list
11-23 19:15:55.036  5588  5634 D io.jxcore.node.ConnectivityMonitor: stop
11-23 19:15:55.036  5588  5634 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-23 19:15:55.037  5588  5634 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-23 19:15:55.039  5588  5634 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-23 19:15:55.039  5588  5634 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 19:15:55.039  5588  5634 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 19:15:55.039  5588  5634 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-23 19:15:55.039  5588  5634 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-23 19:15:55.039  5588  5634 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 19:15:55.039  5588  5634 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d4356ef not in the list
11-23 19:15:55.039  5588  5634 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-23 19:15:55.039  5588  5634 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-23 19:15:55.041  5588  5634 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-23 19:15:55.041  5588  5634 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 19:15:55.041  5588  5634 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
,11-23 19:15:55.041  5588  5634 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-23 19:15:55.041   929  2970 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
11-23 19:15:55.041  5588  5634 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-23 19:15:55.041  5588  5634 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 19:15:55.041  5588  5634 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8048485 removed from the list
11-23 19:15:55.041  5588  5634 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-23 19:15:55.042  5588  5634 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-23 19:15:55.042  5588  5634 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-23 19:15:55.042  5588  5634 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@60305fc removed from the list
11-23 19:15:55.042   929  2970 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3
11-23 19:15:55.043   929  2970 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
11-23 19:15:55.043  5588  5634 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-23 19:15:55.043  5588  5634 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e2b22da added. We now have 3 listener(s)
11-23 19:15:55.044  5588  5634 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
,11-23 19:15:55.045  5588  5634 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-23 19:15:55.045  5588  5634 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-23 19:15:55.046  5588  5634 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-23 19:15:55.046  5588  5634 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b98730b added. We now have 4 listener(s)
11-23 19:15:55.046  5588  5634 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-23 19:15:55.048  5588  5634 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,11-23 19:15:55.050  5588  5634 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,11-23 19:15:55.050  5588  5634 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@87885e8 added. We now have 4 listener(s)
,11-23 19:15:55.052  5588  5634 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
,11-23 19:15:55.052   929  2970 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=0
11-23 19:15:55.052  5588  5634 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-23 19:15:55.052  5588  5634 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-23 19:15:55.052  5588  5634 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-23 19:15:55.053  5588  5634 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d8de401 added. We now have 5 listener(s)
11-23 19:15:55.053  5588  5634 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-23 19:15:55.053  5588  5634 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-23 19:15:55.053  5588  5634 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
11-23 19:15:55.053  5588  5634 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
11-23 19:15:55.053  5588  5634 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-23 19:15:55.053  5588  5634 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
11-23 19:15:55.055  5588  5634 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,11-23 19:15:55.059  5588  5634 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-23 19:15:55.059  5588  5634 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,11-23 19:15:55.059  5588  5634 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
11-23 19:15:55.062  5588  5634 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-61,5,main], id: 61
11-23 19:15:55.062  5588  5634 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-23 19:15:55.062  5588  5634 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-23 19:15:55.063  5588  5634 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-23 19:15:55.063  5588  5634 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 0
11-23 19:15:55.065  5588  5634 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-23 19:15:55.065  5588  5634 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
11-23 19:15:55.065  5588  5634 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
11-23 19:15:55.065  5588  5634 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
11-23 19:15:55.065  5588  5634 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
11-23 19:15:55.065  5588  5634 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-61,5,main], id: 61
11-23 19:15:55.066  5588  5634 D BluetoothAdapter: STATE_ON
,11-23 19:15:55.069  5812  5823 D BtGatt.GattService: registerClient() - UUID=e6155a46-fbcd-49e2-9d6b-1f34e8e372e2
,11-23 19:15:55.070  5812  5828 D BtGatt.GattService: onClientRegistered() - UUID=e6155a46-fbcd-49e2-9d6b-1f34e8e372e2, clientIf=5
,11-23 19:15:55.071  5588  5598 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
11-23 19:15:55.071  5812  5822 D BtGatt.GattService: start scan with filters
11-23 19:15:55.075  5588  5634 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
,11-23 19:15:55.075  5588  5634 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-23 19:15:55.075  5588  5634 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
11-23 19:15:55.075  5812  5832 D BtGatt.ScanManager: handling starting scan
11-23 19:15:55.075  5588  5634 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-61,5,main], id: 61
11-23 19:15:55.075  5588  5634 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-23 19:15:55.075  5588  5588 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-23 19:15:55.075  5588  5588 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-23 19:15:55.075  5588  5588 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
11-23 19:15:55.076  5588  5588 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-23 19:15:55.076  5588  5588 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-23 19:15:55.076  5588  5588 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
,11-23 19:15:55.076  5588  5588 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-23 19:15:55.076  5588  5588 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING] Current thread: Thread[main,5,main], id: 1
11-23 19:15:55.077  5588  5634 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-23 19:15:55.077  5588  5634 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-23 19:15:55.077  5812  5832 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f8a38f6
11-23 19:15:55.079  5588  5634 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-23 19:15:55.080  5588  5634 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
11-23 19:15:55.080  5588  5634 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 19:15:55.080  5588  5634 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 19:15:55.080  5588  5634 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
11-23 19:15:55.080  5588  5588 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
,11-23 19:15:55.080  5588  5634 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
11-23 19:15:55.080  5588  5634 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
11-23 19:15:55.080  5588  5634 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-23 19:15:55.080  5588  5634 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-23 19:15:55.080  5588  5634 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-23 19:15:55.080  5588  5634 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,11-23 19:15:55.084  5812  5828 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
11-23 19:15:55.084  5812  5828 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-23 19:15:55.085  5812  5832 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
11-23 19:15:55.085  5588  5588 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-23 19:15:55.085  5588  5588 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-23 19:15:55.086  5588  5588 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-23 19:15:55.086  5588  5588 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
11-23 19:15:55.086  5588  5634 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-23 19:15:55.086  5588  5634 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-23 19:15:55.086  5588  5634 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
11-23 19:15:55.086  5588  5634 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-23 19:15:55.086  5588  5634 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
11-23 19:15:55.086  5588  5634 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-61,5,main], id: 61
11-23 19:15:55.086  5588  5634 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-23 19:15:55.086  5588  5634 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
11-23 19:15:55.087  5588  5634 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-61,5,main], id: 61
,11-23 19:15:55.088  5588  5634 D BluetoothAdapter: STATE_ON
11-23 19:15:55.088  5812  5823 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
,11-23 19:15:55.088  5588  5634 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-23 19:15:55.089  5588  5634 D BluetoothAdapter: STATE_ON
11-23 19:15:55.090  5812  5851 D BtGatt.GattService: stopScan() - queue size =1
,11-23 19:15:55.090  5812  5850 D BtGatt.GattService: unregisterClient() - clientIf=5
,11-23 19:15:55.091   929  2970 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=0
11-23 19:15:55.091  5812  5828 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
,11-23 19:15:55.091  5812  5828 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-23 19:15:55.091  5588  5634 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-23 19:15:55.091  5588  5634 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-23 19:15:55.091  5588  5634 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
11-23 19:15:55.091  5588  5634 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-61,5,main], id: 61
11-23 19:15:55.091  5588  5634 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-61,5,main], id: 61
11-23 19:15:55.091  5812  5832 D BtGatt.ScanManager: Starting BLE batch scan
11-23 19:15:55.091  5588  5634 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-61,5,main], id: 61
11-23 19:15:55.091  5588  5634 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-61,5,main], id: 61
11-23 19:15:55.091  5812  5832 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
11-23 19:15:55.091  5588  5634 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-23 19:15:55.091  5588  5634 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
11-23 19:15:55.091  5588  5634 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 19:15:55.092  5588  5634 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-61,5,main], id: 61
,11-23 19:15:55.092  5588  5634 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-23 19:15:55.092  5588  5634 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-23 19:15:55.096  5588  5634 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
11-23 19:15:55.096  5588  5634 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-23 19:15:55.097  5588  5634 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-23 19:15:55.097  5588  5634 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-23 19:15:55.097  5588  5634 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 19:15:55.097  5588  5634 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 19:15:55.097  5588  5588 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-23 19:15:55.097  5866  5866 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
11-23 19:15:55.097  5588  5588 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-23 19:15:55.098  5588  5588 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-23 19:15:55.098  5588  5588 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-23 19:15:55.098  5588  5588 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
,11-23 19:15:55.098  5588  5588 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
11-23 19:15:55.098  5588  5588 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-23 19:15:55.098  5588  5588 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-23 19:15:55.098  5588  5588 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-23 19:15:55.098  5588  5588 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-23 19:15:55.098  5588  5588 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED] Current thread: Thread[main,5,main], id: 1
11-23 19:15:55.098  5588  5588 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-23 19:15:55.101  5588  5588 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-23 19:15:55.101  5588  5588 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-23 19:15:55.101  5588  5588 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-23 19:15:55.102  5588  5634 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-23 19:15:55.102  5588  5634 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-23 19:15:55.102  5588  5634 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-23 19:15:55.102  5588  5634 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-23 19:15:55.102  5588  5634 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-23 19:15:55.102  5588  5634 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-23 19:15:55.102  5588  5634 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e2b22da removed from the list
11-23 19:15:55.102  5588  5634 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-23 19:15:55.102  5588  5634 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b98730b removed from the list
11-23 19:15:55.102  5588  5634 D io.jxcore.node.ConnectivityMonitor: stop
11-23 19:15:55.102  5588  5634 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-23 19:15:55.102  5588  5634 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-23 19:15:55.103  5812  5828 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
11-23 19:15:55.103  5812  5828 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-23 19:15:55.103  5588  5634 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-23 19:15:55.103  5588  5634 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 19:15:55.103  5588  5634 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 19:15:55.103  5588  5634 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-23 19:15:55.103  5588  5634 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-23 19:15:55.104  5588  5634 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 19:15:55.104  5588  5634 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b98730b not in the list
11-23 19:15:55.104  5588  5634 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-23 19:15:55.104  5588  5634 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-23 19:15:55.105  5588  5634 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-23 19:15:55.105  5588  5634 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
,11-23 19:15:55.105  5588  5634 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 19:15:55.105  5588  5634 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-23 19:15:55.105  5588  5634 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-23 19:15:55.105  5588  5634 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 19:15:55.105  5588  5634 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d8de401 removed from the list
11-23 19:15:55.105  5588  5634 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-23 19:15:55.105  5588  5634 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-23 19:15:55.105  5588  5634 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-23 19:15:55.105  5588  5634 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@87885e8 removed from the list
11-23 19:15:55.106  5588  5634 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-23 19:15:55.106  5588  5634 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3b3332 added. We now have 3 listener(s)
11-23 19:15:55.108  5588  5634 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-23 19:15:55.108  5588  5634 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-23 19:15:55.108  5588  5634 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-23 19:15:55.108  5812  5828 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,11-23 19:15:55.108  5588  5634 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-23 19:15:55.108  5812  5828 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-23 19:15:55.108  5588  5634 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d7a3883 added. We now have 4 listener(s)
11-23 19:15:55.108  5588  5634 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-23 19:15:55.109  5588  5634 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
11-23 19:15:55.110  5812  5832 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
11-23 19:15:55.110  5588  5634 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-23 19:15:55.110  5588  5634 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2942a00 added. We now have 4 listener(s)
,11-23 19:15:55.113  5588  5634 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-23 19:15:55.113  5588  5634 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-23 19:15:55.113  5588  5634 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,11-23 19:15:55.113  5588  5634 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-23 19:15:55.113  5588  5634 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9e21239 added. We now have 5 listener(s)
11-23 19:15:55.113  5588  5634 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-23 19:15:55.113  5588  5634 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-23 19:15:55.114  5588  5634 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-23 19:15:55.114  5588  5634 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
11-23 19:15:55.114  5588  5634 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
11-23 19:15:55.114  5588  5634 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-23 19:15:55.114  5588  5634 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
,11-23 19:15:55.115  5812  5828 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,11-23 19:15:55.115  5812  5828 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-23 19:15:55.115  5812  5828 E BtGatt.ContextMap: Context not found for ID 5
11-23 19:15:55.116  5588  5634 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,11-23 19:15:55.118  5588  5634 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
,11-23 19:15:55.118  5588  5634 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-23 19:15:55.118  5588  5634 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,11-23 19:15:55.121  5588  5634 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-61,5,main], id: 61
11-23 19:15:55.121  5588  5634 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-23 19:15:55.121  5588  5634 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-23 19:15:55.121  5588  5634 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-23 19:15:55.121  5588  5634 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 0
11-23 19:15:55.122  5812  5828 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
11-23 19:15:55.122  5812  5828 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-23 19:15:55.122  5812  5832 D BtGatt.ScanManager: stopping BLe Batch
,11-23 19:15:55.124  5588  5634 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-61,5,main], id: 61
,11-23 19:15:55.124  5588  5634 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
11-23 19:15:55.124  5588  5634 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
11-23 19:15:55.124  5588  5634 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
11-23 19:15:55.124  5588  5634 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
11-23 19:15:55.124  5588  5634 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-61,5,main], id: 61
11-23 19:15:55.125  5588  5634 D BluetoothAdapter: STATE_ON
,11-23 19:15:55.127  5812  5829 D BtGatt.GattService: registerClient() - UUID=615165ac-a9de-45bf-8bd9-0bb186433860
11-23 19:15:55.127  5812  5828 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
11-23 19:15:55.127  5812  5828 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-23 19:15:55.127  5812  5832 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
11-23 19:15:55.127  5812  5828 D BtGatt.GattService: onClientRegistered() - UUID=615165ac-a9de-45bf-8bd9-0bb186433860, clientIf=5
,11-23 19:15:55.128  5588  5599 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
11-23 19:15:55.128  5812  5851 D BtGatt.GattService: start scan with filters
,11-23 19:15:55.130  5588  5634 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
,11-23 19:15:55.130  5588  5634 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-23 19:15:55.130  5588  5634 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
11-23 19:15:55.130  5588  5634 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-61,5,main], id: 61
11-23 19:15:55.130  5588  5634 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-23 19:15:55.130  5588  5588 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-23 19:15:55.130  5588  5588 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-23 19:15:55.131  5588  5588 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
11-23 19:15:55.131  5588  5588 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-23 19:15:55.131  5588  5588 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-23 19:15:55.131  5588  5588 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
11-23 19:15:55.131  5588  5588 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-23 19:15:55.131  5588  5588 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING] Current thread: Thread[main,5,main], id: 1
11-23 19:15:55.131  5588  5634 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-23 19:15:55.132  5588  5634 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-23 19:15:55.132  5812  5828 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,11-23 19:15:55.132  5812  5828 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-23 19:15:55.134  5588  5634 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-23 19:15:55.134  5588  5634 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
11-23 19:15:55.134  5588  5634 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 19:15:55.134  5588  5634 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 19:15:55.134  5588  5588 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-23 19:15:55.134  5588  5634 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,11-23 19:15:55.136  5588  5588 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-23 19:15:55.145  5588  5588 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
,11-23 19:15:55.145  5588  5588 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-23 19:15:55.145  5588  5588 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
11-23 19:15:55.134  5588  5634 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
11-23 19:15:55.146  5588  5634 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-23 19:15:55.146  5588  5634 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-23 19:15:55.146  5588  5634 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-23 19:15:55.146  5812  5832 D BtGatt.ScanManager: handling starting scan
11-23 19:15:55.146  5588  5634 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-23 19:15:55.146  5588  5634 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-23 19:15:55.146  5588  5634 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-23 19:15:55.147  5588  5634 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-23 19:15:55.147  5588  5634 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-23 19:15:55.147  5588  5634 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3b3332 removed from the list
11-23 19:15:55.147  5588  5634 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 19:15:55.147  5588  5634 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d7a3883 removed from the list
11-23 19:15:55.147  5588  5634 D io.jxcore.node.ConnectivityMonitor: stop
11-23 19:15:55.147  5588  5634 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,11-23 19:15:55.147  5588  5634 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-23 19:15:55.147  5588  5634 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-23 19:15:55.147  5588  5634 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
11-23 19:15:55.147  5588  5634 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
11-23 19:15:55.148  5588  5634 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-23 19:15:55.148  5588  5634 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-23 19:15:55.148  5588  5634 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-23 19:15:55.149  5588  5634 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-23 19:15:55.149  5588  5634 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 19:15:55.149  5588  5634 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 19:15:55.149  5588  5634 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-23 19:15:55.149  5588  5634 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-23 19:15:55.149  5588  5634 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 19:15:55.150  5588  5634 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d7a3883 not in the list
11-23 19:15:55.150  5588  5634 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-23 19:15:55.150  5588  5634 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-23 19:15:55.150  5588  5634 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
,11-23 19:15:55.150  5588  5634 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-23 19:15:55.150  5588  5634 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
11-23 19:15:55.150  5588  5634 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-61,5,main], id: 61
11-23 19:15:55.150  5588  5634 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-23 19:15:55.150  5588  5634 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
11-23 19:15:55.151  5588  5634 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-61,5,main], id: 61
,11-23 19:15:55.151  5588  5634 D BluetoothAdapter: STATE_ON
11-23 19:15:55.152  5812  5850 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
11-23 19:15:55.152  5588  5634 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
,11-23 19:15:55.152  5812  5828 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
11-23 19:15:55.152  5812  5828 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-23 19:15:55.152  5812  5832 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
11-23 19:15:55.153  5588  5634 D BluetoothAdapter: STATE_ON
11-23 19:15:55.153  5812  5822 D BtGatt.GattService: stopScan() - queue size =1
,11-23 19:15:55.154  5812  5829 D BtGatt.GattService: unregisterClient() - clientIf=5
11-23 19:15:55.154  5588  5634 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-23 19:15:55.154  5588  5634 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-23 19:15:55.154  5588  5634 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
11-23 19:15:55.154  5588  5634 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-61,5,main], id: 61
11-23 19:15:55.155  5588  5634 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-61,5,main], id: 61
11-23 19:15:55.155  5588  5634 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-61,5,main], id: 61
11-23 19:15:55.155  5588  5634 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-61,5,main], id: 61
,11-23 19:15:55.155  5588  5634 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-23 19:15:55.155  5588  5634 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
11-23 19:15:55.155  5588  5634 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 19:15:55.155  5588  5634 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-61,5,main], id: 61
11-23 19:15:55.155  5588  5634 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-23 19:15:55.155  5588  5634 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-23 19:15:55.156  5588  5634 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
,11-23 19:15:55.156  5588  5634 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-23 19:15:55.158  5588  5634 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-23 19:15:55.158  5588  5634 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-23 19:15:55.158  5588  5634 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 19:15:55.158  5588  5634 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 19:15:55.158  5588  5634 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-23 19:15:55.158  5588  5634 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-23 19:15:55.158  5588  5634 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 19:15:55.158  5588  5634 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9e21239 removed from the list
,11-23 19:15:55.159  5588  5634 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-23 19:15:55.159  5588  5634 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,11-23 19:15:55.159  5588  5634 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-23 19:15:55.159  5588  5634 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2942a00 removed from the list
11-23 19:15:55.159  5588  5588 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-23 19:15:55.159  5588  5588 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-23 19:15:55.159  5588  5588 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-23 19:15:55.159  5588  5588 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-23 19:15:55.159  5588  5588 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-23 19:15:55.159  5588  5588 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
11-23 19:15:55.159  5588  5588 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-23 19:15:55.159  5588  5634 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-23 19:15:55.160  5588  5588 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-23 19:15:55.160  5588  5634 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@681f68a added. We now have 3 listener(s)
11-23 19:15:55.160  5588  5588 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-23 19:15:55.160  5812  5828 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
11-23 19:15:55.160  5588  5588 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,11-23 19:15:55.160  5812  5828 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-23 19:15:55.160  5588  5588 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED] Current thread: Thread[main,5,main], id: 1
11-23 19:15:55.160  5588  5588 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-23 19:15:55.160  5812  5832 D BtGatt.ScanManager: Starting BLE batch scan
11-23 19:15:55.160  5812  5832 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
11-23 19:15:55.161  5588  5588 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-23 19:15:55.161  5588  5588 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-23 19:15:55.161  5588  5634 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-23 19:15:55.161  5588  5588 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-23 19:15:55.161  5588  5634 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-23 19:15:55.161  5588  5634 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-23 19:15:55.161  5588  5634 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-23 19:15:55.162  5588  5634 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@73034fb added. We now have 4 listener(s)
11-23 19:15:55.162  5588  5634 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-23 19:15:55.162  5588  5634 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,11-23 19:15:55.165  5588  5634 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,11-23 19:15:55.165  5588  5634 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4cd3918 added. We now have 4 listener(s)
,11-23 19:15:55.167  5588  5634 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-23 19:15:55.167  5588  5634 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-23 19:15:55.167  5588  5634 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-23 19:15:55.167  5588  5634 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-23 19:15:55.167  5588  5634 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@356cf71 added. We now have 5 listener(s)
11-23 19:15:55.167  5588  5634 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-23 19:15:55.167  5588  5634 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-23 19:15:55.167  5588  5634 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
11-23 19:15:55.167  5588  5634 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
11-23 19:15:55.167  5588  5634 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-23 19:15:55.167  5588  5634 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
,11-23 19:15:55.169  5588  5634 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,11-23 19:15:55.170  5812  5828 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
11-23 19:15:55.170  5812  5828 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-23 19:15:55.171  5588  5634 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-23 19:15:55.171  5588  5634 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-23 19:15:55.171  5588  5634 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,11-23 19:15:55.173  5812  5828 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,11-23 19:15:55.174  5812  5828 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-23 19:15:55.174  5588  5634 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-61,5,main], id: 61
11-23 19:15:55.174  5588  5634 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,11-23 19:15:55.174  5588  5634 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-23 19:15:55.174  5812  5832 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
11-23 19:15:55.175  5588  5634 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-23 19:15:55.175  5588  5634 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 0
,11-23 19:15:55.178  5812  5828 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,11-23 19:15:55.178  5812  5828 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-23 19:15:55.178  5812  5828 E BtGatt.ContextMap: Context not found for ID 5
,11-23 19:15:55.179  5588  5634 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-23 19:15:55.179  5588  5634 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
11-23 19:15:55.179  5588  5634 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
11-23 19:15:55.179  5588  5634 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
11-23 19:15:55.180  5588  5634 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
11-23 19:15:55.180  5588  5634 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-61,5,main], id: 61
,11-23 19:15:55.180  5588  5634 D BluetoothAdapter: STATE_ON
11-23 19:15:55.182  5812  5850 D BtGatt.GattService: registerClient() - UUID=887514a9-41a8-43b0-969b-5687c9c9e48d
,11-23 19:15:55.183  5812  5828 D BtGatt.GattService: onClientRegistered() - UUID=887514a9-41a8-43b0-969b-5687c9c9e48d, clientIf=5
11-23 19:15:55.183  5588  5599 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
11-23 19:15:55.183  5812  5828 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
11-23 19:15:55.183  5812  5851 D BtGatt.GattService: start scan with filters
11-23 19:15:55.183  5812  5828 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-23 19:15:55.183  5812  5832 D BtGatt.ScanManager: stopping BLe Batch
,11-23 19:15:55.185  5588  5634 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
,11-23 19:15:55.186  5588  5634 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-23 19:15:55.186  5588  5634 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
11-23 19:15:55.186  5588  5634 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-61,5,main], id: 61
11-23 19:15:55.186  5588  5634 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-23 19:15:55.186  5588  5588 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-23 19:15:55.186  5588  5588 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-23 19:15:55.186  5588  5588 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
11-23 19:15:55.186  5588  5588 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-23 19:15:55.186  5588  5588 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-23 19:15:55.186  5588  5588 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
11-23 19:15:55.186  5588  5588 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
,11-23 19:15:55.186  5588  5588 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING] Current thread: Thread[main,5,main], id: 1
11-23 19:15:55.187  5588  5634 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-23 19:15:55.187  5588  5634 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-23 19:15:55.187  5812  5828 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
11-23 19:15:55.187  5812  5828 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-23 19:15:55.187  5812  5832 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
11-23 19:15:55.189  5588  5634 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-23 19:15:55.189  5588  5634 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
11-23 19:15:55.189  5588  5634 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 19:15:55.189  5588  5634 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 19:15:55.190  5588  5588 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-23 19:15:55.191  5812  5828 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-23 19:15:55.191  5812  5828 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-23 19:15:55.192  5588  5588 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
,11-23 19:15:55.192  5588  5588 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-23 19:15:55.193  5588  5588 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-23 19:15:55.193  5588  5588 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
11-23 19:15:55.193  5812  5832 D BtGatt.ScanManager: handling starting scan
11-23 19:15:55.193  5588  5634 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-23 19:15:55.193  5588  5634 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-23 19:15:55.193  5588  5634 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-23 19:15:55.193  5588  5634 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-23 19:15:55.193  5588  5634 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-23 19:15:55.193  5588  5634 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-23 19:15:55.193  5588  5634 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-23 19:15:55.193  5588  5634 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,11-23 19:15:55.193  5588  5634 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@681f68a removed from the list
11-23 19:15:55.193  5588  5634 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 19:15:55.193  5588  5634 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@73034fb removed from the list
11-23 19:15:55.193  5588  5634 D io.jxcore.node.ConnectivityMonitor: stop
11-23 19:15:55.193  5588  5634 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-23 19:15:55.193  5588  5634 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-23 19:15:55.193  5588  5634 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-23 19:15:55.194  5588  5634 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
11-23 19:15:55.194  5588  5634 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
11-23 19:15:55.194  5588  5634 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-23 19:15:55.194  5588  5634 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-23 19:15:55.194  5588  5634 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-23 19:15:55.194  5588  5634 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
,11-23 19:15:55.194  5588  5634 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 19:15:55.195  5588  5634 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 19:15:55.195  5588  5634 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-23 19:15:55.195  5588  5634 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-23 19:15:55.195  5588  5634 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 19:15:55.195  5588  5634 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@73034fb not in the list
11-23 19:15:55.195  5588  5634 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-23 19:15:55.195  5588  5634 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-23 19:15:55.195  5588  5634 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
11-23 19:15:55.195  5588  5634 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-23 19:15:55.195  5588  5634 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
11-23 19:15:55.195  5588  5634 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-61,5,main], id: 61
11-23 19:15:55.195  5588  5634 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-61,5,main], id: 61
,11-23 19:15:55.195  5588  5634 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
11-23 19:15:55.195  5588  5634 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-61,5,main], id: 61
11-23 19:15:55.196  5588  5634 D BluetoothAdapter: STATE_ON
11-23 19:15:55.196  5812  5851 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
11-23 19:15:55.197  5588  5634 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-23 19:15:55.197  5812  5828 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
11-23 19:15:55.197  5812  5828 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-23 19:15:55.197  5588  5634 D BluetoothAdapter: STATE_ON
11-23 19:15:55.197  5812  5832 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
11-23 19:15:55.197  5812  5829 D BtGatt.GattService: stopScan() - queue size =1
11-23 19:15:55.198  5812  5822 D BtGatt.GattService: unregisterClient() - clientIf=5
11-23 19:15:55.198  5588  5634 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-23 19:15:55.198  5588  5634 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-23 19:15:55.198  5588  5634 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,11-23 19:15:55.198  5588  5634 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-61,5,main], id: 61
11-23 19:15:55.199  5588  5634 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-61,5,main], id: 61
11-23 19:15:55.199  5588  5634 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-61,5,main], id: 61
11-23 19:15:55.199  5588  5634 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-61,5,main], id: 61
11-23 19:15:55.199  5588  5634 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-23 19:15:55.199  5588  5634 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
11-23 19:15:55.199  5588  5634 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 19:15:55.199  5588  5634 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-61,5,main], id: 61
11-23 19:15:55.199  5588  5634 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-23 19:15:55.199  5588  5634 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-23 19:15:55.199  5588  5634 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
11-23 19:15:55.201  5588  5634 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-23 19:15:55.201  5812  5828 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
11-23 19:15:55.201  5812  5828 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-23 19:15:55.201  5812  5832 D BtGatt.ScanManager: Starting BLE batch scan
11-23 19:15:55.201  5812  5832 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
11-23 19:15:55.201  5588  5634 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-23 19:15:55.202  5588  5634 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,11-23 19:15:55.202  5588  5634 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 19:15:55.202  5588  5634 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 19:15:55.202  5588  5634 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-23 19:15:55.202  5588  5634 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-23 19:15:55.202  5588  5634 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-23 19:15:55.202  5588  5588 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-23 19:15:55.202  5588  5634 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@356cf71 removed from the list
11-23 19:15:55.202  5588  5634 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-23 19:15:55.202  5588  5588 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-23 19:15:55.202  5588  5634 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-23 19:15:55.202  5588  5634 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-23 19:15:55.202  5588  5588 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-23 19:15:55.202  5588  5634 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4cd3918 removed from the list
11-23 19:15:55.202  5588  5588 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-23 19:15:55.202  5588  5588 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-23 19:15:55.202  5588  5588 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
11-23 19:15:55.202  5588  5588 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-23 19:15:55.202  5588  5588 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-23 19:15:55.202  5588  5588 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-23 19:15:55.203  5588  5588 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-23 19:15:55.203  5588  5588 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED] Current thread: Thread[main,5,main], id: 1
,11-23 19:15:55.203  5588  5588 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-23 19:15:55.203  5588  5634 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-23 19:15:55.203  5588  5634 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4c2cce2 added. We now have 3 listener(s)
11-23 19:15:55.204  5588  5588 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-23 19:15:55.204  5588  5634 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-23 19:15:55.204  5588  5588 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-23 19:15:55.204  5588  5634 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-23 19:15:55.204  5588  5588 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
,11-23 19:15:55.204  5588  5634 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-23 19:15:55.204  5588  5634 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-23 19:15:55.204  5588  5634 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a2a4873 added. We now have 4 listener(s)
11-23 19:15:55.205  5588  5634 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-23 19:15:55.205  5588  5634 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
11-23 19:15:55.206  5588  5634 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-23 19:15:55.207  5588  5634 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2061330 added. We now have 4 listener(s)
11-23 19:15:55.208  5588  5634 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-23 19:15:55.208  5588  5634 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,11-23 19:15:55.208  5588  5634 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-23 19:15:55.208  5588  5634 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-23 19:15:55.208  5588  5634 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d8efba9 added. We now have 5 listener(s)
11-23 19:15:55.208  5588  5634 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-23 19:15:55.208  5588  5634 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-23 19:15:55.209  5588  5634 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-23 19:15:55.209  5588  5634 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-23 19:15:55.209  5588  5634 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-23 19:15:55.209  5588  5634 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-23 19:15:55.209  5812  5828 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
11-23 19:15:55.209  5588  5634 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-23 19:15:55.209  5812  5828 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-23 19:15:55.209  5588  5634 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4c2cce2 removed from the list
11-23 19:15:55.209  5588  5634 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 19:15:55.209  5588  5634 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a2a4873 removed from the list
11-23 19:15:55.209  5588  5634 D io.jxcore.node.ConnectivityMonitor: stop
11-23 19:15:55.210  5588  5634 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
,11-23 19:15:55.210  5588  5634 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-23 19:15:55.212  5588  5634 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-23 19:15:55.212  5588  5634 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 19:15:55.212  5588  5634 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 19:15:55.213  5588  5634 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-23 19:15:55.213  5588  5634 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-23 19:15:55.213  5588  5634 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 19:15:55.213  5588  5634 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a2a4873 not in the list
11-23 19:15:55.213  5588  5634 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-23 19:15:55.213  5588  5634 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-23 19:15:55.214  5812  5828 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
11-23 19:15:55.214  5812  5828 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-23 19:15:55.214  5588  5634 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
,11-23 19:15:55.214  5588  5634 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 19:15:55.214  5588  5634 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 19:15:55.214  5588  5634 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-23 19:15:55.215  5588  5634 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-23 19:15:55.215  5588  5634 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 19:15:55.215  5588  5634 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d8efba9 removed from the list
11-23 19:15:55.215  5588  5634 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-23 19:15:55.215  5812  5832 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
11-23 19:15:55.215  5588  5634 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-23 19:15:55.215  5588  5634 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-23 19:15:55.215  5588  5634 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2061330 removed from the list
11-23 19:15:55.216  5588  5634 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
,11-23 19:15:55.216  5588  5634 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
11-23 19:15:55.216  5588  5634 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
11-23 19:15:55.216  5588  5634 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-23 19:15:55.216  5588  5634 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
11-23 19:15:55.216  5588  5634 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,11-23 19:15:55.219  5812  5828 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,11-23 19:15:55.219  5812  5828 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-23 19:15:55.219  5812  5828 E BtGatt.ContextMap: Context not found for ID 5
,11-23 19:15:55.224  5812  5828 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
,11-23 19:15:55.224  5812  5828 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-23 19:15:55.224  5812  5832 D BtGatt.ScanManager: stopping BLe Batch
,11-23 19:15:55.228  5812  5828 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,11-23 19:15:55.229  5812  5828 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-23 19:15:55.229  5812  5832 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-23 19:15:55.233  5812  5828 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,11-23 19:15:55.233  5812  5828 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-23 19:15:55.519  5866  5866 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,11-23 19:15:55.552  5866  5866 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,11-23 19:15:55.553  5866  5866 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,11-23 19:15:55.561   929  2970 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,11-23 19:15:55.562   929  2970 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
11-23 19:15:55.562   929  2972 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,11-23 19:15:55.581   929  2970 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-23 19:15:55.593   508   913 D CommandListener: Setting iface cfg
,11-23 19:15:55.599  5588  5588 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-23 19:15:55.599   929  2970 D WifiStateMachine: Start Dhcp Watchdog 3
,11-23 19:15:55.605   929  5871 D DhcpClient: Receive thread started
,11-23 19:15:55.610   929  2972 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-23 19:15:55.611   929  2970 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
11-23 19:15:55.611   929  2972 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 102] to 60
,11-23 19:15:55.660  5588  5588 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-23 19:15:55.693   929  2970 E native  : do suspend false
,11-23 19:15:55.703  5588  5588 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-23 19:15:55.708   929  5870 D DhcpClient: Broadcasting DHCPDISCOVER
,11-23 19:15:55.722   929  5871 D DhcpClient: Received packet: 60:83:34:25:d7:70 OFFER, ip /192.168.1.109, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172764, domain null
,11-23 19:15:55.722   929  5870 D DhcpClient: Got pending lease: IP address 192.168.1.109/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172764 seconds
,11-23 19:15:55.724   929  5870 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.109 serverid=192.168.1.1
,11-23 19:15:55.737   929  5871 D DhcpClient: Received packet: 60:83:34:25:d7:70 ACK: your new IP /192.168.1.109, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,11-23 19:15:55.737   929  5870 D DhcpClient: Confirmed lease: IP address 192.168.1.109/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,11-23 19:15:55.740   508   913 D CommandListener: Setting iface cfg
11-23 19:15:55.745   929  2970 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,11-23 19:15:55.748   929  5870 D DhcpClient: Scheduling renewal in 86399s
,11-23 19:15:55.764   929  2970 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,11-23 19:15:55.765   929  2970 D WifiConfigStore: No blacklist allowed without epno enabled
,11-23 19:15:55.766   929  2972 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
11-23 19:15:55.772   929  2972 D ConnectivityService: Adding iface wlan0 to network 102
11-23 19:15:55.777   929  2970 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,11-23 19:15:55.823   929  2972 E ConnectivityService: Unexpected mtu value: 0, wlan0
,11-23 19:15:55.823   929  2972 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
,11-23 19:15:55.825   929  2972 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
,11-23 19:15:55.827   929  2972 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
,11-23 19:15:55.831   929  2972 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
,11-23 19:15:55.839   929  2972 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-23 19:15:55.844   929  2972 D ConnectivityService: scheduleUnvalidatedPrompt 102
,11-23 19:15:55.844   929  2972 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 102]
11-23 19:15:55.845   929  2972 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 102]
11-23 19:15:55.845   929  2970 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
11-23 19:15:55.845   929  2972 D ConnectivityService:    accepting network in place of null
11-23 19:15:55.845   929  2970 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,11-23 19:15:55.846   929  2972 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d770/64,192.168.1.109/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -65]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,11-23 19:15:55.855   929  5869 D NetlinkSocketObserver: NeighborEvent{elapsedMs=263358, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,11-23 19:15:55.869   508   913 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-23 19:15:55.893   508   913 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-23 19:15:55.896   929  2972 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
,11-23 19:15:55.897   929  2972 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
11-23 19:15:55.897  3769  3887 W QCNEJ   : |CORE| network available: 102
11-23 19:15:55.898   929  2972 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
11-23 19:15:55.898  3769  3887 W QCNEJ   : |CORE| onAvailable: bind the process to WIFI
11-23 19:15:55.899   929   946 D Tethering: MasterInitialState.processMessage what=3
11-23 19:15:55.903  3769  3887 W QCNEJ   : |CORE| newLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d770/64,192.168.1.109/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}
11-23 19:15:55.904  3769  3887 W QCNEJ   : |CORE| curLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d770/64,192.168.1.109/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,11-23 19:15:55.913  5021  5045 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
11-23 19:15:55.913  5021  5045 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
11-23 19:15:55.913  5021  5045 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,1,0,0
11-23 19:15:55.914  5021  5045 E SarControlService: no key has been found,reset the power
11-23 19:15:55.914  5021  5058 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
11-23 19:15:55.914  5021  5058 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
11-23 19:15:55.914  5021  5058 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
11-23 19:15:55.915  5046  5046 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
11-23 19:15:55.915  5046  5046 D QcrilMsgTunnelSocket: [1004] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
11-23 19:15:55.918  5021  5058 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
,11-23 19:15:55.918  5021  5058 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
11-23 19:15:55.918  5021  5058 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
11-23 19:15:55.919  5046  5060 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@6ad9059 HexData = [00000000ec03000000000000ffffffff]
11-23 19:15:55.919  5046  5060 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-23 19:15:55.919  5046  5060 D QcrilMsgTunnelSocket: [1004] < OEM_HOOK_RAW [null]
11-23 19:15:55.920  3954  3954 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
11-23 19:15:55.923   929  5868 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=172.217.21.14,2a00:1450:4001:802::200e
11-23 19:15:55.923  3743  3743 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
11-23 19:15:55.926  3743  3743 D SystemUpdateService: onCreate
11-23 19:15:55.927  5046  5046 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
11-23 19:15:55.927  5046  5046 D QcrilMsgTunnelSocket: [1005] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
11-23 19:15:55.930  5046  5046 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
11-23 19:15:55.930  5021  5032 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
11-23 19:15:55.933  5046  5060 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@6ad9059 HexData = [00000000ed03000000000000ffffffff]
11-23 19:15:55.933  5046  5060 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-23 19:15:55.933  5046  5060 D QcrilMsgTunnelSocket: [1005] < OEM_HOOK_RAW [null]
11-23 19:15:55.933  5046  5046 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
11-23 19:15:55.933  5021  5031 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
11-23 19:15:55.934  3743  3743 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,11-23 19:15:55.945  3743  3743 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,11-23 19:15:55.950  3743  5369 I iu.UploadsManager: num queued entries: 0
,11-23 19:15:55.950  3743  5369 I iu.UploadsManager: num updated entries: 0
,11-23 19:15:55.952  3743  5369 I iu.SyncManager: NEXT; no task
,11-23 19:15:55.954  3743  5886 I SystemUpdateService: active receiver: enabled
,11-23 19:15:55.957  3743  3743 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,11-23 19:15:55.958  3743  3743 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
11-23 19:15:55.960  5693  5693 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
11-23 19:15:55.964  5693  5693 D SprintDMHelper: simOperator: 
11-23 19:15:55.964  5693  5693 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,11-23 19:15:55.976   929  5868 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 23 Nov 2016 18:15:55 GMT], X-Android-Received-Millis=[1479924955976], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1479924955947]}
,11-23 19:15:55.977   929  2972 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,11-23 19:15:55.977   929  2972 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] validation  passed
11-23 19:15:55.977   929  2972 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
11-23 19:15:55.978   929  2972 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,11-23 19:15:55.981  3743  5886 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,11-23 19:15:55.996  3743  5886 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,11-23 19:15:55.996  3743  5886 I SystemUpdateService: now status is 0 (complete)
11-23 19:15:55.996  3743  5886 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
11-23 19:15:55.996  3743  5886 I SystemUpdateService: file has been verified
11-23 19:15:55.996  3743  5886 I SystemUpdateService: OTA package size = 21989297
,11-23 19:15:56.006  3743  5886 I SystemUpdateService: showing system update notification
,11-23 19:15:56.017   929   929 V NotificationService: pkg=com.google.android.gms canInterrupt=false intercept=true
,11-23 19:15:56.018  3743  3743 D SystemUpdateService: onDestroy
,11-23 19:15:56.081  4996  5894 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,11-23 19:15:56.129   508   913 D TetherController: Setting IP forward enable = 1
,11-23 19:15:57.350  5588  5929 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 177, name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
11-23 19:15:57.350  5588  5929 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-23 19:15:58.145  5588  5929 W !!      : call onHalfStreamCopied
,11-23 19:15:58.145  5588  5929 I testCopyDataAndClose: closing input stream
,11-23 19:15:58.629   929  2972 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-23 19:15:58.910  5588  5929 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 177, thread name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
11-23 19:15:58.910  5588  5929 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-23 19:15:58.910  5588  5929 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
11-23 19:15:58.910  5588  5929 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-23 19:15:58.910  5588  5929 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
,11-23 19:15:58.910  5588  5929 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
11-23 19:15:58.910  5588  5929 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
11-23 19:15:58.910  5588  5929 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
,11-23 19:15:58.910  5588  5929 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
11-23 19:15:58.910  5588  5929 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 177, name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
11-23 19:15:58.910  5588  5929 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 20971520 and the total number of bytes written 20971520
,11-23 19:16:01.647   929  2972 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-23 19:16:02.993  5588  5930 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 180, name: My test thread name). Connection data: Peer properties: [null null].
11-23 19:16:02.993  5588  5930 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-23 19:16:03.848   929  2972 D ConnectivityService: handlePromptUnvalidated 102
,11-23 19:16:04.668   929  2972 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-23 19:16:04.992  5588  5634 I io.jxcore.node.StreamCopyingThread: close: Thread ID: 180. Connection data: Peer properties: [null null].
11-23 19:16:04.992  5588  5634 I io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-23 19:16:04.993  5588  5634 D io.jxcore.node.StreamCopyingThread: closeStreams: Streams closed (thread ID: 180, name: My test thread name)
,11-23 19:16:05.131  5588  5931 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 182, name: testCopyBigData thread). Connection data: Peer properties: [null null].
11-23 19:16:05.131  5588  5931 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-23 19:16:05.139  5588  5930 D io.jxcore.node.StreamCopyingThread: number of bytes read = 0
,11-23 19:16:05.139  5588  5930 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 180, name: My test thread name). Connection data: Peer properties: [null null].
11-23 19:16:05.139  5588  5930 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 154 and the total number of bytes written 154
,11-23 19:16:06.739  5588  5931 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 182, thread name: testCopyBigData thread). Connection data: Peer properties: [null null].
11-23 19:16:06.739  5588  5931 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-23 19:16:06.740  5588  5931 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
11-23 19:16:06.740  5588  5931 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
11-23 19:16:06.740  5588  5931 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
11-23 19:16:06.740  5588  5931 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
11-23 19:16:06.740  5588  5931 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
11-23 19:16:06.740  5588  5931 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
,11-23 19:16:06.740  5588  5931 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
11-23 19:16:06.740  5588  5931 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 182, name: testCopyBigData thread). Connection data: Peer properties: [null null].
11-23 19:16:06.740  5588  5931 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 20971520 and the total number of bytes written 20971520
,11-23 19:16:06.812   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 19:16:06.912   929  2970 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 15, 16 -> obsolete
,11-23 19:16:07.813   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 19:16:08.814   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 19:16:09.815   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 19:16:10.817   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 19:16:11.246  5588  5932 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 184, name: My test thread name). Connection data: Peer properties: [null null].
11-23 19:16:11.246  5588  5932 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-23 19:16:11.246  5588  5932 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 184, thread name: My test thread name). Connection data: Peer properties: [null null].
11-23 19:16:11.246  5588  5932 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
11-23 19:16:11.246  5588  5932 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
11-23 19:16:11.246  5588  5932 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
11-23 19:16:11.246  5588  5932 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
11-23 19:16:11.247  5588  5932 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
,11-23 19:16:11.247  5588  5932 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
11-23 19:16:11.247  5588  5932 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
11-23 19:16:11.247  5588  5932 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
11-23 19:16:11.247  5588  5932 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 184, name: My test thread name). Connection data: Peer properties: [null null].
11-23 19:16:11.247  5588  5932 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 22
11-23 19:16:11.249  5588  5634 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
11-23 19:16:11.252  5588  5933 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 188, name: My test thread name). Connection data: Peer properties: [null null].
11-23 19:16:11.252  5588  5933 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-23 19:16:11.253  5588  5933 E io.jxcore.node.StreamCopyingThread: Failed to write to the output stream (thread ID: 188, thread name: My test thread name): Test exception.
11-23 19:16:11.253  5588  5933 D io.jxcore.node.StreamCopyingThread: onStreamCopyError (ID: 188, name: My test thread name). Connection data: Peer properties: [null null].
11-23 19:16:11.253  5588  5933 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
11-23 19:16:11.253  5588  5933 D io.jxcore.node.StreamCopyingThread: number of bytes read = 22
11-23 19:16:11.253  5588  5933 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 188, name: My test thread name). Connection data: Peer properties: [null null].
11-23 19:16:11.253  5588  5933 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
,11-23 19:16:11.256  5588  5634 I jxcore-log: 2016-11-23 18:16:11 - DEBUG UnitTest_app: 'Total number of executed tests:  82'
11-23 19:16:11.256  5588  5634 I jxcore-log: 
11-23 19:16:11.256  5588  5634 I jxcore-log: 2016-11-23 18:16:11 - DEBUG UnitTest_app: 'Number of passed tests:  82'
11-23 19:16:11.256  5588  5634 I jxcore-log: 
,11-23 19:16:11.257  5588  5634 I jxcore-log: 2016-11-23 18:16:11 - DEBUG UnitTest_app: 'Number of failed tests:  0'
11-23 19:16:11.257  5588  5634 I jxcore-log: 
11-23 19:16:11.257  5588  5634 I jxcore-log: 2016-11-23 18:16:11 - DEBUG UnitTest_app: 'Number of ignored tests:  0'
11-23 19:16:11.257  5588  5634 I jxcore-log: 
11-23 19:16:11.257  5588  5634 I jxcore-log: 2016-11-23 18:16:11 - DEBUG UnitTest_app: 'Total duration:  91777'
11-23 19:16:11.257  5588  5634 I jxcore-log: 
,11-23 19:16:11.259  5588  5634 I jxcore-log: 2016-11-23 18:16:11 - DEBUG UnitTest_app: 'Unit Test app is loaded'
11-23 19:16:11.259  5588  5634 I jxcore-log: 
,11-23 19:16:11.262  5588  5634 I jxcore-log: 2016-11-23 18:16:11 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
11-23 19:16:11.262  5588  5634 I jxcore-log: 
11-23 19:16:11.263  5588  5634 I jxcore-log: 2016-11-23 18:16:11 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
11-23 19:16:11.263  5588  5634 I jxcore-log: 
11-23 19:16:11.264  5588  5634 I jxcore-log: 2016-11-23 18:16:11 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
11-23 19:16:11.264  5588  5634 I jxcore-log: 
11-23 19:16:11.264  5588  5634 I jxcore-log: 2016-11-23 18:16:11 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH"})'
11-23 19:16:11.264  5588  5634 I jxcore-log: 
11-23 19:16:11.264  5588  5634 I jxcore-log: 2016-11-23 18:16:11 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-23 19:16:11.264  5588  5634 I jxcore-log: 
11-23 19:16:11.265  5588  5634 I jxcore-log: 2016-11-23 18:16:11 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-23 19:16:11.265  5588  5634 I jxcore-log: 
11-23 19:16:11.265  5588  5634 I jxcore-log: 2016-11-23 18:16:11 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-23 19:16:11.265  5588  5634 I jxcore-log: 
,11-23 19:16:11.265  5588  5634 I jxcore-log: 2016-11-23 18:16:11 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
11-23 19:16:11.265  5588  5634 I jxcore-log: 
11-23 19:16:11.266  5588  5634 I jxcore-log: 2016-11-23 18:16:11 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
11-23 19:16:11.266  5588  5634 I jxcore-log: 
11-23 19:16:11.266  5588  5634 I jxcore-log: 2016-11-23 18:16:11 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
11-23 19:16:11.266  5588  5634 I jxcore-log: 
11-23 19:16:11.266  5588  5634 I jxcore-log: 2016-11-23 18:16:11 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH"})'
11-23 19:16:11.266  5588  5634 I jxcore-log: 
11-23 19:16:11.266  5588  5634 I jxcore-log: 2016-11-23 18:16:11 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-23 19:16:11.266  5588  5634 I jxcore-log: 
11-23 19:16:11.266  5588  5634 I jxcore-log: 2016-11-23 18:16:11 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-23 19:16:11.266  5588  5634 I jxcore-log: 
,11-23 19:16:11.267  5588  5634 I jxcore-log: 2016-11-23 18:16:11 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-23 19:16:11.267  5588  5634 I jxcore-log: 
11-23 19:16:11.267  5588  5634 I jxcore-log: 2016-11-23 18:16:11 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-23 19:16:11.267  5588  5634 I jxcore-log: 
11-23 19:16:11.267  5588  5634 I jxcore-log: 2016-11-23 18:16:11 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-23 19:16:11.267  5588  5634 I jxcore-log: 
11-23 19:16:11.267  5588  5634 I jxcore-log: 2016-11-23 18:16:11 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
11-23 19:16:11.267  5588  5634 I jxcore-log: 
11-23 19:16:11.268  5588  5634 I jxcore-log: 2016-11-23 18:16:11 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
11-23 19:16:11.268  5588  5634 I jxcore-log: 
,11-23 19:16:11.268  5588  5634 I jxcore-log: 2016-11-23 18:16:11 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
11-23 19:16:11.268  5588  5634 I jxcore-log: 
11-23 19:16:11.268  5588  5634 I jxcore-log: 2016-11-23 18:16:11 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
11-23 19:16:11.268  5588  5634 I jxcore-log: 
11-23 19:16:11.268  5588  5634 I jxcore-log: 2016-11-23 18:16:11 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
11-23 19:16:11.268  5588  5634 I jxcore-log: 
11-23 19:16:11.269  5588  5634 I jxcore-log: 2016-11-23 18:16:11 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
11-23 19:16:11.269  5588  5634 I jxcore-log: 
11-23 19:16:11.269  5588  5634 I jxcore-log: 2016-11-23 18:16:11 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
11-23 19:16:11.269  5588  5634 I jxcore-log: 
11-23 19:16:11.269  5588  5634 I jxcore-log: 2016-11-23 18:16:11 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
11-23 19:16:11.269  5588  5634 I jxcore-log: 
,11-23 19:16:11.271  5588  5634 I jxcore-log: 2016-11-23 18:16:11 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
11-23 19:16:11.271  5588  5634 I jxcore-log: 
11-23 19:16:11.271  5588  5634 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-23 19:16:11.271  5588  5634 D io.jxcore.node.StartStopOperationHandler: Operation timeout, state error: null
11-23 19:16:11.271  5588  5634 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-23 19:16:11.271  5588  5634 D io.jxcore.node.StartStopOperationHandler: Operation timeout, state error: Discovery manager not started
11-23 19:16:11.271  5588  5634 I jxcore-log: 2016-11-23 18:16:11 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-23 19:16:11.271  5588  5634 I jxcore-log: 
,11-23 19:16:11.272  5588  5634 I jxcore-log: 2016-11-23 18:16:11 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-23 19:16:11.272  5588  5634 I jxcore-log: 
11-23 19:16:11.272  5588  5634 I jxcore-log: 2016-11-23 18:16:11 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-23 19:16:11.272  5588  5634 I jxcore-log: 
11-23 19:16:11.272  5588  5634 I jxcore-log: 2016-11-23 18:16:11 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-23 19:16:11.272  5588  5634 I jxcore-log: 
11-23 19:16:11.272  5588  5634 I jxcore-log: 2016-11-23 18:16:11 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-23 19:16:11.272  5588  5634 I jxcore-log: 
11-23 19:16:11.273  5588  5634 I jxcore-log: 2016-11-23 18:16:11 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-23 19:16:11.273  5588  5634 I jxcore-log: 
,11-23 19:16:11.278  5588  5634 I jxcore-log: 2016-11-23 18:16:11 - DEBUG UnitTest_app: 'My device name is: Huawei-Nexus 6P'
11-23 19:16:11.278  5588  5634 I jxcore-log: 
11-23 19:16:11.278  5588  5634 I jxcore-log: 2016-11-23 18:16:11 - WARN testUtils: 'myNameCallback not set!'
11-23 19:16:11.278  5588  5634 I jxcore-log: 
,11-23 19:16:11.285  5588  5588 D SystemWebChromeClient: file:///android_asset/www/js/thali_main.js: Line 68 : UIApp is all set and ready!
,11-23 19:16:11.285  5588  5588 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
,11-23 19:16:11.818   536   536 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,11-23 19:16:13.370  5588  5634 I jxcore-log: 2016-11-23 18:16:13 - INFO runTests: 'Starting tests. Network type: WIFI. Platform: android'
11-23 19:16:13.370  5588  5634 I jxcore-log: 
,11-23 19:16:13.372  5588  5634 I jxcore-log: 2016-11-23 18:16:13 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js'
11-23 19:16:13.372  5588  5634 I jxcore-log: 
,11-23 19:16:13.729  5588  5634 I jxcore-log: 2016-11-23 18:16:13 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js'
11-23 19:16:13.729  5588  5634 I jxcore-log: 
,11-23 19:16:13.740  5588  5634 I jxcore-log: 2016-11-23 18:16:13 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManager.js'
11-23 19:16:13.740  5588  5634 I jxcore-log: 
,11-23 19:16:14.863  5588  5634 I jxcore-log: 2016-11-23 18:16:14 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js'
11-23 19:16:14.863  5588  5634 I jxcore-log: 
,11-23 19:16:15.059  5588  5634 I jxcore-log: 2016-11-23 18:16:15 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js'
11-23 19:16:15.059  5588  5634 I jxcore-log: 
,11-23 19:16:15.064  5588  5634 I jxcore-log: 2016-11-23 18:16:15 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testNativeMethod.js'
11-23 19:16:15.064  5588  5634 I jxcore-log: 
,11-23 19:16:15.069  5588  5634 I jxcore-log: 2016-11-23 18:16:15 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPouchDBCheckpointPlugin.js'
11-23 19:16:15.069  5588  5634 I jxcore-log: 
,11-23 19:16:15.559  5588  5634 I jxcore-log: 2016-11-23 18:16:15 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPouchDBGenerator.js'
11-23 19:16:15.559  5588  5634 I jxcore-log: 
,11-23 19:16:15.604  5588  5634 I jxcore-log: 2016-11-23 18:16:15 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js'
11-23 19:16:15.604  5588  5634 I jxcore-log: 
,11-23 19:16:15.617  5588  5634 I jxcore-log: 2016-11-23 18:16:15 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js'
11-23 19:16:15.617  5588  5634 I jxcore-log: 
,11-23 19:16:15.621  5588  5634 I jxcore-log: 2016-11-23 18:16:15 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliManager.js'
11-23 19:16:15.621  5588  5634 I jxcore-log: 
,11-23 19:16:15.897  5588  5634 I jxcore-log: 2016-11-23 18:16:15 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliManagerCoordinated.js'
11-23 19:16:15.897  5588  5634 I jxcore-log: 
,11-23 19:16:16.025  5588  5634 I jxcore-log: 2016-11-23 18:16:16 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js'
11-23 19:16:16.025  5588  5634 I jxcore-log: 
,11-23 19:16:16.399  5588  5634 I jxcore-log: 2016-11-23 18:16:16 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js'
11-23 19:16:16.399  5588  5634 I jxcore-log: 
,11-23 19:16:16.407  5588  5634 I jxcore-log: 2016-11-23 18:16:16 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeDiscoveryCoordinated.js'
11-23 19:16:16.407  5588  5634 I jxcore-log: 
,11-23 19:16:16.411  5588  5634 I jxcore-log: 2016-11-23 18:16:16 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js'
11-23 19:16:16.411  5588  5634 I jxcore-log: 
,11-23 19:16:16.416  5588  5634 I jxcore-log: 2016-11-23 18:16:16 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js'
11-23 19:16:16.416  5588  5634 I jxcore-log: 
,11-23 19:16:16.422  5588  5634 I jxcore-log: 2016-11-23 18:16:16 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js'
11-23 19:16:16.422  5588  5634 I jxcore-log: 
,11-23 19:16:16.451  5588  5634 I jxcore-log: 2016-11-23 18:16:16 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js'
11-23 19:16:16.451  5588  5634 I jxcore-log: 
,11-23 19:16:16.486  5588  5634 I jxcore-log: 2016-11-23 18:16:16 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js'
11-23 19:16:16.486  5588  5634 I jxcore-log: 
,11-23 19:16:16.492  5588  5634 I jxcore-log: 2016-11-23 18:16:16 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationLocal.js'
11-23 19:16:16.492  5588  5634 I jxcore-log: 
,11-23 19:16:16.499  5588  5634 I jxcore-log: 2016-11-23 18:16:16 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js'
11-23 19:16:16.499  5588  5634 I jxcore-log: 
,11-23 19:16:16.514  5588  5634 I jxcore-log: 2016-11-23 18:16:16 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js'
11-23 19:16:16.514  5588  5634 I jxcore-log: 
,11-23 19:16:16.530  5588  5634 I jxcore-log: 2016-11-23 18:16:16 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js'
11-23 19:16:16.530  5588  5634 I jxcore-log: 
,11-23 19:16:16.536  5588  5634 I jxcore-log: 2016-11-23 18:16:16 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolDefault.js'
11-23 19:16:16.536  5588  5634 I jxcore-log: 
,11-23 19:16:16.541  5588  5634 I jxcore-log: 2016-11-23 18:16:16 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js'
11-23 19:16:16.541  5588  5634 I jxcore-log: 
,11-23 19:16:16.554  5588  5634 I jxcore-log: 2016-11-23 18:16:16 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolOneAtATime.js'
11-23 19:16:16.554  5588  5634 I jxcore-log: 
,11-23 19:16:16.572  5588  5634 I jxcore-log: 2016-11-23 18:16:16 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js'
11-23 19:16:16.572  5588  5634 I jxcore-log: 
,11-23 19:16:16.586  5588  5634 I jxcore-log: 2016-11-23 18:16:16 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js'
11-23 19:16:16.586  5588  5634 I jxcore-log: 
,11-23 19:16:16.597  5588  5634 I jxcore-log: 2016-11-23 18:16:16 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerAction.js'
11-23 19:16:16.597  5588  5634 I jxcore-log: 
,11-23 19:16:16.610  5588  5634 I jxcore-log: 2016-11-23 18:16:16 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js'
11-23 19:16:16.610  5588  5634 I jxcore-log: 
,11-23 19:16:16.620  5588  5634 I jxcore-log: 2016-11-23 18:16:16 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js'
11-23 19:16:16.620  5588  5634 I jxcore-log: 
,11-23 19:16:16.633  5588  5634 I jxcore-log: 2016-11-23 18:16:16 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js'
11-23 19:16:16.633  5588  5634 I jxcore-log: 
,11-23 19:16:16.643  5588  5634 I jxcore-log: 2016-11-23 18:16:16 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js'
11-23 19:16:16.643  5588  5634 I jxcore-log: 
,11-23 19:16:16.650  5588  5634 I jxcore-log: 2016-11-23 18:16:16 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js'
11-23 19:16:16.650  5588  5634 I jxcore-log: 
,11-23 19:16:16.672  5588  5634 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: SUPPORTED
,11-23 19:16:16.673  5588  5634 I jxcore-log: 2016-11-23 18:16:16 - INFO testUtils: 'BLE multiple advertisement supported'
11-23 19:16:16.673  5588  5634 I jxcore-log: 
,11-23 19:16:16.705  5588  5634 I jxcore-log: 2016-11-23 18:16:16 - INFO CoordinatedClient: 'Connecting to coordination server on http://85.14.110.168:3000/'
11-23 19:16:16.705  5588  5634 I jxcore-log: 
,11-23 19:16:16.996  5588  5634 I jxcore-log: 2016-11-23 18:16:16 - DEBUG CoordinatedClient: 'connected to the test server'
11-23 19:16:16.996  5588  5634 I jxcore-log: 
,11-23 19:16:22.822   929  2972 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-23 19:16:28.882   929  2972 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-23 19:16:31.819   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 19:16:32.821   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 19:16:33.822   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 19:16:34.824   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 19:16:34.953   929  2972 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-23 19:16:35.825   536   536 I ServiceManager: Waiting for service AtCmdFwd...
11-23 19:16:35.826   929  2970 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-23 19:16:36.826   536   536 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,11-23 19:16:37.976   929  2972 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-23 19:16:47.065   929  2972 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-23 19:16:59.155   929  2972 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-23 19:17:01.826   536   536 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,11-23 19:17:01.827   536   536 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,11-23 19:17:08.242   929  2972 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-23 19:17:14.308   929  2972 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-23 19:17:15.830   929  2970 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-23 19:17:16.828   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 19:17:17.830   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 19:17:18.831   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 19:17:19.833   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 19:17:20.834   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 19:17:21.835   536   536 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,11-23 19:17:23.398   929  2972 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-23 19:17:26.428   929  2972 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-23 19:17:26.836   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 19:17:27.838   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 19:17:28.839   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 19:17:29.458   929  2972 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-23 19:17:29.841   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 19:17:30.842   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 19:17:31.843   536   536 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,11-23 19:17:32.491   929  2972 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-23 19:17:35.831   929  2970 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-23 19:17:41.581   929  2972 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-23 19:17:41.844   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 19:17:42.845   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 19:17:43.846   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 19:17:44.613   929  2972 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-23 19:17:44.848   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 19:17:45.849   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 19:17:46.850   536   536 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,11-23 19:18:01.851   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 19:18:02.853   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 19:18:03.854   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 19:18:04.855   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 19:18:05.857   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 19:18:06.857   536   536 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,11-23 19:18:14.899   929  2972 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-23 19:18:15.836   929  2970 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-23 19:18:17.936   929  2972 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-23 19:18:26.859   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 19:18:27.860   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 19:18:28.862   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 19:18:29.863   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 19:18:30.042   929  2972 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-23 19:18:30.865   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 19:18:31.866   536   536 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,11-23 19:18:33.074   929  2972 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-23 19:18:35.839   929  2970 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-23 19:18:48.221   929  2972 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-23 19:18:51.251   929  2972 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-23 19:18:55.841   929  2970 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-23 19:18:56.866   536   536 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,11-23 19:18:56.866   536   536 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,11-23 19:19:03.356   929  2972 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-23 19:19:06.387   929  2972 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-23 19:19:16.867   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 19:19:17.869   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 19:19:18.871   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 19:19:19.872   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 19:19:20.873   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 19:19:21.505   929  2972 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-23 19:19:21.874   536   536 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,11-23 19:19:24.531   929  2972 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-23 19:19:26.876   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 19:19:27.878   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 19:19:28.879   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 19:19:29.881   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 19:19:30.667  5588  5634 I jxcore-log: 2016-11-23 18:19:30 - DEBUG CoordinatedClient: 'device disconnected from the test server'
11-23 19:19:30.667  5588  5634 I jxcore-log: 
,11-23 19:19:30.882   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 19:19:30.971  5588  5634 I jxcore-log: 2016-11-23 18:19:30 - ERROR CoordinatedClient: 'connection error: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-23 19:19:30.971  5588  5634 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-23 19:19:30.971  5588  5634 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-23 19:19:30.971  5588  5634 I jxcore-log: emit@events.js:82:1
11-23 19:19:30.971  5588  5634 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-23 19:19:30.971  5588  5634 I jxcore-log: emit@events.js:82:1''
11-23 19:19:30.971  5588  5634 I jxcore-log: 
,11-23 19:19:30.972  5588  5634 I jxcore-log: 2016-11-23 18:19:30 - DEBUG CoordinatedClient: 'test client failed'
11-23 19:19:30.972  5588  5634 I jxcore-log: 
,11-23 19:19:30.983  5588  5634 I jxcore-log: 2016-11-23 18:19:30 - ERROR CoordinatedClient: 'connection error: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-23 19:19:30.983  5588  5634 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-23 19:19:30.983  5588  5634 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-23 19:19:30.983  5588  5634 I jxcore-log: emit@events.js:82:1
11-23 19:19:30.983  5588  5634 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-23 19:19:30.983  5588  5634 I jxcore-log: emit@events.js:82:1''
11-23 19:19:30.983  5588  5634 I jxcore-log: 
,11-23 19:19:30.984  5588  5634 I jxcore-log: 2016-11-23 18:19:30 - DEBUG CoordinatedClient: 'test client failed'
11-23 19:19:30.984  5588  5634 I jxcore-log: 
,11-23 19:19:30.989  5588  5634 I jxcore-log: 2016-11-23 18:19:30 - ERROR CoordinatedThaliTape: 'tests failed, error: 'Error: websocket error', stack: 'Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-23 19:19:30.989  5588  5634 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-23 19:19:30.989  5588  5634 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-23 19:19:30.989  5588  5634 I jxcore-log: emit@events.js:82:1
11-23 19:19:30.989  5588  5634 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-23 19:19:30.989  5588  5634 I jxcore-log: emit@events.js:82:1''
11-23 19:19:30.989  5588  5634 I jxcore-log: 
11-23 19:19:30.991  5588  5634 I jxcore-log: 2016-11-23 18:19:30 - DEBUG CoordinatedThaliTape: '****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****'
11-23 19:19:30.991  5588  5634 I jxcore-log: 
,11-23 19:19:31.477  5944  5944 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,11-23 19:19:31.483  5944  5944 D AndroidRuntime: CheckJNI is OFF
,11-23 19:19:31.506  5944  5944 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,11-23 19:19:31.538  5944  5944 I Radio-JNI: register_android_hardware_Radio DONE
,11-23 19:19:31.553  5944  5944 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,11-23 19:19:31.563   929   942 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=-1: uninstall pkg
11-23 19:19:31.564   929   942 I ActivityManager: Killing 5588:com.test.thalitest/u0a77 (adj 0): stop com.test.thalitest
,11-23 19:19:31.684   929  4871 D GraphicsStats: Buffer count: 2
,11-23 19:19:31.684   929  3596 I WindowState: WIN DEATH: Window{446212f u0 com.test.thalitest/com.test.thalitest.MainActivity}
,11-23 19:19:31.685   929  2971 D WifiService: Client connection lost with reason: 4
,11-23 19:19:31.703   929   942 W ActivityManager: Force removing ActivityRecord{5761344 u0 com.test.thalitest/.MainActivity t70}: app died, no saved state
,11-23 19:19:31.711   929   952 I art     : Starting a blocking GC Explicit
,11-23 19:19:31.718   929  3841 W ActivityManager: Spurious death for ProcessRecord{3f85cf 0:com.test.thalitest/u0a77}, curProc for 5588: null
,11-23 19:19:31.748   929  3596 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 5588 uid 10077
,11-23 19:19:31.743  3596  3596 W Binder_6: type=1400 audit(0.0:119): avc: denied { ioctl } for path="socket:[29698]" dev="sockfs" ino=29698 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
11-23 19:19:31.747  3596  3596 W Binder_6: type=1400 audit(0.0:120): avc: denied { ioctl } for path="socket:[29698]" dev="sockfs" ino=29698 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
11-23 19:19:31.749  3666  3666 I Keyboard.Facilitator: onFinishInput()
,11-23 19:19:31.816  3954  5958 I MicroRecognitionRnrImpl: Starting detection.
,11-23 19:19:31.818  3954  5959 I MicrophoneInputStream: mic_starting com.google.android.apps.gsa.speech.audio.x@e7be4be
,11-23 19:19:31.820   513  5961 I AudioFlinger: AudioFlinger's thread 0xf1ac0000 ready to run
,11-23 19:19:31.824   513  3006 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
,11-23 19:19:31.827   929   952 I art     : Explicit concurrent mark sweep GC freed 113754(7MB) AllocSpace objects, 64(2MB) LOS objects, 33% free, 29MB/44MB, paused 2.575ms total 115.352ms
11-23 19:19:31.827  3954  5959 I MicrophoneInputStream: mic_started com.google.android.apps.gsa.speech.audio.x@e7be4be
,11-23 19:19:31.837   513  5961 D audio_hw_primary: select_devices: out_snd_device(0: none) in_snd_device(63: voice-rec-mic)
,11-23 19:19:31.837   513  5961 D msm8974_platform: platform_send_audio_calibration: sending audio calibration for snd_device(63) acdb_id(62)
11-23 19:19:31.837   513  5961 I ACDB-LOADER: ACDB AFE returned = -19
11-23 19:19:31.837   513  5961 I soundtrigger: audio_extn_sound_trigger_update_device_status: device 0x3f of type 1 for Event 1
11-23 19:19:31.837   513  5961 D sound_trigger_platform: platform_stdev_check_and_update_concurrency: concurrency active 0, tx 1, rx 0, concurrency session_allowed 0
,11-23 19:19:31.838   513  5961 D audio_hw_primary: enable_snd_device: snd_device(63: voice-rec-mic)
,11-23 19:19:31.847   513  5961 D audio_hw_primary: enable_audio_route: apply and update mixer path: audio-record
,11-23 19:19:31.853   929   952 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,11-23 19:19:31.856  5944  5944 I art     : System.exit called, status: 0
,11-23 19:19:31.856  5944  5944 I AndroidRuntime: VM exiting with result code 0.
,11-23 19:19:31.860   929   952 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=0: pkg removed
,11-23 19:19:31.870  3666  3666 I Keyboard.Facilitator: resetDictionaries() : en_US
,11-23 19:19:31.872  5812  5812 D BluetoothMapAppObserver: onReceive
11-23 19:19:31.872  5812  5812 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
11-23 19:19:31.876  4038  4175 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
11-23 19:19:31.878   929  2962 I InputReader: Reconfiguring input devices.  changes=0x00000010
11-23 19:19:31.883   536   536 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,11-23 19:19:31.896  3666  5965 I Keyboard.Facilitator.DecoderInitializer: run()
,11-23 19:19:31.900  3393  5966 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,11-23 19:19:31.905  3666  5965 I Decoder : createOrResetDecoder
,11-23 19:19:31.935  3954  3954 I HotwordWorkerImpl: onReady
,11-23 19:19:31.941   929   929 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,11-23 19:19:31.945  3800  3800 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,11-23 19:19:31.947   445   445 W kworker/5:1: type=1400 audit(0.0:121): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-23 19:19:31.950  3580  3580 I ConfigService: onCreate
,11-23 19:19:31.953   445   445 W kworker/5:1: type=1400 audit(0.0:122): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-23 19:19:31.957  3580  3580 E NetworkScheduler.SchedulerReceiver: Invalid parameter app
,11-23 19:19:31.957  3580  3580 E NetworkScheduler.SchedulerReceiver: Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,11-23 19:19:31.964   929   941 E PackageManager: Failed to write settings, restoring backup
11-23 19:19:31.964   929   941 E PackageManager: java.io.IOException: write failed: EBADF (Bad file descriptor)
11-23 19:19:31.964   929   941 E PackageManager: 	at libcore.io.IoBridge.write(IoBridge.java:498)
11-23 19:19:31.964   929   941 E PackageManager: 	at java.io.FileOutputStream.write(FileOutputStream.java:186)
11-23 19:19:31.964   929   941 E PackageManager: 	at java.io.OutputStreamWriter.flushBytes(OutputStreamWriter.java:170)
11-23 19:19:31.964   929   941 E PackageManager: 	at java.io.OutputStreamWriter.flush(OutputStreamWriter.java:161)
11-23 19:19:31.964   929   941 E PackageManager: 	at java.io.BufferedWriter.flush(BufferedWriter.java:124)
11-23 19:19:31.964   929   941 E PackageManager: 	at org.kxml2.io.KXmlSerializer.flush(KXmlSerializer.java:477)
11-23 19:19:31.964   929   941 E PackageManager: 	at org.kxml2.io.KXmlSerializer.endDocument(KXmlSerializer.java:169)
11-23 19:19:31.964   929   941 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.writePermissionsSync(Settings.java:4650)
11-23 19:19:31.964   929   941 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.-wrap1(Settings.java)
11-23 19:19:31.964   929   941 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence$MyHandler.handleMessage(Settings.java:4830)
11-23 19:19:31.964   929   941 E PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-23 19:19:31.964   929   941 E PackageManager: 	at android.os.Looper.loop(Looper.java:148)
11-23 19:19:31.964   929   941 E PackageManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
11-23 19:19:31.964   929   941 E PackageManager: Caused by: android.system.ErrnoException: write failed: EBADF (Bad file descriptor)
11-23 19:19:31.964   929   941 E PackageManager: 	at libcore.io.Posix.writeBytes(Native Method)
11-23 19:19:31.964   929   941 E PackageManager: 	at libcore.io.Posix.write(Posix.java:271)
11-23 19:19:31.964   929   941 E PackageManager: 	at libcore.io.BlockGuardOs.write(BlockGuardOs.java:313)
11-23 19:19:31.964   929   941 E PackageManager: 	at libcore.io.IoBridge.write(IoBridge.java:493)
11-23 19:19:31.964   929   941 E PackageManager: 	... 12 more
,11-23 19:19:31.971  3666  5965 I Keyboard.Facilitator.MainLanguageModelLoader: run()
,11-23 19:19:31.967   445   445 W kworker/5:1: type=1400 audit(0.0:123): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-23 19:19:31.980   929  3833 I ActivityManager: Start proc 5973:com.google.android.googlequicksearchbox:crash_report/u0a29 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
,--------- beginning of crash
11-23 19:19:31.980  3838  3945 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
11-23 19:19:31.980  3838  3945 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 3838
11-23 19:19:31.980  3838  3945 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 778)
11-23 19:19:31.980  3838  3945 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
11-23 19:19:31.980  3838  3945 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
11-23 19:19:31.980  3838  3945 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
11-23 19:19:31.980  3838  3945 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
11-23 19:19:31.980  3838  3945 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
11-23 19:19:31.980  3838  3945 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
11-23 19:19:31.980  3838  3945 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
11-23 19:19:31.980  3838  3945 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
11-23 19:19:31.980  3838  3945 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
11-23 19:19:31.980  3838  3945 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
11-23 19:19:31.980  3838  3945 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,11-23 19:19:31.984   929  3555 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
11-23 19:19:31.985   929  5979 E DropBoxManagerService: Can't write: system_app_crash
11-23 19:19:31.985   929  5979 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop122.tmp: open failed: EROFS (Read-only file system)
11-23 19:19:31.985   929  5979 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
11-23 19:19:31.985   929  5979 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
11-23 19:19:31.985   929  5979 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
11-23 19:19:31.985   929  5979 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
11-23 19:19:31.985   929  5979 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
11-23 19:19:31.985   929  5979 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
11-23 19:19:31.985   929  5979 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
11-23 19:19:31.985   929  5979 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
11-23 19:19:31.985   929  5979 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
11-23 19:19:31.985   929  5979 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
11-23 19:19:31.985   929  5979 E DropBoxManagerService: 	... 5 more
11-23 19:19:31.988  3954  5561 W SearchService: Abort, client detached.
11-23 19:19:31.991  3954  3954 I HotwordDetector: Closing mic
11-23 19:19:31.991  3954  4194 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@e7be4be
11-23 19:19:31.991  3954  5959 E AudioRecord-JNI: Error -4 during AudioRecord native read
,11-23 19:19:31.998  3393  5966 E SQLiteLog: (3850) statement aborts at 18: [DELETE FROM calls WHERE (((source_package = 'com.test.thalitest'))) AND ((type = 4))] disk I/O error
,11-23 19:19:32.003   737   737 W Binder_4: type=1400 audit(0.0:124): avc: denied { ioctl } for path="socket:[15331]" dev="sockfs" ino=15331 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-23 19:19:32.011   929  5986 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,11-23 19:19:32.007   737   737 W Binder_4: type=1400 audit(0.0:125): avc: denied { ioctl } for path="socket:[15331]" dev="sockfs" ino=15331 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
11-23 19:19:32.007   736   736 W Binder_3: type=1400 audit(0.0:126): avc: denied { ioctl } for path="socket:[32400]" dev="sockfs" ino=32400 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
11-23 19:19:32.007   736   736 W Binder_3: type=1400 audit(0.0:127): avc: denied { ioctl } for path="socket:[32400]" dev="sockfs" ino=32400 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-23 19:19:32.014  3393  5966 E AndroidRuntime: FATAL EXCEPTION: IntentService[VoicemailCleanupService]
11-23 19:19:32.014  3393  5966 E AndroidRuntime: Process: android.process.acore, PID: 3393
11-23 19:19:32.014  3393  5966 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
11-23 19:19:32.014  3393  5966 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
11-23 19:19:32.014  3393  5966 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
11-23 19:19:32.014  3393  5966 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
11-23 19:19:32.014  3393  5966 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
11-23 19:19:32.014  3393  5966 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
11-23 19:19:32.014  3393  5966 E AndroidRuntime: 	at com.android.providers.contacts.DbModifierWithNotification.delete(DbModifierWithNotification.java:197)
11-23 19:19:32.014  3393  5966 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:219)
11-23 19:19:32.014  3393  5966 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
11-23 19:19:32.014  3393  5966 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
11-23 19:19:32.014  3393  5966 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
11-23 19:19:32.014  3393  5966 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
11-23 19:19:32.014  3393  5966 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
11-23 19:19:32.014  3393  5966 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
11-23 19:19:32.014  3393  5966 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-23 19:19:32.014  3393  5966 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
11-23 19:19:32.014  3393  5966 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,11-23 19:19:32.021   929  5987 E DropBoxManagerService: Can't write: system_app_crash
11-23 19:19:32.021   929  5987 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop124.tmp: open failed: EROFS (Read-only file system)
11-23 19:19:32.021   929  5987 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
11-23 19:19:32.021   929  5987 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
11-23 19:19:32.021   929  5987 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
11-23 19:19:32.021   929  5987 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
11-23 19:19:32.021   929  5987 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
11-23 19:19:32.021   929  5987 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
11-23 19:19:32.021   929  5987 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
11-23 19:19:32.021   929  5987 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
11-23 19:19:32.021   929  5987 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
11-23 19:19:32.021   929  5987 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
11-23 19:19:32.021   929  5987 E DropBoxManagerService: 	... 5 more
,11-23 19:19:32.035  3743  5989 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
,11-23 19:19:32.035  3743  5989 D AccountUtils: Clearing selected account for com.test.thalitest
,11-23 19:19:32.041  3666  5965 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /data/user/0/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
11-23 19:19:32.044  3666  5965 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
11-23 19:19:32.044  3666  5965 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
,11-23 19:19:32.046  3666  5965 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Contacts.dict
11-23 19:19:32.047  3666  5965 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = history
11-23 19:19:32.047  3666  5965 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loaded File = UserHistory.en_US.dict
,11-23 19:19:32.047  3666  5965 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = user
11-23 19:19:32.050   513  5961 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
,11-23 19:19:32.051   513  5961 D audio_hw_primary: disable_snd_device: snd_device(63: voice-rec-mic)
11-23 19:19:32.052  3666  5965 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Personal.en_US.dict
11-23 19:19:32.053  3666  5965 I Keyboard.Facilitator.PersonalDictionaryLoader: run() : Loaded (exit)
11-23 19:19:32.053  3666  5965 I Keyboard.Facilitator.Delight2FileSweeper: run()
,11-23 19:19:32.053  3666  5965 I Keyboard.Facilitator.RecurringTaskScheduler: run()
11-23 19:19:32.053  3666  5965 I StatsUtilsManager: startPeriodStatsRecorder() : Success
11-23 19:19:32.053  3666  5965 I PeriodicStatsRecorder: shouldRecordStats() = Too Soon
11-23 19:19:32.054  3743  5989 I LocationSettingsChecker: Removing dialog suppression flag for package com.test.thalitest
11-23 19:19:32.058   513  5961 I soundtrigger: audio_extn_sound_trigger_update_device_status: device 0x3f of type 1 for Event 0
11-23 19:19:32.059   513  5961 D sound_trigger_platform: platform_stdev_check_and_update_concurrency: concurrency active 0, tx 0, rx 0, concurrency session_allowed 1
11-23 19:19:32.059  3743  3743 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
11-23 19:19:32.060  3743  3743 D ChimeraModuleLdr: Module APK com.google.android.play.games already loaded
11-23 19:19:32.060   513  3006 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
11-23 19:19:32.063   929  5986 I Adreno  : QUALCOMM build                   : 63c06b2, I8366cd0437
11-23 19:19:32.063   929  5986 I Adreno  : Build Date                       : 12/06/15
11-23 19:19:32.063   929  5986 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
11-23 19:19:32.063   929  5986 I Adreno  : Local Branch                     : mybranch17112971
11-23 19:19:32.063   929  5986 I Adreno  : Remote Branch                    : quic/LA.BF64.1.2.9_v2
11-23 19:19:32.063   929  5986 I Adreno  : Remote Branch                    : NONE
11-23 19:19:32.063   929  5986 I Adreno  : Reconstruct Branch               : NOTHING
11-23 19:19:32.063  3954  4199 I MicroRecognitionRnrImpl: Stopping hotword detection.
11-23 19:19:32.064  3954  5958 I MicroRecognitionRnrImpl: Detection finished
,11-23 19:19:32.066  3743  3743 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
11-23 19:19:32.067  3743  3743 D ChimeraModuleLdr: Module APK com.google.android.play.games already loaded
,11-23 19:19:32.085  3954  5998 I UpdateIcingCorporaServi: Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,11-23 19:19:32.115   929   939 I ActivityManager: Start proc 6001:com.android.keychain/1000 for broadcast com.android.keychain/.KeyChainBroadcastReceiver
,11-23 19:19:32.121  3743  5996 W BaseAppContext: Using Auth Proxy for data requests.
11-23 19:19:32.125  3743  5996 W BaseAppContext: Using Auth Proxy for data requests.
,11-23 19:19:32.355   383   481 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0

```
