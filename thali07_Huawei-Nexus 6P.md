#### Test 914795748cc43db_thali07_Huawei-Nexus 6P Logs


```
--------- beginning of main
11-03 23:34:26.407  4006  4233 I Icing   : Indexing 3C763AF371F9E97B4ECFEA01A338ADB468C38476 from com.google.android.googlequicksearchbox
,11-03 23:34:26.487  4006  4233 I Icing   : Indexing done 3C763AF371F9E97B4ECFEA01A338ADB468C38476
11-03 23:34:26.879  5563  5563 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
11-03 23:34:26.885  5563  5563 D AndroidRuntime: CheckJNI is OFF
11-03 23:34:26.913  5563  5563 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
11-03 23:34:26.946  5563  5563 I Radio-JNI: register_android_hardware_Radio DONE
11-03 23:34:26.961  5563  5563 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
11-03 23:34:26.965   928  3796 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
11-03 23:34:26.986  5563  5563 D AndroidRuntime: Shutting down VM
11-03 23:34:26.993  3947  3965 W SearchService: Abort, client detached.
11-03 23:34:26.999  3947  3947 I HotwordDetector: Closing mic
11-03 23:34:27.000  3947  4210 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@3aafabc
11-03 23:34:27.001  3947  4226 E AudioRecord-JNI: Error -4 during AudioRecord native read
11-03 23:34:27.021   928  3435 I ActivityManager: Start proc 5572:com.test.thalitest/u0a77 for activity com.test.thalitest/.MainActivity
11-03 23:34:27.077   512  4231 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
11-03 23:34:27.078   512  4231 D audio_hw_primary: disable_snd_device: snd_device(63: voice-rec-mic)
11-03 23:34:27.084   512  4231 I soundtrigger: audio_extn_sound_trigger_update_device_status: device 0x3f of type 1 for Event 0
11-03 23:34:27.085   512  4231 D sound_trigger_platform: platform_stdev_check_and_update_concurrency: concurrency active 0, tx 0, rx 0, concurrency session_allowed 1
11-03 23:34:27.085   512  3006 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
11-03 23:34:27.088  3947  4223 I MicroRecognitionRnrImpl: Detection finished
11-03 23:34:27.090  3947  4211 I MicroRecognitionRnrImpl: Stopping hotword detection.
11-03 23:34:27.117  5572  5572 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011750)
11-03 23:34:27.140  5572  5572 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
11-03 23:34:27.204  5572  5572 I LibraryLoader: Time to load native libraries: 60 ms (timestamps 579-639)
11-03 23:34:27.205  5572  5572 I LibraryLoader: Expected native library version number "",actual native library version number ""
,11-03 23:34:27.239  5572  5572 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {62df38c}
,11-03 23:34:27.240  5572  5572 I LibraryLoader: Expected native library version number "",actual native library version number ""
11-03 23:34:27.240  5572  5572 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
11-03 23:34:27.245  5572  5572 I BrowserStartupController: Initializing chromium process, singleProcess=true
11-03 23:34:27.246  5572  5572 E SysUtils: ApplicationContext is null in ApplicationStatus
,11-03 23:34:27.289  5572  5572 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,11-03 23:34:27.301  5572  5572 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,11-03 23:34:27.301  5572  5572 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
11-03 23:34:27.301  5572  5572 I Adreno  : QUALCOMM build                   : 63c06b2, I8366cd0437
11-03 23:34:27.301  5572  5572 I Adreno  : Build Date                       : 12/06/15
11-03 23:34:27.301  5572  5572 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
11-03 23:34:27.301  5572  5572 I Adreno  : Local Branch                     : mybranch17112971
11-03 23:34:27.301  5572  5572 I Adreno  : Remote Branch                    : quic/LA.BF64.1.2.9_v2
11-03 23:34:27.301  5572  5572 I Adreno  : Remote Branch                    : NONE
11-03 23:34:27.301  5572  5572 I Adreno  : Reconstruct Branch               : NOTHING
,11-03 23:34:27.347   928   945 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@d2e4d07:true
,11-03 23:34:27.379  3051  3051 W Binder_5: type=1400 audit(0.0:99): avc: denied { ioctl } for path="socket:[14206]" dev="sockfs" ino=14206 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
11-03 23:34:27.379  3051  3051 W Binder_5: type=1400 audit(0.0:100): avc: denied { ioctl } for path="socket:[14206]" dev="sockfs" ino=14206 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-03 23:34:27.392  5572  5572 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,11-03 23:34:27.401  5572  5572 D SystemWebViewEngine: CordovaWebView is running on device made by: Huawei
,11-03 23:34:27.425  5572  5609 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,11-03 23:34:27.423  3050  3050 W Binder_4: type=1400 audit(0.0:101): avc: denied { ioctl } for path="socket:[31967]" dev="sockfs" ino=31967 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
11-03 23:34:27.423  3050  3050 W Binder_4: type=1400 audit(0.0:102): avc: denied { ioctl } for path="socket:[31967]" dev="sockfs" ino=31967 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-03 23:34:27.423  3812  3812 W Binder_B: type=1400 audit(0.0:103): avc: denied { ioctl } for path="socket:[20385]" dev="sockfs" ino=20385 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-03 23:34:27.429  5572  5596 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
11-03 23:34:27.426  3812  3812 W Binder_B: type=1400 audit(0.0:104): avc: denied { ioctl } for path="socket:[20385]" dev="sockfs" ino=20385 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-03 23:34:27.458  5572  5609 I OpenGLRenderer: Initialized EGL, version 1.4
,11-03 23:34:27.471   928  2958 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-03 23:34:27.533  3167  3167 W Binder_4: type=1400 audit(0.0:105): avc: denied { ioctl } for path="socket:[31512]" dev="sockfs" ino=31512 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-03 23:34:27.533  3167  3167 W Binder_4: type=1400 audit(0.0:106): avc: denied { ioctl } for path="socket:[31512]" dev="sockfs" ino=31512 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-03 23:34:27.537   928   946 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +535ms
,11-03 23:34:27.539   939   939 W Binder_2: type=1400 audit(0.0:107): avc: denied { ioctl } for path="socket:[31511]" dev="sockfs" ino=31511 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-03 23:34:27.539   939   939 W Binder_2: type=1400 audit(0.0:108): avc: denied { ioctl } for path="socket:[31511]" dev="sockfs" ino=31511 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
11-03 23:34:27.542  3651  3651 I Keyboard.Facilitator: onFinishInput()
,11-03 23:34:27.563  5572  5572 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 5572
,11-03 23:34:27.645  5572  5572 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,11-03 23:34:27.801  5572  5612 D jxcore_app_log: JniHelper::setJavaVM(0xf4efc000), pthread_self() = -588510928
,11-03 23:34:27.807  5572  5612 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
11-03 23:34:27.807  5572  5612 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
11-03 23:34:27.807  5572  5612 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
11-03 23:34:27.807  5572  5612 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
11-03 23:34:27.807  5572  5612 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
11-03 23:34:27.807  5572  5612 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@83cf402 added. We now have 1 listener(s)
,11-03 23:34:27.809  5572  5612 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 60:83:34:25:D7:D4
,11-03 23:34:27.809  5572  5612 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-03 23:34:27.810  5572  5612 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-03 23:34:27.810  5572  5612 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,11-03 23:34:27.812  5572  5612 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
11-03 23:34:27.812  5572  5612 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
11-03 23:34:27.812  5572  5612 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
11-03 23:34:27.812  5572  5612 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 60:83:34:25:D7:D4
11-03 23:34:27.812  5572  5612 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
11-03 23:34:27.812  5572  5612 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
11-03 23:34:27.812  5572  5612 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
11-03 23:34:27.812  5572  5612 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
11-03 23:34:27.812  5572  5612 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
11-03 23:34:27.812  5572  5612 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
11-03 23:34:27.812  5572  5612 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
11-03 23:34:27.812  5572  5612 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
11-03 23:34:27.812  5572  5612 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
11-03 23:34:27.812  5572  5612 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,11-03 23:34:27.812  5572  5612 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@38a4e4e added. We now have 1 listener(s)
11-03 23:34:27.812  5572  5612 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-03 23:34:27.817   928  2959 D WifiService: New client listening to asynchronous messages
,11-03 23:34:27.818  5572  5612 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
11-03 23:34:27.818  5572  5612 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
,11-03 23:34:27.818  5572  5612 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[JavaBridge,5,main], id: 55
11-03 23:34:27.818  5572  5612 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
11-03 23:34:27.818  5572  5612 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
,11-03 23:34:27.818  5572  5612 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
11-03 23:34:27.818  5572  5612 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[JavaBridge,5,main], id: 55
11-03 23:34:27.820  5572  5612 I io.jxcore.node.LifeCycleMonitor: start: OK
,11-03 23:34:27.938  5572  5572 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,11-03 23:34:28.386  5572  5619 W jxcore-log: Initializing JXcore engine
,11-03 23:34:28.386  5572  5619 W jxcore-log: JXcore engine is ready
,11-03 23:34:28.409  5619  5619 W Thread-61: type=1400 audit(0.0:109): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=1305 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,11-03 23:34:28.409  5619  5619 W Thread-61: type=1400 audit(0.0:110): avc: denied { ioctl } for path="socket:[10789]" dev="sockfs" ino=10789 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
11-03 23:34:28.409  5619  5619 W Thread-61: type=1400 audit(0.0:111): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=6259 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,11-03 23:34:28.409  5619  5619 W Thread-61: type=1400 audit(0.0:112): avc: denied { ioctl } for path="socket:[28460]" dev="sockfs" ino=28460 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:untrusted_app:s0:c512,c768 tclass=netlink_route_socket permissive=0
,11-03 23:34:28.419  5572  5619 W jxcore-log: Starting JXcore engine
,11-03 23:34:28.469  5572  5619 W jxcore-log: Platform android
11-03 23:34:28.469  5572  5619 W jxcore-log: 
,11-03 23:34:28.469  5572  5619 W jxcore-log: Process ARCH arm
11-03 23:34:28.469  5572  5619 W jxcore-log: 
,11-03 23:34:28.643  5572  5619 I jxcore-log: JXcore Cordova bridge is ready!
11-03 23:34:28.643  5572  5619 I jxcore-log: 
11-03 23:34:28.643  5572  5619 W jxcore-log: JXcore engine is started
,11-03 23:34:28.652  5572  5612 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,11-03 23:34:28.659  5572  5572 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,11-03 23:34:30.100   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-03 23:34:30.708  3596  3596 I ConfigService: onDestroy
,11-03 23:34:31.101   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-03 23:34:32.008   928  3812 I ActivityManager: Killing 5217:org.codeaurora.ims/1001 (adj 15): empty #17
,11-03 23:34:32.051   928  3812 I ActivityManager: Killing 5129:com.google.android.youtube/u0a75 (adj 15): empty #18
,11-03 23:34:32.101   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-03 23:34:33.102   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-03 23:34:34.103   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-03 23:34:35.104   535   535 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,11-03 23:34:38.233  5572  5619 I jxcore-log: 2016-11-03 22:34:38 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
11-03 23:34:38.233  5572  5619 I jxcore-log: 
,11-03 23:34:38.235  5572  5619 I jxcore-log: 2016-11-03 22:34:38 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
11-03 23:34:38.235  5572  5619 I jxcore-log: 
,11-03 23:34:38.240  5572  5619 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,11-03 23:34:38.240  5572  5619 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-03 23:34:38.240  5572  5619 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-03 23:34:38.240  5572  5619 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-03 23:34:38.240  5572  5619 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-03 23:34:38.240  5572  5619 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-03 23:34:38.240  5572  5619 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-03 23:34:38.240  5572  5619 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-03 23:34:38.240  5572  5619 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,11-03 23:34:38.242  5572  5619 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
11-03 23:34:38.244  5572  5619 I jxcore-log: 2016-11-03 22:34:38 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
11-03 23:34:38.244  5572  5619 I jxcore-log: 
,11-03 23:34:38.246  5572  5619 I jxcore-log: 2016-11-03 22:34:38 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
11-03 23:34:38.246  5572  5619 I jxcore-log: 
,11-03 23:34:38.492  5572  5619 I jxcore-log: 2016-11-03 22:34:38 - DEBUG UnitTest_app: 'Running unit tests'
11-03 23:34:38.492  5572  5619 I jxcore-log: 
,11-03 23:34:38.493  5572  5619 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,11-03 23:34:38.493  5572  5619 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@34b8b2c added. We now have 2 listener(s)
11-03 23:34:38.494  5572  5619 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-03 23:34:38.494  5572  5619 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-03 23:34:38.494  5572  5619 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,11-03 23:34:38.494  5572  5619 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-03 23:34:38.494  5572  5619 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b99d9f5 added. We now have 2 listener(s)
,11-03 23:34:38.494  5572  5619 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-03 23:34:38.495  5572  5619 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,11-03 23:34:38.496  5572  5619 D executeNativeTests: Running unit tests
,11-03 23:34:38.534  5572  5619 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,11-03 23:34:38.535  5572  5619 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c39033a added. We now have 3 listener(s)
11-03 23:34:38.535  5572  5619 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-03 23:34:38.535  5572  5619 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-03 23:34:38.535  5572  5619 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,11-03 23:34:38.535  5572  5619 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-03 23:34:38.535  5572  5619 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c1e3beb added. We now have 3 listener(s)
11-03 23:34:38.535  5572  5619 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-03 23:34:38.536  5572  5619 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,11-03 23:34:38.538  5572  5619 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,11-03 23:34:38.538  5572  5619 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,11-03 23:34:38.538  5572  5619 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,11-03 23:34:38.538  5572  5619 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,11-03 23:34:38.538  5572  5619 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
11-03 23:34:38.539  5572  5619 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
11-03 23:34:38.539  5572  5619 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
11-03 23:34:38.539  5572  5619 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-03 23:34:38.539  5572  5619 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-03 23:34:38.539  5572  5619 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-03 23:34:38.539  5572  5619 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-03 23:34:38.539  5572  5619 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-03 23:34:38.539  5572  5619 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,11-03 23:34:38.539  5572  5619 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-03 23:34:38.540  5572  5619 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-03 23:34:38.540  5572  5619 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-03 23:34:38.540  5572  5619 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c39033a removed from the list
11-03 23:34:38.540  5572  5619 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-03 23:34:38.540  5572  5619 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c1e3beb removed from the list
11-03 23:34:38.540  5572  5619 D io.jxcore.node.ConnectivityMonitor: stop
11-03 23:34:38.540  5572  5619 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-03 23:34:38.541  5572  5619 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-03 23:34:38.541  5572  5619 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-03 23:34:38.541  5572  5619 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-03 23:34:38.541  5572  5619 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-03 23:34:38.541  5572  5619 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-03 23:34:38.541  5572  5619 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-03 23:34:38.541  5572  5619 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c1e3beb not in the list
11-03 23:34:38.542  5572  5619 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
11-03 23:34:38.542  5572  5619 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-03 23:34:38.542  5572  5619 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-03 23:34:38.542  5572  5619 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,11-03 23:34:38.542  5572  5619 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-03 23:34:38.543  5572  5619 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-03 23:34:38.543  5572  5619 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c39033a not in the list
11-03 23:34:38.543  5572  5619 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-03 23:34:38.543  5572  5619 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c1e3beb not in the list
11-03 23:34:38.543  5572  5619 D io.jxcore.node.ConnectivityMonitor: stop
11-03 23:34:38.543  5572  5619 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-03 23:34:38.543  5572  5619 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-03 23:34:38.543  5572  5619 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-03 23:34:38.543  5572  5619 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-03 23:34:38.543  5572  5619 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-03 23:34:38.543  5572  5619 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-03 23:34:38.543  5572  5619 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-03 23:34:38.543  5572  5619 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c1e3beb not in the list
11-03 23:34:38.546  5572  5619 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
11-03 23:34:38.546  5572  5619 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
11-03 23:34:38.546  5572  5619 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
11-03 23:34:38.546  5572  5619 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
11-03 23:34:38.546  5572  5619 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
,11-03 23:34:38.546  5572  5619 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
11-03 23:34:38.546  5572  5619 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
11-03 23:34:38.546  5572  5619 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
11-03 23:34:38.546  5572  5619 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
11-03 23:34:38.546  5572  5619 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
11-03 23:34:38.546  5572  5619 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
11-03 23:34:38.546  5572  5619 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
,11-03 23:34:38.546  5572  5619 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
11-03 23:34:38.546  5572  5619 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
11-03 23:34:38.546  5572  5619 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
11-03 23:34:38.546  5572  5619 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
11-03 23:34:38.546  5572  5619 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
11-03 23:34:38.546  5572  5619 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
11-03 23:34:38.546  5572  5619 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
11-03 23:34:38.546  5572  5619 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
11-03 23:34:38.546  5572  5619 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
11-03 23:34:38.546  5572  5619 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
11-03 23:34:38.546  5572  5619 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
11-03 23:34:38.546  5572  5619 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
11-03 23:34:38.546  5572  5619 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
11-03 23:34:38.546  5572  5619 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
11-03 23:34:38.546  5572  5619 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
,11-03 23:34:38.547  5572  5619 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
11-03 23:34:38.547  5572  5619 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
11-03 23:34:38.547  5572  5619 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
,11-03 23:34:38.547  5572  5619 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
11-03 23:34:38.547  5572  5619 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-03 23:34:38.547  5572  5619 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-03 23:34:38.547  5572  5619 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-03 23:34:38.547  5572  5619 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-03 23:34:38.547  5572  5619 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,11-03 23:34:38.547  5572  5619 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c39033a not in the list
11-03 23:34:38.547  5572  5619 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-03 23:34:38.547  5572  5619 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c1e3beb not in the list
,11-03 23:34:38.547  5572  5619 D io.jxcore.node.ConnectivityMonitor: stop
11-03 23:34:38.547  5572  5619 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-03 23:34:38.548  5572  5619 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-03 23:34:38.548  5572  5619 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-03 23:34:38.548  5572  5619 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-03 23:34:38.548  5572  5619 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,11-03 23:34:38.548  5572  5619 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-03 23:34:38.548  5572  5619 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-03 23:34:38.548  5572  5619 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c1e3beb not in the list
11-03 23:34:38.548  5572  5619 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
11-03 23:34:38.549  5572  5619 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-03 23:34:38.549  5572  5619 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
11-03 23:34:38.562  5572  5619 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-03 23:34:38.562  5572  5619 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-03 23:34:38.562  5572  5619 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-03 23:34:38.562  5572  5619 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-03 23:34:38.562  5572  5619 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-03 23:34:38.562  5572  5619 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-03 23:34:38.562  5572  5619 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-03 23:34:38.562  5572  5619 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,11-03 23:34:38.563  5572  5619 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
11-03 23:34:38.563  5572  5619 D io.jxcore.node.ConnectivityMonitor: start: OK
11-03 23:34:38.563  5572  5619 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-03 23:34:38.563  5572  5619 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,11-03 23:34:38.563  5572  5619 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
11-03 23:34:38.563  5572  5619 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-03 23:34:38.563  5572  5619 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
11-03 23:34:38.565  5572  5619 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
,11-03 23:34:38.565  5572  5619 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-03 23:34:38.565  5572  5619 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,11-03 23:34:38.568  5572  5572 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-03 23:34:38.572  5572  5572 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-03 23:34:38.573  5572  5619 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-61,5,main], id: 61
11-03 23:34:38.573  5572  5619 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-03 23:34:38.575  5572  5619 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,11-03 23:34:38.576  5572  5619 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-03 23:34:38.576  5572  5619 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 0
11-03 23:34:38.579  5572  5619 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
11-03 23:34:38.582  5572  5619 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
,11-03 23:34:38.582  5572  5619 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-03 23:34:38.582  5572  5619 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,11-03 23:34:38.582  5572  5619 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
11-03 23:34:38.582  5572  5619 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
,11-03 23:34:38.583  5572  5619 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
11-03 23:34:38.584  5572  5619 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-61,5,main], id: 61
11-03 23:34:38.584  5572  5619 D BluetoothAdapter: STATE_ON
11-03 23:34:38.586  4675  4686 D BtGatt.GattService: registerClient() - UUID=35d26e14-5a91-460c-9227-9722c892bd1d
,11-03 23:34:38.587  4675  4747 D BtGatt.GattService: onClientRegistered() - UUID=35d26e14-5a91-460c-9227-9722c892bd1d, clientIf=5
,11-03 23:34:38.588  5572  5583 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
11-03 23:34:38.589  4675  4872 D BtGatt.GattService: start scan with filters
,11-03 23:34:38.594  5572  5619 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
,11-03 23:34:38.594  4675  4750 D BtGatt.ScanManager: handling starting scan
11-03 23:34:38.594  5572  5619 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-03 23:34:38.594  5572  5619 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
11-03 23:34:38.595  5572  5619 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-61,5,main], id: 61
,11-03 23:34:38.595  5572  5619 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-03 23:34:38.595  5572  5572 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-03 23:34:38.595  5572  5572 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-03 23:34:38.595  5572  5572 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
,11-03 23:34:38.595  5572  5572 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
,11-03 23:34:38.595  5572  5572 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-03 23:34:38.595  5572  5619 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-03 23:34:38.596  5572  5619 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-03 23:34:38.596  5572  5572 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
11-03 23:34:38.596  5572  5572 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
11-03 23:34:38.597  4675  4750 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@38588b7
11-03 23:34:38.598  5572  5619 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-03 23:34:38.598  5572  5619 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
,11-03 23:34:38.598  5572  5619 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-03 23:34:38.598  5572  5572 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-03 23:34:38.599  5572  5619 I io.jxcore.node.ConnectionHelper: start: OK
,11-03 23:34:38.601  5572  5572 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-03 23:34:38.601  5572  5572 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,11-03 23:34:38.602  5572  5572 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-03 23:34:38.602  5572  5572 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-03 23:34:38.602  5572  5572 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-03 23:34:38.602  5572  5572 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,11-03 23:34:38.605  4675  4747 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
11-03 23:34:38.605  4675  4747 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-03 23:34:38.606  4675  4750 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,11-03 23:34:38.612  4675  4747 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
11-03 23:34:38.612  4675  4747 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-03 23:34:38.612  4675  4750 D BtGatt.ScanManager: Starting BLE batch scan
11-03 23:34:38.612  4675  4750 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,11-03 23:34:38.622  4675  4747 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,11-03 23:34:38.623  4675  4747 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-03 23:34:38.628  4675  4747 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
11-03 23:34:38.628  4675  4747 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-03 23:34:39.103  5572  5572 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
11-03 23:34:39.104  5572  5572 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,11-03 23:34:39.104  5572  5572 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,11-03 23:34:43.608  5572  5619 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-03 23:34:43.608  5572  5619 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
11-03 23:34:43.608  5572  5619 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
11-03 23:34:43.609  5572  5619 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-03 23:34:43.609  5572  5619 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,11-03 23:34:43.609  5572  5619 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-03 23:34:43.609  5572  5619 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,11-03 23:34:43.609  5572  5619 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-03 23:34:43.610  5572  5619 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
11-03 23:34:43.610  5572  5619 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,11-03 23:34:43.612  5572  5619 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
11-03 23:34:43.613  5572  5619 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-61,5,main], id: 61
11-03 23:34:43.613  5572  5619 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-03 23:34:43.613  5572  5619 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
11-03 23:34:43.614  5572  5619 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-61,5,main], id: 61
11-03 23:34:43.616  5572  5619 D BluetoothAdapter: STATE_ON
11-03 23:34:43.616  4675  4872 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
11-03 23:34:43.618  4675  4750 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
11-03 23:34:43.619  5572  5619 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-03 23:34:43.621  5572  5619 D BluetoothAdapter: STATE_ON
11-03 23:34:43.622  4675  4688 D BtGatt.GattService: stopScan() - queue size =1
,11-03 23:34:43.623  4675  4686 D BtGatt.GattService: unregisterClient() - clientIf=5
11-03 23:34:43.624  5572  5619 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-03 23:34:43.624  5572  5619 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
,11-03 23:34:43.625  5572  5619 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
11-03 23:34:43.625  5572  5619 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-61,5,main], id: 61
11-03 23:34:43.625  5572  5619 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-61,5,main], id: 61
,11-03 23:34:43.626  5572  5619 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-61,5,main], id: 61
11-03 23:34:43.626  5572  5619 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-61,5,main], id: 61
11-03 23:34:43.626  5572  5619 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-03 23:34:43.627  5572  5619 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
11-03 23:34:43.627  5572  5619 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-61,5,main], id: 61
,11-03 23:34:43.627  5572  5619 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-61,5,main], id: 61
11-03 23:34:43.627  5572  5619 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-03 23:34:43.628  5572  5619 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,11-03 23:34:43.637  4675  4675 D BtGatt.ScanManager: awakened up at time 97071
11-03 23:34:43.637  5572  5619 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-03 23:34:43.638  5572  5619 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-03 23:34:43.669  5572  5619 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
,11-03 23:34:43.669  5572  5619 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,11-03 23:34:43.669  5572  5619 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-03 23:34:43.669  5572  5619 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-03 23:34:43.669  5572  5619 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-03 23:34:43.669  5572  5572 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-03 23:34:43.669  5572  5619 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-03 23:34:43.669  5572  5572 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-03 23:34:43.669  5572  5619 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,11-03 23:34:43.669  5572  5619 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,11-03 23:34:43.669  5572  5572 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-03 23:34:43.669  5572  5619 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c39033a not in the list
11-03 23:34:43.669  5572  5572 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-03 23:34:43.669  5572  5619 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-03 23:34:43.670  5572  5572 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-03 23:34:43.670  5572  5619 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c1e3beb not in the list
11-03 23:34:43.670  5572  5619 D io.jxcore.node.ConnectivityMonitor: stop
11-03 23:34:43.670  5572  5572 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
11-03 23:34:43.670  5572  5619 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
11-03 23:34:43.670  5572  5572 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-03 23:34:43.670  5572  5572 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-03 23:34:43.670  5572  5572 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,11-03 23:34:43.670  5572  5572 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-03 23:34:43.671  5572  5572 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-03 23:34:43.671  5572  5572 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
,11-03 23:34:43.672  5572  5572 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-03 23:34:43.672  5572  5572 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-03 23:34:43.672  5572  5572 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,11-03 23:34:43.691  4675  4747 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=6
,11-03 23:34:43.691  4675  4747 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-03 23:34:43.691  4675  4747 D BtGatt.GattService: current time is 97126184421
11-03 23:34:43.691  4675  4747 D BtGatt.GattService: Batch record : [37, -47, 14, -113, 116, -46, 1, -128, -84, 96, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 71, -122, -77, 84, 69, -12, 1, -128, -85, 89, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 35, 97, 126, -92, 22, -56, 1, -128, -80, 75, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, -46, -4, -117, 6, 105, -37, 1, -128, -75, 74, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 116, -43, -111, -91, -20, -29, 1, -128, -86, 71, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 81, 34, 97, 112, -14, -5, 1, -128, -86, 65, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
11-03 23:34:43.693  4675  4747 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
11-03 23:34:43.694  4675  4747 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
11-03 23:34:43.694  4675  4747 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,11-03 23:34:43.694  4675  4747 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
11-03 23:34:43.694  4675  4747 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
11-03 23:34:43.694  4675  4747 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
11-03 23:34:43.695  4675  4747 E BtGatt.ContextMap: Context not found for ID 5
11-03 23:34:43.703  4675  4747 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
11-03 23:34:43.703  4675  4747 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-03 23:34:43.703  4675  4750 D BtGatt.ScanManager: stopping BLe Batch
11-03 23:34:43.709  4675  4747 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
11-03 23:34:43.709  4675  4747 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-03 23:34:43.709  4675  4750 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
11-03 23:34:43.715  4675  4747 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-03 23:34:43.715  4675  4747 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-03 23:34:43.790   928  2959 D WifiService: New client listening to asynchronous messages
,11-03 23:34:43.794  3947  5620 W CronetSyncConnectionRcs: Upload content type not set.
,11-03 23:34:43.865  4884  4914 D Finsky  : [188] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,11-03 23:34:43.866  4884  4884 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,11-03 23:34:44.173  5572  5572 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-03 23:34:47.476   928  2958 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-03 23:34:48.679  5572  5619 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,11-03 23:34:48.688  5572  5619 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,11-03 23:34:48.689  5572  5619 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
,11-03 23:34:48.705  5572  5619 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-03 23:34:48.705  5572  5619 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-03 23:34:48.705  5572  5619 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-03 23:34:48.705  5572  5619 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-03 23:34:48.705  5572  5619 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-03 23:34:48.705  5572  5619 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-03 23:34:48.705  5572  5619 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-03 23:34:48.705  5572  5619 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,11-03 23:34:48.707  5572  5619 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,11-03 23:34:48.708  5572  5619 D io.jxcore.node.ConnectivityMonitor: start: OK
,11-03 23:34:48.708  5572  5619 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-03 23:34:48.708  5572  5619 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
11-03 23:34:48.708  5572  5619 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
11-03 23:34:48.708  5572  5619 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-03 23:34:48.708  5572  5619 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,11-03 23:34:48.712  5572  5572 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-03 23:34:48.716  5572  5619 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
,11-03 23:34:48.716  5572  5619 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-03 23:34:48.716  5572  5619 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
11-03 23:34:48.717  5572  5572 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-03 23:34:48.721  5572  5619 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-61,5,main], id: 61
,11-03 23:34:48.721  5572  5619 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-03 23:34:48.723  5572  5619 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-03 23:34:48.723  5572  5619 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-03 23:34:48.723  5572  5619 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 0
,11-03 23:34:48.727  5572  5619 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-61,5,main], id: 61
,11-03 23:34:48.727  5572  5619 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
11-03 23:34:48.727  5572  5619 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
11-03 23:34:48.727  5572  5619 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
11-03 23:34:48.727  5572  5619 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
11-03 23:34:48.728  5572  5619 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-61,5,main], id: 61
,11-03 23:34:48.729  5572  5619 D BluetoothAdapter: STATE_ON
,11-03 23:34:48.731  4675  4688 D BtGatt.GattService: registerClient() - UUID=0c3c9ac4-1ce3-4fda-8873-2c3a91676a49
11-03 23:34:48.731  4675  4747 D BtGatt.GattService: onClientRegistered() - UUID=0c3c9ac4-1ce3-4fda-8873-2c3a91676a49, clientIf=5
,11-03 23:34:48.732  5572  5583 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
11-03 23:34:48.732  4675  4686 D BtGatt.GattService: start scan with filters
,11-03 23:34:48.734  5572  5619 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
,11-03 23:34:48.734  4675  4750 D BtGatt.ScanManager: handling starting scan
11-03 23:34:48.735  5572  5619 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-03 23:34:48.735  5572  5619 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
11-03 23:34:48.735  5572  5619 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-61,5,main], id: 61
11-03 23:34:48.735  5572  5619 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-03 23:34:48.735  5572  5572 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-03 23:34:48.735  5572  5572 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-03 23:34:48.735  5572  5572 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
,11-03 23:34:48.735  5572  5572 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-03 23:34:48.735  5572  5572 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-03 23:34:48.735  5572  5572 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
11-03 23:34:48.735  5572  5572 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
11-03 23:34:48.736  5572  5619 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-03 23:34:48.736  5572  5619 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-03 23:34:48.740  5572  5619 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-03 23:34:48.740  5572  5619 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
11-03 23:34:48.740  5572  5619 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-03 23:34:48.740  5572  5619 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-03 23:34:48.740  5572  5619 I io.jxcore.node.ConnectionHelper: start: OK
11-03 23:34:48.740  5572  5572 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-03 23:34:48.742  4675  4747 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
11-03 23:34:48.742  4675  4747 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-03 23:34:48.743  4675  4750 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,11-03 23:34:48.743  5572  5572 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-03 23:34:48.743  5572  5572 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-03 23:34:48.743  5572  5619 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-03 23:34:48.743  5572  5572 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-03 23:34:48.743  5572  5619 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,11-03 23:34:48.743  5572  5572 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-03 23:34:48.744  5572  5619 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
11-03 23:34:48.744  5572  5572 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
11-03 23:34:48.744  5572  5619 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
11-03 23:34:48.744  5572  5619 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-03 23:34:48.744  5572  5619 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-03 23:34:48.744  5572  5619 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-03 23:34:48.744  5572  5619 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,11-03 23:34:48.744  5572  5619 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-03 23:34:48.744  5572  5619 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
11-03 23:34:48.744  5572  5619 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-03 23:34:48.744  5572  5619 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
11-03 23:34:48.744  5572  5619 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-61,5,main], id: 61
11-03 23:34:48.744  5572  5619 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-03 23:34:48.744  5572  5619 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
11-03 23:34:48.744  5572  5619 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-61,5,main], id: 61
,11-03 23:34:48.745  5572  5619 D BluetoothAdapter: STATE_ON
11-03 23:34:48.745  4675  4686 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
,11-03 23:34:48.746  5572  5619 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-03 23:34:48.746  5572  5619 D BluetoothAdapter: STATE_ON
11-03 23:34:48.747  4675  4688 D BtGatt.GattService: stopScan() - queue size =1
11-03 23:34:48.748  4675  4880 D BtGatt.GattService: unregisterClient() - clientIf=5
11-03 23:34:48.748  5572  5619 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-03 23:34:48.748  5572  5619 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-03 23:34:48.749  5572  5619 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
11-03 23:34:48.749  5572  5619 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-61,5,main], id: 61
11-03 23:34:48.749  5572  5619 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-61,5,main], id: 61
,11-03 23:34:48.749  5572  5619 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-61,5,main], id: 61
11-03 23:34:48.749  4675  4747 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
11-03 23:34:48.749  5572  5619 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-61,5,main], id: 61
11-03 23:34:48.749  4675  4747 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-03 23:34:48.749  5572  5619 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-03 23:34:48.749  5572  5619 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
11-03 23:34:48.749  5572  5619 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-61,5,main], id: 61
,11-03 23:34:48.749  4675  4750 D BtGatt.ScanManager: Starting BLE batch scan
11-03 23:34:48.749  5572  5619 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-61,5,main], id: 61
11-03 23:34:48.749  5572  5619 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-03 23:34:48.749  4675  4750 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
11-03 23:34:48.749  5572  5619 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-03 23:34:48.750  5572  5619 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-03 23:34:48.750  5572  5619 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-03 23:34:48.751  5572  5619 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-03 23:34:48.751  5572  5619 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,11-03 23:34:48.751  5572  5619 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-03 23:34:48.751  5572  5619 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-03 23:34:48.752  5572  5619 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-03 23:34:48.752  5572  5572 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-03 23:34:48.752  5572  5619 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-03 23:34:48.752  5572  5572 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-03 23:34:48.752  5572  5619 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-03 23:34:48.752  5572  5619 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,11-03 23:34:48.752  5572  5572 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-03 23:34:48.752  5572  5619 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c39033a not in the list
11-03 23:34:48.752  5572  5572 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-03 23:34:48.752  5572  5619 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-03 23:34:48.752  5572  5572 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-03 23:34:48.752  5572  5619 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c1e3beb not in the list
11-03 23:34:48.752  5572  5572 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
11-03 23:34:48.752  5572  5619 D io.jxcore.node.ConnectivityMonitor: stop
11-03 23:34:48.752  5572  5619 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
,11-03 23:34:48.752  5572  5572 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-03 23:34:48.752  5572  5572 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-03 23:34:48.752  5572  5572 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
11-03 23:34:48.752  5572  5572 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-03 23:34:48.754  5572  5572 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-03 23:34:48.754  5572  5572 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-03 23:34:48.754  5572  5572 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-03 23:34:48.754  5572  5572 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-03 23:34:48.754  5572  5572 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,11-03 23:34:48.758  5572  5619 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-03 23:34:48.759  5572  5619 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-03 23:34:48.760  5572  5619 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
,11-03 23:34:48.760  5572  5619 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-03 23:34:48.760  5572  5619 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-03 23:34:48.760  5572  5619 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-03 23:34:48.760  5572  5619 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-03 23:34:48.760  5572  5619 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c1e3beb not in the list
11-03 23:34:48.760  5572  5619 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
11-03 23:34:48.761  4675  4747 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
11-03 23:34:48.761  4675  4747 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-03 23:34:48.762  5572  5619 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-03 23:34:48.762  5572  5619 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
,11-03 23:34:48.766  4675  4747 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
11-03 23:34:48.766  4675  4747 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-03 23:34:48.767  5572  5619 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-03 23:34:48.767  5572  5619 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-03 23:34:48.767  5572  5619 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-03 23:34:48.767  5572  5619 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-03 23:34:48.767  5572  5619 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-03 23:34:48.767  5572  5619 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-03 23:34:48.767  5572  5619 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-03 23:34:48.767  5572  5619 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,11-03 23:34:48.768  4675  4750 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-03 23:34:48.769  5572  5619 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,11-03 23:34:48.770  5572  5619 D io.jxcore.node.ConnectivityMonitor: start: OK
11-03 23:34:48.770  5572  5619 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-03 23:34:48.770  5572  5619 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
11-03 23:34:48.770  5572  5619 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
11-03 23:34:48.770  5572  5619 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-03 23:34:48.770  5572  5619 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,11-03 23:34:48.772  5572  5572 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-03 23:34:48.773  4675  4747 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-03 23:34:48.773  4675  4747 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-03 23:34:48.773  4675  4747 E BtGatt.ContextMap: Context not found for ID 5
11-03 23:34:48.774  5572  5619 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-03 23:34:48.774  5572  5619 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-03 23:34:48.774  5572  5619 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
11-03 23:34:48.775  5572  5572 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-03 23:34:48.777  5572  5619 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-61,5,main], id: 61
11-03 23:34:48.778  5572  5619 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-03 23:34:48.778  5572  5619 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-03 23:34:48.778  5572  5619 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-03 23:34:48.779  5572  5619 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 0
11-03 23:34:48.780  4675  4747 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
11-03 23:34:48.780  4675  4747 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-03 23:34:48.780  4675  4750 D BtGatt.ScanManager: stopping BLe Batch
11-03 23:34:48.781  5572  5619 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-03 23:34:48.781  5572  5619 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
11-03 23:34:48.782  5572  5619 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
11-03 23:34:48.782  5572  5619 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
11-03 23:34:48.782  5572  5619 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
11-03 23:34:48.782  5572  5619 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-61,5,main], id: 61
11-03 23:34:48.782  5572  5619 D BluetoothAdapter: STATE_ON
11-03 23:34:48.784  4675  4880 D BtGatt.GattService: registerClient() - UUID=3c3ee6cc-9032-48a2-a629-0cb1c9809892
11-03 23:34:48.786  4675  4747 D BtGatt.GattService: onClientRegistered() - UUID=3c3ee6cc-9032-48a2-a629-0cb1c9809892, clientIf=5
11-03 23:34:48.786  4675  4747 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
11-03 23:34:48.786  4675  4747 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-03 23:34:48.786  5572  5582 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
11-03 23:34:48.786  4675  4750 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-03 23:34:48.786  4675  4688 D BtGatt.GattService: start scan with filters
11-03 23:34:48.788  5572  5619 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
11-03 23:34:48.788  5572  5619 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
,11-03 23:34:48.789  5572  5619 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
11-03 23:34:48.789  5572  5619 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-61,5,main], id: 61
11-03 23:34:48.789  5572  5619 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-03 23:34:48.789  5572  5572 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-03 23:34:48.789  5572  5572 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-03 23:34:48.789  5572  5572 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
11-03 23:34:48.789  5572  5572 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-03 23:34:48.789  5572  5572 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-03 23:34:48.789  5572  5572 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
11-03 23:34:48.789  5572  5572 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
11-03 23:34:48.790  5572  5619 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-03 23:34:48.791  5572  5619 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-03 23:34:48.791  4675  4747 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-03 23:34:48.791  4675  4747 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-03 23:34:48.792  4675  4750 D BtGatt.ScanManager: handling starting scan
11-03 23:34:48.793  5572  5619 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-03 23:34:48.793  5572  5619 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
11-03 23:34:48.793  5572  5619 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-03 23:34:48.793  5572  5619 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-03 23:34:48.793  5572  5619 I io.jxcore.node.ConnectionHelper: start: OK
11-03 23:34:48.794  5572  5572 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
,11-03 23:34:48.796  5572  5572 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-03 23:34:48.797  5572  5572 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-03 23:34:48.797  5572  5572 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-03 23:34:48.797  5572  5572 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-03 23:34:48.797  5572  5572 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
11-03 23:34:48.798  4675  4747 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
11-03 23:34:48.799  4675  4747 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-03 23:34:48.799  4675  4750 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
11-03 23:34:48.803  4675  4747 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
11-03 23:34:48.803  4675  4747 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-03 23:34:48.803  4675  4750 D BtGatt.ScanManager: Starting BLE batch scan
11-03 23:34:48.803  4675  4750 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
11-03 23:34:48.811  4675  4747 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
11-03 23:34:48.811  4675  4747 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-03 23:34:48.816  4675  4747 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
11-03 23:34:48.816  4675  4747 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-03 23:34:49.298  5572  5572 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,11-03 23:34:49.298  5572  5572 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
11-03 23:34:49.298  5572  5572 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,11-03 23:34:50.679   928  2960 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,11-03 23:34:53.704   928  2960 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,11-03 23:34:53.794  5572  5619 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-03 23:34:53.795  5572  5619 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,11-03 23:34:53.795  5572  5619 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
11-03 23:34:53.795  5572  5619 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-03 23:34:53.796  5572  5619 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-03 23:34:53.796  5572  5619 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,11-03 23:34:53.796  5572  5619 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
11-03 23:34:53.796  5572  5619 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-03 23:34:53.796  5572  5619 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,11-03 23:34:53.796  5572  5619 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,11-03 23:34:53.797  5572  5619 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
11-03 23:34:53.797  5572  5619 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-61,5,main], id: 61
11-03 23:34:53.797  5572  5619 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-03 23:34:53.797  5572  5619 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
11-03 23:34:53.797  5572  5619 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-61,5,main], id: 61
11-03 23:34:53.800  5572  5619 D BluetoothAdapter: STATE_ON
11-03 23:34:53.800  4675  4686 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
11-03 23:34:53.801  5572  5619 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-03 23:34:53.802  4675  4750 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
11-03 23:34:53.802  5572  5619 D BluetoothAdapter: STATE_ON
11-03 23:34:53.804  4675  4880 D BtGatt.GattService: stopScan() - queue size =1
,11-03 23:34:53.806  4675  4688 D BtGatt.GattService: unregisterClient() - clientIf=5
,11-03 23:34:53.808  5572  5619 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,11-03 23:34:53.809  5572  5619 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
,11-03 23:34:53.809  5572  5619 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
11-03 23:34:53.809  5572  5619 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-61,5,main], id: 61
11-03 23:34:53.810  5572  5619 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-61,5,main], id: 61
,11-03 23:34:53.810  5572  5619 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-61,5,main], id: 61
11-03 23:34:53.810  5572  5619 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-61,5,main], id: 61
11-03 23:34:53.810  5572  5619 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-03 23:34:53.811  5572  5619 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
11-03 23:34:53.811  5572  5619 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-61,5,main], id: 61
11-03 23:34:53.811  5572  5619 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-61,5,main], id: 61
11-03 23:34:53.811  5572  5619 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,11-03 23:34:53.812  5572  5619 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-03 23:34:53.814  5572  5619 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-03 23:34:53.814  5572  5619 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-03 23:34:53.815  4675  4675 D BtGatt.ScanManager: awakened up at time 107250
11-03 23:34:53.817   928  3780 I ActivityManager: Killing 5274:com.android.settings/1000 (adj 15): empty #17
11-03 23:34:53.818  5572  5619 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-03 23:34:53.819  5572  5619 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,11-03 23:34:53.819  5572  5619 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-03 23:34:53.819  5572  5619 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-03 23:34:53.819  5572  5572 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-03 23:34:53.820  5572  5572 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-03 23:34:53.820  5572  5572 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-03 23:34:53.820  5572  5572 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-03 23:34:53.820  5572  5572 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
,11-03 23:34:53.820  5572  5572 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
11-03 23:34:53.820  5572  5572 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-03 23:34:53.820  5572  5572 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-03 23:34:53.821  5572  5572 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
11-03 23:34:53.821  5572  5572 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-03 23:34:53.823  5572  5572 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
,11-03 23:34:53.824  5572  5572 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-03 23:34:53.824  5572  5572 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-03 23:34:53.824  5572  5572 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-03 23:34:53.824  5572  5572 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,11-03 23:34:53.859  4675  4747 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=6
,11-03 23:34:53.859  4675  4747 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-03 23:34:53.859  4675  4747 D BtGatt.GattService: current time is 107294045316
11-03 23:34:53.859  4675  4747 D BtGatt.GattService: Batch record : [71, -122, -77, 84, 69, -12, 1, -128, -85, 92, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 37, -47, 14, -113, 116, -46, 1, -128, -85, 98, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 116, -43, -111, -91, -20, -29, 1, -128, -81, 97, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 81, 34, 97, 112, -14, -5, 1, -128, -97, 94, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 0, 35, 97, 126, -92, 22, -56, 1, -128, -80, 86, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 0, -46, -4, -117, 6, 105, -37, 1, -128, -75, 83, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
11-03 23:34:53.859  4675  4747 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
11-03 23:34:53.859  4675  4747 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
11-03 23:34:53.860  4675  4747 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
11-03 23:34:53.860  4675  4747 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74]
,11-03 23:34:53.860  4675  4747 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74]
11-03 23:34:53.860  4675  4747 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
,11-03 23:34:53.866  4675  4747 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
,11-03 23:34:53.866  4675  4747 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-03 23:34:53.866  4675  4750 D BtGatt.ScanManager: stopping BLe Batch
,11-03 23:34:53.871  4675  4747 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,11-03 23:34:53.871  4675  4747 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-03 23:34:53.871  4675  4750 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-03 23:34:53.876  4675  4747 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-03 23:34:53.877  4675  4747 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-03 23:34:54.325  5572  5572 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-03 23:34:54.325  5572  5572 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-03 23:34:54.326  5572  5572 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,11-03 23:34:58.821  5572  5619 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-03 23:34:58.821  5572  5619 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,11-03 23:34:58.822  5572  5619 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-03 23:34:58.822  5572  5619 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-03 23:34:58.822  5572  5619 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-03 23:34:58.822  5572  5619 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-03 23:34:58.822  5572  5619 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-03 23:34:58.823  5572  5619 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c39033a not in the list
11-03 23:34:58.823  5572  5619 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-03 23:34:58.823  5572  5619 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c1e3beb not in the list
11-03 23:34:58.823  5572  5619 D io.jxcore.node.ConnectivityMonitor: stop
11-03 23:34:58.823  5572  5619 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
,11-03 23:34:58.827  5572  5619 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-03 23:34:58.830  5572  5619 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-03 23:34:58.830  5572  5619 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-03 23:34:58.830  5572  5619 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
,11-03 23:34:58.830  5572  5619 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-03 23:34:58.831  5572  5619 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-03 23:34:58.831  5572  5619 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-03 23:34:58.831  5572  5619 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c1e3beb not in the list
11-03 23:34:58.832  5572  5619 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
11-03 23:34:58.834  5572  5619 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-03 23:34:58.834  5572  5619 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-03 23:34:58.834  5572  5619 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,11-03 23:34:58.835  5572  5619 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-03 23:34:58.835  5572  5619 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-03 23:34:58.835  5572  5619 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c39033a not in the list
,11-03 23:34:58.835  5572  5619 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-03 23:34:58.835  5572  5619 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c1e3beb not in the list
11-03 23:34:58.836  5572  5619 D io.jxcore.node.ConnectivityMonitor: stop
11-03 23:34:58.836  5572  5619 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-03 23:34:58.839  5572  5619 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
,11-03 23:34:58.839  5572  5619 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-03 23:34:58.840  5572  5619 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-03 23:34:58.840  5572  5619 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,11-03 23:34:58.840  5572  5619 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,11-03 23:34:58.840  5572  5619 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-03 23:34:58.840  5572  5619 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c1e3beb not in the list
,11-03 23:34:58.843  5572  5619 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
11-03 23:34:58.843  5572  5619 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-03 23:34:58.843  5572  5619 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-03 23:34:58.843  5572  5619 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-03 23:34:58.843  5572  5619 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-03 23:34:58.844  5572  5619 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,11-03 23:34:58.844  5572  5619 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c39033a not in the list
11-03 23:34:58.844  5572  5619 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-03 23:34:58.844  5572  5619 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c1e3beb not in the list
11-03 23:34:58.844  5572  5619 D io.jxcore.node.ConnectivityMonitor: stop
11-03 23:34:58.845  5572  5619 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-03 23:34:58.847  5572  5619 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
,11-03 23:34:58.847  5572  5619 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-03 23:34:58.847  5572  5619 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-03 23:34:58.847  5572  5619 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,11-03 23:34:58.847  5572  5619 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-03 23:34:58.847  5572  5619 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-03 23:34:58.847  5572  5619 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c1e3beb not in the list
11-03 23:34:58.848  5572  5619 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
11-03 23:34:58.848  5572  5619 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-03 23:34:58.849  5572  5619 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,11-03 23:34:58.849  5572  5619 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-03 23:34:58.849  5572  5619 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-03 23:34:58.849  5572  5619 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-03 23:34:58.849  5572  5619 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c39033a not in the list
11-03 23:34:58.849  5572  5619 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-03 23:34:58.849  5572  5619 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c1e3beb not in the list
11-03 23:34:58.849  5572  5619 D io.jxcore.node.ConnectivityMonitor: stop
11-03 23:34:58.849  5572  5619 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-03 23:34:58.851  5572  5619 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-03 23:34:58.851  5572  5619 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-03 23:34:58.851  5572  5619 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-03 23:34:58.851  5572  5619 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-03 23:34:58.851  5572  5619 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-03 23:34:58.851  5572  5619 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-03 23:34:58.851  5572  5619 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c1e3beb not in the list
11-03 23:34:58.852  5572  5619 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
,11-03 23:34:58.852  5572  5619 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-03 23:34:58.852  5572  5619 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-03 23:34:58.853  5572  5619 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-03 23:34:58.853  5572  5619 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-03 23:34:58.853  5572  5619 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-03 23:34:58.853  5572  5619 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c39033a not in the list
11-03 23:34:58.853  5572  5619 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-03 23:34:58.853  5572  5619 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c1e3beb not in the list
11-03 23:34:58.853  5572  5619 D io.jxcore.node.ConnectivityMonitor: stop
11-03 23:34:58.853  5572  5619 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-03 23:34:58.855  5572  5619 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-03 23:34:58.855  5572  5619 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
,11-03 23:34:58.855  5572  5619 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-03 23:34:58.855  5572  5619 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-03 23:34:58.855  5572  5619 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-03 23:34:58.855  5572  5619 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-03 23:34:58.855  5572  5619 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c1e3beb not in the list
,11-03 23:34:58.856  5572  5619 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
11-03 23:34:58.857  5572  5619 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-03 23:34:58.857  5572  5619 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-03 23:34:58.857  5572  5619 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
11-03 23:34:58.857  5572  5619 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,11-03 23:34:58.857  5572  5619 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-03 23:34:58.857  5572  5619 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
11-03 23:34:58.857  5572  5619 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-03 23:34:58.857  5572  5619 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,11-03 23:34:58.857  5572  5619 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-03 23:34:58.857  5572  5619 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-03 23:34:58.857  5572  5619 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-03 23:34:58.858  5572  5619 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,11-03 23:34:58.858  5572  5619 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-03 23:34:58.858  5572  5619 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c39033a not in the list
11-03 23:34:58.858  5572  5619 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-03 23:34:58.858  5572  5619 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c1e3beb not in the list
11-03 23:34:58.858  5572  5619 D io.jxcore.node.ConnectivityMonitor: stop
11-03 23:34:58.858  5572  5619 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-03 23:34:58.860  5572  5619 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-03 23:34:58.860  5572  5619 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-03 23:34:58.861  5572  5619 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
,11-03 23:34:58.861  5572  5619 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,11-03 23:34:58.861  5572  5619 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-03 23:34:58.861  5572  5619 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-03 23:34:58.862  5572  5619 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c1e3beb not in the list
11-03 23:34:58.865  5572  5619 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
11-03 23:34:58.865  5572  5619 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
11-03 23:34:58.865  5572  5619 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,11-03 23:34:58.869  5572  5619 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
11-03 23:34:58.870  5572  5619 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
,11-03 23:34:58.870  5572  5619 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
11-03 23:34:58.870  5572  5619 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
11-03 23:34:58.870  5572  5619 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
11-03 23:34:58.870  5572  5619 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
11-03 23:34:58.870  5572  5619 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
11-03 23:34:58.870  5572  5619 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
,11-03 23:34:58.870  5572  5619 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
11-03 23:34:58.870  5572  5619 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
11-03 23:34:58.870  5572  5619 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
11-03 23:34:58.870  5572  5619 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
11-03 23:34:58.871  5572  5619 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
11-03 23:34:58.871  5572  5619 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
11-03 23:34:58.871  5572  5619 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
,11-03 23:34:58.871  5572  5619 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
11-03 23:34:58.871  5572  5619 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
11-03 23:34:58.871  5572  5619 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
11-03 23:34:58.871  5572  5619 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
11-03 23:34:58.871  5572  5619 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
11-03 23:34:58.871  5572  5619 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
11-03 23:34:58.871  5572  5619 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
11-03 23:34:58.871  5572  5619 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
11-03 23:34:58.871  5572  5619 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
11-03 23:34:58.871  5572  5619 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
11-03 23:34:58.872  5572  5619 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
11-03 23:34:58.872  5572  5619 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
11-03 23:34:58.872  5572  5619 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
11-03 23:34:58.872  5572  5619 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
11-03 23:34:58.872  5572  5619 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
11-03 23:34:58.872  5572  5619 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
11-03 23:34:58.872  5572  5619 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
11-03 23:34:58.872  5572  5619 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
11-03 23:34:58.872  5572  5619 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
11-03 23:34:58.873  5572  5619 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
11-03 23:34:58.873  5572  5619 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
11-03 23:34:58.873  5572  5619 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
,11-03 23:34:58.873  5572  5619 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
11-03 23:34:58.873  5572  5619 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
11-03 23:34:58.873  5572  5619 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
11-03 23:34:58.873  5572  5619 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
11-03 23:34:58.878  5572  5619 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
11-03 23:34:58.879  5572  5619 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
11-03 23:34:58.879  5572  5619 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
11-03 23:34:58.880  5572  5619 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
11-03 23:34:58.880  5572  5619 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
11-03 23:34:58.880  5572  5619 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
11-03 23:34:58.880  5572  5619 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
11-03 23:34:58.880  5572  5619 E io.jxcore.node.ConnectionHelper: connect: Callback is null
11-03 23:34:58.880  5572  5632 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 125)
11-03 23:34:58.881  5572  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: tryToConnect:  socketConnectSucceeded = false, mIsShuttingDown = false
11-03 23:34:58.881  5572  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: socket closed
11-03 23:34:58.881  5572  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: SYSTEM_DECIDED_INSECURE_RFCOMM_SOCKET_PORT
11-03 23:34:58.881  5572  5619 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-03 23:34:58.881  5572  5619 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-03 23:34:58.882  5572  5619 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-03 23:34:58.882  5572  5619 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-03 23:34:58.882  5572  5619 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-03 23:34:58.882  5572  5619 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
11-03 23:34:58.883  5572  5632 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: connecting
11-03 23:34:58.883  5572  5632 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-03 23:34:58.883  5572  5619 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c39033a not in the list
11-03 23:34:58.884  5572  5619 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-03 23:34:58.884  5572  5619 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c1e3beb not in the list
11-03 23:34:58.883  4688  4688 W Binder_2: type=1400 audit(0.0:113): avc: denied { ioctl } for path="socket:[30625]" dev="sockfs" ino=30625 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-03 23:34:58.883  4688  4688 W Binder_2: type=1400 audit(0.0:114): avc: denied { ioctl } for path="socket:[30625]" dev="sockfs" ino=30625 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-03 23:34:58.885  5572  5619 D io.jxcore.node.ConnectivityMonitor: stop
11-03 23:34:58.885  5572  5619 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-03 23:34:58.885  5572  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 125
11-03 23:34:58.885  5572  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close
11-03 23:34:58.886  5572  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Trying to close the Bluetooth socket... (thread ID: 125)
11-03 23:34:58.886  5572  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Bluetooth socket closed (thread ID: 125)
11-03 23:34:58.886  5572  5632 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: connect, socket closed
11-03 23:34:58.886  5572  5619 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-03 23:34:58.886  5572  5632 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: socketConnectSucceeded false
11-03 23:34:58.886  5572  5632 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 125)
11-03 23:34:58.886  5572  5619 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-03 23:34:58.886  5572  5619 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-03 23:34:58.887  5572  5619 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-03 23:34:58.887  5572  5619 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-03 23:34:58.887  5572  5619 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-03 23:34:58.887  5572  5619 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c1e3beb not in the list
11-03 23:34:58.887  5572  5619 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
11-03 23:34:58.888  5572  5619 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-03 23:34:58.888  5572  5619 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-03 23:34:58.888  5572  5619 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-03 23:34:58.889  5572  5619 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-03 23:34:58.889  5572  5619 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-03 23:34:58.889  5572  5619 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c39033a not in the list
11-03 23:34:58.889  5572  5619 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-03 23:34:58.889  5572  5619 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c1e3beb not in the list
11-03 23:34:58.889  5572  5619 D io.jxcore.node.ConnectivityMonitor: stop
11-03 23:34:58.889  5572  5619 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-03 23:34:58.890  5572  5619 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-03 23:34:58.890  5572  5619 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-03 23:34:58.890  5572  5619 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-03 23:34:58.890  5572  5619 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-03 23:34:58.890  5572  5619 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-03 23:34:58.891  5572  5619 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-03 23:34:58.891  5572  5619 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c1e3beb not in the list
11-03 23:34:58.892  5572  5619 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
11-03 23:34:58.892  5572  5619 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-03 23:34:58.892  5572  5619 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-03 23:34:58.892  5572  5619 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-03 23:34:58.892  5572  5619 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-03 23:34:58.892  5572  5619 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-03 23:34:58.893  5572  5619 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c39033a not in the list
11-03 23:34:58.893  5572  5619 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-03 23:34:58.893  5572  5619 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c1e3beb not in the list
11-03 23:34:58.893  5572  5619 D io.jxcore.node.ConnectivityMonitor: stop
11-03 23:34:58.893  5572  5619 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-03 23:34:58.896  5572  5619 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-03 23:34:58.896  5572  5619 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-03 23:34:58.896  5572  5619 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-03 23:34:58.896  5572  5619 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-03 23:34:58.896  5572  5619 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-03 23:34:58.896  5572  5619 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-03 23:34:58.896  5572  5619 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c1e3beb not in the list
11-03 23:34:58.897  5572  5619 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
11-03 23:34:58.897  5572  5619 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
11-03 23:34:58.897  5572  5619 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
11-03 23:34:58.897  5572  5619 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
11-03 23:34:58.897  5572  5619 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
11-03 23:34:58.897  5572  5619 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
11-03 23:34:58.897  5572  5619 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
11-03 23:34:58.897  5572  5619 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
11-03 23:34:58.897  5572  5619 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
11-03 23:34:58.898  5572  5619 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
11-03 23:34:58.898  5572  5619 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
11-03 23:34:58.898  5572  5619 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
11-03 23:34:58.898  5572  5619 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-03 23:34:58.898  5572  5619 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-03 23:34:58.898  5572  5619 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-03 23:34:58.898  5572  5619 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-03 23:34:58.898  5572  5619 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-03 23:34:58.899  5572  5619 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c39033a not in the list
11-03 23:34:58.899  5572  5619 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-03 23:34:58.899  5572  5619 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c1e3beb not in the list
11-03 23:34:58.899  5572  5619 D io.jxcore.node.ConnectivityMonitor: stop
11-03 23:34:58.899  5572  5619 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-03 23:34:58.900  5572  5619 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-03 23:34:58.900  5572  5619 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-03 23:34:58.901  5572  5619 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-03 23:34:58.901  5572  5619 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-03 23:34:58.901  5572  5619 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-03 23:34:58.901  5572  5619 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-03 23:34:58.901  5572  5619 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c1e3beb not in the list
11-03 23:34:58.901  5572  5619 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-03 23:34:58.902  5572  5619 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-03 23:34:58.902  5572  5619 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c39033a not in the list
11-03 23:34:58.902  5572  5619 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-03 23:34:58.902  5572  5619 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c1e3beb not in the list
11-03 23:34:58.902  5572  5619 D io.jxcore.node.ConnectivityMonitor: stop
,11-03 23:34:59.759   928  2960 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,11-03 23:35:00.104   535   535 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
11-03 23:35:00.104   535   535 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,11-03 23:35:02.722   928  5346 D NetlinkSocketObserver: NeighborEvent{elapsedMs=116157, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,11-03 23:35:03.903  5572  5619 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-03 23:35:03.903  5572  5619 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c1e3beb not in the list
,11-03 23:35:03.903  5572  5619 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,11-03 23:35:03.903  5572  5619 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,11-03 23:35:03.904  5572  5619 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c39033a not in the list
,11-03 23:35:03.904  5572  5619 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-03 23:35:03.904  5572  5619 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-03 23:35:03.904  5572  5619 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,11-03 23:35:03.904  5572  5619 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-03 23:35:03.905  5572  5619 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-03 23:35:03.905  5572  5619 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c39033a not in the list
,11-03 23:35:03.905  5572  5619 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-03 23:35:03.905  5572  5619 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c1e3beb not in the list
,11-03 23:35:03.905  5572  5619 D io.jxcore.node.ConnectivityMonitor: stop
,11-03 23:35:03.906  5572  5619 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-03 23:35:03.912  5572  5619 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-03 23:35:03.912  5572  5619 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-03 23:35:03.912  5572  5619 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
,11-03 23:35:03.913  5572  5619 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-03 23:35:03.913  5572  5619 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-03 23:35:03.913  5572  5619 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-03 23:35:03.913  5572  5619 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c1e3beb not in the list
11-03 23:35:03.917  5572  5619 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
11-03 23:35:03.918  5572  5619 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,11-03 23:35:03.919  5572  5619 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
,11-03 23:35:03.924  5572  5619 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
11-03 23:35:03.925  5572  5619 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
11-03 23:35:03.925  5572  5619 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
11-03 23:35:03.926  5572  5619 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
11-03 23:35:03.926  5572  5634 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
,11-03 23:35:03.926  5572  5619 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
11-03 23:35:03.926  5572  5619 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
11-03 23:35:03.926  5572  5572 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
,11-03 23:35:03.927  5572  5619 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,11-03 23:35:03.927  5572  5619 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
,11-03 23:35:03.927  5572  5619 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
11-03 23:35:03.927  5572  5634 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-03 23:35:03.927  5572  5619 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
11-03 23:35:03.927  5572  5619 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
11-03 23:35:03.928  5572  5619 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
11-03 23:35:03.929  5572  5619 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
11-03 23:35:03.929  5572  5619 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c39033a not in the list
,11-03 23:35:03.929  5572  5619 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-03 23:35:03.929  5572  5619 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-03 23:35:03.929  5572  5619 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
11-03 23:35:03.929  5572  5619 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-03 23:35:03.929  5572  5572 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
,11-03 23:35:03.929  5572  5619 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-03 23:35:03.931  5572  5634 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
11-03 23:35:03.931  5572  5634 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
11-03 23:35:03.931  5572  5634 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
11-03 23:35:03.932  5572  5619 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
,11-03 23:35:03.932  5572  5619 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-03 23:35:03.926  4880  4880 W Binder_4: type=1400 audit(0.0:115): avc: denied { ioctl } for path="socket:[28653]" dev="sockfs" ino=28653 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-03 23:35:03.926  4880  4880 W Binder_4: type=1400 audit(0.0:116): avc: denied { ioctl } for path="socket:[28653]" dev="sockfs" ino=28653 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-03 23:35:03.932  5572  5619 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
,11-03 23:35:03.932  5572  5619 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-03 23:35:03.932  5572  5619 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c1e3beb not in the list
11-03 23:35:03.932  5572  5572 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-03 23:35:03.932  5572  5619 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-03 23:35:03.932  5572  5572 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,11-03 23:35:03.933  5572  5619 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-03 23:35:03.933  5572  5572 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
11-03 23:35:03.933  5572  5619 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-03 23:35:03.933  5572  5572 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-03 23:35:03.933  5572  5619 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,11-03 23:35:03.933  5572  5572 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-03 23:35:03.933  5572  5619 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-03 23:35:03.933  5572  5619 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c39033a not in the list
11-03 23:35:03.933  5572  5619 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-03 23:35:03.933  5572  5619 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c1e3beb not in the list
11-03 23:35:03.933  5572  5619 D io.jxcore.node.ConnectivityMonitor: stop
,11-03 23:35:03.934  5572  5619 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-03 23:35:03.935  5572  5619 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-03 23:35:03.935  5572  5619 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-03 23:35:03.936  5572  5619 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-03 23:35:03.936  5572  5619 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-03 23:35:03.936  5572  5619 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,11-03 23:35:03.936  5572  5619 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-03 23:35:03.936  5572  5619 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c1e3beb not in the list
11-03 23:35:03.938  5572  5619 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
11-03 23:35:03.938  5572  5619 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
11-03 23:35:03.938  5572  5619 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
,11-03 23:35:03.939  5572  5619 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-03 23:35:03.939  5572  5619 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-03 23:35:03.939  5572  5619 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-03 23:35:03.939  5572  5619 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-03 23:35:03.939  5572  5619 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-03 23:35:03.939  5572  5619 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-03 23:35:03.939  5572  5619 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,11-03 23:35:03.939  5572  5619 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c39033a not in the list
11-03 23:35:03.940  5572  5619 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-03 23:35:03.940  5572  5619 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c1e3beb not in the list
11-03 23:35:03.940  5572  5619 D io.jxcore.node.ConnectivityMonitor: stop
11-03 23:35:03.940  5572  5619 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-03 23:35:03.943  5572  5619 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
,11-03 23:35:03.943  5572  5619 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-03 23:35:03.943  5572  5619 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-03 23:35:03.943  5572  5619 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-03 23:35:03.943  5572  5619 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,11-03 23:35:03.943  5572  5619 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-03 23:35:03.943  5572  5619 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c1e3beb not in the list
,11-03 23:35:03.948  5572  5619 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-03 23:35:03.948  5572  5619 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-03 23:35:03.948  5572  5619 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-03 23:35:03.949  5572  5619 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-03 23:35:03.949  5572  5619 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,11-03 23:35:03.949  5572  5619 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c39033a not in the list
11-03 23:35:03.949  5572  5619 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-03 23:35:03.949  5572  5619 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c1e3beb not in the list
11-03 23:35:03.949  5572  5619 D io.jxcore.node.ConnectivityMonitor: stop
,11-03 23:35:03.949  5572  5619 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-03 23:35:03.950  5572  5619 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-03 23:35:03.950  5572  5619 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-03 23:35:03.950  5572  5619 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
,11-03 23:35:03.951  5572  5619 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-03 23:35:03.951  5572  5619 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-03 23:35:03.951  5572  5619 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-03 23:35:03.951  5572  5619 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c1e3beb not in the list
,11-03 23:35:03.953  5572  5619 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-03 23:35:03.953  5572  5619 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-03 23:35:03.953  5572  5619 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-03 23:35:03.953  5572  5619 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,11-03 23:35:03.953  5572  5619 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-03 23:35:03.953  5572  5619 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c39033a not in the list
11-03 23:35:03.953  5572  5619 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-03 23:35:03.953  5572  5619 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c1e3beb not in the list
,11-03 23:35:03.953  5572  5619 D io.jxcore.node.ConnectivityMonitor: stop
11-03 23:35:03.954  5572  5619 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-03 23:35:03.955  5572  5619 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-03 23:35:03.955  5572  5619 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
,11-03 23:35:03.955  5572  5619 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-03 23:35:03.955  5572  5619 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-03 23:35:03.955  5572  5619 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,11-03 23:35:03.955  5572  5619 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-03 23:35:03.956  5572  5619 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c1e3beb not in the list
11-03 23:35:03.957  5572  5619 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
11-03 23:35:03.957  5572  5619 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
,11-03 23:35:03.957  5572  5619 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
11-03 23:35:03.957  5572  5619 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
11-03 23:35:03.957  5572  5619 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
11-03 23:35:03.957  5572  5619 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,11-03 23:35:03.960  5572  5619 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
11-03 23:35:03.960  5572  5619 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
11-03 23:35:03.960  5572  5619 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
,11-03 23:35:03.961  5572  5619 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
11-03 23:35:03.961  5572  5619 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
11-03 23:35:03.961  5572  5619 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
11-03 23:35:03.961  5572  5619 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
,11-03 23:35:03.961  5572  5619 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
11-03 23:35:03.962  5572  5619 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
11-03 23:35:03.962  5572  5619 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
,11-03 23:35:03.962  5572  5619 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
11-03 23:35:03.963  5572  5619 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
11-03 23:35:03.963  5572  5619 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
11-03 23:35:03.963  5572  5619 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
,11-03 23:35:03.964  5572  5619 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,11-03 23:35:03.964  5572  5619 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@9a89878 added. We now have 3 listener(s)
11-03 23:35:03.964  5572  5619 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-03 23:35:03.966  5572  5619 D BluetoothAdapter: enable(): BT is already enabled..!
,11-03 23:35:03.967   928  3435 D WifiService: setWifiEnabled: true pid=5572, uid=10077
11-03 23:35:03.967   928  3435 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-03 23:35:04.012  4675  4864 W bt_sdp  : SDP - Rcvd conn cnf with error: 0x4  CID 0x40
,11-03 23:35:04.013  4675  4869 E bt_btif_sock_rfcomm: find_rfc_slot_by_id unable to find RFCOMM slot id: 5
,11-03 23:35:04.434  5572  5572 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-03 23:35:05.105   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-03 23:35:05.796   928  2960 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,11-03 23:35:06.106   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-03 23:35:07.107   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-03 23:35:08.108   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-03 23:35:08.971  5572  5619 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,11-03 23:35:08.972  5572  5619 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@dab51 added. We now have 4 listener(s)
,11-03 23:35:08.972  5572  5619 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-03 23:35:08.986  5572  5619 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-03 23:35:08.986  5572  5619 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@dab51 removed from the list
11-03 23:35:08.986  5572  5619 D io.jxcore.node.ConnectivityMonitor: stop
11-03 23:35:08.989  5572  5619 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-03 23:35:08.990  5572  5619 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1aacfb6 added. We now have 4 listener(s)
,11-03 23:35:08.990  5572  5619 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-03 23:35:08.995  5572  5619 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-03 23:35:08.995  5572  5619 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1aacfb6 removed from the list
,11-03 23:35:08.995  5572  5619 D io.jxcore.node.ConnectivityMonitor: stop
11-03 23:35:08.997  5572  5619 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,11-03 23:35:08.997  5572  5619 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@dc814b7 added. We now have 4 listener(s)
11-03 23:35:08.997  5572  5619 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-03 23:35:09.005   928  3682 D WifiService: setWifiEnabled: false pid=5572, uid=10077
,11-03 23:35:09.005   928  3682 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-03 23:35:09.014   928  2958 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,11-03 23:35:09.014   928  2958 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
11-03 23:35:09.014   928  2958 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,11-03 23:35:09.015   928  2958 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-03 23:35:09.020  4675  4741 D BluetoothAdapterState: Current state: ON, message: 23
11-03 23:35:09.020  4675  4741 D BluetoothAdapterProperties: Setting state to 13
11-03 23:35:09.020  4675  4741 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
11-03 23:35:09.020  5572  5619 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-03 23:35:09.023  5572  5619 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
11-03 23:35:09.023  4675  4741 D BluetoothAdapterProperties: onBluetoothDisable()
11-03 23:35:09.024  4675  4741 I BluetoothAdapterState: Entering PendingCommandState
11-03 23:35:09.027  4675  4675 D BluetoothMapService: onReceive
11-03 23:35:09.027  4675  4675 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
11-03 23:35:09.027  4675  4675 D BluetoothMapService: STATE_TURNING_OFF
11-03 23:35:09.027  4675  4675 D BluetoothMapService: MAP Service closeService in
11-03 23:35:09.027  4675  4675 D BluetoothMapMasInstance0: MAP Service shutdown
,11-03 23:35:09.028  4675  4675 D ObexServerSockets0: shutdown(block = true)
11-03 23:35:09.033  4675  4675 D ObexServerSockets0: shutdown called from another thread - interrupt().
11-03 23:35:09.033  4675  4675 D ObexServerSockets0: shutdown called from another thread - interrupt().
,11-03 23:35:09.033  4675  4882 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 5
11-03 23:35:09.034  4675  4869 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
11-03 23:35:09.034  4675  4883 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
,11-03 23:35:09.037  4675  4675 I BtOppRfcommListener: stopping Accept Thread
,11-03 23:35:09.038   928  5347 D DhcpClient: Clearing IP address
,11-03 23:35:09.038  4675  5296 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
11-03 23:35:09.038   507   921 D CommandListener: Clearing all IP addresses on wlan0
11-03 23:35:09.038  4675  5296 I BtOppRfcommListener: BluetoothSocket listen thread finished
,11-03 23:35:09.041   507   921 D CommandListener: Setting iface cfg
,11-03 23:35:09.044   928  5348 D DhcpClient: Receive thread stopped
,11-03 23:35:09.049  3596  5398 V NativeCrypto: Read error: ssl=0x7f82009380: I/O error during system call, Connection timed out
,11-03 23:35:09.051  3596  5398 V NativeCrypto: SSL shutdown failed: ssl=0x7f82009380: I/O error during system call, Broken pipe
11-03 23:35:09.053   928  3682 D ConnectivityService: reportNetworkConnectivity(100, false) by 10012
11-03 23:35:09.054   928  5345 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Forcing reevaluation for UID 10012
,11-03 23:35:09.057   928  5345 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.gstatic.com": No address associated with hostname
11-03 23:35:09.059   928  2960 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] validation failed
11-03 23:35:09.059   928  2960 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,11-03 23:35:09.060   928  2960 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
11-03 23:35:09.061   928   941 I ActivityManager: Start proc 5638:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
11-03 23:35:09.062  4675  4747 D BluetoothAdapterProperties: Scan Mode:20
11-03 23:35:09.063  4675  4741 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
,11-03 23:35:09.067   928  2960 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
,11-03 23:35:09.067  4675  4675 D HeadsetService: Received stop request...Stopping profile...
11-03 23:35:09.068   928  2960 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
11-03 23:35:09.069   533   533 E Parcel  : Reading a NULL string not supported here.
11-03 23:35:09.071  5572  5619 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-03 23:35:09.071  5572  5619 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-03 23:35:09.071  5572  5619 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-03 23:35:09.071  5572  5619 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-03 23:35:09.071  5572  5619 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-03 23:35:09.071  5572  5619 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-03 23:35:09.071  5572  5619 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-03 23:35:09.071  5572  5619 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-03 23:35:09.071  5572  5619 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,11-03 23:35:09.073  5572  5619 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,11-03 23:35:09.073  5572  5619 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,11-03 23:35:09.073   928  2960 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
11-03 23:35:09.074  5572  5619 D io.jxcore.node.ConnectivityMonitor: start: OK
11-03 23:35:09.073   928   928 D RttService: SCAN_AVAILABLE : 1
11-03 23:35:09.076   928  3069 D RttService: EnabledState got{ when=-2ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
11-03 23:35:09.076   928   928 D BluetoothHeadset: Proxy object disconnected
,11-03 23:35:09.076  3742  3856 W QCNEJ   : |CORE| network lost: 100
11-03 23:35:09.077  3130  3142 D BluetoothHeadset: Proxy object disconnected
11-03 23:35:09.077  3742  3856 W QCNEJ   : |CORE| onLost: unbind the process to WIFI
11-03 23:35:09.077   928   928 D BluetoothHeadset: Proxy object disconnected
11-03 23:35:09.077   928   928 D BluetoothHeadset: Proxy object disconnected
11-03 23:35:09.078  4675  4675 D A2dpService: Received stop request...Stopping profile...
11-03 23:35:09.078  3785  3808 D BluetoothHeadset: Proxy object disconnected
11-03 23:35:09.080  4675  4675 V BluetoothAdapterState: isTurningOff()=true
11-03 23:35:09.079   928   928 D BluetoothA2dp: Proxy object disconnected
11-03 23:35:09.079  4675  4875 D A2dpStateMachine: Exit Disconnected: -1
11-03 23:35:09.080  4675  4675 V BluetoothAdapterState: isTurningOn()=false
11-03 23:35:09.080  4675  4675 V BluetoothAdapterState: isBleTurningOn()=false
11-03 23:35:09.080  4675  4675 V BluetoothAdapterState: isBleTurningOff()=false
11-03 23:35:09.081  5572  5572 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,11-03 23:35:09.081  5572  5572 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-03 23:35:09.081  5572  5572 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-03 23:35:09.081  5572  5572 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-03 23:35:09.081  5572  5572 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-03 23:35:09.081  5572  5572 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-03 23:35:09.081  5572  5572 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-03 23:35:09.081  5572  5572 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-03 23:35:09.081  5572  5572 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-03 23:35:09.081  4675  4675 D HidService: Received stop request...Stopping profile...
11-03 23:35:09.081  4675  4675 D HidService: Stopping Bluetooth HidService
11-03 23:35:09.081   928  2958 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
11-03 23:35:09.082  5572  5572 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-03 23:35:09.082  4675  4675 D HealthService: Received stop request...Stopping profile...
11-03 23:35:09.084  5572  5572 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-03 23:35:09.085  4675  4675 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
11-03 23:35:09.085  4675  4675 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
11-03 23:35:09.085  4675  4747 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
11-03 23:35:09.085  4675  4864 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-03 23:35:09.085  4675  4864 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-03 23:35:09.085  4675  4864 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,11-03 23:35:09.086  4675  4675 D PanService: Received stop request...Stopping profile...
11-03 23:35:09.086  4675  4747 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
11-03 23:35:09.087  4675  4675 V BluetoothAdapterState: isTurningOff()=true
11-03 23:35:09.087  4675  4675 V BluetoothAdapterState: isTurningOn()=false
11-03 23:35:09.087  4675  4675 V BluetoothAdapterState: isBleTurningOn()=false
11-03 23:35:09.087  4675  4675 V BluetoothAdapterState: isBleTurningOff()=false
11-03 23:35:09.087  4675  4675 D BluetoothMapService: Received stop request...Stopping profile...
11-03 23:35:09.088  4675  4675 D BluetoothMapService: stop()
11-03 23:35:09.088  4675  4675 D BluetoothMapAppObserver: deinitObservers()
11-03 23:35:09.089  4675  4675 D BluetoothMapAppObserver: removeReceiver()
,11-03 23:35:09.091  4675  4864 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,11-03 23:35:09.091   928  2958 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
11-03 23:35:09.092  4675  4864 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-03 23:35:09.092  4675  4747 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
11-03 23:35:09.092  4675  4675 D SapService: Received stop request...Stopping profile...
11-03 23:35:09.092  4675  4675 V SapService: stop()
11-03 23:35:09.093  4675  4864 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
11-03 23:35:09.093  4675  4864 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
11-03 23:35:09.093  4675  4864 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
11-03 23:35:09.093  4675  4864 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,11-03 23:35:09.094  4675  4675 V BluetoothAdapterState: isTurningOff()=true
,11-03 23:35:09.094  4675  4675 V BluetoothAdapterState: isTurningOn()=false
11-03 23:35:09.094  4675  4675 V BluetoothAdapterState: isBleTurningOn()=false
11-03 23:35:09.094  4675  4675 V BluetoothAdapterState: isBleTurningOff()=false
11-03 23:35:09.095  4675  4675 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
11-03 23:35:09.095  4675  4675 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
11-03 23:35:09.095  4675  4675 V BluetoothAdapterState: isTurningOff()=true
11-03 23:35:09.095  4675  4675 V BluetoothAdapterState: isTurningOn()=false
11-03 23:35:09.095  4675  4675 V BluetoothAdapterState: isBleTurningOn()=false
11-03 23:35:09.095  4675  4675 V BluetoothAdapterState: isBleTurningOff()=false
11-03 23:35:09.095  4675  4675 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
,11-03 23:35:09.096  4675  4675 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
11-03 23:35:09.096  4675  4675 V BluetoothAdapterState: isTurningOff()=true
11-03 23:35:09.096  4675  4675 V BluetoothAdapterState: isTurningOn()=false
11-03 23:35:09.096  4675  4675 V BluetoothAdapterState: isBleTurningOn()=false
11-03 23:35:09.096  4675  4675 V BluetoothAdapterState: isBleTurningOff()=false
11-03 23:35:09.096  4675  4675 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
11-03 23:35:09.096  4675  4675 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
11-03 23:35:09.097  4675  4675 D BluetoothMapService: MAP Service closeService in
11-03 23:35:09.097  4675  4675 V BluetoothAdapterState: isTurningOff()=true
11-03 23:35:09.097  4675  4675 V BluetoothAdapterState: isTurningOn()=false
11-03 23:35:09.097  4675  4675 V BluetoothAdapterState: isBleTurningOn()=false
,11-03 23:35:09.097  4675  4675 V BluetoothAdapterState: isBleTurningOff()=false
11-03 23:35:09.098  4675  4675 D BluetoothMapService: cleanup()
11-03 23:35:09.098  4675  4675 D BluetoothMapService: MAP Service closeService in
11-03 23:35:09.098  4675  4675 V BluetoothAdapterState: isTurningOff()=true
11-03 23:35:09.098  4675  4675 V BluetoothAdapterState: isTurningOn()=false
11-03 23:35:09.098  4675  4675 V BluetoothAdapterState: isBleTurningOn()=false
11-03 23:35:09.098  4675  4675 V BluetoothAdapterState: isBleTurningOff()=false
11-03 23:35:09.098  4675  4747 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
11-03 23:35:09.098  4675  4747 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
11-03 23:35:09.098  4675  4741 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
11-03 23:35:09.098  4675  4741 D BluetoothAdapterProperties: Setting state to 15
11-03 23:35:09.098  4675  4741 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
11-03 23:35:09.099  4675  4741 I BluetoothAdapterState: Entering BleOnState
11-03 23:35:09.099  3130  3130 D HeadsetProfile: Bluetooth service disconnected
11-03 23:35:09.099  3130  3130 D BluetoothA2dp: Proxy object disconnected
11-03 23:35:09.099  3130  3130 D BluetoothInputDevice: Proxy object disconnected
11-03 23:35:09.099  3130  3130 D HidProfile: Bluetooth service disconnected
11-03 23:35:09.099  3130  3130 D BluetoothPan: BluetoothPAN Proxy object disconnected
11-03 23:35:09.099  3130  3130 D PanProfile: Bluetooth service disconnected
11-03 23:35:09.100  3130  3130 D BluetoothMap: Proxy object disconnected
,11-03 23:35:09.100  3130  3130 D MapProfile: Bluetooth service disconnected
,11-03 23:35:09.102   507   921 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
11-03 23:35:09.103   928   945 D BluetoothHeadset: onBluetoothStateChange: up=false
,11-03 23:35:09.103   928   945 D BluetoothHeadset: onBluetoothStateChange: up=false
,11-03 23:35:09.105  3130  3142 D BluetoothPan: onBluetoothStateChange on: false
11-03 23:35:09.106  3130  3141 D BluetoothPbap: onBluetoothStateChange: up=false
11-03 23:35:09.107  3130  5423 D BluetoothMap: onBluetoothStateChange: up=false
11-03 23:35:09.108  3130  3141 D BluetoothInputDevice: onBluetoothStateChange: up=false
11-03 23:35:09.109  3130  3142 D BluetoothA2dp: onBluetoothStateChange: up=false
11-03 23:35:09.109   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-03 23:35:09.109  3785  3992 D BluetoothHeadset: onBluetoothStateChange: up=false
11-03 23:35:09.109   928   945 D BluetoothHeadset: onBluetoothStateChange: up=false
11-03 23:35:09.110  3130  5423 D BluetoothHeadset: onBluetoothStateChange: up=false
11-03 23:35:09.110   928   945 D BluetoothA2dp: onBluetoothStateChange: up=false
11-03 23:35:09.110  4675  4741 D BluetoothAdapterState: Current state: BLE ON, message: 20
11-03 23:35:09.110  4675  4741 D BluetoothAdapterProperties: Setting state to 16
,11-03 23:35:09.110  4675  4741 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
11-03 23:35:09.112  4675  4741 D BluetoothAdapterProperties: onBleDisable
11-03 23:35:09.112  4675  4741 I BluetoothAdapterState: Entering PendingCommandState
11-03 23:35:09.112  4675  4743 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
,11-03 23:35:09.113  4675  4747 D BluetoothAdapterProperties: Scan Mode:20
11-03 23:35:09.113  5572  5572 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-03 23:35:09.114  4675  4864 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
11-03 23:35:09.114  4675  4864 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-03 23:35:09.115  5572  5572 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-03 23:35:09.123  5638  5638 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm64
,11-03 23:35:09.132   507   921 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-03 23:35:09.132   507   921 D CommandListener: Clearing all IP addresses on wlan0
11-03 23:35:09.133   507   921 D TetherController: Setting IP forward enable = 0
11-03 23:35:09.134   928  2960 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
11-03 23:35:09.134   928  2960 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
11-03 23:35:09.136   928   945 D Tethering: MasterInitialState.processMessage what=3
11-03 23:35:09.136   928  2958 D DhcpClient: doQuit
,11-03 23:35:09.137   928  2958 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
11-03 23:35:09.137   928  5347 D DhcpClient: onQuitting
11-03 23:35:09.138  3461  3461 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
,11-03 23:35:09.139  5572  5572 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-03 23:35:09.141  3947  3947 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
,11-03 23:35:09.138  5233  5233 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@b0fa138 and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
11-03 23:35:09.143  5572  5572 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-03 23:35:09.143  5572  5572 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-03 23:35:09.143  5572  5572 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-03 23:35:09.143  5572  5572 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-03 23:35:09.143  5572  5572 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-03 23:35:09.143  5572  5572 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-03 23:35:09.143  5572  5572 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-03 23:35:09.143  5572  5572 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-03 23:35:09.143  5572  5572 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-03 23:35:09.144  5572  5572 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-03 23:35:09.144  5572  5572 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,11-03 23:35:09.147  5638  5638 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,11-03 23:35:09.154  3596  3596 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,11-03 23:35:09.154   928   945 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@4ae7178:true
,11-03 23:35:09.162  3461  3461 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
,11-03 23:35:09.167  3461  3461 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,11-03 23:35:09.168   507   914 W SocketClient: write error (Broken pipe)
11-03 23:35:09.168   507   914 W SocketClient: Unable to send msg '600 Iface linkstate wlan0 up'
11-03 23:35:09.168   507   914 W SocketListener: Error sending broadcast (Broken pipe)
,11-03 23:35:09.174  5638  5638 D LocalBluetoothProfileManager: Adding local MAP profile
,11-03 23:35:09.176  5638  5638 D BluetoothMap: Create BluetoothMap proxy object
,11-03 23:35:09.183  5638  5638 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,11-03 23:35:09.190  5638  5638 D DockEventReceiver: finishStartingService: stopping service
,11-03 23:35:09.191   507   921 E Netd    : netlink response contains error (No such file or directory)
11-03 23:35:09.192   507   921 D TetherController: Setting IP forward enable = 0
11-03 23:35:09.192   928  2960 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,11-03 23:35:09.193  5638  5638 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,11-03 23:35:09.198  5638  5638 D DockEventReceiver: finishStartingService: stopping service
11-03 23:35:09.198  3596  3596 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
11-03 23:35:09.200   928  3796 I ActivityManager: Killing 5371:com.android.sdm.plugins.sprintdm/1001 (adj 15): empty #17
,11-03 23:35:09.204  3461  3461 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,11-03 23:35:09.212  3461  3461 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,11-03 23:35:09.222  4006  4006 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
11-03 23:35:09.225  4006  4006 D SystemUpdateService: onCreate
11-03 23:35:09.228  4006  4006 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
11-03 23:35:09.235  4006  4006 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
11-03 23:35:09.242  4006  5674 I SystemUpdateService: active receiver: enabled
11-03 23:35:09.243  4006  4256 I iu.UploadsManager: num queued entries: 0
11-03 23:35:09.243  4006  4256 I iu.UploadsManager: num updated entries: 0
11-03 23:35:09.243  4006  4256 I iu.SyncManager: NEXT; no task
11-03 23:35:09.245  4006  4006 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
11-03 23:35:09.246  4006  4006 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
11-03 23:35:09.249  4006  5674 I SystemUpdateService: Already downloaded, skipping offpeak checks.
11-03 23:35:09.251  4006  5674 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,11-03 23:35:09.251  4006  5674 I SystemUpdateService: now status is 0 (complete)
11-03 23:35:09.251  4006  5674 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
11-03 23:35:09.251  4006  5674 I SystemUpdateService: file has been verified
11-03 23:35:09.251  4006  5674 I SystemUpdateService: OTA package size = 21989297
,11-03 23:35:09.256  4006  5674 I SystemUpdateService: showing system update notification
,11-03 23:35:09.257   928   939 I ActivityManager: Start proc 5676:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,11-03 23:35:09.270   928   928 V NotificationService: pkg=com.google.android.gms canInterrupt=false intercept=true
,11-03 23:35:09.272  4006  4006 D SystemUpdateService: onDestroy
,11-03 23:35:09.294  5676  5676 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm64
,11-03 23:35:09.297  5676  5676 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,11-03 23:35:09.303  5676  5676 D SprintDMHelper: simOperator: 
,11-03 23:35:09.304  5676  5676 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,11-03 23:35:09.314   928  2958 D wifi    : In wifi stop Hal
,11-03 23:35:09.314   928  2958 D wifi    : halHandle = 0x7f6f86f680, mVM = 0x7f8be8d140, mCls = 0x100a02
11-03 23:35:09.314   928  3460 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
,11-03 23:35:09.314   928  3460 D WifiHAL : Got a signal to exit!!!
11-03 23:35:09.314   928  3460 I WifiHAL : Exit wifi_event_loop
,11-03 23:35:09.315  4521  4521 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
11-03 23:35:09.315   928  2958 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 0
11-03 23:35:09.315   928  2958 E WifiHAL : Event processing terminated
11-03 23:35:09.315   928  2958 D wifi    : In wifi cleaned up handler
11-03 23:35:09.315   928  2958 I WifiHAL : Internal cleanup completed
11-03 23:35:09.317  5572  5572 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-03 23:35:09.318  3843  4193 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
11-03 23:35:09.320   928   938 I ActivityManager: Killing 5233:com.google.android.music:main/u0a59 (adj 15): empty #17
11-03 23:35:09.321  4675  4747 I bt_hci  : shut_down
,11-03 23:35:09.340   928  3460 D wifi    : set interface wlan0 flags (DOWN)
,11-03 23:35:09.340   928  2958 D WifiNative-HAL: HAL event thread stopped successfully
,11-03 23:35:09.347   928   938 I ActivityManager: Start proc 5689:com.google.android.apps.gcs/u0a11 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,11-03 23:35:09.350  4675  4751 D bt_hwcfg: hw_epilog_process
,11-03 23:35:09.351  4675  4751 I bt_vendor: low_power_mode_cb
,11-03 23:35:09.353  4675  4751 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
11-03 23:35:09.353  4675  4751 I bt_vendor: epilog_cb
,11-03 23:35:09.353  4675  4751 I bt_hci  : epilog_finished_callback
,11-03 23:35:09.356  4675  4747 I bt_hci_h4: hal_close
,11-03 23:35:09.358  4675  4747 I bt_userial_vendor: device fd = 54 close
,11-03 23:35:09.377  5689  5689 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm64
,11-03 23:35:09.384   928  3167 I ActivityManager: Killing 5447:com.android.defcontainer/u0a7 (adj 15): empty #17
,11-03 23:35:09.468  4675  4743 D bt_stack_manager: event_shut_down_stack finished.
,11-03 23:35:09.468  4675  4741 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,11-03 23:35:09.470  4675  4741 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,11-03 23:35:09.470  4675  4675 D BtGatt.DebugUtils: handleDebugAction() action=null
,11-03 23:35:09.470  4675  4675 D BtGatt.GattService: Received stop request...Stopping profile...
,11-03 23:35:09.470  4675  4675 D BtGatt.GattService: stop()
11-03 23:35:09.470  4675  4675 D BtGatt.AdvertiseManager: advertise clients cleared
11-03 23:35:09.471  4675  4675 V BluetoothAdapterState: isTurningOff()=false
11-03 23:35:09.472  4675  4675 V BluetoothAdapterState: isTurningOn()=false
11-03 23:35:09.472  4675  4675 V BluetoothAdapterState: isBleTurningOn()=false
11-03 23:35:09.472  4675  4675 V BluetoothAdapterState: isBleTurningOff()=true
,11-03 23:35:09.472  4675  4741 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
11-03 23:35:09.472  4675  4741 D BluetoothAdapterProperties: Setting state to 10
11-03 23:35:09.472  4675  4741 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
11-03 23:35:09.472  4675  4741 I BluetoothAdapterState: Entering OffState
,11-03 23:35:09.473   928   945 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,11-03 23:35:09.478  4675  4675 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
11-03 23:35:09.478  4675  4675 W BluetoothSdpJni: Cleaning up Bluetooth Health object
11-03 23:35:09.478  4675  4675 I BluetoothServiceJni: cleanupNative: return from cleanup
11-03 23:35:09.480  4675  4743 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,11-03 23:35:09.483  4675  4675 I art     : System.exit called, status: 0
,11-03 23:35:09.483  4675  4675 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,11-03 23:35:09.506   928  3780 I ActivityManager: Process com.android.bluetooth (pid 4675) has died
,11-03 23:35:09.543   928   945 D Tethering: InitialState.processMessage what=4
,11-03 23:35:09.547   928   945 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,11-03 23:35:10.109   535   535 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,11-03 23:35:14.076   928   938 D WifiService: setWifiEnabled: true pid=5572, uid=10077
,11-03 23:35:14.077   928   938 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-03 23:35:14.090   507   921 D SoftapController: Softap fwReload - Ok
,11-03 23:35:14.097   507   921 D CommandListener: Setting iface cfg
,11-03 23:35:14.097   507   921 D CommandListener: Trying to bring down wlan0
,11-03 23:35:14.101   507   921 D CommandListener: Clearing all IP addresses on wlan0
,11-03 23:35:14.108   928  2958 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,11-03 23:35:14.692   928  2958 D wifi    : set interface wlan0 flags (UP)
,11-03 23:35:14.697   928  2958 I WifiHAL : Initializing wifi
,11-03 23:35:14.697   928  2958 I WifiHAL : Creating socket
,11-03 23:35:14.702   928   945 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,11-03 23:35:14.705   928  2958 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
,11-03 23:35:14.705   928  2958 D wifi    : Did set static halHandle = 0x7f6f86f680
11-03 23:35:14.705   928  2958 D wifi    : halHandle = 0x7f6f86f680, mVM = 0x7f8be8d140, mCls = 0x196e
11-03 23:35:14.706   928  2958 D wifi    : array field set
11-03 23:35:14.706   928  2958 I WifiNative-HAL: interface[0] = wlan0
,11-03 23:35:14.708   928  5705 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=547331962496
11-03 23:35:14.708   928  5705 D wifi    : waitForHalEvents called, vm = 0x7f8be8d140, obj = 0x196e, env = 0x7f74752240
,11-03 23:35:14.770  5706  5706 I wpa_supplicant: Successfully initialized wpa_supplicant
,11-03 23:35:14.810   928  2958 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,11-03 23:35:14.819  5572  5572 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-03 23:35:14.846  5706  5706 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,11-03 23:35:14.899  5706  5706 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,11-03 23:35:14.899  5706  5706 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,11-03 23:35:14.920   928  2958 D WifiConfigStore: Loading config and enabling all networks 
,11-03 23:35:14.924  5572  5572 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,11-03 23:35:14.924  5572  5572 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-03 23:35:14.924  5572  5572 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-03 23:35:14.924  5572  5572 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-03 23:35:14.924  5572  5572 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-03 23:35:14.924  5572  5572 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-03 23:35:14.924  5572  5572 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-03 23:35:14.924  5572  5572 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-03 23:35:14.924  5572  5572 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-03 23:35:14.925  5572  5572 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-03 23:35:14.925  5572  5572 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,11-03 23:35:14.945   928  2958 D WifiConfigStore: loaded 0 passpoint configs
,11-03 23:35:14.945   928  2958 W WifiConfigStore: Upgrading network 4 to android.uid.system:1000
,11-03 23:35:14.946   928  2958 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
11-03 23:35:14.946   928  2958 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,11-03 23:35:14.947   928  2958 W WifiConfigStore: Upgrading network 3 to android.uid.system:1000
11-03 23:35:14.947   928  2958 W WifiConfigStore: Upgrading network 2 to android.uid.system:1000
,11-03 23:35:14.947   928  2958 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,11-03 23:35:14.948   928  2958 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 5
11-03 23:35:14.948   928  2958 E WifiConfigStore: found sortedWifiConfigurations : "AndroidAP"WPA_PSK
11-03 23:35:14.948   928  2958 E WifiConfigStore: found sortedWifiConfigurations : "AndroidHotspot2346"WPA_PSK
11-03 23:35:14.948   928  2958 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,11-03 23:35:14.948   928  2958 E WifiConfigStore: found sortedWifiConfigurations : "Thali_internal"WPA_PSK
11-03 23:35:14.948   928  2958 E WifiConfigStore: found sortedWifiConfigurations : "MC"WPA_PSK
,11-03 23:35:14.950   928  2958 D WifiNative-HAL: Setting external_sim to 1
,11-03 23:35:14.951   928  2958 D wifi    : setting dfs flag to true, 0x7f7047ebe0
11-03 23:35:14.951  4521  4521 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
11-03 23:35:14.951   928  2958 D WifiStateMachine: Setting OUI to DA-A1-19
11-03 23:35:14.951   928  2958 D wifi    : setting scan oui 0x7f7047ebe0
11-03 23:35:14.951   928  2958 D WifiHAL : Sending mac address OUI
,11-03 23:35:14.954   928  2958 E native  : do suspend false
,11-03 23:35:14.961   928  2958 D wifi    : android_net_wifi_setLinkLayerStats: 1
11-03 23:35:14.961   507   921 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,11-03 23:35:14.962   928   928 D RttService: SCAN_AVAILABLE : 3
11-03 23:35:14.962   928  3069 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,11-03 23:35:14.963   507   921 D CommandListener: Setting iface cfg
,11-03 23:35:14.966   928  2957 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '119 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 119 Failed to set address (No such device)'
,11-03 23:35:14.966   928  2957 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,11-03 23:35:14.978   928   943 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=128413 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=12 mControllerEnergyUsed=45 }
,11-03 23:35:14.979   928  2957 D WifiNative-HAL: p2pGetDeviceAddress
11-03 23:35:14.979   928  2957 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:70
,11-03 23:35:15.110   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-03 23:35:16.111   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-03 23:35:17.112   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-03 23:35:18.020  5706  5706 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-03 23:35:18.023  5706  5706 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-03 23:35:18.028  5706  5706 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-03 23:35:18.073   928  2958 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,11-03 23:35:18.074   928  2958 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3
,11-03 23:35:18.074   928  2958 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-03 23:35:18.084   928  2958 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=0
,11-03 23:35:18.113   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-03 23:35:18.115   928  2958 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=0
,11-03 23:35:18.121  5706  5706 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,11-03 23:35:18.549  5706  5706 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,11-03 23:35:18.577  5706  5706 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,11-03 23:35:18.577  5706  5706 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,11-03 23:35:18.586   928  2958 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,11-03 23:35:18.586   928  2958 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
11-03 23:35:18.587   928  2960 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,11-03 23:35:18.604   928  2958 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-03 23:35:18.613   507   921 D CommandListener: Setting iface cfg
,11-03 23:35:18.617   928  2958 D WifiStateMachine: Start Dhcp Watchdog 2
,11-03 23:35:18.622   928  5714 D DhcpClient: Receive thread started
,11-03 23:35:18.627   928  2958 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,11-03 23:35:18.627   928  2960 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
11-03 23:35:18.627   928  2960 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
,11-03 23:35:18.707   928  2958 E native  : do suspend false
,11-03 23:35:18.716   928  5713 D DhcpClient: Broadcasting DHCPDISCOVER
,11-03 23:35:18.736   928  5714 D DhcpClient: Received packet: 60:83:34:25:d7:70 OFFER, ip /192.168.1.105, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172709, domain null
,11-03 23:35:18.737   928  5713 D DhcpClient: Got pending lease: IP address 192.168.1.105/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172709 seconds
,11-03 23:35:18.739   928  5713 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.105 serverid=192.168.1.1
,11-03 23:35:18.762   928  5714 D DhcpClient: Received packet: 60:83:34:25:d7:70 ACK: your new IP /192.168.1.105, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,11-03 23:35:18.762   928  5713 D DhcpClient: Confirmed lease: IP address 192.168.1.105/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,11-03 23:35:18.765   507   921 D CommandListener: Setting iface cfg
,11-03 23:35:18.769   928  2958 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,11-03 23:35:18.772   928  5713 D DhcpClient: Scheduling renewal in 86399s
,11-03 23:35:18.780   928  2958 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,11-03 23:35:18.781   928  2958 D WifiConfigStore: No blacklist allowed without epno enabled
11-03 23:35:18.782   928  2960 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
11-03 23:35:18.785   928  2960 D ConnectivityService: Adding iface wlan0 to network 101
,11-03 23:35:18.796   928  2958 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,11-03 23:35:18.836   928  2960 E ConnectivityService: Unexpected mtu value: 0, wlan0
,11-03 23:35:18.837   928  2960 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
,11-03 23:35:18.839   928  2960 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,11-03 23:35:18.841   928  2960 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,11-03 23:35:18.843   928  2960 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,11-03 23:35:18.853   928  2960 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-03 23:35:18.859   928  2960 D ConnectivityService: scheduleUnvalidatedPrompt 101
,11-03 23:35:18.859   928  2960 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
11-03 23:35:18.859   928  2960 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
11-03 23:35:18.859   928  2958 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
11-03 23:35:18.859   928  2960 D ConnectivityService:    accepting network in place of null
11-03 23:35:18.859   928  2958 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,11-03 23:35:18.860   928  2960 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d770/64,192.168.1.105/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -47]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,11-03 23:35:18.876   928  5712 D NetlinkSocketObserver: NeighborEvent{elapsedMs=132311, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,11-03 23:35:18.884   507   921 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-03 23:35:18.906   507   921 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-03 23:35:18.909   928  2960 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,11-03 23:35:18.909   928  2960 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,11-03 23:35:18.909  3742  3856 W QCNEJ   : |CORE| network available: 101
11-03 23:35:18.910   928  2960 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
,11-03 23:35:18.913   928   945 D Tethering: MasterInitialState.processMessage what=3
11-03 23:35:18.914  3742  3856 W QCNEJ   : |CORE| onAvailable: bind the process to WIFI
,11-03 23:35:18.915  3742  3856 W QCNEJ   : |CORE| newLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d770/64,192.168.1.105/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}
11-03 23:35:18.916  3742  3856 W QCNEJ   : |CORE| curLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d770/64,192.168.1.105/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
11-03 23:35:18.920  5572  5572 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,11-03 23:35:18.920  5572  5572 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-03 23:35:18.920  5572  5572 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-03 23:35:18.920  5572  5572 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-03 23:35:18.920  5572  5572 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-03 23:35:18.920  5572  5572 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-03 23:35:18.920  5572  5572 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-03 23:35:18.920  5572  5572 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-03 23:35:18.920  5572  5572 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
11-03 23:35:18.920  5572  5572 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-03 23:35:18.920  5572  5572 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,11-03 23:35:18.923  3947  3947 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
,11-03 23:35:18.926  4006  4006 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,11-03 23:35:18.929  4006  4006 D SystemUpdateService: onCreate
11-03 23:35:18.932  4006  4006 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,11-03 23:35:18.943  4006  4006 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,11-03 23:35:18.949  4006  5724 I SystemUpdateService: active receiver: enabled
,11-03 23:35:18.951  4006  4256 I iu.UploadsManager: num queued entries: 0
11-03 23:35:18.951  4006  4256 I iu.UploadsManager: num updated entries: 0
,11-03 23:35:18.952   928  5711 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.214.238,2a00:1450:400d:803::200e
,11-03 23:35:18.954  4006  4006 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,11-03 23:35:18.956  4006  4006 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,11-03 23:35:18.958  5676  5676 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,11-03 23:35:18.961  5676  5676 D SprintDMHelper: simOperator: 
,11-03 23:35:18.961  5676  5676 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,11-03 23:35:18.984  4006  5724 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,11-03 23:35:18.986  4006  4256 I iu.SyncManager: NEXT; no task
,11-03 23:35:18.990  4006  5724 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,11-03 23:35:18.990  4006  5724 I SystemUpdateService: now status is 0 (complete)
11-03 23:35:18.990  4006  5724 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
11-03 23:35:18.990  4006  5724 I SystemUpdateService: file has been verified
11-03 23:35:18.991  4006  5724 I SystemUpdateService: OTA package size = 21989297
,11-03 23:35:18.996  4006  5724 I SystemUpdateService: showing system update notification
,11-03 23:35:19.004   928  5711 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Thu, 03 Nov 2016 22:35:18 GMT], X-Android-Received-Millis=[1478212519003], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1478212518979]}
,11-03 23:35:19.004   928  2960 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
11-03 23:35:19.004   928   928 V NotificationService: pkg=com.google.android.gms canInterrupt=false intercept=true
11-03 23:35:19.004   928  2960 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation  passed
,11-03 23:35:19.004   928  2960 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-03 23:35:19.005  4006  4006 D SystemUpdateService: onDestroy
11-03 23:35:19.005   928  2960 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,11-03 23:35:19.086   928   939 D WifiService: setWifiEnabled: false pid=5572, uid=10077
11-03 23:35:19.086   928   939 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-03 23:35:19.088   928  2958 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,11-03 23:35:19.088   928  2958 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
11-03 23:35:19.088   928  2958 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
11-03 23:35:19.088   928  2958 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-03 23:35:19.097   928  5713 D DhcpClient: Clearing IP address
11-03 23:35:19.097   507   921 D CommandListener: Clearing all IP addresses on wlan0
,11-03 23:35:19.099   507   921 D CommandListener: Setting iface cfg
,11-03 23:35:19.105  3596  5731 V NativeCrypto: Read error: ssl=0x7f70e6a000: I/O error during system call, Connection timed out
11-03 23:35:19.106  3596  5731 V NativeCrypto: SSL shutdown failed: ssl=0x7f70e6a000: I/O error during system call, Broken pipe
,11-03 23:35:19.115   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-03 23:35:19.117   928  2960 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
11-03 23:35:19.118   928  2960 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 3
11-03 23:35:19.122   533   533 E Parcel  : Reading a NULL string not supported here.
,11-03 23:35:19.129   928  2958 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,11-03 23:35:19.129   928   928 D RttService: SCAN_AVAILABLE : 1
,11-03 23:35:19.129   928  2960 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
11-03 23:35:19.129   928  5714 D DhcpClient: Receive thread stopped
11-03 23:35:19.129   928  3069 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,11-03 23:35:19.131  3742  3856 W QCNEJ   : |CORE| network lost: 101
11-03 23:35:19.131   928  2958 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
11-03 23:35:19.132  3742  3856 W QCNEJ   : |CORE| onLost: unbind the process to WIFI
,11-03 23:35:19.149   507   921 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-03 23:35:19.167   507   921 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-03 23:35:19.168   928  2960 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
11-03 23:35:19.168   928  2960 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
11-03 23:35:19.168   507   921 D CommandListener: Clearing all IP addresses on wlan0
,11-03 23:35:19.169   928   945 D Tethering: MasterInitialState.processMessage what=3
,11-03 23:35:19.173  5572  5572 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-03 23:35:19.173  5572  5572 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-03 23:35:19.173  5572  5572 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-03 23:35:19.173  5572  5572 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-03 23:35:19.173  5572  5572 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-03 23:35:19.173  5572  5572 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-03 23:35:19.173  5572  5572 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-03 23:35:19.173  5572  5572 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-03 23:35:19.173  5572  5572 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-03 23:35:19.173  5572  5572 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-03 23:35:19.173  5572  5572 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,11-03 23:35:19.179  3947  3947 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
,11-03 23:35:19.181  4006  4006 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,11-03 23:35:19.184  4006  4006 D SystemUpdateService: onCreate
,11-03 23:35:19.187  4006  4006 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,11-03 23:35:19.193  4006  5740 I SystemUpdateService: active receiver: enabled
,11-03 23:35:19.194  4006  4006 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,11-03 23:35:19.199  4006  4256 I iu.UploadsManager: num queued entries: 0
,11-03 23:35:19.199  4006  4256 I iu.UploadsManager: num updated entries: 0
11-03 23:35:19.200  4006  4256 I iu.SyncManager: NEXT; no task
,11-03 23:35:19.202  4006  4006 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
11-03 23:35:19.203  4006  4006 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,11-03 23:35:19.205  5676  5676 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,11-03 23:35:19.209  5676  5676 D SprintDMHelper: simOperator: 
,11-03 23:35:19.209  5676  5676 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,11-03 23:35:19.218  4006  5740 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,11-03 23:35:19.221   507   921 E Netd    : netlink response contains error (No such file or directory)
,11-03 23:35:19.222   928  2960 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
11-03 23:35:19.223   928  2958 D DhcpClient: doQuit
11-03 23:35:19.223   928  2958 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
11-03 23:35:19.223   928  5713 D DhcpClient: onQuitting
11-03 23:35:19.224  5706  5706 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
11-03 23:35:19.226  4006  5740 I SystemUpdateService: network: null; metered: false; mobile allowed: true
11-03 23:35:19.226  4006  5740 I SystemUpdateService: now status is 0 (complete)
11-03 23:35:19.226  4006  5740 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
11-03 23:35:19.226  4006  5740 I SystemUpdateService: file has been verified
11-03 23:35:19.226  4006  5740 I SystemUpdateService: OTA package size = 21989297
11-03 23:35:19.226  5572  5572 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-03 23:35:19.226  5572  5572 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-03 23:35:19.226  5572  5572 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-03 23:35:19.226  5572  5572 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-03 23:35:19.226  5572  5572 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-03 23:35:19.226  5572  5572 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-03 23:35:19.226  5572  5572 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-03 23:35:19.226  5572  5572 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-03 23:35:19.226  5572  5572 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-03 23:35:19.227  5572  5572 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-03 23:35:19.227  5572  5572 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,11-03 23:35:19.236  5706  5706 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
,11-03 23:35:19.239  4006  5740 I SystemUpdateService: showing system update notification
,11-03 23:35:19.240  5706  5706 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,11-03 23:35:19.246   928   928 V NotificationService: pkg=com.google.android.gms canInterrupt=false intercept=true
,11-03 23:35:19.247  4006  4006 D SystemUpdateService: onDestroy
,11-03 23:35:19.264  5706  5706 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,11-03 23:35:19.270  5706  5706 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,11-03 23:35:19.373   928  2958 D wifi    : In wifi stop Hal
11-03 23:35:19.373   928  2958 D wifi    : halHandle = 0x7f6f86f680, mVM = 0x7f8be8d140, mCls = 0x196e
,11-03 23:35:19.374  4521  4521 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,11-03 23:35:19.376   928  5705 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
,11-03 23:35:19.377   928  5705 D WifiHAL : Got a signal to exit!!!
11-03 23:35:19.377   928  5705 I WifiHAL : Exit wifi_event_loop
11-03 23:35:19.377   928  2958 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 0
11-03 23:35:19.377   928  2958 E WifiHAL : Event processing terminated
11-03 23:35:19.377  3843  4193 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,11-03 23:35:19.377   928  2958 D wifi    : In wifi cleaned up handler
11-03 23:35:19.377   928  2958 I WifiHAL : Internal cleanup completed
11-03 23:35:19.379  5572  5572 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-03 23:35:19.402   928  5705 D wifi    : set interface wlan0 flags (DOWN)
,11-03 23:35:19.403   928  2958 D WifiNative-HAL: HAL event thread stopped successfully
,11-03 23:35:19.607   928   945 D Tethering: InitialState.processMessage what=4
,11-03 23:35:19.613   928   945 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,11-03 23:35:19.909   928  2960 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,11-03 23:35:20.116   535   535 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,11-03 23:35:24.122   928   945 I ActivityManager: Start proc 5746:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,11-03 23:35:24.208  5746  5746 D AdapterServiceConfig: Adding HeadsetService
,11-03 23:35:24.208  5746  5746 D AdapterServiceConfig: Adding A2dpService
11-03 23:35:24.209  5746  5746 D AdapterServiceConfig: Adding HidService
11-03 23:35:24.209  5746  5746 D AdapterServiceConfig: Adding HealthService
11-03 23:35:24.209  5746  5746 D AdapterServiceConfig: Adding PanService
11-03 23:35:24.209  5746  5746 D AdapterServiceConfig: Adding GattService
11-03 23:35:24.209  5746  5746 D AdapterServiceConfig: Adding BluetoothMapService
,11-03 23:35:24.209  5746  5746 D AdapterServiceConfig: Adding SapService
,11-03 23:35:24.219   928   945 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@11b85ac:true
,11-03 23:35:24.220  5746  5746 D BluetoothAdapterState: make() - Creating AdapterState
,11-03 23:35:24.222  5746  5746 I bt_bluedroid: init
,11-03 23:35:24.222  5746  5758 I BluetoothAdapterState: Entering OffState
,11-03 23:35:24.225  5746  5759 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,11-03 23:35:24.225  5746  5759 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
11-03 23:35:24.225  5746  5759 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
11-03 23:35:24.225  5746  5759 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
11-03 23:35:24.226  5746  5746 I bt_bluedroid: get_profile_interface socket
,11-03 23:35:24.227  5746  5762 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:D4
,11-03 23:35:24.228  5746  5746 I bt_bluedroid: get_profile_interface sdp
11-03 23:35:24.229  5746  5762 D BluetoothAdapterProperties: Name is: Nexus 6P
11-03 23:35:24.233  5746  5757 I bt_bluedroid: config_hci_snoop_log
11-03 23:35:24.234   928   945 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,11-03 23:35:24.238  5746  5758 D BluetoothAdapterState: Current state: OFF, message: 0
,11-03 23:35:24.238  5746  5758 D BluetoothAdapterProperties: Setting state to 14
11-03 23:35:24.238  5746  5758 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,11-03 23:35:24.240  5746  5758 D BluetoothBondStateMachine: make
,11-03 23:35:24.242  5746  5763 I BluetoothBondStateMachine: StableState(): Entering Off State
,11-03 23:35:24.244  5746  5758 I BluetoothAdapterState: Entering PendingCommandState
,11-03 23:35:24.245  5746  5746 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,11-03 23:35:24.247  5746  5746 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@38588b7
11-03 23:35:24.248  5746  5746 D BtGatt.DebugUtils: handleDebugAction() action=null
,11-03 23:35:24.248  5746  5746 D BtGatt.GattService: Received start request. Starting profile...
11-03 23:35:24.248  5746  5746 D BtGatt.GattService: start()
11-03 23:35:24.248  5746  5746 I bt_bluedroid: get_profile_interface gatt
,11-03 23:35:24.249  5746  5746 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@38588b7
,11-03 23:35:24.250  5746  5746 D BtGatt.AdvertiseManager: advertise manager created
,11-03 23:35:24.254  5746  5746 V BluetoothAdapterState: isTurningOff()=false
11-03 23:35:24.254  5746  5746 V BluetoothAdapterState: isTurningOn()=false
11-03 23:35:24.254  5746  5746 V BluetoothAdapterState: isBleTurningOn()=true
11-03 23:35:24.254  5746  5746 V BluetoothAdapterState: isBleTurningOff()=false
11-03 23:35:24.255  5746  5758 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,11-03 23:35:24.256  5746  5758 I bt_bluedroid: bt_bluedroid
,11-03 23:35:24.256  5746  5759 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,11-03 23:35:24.256  5746  5759 I bt_hci  : start_up
,11-03 23:35:24.262  5746  5759 I bt_vendor: alloc value 0xf3bbd871
,11-03 23:35:24.262  5746  5759 I bt_vendor: init
11-03 23:35:24.262  5746  5759 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
11-03 23:35:24.263  5746  5759 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,11-03 23:35:24.375  5746  5759 D bt_hci  : start_up starting async portion
,11-03 23:35:24.376  5746  5766 I bt_hci  : event_finish_startup
11-03 23:35:24.376  5746  5766 I bt_hci_h4: hal_open
11-03 23:35:24.376  5746  5766 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,11-03 23:35:24.379  5746  5766 I bt_userial_vendor: device fd = 54 open
,11-03 23:35:24.373  5767  5767 W irq/448-msm_hs_: type=1400 audit(0.0:117): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-03 23:35:24.393  5746  5766 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,11-03 23:35:24.396  5746  5766 D bt_hwcfg: Chipset BCM4358A3
,11-03 23:35:24.396  5746  5766 D bt_hwcfg: Target name = [BCM4358A3]
,11-03 23:35:24.396  5746  5766 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,11-03 23:35:24.776  5746  5766 I bt_hwcfg: bt vendor lib: set UART baud 115200
11-03 23:35:24.776  5746  5766 D bt_hwcfg: Settlement delay -- 100 ms
11-03 23:35:24.777  5746  5766 I bt_hwcfg: Setting fw settlement delay to 100 
,11-03 23:35:24.911  5746  5766 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,11-03 23:35:24.912  5746  5766 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:D4
11-03 23:35:24.915  5746  5766 I bt_hwcfg: vendor lib fwcfg completed
11-03 23:35:24.916  5746  5766 I bt_vendor: firmware callback
11-03 23:35:24.916  5746  5766 I bt_hci  : firmware_config_callback
,11-03 23:35:24.925  5746  5769 I bt_btu  : btu_task pending for preload complete event
,11-03 23:35:24.925  5746  5769 I bt_btu_task: Bluetooth chip preload is complete
11-03 23:35:24.925  5746  5769 I bt_btu  : btu_task received preload complete event
,11-03 23:35:24.931  5746  5769 I         : BTE_InitTraceLevels -- TRC_HCI
,11-03 23:35:24.931  5746  5769 I         : BTE_InitTraceLevels -- TRC_L2CAP
11-03 23:35:24.932  5746  5769 I         : BTE_InitTraceLevels -- TRC_RFCOMM
11-03 23:35:24.932  5746  5769 I         : BTE_InitTraceLevels -- TRC_AVDT
11-03 23:35:24.932  5746  5769 I         : BTE_InitTraceLevels -- TRC_AVRC
,11-03 23:35:24.932  5746  5769 I         : BTE_InitTraceLevels -- TRC_A2D
11-03 23:35:24.932  5746  5769 I         : BTE_InitTraceLevels -- TRC_BNEP
11-03 23:35:24.932  5746  5769 I         : BTE_InitTraceLevels -- TRC_BTM
11-03 23:35:24.932  5746  5769 I         : BTE_InitTraceLevels -- TRC_GAP
,11-03 23:35:24.932  5746  5769 I         : BTE_InitTraceLevels -- TRC_PAN
,11-03 23:35:24.933  5746  5769 I         : BTE_InitTraceLevels -- TRC_SDP
11-03 23:35:24.933  5746  5769 I         : BTE_InitTraceLevels -- TRC_GATT
,11-03 23:35:24.933  5746  5769 I         : BTE_InitTraceLevels -- TRC_SMP
,11-03 23:35:24.933  5746  5769 I         : BTE_InitTraceLevels -- TRC_BTAPP
11-03 23:35:24.933  5746  5769 I         : BTE_InitTraceLevels -- TRC_BTIF
,11-03 23:35:25.014  5746  5769 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf3b3b549
11-03 23:35:25.015  5746  5769 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf3b3b549 
,11-03 23:35:25.038  5746  5762 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,11-03 23:35:25.040  5746  5762 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
11-03 23:35:25.040  5746  5762 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:D4
,11-03 23:35:25.043  5746  5762 D BluetoothAdapterProperties: Name is: Nexus 6P
,11-03 23:35:25.045  5746  5762 D BluetoothAdapterProperties: Scan Mode:20
,11-03 23:35:25.046  5746  5762 D BluetoothAdapterProperties: Discoverable Timeout:120
11-03 23:35:25.046  5746  5762 D bt_hci  : do_postload posting postload work item
,11-03 23:35:25.046  5746  5766 I bt_hci  : event_postload
11-03 23:35:25.046  5746  5766 I bt_vendor: sco_config_cb
,11-03 23:35:25.046  5746  5766 I bt_hci  : sco_config_callback postload finished.
11-03 23:35:25.051  5746  5762 D bt_bte_conf: Device ID record 1 : primary
11-03 23:35:25.051  5746  5762 D bt_bte_conf:   vendorId            = 000f
11-03 23:35:25.051  5746  5762 D bt_bte_conf:   vendorIdSource      = 0001
11-03 23:35:25.051  5746  5762 D bt_bte_conf:   product             = 1200
,11-03 23:35:25.051  5746  5762 D bt_bte_conf:   version             = 1436
11-03 23:35:25.051  5746  5762 D bt_bte_conf:   clientExecutableURL = 
11-03 23:35:25.051  5746  5762 D bt_bte_conf:   serviceDescription  = 
11-03 23:35:25.051  5746  5762 D bt_bte_conf:   documentationURL    = 
11-03 23:35:25.051  5746  5762 D bt_bte_conf: bte_load_did_conf no section named DID2.
,11-03 23:35:25.052  5746  5759 D bt_stack_manager: event_start_up_stack finished
11-03 23:35:25.053  5746  5758 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
11-03 23:35:25.053  5572  5572 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-03 23:35:25.053  5746  5758 D BluetoothAdapterProperties: Setting state to 15
11-03 23:35:25.053  5746  5758 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
,11-03 23:35:25.057  5746  5766 I bt_vendor: low_power_mode_cb
,11-03 23:35:25.055  5746  5758 I BluetoothAdapterState: Entering BleOnState
,11-03 23:35:25.060  5746  5758 D BluetoothAdapterState: Current state: BLE ON, message: 1
,11-03 23:35:25.060  5746  5758 D BluetoothAdapterProperties: Setting state to 11
11-03 23:35:25.060  5746  5758 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,11-03 23:35:25.065  5746  5746 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@38588b7
,11-03 23:35:25.067  5746  5746 D HeadsetService: Received start request. Starting profile...
,11-03 23:35:25.068  5572  5572 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-03 23:35:25.070  5746  5746 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,11-03 23:35:25.070  5746  5746 D HeadsetStateMachine: make
,11-03 23:35:25.079  5746  5758 I BluetoothAdapterState: Entering PendingCommandState
,11-03 23:35:25.080  5746  5746 D HeadsetStateMachine: max_hf_connections = 1
,11-03 23:35:25.081  5746  5746 I bt_bluedroid: get_profile_interface handsfree
11-03 23:35:25.081  5746  5762 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
11-03 23:35:25.081  5746  5762 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
,11-03 23:35:25.084  5746  5746 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@38588b7
,11-03 23:35:25.085  5746  5746 D A2dpService: Received start request. Starting profile...
,11-03 23:35:25.086  5746  5746 I BluetoothAvrcpServiceJni: classInitNative: succeeds
11-03 23:35:25.086  5746  5746 I bt_bluedroid: get_profile_interface avrcp
,11-03 23:35:25.092  5746  5746 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,11-03 23:35:25.092  5746  5746 I BluetoothA2dpServiceJni: classInitNative: succeeds
11-03 23:35:25.092  5746  5746 D A2dpStateMachine: make
,11-03 23:35:25.093  5746  5746 I bt_bluedroid: get_profile_interface a2dp
,11-03 23:35:25.094  5746  5762 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,11-03 23:35:25.097  5746  5777 D A2dpStateMachine: Enter Disconnected: -2
,11-03 23:35:25.097  5746  5746 I BluetoothHidServiceJni: classInitNative: succeeds
,11-03 23:35:25.098  5746  5746 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@38588b7
,11-03 23:35:25.099  5746  5746 D HidService: Received start request. Starting profile...
11-03 23:35:25.099  5746  5746 I bt_bluedroid: get_profile_interface hidhost
,11-03 23:35:25.099  5746  5746 D HidService: setHidService(): set to: null
11-03 23:35:25.099  5746  5762 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf3b1c56d
11-03 23:35:25.100  5746  5762 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
11-03 23:35:25.100  5638  5638 D BluetoothInputDevice: Proxy object connected
11-03 23:35:25.101  5638  5638 D HidProfile: Bluetooth service connected
,11-03 23:35:25.101  5746  5746 I BluetoothHealthServiceJni: classInitNative: succeeds
11-03 23:35:25.102  3596  3596 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,11-03 23:35:25.103  5746  5746 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@38588b7
11-03 23:35:25.103  5746  5746 D HealthService: Received start request. Starting profile...
,11-03 23:35:25.105  5746  5746 I bt_bluedroid: get_profile_interface health
11-03 23:35:25.106  5746  5746 I BluetoothPanServiceJni: classInitNative(L105): succeeds
11-03 23:35:25.106  5746  5746 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@38588b7
,11-03 23:35:25.109  5638  5638 D BluetoothPan: BluetoothPAN Proxy object connected
11-03 23:35:25.109  5746  5746 D PanService: Received start request. Starting profile...
,11-03 23:35:25.109  5746  5746 D BluetoothPanServiceJni: initializeNative(L110): pan
11-03 23:35:25.109  5746  5746 I bt_bluedroid: get_profile_interface pan
11-03 23:35:25.110  5638  5638 D PanProfile: Bluetooth service connected
11-03 23:35:25.110  5746  5762 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,11-03 23:35:25.112  5746  5746 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@38588b7
,11-03 23:35:25.113  5746  5746 D BluetoothMapService: Received start request. Starting profile...
,11-03 23:35:25.113  5746  5746 D BluetoothMapService: start()
,11-03 23:35:25.115  5746  5746 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,11-03 23:35:25.116  5746  5746 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
,11-03 23:35:25.116  5746  5746 D BluetoothMapAppObserver: createReceiver()
11-03 23:35:25.117  5746  5746 D BluetoothMapAppObserver: initObservers()
11-03 23:35:25.118  5746  5746 D BluetoothMapAppObserver: getEnabledAccountItems()
,11-03 23:35:25.122  5638  5638 D BluetoothMap: Proxy object connected
,11-03 23:35:25.123  5638  5638 D MapProfile: Bluetooth service connected
11-03 23:35:25.123  5638  5638 D BluetoothMap: getConnectedDevices()
,11-03 23:35:25.128  5746  5746 V SapService: SapBinder()
,11-03 23:35:25.128  5746  5746 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@38588b7
,11-03 23:35:25.128  5746  5746 D SapService: Received start request. Starting profile...
11-03 23:35:25.129  5746  5746 V SapService: start()
11-03 23:35:25.130  5746  5746 V BluetoothAdapterState: isTurningOff()=false
11-03 23:35:25.130  5746  5746 V BluetoothAdapterState: isTurningOn()=true
,11-03 23:35:25.130  5746  5746 V BluetoothAdapterState: isBleTurningOn()=false
11-03 23:35:25.130  5746  5775 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
11-03 23:35:25.130  5746  5746 V BluetoothAdapterState: isBleTurningOff()=false
11-03 23:35:25.130  5746  5746 V BluetoothAdapterState: isTurningOff()=false
11-03 23:35:25.130  5746  5746 V BluetoothAdapterState: isTurningOn()=true
11-03 23:35:25.130  5746  5746 V BluetoothAdapterState: isBleTurningOn()=false
11-03 23:35:25.130  5746  5746 V BluetoothAdapterState: isBleTurningOff()=false
11-03 23:35:25.130  5746  5746 V BluetoothAdapterState: isTurningOff()=false
11-03 23:35:25.130  5746  5746 V BluetoothAdapterState: isTurningOn()=true
,11-03 23:35:25.130  5746  5746 V BluetoothAdapterState: isBleTurningOn()=false
11-03 23:35:25.130  5746  5746 V BluetoothAdapterState: isBleTurningOff()=false
11-03 23:35:25.131  5746  5746 V BluetoothAdapterState: isTurningOff()=false
11-03 23:35:25.131  5746  5746 V BluetoothAdapterState: isTurningOn()=true
11-03 23:35:25.131  5746  5746 V BluetoothAdapterState: isBleTurningOn()=false
11-03 23:35:25.131  5746  5746 V BluetoothAdapterState: isBleTurningOff()=false
11-03 23:35:25.131  5746  5746 V BluetoothAdapterState: isTurningOff()=false
11-03 23:35:25.131  5746  5746 V BluetoothAdapterState: isTurningOn()=true
11-03 23:35:25.131  5746  5746 V BluetoothAdapterState: isBleTurningOn()=false
,11-03 23:35:25.131  5746  5746 V BluetoothAdapterState: isBleTurningOff()=false
11-03 23:35:25.132  5746  5746 V BluetoothAdapterState: isTurningOff()=false
11-03 23:35:25.132  5746  5746 V BluetoothAdapterState: isTurningOn()=true
,11-03 23:35:25.132  5746  5746 V BluetoothAdapterState: isBleTurningOn()=false
11-03 23:35:25.132  5746  5746 V BluetoothAdapterState: isBleTurningOff()=false
11-03 23:35:25.133  5746  5746 V BluetoothAdapterState: isTurningOff()=false
11-03 23:35:25.133  5746  5746 V BluetoothAdapterState: isTurningOn()=true
11-03 23:35:25.133  5746  5746 V BluetoothAdapterState: isBleTurningOn()=false
11-03 23:35:25.133  5746  5746 V BluetoothAdapterState: isBleTurningOff()=false
11-03 23:35:25.133  5746  5758 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
11-03 23:35:25.133  5746  5758 D BluetoothAdapterProperties: ScanMode =  20
,11-03 23:35:25.133  5746  5758 D BluetoothAdapterProperties: State =  11
11-03 23:35:25.134  5638  5638 D BluetoothMap: Bluetooth is Not enabled
11-03 23:35:25.134  5746  5762 D BluetoothAdapterProperties: Scan Mode:21
11-03 23:35:25.134  5746  5762 D BluetoothAdapterProperties: Discoverable Timeout:120
11-03 23:35:25.135  5746  5758 D BluetoothAdapterProperties: Setting state to 12
11-03 23:35:25.135  5746  5758 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
11-03 23:35:25.135  5572  5572 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
11-03 23:35:25.135   928   945 D BluetoothHeadset: onBluetoothStateChange: up=true
11-03 23:35:25.135   928   945 D BluetoothHeadset: onBluetoothStateChange: up=true
,11-03 23:35:25.135  3130  3142 D BluetoothPan: onBluetoothStateChange on: true
11-03 23:35:25.137  5746  5758 I BluetoothAdapterState: Entering OnState
11-03 23:35:25.137  3130  3130 D BluetoothPan: BluetoothPAN Proxy object connected
11-03 23:35:25.137  3130  3130 D PanProfile: Bluetooth service connected
11-03 23:35:25.138  3130  3141 D BluetoothPbap: onBluetoothStateChange: up=true
11-03 23:35:25.139  5572  5572 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-03 23:35:25.139  5572  5572 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-03 23:35:25.139  5572  5572 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-03 23:35:25.139  5572  5572 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-03 23:35:25.139  5572  5572 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-03 23:35:25.139  5572  5572 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-03 23:35:25.139  5572  5572 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-03 23:35:25.139  5572  5572 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,11-03 23:35:25.139  3130  5423 D BluetoothMap: onBluetoothStateChange: up=true
,11-03 23:35:25.141  3130  3130 D BluetoothMap: Proxy object connected
11-03 23:35:25.141  3130  3130 D MapProfile: Bluetooth service connected
11-03 23:35:25.141  5638  5650 D BluetoothPan: onBluetoothStateChange on: true
11-03 23:35:25.141  3130  3130 D BluetoothMap: getConnectedDevices()
11-03 23:35:25.141  5638  5654 D BluetoothInputDevice: onBluetoothStateChange: up=true
11-03 23:35:25.142  5572  5572 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
11-03 23:35:25.142  3130  5423 D BluetoothInputDevice: onBluetoothStateChange: up=true
11-03 23:35:25.143  3130  3141 D BluetoothA2dp: onBluetoothStateChange: up=true
,11-03 23:35:25.146  3130  3130 D BluetoothInputDevice: Proxy object connected
11-03 23:35:25.146  3130  3130 D HidProfile: Bluetooth service connected
11-03 23:35:25.146  5746  5746 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
11-03 23:35:25.146  5746  5746 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
11-03 23:35:25.147  3785  3808 D BluetoothHeadset: onBluetoothStateChange: up=true
,11-03 23:35:25.148   928   945 D BluetoothHeadset: onBluetoothStateChange: up=true
11-03 23:35:25.148  5746  5746 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-03 23:35:25.148  3130  5423 D BluetoothHeadset: onBluetoothStateChange: up=true
,11-03 23:35:25.149  5638  5650 D BluetoothMap: onBluetoothStateChange: up=true
11-03 23:35:25.149   928   945 D BluetoothA2dp: onBluetoothStateChange: up=true
11-03 23:35:25.150  5638  5654 D BluetoothPbap: onBluetoothStateChange: up=true
11-03 23:35:25.150  5746  5746 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-03 23:35:25.151   928   928 I Telecom : BluetoothPhoneService: queryPhoneState
11-03 23:35:25.152  5746  5746 D ObexServerSockets: Succeed to create listening sockets 
11-03 23:35:25.152  5746  5746 D ObexServerSockets0: startAccept()
11-03 23:35:25.152  5746  5746 D ObexServerSockets0: prepareForNewConnect()
,11-03 23:35:25.153  5572  5572 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
,11-03 23:35:25.154  5572  5572 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-03 23:35:25.154  5638  5638 D LocalBluetoothProfileManager: Adding local A2DP profile
11-03 23:35:25.155  5746  5782 D ObexServerSockets0: Accepting socket connection...
11-03 23:35:25.155  5746  5746 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
11-03 23:35:25.155  5746  5746 D BluetoothSdpJni: SDP Create record success - handle: 0
11-03 23:35:25.156  5746  5783 D ObexServerSockets0: Accepting socket connection...
11-03 23:35:25.156   928   928 D BluetoothA2dp: Proxy object connected
11-03 23:35:25.156  5746  5746 D BluetoothMapService: onReceive
,11-03 23:35:25.156  5746  5746 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
11-03 23:35:25.157  3130  3130 D BluetoothA2dp: Proxy object connected
11-03 23:35:25.157  5746  5746 D BluetoothMapService: STATE_ON
,11-03 23:35:25.159  5746  5785 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-03 23:35:25.161  5746  5785 D BluetoothSdpJni: sdpCreateSapsRecordNative:
,11-03 23:35:25.161  5746  5785 D BluetoothSdpJni: SDP Create record success - handle: 1
11-03 23:35:25.161  5638  5638 D LocalBluetoothProfileManager: Adding local HEADSET profile
,11-03 23:35:25.167  5638  5638 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,11-03 23:35:25.169  5638  5638 D BluetoothA2dp: Proxy object connected
,11-03 23:35:25.173  3596  3596 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,11-03 23:35:25.180  3130  3130 D BluetoothPbap: Proxy object connected
11-03 23:35:25.180  3130  3130 D PbapServerProfile: Bluetooth service connected
,11-03 23:35:25.180  5746  5746 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,11-03 23:35:25.181  5746  5746 D ObexServerSockets0: prepareForNewConnect()
11-03 23:35:25.181  5638  5638 D DockEventReceiver: finishStartingService: stopping service
11-03 23:35:25.182  5638  5638 D BluetoothPbap: Proxy object connected
11-03 23:35:25.182  5638  5638 D PbapServerProfile: Bluetooth service connected
,11-03 23:35:25.188  5746  5789 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-03 23:35:25.203  5746  5793 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-03 23:35:25.204  5746  5793 I BtOppRfcommListener: Accept thread started.
,11-03 23:35:25.236   928   928 D BluetoothHeadset: Proxy object connected
,11-03 23:35:25.237  3130  5423 D BluetoothHeadset: Proxy object connected
11-03 23:35:25.237  3130  3130 D HeadsetProfile: Bluetooth service connected
11-03 23:35:25.237   928   928 D BluetoothHeadset: Proxy object connected
11-03 23:35:25.237   928   928 D BluetoothHeadset: Proxy object connected
,11-03 23:35:25.237  3785  3804 D BluetoothHeadset: Proxy object connected
,11-03 23:35:25.248  3785  3992 D BluetoothHeadset: Proxy object connected
11-03 23:35:25.248   928   945 D BluetoothHeadset: Proxy object connected
11-03 23:35:25.249  3130  3142 D BluetoothHeadset: Proxy object connected
11-03 23:35:25.249  3130  3130 D HeadsetProfile: Bluetooth service connected
,11-03 23:35:25.263  5638  5654 D BluetoothHeadset: Proxy object connected
,11-03 23:35:25.265  5638  5638 D HeadsetProfile: Bluetooth service connected
,11-03 23:35:26.867   928  2960 D ConnectivityService: handlePromptUnvalidated 101
,11-03 23:35:27.543  3651  3836 I Keyboard.Facilitator.LanguageModelFlusher: run()
,11-03 23:35:27.543  3651  3836 I Keyboard.Facilitator: flushDynamicLanguageModels()
,11-03 23:35:27.573  3596  3596 I ConfigService: onCreate
,11-03 23:35:29.101  5746  5758 D BluetoothAdapterState: Current state: ON, message: 23
,11-03 23:35:29.101  5746  5758 D BluetoothAdapterProperties: Setting state to 13
11-03 23:35:29.102  5746  5758 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
11-03 23:35:29.103  5746  5758 D BluetoothAdapterProperties: onBluetoothDisable()
,11-03 23:35:29.106  5746  5758 I BluetoothAdapterState: Entering PendingCommandState
,11-03 23:35:29.111  5746  5746 D BluetoothMapService: onReceive
11-03 23:35:29.111  5746  5746 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,11-03 23:35:29.111  5746  5746 D BluetoothMapService: STATE_TURNING_OFF
11-03 23:35:29.112  5746  5746 D BluetoothMapService: MAP Service closeService in
11-03 23:35:29.112  5746  5746 D BluetoothMapMasInstance0: MAP Service shutdown
,11-03 23:35:29.112  5746  5746 D ObexServerSockets0: shutdown(block = true)
,11-03 23:35:29.113  5746  5746 D ObexServerSockets0: shutdown called from another thread - interrupt().
,11-03 23:35:29.114  5746  5782 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
11-03 23:35:29.114  5746  5746 D ObexServerSockets0: shutdown called from another thread - interrupt().
11-03 23:35:29.114  5746  5771 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
11-03 23:35:29.114  5746  5783 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
11-03 23:35:29.116  5746  5746 I BtOppRfcommListener: stopping Accept Thread
11-03 23:35:29.117  5746  5793 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
11-03 23:35:29.120  5572  5572 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-03 23:35:29.120  5572  5572 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-03 23:35:29.120  5572  5572 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-03 23:35:29.120  5572  5572 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-03 23:35:29.120  5572  5572 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-03 23:35:29.120  5572  5572 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-03 23:35:29.120  5572  5572 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-03 23:35:29.120  5572  5572 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-03 23:35:29.120  5572  5572 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-03 23:35:29.122  5572  5572 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-03 23:35:29.122  5572  5572 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
11-03 23:35:29.123  5746  5793 I BtOppRfcommListener: BluetoothSocket listen thread finished
11-03 23:35:29.124  5746  5762 D BluetoothAdapterProperties: Scan Mode:20
11-03 23:35:29.124  5746  5758 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
,11-03 23:35:29.125  5638  5638 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
11-03 23:35:29.128  5572  5572 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-03 23:35:29.129  5746  5746 D HeadsetService: Received stop request...Stopping profile...
11-03 23:35:29.133   928   928 D BluetoothHeadset: Proxy object disconnected
11-03 23:35:29.134  3130  3141 D BluetoothHeadset: Proxy object disconnected
11-03 23:35:29.134   928   928 D BluetoothHeadset: Proxy object disconnected
11-03 23:35:29.134   928   928 D BluetoothHeadset: Proxy object disconnected
11-03 23:35:29.136  3785  3992 D BluetoothHeadset: Proxy object disconnected
11-03 23:35:29.136  5638  5650 D BluetoothHeadset: Proxy object disconnected
11-03 23:35:29.137  3130  3130 D HeadsetProfile: Bluetooth service disconnected
11-03 23:35:29.138  5746  5746 D A2dpService: Received stop request...Stopping profile...
11-03 23:35:29.139  5746  5777 D A2dpStateMachine: Exit Disconnected: -1
,11-03 23:35:29.140   928   928 D BluetoothA2dp: Proxy object disconnected
11-03 23:35:29.141  3130  3130 D BluetoothA2dp: Proxy object disconnected
,11-03 23:35:29.141  5746  5746 D HidService: Received stop request...Stopping profile...
,11-03 23:35:29.141  5746  5746 D HidService: Stopping Bluetooth HidService
11-03 23:35:29.142  5638  5638 D DockEventReceiver: finishStartingService: stopping service
11-03 23:35:29.143  3130  3130 D BluetoothInputDevice: Proxy object disconnected
11-03 23:35:29.143  3130  3130 D HidProfile: Bluetooth service disconnected
11-03 23:35:29.145  5638  5638 D HeadsetProfile: Bluetooth service disconnected
11-03 23:35:29.145  5746  5746 V BluetoothAdapterState: isTurningOff()=true
11-03 23:35:29.145  5746  5746 V BluetoothAdapterState: isTurningOn()=false
,11-03 23:35:29.145  5746  5746 V BluetoothAdapterState: isBleTurningOn()=false
11-03 23:35:29.145  5746  5746 V BluetoothAdapterState: isBleTurningOff()=false
11-03 23:35:29.146  5638  5638 D BluetoothA2dp: Proxy object disconnected
11-03 23:35:29.146  5638  5638 D BluetoothInputDevice: Proxy object disconnected
11-03 23:35:29.146  5638  5638 D HidProfile: Bluetooth service disconnected
11-03 23:35:29.147  5746  5746 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
11-03 23:35:29.147  5746  5746 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
11-03 23:35:29.147  5746  5769 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-03 23:35:29.147  5746  5769 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-03 23:35:29.147  5746  5769 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,11-03 23:35:29.147  5746  5746 D HealthService: Received stop request...Stopping profile...
,11-03 23:35:29.149  5746  5762 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
11-03 23:35:29.149  5746  5762 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
11-03 23:35:29.149  5746  5746 V BluetoothAdapterState: isTurningOff()=true
11-03 23:35:29.149  5746  5746 V BluetoothAdapterState: isTurningOn()=false
11-03 23:35:29.149  5746  5746 V BluetoothAdapterState: isBleTurningOn()=false
11-03 23:35:29.149  5746  5746 V BluetoothAdapterState: isBleTurningOff()=false
11-03 23:35:29.148  3596  3596 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
11-03 23:35:29.150  5746  5746 D PanService: Received stop request...Stopping profile...
11-03 23:35:29.153  5746  5746 V BluetoothAdapterState: isTurningOff()=true
11-03 23:35:29.153  5746  5746 V BluetoothAdapterState: isTurningOn()=false
11-03 23:35:29.153  5746  5746 V BluetoothAdapterState: isBleTurningOn()=false
11-03 23:35:29.153  5746  5746 V BluetoothAdapterState: isBleTurningOff()=false
11-03 23:35:29.154  5638  5638 D BluetoothPan: BluetoothPAN Proxy object disconnected
11-03 23:35:29.155  5638  5638 D PanProfile: Bluetooth service disconnected
11-03 23:35:29.155  5746  5746 D BluetoothMapService: Received stop request...Stopping profile...
11-03 23:35:29.155  5746  5746 D BluetoothMapService: stop()
11-03 23:35:29.156  3130  3130 D BluetoothPan: BluetoothPAN Proxy object disconnected
11-03 23:35:29.156  3130  3130 D PanProfile: Bluetooth service disconnected
11-03 23:35:29.156  5746  5746 D BluetoothMapAppObserver: deinitObservers()
11-03 23:35:29.156  5746  5746 D BluetoothMapAppObserver: removeReceiver()
,11-03 23:35:29.158  5638  5638 D BluetoothMap: Proxy object disconnected
11-03 23:35:29.158  5638  5638 D MapProfile: Bluetooth service disconnected
,11-03 23:35:29.159  5746  5746 D SapService: Received stop request...Stopping profile...
11-03 23:35:29.159  5746  5762 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
11-03 23:35:29.159  5746  5746 V SapService: stop()
11-03 23:35:29.159  5746  5769 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,11-03 23:35:29.159  5746  5769 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-03 23:35:29.159  5746  5769 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
11-03 23:35:29.159  3130  3130 D BluetoothMap: Proxy object disconnected
11-03 23:35:29.159  5746  5769 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
11-03 23:35:29.159  3130  3130 D MapProfile: Bluetooth service disconnected
11-03 23:35:29.159  5746  5769 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
11-03 23:35:29.160  5746  5769 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,11-03 23:35:29.165  5746  5746 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
,11-03 23:35:29.165  5746  5746 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
11-03 23:35:29.165  5746  5762 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,11-03 23:35:29.167  3130  3130 D BluetoothPbap: Proxy object disconnected
11-03 23:35:29.167  3130  3130 D PbapServerProfile: Bluetooth service disconnected
11-03 23:35:29.167  5746  5746 V BluetoothAdapterState: isTurningOff()=true
,11-03 23:35:29.167  5746  5746 V BluetoothAdapterState: isTurningOn()=false
11-03 23:35:29.167  5746  5746 V BluetoothAdapterState: isBleTurningOn()=false
11-03 23:35:29.167  5746  5746 V BluetoothAdapterState: isBleTurningOff()=false
11-03 23:35:29.167  5746  5746 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
11-03 23:35:29.168  5746  5762 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
11-03 23:35:29.168  5638  5638 D BluetoothPbap: Proxy object disconnected
11-03 23:35:29.168  5638  5638 D PbapServerProfile: Bluetooth service disconnected
11-03 23:35:29.168  5746  5746 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
,11-03 23:35:29.168  5746  5746 V BluetoothAdapterState: isTurningOff()=true
,11-03 23:35:29.168  5746  5746 V BluetoothAdapterState: isTurningOn()=false
11-03 23:35:29.168  5746  5746 V BluetoothAdapterState: isBleTurningOn()=false
11-03 23:35:29.168  5746  5746 V BluetoothAdapterState: isBleTurningOff()=false
11-03 23:35:29.169  5746  5746 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
11-03 23:35:29.169  5746  5746 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
11-03 23:35:29.170  5746  5746 D BluetoothMapService: MAP Service closeService in
11-03 23:35:29.170  5746  5746 V BluetoothAdapterState: isTurningOff()=true
11-03 23:35:29.170  5746  5746 V BluetoothAdapterState: isTurningOn()=false
11-03 23:35:29.170  5746  5746 V BluetoothAdapterState: isBleTurningOn()=false
,11-03 23:35:29.171  5746  5746 V BluetoothAdapterState: isBleTurningOff()=false
11-03 23:35:29.171  5746  5746 D BluetoothMapService: cleanup()
11-03 23:35:29.171  5746  5746 D BluetoothMapService: MAP Service closeService in
11-03 23:35:29.171  5746  5746 V BluetoothAdapterState: isTurningOff()=true
11-03 23:35:29.171  5746  5746 V BluetoothAdapterState: isTurningOn()=false
11-03 23:35:29.171  5746  5746 V BluetoothAdapterState: isBleTurningOn()=false
11-03 23:35:29.171  5746  5746 V BluetoothAdapterState: isBleTurningOff()=false
11-03 23:35:29.171  5746  5758 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
11-03 23:35:29.171  5746  5758 D BluetoothAdapterProperties: Setting state to 15
11-03 23:35:29.171  5746  5758 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
,11-03 23:35:29.172  5746  5758 I BluetoothAdapterState: Entering BleOnState
11-03 23:35:29.172   928   945 D BluetoothHeadset: onBluetoothStateChange: up=false
11-03 23:35:29.172   928   945 D BluetoothHeadset: onBluetoothStateChange: up=false
11-03 23:35:29.172  3130  3141 D BluetoothPan: onBluetoothStateChange on: false
11-03 23:35:29.173  3130  5423 D BluetoothPbap: onBluetoothStateChange: up=false
11-03 23:35:29.174  3130  3142 D BluetoothMap: onBluetoothStateChange: up=false
,11-03 23:35:29.175  5638  5650 D BluetoothPan: onBluetoothStateChange on: false
,11-03 23:35:29.184  5638  5654 D BluetoothInputDevice: onBluetoothStateChange: up=false
11-03 23:35:29.184  3130  3141 D BluetoothInputDevice: onBluetoothStateChange: up=false
,11-03 23:35:29.185  3130  5423 D BluetoothA2dp: onBluetoothStateChange: up=false
11-03 23:35:29.185  3785  3808 D BluetoothHeadset: onBluetoothStateChange: up=false
11-03 23:35:29.186   928   945 D BluetoothHeadset: onBluetoothStateChange: up=false
11-03 23:35:29.186  5638  5650 D BluetoothHeadset: onBluetoothStateChange: up=false
11-03 23:35:29.186  5638  5654 D BluetoothA2dp: onBluetoothStateChange: up=false
11-03 23:35:29.186  3130  3142 D BluetoothHeadset: onBluetoothStateChange: up=false
,11-03 23:35:29.187  5638  5650 D BluetoothMap: onBluetoothStateChange: up=false
11-03 23:35:29.187   928   945 D BluetoothA2dp: onBluetoothStateChange: up=false
,11-03 23:35:29.187  5638  5654 D BluetoothPbap: onBluetoothStateChange: up=false
11-03 23:35:29.188  5746  5758 D BluetoothAdapterState: Current state: BLE ON, message: 20
11-03 23:35:29.188  5746  5758 D BluetoothAdapterProperties: Setting state to 16
11-03 23:35:29.188  5746  5758 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
11-03 23:35:29.189  5746  5758 D BluetoothAdapterProperties: onBleDisable
11-03 23:35:29.189  5746  5758 I BluetoothAdapterState: Entering PendingCommandState
11-03 23:35:29.189  5746  5759 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
,11-03 23:35:29.190  5746  5769 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
11-03 23:35:29.190  5746  5769 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-03 23:35:29.192  5746  5762 D BluetoothAdapterProperties: Scan Mode:20
11-03 23:35:29.193  5572  5572 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-03 23:35:29.194  5638  5638 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,11-03 23:35:29.194  5572  5572 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-03 23:35:29.200  3596  3596 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,11-03 23:35:29.202  5638  5638 D DockEventReceiver: finishStartingService: stopping service
,11-03 23:35:29.407  5746  5762 I bt_hci  : shut_down
,11-03 23:35:29.417  5746  5766 D bt_hwcfg: hw_epilog_process
,11-03 23:35:29.418  5746  5766 I bt_vendor: low_power_mode_cb
,11-03 23:35:29.420  5746  5766 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,11-03 23:35:29.421  5746  5766 I bt_vendor: epilog_cb
11-03 23:35:29.421  5746  5766 I bt_hci  : epilog_finished_callback
,11-03 23:35:29.426  5746  5762 I bt_hci_h4: hal_close
,11-03 23:35:29.427  5746  5762 I bt_userial_vendor: device fd = 54 close
,11-03 23:35:29.545  5746  5759 D bt_stack_manager: event_shut_down_stack finished.
,11-03 23:35:29.545  5746  5758 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,11-03 23:35:29.549  5746  5758 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,11-03 23:35:29.549  5746  5746 D BtGatt.DebugUtils: handleDebugAction() action=null
,11-03 23:35:29.550  5746  5746 D BtGatt.GattService: Received stop request...Stopping profile...
,11-03 23:35:29.551  5746  5746 D BtGatt.GattService: stop()
11-03 23:35:29.551  5746  5746 D BtGatt.AdvertiseManager: advertise clients cleared
11-03 23:35:29.555  5746  5746 V BluetoothAdapterState: isTurningOff()=false
,11-03 23:35:29.555  5746  5746 V BluetoothAdapterState: isTurningOn()=false
,11-03 23:35:29.555  5746  5746 V BluetoothAdapterState: isBleTurningOn()=false
11-03 23:35:29.555  5746  5746 V BluetoothAdapterState: isBleTurningOff()=true
11-03 23:35:29.556  5746  5758 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
,11-03 23:35:29.556  5746  5758 D BluetoothAdapterProperties: Setting state to 10
11-03 23:35:29.557  5746  5758 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
11-03 23:35:29.558  5746  5758 I BluetoothAdapterState: Entering OffState
,11-03 23:35:29.559   928   945 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,11-03 23:35:29.573  5746  5746 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,11-03 23:35:29.573  5746  5746 W BluetoothSdpJni: Cleaning up Bluetooth Health object
11-03 23:35:29.573  5746  5746 I BluetoothServiceJni: cleanupNative: return from cleanup
11-03 23:35:29.575  5746  5759 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,11-03 23:35:29.582  5746  5746 I art     : System.exit called, status: 0
,11-03 23:35:29.582  5746  5746 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,11-03 23:35:29.611   928  3812 I ActivityManager: Process com.android.bluetooth (pid 5746) has died
,11-03 23:35:30.116   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-03 23:35:31.117   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-03 23:35:32.119   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-03 23:35:32.603  3596  3596 I ConfigService: onDestroy
,11-03 23:35:33.120   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-03 23:35:34.098  5572  5619 D io.jxcore.node.ConnectivityMonitor: stop
,11-03 23:35:34.099  5572  5619 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
,11-03 23:35:34.103  5572  5619 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-03 23:35:34.104  5572  5619 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@dc814b7 removed from the list
,11-03 23:35:34.104  5572  5619 D io.jxcore.node.ConnectivityMonitor: stop
,11-03 23:35:34.109  5572  5619 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,11-03 23:35:34.109  5572  5619 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@20c3142 added. We now have 4 listener(s)
11-03 23:35:34.110  5572  5619 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-03 23:35:34.112  5572  5619 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-03 23:35:34.113  5572  5619 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@20c3142 removed from the list
11-03 23:35:34.113  5572  5619 D io.jxcore.node.ConnectivityMonitor: stop
,11-03 23:35:34.115  5572  5619 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,11-03 23:35:34.116  5572  5619 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@13f4553 added. We now have 4 listener(s)
11-03 23:35:34.116  5572  5619 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-03 23:35:34.120   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-03 23:35:35.121   535   535 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,11-03 23:35:38.115   928   948 I PowerManagerService: Going to sleep due to screen timeout (uid 1000)...
,11-03 23:35:38.119  3434  3434 W Binder_5: type=1400 audit(0.0:118): avc: denied { ioctl } for path="socket:[31511]" dev="sockfs" ino=31511 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-03 23:35:38.123  3651  3651 I Keyboard.Facilitator: onFinishInput()
,11-03 23:35:38.123  3434  3434 W Binder_5: type=1400 audit(0.0:119): avc: denied { ioctl } for path="socket:[31511]" dev="sockfs" ino=31511 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-03 23:35:38.143   928   948 I Adreno  : QUALCOMM build                   : 63c06b2, I8366cd0437
11-03 23:35:38.143   928   948 I Adreno  : Build Date                       : 12/06/15
11-03 23:35:38.143   928   948 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
11-03 23:35:38.143   928   948 I Adreno  : Local Branch                     : mybranch17112971
11-03 23:35:38.143   928   948 I Adreno  : Remote Branch                    : quic/LA.BF64.1.2.9_v2
11-03 23:35:38.143   928   948 I Adreno  : Remote Branch                    : NONE
11-03 23:35:38.143   928   948 I Adreno  : Reconstruct Branch               : NOTHING
,11-03 23:35:38.184   383  3051 D PermissionCache: checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (182 us)
,11-03 23:35:38.885  5572  5572 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,11-03 23:35:38.885  5572  5572 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,11-03 23:35:38.915   928   948 I sensors : batch
,11-03 23:35:38.916   928   948 V KeyguardServiceDelegate: onScreenTurnedOff()
,11-03 23:35:38.918  5572  5572 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@62f3542 Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@41fe90, 16908290=android.view.AbsSavedState$1@41fe90}, android:focusedViewId=100}]}]
,11-03 23:35:38.919  5572  5572 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
11-03 23:35:38.919  5572  5572 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,11-03 23:35:38.919  5572  5572 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
11-03 23:35:38.920   928   948 E libEGL  : call to OpenGL ES API with no current context (logged once per thread)
,11-03 23:35:38.920   928   948 I sensors : activate
,11-03 23:35:38.921   383   383 D SurfaceFlinger: Set power mode=0, type=0 flinger=0x7f788c3c00
,11-03 23:35:38.921   383   383 D qdhwcomposer: hwc_setPowerMode: Setting mode 0 on display: 0
11-03 23:35:38.921   928   946 I DisplayManagerService: Display device changed state: "Built-in Screen", OFF
11-03 23:35:38.925   928  2672 I hubconnection: sensorhub said: 'batch 31 flags:0, sampling_rate_Hz:15.00, max_report_latency_us:0'
,11-03 23:35:38.927   928  2672 I hubconnection: sensorhub said: 'activate 7 enable:0'
,11-03 23:35:39.125  5572  5619 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-03 23:35:39.161   928   945 I ActivityManager: Start proc 5805:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,11-03 23:35:39.219   383   481 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0
,11-03 23:35:39.221   383   383 D qdhwcomposer: hwc_setPowerMode: Done setting mode 0 on display 0
11-03 23:35:39.222   928  3093 D SurfaceControl: Excessive delay in setPowerMode(): 300ms
,11-03 23:35:39.226   928   948 I DreamManagerService: Entering dreamland.
,11-03 23:35:39.227   928   948 I PowerManagerService: Dozing...
,11-03 23:35:39.234   928   943 I DreamController: Starting dream: name=ComponentInfo{com.android.systemui/com.android.systemui.doze.DozeService}, isTest=false, canDoze=true, userId=0
,11-03 23:35:39.253   939   939 W Binder_2: type=1400 audit(0.0:120): avc: denied { ioctl } for path="socket:[33984]" dev="sockfs" ino=33984 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-03 23:35:39.253   939   939 W Binder_2: type=1400 audit(0.0:121): avc: denied { ioctl } for path="socket:[33984]" dev="sockfs" ino=33984 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
11-03 23:35:39.257   928  3796 I sensors : batch
11-03 23:35:39.257   928  3796 I sensors : activate
,11-03 23:35:39.257  5805  5805 D AdapterServiceConfig: Adding HeadsetService
,11-03 23:35:39.258  5805  5805 D AdapterServiceConfig: Adding A2dpService
11-03 23:35:39.258  5805  5805 D AdapterServiceConfig: Adding HidService
11-03 23:35:39.258  5805  5805 D AdapterServiceConfig: Adding HealthService
11-03 23:35:39.258  5805  5805 D AdapterServiceConfig: Adding PanService
11-03 23:35:39.259  5805  5805 D AdapterServiceConfig: Adding GattService
,11-03 23:35:39.259  5805  5805 D AdapterServiceConfig: Adding BluetoothMapService
,11-03 23:35:39.259  5805  5805 D AdapterServiceConfig: Adding SapService
11-03 23:35:39.261   928  2672 I hubconnection: sensorhub said: 'batch 21 flags:0, sampling_rate_Hz:1000.00, max_report_latency_us:0'
11-03 23:35:39.261   928  2672 I hubconnection: sensorhub said: 'activate 21 enable:1'
,11-03 23:35:39.266   512  3008 D audio_hw_primary: adev_set_parameters: enter: screen_state=on
,11-03 23:35:39.271   928   945 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@f4fda0f:true
11-03 23:35:39.272  5805  5805 D BluetoothAdapterState: make() - Creating AdapterState
,11-03 23:35:39.274  5805  5805 I bt_bluedroid: init
,11-03 23:35:39.276  5805  5817 I BluetoothAdapterState: Entering OffState
,11-03 23:35:39.278  5805  5819 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,11-03 23:35:39.279  5805  5819 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
11-03 23:35:39.279  5805  5819 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
11-03 23:35:39.279  5805  5819 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,11-03 23:35:39.280  5805  5805 I bt_bluedroid: get_profile_interface socket
,11-03 23:35:39.282  5805  5805 I bt_bluedroid: get_profile_interface sdp
11-03 23:35:39.283  5805  5822 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:D4
,11-03 23:35:39.284  5805  5822 D BluetoothAdapterProperties: Name is: Nexus 6P
,11-03 23:35:39.290  3785  4764 D ScreenStateRecorder : ScreenStateRecorderHandler, handleMessage msg.what = 1
11-03 23:35:39.291  3785  4764 D         : oem_qmi_lib:come into oem_qmi_common_stream_from_modem_len --->modem 
,11-03 23:35:39.291  3785  4764 D         : oem_qmi_lib:oem_qmi_cmd: Send to server  passed!!
11-03 23:35:39.291   525  1191 D         : oem-qmi: Connection accepted
11-03 23:35:39.291   525  1191 D         : oem-qmi: Waiting to accept connection
,11-03 23:35:39.292  5805  5816 I bt_bluedroid: config_hci_snoop_log
,11-03 23:35:39.293   928   928 I sensors : activate
11-03 23:35:39.294   928   945 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
11-03 23:35:39.294   512  3007 D audio_hw_primary: adev_set_parameters: enter: screen_state=off
,11-03 23:35:39.297   928  2672 I hubconnection: sensorhub said: 'activate 31 enable:0'
,11-03 23:35:39.297  3785  4764 D         : oem_qmi_lib:output 0
11-03 23:35:39.297  3785  4764 D         : oem_qmi_lib:rapi_event_type=10057, qmi_ret=0, return_status=1. 
11-03 23:35:39.300  5805  5817 D BluetoothAdapterState: Current state: OFF, message: 0
11-03 23:35:39.300  5805  5817 D BluetoothAdapterProperties: Setting state to 14
11-03 23:35:39.300  5805  5817 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,11-03 23:35:39.302  5805  5817 D BluetoothBondStateMachine: make
,11-03 23:35:39.303  5805  5824 I BluetoothBondStateMachine: StableState(): Entering Off State
,11-03 23:35:39.306  5805  5817 I BluetoothAdapterState: Entering PendingCommandState
11-03 23:35:39.307  5805  5805 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,11-03 23:35:39.309  5805  5805 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@38588b7
11-03 23:35:39.309  5805  5805 D BtGatt.DebugUtils: handleDebugAction() action=null
11-03 23:35:39.310  5805  5805 D BtGatt.GattService: Received start request. Starting profile...
,11-03 23:35:39.310  5805  5805 D BtGatt.GattService: start()
11-03 23:35:39.310  5805  5805 I bt_bluedroid: get_profile_interface gatt
11-03 23:35:39.311  5805  5805 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@38588b7
11-03 23:35:39.311  5805  5805 D BtGatt.AdvertiseManager: advertise manager created
,11-03 23:35:39.316  5805  5805 V BluetoothAdapterState: isTurningOff()=false
11-03 23:35:39.316  5805  5805 V BluetoothAdapterState: isTurningOn()=false
11-03 23:35:39.316  5805  5805 V BluetoothAdapterState: isBleTurningOn()=true
11-03 23:35:39.316  5805  5805 V BluetoothAdapterState: isBleTurningOff()=false
,11-03 23:35:39.317  5805  5817 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
11-03 23:35:39.317  3785  4764 D ScreenStateRecorder : ScreenStateRecorderHandler, handleMessage msg.what = 2
,11-03 23:35:39.317  3785  4764 D         : oem_qmi_lib:come into oem_qmi_common_stream_from_modem_len --->modem 
11-03 23:35:39.318  3785  4764 D         : oem_qmi_lib:oem_qmi_cmd: Send to server  passed!!
11-03 23:35:39.318   525  1191 D         : oem-qmi: Connection accepted
11-03 23:35:39.318   525  1191 D         : oem-qmi: Waiting to accept connection
11-03 23:35:39.318  5805  5817 I bt_bluedroid: bt_bluedroid
,11-03 23:35:39.319  5805  5819 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,11-03 23:35:39.319  5805  5819 I bt_hci  : start_up
,11-03 23:35:39.323  3785  4764 D         : oem_qmi_lib:output 0
,11-03 23:35:39.323  3785  4764 D         : oem_qmi_lib:rapi_event_type=10057, qmi_ret=0, return_status=1. 
,11-03 23:35:39.324  5805  5819 I bt_vendor: alloc value 0xf3bbd871
11-03 23:35:39.324  5805  5819 I bt_vendor: init
11-03 23:35:39.324  5805  5819 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
11-03 23:35:39.324  5805  5819 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,11-03 23:35:39.432  5805  5819 D bt_hci  : start_up starting async portion
11-03 23:35:39.433  5805  5829 I bt_hci  : event_finish_startup
11-03 23:35:39.433  5805  5829 I bt_hci_h4: hal_open
11-03 23:35:39.433  5805  5829 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,11-03 23:35:39.429  5830  5830 W irq/448-msm_hs_: type=1400 audit(0.0:122): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
11-03 23:35:39.436  5805  5829 I bt_userial_vendor: device fd = 54 open
,11-03 23:35:39.450  5805  5829 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,11-03 23:35:39.453  5805  5829 D bt_hwcfg: Chipset BCM4358A3
,11-03 23:35:39.454  5805  5829 D bt_hwcfg: Target name = [BCM4358A3]
11-03 23:35:39.454  5805  5829 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,11-03 23:35:39.851  5805  5829 I bt_hwcfg: bt vendor lib: set UART baud 115200
,11-03 23:35:39.852  5805  5829 D bt_hwcfg: Settlement delay -- 100 ms
11-03 23:35:39.852  5805  5829 I bt_hwcfg: Setting fw settlement delay to 100 
,11-03 23:35:39.988  5805  5829 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,11-03 23:35:39.988  5805  5829 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:D4
,11-03 23:35:39.990  5805  5829 I bt_hwcfg: vendor lib fwcfg completed
,11-03 23:35:39.990  5805  5829 I bt_vendor: firmware callback
,11-03 23:35:39.990  5805  5829 I bt_hci  : firmware_config_callback
,11-03 23:35:39.999  5805  5832 I bt_btu  : btu_task pending for preload complete event
,11-03 23:35:39.999  5805  5832 I bt_btu_task: Bluetooth chip preload is complete
11-03 23:35:39.999  5805  5832 I bt_btu  : btu_task received preload complete event
,11-03 23:35:40.006  5805  5832 I         : BTE_InitTraceLevels -- TRC_HCI
,11-03 23:35:40.006  5805  5832 I         : BTE_InitTraceLevels -- TRC_L2CAP
11-03 23:35:40.006  5805  5832 I         : BTE_InitTraceLevels -- TRC_RFCOMM
11-03 23:35:40.006  5805  5832 I         : BTE_InitTraceLevels -- TRC_AVDT
11-03 23:35:40.006  5805  5832 I         : BTE_InitTraceLevels -- TRC_AVRC
11-03 23:35:40.006  5805  5832 I         : BTE_InitTraceLevels -- TRC_A2D
,11-03 23:35:40.007  5805  5832 I         : BTE_InitTraceLevels -- TRC_BNEP
11-03 23:35:40.007  5805  5832 I         : BTE_InitTraceLevels -- TRC_BTM
11-03 23:35:40.007  5805  5832 I         : BTE_InitTraceLevels -- TRC_GAP
11-03 23:35:40.007  5805  5832 I         : BTE_InitTraceLevels -- TRC_PAN
,11-03 23:35:40.007  5805  5832 I         : BTE_InitTraceLevels -- TRC_SDP
11-03 23:35:40.007  5805  5832 I         : BTE_InitTraceLevels -- TRC_GATT
11-03 23:35:40.007  5805  5832 I         : BTE_InitTraceLevels -- TRC_SMP
11-03 23:35:40.007  5805  5832 I         : BTE_InitTraceLevels -- TRC_BTAPP
,11-03 23:35:40.008  5805  5832 I         : BTE_InitTraceLevels -- TRC_BTIF
,11-03 23:35:40.092  5805  5832 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf3b3b549
,11-03 23:35:40.093  5805  5832 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf3b3b549 
,11-03 23:35:40.106  5805  5822 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,11-03 23:35:40.107  5805  5822 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,11-03 23:35:40.108  5805  5822 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:D4
,11-03 23:35:40.110  5805  5822 D BluetoothAdapterProperties: Name is: Nexus 6P
,11-03 23:35:40.113  5805  5822 D BluetoothAdapterProperties: Scan Mode:20
11-03 23:35:40.113  5805  5822 D BluetoothAdapterProperties: Discoverable Timeout:120
,11-03 23:35:40.114  5805  5822 D bt_hci  : do_postload posting postload work item
11-03 23:35:40.114  5805  5829 I bt_hci  : event_postload
,11-03 23:35:40.114  5805  5829 I bt_vendor: sco_config_cb
11-03 23:35:40.114  5805  5829 I bt_hci  : sco_config_callback postload finished.
,11-03 23:35:40.119  5805  5822 D bt_bte_conf: Device ID record 1 : primary
,11-03 23:35:40.120  5805  5822 D bt_bte_conf:   vendorId            = 000f
,11-03 23:35:40.120  5805  5822 D bt_bte_conf:   vendorIdSource      = 0001
,11-03 23:35:40.120  5805  5822 D bt_bte_conf:   product             = 1200
11-03 23:35:40.120  5805  5822 D bt_bte_conf:   version             = 1436
11-03 23:35:40.120  5805  5822 D bt_bte_conf:   clientExecutableURL = 
11-03 23:35:40.121  5805  5822 D bt_bte_conf:   serviceDescription  = 
11-03 23:35:40.121  5805  5822 D bt_bte_conf:   documentationURL    = 
11-03 23:35:40.121  5805  5822 D bt_bte_conf: bte_load_did_conf no section named DID2.
11-03 23:35:40.121  5805  5819 D bt_stack_manager: event_start_up_stack finished
11-03 23:35:40.122  5805  5817 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
,11-03 23:35:40.122  5805  5817 D BluetoothAdapterProperties: Setting state to 15
11-03 23:35:40.123  5805  5817 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
11-03 23:35:40.123  5805  5829 I bt_vendor: low_power_mode_cb
11-03 23:35:40.124  5805  5817 I BluetoothAdapterState: Entering BleOnState
,11-03 23:35:40.133  5805  5817 D BluetoothAdapterState: Current state: BLE ON, message: 1
11-03 23:35:40.134  5805  5817 D BluetoothAdapterProperties: Setting state to 11
11-03 23:35:40.134  5805  5817 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,11-03 23:35:40.139  5805  5805 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@38588b7
,11-03 23:35:40.140  5805  5805 D HeadsetService: Received start request. Starting profile...
11-03 23:35:40.144  5805  5805 I BluetoothHeadsetServiceJni: classInitNative: succeeds
11-03 23:35:40.144  5805  5805 D HeadsetStateMachine: make
11-03 23:35:40.155  5805  5817 I BluetoothAdapterState: Entering PendingCommandState
,11-03 23:35:40.162  5805  5805 D HeadsetStateMachine: max_hf_connections = 1
,11-03 23:35:40.162  5805  5805 I bt_bluedroid: get_profile_interface handsfree
11-03 23:35:40.162  5805  5822 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
11-03 23:35:40.163  5805  5822 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
,11-03 23:35:40.169  5805  5805 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@38588b7
,11-03 23:35:40.170  5805  5805 D A2dpService: Received start request. Starting profile...
11-03 23:35:40.171  5805  5805 I BluetoothAvrcpServiceJni: classInitNative: succeeds
11-03 23:35:40.171  5805  5805 I bt_bluedroid: get_profile_interface avrcp
,11-03 23:35:40.177  5805  5805 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
11-03 23:35:40.177  5805  5805 I BluetoothA2dpServiceJni: classInitNative: succeeds
,11-03 23:35:40.177  5805  5805 D A2dpStateMachine: make
11-03 23:35:40.178  5805  5805 I bt_bluedroid: get_profile_interface a2dp
,11-03 23:35:40.179  5805  5822 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,11-03 23:35:40.180  5805  5840 D A2dpStateMachine: Enter Disconnected: -2
11-03 23:35:40.181  5805  5805 I BluetoothHidServiceJni: classInitNative: succeeds
11-03 23:35:40.182  5805  5805 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@38588b7
,11-03 23:35:40.183  5805  5805 D HidService: Received start request. Starting profile...
11-03 23:35:40.183  5805  5805 I bt_bluedroid: get_profile_interface hidhost
11-03 23:35:40.183  5805  5805 D HidService: setHidService(): set to: null
11-03 23:35:40.183  5805  5822 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf3b1c56d
11-03 23:35:40.183  5805  5822 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
11-03 23:35:40.185  5805  5805 I BluetoothHealthServiceJni: classInitNative: succeeds
,11-03 23:35:40.185  5805  5805 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@38588b7
11-03 23:35:40.186  5805  5805 D HealthService: Received start request. Starting profile...
11-03 23:35:40.186  3596  3596 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,11-03 23:35:40.188  5805  5805 I bt_bluedroid: get_profile_interface health
11-03 23:35:40.188  5805  5805 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,11-03 23:35:40.189  5805  5805 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@38588b7
,11-03 23:35:40.190  5805  5805 D PanService: Received start request. Starting profile...
,11-03 23:35:40.190  5805  5805 D BluetoothPanServiceJni: initializeNative(L110): pan
11-03 23:35:40.190  5805  5805 I bt_bluedroid: get_profile_interface pan
11-03 23:35:40.191  5805  5822 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,11-03 23:35:40.193  5805  5805 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@38588b7
,11-03 23:35:40.193  5805  5805 D BluetoothMapService: Received start request. Starting profile...
11-03 23:35:40.193  5805  5805 D BluetoothMapService: start()
,11-03 23:35:40.196  5805  5805 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,11-03 23:35:40.197  5805  5805 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
11-03 23:35:40.197  5805  5805 D BluetoothMapAppObserver: createReceiver()
,11-03 23:35:40.198  5805  5805 D BluetoothMapAppObserver: initObservers()
,11-03 23:35:40.198  5805  5805 D BluetoothMapAppObserver: getEnabledAccountItems()
,11-03 23:35:40.205  5805  5805 V SapService: SapBinder()
,11-03 23:35:40.205  5805  5805 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@38588b7
11-03 23:35:40.206  5805  5805 D SapService: Received start request. Starting profile...
11-03 23:35:40.206  5805  5805 V SapService: start()
,11-03 23:35:40.209  5805  5805 V BluetoothAdapterState: isTurningOff()=false
11-03 23:35:40.209  5805  5805 V BluetoothAdapterState: isTurningOn()=true
11-03 23:35:40.209  5805  5805 V BluetoothAdapterState: isBleTurningOn()=false
11-03 23:35:40.209  5805  5838 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,11-03 23:35:40.209  5805  5805 V BluetoothAdapterState: isBleTurningOff()=false
11-03 23:35:40.209  5805  5805 V BluetoothAdapterState: isTurningOff()=false
11-03 23:35:40.209  5805  5805 V BluetoothAdapterState: isTurningOn()=true
11-03 23:35:40.209  5805  5805 V BluetoothAdapterState: isBleTurningOn()=false
11-03 23:35:40.209  5805  5805 V BluetoothAdapterState: isBleTurningOff()=false
11-03 23:35:40.209  5805  5805 V BluetoothAdapterState: isTurningOff()=false
11-03 23:35:40.209  5805  5805 V BluetoothAdapterState: isTurningOn()=true
11-03 23:35:40.209  5805  5805 V BluetoothAdapterState: isBleTurningOn()=false
11-03 23:35:40.209  5805  5805 V BluetoothAdapterState: isBleTurningOff()=false
11-03 23:35:40.210  5805  5805 V BluetoothAdapterState: isTurningOff()=false
11-03 23:35:40.210  5805  5805 V BluetoothAdapterState: isTurningOn()=true
11-03 23:35:40.210  5805  5805 V BluetoothAdapterState: isBleTurningOn()=false
11-03 23:35:40.210  5805  5805 V BluetoothAdapterState: isBleTurningOff()=false
11-03 23:35:40.210  5805  5805 V BluetoothAdapterState: isTurningOff()=false
,11-03 23:35:40.210  5805  5805 V BluetoothAdapterState: isTurningOn()=true
11-03 23:35:40.210  5805  5805 V BluetoothAdapterState: isBleTurningOn()=false
11-03 23:35:40.210  5805  5805 V BluetoothAdapterState: isBleTurningOff()=false
11-03 23:35:40.210  5805  5805 V BluetoothAdapterState: isTurningOff()=false
11-03 23:35:40.210  5805  5805 V BluetoothAdapterState: isTurningOn()=true
11-03 23:35:40.211  5805  5805 V BluetoothAdapterState: isBleTurningOn()=false
11-03 23:35:40.211  5805  5805 V BluetoothAdapterState: isBleTurningOff()=false
11-03 23:35:40.212  5805  5805 V BluetoothAdapterState: isTurningOff()=false
11-03 23:35:40.212  5805  5805 V BluetoothAdapterState: isTurningOn()=true
,11-03 23:35:40.212  5805  5805 V BluetoothAdapterState: isBleTurningOn()=false
11-03 23:35:40.212  5805  5805 V BluetoothAdapterState: isBleTurningOff()=false
11-03 23:35:40.212  5805  5817 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
11-03 23:35:40.212  5805  5817 D BluetoothAdapterProperties: ScanMode =  20
11-03 23:35:40.212  5805  5817 D BluetoothAdapterProperties: State =  11
11-03 23:35:40.214  5805  5822 D BluetoothAdapterProperties: Scan Mode:21
11-03 23:35:40.214  5805  5817 D BluetoothAdapterProperties: Setting state to 12
,11-03 23:35:40.214  5805  5817 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
11-03 23:35:40.215   928   945 D BluetoothHeadset: onBluetoothStateChange: up=true
11-03 23:35:40.215   928   945 D BluetoothHeadset: onBluetoothStateChange: up=true
,11-03 23:35:40.215  5805  5822 D BluetoothAdapterProperties: Discoverable Timeout:120
11-03 23:35:40.215  3130  3142 D BluetoothPan: onBluetoothStateChange on: true
11-03 23:35:40.215  5805  5817 I BluetoothAdapterState: Entering OnState
11-03 23:35:40.217  3130  5423 D BluetoothPbap: onBluetoothStateChange: up=true
11-03 23:35:40.218  3130  3130 D BluetoothPan: BluetoothPAN Proxy object connected
11-03 23:35:40.218  3130  3130 D PanProfile: Bluetooth service connected
11-03 23:35:40.219  3130  3142 D BluetoothMap: onBluetoothStateChange: up=true
11-03 23:35:40.220  5638  5654 D BluetoothPan: onBluetoothStateChange on: true
,11-03 23:35:40.221  3130  3130 D BluetoothMap: Proxy object connected
,11-03 23:35:40.221  3130  3130 D MapProfile: Bluetooth service connected
11-03 23:35:40.221  3130  3130 D BluetoothMap: getConnectedDevices()
11-03 23:35:40.223  5638  5650 D BluetoothInputDevice: onBluetoothStateChange: up=true
,11-03 23:35:40.224  5805  5805 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,11-03 23:35:40.224  3130  5423 D BluetoothInputDevice: onBluetoothStateChange: up=true
11-03 23:35:40.225  5805  5805 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
,11-03 23:35:40.226  3130  3142 D BluetoothA2dp: onBluetoothStateChange: up=true
,11-03 23:35:40.227  5805  5805 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-03 23:35:40.228  3785  3804 D BluetoothHeadset: onBluetoothStateChange: up=true
11-03 23:35:40.228  5805  5805 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-03 23:35:40.228   928   945 D BluetoothHeadset: onBluetoothStateChange: up=true
11-03 23:35:40.229  5638  5654 D BluetoothHeadset: onBluetoothStateChange: up=true
11-03 23:35:40.229  5638  5650 D BluetoothA2dp: onBluetoothStateChange: up=true
11-03 23:35:40.229  5805  5805 D ObexServerSockets: Succeed to create listening sockets 
11-03 23:35:40.229  5805  5805 D ObexServerSockets0: startAccept()
11-03 23:35:40.230  5805  5805 D ObexServerSockets0: prepareForNewConnect()
11-03 23:35:40.231  3130  3141 D BluetoothHeadset: onBluetoothStateChange: up=true
11-03 23:35:40.231  5638  5638 D BluetoothPan: BluetoothPAN Proxy object connected
11-03 23:35:40.231  5638  5638 D PanProfile: Bluetooth service connected
11-03 23:35:40.231  5638  5654 D BluetoothMap: onBluetoothStateChange: up=true
11-03 23:35:40.232  5805  5805 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
11-03 23:35:40.232  5805  5805 D BluetoothSdpJni: SDP Create record success - handle: 0
11-03 23:35:40.233  5805  5846 D ObexServerSockets0: Accepting socket connection...
,11-03 23:35:40.233   928   945 D BluetoothA2dp: onBluetoothStateChange: up=true
11-03 23:35:40.234  5805  5847 D ObexServerSockets0: Accepting socket connection...
11-03 23:35:40.234  3130  3130 D BluetoothInputDevice: Proxy object connected
11-03 23:35:40.234  3130  3130 D HidProfile: Bluetooth service connected
11-03 23:35:40.234  5638  5654 D BluetoothPbap: onBluetoothStateChange: up=true
,11-03 23:35:40.235   928   928 D BluetoothA2dp: Proxy object connected
,11-03 23:35:40.238  5638  5638 D BluetoothMap: Proxy object connected
,11-03 23:35:40.239  5638  5638 D MapProfile: Bluetooth service connected
11-03 23:35:40.239  5638  5638 D BluetoothMap: getConnectedDevices()
11-03 23:35:40.239  5805  5805 D BluetoothMapService: onReceive
11-03 23:35:40.239  5805  5805 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
11-03 23:35:40.239  5805  5805 D BluetoothMapService: STATE_ON
,11-03 23:35:40.241   928   928 I Telecom : BluetoothPhoneService: queryPhoneState
,11-03 23:35:40.241  3130  3130 D BluetoothA2dp: Proxy object connected
,11-03 23:35:40.242  5638  5638 D BluetoothInputDevice: Proxy object connected
,11-03 23:35:40.243  5638  5638 D HidProfile: Bluetooth service connected
11-03 23:35:40.244  5638  5638 D BluetoothA2dp: Proxy object connected
11-03 23:35:40.244  5805  5850 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-03 23:35:40.245  5805  5850 D BluetoothSdpJni: sdpCreateSapsRecordNative:
11-03 23:35:40.245  5805  5850 D BluetoothSdpJni: SDP Create record success - handle: 1
,11-03 23:35:40.249  5638  5638 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,11-03 23:35:40.254  3596  3596 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
11-03 23:35:40.255  5638  5638 D DockEventReceiver: finishStartingService: stopping service
,11-03 23:35:40.261  5638  5638 D BluetoothPbap: Proxy object connected
11-03 23:35:40.261  5638  5638 D PbapServerProfile: Bluetooth service connected
,11-03 23:35:40.266  5805  5805 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,11-03 23:35:40.266  5805  5805 D ObexServerSockets0: prepareForNewConnect()
,11-03 23:35:40.270  3130  3130 D BluetoothPbap: Proxy object connected
,11-03 23:35:40.270  3130  3130 D PbapServerProfile: Bluetooth service connected
11-03 23:35:40.270  5805  5854 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-03 23:35:40.282  5805  5858 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-03 23:35:40.283  5805  5858 I BtOppRfcommListener: Accept thread started.
,11-03 23:35:40.317   928   928 D BluetoothHeadset: Proxy object connected
,11-03 23:35:40.318  3130  3141 D BluetoothHeadset: Proxy object connected
11-03 23:35:40.318   928   928 D BluetoothHeadset: Proxy object connected
11-03 23:35:40.318  3130  3130 D HeadsetProfile: Bluetooth service connected
11-03 23:35:40.318   928   928 D BluetoothHeadset: Proxy object connected
11-03 23:35:40.319  3785  3992 D BluetoothHeadset: Proxy object connected
,11-03 23:35:40.322  5638  5845 D BluetoothHeadset: Proxy object connected
11-03 23:35:40.324  5638  5638 D HeadsetProfile: Bluetooth service connected
,11-03 23:35:40.329  3785  3808 D BluetoothHeadset: Proxy object connected
11-03 23:35:40.329   928   945 D BluetoothHeadset: Proxy object connected
,11-03 23:35:40.329  5638  5654 D BluetoothHeadset: Proxy object connected
,11-03 23:35:40.329  5638  5638 D HeadsetProfile: Bluetooth service connected
,11-03 23:35:40.332  3130  5423 D BluetoothHeadset: Proxy object connected
11-03 23:35:40.332  3130  3130 D HeadsetProfile: Bluetooth service connected
,11-03 23:35:42.899  3843  4447 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,11-03 23:35:44.142  5572  5619 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-03 23:35:44.142  5572  5619 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-03 23:35:44.142  5572  5619 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-03 23:35:44.142  5572  5619 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-03 23:35:44.142  5572  5619 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-03 23:35:44.142  5572  5619 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-03 23:35:44.142  5572  5619 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-03 23:35:44.142  5572  5619 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,11-03 23:35:44.148  5572  5619 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,11-03 23:35:44.149  5572  5619 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-03 23:35:44.149  5572  5619 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@13f4553 removed from the list
,11-03 23:35:44.149  5572  5619 D io.jxcore.node.ConnectivityMonitor: stop
11-03 23:35:44.151  5572  5619 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-03 23:35:44.151  5572  5619 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@b097389 added. We now have 4 listener(s)
11-03 23:35:44.151  5572  5619 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-03 23:35:44.155   928  3796 D WifiService: setWifiEnabled: false pid=5572, uid=10077
11-03 23:35:44.155   928  3796 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-03 23:35:49.165  5572  5619 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-03 23:35:49.166   928  3166 D WifiService: setWifiEnabled: true pid=5572, uid=10077
11-03 23:35:49.166   928  3166 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-03 23:35:49.174   507   921 D SoftapController: Softap fwReload - Ok
,11-03 23:35:49.180   507   921 D CommandListener: Setting iface cfg
,11-03 23:35:49.180   507   921 D CommandListener: Trying to bring down wlan0
,11-03 23:35:49.182   507   921 D CommandListener: Clearing all IP addresses on wlan0
,11-03 23:35:49.188   928  2958 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,11-03 23:35:49.849   928  2958 D wifi    : set interface wlan0 flags (UP)
,11-03 23:35:49.850   928  2958 I WifiHAL : Initializing wifi
11-03 23:35:49.851   928  2958 I WifiHAL : Creating socket
,11-03 23:35:49.856   928   945 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,11-03 23:35:49.858   928  2958 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
,11-03 23:35:49.858   928  2958 D wifi    : Did set static halHandle = 0x7f6f86f680
11-03 23:35:49.859   928  2958 D wifi    : halHandle = 0x7f6f86f680, mVM = 0x7f8be8d140, mCls = 0x1014fe
11-03 23:35:49.859   928  2958 D wifi    : array field set
,11-03 23:35:49.859   928  2958 I WifiNative-HAL: interface[0] = wlan0
11-03 23:35:49.862   928  5863 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=547331962496
11-03 23:35:49.863   928  5863 D wifi    : waitForHalEvents called, vm = 0x7f8be8d140, obj = 0x1014fe, env = 0x7f74753080
,11-03 23:35:49.932  5864  5864 I wpa_supplicant: Successfully initialized wpa_supplicant
,11-03 23:35:49.963   928  2958 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,11-03 23:35:50.006  5864  5864 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,11-03 23:35:50.072  5864  5864 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,11-03 23:35:50.072  5864  5864 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,11-03 23:35:50.096   928  2958 D WifiConfigStore: Loading config and enabling all networks 
,11-03 23:35:50.121   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-03 23:35:50.130   928  2958 D WifiConfigStore: loaded 0 passpoint configs
,11-03 23:35:50.131   928  2958 W WifiConfigStore: Upgrading network 4 to android.uid.system:1000
,11-03 23:35:50.132   928  2958 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,11-03 23:35:50.132   928  2958 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,11-03 23:35:50.133   928  2958 W WifiConfigStore: Upgrading network 3 to android.uid.system:1000
11-03 23:35:50.133   928  2958 W WifiConfigStore: Upgrading network 2 to android.uid.system:1000
,11-03 23:35:50.134   928  2958 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
11-03 23:35:50.134   928  2958 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 5
11-03 23:35:50.134   928  2958 E WifiConfigStore: found sortedWifiConfigurations : "AndroidAP"WPA_PSK
,11-03 23:35:50.134   928  2958 E WifiConfigStore: found sortedWifiConfigurations : "AndroidHotspot2346"WPA_PSK
11-03 23:35:50.134   928  2958 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,11-03 23:35:50.134   928  2958 E WifiConfigStore: found sortedWifiConfigurations : "Thali_internal"WPA_PSK
11-03 23:35:50.134   928  2958 E WifiConfigStore: found sortedWifiConfigurations : "MC"WPA_PSK
,11-03 23:35:50.137   928  2958 D WifiNative-HAL: Setting external_sim to 1
11-03 23:35:50.137   928  2958 D wifi    : setting dfs flag to true, 0x7f73598120
11-03 23:35:50.137   928  2958 D WifiStateMachine: Setting OUI to DA-A1-19
,11-03 23:35:50.137  4521  4521 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
11-03 23:35:50.137   928  2958 D wifi    : setting scan oui 0x7f73598120
11-03 23:35:50.137   928  2958 D WifiHAL : Sending mac address OUI
,11-03 23:35:50.141   928  2958 E native  : do suspend true
,11-03 23:35:50.149   928  2958 D wifi    : android_net_wifi_setLinkLayerStats: 1
11-03 23:35:50.150   507   921 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,11-03 23:35:50.150   928   928 D RttService: SCAN_AVAILABLE : 3
11-03 23:35:50.150   928  3069 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,11-03 23:35:50.151   507   921 D CommandListener: Setting iface cfg
,11-03 23:35:50.160   928  2957 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '152 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 152 Failed to set address (No such device)'
11-03 23:35:50.160   928  2957 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,11-03 23:35:50.168   928  2957 D WifiNative-HAL: p2pGetDeviceAddress
,11-03 23:35:50.174   928  2957 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:70
,11-03 23:35:50.174   928   943 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=163608 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=8 mControllerEnergyUsed=30 }
,11-03 23:35:51.123   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-03 23:35:52.125   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-03 23:35:53.126   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-03 23:35:53.311  5864  5864 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,11-03 23:35:53.344   928  2958 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,11-03 23:35:53.352   928  2958 D WifiStateMachine: CMD_AUTO_CONNECT sup state DisconnectedState my state DisconnectedState nid=0 roam=3
11-03 23:35:53.353   928  2958 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-03 23:35:53.370   928  2958 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=0
,11-03 23:35:53.419   928  2958 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=0
,11-03 23:35:53.752  5864  5864 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,11-03 23:35:53.785  5864  5864 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,11-03 23:35:53.786  5864  5864 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,11-03 23:35:53.797   928  2958 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,11-03 23:35:53.797   928  2958 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-03 23:35:53.797   928  2960 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,11-03 23:35:53.814   928  2958 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-03 23:35:53.827   507   921 D CommandListener: Setting iface cfg
,11-03 23:35:53.833   928  2958 D WifiStateMachine: Start Dhcp Watchdog 3
,11-03 23:35:53.837   928  2958 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,11-03 23:35:53.844   928  5869 D DhcpClient: Receive thread started
,11-03 23:35:53.926   928  2958 E native  : do suspend false
,11-03 23:35:53.939   928  5868 D DhcpClient: Broadcasting DHCPDISCOVER
,11-03 23:35:53.967   928  5869 D DhcpClient: Received packet: 60:83:34:25:d7:70 OFFER, ip /192.168.1.105, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172764, domain null
,11-03 23:35:53.968   928  5868 D DhcpClient: Got pending lease: IP address 192.168.1.105/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172764 seconds
,11-03 23:35:53.971   928  5868 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.105 serverid=192.168.1.1
,11-03 23:35:53.987   928  5869 D DhcpClient: Received packet: 60:83:34:25:d7:70 ACK: your new IP /192.168.1.105, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,11-03 23:35:53.987   928  5868 D DhcpClient: Confirmed lease: IP address 192.168.1.105/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,11-03 23:35:53.991   507   921 D CommandListener: Setting iface cfg
,11-03 23:35:53.996   928  2958 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,11-03 23:35:54.000   928  5868 D DhcpClient: Scheduling renewal in 86399s
11-03 23:35:54.000   928  2958 E native  : do suspend true
,11-03 23:35:54.020   928  2958 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,11-03 23:35:54.023   928  2958 D WifiConfigStore: No blacklist allowed without epno enabled
,11-03 23:35:54.026   928  2960 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,11-03 23:35:54.030   928  2960 D ConnectivityService: Adding iface wlan0 to network 102
,11-03 23:35:54.037   928  2958 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,11-03 23:35:54.089   928  2960 E ConnectivityService: Unexpected mtu value: 0, wlan0
11-03 23:35:54.089   928  2960 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
,11-03 23:35:54.091   928  2960 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
11-03 23:35:54.093   928  2960 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
,11-03 23:35:54.094   928  2960 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
,11-03 23:35:54.102   928  2960 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-03 23:35:54.107   928  2960 D ConnectivityService: scheduleUnvalidatedPrompt 102
,11-03 23:35:54.108   928  2960 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 102]
,11-03 23:35:54.109   928  2958 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
,11-03 23:35:54.109   928  2958 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
11-03 23:35:54.109   928  2960 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 102]
11-03 23:35:54.109   928  2960 D ConnectivityService:    accepting network in place of null
,11-03 23:35:54.110   928  2960 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d770/64,192.168.1.105/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,11-03 23:35:54.123   928  5867 D NetlinkSocketObserver: NeighborEvent{elapsedMs=167557, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,11-03 23:35:54.127   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-03 23:35:54.139   507   921 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-03 23:35:54.164   507   921 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-03 23:35:54.168   928  2960 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
,11-03 23:35:54.168   928  2960 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,11-03 23:35:54.168  3742  3856 W QCNEJ   : |CORE| network available: 102
11-03 23:35:54.169   928  2960 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
11-03 23:35:54.171  3742  3856 W QCNEJ   : |CORE| onAvailable: bind the process to WIFI
11-03 23:35:54.172   928   945 D Tethering: MasterInitialState.processMessage what=3
11-03 23:35:54.172  3742  3856 W QCNEJ   : |CORE| newLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d770/64,192.168.1.105/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}
11-03 23:35:54.172  3742  3856 W QCNEJ   : |CORE| curLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d770/64,192.168.1.105/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,11-03 23:35:54.183  5572  5619 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-03 23:35:54.183  5572  5619 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-03 23:35:54.183  5572  5619 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-03 23:35:54.183  5572  5619 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-03 23:35:54.183  5572  5619 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-03 23:35:54.183  5572  5619 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-03 23:35:54.183  5572  5619 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-03 23:35:54.183  5572  5619 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
11-03 23:35:54.185  5572  5619 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
11-03 23:35:54.185  5572  5619 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-03 23:35:54.185  5572  5619 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@b097389 removed from the list
11-03 23:35:54.185  5572  5619 D io.jxcore.node.ConnectivityMonitor: stop
,11-03 23:35:54.186  3947  3947 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
,11-03 23:35:54.188  4006  4006 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
11-03 23:35:54.189  5572  5619 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
11-03 23:35:54.189  5572  5619 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
11-03 23:35:54.191  5572  5619 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@62f3542 Bundle[{}]
11-03 23:35:54.191  5572  5619 I io.jxcore.node.LifeCycleMonitor: start: OK
11-03 23:35:54.192  5572  5619 I io.jxcore.node.LifeCycleMonitor: stop: OK
11-03 23:35:54.192  4006  4006 D SystemUpdateService: onCreate
11-03 23:35:54.192  5572  5619 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
11-03 23:35:54.193  5572  5619 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,11-03 23:35:54.193  5572  5619 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
11-03 23:35:54.193  5572  5619 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
11-03 23:35:54.195  4006  4006 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,11-03 23:35:54.201  5572  5619 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 168)
,11-03 23:35:54.201  5572  5619 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
11-03 23:35:54.201  5572  5619 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 169)
,11-03 23:35:54.205   928  5866 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.214.238,2a00:1450:400d:803::200e
,11-03 23:35:54.205  5572  5619 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-03 23:35:54.206  5572  5619 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9301f8e added. We now have 3 listener(s)
11-03 23:35:54.206  4006  4006 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
11-03 23:35:54.207  5572  5619 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-03 23:35:54.207  5572  5619 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,11-03 23:35:54.207  5572  5619 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-03 23:35:54.208  5572  5619 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-03 23:35:54.208  5572  5619 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8eee3af added. We now have 4 listener(s)
11-03 23:35:54.208  5572  5619 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-03 23:35:54.208  5572  5619 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,11-03 23:35:54.210  5572  5619 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,11-03 23:35:54.210  5572  5619 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f7073bc added. We now have 4 listener(s)
,11-03 23:35:54.211  4006  5878 I SystemUpdateService: active receiver: enabled
,11-03 23:35:54.211  5572  5619 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-03 23:35:54.211  5572  5619 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-03 23:35:54.211  5572  5619 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-03 23:35:54.212  5572  5619 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-03 23:35:54.212  5572  5619 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@58cbf45 added. We now have 5 listener(s)
11-03 23:35:54.212  5572  5619 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-03 23:35:54.212  5572  5619 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-03 23:35:54.212  5572  5619 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-03 23:35:54.212  5572  5619 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,11-03 23:35:54.212  5572  5619 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-03 23:35:54.212  4006  4256 I iu.UploadsManager: num queued entries: 0
11-03 23:35:54.212  5572  5619 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-03 23:35:54.212  5572  5619 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-03 23:35:54.213  5572  5619 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9301f8e removed from the list
11-03 23:35:54.213  5572  5619 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-03 23:35:54.213  4006  4256 I iu.UploadsManager: num updated entries: 0
11-03 23:35:54.213  5572  5619 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8eee3af removed from the list
11-03 23:35:54.213  5572  5619 D io.jxcore.node.ConnectivityMonitor: stop
,11-03 23:35:54.213  5572  5619 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-03 23:35:54.213  4006  4256 I iu.SyncManager: NEXT; no task
,11-03 23:35:54.214  5572  5619 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
,11-03 23:35:54.214  5572  5619 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-03 23:35:54.215  5572  5619 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-03 23:35:54.215  5572  5619 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-03 23:35:54.215  5572  5619 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-03 23:35:54.215  5572  5619 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-03 23:35:54.215  5572  5619 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8eee3af not in the list
11-03 23:35:54.215  5572  5619 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-03 23:35:54.216  5572  5619 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
,11-03 23:35:54.216  5572  5619 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-03 23:35:54.216  5572  5619 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-03 23:35:54.216  5572  5619 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-03 23:35:54.217  5572  5619 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-03 23:35:54.217  5572  5619 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-03 23:35:54.217  5572  5619 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@58cbf45 removed from the list
11-03 23:35:54.217  5572  5619 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-03 23:35:54.217  5572  5619 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-03 23:35:54.217  5572  5619 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,11-03 23:35:54.217  5572  5619 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f7073bc removed from the list
11-03 23:35:54.217  4006  4006 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
11-03 23:35:54.218  5572  5619 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-03 23:35:54.218  5572  5619 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@392a69a added. We now have 3 listener(s)
,11-03 23:35:54.219  4006  4006 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,11-03 23:35:54.219  5572  5619 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-03 23:35:54.219  5572  5619 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-03 23:35:54.220  5572  5619 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-03 23:35:54.220  5572  5619 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-03 23:35:54.220  5572  5619 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9500bcb added. We now have 4 listener(s)
11-03 23:35:54.220  5572  5619 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-03 23:35:54.220  5572  5619 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
11-03 23:35:54.220  5676  5676 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
11-03 23:35:54.221  5572  5619 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-03 23:35:54.221  5572  5619 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4af0fa8 added. We now have 4 listener(s)
,11-03 23:35:54.222  5572  5619 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
,11-03 23:35:54.222  5572  5619 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-03 23:35:54.223  5572  5619 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-03 23:35:54.223  5572  5619 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-03 23:35:54.223  5572  5619 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@93f0ac1 added. We now have 5 listener(s)
11-03 23:35:54.223  5572  5619 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-03 23:35:54.223  5572  5619 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,11-03 23:35:54.223  5572  5619 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
11-03 23:35:54.223  5572  5619 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
11-03 23:35:54.223  5572  5619 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-03 23:35:54.223  5572  5619 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
11-03 23:35:54.224  5572  5619 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,11-03 23:35:54.226  5676  5676 D SprintDMHelper: simOperator: 
11-03 23:35:54.226  5676  5676 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,11-03 23:35:54.227  5572  5619 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-03 23:35:54.227  5572  5619 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-03 23:35:54.227  5572  5619 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
11-03 23:35:54.230  5572  5619 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-61,5,main], id: 61
,11-03 23:35:54.230  5572  5619 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-03 23:35:54.231  5572  5619 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-03 23:35:54.231  5572  5619 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-03 23:35:54.231  5572  5619 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 0
,11-03 23:35:54.234  5572  5619 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-61,5,main], id: 61
,11-03 23:35:54.234  5572  5619 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
11-03 23:35:54.234  5572  5619 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
11-03 23:35:54.234  5572  5619 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
11-03 23:35:54.234  5572  5619 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
11-03 23:35:54.234  5572  5619 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-61,5,main], id: 61
11-03 23:35:54.235  5572  5619 D BluetoothAdapter: STATE_ON
,11-03 23:35:54.238  5805  5848 D BtGatt.GattService: registerClient() - UUID=d7cf1bb1-6fa1-4ed8-80fa-bf3fed8754dd
,11-03 23:35:54.239  5805  5822 D BtGatt.GattService: onClientRegistered() - UUID=d7cf1bb1-6fa1-4ed8-80fa-bf3fed8754dd, clientIf=5
11-03 23:35:54.239  5572  5582 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,11-03 23:35:54.240  4006  5878 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,11-03 23:35:54.240  5805  5849 D BtGatt.GattService: start scan with filters
11-03 23:35:54.244  5572  5619 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
11-03 23:35:54.244  5572  5619 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-03 23:35:54.244  5572  5619 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
11-03 23:35:54.244  5572  5619 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-61,5,main], id: 61
,11-03 23:35:54.244  5572  5619 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,11-03 23:35:54.244  5572  5572 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-03 23:35:54.244  5572  5572 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-03 23:35:54.244  5572  5572 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
11-03 23:35:54.244  5572  5572 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-03 23:35:54.245  5572  5572 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-03 23:35:54.245  5572  5572 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
11-03 23:35:54.245  5572  5572 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
11-03 23:35:54.245  5805  5827 D BtGatt.ScanManager: handling starting scan
11-03 23:35:54.245  5572  5619 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-03 23:35:54.246  5572  5619 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-03 23:35:54.246  5805  5827 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@38588b7
11-03 23:35:54.248  5572  5619 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
,11-03 23:35:54.248  5572  5619 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
11-03 23:35:54.248  5572  5619 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-03 23:35:54.248  5572  5619 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-03 23:35:54.248  5572  5619 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
11-03 23:35:54.248  5572  5619 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
11-03 23:35:54.249  5572  5619 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
11-03 23:35:54.249  5572  5572 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-03 23:35:54.249  5572  5619 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-03 23:35:54.249  5572  5619 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-03 23:35:54.249  5572  5619 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-03 23:35:54.249  5572  5619 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,11-03 23:35:54.251  5572  5572 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-03 23:35:54.251  5572  5572 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-03 23:35:54.251  5572  5572 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-03 23:35:54.251  5572  5572 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-03 23:35:54.252  5572  5572 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,11-03 23:35:54.251  5572  5619 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-03 23:35:54.252  5572  5619 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
11-03 23:35:54.252  5572  5619 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-03 23:35:54.252  5572  5619 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
11-03 23:35:54.252  5572  5619 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-61,5,main], id: 61
11-03 23:35:54.252  5572  5619 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-03 23:35:54.252  5572  5619 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,11-03 23:35:54.252  5572  5619 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-61,5,main], id: 61
11-03 23:35:54.253  5572  5619 D BluetoothAdapter: STATE_ON
,11-03 23:35:54.253  5805  5849 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
11-03 23:35:54.253  5805  5822 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
11-03 23:35:54.253  5805  5822 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-03 23:35:54.253  5572  5619 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-03 23:35:54.254  5805  5827 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,11-03 23:35:54.254  5572  5619 D BluetoothAdapter: STATE_ON
11-03 23:35:54.254  5805  5816 D BtGatt.GattService: stopScan() - queue size =1
11-03 23:35:54.255  4006  5878 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
11-03 23:35:54.255  4006  5878 I SystemUpdateService: now status is 0 (complete)
,11-03 23:35:54.255  4006  5878 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
11-03 23:35:54.255  4006  5878 I SystemUpdateService: file has been verified
11-03 23:35:54.255  5805  5837 D BtGatt.GattService: unregisterClient() - clientIf=5
11-03 23:35:54.255  4006  5878 I SystemUpdateService: OTA package size = 21989297
11-03 23:35:54.255  5572  5619 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,11-03 23:35:54.256  5572  5619 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-03 23:35:54.256  5572  5619 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,11-03 23:35:54.256  5572  5619 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-61,5,main], id: 61
11-03 23:35:54.256  5572  5619 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-61,5,main], id: 61
11-03 23:35:54.256  5572  5619 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-61,5,main], id: 61
11-03 23:35:54.256  5572  5619 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-61,5,main], id: 61
11-03 23:35:54.256  5572  5619 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-03 23:35:54.256  5572  5619 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
11-03 23:35:54.256  5572  5619 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-61,5,main], id: 61
11-03 23:35:54.256  5572  5619 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-61,5,main], id: 61
11-03 23:35:54.256  5572  5619 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-03 23:35:54.256  5572  5619 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-03 23:35:54.257  5572  5619 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
11-03 23:35:54.257  5572  5619 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-03 23:35:54.258   928  5866 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Thu, 03 Nov 2016 22:35:54 GMT], X-Android-Received-Millis=[1478212554257], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1478212554227]}
11-03 23:35:54.258  5572  5619 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-03 23:35:54.258  5572  5619 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-03 23:35:54.258  5572  5619 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-03 23:35:54.259  5572  5619 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-03 23:35:54.259   928  2960 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
11-03 23:35:54.259   928  2960 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] validation  passed
11-03 23:35:54.259   928  2960 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
11-03 23:35:54.260   928  2960 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
11-03 23:35:54.261  4006  5878 I SystemUpdateService: showing system update notification
11-03 23:35:54.261  5805  5822 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
11-03 23:35:54.262  5805  5822 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-03 23:35:54.262  5572  5572 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-03 23:35:54.262  5572  5572 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false,, start advertiser: false
11-03 23:35:54.262  5572  5572 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-03 23:35:54.262  5572  5572 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-03 23:35:54.262  5572  5572 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-03 23:35:54.262  5572  5572 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
11-03 23:35:54.262  5572  5572 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-03 23:35:54.262  5572  5572 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-03 23:35:54.262  5572  5572 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
11-03 23:35:54.262  5572  5572 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
,11-03 23:35:54.263  5805  5827 D BtGatt.ScanManager: Starting BLE batch scan
11-03 23:35:54.263  5805  5827 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
11-03 23:35:54.263  5572  5572 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-03 23:35:54.264  5572  5572 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-03 23:35:54.264  5572  5572 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-03 23:35:54.264  5572  5572 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
,11-03 23:35:54.264  5572  5572 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-03 23:35:54.264  5572  5619 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-03 23:35:54.264  5572  5619 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-03 23:35:54.264  5572  5619 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-03 23:35:54.264  5572  5619 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-03 23:35:54.264  5572  5619 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-03 23:35:54.264  5572  5619 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-03 23:35:54.264  5572  5619 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@392a69a removed from the list
11-03 23:35:54.264  5572  5619 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-03 23:35:54.264  5572  5619 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9500bcb removed from the list
11-03 23:35:54.264  5572  5619 D io.jxcore.node.ConnectivityMonitor: stop
11-03 23:35:54.265  5572  5619 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-03 23:35:54.266  5572  5619 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-03 23:35:54.266  5572  5619 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-03 23:35:54.266  5572  5619 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-03 23:35:54.266  5572  5619 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-03 23:35:54.266  5572  5619 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-03 23:35:54.266  5572  5619 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-03 23:35:54.266  5572  5619 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9500bcb not in the list
11-03 23:35:54.266  5572  5619 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-03 23:35:54.267  5572  5619 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-03 23:35:54.267  5572  5619 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-03 23:35:54.267  5572  5619 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-03 23:35:54.267  5572  5619 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-03 23:35:54.267  5572  5619 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-03 23:35:54.267  5572  5619 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-03 23:35:54.267  5572  5619 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@93f0ac1 removed from the list
11-03 23:35:54.267  5572  5619 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-03 23:35:54.267  5572  5619 D org.thaliproject.p2p.btconnector,lib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-03 23:35:54.268  5572  5619 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-03 23:35:54.268  5572  5619 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4af0fa8 removed from the list
11-03 23:35:54.268  5572  5619 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-03 23:35:54.268  5572  5619 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b176ef2 added. We now have 3 listener(s)
11-03 23:35:54.270  5572  5619 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-03 23:35:54.270  5572  5619 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-03 23:35:54.270  5572  5619 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-03 23:35:54.270  5572  5619 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-03 23:35:54.270  5572  5619 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@df42943 added. We now have 4 listener(s)
11-03 23:35:54.270  5572  5619 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-03 23:35:54.271  5572  5619 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,11-03 23:35:54.271  5572  5619 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,11-03 23:35:54.272  5572  5619 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@25a2bc0 added. We now have 4 listener(s)
11-03 23:35:54.273  5572  5619 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-03 23:35:54.273  5572  5619 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-03 23:35:54.273  5572  5619 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-03 23:35:54.273  5572  5619 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-03 23:35:54.273  5572  5619 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3950f9 added. We now have 5 listener(s)
11-03 23:35:54.273  5572  5619 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-03 23:35:54.273  5572  5619 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-03 23:35:54.274  5572  5619 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-03 23:35:54.274  5572  5619 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
11-03 23:35:54.274  5572  5619 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
11-03 23:35:54.274  5572  5619 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-03 23:35:54.274  5572  5619 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
11-03 23:35:54.274  5805  5822 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
11-03 23:35:54.275  5805  5822 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-03 23:35:54.275  5572  5619 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
11-03 23:35:54.278  5572  5619 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-03 23:35:54.278  5572  5619 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-03 23:35:54.278  5572  5619 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
11-03 23:35:54.279   928   928 V NotificationService: pkg=com.google.android.gms canInterrupt=false intercept=true
11-03 23:35:54.280  5805  5822 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,11-03 23:35:54.280  5805  5822 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-03 23:35:54.281  4006  4006 D SystemUpdateService: onDestroy
,11-03 23:35:54.282  5805  5827 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
11-03 23:35:54.285  5572  5619 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-61,5,main], id: 61
11-03 23:35:54.285  5572  5619 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-03 23:35:54.286  5572  5619 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-03 23:35:54.286  5572  5619 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-03 23:35:54.286  5572  5619 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 0
,11-03 23:35:54.287  5805  5822 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,11-03 23:35:54.287  5805  5822 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-03 23:35:54.287  5805  5822 E BtGatt.ContextMap: Context not found for ID 5
,11-03 23:35:54.290  5572  5619 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-61,5,main], id: 61
,11-03 23:35:54.290  5572  5619 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,11-03 23:35:54.290  5572  5619 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
11-03 23:35:54.290  5572  5619 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
11-03 23:35:54.290  5572  5619 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,11-03 23:35:54.290  5572  5619 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-61,5,main], id: 61
11-03 23:35:54.291  5572  5619 D BluetoothAdapter: STATE_ON
11-03 23:35:54.293  5805  5822 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
11-03 23:35:54.293  5805  5822 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-03 23:35:54.293  5805  5827 D BtGatt.ScanManager: stopping BLe Batch
11-03 23:35:54.294  5805  5849 D BtGatt.GattService: registerClient() - UUID=63c6f365-18b2-4838-8edd-ab4a3277e901
11-03 23:35:54.294  5805  5822 D BtGatt.GattService: onClientRegistered() - UUID=63c6f365-18b2-4838-8edd-ab4a3277e901, clientIf=5
11-03 23:35:54.295  5572  5883 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,11-03 23:35:54.295  5805  5815 D BtGatt.GattService: start scan with filters
11-03 23:35:54.298  5805  5822 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
11-03 23:35:54.298  5805  5822 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-03 23:35:54.298  5805  5827 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-03 23:35:54.301  5572  5619 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
11-03 23:35:54.301  5572  5619 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-03 23:35:54.301  5572  5619 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
11-03 23:35:54.301  5572  5619 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-61,5,main], id: 61
,11-03 23:35:54.301  5572  5619 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-03 23:35:54.301  5572  5572 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-03 23:35:54.301  5572  5572 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-03 23:35:54.302  5572  5572 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
11-03 23:35:54.302  5572  5572 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-03 23:35:54.302  5572  5572 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-03 23:35:54.302  5572  5572 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
11-03 23:35:54.302  5572  5572 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
11-03 23:35:54.302  5572  5619 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-03 23:35:54.302  5572  5619 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-03 23:35:54.303  5805  5822 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-03 23:35:54.303  5805  5822 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-03 23:35:54.304  5805  5827 D BtGatt.ScanManager: handling starting scan
11-03 23:35:54.304  5572  5619 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-03 23:35:54.305  5572  5619 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,11-03 23:35:54.305  5572  5619 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
,11-03 23:35:54.305  5572  5619 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
,11-03 23:35:54.305  5572  5619 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
11-03 23:35:54.305  5572  5572 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-03 23:35:54.305  5572  5619 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
11-03 23:35:54.305  5572  5619 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-03 23:35:54.305  5572  5619 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-03 23:35:54.305  5572  5619 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-03 23:35:54.305  5572  5619 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-03 23:35:54.305  5572  5619 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,11-03 23:35:54.305  5572  5619 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-03 23:35:54.305  5572  5619 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,11-03 23:35:54.305  5572  5619 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,11-03 23:35:54.305  5572  5619 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b176ef2 removed from the list
11-03 23:35:54.305  5572  5619 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-03 23:35:54.305  5572  5619 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@df42943 removed from the list
11-03 23:35:54.305  5572  5619 D io.jxcore.node.ConnectivityMonitor: stop
11-03 23:35:54.306  5572  5619 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,11-03 23:35:54.306  5572  5619 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-03 23:35:54.306  5572  5619 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
11-03 23:35:54.306  5572  5619 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
,11-03 23:35:54.306  5572  5619 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-03 23:35:54.306  5572  5619 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-03 23:35:54.306  5572  5619 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-03 23:35:54.307  5572  5619 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-03 23:35:54.307  5572  5619 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-03 23:35:54.307  5572  5619 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-03 23:35:54.307  5572  5572 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-03 23:35:54.307  5572  5619 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-03 23:35:54.307  5572  5619 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-03 23:35:54.307  5572  5572 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-03 23:35:54.307  5572  5619 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-03 23:35:54.307  5572  5572 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-03 23:35:54.307  5572  5572 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
,11-03 23:35:54.307  5572  5619 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@df42943 not in the list
11-03 23:35:54.307  5572  5619 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-03 23:35:54.307  5572  5619 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
11-03 23:35:54.307  5572  5572 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
11-03 23:35:54.307  5572  5619 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-03 23:35:54.307  5572  5619 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
,11-03 23:35:54.307  5572  5619 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-61,5,main], id: 61
11-03 23:35:54.307  5572  5619 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-03 23:35:54.307  5572  5619 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
11-03 23:35:54.307  5572  5619 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-61,5,main], id: 61
11-03 23:35:54.308  5572  5619 D BluetoothAdapter: STATE_ON
11-03 23:35:54.308  5805  5848 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
11-03 23:35:54.309  5572  5619 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
,11-03 23:35:54.309  5572  5619 D BluetoothAdapter: STATE_ON
11-03 23:35:54.309  5805  5837 D BtGatt.GattService: stopScan() - queue size =1
11-03 23:35:54.310  5805  5815 D BtGatt.GattService: unregisterClient() - clientIf=5
11-03 23:35:54.310  5572  5619 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-03 23:35:54.310  5805  5822 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
11-03 23:35:54.310  5805  5822 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-03 23:35:54.310  5572  5619 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-03 23:35:54.310  5572  5619 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,11-03 23:35:54.310  5572  5619 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-61,5,main], id: 61
11-03 23:35:54.310  5572  5619 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-61,5,main], id: 61
11-03 23:35:54.310  5572  5619 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-61,5,main], id: 61
11-03 23:35:54.310  5805  5827 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
11-03 23:35:54.310  5572  5619 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-61,5,main], id: 61
11-03 23:35:54.310  5572  5619 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-03 23:35:54.311  5572  5619 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
11-03 23:35:54.311  5572  5619 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-61,5,main], id: 61
11-03 23:35:54.311  5572  5619 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-61,5,main], id: 61
11-03 23:35:54.311  5572  5619 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-03 23:35:54.311  5572  5619 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-03 23:35:54.311  5572  5619 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
11-03 23:35:54.312  5572  5619 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-03 23:35:54.313  5572  5619 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-03 23:35:54.314  5572  5619 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-03 23:35:54.314  5572  5619 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-03 23:35:54.314  5572  5619 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-03 23:35:54.314  5572  5619 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-03 23:35:54.314  5572  5619 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-03 23:35:54.314  5572  5619 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-03 23:35:54.314  5572  5619 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3950f9 removed from the list
11-03 23:35:54.314  5572  5619 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-03 23:35:54.314  5572  5572 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-03 23:35:54.314  5572  5619 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-03 23:35:54.314  5572  5619 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-03 23:35:54.314  5572  5572 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-03 23:35:54.314  5572  5619 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@25a2bc0 rem,oved from the list
11-03 23:35:54.314  5572  5572 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-03 23:35:54.314  5572  5572 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-03 23:35:54.314  5572  5572 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-03 23:35:54.314  5572  5572 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
11-03 23:35:54.314  5572  5572 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-03 23:35:54.314  5572  5572 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-03 23:35:54.314  5572  5572 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
11-03 23:35:54.314  5572  5572 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-03 23:35:54.315  5572  5619 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-03 23:35:54.315  5572  5619 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9b1ea4a added. We now have 3 listener(s)
11-03 23:35:54.316  5572  5572 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-03 23:35:54.316  5572  5572 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-03 23:35:54.316  5572  5572 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-03 23:35:54.316  5572  5572 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-03 23:35:54.316  5572  5619 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-03 23:35:54.316  5572  5572 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-03 23:35:54.316  5572  5619 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-03 23:35:54.316  5572  5619 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-03 23:35:54.316  5805  5822 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
11-03 23:35:54.316  5805  5822 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-03 23:35:54.316  5572  5619 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-03 23:35:54.316  5572  5619 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@55f7dbb added. We now have 4 listener(s)
11-03 23:35:54.316  5572  5619 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-03 23:35:54.316  5805  5827 D BtGatt.ScanManager: Starting BLE batch scan
,11-03 23:35:54.316  5805  5827 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
11-03 23:35:54.317  5572  5619 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
11-03 23:35:54.318  5572  5619 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-03 23:35:54.318  5572  5619 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b99b2d8 added. We now have 4 listener(s)
11-03 23:35:54.319  5572  5619 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-03 23:35:54.319  5572  5619 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-03 23:35:54.319  5572  5619 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-03 23:35:54.320  5572  5619 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,11-03 23:35:54.320  5572  5619 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fff2631 added. We now have 5 listener(s)
11-03 23:35:54.320  5572  5619 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-03 23:35:54.320  5572  5619 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-03 23:35:54.320  5572  5619 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
11-03 23:35:54.320  5572  5619 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
11-03 23:35:54.320  5572  5619 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-03 23:35:54.320  5572  5619 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
,11-03 23:35:54.321  5572  5619 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
11-03 23:35:54.324  5572  5619 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-03 23:35:54.324  5572  5619 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-03 23:35:54.324  5572  5619 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
11-03 23:35:54.325  5805  5822 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
11-03 23:35:54.325  5805  5822 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-03 23:35:54.329  5572  5619 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-61,5,main], id: 61
11-03 23:35:54.329  5572  5619 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-03 23:35:54.330  5805  5822 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
11-03 23:35:54.330  5572  5619 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-03 23:35:54.330  5805  5822 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-03 23:35:54.330  5572  5619 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,11-03 23:35:54.330  5572  5619 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 0
,11-03 23:35:54.331  5805  5827 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-03 23:35:54.333  5572  5619 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-61,5,main], id: 61
,11-03 23:35:54.333  5572  5619 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
11-03 23:35:54.333  5572  5619 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
11-03 23:35:54.333  5572  5619 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
11-03 23:35:54.333  5572  5619 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
11-03 23:35:54.333  5572  5619 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-61,5,main], id: 61
,11-03 23:35:54.334  5572  5619 D BluetoothAdapter: STATE_ON
11-03 23:35:54.335  5805  5822 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-03 23:35:54.335  5805  5822 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-03 23:35:54.336  5805  5822 E BtGatt.ContextMap: Context not found for ID 5
11-03 23:35:54.336  5805  5848 D BtGatt.GattService: registerClient() - UUID=646f7c6e-1ca6-4153-bc4b-63b623ecff91
11-03 23:35:54.336  5805  5822 D BtGatt.GattService: onClientRegistered() - UUID=646f7c6e-1ca6-4153-bc4b-63b623ecff91, clientIf=5
,11-03 23:35:54.336  5572  5583 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
11-03 23:35:54.337  5805  5816 D BtGatt.GattService: start scan with filters
,11-03 23:35:54.339  5572  5619 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
,11-03 23:35:54.339  5572  5619 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-03 23:35:54.339  5572  5619 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
11-03 23:35:54.339  5572  5619 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-61,5,main], id: 61
11-03 23:35:54.339  5572  5619 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-03 23:35:54.339  5572  5572 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-03 23:35:54.339  5572  5572 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-03 23:35:54.339  5572  5572 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
11-03 23:35:54.339  5572  5572 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-03 23:35:54.340  5572  5572 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
,11-03 23:35:54.340  5572  5572 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
11-03 23:35:54.340  5572  5572 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
11-03 23:35:54.340  5572  5619 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-03 23:35:54.340  5572  5619 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-03 23:35:54.342  5805  5822 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
11-03 23:35:54.342  5805  5822 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-03 23:35:54.342  5572  5619 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-03 23:35:54.342  5572  5619 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
11-03 23:35:54.342  5805  5827 D BtGatt.ScanManager: stopping BLe Batch
11-03 23:35:54.342  5572  5619 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
,11-03 23:35:54.342  5572  5619 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-03 23:35:54.342  5572  5572 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-03 23:35:54.344  5572  5619 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-03 23:35:54.344  5572  5619 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-03 23:35:54.344  5572  5619 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-03 23:35:54.344  5572  5619 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-03 23:35:54.344  5572  5619 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-03 23:35:54.344  5572  5619 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-03 23:35:54.344  5572  5619 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,11-03 23:35:54.344  5572  5619 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-03 23:35:54.344  5572  5619 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9b1ea4a removed from the list
11-03 23:35:54.344  5572  5619 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-03 23:35:54.345  5572  5619 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@55f7dbb removed from the list
11-03 23:35:54.345  5572  5619 D io.jxcore.node.ConnectivityMonitor: stop
11-03 23:35:54.345  5572  5619 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-03 23:35:54.345  5572  5619 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-03 23:35:54.345  5572  5619 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
11-03 23:35:54.345  5572  5619 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
11-03 23:35:54.345  5572  5619 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-03 23:35:54.345  5572  5619 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,11-03 23:35:54.345  5572  5619 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-03 23:35:54.345  5572  5572 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-03 23:35:54.345  5572  5572 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-03 23:35:54.345  5572  5572 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-03 23:35:54.345  5572  5572 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-03 23:35:54.345  5572  5572 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
11-03 23:35:54.346  5572  5619 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-03 23:35:54.346  5572  5619 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-03 23:35:54.346  5572  5619 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-03 23:35:54.346  5572  5619 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-03 23:35:54.346  5572  5619 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-03 23:35:54.346  5805  5822 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,11-03 23:35:54.346  5572  5619 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-03 23:35:54.346  5805  5822 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-03 23:35:54.346  5572  5619 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@55f7dbb not in the list
11-03 23:35:54.347  5572  5619 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-03 23:35:54.347  5572  5619 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
11-03 23:35:54.347  5805  5827 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
11-03 23:35:54.347  5572  5619 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-03 23:35:54.347  5572  5619 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
11-03 23:35:54.347  5572  5619 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-61,5,main], id: 61
11-03 23:35:54.347  5572  5619 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-03 23:35:54.347  5572  5619 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,11-03 23:35:54.347  5572  5619 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-61,5,main], id: 61
11-03 23:35:54.348  5572  5619 D BluetoothAdapter: STATE_ON
11-03 23:35:54.348  5805  5849 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
11-03 23:35:54.349  5572  5619 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-03 23:35:54.349  5572  5619 D BluetoothAdapter: STATE_ON
11-03 23:35:54.350  5805  5816 D BtGatt.GattService: stopScan() - queue size =0
11-03 23:35:54.350  5805  5848 D BtGatt.GattService: unregisterClient() - clientIf=5
11-03 23:35:54.350  5572  5619 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-03 23:35:54.350  5572  5619 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-03 23:35:54.350  5572  5619 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,11-03 23:35:54.350  5572  5619 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-61,5,main], id: 61
11-03 23:35:54.350  5572  5619 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-61,5,main], id: 61
11-03 23:35:54.351  5572  5619 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-61,5,main], id: 61
11-03 23:35:54.351  5572  5619 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-61,5,main], id: 61
11-03 23:35:54.351  5572  5619 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-03 23:35:54.351  5572  5619 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
11-03 23:35:54.351  5572  5619 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-61,5,main], id: 61
11-03 23:35:54.351  5805  5822 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-03 23:35:54.351  5805  5822 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-03 23:35:54.351  5572  5619 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-61,5,main], id: 61
,11-03 23:35:54.351  5572  5619 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-03 23:35:54.351  5572  5619 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-03 23:35:54.352  5805  5827 D BtGatt.ScanManager: handling starting scan
11-03 23:35:54.353  5572  5619 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
11-03 23:35:54.353  5572  5619 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-03 23:35:54.354  5572  5619 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-03 23:35:54.354  5572  5619 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-03 23:35:54.354  5572  5619 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-03 23:35:54.354  5572  5619 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-03 23:35:54.354  5572  5619 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-03 23:35:54.354  5572  5619 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-03 23:35:54.354  5572  5619 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-03 23:35:54.354  5572  5619 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fff2631 removed from the list
11-03 23:35:54.355  5572  5619 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-03 23:35:54.355  5572  5619 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-03 23:35:54.355  5572  5619 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-03 23:35:54.355  5572  5619 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b99b2d8 removed from the list
11-03 23:35:54.355  5572  5572 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-03 23:35:54.355  5572  5572 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-03 23:35:54.355  5572  5572 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-03 23:35:54.355  5572  5572 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
,11-03 23:35:54.355  5572  5572 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-03 23:35:54.355  5572  5572 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
11-03 23:35:54.355  5572  5572 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-03 23:35:54.355  5572  5572 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-03 23:35:54.355  5572  5572 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,11-03 23:35:54.355  5572  5572 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-03 23:35:54.355  5572  5619 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-03 23:35:54.356  5572  5619 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@578a2 added. We now have 3 listener(s)
11-03 23:35:54.356  5572  5572 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-03 23:35:54.357  5572  5572 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-03 23:35:54.357  5572  5572 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-03 23:35:54.357  5572  5572 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-03 23:35:54.357  5572  5572 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-03 23:35:54.357  5805  5822 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
11-03 23:35:54.357  5805  5822 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-03 23:35:54.357  5572  5619 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-03 23:35:54.357  5805  5827 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
11-03 23:35:54.357  5572  5619 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-03 23:35:54.357  5572  5619 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-03 23:35:54.357  5572  5619 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-03 23:35:54.357  5572  5619 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c61e933 added. We now have 4 listener(s)
11-03 23:35:54.358  5572  5619 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-03 23:35:54.358  5572  5619 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
11-03 23:35:54.359  5572  5619 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-03 23:35:54.359  5572  5619 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b3004f0 added. We now have 4 listener(s)
,11-03 23:35:54.361  5572  5619 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-03 23:35:54.361  5572  5619 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-03 23:35:54.361  5572  5619 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-03 23:35:54.361  5805  5822 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
11-03 23:35:54.361  5805  5822 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-03 23:35:54.361  5572  5619 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,11-03 23:35:54.361  5572  5619 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6936a69 added. We now have 5 listener(s)
11-03 23:35:54.361  5805  5827 D BtGatt.ScanManager: Starting BLE batch scan
11-03 23:35:54.361  5572  5619 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-03 23:35:54.362  5805  5827 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
11-03 23:35:54.362  5572  5619 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-03 23:35:54.362  5572  5619 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-03 23:35:54.362  5572  5619 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-03 23:35:54.362  5572  5619 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-03 23:35:54.362  5572  5619 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,11-03 23:35:54.362  5572  5619 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-03 23:35:54.362  5572  5619 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@578a2 removed from the list
11-03 23:35:54.362  5572  5619 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-03 23:35:54.362  5572  5619 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c61e933 removed from the list
11-03 23:35:54.363  5572  5619 D io.jxcore.node.ConnectivityMonitor: stop
11-03 23:35:54.363  5572  5619 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-03 23:35:54.364  5572  5619 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-03 23:35:54.364  5572  5619 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-03 23:35:54.364  5572  5619 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-03 23:35:54.364  5572  5619 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,11-03 23:35:54.364  5572  5619 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-03 23:35:54.364  5572  5619 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-03 23:35:54.364  5572  5619 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c61e933 not in the list
,11-03 23:35:54.365  5572  5619 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-03 23:35:54.366  5572  5619 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
,11-03 23:35:54.366  5572  5619 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-03 23:35:54.366  5572  5619 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
,11-03 23:35:54.366  5572  5619 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-03 23:35:54.366  5572  5619 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-03 23:35:54.366  5572  5619 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-03 23:35:54.366  5572  5619 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6936a69 removed from the list
11-03 23:35:54.366  5572  5619 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-03 23:35:54.366  5572  5619 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-03 23:35:54.366  5572  5619 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,11-03 23:35:54.366  5572  5619 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b3004f0 removed from the list
11-03 23:35:54.367  5572  5619 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
11-03 23:35:54.367  5572  5619 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
11-03 23:35:54.367  5572  5619 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
11-03 23:35:54.367  5572  5619 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-03 23:35:54.367  5572  5619 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
11-03 23:35:54.367  5572  5619 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,11-03 23:35:54.371  5805  5822 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
11-03 23:35:54.371  5805  5822 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-03 23:35:54.375  5805  5822 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,11-03 23:35:54.376  5805  5822 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-03 23:35:54.377  5805  5827 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-03 23:35:54.381  5805  5822 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,11-03 23:35:54.381  5805  5822 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-03 23:35:54.381  5805  5822 E BtGatt.ContextMap: Context not found for ID 5
,11-03 23:35:54.386  5805  5822 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
,11-03 23:35:54.386  5805  5822 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-03 23:35:54.386  5805  5827 D BtGatt.ScanManager: stopping BLe Batch
,11-03 23:35:54.390  5805  5822 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,11-03 23:35:54.390  5805  5822 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-03 23:35:54.391  5805  5827 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-03 23:35:54.395  5805  5822 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,11-03 23:35:54.395  5805  5822 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-03 23:35:54.765  5572  5572 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-03 23:35:54.817  5572  5572 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-03 23:35:54.858  5572  5572 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-03 23:35:55.127   535   535 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,11-03 23:35:56.520  5572  5887 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 178, name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
11-03 23:35:56.520  5572  5887 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-03 23:35:57.315  5572  5887 W !!      : call onHalfStreamCopied
,11-03 23:35:57.315  5572  5887 I testCopyDataAndClose: closing input stream
,11-03 23:35:57.561  3596  5889 I VacuumService: Vacuum at: now=1478212557561 tag=VacuumService
,11-03 23:35:57.607  3596  5892 D GetConfigurationSnapshotOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,11-03 23:35:57.636  3596  5890 I PhenotypeFlagCommitter: Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,11-03 23:35:57.638  3596  5890 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,11-03 23:35:57.660  3596  5890 W Uploader:  no longer exists, so no auth token.
,11-03 23:35:57.669  3596  5892 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,11-03 23:35:57.968  3596  5894 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,11-03 23:35:58.033  3596  5890 W Uploader:  no longer exists, so no auth token.
,11-03 23:35:58.043  3596  5892 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,11-03 23:35:58.085  5572  5887 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 178, thread name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
11-03 23:35:58.085  5572  5887 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-03 23:35:58.085  5572  5887 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
11-03 23:35:58.085  5572  5887 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
11-03 23:35:58.085  5572  5887 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
,11-03 23:35:58.085  5572  5887 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
11-03 23:35:58.085  5572  5887 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
11-03 23:35:58.085  5572  5887 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
11-03 23:35:58.085  5572  5887 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
,11-03 23:35:58.085  5572  5887 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 178, name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
11-03 23:35:58.085  5572  5887 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 20971520 and the total number of bytes written 20971520
,11-03 23:35:58.132  3596  5894 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,11-03 23:35:58.220  3596  5892 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,11-03 23:36:02.115   928  2960 D ConnectivityService: handlePromptUnvalidated 102
,11-03 23:36:02.435  5572  5899 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 181, name: My test thread name). Connection data: Peer properties: [null null].
11-03 23:36:02.435  5572  5899 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-03 23:36:04.435  5572  5619 I io.jxcore.node.StreamCopyingThread: close: Thread ID: 181. Connection data: Peer properties: [null null].
11-03 23:36:04.435  5572  5619 I io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-03 23:36:04.435  5572  5619 D io.jxcore.node.StreamCopyingThread: closeStreams: Streams closed (thread ID: 181, name: My test thread name)
11-03 23:36:04.436  5572  5899 D io.jxcore.node.StreamCopyingThread: number of bytes read = 0
,11-03 23:36:04.437  5572  5899 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 181, name: My test thread name). Connection data: Peer properties: [null null].
11-03 23:36:04.437  5572  5899 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 176 and the total number of bytes written 176
,11-03 23:36:04.623  5572  5900 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 183, name: testCopyBigData thread). Connection data: Peer properties: [null null].
11-03 23:36:04.623  5572  5900 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-03 23:36:06.243  5572  5900 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 183, thread name: testCopyBigData thread). Connection data: Peer properties: [null null].
11-03 23:36:06.243  5572  5900 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-03 23:36:06.244  5572  5900 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
11-03 23:36:06.244  5572  5900 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
11-03 23:36:06.244  5572  5900 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
11-03 23:36:06.244  5572  5900 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
,11-03 23:36:06.244  5572  5900 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
11-03 23:36:06.244  5572  5900 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
11-03 23:36:06.244  5572  5900 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
11-03 23:36:06.244  5572  5900 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 183, name: testCopyBigData thread). Connection data: Peer properties: [null null].
11-03 23:36:06.244  5572  5900 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 20971520 and the total number of bytes written 20971520
,11-03 23:36:10.488  5572  5901 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 185, name: My test thread name). Connection data: Peer properties: [null null].
11-03 23:36:10.488  5572  5901 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-03 23:36:10.488  5572  5901 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 185, thread name: My test thread name). Connection data: Peer properties: [null null].
11-03 23:36:10.488  5572  5901 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-03 23:36:10.489  5572  5901 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
11-03 23:36:10.489  5572  5901 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-03 23:36:10.489  5572  5901 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
11-03 23:36:10.489  5572  5901 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
,11-03 23:36:10.489  5572  5901 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
11-03 23:36:10.489  5572  5901 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
,11-03 23:36:10.490  5572  5901 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
11-03 23:36:10.490  5572  5901 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 185, name: My test thread name). Connection data: Peer properties: [null null].
11-03 23:36:10.490  5572  5901 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 22
,11-03 23:36:10.491  5572  5619 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
11-03 23:36:10.494  5572  5902 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 189, name: My test thread name). Connection data: Peer properties: [null null].
11-03 23:36:10.494  5572  5902 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-03 23:36:10.495  5572  5902 E io.jxcore.node.StreamCopyingThread: Failed to write to the output stream (thread ID: 189, thread name: My test thread name): Test exception.
11-03 23:36:10.496  5572  5902 D io.jxcore.node.StreamCopyingThread: onStreamCopyError (ID: 189, name: My test thread name). Connection data: Peer properties: [null null].
11-03 23:36:10.496  5572  5902 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
11-03 23:36:10.496  5572  5902 D io.jxcore.node.StreamCopyingThread: number of bytes read = 22
11-03 23:36:10.496  5572  5902 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 189, name: My test thread name). Connection data: Peer properties: [null null].
11-03 23:36:10.496  5572  5902 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
,11-03 23:36:10.501  5572  5619 I jxcore-log: 2016-11-03 22:36:10 - DEBUG UnitTest_app: 'Total number of executed tests:  82'
11-03 23:36:10.501  5572  5619 I jxcore-log: 
11-03 23:36:10.501  5572  5619 I jxcore-log: 2016-11-03 22:36:10 - DEBUG UnitTest_app: 'Number of passed tests:  82'
11-03 23:36:10.501  5572  5619 I jxcore-log: 
11-03 23:36:10.502  5572  5619 I jxcore-log: 2016-11-03 22:36:10 - DEBUG UnitTest_app: 'Number of failed tests:  0'
11-03 23:36:10.502  5572  5619 I jxcore-log: 
,11-03 23:36:10.502  5572  5619 I jxcore-log: 2016-11-03 22:36:10 - DEBUG UnitTest_app: 'Number of ignored tests:  0'
11-03 23:36:10.502  5572  5619 I jxcore-log: 
11-03 23:36:10.502  5572  5619 I jxcore-log: 2016-11-03 22:36:10 - DEBUG UnitTest_app: 'Total duration:  91964'
11-03 23:36:10.502  5572  5619 I jxcore-log: 
,11-03 23:36:10.504  5572  5619 I jxcore-log: 2016-11-03 22:36:10 - DEBUG UnitTest_app: 'Unit Test app is loaded'
11-03 23:36:10.504  5572  5619 I jxcore-log: 
,11-03 23:36:10.507  5572  5619 I jxcore-log: 2016-11-03 22:36:10 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
11-03 23:36:10.507  5572  5619 I jxcore-log: 
,11-03 23:36:10.508  5572  5619 I jxcore-log: 2016-11-03 22:36:10 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
11-03 23:36:10.508  5572  5619 I jxcore-log: 
11-03 23:36:10.509  5572  5619 I jxcore-log: 2016-11-03 22:36:10 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
11-03 23:36:10.509  5572  5619 I jxcore-log: 
11-03 23:36:10.509  5572  5619 I jxcore-log: 2016-11-03 22:36:10 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH"})'
11-03 23:36:10.509  5572  5619 I jxcore-log: 
,11-03 23:36:10.509  5572  5619 I jxcore-log: 2016-11-03 22:36:10 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-03 23:36:10.509  5572  5619 I jxcore-log: 
11-03 23:36:10.509  5572  5619 I jxcore-log: 2016-11-03 22:36:10 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-03 23:36:10.509  5572  5619 I jxcore-log: 
11-03 23:36:10.510  5572  5619 I jxcore-log: 2016-11-03 22:36:10 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-03 23:36:10.510  5572  5619 I jxcore-log: 
11-03 23:36:10.510  5572  5619 I jxcore-log: 2016-11-03 22:36:10 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
11-03 23:36:10.510  5572  5619 I jxcore-log: 
11-03 23:36:10.510  5572  5619 I jxcore-log: 2016-11-03 22:36:10 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
11-03 23:36:10.510  5572  5619 I jxcore-log: 
11-03 23:36:10.511  5572  5619 I jxcore-log: 2016-11-03 22:36:10 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
11-03 23:36:10.511  5572  5619 I jxcore-log: 
11-03 23:36:10.511  5572  5619 I jxcore-log: 2016-11-03 22:36:10 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH"})'
11-03 23:36:10.511  5572  5619 I jxcore-log: 
11-03 23:36:10.511  5572  5619 I jxcore-log: 2016-11-03 22:36:10 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-03 23:36:10.511  5572  5619 I jxcore-log: 
,11-03 23:36:10.511  5572  5619 I jxcore-log: 2016-11-03 22:36:10 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-03 23:36:10.511  5572  5619 I jxcore-log: 
11-03 23:36:10.511  5572  5619 I jxcore-log: 2016-11-03 22:36:10 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-03 23:36:10.511  5572  5619 I jxcore-log: 
11-03 23:36:10.512  5572  5619 I jxcore-log: 2016-11-03 22:36:10 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-03 23:36:10.512  5572  5619 I jxcore-log: 
11-03 23:36:10.512  5572  5619 I jxcore-log: 2016-11-03 22:36:10 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-03 23:36:10.512  5572  5619 I jxcore-log: 
11-03 23:36:10.512  5572  5619 I jxcore-log: 2016-11-03 22:36:10 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
11-03 23:36:10.512  5572  5619 I jxcore-log: 
11-03 23:36:10.512  5572  5619 I jxcore-log: 2016-11-03 22:36:10 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
11-03 23:36:10.512  5572  5619 I jxcore-log: 
11-03 23:36:10.513  5572  5619 I jxcore-log: 2016-11-03 22:36:10 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
11-03 23:36:10.513  5572  5619 I jxcore-log: 
11-03 23:36:10.513  5572  5619 I jxcore-log: 2016-11-03 22:36:10 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
11-03 23:36:10.513  5572  5619 I jxcore-log: 
11-03 23:36:10.513  5572  5619 I jxcore-log: 2016-11-03 22:36:10 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
11-03 23:36:10.513  5572  5619 I jxcore-log: 
11-03 23:36:10.513  5572  5619 I jxcore-log: 2016-11-03 22:36:10 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
11-03 23:36:10.513  5572  5619 I jxcore-log: 
11-03 23:36:10.514  5572  5619 I jxcore-log: 2016-11-03 22:36:10 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
11-03 23:36:10.514  5572  5619 I jxcore-log: 
,11-03 23:36:10.514  5572  5619 I jxcore-log: 2016-11-03 22:36:10 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
11-03 23:36:10.514  5572  5619 I jxcore-log: 
11-03 23:36:10.516  5572  5619 I jxcore-log: 2016-11-03 22:36:10 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
11-03 23:36:10.516  5572  5619 I jxcore-log: 
,11-03 23:36:10.516  5572  5619 I jxcore-log: 2016-11-03 22:36:10 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
11-03 23:36:10.516  5572  5619 I jxcore-log: 
11-03 23:36:10.516  5572  5619 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-03 23:36:10.516  5572  5619 D io.jxcore.node.StartStopOperationHandler: Operation timeout, state error: null
11-03 23:36:10.516  5572  5619 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-03 23:36:10.516  5572  5619 D io.jxcore.node.StartStopOperationHandler: Operation timeout, state error: Discovery manager not started
11-03 23:36:10.517  5572  5619 I jxcore-log: 2016-11-03 22:36:10 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-03 23:36:10.517  5572  5619 I jxcore-log: 
11-03 23:36:10.517  5572  5619 I jxcore-log: 2016-11-03 22:36:10 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-03 23:36:10.517  5572  5619 I jxcore-log: 
,11-03 23:36:10.517  5572  5619 I jxcore-log: 2016-11-03 22:36:10 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-03 23:36:10.517  5572  5619 I jxcore-log: 
11-03 23:36:10.517  5572  5619 I jxcore-log: 2016-11-03 22:36:10 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-03 23:36:10.517  5572  5619 I jxcore-log: 
11-03 23:36:10.517  5572  5619 I jxcore-log: 2016-11-03 22:36:10 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-03 23:36:10.517  5572  5619 I jxcore-log: 
11-03 23:36:10.518  5572  5619 I jxcore-log: 2016-11-03 22:36:10 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-03 23:36:10.518  5572  5619 I jxcore-log: 
,11-03 23:36:10.522  5572  5572 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
,11-03 23:36:10.523  5572  5619 I jxcore-log: 2016-11-03 22:36:10 - DEBUG UnitTest_app: 'My device name is: Huawei-Nexus 6P'
11-03 23:36:10.523  5572  5619 I jxcore-log: 
,11-03 23:36:12.583  5572  5619 I jxcore-log: 2016-11-03 22:36:12 - INFO runTests: 'Starting tests. Network type: WIFI. Platform: android'
11-03 23:36:12.583  5572  5619 I jxcore-log: 
,11-03 23:36:12.584  5572  5619 I jxcore-log: 2016-11-03 22:36:12 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js'
11-03 23:36:12.584  5572  5619 I jxcore-log: 
,11-03 23:36:12.925  5572  5619 I jxcore-log: 2016-11-03 22:36:12 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js'
11-03 23:36:12.925  5572  5619 I jxcore-log: 
,11-03 23:36:12.937  5572  5619 I jxcore-log: 2016-11-03 22:36:12 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManager.js'
11-03 23:36:12.937  5572  5619 I jxcore-log: 
,11-03 23:36:14.058  5572  5619 I jxcore-log: 2016-11-03 22:36:14 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js'
11-03 23:36:14.058  5572  5619 I jxcore-log: 
,11-03 23:36:14.247  5572  5619 I jxcore-log: 2016-11-03 22:36:14 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js'
11-03 23:36:14.247  5572  5619 I jxcore-log: 
,11-03 23:36:14.252  5572  5619 I jxcore-log: 2016-11-03 22:36:14 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testNativeMethod.js'
11-03 23:36:14.252  5572  5619 I jxcore-log: 
,11-03 23:36:14.257  5572  5619 I jxcore-log: 2016-11-03 22:36:14 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPouchDBCheckpointPlugin.js'
11-03 23:36:14.257  5572  5619 I jxcore-log: 
,11-03 23:36:14.733  5572  5619 I jxcore-log: 2016-11-03 22:36:14 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPouchDBGenerator.js'
11-03 23:36:14.733  5572  5619 I jxcore-log: 
,11-03 23:36:14.778  5572  5619 I jxcore-log: 2016-11-03 22:36:14 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js'
11-03 23:36:14.778  5572  5619 I jxcore-log: 
,11-03 23:36:14.791  5572  5619 I jxcore-log: 2016-11-03 22:36:14 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js'
11-03 23:36:14.791  5572  5619 I jxcore-log: 
,11-03 23:36:14.795  5572  5619 I jxcore-log: 2016-11-03 22:36:14 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliManager.js'
11-03 23:36:14.795  5572  5619 I jxcore-log: 
,11-03 23:36:15.082  5572  5619 I jxcore-log: 2016-11-03 22:36:15 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliManagerCoordinated.js'
11-03 23:36:15.082  5572  5619 I jxcore-log: 
,11-03 23:36:15.129   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-03 23:36:15.210  5572  5619 I jxcore-log: 2016-11-03 22:36:15 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js'
11-03 23:36:15.210  5572  5619 I jxcore-log: 
,11-03 23:36:15.578  5572  5619 I jxcore-log: 2016-11-03 22:36:15 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js'
11-03 23:36:15.578  5572  5619 I jxcore-log: 
,11-03 23:36:15.587  5572  5619 I jxcore-log: 2016-11-03 22:36:15 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeDiscoveryCoordinated.js'
11-03 23:36:15.587  5572  5619 I jxcore-log: 
,11-03 23:36:15.591  5572  5619 I jxcore-log: 2016-11-03 22:36:15 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js'
11-03 23:36:15.591  5572  5619 I jxcore-log: 
,11-03 23:36:15.596  5572  5619 I jxcore-log: 2016-11-03 22:36:15 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js'
11-03 23:36:15.596  5572  5619 I jxcore-log: 
,11-03 23:36:15.601  5572  5619 I jxcore-log: 2016-11-03 22:36:15 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js'
11-03 23:36:15.601  5572  5619 I jxcore-log: 
,11-03 23:36:15.628  5572  5619 I jxcore-log: 2016-11-03 22:36:15 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js'
11-03 23:36:15.628  5572  5619 I jxcore-log: 
,11-03 23:36:15.664  5572  5619 I jxcore-log: 2016-11-03 22:36:15 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js'
11-03 23:36:15.664  5572  5619 I jxcore-log: 
,11-03 23:36:15.671  5572  5619 I jxcore-log: 2016-11-03 22:36:15 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationLocal.js'
11-03 23:36:15.671  5572  5619 I jxcore-log: 
,11-03 23:36:15.678  5572  5619 I jxcore-log: 2016-11-03 22:36:15 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js'
11-03 23:36:15.678  5572  5619 I jxcore-log: 
,11-03 23:36:15.693  5572  5619 I jxcore-log: 2016-11-03 22:36:15 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js'
11-03 23:36:15.693  5572  5619 I jxcore-log: 
,11-03 23:36:15.697  5572  5619 I jxcore-log: 2016-11-03 22:36:15 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js'
11-03 23:36:15.697  5572  5619 I jxcore-log: 
,11-03 23:36:15.703  5572  5619 I jxcore-log: 2016-11-03 22:36:15 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolDefault.js'
11-03 23:36:15.703  5572  5619 I jxcore-log: 
,11-03 23:36:15.708  5572  5619 I jxcore-log: 2016-11-03 22:36:15 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js'
11-03 23:36:15.708  5572  5619 I jxcore-log: 
,11-03 23:36:15.721  5572  5619 I jxcore-log: 2016-11-03 22:36:15 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolOneAtATime.js'
11-03 23:36:15.721  5572  5619 I jxcore-log: 
,11-03 23:36:15.757  5572  5619 I jxcore-log: 2016-11-03 22:36:15 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js'
11-03 23:36:15.757  5572  5619 I jxcore-log: 
,11-03 23:36:15.772  5572  5619 I jxcore-log: 2016-11-03 22:36:15 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js'
11-03 23:36:15.772  5572  5619 I jxcore-log: 
,11-03 23:36:15.782  5572  5619 I jxcore-log: 2016-11-03 22:36:15 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerAction.js'
11-03 23:36:15.782  5572  5619 I jxcore-log: 
,11-03 23:36:15.805  5572  5619 I jxcore-log: 2016-11-03 22:36:15 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js'
11-03 23:36:15.805  5572  5619 I jxcore-log: 
,11-03 23:36:15.816  5572  5619 I jxcore-log: 2016-11-03 22:36:15 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js'
11-03 23:36:15.816  5572  5619 I jxcore-log: 
,11-03 23:36:15.830  5572  5619 I jxcore-log: 2016-11-03 22:36:15 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js'
11-03 23:36:15.830  5572  5619 I jxcore-log: 
,11-03 23:36:15.840  5572  5619 I jxcore-log: 2016-11-03 22:36:15 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js'
11-03 23:36:15.840  5572  5619 I jxcore-log: 
,11-03 23:36:15.846  5572  5619 I jxcore-log: 2016-11-03 22:36:15 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js'
11-03 23:36:15.846  5572  5619 I jxcore-log: 
,11-03 23:36:15.869  5572  5619 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: SUPPORTED
,11-03 23:36:15.870  5572  5619 I jxcore-log: 2016-11-03 22:36:15 - INFO testUtils: 'BLE multiple advertisement supported'
11-03 23:36:15.870  5572  5619 I jxcore-log: 
,11-03 23:36:16.090  5572  5619 I jxcore-log: 2016-11-03 22:36:16 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-03 23:36:16.090  5572  5619 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-03 23:36:16.090  5572  5619 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-03 23:36:16.090  5572  5619 I jxcore-log: emit@events.js:82:1
11-03 23:36:16.090  5572  5619 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-03 23:36:16.090  5572  5619 I jxcore-log: emit@events.js:82:1'
11-03 23:36:16.090  5572  5619 I jxcore-log: 
,11-03 23:36:16.130   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-03 23:36:16.333  5572  5619 I jxcore-log: 2016-11-03 22:36:16 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-03 23:36:16.333  5572  5619 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-03 23:36:16.333  5572  5619 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-03 23:36:16.333  5572  5619 I jxcore-log: emit@events.js:82:1
11-03 23:36:16.333  5572  5619 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-03 23:36:16.333  5572  5619 I jxcore-log: emit@events.js:82:1'
11-03 23:36:16.333  5572  5619 I jxcore-log: 
,11-03 23:36:16.336  5572  5619 I jxcore-log: 2016-11-03 22:36:16 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-03 23:36:16.336  5572  5619 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-03 23:36:16.336  5572  5619 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-03 23:36:16.336  5572  5619 I jxcore-log: emit@events.js:82:1
11-03 23:36:16.336  5572  5619 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-03 23:36:16.336  5572  5619 I jxcore-log: emit@events.js:82:1'
11-03 23:36:16.336  5572  5619 I jxcore-log: 
,11-03 23:36:16.679  5572  5619 I jxcore-log: 2016-11-03 22:36:16 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-03 23:36:16.679  5572  5619 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-03 23:36:16.679  5572  5619 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-03 23:36:16.679  5572  5619 I jxcore-log: emit@events.js:82:1
11-03 23:36:16.679  5572  5619 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-03 23:36:16.679  5572  5619 I jxcore-log: emit@events.js:82:1'
11-03 23:36:16.679  5572  5619 I jxcore-log: 
,11-03 23:36:16.682  5572  5619 I jxcore-log: 2016-11-03 22:36:16 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-03 23:36:16.682  5572  5619 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-03 23:36:16.682  5572  5619 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-03 23:36:16.682  5572  5619 I jxcore-log: emit@events.js:82:1
11-03 23:36:16.682  5572  5619 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-03 23:36:16.682  5572  5619 I jxcore-log: emit@events.js:82:1'
11-03 23:36:16.682  5572  5619 I jxcore-log: 
,11-03 23:36:16.803   928  5867 D NetlinkSocketObserver: NeighborEvent{elapsedMs=190237, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,11-03 23:36:17.131   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-03 23:36:17.715  5572  5619 I jxcore-log: 2016-11-03 22:36:17 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-03 23:36:17.715  5572  5619 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-03 23:36:17.715  5572  5619 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-03 23:36:17.715  5572  5619 I jxcore-log: emit@events.js:82:1
11-03 23:36:17.715  5572  5619 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-03 23:36:17.715  5572  5619 I jxcore-log: emit@events.js:82:1'
11-03 23:36:17.715  5572  5619 I jxcore-log: 
,11-03 23:36:17.718  5572  5619 I jxcore-log: 2016-11-03 22:36:17 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-03 23:36:17.718  5572  5619 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-03 23:36:17.718  5572  5619 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-03 23:36:17.718  5572  5619 I jxcore-log: emit@events.js:82:1
11-03 23:36:17.718  5572  5619 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-03 23:36:17.718  5572  5619 I jxcore-log: emit@events.js:82:1'
11-03 23:36:17.718  5572  5619 I jxcore-log: 
,11-03 23:36:18.132   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-03 23:36:18.752  5572  5619 I jxcore-log: 2016-11-03 22:36:18 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-03 23:36:18.752  5572  5619 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-03 23:36:18.752  5572  5619 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-03 23:36:18.752  5572  5619 I jxcore-log: emit@events.js:82:1
11-03 23:36:18.752  5572  5619 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-03 23:36:18.752  5572  5619 I jxcore-log: emit@events.js:82:1'
11-03 23:36:18.752  5572  5619 I jxcore-log: 
,11-03 23:36:18.757  5572  5619 I jxcore-log: 2016-11-03 22:36:18 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-03 23:36:18.757  5572  5619 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-03 23:36:18.757  5572  5619 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-03 23:36:18.757  5572  5619 I jxcore-log: emit@events.js:82:1
11-03 23:36:18.757  5572  5619 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-03 23:36:18.757  5572  5619 I jxcore-log: emit@events.js:82:1'
11-03 23:36:18.757  5572  5619 I jxcore-log: 
,11-03 23:36:19.133   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-03 23:36:19.797  5572  5619 I jxcore-log: 2016-11-03 22:36:19 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-03 23:36:19.797  5572  5619 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-03 23:36:19.797  5572  5619 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-03 23:36:19.797  5572  5619 I jxcore-log: emit@events.js:82:1
11-03 23:36:19.797  5572  5619 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-03 23:36:19.797  5572  5619 I jxcore-log: emit@events.js:82:1'
11-03 23:36:19.797  5572  5619 I jxcore-log: 
,11-03 23:36:19.803  5572  5619 I jxcore-log: 2016-11-03 22:36:19 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-03 23:36:19.803  5572  5619 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-03 23:36:19.803  5572  5619 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-03 23:36:19.803  5572  5619 I jxcore-log: emit@events.js:82:1
11-03 23:36:19.803  5572  5619 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-03 23:36:19.803  5572  5619 I jxcore-log: emit@events.js:82:1'
11-03 23:36:19.803  5572  5619 I jxcore-log: 
,11-03 23:36:20.134   535   535 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,11-03 23:36:20.833  5572  5619 I jxcore-log: 2016-11-03 22:36:20 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-03 23:36:20.833  5572  5619 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-03 23:36:20.833  5572  5619 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-03 23:36:20.833  5572  5619 I jxcore-log: emit@events.js:82:1
11-03 23:36:20.833  5572  5619 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-03 23:36:20.833  5572  5619 I jxcore-log: emit@events.js:82:1'
11-03 23:36:20.833  5572  5619 I jxcore-log: 
,11-03 23:36:20.837  5572  5619 I jxcore-log: 2016-11-03 22:36:20 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-03 23:36:20.837  5572  5619 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-03 23:36:20.837  5572  5619 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-03 23:36:20.837  5572  5619 I jxcore-log: emit@events.js:82:1
11-03 23:36:20.837  5572  5619 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-03 23:36:20.837  5572  5619 I jxcore-log: emit@events.js:82:1'
11-03 23:36:20.837  5572  5619 I jxcore-log: 
,11-03 23:36:21.869  5572  5619 I jxcore-log: 2016-11-03 22:36:21 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-03 23:36:21.869  5572  5619 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-03 23:36:21.869  5572  5619 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-03 23:36:21.869  5572  5619 I jxcore-log: emit@events.js:82:1
11-03 23:36:21.869  5572  5619 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-03 23:36:21.869  5572  5619 I jxcore-log: emit@events.js:82:1'
11-03 23:36:21.869  5572  5619 I jxcore-log: 
,11-03 23:36:21.873  5572  5619 I jxcore-log: 2016-11-03 22:36:21 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-03 23:36:21.873  5572  5619 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-03 23:36:21.873  5572  5619 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-03 23:36:21.873  5572  5619 I jxcore-log: emit@events.js:82:1
11-03 23:36:21.873  5572  5619 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-03 23:36:21.873  5572  5619 I jxcore-log: emit@events.js:82:1'
11-03 23:36:21.873  5572  5619 I jxcore-log: 
,11-03 23:36:22.709   928  5867 D NetlinkSocketObserver: NeighborEvent{elapsedMs=196143, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,11-03 23:36:22.898  5572  5619 I jxcore-log: 2016-11-03 22:36:22 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-03 23:36:22.898  5572  5619 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-03 23:36:22.898  5572  5619 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-03 23:36:22.898  5572  5619 I jxcore-log: emit@events.js:82:1
11-03 23:36:22.898  5572  5619 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-03 23:36:22.898  5572  5619 I jxcore-log: emit@events.js:82:1'
11-03 23:36:22.898  5572  5619 I jxcore-log: 
,11-03 23:36:22.904  5572  5619 I jxcore-log: 2016-11-03 22:36:22 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-03 23:36:22.904  5572  5619 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-03 23:36:22.904  5572  5619 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-03 23:36:22.904  5572  5619 I jxcore-log: emit@events.js:82:1
11-03 23:36:22.904  5572  5619 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-03 23:36:22.904  5572  5619 I jxcore-log: emit@events.js:82:1'
11-03 23:36:22.904  5572  5619 I jxcore-log: 
,11-03 23:36:23.940  5572  5619 I jxcore-log: 2016-11-03 22:36:23 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-03 23:36:23.940  5572  5619 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-03 23:36:23.940  5572  5619 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-03 23:36:23.940  5572  5619 I jxcore-log: emit@events.js:82:1
11-03 23:36:23.940  5572  5619 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-03 23:36:23.940  5572  5619 I jxcore-log: emit@events.js:82:1'
11-03 23:36:23.940  5572  5619 I jxcore-log: 
,11-03 23:36:23.947  5572  5619 I jxcore-log: 2016-11-03 22:36:23 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-03 23:36:23.947  5572  5619 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-03 23:36:23.947  5572  5619 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-03 23:36:23.947  5572  5619 I jxcore-log: emit@events.js:82:1
11-03 23:36:23.947  5572  5619 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-03 23:36:23.947  5572  5619 I jxcore-log: emit@events.js:82:1'
11-03 23:36:23.947  5572  5619 I jxcore-log: 
,11-03 23:36:25.014  5572  5619 I jxcore-log: 2016-11-03 22:36:25 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-03 23:36:25.014  5572  5619 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-03 23:36:25.014  5572  5619 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-03 23:36:25.014  5572  5619 I jxcore-log: emit@events.js:82:1
11-03 23:36:25.014  5572  5619 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-03 23:36:25.014  5572  5619 I jxcore-log: emit@events.js:82:1'
11-03 23:36:25.014  5572  5619 I jxcore-log: 
,11-03 23:36:25.018  5572  5619 I jxcore-log: 2016-11-03 22:36:25 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-03 23:36:25.018  5572  5619 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-03 23:36:25.018  5572  5619 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-03 23:36:25.018  5572  5619 I jxcore-log: emit@events.js:82:1
11-03 23:36:25.018  5572  5619 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-03 23:36:25.018  5572  5619 I jxcore-log: emit@events.js:82:1'
11-03 23:36:25.018  5572  5619 I jxcore-log: 
,11-03 23:36:26.051  5572  5619 I jxcore-log: 2016-11-03 22:36:26 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-03 23:36:26.051  5572  5619 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-03 23:36:26.051  5572  5619 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-03 23:36:26.051  5572  5619 I jxcore-log: emit@events.js:82:1
11-03 23:36:26.051  5572  5619 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-03 23:36:26.051  5572  5619 I jxcore-log: emit@events.js:82:1'
11-03 23:36:26.051  5572  5619 I jxcore-log: 
,11-03 23:36:26.057  5572  5619 I jxcore-log: 2016-11-03 22:36:26 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-03 23:36:26.057  5572  5619 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-03 23:36:26.057  5572  5619 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-03 23:36:26.057  5572  5619 I jxcore-log: emit@events.js:82:1
11-03 23:36:26.057  5572  5619 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-03 23:36:26.057  5572  5619 I jxcore-log: emit@events.js:82:1'
11-03 23:36:26.057  5572  5619 I jxcore-log: 
,11-03 23:36:27.085  5572  5619 I jxcore-log: 2016-11-03 22:36:27 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-03 23:36:27.085  5572  5619 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-03 23:36:27.085  5572  5619 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-03 23:36:27.085  5572  5619 I jxcore-log: emit@events.js:82:1
11-03 23:36:27.085  5572  5619 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-03 23:36:27.085  5572  5619 I jxcore-log: emit@events.js:82:1'
11-03 23:36:27.085  5572  5619 I jxcore-log: 
,11-03 23:36:27.093  5572  5619 I jxcore-log: 2016-11-03 22:36:27 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-03 23:36:27.093  5572  5619 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-03 23:36:27.093  5572  5619 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-03 23:36:27.093  5572  5619 I jxcore-log: emit@events.js:82:1
11-03 23:36:27.093  5572  5619 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-03 23:36:27.093  5572  5619 I jxcore-log: emit@events.js:82:1'
11-03 23:36:27.093  5572  5619 I jxcore-log: 
,11-03 23:36:28.118  5572  5619 I jxcore-log: 2016-11-03 22:36:28 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-03 23:36:28.118  5572  5619 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-03 23:36:28.118  5572  5619 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-03 23:36:28.118  5572  5619 I jxcore-log: emit@events.js:82:1
11-03 23:36:28.118  5572  5619 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-03 23:36:28.118  5572  5619 I jxcore-log: emit@events.js:82:1'
11-03 23:36:28.118  5572  5619 I jxcore-log: 
,11-03 23:36:28.122  5572  5619 I jxcore-log: 2016-11-03 22:36:28 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-03 23:36:28.122  5572  5619 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-03 23:36:28.122  5572  5619 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-03 23:36:28.122  5572  5619 I jxcore-log: emit@events.js:82:1
11-03 23:36:28.122  5572  5619 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-03 23:36:28.122  5572  5619 I jxcore-log: emit@events.js:82:1'
11-03 23:36:28.122  5572  5619 I jxcore-log: 
,11-03 23:36:29.150  5572  5619 I jxcore-log: 2016-11-03 22:36:29 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-03 23:36:29.150  5572  5619 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-03 23:36:29.150  5572  5619 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-03 23:36:29.150  5572  5619 I jxcore-log: emit@events.js:82:1
11-03 23:36:29.150  5572  5619 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-03 23:36:29.150  5572  5619 I jxcore-log: emit@events.js:82:1'
11-03 23:36:29.150  5572  5619 I jxcore-log: 
,11-03 23:36:29.154  5572  5619 I jxcore-log: 2016-11-03 22:36:29 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-03 23:36:29.154  5572  5619 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-03 23:36:29.154  5572  5619 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-03 23:36:29.154  5572  5619 I jxcore-log: emit@events.js:82:1
11-03 23:36:29.154  5572  5619 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-03 23:36:29.154  5572  5619 I jxcore-log: emit@events.js:82:1'
11-03 23:36:29.154  5572  5619 I jxcore-log: 
,11-03 23:36:30.183  5572  5619 I jxcore-log: 2016-11-03 22:36:30 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-03 23:36:30.183  5572  5619 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-03 23:36:30.183  5572  5619 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-03 23:36:30.183  5572  5619 I jxcore-log: emit@events.js:82:1
11-03 23:36:30.183  5572  5619 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-03 23:36:30.183  5572  5619 I jxcore-log: emit@events.js:82:1'
11-03 23:36:30.183  5572  5619 I jxcore-log: 
,11-03 23:36:30.194  5572  5619 E jxcore  : Error!: error is undefined
11-03 23:36:30.194  5572  5619 E jxcore  : Stack: [{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/lib/CoordinatedClient.js","_functionName":"CoordinatedClient.prototype._error","_lineNumber":"223","_columnNumber":"1","_msg":"    at CoordinatedClient.prototype._error@/data/data/com.test.thalitest/files/www/jxcore/lib/CoordinatedClient.js:223:1"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/component-emitter/index.js","_functionName":"Emitter.prototype.emit","_lineNumber":"131","_columnNumber":"7","_msg":"    at Emitter.prototype.emit@/data/data/com.test.thalitest/files/www/jxcore/node_modules/component-emitter/index.js:131:7"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/socket.js","_functionName":"Socket.prototype.emit","_lineNumber":"133","_columnNumber":"5","_msg":"    at Socket.prototype.emit@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/socket.js:133:5"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js","_functionName":"Manager.prototype.emitAll","_lineNumber":"81","_columnNumber":"7","_msg":"    at Manager.prototype.emitAll@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:81:7"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js","_functionName":"Manager.prototype.reconnect","_lineNumber":"507","_columnNumber":"5","_msg":"    at Manager.prototype.reconnect@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:507:5"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js","_functionName":"Manager.prototype.reconnect/timer</<","_lineNumber":"528","_columnNumber":"11","_msg":"    at Manager.prototype.reconnect/timer</<@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:528:11"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js","_functionName":"Manager.prototype.connect/errorSub<","_lineNumber":"235","_columnNumber":"7","_msg":"    at Manager.prototype.connect/errorSub<@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:235:7"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/node_modules/component-emitter/index.js","_functionName":"Emitter.prototype.emit","_lineNumber":"134","_columnNumber":"7","_msg":"    at Emitter.prototype.emit@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/node_modules/component-emitter/index.js:134:7"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/socket.js","_functionName":"Socket.prototype.onError","_lineNumber":"670","_columnNumber":"3","_msg":"    at Socket.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/socket.js:670:3"}]
,11-03 23:36:30.197  5572  5619 I jxcore-log: 2016-11-03 22:36:30 - ERROR TestsProcess: 'uncaught exception, error: 'TypeError: error is undefined', stack: 'TypeError: error is undefined
11-03 23:36:30.197  5572  5619 I jxcore-log:     at CoordinatedClient.prototype._error@/data/data/com.test.thalitest/files/www/jxcore/lib/CoordinatedClient.js:223:1
11-03 23:36:30.197  5572  5619 I jxcore-log:     at Emitter.prototype.emit@/data/data/com.test.thalitest/files/www/jxcore/node_modules/component-emitter/index.js:131:7
11-03 23:36:30.197  5572  5619 I jxcore-log:     at Socket.prototype.emit@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/socket.js:133:5
11-03 23:36:30.197  5572  5619 I jxcore-log:     at Manager.prototype.emitAll@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:81:7
11-03 23:36:30.197  5572  5619 I jxcore-log:     at Manager.prototype.reconnect@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:507:5
11-03 23:36:30.197  5572  5619 I jxcore-log:     at Manager.prototype.reconnect/timer</<@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:528:11
11-03 23:36:30.197  5572  5619 I jxcore-log:     at Manager.prototype.connect/errorSub<@/data/data/com.test.thalitest/files/www/jxcore/node_modules/sock
,11-03 23:36:30.199  5572  5619 I jxcore-log: 2016-11-03 22:36:30 - ERROR TestsProcess: '****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****'
11-03 23:36:30.199  5572  5619 I jxcore-log: 
11-03 23:36:30.200  5572  5619 E jxcore-log: TypeError: 
11-03 23:36:30.201  5572  5619 E jxcore-log: error is undefined
11-03 23:36:30.201  5572  5619 E jxcore-log:  (/data/data/com.test.thalitest/files/www/jxcore/lib/CoordinatedClient.js 223:0)
11-03 23:36:30.201  5572  5619 E jxcore-log: 
,11-03 23:36:30.266   928  2948 W InputDispatcher: channel 'ada7c64 com.test.thalitest/com.test.thalitest.MainActivity (server)' ~ Consumer closed input channel or an error occurred.  events=0x9
,11-03 23:36:30.267   928  2948 E InputDispatcher: channel 'ada7c64 com.test.thalitest/com.test.thalitest.MainActivity (server)' ~ Channel is unrecoverably broken and will be disposed!
11-03 23:36:30.276   928  2959 D WifiService: Client connection lost with reason: 4
11-03 23:36:30.276   928   939 D GraphicsStats: Buffer count: 2
11-03 23:36:30.276   928  3812 I WindowState: WIN DEATH: Window{ada7c64 u0 com.test.thalitest/com.test.thalitest.MainActivity}
11-03 23:36:30.277   928  3812 W InputDispatcher: Attempted to unregister already unregistered input channel 'ada7c64 com.test.thalitest/com.test.thalitest.MainActivity (server)'
,11-03 23:36:30.289   527   527 I Zygote  : Process 5572 exited cleanly (139)
,11-03 23:36:30.293   928  3166 I ActivityManager: Process com.test.thalitest (pid 5572) has died
,11-03 23:36:30.309   928  3166 I ActivityManager: Start proc 5905:com.test.thalitest/u0a77 for activity com.test.thalitest/.MainActivity
,11-03 23:36:30.392  5905  5905 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011750)
,11-03 23:36:30.412  5905  5905 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,11-03 23:36:30.417  5905  5905 I LibraryLoader: Time to load native libraries: 2 ms (timestamps 3850-3852)
,11-03 23:36:30.417  5905  5905 I LibraryLoader: Expected native library version number "",actual native library version number ""
,11-03 23:36:30.426  5905  5905 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {35640bf}
,11-03 23:36:30.427  5905  5905 I LibraryLoader: Expected native library version number "",actual native library version number ""
11-03 23:36:30.427  5905  5905 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,11-03 23:36:30.430  5905  5905 I BrowserStartupController: Initializing chromium process, singleProcess=true
,11-03 23:36:30.431  5905  5905 E SysUtils: ApplicationContext is null in ApplicationStatus
,11-03 23:36:30.441  5905  5905 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,11-03 23:36:30.449  5905  5905 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,11-03 23:36:30.449  5905  5905 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
11-03 23:36:30.450  5905  5905 I Adreno  : QUALCOMM build                   : 63c06b2, I8366cd0437
11-03 23:36:30.450  5905  5905 I Adreno  : Build Date                       : 12/06/15
11-03 23:36:30.450  5905  5905 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
11-03 23:36:30.450  5905  5905 I Adreno  : Local Branch                     : mybranch17112971
11-03 23:36:30.450  5905  5905 I Adreno  : Remote Branch                    : quic/LA.BF64.1.2.9_v2
11-03 23:36:30.450  5905  5905 I Adreno  : Remote Branch                    : NONE
11-03 23:36:30.450  5905  5905 I Adreno  : Reconstruct Branch               : NOTHING
,11-03 23:36:30.481   928   945 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@b742750:true
,11-03 23:36:30.496  3051  3051 W Binder_5: type=1400 audit(0.0:123): avc: denied { ioctl } for path="socket:[15851]" dev="sockfs" ino=15851 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-03 23:36:30.496  3051  3051 W Binder_5: type=1400 audit(0.0:124): avc: denied { ioctl } for path="socket:[15851]" dev="sockfs" ino=15851 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-03 23:36:30.509  5905  5905 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,11-03 23:36:30.517  5905  5905 D SystemWebViewEngine: CordovaWebView is running on device made by: Huawei
,11-03 23:36:30.543  3051  3051 W Binder_5: type=1400 audit(0.0:125): avc: denied { ioctl } for path="socket:[36024]" dev="sockfs" ino=36024 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-03 23:36:30.543  3051  3051 W Binder_5: type=1400 audit(0.0:126): avc: denied { ioctl } for path="socket:[36024]" dev="sockfs" ino=36024 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
11-03 23:36:30.547  5905  5941 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,11-03 23:36:30.549  3682  3682 W Binder_8: type=1400 audit(0.0:127): avc: denied { ioctl } for path="socket:[36898]" dev="sockfs" ino=36898 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-03 23:36:30.549  3682  3682 W Binder_8: type=1400 audit(0.0:128): avc: denied { ioctl } for path="socket:[36898]" dev="sockfs" ino=36898 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-03 23:36:30.553  5905  5928 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,11-03 23:36:30.594  5905  5941 I OpenGLRenderer: Initialized EGL, version 1.4
,11-03 23:36:30.622   928   946 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +285ms (total +324ms)
,11-03 23:36:30.619   938   938 W Binder_1: type=1400 audit(0.0:129): avc: denied { ioctl } for path="socket:[34232]" dev="sockfs" ino=34232 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-03 23:36:30.623   928   938 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 5572 uid 10077
11-03 23:36:30.619   938   938 W Binder_1: type=1400 audit(0.0:130): avc: denied { ioctl } for path="socket:[34232]" dev="sockfs" ino=34232 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-03 23:36:30.619  3682  3682 W Binder_8: type=1400 audit(0.0:131): avc: denied { ioctl } for path="socket:[34231]" dev="sockfs" ino=34231 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
11-03 23:36:30.619  3682  3682 W Binder_8: type=1400 audit(0.0:132): avc: denied { ioctl } for path="socket:[34231]" dev="sockfs" ino=34231 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-03 23:36:30.626  3651  3651 I Keyboard.Facilitator: onFinishInput()
,11-03 23:36:30.628  5905  5905 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 5905
,11-03 23:36:30.707  5905  5905 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,11-03 23:36:30.716  5903  5903 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,11-03 23:36:30.731  5903  5903 D AndroidRuntime: CheckJNI is OFF
,11-03 23:36:30.753  5903  5903 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,11-03 23:36:30.778  5903  5903 I Radio-JNI: register_android_hardware_Radio DONE
,11-03 23:36:30.793  5903  5903 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,11-03 23:36:30.798   928   941 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=-1: uninstall pkg
,11-03 23:36:30.798   928   941 I ActivityManager: Killing 5905:com.test.thalitest/u0a77 (adj 0): stop com.test.thalitest
,11-03 23:36:30.830   928  3812 D GraphicsStats: Buffer count: 2
11-03 23:36:30.830   928  3434 I WindowState: WIN DEATH: Window{73d565f u0 com.test.thalitest/com.test.thalitest.MainActivity}
,11-03 23:36:30.897   928   941 W ActivityManager: Failed trying to unstop package com.test.thalitest: java.lang.IllegalArgumentException: Unknown package: com.test.thalitest
11-03 23:36:30.897   928   941 W PackageManager: Package com.test.thalitest is missing; assuming frozen
,11-03 23:36:30.898   928   941 E ActivityManager: Failure starting process com.test.thalitest
11-03 23:36:30.898   928   941 E ActivityManager: java.lang.RuntimeException: Package com.test.thalitest is frozen!
11-03 23:36:30.898   928   941 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3278)
11-03 23:36:30.898   928   941 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3237)
11-03 23:36:30.898   928   941 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3116)
11-03 23:36:30.898   928   941 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1395)
11-03 23:36:30.898   928   941 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:2007)
11-03 23:36:30.898   928   941 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1554)
11-03 23:36:30.898   928   941 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2735)
11-03 23:36:30.898   928   941 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2724)
11-03 23:36:30.898   928   941 E ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4598)
11-03 23:36:30.898   928   941 E ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:5955)
11-03 23:36:30.898   928   941 E ActivityManager: 	at com.android.server.am.ActivityManagerService.killPackageProcessesLocked(ActivityManagerService.java:5614)
11-03 23:36:30.898   928   941 E ActivityManager: 	at com.android.server.am.ActivityManagerService.forceStopPackageLocked(ActivityManagerService.java:5763)
11-03 23:36:30.898   928   941 E ActivityManager: 	at com.android.server.am.ActivityManagerService.-wrap1(ActivityManagerService.java)
11-03 23:36:30.898   928   941 E ActivityManager: 	at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:1736)
11-03 23:36:30.898   928   941 E ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-03 23:36:30.898   928   941 E ActivityManager: 	at android.os.Looper.loop(Looper.java:148),
11-03 23:36:30.898   928   941 E ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
11-03 23:36:30.898   928   941 E ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
,11-03 23:36:30.899   928   941 I ActivityManager:   Force finishing activity ActivityRecord{2285b6c u0 com.test.thalitest/.MainActivity t68}
11-03 23:36:30.901   928   951 I art     : Starting a blocking GC Explicit
,11-03 23:36:30.906   928   939 W ActivityManager: Spurious death for ProcessRecord{817a975 0:com.test.thalitest/u0a77}, curProc for 5905: null
,11-03 23:36:30.979   928   951 I art     : Explicit concurrent mark sweep GC freed 12784(849KB) AllocSpace objects, 2(40KB) LOS objects, 33% free, 29MB/43MB, paused 1.593ms total 78.196ms
,11-03 23:36:30.997   928   951 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,11-03 23:36:31.000  5903  5903 I art     : System.exit called, status: 0
,11-03 23:36:31.000  5903  5903 I AndroidRuntime: VM exiting with result code 0.
,11-03 23:36:31.014   928   951 I ActivityManager: Start proc 5955:com.android.defcontainer/u0a7 for service com.android.defcontainer/.DefaultContainerService
11-03 23:36:31.015   928   951 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=0: pkg removed
,11-03 23:36:31.018   928   941 I ActivityManager: Exiting empty application process com.test.thalitest (null)
,11-03 23:36:31.022  5805  5805 D BluetoothMapAppObserver: onReceive
,11-03 23:36:31.022  5805  5805 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
11-03 23:36:31.024  3843  4126 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
11-03 23:36:31.033  3651  3651 I Keyboard.Facilitator: resetDictionaries() : en_US
11-03 23:36:31.034   928  2949 I InputReader: Reconfiguring input devices.  changes=0x00000010
,11-03 23:36:31.053  3419  5969 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,11-03 23:36:31.055  3651  5967 I Keyboard.Facilitator.DecoderInitializer: run()
,11-03 23:36:31.079  3785  3785 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,11-03 23:36:31.084   928   928 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,11-03 23:36:31.086  3651  5967 I Decoder : createOrResetDecoder
,11-03 23:36:31.089    13    13 W kworker/1:0: type=1400 audit(0.0:133): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-03 23:36:31.093    13    13 W kworker/1:0: type=1400 audit(0.0:134): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-03 23:36:31.101   928   940 E PackageManager: Failed to write settings, restoring backup
11-03 23:36:31.101   928   940 E PackageManager: java.io.IOException: write failed: EBADF (Bad file descriptor)
11-03 23:36:31.101   928   940 E PackageManager: 	at libcore.io.IoBridge.write(IoBridge.java:498)
11-03 23:36:31.101   928   940 E PackageManager: 	at java.io.FileOutputStream.write(FileOutputStream.java:186)
11-03 23:36:31.101   928   940 E PackageManager: 	at java.io.OutputStreamWriter.flushBytes(OutputStreamWriter.java:170)
11-03 23:36:31.101   928   940 E PackageManager: 	at java.io.OutputStreamWriter.convert(OutputStreamWriter.java:184)
11-03 23:36:31.101   928   940 E PackageManager: 	at java.io.OutputStreamWriter.write(OutputStreamWriter.java:269)
11-03 23:36:31.101   928   940 E PackageManager: 	at java.io.BufferedWriter.write(BufferedWriter.java:236)
11-03 23:36:31.101   928   940 E PackageManager: 	at org.kxml2.io.KXmlSerializer.attribute(KXmlSerializer.java:468)
11-03 23:36:31.101   928   940 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.writePermissionsSync(Settings.java:4644)
11-03 23:36:31.101   928   940 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.-wrap1(Settings.java)
11-03 23:36:31.101   928   940 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence$MyHandler.handleMessage(Settings.java:4830)
11-03 23:36:31.101   928   940 E PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-03 23:36:31.101   928   940 E PackageManager: 	at android.os.Looper.loop(Looper.java:148)
11-03 23:36:31.101   928   940 E PackageManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
11-03 23:36:31.101   928   940 E PackageManager: Caused by: android.system.ErrnoException: write failed: EBADF (Bad file descriptor)
11-03 23:36:31.101   928   940 E PackageManager: 	at libcore.io.Posix.writeBytes(Native Method)
11-03 23:36:31.101   928   940 E PackageManager: 	at libcore.io.Posix.write(Posix.java:271)
11-03 23:36:31.101   928   940 E PackageManager: 	at libcore.io.BlockGuardOs.write(BlockGuardOs.java:313)
11-03 23:36:31.101   928   940 E PackageManager: 	at libcore.io.IoBridge.write(IoBridge.java:493)
11-03 23:36:31.101   928   940 E PackageManager: 	... 12 more
,11-03 23:36:31.106  3596  3596 E SQLiteLog: (3850) statement aborts at 26: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
,11-03 23:36:31.107  3596  3596 D AndroidRuntime: Shutting down VM
,--------- beginning of crash
11-03 23:36:31.107  3596  3596 E AndroidRuntime: FATAL EXCEPTION: main
11-03 23:36:31.107  3596  3596 E AndroidRuntime: Process: com.google.process.gapps, PID: 3596
11-03 23:36:31.107  3596  3596 E AndroidRuntime: java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
11-03 23:36:31.107  3596  3596 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2732)
11-03 23:36:31.107  3596  3596 E AndroidRuntime: 	at android.app.ActivityThread.-wrap14(ActivityThread.java)
11-03 23:36:31.107  3596  3596 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1421)
11-03 23:36:31.107  3596  3596 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-03 23:36:31.107  3596  3596 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
11-03 23:36:31.107  3596  3596 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-03 23:36:31.107  3596  3596 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
11-03 23:36:31.107  3596  3596 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-03 23:36:31.107  3596  3596 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-03 23:36:31.107  3596  3596 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
11-03 23:36:31.107  3596  3596 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
11-03 23:36:31.107  3596  3596 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
11-03 23:36:31.107  3596  3596 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
11-03 23:36:31.107  3596  3596 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
11-03 23:36:31.107  3596  3596 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
11-03 23:36:31.107  3596  3596 E AndroidRuntime: 	at com.google.android.gms.gcm.bg.a(SourceFile:310)
11-03 23:36:31.107  3596  3596 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
11-03 23:36:31.107  3596  3596 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
11-03 23:36:31.107  3596  3596 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2725)
11-03 23:36:31.107  3596  3596 E AndroidRuntime: 	... 8 more
,11-03 23:36:31.113   928  3434 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 5905 uid 10077
,11-03 23:36:31.114  3651  3651 I Keyboard.Facilitator: onFinishInput()
,11-03 23:36:31.109  3434  3434 W Binder_5: type=1400 audit(0.0:135): avc: denied { ioctl } for path="socket:[14603]" dev="sockfs" ino=14603 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-03 23:36:31.109  3434  3434 W Binder_5: type=1400 audit(0.0:136): avc: denied { ioctl } for path="socket:[14603]" dev="sockfs" ino=14603 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-03 23:36:31.116    13    13 W kworker/1:0: type=1400 audit(0.0:137): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-03 23:36:31.125   928  3780 I ActivityManager: Start proc 5975:com.google.android.googlequicksearchbox:crash_report/u0a29 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
,11-03 23:36:31.125  3798  3910 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
11-03 23:36:31.125  3798  3910 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 3798
11-03 23:36:31.125  3798  3910 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 778)
11-03 23:36:31.125  3798  3910 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
11-03 23:36:31.125  3798  3910 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
11-03 23:36:31.125  3798  3910 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
11-03 23:36:31.125  3798  3910 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
11-03 23:36:31.125  3798  3910 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
11-03 23:36:31.125  3798  3910 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
11-03 23:36:31.125  3798  3910 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
11-03 23:36:31.125  3798  3910 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
11-03 23:36:31.125  3798  3910 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
11-03 23:36:31.125  3798  3910 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
11-03 23:36:31.125  3798  3910 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,11-03 23:36:31.131  3596  3596 I Process : Sending signal. PID: 3596 SIG: 9
,11-03 23:36:31.131   928  3167 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,11-03 23:36:31.132   928  5985 E DropBoxManagerService: Can't write: system_app_crash
11-03 23:36:31.132   928  5985 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop126.tmp: open failed: EROFS (Read-only file system)
11-03 23:36:31.132   928  5985 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
11-03 23:36:31.132   928  5985 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
11-03 23:36:31.132   928  5985 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
11-03 23:36:31.132   928  5985 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
11-03 23:36:31.132   928  5985 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
11-03 23:36:31.132   928  5985 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
11-03 23:36:31.132   928  5985 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
11-03 23:36:31.132   928  5985 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
11-03 23:36:31.132   928  5985 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
11-03 23:36:31.132   928  5985 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
11-03 23:36:31.132   928  5985 E DropBoxManagerService: 	... 5 more
11-03 23:36:31.136  3798  3910 I Process : Sending signal. PID: 3798 SIG: 9
,11-03 23:36:31.146  3419  3444 E SQLiteLog: (2570) os_unix.c:31406: (30) unlink(/data/user/0/com.android.providers.contacts/databases/contacts2.db-mj9F7E7D9B0) - 
,11-03 23:36:31.163   928  2959 D WifiService: Client connection lost with reason: 4
,11-03 23:36:31.168   928   939 I ActivityManager: Process com.google.process.gapps (pid 3596) has died
,11-03 23:36:31.169   928   939 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.clearcut.service.ClearcutLoggerService in 1000ms
,11-03 23:36:31.169   928   939 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.tapandpay.hce.service.TpHceService in 11000ms
11-03 23:36:31.169   928   939 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.gcm.GcmService in 21000ms
,11-03 23:36:31.184   928  3434 I ActivityManager: Start proc 5988:com.google.process.gapps/u0a12 for service com.google.android.gms/.config.ConfigService

```
