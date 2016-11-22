#### Test 947851597844ef3_thali07_Huawei-Nexus 6P Logs


```
--------- beginning of main
11-22 11:40:25.946   544   544 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 11:40:26.404  5639  5639 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
11-22 11:40:26.409  5639  5639 D AndroidRuntime: CheckJNI is OFF
11-22 11:40:26.437  5639  5639 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
11-22 11:40:26.473  5639  5639 I Radio-JNI: register_android_hardware_Radio DONE
11-22 11:40:26.488  5639  5639 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
11-22 11:40:26.498   928  3445 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
11-22 11:40:26.516  5639  5639 D AndroidRuntime: Shutting down VM
11-22 11:40:26.525  3998  4309 W SearchService: Abort, client detached.
11-22 11:40:26.538  3998  3998 I HotwordDetector: Closing mic
11-22 11:40:26.539  3998  4213 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@cee897
11-22 11:40:26.539  3998  4239 E AudioRecord-JNI: Error -4 during AudioRecord native read
11-22 11:40:26.549   928  3444 I ActivityManager: Start proc 5648:com.test.thalitest/u0a77 for activity com.test.thalitest/.MainActivity
11-22 11:40:26.606   512  4241 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
11-22 11:40:26.607   512  4241 D audio_hw_primary: disable_snd_device: snd_device(63: voice-rec-mic)
11-22 11:40:26.611   512  4241 I soundtrigger: audio_extn_sound_trigger_update_device_status: device 0x3f of type 1 for Event 0
11-22 11:40:26.611   512  4241 D sound_trigger_platform: platform_stdev_check_and_update_concurrency: concurrency active 0, tx 0, rx 0, concurrency session_allowed 1
11-22 11:40:26.612   512  3026 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
11-22 11:40:26.616  3998  4231 I MicroRecognitionRnrImpl: Stopping hotword detection.
11-22 11:40:26.618  3998  4237 I MicroRecognitionRnrImpl: Detection finished
11-22 11:40:26.644  5648  5648 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011750)
11-22 11:40:26.667  5648  5648 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
11-22 11:40:26.694  5648  5648 I LibraryLoader: Time to load native libraries: 23 ms (timestamps 6340-6363)
11-22 11:40:26.695  5648  5648 I LibraryLoader: Expected native library version number "",actual native library version number ""
11-22 11:40:26.713  5648  5648 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {708b9f2}
11-22 11:40:26.714  5648  5648 I LibraryLoader: Expected native library version number "",actual native library version number ""
11-22 11:40:26.714  5648  5648 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
11-22 11:40:26.717  5648  5648 I BrowserStartupController: Initializing chromium process, singleProcess=true
11-22 11:40:26.718  5648  5648 E SysUtils: ApplicationContext is null in ApplicationStatus
,11-22 11:40:26.751  5648  5648 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,11-22 11:40:26.759  5648  5648 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
11-22 11:40:26.759  5648  5648 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
11-22 11:40:26.759  5648  5648 I Adreno  : QUALCOMM build                   : 63c06b2, I8366cd0437
11-22 11:40:26.759  5648  5648 I Adreno  : Build Date                       : 12/06/15
11-22 11:40:26.759  5648  5648 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
11-22 11:40:26.759  5648  5648 I Adreno  : Local Branch                     : mybranch17112971
11-22 11:40:26.759  5648  5648 I Adreno  : Remote Branch                    : quic/LA.BF64.1.2.9_v2
11-22 11:40:26.759  5648  5648 I Adreno  : Remote Branch                    : NONE
11-22 11:40:26.759  5648  5648 I Adreno  : Reconstruct Branch               : NOTHING
,11-22 11:40:26.800   928   945 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@f60c973:true
,11-22 11:40:26.828   767   767 W Binder_4: type=1400 audit(0.0:99): avc: denied { ioctl } for path="socket:[33805]" dev="sockfs" ino=33805 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-22 11:40:26.828   767   767 W Binder_4: type=1400 audit(0.0:100): avc: denied { ioctl } for path="socket:[33805]" dev="sockfs" ino=33805 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-22 11:40:26.840  5648  5648 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,11-22 11:40:26.849  5648  5648 D SystemWebViewEngine: CordovaWebView is running on device made by: Huawei
,11-22 11:40:26.946   544   544 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 11:40:26.971   408   408 W Binder_2: type=1400 audit(0.0:101): avc: denied { ioctl } for path="socket:[34837]" dev="sockfs" ino=34837 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-22 11:40:26.971   408   408 W Binder_2: type=1400 audit(0.0:102): avc: denied { ioctl } for path="socket:[34837]" dev="sockfs" ino=34837 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
11-22 11:40:26.976  5648  5685 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,11-22 11:40:26.978  3186  3186 W Binder_3: type=1400 audit(0.0:103): avc: denied { ioctl } for path="socket:[31140]" dev="sockfs" ino=31140 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
11-22 11:40:26.978  3186  3186 W Binder_3: type=1400 audit(0.0:104): avc: denied { ioctl } for path="socket:[31140]" dev="sockfs" ino=31140 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-22 11:40:26.986  5648  5672 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,11-22 11:40:27.014  5648  5685 I OpenGLRenderer: Initialized EGL, version 1.4
,11-22 11:40:27.101   928   946 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +569ms
,11-22 11:40:27.098  3186  3186 W Binder_3: type=1400 audit(0.0:105): avc: denied { ioctl } for path="socket:[34842]" dev="sockfs" ino=34842 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-22 11:40:27.098  3186  3186 W Binder_3: type=1400 audit(0.0:106): avc: denied { ioctl } for path="socket:[34842]" dev="sockfs" ino=34842 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
11-22 11:40:27.098  3645  3645 W Binder_7: type=1400 audit(0.0:107): avc: denied { ioctl } for path="socket:[34841]" dev="sockfs" ino=34841 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
11-22 11:40:27.098  3645  3645 W Binder_7: type=1400 audit(0.0:108): avc: denied { ioctl } for path="socket:[34841]" dev="sockfs" ino=34841 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
11-22 11:40:27.104  3704  3704 I Keyboard.Facilitator: onFinishInput()
,11-22 11:40:27.126  5648  5648 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 5648
,11-22 11:40:27.225  5648  5648 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,11-22 11:40:27.351   928  3645 I ActivityManager: Killing 5444:com.android.chrome/u0a39 (adj 15): empty #17
,11-22 11:40:27.378   928  3645 I ActivityManager: Killing 5432:com.android.sdm.plugins.sprintdm/1001 (adj 15): empty #18
,11-22 11:40:27.399  5648  5688 D jxcore_app_log: JniHelper::setJavaVM(0xf547c000), pthread_self() = -562820816
,11-22 11:40:27.403  5648  5688 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
11-22 11:40:27.403  5648  5688 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
11-22 11:40:27.403  5648  5688 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
11-22 11:40:27.403  5648  5688 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
11-22 11:40:27.403  5648  5688 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,11-22 11:40:27.403  5648  5688 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2301a98 added. We now have 1 listener(s)
,11-22 11:40:27.405  5648  5688 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 60:83:34:25:D7:D4
,11-22 11:40:27.406  5648  5688 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
,11-22 11:40:27.406  5648  5688 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-22 11:40:27.406  5648  5688 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,11-22 11:40:27.408  5648  5688 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
11-22 11:40:27.408  5648  5688 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
11-22 11:40:27.408  5648  5688 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
11-22 11:40:27.408  5648  5688 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 60:83:34:25:D7:D4
11-22 11:40:27.408  5648  5688 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
11-22 11:40:27.408  5648  5688 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
11-22 11:40:27.408  5648  5688 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
11-22 11:40:27.408  5648  5688 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
11-22 11:40:27.408  5648  5688 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
11-22 11:40:27.408  5648  5688 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
11-22 11:40:27.408  5648  5688 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
11-22 11:40:27.408  5648  5688 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
11-22 11:40:27.408  5648  5688 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
11-22 11:40:27.408  5648  5688 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,11-22 11:40:27.409  5648  5688 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c69557 added. We now have 1 listener(s)
11-22 11:40:27.409  5648  5688 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-22 11:40:27.413   928  3008 D WifiService: New client listening to asynchronous messages
,11-22 11:40:27.414  5648  5688 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
11-22 11:40:27.414  5648  5688 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
,11-22 11:40:27.414  5648  5688 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[JavaBridge,5,main], id: 55
11-22 11:40:27.414  5648  5688 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
11-22 11:40:27.414  5648  5688 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
11-22 11:40:27.414  5648  5688 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
11-22 11:40:27.414  5648  5688 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[JavaBridge,5,main], id: 55
,11-22 11:40:27.416  5648  5688 I io.jxcore.node.LifeCycleMonitor: start: OK
,11-22 11:40:27.511  5648  5648 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,11-22 11:40:27.947   544   544 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 11:40:28.132  5648  5695 W jxcore-log: Initializing JXcore engine
11-22 11:40:28.132  5648  5695 W jxcore-log: JXcore engine is ready
,11-22 11:40:28.151  5695  5695 W Thread-61: type=1400 audit(0.0:109): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=11568 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,11-22 11:40:28.151  5695  5695 W Thread-61: type=1400 audit(0.0:110): avc: denied { ioctl } for path="socket:[13743]" dev="sockfs" ino=13743 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
11-22 11:40:28.151  5695  5695 W Thread-61: type=1400 audit(0.0:111): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=5964 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
11-22 11:40:28.151  5695  5695 W Thread-61: type=1400 audit(0.0:112): avc: denied { ioctl } for path="socket:[31121]" dev="sockfs" ino=31121 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:untrusted_app:s0:c512,c768 tclass=netlink_route_socket permissive=0
,11-22 11:40:28.164  5648  5695 W jxcore-log: Starting JXcore engine
,11-22 11:40:28.213  5648  5695 W jxcore-log: Platform android
11-22 11:40:28.213  5648  5695 W jxcore-log: 
,11-22 11:40:28.214  5648  5695 W jxcore-log: Process ARCH arm
11-22 11:40:28.214  5648  5695 W jxcore-log: 
,11-22 11:40:28.396  5648  5695 I jxcore-log: JXcore Cordova bridge is ready!
11-22 11:40:28.396  5648  5695 I jxcore-log: 
,11-22 11:40:28.396  5648  5695 W jxcore-log: JXcore engine is started
,11-22 11:40:28.412  5648  5688 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,11-22 11:40:28.419  5648  5648 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,11-22 11:40:28.947   544   544 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,11-22 11:40:38.025  4088  4500 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,11-22 11:40:38.237  5648  5695 I jxcore-log: 2016-11-22 10:40:38 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
11-22 11:40:38.237  5648  5695 I jxcore-log: 
,11-22 11:40:38.239  5648  5695 I jxcore-log: 2016-11-22 10:40:38 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
11-22 11:40:38.239  5648  5695 I jxcore-log: 
,11-22 11:40:38.244  5648  5695 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,11-22 11:40:38.244  5648  5695 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-22 11:40:38.244  5648  5695 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-22 11:40:38.244  5648  5695 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-22 11:40:38.244  5648  5695 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-22 11:40:38.244  5648  5695 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-22 11:40:38.244  5648  5695 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-22 11:40:38.244  5648  5695 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-22 11:40:38.244  5648  5695 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-22 11:40:38.244  5648  5695 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
11-22 11:40:38.246  5648  5695 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
11-22 11:40:38.248  5648  5695 I jxcore-log: 2016-11-22 10:40:38 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
11-22 11:40:38.248  5648  5695 I jxcore-log: 
11-22 11:40:38.250  5648  5695 I jxcore-log: 2016-11-22 10:40:38 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
11-22 11:40:38.250  5648  5695 I jxcore-log: 
,11-22 11:40:38.502  5648  5695 I jxcore-log: 2016-11-22 10:40:38 - DEBUG UnitTest_app: 'Running unit tests'
11-22 11:40:38.502  5648  5695 I jxcore-log: 
,11-22 11:40:38.503  5648  5695 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-22 11:40:38.503  5648  5695 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@465c7 added. We now have 2 listener(s)
11-22 11:40:38.503  5648  5695 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-22 11:40:38.504  5648  5695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-22 11:40:38.504  5648  5695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,11-22 11:40:38.504  5648  5695 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-22 11:40:38.504  5648  5695 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7cc27f4 added. We now have 2 listener(s)
11-22 11:40:38.504  5648  5695 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-22 11:40:38.504  5648  5695 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,11-22 11:40:38.506  5648  5695 D executeNativeTests: Running unit tests
,11-22 11:40:38.543  5648  5695 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,11-22 11:40:38.543  5648  5695 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f10758d added. We now have 3 listener(s)
11-22 11:40:38.544  5648  5695 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-22 11:40:38.544  5648  5695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-22 11:40:38.544  5648  5695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,11-22 11:40:38.544  5648  5695 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-22 11:40:38.544  5648  5695 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5e13342 added. We now have 3 listener(s)
11-22 11:40:38.544  5648  5695 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-22 11:40:38.544  5648  5695 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
11-22 11:40:38.546  5648  5695 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,11-22 11:40:38.546  5648  5695 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-22 11:40:38.546  5648  5695 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-22 11:40:38.546  5648  5695 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-22 11:40:38.547  5648  5695 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
11-22 11:40:38.547  5648  5695 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
11-22 11:40:38.547  5648  5695 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
11-22 11:40:38.547  5648  5695 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-22 11:40:38.547  5648  5695 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-22 11:40:38.547  5648  5695 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,11-22 11:40:38.547  5648  5695 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-22 11:40:38.548  5648  5695 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-22 11:40:38.548  5648  5695 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-22 11:40:38.548  5648  5695 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,11-22 11:40:38.548  5648  5695 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-22 11:40:38.548  5648  5695 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-22 11:40:38.548  5648  5695 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f10758d removed from the list
11-22 11:40:38.548  5648  5695 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-22 11:40:38.548  5648  5695 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5e13342 removed from the list
11-22 11:40:38.548  5648  5695 D io.jxcore.node.ConnectivityMonitor: stop
,11-22 11:40:38.548  5648  5695 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-22 11:40:38.549  5648  5695 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-22 11:40:38.549  5648  5695 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-22 11:40:38.549  5648  5695 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
,11-22 11:40:38.549  5648  5695 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-22 11:40:38.549  5648  5695 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-22 11:40:38.549  5648  5695 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-22 11:40:38.549  5648  5695 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5e13342 not in the list
,11-22 11:40:38.550  5648  5695 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
11-22 11:40:38.550  5648  5695 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-22 11:40:38.550  5648  5695 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-22 11:40:38.550  5648  5695 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-22 11:40:38.550  5648  5695 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,11-22 11:40:38.550  5648  5695 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-22 11:40:38.551  5648  5695 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f10758d not in the list
11-22 11:40:38.551  5648  5695 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-22 11:40:38.551  5648  5695 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5e13342 not in the list
11-22 11:40:38.551  5648  5695 D io.jxcore.node.ConnectivityMonitor: stop
11-22 11:40:38.551  5648  5695 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-22 11:40:38.551  5648  5695 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-22 11:40:38.551  5648  5695 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-22 11:40:38.551  5648  5695 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-22 11:40:38.551  5648  5695 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-22 11:40:38.551  5648  5695 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-22 11:40:38.551  5648  5695 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-22 11:40:38.551  5648  5695 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5e13342 not in the list
,11-22 11:40:38.554  5648  5695 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
11-22 11:40:38.554  5648  5695 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
11-22 11:40:38.554  5648  5695 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
11-22 11:40:38.554  5648  5695 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
,11-22 11:40:38.554  5648  5695 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
11-22 11:40:38.554  5648  5695 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
11-22 11:40:38.554  5648  5695 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
11-22 11:40:38.554  5648  5695 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
11-22 11:40:38.554  5648  5695 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
11-22 11:40:38.554  5648  5695 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
,11-22 11:40:38.554  5648  5695 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
11-22 11:40:38.554  5648  5695 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
11-22 11:40:38.554  5648  5695 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
11-22 11:40:38.554  5648  5695 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
11-22 11:40:38.554  5648  5695 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
11-22 11:40:38.554  5648  5695 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
11-22 11:40:38.554  5648  5695 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
11-22 11:40:38.554  5648  5695 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
11-22 11:40:38.554  5648  5695 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
11-22 11:40:38.554  5648  5695 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
,11-22 11:40:38.554  5648  5695 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
11-22 11:40:38.554  5648  5695 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
11-22 11:40:38.554  5648  5695 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
11-22 11:40:38.554  5648  5695 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
11-22 11:40:38.554  5648  5695 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
11-22 11:40:38.554  5648  5695 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
11-22 11:40:38.555  5648  5695 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
,11-22 11:40:38.555  5648  5695 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
11-22 11:40:38.555  5648  5695 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
11-22 11:40:38.555  5648  5695 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
11-22 11:40:38.555  5648  5695 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
11-22 11:40:38.555  5648  5695 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-22 11:40:38.555  5648  5695 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,11-22 11:40:38.555  5648  5695 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-22 11:40:38.555  5648  5695 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-22 11:40:38.555  5648  5695 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-22 11:40:38.555  5648  5695 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f10758d not in the list
11-22 11:40:38.555  5648  5695 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-22 11:40:38.555  5648  5695 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5e13342 not in the list
11-22 11:40:38.555  5648  5695 D io.jxcore.node.ConnectivityMonitor: stop
11-22 11:40:38.555  5648  5695 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-22 11:40:38.555  5648  5695 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-22 11:40:38.556  5648  5695 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-22 11:40:38.556  5648  5695 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-22 11:40:38.556  5648  5695 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-22 11:40:38.556  5648  5695 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,11-22 11:40:38.556  5648  5695 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-22 11:40:38.556  5648  5695 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5e13342 not in the list
11-22 11:40:38.556  5648  5695 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
11-22 11:40:38.557  5648  5695 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-22 11:40:38.557  5648  5695 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
11-22 11:40:38.566  5648  5695 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-22 11:40:38.566  5648  5695 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-22 11:40:38.566  5648  5695 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-22 11:40:38.566  5648  5695 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-22 11:40:38.566  5648  5695 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-22 11:40:38.566  5648  5695 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-22 11:40:38.566  5648  5695 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-22 11:40:38.566  5648  5695 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-22 11:40:38.566  5648  5695 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,11-22 11:40:38.567  5648  5695 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
11-22 11:40:38.567  5648  5695 D io.jxcore.node.ConnectivityMonitor: start: OK
11-22 11:40:38.567  5648  5695 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-22 11:40:38.567  5648  5695 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
11-22 11:40:38.567  5648  5695 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
11-22 11:40:38.567  5648  5695 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-22 11:40:38.568  5648  5695 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
11-22 11:40:38.572  5648  5695 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-22 11:40:38.572  5648  5695 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-22 11:40:38.573  5648  5695 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
11-22 11:40:38.574  5648  5648 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-22 11:40:38.576  5648  5695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-61,5,main], id: 61
11-22 11:40:38.577  5648  5695 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,11-22 11:40:38.579  5648  5648 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-22 11:40:38.580  5648  5695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-22 11:40:38.580  5648  5695 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,11-22 11:40:38.581  5648  5695 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
,11-22 11:40:38.582  5648  5695 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
11-22 11:40:38.582  5648  5695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-61,5,main], id: 61
,11-22 11:40:38.582  5648  5695 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
11-22 11:40:38.582  5648  5695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
11-22 11:40:38.582  5648  5695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
11-22 11:40:38.582  5648  5695 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
11-22 11:40:38.582  5648  5695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-61,5,main], id: 61
,11-22 11:40:38.583  5648  5695 D BluetoothAdapter: STATE_ON
11-22 11:40:38.585  4679  4890 D BtGatt.GattService: registerClient() - UUID=5e597f84-9f4a-4c81-aa8b-8cdec84259ea
11-22 11:40:38.586  4679  4750 D BtGatt.GattService: onClientRegistered() - UUID=5e597f84-9f4a-4c81-aa8b-8cdec84259ea, clientIf=5
,11-22 11:40:38.587  5648  5659 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
11-22 11:40:38.588  4679  4899 D BtGatt.GattService: start scan with filters
,11-22 11:40:38.593  5648  5695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
,11-22 11:40:38.593  4679  4758 D BtGatt.ScanManager: handling starting scan
11-22 11:40:38.593  5648  5695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-22 11:40:38.593  5648  5695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,11-22 11:40:38.593  5648  5695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-61,5,main], id: 61
11-22 11:40:38.593  5648  5695 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-22 11:40:38.594  5648  5648 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
,11-22 11:40:38.594  5648  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-22 11:40:38.594  5648  5695 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-22 11:40:38.595  5648  5695 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-22 11:40:38.595  4679  4758 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b3c7ab5
11-22 11:40:38.595  5648  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
11-22 11:40:38.595  5648  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-22 11:40:38.595  5648  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-22 11:40:38.595  5648  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
11-22 11:40:38.596  5648  5695 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-22 11:40:38.596  5648  5695 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-22 11:40:38.596  5648  5695 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
,11-22 11:40:38.596  5648  5648 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,11-22 11:40:38.596  5648  5648 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-22 11:40:38.597  5648  5695 I io.jxcore.node.ConnectionHelper: start: OK
11-22 11:40:38.600  5648  5648 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-22 11:40:38.600  5648  5648 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
11-22 11:40:38.600  5648  5648 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-22 11:40:38.600  5648  5648 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-22 11:40:38.600  5648  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
,11-22 11:40:38.600  5648  5648 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
11-22 11:40:38.603  4679  4750 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
11-22 11:40:38.603  4679  4750 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-22 11:40:38.603  4679  4758 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,11-22 11:40:38.610  4679  4750 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
,11-22 11:40:38.610  4679  4750 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-22 11:40:38.611  4679  4758 D BtGatt.ScanManager: Starting BLE batch scan
11-22 11:40:38.611  4679  4758 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,11-22 11:40:38.623  4679  4750 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,11-22 11:40:38.623  4679  4750 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-22 11:40:38.628  4679  4750 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
11-22 11:40:38.628  4679  4750 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-22 11:40:39.102  5648  5648 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
11-22 11:40:39.103  5648  5648 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,11-22 11:40:39.103  5648  5648 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,11-22 11:40:43.601  5648  5695 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-22 11:40:43.602  5648  5695 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,11-22 11:40:43.602  5648  5695 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
11-22 11:40:43.602  5648  5695 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,11-22 11:40:43.602  5648  5695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-22 11:40:43.602  5648  5695 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-22 11:40:43.602  5648  5695 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
11-22 11:40:43.602  5648  5695 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-22 11:40:43.602  5648  5695 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
11-22 11:40:43.602  5648  5695 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,11-22 11:40:43.603  5648  5695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
11-22 11:40:43.603  5648  5695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-61,5,main], id: 61
,11-22 11:40:43.603  5648  5695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-61,5,main], id: 61
,11-22 11:40:43.603  5648  5695 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,11-22 11:40:43.604  5648  5695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-61,5,main], id: 61
11-22 11:40:43.605  5648  5695 D BluetoothAdapter: STATE_ON
11-22 11:40:43.606  4679  4890 D BtGatt.GattService: stopScan() - queue size =1
11-22 11:40:43.608  4679  4899 D BtGatt.GattService: unregisterClient() - clientIf=5
11-22 11:40:43.610  5648  5695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-22 11:40:43.611  5648  5695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-22 11:40:43.612  5648  5695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
11-22 11:40:43.612  5648  5695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-61,5,main], id: 61
,11-22 11:40:43.612  5648  5695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-61,5,main], id: 61
11-22 11:40:43.613  5648  5695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-61,5,main], id: 61
11-22 11:40:43.613  5648  5695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-61,5,main], id: 61
11-22 11:40:43.615  5648  5695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,11-22 11:40:43.615  5648  5695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
,11-22 11:40:43.616  5648  5695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-61,5,main], id: 61
11-22 11:40:43.616  5648  5695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-61,5,main], id: 61
11-22 11:40:43.616  5648  5695 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-22 11:40:43.616  5648  5695 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-22 11:40:43.618  5648  5695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-22 11:40:43.618  5648  5695 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-22 11:40:43.623  5648  5695 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
,11-22 11:40:43.623  5648  5695 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-22 11:40:43.623  5648  5695 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-22 11:40:43.623  5648  5695 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-22 11:40:43.623  5648  5695 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-22 11:40:43.623  5648  5648 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,11-22 11:40:43.623  5648  5695 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-22 11:40:43.623  5648  5648 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-22 11:40:43.623  5648  5695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-22 11:40:43.623  5648  5695 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-22 11:40:43.623  5648  5648 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-22 11:40:43.623  5648  5695 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f10758d not in the list
11-22 11:40:43.623  5648  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-22 11:40:43.623  5648  5695 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-22 11:40:43.623  5648  5695 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5e13342 not in the list
11-22 11:40:43.624  5648  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-22 11:40:43.624  5648  5695 D io.jxcore.node.ConnectivityMonitor: stop
11-22 11:40:43.624  5648  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
11-22 11:40:43.624  5648  5695 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
11-22 11:40:43.624  5648  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-22 11:40:43.624  5648  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-22 11:40:43.624  5648  5648 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
11-22 11:40:43.624  5648  5648 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-22 11:40:43.626  5648  5648 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-22 11:40:43.626  5648  5648 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-22 11:40:43.626  5648  5648 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-22 11:40:43.626  5648  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-22 11:40:43.626  5648  5648 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,11-22 11:40:43.637  4679  4750 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
,11-22 11:40:43.638  4679  4750 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-22 11:40:43.638  4679  4758 D BtGatt.ScanManager: stopping BLe Batch
11-22 11:40:43.642  4679  4679 D BtGatt.ScanManager: awakened up at time 163310
,11-22 11:40:43.648  4679  4750 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,11-22 11:40:43.648  4679  4750 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-22 11:40:43.649  4679  4758 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-22 11:40:43.660  4679  4750 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=3
11-22 11:40:43.660  4679  4750 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-22 11:40:43.661  4679  4750 D BtGatt.GattService: current time is 163329523878
11-22 11:40:43.661  4679  4750 D BtGatt.GattService: Batch record : [116, -43, -111, -91, -20, -29, 1, -128, -84, 75, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 81, 34, 97, 112, -14, -5, 1, -128, -82, 71, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, -46, -4, -117, 6, 105, -37, 1, -128, -92, 71, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
11-22 11:40:43.662  4679  4750 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
11-22 11:40:43.663  4679  4750 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
11-22 11:40:43.663  4679  4750 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
,11-22 11:40:43.694  3998  5697 W CronetSyncConnectionRcs: Upload content type not set.
,11-22 11:40:43.709  3891  5699 I EventLogService: Aggregate from 1479809393571 (log), 1479809393571 (data)
,11-22 11:40:43.748  3612  5704 I VacuumService: Vacuum at: now=1479811243748 tag=VacuumService
,11-22 11:40:43.793  3612  5708 D GetConfigurationSnapshotOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,11-22 11:40:43.820  3612  5705 I PhenotypeFlagCommitter: Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,11-22 11:40:43.823  3612  5705 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,11-22 11:40:43.846  3612  5705 W Uploader:  no longer exists, so no auth token.
,11-22 11:40:43.852  3612  5708 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,11-22 11:40:43.948   544   544 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 11:40:44.127  5648  5648 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-22 11:40:44.531  3612  5715 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,11-22 11:40:44.698  3612  5716 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,11-22 11:40:44.764  3612  5705 W Uploader:  no longer exists, so no auth token.
,11-22 11:40:44.775  3612  5715 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,11-22 11:40:44.850  3612  5716 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,11-22 11:40:44.932  3612  5715 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,11-22 11:40:44.949   544   544 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 11:40:45.950   544   544 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 11:40:46.951   544   544 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 11:40:47.952   544   544 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 11:40:48.637  5648  5695 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,11-22 11:40:48.644  5648  5695 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,11-22 11:40:48.645  5648  5695 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
,11-22 11:40:48.660  5648  5695 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-22 11:40:48.660  5648  5695 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-22 11:40:48.660  5648  5695 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-22 11:40:48.660  5648  5695 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-22 11:40:48.660  5648  5695 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-22 11:40:48.660  5648  5695 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-22 11:40:48.660  5648  5695 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-22 11:40:48.660  5648  5695 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-22 11:40:48.660  5648  5695 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,11-22 11:40:48.663  5648  5695 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
,11-22 11:40:48.663  5648  5695 D io.jxcore.node.ConnectivityMonitor: start: OK
11-22 11:40:48.664  5648  5695 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-22 11:40:48.664  5648  5695 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
11-22 11:40:48.664  5648  5695 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
11-22 11:40:48.664  5648  5695 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-22 11:40:48.664  5648  5695 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,11-22 11:40:48.669  5648  5648 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-22 11:40:48.671  5648  5695 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
,11-22 11:40:48.671  5648  5695 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-22 11:40:48.671  5648  5695 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,11-22 11:40:48.674  5648  5648 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-22 11:40:48.678  5648  5695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-61,5,main], id: 61
11-22 11:40:48.678  5648  5695 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-22 11:40:48.680  5648  5695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-22 11:40:48.680  5648  5695 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,11-22 11:40:48.683  5648  5695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-61,5,main], id: 61
,11-22 11:40:48.683  5648  5695 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
11-22 11:40:48.683  5648  5695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
11-22 11:40:48.683  5648  5695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
11-22 11:40:48.683  5648  5695 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
11-22 11:40:48.683  5648  5695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-61,5,main], id: 61
11-22 11:40:48.685  5648  5695 D BluetoothAdapter: STATE_ON
,11-22 11:40:48.688  4679  4890 D BtGatt.GattService: registerClient() - UUID=e829f1c5-66ee-4d20-a104-8e41daed76f9
,11-22 11:40:48.688  4679  4750 D BtGatt.GattService: onClientRegistered() - UUID=e829f1c5-66ee-4d20-a104-8e41daed76f9, clientIf=5
,11-22 11:40:48.689  5648  5658 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,11-22 11:40:48.689  4679  4899 D BtGatt.GattService: start scan with filters
11-22 11:40:48.692  5648  5695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
11-22 11:40:48.692  4679  4758 D BtGatt.ScanManager: handling starting scan
,11-22 11:40:48.692  5648  5695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-22 11:40:48.692  5648  5695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
11-22 11:40:48.692  5648  5695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-61,5,main], id: 61
11-22 11:40:48.692  5648  5695 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-22 11:40:48.693  5648  5648 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-22 11:40:48.693  5648  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-22 11:40:48.693  5648  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
11-22 11:40:48.693  5648  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-22 11:40:48.693  5648  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-22 11:40:48.693  5648  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
11-22 11:40:48.693  5648  5648 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
11-22 11:40:48.694  5648  5695 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-22 11:40:48.694  5648  5695 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-22 11:40:48.697  5648  5695 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-22 11:40:48.697  5648  5695 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
11-22 11:40:48.697  5648  5695 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-22 11:40:48.697  5648  5695 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-22 11:40:48.697  5648  5695 I io.jxcore.node.ConnectionHelper: start: OK
11-22 11:40:48.697  5648  5648 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
,11-22 11:40:48.699  4679  4750 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,11-22 11:40:48.699  4679  4750 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-22 11:40:48.699  4679  4758 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,11-22 11:40:48.700  5648  5648 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-22 11:40:48.700  5648  5648 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
,11-22 11:40:48.700  5648  5648 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-22 11:40:48.700  5648  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-22 11:40:48.700  5648  5648 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,11-22 11:40:48.702  5648  5695 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-22 11:40:48.702  5648  5695 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
11-22 11:40:48.702  5648  5695 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
11-22 11:40:48.702  5648  5695 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,11-22 11:40:48.703  5648  5695 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-22 11:40:48.703  5648  5695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-22 11:40:48.703  5648  5695 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,11-22 11:40:48.703  5648  5695 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
11-22 11:40:48.703  5648  5695 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,11-22 11:40:48.703  5648  5695 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
11-22 11:40:48.703  5648  5695 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-22 11:40:48.703  5648  5695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
,11-22 11:40:48.703  5648  5695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-61,5,main], id: 61
11-22 11:40:48.703  5648  5695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-22 11:40:48.703  5648  5695 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
11-22 11:40:48.703  5648  5695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-61,5,main], id: 61
11-22 11:40:48.704  5648  5695 D BluetoothAdapter: STATE_ON
11-22 11:40:48.705  4679  4890 D BtGatt.GattService: stopScan() - queue size =1
11-22 11:40:48.705  4679  4750 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
11-22 11:40:48.705  4679  4750 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-22 11:40:48.705  4679  4758 D BtGatt.ScanManager: Starting BLE batch scan
11-22 11:40:48.705  4679  4758 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
11-22 11:40:48.705  4679  4696 D BtGatt.GattService: unregisterClient() - clientIf=5
11-22 11:40:48.706  5648  5695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-22 11:40:48.706  5648  5695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
,11-22 11:40:48.706  5648  5695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
11-22 11:40:48.706  5648  5695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-61,5,main], id: 61
11-22 11:40:48.706  5648  5695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-61,5,main], id: 61
11-22 11:40:48.706  5648  5695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-61,5,main], id: 61
11-22 11:40:48.706  5648  5695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-61,5,main], id: 61
11-22 11:40:48.706  5648  5695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-22 11:40:48.706  5648  5695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
11-22 11:40:48.706  5648  5695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-61,5,main], id: 61
11-22 11:40:48.706  5648  5695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-61,5,main], id: 61
,11-22 11:40:48.706  5648  5695 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-22 11:40:48.706  5648  5695 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-22 11:40:48.707  5648  5695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-22 11:40:48.707  5648  5695 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-22 11:40:48.708  5648  5695 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-22 11:40:48.708  5648  5695 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-22 11:40:48.708  5648  5695 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-22 11:40:48.708  5648  5695 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-22 11:40:48.708  5648  5648 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-22 11:40:48.708  5648  5695 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,11-22 11:40:48.708  5648  5695 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-22 11:40:48.708  5648  5648 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-22 11:40:48.708  5648  5695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-22 11:40:48.708  5648  5695 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-22 11:40:48.708  5648  5648 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-22 11:40:48.708  5648  5695 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f10758d not in the list
11-22 11:40:48.708  5648  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-22 11:40:48.708  5648  5695 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-22 11:40:48.708  5648  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-22 11:40:48.708  5648  5695 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5e13342 not in the list
,11-22 11:40:48.708  5648  5695 D io.jxcore.node.ConnectivityMonitor: stop
11-22 11:40:48.708  5648  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
11-22 11:40:48.709  5648  5695 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
11-22 11:40:48.709  5648  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-22 11:40:48.709  5648  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-22 11:40:48.709  5648  5648 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
11-22 11:40:48.709  5648  5648 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-22 11:40:48.716  4679  4750 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
11-22 11:40:48.716  4679  4750 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-22 11:40:48.717  5648  5648 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-22 11:40:48.717  5648  5648 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-22 11:40:48.717  5648  5648 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-22 11:40:48.717  5648  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-22 11:40:48.717  5648  5648 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-22 11:40:48.717  5648  5695 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-22 11:40:48.721  5648  5695 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-22 11:40:48.721  5648  5695 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-22 11:40:48.721  5648  5695 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-22 11:40:48.721  5648  5695 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-22 11:40:48.721  5648  5695 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-22 11:40:48.721  5648  5695 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-22 11:40:48.721  5648  5695 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5e13342 not in the list
,11-22 11:40:48.722  5648  5695 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
11-22 11:40:48.722  4679  4750 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
11-22 11:40:48.722  4679  4750 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-22 11:40:48.724  5648  5695 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-22 11:40:48.724  5648  5695 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
,11-22 11:40:48.728   928  5404 D NetlinkSocketObserver: NeighborEvent{elapsedMs=168396, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,11-22 11:40:48.730  5648  5695 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-22 11:40:48.730  5648  5695 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-22 11:40:48.730  5648  5695 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-22 11:40:48.730  5648  5695 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-22 11:40:48.730  5648  5695 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-22 11:40:48.730  5648  5695 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-22 11:40:48.730  5648  5695 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-22 11:40:48.730  5648  5695 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-22 11:40:48.730  5648  5695 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,11-22 11:40:48.732  4679  4750 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
11-22 11:40:48.732  4679  4750 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-22 11:40:48.732  4679  4758 D BtGatt.ScanManager: stopping BLe Batch
,11-22 11:40:48.732  5648  5695 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
11-22 11:40:48.732  5648  5695 D io.jxcore.node.ConnectivityMonitor: start: OK
11-22 11:40:48.732  5648  5695 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-22 11:40:48.732  5648  5695 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
11-22 11:40:48.733  5648  5695 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,11-22 11:40:48.733  5648  5695 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-22 11:40:48.733  5648  5695 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,11-22 11:40:48.736  5648  5695 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
,11-22 11:40:48.736  5648  5695 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-22 11:40:48.736  5648  5695 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
11-22 11:40:48.736  5648  5648 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-22 11:40:48.739  4679  4750 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
11-22 11:40:48.739  4679  4750 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-22 11:40:48.739  4679  4758 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
11-22 11:40:48.740  5648  5648 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-22 11:40:48.740  5648  5695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-61,5,main], id: 61
11-22 11:40:48.740  5648  5695 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,11-22 11:40:48.741  5648  5695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-22 11:40:48.741  5648  5695 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-22 11:40:48.745  4679  4750 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-22 11:40:48.745  4679  4750 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-22 11:40:48.745  5648  5695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-22 11:40:48.746  5648  5695 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
11-22 11:40:48.746  5648  5695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
11-22 11:40:48.746  5648  5695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
11-22 11:40:48.746  5648  5695 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
11-22 11:40:48.746  5648  5695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-61,5,main], id: 61
,11-22 11:40:48.747  5648  5695 D BluetoothAdapter: STATE_ON
11-22 11:40:48.749  4679  4696 D BtGatt.GattService: registerClient() - UUID=41f16aa2-3667-403b-a71c-cc2c5f95a8e5
11-22 11:40:48.749  4679  4750 D BtGatt.GattService: onClientRegistered() - UUID=41f16aa2-3667-403b-a71c-cc2c5f95a8e5, clientIf=5
11-22 11:40:48.749  5648  5659 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
11-22 11:40:48.750  4679  4899 D BtGatt.GattService: start scan with filters
11-22 11:40:48.752  5648  5695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
11-22 11:40:48.752  5648  5695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-22 11:40:48.752  5648  5695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
11-22 11:40:48.752  4679  4758 D BtGatt.ScanManager: handling starting scan
11-22 11:40:48.752  5648  5695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-61,5,main], id: 61
11-22 11:40:48.752  5648  5695 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-22 11:40:48.752  5648  5648 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-22 11:40:48.752  5648  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-22 11:40:48.752  5648  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
11-22 11:40:48.752  5648  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-22 11:40:48.752  5648  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-22 11:40:48.752  5648  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
11-22 11:40:48.752  5648  5648 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
11-22 11:40:48.753  5648  5695 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-22 11:40:48.753  5648  5695 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-22 11:40:48.755  5648  5695 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-22 11:40:48.756  5648  5695 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,11-22 11:40:48.756  5648  5695 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-22 11:40:48.756  5648  5695 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-22 11:40:48.756  5648  5695 I io.jxcore.node.ConnectionHelper: start: OK
11-22 11:40:48.756  5648  5648 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-22 11:40:48.758  4679  4750 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
11-22 11:40:48.758  4679  4750 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-22 11:40:48.758  5648  5648 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-22 11:40:48.758  5648  5648 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-22 11:40:48.758  5648  5648 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-22 11:40:48.759  5648  5648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-22 11:40:48.759  5648  5648 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
11-22 11:40:48.759  4679  4758 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
11-22 11:40:48.763  4679  4750 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
,11-22 11:40:48.763  4679  4750 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-22 11:40:48.763  4679  4758 D BtGatt.ScanManager: Starting BLE batch scan
11-22 11:40:48.763  4679  4758 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,11-22 11:40:48.770  4679  4750 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,11-22 11:40:48.770  4679  4750 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-22 11:40:48.775  4679  4750 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,11-22 11:40:48.775  4679  4750 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-22 11:40:48.952   544   544 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,11-22 11:40:49.260  5648  5648 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
11-22 11:40:49.260  5648  5648 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
11-22 11:40:49.260  5648  5648 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed

```
